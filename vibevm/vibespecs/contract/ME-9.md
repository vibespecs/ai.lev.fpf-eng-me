# ME.9 - Relate Method Representations across Their Different Uses {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

>
> **Primary working result:** a Method representation profile for one MethodDescription or candidate Method account. It relates logically complete use-bounded selections across Method actions, preserving source claims, cross-use correspondences, omissions, edition relations, keep-separate decisions and returns. A present profile can be sufficient working prose; when later use needs the basis retained, its rows carry their complete applicable `C.37` claim groups once.

## ME.9:0 - Use This When {#use-this-when}

Use this pattern when a current MethodDescription or candidate Method account must support several unlike Method-related actions or decisions, and the practitioner needs to relate their use-specific representation selections without pretending that one text, diagram, table, model, or view is the Method for every user. Begin with one ordinary question: which exact action or decision must this receiving System perform, and which Method claim must become visible for it?

The first useful result is one logically complete use selection in a Method representation profile. Name the Method or candidate status and source edition, receiver, exact action, needed Method claims, direct basis, applicable reliance and receiving result, material loss, disposition and return. Retain the complete C.37 group in its owning profile row when a later use needs it; an immediate sufficient selection needs no new record or standalone duplicate.

Use `C.37` or the applicable direct pattern and stop when only one action is current and no Method-specific cross-use profile is needed. Do not use ME.9 to select representations for an arbitrary entity, format unchanged content, establish publication or access, or create a collection or selected structure. ME.9 begins only when the missing result is the Method-specific organization of independently governed, use-bounded selections around one MethodDescription or candidate account.

## ME.9:0.1 - Working Distinctions {#working-distinctions}

| Position | What it contributes | What it does not establish |
| --- | --- | --- |
| Method representation profile | A Method-specific ensemble relating complete use-bounded rows to one MethodDescription or candidate account and recording cross-use correspondences, omissions, edition relations, and keep-separate decisions. | A new Method, MethodDescription edition, integrated view, collection, selected structure, or universal representation taxonomy. |
| embedded `C.37` same-use claim group | One receiver and exact action or decision; direct subject result; exact claim; optional A.2.4 first-use classification; material A.10 path and disposition; receiving result; exposure and loss; row disposition; return trigger. | The cross-use Method profile, subject-side direct results, reliance truth, authorization, capability, Work, or support-configuration choice. |
| MethodDescription or candidate account | The current Method claims and status from which representation needs are recovered. | That every claim is admitted, current, applicable, enacted, or supported by one representation. |
| `C.2.1` episteme | Claim-bearing content about a named `EntityOfConcern` under an effective scheme. | View conformance, mathematical correspondence, publication, reliance, or receiving permission. |
| `E.17.0` view result | An episteme that satisfies one stated viewpoint through its own conformance relation. | Conformance to another viewpoint, identity of the viewed entity, or fitness for another action. |
| `C.29` mathematical-lens result | A declared formal object and correspondence used to inspect selected aspects. | That an ordinary node-link diagram is a mathematical graph or that visual layout supplies an obtaining relation. |
| `E.24.PUB` publication result | A publication occurrence, form, and carrier for one selected episteme edition and audience use. | Truth, availability to every user, reliance, or actual Method use. |
| `A.22` selected structure | Independently identified constituents, selected obtaining relations, applied constraints, named use frame, and selection-use basis. | A structure inferred from colocation, diagram layout, profile membership, or a Method label. |

## ME.9:1 - Problem Frame {#problem-frame}

Method material serves unlike actions. A performer needs actions, inputs, results, guards, and stops. A method engineer compares contribution and variation. A support builder needs tool, resource, permission, and feedback positions. An assessor needs evidence, qualification windows, uncertainty, and reopen conditions. Project, process, and case viewpoints may expose different claims about the same independently admitted Method-related Work when each viewpoint can change the same exact action.

One representation rarely serves every action without hiding something. The Method Engineering problem is to relate several use-specific selections while preserving Method identity, candidate status, description currentness, WorkPlan versus Work, the direct authority of every selected result, and the limits of every carried claim.

## ME.9:2 - Problem {#problem}

Teams often place Method representations on one page and call the result an integrated Method view. The page then hides which receiver and action each item supports, which direct result identifies it, which exact claim is relied on, what it omits, whether a reliance or receiving result exists, and whether the subject is a Method, candidate account, WorkPlan, or admitted Work.

The opposite failure declares one canonical Method representation for every user. Performers, assessors, and support builders then reconstruct missing distinctions independently, so inconsistent guards, stale evidence, borrowed authority, and hidden omissions enter action without a return condition.

