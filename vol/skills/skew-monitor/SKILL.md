# /skew-monitor

Track put-call skew and tail-risk pricing across the market.

## Tools
- openbb-mcp — derivatives_options_chains, derivatives_options_surface

## Skew Concepts
- High put skew: market paying up for downside protection (fearful)
- Low put skew: complacency, cheap downside protection
- Call skew: upside demand, squeeze potential
- SKEW Index: measures tail risk pricing

## Output Format
```
Skew Monitor
[Checked: timestamp]

SPX SKEW
- CBOE SKEW Index: X | 52W range: X-X
- 25-delta put skew: X vol pts
- Interpretation: [Fearful/Neutral/Complacent]

PUT SKEW BY EXPIRY
| Expiry | 25D Put IV | ATM IV | Skew | Signal |
|--------|-----------|--------|------|--------|
| 1W | | | | |
| 1M | | | | |
| 3M | | | | |

STOCKS WITH ELEVATED PUT SKEW (fear)
| Ticker | Put skew | Reason | Contrarian opportunity? |

STOCKS WITH ELEVATED CALL SKEW (squeeze potential)
| Ticker | Call skew | Short interest | Setup |

SKEW TRADE IDEAS
- Cheap tail protection: [Where puts are cheap relative to history]
- Overpriced fear: [Where puts are expensive — sell to finance upside]
```
