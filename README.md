# Microsoft Dynamics 365 Business Central (microsoft-dynamics-365-business-central)

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

Microsoft Dynamics 365 Business Central is an all-in-one cloud ERP solution for small and mid-sized businesses that brings together finance, sales, service, project management, supply chain, manufacturing, and operations on the Microsoft Cloud. Business Central exposes a standard REST API (v2.0) plus custom and OData web services so partners can build Connect apps, automate processes, and integrate Business Central with Power Platform and third-party systems using OAuth 2.0 authentication via Microsoft Entra ID.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365-business-central/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365-business-central/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- ERP
- Cloud ERP
- Finance
- Accounting
- Supply Chain
- Operations
- Small Business
- Mid-Market
- Microsoft Dynamics 365

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Business Central API (v2.0)

Standard REST API (v2.0) for Dynamics 365 Business Central exposing entities such as customers, vendors, items, sales and purchase documents, and journals. Authenticates with OAuth 2.0 via Microsoft Entra ID and supports both delegated user and service-to-service flows.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- **Base URL:** `https://api.businesscentral.dynamics.com/v2.0/{environment}/api/v2.0`

#### Tags

- REST
- OAuth 2.0
- Entra ID
- Connect Apps
- Standard Entities

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/)
- [OpenAPI](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-open-api) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication)
- [Postman Collection](collections/microsoft-dynamics-365-business-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-365-business-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central OData Web Services

OData v4 endpoints exposing published Business Central pages and queries as web services for custom integrations, reporting, and Power Platform connectors when standard API v2.0 entities are insufficient.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/odata-web-services](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/odata-web-services)
- **Base URL:** `https://api.businesscentral.dynamics.com/v2.0/{tenant}/{environment}/ODataV4`

#### Tags

- OData
- Web Services
- Pages
- Queries

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/odata-web-services)
- [Postman Collection](collections/microsoft-dynamics-365-business-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-365-business-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Business Central Administration Center API

Administration Center REST API for managing Business Central environments, tenants, telemetry, update settings, and notifications programmatically for ISVs and delegated administrators.

- **Human URL:** [https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)
- **Base URL:** `https://api.businesscentral.dynamics.com/admin/v2.x`

#### Tags

- Administration
- Tenant Management
- Environments

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api)
- [Postman Collection](collections/microsoft-dynamics-365-business-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-dynamics-365-business-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/microsoft)
- [Website](https://www.microsoft.com/en-us/dynamics-365/products/business-central)
- [Documentation](https://learn.microsoft.com/en-us/dynamics365/business-central/)
- [Pricing](https://www.microsoft.com/en-us/dynamics-365/products/business-central/pricing)
- [Sign Up](https://signup.microsoft.com/get-started/signup?products=22b1949b-c5dd-4b06-9c19-1d2fa17e7a9d)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
