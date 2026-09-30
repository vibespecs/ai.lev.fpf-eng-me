# ME.9 - Relate Method Representations across Their Different Uses: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.9:5 - Archetypal Grounding - EC-417 Method Material for Four Uses {#archetypal-grounding-ec-417-method-material-for-four-uses}

The EC-417 team holds candidate whole `C-EC-Release-v2`, its current candidate-account edition, and trial WorkPlan `WP-EC417-B2-Trial-1`. ME.8 has supplied the bounded claims needed for the proposed B2 trial: purpose, A/B/B2/R alternatives, evidence entry, Work order, allocations, authority, confidentiality, recovery, and stops. ME.9 does not admit the candidate as a Method or turn the WorkPlan into Work.

The four proposed uses have the following claim groups. Their subject and reliance results do not fill the missing receiving decisions:

| Use boundary and receiving result | Direct result, exact claim, and reliance | Exposure and loss | `C.37` disposition and return |
| --- | --- | --- | --- |
| `ReleaseDecider-17` must decide A, B2, R, or withhold for the bounded trial. No directly governed result permitting the decision table's contribution to that decision is supplied here. The eventual C.11 or direct Method-architecture result alone chooses the alternative; naming that later choice does not supply the missing representation-use result. | `C.2.1` identifies the current decision-table episteme. Exact claim: the table states the current alternative, evidence-timing, peak-burden, authority, entry, and closure distinctions for this candidate edition. A.2.4 classifies its intended decision-evidence use. A.10 path `P-ME9-EC417-Decision-1` carries that claim and currentness window with `RelianceDisposition=pass`. | Exposes alternative and guard distinctions; omits detailed performer instructions and any proof that B2 will succeed. | `unresolved`: obtain from the receiving decision owner the governing predicate and actual result admitting or declining this table's bounded contribution. Reconsider the row on that result, and return if the candidate edition, evidence entry, authority, window, A.10 disposition, or receiving decision changes. |
| `SafetyReviewer-17` must check the supplier-prepared comparison of the signed pinout with the provisional edition used in integration, and identify the affected safety checks before trial release; [signed-delta preparation](spec://ai.lev/fpf-eng-me/pub/cross-pattern-application#signed-delta-preparation-for-b2) states the operands, action, and result. No directly governed result permitting the action-and-guard episteme's contribution to this preparation action is supplied here; actual permission, Work, and task success also remain with their direct owners. | `C.2.1` identifies the current action-and-guard episteme. Exact claim: it states the B2 inputs, required checks, confidentiality, peak bound, signed-before-closure guard, and rollback stop. A.2.4 classifies the intended preparation use. A.10 path `P-ME9-EC417-Safety-1` carries the current-edition and signed-evidence premises with `RelianceDisposition=pass` for the named preparation window. | Exposes checks and stops; omits portfolio dates and authority not needed to read the preparation steps. | `unresolved`: obtain from the preparation-use owner the governing predicate and actual result admitting or declining this instruction's bounded contribution. Reconsider the row on that result, and return on stale edition, changed confidentiality or guard, missing permission or authority, failed A.10 path, or a different action. |
| `SupportBuilder-17` must configure retrieval and tailoring support for the B2 trial. No directly governed result permitting the support-task episteme's contribution to this configuration action is supplied here. ME.10 owns the support comparison and tests; that ownership alone does not supply the missing result. | `C.2.1` identifies the support-task episteme. Exact claim: it names users, required Method claims, PLM/CI Systems, permissions, task results, and stops. A.10 path `P-ME9-EC417-Support-1` carries the current source and allocation premises with `RelianceDisposition=pass` for this configuration decision. | Exposes task inputs and relation gaps; omits provider capability, actual access, performed task Work, and configuration superiority. | `unresolved`: obtain the ME.10-governed predicate and actual result admitting or declining this input for the named configuration action. Return the omitted support facts to their direct owners; reconsider on the receiving result or a changed task set or source edition. |
| `MethodEngineer-17` must decide which findings from completed trial `W-EC417-B2-1` require reopening the candidate before further evaluation. No directly governed receiving result has yet been recovered for that exact decision; the separate ME.11–ME.14 judgments do not choose the reopen premises by themselves. | `A.15.1` independently admits the one Work. The project reading would expose allocation and occupied decision slots, the process reading the performed verification sequence and its correspondence to recurring check positions, and the case reading the evidence history, observed conditions, and next-decision changes. The candidate epistemes `E`, viewpoint editions `P`, and their fixed rules are not identified in this case. Without them, none of the three required direct judgments that `EpistemeViewpointConformanceRelation(E,P)` obtains can yet be made. A.2.4 classification and A.10 path `P-ME9-EC417-Trial-1` cannot supply those missing conformance judgments or the missing receiving outcome. | The three intended readings keep unlike claims about the same Work visible; they omit proof of Method identity, transfer, worth, future effectiveness, conformance, and permission to use the claims in the reopen decision. Profile membership supplies none of those results. | `unresolved` for the reopen action. Return to the exact `E`/`P` owners for the three `E.17.0` judgments and to the direct decision owner for its predicate and actual outcome; reconsider this row only after both bases are available. A reading for another action starts another row. |

ME.9 relates these four unresolved selections in cross-use profile `MRP-EC417-CrossUse-1`. The profile exposes their correspondences and gaps; it permits none of the pending uses by itself:

| Profile position | Cross-use result |
| --- | --- |
| shared Method source | All four rows return to candidate `C-EC-Release-v2` and the same current candidate-account edition; none promotes that candidate to an admitted Method. |
| cross-use correspondences | The B2 alternative, evidence-entry boundary, confidentiality condition, recovery path, and stop claims occur in different action-specific forms across decision, preparation, support, and reopen uses. Their correspondence lets a source change be traced across rows without making the representations identical. |
| conflicting omissions | The decision row omits performer instructions; the preparation row omits portfolio timing and unused authority; the support row omits actual access, capability, task Work, and configuration superiority; the reopen row omits Method identity, transfer, worth, and future-effectiveness claims. These omissions remain explicit and are not repaired by unioning the rows. |
| edition relations | Every row depends on the named candidate-account edition. The reopen row additionally refers to admitted Work `W-EC417-B2-1` and three still-unresolved candidate-episteme/viewpoint-edition conformance questions; the other rows do not silently inherit those Work-dependent claims. |
| keep-separate decisions | The decision table, action-and-guard episteme, support-task episteme, three candidate readings, their viewpoint editions, each direct conformance judgment, and the receiving decision retain their own governors and statuses. The profile creates no integrated super-view, collection, selected structure, or new MethodDescription edition. |
| cross-use return | A changed candidate status, source edition, B2 alternative, evidence-entry boundary, or recovery/stop claim reopens every affected row and this profile relation. A changed support task reopens the support row. The unresolved reopen row returns only when exact Work identity, the three direct `E.17.0` judgments, their claims, the A.10 disposition, and the governed receiving outcome are available; later change to any of those bases reopens it. |

The project, process, and case readings in the fourth row concern one independently admitted Work, not three Work objects. Each becomes a `U.View` only through its own positive `E.17.0` judgment against an exact viewpoint edition, and co-recording them is useful only when each can change the same exact reopen decision. The profile does not make an integrated super-view.

A timeline, dependency network, state-transition drawing, or other node-link material is a mathematical-lens result only when `C.29` identifies the formal object, mapping, preserved and lost structure, admitted use, and stop. Ordinary node-link material is not a mathematical graph by appearance or vocabulary.

### ME.9:5.1 - An adequate existing profile and a changed omission {#an-adequate-existing-profile-and-a-changed-omission}

In a constructed unchanged-use case, a method engineer relates an existing action-and-stop description for preparation to an evidence-and-limit description for assessment. Their direct results, source claims, receiving uses and earlier matching observations remain adequate. Inspection establishes the needed shared-source correspondence and shows that each omission is irrelevant to the other action's permitted contribution. The present profile and choice are complete without scheduling a user study. Retain the basis only if the receiving use needs later reconstruction.

Now a proposed shorter preparation representation omits an uncommon stop. A fresh user's wrong action under that condition would materially change the choice. Suppose a capable receiver, permitted material and a protected preparation window make the discriminating task worth its whole burden: select that task and obtain its actual answer before claiming observed usability. If the task is unavailable, the omission can still be rejected by direct content inspection; neither the attractive layout nor the study plan establishes safe user performance.

## ME.9:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| artifact-as-Method bias | A diagram or playbook becomes the Method itself. | Return every row to the admitted Method or candidate account and current description edition. |
| use-boundary collapse | One selection is reused for another action because the user, carrier, or Method is unchanged. | Give every receiver/action pair one complete embedded C.37 claim group and another row for another action. |
| layer borrowing | Publication, provenance, evidence classification, or profile membership is treated as reliance or permission. | Keep direct subject result, optional A.2.4 classification, material A.10 reliance, and receiving result separately recoverable. |
| viewpoint reification | Project, process, and case become three different Work objects. | Hold one admitted Work and one exact action fixed; apply each viewpoint conformance separately. |
| plan-as-work bias | A representation of intended enactment is reported as performed Work. | Preserve WorkPlan status and return the failed or absent Work-dependent result. |
| graph metaphor bias | Any connected Method material is called a graph. | Reserve mathematical graph claims for an actual `C.29` result; call ordinary material a diagram, table, map, or other direct kind. |
| integrated-view bias | Profile colocation creates one authoritative super-view or new MethodDescription edition. | Keep rows separate and change the edition, collection, structure, or view only through its direct owner. |

## ME.9:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “This diagram is the Method.” | Name the Method or candidate account, current description edition, direct subject result, exact claim, and use boundary. |
| “Everyone should use the canonical process map.” | Make another row for every receiver/action pair and expose only its required Method claims and stops. |
| “The project, process, and case views show different Work.” | Apply their viewpoint criteria to one admitted Work and co-record them only for the same exact action. |
| “The current publication proves this row may be used.” | Record publication as auxiliary fact; require the direct subject, reliance when material, and receiving results. |
| “The planned trial is already visible as performed process Work.” | Retain a WorkPlan representation until Work exists and satisfies the direct view or Work criterion. |
| “Combine all views into one Method structure.” | Keep rows separate unless direct composition and `A.22` selection-use results independently obtain. |
| “The graph proves the workflow order.” | Identify a mathematical graph and correspondence under `C.29`, or keep the drawing as a non-mathematical episteme. |

## ME.9:10 - Rationale {#rationale}

MethodDescriptions combine action, purpose, inputs and results, variation, evidence, support, and stop claims that different users consume differently. `C.37` governs transdisciplinary selection and co-use for one receiver and one action. ME.9 connects these complete use-bounded selections to one MethodDescription or candidate account and maintains the cross-use correspondences, omissions, edition relations, and keep-separate decisions of that profile.

## ME.9:11 - SoTA-Echoing {#sota-echoing}

Project, process and case management can produce views of the same Method-related Work from different viewpoints. Each view must satisfy its own viewpoint; select its claims for the named action. The different views do not establish three Methods.

| Source | Adopted or adapted contribution | Boundary and practitioner implication |
| --- | --- | --- |
| ISO/IEC/IEEE 24774:2021, [process-description views and elements](https://www.iso.org/standard/78981.html) | Adopt explicit intended views and description elements for different Method users. | View-oriented description conformance does not create performed Work or import a universal ontology. ME.9 relates Method claims to named uses and leaves view identity to its direct governor. |
| Daalhuizen and Cash, [Method content theory](https://doi.org/10.1016/j.destud.2021.101018) | Adapt the separation of Method content from the forms through which users encounter it. | Method-content roles guide the profile; no single content form is made canonical. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Adopt representation, intended use, tool, and adaptation as distinct Method questions. | A tool or representation does not become the Method or evidence of enactment. The EC-417 profile keeps these claims separate. |
| FPF `C.37`, `C.2.1`, `E.17.0`, `C.29`, `E.24.PUB`, `A.22`, and `C.13` in this edition's named dependency state | Reuse use-bounded representation selection, episteme, view, mathematical-lens, publication, structure, and collection results. | These patterns retain authority over common representation kinds, use-bounded claim groups, reliance and receiving-result separation, and direct predicates. ME.9 contributes only the MethodDescription/candidate-account profile, cross-use relations, Method-specific omissions, and return paths. |

Reopen when a representative Method user cannot perform the named action without hidden reconstruction; when a Method-content role or MethodDescription practice changes the profile action; when project, process, and case criteria cease to preserve one Work; when a row no longer carries the complete current C.37 claim group; or when the FPF dependency state changes the consumed representation-selection result.


## ME.9:End {#end}
