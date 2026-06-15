---
tags: [audit, moc]
---

# Content Audit — Correctness & Credibility

> Adversarial audit by a 17-agent fact-check team (one per section). Each verified load-bearing citations via WebFetch and graded the page. Findings drive fixes; see per-issue `fix`. Generated 2026-06-15.

## Grades

**A**: 9 · **B**: 8

| Section | Grade | Issues (H/M/L) | Citations OK |
|---|---|---|---|
| [[creativity-identity-purpose]] | A | 0/0/4 | 4/4 |
| [[decision-making-emotion-language]] | A | 0/0/4 | 4/4 |
| [[dopamine-reward-addiction]] | A | 0/1/3 | 3/5 |
| [[focus-attention-cognitive-control]] | B | 0/3/3 | 5/5 |
| [[general-neuroscience-health]] | B | 0/2/3 | 3/5 |
| [[hormones-endocrine-health]] | A | 0/0/6 | 5/5 |
| [[live-q-a-ama-mixed-topics]] | B | 0/1/4 | 4/4 |
| [[longevity-aging-supplementation]] | A | 0/1/3 | 4/4 |
| [[metabolism-exercise-nutrition]] | B | 1/1/4 | 2/5 |
| [[mood-anxiety-depression]] | B | 0/3/3 | 4/7 |
| [[neuroplasticity-learning-memory]] | B | 0/2/4 | 4/5 |
| [[pain-injury-physical-health]] | A | 0/1/4 | 4/5 |
| [[perception-predictive-processing-consciousness]] | A | 0/1/3 | 3/5 |
| [[psychiatry-clinical-disorders]] | B | 0/1/4 | 4/4 |
| [[relationships-social-behavior]] | A | 0/1/2 | 5/5 |
| [[sleep-circadian-rhythms]] | B | 0/3/3 | 5/6 |
| [[stress-cortisol-resilience]] | A | 1/0/2 | 4/4 |

## High & medium severity findings (actioned)

