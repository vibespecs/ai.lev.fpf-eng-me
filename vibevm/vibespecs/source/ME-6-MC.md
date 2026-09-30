# ME.6.MC - Compare Method Arrangements through a Mathematical Model: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.6.MC:5 - Archetypal Grounding {#archetypal-grounding}

The following constructed cases expose different comparison questions. Their calculations are not observations of a team's performance.

### ME.6.MC:5.1 - Compare centralized calculation with combined local summaries {#compare-centralized-calculation-with-combined-local-summaries}

Two teams must report the mean of all their measurements. The proposed arrangements are to send every measurement to one calculator, or to compute a summary in each team and combine the summaries. All values have the same meaning and units, and every included measurement has equal weight.

Represent a finite list \(x=(x_1,\ldots,x_n)\) by

\[
T(x)=\left(\sum_{i=1}^{n}x_i,\ n\right).
\]

Combine pairs by \((s,n)\oplus(t,m)=(s+t,n+m)\). For concatenation of lists \(x\) and \(y\),

\[
T(x\,y)=T(x)\oplus T(y).
\]

Both components follow from adding the sums and counts. Pair addition is associative, so repeated regrouping preserves the summary. For a nonempty combined list, recover the mean as total sum divided by total count. This supplies the composition and recovery needed by the parallel arrangement.

With lists \((0,4)\) and \((10)\), the summaries are \((4,2)\) and \((10,1)\). Their combination is \((14,3)\), giving \(14/3\), the same mean as central calculation. Averaging the two local means instead gives \((2+10)/2=6\), answering a different weighting question.

The mathematical comparison supports using sum-and-count summaries when this mean is the receiving result. Application requires consistent inclusion and weighting rules, with every included record assigned to one team and counted once. The algebra uses exact addition; a rounded implementation needs the relevant numerical error comparison. Whether the two teams use those rules needs grounds from their work.

Now the recipient asks how many measurements exceed \(3\). Replacing \((0,4)\) by \((2,2)\) leaves the local sum-and-count pair unchanged, and leaves the combined pair \((14,3)\) unchanged, but changes the requested count from two to one. No rule using only that pair can distinguish the cases. The earlier mean-equivalence remains valid; the new question needs another retained quantity or a return to the measurements. The method decision must not treat the old summary as a substitute for all uses of the records.

### ME.6.MC:5.2 - Compare parallel checks with their shared capacity exposed {#compare-parallel-checks-with-their-shared-capacity-exposed}

A team considers one automated test bench versus two independent benches. Two preparations can run independently from time zero, each with its own analyst. Preparation A takes three minutes; preparation B takes two. Each subsequent check occupies a bench for four minutes. Both completed check results are required for one minute of final assembly.

For this calculation, durations are fixed, the work is nonpreemptive, and setup and transfer times are zero. Benches and the final assembler are available when needed, with no competing work. Checks initially require no continuously attending operator. The required completion time is at most ten minutes.

With two benches, check A runs from minute 3 to 7 and check B from 2 to 6. Assembly runs from 7 to 8. The model admits completion at minute 8.

With one bench, the two checks cannot overlap. A feasible schedule is B from 2 to 6, A from 6 to 10, and assembly from 10 to 11. No schedule finishes earlier: the bench cannot start a check before minute 2 and must perform eight minutes of check work before the final assembly minute. Thus eleven minutes is both a lower bound and an achieved value.

The one-bench arrangement fails the ten-minute criterion under these premises. The two-bench arrangement passes that criterion in the constructed schedule. Whether acquiring or allocating another bench is worthwhile remains a choice involving its availability and other burdens. The calculation does not supply those missing facts.

**Changed premise.** Both checks now require one qualified operator throughout, and only one such operator is available from minute 2 onward. Add a capacity-one operator constraint to the model. Two benches no longer permit overlap: there are still eight exclusive operator minutes, no check can begin before minute 2, and assembly follows both checks. The eleven-minute lower bound applies again and the same serial schedule attains it.

A hardware-only proposal therefore does not repair the deadline under the changed condition. The useful next comparison concerns an available arrangement that changes the limiting condition, or a justified change of requirement. Merely redrawing two parallel lanes leaves the conflict in place.

### ME.6.MC:5.3 - Compare orders by the result a later action consumes {#compare-orders-by-the-result-a-later-action-consumes}

A publication team proposes two arrangements for an edit and a review: edit then review, or review then edit. The required result is that the released artifact is the revision to which the review result applies. Review quality is a separate criterion; this comparison concerns revision correspondence.

Use state \((v,c,p)\): \(v\) is the working revision, \(c\) the reviewed revision, and \(p\) the released revision. Initially the state is \((0,\bot,\bot)\), where \(\bot\) means none. Model an edit \(E\) as incrementing \(v\), a completed review \(K\) as setting \(c=v\), and release \(P\) as setting \(p=v\). No other operation occurs in the initial model.

| Proposed order | States after its steps | Required result |
| --- | --- | --- |
| \(E;K;P\) | \((1,\bot,\bot)\), \((1,1,\bot)\), \((1,1,1)\) | \(p=c\) holds. |
| \(K;E;P\) | \((0,0,\bot)\), \((1,0,\bot)\), \((1,0,1)\) | \(p=c\) fails. |

Both orders finish with working revision 1. A model retaining only \(v\) would make them look equivalent and lose the distinction needed by release. The separating trace rejects the second ordering for the stated criterion.

