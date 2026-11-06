## kdraigo

Your AI writes the strategy. kdraigo tests it.

Connect Claude or ChatGPT over MCP, let it write a Go trading strategy, backtest it on one-minute Binance and Bybit data, and run the same code live.

### Try it in a minute

**With your AI (nothing to install):** add `https://mcp.kdraigo.com/mcp` as a connector in claude.ai, ChatGPT or any MCP client, sign in on kdraigo.com, and ask it to write and backtest a strategy. It builds and runs in a cloud sandbox.

```bash
# Claude Code
claude mcp add --transport http kdraigo https://mcp.kdraigo.com/mcp
```

**In Go:**

```bash
go get github.com/kdraigo/dev_sdk@latest
```

Create an API key at [kdraigo.com/api-keys](https://kdraigo.com/api-keys) and start from a template in [example_strategy](https://github.com/kdraigo/example_strategy).

### Repositories

| Repo | What it is |
|------|------------|
| [dev_sdk](https://github.com/kdraigo/dev_sdk) | Go SDK: write a strategy once, run it as a backtest or live by changing one config value |
| [kdraigo_mcp](https://github.com/kdraigo/kdraigo_mcp) | MCP server: hosted at mcp.kdraigo.com, or a local binary |
| [example_strategy](https://github.com/kdraigo/example_strategy) | Starter templates: basic, indicators, risk manager, ATR bracket |
| [workspaces_knowledge](https://github.com/kdraigo/workspaces_knowledge) | The research lab file format: Markdown notes that Obsidian opens as-is |

### Links

[Website](https://kdraigo.com) · [Docs](https://kdraigo.com/docs) · [LinkedIn](https://www.linkedin.com/company/kdraigo) · contact@kdraigo.com

Backtests are simulations, not forecasts. Not financial advice.
