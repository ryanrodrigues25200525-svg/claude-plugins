# /sector-valuations

Compare sector valuations versus historical averages.

## Tools
- openbb-mcp — equity_fundamental_metrics by sector, etf_info

## Output Format
```
Sector Valuations
[Checked: timestamp]

SECTOR P/E COMPARISON
| Sector | Current P/E | 10Y Avg | Premium/Discount | Signal |
|--------|-------------|---------|-----------------|--------|
| Technology | | | | 🔴🟡🟢 |
| Financials | | | | |
| Healthcare | | | | |
| Energy | | | | |
| Industrials | | | | |
| Consumer Disc | | | | |
| Consumer Stap | | | | |
| Utilities | | | | |
| Materials | | | | |
| Comm Services | | | | |
| Real Estate | | | | |

CHEAPEST SECTORS (vs history)
1. [Sector]: Trading at Xx vs Xx historical avg (-X%)

MOST EXPENSIVE SECTORS (vs history)
1. [Sector]: Trading at Xx vs Xx historical avg (+X%)

VALUATION + GROWTH COMBINATION (PEG by sector)
| Sector | P/E | Growth | PEG | Value signal |

REBALANCING OPPORTUNITY
[Which rotation from expensive to cheap sectors makes sense now?]
```
