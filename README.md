# Aiven (aiven)

Aiven is a managed open-source data infrastructure platform that enables developers and organizations to provision, operate, and scale open-source data services across all major cloud providers. The platform offers fully managed Apache Kafka, PostgreSQL, OpenSearch, Redis, MySQL, ClickHouse, and other data technologies through a unified REST API and console. Aiven handles infrastructure provisioning, backups, upgrades, monitoring, and security so teams can focus on building applications rather than managing infrastructure. Pricing is all-inclusive and hourly-billed, covering VMs, networking, backups, and maintenance with no hidden fees across Free, Developer, Startup, Business, and Premium tiers.

APIs.json: https://raw.githubusercontent.com/api-evangelist/aiven/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=aiven-api-evangelist&utm_content=repo

## Tags

- Managed Data Infrastructure
- Apache Kafka
- PostgreSQL
- OpenSearch
- ClickHouse
- Redis
- MySQL
- Open Source
- Cloud Database
- DBaaS
- Data Streaming
- Data Platform

## APIs

### Aiven REST API

The Aiven REST API provides programmatic access to the Aiven platform for provisioning and managing open-source data services including Apache Kafka, PostgreSQL, OpenSearch, Redis, MySQL, ClickHouse, and more. The API supports full lifecycle management of services, projects, organizations, billing, VPCs, integrations, and user access controls. Authentication is via personal access tokens or OAuth2 authorization code flow with granular scopes.

- **Base URL:** https://api.aiven.io/v1
- **Documentation:** https://aiven.io/docs/tools/api
- **API Reference:** https://api.aiven.io/doc/
- **Authentication:** Token (aivenv1) or OAuth2

## Plans / Rate Limits / FinOps

- **Plans & Pricing:** [plans/aiven-plans-pricing.yml](plans/aiven-plans-pricing.yml) — Free, Developer ($5+/mo), Startup ($200+/mo), Business ($500+/mo), Premium ($1,900+/mo), Custom ($5,000+/mo); hourly all-inclusive billing; 30-day/$300 free trial
- **Rate Limits:** [rate-limits/aiven-rate-limits.yml](rate-limits/aiven-rate-limits.yml) — No publicly disclosed numeric limits; HTTP 429 returned on excess; implement exponential backoff
- **FinOps:** [finops/aiven-finops.yml](finops/aiven-finops.yml) — Hourly all-inclusive billing; power-off to stop charges; dynamic disk scaling; Datadog/CloudWatch/Grafana cost visibility

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://aiven.io |
| Documentation | https://aiven.io/docs |
| GitHub Org | https://github.com/aiven |
| GitHub Org (Open Source) | https://github.com/Aiven-Open |
| LinkedIn | https://www.linkedin.com/company/aiven |
| Blog | https://aiven.io/blog |
| Pricing | https://aiven.io/pricing |
| Status Page | https://status.aiven.io |
| X / Twitter | https://x.com/aiven_io |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
