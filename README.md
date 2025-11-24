# 🌵 Cactus Protocol: The Future of Solana Smart Contracts

**Cactus Protocol** introduces **CactUScript**, a secure, high-performance, and developer-friendly programming language designed specifically for building efficient and complex decentralized applications (dApps) on the Solana ecosystem.

## 🌟 Mission

Our mission is to lower the barrier to entry for secure smart contract development on Solana while maximizing transaction efficiency and leveraging the platform's native speed and low transaction costs.

## 🔥 Key Features

### 1. CactUScript Language
* **Safety First:** Features a static type system and built-in checks to mitigate common smart contract vulnerabilities.
* **Solana Native:** Compiles directly into **eBPF** bytecode for maximal performance on the Solana Virtual Machine (SVM).
* **Simple Syntax:** Syntax inspired by popular languages like Python and TypeScript for faster developer adoption.

### 2. Built-in Composability
* **Simplified CPIs (Cross-Program Invocations):** CactUScript makes it intuitive to call and interact with other Solana programs (like the SPL Token Program or external DEXes).

### 3. CactusSwapRouter
* A reference implementation demonstrating **CactUScript's** power in handling multi-step DeFi logic, fees, and external program calls in a single, safe transaction.

---

## 🚀 Getting Started (The Compiler)

### Prerequisites

1.  **Rust:** (The compiler will be written in Rust.)
2.  **Solana Tool Suite:** For local development and testing.
3.  **Anchor CLI:** Recommended for managing Solana workspaces.

### Compiling a Program

The final compiler will be used as follows:
```bash
./target/release/cactusc compile ./programs/CactusSwapRouter/src/main.cactus
