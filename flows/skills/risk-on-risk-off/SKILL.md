---
name: risk-on-risk-off
description: /risk-on-risk-off
---

# /risk-on-risk-off

Measure whether markets favour growth/cyclicals or defensives/bonds/cash.

## Tools
- openbb-mcp — equity performance, credit spreads, rates, VIX
- fed-speech-mcp — policy stance context

## Key Signals
- Risk-ON: Tech/small caps outperform, HY spreads tight, VIX low, USD weak
- Risk-OFF: Utilities/staples lead, HY spreads widen, VIX spikes, USD strong, bonds rally

## Output Format
```
Risk-On / Risk-Off Dashboard
[Checked: timestamp]

CURRENT MODE: 🟢 RISK-ON / 🔴 RISK-OFF / 🟡 MIXED

SIGNAL SCORECARD
| Indicator | Reading | Signal |
|-----------|---------|--------|
| VIX | X | 🟢🟡🔴 |
| HY Spreads | Xbps | |
| 10Y Treasury | X% | |
| USD (DXY) | X | |
| Tech vs Utilities | X% spread | |
| Small vs Large cap | X% spread | |
| EM vs DM | X% spread | |
| Gold | $X | |

CONVICTION: High / Medium / Low

POSITIONING IMPLICATIONS
- Equities: [Overweight growth/value/defensives]
- Fixed income: [Duration preference]
- Commodities: [Bullish/Bearish]
- Cash: [% allocation]
```
