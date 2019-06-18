---
permalink: /getting-started/
title: "Getting started"
modified: 2019-06-18T21:13:00-04:00
---

_This page is under construction_

## Installation
 * Download phobox as you need it
   * windows, linux, mac installer with JRE
   * plain jar
   * docker-image

## Startup
 * Start the application
   * the install creates a starter in the startmenu
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
 * If the programm runs correctly, a browser will be opend up and presents your files
 * It could take a while until all thumbnails are created

## Configuration
 * On the first run phobox asks for the directory with the pictures
 * This setting is stored in .phobox.props in  your home directory
 * You can change this setting in this file as well, but the phobox has to restart after this change

