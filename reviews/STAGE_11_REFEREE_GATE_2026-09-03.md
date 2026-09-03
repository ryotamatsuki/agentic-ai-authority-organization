# Stage 11 — Robustness / Referee Attack Gate

Review date: 2026-09-03

Canonical manuscript HEAD: `8334d857e70c8b7495a15cd33121e3bf169625ed`

Canonical workflow: `ryotamatsuki/research-paper-workflow`, v1.1, `templates/STAGE_11_REFEREE_GATE.md`

Working title: *External Agentic-AI Platforms, Retained Human Recovery Capability, and the Allocation of Authority*

Working target carried into this gate: Review of Industrial Organization (RIO). This target is not treated as fixed; Stage 12 remains blocked unless Stage 11 survives.

## 1. Executive referee-gate verdict

**Verdict: REOPEN EARLIER STAGE / NO-GO for submission preparation.**

The manuscript is mathematically coherent at its core and materially stronger than its earlier JITE-oriented draft, but it does not yet survive the workflow's hostile novelty/mechanism kill test. The newly re-opened literature reveals a dense cluster of close models in dynamic outsourcing/concurrent sourcing and 2025–2026 AI-learning theory. The current paper must demonstrate that its headline mechanism and theorem are not absorbed by these literatures.

The main blocking issue is not a proof failure. It is that the model is currently a single-firm dynamic delegation/outsourcing problem in which: (i) external delegation provides a current cost/performance advantage; (ii) internal production/authority preserves future capability through learning/experience; (iii) external supply may become unavailable; and (iv) the supplier price exceeds resource cost. Each of these mechanisms, including partial outsourcing despite a current internal cost disadvantage, has close antecedents. The current `agentic` element `n` changes success probabilities and multiplies the per-step price wedge, but does not yet create an independently established strategic feedback.

Submission should therefore pause and the project should return first to **Stage 6 Novelty Re-Kill**. If a proposition-level distinction survives a full absorption test, the paper may return to Stage 11 after bounded mathematical/exposition repairs. If no such distinction survives, the project must return to Stage 3/4 for a narrow mechanism pivot rather than relabeling the existing result.

## 2. Referee A — Novelty / mechanism

### Attack A1 — Classic dynamic outsourcing result under AI labels

- **Severity:** FATAL
- **Evidence:** Anderson and Parker (2002), *The Effect of Learning on the Make/Buy Decision*, derive a path-dependent outsourcing trap and conditions under which partial outsourcing dominates complete insourcing or outsourcing. Gray, Tomlin, and Roth (2009), *Outsourcing to a Powerful Contract Manufacturer: The Effect of Learning-by-Doing*, use a two-period game and show that partial outsourcing can be optimal and that the OEM may produce internally even at a cost disadvantage because present outsourcing changes future learning/costs. These results are structurally close to the manuscript's Proposition 2.
- **Current response:** The manuscript does not cite or distinguish this literature.
- **Required fix:** Reopen Stage 6 and conduct a whole-game/proposition absorption matrix against Anderson–Parker and Gray–Tomlin–Roth. State precisely what theorem in the current model cannot be obtained by relabeling internal production as human authority and outsourcing as AI delegation.
- **Does the fix reopen theory?:** YES if no theorem-level distinction survives; otherwise literature/contribution-set repair only.
- **Resolved?:** NO.

### Attack A2 — Concurrent sourcing under disruption already provides the fallback logic

- **Severity:** FATAL
- **Evidence:** Cassidey, Freeman, and Melouk (2022), *Leveraging concurrent sourcing for risk mitigation and pricing*, study make-and-buy under supply disruption and show that in-house production capability affects sourcing and supplier pricing. This is institutionally close to retaining internal human capability when an external platform becomes unavailable.
- **Current response:** Not cited. The present model endogenizes capability erosion through the retained human share, which is a distinction, but the manuscript has not shown that this distinction generates a theorem unavailable in the concurrent-sourcing literature.
- **Required fix:** Stage 6 absorption test. Separate (a) known risk-mitigation value of internal capacity from (b) any genuinely new endogenous capability-depletion result.
- **Does the fix reopen theory?:** Potentially YES.
- **Resolved?:** NO.

