---
name: rates
description: /rates
---

# /rates

Full rates and yield curve analysis.

## Tools
- openbb-mcp — fixedincome_government_treasury_rates, fixedincome_government_yield_curve, fixedincome_rate_effr, fixedincome_rate_sofr, fixedincome_spreads_tcm

## Execution
1. Pull full yield curve data
2. Pull overnight/short rates
3. Calculate spreads and inversions
4. Assess implications

## Output Format
```
Rates Dashboard
[Checked: timestamp]

YIELD CURVE (US Treasuries)
| Tenor | Yield | Change (1W) | Change (1M) |
|-------|-------|-------------|-------------|
| 3M    |       |             |             |
| 2Y    |       |             |             |
| 5Y    |       |             |             |
| 10Y   |       |             |             |
| 30Y   |       |             |             |

KEY SPREADS
- 2s10s: X bps [Inverted/Normal] | Change: X bps
- 3M10Y: X bps | Change: X bps

POLICY RATES
- EFFR: X% | SOFR: X%
- Real 10Y yield: X% (nominal minus breakeven)
- 10Y Breakeven inflation: X%

CURVE SIGNAL
- Shape: Inverted / Flat / Normal / Steep
- Recession signal: [Strong/Moderate/Weak]
- Duration positioning: Long / Neutral / Short

KEY LEVELS TO WATCH: [X%, X% on 10Y]
```
