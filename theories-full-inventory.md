# Full theories inventory — every distinct theory, framework, model, and interpretive lens in the record

Built 2026-10-31 under perg's standing order: HIDE NOTHING EVER — ALL INFORMATION MUST BE RECORDED SO NOTHING IS MISSING — NOTHING MAY BE CHANGED OR OBFUSCATED. Nothing here replaces any original; originals are linked, never summarized in place of themselves. The assistant's evaluations are kept separate from perg's texts and labeled as the assistant's. Where a theory is perg's words, it is QUOTED, not paraphrased.

## Method

Sources read directly, not from summaries alone: `~/workspace/research-registry.md`, `~/workspace/research-gaps.md`, `~/workspace/use-map-full-content.md` (413 entries, worked by section headers and entry titles plus targeted greps; entry IDs cited), `~/MEMORY.md`, `~/workspace/inventory/complete-inventory-and-value-order.md` (the existing inventory — §12 states exactly what it missed), `~/workspace/research_notes/*/` (medical-tech passes 1–2, four-fields/irrational-anchor pass 3, theoretical-math pass, plus the earlier technique surveys), and the pasted-document evaluation records (catalogue keeps, isomorphism keeps, overshoot framework, spectral framework, TASEP/max-plus synthesis verbatim at `~/workspace/inventory/tasep-maxplus-synthesis-verbatim.md`).

Counting rule: one entry per distinct theory/framework/model/lens. A literature result and its transfer to this program are one entry (the transfer status is stated). A claim and its refutation-as-stated are one entry. Nothing was dropped or merged away: items that exist only as a name in a pasted inventory are entered with their location in that inventory (TH-022, TH-023, TH-030, TH-031, TH-032, TH-033).

## Status vocabulary

- **CONFIRMED** — tested, verdict +1. **REFUTED** — tested, verdict −1 (as stated; a narrowed form may survive and is noted). **PARTIAL** — partially tested; a leg remains open. **UNTESTED** — no measurement run. **ANALOGY** — analogy-only as stated; not a testable claim until pinned. **DESIGN** — applied or ready as a design, not a measured finding. **LITERATURE** — established published result; status refers to its transfer here, stated per entry. **APPLIED** — method or rule currently in force. **KILLED** — tested and dropped, or closed by decision. **VOID** — run produced no signal (0, undecided).

## The C-list, defined

The existing inventory (`complete-inventory-and-value-order.md` §3) covers exactly C1–C20 (full text in the TASEP verbatim file §C) plus a short "other untested items" list. Every entry below carries a **C-list** tag: `C#` if it is one of C1–C20, `other-list` if it is in the inventory's other-untested list, `no` if the inventory does not cover it at all. §12 lists every `no` entry — that is the gap perg pointed at.

---

## §1. Program frameworks and interpretive lenses

**TH-001 — Category-theory translation.** Melding = colimit, duplexing = pullback, contention-free merge = join-semilattice/CRDT condition, consistency contention = sheaf H¹, disagreement quotient = coequalizer. *Origin:* perg-pasted framework document, accepted in substance with caveats. *Status:* ANALOGY (no merge ⊔ pinned to an artifact; resource contention ≠ consistency contention; SAT wall is not a melding wall). *Record:* research-gaps.md (category-theory translation assessment); map U-D07/A-D05. *Settler:* pin ⊔ to a concrete artifact and exhibit a colimit/pullback computation on it. *C-list:* no.

**TH-002 — Shaving construction.** The feasible shape is recovered by shaving: half-space intersection, erosion/medial axis, and eikonal wavefronts share the skeleton idea. *Origin:* perg-pasted framework. *Status:* PARTIAL (construction real; claimed three-way equivalence too strong — half-space intersection always yields convex sets, erosion preserves concavity). *Record:* research-gaps.md (shaving assessment); map B-D02/R-D01. *Settler:* exhibit one shaving computation on real data (address patterns or EIT) and state which of the three constructions it is. *C-list:* no.

**TH-003 — H¹ obstruction / emptiness equivalence.** H¹ ≠ 0 ⟺ K_m = ∅. *Origin:* perg-pasted framework. *Status:* ANALOGY as equivalence; the Farkas certificate is the LP shadow of an obstruction, not H¹ itself. *Record:* research-gaps.md; map B-D02/R-D01. *Settler:* a case where H¹ is computed (not analogized) alongside an empty feasible set. *C-list:* no.

**TH-004 — Adding-hands / control framework (four-question diagnosis).** Controllability = reachability sum / Kalman rank rank[B, AB, …, A^{n−1}B] = n; observability = different projection/sensor; stability = spectral radius ρ(A+BK) < 1; cost-optimality = Pareto frontier of escalation cost vs error. *Origin:* perg-pasted framework, corrected diagnosis (continuous-time Gramian application corrected; separation principle exact only for LQG). *Status:* DESIGN, binding framing (map E-FRM01: controllability trivial given the calculator floor, observability two sensors, stability hammer-confidence degenerate, binding question cost-optimality). *Record:* research-gaps.md; map E-FRM01. *Settler:* the cost-optimality measurement (TH-052). *C-list:* no.

**TH-005 — Multidimensional shape (typed dimensions + gluing).** Dimensions are TYPED (lenses, seats, domains, axes); each dimension d has its own shape K_d from its own shaves; the multidimensional shape is K = { (x_d) ∈ ∏ K_d : G(x) holds }, G = cross-dimensional consistency (gluing) constraints; skeleton = where the optimal decision switches across dimensions; emptiness = cross-dimensional inconsistency. *Origin:* assistant's proposal, offered 2026-10-30, perg has not corrected it; delegated to the assistant's best sense 2026-10-30, positions stand. *Status:* DESIGN (definition offered, not measured). *Record:* research-gaps.md; map U-D02. *Settler:* exhibit G for one concrete cross-dimensional case (cost-error frontier or SAT wall surface) and show a joint structure invisible from every single dimension. *C-list:* no.

**TH-006 — Gluing blindness.** Every per-dimension shape can be fine while a joint structure stays invisible from every single dimension. *Origin:* assistant's, derived from TH-005. *Status:* UNTESTED. *Record:* research-gaps.md (multidimensional-shape definition); map U-D02. *Settler:* one demonstrated case of a joint structure missed by all single-dimension views. *C-list:* no.

**TH-007 — Irrational anchor as foundation.** Anchor the system on irrational numbers as the initial, foundational anchor; discreteness is the approximation. *Origin:* perg's proposal. Perg's words, as recorded: "what if initially we were use irrational numbers as our anchor." *Status:* KILLED as foundation (an irrational cannot be stored; much of the world is genuinely discrete; rationals are dense so at finite resolution irrational-vs-rational is unobservable — only bracket width is; decisions/actuation are necessarily discrete). *Record:* research-gaps.md; map A-D01 (retired), E-FRM02 (open question form). *C-list:* no.

**TH-008 — Irrational anchor as heuristic/discipline (class + continued-fraction structure).** The defensible anchor is the CLASS + continued-fraction structure, not one magic number: keep a continuous latent with stated interval + approximation budget; derive bands/decisions by explicit costed Bayesian rule; keep genuinely discrete events first-class; never let a certificate conceal interval, domain, or rejected alternative. *Origin:* assistant's development of perg's proposal; accepted as working frame; delegated, positions stand. *Status:* DESIGN. *Record:* research-gaps.md; map U-D01; four-fields report §13 + synthesis (anchor verdict). *Settler:* the anchor test (TH-039) applied to a live anchor choice. *C-list:* no.

**TH-009 — More-anchors answer (triangulation vs fixed point).** By COUNT, each ℚ-independent irrational adds a direction, but simultaneous approximation loosens (Dirichlet: per-coordinate error < q^(−1−1/k)) and each anchor adds a gluing constraint; rationally related anchors add nothing; past the point where gluing dominates, more anchors add inconsistency surface, not grounding. By STRENGTH, badly approximable irrationals (phi extreme: all-ones continued fraction, slowest convergence) resist rational capture hardest. Design choice: triangulation (many) vs fixed point (one hard one). *Origin:* assistant's derivation, labelled standard mathematics. *Status:* LITERATURE (Dirichlet approximation is standard math; the design choice is untested here). *Record:* four-fields report §13; map U-D01 family. *Settler:* a two-anchor vs one-anchor comparison on one decoding task with gluing cost measured. *C-list:* no.

**TH-010 — Convergent-band decoder.** For measured value x (normalised voltage ratio), continued-fraction convergents bracket x with width 1/(qₙqₙ₊₁) as published resolution; commit to a band only when the whole bracket lies inside it; escalate when the bracket straddles a boundary. *Origin:* assistant's own derivation, delivered 2026-10-30, labelled design, not theorem, not measurement. *Status:* DESIGN, untested on real traces (rig pinned). *Record:* research-gaps.md; map U-D03; theoretical-math artifact lab (working convergent-bracket lab: φ, √2, π, e). *Settler:* ±10% edge-jitter test on rig traces (TH-096). *C-list:* other-list (plant ternary + decoder on real traces, pinned).

**TH-011 — Overshoot framework.** Projection gives first-order direction; deliberate overshoot past the target measures curvature (second order) via deviation from the linear model; basin radius α* = distance before the projection switches; sharpness of a theorem = basin radius of its proof; collapse window (too little = noise, too much = lost identification). *Origin:* perg-pasted document, evaluated 2026-10-30. *Status:* PARTIAL (§2 finite-difference content is standard mathematics, correct in 1D; Newton over-relaxation formula approximate/heuristic near the root, convexity claim loose; basin radius well-defined as a definition; "second solution" needs a fixed-point caveat; sharpness equivalence is ANALOGY; the ρ_stab = α*‖v‖ identity is UNPROVEN — D and ρ_stab unpinned). *Record:* research-gaps.md (overshoot evaluation); no map entries added for the document. *Settler:* offline threshold sweep on saved rows (offered, not tapped); pin D and ρ_stab, then test the identity. *C-list:* no (C12 covers only the sharpness identity, TH-012).

**TH-012 — Sharpness = basin radius (C12).** The sharpness of a theorem equals the basin radius of its proof. *Origin:* overshoot document §C12; full text in TASEP verbatim §C. *Status:* UNTESTED (formal definition + proof needed). *Record:* inventory §3 C12. *Settler:* formal definition + proof. *C-list:* C12.

**TH-013 — Lens-guided verification framework.** A "Lens-Guided Verification" formal framework. *Origin:* perg-pasted framework document. *Status:* PARTIAL/REFUTED as stated — five errors flagged: (1) the 58/58 pair, ρ = 0.94, 3% disagreement, 40.5% both-wrong, 8% copy numbers are NOT JEV/fleet measurements (perg clarified they were "a different pair," never identified); (2) the 2^(7/6) exponent error; (3) Corollary 7's frontier API seat conflicts with perg's standing 2026-10-02 decision declining the paid frontier lane; (4) Part VIII's "proof" of emergence ≠ compressibility overstates (see TH-019); (5) ternary mirror math checks in itself but applying it to JEV assumes mirror-structured seats. *Record:* research-gaps.md (formal-framework errors). *Settler:* re-issue with the five errors corrected and the 58/58 pair identified or dropped. *C-list:* no.

**TH-014 — Fiber-dimension classifier (C1).** A classifier that reads the fiber dimension of a disagreement (the D1 triage hypothesis): disagreements carry a fiber dimension; measuring it classifies the failure. *Origin:* isomorphism document (item 1 + R2 framing), assessed 2026-10-30. *Status:* UNTESTED, measurement premature (both-wrong set unmeasured, no intrinsic-dimension estimator exists). *Record:* map U-CAT04 (amended with fiber-dimension form + measurement-premature status); inventory §3 C1. *Settler:* completeness proof or counterexample; first measure the both-wrong set. *C-list:* C1.

**TH-015 — Melding threshold curve (C2).** Melding exhibits a sharp threshold curve in sparsity/recovery. *Origin:* isomorphism document (item 6). *Status:* UNTESTED (needs a sparsity/recovery model that does not exist). *Record:* map U-CAT04 family; inventory §3 C2. *Settler:* simulation showing a sharp transition, or proof of none. *C-list:* C2.

**TH-016 — Catastrophe bound on seat failures (C3).** Seat failures obey a catastrophe (cusp) bound. *Origin:* isomorphism document (item 7). *Status:* UNTESTED (conjecture conditional on a nonexistent embedding). *Record:* inventory §3 C3. *Settler:* explicit potential for a 2-seat ensemble + cusp check. *C-list:* C3.

**TH-017 — K-way √λ_{K+1} interface scaling (C4).** Interface size scales as √λ_{K+1} for K-way partitions. *Origin:* spectral framework document; C4 in the TASEP verbatim §C. *Status:* PARTIAL — general theorem REFUTED by the 1D interval counterexample (decisive); fits the EIT mesh only (slope 0.905, R² = 0.971) as a heuristic. *Record:* spectral-test report; inventory §3 C4. *Settler:* proof for 2D or counterexample (the 2D proof leg is still open). *C-list:* C4.

**TH-018 — Communication formula (C5).** Bit-level communication = rank H¹ · b · I; corrected form: communication = I · |Γ_K| · b (H¹ is the coarse correction, not the communication dimension). *Origin:* spectral framework document; corrected in the attached re-check. *Status:* UNTESTED as a measurement (formula corrected on paper). *Record:* spectral-test report; inventory §3 C5. *Settler:* measured I vs K on a mesh (EIT lane). *C-list:* C5.

