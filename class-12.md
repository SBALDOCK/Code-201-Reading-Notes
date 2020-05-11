![Stick](https://images.unsplash.com/photo-1456143077270-30de0a1bf7bc?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

### Docs for the HTML canvas Element & Chart.js

#### Chart.js API

* Charts are better for displaying data visually than tables
* Chart.js uses HTML5's `canvas` element to draw the graph onto the page
* You must copt the file into the directory that you're working in
* Step 1 - Add Canvas element with ID
* Step 2 - Write script to retrieve the context of the canvas
* It is relatively easy to draw a nice pie chart, line chart, or bar chart
#### Chart.js Docs

* It is necessary to install chart.js and there are various methods to do so
* Chart.js cna be integrated with plain JavaScript
* In order to create a chart, one must **instantiate** the `Chart` class in HTML
  * Then perform `getElementByID` to find the element containing the ID assigned to the chart
  * Then create an object literal or constructor function with parameters
* Colors, gradient patterns, and other styling can be applied
* It is important to apply accessibility standards to these charts
* charts cannot be expressed through relative size values, but rather fixed width and height
  * The chart does not adjust automatically based on the display size
  * there are several options in JavaScript to make configuration adjustments
* There are options for event response such as **click and hover**

#### Canvas API

* Basic Usage
  * `<canvas>` looks similar to an `img` element, but only has two attributes: width and height. 
    * It has an opening AND closing tag
    * It does not need the src or alt attributes
    * If unspecified, the default dimensions are 300px wide by 150px high
    * The ID attribute is identical to an HTML ID attribute that can be used for CSS styling
    * Styling the `<canvas>` does not affect the actual drawing on the canvas
    * Provide fallback content inside the `<canvas>` element
    * **Rendering contexts** are used to create and manipulate the content shown
    * Example skeleton template:
      `<!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8"/>
          <title>Canvas tutorial</title>
          <script type="text/javascript">
            function draw() {
              var canvas = document.getElementById('tutorial');
              if (canvas.getContext) {
                var ctx = canvas.getContext('2d');
              }
            }
          </script>
          <style type="text/css">
            canvas { border: 1px solid black; }
          </style>
        </head>
        <body onload="draw();">
          <canvas id="tutorial" width="150" height="150"></canvas>
        </body>
      </html>`

* **Drawing Shapes with canvas**

  * `<Canvas>` uses a **coordinate space** which is essentially an x/y axis
  * 1 unit usually corresponds to 1 pixel on the canvas
  * The origin is positioned in the  top left corner to start
    * All elements are placed relative to the origin
  * `<Canvas>` supports two primative shapes: recatangles and paths (lists of points connected by lines)
    * Rectangles use three functions
      * **fillRect** (x, y, width, height) - Draws a filled rectangle
      * **strokeRect** (x, y, width, height) - Draws a rectangle's outline
      * **clearRect** (x, y, width, height) - Clears area to make it transparent
    * Example rectangle shape: 
      `function draw() {
          var canvas = document.getElementById('canvas');
          if (canvas.getContext) {
            var ctx = canvas.getContext('2d');

            ctx.fillRect(25, 25, 100, 100);
            ctx.clearRect(45, 45, 60, 60);
            ctx.strokeRect(50, 50, 50, 50);
          }
        }`
    * A path is a list of points connected by segments
      * First create a path
      * Use drawing commands to draw into the path
      * Stroke or fill the path to render it
      * **beginPath()** - Creates new path
      * **Path Methods** - Methods to set different paths for objects
      * **closePath()** - Adds a straight line to the path
      * **Stroke()** - Draws he shape by stroking outline
      * **fill()** - Draws solid shape by filling the path's content area

* **Applying styles and colors**

  * Use **fillstyle** and **strokestyle** to apply colors
    * `fillstyle = color` - Sets the style used when filling shapes
    * `strokeStyle = color` - Sets outline style
    * Color is a string representing a CSS color, gradient object, or a pattern object
    * Use for loops to draw a grid of rectangles, each with a different color
    * Set the **globalAlpha** or assign a transparent color ot the stroke and/or fill style to draw semi-transparent shapes
      * **globalAlpha** accepts a range from 0.0 (full transparency) to 1.0 (opaque)
  * line style properties - Several examples
    * **lineWdith = value** - sets the width of lines drawn in the future
    * **lineCap = type** - Sets the appearance of the endds of lines
    * **lineJoin = type** - Sets the appearance of the "corners" where lines meet
  * You can also add patterns, gradients, dashes and other border options, and shadows

* **Drawing text**

  * There are two ways to draw text with `<canvas>`
    * **fillText(text, x, y [, maxWidth])** - filled a given text at a specific coordinate on the grid
    * **strokeText(text, x, y [, maxWidth])** - Strokes text at the coordinate
    * Text Styles
      * **font** - Aligns with CSS font property
      * **textAlign** - Start, end, left, right or center
      * **textBaseline** - top, hanging, middle, alphabetic, ideographic, bottom
      * **direction** - ltr, rtl, inherit
  * Measure text with **measureText()**

[Next Topic](class-13.md)  
[Main Page](README.md)