<h1>3dPrintedLino</h1>
Replicating lino print making through the use of a 3d printer and free software.

Pick an image that you would like to print and save it to your computer. <br>
<img width="25%" height="25%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/lino.jpg?raw=true"></img>

Open up the image with paint 3d. It comes free and preinstalled with windows 10. (Photoshop has tools to select specific colors that would make this process even easier, if you have access to that paid software.<br>
<img width="50%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/Capture.PNG?raw=true"></img><br>

Choose the magic select tool. I recommend that you do not crop out the borders as it is helpful to have a common base for the various prints. (This will make more sense later)
<br>
<img width="50%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/magicSelect.PNG?raw=true"></img><br>
Pick a color you want to isolate first. Using the magic select tool add all of the chosen color and the border, but remove every other color. The tool gets smarter and becomes better at selecting the desired colors overtime, but expect to spend several minutes. Click done to end the magic select tool. Drag the selected image away from the unselected image using the drag tool that appears. Cut the image you selected, that isolated only one color and then click menu -> new to create a new portrait. Do not save the inital image that you downloaded because you are going to need to isolate various other layers and you want the base image to do so. 

With the isolated image, crop out the background white if it appears.<br>
<img width="50%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/black%20Selected.PNG?raw=true"></img><br>
Save this image as an svg file.

Repeat this process of isolating each color until you have every color in your image isolated.
<br>
<img width="20%" src="./black.svg"></img><img width="20%" src="./brown.svg"></img><img width="25%" src="./brownRed.svg"></img>
<img width="20%" src="./tan.svg"></img> <br>

<h4>I chose to use fusion360 as my cad software to edit the .svg files to make them ready to print on the 3d printer, but any other cad program should work. (Fusion360 has a free student license, and it works on both PCs and Macs.)</h4>

Right click on the base component and create a new component, activate it, and name it accordingly. <br>
<img width="50%" src="./newComponent.png"></img><img width="50%" src="activateComponent"></img><br>
                                                                                       
Open up the .svg file in your cad software. Highlight the entire sketch and click extrude. Extrude the sketch up 6mm.<br>
<img width="50%" src="./highlightSketch.png"></img><img width="50%" src="./sideDepth.png"></img><br>
                                                                                        
Repeat creating/naming/activating a new component, highlighting the sketch and then extruding it to 6mm until all of the isolated colors have been extruded.

Hide all of the bodies, and show all of the sketches for every component. Create a rectangular sketch bordering the entire set of sketches. 
<br><img width="50%" src="./CreateBase.png"></img>

Extrude this border 4mm and create a join with each of the isolated extrusions. You can measure this joined extrusion to ensure that it is 10mm. (The jig I used was 10mm, you can change this extrusion depth, but the top layer has to be equal to the size of the jig you create later.)

