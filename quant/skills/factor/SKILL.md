---
name: factor
description: /factor TICKER
---

# /factor TICKER

Analyze factor exposures for a stock or portfolio.

## Tools
- paper-search-mcp — factor definitions and research
- openbb-mcp — price and fundamental data for factor calculation

## Factors to Assess
- **Value**: P/E, P/B, EV/EBITDA vs peers
- **Quality**: ROE, ROIC, earnings stability, low leverage
- **Growth**: Revenue and earnings growth vs peers
- **Momentum**: Price momentum (1M, 3M, 6M, 12M)
- **Low Volatility**: Beta, realized volatility
- **Size**: Market cap (small/mid/large)

## Output Format
```
TICKER — Factor Analysis
[Checked: timestamp]

FACTOR EXPOSURES
| Factor | Score | Percentile | Signal |
|--------|-------|------------|--------|
| Value | | | 🟢🟡🔴 |
| Quality | | | |
| Growth | | | |
| Momentum | | | |
| Low Vol | | | |
| Size | | | |

FACTOR PROFILE
- Primary factors: [Strongest exposures]
- Factor conflicts: [Where factors contradict]
- Overall factor score: X/10

RISK FACTOR EXPOSURE
- Market beta: X
- Rate sensitivity: High/Medium/Low
- Dollar sensitivity: High/Medium/Low

COMPARABLE FACTOR STOCKS
[Other stocks with similar factor profile]

POSITIONING CONTEXT
[Is this stock's factor profile in or out of favour in current market?]
```
