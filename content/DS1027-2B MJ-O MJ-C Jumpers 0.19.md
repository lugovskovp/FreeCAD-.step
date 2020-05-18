# DS1027-2B or Jumper.

Uses for handle operate close circle between 2 pins. For change scheme or power on/off to any scheme part.

FreeCAD file: [DS1027-2B MJ-O MJ-C Jumpers 0.19.FCStd](https://github.com/lugovskovp/FreeCAD-.step/blob/master/content/DS1027-2B%20MJ-O%20MJ-C%20Jumpers%200.19.FCStd).

***Attention! File maide in FreeCAD beta0.19. It can be opened and operated in stable 0.18 (I check it), bup Draw page not will work propetly. 3D .step files are prodused correctly anyway.***


## Example:

Next .step 3D jumpers models are avalible alredy from [content page](https://github.com/lugovskovp/FreeCAD-.step/tree/master/content).

- DS1027-2 MJC-60 black 2pins.step
- DS1027-2 MJC-60 black 3pins.step
- DS1027-2 MJC-60 red 3pins.step
- DS1027-2 MJC-60 white 2pins.step
- DS1027-2 MJC-60 white 3pins.step
- DS1027-2 MJO-60 black 2pins.step
- DS1027-2 MJO-60 black 3pins.step
- DS1027-2 MJO-60 red 2pins.step
- DS1027-2 MJO-60 red 3pins.step

Or you can produse own:
- set pin height (`"A" - Height pin:`), down shift lower part pin (`"C" - Shift pin down:`), quantity pins (`X pin qty`) - 2 or 3, quantity rows pin (`Y pin qty`), jumper profile height (`JmprProfileHeight`), close or open type jumper: 1 or 0 (`JmprCloseTypeIfEq0`) in the yellow-on-blue cells on `Set Dimensions` spreadsheet.
![how to change Set Dimension pad](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/15.20.15.png)
- [change body pin and jumper plastic color](#how-to-change-body-color).
- [export](#how-to-export-to-step) .step model file.

And how to seems this resulted .step 3D model imported to DipTrace Pattern Editor.

![DipTrace pattern editor](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/10.42.30.png)

[Up](#example)



## Data.

[Datasheet DS1027-XXXX](http://files.rct.ru/pdf/connectors/ds1027-2.pdf).

Product code designation ISO **`DS1027-X Y Z F H`**, where:<br/>
**`X`** - No. of contacts: 
- 2 : 2 contacts<br/>
**`Y`** - Housing type:
- **A** : open
- **B** : close
- **L** : long<br/>
**`Z`** - Housing color:
- **B** : black
- **U** : blue
- **Y** : yellow
- **W** : white
- **E** : green
- **R** : red<br/>
**`F`** - Contact plating:<br/>
- **F1**: full gold flash
- **N**: nickel
- **2**: gold+nickel<br/>
**`H`** - Profile height (Dim "A"):<br/>
- **0**: 6.0 mm
- **1**: 6.47 mm

(f.e.: `DS1027-2BB20-N-016` - 2 contacts, closed type, black, gold_nickel plated, height 6 mm)


[Another datasheet MJC, MJO, MJH](http://files.rct.ru/pdf/connectors/he.pdf)

**`MJ-X H Y Z`**:<br/>
**`X`** - Housing type:
- **O** : open
- **C** : close
- **H** : with handler<br/>
**`H`** - Profile height (Dim "A"):<br/>
- **45**: 4.5 mm
- **60**: 6.0 mm
- **65**: 6.5 mm
- **80**: 8.0 mm
- **137**: 13.7 mm<br/>
**`Y`** - Contact plating:<br/>
- **G**: full gold flash
- **S**: partitialy gold
- **T**: tinning<br/>
**`Z`** - Housing color:
- **1** : black
- **2** : red
- **3** : yellow
- **4** : green
- **5** : blue
- **6** : grey
- **7** : white<br/>

(f.e.: `MJ-0-60 G 2` means red open type jumper height 6 mm full gold plated contacts)

![Drawing](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/10.42.30.png)

[Up](#example)



## How to change body color

- Select (click) `Export plastic body` (for pin body color) or `Export plastic jumper body` (for jumper color) in the project tree.
- Press `<Ctrl>+<D>`, opened **"Material property"** dialogue.<br/>![Material property](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/10.40.11.png)
- Place for click selected on the screenshot above, after that just choice color. All bodies will change their color to selected.

***Note: For black color plactic, better choice color dark grey, not black, #555555.***

[Up](#example)



## How to export to .STEP

- Select (click with &lt;Ctrl&gt; in project tree parts for export (there are 4, names starting from "Export ...", see screenshot)
- Then Menu **File -> Export** (or `<Ctrl>+<E>`), in appeared dialog select ***"STEP with colors (\*.step, \*.stp)"*** in extensions, and save with your name.
![Material property](https://github.com/lugovskovp/FreeCAD-.step/blob/master/pix/10.49.33.png )
[Up](#example)
