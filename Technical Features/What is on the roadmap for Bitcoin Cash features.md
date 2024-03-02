Bitcoin Cash has an exciting roadmap that includes several key features and upgrades aimed at enhancing scalability, efficiency, and usability. Here are some of the notable features on the Bitcoin Cash roadmap:

#### Adaptive Block Size Limit Algorithm:

The [Adaptive Blocksize Limit Algorithm](https://gitlab.com/0353F40E/ebaa) (ABLA) is a significant upgrade expected in 2024. This algorithm proposes an automatic adjustment of Bitcoin Cash's effective block size limit based on usage metrics. It aims to mitigate challenges tied to manual coordination and reduce susceptibility to social attacks. The algorithm dynamically adjusts the block size limit, allowing for potential doubling annually during periods of maximum growth.

#### UTXO Fastsync & UTXO Commitments:

[UTXO Fastsync](https://bitcoincashresearch.org/t/chip-2021-07-utxo-fastsync/502) and UTXO commitments are innovations designed to improve node syncing. UTXO Fastsync enables nodes to quickly share and update information without the slow process of downloading the entire blockchain history. It introduces the concept of creating and sharing snapshots of the current state of the network, reducing syncing time to a couple of hours. UTXO commitments, still in development, involve miners committing to a specific set of UTXOs in blocks, providing proof of the network's state and enabling trustless syncing.

#### Reusable Payment Addresses:

[Reusable Payment Addresses](https://github.com/imaginaryusername/Reusable_specs/blob/master/reusable_addresses.md) (RPAs) are being developed to address privacy concerns associated with recurring payments. RPAs introduce an alias system that allows senders to generate a fresh address for any recipient with a handle. This system enhances privacy by eliminating the need to share a new address for every payment. Users and merchants can share a static paycode, and anyone can use that paycode to generate a fresh address for sending indistinguishable payments.

#### XThinner & Blocktorrent:

[XThinner and Blocktorrent](https://www.reddit.com/r/btc/comments/afeput/xthinnerblocktorrent_development_status_update/) are protocols aimed at speeding up block propagation. [XThinner](https://github.com/jtoomim/xthinner-spec) focuses on compression, reducing block data to about 12 to 16 bits per transaction, achieving a remarkable reduction of up to 99.6%. [Blocktorrent](https://github.com/jtoomim/blocktorrent-python) breaks down a block into small, independently verifiable chunks for transmission, improving block propagation performance. Both protocols showcase Bitcoin Cash's commitment to advancing scalability and performance in anticipation of potential increases in block size.

These features collectively demonstrate Bitcoin Cash's dedication to innovation, scalability, and user-friendly improvements. The roadmap reflects ongoing efforts to address challenges and position Bitcoin Cash as a robust and efficient blockchain network.

Learn more about upcoming developments and other Bitcoin Cash technical features in our [broad exploration of Bitcoin Cash upgrades](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/#bitcoin-cash-upgrades).