# Apicbase (apicbase)

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
