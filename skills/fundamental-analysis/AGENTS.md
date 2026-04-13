# Fundamental Analysis Top-Level Guide

## Scope

- Apply these rules to `skills/fundamental-analysis/` and its descendants unless a deeper file overrides them.

## Purpose

- Store bottom-up valuation and fundamental-analysis skills in a shallow layout.

## Structure

- Prefer flat skill folders directly under `skills/fundamental-analysis/`.
- Example skill names include `company-analysis`, `crypto-analysis`, `credit-analysis`, and `special-situations`.
- Avoid adding extra intermediate folders unless the flat structure clearly breaks down.

## Rules

- Put shared framework logic in each skill's `SKILL.md` and `references/`.
- Put asset-specific variations inside the skill bundle when that is cleaner than more folder depth.
- Keep listed-company workflows expectations-first and Reverse-DCF-first when applicable.
