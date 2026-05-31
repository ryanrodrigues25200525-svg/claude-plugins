# Quant Finance

Workflow for quantitative finance: factor models, portfolio construction, derivatives pricing, statistical analysis.

## Tools
- Python 3.13 global
- `numpy`, `pandas`, `scipy`, `statsmodels` — core quant stack
- `backtesting.py` 0.6.5 — strategy backtesting
- `vectorbt` 1.0.0 — parameter sweeps, portfolio-level analysis
- `yfinance` — market data
- `openbb-mcp` — macro factors, yield curves, options chains, CFTC positioning

## Domain Coverage

### Factor Models
- Fama-French 3/5-factor (HML, SMB, RMW, CMA)
- Momentum (UMD), quality, low-vol factors
- Factor exposure regression, attribution analysis
- Alpha/beta decomposition

### Portfolio Construction
- Mean-variance optimization (Markowitz)
- Risk parity, equal weight, minimum variance
- Black-Litterman with views
- Resampling/robust optimization
- Portfolio performance: Sharpe, Sortino, Calmar, max drawdown, VaR, CVaR

### Derivatives & Options
- Black-Scholes pricing, Greeks (delta, gamma, vega, theta, rho)
- Implied volatility surface (via openbb-mcp options chains)
- Put-call parity, skew analysis
- Simple hedging strategies

### Statistical Methods
- Time series: ADF stationarity, cointegration, ARIMA, GARCH
- Regression: OLS, WLS, rolling regression, panel data
- Correlation: Pearson, Spearman, DCC-GARCH dynamic correlation
- Hypothesis testing, bootstrap confidence intervals

## Standards
- Always annualize returns and volatility (252 trading days)
- State assumptions: rebalancing frequency, transaction costs, data frequency
- Walk-forward validation on any strategy result
- Flag data snooping / overfitting risks explicitly

## Wiki Integration
Save models/results to `~/Documents/Obsidian Vault/Finance & Investing/_wiki/pages/` via python3.
Tag pages: `quant, [factor-models | portfolio | derivatives | statistics]`

## Session Start
- What is the task: factor analysis, portfolio optimization, options analysis, statistical test?
- What data: provide tickers/assets or use existing datasets?
- Output: code, results summary, or wiki page?
