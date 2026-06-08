---
# Privacy Policy
---

**Version 1.1 — Effective: [06.06.2026]**

ShredNet ("the App", "we", "us", "our") is a mobile application that lets you share planned sports activity dates with friends. This Privacy Policy explains what personal data we collect, why we collect it, who we share it with, and what rights you have under the General Data Protection Regulation (GDPR).

**Data Controller**
[NIKOLAS DEHLER]
[SILCHERSTR. 4]
[89231 NEU-ULM, GERMANY]
Email: [shrednetapp@gmail.com]

---

## 1. Data we collect and why

### 1.1 Account data

When you create an account we collect:

- **Email address** — to identify your account and allow you to sign in. You can change your email address at any time from Settings; a verification link will be sent to the new address and your account email only updates after you click that link.
- **Display name** — to identify you to your friends within the App.
- **Password** — stored as a cryptographic hash by Firebase Authentication. We never see or store your password in plaintext. You can change your password at any time from Settings.
- **Account creation date** — for security and internal record-keeping.

We send a verification email to the address you provide. You must click the link in that email before your account is activated and any profile data is written to our servers.

*Legal basis: performance of contract — GDPR Art. 6(1)(b). This data is strictly necessary to provide the App.*

### 1.2 Profile picture

You may optionally upload a profile photo. It is stored in Firebase Storage and displayed to other users of the App alongside your display name.

*Legal basis: consent — GDPR Art. 6(1)(a). You can remove it at any time from your profile settings.*

### 1.3 Ride data

When you plan a ride, we store:

- The resort you selected.
- Your chosen sport (e.g. skiing, snowboarding, mountain biking, hiking, surfing, après-ski).
- Your planned start and end dates.
- Optionally, a specific time window (start time, end time, and timezone) if you choose to set one.
- An optional written note visible to your friends.
- An optional carpool status (whether you are offering a car seat or looking for one), visible to friends going to the same resort on overlapping dates.
- Optionally, a post-ride log containing: a star rating (1–5), a set of condition tags you select (e.g. "Powder day", "Icy"), a written note, and photos — all stored in Firebase Storage.

This information is shared with your accepted friends through the feed and map features of the App.

*Legal basis: performance of contract — GDPR Art. 6(1)(b).*

### 1.4 Social data

We store:

- Your list of accepted friends (stored as a list of user identifiers).
- Incoming and outgoing friend requests and their status (pending, accepted, declined).

This is necessary to provide the core social features of the App.

**Who can see your friends list:**
If your profile is **public** (the default), your friends list — the display names and profile pictures of your accepted friends — is visible to any other authenticated user of the App. If your profile is **private**, your friends list is only visible to your accepted friends. You can switch between public and private at any time in your profile settings.

*Legal basis: performance of contract — GDPR Art. 6(1)(b).*

### 1.5 In-app notifications

We store a history of in-app notifications delivered to you (for example: "A friend is going to the same resort"). These records are automatically and permanently deleted after 90 days.

*Legal basis: legitimate interests — GDPR Art. 6(1)(f). We have a legitimate interest in informing you about activity relevant to your plans. This does not override your interests or rights.*

### 1.6 Push notification token

