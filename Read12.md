## charts 
Charts are far better for displaying data visually than tables.

• A great way to get started with charts is with Chart.js, 
Drawing a line chart 

• The first thing we need to do is download Chart.js. Copy the Chart.min.js 

• To draw a line chart, the first thing we need to do is create a `canvas` element in our HTML

• The HTML `<canvas>` element is used to draw graphics, on the fly, via JavaScript.

• The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics.

• Canvas has several methods for drawing paths, boxes, circles, text, and adding images

#### Example:
`<canvas id="myCanvas" width="200" height="100"></canvas>`


### Drawing shapes with canvas:
we ca refer html page with coordinate space , All elements are placed relative to this origin. (x,y)

#### Drawing Rectangle:
There are three functions that draw rectangles on the canvas:

`fillRect(x, y, width, height)`
Draws a filled rectangle.

`strokeRect(x, y, width, height)`
Draws a rectangular outline.

`clearRect(x, y, width, height)`
Clears the specified rectangular area, making it fully transparent.

### Drawing paths:
A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color

### we can create path by :

1.create the path.\
2. use drawing commands to draw into the path.\
3.Once the path has been created,we can stroke or fill the path to render it.


## Applying styles and colors
 To apply colors to a shape, there are two important properties we can use: `fillStyle `and `strokeStyle`.

Transparency : we use \
`globalAlpha = transparencyValue`

#### Line styles:
There are several properties which allow us to style lines.

`lineWidth = value`
Sets the width of lines drawn in the future.

`lineCap = type`
Sets the appearance of the ends of lines.

`lineJoin = type`
Sets the appearance of the "corners" where lines meet.

`miterLimit = value`
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

`getLineDash()`
Returns the current line dash pattern array containing an even number of non-negative numbers.

`setLineDash(segments)`
Sets the current line dash pattern.
lineDashOffset = value
Specifies where to start a dash array on a line.


## Drawing text

The canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

`strokeText(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


### Styling text
`font = value`   To specify height of font and family..

`textAlign = value`\
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

`textBaseline = value`
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

`direction = value`
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.