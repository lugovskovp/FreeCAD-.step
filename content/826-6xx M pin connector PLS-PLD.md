# PLS/PLD male connector.

FreeCAD file [826-6xx M pin connector PLS-PLD.FCStd](https://github.com/lugovskovp/FreeCAD-.step/blob/master/content/826-6xx%20M%20pin%20connector%20PLS-PLD.FCStd).

### Table of content:
-[Overall info](#data)
-[How to change materials]()
-[How to change pin quontityes and dimensions]()
-[How to export to .STEP]()

## Data.

[Datasheet](http://www.farnell.com/datasheets/32535.pdf).

There are a lot of part numbers for this connector - part of they in spreadsheet in FreeCAD file. It seems like **826-6xx**, where **xx** - is digits.

Part numbers differ by various height of pin, and lengtn lover part (slide pin down). And various materials, but this feature is not realized in file.

Table in "Pin dimensions" spreadsheet has a standart row values for different partnumbers.


## How to change materials
 
- Click on **Export plastic body** in the project tree.
- Press **&lt;control&gt;+&lt;D&gt;**: it will open **"Material property"** dialogue. ![PBS-6](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/22.55.41.png)
- Place to click selected on the screenshot, after that just choice color. All bodies will change their color to selected.
![PBS-6](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/22.55.41.png)
***Note:* For Black color plactik, better choice color dark grey, #555555.*


## How to change pin quontityes and dimensions

![Spreadsheet window](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/16.25.07.png) 
- Double click **Pin dimensions** in the project tree. Spreadsheet window opens (as on screenshot above).
- For change edit **ONLY** yellow-on-blue cells in the &lt;Pin dimensions&gt; spreadsheet.
- A height change full pin height.
- C Shift change lo part of pin.
- X qty - quontity of pins in row to export.
- Y qty - -//- in columns.

All changes in all parts (3D view, draw, ect.) will appear after "F5" button pressing. Or immidiatly after editing.


## How to export to .STEP

- Click on **"Export pin"** in project tree, after with pressed &lt;Control&gt; click on **"Export plastic body"**.
- Then Menu **File -> Export**, in dialog select *"STEP with colors (\*.step, \*.stp)"* in extensions, and save with your name.






