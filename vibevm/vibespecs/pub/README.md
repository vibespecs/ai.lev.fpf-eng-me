# Method Engineering Principles Framework Readme {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Readme section of the publication. See LICENSE.md for the list of changes.

## Practical entries {#practical-entries}

This framework helps practitioners change a way of working while keeping the receiving problem in view. The examples below show how one Method Engineering result becomes an input to another question, and how changed conditions can send the work back.

These are selected uses, not a catalogue or a required sequence. If one pattern or an existing result answers your question, use it directly. Otherwise use the Table of Contents or search the pattern titles and Problem frames. The full bodies provide the working moves and their limits. You can ask an assisting agent: “Explain this and give me your comments in ordinary language, without framework jargon.”

### ME-CARD-01 — Develop a Method and its supporting arrangements without losing the receiving problem {#me-card-01-develop-a-method-and-its-supporting-arrangements}

- **Situation:** A release team repeatedly reopens firmware integration when a supplier's signed pinout arrives late. It proposes a new release methodology, but the immediate difficulty may lie in the relations among hardware verification, software integration, supplier approval and release authorization.
- **Question:** Which change can reduce that delay without exceeding the available review capacity or closing a release on unsigned information?
- **First useful result or blocker:** A comparison of feasible arrangements, with the burden and conditions of a provisional-integration branch exposed; or the missing subject, capacity or safety premise that prevents a choice.
- **Start with:** `ME.1` to identify the subject of the change. Use `ME.3` for the receiving criteria, `ME.5` for individual qualification and `ME.6` when interactions among the qualified subjects change the answer.
- **Stop or return:** Finish with the relation-level decision when that is enough. Reconsider it when supplier timing, workload or a protected condition changes; use `ME.7` only if the identity or composition of a proposed whole also needs an answer.

