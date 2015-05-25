## window7 SOP
step 1. download windows7's .iso file
step 2. if you are windows7 you can use "Windows 7 USB/DVD Download Tool" to make your bootable USB drives
		here, we make bootable USB by **dd** command, you can input ** sudo dd if=(.iso file position) of=(usb file position)
		for example **dd if=/home/user/desktop/window7.iso of=/dev/sdb1**
