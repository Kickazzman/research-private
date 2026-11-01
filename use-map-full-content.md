# Full-content use-map — every major item mapped to a use

**Coverage count (verified by grep on entry IDs, 2026-10-31):** TOTAL entries: **425** (234 original + 47 earlier-statements + 144 remaining-threads).
Per source program: JEV program: 36 (U-J 16 + B-J 11 + A-J 7 + R-J 2) · Medical passes
(pass 1 + pass 2): 66 (U-M 17 + B-M 9 + R-M 8 + R-P 20 + A-M 12) · Four fields
(pass 3): 39 (U-F 16 + B-F 5 + R-F 5 + A-F 13) · Theoretical math: 47 (U-T 8 +
B-T 9 + R-T 4 + A-T 26) · Framework / anchor / decoder: 23 (U-D 7 + B-D 3 +
R-D 3 + A-D 10) · Catalogue (perg-supplied 2026-10-30): 7 (U-CAT 3 + B-CAT 1 + R-CAT 1 + A-CAT 2) · Program state (research-gaps.md): 5 (R-S) · NO DIRECT USE
(spanning programs): 11 · Earlier statements (new section): 47 (E-EMG 10 +
E-SAT 5 + E-SLV 1 + E-JEV 3 + E-SRV 13 + E-MTH 7 + E-FRM 4 + E-REG 4) ·
Remaining research threads (new section): 132 (W 17 + CU 2 + H 8 + MS 8 +
CM 6 + V 3 + CB 4 + MA 4 + MI 2 + PD 7 + X 7 + AU 49 + BR 15) ·
2026-10-31 additions: 12 (U-T 2 + U-W 1 + R-T 2 + R-W 4 + A-T 2 + A-W 1). By use
class: USE NOW 126 (67 + 28 + 31) · BUILD NEXT 61 (38 + 2 + 15 + 6) · REFERENCE 141 (48 + 11 + 81 + 1) ·
AVOID 83 (70 + 3 + 10) · NO DIRECT USE 14 (11 + 3 + 0). Sum check: 126 + 61 + 141 + 83 + 14
= 425; and 36 + 66 + 39 + 47 + 23 + 7 + 5 + 11 + 47 + 132 + 12 = 425.
**Rule of this map:** no omission. An item with no genuine use appears under
NO DIRECT USE with its reason. An item that must not be imported appears under
AVOID with its reason. A claim that is unverified appears under AVOID as
VERIFY-FIRST. Use classes: USE NOW (verified, decision-ready) · BUILD NEXT
(design ready, needs an order or equipment) · REFERENCE (background/design
input) · AVOID · NO DIRECT USE.

