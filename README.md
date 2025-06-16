# 💬 Decentralized Chat Application using Blockchain

A secure, peer-to-peer chat application built with Ethereum blockchain, Hardhat, and React.

## 🚀 Features

- 📡 Peer-to-Peer Messaging
- 🔐 Blockchain-based encryption and immutability
- 🦊 MetaMask integration for authentication
- 💬 Real-time chat updates

## 🛠️ Technologies Used

- React.js
- Hardhat (Ethereum development environment)
- Solidity (Smart Contracts)
- MetaMask
- Web3.js / Ethers.js
- Node.js

## 📸 Screenshots

**🔹 Login / Wallet Connect**
![Screenshot 1](https://github.com/PallaviPuligilla/chat-dapp/blob/main/Screenshot%202025-06-12%20133900.png?raw=true)

**🔹 Chat Interface**
![Screenshot 2](https://github.com/PallaviPuligilla/chat-dapp/blob/main/Screenshot%202025-06-12%20133940.png?raw=true)

**🔹 Chat in Action**
![Screenshot 3](https://github.com/PallaviPuligilla/chat-dapp/blob/main/Screenshot%202025-06-12%20140007.png?raw=true)
## ⚙️ How to Run Locally

```bash
# Clone the repo
git clone https://github.com/PallaviPuligilla/chat-dapp.git

# Navigate into the folder
cd chat-dapp

# Install dependencies
npm install

# Run the frontend
npm start

# Run Hardhat blockchain
npx hardhat node

# Compile the smart contracts
npx hardhat compile

# Deploy the contracts to local network
npx hardhat run scripts/deploy.js --network localhost

# Start the React app in development mode
npm run dev
