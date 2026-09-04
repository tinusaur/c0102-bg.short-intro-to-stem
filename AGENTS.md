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

## Content images

Use the **same art and files** as `c0012-en.short-intro-to-stem`. Do not invent a separate Bulgarian visual style. When replacing a topic image here, copy the matching JPG from the English tree (same lesson/media filename).

- Topic illustrations: **1920×960** (2:1) JPG. Markdown: `![descriptive alt](media/filename.jpg)`.
- **Do not touch** `media/course-cover.jpg`, `media/course-badge.jpg`, or `media/course-hero.jpg` unless explicitly asked.
- Leave the older **1376×768** photos in place unless asked to replace them. Style references live in the EN tree (same relative paths).
- Full style and the copy-paste generation prompt: **`c0012-en.short-intro-to-stem/AGENTS.md`** (Content images). Handbook art follows that same look in `c0022-bg.short-intro-to-stem`.

## Validation

```bash
bash tools/validate.sh /path/to/c0012-bg.short-intro-to-stem
```
