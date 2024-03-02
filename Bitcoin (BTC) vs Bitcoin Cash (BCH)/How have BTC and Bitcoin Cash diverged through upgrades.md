Bitcoin (BTC) and Bitcoin Cash (BCH) have diverged in many ways through upgrades on each chain, particularly through the numerous upgrades on Bitcoin Cash. The following categories illustrate many of the key divergences.

#### Block Size and Scalability:

* BTC: Maintained its 1 MB block size limit, relying on Segregated Witness (SegWit) and off-chain solutions like the Lightning Network for scalability. Results in a constantly congested network.
* Bitcoin Cash: Eliminated the hard block size limit and introduced a configurable block size. It successfully increased the Excessive Blocksize limit (EB) to 32 MB, aiming for higher throughput. A May 2024 upgrade will will activate an [adaptive block size limit algorithm](https://gitlab.com/0353F40E/ebaa) that will constantly adjust the block size, with a baseline of 32 MB, as the needs of the network evolve.

#### Transaction Policies:

* BTC: Retained its opt-in Replace-By-Fee (RBF) policy and is poised to introduce [full RBF by default](https://github.com/bitcoin/bitcoin/pull/28132).
* Bitcoin Cash: Removed RBF, emphasizing swift and hassle-free transactions in everyday commerce.

#### Address Format:

* BTC: Continued to use legacy addresses.
* Bitcoin Cash: Introduced [CashAddr](https://reference.cash/protocol/blockchain/encoding/cashaddr/) format for clarity and to prevent confusion with BTC addresses.

#### Opcodes:

* BTC: No significant introduction or reintroduction of opcodes.
* Bitcoin Cash: Reintroduced [old](https://upgradespecs.bitcoincashnode.org/may-2018-reenabled-opcodes/) [opcodes](https://github.com/bitcoincashorg/bitcoincash.org/commit/545cc027bc86c85dcbe478d1e82a40c2572bc2b5#diff-075fd7ce9e54a5f721a38cfe43e556064fa64708f65e9410405ba74f48acbe6c) and added new opcodes, providing flexibility for data manipulation, [native introspection](https://gitlab.com/GeneralProtocols/research/chips/-/blob/master/CHIP-2021-02-Add-Native-Introspection-Opcodes.md), and diverse applications.

#### OP_RETURN Size Increase:

* BTC: No change in OP_RETURN size.
* Bitcoin Cash: [Increased OP_RETURN](https://reviews.bitcoinabc.org/rABCcbf4410912f6512e481f15270329683d4d4378d4) size to 220 bytes, enabling more data storage for various applications. Enabled [multiple OP_RETURNs](https://upgradespecs.bitcoincashnode.org/CHIP-2021-03-12_Multiple_OP_RETURN_for_Bitcoin_Cash/).

#### Transaction Ordering:

* BTC: No standardized transaction ordering protocol.
* Bitcoin Cash: Implemented [Canonical Transaction Ordering](https://youtu.be/GYEZ52WVKEI?si=Gu2zt6dARMJ2gKIN) (CTOR) for consistent block reconstruction and improved block propagation.

#### Advancements in Block Propagation:

* BTC: No specific protocol introduced.
* Bitcoin Cash: Implemented [Graphene](https://cryptoeconomics.cs.umass.edu/graphene/explained.html) for faster block propagation. More advanced protocols like [XThinner](https://github.com/jtoomim/xthinner-spec) and [BlockTorrent](https://github.com/jtoomim/blocktorrent-python) in development.

#### External Message Validation:

* BTC: No specific opcodes for external message validation.
* Bitcoin Cash: Introduced [OP_CHECKDATASIG](https://mengerian.medium.com/the-story-of-op-checkdatasig-c2b1b38e801a) and OP_CHECKDATASIGVERIFY for validating messages from external oracles.

#### Schnorr Signatures:

* BTC: Implemented Schnorr signatures via the Taproot soft fork upgrade.
* Bitcoin Cash: Adopted [Schnorr signatures](https://upgradespecs.bitcoincashnode.org/2019-05-15-schnorr/) natively for enhanced privacy, scalability, and non-malleability.

#### Unconfirmed Transaction Chain Limit:

* BTC: Retained a limit on unconfirmed transaction chains.
* Bitcoin Cash: [Eliminated the limit](https://upgradespecs.bitcoincashnode.org/unconfirmed-transaction-chain-limit/), allowing flexibility in scenarios involving frequent transactions.

#### Difficulty Adjustment Algorithms:

* BTC: Continued with the [original difficulty adjustment algorithm](https://learnmeabitcoin.com/beginners/difficulty).
* Bitcoin Cash: Transitioned through [various algorithms](https://reference.cash/protocol/blockchain/proof-of-work/difficulty-adjustment-algorithm), including CW-144 and [ASERT](https://upgradespecs.bitcoincashnode.org/2020-11-15-asert/), for improved stability and block time targeting.

#### Double-Spend Detection:

* BTC: No network-wide standard for detecting double-spends.
* Bitcoin Cash: Introduced [Double-Spend Proofs](https://upgradespecs.bitcoincashnode.org/dsproof/) to provide merchants rapid notifications of attempted fraud.

#### Virtual Machine Improvements:

* BTC: No notable improvements to the virtual machine.
* Bitcoin Cash: Introduced [bigger script integers](https://gitlab.com/GeneralProtocols/research/chips/-/blob/master/CHIP-2021-02-Bigger-Script-Integers.md) and [Pay-To-Script-Hash-32](https://gitlab.com/0353F40E/p2sh32/-/tree/main), allowing for more powerful and secure options.

#### Tokens:

* BTC: No direct support for native tokens.
* Bitcoin Cash: Implemented [CashTokens](https://github.com/cashtokens/cashtokens), enabling native tokens on the blockchain with the power of BCH scripting capabilities, allowing for many new and diverse [use cases](https://www.youtube.com/watch?v=LT0veuGbYTQ).

#### UTXO Fastsync & UTXO Commitments:

* BTC: No specific protocols or plans for faster syncing.
* Bitcoin Cash: [In development](https://bitcoincashresearch.org/t/chip-2021-07-utxo-fastsync/502), allowing for faster and trustless syncing.

#### Reusable Payment Addresses:

* BTC: No specific plans for reusable payment addresses.
* Bitcoin Cash: [In development](https://github.com/imaginaryusername/Reusable_specs/blob/master/reusable_addresses.md), aiming to simplify recurring payments while maintaining privacy.

BTC has generally opted for conservative upgrades, off-chain scaling solutions, and maintaining a smaller block size. In contrast, [Bitcoin Cash's approach](https://upgradespecs.bitcoincashnode.org/) has been marked by frequent hard forks, rapid development, and a focus on on-chain scalability and usability. Both have evolved in response to their respective visions and community priorities.

Learn more in our [deep dive into the differences between BTC and Bitcoin Cash](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/).