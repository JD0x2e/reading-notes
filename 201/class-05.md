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

**Gif image & SVG image**; The difference between these two in simple terms would be, a gif (otherwise known as a Graphics Interchange Format') would be a great choice to use for very simple images or animations. They have been very popular for a long time, due to the simplicity and compatibility. Whereas an SVG (Scalable Vector Graphics) would be used best for an image which needs to be drawn accurately to different sizes and scales. They are ideal 



