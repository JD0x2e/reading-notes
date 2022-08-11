# Programming with JavaScript

## Control Flow

Control flow is the order in which the computer executes the code in the script.

Code runs from the first line to the last line in the file, unless it runs across the structures such as **conditionals** and **loops**, which is extremely
frequent!

E.g - The script below would be used to validate user data from a webpage form. The script will submit the data, but if the user leaves a field empty, 
then it would prompt the user to fill it in.

``` js
if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}
```
Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects
order of execution.

## Functions - continued from class-06 reading notes

Example of functions:
```js
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```

### Function syntax

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

(Taken from W3Schools)


## Operators - continued from class-06 reading notes
```js
let x = 5;         // assign the value 5 to x
let y = 2;         // assign the value 2 to y
let z = x + y;     // assign the value 7 to z (5 + 2)
```

### Different operator types

There are many different operator types, such as:

- Arithmetic Operators (+, -, *, **, /, %, ++, --)
- Assignment Operators (=, +=, -=, *=, /=, %=, **=)
- String Operators (let text3 = text1 + " " + text2;)
- Comparison Operators (==, ===, !=, !==, >, <, >=, <=, ?)
- Logical Operators (&&, ||, !)
- Type Operators (typeof, instanceof)
- Bitwise Operators (&, |, ~, ^, <<, >>, >>>)







