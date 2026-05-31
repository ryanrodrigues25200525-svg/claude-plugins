# /market-breadth

Evaluate market participation and internal strength.

## Tools
- openbb-mcp — equity_price_performance, index data

## Breadth Indicators
- % stocks above 50/200 DMA
- Advance-decline line
- New 52W highs vs lows
- % stocks in uptrend
- Equal-weight vs cap-weight ratio

## Output Format
```
Market Breadth Dashboard
[Checked: timestamp]

PARTICIPATION
- % SPX stocks above 50 DMA: X% [Healthy >60%, Weak <40%]
- % SPX stocks above 200 DMA: X% [Healthy >60%]
- % NYSE stocks in uptrend: X%

ADVANCE-DECLINE
- A-D Line trend: Rising / Falling / Diverging from index
- Cumulative A-D: [Confirming/Diverging from SPX highs]

LEADERSHIP
- New 52W highs: X | New 52W lows: X | Ratio: X
- Leading sectors: [Broad or narrow]

EQUAL-WEIGHT vs CAP-WEIGHT
- RSP vs SPY YTD: [Equal-weight outperforming = broad participation]
- Small cap vs large cap: [IWM vs SPY]

BREADTH VERDICT
🟢 Broad (healthy bull) / 🟡 Narrowing (caution) / 🔴 Narrow (distribution)

DIVERGENCE SIGNAL
[Any notable divergence between index level and breadth indicators]
```
