```
This section introduces the technologies that are used to improve privacy and security of the information. It also aims to provide a social and historical context to the discussion.

```
## Protecting Privacy

![](https://upload.wikimedia.org/wikipedia/en/f/f8/Internet_dog.jpg)

[moral landscape of cryptographic work](https://www.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf) & [presentation](https://www.youtube.com/watch?v=1ReIILmcLpk)

[bitcoin is worse is better](https://www.gwern.net/Bitcoin-is-Worse-is-Better)

<!-- crypto for security and crypto for privacy is a sound seperation imo -->
[what happened to the crypto dream pt1](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part1.pdf) & [pt2](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part2.pdf)
  



## Crypto

[Steganography - Hiding the act of hiding](https://en.wikipedia.org/wiki/Steganography)

[encryption primer](https://www.cs.princeton.edu/~felten/encryption_primer.pdf)

[Symmetric Cryptography](https://en.wikipedia.org/w/index.php?title=Symmetric-key_algorithm)

[Public Key Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)

[zero knowledge proofs](https://www.esat.kuleuven.be/cosic/blog/co6gc-introduction-to-zero-knowledge-proofs-1/) (wikipedia page is also good)

[validity rollups](https://github.com/john-light/validity-rollups/blob/main/validity_rollups_on_bitcoin.md#-section-0-the-history-and-prehistory-of-validity-rollups-) // provides a bridge to bitcoin

[what are pederson commitments](https://crypto.stackexchange.com/questions/64437/what-is-a-pedersen-commitment)

[blind signatures](https://www.wikiwand.com/en/Blind_signature#References)

moon math 🤷🏻‍♂️

[eliptic curve](https://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/)

## networking

[VPN](https://en.wikipedia.org/wiki/Virtual_private_network)

[Tor network](https://en.wikipedia.org/wiki/Tor_(network))
    onion routing

[I2P network](https://en.wikipedia.org/wiki/I2P)
    garlic routing



## keywords

cryptography, symmetric cryptography, private key cryptography, morality, Tor, I2P

## discussion questions

- What are [cryptographic primitives](https://en.wikipedia.org/wiki/Cryptographic_primitive), which ones bitcoin use and for what purphose

- What are the aims of information security?

- What are the aims of privacy enhancing technologies?

- In "what happened to the crypto dream?" author concludes that the cypherpunk dream is not materialized, make the case for and against the authors position.

- what are some challenges of communicating the importance of privacy to public?

- Is "anti-mass surveillance" a better framing then "privacy"? What are some other ways of communicating this message?

- Why, in bitcoin community, is there a negative sentiment towards relying on cloud services for running a node?

- "Trust" is a word often appears in Bitcoin Whitepaper. How does trust on third parties, individual taking responsibility and privacy are related?

- Are P2P networks such as Tor of I2P viable networks for daily internet usage? What use cases and treat models would justify their high latency?

- VPN services are generally marketed as effective tools for privacy and circumventing censorship. How do they differ form networks such as I2P or Tor? 

- what are some main differences between I2P and Tor network? How do they differ in terms of scalability?

- Why are most messaging and emailing apps still don't support basic encryption?

## relevant material


>"Don't trust, verify"


>"No security by obscurity"


>a cryptosystem should be secure even if everything about the system, except the key, is public knowledge.
\-“Kerckhoff's Principle”
    -> open source

>The universe believes in encryption. [..] Strong cryptography can resist an unlimited application of violence. No amount of coercive force will ever solve a math problem.
    [quote from Julian Assange](https://cryptome.org/2012/12/assange-crypto-arms.htm)


>But we discovered something. Our one hope against total domination. A hope that with courage, insight and solidarity we could use to resist. A strange property of the physical universe that we live in. The universe believes in encryption. It is easier to encrypt information than it is to decrypt it. We saw we could use this strange property to create the laws of a new world.

>In words from history, let us speak no more of faith in man, but bind him down from mischief by the chains of cryptography.


\-Edward Snowden


[funny article I came across](https://medium.com/@brannondorsey/wi-fi-is-broken-3f6054210fa5)


[Original? ZK paper](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Zero%20Knowledge/Proofs_That_Yield_Nothing_But_Their_Validity_or_All_Languages_in_NP_Have_Zero-Knowledge_Proof_Systems.pdf)

[Pederson commitments](https://link.springer.com/content/pdf/10.1007/3-540-46766-1_9.pdf#page=3)

## potentially relevant expolarations

self-hosting vs cloud

good security practices
    password manager

good privacy practices
    using email relays
    pseudonym accounts
    TODO: a question regarding methods for being prepared for such leaks, using email relays, one time passwords, random usernames

social engineering
    (spear) fishing

Practice-Oriented Provable Security and the Social Construction of Cryptography. this idea could be connected with various federation designs where the security model relies on social trust and reputation
    
https://cseweb.ucsd.edu/~mihir/papers/isw-pops.pdf

https://www.cs.ucdavis.edu/~rogaway/papers/cc.pdf


encryption - probably better to just leave resources for the interested 
  - cyphers
  - symmetric encryption - secret key encryption
    - AES
  - Asymmetric encryption - public key cryptography
    - encrypting, decrypting, signing, validating signatures
    - RSA
    - Eliptic Curve
  - Deffie-Hellman Key exchange


attacks on encryption (not so relevant tbh)
- ciphertext only attack
- known plaintext attack
- chosen plaintext attack
- chosen ciphertext attack


[practical cryptography book](https://cryptobook.nakov.com/)

[crypto hack](https://cryptohack.org/)

## awesome resources

https://github.com/pFarb/awesome-crypto-papers#introducing-people-to-data-security-and-cryptography

https://github.com/sobolevn/awesome-cryptography

https://eprint.iacr.org/