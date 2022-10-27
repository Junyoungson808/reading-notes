# Reading
## [useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

(state, action) => newState

1. Name an alternative to the useState Hook.
  - useReducer: is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
2. Why might the useReducer Hook be preferable to the useState Hook?
  - when you have complex state logic that involves multiple sub-values or when the next state depends on the previos one.
3. What are two ways to set the initial state?
  1. The simplest way is to pass the initial state as a second argument:
  2. You can also create the initial state lazily. To do this, you can pass an init function as the third argument. The initial state will be set to init(initialArg).

## [Ultimate Guide to useReducer](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)

1. In terms of state, what does useReducer expect to receive as a parameter?
  - a reducer function
2. What does useReducer return?
  - an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it.
3. Explain dispatch to a non-technical recruiter.
  - Dispatch method is similar to setState, it updates state.

### Reflection
- What are your learning goals after reading and reviewing the class README?
  - Hopefully oneday I can look back at all this and understand what I wrote and read.