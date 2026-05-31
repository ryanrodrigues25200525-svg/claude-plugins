# /vol-crush-opportunities

Find stocks likely to experience post-event volatility collapses.

## Tools
- openbb-mcp — derivatives_options_chains, equity_calendar_earnings

## Vol Crush Logic
After binary events (earnings, FDA decisions, FOMC), IV collapses regardless of direction.
Best strategy: sell premium (straddles/strangles) before the event.

## Output Format
```
Vol Crush Opportunities
[Checked: timestamp]

UPCOMING BINARY EVENTS (next 2 weeks)
| Ticker | Event | Date | Current IV | Historical Post-Event IV Drop | Setup |
|--------|-------|------|------------|-------------------------------|-------|

BEST VOL CRUSH SETUPS
| Ticker | IV Rank | Event | Expected crush % | Suggested structure |
|--------|---------|-------|-----------------|---------------------|

ELEVATED IV STOCKS (no upcoming catalyst — vol may compress naturally)
| Ticker | IV | IV Rank | Days elevated | Potential mean reversion |

STRUCTURES TO CONSIDER
- Short straddle: Sell ATM call + put (profit if stock stays flat)
- Short strangle: Sell OTM call + put (wider range, less premium)
- Iron condor: Limited risk version of short strangle

RISK NOTE: Always define risk. Short vol into earnings can have unlimited loss.
```
