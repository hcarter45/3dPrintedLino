<h1>3dPrintedLino</h1>
Replicating lino print making through the use of a 3d printer and free software.

Pick an image that you would like to print and save it to your computer. <br>
<img width="25%" height="25%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/lino.jpg?raw=true"></img>

Open up the image with paint 3d. It comes free and preinstalled with windows 10. (Photoshop has tools to select specific colors that would make this process even easier, if you have access to that paid software.<br>
<img width="50%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/Capture.PNG?raw=true"></img><br>

Choose the magic select tool. I recommend that you do not crop out the borders as it is helpful to have a common base for the various prints. (This will make more sense later)
<br>
<img width="50%" src="https://github.com/hcarter45/3dPrintedLino/blob/master/magicSelect.PNG?raw=true"></img><br>
Pick a color you want to isolate first. Using the magic select tool add all of the chosen color and the border, but remove every other color. The tool gets smarter and becomes better at selecting the desired colors overtime, but expect to spend several minutes. Click done to end the magic select tool. Drag the selected image away from the unselected image using the drag tool that appears. Cut the image you selected, that isolated only one color and then click menu, new to create a new portrait. Do not save the inital image that you downloaded because you are going to need to isolate various other layers and you want the base image to do so. 

With the isolated image, crop out the background white if it appears.<br>
<img width="50%" src="./black Selected.png"></img><br>
Save this image as an svg file.

Repeat this process of isolating each color until you have every color in your image isolated.
<br>
<img width="20%" src="./black.svg"></img><img width="20%" src="./brown.svg"></img><img width="20%" src="./brownRed.svg"></img>
<img width="20%" src="./tan.svg"></img> <br>

<h4>I chose to use fusion360 as my cad software to edit the .svg files to make them ready to print on the 3d printer, but any other cad program should work. (Fusion360 has a free student license, and it works on both PCs and Macs.)</h4>

Right click on the base component and create a new component, activate it, and name it accordingly. <br>
<img width="50%" src="./newComponent.png"></img><img width="50%" src="activateComponent"></img><br>
                                                                                       
Open up the .svg file in your cad software. Highlight the entire sketch and click extrude. Extrude the sketch up 6mm.<br>
<img width="50%" src="./highlightSketch.png"></img><img width="50%" src="./sideDepth.png"></img><br>
                                                                                        
Repeat creating/naming/activating a new component, highlighting the sketch and then extruding it to 6mm until all of the isolated colors have been extruded.

Hide all of the bodies, and show all of the sketches for every component. Create a rectangular sketch bordering the entire set of sketches. 
<br><img width="50%" src="./CreateBase.png"></img>

Extrude this border 4mm and create a join with each of the isolated extrusions. You can measure this joined extrusion to ensure that it is 10mm. (The jig I used was 10mm, you can change this extrusion depth, but the top layer has to be equal to the size of the jig you create later.)<br>

Save the joined 3d extrusion as a .stl file. Repeat the process of creating a base extrusion and joining it with each isolated extrusion. Print out the .stl file. (I used simplify3d, which is not free to create the format my 3d printer needs, but there are various other free slicing software programs that often come included with 3d printers.)

Apply paint to the extruded side until it looks like the paint covers the entire surface well.
<br> <img width="50%" src="./2F937DEA-0536-4980-92D2-D6CB1F59523E.JPG"></img><br>

Create a cardboard jig that is the same height (or at least close) to the height of the highest extrusion.
<br><img width="50%" src="./C22B0429-D917-45C6-BA48-F36D38ECC745.JPG"></img><br>

Place the 3d printed lino inside the jig and then place a piece of paper on top of it. Place a larger piece of paper on top of the printing paper to ensure little movement in the press stage.

Roll the print through.
<br><img width="50%" src="./6BB98BA6-1954-45E5-B04C-A49F44883516.JPG"></img><img width="50%" src="./C3090B28-472C-4DBD-AF61-2B562F819597.JPG"></img>

Repeat this process with using all of the paint colors and the respective 3d printed parts. Ensure that the printed paper is aligned before rolling it through each time. 

