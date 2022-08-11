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

Initialisation - This sets the starting value.
Condition - This is what has to be met to continue with the loop.
Iteration - What we are going to change in the condition.

Example of a for loop:
```js
for (let i = 0; i <= 10; i++) {
  console.log(i);
}
```

[Diagram for a for loop](https://files.slack.com/files-pri/T037AFFRC1E-F03TNMHS7L1/screenshot_2022-08-11_at_14.54.16.png)

[2nd Diagram for a for loop](https://app.slack.com/client/T037AFFRC1E/C03RH9GFK9V)

# While Loops

```js
let count = 1;
while(count <= 10) {
  console.log(count)
  count = count + 1;
}
 // While count is less than or equal to 10, it will repeat.
 // Initialisation, condition, iteration.
```
[Diagram for while loop](https://files.slack.com/files-pri/T037AFFRC1E-F03T9V6MLKV/screenshot_2022-08-11_at_14.54.11.png)

















