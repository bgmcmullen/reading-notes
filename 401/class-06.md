# Class 06 Reading Notes:


## Securing Passwords

### Explain to a non-technical friend how you would safely hash and store a password.
In order to prevent passwords from being easily stolen, we use a hash function to scramble them into a unique code that cannot be reversed back to plain text.
### What is Bcrypt?
Bcrypt is a special hash function intended to prevent brute force attacks by using key stretching to slow down such an attack.
### Why might you use something like Bcrypt?
Bcrypt is great for sites that contain sensitive information.
Basic Auth

### What is Basic Authentication?
Basic Authentication is a way for the client to send a username and password along with HTTP requests.
### What properties are necessary in the header of a Basic Auth request?
Authorization: Basic "username:password"
### How are username:password in Basic Auth encoded?
The username and password are encoded to Base64 but are not hashed or encrypted.
OWASP Auth Cheatsheet

### Define the authentication process to a non-technical recruiter.
Authentication is a system to make sure the user is who they claim to be before entering the site.
### How should your error messaging respond (both HTTP and HTML)? Why?
It should send a generic error message to prevent an enumeration attack.


