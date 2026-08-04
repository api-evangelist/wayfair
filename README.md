# Wayfair (wayfair)

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

Wayfair Inc. is one of the world's largest online destinations for home goods and furniture, serving over 20 million customers and 10,000+ suppliers. Wayfair's Developer Portal provides GraphQL-based APIs enabling suppliers to manage purchase orders, inventory updates, product catalog management, advanced shipment notifications, and returns. The platform is built on federated GraphQL architecture using domain-oriented microservices, allowing suppliers to request only the data they need.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- E-Commerce
- Furniture
- Home Goods
- Retail
- Suppliers
- GraphQL

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Wayfair Supplier API

GraphQL-based API for Wayfair suppliers to manage orders, inventory, product catalogs, shipping notifications, and returns. Provides access to purchase orders, inventory updates, catalog management, and advanced shipment notifications via a unified GraphQL endpoint at api.wayfair.com/v1/graphql.

- **Human URL:** [https://developer.wayfair.com/docs/](https://developer.wayfair.com/docs/)
- **Base URL:** `https://api.wayfair.com/v1/graphql`

#### Tags

- Catalog
- E-Commerce
- GraphQL
- Inventory
- Orders
- Shipping
- Suppliers

#### Properties

- [Documentation](https://developer.wayfair.com/docs/)
- [Documentation](https://developer.wayfair.io/posts/graphQL)
- [OpenAPI](openapi/wayfair-supplier-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wayfair-supplier-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wayfair-supplier-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wayfair-graph-ql-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wayfair-graph-ql-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wayfair-token-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wayfair-token-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wayfair-graph-ql-request-structure.json)
- [JSON Structure](json-structure/wayfair-graph-ql-response-structure.json)
- [Example](examples/wayfair-graph-ql-request-example.json)
- [Example](examples/wayfair-token-request-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/wayfair)
- [Portal](https://developer.wayfair.com/docs/)
- [Portal](https://developer.wayfair.io/posts/introduction)
- [Documentation](https://developer.wayfair.io/posts/graphQL)
- [Documentation](https://developer.wayfair.io/posts/api-testing)
- [Website](https://www.wayfair.com/)
- [About](https://www.aboutwayfair.com/)
- [GitHub Organization](https://github.com/wayfair)
- [Spectral Rules](rules/wayfair-spectral-rules.yml)
- [Vocabulary](vocabulary/wayfair-vocabulary.yml)
- [JSON-LD](json-ld/wayfair-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
