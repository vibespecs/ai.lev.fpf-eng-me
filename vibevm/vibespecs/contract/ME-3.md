# ME.3 - Build or Reconsider Situational Method Requirements and Fit Criteria {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

>
> **Primary working result:** one **situational Method-criteria result** that states the receiving Work and result, required Method contributions, performer capabilities, technical and organizational conditions, allowable variation, non-negotiable conditions, burden limits, evidence needs, and truthful acceptance or stop observations without selecting or admitting a Method. A question about one disputed criterion returns a supported recommendation to retain or change it, together with the criterion's current force and available amendment route.

## ME.3:0 - Use This When {#use-this-when}

Use this pattern when a Method, an established-family or project-local grouping choice, or a proposed Method/Work/support structure may fail in the project's situation. Enter when the practical question concerns the receiving result, performer capabilities, technical or organizational conditions, variability, evidence, authority, or acceptable burden and those conditions are not yet explicit enough for individual qualification or architecture comparison.

Begin with the situation family, intended or current Work, receiving professional result, and the level of the Method decision. State the contributions that a Method or several Methods must make without preselecting which candidate supplies them. Place every resulting criterion with the Method, description, performer capability, covering Work assignment, permission relation, decision-authority relation, performed Work, decision result, support/access relation, responsibility, cultural subject, or receiving result it actually concerns.

The first useful result is a bounded set of criteria with subjects, allowed variation, evidence needs, satisfaction observations, and stops. A criterion can be ready for later use even when no candidate currently meets it. Enter also when the present question concerns the justification of a criterion itself. That use can finish with a supported requirement recommendation and the criterion's current force or amendment limit, without selecting a Method.

Do not use this pattern as a generic product-requirements template. Criteria do not identify, admit, select, qualify, or compose a Method or establish present or future fit. Product acceptance, Method identity, individual qualification, and architecture choice remain separate results.

## ME.3:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| situation family | The recurring class of receiving Work and conditions for which criteria are intended, with important variation and exclusions explicit. |
| receiving Work and result | The dated Work occurrence or intended occurrence and the professional result it must produce or preserve. They are not the Method. |
| required Method contribution | A reusable action, result, or preserved condition needed from one Method or from named Method relations, stated before assigning it to a candidate. |
| criterion subject | The actual object or relation constrained by a criterion: Method/account content, MethodDescription, performer capability, covering Work assignment, permission relation, decision-authority relation, performed Work, decision result, support/access, responsibility, cultural relation, or another domain subject. |
| performer capability | An ability needed to enact or judge a contribution. It is distinct from responsibility, access, assignment, permission, and decision authority. |
| Work assignment | A named assignment occurrence whose holder is one admitted System and whose scope and window cover specified Work. The assignment alone establishes neither permission, decision authority, performed Work, nor a decision result. |
| permission relation | An independently supported relation permitting a named System to perform a specified act within a stated subject, scope, window, and basis. It does not create an assignment, prove performance, or confer decision authority beyond that exact permission. |
| decision-authority relation | An independently supported direct relation under which a named System may issue a named decision result. Its subject, decision scope, window, basis, and evidence for reliance are explicit; assignment, performed Work, capability, responsibility, access, and acceptance need separate evidence. |
| allowable variation | A range or branch that may change while the receiving result and non-negotiable conditions remain protected. |
| burden limit | A bound on time, attention, capacity, delay, coordination, cost, or another named burden at its actual participant, scope, and window. |
| evidence need | The observation or record required before a later decision may rely on criterion satisfaction. It is not satisfaction by itself. |
| acceptance or stop observation | The observable condition under which the criterion can be passed to a later decision or must stop that route. It does not accept a Method or product by itself. |

## ME.3:1 - Problem Frame {#problem-frame}

Situational Method Engineering asks practitioners to fit a way of working to its context. Engineering-design research adds useful questions about a Method's goal, procedure, rationale, framing, mindset, intended use, representation, tool, and ecosystem. A project also faces domain constraints that do not belong inside the Method: protected information, performer capability, authority, shared capacity, evidence timing, reversibility, and the acceptance conditions of the receiving result.

When these unlike claims are placed in one “method requirements” list, description content becomes a Method part, culture becomes a performer property, authority becomes skill, and product requirements become proof of Method fit. A useful criteria result keeps the connected situation visible while returning each claim to its actual subject.

## ME.3:2 - Problem {#problem}

A universal checklist invites premature scoring. It may reward a well-written MethodDescription even when performers lack capability, declare a Method unsuitable because a provider arrangement fails, or hide an architecture-level peak-load conflict inside an individual candidate score.

The project then appears to have objective fit criteria, but nobody can say what must change: the Method account, the description, the support System, the covering Work assignment, a permission or decision-authority relation, the Work arrangement, or the receiving result's own acceptance rule.

