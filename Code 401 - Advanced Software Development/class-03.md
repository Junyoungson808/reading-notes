# Readings

## [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1. Classes are a template for creating **OBJECTS.**
2. Can a class declaration be hoisted? ==NO==
    - Classes must be defined before they can be constructed.

        const p = new Rectangle(); // ReferenceError
        class Rectangle {}

3. How would you describe a constructor and contextual “this” to a non-technical friend?
    - Constructor is a method for creating and initializing an object created with a class.
    **This** in a constructor refers to objects inside the constructor method.

class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
}

## [Using Express Routing](https://expressjs.com/en/guide/routing.html)

1. Within Express, what does routing refer to?
    - refers to how an application’s endpoints (URIs) respond to client requests.
2. What is the difference between a route path and a route method?
    - a route path is a end point, while a route method specify a callback function called when the application recieves request to the specified route (end point) and HTTP method.
3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
    - The only exception is that these callbacks might invoke next('route') to bypass the remaining route callbacks. You can use this mechanism to impose pre-conditions on a route, then pass control to subsequent routes if there’s no reason to proceed with the current route.

## [Express Routing](https://expressjs.com/en/guide/routing.html)

1. What is an Express Router?
    - Router is like a mini-Express application. It doesn’t bring in views or settings but provides us with the routing APIs like .use, .get, .param, and route.
2. By what mean do we initialize express.Router() in an express server?
    - We create routes and then tell our app to use those routes.
3. What do we use route middleware for?
    - is a way to do something before a request is processed.
            - checking if a user is authenticated,
            - logging data for analytics,
            - or anything else we’d like to do before we actually spit out information to our user.
