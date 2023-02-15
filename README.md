# 🕹⛓ mev toolkit


<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/1130416/210285135-2d0c3965-a3cd-44f7-a167-3ec14a9ad695.png" width="50%" align="center" style="padding:1px;border:1px solid black;"/>
 </p>


<br>

## tl; dr

<br>

#### 👾 maximal extractable value (MEV) encompasses the profits generated by participant parties in the block production supply chain. for searchers, this revenue can be generated from arbitrage when reducing the price spread between markets, slippage loss of swap users, frontrunning users' transactions, among other [strategies](MEV_strategies).

#### 👾 the public discussion around MEV started by [pmcgooohan](https://twitter.com/pmcgoohancrypto?lang=en) on [e/ethereum](https://www.reddit.com/r/ethereum/comments/2d84yv/miners_frontrunning/), and it was formalized by [phildaiann et. al](https://twitter.com/phildaian)'s paper [flash boys 2.0](https://arxiv.org/abs/1904.05234). 

#### 👾 MEV extraction can be a force of good in a non-predatory and [fair](https://twitter.com/bertcmiller/status/1456346690164768770) blockspace free-market as an incentive for economic security. every actor in the supply chain is relevant. order flow toxicity is a trader's exposure to counter-parties that possess private informational advantages. as everything in life, *the most valuable commodity is information*.

#### ⚠️ this repository is an ongoing boundless catalog from my own research. therefore, no guarantees, use it at your own risk.


<br>


---

## 🏄🏽 resources && code

<br>

### extraction strategies

<br>

##### atomic (tx ordering)

* [sniping](MEV_strategies/sniping)
* [longtails](MEV_strategies/longtails)
* [atomic arbs](MEV_strategies/atomic_arb)
* [sandwiches](MEV_strategies/sandwich)
* [flashloans](MEV_strategies/flashloans)
* [jit liquidity](MEV_and_trading/protocols/uniswap/uniswap-v3/just-in-time.md)
* [liquidations](MEV_strategies/liquidations)
* [frontrunning](MEV_strategies/frontrunning)
* [backrunning](MEV_strategies/backrunning)


##### statistical (informed signal)

* [statistical arbs](MEV_strategies/stat_arb)
* [oracles and twamm](MEV_strategies/oracles)



<br>

### mev on the chains

* [mev on solana](MEV_by_chains/MEV_on_Solana)
* [mev on cosmos](MEV_by_chains/MEV_on_Cosmos)
* [mev on polygon](MEV_by_chains/MEV_on_Polygon)
* [mev on arbitrum](MEV_by_chains/MEV_on_Arbitrum)
* [mev on optimism](MEV_by_chains/MEV_on_Optimism)
* [mev on ethereum](MEV_by_chains/MEV_on_Ethereum)
* [mev on bsc chain](MEV_by_chains/MEV_on_BSC)
* [mev on avalanche](MEV_by_chains/MEV_on_Avalanche)


<br>

### building a toolkit

<br>

* [mev projects](MEV_projects)
* [defi and trading](MEV_and_trading)
* [build your mev bot](MEV_searchers)
* [cross-domain mev](MEV_searchers/cross_domain_mev)
* [data and analytics](MEV_searchers/data_and_analytics)
* [latency optimization](MEV_searchers/latency)
* [exclusive order flows](MEV_searchers/private_order_flows)
* [mempools monitoring](MEV_searchers/mempool_monitoring)
* [tx and signature explorers](MEV_searchers/tx_and_signature_explorers)

<br>


---

## 🏂 canonical readings

<br>


- [mev and me, by paradigm](https://research.paradigm.xyz/MEV)
- [flash boys 2.0, by p. daian et al.](https://arxiv.org/pdf/1904.05234.pdf)
- [return to the dark forest, by rekt](https://rekt.news/return-to-the-dark-forest/)
- [hiding in plain sight, by samczsun](https://samczsun.com/hiding-in-plain-sight/)
- [we live in a mempool, by tom schmidt](https://medium.com/dragonfly-research/we-live-in-a-mempool-backrunning-the-mev-crisis-a4ea0b493b05)
- [escaping the dark forest, by samczsun](https://samczsun.com/escaping-the-dark-forest/)
- [ethereum is a dark forest, by paradigm](https://www.paradigm.xyz/2020/08/ethereum-is-a-dark-forest)
- [towards a theory of mev I, by diamandis et al.](https://people.eecs.berkeley.edu/~ksk/files/MEV_CFMM.pdf)
- [how to light up the dark forest, by robert miller](https://writings.flashbots.net/writings/the-anatomy-of-an-inspector/)
- [the 0 to 1 guide to mev, by blockchain at berkeley](https://calblockchain.mirror.xyz/c56CHOu-Wow_50qPp2Wlg0rhUvdz1HLbGSUWlB_KX9o)
- [how to build an ethereum mining pool, by dragonfly](https://medium.com/dragonfly-research/how-to-build-an-ethereum-mining-pool-6be356520b7a)
- [how i learned to stop worrying and love mev, by sreeni](https://medium.com/dragonfly-research/dr-reorg-or-how-i-learned-to-stop-worrying-and-love-mev-2ee72b428d1d)
- [the enemy of your enemy is not your friend, by kobayashi](https://fiona.mirror.xyz/QXdCOAggA5g_j5R_JpO-V5LqK89EbimnYIV6c2rOsT0)
- [mev on ethereum: a policy analysis, by m. barczentewicz](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4332703)
- [censorship resistance in on-chain auctions, by m. pai et al.](https://github.com/eljhfx/Decentralized-Auctions/blob/main/Censorship_Resistance_in_On-Chain_Auctions.pdf)
- [wrecking sandwich traders for fun and profit, by n. worsley](https://github.com/Defi-Cartel/salmonella)
- [foundations of blockchains and mev, by tim roughgarden](https://timroughgarden.github.io/fob21/)
- [tricking frontrunners into being transaction relayers, by sankar4033](https://ethresear.ch/t/surrogeth-tricking-frontrunners-into-being-transaction-relayers/6937/1)
- [implementing ethereum trading front-runs on the bancor exchange, by ivan bogatyy](https://hackernoon.com/front-running-bancor-in-150-lines-of-python-with-ethereum-api-d5e2bfd0d798)
- [quantifying blockchain extractable value: how dark is the forest?, by kaihua qin et al.](https://arxiv.org/pdf/2101.05511.pdf)
- [transparent dishonesty: front-running attacks on blockchain, by shayan eskandari et al.](https://arxiv.org/pdf/1902.05164.pdf)





<br>


---


## ⛷ [bonus] 𝕥𝕙𝕖 𝕞𝕒𝕜𝕖 𝕠𝕗 𝕒 𝕔𝕪𝕡𝕙𝕖𝕣𝕡𝕦𝕟𝕜

<br>

* [teal organizations wiki](https://reinventingorganizationswiki.com/)
* [the hacker manifest, by the mentor](http://phrack.org/issues/7/3.html)
* [bitcoin whitepaper by satoshi nakamoto](https://bitcoin.org/bitcoin.pdf)
* [the cypherpunk manifest, by eric hughes](https://activism.net/cypherpunk/manifesto.html)
* [the meaning of decentralization, by vitalik](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274)
* [the crypto anarchist manifest, by timothy c. may](https://nakamotoinstitute.org/crypto-anarchist-manifesto/)
* [a graduate course in applied cryptography, by dan boneh](http://toc.cryptobook.us/)

<br>
<br>

