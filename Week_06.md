# Week 6: Governance and Professionalism in Social Data Science

## Reading Questions

### Beyond Principles

[Mittelstadt (2019)](https://www.nature.com/articles/s42256-019-0114-4) notes that much recent work on AI ethics draws on presumed analogies to medical ethics. However, he points out four key differences between the two disciplines: 

> Compared to medicine, AI development lacks (1) common aims and fiduciary duties, (2) professional history and norms, (3) proven methods to translate principles into practice, and (4) robust legal and professional accountability mechanisms.

Which of these is the most important for AI governance and why? Which is least important? Do you agree that a mature AI ethics must meet all four criteria? What would meeting any one of them look like?  

* Fiduciary duties
    * Brent's comparison to medicine and highlighting the lack of common goal, such as health, is certainly valid. However, a commonality between AI governance and medicine is the potential to do harm through malpractice. Whenever there's a potential for harm, I argue, there is a need for accountability and thus practioners have a fiduciary duty to behave ethically. Further, recipients of medical services or AI-powered services are not themselves versed in the practice and places an inherent trust into the practioners. Fiduciary stems from the meaning of trust (if I remember correctly), so there is an imperative for all AI practioners to uphold their fudiciary duties.
    * Quite different than medicine, AI has a variety of applications (i.e. from corporate to behavioural applications) therefore the common aim would just be interpreting inputs and outputs in the most accurate and reliable way. Therefore, the lack of common aims between different uses of AI limits the fiduciary duties a data scientist should have as not everyone would have the same dataset or impact to individuals. 
    * I think that this could be a dealbreaker to establishing principles for AI governance. In the absence of a set of common aims and fiduciary duties that AI researchers should aim towards, AI governance will probably end up being more of a 'toothless tiger' in the sense that its principles will probably be very general. Examples of 'faux pas'/cardinal sins will depend on which field AI is being applied to. 
    * Fiduciary duties to whom?
  - The absence of strong regulation leads to the fact that users can't trust developers. That's why I really do think that this is the most important thing that we have to try to copy from medicine. Probably, it doesn't have to be as strict as in medicine. However, some basic rules must be developed.
  - The incentive structure is all about money without this!

* Professional history and norms
    * As AI governance develops, it will be important to create a structure for sharing knowledge and updating best practices. Having a references point in professional history as well as a repository for that history (maybe through professional associations like the AMA) will be useful. In medicine the best practices in certain areas are changing (e.g., prescription practices), norms and professional history are a part of that. 
    * I find history and norms to be quite important as disciplines do not arise in a vacuum and take time to settle. I would compare this to ethics committees in research - we definitely did not get it right at the beginning (think of unethical psychology experiments) and then with time some norms settled in. Nonetheless, I believe this require some accountability mechanisms in terms of legal and professional features.
    * I disagreed with his characterization that diversity within the AI field is a barrier to the establishment of norms. He cites the homogeneity of the medical field as a condition that allowed norms to be established, but didn't that homogeneity also lead to the systematic exclusion of groups of people? If the cultivation of norms relies on a homogenous group to decide them, it seems like they'll be unlikely to generalize to the groups that would be adversely affected. Institutions>homogeneity when it comes to norm setting
    * I believe that professional history is the most important and is being built now. For example, could the COMPAS case in AI not serve as a parallel to the Nuremberg trials in medicine, where specific cases create the basis for what is considered a norm?  Further, fiduciary duties seem built upon the norms that come through history (i.e. the relationship between players in a society are built through "trial and error").  So by building this history, fiduciary duties are set, which leads to the establishment of roles of accountability bodies and examples in effective translation of principles to practice.
  - Best practices evolve over time. We might need to disaggregate the concept of professional history and scope it  in a way that it shows relevance for particular use cases. A doctor gets credibility if a person gets healed, the doctor gets credibilty but what is an unequivocal definition of success in data anayltics and hence vouches for the data scientists experience?
  - Honestly, not convinced that this one is nearly as important as the other ones. Norms are a product of the methods of an industry, and if we don't feel great about the current standards in algorithmic work, perhaps we don't want those codified as norms.

* Translational methods
    * It seems to me that the lack of proven methods to put principles into practice, as well as the lack of legal accountability mechanisms are interconnected -- difficult for professional / regulatory bodies to decide on a set of standards if there are imbalances in domain knowledge 
    * Difficulty with cross-country AI application - medical ethics usually apply to within a country's borders - but how to we design AI which is deployed across borders to agree with multiple different AI ethics frameworks which are inherently related to cultural interpretations of the risk and reward from AI. 
* Accountability mechanisms
    * I think the medical analogy breaks down if we think about tools vs the who wields those tools. For example, if a doctor performs an unethical or dangerous operation, the designer of the scapel or the scapel itself are not held accountable, the doctor is the final gatekeeper of information they receive and that actions they commit on that information. But in AI, accountability maybe should be shared between the designer, the operator and perhaps even the AI itself if decisions are being made autonomously or from unsupervised learning. Adequately balancing these responsibilities and accountability mechanisms seems like a tricky but important problem for AI ethics. 
    * I feel that robust legal and professional accountability mechanisms are the most important and this is premised on my assumption that it is impracticable to delineate a common objective in AI development. For instance, AI development in the public sector appears more like a 'public good' whereas AI development in the private sector focuses more on profit-generating mechanisms where 'public interests need not be given primacy' (Mittelstadt, 2019). Thus, I believe that the presence and enforcement of such mechanisms is a (partial) solution to this issue - in a sense that it aligns, to some degree, the objectives of actors (i.e. organisations) within this diverse field. But I caveat that ideal =/= easy to achieve. 
  - The absence of translational methods hinders intersectional work, because one party (e.g. ethicists) cannot properly communicate/follow-up on work done by the other party (e.g. engineers). Can lead to misunderstandings. Meeting such challenges requires building up interdisciplinary skills. 
  - Most important and most difficult. The first barrier is the difficulty of arriving at a consensus on what these principles even should be (who gets to decide on these principles?). The second barrier is then creating policies or legal frameworks to enforce these principles, which may pose different challenges for different jurisdictions (competing priorities — how do we manage these differences across borders?).
    * A lot of what is dangerous about AI comes from two things: 1. the existential risk of runaway AI that leads to our destruction, in which case I'm not sure that accountability really matters (because this is the sort of thing that will probably only happen once, and once it does, game is over, so the cat's out of the bag, so to speak) and 2. its deployment in the public realm to decide things that substantially impact humans' lives (criminal justice reform). In the case of the latter, it's not so much the individual AI designer that we might want to hold accountable but rather the people/systems who decided which algorithms to use and whether to use them at all (take bail algorithms as an example). Either way, not sure that individual accountability as it works in the medical and legal profession is very useful here. But from a broader perspective -- this might be our best bet for AI ethics

* Accountability mechanisms
    - Accountability mechanisms can potentially consolidate common aims, however you cannot enforce the common aims, as these have to develop over time.
    - Accountability mechanisms together with professional norms (which will take time to develop) seem to constitute the most reliable basis for ethical AI in tadays world.  

### Auditing Algorithms

In their seminal article "Auditing Algorithms", [Sandvig et al. (2014)](http://www-personal.umich.edu/~csandvig/research/Auditing%20Algorithms%20--%20Sandvig%20--%20ICA%202014%20Data%20and%20Discrimination%20Preconference.pdf) propose that ethics-based auditing is a promising mechanism to ensure that AI based systems are designed and deployed in safe, fair, and transparent ways. Following this impulse, policymakers, researchers, and tech companies alike have developed a plurality of tools and frameworks to audit AI in practice.  

a) There are different types of audits, for example: (i) functionality audits, (ii) code audits, and (iii) impact audits. Compare these methodologies: which approach do you think best addresses the specific ethical and societal challenges posed by AI?

* Functionality audits
  - Functionality audits are crucial, as it not only asks what the algorithm does, but also why it should (or should not) exist. While impact audits are focused purely on outcome/output and code audits are focused on method, **functionality examines purpose, which relates to ownership of algorithm, power dynamics, and goals**.
  - might be useful especially if there is an analogue alternative to compare against. Simply looking at code would not give you fruitful reference base to assess whether data-/ML-supported functionalities introduce anomalies to the status quo
  - Functionality audits are a necessary complement to impact audits as they consider not only outputs, but also inputs and design. This can can help illucidate drivers of impact and the broader sociotechnical context, or as aptly phrased above power dynamics, that influence the system. 
  - Most helpful, because it combines consequentialist and deontological arguments. Outcomes can be justified via some deontological argument if the outcome is temporary and has some higher goal in mind. E.g., discriminating against white people in risk assessment within courts in order to achieve some unbiased future dataset to train “fair” algorithms (fair in both senses, the classification given the input and the output distribution). 
    * I would expect this type of audit to have better prospects of in a meaningful way speak to the intended reader. It is the only one that understands the audited in a broader social setting and therefore I would expect it to more directly connect with what the general public is concerned with. In the end, we are in some domains okay with biasises, so biased code is not the generall issue; we also sometimes think that other conciderations overrule potential effects
    * If by functionality audit we consider the desired optimal bias-free outcome as a functionality then perhaps this may best serve the ethical and societal challenges when used alongside code audits. Sandvig pointed out code alone may not reveal the full mechanism of an algorithm and sometimes may further confuse auditors (as in the Reddit example), but if it's combined with the intended functionality it may provide a clearer image. By ensuring an algorithm's functionalities are as intended and bias-free and auditors have access to its underlying code, it may be a powerful auditing method.
    * Based on the model just shown, functionality audits appear to be the most holistic and achievable method of addressing the ethical and societal challenges posed by AI. For one, it is an 'intention-based' audit which evaluates how an algorithm fits in with the broad sociotechnical system - not just restricted by the computational system (i.e. code audits, which have their own practical limitations), but rather how the algorithm blends in with cultural norms that are ultimately context-dependent; whereas 'outcome-based' audits (i.e. impact audits) are difficult in practice.
    * This would be a good way to audit AI in accordance with differences in cultural aspects of how the society view what is a 'right' decision. As social algorithms mimic decisions made by people who may be subject to cultural constraints and norms, AI should be too to contextualize its decisions. 

* Code audits
  - Seems feasible only for really simple models :)
  - Code audit is the most complicated in my opinion because it is super hard to analyze the code to understand if it can cause different bias. As it was said in the article, you won't really find a code line like "if this nationality then do this".
  - **Least informative if done stand alone as it has a high tehcnical barrier of entry (i.e. low interpretability**)and does not capture the outcomes of the system itself nor the context in which it is deployed. 
  - Not the most useful for non-coders, since this type of auditing requires people to be familiar with coding. Many algorithms are developed by large teams of software engineers, so even individual software engineers may not be fully familiar with the code.
  - I think we're giving too much credit to software developers - the code could also be very simple - and that's worth knowing e.g. what if recidivism algo was just linear regression?
    * Code audit analyzes the code in a context independent of its societal context, may not be able to capture the interplay between the algorithm and its societal context, and the core reason for an audit is to identify discrimination which exists on the societal level.  While code may seem benign from the surface, it's not always easy to capture how it will behave when it is run or given new input simply by looking at the syntax.
    * Useful in some instances but ignore input data as a source of potential bias (two programs that determine the price of a product on amazon  would look extremely similar, but depending on the training data it could be problematic)
    * Auditing code while has a place in the auditing process, might be the least helpful on it own. Auditing code will require traversing a complicated sets of packages possibly with different licensing requirements and goals. In addition, the clarity of code will depend on the norms of the development team.

* Impact audits
    * 'Right but for the wrong reasons' - I think impact + code have to come together as a pair in order to adequately understand how the model is reaching the conclusions. Impact = Outputs, but outputs are always based on some inputs. It might also be that to reach the right decision (e.g. correct classification of loan default), 1000s of input features are needed - large monetary and privacy cost to collect this data - therefore, the inputs and outputs to the algorithm are inherently tied to its impact and practical implementation. 
    * As the final step of the audit - impact should assimilate the findings of code and functional audits - I'm thinking of this kind of like an academic paper 
        * Functional = Background/Context
        * Code = Methods
        * Impact = Discussion/Conclusion
        * Each section builds on the previous and is not so useful as standalone comments.
    * I would argue that ultimately these are the most important audits to perform when you want to capture societal impacts, but at the same time, I recognize that they might be the most difficult to perform. It is very difficult to estimate a priori how something is going to land in society + interact with existing institutions. It is also difficult to hold someone accountable for unintended consequences of their actions.
    * Do impacts matter more for certain types of ethical concerns than others? We can draw a parallel to US discrimination law, in which employment policies can be illegal even if facially neutral if it has a negative impact on employment of people of a particular race -- but I think (not an expert on discrimination law) not every question of potential discrimination is treated this way. 
  - Might be the easiest to troubleshoot whether there is an actual issue from which could then back-probagate to functionality and code issues. The other way around, critique on code and functionality might not formulate strong enough case to argue for change as the consequences (aka impact) ar not an explicit part of the discussion
  - **I think that impact audit is the best way to audit. Of course, you need to gather as much information about different cases as possible**. If you miss a case it can lead to the failure of the audit. However, there are a lot of opportunities get as much information as needed. 
  - This seems particularly useful for algorithms being used in the government/public space. We can see if there is disproportionate impact on certain demographic characteristics and compare that to other standards in the same system. 
  - This would be important to have but only if used in conjunction with another type of Audit as this only reveals the problem after the fact, i.e. after any 'damage' has been done by the AI. For this reason I think it would only be best used after another type of audit to find what may have been missed by the first audit

