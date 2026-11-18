# EngiCalc – Android

Fully offline (no CDN). Three ways to get it on your phone:

1. Easiest, no build: host the www/ folder on any HTTPS site (e.g. GitHub Pages), open it in Chrome on Android -> menu -> Install app.
2. APK via GitHub (no Android Studio): push this folder to a new GitHub repo, open Actions -> Build Android APK -> Run workflow, then download the EngiCalc-apk artifact.
3. APK locally: install Node 20 + Android Studio, then
   npm install && npx cap add android && npx cap sync android && npx cap open android
   and use Build -> Build APK(s).
