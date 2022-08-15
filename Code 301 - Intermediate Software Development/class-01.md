## Introduction to React and Components

### Component-Based Architecture
1. What is a “component”? 
    - A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.
2. What are the characteristics of a component?
    1. **Reusability** − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
    2. **Replaceable** − Components may be freely substituted with other similar components.
    Not context specific − Components are designed to operate in different environments and contexts.
    3. **Extensible** − A component can be extended from existing components to provide new behavior.
    4. **Encapsulated** − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
    5. **Independent** − Components are designed to have minimal dependencies on other components.
3. What are the advantages of using component-based architecture?
    1. **Ease of deployment** − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.
    2. **Reduced cost** − The use of third-party components allows you to spread the cost of development and maintenance.
    3. **Ease of development** − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.
    4. **Reusable** − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.
    5. **Modification of technical complexity** − A component modifies the complexity through the use of a component container and its services.
    6. **Reliability** − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.
    7. **System maintenance and evolution** − Easy to change and update the implementation without affecting the rest of the system.
    8. **Independent** − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

###  What is Props and How to Use it in React
1. What is “props” short for?
    - Properties
2. How are props used in React?
    - They are used for passing data from one component to another (**prop data is read only**)
3. What is the flow of props?
    - The flow of props flows **uni-directional (downward)**

### Bookmark and Review
React Tutorial through ‘Passing Data Through Props’ https://reactjs.org/tutorial/tutorial.html
React Docs - Hello world https://reactjs.org/docs/hello-world.html
React Docs - Introducing JSX https://reactjs.org/docs/introducing-jsx.html
React Docs - Rendering elements https://reactjs.org/docs/rendering-elements.html
React Docs - Components and props https://reactjs.org/docs/components-and-props.html