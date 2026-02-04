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

This repo is _very much_ WIP.
I will eventually turn it into a useful guide for getting FreeBSD to run on Quartz64 Model B, and provide a way for people not already on FreeBSD to do it easily with the files I've already uploaded here.
The recommended method of install is currently to flash the A-Model's image, and then swap out some boot files for the ones the Model B uses.

At this moment, it's a "figure it out yourself" situation. I want it to be a tad more foolproof for fools like I.
