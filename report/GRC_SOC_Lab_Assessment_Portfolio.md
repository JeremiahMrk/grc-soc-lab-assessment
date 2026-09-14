# GRC Assessment of Automated SOC Home Lab

Jeremiah Mark  
Cyber Security Student, BINUS University

## Executive Summary

This portfolio summarizes an evidence-based personal GRC self-assessment of an Automated SOC Home Lab using ISO/IEC 27001:2022 and NIST Cybersecurity Framework 2.0.

The project is a **self-assessment**, not an independent audit, certification engagement, legal opinion, or client assessment.

### Final Portfolio Baseline

| Area | Result |
|---|---:|
| Asset registry | 28 assets: 24 in scope + 4 dependencies |
| Evidence repository | 126 catalogued evidence items |
| Findings traceability | 39 of 39 findings linked to coded evidence |
| Inherent risk register | 24 risks |
| ISO 27001 gap analysis | 39 assessment rows covering 46 unique Annex A clauses |
| Statement of Applicability | 37 applicability decisions |
| Active treatment planning | 12 selected risks |
| Internal control testing | 13 items; 12 executed, 1 unavailable during the audit window |
| Corrective actions | 13 items; 8 closed at final review |

## 1. Assessment Context

The assessed environment is the same personal SOC lab used for defensive-security work. It includes Wazuh-based monitoring, Sysmon endpoint telemetry, Windows and Ubuntu systems, Docker, and an n8n alert-enrichment / notification workflow.

The ISMS boundary is intentionally limited to the lab. External services and supporting infrastructure are documented as dependencies rather than silently absorbed into the assessment scope.

## 2. Evidence and Traceability

The project follows an evidence-first model:

**Asset → Evidence → Finding → Risk → Control / Treatment → Verification**

The final evidence repository contains 126 catalogued items across categories such as documents, configurations, screenshots, incident reports, assessment outputs, measurements, and logs.

The final traceability review recorded 39 findings and confirmed that all 39 were linked to valid coded evidence.

This is an internal project-quality result and does not imply third-party assurance.

## 3. Risk Assessment

The project uses a 5×5 likelihood-impact matrix.

**Risk score = Likelihood × Impact**

| Score | Level |
|---:|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–14 | High |
| 15–25 | Critical |

The final inherent-risk register contains 24 risks.

Technical finding severity and governance risk are treated as different concepts. Risk priority is based on the lab context, affected assets, likelihood, impact, ownership, and supporting evidence.

## 4. ISO/IEC 27001:2022 Gap Analysis

The control-gap assessment evaluates implementation conditions such as:

- Implemented
- Partial
- Missing
- Not Applicable, with justification

The final baseline contains 39 assessment rows covering 46 unique Annex A clauses.

The count of assessment rows and unique clauses differs because some related clauses are grouped while selected clauses are assessed through more than one component.

## 5. Statement of Applicability

The SoA answers a different question from the gap analysis:

**Is the control applicable to this ISMS scope, and why?**

The final SoA contains 37 applicability decisions with written justification.

The work does not claim ISO certification or accredited conformity assessment.

## 6. Risk Treatment and Residual Risk

The documented treatment phase selected 12 risks for active treatment planning.

Treatment options include:

- Mitigate
- Accept
- Transfer
- Avoid

A treatment decision is not treated as completed remediation by itself.

The residual-risk methodology follows four rules:

1. The scoring scale remains unchanged before and after treatment.
2. Risk is not reduced without post-treatment evidence showing an operating control.
3. Impact is reduced only when defensible evidence supports the change.
4. Like-for-like comparisons are distinguished from changes caused by newly discovered risks.

## 7. Internal Control Testing

The final audit checklist contains 13 test items. Twelve were executed; one could not be performed during the audit window.

Testing principles include:

- define criteria before execution;
- retain actual outcomes even when they differ from predictions;
- use negative testing for preventive controls where appropriate;
- require persistence evidence for controls expected to survive restart/reboot;
- report unavailable tests as unavailable rather than forcing a pass/fail result.

## 8. Corrective Action

The audit-report phase tracks nonconformities, observations, root causes, and corrective actions.

The final baseline contains 13 corrective-action items, with 8 closed at the final review point.

Open, accepted, or unresolved items were preserved rather than silently presented as complete.

## 9. Assurance Limitation

The lab is operated and assessed by one person. The same person performed remediation and later reviewed parts of that work.

This creates a **self-review threat** and limits assurance.

For that reason, this portfolio deliberately uses the terms **self-assessment** and **internal control testing in a personal lab**, not independent audit or third-party assurance.

## 10. Cross-Framework Mapping

ISO/IEC 27001:2022 is the main ISMS/control reference. NIST CSF 2.0 is used as a complementary cybersecurity-governance and risk reference.

A limited academic mapping to Indonesian UU PDP is included in the broader project. It is not legal advice or proof of statutory compliance.

## 11. Public-Disclosure Boundary

The original project contains substantially more granular evidence, configuration records, findings, scan data, and version history than this public portfolio.

This repository intentionally omits credentials, raw security telemetry, sensitive configurations, private network details, and reusable attack paths.

The goal is to demonstrate GRC methodology and evidence discipline without exposing avoidable security-sensitive information.
