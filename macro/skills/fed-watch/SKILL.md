---
name: fed-watch
description: /fed-watch
---

# /fed-watch

Analyze recent Fed speeches, FOMC statements, and policy direction.

## Tools
- fed-speech-mcp — Fed speeches, FOMC statements, minutes
- openbb-mcp — rate futures, EFFR, FRED series

## Execution
1. Pull latest Fed speeches and FOMC communications via fed-speech-mcp
2. Pull rate expectations from market pricing via openbb-mcp
3. Identify policy direction and key phrases/shifts

## Output Format
```
Fed Watch
[Checked: timestamp]

LATEST FED COMMUNICATIONS
- [Speaker, date, key quotes]
- [Tone: Hawkish / Neutral / Dovish]

FOMC STANCE
- Current rate: X%
- Bias: Hiking / Holding / Cutting
- Key concerns: [Inflation / Growth / Employment]

MARKET PRICING
- Next meeting implied: [Hike/Hold/Cut probability]
- Year-end rate implied: X%
- Cuts priced for next 12 months: X

LANGUAGE SHIFTS
- [Any new phrases or deleted language vs prior statement]

FED DASHBOARD
- Inflation vs target: X% vs 2% → [Comfortable/Concerned]
- Employment: [Tight/Loosening]
- Financial stability: [Any concerns raised]

OUTLOOK: [Expected policy path over next 6-12 months]
```
