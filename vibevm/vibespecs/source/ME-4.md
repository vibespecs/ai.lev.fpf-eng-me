# ME.4 - Recover Methods and Decision-Relevant Contributions from Documentary Packages and Corpora: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.4:5 - Archetypal Grounding — EC-417 Release Assurance Package {#archetypal-grounding-ec-417-release-assurance-package}

Source/use boundary for this constructed case: the EC-417 package snapshot specified below, used as documentary Method guidance for the changed release decision; recover the decision-bearing slice, and return when that package, receiving use, or a relied-on condition changes. This one sentence supplies the ordinary one-source contract.

The EC-417 team receives a “release assurance methodology” containing a stage table, release checklist, supplier procedure, AI prompt, PLM and CI instructions, test-rig guidance, role descriptions, and stored evidence bundles. The receiving decision is whether its Method contributions and candidate reconciliation accounts can support a changed release arrangement.

The dossier uses open sections but preserves unlike kinds:

| Local section | Recovered entries and statuses | Decision-bearing slice |
| --- | --- | --- |
| Methods and candidate accounts | identified `M-HW-Verify`, `M-SW-Integrate`, `M-Supplier-Approve`, `M-Release-Authorize`; candidate `C-Evidence-Reconcile-Internal`, `C-Evidence-Reconcile-Supplier`, `C-AI-Trace-Review`, and proposed whole `C-EC-Release-v2` | Each Method or account keeps its source claims, required inputs/results, support, evidence, and limits. |
| descriptions, representations, and source claims | stage table, release checklist, supplier procedure, AI prompt, bundle records | These epistemes may describe or evidence a Method/account; none is promoted by its section. |
| Systems, support, and access | PLM, CI, test rig, AI provider, and provider-access condition | Availability and access are separate from Method identity and fit. |
| capabilities and assignments | safety competence, supplier-configuration responsibility, and release-authority assignment | Capability, responsibility, and authority are checked for the receiving use. |
| inputs, results, premises, and evidence | pinout schema, evidence bundle, verification result, confidentiality premise, and dated records | Each item keeps its direct kind and use. |
| relations | production/use, schema correspondence `A-17`, provider access, allocation, responsibility, and authority | Each relation is independently stated; no section or package edge supplies parthood. |

Two example dependency slices show why the full package is neither copied nor discarded:

- `M-HW-Verify` travels with its change input, verification-result meaning, rig condition, hardware capability, procedure provenance, and evidence window.
- `C-Evidence-Reconcile-Supplier` travels with the supplier procedure, signed-evidence condition, supplier-configuration responsibility, closure authority, four observed source cases, and the unresolved `A.3.1` identification question.

The supplier procedure's four reported cases remain a documentary source claim and evidence return in this recovery. Inspecting the underlying occurrence records to reconstruct a reusable way is a separate A.3.1.MR question; it does not silently occur inside ME.4.

The four identified Methods and the three individually scoped candidate accounts are potential ME.5 subjects for this use. PLM, rig, competence, authority, schema, evidence, and descriptions remain in their slices under their own kinds. `C-EC-Release-v2` remains a proposed-whole candidate account and may later be resolved by ME.7; its presence in the package creates neither a fifth Method nor `methodPartOf` facts.

### ME.4:5.1 - Two Documentary Roles and an Interview {#two-documentary-roles-and-an-interview}

This constructed case concerns a change to the release-assurance arrangement. Handbook H, edition 3, section 4, is an accepted maintained synthesis for reconstructing the supplier-evidence practice. Comparison C, edition 2, section 2, is the current comparator for the same receiving decision. Interview I, recorded on day D1, is offered as evidence about what happened during one release. These are local scenario references, not external studies.

