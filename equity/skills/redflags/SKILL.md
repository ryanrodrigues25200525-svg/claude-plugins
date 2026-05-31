---
name: redflags
description: /redflags TICKER
---

# /redflags TICKER

Automated risk scanner for financial red flags.

## Tools
- edgartools — filings, financials, ownership data

## Execution
1. Pull last 2 years of filings and financial data
2. Scan systematically across all risk categories
3. Score each category and produce overall risk rating

## Red Flag Checklist
- **Dilution:** Share count growth, at-the-market offerings, convertibles, warrants
- **Debt:** Leverage trend, covenant risk, maturity wall, refinancing risk
- **Cash Burn:** Runway, FCF deterioration, working capital issues
- **Revenue Quality:** Customer concentration, deferred revenue changes, channel stuffing signals
- **Accounting:** Auditor changes, restatements, material weaknesses, aggressive revenue recognition
- **Insider Activity:** Cluster selling, large exec sales, option exercises and immediate sales
- **Guidance:** Consistent lowering, vague language, sudden CFO/CEO changes
- **Legal:** New material litigation, regulatory investigations, SEC inquiries

## Output Format
```
TICKER — Red Flag Scan
[Checked: timestamp]

🔴 HIGH RISK FLAGS
- [Critical issues]

🟡 WATCH FLAGS
- [Concerning but not critical]

🟢 CLEAR
- [Areas with no concern]

OVERALL RISK RATING: 🔴 High / 🟡 Medium / 🟢 Low
SUMMARY: [2-3 sentences]
```
