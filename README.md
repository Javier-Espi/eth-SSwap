## 🌀 SimpleSwap

**SimpleSwap** is a smart contract that enables direct swapping between two ERC20 tokens. It supports basic liquidity management, LP token minting (Token L), and price calculation. The logic is intentionally streamlined to prioritize learning and clarity.

### 🎯 Purpose

This contract is intended for **educational purposes only**. It is designed to help developers understand how an Automated Market Maker (AMM)-style pool works, how token exchanges are calculated, and how liquidity provision functions at a fundamental level.

### 🧱 Design Principles

- **Single-pair focus**: limited to two tokens for simplicity and conceptual clarity.
- **Proportional minting**: LP tokens are issued in proportion to contribution vs. current reserves.
- **No swap fees**: the swap formula is applied without fees to highlight its raw behavior.
- **Babylonian root**: used to compute the initial liquidity seed for the pool.

### 🚀 Core Features

- Add and remove liquidity (`addLiquidity`, `removeLiquidity`)
- Perform swaps (`swapExactTokensForTokens`)
- Price quoting (`getPrice`)
- Output estimation (`getAmountOut`)

### 🛠️ Dependencies

- Solidity ^0.8.0
- OpenZeppelin Contracts

### 📄 License

MIT — free to fork, adapt, or build upon.
