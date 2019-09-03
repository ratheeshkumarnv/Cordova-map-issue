# Cordova-map-issue
This shows Done/Cancel button offset issue with Cordova wheel selector when google maps plugin is installed. Only happens in iPhone XR/XS devices.

# Installation
Clone it, add cordova ios platform and run it on iPhone XR/XS simulator or device.

# Steps to reproduce
Click on 'Show List' button on the first screen. The wheel selector will display with Done and Cancel buttons.
Click on the buttons but no action will be fired. But if clicks on slightly top area of the buttons, it works. 

This works fine when google maps plugin is uninstalled. Adding it back again produces same issue.
