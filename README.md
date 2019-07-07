## :arrow_up: How to Setup

**Step 1:** git clone this repo:

**Step 2:** cd to the cloned repo:

**Step 3:** Install the Application with `npm install`

**Step 4:** Create file local.properties and copy to folder android with content :
# Location of the SDK. This is only used by Gradle.
ndk.dir=C\:\\Users\\Admin\\AppData\\Local\\Android\\Sdk\\ndk-bundle
sdk.dir=C\:\\Users\\Admin\\AppData\\Local\\Android\\Sdk

## :arrow_forward: How to Run App

1. cd to the repo
2. Run Build for either OS
  * for iOS
    * run `react-native run-ios`
  * for Android
    * Run Genymotion
    * run `react-native run-android`
3. Run on android real device
Follow on doc: https://facebook.github.io/react-native/docs/running-on-device
or copy file .apk in folder .\android\app\build\outputs\apk\debug
## :arrow_forward: Noted
If running for the first time an error occurred, at the next run:
cd android && .\gradlew clean && cd .. && react-native run-android
