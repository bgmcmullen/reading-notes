## Class 15 Reading Notes:

1. What is OAuth?
OAuth is a protocol released in 2012 that allows authenticated access to servers' assets by sharing the initial login credential.

2. Give an example of what using OAuth would look like.
Often times when using OAuth, you will get the option to log into a website using the credentials of another website.

3. How does OAuth work? What are the steps that it takes to authenticate the user?
Steps: The website connects to the second website, the second site provides a one-time token and a one-time unique secret, the first site gives the token and secret to the user’s client software, the client is asked to authenticate, the user or software approves, the user is given an approved access token, the user gives that token to the first website, the second website gives the token to the first website, the first website allows the second website access to their site, and the user sees the successful transaction.

4. What is OpenID?
OpenID is another security technology that didn’t become widely appealing to users, so it is mostly used for machines logging into other machines.

1. What is the difference between authorization and authentication?
“In simple terms, authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.” (Auth0)

2. What is Authorization Code Flow?
Authorization code flow consists of transferring an authorization code for a token.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
PKCE has a secret Code Verifier so it can work with Native apps and Single-page apps.

4. What is Implicit Flow with Form Post?
“Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operate.” (Auth0)

5. What is Client Credentials Flow?
“This flow is best suited for Machine-to-Machine (M2M) applications, such as CLIs, daemons, or backend services, because the system must authenticate and authorize the application instead of a user.” (Auth0)

6. What is Device Authorization Flow?
“The Device Authorization Flow contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser. The browser flow path, wherein a device code is bound to the session in the browser, occurs in parallel to part of the device flow path.” (Auth0)

7. What is Resource Owner Password Flow?
“[Resource Owner Password Flow] requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information.” (Auth0)

### Citation:
Auth0. (n.d.). Authentication and authorization flows. Auth0 Docs. https://auth0.com/docs/get-started/authentication-and-authorization-flow 


### Things I want to know more about:
How do we make authentication accessible to users you may need accessibility tools?


