# /central-bank COUNTRY

Central bank policy analysis and rate outlook.

## Tools
- fed-speech-mcp — Fed (US)
- openbb-mcp — rate data, inflation, economy_interest_rates
- eurostat-mcp — ECB context
- google-news — latest central bank news

## Execution
1. Pull current policy rate and recent decisions
2. Pull inflation and growth data to assess policy pressure
3. Search for latest central bank communications
4. Build rate path outlook

## Output Format
```
COUNTRY Central Bank Analysis
[Checked: timestamp]

CURRENT STANCE
- Policy rate: X%
- Last decision: [Date, change]
- Stated bias: Hawkish / Neutral / Dovish

MANDATE STATUS
- Inflation: X% vs X% target → [On track/Above/Below]
- Employment/Growth: [Assessment]
- Financial stability: [Any concerns]

RATE PATH
- Market pricing next meeting: [Hike/Hold/Cut] X% probability
- 12-month market implied rate: X%
- Our assessment: [Agreement/Disagreement with market]

COMMUNICATION ANALYSIS
- [Key recent quotes from governor/committee]
- [Tone shift vs prior meetings]

RISKS
- Upside (more hikes/less cuts): [Triggers]
- Downside (cuts sooner): [Triggers]

TRADE IMPLICATION
- [Impact on currency, bonds, rates-sensitive equities]
```
