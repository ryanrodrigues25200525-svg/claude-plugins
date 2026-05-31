---
name: mna-watch
description: /mna-watch
---

# /mna-watch

Track mergers, acquisitions, and strategic transactions.

## Tools
- edgartools — SC TO, DEFM14A, 8-K merger filings
- google-news — M&A news and rumours

## Execution
1. Search edgartools for merger-related filings (SC TO, merger proxies)
2. Search google-news for M&A activity and rumors
3. Track deal status: announced, pending, closed, terminated

## Output Format
```
M&A Watch
[Checked: timestamp]

ANNOUNCED DEALS
| Acquirer | Target | Value | Premium | Status | Expected Close |
|----------|--------|-------|---------|--------|----------------|

RUMOURED / REPORTED
| Target | Potential Acquirer | Source | Credibility |

RECENTLY CLOSED
| Acquirer | Target | Value |

TERMINATED
| Deal | Reason |

ARBITRAGE OPPORTUNITIES
| Target | Current Price | Deal Price | Spread | Risk |

SECTOR TRENDS: [Which sectors are seeing consolidation]
```
