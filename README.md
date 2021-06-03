# class10

JAvascript debiugging

Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger. Built-in debuggers can be turned on and off, forcing errors to be reported to the user. With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

When you are writing JavaScript, do not expect to write it perfectly the first time. 
Programming is like problem solving: you are given a puzzle and not only do you have to solve 
it, but you also need to create the instructions that allow the computer to solve it. too. 
When writing a long script, nobody gets everything right in their first attempt. The error 
messages that a browser gives look cryptic at first, but they can help you determine what 
went wrong in your JavaScript and how to fix it. In this chapter you will learn about: 
THE CONSOLE & 
DEV TOOLS 
Tools built into the browser 
that help you hunt for errors. 
9 ERROR HANDLING & DEBUGGING 
COMMON 
PROBLEMS 
Common sources of errors, 
and how to solve them. 
HANDLING 
ERRORS 
How code can deal with 
potential errors gracefully. 

EXECUTION CONTEXT 
JavaScript 
Hello Molly 
Every statement in a script lives in one of three 
execution contexts: 
Q GLOBAL CONTEXT 
Code that is in the script, but not in a function. 
There is only one global context in any page. 
FUNCTION CONTEXT 
Code that is being run within a function. 
Each function has its own function context. 
Q EVAL CONTEXT (NOT SHOWN) 
Text is executed like code in an internal function 
called eva l {) (which is not covered in this book). 
VARIABLE SCOPE 
The first two execution contexts correspond with the 
notion of scope (which you met on p98): 
Q GLOBAL SCOPE 
If a variable is declared outside a function, it can 
be used anywhere because it has global scope. 
If you do not use the var keyword when creating 
a variable, it is placed in global scope. 
FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, 
it can only be used within that function. This is 
because it has function-level scope.


UNDERSTANDING ERRORS 
If a JavaScript statement generates an error, then it throws an exception. 
At that point, the interpreter stops and looks for exception-handl ing code.
