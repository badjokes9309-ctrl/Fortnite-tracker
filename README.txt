FORTNITE TRACKER - Android project

OPTION A - Android Studio (easiest)
 1. Install Android Studio, choose File > Open, pick this folder.
 2. Wait for Gradle sync, then Build > Build APK(s).
 3. APK: app/build/outputs/apk/release/app-release.apk  (copy to phone, tap to install)

OPTION B - No install, free via GitHub
 1. Create a GitHub repo and upload everything in this folder (keep .github).
 2. Actions tab > "Build APK" > Run workflow.
 3. Download the FortniteTracker-apk artifact when it finishes.

The app is your Fortnite_Tracker.html (app/src/main/assets/index.html) in a WebView.
It needs internet for stats lookups. Icon = your logo, all sizes included.
