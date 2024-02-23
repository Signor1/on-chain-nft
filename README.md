# On-Chain NFT Contract

## Description

This project consists of a Solidity smart contract that implements an on-chain Non-Fungible Token (NFT). The NFT contract allows users to create unique digital assets that are indivisible and cannot be replicated. This contract utilizes the ERC721 standard for NFTs, providing a standardized interface for ownership and transfer of non-fungible tokens on the Ethereum blockchain.

## Getting Started

### Prerequisites

Before deploying the contract, make sure you have the following dependencies installed:

- Node.js
- Hardhat
- Ethereum wallet (e.g., MetaMask)

### Installing

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/on-chain-nft.git
```

2. Navigate to the project directory:

```
cd on-chain-nft
```

3. Install the required npm packages:

```
npm install
```

### Deploying the Contract

1. Configure your Ethereum wallet provider in the `hardhat.config.js` file.

2. Write your NFT contract in the `contracts` directory or use the provided example.

3. Compile the contracts:

```
npx hardhat compile
```

4. Deploy the contract to the desired Ethereum network:

```
npx hardhat run scripts/deploy.js --network <network-name>
```

Replace `<network-name>` with the desired network (e.g., `rinkeby`, `mainnet`).

## Usage

Once the contract is deployed, users can interact with it through various actions, including:

- Minting new NFTs
- Transferring ownership of NFTs
- Viewing NFT metadata

## Help

If you encounter any issues or have questions about using the on-chain NFT contract, you can refer to the Solidity documentation, Hardhat documentation, or seek assistance from the Ethereum development community.

## Authors

- Contact [emmanuelomemgboji@gmail.com](mailto:emmanuelomemgboji@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.