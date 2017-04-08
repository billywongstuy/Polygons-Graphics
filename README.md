# Polygons-Graphics

# Extra Code (color for 3D shapes)

## draw.py 

* add_points
  * new 'color=None' parameter
  * conditional statement to check if color == None
    * if color != None then append a 5 index point (x,y,z,1,color)

* add_polygon
  * new 'color=None' parameter

* draw_polygons
  * new if statement to change polygon's color if point has 5 indices


## parser.py

* 'color' added to ARG_COMMANDS
* color argument added to calls of add_box, add_sphere, and add_torus
* line == 'color case added to parser


# Why This Works

* when using matrix_multi, it only modifies the values in the first 4 columns
  * for r in range(4):
    	m2[point][r] = (VALUE)