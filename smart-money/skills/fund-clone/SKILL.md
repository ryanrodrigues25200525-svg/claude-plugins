---
name: fund-clone
description: /fund-clone FUND
---

# /fund-clone FUND

Build a clone portfolio based on a hedge fund's highest-conviction holdings.

## Tools
- edgartools — 13F filings

## Execution
1. Pull latest 13F for FUND
2. Identify top 10 positions by portfolio weight
3. Filter for positions held >2 quarters (conviction, not short-term)
4. Adjust for staleness (13F is 45 days delayed)

## Output Format
```
FUND Clone Portfolio
[Checked: timestamp] [Note: 13F data is 45 days delayed]

CLONE PORTFOLIO
| Ticker | Weight | Quarters Held | Thesis |
|--------|--------|---------------|--------|

EQUAL-WEIGHT VERSION
| Ticker | Suggested Weight |

REPLICATION NOTES
- [Positions likely still held vs possibly exited]
- [New positions since filing that may have been added]

PERFORMANCE CONTEXT
- FUND YTD: X% | S&P YTD: X%
- Clone YTD (hypothetical): X%
```
