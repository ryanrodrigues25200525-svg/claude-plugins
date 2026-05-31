# /smart-money TICKER

Combined smart money intelligence — insiders, institutions, hedge funds.

## Tools
- edgartools — Form 4, 13F, 13D/G filings

## Execution
1. Pull insider transactions (Form 4) — last 6 months
2. Pull institutional ownership changes (13F) — last quarter
3. Check for 13D/G activist filings
4. Synthesize into unified signal

## Output Format
```
TICKER — Smart Money Dashboard
[Checked: timestamp]

INSIDER SIGNAL
- Recent activity: [Buying / Selling / None]
- Notable: [CEO/CFO transactions]

INSTITUTIONAL SIGNAL
- Net flow: [Adding / Reducing / Stable]
- Notable adds: [Fund names]
- Notable exits: [Fund names]

ACTIVIST PRESENCE
- [Any 13D/G filers, their thesis]

COMBINED SIGNAL: 🟢 Strong Buy / 🟢 Buy / ⚪ Neutral / 🔴 Sell / 🔴 Strong Sell

CONVICTION: High / Medium / Low
REASONING: [2-3 sentences synthesizing all signals]
```
