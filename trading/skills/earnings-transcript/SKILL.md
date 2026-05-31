# /earnings-transcript TICKER

Summarize earnings call transcript and detect tone changes vs prior quarters.

## Tools
- edgartools — earnings transcripts, prior quarter transcripts

## Execution
1. Pull latest earnings transcript via edgartools
2. Pull prior quarter transcript for comparison
3. Analyse CEO/CFO tone, language changes, and key themes
4. Extract most important quotes

## Output Format
```
TICKER — Earnings Transcript Analysis
[Checked: timestamp]

MANAGEMENT TONE
- Overall: Confident / Cautious / Defensive / Evasive
- vs Prior quarter: More bullish / More cautious / Same

KEY CEO QUOTES
- "[Quote]" — Significance: [Why it matters]

KEY CFO QUOTES (financial commentary)
- "[Quote]" — Significance: [Why it matters]

LANGUAGE CHANGES vs PRIOR QUARTER
- NEW language (added): "[Phrase]" — Signal: [What it means]
- REMOVED language: "[Phrase]" — Signal: [What they stopped saying]
- Hedging language: [More/less hedging than prior]

ANALYST Q&A HIGHLIGHTS
- Question: [Topic] | Answer quality: Transparent / Evasive
- [Key concern raised and how management addressed it]

FORWARD SIGNALS
- Guidance tone: [Confident/Conservative/Withdrawn]
- Demand commentary: [Strong/Softening/Mixed by segment]

TRANSCRIPT VERDICT: 🟢 Bullish / 🔴 Bearish / 🟡 Mixed
```
