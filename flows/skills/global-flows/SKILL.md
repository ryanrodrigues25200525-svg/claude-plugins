# /global-flows

Track capital movement across equities, bonds, commodities, and currencies globally.

## Tools
- openbb-mcp — index performance, currency snapshots, commodity prices, fixed income

## Output Format
```
Global Capital Flows
[Checked: timestamp]

EQUITY FLOWS (regional performance as flow proxy)
| Region | 1W | 1M | YTD | Flow Signal |
|--------|----|----|-----|-------------|
| US | | | | |
| Europe | | | | |
| Japan | | | | |
| EM Asia | | | | |
| LatAm | | | | |
| China | | | | |

BOND FLOWS
- US Treasuries: [Inflow/Outflow signal from yield move]
- EM bonds: [Direction]
- IG Corporate: [Direction]
- HY: [Direction]

COMMODITY FLOWS
- Gold: $X [Safe haven buying/selling]
- Oil: $X [Risk sentiment]
- Copper: $X [Growth proxy]

FX FLOWS (USD strength = risk off)
- DXY: X | Direction: Strengthening/Weakening
- EM FX: [Broadly stronger/weaker]

OVERALL FLOW THEME: [Risk-on rotation / Defensive / De-risking / Neutral]
```
