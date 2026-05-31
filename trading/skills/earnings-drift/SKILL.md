# /earnings-drift

Post-earnings momentum — stocks that beat but haven't moved / missed but haven't fallen.

## Tools
- openbb-mcp — equity_price_performance, equity_calendar_earnings
- edgartools — recent earnings filings

## Post-Earnings Drift Logic
- Beat + gap up held = momentum continuation
- Beat + stock sold off = potential dip buy
- Miss + stock held = potential short
- Miss + stock collapsed = potential contrarian

## Output Format
```
Earnings Drift Opportunities
[Checked: timestamp]

BEAT & HOLDING (momentum longs)
| Ticker | Beat % | Reaction | Days since | Drift signal |
|--------|--------|----------|------------|--------------|

BEAT & SOLD OFF (potential dip buys)
| Ticker | Beat % | Drop % | Reason for drop | Recovery potential |

MISSED & HOLDING (potential shorts)
| Ticker | Miss % | Stock move | Why it's holding | Short signal |

MISSED & COLLAPSED (contrarian watch)
| Ticker | Miss % | Drop % | Oversold? | Catalyst to recover |

BEST DRIFT OPPORTUNITY RIGHT NOW
[Single best risk/reward earnings drift trade]
```
