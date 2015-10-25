###### Graphics Programming - Exercise 6
# Scalable Vector Graphics
In this exercise we will look at the SVG tag in HTML.

## Exercises
Save each exercise as a separate source file.

1. Create a blank HTML file.

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <style type="text/css"></style>
      </head>
      <body>
        <script type="text/javascript">
        </script>
      </body>
    </html>
    ```

1. Insert SVG tags.

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <style type="text/css"></style>
      </head>
      <body>
        <svg></svg>
		<script type="text/javascript">
        </script>
      </body>
    </html>
    ```

1. Add a red circle, centred at (100, 100) and with radius 20.

    ```html
    <svg>
	  <circle cx="100" cy="100" r="20" fill="red" />
	</svg>
    ```

1. Add a blue rectangle, starting at (50, 50) and with width 100 and height 200.

    ```html
	<rect x="10" y="10" width="100" height="200" fill="blue" />
    ```
	
1. Add your name in green, starting a (50, 50) and with font size 24.

    ```html
	<text x="50" y="50" font-size="24" fill="green">Ian</text>
    ```
	
1. Have the circle drawn on top of the rectangle, rather than behind it.

1. Put a black border around the circle.

    ```html
	<circle cx="100" cy="100" r="20" fill="red" stroke="black" />
    ```
	
1. Use CSS to set the colours of the circle instead of using attributes to the SVG tag.

    ```html
    <style type="text/css">
	  circle {
	    fill: red;
		stroke: black;
	  }
	</style>
	...
	<circle cx="100" cy="100" r="20" />
    ```

## Advanced exercises

1. Use JavaScript to move the circle to be centered at (120,120) after one second.

1. Use JavaScript to change the colour of the circle to green after two seconds.

1. Draw PacMan on the screen using SVG.

## Notes

- [MDN SVG Tutorial](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial)

- You can find numerous examples of manipulating SVG elements using JavaScript online. One is example is [Using Javascript to control an SVG](http://www.petercollingridge.co.uk/data-visualisation/using-javascript-control-svg).