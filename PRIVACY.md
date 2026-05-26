# GridBurst — Privacy Policy

**Effective date:** 2026-05-23
**Version:** 2.2

This Privacy Policy ("Policy") describes how the publisher of the GridBurst mobile application ("App", "Service", "we", "us", "our") collects, uses, discloses, retains, and protects information in connection with your use of the App. This Policy forms part of, and is incorporated by reference into, the GridBurst Terms of Service ("Terms"). Capitalized terms used but not defined here have the meanings given in the Terms.

This Policy is designed to comply, to the maximum extent applicable, with:

- the European Union General Data Protection Regulation (Regulation (EU) 2016/679) ("GDPR");
- the United Kingdom General Data Protection Regulation and Data Protection Act 2018 ("UK GDPR");
- the California Consumer Privacy Act of 2018, as amended by the California Privacy Rights Act of 2020 ("CCPA/CPRA");
- the Virginia Consumer Data Protection Act, Colorado Privacy Act, Connecticut Data Privacy Act, Utah Consumer Privacy Act, Texas Data Privacy and Security Act, and other U.S. state privacy laws as enacted;
- Brazil's Lei Geral de Proteção de Dados (Law No. 13.709/2018) ("LGPD");
- Canada's Personal Information Protection and Electronic Documents Act ("PIPEDA") and Quebec Law 25;
- Australia's Privacy Act 1988 (Cth);
- the U.S. Children's Online Privacy Protection Act ("COPPA");
- the Apple App Store Review Guidelines (including App Tracking Transparency); and
- the Google Play Developer Program Policies (including the Data Safety section).

**BY DOWNLOADING, INSTALLING, OR USING THE APP YOU ACKNOWLEDGE THAT YOU HAVE READ AND UNDERSTOOD THIS POLICY.** If you do not agree, do not use the App and uninstall it from your device.

---

## 1. Data Controller and Contact

The data controller (GDPR/UK GDPR) and "business" (CCPA/CPRA) responsible for processing personal data described in this Policy is the publisher identified in Section 22 of the Terms ("**Publisher**"). The Publisher alone determines the purposes and means of processing.

The persons who originally conceived, designed, and developed the App (the "**Creator**" and, with their respective affiliates, employees, contractors, and licensors, the "**Developer Parties**") are **not** data controllers, joint controllers, processors, or sub-processors of personal data described in this Policy and have no role in determining the purposes and means of processing. The Developer Parties do **not** receive personal data about you in identifiable form. Any data-subject request or complaint must be directed to the Publisher.

For all privacy questions, data-subject requests, or complaints:

- **Email:** privacy@gridburst.app

EU/EEA users may contact the Publisher at the same address as our representative point of contact for GDPR purposes. We will respond within statutory timeframes (typically 30 days under GDPR/UK GDPR, 45 days under CCPA/CPRA, subject to permitted extensions).

## 2. Scope

This Policy applies to data processed in connection with the App and the optional features it offers (leaderboard submission to Apple Game Center / Google Play Games, rewarded video advertisements via Google AdMob, telemetry as described in Section 3.5, and in-app purchases processed by Apple or Google). It does **not** apply to:

- the Apple App Store, Google Play Store, Apple Game Center, Google Play Games, Apple iCloud, or Google Drive — each is governed by its operator's own privacy policy;
- third-party websites linked from the App; or
- advertising networks beyond Google AdMob.

We are not responsible for the privacy practices of any third party.

**No own backend today.** As of the Effective Date, we do not operate any backend server, database, account system, custom leaderboard, sync service, or analytics warehouse of our own. The App is a self-contained client that talks only to: (i) Apple and Google native services (App Store, Game Center, Play Games, IAP, OS-level diagnostics), (ii) Google AdMob and Google's User Messaging Platform for the voluntary rewarded-ad flow, (iii) a public static site (hosted on GitHub Pages) for serving the current version of these legal documents, and (iv) any Telemetry processor we later enable as described in Section 3.5. If we add an own backend at a later date, this Policy will be updated and re-presented before that processing begins.

