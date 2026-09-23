# gator-product

This repository is **product briefs** for the Gator team. It is not an app. It is not a notes dump.

## Write here

- `product/` — one markdown file per durable topic (quote flow, who it is for, pricing). Rewrite the file when the product changes. Do not add dated drafts or near-duplicates; update the existing brief.
- `decisions/` — when the user states a choice and a reason, add `decisions/YYYY-MM-DD-short-slug.md`. Keep it short: decision, why, date. Do not copy the whole brief into the decision file.

## Do not

- Add a docs site, package.json, app code, or prototypes.
- Create a `notes/` folder. Working notes belong in a different repo.
- Invent product decisions. If the user did not say it, ask.
- Move or rewrite engineering specs from other repos.

## Voice

Plain sentences. Present tense for what the product is. No marketing filler. Match existing briefs in `product/` when you add a new one.

## Git

Commit and push to `main` when the user asks to save. Do not open a pull request unless they ask.
