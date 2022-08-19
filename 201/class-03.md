# Learn HTML

## Unordered lists

Unoredered lists are for grouping together a collection of different items when there is
no numerical order, and the order of the list doesn't matter. They are displayed with
bullet points.

Example:
- a
- b
- c
- d

To change the bullet style of your UL, you need to change it in your CSS file under the 
'list-style-type' property. You can change it to a dot, circle, or square.

## Ordered lists

You should use an ordered list over an unordered, when you need to make sure that the list
is in the correct numerical order, for example, if you are following a cooking recipe. They
are typically displayed with a preceding marker such as a number or letter.

Example:
1. a
2. b
3. c
4. d

To change the number to Roman Numeral type on an ordered list, you can add a `<ol type="i">`

To change the starting number on your list to start at 5 for example, you can add a `<ol start="5">`

## Learn CSS

### The Box Model

In CSS, we have something called the Box Model, everything in CSS has a box around it. You can
change the values of margin, padding, border and it will move it around and change the size.

- Content; This is where the content in the box is displayed, you can use width or height properties.
- Padding; The padding is around the content as white space, you can use the 'padding' property to change the values.
- Border; The border box wraps the content and the padding of the box. Changed by the 'border' property.
- Margin; The margin is the layer on the outside, it wraps all three of the above as whitespace, you can use the 'margin' property.

![Box Model](BoxmodelCSS.png)

## Learn JS

### Arrays 

Arrays are described as 'list-like objects', it is a single object which can contain multiple values stored in a list. You can do lots of different things with arrays, you can access each item in an array seperately and be efficient with the data such as, looping through it.

In an array, you can store many data types, such as;

- Numbers
- Strings
- Booleans
- Functions
- Objects
- An even other arrays

This is a valid example of an array;

`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

Each section in a [] is a part of the array, for example, if I wanted to access the first section  which is `['pete', 32, 'librarian', null]`, you could type;

```js
const people = [
  ["pete", 32, "librarian", null],
  ["Smith", 40, "accountant", "fishing:hiking:rock_climbing"],
  ["bill", null, "artist", null],
];
console.log(people[0]);
// This will return - (4) ['pete', 32, 'librarian', null]
```
The [0] represents the first section as computers start counting from zero.

Push() - adds to end of array

Pop() - removes from end of array

Unshift() - adds to start of array

Shift() - removes from start of array

```js
let arr = ["a", 2, false, {}, "I am last"];

for(let i = 0; i < arr.length; i++) {
  console.log(arr[i])
  }
```
This will produce;

a

2

false

{}

I am last

### Assignment Operators

1. Addition assignment (+=); This operator adds the value of the right operand to a variable and assigns the result to that variable.
2. Subtraction assignment (-=); This operator subtracts the value of the right operand and assigns the result to the variable.
3. Logical AND assignment (&&=); `a &&= b` This operator only assigns if a is Truthy.
4. Logical OR assignemnt (||=); `a ||= b` This operator only assigns if a is Falsy.
5. Remainder assignment (%=); This operator divides a variable by the value of the right operand and assigns the remainder to that chosen variable.

A real world example of a conditional statement would be, if you ate dinner and pudding, the resulting outcome of the first choice could be 'still feeling hungry so I need pudding, and the second outcome could maybe be, 'ate dinner and pudding, now I feel really full'.

Loops in JavaScript are incredibly useful. They can run blocks of code over and over again, often the code will be ever so slightly different each time it runs, or it can run the same code but with different variables. An example of when a loop would be useful is if you need to display some text/numbers more than once on a screen.

Example;

```js
let a = 10;
let b = 'dog';
let c = false;

// evaluate this
(a + c) + b;
```
So, first we would add (a + c) which would equal = 10 as false is nothing, next we would add 10 + 'dog', which would equal '10dog' as it would change the number into a string.






