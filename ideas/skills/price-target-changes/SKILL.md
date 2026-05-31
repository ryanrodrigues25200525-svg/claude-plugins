# /price-target-changes

Monitor major price target revisions and consensus expectations.

## Tools
- openbb-mcp — equity_estimates_price_target, equity_estimates_consensus

## Output Format
```
Price Target Changes
[Checked: timestamp]

LARGEST PT INCREASES
| Ticker | Old PT | New PT | % Change | Consensus PT | Current Price | Upside |
|--------|--------|--------|----------|--------------|---------------|--------|

LARGEST PT CUTS
| Ticker | Old PT | New PT | % Change | Consensus PT | Current Price | Upside |

CONSENSUS PT vs CURRENT PRICE (biggest disconnects)
| Ticker | Price | Consensus PT | Implied Upside | # Analysts |
|--------|-------|--------------|----------------|------------|

CONTRARIAN READS
- Stocks with widening consensus upside (market ignoring analysts): [Tickers]
- Stocks where price has run past consensus PT: [Tickers — potential sell]
```
