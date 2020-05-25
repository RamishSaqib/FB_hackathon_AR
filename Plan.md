1. Idea
	> Plot equations on a graph and view it as a messenger camera effect
2. Features
	> Premade equations 
		# Buttons for each equation that is tied to showing the graph for said equation
			- x^2
			- Log(x)
			- Etc…
		# (extension) custom equations
		# (extension) read and plot equations from the camera 
	> Graph
		# Scale/resize 
		# Zoom 
		# Move 
		# Show x,y coords of a graph 
		# (extension) transformations: reflections, shifts, stretches, compressions
3. User Interaction
	> On screen slider: graph scale
	> Pinch: zoom
	> Drag: move
	> Tap: view x,y coords of a point on the graph
4. Design
5. Code
	> Is there a way to create graphs with spark or are we limited to premade graphs?
6. Tests
7. Implementation 
	> Code
		# Show/hide different graphs based on the selected preset
		# Graph object
		# Slider object
		# Bind the graph's size to the value of the slider
		# Bind the graph's position on screen to pan gestures
		# Bind the graph's scale/zoom level to pinch gestures' scale
		# Calculate x,y coord of the position of a tap on the graph object
	> Objects
		# Graph models for each equation
			- x
			- x^2
			- x^3
			- |x|
			- 1/x
			- x^(1/2)
			- x^x
			- Log(x)
			- e^x
			- / add more equations as needed /
8. Debug
9. Release
