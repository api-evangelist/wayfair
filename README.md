# Wayfair (wayfair)

Wayfair Inc. is one of the world's largest online destinations for home goods and furniture. Wayfair provides a comprehensive developer portal with GraphQL-based APIs for suppliers to manage their business on the platform.

## APIs

### Wayfair Supplier API

GraphQL-based API enabling suppliers to manage orders, inventory, product catalogs, and shipping on the Wayfair platform.

**Key capabilities:**

- **Order Management** - Retrieve dropship purchase orders and send fulfillment updates
- **Inventory Management** - Update stock levels to keep Wayfair informed of product availability
- **Product Catalog** - Update marketing copy and feature bullets for product listings across Wayfair sites (US, CA, UK, DE)
- **Shipment Notifications** - Send Advanced Shipment Notifications (ASN) with tracking, package details, and shipment specifics

**Endpoints:**

- Production: `https://api.wayfair.com/v1/graphql`
- Sandbox: `https://sandbox.api.wayfair.com/v1/graphql`

**Authentication:** OAuth2 client credentials flow via the token endpoint.

## Key Links

- [Developer Portal](https://developer.wayfair.com/docs/)
- [Developer Documentation](https://developer.wayfair.io/posts/introduction)
- [GraphQL Reference](https://developer.wayfair.io/posts/graphQL)
- [Website](https://www.wayfair.com/)