### Attack A3 — Recent AI-learning literature is closer than the cited AI literature

- **Severity:** FATAL
- **Evidence:** Garicano and Rayo (2025) model AI automation of apprentice tasks and the viability of human training; Afrouzi, Blanco, Drenik, and Hurst (2026) make the share of automated tasks jointly determine learning-by-doing and human capital; Ide (2026) studies entry-level automation and tacit-knowledge transmission; Acemoglu, Kong, and Ozdaglar (2026) show agentic AI can improve current decisions while eroding human learning incentives; Srivastava (2026) directly studies human control, full AI autonomy, and hybrid governance.
- **Current response:** None of these frontier papers appears in the current bibliography.
- **Required fix:** Proposition-level Stage 6 re-search and closest-paper matrix. The paper must not claim novelty from `AI delegation reduces future human capability` alone.
- **Does the fix reopen theory?:** Potentially YES.
- **Resolved?:** NO.

### Attack A4 — No-new-mechanism / ingredient-combination attack

- **Severity:** FATAL
- **Evidence:** The external platform does not choose price or availability; `p`, `nu`, and `kappa` are parameters. The firm is the only strategic decision-maker. Recovery capability is mechanically decreasing in delegated mass through `H(s)=Hbar+beta(1-s)`. The agentic horizon `n` enters success and per-step payment but has no strategic platform feedback.
- **Current response:** The paper claims that the combination of external agentic AI, recovery capability, and platform pricing is new.
- **Required fix:** Identify a proposition generated by the joint architecture that cannot arise in nested models containing (i) dynamic outsourcing/learning, (ii) concurrent sourcing/disruption, or (iii) AI-learning/capability erosion. If none exists, reopen Stage 3/4.
- **Does the fix reopen theory?:** YES if current theorem set is absorbed.
- **Resolved?:** NO.

## 3. Referee B — Assumptions / mathematics

### Attack B1 — Recovery-capability law is result-producing

- **Severity:** MAJOR BUT FIXABLE
- **Evidence:** `H(s)=Hbar+beta(1-s)` directly maps retained human task mass into future capability, while `rho''<0` makes the marginal value of capability rise as capability is depleted. This creates the crossing structure behind hybrid authority.
- **Current response:** Section 3.2 now interprets `H` clearly as a recovery-relevant experience stock, which materially improves coherence, but no robustness result shows that linear accumulation is nonessential.
- **Required fix:** Either state and prove the minimum general conditions on `H(s)` and `rho(H)` needed for Propositions 1–2, or provide one disciplined alternative microfoundation/robustness check. Do not add multiple extensions.
- **Does the fix reopen theory?:** YES for a theorem-level generalization; NO if limited to a carefully defended assumption with external evidence.
- **Resolved?:** NO.

### Attack B2 — Parameter-domain inconsistency in Proposition 4

- **Severity:** MAJOR BUT FIXABLE
- **Evidence:** Section 3 assumes `0 < kappa-alpha < kappa < 1`, but Proposition 4 evaluates `Delta^P(1-epsilon;1,p)` and allows `K subset (alpha,1]`. Thus the sufficient condition is stated at a capability value excluded by the model's own primitive restriction.
- **Current response:** None.
- **Required fix:** Either change the primitive restriction to permit `kappa=1` (for example `0<kappa-alpha<kappa<=1`, checking all downstream statements), or define a maximal admissible `kappa_bar<1` and formulate the uniform-persistence condition at `kappa_bar`.
- **Does the fix reopen theory?:** NO if handled as a consistent domain repair.
- **Resolved?:** NO.

### Attack B3 — Notation error in core payoff definitions

- **Severity:** MINOR
- **Evidence:** The manuscript defines `\nu_A^P` and `\nu_H`, then defines `Delta^P` using `\nu_A^P-u_H`; `u_H` is therefore undefined as written.
- **Required fix:** Use `u_A^P` and `u_H` consistently.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** NO.

