# **Chart.js, Canvas**

## **Basic usage of canvas**

The id attribute isn't specific to the canvas element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). 

It is always a good idea to supply an id because this makes it much easier to identify it in a script.

```
<canvas id="tutorial" width="150" height="150"></canvas>
```

•	The canvas element differs from an img tag in that, like for video, audio, or picture elements, it is easy to define some fallback content

•	 If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

•	The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context.

```var canvas = document.getElementById('tutorial')
var ctx = canvas.getContext('2d');
```

## **Drawing shapes with canvas**

**Drawing rectangles**
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}
```
**Drawing paths**
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.beginPath();
    ctx.moveTo(75, 50);
    ctx.lineTo(100, 75);
    ctx.lineTo(100, 25);
    ctx.fill();
  }
}
```

**Lines**
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    // Filled triangle
    ctx.beginPath();
    ctx.moveTo(25, 25);
    ctx.lineTo(105, 25);
    ctx.lineTo(25, 105);
    ctx.fill();

    // Stroked triangle
    ctx.beginPath();
    ctx.moveTo(125, 125);
    ctx.lineTo(125, 45);
    ctx.lineTo(45, 125);
    ctx.closePath();
    ctx.stroke();
  }
}
```
## **Applying styles and colors**

If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

  * fillStyle = color   (Sets the style used when filling shapes.)

  * strokeStyle = colo (Sets the style for shapes' outlines.)

## **A globalAlpha**

The globalAlpha property is set at 0.2 which will be used for all shapes from that point on. Every step in the for loop draws a set of circles with an increasing radius. The final result is a radial gradient.

```
function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  // draw background
  ctx.fillStyle = '#FD0';
  ctx.fillRect(0, 0, 75, 75);
  ctx.fillStyle = '#6C0';
  ctx.fillRect(75, 0, 75, 75);
  ctx.fillStyle = '#09F';
  ctx.fillRect(0, 75, 75, 75);
  ctx.fillStyle = '#F30';
  ctx.fillRect(75, 75, 75, 75);
  ctx.fillStyle = '#FFF';

  // set transparency value
  ctx.globalAlpha = 0.2;

  // Draw semi transparent circles
  for (var i = 0; i < 7; i++) {
    ctx.beginPath();
    ctx.arc(75, 75, 10 + 10 * i, 0, Math.PI * 2, true);
    ctx.fill();
  }
}
```

## **A lineJoin**

The lineJoin property determines how two connecting segments (of lines, arcs or curves) with non-zero lengths in a shape are joined together (degenerate segments with zero lengths, whose specified endpoints and control points are exactly at the same position, are skipped).
There are three possible values for this property: round, bevel and miter


## **Patterns**

The type specifies how to use the image in order to create the pattern, and must be one of the following string values:

 * **repeat**
Tiles the image in both vertical and horizontal directions.

* **repeat-x**
Tiles the image horizontally but not vertically.

* **repeat-y**
Tiles the image vertically but not horizontally.

* **no-repeat**
Doesn't tile the image. It's used only once.



## **Drawing text**

The canvas rendering context provides two methods to render text:

**fillText** (text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. 

Optionally with a maximum width to draw.

**strokeText**(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position.

 Optionally with a maximum width to draw.



## **Styling text**

we are already making use of the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas:

• we use the font property to specify a custom font weight, size, and family.

• textAlign 

```ctx.textAlign = "left" || "right" || "center" || "start" || "end" ``` 

•	textBaseline
``` ctx.textBaseline = "top" || "hanging" || "middle" || "alphabetic" || "ideographic" || "bottom";``` 


•	direction 
```ctx.direction = "ltr" || "rtl" || "inherit";```


**"ltr"**
The text direction is left-to-right.

**"rtl"**
The text direction is right-to-left.

**"inherit"**

The text direction is inherited from the canvas element or the Document as appropriate. Default value.

