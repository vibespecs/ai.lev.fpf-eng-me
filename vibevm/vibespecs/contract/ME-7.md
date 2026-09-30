# ME.7 - Resolve a Proposed Method Whole into Obtaining Relations or a Candidate Account {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

>
> **Primary working result:** either a bounded composition result whose whole, participants, and load-bearing relations are independently supported, or a **prospective candidate Method account** with proposed relation sets, guards, variation, recovery, stops and unresolved conditions needed by its receiving use. Writing the account creates neither the Method nor an obtaining architecture.

## ME.7:0 - Use This When {#use-this-when}

Use this pattern when a proposal already names an intended Method whole—often a methodology, operating model, playbook, integrated process, or local way of working—and the next decision needs to know what can truthfully be said about that whole now.

Begin with the proposal's intended result, participants, relation claims, guards, burdens, unresolved conditions, and selection reason. Recover the whole semantics needed for identification before choosing the result branch.

The first useful result is deliberately two-branched. If the whole and participant Methods are identified and the required relations are shown to obtain, record the bounded composition result. Otherwise return the strongest prospective account or lower claim that the evidence supports. That account can finish a present design comparison while whole identity or relation truth remains unresolved. Select later realization or testing only when its obtainable contribution warrants the full burden and is feasible.

Do not require prior performance of ME.6 when equivalent proposal content is already available. Do not treat a coherent description, selected architecture, WorkPlan, tool implementation, or successful first trial as Method construction or identification by itself.

## ME.7:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| proposed Method whole | A claim that several contributions form one reusable Method for a stated use. It may be no more than a candidate account. |
| whole semantics | Intended result or preserved condition, reusable procedure or invariant, applicability, participants, permitted variation, bounds, and reidentification rule. |
| participant status | Whether each named participant is an identified Method, candidate account, other kind, or unresolved subject. |
| obtaining composition result | A result about an identified whole and identified participant Methods whose required `B.1.5` relations are independently shown to obtain for the bounded claim. |
| prospective candidate account | An episteme proposing a possible reusable whole while identity or relation conditions remain unresolved. |
| relation set | Named proposed or obtaining composition, order, result-use, allocation, support, authority, or other relations. Their truth statuses remain explicit. |
| realization/test WorkPlan | A plan for later Work that could implement the proposal and return observations. It is not performed Work or evidence that the Method exists. |

## ME.7:1 - Problem Frame {#problem-frame}

Method Engineering often produces coherent proposals before the proposed practice exists. Situational Method Engineering and design-Method research offer useful construction and adaptation moves, while FPF keeps the proposed account, world-side Method, MethodDescription, WorkPlan, performed Work, and obtaining relations distinct.

A proposed whole can still be valuable. It can state an invariant, guards, variants, participant roles, stops, and a bounded trial. The error is reporting possible-future content as already obtaining.

## ME.7:2 - Problem {#problem}

One failure declares a whole whenever a document gives several steps a shared name. Another refuses to state anything useful until a mature Method has already been identified. A third treats participant co-use, Work order, or a successful tool integration as `methodPartOf` evidence.

The first error overclaims, the second prevents learning, and the third confuses several relation structures. ME.7 needs a positive lower branch that supports present comparison or later realization while keeping uncertainty explicit.

## ME.7:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Useful proposal | A project needs a coherent possible-future account, while coherence does not identify a Method. |
| Composition evidence | Participant Methods and relations may be supported unevenly, while one missing load-bearing relation can defeat the whole claim. |
| Variation | A reusable Method permits bounded variation, while unlimited adaptation destroys reidentification. |
| Trialability | A WorkPlan can make uncertainty testable, while planned or performed Work does not backdate Method existence. |
| Honest lowering | A lower result must remain actionable, while it cannot hide unresolved identity or relation claims. |

## ME.7:4 - Solution {#solution}

Recover the proposed whole's semantics, test whole and participant identity separately from relation truth, and return the strongest branch the evidence supports.

