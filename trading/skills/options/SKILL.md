# /options TICKER

Options market analysis — unusual activity, IV, skew, positioning.

## Tools
- openbb-mcp — derivatives_options_chains, derivatives_options_unusual, derivatives_options_snapshots

## Execution
1. Pull options chain via openbb-mcp
2. Check unusual options activity
3. Calculate put/call ratio and IV metrics
4. Assess market expectations from options pricing

## Output Format
```
TICKER — Options Analysis
[Checked: timestamp]

IMPLIED VOLATILITY
- IV Rank: X% (percentile vs 1Y range)
- IV: X% | HV30: X% | IV/HV ratio: X
- Term Structure: Contango / Backwardation

PUT/CALL RATIO
- Volume P/C: X | OI P/C: X
- Signal: Bearish / Neutral / Bullish

UNUSUAL ACTIVITY
| Expiry | Strike | Type | Volume | OI | Premium | Sentiment |
|--------|--------|------|--------|-----|---------|-----------|

GAMMA POSITIONING
- Max pain: $X
- Key gamma levels: $X, $X

OPTIONS MARKET VERDICT
- Implied move (nearest expiry): ±X%
- Directional bias: Bullish / Bearish / Neutral
```