### Attack B4 — Longer horizon does not imply a monotonically larger cutoff distortion

- **Severity:** MAJOR BUT FIXABLE
- **Evidence:** Proposition 3 proves `Delta^T-Delta^P=n(p-r)` and `Phi^T-Phi^P=sn(p-r)`. These identities prove that the price/objective wedge rises with `n`; they do **not** prove that the organizational cutoff gap `s_T^*-s_P^*` rises with `n`, because `n` simultaneously changes AI success and the slopes of both FOCs. A numerical counterexample with a valid concave recovery technology `rho(H)=1-exp(-gamma H)` yields cutoff gaps for `n=1,2,3,4` of approximately `0.0461, 0.0651, 0.0696, 0.06925`: the gap falls from 3 to 4 even though `n(p-r)` rises.
- **Current response:** The manuscript repeatedly says the organizational distortion is stronger in longer-horizon environments.
- **Required fix:** Narrow the claim everywhere to the proven statement: the per-task and objective pricing wedges scale linearly with `n`. If the paper wants monotonicity of `s_T^*-s_P^*`, derive additional sufficient conditions and re-run theory gates.
- **Does the fix reopen theory?:** NO for claim narrowing; YES for a new cutoff-gap theorem.
- **Resolved?:** NO.

### Attack B5 — Corners/adoption

- **Severity:** MINOR / largely resolved
- **Evidence:** Proposition 1 explicitly handles boundary derivatives, Proposition 2 rules out full automation under a boundary condition, and the fixed adoption cost is cleanly separated from the conditional authority problem.
- **Required fix:** No new extension. After the `kappa` domain repair, verify all endpoint conditions once more.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** YES except for B2.

### Attack B6 — Numerical-not-proof

- **Severity:** MINOR / resolved
- **Evidence:** Main propositions have analytic proofs. No numerical pattern is used as proof.
- **Required fix:** Add reproducible symbolic/numerical verification scripts to the repository, as Stage 9 recommends, but this is a reproducibility improvement rather than a theorem repair.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** YES on substantive validity.

## 4. Referee C — Welfare / institution / generality

### Attack C1 — `Technological benchmark` is not yet a welfare benchmark

- **Severity:** MAJOR BUT FIXABLE
- **Evidence:** The benchmark replaces platform price `p` by resource cost `r` but does not model platform profits, consumer surplus, or a social planner. The manuscript correctly states this limitation in Section 3, yet later uses language such as `organizational distortion`, `technologically efficient`, and `delegate too little` that can sound normative.
- **Current response:** Partial: the paper explicitly says the technological benchmark is not a full social planner problem.
- **Required fix:** Either consistently call it a `resource-cost / integrated technological benchmark` and remove welfare-loaded language, or reopen Stage 7 and derive a genuine welfare benchmark including the platform side.
- **Does the fix reopen theory?:** NO for relabeling; YES for welfare theory.
- **Resolved?:** NO.

### Attack C2 — Institutional primitive lacks direct validation

- **Severity:** MAJOR BUT FIXABLE
- **Evidence:** The manuscript gives a plausible interpretation of recovery capability but supplies no primary or close institutional evidence that external AI delegation erodes the firm's ability to override/recover when the platform is unavailable. The closest support is currently conceptual.
- **Current response:** The experience-stock wording is coherent but not empirically/institutionally validated.
- **Required fix:** Add a bounded institutional bridge using credible evidence on AI dependence/skill atrophy and, importantly, the established concurrent-sourcing/back-sourcing literature on preserved in-house capability. Label evidence as suggestive rather than causal proof.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** NO.

### Attack C3 — External validity creates a novelty problem

- **Severity:** MAJOR BUT FIXABLE, linked to A1–A4
- **Evidence:** The mechanism applies almost verbatim to outsourcing a non-AI supplier: external execution gives a current advantage, internal activity preserves experience, and external supply can fail. Generality is real, but it weakens the claim that `agentic AI` creates a distinct theory.
- **Current response:** Discussion itself proposes make-or-buy and firm-boundary applications, implicitly acknowledging the broader sourcing interpretation.
- **Required fix:** The paper must distinguish `general mechanism applied to AI` from `AI-specific mechanism`. If it is the former, novelty must be established against sourcing theory and claims rewritten accordingly.
- **Does the fix reopen theory?:** Potentially YES if the current contribution collapses to an application.
- **Resolved?:** NO.

