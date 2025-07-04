# 🚀 Moon Rocketeer

**Moon Rocketeer** is a secure web platform and AI-powered trading system that helps users go from **TradingView alerts** to **verified, high-quality trades** on the **Hyperliquid DEX**.  
Only the best trade setups are cleared for launch.

---

## 🌌 Overview

How it works. 
1. 📈 Traders add our premium indicator is added to their charts in TradingView
2. 🛎️ When a **BUY/SELL alert** fires, a **callback webhook** is made to our backend.
3. 💯 Once our system **authenticates the signal** as authentic, the trade request is forwarded to our AI agent, DEXter
4. 🤖 DEXter **assesses the trade** using on-chain data, technical signals, and recent trends.
5. 🆗 If the assessment passes, DEXter **places a SPOT or LIMIT order with Hyperliquid**.
6. 🆖 If the assessment fails, DEXter **does not proceed with placing an order**.

> ✅ No blind trades. Only intelligent launches.

---

## 🛠 Features

- 🔑 **API key generation** for premium users (subscription-based)
- 📡 **Webhook endpoints** to receive TradingView alerts
- 🧠 **AI agent** using LangChain to verify trade signals
- ⚙️ **Trade execution** on Hyperliquid (spot/futures)
- 📊 Admin dashboard to manage users, keys, and logs

---

## 🧠 Tech Stack

| Layer         | Stack                        |
|---------------|------------------------------|
| Web UI        | React, Tailwind, ShadCN UI   |
| Backend API   | FastAPI / Next.js API routes |
| AI Agent      | LangChain + Python + Redis   |
| Payments      | Stripe (subscription plans)  |
| Wallet        | Coinbase Wallet SDK          |
| DEX Integration | Hyperliquid REST/WebSocket APIs |
| DB            | PostgreSQL / Supabase        |
| Containerization | Docker, Docker Compose    |

---

## 🚀 Getting Started


