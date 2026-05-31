---
name: ownership
description: /ownership TICKER
---

# /ownership TICKER

Institutional ownership analysis.

## Tools
- edgartools — 13F filings, institutional holdings

## Execution
1. Pull latest 13F data for TICKER
2. Identify top 20 institutional holders
3. Compare to prior quarter for changes
4. Calculate concentration metrics

## Output Format
```
TICKER — Ownership Analysis
[Checked: timestamp]

TOP HOLDERS
| Institution | Shares | % Float | QoQ Change |
|-------------|--------|---------|------------|

OWNERSHIP SUMMARY
- Total Institutional: X%
- Top 10 Concentration: X%
- New Positions This Quarter: X
- Exits This Quarter: X

NOTABLE CHANGES
- [Large additions or reductions by major funds]

OWNERSHIP TREND: Increasing / Decreasing / Stable
```
