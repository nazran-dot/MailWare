# MailWare

Email Phishing Detection System  
Stay Alert. Stay Safe.

MailWare is a student project for rule-based email phishing detection and cybersecurity awareness on Android and Windows. Phishing scores use explicit rules, not machine learning. Screenshot text extraction uses on-device OCR (Google ML Kit on Android and Tesseract on Windows).

## Downloads

Open the [latest release](https://github.com/nazran-dot/MailWare/releases/latest), then choose:

- **MailWare-Android.apk** — Android 8.0 or newer. This is an FYP demonstration build, signed with the project's existing development certificate.
- **MailWare-Windows.zip** — Windows x64. Extract the entire ZIP and run `MailWare/MailWare.exe`. Keep the app and runtime folders together; Java is bundled.

## Updates

The latest-release link stays the same and can be used for a QR code. Download the latest file again when a new version is available. Updates are installed manually, not automatically. On Android, install over the existing app to keep its data; do not uninstall first. On Windows, close the app before running the new extracted version.

## Privacy and limitations

Detection and OCR run on the device. Optional Google sign-in uses Firebase to sync learning progress and, if enabled, text scan history. Screenshot images are not uploaded by the history-sync feature. Clearing local data does not delete existing cloud copies. A low risk score does not guarantee that an email is safe. The detector does not open links or inspect attachments.

This repository hosts app downloads and release notes. It does not contain user databases or private signing keys.
