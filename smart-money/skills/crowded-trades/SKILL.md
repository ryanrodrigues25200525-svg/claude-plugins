---
name: crowded-trades
description: /crowded-trades
---

# /crowded-trades

Identify stocks with extremely high hedge fund ownership and crowding risk.

## Tools
- edgartools — 13F concentration data

## Execution
1. Calculate hedge fund ownership % of float for all stocks
2. Flag stocks where hedge funds own >20% of float
3. Assess crowding risk: if everyone owns it, who's left to buy?
4. Identify potential unwind risk

## Output Format
```
Crowded Trades — Risk Monitor
[Checked: timestamp]

MOST CROWDED (by HF ownership % of float)
| Ticker | HF Ownership % | # Funds | Crowding Risk | Sector |
|--------|---------------|---------|---------------|--------|

CROWDING RISK ASSESSMENT
- Extreme crowding (>30% HF owned): [Tickers]
- High crowding (20-30%): [Tickers]
- Moderately crowded (10-20%): [Tickers]

UNWIND RISK: [Which crowded trades have weakening fundamentals?]
AVOID: [Highest risk for sharp selloff on any negative news]
```
