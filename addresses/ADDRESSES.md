# FUEL Protocol — Contract Addresses

**Network:** Robinhood Chain  
**Chain ID:** `4663`  
**Explorer:** https://robinhoodchain.blockscout.com (or https://robin.etherscan.io)

These are the live mainnet contracts used by the official FUEL Protocol frontend.

## Core Contracts

| Name              | Address                                      | Description                          |
|-------------------|----------------------------------------------|--------------------------------------|
| **FUEL Token**    | `0xe60C1F5d9bA7f62a392a78472a3Ab83DD62467A3` | Main $FUEL ERC-20 token              |
| **BatchMinter**   | `0xEaB771dB3883dC05DbEA1915F7e81910869bbc18` | Batch minting of ranks via proxies   |
| **Mint Vault**    | `0x492d111487f097759340dc119DE5887d58c38bB0` | Collects 45% of mint fees            |
| **Buy & Burn**    | `0x1f8e137117f78ef1ea84235f3e5423c46bf2d4a2` | 25% of fees → buy & burn $FUEL       |
| **MORE Burner**   | `0x86f11A15E1793e7ce1F4264830d1973e80339A51` | 30% of fees → buy & burn $MORE       |
| **Fee Distributor**| `0x2f69ff61802d9738e562e438d1f6326389d95861` | Fee routing                          |
| **WETH**          | `0x0Bd7D308f8E1639FAb988df18A8011f41EAcAD73` | Wrapped ETH on Robinhood Chain       |

## Donation Address

`0x33cD0CE479D33aa4dEc5E2b3f3A4683A561a50e5`

## Notes

- All addresses are taken from the official frontend (`index.html`).
- Source code of the contracts is **publicly verified** on the explorer (as of the time this backup was created).
- Always verify addresses on the official site or explorer before interacting.
