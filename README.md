# ScyllaDB (scylladb)

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
