# 🏠 Blockchain-based Property Ownership Management System

A decentralized web application (DApp) built using **Ethereum blockchain** to securely manage property ownership records, enabling transparent and tamper-proof transactions between property buyers, sellers, and registrars.

---

## 📌 Features

- ✅ Register property ownership on the blockchain
- ✅ Transfer property ownership via smart contracts
- ✅ Prevent double-spending or fraud in ownership
- ✅ Role-based access (Admin / Buyer / Seller)
- ✅ IPFS-based document storage (optional)
- ✅ Secure and auditable transaction history

---

## 💡 Use Case

Traditional property management systems are prone to:

- Manual errors
- Forgery and fraud
- Lack of transparency

**This project solves that using blockchain**, ensuring:

- Immutability
- Transparency
- Verifiable ownership records

---

## 🛠️ Tech Stack

| Layer        | Technology                       |
|-------------|----------------------------------|
| Blockchain   | Ethereum (Solidity, Ganache)     |
| Frontend     | React.js, Tailwind CSS           |
| Backend/API  | Node.js, Web3.js, Express (optional) |
| Storage      | IPFS (for documents, optional)   |
| Dev Tools    | Hardhat or Truffle, Metamask     |

---

## 🔧 Smart Contract Functionality

- `registerProperty()`: Register new property with owner details
- `transferOwnership()`: Secure ownership transfer after verification
- `getPropertyDetails()`: Fetch property metadata
- `getOwnershipHistory()`: View past owners (if implemented)

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- Metamask extension
- Ganache or testnet access
- Hardhat or Truffle installed globally

### Clone the Repository

```bash
git clone https://github.com/Anshshetty18/property-ownership-management.git
cd property-ownership-management
