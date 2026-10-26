# Miro (miro)

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
