---
name: etf-flows
description: /etf-flows
---

# /etf-flows

Track ETF inflows/outflows — where institutional money is moving.

## Tools
- openbb-mcp — etf_historical, etf_info, etf_sectors, equity_calendar_events

## Output Format
```
ETF Flows Dashboard
[Checked: timestamp]

TOP INFLOWS (past week)
| ETF | Category | Flows $M | AUM | Implication |
|-----|----------|----------|-----|-------------|

TOP OUTFLOWS (past week)
| ETF | Category | Flows $M | AUM | Implication |

SECTOR FLOW SUMMARY
- Money flowing INTO: [Sectors]
- Money flowing OUT OF: [Sectors]

THEME FLOWS
- Risk-on flows: [ETFs getting money]
- Defensive flows: [ETFs getting money]
- Fixed income: [Direction]

SIGNAL: [What ETF flows say about overall market positioning]
```
