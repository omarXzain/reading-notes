# Error handling and debugging
- Debugging is the process of finding errors. It involves a process of deduction. 

- It is common to face some errors in the process of writing your code using JavaScript. However, there are different methods that you can use to help you locate those errors and to debug your code.

![](https://www.toolsqa.com/wp-content/uploads/2020/05/ERROR-HANDLING-IN-JAVASCRIPT.jpg)

- avaScript has a certain order in which it executes the codes, you should also be familiar of the way that the language works and what it executes first in order to be able to write a code that has no bugs.


- JavaScript is interpreted one function at a time. If it finds a call for another function, it goes to the other function and when it finished it will go back to its place.

## Error Objects
There are seven main types of built-it error objects in JS:

1. Error: generic error
2. SyntaxError: the proper syntax is not followed
3. ReferenceError: referencing a variable that is either undeclared or not within scope
4. TypeError: using an unexpected data type
5. RangeError: numbers are not in the specified range
6. URIError: URI related methods are used incorrectly
7. EvalError: eval() function used incorrectly

## Dealing with Errors:
In order to deal with errors, there are two routs you may choose one based on what is best suited for the situation.

## Debug the script
This basically is using developer tools available to you, to track down an error after it occurs and resolving it. To do so, you must find where the problem is; console allows you to find where the script breaks and helps you determine where to look for the problem. 

## Handle errors gracefully
- On the other hand, if you are writing code and see the potential of the code failing, use try, catch, and finally. This basically is saying: Try to execute the code (try), if there is an exception or an issue, run this code instead (catch), either way this should get executed (finally). If you expect problems in your script, you can also generate or throw your own errors before the interpreter creates them, this allows you to catch issues earlier in the coding process.

## UNDERSTANDING ERRORS
- If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 

## CONDITIONAL BREAKPOINTS 
- You can indicate that a breakpoint should be triggered only if a condition that you specify is met.

![](https://raw.githubusercontent.com/bahmutov/bahmutov.github.io/master/images/conditional-breakpoint.png)

## 5 JavaScript Debugging Tips:

1. Debugger statement
2. Using the console in the debugger
3. Conditional breakpoints
4. Async traces
5. Pause on exceptions 

## Note
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. 
