# python-labyrinth
a simple program that make a labyrinth in python<br />
the only customisation is the size of the maze with the variable in main.py<br />
output is output.png<br />
/!\ over 128 * 128 you gonna have some time to wait for the generation /!\ <br />
you can switch between the black and white and RGB version by changing the second line of main.py :<br />
-black and white : from lab import Labyrinth<br />
-RGB : from lab_rgb import Labyrinth<br />
and the line nine of main.py :<br />
-black and white : image_lab = Image.new("L", (size, size))<br />
-RGB : image_lab = Image.new("RGB", (size, size))<br />
