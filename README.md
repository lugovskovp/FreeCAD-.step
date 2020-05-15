# FreeCAD-.step
[FreeCAD v0.18](https://freecadweb.org/index.php) HQ 3D models, maded by myself. 

Some useful stuff for KiCAD and [DipTrace](https://www.diptrace.com/rus/) schematic and PCB layout CADs users. Extension ".step" is for color 3D models for electronic components.

Use this for easy make .step files with different amount of sub-elements - see HowTo in any file paragfaph.

Table of content:
- [DS1023-female conn (PBS, PBD)](#ds1023-female-connector)


## DS1023-female connector.
Aka PBS (single row), PBD (double) ect. [Datasheet](https://static.chipdip.ru/lib/226/DOC000226931.pdf)

Grey and black plastic variants in file **"/content/DS1023-connector-F PBS-PBD-ect.FCStd"**

https://github.com/lugovskovp/FreeCAD-.step#ds1023-female-connector

 PBD-20 on Picture:

![PBD-20](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/17.05.13(2).png)



### How to make any quontity pins connector DS1023 in .step file. 

![PBD-20](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/17.46.00.png)

For example, if needed **PBS-6** (single row 6 female conns) should be made next steps:
- Download and setup FreeCAD.
- Open in it **DS1023-connector-F PBS-PBD-ect.FCStd** file.
- Choice **Connector array** in project tree (Pos. blue 1 on the picture above).
- In "Data" in field  **Number X** (Pos.2 on the screenshot) set value **6**, in fields **Number Y** and **Number Z** set **1**. (On the picture Number X = 10 and Number Y = 2)
- Make same in **Array Body Grey** or **Array Body Black**. (Just press "space" for on/off visibility for choiced project tree element)
- After that needed component in screen appeared.
- With "Control" key select in project tree elements for export ( "Connector array" and "Array Body Black" if black plastic).
- Menu **File -> Export**, select "STEP with colors (&amp;.step, &amp;.stp)" in extensions, and save with your name.

And how to seems this 3D model in DipTrace Pattern Editor.

![PBS-6](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/17.41.13.png)

