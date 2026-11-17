# Glossary

## Method inventory (high level)
1. Contest architecture mapping
2. Adversary decision modeling (roles, incentives, perception, decision cycle)
3. Mechanism and rule design
4. Information-flow and disclosure mapping
5. Affordance and space design (physical and interface)
6. Trace mapping and forensic-readiness design
7. Multi-domain sequencing design
8. Wargaming and adversarial simulation
9. Security-game and agent-based modeling
10. Design-time evaluation: robustness, escalation, collateral, legitimacy

Each method is expanded in the syllabus; each must eventually have a benchmark.

# Glossary List

**Status tags:** [S] stable · [P] provisional · [C] contested · [B] borrowed. Restricted terms (R-series) are listed separately because they are **flagged, not adopted**.

## A. Core concepts

**1. Contest** [S]
*Def:* A structured interaction in which two or more parties pursue incompatible or partially incompatible objectives within a defined environment and over a defined horizon.
*Not:* Any conflict, disagreement, or competition. A contest requires (a) identified parties, (b) a defined environment, (c) a horizon, (d) partial or full objective incompatibility.
*Types:* physical, informational, rule-based, hybrid. Hybrid is the default in real conflict; single-domain contests are the exception and usually an analytical simplification.

**2. Contest architecture** [S]
*Def:* The coupled configuration of rule, information, physical/procedural, trace, and sequencing structures that define how a contest will unfold.
*Not:* A strategy, a plan, or a set of moves. The architecture is the environment in which moves are made.
*Note:* This is the field's engineered artifact.

**3. Contest engineer** [S]
*Def:* A practitioner trained to model, design, evaluate, and assure contest architectures.
*Not:* An operator, commander, litigator, or intelligence officer. The contest engineer designs the field of play and its evidence record; others act within it.
*Scope:* Acts under lawful authority; subject to the assurance gate (§8).

**4. Contest archetype** [P]
*Def:* A recurring structural pattern of contest (e.g., asymmetric disclosure contest, procedural chokepoint contest, attribution contest, repeated-entry market contest).
*Use:* Archetypes are the field's unit of reusable design knowledge, analogous to design patterns.

**5. Desired outcome** [S]
*Def:* The specified end-state the architecture is designed to constrain toward, stated in observable terms.
*Not:* A goal, vision, or intention. A desired outcome must be observable, time-bounded, and falsifiable.
*Distinction:* "Win" is not a desired outcome; "opponent's admissible argument set is reduced to X by phase 3" is.

**6. Constraint** [S]
*Def:* A design-induced reduction in the set of feasible or likely adversary actions and interpretations.
*Not:* Determination. Constraints shift probabilities and narrow option sets; they do not compel. See R-3.

**7. Contest lifecycle** [P]
*Def:* The three phases — before, during, after — across which architecture operates.
*Note:* The "after" phase (trace, record, attribution, precedent) is the most under-designed and is a defining concern of the field.

**8. Design variable** [S]
*Def:* Any element of the contest architecture that the engineer can set, and whose setting changes adversary behavior or interpretation.
*Examples:* filing deadlines, disclosure rules, room layout, log retention, order of moves.

**9. Contest terrain** [S]
*Def:* The domain in which a component of the architecture operates: physical, informational, or rule-based.
*Not:* "Domain" in the military sense (land/sea/air/space/cyber), though the two can be mapped.

**10. Hybrid contest** [S]
*Def:* A contest in which two or more terrains are simultaneously load-bearing.
*Note:* The default case. Analysis that treats terrains separately is a simplification requiring justification.

## B. Adversary and decision

**11. Adversary** [S]
*Def:* A party whose objectives are partially or fully incompatible with the desired outcome, and whose decisions are adaptive.
*Not:* Opponent (too narrow — implies symmetric contest), stakeholder (implies shared interest), actor (too neutral).
*Note:* "Adversary" is a design-relative term, not a moral judgment.

**12. Adversary model** [S]
*Def:* A structured representation of how a specific adversary perceives, decides, and adapts, sufficient to support design decisions.
*Not:* An intelligence dossier, a psychological profile, or a prediction. It is a design input, not a collection product.
*Contents:* objectives, incentives, information access, perception filters, decision structure, adaptation speed, tolerance for loss.

**13. Decision cycle** [B]
*Def:* The observe–orient–decide–act loop by which an adversary converts information into action.
*Use:* Borrowed from military theory. Used here descriptively, not as a targeting framework.
*Note:* "Breaking" a decision cycle means imposing a mismatch between the adversary's cycle time and the environment's rate of change — not attacking a person.

**14. Bounded decision process** [S]
*Def:* A decision process constrained by limited information, limited computation, cognitive bias, organizational friction, and time.
*Note:* The field assumes bounded, not fully rational, adversaries. Rational-actor models are limiting cases.

**15. Adaptive opposition** [S]
*Def:* An adversary who observes the architecture and changes behavior in response.
*Consequence:* Every architecture must be evaluated against a *responding* adversary, not a static one. This is the field's core evaluation problem.

