# 🏢 AssetFlow

Tokenize and invest in real-world assets using the Stellar blockchain.

![Platform](https://img.shields.io/badge/Platform-RWA-blue)
![Blockchain](https://img.shields.io/badge/Blockchain-Stellar-brightgreen)
![Framework](https://img.shields.io/badge/Framework-Next.js_15-black)
![TypeScript](https://img.shields.io/badge/Language-TypeScript-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎯 Project Overview

The AssetFlow allows users to invest in tokenized real estate, commodities, and infrastructure projects. Built on the Stellar blockchain, it ensures fast and secure transactions with a professional web interface.

---

## 🌟 Features

### 🧑‍💼 For Investors
- Portfolio dashboard with real-time data
- Asset marketplace with filtering
- Secure token transfers with KYC compliance
- Wallet integration (Freighter)

### 🏢 For Asset Owners
- 5-step tokenization wizard
- Compliance & document management
- Funding tracking and deployment tools

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- [Freighter Wallet](https://freighter.app/)
- Stellar Testnet access

### Installation

```bash
git clone <repo-url>
cd rwa-investment-platform/rwa-frontend
npm install
npm run dev
Visit http://localhost:3000

🏗️ Tech Stack
Frontend: Next.js 15, TypeScript, Tailwind CSS

State: Zustand

Blockchain: Stellar SDK

Wallet: Freighter

UI: shadcn/ui + Lucide Icons

🧱 Key Structure
csharp
Kopyala
Düzenle
rwa-frontend/
├── app/            # Main app pages
├── components/     # UI components
├── lib/            # Stellar + contract logic
├── stores/         # Global state
└── public/         # Static assets
🔐 Smart Contract
Network: Stellar Testnet

Contract ID: GC3HCKKMQNJY6DNCTYPLTRV7WPNYSHDFICFLJ74GKSUSUQJL5IFH5BVU

Example Asset: Luxury Apartment NYC (LAPT)

Supported methods:
get_balance, transfer, get_metadata, check_compliance, mint (admin)

📦 Scripts
bash
Kopyala
Düzenle
npm run dev          
npm run build        
npm run start       
npm run lint        
npm run type-check 
📌 Roadmap
✅ Core dashboard, marketplace, wallet integration

🔄 Advanced trading (charts, ROI, analytics)

📋 Tokenization engine (document/legal tools)

🔮 Future: Admin panel, mobile app, multi-chain

🛡️ Security & Compliance
Non-custodial Freighter wallet

KYC & whitelist verification

Transaction previews and address validation

Audit trail (planned)
