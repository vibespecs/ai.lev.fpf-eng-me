# ME.8 - Author a MethodDescription or Candidate Method Account for Named Uses {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

>
> **Primary working result:** one `U.MethodDescription` edition and a use-coverage account for one admitted `U.Method`; or, when Method admission is absent, improved candidate-account content that keeps its candidate status.

## ME.8:0 - Use This When {#use-this-when}

Use this pattern when people need usable claims about an identified Method or a candidate account of a proposed way of working. The receiving use may concern planning, enactment, comparison, review, revision, publication or teaching; retain the claims' actual status. Start from one named use: who needs to do or decide what, which Method claims that use consumes, and what can remain outside the edition.

The first useful result is a short use-coverage row. It names the Method or candidate account, the receiving use, the claims needed now, the claims deliberately omitted, and the stop. That row prevents a documentation project from expanding before its practical question is clear.

Do not use this pattern merely to publish, diagram, approve, schedule, or record Work. A `U.MethodDescription` is the claim-bearing episteme whose exact `EntityOfConcern` is one Method already admitted under `A.3.1`; its code, diagram, form, carrier, approval, WorkPlan, and dated Work remain different things. If the proposed whole is still a candidate account, improve that account without classifying it as a `U.MethodDescription` for the whole.

## ME.8:0.1 - Working Distinctions {#working-distinctions}

| Item | Working meaning here | Boundary |
| --- | --- | --- |
| admitted Method | One reusable way of doing whose identity has been established under `A.3.1`. | A shared title, coherent document, WorkPlan, or successful occurrence does not establish it. |
| `U.MethodDescription` | One C.2.1 episteme about that Method whose claims say something substantive about how the Method is carried out. | Membership is not a completeness, approval, currentness, publication, or effectiveness result. |
| candidate account | Claims about a possible Method whose identity or obtaining relations remain unresolved. | It can be improved and used prospectively without being renamed a MethodDescription. |
| named use | A particular planning, enactment, comparison, audit, revision, publication, or teaching need with a receiver and stop. | A generic wish to “document the method” is not yet a use boundary. |
| use-coverage account | A C.2.1 account that states which Method claims an edition exposes for each named use and which it omits. | It does not prove that the claims are true enough for the use or that anyone used them. |
| representation and publication | A `C.29` correspondence, `E.24.PUB` form or publication occurrence, and carrier through which claims may be expressed or made available. | Form and availability do not decide MethodDescription membership. |

## ME.8:1 - Problem Frame {#problem-frame}

A working group often has too much material rather than too little: procedures, diagrams, code, examples, approval notes, logs, training slides, and tacit explanations. Different users need different portions. A planner needs applicability, preconditions, parameters, bounds, and stops; a performer needs the actionable claims for the current situation; a reviewer may need provenance, changed claims, and declared evidence limits.

Without a use boundary, authors either copy everything into one manual or reduce the Method to one convenient representation. Both moves hide whether the episteme actually describes an admitted Method and whether its claims are sufficient for the receiving use.

## ME.8:2 - Problem {#problem}

A document can look complete while saying little about the way of doing. Conversely, a small claim set can be a valid MethodDescription yet be unsafe for a consequential enactment use. Teams also copy calendars, assignees, tool states, observed results, and approval decisions into the description as if adjacency turned them into Method semantics.

The result is difficult to reuse and difficult to challenge. Readers cannot tell which claims belong to the Method, which belong to one Work occurrence, which are evidence or policy, and which omissions require a return.

## ME.8:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Use fitness | Each receiving use needs enough claims, while one universal description becomes expensive and opaque. |
| Stable subject | Several editions and forms may describe the same Method, while a candidate or changed Method must not inherit that identity by typography. |
| Practical brevity | The first useful edition should be small, while hidden preconditions or stops can make it misleading. |
| Representation plurality | Text, code, diagrams, tables, and formal models may all help, while none determines MethodDescription membership. |
| Evidence limits | Claims may cite evidence and source limits, while the description must not become the evidence or assurance result. |
| Revision | A use may require a new edition, while editing a description does not by itself change the Method. |

## ME.8:4 - Solution {#solution}

Author claims for named uses while preserving the described Method's identity or the account's candidate status. Return gaps instead of filling them with neighboring objects.

### ME.8:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Name the receiving use.** State the reader or consuming system, the action or decision, the situation and qualification window, and the stop. Replace “complete documentation” with the smallest question that changes work.
2. **Establish the subject branch.** Name the admitted `U.Method` and effective `U.ReferenceScheme`. If admission is absent, keep the subject as a candidate account and author only improved candidate content.
3. **Select the needed Method claims.** For the named use, consider the transformation or enactment concern, generic participant meanings, applicability, preconditions, intended effects or preserved conditions, bounds, parameters, variation, internal composition, evaluation conditions, and stops. Include only positions that change the use. For enactment or learning, recover the operations the performer must carry out and where their inputs come from.
4. **Separate neighboring claims.** Keep planned assignments and dates in a `U.WorkPlan`; actual performers, temporal extent, participation, and results with dated `U.Work`; operation declarations with `A.6.1`; evidence reliance with `A.10`; capability with `A.2.2`; approval, permission, and authority with the patterns that define those claims. Cite them when the use depends on them without absorbing them into Method semantics.
5. **Write the explanation or instruction.** For enactment or learning, connect each needed action to its inputs, the operation performed, the result and the condition for continuing or stopping. Explain why a connection or ordering matters when the reader needs that reason to apply or adapt it. Unfold a constituent operation until the intended performer can carry it out, or identify the missing know-how or contribution; do not invent an operation to fill a heading. Retain alternatives and genuine dependencies without imposing one order on independent actions. In the admitted-Method branch, identify the episteme by its claim content, Method as `EntityOfConcern`, and effective scheme. In the candidate branch, retain the account's proposed content and unresolved Method-identification conditions. State which claims were added, retained, narrowed, or removed when another edition is being revised.
6. **Record use coverage and omissions.** For each named use, list the claims exposed, claims deliberately omitted, unresolved claims, and the return condition. An omission is acceptable when the receiver does not rely on it; otherwise it is a gap.
7. **Choose expression and publication separately.** Select text, code, diagrams, a mathematical lens, publication form, and carrier only after the claims are stable enough for the use. When different named Method-related actions require complementary governed representations of the current MethodDescription or candidate account, ME.9 returns a complete Method representation profile: one complete C.37 claim group per action, together with cross-use correspondences, conflicting omissions, edition relations, decisions to keep representations separate, and conditions that require reconsidering several selections. Use the FPF pattern governing any other represented entity.
8. **Try the receiving use from the description.** Recover the claims, conditions and omissions needed by the receiving use. For enactment or learning, work through a small case: recover the first action and its inputs, follow its result to the next needed action or stop, and expose any instruction supplied only from the author's memory. Return a description or candidate-account correction, or identify the missing input, know-how or other result needed by the use. This checks the description at that use; it does not establish the Method's effectiveness or a learner's acquired capability.

