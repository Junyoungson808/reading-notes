# Reading
## [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

1. Explain middleware, answer as though I were a non-technical recruiter.
    - Middleware is a term for any software that enables communication from parts of a system and to manage data.
2. Express the most popular _Node_Web_Framwork_.
3. Express is “unopinionated.” What does that mean?
    - You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure. You may sometimes feel that you have too many choices!
4. What is a module and why is modularity useful to us as developers?
    - Is a JavaScript library/file, We can use these librarys to create apps without recreating them. 

    const express = require("express");
    const app = express();

## [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

1. What version of npm are you running on your machine?
    - 8.19.1
2. What command would you type to install a library/package called ‘jshint’ into your node project?
    - npm i jshint

## [What is TDD?](https://www.agilealliance.org/glossary/tdd/)

1. Explain why tests are important. Please explain as though I were your non technical elder.
    - Tests are there to make sure our app does what we expect it to. We also need to make sure what we test is also gives us the results we are looking for. In the cases it doesn't we can figure out and fix bugs in our application.
2. What are three expected benefits of testing
    1. significant reductions in defect rates
    2. reduction in effort in final phase of projects
    3. leads to improved design qualities in the code, higher degree of internal or technical quality. 
3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
    - Individual:
        1. writing to many tests at once
        2. writing overly tirvial tests
    - Team:
        1. partial adoption
        2. poor maintenance of the test suite

## [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

1. What are three benefits of Continuous Integration?
    1. Ensure everyones changes integrate
    2. Catch bugs
    3. reduce merge conflicts
2. What is the difference between Continuos Delivery and Continuous Deployment?
    - Developing software in a way that it could be released anytime VS Deploy new features Immediately
3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background
    - Github is a clearing house for your code. Github uses **webhooks**:send messages to external systems about activity in your projects.

## Bookmark and Review
[nodeJS docs](https://nodejs.org/en/docs/)
[npm docs](https://docs.npmjs.com/)
[express docs](https://expressjs.com/en/4x/api.html)
[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
[supertest](https://github.com/visionmedia/supertest)