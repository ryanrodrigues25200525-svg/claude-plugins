---
name: 8k-alerts
description: /8k-alerts
---

# /8k-alerts

Monitor important 8-K filings across the market.

## Tools
- edgartools — 8-K filings, material event disclosures

## Execution
1. Pull recent 8-K filings from edgartools
2. Classify by event type
3. Flag material events likely to move stock price
4. Filter out routine/immaterial filings

## Event Types to Flag
- Management changes (CEO/CFO departures)
- Acquisitions and divestitures
- Debt financing, equity raises, credit facilities
- Buyback authorizations
- Regulatory actions, FDA decisions
- Material contracts won or lost
- Bankruptcy filings, going concern

## Output Format
```
8-K Alerts — Material Events
[Checked: timestamp]

HIGH IMPACT
| Ticker | Event Type | Summary | Likely Impact |
|--------|------------|---------|---------------|

MEDIUM IMPACT
| Ticker | Event Type | Summary |

MANAGEMENT CHANGES
| Ticker | Role | Change | Context |

M&A ACTIVITY
| Acquirer | Target | Deal Size | Structure |
```
