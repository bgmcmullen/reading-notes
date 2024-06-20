# Class 39 Reading Notes:

## Redux Toolkit (RTK)
### 1. What concerns are addressed by Redux Toolkit?
• Complexity of a Redux store
• High number of packages needed
• Too much boilerplate code to use Redux
### 2. What does configureStore() do?
configureStore wraps createStore to provide simplified configuration with good default options.
### 3. How would I use createSlice()?
createSlice creates a slice by taking in a reducer option and initial state.
## MobX
### 1. What is MobX?
MobX is a state management system that is scalable and well-tested.
### 2. How does MobX make it “impossible” to produce an inconsistent state?
It does this by ensuring that anything that can possibly be derived from the state will be.
### 3. How would we build a reactive user interface?
We use the observer wrapper to keep the component in sync with the state.