### ME.7:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Name the receiving use.** State the result or preserved condition, situation family, intended users or performers, consuming decision, configuration or edition, and time window.
2. **Recover whole semantics.** State the reusable operations or invariant, entry and exit, applicability, participants, permitted variation, bounds, stops, and reidentification rule. If these cannot be stated, return the missing-account question.
3. **Preserve participant statuses.** Identify each Method under `A.3.1` where supported. Keep candidate accounts and other subjects at their existing statuses.
4. **Name the relation sets.** State every load-bearing proposed or obtaining relation, including Method composition, Work order or overlap, result use, allocation, support/provider access, authority, and description correspondence as applicable. Do not infer one relation from another.
5. **Test the positive branch.** Record an obtaining composition only when the whole and parts are identified as Methods and the required `B.1.5` relations are shown to obtain within the bounded claim.
6. **Return the prospective branch when needed.** State the candidate whole, participant statuses, proposed relation sets, guards, adapters, alternatives, recovery, variation points, burdens and unresolved conditions needed for the receiving use. A traceable proposal can answer that use while its stronger whole claim remains unresolved.
7. **Lower independently.** When whole semantics, identity, or one relation remains too weak even for a useful candidate, return the supported fragment, relation claim, WorkPlan question, or stop. Do not pad the account to look complete.
8. **Choose a useful continuation when needed.** Use C.11.DUA to compare the result a realizable implementation or trial could add with its full burden, including access, allocation, authority and the available window. When that Work is selected, name its observations, acceptance and failure conditions, authority and reconsideration rule; prepare a WorkPlan where coordination needs one. Otherwise finish with the supported account or lower result and the limitation that matters to its recipient.

### ME.7:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| use and whole semantics | Intended result/preserved condition, situation, operations or invariant, applicability, participants, variation, bounds, and reidentification. |
| participant account | Each subject, kind or status, identity basis or open condition, and proposed contribution. |
| relation sets | Each direct relation, truth status, evidence, guard, and receiving use. |
| branch verdict | Obtaining composition result, prospective candidate account, or lower return with decisive reason. |
| prospective content | Guards, adapters, alternatives, recovery, stops, burdens, and variation points when the lower branch applies. |
| continuation, when selected | Later Work and observations, authority, acceptance/failure and reconsideration condition; a realization/test WorkPlan where its coordination needs one. |

### ME.7:4.3 - What Changes in Practice {#what-changes-in-practice}

Practitioners can write and test a coherent proposed Method without pretending that documentation created it. A positive composition claim becomes stronger because its identity and relation evidence are explicit; a prospective account remains useful for comparison through its guards, variation, recovery and stated limits. A selected implementation or trial adds the continuation needed to learn more.

## ME.7:7 - Conformance Checklist {#conformance-checklist}

- [ ] The proposed whole has an intended result or preserved condition, situation, reusable operations/invariant, applicability, participants, variation, bounds, and reidentification rule.
- [ ] Whole identity and every participant status are independently stated.
- [ ] Method composition, Work order/overlap, result use, allocation, support, authority, and description relations are not inferred from one another.
- [ ] The positive branch requires identified whole and parts plus obtaining `B.1.5` relations.
- [ ] The prospective branch preserves proposed truth and names guards, adapters, alternatives, recovery, stops, burdens, and unresolved conditions.
- [ ] WorkPlan, performed Work, observations, MethodDescription, and Method identity remain distinct.
- [ ] The result can lower below a candidate whole when load-bearing semantics or relations are missing.
- [ ] A supported account or lower result can complete its receiving use. Any selected continuation has a worthwhile feasible contribution and names the needed later Work, observations, authority, acceptance/failure and reconsideration.

## ME.7:9 - Consequences {#consequences}

Projects can move from architecture proposal to realization and learning under explicit identity and relation conditions. Strong composition claims are recoverable, while weaker proposals remain actionable without treating their Methods or relations as established.

The cost is a visible open identity or relation question. Some proposed methodologies will remain candidate accounts after useful trials, and some will split into several Methods or a relation structure instead of maturing as one whole.

## ME.7:12 - Relations {#relations}

- `A.3.1` governs whole and participant Method identification; `B.1.5` governs any Method-composition claim.
- ME.6 commonly supplies proposed relation sets and architecture alternatives, but it is not a compulsory predecessor.
- ME.5 supplies individual qualifications without whole identity or compatibility.
- Later realization, identification, description, support, trial, and assurance patterns consume only the branch and truth status returned here.
- A prospective account, WorkPlan, selected architecture, or trial result supplies no obtaining ArchitectureRelation or `methodPartOf` fact by itself.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-5#root, spec://ai.lev/fpf-eng-me/contract/ME-6#root; FPF spec://ai.lev/fpf-spec/contract/A-3-1#root, spec://ai.lev/fpf-spec/contract/A-22#root, spec://ai.lev/fpf-spec/contract/A-15-2#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-me/contract/ME-11#root, spec://ai.lev/fpf-eng-me/contract/ME-21#root, spec://ai.lev/fpf-eng-me/contract/ME-8#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-7
