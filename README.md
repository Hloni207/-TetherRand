# ⚡ TetherRand (USDT-to-ZAR P2P Settlement Engine)

> A high-speed, secure peer-to-peer off-ramp built for overseas entrepreneurs, digital nomads, and crypto traders looking to seamlessly convert Tether (USDT) into South African Rands (ZAR).

---

## 🎯 Problem Statement
Moving capital internationally or liquidating digital assets into local fiat currencies (ZAR) in emerging markets often involves:
* **Exorbitant Wire Fees:** Traditional bank SWIFT transfers take days and lose 5-10% to intermediary bank fees and poor forex spreads.
* **Friction for Foreign Entrepreneurs:** Non-residents struggle with local banking compliance bottlenecks when trying to pay local contractors, settle invoices, or access liquidity in South Africa.
* **The Last-Mile Gap:** Converting stablecoins to local bank accounts or mobile instant clearing (like PayShap / Capitec) lacks automated, trust-minimized escrow protection.

---

## 🚀 Key Features

* **Smart Contract Escrow:** Locks the seller's USDT automatically upon order creation, releasing funds only when local ZAR bank transfer or instant payment verification clears.
* **Instant Local Rail Integration:** Direct support for South African clearing rails, including standard EFT and instant payment routing references.
* **Targeted Peer Matching:** Automated order book matching specifically tailored for crypto traders and foreign entrepreneurs managing cross-border transactions.
* **Gas-Optimized & Multi-Chain:** Built to support low-fee transaction networks (Polygon, TRON, Solana) so users keep maximum value.
* **Real-Time Dual Pricing:** Live exchange rate ticker tracking accurate USDT/ZAR market spreads down to the second.
* **Secure Dispute Management:** Built-in resolution mechanism and merchant reputation scoring to guarantee transaction safety.

---

## 🏗️ Architecture & Tech Stack

* **Frontend:** Mobile-first responsive UI built for rapid cross-border execution.
* **Smart Contracts:** Secure escrow logic handling lock, release, and dispute states.
* **Backend & Matching Engine:** Lightweight API coordinating peer orders, transaction tracking, and rate feeds.

---

## 📋 Getting Started

### Prerequisites
* Node.js (v18+)
* Bun / npm / pnpm

### Installation

```bash
# Clone the repository
git clone [https://github.com/Hloni207/tether-rand-p2p.git](https://github.com/Hloni207/tether-rand-p2p.git)

# Navigate into project directory
cd tether-rand-p2p

# Install dependencies
bun install

# Run development server
bun run dev