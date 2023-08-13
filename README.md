# Project Title

Degen Token Redemption System

## Description

This project involves the creation of a smart contract called "UpdatedDegenToken" based on the Ethereum blockchain. The smart contract is designed to facilitate the redemption of a custom token, "UpdatedDegen" (symbol: UDGN), by users who hold a sufficient balance of these tokens. The main purpose of the contract is to provide a mechanism for users to redeem a specific option by burning a set amount of tokens. The contract also includes functions for minting new tokens, transferring tokens, checking token balances, and burning tokens.

## Getting Started

### Installing

To use the smart contract, follow these steps:

1. Download the necessary dependencies, such as the OpenZeppelin contracts, and any other requirements.
2. Make any required modifications to the smart contract code or configuration files.

### Executing program

To run the smart contract, perform the following steps:

1. Deploy the `UpdatedDegenToken` smart contract to the Ethereum blockchain.
2. Use the provided functions to interact with the contract, such as minting tokens, transferring tokens, checking balances, and redeeming tokens based on specific options.

Example commands for interacting with the smart contract:
```solidity
// Mint tokens to an address (only the contract owner can do this)
mintTokens(address to, uint256 amount);

// Transfer tokens to another address
transfer(address to, uint256 amount);

// Get the token balance of the caller
getBalance();

// Redeem tokens for a specific option (requires a sufficient token balance)
redeemTokens(uint chosenOption);

// Burn a specific amount of tokens
burnTokens(uint amount);
```

## Help

If you encounter any common problems or issues while using the smart contract, refer to the contract's source code or consult the documentation for the functions and their usage.

## Authors

[Aryan Singh]
- GitHub: https://github.com/aryansingh186
- Email: 22bcs80186@cuchd.in

## License

This project is licensed under the MIT [LICENSE]
