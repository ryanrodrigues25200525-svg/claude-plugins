---
name: macro-dashboard
description: /macro-dashboard
---

# /macro-dashboard

Complete global macro overview — one shot.

## Tools
- openbb-mcp — FRED series, rates, inflation, growth, credit
- fed-speech-mcp — Fed commentary
- eurostat-mcp — EU data

## Key Series to Pull
- Growth: US GDP, PMI (US/EU/China)
- Inflation: US CPI/PCE, EU CPI
- Labor: US unemployment, JOLTS, claims
- Rates: EFFR, 2Y/10Y Treasury, yield curve spread
- Credit: HY spreads, IG spreads, VIX
- Liquidity: Fed balance sheet, M2

## Output Format
```
Global Macro Dashboard
[Checked: timestamp]

GROWTH          | Level  | Trend  | Signal
US GDP YoY      |        |        |
US PMI          |        |        |
EU PMI          |        |        |

INFLATION       | Level  | Trend  | Signal
US CPI YoY      |        |        |
US Core PCE     |        |        |
EU CPI YoY      |        |        |

MONETARY POLICY | Level  | Trend  | Signal
Fed Funds Rate  |        |        |
ECB Rate        |        |        |
Real Rate (US)  |        |        |

RATES           | Level  | Trend  | Signal
2Y Treasury     |        |        |
10Y Treasury    |        |        |
2s10s Spread    |        |        |

RISK            | Level  | Trend  | Signal
VIX             |        |        |
HY Spreads      |        |        |
IG Spreads      |        |        |

MACRO REGIME: [Goldilocks / Stagflation / Recession / Reflation / etc.]
FED SIGNAL: [Latest from fed-speech-mcp]
KEY RISK: [The #1 macro risk right now]
```