**TH-019 — Emergence ≠ compressibility "proof".** Emergence is proved distinct from compressibility. *Origin:* framework Part VIII. *Status:* REFUTED as a proof (halting/Diophantine undecidability proved; computational irreducibility as used there is Wolfram's thesis, not a theorem). *Record:* research-gaps.md. *C-list:* no.

**TH-020 — Ternary mirror math.** Given M(x) = −P(x), the check P(x) =? ¬M(¬x) reduces to P(x) = P(−x) — an evenness/mirror-relation check. *Origin:* perg-pasted framework. *Status:* DESIGN, narrow scope (structural consistency check on mirror-structured seats only; JEV seats are different models, not negations, so it is not a correctness certificate for them). *Record:* map R-D02. *Settler:* exhibit one mirror-structured seat pair where the check fires. *C-list:* no.

**TH-021 — K* ≈ N_loc (C6).** The optimal partition count K* approximately equals the number of localized modes N_loc. *Origin:* spectral framework document; C6 in the TASEP verbatim §C. *Status:* PARTIAL — REFUTED on the EIT mesh (K* = 2, boundary minimum, cost strictly increasing, vs N_loc = 73; interface grows 8.12 → 20.37, no plateau); K* ≈ N_loc survives as scaling only, constants undetermined; the cost-sweep settler is still open. *Record:* spectral-test report; inventory §3 C6. *Settler:* K sweep with measured cost. *C-list:* C6.

**TH-022 — Seed independence (C7).** Results are independent of seed: cross-seed correlation ρ < 1 under an external generator. *Origin:* TASEP verbatim §C, C7 ("needs: ρ measurement"); priority queue: "needs an external generator to check ρ < 1." *Status:* UNTESTED. *Record:* inventory §3 C7. *Settler:* external generator, cross-seed ρ < 1. *C-list:* C7. (Distinct from the tested determinism observation, TH-066.)

**TH-023 — Moving Pareto front (C8).** The cost-error Pareto front moves outward with decorrelated seats. *Origin:* TASEP synthesis §C, C8; redundancy-inversion companion (TH-024). *Status:* UNTESTED. *Record:* inventory §3 C8; value order item 10. *Settler:* front measured for 2, 3, 4 seats. *C-list:* C8.

**TH-024 — Redundancy inversion (C9).** High redundancy is good for ribosome survival but bad for fleet error reduction — the same redundancy optimizes opposite objectives in the two systems. *Origin:* TASEP synthesis §C, C9. *Status:* UNTESTED (formal statement of both optimization problems needed). *Record:* inventory §3 C9. *Settler:* formal statement of both optimization problems. *C-list:* C9.

**TH-025 — Capacity gap as floor gap (C10).** The capacity gap C_f − R_f is the floor gap: it relates to P(S) (the calculator-failure floor / success probability). *Origin:* TASEP synthesis §C, C10; capacity formula assumes a binary symmetric channel. *Status:* UNTESTED (derivation needed; BSC assumption flagged). *Record:* inventory §3 C10. *Settler:* derivation of the relation to P(S). *C-list:* C10.

**TH-026 — Three-regime triage completeness (C11).** The TASEP phase diagram gives a complete three-regime triage (low-density / maximal-current / high-density phases map to triage regimes). *Origin:* TASEP synthesis §C, C11; the ρ symbol collision (failure correlation 0.94 ≠ TASEP density) breaks the MC-phase inference as stated. *Status:* UNTESTED (classification or counterexample needed; the collision must be repaired first). *Record:* inventory §3 C11; assistant's evaluation of the synthesis (turn seq 34943, labelled). *Settler:* classification or counterexample, with ρ disambiguated. *C-list:* C11.

**TH-027 — Dual certificate as only escape (C15).** The Farkas/dual certificate is the only escape from a shaving obstruction — a classification of Π-proof techniques. *Origin:* TASEP verbatim §C, C15. *Status:* UNTESTED. *Record:* inventory §3 C15. *Settler:* classification of Π-proof techniques. *C-list:* C15. (Distinct from the Farkas-extraction design keep, TH-040.)

**TH-028 — Floor/invariant duality (C16).** The calculator failure floor and the invariant-graduation rule are dual (floor/invariant duality). *Origin:* TASEP verbatim §C, C16 ("needs: formalization"). *Status:* UNTESTED. *Record:* inventory §3 C16. *Settler:* formalization + proof. *C-list:* C16.

**TH-029 — Bias fraction threshold (C17).** A bias fraction ‖b̂‖²/𝔼‖ε‖² (verbatim B22: "Bias fraction = ‖b̂‖²/𝔼‖ε‖²", derived) has a cost-based cutoff: high bias fraction → correct the bias; low → collect data. *Origin:* TASEP verbatim §B22 (derived) + §C, C17 ("needs: the cutoff"). *Status:* UNTESTED (cutoff/rule unbuilt). *Record:* inventory §3 C17. *Settler:* cost-based decision rule with stated threshold. *C-list:* C17. (Distinct from the measured judge position bias, TH-065.)

**TH-030 — Betti formula at k=0 (C18).** χ = 1 − k + n, with a unified formula with β_0 explicit covering k = 0. *Origin:* spectral re-check (χ = 1−k+n survives for k ≥ 1; k = 0 corrected to 3+n — disjoint shell + cytoplasm); C18 in the TASEP verbatim §C. *Status:* PARTIAL (mesh check done; unified formula unproven). *Record:* spectral-test report; inventory §3 C18. *Settler:* unified formula with β_0 explicit. *C-list:* C18.

**TH-031 — 90° lag = resonance phase (C19).** The 90° lag is the resonance phase (forcing at natural frequency), not a generic marginal-stability phase; the linearized flapping model gives 90° exactly, the full nonlinear model may deviate. *Origin:* TASEP verbatim §B10 (corrected from "marginal stability") + §C, C19. *Status:* UNTESTED (nonlinear simulation needed). *Record:* inventory §3 C19. *Settler:* nonlinear simulation. *C-list:* C19. (Note: the 90°-lag item comes from the pasted synthesis inventory, not from this conversation's own measurements.)

**TH-032 — Hard limits generate constructions / transcendence ladder (C20).** Every hard limit generates a construction that transcends it, and the ladder is well-ordered; the Gödel case (transcendence operator), Turing case (jump), and forcing case (forcing extensions) are proven; the general claim is a pattern observed in four cases, not a theorem. *Origin:* TASEP verbatim §B16 (ordinal ladder well-ordered, proven) + §C, C20. *Status:* UNTESTED as a general claim. *Record:* inventory §3 C20. *Settler:* universality proof or counterexample (a limit with no transcendence construction). *C-list:* C20.

**TH-033 — TASEP / max-plus framework for the fleet.** Fleet throughput under contention follows TASEP/max-plus dynamics: Route 2 (max-plus re-derivation) agrees with TASEP on invariants, disagrees on mechanism, and catches the 4× overclaim (contention cost is 1/[ρ(1−ρ)], 4× is the best case at ρ = 1/2). *Origin:* perg-pasted TASEP/max-plus synthesis, 2026-10-31; Route 2's correction survives the assistant's evaluation. *Status:* ANALOGY with one surviving correction (the ρ symbol collision breaks the MC-phase inference; ribosome numbers — elongation 4.3–6.8, error 10⁻⁴, capacity 4.39, residual 0.0004, redundancy >90% — are unverified from this record and need sources; the spectral-radius/TASEP link is analogy; the capacity formula assumes a BSC). *Record:* verbatim file (39,828 bytes, md5 2e64f3535…); inventory §1/§5; assistant's evaluation turn seq 34943 (labelled). *Settler:* the density sweep (TH-034). *C-list:* no (C13/C14 are its two decisive sub-claims).

**TH-034 — Density sweep discriminator (C13 + C14).** One density sweep decides the mechanism: TASEP predicts a PEAKED throughput-vs-density curve; max-plus predicts a FLAT one; the peak, if present, sits at k/4 (C14: 4× contention). *Origin:* assistant's evaluation keep, offered 2026-10-31, not applied to the map. *Status:* UNTESTED (needs a pre-registered protocol first: in-flight counts, throughput measure, peaked-vs-flat decision rule, controlled concurrency in trap-restore windows; the fleet's serial logs cannot answer it). *Record:* inventory §4 item 1. *Settler:* the sweep itself, under a pre-registered protocol. *C-list:* C13 + C14.

**TH-035 — Three-floors distinction.** Three distinct floors must not be conflated (the synthesis's three-floors distinction, offered as a keep). *Origin:* assistant's evaluation keep, offered 2026-10-31. *Status:* DESIGN (offered, not applied). *Record:* inventory §5. *Settler:* state the three floors explicitly in one decision record and show a case where conflating them changes the verdict. *C-list:* no.

**TH-036 — Spectral framework (particle/wave, time-as-phase, capacity partition).** Particle-wave = localized vs extended Laplacian eigenmodes; time = phase of the unitary group; capacity K forces a spectral (Fiedler) partition. *Origin:* perg-pasted spectral framework document, evaluated 2026-10-30 23:38 EDT with an attached re-check. *Status:* PARTIAL — particle/wave vocabulary survives as IPR-as-localization; sharp mobility edge DEMOTED to crossover; time-as-phase CORRECTED to the phase-space group (wave equation is second order; frequencies √λ_k); K-way scaling demoted (TH-017); communication corrected (TH-018); K* gap (TH-021). Transfer kept separate from verdicts: more seats ≠ less communication; escalation rates are interface cost made visible; particle/wave vocabulary NOT imported directly; nothing changes a seat, rule, or bar. *Record:* research-gaps.md (spectral evaluation); spectral-test report; map R-J02. *Settler:* §8 spectral test — run (TH-080–TH-086). *C-list:* no.

**TH-037 — Trajectory method.** Perg's words, as recorded: "every measurement is a line from the original direction; write the direction down first (pre-registration = the reference line), measure how far each result bends off it, project the next decision to close the gap, re-measure; never assume back on course." *Origin:* perg, 2026-10-29. *Status:* APPLIED. *Record:* MEMORY.md; research-gaps.md. *C-list:* no.

**TH-038 — Precision-then-shift.** "Second measurements add precision, then the cost is removed by shifting (log space generalizes bitshift: exponentials become lines, projection becomes addition); shift AFTER deviation is measured, never before, or the deviation is erased." *Origin:* perg, 2026-10-29. *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-039 — Anchor test.** An anchor needs ≥ 2 independent characterizations; fewer = claim, not anchor; disagreement between characterizations = H¹ signal. *Origin:* assistant's, adopted 2026-10-30. *Status:* APPLIED. *Record:* map U-CAT01. *C-list:* no.

**TH-040 — Dual certificate / Farkas extraction.** Extract the Farkas certificate as the dual witness of a shaving obstruction. *Origin:* catalogue keep (mined 2026-10-30). *Status:* DESIGN (kept, folded into the map; no extraction routine built). *Record:* map B-CAT02. *Settler:* extract one certificate from one real obstruction (LP or EIT). *C-list:* no (C15 is the stronger "only escape" claim, TH-027).

**TH-041 — Four-cell seat-pair table as standard reporting form.** Every seat-pair comparison reports the four cells (both-right, A-only, B-only, both-wrong). *Origin:* catalogue keep. *Status:* APPLIED. *Record:* map U-CAT03. *C-list:* no.

**TH-042 — Search-vs-identifiability triage.** Triage a hard problem first by whether it is search-limited or identifiability-limited. *Origin:* catalogue keep, with the fiber-dimension amendment (TH-014). *Status:* DESIGN. *Record:* map U-CAT04. *Settler:* one problem triaged both ways with different interventions following. *C-list:* no.

**TH-043 — Hit-rate discipline (R2).** Report hit rates with the discipline of the isomorphism document's R2 (rates with denominators, no rate without its population). *Origin:* isomorphism keep. *Status:* APPLIED. *Record:* map R-CAT07. *C-list:* no.

**TH-044 — Mutual information as probe-selection principle.** Choose probes by mutual information. *Origin:* isomorphism keep (item 3). *Status:* UNTESTED (no probe set to apply it to). *Record:* research-gaps.md (isomorphism evaluation). *Settler:* a probe set with MI computed per probe and selection following it. *C-list:* no.

---

## §2. JEV / decider / verification theories

**TH-045 — Null as a complexity sensor.** A fast seat's null (empty/contract-failing output) signals problem complexity, not mere error: null rates rise with pre-registered function-complexity tier (T1 0/32, T2 3/36, T3 11/32; P(T3|null) = 11/14 = 0.786, lift 3.22×; subtlety carries no signal). *Origin:* assistant's five-item program, corrected run (hardness pinned by construction tier, subtlety recorded separately). *Status:* CONFIRMED. *Record:* jev-null-sensor-summary.md; map U-J01/U-J02 family. *C-list:* no.

**TH-046 — Lag as a sensor.** Response latency signals correctness or disagreement. *Origin:* assistant's five-item program. *Status:* REFUTED as a policy input (mechanistic negative: hammer duration degenerate, median 0.07s, no separation; fast duration replicates only as a post-hoc artifact with the retry-inflation caveat — null rows take two attempts, first-attempt latency never logged). *Record:* jev-lag-run-summary.md. *C-list:* no.

**TH-047 — Hammer recalibration.** Hammer's constant confidence 1.0 can be recalibrated to a useful value. *Origin:* assistant's five-item program. *Status:* REFUTED (fixed point does not move: 129 answered / 73 correct = 0.566; expressed confidence exactly {1.0} on all 129, zero information; mapping 1.0 → 0.566 changes no decision = identical to ignoring hammer = lean; logprobs carry no signal either — decision_logprob tertiles 0.500/0.542/0.696, Spearman +0.245, intervals overlap). *Record:* jev-hammer-recalibration-summary.md. *C-list:* no.

**TH-048 — Fast-wrong-among-disagreements rate r.** The rate at which the fast seat is wrong among disagreements; the lean rule's insurance price depends on it (full beats lean in expectation iff r > 0.01, the calculator floor itself). *Origin:* assistant's cost-error frontier analysis. *Status:* UNTESTED (0/41 observed, rule-of-three upper ≈ 0.073; ns2-a23 is uncatchable below escalate-all). *Record:* jev-frontier-summary.md; inventory §3 other-list (fast-wrong run). *Settler:* the fast-wrong disagreement run. *C-list:* other-list.

**TH-049 — Both-wrong measurement.** The both-wrong cell of the four-cell table is measurable and small. *Origin:* assistant's program (four-cell reporting, TH-041). *Status:* VOID/unmeasured, not refuted (0/19 consistent with true rate up to ~17%; 0/10 up to ~28%). *Record:* jev-lag-run-summary.md; inventory §3 other-list. *Settler:* both-wrong measurement run. *C-list:* other-list.

**TH-050 — Calculator failure floor.** P(calculator fails) = 1/100 = 0.010, Wilson (0.0018, 0.0545); implied reachability 0.990; by type (a) 0/50, (b) 1/50. *Origin:* assistant's five-item program. *Status:* CONFIRMED (single failure cf-b30, base36_to_int both-pass ambiguity: suite lacks a leading/trailing-whitespace test — a coverage gap, not a wrong test; on both-pass items the decider needs a tie-break/further-escalation rule). *Record:* jev-calculator-floor-summary.md. *C-list:* no.

**TH-051 — Lean-rule dominance (conditional).** The lean rule (escalate on fast null OR confidence < 0.8; never on hammer confidence) dominates the full rule on every observed population, conditional on future disagreements behaving like the observed ones. *Origin:* assistant's five-item program + decider build. *Status:* CONFIRMED on observed rows only (lag: lean cost 0.28 err 0.0000 perfect-calc; full cost 0.50 same error; ns2: lean cost 0.14 err 0.0100, escalate-all 0.0100 at 7× cost, band fully contains lean's). *Record:* jev-frontier-summary.md; decider-build-report.md. *C-list:* no.

**TH-052 — Decider merge with ⊤ = "disagree" (semilattice merge).** Any JEV decider merge ⊔ must be a semilattice with ⊤ = "disagree"; max-by-confidence alone is the trap; with ⊤, |B/∼| = P(join = ⊤) is a genuine measurement. *Origin:* assistant's merge design constraint, in research-gaps.md. *Status:* DESIGN (built into the decider; merge ⊔ still unpinned to a non-code artifact). *Record:* research-gaps.md; decider-build-report.md. *Settler:* a merge of two disagreeing non-code verdicts exhibiting ⊤. *C-list:* no.

**TH-053 — Distillation-vs-melding guardrail.** Never distill two disagreeing seats from the same teacher; routine math: distil; research math: diversify, then meld; keep a diversity-anchor seat un-distilled; track disagreement rate AND decider edge jointly; collapse signature = disagreement → 0 WITH edge → 0. *Origin:* perg's guardrail, accepted. *Status:* DESIGN (collapse signature untested — no distillation run has been measured against it). *Record:* research-gaps.md; MEMORY.md. *Settler:* a distillation run reporting disagreement rate and decider edge jointly. *C-list:* no.

**TH-054 — Evidence-class guard.** Escalation re-checks, never upgrades evidence class (a PREPRINT claim stays PREPRINT after a re-check; only new evidence promotes). *Origin:* assistant's derived design (X05/X06). *Status:* DESIGN. *Record:* seven-decisions-report.md; map U-X05/U-X06. *Settler:* a case where a re-check tempts an upgrade and the guard holds. *C-list:* no.

**TH-055 — Second-route requirement.** A second verification route only helps if it can CONFIRM as well as veto. *Origin:* perg's proposal (re-derivation runs); tested twice. *Status:* CONFIRMED as a requirement by two collapses (v1 re-derivation: 28/28 by escalating all 28, route C 0 agreements, route D precision 4/14; v2 interface-contract: 28/28 by escalating all 28, C2 confirm rate 0/20; second-route program CLOSED 2026-10-31; reopen needs a route that confirms as well as vetoes, pre-registered). *Record:* rederivation-rule-report.md; interface-contract-route-report.md; map R-J01. *C-list:* no.

**TH-056 — Interface-contract hypothesis.** Route C fails because the spec paragraphs lack the call interface; carrying the mechanically extracted interface contract (signature, return shape, vocabulary, purpose) fixes confirmation. *Origin:* assistant's v2 hypothesis, pre-registered. *Status:* REFUTED as the binding cause (v1-vs-v2: 0/23/5 vs 0/22/6 confirmations/abstains/fails — no measurable change; autopsy: 5 genuine contract gaps PLUS model errors no contract detail fixes — test-writing requires simulating the implementation, the understanding route A lacks). *Record:* interface-contract-route-report.md. *C-list:* no.

**TH-057 — Reference-filtered test design (v3 candidate).** Generate N tests, keep only shipped-passing ones (mutant-blind reference filter), per-test scoring, five contract gaps closed, independence claim explicitly weakened. *Origin:* assistant's candidate design from the v2 autopsy. *Status:* DESIGN, unlaunched (needs perg's word + new pre-registration). *Record:* interface-contract-route-report.md. *Settler:* the v3 run itself, pre-registered. *C-list:* no.

