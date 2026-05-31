---
name: alpha-paper
description: /alpha-paper TOPIC
---

# /alpha-paper TOPIC

Search academic literature and convert findings into actionable investment ideas.

## Tools
- paper-search-mcp — arXiv, SSRN, academic finance journals

## Execution
1. Search paper-search-mcp for papers on TOPIC (finance/quant/economics)
2. Focus on: empirical findings, factor research, market anomalies
3. Extract: key finding, sample period, statistical significance, decay rate
4. Translate into implementable investment idea

## Output Format
```
Alpha Paper Research — TOPIC
[Checked: timestamp]

PAPERS FOUND
| Title | Authors | Year | Journal | Key Finding |
|-------|---------|------|---------|-------------|

TOP FINDING
Paper: [Title]
Finding: [What the paper shows in plain English]
Sample: [Time period, markets covered]
Significance: [t-stat, Sharpe, or return premium]
Decay risk: [Has this alpha decayed since publication?]

IMPLEMENTATION
- Long: [What to buy]
- Short: [What to sell, if applicable]
- Rebalancing: [Frequency]
- Estimated capacity: [How much $ before alpha erodes]
- Transaction costs: [Likely impact]

VERDICT: Implementable / Interesting but complex / Likely arbed away
```
