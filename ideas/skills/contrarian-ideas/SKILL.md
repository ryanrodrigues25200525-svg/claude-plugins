---
name: contrarian-ideas
description: /contrarian-ideas
---

# /contrarian-ideas

Find opportunities where sentiment is extremely negative but fundamentals are improving.

## Tools
- google-news — negative sentiment screening
- edgartools — fundamental improvement signals
- openbb-mcp — valuation and technical data

## Contrarian Signal Framework
- Stock down >40% from highs
- Analyst consensus: Sell or majority Hold
- Short interest: High or rising
- News sentiment: Negative
- BUT: Fundamentals stabilising or improving

## Output Format
```
Contrarian Ideas
[Checked: timestamp]

TOP CONTRARIAN LONGS
---
TICKER: [Ticker]
Why it's hated: [What narrative is driving negativity]
Why it might be wrong: [Fundamental evidence contradicting the bear case]
Valuation if sentiment normalises: $X (X% upside)
Catalyst for re-rating: [What changes market perception]
Risk if wrong: [What makes the bears right]
Conviction: High / Medium

SENTIMENT EXTREMES (most negative)
| Ticker | Analyst % Sell | Short Float | YTD Return | Quality |
|--------|---------------|-------------|------------|---------|

CONTRARIAN FILTER PASSED
[Only include names where fundamentals are actually improving, not value traps]

VALUE TRAP WARNING
[Names that look contrarian but are genuinely deteriorating — avoid]
```
