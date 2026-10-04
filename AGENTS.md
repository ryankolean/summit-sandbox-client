# AGENTS.md

- `site/entity.json` holds **public facts only**. Private intake (pain points,
  competitors, pricing, personal contacts) lives in the private Summit intake
  repo and never here. CI runs `summit verify-split` to enforce this.
- Branch and open a PR for every change; CI must pass before merging.
- Conventional commits, no emojis, no em dashes.
