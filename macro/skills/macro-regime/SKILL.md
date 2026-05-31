---
name: macro-regime
description: /macro-regime COUNTRY
---

# /macro-regime COUNTRY

Identify the current macro regime and investment implications.

## Tools
- openbb-mcp — growth, inflation, credit, rates data
- eurostat-mcp — EU countries

## Regimes
- **Goldilocks**: Growth above trend, inflation falling → Risk-on
- **Reflation**: Growth accelerating, inflation rising → Commodities, value
- **Stagflation**: Growth below trend, inflation high → Cash, commodities, short duration
- **Recession**: Growth contracting, inflation falling → Defensives, long duration bonds
- **Slowdown**: Growth decelerating, inflation sticky → Defensive positioning

## Execution
1. Assess GDP growth: above/below trend, direction
2. Assess inflation: above/below target, direction
3. Assess credit conditions: spreads, lending standards
4. Classify regime and map to asset class implications

## Output Format
```
COUNTRY — Macro Regime Analysis
[Checked: timestamp]

REGIME: [Name]
Confidence: High / Medium / Low

EVIDENCE
- Growth: X% YoY, [above/below] trend, [accelerating/slowing]
- Inflation: X% YoY, [above/below] target, [rising/falling]
- Credit: Spreads [tight/wide], conditions [easing/tightening]
- Yield curve: [normal/inverted/flat]

REGIME HISTORY
- Time in current regime: ~X months
- Transition risk: [Signs of regime change]

ASSET CLASS PLAYBOOK
- Equities: [Overweight/Neutral/Underweight] — [sectors to favour]
- Bonds: [Duration preference]
- Commodities: [Bullish/Bearish]
- FX: [USD strength/weakness]
- Cash: [% allocation]
```
