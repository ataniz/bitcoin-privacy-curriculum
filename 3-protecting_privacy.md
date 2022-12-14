Probably won't include too much details about cryptography primitives but perhaps still could leave some links with practical examples and easy explainers

# Protecting Privacy

[moral landscape of cryptographic work](https://www.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf)
    [presentation](https://www.youtube.com/watch?v=1ReIILmcLpk)


[what happened to the crypto dream pt1](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part1.pdf)
[what happened to the crypto dream pt2](https://www.cs.princeton.edu/~arvindn/publications/crypto-dream-part2.pdf)

crypto for infosec and crypto for privacy is a sound seperation imo



>Practice-Oriented Provable Security and the Social Construction of Cryptography
    this idea could be connected with various federation designs where the security model relies on social trust and reputation
    https://cseweb.ucsd.edu/~mihir/papers/isw-pops.pdf
    https://www.cs.ucdavis.edu/~rogaway/papers/cc.pdf


>talk to hennig and some other CTF people for inputs


Cryptography in InfoSec direction
    encryption
        cyphers
        symetric encryption - secret key encryption
            AES
        Asymetric encryption - public key cryptography
            RSA
            Eliptic Curve
                encrypting, decrypting, signing, validating signitures
            Deffie-Hellman Key exchange

    stenography

    <!-- attacks on encryption
        ciphertext only attack
        known plaintext attack
        chosen plaintext attack
        chosen ciphertext attack -->

Cryptography and tech in privacy
    [OG ZK paper](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Zero%20Knowledge/Proofs_That_Yield_Nothing_But_Their_Validity_or_All_Languages_in_NP_Have_Zero-Knowledge_Proof_Systems.pdf)
    [zero knowledge proofs](https://en.wikipedia.org/wiki/Zero-knowledge_proof)
    peterson commitments
    moon math
    various mixing methods
    tor 
    I2P
    VPNs
    (e.g. [[https://www.wireguard.com/][wireguard]]/[[https://tailscale.com][tailscale]]/[[https://github.com/juanfont/headscale][headscale]], [[https://www.onioncat.org/][onioncat]], [[https://www.gnunet.org/en/][GNUnet]],
    [[https://yggdrasil-network.github.io/][Yggdrasil]], [[https://zerotier.com/][ZeroTier]], etc..[fn::note that headscale is an unofficial self hosted
    version of tailscale and not all ZeroTier clients are fully open source])


![](https://upload.wikimedia.org/wikipedia/en/f/f8/Internet_dog.jpg)

## might be relevant

self-hosting? 

good security practices

good privacy practices

social engineering







## relevant memes: 

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



https://medium.com/@brannondorsey/wi-fi-is-broken-3f6054210fa5