# waft-mcp

Waft plugin for AI coding assistants — gives your agent the ability to deploy, monitor, and scale production apps.

## Claude Code

Two commands inside Claude Code. No terminal needed — the binary downloads automatically on first use.

```
/plugin marketplace add darrenoakey/waft-mcp
/plugin install waft@waft-mcp
```

Then tell Claude: *"make this live"* or *"deploy this as my-app"* and it handles everything.

## Gemini CLI

```bash
curl -sSL https://waft.dev/install | sh
gemini extensions install https://github.com/darrenoakey/waft-mcp
```

## Codex CLI

```bash
curl -sSL https://waft.dev/install | sh
```

The script detects Codex and registers automatically.

---

## What your agent can do

| Say this... | Agent does this |
|-------------|----------------|
| "make this live" | Deploys to `https://my-app.waft.dev` |
| "add auto-deploy on push" | Creates GitHub Actions workflow |
| "add API key auth" | Enables auth + rate limiting |
| "why is my app slow?" | Reads telemetry, finds the bottleneck |
| "show me the logs" | Tails recent log entries |
| "show all my apps" | Lists deployed apps with URLs and status |

## Tools

| Tool | Description |
|------|-------------|
| `waft_release` | Zip and deploy a local directory |
| `waft_apps` | List all deployed apps |
| `waft_status` | Detailed app status and deployment history |
| `waft_logs` | Tail recent log entries |
| `waft_telemetry` | Request metrics, latency, error rate |
| `waft_login` | Authenticate with the waft API |

## Update

```
/plugin marketplace update waft-mcp   # Claude Code
gemini extensions update waft         # Gemini CLI
curl -sSL https://waft.dev/install | sh   # Codex / manual
```

## Links

- [waft.dev](https://waft.dev) — dashboard and full docs
- [Getting started](https://waft.dev/portal/getting-started)

## License

This project is licensed under [CC BY-NC 4.0](https://darren-static.waft.dev) - free to use and modify, but no commercial use without permission.
