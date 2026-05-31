---
name: volatility-dashboard
description: /volatility-dashboard
---

# /volatility-dashboard

Track VIX, term structure, realized vol, and volatility regimes.

## Tools
- openbb-mcp — derivatives_options_snapshots, equity_price_historical for realized vol

## Output Format
```
Volatility Dashboard
[Checked: timestamp]

VIX OVERVIEW
- VIX: X | 52W range: X-X | Percentile: X%
- VIX 1W change: X | Trend: Rising/Falling
- Regime: Low (<15) / Normal (15-25) / Elevated (25-35) / Crisis (>35)

TERM STRUCTURE
| Tenor | Level | vs Spot |
|-------|-------|---------|
| VIX (1M) | | |
| VXV (3M) | | |
| VXMT (6M) | | |
Structure: Contango (normal) / Backwardation (stress)

REALIZED vs IMPLIED
- SPX 30D realized vol: X%
- VIX (implied): X%
- Vol premium: Xpts [Market overpaying/underpaying for protection]

CROSS-ASSET VOL
- Move Index (bonds): X [Bond vol]
- CVIX (FX): X [Currency vol]
- OVX (oil): X [Commodity vol]

VOL REGIME: Low / Normal / Elevated / Crisis
MEAN REVERSION SIGNAL: [If VIX is extreme, note direction of likely mean reversion]
```
