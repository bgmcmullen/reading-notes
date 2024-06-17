# Class 36 Reading Notes:

## Dan Abramov Redux Tutorials
### 1. What is the first principle of Redux?
The entire state of the app will be represented as a single JavaScript object regardless of the size of the application.
### 2. What is a store and what do we use our reducers for within that store?
A store is a library we use to manage the state of our application. A reducer can be used to manage multiple action types.
### 3. Name three Redux store methods given to us by createStore and describe their use.
getState() - This returns the current state of the store.\
dispatch() - This dispatches an action to change the state.\
subscribe() - This lets you give a callback function to be called when the state changes.
### 4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.
 This function lets you split state management into multiple reducer functions. Think of it like a large company: combineReducers is the senior management and each reducer in the object is a separate department.









