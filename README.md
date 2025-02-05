AI Marketplace with Blockchain Integration
This repository contains a decentralized AI marketplace where users can buy and sell AI models using ERC-20 tokens. The marketplace integrates with blockchain tools like MetaMask to enable wallet connection and secure transactions.

Features
1. User Authentication and Wallet Integration
Users can connect their wallets (MetaMask or similar tools) to interact with the blockchain.
Once connected, users can view their wallet details, making the marketplace experience seamless and secure.
2. Token Balance Display
Users can check their ERC-20 token balance directly within the marketplace interface.
Token balance is updated regularly, and users can refresh their balance to reflect real-time data.
3. AI Model Listings
Sellers can list their AI models with the following details:
Model Name
Description
Price (in ERC-20 tokens)
Seller Details (such as wallet address)
Sellers can upload the model file or provide a secure access link for download.
A marketplace listing will display these details for buyers to explore.
4. Purchase Flow
Buyers can:
View detailed information about each AI model.
Initiate purchases by transferring the required ERC-20 tokens to the seller's wallet.
Upon a successful transaction, the marketplace UI will reflect the update:
Mark the AI model as "Sold".
Adjust the inventory accordingly to show available models.

Prerequisites
Node.js (v14 or later)
MetaMask browser extension
Ganache (for local blockchain testing)


Installation

Clone the Repository:

git clone https://github.com/Zhanbatyr06/Blockchain4.git
cd Blockchain4

Install Dependencies:

npm install hardhat
Deploy Smart Contracts:

npx hardhat run scripts/deploy.js --network ganache
Compile Smart Contracts:

npx hardhat compile

Usage

1. Connect Your Wallet
Open the marketplace in your browser.
Ensure you have MetaMask (or a compatible wallet extension) installed.
Connect your wallet to the marketplace by clicking on the "Connect Wallet" button.
After connecting, you will be able to view your ERC-20 token balance and interact with the platform.
2. Browse and Purchase AI Models
Once your wallet is connected, browse through the list of available AI models.
To purchase an AI model, click on the model listing to view details.
Click "Buy Now" to initiate the purchase, which will transfer the required ERC-20 tokens to the seller's wallet.
3. Create New Listings
If you are a seller, navigate to the "Create Listing" page.
Provide the following details for your AI model:
Model Name
Description
Price (in ERC-20 tokens)
Upload Model File or provide an access link for download.
After submitting, your listing will appear in the marketplace for buyers to see.
4. Refresh Token Balance
To keep your token balance updated, click on the "Refresh Balance" button to see your current ERC-20 token balance in real-time.
5. View Purchase Status
Once a transaction is completed, the marketplace will update:
The model will be marked as "Sold".
The inventory count will be adjusted accordingly.

References

[Connecting to MetaMask with Vanilla JS](https://docs.web3js.org/guides/dapps/metamask-vanilla/)
https://wizard.openzeppelin.com/

Members

Moldabek Zhanbatyr  (2317)
Nadir Shugay (2317)
Pavel Kan (2317)
