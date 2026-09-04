# AGENTS.md

Guidance for AI agents working in this repository.

## What this repo is

- **`c0012-bg.short-intro-to-stem`** — sample **learner** course **Кратък увод в STEM** (`C0012`), Bulgarian edition of `c0012-en.short-intro-to-stem`.
- **Course:** `C0012`. Language: **BG**.
- Learner tracks **`V11`** (начинаещи читатели) and **`V12`** (по-млади читатели). The matching handbook is **`c0022-bg.short-intro-to-stem`** (`C0022`).

## Canonical spec

Authoritative layout rules: **`../../tcams/tcams-docs-shared`** (**STRUCTURE.md** wins on conflict).

## Reader-facing text

Bodies are **Bulgarian**. Do not expose filesystem ids or `Vxy` codes in learner-facing prose. Keep **STEM** as STEM. Name groups in plain words (начинаещи читатели, по-млади читатели).

## Validation

```bash
bash tools/validate.sh /path/to/c0012-bg.short-intro-to-stem
```
