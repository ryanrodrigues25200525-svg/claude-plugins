# /conviction-buys

Stocks where hedge funds have significantly increased position sizes.

## Tools
- edgartools — 13F quarter-over-quarter changes

## Execution
1. Compare latest 13F to prior quarter for top 100 hedge funds
2. Find stocks with largest increase in number of holders AND position size
3. Filter for quality funds (>$1B AUM)
4. Rank by conviction score

## Output Format
```
Conviction Buys — Hedge Fund Accumulation
[Checked: timestamp]

HIGH CONVICTION ADDS
| Ticker | # Funds Adding | $ Increase | Notable Funds Buying | Sector |
|--------|---------------|------------|---------------------|--------|

WHAT THEY'RE BUYING AND WHY
- [Ticker]: [Thesis based on fund context and sector dynamics]

WATCH LIST: [Stocks just below threshold worth monitoring]
```
