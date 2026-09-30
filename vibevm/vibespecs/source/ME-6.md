# ME.6 - Compare Method-Architecture Alternatives and Simultaneous Enactment Conflicts: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.6:5 - Archetypal Grounding {#archetypal-grounding}

### ME.6:5.1 - Cheaper Clarification: Several Methods, No Composite {#cheaper-clarification-several-methods-no-composite}

In a safety-relevant release, `M-HW-Verify`, `M-SW-Integrate`, `M-Supplier-Approve`, and `M-Release-Authorize` are identified Methods. Hardware verification and software integration can contribute during overlapping intervals from differently versioned evidence. Supplier approval produces a signed result later. Release authorization uses the safety result and signed-evidence condition.

The selected structures are:

| Structure | Direct relation and truth |
| --- | --- |
| Method structure | Four Methods are co-used; no `methodPartOf` or composite-Method relation is shown to obtain. |
| Work structure | Some verification and integration Work may overlap; bounded Work set `W-TraceAcceptReject-17` contains one human accept/reject occurrence for every AI suggestion used by the branch; signed evidence and accepted safety result are genuine first–then guards for release authorization. |
| description structure | project, process, and case views describe the same release Work while foregrounding schedule, recurring controls, and one release's state; none is an architecture alternative. |
| allocation structure | admitted Systems `TraceReviewer-17`, `SafetyReviewer-17`, and `ReleaseDecider-17`; their decision Work; covering assignments `ASG-TraceReview-17`, `ASG-SafetyReview-17`, and `ASG-ReleaseDecision-17`; permission `PERM-TraceAcceptReject-17`; and direct authorities `AUTH-SafetyEvidence-17` and `AUTH-ReleaseDecision-17` remain separate; shared capacity can constrain later alternatives. |

`ARS-EC417-RelationOnly-1` records the smaller clarification: retain the four Methods and their direct result-use, permission, and authority relations without naming a composite. The question here is only whether co-use supports a Method-whole claim. `B.1.5` supplies the composition test; where an architecture claim is made, `C.30` distinguishes the claimed structure from obtaining relations. No composite is established by the evidence shown, and no rival arrangement is at issue. Stop with that clarification, not a completed ME.6 comparison. A later choice about provisional supplier evidence opens the genuine alternatives in :5.3; their comparison can also end without creating a Method whole.

### ME.6:5.2 - Simultaneous Multigrain Contributions with Local First–Then Relations {#simultaneous-multigrain-contributions-with-local-first-then}

In a separate five-day Method Engineering case, `ME-W0` is the bounded project adaptation Work. `ME-W1` repertoire-recovery Work, `ME-W2` candidate-account formation Work, `ME-W3` description/tool-proposal Work, and `ME-W4` evaluation Work are parts at the next finer grain; trial Work `ME-W7` is part of `ME-W4`. During the same five-day interval, continuing product-engineering Work `ME-W5` and repository-maintenance Work `ME-W6` overlap `ME-W0` but are not its parts.

The repertoire-recovery Method contributes through `ME-W1`, candidate-account formation through `ME-W2`, description/tool proposal through `ME-W3`, and trial/evaluation Methods through `ME-W7` and `ME-W4`. Product-engineering and repository-maintenance Methods contribute concurrently through `ME-W5` and `ME-W6`. These are contributions at whole-Work, part-Work, nested trial-Work, and separate overlapping-Work grains, not one level sequence.

Two case-local first–then relations remain inside that simultaneous interval: `ME-W1` precedes `ME-W2`, and `ME-W3` precedes the relevant evaluation decision in `ME-W4`. Temporal overlap across the other grains erases neither relation. It establishes neither a universal Method stack nor `methodPartOf`; a teaching tree that presents recovery before evaluation is a description view, not the Work structure.

