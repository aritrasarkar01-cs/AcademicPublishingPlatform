# 📚 Academic Publishing Platform (Soroban Smart Contract)

## 📌 Project Description
The Academic Publishing Platform is a decentralized application built on the Stellar Soroban smart contract framework. It allows researchers and authors to publish academic papers securely on-chain, ensuring transparency, immutability, and proof of ownership.
<img width="1600" height="757" alt="image" src="https://github.com/user-attachments/assets/dbf89647-1816-4fb0-9a9d-e8801160fcee" />


## 🚀 What it does
This smart contract enables users to:
- Publish academic papers with metadata
- Store references (hashes) of paper content on-chain
- Retrieve published papers
- Track total number of publications

Instead of storing full documents (which is expensive on-chain), the platform stores a **content hash**, which can link to off-chain storage like IPFS.

## ✨ Features
- 📄 Publish new academic papers
- 🔐 Immutable record of authorship
- 🔎 Retrieve papers by ID
- 📊 Track total publications
- ⚡ Lightweight storage using content hashes
- 🌐 Compatible with decentralized storage (IPFS)

## 🧱 Smart Contract Functions

### 1. `publish_paper(title, author, content_hash)`
Publishes a new academic paper.

**Returns:**
- Paper ID (u64)

---

### 2. `get_paper(id)`
Fetches details of a specific paper.

**Returns:**
- Paper struct (id, title, author, content_hash)

---

### 3. `get_paper_count()`
Returns total number of published papers.

---

## 🛠 Tech Stack
- Stellar Soroban
- Rust (no_std)
- Blockchain storage

## 🌍 Use Cases
- Academic research publishing
- Proof of authorship
- Decentralized journals
- Research collaboration platforms

## 🔗 Deployed Smart Contract Link
Academic Publishing Platform:  
👉 https://stellar.expert/explorer/testnet/contract/CDVOFASBCH5GRZV776IRAXTOYL3E3D2PK2NWOQYQ5D7V23QXMRBGSZMY


## ⚙️ How to Deploy

1. Install Soroban CLI:
```bash
cargo install soroban-cli