Now the environment permits an additional edit after review but before release. Even the first ordering admits

\[
(1,1,\bot)\ \longrightarrow\ (2,1,\bot)\ \longrightarrow\ (2,1,2).
\]

Its earlier result depended on excluding this intervention. The team also offers an arrangement that retains an immutable copy of the reviewed revision and releases that copy. In the same situation it releases revision 1, giving \(p=c=1\), while the workspace contains revision 2. This arrangement satisfies the revision-correspondence criterion if the copy and its review association are actually preserved. It leaves a different question: is releasing revision 1 still useful and permitted, or does the receiving work require revision 2? ME.3 and ME.6 retain that criterion and trade-off rather than silently replacing it.

The comparison supplies a condition for the release arrangement, not evidence that anyone performed the review or retained the copy. If source-copy retention or release selection needs implementation, that construction remains to be done.

## ME.6.MC:6 - Bias-Annotation {#bias-annotation}

A familiar notation can make its retained quantities seem like the only relevant ones. Start with the receiving consequence before selecting a function, graph, schedule or simulation.

Treating every participant as an independent resource can conceal shared attention, access or preparation. Treating a participant as permanently occupied can make an arrangement look worse than its actual operation. Model the demand and release conditions that the comparison uses.

A favorable trace or convenient parameter choice can conceal an allowed failure. Conversely, an overly permissive environment can manufacture an obstruction. Preserve the assumptions that make the example or counterexample relevant.

## ME.6.MC:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Invited mistake | Repair |
| --- | --- |
| Compare pictures whose underlying arrangements are identical. | Identify the changed relation or finish with a change of description. |
| Infer combined adequacy from isolated component success. | Model the connection and establish the property needed of the combination. |
| Treat associativity as permission to reorder work. | Compare the two orders under their required observations. |
| Duplicate a shared performer or tool inside separate branches. | Use one shared-capacity account and recompute feasible overlap. |
| Treat one successful run as a guarantee over allowed interactions. | Retain its observed scope or derive the broader property. |
| Treat a model's counterexample as an observed work failure. | Check the correspondence and state whether the result is a possibility, an impossibility under assumptions, or an observation. |
| Turn mathematical composition into Method parthood. | Return the mathematical consequence to ME.6; use ME.7 for whole identity and obtaining relations. |

## ME.6.MC:10 - Architectural Rationale {#architectural-rationale}

ME.6 selects the structures and alternatives that matter to a Method decision. This method adds the construction that makes an interaction calculable: compatible operation domains, retained observations, combined resource demand, and a property or counterexample of the proposed connection.

MATH.17 and MATH.18 supply operations on operations and comparison through interpretations. CMP.14 supplies computational interactions when shared state or communication makes ordinary sequential composition insufficient. C.29 connects those mathematical results to the working situation.

The distinction between model and work is productive: a conditional impossibility can already reject a proposed arrangement under accepted conditions, while an uncertain premise can identify the clarification that matters. Neither result needs a claim that the mathematical components are actual parts of one Method. ME.7 handles that separate question.

## ME.6.MC:11 - SoTA-Echoing {#sota-echoing}

The practice question is how to compare interacting method contributions without reducing the decision to isolated scores or expanding every case into a large simulation. The selected line uses a property-specific model, explicit composition conditions and the least costly adequate derivation. The three worked cases show why different receiving questions need different retained structure.

**Resource composition versus isolated timing or unrestricted simulation.** [Arronategui, Bañares and Colom, *Large scale system design aided by modelling and DES simulation: A Petri net approach* (2025), §§2.2, 4–5](https://onlinelibrary.wiley.com/doi/full/10.1002/spe.3374) develops interpreted components, shared-resource composition and structure-preserving execution. It also distinguishes properties preserved by construction from failures that composition can introduce. **Adapt** this line in :4.2–:4.4: assign meanings to model elements and derive the selected combined property. Petri nets are an option for larger interacting systems; the inequalities in :5.2 settle the smaller capacity question more cheaply. Simulation becomes a serious alternative when analysis is impractical, with its outcome qualified accordingly. Reopen the representation when omitted resource or timing behavior changes the comparison.

**Compositional contracts versus whole-model verification.** [Dewes and Dimitrova, *Contract-based Design and Verification of Multi-Agent Systems with Quantitative Temporal Requirements* (AAAI 2025), §§4–6](https://arxiv.org/html/2412.13114v1) supplies a contemporary construction for local obligations, shared requirements and modular verification. Its experiments show a trade-off: smaller component checks can avoid the memory burden of a whole-model check, while their overhead can lose on small specifications. **Adapt** :4.4–:4.6 to check assumption compatibility and reopen dependent conclusions after changes. Retain a short whole-model argument when it suffices. The source's temporal logic, quantitative combination rule and computational-agent assumptions are not universal requirements for Method comparison.

For operation regrouping and interpretation, MATH.17/.18 provide the general mathematical constructions used in :5.1 and :5.3. A categorical presentation can package established composition laws, but supplies no shortcut around the operation, observation and correspondence tests. No such formalism is needed for the worked decisions.

These sources supply mathematical and computational modeling methods, not empirical proof that a proposed organizational arrangement improves work. ME.3 supplies the situated criteria, and C.29 governs application of the derived consequence. Reopen the comparison when a new source method answers the same practical question with less effort or when a material work distinction defeats the present model.


## ME.6.MC:End {#end}
