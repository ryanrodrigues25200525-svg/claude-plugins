# /market-is-wrong

Find consensus beliefs and identify data that challenges them.

## Tools
- google-news — consensus views
- fed-speech-mcp — policy narrative
- openbb-mcp — macro data, positioning
- edgartools — company-level data contradicting narrative

## Execution
1. Identify the 3 most entrenched market consensus views
2. For each: gather contradicting evidence from data
3. Assess probability that consensus is wrong
4. Identify the trade if consensus breaks

## Output Format
```
Market Is Wrong
[Checked: timestamp]

CONSENSUS VIEW #1: [Belief]
- Evidence FOR consensus: [Why most believe it]
- Evidence AGAINST: [Data contradicting it]
- Probability consensus is wrong: X%
- Trade if wrong: [How to position]

CONSENSUS VIEW #2: [Belief]
[Same structure]

CONSENSUS VIEW #3: [Belief]
[Same structure]

HIGHEST CONVICTION CONTRARIAN CALL
[The single best consensus-vs-reality trade right now]
Risk/Reward: [Assessment]
Catalyst for consensus to break: [What triggers the repricing]
```
