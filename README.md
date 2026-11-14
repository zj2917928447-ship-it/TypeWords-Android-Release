# TypeWords Android

Independent Android adaptation of [TypeWords](https://github.com/zyronon/TypeWords). This is not an official upstream release.

## Download

The latest stable Android APK and the corresponding complete GPL source archive are published as assets in [GitHub Releases](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/latest).

- APK: `TypeWords-Android.apk`
- APK SHA-256: `TypeWords-Android.apk.sha256`
- Complete corresponding source: `TypeWords-Android-source.zip`
- Source SHA-256: `TypeWords-Android-source.zip.sha256`

## v1.8.1

- Android package: `cc.typewords.android`
- versionName: `1.8.1`
- versionCode: `19`
- Offline English word and article practice.
- Existing FSRS scheduling and review history preserved.
- ZIP backup import uses bounded streaming decompression, CRC32 validation, strict path checks and atomic IndexedDB restoration.

See the v1.8.1 release notes and the complete corresponding source archive attached to the release. The source archive includes the local security patches and third-party license notices.

## Build and license

This project is based on the upstream [zyronon/TypeWords](https://github.com/zyronon/TypeWords) project and is distributed under GNU GPL v3. This is an independent modification and is not endorsed by upstream maintainers. Third-party components retain their respective licenses; see the source archive.

Before upgrading an existing installation, export and verify a ZIP backup. In-place installation requires the same package name and signing certificate.
