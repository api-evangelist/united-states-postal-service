# United States Postal Service (united-states-postal-service)

The United States Postal Service (USPS) provides a modern REST API platform at developers.usps.com that gives ecommerce websites, shipping software, and logistics systems access to postal data and services. APIs cover address validation, package tracking, domestic and international shipping labels, pricing, carrier pickup scheduling, location finding, and Informed Delivery campaign management. The legacy Web Tools platform was retired January 25, 2026, with all functionality migrated to the new OAuth 2.0-secured API platform.

**URL:** [Visit Developer Portal](https://developers.usps.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Government, Postal Service, Shipping, Logistics, Address Validation, Package Tracking

## Timestamps

- **Created:** 2024/01/01
- **Modified:** 2026-05-03

## APIs

### USPS Addresses API

Validates and corrects address information to USPS specifications, eliminating errors and improving package delivery. Supports full address standardization, city and state lookup by ZIP Code, and ZIP Code lookup by address.

**Human URL:** [https://developers.usps.com/addressesv3](https://developers.usps.com/addressesv3)

#### Tags:

 - Addresses, Address Validation, Government

#### Properties

- [Documentation](https://developers.usps.com/addressesv3)
- [OpenAPI](openapi/united-states-postal-service-addresses-openapi.yml)
- [Address Schema](json-schema/addresses-address-schema.json)
- [City State Schema](json-schema/addresses-city-state-schema.json)
- [Address Structure](json-structure/addresses-address-structure.json)
- [JSON-LD Context](json-ld/united-states-postal-service-addresses-context.jsonld)
- [Address Example](examples/addresses-address-example.json)

### USPS Tracking API

Returns tracking status and related details for a given USPS package, including scan events with date, time, and location. Supports single and batch package tracking. Version 3.2 includes enhanced scan event extract notifications.

**Human URL:** [https://developers.usps.com/trackingv3r2](https://developers.usps.com/trackingv3r2)

#### Tags:

 - Tracking, Package Tracking, Government

#### Properties

- [Documentation](https://developers.usps.com/trackingv3r2)
- [OpenAPI](openapi/united-states-postal-service-tracking-openapi.yml)
- [Tracking Event Schema](json-schema/tracking-tracking-event-schema.json)
- [Tracking Event Structure](json-structure/tracking-tracking-event-structure.json)
- [JSON-LD Context](json-ld/united-states-postal-service-tracking-context.jsonld)
- [Tracking Event Example](examples/tracking-tracking-event-example.json)

### USPS Domestic Prices API

Provides postage pricing for domestic USPS shipments based on origin and destination ZIP Codes, weight, dimensions, and mail class. Supports base rate lookups, extra service rates (insurance, signature confirmation, etc.), and total rate calculations.

**Human URL:** [https://developers.usps.com/domesticpricesv3](https://developers.usps.com/domesticpricesv3)

#### Tags:

 - Pricing, Postage, Shipping, Government

#### Properties

- [Documentation](https://developers.usps.com/domesticpricesv3)
- [OpenAPI](openapi/united-states-postal-service-domestic-prices-openapi.yml)
- [Base Rate Request Schema](json-schema/domestic-prices-base-rate-request-schema.json)
- [Base Rate Request Structure](json-structure/domestic-prices-base-rate-request-structure.json)
- [JSON-LD Context](json-ld/united-states-postal-service-domestic-context.jsonld)
- [Base Rate Request Example](examples/domestic-prices-base-rate-request-example.json)

### USPS Carrier Pickup API

Enables free carrier pickup scheduling for next-day service, Monday through Saturday, excluding federal holidays. Supports creating, retrieving, updating, and canceling pickup requests at residential and commercial addresses.

**Human URL:** [https://developers.usps.com/carrierpickupv3](https://developers.usps.com/carrierpickupv3)

#### Tags:

 - Carrier Pickup, Shipping, Government

#### Properties

- [Documentation](https://developers.usps.com/carrierpickupv3)
- [OpenAPI](openapi/united-states-postal-service-carrier-pickup-openapi.yml)
- [Pickup Request Schema](json-schema/carrier-pickup-pickup-request-schema.json)
- [Pickup Request Structure](json-structure/carrier-pickup-pickup-request-structure.json)
- [JSON-LD Context](json-ld/united-states-postal-service-carrier-context.jsonld)
- [Pickup Request Example](examples/carrier-pickup-pickup-request-example.json)

### USPS International Prices API

Provides pricing for international USPS products based on shipment characteristics including destination country, weight, dimensions, and service class.

**Human URL:** [https://developers.usps.com/internationalpricesv3](https://developers.usps.com/internationalpricesv3)

#### Tags:

 - International, Pricing, Postage, Government

#### Properties

- [Documentation](https://developers.usps.com/internationalpricesv3)

### USPS Domestic Labels API

Creates domestic shipping labels with barcodes in multiple formats and generates Shipping Services Files. Requires USPS Ship enrollment and Enterprise Payment Account.

**Human URL:** [https://developers.usps.com/domesticlabelsv3](https://developers.usps.com/domesticlabelsv3)

#### Tags:

 - Labels, Shipping, Government

#### Properties

- [Documentation](https://developers.usps.com/domesticlabelsv3)

### USPS International Labels API

Creates international shipping labels and generates required Shipping Services Files for customs compliance.

**Human URL:** [https://developers.usps.com/internationallabelsv3](https://developers.usps.com/internationallabelsv3)

#### Tags:

 - International, Labels, Shipping, Government

#### Properties

- [Documentation](https://developers.usps.com/internationallabelsv3)

### USPS Locations API

Identifies drop-off facilities and destination entry points for various USPS services. Supports post office locator and drop-off location finder.

**Human URL:** [https://developers.usps.com/locationsv3](https://developers.usps.com/locationsv3)

#### Tags:

 - Locations, Post Offices, Government

#### Properties

- [Documentation](https://developers.usps.com/locationsv3)

### USPS Service Standards API

Provides delivery benchmarks showing expected transit times between origin and destination ZIP Codes for USPS mail classes.

**Human URL:** [https://developers.usps.com/standardsv3](https://developers.usps.com/standardsv3)

#### Tags:

 - Service Standards, Delivery, Government

#### Properties

- [Documentation](https://developers.usps.com/standardsv3)

### USPS Shipping Options API

Returns a comprehensive list of pricing, service standards, and shipping options for USPS products in a single API call.

**Human URL:** [https://developers.usps.com/shippingoptionsv3](https://developers.usps.com/shippingoptionsv3)

#### Tags:

 - Shipping, Pricing, Government

#### Properties

- [Documentation](https://developers.usps.com/shippingoptionsv3)

### USPS SCAN Forms API

Links multiple domestic and international labels through a single electronic file number for batch shipping operations.

**Human URL:** [https://developers.usps.com/scanv3](https://developers.usps.com/scanv3)

#### Tags:

 - SCAN Forms, Shipping, Government

#### Properties

- [Documentation](https://developers.usps.com/scanv3)

### USPS OAuth API

Industry-standard OAuth 2.0 Client Credentials authentication protecting access to all USPS APIs.

**Human URL:** [https://developers.usps.com/Oauth](https://developers.usps.com/Oauth)

#### Tags:

 - Authentication, OAuth, Government

#### Properties

- [Documentation](https://developers.usps.com/Oauth)
- [Authentication Guide](https://developers.usps.com/getting-started)

## Common Properties

- [Portal](https://developers.usps.com/)
- [Getting Started](https://developers.usps.com/getting-started)
- [API Catalog](https://developers.usps.com/apis)
- [Terms of Service](https://developers.usps.com/terms-and-conditions)
- [FAQ](https://developers.usps.com/faq)
- [Support](https://emailus.usps.com/s/web-tools-inquiry)
- [GitHub Organization](https://github.com/USPS)
- [API Examples](https://github.com/USPS/api-examples)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Authentication | Secure API access using industry-standard OAuth 2.0 Client Credentials flow with Bearer Token authentication. |
| RESTful Architecture | All APIs follow RESTful conventions with JSON request and response bodies. |
| Sandbox Testing Environment | Testing Environment for Mailers (TEM) at apis-tem.usps.com for safe API testing before going to production. |
| Address Standardization | USPS Coding Accuracy Support System (CASS) compliant address validation and standardization. |
| Delivery Point Validation | DPV confirmation codes ensure packages can be delivered to the validated address. |
| Real-Time Tracking | Live package tracking with scan events, timestamps, and location details from USPS systems. |
| Webhook Subscriptions | Event-driven subscription APIs for tracking events, adjustments, and disputes delivered via webhooks. |
| Batch Processing | Support for bulk operations including multiple tracking lookups and SCAN Form generation. |

## Use Cases

| Name | Description |
|------|-------------|
| E-Commerce Shipping Integration | Calculate shipping rates, generate labels, and provide package tracking directly within e-commerce checkout flows. |
| Address Verification at Checkout | Validate and standardize customer addresses during checkout to reduce failed deliveries and return rates. |
| Shipping Label Generation | Programmatically create domestic and international USPS shipping labels with barcodes for fulfillment operations. |
| Carrier Pickup Automation | Schedule and manage USPS carrier pickups automatically based on order fulfillment triggers. |
| Logistics Rate Shopping | Compare USPS service options and pricing to select the most cost-effective shipping method. |
| Delivery Time Estimation | Display accurate expected delivery dates to customers using USPS service standards data. |
| Post Office Finder | Help customers locate the nearest USPS facility for drop-offs or in-person services. |
| Informed Delivery Campaigns | Enhance customer engagement by adding digital content to mail pieces viewed through Informed Delivery. |

## Integrations

| Name | Description |
|------|-------------|
| Shopify | USPS shipping integration available through Shopify Shipping for label generation and rate calculation. |
| WooCommerce | WooCommerce shipping plugins integrate USPS APIs for rate calculation and label printing. |
| Magento | Adobe Commerce and Magento integrate USPS for shipping rate display and fulfillment. |
| ShipStation | ShipStation multi-carrier shipping platform integrates USPS APIs for ecommerce fulfillment. |
| EasyPost | EasyPost shipping API aggregator provides access to USPS services alongside other carriers. |
| Stamps.com | Stamps.com and Pitney Bowes shipping platforms integrate USPS APIs for postage and label printing. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [USPS Addresses API](openapi/united-states-postal-service-addresses-openapi.yml)
- [USPS Tracking API](openapi/united-states-postal-service-tracking-openapi.yml)
- [USPS Domestic Prices API](openapi/united-states-postal-service-domestic-prices-openapi.yml)
- [USPS Carrier Pickup API](openapi/united-states-postal-service-carrier-pickup-openapi.yml)

### JSON Schema

- [addresses-address-schema.json](json-schema/addresses-address-schema.json)
- [addresses-city-state-schema.json](json-schema/addresses-city-state-schema.json)
- [addresses-zip-code-result-schema.json](json-schema/addresses-zip-code-result-schema.json)
- [carrier-pickup-pickup-address-schema.json](json-schema/carrier-pickup-pickup-address-schema.json)
- [carrier-pickup-pickup-package-schema.json](json-schema/carrier-pickup-pickup-package-schema.json)
- [carrier-pickup-pickup-request-schema.json](json-schema/carrier-pickup-pickup-request-schema.json)
- [carrier-pickup-pickup-response-schema.json](json-schema/carrier-pickup-pickup-response-schema.json)
- [domestic-prices-base-rate-request-schema.json](json-schema/domestic-prices-base-rate-request-schema.json)
- [domestic-prices-rate-response-schema.json](json-schema/domestic-prices-rate-response-schema.json)
- [tracking-tracking-event-schema.json](json-schema/tracking-tracking-event-schema.json)
- [tracking-tracking-result-schema.json](json-schema/tracking-tracking-result-schema.json)
- [tracking-multiple-tracking-request-schema.json](json-schema/tracking-multiple-tracking-request-schema.json)

### JSON Structure

- [addresses-address-structure.json](json-structure/addresses-address-structure.json)
- [tracking-tracking-event-structure.json](json-structure/tracking-tracking-event-structure.json)
- [domestic-prices-base-rate-request-structure.json](json-structure/domestic-prices-base-rate-request-structure.json)
- [carrier-pickup-pickup-request-structure.json](json-structure/carrier-pickup-pickup-request-structure.json)

### JSON-LD

- [Addresses Context](json-ld/united-states-postal-service-addresses-context.jsonld)
- [Tracking Context](json-ld/united-states-postal-service-tracking-context.jsonld)
- [Domestic Prices Context](json-ld/united-states-postal-service-domestic-context.jsonld)
- [Carrier Pickup Context](json-ld/united-states-postal-service-carrier-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [USPS Addresses API](capabilities/shared/addresses.yaml) — 3 operations for address validation and ZIP Code lookup
- [USPS Tracking API](capabilities/shared/tracking.yaml) — 2 operations for package tracking
- [USPS Domestic Prices API](capabilities/shared/domestic-prices.yaml) — 3 operations for postage rate search
- [USPS Carrier Pickup API](capabilities/shared/carrier-pickup.yaml) — 4 operations for pickup scheduling

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [E-Commerce Shipping](capabilities/ecommerce-shipping.yaml) | Addresses, Domestic Prices, Carrier Pickup | 8 | E-Commerce Developer, Shipping Manager |
| [Package Tracking](capabilities/package-tracking.yaml) | Tracking, Addresses | 3 | Customer Service Agent, Logistics Manager |

## Vocabulary

- [United States Postal Service Vocabulary](vocabulary/united-states-postal-service-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 8 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [USPS Spectral Rules](rules/united-states-postal-service-spectral-rules.yml) — 33 rules across 13 categories enforcing USPS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
