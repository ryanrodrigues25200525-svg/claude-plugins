---
name: peer-compare
description: /peer-compare TICKER1 TICKER2
---

# /peer-compare TICKER1 TICKER2

Side-by-side company comparison.

## Tools
- openbb-mcp — equity_compare_company_facts, metrics, ratios
- edgartools — financial statements

## Execution
1. Pull financials and ratios for both tickers
2. Build comparison table across all key dimensions
3. Declare winner in each category
4. Give overall verdict

## Output Format
```
TICKER1 vs TICKER2 — Peer Comparison
[Checked: timestamp]

GROWTH          | TICKER1 | TICKER2 | Winner
Revenue Growth  |         |         |
EPS Growth      |         |         |
FCF Growth      |         |         |

PROFITABILITY   | TICKER1 | TICKER2 | Winner
Gross Margin    |         |         |
EBITDA Margin   |         |         |
ROIC            |         |         |

VALUATION       | TICKER1 | TICKER2 | Winner
P/E Forward     |         |         |
EV/EBITDA       |         |         |
P/FCF           |         |         |

BALANCE SHEET   | TICKER1 | TICKER2 | Winner
Net Debt/EBITDA |         |         |
Interest Cover  |         |         |

SCORECARD: TICKER1 X/8 | TICKER2 X/8
VERDICT: [Which is the better investment and why]
```
