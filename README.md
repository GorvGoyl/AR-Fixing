Augmented Reality technology Superimposes virtual content on top of real-world objects in real time.

In maintenance field, AR could highlight a part to be replaced, identify special tools needed for the task, prescribe detailed work instructions, and display timely cautions about potentially hazardous activities and materials.

### What is this repository for? ###
This repository showcase the AR Android/iOS app which can be used for troubleshooting and fixing common device issues.
Demo Video: https://youtu.be/8Cb0AE99fI4

## How does the Android/iOS app work? ##

1) User opens the AR app.

2) AR app opens the phone camera.

3) User points the phone camera to the faulty device.

4) App detects the device using the object recognition technology. (For POC I've used QR codes but in an actual case there would be an actual printer. App would place virtual content on the actual printer instead on the 3D model of the printer as shown in the video)

5) App guides the user by showing virtual illustrations and animations on the object.

6) User follows the illustrations and troubleshoots the device efficiently.


### How do I set up for build? ###

* Summary of set up
Build the app for both iOS and android.

* Configuration
Android and iOS : 
	1. Android SDK(android) and XCODE(iOS)
	2. Unity
	3. Vuforia

* Dependencies
Supports Android 6 and above

* Database configuration
Vuforia Target Manager

* Deployment instructions
Switch on to debugger mode on your device while connected to the laptop. In Unity go to file->build and run.
