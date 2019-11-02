# Week 3: Algorithmic Fairness and Bias

## Discussion Questions

Proponents of a flat tax argue that it is maximally fair, since everyone pays the same rate. Are they right?

* There is more marginal utility to their money if it were redistributed, however, it makes for difficult moral defense of a differentiated tax rate as you may end up (see examples in France for instance) with parts of the population not paying anything and a small minority "paying" for the majority.
* Yes, if fair means that everyone is contributing equally. If everyone has the exact same means, this would be totally fair. In reality though, not everyone has the same situatons and means. Therefore, the relative tax impact is different for each person. This might then be considered unfair. Therefore, definitions are key.
* Yes, since everyone is contributing the same proportion of their income.
* No, because people have an decreasing marginal utility (the more money, the lower the additional utility), so higher taxation for richer people is fair because they lose less utility.
* No, since the absolute value of the tax liability supercedes the relative value in terms of contribution to society.
* No -- fairness in terms of taxes should take relative sacrifice into account.
* No, their underlying assumption is that income is an accurate reflection of effort. Is it fair that certain people need to overcome additional hurdles to earn the same amount?
* Interpretation of Progressive Income Tax as hypothetical insurance rates on not being able to earn one's own living (underemployment insurance).
* The same rate doesn't translate to the same utility change with diminishing marginal returns to income.
* This view makes the assumption that everyone has a fair starting point of financial ability.
* No, a single unit of money does not mean the same to someone who doesn't have a high salary vs. someone who does.

Are lotteries fair?

* Yes to the extent that each entrant has an equal chance of winning (if you play against someone with loaded dice, it's not fair)
* Yes, if P(Win|Participant) = P(Win).
* Yes, because people go in knowing and agreeing to the rules of the game.
* No, disproportionately negatively impact on poor/gambling addicts/people who don't understand statistics and create unfair outcomes that prey on these groups.
* Not a mandatory system, people know what they are getting into when they decide to join the "game." Theoretically everyone has the same chance of winning. However, richer people could buy more tickets and increase their chance. 
* They are, because winner is chosen at random (provided system is perfectly random), and everyone has equal right/chance to buy a lottery ticket.
* No, the cost of playing is always higher than the expected outcome. In other words, there is not a fair playing field between the "house" and the "players" even if it is fair between "players".
* Effectively a tax on lower educated (and therefore regressive).
* Not unless there are limits on how many tickets you could buy. 
* Yes? Everyone is subject to the same forces of chance, and have the ability to make a decision to subject themselves to these chances. Unlike taxes where there are systemic factors/biases that makes each person's experience different, and they don't have a say about these systemic factors they experience.
* Access seems to be the same for all people; however, people with more monetary means could pay for more tickets and thus increase their chances.
* Lotteries are an exploitation of the weaknesses of human cognition and inability to properly evaluate short-long term gains and losses.

Here are three prominent formal definitions of algorithmic fairness:
* Demographic parity: $\widehat{Y} \independent A$
* Error parity: $\widehat{Y} \independent A | Y$
* Predictive parity: $Y \independent A | \widehat{Y}$

Where:
$Y$ = ground truth
$\widehat{Y}$ = predicted label
$A$ = protected attribute
$X \perp Y$ = $X$ is independent of $Y$

NOTE: These are all equivalent if and only if either:
(1) $Y \perp A$; or
(2) $Y = \widehat{Y}$

What's wrong with demographic parity?
* May not account for how the demographic groups are actually different in certain areas, given the social context. 
* What about correlates to protected attributes?

What's wrong with error parity?
* Making the same rate of mistakes for both groups does not neccessarely mean that they are "fair": the equal error can be due to differential base rates.
* Incompatible with predictive parity.

What's wrong with predictive parity?
* Incompatible with error parity.

## Formative Assignment

Consider ProPublica's controversial report on [Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). How might one structure a formative based on this study?

### Introduction
Something.

### Epistemological or scientific validity of big data approaches

#### Opportunities
* Larger datasets lead to more accurate and precise predictions.
* A well-designed classifier could be more objective than humans.
* Algorithmic decisions are easier to probe than judicial decisions.

#### Challenges
* Are we sure that the dataset is representative?
* IP laws protect the model from external scrutiny.

### Ethical and social aspects or implications of research

#### Opportunities
* Could lead to more efficient and just outcomes.
* Opens up public and/or policy debate on what type of fairness should be pursued by these institutions.
* Greater awareness regarding the impact algorithms have across fields and how they can impact people's lives.

#### Challenges
* Algorithms could accelerate and automate injustices.
* Fairness may be irreducibly subjective and/or context-dependent.

### Practical implications and limits

#### Opportunities
* Could ease the burden on the criminal justice system.
* May provide tools to test for discrimination with or without COMPAS.

#### Challenges
* Unclear how to "fix" the algorithm. Are technical solutions possible?
* There should be some system in place to challenge algorithmic risk assessments.
* Who (should) decide(s) which fairness definitions we ultimately go with?

### Conclusion
Therefore, something.



