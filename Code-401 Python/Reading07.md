## Python Scope
- The scope of a name defines the area of a program in which you can access that name
  - IE Variables, functions, objects, etc...
- There are two general scopes:
  - Global Scope: This is a name defined that is available to all of the code available
  - Local Scope: These are defined and can only be used within the scope
- Namespaces are dictionaries that python uses to store names in other scopes
- LEGB
- 1. Local Scope: Is a code block or body of any python function. The scope contains the names that are defined within the function. They are created at function call and not the definition of the function itself. 
- 2. Enclosing Scope: Is a scope that can only exist for nested functions. If the local scope exists inside of an inner or nested function then the enclosing scope must exist on the outer of the function. 
- 3. Global Scope: The most common scope in a program, script, or module. The global scope contains all defined methods at the top level or a program and are visible anywhere within the code
- 4. Built In Scope: Is a scope that is created or loaded whenever a script is ran as an interactive session. The built in scope contains keywords, functions, exceptions and other attributes in python. Similar to a global scope they are available anywhere.

## Dont be confused by Big O notation anymore!
- The direct relation between time and size of data is direct