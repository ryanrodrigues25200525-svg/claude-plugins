---
name: filings
description: /filings TICKER
---

# /filings TICKER

Analyze recent SEC filings — 10-K, 10-Q, 8-K, S-1.

## Tools
- edgartools — all SEC filing access

## Execution
1. Pull the 3 most recent filings via edgartools
2. For each filing type focus on:
   - 10-K: business overview, risk factors, MD&A, auditor notes, related party transactions
   - 10-Q: quarterly changes, updated risks, liquidity section
   - 8-K: material events, management changes, acquisitions, financing
3. Flag anything unusual vs prior filings

## Output Format
```
TICKER — Recent SEC Filings Analysis
[Checked: timestamp]

LATEST FILINGS
- [Filing type, date, key changes]

KEY RISKS IDENTIFIED
- [New or escalating risks]

DEBT & LIQUIDITY
- [Changes in debt, credit facilities, cash position]

DILUTION RISK
- [Share issuances, convertibles, warrants, options]

LITIGATION
- [Active lawsuits, settlements, regulatory actions]

AUDITOR NOTES
- [Going concern, restatements, material weaknesses]

RED FLAGS
- [Anything materially concerning]
```
