# 🎲 Raffle Smart Contract

This project is a decentralized **Raffle (Lottery) smart contract** developed using **Solidity** and the **Foundry** development suite. It showcases the integration of secure random number generation using **Chainlink VRF**, full test coverage with Foundry, and deployment to Ethereum testnets.

> 🛠 This is part of my ongoing exploration of advanced smart contract development and infrastructure — improvements are already in the pipeline!

---

## 🧠 Project Overview

The Raffle contract allows users to enter a lottery by sending a fixed ETH amount. At predefined intervals, the contract uses Chainlink's Verifiable Random Function (VRF) to select a random winner and sends them the prize pool.

### Key Features:

- ✅ Entry mechanism with ETH transfer
- ✅ Chainlink VRF integration for secure randomness
- ✅ Automated upkeep (Chainlink Keepers support planned)
- ✅ Access control for sensitive functions
- ✅ Gas usage analysis & optimization
- ✅ Full test coverage (unit + forked)

---

## 🧪 What I Built

This project wasn't just about writing a contract — it was about **end-to-end engineering**. Here's what went into it:

| Layer                       | Description                                                           |
| --------------------------- | --------------------------------------------------------------------- |
| 🔐 **Solidity Contract**     | Handles entries, random winner selection, and ETH transfers           |
| 🧪 **Testing Suite**         | Built with Forge: unit tests, forked simulations, fuzzing, assertions |
| ⚙️ **Deployment Scripts**    | Scripts for automated deployment & verification                       |
| 🌐 **Chainlink Integration** | Used VRFv2.5 for secure randomness (testnet verified)                 |
| ⛽ **Gas Snapshotting**      | Benchmarked costs of critical functions using `forge snapshot`        |
| 🧱 **Future Scope**          | Planning frontend integration & support for multiple rounds           |

---

## 🧰 Tools & Stack

- **Solidity** (v0.8.x)
- **Foundry** (Forge, Anvil, Cast)
- **Chainlink VRF**
- **Sepolia Testnet**
- **Etherscan Verification**
- **dotenv for secrets**
- **GitHub Actions** (planned CI)

---

## ⚡ Try It Out

If you'd like to clone or fork the project:

```bash
git clone https://github.com/barnabasmunuhe/crowdfunding-smart-contract.git
cd raffle-smart-contract
forge install
forge build
forge test
```
To deploy, you'll need your testnet RPC and wallet private key.

🔭 Improvements in Progress
I'm actively improving this contract to include:

🧾 Custom errors for gas optimization

🔄 Full Chainlink Keepers integration (automated draws)

📤 Event logs for frontend compatibility

🧩 Enum-based lifecycle control

🛡 Advanced security patterns (try/catch, fallback logic)

🧪 Hardhat compatibility for frontend devs

📸 Sneak Peek (Coming Soon)
A simple frontend UI for testing the raffle on Sepolia, built with React & ethers.js.

👨‍💻 About Me
I’m Barnabas M., a smart contract developer focused on building practical, production-ready DApps with a deep understanding of Ethereum infrastructure. This project was part of my growth journey through the Cyfrin Updraft course and beyond.

🌐 My GitHub

📫 Reach me via LinkedIn or email

📜 License
This project is open source under the MIT license.

✨ Thanks for checking out my work. More smart contracts and DeFi experiments are on the way!