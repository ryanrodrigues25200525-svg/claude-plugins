# Finance Deck

Workflow for building financial presentations, pitch decks, Excel models, and reports.

## Tool Stack (mandatory)
- **officecli** — ALL PPTX/XLSX/DOCX work. Never use python-pptx or openpyxl directly.
- **pitch-deck skill** — invoke at session start for deck work
- **quant-analyst skill** — invoke at session start for model/Excel work

## Design Standards (Anthropic IB style)

### PowerPoint
- Real table objects (not text boxes arranged as tables)
- Shape-based arrows (not text arrows like →)
- Font hierarchy: Title 24-28pt bold / Section headers 18-20pt / Body 12-14pt / Footnotes 9-10pt
- Dark background slides: use high-contrast text
- No decorative emojis in slides

### Excel
- Hardcoded inputs in blue font, formulas in black
- Assumptions section at top of each sheet
- Named ranges for key drivers
- No merged cells in data tables

## Session Start Checklist
- [ ] Deck or model (or both)?
- [ ] Invoke `pitch-deck` skill (decks) and/or `quant-analyst` skill (models)
- [ ] What company/asset/situation?
- [ ] What audience (internal, client, LP)?
- [ ] Any existing file to work from?

## Financial Data for Decks
- Pull comps/financials via edgartools (SEC) or openbb-mcp (live/estimates)
- Pull macro backdrop via openbb-mcp (FRED/EIA)
- Use agent-reach only for qualitative/narrative/recent news

## Output
- Save to path user specifies
- Use officecli `view` with screenshot for visual validation after each major section
- Final check: confirm fonts, alignment, no placeholder text remaining
