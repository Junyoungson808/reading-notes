# Reading
## [async actions](https://redux.js.org/advanced/asyncactions)

1. Why use Redux middleware?
  -Redux middleware were designed to enable writing logic that has side effects.
2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
  -User deposits money, that goes to the event handler, that dispatches the event, goes to the middleware that sends it to the api, awaits a response and then dispatches to the store, as it sends it off reducer, state also sends off to the reducer function and then fires back with the new state, then that moves back to the user?
3. How are we accommodating async in our Redux app?
  -by implementing a middleware

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

1. Why would you need redux-thunk middleware?
  -With a plain basic Redux store, you can only do simple synchronous updates by dispatching an action. Middleware extends the store's abilities, and lets you write async logic that interacts with the store.
2. Redux Thunk middleware allows you to write action creators that return a **function** instead of an action.
3. Describe how any return value from the inner thunk function will be made available.
  -The inner thunk will take in the dispatch and getstate as parameters and returns a function that allows for more uses and side effects.

### Reflection
What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-38/)