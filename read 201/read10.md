#  **Error Handling & Debugging**

 **ORDER OF EXECUTION**

The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run

*EXECUTION CONTEXTS*

Every statement in a script lives in one of three execution contexts:

  •	GLOBAL CONTEXT Code that is in the script, but not in a function. There is only   one global context in any page.

  •	GLOBAL SCOPE If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 

 •	FUNCTION CONTEXT Code that is being run within a function. Each function has its own function context. 

•	FUNCTION-LEVEL SCOPE When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.

•	EVAL CONTEXT (NOT SHOWN) Text is executed like code in an internal function called eval.

**The Stack**

The JavaScript interpreter possesses one line of codes at a time 
And when statement needs data from another function it STACKS the new function on top of the current task.

**UNDERSTANDING SCOPE**

Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global: Global variables are those declared outside of a block. Local variables are those declared inside of a block.

**ERROR OBJECTS**

It contains 2 properties:

* message: the error description, a human readable message that should explain what error happened

* name: the type of error occurred (assumes the value of the specific error object name, for example, TypeError or SyntaxError or Reference Error or 	URI Error..)



**We use the console to helps narrow down the area in which the error is located, so you can try to find the exact error. JavaScript has 7 different types of errors. Each creates its own error object, which can tell you it’s line number and gives a description of the error.**