GridWorld
=========

[GridWorld resources](http://apcentral.collegeboard.com/apc/public/courses/teachers_corner/151155.html) from AP Computer Science.

World = 25x25
Alive cells = x
Dead cells = -
Patterns are chosen in code, Maybe by user later
Runs forever till all cells are dead
Time interval is .5 seconds
Warps around
gen 1 = 
	0 1 2 3 4 5 6 7 8 9
      0	x - - - - - - - - - 
      1 x x - - - - - - - - 
      2 - x x - - - - - - - 
      3 - - x x - - - - - - 
      4 - - - x x - - - - - 
      5	- - - - x - - - - - 
      6 - - - - - x x - - - 
      7 - - - - - - x x - - 
      8 - - - - - - - - - - 
      9 - - - - - - - - - - 


gen 2 = 
	0 1 2 3 4 5 6 7 8 9
      0	x x - - - - - - - - 
      1 x - x - - - - - - - 
      2 x - - x - - - - - - 
      3 - x - - x - - - - - 
      4 - - x - x - - - - - 
      5	- - - x x - - - - - 
      6 - - - - - x x x - - 
      7 - - - - - x x x - - 
      8 - - - - - - - - - - 
      9 - - - - - - - - - - 


gen 3 = 
	  0 1 2 3 4 5 6 7 8 9
        0 - - - - x - - - - -
        1 - - - x - x - - - -
        2 - - x - - - x - - -
        3 - x - x - x - x - -
        4 x - - - x - - - x -
        5 - x - x - x - x - -
        6 - - x - - - x - - -
        7 - - - x - x - - - -
        8 - - - - x - - - - -
        9 - - - - - - - - - - 