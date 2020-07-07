1. Backend: ERC20 contract written in solidity
2. Web Frontend: Web3.js DApp.
3. Mobile Frontend: JSON markup

# 1. Backend

The "backend" is just a set of solidity contracts. This tutorial is not about writing ERC20 tokens or smart contracts so we're just going to use the most basic token possible.

## Deployment

You can go to [Remix](https://remix.ethereum.org), copy and paste all the files in [contracts](contracts) folder, and deploy to Ethereum.

# 2. Web

The entire DApp is a single HTML file. It uses a JavaScript app framework called [cell.js](https://www.celljs.org) to implement the app in as simple manner as possible. 

# 3. Mobile

Jasonette is view-oriented. Therefore everything revolves around views. There are three views in the app:

1. Main view: Display ERC20 token stats and send tokens
2. Private key QR code scanner: For importing user's private key
3. Receiver Public key QR code scanner: To send a token to another user, you need to scan the user's public key
