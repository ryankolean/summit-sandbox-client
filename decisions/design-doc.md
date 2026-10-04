# Design doc: summit-sandbox-client

## Decisions

- **Mode:** new site
- **Stack:** astro. Content site: static HTML by default, best crawlability, React only where needed.
- **Host:** cloudflare-pages. Default for new sites: _redirects, _headers, DNS, analytics and Turnstile in one account.
- **Live URL:** https://shellfish.example/
- **Security headers:** yes
- **Redirects:** 0

## Pages

| path | title | source | sections |
|---|---|---|---|
| `/` | Shellfish Bar | new | hero |

## Components

| component | version | used on |
|---|---|---|
| hero | 0.2.0 | / |

## Visual direction

- Palette: bg #E8E3CE, fg #2E241A, primary #2B2117, accent #D3A75A
- Type: Fraunces (display), Jost (body)
- Radius: 2px

_Designer: layout, imagery and motion direction, and the reasoning behind them._

