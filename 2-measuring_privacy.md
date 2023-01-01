```
This section aims to introduce quantifiable metrics and methods for evaluating/modeling privacy. These metrics and methods will be later applied to bitcoin context. Section also consideres the neccesity of usability for privacy technologies and argues that it is not a single player game. 

```

# Measuring Privacy

![](https://imgs.xkcd.com/comics/security.png)

| source                                                                                                                  | status |
| ----------------------------------------------------------------------------------------------------------------------- | ------ |
| [threat modeling](https://shellsharks.com/threat-modeling)                                                              |        |
| [Protecting Privacy when Disclosing Information](https://dataprivacylab.org/dataprivacy/projects/kanonymity/paper3.pdf) |        |
| [Towards measuring anonymity](https://www.esat.kuleuven.be/cosic/publications/article-89.pdf)                           |        |
| [Anonymity Loves Company](https://www.freehaven.net/anonbib/cache/oreilly-usability.pdf)                                |        |
| [Boltzman Script](https://medium.com/@laurentmt/introducing-boltzmann-85930984a159)                                     |        |



## keywords

        disclosure, k anonymity, quasi identifier, inference, entophy, threath models

## discussion questions
---

- consider the effectiveness of deanonymization attacks (as demonstrated in k-anonymity paper) and availability of external data (whether from data leaks, sales or social media) how does one make the case for the publication of information such as medical records, housing, usage data etc. ? (also consider the value it provides, on can consider methods of anonymizing data as well as necessity for open consent for the release)

- What inferences can an outside observer make about an individual by looking at their economic activities?
    
- is k-anonimity model applicable to bitcoin transactions?

- what information can an entropic model infer looking at a bitcoin transaction and its inputs/outputs?

- What information does LaurenMT's Boltzmann script provide about bitcoin transactions and their inputs/outputs? 

- What is the use for a script like Boltzmann? How should the entropy score be evaluated? Can a metric looking only at blockchain could ever provide a full picture about outside reality? 

- Why would bitcoin users care about privacy? Come up with threat models for different bitcoin users (user spending bitcoin, a shop accepting bitcoin payments, a person using bitcoin for saving etc.)












## relevant material 

>"what gets measured gets improved"

>"all models are wrong but some might be useful"

[k-ANONYMITY: A MODEL FOR PROTECTING PRIVACY](https://web.archive.org/web/20210720143809/https://www.win.tue.nl/~jhartog/CourseVerif/Papers/10.1.1.90.4099.pdf)
    
[Simple Demographics Often Identify People Uniquely](https://dataprivacylab.org/projects/identifiability/paper1.pdf)

[Towards and Information Theoretic Metric for Anonymity](http://www0.cs.ucl.ac.uk/staff/G.Danezis/papers/set.pdf)

https://www.eff.org/deeplinks/2010/05/every-browser-unique-results-fom-panopticlick

https://coveryourtracks.eff.org/

[threat modeling manifesto](https://www.threatmodelingmanifesto.org/) everyone is into writing manifestos these days ;-)
