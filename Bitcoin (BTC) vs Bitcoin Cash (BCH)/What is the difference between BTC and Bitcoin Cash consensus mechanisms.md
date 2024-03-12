---
Bitcoin (BTC) and Bitcoin Cash (BCH) share an almost identical consensus mechanism rooted in the robust SHA-256 mining algorithm. Miners in both ecosystems dynamically switch between SHA-256 coins to maximize profitability. However, a single significant difference in their consensus mechanisms sets them on separate paths within the realm of mining and consensus.

In the [mining process](https://learnmeabitcoin.com/technical/mining), SHA-256 stands for "Secure Hash Algorithm 256-bit," a cryptographic hash function essential for Proof of Work (PoW) consensus. Miners compete to solve a mathematical puzzle using specialized computers, aiming to add a new block of transactions to the blockchain. The process involves finding a specific nonce that, when hashed with all other block data, meets certain criteria, making the resulting hash computationally expensive and time-consuming to alter.

The consensus in both BTC and Bitcoin Cash is achieved when the majority of miners agree on the validity of transactions and add them to the blockchain using the proof of work described above. This decentralized approach, backed by the cumulative computational power of miners, ensures the security and trustworthiness of the blockchain.

BTC's consensus relies on the chain with the most proof of work. In the event of alternative chains, the one with the most hashing difficulty is considered the correct blockchain, leading to occasional [chain reorganizations](https://learnmeabitcoin.com/technical/chain-reorganisation). 

Bitcoin Cash adopts a similar strategy but introduces rolling checkpoints. Blocks with at least 10 confirmations are deemed final and irreversible, providing resilience against deep reorg attacks. However, this introduces a slight risk of chain splits, prompting discussions within the Bitcoin Cash community on the necessity of rolling checkpoints as its hashrate approaches BTC's.

Learn more in our [deep dive into the differences between BTC and Bitcoin Cash](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-3/#consensus-mechanism).