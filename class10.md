## EXECUTION CONTEXT:
1. GLOBAL CONTEXT: 
Code that is in the script, but not in a function. There is only one global context in any page.                
2. FUNCTION CONTEXT:               
Code that is being run within a function. Each function has its own function context.
3. EVAL CONTEXT:
Text is executed like code in an internal function called eva l ()

### VARIABLE SCOPE:
* GLOBAL SCOPE :          
If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.

* FUNCTION-LEVEL SCOPE:                   
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

## Errors:
There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:

* Error :Generic error - the other errors
are all based upon this error
* Syntax Error :Syntax has not been followed 
* Ref erenceError: Tried to reference a variable that is
not declared/within scope
* TypeError :An unexpected data type that cannot be coerced.
* Range Error: Numbers not in acceptable range
* URI Error: encodeURI ().decodeURI(),and similar methods used incorrectly.

* EvalError: eva l () function used incorrectly.
## Debugging is the process of finding errors. It involves a process of deduction.

