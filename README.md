# OS-EX.3-TROUBLESHOOTING-OF-OS---CASE-STUDY

## AIM:
Troubleshooting an Operating System

## OBJECTIVE:
To diagnose and resolve common issues in an operating system.

## MATERIALS:
Computer with the problematic OS Access to user documentation or online resources

## PROCEDURE:

### STEP 1: Run Playing Audio troubleshoot
You can treat this tool as a first-aid solution for fixing audio problems. This in-built tool can find and fix audio problems automatically.Open the Settings app and go to System.Under System, go to Troubleshoot > Other troubleshooters.Click on Run next to Playing Audio troubleshooter.

1.Open the Settings app and go to System.

2.Under System, go to Troubleshoot > Other troubleshooters.

3.Click on Run next to Playing Audio troubleshooter.
![OUTPUT](/1.png)
In a few moments, you will see that the Playing Audio troubleshooter has found some problems and fixed them. If the troubleshooter found some issues but can't fix them, continue following other methods mentioned next in this guide.
![OUTPUT](/1.2.png)
### STEP 2: Fix by updating the Audio driver
In most of cases involving audio problems, audio drivers can be the main root cause. You can try the following suggestions if the audio driver is causing an audio problem on your system:

1.Right-click on the Start button or press Windows + X and select Device Manager.

2.Under Device Manager, expand Sound, video, and game controllers or section where audio devices are listed.

3.Locate your audio device/driver and double-click on it.

4.Verify if the device status is This device is working properly.

5.If there is some error code with the device/driver, refer to this support article to troubleshoot it.
![OUTPUT](/2.png)

### STEP 3: Updated or roll back your audii driver
If the audio driver is listed and working properly, but still you don't get your audio issue fixed, next you can try updating your audio driver. Double click on the audio driver, go to Driver tab and click Update driver. Follow on-screen instructions to complete the update.
![OUTPUT](/3.png)
### STEP 4:Fix the audio services
If running a troubleshooter and making changes to the audio driver was of no help, you can next check for audio background services.

1.Press Windows + R, type services.msc and click OK.

2.In the Services window, make sure these services are Running and have their Startup type set to Automatic:

3.Windows Audio

4.Windows Audio Endpoint Builder

5.Remote Procedure Call
![OUTPUT](/4.png)
### STEP 5: Disable audio enhancements
If previous methods were not helpful, then you can try disabling audio enhancements and see if it helps:

1.Go to Settings > System > Sound.

2.Click More sound settings.

3.On the Sound tab, select your primary audio device and click Properties.

4.On the property sheet, go to the Enhancements tab.5.

5.Check Disable all enhancements.

6.Click Apply, OK.
![OUTPUT](/5.1.png)
If audio is not working on some specific apps, you go to the Advanced tab and uncheck Allow applications to take exclusive control of this device option. Click Apply, OK.
![OUTPUT](/5.2.png)




<!-- PROCEDURE: -->


## RESULT:
Troubleshooting of OS has been done successfully.


