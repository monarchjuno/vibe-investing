# Data Access Category Guide

## Scope

- Apply these rules to `skills/data-access/` and its descendants unless a deeper file overrides them.

## Purpose

- Store skills for retrieving, validating, and preparing financial, market, economic, and alternative data for investing workflows.

## Structure

- Prefer flat skill folders directly under `skills/data-access/`.
- Keep provider-specific implementation guidance inside the relevant skill folder.
- Handle asset-class differences inside each skill when the same provider covers multiple asset classes.

## Rules

- Separate data retrieval from investment interpretation.
- Preserve source, provider, timestamp, query parameters, and coverage limits with the returned data.
- Prefer structured API clients, SDKs, and documented provider interfaces over scraping or ad hoc parsing.
- State when data requires paid credentials, may be delayed, or cannot be verified from the available source.
- Do not fabricate missing fields; return explicit nulls, errors, or uncertainty notes instead.
