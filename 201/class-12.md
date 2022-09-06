# Class 12

## JavaScript Canvas

 *What does the 'canvas' allow a developer to acheive?*

`<Canvas>` allows you to draw 2D graphics using Javascript. It requires a 'width' and 'height' attribute. You can use DOM manipulation to change the values of these attrubutes like normal.

 *What is the importance of the closing `</canvas> tag?`*
 
You will also need to use a closing tag `</Canvas>` unlike the img element which is self closing. Any content which is between the opening/closing tags is called the 'fallback content' and will be displayed on the page only if the browser doesn't support canvas. Pretty much most browsers nowadays will support the canvas element so you shouldn't have a problem using it.

 *Explain what the getContext() method does.*

The `getContext()` methods returns a render context object. It takes one argument which is the type of the context so for example you can use, `2d`, to get a 2D rendering context object, which is an instance of the `CanvasRenderingContext2D` interface.

This allows you to draw shapes, text, images and other objects.

Example code:

```js
let canvas = document.querySelector('#canvas');
let ctx = main.getContext('2d');
```

### Fills and strokes

`fillStyle` & `strokeStyle` are both properites of the 2d drawing context. 

fillStyle fills in the shape with a specific color, gradient or image.

strokeStyle adds colors to the edges of the shapes.

## Chart.js Documentation

*What is Chart.js and how can it be brought into your project?*

Chart.js is used to make HTML-based charts. It comes with many different types of chart types, a few examples would be:

1. Line chart
2. Bar chart
3. Area chart

To implement chart.js into our project, we would first need a canvas on the page. You should give canvas its own container so it's better for responsiveness on the webpage. 

We then would need to implement a script with a src attribute including the chart.js url  -(https://cdn.jsdelivr.net/npm/chart.js).

Now we create the chart by adding some script tags, which contain information inside. Inside the script tags, we could add an array of different months for example and then an object with different info inside such as colors, labels, data. A great example of this is from chart.js website:

```js
<script>
  const labels = [
    'January',
    'February',
    'March',
    'April',
    'May',
    'June',
  ];

  const data = {
    labels: labels,
    datasets: [{
      label: 'My First dataset',
      backgroundColor: 'rgb(255, 99, 132)',
      borderColor: 'rgb(255, 99, 132)',
      data: [0, 10, 5, 2, 20, 30, 45],
    }]
  };

  const config = {
    type: 'line',
    data: data,
    options: {}
  };
</script>
```


 
 
 











