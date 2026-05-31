---
name: news-catalyst
description: /news-catalyst TICKER
---

# /news-catalyst TICKER

Filter news to find only stories that actually move valuation or price.

## Tools
- google-news — recent headlines

## Execution
1. Pull all recent news for TICKER
2. Apply filter: does this change earnings estimates, competitive position, or risk profile?
3. Discard noise (routine coverage, macro commentary, analyst reiterations)
4. For remaining stories: quantify potential impact

## Filter Criteria
- Changes to revenue/earnings estimates
- New products, partnerships, or contract wins/losses
- Regulatory approvals or rejections
- Management changes
- Balance sheet events (debt, equity issuance, buybacks)
- M&A activity
- Competitive threats or opportunities

## Output Format
```
TICKER — Material News Filter
[Checked: timestamp]

MATERIAL (moves the stock)
- [Story] | Impact: [+/-X% estimated] | Why: [reasoning]

IMMATERIAL (noise)
- [Filtered out stories — brief reason]

NET IMPACT ASSESSMENT: [Summary]
```
