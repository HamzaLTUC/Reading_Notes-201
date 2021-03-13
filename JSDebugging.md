## introduction:
When writing JavaScript, you need to expect to write it perfectly the first time.
Programming is like problem solving: you are given a puzzle and not only do you have to solve
it, but you also need to create the instructions that allow the computer to solve it too.

## *Some topics we need to pay attenion to it:*
1. Order of execution: how scripts are processed ,some tasks complete until another statement or function has been run.
 
2. Execution Context:
Every statement in a script lives in one of three
execution contexts: <br>
a. Global Context:  which Code that is in the script, but not in a function. <br>
b. Eval Context : Text is executed like code in an internal function.

   c. Global Scope: like If a variable is declared outside a function, it has global scope.
  <br> 


 3. Execution Context & hoisting: \
  we need to prepare  Variables, functions, and arguments and then execute .

  4. Understanding Scope: \
  each execution context has its own variables object.
    It holds the variables, functions, and parameters available within it.
     Each execution context can also access its parent's variables object.

  5. Understanding the errors: \
  when JavaScript statement generates an error  then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 

### ERROR OBJECTS
Here is a table which summarize:
![](https://i.ibb.co/dLw6vB2/debegging.png) 

### How to deal with errors:
1. DEBUG THE SCRIPT TO FIX ERRORS :
track down the source of the error,
and fix it.

2. HANDLE ERRORS GRACEFULLY:
using try, catch, throw, and finally statements.

    
 ###  DEBUGGING WORKFLOW
 
1. WHERE IS THE PROBLEM?\
2.WHAT EXACTLY IS THE PROBLEM?

• If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback