# Week 2: Big Data and (Social) Science

## Discussion Prompts

The world is governed by immutable laws. With enough information about the initial conditions, nothing is unpredictable and every outcome is necessary. Discuss.

* Randomness is the foundation of evolution so we can't have certainty in all outcomes 
* But if you had every information about every possible permutation then is anything random? 
* Not possible to gain enough information about initial conditions.
* Claim depends on what you mean by 'nothing is unpredictable' - maybe the outcome is necessary for example, and maybe the laws are immutable, but perhaps it is inherently impossible to have sufficient information to actually predict everything (I think this has something to do with entropy)
* Nature is not deterministic, human activity systems are purposeful and will always set their own objectives depending on what goals they would like to achieve. 
* In a sense, it is a question about how to define 'enough information about the intitial condition'. Yes, given enough information maybe we could compute all outcomes, but can we indeed have enough information about initial conditions?
* Statistics is about quantifying uncertainty, and can be used to put uncertainty into concrete terms
* Not all information is measurable
* Chaos theory
* Against: indeterminacy interpretation of quantum mechanics
* For: counterargument to QM - it just "looks" random to us, just like the weather may have looked random to early humans, i.e. we don't know enough about physics to make this claim.
* For: But [Schrödinger's equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) implies that you may describe the probability distribution of a quantum system for each t if you know the initial conditions, which is in a way deterministic
* Against: Actor-network-theory (Latour) says that nothing exists outside relations
* For: Some neural signals can indicate decision-making processes before we make a certain decision. Probably in the future we will be able to identify decisions based on neural signals before the subject actually makes them.
* Against: the condition is wrong, we are still exploring the laws and they can be changed.
* For: we are still determining the laws governing the world, but everything can be distilled down to interactions of different laws within differring conditions (whether we get there is different matter).
* Against: Lots of processes are unpredictable because of a big stochastic element (weather, stock market crashs,...)
* Against: In particular, social processes are extremely complex

Probabilities are just statements of subjective ignorance. When I say there's a 50% chance it will rain tomorrow, I simply mean that for all I know, it's as likely as not that it will rain tomorrow. Discuss.

* A subjective Bayesian interpretation - "all probabilities are statements of ignorance"
* Bayesian statistics - combination of data and prior information to construct one's probablistic statement 
* A model is a representation of the world, as our underlying data and is thus subjective, but with better, more diverse data we can get approximately closer to a notion of objectivity.
* Depends on context - if you were betting on rain happening then yes, it's your degree of confidence (or subjective ignorance, same thing?). But you might also have concepts of objective probability - if the world is deterministic, the objective probability of any event will always be 1 or 0, depending on initial conditions. If quantum physics permits indeterminism than you can have objective probabilities that are between 0 and 1.
* It is hard to know the true probability distribution of population so maybe even when we do think we have some certainty (>50%), we may just be operating on another sampling distribution that is not representative of the population
* I guess it means I can say it will rain with a chance of 50% with what I know about rainfall in the UK but the person next to me can say it will rain 70% chance based on his/her assumptions and current knowledge?

Observational data is never sufficient to infer a causal relationship between two variables. Discuss.

* [Simpson's paradox](https://en.wikipedia.org/wiki/Simpson%27s_paradox)
* Sampling of data matters a lot, and without a controlled experiment setup confounding factors are almost certain to occur. The likelihood of not introducing bias through confounding correlations is very low.
* Yes, I think the basic idea is that if you can get different observational studies you can find a correlation and start to weed out different causal hypotheses to explain the relationship. 
* Finding a correlation does at least update your Bayesian prior that there was a cause
* Impossible to separate out the treatment effect of the variable of interest 
* Latent variables (e.g. fear) are not observable, but (at least in psychology) play a major role in analysing causal relationships between variables. 
* You cannot replicate the natural world in observational data. It is biased by what you observe.
* Natural experiments?
* Some statistical methods can be used (diff-in-diff) to indicate causality. Then again, even a well designed experiment never guarantees causality.
* RCTs are quite often very confounded.
* [Hawthorne effect](https://en.wikipedia.org/wiki/Hawthorne_effect)
* It's the same discussion as above, about determinism. If you can establish a true, individual, one-to-one causal inference, then you're back to the deterministic world. There is no way to talk about causality without talking about effects on the averages subject to random effects.
* Something is only true if and only if it is true in all environments. 
* Isn't all data observational?
* Not always possible to use RCTs - ethics, validity, unfeasibility etc. 
* New graphical methods and algorithms to study causation even without randomised interventions.
* It may depend on our criteria of certainty for the inference. We may be unable to "prove" a causal relationship with 100% certainty, but we may be able to infer given a "sufficient" amount of evidence
* Against: A well defined identification strategy can uncover causal relationships. It's rarely convincing, but possible.
* Even with natural experiments/quasi-experimental design, there has been inconclusive results in the literature (i.e. Mariel Boatlift, West/East Germany). Modelling and assumptions are crucial.

## Reading Questions

In a famous 2008 cover article in _WIRED_, then editor-in-chief Chris Anderson hailed the arrival of big data as "The End of Theory":

> Out with every theory of human behavior, from linguistics to sociology. Forget taxonomy, ontology, and psychology. Who knows why people do what they do? The point is they do it, and we can track and measure it with unprecedented fidelity. With enough data, the numbers speak for themselves. (Anderson, 2008)

In an article published the same year, David Freedman more or less argues the opposite:

> Informal reasoning, qualitative insights, and the creation of novel data sets that require deep substantive knowledge and a great expenditure of effort and shoe leather have pivotal roles. Many breakthroughs came from recognizing anomalies and capitalizing on accidents, which require immersion in the subject. Progress means refuting old ideas if they are wrong, developing new ideas that are better, and testing both. Qualitative insights can play a key role in all three tasks. Combining the qualitative and the quantitative -- and a healthy dose of skepticism -- may provide the most secure results. (Freedman 2008, p. 300)

Who's right? Is theory more important in some subject areas than others? Why?

* I don't even think Anderson thinks Anderson is right
* We can't "track and measure" everything
* Theory is more important when there are proxies for things we cannot fully measure. Also more important depending on implications (e.g. predicting next film/purchase recommendations vs. designing public policy)
* It's really domain specific. If we only observe behaviour but don't understand causes, can we really learn to 'nudge' into a desired behaviour, let's say? And in medicine that doesn't hold at all...Observing a phenomenon cannot necessarily guarantee a remedy, but an understanding of the mechanism can. Observing also won't explain facts like how asthma patients were shown to have higher survival rate in hospitals than other 'healthy' individuals ([Caruana et al., 2015](http://people.dbmi.columbia.edu/noemie/papers/15kdd.pdf)).
* Theory tells you where to look. The data just isn't that amazing at the moment.
* Blackbox = Danger!
* With no theory and the machine operating invisibly, the machine can often be tricked by adversarial (or accidental) actions https://bit.ly/2uiNynC
* For the numbers to 'speak for themselves' requires putting them into e.g. statistical models, which themselves are informed by theory e.g. qualitative insights.
* Big data isn't the end of theory: data comes from estimating what is happening in the real world, and not the true representation. Even in physics, engineering, etc. you have issues with measurement errors. So data can be used to support theories but we cannot claim that they are the new "truth"
* Feedback loop between data and theory: data informs what questions we ask, which --> more/better data collection, which --> refinements of theory (one cannot exist without the other)
    * Linguistics: data informs theory and vice versa (e.g. phonology)
* Against Anderson, our collection of data must at some level necessitate a theory about what it is we're "looking at" or some characteristics of it.
* There are areas, e.g. crime, that have rare/unique cases, making it impossible to implement "big data theory".
* The 'History of knowledge' has made it clear that is the combination of both, qualitative and quantitative information/theory and data, needed to create, expand and advance in our understanding of the world.



