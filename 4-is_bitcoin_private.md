```
This section analyses patential identifiers and information users leak as they interact with the bitcoin network, mainly thorugh wallet and node behavior. It also introduces meatspace, non-blockcahin, dimenstion of the problem for example KYC and custodial scenarios, blockexplorers etc

```
# Is Bitcoin Private?


TODO: network that youre running your node (clearnet, tor, I2P)

[Map of the Bitcoin Network](https://medium.com/@gloriazhao/map-of-the-bitcoin-network-c6f2619a76f3) \\ node types

Node network activity
- [transaction rebroadcasting](https://www.youtube.com/watch?v=v4TXfwwz_VI) //find the transcript
dandelion

TODO: Light clients
  electrum based
  Block filters
  bip 157
  [BIP 158](https://github.com/bitcoin/bips/blob/master/bip-0158.mediawiki)

TODO: find resources that explain different transaction types, usage of OP codes etc through examples and visuals

wallet related:

  Transaction Fingerprinting
      add info about transaction types and mentioned fileds

  https://github.com/achow101/wallet-fingerprinting

  https://b10c.me/observations/

  wallet fee defaults

  RBF, CPFP

TODO: coin selection
TODO: chain graph heuristics
TODO: KYC and transaction timing and amount knowledge

[mastering bitcoin transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06.asciidoc)
[mastering bitcoin advanced transactions (multisig segwit)](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc)

[Entropy of a transaction](https://gist.github.com/LaurentMT/e758767ca4038ac40aaf)

[Link Probability](https://gist.github.com/LaurentMT/d361bca6dc52868573a2)

[Privacy on Lightning](https://github.com/lnbook/lnbook/blob/develop/16_security_privacy_ln.asciidoc)

## discussion questions

- considering the value of privacy that was discussed in first section, argue for using a blockchain that does not provide privacy for default

- How does receiver/sender anonymity compare in bitcoin and lightning?

- "-noboroadcast" option, why enable?

- do federated structures (in bitcoin & lightning) provide better privacy against an outside observer

- block explorers, IP <-> TXID

- Do 'unanounced channels' in lightningn network provide better 

- Using taproot transactions provide better privacy guarantees (TODO: WHY) to users. Is this true in practice?

TODO: privacy and security are not always alligned, look at federated structures that provide better privacy but consideres a different security model. threat model is useful for prioritication of what is more important and what risk is more reasonable to take