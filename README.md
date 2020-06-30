# Stationeers
Scripts and a helpful diagram for controlling the Advanced Furnace to automate the creation of alloys. This is based on the impressive work found here:
https://github.com/xennon101/Stationeers/tree/master/Automated%20Advanced%20Furnace
This is a much-simplified version, without any of the pre- or post-processing, no sorting of ores or any of the fancy stuff.  It is also in need of improvement, since it pretty much requires a "cold start" every time the system is run, meaning you must shut the processors off and reset the memory all to zero before you select a new alloy on the dial and then turn on the processors.  That's all supposed to get reset in the empty function, but the logic needs some work. I tried to improve on the up-down adjustment time for getting the temp and pressure just right, but with limited success. There's a high and a low setting, with the low being used for ores with tighter tolerances, which helps, but only just. Has been successfully tested with all the alloys as of version 0.2.2445.11152.

Note: the fuel input pressure in my test setup was maintained at roughly 3MPa, not sure if that makes a difference with the internal pumps of the furnace.
