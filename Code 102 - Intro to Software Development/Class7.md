# Class 7: Functions

## MDN Flow: 
The control flow is the order in which the computer executes statements in a script.Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.
Conditional: A condition is a set of rules that can interrupt normal code execution or change it, depending on whether the condition is completed or not.

## Functions:
  -A JavaScript function is a block of code designed to perform a particular task.
  -A JavaScript function is executed when "something" invokes it (calls it).

**A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses (){}.** 

function NAMEFUNCTION(PARAMETERS){CODE TO BE EXECUTED};

function myFunction(p1,p2) { ,<-- Type of code to be executed     <--- EXAMPLE
    return p1 * p2; }

Function Return {}  <--- these paranthesis mean return
When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)