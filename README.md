# FUEL & MORE Protocol — Backup Sites

**Decentralized backups** of the official FUEL Protocol and MORE Protocol frontends on **Robinhood Chain**.  
These static sites run on both **IPFS** and **GitHub Pages**.

Created by [Trevon James](https://x.com/TrVon) as part of the MORE / FUEL ecosystem.

---

## Live Links

### FUEL Protocol Backup

| Location | URL |
|----------|-----|
| **IPFS** | [https://bafybeienye5rr6kdembxqirreosridy5rm2ywpfqlhgxrzhfolekpnxwbi.ipfs.inbrowser.link/](https://bafybeienye5rr6kdembxqirreosridy5rm2ywpfqlhgxrzhfolekpnxwbi.ipfs.inbrowser.link/) |
| **GitHub Pages** | [https://axelcalloway.github.io/fuel-protocol-backup/](https://axelcalloway.github.io/fuel-protocol-backup/) |
| **Original Site** | [https://app.fuelmoretokens.com/](https://app.fuelmoretokens.com/) |

**IPFS CID (FUEL):** `bafybeienye5rr6kdembxqirreosridy5rm2ywpfqlhgxrzhfolekpnxwbi`

### MORE Protocol Backup

| Location | URL |
|----------|-----|
| **IPFS** | [https://bafybeih67fiad25swwftx55bydrmsh3rpzzjniuor3tdlyinyzfpkbvrwy.ipfs.inbrowser.link/](https://bafybeih67fiad25swwftx55bydrmsh3rpzzjniuor3tdlyinyzfpkbvrwy.ipfs.inbrowser.link/) |
| **GitHub Pages** | [https://axelcalloway.github.io/fuel-protocol-backup/more.html](https://axelcalloway.github.io/fuel-protocol-backup/more.html) |
| **Original Site** | [https://app.moretokens.com/](https://app.moretokens.com/) |

**IPFS CID (MORE):** `bafybeih67fiad25swwftx55bydrmsh3rpzzjniuor3tdlyinyzfpkbvrwy`

> This repository is an independent backup. Always prefer the official sites when they are available.

---

## What is FUEL Protocol?

FUEL is a minting, claiming, staking and burn protocol on **Robinhood Chain** (Chain ID `4663`).

Users can:
- **Mint** ranks (solo or in batches of up to 100)
- **Claim** matured mint rewards
- **Stake** $FUEL for APY — either a single native stake, or **unlimited concurrent stakes via multi-stake NFTs** (each stake mints a tradeable FSTAKE NFT, so there's no cap on how many open positions a wallet can hold)
- Interact with the **Mint Vault**, **Buy & Burn**, and **MORE Burner** fee pools

### FUEL frontend features
- Dashboard with live protocol stats
- Mint (single or batch)
- Claim solo rewards + batch proxy claims
- Claim & Share / Claim & Stake
- Native Stake / Withdraw
- **Multi-stake via NFTs** — create as many simultaneous stakes as you want, each represented by its own FSTAKE NFT, with a per-wallet position list and one-click unstake per NFT
- Vault sweep + Buy & Burn actions
- Fully client-side (ethers.js v6)
- Works with any injected wallet (MetaMask, Rabby, etc.)

---

## What is MORE Protocol?

MORE is a penalty-based staking protocol on **Robinhood Chain**. There is **no fixed APR** — rewards come only from early/late exit penalties of other stakers, which are recycled 100% into the reward pool.

Users can:
- **Stake** $MORE for a chosen duration (1–5555 days)
- **Unstake** (with early or late penalties when applicable)
- View active positions, earned rewards, and protocol stats

### MORE frontend features
- Dashboard with total staked, active stakes, unique stakers, total distributed
- Stake form (amount + duration)
- Your Stakes list with per-position unstake
- Penalty mechanics documented on-page
- Fully client-side (ethers.js v6)
- Works with any injected wallet

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

### FUEL

| Contract              | Address |
|------------------------|---------|
| **FUEL Token**         | `0xe60C1F5d9bA7f62a392a78472a3Ab83DD62467A3` |
| **BatchMinter**        | `0xEaB771dB3883dC05DbEA1915F7e81910869bbc18` |
| **Mint Vault**         | `0x492d111487f097759340dc119DE5887d58c38bB0` |
| **Buy & Burn**         | `0x1f8e137117f78ef1ea84235f3e5423c46bf2d4a2` |
| **MORE Burner**        | `0x86f11A15E1793e7ce1F4264830d1973e80339A51` |
| **Fee Distributor**    | `0x2f69ff61802d9738e562e438d1f6326389d95861` |
| **WETH**               | `0x0Bd7D308f8E1639FAb988df18A8011f41EAcAD73` |
| **FStake**    | `0x6060acC907dE482a42fFA5AED51c72021e7579e1` |

### MORE

| Contract            | Address |
|---------------------|---------|
| **MORE Token**      | `0xc0F1A40512114b25cc1F30b5DF0bb48691405555` |
| **Staking**         | `0xCC22e7f65bEF29aa21f6F59b9363fdc26005dE31` |
| **MORE Burner**     | `0x86f11A15E1793e7ce1F4264830d1973e80339A51` |

Donation address (shared): `0x33cD0CE479D33aa4dEc5E2b3f3A4683A561a50e5`

Full address lists are also available in the [`contracts/`](./contracts/) and [`addresses/`](./addresses/) folders.

---

## How to use

1. Open the site (IPFS or GitHub Pages)
2. Click **Connect Wallet**
3. Switch to **Robinhood Chain** (4663) if prompted
4. Navigate with the sidebar

**FUEL pages:** Dashboard · Mint · Claim · Stake (native + unlimited multi-stake NFTs) · Burns & Vault  

**MORE pages:** Dashboard · Stake · Your Stakes · Burns  

---

## Socials & Creator

- **Creator**: [Trevon James (@TrVon)](https://x.com/TrVon)
- **Telegram**: [t.me/buymoretoken](https://t.me/buymoretoken)
- **Original FUEL site**: [app.fuelmoretokens.com](https://app.fuelmoretokens.com/)
- **Original MORE site**: [app.moretokens.com](https://app.moretokens.com/)

---

## Repository Structure

```
fuel-protocol-backup/
├── index.html              # FUEL Protocol frontend
├── more.html               # MORE Protocol frontend
├── favicon.png              # FUEL favicon
├── favicon_more.png         # MORE favicon
├── fuel_logo_200x200.png
├── more_logo_200x200.png
├── contracts/               # Contract addresses
├── addresses/                # Additional address references
└── README.md
```

---

## Why these backups exist

- The official sites are the primary interfaces.
- This repo keeps permanent, censor-resistant copies on **IPFS** and simple, always-available mirrors on **GitHub Pages**.
- Anyone can pin the IPFS CIDs or fork this repository.

| Site | IPFS CID |
|------|----------|
| FUEL | `bafybeienye5rr6kdembxqirreosridy5rm2ywpfqlhgxrzhfolekpnxwbi` |
| MORE | `bafybeih67fiad25swwftx55bydrmsh3rpzzjniuor3tdlyinyzfpkbvrwy` |

---

## Disclaimer

These are unofficial backups of community protocols.  
Always double-check contract addresses and the official sources before sending transactions.  
Interact at your own risk.

---

**FUEL Protocol** · **MORE Protocol** · Robinhood Chain · Built by Trevon James
