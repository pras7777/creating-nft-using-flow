# creating-nft-using-flow
The CrytoPoops smart contract is a simple implementation of a non-fungible token (NFT) collection using the Cadence programming language on the Flow blockchain.

## Features
NFT Minting: Create unique NFTs with distinct properties.
NFT Collection: Manage ownership of NFTs within a collection.
Deposit and Withdrawal: Interact with the NFT collection through depositing and withdrawing NFTs.
Public Interface: Publicly accessible functions for NFT deposit, retrieval, and borrowing.
## Smart Contract Components
### NFT Resource
The NFT resource represents a unique non-fungible token with specific properties such as a name, favorite food, and lucky number.

### Collection Resource
The Collection resource acts as a provider, receiver, and public interface for managing NFTs. It includes functions for depositing, withdrawing, and retrieving NFTs.

### MintingFacility Resource
The MintingFacility resource provides functions for creating new NFTs and minting facilities.

### Usage
1.Minting NFTs: Use the MintingFacility resource to create new NFTs.

2.Creating Collections: Create an empty NFT collection using the createEmptyNFTCollection function.

3.Depositing and Withdrawing: Interact with the NFT collection by depositing and withdrawing NFTs.

4.Public Interface: Utilize the public interface to access functions for NFT deposit, retrieval, and borrowing.

### Getting Started
1.Install the required dependencies for Cadence development.

2.Deploy the smart contract to the Flow blockchain.

3.Interact with the smart contract using the provided functions.
