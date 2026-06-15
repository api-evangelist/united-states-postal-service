# United States Postal Service (united-states-postal-service)

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
