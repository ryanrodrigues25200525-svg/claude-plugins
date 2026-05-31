---
name: valuation
description: /valuation TICKER
---

# /valuation TICKER

Estimate fair value using multiples and peer comparisons.

## Tools
- openbb-mcp — equity_fundamental_metrics, equity_estimates_consensus, equity_compare_peers
- edgartools — financial statements for DCF inputs

## Execution
1. Pull current trading multiples via openbb-mcp
2. Pull consensus estimates for forward multiples
3. Identify peer group and their multiples
4. Build bull/base/bear scenarios

## Output Format
```
TICKER — Valuation Analysis
[Checked: timestamp]

CURRENT MULTIPLES
- P/E: Xx | Forward P/E: Xx
- EV/EBITDA: Xx | Forward EV/EBITDA: Xx
- P/S: Xx | P/FCF: Xx
- EV/Sales: Xx

PEER COMPARISON
| Peer | P/E | EV/EBITDA | P/S |
|------|-----|-----------|-----|
| [peers] |

SCENARIOS
- Bear: $XX (Xx multiple on low estimates)
- Base: $XX (Xx multiple on consensus)
- Bull: $XX (Xx multiple on high estimates)

CURRENT PRICE: $XX
UPSIDE/DOWNSIDE: Base +X% | Bull +X% | Bear -X%

VERDICT: Cheap / Fair / Expensive
```
