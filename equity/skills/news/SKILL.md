---
name: news
description: /news TICKER
---

# /news TICKER

Summarize recent news with market impact classification.

## Tools
- google-news — recent headlines and articles

## Execution
1. Search google-news for TICKER over past 7 days
2. Classify each story: Bullish / Bearish / Neutral
3. Assess magnitude of impact on stock price

## Output Format
```
TICKER — News Summary
[Checked: timestamp]

🟢 BULLISH
- [Headline] — [Why it matters]

🔴 BEARISH
- [Headline] — [Why it matters]

⚪ NEUTRAL / NOISE
- [Headlines with no material impact]

NET SENTIMENT: Bullish / Bearish / Mixed
KEY TAKEAWAY: [1-2 sentences]
```
