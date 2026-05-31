---
name: backtest-idea
description: /backtest-idea STRATEGY
---

# /backtest-idea STRATEGY

Convert a discretionary investment idea into a systematic strategy ready for testing.

## Tools
- paper-search-mcp — find academic backing for the strategy logic

## Execution
1. Clarify the strategy idea in plain English
2. Search for academic evidence supporting the mechanism
3. Define precise rules: entry, exit, filters, universe
4. Write Python pseudocode/framework for backtesting
5. Flag assumptions and potential data mining concerns

## Output Format
```
Strategy Specification — STRATEGY
[Checked: timestamp]

STRATEGY LOGIC
[Plain English description of what the strategy does and why it should work]

ACADEMIC BACKING
[Papers supporting the mechanism — or flag if none found]

PRECISE RULES
Universe: [What stocks/assets to trade]
Entry signal: [Exact definition]
Exit signal: [Exact definition]
Filters: [Additional conditions]
Rebalancing: [Frequency]
Position sizing: [Equal weight / Vol-adjusted / etc.]

PYTHON FRAMEWORK
```python
# Pseudocode for backtesting
# Data: yfinance / edgartools / openbb
# Library: backtesting.py or vectorbt

[Code outline]
```

ASSUMPTIONS TO TEST
- [What needs to be true for this to work]

DATA MINING RISKS
- [What could make backtest results misleading]

RECOMMENDED BACKTEST PERIOD
- In-sample: [Dates]
- Out-of-sample validation: [Dates]
```
