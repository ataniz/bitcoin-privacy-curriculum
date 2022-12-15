```

This section analyses the identifiers users leak as they interact with the network, mainly thorugh wallet and node behavior. It also introduces meatspace dimenstion of the problem for example KYC and custodial scenarios, blockexplorers

TODO: find resources that explain different transaction types, usage of OP codes etc through examples and visuals
```
# Is Bitcoin Private?


where are you running your node (clearnet, tor, I2P)

[Map of the Bitcoin Network](https://medium.com/@gloriazhao/map-of-the-bitcoin-network-c6f2619a76f3) \\ node types

Node network activity
- broadcast behaviour
  - [transaction rebroadcasting](https://www.youtube.com/watch?v=v4TXfwwz_VI) //find the transcript

Light clients
    electrum based

>A common usage pattern for improved privacy is to use Bitcoin Core with [[https://github.com/chris-belcher/electrum-personal-server][electrum personal server]] or [[https://github.com/bwt-dev/bwt][bwt]]

Block filters
bip 157
bip 158

[BIP 158](https://github.com/bitcoin/bips/blob/master/bip-0158.mediawiki)


wallet related:

  Transaction Fingerprinting
      add info about transaction types and mentioned fileds

  https://github.com/achow101/wallet-fingerprinting

  https://b10c.me/observations/

  coin selection
  transaction fingerprinting


[mastering bitcoin transactions](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch06.asciidoc)
[mastering bitcoin advanced transactions (multisig segwit)](https://github.com/bitcoinbook/bitcoinbook/blob/develop/ch07.asciidoc)


## questions

- "-noboradcast" option, why enable?

- block explorers, IP <-> TXID
