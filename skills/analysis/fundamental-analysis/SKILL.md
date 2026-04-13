---
name: fundamental-analysis
description: Evaluate a company's intrinsic value, financial strength, profitability, balance-sheet quality, competitive position, risk profile, and long-term growth potential using a structured fundamental-analysis workflow. Use when an agent needs to analyze a public company, read annual or quarterly reports, interpret income statement, balance sheet, or cash flow data, compare value versus growth characteristics, assess PER, PBR, ROE, debt, or liquidity metrics, or produce an investment memo grounded in business fundamentals rather than price action alone.
---

# Fundamental Analysis

## Overview

Use this skill to turn raw company information into a disciplined, long-term investment view. Prioritize intrinsic value, business quality, financial durability, risk, and future growth over short-term market noise.

## Quick Start

- Define the company, ticker, market, reporting currency, and time horizon before interpreting any metric.
- Start with the business model and reporting context, then move to financial statements, ratios, risk, and valuation.
- Read `references/fundamental-analysis-reference.md` when you need definitions, formulas, interpretation rules, or common red flags.
- Read `references/investment-memo-template.md` when the user wants a memo, investment thesis, or company brief.

## Core Workflow

### 1. Frame the task

- Identify whether the user wants a quick screen, a full memo, a valuation view, a quality review, or a risk review.
- State the analysis horizon clearly. Prefer long-term framing unless the user explicitly asks for a short-term view.
- Prefer the latest annual report plus recent quarterly data when available.

### 2. Understand the business first

- Summarize how the company makes money, its main segments, and the assumptions that must hold for the thesis to work.
- Identify industry structure, competitive position, demand drivers, and obvious constraints.
- Avoid ratio-first analysis with no business context.

### 3. Analyze the three financial statements

- Use the income statement to evaluate revenue growth, margin profile, earnings stability, and unusual one-off items.
- Use the balance sheet to evaluate asset quality, leverage, liquidity, and capital structure.
- Use the cash flow statement to confirm whether accounting profits convert into cash.
- Treat mismatches between earnings and cash generation as a major warning sign.

### 4. Evaluate core fundamental metrics

- Review PER, PBR, ROE, debt-related measures, and liquidity ratios.
- Compare each metric against the company's own history, close peers, and sector norms rather than using a single absolute cutoff.
- Treat a low multiple as a starting point for investigation, not as proof of undervaluation.

### 5. Assess management, risk, and growth

- Evaluate management quality through capital allocation, execution discipline, governance signals, and strategic clarity.
- Identify balance-sheet risk, regulatory exposure, cyclicality, concentration risk, technological disruption, and refinancing pressure.
- Assess future growth using realistic drivers such as reinvestment, product expansion, market share gains, R&D, or geographic expansion.

### 6. Form a valuation stance

- Decide whether the company appears undervalued, fairly valued, or overvalued relative to its fundamentals.
- Distinguish value characteristics from growth characteristics instead of forcing a false binary when the business shows both.
- State which assumptions support the conclusion and what evidence would change it.

## Output Requirements

- Produce a conclusion with these elements: business summary, financial statement review, metric interpretation, risk list, growth outlook, and valuation stance.
- Separate observed facts from inference.
- State data gaps and uncertainty explicitly.
- Prefer plain language over unexplained jargon.

## Guardrails

- Do not treat low PER or low PBR as automatically attractive. Weak businesses can look statistically cheap.
- Do not treat high ROE as automatically strong. Leverage can inflate it.
- Do not ignore the cash flow statement when reported earnings look strong.
- Do not rely on a single quarter unless the user explicitly asks for a near-term update.
- Note that fundamental analysis is most useful for medium- and long-term judgment and can miss sudden regime changes.
