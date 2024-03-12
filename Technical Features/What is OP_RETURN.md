---
### Before the 2017 BTC/Bitcoin Cash Split:

[OP_RETURN](https://learnmeabitcoin.com/technical/nulldata) has been a crucial feature since the early days of Bitcoin, allowing users to store data on the blockchain. From the initial stages, users have always found ways to insert arbitrary data into Bitcoin transactions. Some community members opposed the idea of storing non-transaction-specific data in the Bitcoin blockchain. To address this, OP_RETURN emerged as a [compromise](https://blog.bitmex.com/dapps-or-only-bitcoin-transactions-the-2014-debate/). This opcode designates an output as provably unspendable, enabling the insertion of arbitrary data into transactions while allowing nodes to prune the data if desired.

Initially allowing data up to 10,000 bytes, these transactions were considered non-standard, leading nodes to refuse to relay them. In 2014, the standardization of relaying OP_RETURN transactions was implemented, permitting a size of up to 40 bytes. The decision to limit it was driven by concerns about specific use cases surrounding OP_RETURN, such as spam. Despite frustrations and debates about expanding its data capacity, the relay limit was eventually raised to the initially proposed 80 bytes in 2016.

### Post-Split:

#### Larger OP_RETURN:

In [2018](https://reviews.bitcoinabc.org/rABCcbf4410912f6512e481f15270329683d4d4378d4), Bitcoin Cash nodes collectively increased the maximum size of OP_RETURN outputs from 80 bytes to 220 bytes. This expansion significantly increased the capacity for arbitrary data storage within the blockchain. The decision aimed to accommodate the persistent interest in injecting data into the blockchain and discourage alternative methods that might burden nodes with additional data parsing tasks.

The larger capacity of 220 bytes enables various applications, including contract metadata storage, on-chain social media platforms, and colored coin protocols. Since OP_RETURN outputs are unspendable, they can be safely ignored by unconcerned parties. Allocating 220 bytes for data storage ensures that OP_RETURN remains the most practical and efficient method for storing data on the blockchain.

#### Multiple OP_RETURNs:

In [2021](https://upgradespecs.bitcoincashnode.org/CHIP-2021-03-12_Multiple_OP_RETURN_for_Bitcoin_Cash/), Bitcoin Cash nodes introduced a new standard allowing the inclusion of multiple OP_RETURN outputs in a single transaction. This update enhances the functionality of OP_RETURN, providing developers with flexibility for experimenting with new features without disrupting existing systems.

The introduction of multiple OP_RETURNs unleashes the full potential of OP_RETURN’s experimental expressiveness, simplifying the development process for its capabilities. Developers can now build upon these capabilities more easily, avoiding the complications of parsing scripts or the need to distribute efforts across multiple transactions.

Learn more about OP_RETURN and other Bitcoin Cash technical features in our [broad exploration of Bitcoin Cash upgrades](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/#bitcoin-cash-upgrades).