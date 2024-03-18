## Class 05 Reading Notes:

The single responsibility principle is the idea that each component should do one thing and one thing only. If the component evolves to have more functions, it should be split into multiple components.\
\
A static version of an application renders all of the UI but does not yet have any interactivity.\
\
After making a static version of an application, it is time to add basic data handling in the app. This will be done using state.\
\
These question can determine if state is necessary:
"Does it remain unchanged over time? If so, it isn’t state.\
Is it passed in from a parent via props? If so, it isn’t state.\
Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!\
What’s left is probably state."\
\
If only one component needs to render something based on the state, the state will live in that component. If multiple components need access to the state, then the state will probably live in the nearest common parent.\
\
Higher-order functions are functions that operate on other functions. This would happen either by returning another function or taking a function in as an argument.\
\
The greaterThan function takes in an argument and then returns a function. The function returned will determine if a value is greater or less than the original argument given.\
\
Reduce and Map are themselves higher-order functions that take in functions that the values of the array will be passed through.

## Things I want to know more about:
Are there exceptions to the single responsibility principle?

## Works Cited
“Thinking in React.” React. Accessed March 18, 2024. https://react.dev/learn/t