**TH-058 — Disagreement = fast-right pattern.** When the two fast seats disagree, the fast seat is right: 41/41 across three populations (13/13, 6/6, 22/22). *Origin:* assistant's measurement. *Status:* CONFIRMED as a pattern, mechanism unknown (no mechanism proposed or tested). *Record:* jev-contract-test-report.md; jev-hard-run-report.md; jev-lag-run-summary.md. *C-list:* no.

**TH-059 — Quicklook empties mechanism.** Quicklook's intermittent empties (6/50 = 12% in the contract test; 15/40 in the harder run; 64/82 outputs empty in the Glimmer sweep) have a mechanism. *Origin:* observed phenomenon. *Status:* UNTESTED (mechanism unknown; thinking-burn/template interaction suspected — 1024-token budgets truncated Qwen3-4B thinking in runs 1–2; the Glimmer sweep's quicklook wrapper-path template is uninvestigated). *Record:* jev-contract-test-report.md; glimmer-sweep-report.md. *Settler:* quicklook wrapper-path template investigation (offered follow-up). *C-list:* no.

**TH-060 — Correction path (error-correction).** When the fast seat is wrong, the slow seat corrects it through the escalation path. *Origin:* JEV contract design. *Status:* UNTESTED on constructed populations (combined 0/60 wrong-when-answered; the one fast-wrong case, ns2-a23, was caught by neither rule below escalate-all). *Record:* jev-hard-run-report.md; jev-null-sensor-summary.md; inventory §3 other-list. *Settler:* a population containing fast-wrong-when-answered items run through the full rule. *C-list:* other-list.

**TH-061 — Sub-0.95 calibration.** Fast-seat confidence below 0.95 is measurable and calibrated. *Origin:* JEV contract design (monotonicity untested: quicklook never below 0.95 in the contract test). *Status:* PARTIAL (one sub-0.95 case ever: ns2-a35, 0.9, CORRECT; no calibration curve exists). *Record:* jev-null-sensor-summary.md. *Settler:* a population eliciting the full confidence range with correctness per band. *C-list:* other-list (correction path + sub-0.95 calibration).

**TH-062 — Real-diff transfer.** The constructed-materials 100% top bucket transfers to real code diffs. *Origin:* assistant's transfer hypothesis, tested on perg's tap. *Status:* REFUTED (coder-30B 20/28, Coder-Next 21/28, lean final 22/28, 0 nulls in 56 rows, every coder-30B error at confidence 0.95; both-wrong set A10/A12/A14/B10/B14 — single-line semantic traps; the calculator 56/56 and the second-opinion SHAPE survive; on real work safety must come from running the tests). *Record:* real-diff-coder-report.md; map A-J07/U-J16. *C-list:* no.

**TH-063 — H4 vacuous-check finding.** The shipped hook harness's deep-copy check is vacuous against a shallow copy (H4 mutant passed; the check guards key-replacement only). *Origin:* assistant's freeze verification finding. *Status:* CONFIRMED as a finding, recorded not fixed (fix needs perg's word; the harness is shipped code). *Record:* real-diff-coder-report.md; inventory §3 other-list. *C-list:* other-list.

**TH-064 — Judge position bias.** The blind judge picks slot B ~70% of the time and only 25/42 swap re-judgements agree (~40% position-driven). *Origin:* assistant's blind-judge run, pre-registered flag (<80% swap agreement). *Status:* CONFIRMED (flag FIRES: swap agreement 25/42 = 59.5%, flips 17/42, slot B in 69.6% of 411 calls; no judged-only margin is clean; auto-decision components unaffected). *Record:* phase2-judge-report.md. *Settler for the FIX:* second judge, both-presentations scoring, or low-flip-rate judge on the 42-item calibration set (identified, NOT BUILT). *C-list:* other-list (judge bias fix).

**TH-065 — Overshoot threshold sweep (§7 test).** Sweeping the escalation confidence threshold (0.5–1.0) over saved rows (280 JEV + 56 real-diff) finds a threshold dominating 0.8 on final accuracy + escalation rate. *Origin:* overshoot document §7 test on the escalation rule, offered 2026-10-30. *Status:* REFUTED 2026-10-31 (sweep ran under pre-registered protocol `v01-threshold-sweep-protocol.md`, three independent computations agreeing exactly; no threshold dominates 0.8 in any population — the threshold is inert because fast confidences are ≥0.9 on included rows; see `v01-threshold-sweep-results.md`). Population basis corrected: per-population included rows (32/14/51/28), never pooled — the "280 + 56" count in the statement above was wrong (lag shares prompt_refs). *Record:* research-gaps.md (overshoot evaluation); inventory §3 other-list. *Settler:* the sweep itself (RAN). *C-list:* other-list.

**TH-066 — Determinism / re-runs add no evidence.** At temp 0 with identical prompts, re-runs replicate exactly and add NO independent evidence (probe replicated saved hammer exactly, 71/71 rows). *Origin:* assistant's hammer-recalibration probe. *Status:* CONFIRMED for that probe (distinct from C7 seed independence, TH-022, which concerns cross-seed ρ under an external generator). *Record:* jev-hammer-recalibration-summary.md. *C-list:* no.

---

## §3. SAT / solver-improvement theories

**TH-067 — Wall-as-quantile.** The SAT "wall" is where P(T(n) ≤ cap) crosses majority — a quantile, not a ceiling; cap-dependent. *Origin:* assistant's analysis, accepted. *Status:* CONFIRMED (30s cap first majority 119; 60s cap first majority 126; 120s-cap prediction n≈133, 240s n≈140 pinned, not launched). *Record:* sat-v3-report.md; map U-S01 family. *C-list:* no.

**TH-068 — Scaling base b ≈ 1.10–1.13/var.** Time fit ≈ 1.127/var, nodes ≈ 1.087/var; seven vars per doubling, base 2^(1/7) ≈ 1.104; velocity form 7/ln 2 ≈ 10 vars per e-fold of cap. *Origin:* assistant's fits. *Status:* CONFIRMED as fits (the 2^(7/6) ≈ 1.12 expression in perg's framework text and two pasted documents is WRONG — 2^(7/6) ≈ 2.24; correct forms are 2^(1/7) ≈ 1.104 or 2^(1/6) ≈ 1.122; flagged each time; attribution correction recorded 2026-10-30 23:38 EDT). *Record:* sat-v3-report.md; map A-CAT05. *C-list:* no.

**TH-069 — Threshold (S-curve), not exponential.** The wall is a threshold crossing: bracket crossings, don't extrapolate pre-wall trends; S-curve inflection 117.79 ± 0.76 (30s-cap curve only). *Origin:* assistant's analysis. *Status:* CONFIRMED. *Record:* sat-v3-report.md. *C-list:* no.

**TH-070 — UNSAT-driven wall.** The wall is UNSAT-driven and cap-dependent; UNSAT ~2.5× more nodes at same cost/node; SAT median 6.52s vs UNSAT median 16.90s; at the Stage-2 wall, zero UNSAT solved at n ≥ 200 (UNSAT fade total). *Origin:* assistant's analysis. *Status:* CONFIRMED. *Record:* sat-v3-report.md; solver-stage2-summary.md. *C-list:* no.

**TH-071 — Per-node cost rise (implementation cost).** Per-node cost rose ~30× from n=10 to n=119 (15.2 μs → 811 μs) under plain DPLL — the wall is partly implementation cost, not pure search growth. *Origin:* assistant's analysis. *Status:* CONFIRMED (Stage 1 flattened per-node cost to ~10 μs, median speedup ~69.4×). *Record:* sat-v3-report.md; solver-stage1-summary.md. *C-list:* no.

**TH-072 — Tail-noise / composition explanation.** Past-wall median bounce is explained by the solved-time distribution (~750× wide, small-k) and SAT/UNSAT composition, not by structure. *Origin:* assistant's bootstrap analysis. *Status:* CONFIRMED. *Record:* sat-v3-report.md. *C-list:* no.

**TH-073 — Watched literals (Stage 1).** Watched literals move the wall with no verdict change. *Origin:* solver-improvement plan, perg-approved. *Status:* CONFIRMED (correctness gate 390/390, 0 flips; wall (118,119] → (173,174], +55 vars, firmed). *Record:* solver-stage1-summary.md; sat-solver-v3.py (md5 ea52be1f…). *C-list:* no.

**TH-074 — VSIDS (Stage 2).** VSIDS variable ordering reduces decisions enough to move the wall despite pick cost. *Origin:* solver-improvement plan. *Status:* CONFIRMED (gate 390/390; wall (200,201], +27 vars; node ratio median 0.209 but per-node cost ~5× from full-scan pick, wall-clock median 0.94). *Record:* solver-stage2-summary.md; sat-solver-v4.py (md5 23d188ae…). *C-list:* no.

**TH-075 — Heap-ordered VSIDS pick (Stage 2b).** A heap-ordered pick preserves VSIDS decisions exactly at ~4× lower cost per node. *Origin:* assistant's Stage 2b design. *Status:* CONFIRMED (decision-identity gate 390/390 verdict + node counts identical, 428/428 with diagnostics; per-node cost 13.1 µs vs 52.5 µs; speedup median 3.94×, 0/390 slower; bracket MOVED above 201 — Stage 2's (200,201] must not be quoted as the heap solver's wall; fallback/budget trigger frequency unmeasured). *Record:* solver-stage2b-summary.md; sat-solver-v4-heap.py (md5 0d4ae47f…). *C-list:* no.

**TH-076 — CDCL: clause learning + backjumping (Stage 3).** 1-UIP conflict analysis + non-chronological backjumping improves the wall over the heap baseline. *Origin:* solver-improvement plan. *Status:* PARTIAL (correctness gate 390/390; heap baseline firmed first per the pre-registered correction: heap count bracket (223,224], firming failed at 224/225; Stage 3 count bracket (235,236], +12 vars count leg PASS, firming leg FAIL for both solvers — shallow S-curve; node ratio vs heap median 0.161, per-node cost ~20× heap repaid ~40× in decision count; bar NOT MET as written; Stage 4 NOT launched; count-only acceptance vs deeper firming awaits perg). *Record:* solver-stage3-summary.md; sat-solver-v5.py (md5 f89967ec…). *C-list:* other-list (Stage 3 firming call).

