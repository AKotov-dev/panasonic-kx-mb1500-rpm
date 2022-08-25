# panasonic-kx-mb1500-rpm
Drivers for Panasonic-KX-MB1500

The packages contain drivers for a multifunctional device (printer and scanner) for Mageia Linux (8/9). During installation, a rule for the scanner is automatically added to the file `/usr/lib/udev/rules.d/60-libsane.rules`, which is not present in the original Mageia. After installation, you need to add the user to the necessary groups and restart the computer:
```
usermod -aG lp,usb,scanner $LOGNAME; reboot
```
![](https://github.com/AKotov-dev/panasonic-kx-mb1500-rpm/blob/main/ScreenShot.jpg)

Drivers on the vendor's website: https://panasonic.net/cns/pcc/support/fax/common/table/linuxdriver.html  

**Similar programs:** [SrEditor - automatic rule editor for scanners](https://github.com/AKotov-dev/sreditor)
