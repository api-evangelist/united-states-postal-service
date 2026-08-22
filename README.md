# United States Postal Service (united-states-postal-service)

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

The United States Postal Service (USPS) provides a modern REST API platform at developers.usps.com that gives ecommerce websites, shipping software, and logistics systems access to postal data and services. APIs cover address validation, package tracking, domestic and international shipping labels, pricing, carrier pickup scheduling, location finding, and Informed Delivery campaign management. The legacy Web Tools platform was retired January 25, 2026, with all functionality migrated to the new OAuth 2.0-secured API platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/united-states-postal-service/refs/heads/main/apis.yml)

## Tags

- Government
- Postal Service
- Shipping
- Logistics
- Address Validation
- Package Tracking

## Timestamps

- **Created:** 2024/01/01
- **Modified:** 2026-05-19

## APIs

### USPS Addresses API

Validates and corrects address information to USPS specifications, eliminating errors and improving package delivery. Supports full address standardization, city and state lookup by ZIP Code, and ZIP Code lookup by address.

- **Human URL:** [https://developers.usps.com/addressesv3](https://developers.usps.com/addressesv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Addresses
- Address Validation
- Government

#### Properties

- [Documentation](https://developers.usps.com/addressesv3)
- [OpenAPI](openapi/united-states-postal-service-addresses-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/addresses-address-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/addresses-city-state-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/addresses-address-structure.json)
- [JSON-LD](json-ld/united-states-postal-service-addresses-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/addresses-address-example.json)

### USPS Tracking API

Returns tracking status and related details for a given USPS package, including scan events with date, time, and location. Supports single and batch package tracking. Version 3.2 includes enhanced scan event extract notifications.

- **Human URL:** [https://developers.usps.com/trackingv3r2](https://developers.usps.com/trackingv3r2)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Tracking
- Package Tracking
- Government

#### Properties

- [Documentation](https://developers.usps.com/trackingv3r2)
- [OpenAPI](openapi/united-states-postal-service-tracking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tracking-tracking-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tracking-tracking-event-structure.json)
- [JSON-LD](json-ld/united-states-postal-service-tracking-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/tracking-tracking-event-example.json)

### USPS Domestic Prices API

Provides postage pricing for domestic USPS shipments based on origin and destination ZIP Codes, weight, dimensions, and mail class. Supports base rate lookups, extra service rates (insurance, signature confirmation, etc.), and total rate calculations.

- **Human URL:** [https://developers.usps.com/domesticpricesv3](https://developers.usps.com/domesticpricesv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Pricing
- Postage
- Shipping
- Government

#### Properties

- [Documentation](https://developers.usps.com/domesticpricesv3)
- [OpenAPI](openapi/united-states-postal-service-domestic-prices-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/domestic-prices-base-rate-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/domestic-prices-base-rate-request-structure.json)
- [JSON-LD](json-ld/united-states-postal-service-domestic-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/domestic-prices-base-rate-request-example.json)

### USPS Carrier Pickup API

Enables free carrier pickup scheduling for next-day service, Monday through Saturday, excluding federal holidays. Supports creating, retrieving, updating, and canceling pickup requests at residential and commercial addresses.

- **Human URL:** [https://developers.usps.com/carrierpickupv3](https://developers.usps.com/carrierpickupv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Carrier Pickup
- Shipping
- Government

#### Properties

- [Documentation](https://developers.usps.com/carrierpickupv3)
- [OpenAPI](openapi/united-states-postal-service-carrier-pickup-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/carrier-pickup-pickup-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/carrier-pickup-pickup-request-structure.json)
- [JSON-LD](json-ld/united-states-postal-service-carrier-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/carrier-pickup-pickup-request-example.json)

### USPS International Prices API

Provides pricing for international USPS products based on shipment characteristics including destination country, weight, dimensions, and service class.

- **Human URL:** [https://developers.usps.com/internationalpricesv3](https://developers.usps.com/internationalpricesv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- International
- Pricing
- Postage
- Government

#### Properties

- [Documentation](https://developers.usps.com/internationalpricesv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS Domestic Labels API

Creates domestic shipping labels with barcodes in multiple formats and generates Shipping Services Files. Requires USPS Ship enrollment and Enterprise Payment Account.

- **Human URL:** [https://developers.usps.com/domesticlabelsv3](https://developers.usps.com/domesticlabelsv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Labels
- Shipping
- Government

#### Properties

- [Documentation](https://developers.usps.com/domesticlabelsv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS International Labels API

Creates international shipping labels and generates required Shipping Services Files for customs compliance.

- **Human URL:** [https://developers.usps.com/internationallabelsv3](https://developers.usps.com/internationallabelsv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- International
- Labels
- Shipping
- Government

#### Properties

- [Documentation](https://developers.usps.com/internationallabelsv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS Locations API

Identifies drop-off facilities and destination entry points for various USPS services. Supports post office locator and drop-off location finder.

- **Human URL:** [https://developers.usps.com/locationsv3](https://developers.usps.com/locationsv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Locations
- Post Offices
- Government

#### Properties

- [Documentation](https://developers.usps.com/locationsv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS Service Standards API

Provides delivery benchmarks showing expected transit times between origin and destination ZIP Codes for USPS mail classes.

- **Human URL:** [https://developers.usps.com/standardsv3](https://developers.usps.com/standardsv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Service Standards
- Delivery
- Government

#### Properties

- [Documentation](https://developers.usps.com/standardsv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS Shipping Options API

Returns a comprehensive list of pricing, service standards, and shipping options for USPS products in a single API call, eliminating the need to query multiple APIs separately.

- **Human URL:** [https://developers.usps.com/shippingoptionsv3](https://developers.usps.com/shippingoptionsv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Shipping
- Pricing
- Government

#### Properties

- [Documentation](https://developers.usps.com/shippingoptionsv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS SCAN Forms API

Links multiple domestic and international labels through a single electronic file number, creating Shipment Confirmation Acceptance Notice forms for batch shipping operations.

- **Human URL:** [https://developers.usps.com/scanv3](https://developers.usps.com/scanv3)
- **Base URL:** `https://apis.usps.com`

#### Tags

- SCAN Forms
- Shipping
- Government

#### Properties

- [Documentation](https://developers.usps.com/scanv3)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPS OAuth API

Industry-standard OAuth 2.0 Client Credentials authentication protecting access to all USPS APIs. Returns Bearer Tokens used in the Authorization header for all USPS API calls.

- **Human URL:** [https://developers.usps.com/Oauth](https://developers.usps.com/Oauth)
- **Base URL:** `https://apis.usps.com`

#### Tags

- Authentication
- OAuth
- Government

#### Properties

- [Documentation](https://developers.usps.com/Oauth)
- [Authentication](https://developers.usps.com/getting-started)
- [Postman Collection](collections/united-states-postal-service-addresses.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-addresses.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-carrier-pickup.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-carrier-pickup.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-domestic-prices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-domestic-prices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/united-states-postal-service-tracking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/united-states-postal-service-tracking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usps)
- [Portal](https://developers.usps.com/)
- [Getting Started](https://developers.usps.com/getting-started)
- [Documentation](https://developers.usps.com/apis)
- [Terms of Service](https://developers.usps.com/terms-and-conditions)
- [F A Q](https://developers.usps.com/faq)
- [Support](https://emailus.usps.com/s/web-tools-inquiry)
- [GitHub Organization](https://github.com/USPS)
- [GitHub Repository](https://github.com/USPS/api-examples)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/united-states-postal-service-spectral-rules.yml)
- [Vocabulary](vocabulary/united-states-postal-service-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