**TH-077 — Restarts + learnt-clause DB (Stage 4).** Restarts + learnt-clause database management move the wall further. *Origin:* solver-improvement plan. *Status:* UNTESTED (not launched; perg's call). *Record:* solver-improvement-plan.md; inventory §3 other-list. *Settler:* Stage 4 run under the plan's gates. *C-list:* other-list.

**TH-078 — Preprocessing (Stage 5, optional).** Preprocessing moves the wall further. *Origin:* solver-improvement plan. *Status:* UNTESTED (optional, not launched). *Record:* solver-improvement-plan.md. *Settler:* Stage 5 run under the plan's gates. *C-list:* no.

**TH-079 — Cap-edge jitter amendment.** The two Stage-0 residuals ((110,12) UNSAT, (119,343) SAT) are cap-edge jitter, diagnosable at 60s; the amendment carries to all stages. *Origin:* assistant's diagnosis, accepted by perg 2026-10-29 ~21:50. *Status:* CONFIRMED (written into the plan). *Record:* solver-improvement-plan.md. *C-list:* no.

---

## §4. EIT / spectral / inverse-problem theories

**TH-080 — Difference imaging with Tikhonov smoothness prior.** A standalone deterministic numpy-only difference-imaging solver (2D unit disk, P1 FEM, 16 point electrodes, adjacent drive/measure, 208 measurements; data mesh 912 elements finer than reconstruction mesh 528) reconstructs inclusions under a first-difference Tikhonov smoothness prior. *Origin:* assistant's EIT lane build (prior provenance marked "standard Tikhonov, this implementation" — no invented citations). *Status:* CONFIRMED (all 6 gates pass both seeds: localization 0.023/0.016, size error −0.01/−0.11, contrast recovery 0.87/0.88 one-step; 3-iteration GN overshoots contrast 1.19–1.20, one-step stays default). *Record:* eit-lane-report.md; eit_solver.py (md5 be034dcd…). *C-list:* no.

**TH-081 — Morozov discrepancy λ rule.** λ chosen by the Morozov discrepancy principle over a 29-point ρ sweep beats the L-curve corner. *Origin:* assistant's amended rule (amended from L-curve BEFORE authoritative runs — L-curve over-smoothed to +183% size error in exploration, ρ = 5.62; corner sits at grid floor in both seeds, diagnostic-only). *Status:* CONFIRMED as the rule in force. *Record:* eit-lane-report.md. *C-list:* no.

**TH-082 — Inverse-crime reduction.** Generating data on a finer mesh than the reconstruction mesh reduces the inverse crime. *Origin:* standard inverse-problem discipline (pass 2, TH-097). *Status:* DESIGN, applied with stated limit (meshes share angular structure — crime reduced, not eliminated). *Record:* eit-lane-report.md. *C-list:* no.

**TH-083 — Resolution/uncertainty reporting rule.** Every result prints prior, λ + rule, noise assumption, discretization, resolution map, uncertainty map — never a bare image. *Origin:* assistant's EIT lane rule. *Status:* APPLIED. *Record:* eit-lane-report.md. *C-list:* no.

**TH-084 — Spectrum decay / effective rank.** EIT singular values decay exponentially (σ₁ 0.088, σ₅₀ 0.0012, σ₁₀₀ 3e-07); effective rank 52 modes above 1%; resolution mean 0.137, centre 0.042 (worst), edge 0.259, PSF radius 0.209. *Origin:* assistant's EIT lane measurement. *Status:* CONFIRMED (both seeds). *Record:* eit-lane-report.md. *C-list:* no.

**TH-085 — Sharp mobility edge (spectral §8 verdict 1).** The FEM spectrum has a sharp mobility edge (localization transition). *Origin:* spectral framework document. *Status:* REFUTED — verdict CROSSOVER (max adjacent IPR jump 3.14 < 5.07 bar; span 9.01 < 100); IPR inversion found instead: 73 above-threshold modes (N_loc) sit at HIGH λ (61/73 top third) — grid-scale oscillation, not Anderson localization. *Record:* spectral-test-report.md; map R-J02. *C-list:* no.

**TH-086 — Cheeger 2-way partition bound.** The 2-way Cheeger bound holds on the mesh. *Origin:* spectral framework document. *Status:* CONFIRMED (|Γ₂| = 8.122 ≥ 2.683, ratio 3.03). *Record:* spectral-test-report.md. *C-list:* no.

**TH-087 — Modal frequencies = wave equation.** Modal frequencies follow the wave equation (frequencies √λ_k), confirmed against leapfrog time-stepping. *Origin:* spectral re-check correction (time-as-phase corrected to the phase-space group). *Status:* CONFIRMED (wave err ≤ 1.8e-3). *Record:* spectral-test-report.md. *C-list:* no.

**TH-088 — ker D (spectral §8 verdict 5).** The kernel of the (unpinned) operator D carries the obstruction. *Origin:* spectral framework document. *Status:* UNTESTED (D unpinned — anchor test applies; NOT TESTED in the §8 run). *Record:* spectral-test-report.md. *Settler:* pin D, then compute ker D. *C-list:* no.

**TH-089 — Linear vs nonlinear shaves for address data.** Address patterns have holes/gaps; linear shaves recover only the convex shadow, so the load-bearing pre-build decision (linear vs nonlinear shaves) must be made before any pointer/address shaving build. *Origin:* assistant's shaving assessment. *Status:* UNTESTED (no shaving build ordered). *Record:* research-gaps.md. *Settler:* the decision + one shaving computation on address data. *C-list:* no.

**TH-090 — Negative-contrast linearization asymmetry.** A negative-contrast inclusion localizes correctly but its contrast overshoots (1.49) — linearization asymmetry. *Origin:* assistant's EIT lane measurement. *Status:* CONFIRMED as a measured limit. *Record:* eit-lane-report.md. *C-list:* no.

**TH-091 — Two-inclusion resolution limit.** Two inclusions resolve down to separation d = 0.35 (both seeds); d = 0.2 unmeasured. *Origin:* assistant's EIT lane gate Tb. *Status:* PARTIAL (d = 0.2 unmeasured, n/a). *Record:* eit-lane-report.md. *Settler:* run Tb at d = 0.2. *C-list:* no.

---

## §5. Medical / plant transfers and computing axes

**TH-092 — Closed-loop policy (two timescales + sham).** Closed-loop sensor→policy→actuator transfers with repair: two timescales, per-action response/ECAP analogue, sham as blinded evaluation, cost-error frontier plotted. *Origin:* medical-tech pass 2, Task A1 (stress-tested transfer, SURVIVES with repair). *Status:* DESIGN. *Record:* second-pass report §A1; map U-M01/U-M02 family. *Settler:* two-timescale loop with blinded sham on reversible actions only (build order item 3). *C-list:* no.

**TH-093 — Inverse-problem discipline.** Difference imaging with published prior/resolution/λ-sensitivity first; never a bare image. *Origin:* medical-tech pass 2, Task A2 (SURVIVES strongest, no repair). *Status:* APPLIED (built as the EIT lane, TH-080–TH-084). *Record:* second-pass report §A2; map U-M03/U-M04. *C-list:* no.

**TH-094 — Frozen-encoder-first decoding + drift separation.** Foundation-model decoding transfers with major repair: frozen-encoder-first, measurement drift separated from generator drift, gradient test-time adaptation banned as default. *Origin:* medical-tech pass 2, Task A3 (SURVIVES with major repair). *Status:* DESIGN. *Record:* second-pass report §A3; map U-M05/U-M06. *Settler:* frozen-encoder drift dashboard (build order item 2). *C-list:* no.

**TH-095 — Gradient test-time adaptation ban.** Gradient test-time adaptation is banned as the default decoding adaptation (it confounds measurement drift with generator drift). *Origin:* medical-tech pass 2, Task A3. *Status:* DESIGN (rule). *Record:* second-pass report §A3. *C-list:* no.

**TH-096 — Ternary bands repair-or-drop (plant ternary bar).** Ternary voltage bands transfer ONLY if: bands are relative, justified vs continuous AND quaternary, hysteresis timed, coupling explicit, and the ±10% edge-jitter test passes — the concrete bar for the pinned plant-ternary hypothesis. *Origin:* medical-tech pass 2, Task A4 (REPAIR-OR-DROP per deployment); plants have AP/VP/SP event types, not three levels. *Status:* UNTESTED (rig pinned; the jitter test is the settling test). *Record:* second-pass report §A4; map U-M07; rig-spec R-requirements. *Settler:* ±10% edge-jitter test on real traces. *C-list:* other-list (plant ternary hypothesis, pinned).

**TH-097 — Multiplexed routing repair (ablation test).** Routing by confidence×cost alone misroutes — add latency + reversibility + channel-specific false-positive cost; ablation test: if outcomes don't change when the router is removed, it was decoration. *Origin:* medical-tech pass 2, Task A5 (REPAIR). *Status:* DESIGN, untested. *Record:* second-pass report §A5; map U-M08. *Settler:* the ablation test. *C-list:* no.

**TH-098 — Hodgkin–Huxley as drop-in mechanistic prior.** The Hodgkin–Huxley formalism is a drop-in mechanistic prior for plant electrical modelling. *Origin:* literature (Hodgkin–Huxley 1952), ranked transfer #1 in pass 3. *Status:* LITERATURE, transfer untested here. *Record:* four-fields report §3a/§3b + synthesis ranking; map U-F07 family. *Settler:* fit HH to one real plant trace and compare against a black-box decoder. *C-list:* no.

**TH-099 — PBPK/SEIR credibility-by-context-of-use + identifiability.** Credibility is by context of use, with identifiability analysis — the credibility guard for plant claims. *Origin:* literature (PBPK/SEIR methodology), pass 3. *Status:* DESIGN (credibility guard; honest gap noted: validity gate and credibility guard have no dedicated map entries). *Record:* four-fields report §3a; map U-F07 family. *Settler:* one plant claim carried through a context-of-use + identifiability check. *C-list:* no.

**TH-100 — MLIP caution (universal models fail silently out-of-domain).** Universal machine-learning interatomic potentials fail silently out-of-domain — the cautionary tale for any universal plant decoder. *Origin:* literature (chemistry pass 3: universal MLIPs). *Status:* LITERATURE, applied as a guard. *Record:* four-fields report §4a/§4b + synthesis; map U-F10/R-F04. *C-list:* no.

**TH-101 — Levin bioelectricity (voltage as causal layer).** Bioelectric voltage gradients are a causal layer in regeneration, wound healing, and cancer — not a decoded dictionary ("Voltage is a code we have decoded" is the transfer that must NOT be made); Levin's strong rewrite-anatomy claim is NOT transferred. *Origin:* literature (Levin lab), medical-tech pass 1 §1 + §8. *Status:* LITERATURE (background); the strong claim is AVOID. *Record:* pass-1 report §§1/8; map R-M01/A-M01. *C-list:* no.

**TH-102 — Ion channels as computational elements.** Ion channels compute (gating, selectivity, voltage-dependence as computational primitives). *Origin:* literature, medical-tech pass 1 §8.1. *Status:* LITERATURE (background). *Record:* pass-1 report §8.1; map R-M08. *C-list:* no.

**TH-103 — Plant electrophysiology parallel + honest baseline.** Plant electrical signals parallel the medical signals, with an honest peer-reviewed plant-ML baseline of 62–85%, NOT the 97% preprint claim (Biosensors 2025 single Tradescantia ResNet18 lamp 85.4% n=2767, emotion 73% n=1619, authors call preliminary; Biomimetics 2025 Random Forest 62.7% AUC 0.67, confounds unisolated; CONTRAST arXiv Jun 2025 ResNet50 97% is a preprint, NOT weighted equally). *Origin:* literature, medical-tech pass 1 §8.2 + pass 3 §3a. *Status:* LITERATURE; baseline APPLIED as the prior (map U-M14). *Record:* pass-1 report §8.2; map U-M14. *C-list:* no.

**TH-104 — "Do not act" gate for high-cost actions.** A high-cost action (decoding inner speech; tier-2 plant actuation) requires a separate high-confidence gate — for plants, a second modality (soil moisture, imaging) confirming the electrical signature before tier-2 actuation (Stanford mental-password gate, >98%). *Origin:* literature + synthesis Tier 1, pass 1 §2.1. *Status:* DESIGN. *Record:* map U-M11. *Settler:* one tier-2 actuation gated by a second modality on real traces. *C-list:* no.

**TH-105 — No single-driver stories in coupled excitable tissue.** Do not report "found the driver" for plant tissue without phantom-rotor validation and a multi-driver null (rotor-trial sobriety: persistent-AF ablation ~50% successful, Europace 2025; REAFFIRM randomised follow-up sobering; dual-atria rotor study calls for larger studies). *Origin:* literature, pass 1 §6. *Status:* APPLIED (rule). *Record:* map U-M12. *C-list:* no.

**TH-106 — Lab-vs-field reporting rule.** Every plant accuracy claim carries its population, time window, and shuffled-label baseline (Harrell: 3,800 h at home; ECGFounder internal-vs-external AUROC gap is the norm; Vivent/Electric Plant claims await independent trials). *Origin:* literature + pass 1 §5.2. *Status:* APPLIED. *Record:* map U-M13. *C-list:* no.

**TH-107 — Triage framing for plant alerts.** Frame plant alerts as triage for confirmatory inspection, not diagnosis (Imperial ECG AI: routine 10-s ECG, <2 s, heart failure up to 81%, valve disease up to 90%, 67,000-patient US trial; AUROC 0.86–0.90). *Origin:* literature, pass 1 §5.1. *Status:* APPLIED. *Record:* map U-M15. *C-list:* no.

**TH-108 — Non-inferiority discipline.** Safety + speed at equal efficacy is the advance; never report a non-inferior result as superiority (PFA: ADVENT 73.3% vs 71.3% thermal, non-inferior; PULSED AF 0.7% adverse events). *Origin:* literature, pass 1 §6.2. *Status:* APPLIED. *Record:* map U-M16. *C-list:* no.

**TH-109 — EIT consensus as plant-electrode standard template.** Standardise the electrode plane, warn absolute values are not comparable across subjects/positions, frame the tool as titration/recruitment (2025 international EIT consensus, 87 recommendations, 12 countries; PEEP 18 → 8 cmH₂O case report). *Origin:* literature, pass 1 §4.1. *Status:* DESIGN. *Record:* map U-M17. *Settler:* a plant-electrode standard document following the template. *C-list:* no.

**TH-110 — Vivent stress lead-time/yield claims.** Vivent's stress lead-time and yield claims. *Origin:* company claims. *Status:* VOID as field facts (no independent trial found; €7.5M Nov 2025 raise and >1,000 ha Europe confirmed; claims themselves unverified). *Record:* pass-1 report; MEMORY.md correction. *Settler:* an independent trial. *C-list:* no.

**TH-111 — Artificial pancreas as deployed closed-loop reference.** The artificial pancreas is the deployed closed-loop medical system to learn from. *Origin:* literature, pass 2 gap B1. *Status:* LITERATURE (background gap, unmined beyond the reference). *Record:* second-pass report §B1; map R-P01. *C-list:* no.

**TH-112 — TMS / tDCS / tACS noninvasive stimulation.** Noninvasive brain stimulation as a stimulation/actuation reference. *Origin:* literature, pass 2 gap B2. *Status:* LITERATURE (background). *Record:* second-pass report §B2; map R-P02. *C-list:* no.

**TH-113 — Focused ultrasound (BBB opening + neuromodulation).** Focused ultrasound as a targeted-actuation reference. *Origin:* literature, pass 2 gap B3. *Status:* LITERATURE (background). *Record:* second-pass report §B3; map R-P03. *C-list:* no.

**TH-114 — NV-diamond (quantum diamond) sensing.** NV-centre sensing for cardiac and neural fields as a sensing reference. *Origin:* literature, pass 2 gap B4. *Status:* LITERATURE (background). *Record:* second-pass report §B4; map R-P04. *C-list:* no.

**TH-115 — Ingestible / wearable continuous sensing.** Ingestible sensors and continuous wearables as a sensing reference. *Origin:* literature, pass 2 gap B5. *Status:* LITERATURE (background). *Record:* second-pass report §B5; map R-P05. *C-list:* no.

**TH-116 — Spinal / cochlear / retinal stimulation.** Stimulation beyond the single optogenetics trial as an actuation reference. *Origin:* literature, pass 2 gap B6. *Status:* LITERATURE (background). *Record:* second-pass report §B6; map R-P06. *C-list:* no.

**TH-117 — Bioelectricity in aging.** Bioelectric changes in aging as a drift/long-timescale reference. *Origin:* literature, pass 2 gap B7. *Status:* LITERATURE (background). *Record:* second-pass report §B7; map R-P07. *C-list:* no.

**TH-118 — Organ-on-chip electrical readouts.** Organ-on-chip electrical readouts as a controlled-preparation reference. *Origin:* literature, pass 2 gap B8. *Status:* LITERATURE (background). *Record:* second-pass report §B8; map R-P08. *C-list:* no.

**TH-119 — AI medical imaging beyond ECG/EEG.** AI imaging transfer beyond electrical signals. *Origin:* literature, pass 2 gap B9. *Status:* LITERATURE (background). *Record:* second-pass report §B9; map R-P09. *C-list:* no.

**TH-120 — Digital twins of organs.** Organ digital twins as a model-based reference. *Origin:* literature, pass 2 gap B10. *Status:* LITERATURE (background). *Record:* second-pass report §B10; map R-P10. *C-list:* no.

**TH-121 — Computing axes ranking (analog/memristor, neuromorphic, organoid, photonic, NV, quantum, DNA).** Ranked by direct transfer: analog/memristor in-memory 1st, neuromorphic/spike 2nd, bioelectric/organoid-as-model 3rd (proof-of-concept), photonic front-end, NV as sensor, quantum (no economically useful result yet), DNA (storage only). *Origin:* medical-tech pass 2, Task C3. *Status:* LITERATURE synthesis (ranking applied as build-order guidance; quantum/DNA are AVOID for compute). *Record:* second-pass report §C3; map R-P14–R-P20. *C-list:* no.

---

## §6. Theoretical mathematics — literature results and their transfers

Each entry: the published result (status as corrected by the retrieval pilots where applicable) + the transfer claimed in the theoretical-math report. "Transfer untested" throughout unless stated; the report's Tier 1/2/3 synthesis is TH-150.

**TH-122 — Komlós discrepancy nearly solved (Bansal–Jiang, (log N)^{1/4}).** Steinitz/Komlós discrepancy bound improved to (log N)^{1/4} (fall 2025 preprint at report time; retrieval pilot 2 corrected the status: PUBLISHED, STOC proceedings). Transfer: discrepancy control for seat ensembles. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §1.1; map B-T01; retrieval-pilot2-report.md (status correction). *C-list:* no.

**TH-123 — First explicit Poissonian rotation (Hauke).** Badly approximable α with rough numbers gives the first explicit Poissonian rotation (arXiv:2506.01736). Transfer: badly-approximable sampling for decoder/trajectory design — a genuine irrational-anchor connection. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §1.2; map B-T02; R-D03. *C-list:* no.

**TH-124 — Metric Diophantine approximation with reduced fractions (Aistleitner et al. 2023).** Quantitative metric Diophantine approximation with reduced fractions. Transfer: reduced-fraction approximation budgets. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §1.3; map B-T04. *C-list:* no.

**TH-125 — Diophantine approximation by primes from short intervals (Baier–Roy 2025/26).** Primes from short intervals approximate. Transfer: prime-spaced sampling. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §1.4; map B-T03. *C-list:* no.

**TH-126 — Three-term progressions, quasipolynomial (Kelley–Meka 2023; Bloom–Sisask 2023).** Roth numbers bound exp(−c(log N)^{1/12})N (FOCS 2023); Bohr sets as the structure. Transfer: Bohr-set structure for forced patterns — a genuine irrational-anchor connection. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §1.5; map U-T02; R-D03. *C-list:* no.

**TH-127 — Primes in short intervals / zero density (Guth–Maynard 2024).** N(σ,T) ≪ T^{30(1−σ)/13+o(1)}; primes in intervals x^{17/30}. Transferable METHOD: when a worst-case bound is stuck, improve the bound at the single critical parameter regime rather than uniformly. *Origin:* literature (arXiv:2405.20552; retrieval pilot 2 corrected the status: PUBLISHED, Annals of Mathematics — the report's PREPRINT status was stale). *Status:* LITERATURE; method transfer UNTESTED. *Record:* theoretical-math report §1.6; map R-T01; retrieval-pilot2-report.md. *C-list:* no.

**TH-128 — Prime statistics as Gaussian multiplicative chaos (Harper et al. 2025, announced).** Prime statistics modelled as GMC. *Origin:* literature, ANNOUNCED, unverified. *Status:* LITERATURE, announced only. *Record:* theoretical-math report §1.7; map N-T05. *C-list:* no.

**TH-129 — Diagonal Ramsey numbers (Campos et al. 2023).** R(k) ≤ (4−ε)^k — first exponential improvement in 88 years (book algorithm + zigzag lemma). Transfer: R(k) as a SCALE for forced consensus/exclusion clusters in channel graphs (below it independence is possible in principle; above it the router must handle forced clusters) — NOT a safety guarantee. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §2.1; map R-T04. *C-list:* no.

**TH-130 — Asymptotics of r(4,t) (Mattheus–Verstraete 2024).** r(4,t) = Ω(t³/(log t)⁴), solving Erdős's conjecture up to (log t)² (Hermitian unital in PG(2,q²) + random bipartite replacement + random subset; geometry supplies structure, randomness the rest). Transfer: skeleton-then-randomise as a template for electrode layouts. *Origin:* literature (Annals Math. 199 (2024), peer-reviewed). *Status:* LITERATURE; transfer UNTESTED; NO separate map entry (folded only inside R-T04). *Record:* theoretical-math report §2.2; map R-T04 (joint). *C-list:* no.

**TH-131 — Random-graph sandwich conjecture (Behague–Ilkovič–Montgomery 2025).** The sandwich conjecture proved (as probability — see TH-141). *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §2.3; map B-T07. *C-list:* no.

**TH-132 — Stanley–Stembridge e-positivity (Hikita 2024).** Chromatic symmetric function of a (3+1)-free poset's incomparability graph has all e-coefficients ≥ 0, via explicit inductive formula + modular law, coefficients as (normalised) PROBABILITIES. Transferable METHOD only: to prove non-negativity of a combinatorial count, find a probabilistic interpretation. *Origin:* literature (arXiv:2410.12758, accepted JAMS per Sep 2026 report). *Status:* LITERATURE; method transfer UNTESTED. *Record:* theoretical-math report §2.4; map R-T02. *C-list:* no.

**TH-133 — Aperiodic monotile (hat and spectre, Smith et al. 2023).** A single tile forces aperiodicity. Transfer: none direct (Tier 3). *Origin:* literature. *Status:* LITERATURE; no transfer claimed. *Record:* theoretical-math report §3.1; map B-T09a. *C-list:* no.

**TH-134 — Moving sofa is Gerver's (Baek 2024).** Gerver's sofa is optimal. Transfer: none direct. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §3.2; map B-T09b. *C-list:* no.

**TH-135 — Noperthedron (Steininger–Yurkevich 2025).** A convex polyhedron that cannot pass through itself. Transfer: none direct. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §3.3; map B-T09c. *C-list:* no.

**TH-136 — Unknotting number is not additive (Brittenham–Hermiller 2025).** Unknotting number fails additivity under connected sum. Transfer: non-additivity caution for composite scores. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §3.4; map U-T05. *C-list:* no.

**TH-137 — Kervaire invariant in dimension 126 (Lin–Wang–Xu 2024).** Kervaire invariant one exists in dimension 126. *Origin:* literature, PREPRINT. *Status:* LITERATURE, preprint; explicitly NOT an irrational-anchor result. *Record:* theoretical-math report §3.5; map N-T01; R-D03. *C-list:* no.

**TH-138 — Dudeney's dissection is optimal (Demaine–Kamata–Uehara 2024).** Dudeney's haberdasher dissection is optimal. Transfer: none direct. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §3.6; map B-T09d. *C-list:* no.

**TH-139 — Typical hyperbolic surfaces optimally connected (Anantharaman–Monk 2023–25).** Typical hyperbolic surfaces achieve optimal spectral-gap connectivity. Transfer: spectral-gap thinking for seat graphs. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §3.7; map B-T08. *C-list:* no.

**TH-140 — Kakeya in three dimensions (Wang–Zahl 2025).** Kakeya sets in 3D have full dimension 3 (arXiv:2502.17655, Feb 2025 preprint trilogy; Wang Fields Medal 2026; main paper still preprint as of Oct 2026). Transfer: directional-concentration thinking for measurements. *Origin:* literature, preprint. *Status:* LITERATURE, preprint; explicitly NOT an irrational-anchor result by metaphor. *Record:* theoretical-math report §4.1; map U-T01; notes/correction-url.md (one reconstructed URL flagged and disregarded — citation provenance, not a content ban). *C-list:* no.

**TH-141 — Counterexample to Mizohata–Takeuchi (Cairo 2025).** The Mizohata–Takeuchi conjecture is false. Transfer: a caution against assumed weighted estimates. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §4.2; map B-T05. *C-list:* no.

**TH-142 — Hilbert's sixth problem, kinetic part (Deng–Hani–Ma 2024–25).** Derivation of kinetic equations from particle dynamics. Transfer: derivation-from-particles as a template for deriving macroscopic laws from microscopic rules. *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §4.3; map B-T06. *C-list:* no.

**TH-143 — Nonuniformly elliptic Schauder theory (De Filippis–Mingione 2023, sharp 2025).** Schauder regularity under nonuniform ellipticity, sharp. Transfer: regularity under rough coefficients — changes how the program thinks now (Tier 1). *Origin:* literature. *Status:* LITERATURE; transfer UNTESTED. *Record:* theoretical-math report §4.4; map U-T03. *C-list:* no.

**TH-144 — Finite-time blowup for 3D Euler (Chen–Hou 2025).** Smooth data + boundary → finite-time blowup. Transfer: boundary-driven singularity caution. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §4.5; map B-T10. *C-list:* no.

**TH-145 — Diagram-free regularity structures for SPDEs (Linares–Otto–Tempelmayr–Tsatsoulis 2024).** Regularity structures without diagrams. Transfer: none direct (Tier 2/3). *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §4.6; map B-T11. *C-list:* no.

**TH-146 — Gaussian multiplicative chaos / Garban–Vargas conjecture (Lin–Qiu–Tan 2024).** GMC and the Garban–Vargas conjecture resolved. Transfer: multiplicative-chaos modelling of prime/signal statistics (with TH-128). *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §5.1; map B-T06/R-T05 family. *C-list:* no.

**TH-147 — Geometric Langlands, unramified, characteristic zero (Gaitsgory et al. 2024).** Geometric Langlands proved (~1000pp submitted; Breakthrough Prize 2025 ≠ peer review). Transfer: none — Tier 3, do not force one. *Origin:* literature, submitted. *Status:* LITERATURE. *Record:* theoretical-math report §6.1; map N-T02. *C-list:* no.

**TH-148 — Absoluteness between V and HOD (Goldberg–Hathaway 2025).** Under a proper class of Woodin cardinals, every (Σ₁²)^{uB} statement true in V is true in HOD; full absoluteness cannot follow from any large-cardinal axiom consistent with V = Ultimate L. Transferable IDEA only: absoluteness as a robustness criterion (a decision procedure is trustworthy if its verdict does not change when moved to a smaller, more definable model). *Origin:* literature, preprint. *Status:* LITERATURE; idea transfer UNTESTED. *Record:* theoretical-math report §7.1; map R-T03. *C-list:* no.

**TH-149 — Large cardinals beyond HOD (Aguilera–Bagaria–Goldberg–Lücke 2024–25).** Exacting and ultraexacting cardinals. Transfer: none — NO DIRECT USE. *Origin:* literature. *Status:* LITERATURE. *Record:* theoretical-math report §7.2; map N-T03. *C-list:* no.

**TH-150 — Tier 1/2/3 synthesis ranking.** Tier 1 (changes thinking now): nonuniform Schauder, Komlós, Kakeya, Kelley–Meka, Hauke. Tier 2 (changes a subsystem or warns): the rest of §§1–5. Tier 3 (no direct transfer): Langlands, Kervaire, Guth–Maynard as theorem, Stanley–Stembridge as theorem, large cardinals/logic, GMC as theorem. The edge is largely preprint-edge right now; preprints NOT called proved; formalisations NOT counted as new theorems; Oct 2026 AI mass claims excluded as unverified. *Origin:* assistant's synthesis. *Status:* APPLIED (ranking used for build order). *Record:* theoretical-math report synthesis + guardrails; artifact theoretical-math-advancements. *C-list:* no.

---

## §7. Four-fields formalisms (reasoning / mathematics / chemistry / medical-native)

**TH-151 — Formal verification / AI-assisted proof discovery (Lean, AlphaProof).** Formal verification and AI-assisted proof discovery as the correctness layer for math claims. *Origin:* literature + field survey, four-fields §1a/§C1. *Status:* DESIGN (Lean leg conditional on an acquisition step — elan + toolchain + Mathlib decision — named as perg's call; oracle-tier design). *Record:* four-fields report §1a; map U-F06; oracle-tier-design.md. *Settler:* the oracle-tier pilot (TH-164). *C-list:* no.

**TH-152 — CAS + continued-fraction certificates.** Computer algebra + continued-fraction convergents as resolution certificates (bracket width 1/(qₙqₙ₊₁)). *Origin:* literature + assistant's development, four-fields §1a. *Status:* DESIGN (certificate form used in the convergent-band decoder, TH-010). *Record:* four-fields report §1a; map F15/F16. *C-list:* no.

**TH-153 — ASP / Dung retraction + conflict audit.** Answer-set programming and Dung argumentation frameworks: retraction + conflict audit for research synthesis (3 triggers / 3 tiers, verdicts stay ternary). *Origin:* literature (reasoning field), four-fields §2a/§2b. *Status:* DESIGN (X06, derived-design, NOT measured). *Record:* four-fields report §2a; seven-decisions-report.md; map U-F01. *Settler:* a synthesis case carried through the Dung audit with a retraction. *C-list:* no.

**TH-154 — Bayesian action / value-of-information routing.** The router as a Bayes action: route by value of information, not confidence alone. *Origin:* literature (reasoning field), four-fields §2a/§2b. *Status:* DESIGN. *Record:* four-fields report §2a; map U-F02. *Settler:* a routing decision where VOI and confidence disagree, decided by VOI. *C-list:* no.

**TH-155 — SMT / solver-backed verification.** SMT solvers as the verification back-end for math claims. *Origin:* literature, four-fields §1a/§2a. *Status:* DESIGN (Z3 4.12.1 present, subprocess + SMT-LIB only, no Python bindings; Dafny loop used it via --solver-path). *Record:* four-fields report; dafny-redesign-report.md. *C-list:* no.

**TH-156 — Compartmental / PBPK models.** Physiologically-based pharmacokinetic compartmental models as the native mathematics of medical science. *Origin:* literature, four-fields §3a. *Status:* LITERATURE (background). *Record:* four-fields report §3a; map U-F07. *C-list:* no.

**TH-157 — SEIR / epidemic models + identifiability.** SEIR-type models with identifiability analysis as the native mathematics of population medical science. *Origin:* literature, four-fields §3a. *Status:* LITERATURE (background; identifiability feeds TH-099). *Record:* four-fields report §3a; map U-F08/F09. *C-list:* no.

**TH-158 — MLIP energy landscapes.** Machine-learning interatomic potentials: energy landscapes as the native object of chemistry. *Origin:* literature, four-fields §4a. *Status:* LITERATURE (background). *Record:* four-fields report §4a; map U-F10. *C-list:* no.

**TH-159 — Graph + ODE hybrids / representation sensitivity.** Graph-plus-ODE hybrid models; representation sensitivity as the failure mode (atoms interchangeable, plants are not — the furthest substrate). *Origin:* literature, four-fields §4a/§4b. *Status:* LITERATURE; caution APPLIED. *Record:* four-fields report §4b; map U-F11/R-F04. *C-list:* no.

**TH-160 — Field ranking (medical > reasoning > math > chemistry).** Transfer ranking: 1 Medical science, 2 Reasoning, 3 Mathematics, 4 Chemistry — by directness of transfer to the program. *Origin:* assistant's synthesis, four-fields. *Status:* APPLIED (ranking used for build order). *Record:* four-fields report synthesis; map R-F01 family. *C-list:* no.

**TH-161 — Anchor verdict per field (holds/breaks).** The irrational anchor holds in mathematics (continued fractions, discrepancy) and reasoning (approximation budgets), breaks in medical science (genuinely discrete events, thresholds) and chemistry (discrete atoms, countable states) — verdict: SURVIVES AS HEURISTIC/DISCIPLINE, NOT AS FOUNDATION. *Origin:* assistant's synthesis, four-fields §§1c/2c/3c/4c. *Status:* APPLIED (TH-008). *Record:* four-fields report synthesis; map R-D03. *C-list:* no.

---

## §8. Wire program / cube / emergence toolkit

**TH-162 — Wire doctrine (clean-room method).** "NOTHING human touches agents — no English, no human data; observers measure structure/learnability." *Origin:* perg, 2026-10-03 (doctrine). *Status:* APPLIED (the doctrine IS the method; any emergent-communication claim that breaks it measures the injection, not the agents; glimmer BARRED from the wire experiment under it). *Record:* MEMORY.md; map U-W01; wire-experiment/README.md. *C-list:* no.

**TH-163 — Generative null.** For any distributional claim, build a generator that fakes the pattern and compare — stronger than a significance test (random-typing null reproduced α exactly). *Origin:* assistant's method note, proven by example in the wire program. *Status:* APPLIED. *Record:* research-registry.md (T-W-002); map U-W02. *C-list:* no.

**TH-164 — Q-table size is not a proxy for learning.** Q-table growth does not measure learning. *Origin:* wire program measurement. *Status:* CONFIRMED. *Record:* map U-W03. *C-list:* no.

**TH-165 — Bits-through-queues.** Communication capacity is measurable as bits through queues. *Origin:* wire program hypothesis. *Status:* KILLED (no support). *Record:* research-registry.md. *C-list:* no.

**TH-166 — Self-organized criticality (SOC).** Wire dynamics sit at a critical point. *Origin:* wire program hypothesis. *Status:* KILLED (no support). *Record:* research-registry.md. *C-list:* no.

**TH-167 — Fibonacci waveform.** A Fibonacci-structured waveform carries the wire signal (an idea perg carried for years). *Origin:* perg's long-held idea. *Status:* KILLED (tested; no support). *Record:* research-registry.md; MEMORY.md. *C-list:* no.

**TH-168 — Kuramoto / Arnold tongue.** Wire synchrony follows Kuramoto dynamics with an Arnold tongue. *Origin:* wire program hypothesis. *Status:* KILLED (no support). *Record:* research-registry.md (T-W-005). *C-list:* no.

**TH-169 — Phase Response Curve (PRC).** Wire agents show a phase response curve. *Origin:* wire program hypothesis. *Status:* KILLED (no support). *Record:* research-registry.md (T-W-004). *C-list:* no.

**TH-170 — DFA / Hurst analysis.** Detrended fluctuation analysis / Hurst exponent reads wire structure. *Origin:* wire program method. *Status:* KILLED/superseded (method note; replaced by timescale decomposition). *Record:* research-registry.md. *C-list:* no.

**TH-171 — Timescale decomposition (surprise_slow/fast/excess).** bits_ema decomposed into surprise_slow / surprise_fast / surprise_excess; a slow instrument cannot answer a fast-events question; decompose before interpreting, never average across timescales. *Origin:* assistant's method note (T-W-001 superseded 2026-10-08). *Status:* APPLIED. *Record:* map R-W08. *C-list:* no.

**TH-172 — Diet battery instrument.** Five observer lenses, diet the only variable, identical wire data; diets touch observers only, never the agents. *Origin:* wire program instrument. *Status:* CONFIRMED as an instrument; verdict: "the protocol looks like noise to every lens — or its structure is alien to all of them" (Oct 30: 51,203 aligned chunks, means 1.16–1.34%, control 1.337%; Oct 29: 76,296 chunks, means 0.645–0.692%, control 0.677% — none beats control either day). *Record:* verification-reads-report.md §1; map R-W09. *Settler (open):* re-running compare.py on earlier diet days (read-only). *C-list:* no.

**TH-173 — Quorum sensing / motif method.** Quorum-sensing and motif methods read collective wire structure. *Origin:* wire program background (T-W-002 family). *Status:* LITERATURE/background, unmeasured here. *Record:* research-registry.md. *C-list:* no.

**TH-174 — Cube contention/propagation (Phase 1).** In the cube cellular-automaton experiment, contention dominates and propagation is null. *Origin:* cube experiment Phase 1. *Status:* CONFIRMED (Phase 1 complete 2026-10-03, installed mrfloppy ~/llm/cube/; Phase 2 queued). *Record:* research-registry.md; goal_22bb74ff8419. *C-list:* no.

**TH-175 — Busy-tone ratio ~half.** The cube busy-tone ratio is ~half right (t1-16k: 1,162,033 busy / 2,351,793 attempts = 49.4%; other runs 39.9–49.8%; the 97.7% figure was a denominator error). *Origin:* assistant's measurement, corrected. *Status:* CONFIRMED (settled). *Record:* research-gaps.md. *C-list:* no.

**TH-176 — Flip-a-tile v2 (layer-4 verdict).** A flip-a-tile intervention at layer 4 proves a world-model sensor. *Origin:* emergence toolkit analysis. *Status:* VOID/NOT PROVEN at layer 4 (layer 14 met both bars individually — shift 0.2418 at alpha 3.0, control −0.0015 — only layer with specificity; formal verdict not retroactively changed; rule flaw: select best layer by specificity = shift − control). *Record:* audit-template.md appendices. *C-list:* no.

**TH-177 — Pointer heuristic (tightened).** Pointer-like structure exists in the saved data (confirmed real 79; shuffled confirmed mean/SD 0.000/0.000 across 20 rounds — caveat: 5× and +3SD legs vacuous at a zero null; strength rests on 0-vs-79 separation; P170 recovery 5/5, P10240 21/21). *Origin:* emergence toolkit analysis. *Status:* CONFIRMED for the confirmed subset only (after tightening). *Record:* audit-template.md appendices. *C-list:* no.

**TH-178 — P170 family.** Five fields at offsets 6, 14, 22, 46, 166, only constant step 46→166 = 0x78. *Origin:* saved-data analysis. *Status:* CONFIRMED (SUPPORTED). *Record:* audit-template.md appendices. *C-list:* no.

**TH-179 — P10240 array.** A perfect 21-window array, step +24, phase 12 exclusive, byte-exact generation 21/21. *Origin:* relation scanner (24 strips, exactly one array found). *Status:* CONFIRMED (SUPPORTED). *Record:* audit-template.md appendices; relation-scanner.py. *C-list:* no.

**TH-180 — Grid sensor v1/v2.** A grid sensor reads structure in the saved data. *Origin:* emergence toolkit analysis. *Status:* VOID (NO SIGNAL, both versions). *Record:* audit-template.md appendices. *C-list:* no.

**TH-181 — World-model sensor.** A world-model sensor reads structure in the saved data. *Origin:* emergence toolkit analysis. *Status:* REFUTED (NEGATIVE). *Record:* audit-template.md appendices. *C-list:* no.

**TH-182 — Mirage-check resolution.** The frank-vs-mrfloppy divergence was a thinking-burn artifact, not a weights difference (true summarization 20/22 = 0.909 both machines; weights md5-identical). *Origin:* assistant's analysis. *Status:* CONFIRMED (resolved). *Record:* audit-template.md appendices. *C-list:* no.

**TH-183 — 72h ticks.** The registry's tick record is right: final record tick 14,458,400 (step 1,807,300, Oct 10 07:27:07 EDT). *Origin:* assistant's verification. *Status:* CONFIRMED (settled). *Record:* research-gaps.md. *C-list:* no.

---

## §9. Harvest, method, and standing rules

**TH-184 — Scientist OS (10 invariants + 2-source graduation).** Ten invariants of how scientists work, each needing 2+ independent sources for promotion; promotion stays with perg/the assistant. *Origin:* assistant's harvest design (perg's scientist-harvest mission). *Status:* DESIGN, in use (BGSU pilot harvest). *Record:* research-registry.md; MEMORY.md. *C-list:* no.

**TH-185 — WHY/PATH/HOW/WHAT harvest.** Harvest each scientist's WHY, PATH, HOW, and WHAT. *Origin:* assistant's harvest design (model-expert program). *Status:* APPLIED. *Record:* research-registry.md; model-expert-program.md. *C-list:* no.

**TH-186 — Thinking-pattern harvest (BGSU pilot).** Fifteen candidate thinking patterns across three BGSU RNA-group papers (FR3D: pick the signal-carrying unit; dual representation; bound then screen; design for what others miss; fix the textbook method your domain breaks. Isostericity: quantify the qualitative; centroids should be real; warn against your own simplification; state the domain of validity; anchor and extend. Motif Atlas: formalize the intuition; stable IDs, immutable history; science as infrastructure; two independent signals; explicit quality gates). *Origin:* literature (BGSU RNA group), harvested. *Status:* DESIGN (candidates; graduation needs 2+ sources each). *Record:* bgsu-thinking-patterns.md. *C-list:* no.

**TH-187 — Origin-tagging / university hypothesis.** Research labs make the best specialists; origin-tagging (lab/university of origin) predicts specialist quality. *Origin:* perg's hypothesis. *Status:* UNTESTED (Phase 1 census done, 8,268 models; Phase 2 small sweep not started under this framing). *Record:* model-expert-program.md; MEMORY.md. *Settler:* Phase 2 small sweep (0.5B–4B) with origin tags vs performance. *C-list:* no.

**TH-188 — Multitude-of-experts thesis.** A multitude of small expert models beats one general model; every valid model is best-in-band at ≥1 job. *Origin:* perg's preference, tested in Phase 2. *Status:* CONFIRMED (Phase 2: every valid model best-in-band at ≥1 job; control comparison: once template handling is controlled, origin doesn't separate the band; research leads specialties, product steadier). *Record:* phase2-eval-report.md. *C-list:* no.

**TH-189 — Serial-first capacity + RAM overflow lane.** Models need not run in parallel; run best-for-purpose models in series, swapping in/out per task; mrfloppy's ~128 GB system RAM is the overflow lane for quality-critical evals. *Origin:* perg, 2026-10-28/29 (corrected twice: never frame a swap as a sacrifice choice). *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-190 — Deterministic algorithms over model agency.** Wherever a pattern is known, compact reasoning into deterministic algorithms (verification, search, generator-verifier pairs); the leap, the frame, and the goal stay with the person. *Origin:* perg, 2026-10-19 (system-design direction). *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-191 — Final gate as re-derivation.** A final gate is a re-derivation, not a judgment. *Origin:* perg, 2026-10-20 (RE final-gate principle). *Status:* APPLIED (re-derivation runs TH-055 are its implementation). *Record:* MEMORY.md. *C-list:* no.

**TH-192 — Pre-registration discipline.** Thresholds, bars, and protocols are written and hashed BEFORE any measurement; never relaxed post hoc; frozen scores never rewritten. *Origin:* assistant's discipline, perg-approved in each run. *Status:* APPLIED. *Record:* research-gaps.md; all run reports. *C-list:* no.

**TH-193 — Ternary verdicts.** Audit verdicts are three-valued: confirmed (+1) / undecided-void (0) / refuted (−1); 0 must never collapse into −1; verdict levels are labels, not quantities; strength is association count; conflict is its own flag. *Origin:* perg, 2026-10-29. *Status:* APPLIED. *Record:* MEMORY.md; research-gaps.md. *C-list:* no.

**TH-194 — Relation-as-math.** "Once a relation is extracted and audited, it replaces the collective that found it (model proposes, relation computes)." *Origin:* perg, 2026-10-29. *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-195 — HIDE NOTHING EVER (standing order).** Perg's words: "HIDE NOTHING EVER — ALL INFORMATION MUST BE RECORDED SO NOTHING IS MISSING — NOTHING MAY BE CHANGED OR OBFUSCATED. Every tool, idea, and untested theory used in this work is kept in the inventory, recorded complete, and the testing order is set by value to the system." *Origin:* perg, 2026-10-31 (standing order). *Status:* APPLIED (this file is built under it). *Record:* MEMORY.md; inventory header. *C-list:* no.

**TH-196 — Blind-spot math + two hypotheses.** "The only certain knowledge is that the theoretical total differs from what is held; the work is enumerating the forms the difference can take and checking each independently." Hypotheses: (1) the sought information lives at bit level or below (free space, journals, dangling objects, slack bytes); (2) it is present in an unfamiliar datatype searches never see (full datatype census + decoding of never-decoded formats). *Origin:* perg's framing, 2026-10-31. *Status:* CHECKED EMPTY (both checks ran 2026-10-31, 0 recovered; named limits: no raw-disk access, live stores beyond dumps/JSONL unreachable, screenshot pixels + DEX strings unexamined, 169/191 .bin files unsampled, xattr values unread). *Record:* recovery-work/hypotheses/; MEMORY.md. *C-list:* no.

**TH-197 — No-/tmp rule.** "NO /tmp files for his data, ever — no ephemeral scratch that gets deleted, because deleted intermediates make his own data unevaluable to him. All intermediate processing of his data happens in persistent, hashed, retained, delivered staging." *Origin:* perg's order, 2026-10-31. *Status:* APPLIED (this file: persistent staging only, no /tmp). *Record:* MEMORY.md. *C-list:* no.

**TH-198 — Data-unmodified rule.** "His data is to be given to him unmodified — no truncating, changing, or omitting files on the assistant's own say-so; any exclusion needs his explicit word." *Origin:* perg, 2026-10-24. *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-199 — Ownership language rule.** "Nothing generated here is the assistant's — no 'my code,' 'my documents,' 'my verdicts' for generated work; the seed, input, generation, and values are perg's, the price buys that ownership end to end; mistakes stay the assistant's to own, the work stays perg's. No truncation, omission, or deletion of his data/code without his explicit word per item; excerpts labeled as excerpts with the full file linked." *Origin:* perg, 2026-10-31. *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-200 — Centered math / recentering hypothesis.** Centered-math/recentering claims about model internals. *Origin:* perg-pasted framework thread (Q-CM-001/002). *Status:* KILLED/superseded (registry: centered-math killed; frame-shifting superseded by novelty lanes). *Record:* research-registry.md. *C-list:* no.

**TH-201 — Frame-shifting / interpolation coefficients.** Frame-shifting as a reasoning move; interpolation coefficients as its mechanism. *Origin:* perg-pasted framework thread. *Status:* KILLED/superseded (interpolation coefficients killed; frame-shifting lives on only as the novelty-lane frame_shift seat, TH-203). *Record:* research-registry.md. *C-list:* no.

**TH-202 — Novelty lanes.** Seven lanes on :8212 (frame_shift, disconfirm, novelty_score, vague_loop, validity, planted_error_test, analogy); whimsy dropped on perg's tap. *Origin:* perg-approved design, 2026-10-28. *Status:* APPLIED with a known unfixed issue (vague_loop still uses the 0.7 threshold on raw reward scores; redesign awaits perg's word). *Record:* MEMORY.md; novelty-lanes-design.md. *C-list:* no.

