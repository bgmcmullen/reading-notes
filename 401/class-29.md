# Class 29 Reading Notes:


## Extracting State Logic into a Reducer
### 1. What is the motivation for adding a reducer?
As React apps get more complex, adding a reducer makes them simpler, cleaner, and more readable.
### 2. What are actions in the context of a reducer? How are they different than setting state directly? 
Actions are objects that represent changes to the state.
### 3. What common list operation is useReducer named for, and why? 
It is named after reduce since it accumulates state changes just like the array reduce function.
### 4. When should you switch from useState to useReducer? 
Generally, if you have complex state logic, it is appropriate to switch to useReducer.
