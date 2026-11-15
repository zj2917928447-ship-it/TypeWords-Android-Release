# TypeWords Android

Independent Android adaptation of [TypeWords](https://github.com/zyronon/TypeWords). This is not an official upstream release.

## Download

The latest stable Android APK and its complete corresponding GPL source archive are published in [GitHub Releases](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/latest).

### v1.9.5

- **Android APK:** [TypeWords-Android-v1.9.5.apk](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.5/TypeWords-Android-v1.9.5.apk)
- **APK SHA-256:** [TypeWords-Android-v1.9.5.apk.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.5/TypeWords-Android-v1.9.5.apk.sha256)
- **Complete corresponding GPL source:** [TypeWords-Android-v1.9.5-source.zip](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.5/TypeWords-Android-v1.9.5-source.zip)
- **Source SHA-256:** [TypeWords-Android-v1.9.5-source.zip.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.5/TypeWords-Android-v1.9.5-source.zip.sha256)

Android package: `cc.typewords.android`  
versionName: `1.9.5`  
versionCode: `25`  
Minimum Android: 6.0

APK SHA-256: `ce285c09164f9a4fe20a62f04a24cc8e8920b0888793c1ad9e0f36acaa248115`  
Source ZIP SHA-256: `acb8ed5a984b94797b48a5b0d09cbec2f234b16a2dc184eef4e83da6ee807932`

### Release highlights

- Preserves the FSRS-6 scheduler, existing review history, IndexedDB learning data and ZIP backup/restore format.
- Adds an offline US IPA overlay for 14,382 bundled headwords, locale-aware phonetic display and optional phoneme / stress hints.
- Hardens PWA offline caching: query-bearing root URLs are not cached, core app shell entries survive the 400-item cache cap, and online deep-link 404s fall back to the SPA shell.
- Keeps the Android app as an independent adaptation; this is not an official upstream release.


### v1.9.5 highlights

- Adds real per-key accuracy, a QWERTY heatmap, slow-bigram analysis and adaptive weak-key practice.
- Keeps typing aggregates optional and bounded (90 days / 5,000 summaries); FSRS-6 grades, parameters and due dates are unchanged.
- Node tests: 162 passed. Android Release lint, APK alignment/signature and asset-integrity checks passed.
- Public GitHub Release: [v1.9.5](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/tag/v1.9.5).

## Upgrade safely

Before upgrading an existing installation, export and verify an in-app ZIP backup. In-place installation requires the same package name and signing certificate. If Android reports a signature mismatch or refuses an update, stop; do not uninstall the old app or clear its data.

## Build and license

This project is based on the upstream [zyronon/TypeWords](https://github.com/zyronon/TypeWords) project and is distributed under GNU GPL v3. This is an independent modification and is not endorsed by upstream maintainers. Third-party components retain their respective licenses; see the complete corresponding source archive.
