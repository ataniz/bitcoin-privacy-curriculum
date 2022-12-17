```

This section analyses the identifiers users leak as they interact with the network, mainly thorugh wallet and node behavior. It also introduces meatspace dimenstion of the problem for example KYC and custodial scenarios, blockexplorers

TODO: find resources that explain different transaction types, usage of OP codes etc through examples and visuals
```
# Is Bitcoin Private?


TODO: network that youre running your node (clearnet, tor, I2P)

[Map of the Bitcoin Network](https://medium.com/@gloriazhao/map-of-the-bitcoin-network-c6f2619a76f3) \\ node types

Node network activity
- [transaction rebroadcasting](https://www.youtube.com/watch?v=v4TXfwwz_VI) //find the transcript

TODO: Light clients
  electrum based
  Block filters
  bip 157
  [BIP 158](https://github.com/bitcoin/bips/blob/master/bip-0158.mediawiki)


wallet related:

  Transaction Fingerprinting
      add info about transaction types and mentioned fileds

  https://github.com/achow101/wallet-fingerprinting

  https://b10c.me/observations/

  wallet fee defaults

  RBF, CPFP

TODO: coin selection
  
TODO: chain graph heuristics

[mastering bitcoin transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06.asciidoc)
[mastering bitcoin advanced transactions (multisig segwit)](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc)


[Privacy on Lightning](https://github.com/lnbook/lnbook/blob/develop/16_security_privacy_ln.asciidoc)

## questions

- "-noboroadcast" option, why enable?

- block explorers, IP <-> TXID

- Do 'unanounced channels' in lightningn network provide better 