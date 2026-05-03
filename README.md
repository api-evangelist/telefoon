# Telefoon

Telefoon is a GDPR-compliant cloud telephony and communications platform built for European markets. The platform provides programmable voice, SMS, and number management APIs with EU data residency, multi-language TTS (Dutch, French, German, English), branded sender IDs, and regulatory compliance for Dutch, Belgian, and broader EU telecommunications.

**Human URL:** [https://www.telefoon.com](https://www.telefoon.com)
**Developer URL:** [https://developers.telefoon.com](https://developers.telefoon.com)

## APIs

### Telefoon Voice API
GDPR-compliant EU voice API with multi-language TTS, call conferencing, and recording.
- **OpenAPI Spec:** [openapi/telefoon-voice-openapi.yml](openapi/telefoon-voice-openapi.yml)

### Telefoon SMS API
EU SMS API with alphanumeric sender IDs, GDPR consent tracking, and delivery reports.
- **OpenAPI Spec:** [openapi/telefoon-sms-openapi.yml](openapi/telefoon-sms-openapi.yml)

### Telefoon Number Management API
Dutch, Belgian, German, and EU number provisioning with regulatory compliance support.
- **OpenAPI Spec:** [openapi/telefoon-numbers-openapi.yml](openapi/telefoon-numbers-openapi.yml)

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/telefoon-voice-openapi.yml](openapi/telefoon-voice-openapi.yml) | Voice API — calls and conferencing with EU TTS |
| [openapi/telefoon-sms-openapi.yml](openapi/telefoon-sms-openapi.yml) | SMS API — branded sender IDs and GDPR consent tracking |
| [openapi/telefoon-numbers-openapi.yml](openapi/telefoon-numbers-openapi.yml) | Number Management API — EU numbers with regulatory compliance |

### JSON Schemas
| File | Description |
|---|---|
| [json-schema/telefoon-call-schema.json](json-schema/telefoon-call-schema.json) | Call object JSON Schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/telefoon-call-structure.json](json-structure/telefoon-call-structure.json) | Call object field structure |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/telefoon-context.jsonld](json-ld/telefoon-context.jsonld) | JSON-LD context including GDPR semantic mappings |

### Examples
| File | Description |
|---|---|
| [examples/telefoon-initiate-call-example.json](examples/telefoon-initiate-call-example.json) | Initiate a Dutch-language call |
| [examples/telefoon-send-sms-example.json](examples/telefoon-send-sms-example.json) | Send a branded SMS (Dutch) with GDPR reference |

### Spectral Rules
| File | Description |
|---|---|
| [rules/telefoon-rules.yml](rules/telefoon-rules.yml) | Spectral ruleset for Telefoon API conventions |

### Naftiko Capabilities
| File | Description |
|---|---|
| [capabilities/shared/telefoon-voice.yaml](capabilities/shared/telefoon-voice.yaml) | Shared EU Voice API capability |
| [capabilities/shared/telefoon-sms.yaml](capabilities/shared/telefoon-sms.yaml) | Shared EU SMS API capability |
| [capabilities/eu-communications.yaml](capabilities/eu-communications.yaml) | EU communications workflow (REST port 8080, MCP port 9090) |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/telefoon-vocabulary.yml](vocabulary/telefoon-vocabulary.yml) | Telefoon vocabulary including GDPR, EU number types, and EU telecom terms |

## Common Properties

| Property | URL |
|---|---|
| Authentication | https://developers.telefoon.com/authentication |
| GDPR | https://www.telefoon.com/gdpr |
| Rate Limits | https://developers.telefoon.com/rate-limits |
| Status | https://status.telefoon.com |
| Terms of Service | https://www.telefoon.com/terms |
| Privacy Policy | https://www.telefoon.com/privacy |

## Maintainers
- **Telefoon API Team** — api-team@telefoon.com
