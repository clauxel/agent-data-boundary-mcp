# AgentData Boundary MCP

Permission boundary receipts for ChatGPT agents.

Paid remote MCP for agent data-access boundary reviews, permission scope evidence, sensitive data notes, and governance receipts.

## Public Endpoints

- Website: https://agentdataboundary.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://agentdataboundary.clauxel.com/mcp
- Server card: https://agentdataboundary.clauxel.com/server-card.json
- Registry name: `com.clauxel.agentdataboundary/agentdataboundary-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `map_permissions`
- `flag_sensitive_fields`
- `summarize_boundary`
- `export_remediation_plan`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://agentdataboundary.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://agentdataboundary.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://agentdataboundary.clauxel.com/server-card.json
- MCP endpoint: https://agentdataboundary.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
