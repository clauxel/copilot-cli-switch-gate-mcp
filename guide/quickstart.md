# Quickstart

Copilot CLI Switch Gate is a hosted remote MCP for Copilot CLI switch gate MCP.

## Fast Path

1. Open Copilot CLI Switch Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://copilotcliswitchgate.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_cli_switch_gate with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://copilotcliswitchgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=quickstart_home
- https://copilotcliswitchgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=quickstart_pricing
- https://copilotcliswitchgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=copilotcliswitchgate_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://copilotcliswitchgate.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
