---
name: second-order-effects
description: /second-order-effects EVENT
---

# /second-order-effects EVENT

Analyze indirect market impacts of a major event.

## Tools
- openbb-mcp — sector and macro data
- fed-speech-mcp — policy implications
- google-news — market reaction and commentary

## Execution
1. Identify the direct, obvious impact of EVENT
2. Map second-order effects (what does the first effect cause?)
3. Map third-order effects where clear
4. Identify non-consensus implications
5. Find specific winners and losers beyond the obvious

## Output Format
```
Second-Order Effects — EVENT
[Checked: timestamp]

EVENT SUMMARY
[Brief description of what happened]

DIRECT EFFECTS (first order — already priced)
- [Obvious and immediate market impact]

SECOND-ORDER EFFECTS (where the opportunity is)
1. [Effect] → [Why] → [Asset class/sector impacted] → [Direction]
2. [Effect] → [Why] → [Asset class/sector impacted] → [Direction]
3. [Effect] → [Why] → [Asset class/sector impacted] → [Direction]

THIRD-ORDER EFFECTS (further out, less certain)
- [Longer chain of causation]

NON-CONSENSUS IMPLICATIONS
[What is the market missing or underpricing?]

SPECIFIC WINNERS
| Ticker/Asset | Why | Conviction |
|-------------|-----|------------|

SPECIFIC LOSERS
| Ticker/Asset | Why | Conviction |

TIMELINE
[When do second-order effects typically play out for this type of event?]
```
