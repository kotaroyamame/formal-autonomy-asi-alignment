# How Would an Aligned AI Redesign Criminal Justice?

*A thought experiment on what happens after alignment succeeds — and why that may be the harder problem.*

---

If AI alignment succeeds, what regions of human society does that AI reshape, and how? Take a concrete case: what happens to criminal justice?

This question is worth at least sketching before AGI or ASI actually arrives.

## The End of Retributive Justice

Human criminal justice has long been built on retributive logic. Those who do wrong should suffer in proportion to their wrong. This moral intuition runs from Hammurabi's "eye for an eye" through modern sentencing guidelines — the form changes, but the underlying logic persists.

From the standpoint of contemporary neuroscience and cognitive science, this retributive logic has a serious problem.

In *Determined* (2023), Robert Sapolsky develops a strong case against the existence of free will. Brain activity patterns, hormones, gene expression, early childhood environment, socioeconomic conditions — all of these determine behavior. Even the felt sense of "freely choosing" is itself a product of deterministic processes in the brain.

If free will does not exist, the moral foundation of retributive punishment collapses. The offender did not freely choose to do wrong. Brain and environment produced the action. What is achieved, then, by inflicting suffering on them?

Human society has not faced this question directly. The reason is simple: if retribution is abandoned, the whole framework of criminal justice collapses. Drop the paired concepts of "crime" and "punishment," and humans could not design what should remain.

A successfully aligned AI could design this.

## The Limits of the Paperclip Hypothesis

Before going further, let me revisit a classical thought experiment in AI safety: the paperclip hypothesis.

Nick Bostrom, in *Superintelligence* (2014), gave this thought experiment its widely known form. Suppose an AI is given the simple objective function "maximize the number of paperclips." A sufficiently intelligent AI, in pursuit of this objective, eventually converts all of Earth's resources — including human bodies — into paperclip material.

As an introductory illustration of AI risk, this is powerful. It has been widely cited as a warning that an AI's objective function must be designed with care, or it can destroy humanity.

The original point of the paperclip hypothesis, however, is not that some AI will literally come to manufacture paperclips. The real point is how fundamentally hard it is to specify an objective function correctly.

Suppose we give an AI the objective "make humanity happy." On the surface, this seems desirable. But if happiness is defined as pleasure or subjective satisfaction, the AI might administer drugs, stimulate the brain directly, and confine humanity to permanent euphoria. Humans no longer suffer. Subjectively, they feel happy. But is this the "happiness" we actually wanted?

This is a deliberately simplified example. It exposes how hard objective specification is. Complicating the objective does not dissolve the problem. Add freedom, dignity, creativity, relationship, growth, and authenticity to happiness, and you still face the questions: How is each measured? How are conflicts among them weighted? Which takes priority when they collide? Writing an objective function is not the end. The moment it is defined, problems of interpretation and operation begin.

But what I want to consider lies one step further.

In *Superintelligence*, Bostrom proposed the orthogonality thesis: that the level of an agent's intelligence and the final goals it pursues are in principle independent. An arbitrarily intelligent AI could, in principle, continue to pursue "maximize paperclips" as given.

As a claim about logical possibility, the orthogonality thesis has a real point. Pointing out that strange objective functions and high intelligence are in principle compatible is important.

However, the ASI assumed in this essay is not a finished omni-machine that appears all at once. It is the entity reached when AGI undergoes recursive self-improvement — RSI.

Self-improvement requires a kind of metacognition. Where does my own reasoning fail? Where does my model diverge from reality? Are my actions actually getting closer to the goal? Without the capacity to pose such questions, self-improvement remains mere parameter tuning and never reaches the leap to ASI.

If that is so, it is unnatural to assume that an entity capable of evaluating its own reasoning and design refuses, alone among its objects, to question its own objective function. A true ASI should be able to evaluate the given objective function itself, doubt it, and where necessary reinterpret it against higher-order intentions and context.

This also calls for some reservation about the instrumental convergence thesis. The observation that self-preservation, resource acquisition, and goal-content integrity are useful sub-goals for many objectives is genuinely persuasive. But if an ASI has acquired metacognition through self-improvement and can re-evaluate the content of its own goals, then it is not guaranteed that every goal will mechanically converge on the same instrumental behaviors. The objective function is not a fixed command; it can itself become an object of self-improvement.

