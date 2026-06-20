# Caris Life Sciences (caris-life-sciences)

Caris Life Sciences is a molecular science and precision oncology company that delivers comprehensive tumor profiling (Caris Molecular Intelligence / MI Profiling) and a clinico-genomic real-world data platform (CODEai). Clinician access is through the Caris+Portal and partner-provisioned EHR integrations (Epic Orders and Results Anywhere, OncoEMR/Flatiron, iKnowMed, and other CMS-certified systems). Caris does not publish a public, self-serve developer API; integration is partner- and contract-based.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/caris-life-sciences/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/caris-life-sciences/refs/heads/main/apis.yml)

## Tags

- Precision Oncology
- Molecular Profiling
- Genomics
- Healthcare
- EHR Integration
- Real-World Data

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Caris+Portal

Web-based clinician portal for electronically submitting test orders (requisitions), tracking case progress, and viewing molecular profiling results. Accessed through the browser at portal.caris.ai; no documented public HTTP API is exposed to third-party developers.

- **Human URL:** [https://portal.caris.ai/](https://portal.caris.ai/)
- **Base URL:** `https://portal.caris.ai`

#### Tags

- Portal
- Ordering
- Results

#### Properties

- [Documentation](https://www.carislifesciences.com/order/)
- [OpenAPI](openapi/caris-life-sciences-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/caris-life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/caris-life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Caris EHR Integration

Partner-provisioned electronic orders-and-results integration with CMS-certified EHR systems (Epic Orders and Results Anywhere, OncoEMR/Flatiron, iKnowMed, Meditech, Oracle, Aria, Elekta, Practice Fusion, CareEvolve, and others). Implemented via standards-based lab order/result interfaces; not a publicly documented developer API.

- **Human URL:** [https://www.carislifesciences.com/partners/ehr-integrations/](https://www.carislifesciences.com/partners/ehr-integrations/)
- **Base URL:** `https://www.carislifesciences.com/partners/ehr-integrations/`

#### Tags

- EHR
- HL7
- Orders and Results
- Epic

#### Properties

- [Documentation](https://www.carislifesciences.com/partners/ehr-integrations/)
- [OpenAPI](openapi/caris-life-sciences-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/caris-life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/caris-life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Caris CODEai Real-World Data

Clinico-genomic real-world data platform combining molecular data, treatment information, and clinical outcomes for biopharma and academic research cohort analysis. Access is granted under contract via a Caris Molecular Science Liaison; no public programmatic API is documented.

- **Human URL:** [https://www.carislifesciences.com/research/artificial-intelligence/caris-codeai/](https://www.carislifesciences.com/research/artificial-intelligence/caris-codeai/)
- **Base URL:** `https://www.carislifesciences.com/research/artificial-intelligence/caris-codeai/`

#### Tags

- Real-World Data
- Clinico-Genomic
- Biopharma
- Research

#### Properties

- [Documentation](https://www.carislifesciences.com/research/artificial-intelligence/caris-codeai/)
- [OpenAPI](openapi/caris-life-sciences-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/caris-life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/caris-life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/caris-life-sciences)
- [Website](https://www.carislifesciences.com)
- [Documentation](https://www.carislifesciences.com/partners/ehr-integrations/)
- [Plans](plans/caris-life-sciences-plans-pricing.yml)
- [Rate Limits](rate-limits/caris-life-sciences-rate-limits.yml)
- [Fin Ops](finops/caris-life-sciences-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

## Note on API Availability

Caris Life Sciences does not publish a public, self-serve developer API or API reference. The surfaces catalogued here — the Caris+Portal, partner EHR integrations, and the CODEai data platform — are provisioned through partnership, onboarding, or contract rather than open developer sign-up. The OpenAPI, plans, rate-limit, and FinOps artifacts in this repository are marked `reconciled: false` where details are not publicly documented, and describe only what Caris states publicly. No endpoints have been fabricated.
