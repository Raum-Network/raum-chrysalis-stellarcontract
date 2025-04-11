# 🌱 Chrysalis Core

**Chrysalis** is a liquid staking platform designed to simplify and enhance the staking experience across multiple blockchains. Users can stake both native tokens and stablecoins to earn higher yields while maintaining liquidity—without the technical complexities typically associated with staking.

> ⚠️ **Note:** This repository is a **Proof of Concept (POC)**. The integration with Lido is currently **in progress**, and the system will be deployed to testnet after further development and testing.

---

## ✨ Key Highlights

- **Liquid staking across chains**
- **Stake native tokens and stablecoins**
- **Earn higher APYs via Ethereum-based staking protocols**
- **Maintain liquidity with wrapped staking tokens**
- **Simple, user-friendly staking interface**

---

## 🌐 Current Integrations

### ✅ Polygon Amoy Testnet (Early Access)

Currently, Chrysalis is integrated with **Lido** on the **Ethereum blockchain**, accessible via the Polygon Amoy testnet.

### 🚧 Upcoming Integrations

Chrysalis is actively working to integrate with additional leading staking protocols:
- RocketPool
- Mantle
- Swell
- Eigenlayer (for re-staking)
- And more...

---

## 💡 Why Chrysalis?

Chrysalis is built with **simplicity** and **accessibility** at its core:

- A unified staking interface across chains
- Stake without technical overhead
- Liquidity-preserving staking tokens (e.g., wstETH)
- Future-ready with re-staking capabilities and multiple L1/L2 support

---

## ⭐ Stellar Integration: High-Speed, Cross-Chain Staking

Chrysalis brings liquid staking to the **Stellar blockchain**, allowing users to stake native Stellar assets like **XLM** while earning Ethereum-based staking yields.

### Key Features:
- **Stellar-Native Staking** – Stake XLM and other Stellar-native assets without leaving the ecosystem.
- **Cross-Chain Yields** – Earn Ethereum staking rewards (e.g., **stETH**) bridged securely via Allbridge.
- **DeFi-Ready Liquidity** – Receive wrapped stETH (**wstETH**) or stETH (**stETH**)  on Stellar for use in decentralized finance protocols.

---

## 💪 Core Technical Components

### 1. Liquid Staking (Lido – In Progress)

- Chrysalis will deploy liquidity to **Lido on Ethereum**.
- **stETH tokens** obtained from staking will be bridged to Stellar.
- Users on Stellar will receive **wrapped stETH (wstETH) or stETH (stETH)** representing their staking position and rewards.

### 2. Soroban Smart Contracts

Built on the Stellar Soroban VM, the core contract:
- Manages minting and redemption of wrapped stETH tokens
- Tracks user staking and reward claims
- Ensures transparency and security in cross-chain asset flow

### 3. Bridge Integration (Allbridge)

- **Allbridge** enables seamless cross-chain transfers between **Ethereum** and **Stellar**
- A dedicated **testnet bridge** is already available for use:
  👉 [Testnet Bridge Interface](https://allbridge-debug.web.app/bridge?from=HOL&to=XLM&asset=stETH)

---

## 🔭 Roadmap

- ✅ Testnet bridge via Allbridge (live)
- 💧 Lido integration (in progress)
- 🔄 Wrapped stETH smart contract (development phase)
- 🔬 End-to-end testing on testnet
- 🚀 Full deployment on Stellar + Ethereum testnets

---

## 📌 Disclaimer

> This repository represents a **Proof of Concept**. Expect rapid iteration, structural changes, and new feature additions as we move toward production readiness.

---

## 🤝 Get Involved

Interested in contributing or collaborating? We'd love to hear from you. Reach out via GitHub or [join our community](#) (link to community if available).

