# Welcome to My Bouncing Box
***

## Task
Complete an index.html file with the missing javascript code in order to replicate the famous Windows Screensaver - Bounce

Example - https://www.youtube.com/watch?v=NVp6GMHpYvo

You need to move the "div" with the id my_bouncing_box diagonally.

We defined the (0, 0) coordinate (x, y) at the very top left of your screen.
The box must move diagonally and each time it reaches a border it will change direction of the border it touched.
If the box is moving bottom-right:
-- when it reaches the bottom border it will go top.
-- when it reaches the right border it will go left.

We let you choose the speed rate for the movement of the box. Between 0.3 and 1 second seems to be good values.

You cannot change the value of the html, moving the box needs to be done using javascript. (Yes, JQuery is not allowed yet.)
```
$>cat index.html
<html style="background-color: black">
    <div
        id="my_bouncing_box"
        style="background-color: blue; border-radius: 3px; position: absolute; left: 0px; top: 0px; min-width: 100px; min-height: 100px; text-align: center; font-weight: bold; color: #999;"
    >
        Not loaded
    </div>
    <script type="text/javascript">
        // YOUR CODE
    </script>
</html>
$>
```
You don't have to handle any screen resizing.
Do NOT use canvas tag.

## Description
The problem was solved using JavaScript functions and properties to move the  box  diagonally so that each time it reaches a border it will change direction of the border it touched

## Installation
No Installation is required for this project 

## Usage
You can display this project by running it on a browser to preview or use a static html page renderer in order to preview your bouncing box. Enjoy !

