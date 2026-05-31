# /portfolio-scenarios

Analyze portfolio across multiple future macro scenarios.

## Tools
- openbb-mcp — macro data and asset class correlations
- fed-speech-mcp — policy path scenarios

## Four Core Scenarios
1. **Soft landing**: Inflation falls, growth holds, Fed cuts gradually
2. **Hard landing**: Recession, Fed cuts aggressively, credit stress
3. **No landing**: Growth stays hot, inflation sticky, Fed stays higher for longer
4. **Stagflation**: Growth weak, inflation high, policy constrained

## Output Format
```
Portfolio Scenario Analysis — [Tickers]
[Checked: timestamp]

SCENARIO PROBABILITIES (our assessment)
- Soft landing: X%
- Hard landing: X%
- No landing: X%
- Stagflation: X%

PORTFOLIO PERFORMANCE BY SCENARIO
| Position | Soft Landing | Hard Landing | No Landing | Stagflation |
|----------|-------------|--------------|------------|-------------|

EXPECTED PORTFOLIO RETURN (probability-weighted): X%

BEST POSITIONED FOR: [Scenario]
MOST VULNERABLE TO: [Scenario]

PORTFOLIO GAPS
- Underweight scenario: [Which scenario the portfolio doesn't hedge]
- Recommended additions for balance: [Assets/sectors]

OPTIMAL SCENARIO PORTFOLIO
[What to own if you had to pick one scenario]
```
