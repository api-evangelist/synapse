# Synapse

Synapse is the reference Matrix homeserver implementation, written in Python and Rust. It powers decentralized, end-to-end encrypted real-time communication through the open Matrix standard. Originally developed by the Matrix.org Foundation, maintained by Element since version 1.99 under AGPL-3.0.

## APIs

| API | Description |
|---|---|
| [Synapse Client-Server API](https://spec.matrix.org/latest/client-server-api/) | RESTful API for Matrix clients: messaging, rooms, auth, sync |
| [Synapse Server-Server API](https://spec.matrix.org/latest/server-server-api/) | Federation API for homeserver-to-homeserver communication |
| [Synapse Admin API](https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/) | Administrative API for users, rooms, media, federation, stats |
| [Synapse Application Service API](https://spec.matrix.org/latest/application-service-api/) | Bridge and bot integration with the homeserver |

## OpenAPI Specifications

| Spec | File |
|---|---|
| Synapse Admin API | [openapi/synapse-admin-api-openapi.yml](openapi/synapse-admin-api-openapi.yml) |

## Capabilities

### Shared Per-API Definitions

| Capability | Description |
|---|---|
| [Admin API](capabilities/shared/admin-api.yaml) | User management, rooms, registration tokens, server info |

### Workflow Capabilities

| Workflow | APIs | Description |
|---|---|---|
| [Homeserver Administration](capabilities/homeserver-administration.yaml) | Admin API | Full homeserver admin: users, rooms, tokens, federation, monitoring |

## Artifacts

| Type | Resource |
|---|---|
| Spectral Rules | [rules/synapse-rules.yml](rules/synapse-rules.yml) |
| JSON Schema - User | [json-schema/synapse-user-schema.json](json-schema/synapse-user-schema.json) |
| JSON Structure - Room | [json-structure/synapse-room-structure.json](json-structure/synapse-room-structure.json) |
| JSON-LD Context | [json-ld/synapse-context.jsonld](json-ld/synapse-context.jsonld) |
| Example - List Users | [examples/synapse-list-users-example.json](examples/synapse-list-users-example.json) |
| Vocabulary | [vocabulary/synapse-vocabulary.yml](vocabulary/synapse-vocabulary.yml) |

## Links

- **GitHub (Matrix.org)**: https://github.com/matrix-org/synapse
- **GitHub (Element)**: https://github.com/element-hq/synapse
- **Documentation**: https://matrix-org.github.io/synapse/latest/
- **Admin API Docs**: https://matrix-org.github.io/synapse/latest/usage/administration/admin_api/
- **Matrix Spec**: https://spec.matrix.org/latest/
- **Getting Started**: https://matrix-org.github.io/synapse/latest/setup/installation.html
- **Docker**: https://hub.docker.com/r/matrixdotorg/synapse
- **PyPI**: https://pypi.org/project/matrix-synapse/
- **Changelog**: https://github.com/matrix-org/synapse/blob/develop/CHANGES.md

## Maintainers

**API Evangelist** | info@apievangelist.com
