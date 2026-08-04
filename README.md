# Jumio (jumio)

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

Jumio operates the KYX Platform, an end-to-end AI-driven identity verification, fraud prevention, and compliance suite. Backend APIs orchestrate ID verification, document verification, biometric authentication, AML and watchlist screening, risk signals, and reusable identity (selfie.DONE). Web client and native iOS / Android / React Native / Flutter / Cordova SDKs front the platform; backend Java and .NET SDKs wrap the REST API for server-side flows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/jumio/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=jumio-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags

- KYC, Identity Verification, Biometrics, AML, Fraud Prevention, KYX

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Jumio ID Verification API | Initiates and retrieves ID verification transactions; issues SDK tokens, accepts callbacks. |
| Jumio Document Verification API | Validates supporting documents (utility bills, statements, leases). |
| Jumio Authentication API | Selfie-driven biometric reverification of returning customers. |
| Jumio selfie.DONE API | Frictionless single-selfie reverification for trusted returning users. |
| Jumio Screening API | AI-powered AML, sanctions, PEP, and adverse-media screening with ongoing monitoring. |
| Jumio Risk Signals API | Enriched risk-signal lookups against the Identity Graph, device, and behavioural data. |
| Jumio Retrieval API | Retrieves stored transactions, scanned documents, and decision audit history. |
| Jumio Callback / Webhook | Server-to-server final-decision delivery to a customer-configured URL. |
| Jumio Web SDK | Browser-based capture UI hosted on the customer's site. |
| Jumio Mobile SDK (iOS) | Native iOS SDK in Swift. |
| Jumio Mobile SDK (Android) | Native Android SDK in Java/Kotlin. |
| Jumio React Native Plugin | Cross-platform mobile wrapper. |
| Jumio Flutter Plugin | Flutter mobile wrapper. |
| Jumio Cordova Plugin | Apache Cordova hybrid mobile wrapper. |

## Common Properties

- [Website](https://www.jumio.com/)
- [Documentation](https://documentation.jumio.ai/)
- [GitHub](https://github.com/Jumio)
- [Plans](plans/jumio-plans-pricing.yml) - API Commons Plans 0.1
- [RateLimits](rate-limits/jumio-rate-limits.yml) - API Commons Rate Limits 0.1
- [FinOps](finops/jumio-finops.yml) - FOCUS-aligned FinOps Framework 1.0

## Plans

Jumio does not publish self-serve plan pricing. Commercial terms are negotiated per customer:

- **KYX Platform (Custom)** - Per-verification consumption with volume discounts; add-on lines for AML / PEP / sanctions / adverse-media screening, ongoing monitoring, document verification, biometric authentication, risk signals, retrieval, and extended retention; minimum monthly commit.

The SDKs are free to use; cost is incurred only when a transaction reaches the backend KYX Platform.

## Rate Limits

- Per-customer dynamic throttling that scales with the contracted verification volume; numeric ceiling not published.
- 429 Too Many Requests on excessive throughput; verify callbacks via mTLS or signed payload.
- ID Verification initiation tokens are short-lived and single-flow.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