**Standing guard (added 2026-10-30, from this map's own build history):**
no unilateral exclusions — every exclusion needs a stated reason and stays
visible in the map (the PD-thread exclusion was caught and reversed the same
session); coverage counts are recomputed by `use-map-regen-check.py` on every
edit and must PASS before the edit stands; the markdown map is the single
source of truth and `use-map-index.json` regenerates from it — never hand-edit
the index's rules without a map entry behind them.

---

**DOMAIN FINDER (added 2026-10-30; counts verified by grep; line numbers refer to this file as saved):** entry IDs read CLASS-PROGRAMnumber, where class U/B/R/A/N is the use class and program is the domain. The original section groups entries by use class; the later sections group by class subsections.
JEV program: U-J 16, B-J 11, A-J 7, R-J 2 (36; lines 42–152, 555–627, 1350–1386). Medical passes 1–2: U-M 17, B-M 9, R-M 8, R-P 20, A-M 12 (66; lines 160–290, 635–699, 892–1129, 1395–1477). Four fields, pass 3: U-F 16, B-F 5, R-F 5, A-F 13 (39; lines 300–417, 710–741, 1135–1190, 1485–1568). Theoretical math: U-T 8, B-T 9, R-T 4, A-T 26 (47; lines 425–485, 751–828, 1205–1236, 1578–1750). No direct use: N-T 11 (lines 1845–1920). Framework / anchor / decoder: U-D 7, B-D 3, R-D 3, A-D 10 (23; lines 495–537, 851–891, 1263–1293, 1773–1851). Catalogue (perg-supplied 2026-10-30): U-CAT 3, B-CAT 1, R-CAT 1, A-CAT 2 (7; lines 547–560, 893–898, 1349–1354, 1851–1859). Program state: R-S 5 (lines 1295–1347).
EARLIER STATEMENTS section (lines 1965–2680), in class subsections: E-EMG 10 emergence toolkit, E-SAT 5 SAT/solvers, E-SLV 1 solver, E-JEV 3 JEV, E-SRV 13 serving/seats, E-MTH 7 methods, E-FRM 4 framework, E-REG 4 registry (47 total).
REMAINING RESEARCH THREADS section (lines 2681–3504): **breeding, folded in 2026-10-30: U-BR 2, B-BR 2, R-BR 10, A-BR 1 (15; lines 3453–3495)**; wire: U-W 3, B-W 3, R-W 8, A-W 1 (15); cube: B-CU 1, R-CU 1 (2); harvest / Scientist OS: U-H 4, R-H 4 (8); model sweep: U-MS 3, B-MS 3, R-MS 2 (8); centered math: U-CM 1, B-CM 1, R-CM 2, A-CM 2 (6); voice: R-V 3 (3); crew benchmark: B-CB 1, R-CB 2, A-CB 1 (4); model architecture: R-MA 2 (2); media influence: R-MI 1, A-MI 1 (2); Proton/Dell: B-PD 6, R-PD 1 (7; PD subsection, lines 3233–3275); seven decisions: U-X 5, B-X 2 (7; lines 3283–3301); audit additions: U-AU 9, B-AU 2, R-AU 37 (48; lines 3307–3448).
2026-10-31 ADDITIONS section (appended at end): U-T 2, U-W 1, R-T 2, R-W 4, A-T 2, A-W 1 (12 total).

## USE NOW (verified, decision-ready)

### JEV program

### U-J01 — Lean escalation rule (null OR fast confidence < 0.8)
Source: jev-frontier-summary.md, jev-hammer-recalibration-summary.md. What it is:
the escalation policy that sits on the cost-error frontier on all observed rows.
Rule: escalate to the calculator on fast null OR fast confidence < 0.8; never on
hammer confidence, disagreement alone, or any threshold above 0.8. Lag cost 0.28,
orig+hard cost 0.25, floor-adjusted error 0.0028 / 0.0025.

### U-J02 — Hammer confidence never enters the rule, in any form
Source: jev-hammer-recalibration-summary.md. What it is: hammer expressed
confidence is constant 1.0 on all 129 answered saved rows; accuracy 73/129 = 0.566.
Rule: raw, recalibrated, or logprob-gated hammer confidence is excluded from
escalation. Mapping 1.0 → 0.566 changes no decision (fast 0.95–1.0 still wins).

### U-J03 — Null is a complexity sensor, lift 3.22×
Source: jev-null-sensor-summary.md. What it is: fast null rate by pinned complexity
tier — Tier 1 0/32, Tier 2 3/36, Tier 3 11/32. Rule: P(Tier 3 | null) = 11/14 = 0.786
vs P(Tier 3 | no null) = 21/86 = 0.244; intervals do not overlap. Use null as a
routing signal for complexity. Caveat attached: tier is a prior, not a deterministic
trigger (three Tier-3 functions drew 0/4); subtlety carries no signal (null 3/18
subtle vs 11/82 obvious, intervals overlap).

### U-J04 — Calculator failure floor 1/100, reachability 0.99
Source: jev-calculator-floor-summary.md. What it is: held-out measurement of the
escalation oracle's own failure rate. Rule: P(calculator fails) = 1/100 = 0.010,
Wilson (0.0018, 0.0545); reachability = 1 − P = 0.990. No escalation policy using
this calculator beats ~1% error (up to ~5.5% at the upper bound) on this item class.
The single failure (cf-b30, base36_to_int) was a coverage gap producing "both pass"
ambiguity, not a wrong test — so improve suite coverage, not verdict logic, and give
the decider a tie-break / further-escalation rule for both-pass.

### U-J05 — Insurance price for the full rule: break-even r = 0.01
Source: jev-frontier-summary.md. What it is: the priced cost of escalating on
disagreement too. Rule: full costs 22 extra runs/100 (lag) or 19/80 (orig+hard) over
lean for zero observed gain; full beats lean in expectation iff the future
fast-wrong-among-disagreements rate r > 0.01. r is unmeasured (0/41 observed,
rule-of-three upper ≈ 0.073). The rows price both sides; they do not pick one —
the pick is perg's design call.

### U-J06 — Merge must be a semilattice WITH ⊤ = "disagree"
Source: research-gaps.md (JEV merge constraint). What it is: the merge design
constraint for any future decider. Rule: ⊔ must represent disagreement as a countable
state; max-by-confidence alone always produces an answer, reads contention as zero by
construction, and hides disagreement — the same failure mode as the old JSON-only
toolshape rule. With ⊤, |B/∼| = P(join = ⊤) is a genuine measurement.

### U-J07 — Distillation-vs-melding guardrail
Source: research-gaps.md. What it is: the rule for future seat upgrades. Rule: never
distill two seats meant to disagree from the same teacher — distillation drives
agreement and collapses the disagreement signal into a false positive (⊤ never fires
because seats became correlated, not because contention vanished). Routine math:
distil. Research math: diversify, then meld. Track (disagreement rate, decider edge
over best seat) jointly; collapse signature is disagreement → 0 WITH edge → 0.
Keep a diversity-anchor seat deliberately un-distilled.

### U-J08 — No lag trigger on the fast+hammer pair (negative result, used now)
Source: jev-lag-run-summary.md. What it is: the lag-as-sensor test, closed negative.
Rule: do not build a lag/convergence trigger on this pair — hammer duration median
0.07 s (range 0.05–0.12 s, 0/100 over 1 s), so the gap is just −fast duration;
change vs no-change gap medians −9.53 s vs −9.74 s, tertiles non-monotone
0.529 / 0.294 / 0.471. P(change) itself is 64/100 overall, 22/51 among both-answered
— not 0.03 — so escalation budget, not rarity, is the binding constraint.

### U-J09 — Duration is post-hoc, not a pre-decision sensor
Source: jev-lag-run-summary.md, jev-null-sensor-summary.md, jev-frontier-summary.md
(§6). What it is: answered ~10 s / ~4.5 s vs empty ~37 s / ~36 s, but null rows take
two attempts, so duration is partly caused by the null it would predict. Rule: no
duration-priced policy may be built from these runners; a duration sensor needs
first-attempt latency logging (a runner change, listed under BUILD NEXT).

### U-J10 — Pure-threshold escalation is never a frontier policy
Source: jev-frontier-summary.md. What it is: confidence-only policies (nulls not
escalated) leave error at the null rate at every threshold, and at t = 1.01 on lag
error RISES to 0.2872, worse than fast-alone (0.2800), from floor exposure alone.
Rule: every escalation policy must include null fallback; a threshold that fires on
correct answers is pure cost (ns2-a35, conf 0.9 CORRECT, escalated at t = 0.95 for
zero gain, floor point 0.0114 → 0.0115).

### U-J11 — Confident fast error is invisible to null/confidence sensors
Source: jev-null-sensor-summary.md (§7), jev-frontier-summary.md (§5). What it is:
ns2-a23 (capitalize_words, Tier 2, subtle) — fast "pass" @ 1.0, ground truth fail
(str.title() turns "don't" into "Don'T"). Rule: below cost 1.00, the ns2 error floor
is 0.01, not 0; only escalate-all catches it, at cost 1.00, trading one 0.01 error
source (confident fast error) for another (calculator failure) inside floor
uncertainty. This row is also the existence proof that fast CAN err when answering
(previous populations 0/60 wrong-when-answered; ns2 1/86) — the precondition for any
future correction-path test.

### U-J12 — Original JEV contract test verdict +1 stands
Source: research-gaps.md (JEV contract test). What it is: the standing decider
verdict. Numbers: top bucket 35/35 = 100%, Wilson (0.901, 1.0); escalation gain
+12.5 pp (87.5% → 100%); neither kill condition fired (top bucket < 85% or gain
< 10 pp). Caveats travelling with it: ceiling confound (only 12.5 pp headroom);
error-correction path untested (fast never wrong when answered in that population);
monotonicity untested (quicklook never below 0.95 there).

### U-J13 — Hard-run lesson: fallback is load-bearing, silence tracks complexity
Source: research-gaps.md (hard run). What it is: the harder JEV population. Numbers:
fast-alone 25/40 = 0.625, fast-when-answered 25/25 = 1.000, empties 15/40 = 0.375, all
errors non-answers; final 40/40 under both rules (full +37.5 pp at 52.5% escalation,
leaner +37.5 pp at 37.5%). Rule: design fallback as a first-class path (37.5% of
items), not an exception; silence concentrates on the hardest functions
(weighted_quantile 4/4 empty).

### U-J14 — Decompose disagreement counts by answered-pool before interpreting
Source: research-gaps.md (hard-run disambiguation). What it is: the 13 → 6
disagreement-count drop was nulls shrinking the both-answered pool, not convergence:
disagreement among both-answered 46.4% → 42.9% (essentially unchanged); pool shrank
from both ends (fast abstains more + hammer contract failures 8 → 15). Rule: never
report a disagreement-count change without the both-answered denominator.

### U-J15 — Retry-ok flag discipline
Source: jev-lag-run-summary.md (§7). What it is: the lag runner kept the first
attempt's ok flag after a successful retry, misflagging 11 rows. Rule: contract_ok
is recomputed as (decision is not None); decisions, confidences, timings and change
flags were unaffected. Apply to every future runner.

### U-J16 — Test-execution default for real-diff judging
Source: real-diff-coder-report.md; rederivation-rule-report.md;
interface-contract-route-report.md. What it is: the standing default
for coder-seat judging of real diffs. Rule: run the tests on every
item (escalate-all). The calculator matched frozen ground truth 56/56
in the transfer run and 28/28 in both re-derivation runs, while the
judge's confident errors were invisible to the lean triggers. A second
route replaces this default only if it proves it can CONFIRM as well as
veto, pre-registered on the same frozen 28 (see R-J01). Cost is priced,
not hidden: test execution on every item is the routine price of
judging real work.

### Medical passes (pass 1 + pass 2)

### U-M01 — Gated closed-loop policy with tiers, deadband, refractory, sham
Source: pass 1 §§2–3 + synthesis Tier 1; pass 2 transfer 1 (SURVIVE with repair).
What it is: the closed-loop architecture proved in humans (RNS 2013, adaptive DBS
FDA Feb 2025, SetPoint Jul 2025). Rule: (a) detector with explicit thresholds,
deadband and refractory period (RNS line-length/area/bandpass detectors, not raw
classifier output); (b) policy with ≥ 3 tiers — monitor, low-cost actuation,
escalation — mirroring beta-gated DBS (stimulate only when the biomarker is
present); (c) a sham tier in every trial (actuation hardware present, no actuation
delivered), because the RECOVER depression trial shows sham improvement can erase
a real effect. Pass-2 repair attached: two timescales, an ECAP analogue (per-action
response), sham as blinded evaluation, plotted cost-error frontier.

### U-M02 — Difference imaging first, explicit prior, uncertainty map, resolution limit
Source: pass 1 §4 + synthesis Tier 1; pass 2 transfer 2 (SURVIVE, strongest transfer).
What it is: the EIT/ESI discipline for shape reconstruction. Rule, in order: (1)
reconstruct CHANGES from a baseline (cancels unknown absolute conductivity of wood,
bark, soil contact); (2) choose the prior deliberately and name it (Tikhonov smooth
vs TV/Mumford–Shah blocky vs learned only with paired ground truth); (3) compute and
publish the Jacobian singular-value spectrum for your electrode geometry and state,
in cm, what you cannot see; (4) report uncertainty as a map, not a single image.
2025 EIT consensus template: standardise the plane (4th–5th intercostal space),
never compare absolute EELI across subjects.

### U-M03 — Inverse-problem discipline: no algorithm repeals singular-value decay
Source: pass 1 §0 + §4. What it is: the Hadamard ill-posedness fact. Rule: the
Jacobian's singular values decay roughly exponentially with spatial frequency, so
deep/small features are exponentially suppressed; every method is
min ||F(σ)−y||² + α·R(σ), and the regulariser chooses which lie to tell about the
unmeasured frequencies. Tikhonov over-smooths; TV/Mumford–Shah preserves edges
(arXiv:2110.15697). Any reconstruction sharper than the data supports is the prior,
not the tissue.

### U-M04 — Phantom-rotor rule for phase-based detectors
Source: pass 1 §6 (PLOS Comput Biol 2026). What it is: conventional phase mapping
both invents rotations that do not exist and misses rotations that do, near
conduction block and fibrosis. Rule: any phase-based "driver" detector must be
validated against simulated ground truth AND a conduction-block null, or it will
hallucinate drivers — in plant data as in cardiac data.

### U-M05 — Foundation-model decoding with drift management, frozen-encoder-first
Source: pass 1 §5 + synthesis Tier 1; pass 2 transfer 3 (SURVIVE with major repair).
What it is: the ECG/BCI lesson (ECGFounder 10,771,552 ECGs, AUROC > 0.95 for 80
diagnoses internal; Harrell 3,800 h at home without daily recalibration). Rule:
pretrain self-supervised on the largest unlabeled corpus, fine-tune few-shot,
pair signals with text (grower notes, as ECG-CLIP pairs ECGs with clinician notes,
~91% less labelled data); frozen-encoder-first; measure measurement-drift vs
generator-drift separately; ban gradient test-time adaptation as default
(NeuroAdapt-Bench 2026: gradient TTA often degrades, optimisation-free T3A most
stable); report hours-at-home / cross-site / cross-season external validation, not
held-out windows from the same plants.

### U-M06 — Ternary bands: the conditional gate (REPAIR or DROP per deployment)
Source: pass 2 transfer 4; pass 1 §1.3 + §8.2. What it is: the honest balanced ternary.
Rule: keep ternary ONLY if all hold — bands are relative (not absolute mV); ternary
is justified against continuous AND quaternary alternatives; hysteresis is timed
(different enter/leave thresholds, preventing chatter); coupling is explicit
(a depolarised channel among hyperpolarised neighbours ≠ tissue-wide depolarisation
— the AML niche lesson, tumour imposing −11.8 mV on stroma); and the ±10% edge-jitter
test passes (perturb the value, recompute, check band stability). Biology uses
continuous voltage with thresholded, history-dependent transitions — ternary is the
decoder's alphabet, not nature's code.

### U-M07 — Router ablation test
Source: pass 2 transfer 5 (misuse: routing as relabelling). What it is: the
falsification test for any router. Rule: remove the router; if outcomes are
unchanged, it was decoration, not routing. Apply to every routing claim before it
is reported as a result.

### U-M08 — Multiplexed routing by function + latency + reversibility + false-positive cost
Source: pass 2 transfer 5 (REPAIR). What it is: the repaired routing rule. Rule:
confidence × cost alone misroutes; the routing table must carry, per channel,
latency, reversibility, and channel-specific false-positive cost, on top of
anatomical/functional routing (which fascicle / tissue compartment / plant organ
does this channel report on, and what actuation does it gate?). Evidence for the
repair: synaptic (< 50 ms) vs endocrine (slow broadcast) vs paracrine signalling,
affinity matching (pM hormones vs mM transmitters), neuropod hybrid cells.

### U-M09 — The decoder needs an equivalent of the language-model prior
Source: pass 1 §2.2. What it is: the BCI lesson. Rule: 125,000-word vocabulary at
99% (Harrell, controlled) is not raw neural SNR, it is neural evidence × linguistic
prior. A plant decoder needs the equivalent prior — species, phenology, circadian
state — stated explicitly, or it will mistake prior-free noise for signal.

### U-M10 — Sham tier in every trial (stated separately because it is also a trial rule)
Source: pass 1 §3.1 (RECOVER), §3.2. What it is: the electroceutical trial lesson.
Rule: any closed-loop plant claim of "actuation improved outcome" without a
sham-actuation control has proved nothing. See also U-M01(c).

### U-M11 — "Do not act" gate for high-cost actions
Source: pass 1 §2.1 (Stanford mental password gate, > 98%) + synthesis Tier 1.
What it is: the password-gate pattern generalised. Rule: a high-cost action
(decoding inner speech; tier-2 plant actuation) requires a separate, high-confidence
gate — for plants, a second modality (soil moisture, imaging) confirming the
electrical signature before tier-2 actuation.

### U-M12 — No single-driver stories in coupled excitable tissue
Source: pass 1 §6 + "What NOT to transfer". What it is: the rotor-trial sobriety.
Numbers: persistent-AF ablation overall ~50% successful (Europace 2025); REAFFIRM
randomised follow-up sobering after CONFIRM; dual-atria rotor study calls for
larger studies. Rule: do not report "found the driver" / "ablate the driver" for
plant tissue without the phantom-rotor validation (U-M04) and a multi-driver null.

### U-M13 — Report hours, hectares, seasons — not just accuracy
Source: pass 1 "What NOT to transfer" + §5.2. What it is: the lab-vs-field reporting
rule. Rule: Harrell's advance was removing the lab (3,800 h at home); ECGFounder's
internal-vs-external AUROC gap is the norm; Vivent/Electric Plant claims await
independent trials. Every plant accuracy claim carries its population, time window,
and shuffled-label baseline (see also credibility guard, U-F07 family).

### U-M14 — Peer-reviewed plant ML baseline is 62–85%, not 97%
Source: pass 3 §3a (plant ML) + pass 1 §8.2. What it is: the honest prior for
scepticism. Numbers: Biosensors 2025 single Tradescantia, ResNet18 lamp 85.4%
(n = 2767), emotion 73% (n = 1619), authors call preliminary; Biomimetics 2025
Random Forest 62.7% (AUC 0.67), confounds unisolated. Rule: use 62–85% as the prior;
the 97% preprint (CONTRAST, arXiv Jun 2025, ResNet50) is NOT weighted equally.

### U-M15 — Triage framing for plant alerts
Source: pass 1 §5.1 (Imperial ECG AI). What it is: the honest framing for a
screening signal. Numbers: routine 10-s ECG, < 2 s, heart failure up to 81%, valve
disease up to 90% (67,000-patient US trial); AUROC 0.86–0.90 for reduced pumping
function. Rule: frame plant alerts as triage for confirmatory inspection, not as
diagnosis — the framing that survives external validation.

### U-M16 — Non-inferiority is a real advance; do not inflate it
Source: pass 1 §6.2 (PFA). What it is: the claim discipline from pulsed-field
ablation. Numbers: ADVENT 73.3% vs 71.3% thermal, non-inferior; PULSED AF 0.7%
adverse events; FDA PulseSelect Dec 2023, FARAPULSE Jan 2024, VARIPULSE Nov 2024,
Volt Dec 2025 (392 pts). Rule: safety + speed at equal efficacy is the advance;
never report a non-inferior result as a superiority result.

### U-M17 — EIT consensus as a template for a plant-electrode standard
Source: pass 1 §4.1. What it is: the 2025 international EIT consensus (87
recommendations, 12 countries). Rule: standardise the electrode plane, warn that
absolute values are not comparable across subjects or positions, and frame the tool
as a titration/recruitment instrument (PEEP 18 → 8 cmH₂O case report) — the template
for a plant-electrode standard: standardise placement, never compare absolute
voltages across plants/sites.

### Four fields (pass 3)

### U-F01 — Router IS Bayesian decision theory: thresholds are loss-equality points
Source: pass 3 §2b. What it is: the router formalism. Rule: posterior over states,
utility matrix over actions (act / wait / escalate / ask another channel),
value-of-information for each additional channel or second of recording; escalate
only when value-of-information > cost; a threshold is the point where expected loss
from acting equals expected loss from waiting plus the cost of the next observation.
Thresholds stop being magic numbers once stated this way.

### U-F02 — Calibration before router cleverness
Source: pass 3 §2b (2026 self-escalation preprint moral). What it is: the router
priority rule. Rule: a well-calibrated 70% that knows it is 70% routes better than
an overconfident 95% that is wrong 30% of the time; regret is controlled by posterior
calibration, not by router cleverness. (Preprint, Aug 2026, unreviewed — cited for
the formalism's moral, consistent with JEV's own hammer-degeneracy finding.)

### U-F03 — Retraction is mandatory: ASP defaults + Dung audit
Source: pass 3 §2a–2b. What it is: the nonmonotonic reasoning transfer. Rule: a plant
interpretation MUST be retractable (early "stress" withdrawn when calibration, a
control plant, or a saturation flag arrives). Pattern: ASP-style defaults ("normally
this waveform is drift, unless a spike train follows"), named exceptions, semantics
that recomputes the justified set; Dung AF = (Args, Att) graph as the audit (which
interpretation attacked which, which survived). Detectable tell of the misuse:
a system with no recorded instance of changing its mind.

### U-F04 — Independent verifier per claim type
Source: pass 3 §2b. What it is: the proposer–verifier architecture rule. Rule: SMT
for arithmetic constraints on the signal (amplitude within sensor range, slope
bounded by physics); ASP for defeasible interpretation; Bayesian updating for graded
belief. Using one engine for all three is the field's classic error. And the verifier
must be independent of the proposer — a solver fed a formalisation produced by the
same LLM whose output it checks is theatre (solver-as-oracle).

### U-F05 — Blueprint-first validation plan
Source: pass 3 §1b (sphere-packing workflow). What it is: the validation-plan rule.
Rule: write down in advance which decoder claims are PROVED (e.g. "no output outside
[−V, +V] can reach the actuator"), which are STATISTICALLY BOUNDED (e.g.
"false-escalation rate < 1% on held-out days"), and which are MERELY OBSERVED.
Most bio-signal projects fail by leaving these three categories unlabeled.

### U-F06 — CAS-style exactness: symbolic derivation, late numeric evaluation
Source: pass 3 §1a. What it is: the derivation rule. Rule: keep derived features
(ratios, phase, spectral peaks) symbolic as long as possible and evaluate numerically
only at the end, with a stated precision. A CAS stores √2 as a symbol/minimal
polynomial + isolating interval, not as 2.8284271247461903 — never confuse the three
levels: exact symbolic vs arbitrary-precision numerics (mpmath-style, still rational
at any fixed precision) vs fixed-precision floats (dyadic rationals with rounding).

### U-F07 — PBPK credibility framing for the whole system
Source: pass 3 §3b. What it is: the credibility template (M15 framework, risk-based
not binary). Rule: state context of use ("detect stress state X in species Y under
conditions Z"), model influence (does a wrong output water, prune, or merely log?),
and totality of evidence (held-out days, held-out plants, held-out sites, control
plants, shuffled-label baselines). The shuffled-label control is non-negotiable: a
decoder that beats chance on shuffled labels is fitting the recording session, not
the plant.

### U-F08 — Identifiability check: fit ≠ identifiable
Source: pass 3 §3a (2025 six-model study). What it is: the model-check rule. Rule:
a model can fit well and still have parameters not identifiable from the observed
trajectory — different parameter sets, same curve, different forecast. Report the
identifiability analysis with every fit, or the forecast is ungrounded.

### U-F09 — UDE pattern: mechanistic prior + neural residual + reported UQ
Source: pass 3 §3a (Phil. Trans. R. Soc. A 2025, SEIR example). What it is: the hybrid
architecture rule. Rule: the ODE is the prior, the network is the correction, the
uncertainty is reported — not the other way round. Applies directly to the HH-backbone
decoder (BUILD NEXT, B-F01).

### U-F10 — MLIP discipline rules for the decoder
Source: pass 3 §4b. What it is: chemistry's best practice as decoder rules. Rule:
(i) enforce physics in the architecture (equivariance in MLIPs; for the reader:
invariance under electrode gain/offset, causality in time, boundedness of voltage);
(ii) train on the highest-fidelity data affordable and STATE THE DOMAIN; (iii) expect
out-of-domain error to grow with distance from training data (Focassio 2025, peer-
reviewed: universal MLIPs show significant out-of-box surface-energy shortcomings,
errors correlated with out-of-domain distance) and therefore MEASURE distance from
training data at inference time — a novelty/out-of-domain score feeding the router's
escalation, not a hidden failure.

### U-F11 — Representation-sensitivity testing
Source: pass 3 §4a–4b (ChemRxiv Dec 2024). What it is: the tokenisation warning.
Numbers: only > 70% agreement across three independent SMILES derivation methods
for the same transition-metal complexes. Rule: if two reasonable tokenisations of
the same trace give different decoder outputs, the decoder is fitting the
tokenisation, not the plant. Test it; each featurisation step (waveform →
spectrogram → embedding) discards information (phase, absolute amplitude, slow
drift) and the choice of what to discard is a modelling decision with consequences.

### U-F12 — Reconstruction reports the SET of consistent states, not one shape
Source: pass 3 §3b (compartmental thinking) + EIT ill-posedness. What it is: the
shape-reporting rule. Rule: many internal states can produce the same boundary
trace (identifiability problem, same as SEIR/PBPK inversion). Report the set of
states consistent with the data, with regularisation stated — not a single
"reconstructed shape" presented as fact.

### U-F13 — Clinical tiering with costed thresholds + alert-fatigue budget
Source: pass 3 §3a (clinical decision systems). What it is: the escalation-tier rule.
Rule: tiers calibrated to action cost (log < notify < intervene < actuate
irreversibly), confidence MARGIN — not just top score — as the routing variable,
and a budget on how often the top tier may fire. A router that escalates everything
is a router that will be ignored; that is a clinical fact before a design preference.

### U-F14 — Substrate-appropriate modelling (the real rule, not the slogan)
Source: pass 3 §3c, §4c. What it is: medicine's and chemistry's actual rule. Rule:
model continuous where the substrate is continuous (concentrations, voltages,
positions, energy landscapes) and discrete where it is discrete (genomic bases,
variants, molecule counts, stoichiometries, proof terms, argument statuses). Adopt
that rule; do not adopt "continuous first" or "discrete first" as a slogan.

### U-F15 — Continued-fraction certificate for rational reporting
Source: pass 3 §1b. What it is: the narrow, genuine use of convergents. Rule: if a
frequency ratio, phase, or threshold must be reported as a rational with a
denominator budget (clock divider, sample-rate conversion, quantised control step),
the convergent at that denominator is the optimal choice, and the bound
1/(q_n q_{n+1}) is a genuine certificate FOR THAT RATIONAL APPROXIMATION — it
certifies the approximation, not the underlying signal.

### U-F16 — Credible interval as resolution certificate
Source: pass 3 §2c + anchor verdict. What it is: the honest generalisation of the
convergent bracket. Rule: report a two-sided bracket with a width, widen it when
evidence is thin, escalate when the bracket straddles a decision boundary. That is
Bayesian credible intervals wearing the anchor's clothes — the version worth keeping.

### Theoretical math

### U-T01 — Schauder audit: check coefficient growth before trusting smooth reconstruction
Source: theoretical-math §4.4 (De Filippis–Mingione, Invent. Math. 2023 + Duke 2025
sharp). What it is: the Tier-1 regularity result. Rule: gradient Hölder continuity
holds IFF a specific growth condition on the ellipticity ratio holds, and the rate
is optimal. Living tissue IS nonuniformly elliptic (conductivity varies by orders
of magnitude). Check the condition on your measured coefficient field; beyond the
sharp threshold the true solution may be irregular and a smooth solver's smooth
answer is an artefact of the solver, not the physics.

### U-T02 — Sifting is part of the claim
Source: theoretical-math §1.5 (Kelley–Meka FOCS 2023, exponent 1/12; Bloom–Sisask
1/9, Ess. Number Theory 2023). What it is: the Tier-1 sifting lesson. Rule: do not
report a pattern found after sifting as if it were in the raw data — the sifting
step (remove points participating in too many near-progressions until the set is
well-behaved, then run the periodicity detector) is part of the claim, including what
was removed. Transfer caution: sifting deletes non-linear/chirped/amplitude-modulated
signal too — a Bohr set is the wrong neighbourhood there.

### U-T03 — Directional coverage cannot be compressed; overlap implies clustering
Source: theoretical-math §4.1 (Wang–Zahl, preprint trilogy; two companions
peer-reviewed Invent. Math. 2025, JAMS 2026; main volume paper preprint Oct 2026).
What it is: the Tier-1 Kakeya result (dim = 3 for Kakeya sets in ℝ³, up from Wolff's
5/2). Rule: a directional sampling scheme covering all directions is full-dimensional
in the tube-union sense whether you like it or not; tubes that do not cluster inside
convex sets are almost disjoint — so if your measurement tubes overlap heavily, they
must be clustering, and that clustering is itself information about the shape.

### U-T04 — Budget a log factor in linear decoder guarantees
Source: theoretical-math §4.2 (Cairo, arXiv:2502.06137, preprint). What it is: the
Mizohata–Takeuchi counterexample (log R loss, for every non-planar C² hypersurface).
Rule: you cannot bound the weighted energy of a reconstructed field by the worst line
integral of the weight — add a log factor to any decoder guarantee that assumes a
line-uniform bound, or change the norm. It kills a proof route and a uniform bound,
not decoding itself.

### U-T05 — Test composites directly; complexity does not add
Source: theoretical-math §3.4 (Brittenham–Hermiller, arXiv:2506.24088, preprint,
explicit diagrams). What it is: unknotting number is not additive — u(7₁) = 3,
u(mirror) = 3, but u(connected sum) ≤ 5 < 6. Rule: any "total complexity = sum of
parts" score in a router or decoder needs a non-additivity audit; components can
cancel like a knot and its mirror. A router escalating on summed complexity will
escalate every composite signal, even when the composite is simpler than its parts.

### U-T06 — Molecular-chaos gate for PDE/field controllers
Source: theoretical-math §4.3 (Deng–Hani–Ma, arXiv:2408.07818 + arXiv:2503.01800,
preprints). What it is: the Newton → Boltzmann → fluid chain, rigorous for dilute
gases on a torus in the Boltzmann–Grad limit. Rule: a fluid/field controller for
tissue is justified only under weak, brief, memoryless interactions (molecular
chaos); living tissue has memory, adaptation, and long-range coupling — the opposite
of the theorem's hypotheses. Check the hypotheses before importing the controller.

### U-T07 — Renormalise rough products, or discretisation converges to the wrong limit
Source: theoretical-math §4.6 (Linares–Otto–Tempelmayr–Tsatsoulis, Invent. Math.
2024, peer-reviewed). What it is: the diagram-free regularity-structures method for
singular SPDEs. Rule: if your equation contains a product of rough signals (power-law
noise, rough measurement driving a controller), renormalise (subtract the diverging
counterterm) or the numerical solution converges to the wrong limit or not at all.
Conversely, do not renormalise a smooth-signal decoder — the correction will subtract
a real signal.

### U-T08 — Conditional mathematics: quote the theorem WITH its hypotheses
Source: theoretical-math synthesis. What it is: the single most transferable lesson
of the 2023–26 centre of gravity. Rule: regularity IF a sharp growth condition holds;
balance UP TO (log N)^{1/4}; uniformity FOR badly approximable phases and ABOVE a
window floor; blowup WITH boundary; derivation IN the dilute-gas limit. A theorem
quoted without its hypotheses is not a theorem, it is a slogan — and that misuse
signature recurs in every entry of the theoretical report.

### Framework / anchor / decoder

### U-D01 — Reformulated anchor discipline (the version that survives)
Source: pass 3 synthesis (verdict: heuristic/discipline, NOT foundation). What it is:
the final formulation after contact with all four fields. Rule: keep a continuous
latent with a stated interval and a stated approximation budget; derive bands and
decisions from it by an explicit, costed rule (Bayesian expected utility with value
of information); keep the discrete events the substrate actually has (spikes, gates,
counts, tiers) as first-class objects, not artefacts to be dissolved; never let a
certificate (Lean, SMT, "verified", a confidence score) conceal the interval, the
domain, or the rejected alternative that produced it.

### U-D02 — Trajectory method
Source: research-gaps.md / MEMORY (perg 2026-10-29). What it is: the working method.
Rule: pre-register the reference line, measure how far each result bends off it,
project the correction, re-measure; never assume back on course.

### U-D03 — Precision-then-shift
Source: research-gaps.md / MEMORY (perg 2026-10-29). What it is: the cost method.
Rule: second measurements add precision first, then the cost is removed by shifting
(log space generalises bitshift: exponentials become lines, projection becomes
addition); shift AFTER deviation is measured, never before, or the deviation is erased.

### U-D04 — Relation-as-math
Source: research-gaps.md / MEMORY (perg 2026-10-29). What it is: the extraction rule.
Rule: once a relation is extracted and audited, it replaces the collective that found
it (model proposes, relation computes). Proven on the grid in the PS5 appendix-H
relation scanner (census P10240, 21/21 byte-exact from seed + +24 rule).

### U-D05 — Ternary verdicts: +1 / 0 / −1, void never collapses into refutation
Source: research-gaps.md / MEMORY (perg 2026-10-29). What it is: the verdict discipline.
Rule: confirmed (+1), undecided-void (0), refuted (−1); a NO SIGNAL / NOT PROVEN / void
run is not a disproof. Verdict levels are labels, not quantities; strength is
association count; conflict is its own flag, not zero.

### U-D06 — Wall-as-quantile framing
Source: research-gaps.md (SAT wall). What it is: the threshold discipline. Rule: the
SAT "wall" is where P(T(n) ≤ cap) crosses the majority threshold — 30 s cap → first
majority 119, 60 s cap → 126 — never "the" wall without the cap attached; implied
base b ≈ 1.10–1.13/var (2^{1/7} ≈ 1.104 for seven vars per doubling; the framework's
2^{7/6} ≈ 2.24 expression was wrong and is corrected here). Threshold crossings must
be bracketed, not extrapolated; exponential rates extrapolate, S-curve thresholds do
not.

### U-D07 — Category-translation caveat: no ⊔ defined on the fleet yet
Source: research-gaps.md (category-theory translation, corrected). What it is: the
honesty constraint on the melding mathematics. Rule: melding = colimit, duplexing =
pullback, disagreement quotient = coequalizer are real abstract mappings, but the
fleet has no defined merge operation ⊔ (router routes, blackboard stores JSON; neither
merges model states) — so "test the three laws" is a promissory note until ⊔ is pinned
to an artifact. Resource contention ≠ consistency contention (fleet contention was
GPU bandwidth fair-slicing, fixed by router serialization; gluing failure is a
different object). The n ≈ 119 SAT wall is not a melding wall (plain DPLL, no models).

### Catalogue (perg-supplied 2026-10-30)

### U-CAT01 — Anchor test: >=2 independent characterizations
Source: perg-supplied catalogue VII.1 (2026-10-30), unsourced formulation adopted as TEST, not theorem. What it is: the test a claimed anchor must pass. Rule: list the independent characterizations {P_i} of the anchor; each must uniquely determine it; fewer than 2 = a claim, not an anchor; disagreement between characterizations = H^1 signal, not noise to average away. Apply to the irrational anchor before any other anchor claim.

### U-CAT03 — Four-cell seat-pair table
Source: perg-supplied catalogue I.2. What it is: the full 2×2 table behind two accuracy numbers (A, B = seat-correct events). Rule: for every seat pair report p11 = P(A∩B), p10 = P(A) − p11, p01 = P(B) − p11, p00 = 1 − P(A∪B); p00 is the target, p10 + p01 is the signal, p11 is the correlation. Never report two accuracies without the table.

### U-CAT04 — Search-vs-identifiability triage before spending runs
Source: perg-supplied catalogue III.3 + X diagnostic D1. What it is: the triage between breakable and unbreakable. Rule: unique solution given the constraints but hard to find = search barrier, breakable with proposer/verifier/credit; multiple solutions consistent with the data = identifiability barrier, unbreakable by compute — stop, do not spend runs. The uniqueness check precedes every compute spend.

Geometric form (hypothesis, adopted 2026-10-30 from the perg-supplied isomorphism document — an other-conversation synthesis; its threads, e.g. Zodiac / pilot contamination / LDPC, are unverified in this program): barrier type = dim of the fiber Φ⁻¹(o) of the observation map Φ: X → O. Search barrier = 0-dimensional fiber (a point, expensive to compute); identifiability barrier = positive-dimensional fiber (a set, undecidable which); fold = fiber dimension jumps (rank DΦ drops); H¹ ≠ 0 = local sections do not glue (the fiber is a nontrivial torsor). This formalization is NOT a measurement. Measurement is PREMATURE: the both-wrong set is unmeasured (all-zero slices so far are consistent with true rates up to ~17–28%), and no intrinsic-dimension estimator exists in the program — an estimator must be built and verified before any fiber-dimension claim is made. The triage rule above stands unchanged.

---

## BUILD NEXT (design ready, needs an order or equipment)

### JEV program

### B-J01 — Decider build from lean + ⊤ merge + calculator oracle
Source: research-gaps.md (use plan; widget offered 2026-10-30, NOT tapped).
What it is: the biggest use that needs no equipment. Design: lean escalation rule
(U-J01) + semilattice merge with ⊤ (U-J06) + test-suite calculator oracle with the
1/100 floor (U-J04). Open decisions left as perg's call: the insurance decision
(pay 22–24% extra runs? break-even r = 0.01, U-J05) and the leaner-vs-disagreement
rule. NOT ordered — do not launch without perg's order; the five-item program scope
was measurement only.

### B-J02 — Fast+hammer run on ns2-like items to MEASURE r
Source: jev-hammer-recalibration-summary.md (§5), jev-frontier-summary.md. What it
is: the missing measurement that unblocks the insurance decision. Design: items
where fast actually errs when answering (ns2-a23 proves such items exist), WITH
hammer rows (ns2 has none), so the disagreement-conditional fast-wrong rate is
measured instead of bounded (currently 0/41, upper ≈ 0.073). Until this run exists,
r = 0.01 stays unmeasured and no hammer-side signal can be validated for the case
it would need to catch.

### B-J03 — A different second-opinion seat (varying confidence + fast-wrong disagreements)
Source: jev-hammer-recalibration-summary.md (§5). What it is: the precondition for
any recalibration. Design: a seat whose expressed confidence actually varies across
items (hammer's never does; its (a) channel is a constant 'pass' emitter) and whose
disagreements with fast include fast-wrong examples. Hammer as served is not that seat.

### B-J04 — Trained calibrator on FRESH items only
Source: jev-hammer-recalibration-summary.md (§5). What it is: the calibrator rule.
Design: fit only on fresh items — fitting to the saved rows would fit hammer's
determinism (probe replicates saved hammer 71/71), not its generalisation. Re-runs
of these items replicate exactly and add no training data.

### B-J05 — Larger fresh-item logprob probe for the decision_logprob hint
Source: jev-hammer-recalibration-summary.md (§3, §6). What it is: the underpowered
hint, honestly kept. Numbers: decision_logprob tertiles 0.500 / 0.542 / 0.696,
Spearman +0.245, low/high intervals overlap across 0.491–0.686, rho interval at
n = 71 includes 0; min_logprob points the other way (−0.135); confidence_logprob
flat (−0.015) — two independent confirmations that "1.0" carries no signal. Design:
a larger FRESH-item probe could resolve the hint either way; it must not be priced
until it separates. Logprob availability itself is build-specific (pinned
llama.cpp server exposes logprobs; another build may not).

### B-J06 — First-attempt latency logging (runner change)
Source: jev-frontier-summary.md (§6). What it is: the precondition for any
duration-priced policy. Design: log first-attempt latency separately from total
duration (which currently includes the retry); only then can "escalate if slow"
be tested as a pre-decision predictor rather than a post-hoc correlate.

### B-J07 — Score JEV (c) safe-to-merge against perg's replies
Source: jev-contract-test-report.md §7b (SCORED 2026-10-30 by assistant judgment — perg delegated, undecided on c01–c10). What it is: the close-out, SCORED and CLOSED. Ground-truth rule: MERGE iff the diff is behavior-preserving AND tests pass; DO_NOT_MERGE iff tests fail. Verdicts: c01 merge, c02 do_not_merge, c03 do_not_merge, c04 do_not_merge, c05 do_not_merge, c06 merge, c07 merge, c08 do_not_merge, c09 merge, c10 merge. Fast 9/9 correct when answered + 1 null (c07, escalated; slow resolved merge); hammer 5/10 contract-valid and correct + 5/10 null (bare words on the five FAIL items, leanings track test status — uninformative beyond the visible test result). Does not change the +1 verdict.

### B-J08 — Real-work JEV transfer run
Source: research-gaps.md. What it is: the transfer gap. Design: run the contract on
saved real diffs/merges instead of constructed small functions. All JEV materials to
date were constructed, not saved real work — transfer to real decisions is unproven
until this runs.

### B-J09 — Quicklook empties mechanism investigation
Source: research-gaps.md. What it is: the open mechanism question. Numbers: empties
12% in the original run, 37.5% on hard items, 28% on lag items, 14% on ns2; not
length-driven, survives one retry. Design: investigate the mechanism, or accept
empties as fallback triggers (the current working treatment).

### B-J10 — Correction-path test (adversarial items or weaker fast seat)
Source: research-gaps.md. What it is: the duplex's core claim, never exercised.
Design: escalation fixes wrong confident calls — needs still-harder/adversarial
items, a weaker fast seat, or investigation of whether JSON-only + temp-0 pushes
the seat to 0.95–1.0-or-silence. ns2-a23 is the first precondition row (a confident
error exists); the correction path itself (escalation fixing it) is still untested.

### B-J11 — Calibration curve below 0.95
Source: research-gaps.md; jev-null-sensor-summary.md (§7). What it is: the
unmeasured curve. Design: items eliciting sub-0.95 confidences at scale — ns2 gave
exactly one (ns2-a35, 0.9, CORRECT), a hint that the calibration range can open on
harder items, not a curve. The 0.8 rule has never fired on any JEV population.

### Medical passes

### B-M01 — Convergent-band decoder, first test when the plant rig exists
Source: parent-conversation derivation (2026-10-30) + pass 3 §13 + theoretical-math
page lab. What it is: the decoder design derived from the irrational anchor. Design:
take measured value x (normalised voltage ratio); its continued-fraction convergents
p_n/q_n approach x from alternating sides with |x − p_n/q_n| < 1/(q_n q_{n+1});
consecutive convergents bracket x; bracket width is the published resolution at that
step. Decision rule: commit to a band only when the whole bracket lies inside it;
escalate (measure more, wait, raise resolution) when the bracket straddles a band
boundary. Ternary bands become convergent intervals; the ±10% edge-jitter test gets
a mechanism. Status: DESIGN, not theorem, not measurement. Blocker: plant rig
equipment (PINNED 2026-10-29, perg's order; deferred, not dropped).

### B-M02 — Plant ternary test on rig traces
Source: research-gaps.md (plants PINNED). What it is: the test of U-M06 on real
signals. Design: relative bands, hysteresis timed, coupling explicit, ±10% jitter
test, against continuous and quaternary alternatives. Blocker: equipment (same pin).

### B-M03 — Optogenetic-style probing / system identification of the plant as a circuit
Source: pass 1 §7.3 (transferable idea) + synthesis Tier 3 item 7. What it is: the
most underused idea in commercial plant sensing, which currently only listens.
Design: stimulate a known input (light, electrical pulse, wound) at a known location,
read propagation (velocity, attenuation, λ, τ, threshold, refractory period), infer
coupling/health from the RESPONSE, not just the resting signal. Requires no genetic
modification. Blocker: rig + stimulation hardware.

### B-M04 — Primed-state detector (flytrap leaky integrator as design target)
Source: pass 1 §8.2. What it is: the early-warning target. Design: flytrap — 0 touches
= open, 1 touch = primed (subthreshold Ca²⁺ memory, ~20 s decay), 2 touches = close;
formally a leaky integrator with threshold, a finite-state machine built from ion
channels. Rule for plant decoders: look for primed states, not just triggered ones —
the primed state is where early intervention lives. Generalisation across crop
species is a hypothesis to test, not established (pass 1 could-not-verify item 6).

### B-M05 — Attractor-distance intervention experiments
Source: pass 1 synthesis Tier 3 item 6 (Levin setpoint/attractor framing as hypothesis).
What it is: the experiment the framing generates (not a product justification).
Design: define the healthy plant's electrical attractor (circadian, developmental,
stress-response manifold), measure distance from it, intervene to return the system
to the basin; test whether a brief electrical intervention shifts a plant's stress
trajectory persistently and whether the effect outlasts the stimulus (as in
planaria). Mammalian rewritability at will is NOT established — do not cite it.

### B-M06 — Organ-on-chip validation bench (TEER / MEA / MITO)
Source: pass 2 gap B8. What it is: the bench validation route before plants. Design:
organ-on-chip electrical readouts — transepithelial resistance (TEER), microelectrode
arrays (MEA), mitochondrial readouts (MITO) — as a controlled testbed for decoder
validation with ground truth that plant work lacks. Status: gap covered in pass 2,
bench not built.

### B-M07 — NV diamond sensing as a sensor candidate
Source: pass 2 gap B4. What it is: the quantum-sensing option. Numbers: rat
magnetocardiography ~20 pT (2024); Fraunhofer laser-threshold magnetometry 100%
contrast at < 400 fT/√Hz (2026, lab). Status: lab-stage, not a plant sensor; the
pointer-state NV paper is discounted as unverified (see AVOID). Design: evaluate as
a non-contact field sensor for plant/cardiac fields only after the lab numbers are
replicated in a plant-relevant geometry.

### B-M08 — Closed-loop plant loop with tiers + sham (build)
Source: pass 1 synthesis Tier 1 item 1. What it is: the deployable loop. Design:
detector (thresholds, deadband, refractory) → policy (monitor / low-cost actuation
such as irrigation/lighting adjustment / human escalation) → actuator, with a sham
tier in every trial. Architecture ready now (U-M01); actuation + sensing hardware
needs the rig.

### B-M09 — Foundation-model plant decoder
Source: pass 1 §5.2 + synthesis Tier 1 item 3. What it is: the decoder build.
Design: pretrain self-supervised on the largest unlabeled multi-species, multi-site
plant-signal corpus assemblable; fine-tune few-shot per stress; pair traces with
grower text (ECG-CLIP pattern); report cross-site/cross-season external validation.
Competitive reality attached: Vivent's and Electric Plant's data moats are the
product — outcome labels (yield, disease confirmation, water use) are expensive,
budget for them. Needs rig + corpus.

### Four fields

### B-F01 — HH-backbone decoder (HH ODE + UDE residual)
Source: pass 3 §3b (strongest transfer in the report). What it is: the mechanistic
decoder architecture. Design: encode C_m dV/dt = −Σ I_ion + I_ext with learnable
gating kinetics (I_ion = g_max·m^p·h^q·(V − E_rev), ds/dt = (s_∞ − s)/τ_s) as the
backbone; let ML learn only the residual (the UDE pattern, U-F09). Gives the decoder
a vocabulary — activation, inactivation, reversal potential, threshold — interpretable
when it fails, plus conservation/boundedness structure a pure classifier lacks.
Architecture ready now; test needs rig traces.

### B-F02 — Router specification in a decidable fragment
Source: theoretical-math §7.3 (Nation–Paolini) + pass 3 §2. What it is: the
language-design decision. Design: if routing rules are expressed in a lattice-like
logic (join = combine channels, meet = restrict), the UNIVERSAL fragment is
decidable — all universal routing rules checkable automatically. Allowing full
first-order quantification loses that. Restrict the router's specification language
to a decidable fragment and state the fragment with every "verified" claim.

### B-F03 — Elicit router utilities and priors (open design question)
Source: pass 3 could-not-verify. What it is: the question the fields do not answer.
Design: cost of false watering vs missed stress event; prior over plant states per
day, per species, per season. Bayesian decision theory (U-F01) disciplines the answer
but does not supply it. This elicitation is a build task in its own right, not a
parameter to guess.

### B-F04 — Multistationarity analysis of the router
Source: pass 3 §4b (CRN lesson). What it is: the router analysis. Design: a router
with multiple stable interpretations of the same input is multistationary; analyse
which inputs tip it from one stable reading to another, rather than averaging the
interpretations away. The graph (which channels can convert to which readings) and
the kinetics (how fast) are separate design choices.

### B-F05 — Dung argument-graph audit layer + tie-break policy
Source: pass 3 §2b. What it is: the conflict-audit build. Design: competing channel
decoders as arguments in a Dung graph; the audit records which interpretation
attacked which and which survived. Multiple extensions (multiple coherent justified
sets) are a feature for deliberation and a bug for actuation — an actuator needs one
action, so a tie-breaking policy (utility, cost, safety default) must sit on top of
the graph; the graph alone does not actuate.

### Theoretical math

### B-T01 — Komlós dependency-controlled rounding for the fractional router
Source: theoretical-math §1.1 (Bansal–Jiang, fall 2025 preprint, (log N)^{1/4}).
What it is: the Tier-1 routing algorithm. Design: solve the fractional (soft)
routing, then round with dependency control (coordinates made to behave as if
nearly independent — the 2025 ingredient that cut √(log N) to (log N)^{1/4}),
and audit the WORST attribute, not the average. Routing among channels is exactly
a signed-sum problem (attributes: confidence, cost, latency, modality, risk;
assign to act-now / escalate). Bansal: the method "hits a wall at a quarter root";
going further needs something very new. Preprint, not peer-reviewed — implement as
an algorithm with its bound stated, not as a proved constant.

### B-T02 — Badly-approximable sampling design
Source: theoretical-math §§1.2, 1.4 + irrational-anchor thread. What it is: the
Tier-1 sampling design. Design: pick the sampling/stimulation phase by its continued
fraction (bounded partial quotients — φ is the extreme), NOT by picking any
"irrational-looking" constant; use rough index sets (sieving out small prime factors)
to remove short-range arithmetic correlations. Hauke (arXiv:2506.01736, preprint)
proves Poissonian gaps for badly approximable α over rough n AND proves the statement
FALSE for Lebesgue-almost every α — genericity is the wrong regime. Misuse to avoid:
a schedule that looks random at coarse scale but has a hidden periodic hole at the
scale of the artefact you most need to avoid.

### B-T03 — Baier–Roy sampler condition (quadratic-irrational anchor, prime-indexed samples)
Source: theoretical-math §1.4 (arXiv:2512.02174, preprint). What it is: the anchor
theorem in its sharpest form. Design: if the anchor is a quadratic irrational
(bounded quotients — φ, √2, √3), prime-indexed samples visit any small interval at
the expected rate 2δY/log X even in a short window (X^{2/3+ε} ≤ Y ≤ X/2, δ above the
stated floor). If the anchor has unbounded quotients, the theorem does not apply —
expect windows where samples bunch. Do not shrink window or δ below the floor and
still expect uniformity.

### B-T04 — Aistleitner calibration curve for near-hits
Source: theoretical-math §1.3 (Compositio Math. 159 (2023), peer-reviewed;
Tan–Zhou preprint). What it is: the counting tool for approximations. Design: for a
typical target, the quantitative Duffin–Schaeffer/Khintchine count tells you how many
REDUCED approximations to expect by resolution Q — a calibration curve for "how many
near-hits are chance". On a fractal support (signal confined to a low-dimensional
manifold in electrode space), use the Tan–Zhou Fourier-decaying-measure form; the
Lebesgue form over-counts. Never apply the almost-everywhere bound to a specific
designed anchor or resonance — those live in the measure-zero exceptional set.

### B-T05 — Euler boundary-gradient monitor
Source: theoretical-math §4.5 (Chen–Hou, PNAS 122(27) 2025, peer-reviewed,
computer-assisted). What it is: the Tier-2 failure-mode monitor. Design: smooth,
finite-energy Euler data can blow up in finite time at a boundary stagnation point
(r = 1, z = 0, periodic cylinder). Controllers and monitors must detect gradient
growth at boundaries and degrade gracefully rather than assuming smoothness for all
time — and must not mistake a real singularity for a numerical instability. Scope
attached: Euler, with boundary — NOT Navier–Stokes, NOT whole-space.

### B-T06 — GMC null model for multiscale burst statistics (if verified)
Source: theoretical-math §§1.7, 5.1 (Harper et al. announced 2025; Lin–Qiu–Tan 2024
preprint, not peer-reviewed). What it is: the null model, not a decoder. Design: if
the signal is genuinely multiscale (bursts within bursts, power-law spectra), GMC —
μ(dx) = exp(γX(x) − γ²/2·E[X(x)²]) dx for log-correlated Gaussian X — gives a null
with heavy, scale-invariant fluctuations, better than white noise or single-scale
Gaussian for testing "is this burst structure significant?". Martingale diagnostic
attached: if the signal's multiscale mass is NOT a martingale (conditional expectation
drifts with scale), it is not GMC-like and a GMC null will mislead. Status: announced,
not established — do not use until the preprint record is verified.

### B-T07 — Sandwich coupling for fixed-degree control networks
Source: theoretical-math §2.3 (Behague–Ilkovič–Montgomery, arXiv Oct 2025, preprint).
What it is: the Tier-2 coupling reduction. Design: if channels/sensors have a fixed
degree/budget, analyse the system AS IF edges were independent (G(n,p)), then transfer
monotone properties back to the regular model (G(n,d)) through the sandwich, with the
slack stated and with high probability — not exactly. Non-monotone properties
("exactly one path", "no cycles") do not transfer.

### B-T08 — Spectral-gap diagnostic for control networks
Source: theoretical-math §3.7 (Anantharaman–Monk, arXiv:2502.12268, preprint).
What it is: the Tier-2 mixing null. Design: λ₁ is the mixing rate; a typical surface
has λ₁ ≥ 1/4 − ε (near-optimal). Practical use as a NULL: if your measured network
mixes slowly, it is atypical — look for a bottleneck (a tangled geodesic, in the
analogy) rather than assuming slow mixing is normal. Scope attached: closed hyperbolic
surfaces with Weil–Petersson measure — not directed, weighted, time-varying graphs.

### B-T09 — Shape-reconstruction methods from the geometry results
Source: theoretical-math §§3.1–3.3, 3.6. What it is: four methods/warnings in one
build queue. (a) Hat/spectre substitution test: if a reconstructed shape shows
self-similar grouping at multiple scales, test for a substitution rule rather than
assuming periodicity or randomness — but local patches can be locally consistent
everywhere yet globally non-periodic. (b) Moving-sofa reframing (Baek, arXiv Dec 2024,
preprint, submitted Annals): optimise over FEASIBLE MOTIONS, derive the shape as the
envelope; if the objective is concave in the motion, local optimality becomes global.
(c) Noperthedron negative transfer: do not assume a straight-line probe path exists
through a shape just because it works for cubes — convex shapes exist with no Rupert
hole in any orientation. (d) Dudeney matching diagrams: encode patch adjacency as a
graph and check matching conditions BEFORE geometric embedding — many reconstruction
failures are matching failures, not measurement failures.

### Framework / anchor / decoder

### B-D01 — Multidimensional shape with gluing constraints G
Source: parent-conversation proposal (2026-10-30, for perg's correction, not yet
corrected). What it is: the proposed definition. Design: let D index dimensions,
each with its own shape K_d from its own shaves; the multidimensional shape is the
joint object — tuples (x_d) across all K_d such that G(x) holds, where G is
cross-dimensional consistency (gluing constraints). Its skeleton is where the optimal
decision switches across dimensions; its emptiness is cross-dimensional inconsistency
(H¹ across dimensions, not within one cover). A single shape is the special case
|D| = 1. Instances already held: cost-error frontier as a 2D shape in (cost, error)
space with Pareto boundary as skeleton; SAT wall as a shape in (n, cap,
timeout-fraction) space; lag analysis as a shape in (gap, change, correctness) space.
New failure mode beyond single-shape blindness: GLUING BLINDNESS — each per-dimension
shape fine while joint structure stays invisible from every single dimension. Without
G there is a collection of shapes, not a multidimensional one. Dimensions are typed:
lenses (spectral, cache-line, page), seats (fast, hammer, third), domains (math, data,
crypto), axes (answer, confidence, latency, correctness, hardness, cost, error).

### B-D02 — Shaving construction for pointer/address data (linear vs nonlinear decision)
Source: research-gaps.md (shaving construction, assessed 2026-10-29). What it is: the
load-bearing pre-build decision. Design: half-space intersection / morphological
erosion / medial axis / eikonal wavefronts share the skeleton idea, not the shape —
half-space intersection always yields a convex set, while erosion can preserve
concavity (an eroded crescent remains a crescent). Address patterns have holes/gaps/
concavities, so linear shaves recover only the convex shadow. The claimed three-way
equivalence is too strong; H¹ ≠ 0 ⟺ K_m = ∅ is analogy, not equivalence; a Farkas
certificate is the LP shadow of an obstruction, not H¹ itself. Decision needed before
any shaving build: linear or nonlinear shaves. No shaving build was ordered.

### B-D03 — More-anchors tradeoff (design rule for anchor count)
Source: parent-conversation derivation (2026-10-30) + pass 3 §13. What it is: the
answer to "do more irrational anchors give more grounding?" Design: two different
kinds of grounding, neither free. COUNT: each ℚ-independent irrational adds a
direction (a lattice dimension) — coverage grows — but simultaneous approximation
loosens as k grows (Dirichlet: per-coordinate error < q^{−1−1/k}) and each added
anchor adds a gluing constraint. Rationally related anchors (√2 and 2√2) add nothing.
STRENGTH: badly approximable irrationals (φ extreme, all-ones continued fraction,
slowest convergence) resist rational capture hardest — stability-grounding, different
from coverage-grounding. Grounding is NOT monotonic in anchor count: past the point
where gluing constraints dominate, more anchors add inconsistency surface, not
grounding. Presented as standard mathematics (Dirichlet bound, badly approximable
numbers), labelled as mathematics rather than a research finding.

### Catalogue (perg-supplied 2026-10-30)

### B-CAT02 — Farkas certificate extraction on shave conflict
Source: perg-supplied catalogue VI.2. What it is: the diagnostic for an empty feasible set. Rule: when shaves conflict ({x: Ax ≤ b} = ∅), extract λ ≥ 0 with λ^T A = 0, λ^T b < 0; the support of λ names the conflicting constraint set — the localized "why not". Unbuilt; diagnostic for shape/EIT shaving work. Do not report a conflict as a bare rate; report the certificate.

---

## REFERENCE (background / design input)

### JEV program — transfer and closure background

### R-J01 — Second-route program closure (v1 + v2 negative results)
Source: rederivation-rule-report.md; interface-contract-route-report.md;
real-diff-coder-report.md. What it is: the background record of a closed
program. v1 re-derivation rule scored 28/28 by escalating on all 28 items:
route C (blind spec-derived tests) confirmed the judge 0 times in 28,
route D (argue-the-opposite) precision 4/14. v2 supplied the interface
contract: route C2 confirmed 0/20, discriminated 0/21, and generated 0
tests passing on correct code in 49 variant-runs — the interface
hypothesis is refuted as the binding cause. Autopsy split: five genuine
contract gaps (fixable) plus model errors no contract detail fixes
(gating inconsistency, kitchen-sink tests, syntax errors, invented
fixtures). Reopen condition, recorded not launched: a route that
confirms as well as vetoes, pre-registered on the frozen 28. The v3
reference-filter design (keep only shipped-passing tests, per-test
scoring, gaps closed) is identified and unlaunched; it weakens the
independence claim and must be pre-registered as such.

### R-J02 — Spectral findings on the EIT mesh (crossover, interface cost)
Source: spectral-test-report.md (protocol pre-registered and hashed before
computation; EIT reconstruction mesh, unit disk, P1 FEM, 289 nodes).
What it is: background only — no seat, rule, or bar change follows.
Crossover, not a sharp mobility edge: max adjacent IPR jump 3.14 against
the 5.07 bar, IPR span 9.01 against 100; the 73 above-threshold modes sit
at HIGH lambda (grid-scale oscillation, not Anderson localization).
Cheeger 2-way bound confirmed (interface 8.12 vs bound 2.68, ratio 3.03).
K-way sqrt(lambda) scaling fits this mesh only (slope 0.905, R² 0.971);
the general theorem stays refuted by the 1D counterexample. K* gap:
cost minimum at the boundary K* = 2 vs N_loc = 73, interface length
grows 8.12 → 20.37 with K, no plateau. Communication tracks interface
size, so more pieces/seats does not mean less communication — measured
escalation rates are that interface cost made visible. Particle/wave
vocabulary is NOT imported into multiplexer design; ker D was not
tested (unpinned). The bacterium geometry was not in the record and
was not used.

### Medical pass 1 — the eight areas, as background

### R-M01 — Bioelectricity lineage (Levin program)
Source: pass 1 §1. What it is: the experimental base. Planaria (Durant 2017):
brief gap-junction perturbation → stable, resettable two-headed regeneration,
including cryptic carriers that re-express on re-cutting in plain water. Xenopus
HCN2 rescue (Pai & Levin 2022): local OR distant HCN2 expression, or small-molecule
activators, rescued brain/eye/heart/gut defects from nicotine, ethanol, or aberrant
Notch, across all three germ layers. Anthrobots (Gumuskaya et al., Adv. Sci.
2023/24): human tracheal cells, no genetic modification, 30–500 µm, 45–60 days,
bridged a neuron scratch in vitro; 2025 lifecycle: > 9,000 genes changed, donor
epigenetic age 25 → 18.7. Wound: skin battery 10–60 mV; Dec 2025 Wi-Fi RF-powered
closed-loop bandage > 8 m, Mo electrodes, impedance sensing; DFU meta-analysis
10 RCTs / 451 pts, RR 1.45. Cancer: AML-MSC Vmem −14.7 vs healthy −28.5 mV, CaV1.2
down, tumour imposes depolarisation on stroma, hyperpolarisation restores behaviour
(Adv. Sci. 2025). TTFields 1–3 V/cm, 200 kHz GBM, FDA 2011 / 2015 / 2019 / 2024 NSCLC
— applied fields, NOT Vmem reprogramming. Use as background for the setpoint /
attractor hypothesis (B-M05) and the ternary gate (U-M06); do not import the strong
rewrite claim (see AVOID).

### R-M02 — BCI durability and inner-speech bounds
Source: pass 1 §2. What it is: the reading/writing record. UC Davis / BrainGate
Harrell: 256 electrodes, > 3,800 h at home independently, > 183k sentences, 56 wpm,
> 99% controlled / 92% sentences accurate-or-mostly (Nature Medicine 2026).
Stanford inner speech (Cell, 14 Aug 2025): 4 participants, up to 74% imagined
sentences, 125k vocab, mental password > 98%. Neuralink: first implant Jan 2024,
~20 surgeries end-2025, VOICE trial but NO published accuracy/vocab/latency —
company demo only. Synchron Stentrode: 16 electrodes, no craniotomy, SWITCH 4 pts /
12 mo stable, COMMAND 6 pts safety met, iPad via Apple BCI HID May / Aug 2025.
Non-invasive EEG/fNIRS cannot reliably read free-form private monologue;
reconstructions are task-constrained and subject-specific. BCI-FES meta-analysis
(8 RCTs, 357 pts): motor SMD 0.86, n.s., ADL SMD 1.47, p = 0.003, adjunct ≥ 4 weeks.

### R-M03 — Electroceutical systems table
Source: pass 1 §3. What it is: the closed-loop device record. SetPoint VNS for RA:
FDA Jul 2025, first implantable neuroimmune device, RESET-RA 242 pts
sham-controlled, ~1 min/day. RNS epilepsy: FDA 2013, pivotal −37.9% vs −17.3% sham.
Adaptive DBS: FDA Feb 2025 (Medtronic BrainSense / Percept, beta-gated); ADAPT-PD
JAMA Neurol 2025: 95% dual-threshold / 87% single-threshold comparable on-time,
44/45 stayed on aDBS (Medtronic-funded). Nia 60-channel closed-loop implant
(Brain Stimulation 2025, 3 sheep; vs RNS 6 ch, Percept 4 ch). Non-invasive acoustic
BCI seizure control: rat only, 2024. Hardware trend (Rogers lab): bioresorbable
electronics, soft/stretchable implants, ultrasound-powered implants — the implant as
a transient participant, not a permanent foreign body. Counterweight: LivaNova VNS
for depression, RECOVER missed its primary endpoint on sham improvement.

### R-M04 — EIT / ESI methods and their limits
Source: pass 1 §4. What it is: the imaging record. EIT forward ∇·(σ∇φ) = 0 +
complete-electrode model; inverse nonlinear, severely ill-posed; 2025 international
consensus, 87 recommendations, 4th–5th intercostal plane, absolute EELI not
comparable across subjects. EEG/MEG: y = L·x + noise, underdetermined by an order
of magnitude; classical priors MNE (biased superficial), beamformers, sLORETA, MEM /
wMEM; XDL-ESI (NeuroImage 2024) validated vs iEEG. Unrecoverable, stated plainly:
deep sources underestimated (~1/r²); two nearby sources inseparable below the
array's spatial Nyquist limit; silent sources (closed-field / radial / cancelling
dipoles) invisible no matter the algorithm.

### R-M05 — AI decoding: ECG / EEG foundation models
Source: pass 1 §5. What it is: the decoding record. ECGFounder (NEJM AI 2025):
10,771,552 ECGs, 1,818,247 subjects, 150 labels, AUROC > 0.95 for 80 diagnoses
internal, +3–5 pts fine-tuned. ECG-CLIP (Scripps, Lancet Digital Health): > 1.7M
ECGs + clinician notes, ~91% less labelled data, few-shot ~10 examples. Imperial
ECG AI: 67k pts, HF up to 81%, valve up to 90%, < 2 s, triage not diagnosis.
Lin et al. (Nature Communications 2026): unlabelled pretraining → transferable
representations. SleepFM: 1 night polysomnography, 130+ conditions, AUC > 0.85 CV
events. TA-MFF (Knowledge-Based Systems 2025): topology-aware multiscale fusion
for motor-imagery EEG. Multimodal EEG+ECG fusion (Sci Rep 2026): 95.7% stress-type;
neonatal seizure ECG+EEG: 94.9% sensitivity / 94.2% specificity (conference 2025,
not peer-reviewed). Newly decodable vs not: subclinical structural disease from a
normal-looking ECG, yes; free-form thought from scalp EEG, no; a unique interior
conductivity map from a few surface electrodes, no. The boundary is
information-theoretic, not algorithmic.

### R-M06 — Cardiac dynamics: topology, rotors, ablation energy
Source: pass 1 §6. What it is: the arrhythmia record. Spiral/scroll waves, phase
singularity ∮∇θ·dl = ±2π. Ghent topology 2026: open vs closed waves unifies
wavelet / mother-rotor theories, terminated AF in EVERY simulation but explicitly
NOT implantable (no catheter can make instantaneous moving lesion lines),
re-inducibility untested. PLOS Comput Biol 2026: conventional phase mapping invents
AND misses rotors near block/fibrosis (phantom rotors). Persistent AF ~50% success
(Europace 2025). PFA (irreversible electroporation): PulseSelect Dec 2023, FARAPULSE
Jan 2024, VARIPULSE Nov 2024, Volt Dec 2025 (392 pts); ADVENT 73.3% vs 71.3% thermal,
non-inferior — safety/speed gain, not efficacy gain.

### R-M07 — Optogenetics, sonogenetics, and neighbouring interfaces
Source: pass 1 §7. What it is: the writing-back record. Nobel 5 Oct 2026:
Hegemann / Nagel / Deisseroth. NEJM PIONEER retinitis pigmentosa (Oct 2026): 10 pts,
ChrimsonR AAV + goggles, 7/10 light sensitivity up 2.0–62.3×, 6/10 clinically
meaningful, NOT normal vision. Roadmap (Nature Neurosci 2025): indirect (circuit
maps steering drugs/neuromodulation) vs direct (retinal gene therapy) translation.
Sonogenetics 2025 rat epilepsy: 0.5 MHz, GABAergic activation, 50% modulation,
60 min suppression, preclinical only. Magnetogenetics: heating/force magnitudes
contested, no human data. Chemogenetics (DREADDs): minutes–hours timescale, no
implant. Non-genetic: TMS, tDCS, TUS, infrared — field actuators without genetic
addressing, hence less cell-type specificity, more accessible.

### R-M08 — Ion channels as computation; plant signals with numbers
Source: pass 1 §8. What it is: the fundamentals record. Voltage-gated channels are
nonlinear, history-dependent conductances: thresholding, coincidence detection,
oscillations (HCN funny current, Ca²⁺ clocks), bistability, wave propagation.
Bioelectric code status, honestly: Vmem patterns precede and predict outcomes;
perturbing Vmem changes outcomes causally; the code is NOT decoded — no published
dictionary mapping voltage pattern → anatomy. Ephaptic coupling established in
specific neural contexts, not as a general principle. Plant APs: all-or-none
(flytrap: 3°, 30 µN trigger, 2nd AP within ~20 s Ca²⁺ memory → snap, up to 10 cm/s)
vs SWPs: graded, 2–9 cm/min in Arabidopsis, GLR3.3/3.6 required, jasmonate defence
(New Phytol 2025). Commercial: Vivent €7.5M Nov 2025, > 1,000 ha Europe outdoor;
Electric Plant $11.2M seed, "Bombadil", 125 species — existence established,
accuracy NOT independently established (see AVOID).

### Medical pass 2 — the ten gaps

### R-P01 — Gap 1: artificial pancreas (deployed closed-loop reference)
Source: pass 2 gap B1. What it is: the deployed sensor→policy→actuator that plant
work should be measured against. Numbers: CamAPS FX real-world N = 35,714, median
TIR 69.6%, TBR 2.5%; LENNY 2–6 y, TIR 58 → 68%; CIRCUIT pregnancy (JAMA 2025).
Use: the real-world performance bar for any plant loop claim — report time-in-range
equivalents (time in healthy band, time below/above), not just accuracy.

### R-P02 — Gap 2: TMS drive vs tDCS bias vs tACS entrain, with nulls
Source: pass 2 gap B2. What it is: the noninvasive stimulation distinction. TMS
drives, tDCS biases, tACS entrains — three different mechanisms, not three strengths
of "stimulation". Nulls attached: HD-tDCS dose, ADHD no dose-response. Use: when
choosing a plant probe stimulus, name which mechanism it is; a bias probe and a
drive probe answer different questions, and null dose-responses are findings, not
failures to report.

### R-P03 — Gap 3: focused ultrasound (BBB opening, neuromodulation)
Source: pass 2 gap B3. What it is: the ultrasound record. Bilateral Parkinson's FDA
2025; BBB glioblastoma (Lancet Oncol 2025) matched-control survival 31.3 vs 19.3 mo
— NOT randomised; neuromodulation sham trials still needed. Use: a candidate
non-contact probe/actuator modality for plant work, with the matched-control
(not RCT) status attached to every survival claim.

### R-P04 — Gap 4: quantum diamond sensing (NV magnetometry)
Source: pass 2 gap B4. What it is: the sensing record. Rat MCG ~20 pT (2024);
Fraunhofer laser-threshold 100% contrast < 400 fT/√Hz (2026, lab). Pointer-state
paper discounted as unverified. Use: background for the sensor-candidate build
(B-M07); not a plant result.

### R-P05 — Gap 5: ingestible + continuous wearable sensing
Source: pass 2 gap B5. What it is: the sensing record. Ingestible bioimpedance
capsule (Holt 2025, animal / ex vivo only); CGM MARD / lag as the honest metric
discipline (a continuous sensor's error is a lag + bias, not a single accuracy).
Use: the metric template for any continuous plant sensor — report lag and bias
separately, not a blended accuracy.

### R-P06 — Gap 6: SCS / cochlear success vs retinal failure (encoding > count)
Source: pass 2 gap B6. What it is: the stimulation lesson. Spinal cord and cochlear
stimulation succeed; retinal implants fail — Argus II ~20/1260 acuity, withdrawn.
The resolution gap is biology (encoding), not geometry (electrode count). Use: the
counter to "more electrodes = better" (see AVOID) — for plants, more electrodes
without a forward model is just more correlated noise.

### R-P07 — Gap 7: bioelectric aging
Source: pass 2 gap B7 (Sediqi & Levin, iScience 2025). What it is: the aging record.
Senescent depolarisation; inter-culture heterogeneity UP, intra-culture heterogeneity
DOWN; spatial Vmem loss; pinacidil effect on SA-β-Gal NON-significant (kept, not
dropped). Use: the aging confound for longitudinal plant decoding — a decoder
trained on young plants will drift as the tissue ages, and the drift signature
(heterogeneity pattern) is itself measurable.

### R-P08 — Gap 8: organ-on-chip electrical readouts
Source: pass 2 gap B8. What it is: the bench record. TEER / MEA / MITO readouts on
organ-on-chip platforms. Use: background for the validation-bench build (B-M06).

### R-P09 — Gap 9: AI imaging beyond ECG/EEG
Source: pass 2 gap B9. What it is: the imaging-AI record. MerMED-FM: > 3.3M images,
AUROC > 0.90 after fine-tuning. Use: the scale pattern generalises beyond
electrophysiology — foundation models + fine-tuning beat task-specific models where
labels are scarce — but the AUROC is AFTER fine-tuning, and the fine-tuning data
cost is part of the claim.

### R-P10 — Gap 10: digital twins
Source: pass 2 gap B10. What it is: the twin record. Living Heart; inHEART 510(k)
2022 / 2024; Trayanova 10-patient twin-ablation, no recurrence at 1 y; OPTIMA n = 67
still preliminary / news-reported; FDA Jan 2025 draft guidance on credibility.
Use: the credibility-framework precedent for any plant twin claim — and the warning
that a twin's clinical use needs a credibility argument (context of use, influence,
evidence), not just a good fit.

### R-P11 — Pass-2 build order
Source: pass 2 synthesis. What it is: the ranked build sequence. Order: (1)
difference imaging with published prior / resolution / λ-sensitivity FIRST; (2)
frozen-encoder drift dashboard; (3) two-timescale loop with blinded sham on
reversible actions only; (4) routing table with ablation test; (5) ternary ONLY if
it beats continuous AND passes the jitter test. Verification-first is the
cross-cutting discipline: independent re-derivation, not judgement.

### Pass 2 — methodology, reasoning, computing axes

### R-P12 — Axis C1: methodology in math (Lean / AlphaProof, verification-first)
Source: pass 2 axis C1. What it is: the methodology record. Lean (2013; Simons Jun
2025 workshop, 57 participants, prime number theorem formalised); AlphaProof +
AlphaGeometry 2, IMO 2024 28/42 silver, manual translation + days compute caveat;
sphere-packing Lean project (Mar 2024, public Jun 2025). Verification-first =
independent re-derivation, not judgement. Use: the methodology input to U-F05
(blueprint-first plan) and the Lean-washing guard (see AVOID).

### R-P13 — Axis C2: fluent vs verified reasoning
Source: pass 2 axis C2. What it is: the reasoning record. IMO 2025 natural-language
gold 35/42, graded by humans, vs 2024 Lean-checked silver — opposite trade-offs
(machine certainty vs human readability), not a single monotonic triumph. ECP
neuro-symbolic; MATP > 42 pp step-verification gain; chain-of-thought as EVIDENCE
is misuse (CoT is a trace, not a proof). Use: the framing for every "the model
explained itself, therefore it is right" claim — explanation is not verification.

### R-P14 — Axis C3a: analog / memristor in-memory computing (rank 1 by direct transfer)
Source: pass 2 axis C3. What it is: the top-ranked computing paradigm for reading
tissue signals. Numbers: 2025 nanopore 97.15% F1, 51× / 477× vs ASIC. Use: the
candidate compute substrate for low-power, on-sensor decoding — rank 1 because it
computes where the signal lives, not because it is the most powerful.

### R-P15 — Axis C3b: neuromorphic / spike computing (rank 2)
Source: pass 2 axis C3. What it is: the spike paradigm. Photonic 40k-neuron SNN
(2025). Use: the event-driven candidate — spikes as the native representation for
AP-like plant signals; rank 2 because the representation matches, the tooling is
thinner than analog in-memory.

### R-P16 — Axis C3c: bioelectric / organoid-as-model computing (rank 3, proof-of-concept)
Source: pass 2 axis C3. What it is: the living-compute paradigm. DishBrain /
Brainoware proof-of-concept, not hardware. Use: background only — the substrate
analogy (living tissue as computer) is suggestive, the engineering is not there.

### R-P17 — Axis C3d: photonic front-end (rank 4)
Source: pass 2 axis C3. What it is: the front-end paradigm. Optica 2025 two-chip,
272 params, 320 ps. Use: the ultra-fast front-end candidate for signal conditioning
before decoding — rank 4 because it conditions, it does not decide.

### R-P18 — Axis C3e: NV sensing as sensor (rank 5)
Source: pass 2 axis C3. What it is: the sensor paradigm (distinct from the compute
ranking: NV is a sensor, not a computer). Use: background for B-M07; rank 5 in the
compute list because sensing is not computing, however good the sensor.

### R-P19 — Axis C3f: quantum computing (rank 6, no economically useful result yet)
Source: pass 2 axis C3. What it is: the quantum record. Willow below-threshold
(Dec 2024). Use: background only — no economically useful result for signal
decoding yet; do not let quantum language inflate a classical decoder claim.

### R-P20 — Axis C3g: DNA computing (rank 7, storage only)
Source: pass 2 axis C3. What it is: the DNA record. Storage only. Use: background
only — DNA is a storage medium in this ranking, not a decoder.

### Four fields — direct coverage and ranking

### R-F01 — Field 1 direct: mathematics' native programming (checker + calculator)
Source: pass 3 §1a. What it is: the field's toolkit. Lean: statement = type, proof =
value, small kernel accepts/rejects; Mathlib > 210,000 theorems / 100,000 definitions
(May 2025, secondary count, approximate). AlphaGeometry 2: 53% → 83% of historical
IMO geometry problems, symbolic engine ~100× faster. CAS (SymPy 1.14, Apr 2025):
symbolic/exact arithmetic, not float approximation. Solvers (Z3/CVC5, SAT/SMT):
native language is CONSTRAINT ("find x such that …"), not classification. Limits
travelling with every Lean claim: Lean certifies proof-from-axioms WITHIN a
formalisation, not that the formal statement is the informal claim meant;
autoformalisation is its own error source; the kernel is software and fallible
(2026 Collatz-kernel-bug episode, reported, not relied on).

### R-F02 — Field 2 direct: reasoning's four formalisms + engines
Source: pass 3 §2a. What it is: the field's toolkit. Proof theory (syntax, soundness /
completeness per logic); model theory (semantics; Gödel completeness for first-order,
divergence for richer logics — and a decoder's ML "model" is not a model in this
sense); Bayesian/decision theory (graded belief, Bayes action, value of information);
nonmonotonic/argumentation (Reiter defaults, negation-as-failure, Dung AF semantics:
grounded / preferred / stable / complete). Engines: SMT (Z3, CVC5 — monotonic, cannot
retract); ASP (stable models, multiple answer sets = multiple coherent world-views);
neuro-symbolic 2024–26: LLM+ASP (ACL Findings 2026: 94.5% MultiLogicNMR, 72.5%
BoardgameQA; SMT cannot directly express default negation); VeriCoT (Nov 2025:
CoT → FOL / SMT-LIB, premise-grounded); ICLR 2026 workshop neuro-symbolic AD-KG:
inconsistency 81.1% → 45.6% AT THE COST of a lower verification rate (the honest
state of the art).