### Attack C4 — Separate lambda and nu have no independent structural role

- **Severity:** MINOR
- **Evidence:** In all payoffs they enter only through the product `lambda*nu`; comparative statics with respect to either are therefore mechanically identical.
- **Required fix:** Either define the composite contingency-unavailability probability directly, or explain why the decomposition is institutionally useful while acknowledging that only the product matters in the baseline.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** NO.

## 5. Referee D — Journal / exposition

### Attack D1 — RIO fit is plausible but currently fragile

- **Severity:** MAJOR BUT FIXABLE only if novelty survives
- **Evidence:** RIO is broad enough to include internal organization, but its center of gravity remains industrial organization, competition, market structure, and policy. The current platform price is exogenous and there is no strategic platform-side behavior. The paper therefore needs either a genuinely significant organization/IO theorem or a different journal audience.
- **Current response:** Repository notes currently rank RIO first as a pragmatic target.
- **Required fix:** Do not choose the journal until Stage 6 resolves the surviving contribution. Stage 12 must select the outlet for the actual surviving mechanism, not retrofit the model to RIO.
- **Does the fix reopen theory?:** NO at Stage 12; YES only if one tries to add platform strategy to chase RIO, which is prohibited without reopening earlier stages.
- **Resolved?:** NO.

### Attack D2 — Manuscript still contains explicit JITE-targeting prose

- **Severity:** MAJOR BUT FIXABLE for submission readiness
- **Evidence:** Introduction says `the paper speaks to a JITE-style question`; Related Literature says the questions have `recently become salient in JITE`.
- **Required fix:** Remove journal-targeting meta-prose and describe the substantive institutional/organizational question directly. Do this regardless of eventual target.
- **Does the fix reopen theory?:** NO.
- **Resolved?:** NO.

### Attack D3 — Novelty claim is too strong relative to the actual literature search

- **Severity:** MAJOR BUT FIXABLE only if Stage 6 survives
- **Evidence:** Related Literature states that existing work has not provided a comparably simple theory jointly linking external agentic AI, recovery capability, and pricing distortion, but the current bibliography omits the closest sourcing and 2025–2026 AI-learning work.
- **Required fix:** Delete or sharply qualify the claim until a Stage 6 proposition-level novelty audit supports it.
- **Does the fix reopen theory?:** NO for wording; potentially YES if novelty fails.
- **Resolved?:** NO.

## 6. Consolidated severity table

| Attack | Severity | Status | Required route |
|---|---|---|---|
| Classic dynamic outsourcing absorption | FATAL | Unresolved | Stage 6 Re-Kill |
| Concurrent sourcing / disruption absorption | FATAL | Unresolved | Stage 6 Re-Kill |
| Recent AI-learning prior art | FATAL | Unresolved | Stage 6 Re-Kill |
| No independently established new mechanism | FATAL | Unresolved | Stage 6; possibly Stage 3/4 |
| Linear recovery stock / concavity built-in | MAJOR BUT FIXABLE | Unresolved | bounded robustness / assumption defense |
| `kappa=1` domain inconsistency | MAJOR BUT FIXABLE | Unresolved | direct math repair |
| `nu_A` / `u_H` notation inconsistency | MINOR | Unresolved | direct edit |
| Longer-`n` cutoff-distortion overclaim | MAJOR BUT FIXABLE | Unresolved | claim narrowing or new theorem |
| Corner/adoption logic | MINOR | Largely resolved | verify after domain repair |
| Numerical-not-proof | MINOR | Resolved | optional reproducibility scripts |
| Technological benchmark vs welfare language | MAJOR BUT FIXABLE | Unresolved | relabel or reopen Stage 7 |
| Institutional validation of recovery stock | MAJOR BUT FIXABLE | Unresolved | evidence bridge |
| Generality vs AI-specific novelty | MAJOR BUT FIXABLE / tied to fatal novelty gate | Unresolved | Stage 6 |
| `lambda` and `nu` only through product | MINOR | Unresolved | simplify/explain |
| RIO contribution fit | MAJOR BUT FIXABLE if novelty survives | Unresolved | Stage 12 after Stage 11 |
| JITE-targeting prose remains | MAJOR BUT FIXABLE | Unresolved | direct edit |
| Inflated novelty statement | MAJOR BUT FIXABLE | Unresolved | Stage 6 then rewrite |

