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

Some advantages to using a constructor are 

















