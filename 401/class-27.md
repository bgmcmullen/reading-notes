# Class 27 Reading Notes:


## Thinking in React
### 1. Summarize the five steps of thinking in React. 
### Step 1: Break the UI into a component hierarchy
Draw a diagram and identify which components will be contained within which other component.
### Step 2: Build a static version in React 
Create a visual version of your React app which will not yet have interactivity.
### Step 3: Find the minimal but complete representation of UI state. 
Make the UI interactive using state following the DRY (Don't Repeat Yourself) model.
### Step 4: Identify where your state should live 
Since React uses one-way data flow, you will need to find the common parent where the state will live.
### Step 5: Add inverse data flow 
You will need to pass functions down in props so they can be triggered in child components.
## State: A Component’s Memory
### 1. What is one reason a local variable isn’t sufficient for managing a React component?
A local variable will be lost between renders.
### 2. What is the argument to the useState hook, and what are the two parts of its return array? 
The argument is the initial value, and the return array contains the current state value and the function that will update the value.
### 3. How can Component A access state from Component B?
The state can be passed as props.





