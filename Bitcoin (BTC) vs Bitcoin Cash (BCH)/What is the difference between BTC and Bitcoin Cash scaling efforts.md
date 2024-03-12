---
Bitcoin (BTC) and Bitcoin Cash (BCH) differ fundamentally in their approaches to scalability. 

BTC retained a 1 MB block size limit and implemented Segregated Witness (SegWit) to address scalability issues. SegWit, introduced in 2017, separates signature data from transactions and provides a block space discount, effectively increasing the block size to around 1.8 MB. However, BTC's transaction capacity remains limited, maxing out at approximately 8 transactions per second, leading to high fees during network congestion. BTC's focus on a 1 MB block size, while ensuring a predictable blockchain size, comes with limitations in transaction throughput and cost, prompting users to consider the trade-offs based on their specific needs.

On the other hand, Bitcoin Cash removed the hard-coded block size limit entirely, starting with an 8 MB soft limit at the time of the fork. This allows for larger block sizes, significantly improving scalability. Subsequent upgrades increased the effective block size limit to 32 MB, with demonstrated possibilities of [256 MB](https://read.cash/@mtrycz/how-my-rpi4-handles-mining-256mb-blocks-3ca73237) and even [1 GB](https://read.cash/@mtrycz/how-my-rpi4-handles-mining-1gb-blocks-e5d09d83) blocks. 

In May of 2024, Bitcoin Cash will activate an [adaptive block size limit algorithm](https://gitlab.com/0353F40E/ebaa). This algorithm will constantly adjust the block size, with a baseline of 32 MB, as the needs of the network evolve. The update will allow the block size on Bitcoin Cash to grow as much as 2x per year. 

Bitcoin Cash's larger block sizes enable faster confirmation times, lower transaction fees, and a more efficient user experience, making it appealing for everyday transactions, microtransactions, and innovative use cases. The scalability improvements position Bitcoin Cash as a network with the potential for mass adoption and a broad range of practical applications.

Learn more in our [deep dive into the differences between BTC and Bitcoin Cash](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-1/#scalability-solutions).