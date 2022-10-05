# Reading

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.
  - chat is a bi-directional communication between two or more clients and servers
2. What proof of life are we getting on the backend from the above app?
  - We get proof of life when a client connects to the server, we will see them make a connection. 
3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
  - broadcasting flag.

## [Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?
  - to make sure the noise or traffic is only shown to those who are involved or need to know. 
2. How do you join a room?
  - you create a emit.('JOIN') to join a room with the server having a .on to listen for the applicants.
3. how do you leave a room?
  - you dont - you can never leave.

## [Namespaces](https://socket.io/docs/v4/namespaces/)

1. What is a Namespace and what does it allow you to do?
  - allows you to split the logic of your application over a single shared connection.
2. Each namespace potentially has its own what? (hint: 3 things)
  1. event handlers
  2. rooms
  3. middlewares
3. Discuss a possible use case for separate namespaces
  - you want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application

## Bookmark and Review
1. [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)