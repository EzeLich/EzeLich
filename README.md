### Hi, I'm Ezequiel Lech 👋

**Web3, AI & Python Infrastructure Engineer** — building **non-custodial stablecoin payment gateways, `x402` monetization APIs, MCP agent infrastructure, and automated Telegram/exchange systems**.

---

#### 🚀 Flagship Open-Source Product — [PayGate USDT v2.0 (`EzeLich/paygate-usdt`)](https://github.com/EzeLich/paygate-usdt)

Non-custodial **USDT & USDC Payment Gateway** across **Polygon, BSC (BEP-20), Base, Arbitrum, Ethereum, and Solana SPL** — zero custody, zero Stripe/bank KYC, zero platform cut:

- **Hosted Checkout Invoices & HMAC-SHA256 Signed Webhooks** (`/paygate/checkout/{id}` + `X-PayGate-Signature`)
- **FastAPI `HTTP 402` (`x402 v2`) Paywall Decorator** (`@require_usdt_payment` with `PAYMENT-REQUIRED` header & anti-replay)
- **Automated Telegram Paid VIP Bot** (`@ChainGuardVaultBot`, single-use invites + auto-kick on expiry)
- **Remote Streamable-HTTP MCP Server** (`create_usdt_invoice` & `verify_usdt_invoice` tools live at `/mcp`)

- 🌐 **Live Cloud Sandbox & B2B Portal:** [chainguard-studio-production.up.railway.app/paygate](https://chainguard-studio-production.up.railway.app/paygate)
- 🏢 **Turnkey Integration / Custom Crypto Bot (`$199–$499 USDT`):** [Book via On-Chain Checkout](https://chainguard-studio-production.up.railway.app/paygate#b2b) · [Open B2B GitHub Inquiry](https://github.com/EzeLich/paygate-usdt/issues/new?template=b2b_custom_deployment.yml)

---

#### 📦 Additional Public Work
- **[polymarket-whale-radar](https://github.com/EzeLich/polymarket-whale-radar)** — Polymarket Data API v2 whale flow & leaderboard intelligence engine.

#### 🛠️ Core Stack
`Python 3.10+` · `FastAPI` · `MCP (Model Context Protocol)` · `x402` · `EVM JSON-RPC` · `Solana SPL` · `Telegram Bot API` · `SQLite`
