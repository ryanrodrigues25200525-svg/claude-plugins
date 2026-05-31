---
name: hedge-fund-consensus
description: /hedge-fund-consensus
---

# /hedge-fund-consensus

Most commonly owned stocks across major hedge funds.

## Tools
- edgartools — 13F filings aggregated

## Execution
1. Pull 13F data from top 50 hedge funds
2. Count ownership frequency per stock
3. Weight by conviction (position size as % of fund)
4. Rank by consensus score

## Output Format
```
Hedge Fund Consensus — Most Owned Stocks
[Checked: timestamp]

TOP CONSENSUS LONGS
| Rank | Ticker | # Funds | Avg % of Portfolio | Sector |
|------|--------|---------|-------------------|--------|

RISING CONSENSUS (most new buyers)
| Ticker | # New Funds | Prior Rank | Current Rank |

FALLING CONSENSUS (most exits)
| Ticker | # Exits | Prior Rank | Current Rank |

SECTOR DISTRIBUTION OF CONSENSUS LONGS:
[Chart-style breakdown]
```
