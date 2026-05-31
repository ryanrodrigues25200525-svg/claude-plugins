---
name: banking-stress
description: /banking-stress
---

# /banking-stress

Monitor indicators of financial system stress.

## Tools
- openbb-mcp — FRED stress indicators, bank CDS, EFFR/SOFR spreads

## Key Stress Indicators
- TED Spread (LIBOR-T-bill): systemic funding stress
- SOFR-OIS spread: bank funding stress
- FRA-OIS spread: forward funding stress
- Bank CDS spreads: individual bank stress
- Commercial bank reserves: liquidity buffer
- NFCI (Chicago Fed Financial Conditions): broad conditions

## Output Format
```
Banking Stress Monitor
[Checked: timestamp]

SYSTEMIC STRESS INDICATORS
| Indicator | Current | Stressed Level | Signal |
|-----------|---------|----------------|--------|
| SOFR-OIS spread | Xbps | >25bps | 🟢🟡🔴 |
| FRA-OIS | Xbps | >30bps | |
| NFCI | X | <-0.5 | |
| Bank reserves | $XTn | <$3Tn | |

BANK FUNDING CONDITIONS
- Fed discount window usage: $XBn [Elevated/Normal]
- BTFP/emergency facilities: [Active/Inactive]
- Interbank lending: [Functioning/Stressed]

REGIONAL BANK WATCH
- CRE exposure concerns: [Banks flagged]
- Deposit outflow risks: [Any notable situations]

OVERALL SYSTEM STRESS: 🟢 Low / 🟡 Moderate / 🔴 High
LAST STRESSED PERIOD: [Reference point for comparison]
```
