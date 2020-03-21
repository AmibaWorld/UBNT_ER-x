# UBNT_ER-x
UBNT_ER-x 固件刷机

>scp /path/to/openwrt-ramips-mt7621-ubnt-erx-initramfs-kernel.bin ubnt@192.168.1.1:/tmp
>ssh ubnt@192.168.1.1
ubnt@ubnt:/$cd tmp
ubnt@ubnt:/tmp$add system image openwrt-ramips-mt7621-ubnt-erx-initramfs-kernel.bin
Checking upgrade image...Done
Preparing to upgrade...Done
Copying upgrade image.../usr/bin/ubnt-upgrade: line 509: [: too many arguments
Done
Removing old image...Done
Checking upgrade image...Done
Copying config data...Done
Finishing upgrade...Done
Upgrade completed

ubnt@ubnt:/tmp$show system image
The system currently has the following image(s) installed:
ramips Bleeding Edge r49395 (default boot) 
v1.7.1.4821926.151103.1114 (running image) 
A reboot is needed to boot default image
