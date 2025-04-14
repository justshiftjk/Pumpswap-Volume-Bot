# Pump.fun AMM Volume Bot

A high-performance automated trading bot engineered to interact seamlessly with the **Pump.fun AMM** platform. This bot is designed to simulate organic trading volume by distributing SOL across multiple wallets, executing continuous buy/sell operations, and managing token accounts efficiently.

---

## 📌 Features

### ✅ Automated Wallet Management
- Programmatically creates multiple wallets.
- Automatically funds each wallet with SOL via airdrops or configured sources.

### ✅ Dynamic Token Trading
- Executes randomized buy operations on selected Pump.fun swap pools.
- Sells accumulated tokens from older wallets based on configurable strategies.

### ✅ Token Account Lifecycle Handling
- Periodically scans and processes existing wallets.
- Automatically:
  - Sells remaining token balances.
  - Withdraws residual SOL.
  - Closes associated token accounts (ATAs) to reclaim rent.

### ✅ Transaction Logging & Analytics
- Real-time logging of all executed swap transactions.
- Tracks volume metrics and token performance data.

### ✅ Integrated PumpSwap SDK
- Leverages a reliable SDK to:
  - Fetch pool data.
  - Calculate expected input/output.
  - Handle slippage.
  - Execute swaps efficiently.

### ✅ Highly Configurable Parameters
- Customize:
  - Buy/sell frequency and intervals.
  - Token allocation strategies.
  - Wallet distribution logic.
  - Minimum/maximum thresholds.

---

## 💡 Use Cases

- Simulate organic volume for newly launched tokens on Pumpswap.
