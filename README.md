# Android QPST Tool [ROOT]  
An Android application which has various features for fixing baseband etc. problems on Qualcomm Snapdragon devices  
  
[Türkçe Google Translate çevirisi](https://github-com.translate.goog/symbuzzer/android-qpst-tool/blob/main/README.md?_x_tr_sl=en&_x_tr_tl=tr&_x_tr_hl=tr&_x_tr_pto=wapp)  
  
## How to use:
- Download latest apk file from [releases page](https://github.com/symbuzzer/android-qpst-tool/releases).    
- Install it on your rooted Android device.  
- Give it root permission.  
- For using "Erase EFS" and "Reboot" options, click its button and when it indicates red press and hold same button again.  

## Features:  
- Activating QPST (QUALCOMM DIAG) mode with one click.  
- Erasing problematic EFS paritions (/dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10) with one click.  
- Rebooting with one click.
- Eye-candy design

## Notes:  
- Tested on Xiaomi Mi 10T Pro which is Qualcomm Snapdragon 865. Should work other Snapdragon 865 devices too.  
- ! Use at your own risk !
- Erase EFS feature will erase EFS paritions (/dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10). Since these partitions are device specific, be sure to back them up first.  
  
## How to compile:  
- This app is created with Tasker (v6.1.3-beta) and Tasker App Factory (v6.1.3-beta). So download and install them or their newer builds on your device.  
- Download QPST_Tool.prj.xml and import it as project from Tasker Android App.  
- Set app icon on profile options, Main and HtmlViewer scenes.  
- Set "start task: Start", "min android version: 21" and "target android version: 22" (Should be max 22 because of Tasker App Factory's damn notification problems)  
- Finally you can export as standalone app.  
  
## Changelog:  
- See [CHANGELOG.md](https://github.com/symbuzzer/android-qpst-tool/blob/main/CHANGELOG.md)
  
## Screenshots:
![](https://github.com/symbuzzer/android-qpst-tool/blob/main/screenshot1.jpg?raw=true)
