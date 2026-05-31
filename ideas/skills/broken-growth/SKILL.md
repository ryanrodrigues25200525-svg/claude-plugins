# /broken-growth

Identify former growth stocks that may be recovering.

## Tools
- openbb-mcp — price performance, valuations
- edgartools — fundamental trends
- google-news — recent developments

## Broken Growth Profile
- Once high-growth, high-multiple stock
- Sold off 50-80% from peak (multiple compression + estimate cuts)
- Now trading at reasonable or cheap valuation
- Growth may be re-accelerating from lower base
- Market still pricing for failure

## Output Format
```
Broken Growth Opportunities
[Checked: timestamp]

RECOVERING BROKEN GROWTH
---
TICKER: [Ticker]
Peak price: $X | Current: $X | Down X% from peak
Peak multiple: Xx EV/Sales | Current: Xx
What broke: [Why it sold off]
What's changing: [Signs of recovery]
Growth re-acceleration: [Evidence from recent results]
Valuation now: [Cheap vs history and peers]
Target if re-rates to X multiple: $X (X% upside)

STILL BROKEN (avoid)
| Ticker | Why not yet | What needs to happen |

SCREENING CRITERIA USED
- Down >50% from 52W high
- Revenue growth still positive
- Gross margin stable or improving
- Current EV/Sales <5x (cheap for growth)
- Insider buying or institutional accumulation
```
