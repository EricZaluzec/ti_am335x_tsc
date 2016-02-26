# ti_am335x_tsc
ti_am335x_tsc patch to remove jitter.

Patch listed here can be applied to the linux 3.12 kernel. 
Using the ti-tsc drivers for a embedded system touch screen, a drop in 'touch' pressure will cause the touch screen to drastically jitter and mark incorrect coordinates touched.

Patch for v3.8 kernel was found here. Code was taken from here.
https://github.com/RobertCNelson/linux-dev/blob/20c9c32e3443826d79ea01e17cbd2d6fa2c616ae/patches/fixes/0006-ti_am335x_tsc-touchscreen-jitter-fix.patch 
