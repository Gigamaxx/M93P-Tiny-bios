# M93P-Tiny-bios
**** Use at your own risk **** Be carefull and follow all the steps through to completion.    
Bios flash back to 2016 version for Hackintosh compatibility.
Directions: Format a USB stick 16gb in Fat32, unzip the folder and add the files.   
Remove all other connected drives tothe system and start PC, hold Fn and F12 keys and toggle back and forth to enter bios.
In Bios set Optimzed Defaults, set CSM to enabled and set boot to Auto which will allow legacy boot, save and exit.
Start PC with USB plugged in.
At first command prompt type:dir' then hit enter.
At second command prompt type:cd . then hit hit enter.
At third command prompt type:flash2.exe imagefb.rom hit enter.
When it boots into the bios screen it will ask if you want to downgrade bios to older version type: n
At second prompt it will ask if you want a new serial # type: n
At third prompt it will ask if you want to change model # type: n
Wait for it to finish and reboot. At reboot remove the USB stick and enter into bios.
Check for the bios date to see that os is 2016 version.
Now your Lenovo M93P Tiny shpul dbe able to boot clover into Yosemite through Catalina.
