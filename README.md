### Ezequiel Lech

**Python & Web3 Infrastructure Engineer** — building non-custodial stablecoin payment gateways, HTTP 402 (`x402 v2`) API monetization middlewares, Streamable-HTTP MCP servers, and pre-flight DeFi security firewalls.

---

#### Production Open-Source Software

1. **[PayGate USDT v2.5.1 (`EzeLich/paygate-usdt`)](https://github.com/EzeLich/paygate-usdt)** — Non-custodial USDT and USDC payment gateway across Polygon, BSC (BEP-20), Base, Arbitrum, Ethereum, and Solana SPL (0% custody, no bank or Stripe KYC, 0% platform cut):
   - **Official MCP Registry**: `io.github.EzeLich/paygate-usdt` ([Rated Grade-A `4.1/5.0` on Glama](https://glama.ai/mcp/connectors/io.github.EzeLich/paygate-usdt))
   - **1-Line MCP Tool Paywall Decorator (`@mcp_tool_paywall`)** and **FastAPI HTTP 402 Decorator (`@require_usdt_payment`)**
   - **Hosted Multi-Chain Checkout (`/paygate/checkout/{id}`)** with 6-network switcher, zero-tx-hash on-chain transfer auto-detection, signed HMAC-SHA256 webhooks, and recurring SaaS subscriptions without `MAX_UINT256` token approvals

2. **[ChainGuard MCP v1.2.0 (`EzeLich/chainguard-mcp`)](https://github.com/EzeLich/chainguard-mcp)** — 15-tool Web3 security firewall, DeFi yield scanner, ERC-20 allowance revoker, and vault recovery MCP server:
   - **Official MCP Registry**: `io.github.EzeLich/chainguard-mcp` ([Rated Grade-A `4.2/5.0` on Glama](https://glama.ai/mcp/connectors/io.github.EzeLich/chainguard-mcp))
   - **Hosted Remote Streamable-HTTP MCP (`2025-06-18`)**: `https://chainguard-studio-production.up.railway.app/mcp`
   - **Zero-Dependency Python CLI & Offline Pre-Flight Firewall**: `chainguard-mcp mcp [--offline]`, `scan-tx`, `scan-mcp` (EIP-7702 delegation hijack detection, Solana Token-2022 drainer audit, ERC-20 `approve(spender, 0)` revocation builder, and MCP Unicode smuggling protection)

---

#### Hosted Passes, White-Label Licensing & Custom B2B Engineering

- **[24-Hour Micro-Unlock Pass ($0.50 USDC/USDT — 50 Calls)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=0.5&network=base&title=ChainGuard+24h+Micro+Unlock+Pass&issue_pass=1&billing_days=1)** — Instant on-screen `cg_live_` API key
- **[7-Day Starter MCP & Pro API Pass ($2.00 USDC/USDT — 250 Calls)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=2&network=base&title=ChainGuard+7-Day+Starter+MCP+Pass&issue_pass=1&billing_days=7)** — Instant on-screen `cg_live_` API key
- **[30-Day Unlimited MCP & Pro API Pass ($9.00 USDC/USDT — 1,000 REST Calls + Unlimited `/mcp`)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=9&network=base&title=ChainGuard+Unlimited+MCP+Pass&issue_pass=1&billing_days=30)** — Instant on-screen `cg_live_` API key
- **[PayGate Lifetime White-Label License ($79.00 USDT/USDC)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=79&network=polygon&title=PayGate+Lifetime+White-Label+License&issue_pass=1&billing_days=3650)** — Unlimited members + 25,000-call Master API Key
- **[Turnkey B2B Payment Gateway Deployment ($199 USDT · $99 Deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=99&network=polygon&title=Turnkey+VIP+Gate+Deployment+50pct+Deposit&issue_pass=1)** · **[Scope & Documentation](https://chainguard-studio-production.up.railway.app/paygate#b2b)**
- **[Custom Crypto Bot + Exchange/API Automation ($499 USDT · $249 Deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=249&network=polygon&title=Custom+Bot+%2B+Exchange+API+50pct+Deposit&issue_pass=1)** · **[Open Technical Inquiry](https://github.com/EzeLich/paygate-usdt/issues/new?template=b2b_custom_deployment.yml)**

---

#### Technical Stack
`Python 3.10+` · `FastAPI` · `MCP (2025-06-18)` · `x402 v2` · `EVM JSON-RPC` · `Solana SPL / Token-2022` · `Telegram Bot API` · `SQLite` · `Docker`
