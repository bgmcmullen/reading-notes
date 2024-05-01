# Class 03 Reading Notes:

## Review: ES6 Classes
1.	Classes are a template for creating ____
objects.
2.	Can a class declaration be hoisted? 
No.
3.	How would you describe a constructor and contextual “this” to a non-technical friend?
A constructor builds the class with the information it needs. “this” is how the class references itself and its own elements.
## Using Express Routing
1.	Within Express, what does routing refer to? 
Routing refers to the application's endpoints and how they respond to client requests.
2.	What is the difference between a route path and a route method?
Route methods invoke one of the HTTP methods such as GET or POST. Route paths define the specific client endpoint.
3.	When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter? 
If you have multiple callback functions for an HTTP request, you need to use “next” to trigger the next one. “Next” must be called when it is passed into a function.
## Express Routing
1.	What is an Express Router? 
An Express Router is a “mini-app” that can create modular route handlers.
2.	By what means do we initialize express.Router() in an Express server? 
Using Node’s “require”.
3.	What do we use route middleware for? 
We can use route middleware for request and response processing and other purposes.

