# ISO/IEC 27001:2022 Gap Analysis and Statement of Applicability

## Two Different Questions

The project separates two governance artifacts that answer different questions.

### Gap Analysis

**Question:** What is the current implementation condition of relevant controls?

The final gap-analysis baseline contains **39 assessment rows covering 46 unique Annex A clauses**.

Assessment labels include:

- Implemented
- Partial
- Missing
- Not Applicable, with justification

The 39 rows and 46 clauses are not contradictory: some rows group related clauses, while a small number of clauses are separated into multiple assessment components.

### Statement of Applicability (SoA)

**Question:** Is the control applicable to this ISMS scope, and why?

The final SoA contains **37 applicability decisions**.

Each decision records the applicability rationale and implementation context for the lab environment.

## Scope-Aware Decisions

The lab is a virtual personal environment, not a corporate organization or physical data center. Applicability decisions therefore consider the actual ISMS boundary.

Examples of decision logic include:

- controls relevant to identities, logging, authentication, evidence, network security, backup, and monitoring can be directly applicable;
- controls dependent on organizational structures, employees, physical facilities, or production personal-data processing may require exclusion or limited interpretation when outside the defined scope.

An exclusion is not silently omitted; it requires a written scope-based justification.

## Snapshot Discipline

The gap analysis represents a point-in-time assessment. Later remediation can change the live control condition.

The project therefore avoids silently rewriting historical snapshots. Post-treatment status is tracked through later treatment and residual-risk artifacts.

## Framework Use

The project uses ISO/IEC 27001:2022 and Annex A as governance/control references. It does **not** claim:

- ISO certification
- conformity assessment by an accredited body
- independent assurance
- organization-wide implementation

The work demonstrates control-assessment methodology in a personal cybersecurity lab.
