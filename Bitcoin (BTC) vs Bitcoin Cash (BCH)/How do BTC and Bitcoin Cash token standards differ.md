Bitcoin (BTC), historically resistant to native token standards on its base layer, initially limited token functionality due to restrictions on adding arbitrary data to the blockchain. While token schemes have emerged on BTC's Lightning Network, their adoption faces challenges related to liquidity and routing.

The [Ordinals](https://docs.ordinals.com/introduction.html) phenomenon, leveraging the SegWit and Taproot upgrades, introduced a novel token layer to BTC. Ordinals assign unique identifiers to satoshis in the order they were mined, with attached inscriptions storing data. However, these tokens are not native to the BTC base layer, relying on third-party indexers for validation, sparking debates about network purpose, congestion, and security vulnerabilities.

Bitcoin Cash initially implemented the Simple Ledger Protocol (SLP) for token functionality, operating outside its base layer. SLP faced challenges with external indexers, but the experience guided developers toward refining protocols.

In May 2023, Bitcoin Cash implemented [CashTokens](https://cashtokens.org/), marking a significant advancement. CashTokens exist on the base layer, validated by miners, inheriting the same security and scripting functionality as native Bitcoin Cash units. This enables the implementation of a diverse range of smart contracts, leveraging Bitcoin Cash's superior scalability.

The introduction of [CashTokens Studio](https://cashtokens.studio/) and an open-source advanced [minting contract](https://github.com/cashninjas/minting-contract) has helped streamline token projects, offering a user-friendly approach for minting both fungible and non-fungible tokens.

Learn more in our [deep dive into the differences between BTC and Bitcoin Cash](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-5/#tokens).