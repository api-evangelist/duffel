# Duffel (duffel)

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
