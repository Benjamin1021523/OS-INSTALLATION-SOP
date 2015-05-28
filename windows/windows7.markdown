## window7 SOP
step 1. Download windows7's .iso file.

step 2. If you are windows7 you can use "Windows 7 USB/DVD Download Tool" to make your bootable USB drives.
		
		Here, we make bootable USB by *dd* command, you can input *sudo dd if=(.iso file position) of=(usb file position)*
		
		For example *dd if=/home/user/desktop/window7.iso of=/dev/sdb1*

step 3. Insert your usb and turn on the computer you want to install

step 4. Press the button (maybe del) to enter BIOS page, choose the usb to be your first boot device, and then store it and exit.

step 5. You should see the page showing the windows is ready to be installed.(ensure your network cable is inserted)

step 6. Set up the options as you want.

step 7. When the desktop page comes up, go to control panel/internet options/connect/set up LAN/ check the proxy and input your proxy address.

step 8. Finally, go to control panel/windows update make your computer update regulerly automaticly.