## 3. Categories of Data

We collect only the data described in this Section. We do **not** collect any other category of personal data.

### 3.1 Data stored locally on your device only

The following data is written to local storage on your device (e.g., `localStorage`, app sandbox files) and is **never transmitted** to us except as described in Section 3.2:

- game progress, current grid state, score, level, combo streak;
- high scores, lifetime statistics, achievement progress and unlock state;
- Daily Challenge best score, streak, and history;
- settings and preferences (sound, haptics, theme, classic-timer toggle);
- install timestamp, welcome-window state, daily try counter;
- In-App Purchase entitlement flags (e.g., whether Daily Plus is active);
- Terms of Service version and acceptance timestamp; and
- locally-generated random identifiers (UUID) used solely on-device.

This data persists until you uninstall the App or clear its data via your operating system.

### 3.2 Data transmitted to third-party platform leaderboards

**We do not operate our own backend server today.** The App's leaderboard feature is provided entirely through Apple Game Center (iOS / iPadOS) and Google Play Games (Android). When your device is signed into one of those services and you complete a Daily Challenge, the App calls the platform's native API to submit your **numeric daily best score** for that day's leaderboard ID. The submission goes **directly from your device to Apple or Google**, not to us. We do not see your real name, email address, platform account ID, IP address, or device advertising identifier as a result of that submission.

What is sent to the platform:

- the numeric Daily Challenge score and submission timestamp;
- the leaderboard identifier the score is being submitted to (e.g., `daily_score_v1`);
- whatever device, account, and network metadata Apple or Google itself attaches to a platform-API call. The amount and content of that metadata is determined by Apple and Google and is governed by their respective privacy policies; we do not control it and we do not receive it.

**How to opt out.** Because submission happens automatically when your device is signed into Game Center / Play Games, the way to opt out is to sign out of (or never sign into) those services for the App at the operating-system level:

- **iOS / iPadOS:** Settings → Game Center → toggle off, or Settings → Game Center → tap the App row and disable.
- **Android:** Settings → Google → Play Games → manage account.

When you are signed out of the platform service, the App's submission call fails silently and no score is sent. Single-player functionality is unaffected. Local scores remain on-device as described in Section 3.1.

If we later add our own backend (for example, a custom global leaderboard, account system, or cross-device sync), we will update this Policy, present the changes inside the App on next launch, and obtain any consent required by applicable law before any new transmission begins.

### 3.3 Data received from your platform

- **In-App Purchase receipts** are issued by Apple or Google for purchase validation and entitlement grants. Receipts are processed transiently and may be cached locally on your device; we do not store payment card numbers, billing addresses, or other payment instruments, and we do not transmit receipts to any backend we operate.
- If you are signed into Apple Game Center or Google Play Games, the platform may make your opaque player identifier and, with your separate consent given to the platform, a display name available to the App's runtime. Any such identifier or display name shown to other players (for example, on the platform leaderboard) is rendered and stored by Apple or Google, not by us.

### 3.4 Data processed by Google AdMob (advertising)

When you voluntarily tap a "Watch ad" button to earn an in-game retry, the App requests a rewarded video advertisement from Google AdMob (operated by Google LLC and/or its affiliates). To serve, measure, and report on that advertisement, AdMob may collect or process:

- a device-specific advertising identifier (IDFA on iOS, AAID on Android), **only where allowed by the operating system and only with your consent** (on iOS, this requires you to grant the App Tracking Transparency prompt; on Android, the AAID is governed by your Google Account settings);
- coarse, non-precise location inferred from your IP address (city or region level);
- general device and network diagnostics (device model, OS version, language, connection type);
- ad-interaction events (whether the ad was viewed to completion, clicked, or closed); and
- a consent signal generated by the in-app GDPR/CCPA consent dialog presented to applicable users before the first ad request.

