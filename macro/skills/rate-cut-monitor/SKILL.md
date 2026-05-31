---
name: rate-cut-monitor
description: /rate-cut-monitor
---

# /rate-cut-monitor

Track market expectations for rate cuts and policy pivots.

## Tools
- fed-speech-mcp — Fed communications
- openbb-mcp — EFFR futures implied rates, FRED series

## Execution
1. Pull current market pricing for rate cuts via openbb
2. Pull latest Fed/central bank communications via fed-speech-mcp
3. Compare market expectations to stated policy
4. Identify mispricing opportunities

## Output Format
```
Rate Cut Monitor
[Checked: timestamp]

CURRENT RATES
- Fed Funds: X% | Market-implied year-end: X%
- Cuts priced: X cuts of 25bps in next 12 months

MEETING-BY-MEETING PRICING
| Meeting Date | Implied Rate | Cut Probability |
|--------------|-------------|-----------------|

FED COMMUNICATION TONE
- [Latest speech summary — hawkish/dovish signals]
- [Key phrases to watch]

MARKET vs FED GAP
- Market pricing: X cuts
- Fed dots suggest: X cuts
- Gap: [Market too aggressive/too conservative]

DATA DEPENDENCY
- CPI needs to reach: X% for first cut
- Unemployment needs to reach: X% for first cut
- Current trajectory implies first cut: [Month YYYY]

TRADE IMPLICATION
- [How to position if market is mispricing cuts]
```
