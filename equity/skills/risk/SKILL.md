# /risk TICKER

Full investment risk profile analysis.

## Tools
- openbb-mcp — price history, volatility, options data
- edgartools — financial risk factors, debt structure

## Execution
1. Pull price history and compute volatility metrics via openbb-mcp
2. Pull debt structure and financial risk from edgartools
3. Assess macro sensitivity
4. Combine into risk scorecard

## Output Format
```
TICKER — Risk Profile
[Checked: timestamp]

MARKET RISK
- Beta: X | 52W Volatility: X%
- Max Drawdown (1Y): -X%
- Correlation to SPX: X

FINANCIAL RISK
- Debt/EBITDA: Xx | Interest Coverage: Xx
- FCF Margin: X% | Cash Runway: X months

EARNINGS RISK
- EPS Estimate Dispersion: X%
- Historical Beat/Miss Rate: X%

MACRO SENSITIVITY
- Rate sensitivity: [High/Medium/Low]
- USD sensitivity: [High/Medium/Low]
- Commodity exposure: [High/Medium/Low]

OVERALL RISK RATING: 🔴 High / 🟡 Medium / 🟢 Low
```
