# 😛😛 Chat  Real Time in Flutter😁😁

The application is a simple real time chat platform developed using the technologies below:

- Dart - Language
- Flutter - Framework
- GetX - State Manager
- Firebase - Store and Authentication
- OneSignal - Push Notifications



## 😐 Instructions for integrating with Firebase 😑

- place the google-services file inside the folder: android >> app

-  add => inside the android file ⏩ build.gradle

  ​	dependencies {
  ​    	   ...
  ​    	   // Add this line
  ​    	   classpath 'com.google.gms:google-services:4.3.8' // or the version firebase indicates
    	}

- inside the android file ⏩ app   ⏩ build.gradle modify minSdkVersion to 25

- inside the android file ⏩ app ⏩ build.gradle add right below apply plugin: 'com.android.application'
  add => apply plugin: 'com.google.gms.google-services'



## 😐 Instructions for integrating with One Signal😑

- inside the android file ⏩ build.gradle add the following code below jcenter()
  add line => maven{ url 'https://plugins.gradle.org/m2/' }
- inside the android file ⏩ build.gradle add the following code inside dependencies
  add line => classpath 'gradle.plugin.com.onesignal:onesignal-gradle-plugin:[0.12.1, 0.99.99]'
- inside the android file ⏩ app ⏩ build.gradle add
  apply plugin: 'com.onesignal.androidsdk.onesignal-gradle-plugin'

