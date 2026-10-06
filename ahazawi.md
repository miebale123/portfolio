# Ahazawi: offline-first mobile learning

- **Company:** Ahaz Platforms PLC, selected for the first Ethiopian cohort of the Mastercard Foundation EdTech Fellowship
- **Role:** Junior Software Developer. I owned the app's offline architecture.
- **When:** January – July 2026
- **Stack:** React Native, Laravel, Cloudflare R2
- **Live:** [Google Play](https://play.google.com/store/apps/details?id=com.ahazawi.app), 6,500+ learners

**In short:** Many Ahazawi learners use older Android phones, live where the internet is unreliable, and cannot afford regular mobile data. I built what lets them download a course and keep learning offline: encrypted local media, resumable background downloads, and progress sync that stays consistent whether a lesson is finished offline or online.

## The problem

- **Connectivity.** Many learners have no connection, or a slow and expensive one. An app that streams every lesson does not work for them.
- **Devices.** Most learners own older, low-end Android phones.
- **Paid content.** Courses are paid, and phones are often shared or rooted, so downloaded videos must not be copyable to another device.

## What I built

- **Resumable background downloads.** Lessons download in the background and continue after a dropped connection instead of starting over.
- **Offline progress sync.** A learner's progress stays consistent whether a lesson is finished offline or online.
- **Content protection.** Downloaded media is encrypted with AES-GCM using device-bound keys, so it cannot be extracted or copied to another device.
- **Support for older phones.** I extended compatibility to older Android versions and low-end devices instead of targeting only current hardware.
- **Instant lesson switching.** The app preloads the next lesson's media, which cut lesson-switch time to under 0.5 seconds, so playback starts immediately instead of buffering on a slow connection.

## Result

The app is live on Google Play with more than 6,500 learners, who can complete a course on a low-cost phone without a data plan.
