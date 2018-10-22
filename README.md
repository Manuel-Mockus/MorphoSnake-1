Installation: (Assuming you have all the requirements for the old morphosnake version) 

to run the updated version of morphosnake you have to update networkx to version 2.0 via:

sudo pip3 install networkx --upgrade

The library OpenCV (cv2) is also needed, you can install it using: 

sudo pip3 install opencv-python

To charge an image, make sure no graph file (.pkl)created by an older version is available. please delete it and try again
Keyboard commands:

Click on a node to select it, then use one of the following commands:

	't' to change the root to the selected node 
	'a' to mark the selected node as fertile
	'd' to delete the selected node
	'b' to modify the diameter of the node (just place the mouse where the new diameter is wanted and press the button)
	
Without any click, press on the keyboard:

	'n' to add a node to the skeleton pixel closest to the pointer
	'x' to delete edge closest to the pointer
	'u' to undo last modification
	'r' to rebuild the graph - restoring all manually deleted nodes and edges
	'alt+e' to hide the changes graphically
	



