# 🚀 Smart Contract for Land Registry Using Blockchain 🌍

## 📚 Overview

This project demonstrates how to build a **decentralized land registry system** using **Ethereum** and **Solidity**. By leveraging blockchain technology, the goal is to create a **secure**, **immutable**, and **transparent** land registration system, ideal for managing land ownership and transactions. Blockchain ensures that sensitive data is tamper-proof and provides transparency to prevent fraud.

### 🌐 Key Features:
- **Decentralized Storage**: Store land ownership data securely and transparently.
- **Enhanced Security**: Use cryptographic hashing to secure data integrity.
- **Improved Access**: A transparent system accessible by authorized users.
- **Smart Contract Automation**: Automate property transfers and updates to eliminate manual intervention.

## 💡 Problem Statement

Traditional land registries are often centralized and vulnerable to tampering, fraud, and inefficiency. Paper-based or centralized databases pose serious security and trust concerns, which hinder the effective management of property ownership and transactions. This project addresses these issues by providing a **decentralized** alternative using blockchain technology.

## 🔧 Technology Stack

- **Blockchain Platform**: Ethereum
- **Smart Contract Language**: Solidity
- **Development Environment**: [Remix Ethereum IDE](https://remix.ethereum.org)
- **Libraries**: 
  - Web3.js
  - Ethers.js

## 📁 File Structure

The Remix workspace includes the following folders:

- **`contracts/`**: Contains the smart contracts, with increasing levels of complexity.
- **`scripts/`**: TypeScript files used to deploy contracts using `web3.js` and `ethers.js`.
- **`tests/`**: Contains test files for smart contract validation using Mocha and Chai.

### 📑 SCRIPTS

The `scripts` folder includes the following files:

- `deploy_with_ethers.ts`: Deploys the contract using the `ethers.js` library.
- `deploy_with_web3.ts`: Deploys the contract using the `web3.js` library.
- To deploy a contract, change the contract name and constructor arguments in the respective files.

### 🧪 TESTING

- The `tests/` folder contains unit tests for the `Storage` contract using Mocha and Chai.
- To run the tests, right-click on the test file and click **Run**. Ensure that the Solidity file is compiled before testing.

## 🎯 Project Goals

- **Design a Blockchain Solution**: Develop a smart contract to handle land registration processes.
- **Implement Smart Contracts**: Write and deploy the smart contract on the Ethereum network using Solidity.
- **Deploy a Blockchain Application**: Use Remix to deploy and interact with the contract.

## 👥 End Users

- **Government Agencies**: Can utilize the system for official land ownership records.
- **Real Estate Professionals**: Property developers and agents can track property transactions.
- **Property Owners**: Individuals can maintain transparent and immutable property records.
- **Legal Professionals**: Lawyers and notaries can verify land ownership digitally.

## 🛠️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Saket22-CS/SmartContract-LandRegistry.git
