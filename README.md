# ๐ CertiMint- Certificate Bound Token
Track and Send Certificates using Non transferrable ERC721 Tokens (Inspired By: SBT- Soul Bound Token)
Certificates once minted cannot be burnt and cannot transferred further

<p align="center">
    Make Sure you have React installed for local setup of this project
    <br />
    <a href="https://reactjs.org/"><strong>Learn more about React ยป</strong></a>
    <br />
    <a href="https://github.com/dhananjaypai08/CertiMint/issues">Report Bug</a>
    <br />
  <a href="https://github.com/dhananjaypai08/CertiMint">Project Link</a>
 </p>
 
## โ๏ธ Table of Contents
- [About the Project](#about-the-project)
- [Project Breakdown](#project-breakdown)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)

 
 ## ๐จ Project Breakdown 
- Developing ERC721 contract. Making changes to this contract and giving it the Sould Bound properties. Changing the before token transfer and after token transfer phases.
- Deploying the contract on remix IDE for easy deployment, Contract deployed on the goerli test network.
- Using Ethers JS for smart contract interaction and safely minting the CBT.
- Using IPFS for setting up the IPFS http client on the development server and adding metadata to the IPFS and receiving the IPFS hash for the Certify Token data.
- Using ReactJS for setting up IPFS infura client node, ethers.js and also for providing the development server.

### ๐ง Built With
- Frontend:
  - HTML
  - React
  - Ethers
  - JavaScript
  - IPFS HTTP Client
- Contract: 
  - Solidity
  - Remix
  - Metamask
  - Hardhat
 
## ๐ Getting Started
To get a local copy up and running follow these simple steps.

### ๐จ Installation
1. Clone the repo

```sh
git clone https://github.com/dhananjaypai08/CertiMint
```

2. Installing dependencies and requirements

```sh
cd CertiMint
npm install ethers
npm install ipfs-http-client
npm install particles-bg
npm install bulma
```

Note: In case the project is still not working, use
```sh
npm i
```

3. Running the APP
```sh
npm start
```

## ๐ง? Usage
Built version:
- npm v8.1.2
- Node v16.13.2

The Basic goal is to make certificate records easily accessible.
Reliable and data once minted cannot be deleted or erased which happens in centralized systems.

## โ Future Plan
- Integration with Lens Protocol for seperate Portfolio Profile
- Using Covalent API for getting unified CertiMint Tokens
- URL Routing in the frontend handling different paths
- Web3 authorization system for ownership which further helps minting the NFT

## ๐ค? Contributions 
Open for contributions. Just clone and follow the installation. Make changes and raise a PR detailing about the changes made.
