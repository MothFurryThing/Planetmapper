This is relatively complicated to use, so i will attempt to describe this as best as possible.
If need be, dm me on discord and ask for help, this, as stated, is complicated, at least for someone with no blender experience.

Set 1

	the file itself
	
	The file itself is made with blender 4.2.3 LTS, there should be no issues with later or earlier versions so long as they have the noise and voronoi node.
	If not, god help you.
	
	If you notice anything bloating the file size like unused images, remove them and send that to me, i can't find out how to remove those images even after a week.
	
	I have 4 base node groups setup, Star surface and corona mapping, icecap mapping, and landmass mapping, i think they look decent, they might not, idk.
	
Set 2

	instructions
	
	Open file with blender, as stated, any version with noise and voronoi.
	
	check whichever node group you want to use, it doesn't matter, you'll probably make your own considering that i only have 3 of them.
	
	Set 2.1
		
		The star surface mapping node has 3 outputs, one for noise, one for sunspots, and one for the inverted sunspots, if your GPU is fast enough, using that last one is faster than inverting the sunspot image in GIMP or Photoshop.
		
	Click render, render image, wait 15 minutes cause you have an integrated GPU.
	
	SAVE THE IMAGE, I KEPT FORGETTING TO DO THAT MULTIPLE TIMES AND SPENT 5 HOURS TROUBLSHOOTING A NONEXISTENT PROBLEM BECAUSE OF IT.
	
	And enjoy the newly created, probably better than directly ripping from space engine planetmap that you get.
	
Set 3

	the ugly one
	
	To render the corona, you have to make the sphere invisible to both the scene camera, and the render camera, and make the cyclinder (Corona) visible to both.
	
	Make whatever changes you want to it, it doesnt matter, no one will notice it much, this is just an extra thing to do if you want it to be stock compatible.
	
	Click on the camera object in the scene, set the up and down fov to 45 and -45 respectively, set the width of the rendered image to 4x the height, it doesn't matter what resolution you use, just make it 4/1.
	
	Click render image and boom, a semi decent corona that probably doesnt suck and glitch out the game if you export it right which i only know PNG works.
	
And that's how to use this stupid, very, very brute forced method planet mapper, holy shit does it suck.
