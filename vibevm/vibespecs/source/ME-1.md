# ME.1 - Choose and Reopen the Project's Method-Engineering Focus: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Method Engineering Principles Framework* (20 September 2026), `Engineering DPF Suite/METHOD-ENGINEERING-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## ME.1:5 - Archetypal Grounding — EC-417 Release Focus {#archetypal-grounding-ec-417-release-focus}

In the EC-417 release scenario, eight of twenty releases reopened. The package is commonly called the “release methodology”, so the first proposal is to replace it as one Method.

Three existing views describe the same release Work:

| Viewpoint and view | Question exposed | Boundary |
| --- | --- | --- |
| project view | Whether provisional integration at `D-21` and signed evidence at `D-8` can reach `D0` with available people and rig time | Its schedule positions do not identify Methods. |
| process view | Which evidence checks, approvals, and stops recur | Repeated descriptions do not create one process-Method or whole. |
| case view | Which evidence, mismatch, exception, and authority state belongs to one release | The case description is not the Work or a Method. |

The status inventory contains four identified Methods: `M-HW-Verify`, `M-SW-Integrate`, `M-Supplier-Approve`, and `M-Release-Authorize`. It also contains candidate accounts `C-Evidence-Reconcile-Internal`, `C-Evidence-Reconcile-Supplier`, and `C-AI-Trace-Review`. `C-EC-Release-v2` is only a proposed-whole account. The PLM, CI, test rig, AI provider, safety capability, and supplier responsibility are support, System, capability, access, or assignment subjects rather than Method candidates by position.

| Focus option | Result |
| --- | --- |
| one Method: `C-EC-Release-v2` | rejected because the whole is not identified as a Method |
| established release-Method family | rejected because no governed family membership is supplied |
| project-local `LG-EC417-ReleaseMethods` grouping | retained only as a comparison locator; no family claim |
| candidate account: `C-AI-Trace-Review` | not selected as the current focus because its bounded trace suggestions govern neither evidence reconciliation nor release authority; candidate-account status is preserved |
| relations among the four Methods and two reconciliation accounts | selected because evidence timing, result use, allocation, and authority relations change the release decision |
| test-rig support decision | retained as a rival non-Method return, but current evidence does not make it the sole focus |

The first result is therefore a Method-relation focus. It creates no fifth Method and no composite. Reopen to a test-capability focus if two of the next three comparable delays occur while required evidence is complete and the rig is unavailable.

## ME.1:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| package bias | The boundary of a standard, methodology, or tool suite becomes one Method boundary. | Recover the receiving result, Work, Methods, accounts, and support subjects before choosing focus. |
| management-view bias | Project, process, or case descriptions become competing kinds of Work or Methods. | State the viewpoint and keep all applicable views connected to the same Work. |
| family-language bias | A local shortlist is presented as an established professional family. | Name its criterion and bounded use and retain unresolved family status. |
| composite bias | Co-use of several Methods becomes a whole Method. | Select a relation focus until whole identity and obtaining relations are separately supported. |

## ME.1:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Repair |
| --- | --- |
| “The process failed, so change the Method.” | Identify the result, Work, view, Method, and non-Method conditions before selecting the subject. |
| “These methods are our family.” | Use a local grouping unless governed membership is independently established. |
| “The tracker shows the real process.” | Treat the tracker content as a case, project, or process view with stated coverage and loss. |
| “Several contributors imply one composite.” | Return a Method-relation focus and send a proposed whole to ME.7 only when that later question is live. |
| “Choose the smallest item.” | Choose the smallest *decision-changing* subject, which may be a relation focus rather than one operation. |

## ME.1:10 - Rationale {#rationale}

The focus determines which claims are admissible in later Method use. Preserving the difference among a Method, family, local grouping, relation focus, and non-Method subject prevents downstream qualification or architecture prose from silently upgrading an unsupported object.

ME.1 connects questions about Methods, their descriptions, Work, capability, tools, variants and Method change. Project, process and case management can provide different viewpoints on the same Work. The pattern uses those views to discover questions, then identifies the subjects and relations that the project decision concerns; a view label alone establishes neither a new Work nor a Method.

## ME.1:11 - SoTA-Echoing {#sota-echoing}

| Source | Retained contribution | Use boundary |
| --- | --- | --- |
| Current FPF `A.15.6`, `C.11`, `A.3.1`, and `G.5` | Project-relative subject recovery, bounded choice, Method identity, and family/selector discipline. | These patterns do not choose the Method Engineering focus for the project. |
| Gericke, Eckert, and Stacey, [Elements of a design method](https://doi.org/10.1017/dsj.2022.23) | Method-ecosystem and element distinctions that help locate a candidate focus. | Source elements are prompts, not FPF kinds or Method parts. |
| Bender, [embedded-analytics process selection](https://doi.org/10.1007/s10257-024-00675-1) | Current context-specific selection evidence. | One application population does not establish a universal focus taxonomy. |

Reopen the affected rule when a current source or representative use exposes another materially different focus class, or when project/process/case views cannot preserve one Work while revealing the needed Method questions.


## ME.1:End {#end}
