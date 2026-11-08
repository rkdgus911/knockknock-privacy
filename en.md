---
title: Knock Knock Privacy Policy
lang: en
---

[한국어](./)

# Knock Knock Privacy Policy

Effective date: 2026-11-08  
Last updated: 2026-11-08

Knock Knock ("the app") is a calendar app that picks reminder times for the events you write down. The app **has no server, no sign-up and no login, and it never sends the events you write to the developer.** This policy explains what information the app handles on your device, and the few cases where information leaves it.

## 1. At a glance

- Your events, types and settings are stored **only on your device**.
- The app sends no information over the internet. The developer cannot see your events.
- The app uses no ads, no analytics and no crash-reporting tools. It does not collect an advertising ID.
- You can export your events and types to a file, or delete all your data, inside the app at any time.

## 2. What the app stores on your device

| Information | Examples | Used for |
| --- | --- | --- |
| Events | Title, date and time, time zone, lunar date, yearly repeat, milestone counting, checklist items and whether they are checked, "Prepared" mark, reminder times, when the event was created | Event list, calendar, reminders |
| Types | Name, color, icon, default reminder times, auto-pick words, prep note, usual checklist items, whether notification details are hidden | Suggesting reminder times when you write an event |
| Settings | Hide notification details, weekly summary on or off, its day and time, whether first run is done | App behavior |
| Scheduling records | IDs and fire times of scheduled reminders, snooze times | Re-scheduling so reminders are not lost |
| Usage counts | How many times each feature was used, and the first and last date (date only, no time). No event content | Kept on the device only (see section 6) |
| Recovery records | How many times the database failed to open, retries that worked, fresh starts, and the date of the last failure. Numbers and dates only | Recovering when the database is damaged |

This information is entered by you or created on your device as you use the app. You can write anything in event titles, checklist items and prep notes, so **they may contain sensitive information such as medical appointments.** The app does not send this content off your device.

The app does not collect your name, phone number, email address, location, contacts, photos, device identifiers or advertising ID.

## 3. Why the information is used

Information on your device is used only to:
- show your events and fire reminders at the times you set
- suggest reminder times and checklist items based on the event type
- build the weekly summary "This week on Knock Knock"
- show a recovery screen when the database is damaged

## 4. What reminders show

Reminders can appear on your lock screen, in the notification center, and on a connected watch or car display. A reminder may include:
- the event title
- up to 3 remaining checklist items
- the type's prep note (early reminders only)
- a milestone name (for example "100 days" or "3rd anniversary")
- the weekly summary: up to 3 event titles for the next 7 days, weekdays, milestone names, whether checklist items are left, and how many more events there are

People who can see your phone, and other apps you allowed to read notifications, may see this content. To prevent this, turn on **Settings > Hide notification details**, or turn it on for a single type. Reminders then show only fixed text such as "You have something coming up", and the weekly summary shows only a count. Events of hidden types are still included in that count. Among the suggested types, "Health" has hiding turned on from the start.

Hiding has limits:
- The notification title ("Knock knock! 🚪") and buttons still show.
- Notifications already in the notification center do not change.
- On Android, details are hidden on a lock screen with a PIN or pattern, but they show when the phone is unlocked and on a watch. On iOS, your phone's "Show Previews" setting applies.

Reminders are local notifications scheduled on your phone. The app does not use remote push notifications and does not create a push token.

## 5. When information leaves your device

The app never sends information on its own. The following happen **only when you choose them or turn them on in your phone's settings**.

1. **Device backup**: if iCloud Backup or Google device backup is on, the app's data is backed up to your own cloud account. Backups follow Apple's and Google's policies. iCloud backups are not end-to-end encrypted unless Advanced Data Protection is on. On Android, Google backups are not end-to-end encrypted if your phone has no screen lock (PIN, pattern or password). The app keeps backup on for such phones too, so your events are not lost when you change phones. On Android, only the app database (events, types, settings and the other information in section 2) and recovery records are backed up, not the list of scheduled reminders (the app schedules them again when you open it on the new phone). The app cannot delete backups, so manage backup settings on your phone.
2. **Export**: Settings > Export creates a file (JSON) with your events and types and opens your phone's share sheet. The file contains your event titles, dates, time zones, checklist items and the types' prep notes as they are. You choose where it goes (mail, a messenger, a files app), and what happens next follows that service's policy. The file stays in a temporary folder on your phone until your next export or Delete all data, and it is not included in device backups.
3. **Phone crash reports**: if "Share With App Developers" (iOS) or usage and diagnostics (Android) is on in your phone's settings, Apple and Google may show the developer crash reports (device model, OS version, where the error happened). They contain no event content, and you can turn this off in your phone's settings.
4. **Opening this policy**: your phone's browser loads this page.

