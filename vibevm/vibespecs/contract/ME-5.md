# ME.5 - Qualify Individual Methods, Candidate Accounts, and Local Connections {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

>
> **Primary working result:** one **status-preserving individual qualification** for each selected Method or candidate Method account, plus only those local input/result, schema-correspondence, or adapter-feasibility claims that can be judged without choosing a whole architecture.

## ME.5:0 - Use This When {#use-this-when}

Use this pattern when a project has one or more Methods identified under `A.3.1`, candidate Method accounts, and situational criteria, but it still does not know which subjects are individually usable for the bounded result. Use it before a several-structure comparison when a weak subject can be rejected cheaply on its own.

Begin with one Method or candidate account, its status, the contribution it is expected to make, and the criteria that matter for that contribution. Keep whole-level allocation, synchronization, composition, and compatibility questions outside the individual result.

The first useful result says one of the following: an identified Method is qualified or not qualified for the bounded use; a candidate account is retained or excluded while its Method-identification question remains open; or a local connection claim is supported, unsupported, or unresolved independently of a whole synthesis.

Do not use qualification wording to admit a candidate account as a Method, to establish compatibility or parthood, or to declare a Method architecture fit.

## ME.5:0.1 - Working Distinctions {#working-distinctions}

| Name used here | Meaning |
| --- | --- |
| identified Method subject | A Method already identified under `A.3.1`; ME.5 judges bounded use without repeating identity. |
| candidate-account subject | An episteme about a possible Method whose unresolved identity conditions remain visible throughout qualification. |
| individual contribution | The result or preserved condition attributable to this subject under the stated use, not the success of a whole arrangement. |
| local connection | An input/result, schema-correspondence, or adapter-feasibility claim whose truth does not depend on choosing one whole synthesis. |
| individual qualification | A bounded result covering contribution, applicability, inputs/results, attributable time or burden, capability, support, authority/access, evidence, source limits, and stop. |
| architecture question | A claim about combined allocation, timing, composition, Work overlap, provider arrangement, authority distribution, or another several-structure relation. It belongs to ME.6 when live. |

## ME.5:1 - Problem Frame {#problem-frame}

Method-selection literature correctly emphasizes situation and fit, but real project candidates arrive at unlike epistemic states. One is an identified Method with known use evidence, another is a candidate account recovered from Work records, and a third phrase refers only to a tool or support condition.

Individual qualification can save architecture effort by rejecting a candidate that cannot produce the required result or cannot meet one non-negotiable condition. It becomes misleading when it averages several Methods and support arrangements into one fit score or upgrades an account through confident language.

## ME.5:2 - Problem {#problem}

Three errors recur. First, a retained candidate account is called a qualified Method. Second, one independently feasible schema mapping is called compatibility of the whole package. Third, a combined peak-load or authority conflict is hidden inside separate “passes” for each Method.

The project then believes the architecture problem is solved even though no result states how the individually plausible subjects work together.

## ME.5:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Cheap rejection | Individual defects should stop early, while whole conflicts must remain visible for ME.6. |
| Status preservation | Candidate accounts need useful assessment, while qualification cannot identify their Methods. |
| Comparable questions | A common set of questions aids choice, while not every question applies to every subject. |
| Evidence proportionality | A bounded use may need little evidence, while safety, authority, or high burden can require stronger support. |
| Local connections | A schema or adapter can be tested independently, while its placement and maintenance belong to a whole synthesis. |

## ME.5:4 - Solution {#solution}

Qualify one subject at a time against the bounded receiving use. Preserve status, expose unsupported conditions, and route only genuinely combined questions to ME.6.

