# /earnings TICKER

Deep earnings review for any publicly traded company.

## Tools
- edgartools — filing data, XBRL financials, MD&A, transcript
- google-news — analyst reactions, post-earnings coverage

## Execution
1. Pull latest 10-Q or 10-K via edgartools
2. Extract: revenue, EPS, gross margin, operating margin, net income, FCF
3. Compare actuals vs prior quarter and prior year
4. Pull guidance if provided
5. Search google-news for analyst reactions and price movement
6. Synthesize transcript highlights if available

## Output Format
```
TICKER — Q[X] YYYY Earnings Review
[Checked: timestamp]

HEADLINE NUMBERS
- Revenue: $X vs $X prior / est $X → beat/miss by X%
- EPS: $X vs $X prior / est $X → beat/miss by $X
- Gross Margin: X% vs X% prior
- Operating Margin: X% vs X% prior
- FCF: $X

GUIDANCE
- [Next quarter / FY guidance vs consensus]

TRANSCRIPT HIGHLIGHTS
- [Key management quotes]
- [Forward-looking statements]

ANALYST REACTION
- [Upgrades/downgrades, PT changes]

VERDICT
🟢 Bullish / 🔴 Bearish / 🟡 Mixed
- [2-3 sentence takeaway]
```