## 6. Beta stats in test builds

Release builds do not have this feature. Only beta builds for invited testers have "Send beta stats".
- Included: how many times each feature was used, the date counting started and the date sent, whether the weekly summary is on, recovery records (counts and the date of the last failure), operating system and major version, app version and build number, app language, and a maker group (samsung, xiaomi, oppo, other, or apple on iOS)
- Not included: event titles, event dates, checklist items, device model, device identifiers, advertising ID, time zone
- The full text is shown on screen before sending, and it leaves the device only when you tap [Send] and pick an app in the share sheet. The app does not send it over the network itself.
- If you send it by mail or a messenger, the developer also receives your email address or account name, and that service handles it under its own policy.
- Sending is your choice. The legal basis is your consent (GDPR Art. 6(1)(a)). You can use the app fully without sending.
- Stats received are used only to improve the app and are deleted from mail and messengers within 3 months after the beta ends.

## 7. Retention and deletion

- Information on your device is kept until you delete it or uninstall the app.
- **Settings > Delete all data** deletes your events, types, settings, scheduling records, usage counts, recovery records, scheduled reminders, Knock Knock notifications in the notification center, and earlier export files. Deleted space is overwritten and cleaned up so nothing is left in the app. This cannot be undone. You can turn off the notification permission separately in your phone's settings.
- Uninstalling the app makes the operating system delete the app's data on the device.
- The app cannot delete data in existing iCloud or Google device backups, or files you exported and sent elsewhere.
- Beta stats the developer received are deleted within the period in section 6, and contact emails within the period in section 14.

## 8. Sharing with third parties

In release builds, the developer receives none of your information. The developer only receives beta stats you send yourself from a beta build (section 6) and emails you send (section 14), and does not share them with or have them processed by any third party. Device backups, sharing and phone crash reports are handled by the services you choose (Apple, Google, the receiving app) under their own policies.

## 9. Permissions

| Permission | Why |
| --- | --- |
| Notifications | To show event reminders |
| Exact alarms (Android) | To fire reminders on time |
| Run at startup (Android) | To restore scheduled reminders after the phone restarts |
| Vibrate (Android) | To vibrate when a reminder fires |

The app does not use location, contacts, camera, microphone, photos or storage permissions. The internet permission is a default of the app's building blocks and is not used to send event information. The app's building blocks also include, by default, a lookup of other apps used by the share sheet and file opening, and an install-source library (Install Referrer), but the app never calls them.

## 10. How your information is protected

- Data is protected by your phone's operating system encryption (iOS Data Protection, Android file-based encryption). Please set a screen lock (PIN, pattern or biometrics).
- Someone with physical access to your phone may see the data, for example on a phone with no screen lock, or by extracting a backup with developer tools on Android 11 or earlier.
- The app validates what you enter and does not put event content in error logs.

## 11. Your rights

You can do the following yourself inside the app at any time:
- Access and correct: view and edit events and types
- Delete: delete events one by one, or use Settings > Delete all data
- Portability: get your events and types as a file with Settings > Export
- Turn reminders off or hide their details

Because the developer does not hold the information on your device, the developer cannot access or delete it for you. For beta stats and emails the developer received, ask at the email below and the developer will show or delete them.

If you are in the European Economic Area, the United Kingdom or Switzerland: the app processes your information only on your device to provide the features you use. You also have the right to lodge a complaint with your local data protection authority.

## 12. Children

The app is not directed at children. It does not collect children's information separately, and it does not collect anyone's information off the device (except beta stats in section 6).

## 13. Cookies and tracking

The app does not use cookies, advertising IDs, analytics or other tracking technologies.

## 14. Privacy contact

- Person responsible for privacy: Ganghyeon Kim (developer)
- Email: rkdgus911@gmail.com

Your email address and message are used only to reply, and are deleted within 1 year after the reply.

## 15. Changes to this policy

If this policy changes, we will announce it in the app update notes and on this page at least 7 days before it takes effect. For changes that matter more to you, such as a feature that sends information off your device, we will announce it at least 30 days ahead and ask for consent when needed. Earlier versions are listed at the bottom of this page.
