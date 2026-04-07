# Privacy Policy for Film Tracker

**Last updated:** April 6, 2026

Film Tracker ("the App") is developed by Steven Rosenblum. This privacy policy explains how the App handles your information.

## Summary

Film Tracker stores all data locally on your device. We do not collect, transmit, or store any personal information on external servers.

## Data Storage

All data you enter into Film Tracker — including film inventory, camera collection, roll history, and settings — is stored exclusively on your device using Apple's SwiftData framework. Your data is protected by iOS file encryption (NSFileProtectionComplete) and is only accessible when your device is unlocked.

## Camera Access

Film Tracker requests camera access solely to scan film barcodes. Camera data is processed on-device in real time and is never recorded, stored, or transmitted.

## Optional Third-Party API Connections

Film Tracker offers optional integrations that you may choose to configure:

- **AI Camera Lookup:** If you provide your own API key for Claude (Anthropic), ChatGPT (OpenAI), or Gemini (Google), the App sends camera model names to the selected provider to retrieve specifications. Only the camera name you search for is sent. No personal data is included in these requests.

- **eBay Price Lookup:** If you enable eBay market value tracking, camera model names are sent to the eBay Browse API to retrieve recent sold prices. No personal data is included in these requests.

API keys you provide are stored securely in the iOS Keychain on your device and are never transmitted to us or any third party other than the respective API provider.

## Biometric Authentication

If you enable Face ID or Touch ID lock, authentication is handled entirely by iOS. Film Tracker never accesses, stores, or transmits biometric data.

## Notifications

Film Tracker may send local notifications for low stock alerts and film expiry warnings if you enable them. These notifications are generated and delivered entirely on your device. No notification data is sent to external servers.

## Data Export

The backup export feature creates a JSON file containing your film and camera data. This file is generated locally and shared only through the iOS share sheet at your discretion. We never receive copies of your backups.

## Analytics and Tracking

Film Tracker does not include any analytics SDKs, advertising frameworks, or tracking mechanisms. We do not collect usage data, crash reports (beyond what Apple provides through App Store Connect), or device information.

## Children's Privacy

Film Tracker does not knowingly collect information from children under 13.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this privacy policy, contact us at:

filmtrackerapphelp@gmail.com
