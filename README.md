ExhibitionScript
================

A shotty applescript to autorun applications. If the application stops running (clean quit, won't detect hang), it will warn you with a dialogue box. If you don't click the button, it will restart your machine in 10 seconds.


Be sure you tell the mac to not to try to detect a bluetooth keyboard or run the assistant (if you have none)

TO CONFIGURE:

1.In OSX, open the application "Automator"

2.Open an existing project -> This one.

3.Right now, you'll see it makes two calls to open "Chess". Replace the chess app with your app. Keep both calls.

4.In the applescript, replace "XXXXXXX" with the process name of your app. This can be found by running it and looking inside the Activity Monitor

5.Set the application to auto-run on login (as well as have your profile auto login) via system preferences -> Users

6.You may need to go into your security settings and add the reformatted application into a list of applications with the power to "control your computer." SysPrefs->Security->Privacy. Any changes you make will require you to re-add the new app to the list.


Good Luck!
