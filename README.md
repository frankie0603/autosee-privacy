# Privacy Policy for AutoSee

**Effective Date:** 2026-11-15  
**Developer / Service Provider:** AutoSee Team  
**Contact Email:** autosee.support@gmail.com  

This Privacy Policy applies to the **AutoSee** mobile application (the "Application") for Android devices, developed and provided by **AutoSee Team** (the "Service Provider") as an Ad-Supported and Freemium service.

---

## 1. Accessibility Service & Screen Capture Declaration

To deliver its core screen-automation features, the Application requests Android **AccessibilityService API**, **MediaProjection (Screen Capture)**, and **Display Over Other Apps (Overlay)** permissions only after obtaining your explicit consent.

- **Purpose of Use:** These permissions are used solely to detect user-configured visual templates, on-screen text, or pixel colors, and to execute automated taps, swipes, long-presses, and gesture workflows configured by you.
- **100% On-Device Visual Processing:** All screen captures, image template matching (OpenCV), and text recognition (Google ML Kit OCR) are processed **exclusively in volatile memory on your local device**.
- **Strict Non-Collection Guarantee for Screen Content:** The Application does **not** upload, transmit, log, or share your screen recordings, screenshots, passwords, keystrokes, or personal screen contents to our servers or any third party.
- **User Control:** You may pause, disable, or revoke Accessibility, Screen Capture, or Overlay permissions at any time through your Android system settings.

---

## 2. Information Collection and Use

While screen contents never leave your device, the Application collects and processes limited account, device, subscription, and diagnostic information necessary to operate authentication, quota management, subscriptions, advertising, and stability monitoring:

- **Account & Authentication Data:** When you choose to sign in with Google, we receive your Firebase User ID (`uid`) and Email address to identify your account, sync VIP status/quotas, and prevent multi-device abuse.
- **Device & Advertising Identifiers:** Device model, OS version, app version, crash traces, diagnostic logs, and Google Advertising ID (`AD_ID`) for ad delivery and fraud prevention.
- **Usage & Purchase Status:** App feature interactions, daily quota usage, promo code redemptions, and Google Play subscription verification status.

*(The Application does not collect precise GPS location data.)*

---

## 3. Third-Party Services

The Application uses third-party services that have their own Privacy Policies governing data handling:

- [Google Play Services & Google Play Billing](https://www.google.com/policies/privacy/)
- [AdMob](https://support.google.com/admob/answer/6128543?hl=en)
- [Google Analytics for Firebase](https://firebase.google.com/support/privacy)
- [Firebase Crashlytics](https://firebase.google.com/support/privacy/)
- [Firebase Authentication & Cloud Firestore](https://firebase.google.com/support/privacy/)

Data transmitted for authentication, cloud quota synchronization, subscription verification, analytics, crash reporting, and advertising is encrypted in transit via HTTPS/TLS.

---

## 4. Account Deletion & Data Retention Policy {#account-deletion}

In compliance with Google Play's Account Deletion Policy, **AutoSee** provides both in-app and web/email methods to delete your account and associated cloud data:

### Method A: Delete Account Directly Inside the App (Recommended)
1. Open **AutoSee** on your Android device.
2. Open the **Account / VIP Center** dialog from the Home screen.
3. Tap **"Delete Account" (刪除帳號)** and confirm the prompt (you may be asked to re-verify your Google login for security).
4. Your Firebase Authentication account and associated Cloud Firestore user records will be permanently deleted.

### Method B: Request Account Deletion via Email (If You Uninstalled the App)
1. Send an email from your registered Google account email address to **`autosee.support@gmail.com`**.
2. Use the subject line: **`AutoSee Account Deletion Request`**.
3. We will verify ownership and permanently delete your cloud account records within **7 business days**.

### What Data Is Deleted vs. Retained
- **Deleted Immediately / Within 7 Days:** Your Firebase Authentication account (`uid`, email link) and your Cloud Firestore user profile, quota records, and active VIP device session records.
- **Local App Data:** Automation scripts and templates are stored locally on your device and can be removed by clearing app data or uninstalling AutoSee.
- **Retained by Law or Anonymized:** Google Play Billing transaction receipts/invoices are retained by Google in accordance with tax and legal obligations (please note that deleting your AutoSee account does **not** automatically cancel an active Google Play subscription—manage or cancel subscriptions directly in Google Play Store). Aggregated, anonymized crash/analytics telemetry that cannot be linked back to your identity may be retained for service stability.

---

## 5. Children's Privacy

The Application is not directed to anyone under the age of 16. We do not knowingly collect personally identifiable information from children under 16. If you believe a child has provided personal information, please contact **`autosee.support@gmail.com`** so we can promptly delete it.

---

## 6. Security & International Transfers

We value your trust and employ encryption in transit (HTTPS/TLS) and hardware-backed local encryption (`EncryptedSharedPreferences` / Android Keystore) where supported. Third-party cloud providers (such as Google Firebase) may process data on servers located outside your region in accordance with applicable data protection frameworks (including GDPR/CCPA safeguards).

---

## 7. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. Changes will be posted on this page with an updated effective date.

---

## 8. Contact Us

If you have any questions about this Privacy Policy or data deletion requests, please contact **AutoSee Team** at:  
**Email:** autosee.support@gmail.com
