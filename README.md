

# 🗳️ Soroban Vote dApp with Freighter Wallet

A **Stellar Soroban Smart Contract** + **Next.js Frontend** project that enables users to vote on proposals using the **Freighter Wallet**.

This app demonstrates how to integrate **on-chain voting functionality** with **wallet-based identity** using Soroban and Next.js.

<img src="https://raw.githubusercontent.com/net2devcrypto/misc/main/vote5.png" width="550" height="370">

---

## ⚙️ Features

- ✅ Soroban smart contract-based proposal voting  
- ✅ Freighter wallet integration (testnet compatible)  
- ✅ Simple and responsive Next.js frontend  
- ✅ Interacts with deployed Soroban contract in real-time  

---

## 📦 Getting Started

### 1. Clone the Repo & Deploy the Contract

```bash
git clone https://github.com/YOUR_USERNAME/soroban-vote-dapp.git
cd soroban-vote-dapp
```

Deploy the `n2d-soroban-votecontract-v1.rs` contract to the **Soroban Testnet** using the Soroban CLI.

Save the **deployed contract address**, you’ll need it soon.

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Set Your Contract Address

Open `soroban.js` and update the contract address:

```javascript
let contractAddress = 'YOUR_DEPLOYED_CONTRACT_ADDRESS';
```

Save the file.

---

### 4. Set Up Freighter Wallet

1. Install the [Freighter Wallet](https://freighter.stellar.org/) browser extension  
2. Create or import a testnet wallet  
3. Fund your wallet using [Friendbot](https://laboratory.stellar.org/#account-creator?network=test)  

---

### 5. Run the App

```bash
npm run dev
```

Visit the app at:  
**http://localhost:3000**

---


## 🧪 Built With

- [Next.js](https://nextjs.org/)
- [Stellar Soroban](https://soroban.stellar.org/)
- [Freighter Wallet](https://freighter.stellar.org/)

---

## 🤝 Contributing

Pull requests and issues are welcome! Let’s make decentralized voting simple and accessible.

---

Let me know if you want a **badge section**, **license**, or **credits** section added too.
