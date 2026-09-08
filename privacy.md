---
title: Holdback — Privacy Policy
permalink: /privacy
---

Last updated: 8 September 2026.

# Privacy policy — Holdback

Effective 8 September 2026.

Developer: LPJ Incorporated, Crown Point, Indiana, United States.
App: Holdback (`com.lpj.holdback`) on Google Play.
Contact: boban.kostadinoski@gmail.com

This is the same policy the app shows under Settings → Privacy & error log: nothing leaves your phone.

## What Holdback is

Holdback is a money and rate-con tool for owner-operators. You type settlements, bills, and costs. You can check a rate confirmation PDF on the phone. The books live in SQLite on this device.

## No account. No bank login. No analytics

Holdback does not create an account.
Holdback does not log into a bank.
Holdback does not run analytics, ads, or crash reporters that send data to us.

## Where your numbers live

Settlements, deductions, miles, work costs, life bills, nights out, tax holdback percent, savings percent, reminders, rate-con checks, and attached photos or PDFs stay in app storage on the phone.

Holdback does not operate a server for this app. We do not receive your settlements, your rate cons, or your photos.

## Network

Grep of app source (`src/**/*.ts`, `src/**/*.tsx`) at tree `356674c`: no `fetch(`, no `XMLHttpRequest`, no `WebSocket(`, no `axios`.

There is **no network call** in the shipping app.

Reminders are scheduled on the device (`src/notifications/schedule.ts`). They do not use a push token.

Share, backup, year-end pack, and “Send the error log” open the Android share sheet. The file goes where **you** pick (Drive, Messages, Files). It does not go to LPJ Incorporated unless you send it to us.

Fonts ship inside the APK. They are not downloaded.

Google Play Billing is not wired. Restore purchases on the paywall is an in-app toast. When billing ships (task T8), this policy will name that one Google Play purchase/restore call and nothing else.

## Camera, photos, and files

Holdback may use the camera or photo library so you can attach a settlement sheet or a receipt. Those files stay on the phone unless you share them.

You can share a PDF from Gmail or Messages into Holdback. Holdback copies the file into app storage and reads it on the device.

## Error log

If something breaks, Holdback writes one local line: which screen, and what broke. Never a dollar amount, never a name. You can send that file through the share sheet, or clear it.

## Children

Holdback is built for working drivers. It is not directed at children.

## Changes

If this policy changes, the date at the top changes and the in-app Privacy screen stays the source you can read without a network.

## Contact

Questions: boban.kostadinoski@gmail.com
LPJ Incorporated, Crown Point, Indiana, United States.
