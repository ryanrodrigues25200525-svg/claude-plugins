# /new-highs-lows

Monitor expansion or contraction in market leadership.

## Tools
- openbb-mcp — equity_price_performance, equity_discovery_gainers, equity_discovery_losers

## Output Format
```
New Highs / New Lows
[Checked: timestamp]

52-WEEK HIGHS
- Count: X stocks | vs prior week: [+X / -X]
- Sectors dominating new highs: [Sectors]
- Notable new highs: [Key stocks]

52-WEEK LOWS
- Count: X stocks | vs prior week: [+X / -X]
- Sectors hitting new lows: [Sectors]
- Notable new lows: [Key stocks]

HIGH-LOW RATIO: X:1 [Bullish >2:1 / Bearish <1:2]
TREND: Expanding highs (healthy) / Contracting highs (weakening) / Expanding lows (deteriorating)

SECTOR BREAKDOWN
| Sector | New Highs | New Lows | Net |
|--------|-----------|----------|-----|

SIGNAL
[What the expansion/contraction in new highs/lows says about market health]
```
