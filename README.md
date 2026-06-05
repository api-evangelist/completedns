# CompleteDNS (completedns)

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
