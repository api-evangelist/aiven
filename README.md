# Aiven (aiven)

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
