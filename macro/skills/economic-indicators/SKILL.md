---
name: economic-indicators
description: /economic-indicators COUNTRY
---

# /economic-indicators COUNTRY

Full economic dashboard for any country.

## Tools
- openbb-mcp — economy_indicators, economy_gdp_real, economy_cpi, economy_unemployment, economy_interest_rates, economy_country_profile
- eurostat-mcp — EU countries (deeper data)

## Execution
1. Pull country profile via openbb-mcp economy_country_profile
2. Pull GDP, CPI, unemployment, rates via openbb-mcp economy_indicators
3. For EU countries: supplement with eurostat-mcp
4. Interpret trends and provide outlook

## Output Format
```
COUNTRY — Economic Indicators
[Checked: timestamp]

GROWTH
- GDP Growth (YoY): X% | Trend: Accelerating/Slowing
- GDP per capita: $X
- PMI: X [Expansion >50 / Contraction <50]

INFLATION
- CPI (YoY): X% | Core: X%
- Trend: Rising / Falling / Stable
- vs Central Bank Target: X%

LABOR MARKET
- Unemployment: X% | Trend: Improving/Worsening
- Wage Growth: X%

MONETARY POLICY
- Policy Rate: X% | Last change: [date/direction]
- Real Rate: X% (rate minus inflation)
- Next meeting: [date]

FISCAL
- Debt/GDP: X% | Deficit/GDP: X%

TRADE
- Current Account: X% of GDP
- Trade Balance: $X

OUTLOOK: Positive / Neutral / Negative
KEY RISKS: [Top 3 risks]
```
