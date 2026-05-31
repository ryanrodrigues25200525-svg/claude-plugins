# Gold Strategy

Workflow for developing, testing, and evaluating XAU/USD trading strategies.

## Data Paths
- **Strategies:** `~/Documents/gold_strategies/` (12 strategy files: 01_ema_crossover.py through 12_liquidity_sweep_optimize.py)
- **XAU intraday data:** `~/Documents/datasets/XAU Data/`

## Tools Available
- `backtesting.py` 0.6.5
- `vectorbt` 1.0.0
- `zipline-reloaded` 3.1.1
- `yfinance` (live data)
- Python 3.13 global

## Session Workflow

### Step 1: Orient
- Read existing strategy files in `~/Documents/gold_strategies/` to understand current state
- Ask: new strategy, optimize existing, or compare strategies?

### Step 2: Data
- Use XAU intraday data from `~/Documents/datasets/XAU Data/` for backtests
- Use `yfinance` for recent/live data only
- For macro context (DXY, yields, Fed): use openbb-mcp (FRED series)

### Step 3: Build/Test
- Prefer `backtesting.py` for single-strategy development (simpler, faster iteration)
- Use `vectorbt` for parameter sweeps and portfolio-level analysis
- Always report: Sharpe ratio, max drawdown, win rate, total return, number of trades

### Step 4: Save Results
- Save new/modified strategies to `~/Documents/gold_strategies/` with next number prefix
- Save backtest results summary to `~/Documents/Obsidian Vault/Finance & Investing/gold_strategies/` via python3

## Standards
- Walk-forward validation, not just in-sample backtest
- Always test on out-of-sample period before reporting results
- State assumptions explicitly: commission, slippage, data frequency
- If result looks too good, say so and explain why (overfitting check)