b) What are some of the conceptual limitations and practical constraints associated with ethics-based auditing of AI?

* Conceptual limitations
    * AI-ethics itself is hardly defined properly as of right now. So auditing based on a debated set of principles will be quite difficult.
    * Difficult to outline a clear 'rubric' for ethics-based auditing, especially since ethical considerations often conflict with one another 
    * Can authors of algorihtms be held accountable for the unintended practical consequences of their work? This implies that they should then also have - at all times - control of who/where/when their algorithm is used.
    * Issues of deception
  - Whose ethics?  **People have different ethics**!
  - Possible that a functionality audit could result in some questionable functionality, but a subsequent impact audit could be fine. In that case, should we keep the algorithm? Rewrite it? What if fixing the functionality results in discriminatory impact?
  - **Audits may provide an inaccurate representation of reality** (e.g., if we only did code audit but no impact audit) and a false sense of security
  - Longitudinal assessments (at what point /at which scale start things to go wrong so that an audit might actually generate strong signals)
  - Latency between model output and real life impact. 
  - What about decision making more generally - should we be holding human decision makers to the same/higher account?
  - What we determine to be ethical and safe now might not be in a few months or years, as tech continues to develop at an accelerating pace.
    
    
* Practical constraints
    * Penalties not sufficiently prohibitive ('cost of business')
    * Also run into issues here with stricter enforcement -> favouring large corporations (not ideal!) who can afford teams of internal auditors and/or big fines
    * Companies are not gonna be too happy to give their code out, for many reasons. A lot of the outputs-based auditing models also depend on company cooperation, or at the very least, auditors not getting sued and/or sent to jail for violating businesses' terms of service.
    * Companies don't want to sign up to an audit process that might expose bias - 'blissful ignorance' is better than uncovering bias - audits are not incentive compatible with company's profit or public-opinion maximisers - so unless there is considerable pressure from competitors, from customers or from governments - companies are not going to voluntarily do audits, let alone pay large sums of money (btw IBM charges £13,000 for auditing one model)
    * What happens if an audit finds really bad stuff? Does the company have a period of time ' a grace window' to rectify the issue or do they get punished straight out? E.g. what if we find out they are explicitly discriminating by gender or race in violation of EU anti-discrimination laws. 
    * In a code audit, "bad" code isn't easy to identify. Cue the line in the article about 'if not Caucasian -> illegal discrimination'
    * Measuring outcomes before they occur.
    * Adverserial algorithms.
  - If you conduct these in an obvious manner, results you get out of it might be biased. On the other hand, if I conduct these in a more subtle manner, it might be questionable practice from an ethics standpoint as consent is not overtly obtained 
  - For impact audit we need to have as much information as possible for all of the cases, for code audit we can't analyze code really good just by reading it if a model is too complex, for functionality audit I think that it's kind of a shallow type of audit.
  - The question of **who has the mandate/access to conduct audits** is a sgnificant constraint on their effectiveness. Marginalized populations that are more likely to bear the burden of biased systems are also the least empowered to hold such systems accountable. If audits are not inclusive they may instill a false notion of trust and fairness. 
  - Code audits obviously need people who understand code. Impact/Functionality audits also require experts in the field that the algorithm is being used in.
  - **Who pays for it?** 
  - Some ethical principles do only weakly translate into practical implications for algorithmic models. Hence it can be hard for engineers to implement the ethical auditing results. Essentially, it is two very different skills involved (coding and ethics) which have little overlap, thus making it hard to work together, i.e., ethical auditers cannot properly voice their recommendations in the language of engineers and vice versa.
  - How is it enforced? What kind of regulations may influence stakeholders to introduce changes into a code which was indicated to violate some ethical standards? 
