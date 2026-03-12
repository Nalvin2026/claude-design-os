# Claude Design OS

## What this is
A single-page reference guide and practical operating system for digital product designers using Claude across every stage of the design process — from idea to shipped prototype.

## Design goals
- Feel like a considered design artefact, not a dev doc — warm, typographic, and on-brand
- Scannable and section-linked so designers can jump to what they need fast
- Teach through real examples: actual prompts, real git commands, a worked end-to-end project

## Tech constraints
- Single HTML file — no dependencies, no build step, no framework
- Vanilla CSS/JS only
- All design tokens defined as CSS custom properties inside `<style>` in `index.html`
- Fonts loaded from Google Fonts (DM Serif Display, DM Mono, DM Sans)

## Current status
Working on: UI polish and responsive refinements on `experiment/design` branch.

## File guide
- `index.html` — the entire site: markup, styles, and scripts in one file
- `.gitignore` — excludes OS files, editor folders, and node_modules

## Sections
| # | Section | What it covers |
|---|---------|---------------|
| 01 | Workflow | Stage-by-stage table: what Claude does vs. what you do |
| 02 | Vibe Coding | The CRAFT prompt framework and prompt card examples |
| 03 | Project Structure | Recommended folder layout and README template |
| 04 | Version Control | Git basics, branching strategy, commit message conventions |
| 05 | Sharing Prototypes | GitHub Pages setup and hosting options compared |
| 06 | Design Outputs | What Claude can produce: prototypes, decks, specs |
| 07 | Tool Stack | Recommended tools at each stage |
| 08 | Real-World Example | Full worked walkthrough: micro-journaling app concept to v1 |
