# ME.6.MC - Compare Method Arrangements through a Mathematical Model {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Normativity:** Normative within the stated use

## ME.6.MC:1 - Problem frame {#problem-frame}

**Use this when** materially different ways of ordering, combining or allocating method contributions are plausible, and their interaction can change the receiving result. Two checks may compete for the same performer. A parallel summary may discard a distinction needed later. A reordered operation may preserve the final object while changing the answer on which someone acts.

Begin with one consequence that could change the choice, then construct the smallest mathematical account that can distinguish the arrangements. The first useful result is a derived property, feasible construction, bound or counterexample, interpreted back into the method comparison.

This method refines ME.6's comparison of arrangements. Here an arrangement concerns how contributions are connected for the selected work; it need not form one Method whole. The mathematical model represents the relevant operations, observations and shared resources. C.29 supplies the correspondence to the working situation. ME.7 supplies the separate judgment about whether participant Methods and their whole relations actually obtain.

Preparation requires the ability to describe the proposed work and its criteria, elementary algebra, and reasoning about functions, inequalities or finite sequences. A larger concurrent model may require a specialist using CMP.14. The specialist's result must expose the property, assumptions and decisive construction or counterexample needed by the method decision.

Use ordinary ME.6 comparison when the consequences are already clear and another model would add nothing. A different diagram of the same arrangement is not a rival. If only the status of a proposed Method whole is at issue, use ME.7. This method compares arrangements; constructing and introducing a changed way of working requires its own design and realization.

## ME.6.MC:2 - Problem {#problem}

Locally adequate contributions can fail together. Their inputs may have incompatible meanings, their conditions may not survive another contribution's operation, or their combined demand may exceed an available resource. Conversely, arrangements that look different can preserve everything the receiver needs.

A mathematical model can resolve these questions only if it retains the distinctions that matter. A proof about a reduced description may otherwise conceal the difference that should have changed the decision.

## ME.6.MC:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Useful simplification | A small model makes comparison affordable, while omitted observations or shared resources can reverse it. |
| Local and combined adequacy | Each contribution can satisfy its own conditions while their connection fails. |
| Result and history | Equal final values can accompany different intermediate answers, delays or failures. |
| Composition and allocation | Independent operations can overlap in principle while competing for the same equipment or attention. |
| Mathematical and practical grounds | A derivation establishes what follows from the model; reliance on the work requires the correspondence and assumptions to hold. |
| Comparison and development | A result can reject or retain an arrangement without constructing a replacement or requiring a new trial. |

## ME.6.MC:4 - Solution {#solution}

Select the consequence, model the competing arrangements and their interactions, derive the difference, and return what it changes in the Method decision.

### ME.6.MC:4.1 - Fix the receiving question and the actual alternatives {#fix-the-receiving-question-and-the-actual-alternatives}

Take the receiving result and its criteria from ME.3, or reuse an adequate account already available. Take the serious alternatives from ME.6. State how their proposed ordering, result use, allocation or shared resources differ. Keep a feasible incumbent in the comparison when it remains an option.

Choose the property that matters now. Examples include preserving an answer after regrouping work, completing before a deadline with the available capacity, preventing an obsolete result from being used, or ensuring that a required response eventually occurs. Name the inputs, variations and operating conditions over which it is required.

Distinguish an existence question from a guarantee. Finding one schedule establishes that the model admits that schedule; it does not show that every allowed scheduling policy will meet the deadline. Finding one successful sequence does not establish that all allowed interleavings preserve the result.

Retain each alternative's status. A proposed allocation, available tool, performed operation and obtaining Method relation are different facts. Carry a proposed arrangement's unconfirmed conditions into the result.

### ME.6.MC:4.2 - Represent the operations and the distinctions the receiver uses {#represent-the-operations-and-the-distinctions-the-receiver-uses}

Use C.29 to say what the mathematical objects represent. Define the relevant inputs, state, operations, outputs and conditions. For a sequential contribution, a function or partial function may suffice. For a changing document, state can include its revision and which revision a result concerns. For a shared resource, include its occupancy and availability.

Choose what the receiver can observe. Retain an intermediate answer if another step uses it, even when it disappears from the final store. Retain case identity or version when using the wrong case or version changes the result. If probability, timing or cost matters, represent that quantity and the assumptions supporting it; a plain set of possible outputs does not supply its distribution or duration.