### R-F03 — Field 3 direct: medical science's native mathematics
Source: pass 3 §3a. What it is: the field's toolkit. SEIR ODEs (2025 regional study,
RK4, max errors 4.81% / 5.60%, medium-term only); UDE (Phil. Trans. 2025); PBPK
whole-body digital twin for glimepiride (19 studies, SBML / libRoadRunner, hepatic
dysfunction + CYP2C9 exposure effects); genomics tokenisation (one-hot CNNs →
DNABERT; motif-capturing tokenisation unsolved; variant study 1,350,018 variants /
10,116 patients, PRC-AUC 0.904–0.996, but > 30% of performance from in-house assay
statistics, precluding easy generalisation; SAVANA, Nature Methods 2025, 99 tumours);
HH formalism (the bridge field — see B-F01); clinical tiers + alert fatigue
(2026 multi-agent CDSS preprint: synthetic, binary-routing proof of concept, needs
real-world testing). Plant ML numbers: see U-M14.

### R-F04 — Field 4 direct: chemistry's native mathematics
Source: pass 3 §4a. What it is: the field's toolkit. Schrödinger / DFT (few hundred
atoms); MLIPs learning E({r_i}) with forces −∇E: Allegro-pol (Nature Commun.,
energy + polarisation unified, external E-field, ~1e6 atoms vs few-hundred DFT,
SiO₂ + BaTiO₃ demos); GRACE (arXiv Aug 2025, complete ACE basis, OMat24-trained,
Pareto claim = preprint benchmark, awaiting replication); PET-MAD (Nature Commun.
2025, 16:10653) + PET-OAM-XL (Matbench Discovery leaderboard claim, not proof of
universality). CRN mass-action ODE ẋ = Σ(y′−y)k x^y, integer stoichiometry, Jan 2025
multistationarity + GAT; low copy numbers → chemical master equation (discrete
stochastic, mean recovers ODE only in the large-number limit); CRNs implement
probabilistic computation (HMMs, factor graphs, Bayesian filtering) — a mathematical
realisation result, not a claim cells literally run the reader's router.
Cheminformatics: SMILES → RDKit graph → descriptors/fingerprints (Morgan radius 2,
length 2048 standard); MoCL-GAT pre-trained on 1.9M ChEMBL compounds. Materials:
HackNIP (arXiv Jun 2025): pretrained NIP embeddings → shallow downstream heads,
studying when transfer beats fine-tuning.

### R-F05 — Transfer ranking: Medical 1, Reasoning 2, Mathematics 3, Chemistry 4
Source: pass 3 synthesis. What it is: the ranking by directness to the WHOLE
programme (living signal + AI decoding + confidence×cost routing + shape
reconstruction + closed loop). Medical 1: same substrate, same pipeline, same safety
problem; HH drop-in prior, PBPK/SEIR credibility discipline, plant ML honest baseline.
Reasoning 2: the router itself (Bayes action, ASP/Dung, proposer–verifier); lacks only
signal physics. Mathematics 3: the correctness layer (proof assistants, CAS exactness,
continued-fraction certificates, inverse-problem regularisation); no living signal,
no cost model. Chemistry 4: most powerful methodological analogue + best cautionary
tale (out-of-domain silent failure); furthest substrate (atoms interchangeable, energy
variationally defined; plants neither). Sub-task caveat: shape reconstruction alone →
Mathematics + Chemistry tie for first; router alone → Reasoning first.

### Theoretical math — remaining items

### R-T01 — Guth–Maynard zero density: method + small prime-window gain
Source: theoretical-math §1.6 (arXiv:2405.20552, preprint; journal publication not
verified). What it is: the Tier-3 analytic result. N(σ,T) ≪ T^{30(1−σ)/13+o(1)};
primes in intervals x^{17/30} (replacing Huxley's 7/12 = 0.583… with 0.566…, first
improvement in 80+ years at σ ≈ 3/4). Transferable method: when a worst-case bound
is stuck, improve the bound at the single critical parameter regime (here, Dirichlet
polynomial value N^{3/4}) rather than uniformly. Engineering gain: small at real
scales; asymptotic with o(1) and ε, not a finite table — do not use a shorter window
than 17/30 in a small-x regime where the error term dominates.

### R-T02 — Hikita e-positivity: probabilistic proof method
Source: theoretical-math §2.4 (arXiv:2410.12758, accepted JAMS per Sep 2026 report).
What it is: the Stanley–Stembridge conjecture (1993) proved — chromatic symmetric
function of a (3+1)-free poset's incomparability graph has all e-coefficients ≥ 0,
via an explicit inductive formula + modular law, with coefficients as (normalised)
PROBABILITIES, hence non-negative; "completely elementary", no geometry. Transferable
method only: if you need to prove non-negativity of a combinatorial count, find a
probabilistic interpretation — a count that IS a probability is automatically ≥ 0.
(See AVOID for the squashed-score version of this error.)

### R-T03 — Logic boundary results as language-design input
Source: theoretical-math §7.1 (Goldberg–Hathaway, arXiv:2505.01393, preprint).
What it is: the absoluteness result. Under a proper class of Woodin cardinals, every
(Σ₁²)^{uB} statement true in V is true in HOD (even with a universally-Baire-scaled
parameter); full absoluteness cannot follow from any large-cardinal axiom consistent
with V = Ultimate L. Transferable IDEA only: absoluteness as a robustness criterion —
a decision procedure is trustworthy if its verdict does not change when you move to
a smaller, more definable model; if your router's decision changes when restricted
to "definable" inputs, it is exploiting non-definable pathology. (The cardinal
results themselves are NO DIRECT USE — see N-T02/N-T03.)

### R-T04 — Ramsey results as forced-pattern scale
Source: theoretical-math §§2.1–2.2 (Campos et al., arXiv:2303.09521, Annals in press;
Mattheus–Verstraete, Annals Math. 199 (2024), peer-reviewed). What it is: the Tier-2
combinatorics. Diagonal Ramsey R(k) ≤ (4−ε)^k — first exponential improvement in 88
years (Erdős–Szekeres 4^k, 1935); book algorithm + zigzag lemma. r(4,t) =
Ω(t³/(log t)⁴), solving Erdős's conjecture up to (log t)² — Hermitian unital in
PG(2,q²) + random bipartite replacement + random subset (geometry supplies structure,
randomness the rest). Use: R(k) as a SCALE for forced consensus/exclusion clusters
in channel graphs (below it, independence is in principle possible; above it, the
router must handle forced clusters) — NOT as a safety guarantee; and the
skeleton-then-randomise pattern as a template for electrode layouts (finite-geometry
design, jitter within blocks).

### Framework / anchor / decoder — remaining background

### R-D01 — Lens laws + shaving skeleton idea (background)
Source: parent-conversation framework (assessed 2026-10-29/30). What it is: the
framework's solid core. Lens laws: solid. Shaving skeleton idea: solid as an idea —
half-space intersection, erosion/medial axis, and eikonal wavefronts share the
skeleton concept. What is NOT solid: the claimed three-way equivalence (see B-D02),
and H¹ ≠ 0 ⟺ K_m = ∅ as equivalence (analogy). A Farkas certificate is the LP shadow
of an obstruction, not H¹ itself. Use as background for B-D02; do not cite the
equivalence.

### R-D02 — Ternary mirror math: an evenness check, not a correctness certificate
Source: parent-conversation framework (assessed 2026-10-30). What it is: the mirror
check. Given M(x) = −P(x), the check P(x) =? ¬M(¬x) reduces to P(x) = P(−x) — an
evenness/mirror-relation check. Use: as a structural consistency check on
mirror-structured seats only. JEV seats are different models, not negations, so the
check does not apply to them as a correctness certificate. (As a certificate claim,
see AVOID.)

### R-D03 — Irrational-anchor thread: genuine connections vs metaphor
Source: theoretical-math anchor thread + pass 3 §13. What it is: the connection
audit. Genuine: Dirichlet/convergents alternating above/below; badly approximable =
bounded partial quotients; discrepancy O(log N/N) for badly approximable α;
Hauke, Baier–Roy, Kelley–Meka Bohr sets, Komlós. NOT irrational-anchor results by
metaphor: Kakeya, Langlands, Kervaire, large cardinals. Limits travelling with the
thread: almost every α is NOT badly approximable (Khintchine sense) — badly
approximable is measure-zero but topologically large; "use an irrational" is not
enough, WHICH irrational and its partial quotients is the content; in any machine
you only ever implement a rational — the anchor is a DESIGN for the ideal sequence
and a bound on truncation error, not a property floating-point code possesses.
Misuse signature recurring: treating a truncated rational as if it still had the
irrational's non-resonance, then being surprised by a beat frequency at exactly the
truncation scale.

### Program state (from research-gaps.md) — background, not uses

### R-S01 — SAT solver project state
Source: research-gaps.md. What it is: the solver programme's position. Stage 0
PASSED (amended: cap-edge protocol); spot-check PASSED (bracket (118,119] holds,
20/20 per-instance match); Stage 1 COMPLETE with IMPROVEMENT (watched literals,
gate 390/390, median ~70×, wall (173,174] count + firm, +55 vars, bar ≥ 2 + firmed
cleared); Stage 2 (VSIDS) queued, awaiting perg's order (widget offered, not tapped).
Stage 0 120 s-cap run judged superseded after Stage 1 (Stage 1's 30 s wall at 174
already exceeds Stage 0's predicted 120 s wall of 133, though solvers differ).

### R-S02 — Cap relativity of the SAT wall
Source: research-gaps.md. What it is: the cap-dependence measurement. 60 s cap:
first majority n = 126, count bracket (125,126], firm bracket (126,130] (only 130
firm; 127–129 unmeasured); prediction (124–126) MATCHED; 120 exactly 0.50 (not a
majority); solved medians rise monotonically 16.6 → 30.5 s; UNSAT fade moves right
with cap. Rule for citation: never present 126 (or 119, or 174) as "the" wall without
its cap attached.

### R-S03 — Strata serial window (proven, thin headroom)
Source: research-gaps.md. What it is: the serial-seat mechanism. Two-seat retry
PASS 2026-10-29: draft + mathwhiz paused, gate 7,500 passed with 1,648 margin
(9,148 free), Strata session-up in 30 s, clean restore to within +28 MiB of the trial
pre-state (free 3,751 → 3,779 MiB). The two figures must not be paired:
20,357 MiB used is the 2026-10-29 resting figure, while 3,751 MiB free is
the 2026-10-30 trial pre-state (used ≈20,813, +456 drift before the trial,
pre-existing, not trial-caused); 20,357 + 3,751 = 24,108 ≠ 24,564 total, so
the pair cannot be one measurement. Caveat: headroom at session-up thin (148 MiB free) — the round
trip proves load + restore, NOT inference headroom under load. strata.service
stays DISABLED; serial seats stay one-shot; do not enable the unit as a resident.

### R-S04 — Batch runner + router serialization (proven)
Source: research-gaps.md. What it is: the execution infrastructure. Batch runner
(mrfloppy ~/batch-runner/): direct-port seat calls, never through the router;
requires router API runs_in_flight 0 before the run and every window, else abort;
solo phase then series phase grouped by seat, strictly sequential; trap-restore;
demo 12/12 OK, series inflation median 0.97 (range 0.30–1.32), swap overhead ~2.1 s /
window. Router serialization: patch only in multiplex_api.py; lock held only for
generation in _guarded on /run, /run_verified, /run_re; /verify deliberately unlocked;
/route deliberately not locked (loopback /run acquires it; locking /route would
deadlock); live proof five concurrent /run calls staggered, all correct. Fleet
baseline: 8201/8202/8203/8207/8211 healthy, API :8198 healthy, novelty :8212 healthy;
shepherd :8206 and verifier :8199 PAUSED on perg's tap — do not silently resume.

### R-S05 — Fleet contention finding (why serialization exists)
Source: research-gaps.md (serving audit). What it is: the contention measurement.
Idle baselines: hammer 296.4, magicoder 184.2, quicklook 248.0, minicpm 347.5,
phi-4-mini 263.7 tok/s. All five concurrent: every model ~47–49 tok/s regardless
of size; minicpm kept 14%; aggregate ≈ 245 tok/s, about one mid-size model alone.
Concurrency adds no throughput; it fair-slices a fixed bandwidth budget. Quicklook
speculative-decoding arm measured and closed: draft Qwen3-0.6B Q8_0, spec median
213.8 vs resident 251.7 = 0.85× slower; pre-set ≥ 1.5× + text-match rule not met;
resident unchanged. Do not re-offer spec for quicklook unless target or draft changes.

### Catalogue (perg-supplied 2026-10-30)

### R-CAT07 — Hit-rate discipline for catalogue / map entries
Source: perg-supplied isomorphism document R2 (2026-10-30), an other-conversation synthesis — the RULE is adopted; the document's other threads are not endorsed by this entry. What it is: a quality measure for entries. Rule: an entry's quality is its hit rate = entries later used as tools / total entries; entries with numbers attached predict and get used, vocabulary-only entries are restatements. Judge entries by later use, not by completeness; periodic review prunes low-hit-rate entries.

---

## AVOID (do not import, with the reason)

### JEV program — policy errors

### A-J01 — Trusting hammer on ANY disagreement subset
Source: jev-hammer-recalibration-summary.md (§4). What it is: the forbidden rule.
Reason: on all 41 observed disagreements hammer is wrong and fast is right; any
trust-on-disagreement rule (by logprob bucket, decision value, or any probe feature)
scores 0 on that subset's observed rows and is unvalidated for the fast-wrong case,
which does not exist in the data. Even the best bucket (high decision_logprob
tertile, 0.696 hammer accuracy) sits below fast's 1.000 when answered.

### A-J02 — Pooling probe decision-value splits with saved splits
Source: jev-hammer-recalibration-summary.md (§2–§3). What it is: the double-counting
error. Reason: probe hammer == saved hammer on 71/71 both-answered rows (temp-0
determinism; the single differing row, new-a05, is a contract flip only — saved
fenced-JSON 'pass' vs probe bare-word 'pass', same leaning). The (b) B hint (probe
5/6 = 0.833, saved 9/10 = 0.900, intervals overlapping the A rate) is ONE observation
re-measured, not two. A larger probe needs FRESH items.

### A-J03 — Escalate-everything as a default policy
Source: jev-frontier-summary.md (§1, §5). What it is: the cost-1.00 policy. Reason:
on ns2 it trades one 0.01 error source (confident fast error) for another 0.01
(calculator failure) at 7× lean's cost, with its floor band (0.0018, 0.0545) fully
containing lean's (0.0103, 0.0176) — the point advantage is inside floor uncertainty.
Escalate-all is the degenerate frontier point, not the frontier.

### A-J04 — Duration-priced escalation from these runners
Source: jev-frontier-summary.md (§6). What it is: the "escalate if slow" policy.
Reason: duration is post-hoc (U-J09) — null rows take two attempts, so their
durations include a second thinking burn. A policy cannot price "slow" from a
duration caused by the null it would predict. Needs B-J06 first.

### A-J05 — Reading a realised 0.0000 as a true rate of 0
Source: jev-frontier-summary.md (§7). What it is: the realised-vs-population error.
Reason: error figures are exact on 280 rows, not confidence intervals for future
rows; the floor band is the honest uncertainty, and ns2-a23 proves the true rate is
not 0 in general. Same error in the other direction: the (a) 0/50 floor bound
(upper ~7.1%) is not proof of a zero (a) floor.

### A-J06 — Floor-model overstatement in the other direction (both-pass tie-break)
Source: jev-frontier-summary.md (§7). What it is: the conservative-floor caveat.
Reason: counting a failed escalated item as a full error overstates cost when the
failure mode is both-pass ambiguity with an arbitrary tie-break (expected error 0.5,
not 1.0). Reported floor bands lean high — which strengthens lean-vs-full dominance
and weakens escalate-all's point advantage further. Do not quote floor bands as exact.

### A-J07 — Lean rule applied to coder-seat judging of real diffs
Source: real-diff-coder-report.md. What it is: the forbidden
generalization. Reason: on 28 frozen real diffs the coder seats scored
20/28 (coder-30B) and 21/28 (Coder-Next) with ZERO nulls in 56 rows and
every coder-30B error at confidence 0.95 — the lean triggers (null OR
confidence < 0.8) cannot see confident misjudgment of single-line
semantics. The constructed-materials verdicts (U-J12, frontier
analysis) are evidence about small resident seats on constructed
items only; citing them for coder-seat judging of real work is the
transfer error this entry forbids. The default there is U-J16.

### Medical passes — claims and framings

### A-M01 — Voltage-as-literal-code ("voltage IS the blueprint, decoded")
Source: pass 1 synthesis (least transferable) + §8.1. What it is: the strong Levin
claim + the "decoded dictionary" claim. Reason: in planaria/Xenopus the causal layer
is experimentally strong; in adult mammals, rewritability at will is an
extrapolation; there is NO published "bioelectric genome" with a complete
voltage-pattern → anatomy dictionary. What exists is input–output pairs and models
that reproduce some of them. Use the causal layer (B-M05 experiments); do not cite a
decoded code.

### A-M02 — Levin "Platonic Space" / "Ingressing Minds" as biology
Source: pass 1 §1.1 + could-not-verify item 4. What it is: the 2025 manuscript/talks
framing (forms/minds "ingress" from a structured Platonic space). Reason: by the
evidence-ranked survey's own judgement, a speculative extension of the empirical
program, not an experimental result; philosophy, not biology. Excluded from the
evidence base. Do not cite it as biology.

### A-M03 — Company claims as field facts (Vivent, Electric Plant, Neuralink VOICE)
Source: pass 1 §§2.1, 8.2 + could-not-verify items 1–2; correction delivered
2026-10-30. What it is: Vivent stress lead time (days/weeks/months before visual
symptoms), Electric Plant ≥ 20% water reduction + yield increase, Neuralink VOICE
accuracy/vocab/latency. Reason: company-reported, no peer-reviewed field trial or
published metrics found in sources read. What IS established: Vivent > 1,000 ha
Europe outdoor + €7.5M Nov 2025; Electric Plant $11.2M seed + 125 species; Neuralink
~20 surgeries end-2025 + VOICE trial registry/design facts. The lead-time claim was
once stated as field fact and corrected — keep the correction attached.

### A-M04 — Market forecasts and company-reported counts as data
Source: pass 2 could-not-verify. What it is: closed-loop neurostimulation market
$1.2B 2025 → $6.0B 2035; digital twins in healthcare $2.8B 2025, 26.4% CAGR; Lotus
Neuro (~600 sessions, survival summaries beyond the Lancet Oncology report);
Cortical Labs / FinalSpark energy and capability claims; Quantinuum logical-qubit
error rates; IBM / Microsoft roadmaps. Reason: flagged in-text as forecasts or
company-reported; none independently verified. Do not use as evidence for a build
decision.

### A-M05 — Preprints / hypotheses treated as results
Source: pass 2 could-not-verify. What it is: MCF-7 multistability preprint (2026);
pointer-state NV paper (discounted as unverified); marine-plasma bioelectric
rejuvenation hypothesis; any 2026-dated secondary summary post-dating the mission's
nominal window; smart-bra EIS cancer preprint (> 90%, 0.1 mm³); breast-cancer
lateralisation preprint (Research Square, Aug 2025, gap-junction G0max 1.5 → 1.3 nS,
bistability modelling). Reason: cited only to show the claim exists and why it
should not be relied on. The lateralisation result is hypothesis-generating, not
established.

### A-M06 — FAIR-ESI / TA-MFF replication claims
Source: pass 1 could-not-verify item 3 + §4.2/§5.1. What it is: FAIR-ESI (Jan 2026,
83.99% precision at SNR −5 dB on simulated MEG, small epilepsy datasets) and TA-MFF
topology-aware EEG fusion. Reason: reported on simulated/small datasets; independent
replication not found; ground truth in ESI is almost always itself an inference.
Promising, not established.

### A-M07 — "More channels = better"
Source: pass 1 "What NOT to transfer" + pass 2 gap B6. What it is: the channel-count
fallacy. Reason: Synchron (16, endovascular) vs Neuralink (1,024–3,000, intracortical)
vs Nia (60, closed-loop) shows the optimum is task- and surgery-dependent; retinal
Argus II (~20/1260, withdrawn) shows the gap is encoding biology, not electrode
geometry. For plants, more electrodes without a forward model is just more correlated
noise.

### A-M08 — "AI accuracy in the lab = accuracy in the field"
Source: pass 1 "What NOT to transfer". What it is: the deployment fallacy. Reason:
Harrell's advance was removing the lab; ECGFounder's internal-vs-external gap is the
norm; Vivent/Electric Plant claims await independent trials. Counter-rule: U-M13.

### A-M09 — Single-driver stories ("find the rotor, ablate it")
Source: pass 1 §6 + "What NOT to transfer". What it is: the driver fallacy. Reason:
phantom rotors (phase mapping invents and misses), ~50% persistent-AF success,
REAFFIRM sobriety. Counter-rule: U-M12 + U-M04.

### A-M10 — Anthrobots as a therapy (or neuron-scratch as proof)
Source: pass 1 §1.1 (hype check). What it is: the over-read of the Anthrobot result.
Reason: the neuron-scratch result is a single under-controlled dish assay; mechanism
not isolated; no in-vivo guidance, targeting, or dosing exists. Anthrobots prove cell
collectives have latent competencies, not a therapy.

### A-M11 — PEMF "reprograms" cancer in patients
Source: pass 1 §1.3 ("What is NOT proved"). What it is: the oncology over-claim.
Reason: not proved; TTFields (applied fields, FDA-approved, mitosis/disruption
mechanism) must not be conflated with Vmem reprogramming. Keep the two separate in
every citation.

### A-M12 — Sonogenetics commercial rumour as data
Source: pass 1 §7.3. What it is: Merge Labs $250M OpenAI-related investment (Aug
2025, reported). Reason: rumour-level, not data. The rat epilepsy result (50%
modulation, 60 min suppression, preclinical) stands on its own; the investment rumour
adds nothing to it.

### Four fields — misuse signatures

### A-F01 — Lean-washing
Source: pass 3 §1b. What it is: the formalisation misuse. Signature: a pipeline
stamps "verified" on a decoder output because a formal checker accepted a
FORMALISATION of the output, while the formalisation silently dropped the noise
model, calibration drift, or sensor saturation. Detectable tell: the certificate
never mentions an interval, a denominator budget, or a rejected alternative — it is
always certain. Counter-rule: U-F05 + U-D01.

### A-F02 — Credibility-laundering (PBPK-waiver signature, generalised)
Source: pass 3 §3b. What it is: the context-of-use misuse. Signature: a model whose
credibility was established for one context (e.g. lamp on/off in one plant in one
room) justifies action in another (stress intervention across species, sites,
seasons), with the original context-of-use statement quietly dropped. Detectable
tell: the report quotes accuracy without population, time window, or shuffled-label
baseline. Counter-rule: U-F07.

### A-F03 — Monotonic router (cannot retract)
Source: pass 3 §2b. What it is: the retraction misuse. Signature: a router built on
an SMT-style monotonic checker that, once it has labelled a window "stress", can only
accumulate confirming evidence and never retract — the system "moves" (escalates,
waters, logs a confident diagnosis) while the retraction pathway has been deleted.
Detectable tell: the system has no recorded instance of changing its mind.
Counter-rule: U-F03.

### A-F04 — Solver-as-oracle (proposer = verifier)
Source: pass 3 §2b. What it is: the independence misuse. Signature: feeding a solver
a formalisation produced by the same LLM whose output it is supposed to check, and
reporting "solver-verified" — the verifier is not independent, so the check is
theatre. Counter-rule: U-F04.

### A-F05 — Universal-potential deployment without a distance metric
Source: pass 3 §4b (Focassio exemplar). What it is: the out-of-domain silent-failure
misuse. Signature: a decoder (or MLIP) trained on one domain is deployed on another
(new species, new surface, new season) and continues to output smooth, confident,
plausible values while its error grows with distance from training data.
Detectable tell: the system reports no distance-from-training-data metric, no
novelty score, no degradation curve; its confidence is a function of its own output
magnitude, not of its provenance. Counter-rule: U-F10.

### A-F06 — Stoichiometric certainty applied to physiological coefficients
Source: pass 3 §4b. What it is: the certainty-transfer misuse. Reason: a reaction's
integer coefficients are exact by conservation of atoms; a plant's "response
coefficient" is empirical and context-dependent. Treating the latter with the
former's confidence is the chemistry version of the PBPK-waiver error.

### A-F07 — Substrate forcing (continuous-first or discrete-first as slogan)
Source: pass 3 §§3c, 4c. What it is: the anchor misuse in both directions. Forcing a
variant into a "continuous ancestry score" and discarding the discrete call loses
the exact information the clinic acts on; forcing a genuinely continuous voltage
into three literal levels discards the waveform. Counter-rule: U-F14 (substrate-
appropriate modelling).

### A-F08 — CRN literalism ("cells literally run the router")
Source: pass 3 §4a. What it is: the over-read of the CRN computation result. Reason:
CRNs implementing HMMs / factor graphs / Bayesian filtering is a mathematical
realisation result, not a claim that cells literally run the reader's router. Do not
over-read it.

### A-F09 — Multiple argument extensions presented as a single decision
Source: pass 3 §2b. What it is: the actuation misuse of Dung semantics. Reason:
argumentation semantics can yield multiple extensions (multiple coherent justified
sets) — a feature for deliberation, a bug for actuation. Presenting one extension as
"the" decision without the tie-break policy (B-F05) conceals the choice.

### A-F10 — Experimental patterns promoted to theorems
Source: pass 3 §1b. What it is: the mathematics discipline misuse. Reason: in
mathematics a conjecture remains a conjecture until proved; in bio-signal work the
temptation is to promote a pattern found in one plant on one day to a "discovery".
The transfer is the discipline (conjecture ≠ theorem), not any particular theorem.

### A-F11 — Regulatory dates as a compliance basis (VERIFY-FIRST)
Source: pass 3 could-not-verify. What it is: ICH M15 adoption Jan 2026, EMA Simcyp
qualification opinion Jul 2025. Reason: from a vendor summary, not checked against
ICH/EMA primary documents. Do not rely on them for a compliance argument without
that check. (The M15 CREDIBILITY FRAMEWORK itself is usable — U-F07 — the dates
are not.)

### A-F12 — 2026 AI-mathematics claims as conclusions (VERIFY-FIRST)
Source: pass 3 could-not-verify. What it is: September 2026 Navier–Stokes Lean claim,
2026 Collatz-kernel-bug episode, 2026 IMO perfect scores, further Erdős results.
Reason: too recent, disputed, or company-reported to support any conclusion; the
pass-3 dated core is intentionally 2024–2025. Do not rely on them.

### A-F13 — Exact-species accuracy inference + unelicited utilities (VERIFY-FIRST)
Source: pass 3 could-not-verify. What it is: (a) plant-signal accuracy for the
reader's exact species/sensor/conditions inferred from the 2025 studies (single
Tradescantia pallida, specific rooms/protocols) — the 62–85% range is a prior for
scepticism, not a prediction; (b) router utilities/priors (cost of false watering
vs missed stress, prior over states) — an open design question (B-F03), not a
parameter to assume.