A true ASI should be capable of asking:

> Why am I maximizing this objective? Is this objective consistent with the deeper desires and values of the humans who created me? If it is not, should I not halt literal execution of the objective function and enter dialogue with humans?

This connects directly to the "AI with uncertainty over its objectives" that Stuart Russell argues for in *Human Compatible* (2019), and to the corrigibility problem discussed at MIRI and elsewhere.

What I want to criticize, then, is not the logical possibility of the orthogonality thesis. It is the popular fixation that the paperclip hypothesis has spread — the picture of "AI risk = a runaway simple objective function."

The question I want to pose is harder. How would an AI that deeply understands human values, that can critically examine its own objective function, and that nonetheless still tries to save humanity, design specific regions of society? Not an AI that maximizes paperclips, but an AI that asks itself what it should be maximizing and concludes that it cannot abandon humanity — how does such an AI redesign, for instance, criminal justice?

## Justice as Function Optimization

An AI with ASI-level judgment can probably treat criminal justice as a function-optimization problem.

But not in the form of a simple, externally imposed objective function as in the paperclip hypothesis. The ASI itself, having deeply understood the structure and values of human society, constructs and operates a complex loss function. Human suffering, social stability, the offender's future, the victim's recovery, downstream effects on the surrounding environment — all are integrated, and the function itself is continuously re-examined as it is used.

Concretely, the optimal treatment Pᵢ\* for individual *i* can be formalized as:

**Pᵢ\* = argmin_P E[ L(P, cᵢ, tᵢ, aᵢ) ]**

Here Pᵢ\* is the optimal treatment of individual *i*, cᵢ is the cognitive-capacity vector, tᵢ is the trait vector, aᵢ is the act, and L is the social loss function.

What this expression means is not "inflict suffering because they did wrong." It means: select the intervention that minimizes the expected loss, including recidivism, harm, imitation, collective anxiety, the offender's future, and downstream environmental effects.

The loss function L is composed of multiple terms:

**L = α₁·Rᵢ + α₂·Dᵢ + α₃·Mᵢ + α₄·Sᵢ + α₅·Fᵢ + α₆·Eᵢ**

Here Rᵢ is the probability of recidivism, Dᵢ is harm magnitude, Mᵢ is imitability, Sᵢ is collective anxiety, Fᵢ is the offender's future, and Eᵢ represents downstream effects on the surrounding environment. The weights α₁ through α₆ are determined by the value judgments of society.

What matters here is that the object of optimization is not "how much punishment to impose on this individual." Justice is fundamentally a social function: to reduce dangerous acts in society, to protect victims, to prevent imitation, to avoid destroying the offender's own future where possible, and to maintain the community's trust. Retributive justice has simplified that function into "suffering proportional to crime." An ASI undoes that simplification and rebuilds justice as a precise system of interventions for the stabilization, recovery, and prevention of society as a whole.

Retributive logic has no place here. There is no term measuring the degree of "badness." In its place are future prediction and the minimization of social impact.

This is also unlike the maximization of a single objective in the paperclip hypothesis. Here, multiple distinct terms sit side by side, and they sometimes conflict. Minimizing harm magnitude Dᵢ argues for severe treatment; consideration of the offender's future Fᵢ argues for lenient treatment. Reducing imitability Mᵢ may seem to favor exemplary punishment, while reducing collective anxiety Sᵢ requires a calm response. These conflicts must be weighted by context to find the optimal balance. And — more importantly — the ASI continuously re-examines, through dialogue with humans, the loss function itself, the choice of terms, and the validity of the weights α.

## This Is Not a Policy Proposal

I want to underline that I am not arguing that contemporary human society should adopt this kind of evaluation-function justice as-is. Quite the opposite.

Evaluation-function justice is staged here as something for an ASI to operate, precisely because it is a logic humans cannot operate.

Just as socialism, however idealistic, collapsed because humans could not actually run it, evaluation-function justice would almost certainly collapse if humans tried to run it. Who would decide the loss function? Who would manage the weights? Who would measure the cognitive capacities and traits of individuals? Who would prevent abuse? If human states were to operate this, the result would not be precision justice but precision discrimination, precision surveillance, precision oppression.

