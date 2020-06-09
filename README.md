# Your Task

You’re part of the team that explores Mars by sending remotely controlled vehicles to the surface of the planet. Develop an API that translates the commands sent from earth to instructions that are understood by the rover.

# Input and output

* Rover starts at position (0,0) (bottom left corner) of a 4x4 grid.

* The rover receives a character array of commands.
    * 'F' means forward
    * 'R' means rotate right 90 degrees
    * 'L' means rotate left 90 degrees
    * Example: "FRFLF"
    
* Implement a function that takes a character array of commands and computes the final position and direction (N,W,S,E)
    
* Example: 
   * Input: "FRFLF"
   * Output: "1 2 N"

# Note

* Opposite edges are connected.
