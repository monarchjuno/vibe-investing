# Repository Agents Guide

This file defines maintenance rules for the whole repository.

## Scope

- Apply these rules to all files and folders unless a deeper `AGENTS.md` overrides them.

## Repository Purpose

- Use this repository to manage finance and investing skills.
- Keep each skill reusable, modular, and easy to evolve over time.

## Structure Rules

- Keep user-facing project overview in the root `README.md` only.
- Use `AGENTS.md` files for folder-level maintenance instructions.
- Keep skill-specific operational guidance inside each skill's `SKILL.md`.
- Prefer capability-first categories over asset-class-first categories when one skill should span equities, crypto, credit, commodities, or other assets.
- Keep this repository focused on investing logic and reusable output styles rather than every possible file-conversion workflow.
- Keep the repository aligned with the generic skill spec instead of assuming a single host product.

## Naming Rules

- Use lowercase hyphen-case for skill folder names.
- Use category folders under `skills/` to group shared capabilities.

## Editing Rules

- Prefer small, targeted updates over broad rewrites.
- Do not add extra documentation files like nested `README.md` files unless explicitly requested.
- Keep reference material inside `references/` and use skill-local `scripts/` only when they provide real leverage.
- When final delivery must be `docx`, `pdf`, `xlsx`, or another concrete file type, prefer applying a specialized external skill directly unless repo-specific behavior is required.
- Remove placeholder files and speculative sample skills unless they serve an immediate purpose.
