# Search First

[![skills.sh](https://skills.sh/b/jimmyrogue/Search1st-skill)](https://www.skills.sh/jimmyrogue/search1st-skill/search-first)

An agent skill that researches mature, established solutions before writing custom code.

## Install

```bash
npx skills add jimmyrogue/Search1st-skill --skill search-first
```

Add `-g` to install it globally.

## What It Does

Before implementation, Search First:

1. Inspects the existing project for reusable code and dependencies.
2. Searches for native features, official scaffolds, maintained frameworks, and proven implementations.
3. Checks compatibility, maintenance, licensing, security, cost, and lock-in.
4. Recommends the best fit with sources and a clear reuse plan.
5. Implements only the product-specific gap.

Trivial edits and exact local changes skip unnecessary internet research.

See [SKILL.md](./SKILL.md) for the complete agent instructions.
