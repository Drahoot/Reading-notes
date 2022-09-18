## Classes and Objects
- Objects are an encapsulation of variables and functions
- Classes are a template for objects
- The init() function is a special function that is called when the class is being initiated, think of this as a consctructor

## Thinking Recrusivly
- A recursive function is a function that is defined in terms of itself
  - The function will continue to call itself and repeat its behavior until a condition is met
- There are two parts of a recursive function
  - Base Case
  - Recursive Case
- Each call has its own execution to maintain the state
  - Thread the state through each recursion call so that the current state is part of the execution
  - Keep it in a global scope
- A list is a perfect example of a recursive data structure
- Python does not have support for tail end elimination - a stack overflow can happen if you end up using more stack frames than the default stack