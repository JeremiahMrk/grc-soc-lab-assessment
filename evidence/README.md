# Public Evidence Policy

The original GRC project maintains a substantially larger private evidence repository. This public portfolio intentionally does **not** reproduce the full catalogue.

## Why Evidence Is Curated

GRC evidence can contain information that is unnecessary or inappropriate for a public repository, including:

- passwords or authentication material
- API keys and tokens
- account identifiers
- private IP addresses and host details
- raw vulnerability-scan output
- sensitive configuration excerpts
- security telemetry and logs
- screenshots containing operational details
- exact exploitation or privilege-escalation paths

Publishing all of that would not improve recruiter evaluation enough to justify the exposure.

## What the Portfolio Demonstrates Instead

The repository documents the evidence-management methodology:

- structured evidence identifiers
- consistent evidence categories
- asset linkage
- finding linkage
- risk linkage
- control/treatment linkage
- post-treatment verification

The private project follows the traceability path:

**Asset → Evidence → Finding → Risk → Control / Treatment → Verification**

## Sanitization Standard

Any evidence added to this public folder should be reviewed before publication and must remove or obscure:

- credentials and secrets
- personal information
- account names when unnecessary
- private host/IP information when unnecessary
- raw request/response data
- reusable attack sequences
- sensitive file paths or configuration values

When evidence cannot be made safely public without losing context, the correct decision is to omit it.
