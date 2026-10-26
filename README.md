# Hopper (hopper-com)

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
