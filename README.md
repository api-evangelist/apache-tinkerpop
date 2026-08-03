# Apache TinkerPop (apache-tinkerpop)

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

Apache TinkerPop is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP). It provides the Gremlin graph traversal language working with Amazon Neptune, Azure Cosmos DB, JanusGraph, Neo4j, and 20+ other graph systems.

**URL:** [https://tinkerpop.apache.org/](https://tinkerpop.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Graph Computing, Graph Database, Gremlin, OLAP, OLTP, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache TinkerPop Gremlin Server API
WebSocket and HTTP endpoints for submitting Gremlin traversals to a remote graph database with GraphBinary and GraphSON serialization.

**Human URL:** [https://tinkerpop.apache.org/docs/current/reference/#gremlin-server](https://tinkerpop.apache.org/docs/current/reference/#gremlin-server)

#### Tags:

 - WebSocket, HTTP, Gremlin, Graph Database

#### Properties

- [Documentation](https://tinkerpop.apache.org/docs/current/reference/#gremlin-server)

### Apache TinkerPop Gremlin Traversal API
The Gremlin functional graph traversal language for expressing complex graph queries and mutations with multi-language SDKs for Java, Python, JavaScript, Go, and .NET.

**Human URL:** [https://tinkerpop.apache.org/docs/current/reference/](https://tinkerpop.apache.org/docs/current/reference/)

#### Tags:

 - Gremlin, Graph Traversal, Graph Database, Java, Python

#### Properties

- [Documentation](https://tinkerpop.apache.org/docs/current/reference/)
- [Python Gremlin SDK](https://pypi.org/project/gremlinpython/)
- [Java Maven SDK](https://search.maven.org/search?q=org.apache.tinkerpop)
- [JavaScript/Node.js SDK](https://www.npmjs.com/package/gremlin)

## Common Properties

- [GitHubRepository](https://github.com/apache/tinkerpop)
- [Documentation](https://tinkerpop.apache.org/docs/current/reference/)
- [Portal](https://tinkerpop.apache.org/)
- [GettingStarted](https://tinkerpop.apache.org/docs/current/tutorials/getting-started/)
- [ReleaseNotes](https://github.com/apache/tinkerpop/releases)
- [Support](https://groups.google.com/g/gremlin-users)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Graph Database Abstraction | Single API working across Neo4j, JanusGraph, Amazon Neptune, Azure Cosmos DB, and 20+ graph systems. |
| Gremlin Language | Expressive functional graph traversal language for both queries and mutations. |
| OLAP Graph Processing | Bulk/analytical graph processing via SparkGraphComputer for large-scale graph algorithms. |
| GraphBinary Serialization | Compact binary serialization format for efficient Gremlin traversal encoding. |
| Gremlin Server | Standalone server hosting Gremlin traversal execution over WebSocket or HTTP. |
| Multi-Language SDKs | Official Gremlin SDKs for Java, Python, JavaScript, Go, and .NET. |

## Use Cases

| Name | Description |
|------|-------------|
| Knowledge Graphs | Build and query knowledge graphs for entity relationship modeling. |
| Social Network Analysis | Traverse and analyze social graph relationships and influence patterns. |
| Fraud Detection | Detect fraud rings and suspicious patterns via graph relationship traversal. |
| Recommendation Engines | Graph-based collaborative filtering and content recommendation. |
| Identity and Access Management | Model and query complex permission hierarchies and role relationships. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon Neptune | AWS managed graph database with full TinkerPop and Gremlin compatibility. |
| Azure Cosmos DB | Azure Cosmos DB Gremlin API for TinkerPop-compatible graph storage. |
| JanusGraph | Distributed graph database with TinkerPop/Gremlin interface. |
| Neo4j | Neo4j TinkerPop plugin for Gremlin traversal on Neo4j graph data. |
| Apache Spark | SparkGraphComputer for OLAP graph analytics on Spark clusters. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
