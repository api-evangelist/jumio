# Jumio

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** KYC · Identity Verification · Biometrics · AML · Fraud Prevention · KYX

## Jumio on APIs.io

Everything profiled for Jumio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/jumio/](https://apis.io/providers/jumio/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Jumio ID Verification API](https://apis.io/apis/jumio/id-verification/) — Initiates and retrieves ID verification transactions. Issues a token used to start the SDK or hosted web flow, accepts callback events when the verification…
- [Jumio Document Verification API](https://apis.io/apis/jumio/document-verification/) — Validates supporting documents beyond government ID - utility bills, bank statements, leases, and other proof-of-address artifacts. Returns extracted…
- [Jumio Authentication API](https://apis.io/apis/jumio/authentication/) — Selfie-driven biometric reverification of returning customers. Compares a fresh selfie against the previously enrolled face graph for the same user and…
- [Jumio selfie.DONE API](https://apis.io/apis/jumio/selfie-done/) — Frictionless reverification flow that recognizes returning trusted users with a single selfie - no need to rescan ID. Backed by the Jumio Identity Graph and…
- [Jumio Screening API (AML / Watchlist)](https://apis.io/apis/jumio/screening/) — AI-powered AML, sanctions, PEP, and adverse-media screening. Supports one-off screening calls and ongoing monitoring of enrolled identities. Returns hits,…
- [Jumio Risk Signals API](https://apis.io/apis/jumio/risk-signals/) — Returns enriched risk-signal data on a user (device, behavioural, network, and identity-graph signals) for layered risk scoring without requiring a full…
- [Jumio Retrieval API](https://apis.io/apis/jumio/retrieval/) — Retrieves stored transaction details, scanned documents, similarity scores, and decision audit history for an existing transaction. Used by compliance teams…
- [Jumio Callback / Webhook](https://apis.io/apis/jumio/callback/) — Server-to-server callback delivering verification results. Jumio POSTs the final decision and metadata to a customer-configured URL once a transaction…
- [Jumio Web SDK](https://apis.io/apis/jumio/web-sdk/) — Browser-based client SDK that hosts the verification UI, captures documents and selfies, and streams them to Jumio. Initialised with a token from the ID…
- [Jumio Mobile SDK (iOS)](https://apis.io/apis/jumio/mobile-sdk-ios/) — Native iOS SDK (Swift) that captures ID, supporting documents, and selfie biometrics, with on-device pre-checks before streaming to Jumio.
- [Jumio Mobile SDK (Android)](https://apis.io/apis/jumio/mobile-sdk-android/) — Native Android SDK (Java/Kotlin) that captures ID, supporting documents, and selfie biometrics, with on-device pre-checks before streaming to Jumio.
- [Jumio React Native Plugin](https://apis.io/apis/jumio/mobile-react/) — React Native plugin wrapping the iOS and Android SDKs for cross-platform mobile apps.
- [Jumio Flutter Plugin](https://apis.io/apis/jumio/mobile-flutter/) — Flutter plugin wrapping the iOS and Android SDKs for Flutter applications. MIT-licensed.
- [Jumio Cordova Plugin](https://apis.io/apis/jumio/mobile-cordova/) — Apache Cordova plugin wrapping the iOS and Android SDKs for hybrid Cordova apps.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Jumio KYX Workflow Callback](https://apis.io/asyncapis/jumio/jumio-callback-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [workflow-execution-callback](https://apis.io/channels/jumio/workflow-execution-callback/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Jumio — asyncapi rules](https://apis.io/rules/jumio/jumio-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Jumio Domain Security](https://apis.io/security/jumio/jumio-domain-security/)
- [Jumio Trust Center](https://apis.io/security/jumio/jumio-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Jumio Plans Pricing](https://apis.io/plans/jumio/jumio-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Jumio Rate Limits](https://apis.io/rate-limits/jumio/jumio-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Jumio Finops](https://apis.io/finops/jumio/jumio-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.jumio.com/)
- [Documentation](https://documentation.jumio.ai/)
- [Blog](https://www.jumio.com/feed/)

## API Evangelist rating

**Kin Score 24.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 40.6 |
| Contract governance | 13.6 |
| Operational transparency | 13.2 |
| Developer ergonomics | 11.9 |
| Access clarity | 13.2 |

**Agent readiness 14.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.4** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/jumio/](https://apis.io/providers/jumio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Jumio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/jumio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
