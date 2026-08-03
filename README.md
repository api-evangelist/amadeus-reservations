# Amadeus Reservations (amadeus-reservations)

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

Amadeus Reservations provides APIs for creating and managing travel bookings including flight orders, hotel reservations, and ground transfer bookings. These APIs power the full reservation lifecycle for online travel agencies, corporate travel platforms, and travel management companies, connecting to Amadeus's global distribution network of airlines, hotels, and transfer operators.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Booking, Flights, Hotels, Reservations, Travel

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Hotel Booking API
The Amadeus Hotel Booking API lets you complete hotel reservations at over 150,000 hotels and accommodations worldwide. Create bookings using hotel offer IDs returned by the Hotel Search API, manage guest details, and receive booking confirmations with property reference numbers.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)

#### Tags:

 - Booking, Hotels, Reservations, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-booking/api-reference)
- [OpenAPI](openapi/amadeus-reservations-hotel-booking-openapi.yaml)

### Flight Create Orders API
The Amadeus Flight Create Orders API enables creation of flight bookings from flight offers returned by the Flight Offers Search API. Create confirmed airline reservations for one or more travelers, receive booking confirmations with PNR codes, and manage the complete flight order lifecycle from creation to ticketing.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)

#### Tags:

 - Booking, Flights, Orders, Reservations, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-create-orders/api-reference)
- [OpenAPI](openapi/amadeus-reservations-flight-create-orders-openapi.yaml)

### Flight Order Management API
The Amadeus Flight Order Management API allows you to retrieve and cancel existing flight orders. Look up booking details using the order ID, retrieve full itinerary and traveler information, and cancel confirmed reservations subject to airline fare rules.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)

#### Tags:

 - Flights, Management, Orders, Reservations, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-order-management)
- [OpenAPI](openapi/amadeus-reservations-flight-order-management-openapi.yaml)

### Transfer Booking API
The Amadeus Transfer Booking API allows you to book ground transfer services including airport taxis, private cars, and shuttle services. Create transfer reservations from search results returned by the Transfer Search API, providing pickup and drop-off details with traveler information.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking)

#### Tags:

 - Booking, Ground Transport, Reservations, Transfers, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-booking)
- [OpenAPI](openapi/amadeus-reservations-transfer-booking-openapi.yaml)

### Transfer Management API
The Amadeus Transfer Management API enables management of confirmed ground transfer bookings. Cancel existing transfer reservations and retrieve booking details using transfer order IDs obtained during the booking process.

**Human URL:** [https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)

#### Tags:

 - Ground Transport, Management, Reservations, Transfers, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/cars-and-transfers/api-doc/transfer-management)
- [OpenAPI](openapi/amadeus-reservations-transfer-management-openapi.yaml)

## Common Properties

- [Portal](https://developers.amadeus.com/)
- [GettingStarted](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [SignUp](https://developers.amadeus.com/register)
- [Pricing](https://developers.amadeus.com/pricing)
- [Blog](https://developers.amadeus.com/blog)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Support](https://developers.amadeus.com/support)
- [TermsOfService](https://developers.amadeus.com/legal/terms-and-conditions)
- [PrivacyPolicy](https://developers.amadeus.com/legal/privacy-policy)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [Python SDK](https://github.com/amadeus4dev/amadeus-python)
- [Node.js SDK](https://github.com/amadeus4dev/amadeus-node)
- [Java SDK](https://github.com/amadeus4dev/amadeus-java)
- [StatusPage](https://developers.amadeus.com/status)

## Features

| Name | Description |
|------|-------------|
| Hotel Booking at Scale | Book rooms at over 150,000 hotels worldwide using Amadeus GDS connectivity, with instant confirmation and property reference numbers. |
| Flight Order Creation | Create confirmed airline reservations with full PNR support across hundreds of airlines in the Amadeus inventory. |
| Multi-Traveler Bookings | Create reservations for multiple travelers in a single API call, managing individual passenger details and fare assignments. |
| Ground Transfer Bookings | Book airport taxis, private cars, and shuttle services with real-time availability and instant confirmation. |
| Order Management | Retrieve and cancel existing flight and transfer reservations programmatically with full booking detail access. |

## Use Cases

| Name | Description |
|------|-------------|
| Online Travel Agency Booking Engine | Power end-to-end booking flows for flights, hotels, and transfers on consumer-facing OTA platforms. |
| Corporate Travel Management | Enable corporate travel managers to book and manage business travel including flights and hotel accommodations with policy compliance. |
| Travel App Integration | Integrate booking capabilities into mobile travel apps providing users with seamless reservation creation from search to confirmation. |
| Itinerary Builder | Build complete multi-modal itineraries combining flight bookings with hotel reservations and ground transfers through unified API access. |
| Travel Chatbot | Enable AI-powered travel assistants to create and manage bookings on behalf of travelers through conversational interfaces. |

## Integrations

| Name | Description |
|------|-------------|
| Amadeus Flight Offers Search | Flight Create Orders works with Flight Offers Search to convert priced flight offers into confirmed airline reservations. |
| Amadeus Hotel Search | Hotel Booking completes the hotel shopping flow started by Hotel Search, converting hotel offers into confirmed reservations. |
| Amadeus Transfer Search | Transfer Booking confirms ground transportation offers returned by the Transfer Search API. |
| Amadeus Flight Offers Price | Validate and reprice flight offers before booking to ensure accurate pricing at time of reservation creation. |
| Amadeus Hotel Name Autocomplete | Use Hotel Name Autocomplete to let users search for properties before fetching offers and creating hotel bookings. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amadeus Hotel Booking OpenAPI](openapi/amadeus-reservations-hotel-booking-openapi.yaml)
- [Amadeus Flight Create Orders OpenAPI](openapi/amadeus-reservations-flight-create-orders-openapi.yaml)
- [Amadeus Flight Order Management OpenAPI](openapi/amadeus-reservations-flight-order-management-openapi.yaml)
- [Amadeus Transfer Booking OpenAPI](openapi/amadeus-reservations-transfer-booking-openapi.yaml)
- [Amadeus Transfer Management OpenAPI](openapi/amadeus-reservations-transfer-management-openapi.yaml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Hotel Booking API](capabilities/shared/hotel-booking.yaml) — 1 operation for hotel reservation creation
- [Flight Orders API](capabilities/shared/flight-orders.yaml) — 3 operations for flight order creation, retrieval, and cancellation
- [Transfer Booking API](capabilities/shared/transfer-booking.yaml) — 2 operations for transfer booking and cancellation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Travel Booking](capabilities/travel-booking.yaml) | Hotel Booking API, Flight Create Orders API, Flight Order Management API, Transfer Booking API, Transfer Management API | 6 | Travel Booking Agent, Travel Chatbot Developer |

## Vocabulary

- [Amadeus Reservations Vocabulary](vocabulary/amadeus-reservations-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amadeus Reservations Spectral Rules](rules/amadeus-reservations-spectral-rules.yml) — 20 rules across 7 categories enforcing Amadeus Reservations API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
