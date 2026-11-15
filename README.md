# TypeWords Android

Independent Android adaptation of [TypeWords](https://github.com/zyronon/TypeWords). This is not an official upstream release.

## Download

The latest stable Android APK and its complete corresponding GPL source archive are published in [GitHub Releases](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/latest).

### v1.9.4

- **Android APK:** [TypeWords-Android-v1.9.4.apk](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.4/TypeWords-Android-v1.9.4.apk)
- **APK SHA-256:** [TypeWords-Android-v1.9.4.apk.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.4/TypeWords-Android-v1.9.4.apk.sha256)
- **Complete corresponding GPL source:** [TypeWords-Android-v1.9.4-source.zip](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.4/TypeWords-Android-v1.9.4-source.zip)
- **Source SHA-256:** [TypeWords-Android-v1.9.4-source.zip.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.4/TypeWords-Android-v1.9.4-source.zip.sha256)

Android package: `cc.typewords.android`  
versionName: `1.9.4`  
versionCode: `24`  
Minimum Android: 6.0

APK SHA-256: `e38f9b9d5f0423a9a92d4b9fb03c68b3df2fad95bf4e26c968719a1583bde1bd`  
Source ZIP SHA-256: `4932e58285764a0819f42ec2af774d9e274f57c60feaaf0db2b28c60f7a2d91d`

### Release highlights

- Preserves the FSRS-6 scheduler, existing review history, IndexedDB learning data and ZIP backup/restore format.
- Adds an offline US IPA overlay for 14,382 bundled headwords, locale-aware phonetic display and optional phoneme / stress hints.
- Hardens PWA offline caching: query-bearing root URLs are not cached, core app shell entries survive the 400-item cache cap, and online deep-link 404s fall back to the SPA shell.
- Keeps the Android app as an independent adaptation; this is not an official upstream release.

## Upgrade safely

Before upgrading an existing installation, export and verify an in-app ZIP backup. In-place installation requires the same package name and signing certificate. If Android reports a signature mismatch or refuses an update, stop; do not uninstall the old app or clear its data.

## Build and license

This project is based on the upstream [zyronon/TypeWords](https://github.com/zyronon/TypeWords) project and is distributed under GNU GPL v3. This is an independent modification and is not endorsed by upstream maintainers. Third-party components retain their respective licenses; see the complete corresponding source archive.
