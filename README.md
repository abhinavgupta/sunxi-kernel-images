sunxi-kernel-images
===================

Custom Kernel Images and Bootloaders for Allwinner A10 boards and Cubieboard specific script files.

NOTE: All bootloder and script files work for Cubieboard only!

The repository contains the 3.0.x kernel version:

 **Kernel features:**
 
* Support for user-controllable LEDs on the board 
* GPIO support for the expansion headers 
* SSH server 
* Fast boot due to minimal services 
* Linaro/Ubuntu Server 13.01 used as base 
* Serial console enabled 
* sunxi linux kernel 3.0.69+ 
* Text-mode framebuffer console 
* Kernel configured with maximal networking options
* Loads of USB device drivers and handy things
* Ethernet full duplex 100Mb/s 
* Solved the speed fluctuations on reboot
* SPI IRQ activated on certain GPIO
* 7 UARTs configured
* USB Cameras working V4L drivers added
	

Note : To support auto login on boot, assuming the OS is a debain OS, perform the following edits 
       in the file /etc/inittabs,
       
       Make the following changes:
		```
      	 #1:2345:respawn:/sbin/getty 38400 tty1
         1:2345:respawn:/bin/login -f YOUR_USER_NAME tty1 </dev/tty1 >/dev/tty1 2>&1
```
This will enable autologin only not startX
  


