# Class 02 Reading Notes:

The render happens first then the componentDidMount.

The first thing that happens in React is the constructor runs.

Here is the order of events: constructor-render-React Updates-componentDidMount-componentWillUnmount

The componentDidMount() method gets invoked after a component is mounted. This can be used to  load a network request or initialize the DOM or possible other events.

You can pass almost any variable into a component as props. It could be a number an object or maybe a string that gives the component the information it needs to function the way we want.

The main difference between props and state is that props are past into the component from the outside while state is managed inside the component.

You can re-render part of a component as needed with state but this is not the case with props because props are handle outside the component.

State is used to store variables that we need change inside the component such as number to keep track of a count.

## Things I want to know more about.
Is there situation where either props or state could work? If so, is one more efficient for the computer to process that the other?