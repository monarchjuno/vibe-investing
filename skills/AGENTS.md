# Skills Root Guide

## Scope

- Apply these rules to everything under `skills/` unless a deeper `AGENTS.md` overrides them.

## Purpose

- Use this directory as the source of truth for all investing skill packages.

## Rules

- Keep each direct child folder under `skills/` focused on a major investing capability such as `data-access`, `fundamental-analysis`, `market-analysis`, `quantitative-analysis`, `portfolio`, or `output-formats`.
- Keep the structure shallow: prefer `skills/<top-level-domain>/<skill-name>` over deeper category nesting.
- Keep every skill self-contained in its own folder.
- Each skill folder must include `SKILL.md`.
- Add `references/`, `scripts/`, and `assets/` only when needed.
- Handle asset-class differences inside each skill when possible instead of creating extra nesting layers too early.
- Treat `output-formats/` as reusable presentation styles or output packaging patterns, not necessarily literal file extensions.

## Quality Standard

- Keep `SKILL.md` concise and workflow-driven.
- Move long explanations, formulas, and templates into `references/`.
- Avoid duplicate guidance across multiple skills when it can be shared cleanly.
- Treat `output-formats/*` skills as owners of presentation schema and reusable publishing style.
- Avoid keeping placeholder or speculative skill folders with no concrete implementation plan.