## ME.9:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Method-content coherence | Rows must return to one current MethodDescription or candidate account, while every receiver/action pair keeps its own selection and limits. |
| User-action fit | A representation should expose the claim that changes one action, while adding every available claim raises burden and hides stops. |
| Status preservation | Plans, candidate claims, and observed Work can help explain a Method, while representation cannot promote their status. |
| View discipline | Project, process, and case viewpoints can illuminate one Work occurrence, while viewpoint names alone establish neither a view nor co-use for another action. |
| Formal precision | A mathematical lens can expose a Method relation or unfolding, while a node-link appearance can overstate correspondence or graph structure. |
| Reliance proportionality | Reversible orientation may need only a direct result and visible limit, while consequential use may require an exact A.10 path and disposition. |
| Maintenance cost | A persisted profile can aid reuse and refresh, while every temporary presentation need not create a second C.37 account, collection, structure, or edition. |

## ME.9:4 - Solution {#solution}

Build the Method representation profile from the current MethodDescription or candidate account. For each receiver/action pair, recover its direct subject results and complete the applicable `C.37` selection. Then relate the uses through shared source claims, unlike omissions, edition relations, correspondences and keep-separate decisions. Existing claims and matching observations can suffice; new user Work is selected only for a use-changing question worth its attainable whole burden. Retain the complete basis where later profile use needs it, without a second C.37 copy.

**Local mantra.** *One receiver, one action, one C.37 claim group. Recover the direct result and exact claim; state reliance, receiving result, exposure, loss, disposition, and return. Relate rows through the Method profile without inventing a whole.*

### ME.9:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Name one Method-related use.** State the receiving System, exact Method Engineering decision or enactment-support action, situation, qualification window, and stop. Another action starts another `C.37` invocation even when the user, carrier, or Method is unchanged.
2. **Fix the Method subject and source account.** Name the admitted Method or candidate status and the current MethodDescription or candidate-account edition. Use ME.8 when the needed Method claims are absent or not current enough.
3. **Recover the claims needed by the action.** Select only the needed purpose, input/result, performer, capability, tool or resource, action or Work specification, variation point, guard, evidence, authority, support, feedback, or stop claims. Keep their actual subjects and statuses.
4. **Recover every candidate through its direct governor.** Use `C.2.1` for the claim-bearing episteme, `E.17.0` for a view with its own conformance relation, `C.29` for a mathematical lens and correspondence, `E.24.PUB` for publication, and `A.22` for a selected structure. A title, layout, Method label, carrier, or profile row supplies none of those results.
5. **Complete the use-bounded selection.** For the receiver and action, recover the direct subject result, exact claim, applicable A.2.4 classification and material A.10 reliance, direct receiving result, exposure and loss, disposition and return. Use the direct exit when one owner already supplies this complete answer. Otherwise apply C.37; retain its complete basis once in the owning profile row only when later use needs it.
6. **Compose the Method profile without flattening.** Connect the completed rows to one MethodDescription or candidate account. Record cross-use correspondences, conflicting omissions, edition dependencies, and keep-separate decisions. Shared profile membership creates no composite Method, super-view, collection, selected structure, or new description edition.
7. **Handle WorkPlan and Work as supporting subjects.** Preserve WorkPlan or Work status. Project, process, and case candidates may be co-recorded inside one row only when each has its own `E.17.0` conformance result, concerns the same independently admitted Work, and can change the same exact action. A candidate for another action belongs in another row.
8. **Resolve the live user-action question.** Direct claim inspection or an already matching observation may suffice for the present profile. Select a new probe only when a usability, interpretation or loss uncertainty can change the decision and its full design, reader, interpretation and displaced-Work burden is warranted and obtainable. For a selected probe, the named receiver retrieves the claim, distinguishes status or alternatives, performs the bounded action and applies its stop; report the actual result, not observed success from a plan. Return a defect to ME.8, C.37, the direct subject or receiving-result owner, ME.10, or the owning Method decision.

### ME.9:4.2 - Record the Result {#record-the-result}

Use this shape when a later use needs the profile retained. Its applicable distinctions govern an immediate working answer too, without requiring a stored row for every use.

| Result position | Required content |
| --- | --- |
| Method subject | Admitted Method or candidate status and current MethodDescription or candidate-account edition. |
| use boundary | Receiving System, exact Method-related action or decision, situation, qualification window, and stop. |
| required Method claims | Exact purpose, input/result, action, variation, evidence, support, authority, or stop positions needed by the action. |
| direct subject result | Independently governed `C.2.1`, `E.17.0`, `C.29`, `E.24.PUB`, `A.22`, or other direct result; explicit lower or failed result when it does not obtain. |
| exact use claim | The precise claim this action would carry from that direct result. |
| evidence and reliance | Optional A.2.4 first-use classification; when material, exact A.10 path, decision-use relation, currentness boundary, `RelianceDisposition`, and stop. |
| receiving result | Direct choice, gate, permission, authorization, acceptance, task, or domain result that permits, declines, or leaves the use unresolved. |
| exposure and loss | Method claims and distinctions exposed or preserved, and those omitted, withheld, transformed, or uncertain. |
| row disposition | `select`, `decline`, or `unresolved` for this exact action, with any narrowed use. |
| status boundary | Method, candidate account, MethodDescription, WorkPlan, Work, representation, view, publication, structure, reliance, and receiving-result statuses preserved. |
| return | Supported current result and basis, failure owner and correction target where needed, and reconsideration trigger; actual user-action observations only when obtained, with their limits. |
| profile relation | Cross-use correspondence, conflict, edition relation, omission, or keep-separate decision contributed by this row. |

