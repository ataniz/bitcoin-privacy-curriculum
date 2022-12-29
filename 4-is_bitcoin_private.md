```
This section analyses patential identifiers and information users leak as they interact with the bitcoin network, mainly thorugh wallet and node behavior. It also introduces meatspace, non-blockcahin, dimenstion of the problem for example KYC and custodial scenarios, blockexplorers etc

```
# Is Bitcoin Private?




# node related

[transaction rebroadcasting](https://www.youtube.com/watch?v=v4TXfwwz_VI)

[Map of the Bitcoin Network](https://medium.com/@gloriazhao/map-of-the-bitcoin-network-c6f2619a76f3)

[BIP 37 proablems](https://en.bitcoin.it/wiki/BIP37_privacy_problems)

[Client-side block filtering](https://en.bitcoin.it/wiki/Client-side_block_filtering)

[Attacks on privacy (blockchain)](https://en.bitcoin.it/wiki/Privacy#Blockchain_attacks_on_privacy)
### Wallet related

[Bitcoin Script](https://en.bitcoin.it/wiki/Script)

[Bitcoin Transactions](https://en.bitcoin.it/wiki/Transaction)

[mastering bitcoin transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06.asciidoc)

[mastering bitcoin advanced transactions (multisig segwit)](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc)



### external information

[Attacks on privacy (non-blockchain)](https://en.bitcoin.it/wiki/Privacy#Non-blockchain_attacks_on_privacy)


TODO: coin selection
TODO: chain graph heuristics
TODO: KYC and transaction timing and amount knowledge


[Boltzman Script](https://medium.com/@laurentmt/introducing-boltzmann-85930984a159)

[Privacy on Lightning](https://github.com/lnbook/lnbook/blob/develop/16_security_privacy_ln.asciidoc)

[Miner Privacy](https://braiins.com/blog/data-privacy-and-security-for-bitcoin-miners)
bip69 input output ordering

['taint'](https://blockfi.com/prohibited-uses)
## discussion questions

- Discuss the privacy concerns towards the "store of value" and "medium of exchange" property of bitcoin.

- considering the value of privacy that was discussed in first section, argue for using a blockchain that does not provide privacy by default

- What is BIP 37, why was it problematic? How was/can the problems (be) addressed?

- How does receiver/sender anonymity compare in bitcoin and lightning?

- "-noboroadcast" option, why enable?

- do federated structures (in bitcoin & lightning) provide better privacy against an outside observer

- block explorers, IP <-> TXID

- Do 'unanounced channels' in lightningn network provide better 

- Does using taproot transactions (instead of segwit) provide better privacy to users? Is this true in practice?

- Consider the case of a "privacy nihilist" what are the worst practices an individual can follow to obtain the least amount of privacy for themselves and their transaction parties?


TODO: privacy and security are not always alligned, look at federated structures that provide better privacy but consideres a different security model. threat model is useful for prioritication of what is more important and what risk is more reasonable to take
  RBF, CPFP

## other resources

[Link Probability](https://gist.github.com/LaurentMT/d361bca6dc52868573a2)

[Entropy of a transaction](https://gist.github.com/LaurentMT/e758767ca4038ac40aaf)



https://github.com/achow101/wallet-fingerprinting
  
https://b10c.me/observations/
  