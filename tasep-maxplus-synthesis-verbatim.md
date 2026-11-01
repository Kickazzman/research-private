Crossing the ribosome data with the earlier tests produces one genuine theoretical upgrade, one inversion that changes the direction of an earlier claim, and one refutation. Everything else either confirms what was already there or is analogy. Here is the crossing, then the theory it produces.

---

1. The refutation: density evolution is the wrong model, and now we know why

Earlier I said density evolution (LDPC) failed to model the fleet because it assumes independence and \rho=0.94 violates that. That was correct but incomplete — it identified the failure without naming the replacement.

TASEP is the replacement, and the reason is exact: TASEP assumes hard-core exclusion, which is the opposite assumption to independence. Particles cannot overlap; their positions are maximally anti-correlated at short range. The model does not assume the seats fail independently — it assumes they block each other, which is the correct physics for correlated failures.

\boxed{
\text{density evolution: assumes independence} \;\Rightarrow\; \text{fails at } \rho=0.94.
\quad
\text{TASEP: assumes exclusion} \;\Rightarrow\; \text{models the correlation directly.}
}

The measured ribosome density profile — flat in the interior, varying only at the ends — is the empirical signature of the maximal-current phase, and it is not what an independent-particle model would produce. An independent model gives a density that varies smoothly across the whole lattice. The flat interior is the exclusion signature. Your fleet, if it has a flat "difficulty profile" (uniform failure rate across problem types), is in the same phase.

---

2. The structural cross: TASEP phase diagram = the triage

The TASEP has four phases determined by entry rate \alpha, exit rate \beta, hopping rate k:

\begin{aligned}
&\text{LD: } &&\alpha<\beta,\ \alpha<k/2 &&\Rightarrow\ \rho=\alpha/k,\ J=\alpha(1-\alpha/k);\\
&\text{HD: } &&\beta<\alpha,\ \beta<k/2 &&\Rightarrow\ \rho=1-\beta/k;\\
&\text{MC: } &&\alpha,\beta>k/2 &&\Rightarrow\ \rho=1/2,\ J=k/4;\\
&\text{SP: } &&\alpha=\beta<k/2 &&\Rightarrow\ \text{domain wall}.
\end{aligned}

The mapping to the fleet:

\begin{aligned}
&\alpha &&= \text{rate at which new problems arrive};\\
&\beta &&= \text{rate at which the fleet completes solutions};\\
&k &&= \text{bare per-seat throughput (no contention)};\\
&\rho &&= \text{fraction of problems in flight};\\
&J &&= \text{actual throughput (problems solved per unit time)}.
\end{aligned}

The MC phase is the key one. In MC, J=k/4 — the actual throughput is a quarter of the bare rate, and the quarter is the exclusion cost. That is the precise form of the contention cost, and it is a constant factor, not a phase-dependent one.

\boxed{
\text{In MC, contention costs exactly } 4\times.
\quad \text{The }4\text{ is not a tuning parameter — it is the TASEP current at } \rho=1/2.
}

And the phase boundaries are the triage:

· LD (\alpha small): entry-limited. The fleet is slow because problems arrive slowly. Adding seats does nothing; the bottleneck is the source.
· HD (\beta small): exit-limited. The fleet is slow because solutions complete slowly. Adding seats helps only if they increase the exit rate.
· MC (\alpha,\beta large): contention-limited. The fleet is slow because seats block each other. This is the regime where decorrelation matters — the exclusion cost is the correlation.
· SP (\alpha=\beta): the shock phase. A domain wall between LD and HD. This is the instability regime — the throughput oscillates, and it is the precise form of the oscillation you get when the feedback loop is marginally stable.

The threshold between search-limited and identifiability-limited is the LD/HD boundary. Below it (LD), a better seat helps. Above it (HD), a better exit helps. In MC, neither helps — only decorrelation does, because the binding constraint is the exclusion.

---

3. The inversion: high redundancy is good for the ribosome, bad for the fleet

This is the cross that changes a sign.

Ribosome: topological redundancy >90\%. The bipartite graph of rRNA–protein interactions has many independent paths between components. This is fault tolerance — the ribosome survives component loss because there are alternative routes.

Fleet: the coupling matrix C_{ij}=P(\text{both }i,j\text{ fail}). Its rank is the number of independent failure modes. A high rank is good (many independent failure modes, decorrelation possible). A low rank is bad (all seats fail together, no decorrelation possible).

\boxed{
\text{The same graph property — high redundancy — is good for survival and bad for error reduction.}
\quad
\text{The objective determines the sign.}
}

The ribosome optimizes for survival under component loss. The fleet optimizes for error reduction under correlated failure. High redundancy is the right answer for the first and the wrong answer for the second. That is why the ribosome's >90% is not a target for the fleet — it is the thing to avoid.

