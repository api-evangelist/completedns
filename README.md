# CompleteDNS (completedns)
CompleteDNS is a DNS research platform that tracks nameserver modifications and domain drops, with over twenty years of history and billions of recorded changes. The CompleteDNS API exposes domain-scoped lookups that return the chronological history of nameserver changes, drop events, and parking status for a given domain. Both a current v2 API and a legacy v1 API are available, authenticated by API key.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/completedns/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - DNS, DNS History, Domain Intelligence, Domains, Nameservers, Threat Intelligence

## Timestamps

- **Created:** 2025-02-09
- **Modified:** 2026-04-28

## APIs

### CompleteDNS API v2
The CompleteDNS API v2 returns the historical nameserver record for a domain, including counts of changes and drops, years of history, and a chronologically ordered list of events. Authentication uses an API key passed as a query parameter.

**Human URL:** [https://completedns.com/api/documentation/v2](https://completedns.com/api/documentation/v2)

**Base URL:** `https://api.completedns.com/v2`

#### Tags

 - DNS History, Domains, Lookup, Nameservers

#### Properties

- [Documentation](https://completedns.com/api/documentation/v2)
- [OpenAPI](openapi/completedns-v2-openapi.yml)
- [Spectral Rules](rules/completedns-rules.yml)
- [Naftiko Capabilities](capabilities/completedns-dns-history-lookup.yml)

#### Features

- Domain DNS history lookup
- Drop event tracking
- Parking detection
- API key authentication

#### Use Cases

- Threat intelligence and domain pivot investigation
- Brand protection monitoring
- Domain acquisition research

### CompleteDNS API v1
The legacy CompleteDNS API v1 returns the historical nameserver record for a domain. Includes drop and change counts, TLD support indicator, and chronologically ordered events with added/removed nameservers. CompleteDNS recommends migrating to v2.

**Human URL:** [https://completedns.com/api/documentation/v1](https://completedns.com/api/documentation/v1)

**Base URL:** `https://api.completedns.com/v1`

#### Tags

 - DNS History, Legacy, Lookup, Nameservers

#### Properties

- [Documentation](https://completedns.com/api/documentation/v1)
- [OpenAPI](openapi/completedns-v1-openapi.yml)
- [Spectral Rules](rules/completedns-rules.yml)
- [Naftiko Capabilities](capabilities/completedns-dns-history-lookup.yml)

## Common Properties

- [Portal](https://completedns.com/)
- [Documentation](https://completedns.com/api/documentation/v2)
- [Sign Up](https://completedns.com/register)
- [Login](https://completedns.com/login)
- [Pricing](https://completedns.com/pricing)
- [Contact](https://completedns.com/contact)
- [Terms of Service](https://completedns.com/terms)
- [Privacy Policy](https://completedns.com/privacy)
- [JSON-LD Context](json-ld/completedns-context.jsonld)
- [DNS History JSON Schema](json-schema/completedns-dns-history-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
