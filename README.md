# Firebase Chat
This repo is a very simple (but working!) android chat using Firebase Relatime Database!
This Google I/O conference may be helpful if you're learning like me: https://www.youtube.com/watch?v=xAsvwy1-oxE

# Gradle and other settings

In your build.gradle Project file, add:

    classpath 'com.google.gms:google-services:3.0.0'
  
In your build.gradle Module file, add:

    compile 'com.google.firebase:firebase-database:9.2.1'
  
Then open up your _SDK Manager_ and install **Google Play Services** and **Google Repository** (both are located under **_Extras_**).

You should have generated a **google-services.json** file with Firebase website, place it at: **_/YourProject/app_**

That's it, you should be ready to code!

# Important note

The is not using any kind of authentification, thus your firebase server should accept every connection. Of course this is not secure, this was just for the example.
