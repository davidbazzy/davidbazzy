# Hi, I'm David 👋
**Software Engineer · Finance & Digital Assets**

---

## Experience

Professionally, I build and extend **Order Management Systems (OMS)** within equities — focused on performance, reliability and new features. 

## Digital Assets

I’ve been **crypto-native since 2017** as an investor and trader, and more recently as a **builder**.

My interest in digital assets comes from the **speed, transparency, and accessibility** of blockchain-based systems and how they reshape execution, settlement, and market structure.

## Interests

`Tokenized Real World Assets` `DeFi protocols` `Perpertual Futures` `On-chain market structure` `Execution & Settlement` `AI in finance` `trading systems`

---

## 🚀 Featured Projects

### 🔹 [Solana Wallet Tracker](https://github.com/davidbazzy/SolanaWalletTracker)
`Java` `PostgreSQL` `REST`

A multithreaded Java 21 desktop application for monitoring Solana wallets in real time. Aggregates token balances across multiple wallets, fetches token metadata via the Helius API, and pulls live USD pricing from Jupiter — all with batched requests and semaphore-controlled concurrency to manage rate limits. Backed by PostgreSQL with caching to reduce latency on repeated lookups.

`Java 21 virtual threads` `Helius API` `Jupiter API` `Solana RPC` `PostgreSQL`

---

### 🔹 [Search API](https://github.com/davidbazzy/SearchApi)
`Java` `Spring Boot` `pgvector`

A backend search API supporting unified search across clients and their documents. Client search uses substring matching; document search runs a hybrid pipeline combining semantic similarity (70%) via locally-embedded `all-MiniLM-L6-v2` vectors with PostgreSQL full-text ranking (30%). Vectors stored in PostgreSQL via pgvector with an HNSW index for sub-linear nearest-neighbour lookups — no external vector DB required. Fully containerised with Docker Compose.

`ONNX Runtime` `pgvector + HNSW` `Flyway` `Docker` `Spring Boot 4`

---

### 🔹 [Order Book](https://github.com/davidbazzy/OrderBook)
`Java`

A Java implementation of a simple single threaded order book engine supporting limit and iceberg order types.

`limit orders` `iceberg orders` `market microstructure`

---