| Source/use statement | Source-local contribution retained | Result and return |
| --- | --- | --- |
| H/3 §4; maintained synthesis; full source-local within the supplier-evidence practice; return if that section or the receiving scope changes. | Missing supplier evidence can stop release. The source proposes reconciliation before authorization and names a signed-evidence result. It also names supplier access and authorization conditions. | Recover the reusable-way claim at its existing status with those conditions; preserve access and authority as different subjects. Return to H/3 §4 for its meaning. |
| C/2 §2; current comparator; SoTA-first for this decision; return if a rival or the comparison basis changes. | A separately reviewed evidence bundle is proposed to reduce reliance on one supplier account. Its first result is a reviewed bundle or a named evidence gap. The claim's tested reach is limited to the comparison's cases. | Retain this alternative and its limits separately from H. Do not decide that two differently supported activities are one Method or that either replaces the other. |
| I/D1; occurrence evidence, not a third documentary recovery profile. | The interview reports one release episode but does not yet distinguish a reusable way from a one-off response. | For the one-occurrence question use A.15.1. If several occurrences create a candidate-recovery question, use A.3.1.MR; keep a record-only lower result when that is all the evidence supports. ME.18 is not an automatic next step. |

The first result is the two-source documentary dossier plus the honest occurrence-evidence return, not a merged release Method. A later semantic comparison must decide whether the two documentary contributions overlap, conflict, or complement one another.

If C's full argument becomes unavailable but a page-located excerpt remains, retain the excerpt and reopen only entries whose receiving use depends on the missing context. H's independent source-local result remains usable. Do not turn unavailable support into proof that C was false, or continue a gap-only recovery without its baseline.

## ME.4:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| source-taxonomy bias | Goal, procedure, rationale, framing, mindset, representation, role, or tool becomes a universal Method component kind. | Use those terms as source questions and place each returned claim with its actual subject. |
| diagram-containment bias | A box or lane is read as composition or parthood. | Require the direct relation and its evidence independently. |
| package-authority bias | Institutional or standards status becomes Method identity, fit, or effectiveness. | Separate source authority from the receiving claim and evidence. |
| procedure-only bias | A reusable action is extracted without rationale, applicability, input/result, support, or authority. | Carry the smallest dependency slice that can change qualification. |

## ME.4:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| Six local sections become six ontology kinds. | Call them open navigation and keep each entry's existing kind. |
| Everything actionable becomes a Method candidate. | Require a reusable way-of-doing account; keep support, capability, evidence, and authority under their direct kinds. |
| The package is reduced to a procedure. | Recover rationale, framing, intended use, inputs/results, support, evidence, and authority only where they change the receiving decision. |
| The whole package is copied for provenance. | Attach a bounded dependency slice to each Method/account and retain a source return to the package edition. |
| Unknown relation is inferred from adjacency. | Record the relation as unresolved and state what observation or source would settle it. |

## ME.4:10 - Architectural Rationale {#architectural-rationale}

A heavyweight package is a publication and practice carrier, not evidence that its visible organization is a Method structure. Preserving unlike kinds lets several useful representations coexist without forcing one-to-one correspondence among Method, Work, subject, description, capability/provider/support, allocation, and cultural structures.

The dossier is deliberately open. Its value lies in tracing source contributions to the receiving decision and retaining their dependency slices, not in a fixed number of sections or a universal element taxonomy.

## ME.4:11 - SoTA-Echoing {#sota-echoing}

| Source | Retained contribution | Use boundary |
| --- | --- | --- |
| Daalhuizen and Cash, [Method Content Theory](https://doi.org/10.1016/j.destud.2021.101018) | Goal, procedure, rationale, framing, and mindset as questions that prevent procedure-only recovery. | Static content variables and initial study population do not define FPF kinds, Method parts, or cross-domain effectiveness. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Core idea, representation, procedure, intended use, tool, ecosystem, and adaptation prompts. | Source elements remain questions and source claims, not a universal dossier ontology. |
| Stacey et al., [Methods as a form of engineering knowledge](https://doi.org/10.1017/dsj.2025.9) | Current comparison of engineering-Method knowledge and the placement of representations, framing, and rationale. | Conceptual comparison supplies no project Method identity or package parthood. |
| Current FPF `A.3.1`, `A.3.2`, `B.1.5`, and `F.18` | Method identity, MethodDescription membership, composition law, and name recovery. | The DPF adds the decision-bounded dossier and dependency-slice Method. |

Reopen when a current source or package case exposes a decision-bearing contribution that cannot retain its kind, provenance, role, and relation in the open dossier; when a source profile hides material receiving conditions; or when the ordinary one-package result acquires burden that its use does not need.


## ME.4:End {#end}
