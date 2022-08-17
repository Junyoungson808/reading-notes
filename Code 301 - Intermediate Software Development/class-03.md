### Readings: Passing Functions as Props

### React Docs - lists and keys

1. What does .map() return?
    - A map object, which is an iterator that yields items on demand.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
    - Not sure....
3. Each list item needs a unique _KEY_.
4. What is the purpose of a key?
    - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

### The Spread Operator

1. What is the spread operator?
    - Is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
2. List 4 things that the spread operator can do.
    1. Copying an array
    2. Concatenating or combining arrays
    3. Using Math functions
    4. Using an array as arguments
    5. Adding an item to a list
    6. Adding to state in React
    7. Combining objects
    8. Converting NodeList to an array
3. Give an example of using the spread operator to combine two arrays.
----
    1. const objectOne = {hello: "🤪"}
    const objectTwo = {world: "🐻"}
    const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
    console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
    const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
    objectFour.laugh() // 😂😂😂😂😂
----
4. Give an example of using the spread operator to add a new item to an array.
    not sure...
5. Give an example of using the spread operator to combine two objects into one.
    not sure...

### Videos
### How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
    - he creates a function, in this case he created "increment" 
    increment = (name) => {
        let ppl = this.state.people.map( (p) = {
            if(p.name === name){
                p.count++;
            }
            return p;
        })
        this.setState({people: ppl});
    }
2. In your own words, what does the increment function do?
    - Lost in the explanation.
3. How can you pass a method from a parent component into a child component?
    - by bringing it in by with props.
4. How does the child component invoke a method that was passed to it from a parent component?
    - 


### Bookmark and Review
[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)