AdMob's processing is governed by Google's privacy policy and policies for advertising:
- https://policies.google.com/privacy
- https://policies.google.com/technologies/ads
- https://support.google.com/admob/answer/6128543

We display only **rewarded video advertisements**, only when you voluntarily request them. We do **not** display banner ads, interstitial ads, native ads, or unsolicited advertisements of any kind. We do **not** use AdMob's audience-segmentation or remarketing features.

### 3.5 Telemetry, analytics, and diagnostics

The App may, now or in future versions, collect telemetry, analytics, performance, and crash-reporting data ("**Telemetry**") to understand how the App is installed, opened, used, and closed; to measure feature engagement, session length, and retention; to identify crashes, errors, and performance issues; to detect fraud and abuse; to measure monetization effectiveness; to run A/B tests; to operate, secure, and improve the App; and to comply with legal or platform requirements.

**Categories of Telemetry that may be collected:**

- App version and build, operating-system name and version, device model, language, region, screen size and orientation, free memory and storage, connection type.
- App lifecycle events (install, first launch, open, foreground, background, close, crash, force-quit) and timestamps.
- Feature events (mode selected, game started or ended, score, IAP screen viewed, button tapped, ad requested, ad watched, setting changed).
- Error reports and crash stack traces (which may incidentally include filenames and code symbols but exclude content data and personal identifiers we do not collect).
- Request and response timings for online features (leaderboards, ad fetch).
- A randomly-generated opaque "installation identifier" used solely to deduplicate events; not linked to your real identity.

**Categories of Telemetry that are NOT collected:** the content of any communications, real name, email address, phone number, postal address, payment-instrument data, precise geolocation, contacts, photos, calendar, microphone or camera content, or any data the App has not been granted permission to access.

**Third-party processors that may handle Telemetry on the Publisher's behalf** (each acting as a processor under the Publisher's documented instructions): Apple App Analytics, Google Play Console reporting, Firebase, Google Analytics for Firebase, Sentry, Crashlytics, AppsFlyer, Adjust, Mixpanel, Amplitude, PostHog, or a successor service. The specific set of providers in use at any given time may change; the **current** set is available on request at privacy@gridburst.app and, where required by platform policy, is also disclosed in the App Store "Privacy Nutrition Label" and the Google Play "Data Safety" form for the App.

**Legal basis (GDPR/UK GDPR):** Where Telemetry is strictly necessary to provide the Service or to detect fraud or security incidents, the Publisher relies on legitimate interests (Art. 6(1)(f)) and on performance of a contract (Art. 6(1)(b)). Where applicable law requires consent (for example, where Telemetry involves access to information stored on your device beyond what is strictly necessary, or where it relies on a device identifier subject to ATT/UMP), the Publisher will request your consent through an in-App dialog or platform consent framework before collecting that Telemetry, and you may withdraw consent at any time from the App's settings.

**No sale; no behavioral-advertising profiles.** Telemetry is not "sold" or "shared" for cross-context behavioral advertising as those terms are defined under the CCPA/CPRA and similar laws.

**Aggregation and de-identification.** The Publisher may create aggregated or de-identified data from Telemetry and may use, retain, and disclose such data without restriction for any lawful purpose.

**Developer Parties.** The Developer Parties do not receive Telemetry in identifiable form, do not determine the purposes and means of its processing, and have no obligation or liability in respect of it (see Section 1 and the Terms).

### 3.6 Data we do not collect

We do **not** collect or process:

- your real name, email address (other than where you choose to contact us), phone number, postal address, or government identifier;
- payment card data, bank-account data, or other payment-instrument data (handled exclusively by Apple or Google);
- biometric data, health data, sexual-orientation data, religious-belief data, racial or ethnic data, political-opinion data, or trade-union membership;
- precise or approximate geolocation (we do not request location permission);
- access to your contacts, photos, calendar, microphone, camera, SMS, call log, or files outside the App sandbox;
- browsing history outside the App;
- session replay, screen recording, heat maps, eye-tracking, keystroke logging, or any behavioral profile for advertising or resale;
- third-party SDK telemetry beyond (i) what Google AdMob requires to serve a requested rewarded ad and (ii) the Telemetry described in Section 3.5.