Consider a minute inside trial Work `ME-W7`. The participant follows the proposed unit-review description, converts a supplied measurement and compares it with the stated tolerance. Performing that comparison is part of carrying out the trial; the trial is part of evaluating the proposed description in `ME-W4`; that evaluation is part of the project adaptation `ME-W0` currently under way. The encompassing evaluation and adaptation are ongoing through this performed action, although their conclusions have not yet been reached. This is a constituent connection, not an inference from the five-day overlap.

The evaluation purpose changes how the trial is performed. If the purpose is to test whether a reader can recover a conversion rule from the description, supplying the rule as a spoken prompt would defeat that use. If the purpose is instead to measure supported execution after instruction, the same prompt may be appropriate. The arithmetic can be correct in both cases while one trial fails its encompassing purpose. Keep the participant's result, the help actually supplied and the evaluation conclusion distinct. B.1.5.EW recovers this connection; B.1.5.RS applies when replacing a shared trial or checking Method across differently intended evaluations.

### ME.6:5.3 - Possible-Future Alternatives: A, B, and B2 {#possible-future-alternatives-a-b-and-b2}
The EC-417 release scenario later asks how to handle provisional supplier evidence. Three alternatives differ by Work order and allocation:

For this constructed comparison, `2.07 h` is safety-engineer time for traceability and safety-closure work: checking the current requirement–implementation–verification correspondences and preparing or recording the closure disposition. It excludes the separately counted signed-delta preparation and `0.33 h` board, and any additional affected verification or integration rework.

| Alternative | Work and allocation structure | Capacity and consequence |
| --- | --- | --- |
| A | wait for signed evidence before software integration; one final board | prospective pre-entry alternative; under baseline signed evidence at `D-8`, misses the `D-21` integration slot |
| B | integrate from an explicitly versioned provisional edition at `D-21`, preserve that basis and uncertainty, and reconcile it to signed evidence at `D-8`; safety engineer performs all `2.00 h` signed-delta preparation | on the `D-8` peak day: `2.00 + 0.33 + 2.07 = 4.40 h`, or `0.55` of an eight-hour day; exceeds the `0.40` limit |
| B2 | same Work order and evidence-history rule as B; supplier-configuration role performs `1.60 h` of preparation and safety performs `0.40 h` | on `D-8`: `0.40 + 0.33 + 2.07 = 2.80 h`, or `0.35`; the separate `D-21` board makes per-release safety burden `3.13 h` rather than B's `4.73 h` |

The first 20-minute board is on `D-21`; the second is on `D-8`. They occur on different days. The peak-day comparison and per-release burden are separate measures. Each board remains below the 45-minute meeting limit. Under B or B2, signed evidence supersedes the provisional edition only for safety-closure reliance; the provisional edition, uncertainty, use in `D-21` integration Work, and relation and delta to the signed evidence remain traceable.

`CUR-EC417-CadenceEffect-1` returns `unsupported` for the interventional claim that earlier reconciliation reduces reopenings. `AD-EC417-B2-Trial-1` therefore consumes no positive causal premise. It consumes separately named non-causal `DC-EC417-CadenceMismatch-1`, the capacity comparison, confidentiality, the covering trace/safety/release assignments, `PERM-TraceAcceptReject-17`, the two independently supported direct authority relations, and reversibility to choose only three bounded B2 trials.

At the `D-21` pre-entry checkpoint, `ReleaseDecider-17` performs the branch decision under `ASG-ReleaseDecision-17` and `AUTH-ReleaseDecision-17`, after the required safety-evidence decision under `ASG-SafetyReview-17` and `AUTH-SafetyEvidence-17`. B2 entry also requires `TraceReviewer-17` to perform `W-TraceAcceptReject-17` under `ASG-TraceReview-17` and `PERM-TraceAcceptReject-17` for every AI suggestion used by the branch.

Before entry, choose A when signed evidence is already available or when versioned provisional evidence, supplier preparation, confidentiality, the trace-review assignment or permission, or a safety/release assignment or authority condition for B2 is absent. Once early B2 integration has occurred, A is no longer a possible history for that release.