If you grant notification permission, we store a device push token (a unique identifier assigned by Expo's notification infrastructure) in a private, owner-only subcollection of your user record. This token is used solely to deliver push notifications to your device.

The push token is personal data. It is removed immediately if you disable notifications in the App's settings or delete your account.

*Legal basis: consent — GDPR Art. 6(1)(a). You can withdraw consent at any time by disabling notifications in Settings.*

### 1.7 Notification preferences

Your notification on/off preference is stored locally on your device and synced to our servers. This allows our backend to avoid sending push notifications to users who have opted out.

*Legal basis: consent — GDPR Art. 6(1)(a).*

### 1.8 Consent record

When you accept these Terms of Service and this Privacy Policy, we record the timestamp and the version number of the documents you accepted. This audit record is stored in our database and is deleted when you delete your account.

*Legal basis: legal obligation — GDPR Art. 6(1)(c). We are required to be able to demonstrate that consent was freely given and informed.*

### 1.9 Resort suggestions and corrections

If you submit a new resort or propose a correction to existing resort data, we store your submission alongside your user identifier so we can review it and notify you of the outcome. Approved submissions are incorporated into the App's resort database without your identifier attached.

*Legal basis: legitimate interests — GDPR Art. 6(1)(f). We have a legitimate interest in maintaining accurate resort data while being able to contact you about your submission.*

---

## 2. What we do not collect

- **GPS or precise location data.** We never request or store your device's GPS coordinates. The map in the App shows the publicly available geographic coordinates of resorts and trail locations. Your presence on the map is derived solely from the resort you chose when planning a ride — not from your device location.
- **Advertising identifiers or SDKs.** We do not use any advertising networks.
- **Analytics or crash-reporting SDKs.** We do not use Firebase Analytics, Crashlytics, or any equivalent third-party service.
- **Cookies.** This is a mobile application and does not use cookies.

We do not sell, rent, or trade your personal data to any third party.

---

## 3. Third-party processors

We rely on the following sub-processors, each of which processes data on our behalf under a Data Processing Agreement:

| Processor | Role | Data involved | Storage location |
|---|---|---|---|
| **Google LLC** (Firebase Authentication, Firestore, Firebase Storage, Cloud Functions) | Core infrastructure — authentication, database, file storage, and server-side functions | Email, display name, profile picture, ride data, friend lists, notifications, push token, consent record | United States (transferred under EU Standard Contractual Clauses) |
| **Expo Inc.** | Push notification routing — receives Expo push tokens and forwards notifications to Apple APNs / Google FCM | Expo push token, notification title and body | United States |
| **Google LLC** (Google Maps Platform) | Map rendering on Android devices | No personal data is transmitted; only the public coordinates of resorts are passed to the map renderer | N/A |

**Google Firebase Data Processing Agreement:**
Google's Data Processing and Security Terms are available at firebase.google.com/support/privacy. The applicable Standard Contractual Clauses are included within that agreement and cover transfers of personal data to the United States.

**Expo Privacy:**
Expo's privacy policy is available at expo.dev/privacy.

---

## 4. International data transfers

Your data is processed by Google Firebase on servers that may be located in the United States. These transfers are governed by the EU Standard Contractual Clauses incorporated into Google's Data Processing Agreement, which provide appropriate GDPR safeguards. You can request a copy of the applicable safeguards by contacting us at the address above.

---

## 5. Data retention

| Data | Retained until |
|---|---|
| Email address, display name, sports preferences, settings | You delete your account |
| Profile picture | You remove it, or you delete your account |
| Ride data | You delete the individual ride, or you delete your account |
| Friend lists and friend requests | You unfriend / decline, or you delete your account |
| In-app notifications | 90 days from creation (automatic), or you delete your account |
| Push notification token | You disable notifications, or you delete your account |
| Notification preferences | You delete your account |
| Consent record | You delete your account |
| Unverified account (Firebase Authentication record only — no Firestore data written) | Automatically deleted by Google Firebase after 30 days if email verification is not completed |

When you delete your account, all of the above data is permanently erased. This includes your Firebase Authentication record, all Firestore documents, your profile picture and ride log photos in Firebase Storage, and all notification history. There is no retention period after deletion.

---

## 6. Your rights

Under the GDPR you have the following rights regarding your personal data:

**Right of access (Art. 15)**
You can download a copy of all data we hold about you. Go to **Settings → Export My Data** in the App.

**Right to erasure (Art. 17)**
You can permanently delete your account and all associated data at any time. Go to **Settings → Delete Account**. All data is erased immediately. There is no residual retention.

**Right to rectification (Art. 16)**
You can update your display name, email address, sports preferences, and profile picture at any time from your profile settings or Settings within the App.

**Right to data portability (Art. 20)**
The data export (Settings → Export My Data) provides your profile and ride history in a portable text format.

**Right to restriction of processing (Art. 18)**
You may contact us to request that we restrict how we process your data while a dispute is pending.

**Right to object (Art. 21)**
For processing based on legitimate interests (in-app notifications, resort suggestions), you may contact us to object. We will assess whether our legitimate interests are overridden by your interests or rights.

**Right to withdraw consent**
Where processing is based on your consent (profile picture, push notifications), you can withdraw at any time — by removing the picture in profile settings or disabling notifications in Settings — without affecting the lawfulness of processing carried out before withdrawal.

To exercise any of these rights, contact us at: **[shrednetapp@gmail.com]**

We will respond within one month. In complex cases we may extend this period by a further two months, and will inform you of this within the first month.

**Right to lodge a complaint**
You have the right to lodge a complaint with your national supervisory authority. If you are based in Germany:

Bundesbeauftragte für den Datenschutz und die Informationsfreiheit (BfDI)
Graurheindorfer Str. 153, 53117 Bonn
www.bfdi.bund.de

---

## 7. Children

The App is intended for users aged **16 and over**. We do not knowingly collect personal data from anyone under 16. If you believe a child under 16 has created an account, please contact us immediately and we will delete the account and all associated data without delay.

---

## 8. Security

We implement appropriate technical and organisational measures to protect your personal data, including:

- Firestore Security Rules that restrict ride data and private profile content to the account owner and their accepted friends. Public profile data (display name, profile picture, and — for public profiles — the friends list) is readable by any authenticated user, consistent with the visibility model described in section 1.4.
- Push tokens stored in a private owner-only subcollection, inaccessible to other users.
- Firebase Authentication's industry-standard password hashing.
- All data transmitted over HTTPS.

No system is perfectly secure. If you discover a security vulnerability, please contact us responsibly at [shrednetapp@gmail.com].

---

## 9. Changes to this policy

If we make material changes to this policy, we will update the version number and effective date at the top of this document, and — where the change affects how we process your data — ask you to review and re-accept the updated policy the next time you open the App. The policy version you accepted is recorded in our systems.

Continued use of the App after a non-material update constitutes acceptance of the revised policy.

---

*ShredNet Privacy Policy — Version 1.1*
*Data Controller: [NIKOLAS DEHLER]*
