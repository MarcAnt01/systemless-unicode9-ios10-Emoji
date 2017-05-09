# iOS10 Emoji
Changes the default emoji font to the iOS10 Emoji for various android devices.
This module also changes the system font configuration so the font pack is loaded first.

**_Note:_** When you experience problems with fonts reboot for a second time.

## Preview of all the iOS10 emojis included in this module:
![All included](http://i.imgur.com/Scr2QQq.jpg)
All the included emojis.

## Prerequisites
* Magisk v11.6 or higher

**_Note:_** Tested on the Oneplus x running various android 6 and 7 roms with Magisk v11.6 and v12.0. Your mileage may vary.

## How to download & install this module
Inside [Magisk manager app](https://play.google.com/store/apps/details?id=com.topjohnwu.magisk) go to the "Downloads" section. 
You can find "iOS10 emoji font" listed their. 
Click on the download button (down arrow) and then click on "install". 
Wait a few seconds for the download & installing to finish.  
After installing click on "reboot". Your device should reboot. 

**_Note:_** When you experience problems with fonts not displaying correctly reboot for a second time. This should fix some fonts not displaying correctly.

**_Note:_** When you experience problems installing this module check out this [discussion on XDA](https://forum.xda-developers.com/apps/magisk/magisk-ios10-emoji-font-t3596503)

**_Note:_** Clear data of your keyboard app to enable ALL the Emoji fonts inside your keyboard app.

## How it works
Replaces the default emoji font (NotoColorEmoji.tff) with the iOS10 variant. 
Also modifies your original fonts.xml & fallback_fonts.xml files with the sed command to update your font order.

## Links
* [Magisk forum](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)
* [Magisk manager app](https://play.google.com/store/apps/details?id=com.topjohnwu.magisk)
* [Manual zip download](https://drive.google.com/drive/folders/0BzOEHiXH09zFTnVKNjAtZUVlR3c?usp=sharing)
* [Discussion on XDA](https://forum.xda-developers.com/apps/magisk/magisk-ios10-emoji-font-t3596503)
* [Bug report](https://github.com/Magisk-Modules-Repo/Magisk-ios10-Emoji-font/issues/new)
* [Github](https://github.com/Magisk-Modules-Repo/Magisk-ios10-Emoji-font)
* [Donate](http://paypal.me/jeanpierrewolters/5)

## Change Log 
#### version 5
* Added  post-fs-data script
* Dynamic fonts.xml
* Dynamic fallback_fonts.xml

#### version 4
* Updated font file
* Some typo's fixed
* Updated support links

#### version 3
* Updated module for magisk v11.6

#### version 2
* Name updated
* Description added
* Added Donate link

#### version 1
* Initial Release
