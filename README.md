# buildPlans
build plans for sniffy and associated brackets. 

We're a little thin on documentation here - please help us out and submit a pull request!

The works contained in this repositiory are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license (CC BY-NC-SA 4.0). This means you are free to share and share-alike for non-commercial use.

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


# Sniffy v1 Build Kit Assmebly

The sniffy kit containes the following: -

* 4x M4 x 12 barral bolts (#2)
* 4x M2 x 10 cheese head screws (#5)
* 4x self tapping screws (#3)
* 9x Nylon M3 x 10 cheese head screws 4x spacers (#1 & #6)
* 1x Back plate (drilled) (#7)
* 1x Enclosure (drilled) (not on photo)
* 1x 3D printed sensor cowling (#11)
* 1x Bosche BME280 environment sensor (temp, pressure, humdity) (#9)
* 1x Plantower PMS5003 Particulate Matter (PM) sensor (#10)
* 1x pi header to sensor cable

In addtion to the kit you will need:
* 1x Raspberry Pi Zero W
* Micro SD card (minimum 8 GB)
* Raspberry Pi Header (solderless headers are amvailable if you don't feel confident soldering)

These parts are shown in the photos below:
![Photo](images/10.jpg?raw=true "Parts")

* Insert the threads into the 3D printed sensor cowling 
![Photo](images/7.jpg?raw=true "sensorCowling)

* Use the M2 screws to mount the Pm sensor to the mounting place

* Use the nylon spacers and screws to mount the Raspbery Pi Zero above the PM sensor. You may need to widen the holes to 3mm but the nylon screws generally fit.

* Mount the assembly into the enclosure, fix the mounting plate using the self tapping screws

* Mount the BME280 sensor above the PM sensor using the remaining nylon screw into the threaded hole.
![Photo](images/12.jpg?raw=true "box")

* wire the sensor to the pi taking note of white marks denoting pin 1

![Photo](images/1.jpg?raw=true "BME280")
![Photo](images/5.jpg?raw=true "RPi Header Pin 1")

* Fit an SD card of at least 8GB and head over to /solentairwatcg/sniffy and follow the instructions to set up the raspberry pi and begin streaming data.

