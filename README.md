# Foundry Fund Me

A simple crowdfunding smart contract project built with Solidity and Foundry.

## Overview

FundMe allows users to fund a smart contract with ETH. The contract uses a Chainlink price feed to calculate the USD value of ETH contributions and enforces a minimum funding amount.

The contract owner can withdraw the funds after they have been deposited.

## Features

- Accept ETH contributions.
- Use a Chainlink price feed to calculate contribution values in USD.
- Enforce a minimum contribution value of $5.
- Track funders and their contributions.
- Allow only the contract owner to withdraw funds.
- Include unit and integration tests.

## Tech Stack

- Solidity
- Foundry (Forge)
- Chainlink Price Feeds
- Ethereum and zkSync testnet development

## Testing

Run the test suite with:

```bash
forge test
```

Build the contracts and check their sizes with:

```bash
forge build --sizes
```

All 12 tests passed in the local test run.

## Purpose

This project was built as part of my journey learning Solidity and smart contract development. It covers basic contract development, external price feed integration, deployment scripts, and testing.

## Disclaimer

This project is for educational purposes only. It has not been audited and should not be used to manage real funds.