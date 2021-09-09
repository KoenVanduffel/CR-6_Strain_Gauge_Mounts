# Creality CR-6 SE & MAX extruder and hotend collection mounting directly to the strain gauge
A collection of hot end and extruder combinations for the Creality CR-6 SE and CR-6 MAX is provided in this repo.

```For ease of use the structure has been changed with every possible hotned in a directory followed by directories with the different extruders.```

All of them are mounted directly onto the strain gauge without any connection to the carriage. The aim is to avoid the issue of the extruder pushing down on the strain gauge and causing variation in layer height in the typical gantry mounted direct drive setups. There are a few gantry mounted direct drive setups available that try to avoid this pushing down on the strain gauge issue by installing a washer. This has the added benefit of preventing the strain gauge from oscilating to a large extent. For this reason also in this series the print will extend onto the strain gauge frame and thus greatly limit vibrations.

Next to the above advantages avoiding pushing down on the strain gauge and reducing vibrations we also get optimally short extrusion pathlength.

The disadvantage is that the stock hot end cover does not fit any longer (A series is planned which will work with the stock hot end cover, however the filament path will inevitably be longer).

The daughterboard and 5015 fan mount directory contains the modles needed to mount the daughterboard and a generic 5015 part cooling fan mount. Further work is ongoing to improve the part fan shroud and for some of the extruders there is an improved version in it's rewspective directory.

## Extruders:
For this principle to work we need an extruder that has less than 9 mm space needed behind its filament path or it will not fit between the gantry and the hot end entrance. Two extruders have been selected:
### Orbiter v1.5:
    The orbniter is the highest performing extruder I have tested. With PETG in combination with a high flow Dragon I get up to 600 mm/min (or 25 mm3/s) extrusion speed with just 1.5% deviation versus no resistance at all.
### Mjolnir:
    An extruder using the internals of a BMG extruder. For this any BMG extruder or clone can be used. Also a set of the internals of a BMG extruder is sufficient. The performance is similar to a genuine BMG extruder or its clone variant. I measured an extrusion drop of 5 to 6% with PETG in identical circumstances and filament as the test with the Orbiter. Not as good as the orbiter but still more than sufficient for standard or even slightly higher print speeds.

## Hot ends:
The hot ends chosen all have mount screw holes on the top making them rather easy to mount. Also are they significant all metal upgrades to the stock hot end.
### Dragon
    both high flow and standard flow
### Mosquito
### MicroSwiss for Creality CR-6
### Stock hotend
<br/>
Just a couple of examples:

![CR-6 stoch hotend and Mjolnir extruder](https://user-images.githubusercontent.com/13643644/121425564-d613ab00-c972-11eb-9b16-f10bbce3bcb8.png)
![CR6 Dragon and Orbiter extruder mount](https://user-images.githubusercontent.com/13643644/121425630-ed529880-c972-11eb-9c41-f8ee2b195533.png)
![Mosquito   Orbiter mount 2](https://user-images.githubusercontent.com/13643644/121426032-65b95980-c973-11eb-9b75-b8b25f1e59a7.png)