### ME.5:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **State the subject and status.** Name the identified Method or candidate account and cite the identity or account basis already available. Reject unlike support facts as qualification subjects.
2. **Bind the use.** State the receiving Work or result, situation family, scope, time window, non-negotiable criteria, acceptable variation, and decision that will consume the qualification.
3. **Recover the individual contribution.** Name the input, result or preserved condition, procedure or invariant as far as known, applicability, and important source meaning. Do not credit the subject with another Method's result.
4. **Check attributable conditions.** Inspect timing and burden attributable to this subject; performer capability; support and provider access; authority or responsibility; evidence; and source or transfer limits.
5. **Test local connections only.** Check an input/result handoff, schema correspondence, or adapter feasibility when it can be supported independently. Record its scope and failure case.
6. **Return the truthful branch.** An identified Method is qualified or not qualified for the bounded use. A candidate account is retained or excluded *as an account*, with unresolved identification conditions unchanged. A local connection is supported, unsupported, or unresolved.
7. **Choose the stop.** Stop after one usable Method, one retained account, or several independently usable subjects when no whole question remains. Enter ME.6 only when a several-structure choice can change the decision.

### ME.5:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| subject and status | Method identity or candidate-account reference and the status that remains after qualification. |
| bounded use | Receiving result or Work, situation, scope, window, criteria, and consuming decision. |
| contribution | Inputs, result or preserved condition, known procedure/invariant, applicability, and variation. |
| attributable conditions | Time/burden, capability, support/provider access, authority/responsibility, evidence, and source limits attributable to this subject. |
| local connections | Independently tested input/result, schema, or adapter claims with scope and status. |
| verdict and stop | Qualified/not-qualified Method or retained/excluded account, open identity conditions, remaining whole question, and next action. |

### ME.5:4.3 - What Changes in Practice {#what-changes-in-practice}

Teams stop scoring a methodology bundle as one object. They can reject one Method, retain a promising account without admitting it, and prove one schema mapping without calling the whole arrangement compatible. ME.6 then receives only the genuinely combined timing, allocation, support, authority, or composition questions.

## ME.5:7 - Conformance Checklist {#conformance-checklist}

- [ ] Every subject is an identified Method or a candidate Method account and keeps that status.
- [ ] The qualification names one receiving use, scope, situation, window, and consuming decision.
- [ ] Contribution, inputs/results, applicability, attributable burden, capability, support, authority/access, evidence, and source limits are checked as applicable.
- [ ] No subject receives credit for another Method or whole arrangement's result.
- [ ] Local connection claims are independently testable and bounded.
- [ ] A candidate-account verdict preserves unresolved `A.3.1` identification conditions.
- [ ] Whole allocation, synchronization, composition, provider, and architecture questions remain explicit rather than hidden in individual verdicts.
- [ ] The result states whether to stop, reject, retain, or enter ME.6.

## ME.5:9 - Consequences {#consequences}

Weak subjects fail early, promising accounts remain usable without ontological promotion, and local handoffs become inspectable. Architecture comparison is smaller because it receives only retained subjects and unresolved combined questions.

The cost is refusal to publish one convenient compatibility score. A project may receive several qualified individual results and still have no acceptable synthesis.

## ME.5:12 - Relations {#relations}

- ME.3 or an applicable domain result supplies situational criteria; ME.4 or another lawful route supplies identified Methods/accounts and dependency slices. Neither named predecessor is compulsory when equivalent content exists.
- `A.3.1` alone governs Method identification. ME.5 does not admit Methods.
- ME.6 receives retained subjects only when combined Method, Work, allocation, support, description, subject, or cultural structures change the decision.
- ME.7 resolves a proposed whole; ME.5 qualification supplies no whole identity, compatibility, or `methodPartOf` fact.
- `C.11` or the applicable domain decision Method consumes the bounded individual results when a choice is live.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-2#root, spec://ai.lev/fpf-eng-me/contract/ME-3#root, spec://ai.lev/fpf-eng-me/contract/ME-4#root; FPF spec://ai.lev/fpf-spec/contract/A-3-1#root, spec://ai.lev/fpf-spec/contract/A-10#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-me/contract/ME-21#root, spec://ai.lev/fpf-eng-me/contract/ME-6#root, spec://ai.lev/fpf-eng-me/contract/ME-7#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-5
