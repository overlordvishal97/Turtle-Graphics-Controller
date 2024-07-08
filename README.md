# Turtle-Graphics-Controller
This project is a simple controller for the Turtle graphics library in Python. It allows the user to control the turtle's movements using keyboard inputs.

# Controls
w: Move the turtle forward by 10 units
s: Move the turtle backward by 10 units
a: Turn the turtle counter-clockwise by 90 degrees
d: Turn the turtle clockwise by 90 degrees
c: Clear the drawing and reset the turtle to its initial position

# How it Works
The code imports the necessary modules from the Turtle graphics library.
A turtle object (tim) and a screen object (screen) are created.
Five functions are defined to control the turtle's movements:
move_forwards: Moves the turtle forward by 10 units.
move_backwards: Moves the turtle backward by 10 units.
counter_clockwise: Turns the turtle counter-clockwise by 90 degrees.
clockwise: Turns the turtle clockwise by 90 degrees.
clear_drawing: Clears the drawing and resets the turtle to its initial position.
The screen.listen() method is used to enable keyboard input.
The screen.onkey() method is used to bind each function to a specific key press.
The screen.exitonclick() method is used to keep the window open until the user clicks on it.

# Run the Code
To run the code, simply execute the Python script. The Turtle graphics window will appear, and you can use the keyboard controls to move the turtle around and create your own drawings.
