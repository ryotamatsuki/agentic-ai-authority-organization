# Proposition Absorption Matrix

Stage: 6R Proposition-Level Novelty Re-Kill
Date: 2026-09-03

| Proposition | Candidate claim | Closest prior result(s) | Exact difference | Full-model-only interaction? | Prior-art status | Kill decision |
|---|---|---|---|---|---|---|
| P1 | Routine tasks delegated externally; exceptional tasks retained internally; unique hybrid cutoff | Anderson & Parker (2002): partial outsourcing; Gray et al. (2009): partial outsourcing; Srivastava (2026): partial AI delegation / hybrid governance | Current model orders tasks by exceptionality and adds recovery stock | No. Cutoff follows monotone current gain plus concave capability term | STRUCTURALLY VERY CLOSE | **KILL AS CONTRIBUTION**; retain as characterization |
| P2 | Full automation can be suboptimal even when AI dominates human handling task by task | Gray et al. (2009): OEM can produce internally while at a current cost disadvantage due to learning/future effects; Anderson & Parker (2002): immediate outsourcing benefit can worsen long-run costs and partial outsourcing may dominate; Cassidey et al. (2022): in-house capability mitigates complete supplier disruption | Current paper labels internal learning as recovery capability and makes its payoff contingent on external platform outage | No new theorem from the interaction. `lambda*nu` scales the future capability-preservation motive | STRUCTURALLY VERY CLOSE / immediate economic analogue | **KILL AS MAIN CONTRIBUTION** |
| P3 | If platform price exceeds resource cost, private delegation is below technological benchmark; wedge scales with execution horizon | Loertscher & Riordan (2019): make-and-buy and supplier markup avoidance; Cassidey et al. (2022): in-house capability affects supplier pricing | Current model has exogenous `p` and resource cost `r`, plus per-step `n` | No. `DeltaT-DeltaP=n(p-r)` and `PhiT-PhiP=sn(p-r)` are identities; no strategic pricing response | MECHANICAL / COMPONENT OVERLAP | **KILL AS MAIN THEOREM**; possible accounting implication only |
| P4(1) | Better AI increases delegation | Standard monotone comparative statics; AI authority literature studies delegation responses to capability/uncertainty | One-dimensional cutoff problem | No | STRUCTURALLY VERY CLOSE | **KILL AS CONTRIBUTION** |
| P4(2) | A positive human share remains uniformly across all admissible AI capability levels under a sufficient maximal-capability condition | AI learning papers show automation can undermine training/human capital/knowledge and generate viability/trap thresholds; dynamic outsourcing shows persistence of internal activity for future learning | Exact epsilon-bound statement was not located verbatim | No new feedback. It is a boundary-condition plus monotonicity sharpening of the same dynamic capability-preservation trade-off | STRUCTURALLY VERY CLOSE / mathematical sharpening | **KILL AS MAIN CONTRIBUTION** |

## Nested-benchmark test

Define three conceptual benchmark strands, not literal parameter restrictions of one common prior model:

### Benchmark A — Dynamic outsourcing with learning

Remove external outage and AI-specific labels. External sourcing yields current benefits; internal activity affects future capability/cost through learning.

Closest papers: Anderson & Parker (2002); Gray, Tomlin & Roth (2009).

Result already available: partial outsourcing and internal production despite current disadvantage.

### Benchmark B — Concurrent sourcing under disruption

Hold internal capability as available capacity rather than an endogenous experience stock; external supply can fail.

Closest paper: Cassidey, Freeman & Melouk (2022), with Freeman et al. (2018) as a related risk-mitigation predecessor.

Result already available: internal production capability is valuable under outsourced-supply disruption; concurrent sourcing can be optimal; supplier pricing is affected by internal capability.

### Benchmark C — Automation with endogenous human learning/knowledge

Remove external supplier pricing/outage; automation substitutes for tasks through which humans learn or preserve knowledge.

Closest papers: Garicano & Rayo (2025/26); Afrouzi et al. (2026); Ide (2025/26); Acemoglu, Kong & Ozdaglar (2026).

Result already available: current AI/automation gains can erode learning, human capital, training viability, or knowledge stocks; non-full automation / continued human learning can be valuable.

## Full-model-only row

| Result | Benchmark A | Benchmark B | Benchmark C | Full current model | Status |
|---|---|---|---|---|---|
| Partial internal share | Yes | Yes | Related positive human/training margin | Yes | Not unique |
| Internal activity despite current disadvantage | Yes | Backup activity can be valuable | Dynamic learning trade-off | Yes | Not unique |
| Internal capability valuable only when supplier fails | Not central | Yes | No | Yes | Component overlap |
| Capability itself falls with past outsourcing | Yes | Usually no | Yes | Yes | Component overlap |
| Supplier price/resource-cost wedge shifts sourcing | Broad sourcing literature | Pricing explicitly studied | No | Yes | Mechanical here |
| New theorem requiring capability × outage × pricing jointly | No | No | No | **No separate proposition** | **FAIL** |
| New theorem requiring multi-step `n` | No | No | No | **No; all headline logic survives at n=1** | **FAIL** |

## Stage 6 conclusion

The current paper cannot claim a generalization/unification contribution because it does not exhibit a result that is unavailable in every nested benchmark and arises from the interaction of the added margins. Its strongest statements are either already known qualitatively or follow mechanically from the frozen objective.
