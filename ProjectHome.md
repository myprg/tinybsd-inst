Based on TinyBSD installer of TinyBSD. Live USB mode and installation with simple interface for configurating of the network (based on predefined values). Image is 32Mb, installed system is about 16Mb, good for fast installation of FreeBSD for embedded devices, used MFS root and doesn't need disk writing. Contents: mksh shell, tmux console "switcher", additional partition for user "firmware".

'osinst' script boots TinyBSD from USB and installes system if user select it (instead of the "live-usb mode"). 'build.my' script creates image and copy one to USB flash storage. 'tinybsd.my' is modified 'original 'tinybsd' script to support included and excluded files' lists for OS image (see 'tinybsd.patch').

Tested on LX-800 board (AMD based).

This project can be used with some customization.