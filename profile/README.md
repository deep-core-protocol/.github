<p align="center">
  <a href="https://deepcore.fun">
    <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/og-image-1200x630.png" alt="DeepCore: launch on one core. Tokens, Launchpads and DEXes at deepcore.fun" width="720">
  </a>
</p>

# DeepCore Protocol

One shared liquidity core that Launchpads and DEXes build on, instead of each deploying its own AMM:
a single Vault with concentrated-liquidity (CL) and Bin pool managers on the Infinity architecture,
the launch and DEX contracts on top of it, and the SDK, widgets and templates to ship on it.

<p>
  <b>Live on</b>&nbsp;
  <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/chains/hyperevm.svg" alt="" width="16" height="16">&nbsp;HyperEVM&nbsp;·&nbsp;
  <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/chains/bnb.svg" alt="" width="16" height="16">&nbsp;BNB Chain&nbsp;·&nbsp;
  <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/chains/robinhood.jpg" alt="" width="16" height="16">&nbsp;Robinhood Chain&nbsp;·&nbsp;
  <img src="https://raw.githubusercontent.com/deep-core-protocol/.github/main/profile/assets/chains/base.svg" alt="" width="16" height="16">&nbsp;Base
</p>

The same contract addresses on every chain, listed in the SDK address book and verified on Sourcify.

**[deepcore.fun](https://deepcore.fun)** · **[App](https://deepcore.fun/app)** · **[Docs](https://docs.deepcore.fun)**

## Features

- **Launch a token in one transaction.** On a CL range or a shaped Bin distribution, tradable on the
  real pool from the first block, with the liquidity locked forever. The launch form is
  market-cap-first, opening at a $3.5K-equivalent default priced from an on-chain feed.
- **Anti-snipe fee.** Up to 50% at the open (10% on Bin), decaying to the trade fee over at least
  60 seconds, for example 50% to 0.3%.
- **Optional creator tax.** Buy and sell rates up to 10% that expire on their own, frozen with the
  rest of the launch at the first trade.
- **Launchpads and DEXes in one transaction, on any of the four chains.** Each can take a free
  deepcore.fun subdomain or its owner's own domain, a theme pack, and its own share of the launch
  fees; owner, name, brand and terms live on chain.
- **Swap with routing.** No router fee on DeepCore pools; a trade filled on another venue pays 0.15%.
- **Locks and distribution.** Liquidity locks, token locks and vesting, Merkle airdrops, team splits
  and multisend.
- **Dynamic-fee hooks** for CL and Bin pools.
- **Every chain in one app.** Markets, launches and sites from all four chains together, each
  labelled with its chain, and a portfolio with activity from every chain.
- **For builders.** An MIT TypeScript SDK, the `SwapWidget` and other widgets, a `create-app`
  template and a `create-hook` scaffolder (on npm soon), and token lists per chain. Upkeep calls are
  permissionless, and DeepCore's keeper runs them.
- **Bounded admin.** The contracts are owned by a 2-of-3 Safe multisig. Fees and caps are immutable
  or move only behind notice delays written in the contracts; `renounceOwnership` is disabled on
  DeepCore's own contracts.

## Repositories

| Repository | What it is |
|---|---|
| [contracts](https://github.com/deep-core-protocol/contracts) | The Solidity contracts, GPL-2.0-or-later, with tests under both build profiles and the deployed addresses |
| [deep-sdk](https://github.com/deep-core-protocol/deep-sdk) | The TypeScript SDK and address book, MIT |
| [token-list](https://github.com/deep-core-protocol/token-list) | The published token lists, one file per chain |
