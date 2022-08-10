# What is JavaScript?

JavaScript is lightweight, compiled programming languag with first-class functions. It is classed as
**functional programming**.

It is most commonly used as part of web pages, which allows client-side scripts to interact with the user
and make dynamic pages. JavaScript also has object-oriented capabilities.

## Variables

In JS, we have things called **Variables** which we can set a value too and they are also able to be
changed at a later date. 'Let' is the keyword to declare a variable.

For example:

```
let firstName = "Jack";
  console.log(firstName);
```

## Constant (Const)

In JS, we also have a thing called **Consts** which we can set a value too and they cannot be changed at a
later date, unlike **let**.

```
const firstName = "Jack";
  console.log(firstName);
```

## Operators

```
+ Addition
- Subtraction
* Multiplication
/ Division
```

## Functions

Functions are reusable blocks of code that you can write once and run again and again, so you don't need
to keep repeating the code.

E.g
```
function checkGuess() {
  alert('I am a placeholder');
}
```

## If, Else statements
``` js
let speedLimit = prompt("What speed are you going?");

let message;

if (speedLimit > 60){
  message = "You are speeding!"
} 
else { (speedLimit < 60);
  message = "You are driving fine!"
}

document.write(message);
```
  
  
  
  
  
  
  
  
  
