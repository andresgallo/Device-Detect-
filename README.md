Andres Gallo's Device-Detect-
============================

Many modern web applications place emphasis on the android platform and iOS when it comes to smartphones, however when that is not enough knowing if the device can support touch capabilities and more is the way to go

Using it in javascript
----------------------

To use it simply have this script available before the code where you will be using the device detection. You can use it like
	
	if(deviceType.isTouch)document.body.className += ' deviceIsTouch ';
	//For example if you want to change styles based on touch screen capabilities, which css alone can't detect.
	//I have added support for htc as well as their browser has issues with zooming in and other stuff specific to the htc brand. 