### ME.9:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners stop asking one artifact to be the Method for every user and stop treating a profile as authority by colocation. A performer can receive an action-and-stop representation, an assessor an evidence-and-limit representation, and a method engineer a comparison or variation representation. Each row shows its own direct basis and exact permitted use, while the Method profile shows how those unlike selections return to one current source account.

## ME.9:7 - Conformance Checklist {#conformance-checklist}

- [ ] The profile names one admitted Method or candidate status and one current MethodDescription or candidate-account edition.
- [ ] Every row names one receiving System and exact Method-related action or decision, qualification window, and stop.
- [ ] Every row carries one complete C.37 claim group: direct subject result, exact claim, applicable A.2.4/A.10 layers, receiving result, exposure and loss, disposition, and return.
- [ ] A later use that needs retention can recover the complete selection basis once in its owning result; an immediate sufficient answer requires no new record or omission certificate.
- [ ] Each representation kind is established by its direct FPF governor rather than by layout, title, carrier, or profile membership.
- [ ] Method, candidate account, MethodDescription, WorkPlan, Work, representation, view, publication, carrier, reliance, receiving result, and selected structure remain distinct.
- [ ] Project, process, and case candidates concern the same independently admitted Work and are co-recorded only when each can change the same exact action.
- [ ] A mathematical-lens claim states the formal object, correspondence, intended use, and loss boundary under `C.29`; ordinary node-link material is not called a mathematical graph.
- [ ] Failed or missing direct results return the lower episteme and named gap rather than borrowing support from another layer.
- [ ] Current adequacy may be established by direct inspection or matching prior observations. A new user-action probe is selected only for a useful attainable question worth its whole burden; a claimed observed success or failure has its actual evidence and no wider capability, enactment, fit, transfer, worth or authority claim.

## ME.9:9 - Consequences {#consequences}

Method material becomes usable for unlike actions without multiplying Methods or hiding the source edition. A practitioner can recover why each row is selected, declined, or unresolved, what exact claim it carries, what it omits, and which change requires return. The profile adds the Method-specific cross-use account without copying the common representation-selection move.

The cost is maintaining the rows and profile relations actually needed by later use. Some attractive artifacts remain lower epistemes or fail a direct view, lens, publication, reliance, receiving-result or structure rule. Another action has another selection boundary, not automatically another stored record. A changed Method claim may reopen ME.8 or its source edition instead of being patched independently in several representations.

## ME.9:12 - Relations {#relations}

- ME.8 supplies the current MethodDescription or candidate-account claims and their use boundary; ME.9 relates complete use-bounded representation rows to the Method-specific uses that consume them.
- `C.37` governs one receiver/action selection, direct-result and reliance layers, exposure and loss, disposition, co-use, return and use-needed retention. ME.9 adds the cross-use Method profile and retains complete group content where that later use needs it.
- `C.2.1` identifies claim-bearing epistemes; `E.17.0` governs viewpoint conformance; `C.29` governs mathematical-lens use; `E.24.PUB` governs publication; `A.22` governs selected structures; `C.13` governs material collection treatment. ME.9 cannot borrow one result from another.
- `A.15.2` governs WorkPlan and `A.15.1` governs performed Work. A Method representation may rely on either as a supporting subject without changing its status or making ME.9 their general representation owner.
- `C.11.DUA` appraises a questionable user-study demand, including design, obtainable contribution and whole burden.
- ME.10 takes the direct exit when one owning result already supplies the complete one-result/one-use answer. It consumes ME.9 only when unlike Method actions need the cross-use profile; no second standalone C.37 copy is required.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-8#root; FPF spec://ai.lev/fpf-spec/contract/C-37#root, spec://ai.lev/fpf-spec/contract/C-2-1#root, spec://ai.lev/fpf-spec/contract/E-17-0#root, spec://ai.lev/fpf-spec/contract/C-29#root, spec://ai.lev/fpf-spec/contract/E-24-PUB#root, spec://ai.lev/fpf-spec/contract/A-22#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-me/contract/ME-10#root, spec://ai.lev/fpf-eng-me/contract/ME-22#root, spec://ai.lev/fpf-think-not/contract/NOT-6#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-9
