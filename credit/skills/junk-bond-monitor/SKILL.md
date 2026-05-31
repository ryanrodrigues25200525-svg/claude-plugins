# /junk-bond-monitor

Track high-yield credit conditions and risk appetite.

## Tools
- openbb-mcp — fixedincome_bond_indices, FRED HY spread series

## Output Format
```
Junk Bond Monitor
[Checked: timestamp]

HY MARKET OVERVIEW
- HY Spread (OAS): Xbps
- 52W range: X-Xbps | Percentile: X%
- HY Yield: X%
- Default rate (trailing 12M): X%

RECENT ISSUANCE
- New HY deals this week: $XBn
- Demand: Oversubscribed/Undersubscribed
- Covenant quality: Tight/Loose

DISTRESSED UNIVERSE
- % of HY >1000bps: X%
- Trend: Growing/Shrinking

CCC vs BB SPREAD
- CCC spread: Xbps | BB spread: Xbps
- CCC-BB gap: Xbps [Quality bifurcation signal]

RISK APPETITE SIGNAL
🟢 Strong appetite (spreads tight, issuance heavy)
🟡 Selective (mixed conditions)
🔴 Risk aversion (spreads wide, issuance slow)

IMPLICATION: [For leveraged equities, PE-backed companies, rate-sensitive sectors]
```
