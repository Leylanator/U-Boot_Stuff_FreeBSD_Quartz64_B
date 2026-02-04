# U-Boot_Stuff_FreeBSD_Quartz64_B
This repo is just to throw the binaries I need for the Quartz64 Model B to load up with u-boot. Binaries are from fresh ports: https://www.freshports.org/sysutils/u-boot-quartz64-b/

Expect a nicer and proper one-stop-shop guide later. But for now, just click through the link.

Important part is:
```
U-Boot loader and related files for the Pine64 Quartz-B

To install this bootloader on an sdcard just do:

dd if=/usr/local/share/u-boot/u-boot-quartz-b/idbloader.img of=/path/to/sdcarddevice seek=64 bs=512 conv=sync
dd if=/usr/local/share/u-boot/u-boot-quartz-b/u-boot.itb of=/path/to/sdcarddevice seek=16384 bs=512 conv=sync
```
