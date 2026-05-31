---
name: portfolio-check
description: /portfolio-check TICKERS
---

# /portfolio-check TICKERS

Analyze a portfolio for diversification, risk, and factor exposures.

## Tools
- openbb-mcp — price history, correlations, fundamentals

## Execution
1. Pull price history for all tickers
2. Calculate correlation matrix
3. Assess sector and factor concentration
4. Run basic risk metrics

## Output Format
```
Portfolio Check — [Tickers]
[Checked: timestamp]

HOLDINGS OVERVIEW
| Ticker | Weight | Sector | Beta | YTD |
|--------|--------|--------|------|-----|

CONCENTRATION RISK
- Largest position: X% — [Ticker]
- Top 3 concentration: X%
- Sector concentration: [Most concentrated sector: X%]

CORRELATION ANALYSIS
- Highest correlation pair: [Ticker1/Ticker2]: X.XX
- Lowest correlation pair: [Ticker1/Ticker2]: X.XX
- Portfolio average correlation: X.XX
- Diversification effectiveness: Good / Moderate / Poor

FACTOR TILTS
- Value tilt: [Score]
- Growth tilt: [Score]
- Quality tilt: [Score]
- Momentum tilt: [Score]

PORTFOLIO RISK METRICS
- Weighted beta: X
- Estimated portfolio vol: X%
- Max single-stock risk: [Ticker, % of total risk]

RECOMMENDATIONS
- [What to add for better diversification]
- [What's redundant / correlated]
- [Concentration risks to reduce]
```
