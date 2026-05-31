# /concentration-risk

Identify excessive position, sector, or factor concentration.

## Tools
- openbb-mcp — equity data for sector and correlation analysis

## Output Format
```
Concentration Risk Analysis — [Tickers/Portfolio]
[Checked: timestamp]

POSITION CONCENTRATION
- Largest position: X% — [Ticker]
- Top 3 positions: X% of portfolio
- HHI (Herfindahl Index): X [Higher = more concentrated]
- Threshold breach: [>10% single name / >25% top 3]

SECTOR CONCENTRATION
| Sector | Weight | vs SPX weight | Overweight |
|--------|--------|---------------|------------|
[Flag any sector >25% of portfolio]

CORRELATION RISK
- Portfolio average pairwise correlation: X.XX
- Highest correlation cluster: [Tickers that move together]
- True diversification: X names (effective diversification accounting for correlation)

FACTOR CONCENTRATION
- Dominant factor: [Factor] at Xx exposure
- Risk: [What happens if this factor underperforms]

GEOGRAPHIC CONCENTRATION
- US: X% | International: X% | EM: X%

RISK FLAGS 🔴
- [Any concentration exceeding risk thresholds]

RECOMMENDED ACTIONS
- Trim: [Oversized positions]
- Add: [Sectors/factors for balance]
- Replace: [Correlated positions with uncorrelated alternatives]
```
