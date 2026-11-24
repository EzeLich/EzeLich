### Hi, I'm Ezequiel Lech 👋

**Web3, AI & Python Infrastructure Engineer** — building **non-custodial stablecoin payment gateways, `x402` monetization APIs, MCP agent infrastructure, and automated Telegram/exchange systems**.

---

#### 🚀 Flagship Open-Source Product — [PayGate USDT v2.2.0 (`EzeLich/paygate-usdt`)](https://github.com/EzeLich/paygate-usdt)

Non-custodial **USDT & USDC Payment Gateway** across **Polygon, BSC (BEP-20), Base, Arbitrum, Ethereum, and Solana SPL** — zero custody, zero Stripe/bank KYC, zero platform cut:

- **Stateless 1-Click Payment Links & Widget** (`/paygate/pay?...` + `/paygate/widget.js`) with 1-Click MetaMask/Rabby/Phantom `0xa9059cbb` checkout
- **Hosted Invoices, Verifiable SHA-256 Receipts & HMAC-SHA256 Webhooks** (`/paygate/checkout/{id}`, `/paygate/receipt/{id}`)
- **FastAPI `HTTP 402` (`x402 v2`) Paywall Decorator** (`@require_usdt_payment`)
- **Automated Telegram Paid VIP Bot** (`@ChainGuardVaultBot`) + **Remote & Stdio MCP Server** (`python -m paygate_sdk mcp`)

#### ⚡ Instant 1-Click Non-Custodial Checkout & B2B Hiring
- 🔑 **[30-Day Unlimited MCP & Pro API Pass ($9 Base USDC/USDT)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=9&network=base&title=30-Day+Unlimited+MCP+%26+Pro+API+Pass&issue_pass=1)** *(auto-mints `cg_live_` key on-chain)*
- 🏢 **[Turnkey VIP Gate Deployment ($199 USDT · $99 deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=99&network=polygon&title=Turnkey+VIP+Gate+Deployment+50pct+Deposit)** · **[Book B2B Scope](https://chainguard-studio-production.up.railway.app/paygate#b2b)**
- 🛠️ **[Custom Bot + API / Exchange Automation ($499 USDT · $249 deposit)](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=249&network=polygon&title=Custom+Bot+%2B+Exchange+API+50pct+Deposit)** · **[Open GitHub Inquiry](https://github.com/EzeLich/paygate-usdt/issues/new?template=b2b_custom_deployment.yml)**

---

#### 📦 Additional Public Work
- **[polymarket-whale-radar](https://github.com/EzeLich/polymarket-whale-radar)** — Polymarket Data API v2 whale flow & leaderboard intelligence engine.

#### 🛠️ Core Stack
`Python 3.10+` · `FastAPI` · `MCP (Model Context Protocol)` · `x402` · `EVM JSON-RPC` · `Solana SPL` · `Telegram Bot API` · `SQLite`
