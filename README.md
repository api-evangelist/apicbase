# Apicbase (apicbase)

Apicbase is a cloud-based food & beverage back-of-house management platform for restaurants, hotels, and catering groups, covering recipes and menu engineering, ingredient libraries, inventory and stock, procurement, suppliers, and multi-outlet operations. The Apicbase REST API exposes these entities over HTTPS with OAuth 2.0 authentication, plus webhooks for integrated supplier ordering.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apicbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apicbase/refs/heads/main/apis.yml)

## Tags

- Food and Beverage
- Restaurant
- Back of House
- Inventory
- Procurement
- Recipes

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Apicbase Ingredients API

List, create, edit, clone, and merge ingredients in the library, with extensive filtering by category, supplier, allergen verification, and custom fields.

- **Human URL:** [https://developers.apicbase.com/reference/get-ingredients](https://developers.apicbase.com/reference/get-ingredients)
- **Base URL:** `https://api.apicbase.com/api/v2/products/ingredients`

#### Tags

- Ingredients
- Library
- Allergens

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-ingredients)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Recipes API

Create, edit, clone, and retrieve recipes and menus, including financial, nutritional, and bill-of-materials (BOM) calculations.

- **Human URL:** [https://developers.apicbase.com/reference/get-recipes](https://developers.apicbase.com/reference/get-recipes)
- **Base URL:** `https://api.apicbase.com/api/v2/products/recipes`

#### Tags

- Recipes
- Menus
- Menu Engineering

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-recipes)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Products API

Product development entities spanning ingredients, recipes, and stock items, modeling sellable finished products and POS-linkable catalog items.

- **Human URL:** [https://developers.apicbase.com/reference/introduction](https://developers.apicbase.com/reference/introduction)
- **Base URL:** `https://api.apicbase.com/api/v2/products`

#### Tags

- Products
- POS Items
- Catalog

#### Properties

- [API Reference](https://developers.apicbase.com/reference/introduction)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Inventory & Stock API

List, create, and edit stock items and inventory levels, plus stock events for waste, production, sales, transfers, and stock counts.

- **Human URL:** [https://developers.apicbase.com/reference/get-stock-items](https://developers.apicbase.com/reference/get-stock-items)
- **Base URL:** `https://api.apicbase.com/api/v2/products/stock_items`

#### Tags

- Inventory
- Stock
- Stock Events

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-stock-items)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Purchase Orders API

Create, send, retrieve, and delete purchase orders, filterable by supplier, outlet, status (IN_PROGRESS, ORDERED, DELIVERED), and delivery dates.

- **Human URL:** [https://developers.apicbase.com/reference/get-purchase-orders](https://developers.apicbase.com/reference/get-purchase-orders)
- **Base URL:** `https://api.apicbase.com/api/v2/procurement/purchase_orders`

#### Tags

- Purchase Orders
- Procurement
- Ordering

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-purchase-orders)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Suppliers API

List, create, and edit suppliers and their packages, filterable by company name, email, or VAT number, including supplier ordering details.

- **Human URL:** [https://developers.apicbase.com/reference/get-suppliers](https://developers.apicbase.com/reference/get-suppliers)
- **Base URL:** `https://api.apicbase.com/api/v2/suppliers`

#### Tags

- Suppliers
- Vendors
- Packages

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-suppliers)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Outlets API

List, create, and edit outlets (locations) in the library, with name and custom-field filtering for multi-site operations.

- **Human URL:** [https://developers.apicbase.com/reference/get-outlets](https://developers.apicbase.com/reference/get-outlets)
- **Base URL:** `https://api.apicbase.com/api/v2/accounts/outlets`

#### Tags

- Outlets
- Locations
- Accounts

#### Properties

- [API Reference](https://developers.apicbase.com/reference/get-outlets)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apicbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apicbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apicbase Webhooks

Outbound webhooks deliver orders to a partner-supplied HTTPS endpoint the moment an order is placed, signed with an X-APIC-WEBHOOK-SIGNATURE header.

- **Human URL:** [https://developers.apicbase.com/docs/integrated-ordering](https://developers.apicbase.com/docs/integrated-ordering)
- **Base URL:** `https://api.apicbase.com`

#### Tags

- Webhooks
- Events
- Integrated Ordering

#### Properties

- [Documentation](https://developers.apicbase.com/docs/integrated-ordering)
- [OpenAPI](openapi/apicbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/APICBASE)
- [LinkedIn](https://www.linkedin.com/company/apicbase)
- [Website](https://www.apicbase.com)
- [Documentation](https://developers.apicbase.com/docs/welcome)
- [Plans](plans/apicbase-plans-pricing.yml)
- [Rate Limits](rate-limits/apicbase-rate-limits.yml)
- [Fin Ops](finops/apicbase-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
