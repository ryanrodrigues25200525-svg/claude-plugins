# /catalysts TICKER

Identify upcoming events likely to move the stock.

## Tools
- edgartools — filing history, disclosed events
- google-news — upcoming events, analyst days, regulatory timelines

## Execution
1. Pull recent filings for disclosed future events
2. Search news for scheduled events, regulatory timelines, product launches
3. Classify each catalyst by type and expected impact direction

## Output Format
```
TICKER — Catalyst Map
[Checked: timestamp]

NEAR-TERM (0-3 months)
- [Date] [Event] → Expected impact: Bullish/Bearish/Binary

MEDIUM-TERM (3-12 months)
- [Event] → [Impact assessment]

KEY RISKS TO WATCH
- [Regulatory, competitive, macro catalysts]

BINARY EVENTS
- [Events with significant upside/downside]

NEXT EARNINGS: [Date] | IMPLIED MOVE: [if available]
```
