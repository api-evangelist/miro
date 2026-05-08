# Miro (miro)

Miro is an online collaborative whiteboard used by distributed teams for brainstorming, diagramming, and workshops. The Miro REST API exposes boards, board items (sticky notes, cards, shapes, frames, images, embeds, etc.), connectors, tags, mind maps, members, organizations, teams, webhooks, audit logs, and SCIM provisioning. Miro also offers a Web SDK for in-board apps.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/miro/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=miro-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - Productivity, Whiteboard, Visual Collaboration, Diagramming, SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Miro Boards API | Create, read, update, copy, and delete Miro boards. |
| Miro Board Items API | CRUD on sticky notes, cards, shapes, text, frames, images, documents, embeds, app cards. |
| Miro Connectors API | Lines/arrows between board items for diagramming. |
| Miro Tags API | Create, attach, remove tags on items. |
| Miro Mind Map API | Mind-map nodes and parent-child links. |
| Miro Board Members API | Manage board access and roles. |
| Miro Webhooks API | Event subscriptions (item and board events). |
| Miro Organization API | Enterprise-only org-level management. |
| Miro Teams API | Enterprise team management. |
| Miro Audit Logs API | Enterprise audit log queries. |
| Miro SCIM API | SCIM 2.0 provisioning for Enterprise. |
| Miro Web SDK | Build apps that run inside the Miro board UI. |

## Common Properties

- [Website](https://miro.com/)
- [Developer Portal](https://developers.miro.com/)
- [Pricing](https://miro.com/pricing/)
- [GitHub](https://github.com/miroapp)
- [Plans](plans/miro-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/miro-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/miro-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/miro-plans-pricing.yml` | Free / Starter $8-10/mbr / Business $20-25/mbr / Enterprise (30+ min) |
| Rate Limits | `rate-limits/miro-rate-limits.yml` | Per-OAuth-app; raised by Miro Marketplace verification/certification |
| FinOps | `finops/miro-finops.yml` | Per-Member subscription + AI credit metering |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
