# Maverick Storm 2 BeamWash

## Software Versions

[V1.240523 - Maverick Storm 2 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM2BEAMWASH/blob/0171079d335fc5c4d05f2bc015bf7bf65cb0c0ff/Firmware/V1.240523.zip)
* Updated DMX slot information in RDM under Full PXL mode
* Fixed appearance of strobe function in DMX values 25-36
* Fixed timing issue in strobe function in DMX values 170-184
* Fixed bug in Dimmer Smooth to allow center LED to sync with ring LED
* Fixed bug in TV Reset mode to allow reset to be quieter in function
* ***NOTE: The software filename is V1.230523 but will reflect the correct version number V1.240523 once installed in the product***

[V1.230822 – Maverick Storm 2 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM2BEAMWASH/blob/eb8472c0aca01b08e16b2c800e406af9596072bd/Firmware/V1.230822.zip)
-	Added IC chip compatibility
  
[V1.230516 – Maverick Storm 2 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM2BEAMWASH/blob/eb8472c0aca01b08e16b2c800e406af9596072bd/Firmware/V1.230516.zip)
-	Fixed timing errors and reduced reset noise
  
[V1.221102 – Maverick Storm 2 BeamWash](https://github.com/Chauvet-Pro/MAVERICKSTORM2BEAMWASH/blob/eb8472c0aca01b08e16b2c800e406af9596072bd/Firmware/V1.221102.zip)
-	Released software version

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
