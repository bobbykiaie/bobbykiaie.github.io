---
layout: page
title: Privacy Policy
permalink: /privacy/
---

# Set by Set Privacy Policy

Effective date: August 3, 2026

Set by Set is a strength-training planning and workout-tracking app. This policy explains what data the app accesses, how it uses that data, and the choices available to you.

## Data Set by Set Handles

Set by Set can store routines, custom exercises, training preferences, completed workouts, exercise notes, repetitions, weights, RPE or RIR, rest times, progress records, and derived per-set cardio-response information you create in the app. If you enable iCloud sync, routines, custom exercises, your active-routine choice, and exercise-library edits can sync through your private iCloud account. Workout history, exercise progress, notes, effort ratings, heart-rate information, and connected-health summaries remain stored locally on your device and are not synced through iCloud.

If you choose to connect Apple Health, Set by Set can read the recent health and fitness categories shown in Apple's permission sheet: steps, active energy, sleep, resting heart rate, heart-rate variability, workouts, and date of birth. Date of birth is used only to estimate maximum heart rate for training-zone displays. With separate permission, Set by Set can write completed strength workouts to Apple Health. Set by Set reduces the records it reads to short daily summaries for in-app fitness features.

During an active workout, you may optionally stream heart rate from the Set by Set Apple Watch companion or a nearby device that exposes the standard Bluetooth Heart Rate Service, such as a compatible Fitbit device or chest strap. Live samples are processed on device to show BPM and attribute a cardio response to each set. A compact per-set trace and summary can be stored with your local workout history; the full live stream is discarded when the session ends. Bluetooth device names and readings are not sent to the developer.

This public Release does not offer Google sign-in or Google Health access. Google Health support is hidden and inactive while its restricted OAuth scopes await production verification. The binary still contains Google Sign-In components for development compatibility. Google Sign-In's signed privacy manifest states that, if invoked in a future release, the SDK may collect account contact information, user and device identifiers, coarse location, usage data, and other authorization-related data for app functionality and analytics. Set by Set does not invoke that flow in this Release and does not use those categories for advertising or tracking.

## Purchases and Subscriptions

Set by Set Pro is sold through Apple's In-App Purchase system. Apple processes the payment and
tells Set by Set only whether an active entitlement exists — the developer never receives your
name, card details, billing address, or Apple Account credentials, and has no access to them.

The app stores a single local flag recording whether Pro is active, so paid features keep working
without a network connection. That flag stays on your device; it is not part of the app's iCloud
sync and is not sent to the developer.

Purchase history, refunds, and subscription management are handled by Apple. See Apple's Privacy
Policy for how Apple handles payment information.

## How Data Is Used

Set by Set uses the data you provide to display your routines and history, calculate progress and training-volume views, create explainable next-session recommendations, and provide features you explicitly request. Connected health data is used only for fitness and wellness context after you opt in.

Set by Set does not sell personal information or health data, use health data for advertising, or share health data with data brokers.

Set by Set uses Apple platform services only for the functions you choose. Integrated providers are required by their applicable terms and platform protections to safeguard data consistently with the disclosures in this policy. Set by Set does not provide health or workout records to advertising or analytics providers.

## AI Features

On supported Apple devices, Set by Set can use Apple Foundation Models to answer coaching questions, parse routine documents, and help create or refine plans. Deterministic app features remain available without AI. When you separately enable health-aware coaching, Set by Set uses only a compact seven-day summary and forces the request to the on-device Apple model. Raw HealthKit samples and live heart-rate readings are not included in that AI request.

When Apple Intelligence is available, this release uses Apple's on-device Foundation Model. Coach and other model-backed entry points are hidden when the system model is unavailable. Set by Set does not operate an AI server or retain model prompts on a developer-controlled server.

## Data Retention and Deletion

You can delete individual workouts and routines in Set by Set or delete the app to remove its local data. You can disable Apple Watch heart-rate tracking in the heart-rate connection menu, disconnect a Bluetooth sensor, and change or revoke Apple Health permissions in the Health app or iOS Settings. Locally stored Apple Health summaries are removed when the app is deleted. Content previously synced through iCloud is managed through your Apple account and Apple's iCloud controls.

## Security and Transfers

Set by Set uses platform security features such as app sandboxing, Keychain-backed authorization managed by integrated providers, and private iCloud storage. Internet transfers to Apple use encrypted connections. The inactive Google components in this release do not expose a public sign-in flow; any future enabled provider connection will use encrypted transport. No security method is perfect, but Set by Set is designed to minimize data sent off the device.

## Children

Set by Set is not directed to children under 13 and does not knowingly collect personal information from children.

## Fitness, Not Medical Advice

Set by Set provides general fitness and wellness information. It does not diagnose, treat, cure, or prevent any disease or medical condition and is not a regulated medical device. Consult a qualified professional about pain, injury, or medical concerns.

## Changes

This policy may be updated when Set by Set's features or legal requirements change. The effective date above will identify the current version.

## Contact

For privacy or support questions, contact [bobbykiaie@gmail.com](mailto:bobbykiaie@gmail.com).
