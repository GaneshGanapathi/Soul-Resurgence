# 🏥 Secure Electronic Health Records using Blockchain

## 📌 Overview
This project is a **decentralized medical record system** that uses **blockchain technology** to ensure **secure, immutable, and convenient access** to healthcare data. It allows patients and healthcare professionals to interact with medical records in a **transparent yet privacy-preserving** way.

## 🔥 Key Features
✅ **Decentralized & Secure** – Uses blockchain for **tamper-proof** medical records  
✅ **Patient-Controlled Access** – Patients decide who can access their data  
✅ **Smart Contracts** – Enforce rules for medical record storage and access  
✅ **Immutable Ledger** – No unauthorized changes or deletions  
✅ **Transparent & Efficient** – Ensures **trust** between healthcare providers  

---

## ⚙️ Tech Stack
- **Blockchain**: Ethereum (Ganache for local testing)  
- **Smart Contracts**: Solidity  
- **Development Framework**: Truffle  
- **Frontend**: React.js  
- **Backend**: Node.js & Express  
- **Storage**: IPFS (for off-chain storage of medical records)  
- **Wallet Integration**: MetaMask  

---

## 📌 How to Set Up the Project

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/GaneshGanapathi/Soul-Resurgence.git
cd Soul-Resurgence
```

2️⃣ Install Dependencies
```sh
npm install --force
npm install -g truffle
```

3️⃣ Start Local Blockchain (Ganache)
```sh
ganache-cli --deterministic
or open Ganache GUI.
```

4️⃣ Compile & Deploy Smart Contracts
```sh
cd src
truffle compile
truffle migrate
```

5️⃣ Run the Frontend
```sh
npm start
```
