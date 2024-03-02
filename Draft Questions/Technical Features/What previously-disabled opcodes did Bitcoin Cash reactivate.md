Bitcoin Script, serving as the language for transactions, initially included various opcodes that were largely dormant during the cryptocurrency's early years. However, in 2010, the identification of bugs related to certain opcodes raised concerns about potential node crashes and unauthorized spending of coins. As a precautionary measure, numerous unexplored opcodes, including splicing, logical, and arithmetic operations, were disabled. This removal deprived the Bitcoin community of the chance to explore applications utilizing these functionalities.

Bitcoin Cash reactivated numerous opcodes between [2018](https://upgradespecs.bitcoincashnode.org/may-2018-reenabled-opcodes/) and [2019](https://github.com/bitcoincashorg/bitcoincash.org/commit/545cc027bc86c85dcbe478d1e82a40c2572bc2b5#diff-075fd7ce9e54a5f721a38cfe43e556064fa64708f65e9410405ba74f48acbe6c). These re-enabled opcodes encompass a range of functionalities, including splicing, bitwise logic, arithmetic, and more. The reintroduction of these fundamental building blocks allows for straightforward data manipulation with minimal overhead. This restoration of opcodes provides developers with greater flexibility, enabling them to create custom transactions and explore a variety of applications.

The re-enabled opcodes include:

* OP_CAT
* OP_AND
* OP_OR
* OP_XOR
* OP_MUL
* OP_DIV
* OP_MOD
* OP_LSHIFT
* OP_RSHIFT

Learn more about the re-enabled opcodes and other Bitcoin Cash technical features in our [broad exploration of Bitcoin Cash upgrades](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/#bitcoin-cash-upgrades).