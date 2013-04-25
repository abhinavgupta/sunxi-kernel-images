sunxi-kernel-images
===================

Custom Kernel Images and Bootloaders for Allwinner A10 boards and Cubieboard specific script files.

The repository contains two kernel versions:

1. 3.4.47 - Consists of the following features
Features: * Support for user-controllable LEDs on the board 
          * GPIO support for the expansion headers 
          * ssh server 
          * Fast boot due to minimal services 
          * Linaro/Ubuntu Server 13.01 used as base 
          * Serial console enabled 
          * sunxi linux kernel 3.4.x 
          * Text-mode framebuffer console 
          * Kernel configured with maximal networking options
          * Loads of USB device drivers and handy things


Issues    * Ethernet MAC not initializing
          * UVC video drivers buggy
          
          
1. 3.0.69 - Consists of the following features
Features: * Support for user-controllable LEDs on the board 
          * GPIO support for the expansion headers 
          * ssh server 
          * Fast boot due to minimal services 
          * Linaro/Ubuntu Server 13.01 used as base 
          * Serial console enabled 
          * sunxi linux kernel 3.4.x 
          * Text-mode framebuffer console 
          * Kernel configured with maximal networking options
          * Loads of USB device drivers and handy things
          * Ethernet full duplex 100Mb/s 
          * Solved the speed fluctuations on reboot
          * SPI IRQ activated on certain GPIO
          * 7 UARTs configured


Issues    * UVC video drivers buggy
