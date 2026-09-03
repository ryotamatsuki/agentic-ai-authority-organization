# Referee-Style Review and Revision History

Snapshot date: 2026-09-03

This note records the main concerns raised in prior JITE-style referee review and the corresponding revisions incorporated into the current manuscript.

## 1. Propositions were too condition-driven / insufficiently sharp

**Prior concern:** Propositions 2 and 4 looked close to corollaries of the assumed functional form and did not generate a sufficiently strong theoretical payoff.

**Current response:**
- Proposition 2 now isolates a parameterized sufficient condition under which full automation is suboptimal even when AI dominates human handling task by task in normal operations.
- Proposition 4 has been substantially strengthened. If there exists an `epsilon in (0,1)` satisfying the stated condition at maximal admissible AI capability, then
  `s_P^*(kappa) < 1 - epsilon`
  for every admissible `kappa` in the capability interval. Thus a uniformly positive human-authority share survives AI capability improvements.
- The theorem and Appendix proof use the strict inequality consistently.

**Remaining caveat:** The paper remains a deliberately parsimonious, sufficient-condition-driven theory paper rather than a full characterization over a large parameter space.

## 2. Fallback capability was too reduced-form and economically ambiguous

**Prior concern:** It was unclear whether the state variable represented resilience, tacit knowledge, supervisory capacity, organizational memory, or something else.

**Current response:**
- Section 3.2 now defines the primitive as `recovery capability (fallback capability)`.
- The state variable is explicitly interpreted as a **recovery-relevant experience stock** accumulated through retained human authority in period 1:
  `H(s) = Hbar + beta(1-s)`.
- A contingency occurs with probability `lambda`; conditional on a contingency, the external platform is unavailable or unreliable with probability `nu`.
- `rho(H(s))` is explicitly the probability of successful recovery in that state, and successful recovery yields value `R`.
- Discussion uses the phrase `experience stock` and treats crisis response, override capacity, supervisory judgment, and tacit operational knowledge as practical manifestations rather than separate primitives.

**Remaining caveat:** The experience-stock/recovery technology is still reduced form; a richer microfoundation of learning, forgetting, or crisis response is left for future work.

## 3. Platform pricing result looked like a mechanical exogenous wedge

**Prior concern:** With `p-r` exogenous, the private-versus-technological comparison risked being a trivial price-wedge result.

**Current response:**
- Proposition 3 makes the agentic execution horizon economically operative:
  `Delta^T - Delta^P = n(p-r)` task by task, and
  `Phi^T - Phi^P = s n(p-r)` for delegated mass `s`.
- Therefore the organizational distortion caused by platform pricing is stronger in longer-horizon, more genuinely agentic execution environments.
- The paper separates the intensive authority-allocation distortion from the extensive adoption margin.

**Remaining caveat:** Platform pricing remains exogenous; endogenous platform market power is explicitly identified as an extension.

## 4. Literature review and institutional positioning were too thin

**Prior concern:** The manuscript did not sufficiently connect to the economics of organizations, governance, technical change, and platform institutions.

**Current response:** The literature section now explicitly connects the model to:
- Aghion and Tirole (1997) on formal and real authority;
- Dessein (2002) on authority and communication;
- Garicano (2000) on knowledge hierarchies;
- Athey, Bryan, and Gans (2020) on allocation of decision authority to human and AI;
- Agrawal, Gans, and Goldfarb (2019) on AI as prediction;
- Baker, Gibbons, and Murphy (2023), Marschak and Wei (2024), Mukherjee and Saha (2024), and Kim (2025) for recent JITE-relevant governance, technical-change, delegation, and platform themes;
- Rochet and Tirole (2003) on platforms;
- Nzembayie and Urbano (2026) on generative-AI platform dependence and power dynamics.

## 5. Section 6 was too weak

**Prior concern:** Showing merely that better AI increases delegation while full automation might fail did not add enough beyond earlier propositions.

**Current response:** Proposition 4 now establishes a uniform-persistence result. Under the stated condition, the optimal cutoff is bounded strictly below `1-epsilon` for every admissible AI capability level. This is materially stronger than saying only `s^*<1` at a given parameter value.

## 6. Discussion did not sufficiently integrate the mechanism

**Current response:** Discussion now explicitly describes retained recovery capability as an internal experience stock relevant for abnormal states and links the mechanism to organizational resilience, platform governance, make-or-buy decisions, and firm boundaries.

## Overall current assessment

The main prior JITE-style criticisms have been substantially addressed. The remaining theoretical vulnerabilities are primarily:

1. reduced-form recovery-capability accumulation;
2. exogenous platform pricing;
3. a model whose strongest results are still sufficient-condition rather than full global-characterization results.

These are now best treated as scope/extension issues rather than evidence that the baseline manuscript is underdeveloped.
