# T500-Configuration-Public
A Public repository with my optimized Klipper configurations for the T500 3D printer

# TO USE THESE FILES
These configurations assume that you have:
> Installed and configured KAMP https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging

> Edited your Slicer's Start/End Code like this:
* PRINT_START EXTRUDER=[nozzle_temperature_initial_layer] BED=[bed_temperature_initial_layer_single] CHAMBER=[chamber_temperature]
* PRINT_END
> Additionally, if you're using Orca slicer, for best results in the 'others' tab you'll want to enable
* Label Objects
* Exclude Objects

Once you've done the above, in your printers web config BACK UP YOUR EXISTING CONFIGURATIONS, then delete them ALL except klipperscreen.conf and KAMP's configuration files, then copy over each of the .cfg files in this repository. YOU SHOULD RETUNE INPUT SHAPER, PRESSURE ADVANCE, AND Z-OFFSET BEFORE PRINTING! Happy printing!

If you run into an error with the screen constantly rebooting, re-apply the firmware update from comgrow (even if you've done it before). The makerbase firmware can be touchy for some reason, havent quite worked out why. After re-updating the issue vanished, including between reboots. Thankfully it wont overwrite the new configurations. 

Firmware update is located here: https://drive.google.com/drive/folders/1Yt9YJvf4PYsZnZN0SJ2QfM854uHyY-OW?fbclid=IwAR0X5d5XWNX3VRbQPU41ONEbuIXbYEswDVW4dIzs3GIlIn9iSdKypPv_4bw
