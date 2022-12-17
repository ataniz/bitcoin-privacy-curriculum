```
This section aims to introduce quantifiable metrics and methods for evaluating privacy. These metrics and methods will be later applied to bitcoin context. Section also consideres the neccesity of usability for privacy technologies and argues that it is not a single player game. 

TODO: add a resource about basic intro to information security
```

# Measuring Privacy

[threat model](https://en.wikipedia.org/wiki/Threat_model)

![](https://imgs.xkcd.com/comics/security.png)

[k-ANONYMITY: A MODEL FOR PROTECTING PRIVACY](https://web.archive.org/web/20210720143809/https://www.win.tue.nl/~jhartog/CourseVerif/Papers/10.1.1.90.4099.pdf)
    (optional) [Simple Demographics Often Identify People Uniquely](https://dataprivacylab.org/projects/identifiability/paper1.pdf)

[Towards and Information Theoretic Metric for Anonymity](http://www0.cs.ucl.ac.uk/staff/G.Danezis/papers/set.pdf)

[Towards measuring anonymity](https://www.esat.kuleuven.be/cosic/publications/article-89.pdf)

[Anonymity Loves Company](https://www.freehaven.net/anonbib/cache/oreilly-usability.pdf)

---

## discussion questions


- 'Simple Demographics Often Identify People Uniquely' demonstrates the strength of quasi identifiers at deanonymizing individuals. Considering the effectiveness of identifiers and the regularity of data leaks that make such information public, how does one make the case for the (anonymized?) publication of information such as medical records, housing, academic records etc. ? (also consider the value it provides, on can consider methods of anonymizing data as well as necessity for open consent for the release)

<!-- - Threat Modeling -->
  <!-- - what structural vulnerabilities exist in bitcoin network? -->
  <!-- - what are some of the adversary models that generally apply for bitcoin users? -->
  <!-- - Provide examples of different real life scenarios (like the ones described in bitcoin/privacy) for different attacker definitions described in the >paper< -->
- Describe a threat models that apply to a bitcoin user buying a coffee using L1?
TODO: Create similar examples, using bitcoin privacy wiki examples


- What *inferences* can an outside observer make looking at individuals economic activities?


    disclosure
    k anonymity
    quasi identifier
    
- what are the shortcomings of *anonymity set* model for measuring anonymity? (draw attention to the equal handling of different messages in the set and lack of inclusion of any additional information, or cost of gathering such information)

- Does 'feedback mixing' provide better anonymity for users?

- what is *anonymity probability distribution*, and how does it enrich *anonymity set* based measurements?

- what is the entropy of a transaction?
















Definition of Attacker

These papers also served to give concise definitions of an attacker:

Internal/External
    an internal attacker controls nodes in the network, whereas an external can only compromise communication channels between nodes.
Passive/Active
    an active attacker can add, remove, and modify any messages, whereas a passive attacker can only listen to the messages.
Local/Global
    a local attacker has access to only part of the network, whereas a global can access the entire network.



