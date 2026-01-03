# Blockchain File Storage and Sharing

A decentralized platform for secure file storage and sharing. This project combines **Ethereum Smart Contracts** with **IPFS (InterPlanetary File System)** to ensure that your data is permanent, tamper-proof, and entirely under your control.

## 🚀 Overview

Unlike traditional cloud storage, this application eliminates centralized authorities. By using blockchain for access management and IPFS for storage, users benefit from:
* **Data Ownership:** You own the keys to your files.
* **No Single Point of Failure:** Decentralized hosting ensures high availability.
* **Transparency:** File metadata and sharing permissions are verifiable on the blockchain.

## 📂 Project Structure

```text
BlockchainFileStorageandSharing/
├── contracts/             # Solidity Smart Contracts
│   └── Storage.sol        # Main contract for file metadata & access
├── scripts/               # Deployment and maintenance scripts
│   └── deploy.js          # Hardhat deployment script
├── src/                   # React Frontend Source
│   ├── components/        # Reusable UI components (Navbar, Modal)
│   ├── artifacts/         # Compiled Contract ABI files
│   ├── App.js             # Main Application Logic
│   └── main.jsx           # Frontend entry point
├── test/                  # Smart Contract test files
├── public/                # Static assets
├── .env.example           # Template for environment variables
├── hardhat.config.js      # Hardhat configuration
├── package.json           # Project dependencies and scripts
└── README.md              # Project documentation
```
## ✨ Features
Secure Uploads: Files are stored on IPFS and indexed via content hashes (CIDs).

Smart Contract Access Control: Manage who can view your files using Solidity-based permissions.

MetaMask Integration: Securely sign transactions and interact with the dApp.

File Sharing: Grant and revoke access to other Ethereum addresses instantly.

Responsive UI: A user-friendly dashboard to track your uploads and shared files.

## 🛠️ Tech Stack
Component,Technology
Frontend,React.js / Vite
Blockchain,Ethereum / Solidity
Storage,IPFS (InterPlanetary File System)
Development,Hardhat / Ethers.js
Wallet,MetaMask

## 🔧 Installation & Setup
1. Clone the Repository
```
 git clone [https://github.com/revxi/BlockchainFileStorageandSharing.git](https://github.com/revxi/BlockchainFileStorageandSharing.git)
cd BlockchainFileStorageandSharing
```
2. Install Dependencies
```
npm install
```
4. Environment Configuration
Create a .env file in the root directory and add your keys:
    ```
    PRIVATE_KEY=your_metamask_private_key
    RPC_URL=your_rpc_endpoint_url
    PINATA_API_KEY=your_pinata_api_key
    PINATA_SECRET_KEY=your_pinata_secret_key
`
5. Smart Contract Deploymen
  ```
     npx hardhat compile
    npx hardhat run scripts/deploy.js --network <your-network>
   ```
6. Run the Application

   ``` 
   npm run dev
## 🖥️ How it Works
Upload: When a user selects a file, it is sent to IPFS.

Hashing: IPFS returns a unique hash (CID).

Blockchain Record: The dApp triggers a MetaMask transaction to store the CID and file metadata on the Ethereum blockchain.

Sharing: The owner can call a shareAccess function in the smart contract to allow specific addresses to retrieve the file CID.

## 🛡️ License
This project is licensed under the MIT License.

## 🤝 Contributing
Fork the Project.

Create your Feature Branch (git checkout -b feature/NewFeature).

Commit your Changes (git commit -m 'Add NewFeature').

Push to the Branch (git push origin feature/NewFeature).

Open a Pull Request.
