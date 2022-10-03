# Reading

# [Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

1. What native Node.js module allows us to get started with Event Driven Programming?

- EventEmitter:

    const EventEmitter = require('events').EventEmitter;
    const myEventEmitter = new EventEmitter;

    const EventEmitter = require('events').EventEmitter;
    const chatRoomEvents = new EventEmitter;

    function userJoined(username){
    // Assuming we already have a function to alert all users.
    alertAllUsers('User ' + username + ' has joined the chat.');
    }

    // Run the userJoined function when a 'userJoined' event is triggered.
    chatRoomEvents.on('userJoined', userJoined);

2. What is the value of Object Oriented Programming used in tandem with Event Driven Programming?

- Promotes the idea that all behavior of an individual unit (or object) be handled from code within that unit.

3. Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.

- Everything within a object handles is able to within that object.

# Bookmark and Review

# [Node docs: events](https://nodejs.org/api/events.html)
