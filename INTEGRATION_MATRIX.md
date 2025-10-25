# 402Gate — Integration Matrix

This document tracks all ecosystem integrations and forks related to 402Gate,  
the HTTP 402 Paywall Protocol built on Solana.

> Status legend: ✅ Adopted · 🧪 Evaluating · 🟡 Optional

---

## ⚡ Payments & Settlement

| Project | Fork | Status | Why it matters | 402Gate Touchpoints |
|----------|------|--------|----------------|----------------------|
| Coinbase **x402** | N/A (PR submitted) | ✅ Adopted | Canonical HTTP 402 Payment Protocol | 402 response schema, Payment-Proof header |
| **Solana Pay** (`solana-labs/solana-pay`) | yes | 🧪 Evaluating | Merchant flows & request metadata patterns | Amount/recipient semantics, wallet UX, settlement confirmation |
| **Helius SDK** (`helius-labs/helius-sdk`) | planned | 🧪 Evaluating | RPC + webhook verification | Payment proof validation, memo parsing |
| **Open Payments** (`interledger/open-payments`) | planned | 🟡 Optional | Web monetization & receipt system | Cross-protocol compatibility |

---

## 🤖 AI & Automation

| Project | Fork | Status | Why it matters | 402Gate Touchpoints |
|----------|------|--------|----------------|----------------------|
| **Autonolas Agents** | planned | 🧪 Evaluating | AI-to-AI micropayments automation | Agent pays 402 invoice autonomously |
| **Lit Protocol SDK** | planned | 🧪 Evaluating | Encryption & key management | Secure Payment-Proof headers |

---

## 🌐 Developer Experience

| Project | Fork | Status | Why it matters | 402Gate Touchpoints |
|----------|------|--------|----------------|----------------------|
| **Solana Web3.js** | planned | 🧪 Evaluating | Core Solana client SDK | Transaction building, signature verification |
| **QuickNode Paywall Demo** | planned | 🧪 Evaluating | Real-world HTTP paywall demo | Middleware design & response flow |

---

### 🔗 Links

- 🌍 Website: [https://www.402gate.com](https://www.402gate.com)
- 🧭 DApp: [https://dapps.402gate.com](https://dapps.402gate.com)
- 📘 Docs: [https://docs.402gate.com](https://docs.402gate.com)
- 💾 SDK: [https://github.com/402gate/402gate-sdk](https://github.com/402gate/402gate-sdk)
- 🧱 Core: [https://github.com/402gate/402gate-core](https://github.com/402gate/402gate-core)
- 🔗 x402 PR: [https://github.com/coinbase/x402/pull/498](https://github.com/coinbase/x402/pull/498)
