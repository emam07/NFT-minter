
# 🖼️ NFT Minter using Starton + Hardhat

This project lets you **deploy and mint NFTs on the blockchain using Starton** APIs and Hardhat. It automates the NFT creation process and connects with Starton's powerful developer tools.

---

## 🚀 Features
- Write and deploy ERC-721 NFT contracts
- Store metadata on IPFS via Starton
- Mint NFTs to any wallet using Starton API
- Fully automated with Hardhat scripts

---

## 📦 Prerequisites

- Node.js v16+
- A Starton account → https://www.starton.com
- A Starton project with API key and smart contract credentials
- A funded testnet wallet (Mumbai/Goerli)
- Metamask + Etherscan for verification

---

## 📁 Project Structure
nft-minter/
├── contracts/
│ └── NftMinter.sol
├── scripts/
│ └── deploy.js
│ └── mint.js
├── .env
├── hardhat.config.js
├── package.json
└── README.md

npm install --save-dev hardhat
npm install @nomicfoundation/hardhat-toolbox dotenv axios ethers
Initialize Hardhat
npx hardhat
Create a .env file:
STARTON_API_KEY=your_starton_api_key
STARTON_PROJECT_ID=your_project_id
PRIVATE_KEY=your_wallet_private_key
RPC_URL=https://polygon-mumbai.infura.io/v3/your_infura_project_id
CONTRACT_NAME=NftMinter

for running 
npx hardhat run scripts/deploy.js 



make id on startonn and create api key if u dont have metamask wallet create one as well
