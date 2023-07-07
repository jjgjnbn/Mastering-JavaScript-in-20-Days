# Day 3:Functions, Arrow Function, and Scope :
## Functions
Functions are indeed a crucial aspect of JavaScript programming. Here are the key points covered in this lesson:

Function Declaration:
- Functions are declared using the `function` keyword, followed by the function name and parentheses.
- The function's behavior is defined within curly braces `{}`.

Parameters and Arguments:
- Functions can have parameters, which act as placeholders for values that will be passed in when the function is called.
- Parameters are specified within the parentheses of the function declaration.
- The values we provide when calling a function are called arguments, and they correspond to the parameters in the function declaration.

Return Statement:
- Functions can produce an output value using the `return` statement.
- The `return` statement specifies the value that the function will evaluate to and ends the execution of the function.
- When a `return` statement is encountered, the function immediately exits, and the specified value is returned.

Example:
```
function greet(name) {
  return "Hello, " + name + "!";
}

let message = greet("John");
console.log(message); // Output: Hello, John!
```

## Arrow Function
Indeed, arrow functions are a concise and convenient syntax for creating unnamed functions in JavaScript. Here are the key points covered in this topic:

Arrow Function Syntax:

Arrow functions are defined using the arrow (=>) operator, hence their name.
They have a shorter and more compact syntax compared to regular function expressions.
Example:

```
const add = (x, y) => x + y; // arrow function
```
Assigning Arrow Functions to Variables:

Arrow functions can be assigned to variables, making them useful for callbacks and function expressions.
They can be used as a more concise alternative to regular function expressions in these scenarios.

## Scope
Scope plays a vital role in JavaScript and determines the visibility and accessibility of variables. Here are the key points covered in this lesson:

Global Scope:

The global scope is the outermost scope in JavaScript and is accessible from anywhere in the program.
Variables declared in the global scope can be accessed and modified from any part of the code.
Function Scope:

Each function in JavaScript has its own function scope, which is created when the function is defined.
Variables declared within a function using the var, let, or const keywords are only accessible within that function's scope.
Function scope allows for encapsulation and prevents variable name clashes between different functions.
Block Scope:

Block scope refers to the visibility of variables within a block of code, usually delimited by curly braces {}.
Prior to ES6, JavaScript only had function scope and did not have block scope for variables declared with the var keyword.
Variables declared with var inside a block are not limited to that block's scope but instead are accessible throughout the entire function scope.

## Difference Between var and let:
var variables:

Function-scoped: var variables are accessible throughout the entire function in which they are declared or at the global level.
Hoisting: var variables are hoisted to the top of their function or global scope, allowing them to be accessed and assigned values before they are declared. However, their initial value is undefined until assigned.
Redeclaration: var variables can be redeclared multiple times within the same scope without throwing an error. Each redeclaration simply overwrites the previous value.

let variables:

Block-scoped: let variables are limited to the block of code (within curly braces) in which they are defined, such as an if statement or a loop.
Hoisting: let variables are hoisted to the top of their block scope but are not initialized. They are in a "temporal dead zone" until they are declared, and accessing them before declaration results in a ReferenceError.
Redeclaration: let variables cannot be redeclared within the same block scope. Attempting to do so will throw a SyntaxError.


