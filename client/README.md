# Ethirum Wallet
This project is a decentralized cryptocurrency wallet application that enables users to securely store, send, and receive cryptocurrencies. The application is built with a client-side interface and integrates a smart contract deployed on the Ethereum blockchain.

# Project Structure
## Client
This directory contains the frontend code for the cryptocurrency wallet.

* Images:
  * animated.svg: An animated SVG graphic.
  * hello.svg: A static SVG graphic.
  * logo.png: The application's logo.
* Source Code:
  * .eslintrc.js: ESLint configuration file.
  * .gitignore: Git ignore file specifying untracked files.
  * .prettierrc: Prettier configuration file.
  * index.html: Main HTML file for the client-side application.
  * package-lock.json: Dependency lock file for npm.
  * package.json: Project metadata and dependencies.
  * postcss.config.js: PostCSS configuration file.
  * tailwind.config.js: Tailwind CSS configuration file.
  * vite.config.js: Vite configuration file.
  * yarn.lock: Dependency lock file for Yarn.
  
## Smart Contract
This directory contains the smart contract code and related scripts for the cryptocurrency wallet.

* Contracts:
  * Transactions.sol: Solidity smart contract for handling transactions.
* Scripts:
  * deploy.js: Script to deploy the smart contract.
* Tests:
  * sample-test.js: Sample test script for the smart contract.

# Getting Started
## Prerequisites
* Node.js and npm (or Yarn)
* Hardhat (Ethereum development environment)
* A web browser (for the client-side application)

## Installation
1. Clone the repository:
   `git clone https://github.com/ggwpfax/crypto-wallet.git`
   `cd crypto-wallet`
2. Install client dependencies:
  `cd client`
  `npm install` or `yarn install`
3. Install smart contract dependencies:
  `cd ../smart_contract`
  `npm install` or `yarn install`

## Usage
1. Run the client-side application:
  `cd client`
  `npm run dev` or `yarn dev`
2. Deploy the smart contract:
  `cd smart_contract`
  `npx hardhat run scripts/deploy.js --network your-network`
3. Run tests for the smart contract:
  `npx hardhat test`