## ME.3:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Comparability | Shared questions help compare alternatives, while different subjects need different criteria and evidence. |
| Situation specificity | Local constraints change the decision, while a one-project list may overfit and block reuse. |
| Candidate neutrality | Criteria should expose viable alternatives, while familiar candidates can be smuggled into the wording. |
| Flexibility | Professional Work must adapt, while non-negotiable safety, evidence, authority, and burden bounds must hold. |
| Clarity | Source-side content prompts reveal omissions, while they can be mistaken for universal Method parts. |
| Economy | Cheap observable stops save effort, while high-consequence claims need stronger evidence. |

## ME.3:4 - Solution {#solution}

Build criteria from the receiving situation outward. State required contributions and conditions, assign each criterion to its actual subject, preserve allowed variation, and defer every fit or selection verdict to the pattern that evaluates the relevant subject or structure. For a disputed criterion, start with its existing context and the appraisal in §4.4; build or update other criteria only where that question needs them.

Recognition is cheap: recurring Work, a changed constraint, or one plausible capability, access, authority, evidence, or burden failure is enough to expose a criterion question. Assurance is later and row-specific: the named observation, edition, and window must support satisfaction before qualification or architecture work may rely on that row.

### ME.3:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Bound the situation family.** Name representative Work, receiving result, affected subjects, decision window, recurrence expected, important variants, and ordinary exclusions. Keep project, process, and case views as descriptions of the same Work when they are used.
2. **State required contributions before candidates.** Describe the reusable actions, results, or preserved conditions that one Method or named Method relations must contribute. Do not write a familiar candidate's current procedure as the requirement unless that exact feature is independently non-negotiable.
3. **Use source prompts without importing kinds.** Ask what goal, procedure, rationale, framing, mindset, intended use, representation, tool, scope, and adaptation conditions a source makes visible. Place the answer with its actual subject. A stated mindset may be description content; an obtaining capability or cultural relation needs separate evidence.
4. **Recover conditions around enactment.** State performer capabilities, technical and organizational conditions, inputs, support/provider access, responsibility, covering Work assignments, permission and decision-authority relations, evidence timing, reversibility, and other Work or result constraints. Keep these conditions distinct from one another and from the performed Work and its decision result.
5. **Separate variation from invariants.** Name lawful branches, substitutions, timing ranges, and local adaptations. Mark non-negotiable result, safety, confidentiality, authority, or evidence conditions explicitly. If a criterion's justification is the live question, use §4.4 to appraise it while retaining its current force. An already justified criterion needs no new appraisal.
6. **Set burdens at the right level.** Attach time, attention, capacity, delay, meeting, or cost limits to a participant, Work scope, and window. Keep individual burden distinguishable from combined peak demand and burden transferred to another participant or period.
7. **Name evidence and observations.** For every decision-changing criterion, state what record or observation a later evaluation needs, its edition or window when material, and what would count as satisfied, failed, or unknown. Do not turn the requested evidence into a fit verdict.
8. **State acceptance, stop, and reopen rules.** Say when the criteria set is adequate for its next use, which missing fact stops that route, and which situation or source change requires rebuilding it. A stop may route to capability, support, authority, product, or Work redesign rather than Method selection.
9. **Return without selecting.** Publish the criteria by subject and decision level. Send individual subject questions to ME.5 and combined structure questions to ME.6 only when their own entry conditions hold.

### ME.3:4.2 - Record the Result {#record-the-result}

Use the rows that carry the present result. For a disputed criterion, retain the relevant existing context and return the recommendation described in §4.4.

| Result position | Content for the present use |
| --- | --- |
| use and situation family | Receiving Work/result, decision level, scope, window, representative variations, and exclusions. |
| required contributions | Candidate-neutral Method contributions and the result or preserved condition each must support. |
| criterion rows | Criterion ID, actual subject/relation, requirement or bound, allowed variation, non-negotiable status, and decision level. |
| capability, assignment, permission, and authority | Required performer capabilities; separate responsibility and access conditions; covering Work assignments; permission and direct decision-authority relations; and evidence for each. |
| technical and organizational conditions | Inputs, support/provider conditions, evidence timing, reversibility, coordination, and other situated constraints. |
| burden limits | Participant, Work scope, time window, bound, measurement basis, and transferred-burden warning. |
| evidence and disposition | Required observation or record and the condition for `satisfied`, `failed`, or `unknown` in later use, without a fit or selection verdict. |
| disputed requirement, when this question is live | Supported retention or change recommendation, the protection and burden that justify it, current force, and the available amendment route or limit needed by its recipient. |
| stop and reopen | Missing fact or failed non-negotiable that stops a route, adequate-next-use condition, and situation/source change that reopens the set. |

### ME.3:4.3 - What Changes in Practice {#what-changes-in-practice}

