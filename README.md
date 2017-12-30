Package Instalations
--------------------

NOTE THESE ARE FOR FIRST TIME SETUP.

1. Install CocoaPods
    - pod install (from the application root directory)
2. Getting firebase ready
    - Go to firebase console (console.firebase.google.com)
    - Click Create a new Project
    - Name your project chatmessenger
    - Click Add Firebase to your iOS app
    - Add bundle ID you can find it in your applications settings under general in XCode
    - Download GoogleService-Info.plist file
    - Add it to the root folder of your application.
    - Click continue in firebase console.
    - No need to add anything to Podfile, everything is already added. Just do pod install if you haven't already.
    - Click continue in firebase console, no need to add any code, it's already there in AppDelegate.swift
    - Go to authentication tab from your firebase console, click Sign-in methods and enable Email/Password method.
    - Go to storage tab, and enable it.

That is it folks!!!
You are up and running with your new chat application for iOS devices. :)
