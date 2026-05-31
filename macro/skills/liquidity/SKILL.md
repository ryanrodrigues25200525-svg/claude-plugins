---
name: liquidity
description: /liquidity
---

# /liquidity

Track global liquidity conditions.

## Tools
- openbb-mcp — Fed balance sheet (WALCL), M2, financial conditions, reserve balances

## Key Series (FRED via openbb)
- WALCL: Fed balance sheet total assets
- M2SL: M2 money supply
- RRPONTSYD: Overnight reverse repo (drains liquidity)
- WRESBAL: Reserve balances at Fed
- NFCI: Chicago Fed National Financial Conditions Index

## Output Format
```
Global Liquidity Dashboard
[Checked: timestamp]

FED BALANCE SHEET
- Total assets: $XTn | Change (3M): $X
- QT pace: $X/month
- Trend: Expanding / Contracting

MONEY SUPPLY
- M2: $XTn | YoY: X%
- Real M2 growth: X%
- Historical signal: [Positive/Negative for risk assets]

BANK RESERVES
- Reserve balances: $XTn
- Overnight RRP: $XTn (money parked at Fed)
- Net liquidity: $XTn

FINANCIAL CONDITIONS
- NFCI: X [Tight <0 / Loose >0]
- Trend: Tightening / Easing

GLOBAL CONTEXT
- ECB balance sheet trend: [Expanding/Contracting]
- BOJ policy: [Easing/Tightening]
- Combined G4 CB balance sheet: $XTn

LIQUIDITY VERDICT
🟢 Abundant | 🟡 Neutral | 🔴 Tight
IMPLICATION: [For risk assets, rates, credit]
```
