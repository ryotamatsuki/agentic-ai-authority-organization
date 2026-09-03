# Stage 6R — Proposition-Level Novelty Re-Kill

Review date: 2026-09-03

Repository: `ryotamatsuki/agentic-ai-authority-organization`

Canonical workflow: `ryotamatsuki/research-paper-workflow` v1.1, release `488e5ab06c207909296a7564eaf9066f7f94319c`

Canonical template: `templates/STAGE_06_NOVELTY_REKILL.md`

Main branch HEAD at stage start: `ec356854fc039d5b6354133ed6fd1eff85b71650`

Canonical manuscript HEAD frozen for this gate: `8334d857e70c8b7495a15cd33121e3bf169625ed`

Working branch: `stage6/novelty-rekill`

## 1. Executive verdict

**Canonical Stage 6 verdict: NO-GO.**

The current model is not exact prior art as a complete game: no single located paper simultaneously contains endogenous current outsourcing/delegation, endogenous future internal capability, all-or-nothing external-supply failure, a private supplier/platform-price versus resource-cost wedge, and multi-step execution. Under the workflow, however, absence of a single exact predecessor is not enough. The full architecture must generate at least one theorem that is unavailable in the close nested literatures.

That test fails. The headline results decompose into already-known or mechanically implied results:

1. Partial external sourcing / hybrid organization is well established in outsourcing and agentic-AI delegation models.
2. Retaining internal production despite a current cost disadvantage because current outsourcing changes future learning/capability is directly established in the dynamic outsourcing literature.
3. Retaining internal capability to mitigate an all-or-nothing external supply disruption is established in concurrent-sourcing models.
4. AI automation reducing learning, human capital, training pipelines, or knowledge accumulation is an active 2025–2026 theory frontier.
5. The current platform-price result is a direct consequence of replacing the private per-step price `p` by resource cost `r`; the exact objective gap is an accounting identity.
6. The agentic horizon `n` is an amplifier/scaling parameter, not a new strategic margin. Setting `n=1` leaves the core P1–P4 logic intact.
7. Proposition 4's uniform-persistence statement is a valid sharpening inside the present model, but economically it follows from monotonicity plus a boundary condition at maximal capability; it does not create a new interaction that separates the paper from the close automation-learning and dynamic-outsourcing literatures.

Accordingly, the paper currently has **combination novelty without a surviving full-model-only theorem**. That does not satisfy Stage 6 v1.1.

## 2. Current contribution reconstructed without paper rhetoric

Strip away the AI labels. A firm chooses what share of activities to source externally rather than keep internal. External sourcing yields a current cost/performance advantage, but a larger outsourced share lowers a future internal capability stock that is valuable when the external supplier cannot be relied upon. The firm therefore may retain internal activity despite its current disadvantage. A supplier-price markup shifts the sourcing cutoff toward internal activity; better external technology shifts it toward external sourcing. If the future value of internal capability remains sufficiently high even at the maximum technology level, a positive internal share persists.

This is an economically coherent model. The novelty problem is that each substantive mechanism in that stripped description is already represented in close literatures, and their combination in the present objective is additively separable rather than strategically interactive.

## 3. Closest literature frontier

The strongest verified threats are:

