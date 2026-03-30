<p align="center">
  <img src="./.github/SurgeLogoOnly.svg" width="80" alt="Surge Logo" />
</p>

<h1 align="center">
  Surge Rollup
</h1>

Surge is a high-performance, rollup framework built on a modified Taiko Alethia stack, aligning with Ethereum's principles of decentralization and security and featuring realtime proving, synchronous composability, Gigagas performance, and Stage 2 trustless security.

Learn more at https://www.surge.wtf or check out the official docs at https://docs.surge.wtf.

The core codebase for Surge resides in the [Surge Taiko Mono](https://github.com/NethermindEth/surge-taiko-mono) repository, while other repositories provide supporting tools, libraries, and documentation to facilitate development and deployment.

- [Surge Taiko Mono](https://github.com/NethermindEth/surge-taiko-mono): Monorepo containing the codebase for the Surge Rollup, built on the Taiko stack.
- [Nethermind](https://github.com/NethermindEth/nethermind): The Nethermind execution client.
- [Raiko](https://github.com/NethermindEth/raiko): Surge's prover client.
- [Surge Documentation](https://github.com/NethermindEth/surge-docs): Comprehensive documentation for Surge, including setup guides and technical details.
- [Simple Surge Node](https://github.com/NethermindEth/simple-surge-node): A simplified presetup docker compose of a Surge node for developers.
- [Alethia Reth](https://github.com/NethermindEth/alethia-reth): A high-performance Rust execution client for the Surge framework.

Previously used repositories:

- [SP1](https://github.com/NethermindEth/sp1): SP1 prover for Surge.

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
| **Interop with the base layer (Composability)**                                                   | 🚧 Done          |
| **Delayed Inbox for Censorship Resistance**                                                       | ✅ Done          |
| **Realtime ZK Proving**                                                                           | ✅ Done          |
| **Add Cancun and Prague EIPs support**                                                            | 🔜 To Do         |

### Milestone 3: Surge Power-Ups Plus

| Feature                                                                                           | Status           |
|---------------------------------------------------------------------------------------------------|------------------|
| **Proof Aggregation**                                                                             | ✅ Done          |
| **Nethermind TDX Prover**                                                                         | ✅ Done          |
