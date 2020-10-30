# General
These configuration files are used to configure Marlin 2.x for Creality Ender-3 Pro with or without Silent Mainboard v1.1.5. To get more information how to use these files visit https://marlinfw.org.
# Prerequisites
To compile and use your own Marlin-firmware you need a 3D-printer having bootloader installed. If you don't have a bootloader installed there are a lot of guides around how to install a bootloader to your Creality Ender-3 Pro.<br><br>
Please install missing bootloader on your own, because I've never installed one by myself for my Creality Ender-3 Pro using Silent Mainboard v1.1.5 ... ;-)<br>
This seems to be a good starting point for installing bootloader to your 3D-printer:<br>
https://all3dp.com/2/ender-3-with-marlin-how-to-install-marlin-firmware-on-your-ender-3
# How To
* Download Marlin 2.x source from the site above
* Extract sources
* Place the all files suited for your printer type to Marlin folder located below your extraction folder from the step above
* Follow this german guide to compile Marlin by your own:<br>https://www.longrisoft.de/cnc/ender-3/marlin-auf-dem-ender-3-installieren
* Upload firmware file to your printer
# Language
Selected language is for this configuration is English (en). To change used language to for example German (de), modify LCD_LANGUAGE in configuration file Configuration.h to your needs.
# Reduce Marlin binary size
If you have problems with Marlin binary size or if you want to disable SLIM_LCD_MENUS or enable ARC_SUPPORT for manual mesh bed levelling branches, use my Sanguino-fork at https://github.com/ariaci/Sanguino to enable some compiler optimizations to reduce binary size.
