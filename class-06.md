# Class 6

### JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with? 
    - Objects are a collection of related data and/or functionality.
2. What are some advantages to creating object literals?
    - It is easier to work with than an array and when you want to identify items by name.
3. How do objects differ from arrays?
    -
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    -  instead of using an index number to select an item, you are using the name associated with each member's value.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
    - when using color: object we can define it with a name in regards to calling it out later on its easier to specify.

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

### Introduction To The DOM

1. What is the DOM?
    - Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. 
2. Briefly describe the relationship between the DOM and JavaScript
    - JavaScripted webpages uses DOM to access the document and its elements. Without the DOM JavaScript wouldnt be able to have any model or notion of the webpage.