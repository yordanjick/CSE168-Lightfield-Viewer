# CSE168-Lightfield-Viewer
This is a novel lightfield Viewer created using the OpenGL engine.
It is created to read in and load lightfield data pulled from the new Stanford Lightfield Archive.
Once loaded, you can use the arrow keys to change the aperture size and focus, as well as clicking and dragging
the mouse to change the camera position.

Along with using the OpenGL library, it also uses the open source stb_image library in order to load in images as data.

This program was created in Visual Studio, so while other compilation methods may work,
I personally compiled and ran using VS.

This program takes in up to 2 command line arguments, with one of them being required. The 1st argument is the
relative path to the folder containing the light field data. For example, 'data/legos' would be a valid folder.
The 2nd optional argument is a flag for how much of the data you want loaded in. '-f' for the full dataset,
'-m' for a medium dataset (9x9), or '-s' for a small dataset (5x5). While the full dataset looks the most accurate and has the
least artifacting, it can take a while to load. By default, the full dataset is used if no flag is specified.

You can see examples of the results this Lightfield Viewer achieves below.


