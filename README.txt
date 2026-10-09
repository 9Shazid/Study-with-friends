STUDY WITH FRIENDS - Android APK project

GET THE APK (no Android Studio needed)
1. Create a free GitHub account and a new repository.
2. Upload ALL files of this folder (including the hidden .github folder). Easiest: unzip, open the repo page, drag the folder CONTENTS in.
3. Open the repo > Actions tab > "Build APK" > Run workflow. Takes about 5 minutes.
4. Open the finished run > Artifacts > download "study-with-friends-apk" > unzip > study-with-friends.apk
5. Share the .apk by Google Drive/WhatsApp. On the phone: open it, allow "Install unknown apps" for that app (Drive/Files/Chrome), install.

If the run fails, open the failed step, copy the red error text and send it to me.

BUILD LOCALLY: Node 20 + JDK 17 + Android SDK, then
  npm install && npx cap add android && npx cap sync android
  cd android && ./gradlew assembleDebug
  APK: android/app/build/outputs/apk/debug/app-debug.apk

NOTE: this APK is the offline app (timer, journal, stats, backup). Group chat, video call and invite codes run in the Claude-hosted page.
