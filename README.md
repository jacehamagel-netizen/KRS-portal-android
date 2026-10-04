# KRS Portal – Android app (APK)
Wraps the live portal (https://krs-student-portal.web.app) in a native Android app using Capacitor.
Portal updates appear automatically; you only rebuild the APK to change the app itself (icon, name, settings).

## Build with GitHub (no Android Studio needed)
1. Create a GitHub repository, upload everything in this folder (keep the `.github` folder; do NOT upload node_modules).
2. Actions tab -> **Build Android APK** -> Run workflow.
3. After ~5-8 minutes download **KRS-Portal-Android** (zip) -> `KRS-Portal.apk`.

## Install on a phone
1. Send `KRS-Portal.apk` to the phone (WhatsApp as document, Drive link, USB).
2. Tap it. Android asks to allow "Install unknown apps" for that app -> allow.
3. Tap Install, then Open.

Notes: this is a debug-signed APK, fine for installing directly on school/staff/parent phones. Google Play needs a
release-signed bundle and a developer account.