- Edward G. Anderson Jr. and Geoffrey G. Parker (2002), **The Effect of Learning on the Make/Buy Decision**, *Production and Operations Management* 11(3):313–339, DOI `10.1111/j.1937-5956.2002.tb00189.x`. The paper shows path-dependent outsourcing effects and conditions under which a small amount of outsourcing can dominate both complete insourcing and complete outsourcing.
- John V. Gray, Brian Tomlin, and Aleda V. Roth (2009), **Outsourcing to a Powerful Contract Manufacturer: The Effect of Learning-by-Doing**, *Production and Operations Management* 18(5):487–505, DOI `10.1111/j.1937-5956.2009.01024.x`. A two-period game; partial outsourcing can be optimal, and the OEM may produce internally even when it has a current cost disadvantage because outsourcing affects learning and future costs.
- Thomas B. Cassidey, Nickolas Freeman, and Sharif Melouk (2022), **Leveraging concurrent sourcing for risk mitigation and pricing**, *Omega* 113:102723, DOI `10.1016/j.omega.2022.102723`. A manufacturer may make and buy under all-or-nothing outsourced-supply disruption; in-house capability mitigates risk and affects supplier pricing.
- Simon Loertscher and Michael H. Riordan (2019), **Make and Buy: Outsourcing, Vertical Integration, and Cost Reduction**, *American Economic Journal: Microeconomics* 11(1):105–123, DOI `10.1257/mic.20160347`. Integration provides an internal-sourcing option that avoids supplier markups but changes supplier cost-reduction incentives.
- Luis Garicano and Luis Rayo (2025; revised 2026), **Training in the Age of AI: A Theory of Career Viability**, CEPR DP20634. AI automation of junior work threatens the training/career pipeline; the current CEPR record was revised 2 March 2026.
- Hassan Afrouzi, Andres/Andrés Blanco, Andres Drenik, and Erik Hurst (2026), **Automation, Learning, and Career Dynamics**, NBER Working Paper 35157 / FRB Atlanta Working Paper 2026-6. Learning-by-doing and the share of automated tasks are jointly determined; cheap automation can create a human-capital trap.
- Enrique Ide (2025; revised June 2026), **Automation, AI, and the Intergenerational Transmission of Knowledge**, CEPR DP20940 / IESE working paper. Automation can raise current output while weakening tacit-knowledge transmission and long-run growth.
- Daron Acemoglu, Dingwen Kong, and Asuman Ozdaglar (2026), **AI, Human Cognition and Knowledge Collapse**, NBER Working Paper 34910. Agentic AI can improve current decisions while eroding human learning incentives and the long-run stock of knowledge.
- Hideshi Itoh and Kimiyuki Morita (2026), **The Allocation of Decision Authority in Three-stage Decision Processes with Applications to Artificial Intelligence in Organizations**, SSRN `6440458`. Directly concerns formal authority allocation with AI applications, but not the present dynamic recovery-capability mechanism.
- Abhishek Srivastava (2026), **Governing AI-enabled decision making: Delegation, autonomy, and control**, *Production and Operations Management*, OnlineFirst, DOI `10.1177/10591478261473004`. The model directly compares human control, full AI autonomy, and human-in-the-loop governance and shows partial delegation can strictly dominate the extremes.

Detailed bibliographic and access records are in `LITERATURE_LEDGER.md`.

## 4. Whole-game absorption verdict

**No single exact predecessor located.** Therefore the current paper is not classified as `EXACT PRIOR ART` at the whole-game level.

Nevertheless, the full game fails the workflow's interaction-result test. Reconstructing the current architecture requires at least three close strands:

- dynamic outsourcing with learning/capability accumulation (Anderson–Parker; Gray–Tomlin–Roth),
- concurrent sourcing under supplier disruption and pricing (Cassidey–Freeman–Melouk; related sourcing-risk literature),
- AI automation with endogenous human learning/knowledge (Garicano–Rayo; Afrouzi et al.; Ide; Acemoglu–Kong–Ozdaglar).

The key question is therefore whether combining these margins generates a theorem that disappears in every nested benchmark. It does not.

The continuation term enters the private objective additively as `lambda * nu * R * rho(H(s))`. Supplier unavailability therefore scales the marginal value of the same internal capability-preservation margin that already creates partial insourcing/retention. Platform pricing enters separately as the constant per-step wedge `n(p-r)`. There is no best-response loop between supplier behavior and capability retention, no endogenous outage probability, no price-risk-capability interaction, and no strategic platform response.

Thus the full architecture is **not exactly absorbed by one prior model, but its current theorems are economically redundant with close benchmark results**.

## 5. Proposition-by-proposition verdict

### Proposition 1 — unique cutoff / hybrid organization

**Prior-art classification: STRUCTURALLY VERY CLOSE.**  
**Kill decision: KILL AS CONTRIBUTION; retain only as model characterization.**

A monotone task advantage plus a concave future-capability term naturally generates a cutoff. Hybrid sourcing itself is old in Anderson–Parker and Gray–Tomlin–Roth, and hybrid human/AI governance is explicitly obtained by Srivastava (2026). The exact task ordering by exceptionality is a convenient implementation, not an independent contribution.

### Proposition 2 — full automation can be suboptimal despite static AI dominance

**Prior-art classification: STRUCTURALLY VERY CLOSE / immediate economic analogue.**  
**Kill decision: KILL AS MAIN CONTRIBUTION.**