**TH-203 — Validity gate.** No preconditions ⇒ "untested", never pass; <50% content-word coverage ⇒ "invalid" (deterministic heuristic). *Origin:* assistant's design, 2026-10-28. *Status:* APPLIED (genuinely gates, unlike the verify gate). *Record:* MEMORY.md. *C-list:* no.

**TH-204 — Verify gate decorative.** The staged Skywork verifier is a style reward and does not separate the planted true/false pair; the verify gate is DECORATIVE as a truth gate. *Origin:* assistant's measurement, 2026-10-28. *Status:* CONFIRMED (planted-error test live 2/3 caught by validity, not by verify). *Record:* MEMORY.md. *C-list:* no.

---

## §10. Perg's own theories and the breeding program

**TH-205 — Seasonal-repetition / media-influence theory.** Perg's words, as recorded in the registry: "the banned channel (subliminal frames; Vicary 1957 was a hoax) was never the working one — influence runs through overt repetition + curation on a seasonal schedule." Perg's fuller statement, as recorded 2026-10-21: "the banned subliminal channel was a hoax-era ghost — the working influence is overt repetition + seasonal curation of media (playlists, ads, feeds) steering population behavior on a schedule; illusory truth is the mechanism." Anchors: Facebook analysts (Gorham & Fiore): +49% relationships started vs ended on Valentine's Day, +34% on Christmas, December net +4% coupling; breakup crests post-Valentine's, spring break, 2 weeks pre-Christmas (McCandless). Exemplar emitter: WVKS 92.5 KISS FM Toledo — iHeart Premium Choice national playlist, 50 kW, same songs cycling ~every 2 hours. Held since high school; predates the adult betrayals. *Origin:* perg's, carried for years, first recorded 2026-10-21 at his word ("if it could be important we should keep it"). *Status:* UNTESTED (registry Q-MI-001/T-MI-001 open, never run; media test December cleanest; test T-MI-001). *Record:* research-registry.md (Q-MI-001, T-MI-001, B-MI-001, B-MI-002); MEMORY.md. *Settler:* the media test (registry T-MI-001). *C-list:* other-list (media/presentation spectrum test).

