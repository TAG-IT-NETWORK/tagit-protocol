# oracular-protocol

This repository contains the core smart contracts for the **Tagit Network**. It is built using the [Foundry](https://book.getfoundry.sh/) toolkit. The repository is organized into modules to support a modular, upgradeable protocol.

## Directory structure

- `contracts/AssetNFT/` – Implementation for the asset NFT standard.
- `contracts/Transfer/` – Contracts for transfers and custody.
- `contracts/Verification/` – Proof verification and KYC logic.
- `contracts/RecoveryFlag/` – Recovery flag management.
- `contracts/DAO/` – Governance modules and timelocks.
- `contracts/Rewards/` – Token rewards and incentives.
- `contracts/Customs/` – Customs modules for import/export flows.
- `contracts/Recall/` – Recall functionality.
- `contracts/interfaces/` – Shared interfaces for cross-module interaction.
- `contracts/libs/` – Library code and shared utilities.
- `script/` – Deployment and upgrade scripts.
- `test/` – Unit and integration tests.
- `deployments/` – Deployment artifacts and chain-specific addresses.

## Getting started

1. Install Foundry via `curl -L https://foundry.paradigm.xyz | bash` and run `foundryup`.
2. Install dependencies: `forge install`.
3. Build the contracts: `forge build`.
4. Run tests: `forge test`.

This is an initial skeleton; please flesh out each module with proper implementations, tests, and docs.
