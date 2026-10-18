# FreeToken MCP: read-only API discovery for AI assistants

Published in the [Official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/link.freetoken%2Fcatalog/versions/1.0.0) as **`link.freetoken/catalog` v1.0.0**. Listing is not provider endorsement or a guarantee of availability.

## Connect

Add a remote MCP server in a client supporting **Streamable HTTP**:

```text
https://freetoken.link/mcp
```

No FreeToken login or API key is required. Use the client's remote-server setup, not a local stdio command. Client capabilities and settings differ; this is not a claim that every AI client has been tested. Opening the raw endpoint in a browser sends GET and returns **405** by design; use an MCP client, or read a human guide below.

[English](https://freetoken.link/mcp-guide) · [简体中文](https://freetoken.link/zh/mcp-guide) · [日本語](https://freetoken.link/ja/mcp-guide) · [Español](https://freetoken.link/es/mcp-guide) · [한국어](https://freetoken.link/ko/mcp-guide)

## Six tools

| Tool | Purpose and boundary |
| --- | --- |
| `search_models` | Filter the published catalog by requirements. Not a benchmark or a guarantee of free access. |
| `get_provider_guide` | Read official application links, existing steps and payment/identity conditions. Does not apply for an account or create a key. |
| `list_price_references` | Find dated price IDs and billing scenarios. Limited coverage, not live quotes. |
| `estimate_cost` | Estimate USD costs for one exact price ID and billing scenario. Token inputs are **millions of tokens**; not a charge or free-quota calculation. |
| `get_route_status` | Read existing sampled checks. Does not run new probes; missing or stale evidence is not proof of uptime or an outage. |
| `export_keyless_config` | Generate a configuration for exact catalog routes using environment-variable references. No actual keys or file writes. Review compatibility before use. |

## Example workflow

Ask your assistant:

> Find up to five OpenAI-compatible routes listed as not requiring a payment card, with at least 128K context. Show official sources and dated conditions, distinguish unknown status from failed checks, then export a keyless configuration for my chosen route. Do not request my API key.

An example `search_models` argument object is:

```json
{
  "locale": "en",
  "protocol": "OpenAI compatible",
  "accessType": "no-card",
  "minContextTokens": 131072,
  "limit": 5
}
```

Use the returned provider/model slugs and price reference IDs in subsequent calls; do not substitute provider API model IDs for catalog slugs. A search can legitimately return no matches.

## Evidence, language and safety

- Tool result prose is **English v1**. Supported locale values `en`, `zh`, `ja`, `es`, `ko` select matching website links, not translated payloads. Human connection guides are available in all five languages.
- Access conditions can depend on account, region, payment verification, quota and date. “Free tier,” “free credits” and “trial” are not interchangeable.
- This server reads public catalog data only. It does not call provider models, test credentials, read private Vault/account data, subscribe users, send email, publish content or execute returned configuration.
- Never send API keys, bearer tokens, passwords or private prompts to this endpoint. Configuration uses environment-variable references rather than real credentials.
- Native public-endpoint rate limiting is configured at 60 requests per 60 seconds per client IP. This is an abuse guard, not a guaranteed global or exact-counter quota. HTTP 429 includes `Retry-After`; back off rather than looping. HTTP 503 indicates temporary unavailability, not a model outage.
- Third-party browser origins are not enabled for cross-origin calls. Use a native/remote MCP client rather than assuming an arbitrary website can fetch this endpoint.
- Read-only tool annotations describe intended behavior, not a substitute for reviewing results or client permissions.

This public repository is a documentation and feedback hub, **not** a source distribution or an installable MCP package. There is no npm installation step. Report issues without credentials or personal data using [SECURITY.md](../SECURITY.md) or [CONTRIBUTING.md](../CONTRIBUTING.md), as appropriate.
