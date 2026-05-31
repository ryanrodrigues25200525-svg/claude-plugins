---
name: upgrades-downgrades
description: /upgrades-downgrades
---

# /upgrades-downgrades

Track analyst rating changes and explain market impact.

## Tools
- google-news — analyst rating changes
- openbb-mcp — equity_estimates_analyst_search, equity_estimates_price_target

## Output Format
```
Upgrades & Downgrades
[Checked: timestamp]

UPGRADES
| Ticker | From | To | Firm | New PT | Old PT | Reason |
|--------|------|----|------|--------|--------|--------|

DOWNGRADES
| Ticker | From | To | Firm | New PT | Old PT | Reason |

INITIATIONS
| Ticker | Rating | PT | Firm | Thesis |

PT CHANGES (no rating change)
| Ticker | Old PT | New PT | Change | Firm |

HIGH CONVICTION CALLS (from top-ranked analysts)
- [Ticker + brief thesis]

FADE OPPORTUNITIES
[Upgrades at highs or downgrades at lows worth fading]
```
