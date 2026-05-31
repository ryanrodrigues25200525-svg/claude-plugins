---
name: consumer-health
description: /consumer-health COUNTRY
---

# /consumer-health COUNTRY

Assess consumer spending power, confidence, debt, and savings.

## Tools
- openbb-mcp — economy_pce, consumer confidence, retail sales, FRED consumer data

## Output Format
```
COUNTRY Consumer Health
[Checked: timestamp]

SPENDING
- Retail sales MoM: X% | YoY: X%
- Real retail sales (inflation-adjusted): X%
- PCE (US): X% | Core PCE: X%
- Trend: Accelerating / Stable / Slowing

CONFIDENCE
- Consumer confidence: X | vs prior: X | 52W range: X-X
- University of Michigan sentiment: X
- Expectations vs current conditions: [Gap analysis]

FINANCIAL HEALTH
- Household savings rate: X%
- Consumer credit growth: X% YoY
- Credit card delinquency rate: X%
- Mortgage delinquency rate: X%
- Debt service ratio: X% of income

EXCESS SAVINGS
- Pandemic savings buffer remaining: $XBn [Depleted/Remaining]
- Impact on spending outlook: [Positive/Negative]

CONSUMER HEALTH VERDICT
🟢 Strong / 🟡 Softening / 🔴 Stressed

SECTOR IMPLICATIONS
[Consumer discretionary vs staples positioning based on consumer health]
```
