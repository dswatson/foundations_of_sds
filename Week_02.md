# Week 2: Data Infrastructures, Citizens, and Publics

First, note that the [Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/) (SEP) has some great entries on a huge number of important debates in [epistemology](https://plato.stanford.edu/entries/epistemology/), [ethics](https://plato.stanford.edu/entries/ethics-virtue/), [AI](https://plato.stanford.edu/entries/artificial-intelligence/), [probability](https://plato.stanford.edu/entries/probability-interpret/), etc.

## What's up with this formative?

From the syllabus:

>Assessment is by a single essay not to exceed 5,000 words in length. [Formative is a 2-3,000 word version of same.] The summative essay should take the form of a critical assessment of a single topic in social data science research....The essay should critically engage with the strengths and weaknesses of the research, suggesting possible improvements or limitatio ens pertaining to theory, method and analysis when appropriate. However, in each case, you must consider all three of the course themes — (i) the epistemological or scientific validity of big data approaches, (ii) the ethical and social aspects or implications of the research, and (iii) its practical implications and limits. 

Consider ProPublica's controversial report on [Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). How might one structure a formative based on this study?

### Introduction
Something.

### Epistemological or scientific validity of big data approaches

#### Opportunities
* Larger sample sizes and more features can improve predictions (increase precision, boost power to detect effects)
* Better predictions can potentially reduce bias (see, e.g., [Kleinberg et al., 2017](https://academic.oup.com/qje/article/133/1/237/4095198))
* Running algorithm and underlying data against a multitude of additional fairness metrics (e.g., equal opportunities, equalized odds, demographic parity) as proposed by IBM's [AI Fairness 360 Toolkit](https://developer.ibm.com/technologies/artificial-intelligence/projects/ai-fairness-360/) can help users arrive at a more robust and explainable decisions.

#### Challenges
* Imbalance in sample collection across different races could lead to poor results.
* If the data is biased due to human factors (e.g., historic disadvantage), this will be reflected in the algorithm, further reinforcing this bias.
* Justifying results based on model parameters might be arduous. If they're publicly available, it is possible to critique the decision of certain parameters and how they causally affect the person's likelihood of recidivism. If they're unavailable, it becomes a black box, hence hard to justify any decisions.
* Lack of transparency on how decisions are made by the algorithm.
* There are a lot of data sets that can become proxies for race. (See [Kilbertus et al., 2017](https://arxiv.org/pdf/1706.02744.pdf), [Lakkaraju & Bastani, 2020](https://dl.acm.org/doi/10.1145/3375627.3375833)).
* Generalization since the algorithm is based on one particular jurisdiction.
* Proprietary code and data is opaque and fundamentally unscientific. 
* Questions around what protected classes are and how other factors can become proxies for them. 
* To what extent do we believe that an algorithim based on data could make a better prediction that an informed judge? (I.e., can the algorithim consider all relevant nuances of each case that would influence the likelihood of a criminal re-offending?)
* Exercise of judgment and expertise of a judge becomes a mere appliction of some quantified information.
* Should we hide sensitive/protected variables or explictly use them and their correlates as inputs?
* How do we define fairness? 
* Impossibility results show that different intuitive notions of fairness can be inconsistent. See [Kleinberg et al., 2016](https://arxiv.org/abs/1609.05807).
* Establishes a classification algorithm based on quantifiable features, which are intended to act as proxies for human behaviour - how accurate or relevant are these proxies? Do they promote some form of 'other-isation' or social stigma?
* Difficult to make judgements in precision-recall trade-offs, especially for sensitive issues (e.g., issues pertaining to national interests vs. individual interest) This is an epistemological challenge that also raises ethical/social issues of _who_ makes such judgements?
* Disruption of the iron cage/bureaucracy of the justice system (e.g., time before appeal, resources required for appeal). But perhaps creates a new, stronger cage embedded in the algorithm?


### Ethical and social aspects or implications of research

#### Opportunities
* Current systems are potentially biased; improved systems could promote greater equality.
* Potential to reform current processes, which have often been shown to discriminate on the basis of race, wealth, etc. 
* Existing systems were also already biased, so technology will help mitigate some of these biases in a more rigorous fashion (if done correctly, though...)
* Reduce judicial backlogs.

#### Challenges
* Algorithm is based on historical data, which may not adequately reflect likelihood of recidivism. Algorithm may just [automate inequality](https://www.amazon.co.uk/Automating-Inequality-Virginia-Eubanks/dp/1250074312), becoming a [weapon of math destruction](https://www.amazon.co.uk/Weapons-Math-Destruction-Increases-Inequality/dp/0553418815) or [algorithm of oppression](https://www.amazon.co.uk/Algorithms-Oppression-Search-Engines-Reinforce/dp/1479837245/ref=sr_1_1?dchild=1&keywords=algorithms+of+oppression&qid=1603838322&s=books&sr=1-1). 
* Self-fulfilling prophecies: lacking perspectives for high-rated people, consolidation of existing patterns.
* Algorithms used are generally products of for-profit companies. What are their incentives? When and why might they be ethical?
* Is it ethical to outsource important human decisions to machines?
* Do different ethical perspectives (e.g., [deontology](https://plato.stanford.edu/entries/ethics-deontological/) or [consequentialism](https://plato.stanford.edu/entries/consequentialism/)) render different judgments here?


### Practical implications and limits

#### Opportunities
* A well-functioning algorithm could help busy courts by increassing efficiency and cutting costs. 
* Pre-trial algorithms were introduced to combat systemic racism in the US criminal justice system. With vulnerabilities exposed, this raises the need for a regulatory framework for their implementation (if at all implemented). This may include centralization of the algorithms used, introduction of methods for community participation and transparency, and weighting for a human machine aided approach. 
* Perhaps the bias demonstrated by the algorithm can highlight and quantify systemic issues in the US justice system.

#### Challenges
* There is no unanimously accepted definition of "fairness", and different notions are mutually inconsistent. 
* What level of granularity do you seek for bias? I.e., ProPublica looked at black vs. white. But at what level of granularity/intersectionality do you stop (e.g., age, race, gender, income, etc.). See [Kearns et al., 2019](https://arxiv.org/abs/1905.10607). It is all very subjective and different parties involved have different definitions of fairness and what it will entail.
* when attempting to reverse-engineer the recidivism model, how do you gather enough data on the alleged criminals to get a representative sample? Or in order to determine the external validity of the approach - how does one get access to that data in other countries? Does it require personal follow-up? See [Rudin et al., 2018](https://arxiv.org/abs/1811.00731).
* How do you regulate a black box algorithm? Do we need regulations / policies to increase transparency? What would they look like? Results of an algorithm are difficult to explain to those who are affected by it.
* How do judges use the scores? 
* Does this approach simply perpetuate a system that does not serve us? 
* Understanding the judicial trade-off between human and machine decision-making (how much should each be weighed?)
* How can people appeal algorithmic decisions? 
* Who is liable for wrongdoing?

### Conclusion
Therefore, something.



## Reading Questions

In this week’s readings, several articles -- including Knight (2020 and Kosta (2019) -- discuss the use of social credit systems in China. Other articles -- notably Khera (2019) and Aurora (2019) -- explain and critique the role ‘Aadhaar’ plays in the process of redefining citizenship in India. What similarities and differences do you see between China’s social credit systems and the implementation of Aadhaar in India?  

### Similarities
* Both systems make the assumption that an individual of a society can and should be "codified" to a certain degree in order to foster human coordinatiion (see Weberian [rationalization](https://plato.stanford.edu/entries/weber/#RatTheUni)).
* Some portion of the population view these AI systems as beneficial. In China, some people think the social credit system impoves the declining morality issue. In India, it helps to get everyone online, even those in rural communities. Aadhaar can almost be seen as an equalizer of sorts.
* Both create a barrier to entry in civil life for marginalized groups that cannot easily access the resources needed to participate in the system.
* Both have the underlying potential (or in the case of the social credit system are being used) to maintain current political control and stability. 
* Both China’s Social Credit System and India’s Aadhaar have the goal of shaping social behaviour through (i) identification and (ii) surveillance.
* Both redefine the essence of 'privacy' in both countries.
* Both governments dealing with very large populations - monitoring becomes difficult if decentralized.
* Both are rapidly developing nations with weak identification infrastures, as they were developed ad-hoc in comparison to mature developed nations.
* Access to social welfare stipulated by these systems.


### Differences 
* It seems as though the social credit system has more of an emphasis on quantifying things we usually view qualitatively, like social behavior, while Aadhaar is more focused on creating unique identifiers for people. The key difference is that the Aadhaar data doesn't contain as much information about how you act, just what you have signed up for.
* Chinese system seems a lot more involved in fine-grained ways in your behavior... they seem to have a lot more data and are running a lot of ML/AI things (like facial recognition) and seem to be a lot more involved in your life.
* In China, the social credit system is part of a bigger and more centralized plan of AI development.
* The Chinese approach is targetting social behaviour change, and although the Aadhaar system _could_ be used for this, it was not the explicit driving force behind its conceptualization and implementation.
* Aadhaar claims to be identity first -- i.e., registration is separate from settling other statuses (questionably true). However, SCS puts the settlement of statuses as a high priority of the implementation of the system. This entangles political causes with a system that should provide access to basic rights. 
* Practically, the Western narrative of Social Credit System is much more dramatic/well-known/used as an example of how AI is dangerous, as well as the ongoing US-China AI Arms Race narrative.
* Autocratic vs. Democratic government system. People can't use their vote to express discontent with Chinese digital governance. This different system and differences in underlying ethics systems/ideologies introduces differences in the accepted government-citizen relationship.
* Different demographics? The Chinese population is more ethnically homogenous (97% Han Chinese), so system differentially affects the other ethnicities.
* The main intent of China's social credit system is risk assessment, i.e. inevitably invoking some form of marginalisation or 'redlining'; whereas in contrast, the implementation of Aadhaar (nominally) seeks to incorporate under-represented/marginalized communities into decision-making processes (although, as argued by the article, might have secondary outcomes).


(We didn't get to discuss these last two questions, but I'll keep them here in case you want to reflect on them later.)

Roberts et al. (2020), and several other articles in this week’s readings, link cultural and geographic factors to how countries approach the opportunities and challenges posed by AI. Do you think it is meaningful to speak of a ‘Chinese’ or ‘Indian’ approach to AI? Why or why not?

The use of social credit systems is not unique to China. Nor need the use of social credit systems be linked to government programs (think of corporate profiling). What underlying forces or mechanisms do you think drive the general tendency towards increased digital surveillance? How, if at all, do these forces relate to concepts like trust and individuality?  

