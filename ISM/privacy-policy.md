---
title: Privacy Policy — Ekonomika
layout: default
---

[🇱🇹 Lietuviškai](./privatumo-politika.html) · **🇬🇧 English**

# Privacy Policy — Ekonomika

**Last updated:** 30 April 2026
**Effective date:** 30 April 2026
**Version:** 2.1

This Privacy Policy describes how the **Ekonomika** mobile application ("the App") processes personal data. The App is an educational product of **ISM University of Management and Economics** and is governed by ISM's institutional privacy policy, available at **[ism.lt/privatumo-politika](https://www.ism.lt/privatumo-politika/)**. This document adapts that institutional policy to the specific context of the App, as required by the EU General Data Protection Regulation (Regulation (EU) 2016/679 — "**GDPR**") and the Lithuanian Law on Legal Protection of Personal Data.

Where this document is silent on a question, the ISM institutional policy applies.

---

## 1. General Provisions

The data controller is:

**UAB "ISM Vadybos ir ekonomikos universitetas"** (ISM University of Management and Economics)
Registration No.: **111963319**
Registered office: **Gedimino pr. 7, Vilnius, Lithuania**
Phone: **+370 687 08080**
Email: **ism@ism.lt**

**Data Protection Officer (DPO):** **dpo@ism.lt**

This Privacy Policy applies to users of the Ekonomika mobile application. It governs the collection, processing, and storage of personal data in connection with the App, alongside ISM's accredited study programmes, executive training, research activities, exchange programmes, and other services covered by ISM's institutional policy.

---

## 2. Data Processing Principles

The University processes personal data in accordance with EU Regulation 2016/679 and Lithuanian data protection laws. The core principles are:

- Personal data is collected for **clearly defined and lawful purposes** and is not further processed in a manner incompatible with those purposes.
- Processing is conducted **lawfully, fairly, and in a transparent manner**.
- Data is kept **up to date** and, where necessary, corrected.
- Data is **stored securely** and only for as long as is necessary for the purposes for which it was collected.
- Access is **restricted to authorised personnel** on a least-privilege basis.

**Legal bases** for processing (GDPR Art. 6(1)):

1. Performance of a contract or pre-contractual steps at the data subject's request;
2. Explicit consent;
3. Compliance with a legal obligation;
4. Protection of vital interests;
5. Legitimate interests pursued by the University.

---

## 3. Data Sources

The App operates **without a user account**. Instead, a random local identifier (UUID) is generated on first launch and stored only on that device. The University does not receive this identifier, **except** in the single case where the user provides marketing consent (see §6).

Personal data is obtained directly from the individual (student, user, representative) when the individual:

- Completes the onboarding learning-style questionnaire or student profile (stored only on the device);
- Provides an email address or phone number for marketing purposes (optional);
- Interacts with lessons, quizzes, and mock exams within the App (results stored only on the device).

Technical analytics data (device model, operating system, app version, language, approximate IP-based region) is obtained automatically via Firebase Analytics (provider: Google Ireland Ltd.).

---

## 4. Processing Purposes

The University processes personal data for the following purposes:

| Purpose | Legal basis |
|---|---|
| Providing the Ekonomika learning service and saving learning progress on the user's device | Legitimate interest |
| Aggregated product analytics (lesson completion counts, error rates) without identity | Legitimate interest |
| Direct marketing (information about new ISM educational products) | Explicit consent (separate checkbox, withdrawable at any time) |
| Compliance with legal obligations (accounting, responding to authorities) | Legal obligation |

The marketing-consent checkbox is **unticked by default**. The App can be used in full without providing an email address or phone number.

---

## 5. Categories of Personal Data

The App processes the following categories. All user profile and learning data is stored **only on the user's device** (local Hive database and SharedPreferences); only marketing-consent submissions and anonymous analytics events are sent to ISM-controlled servers.

**Stored on the device only:**