In the constructed [EC-417 application](spec://ai.lev/fpf-eng-me/pub/cross-pattern-application#app-me-01-choose-the-smallest-method-engineering-result-needed), integration is due 21 days before release, but the signed pinout is expected only eight days before release. The four Methods have been identified separately. `ME.1` therefore selects their relations as the present focus; `ME.2` keeps the reusable alternatives and their statuses available. The proposed release-wide Method remains a candidate.

The criteria from `ME.3` now constrain the `ME.6` comparison: signed information is required before closure, the safety engineer has at most 3.20 hours on the peak day, and rollback must remain available until one day before release. Waiting for the signed pinout misses the integration slot by 13 days. Integrating provisionally and reconciling later meets that slot, but initially needs 4.40 safety-engineer hours on the reconciliation day. Moving 1.60 hours of preparation to supplier configuration lowers that peak to 2.80 hours. The receiving result is a feasible candidate arrangement under those assumptions, including the burden transferred to the supplier.

That result can support a bounded choice through `ME.14`; it need not wait for a new trial. If trial observations could change the decision enough to justify their cost, `ME.11` plans and obtains the relevant Work evidence. `ME.12` checks a named maintained claim, `ME.13` addresses fit or transfer to a different situation, and `ME.14` compares results and burdens with alternatives. A successful support task or a plausible workload estimate does not supply all three conclusions.

Two changed conditions lead to different returns. If the signed pinout is still absent at closure, withhold closure, preserve the completed provisional work and follow the recovery conditions; do not silently waive the signed-information requirement. If the supplier can instead provide the signed pinout before the integration slot, repeat the arrangement comparison: the simpler signed-first option may now avoid provisional reconciliation and recovery. The earlier choice remains an account of its earlier conditions.

### ME-MODEL-AND-CHANGE - Use a mathematical construction to change how work is divided {#me-model-and-change-use-a-mathematical-construction-to-change}

- **Situation:** A repeated calculation gathers all measurements in one place, while the measurements are already available to several teams.
- **Question:** Can the teams return smaller contributions that preserve the required answer, and what must change when the recipient asks a different question?
- **First useful result or blocker:** A proposed distributed procedure with a derivation of its preserved answer and its resource consequences, or the information the proposed summaries lose.
- **Start with:** ME.3 for the receiving requirement, [ME.6.MC](spec://ai.lev/fpf-eng-me/contract/ME-6-MC#root) for the comparison, and [ME.25](spec://ai.lev/fpf-eng-me/contract/ME-25#root) to turn the mathematical construction into a changed procedure.
- **Stop or return:** Retain the current procedure when the new one has no worthwhile benefit. A changed required answer returns to the summary and recovery construction; if a team's capability or support changes, reconsider the affected allocation or support before relying on the procedure.

**1. Choose the answer to preserve.** The recipient needs the mean of all included measurements, each with equal weight. The records have the same units and meaning. ME.3 retains those conditions when a team proposes sending local means instead of individual measurements.

**2. Compare the mathematical constructions.** ME.6.MC exposes the weighting difference. For local lists (0,4,0,4) and (10,10), the local means are 2 and 10. Averaging those means gives 6; the mean of all six measurements is 28/6, or 14/3.

MATH.17 supplies an operation on summaries: represent a list by its sum and count, and combine two pairs by adding their respective components. This operation is associative. MATH.18 supplies the interpretation question: does summarizing a concatenated list give the same result as combining its summaries? Here both routes give the total sum and count. Division recovers the required mean when the total count is positive. The construction preserves this answer for any partition under the stated inclusion and weighting rules.

**3. Construct the changed way of working.** ME.25 now uses that mathematical result to propose local sum-and-count calculation followed by pair addition and division. Every included record must be counted once; each team must have its assigned records and deliver the pair before the result is needed. These are requirements on the changed procedure and its support. The algebra does not establish that the teams already have those capabilities or connections.

For k nonempty teams and N scalar measurements, the proposal transmits 2k scalar values instead of N, apart from any identifiers and communication overhead. It can reduce that transfer when N exceeds 2k, while adding local calculation and coordination. In the small example, four scalar values replace six. ME.6 and ME.14 compare that contribution with the total burden; equality of the mean alone does not establish practical improvement. Rounded computation needs its numerical error allowance.

**4. Describe and introduce only the supported change.** ME.8 makes the selected procedure and its conditions available to its users. ME.7 addresses a claim that the participating Methods constitute a Method whole when that claim matters. ME.16 addresses introduction into practice; ME.11 supplies a trial only when the result it could obtain is worth the work. Existing adequate grounds can suffice for the decision being made.

**5. Reopen the construction when the required result changes.** The recipient now also needs the number of measurements greater than 3. Replacing the first list by (2,2,2,2) preserves its sum and count, hence the overall mean, but changes the total above 3 from four to two. The old pair cannot supply the new answer.

ME.6.MC returns this separating case to ME.25. Add a local count above 3 to the summary and combine those counts by addition, or retain access to the original records. The former mean calculation remains valid. Here three values per team would again transmit six scalars, so the original reduction in their number disappears. A later change of threshold can require a different retained contribution again. ME.3 preserves the revised requirement, while ME.8 describes the revised instruction.

### ME-DESCRIBE-SUPPORT — Make Method material usable for named decisions and Work {#me-describe-support-make-method-material-usable-for-named}

- **Situation:** The EC-417 team has a candidate arrangement, but its users need different things from the material: a trace reviewer must retrieve the current account, a release decider must choose a branch, and a safety reviewer must tailor it without dropping a closure condition.
- **Question:** Which claims and representations does each action need, and which support tasks actually work?
- **First useful result or blocker:** Description content for the named uses, related representation selections where the actions differ, and a support decision that preserves successful tasks alongside untested or failed ones.
- **Start with:** `ME.8` for the description or candidate-account content; `ME.9` when several unlike Method actions need related representation selections; `ME.10` for the support arrangement through which users obtain and use them.
- **Stop or return:** Stop at a sufficient answer for the named action. A contradicted support or description claim returns through `ME.12` to its owner; a changed task or permission premise reopens only the uses that depend on it.

The selected arrangement supplies the branch conditions that the material must preserve. `ME.8` makes those claims available for the intended actions, keeping the candidate's status visible. If one action needs only one adequate representation, its direct `C.37` selection can finish the question. For each action, `C.37` asks whether the proposed representation supplies the needed claim, what supports relying on it, which use the receiving decision permits, which distinctions it shows or omits, and when to reconsider. `ME.9` relates these per-action choices through shared sources, corresponding claims, conflicting omissions, edition dependencies and reasons to keep forms separate. A compact branch view may omit detail that tailoring still needs.

`ME.10` consumes those task requirements when comparing support arrangements. In the application's constructed task observations, retrieval and branch selection succeed. The tailoring exercise preserves the signed-before-closure condition and rejects stale material, but the task's required input, action and result are not fully defined, and its permission/authority stop remains untested. The supported conclusion is partial support, not completion of the whole task set. Untested alternative arrangements remain untested, not inferior. Repair or test the missing task only if the receiving use needs that answer; retain the successful tasks.

When the remaining difficulty concerns an explanation, `ME.22` compares the claims separately from their expression. `ME.8` supplies claims about one Method; `ME.23` supplies the relations explaining the surrounding language. The [worked explanation comparison](spec://ai.lev/fpf-eng-me/pub/cross-pattern-application#compare-explanations-of-a-pattern-language) selects a prose explanation of three independent questions, then expresses those same selected claims as a table. The first contrast changes the selected content; the second can address form under comparable reading conditions. It reports no observed advantage of the table. Keep a sufficient explanation unless the proposed change has a worthwhile benefit. Access to that explanation, capability to act and authority to choose still need their own bases when the task relies on them.

### ME-PLUS-PRODUCE — Engineer source-grounded Method-description knowledge as a pattern language {#me-plus-produce-engineer-source-grounded-method-description}

- **Situation:** A handbook permits reuse of a prior review after a display-only change; a research source limits that reuse to matching claims, question and qualification window; a recovered work account leaves open whether a shortened warning lost a needed condition.
- **Question:** How can a reusable language preserve the common action, the limiting condition and the unresolved account without making readers reconstruct all three sources for every use?
- **First useful result or blocker:** A justified source allocation, a useful relation between independently reusable questions, and a reconstruction of the promised answer; or the missing condition or source basis.
- **Start with:** The [production MethodDescription](spec://ai.lev/fpf-eng-me/pub/PREFACE#me-preface-7-3-production-methoddescription-engineer-a-source) for the connected account. Enter `ME.4`, `ME.21`, `ME.23` or `ME.24` at the result that is missing.
- **Stop or return:** Keep a direct source or one-Method description when it suffices. Follow a changed source premise to the claims and uses that relied on it, preserving results whose basis still holds.

In the constructed handbook/research/work-account case in the Preface, `ME.4` recovers the documentary claims in their source contexts. The returned work account remains a candidate with rival interpretations. `ME.21` compares these contributions with current supply: reuse `ME.12` for coherence checking, carry the research source's matching conditions into the reuse rule, leave tool-specific layout detail at its source, and keep the warning account unresolved.

If recurring uses need allocation, contradiction checking and reconstruction separately, `ME.23` relates those questions. A reconstruction consumes the allocated condition; a missing allocation sends it back to `ME.21`; a contradicted maintained claim goes to `ME.12`. Grouping the entries does not establish Method parthood. `ME.24` then attempts the promised answer through the language and its source returns. A topic match or citation cannot replace a condition needed to decide whether the old review is reusable.

Now suppose the handbook is available only as excerpts, and a new recheck needs an argument outside them. A stored allocation locator does not supply that argument. `ME.24` identifies the unsupported current reliance; obtain another justified basis, narrow the use or stop it. Keep the historical result, the independently supported research condition and the unresolved work account. Revisit copied premises too: unchanged wording does not make their reliance independent.

`ME.20` helps select the next missing result when a new fact changes the question. It can also finish immediately by reusing a sufficient current answer. Publication permission remains a separate question.

## Citation {#citation}

If you use this framework, please cite:

```text
Levenchuk, Anatoly. Method Engineering Principles Framework.
Version date: as shown at the beginning of this file.
GitHub repository: https://github.com/ailev/FPF
```

For a particular pattern, add its PatternID and title, for example: Method Engineering Principles Framework, ME.9 - Relate Method Representations across Their Different Uses. Retain the release date, and include a permanent link or stored copy when the exact wording matters.
