# Pismo (pismo)

Pismo is a cloud-native issuer-processing and core-banking platform exposing REST APIs for accounts, customers, cards, authorizations, transactions, statements, and programs, plus an event stream (Kafka-backed, delivered via webhooks and cloud event buses). Acquired by Visa in January 2024, Pismo powers card issuing and digital banking for financial institutions across the Americas, Europe, and APAC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pismo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pismo/refs/heads/main/apis.yml)

## Tags

- Banking
- Card Issuing
- Payments
- Fintech
- Core Banking
- Cloud Native

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Pismo Accounts API

Create and manage core-banking accounts, account status lifecycle, ownership transfer, and account balances and balance history under the /accounts/v1 path family.

- **Human URL:** [https://developers.pismo.io/pismo-docs/reference](https://developers.pismo.io/pismo-docs/reference)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Accounts
- Core Banking
- Balances

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/setup-overview)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Customers API

Register and manage customers (individual and legal entities), their documents and contact details, and the customer-to-account relationships that anchor cards and balances.

- **Human URL:** [https://developers.pismo.io/pismo-docs/reference](https://developers.pismo.io/pismo-docs/reference)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Customers
- Onboarding
- KYC

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/setup-overview)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Cards API

Issue and manage physical and virtual cards across the /wallet card path family - create cards, retrieve card details, manage card status and lifecycle, and drive network tokenization flows.

- **Human URL:** [https://developers.pismo.io/pismo-docs/docs/cards-overview-1](https://developers.pismo.io/pismo-docs/docs/cards-overview-1)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Cards
- Issuing
- Tokenization

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/cards-overview-1)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Authorizations API

List and inspect card-network authorizations for an account, query direct-network transactions, and simulate authorization scenarios for integration testing.

- **Human URL:** [https://developers.pismo.io/pismo-docs/docs/simulate-authorizations](https://developers.pismo.io/pismo-docs/docs/simulate-authorizations)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Authorizations
- Real Time
- Network Transactions

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/simulate-authorizations)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Transactions and Statements API

Retrieve posted transactions, transaction details, current and historical statements, statement transactions, and transaction shift operations under the /statements and /accounts statement path families.

- **Human URL:** [https://developers.pismo.io/pismo-docs/docs/understanding-statements](https://developers.pismo.io/pismo-docs/docs/understanding-statements)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Transactions
- Statements
- Billing

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/understanding-statements)
- [API Reference](https://developers.pismo.io/pismo-docs/reference/gettransactionbyid)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Programs API

Create and configure programs - the product templates that bind card products, account types, fees, and rules - including program creation, retrieval, and cloning.

- **Human URL:** [https://developers.pismo.io/pismo-docs/docs/main-solutions](https://developers.pismo.io/pismo-docs/docs/main-solutions)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Programs
- Configuration
- Product Setup

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/main-solutions)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pismo Events API

Subscribe to and manage platform events emitted from Pismo's Kafka-backed event stream - register client webhooks and configure real-time delivery (AWS SNS / EventBridge, Azure, GCP) or batch file delivery (SFTP, S3).

- **Human URL:** [https://developers.pismo.io/pismo-docs/docs/client-webhooks](https://developers.pismo.io/pismo-docs/docs/client-webhooks)
- **Base URL:** `https://api.pismo.io`

#### Tags

- Events
- Webhooks
- Kafka

#### Properties

- [Documentation](https://developers.pismo.io/pismo-docs/docs/client-webhooks)
- [API Reference](https://developers.pismo.io/pismo-docs/reference)
- [OpenAPI](openapi/pismo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pismo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pismo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/pismo)
- [Website](https://www.pismo.io)
- [Documentation](https://developers.pismo.io)
- [Plans](plans/pismo-plans-pricing.yml)
- [Rate Limits](rate-limits/pismo-rate-limits.yml)
- [Fin Ops](finops/pismo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

---

> Note: Pismo was acquired by Visa in January 2024 (~US$1B all-cash). It operates as a Visa-owned platform and continues to run its own developer portal at developers.pismo.io. Pricing is sales-led / partner-negotiated and is not publicly published; usage and rate-limit values in this catalog are marked unreconciled where the provider does not document specific figures.
