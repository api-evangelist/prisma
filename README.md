# Prisma (prisma)

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

Prisma is a next-generation ORM that helps developers build applications faster and with fewer errors. It provides a type-safe database client, migrations system, and visual database browser.

**APIs.json:** [https://www.prisma.io](https://www.prisma.io)

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Prisma Data Platform API

REST API for managing Prisma Data Platform resources including projects, environments, and database connections through the Prisma Console.

#### Tags

- Database
- Developer Tools
- ORM
- Platform

#### Properties

- [Documentation](https://www.prisma.io/docs/platform/about)
- [OpenAPI](https://api.cloud.prisma.io/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/prisma-data-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-data-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-data-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.prisma.io/docs/management-api/authentication)
- [Getting Started](https://www.prisma.io/docs/console/getting-started)

### Prisma Accelerate API

API for Prisma Accelerate, a fully managed global connection pool and caching layer for existing databases with query-level cache policies directly from the Prisma ORM.

#### Tags

- Caching
- Connection Pooling
- Database
- Performance
- Serverless

#### Properties

- [Documentation](https://www.prisma.io/docs/accelerate)
- [OpenAPI](openapi/prisma-accelerate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-accelerate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-accelerate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://www.prisma.io/docs/accelerate/getting-started)
- [Reference](https://www.prisma.io/docs/accelerate/reference/api-reference)
- [F A Q](https://www.prisma.io/docs/accelerate/more/faq)

### Prisma Pulse API

API for Prisma Pulse, a managed Change Data Capture service enabling real-time database change events and type-safe subscriptions via Prisma Client.

#### Tags

- Change Data Capture
- Database
- Events
- Real-Time
- Subscriptions

#### Properties

- [Documentation](https://www.prisma.io/docs/pulse/database-events)
- [OpenAPI](openapi/prisma-pulse-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-pulse.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-pulse.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://www.prisma.io/docs/pulse/getting-started)
- [F A Q](https://www.prisma.io/docs/pulse/faq)

### Prisma Postgres Management API

REST API for programmatically provisioning and managing Prisma Postgres databases, projects, and workspaces, supporting automation, CI/CD workflows, and partner integrations.

#### Tags

- Database
- Infrastructure
- Managed Database
- PostgreSQL
- Provisioning

#### Properties

- [Documentation](https://www.prisma.io/docs/postgres/introduction/management-api)
- [OpenAPI](openapi/prisma-postgres-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-postgres-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-postgres-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://www.prisma.io/docs/guides/management-api-basic)
- [Authentication](https://www.prisma.io/docs/management-api/authentication)
- [S D Ks](https://www.prisma.io/docs/management-api/sdk)

### Prisma Client API

Auto-generated, type-safe query builder for Node.js and TypeScript that provides programmatic database access for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB, and CockroachDB.

#### Tags

- Database
- Node.js
- ORM
- Query Builder
- TypeScript

#### Properties

- [Documentation](https://www.prisma.io/docs/orm)
- [OpenAPI](openapi/prisma-client-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-client.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-client.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://www.prisma.io/docs/orm/reference/prisma-client-reference)
- [Getting Started](https://www.prisma.io/docs/getting-started/prisma-orm/quickstart/prisma-postgres)
- [S D Ks](https://www.npmjs.com/package/@prisma/client)

### Prisma Optimize API

Query performance tool for analyzing, debugging, and improving database queries during development, with AI-powered recommendations to reduce database load and improve responsiveness.

#### Tags

- AI
- Database
- Developer Tools
- Performance
- Query Optimization

#### Properties

- [Documentation](https://www.prisma.io/docs/optimize)
- [OpenAPI](openapi/prisma-optimize-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prisma-optimize.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prisma-optimize.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://www.prisma.io/docs/optimize/getting-started)
- [S D Ks](https://www.npmjs.com/package/@prisma/extension-optimize)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/prisma-io)
- [Portal](https://console.prisma.io/login)
- [Documentation](https://www.prisma.io/docs)
- [Getting Started](https://www.prisma.io/docs/getting-started)
- [Authentication](https://www.prisma.io/docs/management-api/authentication)
- [Blog](https://www.prisma.io/blog)
- [Changelog](https://www.prisma.io/changelog)
- [GitHub Organization](https://github.com/prisma)
- [Community](https://www.prisma.io/community)
- [Discord](https://pris.ly/discord)
- [Twitter](https://twitter.com/prisma)
- [Pricing](https://www.prisma.io/pricing)
- [Status Page](https://www.prisma-status.com)
- [Support](https://www.prisma.io/support)
- [Terms of Service](https://www.prisma.io/terms)
- [Privacy Policy](https://www.prisma.io/privacy)
- [Website](https://www.prisma.io)
- [Login](https://console.prisma.io/login)
- [Sign Up](https://console.prisma.io/sign-up)
- [J S O N- L D  Context](json-ld/prisma-context.jsonld)
- [J S O N  Schema](json-schema/prisma-workspace-schema.json)
- [J S O N  Schema](json-schema/prisma-project-schema.json)
- [J S O N  Schema](json-schema/prisma-database-schema.json)
- [J S O N  Schema](json-schema/prisma-cache-strategy-schema.json)
- [J S O N  Schema](json-schema/prisma-pulse-event-schema.json)
- [J S O N  Schema](json-schema/prisma-query-recommendation-schema.json)
- [Integrations](https://www.prisma.io/partners)
- [M C P Server](https://github.com/prisma/mcp)
- [Agent Skill](https://github.com/prisma/skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://www.prisma.io
