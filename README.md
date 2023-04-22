# Android QPST Tool [ROOT]  
An Android application which has various features fixing IMEI problems on Qualcomm Snapdragon devices  
  
## How to use:
- Download latest apk file from [releases page](https://github.com/symbuzzer/android-qpst-tool/releases).    
- Install it on your rooted Android device.  
- Give it root permission

## Features:  
- Activating QPST (QUALCOMM DIAG) mode with one click.  
- Erasing EFS paritions (/dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10) with one click.  
- Rebooting with one click
- Eye-candy design

## Notes:  
- Tested on Xiaomi Mi 10T Pro which is Qualcomm Snapdragon 865. Should work other Snapdragon devices too.  
- ! Use at yout own risk !
- Erase EFS feature will erase EFS paritions (/dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10). Since these partitions are device specific, be sure to back them up first.  
  
## How to compile:  
- This app ise created with Tasker (v6.1.3-beta) and Tasker App Factory (v6.1.3-beta). So download and install them or theri newer builds on your device.  
- Download QPST_Tool.prj.xml and import it as project from Tasker Android App.  
- When importing complete, you can export as standalone app.  
  
## Changelog:  
- See [CHANGELOG.md](https://github.com/symbuzzer/android-qpst-tool/blob/main/CHANGELOG.md)
  
## Screenshots:
![](https://github.com/symbuzzer/android-qpst-tool/blob/main/screenshot1.jpg?raw=true)
