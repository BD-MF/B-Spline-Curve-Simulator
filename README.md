# A B-spline curve simulator

I used glfw3 and glew

Compile:
	-> $ g++ main.cpp -lGL -lGLU -lglut -lglfw

Key List:

	-> a,d = increase/ decrease order
	-> right arrow = show geometry
	-> up/ down = increase/ decrease paramter step
	-> s = clear window
	-> r = surface of revolution
	-> q,e,w,z = rotating the object created by surface of revolution

Mouse actions:

	-> Click = to create new points
	-> Click on an existing point = will focus that point and allow to move it
	-> Right click on an existing point = delete the point
