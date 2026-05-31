---
name: earnings-revisions
description: /earnings-revisions
---

# /earnings-revisions

Track analyst estimate revisions and earnings expectation momentum.

## Tools
- openbb-mcp — equity_estimates_historical, equity_estimates_forward_eps, equity_estimates_forward_ebitda

## Output Format
```
Earnings Revisions Tracker
[Checked: timestamp]

STRONGEST POSITIVE REVISIONS (estimates going up)
| Ticker | EPS Revision % | Rev Revision % | # Analysts raising | Sector |
|--------|----------------|----------------|-------------------|--------|

STRONGEST NEGATIVE REVISIONS (estimates going down)
| Ticker | EPS Revision % | Rev Revision % | # Analysts cutting | Sector |

SECTOR REVISION TRENDS
| Sector | Net Revision % | Trend | Signal |
|--------|----------------|-------|--------|

REVISION MOMENTUM PLAYS
- Buy: [Tickers with accelerating positive revisions not yet in price]
- Avoid: [Tickers with deteriorating revisions priced as growth]

NOTE: Positive earnings revision momentum is one of the strongest known return predictors
```
