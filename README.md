# All Quiet (allquiet)

All Quiet is a lean, SRE-first incident management and on-call alerting platform for engineering teams. Its Public REST API (US and EU regions, API-key authenticated) lets teams programmatically create and manage incidents, configure inbound and outbound integrations, manage teams and escalation schedules, and read who is on call.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/allquiet/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/allquiet/refs/heads/main/apis.yml)

## Tags

- Incident Management
- On-Call
- Alerting
- Incident Response
- DevOps

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### All Quiet Incidents API

Create, retrieve, search, update (PATCH), and delete incidents, including severity, status, team assignment, user assignments, and attributes. A Markdown rendering of any incident is also available.

- **Human URL:** [https://docs.allquiet.app/advanced/api](https://docs.allquiet.app/advanced/api)
- **Base URL:** `https://allquiet.app/api/public/v1`

#### Tags

- Incidents
- Incident Response
- Alerting

#### Properties

- [Documentation](https://docs.allquiet.app/essentials/incident)
- [API Reference](https://allquiet.app/api/public/swagger-ui/index.html)
- [OpenAPI](openapi/allquiet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/allquiet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/allquiet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### All Quiet Inbound Integrations API

Manage inbound integrations that turn observability and alerting signals into All Quiet incidents, including the generic inbound webhook endpoint, payload attribute mapping, integration types, and maintenance windows.

- **Human URL:** [https://docs.allquiet.app/essentials/inbound](https://docs.allquiet.app/essentials/inbound)
- **Base URL:** `https://allquiet.app/api/public/v1`

#### Tags

- Inbound Integrations
- Webhooks
- Alerting

#### Properties

- [Documentation](https://docs.allquiet.app/integrations/inbound/webhook)
- [API Reference](https://allquiet.app/api/public/swagger-ui/index.html)
- [OpenAPI](openapi/allquiet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/allquiet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/allquiet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### All Quiet Teams API

Create, read, update, and delete teams, team memberships, and organization memberships (users), the building blocks for routing incidents and on-call duty.

- **Human URL:** [https://docs.allquiet.app/essentials/teams](https://docs.allquiet.app/essentials/teams)
- **Base URL:** `https://allquiet.app/api/public/v1`

#### Tags

- Teams
- Membership
- Organization

#### Properties

- [Documentation](https://docs.allquiet.app/essentials/teams)
- [API Reference](https://allquiet.app/api/public/swagger-ui/index.html)
- [OpenAPI](openapi/allquiet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/allquiet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/allquiet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### All Quiet On-Call Schedules API

Read who is on call across teams and users at a point in time, configure team escalation tiers and rotations, and create on-call overrides for coverage swaps.

- **Human URL:** [https://docs.allquiet.app/essentials/escalations](https://docs.allquiet.app/essentials/escalations)
- **Base URL:** `https://allquiet.app/api/public/v1`

#### Tags

- On-Call
- Schedules
- Escalations

#### Properties

- [Documentation](https://docs.allquiet.app/essentials/escalations)
- [API Reference](https://allquiet.app/api/public/swagger-ui/index.html)
- [OpenAPI](openapi/allquiet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/allquiet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/allquiet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### All Quiet Webhooks API

Manage outbound integrations that forward All Quiet incidents to third-party platforms, including a generic outbound webhook that POSTs incident events to any HTTP endpoint, plus Slack and Mattermost delivery.

- **Human URL:** [https://docs.allquiet.app/integrations/outbound/webhook](https://docs.allquiet.app/integrations/outbound/webhook)
- **Base URL:** `https://allquiet.app/api/public/v1`

#### Tags

- Webhooks
- Outbound Integrations
- Notifications

#### Properties

- [Documentation](https://docs.allquiet.app/essentials/outbound)
- [API Reference](https://allquiet.app/api/public/swagger-ui/index.html)
- [OpenAPI](openapi/allquiet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/allquiet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/allquiet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/AllQuietApp)
- [LinkedIn](https://www.linkedin.com/company/allquiet)
- [Website](https://allquiet.app/)
- [Documentation](https://docs.allquiet.app)
- [Plans](plans/allquiet-plans-pricing.yml)
- [Rate Limits](rate-limits/allquiet-rate-limits.yml)
- [Fin Ops](finops/allquiet-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
