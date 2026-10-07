# Gupta's Parcha — Android Project

Native Android application project for the Gupta's Parcha shop workflow.

## Current version
- Application ID: `com.guptasparcha.app`
- Version: 1.0
- Minimum Android: API 23
- Target/compile SDK: 36
- Android Gradle Plugin: 9.4.1
- Java: 17

## Build
Open this folder in Android Studio and let Gradle sync. Then run `assembleDebug` or use Build > Build APK(s).

The current Parcha UI is bundled under `app/src/main/assets/index.html` and runs inside the native Android WebView shell. Its data is stored locally on the device.
