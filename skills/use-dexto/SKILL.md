---
name: use-dexto
description: Use Dexto workspace tools to find context or work with agents, apps, and automations when the user asks.
---

# Use Dexto

Use the connected Dexto MCP server when the user asks to work with their Dexto workspace. Discover
available tools and actions before choosing one; availability depends on the account, workspace,
and permissions granted to the connection. If the server is unavailable, ask the user to connect
it through Claude Code's `/mcp` menu.

Read only the information needed for the request. Before changing, publishing, sending, deploying,
installing, or spending, follow the tool's instructions and ask the user when confirmation is
required. For tools requiring `confirm: true`, send it only after the user approves that exact
action. Do not ask the user to paste access tokens or other credentials into the conversation.
