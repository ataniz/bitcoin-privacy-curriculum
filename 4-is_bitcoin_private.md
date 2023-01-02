```
This section analyses patential identifiers and information users leak as they interact with the bitcoin network, mainly thorugh wallet and node behavior.
It also introduces meatspace, non-blockcahin, dimenstion of the problem for example KYC and custodial scenarios, blockexplorers, online unit conversion etc

```
# Is Bitcoin Private?



| source                                                                                                                               | status |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------ |
| **node related**                                                                                                                     | ------ |
| [transaction rebroadcasting](https://www.youtube.com/watch?v=v4TXfwwz_VI)                                                            |        |
| [Map of the Bitcoin Network](https://medium.com/@gloriazhao/map-of-the-bitcoin-network-c6f2619a76f3)                                 |        |
| [BIP 37 proablems](https://en.bitcoin.it/wiki/BIP37_privacy_problems)                                                                |        |
| [Client-side block filtering](https://en.bitcoin.it/wiki/Client-side_block_filtering)                                                |        |
| [Attacks on privacy (blockchain)](https://en.bitcoin.it/wiki/Privacy#Blockchain_attacks_on_privacy)                                  |        |
| **Wallet related**                                                                                                                   | ------ |
| [Bitcoin Script](https://en.bitcoin.it/wiki/Script)                                                                                  |        |
| [Bitcoin Transactions](https://en.bitcoin.it/wiki/Transaction)                                                                       |        |
| [mastering bitcoin - transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06.asciidoc)                            |        |
| [mastering bitcoin - advanced transactions (multisig segwit)](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc) |        |
| **external information**                                                                                                             | ------ |
| [Attacks on privacy (non-blockchain)](https://en.bitcoin.it/wiki/Privacy#Non-blockchain_attacks_on_privacy)                          |        |
| **other**                                                                                                                            |        |
| [Privacy on Lightning](https://github.com/lnbook/lnbook/blob/develop/16_security_privacy_ln.asciidoc)                                |        |
| [Miner Privacy](https://braiins.com/blog/data-privacy-and-security-for-bitcoin-miners)                                               |        |
| ['taint'](https://blockfi.com/prohibited-uses)                                                                                       |        |



## discussion questions

- If there was an ideal money, what properties would it possess?

- Discuss the privacy concerns towards the "store of value" and "medium of exchange" property of bitcoin.

- What is BIP 37, why was it problematic? How was the problems later addressed?

- How does receiver/sender anonymity compare in bitcoin and lightning?

- What is"-noboroadcast" option, why does some users recommend enabling it?

- What are federated structures (in bitcoin & lightning), what are the benefits and drawbacks for users?

- Do 'unannounced channels' in lightning network provide better privacy in reality?

- Does using taproot transactions (instead of segwit) provide better privacy to users and why? Is this true in practice?

- Consider the case of a "privacy nihilist" what are the worst practices an individual can follow to obtain the least amount of privacy for themselves and their transaction parties?

- what might be some reasons for a miner to be concerned about their privacy?

- what trade-offs a miner might consider before joining a central mining pool?

- Looking at the idea of 'taint', do you think it is an enforceable mechanism for censoring certain UTXOs?



## other resources

RBF, CPFP

bip69 input output ordering

nodes don't support encrypted p2p communications, 

TODO: txgraph heuristics

TODO: KYC and transaction timing and amount knowledge

[Link Probability](https://gist.github.com/LaurentMT/d361bca6dc52868573a2) & [Entropy of a transaction](https://gist.github.com/LaurentMT/e758767ca4038ac40aaf)


[wallet fingerprinting](https://github.com/achow101/wallet-fingerprinting) (similar to browser fingerprinting)
  
https://b10c.me/observations/
  