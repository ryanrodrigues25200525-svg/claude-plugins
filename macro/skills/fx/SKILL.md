---
name: fx
description: /fx PAIR
---

# /fx PAIR

Currency analysis — rates, macro, flows, positioning.

## Tools
- openbb-mcp — currency_price_historical, currency_snapshots, economy_interest_rates

## Execution
1. Pull spot rate and historical performance
2. Pull rate differential between the two countries
3. Pull inflation differential
4. Assess fundamental fair value and direction

## Output Format
```
PAIR — FX Analysis
[Checked: timestamp]

CURRENT RATE: X.XXXX
1W: X% | 1M: X% | YTD: X% | 1Y: X%

RATE DIFFERENTIAL
- Country A rate: X% | Country B rate: X%
- Spread: X bps | Trend: Widening/Narrowing
- Carry trade: Long [currency] yields X% annualised

INFLATION DIFFERENTIAL
- Country A CPI: X% | Country B CPI: X%
- Real rate differential: X bps

FUNDAMENTAL FAIR VALUE
- PPP estimate: X.XXXX
- Current deviation: X% [Over/Undervalued]

POSITIONING (if available via CFTC COT)
- Speculative net position: [Long/Short], X contracts

TECHNICAL
- 50 DMA: X.XXXX | 200 DMA: X.XXXX
- Key support: X.XXXX | Key resistance: X.XXXX

VERDICT: Bullish / Bearish / Neutral on [base currency]
TARGET (3M): X.XXXX | RANGE: X.XXXX — X.XXXX
```
