# Functions
==

 functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure 
a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take  input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

## Defining functions

Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:
The name of the function and a list of parameters to the function, enclosed in parentheses **;** and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, **{}**.


example:

function printuserName(userName, surName){


    console.log ('welcome ',userName, surName);



  document.write(`hello <b> ${userName} </b> ${surName} <br>`)


 }
printuserName(userName, surName);
