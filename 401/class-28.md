# Class 28 Reading Notes:


### What is the main intended use case for the useEffect hook? 
The main intended use case for the useEffect hook is connecting to an external system.
### How does the effect’s logic interact with the component? 
The component mounts, the effect’s function runs after the render is committed to the screen, then the effect runs again if any value in its dependency array changes.
### What is the importance of the return value from the effect’s logic function? 
The return value from the effect’s logic function in React's useEffect hook is crucial because it defines a cleanup function.