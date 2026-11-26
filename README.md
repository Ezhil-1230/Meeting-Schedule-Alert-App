# Meeting Schedule & Alert App

A native **Android (Java)** mobile application built for scheduling meetings, organizing schedules, triggering background alarm reminders, and supporting quick call/SMS actions.

---

## Tech Stack

- **Language & Platform:** Java, Android SDK (`com.example.ezhilcomponent`, `minSdk 8`, `targetSdk 17`)
- **Local Storage:** SQLite
- **Background Alerts:** Android `AlarmManager` & `BroadcastReceiver`
- **Permissions:** `android.permission.SEND_SMS`, `android.permission.CALL_PHONE`

---

## App Modules & Screens

- `MainActivity` (`activity_main.xml`) — Main dashboard navigation
- `Meeting` (`activity_meeting.xml`) — Meeting creation and details
- `Schedule` (`activity_schedule.xml`) — Schedule organizer and lookup
- `Alarm` (`activity_alarm.xml`) — Alarm configuration using `AlarmManager`
- `AlertReceiver` (`activity_alert_receiver.xml`) — `BroadcastReceiver` for scheduled alert delivery
- `Call` (`activity_call.xml`) & `Sms` (`activity_sms.xml`) — Integrated call and SMS utilities

---

## Download & Install (Android APK)

The compiled Android APK is available in [`release/Meeting-Schedule-Alert-App.apk`](release/Meeting-Schedule-Alert-App.apk).

1. Download **`Meeting-Schedule-Alert-App.apk`** onto your Android device.
2. Enable **Install from unknown sources** if prompted.
3. Open the APK file and tap **Install**.

---

## Build Note

This repository preserves the compiled Android package (`classes.dex`, `AndroidManifest.xml`, and XML layout resources).
