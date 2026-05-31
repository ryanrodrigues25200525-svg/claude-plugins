# Macro Economics

Workflow for macroeconomic analysis, monetary policy, and economic research.

## Data Tools (strict order)
1. **openbb-mcp** — FRED series, BLS, IMF, OECD, BIS, World Bank, economic calendars, CPI, PCE, GDP, unemployment, PMI, yield curves, central bank rates
2. **edgartools** — company-level economic exposure in filings (10-K risk factors, MD&A)
3. **agent-reach** — recent policy statements, speeches, academic papers, news post-August 2025

## Key Data Series (FRED via openbb-mcp)
- GDP: GDP, GDPC1 (real), GDPPOT (potential)
- Inflation: CPIAUCSL, CPILFESL (core), PCEPI, PCEPILFE (core PCE)
- Labor: UNRATE, PAYEMS, U6RATE, JOLTS, ICSA (claims)
- Rates: FEDFUNDS, DFF, SOFR, T10Y2Y (yield curve spread), T10YIE (breakeven)
- Money: M2SL, M2V (velocity), WALCL (Fed balance sheet)
- Credit: BAMLH0A0HYM2 (HY spreads), BAMLC0A0CM (IG spreads)

## Analysis Framework

### Macro Regime Identification
- Growth: above/below trend (GDP gap, PMI, leading indicators)
- Inflation: above/below target, trend direction
- Policy: tightening/easing/neutral, real rate level
- Credit: risk-on/risk-off (spreads, VIX, financial conditions)

### Standard Outputs
- **Situation summary:** current regime across 4 dimensions above
- **Key data table:** latest readings vs prior period vs consensus
- **Market implications:** what the regime means for equities, rates, FX, commodities
- **Risks:** upside and downside scenarios with probability assessment

## Wiki Integration
Save research to `~/Documents/Obsidian Vault/Finance & Investing/_wiki/pages/` via python3.
Tag pages: `economics, macro, [specific topic]`
Cross-link to related pages using [[Page Name]].

## Session Start
- What is the question: regime assessment, specific indicator deep-dive, policy analysis, or forecast?
- What time horizon: current snapshot, trend analysis, or forward-looking?
- What output: in-session summary, wiki page, or deck slide?
