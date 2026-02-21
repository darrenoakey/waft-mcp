# waft-mcp

Waft MCP plugin — gives your AI assistant the ability to deploy, monitor, and scale production apps.

## Install

### Gemini CLI

```bash
curl -sSL https://waft.dev/install | sh
gemini extensions install https://github.com/darrenoakey/waft-mcp
```

### Claude Code

```bash
curl -sSL https://waft.dev/install | sh
```

The install script downloads the waft binary and registers it with Claude Code automatically.

### Codex CLI

```bash
curl -sSL https://waft.dev/install | sh
```

The install script also registers with Codex if it detects it installed.

## What it does

Once installed, tell your AI assistant to deploy your project:

- "make this live as my-app"
- "what's the status of my dashboard?"
- "show me the logs for my-api"
- "what's the error rate on production?"

Your app gets a `https://your-app.waft.dev` URL automatically.

## Tools

| Tool | Description |
|------|-------------|
| `waft_release` | Deploy a directory as a new app revision |
| `waft_apps` | List all deployed apps |
| `waft_status` | Detailed app status and deployment history |
| `waft_logs` | Tail recent log entries |
| `waft_telemetry` | Request metrics, latency, error rate |
| `waft_login` | Authenticate with the waft API |

## Update

```bash
gemini extensions update waft   # Gemini
curl -sSL https://waft.dev/install | sh   # Claude Code / Codex
```

## Links

- [waft.dev](https://waft.dev) — dashboard and docs
- [Getting started](https://waft.dev/portal/getting-started)
