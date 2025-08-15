# COLORado PXL Curve 12

## Software Versions

[V1.250508 _ COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/197946a255f3d122da8fa44226ae707d0b259a75/firmware/V1.250508.zip)
- Minor bug fix - tilt improvement

[V1.250410 - CoLorado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/7847228bd18a5303ed7845de051ef45fa05ae2e8/firmware/V1.250410.zip)
- Raised sACN universe count to 32000 from 256

[V1.250120 - COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/4749415c93e3241db780c6a8907642b4ce24ea0e/firmware/V1.250120.zip)
- Fix the bug that LED color will change if DMX is lost

[V1.240806 - COLORado PXL Curve 12](https://github.com/Chauvet-Pro/COLORADOPXLCURVE12/blob/aafbf62867c2809edeca5b79363b229f05194627/firmware/V1.240806.zip)
- Fixed sACN timing and IGMP subscription bugs

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
