# TextLift Privacy Policy

**Effective date: 12 July 2026**

TextLift is built around one rule: what is on your screen stays on your device.

## 1. What TextLift does

TextLift reads visible text from your current screen — using Android's accessibility API, or by reading an image with on-device text recognition (OCR) — so you can copy, share, edit, or translate it. Every capture happens only when you explicitly trigger it (notification shortcut, Quick Settings tile, an in-app button, or by sharing an image into TextLift).

## 2. Data we collect

None. TextLift has no user accounts, no analytics, no advertising SDKs, and no servers of its own. We do not collect, store, sell, or share any personal data.

## 3. Captured screen text and images

Text captured from your screen and images you share into TextLift are processed entirely on your device, in memory. They are never written to storage, never logged, and never transmitted anywhere. Captured text leaves the app only when you explicitly copy it to the clipboard, share it, edit it, or send it to a translator app — all actions you initiate.

Screen reading with OCR takes a single screenshot frame, recognizes the text on the device, and immediately discards the image.

Text recognition uses Google's ML Kit with a bundled on-device model; recognition does not use the network.

## 4. Accessibility API

TextLift uses Android's accessibility API to read visible text from the current screen only after you trigger capture. This is used to help you copy, share, or edit text from apps and screens where normal text selection is unavailable. TextLift does not read your screen in the background, does not store captured text by default, and does not send captured screen text to our servers.

## 5. Diagnostics

To help you keep the capture shortcut working, TextLift stores a short local history of technical event codes and timestamps (for example "ServiceConnected" or "CaptureTimeout"). This history never contains screen text, screenshots, or anything you captured. It stays on your device unless you explicitly use "Share diagnostic summary".

## 6. Permissions

- **Accessibility**: read visible screen text on your explicit trigger (see section 4).
- **Notifications**: show the optional "Tap to lift text" shortcut and rare reliability alerts.
- No storage permission is used: images are opened through the system photo picker or share sheet.

## 7. Clipboard

Text you copy is placed on the Android clipboard, which is managed by the system and may be visible to other apps you use, per Android's clipboard rules. An optional setting can clear the clipboard automatically after a delay.

## 8. Data retention and deletion

TextLift keeps no captured content, so there is nothing to delete on our side. Settings and the diagnostic event history are stored locally and are removed when you clear the app's data or uninstall it.

## 9. Children

TextLift is a general-purpose utility and is not directed at children under 13.

## 10. Changes

If this policy changes, the updated version will be published at the same address and the effective date above will change.

## 11. Contact

Questions about this policy: support.aptitudedigital@gmail.com
