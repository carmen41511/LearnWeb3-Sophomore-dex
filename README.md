# Build my own decentralized exchange like Uniswap v1

This project is to build a decentralized exchange (DEX) smart contract implementation based on the Uniswap v1 model. This allows users to swap ETH for ERC20 tokens by adding/removing liquidity.

## Technologies
- Solidity - For smart contract development
- Hardhat - For Ethereum development environment
- OpenZeppelin - For ERC20 token implementation
- Ethers.js - For interacting with Ethereum node

## Contracts
- Token.sol - Basic ERC20 token contract
- Exchange.sol - Core exchange contract implementing add/remove liquidity and swap functions


## Featured Functionality
- Add liquidity - Deposit ETH and tokens to trading pool, mint, issue, and receive LP tokens
- Remove liquidity - Burn LP tokens to claim deposited assets back
- Swap ETH for tokens - Perform exchange by paying a 0.5% fee
- Swap tokens for ETH - Perform exchange by paying a 0.5% fee
- View reserves - See balance of ETH and tokens in the pool

## Usage
The deployed contracts can be interacted with directly on Etherscan. A frontend application is in progress to facilitate nicer UX. Stay tuned for updates!

