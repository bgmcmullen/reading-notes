# Class 03 Reading Notes:

Map returns a new array with each variable having been passed through the function you give to map.

To display the elements of the array in JSX you will want to use map to return <li> elements containing each index of the array.

Each list item needs a unique key. 

React requires the key so it can keep the list ordered properly if elements are added or removed.

The spread operator as the name suggests breaks up an iterable into its individual indices.

Spread can be used to:
Replace apply(),
Be used in an array literal,
Be used to copy an array to a new variable
To concatenate arrays without .concat()

Two arrays can be combined: newArray = [...array1, ...array2];
A new item can be added to an array: newArray = [...originalArray, newItem];
Two objects can be combined: newObject = {...object1, object2};

First the developer passes in the function in as a prop.

In theory handleClick will do what ever you assign it to do but presumably it is the function you will call any time an element is clicked. Perhaps you would use it to call a function from the props.

You can pass a method from a parent component into a child component with props.

To invoke a method passed into a child component you just access the props and invoke the function.



## Things I want to know more about.
Are there times when apply() and .concat() should be used over the spread operator?