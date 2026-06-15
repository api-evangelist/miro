# Miro (miro)

Miro is an online collaborative whiteboard used by distributed teams for brainstorming, diagramming, and workshops. The Miro REST API exposes boards, board items (sticky notes, cards, shapes, frames, images, embeds, etc.), connectors, tags, mind maps, members, organizations, teams, webhooks, audit logs, and SCIM provisioning. Miro also offers a Web SDK for in-board apps.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/miro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/miro/refs/heads/main/apis.yml)

## Tags

- Productivity
- Whiteboard
- Visual Collaboration
- Diagramming
- SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Miro Boards API

Create, read, update, copy, and delete Miro boards. Boards are the top-level container for whiteboard content within a team or workspace.

- **Human URL:** [https://developers.miro.com/reference/boards](https://developers.miro.com/reference/boards)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Boards
- CRUD

#### Properties

- [API Reference](https://developers.miro.com/reference/boards)
- [Documentation](https://developers.miro.com/reference/overview)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Board Items API

Generic and per-type endpoints for board items: sticky notes, cards, shapes, text, frames, images, documents, embeds, and app cards. CRUD on items, with type-specific create/update endpoints for each item kind.

- **Human URL:** [https://developers.miro.com/reference/items](https://developers.miro.com/reference/items)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Items
- Sticky Notes
- Shapes

#### Properties

- [API Reference](https://developers.miro.com/reference/items)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Connectors API

Create and manage connectors (lines/arrows) between board items, including style and shape options for diagramming workflows.

- **Human URL:** [https://developers.miro.com/reference/connectors](https://developers.miro.com/reference/connectors)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Connectors
- Diagramming

#### Properties

- [API Reference](https://developers.miro.com/reference/connectors)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Tags API

Create, attach, and remove tags on board items for searching, filtering, and grouping.

- **Human URL:** [https://developers.miro.com/reference/tags](https://developers.miro.com/reference/tags)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Tags
- Metadata

#### Properties

- [API Reference](https://developers.miro.com/reference/tags)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Mind Map API

Create and manage mind-map nodes and parent-child relationships on a board.

- **Human URL:** [https://developers.miro.com/reference/mindmap-nodes](https://developers.miro.com/reference/mindmap-nodes)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Mind Map
- Diagramming

#### Properties

- [API Reference](https://developers.miro.com/reference/mindmap-nodes)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Board Members API

Manage who has access to a board and what role (owner, editor, commenter, viewer) they hold.

- **Human URL:** [https://developers.miro.com/reference/board-members](https://developers.miro.com/reference/board-members)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Members
- Sharing
- Permissions

#### Properties

- [API Reference](https://developers.miro.com/reference/board-members)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Webhooks API

Subscribe to board events (item created/updated/deleted, board events) and receive HTTP callbacks at your endpoint.

- **Human URL:** [https://developers.miro.com/reference/webhooks](https://developers.miro.com/reference/webhooks)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Webhooks
- Events

#### Properties

- [API Reference](https://developers.miro.com/reference/webhooks)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Organization API

Enterprise-only endpoints to manage the organization, list members, and inspect organization-wide membership and licensing.

- **Human URL:** [https://developers.miro.com/reference/enterprise-organization](https://developers.miro.com/reference/enterprise-organization)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Organization
- Enterprise

#### Properties

- [API Reference](https://developers.miro.com/reference/enterprise-organization)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Teams API

Manage teams, team members, team settings, and default team roles within an organization.

- **Human URL:** [https://developers.miro.com/reference/enterprise-teams](https://developers.miro.com/reference/enterprise-teams)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Teams
- Membership

#### Properties

- [API Reference](https://developers.miro.com/reference/enterprise-teams)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Audit Logs API

Enterprise audit-log endpoints. Query user, board, and admin actions for compliance and security monitoring.

- **Human URL:** [https://developers.miro.com/reference/audit-logs](https://developers.miro.com/reference/audit-logs)
- **Base URL:** `https://api.miro.com/v2`

#### Tags

- Audit
- Compliance
- Enterprise

#### Properties

- [API Reference](https://developers.miro.com/reference/audit-logs)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro SCIM API

SCIM 2.0 provisioning for Enterprise customers. Automate user/group lifecycle from Okta, Azure AD, OneLogin, and other IdPs.

- **Human URL:** [https://developers.miro.com/reference/scim-api](https://developers.miro.com/reference/scim-api)
- **Base URL:** `https://miro.com/api/v1/scim`

#### Tags

- SCIM
- Identity
- Provisioning

#### Properties

- [API Reference](https://developers.miro.com/reference/scim-api)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Miro Web SDK

Build apps that run inside the Miro board UI. The Web SDK lets your app create and modify board items, react to events, render custom panels, and integrate with the user's workspace.

- **Human URL:** [https://developers.miro.com/docs/build-your-first-hello-world-app](https://developers.miro.com/docs/build-your-first-hello-world-app)
- **Base URL:** `https://miro.com`

#### Tags

- SDK
- Browser
- Apps

#### Properties

- [Documentation](https://developers.miro.com/docs/build-your-first-hello-world-app)
- [Git Hub](https://github.com/miroapp)
- [OpenAPI](openapi/miro-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/miro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/miro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mirohq)
- [Website](https://miro.com/)
- [Developer Portal](https://developers.miro.com/)
- [Pricing](https://miro.com/pricing/)
- [Git Hub](https://github.com/miroapp)
- [Plans](plans/miro-plans-pricing.yml)
- [Rate Limits](rate-limits/miro-rate-limits.yml)
- [Fin Ops](finops/miro-finops.yml)
- [Integrations](https://miro.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
