# Ethereum Multisig Wallet

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Truffle](https://img.shields.io/badge/Truffle-3FE0C5?style=for-the-badge&logo=truffle&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)

Ethereum multisignature wallet smart contract that requires a quorum of signatures to approve transactions. Written in Solidity and deployed using Truffle to Ethereum test networks.

[🚀 Live Demo](https://determined-aryabhata-3079aa.netlify.app/)

## Features

- **Multisignature Support**: Requires multiple signatures to approve transactions
- **Quorum-Based**: Configurable quorum threshold for transaction approval
- **Secure**: Smart contract-based wallet for enhanced security
- **Truffle Deployment**: Easy deployment to test networks

## Tech Stack

- **Smart Contracts**: Solidity
- **Deployment**: Truffle
- **Network**: Ethereum (Kovan testnet)
- **Frontend**: JavaScript/React

## Installation

```bash
git clone https://github.com/arthur-zhuk/eth-multisig-wallet.git
cd eth-multisig-wallet
npm install
```

## Usage

### Compile Contracts

```bash
truffle compile
```

### Deploy to Test Network

```bash
truffle migrate --network kovan
```

### Run Tests

```bash
truffle test
```

## Smart Contract Features

- Multiple owner support
- Configurable quorum threshold
- Transaction proposal and approval system
- Secure execution of approved transactions

## Development

```bash
truffle compile  # Compile smart contracts
truffle migrate  # Deploy contracts
truffle test     # Run test suite
```

## License

MIT