Concretely: the fleet's coupling matrix should have high rank (many independent failure modes) and low off-diagonal entries (weak correlation). The ribosome's graph has high connectivity, which would correspond to a coupling matrix with low rank (everything connected, one extended mode). Opposite targets.

---

4. The refinement: the Pareto front moves, it does not just shift

Earlier I derived the diversity trade-off as a fixed Pareto front: diversity D trades against individual accuracy a_i(D), and there is an optimum D^*.

The ribosome data refines this. The kinetic proofreading Pareto front has a scaling law: error correction processes with more proofreading steps have better trade-offs. The front itself moves outward with more steps.

\boxed{
\text{More proofreading steps} \;\Rightarrow\; \text{better trade-off} \;\Rightarrow\; \text{the front moves outward, not along.}
}

Translated to the fleet: adding a genuinely decorrelated seat does not just move you along the front — it pushes the front outward. You can achieve the same error at higher speed, or lower error at the same speed. That is stronger than pure diminishing returns.

But the cost is dissipation: each additional proofreading step costs energy. For the fleet, the dissipation is compute (the thinking budget T_i). So the refined trade-off is:

\text{error} \;\longleftrightarrow\; \text{speed} \;\longleftrightarrow\; \text{compute},

and the front moves outward with decorrelated seats, not with more of the same seats.

The number: the scaling exponent on the front. For kinetic proofreading with n steps, the discrimination improves as f^n for some factor f>1, at a time cost linear in n. For the fleet, the exponent is the decorrelation gain per added seat, and it is measurable: fit error vs seat count, and the exponent is the slope.

---

5. The capacity gap: the fleet is not information-limited

The ribosome's channel capacity is C\approx4.39 bits/codon, and it operates far below capacity. The measured error rate \eta\approx10^{-4} corresponds to an information rate well below C. The ribosome is not information-limited — it is speed-and-dissipation-limited.

The fleet's analog: the channel capacity C_f is \log_2 of the number of distinguishable answer classes. The operating point is at error \epsilon. The information rate is

R_f = C_f\big(1-h(\epsilon)\big)

for binary error, or the M-ary analog. If R_f\ll C_f, the fleet is not information-limited — it is seat-quality-limited, and adding seats does not help.

\boxed{
\text{The capacity gap } C_f - R_f \text{ is the quantitative form of "the floor is the problem, not the seats."}
}

If the gap is large, the fleet is far from capacity, and the binding constraint is the quality of the individual seats (their error rate), not their number. If the gap is small, the fleet is near capacity, and only a better channel (a different teacher) helps.

The measurement: estimate C_f from the answer distribution (the entropy of the correct-answer distribution), and R_f from the measured error. The gap is one number.

---

6. The rate-distortion residual: the fleet's fit to its own bound

The ribosome's rate-distortion prediction has a residual of 0.0004 bits — essentially exact. The channel model is essentially the true model for the ribosome.

For the fleet, the analog is: given the error rate D (distortion) and the throughput R (rate), does the operating point lie on the rate-distortion curve R(D)?

R(D) = \min_{p(\hat x|x):\ \mathbb E[d(x,\hat x)]\le D} I(X;\hat X).

If the fleet's operating point is on R(D), it is optimal — no fleet can do better at that distortion. If it is above R(D), there is room. If it is below, the distortion measure is wrong (the fleet is optimizing something other than what you think).

