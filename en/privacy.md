---
lang: en
title: Privacy Policy
permalink: /en/privacy/
alt: /privacy/
description: What information the FlexTrip app stores, where it is stored, and who receives it.
---
# Privacy Policy

<p class="meta">Effective date: October 19, 2026</p>

FlexTrip ("the app") stores your travel plans **on your device**. The developer does not offer accounts and does not run any server that receives or keeps your information. This policy explains what information the app handles and where it goes depending on the features you choose to use.

## 1. Information the developer collects
The developer does not collect your personal information. The app contains no analytics tools, and its only advertising is Google AdMob as described in "Ads" below. The only information the developer receives directly is the "Error reports" described below. Error reports are diagnostic information for fixing the app, designed not to contain anything that identifies you.

### Error reports
If the app hits an error or closes unexpectedly, it asks you "Send an error report?" and sends one only if you choose Send (the default setting is "Ask on error"). If you choose "Always send" in **Settings › Error reports**, reports are sent without asking. Before sending, "Show what will be sent" shows the exact report, and choosing "Don't send" deletes that report from your device. Error reports are not linked to any account or unique device identifier and are never used for advertising or tracking.

- **What is sent**: app version and build number, operating system and version, device type (for example iPhone, iPad, or an Android device's manufacturer and model), the error's name, message, and location (function names and line numbers in the app's code), the kind of screen where it happened (for example trip details), and when it happened.
- **What is never sent**: trip or place names, addresses, coordinates, notes, photos, search text, email addresses or phone numbers, device name, advertising identifiers, or cloud account information. Because error messages can contain such text, the app removes quoted text, links, email addresses, coordinate-like numbers, and long numbers before sending.
- **Recipient**: The report is stored as an issue in the developer's private GitHub repository (operated by GitHub, Inc.), visible only to the developer. GitHub's [Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) applies. As with any internet connection, GitHub's servers may receive your device's IP address, but the IP address is not part of the report and the developer never receives or sees it.
- **Purpose and retention**: Reports are used only to find and fix errors. Reports are deleted once the cause is fixed, and in any case within one year of receipt.

### Ads
All features of the app are free. There are no ads for the first 3 months after installation; after that, a full-screen ad appears once only right before you share a trip or place file (never for backups or error reports). Ads are shown by Google AdMob, and Google may receive your device's advertising identifier (on iOS only if you allow "Allow Tracking"), an approximate location estimated from your IP address, ad impression and click information, and ad SDK interaction and performance diagnostics. Trip and place content is never passed to ads.
- When an ad is first needed, Google's consent form (UMP) appears where required, and on iOS the app then asks "Allow Tracking". If you don't allow it, only non-personalized ads are shown. You can change this anytime in **Settings › Remove ads › Ad privacy settings**.
- Google's [Privacy Policy](https://policies.google.com/privacy) and [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites) apply.

### Remove-ads purchase
In **Settings › Remove ads** you can buy a subscription (monthly or yearly, auto-renewing) or a lifetime pass to remove ads. Payment is handled by the Apple App Store or Google Play, and the developer never receives your payment information. The app only checks what you bought (product and expiry) on the device. On iPhone and iPad, the free-trial start date and remove-ads status are shared through the device keychain with the developer's other travel apps (Trip Route and Trip Photo); this never leaves the device.

## 2. Information stored on your device
The following information you enter or choose is stored only in the app's storage on your device:

- Trips: title, dates, number of travelers, start and end places, daily plans and visit order, transport modes, costs and currencies, notes
- Places: name, coordinates, address, type, time zone, notes
- Photos you attach to places
- App settings (theme, default currency, error report setting, and so on)
- Error reports not yet sent (up to 5, deleted after 7 days)
- Diagnostic log: numbers such as screen positions and scroll heights, plus state names (the most recent 3,000 lines). It contains no trip or place content and leaves your device only when you share it yourself from **Settings › Send diagnostic log**.

## 3. Information shared when you use certain features

| Feature | Information shared | Recipient |
| --- | --- | --- |
| Place search, dropping a pin, and fetching an address (iOS) | Search text, visible map area, coordinates of the pin or place | Apple (Maps, MapKit) |
| Showing the Apple Maps place card (iOS 18 or later) | The place's Apple Maps identifier | Apple (Maps) |
| Place search, dropping a pin, and fetching an address (Android) | Search text, coordinates of the pin or place | The device's location services (Google) |
| Map display (Android) | Visible map area | Google Maps SDK |
| Cloud backup, restore, and export | Backup files (the trip and place data in section 2) and exported files | The Google Drive, Dropbox, or iCloud account you connect |
| iCloud sync across devices (iOS, if turned on) | The trip and place data in section 2 | The private database of your iCloud account (Apple CloudKit) |
| External directions | Names and coordinates of the start and destination, transport mode | The map or navigation app you choose (Naver Map, KakaoMap, TMAP, Google Maps, Apple Maps) |
| Sharing files | The files you choose | The app you choose in the share sheet |
| Error reports (section 1) | The error report | The developer's private GitHub repository (GitHub, Inc.) |
| Travel product links (see "Affiliate links" below) | The search conditions in the link you tap (for example city and dates) | The affiliate platform Travelpayouts (Travelspark Limited) and the selling site |
| Receiving a place shared from another map app | If the shared link is a short link (maps.app.goo.gl, naver.me, kko.to, and so on), the link address, to find the place's location | The link server of the map company that made the link (Google, NAVER, Kakao, Apple) |

When you receive a place shared from another map app, its name, address, and location are stored on your device only when you save it in the place form. The app sends only the link address to the short-link server and reads only the original map address that the server returns.

### Affiliate links
Some links to selling sites, such as in finding stays and flights, finding tickets and tours, and checklist suggestions, are affiliate links. When you tap one, your device's browser goes to the selling site through Travelpayouts, and if you book there, the selling site pays the developer a small commission (the price is the same). The link contains only fixed values for the developer's affiliate account and the link's location in the app (for example, finding stays) and the search conditions you are looking for (city, dates, and so on); it never contains values that identify you or your device. After you leave the app, the privacy policies of Travelpayouts and the selling site apply. Turning off **Settings › Show travel product suggestions** hides affiliate links.

This information is shared only when you use the feature, and the recipient's privacy policy applies. Apart from error reports, the developer does not receive or see this information.

## 4. Connecting cloud accounts
- **Google Drive**: The app requests only the `drive.file` scope. It can access only files the app created (backups and exports in the FlexTrip folder) and cannot see your other Drive files.
- **Dropbox**: The app can access only its own app folder (`Apps/FlexTrip`). Your account name and email are used only to show which account is connected.
- **iCloud** (iOS): Backups use the FlexTrip folder in your iCloud Drive. If you turn on sync across devices, trip and place data syncs to the private database of your iCloud account (CloudKit), which the developer cannot access. Turning it off in Settings stops syncing.
- Sign-in happens in your device's system browser; the app never receives your password. Access tokens are kept only in the device's secure storage (iOS Keychain, Android Keystore).
- When you disconnect an account in Settings, the app revokes the token and deletes it from the device. Backup files already uploaded remain in your cloud account, and you can delete them yourself.

FlexTrip's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google user data is used only to provide backup, restore, and export, and is never used for advertising or transferred to others.

## 5. Device permissions
- **Photo library and camera** (optional): requested only when you attach a photo to a place.
- **Allow Tracking** (iOS, optional): asked once when an ad is first needed after the free trial (see "Ads" above).
- **Location**: The app does not request device location permission. "Start from current location" in directions is handled by the directions app itself.

## 6. Retention and deletion
- Data on your device stays until you delete it. Using **Settings › Storage › Reset data** or deleting the app removes it from your device.
- You can delete cloud backup files directly in your cloud account.

## 7. Sale and sharing with third parties
The developer does not sell your information. Apart from Google AdMob receiving the information described in "Ads" to show ads, it is not provided to third parties. Error reports are only stored in the developer's GitHub repository and are not passed on to anyone else.

## 8. Children
The app is not directed at children, and the developer does not collect information from children.

## 9. Changes to this policy
If this policy changes, the updated version will be posted on this page with a new effective date.

## 10. This website (flex-trip.net)
Sections 1–9 of this policy cover the app. This website includes a script (Drive) from the travel affiliate platform **Travelpayouts** (Travelspark Limited). The script places affiliate links to travel products on pages and, to count clicks and bookings made through those links, may use cookies and pass browser information (such as IP address, browser type, and pages visited) to Travelpayouts and its partner brands. If you book through such a link, the developer may receive a commission; the price you pay does not change. Travelpayouts' [Privacy Policy](https://support.travelpayouts.com/hc/en-us/articles/360004121052) applies. Blocking cookies or scripts in your browser disables this feature without affecting the rest of the website. The app does not use this script (for affiliate links in the app, see "Affiliate links" in section 3).

## 11. Contact
For privacy questions, email [flextrip-support@googlegroups.com](mailto:flextrip-support@googlegroups.com). For other questions, see the [Support page]({{ '/en/support/' | relative_url }}).