- **Identity data:** first name, last name (optional).
- **Education data:** school, class (optional).
- **Preferences:** learning style derived from the onboarding questionnaire (optional).
- **Usage data:** lessons completed, quiz answers and scores, XP, level, streaks, in-app coin balance, hint usage, mock-exam attempts and results.
- **Local identifier:** a random UUID generated on first launch to distinguish sessions on the same device.

**Sent to ISM servers (Firestore, Google Ireland Ltd.):**

- **Contact and marketing data** — first name, last name, email, phone, school, class, local UUID, consent timestamp — **only if the user ticks the marketing-consent checkbox** and provides an email or phone number. Stored in a single document in the `marketing_optins/{deviceUuid}` collection. At most one document per device.

**Anonymous analytics (Firebase Analytics):**

- Anonymous events (`lesson_start`, `quiz_complete`, `screen_view`, etc.), device model, operating system and version, app version and language, approximate IP-based region. This data is not linked to a user's name or contact information.

The App does **not** access contacts, camera, microphone, location, photo library, or calendar. The App does **not** send push notifications, does **not** use advertising SDKs or identifiers, and does **not** perform automated decision-making or profiling that produces legal effects.

---

## 6. Direct Marketing

The University may carry out direct marketing regarding educational products and services.

- **Data used:** name, surname, email, phone, school, class.
- **Consent:** obtained via a separate, voluntary checkbox during App registration. Consent is **not** a condition of using the App.
- **Channels:** email and, where applicable, phone consultation.
- **Storage duration:** until consent is withdrawn — at the latest, **10 years** after the end of the relationship with the University.
- **Withdrawal of consent:** at any time, either in the App (Settings → Profile or Settings → Delete Account) or by emailing **dpo@ism.lt**. Withdrawing consent in the App deletes the corresponding document from the `marketing_optins` collection automatically.

Withdrawing consent does not affect the lawfulness of processing carried out before withdrawal.

---

## 7. Data Disclosure and Processors

The University does **not** sell personal data. The University maintains confidentiality and discloses personal data to third parties only where necessary for performance of a contract or where there is a legitimate reason, including:

- **Data processors** — IT, hosting, analytics, accounting, and collection services operating under data-processing agreements compliant with GDPR Art. 28. In particular:
  - **Google Ireland Ltd.** — Cloud Firestore (only for the marketing-consent collection `marketing_optins`), Firebase Analytics (anonymous events), Firebase App Check (abuse prevention). The App does **not** use Firebase Authentication, Cloud Storage for Firebase, or Google Sign-In. See [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy), [policies.google.com/privacy](https://policies.google.com/privacy).
- **ISM University staff** — educators and researchers working with aggregated or anonymised data for pedagogical and research purposes.
- **ISM marketing team** — only with the data subject's prior consent.
- **Courts, law-enforcement or government institutions** — where disclosure is required by applicable law.

### 7.1 International transfers

Some Firebase infrastructure is located outside the European Economic Area (primarily in the United States). Google Ireland Ltd. ensures adequate protection for such transfers through the **EU–US Data Privacy Framework** and/or **Standard Contractual Clauses** (GDPR Art. 46).

---

## 8. Data Retention

Personal data is stored in electronic systems hosted by the University's data processors.

| Data | Retention period |
|---|---|
| Profile and learning data on the device | Stored on the user's device for as long as the user keeps using the App. Deleted in one tap (Settings → Delete Account) or by uninstalling the App |
| Marketing opt-in document (`marketing_optins/{deviceUuid}`) | Until consent is withdrawn in the App, at the latest 10 years after the end of the relationship. Withdrawal triggers immediate deletion of the document |
| Anonymous analytics events | Google default retention, typically up to 14 months, not linked to a name or contact information |

Where a legal claim period exists, data may be retained until the expiry of applicable limitation periods.

---

## 9. Data Subject Rights

Under the GDPR, the data subject has the right to:

- **Access** (Art. 15) — obtain a copy of personal data held;
- **Rectification** (Art. 16) — correct inaccurate or incomplete data;
- **Erasure** (Art. 17) — request deletion where processing is no longer necessary or consent is withdrawn;
- **Restriction of processing** (Art. 18);
- **Data portability** (Art. 20) — receive the data in a structured, machine-readable format;
- **Objection** (Art. 21) — object to processing based on legitimate interest;
- **Withdraw consent** (Art. 7(3)) — at any time, for any consent-based processing;
- **Object to direct marketing** — at any time;
- **Not be subject to automated decision-making** (Art. 22) — the App does not perform such decision-making.

Requests should be addressed to the DPO at **dpo@ism.lt**. The University may ask for identity verification to prevent unauthorised disclosure and will respond free of charge within **one month** (GDPR Art. 12(3)).

### 9.1 Right to complain

If the data subject believes that the University is processing data unlawfully, the data subject may lodge a complaint with the Lithuanian supervisory authority:

**Valstybinė duomenų apsaugos inspekcija (State Data Protection Inspectorate)**
L. Sapiegos g. 17, 10312 Vilnius, Lithuania
Web: [ada.lt](https://ada.lt)

---

## 10. Security

The University applies industry-standard security measures through its processors, including:

- **TLS 1.2+** encryption for data in transit;
- **AES-256** encryption for data at rest;
- Firestore security rules: the `marketing_optins` collection is **write-only** (clients cannot read any documents), with a strict allow-list of fields and a mandatory server-side timestamp;
- **Firebase App Check** (Play Integrity on Android, App Attest with DeviceCheck fallback on iOS) — ensures that only authentic instances of the App can write;
- Two-factor authentication on ISM administrative accounts;
- Principle of least privilege for internal access.

If a personal-data breach occurs that is likely to result in a risk to the rights and freedoms of data subjects, the University will notify the State Data Protection Inspectorate within **72 hours** and affected users without undue delay (GDPR Art. 33–34).

---

## 11. Minors

The App is intended for students aged **16 and older** (gymnasium grades 11–12).

Under Lithuanian law and GDPR Art. 8, the processing of personal data of children under 16 requires the consent of a parent or legal guardian. Parents or guardians wishing to withdraw consent may email **dpo@ism.lt**; the child's account and associated data will be deleted within 30 days.

The University does not knowingly collect data from children under 14. If such collection comes to the University's attention, the data will be deleted immediately.

---

## 12. Cookies and Local Storage

The App is a mobile application and does **not** use browser cookies. The App operates entirely offline and stores the following **on the user's device**:

- Learning progress, profile fields, and settings (local Hive database and SharedPreferences);
- A local UUID — a random identifier generated on first launch to distinguish sessions on the same device.

This local data can be cleared by uninstalling the App, using the device's app-storage controls, or via the in-App settings ("Delete Account"). The ISM website ([ism.lt](https://www.ism.lt)) uses cookies; see the ISM institutional policy and [Slapukai-LT.pdf](https://www.ism.lt/wp-content/uploads/Slapukai-LT.pdf) for details.

---

## 13. Final Provisions

The University reserves the right to modify this Privacy Policy. Material changes will be notified in the App before they take effect, and the "Last updated" date above will be revised. Users are encouraged to review the policy and the ISM institutional policy at **[ism.lt/privatumo-politika](https://www.ism.lt/privatumo-politika/)** periodically.

Lithuanian law applies to this Privacy Policy.

---

## 14. Contact

**Data controller:** UAB "ISM Vadybos ir ekonomikos universitetas"
**Registered office:** Gedimino pr. 7, Vilnius, Lithuania
**Registration No.:** 111963319
**General:** [ism@ism.lt](mailto:ism@ism.lt) · +370 687 08080
**Data Protection Officer / privacy requests:** **[dpo@ism.lt](mailto:dpo@ism.lt)**
**App identifier:** `org.kastalia.ekonomika`
**Parent policy:** [ism.lt/privatumo-politika](https://www.ism.lt/privatumo-politika/)
