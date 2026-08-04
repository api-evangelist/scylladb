# ScyllaDB (scylladb)

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

ScyllaDB is a high-performance distributed NoSQL database engineered for real-time, data-intensive applications, offering close-to-the-metal architecture with predictable single-digit millisecond latencies and millions of operations per second. It is fully compatible with Apache Cassandra's CQL interface and Amazon DynamoDB's API (via Project Alternator). ScyllaDB Cloud is a fully managed database-as-a-service available on AWS and GCP with a REST management API for automating cluster lifecycle operations.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/scylladb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scylladb/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=scylladb-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=scylladb-api-evangelist&utm_content=repo)

## Tags

- Database
- NoSQL
- Cassandra Compatible
- DynamoDB Compatible
- Distributed Database
- Real-Time
- Vector Search
- Cloud Database

## APIs

### ScyllaDB Cloud Management API

REST API for programmatic access to ScyllaDB Cloud, enabling automation of cluster provisioning, resizing, deletion, VPC peering, firewall rules, datacenter management, vector search nodes, and account configuration. Authenticated via personal access tokens.

- Documentation: [https://cloud.docs.scylladb.com/stable/api-docs/](https://cloud.docs.scylladb.com/stable/api-docs/)
- OpenAPI: [https://api.cloud.scylladb.com/api-docs.json](https://api.cloud.scylladb.com/api-docs.json)

### ScyllaDB Admin REST API

Node-level administrative REST API exposing endpoints to check and update configuration, retrieve cluster-level and node-level information, and execute administrative operations. Accessible locally on port 10000 with Swagger 2.0 spec at /v2.

- Documentation: [https://docs.scylladb.com/stable/operating-scylla/rest.html](https://docs.scylladb.com/stable/operating-scylla/rest.html)

## Plans, Rate Limits, and FinOps

- Plans: [plans/scylladb-plans-pricing.yml](plans/scylladb-plans-pricing.yml)
- Rate Limits: [rate-limits/scylladb-rate-limits.yml](rate-limits/scylladb-rate-limits.yml)
- FinOps: [finops/scylladb-finops.yml](finops/scylladb-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.scylladb.com/](https://www.scylladb.com/) |
| Documentation | [https://docs.scylladb.com/](https://docs.scylladb.com/) |
| Getting Started | [https://developers.scylladb.com/stable/](https://developers.scylladb.com/stable/) |
| GitHub Organization | [https://github.com/scylladb](https://github.com/scylladb) |
| LinkedIn | [https://www.linkedin.com/company/scylladb](https://www.linkedin.com/company/scylladb) |
| X / Twitter | [https://x.com/ScyllaDB](https://x.com/ScyllaDB) |
| Blog | [https://resources.scylladb.com/blog](https://resources.scylladb.com/blog) |
| Pricing | [https://www.scylladb.com/pricing/](https://www.scylladb.com/pricing/) |
| Status Page | [https://status.cloud.scylladb.com/](https://status.cloud.scylladb.com/) |
| Release Notes | [https://www.scylladb.com/product/release-notes/](https://www.scylladb.com/product/release-notes/) |
| Forum | [https://forum.scylladb.com/](https://forum.scylladb.com/) |
| University | [https://university.scylladb.com/](https://university.scylladb.com/) |

## Maintainers

- Kin Lane / [kin@apievangelist.com](mailto:kin@apievangelist.com)
