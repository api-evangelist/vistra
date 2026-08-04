# Vistra (vistra)

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

Vistra is a global corporate services provider operating in over 45 jurisdictions, offering entity management, incorporation, compliance, payroll, and fund administration services. The Vistra REST API enables developers to programmatically submit company incorporation requests in supported jurisdictions (initially British Virgin Islands), upload supporting documents to pre-signed storage URLs, and integrate Vistra's corporate services into business process workflows. Authentication uses OAuth2 bearer tokens obtained through the Vistra Developer Portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Compliance
- Corporate Services
- Entity Management
- Finance
- Fortune 500
- Legal

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Vistra Incorporations API

The Vistra Incorporations API enables programmatic submission of company incorporation requests in supported jurisdictions. Currently available for the British Virgin Islands (BVI) on an invite-only basis, the API supports the full incorporation workflow: generating pre-signed S3 document upload URLs, confirming document upload completion, and submitting incorporation requests with entity details, stakeholder information, shareholding structure, and compliance data. Authentication requires OAuth2 bearer tokens obtained from the Vistra Developer Portal.

- **Human URL:** [https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands](https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands)
- **Base URL:** `https://api.vistra.com`

#### Tags

- BVI
- British Virgin Islands
- Compliance
- Corporate Services
- Entity Management
- Incorporation
- Legal
- OAuth2

#### Properties

- [Documentation](https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands)
- [Developer  Portal](https://devportal.vistra.com/)
- [OpenAPI](openapi/vistra-incorporations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vistra-incorporations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vistra-incorporations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vistra-energy)
- [Website](https://www.vistra.com)
- [Developer  Portal](https://devportal.vistra.com/)
- [Help  Center](https://help.vistra.com/en/)
- [Client  Portals](https://www.vistra.com/client-portals)
- [Entity  Management](https://www.vistra.com/corporate/entity-management)
- [Privacy Policy](https://www.vistra.com/privacy-policy)
- [OpenAPI](openapi/vistra-incorporations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/vistra-incorporation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/vistra-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/vistra-vocabulary.yml)
- [Spectral Rules](rules/vistra-rules.yml)
- [Integrations](https://www.vistra.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
