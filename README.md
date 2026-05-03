# Towers Watson (WTW)

Towers Watson was a global professional services company that provided risk management, actuarial, human capital, and investment consulting services before merging with Willis Group to form Willis Towers Watson (now WTW) in 2016. WTW provides data-driven, insight-led solutions in risk, broking, HR consulting, and benefits administration across 140+ countries. WTW's software products include the HR Portal for employee benefits communication, benefits administration systems, compensation management tools, and actuarial modeling platforms.

**Website:** [https://www.wtwco.com/](https://www.wtwco.com/)
**Products:** [https://www.wtwco.com/en-us/solutions/products](https://www.wtwco.com/en-us/solutions/products)

---

## APIs

### WTW HR Portal

Digital employee experience platform API for managing total rewards communications, benefits enrollment status, HR content delivery, and service case management.

- **Documentation:** [https://www.wtwco.com/en-us/solutions/products/hr-portal-software](https://www.wtwco.com/en-us/solutions/products/hr-portal-software)
- **OpenAPI Spec:** [openapi/wtw-hr-portal-openapi.yml](openapi/wtw-hr-portal-openapi.yml)

### WTW Benefits Administration

API for managing employee benefits enrollment, eligibility, plan configuration, and benefits data for health, dental, vision, life, and disability programs.

- **Documentation:** [https://www.wtwco.com/en-us/services/benefits-delivery-and-administration](https://www.wtwco.com/en-us/services/benefits-delivery-and-administration)

---

## Artifacts

### OpenAPI Specifications

| File | API | Description |
|---|---|---|
| [wtw-hr-portal-openapi.yml](openapi/wtw-hr-portal-openapi.yml) | WTW HR Portal | Employee experience and case management |

### Naftiko Capabilities

**Workflow Capabilities:**

| File | Description |
|---|---|
| [capabilities/employee-experience.yaml](capabilities/employee-experience.yaml) | Unified employee digital experience workflow (9 tools) |

**Shared Per-API Definitions:**

| File | API |
|---|---|
| [capabilities/shared/hr-portal.yaml](capabilities/shared/hr-portal.yaml) | WTW HR Portal |

### JSON Schemas

| File | Resource |
|---|---|
| [json-schema/wtw-employee-schema.json](json-schema/wtw-employee-schema.json) | Employee |

### JSON Structure

| File | Resource |
|---|---|
| [json-structure/wtw-employee-structure.json](json-structure/wtw-employee-structure.json) | Employee |

### JSON-LD Context

| File | Description |
|---|---|
| [json-ld/towers-watson-context.jsonld](json-ld/towers-watson-context.jsonld) | Linked data context for WTW HR and benefits resources |

### Examples

| File | Operation |
|---|---|
| [examples/wtw-get-employee-total-rewards-example.json](examples/wtw-get-employee-total-rewards-example.json) | Get Employee Total Rewards |

### Spectral Rules

| File | Description |
|---|---|
| [rules/wtw-spectral-rules.yml](rules/wtw-spectral-rules.yml) | API design rules for WTW OpenAPI specifications |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/towers-watson-vocabulary.yml](vocabulary/towers-watson-vocabulary.yml) | Human capital and HR consulting vocabulary for WTW |

---

## Tags

`Human Resources` `Risk Management` `Benefits` `Consulting` `Actuarial` `Insurance Brokerage` `Human Capital`
