# American Airlines (american-airlines)

American Airlines is one of the world's largest airlines, operating an extensive domestic and international route network. The company's Runway developer experience platform, built on Spotify's Backstage, provides internal developer tooling and API management for engineering teams. American Airlines exposes flight data, status, and booking capabilities through its developer portal.

**URL:** [https://developer.aa.com/](https://developer.aa.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Airlines, Aviation, Flights, Travel, Booking, Developer Experience

## Timestamps

- **Created:** 2026-04-19
- **Modified:** 2026-04-19

## APIs

### American Airlines Runway Developer API

Runway is American Airlines' developer experience platform providing APIs for flight operations, booking, scheduling, and travel services. Built on Spotify's Backstage platform.

**Human URL:** [https://developer.aa.com/](https://developer.aa.com/)

#### Tags

 - Airlines, Aviation, Flights, Travel, Booking

#### Properties

- [Documentation](https://developer.aa.com/)
- [OpenAPI](openapi/american-airlines-runway-developer-api-openapi.yml)

## Common Properties

- [Website](https://www.aa.com/)
- [DeveloperPortal](https://developer.aa.com/)
- [GitHubOrganization](https://github.com/AmericanAirlines)
- [Blog](https://tech.aa.com/)

## Features

| Name | Description |
|------|-------------|
| Runway Developer Experience Platform | Internal developer platform built on Spotify's Backstage providing centralized API management and service catalog. |
| Flight Data APIs | APIs for querying flight schedules, routes, status, and operational data. |
| Booking and Reservation APIs | APIs supporting flight search, booking, and reservation management. |
| Built-In API Management | Integrated API management with security and authentication toggles. |
| Service Mesh Integration | Kong-based service mesh for reliable microservices communication. |
| Open Source Tooling | Open-source tools including Flight Engine mock API and Hangar hackathon management. |

## Use Cases

| Name | Description |
|------|-------------|
| Flight Search and Booking | Travel agencies integrate flight availability and booking APIs. |
| Flight Status Tracking | Applications query real-time flight status information. |
| Internal Developer Tooling | Engineering teams use Runway to self-service infrastructure and API catalog. |
| Hackathon and Innovation | Open-source Hangar tool enables hackathon management for tech events. |

## Integrations

| Name | Description |
|------|-------------|
| Spotify Backstage | Runway developer portal is built on Spotify's Backstage platform. |
| Kong Service Mesh | American Airlines uses Kong's Kuma service mesh for microservices networking. |
| HashiCorp Vault | Integration with HashiCorp Vault for secrets management. |
| Dynatrace | Python API client for Dynatrace integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [American Airlines Runway Developer API](openapi/american-airlines-runway-developer-api-openapi.yml)

### JSON Schema

- [5 JSON Schema files](json-schema/)

### JSON Structure

- [5 JSON Structure files](json-structure/)

### JSON-LD

- [american-airlines-runway-context.jsonld](json-ld/american-airlines-runway-context.jsonld)

### Examples

- [5 example JSON files](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [American Airlines Runway API](capabilities/shared/runway-api.yaml) — 2 operations for flight search and status

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Flight Operations](capabilities/flight-operations.yaml) | Runway API | 2 | Travel Technology Developer, Booking Agent |

## Vocabulary

- [American Airlines Vocabulary](vocabulary/american-airlines-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 5 actions, 1 workflow, and 2 personas

## Rules

- [American Airlines Spectral Rules](rules/american-airlines-spectral-rules.yml) — 12 rules across 6 categories enforcing American Airlines API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
