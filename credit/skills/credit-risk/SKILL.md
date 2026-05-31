# /credit-risk

Identify deteriorating corporate credit conditions.

## Tools
- openbb-mcp — fixedincome data, credit spreads
- edgartools — debt structure from filings

## Output Format
```
Credit Risk Monitor
[Checked: timestamp]

MARKET CREDIT CONDITIONS
- HY spreads: Xbps | Trend: [Tightening/Widening]
- Leveraged loan index: X | Default rate: X%
- Distressed ratio (spreads >1000bps): X% of HY market

RISING STARS (improving credit, HY → IG)
| Issuer | Current Rating | Expected Upgrade | Implication |

FALLEN ANGELS (deteriorating, IG → HY)
| Issuer | Current Rating | Risk of Downgrade | Implication |

DISTRESSED CREDITS (spreads >600bps)
| Issuer | Spread | Rating | Debt Maturity | Risk |

MATURITY WALL
- 2025-2026 HY maturities: $XBn at current rates
- Refinancing risk: [High/Medium/Low]

CREDIT CYCLE STAGE: Early / Mid / Late / Stressed
```