**16. Perception** [S]
*Def:* The adversary's model of the situation — what they believe is happening, what they believe is knowable, and what they believe others believe.
*Note:* Treated as a design surface (information architecture) and as a modeling input (adversary model).

## C. Environment

**17. Environment** [S]
*Def:* The structured set of conditions within which a contest occurs, comprising rule, information, physical/procedural, and trace components.
*Not:* "Context" (too vague), "setting" (too passive). The environment is designable.

**18. Rule environment** [S]
*Def:* The set of procedures, constraints, entitlements, thresholds, and enforcement mechanisms that govern admissible action.
*Note:* Includes formal law and informal procedure; both are designable.

**19. Information environment** [S]
*Def:* The set of conditions governing what is knowable, by whom, when, and at what cost.
*Components:* disclosure, secrecy, signaling, narrative, verification, deception.

**20. Physical and procedural environment** [S]
*Def:* Space, access, visibility, tempo, and interface structures that channel action.
*Note:* "Procedural" is included because in legal and administrative contests, procedure functions as physical space.

**21. Affordance** [B]
*Def:* A property of the environment that suggests or enables a particular action to a particular actor.
*Source:* Ecological psychology / design; adopted via CPTED and interface design.
*Use:* The field designs affordances so that the adversary's *easiest* action is the intended one.

**22. Trace** [S]
*Def:* Any persistent record — physical, digital, testimonial, procedural — produced by action within a contest.
*Not:* Evidence. A trace becomes evidence only when read and admitted under a rule environment. The distinction is load-bearing.

**23. Trace environment** [S]
*Def:* The designed set of conditions governing what traces are produced, who can access them, and how they will be interpreted.
*Scope:* Design is limited to lawful record design, retention, disclosure, and forensic readiness. Manipulation is prohibited (R-4).

**24. Forensic readiness** [B]
*Def:* The pre-positioning of record-keeping and interpretive capacity so that traces can be read and attributed when needed.
*Source:* Digital forensics; generalized here to all terrains.

**25. Attribution** [S]
*Def:* The process by which a trace is linked to an actor, and the credibility of that link.
*Note:* Attribution is a contest in itself and is frequently the real objective of hybrid contests.

## D. Methods

**26. Architecture mapping** [P]
*Def:* The method of rendering a contest's five components and their couplings in a form that supports design and evaluation.
*Output:* a contest architecture map; the field's primary design artifact.

**27. Adversary decision modeling** [S]
*Def:* The method of constructing and validating an adversary model for design purposes.
*Not:* Prediction. A good model yields design-relevant constraints, not forecasts.

**28. Mechanism design** [B]
*Def:* The design of rules and incentives such that self-interested actors produce a desired outcome.
*Source:* Economics. Adopted as a core method, extended with perception, trace, and physical variables.

**29. Strategic orchestration** [S]
*Def:* The design of the order, timing, and cross-domain coupling of moves across the contest lifecycle.
*Replaces:* "Military strategy" as the field's general term, so the field is not military-only.

**30. Wargaming** [B]
*Def:* A structured adversarial simulation used to test an architecture or a plan against a responding opponent.
*Use:* Primary validation method for sequencing and adaptation.

**31. Red-teaming** [B]
*Def:* Structured adversarial analysis aimed at finding failure modes in a design or system.
*Note:* A method within the field, not a synonym for it.

**32. Adversarial user journey** [P]
*Def:* A step-by-step reconstruction of how an adversary encounters, interprets, and acts within an architecture.
*Source:* Adapted from UX and service design.

**33. Trace mapping** [P]
*Def:* The method of enumerating what traces an architecture produces, who can read them, and how they will likely be interpreted.
*Use:* Designed jointly with information and rule architecture.

**34. Benchmark scenario** [P]
*Def:* A shared, reproducible contest scenario with defined parties, environment, and evaluation criteria, used to compare methods.
*Note:* The field's equivalent of a dataset. Without these, the field cannot be taught or tested.

**35. Security game** [B]
*Def:* A game-theoretic model of adversarial interaction with resource constraints, typically Stackelberg-style.
*Use:* One modeling tool among several; insufficient alone because it omits perception and trace.

## E. Evaluation and assurance

**36. Robustness** [S]
*Def:* The degree to which the desired outcome is preserved under adversary adaptation and environmental perturbation.
*Metric:* Report as a range of adversary responses, not a point estimate.

**37. Escalation risk** [S]
*Def:* The probability and severity of an adversary responding in a way that expands the contest beyond its intended bounds.
*Note:* Mandatory in every architecture evaluation.

**38. Collateral effect** [S]
*Def:* Effects on third parties not party to the contest.
*Note:* Includes effects on institutional trust, not only on individuals.

**39. Legitimacy** [S]
*Def:* The degree to which the architecture is accepted as appropriate by relevant institutions and publics.
*Note:* Legitimacy is a design constraint, not a public-relations concern. Architectures that "work" but lose legitimacy are failures.

**40. Contest assurance** [S]
*Def:* The pre-deployment audit of an architecture against the ten assurance commitments (§8).
*Status:* No artifact is contest engineering without it. This is the field's professional gate.

---
