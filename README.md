# Privacy Policy for **Bible Quiz Quest**

*Effective date: August 29 2026*

---

## 1. Introduction

**Bible Quiz Quest** (the “App”) is a mobile application built with React Native / Expo that provides multiple‑choice Bible quiz questions and optional voice‑answer input. This Privacy Policy explains how we (Greason Tech Solutions) collect, use, store, and protect the personal information of our users (“you” or “your”).

---

## 2. Information We Collect

| Category | What we collect | How it is collected |
|----------|----------------|---------------------|
| **User‑provided data** | • Answers to quiz questions (selected option, voice recording)\n• Optional profile name (if you choose to create one) | Directly entered via the app UI or captured through the microphone when you use the voice‑answer feature. |
| **Device & usage data** | • Device model, OS version, expo‑constants (e.g., app version, bundle identifier)\n• Crash reports, performance metrics | Automatically via Expo’s built‑in analytics and the React Native runtime. |
| **Authentication / session data** | • Supabase user ID (UUID)\n• Temporary access tokens stored in `expo-secure-store` | Issued by Supabase after you sign in with your email/password or social provider. |
| **Network data** | • IP address (transient, for request routing)\n• Referrer header for API calls | Sent with each HTTPS request to Supabase or Expo services. |

> **Note:** The App does **not** collect location data, contacts, calendar, or any other personally identifiable information unless you explicitly provide it.

---

## 3. How We Use Your Information

1. **Quiz functionality** – To present questions, evaluate answers, and track your progress (score, completed stages).
2. **Voice recognition** – To transcribe your spoken answer via Expo Speech Recognition; recordings are processed locally and are **not** stored on our servers.
3. **User account management** – Supabase stores your user ID, email (if you sign‑up), and quiz progress securely.
4. **Security** – Tokens stored in `expo-secure-store` protect your session and prevent unauthorized access.
5. **Diagnostics & analytics** – To improve stability and performance, we may collect anonymized usage statistics.

---

## 4. Data Sharing & Disclosure

- **Supabase** – Your quiz progress and authentication data are stored in Supabase (hosted on `https://mvkjqpzgvwzwitcdgtzx.supabase.co`). Supabase’s own privacy policy governs that storage.
- **Third‑party services** – The App uses Expo’s services (e.g., `expo-doctor`, `expo-updates`) which may receive minimal, non‑personal data required for building and updating the app.
- **Legal requirements** – We will disclose information if required by law or to protect our rights.

We do **not** sell, trade, or otherwise share your personal data with advertising networks or unrelated third parties.

---

## 5. Data Retention & Deletion

- **Supabase records** – Retained until you delete your account or request removal. You can delete your account via the app’s settings; this triggers a deletion request to Supabase.
- **Local data** – Tokens stored in `expo-secure-store` are cleared when you uninstall the app or manually clear app data.
- **Voice recordings** – Processed in‑memory only; no files are persisted.

---

## 6. Security Measures

- All network traffic uses **HTTPS**.
- Access tokens are stored in **secure enclave** via `expo-secure-store`.
- Supabase employs standard PostgreSQL security practices (encryption at rest, row‑level security).
- Regular dependency updates (SDK 57) mitigate known vulnerabilities.

---

## 7. Children’s Privacy

The App is **not directed** at children under 13 years of age. We do not knowingly collect personal data from children. If we become aware of such data, we will delete it promptly.

---

## 8. Your Rights

- **Access & correction** – You may view and edit your profile information within the app.
- **Deletion** – You can delete your account, which removes all associated data from Supabase.
- **Export** – You may request a copy of your quiz progress by contacting us.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted within the app and on the hosted page with an updated effective date.

---

## 10. Contact Information

If you have questions or concerns about this Privacy Policy, please contact us at:

**Email:** zazikhetha@gmail.com

---

*This document is provided as a draft. Replace placeholder contact details and the URL where you will host the final version.*
