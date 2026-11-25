# Dexto for Claude Code

Connect Claude Code to your Dexto workspace to discover available tools and work with your saved
context, apps, agents, and automations. The Dexto account and workspace you authorize determine
which tools and data are available. The bundled skill helps Claude find the right tool and follow
its confirmation requirements.

## Connect

Install this plugin through a marketplace or load this directory with
`claude --plugin-dir /path/to/dexto-claude-plugin`. In Claude Code, open `/mcp`, select `dexto`,
and authenticate. Sign in to Dexto, choose your organization, and review the requested access
before approving it. No API key needs to be placed in the plugin configuration.

Once connected, try asking Claude to list your Dexto chats or find an available app action. An
empty list can simply mean that the workspace has no matching items.

## Data and permissions

The plugin configures a remote MCP connection to `https://app.dexto.ai/mcp`. Requests and the
information needed to answer them are sent to Dexto through that connection. This plugin runs no
local server, scripts, or hooks. Claude Code handles the OAuth sign-in; Dexto enforces your
workspace permissions on each call.

Review the OAuth consent screen: requested scopes can include permission to change workspace
data or use metered capabilities. Some actions require your explicit confirmation. See the
[Dexto MCP guide](https://www.dexto.ai/docs/mcp/) for details and the
[privacy policy](https://www.dexto.ai/privacy/) for data handling.

## Support

Visit the [Dexto documentation](https://www.dexto.ai/docs/mcp/) or contact support@dexto.ai.

## License

MIT; see [LICENSE](LICENSE).
