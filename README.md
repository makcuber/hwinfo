# hwinfo
Description: Bash Script for listing a bunch of common hardware info from a Linux system
more detailed than base neofetch, useful for quick checks on machines being repaired

There is a built-in dependancy check before running the main part of the script

Dependancies:
 - xargs
 - dmidecode
 - lshw
 - lscpu

Note regarding Serial #'s: On Desktop systems if the Motherboard was bought directly 
from the manufacturer it will often not have a serial number. The listed value will be "serial number to be filled by o.e.m" instead.

Example Output:
<pre>
HW Info
===================================================================================

Serial #: 		    DFSDF45S5D45

===MOBO===
Mobo Model: 		  Pear-DS65F4S65SD5F46
Mobo Version: 		PearBookLite7,2

===CPU===
CPU Model: 		   Pear Inc.
CPU Model: 		   Intel(R) Core(TM) i2-7411U CPU @ 0.80GHz
CPU Cores: 		   1
L3 Cache: 		    3 MiB
CPU Min (MHz): 	800
CPU Max (MHz): 	2800

===GPU===
GPU Vendor: 		  Intel Corporation
GPU Model: 		   2rd Gen Core processor Graphics Controller
Min vRAM (MB): 	64
</pre>
