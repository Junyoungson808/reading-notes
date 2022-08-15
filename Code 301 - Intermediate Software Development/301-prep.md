# Dive Into React
https://www.youtube.com/watch?v=FRjlF74_EZk

What is React?
- A user interface library. (agnostic)

---
App.js
import React from 'react';
import ReactDOM from 'react-dom';
import Header from '/Header';
import Content from '/Content';
import Footer from '/Footer';

function App() (
    <div className = "app">
        <Header />
        <Content />
        <Footer />
    </div>
);

ReactDom.render(
    <App />,
    document.getElementById("root")
);
---
What is a component?
- Certain part of code that fills up the userface that builds up react

What is the dataflow of React?
- Down from a component to its children

How do we make a React element a DOM element?

React is a User Interface ***library**.

Which direction does data flow in React?
Data flows **down** **one way** through a React App.

Every component manages its own **state and pass it down to its children.**