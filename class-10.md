# Error Handling &Debugging:
- ORDER OF EXECUTION: help us to know where’s error occurred .
- EXECUTION CONTEXT: Every statement in a script lives in one of three execution contexts:
  (GLOBAL CONTEXT, FUNCTION CONTEXT, EVAL CONTEXT (NOT SHOWN)).
- VARIABLE SCOPE:( GLOBAL SCOPE, FUNCTION-LEVEL SCOPE).
- interpreter processes one line of code at time, when u called function, that’s function will be in top stack.
- EXECUTION CONTEXT & HOISTING:(1.PREPARE, 2: EXECUTE)  the two point help us to understand hoisting.
- each execution context has its own variables object. It holds the variables, functions, and parameters available within  it.
- exception-handling: inform users when there is a problem.
- ERROR OBJECTS: can help you find where your mistakes are and browsers have tools to help you read them.  (Error, Syntax Error, Reference Error, TypeError, Range Error, URI Error
, EvalError)

- DEAL WITH ERRORS:
1. DEBUG THE SCRIPT TO FIX ERRORS.
2. HANDLE ERRORS GRACEFULLY.
- using Try  and Catch to allocate error befor occured .
