# Turtlefin for Android

Official Android downloads and installation instructions. This repository contains distribution files only—not Turtlefin development source, signing keys, account credentials or pairing tokens.

## Current status

**Phone-testing release is being prepared. No APK has been published here yet.** Secure physical-phone pairing and LAN playback still need implementation and testing. Do not treat the current build as a finished phone release.

## Install on your phone

1. When a release is available, open **Releases** and download `turtlefin-android.apk`.
2. Requires **Android 8.0 or newer**. Keep your phone and Turtlefin PC on the same Wi-Fi.
3. If Android asks, allow the browser to install this trusted APK, then restore that permission afterward. Do not bypass Play Protect or security warnings.
4. Open Turtlefin. When the phone-pairing workflow is available, choose **Connect to Turtlefin PC**. On your PC choose **Devices → Add New Device**, scan the private pairing QR and approve the phone on the PC.

The public download link and the private pairing QR serve different purposes. Never share a pairing QR publicly.

## Safety and updates

- Only install APKs attached to releases in this repository.
- Verify the release SHA-256 checksum when provided.
- Debug and release builds have different signing certificates and cannot update one another. Do not uninstall a working app without considering saved pairing data.
- The PC performs subtitle downloads and translation; Android is the client.
