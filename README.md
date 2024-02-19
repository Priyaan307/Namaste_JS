# Namaste JavaScript Season 1

# Ep_1.
# Topic: How JavaScript Works &  Execution Context
- Everything in JS Happens inside an Execution Context.

|--------------------------------------------------|
|            Execution context                     |
|--------------------------------------------------|
|Memory Component           |  Code Component      |
| (Variable Environment)    | (Thread of Execution)|
|--------------------------------------------------|                         
|                           | This is the place    |
|     Key : Value           | where code executed  | 
|                           |  one line at a time. |
| It's environment where all|                      |
|  the variables, functions |                      |
| stored as key-value pairs.|                      |
|                           |                      |
|---------------------------|----------------------|

- JavaScript is a Synchronous Single-threaded language.
 js can only execute one command at a time in specific order.
 Which means it can only go to the next line once the current line has been finished executing.

# Ep_2.

# Topic: Functions and Call Stack

- What happens when you run a javaScript program?? 

A Global execution context is created. This context is created in two phases.

Phase 1:

# memory Creation Phase - In the first phase js will allocate memory to all the variables and functions


|--------------------------------------------------|
|    Memory Component       |   Code Component     |
|--------------------------------------------------|                         
|                           |                      |
|  n : undefined            |                      | 
|                           |                      |
|  square: {.......}        |                      |
|                           |                      |
|  square2:  undefined      |                      |
|  square3: undefined       |                      |
|---------------------------|----------------------|

Phase 2:
# Code execution Phase 
When you run a function or invoke a function a brand new execution context is created.

# Call Stack - maintains the order of execution of execution contexts.
also known as -
1. Execution context stack
2. Program stack
3. Control stack
4. Runtime stack
5. Machine Stack

# Ep_3.