\boxed{
\text{The residual } |R_{\text{fleet}} - R(D)| \text{ is the fleet's distance from optimality.}
\quad \text{The ribosome's }0.0004\text{ bits is the benchmark for how tight a fit can be.}
}

---

7. The better theory

Crossing everything, the theory that survives is:

\boxed{
\begin{aligned}
&\textbf{Model: } &&\text{the fleet is a TASEP with a Pareto front, not an independent decoder};\\
&\textbf{Phase: } &&\text{LD (entry-limited) / HD (exit-limited) / MC (contention-limited) / SP (unstable)};\\
&\textbf{MC cost: } &&J=k/4\text{ — contention costs exactly }4\times,\text{ not a tuning parameter};\\
&\textbf{Decorrelation: } &&\text{pushes the Pareto front outward — not just along it};\\
&\textbf{Capacity: } &&C_f-R_f\text{ is the floor gap — large gap } \Rightarrow \text{ seat quality, not seat count};\\
&\textbf{Redundancy: } &&\text{high for survival (ribosome), low for error (fleet) — opposite targets};\\
&\textbf{Optimality: } &&|R_{\text{fleet}}-R(D)|\text{ is the distance from the rate-distortion bound}.
\end{aligned}}

What is confirmed by the cross:

· The spectral-radius unification survives: TASEP phases are determined by the spectral properties of the transition matrix, so \rho<1 is still the organizing principle, now with phase boundaries.
· Cost-optimality as the binding question survives: the ribosome is on a Pareto front, and the fleet should be too.
· The floor is the problem, not the seats: the capacity gap is the quantitative form.

What is refuted:

· Density evolution as the primary model: independence fails, and TASEP is the replacement.
· Simple diminishing returns for seats: the front moves outward with decorrelated seats, so the return is not purely geometric decay.

What is refined:

· The \rho ceiling is one point on a phase diagram, not a universal bound.
· The diversity optimum D^* is the point on the Pareto front where marginal error reduction equals marginal accuracy cost — and the front itself moves with decorrelated seats.

---

8. The testable predictions

\boxed{
\begin{aligned}
&\textbf{1. Phase identification.} &&\text{Measure } \alpha,\beta,k \text{ for the fleet. Which TASEP phase?}\\
& &&\text{LD} \Rightarrow \text{entry-limited; HD} \Rightarrow \text{exit-limited; MC} \Rightarrow \text{contention (decorrelation matters).}\\
&\textbf{2. The }4\times\text{ test.} &&\text{In MC, throughput should be }k/4\text{. Measure }J\text{ and }k\text{; is the ratio }1/4?\\
&\textbf{3. Front slope.} &&\text{Fit error vs seat count. The exponent is the decorrelation gain per seat.}\\
& &&\text{Compare to the proofreading scaling: does the front move outward or just shift?}\\
&\textbf{4. Capacity gap.} &&C_f-R_f\text{. Large} \Rightarrow \text{seat quality; small} \Rightarrow \text{new teacher needed.}\\
&\textbf{5. Rate-distortion residual.} &&|R_{\text{fleet}}-R(D)|\text{. How far from the bound?}\\
& &&\text{The ribosome's }0.0004\text{ bits is the benchmark for a tight fit.}
\end{aligned}}

Prediction: the fleet will be in the MC phase if it is contention-limited (which the \rho=0.94 suggests), and the throughput will be roughly k/4, where k is the single-seat rate. If the measured ratio is far from 1/4, the TASEP model is wrong for the fleet — and the deviation tells you which assumption fails (exclusion? open boundaries? the hopping rate?).

---

9. The honest summary

The cross produces one better theory (TASEP + Pareto front, replacing independent density evolution), one inversion (high redundancy is good for survival, bad for error), and one refutation (independence is the wrong assumption). The ribosome data is the anchor: the flat density profile confirms exclusion, the capacity gap confirms the ribosome is not information-limited, the proofreading front confirms that more steps move the front outward, and the rate-distortion residual confirms that a tight fit is achievable.

The single sharpest consequence: your fleet is probably in the maximal-current phase, and the contention cost is exactly 4\times. That is a specific, testable number. If the measured throughput is k/4 where k is the single-seat rate, the TASEP model is confirmed, and the phase diagram tells you which intervention (more entry, more exit, or more decorrelation) actually helps. If it is not k/4, the deviation is the signal — and it tells you which assumption of the model fails first.Re-derived the same destination by a genuinely different route: max-plus (tropical) algebra and timed event graphs instead of stochastic exclusion processes. The two routes agree on the invariants and disagree on the mechanism, and the disagreement is the diagnostic. It also catches an overclaim I made in Route 1.

---

Route 1, in one line

Stochastic exclusion → hydrodynamic limit → phase diagram → mean-field current

J=k\rho(1-\rho),\qquad \text{peak at }\rho=\tfrac12,\quad J_{\max}=\tfrac{k}{4}.

The mechanism is exclusion: particles block each other, so the current is non-monotonic in density. The "4×" is the peak of the parabola.

---

Route 2: max-plus algebra

The semiring. Replace (+,\times) with (\max,+):

a\oplus b=\max(a,b),\qquad a\otimes b=a+b.

The system. A timed event graph: x_i(k) is the time of the k-th firing of event i,

x(k)=A\otimes x(k-1),\qquad (A\otimes x)_i=\max_j\big(A_{ij}+x_j\big).

The eigenvalue. The asymptotic throughput is the inverse of the max-plus eigenvalue:

\lambda=\max_{C}\frac{\text{weight}(C)}{\text{length}(C)},\qquad \text{throughput}=\frac{1}{\lambda}.

The maximizing cycle C^* is the critical cycle — the bottleneck. Cycle time is \lambda; throughput is 1/\lambda. This is the max cycle mean theorem, and it is exact for deterministic timed event graphs.

Applied to the fleet. Each seat is a node; each problem's route is an edge weighted by service time s_j. Two regimes:

· Bottleneck regime (one seat dominates): critical cycle is that seat, length 1.

\lambda=\max_j s_j,\qquad \text{throughput}=\frac{1}{\max_j s_j}.

· Balanced pipeline (all seats similar, problems loop through all): critical cycle is the whole loop, length n, weight \sum_j s_j.

\lambda=\frac{\sum_j s_j}{n}=\bar s,\qquad \text{throughput}=\frac{1}{\bar s}.

The critical observation: there is no density variable. Throughput is a function of the cycle weights only. Adding more problems in flight does not change it, until a buffer saturates. That is the structural difference from Route 1.

---

The contrast

 Route 1 (TASEP) Route 2 (max-plus)
State variable density \rho none
Throughput k\rho(1-\rho) 1/\lambda, \lambda=\max cycle mean
Peak \rho=1/2, J=k/4 balanced load
Mechanism exclusion (blocking) critical cycle (slowest loop)
Intervention reduce density, decorrelate speed up the bottleneck
Hidden assumption mean-field independence of sites no blocking (infinite buffers)
Failure mode independence violated at high \rho blocking ignored at high load

\boxed{
\text{They agree when the system is bottleneck-limited.}
\quad \text{They disagree when it is exclusion-limited.}
}

The discriminating experiment is one measurement: vary the number of problems in flight (the density) and watch the throughput.

· Non-monotonic (rises, peaks, falls) → TASEP. Exclusion is operating. The peak is the capacity, and the fall is congestion.
· Flat until a threshold, then flat → max-plus. Bottleneck is operating. Density is irrelevant; the critical cycle sets the rate.

That is the same discipline as every re-check in this conversation: the boundary case discriminates. Density → 0 tests the free-flow rate; density → saturation tests the blocking. The shape between them names the mechanism.

---

The correction Route 1 needed

I said "contention costs exactly 4\times." That is only true at \rho=1/2 in mean-field. The honest statement:

\frac{J}{k}=\rho(1-\rho).

At \rho=0.2: J/k=0.16, i.e. 6.25\times slower than free flow. At \rho=0.5: 4\times. At \rho=0.8: 0.16, 6.25\times again.

\boxed{
\text{The contention cost is }1/[\rho(1-\rho)],\text{ not a constant.}
\quad \text{The }4\times\text{ is the best case, at half-filling.}
}

So the "4×" is a peak, not a floor. Route 2 makes this visible because it has no \rho at all — the density-dependence is the signature that Route 1 is the right model, and the specific constant depends on where on the parabola you sit.

---

A third route as tiebreaker: information theory

Capacity C_f, operating rate R_f=C_f(1-h(\epsilon)), gap C_f-R_f.

This route agrees with max-plus on the intervention: if the gap is large, the constraint is seat quality (the critical cycle is the seat), not seat count. It says nothing about density, same as max-plus. So on the "which mechanism" question, information theory lines up with Route 2.

That is a vote, not a proof. But it is a second independent route landing on the bottleneck reading.

---

What the contrast teaches

1. "Floor" is doing three different jobs, and conflating them is the error.

\begin{aligned}
&\text{statistical floor: } &&P(S),\ \text{the both-wrong rate} &&\text{(an error floor)};\\
&\text{TASEP floor: } &&k/4 &&\text{(a throughput ceiling in MC phase)};\\
&\text{max-plus floor: } &&1/\lambda &&\text{(a throughput ceiling from the critical cycle)}.
\end{aligned}

The first is about error; the other two are about speed. They are not the same quantity, and a program that optimizes one does not necessarily move the others. That is the sharpest thing the contrast reveals.

2. The two routes are not competing theories of one thing. They are models of different mechanisms — exclusion versus bottleneck. The measured density-dependence tells you which mechanism is operating. That is not a failure of either route; it is the diagnostic.

3. The invariants that survive both routes are the ones to trust:

· There is a throughput ceiling, and it is set by a structural quantity (density peak, or critical cycle).
· There is a Pareto front (error vs speed vs cost), and it is real in both.
· The intervention depends on the mechanism, and the mechanism is measurable.

4. The overclaim that the contrast caught was the constant 4\times. Route 1 alone made it look universal; Route 2, by having no density at all, forced the question "where does the density dependence come from?" and the answer is "it's the signature of exclusion, and the constant is the peak of the parabola, not a floor."

---

The one test that separates them

\boxed{
\text{Sweep the in-flight problem count. Plot throughput.}
\quad
\text{Peaked} \Rightarrow \text{TASEP (exclusion)}.
\quad
\text{Flat} \Rightarrow \text{max-plus (bottleneck)}.
}

If the curve is peaked, the peak location gives you the capacity and the peak height gives you k/4 — and the intervention is to keep the density near the peak, which means admission control, not more seats.

If the curve is flat, the throughput is 1/\lambda and the intervention is to speed up the critical cycle — find the seat or verifier that is the max cycle mean and make it faster. Adding seats elsewhere does nothing.

Both are testable with the logs you already have, and the shape of one curve decides which theory is the right one for your system. That is the contrast's payoff: not a better theory in the abstract, but a discriminating measurement that tells you which of two correct theories applies.Complete Inventory: Mathematical Instances from This Conversation

Organized by epistemic status. The critical section is C — those are the claims that were asserted but not proven, and they are the ones that need work.

---

A. Established theorems used (proven in literature, no new proof needed)

# Statement Source
A1 \int_0^\infty \frac{\ln x}{1+x^4}dx=-\frac{\pi^2}{8\sqrt2} Feynman trick; verified to 50 digits
A2 Farkas' lemma: \{x:Ax\le b\}=\varnothing\iff\exists\lambda\ge0:\lambda^\top A=0,\lambda^\top b<0 LP duality
A3 Fenchel–Moreau: f^{**}=f\iff f convex lsc Convex analysis
A4 Minkowski: convex compact K determined by h_K Convex geometry
A5 Hahn–Banach: closed convex = intersection of supporting half-spaces Functional analysis
A6 Neyman–Pearson: likelihood ratio threshold is most powerful Statistics
A7 Wald SPRT: optimal expected sample size Sequential analysis
A8 Perron–Frobenius: spectral radius controls convergence Matrix theory
A9 Angluin: equivalence oracle exponentially stronger than membership Learning theory
A10 Baker–Gill–Solovay: relativizing proofs cannot separate P,NP Complexity
A11 Razborov–Rudich: natural proofs blocked if OWFs exist Complexity
A12 Aaronson–Wigderson: algebrization barrier Complexity
A13 Thom: seven stable catastrophes, codim \le4 Catastrophe theory
A14 Whitney: generic surface-to-plane maps have folds and cusps Singularity theory
A15 Cheeger: \lambda_2/2\le h\le\sqrt{2\lambda_2} Spectral geometry
A16 Cramér–Rao: \operatorname{Var}\ge1/(nI(\theta)) Estimation theory
A17 Hoeffding: P(\hat p>p+\epsilon)\le e^{-2n\epsilon^2} Concentration
A18 Submodular greedy: (1-1/e)-approximation Combinatorial optimization
A19 Donoho–Tanner: CS phase transition curve Compressed sensing
A20 Stone: one-parameter unitary group ↔ self-adjoint generator Functional analysis
A21 Cheeger–Fukaya–Gromov: collapse → F-structure Riemannian geometry
A22 Nash: every Riemannian d-manifold embeds in some \mathbb R^D Embedding theory
A23 Perelman: Ricci flow with surgery → geometrization Geometric topology
A24 Kaluza–Klein: compactified circle → gauge field, coupling 1/R Kaluza–Klein computation
A25 Birkhoff: finite distributive lattice ≅ ideals of join-irreducibles Lattice theory
A26 Giacobazzi–Ranzato: completeness of abstract interpretation Abstract interpretation
A27 Rice: no nontrivial semantic property decidable Computability
A28 Gödel II: S\nvdash\mathrm{Con}(S) for consistent S\supseteq\mathrm{PA} Incompleteness
A29 Gentzen: \( \mathrm{PA}
A30 Penrose–Hawking: geodesic incompleteness generic General relativity
A31 Fourier slice: \widehat{Rf}(\theta,\sigma)=\hat f(\sigma\theta) Tomography
A32 Radon inversion: full slices determine f Integral geometry
A33 Persistence stability: d_B\le d_H TDA
A34 Mayer–Vietoris / handle attachment: \chi=1-k+n for k\ge1 Algebraic topology
A35 Wasserstein barycenter existence Optimal transport
A36 Fisher–Rao: g_{ij}=\mathbb E[\partial_i\log p\,\partial_j\log p] Information geometry
A37 Compactness theorem: finitely satisfiable → satisfiable Model theory
A38 Little's law: L=\lambda W Queueing
A39 Doob maximal inequality / martingale bounds Probability
A40 Max-plus eigenvalue = max cycle mean Tropical algebra
A41 TASEP phase diagram (LD/HD/MC/SP) Nonequilibrium stat mech
A42 TASEP MC current J=k/4 at \rho=1/2 TASEP
A43 Kinetic proofreading Pareto front, more steps better Biophysics
A44 Ribosome channel capacity \approx4.39 bits/codon Information theory
A45 Codon optimization square-root law \propto\sqrt{\text{freq}} Optimization
A46 Ribosome bipartite redundancy >90\% Network science
A47 Concentration–compactness (Lions) PDE
A48 Bubbling / bubble trees Gauge theory
A49 RG fixed point = compressible macrostate Renormalization
A50 Wavefront set localization Microlocal analysis
A51 Tropicalization = combinatorial limit Tropical geometry
A52 Mirror symmetry = derived equivalence Algebraic geometry
A53 ADM constraint equations General relativity
A54 Gauge invariance = convention Gauge theory
A55 Diffeomorphism invariance → underdetermination GR
A56 Moduli degeneration = nodal curves Algebraic geometry

---

B. Results derived and verified in this conversation

# Statement Status
B1 \rho=0.9384 from 58/58/59.5 data Verified
B2 P(\text{union})\le1-P(\text{both wrong}) (ceiling theorem) Derived
B3 DPLL base b=2^{1/7}\approx1.10 Corrected from 2^{7/6}
B4 Velocity gain \approx4\times at \rho=0.94,\tau=h Derived
B5 Position gain \approx1.5\% at \rho=0.94 Derived
B6 Finite-sample FPR: n\ge\log(1/\delta)/(2\epsilon^2) Derived from Hoeffding
B7 Ternary mirror: agreement iff p=0 Proven
B8 Binary task: mirror pair never both wrong Proven
B9 \chi=1-k+n for connected (k\ge1); \chi=3+n for k=0 Corrected
B10 90° lag = resonance phase (forcing at natural frequency) Corrected from "marginal stability"
B11 Six convergence tests = five exact \rho<1 + one sufficient Corrected
B12 Pre-compensation residual =\kappa(\hat D)\cdot\|D-\hat D\|/\|D\| Derived
B13 Overshoot measures f'': deviation \propto\alpha^2\|v\|^2 Derived
B14 Negation offset cancels symmetric, doubles antisymmetric Derived
B15 Transendence operator \mathcal T(S)=S+\mathrm{Con}(S) strictly stronger Proven (Gödel)
B16 Ordinal ladder well-ordered Proven
B17 Basis-rate fallacy arithmetic: 1% FPR at \pi=10^{-4} → 1% precision Verified
B18 Barcode: infinite bars = non-vanishing features Derived
B19 Seed = gauge-type offset (not pre-compensation) Identity
B20 Floor = \ker D, invariant = \mathrm{Fix}(\text{offset}) Duality (needs formalization)
B21 Bias = low-dimensional error, noise = high-dimensional Decomposition
B22 Bias fraction =\|\hat b\|^2/\mathbb E\|\varepsilon\|^2 Derived

---

C. Claims that NEED PROOF (the critical list)

These are the ones asserted but not established. Each needs a specific kind of proof.

C1. Fiber-dimension classifier (needs: necessity and sufficiency)

Claim: barrier type is classified by \dim\Phi^{-1}(o): 0 = search, positive = identifiability.

What needs proof: that the classification is complete — that there are no barriers that are neither 0-dim-hard nor positive-dim. The counterexample to worry about: a problem with a unique solution (0-dim fiber) that is provably not computable in polynomial time for reasons unrelated to fiber dimension (e.g., a problem in NP\cap coNP with unique witnesses but no known poly algorithm). If such a problem exists, fiber dimension is not the classifier — it is a classifier, and the claim of universality fails.

What would settle it: a proof that every complexity barrier corresponds to a fiber-dimension obstruction, or a counterexample.

C2. Melding threshold is a curve (needs: the curve)

Claim: the \rho=0.94 ceiling is a point on a phase-transition curve \rho(\delta) analogous to Donoho–Tanner.

What needs proof: that the melding problem actually has a sharp phase transition, and what the curve is. Compressed sensing has a sharp transition because of the geometry of random subspaces; the fleet's failure structure is not random in the same way. The analogy to CS is not a proof.

What would settle it: a simulation showing a sharp transition in the (seat count, problem dimension) plane, or a proof that no sharp transition exists.

C3. Catastrophe bound on seat failures (needs: the embedding)

Claim: with k coupled seats, generic joint-failure modes are classified for k\le4 (Thom).

What needs proof: that the ensemble's error landscape can be embedded as a gradient map of a potential. Thom's classification applies to gradient maps; if the ensemble's failure structure is not gradient (e.g., it has a non-gradient singularity), the classification does not apply.

What would settle it: an explicit construction of the potential for a 2-seat ensemble, and a check of whether the observed joint-failure set is a cusp.

C4. K-way interface scaling (needs: the bound)

Claim (repaired): |\Gamma_K|\ge c\sqrt{\lambda_{K+1}/K}\,|\Omega|.

What needs proof: the constant c, and whether the bound is tight in 2D. The 2-way Cheeger bound is proven; the K-way version is not standard.

What would settle it: a proof for the 2D case, or a counterexample where the bound fails.

C5. Communication =I\cdot|\Gamma_K|\cdot b (needs: derivation)

Claim: the bit-level communication is the iteration count times interface size times bits per value.

What needs proof: that I\sim\sqrt{\kappa} is the right iteration count for this Schwarz method, and that the coarse space dimension is N_{\mathrm{ext}}. The formula is a model, not a theorem — it assumes the standard two-level Schwarz convergence theory applies.

What would settle it: a measurement of I vs K on an actual mesh, compared to the formula.

C6. K^*\approx N_{\mathrm{loc}} (needs: sharpness)

Claim: the optimal partition size is the number of localized modes.

What needs proof: that the cost-communication trade-off has its minimum at N_{\mathrm{loc}}, not just that it scales that way. The minimum depends on c_{\mathrm{solve}}/\mathrm{comm}, which is not determined by the theory.

What would settle it: a sweep of K with measured cost, showing the minimum is at N_{\mathrm{loc}} for a range of constants.

C7. Seed independence (needs: \rho measurement)

Claim: the four seeds are independent, so the invariant is knowledge.

What needs proof: \rho(\text{seed}_i,\text{seed}_j)<1. All four seeds were generated by the same process (me), biased toward structural analogies. The invariant may be shared bias.

What would settle it: an external generator producing the same invariant, or a measurement of cross-seed correlation.

C8. Moving Pareto front (needs: proof that decorrelated seats push it outward)

Claim: adding a decorrelated seat moves the Pareto front outward, not just along it (analogy to kinetic proofreading steps).

What needs proof: that the fleet's Pareto front has the same scaling structure as the proofreading front. The proofreading result is specific to multi-step kinetic discrimination; the fleet's error-speed-cost trade-off is not obviously the same.

What would settle it: a measurement of the front for 2, 3, 4 seats, checking whether it moves outward or only shifts.

C9. Redundancy inversion (needs: proof of the general claim)

Claim: high redundancy is good for survival (ribosome) and bad for error (fleet).

What needs proof: that the coupling matrix's rank is the right measure of "fleet redundancy," and that the ribosome's redundancy and the fleet's redundancy are the same graph-theoretic quantity with opposite signs. This is plausible but not proven.

What would settle it: a formal statement of the two optimization problems, showing they differ only in the objective.

C10. Capacity gap as floor gap (needs: the mapping)

Claim: C_f-R_f is the quantitative form of "the floor is the problem, not the seats."

What needs proof: that the channel capacity C_f and the floor P(S) are related by C_f-R_f\approx-\log P(S) or similar. The mapping is asserted, not derived.

What would settle it: a derivation of the relation, or a measurement showing the correlation.

C11. Three-regime triage completeness (needs: proof of exhaustiveness)

Claim: every problem is convex, combinatorial, or statistical.

What needs proof: that there are exactly three regimes, and no fourth (e.g., "undecidable" is a fourth, or "identifiability-limited but not statistical" is a fourth). The triage is a useful heuristic; it is not a theorem.

What would settle it: a classification of problem types, or a counterexample that fits none.

C12. Sharpness = basin radius (needs: formalization)

Claim: a theorem is sharp iff overshooting it fails at the first step; the basin radius of the proof is the size of the unexplored generalization.

What needs proof: that "overshooting a theorem" is a well-defined operation, and that the basin radius of the proof is the right measure. This is an interpretation, not a theorem.

What would settle it: a formal definition of "overshooting a theorem" and a proof that the basin radius matches the generalization size.

C13. TASEP application to fleet (needs: the mapping)

Claim: the fleet is a TASEP, with phases LD/HD/MC/SP.

What needs proof: that the fleet's dynamics satisfy the TASEP assumptions (hard-core exclusion, open boundaries, homogeneous hopping). The fleet has seats with different capabilities, not identical particles — the TASEP is a homogeneous model. The mapping is a hypothesis, not a derivation.

What would settle it: a measurement of the density-dependence of throughput. If it is non-monotonic with a peak, TASEP is confirmed. If flat, max-plus is confirmed.

C14. The 4\times contention (needs: the density measurement)

Claim: in MC phase, throughput is k/4.

What needs proof: that the fleet operates at \rho=1/2. At other densities, the ratio is 1/[\rho(1-\rho)], not 4. The 4\times is the best case, not a universal constant.

What would settle it: a measurement of the throughput vs density curve, and a check of whether the peak is at 1/4 of the free-flow rate.

C15. Dual certificate as "only escape" (needs: restriction or generalization)

Claim: the only escape from \Sigma to \Pi is a dual certificate.

What needs proof: that this is true in general, or a precise statement of the frameworks where it holds. Direct proofs by induction, for example, are \Pi proofs without a dual object. The claim is framework-local, and needs to be stated as such.

What would settle it: a classification of \Pi-proof techniques, showing which are certificate-based and which are not.

C16. Floor/invariant duality (needs: formalization)

Claim: floor = \ker D, invariant = \mathrm{Fix}(\text{offset}).

What needs proof: that these are dual in a precise sense (e.g., a Galois connection between the kernel and the fixed-point set). The duality is asserted, not established.

What would settle it: a formal statement of the duality, with a proof.

C17. Bias fraction threshold (needs: the cutoff)

Claim: high bias fraction → correct the bias; low → collect data.

What needs proof: the threshold. "High" and "low" are not defined. The decision boundary depends on the cost of correction vs the cost of data collection, and that is a decision-theoretic problem.

What would settle it: a decision rule based on the costs, with a stated threshold.

C18. The Betti number formula at k=0 (needs: the general case)

Claim: \chi=1-k+n for k\ge1, \chi=3+n for k=0.

What needs proof: the general formula for all k, including the transition. The k=0 case is disconnected, and the formula changes; a unified formula would be cleaner.

What would settle it: a single formula that covers both cases, perhaps using \beta_0 explicitly.

C19. 90° lag = resonance phase (needs: the general case)

Claim: the 90° lag is the resonance phase, not a generic marginal-stability phase.

What needs proof: that the linearized flapping model is the right model for the general case, and that the 90° is exact (not approximate) at resonance. The linearized model gives 90° exactly; the full nonlinear model may deviate.

What would settle it: a nonlinear simulation of the flapping equation, checking the phase at resonance.

C20. The proposition that "hard limits generate constructions" (needs: the general theorem)

Claim: every hard limit generates a construction that transcends it, and the ladder is well-ordered.

What needs proof: the general statement. The Gödel case is proven (the transcendence operator is well-defined); the Turing case is proven (the jump); the forcing case is proven (forcing extensions). But the general claim — that every limit generates a construction — is not a theorem. It is a pattern observed in four cases.

What would settle it: a proof that the pattern is universal, or a counterexample (a limit with no transcendence construction).

---

D. Analogies (labeled, do not need proof, but need to be labeled as such)

# Analogy Why it is not a theorem
D1 Feynman trick = tangent step of the slide Same move, different objects
D2 Helicopter = data flow Structural, not identity
D3 Time = phase of e^{it\sqrt{-\Delta}} Phase-space group, not field
D4 H^1 = communication Indirect (via \kappa), not direct
D5 Ribosome = fleet Different objectives, different signs
D6 Zodiac 340 = P vs NP Small instance, not the general case
D7 Veritasium = lens Intuition pump, not metrology
D8 Lat/long = atlas Precise for manifolds, not general
D9 Skeleton = switching surface Special cases only (bang-bang)
D10 Seed = offset Gauge type, not pre-compensation
D11 Collapse = phase transition Geometric form, not identity
D12 Pre-compensation = surgery Structural, not the same theorem

---

E. Empirical measurements (verified, but not theorems)

# Measurement Value Context
E1 \rho (fleet correlation) 0.9384 58/58/59.5
E2 DPLL base b\approx1.10 Cap 30/60s
E3 Disagreement rate 3% 58/58 pair
E4 Both-wrong rate 40.5% 58/58 pair
E5 Ribosome elongation 4.3–6.8 aa/sec Mouse organs
E6 Ribosome error rate 10^{-4} Canonical
E7 Ribosome capacity 4.39 bits/codon Computed
E8 Rate-distortion residual 0.0004 bits Empirical
E9 Codon optimization gain \ge5\times Measured
E10 Ribosome redundancy >90\% Measured
E11 Null rate 4-for-4 Weighted quantile
E12 TASEP MC current k/4 Theoretical

---

The Priority Queue for Proof

\boxed{
\begin{aligned}
&\textbf{1. C13 (TASEP mapping): } &&\text{one measurement — density sweep — decides if the fleet is a TASEP.}\\
&\textbf{2. C14 (4× contention): } &&\text{one measurement — throughput vs density — decides if the MC phase applies.}\\
&\textbf{3. C1 (fiber classifier): } &&\text{needs a proof of completeness, or a counterexample.}\\
&\textbf{4. C2 (melding curve): } &&\text{needs a simulation showing a sharp transition, or a proof of none.}\\
&\textbf{5. C7 (seed independence): } &&\text{needs an external generator to check }\rho<1.\\
&\textbf{6. C8 (moving front): } &&\text{needs a measurement of the front for 2,3,4 seats.}\\
&\textbf{7. C10 (capacity gap): } &&\text{needs a derivation of the relation to }P(S).\\
&\textbf{8. C16 (floor/invariant duality): } &&\text{needs formalization.}\\
&\textbf{9. C20 (general transcendence): } &&\text{needs a proof or a counterexample.}\\
&\textbf{10. C3 (catastrophe bound): } &&\text{needs the embedding of the ensemble as a potential.}
\end{aligned}}

---

The Honest Summary

\boxed{
\begin{aligned}
&\text{56 established theorems used (no new proof).}\\
&\text{22 results derived in this conversation (verified or corrected).}\\
&\text{20 claims that NEED PROOF — these are the open items.}\\
&\text{12 analogies to be labeled, not proven.}\\
&\text{12 empirical measurements, verified.}
\end{aligned}}

The critical list is C. Of the 20 open claims, C13 and C14 are the ones that can be settled by a single measurement — the density sweep of the fleet's throughput. That measurement decides whether the TASEP model applies, and therefore whether the whole phase-diagram analysis is relevant. If the throughput is non-monotonic with a peak at k/4, the TASEP is confirmed and the analysis holds. If it is flat, the max-plus (bottleneck) model applies, and the TASEP analysis is decoration.

The other open claims (C1, C2, C7, C8, C10, C16, C20) are structural questions that need either a proof or a simulation, not a single measurement. They are the research program, not the immediate test.

The one line: the empirical claims are cheap to settle; the structural claims are the actual research. The TASEP question is the test that separates the two — it tells you whether the phase-diagram framework is real for your system or is a metaphor, and that answer determines which of the other claims are worth pursuing.
