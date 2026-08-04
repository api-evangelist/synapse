# Synapse (synapse)

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

Synapse is the reference Matrix homeserver implementation maintained by Element (formerly by the Matrix.org Foundation). Written in Python and Rust, it implements the Matrix open standard for secure, decentralized real-time communication. Synapse powers thousands of deployments worldwide and provides Client-Server, Server-Server (federation), Application Service, Identity Service, and Admin APIs. Since version 1.99, maintained by Element under AGPL-3.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/synapse/refs/heads/main/apis.yml)

## Tags

- Chat
- Collaboration
- Decentralized
- Federation
- Matrix
- Messaging
- Open-Source
- Real-Time

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Synapse Client-Server API

RESTful API for Matrix client applications to interact with the homeserver, enabling real-time messaging, room management, user authentication, event synchronization, and media uploads. Follows the Matrix Client-Server specification.

- **Human URL:** [https://spec.matrix.org/latest/client-server-api/](https://spec.matrix.org/latest/client-server-api/)
- **Base URL:** `https://matrix.example.com/_matrix/client`

#### Tags

- Chat
- Client
- Collaboration
- Matrix
- Messaging
- Real-Time
- Rooms

#### Properties

- [Documentation](https://spec.matrix.org/latest/client-server-api/)
- [OpenAPI](https://github.com/matrix-org/matrix-spec/tree/main/data/api/client-server) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synapse-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synapse-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synapse Server-Server API

Federation API enabling different Matrix homeservers to communicate with each other, supporting decentralized messaging, event exchange, and room state synchronization across server boundaries.

- **Human URL:** [https://spec.matrix.org/latest/server-server-api/](https://spec.matrix.org/latest/server-server-api/)
- **Base URL:** `https://matrix.example.com/_matrix/federation`

#### Tags

- Decentralized
- Federation
- Matrix
- Server-To-Server

#### Properties

- [Documentation](https://spec.matrix.org/latest/server-server-api/)
- [OpenAPI](https://github.com/matrix-org/matrix-spec/tree/main/data/api/server-server) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synapse-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synapse-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Synapse Admin API

Administrative REST API for managing the Synapse homeserver. Provides server administrators with endpoints for user management, room administration, media management, federation control, registration tokens, background updates, event reports, and server statistics.

- **Human URL:** [https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/](https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/)
- **Base URL:** `https://matrix.example.com/_synapse/admin`

#### Tags

- Administration
- Management
- Matrix
- Monitoring
- Users

#### Properties

- [Documentation](https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/)
- [OpenAPI](openapi/synapse-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/synapse-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synapse-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Git Hub](https://github.com/matrix-org/synapse/tree/develop/docs/admin_api)

### Synapse Application Service API

API for integrating application services (bridges and bots) with the Matrix homeserver. Allows third-party applications to handle namespaced user IDs and room aliases, enabling Matrix bridges for IRC, Slack, Telegram, and other platforms.

- **Human URL:** [https://spec.matrix.org/latest/application-service-api/](https://spec.matrix.org/latest/application-service-api/)
- **Base URL:** `https://matrix.example.com/_matrix/app`

#### Tags

- Application-Services
- Bots
- Bridges
- Integration
- Matrix

#### Properties

- [Documentation](https://spec.matrix.org/latest/application-service-api/)
- [Postman Collection](collections/synapse-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/synapse-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/synapsepay)
- [Git Hub](https://github.com/matrix-org/synapse)
- [Git Hub](https://github.com/element-hq/synapse)
- [Documentation](https://matrix-org.github.io/synapse/latest/)
- [Getting Started](https://matrix-org.github.io/synapse/latest/setup/installation.html)
- [Authentication](https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#authentication)
- [Rate Limits](https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html#ratelimiting)
- [Changelog](https://github.com/matrix-org/synapse/blob/develop/CHANGES.md)
- [License](https://github.com/matrix-org/synapse/blob/develop/LICENSE)
- [Docker](https://hub.docker.com/r/matrixdotorg/synapse)
- [Py P I](https://pypi.org/project/matrix-synapse/)
- [Matrix  Spec](https://spec.matrix.org/latest/)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
