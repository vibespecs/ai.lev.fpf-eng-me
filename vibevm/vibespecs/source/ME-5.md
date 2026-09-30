# ME.5 - Qualify Individual Methods, Candidate Accounts, and Local Connections: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.5:5 - Archetypal Grounding — EC-417 Individual Stops {#archetypal-grounding-ec-417-individual-stops}

The EC-417 dossier supplies four identified Methods and several candidate accounts. The bounded use is a safety-relevant release arrangement in which signed evidence must exist before safety closure, confidential supplier geometry must stay outside the AI provider, and decision Work remains with admitted human Systems under separate covering assignments and permission or direct decision-authority relations.

| Subject and prior status | Individual result | ME.5 return |
| --- | --- | --- |
| `M-HW-Verify`, identified Method | accepts the affected change and pinout version; produces a verification result with named rig and hardware capability conditions | qualified for the bounded use |
| `M-SW-Integrate`, identified Method | accepts explicitly versioned provisional or signed pinout evidence; its integration record preserves the exact edition, any provisional uncertainty, and the edition actually used; later signed evidence supersedes a provisional edition only for safety-closure reliance while the earlier use and provisional-to-signed relation remain traceable; software remains reversible until `D-1` | qualified under the evidence-version, history, closure-reliance, and reversibility conditions |
| `M-Supplier-Approve`, identified Method | produces signed supplier approval or the explicit missing-approval stop; requires supplier-configuration responsibility and evidence access | qualified under the named access and responsibility conditions |
| `M-Release-Authorize`, identified Method | consumes the safety result and named evidence conditions; admitted human System `ReleaseDecider-17` performs `W-ReleaseDecision-17` under covering assignment `ASG-ReleaseDecision-17` and independently supported direct relation `AUTH-ReleaseDecision-17`; returns release, withhold, or next-slot authorization | qualified for the bounded Work, assignment, and authority scope; none proves the others |
| `C-Evidence-Reconcile-Internal`, candidate account | eight internal cases support an account in which the versioned provisional edition, uncertainty, and earlier integration use remain traceable through reconciliation to later signed evidence before closure | retained as a candidate account; `A.3.1` identification remains open |
| `C-Evidence-Reconcile-Supplier`, candidate account | four supplier-originated cases and one held-out supplier case support a signed-evidence branch | retained as a candidate account; `A.3.1` identification remains open |
| `C-AI-Trace-Review`, candidate account | the account specifies a trace-suggestion contribution; `TraceReviewer-17` performs the accept/reject Work under `ASG-TraceReview-17` and `PERM-TraceAcceptReject-17`, while the AI provider holds neither | retained as a human-governed candidate account |

The `provider-default AI proposal` is outside ME.5's present qualification subjects because no identified Method or candidate Method account has been supplied for it. Independently, implementing the proposal would disclose confidential geometry to the AI provider, and the proposal names no admitted human decision performer, covering assignment, or permission/authority relation. Those failures would block this use even if a candidate account were supplied.

Local schema correspondence `A-17` maps signed or explicitly provisional pinout-version fields to the integration bundle and preserves the exact edition and uncertainty used. Five stored bundles support that mapping for the named schema editions. The mapping preserves the provisional basis after later signed evidence becomes the safety-closure basis. This is a local connection result, not whole compatibility.

Two honest stops are now available. A project needing only hardware verification can stop with the qualified `M-HW-Verify`; no architecture comparison is required. A project investigating supplier reconciliation can stop with the retained `C-Evidence-Reconcile-Supplier` account and its open `A.3.1` question. EC-417 continues to ME.6 only because the combined safety allocation, board timing, evidence routing, and recovery burden differ among whole alternatives.

## ME.5:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| fit-score bias | Unlike contribution, capability, authority, evidence, and burden claims collapse into one number. | Return the decision-changing conditions and truthful branch instead of an opaque total. |
| candidate-upgrade bias | “Qualified candidate” is read as identified Method. | Repeat the account status in the verdict and state the open `A.3.1` condition. |
| compatibility bias | One feasible handoff or schema mapping becomes whole fit. | Call it a bounded local connection and route combined questions to ME.6. |
| decomposition bias | Each support System, role, or evidence item is evaluated as a Method candidate. | Accept only identified Methods and candidate Method accounts as qualification subjects. |

## ME.5:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “This account fits, so it is a Method.” | Retain or exclude the account and send identity to `A.3.1`. |
| “All individual Methods pass, so the architecture is compatible.” | State the unresolved combined structure and use ME.6 only when it changes the decision. |
| “The adapter works, so integration is solved.” | Bound the adapter-feasibility result; compare placement, versioning, responsibility, and failure in ME.6. |
| “Use the same checklist for every subject.” | Ask only applicable questions but preserve the common result positions needed by the decision. |
| “More evidence is always safer.” | Select evidence by consequence and claim; stop when the bounded decision can be made honestly. |

## ME.5:10 - Rationale {#rationale}

Individual suitability and whole architecture answer different questions. A Method can be usable alone yet overload a shared Agent when combined with others. A candidate account can be useful evidence for design while still failing Method identification. Keeping the individual and architecture results separate protects both cheap stops and escalation when combined questions remain.

## ME.5:11 - SoTA-Echoing {#sota-echoing}

| Source | Retained contribution | Use boundary |
| --- | --- | --- |
| Henderson-Sellers and Ralyté, [Situational Method Engineering review](https://opus.lib.uts.edu.au/handle/10453/13456) | Situational construction, selection, and adaptation questions. | Source-local fragment and process ontologies do not determine FPF subject status. |
| Daalhuizen and Cash, [Method Content Theory](https://doi.org/10.1016/j.destud.2021.101018) | Goal, procedure, rationale, framing, and mindset questions relevant to individual content and use. | These variables do not become universal qualification dimensions or Method parts. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Intended use, scope, representation, procedure, tool, ecosystem, and adaptation conditions. | Conceptual elements guide questions; current project evidence supplies the verdict. |
| Current FPF `A.3.1`, `C.18`, and `G.5` | Method identity, candidate generation when needed, and bounded family/selector results. | ME.5 adds status-preserving individual qualification and the local-connection boundary. |

Reopen when a current source or use shows that an individual question cannot be judged without a named whole structure, or when a repeated ME.6 finding can be prevented by one affordable individual check.


## ME.5:End {#end}
