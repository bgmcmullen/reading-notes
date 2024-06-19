# Class 36 Reading Notes:

## Async Actions
### 1. Why use Redux middleware?
There are many reasons to use Redux middleware; one is to allow for async logic, which Redux on its own does not support.
### 2.Consider the Redux Async Data Flow Diagram. Describe the flow in your own words. 
First, the user makes an input to the UI, triggering an event. The event handler dispatches an action to Redux. The middleware then makes a request to the API and waits until the API fulfills the request. The middleware then dispatches an action to the Redux reducer.
### 3. How are we accommodating async in our Redux app?
Redux Thunk middleware.
## Thunk Middleware
### 1. Why would you need Redux Thunk middleware?
Redux Thunk allows for asynchronous logic and side effect handling.
### 2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
Function
### 3. Describe how any return value from the inner thunk function will be made available.
It will be the return value of dispatch.









