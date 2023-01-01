```
This section disscusses tools and practices for measuring and improving privacy while using bitcoin.


```
# Bitcoin & Privacy




| source                                                                                                                                                           | status |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| [bip 47 payment code](https://samourai.kayako.com/article/68-what-are-paynyms)                                                                                   |        |
| https://bitcoinops.org/en/topics/coinjoin/                                                                                                                       |        |
| [gmaxwell coinjoin](https://bitcointalk.org/index.php?topic=279249.0)                                                                                            |        |
| [WabiSabi](https://github.com/zkSNACKs/WabiSabi)                                                                                                                 |        |
| [payjoin](https://diyhpl.us/wiki/transcripts/london-bitcoin-devs/2020-05-05-socratic-seminar-payjoins/)                                                          |        |
| [joinmarket](https://www.youtube.com/watch?v=hJZnkm0jW5E)                                                                                                        |        |
| [Anonymous CoinJoin Transactions with Arbitrary Values](https://www.comsys.rwth-aachen.de/fileadmin/papers/2017/2017-maurer-trustcom-coinjoin.pdf)               |        |
| [coin selection](https://btctranscripts.com/scalingbitcoin/tokyo-2018/edgedevplusplus/coin-selection/)                                                           |        |
| [coinswap](https://bitcoinops.org/en/topics/coinswap/)                                                                                                           |        |
| [Sidechains](https://blockstream.com/sidechains.pdf) [see also](https://github.com/john-light/sidechains)                                                        |        |
| [rollups](https://github.com/john-light/validity-rollups/blob/main/validity_rollups_on_bitcoin.md)                                                               |        |
| [chaumian ecash](https://www.youtube.com/watch?v=VwMzNE1D3so)                                                                                                    |        |
| (miner privacy)[P2Pools](https://github.com/bitcoinbook/bitcoinbook/blob/77b91b1949e2c03a36c395586a44dac20ec41533/ch10.asciidoc#peer-to-peer-mining-pool-p2pool) |        |


## discussion questions

- what are the benefits of running a full node and interacting with the network through this node?  

- According to the white paper how does bitcoin network aims to maintain privacy? Is the method suggested in the paper compatible with today's common KYC practices?

- Is "cost of running a node" a relevant for usability of privacy?

- Looking at blockchains that are supporting confidential transactions, a question appears: Is "privacy by default" a valid reason for sacrificing "easy verifiably"? What are some other implications of having an "opaque" blockchain?

- Thinking about fungibility and 'taint' on coins . Consider a different approach, what if people voluntarily tainted their coins, would effective cencorship still be applied? How would the fungibility property be effected?

- Does coin swapping provide a protection against censorship? How is it different from 'playing musical chairs'? Does it really improve the overall fungibility of bitcoin? (what I mean here it that 'tainted' coins still stay 'tainted')

- Compare two join operations, coinjoin and payjoin. How do they differ?

- what are some challenges related to coinjoin operations? (liquidity, consensus, DoS vector)

- What are some anonymous ways of acquiring bitcoins?

- Do bip 57 payment adresses improve users privacy? Considering that payment adresses are also unique adresses, how are they better than using onchain adresses?

- what are P2Pools what advantages they provide to miners, what are the drawbacks? Could they provide better privacy?

## other things to be covered
attacks on bitcoin privacy, eclipse? miner cencorship?
federations (bitcoin beach wallet, chaumian mints), social 
on chain and off chain privacy
covert vs overt - payjoin vs coinjoin

lightning probing for channel balances
the cost of better privacy should be considered according to the treat model
randevue and trambolines in lightning
federated structures provide better privacy against an outside observer while requiring varied degrees of trust to the federation

(maay be relevant?)

[softchains](https://gist.github.com/RubenSomsen/7ecf7f13dc2496aa7eed8815a02f13d1)
or here https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-December/018331.html

[spacechains](https://medium.com/@RubenSomsen/21-million-bitcoins-to-rule-all-sidechains-the-perpetual-one-way-peg-96cb2f8ac302)
    https://www.youtube.com/watch?v=N2ow4Q34Jeg 

[whirpool](https://bitcoiner.guide/whirlpool/)

[electrum personal server](https://github.com/chris-belcher/electrum-personal-server)

[bwt](https://github.com/bwt-dev/bwt)

[nopara - Pay to endpoint](https://nopara73.medium.com/pay-to-endpoint-56eb05d3cac6)