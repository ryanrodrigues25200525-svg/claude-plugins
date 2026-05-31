# /strategy-builder

Build a complete trading or investing strategy from scratch.

## Tools
- paper-search-mcp — academic strategy research
- openbb-mcp — market data for context

## Execution
1. Clarify objective: return target, risk tolerance, time horizon, asset class
2. Design strategy architecture
3. Define all rules precisely
4. Estimate realistic expectations

## Output Format
```
Strategy Blueprint
[Checked: timestamp]

OBJECTIVE
- Target return: X% pa
- Max drawdown tolerance: X%
- Time horizon: [Trade/Invest]
- Asset class: [Equities/Options/Macro/Multi-asset]

STRATEGY TYPE
[Trend following / Mean reversion / Factor / Event-driven / Macro / etc.]

EDGE HYPOTHESIS
[Why should this strategy make money? What market inefficiency does it exploit?]

RULES
1. Universe selection: [What to trade]
2. Signal generation: [How to identify opportunities]
3. Entry rules: [Precise entry criteria]
4. Position sizing: [How much to allocate]
5. Risk management: [Stop losses, max position, max drawdown rule]
6. Exit rules: [When to close]
7. Rebalancing: [How often to review]

EXPECTED CHARACTERISTICS
- Expected Sharpe: X
- Expected annual return: X%
- Expected max drawdown: X%
- Trade frequency: X trades/month

IMPLEMENTATION
- Data needed: [Sources]
- Tools: [backtesting.py / vectorbt]
- Complexity: Low/Medium/High

NEXT STEP: [What to backtest first]
```
