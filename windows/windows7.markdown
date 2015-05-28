## window7 SOP
step 1. download windows7's .iso file

step 2. if you are windows7 you can use "Windows 7 USB/DVD Download Tool" to make your bootable USB drives
		
		here, we make bootable USB by **dd** command, you can input ** sudo dd if=(.iso file position) of=(usb file position)
		
		for example **dd if=/home/user/desktop/window7.iso of=/dev/sdb1**

step 3. insert your usb and turn on the computer you want to install

step 4. press the button (maybe del) to enter BIOS page, choose the usb to be your first boot device, and then store it and exit.

step 5. you should see the page showing the windows is ready to be installed.(ensure your network cable is inserted)

step 6. set up the options as you want.

step 7. when the desktop page comes up, go to control panel/internet options/connect/set up LAN/ check the proxy and input your proxy address.

step 8. finally, go to control panel/windows update make your computer update regulerly automaticly.



