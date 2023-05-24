# RAWD - Drawing-App
## Click this link to find project - https://studio.code.org/projects/applab/9CytgcNxI8MhUoeTNr7OrWSGCUmsEnzL3-wcqK0xUDw
Implemented in Java-Script. Helps users illustrate drawings and sketches using numerous colors and effects. ie: graffiti, etch, streak

Project Description:

This JavaScript project focuses on creating a simple painting application using the Code.org's "App Lab" environment. The project allows users to draw on a canvas, change colors, and apply various painting techniques.

The project begins by setting up the initial screen and canvas. It declares variables to store event lists for different colors and initializes other necessary variables.

The project defines event handlers for different buttons, such as the help button, back button, and start button, to navigate between screens. The "redbtn," "bluebtn," "greenbtn," and "blackbtn" buttons change the drawing color and set the stroke and fill colors accordingly. If the shift key is pressed while clicking, the program appends the event to the corresponding color's event list and draws a circle on the canvas.

The "mousemove" event on the "firstcanvas" updates the current event list based on the selected color. If the shift key is pressed, the event is appended to the event list, and a circle is drawn on the canvas.

The "deletebtn" button clears the canvas and resets all event lists. The "spraybtn" and "originalbtn" buttons call the "drawpainting" function to draw the saved painting. The "spraybtn" applies a spray effect by randomly varying the position and size of the circles, while the "originalbtn" reproduces the original drawing by using the recorded event data.

The "etchbtn" button applies an etching effect by drawing lines between consecutive events in each color's event list.

The project utilizes functions like "dotRadius" to calculate the size of circles based on the movement of the mouse, "randomYpos" to add randomness to the y-position of circles in the spray effect, and "drawColorSetRadius" to draw circles of different colors with varying sizes and positions based on the selected painting technique.

Overall, this project demonstrates the use of event handling, drawing functions, and basic JavaScript programming concepts to create a painting application with different colors and painting techniques. It provides users with the ability to draw and experiment with various painting effects.
