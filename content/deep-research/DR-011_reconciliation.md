# DR-011 Reconciliation: Predictive Processing & Free-Energy

Cross-check of two independent deep-research reports answering DR-011 (empirical support vs overreach for predictive processing / free-energy).

- **CDR** = ChatGPT report (`raw_reports/chatgpt/DR-011-CDR.md`)
- **Agent** = Autonomous agent report (`raw_reports/agent/DR-011.md`)

## Agreements (claims both reports make — high confidence)

1. **The layered-claims framing is essential.** Both insist the literature must be split into separable levels: (a) the brain is predictive/anticipatory; (b) cortex specifically implements predictive coding (dedicated error/prediction units, laminar microcircuit); (c) precision-weighting via neuromodulatory gain; (d) the FEP as a normative/mathematical principle. Evidence strength decreases down this ladder.

2. **Prediction-related signals are real and robust.** Mismatch responses, expectation effects, and surprise responses replicate across species, modalities, and methods. This is the empirical backbone PP must explain. (Agent: HIGH; CDR: treats "prediction-related, mismatch-related, error-like signals in some tasks/areas" as the strongest-supported tier.)

3. **Bastos et al. 2012 is a theoretical correspondence / hypothesis paper, not proof.** Both explicitly flag that the canonical microcircuit mapping (superficial = error, deep = prediction; gamma feedforward, beta/alpha feedback) is a proposal with correlational support for directionality, not a direct demonstration that cortex implements that exact circuit as a general rule.

4. **Feedforward gamma / feedback beta-alpha asymmetries are directional markers, not uniquely diagnostic of prediction vs error messages.** Both warn these spectral asymmetries are compatible with predictive coding but also with generic hierarchical communication.

5. **MMN / repetition suppression is a mixture of model-violation and adaptation components.** Both reject the "MMN = pure prediction error" reading and the "MMN = pure adaptation" reading; the balance depends on controls and paradigm design. Adaptation/novelty/surprise/attention confounds are the central live empirical dispute.

6. **Pérez-González et al. 2024 (eLife) is the key direct precision-ACh result** — cholinergic modulation affects prediction-error responses but not repetition suppression (strongest infragranular), with author-acknowledged caveats (exogenous ACh, anesthetized prep, no receptor-specific manipulation). Both cite the same paper.

7. **NE/noradrenaline ↔ unexpected uncertainty / volatility has the better empirical case; ACh is weaker.** Both cite Nassar et al. 2012 (pupil-linked arousal regulates learning rate) and rate NE-volatility support above the ACh-precision mapping.

8. **The strict ACh = expected uncertainty / NE = unexpected uncertainty one-to-one code is NOT settled.** Both say it is a useful, partly-supported heuristic, not a receptor-level fact; the real picture is distributed, receptor- and task-specific.

9. **Bayesian-consistent behavior/signals ≠ demonstrated Bayesian implementation.** Both warn against the jump from "behaves as if Bayesian" to "cortex implements predictive coding."

10. **Attention-as-precision is partly redescription.** Both note it is elegant and data-consistent but does not uniquely outcompete classical attentional-gain accounts.

11. **The FEP as a grand unifying theory is not falsifiable as stated; the testable content lives in the process theories (predictive coding / active inference).** Both reach the same headline verdict, citing Friston's own framing (least-action / Hamilton's-principle analogy) and the philosophy-of-science critique (Colombo & Wright appears in both).

12. **"FEP explains life, mind, agency, consciousness" is creator/popular overreach** and should not be recorded as an empirical neuroscience finding. Both place this in their "do not absorb" lists.

## Conflicts

| Point | CDR (ChatGPT) says | Agent says |
|---|---|---|
| Human laminar 7T fMRI direction (Aitken et al. 2024 / "expected vs unexpected" in V1) | Expected orientations represented **broadly across all V1 layers**, with unexpected information decoding **most robustly in superficial layers**. Frames it as suggestive, indirect, layer-specific PE in superficial laminae. Does NOT assert a clean deep-layer prediction locus. | Unexpected (PE) signals decodable in **superficial** layers **AND** expected/prediction-related stimulus-specific activity in **deep** layers — i.e. a two-sided dissociation "matching the Bastos/Rao-Ballard architecture." This is a stronger reading of the same study than CDR gives. |
| Pupil ↔ LC-NE proxy reliability | Treats pupil-linked arousal as a usable index of NE/volatility (Nassar, Lawson) without foregrounding the pupil-LC mismatch; relies on pupillometry for the NE case. | Foregrounds Megemont et al. 2022 (eLife): pupil is **not** an accurate real-time readout of LC spiking, explicitly weakening "NE = precision" claims built on pupillometry. CDR does not cite this caveat. |
| Active inference vs reinforcement learning | Dedicated claim + section: distinctive epistemic-value prediction; Sajid et al. (AIF ≈ Bayesian model-based RL) and Gijsen et al. (better fit in 2 of 4 datasets, ~half of participants info-gain sensitive). Confidence: low-to-moderate. | **Not addressed.** Agent has no active-inference-vs-RL section. (Asymmetry, not a factual contradiction.) |
| Confidence label on the predictive-coding-implementation tier | "moderate" (substantial support for prediction-related computations, not established mechanism). | "MEDIUM" overall, but elevates the architectural tier somewhat by calling Aitken 2024 "its first direct human laminar support" and citing converging mouse L2/3 mismatch neurons. Slightly more optimistic phrasing on the microcircuit's recent empirical traction. |

