# TypeWords Android

Independent Android adaptation of [TypeWords](https://github.com/zyronon/TypeWords). This is not an official upstream release.

## Download

The latest stable Android APK and its complete corresponding GPL source archive are published in [GitHub Releases](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/latest).

### v1.9.6 (latest)

- **Android APK:** [TypeWords-Android-v1.9.6.apk](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.6/TypeWords-Android-v1.9.6.apk)
- **APK SHA-256:** [TypeWords-Android-v1.9.6.apk.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.6/TypeWords-Android-v1.9.6.apk.sha256)
- **Complete corresponding GPL source:** [TypeWords-Android-v1.9.6-source.zip](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.6/TypeWords-Android-v1.9.6-source.zip)
- **Source SHA-256:** [TypeWords-Android-v1.9.6-source.zip.sha256](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.6/TypeWords-Android-v1.9.6-source.zip.sha256)
- **Install guide:** [v1.9.6-install-guide.txt](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/download/v1.9.6/v1.9.6-install-guide.txt)
- **Release notes:** [v1.9.6](https://github.com/zj2917928447-ship-it/TypeWords-Android-Release/releases/tag/v1.9.6)

Android package: `cc.typewords.android`  
versionName: `1.9.6`  
versionCode: `26`  
Minimum Android: 6.0

APK SHA-256: `e93302b2cd27083d043e128a039285ff2b76b2c8542f85575f90433ba50ac875`  
Source ZIP SHA-256: `8726cc2a4f42f8bd30badf2f807e3d05adcc1022b832e2d4a9537016abe86215`

### v1.9.6 highlights

- Fixes Android soft-keyboard paths where IME emits InputEvent without a usable keydown, including keyCode 229 / Unidentified.
- Fixes hidden input sentinel reset after keydown/input de-duplication.
- Handles Backspace and Enter InputEvents; rejects multi-character paste, Chinese IME composition commits and whole-word autocorrect as fake single-key events.
- Moves API 27 navigation-bar theme attributes to values-v27 for Android 6.0–8.0 compatibility.
- Preserves FSRS-6, historical review grades, due dates, learning data and ZIP backup format.
- 167 Node tests passed; Playwright Android-UA flows passed at 320 / 393 / 768 / 1440px.
- Android Release lint: 0 errors, 18 warnings. See release notes for known limits and real-device verification status.

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
