# Klera AI Privacy Policy

_Last updated: 2026-09-29._

Klera AI ("Klera", "we", "the app") is an AI study tool for handwriting math and physics on iPad. This
policy explains what we collect, why, and your choices. We designed the app to collect as little as
possible and to keep your learning data private to you.

## Who this is for
Klera is intended for students **aged 13 and over**, teachers, and parents. It is **not**
directed to children under 13, and we do not knowingly collect personal information from children
under 13. If you believe a child under 13 has provided us data, contact us and we will delete it.

## What we collect
- **Account** — when you sign in with Google (or Apple), we receive your name, email address, and a
  user identifier. We use these to identify your account and secure your data.
- **Learning data** — your handwritten work, per-topic mastery estimates, and behavioral signals the
  app uses to personalize tutoring (e.g. how long you work before asking for help, pen-motion
  patterns such as speed and pressure, help usage, session summaries). This is stored **under your
  account** and used only to adapt the tutoring to you.
- **Content you create** — boards, problems, and (if you use the exam features) exam answers and
  results. To provide AI tutoring, images or text of your current work are sent to our AI providers
  (below) to generate hints, checks, and solutions. If you use the voice tutor, spoken/typed
  messages are processed to produce a response.
- **Diagnostics** — crash and performance diagnostics via Apple's MetricKit, stored on your device.
- **Anonymous usage analytics** — anonymous feature-usage events (for example "a hint was
  requested") that help us improve Klera. These use a random installation identifier, are
  **never linked to your account, name, or email**, and never include your handwriting, problem
  content, or school. You can turn this off any time in Settings → *Share anonymous usage
  analytics*; deleting your data also resets the identifier and stops collection.
  We do **not** use advertising SDKs and we do **not** track you across other apps or websites.

## How we use it
To provide and personalize the tutoring, sync your data across your devices, keep your account
secure, and fix crashes. **We do not sell your personal data and we do not use it for advertising.**

## Who processes it (service providers)
We use these processors solely to run the service; they process data on our behalf:
- **Supabase** — authentication and encrypted storage of your account and learning data.
- **Google / Apple** — sign-in (identity verification).
- **OpenAI** — generating tutoring (hints, mistake checks, solutions) from images/text of your work.
- **ElevenLabs** — text-to-speech for the voice tutor.
- **PostHog (EU-hosted)** — anonymous usage analytics only (see above); never receives your
  identity or content.
Data is transmitted over encrypted (HTTPS) connections.

## Your data is yours (rights)
- **Export** — Settings → Account → *Export my learning data* downloads a JSON copy of your
  learning data (no third-party content).
- **Delete** — Settings → Account → *Delete my learning data* permanently removes your learning
  profile from this device and our cloud. Signing out reverts the app to a local, anonymous state.
- **Access / questions** — contact us (below). Depending on your location you may have additional
  rights under your local data-protection law, such as the GDPR.

## Data security
Access tokens are stored in the device Keychain. Your learning profile is protected by row-level
security so only your signed-in account can read or write it. Data in transit is encrypted.

## Retention
We keep your learning data while your account is active. When you delete it (above) it is removed
from our cloud. Local device data is removed on delete or app uninstall.

We also apply automatic limits so nothing is kept indefinitely by default:

- **Detailed working records** — the per-problem behavioural detail (pen pressure, writing speed,
  pauses and similar signals) is removed after **12 months** without activity. Your topic progress
  is kept, so the tutor still knows you if you come back.
- **Everything else** — a learning profile untouched for **24 months** is deleted in full.
- **On the device** — the app keeps only the last 40 problem records and 7 days of daily activity;
  older detail is discarded as you use it, not archived.

## Early-access waitlist (website)
If you sign up for early access on our website, we store what you enter in the form: your email,
and optionally your name, role, university or school, device, what you study, and an Apple ID email
for TestFlight, together with your consent and the date. We use it only to send you TestFlight
invites and early-access updates, and to record the free year of Premium promised to testers. It is
stored with **Supabase** and is not readable from the website. It is never sold or shared for
marketing. To be removed, email filip@klera.tech and we will delete your entry.

## Children & schools
Where the app is used through a school, the school may act as the data controller for student data;
we act as a processor on the school's behalf. We do not knowingly collect data from children under
13 without appropriate consent.

## Changes
We will update this policy as the app evolves and post the new version at this URL with a revised
date.

## Contact
Klera AI: filip@klera.tech or darius@klera.tech
