---
name: guidance-changes
description: /guidance-changes
---

# /guidance-changes

Track companies raising or lowering guidance.

## Tools
- edgartools — 10-Q, 8-K filings with guidance disclosures

## Execution
1. Scan recent 8-K and earnings filings for guidance language
2. Compare new guidance to prior guidance
3. Classify: raise, lower, maintain, withdraw
4. Assess market implications

## Output Format
```
Guidance Changes — Recent Updates
[Checked: timestamp]

GUIDANCE RAISES 🟢
| Ticker | Old Guide | New Guide | % Change | Reason |
|--------|-----------|-----------|----------|--------|

GUIDANCE CUTS 🔴
| Ticker | Old Guide | New Guide | % Change | Reason |

GUIDANCE WITHDRAWN ⚠️
| Ticker | Reason |

KEY TAKEAWAYS
- Sector with most raises: [Sector]
- Sector with most cuts: [Sector]
- Macro signal: [What guidance trends say about the economy]
```
