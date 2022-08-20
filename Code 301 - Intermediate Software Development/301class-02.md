## State and Props

## React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
    - ‘render’ will happen before ‘componentDidMount’
2. What is the very first thing to happen in the lifecycle of React?
    - Mounting -> Constructor -> static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    1. Constructor
    2. render
    3. componentDidMount
    4. React Updates
    5. componentWillUnmount
4. What does componentDidMount do?
    - load anything using a network request or initialize the DOM
---
Notes: 
Mounting, Updating, and Unmounting are the three phases of the component lifecycle.
Mounting: When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.
Updating: Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
Unmounting: The final phase of the lifecycle if called when a component is being removed from the DOM.
Constructor: Constructors can be used to assign state using this.state or to bind event handle methods to an instance. Let’s take a look at some example code.

## Videos
## React State Vs Props

1. What types of things can you pass in the props?
2. What is the big difference between props and state?
    - Props you pass into a component. handled outside of the component // State is handled inside of the component.
3. When do we re-render our application?
    - Change something in our application when we use State.
4. What are some examples of things that we could store in state?
    - counter, user input, form, checkbox, 

## Bookmark and Review
[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[React Docs - handling events](https://reactjs.org/docs/handling-events.html)
[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)