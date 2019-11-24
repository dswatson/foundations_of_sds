# Week 6: Algorithmic Explainability

## Discussion Prompts/Questions

All that matters is performance. If model $f_1$ outperforms model $f_2$, then who cares which is more "interpretable"?

* Stakes matter. It's probably not hugely important if a spam filter is inexplicable, but doctors and patients will likely prefer intelligible algorithms for medical applications.
* If you are thinking of applying it in human-oriented positions, it does you only marginal good to have better models if you cannot explain what they do to your (often) non-cooperative teamates or clients. 
* I'd say it depends on what "outperforms" means. If it means "is better at achieving the goals of the exercise", then sure. But more realistically, if we take outperforms to mean is "is more predictive," then I'd say it depends on context and we get back to the tradeoff between the returns to interpretability vs. the returns to performance.
* Pro: Industry cares about outcome and performance. Con: If it's not interpretable, good science may not be performed. 
* Still need ability to contest decisions. Also, outperforms based on what metric?
* Pros: Obviously improved results of $f_1$ vs. $f_2$, and hence overall applicability. Cons: $f_1$ might potentially exhibit privacy or fairness issues that cannot be identified if it's a black box.
* Perhaps for medical algorithms, where greater accuracy means more lives saved
* I would argue that it depends on the variables in the model..are they objects or data relating to individuals? I would say interpretability matters more when there are human lives at stake.
* Interpretable by/to whom(who?)? If by end user then it does not matter as much
* Interpretability is needed for accountability to the consumer on how their data is being used.

What makes an explanation (algorithmic or otherwise) successful?

* Accuracy
* Simplicity
* Credibility
* Reproducibility 
* Generalizability 
* Causal effects are clearly articulated 

Are linear models inherently intelligible?

* Yes. The linear equation describes a global property of the model that holds with equal probability for all points in the dataset. It assigns straightforward feature weights to inputs. Totally transparent.
* No, if coefficients become sufficiently numerous. People cannot plausible be expected to remember much more than six or seven numbers, let alone hundreds or thousands, especially when those numbers are not integers and are estimated with varying degrees of precision.

## A few notes on the reading

See [Rashomon](https://en.wikipedia.org/wiki/Rashomon)! Great movie. More relevantly, [Breiman (2001)](http://www2.math.uu.se/~thulin/mm/breiman.pdf) introduces the notion of a "Rashomon set", i.e. a class of models that all perform reasonably well on a given dataset. Rudin argues that in any given Rashomon set, there is always at least one intelligible model. If she is right, then there is no accuracy-interpretability tradeoff. 

For some more info on Rudin's work in this area, see her [SLIM](https://link.springer.com/article/10.1007/s10994-015-5528-6) algorithm, [CORELS](http://www.jmlr.org/papers/volume18/17-716/17-716.pdf) algorithm, and [recent paper](https://arxiv.org/abs/1908.01755) on Rashomon curves and volumes. (Warning: very technical!)




