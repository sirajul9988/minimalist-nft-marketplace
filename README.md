# Minimalist NFT Marketplace

A professional-grade, "flat" repository containing a Solidity smart contract for a decentralized NFT marketplace. This project demonstrates how to handle secondary sales, escrow-less listings, and secure ether transfers on-chain.

## Features
* **ERC-721 Integration**: Native support for OpenZeppelin's URI storage.
* **Escrow-Less Listings**: NFTs remain in the owner's wallet until the moment of sale.
* **Fixed Price Sales**: Simple logic for listing and purchasing digital assets.
* **Security First**: Reentrancy protection and ownership controls included.

## How to Use
1. Deploy `Marketplace.sol` to a testnet (Sepolia or Polygon Amoy).
2. Mint an NFT using the `createToken` function.
3. List the token by calling `listMarketItem` with a price in Wei.
4. Another user can call `createMarketSale` to purchase and instantly transfer ownership.

## License
MIT
