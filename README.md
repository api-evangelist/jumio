# Jumio (jumio)

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
