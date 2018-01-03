
***How to create a 3d object in Bledar from an SVG file:***

</br>

**1. Start by making a file in illustrator.**

<img width="452" alt="screen shot 2017-10-22 at 10 08 27 pm" src="https://user-images.githubusercontent.com/30060990/33008459-0014cfa0-cd88-11e7-8516-df160e1e2233.png">

</br>
</br>
</br>
</br>

**2. If you have any type you need to convert it to outlines. You can do this by selecting the type and typing the hotkey CMD+SHFT+O**

<img width="479" alt="screen shot 2017-10-22 at 10 02 01 pm" src="https://user-images.githubusercontent.com/30060990/33008482-18adb108-cd88-11e7-8668-cfbb9b62dd66.png">

</br>
</br>
</br>
</br>

**3. All strokes will need to be expanded**
Another thing that you might want to do is crop the artboard to the size of the graphic. It seems to define where the gizmo (the moving tool x,y,z). In the pictures the gizmo is rather far away from the graphic, which makes editing a bit of a pain. This way the gizmo is attached much closer.

<img width="655" alt="screen shot 2017-10-31 at 10 14 33 pm" src="https://user-images.githubusercontent.com/30060990/33008383-bdbae860-cd87-11e7-801c-d5fccf3c8d4a.png">

</br>
</br>

With objects that are already filled in like the letters in this example extruding is simple, but with the smilely face, if you want it to be filled and the mouth and eyes knocked out, its not as simple. You will have to create a fill everything in in Illustrator. 

</br>

To do this add a point next to another point and delete the stroke between those two points. 
<img width="449" alt="screen shot 2018-01-02 at 7 02 57 pm" src="https://user-images.githubusercontent.com/30060990/34507991-2e0c62d0-eff0-11e7-8911-f68a6e537d3d.png">

</br>
</br>

Add points using the pen tool (p) and then select the curve using the white arrow tool (a), but when selecting make sure that the points are not highligted blue, and are empty white boxes. 
<img width="454" alt="screen shot 2018-01-02 at 7 03 11 pm" src="https://user-images.githubusercontent.com/30060990/34508031-7aaf94f4-eff0-11e7-8d6e-a6bf53b99be4.png">

</br>
</br>

Then you will need use the pen to bridge the gaps. Once you have done this for both eyes and the mouth you need to switch the stroke of the object to be fill. 

<img width="603" alt="screen shot 2018-01-02 at 7 06 56 pm" src="https://user-images.githubusercontent.com/30060990/34508036-9573251c-eff0-11e7-9b85-a7fe5c7b0a4c.png">

</br>
</br>
</br>
</br>

**4. Save as: SVG file, make sure to convert to convert to outlines**

<img width="536" alt="screen shot 2017-10-22 at 10 05 25 pm" src="https://user-images.githubusercontent.com/30060990/33008411-d7caecaa-cd87-11e7-8a47-d2cdcb1e7bac.png">


<img width="494" alt="screen shot 2017-10-22 at 10 08 48 pm" src="https://user-images.githubusercontent.com/30060990/33008438-e603e43e-cd87-11e7-9ce8-171b57d02eaa.png">

</br>
</br>
</br>
</br>

**5. Now open up Blender, delete the square by hitting x and selecting delete (hit enter). Now select file import, and import your svg. Should look something like this:**


open blender:


<img width="709" alt="screen shot 2017-11-26 at 9 50 42 pm" src="https://user-images.githubusercontent.com/30060990/33252592-f9df1f98-d2f3-11e7-91b9-9a2c7c860d26.png">

</br>
</br>

delete the square by hitting "x" and selecting delete:


<img width="770" alt="screen shot 2017-11-26 at 9 50 51 pm" src="https://user-images.githubusercontent.com/30060990/33252593-fa049c00-d2f3-11e7-92a3-f607ce02eef1.png">

</br>
</br>

Import your svg file by going to file >> import >> Scalable Vector Graphic (.svg):


<img width="614" alt="screen shot 2017-11-26 at 9 53 19 pm" src="https://user-images.githubusercontent.com/30060990/33252650-511eff80-d2f4-11e7-9a22-669995916136.png">

</br>
</br>
</br>
</br>

**6. zoom in to see your svg file... its going to be small... like super small, but its there**

</br>

zoom in! with a mac trac pad its to fingers scale motion/ two fingers expand out, with a three button mouse its just the center scroll wheel or middle button + CTRL:



<img width="520" alt="screen shot 2017-10-31 at 10 27 49 pm" src="https://user-images.githubusercontent.com/30060990/33252766-ea081830-d2f4-11e7-8d56-7520469703ae.png">

</br>
</br>
</br>
</br>

Now rotate the platform so your file is upright. With a mac trac pad use two fingers up and down to rotate the plane around the Y axis, left and right to rotate around the z axis. With a three button mouse its similiar but with the center button:


