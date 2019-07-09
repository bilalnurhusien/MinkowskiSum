
Build:
	
	$ make

Usage:

	$ ./minkowski <num-of-polygon1-verticies> <num-of-polygon2-verticies>
	$ ./minkowski -f <input-file> # CSV input file
	
Example:

	$./minkowski 6 5 # For a hexagon and a pentagon

	$./minkowski -f inputDataExample.txt

Library Installation:

	For rendering images, please install SFML library.

	$ sudo apt-get install libsfml-dev

Output: 

	Minkowski sum

	# For two pentagons
	$ ./minkowski 5 5 

![alt text](https://github.com/bilalnurhusien/MinkowskiSum/blob/master/images/MinkowskiDiffPentagon.png)

	# For a hexagon and a square
	$ ./minkowski 6 4 

![alt text](https://github.com/bilalnurhusien/MinkowskiSum/blob/master/images/MinkowskiDiffSquareHexagon.png)

        # For input file
        $ ./minkowski -f inputDataExample.txt

![alt text](https://github.com/bilalnurhusien/MinkowskiSum/blob/master/images/MinkowskiDiffInputExample.png)
