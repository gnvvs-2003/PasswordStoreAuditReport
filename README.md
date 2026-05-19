# Smart Contract Security Audit Workspace: PasswordStore

<p align="center">
  <img src="./logo.pdf" width="200" alt="Auditor Logo">
</p>

This repository contains the smart contract code, verification testing suite, and official security audit report artifacts for the **PasswordStore** protocol assessment.

---

## 📋 Project Overview

**PasswordStore** is a simple smart contract designed to act as a decentralized password manager. The protocol's primary specification is to allow a single authorized user (the contract owner) to securely save a private password on the blockchain and retrieve it later. According to the project specifications, no other third party should be allowed to view or change this password.

---

## 🛠️ Scope & Audit Details

- **Lead Security Auditor:** G.N.V.Vinay Sankar
- **Target Repository:** [Cyfrin 3-passwordstore-audit](https://github.com/Cyfrin/3-passwordstore-audit)
- **Commit Hash under Review:** `2e8f81e263b3a9d18fab4fb5c46805ffc10a9990`
- **Compiler Configuration:** Solc `0.8.18`
- **Target Blockchain Network:** Ethereum
- **In-Scope Contracts:**
  ```text
  ./src/
  └── PasswordStore.sol
