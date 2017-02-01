# About
This is an migrated project of [lipitk](https://github.com/hplabsindia/Lipitk) by [HP Labs India](https://github.com/hplabsindia). This project is Gradle based and all the external libraries has been taken care of.

# Requirements
1. [Android Studio](https://developer.android.com/studio/index.html)
2. [External NDK](https://developer.android.com/ndk/downloads/index.html) or Internal using SDK Manager
3. [OpenCV](http://opencv.org/)

# Steps to Follow
1. **Fork then Clone/Clone/Download as ZIP** the project files.
2. Go to Android.mk file located in `app/src/main/jni`.
3. Change
`PATHH := D:\Temporary\LipiTK-Backup\app\src\main\jni` to your jni directory.
4. `-I C:\OpenCV\build\include \` to your `OpenCV` directory.
5. Right click on the project files and click on `Link C/C++ project...`
6. Select the Android.mk File that you edited.  
7. Sync Gradle and Run.

**Note : The API is pretty stable for single character but, is not that accurate.**