### [[dopamine-reward-addiction]] — A
- **[medium] bad_citation** — DR-009 key finding graded [high]: 'Mechanism is established preclinically: GLP-1 receptors in mesolimbic reward areas (VTA, nucleus accumbens) and NTS; GLP-1RAs blunt drug/food-evoked dopamine signaling and reduce reward-seeking in rodents.' cites https://pmc.ncbi.nlm.nih.gov/articles/PMC12244148/. That article reports semaglutide ENHANCED VTA dopamine signaling during the reward-collection (consu
  - *fix:* Either swap the citation for a review that actually documents GLP-1RA blunting of drug/food-evoked mesolimbic dopamine (e.g. an Egecioglu/Jerlhag-lineage review), or soften the claim to match PMC12244148 ('GLP-1RAs modulate mesolimbic/NTS reward circuitry and reduce reward-seeking in rodents; effect

### [[focus-attention-cognitive-control]] — B
- **[medium] factual_error** — Lines 7, 22, 112 repeatedly date the 'low dopamine hypothesis' of ADHD to being 'formalized ~2015.' There is no canonical 2015 formalization. The dopamine/catecholamine hypothesis of ADHD dates to the 1970s and was developed through the 1990s-2000s (e.g., Levy 1991; Volkow's PET imaging work, 2000s; the dopamine transporter focus predates 2015 by decades). The specific '~2015' date appears to be a
  - *fix:* Remove the '~2015' date or replace with accurate provenance, e.g., 'a long-standing model (catecholamine hypothesis, developed from the 1970s onward; refined with dopamine-transporter and network-imaging work since the 2000s).' If a specific recent paper is meant, cite it; otherwise drop the year.
- **[medium] overstatement** — Lines 11 and 43 state methylphenidate and amphetamine salts are 'structurally and functionally close to street stimulants' / 'structurally/functionally close to cocaine/amphetamine,' tagged [high]. This is imprecise on two counts: (1) Adderall is amphetamine (mixed amphetamine salts), not merely 'close to' it; (2) methylphenidate is NOT structurally close to cocaine — it shares a functional mechan
  - *fix:* Separate structure from mechanism: 'Amphetamine salts (Adderall) ARE amphetamine; methylphenidate (Ritalin) is structurally distinct from cocaine but shares its dopamine-reuptake-blocking mechanism. Functionally these are stimulants.' Keep [high] only for the functional-stimulant claim.
- **[medium] wrong_confidence** — Line 54 (and protocol line 89) tags 'through-a-window sunlight is ~50x less effective than direct/open exposure' as [high]. The ~50x figure is a specific Huberman talking point reflecting lux attenuation through glass; the order-of-magnitude direction is sound but the precise 50x multiplier is loosely sourced and context-dependent (glass type, angle, weather). A precise numeric multiplier does not
  - *fix:* Downgrade the numeric multiplier to [medium] and soften: 'window glass substantially reduces effective light intensity (creators cite ~50x); get light outdoors when possible.' Keep [high] only for the directional claim that window light is much weaker.

### [[general-neuroscience-health]] — B
- **[medium] factual_error** — Line 46: '"Junk DNA" is a misnomer — ~95% non-coding DNA is largely regulatory, not packing material. [high]'. Two problems: (1) the figure is ~98-99% non-coding (only 1-2% protein-coding), not 95%; (2) 'largely regulatory' overstates consensus — the function of much non-coding DNA remains genuinely debated, with substantial fractions (introns, pseudogenes, transposon/viral fragments, intergenic D
  - *fix:* Revise to: '"Junk DNA" is a misnomer — the ~98-99% non-coding genome contains extensive regulatory and structural elements, though the functional fraction remains debated and is not all regulatory. [high] that non-coding ≠ junk; [medium] on how much is functionally regulatory.'
- **[medium] overstatement** — Line 45: 'Dopamine encodes anticipation/prediction, not reward receipt ... [high]'. The reward-prediction-error / anticipation framing (Schultz) is well-established, but the flat 'not reward receipt' is an overstatement: dopamine also signals reward-prediction error at outcome (including unexpected receipt), and dopamine's role spans motivation/movement, not solely anticipation. Stated as an absol
  - *fix:* Soften to 'Dopamine primarily encodes reward prediction error and anticipation rather than simple reward consumption' and keep [high] only on the prediction-error core, noting the receipt-signal nuance.

### [[live-q-a-ama-mixed-topics]] — B
- **[medium] factual_error** — Line 50: 'Brief cold (cold shower/immersion 1-3 min, generally <=5-6 min) raises core temperature via the medial preoptic thermostat and drives adrenaline.' Brief cold exposure does not acutely raise core body temperature during the exposure — skin and peripheral temperature drop, and core temperature can fall. The commonly cited 'rise' is a rebound/thermogenic effect that occurs AFTER exiting the
  - *fix:* Reword to: 'drives a surge of adrenaline/noradrenaline and a delayed thermogenic rebound that warms the body after exit' — drop or qualify the claim that cold itself 'raises core temperature' during immersion.

### [[longevity-aging-supplementation]] — A
- **[medium] overstatement** — The claim 'Caloric restriction extends lifespan ~30% across many animal models (rodents, dogs, monkeys); this is one of the most reproduced findings in biology. [high]' overstates the primate and canine evidence. The ~30% magnitude is essentially a rodent finding. In rhesus monkeys the two landmark studies disagreed: the Wisconsin study showed a survival benefit but the NIH/NIA study found NO exte
  - *fix:* Split the claim: keep [high] for rodents ('CR extends lifespan up to ~30-40% in rodents — among the most reproduced findings in biology'), and downgrade the primate/dog statement to [medium] with the caveat that the Wisconsin and NIA rhesus studies disagreed on lifespan (NIA found no extension) and 

### [[metabolism-exercise-nutrition]] — B
- **[high] bad_citation** — DR-007 key finding: "Alternate-day fasting is not superior to daily calorie restriction for weight loss (1-yr RCT, N=100, ~6% loss in both), and has higher dropout (38% vs 29%)" is cited to https://pubmed.ncbi.nlm.nih.gov/24215592/. I verified that PMID 24215592 is Varady et al. 2013, a 12-WEEK, N=32 trial of ADF vs CONTROL (no calorie-restriction comparator) — it does not contain a 1-year design,
  - *fix:* Replace the URL with https://pubmed.ncbi.nlm.nih.gov/28459931/ (Trepanowski 2017 JAMA Intern Med).
- **[medium] wrong_confidence** — Section 1: "~5–30 reps/set are roughly equally effective for growth provided sets approach muscular failure ... [high]". The load-independence-of-hypertrophy finding (Morton/Schoenfeld) is real but the FULL 5–30 (i.e. ~30%–85%+ 1RM) equivalence is still actively debated, rests on small trained-subject samples, and very-low-load training to failure is uncomfortable/uncommon in practice. A [high] ta
  - *fix:* Downgrade to [medium-high] and note the equivalence is best-supported in the ~30–80% 1RM band and depends on genuinely training to/near failure.

### [[mood-anxiety-depression]] — B
- **[medium] factual_error** — Line 47: 'Creatine monohydrate augments SSRI response (2012 JAMA Psychiatry RCT, women with MDD)'. The cited trial (Lyoo/Kim et al., creatine + escitalopram in 52 women with MDD, 5 g/day) was published in the American Journal of Psychiatry, vol 169(9):937-945, September 2012 — NOT JAMA Psychiatry. JAMA Psychiatry did not exist under that name in 2012 (its predecessor Archives of General Psychiatry
  - *fix:* Change 'JAMA Psychiatry' to 'American Journal of Psychiatry' (Lyoo et al., 2012). Apply the same fix to the Actionable protocols creatine entry (line 79) if it inherits the citation.
- **[medium] miscredit** — Line 58: 'risk of heart attack is ~21x higher on the day a loved one dies ... [medium-high] (O'Connor's research).' The ~21-fold elevation in acute MI risk within the first 24 hours of bereavement is from Mostofsky, Mittleman et al., Circulation 2012 ('Risk of Acute Myocardial Infarction After the Death of a Significant Person in One's Life'). Mary-Frances O'Connor is a grief neuroscientist who ma
  - *fix:* Attribute the 21x figure to Mostofsky/Mittleman et al. (Circulation, 2012). Keep O'Connor credited for the grief-biology/timeline framing (the 'no single correct timeline' point is genuinely hers).
- **[medium] wrong_confidence** — Lines 15 and 39: depression marked by 'an abnormal evening (~9 p.m.) cortisol peak rather than the healthy morning peak', tagged [high] on line 39. The robust HPA-axis literature shows elevated evening/nocturnal cortisol, a flattened diurnal slope, an elevated cortisol awakening response, and dexamethasone non-suppression — i.e., a blunted/dysregulated rhythm, not a literal wholesale phase-shift t
  - *fix:* Downgrade to [medium] and reword to 'elevated evening/nighttime cortisol and a flattened diurnal slope (HPA-axis dysregulation)' rather than describing a clean peak that moves from morning to evening.

### [[neuroplasticity-learning-memory]] — B
- **[medium] wrong_confidence** — Line 28 4x-cortex claim tagged high but human PFC expansion is contested.
  - *fix:* Downgrade to medium, hedge the 4x figure, cite Semendeferi 2002.
- **[medium] overstatement** — Line 42 lumps psychedelic and SSRI plasticity as one serotonin pathway.
  - *fix:* Note distinct, debated mechanisms for each.

### [[pain-injury-physical-health]] — A
- **[medium] bad_citation** — The episode table uses YouTube IDs that appear to be internal transcript identifiers rather than the canonical published video URLs. For the Mackey pain episode the wiki links youtube.com/watch?v=K9lORz2_XSU, but the published Huberman episode is at watch?v=kD4rxsd-yn0; the wiki ID returns no matching video in search. The  wikilink likely points to a local transcript file, but the [
  - *fix:* Verify each row's [yt] link actually resolves to the named episode; if the IDs are internal corpus IDs, drop or correct the external youtube.com links so readers don't hit unavailable/wrong videos. At minimum spot-fix the Mackey, McGill, and other load-bearing rows against hubermanlab.com canonical 

### [[perception-predictive-processing-consciousness]] — A
- **[medium] overstatement** — Lines 17 and 37 state the perturbational complexity index (PCI / 'zap-and-zip') 'reliably separates conscious states (awake, dreaming, ketamine dissociation) from unconscious ones (deep non-REM sleep, anesthesia, brain death)' and is tagged [high] as 'validated across awake, sleep, anesthesia, vegetative/brain-death states.' The landmark PCI validation work (Casali et al. 2013; Casarotto et al. 20
  - *fix:* Remove 'brain death' from the validated list (lines 17 and 38) or downgrade it to an inference. Replace with the actually-validated category, e.g. 'vegetative/unresponsive-wakefulness and minimally-conscious states,' and keep [high] only for those tested conditions.

### [[psychiatry-clinical-disorders]] — B
- **[medium] factual_error** — Claim: 'OCD is one of the most debilitating illnesses overall (cited as ~#7 on global disability burden)... [high]'. The widely cited WHO/Global Burden of Disease figure is that OCD ranked among the top 10 most disabling illnesses (commonly cited as ~10th, and specifically among the top 10 causes of disability for ages 15-44 in developed economies) — not #7 overall. '#7 on global disability burden
  - *fix:* Change to 'historically ranked by WHO among the top 10 most disabling illnesses (often cited as ~10th, and within the top 10 causes of disability for ages 15-44 in developed economies)'. Drop the specific '#7' and 'overall' framing, or downgrade the tag to [medium] and attribute it to the creator's 

### [[relationships-social-behavior]] — A
- **[medium] overstatement** — Line 26: 'social connection is a robust predictor of longevity and morbidity — comparable in effect size to classic risk factors' tagged [high]. The directional mortality association (Holt-Lunstad meta-analyses) is well established, but the specific 'comparable in effect size to classic risk factors / smoking' equivalence is the part that has drawn methodological criticism (heterogeneous measures,
  - *fix:* Keep [high] for 'robust predictor of mortality/morbidity' but downgrade the effect-size-equivalence clause to [medium] and soften to 'effect sizes that some meta-analyses place on par with established risk factors, though the magnitude of that equivalence is debated.'

### [[sleep-circadian-rhythms]] — B
- **[medium] outdated** — Lines 13 and 26 describe NREM as 'stages 1-4, with 3-4 being slow-wave/deep sleep'. This is the obsolete Rechtschaffen & Kales nomenclature. Since the 2007 AASM scoring manual, NREM is staged N1-N3, with N3 being slow-wave (deep) sleep; old stages 3 and 4 were merged into N3. Presenting 'stages 1-4' as current is outdated and internally redundant (the page elsewhere on line 34 writes 'deep NREM (s
  - *fix:* Replace with the current convention: 'non-REM (stages N1-N3, with N3 being slow-wave/deep sleep)'. Note the old 4-stage system parenthetically if historical context is wanted.
- **[medium] miscredit** — Lines 17 and 44 attribute the ~24.2 h free-running human circadian period to Hattar ('Hattar's data frame the free-running human period at ~24.2 hours', tagged [high], cited 2XMb3MD6g6Q). The canonical measurement of the intrinsic human period at ~24.18 h is from Czeisler et al. 1999 (Science, forced-desynchrony protocol). Hattar may cite or discuss the figure on the podcast, but the finding is no
  - *fix:* Reattribute the figure to its source (Czeisler et al. 1999, Science) or phrase as 'as Hattar discusses, the intrinsic human period is ~24.2 h (Czeisler et al. 1999)'. Keep the podcast wikilink as the synthesis source, not the origin of the datum.
- **[medium] overstatement** — Line 38: 'No major psychiatric disorder has been found with normal sleep — sleep and mental health are tightly bidirectionally linked. [high] (Walker)'. The first clause is a Walker rhetorical aphorism, not an established epidemiological fact; sleep disturbance is common across psychiatric disorders but the absolute claim 'no major psychiatric disorder has normal sleep' is an overstatement present
  - *fix:* Downgrade the first clause to [medium] and frame as a Walker characterization: 'Walker notes that sleep disruption accompanies essentially every major psychiatric disorder'. Keep the bidirectional-link claim at [high].

### [[stress-cortisol-resilience]] — A
- **[high] factual_error** — Line 84 (Actionable protocols, Deliberate cold): "Reference doses cited: cold water ~104°F for ~20 min (shoulders down) for some protocols." 104°F equals 40°C, which is warm-to-hot bath/hot-tub temperature, NOT cold-water immersion. Cold-plunge protocols discussed by the cited sources (Soberg, Huberman) are on the order of ~50-60°F (~10-15°C). A reader following this literally would sit in warm wa
  - *fix:* Correct to a cold range, e.g. "cold water ~45-60°F (~7-15°C) for up to ~20 min (shoulders down); colder = shorter." If a specific figure like 104°F came from a transcript, it was almost certainly a transcription/unit error and should be removed.

## Broken / wrong citations flagged

- [[dopamine-reward-addiction]] — https://pmc.ncbi.nlm.nih.gov/articles/PMC12244148/
- [[metabolism-exercise-nutrition]] — https://pubmed.ncbi.nlm.nih.gov/24215592/
- [[mood-anxiety-depression]] — https://www.nejm.org/doi/full/10.1056/NEJMoa2032994
- [[mood-anxiety-depression]] — https://www.thelancet.com/journals/lanpsy/article/PIIS2215-0366(24)00133-0/fulltext
- [[pain-injury-physical-health]] — https://www.youtube.com/watch?v=K9lORz2_XSU
- [[sleep-circadian-rhythms]] — https://jcsm.aasm.org/doi/full/10.5664/jcsm.6462

## Verdict

Overall: **9 A / 8 B**, no C/D/F. 67 cited URLs verified as resolving-and-supporting; 6 flagged broken/wrong. The corpus is well-calibrated and honestly hedged; the deterministic extractor swept in a few off-topic episodes (flagged), and a handful of magnitude/date/nomenclature errors were caught and fixed. Low-severity items are recorded per section.
