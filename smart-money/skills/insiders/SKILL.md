---
name: insiders
description: /insiders TICKER
---

# /insiders TICKER

Insider buying and selling activity analysis.

## Tools
- edgartools — Form 4 filings, insider transactions

## Execution
1. Pull all Form 4 filings for TICKER over past 6 months
2. Identify CEO, CFO, board member transactions separately
3. Classify: open market purchase vs option exercise vs sale
4. Look for cluster buying (multiple insiders buying simultaneously)

## Output Format
```
TICKER — Insider Activity
[Checked: timestamp]

RECENT TRANSACTIONS
| Date | Insider | Role | Type | Shares | Value | Price |
|------|---------|------|------|--------|-------|-------|

CLUSTER BUYING: Yes / No
CEO/CFO ACTIVITY: [Buying / Selling / None]
NOTABLE: [Any significant single transactions]

SIGNAL: 🟢 Bullish / 🔴 Bearish / ⚪ Neutral
INTERPRETATION: [2-3 sentences]
```
