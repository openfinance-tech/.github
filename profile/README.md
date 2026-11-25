## OpenFinance

Trading for AI agents. Connect Claude, ChatGPT, Cursor, Codex or any MCP client to one hosted server, and your agent can research and trade crypto spot and perps, stocks, forex, prediction markets and memecoins.

```text
https://api.openfinance.tech/agent/mcp
```

Sign in with OAuth, or send your OpenFinance API key in an `x-api-key` header. There's nothing to install.

| Repo | What it is |
|---|---|
| [**mcp**](https://github.com/openfinance-tech/mcp) | The OpenFinance MCP server: setup for every AI client, the tool reference, safety notes |
| [**skills**](https://github.com/openfinance-tech/skills) | Agent skills for Polymarket, Hyperliquid, Relay, onchain tokens and launches: `npx skills add openfinance-tech/skills -y` |
| [**self-hosted-perp-dex**](https://github.com/openfinance-tech/self-hosted-perp-dex) | A Hyperliquid perp DEX with an AI agent that you deploy yourself, running on one OpenFinance key |

**What an agent can and can't do with your money**

- Every order tool tells it to confirm with you first: it shows a summary and waits for your go-ahead, such as replying "confirm".
- It can move funds only between your own wallets. Sending to anyone else needs your sign-in on openfinance.tech and a code from your authenticator app.
- It can still trade, so a bad trade can lose money. Fund only what you're willing to risk.
- Your wallets are yours: export the private keys from Settings → Export Keys, with a code from your authenticator app.

[openfinance.tech](https://openfinance.tech) · [Connect your agent](https://openfinance.tech/agents) · [Docs](https://docs.openfinance.tech) · [Security](https://openfinance.tech/security) · [X](https://x.com/openfinancelabs)

<sub>Trading carries a high risk of loss. Nothing here is financial advice.</sub>
