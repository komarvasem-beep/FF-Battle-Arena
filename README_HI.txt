FF BATTLE ARENA — ANDROID APK PROJECT

This ZIP contains the app source and GitHub Actions workflow for building a test/debug Android APK.

IMPORTANT: Extract this ZIP first. Upload the project files/folders to the ROOT of your GitHub repository. Do not upload only README_HI.txt.

FILES INCLUDED:
- package.json
- capacitor.config.json
- www/ (the app's web files)
- .github/workflows/build-apk.yml (automatic Android APK build)
- README_HI.txt

BUILD STEPS:
1. Extract this ZIP on your phone or computer.
2. In your GitHub repository, choose Add file > Upload files.
3. Upload package.json and capacitor.config.json, plus the www and .github folders. Keep the folder structure exactly as shown.
4. Commit the files to the main branch.
5. Open the Actions tab and select “Build Free Android APK”.
6. Tap “Run workflow” if it has not started automatically.
7. When the run completes successfully, open it and download the “FF-Battle-Arena-APK” artifact.
8. Extract that artifact ZIP and install app-debug.apk on your Android device.

APP FEATURES:
- Tournament categories: Solo, Duo, Squad and 1v1
- Player profile and UID entry
- Tournament registration
- Admin-created tournaments and result entry
- Leaderboard based on entered results

LIMITATIONS:
- This is a debug/test APK build, not a Play Store release.
- Data is stored locally on each device. Different players' phones do not sync registrations yet.
- Admin PIN 2468 is a demo-only lock and is not secure. Do not use it to protect money or private data.
- No paid entry, betting, gambling, or cash-withdrawal feature is included.
- Unofficial fan project; not affiliated with Garena or Free Fire.
