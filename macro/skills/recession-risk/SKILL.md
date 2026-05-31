# /recession-risk COUNTRY

Estimate recession probability using leading indicators.

## Tools
- openbb-mcp — yield curve, leading indicators, PMI, unemployment, credit spreads

## Indicators to Check
- Yield curve (2s10s, 3M10Y inversion)
- Conference Board LEI
- ISM Manufacturing PMI
- Unemployment rate trend
- Initial jobless claims trend
- Credit spreads (HY, IG)
- Consumer confidence
- Housing starts
- Real M2 money supply growth

## Output Format
```
COUNTRY — Recession Risk Assessment
[Checked: timestamp]

RECESSION PROBABILITY: X% (next 12 months)

INDICATOR SCORECARD
| Indicator | Level | Signal | Weight |
|-----------|-------|--------|--------|
| 2s10s curve | Xbps | 🔴/🟡/🟢 | High |
| PMI | X | | High |
| Unemployment | X% | | High |
| Jobless claims | X | | Medium |
| Credit spreads | Xbps | | Medium |
| LEI | X | | Medium |
| Consumer conf | X | | Low |

FLASHING RED (🔴): [Indicators signalling recession]
CAUTIONARY (🟡): [Mixed signals]
HEALTHY (🟢): [Strong indicators]

TIMELINE: If recession comes, expected in [X-Y months]
SEVERITY: Mild / Moderate / Severe

HISTORICAL COMPARISON: [Similar to which prior recession setup?]
```
