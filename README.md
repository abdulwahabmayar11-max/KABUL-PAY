# Kabul Pay Android

Native Android Java starter app for mobile/GitHub builds.

## Build APK
1. Upload/commit these files to the root of your GitHub repository.
2. Open **Actions** and choose **Build Kabul Pay Android APK**.
3. Wait for a green run.
4. Download the `Kabul-Pay-APK` artifact ZIP and extract `app-debug.apk`.

## Important limitations
- This is a local demo prototype.
- Login/profile/history are stored locally on the device; local demo login is not secure authentication.
- Transfers only change demo balance on this device. No real money moves.
- Admin is informational/demo only.
- Before any real financial use, integrate a secure backend, identity verification, fraud controls, audit logging, and a licensed payment provider. Do not collect bank passwords or OTPs in this prototype.