Note: the Aitken-2024 reading (row 1) is the only substantive factual divergence. The others are emphasis/coverage differences rather than contradictions of fact.

## Unique to CDR (ChatGPT)

- **Macaque/primate null and negative results** as a counterweight: Solomon et al. (limited PE in macaque V1/V4), Kaliukhovich & Vogels (no surprise response in macaque IT). The "failures matter" framing is absent from the agent report.
- **Species/task-generalization problem** stated explicitly: strongest error-neuron evidence comes from specialized rodent sensorimotor/auditory-self-generation settings (Keller; Audette & Schneider), while macaque visual physiology is mixed.
- **Specific discriminating cellular/intracranial findings** beyond mouse V1: Dürschmid et al. (prefrontal prediction signals independent of PE), Audette & Schneider (auditory cortex cells encoding specific unexpected self-generated outcomes), Casado-Román et al. (no-repetition controls in rat mPFC).
- **Detailed MMN control logic**: Jacobsen & Schröger many-standards control, cascade controls, Wacongne and Bekinschtein local-global hierarchy, Todorovic & de Lange (RS vs expectation-suppression dissociable in time), Parras et al. (PE components increase toward cortex), Fishman (adaptation in A1).
- **Marshall et al. 2016 and Lawson et al. 2021** pharmacology (propranolol slows updating under volatility; antagonist dissociation of NE vs ACh roles) — a fuller neuromodulation causal package.
- **Granular FEP-critique taxonomy**: distinguishes Biehl/Pollock/Kanai (lemma + Markov-blanket-equivalence is wrong as stated), Aguilera et al. (blanket holds only in narrow parameter regime), Bruineberg / Raja (post-hoc Markov blankets in biology), Hohwy (FEP as regulatory principle). Agent cites only Colombo & Wright and Sánchez-Cañizares.
- **Predictive coding ≈ backprop** (Whittington & Bogacz): PC is one local-learning implementation family among several, not uniquely singled out.
- A "what to validate against primary papers locally" section (process guidance).

## Unique to Agent

- **Explicit pupil-LC unreliability caveat** (Megemont et al. 2022) — a load-bearing methodological correction the CDR lacks.
- **Walsh et al. 2020 (Ann NY Acad Sci) and the Bogacz/Spratling-adjacent "empirical status" review** as the sympathetic-reviewer source concluding evidence offers only *modest* support for *separate, dedicated* prediction vs prediction-error populations.
- **Laminar-fMRI methodological confound foregrounded**: gradient-echo 7T BOLD superficial/draining-vein bias and small samples for Aitken 2024.
- **Feuerriegel-adjacent ERP confound critique** and FFA statistical-learning-inflates-repetition-suppression paper as concrete "PP evidence may not survive controls" citations.
- **Millidge, Seth & Buckley 2021** review as a framing source.
- More compact, single-source-per-claim structure with confidence tags inline (Claims 1-8).

## Verdict

Convergence is **high** on substance and verdict. Both reports independently arrive at the same skeptical, tiered conclusion: prediction signals are robustly real (high confidence); the specific predictive-coding microcircuit is a well-motivated but not-yet-proven correspondence (medium); precision-neuromodulation mapping is suggestive-not-settled with NE > ACh and no clean one-to-one code (medium-low); and the FEP-as-grand-theory is non-falsifiable framing whose empirical content reduces to the process theories (low as an empirical claim). The shared, independently-derived claims warranting **raised confidence** are: (1) the necessity of separating the predictive/predictive-coding/precision/FEP levels; (2) Bastos 2012 as hypothesis-not-proof; (3) gamma-beta asymmetries as directional-but-not-diagnostic; (4) MMN as a mixture phenomenon; (5) Pérez-González 2024 as the key precision-ACh result with its caveats; (6) NE-volatility support exceeding the ACh-precision case; and (7) the FEP falsifiability split. The one claim warranting **lowered/flagged confidence** is the human laminar deep-vs-superficial dissociation (Aitken 2024): the two reports describe the same study differently — the agent asserts a clean two-sided "errors-superficial / predictions-deep" match to Bastos, while the CDR reports predictions as broadly distributed across layers with only the error signal superficial. Combined with the agent's (uniquely cited) gradient-echo superficial-bias and small-sample caveats, the strong two-sided architectural reading should be treated as promising but unsettled, not as direct confirmation. Two areas are under-covered rather than disputed and should be validated against primaries: active-inference-vs-RL (CDR only) and the pupil-LC proxy unreliability (agent only) — each is a genuine gap in the other report, not a conflict.
