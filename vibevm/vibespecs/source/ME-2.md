# ME.2 - Recover a Reusable Method Repertoire and Its Lineages: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.2:5 - Archetypal Grounding — EC-417 Release-Evidence Repertoire {#archetypal-grounding-ec-417-release-evidence-repertoire}

The EC-417 project needs an inspectable repertoire for a Method-relation comparison around one safety-relevant controller release. The relevance criterion is narrow: an entry must contribute to verification, integration, supplier evidence, release authority, or evidence reconciliation for the named receiving result. The following identifiers and editions are local scenario records; they are not population evidence.

| Subject and status | Claim-bearing basis and edition | Supported relations or lineage | Use limit or missing position |
| --- | --- | --- | --- |
| `M-HW-Verify`, identified Method | existing `A.3.1` identity result; hardware-verification procedure `HV-6`; EC-417 verification records | its verification result is an established input to release authorization for this use | no supported lineage to another Method and no general effectiveness claim beyond the cited use window |
| `M-SW-Integrate`, identified Method | existing `A.3.1` identity result; firmware-integration procedure `FI-4.8`; integration records | description edition `FI-4.8` succeeds `FI-4.7`; this is document-edition lineage, not a claim that the Method became a different or better Method | transfer beyond controller firmware `4.8` and the named toolchain is untested |
| `M-Supplier-Approve`, identified Method | existing `A.3.1` identity result; supplier pinout-approval procedure `H17-3`; signed approvals and missing-approval stops | signed or explicitly missing approval supplies an input/stop to the release decision; `H17-3` documents an adaptation from `H17-2` | whether the documented adaptation changed Method identity is unresolved |
| `M-Release-Authorize`, identified Method | existing `A.3.1` identity result; release checklist `RC-17.3`; named authorization results | consumes verification, evidence-state, and authority conditions for EC-417 | no family relation with the other three Methods is established |
| `C-Evidence-Reconcile-Internal`, candidate Method account | eight internal cases in evidence dossier `ER-EC417-12+1` | documented derivation from the eight internal occurrences and their artifact traces | `A.3.1` identity and transfer to supplier-originated changes remain open |
| `C-Evidence-Reconcile-Supplier`, candidate Method account | four supplier-originated cases plus the held-out thirteenth case in `ER-EC417-12+1` | documented derivation from those cases; the held-out case supports the supplier branch without proving a Method | `A.3.1` identity, population scope, and relation to the internal account remain open |
| `C-AI-Trace-Review`, human-governed candidate Method account | AI trace prompt `ATP-2`, confidentiality rule, human-decision record set `HDR-TraceAcceptReject-17`, and decision-result set `RES-TraceAcceptReject-17` | `ATP-2` contributes prompt-and-guard description content to the candidate account; `HDR-TraceAcceptReject-17` evidences the bounded human Work set `W-TraceAcceptReject-17` performed by `TraceReviewer-17` and links each occurrence to its corresponding result in `RES-TraceAcceptReject-17`; the candidate account is documented as derived from `ATP-2`, `HDR-TraceAcceptReject-17`, and `RES-TraceAcceptReject-17`; the AI provider remains a separate System | no evidence of autonomous authority, effectiveness, or transfer outside the named information boundary; none of these relations establishes Method identity, family membership, causation, superiority, applicability, or composition |

For the `D-21` through `D0` use window, the project relies on the exact contributions and conditions in the table. If a new export or edition changes only their layout while the relied-on claims, configuration, access and use remain the same, retain the repertoire without a new search, trial or renewal record. If `FI-4.8` instead loses coverage for a changed controller or toolchain, or an actual permission or qualification window ends, reopen or suspend that affected use even before the planned review date. Keeping the old edition identified does not authorize continued reliance on defeated premises. Reconsider only the affected source-use row, preserve the earlier claim for its supported conditions, and keep the needed limitation with the result for later receivers.

The existing project-local locator `LG-EC417-ReleaseMethods` contains only the four identified Methods for the bounded release comparison. Its criterion is contribution of a verification, integration, supplier-approval, or authorization result to EC-417. The three candidate accounts remain adjacent repertoire entries with their own statuses; a wider source-inspection list does not silently add them to the Method grouping. Family status remains unresolved. No family membership, fifth Method, or composite Method follows.

