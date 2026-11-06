---
title: Data Deletion — Ekonomika
layout: default
---

[🇱🇹 Lietuviškai](./duomenu-istrynimas.html) · **🇬🇧 English**

# Data Deletion — Ekonomika

**App name:** Ekonomika (Ekonomika ir Verslumas)
**Developer:** ISM University of Management and Economics
**Contact:** aras.zirgulis@ism.lt
**Last updated:** 20 April 2026

---

This page explains how to request deletion of data the Ekonomika mobile app has collected about you, what data is deleted, what is retained, and for how long. It fulfils the right of erasure under GDPR Art. 17 ("right to be forgotten").

---

## How to request deletion

You have two options. Both result in complete deletion of your account and personal data.

### Option 1 — Delete from inside the app (fastest)

1. Open the Ekonomika app on your device.
2. Tap **Profile** (bottom navigation bar).
3. Tap the ⚙️ **Settings** icon (top right).
4. Scroll to **Account**.
5. Tap **Delete Account**.
6. Confirm by typing **DELETE** in the confirmation dialog.
7. Tap **Delete Account** a second time to confirm.

The app will immediately:
- Remove your user document from our Firestore database.
- Remove all progress, achievements, and leaderboard entries tied to your account.
- Clear all locally-cached data on your device.
- Delete your Firebase Authentication user.
- Sign you out.

### Option 2 — Email request

If you cannot open the app (e.g. you have already uninstalled it) or prefer email:

1. Send an email to **aras.zirgulis@ism.lt** from the email address associated with your account.
2. Subject: *Ekonomika — data deletion request*
3. In the body, state that you want your Ekonomika account and data deleted.

We will complete the deletion within **30 days** of receiving the request and email you a confirmation, free of charge (GDPR Art. 12(3)). We may ask one follow-up question to verify your identity and prevent unauthorised disclosure.

---

## What is deleted

| Category | Deleted? |
|---|---|
| First name, last name | ✅ Yes |
| School, class, learning style | ✅ Yes |
| Email address and phone number (if you provided them for marketing) | ✅ Yes |
| Learning progress: lessons completed, quiz answers and scores, XP, level, streaks, in-app coin balance | ✅ Yes |
| Mock-exam attempts and results | ✅ Yes |
| Hint-usage and purchase records (in-app coins only) | ✅ Yes |
| Firebase Authentication record (anonymous UID or Google sign-in token) | ✅ Yes |
| Local app caches on your device (Hive database, shared preferences) | ✅ Yes |
| Marketing-consent record | ✅ Yes |

---

## What is retained, and for how long

| Category | Retention | Legal basis |
|---|---|---|
| Anonymous, aggregated analytics events (`lesson_start`, `quiz_complete`, etc.) that have already been pseudonymised by Firebase Analytics and can no longer be linked to your identity | Up to 14 months (Google Firebase Analytics default) | Legitimate interest — improving the App (GDPR Art. 6(1)(f)) |
| Records we are legally required to keep (e.g. tax records if you had made a real-money purchase — the App currently has no real-money transactions, so this section is typically empty) | As required by Lithuanian law | Legal obligation (GDPR Art. 6(1)(c)) |

Nothing that can identify you personally is retained once deletion has been processed.

---

## Questions?

If you have any questions about this process or about our full data-handling practices, please:

- Read the full [Privacy Policy](./privacy-policy.html).
- Email **aras.zirgulis@ism.lt**.
- File a complaint with the Lithuanian supervisory authority: **Valstybinė duomenų apsaugos inspekcija (VDAI)**, L. Sapiegos g. 17, 10312 Vilnius, [ada.lt](https://ada.lt).
