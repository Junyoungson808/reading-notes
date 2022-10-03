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