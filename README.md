# :lock: :key: MultiToken MultiSig Wallet

A MultiSigWallet with ERC20 Support. This repository contains a **MultiSigWallet** smart contract with support for **ERC20** tokens, developed using **Foundry** and **Solidity 0.8.13**. The smart contract allows multiple owners to manage a wallet with a required quorum for executing transactions, including transfers of ERC20 tokens.

## :wrench: Development Tools

- **Solidity**: I've used Solidity version **0.8.13** to write the smart contracts in this repository.
- **Foundry**: a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.

## :open_file_folder: Repository Structure

- `src/`: Contains the MultiSigWallet and MockToken smart contracts.
- `tests/`: Contains the test suite for the smart contracts using Foundry.

## :rocket: Getting Started

1. Clone this repository. `git clone https://github.com/0xValerius/multitoken-multisig-wallet.git`
2. Compile the smart contracts. `forge build`
3. Run the test suite. `forge test`

## :scroll: License

[MIT](https://choosealicense.com/licenses/mit/)