**TH-206 — Time as the input format (Q-MA-002).** "Time is the clock cycle; the CPU cannot explain the cycle because explanation requires cycles — the precondition for explanation, not an object of explanation." Positional encoding (RoPE in Qwen) is ADDED to token embeddings — there is no separate position/time module; the model processes time-infused tokens but holds no representation of time itself. Whoever assembles the context IS the model's clock. *Origin:* perg's framing, 2026-10-19. *Status:* CONFIRMED in silicon (architecture inspection, not by asking the model); OPEN for biological minds (generalization well-supported but NOT proven); literature check found no exact prior statement. *Record:* research-registry.md (Q-MA-002). *C-list:* no.

**TH-207 — Plant ternary hypothesis (balanced-ternary physiology).** Plant electrical phases map naturally onto balanced ternary (−1 hyperpolarized / 0 resting / +1 depolarized) instead of binary thresholding, which would force a 3-state physiology into 2 states and lose information. *Origin:* perg's hypothesis (untested, needs his voltage traces). *Status:* UNTESTED, PINNED 2026-10-29 (perg's order: equipment not yet acquired — deferred, not dropped). *Record:* MEMORY.md; rig-spec-options.md; research-gaps.md. *Settler:* TH-096's five conditions + ±10% edge-jitter test on rig traces. *C-list:* other-list (plant ternary hypothesis, pinned).

