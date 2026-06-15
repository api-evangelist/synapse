# Synapse (synapse)

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
