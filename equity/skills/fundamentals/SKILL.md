---
name: fundamentals
description: /fundamentals TICKER
---

# /fundamentals TICKER

Comprehensive business health report.

## Tools
- edgartools — financial statements, XBRL data
- openbb-mcp — live ratios, market data, estimates

## Execution
1. Pull 3-5 years of financial statements via edgartools
2. Pull current ratios and market data via openbb-mcp equity_fundamental_metrics and ratios
3. Analyze trends across all key metrics

## Output Format
```
TICKER — Fundamentals Report
[Checked: timestamp]

REVENUE GROWTH
- [YoY and QoQ trends, acceleration/deceleration]

PROFITABILITY
- Gross Margin: X% (trend)
- EBITDA Margin: X% (trend)
- Net Margin: X% (trend)
- ROE / ROA / ROIC

CASH FLOW
- Operating CF: $X
- FCF: $X
- FCF Conversion: X%

BALANCE SHEET
- Cash: $X | Debt: $X | Net Debt: $X
- Debt/EBITDA: Xx
- Interest Coverage: Xx

CAPITAL ALLOCATION
- Buybacks: $X | Dividends: $X | Capex: $X

QUALITY SCORE
🟢 High / 🟡 Medium / 🔴 Low Quality Business
```
