# All Quiet (allquiet)

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
