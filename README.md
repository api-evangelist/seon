# SEON (seon)

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

SEON provides fraud prevention and anti-money-laundering APIs that combine digital-footprint analysis, device fingerprinting, and machine-learning risk scoring. The SEON REST API returns real-time fraud scores and enriched intelligence from an email address, phone number, or IP address, plus a combined transaction Fraud API and AML screening, accessed over HTTPS with an X-API-KEY header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/seon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/seon/refs/heads/main/apis.yml)

## Tags

- Fraud Prevention
- Risk Scoring
- Digital Footprint
- AML
- Identity

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### SEON Fraud API

Combined end-to-end fraud scoring endpoint that ingests user, transaction, payment, device, email, phone, and IP signals and returns a fraud_score, a state decision, and the applied_rules that fired, enriched with email, phone, IP, BIN, device, and AML details modules.

- **Human URL:** [https://docs.seon.io/api-reference/fraud-api](https://docs.seon.io/api-reference/fraud-api)
- **Base URL:** `https://api.seon.io/SeonRestService/fraud-api/v2.0`

#### Tags

- Fraud
- Risk Scoring
- Transactions

#### Properties

- [Documentation](https://docs.seon.io/api-reference/fraud-api)
- [API Reference](https://docs.seon.io/api-reference/fraud-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Email API

Unlocks the digital footprint behind an email address - deliverability, domain details, breach history, and registration on 250+ online platforms - returning a machine-learning risk score and account aggregates.

- **Human URL:** [https://docs.seon.io/api-reference/email-api](https://docs.seon.io/api-reference/email-api)
- **Base URL:** `https://api.seon.io/SeonRestService/email-api/v3`

#### Tags

- Email
- Digital Footprint
- Enrichment

#### Properties

- [Documentation](https://docs.seon.io/api-reference/email-api)
- [API Reference](https://docs.seon.io/api-reference/email-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Phone API

Returns the digital footprint behind a phone number, including carrier and HLR details, CNAM, telco attributes such as SIM-swap and porting history, account aggregates, and a global network risk score.

- **Human URL:** [https://docs.seon.io/api-reference/phone-api](https://docs.seon.io/api-reference/phone-api)
- **Base URL:** `https://api.seon.io/SeonRestService/phone-api/v2`

#### Tags

- Phone
- Digital Footprint
- Enrichment

#### Properties

- [Documentation](https://docs.seon.io/api-reference/phone-api)
- [API Reference](https://docs.seon.io/api-reference/phone-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON IP API

Detects fake, harmful, and suspicious IP addresses - including Tor, VPN, web, public, data-center, and residential proxies - with geolocation, ISP, open ports, and a risk score for a given IPv4 or IPv6 address.

- **Human URL:** [https://docs.seon.io/api-reference/ip-api](https://docs.seon.io/api-reference/ip-api)
- **Base URL:** `https://api.seon.io/SeonRestService/ip-api/v1`

#### Tags

- IP
- Proxy Detection
- Enrichment

#### Properties

- [Documentation](https://docs.seon.io/api-reference/ip-api)
- [API Reference](https://docs.seon.io/api-reference/ip-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON AML API

Screens a person against sanctions, watchlists, crime lists, politically exposed persons (PEP), and adverse-media sources, returning per-category match flags and a result payload for anti-money-laundering compliance.

- **Human URL:** [https://docs.seon.io/api-reference/aml-api](https://docs.seon.io/api-reference/aml-api)
- **Base URL:** `https://api.seon.io/SeonRestService/aml-api/v1`

#### Tags

- AML
- Sanctions
- Compliance

#### Properties

- [Documentation](https://docs.seon.io/api-reference/aml-api)
- [API Reference](https://docs.seon.io/api-reference/aml-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Scoring / Labels API

Applies fraud-outcome labels (such as fraud_detection_fraud) to up to 50 previously scored transactions per request, feeding SEON's machine-learning models so future fraud scores improve over time.

- **Human URL:** [https://docs.seon.io/api-reference/label-api](https://docs.seon.io/api-reference/label-api)
- **Base URL:** `https://api.seon.io/SeonRestService/fraud-api/transaction-label/v2`

#### Tags

- Labels
- Scoring
- Machine Learning

#### Properties

- [Documentation](https://docs.seon.io/api-reference/label-api)
- [API Reference](https://docs.seon.io/api-reference/label-api)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Device Fingerprint

Web, iOS, and Android SDKs capture an encrypted, base64-encoded device fingerprint via getSession(); the payload is passed in the Fraud API session field and decoded server-side into device_details intelligence covering hardware, browser, emulator, and tampering signals.

- **Human URL:** [https://docs.seon.io/integration/device-intelligence](https://docs.seon.io/integration/device-intelligence)
- **Base URL:** `https://api.seon.io/SeonRestService/fraud-api/v2.0`

#### Tags

- Device Intelligence
- Fingerprinting
- SDK

#### Properties

- [Documentation](https://docs.seon.io/integration/device-intelligence)
- [GitHub](https://github.com/seontechnologies/seon-web-sdk-public)
- [OpenAPI](openapi/seon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/seontechnologies)
- [LinkedIn](https://www.linkedin.com/company/seon-tech)
- [Website](https://seon.io/)
- [Documentation](https://docs.seon.io)
- [Plans](plans/seon-plans-pricing.yml)
- [Rate Limits](rate-limits/seon-rate-limits.yml)
- [Fin Ops](finops/seon-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
