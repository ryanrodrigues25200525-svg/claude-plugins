# /trade-setup TICKER

Complete trading plan with entry, exit, and risk parameters.

## Tools
- openbb-mcp — price data, options, technicals
- google-news — catalyst and news context

## Execution
1. Pull technical levels and price data
2. Pull options for implied move and positioning
3. Pull recent news for catalyst context
4. Build complete trade plan

## Output Format
```
TICKER — Trade Setup
[Checked: timestamp]

THESIS
[1-2 sentence bull or bear case]

TRADE PARAMETERS
- Direction: Long / Short
- Entry zone: $X — $X
- Stop loss: $X (-X% from entry)
- Target 1: $X (+X%) | Target 2: $X (+X%)
- Risk/Reward: X:1
- Position size suggestion: X% of portfolio

CATALYST
- [What triggers the move and when]

TIMEFRAME: [Days / Weeks / Months]

INVALIDATION
- [What would make this trade wrong]

OPTIONS ALTERNATIVE (if applicable)
- [Suggested options structure with strikes and expiry]

RISK FACTORS
- [Key risks to the trade]
```