### ME.8:4.2 - Record the Result {#record-the-result}

| Result position | Required content |
| --- | --- |
| subject | Admitted Method and identity basis, or candidate account and unresolved admission condition. |
| named use | Receiver, action or decision, situation, qualification window, and stop. |
| claim set | Method-side claims included in this edition and their effective scheme; the connected operations, inputs, results and conditions when the use requires an actionable instruction. |
| use coverage | Needed claims, exposed claims, deliberate omissions, gaps, and return condition for each use. |
| neighboring objects | Any WorkPlan, Work, representation, operation declaration, evidence path, capability, permission, authority, publication, or carrier relied on, each kept under its own kind. |
| edition disposition | MethodDescription edition, improved candidate-account content, or lower stop with the decisive missing condition. |

### ME.8:4.3 - What Changes in Practice {#what-changes-in-practice}

Authors stop treating “the method document” as one undifferentiated object. They can issue a small edition for one use, explain why it is enough, and name the exact gap when it is not. Readers can distinguish a claim about a reusable way of doing from a plan, an observed occurrence, a tool presentation, or an approval fact.

## ME.8:7 - Conformance Checklist {#conformance-checklist}

- [ ] Each `U.MethodDescription` result names one `A.3.1`-admitted Method as its exact `EntityOfConcern`.
- [ ] A candidate whole remains a candidate account when Method admission is absent.
- [ ] Every named use has a receiver, action or decision, situation, qualification window, and stop.
- [ ] Included claims say something substantive about the Method as a way of doing. An enactment or learning description lets the prepared reader recover the needed operations and their input/result connections, or exposes the missing contribution.
- [ ] Use coverage distinguishes exposed claims, deliberate omissions, unresolved gaps, and return conditions.
- [ ] WorkPlan, dated Work, actual participants and results, operation declarations, evidence, capability, permission, authority, representation, publication, and carrier claims remain separate.
- [ ] Representation choice does not decide MethodDescription membership.
- [ ] The result says only whether this edition covers the named claim need; it does not infer Method fit, effectiveness, assurance, or actual use.

## ME.8:9 - Consequences {#consequences}

Method descriptions become smaller, more reusable, and easier to compare because their subject and receiving uses are explicit. Candidate accounts remain useful without losing their truth status, and missing claims return to the right owner.

The cost is plurality: one Method may have several editions, use-coverage rows, and representations. Projects must also maintain links to neighboring plans, evidence, policy, and publication results instead of copying them into one manual.

## ME.8:12 - Relations {#relations}

- `A.3.1` supplies Method admission; `A.3.2` defines `U.MethodDescription` membership and its boundary from plans, Work, representations, and publication.
- ME.7 can supply an admitted whole or a prospective candidate account. ME.8 preserves the branch it receives.
- ME.18 can supply claim content and evidence limits for a candidate account; it does not admit the Method or create the description.
- ME.9 consumes ME.8's current MethodDescription or candidate-account claims only when several unlike named Method-related actions require a Method-specific profile. It returns one complete C.37 claim group per action and a separate result showing how the selections relate: source correspondences, conflicting omissions, edition relations, decisions to keep representations separate, and conditions that require reconsidering several selections. For one action, use C.37 or the pattern that governs it; for another represented entity, use that entity’s governing FPF pattern.
- `A.15.2`, `A.15.1`, `A.10`, `A.2.2`, `C.29`, and `E.24.PUB` define or constrain the neighboring plan, Work, evidence, capability, representation, and publication claims that ME.8 keeps separate.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-2#root, spec://ai.lev/fpf-eng-me/contract/ME-3#root, spec://ai.lev/fpf-eng-me/contract/ME-7#root; FPF spec://ai.lev/fpf-spec/contract/A-3-1#root, spec://ai.lev/fpf-spec/contract/A-3-2#root, spec://ai.lev/fpf-spec/contract/C-2-1#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-chk/contract/CHK-2#root, spec://ai.lev/fpf-eng-me/contract/ME-10#root, spec://ai.lev/fpf-eng-me/contract/ME-12#root, spec://ai.lev/fpf-eng-me/contract/ME-15#root, spec://ai.lev/fpf-eng-me/contract/ME-22#root, spec://ai.lev/fpf-eng-me/contract/ME-23#root, spec://ai.lev/fpf-eng-me/contract/ME-9#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-8
