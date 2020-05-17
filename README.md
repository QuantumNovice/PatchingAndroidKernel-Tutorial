# Custom Patching Linux Kernel

# Installing ROM on Mediatek 6753

# Aliases:
Gionee S6s <br>
Q Mobile Z12 Pro <br>
MT6753 <br>

# Installing Drivers:
Install `Drivers` folder navigate to each driver folder and install it.
These drivers are:
* ADB Driver:
* VCOM Driver:
* CDC Driver:


# Flashing
<h3 style="color:red">
Warning: Battery Percentage should be above 80 when flashing preloader.
</h3>
<br>

* Download the latest version of [SP Flash Tool](https://spflashtool.com/).
* Open the executable(`flashtool.exe`) inside SP Flash Tool folder.
* Navigate to `Download` tab.
* Load scatter file from `Firmware` folder.
* Make sure the drop down is set to `Download Only` and uncheck the `PRELOADER` field.
* Connect the compatible android device via USB .
* Wait till the program recognizes the chip.
* Press `Download Button` under `Download` tab.



# Platform Tools (Optional):
* Download Platform Tools from
[Android SDK Platform Tools](https://developer.android.com/studio/releases/platform-tools).
* `adb usb`
* `adb reboot bootloader`
* `fastboot boot /path/to/recovery.img`

Once you've done the above steps you might have some idea of how android booting works.
