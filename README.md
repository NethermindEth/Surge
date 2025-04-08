<p align="center">
  <img src="./.github/SurgeLogoOnly.svg" width="80" alt="Logo for Surge" />
</p>

<h1 align="center">
  Surge Rollup
</h1>

<p align="center">
  A based rollup template of the Taiko Alethia stack.
</p>

# Surge Rollup

Surge is a high-performance, based rollup template built on a modified Taiko stack, aligning with Ethereum's principles of decentralization and security. 

Learn more at https://www.surge.wtf or check out the official docs at https://docs.surge.wtf.

## What is this repo?

This repository holds essential configuration files for different Surge testnets. These files define the network parameters and initial states for each testnet, providing the foundation upon which Surge operates. 

The entire codebase for Surge is located in the [Surge Taiko Mono](https://github.com/NethermindEth/surge-taiko-mono) repository.

## Repository Links

- [Surge Taiko Mono](https://github.com/NethermindEth/surge-taiko-mono): Monorepo containing the codebase for the Surge Rollup, built on the Taiko stack.
- [Nethermind](https://github.com/NethermindEth/nethermind): The Nethermind execution client.
- [Raiko](https://github.com/NethermindEth/raiko): Surge's prover client.
- [Surge Documentation](https://github.com/NethermindEth/surge-docs): Comprehensive documentation for Surge, including setup guides and technical details.
- [Simple Surge Node](https://github.com/NethermindEth/simple-surge-node): A simplified presetup docker compose of a Surge node for developers.
- [Surge Devnet Package](https://github.com/NethermindEth/surge-devnet-package): A kurtosis package to help set up a devnet for a Surge L2.
- [SP1](https://github.com/NethermindEth/sp1): SP1 prover for Surge.

Supporting libraries:
- [Surge Reth](https://github.com/NethermindEth/surge-reth): Surge integration with the Reth execution client.
- [Surge Geth](https://github.com/NethermindEth/surge-geth): Surge integration with the Geth execution client.

## Roadmap

### Milestone 1: Vanilla Surge Template

| Feature                                                  | Status           |
|----------------------------------------------------------|------------------|
| **Stage2 protocol design**                               | ✅ Done          |
| **Nethermind Client support**                            | ✅ Done          |
| **Use Eth as bond**                                      | ✅ Done          |

### Milestone 2: Surge Power-Ups

| Feature                                                                                           | Status           |
|---------------------------------------------------------------------------------------------------|------------------|
| **Preconfirmations**                                                                              | 🚧 In Progress   |
| **Interop with the base layer (Composability)**                                                   | 🚧 In Progress   |
| **Delayed Inbox for Censorship Resistance**                                                       | 🚧 In Progress   |
| **Add Cancun and Prague EIPs support**                                                            | 🔜 To Do         |
| **Improved proving system with failure fallback mechanisms**                                      | 🔜 To Do         |

### Milestone 3: Surge Power-Ups Plus

| Feature                                                                                           | Status           |
|---------------------------------------------------------------------------------------------------|------------------|
| **Proof Aggregation**                                                                             | 🚧 In Progress   |
| **Nethermind TDX Prover**                                                                         | 🚧 In Progress   |
| **Prover Election/Auction**                                                                       | 🔜 To Do         |
| **Utilize Blob Sharing**                                                                          | 🔜 To Do         |
