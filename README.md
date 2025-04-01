# scavengerSmartContract
# Scavenger Hunt NFT

## Overview

This smart contract implements a blockchain-based scavenger hunt where a winner is selected and rewarded with an NFT. The contract ensures fairness by preventing multiple winners and tracking NFT ownership.

## Features

- Selects a single winner for the scavenger hunt.
- Automatically increments the token ID when a winner is set.
- Allows the winner to mint an NFT.
- Ensures that an NFT is only minted once per token ID.

## How It Works

1. The contract starts with no winner selected.
2. The owner calls `setWinner(address _winner)`, assigning the winner and incrementing the token ID.
3. The winner can then call `mintNFT()` to claim their NFT.
4. The event logs record winner selection and NFT minting for transparency.

## Deployment & Usage

- Deploy the contract to an Ethereum-compatible blockchain.
- Use tools like Remix, Hardhat, or Truffle for interaction.

## Contract Address

*(To be added after deployment)*



