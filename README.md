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