## 4. Purposes and Lawful Bases for Processing

We process data only for the purposes and on the lawful bases set out below.

| Purpose | Categories used | GDPR / UK GDPR lawful basis |
|---|---|---|
| Provide the App's single-player functionality | 3.1 local data | Performance of a contract (Art. 6(1)(b)) |
| Validate and grant In-App Purchase entitlements | 3.3 IAP receipts | Performance of a contract (Art. 6(1)(b)) |
| Submit your Daily Challenge score to the platform leaderboard (Apple Game Center / Google Play Games) when your device is signed into that service | 3.2 submission to platform | Performance of a contract (Art. 6(1)(b)) — providing the leaderboard feature you can opt out of by signing out of the platform service; and legitimate interests (Art. 6(1)(f)) in offering competitive play |
| Leaderboard integrity, anti-cheat, and abuse detection | 3.2 / 3.5 | Legitimate interests (Art. 6(1)(f)) — operating a fair service. Note that platform leaderboards are operated by Apple and Google under their own anti-cheat measures |
| Maintain a legal record of your acceptance of the Terms | 3.1 / 3.2 acceptance records | Legal obligation (Art. 6(1)(c)) and legitimate interests (Art. 6(1)(f)) |
| Serve a voluntary rewarded advertisement on request | 3.4 AdMob data | Consent (Art. 6(1)(a)) — for ad personalization and advertising identifier where applicable; legitimate interests for fraud-prevention diagnostics |
| Understand how the App is installed, opened, used, and closed; detect crashes; measure feature engagement; A/B test; secure and improve the App | 3.5 Telemetry | Legitimate interests (Art. 6(1)(f)) for strictly-necessary diagnostics and security; performance of contract (Art. 6(1)(b)) for operating requested features; consent (Art. 6(1)(a)) for any Telemetry that requires consent under applicable law (collected via in-App consent dialog or ATT/UMP) |
| Comply with law, respond to lawful requests, defend legal claims | any | Legal obligation (Art. 6(1)(c)) and legitimate interests (Art. 6(1)(f)) |

Where we rely on legitimate interests, we have performed a balancing assessment and concluded that our interests are not overridden by your fundamental rights and freedoms. You may object to such processing under Section 9.

We do **not** engage in any form of automated decision-making (including profiling) that produces legal or similarly significant effects on you.

## 5. Sale and Sharing of Personal Information

We do **not** "sell" personal information for monetary or other valuable consideration, and we do **not** "share" personal information for cross-context behavioral advertising, as those terms are defined under the CCPA/CPRA and similar U.S. state laws.

Voluntary rewarded advertisements delivered by Google AdMob may, where you have consented and where required by law, involve disclosure to Google for ad-serving purposes. We do not direct Google to use that data to build profiles for resale.

## 6. Recipients and Disclosures

We do not operate our own backend today. As a result, the categories of recipients to which data flows from the App are limited to:

- **Apple Inc. and Google LLC** as the operators of the App Store, Game Center, iCloud backup, Google Play, Google Play Games, and Google Play Console reporting — in connection with App distribution, IAP receipts, leaderboard submission (Section 3.2), and OS-level diagnostics that the device sends regardless of our wishes;
- **Google LLC (Google AdMob and the Google User Messaging Platform)** for the purposes described in Sections 3.4 and 16;
- **Telemetry service providers** described in Section 3.5, if and when we enable a particular provider, each acting as a processor on the Publisher's documented instructions;
- **competent authorities, courts, regulators, or law-enforcement agencies** where required by valid legal process or to protect our rights, your safety, or the safety of others;
- **professional advisors** (legal counsel, accountants, auditors) under duties of confidentiality, where reasonably necessary;
- **a successor entity** in connection with a merger, acquisition, reorganization, financing, sale of assets, bankruptcy, or insolvency event (with notice as required by law); and
- **cloud-hosting, infrastructure, security, or backend providers** that we may engage in the future if we add our own backend — none today.

