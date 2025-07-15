# 🚀 Solana Token Launchpad

A Token Launchpad built on the Solana blockchain using React and Wallet Adapter. This app allows users to create their own tokens on Solana Devnet — complete with metadata and minting functionality.

---

## 📚 About the Project

This project was created as part of **100xDevs Cohort 3.0 - Web3 Week 8.0.2**, where we built a full-fledged token creation platform (Launchpad) on Solana using React.

---

## 🧠 Key Concepts Covered

### 🔹 What is a Token?

A **token** is a digital asset built on top of a blockchain. It can represent currency, utility, governance rights, or digital collectibles.

- **Token Mint**: Like a digital mint that can produce new tokens.
- **Associated Token Account**: Wallet-specific account to store tokens.
- **Metadata**: Info like name, symbol, and image URL attached to a token.

---

### 🔹 Transactions vs Instructions

- **Instructions**: Individual actions like “mint token” or “transfer token.”
- **Transactions**: A batch of instructions that get submitted to the blockchain.

In Solana, a transaction is composed of multiple instructions.

---

## ⚙️ Project Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Chandands1/solana-token-launchpad.git
   cd solana-token-launchpad
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Install wallet adapter and Solana packages**  
   ```bash
   npm install @solana/web3.js \
               @solana/spl-token \
               @solana/wallet-adapter-base \
               @solana/wallet-adapter-react \
               @solana/wallet-adapter-react-ui \
               @solana/wallet-adapter-wallets
   ```

4. **Install Vite plugin for node polyfills**  
   ```bash
   npm install --save-dev vite-plugin-node-polyfills
   ```

5. **Run the project**  
   ```bash
   npm run dev
   ```

---

## 🧰 Tech Stack

- **React + Vite**
- **Solana Web3.js**
- **Solana SPL Token & Token-2022**
- **Wallet Adapter**
- **Node Polyfills**

---

## 🚀 Features

- 🔐 **Connect Solana Wallet** (Devnet)
- 🪙 **Create Token Mint**
- 📝 **Add Metadata (name, symbol, image URI)**
- 💰 **Mint Tokens to Wallet**
- 🔗 **Uses Token-2022 Program for Metadata Support**

---

## 🧪 Network Info

> All actions are performed on **Solana Devnet**. Ensure your connected wallet is set to the Devnet network for testing.

---

## 📚 Resources & References

- [Solana Program Library (SPL)](https://github.com/solana-labs/solana-program-library)
- [Token Extensions Metadata Pointer](https://spl.solana.com/token-2022/extensions#example-create-a-mint-with-metadata)
- [Wallet Adapter Docs](https://github.com/anza-xyz/wallet-adapter/blob/master/APP.md)
- [Vite Node Polyfills](https://www.npmjs.com/package/vite-plugin-node-polyfills)

---

## 🙌 Acknowledgements

Thanks to [Harkirat Singh](https://twitter.com/kirat_tw) and the [100xDevs](https://100xdevs.com) community for the guidance and mentorship on Solana development.

---

## 📎 Final Note

This project is a hands-on implementation of everything needed to create, customize, and mint tokens using Solana's Token-2022 standard. It provides a real-world understanding of how token minting works in a decentralized and permissionless environment.
