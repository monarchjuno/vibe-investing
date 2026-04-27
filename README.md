# Vibe Investing

Open-source repository of finance and investing skills built around the `SKILL.md` format.

This project collects reusable investing workflows instead of one-off prompts. The goal is to make research frameworks, market-analysis lenses, portfolio logic, and report formats easier to reuse, compare, and extend.

## What This Repository Contains

- Fundamental-analysis skills for bottom-up business and valuation work
- Data-access skills for retrieving, validating, and preparing financial data
- Market-analysis skills for regime, liquidity, and macro context
- Quantitative-research skills for signal design and validation
- Output-format skills for packaging research into publishable deliverables
- Investor-persona skills that apply the decision framework of well-known investors

## Current Skill Set

### Core Analysis

- `skills/fundamental-analysis/company-analysis`
- `skills/data-access/openbb-data-fetcher`
- `skills/market-analysis/traditional-market-analysis`
- `skills/quantitative-analysis/quant-research`
- `skills/output-formats/financial-report`

### Investor Personas

- `skills/investor-personas/aswath-damodaran`
- `skills/investor-personas/ben-graham`
- `skills/investor-personas/bill-ackman`
- `skills/investor-personas/cathie-wood`
- `skills/investor-personas/charlie-munger`
- `skills/investor-personas/michael-burry`
- `skills/investor-personas/mohnish-pabrai`
- `skills/investor-personas/nassim-taleb`
- `skills/investor-personas/peter-lynch`
- `skills/investor-personas/phil-fisher`
- `skills/investor-personas/rakesh-jhunjhunwala`
- `skills/investor-personas/stanley-druckenmiller`
- `skills/investor-personas/warren-buffett`

## Repository Layout

```text
vibe-investing/
├── README.md
├── AGENTS.md
└── skills/
    ├── AGENTS.md
    ├── data-access/
    ├── fundamental-analysis/
    ├── investor-personas/
    ├── market-analysis/
    ├── output-formats/
    ├── portfolio/
    └── quantitative-analysis/
```

Each skill lives in its own folder:

```text
skills/<category>/<skill-name>/
├── SKILL.md
├── references/   # optional
├── scripts/      # optional
└── assets/       # optional
```

`SKILL.md` is the only required file.

## Design Principles

- Organize skills by reusable capability, not by ad hoc project folders
- Keep each skill modular, portable, and easy to evolve
- Keep `SKILL.md` concise and workflow-driven
- Move detailed formulas, templates, and long guidance into `references/` when needed
- Add `scripts/` only when deterministic repeated work is worth automating
- Use lowercase hyphen-case for skill names
- Use `AGENTS.md` for folder-level maintenance rules instead of extra documentation files

## Using This Repository

This repository is designed for any system or workflow that can consume `SKILL.md`-style skill folders.

Typical usage:

1. Choose the category that matches the task.
2. Open the relevant `SKILL.md`.
3. Load any `references/`, `scripts/`, or `assets/` only when needed.
4. Apply the workflow to the investment question, research task, or report-generation job.

## Contributing

Contributions are welcome if they improve the repository as reusable open-source infrastructure for investing workflows.

When adding or updating a skill:

- Put it under the most appropriate top-level category in `skills/`
- Keep the structure shallow
- Prefer small, targeted additions over broad speculative scaffolding
- Avoid adding extra nested `README.md` files
- Keep skill instructions generic rather than tied to a single host product
- Follow any relevant `AGENTS.md` guidance in the directory you are editing

## References

- [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund): reference source for the investor persona skill adaptation work under `skills/investor-personas/`
- `skills/fundamental-analysis/company-analysis`: built around Aswath Damodaran style valuation logic, including narrative-first analysis, market-implied expectations, Reverse DCF before Forward DCF, FCFF-based intrinsic valuation, reinvestment and margin decomposition, and industry-reality checks.
- `skills/quantitative-analysis/quant-research`: built from the Fama-French / Kenneth French factor framework, AQR-style factor investing and factor momentum research, Andrew Lo's Adaptive Markets view, David Bailey and Marcos Lopez de Prado's backtest-overfitting defense framework, CMT and John Bollinger style rule-based technical analysis, and performance attribution / risk decomposition thinking.
- `skills/market-analysis/traditional-market-analysis`: built from Howard Marks style cycle awareness, pendulum psychology, second-level thinking, and risk asymmetry; Michael Mauboussin style expectations investing, base rates, moat durability, capital allocation, and probability-weighted judgment; Stanley Druckenmiller style macro regime detection, liquidity-first interpretation, adaptive view changes, and decisive positioning; and George Soros style reflexivity and self-reinforcing market narrative analysis.
