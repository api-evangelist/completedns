# CompleteDNS (completedns)

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

CompleteDNS is a DNS research platform that tracks nameserver modifications and domain drops, with over twenty years of history and billions of recorded changes. The CompleteDNS API exposes domain-scoped lookups that return the chronological history of nameserver changes, drop events, and parking status for a given domain. Both a current v2 API and a legacy v1 API are available, authenticated by API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- DNS
- DNS History
- Domain Intelligence
- Domains
- Nameservers
- Threat Intelligence

## Timestamps

- **Created:** 2025-02-09
- **Modified:** 2026-05-19

## APIs

### CompleteDNS API v2

The CompleteDNS API v2 returns the historical nameserver record for a domain, including counts of changes and drops, years of history, and a chronologically ordered list of events. Authentication uses an API key passed as a query parameter.

- **Human URL:** [https://completedns.com/api/documentation/v2](https://completedns.com/api/documentation/v2)
- **Base URL:** `https://api.completedns.com/v2`

#### Tags

- DNS History
- Domains
- Lookup
- Nameservers

#### Properties

- [Documentation](https://completedns.com/api/documentation/v2)
- [OpenAPI](openapi/completedns-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/completedns-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/completedns-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/completedns-rules.yml)

### CompleteDNS API v1

The CompleteDNS API v1 (legacy) returns the historical nameserver record for a domain. Includes drop and change counts, TLD support indicator, and chronologically ordered events with added/removed nameservers. CompleteDNS recommends migrating to v2.

- **Human URL:** [https://completedns.com/api/documentation/v1](https://completedns.com/api/documentation/v1)
- **Base URL:** `https://api.completedns.com/v1`

#### Tags

- DNS History
- Legacy
- Lookup
- Nameservers

#### Properties

- [Documentation](https://completedns.com/api/documentation/v1)
- [OpenAPI](openapi/completedns-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/completedns-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/completedns-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral  Rules](rules/completedns-rules.yml)

## Common Properties

- [Portal](https://completedns.com/)
- [Documentation](https://completedns.com/api/documentation/v2)
- [Sign Up](https://completedns.com/register)
- [Login](https://completedns.com/login)
- [Pricing](https://completedns.com/pricing)
- [Contact](https://completedns.com/contact)
- [Terms of Service](https://completedns.com/terms)
- [Privacy Policy](https://completedns.com/privacy)
- [JSON-LD](json-ld/completedns-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/completedns-dns-history-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