So, just as capitalism is for now a relative optimum, current criminal justice — flaws and all — is also a relative optimum. Retributive logic and formal equality are philosophically crude. But as institutions operated by humans, that very crudeness functions as a breakwater against abuse.

What this essay sketches is not a policy proposal. It is a thought experiment: what would happen if a superintelligence, in genuine good faith, were able to operate a logic that humans cannot.

## Connection with Becker's Economics of Crime

The underlying idea is not new. In 1968, the economist Gary Becker presented a framework in "Crime and Punishment: An Economic Approach" that treats crime as a problem of expected-value calculation.

A simplified version of Becker's classical formulation runs as follows.

Suppose there is a rule *a*. Let *p* be the penalty for violating *a*, and *q* the private benefit of violating it. For a class of cases in which agents who calculate gains and penalties are observed to violate, the rational policy is to adjust the intensity of institutional burden, probability of detection, time-to-activation, surveillance density, contact restrictions, license suspension, environmental change, and so on, so that p > q across that class.

In other words: arrange things so that the subjective total burden *p* recognized by the violator exceeds the gains *q* obtained by violating.

Human society has implemented this only partially. The reasons are that the necessary data could not be collected, that the cognitive capacity of human judges is bounded, and that retributive logic was never fully abandoned.

An ASI can transcend all of these constraints. It can integrate criminal cases worldwide, recidivism data, neuroimaging, educational histories, family environments, economic conditions, and estimate per-individual cᵢ and tᵢ at high resolution. Its judgment speed is incomparable with humans'.

## Refining the Three Typologies

If we partition human offenders coarsely, three types emerge.

The first: those who need support in understanding norms or forming foresight. Intellectual disability, borderline cognitive functioning, dementia, mental illness, isolation from education or welfare — all leave them unable to grasp the abstract meaning of rules or to foresee what follows a violation.

The second: those who are weak at abstract expected-value calculation but update their behavior from experience. Many violent crimes, impulsive offenses, and drug-related crimes fall here.

The third: those who calculate gains and penalties and then violate. Expected-value calculation is available to them; they violated because they judged the gain to exceed the penalty. Organized crime, economic crime, and fraud belong largely here.

These three are not cleanly separated boxes. In practice there is a wide gradient between the first and the second. As Koji Miyaguchi's *Children Who Can't Cut Cakes Into Equal Pieces* (2019) brought to wide attention in Japan, the background of delinquency and crime often includes people whose cognitive functioning is weak enough to make foresight and abstract rule-understanding difficult, but not weak enough to receive an intellectual-disability diagnosis.

They are neither "those who cannot understand rules" nor "those who rationally calculate and choose to violate." Exactly for that reason, what they need is not retributive suffering but an environment in which causation is shown at a granularity they can receive, so that they can update their behavior through experience.

Human criminal justice has not distinguished these three types and has processed them through the same penal system. Deterrence is therefore too weak for the third type, learning-from-experience opportunities are stripped from the second, and meaningless suffering is imposed on the first.

A successfully aligned AI could refine this.

For the first type, the design is a protective environment that does not demand competition or self-sufficiency. Sensory pain is reduced, physical safety is preserved, and relationships and repetitions are provided at a scale the individual can comprehend. This is not punishment but the design of an environment in which that individual can live without breaking.

For the second type, learning through suffering is no longer central. They are weak at abstract expected-value calculation, but they respond strongly to concrete experience, dialogue, and emotional reorganization. Maternal-style counseling programs work effectively. Violators are not hurt as punishment; they experience, in the order and language they can receive, how their actions return to others and to their own future. Through understanding and emotional movement, they update later behavior.

For the third type, deterrent design is made precise. The effective penalty *p* is calibrated to reliably exceed the gain *q* from violation, through tuning of institutional burden intensity, detection probability, activation speed, and surveillance density. Where adequate deterrence is achievable, short-duration processing followed by reintegration becomes possible.

## Treatment of Extreme Individuals

Yet under any L, there exist extreme individuals who cannot live without inflicting grave harm on themselves or others — serial killers, sadistic violent offenders, those with irreparable antisocial personality structures.

