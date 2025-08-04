-----------------------------------------------Guide-------------------------------------------------
Download last ANDROID 14 firmware and EXTRACT it. 
Download and install SAMSUNG USB DRIVER.
Download and launch ODIN.
Put device in DOWNLOAD MODE and PLUG in PC. (POWER OFF and disconnected, then keep press VOL+ and VOL- then PLUG IN then short press on VOL+).
 (If not recognized by ODIN → Device Manager → Android... → Update Driver → ON COMPUTER → Samsung bootloader interface)
In ODIN, put "BL" firmware file in "BL" SLOT, "AP" in "AP" slot , "CSC" in "CSC" slot and "CP" in "CP".
Click START: device is being flashed with last stock firmware and reboots into it.
Select language/region, connect to Wifi and do all the "first boot stuff".
Enable DEVELOPER OPTIONS (Settings → About Tablet → Software informations → Click 7 times on BUILD NUMBER)
(Enable OEM UNLOCK) and USB Debugging in DEV. OPTIONS
Put device in DOWNLOAD MODE
UNLOCK BOOTLOADER (long press on VOL+ then confirm), device will WIPE DATA and reboot.
Select language/region, connect to Wifi and do the "first boot stuff".
Re-enable DEV. OPTIONS, USB DEBUGGING and check OEM UNLOCK is ENABLE.
-----------------------------------------------------------------------------------------------------------------
Enable DEVELOPER OPTIONS, check OEM UNLOCK is still ENABLE, Bootloader UNLOCKED and ENABLE USB DEBUGGING.
Download Magisk APK on Github and install it.
Copy the firmware "AP" file to your TAB.
Open Magisk, select "install" then "patch a file" and select the "AP" firmware file and hit "Let's GO".
Copy the patched "AP" to your computer and boot in DOWNLOAD mode (POWER OFF and disconnected, then keep press VOL+ and VOL- then PLUG IN and short press VOL+).
Put Magisk patched "AP" file in ODIN in the "AP" slot. Turn OFF AUTO-REBOOT in ODIN option. FLASH (Start).
Quit download mode (POWER and VOL- more then 7secs) and when screen turns off, directly boot into recovery (POWER and VOL+).
In recovery, wipe cache and wipe data/factory reset then REBOOT SYSTEM.
Select language/region, connect to Wifi and do all the "first boot stuff". 
Re-install Magisk APK, open it and click ok to Reboot.
You're TAB is now ROOTED, check ROOT status with ROOT CHECKER app. 
Boot into DOWNLOAD mode. In ODIN, on auto-reboot, flash TWRP in "AP" slot. So you have twrp!
-----------------------------------------------------------------------------------------------------------------
Take a coffee pause !
-----------------------------------------------------------------------------------------------------------------
Copy the "up_param.tar" file into the tab Download folder on your Tablet
Download, install and open Termux.
Type "apt update" and hit ENTER then "apt upgrade" and ENTER.
Type "su" and grant termux root privilege.
Type "dd if=/storage/emulated/0/Download/up_param.tar of=/dev/block/platform/bootdevice/by-name/up_param" and hit ENTER
Reboot, all warnings are gone.

-----------------------------------------------Guide-------------------------------------------------
Download last ANDROID 14 firmware and EXTRACT it. 
Download and install SAMSUNG USB DRIVER.
Download and launch ODIN.
Put device in DOWNLOAD MODE and PLUG in PC. (POWER OFF and disconnected, then keep press VOL+ and VOL- then PLUG IN then short press on VOL+).
 (If not recognized by ODIN → Device Manager → Android... → Update Driver → ON COMPUTER → Samsung bootloader interface)
In ODIN, put "BL" firmware file in "BL" SLOT, "AP" in "AP" slot , "CSC" in "CSC" slot and "CP" in "CP".
Click START: device is being flashed with last stock firmware and reboots into it.
Select language/region, connect to Wifi and do all the "first boot stuff".
Enable DEVELOPER OPTIONS (Settings → About Tablet → Software informations → Click 7 times on BUILD NUMBER)
(Enable OEM UNLOCK) and USB Debugging in DEV. OPTIONS
Put device in DOWNLOAD MODE
UNLOCK BOOTLOADER (long press on VOL+ then confirm), device will WIPE DATA and reboot.
Select language/region, connect to Wifi and do the "first boot stuff".
Re-enable DEV. OPTIONS, USB DEBUGGING and check OEM UNLOCK is ENABLE.
-----------------------------------------------------------------------------------------------------------------
Enable DEVELOPER OPTIONS, check OEM UNLOCK is still ENABLE, Bootloader UNLOCKED and ENABLE USB DEBUGGING.
Download Magisk APK on Github and install it.
Copy the firmware "AP" file to your TAB.
Open Magisk, select "install" then "patch a file" and select the "AP" firmware file and hit "Let's GO".
Copy the patched "AP" to your computer and boot in DOWNLOAD mode (POWER OFF and disconnected, then keep press VOL+ and VOL- then PLUG IN and short press VOL+).
Put Magisk patched "AP" file in ODIN in the "AP" slot. Turn OFF AUTO-REBOOT in ODIN option. FLASH (Start).
Quit download mode (POWER and VOL- more then 7secs) and when screen turns off, directly boot into recovery (POWER and VOL+).
In recovery, wipe cache and wipe data/factory reset then REBOOT SYSTEM.
Select language/region, connect to Wifi and do all the "first boot stuff". 
Re-install Magisk APK, open it and click ok to Reboot.
You're TAB is now ROOTED, check ROOT status with ROOT CHECKER app. 
Boot into DOWNLOAD mode. In ODIN, on auto-reboot, flash TWRP in "AP" slot. So you have twrp!
-----------------------------------------------------------------------------------------------------------------
Take a coffee pause !
-----------------------------------------------------------------------------------------------------------------
Copy the "up_param.tar" file into the tab Download folder on your Tablet
Download, install and open Termux.
Type "apt update" and hit ENTER then "apt upgrade" and ENTER.
Type "su" and grant termux root privilege.
Type "dd if=/storage/emulated/0/Download/up_param.tar of=/dev/block/platform/bootdevice/by-name/up_param" and hit ENTER
Reboot, all warnings are gone.
Note: we do not guarantee it will run 100% and it does not mean you can hide root if you want to hide root please install zygisk and these files are only for Samsung Galaxy Tab A7 Lite if your device is broken we will not test please do not talk in a pushy way please talk gently if you want to add new features please chat to let us know thank you
