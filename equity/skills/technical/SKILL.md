---
name: technical
description: /technical TICKER
---

# /technical TICKER

Technical analysis — trend, levels, momentum, volatility.

## Tools
- openbb-mcp — equity_price_historical, equity_price_performance

## Execution
1. Pull price history via openbb-mcp
2. Calculate key technical indicators
3. Identify trend, key levels, momentum signals

## Output Format
```
TICKER — Technical Analysis
[Checked: timestamp]

TREND
- Primary trend: Uptrend / Downtrend / Sideways
- Above/below 50MA: Yes/No | 200MA: Yes/No
- Price vs 52W High: -X% | vs 52W Low: +X%

KEY LEVELS
- Resistance: $X, $X
- Support: $X, $X
- Current: $X

MOMENTUM
- RSI(14): X [Overbought >70 / Oversold <30]
- MACD: Bullish / Bearish crossover
- Volume trend: Above/below average

VOLATILITY
- ATR: $X (X% of price)
- Bollinger Band position: Upper/Middle/Lower

SIGNAL: 🟢 Bullish / 🔴 Bearish / ⚪ Neutral
SETUP: [1-2 sentence trade setup description]
```
