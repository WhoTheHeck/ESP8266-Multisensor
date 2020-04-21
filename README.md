## This project and the repo are heavily WIP. I plan to publish everything as it's in the state to be published.

# ESPHome based multisensor

## Overview

Measuring temperature, humidity, air quality, brightness and movement. ESP board is a NodeMCU v2; Sensors are: SHT31, CCS811, BME280 and AM312. An RGB LED currently indicates if the air quality is good, ok or bad whenever movement is recognized.
Components fits a standard 70x50mm prototype PCB.

Images: https://imgur.com/a/AnUrrSX


## Case

Case is intended to be 3d printed. Sensors sit in indentations in printed top part, which requires lots of support structures for 3D printing. A simplified version that can be printed upside down is possible, but looks less nice. The case measures 76x56x20mm. Everything gets soldered onto the PCB, placed into the case, backside gets screwed onto the wall, frontcase snapfits in place.


## PCB

The PCB was intended to be hand solderable on a 70x50mm prototype-PCB. It's possible but time consuming. If more than one or two boards are required consider sending the kicad_pcb file (ToDo: Gerber-Export) to a manufacturer of your choice. Therefore the traces are held campatible to be used as an exact hand solder guide and are also fabrication ready. That results in some unncessary vias.
Dependent on the position of a component hand soldering starts from one or the other side and sometimes an immediate layer change is required. For a manufactured board these additional vias are no problem.
A jumper can be used for changing one of the external sensors from digital to analog-in.


## External Sensors

There are 3 JST connectors usable for simple external sensors. I use them for super tiny 10x17x8mm wired window/door contacts with hall effect sensors. (ToDo --> add to project)
Soldering the JST connectors is a little finicky, therefore uses a 3d printed placement guide. (ToDo --> add to project) 