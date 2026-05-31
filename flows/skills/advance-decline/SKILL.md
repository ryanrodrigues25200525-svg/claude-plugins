---
name: advance-decline
description: /advance-decline
---

# /advance-decline

Analyze advance-decline lines and overall market health.

## Tools
- openbb-mcp — equity market performance data

## Output Format
```
Advance-Decline Analysis
[Checked: timestamp]

TODAY'S BREADTH
- Advancing: X | Declining: X | Unchanged: X
- A-D ratio: X:1
- Up volume: X% | Down volume: X%

A-D LINE TREND (cumulative)
- Direction: Rising / Falling / Flat
- vs SPX: Confirming / Diverging
- Divergence signal: [If A-D line falling while SPX rising = bearish warning]

WEEKLY A-D TREND
- Last 4 weeks: [Rising/Falling/Mixed]
- Structural trend: [Bull market breadth / Bear market breadth]

SECTOR INTERNALS TODAY
| Sector | Advancers | Decliners | Net |
|--------|-----------|-----------|-----|

VOLUME ANALYSIS
- Total volume: X vs 20D avg: X [Above/Below average]
- Volume distribution: X% in advancing stocks

INTERNAL MARKET VERDICT
🟢 Healthy internals | 🟡 Mixed | 🔴 Poor breadth
```