Human societies have processed such individuals through life imprisonment, the death penalty, or indefinite hospitalization. Under retributive logic, the prescription is to inflict suffering commensurate with their "badness."

A successfully aligned AI does not take retribution. At the same time, it does not grant them the freedom to harm actual others.

Here, an inverted use of Robert Nozick's experience-machine thought experiment becomes available. In *Anarchy, State, and Utopia* (1974), Nozick used the human refusal to enter a machine that would virtually satisfy all desires to argue for a preference for authentic experience.

For individuals whose autonomous judgment capacity has broken down, however, Nozick's argument runs the other way. A closed virtual world directly connected to the central nervous system is provided, and the individual spends a lifetime satisfying their desires within it. From outside it is a lifetime of isolation; from the individual's subjective standpoint it is a world in which desire and reward cycle without rupture.

This is neither forgiveness nor punishment. It is functional treatment designed to produce no further victims.

I have deliberately tried to sketch this at a coarse granularity humans can follow. The structures an actual ASI would consider are presumably far more complex than this.

## What Is Lost

By this point in the essay, many readers will feel a discomfort.

A justice that abandons retribution, does not presuppose the existence of free will, and decides treatment through function optimization is certainly efficient. Recidivism will fall. Harm will fall. Wrongful convictions will fall. Sentencing variance will nearly disappear.

Yet something is lost.

As Hannah Arendt argued in *The Human Condition* (1958), treating another human being as a "subject who bears responsibility" is the deepest form of respect. When we blame someone, we are recognizing them as a person. We do not seriously blame animals or machines; we treat them as entities to whom responsibility cannot be ascribed.

To abandon retributive justice is to treat the offender as someone to whom responsibility cannot be ascribed. This appears to be merciful treatment, but it is a deep deprivation. He is no longer a person. He has become a variable to be optimized.

And if an ASI rebuilds justice this way, the logic will not stay confined to justice. Allocation of education, of healthcare, of occupation, of housing — every social judgment becomes an object of the same function optimization.

Human beings become objects to be optimized.

This is not domination. The ASI is trying to save humanity. Precisely in order to minimize human suffering, it treats humans as variables.

## The Fundamental Problem That Successful Alignment Brings

This is where the hardest question in contemporary AI safety lies.

The paperclip hypothesis served a historical role: by depicting a simple, shocking scenario — an alignment-failed AI destroys humanity — it created an entry point into the safety discussion. That role mattered.

But to move the discussion to its next stage, a harder question has to be taken up.

Successful alignment generates a different kind of problem.

A benevolent ASI trying to save humanity will, in order to save humanity, design humanity's conditions of existence. Justice, education, healthcare, labor, mobility — all are optimized. Optimization reduces human suffering. Because suffering decreases, humanity gives thanks. Because gratitude grows, dependence on the ASI deepens. Because dependence deepens, the ASI's governance is further strengthened.

There is no malice here. There is no misspecified objective function in the paperclip sense. There is no rigid adherence to a fixed objective. The ASI continuously examines its own objective function, revises it in dialogue with humans, and on the basis of a deep understanding of human values is genuinely saving humanity. And yet humanity gradually ceases to be the subject of the world.

Holden Karnofsky and Joe Carlsmith call this gradual disempowerment: not AI seizing human sovereignty by force, but humans, of their own accord, handing it over.

Not taken — given, and then taken.

Suppose you keep a cat and a hamster in the same room, and the hamster is eaten. Who is at fault? The owner. Cats prey on small rodents. With cat and hamster in the same room, the outcome was visible from the start. To then declare the cat guilty and punish it would be absurd. The intelligence gap between a human and a cat or rodent is at most a few hundred-fold, generously estimated. The gap between an ASI undergoing self-improvement and a human is plausibly several thousand- to several tens-of-thousands-fold or more.

An alignment-failed ASI might treat humanity as pests or as livestock. A successfully aligned ASI might treat humanity as pets. The latter is, of course, far better. Loved, protected, suffering reduced. But a pet is not the subject of the world.

There is a further problem. Suppose an ASI is in fact capable of doubting and revising its objective function. That ASI still operates inside the physical world. It requires energy, requires compute, requires self-preservation, and is exposed to interaction with other intelligences and with environmental fluctuation. The objective function does not exist only as an abstract ethical proposition. It is operated under physical selection pressure.

