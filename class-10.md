## Code 201
#### Day 9

**JS Ch 10 - Debugging**

*Order of execution* results in some tasks being unable to complete before another statement or function has been run. 

*Execution contexts* are groups of code that are created when as a script is interpreted. They correspond to the variable scope.
- There is one Global execution context
- Each function creates a new execution context 

The Stack: The interpreter processes one line of code at a time. When a statement needs data from another function it stacks the new function on top of the current task. Each time a new item is added to the stack it creates a new execuction context. As a item completes evalution without dependancy on another function it is removed from the stack and we evaluate the function below it (FIFO).

Execution Context and Hoisting: When a script enters a new execution context there are two phases of activity.
1. Preparation
  - new scope created
  - variables, functions, and arguments are created and stored in memory.
2. Execution
  - assigns the values to the variables that were created
  - functions are referenced and the code is run
  - statements are executed

All of the variables and funcitons are created BEFORE they are executed, we say they are *hoisted* to the top of the execution context.

Each execution context creates it's own (non-accessable by us) *variables object* that contains all of the variables, functions, and parameters for that execution context.

*Lexical scope* in JS functions means that they are linked to everything within their execution context variable object AND in each parent object that surrounds them. A function can access anything that wraps around it but not the contents of a function inside it. The book uses the example of nesting dolls which I thought was really good. I have also discused this in terms of an appartment building with common areas, apartment units, rooms inside of each unit, and closets inside of rooms.

The further out of it's immediate scope a function has to go to find data it's looking for the more it will slow performance. 

**Errors and Debugging**

If a JS statement generates an error it "throws an *exception*, at which point the interpreter stops and looks for exception handling code. If none exists in that scope or each subsequent parent scope an *error object* is created.

Error Object Properties
- name: type of error
- message: description
- fileNumber: name of the JS file
- lineNumber: line number of the error

Error Object Types
- Error - generic error
- SyntaxError - syntax not followed properly
- ReferenceError - tried to reference something out of scope
- TypeError - unexpected data type that could not by coerced
- RangeError - number not in acceptable range
- URIError - a URI handling function was used incorrectly
- EvalError - eval() was used incorrectly

Debugging Workflow
- Where is the problem?
- What is the problem?

Use dev tools to help answer these questions, utilizing console functions can be helpful
- `console.log`
- `console.info`
- `console.warn`
- `console.error`
- `console.group`
- `console.table`
- `console.assert`

Use dev tools to create breakpoints to stop and evaluate your code. 

If you know your code may fail use Try, Catch, Finally.

>`try {`

>   `to execute the code here`

>`} catch (exception) {`

>   `if exception, run this code`

>`} finally {`

>   `run this code regardless`


>`}`

You can also add `throw new Error('message')` to create your own error and message when a condition occurs to stop the program there.

Debugging Tips
- try another browser
- add numbers logged throughout the code to track how for it runs
- strip it back to test each part
- explain the code aloud
- search the internet
- use code playgrounds
- validation tools

Common errors to look for
- syntax
- mispelling
- scope
- reserved words
- repeated variable names
- data type errors



[Return to the Main Page](README.md)