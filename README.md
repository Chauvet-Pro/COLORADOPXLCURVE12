# COLORado PXL Curve 12

## Software Versions

[V1.240509 - COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/deec72379ace36f4a92b55ca3a0df9a9cab87b6c/firmware/V1.240509.zip)
- Added better capability for calibration and help with LED color uniformity

[V1.240411 - COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/0c1a982447efde5e25913eddb22d2e283ce5b79f/firmware/V1.240411.zip)
- Fixed color snap issue and corrected wrong Web server channels
     * Web server was showing wrong channel counts as: **3, 5, 9, 12, 17, 19,** and **37**.  The new  software corrected this issue, and it now shows the correct channel counts as: **Basic, Basic2, Standard, Advanced, Advanced2, Tour,** and **Full PXL**.

[V1.240222 – COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/1a3d1764795c843def4e53d80e5e310c747bd709/firmware/V1.240222.zip)
-	Fixed IGMP subscription issue

[V1.240131 – COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/1a3d1764795c843def4e53d80e5e310c747bd709/firmware/V1.240131.zip)
-	Added new zoom mode

[V1.231222 – COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/1a3d1764795c843def4e53d80e5e310c747bd709/firmware/V1.231222.zip)
-	Improved dimming and added tilt adjustment

[V1.231019 – COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/1a3d1764795c843def4e53d80e5e310c747bd709/firmware/V1.231019.zip)
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
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
