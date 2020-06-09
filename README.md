# Your Task

You’re part of the team that explores Mars by sending remotely controlled vehicles to the surface of the planet. Develop an API that translates the commands sent from earth to instructions that are understood by the rover.

# Input and output

* Rover starts at position (0,0) (bottom left corner) of a 4x4 grid.

* The rover receives a character array of commands.
    * 'F' means forward
    * 'R' means rotate right 90 degrees
    * 'L' means rotate left 90 degrees
    
* Example: "FRFLF"

# Requirements

* Implement wrapping from one edge of the grid to another. (planets are spheres after all)
