# DeFi-Kingdom-Clone

## Project Description

This project implements a Vault smart contract that allows users to deposit and withdraw ERC20 tokens. The contract uses shares to represent a user's stake in the Vault, enabling proportional withdrawals based on the shares held by the user.

## Smart Contract Details

- **Token Interface (IERC20)**: Defines the standard functions for an ERC20 token.
- **Vault Contract**: Manages the deposit and withdrawal of tokens. The contract mints shares on deposits and burns shares on withdrawals.

## Setup and Deployment

### Prerequisites

- Node.js
- npm or yarn
- Hardhat
- MetaMask
- Avalanche Network (deployed locally and imported to MetaMask)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/vault-contract.git
   cd vault-contract

2. Install dependencies
   ```sh
   npm install
