# Multilingual coverage and maintenance

Updated 2026-10-19. This supersedes the earlier English/Chinese-only launch plan.

## Current public entry points

| Language | Site | Repository introduction | MCP guide |
| --- | --- | --- | --- |
| English | https://freetoken.link/ | [README.md](../README.md) | https://freetoken.link/mcp-guide |
| 简体中文 | https://freetoken.link/zh | [README.zh-CN.md](../README.zh-CN.md) | https://freetoken.link/zh/mcp-guide |
| 日本語 | https://freetoken.link/ja | [README.ja.md](../README.ja.md) | https://freetoken.link/ja/mcp-guide |
| Español | https://freetoken.link/es | [README.es.md](../README.es.md) | https://freetoken.link/es/mcp-guide |
| 한국어 | https://freetoken.link/ko | [README.ko.md](../README.ko.md) | https://freetoken.link/ko/mcp-guide |

Localized public discovery and tool routes exist, including models, key guides,
Config, Doctor, Playground, Watchlist, pricing and status. This is not a claim
that every article, provider response, email or private workflow is translated.
The English Find-by-requirement route is labeled as English in introductions
where no equivalent localized route is linked.

## MCP language boundary

The six MCP tools currently return English explanatory prose. The `locale`
argument selects corresponding site links; it does not translate the tool
payload. All five human connection guides explain this limitation. See
[MCP.md](MCP.md).

## Maintenance rules

- Preserve brands, model IDs, protocols and technical identifiers.
- Keep free tiers, free credits and trials distinct. Preserve payment, account,
  region and quota conditions rather than simplifying them during translation.
- Match evidence dates to the source; a translation update does not verify a fact.
- Link to an existing same-language route where available. Otherwise label the
  fallback language explicitly instead of pretending a translation exists.
- Validate changed links and maintain README language-switch links together.
- Do not claim full locale parity, universal availability or automatic indexing.

The canonical product remains on `https://freetoken.link/`. Repository
translations do not create duplicate GitHub Pages sites, language subdomains,
or independent hreflang declarations.