Description-side material stays separate. Existing `A.3.2` results identify `HV-6`, `FI-4.8`, `H17-3`, and `RC-17.3` as MethodDescriptions of the four already identified Methods. The stage table, bundle records, AI prompt, and evidence grades remain other claim-bearing epistemes or artifacts. They are not additional Methods. The two reconciliation records and the AI review record remain candidate accounts, so no `A.3.2` MethodDescription is asserted for them.

Proposed-whole account `C-EC-Release-v2` is recorded outside the repertoire membership table as an architecture subject. It cites contributions from the four Methods and three accounts, but that source relation establishes neither a whole Method nor `methodPartOf`.

The repertoire stops honestly with four missing positions: no established Method family covers the local grouping; no source establishes a Method-lineage relation among the four identified Methods; the same-Method or distinct-Method relation between the two reconciliation accounts is unresolved; and the AI account lacks transfer and effectiveness evidence. Those gaps do not prevent ME.5 from qualifying individual subjects or ME.6 from comparing named structures. They prevent family, ancestry, superiority, and composite claims.

## ME.2:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| repository-completeness bias | A large collection is treated as a complete repertoire. | Bind relevance to one use and list missing positions explicitly. |
| package-kind bias | Sections, tools, roles, and artifacts are all called Methods. | Recover each subject's actual kind or provisional status before grouping. |
| lineage-progress bias | A later edition or descendant is assumed better or more effective. | Record only the supported provenance relation; evaluate worth and causality separately. |
| family-by-co-listing bias | Entries under one heading become a Method family. | Cite the independent family basis or call the result a project-local grouping. |
| freshness-by-date bias | The newest publication is assumed applicable to the current use. | Separate source edition, source-use currentness, evidence window, and applicability. |

## ME.2:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “The repository contains 40 Methods.” | Reclassify exact entries; count only Methods already identified under `A.3.1`. |
| “These practices share a history, so they form one family.” | Separate the supported lineage relation from the independently governed family question. |
| “Version 3 supersedes version 2, so it is better.” | Record edition succession and compare the decision-bearing contribution under its own evidence. |
| “We observed the procedure, so the Method belongs in the repertoire.” | Keep the observation as occurrence evidence or a candidate account until Method identification. |
| “A blank row makes the repertoire incomplete and unusable.” | Name the missing position and whether it blocks, weakens, or does not affect the receiving use. |

## ME.2:10 - Rationale {#rationale}

A repertoire becomes reusable when its users can distinguish statuses and trace provenance. Source lineage can explain where an edition, account, or variant came from, but it cannot answer whether a Method exists, whether two Methods form a family or whole, whether one caused an outcome, or whether the latest variant is preferable. Those questions have different subjects and governors.

The repertoire distinguishes Methods, performed Work, descriptions, variants, capability and tools, including cases where several representations concern the same Method. These distinctions keep a source document's organization from determining the kind of thing each passage describes. Method Engineering literature supplies search and reuse practices; FPF supplies the status and relation boundaries needed to use their contributions across projects.

## ME.2:11 - SoTA-Echoing {#sota-echoing}

| Source | Retained contribution | Use boundary |
| --- | --- | --- |
| Henderson-Sellers and Ralyté, [Situational Method Engineering: State-of-the-Art Review](https://opus.lib.uts.edu.au/handle/10453/13456) | Method-base lineage, reusable source material, situational construction, and explicit Method Engineering traditions. | Source-local fragments and construction terms do not determine FPF kinds, family membership, or composition. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Method ecosystem, core idea, representation, procedure, intended use, tool, and adaptation questions. | The elements guide source recovery; they are not an imported ontology or universal repertoire schema. |
| Current FPF `G.2`, `G.5`, and `G.11` | Refreshable SoTA sourcing when needed, truthful family or local set results, and edition/currentness discipline. | These patterns do not identify repertoire Methods or turn co-listing and lineage into selection, family, or merit. |

Reopen when a relied-on source contribution, its support or its applicability changes, a missing position becomes available, an `A.3.1` result changes a subject's status, a family or lineage relation gains or loses support, or the named comparison requires an alternative outside the current relevance boundary. Age or edition succession alone establishes none of these changes.


## ME.2:End {#end}
