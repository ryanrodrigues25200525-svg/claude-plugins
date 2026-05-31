---
name: guidance-tracker
description: /guidance-tracker
---

# /guidance-tracker

Track guidance changes across the market with sector trend analysis.

## Tools
- edgartools — 10-Q, 8-K, earnings filings with guidance

## Output Format
```
Guidance Tracker
[Checked: timestamp]

GUIDANCE RAISES 🟢
| Ticker | Sector | Old | New | % Change | Reason |
|--------|--------|-----|-----|----------|--------|

GUIDANCE CUTS 🔴
| Ticker | Sector | Old | New | % Change | Reason |

GUIDANCE WITHDRAWN ⚠️
| Ticker | Reason | Impact |

SECTOR TRENDS
| Sector | Raises | Cuts | Net | Trend |
|--------|--------|------|-----|-------|

MACRO READ FROM GUIDANCE
[What corporate guidance collectively says about economic conditions]

BEST RISK/REWARD FROM GUIDANCE CHANGES
- Buy on cut overreaction: [Ticker, reasoning]
- Avoid guidance raise that's priced in: [Ticker, reasoning]
```
