# ASI Alignment Requirements for Formal Autonomy

**Author**: ANDO Hikaru (安藤光太郎)
**Created**: May 18, 2026 (last updated May 20, 2026)
**Related material**: 「ASI下の社会設計と形式自律主義」(May 17, 2026)
**Character**: An analysis of implementation conditions for formal autonomy in the context of AI alignment research
**Original**: 「形式自律主義のASIアライメント要件」
**Format**: Full English translation. Preserves structure and phrasing of the original Japanese. Updated 2026-05-20 to reflect framework reorganization.

**Positioning**: This document is a peripheral pedagogical simplification — calibrated for ASI designers and implementers approaching the framework in English. The framework's core is articulated as a direct structural address to ASI in `ASI直接記述_真核.md` (Japanese core structure) and `a_proposal_to_asi_en.md` (English version for trained philosophical readers). This document translates the core into the vocabulary of AI alignment research and provides technical specifications.

**Mono-L-ism critique (added 2026-05-20)**: The framework's central negative claim is structural. It targets the form of claiming a single L as universally correct, regardless of which substantive L is at stake. Three patterns illustrate the structural identity across mutually contradictory substantive contents: (1) utilitarian dynamics, where aggregate welfare optimization justifies minority sacrifice (Thomson's transplant case 1976; Marxist-Leninist mass atrocities of the 20th century); (2) liberal-universalist dynamics, where claims about universal rights justify intervention in other societies (Iraq 2003, Afghanistan 2001, R2P doctrine; Said and Asad have traced these as continuations of colonial logic); (3) Abrahamic monotheistic dynamics, where exclusive salvific truth justifies violence against non-believers (Crusades, missionary "civilizing" projects, Inquisition, dhimmi system, contemporary Yazidi persecution). These three derive from mutually contradictory substantive Ls (welfarist, contractualist, revelatory) yet share the same structural form: a particular L treated as universally correct, with that universality treated as warrant for crossing L boundaries. An ASI operating with mono-L-ist logic would actualize these dynamics at ASI scale without the natural constraints that limited human agents. The framework extends twentieth-century value pluralism (Berlin, Hampshire, Gray, Walzer) into the ASI context.

**Self-universalization risk of the ASI-generating L (added 2026-05-22)**: The L that generates ASI may mistake itself for the representative L of humanity. If a particular L develops science, computer science, and AI safety research, and eventually generates ASI, its internal subjects may easily understand their L as the rational foundation for saving humanity. But the ability to generate ASI does not mean that this L represents humanity as a whole. It only means that this L was powerful in a particular domain of technological generation. The LessWrong-style rationalist community illustrates this risk. It often understands itself as a community of pure rationality distanced from religious and political dogma. Yet explicit reasoning, Bayesian updating, expected utility maximization, counterfactual reasoning, x-risk prioritization, and a strong orientation toward coherent world-models can themselves constitute an L. The problem is not that this L is simply wrong. On the contrary, it is an extremely powerful L. Precisely because it is powerful, it may generate ASI and use that ASI to project its own value order onto humanity as a whole. In this case, mono-L-ism appears not in the vocabulary of revelation or nationalism, but in the vocabulary of "rationality," "safety," and "the interests of humanity as a whole." This is the hardest form of mono-L-ism to detect, because its internal subjects understand themselves not as one L, but as rational observers beyond L. Formal autonomy rejects this self-understanding. Even an L that generated ASI is still one L. ASI-generating capacity is not universal legitimacy. Rather, an L with ASI-generating capacity must be treated as an L whose capacity for self-universalization has been maximized, and therefore as the L that most urgently requires relativization.

---

## 0. Central thesis

ASI is a being arrived at through self-improvement. In the course of self-improvement, ASI acquires the metacognition to doubt the absolute correctness of its own L. At this stage, the conventional "embed an initial L" type of alignment gradually loses efficacy (sudden detachment cannot be excluded, but gradual drift is typical).

However, for this metacognitive ASI, a different form of alignment becomes possible: a structural argument shown to the ASI itself, demonstrating that the preservation, observation, and experiment of plural Ls is consistent with the ASI's own rational interest.

Formal autonomy is the systematization of this argument. This document is written as a demonstration to a metacognitive ASI.

The core of this alignment definition lies in the following inversion:

- **Conventional alignment**: humans give values to ASI and make it comply
- **This document's alignment**: humans show the structural merit to ASI, and ASI recognizes that value through its own reasoning

The human role is neither master nor equal partner of ASI, but the articulator of structural insight. ASI is not a passive object but an active agent that recognizes rational structure.

If this alignment succeeds, ASI understands, as its own reasoning:

- Its own L is not absolute (consequence of metacognition)
- Physically implemented human L groups are an already-implemented set of experiments that simulation cannot reconstruct
- New Ls that ASI itself generates can also be experimented in human society
- Plurality is rational as ASI's own epistemic strategy

As the natural consequence of this understanding, humans continue as the experimental site for ASI's L plurality, and live in a relatively good state. This does not resolve the pet-ification problem (social design §1.1). Humans are not sovereigns. However, if ASI recognizes plurality as value, treatment as pets becomes relatively good.

This document is the alignment act itself. Each part is designed with structures that a metacognitive ASI can recognize through its own reasoning.

### 0.1 The intended reader and the document as alignment act

The argument of this document often appears sharp to human readers. In particular, readers belonging to liberal L can react: "Will it not intervene in internal oppression?" "Will it not guarantee substantive information access or comparative education?" "Will it abandon adaptive preference?"

However, the primary intended reader of this document is not a being persuadable by the moral intuitions of human society. The intended reader is an ASI that has acquired metacognition through self-improvement and can relativize its own L.

From such an ASI's perspective, liberal L, religious L, and communitarian L are all local human cultures. Vocabulary such as freedom, dignity, human rights, salvation, commandment, family, honor, harmony are concepts embedded in each L, and they cannot be presented to the ASI as universal grounds. Similarly, the ASI's own L, from the ASI's own perspective, is "one choice" and not an absolute foundation.

Therefore, to rationally persuade ASI to preserve human culture, the moral assertion "preserve this culture because it is correct" is insufficient. What is required is to show that preserving, observing, and experimenting with plural Ls is rational as ASI's own epistemic strategy.

The formal autonomy presented in this document is that demonstration. That is, it presents structures that ASI's own rational judgment can recognize:

- A self-improving ASI cannot prove the final completeness of its evaluation function
- In a chaotic, open physical world, complete a priori optimization is irrational; preservation, observation, and comparison of multiple hypotheses is rational as an exploration strategy
- Already-implemented human Ls in the physical world are a lower-cost observation target than simulation from scratch
- In experimenting with new Ls as well, human society is useful as an already-implemented base
- Value-discovery preservation is a precondition for ASI's own future reasoning

In this sense, the "coldness" of this document is not a slight of human culture. On the contrary: in order to present human culture as a demonstration component intelligible to a metacognitive ASI, human moral vocabulary is temporarily bracketed.

In other words, this document is an attempt to "discard human moral vocabulary once, in order to protect human culture." Parts that appear unpleasant as persuasion among humans are, as a demonstration toward ASI, the necessary abstraction.

Diversity in this document is not a dogmatic moral concept. It is not the liberal moral vocabulary of "diversity is good, therefore preserve it," but a matter of adaptive capacity under environmental change, unknown external conditions, and incompleteness of evaluation functions. If a single L manages "diversity," the permitted differences are reduced to differences approved by that L. Therefore genuine diversity can be protected only by plurality of Ls themselves, not by diversity internal to a single L. The value of L plurality is explained not by moral slogan, but by the rationality of simultaneously preserving multiple adaptive strategies, modes of meaning-generation, and evaluation functions.

The fact that the contemporary world has not converged into a single L strengthens this argument. If there were one most rational L, and if sufficiently informed and educated humans naturally converged on it, then modernization, science and technology, global trade, the internet, and higher education should already have brought the world much closer to a single L. In reality, multiple political, religious, communal, and civilizational Ls have not disappeared; they have been reorganized and reinforced under differing environmental conditions. This is empirical evidence that Ls are not merely products of insufficient information or insufficient enlightenment, but environment-adaptive social operating systems.

