### Ezequiel Lech

**Python, TypeScript & Web3 Infrastructure Engineer** — building non-custodial multi-chain payment gateways (`USDT`, `USDC`, native `ETH`, `BNB`, `POL`, `SOL`, and `Bitcoin Taproot`), HTTP 402 (`x402 v2`) API and MCP monetization SDKs, Streamable-HTTP MCP servers, and automated CI/CD Web3 security firewalls.

---

#### Production Open-Source Software (Official MCP Registry & Glama Grade-A)

1. **[PayGate USDT v2.7.0 (`EzequielLech/paygate-usdt`)](https://github.com/EzequielLech/paygate-usdt)** — Non-custodial crypto & stablecoin payment gateway across Base, Polygon, Arbitrum, BSC (BEP-20), Ethereum, Solana SPL, and Bitcoin Taproot (`bc1p...`) with 0% custody and no bank or Stripe KYC:
   - **Official MCP Registry**: `io.github.EzequielLech/paygate-usdt` ([Rated Grade-A `4.1/5.0` on Glama](https://glama.ai/mcp/connectors/io.github.EzeLich/paygate-usdt))
   - **Python & Zero-Dependency TypeScript/Node.js SDKs (`paygate_sdk` + `sdk-js/`)**: 1-line MCP tool monetization (`@mcp_tool_paywall` / `withMcpToolPaywall`) and HTTP 402 `x402 v2` route guards (`@require_usdt_payment` / `paygateExpressMiddleware`)
   - **Hosted Multi-Asset Checkout (`/paygate/checkout/{id}`) & Self-Serve Merchant Dashboard (`/paygate/merchant`)**: 7-network switcher (`USDT/USDC` + 1-click native `ETH`, `BNB`, `POL`, `SOL`, `BTC` with live DeFiLlama spot quotes), zero-tx-hash on-chain transfer auto-detection, SHA-256 verifiable receipts, signed HMAC-SHA256 webhooks, and recurring SaaS subscriptions without `MAX_UINT256` token approvals

2. **[ChainGuard MCP v1.3.1 (`EzequielLech/chainguard-mcp`)](https://github.com/EzequielLech/chainguard-mcp)** — 15-tool Web3 security firewall, GitHub Action CI security gate, DeFiLlama yield scanner, ERC-20 allowance revoker, and vault recovery MCP server:
   - **Official MCP Registry**: `io.github.EzequielLech/chainguard-mcp` ([Rated Grade-A `4.2/5.0` on Glama](https://glama.ai/mcp/connectors/io.github.EzeLich/chainguard-mcp))
   - **GitHub Action CI Security Gate**: `uses: EzequielLech/chainguard-mcp@v1.3.1` + `chainguard-mcp scan-dir . --fail-on-block --markdown` to block `tx.origin`, `selfdestruct`, unchecked `delegatecall`, reentrancy, invisible Unicode smuggling, and leaked keys on pull requests
   - **Hosted Remote Streamable-HTTP MCP (`2025-06-18`) & Offline CLI**: `https://chainguard-studio-production.up.railway.app/mcp` (EIP-7702 delegation hijack detection, Solana Token-2022 drainer audit, ERC-20 `approve(spender, 0)` revocation builder, and 8-chain dust/hygiene recovery)

---

#### Instant Self-Serve Passes, White-Label Licensing & Custom B2B Engineering

All checkouts accept **USDC, USDT, and native ETH, BNB, POL, SOL, or BTC** across Base, Polygon, Arbitrum, BSC, Ethereum, Solana, and Bitcoin with instant automated on-screen `cg_live_` API key delivery upon 1 block confirmation:

| Plan / Service | Settlement | Deliverables | Direct 1-Click Checkout |
|---|---|---|---|
| **24-Hour Micro-Unlock Pass** | **$0.50** | 50 Pro MCP & REST calls (24h), full vulnerability patches & 25 DeFi pools | [Launch $0.50 Checkout](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=0.5&network=base&title=ChainGuard+24h+Micro+Unlock+Pass&issue_pass=1&billing_days=1) |
| **7-Day Starter MCP & Pro API Pass** | **$2.00** | 250 Pro MCP & REST calls (7 days) + full 8-chain portfolio & allowance scanner | [Launch $2.00 Checkout](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=2&network=base&title=ChainGuard+7-Day+Starter+MCP+Pass&issue_pass=1&billing_days=7) |
| **30-Day Unlimited MCP & Cloud Pro Pass** | **$9.00** | Unlimited `/mcp` calls + 1,000 REST calls + unlimited hosted PayGate Cloud merchant settlements (30 days) | [Launch $9.00 Checkout](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=9&network=base&title=ChainGuard+Unlimited+MCP+Pass&issue_pass=1&billing_days=30) |
| **PayGate Lifetime White-Label License** | **$79.00** | Unlimited merchants/members + 25,000-call Master API Key (10-year validity) | [Launch $79.00 Checkout](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=79&network=polygon&title=PayGate+Lifetime+White-Label+License&issue_pass=1&billing_days=3650) |
| **Turnkey B2B Payment Gateway Deployment** | **$199.00** ($99 Deposit) | Dedicated multi-chain PayGate + Telegram VIP + webhook integration deployed on your infra | [Pay $99 Deposit](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=99&network=polygon&title=Turnkey+VIP+Gate+Deployment+50pct+Deposit&issue_pass=1) · [Scope](https://chainguard-studio-production.up.railway.app/paygate#b2b) |
| **Custom Crypto Bot + Exchange/API Automation** | **$499.00** ($249 Deposit) | Custom Python/TypeScript Web3 agent, MCP server, or trading/execution workflow | [Pay $249 Deposit](https://chainguard-studio-production.up.railway.app/paygate/pay?merchant=0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD&amount=249&network=polygon&title=Custom+Bot+%2B+Exchange+API+50pct+Deposit&issue_pass=1) · [Open B2B Issue](https://github.com/EzequielLech/paygate-usdt/issues/new?template=b2b_custom_deployment.yml) |

- **Self-Serve Merchant Revenue Dashboard**: [https://chainguard-studio-production.up.railway.app/paygate/merchant](https://chainguard-studio-production.up.railway.app/paygate/merchant)
- **Direct On-Chain Settlement Wallets (Self-Custody)**:
  - **EVM (`ETH`, `BNB`, `POL`, `USDC`, `USDT` on Base, Arbitrum, Polygon, BSC, Ethereum)**: `0x4Ed4D0750453C027FA8398067d5af980Bcc9B6eD`
  - **Solana (`SOL`, `USDC`, `USDT`)**: `3fZSMAyCEMhZwWiynbJDjoYNUT97aiV9BLzoUNroEMAz`
  - **Bitcoin (`BTC` Taproot Bech32m)**: `bc1p980u6y2m768yrhcy5u3llas49w2wpsnselp7sqetn43vnetzqkdqypjcgk`

---

#### Technical Stack
`Python 3.10+` · `TypeScript / Node.js ESM` · `FastAPI` · `MCP (2025-06-18)` · `x402 v2` · `EVM JSON-RPC` · `Solana SPL / Token-2022` · `Bitcoin Taproot` · `GitHub Actions CI` · `SQLite` · `Docker`
