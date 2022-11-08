# Reading

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. Why create multiple reducers?
  -Having one giant reducer is hard to maintain. So having multiple smaller ones is the way to go.
2. How would you combine multiple reducers?
  -With the combineReducers method.
3. How will you manage state as an immutable object? why?

## [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. combineReducers is a utility function to simplify the most common use case when writing Redux Reducers_ .
2. Explain how combineReducers assembles the new state tree.
  -combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed. So, in that sense, using combineReducers does "call all reducers", or at least all of the slice reducers it is wrapping.
3. How would you define initial state in an app using combineReducers?
  -takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys. This means that if no preloaded state is provided to createStore, the naming of the keys in the input slice reducer object will define the naming of the keys in the output state object. The correlation between these names is not always apparent, especially when using ES6 features such as default module exports and object literal shorthands.

  -In my understanding this will create a state if no preloaded state is provided to createStore.

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. Why will you want to split your reducing functions as your app becomes more complex?
  -Having one large reducer will make managing state hard to see and find in the large reducer function, instead by breaking it down and looking at each individual piece will help reduce the noise in what each reducer does and how it functions.
2. The _**combbineReducers**_ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to __**createStore**__.
3. What is a popular convention when naming reducers?
  -Is to name reducers after the state slices they manage,

### Reflection

What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-37/)
  -Combined reducers is nothing more than pulling in more than one reducer from source and creating a keyed object from them.
````
  import todoReducer from './todo.store.js';
import itemReducer from './item.store.js';

let reducers = combineReducers({
  todo: todoReducer,
  item: itemReducer,
});
````
-Each reducer really should have only 1 part of state to manage
````
// YES:
const initialState = { value: 0 };

// NO:
const initialState = { value: 0, numChanges:0, changes:[] };
  // Move those to separate reducers/actions
````

