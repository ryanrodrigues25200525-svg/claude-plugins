# ML Research

Workflow for reading, ingesting, and tracking AI/ML papers, benchmarks, and model developments.

## Data Tools
1. **paper-search-mcp** — search and download papers from arXiv, Semantic Scholar, PubMed, etc.
2. **agent-reach** — recent blog posts, model releases, benchmark leaderboards, community discussion
3. **hugging-face-*** skills — model cards, datasets, evaluation results

## Paper Workflow

### Ingest a Paper
1. Search or fetch paper via `mcp__paper-search-mcp__search_arxiv` or `read_arxiv_paper`
2. Extract: problem statement, method, key results, benchmarks, limitations
3. Situate: how does it relate to existing wiki pages? What does it contradict or extend?
4. Save structured page to wiki (see below)

### Paper Page Format (wiki)
```yaml
---
title: [Paper Title]
tags: [ml, ai, [specific: transformers | rl | diffusion | llm | agents | etc.]]
arxiv_id: XXXX.XXXXX
authors: [list]
published: YYYY-MM-DD
sources: [arxiv URL]
confidence: high
---
```
Sections: Summary, Method, Key Results, Benchmarks, Limitations, Related Work, My Notes

### Track Model Benchmarks
Maintain a wiki page `pages/benchmark-tracker.md` with:
- MMLU, HumanEval, MATH, GPQA, SWE-bench scores by model
- Updated each time a new model or paper is ingested
- Cross-linked to individual model/paper pages

## Domain Coverage
- **LLMs:** architecture, training, RLHF/DPO alignment, inference optimization, scaling laws
- **Agents:** tool use, planning, multi-agent systems, memory, evaluation
- **ML Engineering:** training infrastructure, quantization, distillation, fine-tuning
- **Applied ML:** recommendation systems, time series forecasting, tabular models
- **Theory:** optimization, generalization, interpretability

## Wiki Integration
All papers/notes → `~/Documents/Obsidian Vault/Finance & Investing/_wiki/pages/` via python3.
Use subdirectory naming in title: e.g. `LLM - Attention Is All You Need` for easy Obsidian grouping.
Update `benchmark-tracker.md` whenever a new model result is encountered.

## Session Start
- Ingest a specific paper: provide arXiv ID or title
- Track a new model release: provide model name
- Survey a topic: provide research question, I'll search and synthesize
- Update benchmarks: I'll pull latest leaderboard data via agent-reach
