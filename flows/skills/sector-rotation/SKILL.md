# /sector-rotation

Identify sector leadership changes and capital rotation.

## Tools
- openbb-mcp — equity_price_performance, etf_sectors, etf_price_performance

## Output Format
```
Sector Rotation Analysis
[Checked: timestamp]

PERFORMANCE RANKING (1M / 3M / YTD)
| Sector | 1W | 1M | 3M | YTD | Trend |
|--------|----|----|----|----|-------|
| Technology | | | | | |
| Financials | | | | | |
| Energy | | | | | |
| Healthcare | | | | | |
| Industrials | | | | | |
| Consumer Disc | | | | | |
| Consumer Stap | | | | | |
| Utilities | | | | | |
| Real Estate | | | | | |
| Materials | | | | | |
| Comm Services | | | | | |

LEADERSHIP CHANGE
- New leaders (rising): [Sectors]
- Losing leadership: [Sectors]

ROTATION SIGNAL
- From: [Sectors losing money]
- Into: [Sectors gaining money]

MACRO INTERPRETATION
[What this rotation says about economic expectations]

CYCLE POSITIONING: Early / Mid / Late cycle
```
