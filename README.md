# 🍎 iPhone Messages and AI Privacy: Siri, Apple Intelligence, ChatGPT and iCloud

![iPhone](https://img.shields.io/badge/iPhone-iOS%2026%20%7C%2027-000000?logo=apple&logoColor=white)
![Type: privacy guide](https://img.shields.io/badge/Type-privacy%20guide-d73a49)
![Covers: Siri, ChatGPT, iCloud](https://img.shields.io/badge/Covers-Siri%20%7C%20ChatGPT%20%7C%20iCloud-5c2d91)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

**📄 [Download the PDF](iPhone-Messages-AI-Privacy.pdf)**

## 📖 Overview
This is the iPhone companion to [Gemini and Your Android Messages](https://github.com/ImmuneMoon/Android-Gemini-Messages-Privacy). It covers the same concern: what AI features and the cloud can see of your messages, and which settings control it.

The answer is different on an iPhone. Apple's AI mostly works on the device, and ChatGPT is switched off until you turn it on. The bigger privacy question is **iCloud**: under Apple's default settings, a copy of the key to your messages can sit in your iCloud backup. This guide covers Siri, Apple Intelligence, the ChatGPT extension, analytics, iCloud and Advanced Data Protection, and how iPhone and Android messages are protected.

There's no video behind this guide. Everything comes from Apple's own documentation, listed in Sources.

## ⚠️ Important Notes
* **Menu names depend on your iOS version.** Apple calls the main AI settings **Siri** on some versions and **Apple Intelligence & Siri** on others. This guide gives both where Apple does.
* **Advanced Data Protection can lock you out.** With it on, Apple can't recover your data. Set up a recovery contact or recovery key, and keep it safe (Section 5).
* **Advanced Data Protection isn't available to new users in the UK.** See Section 5.

## 🚀 How to Use
Download the PDF above, or read on below. **The Short Version** lists the settings. Section 5 has the biggest effect on who could read your messages.

Texting people with Android phones? See [Gemini and Your Android Messages](https://github.com/ImmuneMoon/Android-Gemini-Messages-Privacy).

---

<!-- guide:start -->

## The Short Version

- **ChatGPT:** it's off by default. If you turned it on, switch it off under **Settings** ▸ **Siri** (or **Apple Intelligence & Siri**) ▸ **ChatGPT** (Section 2).
- **Siri learning from Messages:** turn off **Learn from this App** for Messages (Section 3).
- **Sharing recordings and analytics with Apple:** check **Settings** ▸ **Privacy & Security** ▸ **Analytics & Improvements** (Section 4).
- **Who could read your messages in iCloud:** turn on **Advanced Data Protection**, or turn off iCloud Backup (Section 5).
- **Which messages are encrypted:** iMessage always is, RCS can be, and SMS never is (Section 6).

## Contents

1. [How Apple Intelligence Handles Your Data](#1-how-apple-intelligence-handles-your-data)
2. [The ChatGPT Extension](#2-the-chatgpt-extension)
3. [Stop Siri Learning From Messages](#3-stop-siri-learning-from-messages)
4. [What You Share With Apple](#4-what-you-share-with-apple)
5. [Your Messages in iCloud](#5-your-messages-in-icloud)
6. [iMessage, RCS and SMS](#6-imessage-rcs-and-sms)
7. [Quick Checklist](#7-quick-checklist)
8. [Sources](#8-sources)

---

## 1. How Apple Intelligence Handles Your Data

Apple says **Apple Intelligence** handles many requests **on your iPhone** itself. Larger requests go to **Private Cloud Compute**, Apple's servers for AI. Apple says only the data needed for the request is sent, and that it's used only for that request and never stored or made accessible to Apple.

Apple also says smart suggestions in Messages are worked out on your device.

That's the main contrast with Gemini on Android, where Google keeps chats for at least 72 hours and some are reviewed by people. See [Gemini and Your Android Messages](https://github.com/ImmuneMoon/Android-Gemini-Messages-Privacy#4-turn-off-keep-activity).

---

## 2. The ChatGPT Extension

ChatGPT is a separate service from OpenAI that Apple Intelligence can pass requests to. According to Apple:

- **It's off by default.** Nothing goes to ChatGPT until you turn it on.
- **You're asked before anything is shared,** unless you turn that confirmation off.
- **What's sent:** your request and anything you attach, plus limited details such as your time zone, country, device type and language. Your IP address is hidden from OpenAI, but your general location is shared.
- **Without a ChatGPT account,** OpenAI may only use your request to answer it. It mustn't store requests or use them to train its models, unless the law requires it to keep them.
- **Signed in to a ChatGPT account,** OpenAI's own settings and privacy policy apply. It may keep your requests and use them to train its models.

**To turn it off:**

1. Open **Settings** and tap **Siri** (called **Apple Intelligence & Siri** on some versions).
2. Tap **ChatGPT**, then turn off **Use ChatGPT**.
3. To stop Siri suggesting ChatGPT, also turn off **Setup Prompts**.

On iOS 27 with the new **Siri AI (Beta)**, it's **Settings** ▸ **Siri** ▸ **Extensions** ▸ **ChatGPT** ▸ **Use Extension**.

If you keep ChatGPT on, check that **Confirm Requests** stays on, so you're asked each time. On some versions it's called **Confirm ChatGPT Requests**.

---

## 3. Stop Siri Learning From Messages

Siri can learn how you use each app, to make suggestions. Apple's instructions use the Health app as their example:

1. Open **Settings**, scroll down and tap **Apps**, then tap the app.
2. Tap **Siri** or **Apple Intelligence & Siri**.
3. Turn **Learn from this App** off.

To do the same for Messages, tap **Messages** in step 1. Apple's page only shows the Health app, so if your Messages page doesn't have this option, it doesn't apply on your iOS version.

---

## 4. What You Share With Apple

Both of these settings are in the same place: **Settings** ▸ **Privacy & Security** ▸ **Analytics & Improvements**.

### 4.1 Improve Siri & Apple Intelligence

On newer versions it's called **Improve Siri & Apple Intelligence**. On older ones, it's **Improve Siri & Dictation**. Apple describes it as optional, and asks during setup or the first time you use Siri, Dictation or Translate.

When it's on, Apple says it may store your interactions with Siri and Dictation, **including audio recordings and transcripts**, and that people at Apple may review a sample. Apple says:
- the data is tied to a **random identifier** that changes several times an hour, not to your Apple Account;
- it may be kept for **up to two years**, and a reviewed sample may be kept longer.

Turn it off on the page above if you don't want to share recordings.

### 4.2 Share iPhone Analytics

This sends Apple diagnostic and usage information, which Apple says it collects anonymously. On the same page, turn off **Share iPhone Analytics**. It's labelled **Share iPhone & Watch Analytics** if you have an Apple Watch.

---

## 5. Your Messages in iCloud

This is the setting with the biggest effect on who could read your messages.

**iMessage is always end-to-end encrypted while messages are being sent.** What matters is how they're stored afterward, in iCloud:

| Your settings | Can Apple access your messages in iCloud? |
|---|---|
| **Messages in iCloud on, iCloud Backup on, standard protection** (the default) | **Yes, in principle.** Apple holds the keys to your backups, and the backup includes a copy of the key to your Messages in iCloud |
| **Messages in iCloud on, iCloud Backup off** | **No.** Messages in iCloud is end-to-end encrypted, and Apple doesn't store its key |
| **Advanced Data Protection on** | **No.** Messages in iCloud and iCloud Backup are both end-to-end encrypted |

### 5.1 Turn on Advanced Data Protection

**Advanced Data Protection** extends end-to-end encryption to most of your iCloud data. Apple says it raises the number of protected data categories from 15 to 25, including iCloud Backup.

**Before you start:**
- Your Apple Account needs **two-factor authentication**, and your iPhone needs a **passcode**.
- All your devices need recent software. For iPhone, that's **iOS 16.2 or later**.
- Child accounts and Managed Apple Accounts can't use it.

**Turn it on:**

1. Open **Settings**, tap your **name**, then tap **iCloud**.
2. Scroll down, tap **Advanced Data Protection**, then **Turn on Advanced Data Protection**.
3. Follow the steps to set up a **recovery contact** or a **recovery key**, a 28-character code.

**Before you turn it on:**
- **Keep your recovery key safe.** Apple can't recover your data for you once it's on.
- **It applies to your whole account,** on every device.
- **It turns off iCloud.com web access by default.**

> **United Kingdom:** Apple stopped offering Advanced Data Protection to **new** UK users in 2025, and said existing UK users would need to turn it off. Apple says iMessage and FaceTime stay end-to-end encrypted in the UK. Elsewhere, Advanced Data Protection is still available.

---

## 6. iMessage, RCS and SMS

Your iPhone uses three kinds of messages:

| Type | Bubble | End-to-end encrypted? |
|---|---|---|
| **iMessage** (iPhone to iPhone) | Blue | **Yes,** always. A lock icon shows at the top |
| **RCS** (usually to Android) | Green | **Sometimes.** From **iOS 26.5**, as a beta, if both people's carriers support it. Encrypted chats show **Encrypted** with a lock icon |
| **SMS / MMS** | Green | **No** |

RCS on iPhone needs **iOS 18** and a carrier plan that supports it.

**Texting someone with an Android phone?** Look for the lock icon, rather than assuming. Google's Android guidance says encrypted RCS needs both people on supported apps. Apple's says it depends on both people's carriers. The Android side is covered in [Gemini and Your Android Messages](https://github.com/ImmuneMoon/Android-Gemini-Messages-Privacy#7-which-of-your-messages-are-encrypted).

---

## 7. Quick Checklist

- [ ] ChatGPT extension off, or **Confirm Requests** left on
- [ ] **Learn from this App** off for Messages, where it's offered
- [ ] **Improve Siri & Apple Intelligence** (or **& Dictation**) off, if I don't want to share recordings
- [ ] **Share iPhone Analytics** off, if I prefer
- [ ] **Advanced Data Protection** on, with a recovery key or contact set up, or iCloud Backup off
- [ ] Look for the lock icon in conversations with Android users

---

## 8. Sources

**Apple Intelligence and ChatGPT**
- [Apple Privacy](https://www.apple.com/privacy/)
- [Apple Intelligence](https://www.apple.com/apple-intelligence/)
- [Turn on ChatGPT on iPhone](https://support.apple.com/guide/iphone/use-chatgpt-with-apple-intelligence-iph00fd3c8c2/ios)
- [ChatGPT Extension & Privacy](https://www.apple.com/legal/privacy/data/en/chatgpt-extension/)

**Siri and analytics**
- [Turn Siri's access to your Health app data on or off ("Learn from this App")](https://support.apple.com/en-us/118493)
- [Turn Improve Siri & Apple Intelligence or Improve Siri & Dictation on or off](https://support.apple.com/en-us/127070)
- [Improve Siri and Dictation & Privacy](https://www.apple.com/legal/privacy/data/en/improve-siri-dictation/)
- [Share analytics, diagnostics, and usage information with Apple](https://support.apple.com/en-us/108971)

**iCloud and Advanced Data Protection**
- [iCloud data security overview](https://support.apple.com/en-us/102651)
- [How to turn on Advanced Data Protection for iCloud](https://support.apple.com/en-us/108756)
- [Advanced Data Protection in the United Kingdom](https://support.apple.com/en-us/122234)

**Messages**
- [iMessage, RCS and SMS/MMS](https://support.apple.com/en-us/104972)

<!-- guide:end -->

## ☕ Support the Project

If you find this project helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)

---
© 2026 Fulllion Creative Works. All rights reserved.
