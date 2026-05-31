# /13f FUND

Track a hedge fund's portfolio from 13F filings.

## Tools
- edgartools — 13F institutional holdings

## Execution
1. Search for FUND's latest 13F filing via edgartools
2. Pull full position list
3. Compare to prior quarter 13F
4. Identify new positions, exits, and conviction changes

## Output Format
```
FUND — 13F Portfolio Analysis
[Checked: timestamp]

PORTFOLIO OVERVIEW
- Total Value: $X | # Positions: X
- Top 10 Concentration: X%

NEW POSITIONS
- [Ticker, size, % of portfolio]

EXITS
- [Ticker, prior size]

INCREASED (>25% QoQ)
- [Ticker, new %, change]

DECREASED (>25% QoQ)
- [Ticker, new %, change]

TOP 10 HOLDINGS
| Rank | Ticker | Value | % Portfolio | QoQ |
|------|--------|-------|-------------|-----|

KEY THEMES: [What sectors/themes dominate this portfolio]
```
