# Privacy Policy for Digital Sanity

**Effective date:** November 1, 2026
**Developer:** Hasnain Softwares
**Contact:** hasnainsoftwares@gmail.com

Digital Sanity ("the app", "we") helps you build calmer phone habits. It shows a short pause screen when you open an app you chose to manage, and it lets you set daily limits, run focus sessions, and write short reflections.

We built Digital Sanity to be **private by default**. The app has no account and no ads. It has no analytics or tracking SDKs, and it does not request the Internet permission. Everything the app records stays on your phone unless you choose to back it up yourself.

---

## 1. Summary

|                                        |                                                        |
| -------------------------------------- | ------------------------------------------------------ |
| Account or sign-in                     | None                                                   |
| Ads                                    | None                                                   |
| Analytics, tracking or crash reporting | None                                                   |
| Internet permission                    | Not requested. The app cannot send data to any server. |
| Where your data is stored              | Only in the app's private storage on your phone        |
| Data shared with the developer         | None. We never receive any of your data.               |
| Data sold to third parties             | None                                                   |

---

## 2. Information the app processes

All of the following is created and stored **only on your device**. None of it is sent to us.

### 2.1 Apps you choose to manage

- The names and package names of the apps you add (for example, a social media app).
- The daily limit, blocking mode (Gentle, Balanced or Strict) and schedule you set for each one.
- A list of apps that have a launcher icon on your phone. The app reads this only to show you a list to choose from. It is never saved or sent anywhere.

### 2.2 App usage time (Usage Access permission)

If you grant **Usage Access**, the app reads how many minutes you spent in apps and how many times you opened them. It uses this to show your screen time, daily limits and weekly insights. Usage data is read from Android on demand and shown on your phone only.

### 2.3 Foreground app detection (Accessibility Service)

See [Section 3](#3-accessibility-service-disclosure) for full details.

### 2.4 Your activity inside the app

- Pause events: when a pause was shown, for which app, whether you kept the pause or continued, and the optional reason you tapped (for example "Bored" or "Habit").
- Focus sessions: the preset name, start and end time, and focused minutes.
- Daily reflections: the short answers you choose to type (what was hardest, what helped, your intention for tomorrow).
- Bedtime protection settings and reminder preferences.
- An optional display name that you enter so the app can greet you. It does not need to be your real name.

### 2.5 Purchase status

If you buy the optional one-time **Backup unlock**, the app stores a flag on your phone that says the purchase is owned. The app does not see or store your payment details (see [Section 5](#5-in-app-purchase)).

---

## 3. Accessibility Service disclosure

Digital Sanity uses Android's **AccessibilityService API**. This is the app's core feature: it lets the app notice when you open an app you chose to manage and show the pause screen at that moment.

**What the service does:**

- It listens only for "window state changed" events. These tell the app which app has just come to the foreground, identified by its package name.
- It compares that package name with the list of apps you chose to manage, your limits, your focus session and your bedtime schedule. Then it decides whether to show a pause.

**What the service does NOT do:**

- It **cannot read the content of your screen**. The service is configured with `canRetrieveWindowContent="false"`, so Android never gives it the text, images, messages or passwords shown in other apps.
- It does not record keystrokes, perform gestures, or interact with other apps.
- It does not collect or send any data off your device.

The app explains this and asks for your consent during setup before it sends you to Android's settings. You can turn the service off at any time in **Android Settings → Accessibility → Digital Sanity**. If you do, the pause screen stops appearing.

---

## 4. Permissions

| Permission                                | Why it is used                                                                   |
| ----------------------------------------- | -------------------------------------------------------------------------------- |
| Accessibility Service                     | Detects when a managed app opens so the pause screen can appear (see Section 3). |
| Usage Access (`PACKAGE_USAGE_STATS`)      | Shows screen time and enforces the daily limits you set.                         |
| Notifications (`POST_NOTIFICATIONS`)      | Optional reminders, such as your daily reflection or bedtime.                    |
| Run at startup (`RECEIVE_BOOT_COMPLETED`) | Restores your scheduled reminders after the phone restarts.                      |
| Google Play Billing (`BILLING`)           | Lets you buy the optional Backup unlock through Google Play.                     |

The app does **not** request the Internet, location, contacts, camera, microphone, SMS, phone or storage permissions.

---

## 5. In-app purchase

Digital Sanity is free. One optional one-time purchase, **Backup unlock**, turns on backup and restore.

Purchases are processed entirely by **Google Play**. We never receive your card number, billing address or other payment details. Google may collect information to process the payment, as described in the [Google Play Terms of Service](https://play.google.com/about/play-terms/) and the [Google Privacy Policy](https://policies.google.com/privacy). The app only receives a confirmation from Google Play that the purchase is owned.

---

## 6. Backup and restore (optional)

Backup is **off** unless you buy the Backup unlock. After you buy it, you can choose to use either of the following:

- **Android Auto Backup to Google Drive.** Android's built-in backup system can copy the app's data to _your own_ Google account. Google runs this backup and encrypts it. We cannot access it. Backup is controlled by your phone's backup settings (**Settings → Google → Backup**), and Google's privacy policy applies to it.
- **Backup file (export and restore).** You can save your plan and history as a file. Android's file picker lets you choose where the file goes, such as your phone's storage or a cloud folder you pick. You can later restore from that file. The app writes the file only to the place you choose, and the app never uploads it itself.

Temporary data, such as today's "continue for 10 minutes" allowances, is excluded from backups.

---

## 7. Data sharing

We do **not** share, sell, rent or transfer your data to anyone. Because the app has no Internet access, it cannot send your data to us or to any third party.

The only times data leaves the app are the ones you start yourself:

- Android Auto Backup, if you unlocked it and it is on in your phone's settings.
- A backup file that you save to a place you choose.
- Purchase information that Google Play processes when you buy the Backup unlock.

---

## 8. Data retention and deletion

Your data stays on your phone for as long as you keep the app installed, or until you delete it. You can delete it at any time:

- **In the app:** go to **Settings → Privacy → Delete all data**. This erases all local records, rules, history and scheduled reminders.
- **Uninstall the app:** Android removes all of the app's data from your phone.
- **Google Drive backup:** you can delete it from your Google account (**Google Drive → Backups**) or by turning off backup in your phone's settings.
- **Backup files** you saved are yours to delete wherever you stored them.

Because we never receive your data, we have no copy of it to delete. You do not need to contact us to have your data removed.

---

## 9. Security

Your data is stored in the app's private storage, which Android protects from other apps. Because nothing is sent over the network, your data is not exposed to interception in transit. Google Drive backups are encrypted by Google. Keep backup files you export in a place you trust, since anyone with access to the file could read it.

---

## 10. Children's privacy

Digital Sanity is not directed at children under 13, and we do not knowingly collect personal information from anyone. Because the app collects nothing on our side, no data about any user, including children, ever reaches us.

---

## 11. Not a medical product

Digital Sanity is a self-help tool for building healthier phone habits. It is not a medical device and does not diagnose or treat any condition.

---

## 12. Changes to this policy

If we change this policy, we will update the effective date above and publish the new version at this same address. If a change affects how your data is handled, we will also tell you in the app or in the Play Store release notes.

---

## 13. Contact

If you have questions about this policy or your privacy, contact:

**Hasnain Softwares**
Email: **hasnainsoftwares@gmail.com**
