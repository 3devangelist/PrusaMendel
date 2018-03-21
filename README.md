# maZEmendel

<p align="center">
  <img src="Maise_mendal/imagens/Foto_1_Maise_mendel.JPG" width: 20%;>
</p>

I have made these because i can, and i love history! and is a historic printer!

My motivation is make a printer with a printer, i have a [*Beethefirst+*](https://beeverycreative.com/beethefirstplus/), that is **portable** and **user friendly** and i wanted to prove that with a Little machine i could create a bigger one! and more maker oriented.
That is the base of REPRAP movement!

You will have all the gcode already generated to print one just like me in you beethefirst! and if you do **Show me!**

## First technical notes about these printer

These printer is not easy to assemble, have a lot of bolts and hardware, but if well assembled it can be reliable.
You have a calibration paragraph, as a guide for you to calibrate all the perpendicularity of your XYZ axis.
I have printed the majority parts in PETG because my BTF+ (beeverycreatrive printer) prints it very well and is more flexible than PLA to absorb some vibrations and have better layer adhesion.

**Side note** if you use PETG try to use one that is transparent the color opaque ones normally as worse strength proprieties.


## Modeling
I have used **BLENDER**, because i am a blender hardcore-user, because i can, and because is really good to edit meshes.

To cut pieces,i have used rhino, because is the only paid CAD program i have, but you can use the dxf or you can ask to me and i can convert to your needs, and to bee fair the only part you have to cut with precision is the Y wood base, later i will give the fabrication manual.

The file as called *"maise.blend"*, with that file i have rendered all images for the manual, and modeled all parts that i need to create or change for these build. If you need to edit you can and you should is because of that i share the source code. All the parts have the same name of the boom file, and are distributed by layers, i know that could be better organized, but better done than perfect.
You should use some add-on's like "3d print toolbox", "Layer management", "cycle engine", when you use models from blender you can try to clean all the mesh to be printable, but that is normally for power users, and when you use Boolean tools is impossible to make that without lose the modifiers stack, and we have to source the more editable parts we can, for others could change. The pipe-line i use is export meshes to stl with "3d print toolbox" add on, then use a tool that came with windows10 called "3d Builder" that is great to heal meshes.

### Heal meshes on 3d Builder

![image 3d builder - heal meshes](Maise_mendal/imagens/repair_meshes_3d_builder.png)

- 1 Import as mm;
- 2 When you see red rectangle in the base of the model, means that the model has errors;
- 3 Import the model;
- 4 When you import the model, a rectangle shows up in the right down of your screen, click on it to repair;
- 5 Save your file em STL;

## Changes

- New X axes;
- remodeled Y;
- Some updates on Z;
- Bowden for extruder;
- E3d v6 hotend;
- Igus sliders for X and Y;
- board MKSgen 1.4;
- Drivers X, Y, E, Trynamic 2100, Z LV8729;
- Added LEDs to the system, you can add RGB "if you do show it!"

Working..


## BOM Build of Materials

[Spreedsheet](https://docs.google.com/spreadsheets/d/16tOSJMvPqgqwrDMo-RX5avmmjWwADpJSkYPEsrkDC4U/edit?usp=sharing)
(only parts to be printed the parts to buy needs to be updated)

## Extruder

### Saintflint


<p align="center">
  <img src="https://cdn.thingiverse.com/renders/45/15/26/87/0c/IMG_20150810_120851_preview_featured.jpg">
</p>

These is the best bowden printed extruder i have used! was developed by a great friend [Michael Memeteau](https://incompreendido/in/mmemetea/), creative and resourceful engineer.
These extruder has a concept of double the area of adherence of the tooth to the filament.
I have edited the model to fit a MK10 type of gear if you want other please edit it yourself, you have a editable [onshape instance](https://cad.onshape.com/documents/5c209690b10748338481382a/w/6d6638f54420d7c76fe7949d/e/2d47f4694787414fab59244e)

In the [source](https://www.thingiverse.com/thing:979113) you have all information you need to assemble the extruder!

**Recommendation** - print all the parts in PETg and 90% infill, takes longer use more plastic but is safer that you will not end with a broken extruder.

## Assembly the frame


### Filament Sensor

To implement!


### Hotend
I have used a Bowden setup with E3d v6 Chinese clone, before all the test I am thinking to upgrade it for a original one!

### Wiring

#### MKS GEN 1.4
I have chose these because is good relation price what you get, in the boom you have links to buy the board, with these boar like i want a silent machine i chose TMC2100 stepper drivers X Y E they are not cheep but they worth it!
You should be able to assemble with these [instructions](http://reprap.org/wiki/MKS_GEN) from reprap community, if you use LEDs you should connect to the 12V output is the same place you connect the hotend fan.

### ATX Power supply 
To use a PC ATX power supply, you have to convert it, go to these [instructables](http://www.instructables.com/id/A-Makers-Guide-to-ATX-Power-Supplies/) you only need the 12V track, unless you will config a raspberrypi with octaprint, if you will, use the 5x track to, power up the raspberrypi.

# Assembly
## Structure
![montage](Maise_mendal/imagens/struture_montage.svg)

1. Pick 6X380 M8 rods, and 2X *"001 bar-clamp-tall"*, and M8 Bolts and Washers, and displace them like in the picture.
2. 

