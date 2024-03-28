## Class 10 Reading Notes:

1. What is a 'call'?\
   The call is the invocation of a function.\

2. How many 'calls' can happen at once?\
   Calls cannot happen simultaneously.\

3. What does LIFO mean?\
   Last In, First Out.\

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.\


function functionOne() {\
  console.log("This is functionOne");\
}\
function functionTwo() {\
  functionOne();\
  console.log("This is functionTwo");\
}\
functionTwo();\

Stack:\
1. functionOne()\
2. functionTwo()\

5. What causes a Stack Overflow?\
   A stack overflow happens if a function starts continuously calling itself.\

1. What is a 'reference error'?\
   A reference error occurs when you use an undeclared variable.\

2. What is a 'syntax error'?\
   A syntax error occurs due to incorrect syntax that JavaScript cannot parse.\

3. What is a 'range error'?\
   A range error occurs if an object with length such as an array is given an invalid length.\

4. What is a 'type error'?\
   A type error occurs when trying to access an invalid type.\

5. What is a breakpoint?\
   A breakpoint is a point where your code will temporarily pause, allowing you to see if any problems have occurred.\

6. What does the word 'debugger' do in your code?\
    A debugger statement adds a breakpoint to your code.\


### Things I want to know more about:
Are there other types of errors?



