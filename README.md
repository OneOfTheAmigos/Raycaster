# Raycaster
It's a raycaster in python

drawing.py is the file you want to execute

In order to run it, you'll need the following libraries: 
- pygame
- math
- numpy

Controls:
Use the left and right arrow keys to look around
Use the up and down arrow keys to move forward and backward
Press the spacebar to switch between first person mode and top view mode

This is outlined in the comments of the code, but near the top of drawing.py, there is a variable called PerformanceValue
If you change it from 1 to any of the following values, it will have the following effects: 
#assuming FOV == 100:
# >1 = worse graphics and the performance isn't drastically effected
# 1 = rendered rectangle for every 5 pixels (really smooth performance)
# 0.8 = this is the best balance in my opinion [default]
# 0.4 = twice as good looking as 0.8 but it's twice as slow
# 0.2 = pixel perfect rendering (but it's really laggy and slow)
# <0.2 = won't render anything
#anything between 1 and 0.2 that wasn't mentioned above will create a weird transparent effect
#anything 0 or below will break it

There is no player collision, so feel free to clip through the walls as you please
You can even venture outside the box realm and into the endless desert
