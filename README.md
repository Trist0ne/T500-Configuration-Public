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

Once you've done the above, in your printers web config BACK UP YOUR EXISTING CONFIGURATIONS, then delete them ALL (except KAMP's configuration files) and copy over each of the .cfg files in this repository. Happy printing!
