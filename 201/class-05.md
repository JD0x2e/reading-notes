# Reading

## HTML Media

**Alternative text** or 'alt' for short; Its value is supposed to be a textual description of that particular image, for use in certain situations where the internet connection may be particularly slow so the webpage cannot render the image, so you can hover over it and it will tell you what it is. Other reasons why you would use an alt attribute would be;

- The user is visually impaired and is using a screen reader.
- The spelling of the file or path name might be wrong.
- The browser doesn't support images, they may use a text-only browser such as Lynx, which displays alt text.
- Users may have turned off images to reduce the data transfer, common on mobile phones.

As with links, you can also add the 'title' attribute to images, to provide more information if needs be. However, title does have a number of accessibility problems, screen reader support is very unpredictable and most browsers don't show it unless hovered over with a mouse. To fix this, it would be better to include supporting info in the main article text.

**Figure/figcaption elements**; These were created to provide a semantic container for figures. They clearly link the figure to the caption.

An example of this (taken from [MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)):

```js
<figure>
  <img src="images/dinosaur.jpg"
       alt="The head and torso of a dinosaur skeleton;
            it has a large head with long sharp teeth"
       width="400"
       height="341">

  <figcaption>A T-Rex on display in the Manchester University Museum.</figcaption>
</figure>
```

**Gif image & SVG image**; The difference between these two in simple terms would be, a gif (otherwise known as a Graphics Interchange Format') would be a great choice to use for very simple images or animations. They have been very popular for a long time, due to the simplicity and compatibility. Whereas an SVG (Scalable Vector Graphics) would be used best for an image which needs to be drawn accurately to different sizes and scales. They are ideal for diagrams, icons and other images which need to be drawn at different sizes.

I would use a jpeg image type if I wanted to display a screenshot on my website because the file size is a lot smaller than when using a png.

## Learn CSS

A foreground color is the color of the element, so if you change the color of text to orange for example, this will change the 'foreground'. Whereas background color is for changing the text's background color, so if you changed it to yellow, you would have a yellow background behind the text and orange text color.

If a friend asked me to give his colorless blog a touch up, I would first start by picking some colours to add in, probably some lighter colour for the background and then make the text slightly darker so it has a nice contrast. I would then think about adding some borders and padding and margin (box model), so it would create nice shapes etc.

When picking a certain font for your HTML document, you ideally want to use 'web safe fonts'. This is because as web developers have no way of knowing which fonts will be able to be seen from different computers, if we use a web safe font then chances are they will be able to be seen from every single computer. This is important if we want to access a wide variety of users.

**Font-size**; The font size property purely allows you to change the size of the text.

**Font-weight**; The font weight property allows us to change how bold the text is. There is many different values available, such as, 'light', 'normal', 'bold', 'extrabold', '100-900', etc.

**Font-style**; The font style property allows us to turn italic text on or off. The different values are, 'normal', 'italic', and 'oblique'.

To add space around a h1 element, you could either use `word-spacing` or `letter-spacing`. These properties allow you to set the spacing between the letters and words in your text.

For example:

```js
h1 {
letter-spacing: 5px;
word-spacing: 5px;
}
```



