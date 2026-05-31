---
name: portfolio-stress-test
description: /portfolio-stress-test
---

# /portfolio-stress-test

Estimate portfolio behavior under macro shocks.

## Tools
- openbb-mcp — historical price data for correlation/beta analysis

## Scenarios to Run
1. **Rate shock**: +200bps rapid rate rise
2. **Recession**: -20% equity drawdown, credit widening
3. **Inflation surge**: CPI spikes, stagflation
4. **Dollar spike**: DXY +15% rapid appreciation
5. **Credit crisis**: HY spreads +400bps, IG +150bps
6. **China shock**: Hard landing, EM contagion
7. **Oil spike**: Crude +50% (supply shock)

## Output Format
```
Portfolio Stress Test — [Tickers/Weights]
[Checked: timestamp]

SCENARIO RESULTS
| Scenario | Portfolio Impact | Worst Position | Best Position |
|----------|-----------------|----------------|---------------|
| Rate shock +200bps | -X% | | |
| Recession -20% equity | -X% | | |
| Inflation surge | -X% | | |
| Dollar spike | -X% | | |
| Credit crisis | -X% | | |
| China hard landing | -X% | | |
| Oil spike | -X% | | |

WORST CASE (tail risk)
- Combined scenario (recession + credit stress): -X%
- Portfolio VaR (95%, 1M): -X%

MOST VULNERABLE POSITIONS
| Ticker | Scenario | Estimated Loss |

NATURAL HEDGES IN PORTFOLIO
| Position | Hedges against |

RECOMMENDED HEDGES
[What to add to reduce tail risk exposure]
```
