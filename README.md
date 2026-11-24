### Hi, I'm Ezequiel Lech 👋

**Web3, AI & Python Infrastructure Engineer** — building **non-custodial stablecoin payment gateways, `x402 v2` monetization APIs, Streamable-HTTP MCP agent infrastructure, and DeFi security firewalls**.

---

#### 🚀 Flagship Open-Source Products

1. **[PayGate USDT v2.3.0 (`EzeLich/paygate-usdt`)](https://github.com/EzeLich/paygate-usdt)** — Non-custodial **USDT & USDC Payment Gateway** across **Polygon, BSC (BEP-20), Base, Arbitrum, Ethereum, and Solana SPL** (0% custody, 0% Stripe/bank KYC, 0% platform cut):
   - **Recurring Non-Custodial SaaS Subscriptions** (`customer_ref` + `billing_days` + early-renewal stacking + `/api/v1/paygate/subscriptions/check`) — zero `MAX_UINT256` token approvals
   - **Stateless 1-Click Payment Links & Widget** (`/paygate/pay?...` + `/paygate/widget.js`) with 1-Click MetaMask/Rabby/Phantom `0xa9059cbb` checkout + SHA-256 Receipts
   - **FastAPI `HTTP 402` (`x402 v2`) Paywall Decorator** (`@require_usdt_payment`) + **Automated Telegram Paid VIP Bot** (`@ChainGuardVaultBot`) + **Stdio/HTTP MCP Server**

2. **[ChainGuard MCP v1.0.0 (`EzeLich/chainguard-mcp`)](https://github.com/EzeLich/chainguard-mcp)** — **14-Tool Web3 Security, DeFi Yield, Vault Recovery & Non-Custodial USDT MCP Server + Offline Pre-Flight Firewall**:
   - **Hosted Remote MCP (`2025-03-26`)**: `https://chainguard-studio-production.up.railway.app/mcp` (tools, resources, prompts, free 5 calls/hr)
   - **Zero-Dependency Python Stdio Bridge & CLI Firewall**: `chainguard-mcp mcp [--offline]`, `scan-tx`, `scan-mcp` (EIP-7702 hijack, Solana Token-2022, unlimited ERC-20 approval & MCP Unicode smuggling detection)

#### ⚡ Instant 1-Click Non-Custodial Checkout & B2B Hiring
- 🔑 **[30-Day Unlimited MCP & Pro API Pass ($9 Base USDC/USDT)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=9&network=base&title=ChainGuard+Unlimited+MCP+Pass&issue_pass=1&billing_days=30)** *(auto-mints `cg_live_` key on-chain)*
- 🏢 **[Turnkey VIP Gate Deployment ($199 USDT · $99 deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=99&network=polygon&title=Turnkey+VIP+Gate+Deployment+50pct+Deposit)** · **[Book B2B Scope](https://chainguard-studio-production.up.railway.app/paygate#b2b)**
- 🛠️ **[Custom Bot + API / Exchange Automation ($499 USDT · $249 deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=249&network=polygon&title=Custom+Bot+%2B+Exchange+API+50pct+Deposit)** · **[Open GitHub Inquiry](https://github.com/EzeLich/paygate-usdt/issues/new?template=b2b_custom_deployment.yml)**

---

#### 📦 Additional Public Work
- **[polymarket-whale-radar](https://github.com/EzeLich/polymarket-whale-radar)** — Polymarket Data API v2 whale flow & leaderboard intelligence engine.

#### 🛠️ Core Stack
`Python 3.10+` · `FastAPI` · `MCP (2025-03-26)` · `x402 v2` · `EVM JSON-RPC` · `Solana SPL` · `Telegram Bot API` · `SQLite`
