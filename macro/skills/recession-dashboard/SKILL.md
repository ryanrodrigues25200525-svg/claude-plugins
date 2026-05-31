# /recession-dashboard

Monitor recession indicators in real time.

## Tools
- openbb-mcp — multiple FRED series, yield curve, PMI, credit spreads

## Execution
Pull and display all key recession indicators in one view with traffic light status.

## Output Format
```
Recession Dashboard
[Checked: timestamp]

LEADING INDICATORS
| Indicator | Current | 3M Ago | Signal |
|-----------|---------|--------|--------|
| 2s10s spread | | | 🔴🟡🟢 |
| 3M10Y spread | | | |
| ISM Mfg PMI | | | |
| ISM Services | | | |
| LEI YoY | | | |

COINCIDENT INDICATORS
| Indicator | Current | 3M Ago | Signal |
|-----------|---------|--------|--------|
| Unemployment | | | |
| Payroll growth | | | |
| Real GDP | | | |
| Industrial prod | | | |

FINANCIAL CONDITIONS
| Indicator | Current | 3M Ago | Signal |
|-----------|---------|--------|--------|
| HY spreads | | | |
| IG spreads | | | |
| VIX | | | |
| Financial cond index | | | |

DASHBOARD VERDICT
🔴 Recession imminent | 🟡 Risk elevated | 🟢 Expansion continues

PROBABILITY ESTIMATE: X% in next 12 months
```