Gray–Tomlin–Roth explicitly report that the OEM may produce internally when it is at a cost disadvantage because current outsourcing affects learning and future costs. Anderson–Parker show that current outsourcing benefits can create unfavorable long-run learning consequences and that partial outsourcing may dominate the extremes. Cassidey–Freeman–Melouk establish the value of in-house capability under all-or-nothing outsourced-supply disruption. The current Proposition 2 combines the learning/capability argument with outage risk, but the combination adds no new sign reversal, ordering, or equilibrium interaction: outage risk multiplies the future value of retained capability.

### Proposition 3 — platform-price organizational wedge

**Prior-art classification: MECHANICAL / COMPONENT OVERLAP.**  
**Kill decision: KILL AS MAIN THEOREM; at most retain as accounting implication.**

The model defines the technological benchmark by replacing `p` with `r`. Therefore

`Delta^T - Delta^P = n(p-r)`

and

`Phi^T - Phi^P = s n(p-r)`

are identities. The direction `s_P* < s_T*` follows from strict monotonicity of the same marginal condition. Loertscher–Riordan already place supplier markups and internal sourcing at the center of make-and-buy theory, while Cassidey et al. study the relation between internal capability and supplier pricing. The current model does not endogenize pricing, so the result is not a new strategic pricing theorem.

The claim that the *cutoff distortion* must grow in `n` is not established. A separate numerical sanity check using an admissible concave recovery technology found interior examples where the cutoff gap rises from `n=2` to `n=3` and then falls from `n=3` to `n=4`. What is globally valid is only that the direct price/objective wedge scales with `n`.

### Proposition 4 — better AI expands delegation but a positive human share persists uniformly

**Prior-art classification: STRUCTURALLY VERY CLOSE / mathematical sharpening without a new mechanism.**  
**Kill decision: KILL AS MAIN CONTRIBUTION.**

The comparative static `ds*/dkappa > 0` is standard monotone comparative statics in the present one-dimensional concave problem. The uniform-persistence part is logically valid after correcting the domain inconsistency noted below, but it is obtained by checking a sufficient boundary inequality at the maximal capability and then using monotonicity. The underlying economics—automation improves current performance while reducing human learning/capability, so a positive human role may remain—is already central to the 2025–2026 AI-learning literature. The exact epsilon statement was not found verbatim, but Stage 6 does not treat different notation or a boundary restatement of a known trade-off as independent novelty.

## 6. Agentic-`n` hard kill

**Verdict: AMPLIFIER / SCALING PARAMETER, not a core mechanism.**

- With `n=1`, P1 still has the same cutoff structure.
- With `n=1`, P2 still allows partial human retention despite static external advantage.
- With `n=1`, P3 still yields the price-resource-cost wedge `p-r` and the same direction of cutoff distortion.
- With `n=1`, P4 still yields `ds*/dkappa>0` and the same boundary-based persistence logic.

Thus the headline economics does not require multi-step execution. `n` lowers success through `(kappa-alpha z)^n` and scales total usage payments, but it creates no new player, strategy, feedback loop, threshold ordering, or sign reversal.

## 7. Recovery-capability absorption verdict

The interpretation of `H(s)=Hbar+beta(1-s)` as a recovery-relevant experience stock is coherent and much sharper than the earlier generic fallback-capability wording. It is not, however, a novel economic primitive. After label stripping, it is a reduced-form learning/capability-retention law: keeping more activity internal preserves future productive or fallback capability.

The closest mappings are:

- learning-by-doing / future internal cost: Anderson–Parker; Gray–Tomlin–Roth,
- endogenous human capital/knowledge from performed tasks: Afrouzi et al.; Ide; Acemoglu–Kong–Ozdaglar,
- in-house backup capability valuable under supplier disruption: Cassidey–Freeman–Melouk.

The full paper combines endogenous capability retention with supplier unavailability, but `lambda * nu` only scales the return to capability. The present model therefore does not yet identify a distinct interaction theorem generated specifically by *recovery capability under external platform dependence*.

## 8. Nested-benchmark result comparison

