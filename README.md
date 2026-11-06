# HardStop for Android: signed builds

This repo holds the signed HardStop for Android builds (APK files). The HardStop desktop apps download them from here. There is no source code in this repo.

Each build is published by the HardStop android-app CI. Don't upload builds by hand.

## What is published

- A release for each build, named after its tag. It has the APK, a `SHA256SUMS` file and an `android-app.json` file.
- `rc` is a rolling pre-release. It always holds the `android-app.json` for the newest release candidate.

## Manifest addresses

- Live build: https://github.com/tryhardstop/android-releases/releases/latest/download/android-app.json
- Release candidate: https://github.com/tryhardstop/android-releases/releases/download/rc/android-app.json

Each manifest lists the channel, package, version name, version code, the APK address and the APK SHA-256.