# Copilot CLI Switch Gate

Copilot CLI Switch Gate is a hosted remote MCP for Copilot CLI switch gate MCP.

This repository is a public documentation project for Copilot CLI Switch Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://copilotcliswitchgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=readme_home
- Pricing: https://copilotcliswitchgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=readme_pricing
- Checkout: https://copilotcliswitchgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://copilotcliswitchgate.clauxel.com/mcp
- Server card: https://copilotcliswitchgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.copilotcliswitchgate/copilotcliswitchgate-mcp`
- Tools: `check_cli_switch_gate`, `map_cli_command`, `classify_migration_risk`, `issue_switch_receipt`, `export_switch_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

developer platform teams, release owners, AI engineering leads, and delivery reviewers.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_cli_switch_gate
- MCP tool: map_cli_command
- MCP tool: classify_migration_risk
- MCP tool: issue_switch_receipt
- MCP tool: export_switch_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
