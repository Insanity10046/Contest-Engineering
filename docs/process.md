# The ten steps

| # | Step name | Method | Artifact | Phase |
|---|---|---|---|---|
| **1** | **Frame the mandate** | Ends–Ways–Means–Risk | Authority brief | before |
| **2** | **Survey the contest** | Intelligence cycle | Baseline picture | before |
| **3** | **Model the adversary** | Level-k modeling | Adversary model | before |
| **4** | **Analyze the rules** | Doctrinal analysis | Rule analysis | before |
| **5** | **Select the representation** | Formalism triage | Representation brief | before |
| **6** | **Model the contest** | Extensive-form game modeling | Formal model | before |
| **7** | **Design the architecture** | Pattern language | Architecture spec | before |
| **8** | **Stress-test the design** | Wargaming | Evaluation report | before |
| **9** | **Conduct the contest** | OODA | Conduct log | during |
| **10** | **Review the outcome** | After-action review | Record, precedent, lessons | after |

**Steps 1–8 = before. Step 9 = during. Step 10 = after.**

**1 → 2 → 3 ↔ 4 → 5 → 6 → 7 → 8** (fail → back to 7) **→ 9** (wrong → back to 8; adversary adapted → back to 3; rules shifted → back to 4) **→ 10 → 2 or 1.**

## The warrants, in parallel

Standing → Reading → **Opposition** → **Interpretation** → **Selection** → Codification → Setting → Stress → Conduct → Settlement.

# IN DEPTH
## Selection / Select the representation
| Question type | The question sounds like | Formalism family |
|---|---|---|
| **Structural** | "What are the entities, rules, and relations?" | Architecture map, coupling diagram |
| **Argumentative** | "How will the rule system be read, and what claims survive?" | Argument diagram, issue tree |
| **Sequential** | "What order of moves, what branches, what does each side know when?" | Extensive-form game tree, decision tree, battle diagram |
| **Interactional** | "What stable configuration of strategies results?" | Normal-form game, security/Stackelberg game |
| **Emergent** | "What patterns arise from many heterogeneous actors?" | Agent-based model |
| **Evidential** | "What records exist, and how will they be attributed?" | Trace map, evidence chain |
| **Perceptual** | "What does each party believe, including about the other?" | Belief-hierarchy / influence diagram |

### The adequacy checklist

The chosen formalism must answer **yes** to all of these, or be rejected with a stated workaround:

1. Can it represent **two or more players** with **distinct information**?
2. Can it represent **order and timing**?
3. Can it represent the **rule constraint** — not just the rule, but how it binds?
4. Can it represent the **trace/evidence** dimension, or does it need a secondary?
5. Can it represent **adaptation** — the adversary changing behavior in response?
6. Can it represent **uncertainty about the adversary's model of you** (reflexivity)?
7. Can it be **reviewed by someone who wasn't in the room**?

**Item 5 is the gate.** A formalism that cannot express response is disqualified at step 5, not discovered at step 8. That single rule is the reason this step exists.
