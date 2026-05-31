---
name: market-consensus
description: /market-consensus
---

# /market-consensus

What investors currently believe about markets, rates, growth, and risk assets.

## Tools
- google-news — sell-side and media consensus views
- fed-speech-mcp — policy consensus
- openbb-mcp — positioning data, futures pricing

## Execution
1. Search for current Wall Street consensus across major asset classes
2. Pull market-implied expectations (rates, growth from futures)
3. Synthesise the prevailing consensus view

## Output Format
```
Market Consensus
[Checked: timestamp]

EQUITIES
- Consensus: Bullish / Neutral / Bearish
- S&P year-end target (avg): XXXX
- Key risk cited: [Most cited bear case]

RATES
- Consensus on Fed: X cuts priced, X expected by analysts
- 10Y year-end target: X%

GROWTH
- US GDP consensus: X% for YYYY
- Recession probability (consensus): X%

INFLATION
- CPI year-end consensus: X%
- "Higher for longer" believers: X% of surveyed

DOLLAR
- DXY consensus: Stronger / Weaker / Stable

COMMODITIES
- Oil consensus: $X/barrel year-end
- Gold consensus: $X/oz

CONTRARIAN OPPORTUNITIES
[Where is consensus most likely to be wrong?]
```