## 7. Required fixes, ordered

1. **Reopen Stage 6 Novelty Re-Kill before any journal submission.** Build a whole-game/proposition matrix against Anderson–Parker (2002), Gray–Tomlin–Roth (2009), Cassidey–Freeman–Melouk (2022), Loertscher–Riordan (2019), Garicano–Rayo (2025), Afrouzi–Blanco–Drenik–Hurst (2026), Ide (2026), Acemoglu–Kong–Ozdaglar (2026), Itoh–Morita (2026), and Srivastava (2026).
2. If a distinct theorem survives, fix the `kappa` parameter domain and the `u_A/u_H` notation.
3. Narrow Proposition 3 and all abstract/introduction/discussion/conclusion language so that longer `n` is claimed to increase the **pricing wedge**, not necessarily the cutoff gap.
4. Clarify whether `p-r` comparison is purely a resource-cost benchmark or a welfare result. Avoid `too little`/`efficient` language unless welfare is modeled.
5. Add one bounded robustness/defense for the recovery-experience technology.
6. Add institutional support for capability retention/depletion and external-provider disruption.
7. Remove explicit `JITE-style` / `salient in JITE` wording and rewrite the literature section around the actual closest papers.
8. Add symbolic/numerical verification scripts and a deterministic build gate before the next Stage 11 pass.

## 8. Theory-change implications

- Items 2, 3 (if claim narrowing only), 4 (if relabeling only), 6, and 7 do **not** require substantive theory reopening.
- A general `H(s)` robustness theorem or a genuine welfare benchmark reopens the relevant theory/Stage 7 gate.
- If Stage 6 finds that the current theorem set is absorbed by dynamic sourcing/AI-learning theory, the project must return to Stage 3/4. A journal-specific extension is not an allowed substitute for a new mechanism.

## 9. Resolved versus unresolved attacks

### Resolved / substantially answered

- Basic FOC/SOC and strict-concavity logic.
- Proposition 2's task-by-task AI-dominance statement is mathematically valid under its conditions.
- Proposition 4's IFT sign and uniform-persistence proof are logically valid once the `kappa` domain is repaired.
- Fixed adoption cost is correctly separated from the conditional authority margin.
- The recovery primitive is much better defined than in the earlier draft.
- Main results are analytic rather than numerical.

### Unresolved and blocking

- Whole-game/proposition-level novelty against dynamic outsourcing, concurrent sourcing, and the new AI-learning frontier.
- Whether agentic execution creates a new mechanism rather than only a new parameterization.
- `kappa=1` domain inconsistency.
- Overstatement of the longer-horizon organizational distortion result.
- Normative interpretation of the technological benchmark.
- Institutional validation and current-journal positioning.

## 10. Verdict and next-stage contract

**Canonical Stage 11 verdict: `REOPEN EARLIER STAGE / NO-GO`.**

**Route:** Stage 6 — Proposition-Level Novelty Re-Kill.

**Contract:** Freeze the current model while conducting the re-kill. Do not add endogenous pricing, bargaining, multiple platforms, labor-market structure, or extra state variables during the novelty audit. The sole question is whether at least one economically material proposition survives whole-game absorption by the closest sourcing and AI-learning literatures. If yes, return to bounded hardening/repair and repeat Stage 11. If no, terminate the current architecture or authorize exactly one new mechanism through Stage 3/4. Stage 12 Journal Positioning is blocked until the fatal novelty attacks are resolved.
