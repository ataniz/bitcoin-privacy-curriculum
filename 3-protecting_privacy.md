```
This section introduces the technologies that are used to protect privacy and provide information security and resilience. It also aims to provide a social and historical context to the discussion.

TODO: talk to hennig and some other CTF people for inputs
```
# Protecting Privacy

[moral landscape of cryptographic work](https://www.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf)
    [presentation](https://www.youtube.com/watch?v=1ReIILmcLpk)


[what happened to the crypto dream pt1](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part1.pdf)
    [what happened to the crypto dream pt2](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part2.pdf)
    crypto for security and crypto for privacy is a sound seperation imo

Practice-Oriented Provable Security and the Social Construction of Cryptography
this idea could be connected with various federation designs where the security model relies on social trust and reputation
    https://cseweb.ucsd.edu/~mihir/papers/isw-pops.pdf
    https://www.cs.ucdavis.edu/~rogaway/papers/cc.pdf


[Steganography](https://en.wikipedia.org/wiki/Steganography)


### Crypto for security // not directly our scope so just leaving some practical and informative resources for the interested

[practical cryptography book](https://cryptobook.nakov.com/)

[crypto hack](https://cryptohack.org/)

<!-- encryption - probably better to just leave resources for the interested 
        cyphers
        symetric encryption - secret key encryption
            AES
        Asymetric encryption - public key cryptography
            RSA
            Eliptic Curve
                encrypting, decrypting, signing, validating signitures
            Deffie-Hellman Key exchange -->

<!-- attacks on encryption
        ciphertext only attack
        known plaintext attack
        chosen plaintext attack
        chosen ciphertext attack -->


### crypto for privacy

[OG ZK paper](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Zero%20Knowledge/Proofs_That_Yield_Nothing_But_Their_Validity_or_All_Languages_in_NP_Have_Zero-Knowledge_Proof_Systems.pdf)

[zero knowledge proofs](https://en.wikipedia.org/wiki/Zero-knowledge_proof)

[validity rollups](https://github.com/john-light/validity-rollups/blob/main/validity_rollups_on_bitcoin.md#-section-0-the-history-and-prehistory-of-validity-rollups-) // provides a bridge to bitcoin

[what are pederson commitments](https://crypto.stackexchange.com/questions/64437/what-is-a-pedersen-commitment)
    <!-- [Pederson commitments](https://link.springer.com/content/pdf/10.1007/3-540-46766-1_9.pdf#page=3) -->

[blind signatures](https://www.wikiwand.com/en/Blind_signature#References)

moon math 🤷🏻‍♂️


### networking

[VPN](https://en.wikipedia.org/wiki/Virtual_private_network)

[Tor network](https://en.wikipedia.org/wiki/Tor_(network))
    onion routing

[I2P network](https://en.wikipedia.org/wiki/I2P)
    garlic routing


<!-- (e.g. https://www.wireguard.com/wireguard/ https://tailscale.comtailscale/ https://github.com/juanfont/headscaleheadscale,  https://www.onioncat.org/onioncat,  https://www.gnunet.org/en/GNUnet, https://yggdrasil-network.github.io/Yggdrasil,  https://zerotier.com/ZeroTier,  etc..[fn::note that headscale is an unofficial self hosted version of tailscale and not all ZeroTier clients are fully open source]) -->
<!-- dont think these vpn implementations are relevant (i mean they are to me and to many self hosting folks but perhaps not as a part of the curriculum) -->

![](https://upload.wikimedia.org/wikipedia/en/f/f8/Internet_dog.jpg)

## might be relevant

self-hosting vs cloud

good security practices
    password manager

good privacy practices
    using email relays
    pseudonym accounts

social engineering
    (spear) fishing


## discussion questions

- In "what happened to the crypto dream?" author concludes that the cypherpunk dream is not materialized, make the case for and against the authors position.

- what are some challenges of communicating the importance of privacy to public?

- Is "anti-mass surveillance" a better framing then "privacy"? What are some other ways of communicating this message?

- Why, in bitcoin community, is there a negative sentiment towards relying on cloud services for running a node?

- Are P2P networks such as Tor of I2P viable networks for internet usage? What use cases and treat models would justify their high latency?

- VPN services are generally marketed as effective tools for privacy and circumventing censorship. How do they differ form networks such as I2P or Tor?



## relevant memes: 
memes are cultural artifacts that have survived the test of time in the domain of ideas. thinking deeply about them could provide insights to the fundamental tensions between different ideas and the position they take.



>"Don't trust, verify"

>"No security by obscurity"
>a cryptosystem should be secure even if everything about the system, except the key, is public knowledge.
\-“Kerckhoff's Principle”
    -> open source

>The universe believes in encryption. [..] Strong cryptography can resist an unlimited application of violence. No amount of coercive force will ever solve a math problem.
    [quote from Julian Assange](https://cryptome.org/2012/12/assange-crypto-arms.htm)



>But we discovered something. Our one hope against total domination. A hope that with courage, insight and solidarity we could use to resist. A strange property of the physical universe that we live in. The universe believes in encryption. It is easier to encrypt information than it is to decrypt it. We saw we could use this strange property to create the laws of a new world.71

Similarly, Edward Snowden writes:72

>In words from history, let us speak no more of faith in man, but bind him down from mischief by the chains of cryptography.73




funny article a came across
https://medium.com/@brannondorsey/wi-fi-is-broken-3f6054210fa5