# /wsb-dd DAY|WEEK

WallStreetBets due diligence — filtered and analysed.

## Tools
- agent-reach-exa — Reddit WSB search
- google-news — supplementary news on mentioned tickers

## Execution
1. Search agent-reach for recent WSB DD posts (r/wallstreetbets)
2. Filter: minimum upvotes, DD flair, exclude meme-only posts
3. Extract: ticker, thesis, catalysts, options play if mentioned
4. Cross-check with google-news for any corroborating/contradicting info
5. Rate each DD: quality score 1-5

## Quality Filter Criteria
- Has a clear thesis (not just "to the moon")
- Mentions specific catalysts or data
- Addresses downside risks
- Shows some fundamental or technical analysis

## Output Format
```
WSB Due Diligence — [Today/This Week]
[Checked: timestamp]

HIGH QUALITY DDs (Score 4-5/5)
---
TICKER: [Ticker]
Thesis: [Summary]
Catalyst: [What they think will happen]
Options play: [If mentioned]
Upvotes: X | Quality: X/5
Our take: [Brief assessment using available data]

MEDIUM QUALITY DDs (Score 2-3/5)
---
[Condensed summaries]

TICKERS MENTIONED MOST
| Ticker | Mentions | Sentiment | Our Assessment |
|--------|----------|-----------|----------------|

MEME ALERT 🚨
[Stocks getting hyped without substance — avoid or fade]
```
