---
title: Carvesense Privacy Policy
layout: page
description: What Carvesense keeps on your iPhone, what Full Coaching sends, and what our server keeps.
---

# Carvesense Privacy Policy

*Effective 1 October 2026*

**In short:**

- Your surf videos are analysed entirely on your iPhone and are never uploaded.
- Quick Take coaching runs on your iPhone too. Data only leaves your phone when you use Full Coaching, buy credits, or the app checks your credit balance.
- We don't use advertising, analytics or tracking, and we never sell your data.
- You can export or delete everything the app stores from Settings.

## Who we are

Carvesense is an iOS app made by David Stubbs, an independent developer. In this policy, "we" means the developer and "the app" means Carvesense.

## Data that stays on your device

You choose which clips to analyse. The app measures your rides (for example ride length, speed, knee bend and pop-up) on your iPhone. Your videos, and the sessions, metrics, coaching notes and practice plan the app creates from them, are stored only on your device. We can't see any of it.

Quick Take coaching, including automatic coaching after import, is generated on your iPhone and never sent anywhere.

## Data sent for Full Coaching

Full Coaching only runs when you ask for it. When it does, the app sends our coaching server:

- **Ride measurements** for that one wave: the numbers the app calculated, the clip's length and resolution, and the session details shown in the app (date, venue, wave size and direction). Your other waves aren't sent.
- **Still frames from the clip.** A few wide frames of the whole clip, so the coach can see the wave and where you are on it, and close-ups cropped around you about every third of a second through the ride, combined into a handful of filmstrip images. The full video is never sent. If the clip is no longer on your phone, only the measurements are sent.
- **A random install identifier** that the app creates. It isn't linked to your name, email, Apple ID or advertising identifier. We use it to keep track of your coaching credits and daily coaching limit.

Our server passes the measurements and frames to Anthropic, which provides the AI model that writes your coaching. Anthropic processes the data under its commercial API terms, which don't allow it to train models on that data. The coaching text then comes back to your phone.

## What our server keeps

- **Coaching responses** are cached for up to 30 days, so analysing the same ride again doesn't need a second AI request. The cache stores the response text and a one-way hash of the request. It doesn't store your images or your install identifier.
- **Usage and cost records:** for each AI request we log the time, the model used, token counts and cost. These records contain no ride data or identifiers.
- **Credit records:** your install identifier and credit balance, plus, for each purchase, the App Store transaction ID, the product bought and the date, and any credits we add by hand when helping with a support request. We keep these so credits aren't lost or applied twice.
- **Rate-limit counters:** a daily count of coaching requests for each install (stored as a one-way hash of the identifier) and overall, used to prevent abuse.
- **Server logs:** like most web servers, ours may record IP addresses and request times for security and troubleshooting, and an error message can include the install identifier. These logs are kept only for a short time.

## Checking your credit balance

When the app starts, and when you open the credits page, it asks our server for your balance. That request carries only the random install identifier.

## Purchases

Coaching credits are bought through Apple's App Store. Apple handles payment, and we never see your name, Apple ID or payment details. The app sends our server Apple's signed transaction record so we can add the credits to your balance.

## What we don't do

- We don't include advertising, analytics or third-party tracking SDKs.
- We don't track you across other apps or websites.
- We don't sell or rent data, or share it except as described above.
- We don't ask for your name, email or location.

## Your choices and rights

- **Export:** Settings › Export my data saves everything the app stores (except videos) as a JSON file.
- **Delete:** Settings › Delete all data erases the app's data from your phone. Deleting the app also removes it.
- **Server data:** to have your credit record deleted, email us. Because the identifier is random, you'll need to tell us roughly when you made purchases so we can find it. Deleting it also deletes any unused credits.

Depending on where you live, for example in the UK or EU, you may have rights to access, correct, delete or object to the processing of your personal data, and to complain to your data protection authority. Email us to use any of these rights.

## Children

Carvesense isn't directed at children under 13, and we don't knowingly collect personal data from them.

## Changes

If this policy changes, we'll update this page and the effective date above. If a change is significant, we'll also point it out in the app.

## Contact

Questions or requests: [davestubbs@hotmail.com](mailto:davestubbs@hotmail.com)

[Support](../support/) · [Home](../)
