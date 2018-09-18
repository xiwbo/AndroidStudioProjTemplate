# AndroidStudioProjTemplate
Thanks to Sir Wax :)

Add the gradle and adb.exe in PATH of your Environmental Variables..

To run the project, open a command line or bash
NOTE: Make sure that the bash is open in the project folder.
Type "gradle build"
  if the build is unsuccessful, check the PATH or check your code.
  
  else if the build is successful, go to the folder build/outputs/debug folder
      you will see your <ApplicationName>-debug.apk
        if you see the apk your good to go! if not you might wanna re-run the project.
        open a new bash in the same folder where the apk is located then type "adb install -r <ApplicationName>-debug.apk"
        NOTE: Make sure that your Mobile Device is ON and it needs to be connected in the laptop
              and the USB Debugging Mode is turned ON also.
              
        Then you will a Message indicated that the app is installed on your device.
        
        Happy Coding! :)
