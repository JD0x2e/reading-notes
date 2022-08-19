# Introduction to HTML, continued from class-01

## Why is it important to use semantic elements in HTML?

Firstly, the browser will be able to read semantics well and automatically apply large font size to a 'h1' for example, rather than a 'span'. We also need to use semantics as it is much better for search engine optimisation and screen readers

## Headings

In total there at 6 levels of headings in HTML, these are:

# 'h1' - This is the biggest and is used for top-level headings on a page, preferably only 1x per page.
## 'h2' - This is the second largest and is for sub-headings.
### 'h3' - This is the third biggest and is for sub-sub headings, and it just continues like this...
#### 'h4' - This is the fourth biggest
##### 'h5' - Fifth biggest
###### 'h6'- Sixth biggest (or smallest)

## Superscript and Subscript

Superscript (sup) and Subscript (sub) are two elements in HTML which are used when marking up dates, chemical formulae and mathematical equations so they show the correct meaning.

Example:
[Superscript & Subscript Example](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting#superscript_and_subscript)

## Abbr Element (Abbreviation)

'Abbreviation' element is used to wrap around an an abbreviation or acronym. When including this in your HTML, you should provide a full expansion of the text, along with the 'abbr' element to mark it up.
If providing the expansion in addition to the abbreviation doesn't make sense to do, and the abbreviation/acronym is a shortened term, provide the full expansion of the term as the value of title attribute instead.

## Learn CSS

There a 3 ways to apply CSS to a HTML document. External CSS, Internal CSS, and Inline CSS.

- **External CSS**, you have a seperate CSS stylesheet and you link your HTML document to this by using the 'link' element.
```
<link rel="stylesheet" href="styles.css">
```
- **Internal CSS**, you can put 'style' elements in the head of your HTML document and then write all your CSS in there.
```
<style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }

      p {
        color: red;
      }
    </style>
```

- **Inline Styles CSS**, you can put a style element on a single line of code, but this is far from efficient.
```
<h1 style="color: blue;background-color: yellow;border: 1px solid black;">Hello World!</h1>
```
We should avoid using inline styles as much as possible due to its inefficieny for maintenance. If you change one style, it could mess up the rest of the page and will require more changes later to match. Secondly, it also mixes us the CSS/HTML code and makes it much harder to read and understand, this is why it is best to keep it seperate.

## Review
```
   h2 {
     color: black;
     padding: 5px;
   }
```
Here is an example code block and I will explain what each part means: 

'h2' - This is the selector, the first part of the CSS rule. This tells the browser which element to apply the styles onto.

'color' & 'padding' - These are the properties, which identify the stylistic features you want to make changes to.

'black' & '5px' - These are the values, black is the color which we want to change to and 5px is the amount of pixels we want to add of padding.

When a property is paired with a value, we call this a *declaration*.

## Learn JS

A sequence of text which is enclosed with single quote marks is a data type called a 'String'.

Example:
```
let myVariable = 'Bob';
```

### JavaScript Operators

1. Addition +
2. Subtraction -
3. Multiplication *
4. Division /
5. Assignment =
6. Strict Equality ===
7. Not/Does Not equal !/!==

Functions - A real world problem which you could solve with functions would be if I wanted to multiply repeated number entries, I could just write out the function and whenever I have 2x numbers I need to multiply together, I can just invoke (call) the function as to save writing more code.

### If else conditional statements

An if statement, checks a condition, and if it evaluates to true, then a code block will execute.

An else if statement, this is a way to add an extra choice/outcome to the if/else statement. This will be added inbetween the if and else statements and will be tested if the if statement values as false.

An else statement will be executed if the same condition as the if statement, evaluates to false.

### Comparison Operators

=== and !== — test if one value is identical to, or not identical to, another.

< and > — test if one value is less than or greater than another.

<= and >= — test if one value is less than or equal to, or greater than or equal to, another.

(Taken the above example from [MDN Docs on Comparison Operators](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals#if...else_statements)

### Logical Operators

&& - This represents 'AND'; this allows you to chain together two or more expressions so that they both have to evaluate to true for the expression to be true.

|| - This represents 'OR'; this allows you to chain together two or more expressions so that one or more of them has to evaluate to atleast true, for the expression to be true

! - This represents 'NOT' 


