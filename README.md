Android Asset Studio
====================

**[Open the Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/)**

A web-based set of tools for generating graphics and other assets that would eventually be in an Android application's res/ directory.

Currently available asset generators area available for:

- Launcher icons
- Action bar icons
- Notification icons
- Device-framed screenshots
- Simple nine-patches

###How to build
- Install java sdk and add to PATH (/bin, /jre) http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html
- Install ant and add to PATH (/bin) http://ant.apache.org/bindownload.cgi
- Install flinkjs and add to PATH (/bin) https://code.google.com/archive/p/flintjs/
- Modify the line in src/js/build.xml referring to flintjs:
```
<import file="<your_path>/flintjs-0.1.1/flintjs.build.xml"/>
```
- Run make.sh (./make.sh or sh make.sh)
- Source will generate at _gh-pages foler

