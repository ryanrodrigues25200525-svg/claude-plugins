# /reddit-sentiment TICKER

Reddit sentiment analysis across finance subreddits.

## Tools
- agent-reach-exa — Reddit search (WSB, investing, stocks, options)
- google-news — supplementary

## Execution
1. Search agent-reach for TICKER mentions on Reddit (past 7 days)
2. Sample from: r/wallstreetbets, r/investing, r/stocks, r/options
3. Classify each post/comment: bullish, bearish, neutral
4. Extract recurring narratives and key concerns

## Output Format
```
TICKER — Reddit Sentiment
[Checked: timestamp]

OVERALL SENTIMENT: 🟢 Bullish / 🔴 Bearish / ⚪ Mixed
Bullish: X% | Bearish: X% | Neutral: X%

BULL THESIS (what bulls are saying)
- [Key bullish arguments]

BEAR THESIS (what bears are saying)
- [Key bearish arguments]

RECURRING NARRATIVES
- [Most mentioned themes or concerns]

RETAIL POSITIONING
- Options bias: Calls/Puts
- Meme potential: High/Low

CONTRARIAN SIGNAL
[If sentiment is extremely one-sided, note the contrarian opportunity]
```
