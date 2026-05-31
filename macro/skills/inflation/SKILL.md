---
name: inflation
description: /inflation COUNTRY
---

# /inflation COUNTRY

Deep inflation analysis — components, trends, outlook.

## Tools
- openbb-mcp — economy_cpi, economy_pce, FRED series
- eurostat-mcp — EU inflation data

## Execution
1. Pull headline and core CPI/PCE
2. Pull component breakdown (goods, services, shelter, energy, food)
3. Pull wage data
4. Assess trajectory and central bank implications

## Output Format
```
COUNTRY — Inflation Analysis
[Checked: timestamp]

HEADLINE NUMBERS
- CPI YoY: X% | MoM: X%
- Core CPI YoY: X% | MoM: X%
- PCE YoY: X% (US only) | Core PCE: X%

COMPONENTS
| Category | YoY | MoM | Trend |
|----------|-----|-----|-------|
| Shelter  |     |     |       |
| Services |     |     |       |
| Goods    |     |     |       |
| Energy   |     |     |       |
| Food     |     |     |       |

WAGE GROWTH
- Average hourly earnings YoY: X%
- Real wage growth: X% (wages minus inflation)

INFLATION DRIVERS
- [What is driving inflation up/down]

OUTLOOK
- 3-month trajectory: Rising/Falling/Stable
- Will inflation reach target by: [timeframe]
- Sticky components: [what won't come down quickly]

CENTRAL BANK IMPLICATION
- [How this print affects rate path]
```
