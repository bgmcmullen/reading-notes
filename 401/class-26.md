# Class 26 Reading Notes:


## React Quick Start
### 1. What are the building blocks of a React app?
Components

### 2. What is the difference between an HTML element and a React component? 
An HTML element is simply the basic building block of a web page while a React component is a reusable piece of UI that can be built with a JavaScript function.

### 3. What is JSX and why do we use it?
JSX is similar to HTML but more strict. We use it in React to describe the UI structure in a more readable and expressive way.
### 4. Describe the process of embedding JavaScript expressions in JSX.
We can place JavaScript expressions inside curly braces within a JSX element.
### 5. Does React or JSX have any special features for iteration or conditional logic?
No, but this can be achieved with standard JavaScript operations.
### 6. How does React know to respond to a user’s inputs?
React can respond to user inputs with event handlers such as onClick.
### 7. What word indicates that a React component manages data with a Hook?
use
### 8. How can two React components share data?
React components can share data with information passed as props. 

## Render and Commit
### 9. What are the three steps of refreshing a React UI? 
Triggering a render, Rendering the component, Committing to the DOM
### 10. How do you trigger updates to a component after the initial render? 
Updating the state
### 11. Does React recreate DOM nodes on every rerender? 
It does not.
### 12. After React has updated the DOM, what still needs to happen before the user sees the change? 
After React updates the DOM, the browser still needs to perform layout and painting operations to reflect the changes visually.





