# Week 2: Big Data and (Social) Science

For starters, you may want to check out the SEP entries on the [problem of induction](https://plato.stanford.edu/entries/induction-problem/), [interpretations of probability](https://plato.stanford.edu/entries/probability-interpret/), and the [uncertainty principle](https://plato.stanford.edu/entries/qt-uncertainty/). 

## Discussion Prompts

The world is governed by immutable laws. With enough information about the initial conditions, nothing is unpredictable and every outcome is necessary. Discuss.
* This is a powerful statement of determinism! If there is no free will, have I already failed my social data science degree?
* This premise is difficult to square with things like chaos theory and various other 'strongly' random processes. Is it meaningful if the world is 'technically' deterministic but uncomputable?
* How do we know these laws are immutable?
* True. But this information is difficult to get.
* If the world is governed by these immutable laws then the future is entirely deterministic, and every outcome neccessarely pre-destined.
* One might object that the "immutable" laws are only immutable as long as we do not find evidence to the contrary. And moreover, we would only access the notion of immutability through models that allows us to comprehend the world. 
* Quantum indeterminacy?
* Models are necessarily simplifications of the real world, therefore cannot achieve perfect predictive power.
* How much information is "enough"?
* Instead it seems more likely that there are probabilities of what can happen, but our cognition allows us to act against probabilities. Of course, we could theoretically figure out who is likely to opt out and under which conditions they will. 
* Random outcomes are still possible.
* Assumes that there are such laws to be found.
* Is it actually so clear that the laws of physics (as we have them best today) are actually deterministic in the sense necessary for the assertion? 
* This is not possible given chaos theory; also there are too many variables and interactions (power sets) that make this physically impossible given our technologies and resources.
* The question is whether the human social world is non-chaotic enough to be predicted with certainty given enough data and processing.
* Uncertainty might be one of the immutable laws of nature. If we perfectly described our world using mathematical statistics, this would not imply absence of uncertainty and hence undermine scientific determinism.
* While laws are immutable, human behavior does not always match our perceptions and predictions. 
* A general set of events may be predictable, but specifics may be difficult (margin of error).

Probabilities are just statements of subjective ignorance. When I say there's a 50% chance it will rain tomorrow, I simply mean that, for all I know, it's as likely as not that it will rain tomorrow. Discuss.
* We come in with "priors" that aren't necessarily 50/50.
* Unknown unknowns?
* We’re in a world governed by laws that tend to produce likely results or are heading toward a certain result (if objective probabilities of events exist). However, there’s an embodied context to consider that moderates and mediates what can happen. Humans have cognition that allows them to act against the "probability forces" that are leading them to a certain action. And when those happens, it has some reaction/repercussion. Free will is our ability to go against probability. So, we can subjective say/bet on what we will do.
* Only true given that you possess no information that would change this probability (in your point of view); the more information you have, the more refined this probability becomes.
* Probabilities are objective characteristics of reality and describe a population, not a sample of observations. We use statistics, Bayesian or frequentist, to approximate true probabilities.
* Depends on context and background research done on subject...if you are stating that with no understanding of meterology than yes, it is more likely as not that it will rain, but having repeated patterns over time to predict the same events in the future than no, it is more than a statement of subjective ignorance

Observational data is never sufficient to infer a causal relationship between two variables. Discuss.
* False. There are plenty of methods for establishing causality that do not rely on designed, perfectly random experiments (instrumental variables, regression discontinuity, natural experiments...). They do usually require a set of weak assumptions.
* False - but I did not fully understand Judea Pearl... (apparently Bayesian Networks were a good idea but still problematic...the backdoor has to be closed? 
* In a deterministic world, observational data are the (inevitable) result of their causes, which should theoretically serve as evidence for the causal effect even without our intervention of controlling the variables at play. However, we might not interpret these observations in the way true to their deterministic causes, which injects subjectivity into observational data. 
* With caution..association does not imply causation due to confounding factors and omitted variable bias.


## Reading Questions

In a famous 2008 cover article in _WIRED_, then editor-in-chief Chris Anderson hailed the arrival of big data as "The End of Theory":

> Out with every theory of human behavior, from linguistics to sociology. Forget taxonomy, ontology, and psychology. Who knows why people do what they do? The point is they do it, and we can track and measure it with unprecedented fidelity. With enough data, the numbers speak for themselves. (Anderson, 2008)

In an article published the same year, David Freedman more or less argues the opposite:

> Informal reasoning, qualitative insights, and the creation of novel data sets that require deep substantive knowledge and a great expenditure of effort and shoe leather have pivotal roles. Many breakthroughs came from recognizing anomalies and capitalizing on accidents, which require immersion in the subject. Progress means refuting old ideas if they are wrong, developing new ideas that are better, and testing both. Qualitative insights can play a key role in all three tasks. Combining the qualitative and the quantitative -- and a healthy dose of skepticism -- may provide the most secure results. (Freedman 2008, p. 300)

Who's right? Is theory more important in some subject areas than others? Why?

Team Anderson:
* Chris Anderson was probably trying to make a splash. But a weaker form of his argument might be right. Where we could only use theory before, now data give us insight. Maybe the title should be "The End of (Only Using) Theory".
* The aggregation of large databases on each and everyone of us allows an ML simulation to approach reality even probabilistically (and depending on the field, being almost right is as good as creating replicable scientific results).
* Similarities with idea of "revealed preferences".
* Insights from data often make the previous work of some social sciences look weak.
* There might be theories out there that we haven't had the capacity to find before, that we now can. 

Team Freedman:
* Not every research area has access to such large datasets 
* Numbers cannot speak for themselves - to be meaningful to us they must be interpreted, and to be interpreted they require the social sciences.
* Data is often uncontextualized by nature of it being an abstraction and requires other qualitative measures to understand
* Dustbowl empiricism has the problem of certain correlations or reactions happening together just by chance. Big data also has the problem that with enough data, results tend to be significant. Given this, there needs to be follow-up studies that use the usual research methods. 
* We don't want another replication crisis...
* David Freedman is right. All components in a thing must be studied to understand why it occurs. "Who knows" is a strange way of looking at the world especially for those trying to understand what is, and what is not the case of affairs. 
* The numbers do not speak for themselves but for the person who compiled them. Any translation of individual characteristics into quantitative data forces contextualisation, approximation and establishing implicit/explicit assumptions. To understand the data, there has to be a qualitative understanding of why the data came to assume the form it is in.
* Numbers and data do not make interesting theoretical insight on their own. It requires selection of relevant subsets, thought about what might have been omitted that be relevant, and often in the history of science intuition, or luck, or as Freedman says deep domain knowledge.
* Data science/analysis that is not grounded in frameworks provided by qualitative disciplines themselves can result in numbers and complex analyses with no understanding of how these results impact the specific topc in question. I would side more with Freeman.
* Theory is still important in the sense that it can help fill in the gaps that we cannot quantify. Furthermore, it can be said that the numbers only "speak" if there is some sort of comparison being done. What kind of comparison should be made is a decision that is made by human beings with biases.

Who needs "teams" anyway? 
* Understanding human behaviour from theory might take a more predictive approach, whereas analysing data generated from human behaviour might be more retrospective. The two perspectives might offer different and unique insights from each other. 
* Depends on the goal! There's a reasonable setting where lacking a theory is irrelevant to the discussion/where having one is strictly necessary.


