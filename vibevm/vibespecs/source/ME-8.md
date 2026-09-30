# ME.8 - Author a MethodDescription or Candidate Method Account for Named Uses: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.8:5 - Archetypal Grounding {#archetypal-grounding}

### ME.8:5.1 - Stop at the Candidate Whole {#stop-at-the-candidate-whole}

`C-EC-Release-v2` is a prospective account of a possible release-coordination whole. Its intended result, alternatives A, B2, and R, guards, authority boundaries, confidentiality, reversibility, and D0 stop make it useful, but the whole is not admitted as a `U.Method`. ME.8 may improve those claims for a selection or trial-planning use; it does not return a `U.MethodDescription` for that candidate whole.

The improved account remains useful: users can compare A and B2 before integration and plan a bounded trial with recovery R after a failed B2 closure. Every downstream use keeps the account's candidate status.

### ME.8:5.2 - A Bounded Description of an Admitted Constituent Method {#a-bounded-description-of-an-admitted-constituent-method}

For the admitted constituent `M-HW-Verify`, suppose the named use is preparing safety-verification Work for one EC-417 release. A description edition can state the applicable safety-relevant change family, the distinction between provisional and signed evidence, the comparison and affected-verification actions, the signed-before-closure bound, confidentiality conditions, and the mismatch or stale-edition stop. The use-coverage account says that it exposes those Method claims but omits dates, assignees, actual evidence versions, actual verification results, and release authority decisions.

The planner may cite that edition when constructing a WorkPlan. Supply separate claims about the Work schedule, the assignment of `SafetyReviewer-17`, the required capability, closure authorization, and whether verification occurred whenever the plan or later Work relies on them.

### ME.8:5.3 - Turn a reconciliation reminder into an instruction {#turn-a-reconciliation-reminder-into-an-instruction}

In this constructed case, a stock-reconciliation Method has already been identified. Its working rule is available, but the draft for a new storekeeper says only: "Reconcile stock and investigate discrepancies." The reader can add and subtract counts; they still need to know which counts to compare and what the difference means.

The author recovers the rule's inputs and dependencies. For one item, unit and interval, an opening stock count plus receipts minus issues gives the expected closing count, provided the movement account includes every change once. A physical count at the closing boundary supplies a different input. The author writes this instruction:

1. Select the item, counting unit and interval. Obtain the opening count, receipts and issues for that same scope, and the physical count at its closing boundary. Resolve a missing movement class, unit conversion or mismatched boundary before treating the balance as complete.
2. Calculate expected closing stock as opening stock plus receipts minus issues. The additions and subtractions represent movements into and out of the selected stock.
3. Subtract expected stock from the physical count. Return the difference with the counts and scope used. A negative difference means fewer units were counted than the movement account predicts; it does not identify the cause.
4. If the counts disagree, return the discrepancy for checking the movements and counts. Do not change a source count merely to force agreement.

With opening stock 48, receipts 12, issues 17 and a closing physical count of 41, the expected count is 43 and the discrepancy is -2. The description now supplies an operation, its operands, their origins, the reason for their combination and a useful return. Its authoring result is the instruction, not evidence that a storekeeper performed it.

The receiving-use check asks the reader to recover that calculation and return from the description. If the opening figure is in boxes while movements are in individual units and the conversion is unknown, a numerical balance remains unavailable. A comparison-only description could legitimately omit this enactment detail; this edition promises the storekeeper a way to perform the reconciliation.

## ME.8:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| document identity bias | A titled document becomes the Method or its complete description. | Establish Method admission and identify the claim-bearing episteme separately. |
| completeness bias | More sections are assumed to make the edition adequate for every use. | Name uses and expose only the claim positions they consume. |
| execution bias | Code, a checklist, or executable syntax becomes evidence that Work happened. | Keep representation, WorkPlan, Work, and result claims separate. |
| policy absorption | Approval, permission, or authority is written as Method semantics. | Cite the separate policy or relation only where the receiving use needs it. |
| candidate laundering | A useful prospective account is called a MethodDescription. | Improve the account but do not call it a `U.MethodDescription` until `A.3.1` admits the Method. |

## ME.8:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “Write the complete method once.” | Split the request into named uses and record coverage and omissions for each. |
| “The workflow diagram is the MethodDescription.” | Identify the claim-bearing episteme first; treat the diagram as one representation of selected claims. |
| “Add the project schedule so the description is actionable.” | Keep the reusable Method claims in the description and put dates and intended assignments in the WorkPlan. |
| “The procedure passed review, so the claims are adequate everywhere.” | Record the exact review or policy claim separately and evaluate each receiving use under its own conditions. |
| “The candidate account is detailed enough to count.” | Detail does not replace Method admission; return improved candidate content. |

## ME.8:10 - Rationale {#rationale}

Description adequacy is use-relative, while MethodDescription membership is not. Separating those questions allows a small episteme to describe an admitted Method without pretending to satisfy every receiver. It also lets a rich candidate account remain prospectively useful without turning description quality into Method identity.

The claim-first order prevents representation and publication choices from selecting ontology.

## ME.8:11 - SoTA-Echoing {#sota-echoing}

| Source | Adopted or adapted contribution | Boundary and practitioner implication |
| --- | --- | --- |
| ISO/IEC/IEEE 24774:2021, [process-description elements](https://www.iso.org/standard/78981.html) | Adopt the discipline of describing purpose, outcomes, activities, tasks, information items, roles, and views only where the receiving description use needs them. | Description-side conformance does not establish process performance or FPF kinds. Practitioners still recover the admitted Method and each neighboring claim separately. |
| Daalhuizen and Cash, [Method content theory](https://doi.org/10.1016/j.destud.2021.101018) | Adapt the focus on content that helps a user understand and use a Method. | The source does not make one universal completeness schema. ME.8 uses named-use coverage and explicit omissions instead. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Adopt intended use, procedure, representation, tools, and adaptation conditions as recurring authoring questions. | Conceptual elements do not prove Method identity, obtaining relations, Work, or effectiveness. The EC-417 slices preserve those stops. |
| Stacey et al., [Methods as a form of engineering knowledge](https://doi.org/10.1017/dsj.2025.9), §§2.4 and 4.4 | Adapt the connection between procedure, required knowledge and the generation of inputs and results: make the reasoning steps recoverable where the receiving use needs them. | This strengthens instruction construction and the small receiving-use check. Explicit content alone does not supply tacit skill, establish learning or settle FPF's Method/description distinction. |
| Current FPF `A.3.1`, `A.3.2`, `C.2.1`, `C.29`, and `E.24.PUB` | Adopt exact Method identity, MethodDescription membership, episteme identity, representation correspondence, and publication separation. | These patterns supply the identity and boundary rules; ME.8 contributes the practitioner method for authoring a use-bounded edition and returning an honest lower result. |

Reopen the pattern when a representative user cannot state the named use without a universal field catalogue, when candidate status is repeatedly lost, or when the reader can find claims but cannot recover the promised operation, or when a current source offers a better way to select, explain or test the claims needed by a use at comparable effort.


## ME.8:End {#end}
