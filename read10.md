# The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.

## Temporarily store: When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame.

## Manage function invocation (call): The call stack maintains a record of the position of each stack frame.

- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

# Types of error messages:

- Reference errors
- Syntax errors
- Range errors
- Type errors
