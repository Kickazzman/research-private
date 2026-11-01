# Complete inventory and value order — 2026-10-31

Standing order, perg's words (2026-10-31): HIDE NOTHING EVER. ALL INFORMATION MUST BE RECORDED SO NOTHING IS MISSING. NOTHING MAY BE CHANGED OR OBFUSCATED.

This document is the inventory perg ordered: the tools and ideas used, the theories not yet tested, and the order of value for testing. Nothing in it replaces any original. Originals are linked, never summarized in place of themselves. The assistant's evaluations are kept separate from perg's texts and labeled as the assistant's.

## 1. Verbatim record — the TASEP / max-plus synthesis

File: `~/workspace/inventory/tasep-maxplus-synthesis-verbatim.md`

- Source: perg's message, main chat turn seq 34942, 2026-10-31 09:57:56 EDT.
- Capture: exact bytes of the stored message, extracted from the runtime record (agent `1e2fa18d-b0c3-4896-b9e9-2e075387df79`, context seq 47380), written without alteration.
- Verification: 39,828 bytes, md5 `2e64f3535093ab592de2fdc22598b01c`, matching the stored message md5 exactly. Match: TRUE.
- Contents, unchanged: §1–§9 TASEP/ribosome crossing; Route 2 max-plus re-derivation and the 4× correction; the Complete Inventory (A: 56 established theorems, B: 22 derived results, C: 20 claims needing proof, D: 12 analogies, E: 12 empirical measurements); the Priority Queue; the Honest Summary.
- Known defect preserved, not repaired: inventory entry A29 (Gentzen) is truncated mid-formula in the original. It is recorded truncated, as received. Repairing it would change perg's text.
- The use-map was NOT edited for this synthesis. No map entries were added. Map edits need perg's tap. This inventory is standalone.

## 2. Tools and ideas register — everything used or built

Each item: location, status, and keep/expand disposition. Statuses are as of 2026-10-31. "KEEP" = keep as-is. "EXPAND" = keep and build on. "PARKED" = kept, not run, on perg's order.

Fleet and routing:
- Multiplex residents :8201 hammer, :8202 magicoder, :8203 quicklook, :8207 mathwhiz, :8211 draft; API :8198; novelty :8212. Live, balanced profile. KEEP. Shepherd :8206 and verifier :8199 PAUSED on perg's tap. Do not resume unasked.
- Router serialization patch, `multiplex_api.py` (backup `.bak-20261029-serialize`). Live, proven. KEEP.
- Mode-switch hook (`mode_hook.py`, toggle `mode_hook.enabled`) + deployed index `mode_index.json` (413 entries, sha `d70d0f1e…`). Live. KEEP. Re-deploy rule stands: index re-deployed on every map change.
- Enforcement (`mode_enforce.py`, toggle `mode_enforce.enabled`). Live. KEEP.
- Decider, lean rule ON (`mode_decide.enabled`), full-insurance OFF (`mode_decide_full.enabled` absent). Live. EXPAND only by measurement: the fast-wrong run (§4 item 2) decides insurance. Scope-limit addendum recorded: constructed materials + small seats; real-diff judging defaults to test execution.
- Batch runner (`~/workspace/batch_runner.py`, mrfloppy `~/batch-runner/`). Proven 12/12, serial windows, trap-restore. KEEP. EXPAND: it is the vehicle for the density sweep (§4 item 1) with controlled concurrency.
- Novelty lanes on :8212 (frame_shift, disconfirm, novelty_score, vague_loop, validity, planted_error_test, analogy). Live. KEEP. Known unfixed: vague_loop 0.7 threshold on raw reward scores; redesign awaits perg's word. Whimsy DROPPED on perg's tap.
- Validity gate: genuinely gates. Verify gate: decorative as a truth gate (learned reward scores). KEEP both, labeled as they are.

