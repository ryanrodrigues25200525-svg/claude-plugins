# /activist-watch

Track activist investors across the market.

## Tools
- edgartools — 13D/G filings, Schedule 13D

## Execution
1. Search recent 13D and 13G filings via edgartools
2. Identify new activist campaigns (13D = active, 13G = passive >5%)
3. Pull activist's historical success rate where possible
4. Summarize stated thesis and demands

## Output Format
```
Activist Watch — Latest Campaigns
[Checked: timestamp]

NEW 13D FILINGS (Active Activism)
| Target | Activist | Stake % | Thesis/Demands | Filed |
|--------|----------|---------|----------------|-------|

NEW 13G FILINGS (Passive >5%)
| Target | Institution | Stake % | Filed |
|--------|-------------|---------|-------|

ONGOING CAMPAIGNS
- [Active situations with updates]

NOTABLE: [Most significant new campaign this period]
```
