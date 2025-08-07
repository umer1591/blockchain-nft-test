# 🧠 blockchain-nft-test

This is an assessment project to demonstrate an **ERC-721 Smart Contract** integrated into a full-stack NFT marketplace app using **Next.js**, **Tailwind CSS**, and **Solidity**.

---

## 🚀 Features

- 🖼 NFT minting (ERC-721)
- 👛 Wallet connection (MetaMask)
- 📦 NFT categories UI (Art, Music, Collectibles)
- ⚙ Backend powered by Prisma + SQLite
- 🧪 Smart contract testing with Hardhat

---

## 🛠 Tech Stack

- **Frontend**: Next.js, Tailwind CSS, TypeScript
- **Backend**: Prisma ORM, SQLite
- **Smart Contracts**: Solidity, Hardhat
- **Package Management**: `pnpm` (monorepo)
- **Blockchain**: Local + Wallet integration

---

## 📁 Folder Structure

Blockchain-Test/
├── apps/
│ ├── api/ # Backend - Nest.js + Prisma
│ └── web/ # Frontend - Next.js app
├── packages/ # Shared components and config
└── ....

## ⚙️ Environment Variables

Create a `.env` file inside `apps/api/prisma/`:

```env
DATABASE_URL="file:./dev.db"
