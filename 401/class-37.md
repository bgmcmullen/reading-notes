# Class 37 Reading Notes:

## Multiple Reducers Example
### 1. Why create multiple reducers? 
Creating multiple reducers allows the coder to modularize the logic of the Redux state, making it more scalable and reusable.
### 2.How would you combine multiple reducers?
Reducers are combined with the combineReducers function.
### 3. How will you manage state as an immutable object? Why?
One of the primary ways to manage state immutability is the spread operator (...). This is necessary for predictability.
## Redux Docs: Using Combined Reducers
### 1. combineReducers is a utility function to simplify the most common use case when writing ___ _____. 
Redux reducers
### 2. Explain how combineReducers assembles the new state tree. 
combineReducers calls all slice reducers with that reducer’s piece of the state and action.
### 3. How would you define initial state in an app using combineReducers?
The initial state is the state the app will begin with if no actions have been called to change it.
## Redux Docs: Combined Reducer Syntax
### 1. Why will you want to split your reducing functions as your app becomes more complex?
Splitting the reducer allows you to modularize the app, making it more scalable and versatile.
### 2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____. 
combineReducers, Redux Toolkit's configureStore
### 3.What is a popular convention when naming reducers?
Generally reducers are named with a noun describing its function followed by the word "Reducer" in camel case.









