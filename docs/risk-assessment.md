# Risk Assessment

## Methodology

The project uses a 5×5 likelihood-impact matrix.

**Risk score = Likelihood × Impact**

Both factors are scored from 1 to 5, producing a final score from 1 to 25.

Risk levels:

| Score | Level |
|---:|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–14 | High |
| 15–25 | Critical |

The assessment distinguishes technical finding severity from risk. A technical issue can receive a different risk priority when business/operational impact and likelihood are considered.

## Inherent Risk Register

The final inherent-risk register contains **24 risks**.

Each private register entry records:

- risk ID
- linked finding(s)
- risk statement
- likelihood
- impact
- inherent score
- risk level
- risk owner
- supporting evidence

## Evidence-Based Scoring

Risk scoring was tied to documented findings and evidence rather than assigned in isolation.

The assessment used explicit risk statements that connect:

**threat / condition → weakness → affected asset → potential impact**

## Prioritization

The risk register feeds a heatmap and treatment-priority process. Higher-scoring risks receive stronger treatment expectations, while lower risks may be accepted and monitored when justified.

The public portfolio intentionally does not reproduce raw credential weaknesses, exact administrative paths, or other details that could unnecessarily expose the lab.

## Residual-Risk Principle

A separate post-treatment assessment evaluates residual risk.

A core rule of the project is:

> A risk score is not reduced merely because a remediation was planned or configured. Post-treatment evidence must demonstrate that the relevant control was actually implemented and functioning.

This prevents optimistic treatment plans from being mistaken for verified risk reduction.
