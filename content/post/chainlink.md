---
title: Paraswap to Use Chainlink Oracles for More Accurate and Reliable Pricing of ETH and ERC-20 Tokens
date: 2020-04-16
hero: "/images/chainlink.png"
excerpt: The three reasons why we switched to Chainlink - speed, price accuracy and security.
authors:
  - TokenBrice

---

At [Paraswap](https://paraswap.io/), we take pride in staying on the cutting edge of DeFi, constantly assessing the latest technology and seeing how it can integrate with our existing services. In fact, **maintaining strong composability** has been a major component of Paraswap’s success as a DEX aggregator, having integrated 15 different liquidity providers since inception.

In an effort to continue evolving, we have shifted some of our focus towards improving** Paraswap’s oracle mechanism** — an area of particular importance considering it’s the basis for comparing asset prices across different exchanges.

After extensive research into price oracle solutions, we are thrilled to announce that **Paraswap is now using Chainlink’s [Price Reference Contracts](https://feeds.chain.link/) **for more accurate and timely price feeds for ETH and ERC-20 tokens.**

### Why Chainlink?

As a DEX aggregator, Paraswap’s mission is more complex than it seems on the surface. Paraswap needs to fetch & aggregate the liquidity from all relevant DEXs for a particular trading pair. The best swapping path depends only on the assets themselves. ParaSwap picks the one that returns more of the target assets regardless of its fiat price.

Pricing is almost as critical as liquidity for a DEX aggregator. **When the prices are not accurate, the transaction failure rate increases**, which degrades the overall user experience. As Paraswap Founder Mounir Benchemled puts it:

> “Since the very beginning of Paraswap, I’ve been monitoring the transaction failure closely and deploying a lot of efforts to keep it within a reasonable range.”

Paraswap used to get its prices for ETH and ERC20 tokens directly from APIs, such as CoinGecko and CoinMarketCap. While satisfactory for initial deployment, switching to Chainlink’s Price Reference Contracts have three distinct advantages for Paraswap.


## 1/ Speed

Chainlink’s Price Reference Contracts store prices on-chain for most major ETH and ERC-20 trading pairs. As such, Paraswap’s systems can easily and cheaply read these on-chain prices and use them as the base price for determining which liquidity pools offer the best rates at a given moment in etime.


## 2/ Price Accuracy

Chainlink’s Price Reference Contracts provide accurate market data sourced from a pool of high-quality data aggregators. While Paraswap was already using aggregators, Chainlink further extends our market coverage by having **at least seven aggregators** present on each Price Reference Contract.


## 3/ Security

Chainlink’s Price Reference Contracts consist of decentralized oracle networks with 7–21 nodes each, which source data from at least seven different sources. Having decentralized aggregation at both the oracle and data levels provides enhanced security and reliability to the delivery and accuracy of Paraswap’s price feeds.

Ultimately, Paraswap wanted the best solution in the market, whether it be centralized or decentralized, to improve our system’s pricing. Chainlink not only offers that most performant solution, but it’s also decentralized, further aligning Paraswap with the ethos of decentralization permeating throughout DeFi.

![ParaSwap - Dune Analytics April 2020 stats](/images/dune-analytics-apr2020.png)
_Paraswap monthly transaction volume skyrocketed since the beginning of the year(Source: [Dune Analytics](https://explore.duneanalytics.com/public/dashboards/aWrmWKusSbMXegHoUaO46tYnAh2aHZBvQYq6eg82))_

Combining speed, accuracy, and security enables Paraswap to fetch accurate prices much quicker than calling APIs directly. **At the end of the day, transactions on Paraswap are settled on-chain, so on-chain solutions tend to be preferred.**

Additionally, switching to Chainlink as a price oracle was a future-facing decision. As DeFi continues to grow, having an on-chain price feed will become more and more useful, especially for complex DeFi tokens such as options positions. By integrating with Chainlink now, Paraswap is better set up to offer more advanced products in the future that require Chainlink’s Price Reference Contracts.


> “We are very excited to integrate Chainlink’s oracle network as a key component in further improving the speed, accuracy, and security of our DEX aggregator. Backed by an incredibly smart and responsive team, we were able to quickly integrate Chainlink’s oracle price feeds, bringing an immediate performance upgrade to Paraswap’s growing userbase.”>

> — Mounir Benchemled, Paraswap Founder

**About Paraswap**

[ParaSwap](https://paraswap.io/) aggregates the liquidity of exchanges and lending pools to provide a comprehensive access point to Ethereum’s decentralized finance ecosystem.

With a robust infrastructure harnessing relevant decentralized solutions such as Chainlink’s Price Reference Contracts, a 1000 ETH Nexus Mutual coverage or GasToken (GST2) for gas optimizations, ParaSwap consistently provides its users with the best prices.

If you’re a developer and want to enable access to DeFi services for your DApp users, feel free [to reach out](https://twitter.com/mounibec). We maintain a single access point seamlessly enabling speedy access to 15+ protocols, consistently, check [ParaSwap’s documentation](https://paraswapapi.docs.apiary.io/).

**About Chainlink**

If you’re a developer and want to connect your smart contract to existing data and infrastructure outside the underlying blockchain, reach out to us[ here](https://chainlink.typeform.com/to/gEwrPO)! We can help you quickly and securely launch your data-enabled application or[ Chainlink Price Reference Data Contract](https://feeds.chain.link/) on mainnet today. You can also visit the[ developer documentation](https://docs.chain.link/) or join the technical discussion on[ Discord](https://discordapp.com/invite/aSK4zew). Learn more by visiting the[ Chainlink website](https://chain.link/) or follow us on[ Twitter](https://twitter.com/chainlink) or[ Reddit](https://www.reddit.com/r/Chainlink/).

[Chainlink](https://chain.link/) is a decentralized oracle network that enables smart contracts to securely access off-chain data feeds, web APIs, and traditional bank payments. It is well known for providing highly secure and reliable oracles to large enterprises ([Google](https://cloud.google.com/blog/products/data-analytics/building-hybrid-blockchain-cloud-applications-with-ethereum-and-google-cloud),[Oracle](https://www.forbes.com/sites/darrynpollock/2019/07/30/oracle-building-a-virtuous-cycle-of-innovation-with-start-ups-through-chainlink-and-blockchain/#34cfc294ffcc), and[ SWIFT](https://create.smartcontract.com/sibos17)) and leading smart contract development teams such as[Polkadot/Substrate](https://medium.com/web3foundation/web3-foundation-and-chainlink-announce-collaboration-df55ed462a3a),[ Synthetix](https://blog.synthetix.io/synthetix-and-chainlink/),[ Loopring](https://medium.com/loopring-protocol/chainlink-and-loopring-collaborate-on-oracles-for-zkrollup-dex-protocol-c1c8094afc27),[ Aave](https://medium.com/aave/the-aave-oracle-network-powered-by-chainlink-is-now-live-45bb8a5a8c4e),[OpenLaw](https://medium.com/@OpenLawOfficial/openlaw-teams-with-chainlink-to-bring-real-world-info-to-smart-contracts-4e7a3dac80a8),[ Etherisc](https://blog.etherisc.com/etherisc-to-leverage-chainlink-oracles-for-decentralized-flight-insurance-product-9559b64d79c7),[Conflux](https://medium.com/@Confluxchain/conflux-partners-with-chainlink-to-enable-secure-connections-between-the-blockchain-and-75b2ae8ef176), and many others.
