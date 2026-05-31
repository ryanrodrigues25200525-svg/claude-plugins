# /best-ideas

Generate highest-conviction investment opportunities across all signals.

## Tools
- edgartools — fundamental quality screening
- openbb-mcp — valuation, momentum, analyst data
- google-news — recent catalysts and themes

## Idea Generation Process
1. Screen for improving fundamentals (earnings revisions up)
2. Screen for reasonable valuation (not overextended)
3. Check insider/institutional buying
4. Check for upcoming catalysts
5. Check technical setup (not extended)
6. Filter for quality business (high ROIC, strong balance sheet)

## Output Format
```
Best Ideas — High Conviction Opportunities
[Checked: timestamp]

LONG IDEAS
---
TICKER: [Ticker] | Sector: [Sector] | Market cap: $X
Thesis: [2-3 sentence investment case]
Valuation: [Current multiple vs fair value]
Catalyst: [What drives the stock in next 3-12 months]
Conviction: High / Medium
Risk: [Main downside risk]

SHORT / AVOID IDEAS
---
TICKER: [Ticker]
Thesis: [Why to avoid or short]
Catalyst for pain: [What could trigger selloff]

THEMATIC BASKET
[If a macro theme is playing out, suggest a basket of names to own]

PORTFOLIO CONSTRUCTION
[How to size these ideas relative to each other]
```
