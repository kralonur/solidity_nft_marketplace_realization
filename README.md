# Solidity NFT Marketplace Realization

This contract provides platform for creating ERC721 token and selling it. With the new version auction functionality also added.

With new version , you can also use ERC1155Marketplace for creating ERC1155 token and selling it. But same logic on NftMarketplace is being used so ERC1155Marketplace will create 1 token each time and sell 1 token each time (this is desired functionality and can be changed).

## Development

The contract is written with solidity.

Hardhat development environment being used to write this contract.

The test coverage is %100 for NftMarketplace,ERC1155Marketplace, ERC721WithAccessControl(result from solidity-coverage).

For linting solhint and prettier is being used.

Contract could be deployed to rinkeby testnet using infura api key and wallet private key.
Environment file has to be created to use test network and contract validation. (.env.example file contains example template)

Scripts folder contains the script for contract deployment.

For the easier contract interaction, hardhat tasks are created.
To see the list of tasks, write `npx hardhat` to the terminal.