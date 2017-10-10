Jar To App
----------

Create a Mac OSX application (`.app`) froe any `.jar` file. Finally be able to view your Java apps with an icon and display it proudly in your applications folder. This project contains a basic template to bundle your jar file into an application in a few easy steps.

1. make sure the launcher script has the proper permissions to run. change into the app's root directory then use:

  `chmod a+x Contents/MacOS/launcher.sh`

2. rename everything and place your icon and jar application
  
  - rename the app itself
  - rename the `APP_NAME` in `Contents/MacOS/runner`
  - replace `app.jar` with your jar file
  - replace `application.icns` with an .icns file using ur image. (You can use an online tool such as [iconverticons.com](https://iconverticons.com/online/))

3. use application or create an issue here if you somehow fuck this up.
    
---------------------------

*Reformatted from Slavko Zitnik's blog. [Read more](http://www.zitnik.si/wordpress/2016/02/21/creating-a-mac-os-app-from-a-runnable-jar-file/)*
