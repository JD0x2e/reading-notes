# How the web works?

## How does does HTTP send data between computers?

Firstly, the browser will go to the DNS (Domain Name System), and finds the address of the server which the website is on. The browser will send a HTTP request message to the server. The message will ask if it can send a copy of the website to the client. This, plus all other data sent between you both, will be sent across the internet connection using TCP/IP. If it approves the request, the server will send the client a '200 OK' message which indicates that you can go to the website, then starts sending the websites files as little packets of data, known as data packets

TCP - Transmission Control Protcol 
IP - Internet Protocol

## Parsing

HTML file alwasys gets parsed first - the browser will recgonise any <link> or <script> elements. As the browser sends requests back to the server, any <link> elements will be found and any <script> elements, thus parsing the CSS files then the Javascript.

The browser generates an, in-memory DOM (Document Object Model) tree from HTML.
It generates an in-memory CSSOM (CSS Object Model) from the CSS.
It then complies and executes the JavaScript.
  
## Images 
To find certain images to put onto your website, you can go to [Google Images](https://www.google.co.uk/imghp?hl=en&ogbl), or another one of my favourites is [Flaticon](https://www.flaticon.com/)
  
## What is JavaScript?
  
To make a string in JS, you must enclose the value in single quotation marks.
  
Example:
```js
let myVariable = 'Jack';
```
  
To make just a number in JS, you don't need to put anything around the text.
  
Example:
```js
let myVariable = 10;
```
  
### What is a variable?
  
A variable is a container which stores a value. You can declare it by using the keyword 'let'. This value can be changed later down the line if you need it to be. You must also put a semicolon ; at the end of the line as this indicates that the statement has ended. We **need** variables to be able to do anything remotely cool in coding. If they can't change, then we can't do anything dynamic, e.g change an image displayed in a gallery.

  
## Introduction to HTML
A HTML attribute contains extra info about the element which will not appear in the content. For example, you could have a class on your element so you can later refer to it on your CSS sheet.
  
Example:
![HTML Attribute](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-attribute-small.png)
  
Requirements are:
1. You need a space between the attribute and the element name
2. It needs to be followed by an equal sign.
3. Needs a value, wrapped with quotation marks.

Anatomy of a HTML Element, it goes as follows:
- Opening tag at the startm e.g <p>
- Content in the middle, the text from the paragraph for example
- Closing tag at the end, e.g </p>
 
An <article> tag defines a certain section in a document, whereas, <section> tag specifies independent content on its own.
  
A typical layout of a webpage would include (not limited to) tags, such as
  
- Header
- Navigation Bar
- Main 
- Body
- Footer
- Sidebar
   
Metadata is the data which describes the data. The <meta> element is a way to incorporate metadata into a HTML document. This will be at the top of your index.html file.
  
Using metadata boosts up the SEO because it's written in the language which the search engine understands. It helps to better understand the specific topic and content. It also displays more relevant searches.
  
##
