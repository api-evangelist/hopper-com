# Hopper (hopper-com)

Hopper is a Boston- and Montreal-based travel booking platform and B2B travel fintech provider serving more than 120 million travelers globally. Its consumer app aggregates flights, hotels, rental cars, and homes alongside proprietary price prediction and a family of "for any reason" fintech ancillaries — Price Freeze, Cancel For Any Reason (CFAR), Change For Any Reason, Leave For Any Reason, and Disruption Guarantee. Through its B2B division, Hopper Technology Solutions (HTS), the company licenses those same fintech ancillaries, agentic AI customer service (HTS Assist), white-label travel agency products (HTS Stays, HTS Cars, HTS Packages), and travel loyalty portals to airlines, banks, and travel providers. HTS exposes a documented OAuth2-secured REST API — the HTS Airline API v1.1 — for embedding CFAR and Disruption Guarantee contracts in airline booking flows, with OpenAPI-generated SDKs for Java, .NET, Angular, and iOS, plus a JavaScript SDK for hotel price-freeze integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hopper-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hopper-com/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Travel
- Travel Fintech
- Price Prediction
- Cancel For Any Reason
- Disruption Guarantee
- Price Freeze
- Airlines
- Hotels
- Car Rental
- Vacation Rentals
- Ancillary Revenue
- B2B
- Loyalty
- Agentic AI

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### HTS Airline API

The Hopper Technology Solutions Airline API lets airlines embed Hopper's ancillary fintech products — Cancel For Any Reason (CFAR) and Disruption Guarantee (DG) — directly into their booking flow. Airlines call the API to create a user session, request CFAR or DG offers for an itinerary, bind an offer into a contract, take payment, update itinerary slices, and later exercise the contract (cancel, refund, or rebook) on behalf of the customer. The API is OAuth2 Client Credentials authenticated, uses an HC-Session-ID correlation header, and exposes 23 operations under https://airlines-api.hopper.com/airline/v1.1.

- **Human URL:** [https://github.com/hopper/hc-airlines-java](https://github.com/hopper/hc-airlines-java)
- **Base URL:** `https://airlines-api.hopper.com/airline/v1.1`

#### Tags

- Airlines
- Travel Fintech
- Cancel For Any Reason
- Disruption Guarantee
- Ancillary Revenue
- OAuth2

#### Properties

- [OpenAPI](openapi/hopper-airlines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hopper-airlines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hopper-airlines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://github.com/hopper/hc-airlines-java)
- [SDK](https://github.com/hopper/hc-airlines-java)
- [SDK](https://github.com/hopper/hts-airlines-dotnet)
- [SDK](https://github.com/hopper/hc-airlines-angular)

## Common Properties

- [Website](https://www.hopper.com)
- [B2 B](https://hts.hopper.com)
- [Product](https://hts.hopper.com/cancel-for-any-reason)
- [Product](https://hts.hopper.com/disruption-assistance-for-any-reason)
- [Product](https://hts.hopper.com/hts-stays)
- [Product](https://hts.hopper.com/hts-cars)
- [Product](https://hts.hopper.com/hts-packages)
- [Product](https://hts.hopper.com/travel-loyalty-portals)
- [Product](https://hts.hopper.com/hts-assist)
- [Company](https://www.hopper.com/about)
- [Press](https://www.hopper.com/press)
- [Careers](https://www.hopper.com/careers)
- [Contact](https://hts.hopper.com/contact)
- [Git Hub](https://github.com/hopper)
- [Twitter](https://twitter.com/hopper)
- [LinkedIn](https://www.linkedin.com/company/hopper)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
