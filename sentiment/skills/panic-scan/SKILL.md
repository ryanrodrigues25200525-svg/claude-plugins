# /panic-scan

Find heavily sold-off stocks — evaluate if selloff is justified or overdone.

## Tools
- google-news — selloff news and reason
- openbb-mcp — price performance, equity_discovery_losers

## Execution
1. Pull biggest losers via openbb-mcp equity_discovery_losers
2. For each: search google-news for the reason
3. Assess: is the selloff fundamental (deserved) or emotional (opportunity)?
4. Flag oversold opportunities

## Output Format
```
Panic Scan — Oversold Opportunities
[Checked: timestamp]

BIGGEST LOSERS TODAY
| Ticker | % Drop | Volume | Reason | Justified? |
|--------|--------|--------|--------|------------|

OVERDONE SELLOFFS (potential buy)
- [Ticker]: Down X% because [reason] — but [why it's overdone]
- Fundamental impact: [Quantify the actual damage]
- Historical precedent: [How similar selloffs resolved]

DESERVED SELLOFFS (avoid or short)
- [Ticker]: [Why this is fundamental deterioration]

FEAR GAUGE: [Is this stock-specific or market-wide panic?]
```
