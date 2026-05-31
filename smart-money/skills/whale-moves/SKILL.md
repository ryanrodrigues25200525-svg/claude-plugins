# /whale-moves

Identify significant institutional buying and selling across the market.

## Tools
- edgartools — 13F aggregate data, large position changes

## Execution
1. Scan recent 13F amendments and filings for outsized position changes
2. Focus on changes >$100M or >50% position change
3. Group by sector and theme

## Output Format
```
Whale Moves — Institutional Activity
[Checked: timestamp]

BIG BUYS (New or significantly increased)
| Fund | Ticker | $ Value | % Change | Sector |
|------|--------|---------|----------|--------|

BIG SELLS (Exits or significantly reduced)
| Fund | Ticker | $ Value | % Change | Sector |

SECTOR ROTATION SIGNALS
- Into: [sectors being accumulated]
- Out of: [sectors being sold]

THEME: [What are the biggest funds positioning for?]
```
