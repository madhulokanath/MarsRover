# MarsRover
Mars Rover

SPECIFICATION:

 A squad of robotic rovers are to be landed by NASA on a plateau on Mars. The navigation team needs a
 utility for them to simulate rover movements so they can develop a navigation plan.
 
 A rover&#39;s position is represented by a combination of an x and y co-ordinates and a letter
 representing one of the four cardinal compass points. The plateau is divided up into a grid to
 simplify navigation. An example position might be 0, 0, N, which means the rover is in the bottom
 left corner and facing North.
 
 In order to control a rover, NASA sends a simple string of letters.The possible letters are:
    'L'; – Make the rover spin 90 degrees left without moving from its current spot
    'R'; - Make the rover spin 90 degrees right without moving from its current spot
    'M';. Move forward one grid point, and maintain the same heading.
 
	Assumptions:
		1. Graph left down corner vertices is always: (0,0)
		2. The Rover can move with in the graph only.
		3. A Initial postion  should always be inside the graph
		4. If any command takes Rover outside graph, those commands are skipped
		5. Default initail position is '0 0 N'
		6. If intitail position is invalid, its set to deafult position.
		7. Default direction is North 'N'
		8. If the right  Coordinate of Rover is more than the graph Right cordinate, Its a wrong Initial position.

	How To Run:
        1. Enter once for the first time Upper Right Coordinates: as "xpos ypos"
        2. Now we enter a loop where we can reposition any number of Rovers until you press "Escape(Esc)".
        3.Provide Initial Position as "xpos ypos Direction"
        4. xpos value range : 0 <= xpos <=2147483647.>
        5. ypos value range : 0 <= ypos <=2147483647.>
        6. Direction : 'N' for north
                       'S' for South
                       'W' for West
                       'E' for East
        7. Provide series of Commands as a string without spaces between commands:
                'L' for Left Turn
                'R' for Right Turn
                'M' for Move
        8. You shall be given Final postion of Rover after the movemet. "xpos ypos Direction".

Author: Madhu Lokanath
Phone:3126468532
Email: Madhu.lokanath@gmail.com
