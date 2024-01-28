# web3-chainlink-workshop

## Outline

## Basic intro to ethereum/blockchain (Santiago?)

- private keys and wallets (creating wallet using metamask)
- u can do only 2 things with a blockchain, read or write data
- testnets and faucets

### Intro to web3.js (Santiago)

- what's web3.js (raw RPC calls vs javascript abstraction)
- maintainers
- projects that have used web3js
- other alternatives (ethers, viem, raw rpc calls)

### Diving into web3 modules (Santiago)

- web3.eth (fetch data from blocks, get balance, estimate gas, etc)
- web3.eth.accounts & web3.eth.accounts.wallet (create account, sign tx, send tx, etc)
- web3.eth.contract (deploying and interacting with contracts)
- web3.utils (short explanation of a couple of methods)

### Writing your first smart contract / basic solidity (Santiago?)

- u can do only 2 things with a blockchain, read or write data
- write a contract with setMessage() and getMessage() and only 1 string private variable
- deploy the contract to mumbai testnet with web3js
- interact with the contract using scripts/web3js

### dApp

- npx create-react-app
- create a simple front end (simple one, no design/fancy things) with 2 things:
  - input text to set the message (write data to the blockchain)
  - button to `update msg` and a <h2> to print the `msg` (retrieve data from the blockchain)

### Chainlink (David)

- TBD

### [Chainlink plugin](https://www.npmjs.com/package/@chainsafe/web3-plugin-chainlink) (Santiago?/David?)

- TBD
