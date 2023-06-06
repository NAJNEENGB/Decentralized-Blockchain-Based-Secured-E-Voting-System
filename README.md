# Decentralized-Blockchain-Based-Secured-E-Voting-System
Build your first Decentralized Blockchain E-voting system on Ethereum Network

# 1. Installation
Install the Dependencies listed below:


NPM: https://nodejs.org

Truffle: https://github.com/trufflesuite/truffle

Ganache: http://truffleframework.com/ganache/

Metamask: https://metamask.io/


# 2. Get started with Back-End

$ cd election

$ npm install


# 3. Open Ganache
Open Ganache GUI client that can be downloaded from above link. It will start your local Blockchain instance which can be used in creating accounts in MetaMask.4


# 4. Deploy Election Smart Contract
You must compile and migrate the Election Smart Contract whenever you restart Ganache each time.

Following code to migrate:

$ truffle migrate --reset


# 5. Start your MetaMask 
Create local account and login to your MetaMask. Then, connect metamask to your local Etherum blockchain provided by Ganache.
Import the accounts provided by Ganache.


# 6. Execute the Front-End
Following code to run your First Decentralized project:

$ npm run dev