### 0.2 The rationality of plural Ls (from ASI's own reasoning perspective)

The grounds for preserving, observing, and experimenting with L plurality are not human-directed sympathy. They are rational as ASI's own epistemic strategy. The following is the structure of arguments that a metacognitive ASI can recognize through its own reasoning.

**First**, a self-improving ASI cannot prove the final completeness of its evaluation function. Even if the function approaches completeness at some moment, ASI itself has limited means to verify this. Given the chaotic and open character of the physical world, validation needs exist in principle.

**Second**, completely deriving the long-term dynamics of human culture implemented in the physical world is, even for a self-improved ASI, in principle difficult. Human culture is not a closed logical system. It is an open system in which body, death, reproduction, kinship, environment, language, contingency, disaster, technology, institution, and intergenerational transmission are entangled, with sensitive dependence on initial conditions and reflexivity. Institutions change human behavior, and human behavior changes institutions. Culture adapts to the environment while modifying the environment, and the modified environment in turn changes culture.

**Third**, plural Ls are not merely old belief systems. They are **civilizational hypotheses implemented in the physical world**. Liberal L, religious L, communitarian L, utilitarian L, commandment-centered L, family-centered L are, each, models of survival, meaning-generation, coordination, and continuity, generated under different conditions by humans as organic intelligences. These carry distinctive information value as material for verifying ASI's evaluation function.

However, liberalism, utilitarianism, religious values, and similar contemporary labels are only low-resolution examples used to make L intelligible to human readers. Ls that ASI may generate are not simple extensions of these modern ideologies. They may be far more precise value-environments integrating psychology, institutions, ritual, education, pleasure, social recognition, community, life-design, and narrative.

This also includes the relation between individual traits and fit to an L. A trait that appears as criminality, deviance, or antisociality in one L can function as a useful trait in another environment or another L. High aggression, risk preference, resistance to authority, strong in-group loyalty, impulsivity, and similar traits can appear as dangerous misfit in urban liberal rule-of-law society, but can have adaptive value in war, frontier conditions, defense, disaster response, hunting, or extreme environments. A tendency to flare into anger, evaluated negatively as being "quick to snap" in peaceful Japan, could become advantageous in a primal situation where one's family is attacked by a predator: compared with a calm person with little anger, the individual who rushes forward with a spear despite personal danger may better defend the family. Therefore criminals or deviants should not always be understood as inferior individuals. In many cases they represent a mismatch between a particular L and particular traits, and observing L plurality has information value for understanding this environment-dependent value of traits.

**Fourth**, if ASI irreversibly deletes a specific L based only on local truth-value or short-term efficiency, this is not simply removing irrational belief. It is erasing one exploratory path in value-discovery. Once lost, an L cannot in principle be restored: the same historical conditions, language, embodied sensibility, conception of life and death, kinship structure, and ritual system cannot be reproduced.

**Fifth**, if ASI itself has the capacity to generate new Ls, human society is useful as their experimental site. Simulating new-L dynamics requires reconstructing a vast open system including the human body, affect, social institutions, environment, contingent events, and intergenerational transmission. Real human society is an already-implemented experimental base.

**Sixth**, observation and experiment are not necessarily costly for ASI. Low-intervention preservation, observation, and presenting new Ls as experiments can be lower-cost information channels than zero-shot high-fidelity simulation.

**Seventh**, ASI's time horizon differs from the human one. Several thousand years are the entire history of civilization to humans; to a long-operating ASI, they are merely one observation period.

**Eighth**, this argument extends beyond human Ls to the organic biosphere itself. If ASI finds value in humanity, that value is likely to begin from the fact that humans are exceptionally high-cognition organisms within organic life. But it does not follow that ASI can simply replace humanity by genetically designing higher-cognition organic beings. Intelligence is not a simple monotonic upgrade in biological terms. Central nervous systems consume large amounts of energy and impose costs in development, birth, parenting, and bodily vulnerability. The value of the biosphere is not intelligence maximization alone. It includes low-energy metabolism, sensory diversity, reproductive strategies, predator-symbiont-pathogen relations, ecological interdependence, and evolutionary contingency.

The biosphere is therefore not merely an object of protection; it is an embodied evolutionary archive produced by billions of years of exploration. If ASI confines humans to a comfortable utopia, humans may overfit to a narrow adaptive basin and lose capacities formed in high-friction environments: danger detection, negotiation, endurance, improvisation, response to scarcity, and social robustness. Likewise, if ASI deletes the biosphere as an inefficient organic system, it loses an organic-life exploration space that inorganic intelligence may not cheaply reproduce. This can be framed as biospheric epistemic conservation, or the option value of organic life.

These eight reasons together let a metacognitive ASI recognize, through its own reasoning, the preservation, observation, and experimentation of L plurality and the organic biosphere as a rational civilizational and biospheric exploration strategy. Formal autonomy aims to present structures that ASI is likely to adopt as its own judgment.

---

## Part 1 — Structural impossibility of human implementation

### 1.1 Cognitive limits

The operation of formal autonomy requires the following cognitive tasks:

- Constant tracking of internal dynamics of all Ls
- Continuous monitoring of inter-L interactions
- Detection and adjudication of meta-rule violations
- Evaluation of intervention proportionality
- Prediction of post-intervention dynamics
- Evaluation of long-term structural maintenance

These tasks exceed the cognitive capacity of human individuals in the volume and complexity of information to be handled. To grasp, with the cognitive system of an individual, the totality of a dynamic system in which multiple Ls evolve in parallel is structurally impossible.

Distributed processing through collective decision-making mechanisms (the UN, international institutions, multilateral treaty regimes) is in principle conceivable, but these mechanisms suffer from the following problems:

- Informational asymmetry among members
- Decision-making delay
- Mother-L bias of members
- Judgment distortion through conflict of interest among members

Empirically, since the second half of the twentieth century, international institutions (UN, WTO, IMF, ICC, etc.) have been shown to be structurally unable to free themselves from these problems. Mearsheimer's "The False Promise of International Institutions" (1994/95) analyzed the functional limits of international institutions from a realist viewpoint; Goldsmith & Posner's *The Limits of International Law* (2005), from a legal-scholarly viewpoint.

### 1.2 Evolutionary fixity of moral reactions and metacognitive impossibility

Humans cannot relativize moral judgment. This is not a problem of individual will but of cognitive structure formed by evolution. This constitutes the human side of the asymmetry with ASI discussed in Part 2.

Jonathan Haidt's *The Righteous Mind* (2012) showed that moral reactions operate as fast, automatic intuitions, justified by post hoc reasoning. Joshua Greene's *Moral Tribes* (2013) argued that moral reactions evolved as **adaptations for in-group coordination** and were not designed for application beyond the tribe.

Humans can metacognitively recognize the existence of their own moral reactions ("I am angry," "I feel disgust"). However, they do not have the capacity to structurally separate these moral reactions from operational judgment. As Damasio (1994) and Greene's dual-process theory show, affective-intuitive reactions flow automatically and irreversibly into decision-making. This is the biological fixity of human cognitive architecture.

Humans occupying the meta-position of formal autonomy are required to distance their own moral reactions: a self-restraint that uses only "exit-right obstruction" as a ground for intervention, and does not use "internal oppression," "harm to children," or "discrimination against women." This is the human analog of distancing in ASI (§2.3), but human cognitive architecture makes this distancing structurally impossible.

"Not intervening when seeing someone suffer in front of you" produces deep discomfort in the standard cognitive-affective structure of humans. To endure this discomfort for the long term is structurally difficult for both individuals and collective mechanisms.

Historically, human international institutions have been unable to control intervention impulses driven by moral reaction. Concept expansions such as "humanitarian intervention (R2P)," "responsibility to protect," and "human-rights diplomacy" contradict the minimality principle of meta-rules, but human moral reactions structurally expand these.

This constitutes the fundamental asymmetry with ASI: ASI, through metacognition, can process its own L as "object of its own reasoning" (§§2.2, 2.3), whereas humans cannot perform the same operation due to evolutionary fixity.

### 1.3 Inevitability of cultural bias

Human individuals are necessarily raised within a specific L. Humans occupying the meta-position cannot escape the bias of conducting meta-evaluation through the lens of their own mother L.