Teams stop asking whether a methodology “fits the context” as one opaque question. They can see whether the live issue is a Method contribution, a description gap, missing capability, covering assignment, permission, decision authority, provider access, Work timing, receiving-result condition, or combined burden. Later qualification and architecture comparison receive explicit conditions instead of a precomputed winner.

### ME.3:4.4 - Appraise a Disputed Criterion {#appraise-a-disputed-criterion}

Use C.11.DUA §4.3 when the practitioner needs to decide whether a Method criterion or protective requirement is justified. Recover the person, system or receiving result it protects, the particular failure or exposure, the governed activity or quantity, the evidence and threshold basis, and the protection the requirement adds under these conditions. Compare that contribution with the burden, delay and displaced protective work. Use the relevant domain judgement and measurement or causal analysis where the question needs them; a label such as safety does not supply that basis.

Return supported retention, tightening, revision, replacement or removal only among meaningful alternatives. Keep the requirement's current force and the authority and time needed to change it explicit where they determine the feasible continuation. A recommendation can be complete while amendment remains unavailable. Continue under the current allowed options until the governing authority or agreement changes the requirement; if none meets the receiving need within the window, return that limitation. A later amendment does not restore an opportunity already lost.

Carry the useful reason and limit in the same criteria or recommendation result. Finish when it answers the present question at a supported strength. Choose a further study only when its obtainable result could change that answer enough to warrant the full burden.

## ME.3:7 - Conformance Checklist {#conformance-checklist}

Apply these questions to the criteria being established or appraised and to the present use of the result. Existing relevant context can supply the answer.

- [ ] The criteria name a situation family, receiving Work/result, decision level, scope, window, variations, and exclusions.
- [ ] Required Method contributions are stated before candidate assignment.
- [ ] Every criterion names its actual subject or relation rather than hiding it under “method fit”.
- [ ] Method/account content, MethodDescription, performer capability, responsibility, support/access, covering Work assignment, permission relation, decision-authority relation, performed Work, decision result, culture, and receiving-result claims remain distinct.
- [ ] Capability, assignment, permission, and decision authority imply none of one another; an assignment or authority relation does not prove performed Work or its decision result.
- [ ] Allowable variation and non-negotiable conditions are explicit.
- [ ] When a criterion's justification is disputed, the recommendation compares its actual protective contribution and burden and distinguishes that judgement from current force and the feasible amendment route.
- [ ] Every burden limit names participant, Work scope, time window, bound, and measurement basis.
- [ ] Every decision-changing row names evidence and `satisfied | failed | unknown` observations.
- [ ] The result states acceptance-for-next-use, stop, and reopen conditions without selecting or admitting a Method.
- [ ] Individual and combined structure questions are routed to different later results.

## ME.3:9 - Consequences {#consequences}

The project obtains criteria that say what must hold and where, rather than a generic context score. Missing capability can trigger preparation, an access failure can trigger support redesign, a product stop can withhold release, and an architecture burden can remain open without blaming an individual Method.

The cost is more explicit subject placement and fewer easy rankings. Some criteria remain unknown until evidence or a candidate account is available, and a complete criteria set still makes no selection.

## ME.3:12 - Relations {#relations}

- ME.1 or an equivalent result supplies the Method, family/local-grouping, or relation focus. ME.2 may supply inspectable alternatives and source limits. When equivalent content already exists, ME.1 and ME.2 need not be applied first.
- `A.3.1` governs Method identity and applicability. ME.3 criteria identify or admit no Method.
- `A.15.6` supplies project-subject distinctions. When building situational criteria, distinguish the Method, Work, description, capability, tool or support arrangement, and viewpoint.
- ME.5 qualifies one identified Method or candidate account against applicable rows without turning the criteria into admission or whole fit.
- ME.6 compares combined Method, Work, allocation, support, authority, description, subject, capability, or cultural structures when several-structure relations change the decision.
- `C.11` or the applicable domain decision Method may consume later qualification and architecture results. The ME.3 criteria set itself selects nothing.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-1#root, spec://ai.lev/fpf-eng-me/contract/ME-2#root; FPF spec://ai.lev/fpf-spec/contract/C-11#root, spec://ai.lev/fpf-spec/contract/A-10#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-chk/contract/CHK-1#root, spec://ai.lev/fpf-eng-chk/contract/CHK-6#root, spec://ai.lev/fpf-eng-me/contract/ME-11#root, spec://ai.lev/fpf-eng-me/contract/ME-13#root, spec://ai.lev/fpf-eng-me/contract/ME-25#root, spec://ai.lev/fpf-eng-me/contract/ME-4#root, spec://ai.lev/fpf-eng-me/contract/ME-5#root, spec://ai.lev/fpf-eng-me/contract/ME-6#root, spec://ai.lev/fpf-eng-me/contract/ME-6-MC#root, spec://ai.lev/fpf-eng-me/contract/ME-8#root, spec://ai.lev/fpf-eng-sie/contract/SIE-1#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-3
