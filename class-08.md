# Expressions and Operators

## Comparison Operators

### What is a comparison operator?

A comparison operator compares its operands and returns a value based of whether is it true or not. They can be:

- Numerical
- String
- Logical
- Object Values

Mostly, if the two operands are *not* of the same type, JS will try to convert them to an appropriate type for the comparison, which generally results
in comparing them *numerically*.

The only exception to this is, === or !== which represents the strict equality or inequality comparisons.

Example: 
```js
const var1 = 3;
const var2 = 4;
```

## Assignment Operators

## What is an assignment operator?

An assignment operator assigns a value to its left operand, based on the value of the right operand. The simplest assignment operator is equal (=),
which assigns the value of the right operand, to the left.

[Assignment Operators table](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

Example of assigning to properties:
```js
const obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
```

## Destructuring 

Destructuring assignment syntax allows us to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.

Example:
```js
const foo = ['one', 'two', 'three'];

// without destructuring
const one   = foo[0];
const two   = foo[1];
const three = foo[2];

// with destructuring
const [one, two, three] = foo;
```

# Loops

Loops offer a quick and easy way to repeat a piece of code multiple times. You can think of a loop as a computerised version of the game where you tell
someone to take X steps in one direction, and Y steps in another.

Example ('Go five steps to the east'):
```js
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
```
## For loops

A *for* loop repeats until the specified condition evaluates to false. It has 3 optional expressions.

Expression 1 - executed (one time) before the execution of the code block.
Expression 2 - defines the condition for executing the code block.
Expression 3 - executed (every time) after the code block has been executed.

Example of a for loop:
```js
for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```




















