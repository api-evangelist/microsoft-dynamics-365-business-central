# Microsoft Dynamics 365 Business Central (microsoft-dynamics-365-business-central)

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
