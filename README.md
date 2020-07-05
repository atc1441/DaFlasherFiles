# DaFlasherFiles

These are the files needed for the DaFlasher app, Playstore: 
https://play.google.com/store/apps/details?id=com.atcnetz.paatc.patc

After flashing you will end with an Nordic DFU Bootloader where you can flash your own Firmware to The Watch.
Like via Arduino etc. 


### You can support my work via paypal: https://paypal.me/hoverboard1 this keeps projects like this comming.

## And all without opening the watch, all over the Air.
I recomment to have one opened watch to develope new Firmware and when it is tested upload it to the closed Watch

Here you have the 3 Files you can see me using in this video:

(click on the image)

https://www.youtube.com/watch?v=gUVEz-pxhgg

[![YoutubeVideo](https://img.youtube.com/vi/gUVEz-pxhgg/0.jpg)](https://www.youtube.com/watch?v=gUVEz-pxhgg)


# You can Upate the Bootloader and SD to any Other version as long as the New Bootloader is At address 0x78000, 
### this can also be changed but needs an additional bootloader and flash step.


## Files:

### DaFitBootloader23Hacked.bin
This gets you started, flash this file first when you are on the Stock DaFit Firmware, 
this will install an Custom Bootloader i made using the Installed SoftDevice5.0.1
Here is a list of all the Compatible watches that can be flashed with this "Hack"
https://gist.github.com/atc1441/d0a3c1f5ee69ab901bccba4eb47a6e4e

### FitBootloaderDFU2.0.1.zip
This installs the SoftDevice version 2.0.1 and an Bootloader for SD2.0.1 useable when on SD5.0.1
#### To create your own DFU update files for SD2.0.1 you need to use nrfutilV0.5.3:
https://github.com/NordicSemiconductor/pc-nrfutil/releases/tag/v0.5.3

### ATCdfuFromSD2toSD5.zip
If you want to go Back to SD5.0.0 Bootloader you can do so with this file

### ATCwatchP8.ino.zip // OLD Name: P8TestMenuDisplay.ino.zip
This is just a more advanced demo Made for the P8 Smartwatch to show the hardware is working,
it will also run on other Watches but maybe they have different pinout for aditional Hardware like the Push Button.

### ATCwatchPineTime.ino.zip // OLD Name: PineTimeTestMenuDisplay.ino.zip
This is just a more advanced demo Made for the PineTime Smartwatch to show the hardware is working,
it will also run on other Watches but maybe they have different pinout for aditional Hardware like the Push Button.


## Compatible Software:

### Arduino: https://youtu.be/3gjmEdEDJ5A 
In the Portable version there is the P8 Board available.
Portable version: http://atcnetz.de/downloads/D6Arduino.rar 
Install Version: https://github.com/atc1441/D6-arduino-nRF5
### Espruino: https://github.com/fanoush/ds-d6
### Pinetime: https://wiki.pine64.org/index.php/PineTime