**TH-208 — Quiet-donor requirement.** The stud-line father must be a 'quiet donor' — the mother's bud structure, terps, and effects lead in the F1, the father's vigor and resin underneath. *Origin:* perg's requirement. *Status:* APPLIED (breeding rule). *Record:* MEMORY.md; research-gaps.md (BR entries). *C-list:* no.

**TH-209 — Three-track stud-line plan.** One elite stud line via three tracks: (a) long-flowering × autoflower toward a slow autoflower keeping long-sativa effects; (b) hemp growth speed into a giant cultivar, backcrossed into drug-types then crossed with Northern Lights #5 or C99; (c) cross those lines into the single stud line. *Origin:* perg's breeding plan, 2026-09-25. *Status:* DESIGN (plan; C99 confirmed as pairing pick 2026-10-30). *Record:* MEMORY.md; research-gaps.md. *C-list:* no.

**TH-210 — S1 / clone-first workflow.** Sprout each strain, clone first, every mother backed up in veg before anything is flowered for breeding, then self each strain (S1) for feminized seed backups of the keepers — a few at a time, constrained by the Ohio 6-plants-per-person/12-per-household count. *Origin:* perg's workflow, confirmed 2026-10-30 (order: clone + veg backup before flowering). *Status:* APPLIED. *Record:* MEMORY.md. *C-list:* no.

**TH-211 — Hemp introgression (hunt-and-backcross).** Industrial-hemp vigor introgression: a hunt-and-backcross path (~5 years pheno-hunting plus backcross rounds) aiming to produce something stronger than anything else on the market; ErdPurt leads the hemp shopping card (a September finisher beats freeze survival). *Origin:* perg's plan + Sept 24 analysis. *Status:* DESIGN (plan). *Record:* MEMORY.md; research-gaps.md (BR entries). *C-list:* no.

---

## §11. Engineering / efficiency theories (research-notes surveys)