We do not sell or rent data to advertisers, data brokers, or third parties for marketing.

## 7. International Data Transfers

Because we do not operate our own backend today, we do not ourselves transfer your personal data across borders. The cross-border transfers that may occur when you use the App are performed by third parties acting on their own account, including:

- **Apple Inc.** (App Store, Game Center, iCloud) — governed by Apple's privacy policy and Apple's own data-transfer safeguards;
- **Google LLC** (Google Play, Google Play Games, Google AdMob, Google User Messaging Platform, and any Google-operated analytics service we later enable) — governed by Google's privacy policy and Google's own data-transfer safeguards, including the European Commission's Standard Contractual Clauses where applicable; and
- any Telemetry processor we engage under Section 3.5, in which case we will execute the European Commission's Standard Contractual Clauses (2021/914), the UK International Data Transfer Addendum, the Swiss FDPIC Addendum, or other approved transfer mechanism, with supplementary technical and organizational measures as appropriate.

If we later operate our own backend, we will enter into all transfer mechanisms required by then-applicable law before any personal data leaves your country of residence. A summary of the transfer mechanisms then in force may be requested at privacy@gridburst.app.

## 8. Retention

We retain personal data only for as long as necessary to fulfill the purposes for which it was collected, including for legal, accounting, or reporting requirements.

| Category | Retention period |
|---|---|
| Local on-device data (Section 3.1) | Until you uninstall the App or clear its data |
| Leaderboard score and submission timestamp (Section 3.2) | Retained by Apple Game Center / Google Play Games per the operator's own policy; we do not control retention and have no ability to delete entries on the platform leaderboard. The leaderboard ID and submission cadence we send is configured per Daily Challenge |
| Aggregate or de-identified statistics derived from any data we lawfully hold | Indefinitely, in a form that cannot reasonably be re-identified |
| Server access logs (only if we later operate a backend) | Up to 30 days, then deleted or aggregated. None today |
| Telemetry events (raw, event-level) | Up to 25 months (Google Analytics maximum default) or shorter as configured |
| Crash and error reports | Up to 90 days for raw stack traces; aggregate counts may be retained indefinitely |
| Aggregated / de-identified Telemetry | Indefinitely, in a form that cannot reasonably be re-identified |
| IAP entitlement records | Duration of entitlement plus 7 years (accounting / tax compliance) |
| Terms acceptance records | Duration of your use plus 3 years (limitations period) |
| Records related to legal claims or disputes | Duration of the matter plus the applicable limitations period |

After the applicable retention period, data is deleted, anonymized, or aggregated such that re-identification is not reasonably possible.

## 9. Your Rights

Subject to applicable law and to verification of your identity, you may exercise the following rights with respect to personal data we process about you:

- **Right of access** — confirmation of whether we process data about you and, if so, a copy of that data;
- **Right to rectification** — correction of inaccurate or incomplete data;
- **Right to erasure / "right to be forgotten"** — deletion of data, subject to legal-retention exceptions;
- **Right to restriction** — limit how we process data while a dispute is resolved;
- **Right to data portability** — receipt of data you have provided to us in a structured, commonly used, machine-readable format;
- **Right to object** — object to processing based on legitimate interests, including profiling;
- **Right to withdraw consent** — at any time, where processing is based on consent (withdrawal does not affect the lawfulness of prior processing);
- **Right not to be subject to automated decision-making** producing legal or similarly significant effects (we do not engage in such processing);
- **Right to lodge a complaint** with your supervisory authority.

**California / CPRA residents** additionally have:

- the right to know the categories of personal information collected, sources, business or commercial purposes, and categories of recipients;
- the right to know specific pieces of personal information collected;
- the right to delete personal information, subject to permitted exceptions;
- the right to correct inaccurate personal information;
- the right to opt out of the "sale" or "sharing" of personal information (we do neither);
- the right to limit the use and disclosure of "sensitive personal information" (we do not collect any);
- the right to non-discrimination for exercising your privacy rights; and
- the right to designate an authorized agent to act on your behalf.

**Virginia, Colorado, Connecticut, Utah, Texas, and other U.S. state-law residents** have analogous rights, including (where the applicable statute provides) the right to appeal a refusal of a request.

**EU/EEA and UK residents** may lodge a complaint with their local supervisory authority; a list of EU authorities is available at https://edpb.europa.eu/about-edpb/about-edpb/members_en.

**To exercise any right**, contact privacy@gridburst.app and include sufficient information to verify your identity and to identify the data at issue. Because we do not currently maintain server-side records about individual users, the practical exercise of many rights is as follows:

- **Locally-stored data (Section 3.1):** uninstall the App, or use your OS settings to clear the App's storage. This deletes all local data instantly without contacting us.
- **Leaderboard scores submitted to Apple Game Center / Google Play Games (Section 3.2):** contact Apple or Google directly; we do not control the platform leaderboard and cannot delete platform-side entries.
- **AdMob data (Section 3.4):** revoke ATT permission in iOS Settings → Privacy & Security → Tracking, change UMP consent in the App's settings, and / or follow Google's controls at https://adssettings.google.com/.
- **Telemetry (Section 3.5):** withdraw consent through the App's in-app consent dialog (if one was presented to you), through your OS-level ATT / UMP choices, or by contacting privacy@gridburst.app to request that we instruct the relevant processor to delete events associated with your installation identifier.
- **IAP receipts:** contact Apple or Google for refund and receipt records, which they alone control.

We may refuse a request that is manifestly unfounded, excessive, or repetitive, or charge a reasonable fee where permitted by law.

## 10. Children's Privacy

The App is rated for general audiences but is **not directed to children under the age of 13** (or under the age of digital consent that applies in your jurisdiction, which may be up to 16 under GDPR Member State law).

We do not knowingly collect personal information from children below the applicable age of digital consent without verifiable parental consent. We do not use behavioral advertising; rewarded video advertisements served by Google AdMob are non-personalized for users we have reason to believe are under the applicable age, and we apply Google's "tag for child-directed treatment" / "tag for users under the age of consent" signals where relevant.

If you are a parent or guardian and believe that a child under the applicable age has provided personal information to us, contact privacy@gridburst.app and we will delete the data promptly.

## 11. Security

We implement appropriate technical and organizational measures designed to protect personal data against accidental or unlawful destruction, loss, alteration, unauthorized disclosure, or access, including:

- HTTPS / TLS for all outbound network requests the App makes that we control (today, this is limited to fetching the current Terms version file from our public legal-documents static site, and to calls to Apple, Google, and Google AdMob, each of which encrypts its own transport);
- minimization of data collected and retained;
- separation of legal-documents hosting from any future operational backend;
- routine review of native plugin and third-party SDK updates for security advisories;
- reliance on the security controls of Apple, Google, and any future processor we engage (each of which publishes its own security documentation).

No security measure is impenetrable. We cannot and do not guarantee absolute security. You are responsible for keeping your device and platform account secure (including using a current operating system version and a screen lock).

## 12. Data Breach Notification

In the event of a personal-data breach likely to result in a risk to the rights and freedoms of natural persons, we will notify the competent supervisory authority without undue delay and, where feasible, within 72 hours of becoming aware of it, in accordance with Art. 33 GDPR (and equivalent obligations under other applicable laws). Where the breach is likely to result in a **high** risk to those rights and freedoms, we will also notify affected users without undue delay, in accordance with Art. 34 GDPR.

## 13. Cookies and Similar Technologies

