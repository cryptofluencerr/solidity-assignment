# NFTStaker

### NFTStaker is a smart contract that allows users to stake NFTs and earn rewards in the form of ERC20 tokens.

## Features:

1. Stake ERC721 NFTs
2. Earn ERC20 rewards per block
3. Unstake NFTs with an unbonding period
4. Claim accumulated rewards with a delay period
5. Upgradeable contract

## Benefits:

1. Users can earn rewards for holding NFTs
2. Project owners can incentivize NFT holding

## Getting Started:

1. Fork the project
2. Clone the project
3. Deploy the contract with the desired reward parameters, given below
4. yarn/npm install to install all the dependencies
5. Add KEY (private key), BSC_SCAN_TESTNET_API (api-key from bscTestnet), BSC_SCAN_TESTNET_URL (api url) all inside .env file
6. Deploying Contract: npx hardhat run scripts/deploy.js
7. Verifying Contract: npx hardhat verify <Contract-Address>
8. Testing: npx hardhat test
