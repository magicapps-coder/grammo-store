---
title: Privacy Policy
permalink: /privacy
---

# Privacy Policy — Grammo

**Last updated: November 11, 2026**

---

## 1. Overview

Grammo ("the App", package `com.magic.apps.grammo`) is an English grammar trainer: lessons, quizzes on tenses and
other grammar topics, word sets and flashcards, quiz history, progress statistics, reminders and a home-screen
widget. This Privacy Policy explains what data the App processes, what leaves your device and why.

The App is developed and maintained by an independent developer ("we"). We do not sell data.

**Short version:** by default your answers, quiz history, progress and settings stay on your device. If you
**optionally sign in with Google**, a copy of your progress is stored in your private cloud backup so you can
restore it on another device; you can delete the account and the backup at any time in the App. The App sends
usage statistics and crash reports (Firebase), and shows ads through Google AdMob, which may use your device's
advertising ID. Ads are removed with the Grammo Premium subscription.

---

## 2. Data processed only on your device

| Data | Why | Leaves the device? |
|---|---|---|
| Your answers, quiz settings and quiz history | Results, retaking quizzes, the mistakes deck | **No** |
| Progress per topic, daily goal, streak | Progress screen, reminders | **No** |
| Settings (theme, hints, haptics, sounds, reminders) | App features | **No** |
| Words and rules shown in the widget, your "know / don't know" taps | Home-screen widget | **No** |
| Words you import from a CSV file, your favourite words | Word training | **No** (unless you sign in, section 3.3) |
| Purchase status (Premium, unlocked mascots) | Hiding ads, unlocking mascots; also confirmed with Google Play | **No** (checked with Google Play, see section 4) |

You can export your history to a file or reset all progress in Settings. Uninstalling the App deletes all data
listed above from the device.

---

## 3. Data collected automatically

### 3.1 Analytics and crash reports

The App uses **Firebase Analytics** and **Firebase Crashlytics**, services provided by Google LLC.

- **Usage analytics:** which screens are opened and which features are used, for example "quiz started: 20
  questions, level B1", "quiz finished: 75%", "widget added". Events contain counts, levels, topic identifiers and
  settings. They never contain text you type.
- **Crash reports:** when the App crashes or hits an error, a report is sent with the stack trace, device model,
  Android version, App version and the App's state at that time.
- **Identifiers:** Firebase assigns a random app-instance / installation identifier. Firebase Analytics in the App
  does **not** collect the advertising ID and does not link data to your identity.

Analytics and crash reporting are disabled in development builds.

### 3.2 Advertising

Unless you have removed ads, the App shows a small banner provided by **Google AdMob**. To show and measure ads,
AdMob may collect your device's **advertising ID**, IP address, approximate location derived from it, device and
app information, and ad interactions. Depending on your choices and your region, ads may be personalised.

- In the European Economic Area, the United Kingdom and Switzerland the App asks for your consent through Google's
  consent form before personalised ads are shown. You can change your choice at any time in Settings → «Конфиденциальность рекламы» (Ad privacy).
- You can reset or delete your advertising ID, or opt out of ad personalisation, in Android Settings →
  Privacy → Ads.
- How Google uses this data: https://policies.google.com/technologies/partner-sites

While your Grammo Premium subscription is active no ads are requested.

This data is processed by Google in accordance with Google's Privacy Policy: https://policies.google.com/privacy

### 3.3 Optional account and cloud backup

Signing in is optional; every feature works without it. If you choose **Sign in with Google**:

- **Firebase Authentication** (Google LLC) receives your Google account's **name, e-mail address and a user ID**
  to create your Grammo account.
- **Cloud Firestore** (Google LLC) stores **one private document** with a copy of your learning data: progress per
  topic, quiz history (answers and results), streak, settings, favourite and imported words. Only you can read or
  write it (it is protected by your user ID). It is used to restore your progress after reinstalling the App or
  on another device.
- **Deleting your account:** Settings → Account → **Delete account** deletes the cloud document and your Grammo
  account immediately. Data on the current device stays until you reset it or uninstall the App. You can also ask
  us to delete your account by e-mail (section 12) from the address you signed in with.

---

## 4. Network connections

The App works offline. It connects to the internet only to:

1. Send analytics and crash reports (section 3.1).
2. Load banner ads (section 3.2), unless ads are removed.
3. Process the optional **Grammo Premium** subscription (yearly, with a free trial for new subscribers) and
   one-time **mascot** purchases, and restore them, through **Google Play Billing**. Payment details are handled
   by Google; the App only receives the purchase status and purchase token. Manage or cancel the subscription in
   Google Play → Payments & subscriptions.
4. Sync your progress if you signed in (section 3.3).
5. Read remote settings (for example, how often a full-screen ad may appear) from **Firebase Remote Config**.
6. Check for app updates and show the rating dialog through **Google Play** (in-app updates, in-app review).
7. Pronounce words with your device's text-to-speech engine (may use the network depending on your device
   settings).

---

## 5. Permissions

| Permission | Purpose |
|---|---|
| Internet, network state | Ads, analytics, crash reports, purchases, optional sync (section 4) |
| Notifications (`POST_NOTIFICATIONS`) | Reminders about an unfinished quiz and your daily goal. Asked only when you turn reminders on. |
| Run at startup (`RECEIVE_BOOT_COMPLETED`) | Re-schedule your reminders after the device restarts |
| Vibration (`VIBRATE`) | Haptic feedback, for example on a wrong answer. Can be turned off in Settings. |
| Google Play Billing (`com.android.vending.BILLING`) | Buy and restore Grammo Premium and mascots |
| Advertising ID (`AD_ID`) | Used by Google AdMob to show ads (section 3.2) |

---

## 6. Sharing

When you share a quiz result or invite a friend, the App opens the Android share sheet with a picture of the
result and a link to the App. Nothing is sent until you choose an app to share with, and what you send is then
handled by that app.

---

## 7. Data sharing

We do not sell or rent personal data. Data from section 3 is processed by Google as our service provider
(Firebase Analytics, Crashlytics, Authentication, Firestore, Remote Config) and as the ad network (AdMob).

---

## 8. Retention

On-device data is kept until you reset it in the App or uninstall the App. Your account and cloud backup are kept
until you delete the account (section 3.3). Firebase data is kept according to the retention settings of the
Firebase project (crash reports: 90 days; analytics: up to 14 months). AdMob data is kept according to Google's
retention policy.

---

## 9. Your rights

Data on your device is under your control (section 2). Your account and cloud backup can be deleted in the App
(section 3.3) or on request by e-mail. To ask us to delete analytics data linked to your app
instance, contact us (section 12) with the date you installed the App; because we do not know who you are, we may
need you to reinstall the App to break the link. Depending on where you live, you may have further rights under
laws such as the GDPR; contact us to exercise them.

---

## 10. Children's privacy

The App is intended for users aged 13 and older. Accounts are optional, and the App has no chat or social
features and no public user-generated content. We do not knowingly collect personal information from children under 13. Parents or
guardians who believe a child has provided personal information can contact us and we will delete it.

---

## 11. Changes to this policy

This policy may be updated from time to time. Changes are reflected by the date at the top of this page.

---

## 12. Contact

Questions about this policy: **victoramazon1001@gmail.com**
