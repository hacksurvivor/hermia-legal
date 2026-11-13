---
title: Hermia Privacy Policy
heading: Privacy Policy
layout: default
permalink: /privacy
---


<p class="updated">Last updated: 13 November 2026</p>

Hermia ("we") translates phone calls live between you and the people who call you. This policy explains
what we collect, why, who processes it for us, and your choices.

## 1. What we collect

**About you (the account holder)**
- Your sign-in account (email address, or the identifier Apple gives us with Sign in with Apple), handled by
  our sign-in provider.
- Your phone number. You confirm it's yours by calling our service number from it once (or, if that can't
  work, by an SMS code). It tells our system which forwarded calls are yours.
- Your settings: your language, the language your callers usually speak, the voice that speaks your words to callers (and
  its gender), and your country (from your number).
- Call records: for each translated call, the caller's number, our service number, start, answer and end
  times, billed seconds, and the outcome (for example "completed" or "out of minutes"). **No audio and no
  transcript.**
- Minutes used in each billing period.
- Subscription state from Apple: product, renewal and expiry dates, and Apple's transaction identifier. We
  never see your card or payment details; Apple handles payment.
- Your IP address, held briefly in memory to limit repeated verification attempts. It is not written to our database.

**About the people who call you**
- Their phone number, in your call records and in a routing entry that lets them reach you again by calling
  our service number back. The routing entry expires 7 days after your last call with them.
- Their voice, processed live to translate it (see section 2). It is not stored.

## 2. Call audio and translation
- Call audio is streamed in real time to our speech and translation providers, translated, and spoken to the
  other person. **We do not record or store call audio or transcripts.**
- Every call starts with a spoken notice to the caller, in their language, that the call is translated by
  software.
- Machine translation can be wrong, especially with numbers, dates and names. See the Terms.

## 3. Why we use it
- To route forwarded calls to you and translate them (the service you asked for).
- To meter your minutes and apply your plan.
- To keep the service secure: verifying your number, limiting abuse, finding faults.
- We do not sell your personal information or share it for cross-context behavioral advertising.

## 4. Who processes it for us
| Provider | What for | Data |
|---|---|---|
| WorkOS | Sign-in (AuthKit) | Email or Apple sign-in identifier, sign-in sessions |
| Twilio | Phone calls on our service numbers; SMS codes when a number can't be confirmed by call (Twilio Verify) | Phone numbers, call audio in transit, call metadata |
| Soniox | Speech recognition, translation, and the translated voice | Call audio in real time; text of the translation in transit |
| OpenAI | Translating the quick replies you type during a call; backup translation and voice when the main engine can't serve a language | Text you type; call audio in real time when used as backup |
| Railway | Hosting of our servers and database | Everything in section 1 |
| Apple | Subscriptions and payment | Purchase records (Apple's own privacy policy applies) |

## 5. How long we keep it
- Account and settings: until you delete your account.
- Call records and usage: 12 months, then deleted.
- Caller routing entries: 7 days after the last contact.
- Subscription records: as long as needed for billing disputes and tax law.

## 6. Your choices and rights
- Change your settings in the app at any time.
- Turn forwarding off from the app; calls then stop reaching us.
- Ask for a copy of your data, a correction, or deletion of your account at [hermia@moloman.dev](mailto:hermia@moloman.dev). We answer within
  30 days. California residents have the rights to know, delete, correct and opt out of sale/sharing
  (we don't sell or share); we won't treat you differently for using them.

## 7. Security
Data in transit is encrypted. Signing keys and secrets are kept out of the code. Webhooks from Twilio and Apple
are signature-checked.

## 8. Children
Hermia is not for children under 13 (or under 16 where local law sets that age), and we don't knowingly collect their data.

## 9. Changes
We'll post changes here and, for material ones, tell you in the app.

## 10. Contact
Sergey Moloman, Republic of Moldova, [hermia@moloman.dev](mailto:hermia@moloman.dev).