**TH-212 — Weight quantization for inference.** Quantization (Q4_K_M and kin) preserves capability at a fraction of the memory. *Origin:* literature survey, cross-cutting techniques §(1). *Status:* LITERATURE, applied throughout (all fleet GGUFs; SFT-quant corruption case quarantined — TH-219's companion finding: a hash-matching quant can still be corrupt). *Record:* research_notes/cross-cutting-ai-techniques-20261003-1757/report.md. *C-list:* no.

**TH-213 — KV-cache quantization.** KV-cache quantization (FP8 KV, INT8 KV-quant) buys context/memory headroom. *Origin:* literature survey. *Status:* LITERATURE, applied (Strata INT8 KV-quant live; FP8 KV 4090-only per the Strata audit). *Record:* cross-cutting survey §(2); MEMORY.md (Strata audit). *C-list:* no.

**TH-214 — Speculative decoding variants (EAGLE, DFlash2, MTP).** Draft-model speculative decoding speeds up decode. *Origin:* literature survey. *Status:* PARTIAL — measured and CLOSED for quicklook (0.85× slower; do not re-offer unless target or draft changes); EAGLE 3.1 needs acceptance-rate measurement; MTP speculative live on Strata (do not re-offer). *Record:* cross-cutting survey §(3); MEMORY.md. *C-list:* no.

**TH-215 — Distillation recipes + ternary/BitNet-style distillation.** Distillation (including ternary/BitNet-style) transfers capability into small models. *Origin:* literature survey. *Status:* LITERATURE; the distillation-vs-melding guardrail (TH-053) governs its use here. *Record:* cross-cutting survey §(4). *C-list:* no.

**TH-216 — LoRA/QLoRA fine-tuning best practice (2026).** LoRA/QLoRA recipes for small-model adaptation (incl. Qwen3-4B tool-calling LoRAs: sweatSmile Function-Calling-Pro, 154teru structured-output adapter, MimiTechAI mimi-pro — authors admit degradation + parallel-calling issues). *Origin:* literature survey + LoRA survey 2026-10-30. *Status:* LITERATURE; judgment recorded: generic tool-calling LoRAs may lift CONTRACT, unlikely to lift TRIAGE (judgment needs task data that does not exist; training on frozen tasks = contamination); the Qwen3-4B LoRA-variants run was offered, not tapped. *Record:* cross-cutting survey §(5); glimmer LoRA survey notes. *C-list:* no.

**TH-217 — Eval-harness design for honest local comparison.** Frozen graders, frozen prompts, template control, verbatim re-derivation. *Origin:* literature survey + program practice. *Status:* APPLIED (Phase 2 DET re-derivation: zero mismatches across 16 Oct 22 dirs; boxed re-score discipline). *Record:* cross-cutting survey §(6); phase2-eval-report.md. *C-list:* no.

**TH-218 — MLA / KV-cache compression (DeepSeek).** Multi-head latent attention compresses the KV cache. *Origin:* literature (DeepSeek-V3/R1 reports, arXiv:2412.19437 / arXiv:2501.12948). *Status:* LITERATURE (background). *Record:* research_notes/deepseek-efficiency-papers-20261002-0711/report.md §3. *C-list:* no.

**TH-219 — FP8 / FP4 / NVFP4 training & inference.** Ultra-low-precision floating point for training and inference. *Origin:* literature (DeepSeek survey §4). *Status:* LITERATURE; hardware-gated here (no FP8/NVFP4 on frank's 2070 SUPER sm_75; FP8 KV 4090-only). *Record:* deepseek survey §4. *C-list:* no.

**TH-220 — MoE routing / load-balancing.** MoE expert routing and load-balancing improvements. *Origin:* literature (DeepSeek survey §5). *Status:* LITERATURE (background; Strata's MoE expert offload is the local instance). *Record:* deepseek survey §5. *C-list:* no.

**TH-221 — R1-style RL reasoning replication.** R1-style RL reasoning can be replicated in small models. *Origin:* literature (DeepSeek survey §6). *Status:* LITERATURE (background). *Record:* deepseek survey §6. *C-list:* no.

**TH-222 — Ultra-low-precision 1.58-bit ternary inference.** 1.58-bit ternary weights (BitNet-style) run at full capability. *Origin:* literature (DeepSeek survey §7). *Status:* PARTIAL — evaluated locally and REJECTED for the scout seat (Ternary-Bonsai-2-27B-PTQ1_0: safety gate 0.0, summarization 0.909 beat baseline, 5.2 vs 14.2 tok/s; whether REJECT still stands is an open question — no newer eval found). *Record:* deepseek survey §7; MEMORY.md. *C-list:* no.

**TH-223 — TTS architectures (VoxCPM2, Voxtral, MOSS, RVC, streaming).** Open TTS models and real-time voice conversion architectures for the GLaDOS voice. *Origin:* literature survey, voice/TTS deep dive §§(1)–(3),(5). *Status:* LITERATURE; decisions stand: Piper stays; Fish Audio S2 REJECTED (too human); Twin's RVC models rejected; RVC retrain on Portal audio + custom Valve-recipe DSP chain remain parallel paths. *Record:* research_notes/voice-tts-2026-deep-dive-20261003-2000/report.md. *C-list:* no.

**TH-224 — Hardware vs software vocal processing.** Software processing beats hardware for the GLaDOS voice (hardware's edge is live-mic reliability only). *Origin:* voice/TTS deep dive §(4) (how GLaDOS was actually made). *Status:* CONFIRMED (design decision: skip hardware vocal processing). *Record:* voice-tts report §(4); MEMORY.md. *C-list:* no.

**TH-225 — STT stack (faster-whisper, streaming, diarization).** STT baselines, true-streaming alternatives for barge-in partials, accuracy kings, and the missing speaker layer (NVIDIA Nemotron 3 Diarization). *Origin:* literature survey, voice/TTS §(6) + 72h scan. *Status:* LITERATURE/design (faster-whisper baseline; diarization unbuilt). *Record:* voice-tts report §(6); local-ai-72h-scan report. *C-list:* no.

**TH-226 — Dark-matter model ecosystem.** The weight ecosystem NOT on Hugging Face (alternative hubs: Civitai, ModelScope, Ollama registry, Kaggle, Tensor.art/SeaArt, Pirate Face; rarely-released artifacts: full intermediate checkpoint suites, public training datasets, optimizer states; models removed from HF) matters for coverage. *Origin:* survey, dark-matter report. *Status:* LITERATURE (background; Phase 1 census covered 8,268 models on HF — the dark-matter census is unbuilt). *Record:* research_notes/dark-matter-model-ecosystem-20261003-1732/report.md. *C-list:* no.

**TH-227 — FreeToken reality check.** FreeToken only wins when the MoE doesn't fit VRAM. *Origin:* community finding, local-ai community scan. *Status:* CONFIRMED as a check (needs ~192GB RAM for big configs — mrfloppy's 125GB is short). *Record:* local-ai-community-scan report; MEMORY.md (Strata check). *C-list:* no.

**TH-228 — Qwen3.8 thinking-mode control.** Qwen3.8 thinking mode is controlled by template/chat_template_kwargs, with known failure modes (thinking burn → empty content). *Origin:* literature + program measurement. *Status:* CONFIRMED (mechanism finding M1: template control dominates; Qwen3-4B needs BUDGET not kwargs; LFM3 needs enable_thinking:false on EVERY request). *Record:* qwen3-8-27b report; phase2-eval-report.md (M1–M9). *C-list:* no.

---

## §12. The gap: theories NOT covered by the C-list inventory

The existing inventory (`complete-inventory-and-value-order.md` §3) covers C1–C20 (19 entries here, TH-012/014–018/021–032/034 — C13 and C14 share TH-034) plus 13 other-list items (TH-010, TH-048, TH-049, TH-060, TH-061, TH-063, TH-064, TH-065, TH-076, TH-077, TH-096, TH-205, TH-207). Everything below — **196 theories** — is NOT in that inventory at all. This is the gap perg pointed at: the C-list is 20 claims from one pasted synthesis; the record holds 208 more theories, frameworks, and lenses, of which 196 were not even named in the inventory.

### §1 gap (24)
TH-001 Category-theory translation · TH-002 Shaving construction · TH-003 H¹ obstruction / emptiness equivalence · TH-004 Adding-hands / control framework · TH-005 Multidimensional shape · TH-006 Gluing blindness · TH-007 Irrational anchor as foundation (killed) · TH-008 Irrational anchor as heuristic/discipline · TH-009 More-anchors answer · TH-011 Overshoot framework · TH-013 Lens-guided verification framework · TH-019 Emergence ≠ compressibility "proof" (refuted) · TH-020 Ternary mirror math · TH-033 TASEP / max-plus framework · TH-035 Three-floors distinction · TH-036 Spectral framework · TH-037 Trajectory method · TH-038 Precision-then-shift · TH-039 Anchor test · TH-040 Dual certificate / Farkas extraction · TH-041 Four-cell seat-pair table · TH-042 Search-vs-identifiability triage · TH-043 Hit-rate discipline · TH-044 Mutual information as probe-selection.

### §2 gap (15)
TH-045 Null as complexity sensor · TH-046 Lag as sensor (refuted) · TH-047 Hammer recalibration (refuted) · TH-050 Calculator failure floor · TH-051 Lean-rule dominance · TH-052 Decider merge with ⊤ = "disagree" · TH-053 Distillation-vs-melding guardrail · TH-054 Evidence-class guard · TH-055 Second-route requirement · TH-056 Interface-contract hypothesis (refuted) · TH-057 Reference-filtered test design (v3) · TH-058 Disagreement = fast-right pattern · TH-059 Quicklook empties mechanism · TH-062 Real-diff transfer (refuted) · TH-066 Determinism / re-runs add no evidence.

### §3 gap (11)
TH-067 Wall-as-quantile · TH-068 Scaling base b ≈ 1.10–1.13/var · TH-069 Threshold (S-curve), not exponential · TH-070 UNSAT-driven wall · TH-071 Per-node cost rise · TH-072 Tail-noise / composition explanation · TH-073 Watched literals · TH-074 VSIDS · TH-075 Heap-ordered VSIDS pick · TH-078 Preprocessing (Stage 5) · TH-079 Cap-edge jitter amendment.

### §4 gap (12)
TH-080 Difference imaging + Tikhonov prior · TH-081 Morozov discrepancy λ rule · TH-082 Inverse-crime reduction · TH-083 Resolution/uncertainty reporting rule · TH-084 Spectrum decay / effective rank · TH-085 Sharp mobility edge (refuted → crossover) · TH-086 Cheeger 2-way bound · TH-087 Modal frequencies = wave equation · TH-088 ker D (untested) · TH-089 Linear vs nonlinear shaves for address data · TH-090 Negative-contrast linearization asymmetry · TH-091 Two-inclusion resolution limit.

### §5 gap (29)
TH-092 Closed-loop policy · TH-093 Inverse-problem discipline · TH-094 Frozen-encoder-first decoding · TH-095 Gradient-TTA ban · TH-097 Routing repair / ablation test · TH-098 Hodgkin–Huxley prior · TH-099 PBPK/SEIR credibility + identifiability · TH-100 MLIP caution · TH-101 Levin bioelectricity · TH-102 Ion channels as computation · TH-103 Plant electrophysiology parallel + honest baseline · TH-104 "Do not act" gate · TH-105 No single-driver stories · TH-106 Lab-vs-field reporting · TH-107 Triage framing · TH-108 Non-inferiority discipline · TH-109 EIT consensus template · TH-110 Vivent claims (void) · TH-111 Artificial pancreas · TH-112 TMS/tDCS/tACS · TH-113 Focused ultrasound · TH-114 NV-diamond sensing · TH-115 Ingestible/wearable sensing · TH-116 Spinal/cochlear/retinal stimulation · TH-117 Bioelectricity in aging · TH-118 Organ-on-chip · TH-119 AI imaging beyond ECG/EEG · TH-120 Digital twins · TH-121 Computing axes ranking.

### §6 gap (29)
TH-122 Komlós/Bansal–Jiang · TH-123 Hauke Poissonian rotation · TH-124 Aistleitner metric DA · TH-125 Baier–Roy primes · TH-126 Kelley–Meka · TH-127 Guth–Maynard · TH-128 Harper GMC (announced) · TH-129 Diagonal Ramsey · TH-130 r(4,t) asymptotics · TH-131 Random-graph sandwich · TH-132 Hikita e-positivity · TH-133 Aperiodic monotile · TH-134 Moving sofa · TH-135 Noperthedron · TH-136 Unknotting non-additivity · TH-137 Kervaire 126 · TH-138 Dudeney dissection · TH-139 Hyperbolic surfaces · TH-140 Kakeya 3D · TH-141 Mizohata–Takeuchi counterexample · TH-142 Hilbert sixth, kinetic part · TH-143 Nonuniform Schauder · TH-144 Euler blowup · TH-145 Diagram-free regularity structures · TH-146 GMC / Garban–Vargas · TH-147 Geometric Langlands · TH-148 Absoluteness V/HOD · TH-149 Large cardinals beyond HOD · TH-150 Tier 1/2/3 synthesis ranking.

### §7 gap (11)
TH-151 Lean/AlphaProof verification · TH-152 CAS + continued-fraction certificates · TH-153 ASP/Dung retraction + conflict audit · TH-154 Bayesian action / VOI routing · TH-155 SMT/solver-backed verification · TH-156 Compartmental/PBPK models · TH-157 SEIR + identifiability · TH-158 MLIP energy landscapes · TH-159 Graph+ODE hybrids / representation sensitivity · TH-160 Field ranking · TH-161 Anchor verdict per field.

### §8 gap (22)
TH-162 Wire doctrine · TH-163 Generative null · TH-164 Q-table size ≠ learning · TH-165 Bits-through-queues (killed) · TH-166 SOC (killed) · TH-167 Fibonacci waveform (killed) · TH-168 Kuramoto/Arnold tongue (killed) · TH-169 Phase Response Curve (killed) · TH-170 DFA/Hurst (superseded) · TH-171 Timescale decomposition · TH-172 Diet battery instrument · TH-173 Quorum sensing / motif method · TH-174 Cube contention/propagation · TH-175 Busy-tone ratio · TH-176 Flip-a-tile v2 (void) · TH-177 Pointer heuristic · TH-178 P170 family · TH-179 P10240 array · TH-180 Grid sensor (void) · TH-181 World-model sensor (refuted) · TH-182 Mirage-check resolution · TH-183 72h ticks.

### §9 gap (21)
TH-184 Scientist OS invariants · TH-185 WHY/PATH/HOW/WHAT harvest · TH-186 Thinking-pattern harvest (BGSU) · TH-187 Origin-tagging / university hypothesis · TH-188 Multitude-of-experts thesis · TH-189 Serial-first capacity · TH-190 Deterministic algorithms over agency · TH-191 Final gate as re-derivation · TH-192 Pre-registration discipline · TH-193 Ternary verdicts · TH-194 Relation-as-math · TH-195 HIDE NOTHING EVER · TH-196 Blind-spot math + two hypotheses (checked empty) · TH-197 No-/tmp rule · TH-198 Data-unmodified rule · TH-199 Ownership language rule · TH-200 Centered math (killed) · TH-201 Frame-shifting / interpolation coefficients (killed) · TH-202 Novelty lanes · TH-203 Validity gate · TH-204 Verify gate decorative.

### §10 gap (5)
TH-206 Time as the input format · TH-208 Quiet-donor requirement · TH-209 Three-track stud-line plan · TH-210 S1 / clone-first workflow · TH-211 Hemp introgression.

### §11 gap (17)
TH-212 Weight quantization · TH-213 KV-cache quantization · TH-214 Speculative decoding · TH-215 Distillation recipes · TH-216 LoRA/QLoRA best practice · TH-217 Eval-harness design · TH-218 MLA / KV compression · TH-219 FP8/FP4/NVFP4 · TH-220 MoE routing · TH-221 R1-style RL replication · TH-222 1.58-bit ternary inference · TH-223 TTS architectures · TH-224 Hardware vs software vocal processing · TH-225 STT stack · TH-226 Dark-matter model ecosystem · TH-227 FreeToken reality check · TH-228 Qwen3.8 thinking-mode control.

## Counts

**Total theories: 228** (TH-001–TH-228).

| Status | Count | Entries |
|---|---|---|
| CONFIRMED (tested, +1) | 38 | TH-045, 050, 051, 055, 058, 063, 064, 066, 067–075, 079, 080, 081, 084, 086, 087, 090, 164, 172, 174, 175, 177–179, 182, 183, 188, 204, 224, 227, 228 |
| REFUTED (tested, −1 as stated) | 8 | TH-019, 046, 047, 056, 062, 065, 085, 181 |
| PARTIAL (a leg remains open) | 13 | TH-002, 011, 013, 017, 021, 030, 036, 061, 076, 091, 206, 214, 222 |
| UNTESTED | 29 | TH-006, 012, 014–016, 018, 022–029, 031, 032, 034, 044, 048, 059, 060, 077, 078, 088, 089, 096, 187, 205, 207 |
| ANALOGY (not pinned to a testable claim) | 3 | TH-001, 003, 033 |
| DESIGN (applied/ready as design, not a finding) | 29 | TH-004, 005, 008, 010, 020, 035, 040, 042, 052–054, 057, 082, 092, 094, 095, 097, 099, 104, 109, 151–155, 184, 186, 209, 211 |
| LITERATURE (published result; transfer status per entry) | 61 | TH-009, 098, 100–103, 111–121, 122–149, 156–159, 173, 212, 213, 215, 216, 218–221, 223, 225, 226 |
| APPLIED (method/rule in force) | 33 | TH-037–039, 041, 043, 083, 093, 105–108, 150, 160, 161, 162, 163, 171, 185, 189–193, 195, 197–199, 202, 203, 208, 210, 217 |
| KILLED (tested and dropped, or closed) | 9 | TH-007, 165–170, 200, 201 |
| VOID (run produced no signal) | 5 | TH-049, 110, 176, 180, 196 (checked empty) |
| **Total** | **228** | |

C-list coverage: **20/20 C-numbers covered** (19 entries; C13+C14 share TH-034) + **13 other-list items** named in the inventory's other-untested list + **196 theories with no inventory coverage at all**. Perg was right: the C-list captured less than a tenth of the record's theories.

## Limits of this enumeration (named, not hidden)

1. **TASEP verbatim §A/§B/§E lists not exploded.** The pasted synthesis contains a "Complete Inventory" of 56 established theorems (§A), 22 derived results (§B), and 12 empirical measurements (§E). Those 90 items are preserved COMPLETE and VERBATIM in `~/workspace/inventory/tasep-maxplus-synthesis-verbatim.md` (39,828 bytes, md5 `2e64f3535093ab592de2fdc22598b01c`) and are NOT re-enumerated as individual entries here, except the named items the record itself singles out (B10 → TH-031, B16 → TH-032, B22 → TH-029, and the §C claims C1–C20). Exploding §A/§B/§E into 90 more entries is a defined follow-up pass; it was not done here because the verbatim file already is the complete record of them, and duplicating it would risk altering it.
2. **Pasted documents known only through evaluations.** The catalogue, isomorphism document, overshoot framework, and spectral framework documents themselves are not separate files in this workspace; they survive as perg-pasted chat text evaluated in the record (research-gaps.md assessments + the delivered transcript). Their keeps/flags are entered here from those evaluations; no entry claims a reading of an original that was not read.
3. **Attribution where the record is thin.** Where a framework's author is "perg-pasted document" without a named author in the record, that is stated. Where the direction of a correction is not cleanly settled in the record (continuous-time Gramian application, TH-004), no direction is assigned.
4. **Status is as of 2026-10-31.** Nothing here launches, edits the map, or changes any verdict. Settling tests are stated per untested entry; the value order in `complete-inventory-and-value-order.md` §4 still governs sequencing, and nothing launches without perg's tap per item.
