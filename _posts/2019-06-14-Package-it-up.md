---
title: "Package it up"
categories:
  - development
tags:
  - packaging
  - java
  - phobox
  - announcement
---

I am currently experimenting with various package implementations to create an installer for Phobox for Windows, Linux and Mac. 

As a full-time web developer, it's completely new for me to distribute a Java desktop application :-)

**Update 1**

Unfortunately the first try with packr from badlogic doesn't work with spring boot for me. This packing tool is looks interessing and very uncomplicated. I think for simple JAR file applications (without spring) it's quite nice.

In the end I used the JavaPackager which is deployed with the JDK. And ... on windows I builded a working installer :-)


**Update 2**

Packaging with the javapackager from the Oracle JDK seems to be very easy - for windows and linux. Starting packaging with the openJDK the surprise is big ... no javapackager included. The OpenJDK will include a jpackager in version 13.
But good news, [Gluon](https://mail.openjdk.java.net/pipermail/openjfx-dev/2018-September/022500.html) provides an internal build for packaging. 
Now the hacking begins ...
