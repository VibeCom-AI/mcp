# VibeCom MCP Server

VibeCom is the vibe marketing platform for technical founders. The VibeCom MCP server connects Cursor to Growth Autopilot so AI agents can turn product context, code changes, and launch plans into multi-platform marketing content.

## What You Can Do

- Generate launch posts, founder updates, blog outlines, and channel-native content.
- Turn codebase context, product docs, and recent changes into specific marketing assets.
- Prepare Growth Autopilot review tasks without leaving Cursor.
- Create content for X, LinkedIn, blog, newsletters, directories, and launch communities.
- Use VibeCom's hosted remote MCP server with OAuth authentication.

## MCP Endpoint

VibeCom is a hosted remote MCP server using Streamable HTTP and OAuth.

```json
{
  "mcpServers": {
    "vibecom-growth": {
      "url": "https://www.vibecom.app/api/mcp/growth"
    }
  }
}
```

No npm package or local server process is required.

## Install In Cursor

1. Open Cursor Settings.
2. Go to Tools & MCP.
3. Add a custom MCP server.
4. Paste the config above.
5. Save the config.
6. Click Connect and complete VibeCom OAuth authorization.

After authentication, VibeCom appears in Cursor's available MCP tools.

## Requirements

- Cursor with remote MCP support.
- A VibeCom account.
- Free, Pro, or Growth plan.

## Authentication

VibeCom uses OAuth. Cursor opens a browser authorization flow when you connect the server.

Do not add API keys, bearer tokens, or secrets to your `mcp.json`.

## Example Prompts

```text
Use VibeCom to generate launch content from this repo.
```

```text
Use VibeCom to draft X and LinkedIn posts for the latest product changes.
```

```text
Use VibeCom to prepare my Growth Autopilot review queue.
```

```text
Use VibeCom to turn this changelog into a blog outline and founder update.
```

## Links

- Website: https://www.vibecom.app
- Product: https://www.vibecom.app/product
- MCP setup docs: https://www.vibecom.app/docs/growth-autopilot/mcp-setup
- Support: https://www.vibecom.app/support
