# CSS - Cascasding Style Sheets

## What is CSS?

With CSS, you can control how you use HTML and how it looks on a webpage. You can change backgrounds, colors, styles, sizes, borders and many more.
CSS is a rule-based language, you define the rules by specifying groups of styles that should be applied to certain elements or groups of elements
on your web page.

For example:
```
h1 {
    color: red;
    font-size: 5em;
}
```

To explain that further;
- H1 is the '**selector**'
- Then you always have a set of curly braces {}
- Inside the braces you have a **declaration**, inside the declaration you have one or more **properties** and **values**.
- The example above has 2x declarations.

Inside CSS, there is always many rules as that effectively is the style of your entire HTML webpage.

## CSS Modules 

The language of CSS is broken down into '**modules**'

For a specific example, Backgrounds and Borders module — it makes sense for the **background-color** and **border-color** properties to be defined
in this module.

Here is a reference to the Mozilla Docs for [Backgrounds and Borders](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders)

## Three ways to add CSS to your HTML

### External CSS
With External CSS, you have to link to the external page inside the <link> element.

```
<link rel="stylesheet" href="mystyle.css">
```

### Internal CSS
With Interal CSS, you can add your CSS in the <style> element at the top of your HTML file.
  
```
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
```
 
### Inline CSS
An inline style of CSS would maybe be used if you want to just style a single element.
  
```
<p style="color:red;">This is a paragraph.</p>
```
  
### CSS Color
  
```
body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
```
  

