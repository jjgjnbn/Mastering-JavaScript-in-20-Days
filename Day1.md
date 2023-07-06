# Day 1: Introduction to JavaScript, DOM, Values & Data Types, and Operators
## introduction :
To sum up, JavaScript stands as a formidable and adaptable programming language, empowering developers to fashion web pages that are both interactive and dynamic.
## DOM :
The Document Object Model (DOM) is a crucial concept in web development. It presents the structure of HTML documents in the form of a tree-like structure, allowing for easy navigation and manipulation of the elements within the document.

By utilizing JavaScript, you can access and modify HTML elements through the DOM. This enables you to change attributes, such as modifying the content or styling of elements dynamically. You can also add or remove elements from the web page dynamically, allowing for dynamic updates and interactions.

Furthermore, the DOM enables you to respond to user interactions, such as handling events triggered by user actions like clicks or input changes. With the DOM, you have the power to create interactive and dynamic web pages that respond to user input and provide a rich user experience.

## Values & Data Types
In JavaScript, there are various types of values and data types that you can work with. Here are some of the key ones:

1. Strings: Strings are used to represent textual data. They are enclosed within single or double quotation marks.

2. Numbers: Numbers represent numeric data in JavaScript. They can be integers or floating-point numbers.

3. Booleans: Booleans have two possible values, true or false. They are often used in conditional statements to control program flow.

4. Null: Null is a special value that represents the absence of any object value. It is typically used to indicate the intentional absence of an object reference.

5. Undefined: Undefined is a value assigned to a variable that has been declared but not initialized. It represents the absence of a value.

6. Objects: Objects are complex data structures that can hold multiple values and methods. They are created using curly braces {} and can be used to represent more advanced data types.

Additionally, JavaScript allows you to declare variables and assign values to them. Variables are used to store and manipulate data in your code. The concept of variable scope determines where a variable is accessible within your code.

By understanding these values and data types, you gain the ability to work with different types of data and utilize them effectively in your JavaScript programs.

 
## Operators
Operators in JavaScript serve various purposes and can significantly impact values. When working with arithmetic operators, JavaScript respects the order of operations, allowing for the use of parentheses to group expressions effectively.

## Coding Examples
```javascript
// Example 1: Determining value types using typeof
let value1 = 15;
let value2 = "15";
let value3 = null;
console.log(typeof value1); // number
console.log(typeof value2); // string
console.log(typeof value3); // object (null is a special case its a primitive data type)

// Example 2: Arithmetic operators
let x = 8;
let y = 2;
let s = "2";
let addition = x + y; // Addition
let subtraction = x - y; // Subtraction
let multiplication = x * y; // Multiplication
let division = x / y; // Division
console.log(addition); // Output: 10
console.log(subtraction); // Output: 6
console.log(multiplication); // Output: 16
console.log(division); // Output: 4
console.log(y == s); // true because it just compares the value, not the type 
console.log(y === s); // false because it compares the value and the type of the argument 
```
