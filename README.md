# RX Study Mod Android APK wrapper

This repository contains an Android WebView wrapper for the existing RX Study Mod website. The original `Rx-study-mod` repository is not modified by this project.

## Website
The app opens the existing Vercel deployment at `https://rx-study-mod-lvgc.vercel.app`. Website features and behavior remain in the website project; this Android wrapper adds native file picking, downloads, and Android back navigation.

## Build APK
1. Open the **Actions** tab in this repository.
2. Select **Build RX Study Mod APK**.
3. Press **Run workflow** (or wait for the workflow to run after a source change).
4. Open the completed workflow run and download the `RX-Study-Mod-debug-APK` artifact.
5. Extract the ZIP and install `app-debug.apk` on your Android phone. Android may ask you to allow installation from the browser/file manager.

This is a debug APK for personal testing, not a signed Play Store release.

## Important
The website must remain deployed and reachable for the app to work. This wrapper does not reimplement server-side AI/API features or make them work offline. Features that depend on the website's APIs still depend on those services being available.
