## This project and the repo are heavily WIP. I plan to publish everything as it's in the state to be published.

# ESPHome based multisensor

Measuring temperature, humidity, air quality, brightness and movement. ESP board is a NodeMCU v2; Sensors are: SHT31, CCS811, BME280 and AM312. An RGB LED currently indicates if the air quality is good, ok or bad whenever movement is recognized.

For the case I started of modeling every sensorboard, placing them onto a PCB. Turns out everything fits a standard prototype PCB just fine. Sensors sit in indentations in top part, which requires lots of support structures for 3D printing. A simplified version that can be printed upside down is possible, but looks less nice. The case measures 76x56x20mm. Everything gets soldered onto the PCB, placed into the case, backside gets screwed onto the wall, frontcase snapfits in place. Soldering the JST connectors will be the only finicky part. The 3 JST connectors are used for super tiny 10x17x8mm wired window/door contacts with hall effect sensors.

Images: https://imgur.com/a/AnUrrSX
