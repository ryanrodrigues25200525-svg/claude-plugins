# /growth-nowcast COUNTRY

Estimate current economic growth before official GDP releases.

## Tools
- openbb-mcp — PMI, retail sales, industrial production, employment, freight data
- eurostat-mcp — EU nowcast data

## Nowcast Inputs (GDP proxies)
- ISM/PMI surveys (leading)
- Retail sales (consumer)
- Industrial production (manufacturing)
- Employment (labor market health)
- Freight/shipping volumes (real economy activity)
- Bank lending (credit creation)

## Output Format
```
COUNTRY Growth Nowcast
[Checked: timestamp]

GDP NOWCAST: X% annualised (Q[X] YYYY)
vs Last official print: X% | Consensus forecast: X%
Trend: Accelerating / Decelerating / Stable

COMPONENT BREAKDOWN
| Component | Reading | Contribution | Signal |
|-----------|---------|-------------|--------|
| Manufacturing PMI | | | |
| Services PMI | | | |
| Retail Sales | | | |
| Industrial Prod | | | |
| Employment | | | |

NOWCAST vs OFFICIAL ESTIMATE GAP
[How far above/below official forecasts our nowcast sits and why]

RISK TO NOWCAST
- Upside: [What could make growth stronger]
- Downside: [What could disappoint]

IMPLICATIONS
[For monetary policy, asset allocation, sector positioning]
```
