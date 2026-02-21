# Waft — Deploy from your AI

Waft gives you the ability to deploy, monitor, and scale real production apps directly from this conversation.

## What you can do

- **Deploy an app** — "make this live" or "release this as my-app"
- **Check status** — "what's the status of my dashboard app?"
- **Read logs** — "show me the last 50 log lines from my-api"
- **View telemetry** — "what's the error rate on production?"
- **List apps** — "show all my apps"

## Available tools

| Tool | Purpose |
|------|---------|
| `waft_release` | Zip and deploy a local directory as a new app revision |
| `waft_apps` | List all deployed apps with URLs and status |
| `waft_status` | Detailed status for one app including recent deployments |
| `waft_logs` | Tail recent log entries from a deployed app |
| `waft_telemetry` | Request metrics, latency, error rate, cold starts |
| `waft_login` | Authenticate with the waft API |

## Authentication

If you haven't authenticated yet, call `waft_login` — it will open a browser window to log in.

## Deployed app URLs

All apps get a `{name}.waft.dev` URL automatically. Custom domains can be configured from the dashboard at https://waft.dev/portal.
