# /analyst-vs-reality

Compare analyst forecasts against actual company performance.

## Tools
- openbb-mcp — equity_estimates_historical, equity_fundamental_historical_eps
- edgartools — actual financial results

## Output Format
```
TICKER — Analyst vs Reality
[Checked: timestamp]

EPS TRACK RECORD (last 8 quarters)
| Quarter | Consensus Est | Actual | Beat/Miss | % Surprise |
|---------|--------------|--------|-----------|------------|

REVENUE TRACK RECORD
| Quarter | Consensus Est | Actual | Beat/Miss | % Surprise |

ANALYST ACCURACY ASSESSMENT
- Average EPS beat: X% (beats by X cents on avg)
- Beat rate: X% of quarters (last 8)
- Analysts: Consistently too [conservative/aggressive]

GUIDANCE CREDIBILITY
- Management guide vs actual: [Tend to guide low and beat / guide accurately / miss own guidance]

FORWARD ESTIMATE RELIABILITY
- With X% typical upside surprise, adjusted forward EPS: $X vs stated $X
- Adjusted fair value implication: [Higher/lower than consensus]

CONCLUSION: Are estimates too high or too low?
```
