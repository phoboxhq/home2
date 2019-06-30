---
permalink: /getting-started/
layout: splash
header:
    overlay_image: /assets/images/splash_getting-started.png
title: "Getting started"
modified: 2019-06-23T17:30:00-04:00
---

_This page is under construction_

## Installation
 * Download phobox as you need it
   * windows, linux, mac installer with JRE
   * plain jar
   * docker-image

## Startup
 * Start the application
   * the installer creates a starter in the startmenu
   * plain jar: `java -jar phobox.jar`
```
usage: phobox
 -b,--backupDirectory <arg>   Sets the directory for backups
 -db,--dbbrowser              Activates the integrated database browser
                              (port 8082)
 -h,--help                    Prints this help
 -nw,--noWindow               Hides the application window for headless
                              usage
 -p,--port <arg>              Sets the port for this application (default
                              8080)
 -s,--storage <arg>           Defines the main storage path
 -w,--watchDirectory <arg>    Scans this directory for new files
```
 * On the first run phobox asks for the photostorage. Select the directory with all your photos.
 * If the programm runs correctly, a browser will be opend up and presents your files
 * It could take a while until all thumbnails are created
 * Phobox doesn't change the structure or photos of your directory. It creates just a new subdirectory named "phobox" which contains all necessary files.
 
## Import files
 * There are different ways to import files to your phobox:
   1. copy your files into the subdirectory `phobox/import/`
   2. open "upload" in the left menu in the webinterface and drag and drop your files into the dropzone
   3. copy your files to the specifed watch-directory

## Configuration
 * To change your settings, you can open the settings page in the webinterface or use the .phobox.properties file in your home directory
 * You can change this setting in this file as well, but the phobox has to restart after this change
 * For more configuration information [look here](https://github.com/phoboxhq/phobox/wiki/Configuration)
