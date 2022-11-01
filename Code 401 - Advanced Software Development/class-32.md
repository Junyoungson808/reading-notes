# Reading

## [Hooks and Context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

1. With regard to the React Context API, what does a “provider” do?

- Provides both display of local state and exposing an API for globally managing them.

2. With regard to the React Context API, how would we implement a “consumer” role?

- we need a consumer to the provider, by importing useContext to the consumer parts (children).

3. Specifically with Context, how are we “wrapping” components to achieve our goals?

- import { useContext } from 'react'

## [Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
    - [Takeaway 1](https://github.com/drcmda/react-contextual/blob/master/API.md#subscribe):

    This because we just learned provider and I would like to understand it more and more uses for it.
  Provider
import { Provider } from 'react-contextual'
A small Redux-like store. Declare props that represents the state and actions on the state. The provider will distribute the state and actions as props to listening components which either use React's API directly or contextual's subscribe hoc to consume it. Alternatively you can pass an external store by the store props.

The actions on the state are basically functions which return an object that is going to be merged back into the state using regular setState semantics.

They can be simple ...

setName: name => ({ name }),

    - [Takeaway 2](https://redux.js.org/introduction/getting-started): 

    Since Robert mentioned this in class I thought I look into it. It looks similar to useContext and what we are learning now, but putting state into one single store.
    
    # NPM
npm install @reduxjs/toolkit

The whole global state of your app is stored in an object tree inside a single store. The only way to change the state tree is to create an action, an object describing what happened, and dispatch it to the store. To specify how state gets updated in response to an action, you write pure reducer functions that calculate a new state based on the old state and the action.


## Reflection

1. What are your learning goals after reading and reviewing the class README?
  Hope to cram all im reading into long term knowledge. 
