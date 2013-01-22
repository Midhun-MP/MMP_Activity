MMP_Activity
============

Module for Titanium, which helps user to integrate a activity indicator similar to MBProgressHUD to Titanium App.

Step to integrate the module with your project:

	1) Unzip the zip file
	2) Copy the com.midhun.progress folder to your Appcelerator titanium's iPhone module folder.
If you didn't changed the install path the normal path will be:

~/Library/Application Support/Titanium/modules/iphone
	3) Go to the TiApp Editor page of your project.
		a) If you are using the GUI interface add the module on the right side window.
		b) If you are using the xml file, add the below lines to your tiapp.xml.
			<modules>
        			<module platform="iphone" version="1.0">com.midhun.progress</module>
    			</modules>


Create the activity indicator:

	var smsModule = require('com.midhun.progress');
        var wind = Ti.UI.createWindow();               //your window
        var foo = my_module.createHUD({
	    color	:"transparent",
  	    width	:'100%',
  	    height	:'100%',
  	    text  	: "Hello",
  	    type  	: "MMP_Type4",  
        });                                          //creating Activity Indicator
       wind.add(foo)                                 //Adding indicator to your window


For Further Details Contact:

	Midhun M P
	Email : midhunmp7@gmail.com
	Mobile: +91 9846389231


Special Thanks
--------------
MBProgressHUD team (https://github.com/matej/MBProgressHUD) and Matej Bukovinski.