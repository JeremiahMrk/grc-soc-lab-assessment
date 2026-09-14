# GRC Assessment of Automated SOC Home Lab

Evidence-based Governance, Risk, and Compliance (GRC) self-assessment of a personal Automated SOC Home Lab.

The project applies structured scoping, asset inventory, evidence management, risk assessment, ISO/IEC 27001:2022 control-gap analysis, Statement of Applicability (SoA), risk treatment, residual-risk review, and internal control testing to the same environment used in my SOC / Blue Team project.

> **Important:** This is a personal self-assessment of my own lab. It is not an independent audit, ISO certification, legal-compliance opinion, or assessment performed for a client organization.

## Project Snapshot

| Area | Final portfolio metric |
|---|---:|
| Asset registry | 28 assets: 24 in scope + 4 dependencies |
| Evidence repository | 126 catalogued evidence items |
| Inherent risk register | 24 risks |
| ISO 27001 gap analysis | 39 assessment rows covering 46 unique Annex A clauses |
| Statement of Applicability | 37 applicability decisions |
| Active treatment planning | 12 selected risks in the treatment phase |
| Internal control audit | 13 test items; 12 executed, 1 unavailable during the audit window |

These values come from the project's final living documents and are intentionally separated from older intermediate counts.

## Assessment Context

**Environment:** Automated SOC Home Lab

**Primary security stack:**

- Wazuh SIEM
- Sysmon telemetry
- Windows endpoint
- Ubuntu server
- n8n alert-enrichment / notification workflow
- Docker
- AbuseIPDB and Telegram as external dependencies

The formal asset inventory contains 24 in-scope assets and four external/supporting dependencies. The scope is intentionally bounded to the lab rather than the entire physical host or unrelated personal infrastructure.

## Frameworks and References

The project uses:

- ISO/IEC 27001:2022
- ISO/IEC 27001:2022 Annex A
- NIST Cybersecurity Framework 2.0
- Limited analytical mapping to Indonesian UU PDP in the compliance-mapping work

The UU PDP mapping is an academic analytical exercise and must not be interpreted as a legal opinion or proof of statutory compliance.

## GRC Workflow

The project uses an evidence-first traceability model:

**Asset → Evidence → Finding → Risk → Control / Treatment → Verification**

This structure was designed so that risk and control claims can be traced back to documented evidence rather than being presented as unsupported statements.

## Key Workstreams

### 1. Scope and Asset Governance

- Defined an ISMS boundary for the SOC lab
- Separated in-scope components from third-party and supporting dependencies
- Maintained an official asset registry with data classification and criticality

See [Scope and Assets](docs/scope-and-assets.md).

### 2. Evidence Management

- Created a central evidence catalogue
- Used structured evidence IDs across documents, configurations, screenshots, scans, logs, and reports
- Established traceability from assets through findings and risks

See [Evidence and Traceability](docs/evidence-and-traceability.md).

### 3. Risk Assessment

- Applied a 5×5 likelihood-impact methodology
- Built a 24-risk inherent risk register
- Produced risk prioritization and before/after residual-risk analysis

See [Risk Assessment](docs/risk-assessment.md).

### 4. ISO 27001 Gap Analysis and SoA

- Assessed 39 control rows covering 46 unique Annex A clauses
- Recorded implemented, partial, missing, and not-applicable conditions
- Created 37 Statement of Applicability decisions with justification

See [ISO 27001 Gap Analysis and SoA](docs/iso27001-gap-and-soa.md).

### 5. Risk Treatment and Verification

- Selected 12 risks for active treatment planning during the treatment phase
- Documented risk owners, treatment decisions, target controls, and residual-risk reasoning
- Required post-treatment evidence before reducing a risk score

See [Risk Treatment and Residual Risk](docs/risk-treatment-and-residual-risk.md).

### 6. Internal Control Testing

- Created a 13-item control-testing checklist
- Executed 12 tests; one test could not be performed within the audit window
- Preserved pass/fail criteria defined before execution
- Explicitly documented the self-review threat because the lab is operated and assessed by the same person

See [Audit and Assurance Limitations](docs/audit-and-assurance.md).

### 7. Framework Mapping

- Connected ISO/IEC 27001:2022 with NIST CSF 2.0
- Preserved scope limitations when controls/outcomes were not meaningful for a personal virtual lab
- Kept UU PDP mapping explicitly analytical rather than presenting it as legal compliance

See [Framework Mapping](docs/framework-mapping.md).

## Public Portfolio Report

A recruiter-friendly summary of the assessment is available here:

[View the GRC portfolio report](report/GRC_SOC_Lab_Assessment_Portfolio.md)

## Repository Structure

- `docs/` - sanitized summaries of the main GRC workstreams
- `evidence/` - public evidence-handling and disclosure guidance
- `report/` - recruiter-friendly portfolio report
- `DISCLAIMER.md` - scope and assurance limitations

## Public-Disclosure Approach

This repository is intentionally a **curated portfolio**, not a raw export of the original Notion workspace.

The public version omits or sanitizes:

- passwords and API secrets
- authentication material
- unnecessary private IP/address details
- raw scan output
- sensitive configuration excerpts
- full exploitation paths
- working files, progress logs, QC logs, and obsolete document versions

The goal is to demonstrate GRC methodology, evidence discipline, risk reasoning, control assessment, and audit awareness without exposing unnecessary security-sensitive information.

## Skills Demonstrated

- Information Security Governance
- ISMS Scoping
- Asset Inventory and Classification
- Evidence Management and Traceability
- Risk Assessment and Risk Register Development
- Risk Treatment Planning
- Residual-Risk Assessment
- ISO/IEC 27001:2022
- Statement of Applicability
- Control-Gap Analysis
- NIST CSF 2.0 Mapping
- Internal Control Testing
- Corrective-Action Tracking
- Security Documentation and Reporting