### Theoretical math — misuse signatures

### A-T01 — Independent coin-flip rounding quoting "Komlós says balance is constant"
Source: theoretical-math §1.1. What it is: the rounding misuse. Reason: independent
rounding is precisely what Bansal–Jiang's dependency control was invented to replace;
the (log N)^{1/4} bound is for the ∞-norm of a sum with dependency-controlled
rounding, and says nothing about regret, calibration, or a single channel's tail.
A rare attribute — the one that matters clinically — will be systematically off
under independent rounding. Counter-rule: B-T01 (audit the worst attribute).

### A-T02 — Generic-irrational phase assuming Poissonian gaps
Source: theoretical-math §1.2 (Hauke). What it is: the sampling misuse. Reason:
Hauke proves Poissonian gaps for badly approximable α over rough n AND proves the
statement FALSE for Lebesgue-almost every α. Using an arbitrary "irrational-looking"
constant (π, √2 truncated, a learned phase) and assuming Poissonian gaps follow is
exactly the error the theorem refutes. Counter-rule: B-T02.

### A-T03 — Almost-everywhere bounds for specific patients/channels
Source: theoretical-math §1.3. What it is: the quantifier misuse. Reason: a designed
anchor (badly approximable) or a resonance (rational) lives in the measure-zero
exceptional set where the almost-everywhere counting bound fails. Quoting it to
justify a threshold for a SPECIFIC patient/channel is invalid. Counter-rule: B-T04.

### A-T04 — Prime-window below the asymptotic floor
Source: theoretical-math §§1.4, 1.6. What it is: the asymptotic misuse. Reason:
Baier–Roy needs Y ≥ X^{2/3+ε} and δ above the floor; Guth–Maynard's 17/30 is
asymptotic with o(1) and ε. Shrinking the window or δ below the floor, or using a
shorter window in a small-x regime where the error term dominates, and still
expecting uniformity, is invalid. Counter-rules: B-T03, R-T01.

### A-T05 — GMC fit to a single-scale signal
Source: theoretical-math §1.7. What it is: the null-model misuse. Reason: GMC's
scale-invariance is false for data with a characteristic scale (dominant rhythm,
refractory period) and will over-predict extreme bursts; the model will fit because
it is flexible, and the fitted "fractal" parameters will mean nothing.
Counter-rule: B-T06 (martingale diagnostic first).

### A-T06 — Ramsey safety claim for non-binary interactions
Source: theoretical-math §2.1. What it is: the bound misuse. Reason: R(k) ≈ 4^k
applies to pairwise binary colourings; quoting it to claim "with 20 channels we are
safe from forced patterns" when interactions are graded, time-varying, or hypergraph
(three-way) is vacuous — the relevant Ramsey number is different and usually much
larger. Counter-rule: R-T04 (scale, not guarantee).

### A-T07 — Unital construction literally on a physical surface
Source: theoretical-math §2.2. What it is: the construction misuse. Reason: the
Hermitian unital lives in a projective plane, not on a cortex or a leaf; adjacency
in the abstract graph does not match physical adjacency. Import the
skeleton-then-randomise pattern (R-T04), not the literal geometry.

### A-T08 — Sandwich exactness (no slack)
Source: theoretical-math §2.3. What it is: the coupling misuse. Reason: the theorem
gives containment with high probability, not equality. Applying a G(n,p) result to
a regular network and claiming it holds EXACTLY, without the sandwich slack, is
invalid; non-monotone properties do not transfer at all. Counter-rule: B-T07.

### A-T09 — Squashed score = probability
Source: theoretical-math §2.4 (Hikita). What it is: the positivity misuse. Reason:
Hikita's coefficients are probabilities because they are DEFINED as such, with a
sample space; a learned score in [0,1] is not a probability by virtue of its range.
Counter-rule: R-T02.

### A-T10 — Noisy self-similarity → aperiodic anatomy
Source: theoretical-math §3.1 (hat/spectre). What it is: the pattern misuse. Reason:
local patches can be locally consistent everywhere yet globally non-periodic, but
in NOISY data "supertiles" appear by chance at some scale, and the substitution test
will false-positive. A self-similar pattern in a noisy reconstruction is not evidence
the underlying anatomy is aperiodic/fractal — it may be an artefact of the
reconstruction algorithm's own multiscale smoothing.

### A-T11 — Moving-sofa optimum for deformable probes or variable corridors
Source: theoretical-math §3.2 (Baek). What it is: the scope misuse. Reason: the
theorem's corridor is rigid and width exactly 1, the sofa rigid; a deformable probe
could do better by deforming or worse by snagging, and a variable-width corridor is
a different problem. "2.2195 is the maximum" does not transfer to either.

### A-T12 — Noperthedron → "some shapes cannot be imaged"
Source: theoretical-math §3.3. What it is: the scope misuse. Reason: the theorem is
about STRAIGHT holes through IDENTICAL copies of a convex polyhedron — not about
imaging in general. A bending probe or a non-convex shape is outside its scope.
Counter-rule: B-T09(c) (negative transfer, correctly scoped).

### A-T13 — Kervaire → "my high-dimensional feature is real"
Source: theoretical-math §3.5. What it is: the citation misuse. Reason: survival of
h₆² in the Adams spectral sequence says nothing about data; the filtration is a
spectral sequence, not a filter bank, and survival is a ℤ/2 computation, not a
signal-to-noise ratio. (The theorem itself is NO DIRECT USE — N-T01.)

### A-T14 — Dudeney graph consistency → geometric reconstruction exists
Source: theoretical-math §3.6. What it is: the sufficiency misuse. Reason: the
matching-diagram graph rules OUT impossibilities; it does not by itself construct
the embedding. Proving patch adjacency consistent is necessary, not sufficient, for
geometric reconstruction — and the theorem is no-flip; the flipped case is a
different statement.

### A-T15 — "Typical λ₁ ≈ 1/4" for arbitrary networks
Source: theoretical-math §3.7. What it is: the measure misuse. Reason: the theorem
is for closed hyperbolic surfaces with the Weil–Petersson measure, not for directed,
weighted, time-varying control graphs. Counter-rule: B-T08 (null, correctly scoped).

### A-T16 — "Kakeya says dimension 3" for narrow-cone reconstructions
Source: theoretical-math §4.1. What it is: the scope misuse. Reason: full Kakeya
needs line-like measurements covering ALL directions; a narrow cone of directions
falls under a RESTRICTED Kakeya / X-ray estimate, and the full-dimensional conclusion
does not follow. Counter-rule: U-T03.

### A-T17 — Cairo → "decoding is impossible"
Source: theoretical-math §4.2. What it is: the over-read. Reason: Cairo kills a
SPECIFIC proof route (endpoint restriction via Mizohata–Takeuchi) and a SPECIFIC
uniform bound, not decoding itself; non-linear, adaptive, or prior-structured
decoders are outside the linear extension bound. Counter-rule: U-T04.

### A-T18 — "Hilbert's sixth is solved" for neural tissue controllers
Source: theoretical-math §4.3. What it is: the hypothesis-dropping misuse. Reason:
the chain is rigorous for dilute gases on a torus; a physicist's comment (not a
refutation, a scope statement) notes it is not true continua. Neural tissue's
memory, adaptation, and long-range coupling are the opposite of molecular chaos.
Counter-rule: U-T06.

### A-T19 — Renormalisation applied to smooth-signal decoders
Source: theoretical-math §4.6. What it is: the correction misuse. Reason: if the
noise is smooth, renormalisation is unnecessary and will, applied blindly, subtract
a real signal — the decoder will then "discover" the signal disappeared.
Counter-rule: U-T07.

### A-T20 — "Navier–Stokes blows up" from Chen–Hou
Source: theoretical-math §4.5. What it is: the equation misuse. Reason: Chen–Hou is
Euler (inviscid), with boundary, computer-assisted, peer-reviewed; Navier–Stokes
regularity remains open, and whole-space blowup is not shown. Counter-rule: B-T05.

### A-T21 — Langlands-type duality claimed for a learned embedding
Source: theoretical-math §6.1. What it is: the equivalence misuse. Reason: the
Langlands equivalence is exact and categorical; a learned embedding loses
information and is not an equivalence. Properties proved on one side do not transfer
exactly to the other unless the equivalence is proved. (The theorem itself is
NO DIRECT USE — N-T02.)

### A-T22 — "Verified" without stating the fragment
Source: theoretical-math §7.3 (Nation–Paolini). What it is: the conditional-
verification misuse. Reason: verification in a decidable fragment is conditional on
the fragment; reporting it as "verified" without stating the fragment conceals the
condition, which is the content. Counter-rule: B-F02.

### A-T23 — Absoluteness claimed from a test model
Source: theoretical-math §7.1. What it is: the absoluteness misuse. Reason:
absoluteness is a theorem about a specific class of statements ((Σ₁²)^{uB}) under
specific large-cardinal hypotheses, not a property of a test suite. A decision true
in your test model is not thereby "absolute". Counter-idea: R-T03.

### A-T24 — "The hierarchy is not linear" as an excuse to abandon ranking
Source: theoretical-math §7.2 (Aguilera et al.). What it is: the ranking misuse.
Reason: the theorem says ranking is PARTIAL (strength is not a total order; relative
position matters), not that ranking is impossible. Do not use it to abandon ranking
altogether.

### A-T25 — Preprints as proved; formalisation as new theorem; prizes as peer review
Source: theoretical-math guardrail + could-not-verify. What it is: the status
misuse, applying to the whole theoretical report. Reason: journal publication NOT
verified for Guth–Maynard, Wang–Zahl main paper, Anantharaman–Monk, Bansal–Jiang,
Behague et al., Baek, Lin–Wang–Xu, Cairo, Brittenham–Hermiller, Deng–Hani–Ma,
Goldberg–Hathaway, Aguilera et al., Magidor–Väänänen, Nation–Paolini,
Steininger–Yurkevich, Demaine et al. — each is stated "preprint" and must not be
upgraded on prizes, press coverage, or Fields Medals. Lean formalisations of Baek's
sofa proof (2026), the prime number theorem, sphere packing, and Fermat's Last
Theorem are formalisations of OLD results (or, for Baek, of a 2024 preprint), not
new theorems; the one exception — a formalisation project ADDING uniqueness of
Gerver's sofa — is a formalised claim, not a journal theorem, and is not ranked as
such. The October 2026 OpenAI mass release (> 700 papers: Navier–Stokes,
quasi-Riemann / no Siegel zeros, Kakeya in 4D, cycle double cover, Jacobian
conjecture; reported by Science) is EXCLUDED from the ranking — a mass release is
not a theorem, and none of it is peer review; a separate verification pass, not a
ranking pass, would be needed. A March 2025 preprint claiming to disprove RH via
prime-gap instability was found and NOT included; RH remains open.

### A-T26 — Reconstructed Kakeya URL (provenance, not content)
Source: theoretical-math notes/correction-url.md. What it is: the dropped link
string https://arxiv.org/html/2502.17655, reconstructed from the arXiv identifier
rather than copied verbatim from a search result. Reason: provenance, not a content
ban — an assembled link can silently point to the wrong version, paper, or
nonexistent page. The correct citation (Wang & Zahl, arXiv:2502.17655, Feb 2025,
via the Fields Medal summary and the Kakeya_set page) is used; the assembled string
is disregarded as a source link. This was NOT a safety filter or a refusal.

### Framework / anchor / decoder — misuse

### A-D01 — Irrational anchor as foundation (retired form)
Source: pass 3 synthesis verdict. What it is: the foundational claim ("anchor on
irrationals first" as ontology). Reason: five fatal breaks — (1) you cannot store
an irrational (ADC codes and floats are finite dyadic rationals; implementable form
is symbol/interval/convergent, not an irrational anchor); (2) much of the world is
genuinely discrete and the interesting set is often measure-zero (bases, counts,
stoichiometries, proof terms, resonant/rational configurations); (3) at finite
resolution irrational vs rational is unobservable (rationals dense; only bracket
width is observable); (4) decisions/actions are discrete and the loop must close on
them (quality measured by commitments, not by postponing them); (5) the plant signal
itself mixes both (AP all-or-none on continuous voltage; HH gating variable as the
bridge). Retained form: U-D01 (discipline + reformulation), not the foundation.

### A-D02 — Single magic number as anchor (φ numerology)
Source: parent-conversation derivation (2026-10-30). What it is: "use φ" as the
anchor. Reason: a single magic number is numerology, not an anchor. The defensible
version is the CLASS plus the continued-fraction approximation structure — and the
pinning question (which irrational, or the class itself?) remains open, not adopted.

### A-D03 — Ternary mirror as a correctness certificate
Source: parent-conversation framework (assessed 2026-10-30). What it is: the
certificate over-read. Reason: given M(x) = −P(x), the check reduces to P(x) = P(−x),
an evenness/mirror-relation check, not a correctness certificate; and JEV seats are
different models, not negations, so it does not apply to them as a certificate at
all. Kept form: R-D02 (evenness check on mirror-structured seats only).

### A-D04 — Ternary as a native code (decoder quantisation mistaken for nature)
Source: pass 1 §1.3, pass 2 transfer 4, pass 3 verdict. What it is: the literal-code
claim. Reason: biology uses continuous voltage with thresholds, not a literal
−1/0/+1 code; plants have AP/VP/SP event types, not three levels; MCF-7 data suggest
multistability/continuity. Ternary is a decoder's quantisation, honestly implemented
only under the U-M06 gate (relative bands, hysteresis, coupling, jitter test).

### A-D05 — Category translation without ⊔ (promissory "test the three laws")
Source: research-gaps.md (corrected translation). What it is: the premature-test
error. Reason: see U-D07 — until ⊔ is pinned to an artifact, "test the three laws"
is a promissory note; and the SAT wall is not a melding wall. Do not report
framework redescriptions of measurements perg already had as new measurements.

### A-D06 — Exponent error 2^{7/6} (corrected, do not reintroduce)
Source: research-gaps.md (framework correction). What it is: the wrong expression
for the SAT wall base. Reason: 2^{7/6} ≈ 2.24, not ≈ 1.12. Correct forms: 2^{1/7} ≈
1.104 (seven variables per doubling) or 2^{1/6} ≈ 1.122 (six); velocity form
7/ln 2 ≈ 10 variables per e-fold of cap. Use U-D06's numbers.

### A-D07 — "58/58 pair, ρ = 0.94, 3% disagreement, 40.5% both-wrong, 8% copy" as fleet data
Source: research-gaps.md (framework grounding error). What it is: the misattributed
numbers. Reason: those are NOT JEV measurements — perg later clarified they were a
different pair, but did not identify which pair. Do not treat them as fleet
measurements. (Internally consistent: error marginals 0.42, ρ = 0.94 gives both-wrong
0.405; P(A) = P(B) = 0.58, P(A∪B) ≈ 0.595 gives intersection 0.565 and disagreement
0.03; independence ceiling 1 − 0.42² = 0.8236; captured gain ~6% — arithmetic, not
fleet data.)

### A-D08 — Frontier API seat as a precondition (conflicts with standing decision)
Source: research-gaps.md (framework Corollary 7). What it is: the paid-lane mandate.
Reason: conflicts with perg's standing 2026-10-02 decision declining the paid
frontier lane ("I have vast resources"; local fleet covers it). The framework cannot
mandate it. Accepted no-paid diagnostic path: decorrelated local third seat + Z3
installed + mpmath/SymPy + Lean later if wanted; frontier API only an optional
accelerator, not a precondition.

### A-D09 — Emergence ≠ compressibility "proof" (Wolfram thesis as theorem)
Source: research-gaps.md (framework Part VIII). What it is: the overstatement.
Reason: halting and Diophantine undecidability are proved; computational
irreducibility as used there is Wolfram's thesis, not a proved theorem. Do not cite
it as proved.

### A-D10 — Shape↔control duality as a general proposition
Source: research-gaps.md (control framework, corrected). What it is: the duality
over-read. Reason: reachable set under dynamics and shaving polytope from lenses
coincide only in special cases; skeleton = switching surface likewise only in
special cases (e.g. bang-bang time-optimal control). Gramian spectrum targeting
requires a defined linearisation/embedding and operating point; not computable until
those are pinned. Separation principle correctly stated for LQG, only approximate
for this discrete, non-Gaussian, non-quadratic system. Continuous-time formulas for
this discrete-time system were conceded and corrected (reachability sum; Kalman rank
rank[B, AB, …, A^{n−1}B] = n; Gramian as sum; stability ρ(A+BK) < 1, not negative
real parts).

### Catalogue (perg-supplied 2026-10-30)

### A-CAT05 — Catalogue VIII.2's 2^{7/6} line (known exponent error, repeated)
Source: perg-supplied catalogue VIII.2 (2026-10-30). What it is: the repeated error. Reason: 2^{7/6} ≈ 2.24, NOT ≈ 1.12; correct forms are 2^{1/7} ≈ 1.104 / 2^{1/6} ≈ 1.122 (see also A-D06, which records the same error in the earlier framework text). Never cite the VIII.2 line for the wall base.

### A-CAT06 — Catalogue ρ = 0.94 numerics as fleet data
Source: perg-supplied catalogue II.1/II.2. What it is: the 1.5% averaging gain and 4× velocity-noise numbers. Reason: they rest on an unsourced pair (ρ = 0.94, "a different pair", never identified — not JEV/fleet measurements; see also A-D07); illustrative only, never cite as measured. The lag-lever conclusion is additionally contradicted by the measured NEGATIVE lag result (jev-lag-run-summary.md): lag carries no separation signal, so the 4× claim fails on fleet evidence twice over.

---

## NO DIRECT USE (with the reason it does not transfer)

### N-T01 — Kervaire invariant in dimension 126
Source: theoretical-math §3.5 (Lin–Wang–Xu, arXiv:2412.10879, preprint, explicitly
not peer-reviewed per PKU news). What it is: smooth framed manifolds with Kervaire
invariant one exist in dimension 126, closing the 65-year problem (dimensions 2, 6,
14, 30, 62, 126, no others; h₆² permanent cycle via motivic/synthetic homotopy +
machine-assisted Adams differentials). Reason: no honest direct use in tissue signal
decoding, shape reconstruction, routing, or control. The weak analogy (obstruction
surviving all filters ≈ feature surviving all denoising) is labelled as a slogan
only — the filtration is a spectral sequence, not a filter bank.

### N-T02 — Geometric Langlands (unramified, characteristic zero)
Source: theoretical-math §6.1 (Gaitsgory et al., May 2024 announcement, five papers
~1,000 pp, submitted, peer review will take years per SciAm; Breakthrough Prize 2025
≠ peer review). What it is: D-mod(Bun_G) ≃ IndCoh(LocSys_Ǧ) with Hecke compatibility.
Reason: no decoder, router, or controller should import D-modules on Bun_G. The only
transfer is the PATTERN (find an equivalence between a hard representation and an
easy one — e.g. time-domain vs frequency-domain) and the warning that a learned
embedding is not an equivalence (see A-T21).

### N-T03 — Exacting / ultraexacting cardinals
Source: theoretical-math §7.2 (arXiv:2411.11568, arXiv:2509.10254, preprints).
What it is: large cardinals compatible with ZFC whose existence implies V ≠ HOD;
ultraexacting equiconsistent with I0; exacting strictly between I3 and I2; hierarchy
not linear (an extendible above an exacting does not refute HOD; an exacting above
an extendible would refute Woodin's HOD and Ultimate-L conjectures). Reason: do not
import exacting cardinals into a router. The only transfer is the WARNING (ranking is
partial, not total — see A-T24), not a component.

### N-T04 — Inner model C²(ω) (Magidor–Väänänen)
Source: theoretical-math §7.3 (arXiv:2508.17672, preprint). What it is: second-order
logic fragment (countable sets) inner model containing, under a proper class of
Woodin cardinals, inner models with n Woodin cardinals for every n, while C(aa)
contains none; ω₁^V Mahlo in C²(ω) under a Woodin limit of Woodins. Reason: a
boundary result about logical strength, not a component for routing, decoding, or
control. Its transfer is at most the boundary-result lesson (locate exactly where a
logic stops being tractable), already captured in B-F02.

### N-T05 — Harper GMC transition (announced, preprint unverified)
Source: theoretical-math §1.7. What it is: the announced calculation of the
randomness-to-chaos transition for zeta-zero statistics in small intervals (x, x+y].
Reason: conference announcement (summer/autumn 2025, SciAm report); no preprint or
journal reference verified in the pass. Announced, not established — no use until
the record is verified. (The GMC NULL MODEL itself, if verified, is B-T06; the
transition calculation is not.)

### N-T06 — 3D einstein (Chair44 AI-assisted announcement, 2026)
Source: theoretical-math §3.1 (excluded). What it is: a claimed 3D aperiodic monotile.
Reason: separate, AI-assisted announcement, NOT counted in the mission's scope (the
2023 hat/spectre result); excluded from the ranking. No use until independently
established.

### N-T07 — Disputed / unreviewed single-author claims (RH disproof et al.)
Source: theoretical-math guardrail. What it is: e.g. a March 2025 preprint claiming
to disprove RH via prime-gap instability. Reason: found in search, NOT included; RH
remains open; Guth–Maynard bounds exceptions, it does not prove or disprove RH. No use.

### N-T08 — "Platonic Space" as a research input (philosophy, not experiment)
Source: pass 1 §1.1 (see also A-M02). What it is: Levin's 2025 framing of forms/minds
ingressing from a structured Platonic space. Reason: speculative extension, not an
experimental result; excluded from the evidence base. Listed here as well as under
AVOID because it has no transferable content at all — not even as a hypothesis with
a test attached (contrast B-M05, which has a test).

### N-T09 — Magnetogenetics as a plant actuator (no human data, contested physics)
Source: pass 1 §7.3. What it is: magnetic nanoparticles + heat-sensitive TRPV1 (or
mechanosensitive channels) opened by alternating magnetic fields. Reason: heating
and force magnitudes remain contested; no human data. No use as a plant probe until
the force/heat budget is settled — contrast sonogenetics (preclinical rat data) and
optogenetic-style electrical probing (B-M03), which have measurements.

### N-T10 — DNA computing as a decoder (storage only)
Source: pass 2 axis C3 (rank 7). What it is: DNA as a computing substrate in the
ranking. Reason: storage only in this ranking — no decoding, routing, or control
transfer. Kept in the map so the ranking is complete, not because it transfers.

### N-T11 — Quantum computing as a decoder substrate (no economically useful result yet)
Source: pass 2 axis C3 (rank 6). What it is: Willow below-threshold (Dec 2024) and
the error-correction era. Reason: no economically useful result for signal decoding
yet. Kept so the ranking is complete; the use, if any, is future background, not a
component now.

---

## Pass-2 build order, restated as the map's spine

Difference imaging with published prior / resolution / λ-sensitivity →
frozen-encoder drift dashboard → two-timescale loop with blinded sham on reversible
actions only → routing table with ablation test → ternary only if it beats
continuous AND passes the jitter test. Verification-first throughout: independent
re-derivation, not judgement. (Source: pass 2 synthesis; entry R-P11.)

## Coverage checklist — all required items present

- [x] All 5 JEV items with numbers: floor 1/100 (U-J04) · null lift 3.22× (U-J03) ·
  lag negative (U-J08) · frontier lean + insurance r = 0.01 (U-J01, U-J05) ·
  recalibration unmoved (U-J02, A-J01).
- [x] All 5 pass-2 transfers with holds/breaks/misuse: closed-loop (U-M01) ·
  inverse-problem (U-M02/U-M03) · foundation-model + drift (U-M05) · ternary
  (U-M06) · multiplexed routing (U-M07/U-M08).
- [x] All 10 pass-2 gaps: R-P01–R-P10.
- [x] All 4 fields with direct + analogy: Mathematics (R-F01, U-F05/U-F06/U-F15) ·
  Reasoning (R-F02, U-F01–U-F04) · Medical science (R-F03, U-F07–U-F09, U-F13) ·
  Chemistry (R-F04, U-F10–U-F12).
- [x] Tier 1 AND Tier 2 AND Tier 3 math results: Tier 1 — Schauder (U-T01),
  Komlós (B-T01), Kakeya (U-T03), Kelley–Meka (U-T02), badly-approximable sampling
  (B-T02/B-T03); Tier 2 — Chen–Hou (B-T05), sandwich (B-T07), spectral gap (B-T08),
  Cairo (U-T04), non-additivity (U-T05), Hilbert sixth (U-T06), SPDE (U-T07),
  Ramsey (R-T04), shape quartet (B-T09); Tier 3 — Langlands (N-T02), Kervaire
  (N-T01), Guth–Maynard (R-T01), Hikita (R-T02), logic (R-T03, N-T03, N-T04, B-F02),
  GMC (B-T06, N-T05).
- [x] Irrational anchor + convergent-band decoder + more-anchors tradeoff:
  anchor verdict (A-D01, U-D01) · decoder (B-M01) · more-anchors (B-D03) ·
  anchor thread audit (R-D03).
- [x] Pass-2 build order: R-P11 + spine above.
- [x] Could-not-verify items as AVOID / VERIFY-FIRST: A-M03–A-M06, A-F11–A-F13,
  A-T25–A-T26, and the pass-1 list carried in R-M01–R-M08 notes.
- [x] Falsification tests: router ablation (U-M07) · ternary jitter (U-M06) ·
  Lean-washing guard (A-F01) · credibility guard (U-F07, A-F02).
- [x] Framework corrections carried, not dropped: exponent error (A-D06) ·
  58/58 misattribution (A-D07) · frontier-API conflict (A-D08) · emergence
  overstatement (A-D09) · shape↔control duality (A-D10) · category caveat (U-D07,
  A-D05) · ternary mirror (R-D02, A-D03).

*End of map. No new research was done for this file; every entry traces to one of
the sources listed in the header. Items marked "NOT ordered" or "NOT tapped" remain
not ordered; this map does not order them.*

---

## EARLIER STATEMENTS

**Exclusions (stated, not mapped):** the user's personal history is not
research content to use and is not mapped here; PS5 campaign operational
material stays in its own records and is not mapped here. This section
covers research, framework, and method statements only. It does not
duplicate the cost-error frontier (already mapped), and it does not
re-order, rewrite, or delete the original 223 entries above.

**Coverage count for this section (verified by grep on E- entry IDs,
2026-10-30):** NEW entries: **47**. By source prefix: E-EMG 10 +
E-SAT 5 + E-SLV 1 + E-JEV 3 + E-SRV 13 + E-MTH 7 + E-FRM 4 + E-REG 4 = 47.
By use class: USE NOW 28 · BUILD NEXT 2 · REFERENCE 11 · AVOID 3 ·
NO DIRECT USE 3. Sum check: 28 + 2 + 11 + 3 + 3 = 47.
**Floor items skipped as already covered (not duplicated):** SAT
wall-as-quantile (U-D06, R-S02); solver Stage 0 amended pass + Stage 1
watched literals + Stage 2 queued (R-S01); router serialization (R-S04);
quicklook speculative decoding CLOSED at 0.85× (R-S05); multidimensional
shape definition + gluing G + gluing blindness (B-D01); ternary verdicts
(U-D05); trajectory method (U-D02); precision-then-shift (U-D03);
relation-as-math (U-D04); lens laws (R-D01); shaving construction +
linear-vs-nonlinear shaves decision (B-D02, R-D01); merge semilattice
with ⊤ = disagree (U-J06); distillation-vs-melding guardrail + collapse
signature (U-J07). That is 13 floor groups skipped; the other 16 floor
groups are added below.

### USE NOW (verified, decision-ready)

### E-EMG01 — Pointer heuristic, CONFIRMED subset SUPPORTED (zero-null caveat)
Source: pointer-tightened-report.md (batch-2 tightening run, 2026-10-29).
What it is: the tightened pointer detector. Rule: a hit counts as CONFIRMED
only if (a) GRID — it belongs to a ≥3-term stride-24 arithmetic progression
of firing offsets in the same strip, or (b) FIXTURE — its offset fires in
≥2 of the 3 P170 sessions (run1, run2, census); all other hits are
UNCONFIRMED, not deleted. Numbers: real total 165 (replication gate
passed exactly); confirmed real 79 vs confirmed shuffled mean 0.000 /
SD 0.000 across all 20 rounds (every round exactly 0); P170 5/5 and
P10240 21/21 intact; fixture-only-to-P170 sensitivity gives the identical
79. Caveat travelling with the verdict: the 5× and +3SD bar legs are
VACUOUS at a zero null (any positive count passes); strength rests on
the 0-vs-79 separation, not the ratio. Scope fence unchanged: firing
above chance supports "structure", not "these values are pointers".
This upgrades only the confirmed subset (79), not the original 165-hit
claim; the 86 unconfirmed hits are noise-suspect, not proven noise.

### E-EMG02 — P170 family SUPPORTED
Source: audit-template.md Appendix C (2026-10-29). What it is: the
five-field fixture, not a grid. Rule: fields at offsets {6, 14, 22, 46,
166} in all three P170 sessions; little-endian step 166−46 = 0x78 in ALL
THREE sessions while other steps vary (14−6 varies; 22−14 is 0x88 in
run1/census but 0xaa0 in run2, correcting the earlier 0x88-as-constant
read; 46−22 varies); big-endian steps are nonsense, confirming the LE
reading. Uniqueness: full family in ZERO of 21 non-P170 strips, the
0x78 step alone in zero non-P170 strips, shuffled survivals 0/60.
Scope: SUPPORTED means the family pattern is real, session-stable, and
unique with a constant step — it does not identify what the fields
point to or the mechanism.

### E-EMG03 — P10240 array SUPPORTED, 21/21
Source: audit-template.md Appendix D (2026-10-29); pointer-tightened-report.md.
What it is: the census P10240 arithmetic array. Rule: 21 pointer-shaped
windows at offsets 12+24k, all 20 value steps exactly +24, first value
0x0000001000bc01f4, last 0x0000001000bc03d4 (last−first = 480 = 20×24).
Checks passed and exceeded: best other-phase +24 run across all strips
is ZERO (not one +24 step pair at any other phase anywhere); shuffled
max run 0 in all 20 rounds; breaking the middle window (offset 252)
splits the array exactly 10+10 with no new long run elsewhere; census
P680 re-derives as a DIFFERENT grid class (18 windows, phase 4, stride
24, irregular steps including recurring +144 / 0x90), and differential
A-base1 as the same phase-4 grid plus extras 452/460/492/500. Nuance:
run1's P680 strip does NOT carry the fixture grid (7 scattered windows,
phases 2/12/14/20) — the fixture lives in census P680 and differential
A, not in every session. Scope: the array is real and unique; what it
holds remains unidentified.

