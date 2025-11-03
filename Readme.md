# BRINGOLD (BRIN) — Jetton on TON

> This token was minted via **TON Minter** using the **Jetton standard (TEP‑74)** with **no custom logic modifications**.

---

## Overview

* **Name:** BRINGOLD
* **Symbol:** BRIN
* **Standard:** Jetton (**TEP‑74**)
* **Network:** TON Mainnet
* **Decimals:** `9`
* **Mintable:** `false`
* **Max supply:** `905,989,000 BRIN`

BRINGOLD is a multifunctional blockchain platform based on DAO principles. The ecosystem covers GameFi, DeFi, SocialFi, and education, aiming to build a universal Web3/metaverse space.

## Contract Addresses

* **Jetton master (base64 / bounceable):** `EQAQfNrwhA5sEywrLTtsxpyQFeKRfEpLdZREZILP9z9iUjAH`
* **Jetton master (hex / raw):** `0:107cdaf0840e6c132c2b2d3b6cc69c9015e2917c4a4b7594446482cff73f6252`
* **Contract type:** `jetton_master`

> Jetton wallet addresses are user‑specific and derived by the standard wallet code of TEP‑74.

## Explorers / Verification

* **Tonscan (Jetton):** [https://tonscan.org/jetton/EQAQfNrwhA5sEywrLTtsxpyQFeKRfEpLdZREZILP9z9iUjAH](https://tonscan.org/jetton/EQAQfNrwhA5sEywrLTtsxpyQFeKRfEpLdZREZILP9z9iUjAH)
* **Tonviewer (address):** [https://tonviewer.com/EQAQfNrwhA5sEywrLTtsxpyQFeKRfEpLdZREZILP9z9iUjAH](https://tonviewer.com/EQAQfNrwhA5sEywrLTtsxpyQFeKRfEpLdZREZILP9z9iUjAH)

## Token Metadata (on‑chain/off‑chain fields)

```json
{
  "address": "0:107cdaf0840e6c132c2b2d3b6cc69c9015e2917c4a4b7594446482cff73f6252",
  "name": "BRINGOLD",
  "symbol": "BRIN",
  "decimals": "9",
  "image": "https://i.ibb.co/vvLQjCqk/brin-logo.png",
  "description": "BRINGOLD is a multifunctional blockchain platform based on DAO principles. The ecosystem covers GameFi, DeFi, SocialFi and education, aiming to build a universal Web3/metaverse space.",
  "social": [
    "https://t.me/Bringold_io",
    "https://twitter.com/Bringold_io"
  ],
  "websites": [
    "https://bringold.io"
  ]
}
```

## Source Code

This token uses the **canonical Jetton contracts** (TEP‑74) as deployed by **TON Minter** with default logic.

* **Jetton standard (TEP‑74):** [https://github.com/ton-blockchain/TEPs/blob/master/text/0074-jettons-standard.md](https://github.com/ton-blockchain/TEPs/blob/master/text/0074-jettons-standard.md)
* **Reference contracts / deployer (examples):** [https://github.com/ton-blockchain/minter-contract](https://github.com/ton-blockchain/minter-contract)

> There is **no custom contract code** beyond the standard Jetton master & wallet implementations. This repository serves as a public reference for reviewers (CMC/exchanges) with links, parameters, and proofs.

## Parameters & Invariants

* **Symbol/Name/Decimals** fixed at deploy.
* **Mintability:** `false` (no further supply increase).
* **Max supply:** `905,989,000` BRIN.

## Supply & Mintability Notes

* "Max supply" reflects the configured total supply at deployment.
* With `mintable = false`, no additional tokens can be minted via the standard Jetton minter functions.

## Project Links

* **Website:** [https://bringold.io](https://bringold.io)
* **Telegram:** [https://t.me/Bringold_io](https://t.me/Bringold_io)
* **Twitter/X:** [https://twitter.com/Bringold_io](https://twitter.com/Bringold_io)

