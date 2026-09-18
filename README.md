# FUEL Protocol — Backup Site

**Decentralized backup** of the official FUEL Protocol frontend.  
This static site runs on both **IPFS** and **GitHub Pages**.

Created by [Trevon James](https://x.com/TrVon) as part of the MORE / FUEL ecosystem on **Robinhood Chain**.

---

## Live Links

| Location          | URL |
|-------------------|-----|
| **IPFS**          | [https://bafybeigobv4743bxmcbwisf3be45owlmrmoobx3xjh5jw7tvu7bd4mhbey.ipfs.inbrowser.link/](https://bafybeigobv4743bxmcbwisf3be45owlmrmoobx3xjh5jw7tvu7bd4mhbey.ipfs.inbrowser.link/) |
| **GitHub Pages**  | [https://axelcalloway.github.io/fuel-protocol-backup/](https://axelcalloway.github.io/fuel-protocol-backup/) |
| **Original Site** | [https://app.fuelmoretokens.com/](https://app.fuelmoretokens.com/) |
| **MORE Website**  | [https://app.moretokens.com/](https://app.moretokens.com/) |

> This repository is an independent backup. Always prefer the official site when it is available.

---

## What is FUEL Protocol?

FUEL is a minting, claiming, staking and burn protocol on **Robinhood Chain** (Chain ID `4663`).

Users can:
- **Mint** ranks (solo or in batches of up to 100)
- **Claim** matured mint rewards
- **Stake** $FUEL for APY
- Interact with the **Mint Vault**, **Buy & Burn**, and **MORE Burner** fee pools

---

## Features in this frontend

- Dashboard with live protocol stats
- Mint (single or batch)
- Claim solo rewards + batch proxy claims
- Claim & Share / Claim & Stake
- Stake / Withdraw
- Vault sweep + Buy & Burn actions
- Fully client-side (ethers.js v6)
- Works with any injected wallet (MetaMask, Rabby, etc.)

---

## Network

| Parameter     | Value |
|---------------|-------|
| Network       | Robinhood Chain |
| Chain ID      | `4663` |
| Native Gas    | ETH |
| Explorer      | [robinhoodchain.blockscout.com](https://robinhoodchain.blockscout.com) |

---

## Contract Addresses

| Contract            | Address |
|---------------------|---------|
| **FUEL Token**      | `0xe60C1F5d9bA7f62a392a78472a3Ab83DD62467A3` |
| **BatchMinter**     | `0xEaB771dB3883dC05DbEA1915F7e81910869bbc18` |
| **Mint Vault**      | `0x492d111487f097759340dc119DE5887d58c38bB0` |
| **Buy & Burn**      | `0x1f8e137117f78ef1ea84235f3e5423c46bf2d4a2` |
| **MORE Burner**     | `0x86f11A15E1793e7ce1F4264830d1973e80339A51` |
| **Fee Distributor** | `0x2f69ff61802d9738e562e438d1f6326389d95861` |
| **WETH**            | `0x0Bd7D308f8E1639FAb988df18A8011f41EAcAD73` |

Donation address: `0x33cD0CE479D33aa4dEc5E2b3f3A4683A561a50e5`

Full address list is also available in the [`contracts/`](./contracts/) and [`addresses/`](./addresses/) folders.

---

## How to use

1. Open the site (IPFS or GitHub Pages)
2. Click **Connect Wallet**
3. Switch to **Robinhood Chain** (4663) if prompted
4. Use the sidebar to navigate:
   - **Dashboard** → live stats
   - **Mint** → open new ranks
   - **Claim** → claim rewards / remint
   - **Stake** → stake or withdraw $FUEL
   - **Burns & Vault** → trigger buy-and-burn or vault sweep

---

## Socials & Creator

- **Creator**: [Trevon James (@TrVon)](https://x.com/TrVon)
- **Telegram**: [t.me/buymoretoken](https://t.me/buymoretoken)
- **Original FUEL site**: [app.fuelmoretokens.com](https://app.fuelmoretokens.com/)
- **MORE ecosystem**: [app.moretokens.com](https://app.moretokens.com/)

---

## Repository Structure

```
fuel-protocol-backup/
├── index.html              # Full static frontend
├── favicon.png
├── fuel_logo_200x200.png
├── contracts/              # Contract addresses
├── addresses/              # Additional address references
└── README.md
```

---

## Why this backup exists

- The official site is the primary interface.
- This repo keeps a permanent, censor-resistant copy on **IPFS** and a simple, always-available mirror on **GitHub Pages**.
- Anyone can pin the IPFS CID or fork this repository.

**IPFS CID**: `bafybeigobv4743bxmcbwisf3be45owlmrmoobx3xjh5jw7tvu7bd4mhbey`

---

## Disclaimer

This is an unofficial backup of a community protocol.  
Always double-check contract addresses and the official sources before sending transactions.  
Interact at your own risk.

---

**FUEL Protocol** · Robinhood Chain · Built by Trevon James
```
