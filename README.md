# Wayfair (wayfair)

Wayfair Inc. is one of the world's largest online destinations for home goods and furniture, serving over 20 million customers and 10,000+ suppliers. Wayfair's Developer Portal provides GraphQL-based APIs enabling suppliers to manage purchase orders, inventory updates, product catalog management, advanced shipment notifications, and returns. The platform is built on federated GraphQL architecture using domain-oriented microservices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - E-Commerce, Furniture, Home Goods, Retail, Suppliers, GraphQL

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### Wayfair Supplier API

GraphQL-based API for Wayfair suppliers to manage orders, inventory, product catalogs, shipping notifications, and returns. Provides access to purchase orders, inventory updates, catalog management, and advanced shipment notifications via a unified GraphQL endpoint.

**Human URL:** [https://developer.wayfair.com/docs/](https://developer.wayfair.com/docs/)

#### Tags:

 - Catalog, E-Commerce, GraphQL, Inventory, Orders, Shipping, Suppliers

#### Properties

- [Documentation](https://developer.wayfair.com/docs/)
- [GraphQL Documentation](https://developer.wayfair.io/posts/graphQL)
- [OpenAPI](openapi/wayfair-supplier-api.yml)
- [GraphQL Request Schema](json-schema/wayfair-graph-ql-request-schema.json)
- [GraphQL Response Schema](json-schema/wayfair-graph-ql-response-schema.json)
- [Token Request Schema](json-schema/wayfair-token-request-schema.json)
- [Token Response Schema](json-schema/wayfair-token-response-schema.json)
- [GraphQL Request Structure](json-structure/wayfair-graph-ql-request-structure.json)
- [GraphQL Response Structure](json-structure/wayfair-graph-ql-response-structure.json)
- [GraphQL Request Example](examples/wayfair-graph-ql-request-example.json)
- [Token Request Example](examples/wayfair-token-request-example.json)

## Common Properties

- [Developer Portal](https://developer.wayfair.com/docs/)
- [Developer Portal (Introduction)](https://developer.wayfair.io/posts/introduction)
- [GraphQL Documentation](https://developer.wayfair.io/posts/graphQL)
- [Sandbox API Testing](https://developer.wayfair.io/posts/api-testing)
- [Wayfair Website](https://www.wayfair.com/)
- [About Wayfair](https://www.aboutwayfair.com/)
- [Wayfair GitHub Organization](https://github.com/wayfair)
- [Wayfair Spectral Rules](rules/wayfair-spectral-rules.yml)
- [Supplier Operations Capability](capabilities/supplier-operations.yaml)
- [Wayfair Vocabulary](vocabulary/wayfair-vocabulary.yml)
- [Wayfair JSON-LD Context](json-ld/wayfair-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| GraphQL Supplier API | Unified GraphQL endpoint enabling suppliers to query and mutate data across orders, inventory, catalog, and shipping. |
| Purchase Order Management | Suppliers retrieve, acknowledge, and manage purchase orders from Wayfair buyers. |
| Inventory Management | Real-time inventory updates and stock level management for the Wayfair marketplace catalog. |
| Product Catalog Management | Suppliers manage product listings, pricing, descriptions, and attributes. |
| Advanced Shipment Notifications | Suppliers submit ASN data to notify Wayfair of pending shipments and tracking numbers. |
| Sandbox Testing Environment | Full sandbox environment at sandbox.api.wayfair.com for integration testing. |
| OAuth2 Token Authentication | Client credentials flow issuing temporary access tokens for secure API access. |

## Use Cases

| Name | Description |
|------|-------------|
| Order Fulfillment Automation | Automate purchase order retrieval, acknowledgment, and fulfillment workflows. |
| Inventory Synchronization | Real-time synchronization of warehouse inventory levels with the Wayfair marketplace. |
| Product Catalog Updates | Batch and real-time updates to product listings, pricing, and attributes. |
| Shipping Notification Automation | Automated submission of ASN data and tracking information when orders ship. |

## Integrations

| Name | Description |
|------|-------------|
| Wayfair Sandbox | Full sandbox environment for integration testing before deploying to production. |
| Apollo GraphQL Federation | Federated GraphQL architecture enabling domain-oriented microservices composition. |
| OAuth2 Authentication | Standard OAuth2 client credentials flow for secure supplier authentication. |

## Artifacts

### OpenAPI

- [Wayfair Supplier API](openapi/wayfair-supplier-api.yml)

### JSON Schema

- [wayfair-graph-ql-error-schema.json](json-schema/wayfair-graph-ql-error-schema.json)
- [wayfair-graph-ql-request-schema.json](json-schema/wayfair-graph-ql-request-schema.json)
- [wayfair-graph-ql-response-schema.json](json-schema/wayfair-graph-ql-response-schema.json)
- [wayfair-token-request-schema.json](json-schema/wayfair-token-request-schema.json)
- [wayfair-token-response-schema.json](json-schema/wayfair-token-response-schema.json)

### JSON Structure

- [wayfair-graph-ql-error-structure.json](json-structure/wayfair-graph-ql-error-structure.json)
- [wayfair-graph-ql-request-structure.json](json-structure/wayfair-graph-ql-request-structure.json)
- [wayfair-graph-ql-response-structure.json](json-structure/wayfair-graph-ql-response-structure.json)
- [wayfair-token-request-structure.json](json-structure/wayfair-token-request-structure.json)
- [wayfair-token-response-structure.json](json-structure/wayfair-token-response-structure.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Wayfair Supplier API](capabilities/shared/wayfair-supplier-api.yaml) — 2 operations for GraphQL queries and OAuth2 authentication

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Supplier Operations](capabilities/supplier-operations.yaml) | Wayfair Supplier API | 7 | Supplier Integration Engineer, E-Commerce Operations Manager |

## Vocabulary

- [Wayfair Vocabulary](vocabulary/wayfair-vocabulary.yml) — Unified taxonomy mapping 2 resources, 2 actions, 2 workflows, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Wayfair Spectral Rules](rules/wayfair-spectral-rules.yml) — 22 rules across 9 categories enforcing Wayfair API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
