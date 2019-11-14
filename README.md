This is the MarsRover Project as defined in the IronHack document
http:learn.ironhack.com/#/learning_unit/8215

Contributor:
Tomasz Walasek, 
November 2019

Features:

  1. Configurable number of vehicles (1..8).
  2. Resizable rectangular scene.
  3. The route for each vehicle is defined in a string of commands. Valid commands are
        f - move forward
	      b - move backward
	      l - turn left
	      r - turn right
  4. Each vehicle keeps a log of all commands processed and the route travelled
  5. Collision types detected
        - boundaries
        - obstacles
        - other vehicles
  6. Collision handling
        - animate vehicle icon
        - turn right automatically

NOTE: Each vehicle can be set up using the function

roverSetup(initial-x-coordinate, 
           initial-y-coordinate,
	   initial direction,
           color,
           command-string);

The setup for this demo consistes of 7 rovers and is as follows. It can be found at the bottom of the JS script and edited to your need. 

roverSetup(0, 0, "S", "red", "ffffffff");
roverSetup(0, 1, "S", "green", "fffffffffffffffffff");
roverSetup(0, 2, "S", "blue", "fffffffffffffffff");
roverSetup(0, 3, "S", "brown", "fffffffff");
roverSetup(0, 4, "S", "magenta", "fffffffffffffffff");
roverSetup(0, 5, "S", "cyan", "fffffffffffffffff");
roverSetup(0, 6, "S", "orange", "fffffffffffffffff");











