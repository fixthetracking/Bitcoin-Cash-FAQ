---
Bitcoin Cash proponents believe that eventually Bitcoin Cash will be able to handle the financial transactions of the entire world. However, there is a lot of work to be done towards that goal.

### Theory:

Bitcoin Cash follows the original scaling plan proposed by Satoshi Nakamoto, the anonymous creator of Bitcoin. There are three main reasons to believe that Bitcoin Cash can continue scaling to global levels.

#### Inherent Parallelism:

In Bitcoin Cash transactions, each transaction is an independent logical unit that can be validated and processed using only its own inputs and outputs. The system is [embarrassingly parallel](https://en.wikipedia.org/wiki/Embarrassingly_parallel), allowing for easy distribution across multiple processors. Transaction chaining is supported without compromising this independence, as any invalidity in a parent transaction extends to its descendants. This contrasts with account model chains like Ethereum, where such independence is not maintained.

#### Hardware Improvements:

Innovation and advancement in hardware, encompassing bandwidth, storage, processing power, and cost, follow an upward trajectory that has persisted for decades. Bitcoin's foundational design aligns with this environment, and Bitcoin Cash benefits by adhering to the original on-chain scaling strategy. The entire computer hardware industry propels Bitcoin Cash scaling effortlessly, as ongoing technological improvements unfold. While global adoption is a gradual process, scaling challenges are organically addressed through the continuous enhancement of technology.

#### Pruned Nodes:

Critics' concerns about on-chain scaling overlook the original Bitcoin design, which doesn't mandate storing all transaction data forever. The UTXO set, containing essential blockchain information, grows slower than cumulative transaction data. Deleting spent transactions after a certain age is a pragmatic approach. In the future, pruned nodes and archival nodes will coexist, with archival nodes offering complete blockchain data as specialized services, meeting market demand for analytics. Thus a globally-scaled Bitcoin Cash can remain robust through the appropriate use of pruned nodes.


### Current Progress:

Bitcoin Cash has no hard limit on block size. However, there is an effective "soft limit" - an Excessive Blocksize limit (EB) - decided through consensus among the various node implementations and those who run them.

The current EB is set to 32 MB. If the typical transaction is 400 bytes, a single Bitcoin Cash block could theoretically fit 80,000 transactions. With 144 blocks in a day, that equates to 11.5 million transactions per day. If a typical person makes two electronic transactions per day, that would be enough to serve more than 5 million users. Of course, that is not nearly enough to serve the entire world. More is needed.

Bitcoin Cash researchers have already successfully tested block sizes of [256 MB](https://read.cash/@mtrycz/how-my-rpi4-handles-mining-256mb-blocks-3ca73237) and even [1 GB](https://read.cash/@mtrycz/how-my-rpi4-handles-mining-1gb-blocks-e5d09d83) on very modest hardware. Block sizes of 1 GB could allow more than 300 million users to transact per day - about the population of the United States.


### The Future:

In May of 2024, Bitcoin Cash is set to implement an [adaptive block size limit algorithm](https://gitlab.com/0353F40E/ebaa). This groundbreaking algorithm will continually adjust the block size, maintaining a baseline of 32 MB, to accommodate the network's changing requirements. The upcoming update will empower Bitcoin Cash's block size to expand by as much as 2x per year. 

For Bitcoin Cash to allow 8 billion users to make a few transctions per day, it would ultimately have to increase the current block size by a factor of 1,000 - to at least 32 GB. 8 billion users may be an overestimate as many people are small children and don't need to transact. At the same time, the block size should be able to handle burst activity in times of increased transaction demand. So 32 GB is likely a decent minimum target. 

There is a lot of work to do to get to 32 GB block sizes. But 32 GB is only a 32x increase from the 1 GB blocks that have already been successfully demonstrated. The adaptize block size limit algorithm can adjust up to that in as few as ten years. And a dramatically-growing Bitcoin Cash network would certainly generate considerable investigation into further scaling efforts on the hardware and software fronts. 

Considering Bitcoin Cash's inherent parallelism, the trajectory of computer technology over the last several decades, and the fact that nodes can be effectively pruned; the future of Bitcoin Cash looks very bright.