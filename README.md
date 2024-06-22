# DeFi Kingdom Clone on Avalanche Network

## Introduction

This repository provides a guide and resources to help you set up a custom EVM subnet on the Avalanche network, define your own native currency, connect to Metamask, and deploy the basic building blocks for your DeFi Kingdom clone. Follow the steps below to get started.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js
- NPM (Node Package Manager)
- Metamask (browser extension)
- Solidity (for writing smart contracts)
- Remix (IDE for Solidity)

## Setting Up Your EVM Subnet

1. **Follow the Guide**:
   Use our guide and the Avalanche documentation to create a custom EVM subnet on the Avalanche network. Refer to the `docs/setup-evm-subnet.md` file for detailed instructions.

2. **Configure Your Subnet**:
   Define the parameters for your EVM subnet such as gas limits, fee structure, and validator settings as described in the guide.

## Defining Your Native Currency

1. **Create Your Currency**:
   Define your own native currency which will be used as the in-game currency for your DeFi Kingdom clone. Follow the steps in `docs/define-native-currency.md` to set this up.

2. **Deployment**:
   Deploy your native currency smart contract on your custom EVM subnet.

## Connecting to Metamask

1. **Connect EVM Subnet to Metamask**:
   Follow the steps laid out in `docs/connect-to-metamask.md` to connect your EVM subnet to Metamask. This will allow you to interact with your subnet using Metamask.

2. **Network Configuration**:
   Add your custom network configuration to Metamask, including the RPC URL, chain ID, and currency symbol.

## Deploying Basic Building Blocks

1. **Writing Smart Contracts**:
   Use Solidity and Remix to write the smart contracts for your game's basic building blocks. These include contracts for battling, exploring, trading, liquidity pools, and tokens.

2. **Deploying Contracts**:
   Deploy the smart contracts on your custom EVM subnet. Refer to the `contracts` directory for sample contracts and `docs/deploy-contracts.md` for deployment instructions.

## Additional Resources

- [Avalanche Documentation](https://docs.avax.network/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [Remix IDE](https://remix.ethereum.org/)

## Contributing

We welcome contributions to improve this guide and the resources provided. Please submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Happy building! If you have any questions or need further assistance, feel free to open an issue or contact the maintainers.
