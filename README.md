# Flutter_Template

This Template is included  easy_localization, flutter_launcher_icons

## how to use flutter_launcher_icons

if your flutter_launcher_icons is 0.9.2 or lower,
you need to change the `./android/app/build.gradle` file,
change compileSdkVersion, targetSdkVersion to 31,
change minSdkVersion to 21
after that you can run `flutter pub run flutter_launcher_icons:main` 
to create your icon for devices.
in the end: change your `./android/app/build.gradle` file return original state.