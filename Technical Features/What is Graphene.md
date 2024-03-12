---
[Graphene](https://cryptoeconomics.cs.umass.edu/graphene/explained.html) is a technology that marks a substantial leap forward in expediting block propagation within blockchain networks. It employs a combination of [bloom filters](https://en.wikipedia.org/wiki/Bloom_filter) and invertible bloom lookup tables to enable nodes to quickly identify missing transactions when receiving block data. While not a consensus rule itself, Graphene has been integrated into [Bitcoin Unlimited](https://www.bitcoinunlimited.info/), a widely used Bitcoin Cash node implementation.

Key features of Graphene include:

#### Accelerated Block Propagation:

Graphene is designed to accelerate the dissemination of block information throughout the network.

#### Bloom Filters and Invertible Bloom Lookup Tables:

It leverages bloom filters and invertible bloom lookup tables - innovative data structures - to facilitate efficient identification of missing transactions.

#### Swift Retrieval of Confirmed Transactions:

When a node broadcasts block information, Graphene aids in the rapid retrieval of all confirmed transactions within the block for receiving nodes.

#### Integration with Bitcoin Unlimited:

While Graphene itself is not a consensus rule, it has been integrated into Bitcoin Unlimited, oa widely-used node implementation in the Bitcoin Cash ecosystem.

#### Compatibility with CTOR:

When combined with Canonical Transaction Ordering (CTOR), another consensus change, Graphene contributes to the efficient and quick reconstruction and validation of new blocks.

Graphene's integration into Bitcoin Unlimited enhances the overall efficiency of block propagation, reducing latency and improving the speed at which nodes can receive and validate block data. This advancement is crucial for maintaining a responsive and competitive blockchain network with the prospect of continued growth.

Learn more about Graphene and other Bitcoin Cash technical features in our [broad exploration of Bitcoin Cash upgrades](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/#bitcoin-cash-upgrades).