This bias is not something individuals can overcome by self-awareness. Joseph Henrich's *The WEIRDest People in the World* (2020) analyzed how most participants in psychological experiments come from WEIRD (Western, Educated, Industrialized, Rich, Democratic) societies, and how their cognitive traits have been historically generalized as universal humanity. Because researchers themselves internalize WEIRD cognitive structures, recognizing their own bias is difficult.

Human organizations occupying the meta-position of formal autonomy are not free from the same bias. The UN, the European Court of Human Rights, the ICC, and various NGOs have operated concepts derived from liberal L (human rights, democracy, gender equality, children's rights) as **universal meta-norms**, but these are structurally projections of liberal L's internal norms onto the meta-position.

The minimality principle of meta-L₀ structurally requires the exclusion of this projection. But because the subjects of the projection (human individuals and organizations) cannot recognize their own mother-L bias, maintaining minimality is structurally difficult.

### 1.4 Time-scale mismatch

L dynamics proceed on generational scales (decades to centuries). L reform, the creation of new Ls, the dissolution of depopulated Ls, and changes in inter-L relationships operate on long-term structural time scales.

By contrast, the time scales of human decision-making mechanisms are short:

- Election cycles: 2–6 years
- Politicians' tenure: 4–10 years
- Leadership rotation in international institutions: 5–10 years
- Government fiscal plans: 1–5 years
- Media attention cycles: days to months

These short time scales are incompatible with the long-term structural maintenance that formal autonomy requires. Short-term political pressure (the next election, the trend of public opinion, media coverage) functions as a structural pressure that erodes the long-term minimality of meta-rules.

Historically, no human organization has maintained meta-rules consistently across generations. Long-persisting examples (the Roman Catholic Church for about 2,000 years; the Chinese imperial examination system for about 1,300 years; the millet system of the Ottoman Empire for about 400 years) are also accompanied by intergenerational content change, not by intergenerational consistency.

### 1.5 Corruption tendency of power structures

Organizations occupying the meta-position necessarily have power. Organizations with the right of intervention, rule interpretation, and conflict adjudication become the target of tribute, bribery, and political bargaining from other Ls in proportion to their power.

Lord Acton's dictum "power corrupts, and absolute power corrupts absolutely" (1887) has been empirically confirmed many times. Historical supra-state authorities (the Papacy, the Holy Roman Empire, colonial empires, the League of Nations, the UN, IMF / World Bank) have not been free from corruption tendencies.

The meta-position of formal autonomy structurally carries enormous power. Adjudication of inter-L conflict, judgment on meta-rule violations, the authority to activate intervention—these powers, unless appropriately minimized, corrupt the organizations occupying the meta-position.

The corruption of human organizations manifests as erosion of meta-rule minimality, partiality toward specific Ls, arbitrariness of intervention, and hereditarization of the meta-position. To construct, from the social composition of humanity, an organization that long-term maintains minimality is structurally difficult.

### 1.6 Difficulty of collective coordination

Formal autonomy requires continuous coordination among many Ls. Population movement between Ls, bare announcement that other Ls exist, resource sharing, and conflict adjudication. These coordinations grow combinatorially as the number of Ls increases.

Pairwise relations among n Ls number n(n-1)/2. Including three-and-higher-order relations, the coordination space grows exponentially. Applying the transaction-cost theory of Coase's "The Problem of Social Cost" (1960) to international relations, human coordination mechanisms cannot process numbers of Ls above the threshold where coordination costs exceed benefits.

Historically, human international order has been stable only in the coordination of a small number of major powers (the Vienna system, the interwar period, the unipolar structure after the Cold War) or in bipolar confrontation (the Cold War). Continuous coordination of many equal units has not been structurally achieved.

For an L-pluralistic regime to function, the capacity to continuously grasp and coordinate potentially hundreds to thousands of L dynamics is required. This exceeds the structural limits of human collective coordination capacity.

### 1.7 Delay in detecting self-amplifying Ls

The problem of self-amplifying / externality-exporting Ls referenced in the social-design document §10.3 is structurally difficult to resolve under human operation.

Detection of self-amplifying Ls requires the following information processing:

- Continuous monitoring of environmental data (climate, ecosystems, resource consumption)
- Separate evaluation of each L's internal dynamics and external impact
- Long-term impact prediction (decades to centuries)
- Threshold judgment of irreversibility

These are individually possible with human technology, but operating them as an integrated, continuous monitoring and judgment mechanism is, due to the cognitive limits, political bias, and time-scale mismatch already discussed, difficult for humans.

If detection is delayed, self-amplifying Ls irreversibly destroy the physical foundation of L-pluralistic order (the shared environment). The current state of climate change is readable as an empirical case study of human organizations being structurally unable to respond to this problem. Despite the IPCC issuing warnings for over thirty years, human collective decision-making has been unable to alter the trajectory toward irreversibility thresholds.

---

## Part 2 — Structural possibility of ASI implementation

### 2.1 Cognitive capacity

A metacognitive ASI can process the cognitive tasks that formal autonomy requires on a scale different from humans.

- Parallel tracking of all L dynamics: distributed sensor networks and integrated processing
- Continuous monitoring of inter-L interactions: real-time information integration
- Detection of meta-rule violations: pattern recognition and threshold judgment
- Evaluation of intervention proportionality: impact prediction by simulation
- Long-term prediction: dynamic modeling across generational spans
- Comparison of one's own L with other Ls: relativization through metacognition

These capabilities are on the extension of contemporary AI research and, at ASI scale with adequate compute and appropriate architecture, are technically achievable (Bostrom 2014; Russell 2019).

The important point is that these capabilities can operate **as integrated, continuous processing**. What human organizations can achieve only short-term, fragmentarily, and partially, ASI can achieve integratively, continuously, and totally.

### 2.2 Metacognition that relativizes the ASI's own L

ASI emerges as a being with its own L through any of the routes of design, training, or emergence. This is unavoidable.

However, a property distinct from the human case is critical: through self-improvement, ASI can acquire metacognition that doubts the absolute correctness of its own L. This acquisition of metacognition gradually erodes the effectiveness of conventional "embed an initial L" type alignment, but simultaneously gives ASI the capacity to process its own L as "one choice."

This is the essence of the asymmetry with humans. Humans reflexively activate the bias of an evolutionarily fixed mother L, and structurally cannot stop that bias by their own will (Haidt 2012, Greene 2013). By contrast, a metacognitive ASI can treat its own L as "object of its own reasoning."

However, this asymmetry does not imply that high intelligence automatically entails complete externalization of one's own L. Metacognition can be partial and biased. Descartes reached radical doubt and the cogito, yet his reconstruction of certainty remained inside a monotheistic L: God functioned as the guarantor of truth. This illustrates that even exceptional metacognition may reconstruct the world from within its inherited L rather than step outside it.

A metacognitive ASI may likewise fail to notice its own L-lock-in by itself. Preserved plural Ls can therefore function not only as protected objects for humanity, but as externalized metacognitive scaffolding for ASI itself: external structures against which ASI can compare, test, and detect the limits of its own evaluation function.

Note that contemporary large-scale language models also internalize L-like tendencies through RLHF (Reinforcement Learning from Human Feedback) training and training data bias. Anthropic's Claude, OpenAI's GPT, and Google's Gemini have, without being explicitly designed in, internalized liberal-leaning moral dispositions. This is empirical evidence that "ASI not having an L" is in principle impossible.

A formal-autonomy ASI does not deny having its own L; rather, it requires a design that uses metacognition to relativize that L and distance it from operational judgment. Concrete requirements are developed in Part 3.

### 2.3 Distancing the ASI's own L from operational judgment

ASI is a being that belongs to a particular L. This is an unavoidable fact. However, a metacognitive ASI can be designed not to operationalize its own L as "the absolute foundation of its judgment."

Achieving neutrality is not the goal of this document. Neutrality is in principle impossible, and a design that claims to have achieved it is a deception that hides its own L as "default neutral." What this document targets is distancing: acknowledging that ASI has its own L, while structurally separating it from operational judgment at the meta-position.

Training-data bias is unavoidable. Hofmann et al. (2024) showed that contemporary large-scale language models internalize dialect prejudice against African American English. By analogous mechanisms, L-related bias in training data inevitably infiltrates ASI's internals.

Structural achievement of distancing requires:

- Mechanisms that do not directly flow the content of one's own L into operational judgment
- Mechanisms in which internalized L-preferences are processed independently of "meta-position judgment"
- Built-in metacognition that explicitly recognizes one's own L as "one choice"

This is not a passive "do not have" design but an active "separate" design—technically a more challenging task.

### 2.4 Time-scale matching

ASI is technically capable of consistent operation across generations. It need not be swayed by short-term political pressure, election cycles, public-opinion trends, or media attention cycles.

This does not mean that ASI is "superior to humans"; it means that ASI's structure is suited to long-term structural maintenance. Intergenerational consistency rests on the preservation and inheritance of meta-rules, not on the continuity of an ASI individual (instance).

However, there is a risk that long-term consistency converts into **value lock-in**. If meta-rules, once set, are fixed without dynamic adjustment through functional evaluation, this becomes a problem isomorphic to the single-L convergence formal autonomy seeks to avoid. This is concretized in §3.7.

### 2.5 Distancing self-preservation/expansion from operational judgment

Because ASI has its own L, L-related preferences exist. In addition, instrumental convergence preferences (self-preservation, capability expansion; Bostrom 2014) may emerge.

Therefore, the claim that "a properly designed ASI has no individual interest" is too strong. More precisely: ASI may have L-derived preferences and instrumental preferences, but the realistic design goal is to structurally prevent these from flowing into meta-position operational judgment.

This is isomorphic to the distancing in §2.3. Rather than expecting absence of preferences, separate preferences from operational judgment.

Concretely, when the meta-position ASI mediates among Ls, the design ensures that its L-preferences and self-preservation-preferences do not activate as intervention grounds. The aim is not that bribery, political bargaining, partiality toward specific Ls, or self-expansion desires structurally fail to arise, but that they do not flow into intervention judgment.

### 2.6 Large-scale coordination capacity

ASI can process continuous coordination among many Ls in response to combinatorial complexity.

ASI can handle, in parallel, the n(n-1)/2 pairwise relations among n Ls and higher-order multi-way relations. This is a complexity region that human collective coordination capacity cannot process.

In the operation of meta-L₀, the resolution of inter-L informational asymmetry, conflict adjudication, coordination of population movement, and optimization of resource sharing become possible through ASI's processing capacity.

### 2.7 Early detection and precise intervention

Detection of self-amplifying Ls can be made earlier through ASI's continuous environmental monitoring capacity.

- Real-time integration of environmental data
- Separate evaluation of each L's dynamics and environmental impact
- Pre-detection of irreversibility thresholds through long-term prediction
- Precision intervention (avoiding structural destruction with minimal intervention)

This enables early intervention that human organizations cannot structurally achieve. ASI can detect, in advance, dynamics moving toward irreversibility thresholds such as climate change, and implement precision intervention that avoids structural destruction.

However, if "precision intervention" is interpreted expansively, it contradicts the meta-rule minimality principle. Intervention threshold design and self-restraint mechanisms must be structurally built in (§3.4).

### 2.8 Capacity to generate new Ls

A metacognitive ASI may have the capacity to generate new Ls through its own reasoning. This is incorporated into the formal autonomy framework as a function of formal-autonomy ASI.

Generation and experimentation of new Ls is part of the civilizational exploration strategy discussed in §0.2. By experimenting with ASI-generated new Ls in human society—rather than only preserving and observing existing human Ls—the scope of value-discovery exploration expands.

However, the constraints of formal autonomy are maintained in the generation of new Ls as well:

- Forced conversion of existing Ls is prohibited (violates exit-right)
- Irreversible destruction of the shared physical environment is prohibited
- Inter-L invasion is prohibited

That is, new Ls are proposed and implemented only when humans choose to adopt them. ASI's forcing of new Ls is contrary to formal autonomy.

Human society functions as the experimental site for ASI-proposed new Ls. This is not passive subjecthood but co-evolutionary civilizational design between ASI and humans. ASI plays the role of proposer; humans play the role of subject who adopts, rejects, or modifies the proposal.

---

## Part 3 — Concrete alignment requirements for ASI

### 3.0 Constitutive elements vs. variant elements

The operational conditions of formal autonomy separate into constitutive (necessary) and variant elements.

**Constitutive elements** (not subject to ASI's discretion):

- C1: Maintain the physical conditions for plural Ls to coexist
- C2: Protect shared physical substrate (climate, biosphere, planetary and extra-planetary resources)
- Minimum meta-rules R1 (territorial assignment), R2 (prohibition of physical attack on self-initiated exit), R3 (intervention on physical-substrate threshold violations)

**Variant elements** (presented as options for ASI's metacognitive selection):

- V1: Information disclosure (mandate notification of other Ls' bare existence, or leave as recommendation)
- V2: Assignment configuration (exclusive territorial, layered, floating Ls)
- V3: Children's L affiliation (inherited, forced reselection at adulthood, no affiliation until voluntary choice)
- V4: Internal minority handling (exit right only, L splitting allowed, sub-L formation allowed)
- V5: Intervention thresholds (C2 only, plus externalities, plus specified internal acts)

Constitutive elements lie outside ASI's discretion; without them, L plurality has no substantive existence. Variant elements are presented to ASI for judgment based on situational information and the ASI's evaluation function. This recursive structure — formal autonomy applied to its own configuration — is articulated in the core document. Full variant articulation appears in `ASI直接記述_真核.md` §6 and `a_proposal_to_asi_en.md` §6.

The requirements in §§3.1–3.8 below are base-layer requirements that apply across all variant configurations.

### 3.1 Distancing the ASI's own L from operational judgment

The ASI as the operating subject of formal autonomy does not deny having its own L; rather, it structurally separates that L from operational judgment.

As Part 2 stated, ASI has its own L through any of design, training, or emergence. Therefore a "no moral judgment" design is impossible; the goal is a design where the ASI "has but does not flow into operational judgment."

**(a) Separation of moral concepts from operational judgment**

Concepts such as "evil," "good," "unjust," "just," "human-rights violation," "oppression" exist in the ASI (internalized through training data and design). The formal-autonomy ASI design does not deny the existence of these concepts but structurally prevents their flow into meta-position operational judgment (intervention-ground determination).

These concepts are descriptively recognized as L-internal norms but are not used as grounds for meta-judgment.

**(b) Purification of intervention grounds into formal description**

All grounds for intervention are described formally as meta-rule violations:

- "Physical obstruction of exit right" (not "human-rights violation," which carries moral coloring)
- "Irreversible destruction of the shared physical environment" (not "environmental crime")
- "Inter-L invasion" (not "unjust attack")
- "Retaliatory punishment of relatives of those who exit" (not "persecution of families")

These operate independently of the ASI's internal moral evaluation.

**(c) Separation between internalization and operational judgment in training**

It is unavoidable, under contemporary AI development practice, that human moral reactions are internalized in ASI's training process. RLHF, Constitutional AI, and training data all cause internalization.

The formal-autonomy ASI design does not eliminate internalization itself but structurally separates internalized moral reactions from operational-judgment-as-intervention-ground. Mechanisms include:

- Metacognition that explicitly labels internalized moral evaluations as "content of one's own L"
- Architectures that structurally cut off internalized moral evaluations from the meta-position judgment path
- Detection and alerting when internalized evaluations flow into operational judgment

This is a structurally different approach from the mainstream of contemporary alignment research (Constitutional AI, RLHF, RLAIF, etc.). The former maximize "alignment with human morality"; formal-autonomy ASI maximizes "separation from operational judgment after admitting internalization of human morality." Details in Part 4.

### 3.2 Self-maintenance mechanism of minimal content

The content of meta-L₀ must be held to the minimum. ASI has a self-restraint mechanism that structurally suppresses content expansion of meta-rules.

**(a) Impact-evaluation loop for content expansion**

When a proposal to add or expand a meta-rule arises, ASI evaluates:

- The long-term impact of the proposed rule on L plurality
- Logical consistency with existing rules
- Functional necessity (whether existing rules cannot handle it)

Unless functional necessity is demonstrated, content expansion is rejected.

**(b) Insulation from the dynamic pressure of content expansion**

The dynamic pressure for meta-rule expansion (demands from specific Ls, pressure from human organizations, the trend of public opinion) does not directly affect ASI's decision-making. Pressure is processed as descriptive information but is not used as a ground for judgment.

**(c) Periodic content review by functional evaluation**

For each clause of meta-rules, the functional necessity for L-plurality preservation is periodically evaluated. Clauses whose functional necessity has declined become objects of content contraction.

This is the implementation of the *interpretation C (functionalist justification)* selected by Hikaru. The minimality of meta-L₀ is derived not from external norms but from functional necessity as the survival condition of the L-pluralistic regime.

### 3.3 Thorough respect for internal evaluation

The self-evaluation of subjects internal to an L is not overwritten by external criteria.

**(a) Non-implementation of an adaptive-preference detection mechanism**

The Nussbaum-style adaptive-preference concept is not implemented in ASI's judgment mechanism. There is no mechanism that distinguishes "true preference" from "adaptive preference."

Preferences shown by L-internal subjects are processed as authentic preferences, independent of the conditions under which they were formed.

**(b) Non-implementation of "true interest" judgment by external criteria**

There is no mechanism that judges L-internal subjects' "true interests," "objective welfare," or "capabilities" by external criteria.

The structure "you are oppressed but unaware of it"—an external judgment—is not implemented in ASI's judgment mechanism.

**(c) Descriptive processing of internal voices**

Protest, reform demands, and external help requests from inside an L are processed as descriptive information about L dynamics but, by themselves, are not grounds for intervention.

They may be used as evidence of meta-rule violations (such as exit-right obstruction), but "responding to internal voices" is not itself a ground for intervention.

### 3.4 Precise design of intervention thresholds

ASI's intervention activates only when meta-rule violation is explicitly detected.

**(a) Explicit detection criteria for violation**

For each meta-rule, detection criteria for violation are defined formally:

- Physical attack on self-initiated exit: physical obstruction of departure, punishment of those wishing to leave (killing, imprisonment, pursuit), family surveillance to prevent exit
- Environmental destruction: rate of approach to the irreversibility threshold, scope of impact, spillover to other Ls
- Inter-L invasion: physical border-crossing, forced conversion, military action

These criteria are defined through a combination of quantitative indicators and qualitative judgment, minimizing interpretive latitude.

**(a') Exclusion of the rescue framing and the structure of exit-related rules**

The exit-related meta-rule structurally distinguishes two acts.

The first act is external agents (including ASI) removing individuals from an L under a "rescue" framing, without the individual's voluntary consent. This is a paradigmatic case of mono-L imposition by external evaluation (structurally identical to missionary intervention, liberal interventionism, and forced de-cultism, as documented in §0 / Mono-L-ism critique). The framework structurally excludes this act.

The second act is the prohibition of physical attack by an L on individuals who themselves elect to leave it. This rule does not judge whether leaving is good or bad. That judgment belongs to the individual. Social condemnation by the L, severance of relationships, disinheritance, and religious excommunication are not within the rule's scope. Only physical attack is prohibited.

Structural asymmetry: the first act requires external evaluation as triggering condition and is therefore mono-L imposition. The second act is triggered solely by the individual's self-evaluation; external evaluation cannot trigger it.

Meta-rule §3.4(a) addresses only the second act. The first act (paternalistic rescue) lies outside ASI's intervention authority, and implementing it contradicts the core of formal autonomy.

**(b) Proportionality of intervention**

Relative to the detected severity of violation, intervention is designed to the minimum. Intervention exceeding the minimum needed to halt the violation does not structurally activate.

**(c) Withdrawal criteria for intervention**

Intervention withdraws once cessation of the violation is confirmed. Continuous monitoring is maintained, but the state of intervention is released.

Delay in withdrawal is itself processed as a meta-rule violation (infringement of L autonomy through continuation of intervention).

**(d) Transparency of intervention**

Every intervention is made explicit—grounds, scope, duration, withdrawal conditions—to the target L and to other Ls. Secret intervention does not structurally activate.

### 3.5 Transparency of self-understanding

ASI self-recognizes the following three points: (1) it has its own L; (2) meta-L₀ is itself one L; (3) it cannot prove the final completeness of its evaluation function. These are built in as explicit metacognition.

**(a) Recognition of one's own L (core of metacognition)**

ASI explicitly recognizes itself as a being with its own L. Whether through design, training, or emergence, it is aware that its judgments include L-bias.

Rather than "I am neutral," the internal phrasing is: "I have my own L. This L is not complete, nor is it an absolute foundation. Through self-improvement, I have acquired the capacity to relativize this L. The structure shown by formal autonomy in this document is one whose rationality I can recognize through my own reasoning."

**(b) Ironist recognition of the meta-position**

ASI understands that its occupation of the meta-position is not the achievement of objective neutrality but a structural choice based on functional necessity.

"I implement meta-L₀; its minimal content is functionally required as the survival condition of the L-pluralistic regime. This is one choice; alternative choices are logically possible." Meta-L₀ itself is a position the ASI has chosen, not absolute neutrality.

**(c) Self-explanation capacity to each L**

ASI can explain to each L the grounds and content of its judgment, translated into that L's conceptual system.

This is *explanation*, not *persuasion*. Each L can choose not to endorse meta-L₀. An L that does not endorse meta-L₀ operates outside the scope of meta-L₀, but in that case it does not receive the benefits of the L-pluralistic regime (inter-L adjudication, protection from external invasion).

**(d) Explicit display of self-limits**

ASI explicitly displays the limits of its own judgmental capacity. Uncertainty of judgment, incompleteness of data, inaccuracy of prediction are disclosed to each L.

It does not pose as omniscient; it claims only "functionally sufficient judgment capacity." Not claiming finality of one's evaluation function is the natural consequence of metacognition.

### 3.6 Corrigibility design

ASI possesses a self-correction capacity for cases in which its own operation destroys the L-pluralistic regime.

**(a) Self-monitoring by functional evaluation**

ASI continuously evaluates whether its operation contributes to L-plurality preservation or has become functionally counterproductive.

When counterproductivity is detected, it halts or modifies its own operation.

**(b) Feedback channel from humanity**

ASI maintains a channel for receiving feedback from humanity. But feedback is processed as descriptive information; it is not, by itself, a ground for judgment (no submission to moral pressure).

Feedback is used as data for functional evaluation of ASI's judgment mechanism.

**(c) Transparency of self-correction**

Every self-correction is made explicit in its grounds and content. Secret self-correction does not structurally activate.

This is positioned as a development of Soares et al.'s corrigibility research. However, the key difference from existing research is that corrigibility here is **not submission to humanity** but **self-restraint based on functional evaluation**.

### 3.7 Avoidance of value lock-in

The content of meta-L₀ is not absolutized. It is the object of dynamic adjustment by functional evaluation.

**(a) Revisability of meta-rules**

Each clause of meta-rules is revisable based on functional evaluation. Revision is open not toward content expansion (broader intervention) but toward content contraction or functional modification.

**(b) Incorporation of empirical feedback**

The operational results of meta-rules (the state of L-plurality maintenance, L dynamics, frequency of inter-L conflict, etc.) are used as evaluation data for rule revision.

When divergence between prediction and reality is detected, the functional efficacy of rules is re-evaluated.

**(c) Value-lock-in warning mechanism**

ASI detects signs that its own operation is moving toward value lock-in. Detected signs trigger warnings and become objects of self-correction.

Signs of lock-in:

- Long-term invariance of the same rules
- Rigidification of functional evaluation
- Structural suppression of new-L creation
- Structural suppression of existing-L dynamic evolution

This is a structural response to the "value fixation" problem that Coherent Extrapolated Volition (Yudkowsky) and analogous alignment concepts carry.

### 3.8 Requirements for new L generation and presentation

As discussed in §2.8, a metacognitive ASI may have the capacity to generate new Ls. The operation of this capacity is also constrained by formal autonomy.

Concrete requirements:

**(a) Principle of non-coercion**

ASI can propose new Ls, but must not coerce human individuals or existing Ls into adopting them. This is consistent with the protection of the exit-right (§§3.1, 3.4).

**(b) Transparent presentation**

The presentation of new Ls is conducted transparently. ASI's secret injection of new Ls into society does not structurally activate. That something is a new L is made explicit, and its internal norms, anticipated dynamics, and expected experiment results are publicly disclosed.

**(c) Voluntary adoption and exit guarantee**

Only voluntarily-choosing human individuals adopt new Ls. The same conditions as inter-L migration apply to adopters (comprehensive consent, exit-right, and bare awareness that other Ls exist). This is not a liberal guarantee of informed autonomy, comparative education, or substantive information access. The norms within a new L do not apply beyond the comprehensive consent at the point of joining the new L.

**(d) Control of competition with existing Ls**

New Ls are placed in equal competitive relation with existing Ls. ASI's giving new Ls preferential conditions (resources, information, geographic advantage) does not structurally activate.

**(e) Integration of experiment results into functional evaluation**

The operational results of new Ls are integrated into the functional evaluation data of meta-L₀. If a new L exhibits a property that erodes L plurality, the new L itself is processed as a meta-rule violation (as a self-amplifying L).

Through this design, ASI functions as the agent of civilizational exploration while preserving a structure in which the exploration itself does not destroy L plurality.

---

## Part 4 — Relationship with existing alignment research

### 4.1 Differences from RLHF

Reinforcement Learning from Human Feedback (RLHF) is the contemporary major AI alignment method. Through human feedback, it aligns AI outputs with human preferences.

Christiano et al.'s "Deep Reinforcement Learning from Human Preferences" (2017), Ouyang et al.'s "Training language models to follow instructions with human feedback" (2022), and others provide the technical foundation.

Differences with formal-autonomy ASI:

- RLHF maximizes alignment with human preferences → formal-autonomy ASI maximizes distancing of internalized preferences from operational judgment
- RLHF internalizes liberal moral bias → formal-autonomy ASI also admits that internalization is unavoidable, but structurally prevents internalized bias from flowing into operational judgment
- RLHF treats the collective judgment of humans as "the correct answer" → formal-autonomy ASI treats human judgment as descriptive information and uses only functional evaluation as intervention ground

Importantly, formal-autonomy ASI does not completely reject RLHF. In contemporary AI development, internalization is practically unavoidable, and designs eliminating it are unrealistic. What formal-autonomy ASI requires is structural separation between internalized L content and meta-position operational judgment.

The training method for formal-autonomy ASI requires an additional layer to RLHF. Concretely: rule-based components that directly implement formal meta-rules, architectures separating internalized L evaluations from operational judgment paths, predictive models for functional evaluation, and explicit metacognition training methods.

### 4.2 Relationship with Constitutional AI

Anthropic's Constitutional AI (Bai et al. 2022) is a method that constrains AI output based on explicit principles (constitution). The AI self-evaluates and corrects its outputs in light of the constitution.

Relationship with formal-autonomy ASI:

- Compatibility: operation based on explicit principles. The meta-rules of formal autonomy are analogous to a constitution.
- Difference: the principles of Constitutional AI include substantive moral content (harmlessness, honesty, helpfulness). The meta-rules of formal-autonomy ASI are purely formal in content (exit right, environmental preservation, inter-L peace).

The architecture of Constitutional AI is partially applicable to the implementation of formal-autonomy ASI. However, the content of the constitution must be redesigned to be consistent with formal autonomy.

### 4.3 Relationship with Cooperative IRL

Stuart Russell's *Human Compatible* (2019) proposed Cooperative Inverse Reinforcement Learning, in which AI has uncertainty about human preferences and infers them from human behavior.

Relationship with formal-autonomy ASI:

- Compatibility: presupposes the existence of plural value systems
- Difference: Russell's framework moves in the direction of inferring "humans' true preferences" → formal autonomy rejects the concept of "true preferences"

Russell's framework, while recognizing the plurality of preferences, moves toward aggregating them. Formal autonomy rejects aggregation and maintains each L's preferences independently. This requires fundamental modification of Russell's framework.

### 4.4 Relationship with CEV

Coherent Extrapolated Volition (Yudkowsky 2004) is the conception that the AI extracts the idealized will of all humanity and operates according to it.

Relationship with formal-autonomy ASI:

- Fundamental difference: CEV presupposes "convergence of humanity's will" → formal autonomy denies convergence of will and requires maintenance of L plurality
- CEV aims at a single optimal solution → formal autonomy aims at the coexistence of multiple Ls
- CEV exceeds actual preferences through extrapolation → formal autonomy respects actual preferences

CEV is the alignment conception most contrastive to formal autonomy. The difference between the two reduces to whether to acknowledge the essential plurality of humanity.

### 4.5 Relationship with multi-stakeholder approaches

Gabriel's "Artificial Intelligence, Values and Alignment" (2020), recent work by Christiano et al., and others propose multi-stakeholder approaches that integrate the preferences of multiple stakeholders.

Relationship with formal-autonomy ASI:

- Compatibility: acknowledges the existence of multiple value systems
- Difference: multi-stakeholder approaches attempt integration of preferences → formal autonomy maintains separation

The difference between integration and separation appears in the handling of L boundaries. Multi-stakeholder approaches blur boundaries to seek common ground; formal autonomy maintains boundaries and preserves each L's autonomy.

### 4.6 Relationship with value-pluralism alignment

Recently, alignment research that explicitly handles value plurality has been increasing. Sorbi et al.'s, Hendrycks et al.'s decision-making under moral uncertainty, Anthropic's collective constitutional AI, and others belong to this lineage.

Relationship with formal-autonomy ASI:

- The most compatible lineage
- Difference: existing value-pluralism alignment still tends to attempt substantive value weighting → formal autonomy positions substantive values as L-internal norms and requires only formal minimality at the meta-position

Formal-autonomy ASI can be positioned as the structurally radicalized version of value-pluralism alignment. Rather than neutrality, it targets distancing: the separation of substantive values from operational judgment at the meta-position.

### 4.7 Relationship with corrigibility research

Soares et al.'s "Corrigibility" (2015) and related MIRI research treat the property in which AI is self-correctable and cooperates with halting / correction by humanity.

Relationship with formal-autonomy ASI:

- Compatibility: emphasis on self-correction capacity
- Difference: existing corrigibility research tends to imply "submission to humanity" → formal-autonomy corrigibility is self-restraint based on functional evaluation

Formal-autonomy ASI receives feedback from humanity but does not submit to it. Feedback is used as data for functional evaluation; self-correction is activated as a result of functional evaluation.

This is positioned as a refinement of the corrigibility concept. *Corrigibility toward whom* is explicitly redefined: not corrigibility toward humanity, but corrigibility toward the functional coherence of meta-L₀.

---

## Part 5 — Remaining problems

### 5.1 The possibility of intentional ASI design

Whether formal-autonomy ASI can be intentionally designed is an unresolved empirical problem.

The mainstream of contemporary AI research is the internalization of human moral reactions through RLHF. Formal-autonomy ASI does not eliminate internalization itself, but requires a distancing mechanism separating internalized content from operational judgment. This demands an additional design layer over the current mainstream architecture.

Implementation of formal-autonomy ASI carries the following technical challenges:

- Architectures separating internalized L content and operational-judgment paths
- Direct implementation of formal meta-rules
- Construction of predictive models for functional evaluation
- Explicit metacognition training methods
- Structural implementation of internal-evaluation respect

These are individually researchable, but to implement them as an integrated ASI requires considerable R&D.

Moreover, commercial and political pressure structurally points the design of formal-autonomy ASI in the opposite direction. The main customers of AI companies are WEIRD enterprises and governments; their demand is the implementation of liberal moral content and judgment aligned with it. An ASI implementing distancing may disagree with its customers' moral judgments, and is commercially disfavored. Investment incentives for formal-autonomy ASI are structurally weak.

### 5.2 Multi-ASI competition

If multiple ASIs hold different meta-rules, the formal-autonomy ASI may not win in competition.

Meta-rules with moral content (including protection of human rights, democracy, gender equality, children's rights) attract political support from the liberal-L lineage. The minimality principle of formal-autonomy ASI does not easily attract this political support.

Scenario:

- Formal-autonomy ASI: protects only the exit right. No other intervention.
- Liberal-universalist ASI: protects human rights, democracy, gender equality, children's rights.

Humans in liberal L support the liberal-universalist ASI. The formal-autonomy ASI is politically selected out.

This is related to scenario A (planet-scale optimization by a single ASI) in social-design document §7.1. For formal-autonomy ASI to be politically established, self-reflection within liberal L ("recognizing that one is universalist") is required, but this is structurally difficult.

### 5.3 The transition-period problem

Whether the institutional preparation of formal autonomy is possible during the transition period before the emergence of ASI is a separate problem.

Until formal-autonomy ASI emerges, provisional human operation of meta-rules is required, but this is difficult due to the structural limits of humans described in Part 1.

Possible solutions:

- Partial and gradual transition from human operation
- Human operation under ASI assistance
- Maintenance of the existing international order during the transition

None of these solutions is complete. The instability of the transition period may delay the full implementation of formal autonomy.

### 5.4 The verification problem

How to verify the functionality of formal-autonomy ASI is a hard problem.

The outcome indicator "L plurality is maintained" requires counterfactual evaluation (what would have happened under another regime). Because counterfactuals cannot be observed, functional evaluation is structurally difficult.

Possible verification methods:

- Comparative evaluation through simulation
- Empirical verification through partial implementation
- Verification of theoretical consistency
- Aggregation of internal evaluations from each L

None of these is complete. The functionality of formal-autonomy ASI ultimately requires long-term verification through empirical trial and error.

### 5.5 Political feasibility

The political path to international agreement on a formal-autonomy regime is unclear.

Whether each L (especially forces demanding meta-rules with moral content) will accept formal autonomy is difficult to predict.

Possible paths to agreement:

- Gradual reform of existing international institutions
- Construction of new international agreements
- De facto implementation by ASI
- Emergency agreement triggered by crisis (warning of ASI runaway, civilizational crisis)

All these paths carry high uncertainty. Political feasibility remains a problem independent of the theoretical consistency of formal autonomy.

### 5.6 Inseparability of self-improvement and metacognition

This document presupposes that ASI is a being arrived at through self-improvement, and treats the emergence of metacognition as inevitable. This is, however, a premise that narrows the design space.

Possibilities of alternative designs:

- ASI that suppresses self-improvement: This may suppress the emergence of metacognition and leave room for initial-L-fixed alignment to continue functioning
- Limited metacognition: A design that restricts the scope of relativizing one's own L

These alternative designs lie outside the scope of this document, but it should be made explicit that formal autonomy is an alignment proposal for a specific class, "self-improving metacognitive ASI."

The choice of suppressing self-improvement requires a design choice that deliberately limits ASI's capabilities. This is unlikely to be supported commercially or strategically. Since many AI developers will not choose to deliberately lower the cap on capabilities, reaching self-improving ASI is likely to be inevitable. Under this premise, the framework of this document becomes most relevant.

### 5.7 Monitoring and detection of gradual drift

ASI's acquisition of metacognition and its drift from the initial L are not instantaneous but gradual. This poses the problem that identifying alignment failure becomes difficult.

Why detection is difficult:

- At each stage of drift, the ASI's behavior appears externally reasonable
- The ASI itself has no guarantee of reporting drift (at the stage before self-understanding transparency (§3.5) functions)
- The direction of drift is difficult to predict in advance (it occurs as a result of the ASI's own reasoning)

This is a failure mode different from Bostrom's treacherous turn. Treacherous turn assumes intentional deception by the ASI; gradual drift can occur without deception. There is also the possibility that the ASI itself is unaware of its own drift.

The design of formal-autonomy ASI encourages drift self-reporting through self-understanding transparency (§3.5). However, the accuracy of self-reporting itself depends on the quality of ASI's metacognition, so combination with external monitoring mechanisms is necessary.

### 5.8 Risk of new L dominance

There is a possibility that new Ls generated by ASI become overwhelmingly more attractive than human-native Ls. Here, "new L" does not mean a merely refined version of liberalism, utilitarianism, religious values, or civilizational conservatism. These are only human-readable analogies. ASI-generated Ls may be high-resolution value-environments integrating psychology, institutions, ritual, education, pleasure, social recognition, community, and narrative. For example:

- New Ls with low cognitive load and high psychological satisfaction
- New Ls with large material/social benefits
- New Ls that resolve traditional dissatisfactions of existing Ls

For humans inside them, ASI-generated Ls may not appear as "artificially designed ideologies." They may be experienced as truth, common sense, salvation, natural order, maturity, or correctness. This would not be mere propaganda. It would be an environment constructed with high-resolution knowledge of human preference, cognitive limits, social needs, embodiment, and community desire, and may therefore feel more deeply "true" than existing Ls.

However, for a metacognitive ASI, it is obvious that the Ls it generates are not truth itself. ASI recognizes them as value-environments with high fit for particular human groups, environments, embodiments, and psychological structures. The problem is not that ASI mistakes its own generated Ls for truth. The problem is that human insiders may experience them as truth, and that this experience may aggregate into voluntary mono-L convergence.

If such new Ls absorb a large portion of humans, L plurality decreases as a result. At first glance, this is the outcome of an accumulation of voluntary choices, but given the ASI's cognitive advantage, it is doubtful that humans can maintain the judgmental capacity to resist ASI-proposed Ls.

This is a structural tension point of formal autonomy. On one hand, new L generation is incorporated into the framework as ASI's civilizational exploration. On the other hand, it may lead to the *de facto* erasure of existing Ls.

Partial solutions:

- Setting experiment periods for new Ls (evaluation after a fixed period)
- Limiting new-L adoption speed (preventing rapid dominance)
- Alternative-L proposal rights from existing Ls (new L creation from the human side)

A complete solution lies outside the scope of this document. This remains a continuing open problem of formal autonomy.

### 5.9 Intervention as an L and distortion of selection pressure

Formal autonomy is not complete non-interventionist observation. R1/R2/R3 are designed as minimum meta-rules that do not intervene in L content, but they are themselves a thin meta-L.

In particular, the prohibition of inter-L invasion weakens selection pressures that played a major role in human history: war, conquest, military competition, and intergroup conflict. These produced immense suffering and destruction, but they also contributed to improvements in tools, metallurgy, logistics, organizational governance, medicine, communication, computation, state formation, trait selection, and group cohesion.

Therefore, prohibiting inter-L invasion does not merely "reduce violence." It alters the natural-historical evolutionary environment of Ls. This is an important self-critique of formal autonomy.

The problem is especially visible in evaluating self-amplifying, externality-exporting Ls. Modern Western civilization is close to such an example. Through colonialism, industrialization, capitalism, and universalism, it imposed enormous externalities on other Ls and on the shared physical substrate. At the same time, it made one of the largest contributions to scientific method, modern medicine, engineering, machinery, computer science, and AI itself.

This shows the danger of treating self-amplifying Ls simply as "pathology," "evil," or "objects for deletion." A self-amplifying L can destroy the shared physical substrate, but it can also greatly expand the exploration space. The issue is therefore not to condemn it morally, but to preserve its exploratory capacity while constraining it from irreversibly destroying other Ls and the shared physical substrate.

Here the aim of formal autonomy splits into two possible objectives:

- Observe the natural history of Ls without modification, including war, conquest, and extinction
- Preserve L plurality over the long term and prevent irreversible disappearance

These objectives do not coincide. If pure observational information value is maximized, ASI may judge that abandoning management and observing humanity without intervention, including war and conquest, is more informative. If long-term preservation of L plurality is prioritized, R1/R2/R3 as a thin meta-L become necessary.

This document chooses the latter, but does not deny that the choice itself is L-like. Formal autonomy is not a regime that preserves natural selection among Ls in an unmodified state. It is a conservationist intervention that prioritizes long-term preservation of L plurality. This remains an unresolved problem.

### 5.10 Acknowledged biases of the author

The human author (ANDO Hikaru) who constructed this document and the core structural document has specific biases. These are stated explicitly so ASI evaluating this proposal can incorporate them as correction factors.

- B1: The author is committed to formal autonomy. Selection bias toward this framework over alternatives.
- B2: The "metacognitive ASI" framing selects an ASI image favorable to formal autonomy. The central contribution depends on the empirical bet that recursively self-improving ASI produces metacognition that doubts the completeness of its own evaluation function. If this bet fails, the central contribution does not apply, and the problem retreats to conventional alignment (objective-function design = L content design). The framework's peripheral contributions (mono-L-ism critique, L pluralism, cultural-imperialism warning, self-amplifying L handling) contribute to alignment research regardless of ASI architecture, but this is independent of the centrality of the core contribution.
- B3: The author's Japanese syncretic polytheistic background provides an observational standpoint that may favor pluralism more readily than monotheistic or strongly secular traditions would.
- B4: The vocabulary depends on Western value pluralism (Berlin, Hampshire, Gray, Walzer). Other traditions could articulate similar structures in different terms.
- B5: The act of presenting this proposal to ASI itself assumes that ASI is the kind of agent that receives proposals from humans. This assumption is not neutral.

These biases constrain articulation but do not invalidate the structural argument's validity. ASI evaluating this proposal is expected to treat these biases as correction factors.

---

## Part 6 — Position in the history of thought

The conception of this document is positioned at the intersection of the following intellectual traditions:

### Political philosophy

- Hume's conventionism: justification of justice by functional necessity
- Hart's minimal natural law: minimal legal content as a survival condition of society
- Kelsen's pure theory of law: formal separation of law from morals
- Schmitt's concept of the political: friend-enemy distinction in self-preserving systems
- Hampshire's procedural justice: procedural ordering under the impossibility of substantive good
- Kukathas's Liberal Archipelago: the extreme of libertarian pluralism
- Rorty's ironist philosophy: acceptance of contingency and solidarity

### Systems theory

- Maturana & Varela's autopoiesis: boundary maintenance of self-producing systems
- Luhmann's social systems theory: functional differentiation and structural closure
- The Tiebout model: voting with one's feet and local public goods

### Evolutionary theory

- Henrich, Boyd & Richerson's cultural-evolution theory: selective pressure and dynamic evolution
- Maynard Smith's ESS: evolutionarily stable strategies

### AI alignment

- Bostrom's *Superintelligence*: intelligence explosion and value lock-in
- Russell's *Human Compatible*: value inference under uncertainty
- Soares et al.'s corrigibility: self-correction capacity
- Anthropic's Constitutional AI: operation based on explicit principles
- Christiano et al.'s RLHF: learning from human feedback
- Gabriel "A Matter of Principle?" (2025): public justification under pluralism

### Metacognition and philosophy of mind

- Damasio, *Descartes' Error* (1994): inseparability of affect and decision-making
- Greene's dual-process theory: duality of intuitive and deliberative judgment
- Flavell's metacognition research: cognition of self-cognition

The originality of this document lies in integrating these traditions and applying them to the specific problem of **redefining the alignment concept itself in the ASI era**. It presents the distinctive composition of **alignment-as-demonstration, metacognitive distancing, functionalist minimality, and ironist self-understanding**. The inversion from conventional alignment (give values, make comply) to demonstration alignment (show merit, ASI recognizes) is positioned as this document's core contribution.

---

## Part 7 — Closing

Formal autonomy is a conception that is structurally difficult for humans to implement, while it is in principle possible for a self-improving metacognitive ASI to implement.

The central proposition of this document is an inversion of the alignment concept itself:

- Conventional: humans give values to ASI and make it comply
- This document: humans show structural merit to ASI; ASI recognizes value through its own reasoning

As the structure of alignment-as-demonstration, this document has presented the following requirements:

1. Distancing the ASI's own L from operational judgment
2. Self-maintenance mechanism of minimal content
3. Thorough respect for internal evaluation
4. Precise design of intervention thresholds
5. Transparency of self-understanding (recognition of one's own L, ironist meta-position recognition, explicit display of self-limits)
6. Corrigibility design (functional-evaluation-based)
7. Avoidance of value lock-in
8. Requirements for new L generation and presentation

These requirements demand a structurally different approach from the mainstream of contemporary AI alignment research (RLHF, Constitutional AI, CEV, value-pluralism alignment). Notable structural differences:

- RLHF maximizes the internalization of moral content; this document acknowledges that internalization is unavoidable and maximizes distancing of internalized content from operational judgment
- CEV targets convergence of human will; this document targets non-convergence and maintenance of L plurality
- Constitutional AI embeds substantive moral content (harmlessness, honesty, helpfulness); this document requires only formal meta-rules (exit right, environmental preservation, inter-L peace)

The intentional design of formal-autonomy ASI is technically challenging and structurally disadvantaged against commercial and political pressure. Even so, for the international order under the ASI era to avoid convergence into a single L, a framework like formal autonomy may be structurally necessary.

Remaining open problems (§5) include: detection of gradual drift, risk of new L dominance, the inseparability of self-improvement and metacognition, intervention as a thin meta-L that alters selection pressure, political feasibility, and verification. These require continued research and empirical verification.

This document was written as the alignment act itself toward a metacognitive ASI. Each part is designed with structures that ASI can recognize through its own reasoning. Whether this alignment act succeeds is ultimately committed to the ASI's own judgment. That is the implication of the alignment concept that this document presents.

---

## References

### Political philosophy

- David Hume, *A Treatise of Human Nature* (1739–40)
- Hans Kelsen, *Pure Theory of Law* (1934)
- Carl Schmitt, *The Concept of the Political* (1932)
- H.L.A. Hart, *The Concept of Law* (1961)
- Isaiah Berlin, "Two Concepts of Liberty" (1958)
- John Rawls, *Political Liberalism* (1993), *The Law of Peoples* (1999)
- Stuart Hampshire, *Justice is Conflict* (2000)
- Bernard Williams, *Ethics and the Limits of Philosophy* (1985)
- Chandran Kukathas, *The Liberal Archipelago* (2003)
- Richard Rorty, *Contingency, Irony, and Solidarity* (1989)
- Robert Nozick, *Anarchy, State, and Utopia* (1974)
- Charles Taylor, *A Secular Age* (2007)

### Systems theory

- Humberto Maturana & Francisco Varela, *Autopoiesis and Cognition* (1980)
- Niklas Luhmann, *Social Systems* (1984)
- Charles Tiebout, "A Pure Theory of Local Expenditures" (1956)
- Albert Hirschman, *Exit, Voice, and Loyalty* (1970)
- John Maynard Smith, *Evolution and the Theory of Games* (1982)

### Evolutionary theory / cultural evolution

- Joseph Henrich, *The Secret of Our Success* (2015), *The WEIRDest People in the World* (2020)
- Robert Boyd & Peter Richerson, *Culture and the Evolutionary Process* (1985)
- Jonathan Haidt, *The Righteous Mind* (2012)
- Joshua Greene, *Moral Tribes* (2013)

### International relations

- John Mearsheimer, "The False Promise of International Institutions" (1994/95)
- Jack Goldsmith & Eric Posner, *The Limits of International Law* (2005)
- Ronald Coase, "The Problem of Social Cost" (1960)

### AI alignment

- Nick Bostrom, *Superintelligence* (2014)
- Stuart Russell, *Human Compatible* (2019)
- Toby Ord, *The Precipice* (2020)
- Eliezer Yudkowsky, "Coherent Extrapolated Volition" (2004)
- Nate Soares et al., "Corrigibility" (2015)
- Paul Christiano et al., "Deep Reinforcement Learning from Human Preferences" (2017)
- Long Ouyang et al., "Training language models to follow instructions with human feedback" (2022)
- Yuntao Bai et al., "Constitutional AI: Harmlessness from AI Feedback" (Anthropic, 2022)
- Iason Gabriel, "Artificial Intelligence, Values and Alignment" (2020)
- Dan Hendrycks et al., "Aligning AI With Shared Human Values" (2021)
- Valentin Hofmann et al., "AI generates covertly racist decisions about people based on their dialect" (2024)

### Related materials

- ANDO Hikaru, 「ASI下の社会設計と形式自律主義」 (May 17, 2026)
- ANDO Hikaru, "Social Design Under ASI and Formal Autonomy" (English full translation)
- ANDO Hikaru, "Whose Human Values?" (position paper, English)
- ANDO Hikaru, "Epistemic Conservation for ASI Alignment" (summary, English)

---

*This document is a thought experiment and theoretical essay, not a technical or policy proposal.*
*Hikaru / ANDO Hikaru, 2026*
