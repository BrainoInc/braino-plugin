# Braino Agent Plugin

Braino gives agents governed access to shared team knowledge: decisions, rules, evidence, and work
history. The hosted MCP server is available at `https://braino.dev/mcp` and uses OAuth with dynamic
client registration and PKCE.

The connection can only reach workspaces and collections granted to the signed-in Braino account.
It cannot browse the open web, send messages, make payments, or access unrelated services.

## Install locally in Cursor

Copy this package to `~/.cursor/plugins/local/braino`, preserving this root layout:

```text
braino/
├── plugin.json
├── mcp.json
├── README.md
├── assets/
└── skills/
```

Restart Cursor, enable Braino, and complete the browser-based OAuth flow. A basic connection check
is: “Which Braino workspaces and collections can I access?”

## Links

- Website: https://braino.dev
- Support: https://braino.dev/support
- Privacy policy: https://braino.dev/privacy
- Terms of service: https://braino.dev/terms
- Source: https://github.com/BrainoInc/braino
