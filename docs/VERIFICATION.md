# How FreeToken verifies an access claim

FreeToken separates discovery, official evidence, platform-operated testing, review, and publication so one weak signal cannot silently become a strong public claim.

## Evidence layers

1. **Official source** — provider documentation, pricing, model catalog, status page, or changelog.
2. **Normalized observation** — a bounded record of what materially changed.
3. **FreeToken-operated Canary** — a platform-owned test of the exact route when configured and appropriate.
4. **Second-pass review** — a separate model or deterministic policy checks the source, conditions, and test result.
5. **Public outcome** — publish a practical article, a concise evidence update, or nothing.

Community directories can suggest a provider or change, but they cannot independently establish a free-access claim.

## Status language

- **Official route checked** means the application or documentation path was reviewed.
- **Canary healthy** means the configured FreeToken-operated test recently passed.
- **Degraded, limited, or unavailable** describes the observed test state, not every user's account.
- **Not configured** means FreeToken has not run its Canary test for that route.

Each statement should carry enough date, source, condition, and uncertainty context for a developer to decide what to test next.

Live methodology: https://freetoken.link/about-verification
