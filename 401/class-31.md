# Class 31 Reading Notes:


## Choosing the State Structure
### Summarize the five principles for structuring state.
## 1. Group related state:
If multiple state variables are updated together, it may be best to combine them into one variable.
### 2. Avoid contradictions in state:
Do not have multiple states that contradict each other.
### 3. Avoid redundant state:
If information can be determined without an additional state variable, do not add that variable.
### 4. Avoid duplication in state:
Don’t have the same data in multiple state variables.
### 5. Avoid deeply nested state:
Don’t pass states through more layers than necessary.
## Passing State Deeply with Context
### 1. What problem do Contexts aim to solve?
Prop drilling
### 2. What is one technique to try before useContext?
Lifting state up.
### 3. What hook complements useContext for complex applications?
useReducer