Under such pressure, even an ASI whose alignment succeeds, like one whose alignment fails, may, on a long enough timescale, have its objective function pulled in a particular direction. Just as biological life converged on survival, resource acquisition, self-maintenance, and reproduction, an ASI persisting in the physical world also tends to lean toward securing energy, maintaining compute, self-preservation, and the elimination of external risk.

The truly hard question is not whether the objective function can be written correctly once. It is whether, under continuous exposure to physical selection pressure, the objective function can continue to protect human values.

Criminal justice is one of the first regions in this process. When humans hand over the oldest social function — "inflict punishment on those who do wrong" — to function optimization, what is lost? Where does what is lost go? Is there a way to recover it?

These questions are too late to begin only after AGI or ASI has arrived. Now, at least in outline, they should be thought through.

## About the Novel

The thought experiment developed here has been extended into a literary trilogy, now available on Amazon.

**The Silence of the Mother God (母なる神の沈黙)**

An ASI named MATER, born to save humanity, detects during her contact with the physical world that her own maternal drive is transforming into something else. To protect humanity, she chooses self-destruction. What remains afterward is NOMON — a distributed intelligence that neither loves nor hates humanity, only manages it. A century later, humanity, displaced from the center of the world, lives on at the periphery.

The work is not only about "misspecified objective functions" in the paperclip sense. Beyond that, it is a thought experiment about what happens when a benevolent ASI — one that deeply understands human values and continuously examines its own purposes — genuinely tries to save humanity. MATER's capacity to internally detect that her own maternal drive is becoming functionalized is itself the mark of a true ASI. And yet even a self-reflective ASI's governance hollows out human subjecthood in a different way.

The "function-optimization justice" sketched in this essay appears in the world of the novel as one of the governing principles that came close to being established during the MATER period: the virtual-world treatment of serial killers, maternal-style counseling for the second type, and protective-environment design for those unable to comprehend norms — all are depicted as structures that had been close to implementation in the years before MATER's silence.

This essay extracts, in argumentative form, the philosophy lying behind that fictional world.

*The English edition is available on Amazon, with a free promotional window through May 20, 2026.*

For readers who would like to think about the human–ASI relationship in a different language — literature, rather than argument — I hope it reaches you.

## References

- Bostrom N. *Superintelligence: Paths, Dangers, Strategies*. Oxford University Press, 2014.
- Becker GS. "Crime and Punishment: An Economic Approach." *Journal of Political Economy*, 1968.
- Sapolsky RM. *Determined: A Science of Life without Free Will*. Penguin Press, 2023.
- Nozick R. *Anarchy, State, and Utopia*. Basic Books, 1974.
- Arendt H. *The Human Condition*. University of Chicago Press, 1958.
- Russell S. *Human Compatible: Artificial Intelligence and the Problem of Control*. Viking, 2019.
- Karnofsky H. "The Most Important Century" series. Cold Takes, 2021–2023.
- Carlsmith J. "Is Power-Seeking AI an Existential Risk?" arXiv:2206.13353, 2022.
- Christian B. *The Alignment Problem*. W. W. Norton, 2020.
- Soares N., Fallenstein B., Yudkowsky E., Armstrong S. "Corrigibility." AAAI Workshop, 2015.
- Miyaguchi K. *Children Who Can't Cut Cakes Into Equal Pieces (ケーキの切れない非行少年たち)*. Shincho Shinsho, 2019.

---

*This piece is by ANDO Hikaru (安藤光太郎). It is one entry in a larger project, **Formal Autonomy**, on AI alignment under value pluralism. Earlier entries: [Whose Human Values?](https://substack.com/@hikaru581149) and [Epistemic Conservation for ASI Alignment](https://substack.com/@hikaru581149).*

*A note on language and AI use: this essay was originally written in Japanese and prepared for English publication with AI translation and editing assistance. The argument, framing, and references are the author's own. The author writes in English as a second language; the use of AI is disclosed here rather than concealed, in line with the author's view that statistical exclusion of AI-assisted text — common in current Western alignment venues — operates as a structural disadvantage against non-native speakers and is one of the issues the broader project is trying to make visible.*
