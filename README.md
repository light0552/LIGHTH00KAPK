# LIGHTH00K - Android APK

Official signed Android app for the LIGHTH00K private cinema.

## Latest release: 2.1.0

Download the APK from [Releases](https://github.com/light0552/LIGHTH00KAPK/releases/latest).

- Android 8+ (`minSdk 26`), `targetSdk 34`
- `arm64-v8a` / `armeabi-v7a` / `x86_64`
- Signed with the same LIGHTH00K key as 1.0.x / 2.0.0 (installs in place)
- Brave `adblock-rust` + uBlock Origin / EasyList / EasyPrivacy
- Loads the live site at https://lighthook.netlify.app

The website updates automatically. The APK is the native shell: update it when the native theme, launch flow, pull-to-refresh or update gate changes.

## 2.1.0

- **Pull down to refresh** at the top of the page. The three-finger menu is gone.
- **Blocking update gate:** when a newer APK is published, older builds show "A newer LIGHTH00K app is required. Contact the admin for the updated APK link." Only Close app; no web access.
- **No cat-only splash:** tapping opens the cat-seal Loading Private Cinema screen; the loading screen returns on reopen.
- Includes the live RECODE web app (seasons, screen expiry, provider refresh, neon avatars).

## Update manifest

`version.json` in this repository is read by the app at launch. It must be updated with every APK release; 2.1.0 runs on versionCode 7.

## Install

Use the APK attached to the latest release. Allow "Install unknown apps" when Android asks, then install over an older LIGHTH00K release.
