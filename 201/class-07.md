# Object-oriented programming, HTML Tables

## Domain Modeling

*Explain why we need domain modeling.*

We need domain modelling because if done well, it can verify and validate specific problems between various stakeholders. It can also be used as a communication tool, which can be used between the technical and business side of the teams.

## HTML Table Basics

*Why should tables not be used for page layouts?*

1. **Layout tables reduce the accessibility for people with visual impairment** - screen readers won't be able to read the layout, nowadays it is much easier to use CSS to layout your page.

2. **Tables produce tag soup** - Tag soup is poorly structured code and this is what happens if you use tables within your HTML on a webpage nowadays. It is clunky and hard to read and understand.

3. **Tables are not auto responsive** - When you use common semantic tags, the default width is always 100%, unlike tables which are sized compared to their content by default, so extra code is needed to lay it out effectively.

*List and describe 3 different semantic HTML elements used in an HTML `<table>`*

1. `<tr>` - Table row; this defines a row of cells in a table.
2. `<th>`- Table head; this defines a cell as a header of a group of table cells.
3. `<td>`- Table data; this defines a cell of a table which containes data in it.

## Introducing constructors

*What is a constructor and what are some advantages to using it?*

A constructor is basically the same as a function, apart from you call it using the 'new' keyword. When you call a constructor, it will create a new object, bind `this` to the new object, run the code, and return the new object. They always start with a capital letter.

Some advantages to using a constructor are when you want to create multiple similar objects with the same properties so then you dont have to re-type all the different objects out multiple times, you can just use the `this` keyword to refer to the current object which the code is being written inside of.

*How does the term 'this' differ when used in an object literal versus when used in a constructor?*

If we only have a single object literal, 'this' is not very useful as you only have the one object so you don't need to use this, but if you have multiplem objects, 'this' allows you to use the same method for each and every object which you create.

When using a constructor where you have the same properties, it is especially useful as you will need to refer to different objects/methods inside.

## Object Prototypes Using A Constructor

*Explain prototypes and inheritance via an analogy from your previous work experience*

Prototypal Inheritance is a feature which allows you to add methods and properties into objects. It inherits the properites and methods of another object.

In my previous work I have done on cookie-stand, I have used a prototype to inherit the data from the constructor. 

An example below:

```js
function CookieStand(name, minCust, maxCust, avgCookieSale) {
  this.name = name;
  this.minCust = minCust;
  this.maxCust = maxCust;
  this.avgCookieSale = avgCookieSale;
  this.custEachHour = [];
  this.cookiesSoldEachHour = [];
  this.totalDailyCookies = 0;
}
CookieStand.prototype.calcCustomersEachHour = function () {
  for (let i = 0; i < hours.length; i++) {
    this.custEachHour.push(randomNum(this.minCust, this.maxCust));
  }
};
```





















