# PLS/PLD male connector.

FreeCAD file: [826-6xx M pin connector PLS-PLD.FCStd](https://github.com/lugovskovp/FreeCAD-.step/blob/master/content/826-6xx%20M%20pin%20connector%20PLS-PLD.FCStd).



### Table of content:

- [Overall info](#data)
- [How to change materials](#how-to-change-materials)
- [How to change pin quontityes and dimensions](#how-to-change-pin-quantityes-and-dimensions)  
- [How to export to .STEP](#how-to-export-to-step)



## Data.

[Datasheet 826-6xx](http://www.farnell.com/datasheets/32535.pdf).

There are a lot of part numbers for this connector - part of they in spreadsheet in FreeCAD file. It seems like **826-6xx**, where **xx** - is digits.

Part numbers differ by various height of pin, and lengtn lover part (slide pin down). And various materials, but this feature is not realized in file.
![Drawing](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/17.02.19.png)
Table in "Pin dimensions" spreadsheet has a standart row values for different partnumbers.

[Up](#table-of-content)



## How to change materials

 ![Export plastic body](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/15.53.41.png)
- Select (click) **Export plastic body** in the project tree.
- Press **&lt;Ctrl&gt;+&lt;D&gt;**: it will open **"Material property"** dialogue. ![Material property](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/22.55.08.png)
- Place to click selected on the screenshot above, after that just choice color. All bodies will change their color to selected.

***Note: For black color plactic, better choice color dark grey, not black, #555555.***

[Up](#table-of-content)



## How to change pin quantityes and dimensions

- Double click **Pin dimensions** in the project tree. Spreadsheet window opens (as on screenshot below).![Spreadsheet window](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/16.25.07.png) 
- For change something edit **ONLY** yellow-on-blue cells in the **&lt;Pin dimensions&gt;** spreadsheet.
- ***`"A" height`*** - change full pins height.
- ***`"C" Shift`*** - change lower part of pins.
- ***`X qty`*** - quantity of pins in row to export.
- ***`Y qty`*** - -//- in columns.

All changes in all parts (3D view, draw, ect.) will appear after "**F5**" button pressing. Or immidiatly after editing.

[Up](#table-of-content)



## How to export to .STEP

- Select (click) the **"Export pin"** in project tree
- After with pressed &lt;Cntrl&gt; click on **"Export plastic body"**.
- Then Menu **File -> Export**, in appeared dialog select ***"STEP with colors (\*.step, \*.stp)"*** in extensions, and save with your name.

[Up](#table-of-content)




