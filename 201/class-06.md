# Reading

## JS Object basics

*How would you describe an object to a non-technical friend you grew up with?*

An object is a collection of data and or functionality. Inside the objects are normally properties and methods which would normally be called variables/functions outside of the object. They have key value pairs inside them like `name: Jack`.

An object starts like this;

```js
const person = {}
```

*What are some advantages to creating object literals?*

Basically, an object literal is literally just an object, but it is cleaner formatted. A reason why you would use an object literal is because it shortens the syntax, allows us to create plain javascript objects and sending a single object is much more efficient than sending several items individually, plus its easier to work with, compared to an array.

*How do objects differ from arrays?*

Objects are basically the same as arrays, apart from in an object you use the name associated with the members value instead of using the index number. Objects represent a data type that can be used to store a collection of different data, whereas an array can be used to store a list of values.

*Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.*

An example of where you would use bracket notation over dot notation would be, if an object property was given at runtime, then you couldn't use dot notation to access the value. You would have to use bracket notation and then have an input & prompt.

*Evaluate the code below. What does the term this refer to and what is the advantage to using this?*

```js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

The term 'this', refers to the current object of which the code is being written inside of. In this particular case, the word 'this' is referring to 'dog'. You could write 'dog' instead if you had just a single object literal, but when you have more than one object, it can become very useful as you won't have to change the name multiple times to `dog` then `dog1` for example.

### Introduction to the DOM

*What is the DOM?*

DOM, stands for 'Document Object Model' is a type of programming interface for web documents. In basic terms, it represents the web page  so that certain programs can change the data inside of it, such as the structure, style and content. DOM represents the document as nodes and objects, so this way programming languages can actually interact with it.

*Briefly describe the relationship between the DOM and JavaScript.*

The document is written in JavaScript, but uses the DOM to access all the information inside. The DOM isn't a programming language but without it, JavaScript wouldn't be able to have any model/notion, html docs, svg docs etc. Everything inside of a the document such as head, tables, text and all other elements, are parts of the DOM for that document. They can all be changed and manipulated using the DOM and a scripting language, like JS.


