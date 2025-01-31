---
title: Celo Governance Cheat Sheet
description: List of governable parameters and governance restrictions on Celo.
slug: /celo-owner-guide/governance-cheat-sheet
---

# Governance Cheat Sheet

List of governable parameters and governance restrictions on Celo.

---

## Governable Parameters

- The stability protocol, including the exchange
- What the protocol does with data feeds from Oracles
- Adding or removing Mento stablecoins
- Whitelisting Mento stablecoins (or other ERC20s) for use in paying gas fees
- The identity protocol, including how phone number attestations works
- Linking of signers and off-chain metadata (e.g claims) to accounts
- Most of Proof of Stake protocol, including elections, locked gold, slashing parameters
- On-chain governance itself
- MinimumClientVersion
- BlockGasLimit
- IntrinsicGasForAlternativeFeeCurrency

## Things That Can't Be Modified By Governance

- The protocol by which nodes communicate
- The format of block headers, block bodies, the fields in transactions, etc
- How nodes sync
- How nodes store their data locally
- Most parameters that affect the blockchain
