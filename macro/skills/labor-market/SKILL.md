# /labor-market COUNTRY

Full labor market analysis.

## Tools
- openbb-mcp — economy_unemployment, BLS data via economy_survey_nonfarm_payrolls, FRED series
- eurostat-mcp — EU labor data

## Output Format
```
COUNTRY Labor Market Analysis
[Checked: timestamp]

HEADLINE NUMBERS
- Unemployment rate: X% | Trend: Improving/Worsening
- Participation rate: X% | Trend: Rising/Falling
- Employment-population ratio: X%

PAYROLLS / JOB CREATION
- Latest payrolls: +X,XXX | vs expected: ±X,XXX
- 3M average: +X,XXX
- Sector breakdown: [Where jobs are being added/lost]

WAGES
- Average hourly earnings YoY: X%
- Real wage growth (wages minus CPI): X%
- Wage trend: Accelerating/Decelerating

JOB OPENINGS & QUITS (US: JOLTS)
- Job openings: XM | Ratio to unemployed: X
- Quit rate: X% [High quits = worker confidence]
- Hiring rate: X%

INITIAL CLAIMS
- Latest: X,XXX | 4W avg: X,XXX
- Trend: Rising/Falling
- Signal: [Deteriorating/Stable/Improving]

LABOR MARKET HEALTH: 🟢 Strong / 🟡 Softening / 🔴 Weakening
FED IMPLICATION: [How labor data affects rate path]
```
