# Shellfish Bar

Website for Shellfish Bar, built with the Summit framework.

The stack is chosen in the Decisions stage. Until then this repo holds the
client's public facts (`site/entity.json`, `site/brand.json`) and deploys an
intake preview from them on every push to `main`.

## Commands

```bash
npm install --global github:ryankolean/summit-components#cli-v0.1.0
summit preview . --out _preview       # build the intake preview
summit verify-split .                 # prove no private intake is committed
summit check gate _preview --mode preview
```
