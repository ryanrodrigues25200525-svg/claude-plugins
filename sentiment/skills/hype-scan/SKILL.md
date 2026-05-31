---
name: hype-scan
description: /hype-scan
---

# /hype-scan

Find stocks receiving unusual retail attention — determine if justified.

## Tools
- google-news — trending stocks, unusual volume news
- agent-reach-exa — Reddit and social trending tickers

## Execution
1. Search for stocks trending on retail platforms
2. Search for stocks with unusual news volume
3. For each: pull basics via openbb-mcp to assess if hype is justified
4. Flag pump-and-dump risks

## Output Format
```
Hype Scan
[Checked: timestamp]

TRENDING NOW
| Ticker | Hype Source | Reason | Justified? | Risk |
|--------|-------------|--------|------------|------|

HYPE JUSTIFIED 🟢
- [Ticker]: [Why the attention is warranted]

HYPE UNJUSTIFIED 🔴 (potential fade/short)
- [Ticker]: [Why it's hype without substance]

MEME SQUEEZE POTENTIAL
- [Tickers with high short interest + retail interest]

WARNING: [Any obvious pump and dump setups]
```
