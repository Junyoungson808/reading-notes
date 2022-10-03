
# [Intro to JWT](https://jwt.io/introduction/)

1. What is a JSON Web Token (JWT)?
  - JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 
2. When should we use JSON Web Tokens?
  - Authorization
  - Information Exchange
3. Claims are expected in which structural component of a JWT?
  - Payload

{
  "alg": "HS256",
  "typ": "JWT"
}

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. If I get a JWT and I can decode the payload, how can we call that secure?
  - because the signature won't match 
2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
  - a signature
3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  - I dont understand this.

### Videos

### [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. Why use JWT?
  - to securely transfer information between any two bodies
  - digitally signed and trusted
  - compact
2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  - Contains information about the user
  - avoid query the database more than once
3. What are the three components (the structure) of a JWT signature?
  - header
  - payload
  - signature

### Bookmark and Review
1. [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

=======
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

