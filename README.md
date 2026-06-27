# SEON (seon)

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
