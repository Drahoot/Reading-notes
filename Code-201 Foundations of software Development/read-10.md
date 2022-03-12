# JS & JQUERY (Jon Duckett Pg. 449 - 486)

## Order Of Execution 
- To find a source of an error, it helps to know how scripts are processed. 
Scripts are ran in order and can sometimes be complex and some tasks cannot be ran until another statement or function has been ran

- Execution context: Every statement in a script lives in one of three execution contexts
> Global Context: Code that is in the script, but not in a function. There is only one global context in any page
- Function Context
> Code that is being run within a function. Each function has its own function context
- Eval Context: Non-showing
> Text is executed like code in an interanl function called eval


- Everytime a script enters a new execution context, there are two phases of activity

1. Prepare
- The new scope is created such as Variables, functions, and arguments

2. Execute
- Now it can assign values to variables
- Reference functions and run their code
- Execute statements

Understanding these two phases helps with understanding a concept called hoisting.

Each execution context also creates its own variables objects. This object contains details of all of the variables, functions, and parameters for that execution context

- Lexical scope
> is a convention used with many programming languages that sets the scope of a variable so that it may only be called from within the block of code in which it is defined

- When an error object is created it will contain the following properties
1. Name
2. message
3. fileNumber
4. lineNumber

- There are seven types of built in error objects in JS
1. Error: Generic Error
2. Syntax Error: incorrect syntax
3. Reference error: Tried to reference a variable that is not declared
4. TypeError: an unexpected data type that cannot be coerced.
5. RangeError: numbers not in acceptable range
6. URIError: encodeURI, decodeURI, and similar methods used incorrectly
7. EvalError: ecal function used incorrectly

If you know something might cause a problem for your script tou can generate your own errors before the interpreter creates them
- Use the: throw new Error )'message'(;

