# WC Kickoff 2026 — Privacy Policy

Last updated: June 19, 2026

This Privacy Policy describes how the WC Kickoff 2026 mobile application ("the app", "we", "us") handles information. By using the app you agree to the practices described below.

## 1. Information we DO NOT collect

The app does not collect, store, or transmit any personal information about you. Specifically, we do not collect:

- Your name, email address, phone number, or any other contact information.
- Your precise or approximate location.
- Your device identifiers (IMEI, advertising ID, etc.).
- Your contacts, calendar, photos, microphone, camera, files, or any other on-device data.
- Crash reports, analytics events, or usage telemetry.
- Account credentials of any kind. The app has no accounts and no login.

## 2. Information stored only on your device

The following preferences are stored locally on your device using the operating system's standard storage. They never leave your device:

- Your selected language (English, French, or Arabic).
- Your selected theme (light, dark, or system).
- Your selected text size.
- Your selected time zone.
- Your selected favorite country (used to filter matches and reminders).
- Your notification preferences (pre-game reminders on/off, live notifications on/off, reminder lead time, scope).
- A cached copy of the public match fixtures and standings list, downloaded from the data source described below.
- Cached PNG images of country flags, downloaded from the source described below.

You can clear all of this at any time by uninstalling the app or clearing its storage from your device's system Settings.

## 3. Third-party services the app contacts

The app makes outbound HTTPS requests to the following third-party services. None of these requests include any personal information about you — only generic, anonymous requests for public data:

- football-data.org — to fetch the public WC Kickoff 2026 fixtures, scores, and standings. See https://www.football-data.org/privacy for their policy.
- flagcdn.com — to fetch public country flag images. See https://flagcdn.com for their terms.
- fonts.gstatic.com (Google Fonts) — to fetch the open-source typefaces used by the app's UI. See https://policies.google.com/privacy for their policy.

These services may log standard request metadata (IP address, timestamp, user agent) as part of normal web server operation. We do not receive or process those logs.

## 4. Notifications

If you enable notifications, the app uses your device's local notification system to:

- Schedule pre-kickoff reminders for matches you have opted in to. These reminders are scheduled and delivered entirely on-device using Android's inexact AlarmManager API.
- Show a live notification while a match is in progress, updated by an on-device background worker.

No notification content is sent to or processed by any external server. We do not use push notifications.

## 5. Permissions the app requests

- POST_NOTIFICATIONS (Android 13+) — required to show match reminders and live score notifications. Granted by you at the moment you enable a notification feature.
- RECEIVE_BOOT_COMPLETED — used to re-register your scheduled reminders after a device reboot, so they still fire on time.
- WAKE_LOCK and VIBRATE — used briefly while displaying a notification.
- INTERNET — required to fetch match data and flag images from the third-party services listed above.

The app does NOT request: location, contacts, calendar, microphone, camera, storage, SMS, phone, exact alarm, or any other sensitive permission.

## 6. Children

The app is suitable for general audiences and does not knowingly collect any information from anyone, including children under the age of 13.

## 7. Changes to this policy

If we update this Privacy Policy, the new version will be shipped with the next app update and the "Last updated" date at the top will change. Continued use of the app after an update constitutes acceptance of the updated policy.

## 8. Contact

Questions about this Privacy Policy can be sent to the developer through the Google Play Store listing's "Contact developer" link.
