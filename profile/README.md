<p align="center">
  <a href="https://deepcore.fun">
    <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/og-image-1200x630.png" alt="DeepCore: launch on one core. Tokens, Launchpads and DEXes at deepcore.fun" width="720">
  </a>
</p>

# DeepCore Protocol

One shared liquidity core that Launchpads and DEXes build on, instead of each deploying its own AMM.
Site: [deepcore.fun](https://deepcore.fun)

## Features

- **One shared core.** A single Vault with concentrated-liquidity (CL) and Bin pool managers, on the
  Infinity architecture, with HyperEVM as the first chain. Every pool built on DeepCore lives in it.
- **Launchpads and DEXes in one transaction.** `DeepCorePadFactory` creates a Launchpad or DEX site
  with its owner, name and brand stored on chain.
- **Token launches.** On a CL range or a shaped Bin distribution, tradable on the real pool from the
  first block, with locked liquidity, an anti-snipe fee that decays over the opening window and an
  optional, time-limited creator tax.
- **Utilities.** Liquidity locks, token locks and vesting, multisend, Merkle airdrops and team splits.
- **For builders.** An MIT TypeScript SDK, swap widgets and a create-app template, so a Launchpad or
  DEX ships without importing GPL code.
- **Bounded admin.** Fees live inside caps fixed in the contracts; an increase takes effect only after
  a public notice period, a decrease applies at once. Governance is a multisig with a timelock.

## Repositories

| Repository | What it is |
|---|---|
| [contracts](https://github.com/deep-core-protocol/contracts) | The Solidity contracts, GPL-2.0-or-later, with tests under both build profiles |
| [deep-sdk](https://github.com/deep-core-protocol/deep-sdk) | The TypeScript SDK, MIT |
| [token-list](https://github.com/deep-core-protocol/token-list) | The published token lists, one file per chain |
