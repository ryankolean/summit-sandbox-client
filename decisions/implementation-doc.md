# Implementation plan: summit-sandbox-client

Generated from `decisions/site.config.json` by `summit decide docs`. One PR per entry, in this
order. Every PR passes `summit verify-split` and `summit check gate` on its preview before merge.

**Stack:** astro. **Host:** cloudflare-pages.

### PR 1: scaffold

Copy `templates/astro-site` from summit-components, point `@summit/*` at release tags (`scripts/use-tags.mjs`), keep `site/*.json`.

### PR 2: `/` `hero`

Add `hero@0.2.0`.

```json
{
  "eyebrow": "Traverse City, MI",
  "title": "Shellfish Bar",
  "lede": "An oyster bar and restaurant in Traverse City, Michigan.",
  "primaryCta": {
    "label": "Hours and location",
    "href": "#visit"
  }
}
```

## Unchanged existing elements

- none

## Replace later (not planned yet)

- none