Missing signed evidence at `D-8` withholds release and starts recovery R. Preserve the performed integration record, exact provisional edition, uncertainty, and earlier use. When signed evidence arrives, record its relation and delta to the provisional edition, re-baseline, and repeat the comparison and affected verification. Retain or roll back/repeat early integration. For a full repeat of these recovery tasks, count `1.60 h` supplier preparation plus `2.80 h` safety preparation, board, and trace/closure work (`0.40 + 0.33 + 2.07`). Count affected verification or integration rework in addition; the case supplies no fixed duration for it. If recovery stops before those tasks finish, record the Work and burden that actually occurred rather than assigning the full repeat cost. Move only to the next authorized slot after repeated decision Work under the covering assignments and authority relations. Every repeated AI suggestion again requires the trace-review Work, assignment, and permission. Signed evidence supersedes provisional evidence for closure reliance without erasing the provisional history.

The architecture decision remains prospective. Implementation and the three trial releases are later Work. If signed evidence becomes available at `D-21`, sensitivity selects A prospectively; it does not rewrite a past B2 release.

In that pre-entry variant, suppose the existing signed-first arrangement has adequate current capability, capacity and release evidence, and the same comparison reveals no useful gain from provisional-first preparation. The team can finish by retaining A on that basis. Planning an extra B2 trial would consume the safety attention needed for the current release without changing this decision. Changed evidence timing or capacity can reopen the comparison. The baseline case still has a thirteen-day mismatch and supports the three bounded B2 trials under their stated conditions.

## ME.6:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| universal-stack bias | Method, Work, support, allocation, description, and culture become one level sequence. | Name each selected structure and direct relation separately. |
| visual-representation bias | A diagram or mathematical graph is treated as the architecture. | State the structure and relation semantics first; choose a representation only for a named use. |
| concurrency bias | Overlap erases result-use, evidence, configuration, or authority guards. | Identify genuine first–then conditions directly. |
| local-efficiency bias | Reduced effort in one role hides burden moved to another role or interval. | Show combined peak and total burdens with receiving scopes. |
| trial-as-reality bias | A selected possible-future synthesis is reported as obtaining practice. | Keep decision, implementation Work, trial Work, observations, and relation truth distinct. |

## ME.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “All methods are layers in one stack.” | Select and name the actual Method, Work, allocation, support, description, and cultural structures. |
| “These two diagrams are alternatives.” | Compare the underlying relation sets; if they are the same, keep them as views. |
| “Work overlaps, so the Methods compose.” | State Work overlap and require independent Method identity and composition evidence. |
| “B2 saves 1.60 hours.” | Name the role and interval from which burden leaves and the role or interval that receives it. |
| “The trial choice proves the architecture.” | Keep proposed relations, decision, trial Work, observations, and later obtaining claims distinct. |
| “Recovery means switching to the earlier alternative.” | Preserve already-performed Work and define a separate post-entry recovery branch. |

## ME.6:10 - Rationale {#rationale}

Method organization, dated Work, subject arrangement, allocation, descriptions, provider support and cultural continuation answer different questions. Treating them as isomorphic loses either useful simultaneous contribution or real dependency. Select the structures that can change the decision and compare their relations in the receiving case.

Project, process and case views provide a practical test: when several views concern the same Work, their labels do not create architecture alternatives. The alternatives begin where proposed direct relations differ.

## ME.6:11 - SoTA-Echoing {#sota-echoing}

| Source | Retained contribution | Use boundary |
| --- | --- | --- |
| Current FPF `C.32.MWA`, `C.30`, `A.22`, and `B.1.5` | Several-structure synthesis, architecture truth, selected structure, and Method composition. | ME.6 supplies the specialist Method-architecture comparison and bounded decision. |

Reopen when a representative use exposes another non-isomorphic structure that can reverse the decision, a moved burden remains systematically hidden, or an alternative cannot be realized without changing the selected relation set.


## ME.6:End {#end}
