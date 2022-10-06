# HP 15 p262nf Hackintosh 
 Hackintosh on MacOS Monterey on HP 15-p262nf 


**Configuration**

You need to modify the config.plist with your smbios, generate with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and use "MacBookAir7,2"

**Known issues**

- The TrackPad is not officially recognized by MacOS, but it works (I am looking for a fix)
- WiFi and Bluetooth do not work, the WiFi card is not compatible. (You can change it and manually insert an appropriate Kext, you must insert it in the Kexts folder and you must update config.plist)
- You must activate the CSM mode in the bios otherwise MacOS will not display correctly at startup.
