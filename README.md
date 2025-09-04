# onchain-point
OnChain Points — A Web3 app that connects to your crypto wallet and awards points based on the tokens, NFTs, and balances you hold. Built with Next.js, RainbowKit, viem, Prisma, and PostgreSQL, it demonstrates real-time on-chain data fetching, scoring logic, and a leaderboard system.

## ✨ Features
- 🔗 **Wallet Connect** — Secure login with RainbowKit & wagmi  
- 📊 **On-Chain Scoring Engine** — Awards points based on wallet balances, token tiers, and NFTs  
- 🪙 **Multi-Chain Support** — Works across Ethereum, Polygon, Base (extendable to Solana)  
- 🗄 **Persistent Leaderboard** — Points and snapshots stored with PostgreSQL + Prisma  
- ⚡ **Next.js 14** — Server-side rendering with API routes for scoring logic  
- ⏱ **Automated Refresh** — Cron jobs to update wallet scores daily/hourly  

---

## 🛠 Tech Stack
- **Frontend:** Next.js 14 (App Router), TypeScript, RainbowKit, wagmi, viem  
- **Backend:** Next.js API routes, Prisma ORM  
- **Database:** PostgreSQL  
- **Blockchain API:** Alchemy/QuickNode for token balances & pricing  
- **Styling:** Tailwind CSS + ShadCN UI  

