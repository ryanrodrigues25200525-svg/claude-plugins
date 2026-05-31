# /credit-spreads

Analyze corporate bond spreads and stress levels.

## Tools
- openbb-mcp — fixedincome_spreads_tcm, fixedincome_corporate_hqm, fixedincome_bond_indices

## Key Indices
- CDX IG: Investment grade CDS index
- CDX HY: High yield CDS index
- BAMLC0A0CM: IG option-adjusted spread (FRED)
- BAMLH0A0HYM2: HY option-adjusted spread (FRED)

## Output Format
```
Credit Spreads Dashboard
[Checked: timestamp]

INVESTMENT GRADE
- IG Spread: Xbps | 1Y range: X-Xbps
- vs historical avg: [Tight/Wide/Normal]
- Trend: Tightening / Widening

HIGH YIELD
- HY Spread: Xbps | 1Y range: X-Xbps
- vs historical avg: [Tight/Wide/Normal]
- Trend: Tightening / Widening

HY-IG SPREAD (risk premium)
- Current: Xbps | Trend: Compressing/Expanding

STRESS SIGNAL
🟢 Benign (<300bps HY) / 🟡 Elevated (300-500bps) / 🔴 Stressed (>500bps)

IMPLICATION FOR EQUITIES
[Tight spreads = risk-on supportive / Wide spreads = equity headwind]

SECTORS UNDER CREDIT STRESS
[Any sectors with notably wider spreads]
```
