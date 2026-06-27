# Duffel (duffel)

Duffel provides a single REST API for selling travel - flights from 300+ airlines, 2M+ hotel properties (Stays), loyalty programmes, and merchant-of-record payments. The Duffel API exposes offer requests, offers, orders, seat maps, order changes and cancellations, payments, and Stays search-to-booking, with webhooks for asynchronous events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/duffel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/duffel/refs/heads/main/apis.yml)

## Tags

- Travel
- Flights
- Hotels
- Booking
- Payments

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Duffel Offer Requests API

Create an offer request describing the journey, passengers, and cabin class to initiate a flight search; airlines return matching offers. Supports listing and retrieving offer requests.

- **Human URL:** [https://duffel.com/docs/api/v2/offer-requests](https://duffel.com/docs/api/v2/offer-requests)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Offer Requests
- Flight Search
- Travel

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/offer-requests)
- [API Reference](https://duffel.com/docs/api/v2/offer-requests)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Offers API

List and retrieve offers returned for an offer request, re-price an offer against intended payment methods, and update offer passenger details before booking.

- **Human URL:** [https://duffel.com/docs/api/v2/offers](https://duffel.com/docs/api/v2/offers)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Offers
- Pricing
- Flights

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/offers)
- [API Reference](https://duffel.com/docs/api/v2/offers)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Orders API

Create flight orders from a selected offer with passenger and payment details, list and retrieve orders, update order metadata, and add ancillary services.

- **Human URL:** [https://duffel.com/docs/api/v2/orders](https://duffel.com/docs/api/v2/orders)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Orders
- Booking
- Tickets

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/orders)
- [API Reference](https://duffel.com/docs/api/v2/orders)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Seat Maps API

Retrieve the seat map for an offer, including cabin layout and available seat services with prices, so travellers can select seats during booking.

- **Human URL:** [https://duffel.com/docs/api/v2/seat-maps](https://duffel.com/docs/api/v2/seat-maps)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Seat Maps
- Ancillaries
- Flights

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/seat-maps)
- [API Reference](https://duffel.com/docs/api/v2/seat-maps)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Order Changes API

Create a pending order change to modify an existing booking, retrieve a single order change, and confirm the change to apply new flights and pricing.

- **Human URL:** [https://duffel.com/docs/api/v2/order-changes](https://duffel.com/docs/api/v2/order-changes)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Order Changes
- Rebooking
- Flights

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/order-changes)
- [API Reference](https://duffel.com/docs/api/v2/order-changes)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Order Cancellations API

Create a pending order cancellation to preview refund amounts, list and retrieve cancellations, and confirm a cancellation to refund and void the order.

- **Human URL:** [https://duffel.com/docs/api/v2/order-cancellations](https://duffel.com/docs/api/v2/order-cancellations)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Order Cancellations
- Refunds
- Flights

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/order-cancellations)
- [API Reference](https://duffel.com/docs/api/v2/order-cancellations)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Payments API

Pay for orders held with Duffel, list and retrieve payments, and use Payment Intents (where enabled) to collect card payments with Duffel as merchant of record.

- **Human URL:** [https://duffel.com/docs/api/v2/payments](https://duffel.com/docs/api/v2/payments)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Payments
- Merchant of Record
- Billing

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/payments)
- [API Reference](https://duffel.com/docs/api/v2/payments)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Stays API

Search 2M+ hotel properties, fetch detailed rates for an accommodation, create a quote to confirm availability and price, then create and manage stay bookings.

- **Human URL:** [https://duffel.com/docs/api/v2/search](https://duffel.com/docs/api/v2/search)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Stays
- Hotels
- Accommodation

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/search)
- [API Reference](https://duffel.com/docs/api/v2/search)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Duffel Webhooks API

Register webhook endpoints to receive asynchronous events such as order creation, airline-initiated changes, and ping events; list, update, delete, and ping webhooks.

- **Human URL:** [https://duffel.com/docs/api/v2/webhooks](https://duffel.com/docs/api/v2/webhooks)
- **Base URL:** `https://api.duffel.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://duffel.com/docs/api/v2/webhooks)
- [API Reference](https://duffel.com/docs/api/v2/webhooks)
- [OpenAPI](openapi/duffel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/duffel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/duffel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/duffelhq)
- [LinkedIn](https://www.linkedin.com/company/duffel)
- [Website](https://duffel.com)
- [Documentation](https://duffel.com/docs)
- [Plans](plans/duffel-plans-pricing.yml)
- [Rate Limits](rate-limits/duffel-rate-limits.yml)
- [Fin Ops](finops/duffel-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
