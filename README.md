# Modern Australis
A userChrome tweak to make Firefox's Australis tabs into nice, simple rectangles, following Microsoft's Windows 10 UI design.

## Install

Go to about:support and click on "Show Folder", this will take you to your Firefox profile folder. In this folder you will need to create a new directory called "Chrome" if it doesn't already exist. Place userChrome.css inside this directory (File path should be '[Firefox Profile Folder]\Chrome\userChrome.css)' and restart firefox.

## Compatibility

Tested on Windows 7 and 10, OSX 10.11.5 and Ubuntu 16.04 LTS.
Only works with Firefox 29.x and up.

## User Tweaks

Colours can be changed by chaning all of the linear-gradient colours on line 78 in userChrome.css. The default for line 78 is
> background-image: linear-gradient(rgba(215,215,215,1) 50%, rgba(215,215,215,1) 50%, rgba(215,215,215,1) 50%) !important;

## Preview

Left tab is active tab, middle tab is when the mouse is hovering over it and the right tab is inactive.
![alt text](http://i.imgur.com/usJU0Ew.png)
