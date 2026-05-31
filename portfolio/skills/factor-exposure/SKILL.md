---
name: factor-exposure
description: /factor-exposure
---

# /factor-exposure

Determine exposure to common investment factors across a portfolio.

## Tools
- openbb-mcp — equity fundamental data for factor scoring

## Output Format
```
Factor Exposure Analysis — [Tickers/Portfolio]
[Checked: timestamp]

PORTFOLIO FACTOR PROFILE
| Factor | Exposure Score | vs Market | Tilt |
|--------|----------------|-----------|------|
| Value (P/E, P/B) | | | Overweight/Neutral/Underweight |
| Quality (ROE, margins) | | | |
| Growth (revenue, EPS) | | | |
| Momentum (12M-1M return) | | | |
| Low Volatility (beta) | | | |
| Size (market cap) | | | |
| Profitability (ROIC) | | | |

DOMINANT FACTOR TILTS
- Primary tilt: [Factor] — [Implication in current environment]
- Secondary tilt: [Factor]

FACTOR CONCENTRATION RISK
[If portfolio is heavily tilted to one factor, what happens if that factor rotates out]

CURRENT FACTOR ENVIRONMENT FIT
- Favoured factors now: [Based on macro regime]
- Your portfolio alignment: [Good fit / Misaligned]

REBALANCING SUGGESTIONS
[If factor profile is misaligned with current environment]
```