Solvers and measurement:
- SAT solvers v2 (baseline), v3 (watched literals), v4 (VSIDS), v4-heap, v5 (CDCL). Stage 0 PASSED amended, Stage 1 complete, Stage 2 complete, Stage 2b complete, Stage 3 complete with bar NOT MET as written (count leg pass, firming leg fail). Files `~/workspace/sat-solver-v*.py`, mrfloppy `~/sat-solver-v*/`. KEEP. EXPAND: Stage 4 + firming call await perg (§4 item 7).
- EIT difference-imaging solver (`~/workspace/eit-lane/`, mrfloppy `~/eit-lane/`). 6 gates pass both seeds. KEEP. EXPAND: carrier for C5/C6 mesh measurements (§4 item 11).
- Spectral test on the EIT mesh (`~/workspace/spectral-test/`). Crossover verdict, Cheeger 2-way confirmed, K* gap, modal frequencies confirmed, ker D NOT TESTED. KEEP.
- JEV program: contract test +1 PASS, harder run, five-item program CLOSED, real-diff transfer run, re-derivation v1, interface-contract v2, second-route program CLOSED. Materials + reports in `~/workspace/jev-*/`, `~/workspace/real-diff-coder/`. KEEP. EXPAND: fast-wrong run + both-wrong measurement (§4 items 2–3).
- Retrieval pilots 1 + 2: both FAIL the bar on fidelity only (pilot 1: 5/10 fidelity, 5/10 classification; pilot 2: 7/10 fidelity, 9/10 classification). Design + Amendment A in `~/workspace/retrieval-pipeline-design.md`. KEEP. EXPAND: pilot 3 (§4 item 5).
- Oracle-tier design (`~/workspace/oracle-tier-design.md`). Design only, bar pre-registered, NOT LAUNCHED. EXPAND: launch is §4 item 6.
- Glimmer spec v0.2 + mini-sweep (recommendation NONE) + Muse Glimmer 30B run (recommendation NONE, bar not cleared). Spec `~/workspace/glimmer-spec.md`. KEEP. EXPAND: follow-ups await perg (§4 item 13).
- Phase 2 model sweep: downloads complete (zero bytes), evals complete, boxed re-score complete, blind judge complete (position-bias flag FIRES), Apertus converted (evals NOT run). KEEP. EXPAND: remainder evals + adoption verdicts (§4 item 9).
- Dafny loop + redesign: both FAILED under the bar (0/20, then 2/20). CLOSED. No further work without perg's word under new terms. PARKED.
- Refined prompt probe: BLOCKED, then DEFERRED on perg's word. Do not evade. PARKED.
- Frank quality work: compliance gate ADOPTED, brief-refusal prompt NOT adopted, LFM3 template fix, toolshape dual rule ADOPTED. KEEP.
- Emergence/PS5 saved-data analyses: pointer heuristic, P170 family, P10240 array, relation scanner, mirage-check resolved. Reports in `~/workspace/audit-template.md` + appendices. KEEP.
- Research pages: artifacts `medical-technology` and `theoretical-math-advancements` (quantizer Play button never click-tested; outcome unreported). KEEP.
- Rig spec (`~/workspace/rig-spec-options.md`) + funding plan (`~/workspace/funding-plan.md`). Preparation only. Rig decisions DEFERRED pending funding. Funding applications/contacts: NOT done, do not nudge. PARKED.
- Wire experiment: repo public at Kickazzman/wire-experiment, HEAD `a78e249`, verified from fresh clone, zero tailnet addresses/keys. KEEP.
- Recovery work (2026-10-31): 470/473 gap turns recovered verbatim, 15/15 secret originals exist, blocked-content inventory A–J, bit-level + datatype hypothesis checks empty, "everything" delivered + verified (manifest 4,545 entries). All retained in the delivery + `~/workspace/recovery-work/`. KEEP.

