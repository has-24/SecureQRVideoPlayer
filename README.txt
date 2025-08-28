SecureQRVideoPlayer
===================

This Android Studio project implements a simple app that scans QR codes and launches VLC to play video streams.
Important notes:
- The app passes the scanned URL directly to VLC without displaying it.
- VLC must be installed on the device for playback.
- The project uses ZXing embedded library for scanning.
- Gradle wrapper JAR is not included; please open the project in Android Studio which will handle Gradle wrapper generation/download automatically.
How to build:
1. Open this project in Android Studio (File -> Open -> select SecureQRVideoPlayer).
2. Let Android Studio sync Gradle and download dependencies.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).