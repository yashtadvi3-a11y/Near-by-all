NearbyApp - Auto-build via GitHub Actions
========================================

This Android project is prepared to be built automatically by GitHub Actions (assembleDebug).
Steps for you:

1. Create a new GitHub repository (public) and push all files from this project into it.
2. In GitHub, go to Actions -> the workflow will run automatically on push to main.
3. After Actions completes, open the workflow run and download the artifact named app-debug.apk.
4. Install the APK on your Android device (allow unknown sources if needed).

Notes:
- Replace the Google Maps API key in app/src/main/AndroidManifest.xml before building if you want map features.
- This project is a starter; the chat/P2P features are simplified for demo.
