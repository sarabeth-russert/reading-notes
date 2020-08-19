## Code 201
#### Day 10

**Article Reading for - Charts.js**

*Chart.js* is a javascript plug-in that uses HTML5's *canvas* element to draw a graph onto the page. You can draw Line Charts, Pie Charts, and Bar Charts by making shapes using canvas. You can also add text.

1. Download Charts.js
2. copy Chart.min.js into your working directory
3. create an html page and use `<script>` to import the script Chart.min.js

The `<canvas></canvas>` element is used with an `id` attribute and option attributes `height` and `width`. If you do not assign a value for height and width the default is 300px wide and 150 high.

You can apply css styling to your canvas element but it will not affect what you have drawn within the element which you style using js. When no styling rules are applied to the canvas it will initially be fully transparent.

You can add fallback content to your canvas element so that if a browser does not support canvas it will display something else.

Canvas drawing is done on a grid, normally one unit in the grid is === 1px. Orientation starts top-left at 0,0.

to use canvas:
let canvasName = document.getElementById(id).getContext(2d);

Rectangles
- `fillRect(x, y, width, height)`
- `strokeRect(x, y, width, height)`
- `clearRect(x, y, width, height)`
- `Rect(x, y, width, height)` - draws to open path

Path
- `beginPath()`

Path Methods
- `closePath()`
- `stroke()`
- `fill()`

- `moveTo()`

Lines
- `lineTo(x, y)`

Arcs/Circles
- `arc(x, y, startAngle, endAngle, anticlockwise)`
- `arcTo(x1, y1, x2, y2, radius)`

Colors
- `fillStyle = 'color'`
- `strokeStyle = 'color'`

Transparency 
- `globalAlpha = rgba value`

Line Styles
- `lineWidth = value`
- `lineCap = butt/round/square`
- `lineJoin = round/bevel/mitter`
- `miterLimit = value`
- Line Dash
  - `getLineDash()`
  - `setLineDash(segments)`
  - `lineDashOffset = value`

Gradients, Patterns, Shadows also available to style.

Text
- `fillText(text, x, y (, maxWidth))` - maxWidth optional
- `strokeText(text, x, y (, maxWidth))` - maxWidth optional
- `font = value`
- `textAlign = start/end/left/right/center`
- `textBaseline = top/hanging/middle/alphabetic/ideographic/bottom`
- `direction = ltr/rtl/inherit`

[Return to the Main Page](README.md)