Distinguish what is known from what the model assumes. A measured duration, a proposed upper bound and a convenient constant have different grounds. A human or automated performer can be represented by a transition rule for this calculation, but the rule needs a correspondence to the capability and conditions of that performer.

When alternatives use different representations, interpret both through the selected receiving quantities. MATH.18 supplies preservation and recovery across mathematical accounts. If a summary sends two cases to the same value but their required answers differ, that summary cannot support the comparison without recovering the lost distinction.

### ME.6.MC:4.3 - Construct the connection, including shared resources {#construct-the-connection-including-shared-resources}

For sequential functions, form \(g\circ f\), meaning first \(f\), then \(g\). Check that every relevant output of \(f\) is an allowed input of \(g\), including its meaning and conditions. With partial functions, determine the inputs on which the composite is defined. MATH.17 supplies the operation collections and closure argument.

Associativity permits regrouping a fixed sequence. Reordering needs a different property: the two orders must agree in the observations the receiver uses. If the operations return information as well as changing state, retain both in that comparison.

For overlapping work, represent the shared state or resource once. Connecting two models that each contain a private copy of the same bench or performer doubles the modeled capacity. Describe when each operation can begin, what it reads, what it changes or occupies, and when it releases a resource.

For example, let operation \(i\) have start time \(s_i\), fixed duration \(d_i\), and resource demand \(r_{ik}\) on resource \(k\). For nonpreemptive work, a precedence \(i\) before \(j\) requires

\[
s_j\geq s_i+d_i.
\]

If the available capacity is \(c_k(t)\), then at every time \(t\),

\[
\sum_{i:\ s_i\leq t<s_i+d_i}r_{ik}\leq c_k(t).
\]

Add input-availability and deadline conditions where they matter. These inequalities describe one timing model; interruptions, setup, rework or uncertain durations require the corresponding extension when they can change the answer.

Use CMP.14 when communications or interleaved updates need a computational interaction model. It supplies allowed steps, interference, coordination and progress arguments. For ordinary schedules or algebraic combinations, the simpler construction can be sufficient.

### ME.6.MC:4.4 - Derive the property or the separating case {#derive-the-property-or-the-separating-case}

Carry out the mathematical operation that can settle the question. Compose the functions, derive the resource bound, build a schedule, or explore the allowed transitions. A model name or a diagram is not yet that result.

For a preservation claim, state the condition initially and show why each allowed step retains it. For modular reasoning, establish what each contribution guarantees under its assumptions, then check that the connected contributions and environment supply those assumptions. Two contributions that each wait for the other's result can both satisfy a conditional promise while neither starts. Progress requires an enabling basis and any needed scheduling or delivery assumptions.

For a failure claim, give the input or sequence that produces the prohibited consequence. One admitted counterexample defeats a universal assertion. Check whether it represents a possible working case; an over-broad abstraction can introduce a sequence the work cannot realize. Conversely, a model that omitted a real interaction can miss a failure. CMP.14 and the applicable mathematical interpretation supply the needed refinement.

For a finite construction, exhaustive exploration can establish the property over the explored state space. A few simulation runs establish their observed outcomes. A bound may settle the question without enumeration; if even an optimistic capacity bound misses the deadline, searching more schedules under the same conditions cannot repair that alternative.

Keep the scope of equivalence explicit. Equality of final outputs can be sufficient for a final-output question. Equality of histories, distributions or burdens requires those distinctions in the comparison. A later receiving operation may distinguish arrangements that were equivalent for the earlier use.

### ME.6.MC:4.5 - Compare the consequences without hiding moved burden {#compare-the-consequences-without-hiding-moved-burden}

Return the result in the quantities and conditions chosen in :4.1. Explain which alternative preserves the required answer, which fails, which remains unresolved, and why. Where alternatives trade off time, effort, retained information or another criterion, keep the distinct consequences available to ME.6 and the applicable C.11 choice.

Include burden moved by the arrangement: a faster central step may require more preparation elsewhere; releasing a checked snapshot may require storage while a newer revision awaits review; independent instruments may still require the same operator. A local improvement is useful only to the extent that the receiving comparison can accept those effects.

Compare the chosen model with a cheaper sufficient argument. A two-step trace can expose an ordering failure without a model checker. A workload lower bound can rule out a schedule without detailed simulation. Use a larger construction when it can change an unresolved consequence or support a broader claim that the decision actually needs.

