---
name: deep-value
description: /deep-value
---

# /deep-value

Screen for potentially undervalued companies with improving fundamentals.

## Tools
- openbb-mcp — equity_screener, equity_fundamental_metrics, equity_fundamental_ratios
- edgartools — balance sheet and cash flow quality

## Deep Value Criteria
- P/E < 10x or P/FCF < 12x
- EV/EBITDA < 6x
- P/B < 1.5x
- Net cash or low leverage (Net debt/EBITDA < 2x)
- Positive FCF
- Not a value trap: some catalyst or improving business

## Output Format
```
Deep Value Screen
[Checked: timestamp]

DEEP VALUE CANDIDATES
---
TICKER: [Ticker] | Sector: [Sector]
Valuation: P/E Xx | EV/EBITDA Xx | P/FCF Xx | P/B Xx
Balance sheet: Net cash $X / Net debt $X | ND/EBITDA Xx
FCF yield: X%
Why cheap: [What's driving the low multiple]
Is it a value trap?: [Evidence for/against]
Catalyst to unlock value: [Buyback / Spin-off / Activist / Earnings recovery]

VALUE TRAP FILTER
[Names that are cheap but declining business — explicitly flagged as avoid]

BEST RISK/REWARD
[Single best deep value idea with clearest catalyst]

SECTOR CONCENTRATION
[Which sectors offer the most deep value right now]
```
