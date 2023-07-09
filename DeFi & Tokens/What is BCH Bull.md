# What is BCH Bull?


[BCH Bull](https://bchbull.com/) allows users to take either long positions (with leverage) or hedged positions on Bitcoin Cash against metals, fiat currencies, or other cryptocurrencies. This is all done entirely using smart contracts on Bitcoin Cash using the [AnyHedge Protocol](https://anyhedge.com/).

The contracts on BCH Bull are non-custodial. That means there is no third party that holds the funds. There are no borrowed assets (thus no risk of margin calls) and everything happens on the Bitcoin Cash blockchain. This ensures the contract executes as expected as no one is able to alter the terms or run off with the funds.

The AnyHedge contracts on BCH Bull get funded by two parties (the hedger and the speculator) at the same time. The hedger seeks to preserve the value of their Bitcoin Cash denominated in USD, BTC, gold, or whatever asset the parties choose. The speculator seeks to increase their Bitcoin Cash holdings, hoping for an increase in the price of Bitcoin Cash against the other asset. Both parties agree on a specific time for contract maturation, ranging from a few hours to a couple of months.

Using the agreed-upon terms of the contract and [price oracles](https://oracles.cash/) that regularly broadcast signed price messages on the Bitcoin Cash network, the contract has all the information it needs to appropriately pay out to the two parties upon maturation.

At maturation of the contract, the hedger will receive the same value they put into it at the beginning (denominated in the other asset), though the precise amount of Bitcoin Cash may be higher or lower, depending on the price changes during the contract. The speculator receives the rest of the Bitcoin Cash in the contract. 

Most BCH Bull contracts are leveraged 5x for the speculator. This is accomplished by the hedger putting four times as much Bitcoin Cash into the contract as the speculator. BCH Bull also offers other leveraged options.

Let's imagine an example of a 5x leverage BCH Bull contract where 1 BCH = $300 USD at the beginning of the contract. The hedger seeks to preserve $1200 worth of Bitcoin Cash and so puts 4 BCH into the contract. The speculator hopes for a rise in the price of Bitcoin Cash and puts $300 worth of Bitcoin Cash (1 BCH) into the contract. The contract contains a total of 5 BCH. The price of Bitcoin Cash against USD will determine what happens at the end of the contract. Let's go through a few scenarios.

If the price of Bitcoin Cash rises to $600 at the end of the contract, the hedger will receive $1200 worth of Bitcoin Cash (2 BCH), which is the same USD value they put into the contract at the beginning (though now the amount of BCH is less than before). The speculator will receive everything else - 3 BCH, equal to $1800 USD, realizing a profit of $1500 (5x more than they would have realized by simply holding onto their Bitcoin Cash). There is theoretically no limit to the percentage gains (in USD) the speculator can earn as the price of Bitcoin Cash rises (although there may be practical limits in place that will cause the contract to execute early). 

In another scenario, if the price of Bitcoin Cash falls to $250 at the end of the contract, the hedger will receive $1200 worth of Bitcoin Cash (4.8 BCH), which is the same USD value they put into the contract at the beginning (and now the amount of BCH is more than before). The speculator will receive everything else - 0.2 BCH, equal to $50 USD, realizing a loss of $250 (5x more than they would have realized by simply holding onto their Bitcoin Cash). 

If the price of Bitcoin Cash falls far enough, the contract may execute early due to the speculator being liquidated. That happens at the price at which there is nothing left for the speculator as the entire contract needs to be paid out to the hedger. 

This would happen in our scenario if the price of Bitcoin Cash falls to $240. In that case the hedger will receive $1200 worth of Bitcoin Cash (5 BCH), which is the same USD value they put into the contract at the beginning (but now 25% more BCH than before). Since the entire contract only had 5 BCH, the speculator is liquidated and will receive nothing. The speculator thus loses $300 worth of Bitcoin Cash (5x more than they would have lost by simply holding onto their Bitcoin Cash). If liquidation happens before the scheduled maturation of the contract, the contract will execute early.

There is always a counterparty on the other side of any given contract on BCH Bull. Often the counterparty is a liquidity provider who may charge (or offer) [premiums](https://bchbull.com/premiums) to any BCH Bull user, depending on market conditions. BCH Bull also offers peer-to-peer contracts, connecting potential hedgers and speculators without the need of funds from a liquidity provider.

For questions and discussions about BCH Bull, see the [BCH Bull Telegram Channel](https://t.me/bchbull).