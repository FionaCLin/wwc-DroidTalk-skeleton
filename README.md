# DroidTalk: Women Who Code August 2016
This git repo contains the skeleton code to get started building out DroidTalk, a messaging app.

# Setup! 
There are many ways to deploy the app. 

You can either use a real physical Android device, use Genymotion (an Android emulator) or use the inbuilt emulator provided by Android Studio. 

**Follow the appropriate instructions to set up (at least) one of the ways to deploy the app.**

## Project common setup 
1. Make sure you have [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 
2. Install [Android Studio, which includes Android SDK](https://developer.android.com/studio/index.html)
3. Clone this repository 
```
git clone https://github.com/jleu1656/wwc-DroidTalk-skeleton.git
```

## Setting up Genymotion
1. Install [Oracle VM VirtualBox](https://www.virtualbox.org/wiki/Downloads). If you already have Oracle VM VirtualBox, make sure that you installed version 5.0.4 or above.
2. Install [Genymotion](https://www.genymotion.com/), the Android emulator app we will be using for testing DroidTalk
3. Install a virtual device with API 19+ on GenyMotion, such as Google Nexus 5 API 21 or Samsung S5 API 19. 

## Setting up the inbuilt Android Studio emulator 
1. Open AVD Manager in Android Studio
2. Select Create Virtual Device > Select a device and click next 
3. Select a system image (make sure it's API 19+, we recommend 22 or 23) > Next
4. Finish to create your new virtual device  

## Setting up your physical device 
1. Go to your phone settings > About phone 
2. Tap on the Build Number 7 times to enable Developer Options
3. Go back to the main settings > Developer Options
4. Enable USB Debugging

# Running the app 
1. Open the project in Android Studio
2. Launch your virtual device on Genymotion OR connect your Android device via USB to your machine
3. In Android Studio, shift + f10 or click on the green play button to build the app. Select a virtual device

# Troubleshooting 

## Genymotion VirtualBox error; Failed to open a session for the virtual machine {virtual device name}
To fix: disable audio or change to Core Audio as the Host Audio Driver	
1. Open Virtual Box
2. Select Android VM (e.g. Samsung Galaxy S6 - 6.0.0 - API 23 - 1440x2560)
3. Click Settings on top
4. Go to Audio and uncheck Enable Audio checkbox

## Error: could not install *smartsocket* listener: Address already in use
Change add in Genymotion (in Settings) to use the same sdk path as Android Studio. Then close Genymotion and restart Android Studio 

## My app isn't running even though studio already sees the devices 
Instant Run requires 'Tools | Android | Enable ADB integration' to be enabled

# Further Reading
Android developer guide: https://developer.android.com/guide/index.html

Material Design: https://material.google.com/ 
