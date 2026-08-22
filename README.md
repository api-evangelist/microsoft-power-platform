# Microsoft Power Platform (microsoft-power-platform)

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

Microsoft Power Platform is a suite of low-code development tools including Power Apps, Power Automate, Power BI, and Power Virtual Agents. It provides APIs for accessing Dataverse, managing environments, and integrating with external services through connectors.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-power-platform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-power-platform/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Dataverse
- Low-Code
- Microsoft
- Power Apps
- Power Automate
- Power BI

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Microsoft Dataverse Web API

The Microsoft Dataverse Web API provides OData v4 RESTful access to the Dataverse data platform that underpins Power Platform. Developers can perform CRUD operations on tables, execute actions and functions, manage metadata, and query data using standard OData conventions.

- **Human URL:** [https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- **Base URL:** `https://{org}.api.crm.dynamics.com/api/data/v9.2/`

#### Tags

- Data Platform
- Dataverse
- OData

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview)
- [Postman Collection](collections/microsoft-power-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Platform Admin API

The Power Platform Admin API enables programmatic management of Power Platform environments, connectors, data loss prevention policies, and tenant settings. Administrators can create and manage environments, configure security roles, and enforce governance policies across the organization.

- **Human URL:** [https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview](https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview)
- **Base URL:** `https://api.bap.microsoft.com/`

#### Tags

- Administration
- Environments
- Governance

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview)
- [Postman Collection](collections/microsoft-power-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Platform Connectors

Power Platform Connectors provide pre-built integrations with hundreds of external services and enable developers to create custom connectors using OpenAPI definitions. Connectors abstract API authentication and data access, making external services available to Power Apps, Power Automate, and Logic Apps.

- **Human URL:** [https://learn.microsoft.com/en-us/connectors/overview](https://learn.microsoft.com/en-us/connectors/overview)

#### Tags

- Connectors
- Custom Connectors
- Integration

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/connectors/overview)
- [Getting Started](https://learn.microsoft.com/en-us/connectors/custom-connectors/)
- [Postman Collection](collections/microsoft-power-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-power-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/microsoft)
- [LinkedIn](https://www.linkedin.com/showcase/microsoft-power-platform)
- [Portal](https://make.powerapps.com/)
- [Documentation](https://learn.microsoft.com/en-us/power-platform/)
- [Pricing](https://powerapps.microsoft.com/en-us/pricing/)
- [Authentication](https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2)
- [Blog](https://powerplatform.microsoft.com/en-us/blog/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Status Page](https://status.powerplatform.microsoft.com/)
- [Features](https://powerplatform.microsoft.com/en-us/what-is-power-platform/)
- [Use Cases](https://powerplatform.microsoft.com/en-us/customer-stories/)
- [Integrations](https://learn.microsoft.com/en-us/connectors/overview)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
