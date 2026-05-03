# Vistra (vistra)

Vistra is a global corporate services provider operating in over 45 jurisdictions, offering entity management, incorporation, compliance, payroll, and fund administration services. The Vistra REST API enables developers to programmatically submit company incorporation requests in supported jurisdictions (initially British Virgin Islands), upload supporting documents to pre-signed storage URLs, and integrate Vistra's corporate services into business process workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vistra/refs/heads/main/apis.yml)

## Tags

- Compliance
- Corporate Services
- Entity Management
- Finance
- Fortune 500
- Legal

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-03

## APIs

### Vistra Incorporations API

Programmatic submission of company incorporation requests in supported jurisdictions. Currently available for the British Virgin Islands (BVI) on an invite-only basis.

**Human URL:** [https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands](https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands)
**Base URL:** https://api.vistra.com

#### Properties

- [Documentation](https://help.vistra.com/en/articles/10351085-vistra-incorporations-api-british-virgin-islands)
- [Developer Portal](https://devportal.vistra.com/)
- [OpenAPI](openapi/vistra-incorporations-openapi.yml)

## Common Properties

- [Website](https://www.vistra.com)
- [Developer Portal](https://devportal.vistra.com/)
- [Help Center](https://help.vistra.com/en/)
- [Client Portals](https://www.vistra.com/client-portals)
- [Entity Management](https://www.vistra.com/corporate/entity-management)
- [Privacy Policy](https://www.vistra.com/privacy-policy)

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [openapi/vistra-incorporations-openapi.yml](openapi/vistra-incorporations-openapi.yml) |
| JSON Schema | [json-schema/vistra-incorporation-schema.json](json-schema/vistra-incorporation-schema.json) |
| JSON Structure | [json-structure/vistra-incorporation-structure.json](json-structure/vistra-incorporation-structure.json) |
| JSON-LD | [json-ld/vistra-context.jsonld](json-ld/vistra-context.jsonld) |
| Spectral Rules | [rules/vistra-rules.yml](rules/vistra-rules.yml) |
| Vocabulary | [vocabulary/vistra-vocabulary.yml](vocabulary/vistra-vocabulary.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Vistra Incorporations API | [capabilities/shared/vistra-incorporations.yaml](capabilities/shared/vistra-incorporations.yaml) |

### Workflow Capabilities

| Workflow | File | Description |
|----------|------|-------------|
| Entity Formation | [capabilities/entity-formation.yaml](capabilities/entity-formation.yaml) | Complete BVI company incorporation workflow with document upload and submission |

## Examples

- [Generate Document Upload URL](examples/vistra-incorporations-generateDocumentUploadUrl-example.json)
- [Create Incorporation](examples/vistra-incorporations-createIncorporation-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
