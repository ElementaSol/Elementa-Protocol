🔥💧🌱🌬️Elementa Protocol - Solana Based Self-Marketmake Protocol

A self-marketmake built on Solana that uses 4 techs to marketmake your token. 
The first marketmake experiment protocol on Pump.Fun.
🎉 Now Open Source! Fork this repo and launch your own token with Elementa Protocol.
Features • How It Works • Setup Guide • Screenshots • Tech Stack • Architecture • Getting Started

🎯 What is Elementa Protocol?

Elementa Protocol is a self-marketmake assistant that uses 4 techs to help your token gain trust by investors.

Key Highlights
* ⏰ Instant Buy-backs and burns - the fastest on Solana chain.
* 💰 Volume Bots - uses bots to increase holders amount and total volume.
* 🔐 Provably Fair - Open-source and secure.
* 📱 Mobile Optimized - Seamless experience across all devices

Elements Protocol - Live Interface

Desktop View  - Active buy-backs, burns process
Real-time buy-backs and burn interface showing transactions, SOL amount used, countdown timer, and time it took.

Desktop View - Countdown for buy-backs/burns
Clean interface for buy-backs countdown, burn options.

Mobile Responsive
Fully responsive design optimized for mobile devices with touch-friendly controls

🎯 Core Mechanics

Automatic Marketmaking

* Claims Pump.fun Rewards to fund the entire process
* Volume Bots count and SOL amount used
* Fetches live market cap and token price
* Instant buy-backs and burns

🔐 Security & Transparency

* On-Chain Verification - All burn transactions verified on Solana
* Duplicate Prevention - Transaction signature tracking prevents reuse
* Price Tolerance - 5% slippage protection on burns
* Recent Transactions Only - Burns must be within 5 minutes

How It Works

Step-by-Step Process

1️⃣ Marketmaking Process (Every X Minutes)

// Automatic marketmaking startup sequence
1. Claim PumpFun creator fees → buy-back into token
2. Fetch live token price from DexScreener
3. Use Volume Bots to pump holder count


Process:
1. Connect Phantom/Solana wallet
2. System checks token balance via Helius RPC
3. Calculates USD value using live price
4. Buys back into the designated CA and burns the chosen supply
5. Volume bots value customization and % of creator rewards to be used

🛠️ Tech Stack

Frontend

* Vue 3 - Progressive JavaScript framework with Composition API
* Vue Router - SPA navigation with smooth scroll-spy behavior
* Pinia - Lightweight state management
* GSAP - High-performance animations & transitions
* Solana Web3.js - Blockchain interaction & wallet connection
* @solana/spl-token - SPL token operations
* Sass - CSS preprocessing with cloud/rain theme
* Vercel Analytics - Performance monitoring

Backend

* Deno - Secure TypeScript runtime for edge functions
* Supabase - PostgreSQL database + serverless functions
* TypeScript - Type-safe backend logic

Infrastructure

* Vercel - Frontend hosting with CDN
* Supabase - Backend services, database, cron jobs
* Helius RPC - Solana blockchain node access
* DexScreener API - Live token market data
* PumpFun API - Creator fee claims

Development Tools

* Vue CLI - Project scaffolding & build tooling
* ESLint - Code linting
* Babel - JavaScript transpilation
* Sass Loader - SCSS compilation

Acknowledgments

* Solana Foundation - For the amazing blockchain infrastructure
* Pump.fun - For the creator fee mechanism that funds our pools
* Helius - For reliable Solana RPC services
* Supabase - For the excellent backend platform
* Vue.js Community - For the fantastic framework and ecosystem