<img width="748" alt="screen shot 2017-10-31 at 10 35 48 pm" src="https://user-images.githubusercontent.com/30060990/33252767-ea2a5cce-d2f4-11e7-8ceb-709e94a0eb80.png">

</br>
</br>
</br>
</br>

**If the gizmo is way off you can select all the text and curves and then in the tools tab, and click on the Set Origins tab then select Origin to Geometry**

<img width="703" alt="screen shot 2017-12-17 at 10 34 21 pm" src="https://user-images.githubusercontent.com/30060990/34506472-d49e91fe-efe1-11e7-9f8a-15169bdd1240.png">

</br>
</br>
</br>
</br>

**7. Edit time!**


After setting up everything so you can see what you are doing right click all the parts of your svg file. Now you need to convert all the curves to mesh. To do this select the object tab at the bottom of the screen and select Convert To >> Mesh from Curve/Meta/Surf/Text. 

<img width="734" alt="screen shot 2017-12-17 at 10 35 33 pm" src="https://user-images.githubusercontent.com/30060990/34506609-4c94e6e4-efe3-11e7-9692-f1d0544b922c.png">


</br>
</br>

Then switch from object mode to edit mode by hitting tab or clicking on object mode and selecting edit mode.

<img width="382" alt="screen shot 2018-01-02 at 5 38 34 pm" src="https://user-images.githubusercontent.com/30060990/34506678-d063bf04-efe3-11e7-9dc5-e74b691281b2.png">

</br>
</br>
</br>

Now select each object and select the extrude tab, and drag up, creating geometry. From here will show the rest of what to do with filled face. 


<img width="937" alt="screen shot 2017-10-31 at 10 36 03 pm" src="https://user-images.githubusercontent.com/30060990/33252768-ea4fb726-d2f4-11e7-8ebc-7a27148d1fb4.png">

<img width="651" alt="screen shot 2018-01-02 at 7 34 05 pm" src="https://user-images.githubusercontent.com/30060990/34508484-c982d25e-eff4-11e7-9b4f-aa448b7c4d9f.png">

</br>
</br>

You also might want to change the material options so you can better see what you are doing. To do this go on the right pannel and select the material editor and change the color from black to what you want it.

<img width="383" alt="screen shot 2018-01-02 at 7 32 58 pm" src="https://user-images.githubusercontent.com/30060990/34508500-f73f3afc-eff4-11e7-9ad9-e87cc761a7ce.png">

</br>
</br>
 
With the extruded geomtry of the filled face there will be way to many polygons then you need. It will also make modeling the gaps in the face harder. To clean this up you will need to switch into edit mode (Tab) and then hit (x) and select Limited Disolve. This will simplify any geometry that isnt needed. I found that you might need to do this twice to get rid of all the polys in the inner spots that we will be modeling.

<img width="682" alt="screen shot 2018-01-02 at 7 33 37 pm" src="https://user-images.githubusercontent.com/30060990/34508616-582d2d46-eff6-11e7-90e3-f7025c87b1d9.png">

<img width="651" alt="screen shot 2018-01-02 at 7 34 05 pm" src="https://user-images.githubusercontent.com/30060990/34508631-6c06273c-eff6-11e7-8a4c-63dea7983f73.png">

Now that the polys are cleaned up we need to start to model the gaps. Switch your selection tool from points to faces and select the inner faces of the gaps. Hit x to delete those faces. 

<img width="525" alt="screen shot 2018-01-02 at 7 34 29 pm" src="https://user-images.githubusercontent.com/30060990/34508640-7bff3c50-eff6-11e7-9bae-082e140dc3fe.png">

<img width="496" alt="screen shot 2018-01-02 at 7 35 01 pm" src="https://user-images.githubusercontent.com/30060990/34508643-8b9a36f6-eff6-11e7-929a-31ab72d17d33.png">

<img width="261" alt="screen shot 2018-01-02 at 7 35 10 pm" src="https://user-images.githubusercontent.com/30060990/34508647-97390bae-eff6-11e7-932a-9687a623287f.png">

</br>
</br>

Now change your selection tool from faces to edges. Select both edges that you need to join and hit (f) for fill. do this on all four sides, and repeat for the other two sections that need to be modeled. 

<img width="560" alt="screen shot 2018-01-02 at 7 35 18 pm" src="https://user-images.githubusercontent.com/30060990/34508653-a9e9222a-eff6-11e7-9039-e4f7f632de62.png">


<img width="297" alt="screen shot 2018-01-02 at 7 35 35 pm" src="https://user-images.githubusercontent.com/30060990/34508666-bc675976-eff6-11e7-8191-3703fdacf172.png">


</br>
</br>
</br>
</br>

**8. Export the file as an .stl file**





