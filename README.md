# Telefoon (telefoon)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Telefoon is a cloud telephony and communications platform offering programmable voice, SMS, and number management APIs tailored for European markets. Built for GDPR compliance and EU regulatory requirements, Telefoon provides developers with REST APIs to build voice calling, SMS notification, number provisioning, and interactive voice response (IVR) solutions. The platform supports Dutch, Belgian, German, and broader European telecommunications infrastructure with local number availability and EU data residency.

**APIs.json:** [https://www.telefoon.com](https://www.telefoon.com)

## Scope

- **Type:** Index

## Tags

- Belgium
- CPaaS
- EU Data Residency
- Europe
- GDPR Compliant
- Messaging
- Netherlands
- Number Provisioning
- SMS
- Telephony
- Voice

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Telefoon Voice API

Programmable voice API for making and receiving calls across European networks. Supports outbound dialing, inbound call handling, IVR with multi-language text-to-speech (Dutch, French, German, English), call conferencing, call recording, and SIP trunking. Built with EU data residency and GDPR compliance for European enterprise customers.

- **Human URL:** [https://developers.telefoon.com/voice](https://developers.telefoon.com/voice)
- **Base URL:** `https://api.telefoon.com/v1/voice`

#### Tags

- Calls
- EU Telephony
- IVR
- Netherlands
- Telephony
- TTS
- Voice

#### Properties

- [Documentation](https://developers.telefoon.com/voice)
- [OpenAPI](openapi/telefoon-voice-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefoon-voice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefoon-voice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefoon.com/authentication)
- [Getting Started](https://developers.telefoon.com/getting-started)
- [Rate Limits](https://developers.telefoon.com/rate-limits)

### Telefoon SMS API

Send and receive SMS messages across European networks with full GDPR compliance. Supports A2P messaging, two-way SMS, delivery reports, unicode for European character sets (Dutch, German, French), bulk SMS, and message archiving for GDPR audit trails. Provides SMS sender ID registration for branded messaging in EU markets.

- **Human URL:** [https://developers.telefoon.com/sms](https://developers.telefoon.com/sms)
- **Base URL:** `https://api.telefoon.com/v1/sms`

#### Tags

- A2P Messaging
- Europe
- GDPR
- Messaging
- SMS
- Sender ID

#### Properties

- [Documentation](https://developers.telefoon.com/sms)
- [OpenAPI](openapi/telefoon-sms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefoon-sms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefoon-sms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefoon.com/authentication)
- [Rate Limits](https://developers.telefoon.com/rate-limits)

### Telefoon Number Management API

Search, purchase, and manage Dutch, Belgian, German, and broader European phone numbers. Supports local geographic numbers (NDC/area codes), national numbers, toll-free (0800), premium-rate (0900), and service numbers (0906). Handles regulatory requirements including address registration for Dutch and Belgian number types and porting requests (number portability).

- **Human URL:** [https://developers.telefoon.com/numbers](https://developers.telefoon.com/numbers)
- **Base URL:** `https://api.telefoon.com/v1/numbers`

#### Tags

- Belgian Numbers
- Dutch Numbers
- EU Numbers
- Number Management
- Number Portability
- Number Provisioning
- Phone Numbers

#### Properties

- [Documentation](https://developers.telefoon.com/numbers)
- [OpenAPI](openapi/telefoon-numbers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/telefoon-numbers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/telefoon-numbers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.telefoon.com/authentication)

## Common Properties

- [Authentication](https://developers.telefoon.com/authentication)
- [Getting Started](https://developers.telefoon.com/getting-started)
- [Rate Limits](https://developers.telefoon.com/rate-limits)
- [G D P R](https://www.telefoon.com/gdpr)
- [Status Page](https://status.telefoon.com)
- [Terms of Service](https://www.telefoon.com/terms)
- [Privacy Policy](https://www.telefoon.com/privacy)
- [Pricing](https://www.telefoon.com/pricing)
- [Support](https://www.telefoon.com/support)
- [Blog](https://blog.telefoon.com)

## Maintainers

**Email:** api-team@telefoon.com
**URL:** https://www.telefoon.com/about/api-team
