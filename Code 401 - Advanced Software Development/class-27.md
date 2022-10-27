# Reading

## [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. What was the motivation for introducing Hooks? 
  - The problems with unconnected problems.
2. What changes are important regarding implementing Hooks versus Component Classes?
  - With Hooks, you can extract stateful logic from a component so it can be tested independently and reused.
3. Hooks allow you to reuse stateful logic without changing _component hierarchy_.

## [hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Name two rules imposed by React Hook usage.
  1. Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
  2. Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)
2. How would you identify a custom Hook and why might you create one?
  - they start with "use" and are state/effect/ or the standard hook but a custom named one. Create one when creating animation, decaltive subscriptions, timers, and many more. 

## [the state hook](https://reactjs.org/docs/hooks-state.html)

1. What is a Hook?
  - A Hook is a special function that lets you “hook into” React features.
2. When would I use the useState Hook?
  - If you write a function component and realize you need to add some state to it, previously you had to convert it to a class.
3. If you were to add React state to a function component by declaring a state variable:
  1. What does calling useState do? 
    - useState is a hook to directly hook into the component. Calls a "state variable"
  2. What do we pass to useState as an argument?
    - The only argument to the useState() Hook is the initial state
  3. What does useState return?
    - It returns a pair of values: the current state and a function that updates it. 

## Bookmark and Review

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)

## Reflection

What are your learning goals after reading and reviewing the class README?
