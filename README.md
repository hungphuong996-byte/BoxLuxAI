Box Lux AI - Android App Source (Starter)
=========================================
This is a minimal Android project skeleton (Kotlin) for "Box Lux AI".
Features:
 - Full-screen (immersive) theme for in-car use
 - Bottom navigation with two tabs: Home and Settings
 - Home: Device ON/OFF demo toggle (shows status)
 - Settings: placeholder for future features (OTA, voice)
 - Uses AndroidX, Kotlin and simple layouts

Important notes before building:
 - This is source code only. You need to build (assembleRelease) to get an APK.
 - You can build using Android Studio on PC, or use cloud builders that accept Android projects:
   * GitHub + GitHub Actions (recommended) - see .github/workflows included
   * app builders that accept zipped Android projects
 - To enable voice/OTA features you must add dependencies and models (not included).

Quick build using GitHub Actions:
 1. Create a GitHub repo and upload the contents of this folder (preserve the folder structure).
 2. The provided .github/workflows/build.yml will run `./gradlew assembleRelease` and upload the APK artifact.
 3. Run the workflow in the Actions tab and download artifact.

App icon:
 - A placeholder car vector drawable is included (res/mipmap-anydpi-v26/ic_launcher.xml and res/drawable/ic_car.xml).
 - You can replace with your own PNG in app/src/main/res/mipmap-*/.

License: MIT (you can modify)