The outcome may support retaining an incumbent, rejecting one proposal, preserving several alternatives, or selecting a bounded trial. It need not rank every arrangement. Existing FPF choice, Pareto and improvement methods govern those results; no new scoring rule is introduced by drawing a mathematical model.

### ME.6.MC:4.6 - Interpret the result and reopen the affected premise {#interpret-the-result-and-reopen-the-affected-premise}

State the mathematical conclusion and the working conclusion it supports. For example: under the stated durations and exclusive-resource rule, no schedule of this arrangement completes by the deadline; if those conditions describe the proposed work, this arrangement cannot meet that criterion.

For reliance on actual work, examine the correspondence where a wrong premise could change the decision. Existing observations or a subject argument may suffice. If the decisive uncertainty concerns setup time, operator availability or a possible edit, obtain the relevant clarification only when its contribution warrants the effort. C.11.DUA governs that choice. A mathematical comparison does not create a requirement for an experiment.

A changed premise returns to its affected operation or constraint. Adding a second bench leaves the operator constraint unchanged. Allowing an intervening update can invalidate a formerly adequate sequence. Changing the requested statistic can invalidate an otherwise correct summary. Preserve conclusions whose conditions remain unchanged.

Use ME.7 when the receiving claim concerns an actual Method whole and its participant relations. Mathematical composition alone establishes neither those relations nor a performed trial. If the comparison reveals a needed change of procedure, return the candidate's required behavior for construction; if it only reveals a different description of the same behavior, say so. A comparison can finish with its conditional decision and return condition.

## ME.6.MC:7 - Conformance Checklist {#conformance-checklist}

When the comparison is used for a decision, the following content must be recoverable from the calculation and its explanation.

| Check | Required content |
| --- | --- |
| Working question | The receiving consequence, criteria and materially different arrangements. |
| Correspondence | What the model represents, with decision-changing omissions and assumptions. |
| Connection | Applicable inputs and outputs, relevant order or overlap, and shared resources represented once with their stated capacity limits. |
| Mathematical result | A derivation, construction, bound or reproducible counterexample at the stated scope. |
| Result strength | Existence, universal preservation, observed simulation outcome and practical reliance are distinguished where they change the decision. |
| Comparison | Consequences and moved burdens are returned to the receiving criteria without an invented aggregate score. |
| Continuation | The supported decision, unresolved premise or changed-condition return; Method-whole claims remain with ME.7. |

## ME.6.MC:9 - Consequences {#consequences}

A comparison can expose an impossible deadline, justify regrouping work for a selected result, or locate the interaction that makes one arrangement fail. Some alternatives can be discarded before costly implementation, while others remain useful under different conditions.

The result is narrower than a complete endorsement of a way of working. Unmodeled quality, capability or access can still decide the choice. Additional mathematical detail is worthwhile only when it changes a needed consequence or its support.

## ME.6.MC:12 - Relations {#relations}

- **ME.3** supplies situated requirements and their subjects. **ME.6** supplies the broader comparison and receives the derived consequence, moved burden and qualification.
- **ME.7** resolves a proposed Method whole into supported obtaining relations or a prospective account. Equality or composition of mathematical descriptions does not perform that work.
- **MATH.17** constructs admissible operations and their composition laws. **MATH.18** constructs interpretations and tests what transfers between mathematical accounts.
- **C.29**, with **C.29.1–.3** where needed, supplies subject correspondence, result transfer, computational formulation and realization.
- **CMP.14** constructs and checks computational interaction when shared state, messages or progress matter. Its environment assumptions remain visible in the receiving Method comparison.
- **C.11/C.11.CRC**, **C.18** and **E.22/E.23** supply choice, contribution comparison, Pareto or retained-alternative treatment, and improvement. **C.11.DUA** governs whether another observation or trial is worth its burden.
- **ME.25** addresses construction of a changed Method from a mathematical transformation. The present result is a comparison or a returned construction requirement, not an assertion that the changed Method has been obtained.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-me/contract/ME-3#root/.6; spec://ai.lev/fpf-think-math/contract/MATH-17#root/.18; spec://ai.lev/fpf-think-cmp/contract/CMP-14#root when interactions matter; FPF spec://ai.lev/fpf-spec/contract/C-29#root @status:spec/done

#source spec://ai.lev/fpf-eng-me/source/ME-6-MC
