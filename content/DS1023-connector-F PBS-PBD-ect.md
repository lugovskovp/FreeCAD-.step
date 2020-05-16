# DS1023-female connector.

Aka PBS (single row), PBD (double row), 254G3-2FVXX (double row)

FreeCAD file [DS1023-connector-F PBS-PBD-ect.FCStd](https://github.com/lugovskovp/FreeCAD-.step/blob/master/content/DS1023-connector-F%20PBS-PBD-ect.FCStd).



## Example:

Imagine, needed black **PBS-6** (single row 6 female conns), should be got by made next steps: 
- [set](#how-to-change-contacts-quontitie-and-dimensions) `Qty contacts X` and `Qty contacts X` as **6**  and **1** in the yellow-on-blue cells.
- [change body color](#how-to-change-body-color) to Dark Grey(#555555).
- [export](#how-to-export-to-step) .step model file.

And how to seems .step 3D model iported in DipTrace Pattern Editor.
![DipTrace pattern editor](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/17.41.13.png)



## Data.

[Datasheet DS1023-XXXX](https://static.chipdip.ru/lib/226/DOC000226931.pdf).

[Another datasheet 254G3-xFVXX](http://files.rct.ru/pdf/connectors/254g3-2fvxx.pdf)

Designation **`DS1023-X Y Z H`** , where:<br/>
**`X`** - No. of contacts: 
- 1\*1 - 1\*40
- 2\*2 - 2\*40
- 3\*3 - 3\*40

**`Y`** - Mounting type: S: stright type<br/>
**`Z`** - Contact plating:<br/>
- **0**: seletive gold flash
- **F1**: full gold flash<br/>

**`H`** - Profile height (Dim "A"):<br/>
- **1**: 8.5mm
- **2**: 5mm

![Drawing](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/20.12.31.png)

[Up](#example)



## How to change body color

- Select (click) **`Export plastic body`** in the project tree.
- Press **'<Ctrl>+<D>`**, opened **"Material property"** dialogue.<br/>![Material property](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/22.55.08.png)
- Place for click selected on the screenshot above, after that just choice color. All bodies will change their color to selected.

***Note: For black color plactic, better choice color dark grey, not black, #555555.***

[Up](#example)



## How to change pin quantityes and dimensions

![Dimentions](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/18.47.51.png)

- Double click **`Dimensions`** in the project tree (see pix). Spreadsheet window opens.
- For change something edit **ONLY** yellow-on-blue cells in the **`Pin dimensions`** spreadsheet.
- ***`A-Height`*** - plastic body height.
- ***`Qty contacts X`*** - quantity of contact in row to export.
- ***`Qty contacts Y`*** - same in columns.

All changes in all parts (3D view, draw, ect.) will appear after "**F5**" button pressing. Or immidiatly after editing.

[Up](#example)



## How to export to .STEP

- Select (click) the **`"Export metall connectors"`** in project tree
- After with pressed &lt;Cntrl&gt; click on **`"Export plastic body"`**.
- Then Menu **File -> Export**, in appeared dialog select ***"STEP with colors (\*.step, \*.stp)"*** in extensions, and save with your name.

[Up](#example)











