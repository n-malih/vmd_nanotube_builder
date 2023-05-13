# vmd_nanotube_builder
This is an edited version of VMD Nanotube Builder to have a simulation box for sheets.
-------------
By default, the VMD Nanotube Builder extension won't create a simulation box when generating sheets. With this edited version of Nanotube Builder, you will have a simulation box after generating the sheet.
-------------
### Usage:
- Replace graphene.tcl with the original file in:
```
C:\Program Files (x86)\University of Illinois\VMD\plugins\noarch\tcl\nanotube1.5
```
- Run VMD and create a sheet
- To see the simulation box write this on VMD TKCosole:
```
pbc box
```
- To get box length write this:
```
molinfo top get {a b c}
```
## Contact:
If you need help or have any quastion feel free to ask.
Nader Malih - Email: malih.nader@gmail.com
