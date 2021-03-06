- [Creality CR-6 SE & MAX extruder and hotend collection mounting directly to the strain gauge](#creality-cr-6-se---max-extruder-and-hotend-collection-mounting-directly-to-the-strain-gauge)
  * [Daughterboard](#daughterboard)
  * [fan mount](#fan-mount)
  * [Extruders:](#extruders-)
    + [Orbiter **V1.5**:](#orbiter---v15---)
    + [Mjolnir:](#mjolnir-)
    + [Bondtech LGX Lite:](#bondtech-lgx-lite-)
  * [Hot ends:](#hot-ends-)
    + [Dragon](#dragon)
    + [Mosquito](#mosquito)
    + [MicroSwiss for Creality CR-6](#microswiss-for-creality-cr-6)
    + [Stock hotend](#stock-hotend)

# Creality CR-6 SE & MAX extruder and hotend collection mounting directly to the strain gauge

## **I am in the process of moving this repo over to the PrusaPrinters.org repository of prints, for the latest updates please check the https://www.prusaprinters.org/social/211289-k2van/collections/114416 collection page. I link the relevant page in every subdirectory.**

A collection of hot end and extruder combinations for the Creality CR-6 SE and CR-6 MAX is provided in this repo.

```For ease of use the structure has been changed with every possible hotend in a directory followed by directories with the different extruders.```

All extruder / hot-end combinations are mounted directly onto the strain gauge without any connection to the carriage. The aim is to avoid the issue of the extruder pushing down on the strain gauge and causing variation in layer height in the typical gantry mounted direct drive setups. An added benefit is that the mount will prevent the strain gauge from vibrating as it blocks downward movement. Only the upward movement to enable bed measurement is allowed. Mounting the extruder this way ensures the shortest possible filament path which is exactly the aim of a direct drive setup. Only the Hemera and alike designs achieve even shorter filament paths.

There are a few gantry mounted direct drive setups available that try to avoid this pushing down on the strain gauge issue by installing a washer.

The disadvantage is that the stock hot end cover does not fit any longer (A series is planned which will work with the stock hot end cover, however the filament path will inevitably be slightly longer).

## Daughterboard
The daughterboard needs to be mounted on its own mount as the stock mount interferes with the extruder. A separate mount can be found in the daughterboard directory. 3 versions are available: one to mount the PCB directly to the mount (on standoffs) and two others that allow/require you to use the plastic OEM mounting plate/cover to mount the board to the plate.  The first mount places the board too low for the LED to safely clear your models and bed clips.
NOTE: Whichever of these daughterboard mounts you use, the LED will no longer be positioned to shine below the nozzle unless you design and make your own modifications to address that.

## fan mount
A series of fan mounts using generic 5015 or 5020 blower fan mounts optimized for each hotend is provided. With thanks to Alex for the idea of the "ears" the fan shroud design has been greatly improved and cooling efficiency of this 5015 fan is very high (enabling lower speed / quieter operation).
The fan mount has to be printed in PETG, ASA, ABS PCTG or another higher temperature filament. PLA will simply melt as its too close to the hotend.

## Extruders:
For this principle to work we need an extruder that has less than 9 mm space needed behind its filament path or it will not fit between the gantry and the hot end entrance. Two extruders have been selected:
### Orbiter **V1.5**:
> The Orbiter is the highest performing extruder I have tested. With PETG in combination with a high flow Dragon I get up to 600 mm3/min (or 25 mm3/s) extrusion speed with just 1.5% deviation versus no resistance at all.
>The Orbiter has a high gear ratio which is beneficial for extrusion as it will improve acccuracy significantly. It has been found that this can cause noise when using the filament unload function of the Community Firmware. The speed is set so high that the extruder will run at nearly 800 rpm. This will not damage the motor but some people have reported that it makes a lot of noise (probably skipping of the motor).

### Orbiter **V2.0**
>The Orbiter V2.0 is currently NOT supported! It might be an upgraded extruder versus the V1.5 however it does not fit on the strain gauge. The drive gears have been turned around which makes it collide with the back carriage plate.

### Mjolnir:
> An extruder using the internals of a BMG extruder. For this any BMG extruder or clone can be used. Also a set of the internals of a BMG extruder is sufficient. The performance is similar to a genuine BMG extruder or its clone variant. I measured an extrusion drop of 5 to 6% with PETG in identical circumstances and filament as the test with the Orbiter. Not as good as the orbiter but still more than sufficient for standard or even slightly higher print speeds.

### Bondtech LGX Lite:
> The all new Bondtech LGX Lite extruder (NOT THE REGULAR LGX, that one too bulky to fit the CR-6). A mount is modeled but untested for now as I do not own an LGX lite. This could well become the highest performance option as its lighter and more compact than the Orbiter 1.5 and  can be mounted closer to the strain gauge bringing the center of mass of the whole hotend assembly closer to the strain gauge thus avoiding vibration of the strain gauge upon higher accelerations.
> Extrusion performance is obviously untested by me but should be equal to or better than the Orbiter.



## Hot ends:
The hot ends chosen all have mount screw holes on the top making them rather easy to mount. Also are they significant all metal upgrades to the stock hot end.
The extruder - hotend mount blocks can be printed in any filament however PETG, PCTG, ASA or ABS are preferred over PLA.

### Dragon
> both high flow and standard flow

### Mosquito
### MicroSwiss for Creality CR-6
### Stock hotend
<br/>
Just a couple of examples:

<img src="images/README/CR-6 Dragon & Orbiter mount with stator fan.png" alt="CR-6 Dragon & Orbiter mount with stator fan" width="60%" />

![CR-6 stoch hotend and Mjolnir extruder](https://user-images.githubusercontent.com/13643644/121425564-d613ab00-c972-11eb-9b16-f10bbce3bcb8.png)

![Mosquito   Orbiter mount 2](https://user-images.githubusercontent.com/13643644/121426032-65b95980-c973-11eb-9b75-b8b25f1e59a7.png)



