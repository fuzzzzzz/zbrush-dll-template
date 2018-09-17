zbrush-dll-template
===================
Don't use if you don't want to contribute to the project.

Objective :
-----------

First objective of mine is to get a version that compile for PC with visual studio community 2017.
Second objective is to find someone who could build the dynamic link Library with Xcode ( i don't own a mac so..).
Next Step would be to make it compiles with Cmake, so cross plateform support could be possible.


First commit note :
-------------------

The code is a bit buggy, Zbrush crashes when the HELLO Dll Button is pressed.

Installation : 
--------------

* Copy plugin-template.txt and plugin-template directory to Zplug64 in Zbrush Startup installation.
* In zbrush "Script > load script" load the plugin-template.txt file.
