# Reading
## react hello world

1. What are the building blocks of a React app?
  - Elements are the smallest building blocks of React Apps.
2. What is the difference between an element and a React component?
  - React elements are plain objects and cheap to create.
3. What are some advantages of React’s component based architecture?
  - lets you split the UI into independent, reusable pieces.

## introducing JSX

1. What is JSX and why do we use it?
  - JSX produces react elements, we use it with React to help visualize things. 
2. Describe the process of embedding JavaScript expressions in JSX.
    const name = 'Josh Perez';
    const element = <h1>Hello, {name}</h1>; <----- use of {} is JSX
3. Is it safe to embed user input in JSX? Explain.
  - I dont think it would be good to inbed a user.

## rendering elements

1. Explain what a React Component is to a non-technical friend.
  - things that help describe what you seen on your screen. 
2. Describe mutability and React Components, specifically, how is the UI updated?
  - React elements are immutable. Once you create an element, you can’t change its children or attributes. An element is like a single frame in a movie: it represents the UI at a certain point in time.

With our knowledge so far, the only way to update the UI is to create a new element, and pass it to root.render().
--------
EX: 
const root = ReactDOM.createRoot(
document.getElementById('root')
);

function tick() {
  const element = (
    <div>
      <h1>Hello, world!</h1>
      <h2>It is {new Date().toLocaleTimeString()}.</h2>
    </div>
  );
  root.render(element);
}

setInterval(tick, 1000);
--------
3. If changes are made to the UI, what does React update?
  - React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.

### Bookmark and Review
sass cheatsheet
react cheatsheet
another react cheatsheet
Additional Questions
Looking ahead at this module’s course schedule, What do you look forward to learning?
What are your learning goals after reading and reviewing the class README?