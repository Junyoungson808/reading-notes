### React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
   - That is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
2. What does it mean to build a ‘static’ version of your application?
   - build components that reuse other components and pass data using props. props are a way of passing data from parent to child.
3. Once you have a static application, what do you need to add?
   - State
4. What are the three questions you can ask to determine if something is state?
   1. Is it passed in from a parent via props? If so, it probably isn’t state.
   2. Does it remain unchanged over time? If so, it probably isn’t state.
   3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
5. How can you identify where state needs to live?

### Higher-Order Functions

1. What is a “higher-order function”?
   - Functions that operate on other functions, either by taking them as arguments or by returning them
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
   - it is a boolen function
3. Explain how either map or reduce operates, with regards to higher-order functions.
   - I don't understand this... 

----------------
function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
---------------
function map(array, transform) {
  let mapped = [];
  for (let element of array) {
    mapped.push(transform(element));
  }
  return mapped;
}
----------------
function reduce(array, combine, start) {
  let current = start;
  for (let element of array) {
    current = combine(current, element);
  }
  return current;
}

console.log(reduce([1, 2, 3, 4], (a, b) => a + b, 0));
// → 10