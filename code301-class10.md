## 	Understanding the JavaScript Call Stack
1.	What is a ‘call’? primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.
2.	How many ‘calls’ can happen at once? one at a time
3.	What does LIFO mean? Last in first out
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack. 
>function firstFunction(){
  throw new Error('Stack Trace Error');
}

>function secondFunction(){
  firstFunction();
}

>function thirdFunction(){
  secondFunction();
}

>thirdFunction();

4.	What causes a Stack Overflow?
stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

##  JavaScript error messages
1.	What is a ‘refrence error’? variable that doesn't exist
2.	What is a ‘syntax error’? create variable in rong way
3.	 What is a ‘range error’?reading from array it out range
4.	What is a ‘tyep error’? errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable
5.	What is a breakpoint? Make your program stop at that point only if a condition is met
6.	What does the word ‘debugger’ do in your code? achieved the breakpoint
