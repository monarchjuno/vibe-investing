# Output Formats Category Guide

## Scope

- Apply these rules to `skills/output-formats/` and its descendants unless a deeper file overrides them.

## Purpose

- Store skills that package investing content into reusable output styles.

## Include Here

- Securities-firm style reports
- Reusable memo or briefing structures
- Publishable output packaging patterns
- Chart-rich financial report layouts and exhibit packaging

## Ownership

- Own output structure, layout logic, title treatment, table placement, disclaimer handling, and publishable presentation patterns.
- Assume the core investing analysis already exists upstream.
- Produce a structured result that can later be handed to an external `docx`, `pdf`, or spreadsheet skill if a concrete file artifact is required.
- Cover chart selection and exhibit placement when that improves the report output.

## Rules

- Do not let file-extension concerns dominate the skill design.
- Keep output-style instructions reusable across many investing use cases.
- Make it easy for an agent to pass the result into an external formatting skill afterward.
