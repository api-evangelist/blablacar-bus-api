# BlaBlaCar Bus API (blablacar-bus-api)

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

BlaBlaCar Bus API enables transport operators, OTAs, and travel aggregators to integrate with BlaBlaCar's coach and bus booking platform across Europe. The API provides access to route search, seat availability, booking creation, ticket management, and passenger notifications. BlaBlaCar Bus operates coach services across France, Germany, Poland, Spain, Italy, Ukraine, and other European markets under the BlaBlaBus brand.

**URL:** [https://bus-api.blablacar.com/](https://bus-api.blablacar.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Booking, Buses, Coach, Europe, Mobility, Ticketing, Transportation, Travel

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-04-19

## APIs

### BlaBlaCar Bus API
REST API for integrating with BlaBlaCar Bus (formerly BlaBlaBus) coach booking platform. Enables partners to search routes, check seat availability, create bookings, manage tickets, and receive booking confirmations. Targeted at OTAs, travel aggregators, mobility platforms, and enterprise travel management companies operating in European markets.

**Human URL:** [https://bus-api.blablacar.com/](https://bus-api.blablacar.com/)

#### Tags:

 - Booking, Buses, Coach, Europe, Ticketing, Transportation

#### Properties

- [Documentation](https://bus-api.blablacar.com/)
- [OpenAPI](openapi/blablacar-bus-api-openapi.yaml)

## Common Properties

- [Website](https://www.blablacar.com/bus)
- [Documentation](https://bus-api.blablacar.com/)
- [GitHub Organization](https://github.com/blablacar)
- [Terms of Service](https://www.blablacar.com/about-us/terms-and-conditions)
- [Privacy Policy](https://www.blablacar.com/about-us/privacy-policy)
- [SpectralRules](rules/blablacar-bus-api-spectral-rules.yml)
- [NaftikoCapability](capabilities/blablacar-bus-booking.yaml)
- [Vocabulary](vocabulary/blablacar-bus-api-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Route Search | Search available coach routes between origin and destination stations across European markets with departure dates and passenger counts. |
| Seat Availability | Check real-time seat availability and pricing for specific routes, trips, and departure times. |
| Booking Creation | Create confirmed bookings for passengers with seat selection, passenger details, and payment processing integration. |
| Ticket Management | Retrieve, modify, and cancel tickets with electronic ticket delivery and QR code generation. |
| Station Information | Access comprehensive station data including names, addresses, GPS coordinates, and amenities across the BlaBlaCar Bus network. |
| Multi-Market Coverage | Single API integration covering coach routes across France, Germany, Poland, Spain, Italy, Ukraine, and other European markets. |

## Use Cases

| Name | Description |
|------|-------------|
| OTA Integration | Online travel agencies can search and book BlaBlaCar Bus routes alongside trains, flights, and car rentals for multimodal journey planning. |
| Travel Aggregator | Price comparison and travel search engines can surface BlaBlaCar Bus options in coach and intercity bus search results. |
| Corporate Travel | Enterprise travel management companies can include BlaBlaCar Bus as an affordable intercity transport option for business travelers. |
| Mobility Platform | Mobility-as-a-Service platforms can integrate BlaBlaCar Bus as a long-distance transport mode in multimodal journey planning. |
| Reseller Programs | Authorized resellers can distribute BlaBlaCar Bus tickets through their own branded channels and sales touchpoints. |

## Integrations

| Name | Description |
|------|-------------|
| BlaBlaCar Carpooling | BlaBlaCar Bus complements the carpooling marketplace, enabling multimodal journey planning combining bus and ridesharing. |
| Google Maps Platform | Station coordinates and route data can be overlaid on mapping platforms for journey visualization. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [BlaBlaCar Bus API](openapi/blablacar-bus-api-openapi.yaml)

### JSON Schema

- [Route](json-schema/blablacar-bus-api-route-schema.json)
- [Trip](json-schema/blablacar-bus-api-trip-schema.json)
- [Booking](json-schema/blablacar-bus-api-booking-schema.json)
- [Ticket](json-schema/blablacar-bus-api-ticket-schema.json)
- [Station](json-schema/blablacar-bus-api-station-schema.json)

### JSON Structure

- [Route](json-structure/blablacar-bus-api-route-structure.json)
- [Trip](json-structure/blablacar-bus-api-trip-structure.json)
- [Booking](json-structure/blablacar-bus-api-booking-structure.json)
- [Ticket](json-structure/blablacar-bus-api-ticket-structure.json)
- [Station](json-structure/blablacar-bus-api-station-structure.json)

### JSON-LD

- [BlaBlaCar Bus API Context](json-ld/blablacar-bus-api-context.jsonld)

### Examples

- [Route Example](examples/blablacar-bus-api-route-example.json)
- [Trip Example](examples/blablacar-bus-api-trip-example.json)
- [Booking Example](examples/blablacar-bus-api-booking-example.json)
- [Ticket Example](examples/blablacar-bus-api-ticket-example.json)
- [Station Example](examples/blablacar-bus-api-station-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [BlaBlaCar Bus API](capabilities/shared/blablacar-bus-api.yaml) — 7 operations for route search, trip availability, booking, ticket, and station management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [BlaBlaCar Bus Booking](capabilities/blablacar-bus-booking.yaml) | BlaBlaCar Bus API | 7 | Travel Agents, OTA Developers, Corporate Travel Managers, Travelers |

## Vocabulary

- [BlaBlaCar Bus API Vocabulary](vocabulary/blablacar-bus-api-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [BlaBlaCar Bus API Spectral Rules](rules/blablacar-bus-api-spectral-rules.yml) — 33 rules across 12 categories enforcing BlaBlaCar Bus API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
