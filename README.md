# Vibe Investing

Structured repository for finance and investing skills.

It is not just vibe coding anymore. It is vibe investing.

Harness engineering is not only for vibe coding. It matters for vibe investing too.

This repository is a focused collection of investing skills that follow the `SKILL.md`-based skill spec. The goal is to make analytical workflows, reporting patterns, and reusable investing playbooks composable, portable, and easy to evolve.

## Purpose

- Keep investing skills in one consistent repository
- Organize skills by reusable capability rather than ad hoc folders
- Stay aligned to the generic skill spec instead of a single host runtime
- Separate lightweight workflow guidance from deeper references and reusable assets

## Repository Structure

```text
vibe-investing/
├── README.md
├── AGENTS.md
├── .gitignore
└── skills/
    ├── AGENTS.md
    ├── analysis/
    ├── output-formats/
    ├── portfolio/
    └── research-ops/
```

## Skill Categories

- `analysis`: cross-asset analytical capabilities such as fundamental, valuation, and risk analysis
- `output-formats`: reusable output styles and packaging patterns for investing work
- `portfolio`: allocation, sizing, rebalancing, risk budgeting
- `research-ops`: filings, transcripts, peer comps, memo pipelines

## Current Status

- First active skill: `skills/analysis/fundamental-analysis`
- Folder-level maintenance rules live in `AGENTS.md` files

## Add a Skill

Create a new skill as a self-contained folder under the right category:

```text
skills/<category>/<skill-name>/
├── SKILL.md
├── references/   # optional
├── scripts/      # optional
└── assets/       # optional
```

The only required file is `SKILL.md`.

For final artifact generation, use this repo for output style and apply external file-format skills as needed:

- this repository owns report structure and publishable packaging
- external skills can convert the result into `docx`, `pdf`, `xlsx`, or other file types

## Skill Design Principles

- Keep `SKILL.md` short and action-oriented
- Put detailed formulas, heuristics, and templates in `references/`
- Add `scripts/` only when deterministic repeated work is worth automating
- Use lowercase hyphen-case for skill names
- Use `AGENTS.md` for folder-level maintenance instructions, not extra `README.md` files
- Prefer external skills for concrete file conversion when a generic tool already exists
- Keep the core repository aligned with the generic skill spec rather than any single runtime

## Recommended Next Skills

1. `analysis/valuation-analysis`
2. `output-formats/financial-report`
3. `research-ops/peer-comparison`
4. `portfolio/portfolio-construction`
5. `research-ops/earnings-call-digest`

## Git

This repository is initialized as a git repository on the `main` branch. No commit has been created yet.