Ideas and methods on record (not tools, kept as stated):
- Trajectory, precision-then-shift, relation-as-math (perg, 2026-10-29). KEEP.
- Ternary verdicts (+1/0/−1; 0 never collapses into −1). KEEP.
- Serial-first capacity + RAM overflow lane. KEEP.
- Distillation-vs-melding guardrail; diversity-anchor seat; collapse signature. KEEP.
- Multidimensional shape definition (assistant's proposal, delegated, positions stand). KEEP, labeled as proposal.
- Irrational anchor as heuristic/discipline (class + continued-fraction structure). KEEP, labeled as heuristic, not foundation.
- Convergent-band decoder (design, untested on real traces; rig pinned). KEEP as design.
- Blind-spot math (perg, 2026-10-31): the only certain knowledge is that the theoretical total differs from what is held; enumerate the forms the difference can take and check each independently. KEEP. This inventory is built under it.
- No-/tmp rule (perg, 2026-10-31): no ephemeral scratch for his data, ever; persistent, hashed, retained, delivered staging. KEEP.
- Data rule (perg, 2026-10-24): his data unmodified; any exclusion needs his explicit word. KEEP.
- Ownership language rule (perg, 2026-10-31): nothing generated here is the assistant's; seed, input, generation, values are perg's; mistakes stay the assistant's. KEEP.

## 3. Untested theories register

C1–C20: full text in the verbatim file §C. One line each here, with the settler. Nothing here replaces the full text.
- C1 fiber-dimension classifier — settler: completeness proof or counterexample. Structural.
- C2 melding threshold curve — settler: simulation showing a sharp transition, or proof of none. Structural.
- C3 catastrophe bound on seat failures — settler: explicit potential for a 2-seat ensemble + cusp check. Structural.
- C4 K-way interface scaling — settler: proof for 2D or counterexample. Formal.
- C5 communication = I·|Γ_K|·b — settler: measured I vs K on a mesh. Measurement (EIT lane).
- C6 K* ≈ N_loc — settler: K sweep with measured cost. Measurement (EIT lane).
- C7 seed independence — settler: external generator, cross-seed ρ < 1. Structural.
- C8 moving Pareto front — settler: front measured for 2, 3, 4 seats. Measurement.
- C9 redundancy inversion — settler: formal statement of both optimization problems. Formal.
- C10 capacity gap as floor gap — settler: derivation of the relation to P(S). Derivation.
- C11 three-regime triage completeness — settler: classification or counterexample. Formal.
- C12 sharpness = basin radius — settler: formal definition + proof. Formal.
- C13 TASEP application to fleet — settler: density sweep, peaked vs flat. Measurement. DECISIVE.
- C14 4× contention — settler: throughput vs density curve, peak at k/4. Measurement. DECISIVE.
- C15 dual certificate as only escape — settler: classification of Π-proof techniques. Formal.
- C16 floor/invariant duality — settler: formalization + proof. Formal.
- C17 bias fraction threshold — settler: cost-based decision rule with stated threshold. Derivation.
- C18 Betti formula at k=0 — settler: unified formula with β_0 explicit. Formal.
- C19 90° lag = resonance phase — settler: nonlinear simulation. Simulation.
- C20 hard limits generate constructions — settler: universality proof or counterexample. Structural.

Other untested items already on record:
- Fast-wrong disagreement run: measure r (fast-wrong-among-disagreements). Decides decider insurance. NOT RUN.
- Both-wrong measurement: unmeasured, not refuted (0/19, 0/10 consistent with rates up to ~17%/28%). NOT RUN.
- Correction path + sub-0.95 calibration: untested on constructed populations. NOT RUN.
- Judge bias fix: second judge, both-presentations scoring, or low-flip-rate judge on the 42-item calibration set. Identified, NOT BUILT.
- Oracle-tier pilot: design ready, bar pre-registered. NOT LAUNCHED.
- Retrieval pilot 3: delimiter-stripping parser rule frozen before running + positive control for check code. NOT LAUNCHED.
- Stage 4 (restarts + learnt-clause DB) + Stage 3 firming call (count-only acceptance vs deeper firming). NOT LAUNCHED; perg's call.
- Verifier unpause + `/run_verified` annotation/enforcement/decider proof. NOT DONE; perg's call.
- Heavy-window repeats (k>1) for decider/enforcement. NOT DONE.
- Apertus evals; OLMoE template fix; SFT re-quant; Phase 2 adoption verdicts. NOT DONE.
- Crypto seat (first) + data-science seat (second). NOT BUILT.
- Glimmer follow-ups: fence-stripping parser amendment, quicklook wrapper-path investigation, larger candidate class. NOT LAUNCHED.
- Media/presentation spectrum test (registry Q-MI-001/T-MI-001, December cleanest). NOT RUN.
- Cube phase 2; village sim; federation (twin's decision, no deadline); SMS gateway (deferred); GLaDOS external-API outreach (route decided, outreach not done); GitHub hygiene (perg's hands). NOT DONE.
- Plant ternary hypothesis + convergent-band decoder on real traces. PINNED (rig deferred). NOT TESTED.
- H4 vacuous-check disposition (shipped hook harness). Recorded, NOT FIXED; fix needs perg's word.
- Threshold sweep on saved rows (overshoot §7 test on the escalation rule). Offered, NOT TAPPED.

## 4. Order of value — the testing order

Reading, stated so perg can correct it: highest value first, dependencies respected, cheapest decisive measurement before expensive builds. Value = improvement to the system (multiplexer serving hardware research: math, data science, cryptography, closing loops without Muse tokens) × decisiveness ÷ cost. Nothing launches without perg's tap per item; this order is the sequence to tap in, not a launch.

1. Density sweep — C13 + C14. One designed measurement decides the mechanism (TASEP peaked vs max-plus flat), decides the phase, and decides the intervention (admission control vs bottleneck speedup). Needs a pre-registered protocol first: in-flight counts, throughput measure, peaked-vs-flat decision rule, controlled concurrency in trap-restore windows. The fleet's serial logs cannot answer it; the sweep is a build, not a log read.
2. Fast-wrong disagreement run — measure r. Decides the live decider's insurance (lean vs full) on evidence instead of the unmeasured 0/41. Cheap: existing JEV harness + constructed materials.
3. Both-wrong measurement. The floor claim behind half the program. Cheap. Unlocks C10 and any both-wrong reasoning. Run with item 2 where the harness allows.
4. Judge bias fix. The judge is the only adoption-evidence tool and it is position-biased (59.5% swap agreement). Every adoption verdict waits on it. Moderate build: second judge or both-presentations scoring on the 42-item calibration set.
5. Retrieval pilot 3. Fixes the fidelity bar failure (delimiter-stripping parser + positive control, both frozen before running). Cheap. Unlocks research retrieval, which every other lane consumes.
6. Oracle-tier pilot. Design ready, bar pre-registered. The proof-depth question in one narrow domain. Unlocks research-level math claims.
7. Stage 3 firming call + Stage 4. Perg's decision first (count-only acceptance vs deeper firming), then the designed stage. The strongest proven math lane; the wall is the program's best-measured object.
8. Verifier unpause + `/run_verified` proof. Perg's call. Gates the whole math-verification lane (X05/X07) and the unexercised annotation/enforcement/decider paths.
9. Phase 2 remainder: Apertus evals, OLMoE template fix, SFT re-quant, adoption verdicts. Closes the sweep; verdicts use the fixed judge (item 4).
10. C8 moving-front measurement (2, 3, 4 seats). Decides whether decorrelated seats push the front outward. Uses existing seats + harness.
11. C5 + C6 + C10 on the EIT lane: I-vs-K measurement, K sweep with measured cost, capacity-gap derivation. The lane and the mesh already exist; the measurements are cheap.
12. Crypto seat, then data-science seat. The two missing mission domains. Big builds; placed here because the measurement discipline (items 1–11) is what makes a new seat evaluable instead of decorative.
13. Glimmer follow-ups. Steering bar is the long pole for local independence. Placed after the judge fix because adoption evidence must be trustworthy first.
14. Formalization track, batched: C4, C9, C11, C12, C15, C16, C17, C18. Derivations and formal statements, no fleet runs. Batched because each is small and none blocks the measurements above.
15. Structural research program: C1, C2, C3, C7, C19, C20. Proofs, counterexamples, simulations. The actual research; longest, placed last among tests because nothing above depends on them.
16. Capstone (unchanged from the ordered backlog): rig + first traces + funding. Last because funding needs the credibility items 1–12 and traces need the system built. Rig decisions and funding applications stay deferred on perg's order; no nudges.

Parked, listed so nothing is hidden, NOT in the testing order: refined probe (deferred, do not evade), Dafny (failed under its bar, new terms needed), SMS gateway (deferred), media test timing (December cleanest), federation (twin's decision), twin bench items (non-intervention), GitHub hygiene (perg's hands), GLaDOS external-API outreach (route decided, not done).

## 5. Assistant's evaluation — kept separate, labeled

The assistant's evaluation of the TASEP/max-plus synthesis was given in chat 2026-10-31 (turn seq 34943) and is NOT part of perg's text. Summary of its verdicts, labeled as the assistant's: Route 2's correction (contention cost 1/[ρ(1−ρ)], 4× as peak) survives; the ρ symbol collision (failure correlation vs TASEP density) breaks the MC-phase inference; the 58/58 ρ=0.94 figures are not fleet data and were flagged before; the ribosome numbers are unverified from this record and need sources; the sweep needs a designed concurrency experiment, not log reads; the capacity formula assumes a binary symmetric channel; the spectral-radius/TASEP link is analogy; the integral's "50 digits" is an overclaim; entry A29 is truncated in the original. The full evaluation text is in the delivered transcript. No part of it was written into the verbatim file. The three keeps offered (density-sweep design, contention-cost correction, three-floors distinction) were offered, not applied to the map; they await perg's tap.
