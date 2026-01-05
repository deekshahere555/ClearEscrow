# ClearEscrow - Decentralized Freelance Escrow Platform

A secure, blockchain-based escrow platform that revolutionizes freelance payments through smart contract automation and milestone-based deliverables.

## Live Link

[Live Link](https://clearescrow.vercel.app/)

## 🌟 Overview

ClearEscrow enables clients and freelancers to collaborate with confidence through decentralized escrow services. Built on Mantle blockchain technology, it ensures transparent, trustless, and automated payment releases based on project milestones.

## ✨ Features

### 🔒 **Secure Smart Contract Escrow**
- Funds are locked in smart contracts until work is completed and approved
- No intermediary required - blockchain handles all transactions
- Immutable transaction history and audit trail

### 🎯 **Milestone-Based Payments**
- Break projects into manageable deliverables
- Freelancers mark milestones as completed
- Clients approve and release payments automatically
- Partial payments as work progresses

### 💰 **Transparent Financial Tracking**
- Real-time escrow balance monitoring
- Clear visibility of paid vs. remaining amounts
- Platform fee deduction (5% on payments)
- Automatic fund distribution

### 👥 **Dual Role Management**
- **For Clients**: Create escrows, add milestones, approve payments
- **For Freelancers**: Mark work complete, receive automated payments
- Role-based interface adapts to user type

### 📊 **Comprehensive Dashboard**
- View all active and completed escrows
- Track project progress and payment status
- Real-time balance updates
- Transaction history

### 🎨 **Modern User Interface**
- Beautiful, responsive design
- Dark mode support
- Intuitive navigation and workflows
- Mobile-friendly experience

## 🏗️ Smart Contract Details

### Contract Address
**Network:** Mantle Sepolia Testnet
**Address:** `0xd536154E364F238CB63bc6d91d6be30060084E82`

### Contract Features
- **Escrow Creation:** Deploy secure escrow contracts with MNT deposits
- **Stage Management:** Add, edit, and track project milestones
- **Payment Automation:** Smart contract handles payment releases
- **Platform Fees:** 5% fee automatically deducted and distributed
- **Access Control:** Role-based permissions for clients and freelancers

### Key Functions
- `createEscrow(address freelancer)` - Create new escrow with MNTdeposit
- `addStage(uint256 id, string desc, uint256 amount)` - Add project milestones
- `markStageCompleted(uint256 id, uint256 stageId)` - Freelancer marks work done
- `releaseStagePayment(uint256 id, uint256 stageId)` - Client releases payment
- `getEscrowStages(uint256 id)` - Retrieve all project milestones

## 🚀 How It Works

### For Clients:
1. **Create Escrow** - Deposit funds and specify freelancer address
2. **Define Milestones** - Break project into payable deliverables
3. **Approve Work** - Review completed milestones and release payments
4. **Track Progress** - Monitor project completion and remaining balance

### For Freelancers:
1. **Receive Escrow** - Get notified when client creates escrow
2. **Complete Work** - Mark milestones as completed when done
3. **Await Approval** - Client reviews and approves your work
4. **Receive Payment** - Funds automatically transferred to your wallet

## 🔐 Security & Trust

- **Decentralized**: No central authority controls funds
- **Transparent**: All transactions visible on blockchain
- **Automated**: Smart contracts execute payments automatically
- **Immutable**: Contract rules cannot be changed once deployed
- **Auditable**: Complete transaction history available

## 🛠️ Technology Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Blockchain:** Mantle Smart Contracts (Solidity)
- **Web3:** Ethers.js for blockchain interaction
- **UI Components:** Lucide React icons
- **Styling:** Tailwind CSS with custom design system

## 📈 Platform Fees

- **Service Fee:** 5% of each milestone payment
- **Fee Distribution:** Automatically collected and managed by platform
- **Transparent Pricing:** Fees clearly displayed before transactions

## 🌐 Network Information

**Deployed Network:** Mantle Sepolia Testnet
**Chain ID:** 5003
---

## Images

<img width="2812" height="2960" alt="Screenshot 2026-01-05 at 18-16-25 ClearEscrow - Secure Blockchain Escrow Service" src="https://github.com/user-attachments/assets/2b700324-4dc5-4db7-baab-6b790dd81c11" />

<img width="1061" height="839" alt="Screenshot 2026-01-05 at 6 17 57 PM" src="https://github.com/user-attachments/assets/d09f6a1f-9a48-4c76-b47d-28bb86488dfe" />

<img width="1456" height="772" alt="Screenshot 2026-01-05 at 6 17 14 PM" src="https://github.com/user-attachments/assets/ef8a4207-b3a5-4110-b325-17d98299acf5" />

<img width="1327" height="836" alt="Screenshot 2026-01-05 at 6 17 34 PM" src="https://github.com/user-attachments/assets/a1ef33b7-7b85-48cd-b08b-e6070d534b30" />

