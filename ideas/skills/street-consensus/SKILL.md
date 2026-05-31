---
name: street-consensus
description: /street-consensus TICKER
---

# /street-consensus TICKER

Full analyst consensus — ratings, targets, estimates, and dispersion.

## Tools
- openbb-mcp — equity_estimates_consensus, equity_estimates_price_target, equity_estimates_forward_eps

## Output Format
```
TICKER — Street Consensus
[Checked: timestamp]

RATING DISTRIBUTION
- Buy: X | Outperform: X | Hold: X | Underperform: X | Sell: X
- Consensus: Strong Buy / Buy / Hold / Sell
- % Bullish: X%

PRICE TARGET
- Consensus PT: $X | Current: $X | Implied upside: X%
- High PT: $X | Low PT: $X | Spread: $X (X%)
- PT dispersion: [Tight/Wide — wide = uncertainty]

ESTIMATES
| Metric | This Q | Next Q | FY | NFY |
|--------|--------|--------|-----|-----|
| EPS | | | | |
| Revenue | | | | |
| EBITDA | | | | |

ESTIMATE REVISION TREND (3M)
- EPS trend: Rising / Falling / Stable
- Revenue trend: Rising / Falling / Stable

ANALYST POSITIONING
- Most recent rating change: [Date, firm, action]
- Consensus shifts this quarter: [Summary]

CONTRARIAN SIGNAL
[If consensus is very one-sided, note the risk or opportunity]
```
