# Power Automate MCP Server by Flow Studio

Debug, build, and manage Power Automate cloud flows with AI — no portal needed.

Ask your AI agent why a flow failed, build new flows from natural language, or check
run history across tenants. This plugin connects the
[Flow Studio](https://mcp.flowstudio.app) MCP server to Cursor.

## Setup

1. Get an API key at [mcp.flowstudio.app](https://mcp.flowstudio.app)
2. Set the environment variable:
   ```
   FLOWSTUDIO_MCP_API_KEY=your-key
   ```
3. Install this plugin in Cursor

## Available Tools

| Tool | Description |
|------|-------------|
| `list_live_flows` | List all flows in a Power Platform environment |
| `list_live_environments` | Discover all Power Platform environments |
| `list_live_connections` | List connectors and connection status |
| `get_live_flow` | Read the full flow definition (triggers, actions, parameters) |
| `get_live_flow_runs` | View recent run history with status and timing |
| `get_live_flow_run_error` | Get per-action error breakdown for a failed run |
| `get_live_flow_run_action_outputs` | Inspect inputs/outputs of any action, including loop iterations |
| `get_live_flow_http_schema` | Inspect the request/response schema of HTTP-triggered flows |
| `get_live_flow_trigger_url` | Get the signed callback URL for HTTP-triggered flows |
| `trigger_live_flow` | Trigger an HTTP-triggered flow with a JSON payload |
| `update_live_flow` | Create a new flow or update an existing definition |
| `resubmit_live_flow_run` | Replay a failed run using its original trigger data |
| `cancel_live_flow_run` | Cancel a currently running flow execution |
| `set_live_flow_state` | Start or stop a flow |
| `add_live_flow_to_solution` | Migrate a flow into a solution |

## Links

- [Flow Studio](https://flowstudio.app)
- [MCP Server](https://mcp.flowstudio.app)
- [Getting Started](https://learn.flowstudio.app/mcp-getting-started)
- [GitHub](https://github.com/ninihen1/power-automate-mcp-skills)
