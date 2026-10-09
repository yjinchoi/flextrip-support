---
lang: en
title: Privacy Policy
permalink: /en/privacy/
alt: /privacy/
description: What information the FlexTrip app stores, where it is stored, and who receives it.
---
# Privacy Policy

<p class="meta">Effective date: October 9, 2026</p>

FlexTrip ("the app") stores your travel plans **on your device**. The developer does not offer accounts and does not run any server that receives or keeps your information. This policy explains what information the app handles and where it goes depending on the features you choose to use.

## 1. Information the developer collects
The developer does not collect your personal information. The app contains no advertising, analytics, tracking, or crash-reporting tools.

## 2. Information stored on your device
The following information you enter or choose is stored only in the app's storage on your device:

- Trips: title, dates, number of travelers, start and end places, daily plans and visit order, transport modes, costs and currencies, notes
- Places: name, coordinates, address, type, time zone, notes
- Photos you attach to places
- App settings (theme, default currency, default directions app, and so on)

## 3. Information shared when you use certain features

| Feature | Information shared | Recipient |
| --- | --- | --- |
| Place search and dropping a pin (iOS) | Search text, visible map area, coordinates of the pin | Apple (Maps, MapKit) |
| Place search and dropping a pin (Android) | Search text, coordinates of the pin | The device's location services (Google) |
| Map display (Android) | Visible map area | Google Maps SDK |
| Cloud backup, restore, and export | Backup files (the trip and place data in section 2) and exported files | The Google Drive, Dropbox, or iCloud account you connect |
| External directions | Names and coordinates of the start and destination, transport mode | The map or navigation app you choose (Naver Map, KakaoMap, TMAP, Google Maps, Apple Maps) |
| Sharing files | The files you choose | The app you choose in the share sheet |
| Receiving a place shared from another map app | If the shared link is a short link (maps.app.goo.gl, naver.me, kko.to, and so on), the link address, to find the place's location | The link server of the map company that made the link (Google, NAVER, Kakao, Apple) |

When you receive a place shared from another map app, its name, address, and location are stored on your device only when you save it in the place form. The app sends only the link address to the short-link server and reads only the original map address that the server returns.

This information is shared only when you use the feature, and the recipient's privacy policy applies. The developer does not receive or see this information.

## 4. Connecting cloud accounts
- **Google Drive**: The app requests only the `drive.file` scope. It can access only files the app created (backups and exports in the FlexTrip folder) and cannot see your other Drive files.
- **Dropbox**: The app can access only its own app folder (`Apps/FlexTrip`). Your account name and email are used only to show which account is connected.
- **iCloud** (iOS): The app uses the FlexTrip folder in your iCloud Drive.
- Sign-in happens in your device's system browser; the app never receives your password. Access tokens are kept only in the device's secure storage (iOS Keychain, Android Keystore).
- When you disconnect an account in Settings, the app revokes the token and deletes it from the device. Backup files already uploaded remain in your cloud account, and you can delete them yourself.

FlexTrip's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google user data is used only to provide backup, restore, and export, and is never used for advertising or transferred to others.

## 5. Device permissions
- **Photo library and camera** (optional): requested only when you attach a photo to a place.
- **Location**: The app does not request device location permission. "Start from current location" in directions is handled by the directions app itself.

## 6. Retention and deletion
- Data on your device stays until you delete it. Using **Settings › Storage › Reset data** or deleting the app removes it from your device.
- You can delete cloud backup files directly in your cloud account.

## 7. Sale and sharing with third parties
The developer does not sell your information or provide it to third parties.

## 8. Children
The app is not directed at children, and the developer does not collect information from children.

## 9. Changes to this policy
If this policy changes, the updated version will be posted on this page with a new effective date.

## 10. Contact
For privacy questions, email [flextrip-support@googlegroups.com](mailto:flextrip-support@googlegroups.com). For other questions, see the [Support page]({{ '/en/support/' | relative_url }}).
