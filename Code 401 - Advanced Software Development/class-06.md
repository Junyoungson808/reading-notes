# Reading

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.
  - Hashing is a way to store huge amounts of data in a short as time possible.

  general purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible. Hashing is the greatest way for protecting passwords and considered to be pretty safe for ensuring the integrity of data or password.

2. What is Bcrypt?
  - a function to stretch out the key strokes. 

3. Why might you use something like Bcrypt?
  - To stop brute force attackers trying to steal passwords and user information.

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?
  - HTTP user agent to provide a username and password when making a request. 
2. What properties are necessary in the header of a Basic Auth request?
  - Authorization: Basic <credentials>,
3. How are username:password in Basic Auth encoded?
  - they are encoded by Base64

### [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. Define the authentication process to a non-technical recruiter.
  - Authentication is a the process to verify the requesting person is the right person.
2. How should your error messaging respond (both HTTP and HTML)? Why?
  1. The user ID or password was incorrect.
  2. The account does not exist.
  3. The account is locked or disabled.
  - The objective is to prevent the creation of a discrepancy factor, allowing an attacker to mount a user enumeration action against the application.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

#### Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)