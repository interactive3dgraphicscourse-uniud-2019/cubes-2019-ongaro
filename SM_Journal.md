#SceneMaker' s Journal
##Ongaro Luca mat. 133639

After reading the assignment i' ve decided to represent the front face of a medieval castle, and using as an animation the lifting bridge as a minimum; more could be added later on.
I' ll now try to get familiar with the starting code and box creation/placement methods.
After realizing the front face alone could be a bit too simple, i' m considering designing an entire (but not too massive) fort. An animation i' m also considering is partolling guards, represented simply of course.

Made paper sketches of the castle' s front view and top view.
I' ll now start positioning boxes to form the front face
I realized that the structure is symmetrical, so i' m considering positioning half the structure at a time with a function.
Half of the wall structure is done, no problems so far. Switching to corner towers and merlons now
Merlon placing is taking up quite a lot of code lines, so i' ll definitely think of a more efficient way to place them with some functions.
The function for placing tower merlons is done and working. Gonna work on a function that makes a cluster of 6 merlons to rotate/traslate where needed
The function for merlons clusters is also done, works just fine and saves quite some lines.
Finished the left half of the structure, proceding to making it into a function to easily duplicate it mirrored.
Function "halfStructure" completed, works as intended. Proceding in making the lifting bridge and relative animation.
Lifting bridge is up and rotating as intended.
Starting to experiment with textures
Getting some simple textures, i' m taking them from the websites "Unsplash" and "TextureLib" wich assures they are copyright-free images
I' m now starting to work on the heightmap function.
The function now correctly creates a floor following the "heightmap.png" picture in the "texture" folder, i just have to tweak its numbers to make it look good.
I reduced the dimension of the heightmap picture to keep FPS at 60, and tweaked the position of the floor:
now the ground where the castle lies and the road connected to it with the bridge are brown, the pit is blue as to represent water and the terrain around it is green.
 



