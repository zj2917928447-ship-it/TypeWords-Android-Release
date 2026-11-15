# TypeWords Android

Independent Android adaptation of [TypeWords](https://github.com/zyronon/TypeWords). This is not an official upstream release.

## Download

The latest stable Android APK and its complete corresponding GPL source archive are published in [GitHub Releases](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/latest).

### v1.9.3

- **Android APK:** [TypeWords-Android-v1.9.3.apk](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.3/TypeWords-Android-v1.9.3.apk)
- **APK SHA-256:** [TypeWords-Android-v1.9.3.apk.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.3/TypeWords-Android-v1.9.3.apk.sha256)
- **Complete corresponding GPL source:** [TypeWords-Android-v1.9.3-source.zip](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.3/TypeWords-Android-v1.9.3-source.zip)
- **Source SHA-256:** [TypeWords-Android-v1.9.3-source.zip.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.3/TypeWords-Android-v1.9.3-source.zip.sha256)

Android package: `cc.typewords.android`  
versionName: `1.9.3`  
versionCode: `23`  
Minimum Android: 6.0

APK SHA-256: `b89fa39175698022c2a0277b9843a0598859766c38e66c445080d68beb12c5b8`  
Source ZIP SHA-256: `cec2bf75c501ebba74e88e2c17e2cc47abb132ae09d9df7ae214128e509b75fc`

### Release highlights

- Preserves the FSRS-6 scheduler, existing review history, IndexedDB learning data and ZIP backup format.
- Fixes FSRS settings changes not taking effect until the scheduler was recreated.
- Hardens PWA offline caching: no API/auth/deep-navigation HTML caching, bounded 400-item static cache and offline shell fallback.
- Keeps the Android app as an independent adaptation; this is not an official upstream release.

## Upgrade safely

Before upgrading an existing installation, export and verify an in-app ZIP backup. In-place installation requires the same package name and signing certificate. If Android reports a signature mismatch or refuses an update, stop; do not uninstall the old app or clear its data.

## Build and license

This project is based on the upstream [zyronon/TypeWords](https://github.com/zyronon/TypeWords) project and is distributed under GNU GPL v3. This is an independent modification and is not endorsed by upstream maintainers. Third-party components retain their respective licenses; see the complete corresponding source archive.
