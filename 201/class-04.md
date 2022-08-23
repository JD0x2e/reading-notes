# Learn HTML

## Creating hyperlinks

To create a hyperlink, we wrap text or other content in an `<a>` element which stands for 'Anchor', and we also use the 'href' attribute also know as 'Hypertext Reference'.

```js
<a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>
```

The href attribute contains the web address of the page you are trying to access.

To make our links accessible to all readers we need to include include keywords in our link text so that screen readers and visual readers can see it clearly.

## CSS Layout

Normal flow - Normal flow is the way in which 'block' and 'inline elements' are displayed on a page before there are any changes made to it. This is a system which by elements are placed inside the browser's viewport.

Block level elements; This content fills up the available space of the parent element and grows along the blockm dimension, to make sure it uses the content. The size of these elements are purely just the size of their content. You cannot change the width and height of inline elements. If you would like to set the width and height, you would need to set it differently to `display: block;` or `display: inline-block;`.

Inline block elements; These do not appear on new lines, they sit on the same line with any wrapped text content as long as there is space inside the parent block element. If there is no space, they will move down to a new line.

### Positioning 

**Static positioning** is the default that every element will get. Nothing special here, just means that it will follow normal flow in the document.

**Absolute positioning** will bring a much different result. An absolutely positioned element no longer exists in normal document flow, it sits on its own layer seperately. This can become very useful as it means we can create isolated UI features that don't interfere with other elements on the page. E.g, popup boxes, control menus etc.

Top, bottom, left, right behave in a different way with absolute also. They specify the distance which the element should be from each of the containing elements sides.

**Fixed positioning** works in the same way as absolute, apart from a key difference which is, fixed positioning usually fixes an element in place, relative to the visible part of the viewport. This is particularly useful because you can create UI items that are fixed in their place, like nav menus that are always visible, no matter how much you scroll down the page.

## Learn JS - Functions

A function declaration tells the JS engine information about it, such as the function's name, return type and the parameters. 

A function invocation is basically just another way of calling/running the function. Once the function has been declared inside the code, you can then call upon it at any time in your code to run that reusable block.

In simple terms, 'Parameters' are the properties of the function, whereas, 'Arguments are properties of a particular call to a specific function. 

## Misc

### Pair Programming

Two of the main reasons on why you should pair programme for me are;

1. Greater efficiency - Although it might take a little longer, it actually works out better in the long run because you have two eyes looking at the code so you may be able to fix mistakes or spot bugs quicker which will save later down the line when trying to debug.

2. Learning from fellow students - Everyone has a different approach to problem solving, and most of the time, your partner will have a different skillset to you so if you come across a certain problem, the more experienced on that issue will be able to share their knowledge with you, or you may be able to share some more knowledge with them. This benefits both of you as sharing knowledge will benefit both of you in different ways.














