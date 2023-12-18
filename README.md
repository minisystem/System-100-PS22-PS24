Roland System 100 Model 101/102 Power Supply Replacement
============

Replaces Roland part # PS22 (110V) or PS24 (220V). I had a Model 102 come in that was missing its power supply so I designed a replacement. It is a straight clone of the schematic from the Model 102 service manual. The BOM from the service manual can be used directly with the exception of the 2SD234 power transistors (replaced with TIP31A equivalent) and the diode bridges (replaced with individual 1N4003). 

![orthoview](/System 100 PS22-PS24.png)

EDA files generated in KiCad 4.0.2. Schematic library here: https://github.com/minisystem/MyKicadLibraries/blob/master/MySynthParts.lib

KiCad GitHub libraries required as well. :/

0.156" MTA header: Molex part # 0009652088
trimmers: Bourns 3362P or equivalent

There are large copper pours top and bottom that were intended to be used as heatsinks, but they are almost certainly inadequate. Use a large external heat sink for each power transistor. The orignal heatsinks will work fine.

Mounting holes match original power supply.

Hardware design by Minisystem: jeff@minisystem.ca 

LICENSE
=======
cc-by-nc-sa
https://creativecommons.org/licenses/by-nc-sa/4.0/
