# Class 07 Reading Notes:


## Intro to JWT

### What is a JSON Web Token (JWT)?
A JWT is a compact way of securely sending information as a JSON object.
### When should we use JSON Web Tokens?
For authorization or secure information exchange.
### Claims are expected in which structural component of a JWT?
Payload component

## Are JWTs Secure?

### If I get a JWT and I can decode the payload, how can we call that secure?
As long as the integrity of the contents of the payload is maintained, it is still secure even if it is not encrypted.
### If sending a JWT, what must the sender and receiver both know? Hint, it’s appended in the signature.
The secret key.
### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
The concatenated content is sealed together, like it is being sent via secured mail delivery.

## JWTs Explained

### Why use JWT?
We use JWT to efficiently send secure data between two parties.
### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
Time and space are valuable even on the internet. Therefore, JWT is an efficient way to deliver a secure piece of information by just sending one self-contained thing and not worrying about large files.
### What are the three components (the structure) of a JWT signature?
Header, Payload, Signature


