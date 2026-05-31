# /gamma-watch

Analyze dealer gamma positioning and its effect on market behavior.

## Tools
- openbb-mcp — derivatives_options_chains, derivatives_options_snapshots

## Gamma Concepts
- Positive gamma: dealers buy dips, sell rips → suppresses volatility
- Negative gamma: dealers sell dips, buy rips → amplifies volatility
- Gamma flip: level where dealer positioning shifts (key price level)
- Max pain: price where most options expire worthless

## Output Format
```
Gamma Watch — SPX / Key Tickers
[Checked: timestamp]

SPX GAMMA POSITIONING
- Current SPX: XXXX
- Gamma flip level: XXXX [Above = positive gamma, Below = negative gamma]
- Current regime: Positive / Negative gamma

MAX PAIN
- SPX max pain: XXXX
- Distance from current: X%

KEY GAMMA LEVELS
- Large gamma at: XXXX (resistance), XXXX (support)
- Dealer hedging creates: [Pinning / Amplification] near these levels

INDIVIDUAL STOCK GAMMA WATCH
| Ticker | Max Pain | Gamma Flip | Implication |
|--------|----------|------------|-------------|

MARKET IMPLICATIONS
- [How current gamma positioning affects near-term price action]
- [Events that could trigger gamma unwind]
```