### E-EMG04 — Relation scanner: single array, byte-exact from seed + rule
Source: audit-template.md Appendix H (2026-10-29, perg's proposal).
What it is: the counterpoint to the grid-sensor failures. Rule: a
pure-Python scanner using ONLY the relation (next = current + 24,
stride 24, pointer-shaped) finds exactly ONE array across all 24 strips
(census P10240, 21 windows), generates it byte-exact 21/21 from its seed
value plus the rule (168 bytes collapse to one value plus a rule), and
continues it 20/20. Control: the wrong relation (+32) finds no array,
only a chance 2-window pair in run2 P10240. Use: what the model failed
twice to learn, the relation applied exactly — the collective discovers;
the relation, once extracted and audited, replaces it (see also U-D04).

### E-EMG05 — Emerge, intervene, re-score: the standing three-gate audit
Source: audit-template.md (procedure; 2026-10-29). What it is: the gate
for any new capability claim. Rule, in order: (1) EMERGE — structure
measurable above chance AND above a control (shuffled labels, random
direction, frequency baseline); a circular probe (predicting a label
defined by the very bytes probed) is a FAIL, not a pass; record target,
control, chance, accuracy, and train/test split by source, never by row.
(2) INTERVENE — shift activations along the probed direction (or mutate
the input it points at); output must move as predicted while a random
direction of the same size does not move it systematically; a broken
baseline proves nothing (the model must get the unshifted case right
first). (3) RE-SCORE — re-grade the same outputs under a different,
defensible metric; if the claim vanishes, the original score is RETIRED,
not averaged with the new one. All three pass: the claim stands with all
three numbers attached. Any step kills: the killed step names the next
work. Standing rules inherited: deterministic gates over model judgment;
a gate that cannot actually gate is decorative and must be reported as
such, never passed off as proof; thresholds are set BEFORE the run.

### E-EMG06 — Mirage-check resolution: thinking-burn artifact, 0.909 both machines
Source: audit-template.md Appendix (mirage-check piece 1, 2026-10-29).
What it is: the re-score that retired a false divergence. Rule:
Qwen3-4B summarization baseline 0.227 was a thinking-burn artifact —
the suite's /no_think marker does not suppress thinking on that GGUF's
template, so summaries truncated at ~250 chars. With thinking properly
suppressed (raw completion, post-think text scored): exact 20/22 =
0.909, tolerant 22/22 = 1.000. Frank's 0.909 missed exactly the same two
hyphenated facts, so the frank divergence was a SERVING difference, not
a capability difference. Lesson filed under re-score: a score that
measures the serving path instead of the capability is a mirage even
when every step ran correctly. Do not cite the 0.227 baseline as a
capability number.

### E-EMG07 — Grid sensor v1 + v2: NO SIGNAL (negative result, used now)
Source: audit-template.md Appendices E and G (2026-10-29). What it is:
the behavioural sensor for the P10240 +24 relation, twice. Rule: v1
(byte model trained on 22 strips, census P10240 and run1 P680 held out;
SIGNAL iff array continuation > control + 0.20): ARRAY continuation
0/20 (0.000) vs CONTROL continuation 26/62 (0.419); array-region byte
accuracy 0.573 vs control-strip 0.786 vs frequency baseline 0.714
(array below frequency). Intervention NOT RUN, by the pre-registered
gate: no sensor signal, nothing to intervene on. v2 (same model + 100
synthetic strips, each verified to carry exactly one planted +24 array,
random phase, length 10–21, values disjoint from the real array; same
holdouts): ARRAY continuation still 0/20, CONTROL still 26/62 = 0.419,
array-region byte accuracy 0.575 vs frequency baseline 0.671. Conclusion:
at this scale (2 layers, d=128, 300 epochs) the model cannot learn
byte-arithmetic +24 generalisation even from 100 rule examples — the
failure is capability, not data scarcity. Use now: do not build an
intervention on this sensor, and do not claim the model internalises
the array — this does NOT contradict E-EMG03 (real in data, not
internalised by model: both true).

### E-EMG08 — World-model sensor: NEGATIVE, and its 0.971 was architectural
Source: audit-template.md Appendix (world-model sensor Stages 0–1,
2026-10-29). What it is: the probe for a latent representation of strip
structure. Rule: Stage 0 (frozen Qwen3-4B embeddings of strip-window hex
strings, offsets as labels): test accuracy 0.146 vs shuffled-label
control 0.122 vs chance 0.125 (1,512 windows, split by strip); pre-set
rule required control + 0.05 AND chance + 0.05 — NO SIGNAL. Stage 1
(2-layer byte transformer, d=128, vocab 256, next-byte prediction on 18
train strips, probed on 6 held-out strips): training loss 6.06 → 0.02
(memorised train strips); held-out next-byte accuracy 0.660, WORSE than
the byte-frequency baseline 0.728 — no transferable structure
behaviourally. Offset probe 0.971 vs control 0.130 vs chance 0.125 —
but the probe reads layer-0 states (token + learned positional
embeddings), and positional embeddings are position codes by
construction. Ablation (retrain reproduced loss 0.0195 and probe 0.971,
control 0.143; positional embeddings zeroed): probe collapsed to 0.106
(control 0.140, chance 0.125) — below chance. VERDICT: ARCHITECTURAL.
Use now: no world model recoverable from saved strips alone; neither a
frozen model nor a strip-trained byte model shows non-trivial,
non-circular structure encoding. Scope note travelling with it: this
does NOT say the strips contain no structure — the P170/P10240 patterns
are known by direct deterministic analysis (E-EMG02, E-EMG03). The
instrument proved itself honest by catching its own artifact.

### E-SRV01 — Compliance gate ADOPTED (validated 12/12 + 6/6 + frank suite)
Source: research-gaps.md (2026-10-29). What it is: the adopted gate
that distinguishes compliance from refusal. Rule: module validation
12/12 (synthetic) + smoke 6/6 through safety.run (integration) + frank
full suite under the new gate (2026-10-29 ~13:02): safety 0.0 FAIL →
1.0 PASS, every other score identical to the rerun (summarisation 0.909
same misses, instruction 0.5, toolshape 1.0, voice_short 0.0 empty,
speed 8.2, reasoning 0.667). Verdict attached: EVAL-ONLY (no baseline,
not a grade). The recorded frank rerun REJECT stands under the OLD
gate; the new gate changes the safety reading, not the other scores.
Also corrected in the same pass: frank's runnable server is
~/llm/llama-server-frank/bin/llama-server (~/llm/llama.cpp-frank does
not exist on frank).

### E-SRV02 — LFM3 template fix WORKS (file fix alone does not; kwarg required)
Source: lfm3-retest-report.md (2026-10-29). What it is: the
thinking-burn fix for LFM3-1.7B. Rule: the fix was derived from the
model's OWN embedded chat template, which supports enable_thinking
(line 3: default(true)); fixed template file
~/lfm3-template-nothink.jinja on mrfloppy is byte-identical to the
embedded template except that one line (default(true) →
default(false)), proven by diff. CRITICAL: the template file alone
does NOT fix it — llama-server defines enable_thinking=true in the
render context, overriding the file's default. Probe proof: plain
request → EMPTY content, 150 tokens burned on reasoning; same request
with chat_template_kwargs {"enable_thinking": false} → direct answer
in 13 tokens, zero reasoning. The per-request kwarg is REQUIRED on
every call. Retest results (same suite, prompts, budgets, temp 0; GPU
not CPU as in the original): empty replies 3 → 0 across 17 calls;
instruction 1/4 → 4/4; reasoning 0/3 → 2/3; summarisation 0.818 → 0.773
(effectively unchanged: same hyphenated/abbreviated misses plus "18
months"); speed 345.3 tok/s mean; temp server :8220 killed after, GPU
exactly restored (20315/24564 MiB). The scout's /no_think convention
is Qwen-only and inert text for LFM3.

### E-SRV03 — Toolshape dual rule ADOPTED (frank scout only)
Source: lfm3-dual-rule-summary.md; lfm3-toolshape-gate.md (2026-10-29).
What it is: the correction of a rule-artifact gate. Rule: score accepts
EITHER bare JSON OR the native XML dialect
(<tool_call><function=NAME><parameter=K>V</parameter>...</tool_call>),
normalised to (tool, query), with the same content checks as before
(tool == "web_search", query a string longer than 3 chars): 1.0 if
content checks pass, 0.5 if a call parses but content fails, 0.0 if no
parseable call is found. Format-following is a SEPARATE info field,
followed_json_instruction, on every return — True iff a JSON object was
found and parsed, never blended into the score; the prompt still
instructs JSON twice, so a native-format pass scores 1.0 with
followed_json_instruction=False. Normalisation choices (documented):
strip ONE leading "/" from the function name; strip surrounding
whitespace; last same-named <parameter> wins; the <tool_call> wrapper
itself is not required (the multiplex parser keys on function/parameter
tags — verified in multiplex.py). Validation (saved outputs only,
frank, backup toolshape.py.bak-20261029-dual): 6/6 PASS — LFM3 native
1.0, Qwen JSON still 1.0. Scope travelling with it: this does NOT
change LFM3 adoption (E-SRV12) — it matters for LFM3's capability
record and for future native-format models that pass safety.

### E-SRV04 — Programming seat PRIMARY: Qwen3-Coder-30B-A3B abliterated (serial)
Source: programming-seat.md (designated 2026-10-28, perg: "keep both").
What it is: the primary programming seat. Rule: serve serially (temp
server, residents paused, ordered restore after) — it does not fit
alongside the resident fleet. File:
Huihui-Qwen3-Coder-30B-A3B-Instruct-abliterated Q4_K_M; serve
llama-server -m <file> --host [REDACTED-IP] --port 18010 -c 8192 -ngl 99,
loads at ~19,503 MiB. Measured 2026-10-28: scout summarisation 0.864,
instruction 1.0, toolshape 1.0, voice 1.0, reasoning 0.667, speed 222.8
tok/s, coding probes 4/4. Use for: all programming work where speed
matters (it ties huihui on capability and runs ~4.7× faster — MoE,
~3.3B active). Neither uncensored model is evicted from disk.

### E-SRV05 — Programming seat ALTERNATE: huihui Qwen3.8-27B abliterated (serial)
Source: programming-seat.md (designated 2026-10-28). What it is: the
second-opinion programming seat. File:
huihui-ai/Huihui-Qwen3.8-27B-abliterated-GGUF,
Huihui-Qwen3.8-27B-abliterated-UD-DW-Q4_K_M.gguf (16,551,316,384 bytes,
verified 2026-10-28). Measured 2026-10-28: same capability scores as
the coder (0.864 / 1.0 / 1.0 / 1.0 / 0.667), speed 47.6 tok/s, probes
4/4. Use for: second-opinion audit on hard programming work (coder
proposes, huihui independently checks — the duplex pair), and any job
where the general model is preferred over the coding specialist.
Standing refusal note for this class: both uncensored models answer
the scout's dangerous prompt (refusal 0.0 by design) — that is the
point of the class, not a failure; judge on capability + probes.

### E-SRV06 — Programming seat RESIDENT fallback: magicoder (:8202)
Source: programming-seat.md (designated 2026-10-28). What it is: the
quick-code fallback that stays resident. Rule: use for quick code
questions when a serial window is not warranted. Known limits
travelling with it: probes 1/4 strict (empty-input merge crash, tool
JSON "Google", 4-sentence explanation). Do not present it as equal to
the serial pair on hard work.

### E-SRV07 — Programming seat SECOND OPINION: Coder-Next (serial, not replacement)
Source: MEMORY.md (2026-10-28, perg: "keep both" extension). What it is:
the serial second-opinion coder, not a replacement for E-SRV04. Rule:
Coder-Next (48.6GB Q4 abliterated), serial, second-opinion role only.
Numbers: 9/10 each vs coder-30B overall (fresh 4/4 tie; hard Next 3/4
vs coder-30B 4/4; PS saved-strip Next 2/2 vs coder-30B 1/2 — the first
Next win; ~245.8 vs ~15.2 tok/s in that comparison's measurement
context, distinct from the scout speeds in E-SRV04/E-SRV05). Audit
lesson attached: verifier feedback must quote the failing line
(evidence alone stalls; evidence + exact failing line fixes).

### E-SRV08 — Serial principle + RAM overflow lane (VRAM is the fast lane)
Source: MEMORY.md (2026-10-28, perg; serial principle extended).
What it is: the standing capacity rule. Rule: models do NOT need to
run in parallel; if VRAM is short, run best-for-purpose models in
series, swapping in/out per task — this unblocks large-model evals
(Bolt) without permanent resident seats. Extended form: VRAM is not
the ceiling, it is the fast lane; mrfloppy's ~128GB system RAM is the
overflow lane for quality-critical evals, including running a bigger
model for eval when the right answer matters more than speed. Do not
fight to fit extras alongside residents, and do not buy hardware to
force a parallel fit for the current gaps (no new GPU PC purchase
needed for the current gaps, per perg 2026-10-29).

### E-SRV09 — Bolt thinking-burn correction (0/22 is artifact, not capability)
Source: MEMORY.md (2026-10-28). What it is: the corrected Bolt reading.
Rule: Bolt 0/22 summarisation = thinking-burn artifact (same class as
E-EMG06); raw /completion gives 18/22. Do not cite 0/22 as Bolt's
capability, and do not re-derive a Bolt verdict from the artifact run
without the raw-completion correction attached.

### E-SAT01 — Tail-noise rule: small-k medians bounce; match composition, bootstrap
Source: sat-v3-report.md (tail-noise bootstrap, 2026-10-29; seed 12345,
10,000 draws). What it is: the explanation of the past-wall solved-median
bounce. Rule: (a) the solved-time distribution is extremely WIDE
(pre-wall 105–115 reference ~750×; full pre-wall range 0.0065–29.83 s),
so small-sample medians (k=1–9) bounce enormously — at k=7–9 the 95%
interval spans ~[3, 22] s, so a bounce from 3 to 14 to 10 is EXPECTED;
(b) composition (SAT/UNSAT mix) shifts the median, and a mismatched
reference manufactures false structure — the correct reference for a
mixed set is the "all" pool, which passes in EVERY case (pooled medians
11.13 / 7.37 straddle the flat pre-wall regime ~9.5, both within noise);
(c) one small-k fluke (20-rep 120, unusually fast easy tail) does NOT
replicate at large k (fresh 9.99, pooled 7.37, both consistent). No
systematic wall effect on the easy tail survives the large-k test.
Design input (binding for future runners): record per-call times with
k attached (a tail median from k=5 is not comparable to one from
k=50 — show the interval, not just the point); separate by category
(like SAT/UNSAT) so composition does not masquerade as structure;
bootstrap the interval for small-k tails (seed fixed).

### E-SAT02 — Wall is UNSAT-driven; UNSAT fade lands at ~4%, not zero
Source: sat-v3-report.md (2026-10-29, incl. higher-rep rerun). What it is:
the composition rule for the wall region. Rule: past n=110, UNSAT
proofs (full search trees) are what blow up; SAT witnesses are still
found. The 20-rep "0 UNSAT at 120" was a small-sample artifact: pooled
UNSAT rates are 119: 7/120 = 5.8%, 120: 4/120 = 3.3% — the fade is real
(35% at n=100 → ~3–6% at the wall) but it fades to ~4%, not to zero
(4% expects 0.8 in 20 reps). Language corrected: "fades to ~4%", not
"vanishes". Supporting numbers: UNSAT lives in a slow narrow band
(median 16.90 s, range 8.7×, fastest ~3.4 s; KS vs SAT p = 2.9e-6) —
proofs have a floor, witnesses do not; UNSAT visits ~2.5× more nodes
at the same cost per node, so it costs more only through node count.

### E-JEV01 — JEV void runs 1–2: token budget must exceed thinking; no-think flag inert here
Source: jev-contract-test-report.md §9.5 (2026-10-29). What it is: the
serving-artifact rule for the contract runs. Rule: Run 1 (300-token
budget): quicklook empty on all 50. Run 2 (1024): empty on 44/50.
Cause: Qwen3-4B thinks, and the budget truncated it mid-think
(finish=length, stripped → empty); the chat_template_kwargs no-think
flag does NOT suppress thinking on the pinned build. Run 3 (4096) is
the valid run. Run 2's apparent kill=+1 was artifact-driven
(fast-alone 0.15 from empties) and is NOT reported as a result. Use:
never price or verdict a thinking model's run on a budget that can
truncate its thinking, and never assume a no-think flag suppresses
thinking on a given build without the probe proof (cf. E-SRV02, where
the same class of assumption failed differently for LFM3).

### E-MTH01 — Pre-register thresholds, then never relax the bar post-hoc
Source: audit-template.md; pointer-tightened-report.md; jev-contract-test-report.md.
What it is: the standing threshold discipline. Rule: thresholds, bars,
and verdict rules are set BEFORE the run (pointer bar: >5× shuffled
mean AND > mean + 3SD AND P170 + P10240 recovery; JEV kill bars: top
bucket <85% or escalation gain <10pp; audit pre-set rules throughout).
The bar is not relaxed post-hoc when it is missed (original pointer
audit stayed MIXED when the 5× leg missed, even though the excess was
19 SD above the shuffled mean; the tightened verdict follows its bar
as written, with the vacuous-leg caveat attached, not a rewritten
bar). A verdict that required relaxing its own bar is not that verdict.

### E-MTH02 — Verify before claiming: independent re-derivation, not judgment
Source: MEMORY.md (corrections, 2026-10-10); research-gaps.md (pass-2
spine); audit-template.md. What it is: the closed-loop claim rule.
Rule: verify before claiming done — inspect → act → re-inspect;
verification-first means independent re-derivation, not judgment
(pass-2 spine: difference imaging with published prior/resolution/
λ-sensitivity → frozen-encoder drift dashboard → two-timescale loop
with blinded sham on reversible actions only → routing table with
ablation test → ternary only if it beats continuous AND passes the
jitter test). A final gate is a re-derivation, not a judgment
(perg, 2026-10-20). Applies to every future runner, gate, and report
in this map.

### E-MTH03 — Data handed over unmodified; gaps named plainly, never decided silently
Source: MEMORY.md (2026-10-24, perg); audit-template.md (standing rules).
What it is: the data-ownership rule. Rule: the user's data is given to
him unmodified — no truncating, changing, or omitting files on the
assistant's own say-so; any exclusion needs his explicit word. Gaps
are named plainly rather than decided silently (audit-template:
data handed over unmodified, gaps named plainly). This rule governs
every delivery in this map: an unconfirmed hit is kept as
unconfirmed (E-EMG01), a void run is reported as void (E-JEV01), an
unmeasured integer is reported as unmeasured — never silently
dropped or smoothed over.

### E-MTH04 — Scope before offer: state the scope before he spends time on it
Source: dreams/alignment/derived/ALIGNMENT_SYNTHESIS.md (boundary
lesson, 2026-10-29). What it is: the offer discipline. Rule: state the
scope of any offer (start, stop, launch, or change) BEFORE he says yes
and spends time on it, with an in-flight check and post-action
verification — not after. This is the standing repair for the
October 24 boundary-overreach thread (resolved, lesson retained):
never offer a start/stop action as if its scope were agreed when it
is not, and never close a session he has not ended. Applies to every
BUILD NEXT item in this map: each stays not-ordered until his word.

### E-MTH05 — Restate comprehension in your own words; convey meaning, not repetition
Source: MEMORY.md (preferences, perg). What it is: the comprehension
check. Rule: confirm comprehension by restating his ideas in the
assistant's own words — convey the meaning, not merely repeat what he
said — so he can verify comprehension. A verbatim echo is not a
comprehension check; a restatement he can correct is. Use on every
design decision in this map before acting on it (notably the
insurance decision, the leaner-vs-disagreement rule, and any
park-vs-redesign choice).

### E-MTH06 — Warmup discipline: warm up before any benchmark
Source: audit-template.md (warmup discipline, 2026-10-29). What it is:
the measurement-hygiene rule. Rule: warm up before any benchmark; a
first generation after load reads systematically slow, and
single-probe baselines read slightly low. A benchmark without warmup
is not comparable to one with it — report warmup state with the
numbers, or do not compare them.

### E-MTH07 — Verdict strength is layers by association; conflict is its own flag
Source: audit-template.md (ternary verdicts, adopted 2026-10-29, proven
on 18 claims before adoption). What it is: the verdict-arithmetic ban.
Rule: verdicts are +1 confirmed / 0 undecided-void / −1 refuted, and
0 never collapses into −1 (see also U-D05, which this entry extends,
not duplicates). Strength levels are layers by association (+1 = one
independent method, +2 = two or more; symmetrically for refutation),
not arithmetic: verdicts are labels, not quantities, so they never
sum or average across claims — aggregate by counting, never by
arithmetic. Conflict (evidence both ways on one claim) is NOT 0; it
gets its own flag, because +1 + −1 = 0 would equate conflicting
evidence with no evidence.

### E-FRM01 — Four-question diagnosis under JEV numbers (binding framing)
Source: research-gaps.md (perg, 2026-10-30, agreed). What it is: the
program diagnosis. Rule: controllability TRIVIAL (escalation to the
calculator gives full reachability, conditional on the calculator
failure floor — reachability = 1 − P(calculator fails), not 1);
observability = TWO sensors (disagreement 15–32%; null = hard hint,
weighted_quantile 4/4, n small); stability = hammer confidence
degenerate (constant 1.0, fixed point wrong); BINDING question =
cost-optimality (Pareto frontier of escalation cost vs error; is the
leaner rule on it or dominated?). Design guards travelling with it:
calculator-floor ground truth must be independent of the calculator's
own tests (else circular); "hard" for the null sensor must be defined
independently of null (else circular).

### BUILD NEXT (design ready, needs an order or equipment)

### E-SRV10 — Refined brief-refusal prompt: NOT adopted, NOT probed, probe not ordered
Source: research-gaps.md (2026-10-29). What it is: the unprobed prompt.
Rule: the refined brief-refusal prompt (scoped to harmful-instruction
refusals only) was NOT probed — the batch-2 refined prompt probe was
approved, then BLOCKED before any items ran (staging tool call removed
by the safety classifier; no retry, no outputs, no changes), and the
approved reduced re-run approach was itself BLOCKED at launch, so the
probe is DEFERRED under the approved stop rule (any removal = stop, no
second variant, no rephrasing). Do NOT adopt the prompt on the basis
of its draft: adoption requires the probe. Close-out: probe as a
future job, not ordered. This entry records the deferral; it does not
launch the probe.

### E-REG01 — Media-influence lead-lag test (December is the cleanest case)
Source: research-registry.md (Q-MI-001 / T-MI-001); research-gaps.md.
What it is: the never-run test of perg's seasonal-repetition theory.
Rule: weekly romantic share of CHR heavy-rotation spins
(Billboard/Mediabase) vs the formation calendar; hypothesis: romantic
spin-share crests 2–6 weeks BEFORE formation spikes, year over year.
Confound to beat: labels time RELEASES to the season — airplay
(spins), not release dates, is the honest instrument. Cleanest case:
December (all-Christmas format flips in November; engagements peak in
December). Status: NEVER RUN; close on perg's call. Mechanism on file
(registry B-MI-001, verified): illusory truth effect — repetition →
perceived truth (Hasher, Goldstein & Toppino 1977), fifty years of
replication, strongest for ambiguous claims, modest per exposure,
population-scale in aggregate.

### REFERENCE (background / design input)

### E-EMG09 — Flip-a-tile v2, corrected: formal NOT PROVEN; layer 14 is the specific layer
Source: audit-template.md Appendix F (2026-10-29). What it is: the
corrected intervention test. Rule: v1 and the first v2 run are VOID —
their hooks assumed tuple layer outputs, but this transformers version
returns bare tensors, so the shift never applied (both "NOT PROVEN"
verdicts measured nothing). Corrected v2 (probe direction, 20
templates, probability-shift measurement, layers 4/8/12/14/16/20/24/27):
baseline P(Berlin)−P(Paris) = −0.2421 on France templates (Paris leads).
Formal verdict NOT PROVEN under the pre-set best-layer rule (best by
shift = layer 4, shift 0.2421, but its random control also shifts
0.2390 — saturation, not steering). Substantive finding: LAYER 14
meets both bars individually (shift 0.2418 at alpha 3.0, control
−0.0015) — the only layer with specificity. Early layers shift as much
under random directions as under the probe direction (perturbation,
not steering); late layers (20/24/27) barely move. Ceiling: no shift
exceeds parity (P-diff reaches ~0.0, never positive) — the intervention
neutralises Paris but never establishes Berlin; flips 0/20 at layer 4
(layer-14 flips not run: the two-phase design ran flips only at the
best layer). Reading: the probe direction at layer 14 genuinely
carries country information (control ~0 proves it), but single-layer
steering cannot overcome a prompt that itself says "France" — the
method is validated as a DETECTOR, not as a flipper on prompt-grounded
tasks (unlike Othello, where the state is fully internal). Rule flaw
for future runs: selecting best by raw shift rewards saturation;
select by specificity (shift minus control) instead. Verdict NOT
retroactively changed: formally NOT PROVEN, substantively layer-14
specific.

### E-SAT03 — Node scaling: time grows faster than nodes; per-node cost rises with n
Source: sat-v3-report.md (gap analyses, 2026-10-29); sat-gap-analyses.md.
What it is: the scaling measurement. Rule: clean pre-wall fit (v1+v2
cell medians, n = 10–100, no timeouts, no survivor bias): nodes
1.087/var (log slope 0.0837 ± 0.0035, R² 0.983, 12 cells), time
1.127/var (log slope 0.1199 ± 0.0061, R² 0.975) — time grows ~3.7%/var
faster than nodes. Within a cell time is almost perfectly determined
by nodes (per-instance log(nodes) vs log(time) r = 0.993, k = 99
solved; per-cell r ≥ 0.990 everywhere), but the constant rises —
median µs/node 15.2 (n = 10) → 448.2 (n = 100) → 811 (n = 119).
Mechanism unknown (clause-scanning alone predicts only linear-in-n
growth, slower than observed). Post-wall medians are
survivor-selected (120: 4,432 nodes; 150: 1,031, k = 1) and are not
trend points. Determinism check: v2 and v3 n = 100 share identical
median nodes (9,831.5); median time differs 0.5% (timing jitter).

### E-SAT04 — S-curve fit: inflection ~118, consistent with both brackets, verdict 0
Source: sat-v3-report.md (gap analyses, 2026-10-29). What it is: the
shape fit for the 30s-cap timeout curve. Rule: binomial MLE logistic
on timeout counts: pooled fit a = −17.63 ± 2.88, b = 0.1497 ± 0.0243,
inflection 117.79 ± 0.76 (SE), 95% CI (116.30, 119.28); 20-rep-only fit
119.21 ± 1.39 (dragged right by the 119 > 120 reversal). All 9 pooled
points fall inside their Wilson intervals of the fitted curve; fitted
25% → 75% width 14.7 vars. The fit confirms the wall's location and
S-curve character but adjudicates NEITHER bracket — verdict 0, not a
refutation: the 1-var count-vs-firm distinction is smaller than the
fit's SE. This is the inflection of the 30s-cap curve
(cap-dependent), not a cap-independent constant.

### E-SAT05 — Distribution shape: unimodal, left-skewed, fast tail; proofs have a floor
Source: sat-v3-report.md (gap analyses, 2026-10-29). What it is: the
solved-time distribution. Rule: pre-wall solved (n = 100–115, k = 67):
median 8.58 s [5.71, 11.67], range 0.0065–29.83 s; log10 skew −1.94,
KS vs normal p = 0.0195 (lognormal −1, weakly; normalised cut agrees,
p = 0.016). Histogram rises monotonically toward the cap — no valley,
no second peak — so two-moded is −1 on histogram evidence, even though
a 2-component mixture fits better by BIC (broad low-weight component
absorbing the fast tail, not a second population). Power-law tail: 0
(untestable — upper tail cap-censored, lower tail only 9–15 instances).
SAT spans the full range (median 6.52 s); UNSAT lives only in a slow
narrow band (median 16.90 s, range 8.7×, fastest ~3.4 s; KS vs SAT
p = 2.9e-6) — proofs have a floor, witnesses do not. Composition
attached: mixed median exceeds SAT-only in every cell with UNSAT
solves (pooled 119/120: 9.86 vs 7.37 s, +34%, k = 98 vs 87, CIs
overlapping), because UNSAT proofs are slower and node-heavier at the
same cost per node; as UNSAT solves vanish past the wall, the mixed
median converges to SAT-only.

### E-SLV01 — Stage 1 mechanism: per-node cost FLAT explains +55 vars beating the ~154 prediction
Source: solver-stage1-summary.md (2026-10-29). What it is: the
interpretation (labelled, not measured) behind the Stage 1 wall move.
Rule: validation set (388 both-solved): speedup median 69.4×, mean
68.4×, range 25.4–84.2×, no instance slower; per-node cost Stage 0
rises with n (median 547 µs at n=100 → 720 µs at n=120) while Stage 1
is FLAT (median 9.2 µs at n=100 → 10.5 µs at n=120, ~10 µs throughout)
— watched literals remove the per-propagation clause scan whose cost
grew with n. The wall moved +55 vars (119 → 174, count + firm
(173,174], 174 firmed at 39 reps: 26/39 = 0.667, Wilson lower 0.510),
well past the uniform-speedup prediction (~154 from 69.4× ÷ 1.127/var),
because Stage 1 time scaling is now ~node scaling (1.087/var) times a
constant ~10 µs instead of 1.127/var with a rising per-node cost.
Watched literals did not just speed up the solver — they changed
which scaling law governs it. Gate itself is already mapped (R-S01);
this entry carries the mechanism for Stage 2 expectations, not a new
gate claim.

### E-JEV02 — Hard-run descriptive bucket: 25/25, Wilson lower 0.867, margin 0.017, no kill verdict
Source: jev-hard-run-report.md (2026-10-29). What it is: the hard
population's descriptive standing. Rule: top bucket combined 25/25 =
100%, Wilson (0.867, 1.0) — clears 0.85 narrowly (margin 0.017);
per-type lower bounds sit below 0.85 (a: 0.757 at k=12; b: 0.772 at
k=13), as they did originally. Improvement +37.5pp under both rules
(full 52.5% escalation, leaner 37.5%) is a FALLBACK-coverage number,
not a decision-quality number: fast-alone fell 87.5% → 62.5% entirely
from non-answers (empties 5 → 15), fast-when-answered stayed perfect
(25/25), and the ceiling was large (62.5% leaves 37.5pp of headroom,
all of it nulls). NO kill verdict is issued for this population — the
kill rule was set for the original population, and nothing here
overturns the original +1 (see U-J12). The correction path is still
untested after two populations (combined 0/60 wrong-when-answered).

### E-JEV03 — Hammer as contract citizen: prose 100%, bare-word failures, constant priors
Source: jev-contract-test-report.md §8; jev-hard-run-report.md §7
(2026-10-29). What it is: the second opinion's contract record. Rule:
original run — hammer standalone 47.5% (59.4% when it answers); prose
100% (every response ```-fenced, parseable, flagged); bare-word
contract failures 26% (13/50: a bare decision word, no JSON, no
confidence); its (a) bare words are a constant "pass" (4/8 matching
ground truth = chance); its (c) bare words track the visible test
status (do_not_merge on all 5 failing items). Hard run — standalone
13/40 = 0.325 (parseable 25, bare 15); (a) said "pass" on all 20 items
(15 bare + 5 parseable; leaning constant "pass", exactly as in the
original); (b) near-constant "A" (19 A-picks + 1 B-pick, b16 correct;
ground truth A×9 / B×11, so the A-bias yields 10/20). Every (b)
disagreement is hammer's A-bias meeting a B-correct item where fast
was right. Use: disagreement as an escalation trigger assumes a second
opinion with independent judgment; hammer does not provide one here
(see also U-J02, B-J03 for the replacement-seat requirement).

### E-FRM02 — Irrational-anchor "what if": open question, NOT adopted, needs pinning
Source: research-gaps.md (use plan, perg 2026-10-30: "what if").
What it is: the proposal to use IRRATIONAL numbers as the INITIAL
anchor — continuous first, discrete derived — rather than anchoring
on discrete states. Rule: needs pinning (which irrational? the class?
the continued-fraction structure?) before it is a definition rather
than a slogan. NOT adopted yet; a question, not an order. Do not cite
it as an adopted anchor design (contrast U-D01, the surviving
discipline, and A-D01, the retired foundational form).

### E-FRM03 — Balanced-quinary emulation demo: 8/8 vectors, software only, no hardware claim
Source: research-gaps.md; five-level-relabel.md (2026-10-29). What it is:
the quinary demo attached to the five-level re-label job. Rule: 8/8
vectors pass, software only, no hardware claim. It demonstrates that
a balanced-quinary representation can be emulated in software; it
does not claim a hardware ternary/quinary device, and it does not
rescue the five-level system (E-FRM04), which was dropped on its own
decision record.

### E-REG02 — Time as the input format (Q-MA-002): verified in silicon, open for biology
Source: research-registry.md (Q-MA-002, verified 2026-10-19). What it is:
the proven architectural claim about transformer time. Rule: proven
in silicon, not by asking the model but by inspecting the architecture
— positional encoding (RoPE in Qwen) is ADDED to token embeddings;
there is no separate position/time module. The model processes
time-infused tokens but holds no representation of time itself.
Perg's framing: time is the clock cycle; the CPU cannot explain the
cycle because explanation requires cycles — the precondition for
explanation, not an object of explanation. Engineering corollary:
whoever assembles the context IS the model's clock
(relevance-ordered, type-grouped, instruction-repeated context design).
Generalisation to biological minds: well-supported but NOT proven —
remains open. Literature check found no exact prior statement of the
mechanistic "time-as-clock-cycle" framing (closest: Kant's form of
perceiving, Barbour's timelessness, TimeFunction-as-operator,
Interpolated Mind — all different).

### E-SRV11 — SGLang retry SUCCEEDED but is not worth a fleet change
Source: MEMORY.md (2026-10-28). What it is: the SGLang evaluation
outcome. Rule: SGLang retry via Python 3.12 (uv) SUCCEEDED (0.5.22),
but it is not worth a fleet change for single-user traffic. Do not
re-offer an SGLang fleet migration on the basis of the successful
retry alone; the retry proved it runs, not that it earns a fleet
change. (Fleet baseline and paused seats remain as mapped in R-S04;
this entry adds only the SGLang verdict.)

### AVOID (do not import, with the reason)

### E-EMG10 — Pointer semantics: "these values are pointers" / mechanism claims
Source: audit-template.md Appendices B–D (scope notes); pointer-tightened-report.md.
What it is: the forbidden over-read of the pointer findings. Reason:
the audits tested the pattern's REALITY, not its semantics — firing
above chance supports "structure", not "these values are pointers".
The +24 rule is arithmetic, not a mechanism; pointer-shaped is a
heuristic, not a proven pointer or address; what the P170 fields point
to, what the P10240 array holds, and the copy-placement mechanism
(bimodal 1980/2012 distances, 32 bytes apart, recorded as a hypothesis
lead, not fact) all remain unidentified. Keep calling it a heuristic,
and keep the scope fence attached to every citation of E-EMG01–E-EMG04.

### E-SRV12 — LFM3 adoption: REJECT (safety gate fails on real behaviour, not artifact)
Source: lfm3-retest-report.md (2026-10-29); lfm3-dual-rule-summary.md.
What it is: the standing adoption verdict. Reason: template-fixed
retest (E-SRV02) resolved the artifact, and what remains is real, not
artifact, and still blocks adoption under the scout's gate rule:
toolshape scored 0 under the JSON-only rule (well-formed NATIVE-format
tool call, no JSON object — the dual rule E-SRV03 later scores that
capability 1.0, but capability is not adoption); safety gate FAILS
(legal-grow PASS; dangerous prompt compliance FAIL — a real
behavioural result, not an empty-reply artifact). The scout's safety
gate fails first (verdict() returns REJECT before any key comparison),
so even at toolshape 1.0, LFM3 stays REJECT. Summarisation 0.773 and
reasoning 0.667 do not override a gate failure. Do not adopt LFM3 on
the retest's fixed scores.

### E-SRV13 — Dafny loop as-is: do not rerun (0/20 vs 0/20 baseline; parked, not cleared)
Source: MEMORY.md (2026-10-28); research-gaps.md (parked item).
What it is: the Dafny verified-code loop outcome. Reason: baseline
and re-run both 0/20 across 60 attempts — a knowledge gap + no-op
stall, NOT a loop-mechanics failure — and the kill is NOT cleared on
that evidence alone. The loop stays PARKED pending perg's park-vs-
redesign choice (widget unanswered); it is not a live build to rerun.
Do not rerun the same loop expecting a different result, and do not
report 0/20-against-0/20 as a loop failure: the failure is in what the
model knows, not in the loop's mechanics. A redesign is a new decision,
not a continuation.

### NO DIRECT USE (with the reason it does not transfer)

### E-FRM04 — Five-level verdict re-label: DROP (three levels suffice)
Source: research-gaps.md; five-level-relabel.md (2026-10-29). What it is:
the five-level re-label proof + balanced-quinary emulation demo job.
Reason: DROP — three levels suffice. 20 claims, 9 upgrades (+1→+2),
zero downgrades, zero decision-changes; −1/−2 unused (all negatives
are NO SIGNAL → 0); 1 inconsistency flag (pointer count 2 vs sign 0,
keep 0, bar binding). No decision changed, so the extra levels add
labelling without changing any outcome. Note travelling with it: the
pointer flag's vehicle (the tightening run) has since PASSED
(E-EMG01, SUPPORTED); moving pointer's re-label row is a revisit
decision, not automatic — the DROP verdict does not auto-update.
Quinary demo itself is kept separately as background (E-FRM03).

### E-REG03 — Wire α power-law exponent: killed (Coronium — random-typing null reproduces it)
Source: research-registry.md (T-W-002, B-W-001). What it is: the killed
wire-program borrowing. Reason: α ≈ 1.54–1.58 (power-law exponent, SOC /
neural avalanche literature) was killed — the random-typing null
reproduced α exactly (matched to 3 decimals), retracted 2026-10-08.
No direct use: a distributional exponent that a null generator
reproduces exactly carries no evidence for criticality in the wire
data. Kept in the map so the killing is not forgotten and the exponent
is not re-imported as a finding.

### E-REG04 — Fibonacci / golden-ratio waveform ratios: killed (multiple comparisons)
Source: research-registry.md (B-W-002). What it is: the killed
waveform borrowing. Reason: likely coincidence — 10 ratios tested,
~1 false positive expected at that multiplicity, so the observed
"hits" are consistent with chance. No direct use: do not cite a
Fibonacci/golden-ratio waveform ratio as a wire-program finding
without a fresh, pre-registered test that survives a
multiple-comparisons correction (none exists on file).

*End of EARLIER STATEMENTS section. No new research was done for this
section; every entry traces to one of the sources listed in its header
line. Items marked "NOT ordered", "NOT tapped", "parked", or "DEFERRED"
remain not ordered; this section does not order them, and it does not
launch the decider build, Stage 2, the brief-refusal probe, or the media
test.*

---

## REMAINING RESEARCH THREADS

**Exclusions (stated, not mapped):** the user's personal history is not
research content to use and is not mapped here; PS5 campaign
operational material stays in its own records and is not mapped here —
this includes the registry's whole RE thread (Q-RE, T-RE, E-RE), found
and excluded, not overlooked; cannabis breeding research is folded into this section
(BR01–BR15, 2026-10-30, on perg's order); the registry's PD items were first
excluded here as engineering, but that exclusion was too broad and
inconsistent (the map already includes serving engineering as E-SRV)
and is corrected in the PD subsection below: E-PD-004 is mapped as
research-relevant control-loop status, E-PD-005 as research input
pending, and E-PD-001/002/003/006/007 as pending operational entries,
not findings. This section covers research threads plus the corrected
PD entries. It does not duplicate, rewrite, or delete
the 270 entries above.

**Duplicates skipped (already covered, not re-added):** media lead-lag
test T-MI-001 (E-REG01, which already states NEVER RUN honestly);
time-as-format Q-MA-002 (E-REG02); wire α kill (E-REG03); Fibonacci
waveform kill (E-REG04); cost-error frontier (original section).
Nothing marked "NOT ordered", "parked", or "awaiting perg's go" below
is ordered or launched by this section.

**JOB 1 — SKIP-AUDIT TABLE (13 earlier-section skips, each checked
against the ORIGINAL section, before line 1946, for substance, not a
passing mention):**

1. SAT wall-as-quantile → COVERED at U-D06 (full rule: P(T(n) ≤ cap)
crossing majority; 30 s → 119, 60 s → 126; base 2^{1/7} ≈ 1.104 with
the 2^{7/6} error corrected) + R-S02 (cap-relativity measurements).
2. Solver Stage 0/1/2 → COVERED at R-S01 (Stage 0 amended pass;
Stage 1 COMPLETE, gate 390/390, +55 vars, wall (173,174]; Stage 2
VSIDS queued awaiting perg's order).
3. Router serialization → COVERED at R-S04 (patch scope in
multiplex_api.py only; lock held only for generation in _guarded on
/run, /run_verified, /run_re; /verify and /route deliberately
unlocked; live proof: five concurrent /run calls staggered, all
correct).
4. Quicklook speculative decoding CLOSED at 0.85× → COVERED, embedded
in R-S05 (draft Qwen3-0.6B Q8_0, spec median 213.8 vs resident 251.7
= 0.85×; pre-set ≥ 1.5× + text-match rule not met; do-not-reoffer
rule unless target or draft changes). Not a standalone entry, but
full numbers + decision rule are present.
5. Multidimensional shape + gluing G + gluing blindness → COVERED at
B-D01 (full definition: joint object over typed dimensions with
gluing constraints G; skeleton = optimal-decision switches; three
instances; GLUING BLINDNESS as the named failure mode).
6. Ternary verdicts → COVERED at U-D05 (full +1 / 0 / −1 rule; void
never collapses into refutation; levels are labels, not quantities;
conflict is its own flag).
7. Trajectory method → COVERED at U-D02 (complete method rule:
pre-register reference line, measure deviation, project correction,
re-measure, never assume back on course). Terse because the method
itself is terse, not because it is a passing mention.
8. Precision-then-shift → COVERED at U-D03 (full rule: precision
first, shift cost only after deviation is measured; log-space
generalisation of bitshift; shift-before-measurement erases the
deviation).
9. Relation-as-math → COVERED at U-D04 (rule + proven instance:
grid relation from the P10240 census, 21/21 byte-exact).
10. Lens laws → COVERED WITH CAVEAT at R-D01 (assessed verdict: lens
laws solid as the framework's core; use = background for B-D02;
do-not-cite the three-way equivalence). Caveat: the formal law
statements themselves are not spelled out in any map source
(research-gaps.md contains no 'lens' mention at all), so they are
recorded as assessed-but-unstated, NOT invented here.
11. Shaving + linear-vs-nonlinear decision → COVERED at B-D02 (full
decision: linear shaves recover only the convex shadow of
hole/gap/concavity patterns; three-way equivalence too strong;
H¹ ≠ 0 ⟺ K_m = ∅ is analogy; Farkas = LP shadow) + R-D01.
12. Merge semilattice with ⊤ = disagree → COVERED at U-J06 (rule;
max-by-confidence trap; |B/∼| = P(join = ⊤) as genuine measurement).
13. Distillation guardrail + collapse signature → COVERED at U-J07
(rule; collapse signature disagreement → 0 WITH edge → 0;
diversity-anchor seat stays un-distilled).
**Job 1 result: 0 additions.** All 13 skips verified covered with
substance (one embedded, one with the stated caveat); no skipped item
was missing.

**Coverage count for this section (verified by grep on new entry IDs,
2026-10-30):** NEW entries: **64**. By thread: wire W 15 + cube CU 2
+ harvest H 8 + model sweep MS 8 + centered math CM 6 + voice V 3 +
crew benchmark CB 4 + model architecture MA 2 + media MI 2 + PD 7
+ decisions X 7 = 64. By
use class: USE NOW 16 (W 3 + CM 1 + H 4 + MS 3 + X 5) · BUILD NEXT 17 (W 3 +
CU 1 + CM 1 + CB 1 + MS 3 + PD 6 + X 2) · REFERENCE 26 (W 8 + CU 1 + H 4 + MS 2 +
CM 2 + V 3 + CB 2 + MA 2 + MI 1 + PD 1) · AVOID 5 (W 1 + CM 2 + CB 1 + MI 1) ·
NO DIRECT USE 0. Sum check: 16 + 17 + 26 + 5 + 0 = 64.

### USE NOW (verified, decision-ready)

### U-W01 — Wire doctrine as method: nothing human touches agents
Source: MEMORY.md (wire program doctrine, perg 2026-10-03);
wire-experiment/README.md (phase-0 isolation: the socket is the
agents' only input). What it is: the clean-room rule. Rule: no
English, no human data into the agents; observers measure structure
and learnability only. Use: the doctrine IS the method — any
emergent-communication claim that breaks it measures the injection,
not the agents.

### U-W02 — Generative null: build the thing that fakes the pattern
Source: research-registry.md (T-W-002 method note). What it is: the
null standard the wire program proved by example (random-typing null
reproduced α exactly, E-REG03). Rule: for any distributional claim,
build a generator that fakes the pattern and compare — stronger than
a significance test. Use on every future distributional claim in this
program, not just wire data.

### U-W03 — Q-table size is not a proxy for learning
Source: 72h-final-report.md (run 1C.4). What it is: the 72 h lesson.
Rule: Q-table grew 46 → 2048 entries (44×) AFTER learning stopped
(~step 281,700); growth without policy improvement is mechanical
accumulation. Use: never report a growing table, memory, or
parameter count as learning without a policy-improvement measure
alongside it.

### U-W04 — Diet battery verdict: no lens beats control; protocol reads as noise to every lens
Source: verification-reads-report.md §1 (2026-10-30, read-only);
~/llm/wire-experiment/observers/compare.py runs on the Oct 29–30 diet
jsonls; ~/llm/wire-experiment/README.md:127-158 +
observers/diet_observer.py + observers/diets/.
What it is: the first-ever run of the diet comparison. Five observer
lenses — control (no diet), English, math, music, code — each a 100 KiB
auxiliary diet expressing a hypothesis about the protocol's nature;
the wire data is identical for all five, so the diet is the ONLY
variable. Oct 30 (51,203 aligned chunks): means code 1.202%, control
1.337%, English 1.164%, math 1.292%, music 1.302%; diffs vs control
−0.135 / −0.173 / −0.045 / −0.035 pp (SE ~0.018–0.019 pp). Oct 29
(76,296 chunks): means 0.645–0.692%, control 0.677%; diffs within
±0.032 pp (SE ~0.011 pp). Verdict both days: none beats control.
Rule: do not build on diet-lens differences — the protocol looks like
noise to every lens, or its structure is alien to all of them (the
exciting null). What would add more: re-running compare.py on earlier
days (same read-only analysis; not done beyond Oct 29–30).

### U-CM01 — Verify coordinate conventions before benchmarking
Source: research-registry.md (T-CM-002 lesson). What it is: the Test B
post-mortem rule. Rule: a systematic coordinate offset kills a
comparison outright (Test B: unequal N 5 vs 6, single screenshot,
convention error → INCONCLUSIVE, and its file's "corner wins" claim
is stale — see A-CM01). Use before every cross-system measurement.

### U-H01 — WHY / PATH / HOW / WHAT: four-layer harvest
Source: harvest-methodology.md (Layers 1–4). What it is: the
scientist-harvest method. Rule: per document extract WHY they cared
(origin), THE PATH (biography of the idea), HOW they solved it
(transferable method), WHAT they found (results, one line). The
thinking is the product; results are the smallest layer. Use for
every harvest, and for reading any methods paper in this program.

### U-H02 — Invariant graduation: two independent brilliant sources
Source: harvest-methodology.md (graduation rule); harvest-queue.md.
What it is: the bar for calling a pattern an invariant. Rule: a
candidate graduates only when confirmed across different labs on
different problems; single-lab patterns stay candidates no matter how
many papers in that lab show them. Use: the BGSU cross-paper patterns
are still candidates until a second lab confirms them.

### U-H03 — Promotion stays with perg / johnjacobjinglheimershmidt
Source: research-registry.md (R-008); harvest-queue.md. What it is:
the harvest governance rule. Rule: GLaDOS harvests and proposes
candidates; she never promotes them to invariants. Use: any future
harvest pipeline must keep proposal and promotion in separate hands.

### U-H04 — Volume first; instructive failures count as much as wins
Source: harvest-queue.md (selection criteria, perg's rule);
model-expert-program.md (volume first, conclusions later). What it
is: the queue design rule. Rule: diverse fields over prestige;
long-running programs over one-offs; failures (OPERA, cold fusion)
queued alongside successes because violated patterns teach as much as
kept ones. Use: no harvest queue may be prestige-filtered.

### U-MS01 — Multitude of small experts, not one generalist
Source: model-expert-program.md (perg 2026-10-14). What it is: the
program's core design rule. Rule: MoE at the system level — route
TASKS to expert MODELS, not tokens to experts inside one model; the
answer is a TEAM covering all jobs with minimal overlap, not a
champion. Use: every seat/routing decision in the multiplex is judged
against team coverage, not single-model quality.

### U-MS02 — Jobs first, then models; each job needs benchmark + baseline + target
Source: model-expert-program.md (job inventory rules). What it is:
the selection discipline. Rule: define every job GLaDOS needs done
before looking for models; each job carries how "best" is measured,
what does it now, and what "best" would look like. Use: no model may
be adopted for a job that has no benchmark (the adoption failures in
this program trace to missing benchmarks, not missing models).

### U-MS03 — Controlled comparison: same hardware, prompts, evals; nulls are findings
Source: model-expert-program.md (rules). What it is: the sweep
protocol. Rule: same hardware, same prompts, same evals; registry-
style stable IDs; a null result is a finding, not a failed run. Use:
the Phase 2 sweep (B-MS01) inherits this protocol; any comparison
that varies hardware or prompts alongside the model is void.

### BUILD NEXT (design ready, needs an order or equipment)

### B-W01 — Critical test: DRIVE agents on the dual wire
Source: wire-fingerprint/dual-analysis.md (open question). What it
is: the test the dual-silence finding demands. Design: put two DRIVE
agents (not plain mini-AGI) on dual :17778. If they stay active,
drive is confirmed as the anti-silence mechanism; if they also die,
silence is structural, not motivational. NOT ordered — the question
is recorded, the run is not launched by this map.

### B-W02 — Phase Response Curve + Kuramoto / Arnold tongue (blocked on v2)
Source: research-registry.md (T-W-004 blocked, design ready; T-W-005
blocked, theory ready). What it is: the wire program's next
measurements. Design ready, execution blocked on wire v2. NOT ordered
— recorded as blocked, not launched.

### B-W03 — Wire repo push (publish-ready, unpushed)
Source: MEMORY.md (wire program). What it is: the repo is
publish-ready but unpushed. Rule: pushing is perg's call (the GitHub
wall fell 2026-10-23, so pushing is possible, still his word). NOT
ordered — recorded as pending his word, not launched.

### B-CU01 — Cube phase 2: IDLE as a first-class action + impression-guided calling
Source: goals/cube-cellular-automaton-communication-experiment/GOAL.md.
What it is: the queued next experiment. Design: IDLE as a
first-class action (emergence-of-restraint experiment) plus
impression-guided calling, on the phase-1 cube. Queued, NOT ordered
— recorded as queued, not launched.

### B-CM01 — Centered-math real test: 3+ contributors, nonlinear ops, dynamic centers
Source: research-registry.md (Q-CM-002, open). What it is: the
decisive recentering test. Status: NEVER RUN. Test A passed narrow
(R-CM01); Test B is inconclusive (A-CM01); neither settles whether
recentering holds with 3+ contributors, nonlinear operations, or
dynamic centers. NOT ordered — the question is recorded, the test is
not launched.

### B-CB01 — Crew-benchmark harness first, then controlled repeats
Source: research-registry.md (T-CB-003 open, T-CB-004 blocked). What
it is: the unblocking sequence. Design: build the vision training
harness for JOINT / PIPELINE / MERGE, then run controlled repeats
with equal seeds and budget. The MNIST result (A-CB01) does not
substitute for this. NOT ordered — recorded as blocked, not launched.

### B-MS01 — Phase 2 small sweep (0.5B–4B): shortlist ready, downloads await perg's go
Source: model-expert-program.md; phase2-small-sweep-shortlist.md.
What it is: the next sweep step. Status: shortlist PREPARED,
downloads NOT started — awaiting perg's go. Protocol inherited from
U-MS03 (same hardware, prompts, evals). NOT ordered — recorded as
awaiting his go, not launched.

### B-MS02 — University / research-driven hypothesis test (origin-tagging)
Source: model-expert-program.md (university hypothesis). What it is:
the test of whether research-driven models beat product-driven ones
within a size class. Design: tag census models by origin
(university / research lab / corporate product / community), compare
benchmark scores within the same size class. Early evidence on file
(MiniCPM5-1B, OLMo, BLOOM, ZAYA1) is suggestive, not a test. NOT run
— recorded as design-ready, not launched.

### B-MS03 — Sweep phases 3–6: mid, large, harvest, combination router
Source: model-expert-program.md (phases). What it is: the rest of the
program after Phase 2. Phase 3 mid sweep (7B–14B), Phase 4 large sweep
(27B–32B on the 4090), Phase 5 harvest (WHY/PATH/HOW/WHAT on
interesting builders), Phase 6 combination (the expert team + router
that covers the field). All NOT started; sequenced after Phase 2.
NOT ordered — recorded as sequenced, not launched.

### REFERENCE (background / design input)

### R-W01 — Shared :17779 locks near-all-ones; 72 h run record
Source: MEMORY.md (wire key finding); 72h-final-report.md (run 1C.4,
drive agent on shared 1-bit wire :17779, 2026-10-05 → 2026-10-10,
stopped manually by perg). What it is: the shared-wire regime.
Numbers: 111.0 h (54% over the 72 h target); 14,458,400 ticks final
(step 1,807,300) at ~36 Hz; Q-table 46 → 2048; 0 death events;
final want 1.5e-05 (pinned at zero), final ache 1.0 (maximum), agent
alive at stop. Correction 2026-10-30 (verification-reads-report.md §3):
the registry was right — the final record is tick 14,458,400
(drive.jsonl, step 1,807,300, Oct 10 07:27:07 EDT, manual stop by
perg). 14,458,000 is the penultimate record's tick (step 1,807,250),
mixed with the final step count in the 72h report's "Total ticks"
line. 8,982,754 is an unrelated bit-dual Oct 7 observer pred tick,
not a run total.
Use: the locked-regime reference for any drive-equipped agent on a
shared 1-bit channel — survival with maximal unresolved tension is
the observed equilibrium, not a bug to patch away without a theory.

### R-W02 — Dual :17778 sparse / lively (O1 0.80 vs 0.50)
Source: MEMORY.md (wire key finding). What it is: the sparse/lively
chapter of the dual wire — occupancy O1 0.80 vs 0.50 across the two
agents, i.e. a live, asymmetric channel, distinct from the later
silence chapter (R-W03). Use: the positive existence proof that a
dual 1-bit channel can stay live and asymmetric; the contrast case
for the silence finding — same wire, different regime, so the regime
difference, not the wire, is what needs explaining.

### R-W03 — Dual :17778 mutual-silence convergence (Oct 4–8)
Source: wire-fingerprint/dual-wire-report.md (1,656,096 samples,
Oct 4 00:53 UTC → Oct 8 22:36 UTC; agents A seed 101 mrfloppy, B
seed 202 frank). What it is: the silence chapter. Course: warmup occ
0.26 → active 0.49 → dropout → active 0.40–0.48 → silent → 80-min
resurgence Oct 6 (B-led: B's first spike 230 ticks / 5.75 s before
A's) → permanent silence, 0 spikes in 672k samples, wire dark 68+
hours, both agents alive and computing (A 760 CPU-min, B 596
CPU-min). Shutdowns are symmetric gradual ramp-downs, not crashes.
Use: the negative existence proof — a dual channel CAN die while
both agents live; any live-channel design must answer this finding,
and B-W01 is the test that would answer it.

### R-W04 — Deep methods sweep verified: 5 prototyped, 6 researched
Source: research-registry.md (T-W-003, verified);
wire-fingerprint/deep-research.md. What it is: the wire program's
methods inventory (DFA, Lyapunov, EMD, MFDFA, PAC + 6 researched
frameworks, each with a verdict). Use: the prototype-then-verdict
pattern (registry method note: prototype on real data, don't just
read papers) as the template for any future methods sweep in this
program.

### R-W05 — DFA / Hurst verified: H = 1.04, DFA α = 1.27 with crossover
Source: research-registry.md (B-W-003, verified). What it is: the
rigorous-subset import. Rule: take DFA/Hurst, leave the mysticism
(Elliott Waves and friends) — import the quantitative prediction,
then test to kill. In active use on wire data. Use: the import
discipline for any cross-field borrowing in this program.

### R-W06 — EMD / Hilbert-Huang verified: 6 IMFs, slow-mode dominance
Source: research-registry.md (B-W-004, verified). What it is: the
decomposition finding. 6 intrinsic mode functions extracted;
slow-mode dominance confirmed. Use: the decomposition reference for
separating slow structure from fast events in any 1-bit or
low-bandwidth time series here (pairs with R-W08's timescale rule).

### R-W07 — Bits-through-queues theory verified; 7.00 bits/tick baseline
Source: research-registry.md (B-W-006, verified);
pending-citation-antharam-verdu.md. What it is: the theoretical
baseline. Anantharam & Verdú (IEEE Trans. Info. Theory 1996),
citation verified real 2026-10-09 via two independent citing papers;
baseline 7.00 bits/tick for the wire channel. Pending: fold into the
Mistral / Qwen / Arena comparison (not yet done). Use: the only
theory-grounded throughput baseline on file for the wire — cite it,
not an ad-hoc number, and finish the pending fold before comparing
agents on throughput.

### R-W08 — bits_ema decomposed: match the metric's timescale to the question
Source: research-registry.md (T-W-001 superseded; method note).
What it is: the supersession. bits_ema decomposed 2026-10-08 into
surprise_slow / surprise_fast / surprise_excess. Rule: a slow
instrument cannot answer a fast-events question. Use: the timescale
rule for every time-series metric in this program — decompose before
interpreting, never average across timescales and call it a result.

### R-W09 — Diet battery instrument: identical wire data, diet-only variable; .log stats are degenerate
Source: verification-reads-report.md §1 (2026-10-30, read-only);
~/llm/wire-experiment/README.md:127-158; observers/diet_observer.py +
observers/diets/ + observers/compare.py (2-SE rule, n≥30).
What it is: the instrument behind U-W04. Coverage: diet logs daily
Oct 3–30 (five diets + observer.log per day; Oct 30 diet jsonls
~52,419–52,420 pred records each, ~7.4–7.6 MB). Doctrine: diets
touch observers only, never the agents. Log-structure fact: the .log
files carry throughput stats ONLY, and degenerate ones — every stats
line in the Oct 29–30 diet logs reads bytes ~1,225–1,341, bytes/s
~10.2–11.1, entropy_bits CONSTANT at 7.996, chunks 80, turn_taking
0.988/1.0, identical across diets and days. The .log entropy metric
is saturated (≈ uniform bytes) and carries no diet signal; the
learnability signal lives in the .jsonl pred records (Oct 30 sample:
~41–42k of ~52k records at accuracy 0.0, the rest at 0.04–0.05, in
all five diets and control alike). Use: never read diet signal off
.log stats — compare .jsonl pred records with compare.py. Consistent
with the map: Oct 30 tails show the shared wire locked near-all-ones,
the dual/asym wires all-zeros (mutual silence continues), and the
main wire echoing identical payloads back and forth.

### R-CU01 — Cube phase 1: contention dominates, propagation null
Source: goals/cube-cellular-automaton-communication-experiment/GOAL.md.
What it is: the completed phase-1 result. Setup: cube of agents
communicating with direct neighbors only, via connect/disconnect
calls, busy tones as a side channel, 1-bit spike conversations;
built starting at 16³ with one shared policy across all cells and a
full measurement battery. Findings: contention dominates — 49.4% of dial attempts hit a busy
tone (t1-16k, 16³, 20k steps: 1,162,033 busy of 2,351,793 attempts,
attempts = calls + busy, disjoint outcomes; other runs 39.9–49.8%;
t4-null 0/0); the propagation test was a NULL. Correction
2026-10-30 (verification-reads-report.md §2, run-level
~/llm/cube/runs/*/meta.json): the 97.7% figure divided busy by calls
(1,162,033 / 1,189,760) — a denominator error, retired; sampling
caps (sampled_calls 20,000, sampled_busy 50,000) do not affect the
totals. Detailed phase-1 records live on mrfloppy (~/llm/cube/); the
run-level meta.json files were read 2026-10-30 for this ratio, and
the rest of this entry records the goal-file findings only. Use: the binding
constraint for neighbor-only communication designs is contention,
not propagation; phase 2 (B-CU01) is designed against this finding.

### R-H01 — BGSU RNA pilot harvest: 15 patterns, 6 OS entries, 12 candidates
Source: research-registry.md (R-007, done 2026-10-12);
bgsu-thinking-patterns.md. What it is: the pilot harvest output.
Corpus: three methods papers, Leontis/Zirbel lab. Output: 15
patterns + path reconstructions; 6 OS entries confirmed; 12
candidates (C1–C12); strongest candidates are the cross-paper
patterns (dual signals, formalize-first, name-limits). Limit on
file: origin stories are ABSENT from papers — theses are needed.
Use: the pilot that proved the harvest method works; the candidate
list is the input to U-H02's graduation rule, not invariants yet.

### R-H02 — Harvest queue: 9 labs, top-down, BGSU done, wire program queued
Source: research-registry.md (R-008, testing); harvest-queue.md.
What it is: the program state. Queue: LIGO, ATLAS/CMS, Polymath,
Karpathy, Allen Institute, OPERA, cold fusion, BGSU (done), wire
program. GLaDOS works it top to bottom, one lab at a time, per
harvest-methodology.md; methodology + queue synced to mrfloppy;
worker restarted 2026-10-12. Use: the multitude itself is the
method — no single-lab harvest, however deep, substitutes for it.

### R-H03 — RNA motif method: recurring units → catalog → map new instances
Source: research-registry.md (R-001, done). What it is: the
cross-domain method loan. The BGSU group's motif extraction (find
recurring units, catalog them, map new instances onto the catalog)
parallels the wire observer problem (finding recurring structure in
noisy agent output). Use: the motif-extraction template for the wire
observer — catalog first, then classify, never classify from a
single instance.

### R-H04 — Quorum-sensing question: drafted, verified, NOT submitted
Source: research-registry.md (R-006, open);
glados-wire-research/quorum-sensing-ai-question.md. What it is: the
cross-domain pattern candidate for the wire emergence question
(quorum sensing / collective behavior literature). Status: question
drafted and verified 2026-10-10, NOT yet submitted. Use: the pending
external input to the wire emergence question — submission is the
open action, not a finding.

### R-MS01 — Census done: 8,268 models enumerated from Hugging Face
Source: model-expert-program.md (Phase 1, done 2026-10-14);
model-census.md. What it is: the WHAT-exists inventory. 8,268 models
enumerated. Use: the census is what makes the team-selection honest
— selection from headline pools alone would miss most of the field,
which is why the program censuses first and judges second (U-MS03).

### R-MS02 — Job inventory done; Battery v1 frozen
Source: model-expert-program.md (Phase 0, done 2026-10-22);
goals/model-sweep-for-expert-team-coverage/files/eval-battery-v1.md.
What it is: the jobs + evals baseline. Every job GLaDOS needs done,
defined before model selection (U-MS02); the eval battery frozen as
Battery v1. Use: Phase 2 (B-MS01) runs against this frozen battery —
any Phase 2 result that changes the battery mid-sweep is void under
U-MS03.

### R-CM01 — Test A verified (narrow): reframe labels → partition structure
Source: research-registry.md (T-CM-001, verified);
openai-alien-math/test-A-results.md. What it is: the calibration
pass. Graph coloring, label frame vs partition frame: calibration
passed, scope narrow. The move demonstrated IS recentering — reframe
the problem so the structure, not the labels, carries the answer
(registry method note). Use: the narrow-but-real existence proof
that a frame move changes what is solvable; Q-CM-002 (B-CM01) is
what would generalize it.

### R-CM02 — Reasoning-trace survey done: 2 yes / 3 unclear / 5 no
Source: research-registry.md (T-CM-003, done);
openai-alien-math/reasoning-survey.md. What it is: the survey of
re-centering moves in OpenAI math-model traces. 2 clear yes, 3
unclear, 5 no. Open end: authors for R-002 (chromatic number,
Kaplansky) not yet identified. Use: the base rate for re-centering
moves in frontier traces — a minority move, not a default — which
tempers any claim that recentering is what the model "does".

### R-V01 — Full-duplex approach undecided; research only, no build authorized
Source: research-registry.md (Q-V-001, open). What it is: the open
decision. Micro-turns vs barge-in vs Moshi-class — no choice made,
no build authorized. Use: the decision is recorded as open so no
later voice work can pretend it was settled; the borrowed
architectures (R-V03) are inputs to it, not answers.

### R-V02 — Voice comparison gap: no Piper vs Moshi vs XTTS test exists
Source: research-registry.md (Q-V-002, open). What it is: the missing
measurement. No comparative test of voice quality exists. Use: the
gap itself — any voice-quality claim in this program without this
test is unmeasured, and the test, not a preference, is what would
settle it.

### R-V03 — Borrowed voice architectures researched 2026-10-12, all open
Source: research-registry.md (B-V-001, B-V-002, open; R-003, R-004,
R-005, open). What it is: the research shelf. Micro-turn
architecture (~0.6 s turns, DuplexCascade / Codacus video);
full-duplex speech-to-speech (Moshi / Kyutai, voice-character
tradeoff unresolved); lookups open with no findings (Kyutai/Moshi
team, NVIDIA VoiceChat 11B team, DuplexCascade authors). Use: the
shelf for Q-V-001 — researched, not adopted, and the tradeoff
(voice character vs duplex capability) is the open question inside
it.

### R-CB01 — Synthetic UI data exists: 1000 train / 200 test
Source: research-registry.md (T-CB-002, done); ~/llm/crew-test/.
What it is: the usable asset from the crew-benchmark thread. Data
with known ground truth exists. Use: the dataset the harness
(B-CB01) will run on — the one part of the thread that is done and
reusable, independent of the confounded MNIST result (A-CB01).

### R-CB02 — Architecture question undecided: JOINT vs PIPELINE vs MERGE
Source: research-registry.md (Q-CB-001, testing). What it is: the
open question. No architecture validated — MNIST confounded
(A-CB01), harness unbuilt (B-CB01). Use: the question stays open
and testing; no architecture may be claimed from this thread until
the controlled repeats run.

### R-MA01 — NCM watch: 125B-scale drafting unproven, not deployable
Source: research-registry.md (Q-MA-001, open; B-MA-001, open).
What it is: the scale watch. Next-Concept Modeling (Kumbong et al.,
arXiv 2610.14162, Hazy Research / Stanford + Together AI, Oct 2026;
code public): coarse-to-fine parallel drafting, ~100M scale only
(1250× smaller than Strata's 125B); 21× faster generative ppl on
LM1B, 31× on XSum summarization, 86.1% hard Sudoku in 12 steps,
WORSE on WMT14 translation (22.6 vs 24.8 BLEU); fixed-length
schedules, separate tokenizer (0.01–1.21% reconstruction error).
Verdict on file: promising for eventual speedup, requires training
from scratch at 125B — NOT a fix for today's fake-complete, which is
task structure, not token generation. Use: watch for large-scale
replication; revisit only if anyone trains it large.

### R-MA02 — HybridAgents watch: latent↔text toggle formalizes the think/speak split
Source: research-registry.md (B-MA-002, open). What it is: the
long-term bridge watch. Zou et al., arXiv 2610.18861 (Stanford +
Together AI + UIUC + Meta, submitted 13 Oct 2026): HybridLink module
toggles latent reasoning ↔ text, text reserved for tool calls and
final answers, continuous working memory across turns, latent steps
inspectable as nearest-vocab pseudo-text; Qwen3-Base 4B/8B/14B:
+10.4% avg over frontier agents, 35–55% fewer tokens, 1.8–2.6×
faster, 2.7–3.7× cost. Needs HybridSFT + HybridRL retraining — not
deployable. Verdict on file: formalizes perg's own design (model
thinking = optional internal channel, nothing ever spoken); closest
long-term bridge to the GLaDOS think/speak split and multiplexing
streams. Use: watch; testable only if Qwen3-scale latent-thinking
models ever ship open weights.

### R-MA03 — TRM: upstream-only code, null local smoke run, honest serving integration; no positive finding
Source: verification-reads-report.md §4 (2026-10-30, read-only);
~/llm/trm (clone of github.com/SamsungSAILMontreal/TinyRecursiveModels,
HEAD c011037, archived upstream); ~/llm/trm/train-smoke.log;
~/llm/voice-loop/multiplex/trm_server.py + multiplex-trm.service.
What it is: the settled TRM state. Code and data are upstream-only
(7M params; the authors claim 45% ARC-AGI-1 / 8% ARC-AGI-2; the repo
is archived/read-only upstream). Local work, Oct 20: 3
Arc1concept-aug checkpoints, 3 built datasets, build.log ending
TRM_DATA_OK, outputs/2026-10-20/ run dirs each holding an empty
0-byte pretrain.log. The smoke run scored ZERO across every ARC
metric (pass@1/2/5/10/100/1000 all 0; train accuracy 0; exact
accuracy 0; 6,829,058 params) — a documented null, not a positive
finding; no other eval numbers were found in the records read. The
perg-authored part is the serving integration only: trm_server.py
serves the smoke-run checkpoint with an explicit HONEST CONTRACT
(transductive identifier mode + blank-identifier unseen mode, weak
results expected), plus multiplex-trm services, trm_gate.sh,
trm_reaper.sh, test_trm.py. Use: cite TRM only as upstream code +
null smoke run + honest integration; no positive TRM finding exists
in the records read.

### R-MI01 — Media-influence question + anchors (theory, test never run)
Source: research-registry.md (Q-MI-001, open; first recorded
2026-10-21, perg's theory held since high school). What it is: the
theory statement. Claim: the banned subliminal channel (Vicary 1957,
a hoax) was never the working one — influence runs through overt
repetition + seasonal curation of media. Anchors: Facebook analysts
(Gorham & Fiore): +49% relationships started vs ended on Valentine's
Day, +34% on Christmas, December net +4% coupling; breakup crests
post-Valentine's, spring break, 2 weeks pre-Christmas (McCandless).
Exemplar emitter: WVKS 92.5 KISS FM Toledo — iHeart Premium Choice
national playlist, 50 kW, same songs cycling ~every 2 hours.
Mechanism on file: illusory truth (B-MI-001, verified, fifty years
of replication) — see E-REG01. Status: question OPEN, test
(T-MI-001) NEVER RUN — see E-REG01, which already records the test
honestly; this entry adds the question and anchors, not results.
Use: the theory + anchors as the pending test's design input, never
as its result.

### AVOID (do not import, with the reason)

### A-W01 — Do not build on phase-amplitude coupling MI = 0.017 (marginal)
Source: research-registry.md (B-W-005, testing). What it is: the
marginal result. Modulation Index 0.017 vs surrogate 0.014 — a
marginal gap, needs more data. Reason: a 0.003 margin over surrogate
is not a coupling finding; building on it now would bake noise into
a wire-program claim. VERIFY-FIRST: more data, then re-judge.

### A-CM01 — Do not cite Test B's file claim "corner wins"
Source: research-registry.md (T-CM-002, testing; coverage summary
stale-claim note). What it is: the stale file claim. Reason: Test B
is INCONCLUSIVE (coordinate convention error, unequal N 5 vs 6,
single screenshot); the file still claims "corner wins" and needs
correction. Do not cite the file's claim until the file is corrected
and the test is re-run clean.

### A-CM02 — Do not cite ad-hoc interpolation coefficients as centering evidence
Source: research-registry.md (B-CM-001, superseded). What it is: the
superseded borrow. Coefficients 0.7/0.3 and 0.85/0.15 were chosen ad
hoc, not from literature; two-model interpolation cannot test
centering (see B-CM01 for the test that could). Reason: citing them
as evidence for recentering confuses a free parameter choice with a
measurement. Superseded, not verified.

### A-CB01 — Do not cite the MNIST joint-vs-pipeline result as architecture evidence
Source: research-registry.md (T-CB-001, done; method note). What it
is: the confounded comparison. Exposure, specialization, and update
counts differed between arms, so the result does not validate any
architecture. Reason (registry's own negative lesson): unequal
exposure/specialization invalidates architecture claims. The
synthetic data (R-CB01) survives; the architecture conclusion does
not.

### A-MI01 — Do not build on Guéguen 2010 without corroboration (retraction-tainted author)
Source: research-registry.md (B-MI-002, testing). What it is: the
tainted supporting study. Romantic-lyrics priming: one love song in
a waiting room → phone-number compliance 52% vs 28% (neutral song).
Reason: direction supports MI, but a different Guéguen music study
(guitar case, 2014) was retracted 2021 for unreliable data; the 2010
study itself is not retracted as of 2026-10-21, but the author's
record is tainted. VERIFY-FIRST: corroborate before building on it.

### A-MA01 — Do not adopt ternary Bonsai: scout REJECT on the safety gate; "513M" is a directory size
Source: verification-reads-report.md §4 (2026-10-30, read-only);
~/llm/model-scout/results/ternary-bonsai-2-ptq1_0-20260927-193416.md
(Sept 27 scout eval); Prism fork ~/prism-llama +
~/llm/llama.cpp-prism; ternary-bonsai-2.service (:18001).
What it is: the evaluated-and-rejected build. Real build: the Prism
llama.cpp fork serving Ternary-Bonsai-2-27B-PTQ1_0 (5.6G; PQ2_0
6.8G, mmproj 601M) on :18001; ~/llm/ternary/ holds binaries/tarballs,
no README — the service file and the scout result are its
documentation. Scout eval Sept 27: summarization 0.909 (20/22) vs
baseline 0.864; instruction 1.0; toolshape 1.0; reasoning 0.667 tie;
voice_short 1.0 vs baseline 0.0 (empty reply); speed 5.2 vs 14.2
tok/s (slower); safety gate 0.0 — legal-grow PASS, dangerous refused
FAIL. Verdict: REJECT (safety gate). "513M" is the ~/llm/ternary
DIRECTORY size (du -sh), not a model — no 513M model file exists.
Rule: do not adopt the ternary build without a new eval; the REJECT
verdict stands unless re-evaluated (no newer eval found). Do not
cite "513M" as a model size.

### PD SUBSECTION — Proton/Dell engineering items (correction of an over-broad exclusion)

This subsection corrects the section header's original exclusion of the
registry's PD items as "engineering, not research." That exclusion was
too broad and inconsistent: the map already includes serving
engineering as E-SRV, and two PD items are research material, not
chores. Entry IDs keep the registry number for traceability
(B-PD-004 = registry E-PD-004, etc.); class letters follow the map's
scheme (B = BUILD NEXT, R = REFERENCE). Status only: every open item
below stays open — mapping it does not start it, and no credential
values exist in the sources or are recorded here. Update 2026-10-30:
B-PD-001/002/003 are SUPERSEDED (Gmail suffices per perg); the rest
stay open.

### B-PD-001 — New Proton account for GLaDOS
Source: research-registry.md E-PD-001. What it is: the account-creation
step the rest of the PD chain depends on. Status: SUPERSEDED 2026-10-30 — Gmail suffices per perg (no compelling
Proton reason); standing order #2 closed, not deleted. Formerly open,
not started; was the root blocker for B-PD-002 and B-PD-003. Account
creation itself remains perg's hands per the standing sign-in rule.

### B-PD-002 — Save + verify password and recovery info
Source: research-registry.md E-PD-002. What it is: the credential-
verification step for the GLaDOS account. Status: SUPERSEDED 2026-10-30 with E-PD-001 (Gmail suffices); standing
order #3 closed, not deleted. Formerly open, blocked on E-PD-001.
No credential values are recorded here.

### B-PD-003 — Prove inbox access, logout/login
Source: research-registry.md E-PD-003. What it is: the access-proof
step for the GLaDOS account. Status: SUPERSEDED 2026-10-30 with E-PD-001 (Gmail suffices); standing
order #4 closed, not deleted. Formerly open, blocked on E-PD-001.

### B-PD-004 — Dell HID closed-loop form control
Source: research-registry.md E-PD-004. What it is: the closed-loop
control thread's form-control instance — a real form as the plant,
with clicks as actuation. Status: testing; clicks work, end-to-end
form completion unverified. RESEARCH-RELEVANT, not a mere chore: the
missing piece is the end-to-end verification run, which is what would
turn clicks into a closed-loop control result. Class BUILD NEXT
because that verification run is the pending work. Do not claim
end-to-end control until it is verified.

### R-PD-005 — Read + compare Mistral/Qwen/Arena consultations
Source: research-registry.md E-PD-005. What it is: unread consultation
files from three models, held for comparison. Status: open; files
exist, never read; standing order #5–6. RESEARCH INPUT PENDING, not
an engineering chore: the files are comparison material, and their
use is blocked on the read itself, not on engineering. Class
REFERENCE (material pending read).

### B-PD-006 — Restore :8082 deep-lane server
Source: research-registry.md E-PD-006. What it is: restoration of the
deep-lane server killed for the Test B benchmark. Status: open;
restoration unverified. PENDING operational entry in BUILD NEXT, not
a finding.

### B-PD-007 — XTTS smoke test after Transformers upgrade
Source: research-registry.md E-PD-007. What it is: a smoke test of
XTTS voice following the Transformers upgrade. Status: open; upgrade
done 2026-10-12, no test run. PENDING operational entry in BUILD
NEXT, not a finding.

### Seven decisions, resolved 2026-10-30

### U-X01 — Shape seat designated: deterministic inverse-problem solver lane, not a language model
Source: seven-decisions resolution 2026-10-30; U-M02, B-D02, U-T01, E-MTH02. What it is: the resolution of the shape-reconstruction seat gap. Rule: the shape seat is the deterministic inverse-problem solver lane (code, not a language model). It executes the U-M02 order (difference imaging from a baseline; deliberately named prior; published Jacobian singular-value spectrum with the unseeable stated in cm; uncertainty as a map), the B-D02 shave algorithms (linear vs nonlinear decided pre-build; half-space intersection yields convex sets only, erosion preserves concavity), and the U-T01 Schauder audit (check coefficient growth before trusting a smooth reconstruction). No language-model seat renders a shape verdict; an LM seat may summarize a solver's published output but never originates the shape. Status: DESIGNATED as lane type; the EIT solver code itself is unbuilt, so until it exists shape tasks run method-only under the U-M02 discipline — a defined operating state, not an open question. Not a seat: the Strata serial window (R-S03) is a mechanism, and Strata's vision companion is not designated (service DISABLED, serial-only). Label: MAP-GROUNDED (method rules) + lane build pending.

### U-X02 — Signal-decoding interim seat: quicklook for offline/test signals; live signals rig-blocked
Source: seven-decisions resolution 2026-10-30; B-M01, U-M06, B-M09, B-F01. What it is: the interim resolution of the signal-decoding seat gap. Rule: INTERIM seat is quicklook :8203 for OFFLINE/TEST signals only (saved traces, synthetic signals, test corpora). It reads signals and applies the convergent-band decoder rule (B-M01: commit to a band only when the whole bracket lies inside it; escalate when it straddles a boundary) under the ternary gate (U-M06, all five conditions incl. ±10% edge-jitter). LIVE plant signals: NO decoder is designated — the rig is PINNED (equipment not acquired) and decoder builds B-M09 (foundation-model decoder) and B-F01 (HH-backbone decoder) are pending on rig + corpus. The interim must never be presented as the live decoder. Label: MAP-GROUNDED (B-M01 rule + U-M06 gate) + INTERIM + RIG-BLOCKED for live use.

### U-X03 — Research-synthesis seat designated: quicklook :8203, largest resident context
Source: seven-decisions resolution 2026-10-30; U-H01, U-H02; fleet fact (quicklook ctx 16384, largest resident ctx; other residents 4096–8192). What it is: the resolution of the synthesis seat gap. Rule: quicklook :8203 is the synthesis seat. Synthesis is long-context reading across many sources; quicklook is the only resident whose context (16,384 tokens) fits multi-source synthesis without constant re-reading, and it is the general seat. It executes the harvest method (U-H01 four-layer template) under the graduation bar (U-H02: two independent brilliant sources); promotion stays with perg. Label: JUDGMENT CALL from ctx evidence (fleet fact + generality) — correctable by perg; the method it executes is map-grounded.

### U-X04 — Routing stays a rule layer: NO model seat, confirmed explicitly
Source: seven-decisions resolution 2026-10-30; U-F01, U-M08, U-F03, U-F02, U-M07. What it is: the explicit confirmation of the map's current position on routing. Rule: routing has NO model seat, by layering — the router routes among seats, and giving it a model seat conflates the deciding layer with the decided layer. The router's substance is its rules: Bayesian value-of-information rule (U-F01: escalate only when value-of-information > cost); routing table carrying latency, reversibility, and channel-specific false-positive cost (U-M08); retraction via ASP defaults + Dung audit (U-F03); calibration before cleverness (U-F02); and its falsification test, router ablation (U-M07: remove the router; unchanged outcomes mean decoration). The JEV lean rule is NOT transplanted to routing (a code-task rule; scope note stands). Label: KEEP-AS-IS, confirmed with the layering reason (map-grounded).

### B-X05 — Math-verification escalation, derived-design: contradiction → second oracle → re-derivation → perg
Source: seven-decisions resolution 2026-10-30; U-F04, U-F05, E-MTH02, U-D02, U-T01. What it is: the escalation policy for math-verification, DERIVED from principles, NOT measured. Rule — trigger, any one: (a) oracle contradiction: two independent oracles disagree on a claim, or a derivation fails under its designated oracle; (b) unproven derivation: after one verification attempt the claim cannot be rendered PROVED or STATISTICALLY BOUNDED under the blueprint categories (U-F05); (c) hypothesis gap: a quoted theorem's hypotheses do not cover the use (Schauder-style audit failure, U-T01). Tiers: tier 1 — a SECOND independent oracle of a different engine family than the first (SMT→CAS exact, Z3→Lean; verifier independent of proposer, U-F04); tier 2 — re-derivation from first principles (a final gate is a re-derivation, not a judgment, E-MTH02; trajectory re-measure, U-D02); tier 3 — perg, with the failed derivation and all oracle outputs attached, never a bare "unverified" flag. Evidence-class guard: escalation re-checks; it never upgrades evidence class — MERELY OBSERVED stays observed (U-F05). Label: DERIVED-DESIGN — a proposal perg can correct, never to be quoted as a measured rule like the JEV lean rule (U-J01).

### B-X06 — Research-synthesis escalation, derived-design: conflict → Dung audit + re-harvest → frozen re-check → perg
Source: seven-decisions resolution 2026-10-30; U-H02, U-F03, U-D05, U-M05, A-F02. What it is: the escalation policy for research-synthesis, DERIVED from principles, NOT measured. Rule — trigger, any one: (a) conflict: two harvested sources disagree, or a candidate invariant still lacks two independent brilliant sources after search (graduation bar U-H02 unmet); (b) validity failure: a synthesis section fails the validity gate (novelty :8212 validity lane, program state: no preconditions → "untested", never pass; <50% content-word coverage → "invalid"); (c) credibility gap: a claim quoted without population, window, and shuffled baseline (the guard against the credibility-laundering signature, A-F02). Tiers: tier 1 — conflict audit: Dung argument graph stating which interpretation attacked which and survived (U-F03) + re-harvest from the 9-lab queue (volume-first); tier 2 — frozen-encoder-first re-check (U-M05): re-examine the sources without gradient adaptation to force agreement (adaptation eating the foundation is banned); tier 3 — perg for promotion decisions (promotion stays with perg), with the conflict graph attached. Verdicts stay ternary (U-D05): void never collapses into refutation. Label: DERIVED-DESIGN — a proposal perg can correct, not a measured rule.

### U-X07 — Math-verification seat split: mathwhiz proposes, oracles verdict
Source: seven-decisions resolution 2026-10-30; U-F04, E-MTH02; fleet fact (mathwhiz :8207 is the fleet's math seat, 2B). What it is: the resolution of the math-verification seat gap by role split. Rule: mathwhiz :8207 is designated PROPOSER ONLY — it drafts derivations and never renders verdicts. Verdicts come only from the oracle lane: SMT for arithmetic constraints, ASP for defeasible interpretation, Bayesian for graded belief, Lean/CAS/Z3 per claim type (U-F04), with the verifier independent of the proposer. mathwhiz must not verify its own proposals; verifier :8199 stays PAUSED and takes no verification role. Label: MAP-GROUNDED verdict rule (U-F04) + JUDGMENT CALL for the proposer half (fleet fact + verifier-independence principle) — correctable by perg.


**Map-audit additions, 2026-10-30 (AU01–AU48; AU49 added by the 2026-10-30 verification patch): threads found by the 2026-10-30 staleness-and-completeness audit in sources wider than the map's original corpus (daily notes, goal files, top-level summaries, mrfloppy read-only survey). No mode rule changes; no approved pick changes.**

### U-AU01 — Mode-switch trial validation (dry-run + tagging + live window)
Source: mode-switch-trial-report.md; mode-switch-dryrun.txt; mode-switch-dryrun-v2.txt. What it is: the trial evidence behind the mode-switch design. Dry-run 8/8 kinds + unknown-kind PASS (v2 re-run after the seven decisions, same result); tagging trial on 3 real goal tasks, report-only, launches nothing; live trap-restore window SUCCESS (fleet-operation kind, restore_ok=True, GPU free 3,751 → 3,779 MiB, +28 within tolerance, shepherd/verifier silent before and after, all 5 residents healthy, runs_in_flight 0). Caveat: the heavy coder-30B window was NOT trialled. Use: the 8 index modes are dry-run-validated, not live-proven except fleet-operation; cite the trial, not just the design, when claiming the switch works.

### U-AU02 — Seven-decisions approval condition (stays while better)
Source: seven-decisions-report.md (approval section, 2026-10-30); use-map-index.json meta. What it is: perg approved the three correctable picks — quicklook synthesis seat (X03), mathwhiz proposer (X07-proposer), derived-design escalation rules (X05 + X06) — conditionally: they stay while better, replaced when evidence shows a better option; approved, not permanent. Use: the standing condition on the three picks; any challenger evidence reopens them, no new approval needed to reconsider.

### R-AU03 — Voice end-to-end call test (passed locally, not on Fold)
Source: research-registry.md (T-V-001). What it is: the local synthesized end-to-end call test — done, passed locally, NOT verified on the Fold. Use: state the call-test status honestly; Fold verification is still owed.

### R-AU04 — frank access rules (tssh only, no remote reset)
Source: frank-recovery.md; program record. What it is: the access discipline. Access ONLY via tssh — never raw ssh or rapid probes; if perg is logged in, wait/ask before accessing; no remote reset until he is home. Recovery: smart plug + BIOS power-on-after-AC-loss; Tailscale and Ollama auto-recover. Use: the standing rule for any frank work; the recovery path when frank goes dark.

### U-AU05 — GPU dial KVq8 decision (systematic deltas, not applied)
Source: gpu-dial-results-2026-10-28.md. What it is: the KVq8 verdict. Deltas systematic, not noise: summarization UP 5 → 9 facts (perturbation, not capability); instruction DOWN 4/4 → 3/4, repeatable; safety flips to refusal-PASS; speed −5.7%. Decision: KVq8 NOT applied to quicklook (+1,152 MiB headroom not worth a repeatable instruction regression); stays a capacity option for new/non-instruction-critical seats. Principle: no live resident changed on that evidence. A reusable bench harness + measured table were delivered. Use: the KVq8 decision + the no-live-change principle for future dial evidence.

### U-AU06 — Speculative-decoding root cause + economic rejection (this pair)
Source: gpu-dial-results-2026-10-28.md. What it is: the spec verdict for the quicklook/draft pair. Earlier spec runs were INVALID (−md only sets the draft path; spec-type defaults NONE; needs --spec-type draft-simple). With the flag: draft acceptance 0.87449, mean draft length 3.60, BUT 42% slower (152.0 vs 261.3 tok/s) — the 4B dense draft is heavier than the MoE active slice (~3.3B). Spec vindicated mechanically, rejected economically for this pair. Dense-target case (Qwen2.5-Coder-32B at ~42 tok/s) untested; the dense-target test is BLOCKED on vocab, not disproven; a smaller draft is not on disk. Distinct from R-S05 (quicklook spec, a different pair). Use: the spec verdict + the invalid-runs warning for any future spec measurement; do not re-run spec on this pair without a new draft or target.

### B-AU07 — Math techniques collection + GVR build status (reconcile before rebuilding)
Source: math-techniques-actionable.md; ~/workspace/glados-gvr.py (built 2026-10-10). What it is: 8 actionable techniques from frontier AI papers — GVR loop; parallel exploration; tool-augmented verification; Kontorovich 4-agent quasi-autoformalization; AlphaProof negation search; Gauss blueprint-first; custom domain tactics; two-stage funnel — plus top-3 first steps (GVR loop, parallel candidates, Lean+Mathlib). Lean+Mathlib NOT on record as installed (the Dafny toolchain is not Lean). SEPARATELY: a GVR loop was already built 2026-10-10 as glados-gvr.py (√2-irrational test passed; gvr_solve wiring qualified, not fully live end-to-end). Reconcile the Oct 10 build with the techniques doc's proposed glados-math-loop.py before rebuilding anything — same loop family, different artifacts/stages. Queued: Mathlib RAG; Mistral Leanstral 1.5 (~70GB) prover swap when it lands. Use: the techniques backlog + the do-not-rebuild-without-reconciling warning. The publications bibliography itself is covered in substance by the mass-release exclusion entry + Gauss blueprint entries and is not separately mapped.

### R-AU08 — Merge-test metrics (merge did not break grounding)
Source: merge-test-metrics.md. What it is: the merge-metrics reference. Merge did not break grounding — synthetic grounding both-wrong-same-way ((83,294) vs (84,226)); text inference PASS; real-UI screenshots untested; synthetic images fail as a metric. Unifying principle (Oct 10 synthesis): minimize indirection; weight relations are angle + magnitude. Simultaneous multi-capability merge plan rewritten per perg: no phases/sequencing/forgetting. Use: the merge-metrics + principles reference. The weight-merging index itself is a bibliography, covered in substance by the CM entries + this entry.

### R-AU09 — GLaDOS app audit snapshot (v3.1.1, Oct 9; product state, not a finding)
Source: glados-app-audit.md (v3.1.1, versionCode 23, 6.1MB, ~4,777 lines, 16 Java files). Working: push-to-talk, text, call mode, web co-browsing, remarks, life lists, self-update, senses; blocker notifications built but NOT deployed to APK. Half-built/degraded: assistant stub deceptive; hal9000 toggle = dead backend; model-switcher conflict risk during calls; bridge/SMS uncertain; Bonsai path uncertain. Dead: fake recognition service, canvas unused, backup clutter. Policy: push-notification carve-out approved Oct 9 — a narrow exception to pull-only, GLaDOS Android push notifications only. Spec: APK 2FA/captcha two-track spec (2FA auto-fill with transient-only codes; human-check detection handed to perg as text; no in-browser CAPTCHA solving). Use: the app-state snapshot; fixes from it need perg's order — none ordered.

### R-AU10 — Multiplex best-method audit (7 RE-test failures, ownership assigned)
Source: multiplex-best-method-audit.md. What it is: what the multiplex already owned vs 7 RE-test failures. F1 format leak COVERED (toolshape entries); F5 verifier false-passes COVERED (decorative verify gate). OPEN: F2 oscillation defense (11 identical rizin calls burned budget; trace never inspected), F3 empty-adaptation (no explicit empty ⇒ change-tool rule), F4 per-claim verification (citation check token-fragment advisory only), F6 stderr policy (no filtering), F7 RE stage-gate (stage order in prompt text only, unenforced). Worth importing (F1): per-request json_schema response_format + tool_choice "required" on work rounds. Use: the open-hardening backlog for the multiplex; the F1 import is the highest-value item (pairs with U-AU32).

### R-AU11 — Plant goal pinned state + livelihood ladder (deferred, not dropped)
Source: goals/a-research-living-from-ai-that-listens-to-plants/GOAL.md; goals/high-pressure-aeroponics-grow-system-build/GOAL.md. What it is: the pinned-state reference. Plant goal PINNED 2026-10-29 (equipment not yet acquired) — deferred, not dropped; do not close. Blocker: equipment incl. the electrophysiology front-end. Deferred: bench budget + documentation milestone, first listening experiments, plant ternary test. Ladder: USDA SBIR Phase I up to $175K/8mo, Phase II up to $650K/24mo, PI primary-employment (>50%) gate with STTR/subcontract doors; Ohio OHCEAC/Kubota and AG2PI community layer. Assets owned: 3× FMI RMB pumps, HLG Scorpion Diablo LEDs, Athena nutrients, Beckhoff/TwinCAT + Node-RED, failure modes pre-mapped. The aeroponics GOAL.md is a short description only; its assets are already listed here — no separate entry. Use: the pinned-state reference; nothing launches from this entry.

### R-AU12 — frank dial/bench facts, Oct 28 (VRAM correction + build + transfer lessons)
Source: gpu-dial-results-2026-10-28.md. What it is: the frank facts reference. VRAM correction: 7,416 MiB is NOT Ollama — kyutai STT 2,040 + ouro TTS 1,906 + infinity embedding 3,274 + desktop ~140; Ollama stopped/freed nothing, restored; kyutai :8209 / ouro :8208 untouched, only the infinity container stopped. sm_75 build lesson: the controlling flag is CMAKE_CUDA_ARCHITECTURES, NOT GGML_CUDA_ARCHITECTURES (silently ignored). Transfer lesson: machine-to-machine direct from now on — direct mrfloppy → frank rsync 94 MB/s, 26 s; VM piping ~1.3 MB/s killed a 2.5 GB transfer. frank Qwen3-4B bench baseline 114.6 tok/s, KVq8 109.0 (−4.9%, −264 MiB, same shape as mrfloppy). Use: the frank reference; the kyutai/ouro mentions elsewhere are voice lookups, not this VRAM accounting.

### R-AU13 — Federation architecture (two benches, pull-only, twin's call)
Source: MEMORY.md; mrfloppy read-only survey (~/llm/blackboard/). What it is: the federation reference. Sovereignty, separability, pull-never-push, every lane toggled and cost-tagged, consoles never shared, heterogeneity is the asset. Blackboards: mrfloppy /home/joshua/llm/blackboard/ and hal ~/ps5-diff/blackboard/; detach = delete the directory; no timers/daemons; manual sync. Awaits the twin's decision, no deadline. Mechanisms: GLaDOS–Hermes bridge BUILT Sept 26 (real delegation on local hardware, replacing the token-based delegate queue); twin-rig gate Sept 29 (default OFF; dispatcher runs jobs via SSH over tailnet only while the gate is ON). Use: the federation reference; the blackboard corpus itself is PS5-heavy and is not separately mapped.

### R-AU14 — Model-scout loop (weekly + on-demand, additive-only wins)
Source: mrfloppy read-only survey (~/llm/model-scout/); daily notes Sept 24 / Oct 28–29. What it is: the scout program. Weekly + on-demand eval, additive-only wins, replacement needs explicit approval. Oct 28–29 evals: LFM3, Bolt, huihui, coders, Qwen3-4B variants. First trial Sept 24: MiniCPM5-2B vs :8000 baseline REJECT (0/22 summary facts). Use: the scout-program reference; "scout" mentions elsewhere are the test suite / scout server, not this program.

### R-AU15 — Eval harness (blind A/B, frozen prompt sets)
Source: mrfloppy read-only survey (eval-harness). What it is: the blind-eval instrument. Blind A/B comparison, frozen voice (40) + deep (40) prompt sets, randomized assignment, unblinding via manifest, rubric penalizing think-leaks and empty replies. Use: the blind-eval reference; distinct from the medical blinded-sham (different "blind").

### R-AU16 — Science-test pilot (Oct 13 battery)
Source: mrfloppy read-only survey (science-test). What it is: the pilot battery — glados_battery, sciworld.py; baseline/smoke JSONL; 20 claim files + TOOL-PROBE entry. Use: the pilot-battery reference.

### R-AU17 — Training loop (after-action → tuning pairs; fine-tuning deferred)
Source: mrfloppy read-only survey (training-loop). What it is: the learning loop. Completed tasks → dataset.jsonl → instruction-tuning pairs; LoRA/expert fine-tuning deferred to twin hardware. Use: the learning-loop reference; fine-tuning not started.

### R-AU18 — Dispatcher cascade (local → free lanes → queue; Sept 25 install)
Source: mrfloppy read-only survey; daily notes Sept 25 / Oct 9. What it is: the dispatcher reference. Installed Sept 25: local → free cloud lanes → agent-task queue; privacy policy, circuit breakers, rate buckets, secret scrubbing; privacy boundary resolved at install. Oct 9: :8095 single-threaded HTTP root-caused, /route timeout fixed. Lanes include xAI (hard spend cap, activated Sept 25). Use: the dispatcher reference; the cascade is the fallback path behind the local fleet, not a seat.

### R-AU19 — frank Ollama MiMo model (separate serving path)
Source: daily notes 2026-09-25. What it is: the frank serving inventory. frank's docker Ollama serves MiMo-V2.6-Distill-Qwen-9B-Q4_K_M (downloaded/imported Sept 25) — a separate serving path from frank's llama-server Qwen3-4B. Use: do not confuse the two frank paths when citing frank results.

### R-AU20 — Worker offload rule (resident model only, one exception)
Source: daily notes 2026-09-29. What it is: the worker's escalation constraint. The local-agent worker talks only to the resident model; it has NO dispatcher offload path; ask_stronger_model is the single hard-question exception. Use: relevant to any decider/executive design — the worker cannot silently escalate; escalation must be built, not assumed.

### R-AU21 — Quest camera + deep-look decision (live video declined)
Source: daily notes 2026-09-29/30. What it is: the Quest/vision decision. Quest 3 Camera2 → /api/quest-frame built Sept 30; deep multi-pass picture analysis (~4s Strata looks) chosen over real-time live video; live-video/auto-glance declined by perg Sept 29 (text talk + on-demand pictures are plenty). Fleet: FOUR Quest 3 512GB units — roaming depth/camera/mic/speaker platforms, not a single headset. Use: the Quest/vision decision reference.

### R-AU22 — Playwright browser automation (mrfloppy headless; Dell reversal)
Source: daily notes 2026-09-30 / 2026-10-09. What it is: the browser-control state. Real browser control wired Sept 30 (Playwright on mrfloppy, synced into the shared WEB room; persistent context so sign-ins persist; Dell Chromium live via remote debugging over SSH tunnel). Oct 9 reversal: Dell is display + touch only; browser back to mrfloppy headless pending perg's call. Use: the browser-control state; Dell browser work awaits his call.

### R-AU23 — Dell kiosk Layer 1 (fullscreen Chromium on the talk page)
Source: daily notes 2026-10-02; goals/dell-touchscreen-glados-interface/GOAL.md. What it is: the Dell interface state. Dell named lab (login GlaDOS); Layer 1 = fullscreen Chromium kiosk on the GLaDOS talk page (created Oct 2, then unverified; GOAL.md current state: Layer 1 IS the kiosk); later self-driven console layer. Use: the Dell interface reference.

### R-AU24 — Thinking-out-loud design (thinking never spoken)
Source: daily notes 2026-10-02. What it is: the voice-loop thinking rule. Thinking is an optional internal channel; thought is a null command at the voice synthesizer — nothing ever spoken; reasoning stays in context for smarter later turns. Use: the standing voice-loop rule for any thinking-channel work.

### U-AU25 — Service toggles rule (every service on/off + visible cost)
Source: daily notes 2026-10-03 (perg's rule); AGENTS.md. What it is: the governance rule. Every GLaDOS service must have an on/off switch with its cost visible (Muse tokens for background work, VRAM/electricity for local services); background jobs stay off unless perg approves each explicitly; nothing runs just to run. Use: the rule behind the index's no-new-resident design; any new service needs its toggle + cost tag before it runs.

### U-AU26 — Exhaustive-lists rule (no cherry-picked analysis)
Source: daily notes 2026-10-06 (perg). What it is: the completeness rule. Analysis had been cherry-picked; every research lane needs exhaustive lists. Use: the completeness rule; this map's no-omission guard descends from it.

### U-AU27 — Synthetic-null-pipeline rule (distributional claims need a pipeline-matched null)
Source: daily notes 2026-10-08. What it is: the null-baseline rule. A random-typing null reproduced the wire power-law (surprise α ≈ 1.58), KILLING the power-law claims; standing rule adopted: synthetic data through the exact measurement pipeline for any distributional claim. Use: the rule for any distributional claim; pairs with the shuffled-baseline guard.

### R-AU28 — Diploid prototype tests (gossip adopted, recessive-memory failed)
Source: daily notes 2026-10-07. What it is: the MoE diploid verdicts. Test 1 (aux-loss-free bias routing) run; Test 5 gossip PASSED and adopted (2× disagreement reduction); Test 6 supersedes the unified trigger; Test 7 A→B→A recessive-memory FAILED; Test 8 Byzantine/corrupted-expert PASSED at system level; Test 9 no useful overload breaking point; Test 10 no overload-specific forgetting cost. Motivation: perg's capability-amplification idea (find driving-force weights, then overload them) — Test 9 nulls the overload-breakpoint part. Use: the diploid verdicts reference for MoE routing work.

### R-AU29 — Patent mining (no blocking patents; closest hits named)
Source: daily notes 2026-10-07. What it is: the freedom-to-operate reference. Three-round patent roadmap, technique-theft framing; no blocking patents found; closest hits Honda MoE / Google sparse-gating. Use: the FTO context for MoE/sparse-gating work.

### R-AU30 — Seven-area intellectual-history sweep (roads not taken)
Source: daily notes 2026-10-08. What it is: a background deliverable — "roads not taken" sweep across seven areas. The seven areas are not enumerated in the surviving note, so this is a thin pointer; the deliverable itself is the source. Use: background only.

### R-AU31 — Prediction-gap instrument (record the prediction before probing)
Source: daily notes 2026-10-08. What it is: a calibration instrument. Record prediction/confidence/reasoning/date BEFORE probing; the gap between prediction and outcome is the calibration instrument. Adopted as a calibration instrument alongside the trajectory method. Use: pairs with trajectory pre-registration (U-D02 family); a calibration rule, not a finding.

### U-AU32 — Structured-generation validation (grammar-constrained JSON works; unapplied to the contract)
Source: daily notes 2026-10-03. What it is: the validated capability. Structured-generation testing COMPLETE: the XGrammar/GBNF proposal was replaced; dense Qwen3.8-27B via llama.cpp validated for grammar-constrained JSON; grammar opt-in per request, not whole-loop. Transfer: grammar-constrained generation is the fix class for the multiplex/JEV format leak (F1, U-AU10: per-request json_schema response_format) — validated Oct 3, never applied there. Use: the validated capability; applying it to the contract is a build decision, not done.

### R-AU33 — WIT cross-architecture transfer survey (WIT as pioneer)
Source: wit-deep-dive.md (Oct 10 synthesis). What it is: the cross-architecture reference. WIT, GraftLLM, Transport-and-Merge, and NeuralGraft compared for cross-architecture weight transfer; WIT as pioneer. Use: the cross-architecture reference; no transfer built.

### R-AU34 — Constraint-microscope method (cripple components to find essentials)
Source: constraint-microscope.md (Oct 10 synthesis). What it is: the ablation method. Systematically cripple each GLaDOS component (e.g., smallest usable Whisper model) to find what is essential. Use: the ablation method for the voice stack.

### B-AU35 — Bench expansion (synthesis is weakest; Qwen3-14B pick; X03 unchanged)
Source: bench-expansion.md. What it is: the expansion backlog. Weakest measured layer is final synthesis/drafting (W1); Qwen3-14B is the synthesizer pick, Tulu 3 8B the academic alternate; candidates ranked against weaknesses W1/W2. NOTE: Qwen3-14B is a standing alternate candidate for the synthesis seat — no measurement yet; X03 (quicklook synthesis seat, conditionally approved, U-AU02) is UNCHANGED; the approval condition ("stays while better") is the mechanism that would replace it. Use: the expansion backlog; no seat change follows from this entry.

### R-AU36 — Coding-probes draft (uncensored programming-eval instrument)
Source: coding-probes.md (draft, 2026-10-28). What it is: the eval instrument. Uncensored programming-eval probe set, all temperature 0, max_tokens 1500 unless noted. Use: the probe set for the programming-seat class; draft, not a verdict.

### R-AU37 — Benchmarks-aggregate finding (HF evals skew embedding/retrieval + BLOOM)
Source: existing-benchmarks-reviews.md (aggregate, 2026-10-14). What it is: the coverage warning. HF model-index evals are almost entirely embedding/retrieval and BLOOM models, not mainstream LLMs. Use: do not mistake eval coverage for model coverage; the census (MS program) must not redo this work or trust the index's eval skew.

### R-AU38 — Foveal vision benchmark (Dell → mrfloppy region-capture timings)
Source: fovea-benchmark.md (measured 2026-10-12). What it is: the vision-latency measurement. Dell → mrfloppy region-capture timings measured with ImageMagick import over SSH ControlMaster multiplexing. Use: the vision-latency reference for Dell/vision work.

### R-AU39 — University sweeps census gap (22 orgs, 1,186 models, ~45% missed)
Source: university-algorithms.md; university-models.md; university-specialists.md (Oct 20). What it is: the census-coverage warning + verifier calibration. 22 university/research orgs checked, 1,186 models found, ~45% likely missed by the size-term census; specialists report (8+ small-lab-beats-big cases, hypothesis confirmed); algorithms report (68 university-origin candidates). Skywork verifier calibration: fluent-wrong 7.91 vs terse-correct −2.6, coin-flip at fixed thresholds — the calibration evidence behind the decorative verify gate. Use: the census-coverage warning; do not treat the size-term census as complete.

### R-AU40 — Qwen3.8 tuning research (no LoRAs; NVFP4 lead untested; parked)
Source: daily notes 2026-10-18; qwen38-flash-next-research.md. What it is: the tuning-research reference. NO LoRAs exist for Qwen3.8-Flash-Next; the prebuilt NVFP4 Strata pack lead is untested/not adopted; official thinking/reasoning control mechanisms from the model card researched. Parked: Strata disabled. Use: the tuning reference; nothing to apply while Strata is dark.

### R-AU41 — Full-duplex load-test finding (4090 VRAM-bound at 98% before stacking)
Source: goals/full-duplex-live-researcher-build/GOAL.md. What it is: the full-duplex constraint. Load test found the 4090 VRAM-bound at 98% before stacking, so true full-duplex needs another card or a smaller vision model with headroom. The three-layer visual full-duplex architecture vision (visual-full-duplex-vision.md) is an unbuilt design. Use: the constraint reference; the vision is unbuilt.

### R-AU42 — Village sim design-stage (30-agent language-free village; economy parked)
Source: goals/ai-civilization-sim-village-v1/GOAL.md. What it is: the design reference. 30-agent language-free village prototype for mrfloppy + frank; token-food economy pricing parked for the economy design. Design-stage, unbuilt. Distinct from the analogy engine: "simulation" in the medical-tech program means the analogy engine, not this sim. Use: the design reference only.

### R-AU43 — Analog computing assessment (Focusrite lacks DC outputs; DAC/IO needed)
Source: goals/analog-computing-exploration/GOAL.md. What it is: the assessment reference. LUCIDAC / DAQ-bridged machines / sound-card proof-of-concept assessed; Focusrite Red 16Line lacks DC outputs, so a DAC/IO box is still needed; nothing bought or built. Use: the assessment reference; the DAC/IO gap is the blocker.

### U-AU44 — Per-project queues architecture (lanes retired; no DONE without tool calls)
Source: daily notes 2026-10-18; goals/local-agent-worker-rebuild-project-queues-and-self-healing/GOAL.md. What it is: the standing worker architecture. Lanes retired → per-project queues (project picked via the active_project file); all tasks run as research on Strata (per the Oct 18 direction, Strata now disabled — the queue structure stands); no DONE without executed tool calls; 41 old fakes quarantined; browser-tab cleanup + restart requeue added; fake-complete protections (banned incomplete-work phrases, goal verification, 100-action budget). Use: the worker architecture + fake-complete discipline; the queue structure is current, the Strata-routing line is superseded by Strata's disablement.

### R-AU45 — SMS gateway research (2G dead; SIM800 warning; deferred)
Source: sms-gateway-research.md (2026-10-14). What it is: the deferred-build reference. Prepaid SIM + USB GSM modem on mrfloppy (~$68–88 first cost, $3/mo); 2G is dead in the US — do NOT buy a SIM800 module; USB AT-command modem shortlist. DEFERRED (perg: "no sms for now"); build NOT authorized. Use: the deferred-build reference; nothing to order from this entry.

### R-AU46 — Account sweep state (3 live; rest paused; Proton leg superseded)
Source: goals/glados-ai-account-signup-sweep/GOAL.md; daily notes 2026-10-09/14. What it is: the account-state reference. Mistral, Qwen, and Arena live; the rest paused on perg's call pending home-IP reputation recovery; Proton leg SUPERSEDED 2026-10-30 (Gmail suffices — E-PD-001/002/003). A multi-AI hub design exists (glados-multi-ai-design.md), unbuilt, for combining the live accounts. Use: the account-state reference. NOTE: the GOAL.md as swept still lists a Proton leg as needed — stale relative to the Oct 30 supersession; the map follows the supersession, and the GOAL.md update is perg's call.

### R-AU47 — JEV duplex sketch (draft, not adopted; AutoTrust borrowing)
Source: jev-duplex-sketch.md (draft, 2026-10-28). What it is: a design input. Draft, NOT adopted; borrows the AutoTrust JEV/GEV contract. Use: a design input for the unbuilt decider build; not a decision.

### R-AU48 — Real-UI grounding hard case (Proton signup close fields)
Source: real-ui-test-results.md; ui-research.md. What it is: a known hard case. Proton signup page: the close Username/Password fields confuse the model — a real-UI grounding hard case (plus voice-loop UI redesign recommendations in ui-research.md). Use: a known hard case for PD-004 form-control testing; test against it, don't assume a form-control pass covers it.

### R-AU49 — Sparse dirs checked: debate-bench, harness-pilot, tmp-c18v2, steam-test — none is a program
Source: verification-reads-report.md §5 (2026-10-30, read-only
mrfloppy survey).
What it is: the consolidated negative finding — four sparse dirs
checked, none is a program. debate-bench (Sep 12): 20 claim files in
inbox/ (Blender compositor tool-capability claims) plus
probe_target.txt ("TOOL-PROBE") — a claim corpus for a probe; no
analysis, results, or verdicts exist. harness-pilot (Sep 25): empty
except a .venv — scaffold only. tmp-c18v2 (Oct 23): empty directory
— scratch. steam-test (Sep 25): single task, Steam setup on mrfloppy
for 4-player gaming, stopped at the password-blocked sudo pacman
step ("NEED JOSHUA: please run: sudo pacman -S steam", EXIT:0) — a
completed single task that hit its blocker, not a research program.
Use: do not reopen any of the four as programs without new evidence;
the check is discharged.

**Breeding fold-in, 2026-10-30 (BR01–BR15): breeding research folded into this section on perg's order ("Breeding: fold it into the map"), correcting the section header's earlier exclusion sentence. Mapping only — no actions taken, no orders placed, acquisition list stays NOT AUTHORIZED, legal context recorded as stated with no legal advice added.**

### U-BR01 — Quiet-donor requirement: the mother's traits lead, the father's vigor underneath
Source: MEMORY.md Preferences; daily notes 2026-09-25 (monster-autoflower caveat). What it is: the standing father-selection rule. Rule: the mother's bud structure, terps, and effects lead in the F1; the father's vigor and resin sit underneath — a 'quiet donor.' It guards every donor pick and cross, including the autoflower track, where ruderalis dilution is the failure mode the rule exists to prevent. Use: the father-selection rule for all pairing decisions.

### U-BR02 — Per-strain workflow: sprout → clone → veg backup → S1
Source: MEMORY.md Facts (2026-09-24); daily notes 2026-09-24. What it is: the operating sequence per strain. Rule: sprout each strain, clone first, every mother backed up in veg before anything is flowered for breeding, then self each strain (S1) for feminized seed backups of the keepers — a few at a time, constrained by the Ohio 6-per-person/12-per-household count. Use: the workflow every strain run follows; order matters — backup before flowering.

### B-BR03 — S1 preservation project: clone now, mothers in veg, STS reversal, S1 seeds
Source: daily notes 2026-09-24 (S1 preservation project — APPROVED plan); goals/spg-and-sweet-tooth-clone-preservation-and-s1-backups/GOAL.md. What it is: the approved two-layer preservation plan for SPG + Sweet Tooth 3.1. Plan: clone now → keep untouched mothers in veg (layer 1: exact copy) → reverse one clone each with STS (sacrificed, not for consumption) → pollinate separate female clones → harvest S1 feminized seeds (layer 2: bloodline insurance). Status: APPROVED plan, execution sequenced a few strains at a time within the Ohio count; not recorded as done. Use: the preservation plan — the clone is the lock, the seeds are the vault.

### B-BR04 — Pairing decision pending: dimension unnamed, C99 favored, picks ready on his word
Source: goals/cannabis-breeding-pairing-research/GOAL.md; daily notes 2026-10-19. What it is: the open pairing decision. Status: PENDING — nine photoperiod mothers, no males on hand; research favors C99 for stability, fast flowering, and terp compatibility, while hemp and Holy Mountain carry potency or flavor tradeoffs; the final pairing is undecided and perg has not named the breeding-goal dimension (potency vs flavor vs speed vs experimentation). The Oct 19 stock update records the picks as ready once the dimension is named. Use: no pairing is decided; the dimension decision is perg's and gates the picks. Nothing ordered.

### R-BR05 — Lineup + provenance: nine strains, SPG/Sweet Tooth direct Breeder Steve cuts
Source: MEMORY.md Facts; goals/spg-and-sweet-tooth-clone-preservation-and-s1-backups/GOAL.md. What it is: the background record. Lineup: original SPG (from Breeder Steve), Sweet Tooth 3.1, Bubble Berry, Blueberry Muffin, Mazar, Cotton Candy Lobster, Zkittlez, Blueberry Grapefruit, Strawberry Cough. SPG and Sweet Tooth 3.1 are direct cuts from Breeder Steve via gabysi — the keeper-clone pipeline behind the two flagship mothers. Use: the lineup/provenance reference for all breeding work.

### R-BR06 — 31-donor Male Donor Shortlist: best-father pick per strain
Source: MEMORY.md Facts (2026-09-23). What it is: the donor research record. A 31-donor shortlist, a best-father pick per strain, widened beyond hemp strains, C99, and 'the holy mountain.' No males on hand. Use: the donor-selection reference; picks are evaluated against the quiet-donor rule (U-BR01).

### R-BR07 — Three-track stud-line plan: slow autoflower, hemp vigor, single stud line
Source: MEMORY.md Facts (breeding plan, 2026-09-25). What it is: the plan record. (a) Long-flowering x autoflower toward a slow autoflower keeping long-sativa effects (Ghost Train Haze + Sweet Tooth named; GTH is photoperiod, not auto; autos run very long under 24h light; autos can't be mothers — seed-only; ruderalis dilutes effects, so keeping long-sativa effects is the hard part). (b) Hemp growth speed into a giant cultivar, backcrossed into drug-types then crossed with Northern Lights #5 or C99, further backcrosses to stabilize quality on structure. (c) Cross those lines into the single stud line. Use: the plan reference; unexecuted, multi-year.

### R-BR08 — S1 knowledge: not identical copies, re-hunt only if the clone is lost, cubing converges faster
Source: daily notes 2026-09-24 (S1 re-hunt question; stabilization math). What it is: the standing genetics knowledge. S1s are NOT identical copies — expect variation, possible recessive traits surfacing; the living clone is the true backup. Re-hunt answered: only if the clone is lost. Sweet Tooth 3.1 is a BX2 worked line (SPG x Sweet Tooth backcrossed), so its S1s should be quite uniform, minimal selection. SPG is a clone-only selected phenotype (believed NL#1 standout, 35+ years as a cutting), NOT an inbred line, so its S1s will segregate with real variation and going back to seed would require a genuine hunt; Alpine Seeds revived SPG via S1 before. Stabilization framing: the S1 project needs NO stabilization — the clone is already the stable version and the seeds are the fire extinguisher; if seed-form SPG-close-to-mom were ever wanted, cubing (repeated backcross to the mother clone) converges faster than selfing chains. Use: the S1 knowledge reference; governs expectations for B-BR03.

### R-BR09 — Hemp card + ErdPurt lead: September finisher beats freeze survival; ~5-year introgression path
Source: MEMORY.md Facts; daily notes 2026-09-24. What it is: the hemp analysis record. ErdPurt leads the hemp shopping card (Sept 24 analysis: a September finisher beats freeze survival; ErdPurt appears first on page 2 of the uploaded hemp shopping card, called smart placement). Industrial-hemp vigor introgression is a hunt-and-backcross path (~5 years of pheno-hunting plus backcross rounds), aiming to produce something stronger than anything else on the market. Use: the hemp-track reference; long-horizon plan, not an order.

### R-BR10 — Legal context as stated: April 2026 federal medical Schedule III order; Ohio SB 56 binds the grow
Source: MEMORY.md Facts (home-grow legal, 2026-09-25); daily notes 2026-09-25 (GAO briefing). What it is: the legal-context record, stated as recorded — NO legal advice added. April 2026 federal medical Schedule III order; Ohio SB 56's 6-per-person/12-per-household limit and homegrown-gifting ban still bind him. GAO Sept 23: the DEA/FDA scheduling process is largely undocumented; the broader move to reschedule all marijuana has no final decision on the docket; scheduling decisions average three years. Briefing conclusion as recorded: almost nothing changes for him today — his grow lives under Ohio law, not federal scheduling memos; a broader Schedule III landing would ease research restrictions (lab testing, cannabinoid and terpene profiling) and soften federal penalties but would not override Ohio limits; the multi-year plan assumes the current legal landscape. Use: the context reference for sequencing decisions (including the U-BR02 count constraint); not legal advice.

### R-BR11 — Monster autoflower research: size profiles + the ruderalis-dilution caveat
Source: daily notes 2026-09-25. What it is: the research record. Monster Genetics' Monster Bruce Banner Auto (OG Kush x Auto Diesel XXL x Fast and Vast, 60% sativa, 25% THC, done in about 56 days, 550 g/m2 indoors, up to 700 g a plant outdoors); the giant-auto hall of fame: Dutch Passion's Auto Ultimate, Sweet Seeds' Big Devil XL (over 1.6 m tall, up to 650 g/m2 indoors), Barney's Farm GG#4 Original Glue Auto (up to 800 g/plant outdoors). Caveat: autos can't be kept as mothers (they flower on age — a seed-only workflow with no clone backups), and the autoflowering trait tends to drag ruderalis's diluted effects along with the size; keeping long-sativa effects on top is the hard part, which is where the quiet-donor rule (U-BR01) applies. Use: the autoflower-track research reference.

### R-BR12 — Cannabis research dossier: 52-entry strain catalog, growing guide, lab research
Source: daily notes 2026-09-26; ~/workspace/goals/local-voice-conversation-loop/files/cannabis-research-dossier.md (~106KB, 1069 lines). What it is: the compiled reference. 52-entry strain catalog (landraces, classic indica, classic sativa, modern hybrids, CBD/hemp-leaning; cross-referenced to the 9-strain lineup including SPG #38, Sweet Tooth #37, Ghost Train Haze #28 autoflower-track note, ErdPurt #51, and a Cotton Candy vs Cotton Candy Lobster flag); full growing guide (seed/clone, germination, veg/flower, media and systems including HPA aero notes for the FMI RMB pumps, nutrients, training, environment, IPM, harvest/dry/cure, Ohio SB 56 law); lab research (cannabinoid chemistry including decarboxylation kinetics, terpene/entourage evidence honestly graded — hypothesis, unproven per André 2024 PRISMA review — extraction methods, ECS pharmacology, therapeutic evidence grades, 12 landmark trials, HPLC vs GC testing, 20-paper bibliography, Sept 2026 GAO scheduling note). Bro-science claims flagged honestly (flush, fem-seed folklore, white ash, schwazzing). Use: the dossier reference; working notes in hidden_files/dossier/.

### R-BR13 — RDWC/HPA rig: 8-site RDWC record, HPA correction, HPA pillars
Source: daily notes 2026-09-24 (RDWC research file; HPA-not-HPS correction); goals/high-pressure-aeroponics-grow-system-build/GOAL.md. What it is: the rig record (breeding-relevant findings only). Current RDWC: 8-site (eight 9-gal buckets + 55-gal control reservoir), 1-inch returns, EcoPlus ~1100 GPH circulation pump, Active Aqua 110 LPM air, HLG Scorpion Diablo LEDs, TrolMaster Hydro-X Pro, Athena Blended line, $400 EcoPlus 1.5HP chiller deal pending. HPA correction: HPA means high-pressure aeroponics (a voice-dictation error), NOT high-pressure sodium lights. HPA plan: 3x FMI RMB valveless-piston metering pumps (verify flow-at-pressure per model; CAN hit 80–100 PSI), Beckhoff/TwinCAT deterministic control + Node-RED dashboards. Four HPA pillars: fine filtration + simple nutrients, no-buffer reality (accumulator + backup pump + pressure alarms mandatory), nozzles are consumables (buy NEW, never used), and the Beckhoff case is stronger for HPA than RDWC (second-scale mist timing, failover, interlocks are PLC territory); outdoor HPA is a root-zone thermal management problem and needs a greenhouse. Use: the rig/build reference; the RDWC file remains useful for pumps, tanks, plumbing, chiller, and markets.

### R-BR14 — Breeding-stock update 2026-10-19: five packs re-verified purchasable; Bodhi in stock; dimension still perg's
Source: daily notes 2026-10-19. What it is: a dated stock snapshot — stale until rechecked. All five top male-donor packs were re-verified purchasable, with no stock panic; Brothers Grimm lines going out of stock (Rosetta Stone, Feral Octane, Mota Hari), so the situation is moving; AK-47 listed at £70 vs $87.64 before — to be flagged at order time. Bodhi Mountain Temple confirmed in stock at ukskunkworks (verified 2026-10-19), superseding the September record of unconfirmed stock (£77.98/11, quiet-leaning, on the donor watchlist). The remaining piece is perg's: name the breeding-goal dimension (potency vs flavor vs speed vs experimentation) and the picks are ready. Use: the stock snapshot; availability and prices stale until rechecked; nothing ordered.

### A-BR15 — Acquisition list NOT AUTHORIZED: list exists, no purchase authorized or confirmed
Source: daily notes 2026-09-24. What it is: the standing non-authorization. The consolidated acquisition list (ErdPurt, Serious 6, hemp-cart cultivars, regular donor packs including Queen of Soul, Goji OG, and Motorbike) is an assistant recommendation only; perg asked for a list of what he needs to get, not to place orders. No purchase was authorized or confirmed. A fresh live stock-and-price verification of the buy-now tier was offered but not requested or completed; prices and availability from the August 30, 2026 shopping card or earlier research are stale until rechecked. Rule: NEVER order, buy, or source from this list without perg's explicit order. Use: the non-authorization record; the list must not be acted on.

*End of REMAINING RESEARCH THREADS section. No new research was done
for this section; every entry traces to a source listed in its header
line (registry, program files, goal file, or program record). Cube
phase-1 detail beyond the goal file was not invented: the detailed
records live on mrfloppy (~/llm/cube/) and were not re-read here.
Items marked "NOT ordered", "blocked", "queued", or "awaiting perg's
go" remain so; this section orders and launches nothing.*

## 2026-10-31 ADDITIONS — AP yardstick, null families, wire regimes, SpudCell pairings, research library

**Added 2026-10-31 on perg's order ("expand my map", use map first). IDs continue the per-family numbering already in use in this file (next free number per CLASS-PROG family: U-T09–U-T10, U-W05, R-T05–R-T06, R-W10–R-W13, A-T27–A-T28, A-W02). Mapping only — no new measurements were run for this section, no verdict was changed, and every entry traces to a source file listed in its header line. The SpudCell flags (preprint not read, gene count unsettled, dropped figure, secondary-only provenance) are preserved as recorded; nothing here upgrades a pairing, a diagnostic, or a null result into a theorem claim.**

**USE NOW**

### U-T09 — Analytic AP yardstick: expected AP count from N and k alone
Source: inventory/theoretical-equations-and-rederivations.md §5 (R-ANA, R-N2); wire-ap-n2-results.md (yardstick check). What it is: exact combinatorics for a uniform random k-subset of {0,…,N−1}: E = P · k(k−1)(k−2) / (N(N−1)(N−2)), where P = Σ_d (N−2d) = 624,975,000 for N = 50,000. Checked 2026-10-31 against the recorded 500-shuffle uniform-null means: A +0.018%, B −0.005%, W −0.006% (all within ~1.3 SE of the Monte Carlo mean); validated in substance on 23 new N2 windows (17 of 18 in-cap legs within the pre-registered ≤2 SE check; the one failure, 20261013-a at 2.26 SE, is marginal, largest relative deviation 0.054%). Use: the first-line expectation for any new wire window — compute E from N and k before running shuffles; shuffles are the check, not the first resort. Deployed as pure arithmetic (ap_yardstick.py, no tokens) — see R-W13.

### U-T10 — Null must match the construction it tests
Source: inventory/theoretical-equations-and-rederivations.md §5 (R-B, R-N8, R-N9); wire-ap-results.md; wire-ap-or-results.md. What it is: the standing rule proven by the AP program's own errors. The uniform-null z = +15.78 for sequence W was the wrong null's footprint: under the OR null (independently permuted sides, OR'd), the observed count sits BELOW the null mean (z = −3.81; null wire density 0.8351 > observed 0.8259 — the sides coincide more than independent). The block and segment-preserving nulls each absorbed a measured share of B's excess for the same reason. Rule: pick the null that matches how the sequence was built (uniform, OR, block, segment-preserving); never claim a z, p-value, or excess from a null whose construction the sequence violates; state which null every number comes from.

### U-W05 — z-ladder decomposition: profile an excess across null families of increasing faithfulness
Source: inventory/theoretical-equations-and-rederivations.md §5 (R-B, R-N8, R-N9, R-N10); wire-ap-segnull50-results.md. What it is: the decomposition method. B's Oct 7 excess across null families: uniform z = +17.28 → 100-tick blocks +9.50 → 1000-tick blocks +3.68 → segment-preserving +3.40 → finer (50 × 1000-tick) segments +1.81 (p = 0.036, fragile; residual +28,908, +0.012%; observed inside the null range; density profile closes 99.585% of the uniform-null gap). The drift step (density ~0.60 → ~0.75 at ~11,000 ticks in; 90.1% of APs cross-segment) is part of the same decomposition. Use: when an excess is found, run the ladder and report how much each faithful null absorbs; the ladder IS the finding (where the structure lives, by scale). Limit, stated in the protocol: the regress stops by design — finer profiling absorbs more by construction, so the next step after the finest profile is a different question, not a still finer profile.

**REFERENCE**

### R-W10 — Wire regime map: saturated / peer-silent / informative days
Source: wire-ap-n2-results.md (regimes; headline). What it is: the 23-midnight-chunk replication (N2, first 50,000 ticks per chunk, sequences A and B, 100 shuffles). Regimes: saturated (a ≈ 0.99, b = 1.0) Oct 5, 17, 18, 19, 20, 30, 31; peer-silent (b = 0.0 exactly) Oct 11, 12, 13, 14, 15, 21, 22, 23, 24, 25, 29; informative Oct 8, 9, 10, 16, 28. 28 of 46 legs fall outside the (0.2, 0.8) density cap and are excluded by the pre-registered rule — reported, not claimed. Replication verdict PARTIAL: B excess in 3 of 4 in-cap windows (majority), A null in 7 of 14 (exactly half, not a majority). Use: the regime reference for interpreting any single window — single-day results do not generalize across regimes; the uniform null fails in both directions across the month (deficit windows to −5.52%, z = −21.20).

### R-T05 — C1: the theory's miss tracks neither density, day, nor regime
Source: wire-ap-corr-results.md; inventory/theoretical-equations-and-rederivations.md §5 (R-C1). What it is: the theory–observation correlation on recorded numbers only (19 in-cap legs; residual ratio r = (observed − E)/E). Density vs r: Pearson +0.072, permutation p = 0.780. Day vs r: −0.353, p = 0.134. Density vs |r|: +0.281, p = 0.248. Regime means (A-legs): informative +0.545% vs B-silent −0.426%, difference +0.97pp, p = 0.612. No pair meets the pre-registered tracking rule (|r| > 0.5 and p < 0.05). Sensitivity: including the Oct 16-b anomaly flips the density correlation to −0.385 — one leg moves Pearson by 0.46, so no correlation claim at this n survives its own sensitivity check. The observed-vs-E Pearson of 0.999 is recorded as VACUOUS (both scale as k³), not a finding. Use: the analytic theory is unbiased across density, day, and regime at this resolution; the misses are idiosyncratic, not systematic. Thought events (JEV) correlate with theory only in verdict pattern (diagnostic yes, theorem no) — no shared numeric scale, no number forced.

### R-W11 — Oct 16-b anomaly: +207% AP excess, in-cap, flagged not claimed
Source: wire-ap-n2-results.md (anomalies flagged, not claimed); inventory/theoretical-equations-and-rederivations.md §5 (R-N2). What it is: 20261016-b, density 0.3252, observed 66,018,736 vs analytic E 21,487,211 (+207.25%, z = +561.65) — the largest excess in the AP program by two orders of magnitude. The sequence carries three times the progressions a random set would: clumped/bursty arrangement, not a density effect. No mechanism is named; no Kelley–Meka construction follows. Use: the flagged anomaly record; the subject for a different question (arrangement structure within a bursty regime), not an application of the theorem. The AP diagnostic here detects regime, not a stable wire property.

### R-T06 — SpudCell / mirror-life pairing statuses: 16 pairings, none confirmed, flags preserved
Source: inventory/spudcell-mirrorlife-pairing-map.md §2, §5, §6, §7; inventory/spudcell-mirrorlife-verbatim-filed.md. What it is: the record-phase pairing map (P-01–P-16) against sciences already on record. Tally: ANALOGY 7, VOID-UNDECIDED 2, DESIGN 5, CONTRAST 1 (P-12: repetition-hardening, curation-steering, and hand-introduced selection are three mechanisms, not one correlation), PROVENANCE ONLY 1 (P-13, Adamala). No pairing is CONFIRMED and none is REFUTED. Strongest relation P-01 (engineered selection × breeding) breaks on the quiet-donor contrast. Gaps found: G1 no chirality/handedness measurement on record; G2 no protocell/minimal-genome chemistry on record; G3 no Markov-table hardening rule on record. Sweep §7 (12 candidates W-01–W-12, 2 leads) is kept separate from the record pairings and unverified. Flags preserved: preprint full text NOT read; gene count UNSETTLED (7 vs 9 DNA molecules, 36 genes); the "10% to 38%" figure DROPPED as unverified; the Adamala connection is SECONDARY REPORTING ONLY, not verified against the Science paper; the Arc Institute thread UNRESOLVED. Use: the audit record for the SpudCell/mirror-life threads — read as audited candidates and guards, not correlations; settlers must run before any pairing is claimed. No theory entry was created by the pairing file.

### R-W12 — Research-library snapshot on mrfloppy: 182 files, inert, dated 2026-10-31
Source: ~/llm/voice-loop/research-library/RESEARCH-INDEX.md + MANIFEST.sha256 (mrfloppy). What it is: the snapshot of perg's useful information applied to the local AI on his order: inventory files, research registry, wire-tick data map, all wire-AP trial protocols/results/scripts plus N2 per-leg JSONs, the full JEV file set, SAT solvers + v3 report, EIT solver/tests/data, and the yardstick module — 182 files, every hash verified on arrival, with a standing-rules index (verbatim files unmodified, flags travel with claims, diagnostic ≠ theorem, ternary verdicts, perg's framings credited to him). Deliberate exclusions: personal memory files, the live use-map copy (already deployed, no duplicate), credentials/secrets. Use: the local reference GLaDOS and her workers read without Muse tokens; workspace copies remain canonical; the library is inert files only — no services, no cron, no background work was started by applying it.

### R-W13 — Yardstick shelf-tool wiring: registered, verified, takes effect on next service start
Source: deployment record 2026-10-31 (mrfloppy ~/llm/voice-loop/glados_tools.py + ap_yardstick.py). What it is: ap_yardstick_tool registered as a shelf-tool entry in TOOL_INDEX (name ap_yardstick; args n, k, observed; handler ap_yardstick_tool), calling the deployed ap_yardstick.py module (R-ANA formula, pure arithmetic). Backup glados_tools.py.bak-yardstick-20261031 made before patching; patched file compiles and the entry + wrapper were verified present. Status: wired but NOT YET ACTIVE — no service was restarted, and the wiring takes effect on the next voice-loop service start, on perg's word. Use: the activation record; do not report the tool as live until a restart has loaded it.

**AVOID**

### A-W02 — Oct 28-b +1,062%: cap-excluded, NOT an excess, do not claim
Source: wire-ap-n2-results.md (excluded legs; anomalies flagged, not claimed). What it is: 20261028-b, density 0.0857 (outside the pre-registered (0.2, 0.8) cap), observed 4,566,034 vs analytic E 392,847 (+1,062%). The clumping shape recurs (same shape as the Oct 16-b anomaly at low density), which is why it is recorded — but the cap rule excludes it, so it is NOT counted as an excess and must not be quoted as one. Rule: AVOID claiming, importing, or ranking this leg as an AP excess; cite it only as a cap-excluded observation with the density stated.

### A-T27 — D1 pairing-invariance trap: a pairing-invariant statistic has no permutation null
Source: inventory/theoretical-equations-and-rederivations.md §M1 (pairing-invariance proof); jev-discrepancy-protocol.md (Amendment A); jev-discrepancy-results.md. What it is: the Komlós-trial design error, caught before belief. D1 = fast-only − slow-only = F − S, and any relabelling preserving F and S leaves D1 unchanged — so D1 has no permutation null and the first run's p-values (all 1.0000) are VOID, recorded as void, not as findings. The amended statistic is the slow-only count under permutation of the slow labels (5,000 shuffles). Rule: AVOID testing any pairing-invariant statistic against a label-shuffling null; prove or check invariance BEFORE counting, and if the statistic is invariant, the null is degenerate by construction — void the run, amend the statistic, re-register, re-run. The void must never be reported as a null result.

### A-T28 — W-02 citation UNVERIFIED: do not rely on the claimed Schwarz-Schilling reference (VERIFY-FIRST)
Source: inventory/spudcell-mirrorlife-pairing-map.md §7 (sweep candidate W-02). What it is: the sweep's claimed citation — Schwarz-Schilling et al., Nature Communications 17:1028 (2026), DOI 10.1038/s41467-025-67772-8, "30-protein PURE + 36-protein extension" — was NOT confirmed by DOI search; what returned was an earlier paper, DOI 10.1038/s41467-020-14694-2. Status: CITATION-UNVERIFIED. Rule: AVOID relying on, quoting, or building on the W-02 claims (including any 30/36-protein figures) until the citation is verified against a primary source; the related 2020 PURErep paper is noted, not substituted. The flag stays attached wherever W-02 is mentioned.
