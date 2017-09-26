# Prusa-I3-Rework

In this repository you will find the source files for the Prusa i3 Rework 3D printer. 

Mounting instruction can be found here: http://reprap.org/wiki/Prusa_i3_Rework_Introduction/fr

The Changes in this derivative include:
 1) Extruder upgrade: Magma Hotend (by Trinity Lab) support. 
 2) New cooling fan duct for Magma Hotend. 
 3) Y Idler with a tensioner system. 
 4) X End Idler with endstop holder. 
 5) Upgrade X End Idler in order to support 624 bearing. 
 6) Y Motor with endstop holder. 
 7) Addition of Z endstop Holder. 

# Upgrades at RED

As GPL v3 require to specifically disclose the sources, all the printed parts in the "AdditionalPartsAndMods" directory are installed to this variant of the printer.

This for now should add the following caracteristics to the machine :
 - part cooling fan for helping printing PLA plastic
 - top-mounted spool holder for easier operation
 
 The machine electronics are (apart for an additional fan) untouched. The Arduino Mega is fitted with a RAMPS 1.4 board, and is running the lattest stable Marlin firmware available today (1.1.5). 
 The current build of marlin on the machine *will not* prevent it to smash the head into the wires for the heated bed, print outside the build volume, or get the head stuck on top of the Z gantry. Otherwise, everything more or less works as intended... ^^'


License 
======

The Prusa i3 Rework is licensed under GPLv3, as was the original Prusa I3 design by Josef Prusa



Attributions
============
 
 - Josef Prusa: Prusa i3 3D printer original author.
 - E-Motion Tech (RepRap France): for the "Rework" 1.0 design
 - 40mm fan duct for eMotion Tech Prusa i3 Rework / Hexagon / 3mm by tototiti is licensed under the Creative Commons - Attribution - Share Alike license
 - Hictop Prusa I3 Spool Holder by jlvnb is licensed under the Creative Commons - Attribution license.