| Result | Dynamic learning / outsourcing benchmark | Disruption / concurrent-sourcing benchmark | AI learning benchmark | Current full model | Stage 6 status |
|---|---|---|---|---|---|
| Partial internal retention | Yes | Yes | Often a positive human/training margin or non-full automation | Yes | Not full-model-only |
| Internal activity despite current disadvantage | Yes, explicitly in Gray et al. | Can be justified as backup capacity | Current productivity can trade off with future learning | Yes | Not full-model-only |
| External-supply disruption raises value of internal capability | Not central | Yes | Not central | Yes | Component overlap |
| Automation lowers future human capability/knowledge | Outsourcing lowers future internal learning | Capacity usually exogenous | Yes | Yes | Structurally close |
| Supplier/platform price changes make/buy share | Yes in broader sourcing literature | Yes; supplier pricing studied | Not central | Yes | Mechanical here |
| Uniform positive human share over all capability levels | Not located verbatim | Not located verbatim | Related persistence/collapse thresholds | Yes under a sufficient boundary condition | Mathematical sharpening, not new mechanism |
| New interaction of endogenous capability × outage × price | No | No | No | **No separate theorem in current paper** | Fails full-model-only test |

## 9. Killed claims

The following must not be presented as independent theoretical contributions in the current model:

1. Hybrid human/AI organization by itself.
2. Full automation can be suboptimal because current outsourcing/automation erodes future human/internal capability.
3. A positive internal share can be optimal even when external provision has a current cost/performance advantage.
4. Platform/supplier markup causes less external sourcing than a resource-cost benchmark.
5. Longer execution horizons necessarily cause a larger cutoff distortion.
6. The word `agentic` or the parameter `n` by itself creates a new organizational mechanism.
7. The combination `AI + recovery + price` is novel merely because no exact paper uses all three labels.

## 10. Surviving claim set

No proposition currently survives Stage 6 as an independent main theoretical contribution.

The following statements survive only as **setting/model facts**, not contribution claims:

- the model is a compact way to combine external-AI delegation, retained recovery capability, outage risk, and a price-resource-cost wedge;
- the recovery-capability interpretation is institutionally plausible and useful for organizing the AI application;
- Proposition 4 is a clean internal characterization of persistence under the model's assumptions;
- no single located prior paper exactly reproduces the complete current game.

Under workflow v1.1, those facts are insufficient for `GO` because the combination generates no independently surviving interaction theorem.

## 11. Mathematical sanity check carried forward

No manuscript theory file was changed in this stage. Three bounded issues remain for any future branch:

1. Model domain states `0 < kappa-alpha < kappa < 1`, but Proposition 4 evaluates the condition at `kappa=1`. Either permit `kappa<=1` or define a maximal admissible `kappa_bar<1`.
2. Proposition 3 proves that the direct price wedge grows linearly with `n`; it does not prove monotonic growth of `s_T* - s_P*` in `n`.
3. The model uses `nu_A^P` / `nu_H` in definitions but later writes `u_H` in the gain expression; notation should be harmonized.

These are not the reason for the `NO-GO` verdict.

## 12. Strongest remaining novelty threat

The strongest threat is the joint reading of Gray–Tomlin–Roth (dynamic partial outsourcing with learning and internal production despite current cost disadvantage) and Cassidey–Freeman–Melouk (make-and-buy under all-or-nothing external disruption with in-house capability and supplier pricing), reinforced by the 2025–2026 AI-learning literature.

The current paper can distinguish itself institutionally, but not yet theoretically: the three channels are additive and no theorem exploits an interaction that is absent in all of those benchmark strands.

## 13. Final Stage 6 verdict and routing

**NO-GO. Stage 12 Journal Positioning remains blocked.**

The research question is not necessarily dead; the application and institutional problem remain meaningful. Therefore route to **Stage 3 — Candidate Mechanism Search**, not Stage 0.

The next Stage 3 search must be narrow. Its objective is to identify exactly one economically meaningful feedback created by external AI platform dependence that standard dynamic outsourcing / learning / concurrent-sourcing models do not have. Do not add multiple margins simultaneously. A promising search direction is to make the platform side strategically operative—rather than a fixed `p` and fixed `nu`—but Stage 3 must compare several candidate single-margin mechanisms before authorizing any model change.

Until such a mechanism survives Stage 3 and a new Stage 4 minimal-model gate, the current P1–P4 contribution set remains killed for submission as a theory contribution.
