```
This section disscusses tools and practices for measuring and improving privacy while using bitcoin

TODO: talk to burak to create a scripting demo
```
# Bitcoin & Privacy

on chain and off chain privacy


bip 47 payment code https://samourai.kayako.com/article/68-what-are-paynyms



covert vs overt - payjoin vs coinjoin

>A common usage pattern for improved privacy is to use Bitcoin Core with 
[electrum personal server](https://github.com/chris-belcher/electrum-personal-server)
[bwt](https://github.com/bwt-dev/bwt)


coinjoin 
    https://bitcoinops.org/en/topics/coinjoin/
    https://bitcointalk.org/index.php?topic=279249.0
    https://github.com/zkSNACKs/WabiSabi


[Anonymous CoinJoin Transactions with Arbitrary Values](https://www.comsys.rwth-aachen.de/fileadmin/papers/2017/2017-maurer-trustcom-coinjoin.pdf) //knapscak coinjoins


[coinswap](https://bitcoinops.org/en/topics/coinswap/)

[Attacks on privacy](https://en.bitcoin.it/wiki/Privacy#Blockchain_attacks_on_privacy)

[Sidechains](https://blockstream.com/sidechains.pdf)
    [see also](https://github.com/john-light/sidechains)

[rollups](https://github.com/john-light/validity-rollups/blob/main/validity_rollups_on_bitcoin.md) 

TODO: attacks on bitcoin privacy, eclipse? miner cencorship?

TODO: federations (bitcoin beach wallet, chaumian mints), social 


## discussion questions

- Looking at blockchains that are supporting confidential transactions, a question appears: Is "privacy by default" a valid reason for sacrificing "easy verifiably"? What are some other implications of having an "opaque" blockchain?


- Does coin swapping provide a protection against censorship? How is it different from 'playing musical chairs'? Does it really improve the overall fungibility of bitcoin? (what I mean here it that 'tainted' coins still stay 'tainted')

- Compare two join operations, coinjoin and payjoin. What are the 

TODO: randevue and trambolines in lightning

- What are some anonymous ways of acquiring bitcoins?

- Do bip 57 payment adresses improve users privacy? Considering that payment adresses are also unique adresses, how are they better than using onchain adresses?


TODO: the cost of better privacy should be considered according to the treath model



<!-- ## maaay be relevant // or not really...

[softchains](https://gist.github.com/RubenSomsen/7ecf7f13dc2496aa7eed8815a02f13d1)
or here https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-December/018331.html
[spacechains](https://medium.com/@RubenSomsen/21-million-bitcoins-to-rule-all-sidechains-the-perpetual-one-way-peg-96cb2f8ac302)
    https://www.youtube.com/watch?v=N2ow4Q34Jeg -->