The App does not use HTTP cookies. The App does use the device's local storage (`localStorage`) and, on iOS / Android, the App's private sandbox file system, solely to persist the data described in Section 3.1. These technologies are strictly necessary for the App to function and are not used for tracking across services.

## 14. Third-Party Services

| Service | Purpose | Provider's privacy policy |
|---|---|---|
| Apple App Store, Apple Game Center, iCloud | Distribution, IAP, optional leaderboards / sync | https://www.apple.com/legal/privacy/ |
| Google Play, Google Play Games, Google Drive backup | Distribution, IAP, optional leaderboards / sync | https://policies.google.com/privacy |
| Google AdMob | Voluntary rewarded video advertisements | https://policies.google.com/technologies/ads |

Each third-party service is governed by its own privacy policy. We encourage you to review them.

## 15. App Tracking Transparency (iOS)

On iOS, before AdMob can access the IDFA advertising identifier, the operating system will present an App Tracking Transparency prompt. If you decline, the App continues to function and rewarded ads continue to be served on a non-personalized basis where available. We do not penalize you for declining.

## 16. EU/UK/EEA Consent for Ads ("GDPR for AdMob")

For users in the EU, EEA, and UK, the first time you request a rewarded video advertisement the App will present a Google-provided consent dialog (User Messaging Platform) that explains AdMob's purposes and asks for your consent. You may change your choice at any time from the App's settings screen. If you do not consent, ads continue to be served on a non-personalized basis where available.

## 17. Service Discontinuation

If we discontinue any online or platform-dependent feature of the App (for example, by removing leaderboard submission, removing rewarded-ad support, removing IAP, or removing the App itself), or if a third-party service we depend on (Apple Game Center, Google Play Games, Google AdMob, an analytics processor, etc.) is discontinued or becomes unavailable to us, we will:

- where reasonably practicable, notify users in advance via the App, our store listings, or our public website / legal-documents page;
- preserve locally-stored game progress on your device (no deletion required from us);
- where technically feasible and where we hold the data on a backend we operate, provide a final opportunity to export your data; and
- where required by law, retain data for the minimum period necessary to satisfy legal obligations and then delete it.

Discontinuation does not entitle you to a refund (see Section 4 of the Terms).

## 18. Do Not Track

Some web browsers transmit a "Do Not Track" signal. The App does not currently respond to such signals because (a) there is no consistent industry or legal standard for processing them and (b) the App does not engage in cross-site or cross-service tracking in any event.

## 19. Successor in Interest

If the Publisher (or any business unit operating the App) is merged with, acquired by, or sold to another entity, or if substantially all of its assets are transferred, personal data held by us may be among the assets transferred. The successor will continue to be bound by this Policy or a policy at least as protective, and you will be notified to the extent required by applicable law.

## 20. Changes to This Policy

We may amend this Policy from time to time. The "Effective date" and "Version" at the top will reflect the latest revision. Material changes will be brought to your attention via the App on next launch (for example, by re-prompting acceptance of the Terms where the changes are material under applicable law). Your continued use of the App after a change takes effect constitutes acceptance of the revised Policy, except where additional consent is required by law.

We will retain prior versions of this Policy and provide them on reasonable request.

## 21. Hierarchy

In the event of any conflict between this Policy and the Terms, this Policy governs to the extent the conflict concerns the processing of personal data; the Terms govern in all other respects. Mandatory provisions of applicable data-protection law override either document to the extent of the conflict.

## 22. Contact

For all privacy questions, requests, and complaints:

- **Email:** privacy@gridburst.app

EU/EEA users who wish to lodge a complaint may also contact their local supervisory authority. A list is available at https://edpb.europa.eu/about-edpb/about-edpb/members_en. UK users may contact the Information Commissioner's Office at https://ico.org.uk/. California residents may contact the California Privacy Protection Agency at https://cppa.ca.gov/.

---

This Privacy Policy is incorporated by reference into the GridBurst Terms of Service. By accepting the Terms, you also accept this Policy.
