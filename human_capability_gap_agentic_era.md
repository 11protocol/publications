## 🛡️ LEGAL NOTICE
>By continuing to access or use this document, you acknowledge that you have read, understood, and agree to be bound by the 11Protocol [Licensing & Intellectual Property terms](https://github.com/11protocol/publications/tree/main?tab=License-1-ov-file).
---
# The Human Capability Gap in the Agentic Era
## Designing organizations that preserve, develop, and deploy human capability alongside AI

**Research and strategy report**  
**November 2026**

---

## Executive summary

The adoption of generative and agentic AI is changing more than the speed at which work is performed. It is changing how work is divided, where expertise is built, how decisions are made, what organizations value in employees, and where accountability sits when software can act across a process rather than merely produce an answer.

The productivity evidence is encouraging, but it is not a universal forecast. In a randomized experiment involving 453 college-educated professionals performing writing tasks, access to ChatGPT reduced average completion time by 40% and increased output quality by 18%. The greatest gains accrued to participants with weaker initial skills. [[1](https://doi.org/10.1126/science.adh2586)] A separate field study of 5,172 customer-support agents found a 15% average increase in issues resolved per hour, with larger improvements among less experienced and lower-skilled workers; it also found evidence that the AI assistant helped newer workers move more quickly down the experience curve. [[2](https://doi.org/10.1093/qje/qjae044)] In software development, three randomized field experiments involving 4,867 developers found a combined 26.08% increase in completed tasks, although the experiments were noisy and effects varied. [[3](https://doi.org/10.1287/mnsc.2025.00535)]

These findings support the view that AI can act as a skill equalizer: it can make some forms of expertise more accessible and reduce performance differences on particular tasks. But that is only one side of the picture. A large field experiment involving 758 knowledge workers found a jagged capability frontier: AI improved performance on many tasks, yet could reduce performance on tasks beyond its capabilities—even when those tasks appeared similar in difficulty. [[4](https://doi.org/10.1287/orsc.2025.21838)] The International Labour Organization’s 2025 analysis estimates that one in four workers globally are in occupations with some exposure to generative AI, while concluding that transformation of jobs is more likely than wholesale automation because most occupations still contain tasks requiring human input. [[5](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure)]

The central issue is therefore not whether AI will eliminate or augment work in the abstract. It is how organizations choose to recompose work, allocate decision rights, distribute the gains, and develop the people who remain responsible for outcomes.

This report advances a central proposition: **the human capability paradox**. As organizations automate more of the execution through which people traditionally build experience, they may also weaken the foundational knowledge and situational understanding required for people to exercise judgment, challenge AI outputs, handle exceptions, and take over when automated processes fail. That outcome is not inevitable. AI can also support learning, distribute expertise, and create new forms of practice. But it will not do so automatically. It depends on how the organization designs the work, learning environment, technology, incentives, and accountability structure.

The answer is not to preserve every manual task, nor to place a human approver at every step. Passive review can create approval fatigue and automation bias; continuous monitoring can produce an illusion of control; and a human-AI combination does not automatically perform better than either a capable human or AI system alone. A meta-analysis of 106 experimental studies found that, on average, human-AI combinations performed worse than the better of the human-only or AI-only conditions. The results varied by task: combinations were more promising for content creation than for decision-making. [[8](https://www.nature.com/articles/s41562-024-02024-1)]

Organizations need a wider and more deliberate set of responses. These include redesigning work around human-AI complementarity; creating multiple forms of human involvement rather than defaulting to approval gates; protecting the development of expertise; using AI as a tutor, simulator, and challenger as well as an executor; redesigning career paths and management practices; building systems that make agent behavior observable and interruptible; involving employees in adoption decisions; creating incentives for challenge and escalation; and measuring whether capability is actually improving over time.

The report distinguishes four questions that are often conflated:

1. **Where should AI perform work?** Which tasks are suitable for automation, augmentation, delegation, or human ownership?
2. **Where must humans remain capable and influential?** Which decisions, relationships, contextual judgments, exceptions, and accountabilities cannot simply be delegated?
3. **How will that human capability be built and maintained?** What experiences, practice, knowledge, tools, authority, and organizational structures make good judgment possible?
4. **How will the organization know whether the design is working?** What evidence demonstrates that productivity, quality, resilience, worker capability, and accountability are improving together?

The strategic objective is not to keep humans involved for its own sake. It is to build organizations in which the allocation of work between people and AI is intentional, adaptive, and productive—and in which the human capability needed to govern the system is not gradually designed out of existence.

---

## 1. The transformation of work: from task automation to organizational redesign

### 1.1 AI changes the economics of tasks, not just the speed of individual workers

Early workplace studies show that generative AI can improve the speed and quality of work in bounded settings. Noy and Zhang’s writing experiment, the customer-support field study by Brynjolfsson, Li, and Raymond, and the software-development field experiments by Cui and colleagues all demonstrate measurable productivity gains. But they study different occupations, tools, outcomes, and organizational conditions. Their estimates should not be combined into a single expected productivity uplift for every business.

The customer-support evidence is especially important because it demonstrates that AI can transmit some of the practices of experienced workers to newer employees. Less experienced agents improved substantially when given access to real-time suggestions, and the authors found evidence consistent with faster learning. [[2](https://doi.org/10.1093/qje/qjae044)] This complicates a simple narrative in which AI necessarily deprives new workers of expertise. In some settings, AI can expose novices to examples, patterns, and guidance that they would otherwise acquire more slowly.

At the same time, the benefit is not uniform. The same study found small declines in conversation quality among the most experienced and highest-skilled agents. The lesson is not that AI helps novices and harms experts in every situation. It is that the effect depends on a worker’s existing skill, the task, the form of assistance, and the relationship between the tool and the expertise already present.

The larger economic issue is how tasks move between human and machine. Acemoglu and Restrepo describe two opposing forces. Automation displaces labor from tasks it previously performed; the creation of new tasks can reinstate labor in activities where people have a comparative advantage. The final effect depends on the balance between these forces, not on automation alone. [[6](https://doi.org/10.1257/jep.33.2.3)] David Autor’s work similarly cautions against assuming that the ability to automate a task means that entire occupations disappear: technology can substitute for some activities while complementing others, increasing demand for the work that remains. [[7](https://www.nber.org/papers/w20485)]

This task-based perspective is critical for organizations. A job title is rarely a single unit of work. It is a bundle of activities: gathering information, applying rules, interpreting context, communicating, making decisions, resolving exceptions, maintaining relationships, and accepting responsibility. AI may automate several activities while increasing the importance of others. The organization must decide how the bundle should change.

The relevant management question is therefore not simply, “Which jobs can AI replace?” It is:

> **Which tasks should be automated, which should be augmented, which should remain human-led, and which new tasks become valuable once AI changes the economics of the process?**

This distinction prevents two strategic errors. The first is automating a task without redesigning the workflow around it. The second is assuming that because AI has made one part of a job cheaper, the rest of the job can remain unchanged.

### 1.2 The skill-equalizer effect is real, but conditional

The skill-equalizer effect is one of the most consequential findings emerging from early AI productivity research. When AI provides suggestions, drafts, code, or structured guidance, less experienced workers may achieve a level of output that previously required more experience. This can improve access to expertise, accelerate delivery, and reduce dependence on a small group of specialists.

However, the effect has at least three different interpretations:

- **Performance equalization:** less experienced workers produce better immediate outputs with AI assistance.
- **Capability transfer:** workers learn practices, concepts, and patterns through interaction with the system.
- **Capability substitution:** the system performs work that the worker would otherwise have learned to do.

These are not equivalent. A novice who uses an AI assistant to understand why a solution works may be developing capability. A novice who repeatedly accepts a generated solution without understanding its assumptions may be achieving performance without acquiring the underlying knowledge. A senior professional who delegates routine work may free capacity for more complex problems—or lose familiarity with the operational detail needed to diagnose failures.

Organizations should therefore avoid treating output improvement as proof of workforce capability improvement. Productivity and learning must be measured separately.

### 1.3 The jagged frontier makes domain knowledge more—not less—important

The idea of a jagged technological frontier captures a central operational reality: AI capability is uneven across tasks, and the boundary is difficult to identify in advance. In the 758-person field experiment by Dell’Acqua and colleagues, AI improved results on tasks inside the frontier, but use of AI could reduce performance on tasks outside it. These tasks could appear similar in difficulty to those where AI performed well. [[4](https://doi.org/10.1287/orsc.2025.21838)]

This is more difficult to manage than a simple list of tasks that are “safe for AI” and “unsafe for AI.” Capability can vary by task formulation, context, data quality, constraints, and the system’s current version. An AI system that is effective in one part of a workflow may be unreliable in another. A system’s fluency can also make a weak answer appear more authoritative than it deserves.

The operational implication is that people need more than the ability to operate a tool. They need enough domain understanding to recognize when the tool is operating outside the conditions in which it can be relied upon. That does not mean every user must be an expert in every detail. It means organizations must decide where expertise resides, how it is accessed, and how it is brought into decisions when the system encounters uncertainty or consequence.

### 1.4 Prediction, judgment, and decision-system redesign

Agrawal, Gans, and Goldfarb frame AI as lowering the cost of prediction. Their subsequent work emphasizes that decisions combine prediction with judgment: AI may make certain predictions cheaper, but organizations still need to determine objectives, trade-offs, constraints, and the actions to take. [[9](https://store.hbr.org/product/power-and-prediction-the-disruptive-economics-of-artificial-intelligence/10580)]

This is a useful way to understand why AI adoption often requires more than adding a tool to an existing process. If prediction becomes cheaper, the number and timing of decisions may change. A company may make decisions more frequently, at a finer level of detail, or with more information. That can shift authority, coordination, and risk across the organization.

For example, an AI system that predicts which maintenance event is likely to occur is not merely automating a report. It may change inventory policy, maintenance schedules, production commitments, staffing, and supplier interactions. The value is created—or lost—through the design of the connected decision system.

The greatest opportunity may therefore lie not in automating individual tasks, but in redesigning how interdependent decisions are made. That requires organizations to examine the full process: what information enters, who defines the objective, who interprets predictions, who can authorize action, who absorbs the consequences, and how learning from the outcome changes future decisions.

### 1.5 Polanyi’s paradox is changing, not disappearing

Michael Polanyi’s observation that people “know more than they can tell” has been influential in explaining why human work has historically resisted complete codification. Tacit knowledge includes learned pattern recognition, practical judgment, contextual sensitivity, and skills that are difficult to express as explicit rules. David Autor used Polanyi’s paradox to analyze the limits of computerization and the changing content of work. [[7](https://www.nber.org/papers/w20485)]

Modern machine-learning systems can infer patterns from examples and perform tasks that once depended on tacit human capabilities. But this does not establish that tacit knowledge has disappeared or that machines have acquired human understanding in a general sense. A system may reproduce a pattern without possessing the broader situational awareness, responsibility, or experiential understanding that a human brings to a particular context.

The organizational challenge has shifted. Some previously tacit patterns can now be approximated by AI. Other knowledge remains local, embodied, relational, context-dependent, or tied to accountability. Still other knowledge may become more important because AI makes it easier to act at scale.

Organizations should not assume that their experienced workers’ knowledge will automatically transfer into models, manuals, or prompts. Nor should they assume that an AI-generated answer can substitute for the experience needed to know when a rule does not apply.

### 1.6 Exposure is not the same as job loss

The ILO’s 2025 refined occupational exposure index estimates that one in four workers globally are in occupations with some exposure to generative AI. It identifies clerical occupations as having the highest exposure and concludes that job transformation is more likely than full automation for most occupations because they include tasks requiring human input. [[5](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure)]

This is an exposure measure, not a forecast that one in four jobs will disappear. It indicates that tasks within those occupations may be affected. The actual employment outcome depends on adoption, organizational redesign, demand, regulation, investment, and the creation of new tasks.

The same caution applies to predictions of a “barbell” labor market in which entry-level AI operators and senior architects grow while mid-level implementers disappear. Such a pattern is possible in some functions, but it is not established as a universal result. Organizations should model several workforce scenarios rather than treat one forecast as inevitable.

A credible workforce strategy must consider not only what technology can perform, but also what customers will demand, what new services become viable, how productivity gains are distributed, what labor costs do, and whether organizations invest in new human roles.

---

## 2. The human role: much more than checking AI output

### 2.1 Why “from generation to evaluation” is too narrow

A common description of the changing human role is a shift from creating outputs to evaluating machine-generated outputs. That is an important change, but it is not a sufficient model of human contribution.

If organizations define the human role primarily as reviewing AI work, they risk creating a workforce of downstream inspectors: people who are expected to identify errors in outputs they did not create, often under time pressure and with limited access to the context that produced them.

The human contribution in an AI-enabled organization is broader. Depending on the task, people may be responsible for:

- **Framing the problem:** determining what needs to be solved, what is in scope, and what a useful outcome means.
- **Defining objectives and constraints:** specifying priorities, tolerances, risk appetite, legal requirements, and unacceptable outcomes.
- **Supplying context:** bringing local, relational, historical, organizational, and situational information that may be missing from the system.
- **Designing the work:** deciding how tasks, decisions, and responsibilities should be divided between people and AI.
- **Interpreting and judging:** evaluating alternatives, trade-offs, ambiguity, and consequences.
- **Challenging assumptions:** testing whether the AI’s framing, evidence, and recommendations are appropriate.
- **Managing exceptions:** recognizing novel situations, conflicting information, edge cases, and conditions outside the system’s authorized scope.
- **Building relationships:** handling trust, negotiation, empathy, conflict, and communication where human interaction is part of the value.
- **Learning and adapting:** using outcomes, failures, and feedback to improve the process and the system.
- **Accepting responsibility:** ensuring that decisions are authorized, defensible, and aligned with the organization’s obligations.

The objective is not to label all these activities as uniquely human forever. AI capability will continue to change. The point is that organizations must explicitly decide which of these activities require human judgment, which can be supported by AI, and which can be delegated under defined constraints.

### 2.2 Knowing how to use AI versus knowing how to think with AI

Tool proficiency is necessary but insufficient. Employees need to know how to formulate a useful request, provide the right information, understand system limitations, and use the available controls. Yet competent use requires a deeper form of engagement.

Thinking with AI means being able to work through a problem while preserving independent judgment. A capable user can:

1. State the problem before asking the AI to solve it.
2. Identify what is known, unknown, assumed, and uncertain.
3. Provide relevant context and constraints.
4. Ask the system to make its assumptions explicit or identify missing information.
5. Consider alternative explanations or solutions.
6. Check important claims against independent evidence.
7. Recognize when the answer is plausible but not sufficiently supported.
8. Decide whether to accept, adapt, reject, or escalate the proposal.
9. Explain the reasoning behind the decision and its consequences.

This is not merely prompt engineering. It combines domain knowledge, critical inquiry, confidence calibration, information literacy, and the ability to recognize the boundaries of one’s own competence.

A 2025 CHI study based on 319 knowledge workers and 936 examples of workplace GenAI use found that critical thinking in AI-assisted work often shifted toward information verification, response integration, and task stewardship. It also found that greater confidence in AI was associated with less reported critical-thinking effort, while greater task-specific self-confidence was associated with more. The study is based on workers’ self-reports, not a longitudinal demonstration that AI causes permanent loss of critical-thinking ability. [[12](https://doi.org/10.1145/3706598.3713778)]

The result is still operationally important: an organization cannot assume that providing access to AI tools creates skilled AI users. It must develop people who can question the system, and it must design the workflow so that questioning is feasible and valued.

### 2.3 The capability paradox: execution can be both a cost and a learning mechanism

The capability paradox emerges when an organization treats foundational execution only as labor cost. Routine work can be repetitive, inefficient, and suitable for automation. But it can also be the environment in which employees learn how the organization works, understand the exceptions to formal rules, and develop the mental models that make expert judgment possible.

A junior analyst who repeatedly reconciles imperfect data learns where errors originate. A maintenance technician who performs inspections learns what abnormal conditions look and feel like. A software engineer who debugs a system learns how components interact. A property manager who handles tenant issues learns how policy, building conditions, vendor performance, and resident expectations intersect.

If AI performs these tasks before the worker develops a useful understanding of them, the organization may gain immediate capacity while weakening the future supply of experienced professionals. But the reverse is also possible: AI can make the practice more accessible by providing coaching, feedback, examples, and progressively challenging exercises.

The real question is not whether humans should continue doing work that AI can do. It is whether the work contains learning value that must be preserved by some deliberate means.

That means distinguishing three things that are often grouped together:

- **Execution value:** the value of completing the task itself.
- **Learning value:** the value of performing the task as a way to develop knowledge, judgment, and skill.
- **Control value:** the value of retaining the ability to perform, diagnose, or take over the task when automation fails.

A task may have low execution value after automation but high learning or control value. Organizations need a way to retain the latter without unnecessarily preserving all the former.

### 2.4 Expertise is not just information stored in a person’s head

Expertise consists of more than recall. It includes structured mental models, pattern recognition, causal reasoning, knowledge of failure modes, an understanding of what is normal, and the ability to detect when a situation does not fit expectations.

Situational awareness research describes how operators perceive relevant information, comprehend what it means, and project what may happen next. These processes depend on attention, workload, mental models, and the design of the surrounding system. [[15](https://doi.org/10.1518/001872095779049543)]

This explains why a person can possess access to a large amount of information and still be unprepared to intervene. A dashboard may show the current state without helping the operator understand why it has changed. An AI agent may provide a summary without exposing the assumptions or actions that led to it. A reviewer may see the final answer but lack the experience needed to recognize a subtle error.

The capability objective is therefore not merely to make information available. It is to develop and sustain the capacity to interpret information in context.

---

## 3. The human factors challenge: oversight can fail even when a person is present

### 3.1 Cognitive load and the verification burden

Cognitive Load Theory explains why learning and complex performance are constrained by the interaction between working memory and long-term knowledge structures. It distinguishes the demands intrinsic to the task from demands created by the way information and work are presented, and from the mental effort involved in learning and constructing useful knowledge structures. [[10](https://doi.org/10.1007/s10648-019-09465-5)]

The original report described AI as absorbing intrinsic load and shifting the burden to extraneous load. That is too simple as a general rule. AI may reduce some demands, introduce others, or change the nature of the work. The outcome depends on the task, the user’s expertise, the interface, the quality of the output, and the degree to which the worker must reconstruct context or verify hidden assumptions.

For example, AI can reduce the effort involved in drafting a routine report. It can simultaneously increase the effort needed to check whether the report uses the correct data, captures the local situation, and does not omit a critical exception. Conversely, AI may reduce cognitive demand when it organizes information in a way that helps an expert see a pattern more clearly.

The phrase **verification tax** is useful as a management concept for the additional human effort required to establish that AI-generated work is acceptable. It should not be presented as a formal, universally measured academic construct. The cost can include checking source data, reconstructing reasoning, testing code, validating calculations, confirming policy compliance, reviewing external effects, and monitoring downstream consequences.

A verification process becomes especially expensive when the reviewer did not participate in forming the solution and cannot readily reconstruct how it was produced. The organization may therefore transfer work from one role to another rather than eliminate it. The relevant productivity measure is not the time saved by the AI user, but the total cost and quality of the end-to-end workflow.

Working memory limits are real, but they should not be turned into a simplistic fixed number. Cowan’s review argues for a capacity of roughly four chunks under specified conditions, while emphasizing that the estimate depends on what counts as a chunk and the conditions of measurement. [[11](https://doi.org/10.1017/S0140525X01003922)] In practice, expertise and long-term memory change what a person can process efficiently. A well-designed system should therefore reduce unnecessary cognitive burden and support expert interpretation, not assume that all people have the same fixed capacity.

### 3.2 Automation bias and complacency

Automation bias describes the tendency to over-rely on automated advice, including when it is incorrect. A systematic review of 74 studies found that automation bias was influenced by user characteristics, system design, trust, workload, task complexity, and time pressure. Proposed mitigations included training, accountability, better presentation of advice, updated confidence information, and presenting information rather than only a recommendation. [[13](https://doi.org/10.1136/amiajnl-2011-000089)]

Automation complacency is related but distinct: the operator does not monitor the system adequately, often because the automated process appears to be functioning reliably or because monitoring competes with other work. Parasuraman and Manzey’s review shows that both phenomena can occur in experienced as well as novice users. Simple instructions to “remain vigilant” are not a sufficient control. [[14](https://doi.org/10.1177/0018720810376055)]

These risks become more serious when organizations design oversight as a high-volume approval queue. If every action produces an alert, reviewers learn to process alerts quickly. If a human is expected to approve decisions without adequate context, authority, or time, the presence of a human becomes a procedural ritual rather than an effective control.

The answer is not to train employees to pay more attention while preserving a poor operating model. Organizations must reduce unnecessary review demand, direct human attention to meaningful exceptions, provide sufficient context, and make it possible to challenge or stop the process. The *Mata v. Avianca* sanctions order illustrates the professional consequences of treating generated material as if it had been independently verified: attorneys submitted nonexistent judicial opinions and fabricated quotations generated by ChatGPT, and the court held that they had abandoned their gatekeeping responsibilities. The case is specific to legal filings, but the broader lesson is that using AI does not remove the accountability of the professional or organization that relies on its output. [[26](https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1%3A2022cv01461/575368/54/)]

### 3.3 The out-of-the-loop problem

The out-of-the-loop (OOTL) performance problem has been documented in automation research for decades. When a person is removed from active control and reduced to monitoring, the operator may lose situational awareness and be slower or less capable when required to take over after an automation failure. Endsley and Kiris demonstrated this in a navigation task and found that the level of operator control affected the loss of situation awareness. [[16](https://doi.org/10.1518/001872095779064555)]

This has direct implications for agentic AI. A human who only receives notifications after an AI system has performed a long sequence of actions may not understand the current state, intermediate decisions, or dependencies well enough to intervene effectively.

The problem is not solved by keeping a person nominally “on the loop.” The operator must have a way to maintain an accurate mental picture of the process, understand what the system is doing, and take action that can realistically change the outcome.

The organization should ask:

- Does the human have enough information to understand the current state?
- Are important changes and exceptions surfaced in time?
- Can the human distinguish normal variation from meaningful deviation?
- Can the human interrupt or reverse the action?
- Is the operator trained to intervene, and does the workflow allow sufficient time?
- Is there a tested fallback when the system is unavailable, compromised, or wrong?

### 3.4 The irony of automation: humans inherit the abnormal conditions

Bainbridge’s classic “Ironies of Automation” paper identifies a recurring design problem: as automation takes over routine operations, the human may be left responsible for monitoring and handling the unusual conditions that the automated system cannot manage. Those abnormal situations can be more difficult precisely because the human has had fewer opportunities to practice direct control. [[17](https://doi.org/10.1016/0005-1098%2883%2990046-8)]

This is especially relevant to agentic systems that execute multi-step workflows. The human may be expected to handle the most complex, ambiguous, and consequential exceptions while having the least direct involvement in the routine actions that would build familiarity with the process.

It is not enough to train employees on the normal path and assume they will manage exceptions. Organizations must deliberately develop exception-handling capability, conduct realistic exercises, and design systems that preserve the information and authority needed to respond.

### 3.5 Human oversight is a design problem and an operational problem

The design of human involvement and the operation of human involvement must be treated separately.

**Designing human involvement** means deciding in advance:

- Which actions can be delegated?
- Which decisions must remain human-led?
- What risk thresholds trigger a pause, review, or escalation?
- What information must be presented before a decision?
- Who has authority to approve, override, stop, or reverse an action?
- What happens when the human is unavailable?
- What evidence must be retained for audit and learning?

**Operating human involvement** means ensuring that people can actually perform those responsibilities:

- Detect changes and anomalies.
- Interpret system behavior and context.
- Challenge an apparently plausible recommendation.
- Recognize personal knowledge limits.
- Give feedback that improves the process.
- Decide whether to continue, constrain, delegate, intervene, or escalate.
- Manage workload and attention so that important warnings are not lost.
- Explain and document consequential decisions.

The distinction matters because an organization can design a theoretically sound governance process that fails in day-to-day operation. A well-written rule does not create the time, knowledge, confidence, authority, and system visibility needed to act on it. The automation literature has long distinguished different stages and levels of human interaction—from information acquisition and analysis to decision selection and action—rather than treating human involvement as a single on/off state. [[18](https://doi.org/10.1109/3468.844354)]

### 3.6 Human-AI collaboration is not automatically complementary

Organizations often assume that combining human judgment with AI capability will produce better performance than either can achieve alone. The assumption is plausible, but evidence does not support treating it as automatic.

A preregistered systematic review and meta-analysis examined 106 experimental studies and 370 effect sizes. On average, human-AI combinations performed worse than the better-performing human-only or AI-only condition. The findings varied by task: human-AI combinations were more promising in content-creation tasks, while decision-making tasks showed performance losses on average. [[8](https://www.nature.com/articles/s41562-024-02024-1)]

This finding changes the design question. The goal should not be “put a human and AI together.” The goal should be to establish **complementarity**: each side contributes capabilities that the other lacks, the responsibilities are partitioned sensibly, the interaction supports rather than obstructs judgment, and the combined system is tested against credible alternatives.

Human-AI collaboration can fail because the roles overlap without adding value, the AI anchors human judgment, the human lacks enough expertise to challenge the result, or the interface forces the person to process too much information. It can also fail because the human is involved at the wrong point in the process.

The organization should compare at least four operating modes for consequential workflows:

1. Human-only performance.
2. AI-only performance within an authorized scope.
3. Human-led performance with AI assistance.
4. AI-led performance with defined human intervention and independent review.

The best model may differ across stages of the same process. It should be demonstrated by evidence, not presumed.

---

## 4. A broader organizational strategy: a portfolio of interventions

There is no single intervention that closes the human capability gap. Training alone cannot compensate for a workflow that overwhelms reviewers. Governance alone cannot create expertise. More human approvals cannot ensure control. Better AI interfaces cannot solve poor incentives. The strategies below are intended to be combined selectively according to the type of work, risk, scale, workforce, and maturity of the organization.

### 4.1 Strategy one: redesign the work, not just the task

**Purpose:** Recompose roles and workflows so that automation reduces low-value effort while human contribution shifts toward activities that need context, judgment, relationship, coordination, or responsibility.

A useful first step is to map the work at task level rather than job-title level. For each activity, assess:

- The degree to which it is repetitive and rules-based.
- The availability and quality of relevant data.
- The degree of uncertainty and contextual variation.
- The consequences of an incorrect result.
- Whether the activity is reversible.
- The level of human judgment and relationship involved.
- Whether performing the activity develops foundational expertise.
- Whether the organization needs a human fallback capability.

Then classify each task into one of five pathways:

| Pathway | Meaning | Typical organizational response |
|---|---|---|
| **Automate** | AI can complete a bounded task reliably under defined conditions. | Remove unnecessary manual execution; retain controls, auditability, and exception handling. |
| **Augment** | AI improves human performance but the human remains the primary actor. | Provide recommendations, synthesis, retrieval, drafting, simulation, or decision support. |
| **Delegate within boundaries** | AI may execute a sequence of actions under explicit permissions and limits. | Use action policies, thresholds, monitoring, exception routing, and interruption mechanisms. |
| **Retain human leadership** | The activity requires human authority, discretion, or responsibility. | Use AI for supporting evidence and preparation; preserve human decision rights. |
| **Create or expand** | New work becomes valuable because AI changes what can be done or makes new services feasible. | Develop new roles, services, controls, customer interactions, and improvement capabilities. |

These categories should not be static. A task can move between them as systems improve, data quality changes, regulation evolves, or the organization learns more about failure modes. Work-design research also reinforces the importance of designing jobs with an appropriate mix of skill variety, problem-solving, feedback, autonomy, social connection, and manageable demands—not merely optimizing task throughput. [[19](https://doi.org/10.1002/hrm.22200)]

**Possible approaches**

- **Workflow decomposition:** break a process into decisions, information flows, approvals, communications, and actions. Identify where AI creates value and where it changes dependencies.
- **End-to-end redesign:** redesign the process around a new division of work rather than adding AI to each existing step.
- **Human-first and AI-first alternatives:** test more than one workflow design. Sometimes the most productive model is AI-first; sometimes AI should prepare options for a human to decide.
- **Exception-centered operations:** allow routine, low-risk steps to proceed automatically while routing unusual, uncertain, or consequential cases to qualified people.
- **Role reconstruction:** redefine jobs around the complete set of activities that remain valuable, including customer relationships, exception resolution, systems improvement, and accountability.
- **New-service exploration:** use AI-enabled capacity to develop services that were previously uneconomic, rather than directing all productivity gains toward headcount reduction.

This strategy requires management to look beyond individual task time. If the AI saves ten minutes in one step but creates fifteen minutes of review, correction, or rework elsewhere, the process has not improved. Measure the total workflow.

### 4.2 Strategy two: design several forms of human involvement, not one universal HITL gate

**Purpose:** Match the type and timing of human involvement to the nature of the decision and the consequences of failure.

A simple autonomy ladder can help, but it should not be treated as a universal classification. The appropriate level of human involvement depends on risk, reversibility, uncertainty, scale, speed, regulatory requirements, and the quality of available monitoring.

The following patterns can be combined across a workflow:

| Human involvement pattern | What the human does | When it is useful |
|---|---|---|
| **Human defines policy and boundaries** | Sets objectives, limits, permissions, prohibited actions, and exception rules before execution. | Repetitive processes where individual review would create needless friction. |
| **Human approves before action** | Reviews a proposed action before it is executed. | High-consequence, difficult-to-reverse, or legally restricted actions. |
| **Human supervises a live process** | Watches meaningful process indicators and intervenes when thresholds are crossed. | Dynamic processes where early intervention can prevent harm. |
| **Human handles exceptions** | Takes over cases outside normal parameters or where the AI expresses uncertainty. | High-volume workflows with predictable routine cases and a smaller proportion of complex ones. |
| **Human conducts independent review** | Tests outcomes, samples cases, audits decisions, and looks for systemic bias or drift. | Processes where continuous approval is impractical but assurance is essential. |
| **Human maintains fallback capability** | Can resume or reconstruct the process when AI is unavailable or unsafe. | Critical operations and processes where continuity matters. |
| **Human owns the consequential decision** | Uses AI evidence but retains authority for the final decision. | Decisions involving rights, safety, livelihood, major commitments, or significant ethical discretion. |

A risk-based delegation model should consider at least six dimensions:

1. **Impact:** What harm could occur if the action is wrong?
2. **Reversibility:** Can the action be undone, and at what cost?
3. **Uncertainty:** How often does the system encounter unfamiliar cases or incomplete information?
4. **Scale:** How many people, transactions, or assets can be affected before the error is detected?
5. **Time sensitivity:** How much time is available for a human to intervene?
6. **Detectability:** Can the organization identify an error before it produces downstream consequences?

This produces more useful distinctions than a simple “human in the loop” label. For instance, an AI system may be permitted to draft and route an internal document without approval, but not to issue an external commitment. It may recommend a maintenance action automatically but require a qualified technician to authorize a safety-critical shutdown. It may process routine service requests but route unusual or vulnerable-customer cases to a trained employee.

**Controls against approval fatigue**

- Do not require approval for every low-risk system action.
- Group low-risk notifications into summaries and surface only material exceptions in real time.
- Use risk-triggered escalation instead of fixed approval quotas.
- Make the reason for an escalation clear.
- Give reviewers enough context to assess the decision.
- Rotate or share oversight duties where sustained vigilance would otherwise become monotonous.
- Monitor review volume, time pressure, override rates, missed exceptions, and reviewer workload.
- Periodically test whether humans can detect deliberately introduced errors.

A review queue should be treated as a scarce organizational resource. Human attention should be directed toward decisions where it can change the outcome.

### 4.3 Strategy three: make AI systems observable, contestable, and interruptible

**Purpose:** Ensure that humans can understand enough about what the system is doing to supervise it effectively.

An AI system that exposes only a final answer or status light is difficult to oversee. This is particularly problematic when the system can call tools, access data, create sub-tasks, communicate externally, or change operational state.

Effective observability does not require exposing every internal computation. It requires meaningful operational evidence:

- What objective is the agent pursuing?
- What instructions, permissions, and policies govern it?
- What data sources and records did it use?
- What actions has it taken, and what remains pending?
- What decisions or assumptions materially changed the plan?
- Which thresholds have been reached?
- What uncertainty or missing information has been identified?
- What exceptions were encountered and how were they resolved?
- What external systems or people have been affected?
- Who can pause, reverse, or terminate the process?

**Possible approaches**

- **Action logs:** maintain a trace of material actions, tool calls, approvals, data access, and external communications.
- **Decision summaries:** present concise explanations of the current state, key assumptions, and reasons for escalation.
- **Data provenance:** identify the sources, freshness, and limits of the evidence supporting material outputs.
- **Confidence and uncertainty communication:** avoid presenting unsupported precision. Show uncertainty in a way that helps the user decide what to verify.
- **Independent controls:** apply permissions and transaction limits outside the model itself. Do not rely on the model to police its own authority.
- **Interruption mechanisms:** provide tested pause, stop, rollback, and recovery capabilities.
- **Exception dashboards:** present anomalies and operational risks in ways that are meaningful to the people responsible for action.
- **Human-readable handoffs:** ensure that when a person takes over, the system transfers relevant history, context, and pending actions rather than simply producing a generic alert.

The control environment should be designed so that the human does not need to reconstruct the entire process from scattered logs during an incident.

### 4.4 Strategy four: protect expertise formation through redesigned learning pathways

**Purpose:** Ensure that automation does not remove the experiences through which employees acquire the knowledge needed for future judgment.

The original proposal to mandate manual execution rotations is one possible intervention, but it should not be the default answer for every role. Requiring employees to perform all tasks manually can waste time, create artificial work, or fail to teach the capabilities the organization actually needs. The better approach is to identify which knowledge and judgment a task develops and then choose the most effective way to develop them.

A capability-preservation strategy can draw on several complementary methods.

**A. Structured apprenticeship**

Pair less experienced employees with experienced practitioners on real cases. The experienced worker explains not only what action is taken but why, what alternatives were considered, what signals matter, and what would change the decision.

Useful practices include:

- Observe an expert handling a case.
- Perform the task with guidance.
- Explain the reasoning before receiving the expert’s answer.
- Compare the employee’s decision with the expert’s decision.
- Review unusual and failed cases.
- Gradually increase the complexity and independence of the work.
- Have the learner teach the process back to another person.

This approach transfers judgment and context, not just procedural steps.

**B. Deliberate practice on selected foundational tasks**

Retain direct practice where it develops skills that are difficult to acquire through passive observation. The goal is not to preserve all manual work; it is to preserve the practice necessary to build critical mental models.

Examples include:

- Diagnosing a problem before consulting AI recommendations.
- Reviewing original data before accepting a generated analysis.
- Writing an initial solution outline before asking AI to complete it.
- Performing manual calculations periodically to understand model assumptions and error ranges.
- Debugging representative examples without AI assistance.
- Conducting customer or field observations rather than learning only from summaries.

The organization should choose these exercises based on the capabilities they develop and the cost of losing those capabilities.

**C. AI as a tutor rather than only an executor**

Configure AI tools to support the learning process:

- Ask the learner to attempt a solution before revealing one.
- Provide hints in stages rather than immediately supplying a finished answer.
- Explain why an answer is correct or incorrect.
- Generate progressively harder practice scenarios.
- Ask the learner to identify assumptions and missing information.
- Compare multiple plausible approaches.
- Require a teach-back or explanation of the final result.
- Provide feedback on the quality of the reasoning, not only the final output.

AI can make coaching more available, but the training design must preserve the learner’s active role. If the system simply produces completed work, it may optimize task completion while bypassing learning.

**D. Case libraries and exception learning**

Build a searchable internal library of real cases, including edge cases, failures, near misses, successful interventions, and decisions that changed after new evidence emerged.

Each case should record:

- The context and problem.
- What the system recommended or did.
- What the human noticed.
- Which assumptions or data were wrong or incomplete.
- What the correct action was and why.
- What could have made the issue easier to detect.
- Whether the workflow, policy, training, or system needs to change.

This preserves organizational memory and makes practical knowledge available beyond the person who originally acquired it.

**E. Simulation and adversarial practice**

Use AI to generate realistic, varied scenarios that test the ability to notice when a normal process has become abnormal. Scenarios can include incomplete data, conflicting instructions, policy exceptions, unusual customer needs, adversarial inputs, tool failures, and misleading but plausible recommendations.

Simulation should not focus only on whether the employee can identify a hallucination. It should test whether they can:

- Detect that a situation is outside the normal pattern.
- Gather the right information.
- Form an independent hypothesis.
- Decide whether to intervene.
- Explain the risk.
- Escalate to the right person.
- Recover the process safely.

**F. Cross-training and capability redundancy**

Do not allow critical knowledge to reside with a single expert or inside an AI system. Cross-train employees in the essential functions needed for continuity and create succession plans for specialized knowledge.

**G. Periodic manual or non-AI proficiency checks**

For selected high-consequence functions, periodically test whether qualified personnel can complete or recover essential tasks without AI support. This is not a recommendation to ban AI from routine work. It is a resilience measure to ensure that the organization has not lost the ability to operate when automation is unavailable or must be suspended.

### 4.5 Strategy five: redesign skills, roles, and career progression

**Purpose:** Align workforce development with the work that is emerging, rather than simply adding AI training to existing job descriptions.

Organizations often respond to new technology by training employees to use a tool while leaving roles, performance measures, and promotion criteria unchanged. This can create a mismatch: employees are asked to exercise more judgment but are still rewarded primarily for speed, volume, and procedural compliance.

A more complete strategy requires a review of:

- Job descriptions and task ownership.
- Entry-level and early-career development.
- Promotion criteria and evidence of expertise.
- Specialist and generalist career paths.
- Management responsibilities.
- Recruitment and internal mobility.
- Compensation and recognition for higher-responsibility work.
- The balance between human expertise and AI-enabled capacity.

**A. Build a capability framework**

A practical capability framework should include several related domains:

| Capability domain | What employees need to be able to do |
|---|---|
| **Domain foundations** | Understand the principles, rules, systems, data, and operational realities of their field. |
| **Problem framing** | Define the problem, clarify objectives, identify constraints, and distinguish symptoms from causes. |
| **Critical inquiry** | Ask what evidence supports a claim, identify assumptions, test alternatives, and challenge plausible but weak answers. |
| **Systems thinking** | Understand dependencies, downstream effects, failure propagation, and the relationship between local decisions and the wider process. |
| **Data and model literacy** | Understand data quality, statistical uncertainty, model limitations, provenance, and the difference between prediction and explanation. |
| **AI interaction and orchestration** | Select appropriate tools, structure tasks, provide context, coordinate agents, and manage handoffs. |
| **Judgment and decision-making** | Evaluate trade-offs, consequences, ambiguity, fairness, and alignment with organizational objectives. |
| **Operational intervention** | Detect exceptions, manage incidents, override or stop systems, and recover the process. |
| **Communication and relationships** | Explain decisions, negotiate, handle conflict, build trust, and engage with affected people. |
| **Learning and adaptation** | Reflect on outcomes, update mental models, recognize knowledge limits, and improve practice. |
| **Accountability and ethics** | Understand decision authority, professional obligations, privacy, safety, fairness, and escalation duties. |

Not every role needs the same depth in every domain. The framework should be role-specific and tied to actual decisions and risks.

**B. Create dual-track progression**

Employees should not be forced into a single path where the only way to advance is to stop doing technical or operational work and become a manager. AI-enabled organizations may need both:

- **Deep domain specialists** who understand systems, workflows, edge cases, and technical foundations.
- **Integrators and decision leaders** who coordinate people, AI, strategy, risk, and interdependent processes.

The organization should recognize the value of both. Otherwise, it may lose the people who can explain how the work actually functions.

**C. Rebuild the early-career pathway**

Entry-level tasks often provide the raw experience from which professional judgment develops. If those tasks are automated, the organization must deliberately create alternative routes into expertise.

Options include:

- Structured rotations across the process rather than repetitive low-value work.
- Supervised case ownership with gradually increasing complexity.
- Shadowing experts in difficult decisions and incidents.
- AI-supported practice environments using anonymized real cases.
- Short assignments that require first-principles problem solving.
- Participation in system testing, audits, and workflow improvement.
- Formal progression milestones demonstrating independent competence.

**D. Reassess what “experienced” means**

Years of service or familiarity with a particular tool should not be treated as sufficient proof of expertise. Employees need to demonstrate that they can explain the work, recognize abnormal conditions, reason about consequences, and act appropriately when AI support is wrong or unavailable.

### 4.6 Strategy six: build human-AI teams with explicit role partitioning

**Purpose:** Create genuine complementarity instead of placing people and AI side by side without a clear division of responsibility.

A human-AI team is not automatically a team in the organizational sense. To work well, the participants need compatible objectives, clear responsibilities, shared context, and a process for resolving disagreement.

Potential role configurations include:

- **AI as researcher; human as problem owner:** AI gathers and organizes evidence; the human defines the question and judges relevance.
- **AI as analyst; human as decision-maker:** AI generates forecasts or options; the human evaluates trade-offs and authorizes action.
- **AI as executor; human as exception manager:** AI performs bounded routine work; humans handle exceptions and review systemic performance.
- **AI as challenger; human as author:** AI identifies weaknesses, counterarguments, and edge cases in human work.
- **Human as expert; AI as apprentice:** the employee demonstrates and explains a task while AI captures procedures and creates training materials.
- **Human as orchestrator; AI agents as specialists:** a person decomposes a complex objective into tasks, delegates work to bounded agents, and integrates the results.
- **Independent human and AI analysis:** each produces a separate assessment before comparison, reducing the risk that the first AI answer anchors the human’s view.

The last pattern is particularly useful for important decisions. Instead of showing the reviewer the model recommendation first, the organization can ask the reviewer to form an initial judgment and then compare it with the AI’s recommendation. This does not eliminate bias, but it can help preserve independent reasoning.

For high-impact decisions, organizations can introduce a second human perspective, specialist review, or independent audit. The objective is not to add bureaucracy. It is to ensure that the decision receives the type of challenge its consequences warrant.

### 4.7 Strategy seven: realign incentives, performance management, and leadership behavior

**Purpose:** Ensure that the organization rewards good judgment and responsible intervention rather than merely rewarding faster output.

If employees are measured only by the number of tasks completed, they may accept AI-generated work that is fast but weak. If reviewers are measured by how quickly they clear an approval queue, they may rubber-stamp decisions. If managers are rewarded for headcount reduction without accountability for capability loss, they may dismantle the very expertise needed to sustain operations.

Performance systems should therefore balance:

- Speed and throughput.
- Quality and rework.
- Exception detection and resolution.
- Customer or stakeholder outcomes.
- Safety, compliance, and fairness.
- Learning and capability development.
- Effective escalation and intervention.
- Process resilience and recovery.
- Long-term value creation.

**Make challenge a positive behavior.** Employees should not be penalized for rejecting an AI recommendation when they provide a sound reason. Nor should they be rewarded simply for finding faults. The aim is disciplined challenge: knowing when to accept, question, correct, or escalate.

**Protect the right to pause.** People responsible for monitoring important AI processes need a credible ability to stop or constrain them without fearing automatic performance penalties. This authority should be bounded by policy and accompanied by clear escalation routes.

**Redesign management roles.** Managers may need to spend less time distributing routine tasks and more time designing workflows, building capability, coordinating human-AI teams, managing risk, and ensuring that technology improves the quality of work rather than simply intensifying it.

**Involve employees in redesign.** Employees often know where the real workarounds, exceptions, undocumented dependencies, and customer impacts exist. Their participation can improve system design and reduce resistance. OECD research on AI and job quality found that while many surveyed workers reported increased autonomy, about one in five said AI reduced their autonomy; it also identified concerns about work intensity, privacy, and reduced human interaction in some settings. [[20](https://www.oecd.org/en/publications/2023/07/oecd-employment-outlook-2023_904bcef3/full-report/artificial-intelligence-job-quality-and-inclusiveness_a713d0ad.html)] More recent OECD research on algorithmic management highlights managerial benefits alongside concerns about accountability, explainability, and worker health, and recommends worker consultation as part of responsible adoption. [[21](https://doi.org/10.1787/cda7a114-en)]

### 4.8 Strategy eight: use AI to extend organizational memory and knowledge transfer

**Purpose:** Capture and distribute expertise without confusing documented information with actual capability.

Organizations often depend on experienced employees whose knowledge is distributed across memory, relationships, habits, and informal practices. AI can help capture and make some of this knowledge more accessible, but the process must be structured.

Possible interventions include:

- Record expert walkthroughs of complex tasks.
- Capture decisions and the reasons behind them.
- Turn incident reviews into searchable case studies.
- Maintain process maps that include exceptions and decision points.
- Create knowledge assistants grounded in approved internal sources.
- Attach source provenance, dates, and ownership to knowledge records.
- Use AI to identify gaps and contradictions in documentation.
- Ask experts to review and correct generated knowledge artifacts.
- Establish a process for retiring outdated procedures and replacing obsolete knowledge.

A knowledge repository is not a substitute for expertise. An employee still needs the ability to interpret what is retrieved, decide whether it applies, and recognize when the documentation is incomplete. The goal is to reduce avoidable dependence on individual memory while supporting the human judgment that gives information meaning.

### 4.9 Strategy nine: treat AI as a capability-building platform

**Purpose:** Deliberately use AI to develop the very skills that organizations are concerned may erode.

Most adoption programs focus on using AI to do work. A more ambitious approach also uses AI to make workers better at work.

AI can serve as:

- A personalized tutor that adapts explanations to a learner’s current understanding.
- A simulator that creates realistic cases and uncommon exceptions.
- A coach that asks the employee to explain a decision.
- A debate partner that produces counterarguments and alternative hypotheses.
- A diagnostic assistant that helps identify gaps in a person’s knowledge.
- A translator that makes specialist knowledge more accessible to adjacent teams.
- A mentor-support tool that helps experienced employees turn tacit practices into teachable examples.
- A reflection aid that helps teams review decisions and outcomes after the event.

The critical design choice is whether AI is used to replace the learner’s thinking or to stimulate it. A tutoring configuration may deliberately withhold the full answer until the learner has made an attempt. A simulation may require the employee to decide what information to seek. A critique tool may challenge the employee’s reasoning instead of simply improving the prose.

This approach can create a virtuous cycle: AI handles selected execution, supports deliberate learning, and makes more people capable of handling higher-value work. It should be tested against actual performance and retention, not assumed to work because the interaction feels educational.

### 4.10 Strategy ten: strengthen governance, rights, and accountability

**Purpose:** Ensure that responsibility, authority, and oversight remain clear as AI systems become more autonomous.

Governance should be embedded in the operating model, not maintained as a separate policy document. It should cover the entire lifecycle: selection, procurement, data access, configuration, testing, deployment, monitoring, change management, incident response, and retirement.

A practical governance framework should address:

| Governance area | Organizational requirement |
|---|---|
| **Ownership** | Assign a business owner, technical owner, risk owner, and accountable executive for each material system. |
| **Identity and access** | Give agents identifiable identities and permissions limited to their approved purpose. |
| **Scope and boundaries** | Define allowed actions, prohibited actions, spending limits, data access, and escalation conditions. |
| **Human authority** | Specify who may approve, override, suspend, or terminate the system. |
| **Evidence and traceability** | Retain logs of material actions, data sources, approvals, model versions, and changes. |
| **Testing** | Test normal performance, edge cases, misuse, security threats, and recovery. |
| **Monitoring** | Track quality, drift, anomalies, complaints, fairness, and control failures. |
| **Incident management** | Define reporting, containment, rollback, investigation, remediation, and communication. |
| **Change control** | Reassess risk when the model, agent, data, tools, permissions, or workflow changes. |
| **Workforce impact** | Assess effects on skill development, role quality, workload, autonomy, and accountability. |

The NIST AI Risk Management Framework and its Generative AI Profile provide voluntary guidance for identifying and managing AI risks throughout design, development, use, and evaluation. [[22](https://doi.org/10.6028/NIST.AI.600-1)] ISO/IEC 42001 specifies requirements for an AI management system and continual improvement within an organization. [[23](https://www.iso.org/standard/42001)] For organizations subject to the EU AI Act, Article 14 sets human-oversight requirements for high-risk AI systems, including the need for oversight measures proportionate to risk, autonomy, and context of use. [[24](https://eur-lex.europa.eu/eli/reg/2024/1689)]

These frameworks are not substitutes for a tailored operating model. They provide structures that organizations can use to identify responsibilities, controls, evidence, and continuous-improvement processes. Legal duties vary by jurisdiction and application; organizations should obtain appropriate legal and compliance advice rather than infer obligations from a general framework.

### 4.11 Strategy eleven: preserve human legitimacy in decisions affecting people

**Purpose:** Ensure that AI-enabled decisions remain understandable, fair, reviewable, and open to challenge.

A decision can be statistically accurate and still be considered illegitimate by the person affected if the process is opaque, inaccessible, or insensitive to relevant context. This is particularly important in recruitment, performance management, customer eligibility, service allocation, credit, education, and other decisions that affect people’s opportunities or rights.

Research on perceived fairness in algorithmic recruiting finds that applicants do not automatically regard algorithmic decisions as fairer than human decisions; transparency and the way the process is presented can affect perceptions of fairness. [[25](https://doi.org/10.1111/isj.12482)]

Organizations should consider:

- Whether the affected person knows AI was used.
- Whether the decision can be explained in meaningful terms.
- Whether the person can correct inaccurate data.
- Whether there is a route to appeal or request human review.
- Whether the reviewer has authority to change the outcome.
- Whether the process accommodates unusual circumstances.
- Whether the system creates disproportionate effects for particular groups.
- Whether the organization can demonstrate that the decision was made under appropriate rules.

The legal and ethical obligations will differ by context, but the management principle is broad: a nominal human reviewer is not enough if the affected person cannot obtain a meaningful reconsideration.

### 4.12 Strategy twelve: manage the distributional consequences of productivity gains

**Purpose:** Avoid capturing short-term efficiency while neglecting the workforce, knowledge, and institutional capacity that make sustainable performance possible.

Automation can displace labor from existing tasks, while new tasks may create new demand for human contribution. The balance is not predetermined. [[6](https://doi.org/10.1257/jep.33.2.3)] Organizations must therefore make explicit choices about how productivity gains will be used.

Possible uses include:

- Reducing cost and increasing margins.
- Increasing output or service capacity.
- Improving quality and reducing backlogs.
- Reducing employee workload and burnout.
- Investing in new products or services.
- Funding training and capability development.
- Redeploying staff into higher-value work.
- Improving customer experience.
- Increasing resilience and service continuity.

These choices have different consequences for the workforce and the organization’s long-term capabilities. If an organization uses all productivity gains to reduce headcount, it may lose critical domain expertise, reduce its capacity to manage exceptions, and weaken the internal pipeline for future specialists. If it retains all labor without redesigning work, it may fail to realize the economic benefits of the technology. It should also recognize that technology adoption often depends on complementary investments in processes, skills, data, and organizational structures; the full productivity benefits may not appear until those investments are made. The productivity J-curve research explains why these intangible complements can be undercounted in early assessments of general-purpose technologies. [[27](https://doi.org/10.1257/mac.20180386)]

A deliberate workforce transition plan should identify which roles are likely to change, which capabilities will become more important, which employees can be redeployed, what training is needed, and how the organization will preserve scarce expertise.

---

## 5. A practical framework for choosing among the strategies

Not every organization should implement every intervention. A smaller organization may not need a large AI governance office, but it still needs clear ownership, limits, and incident procedures. A highly regulated organization may require formal human approval and independent validation for specific decisions. A company automating low-risk internal administration may focus more on workflow redesign, data quality, and employee capability.

The choice should be based on the characteristics of the workflow rather than the organization’s enthusiasm for a particular AI architecture.

### 5.1 Select strategies according to the nature of the work

| Work characteristic | Primary organizational concern | Strategies to prioritize |
|---|---|---|
| High volume, repetitive, low consequence, reversible | Avoid unnecessary human bottlenecks while detecting unusual cases. | Workflow redesign; bounded delegation; exception handling; sampling and audit; observability. |
| High volume, consequential, partly standardized | Maintain throughput without turning review into rubber-stamping. | Risk-based human involvement; independent checks; escalation; reviewer capability; quality and fairness monitoring. |
| Low volume, high consequence, difficult to reverse | Ensure that authority, evidence, and judgment remain with qualified people. | Human-led decisions; specialist review; documented rationale; independent challenge; clear accountability. |
| Complex, variable, context-dependent | Avoid over-delegating work that requires local knowledge or nuanced interpretation. | Augmentation; expert-led analysis; context capture; scenario testing; domain-specific training. |
| New or poorly understood workflow | Learn where AI is capable before granting broad authority. | Controlled pilots; shadow mode; paired operation; structured experiments; frequent review. |
| Critical process with high continuity requirements | Preserve ability to recover from automation failure. | Manual fallback; cross-training; simulation; recovery drills; operational logs. |
| Work that develops foundational expertise | Avoid removing the only meaningful route to learning. | Apprenticeship; deliberate practice; AI tutoring; case learning; progressive autonomy. |
| Work involving rights, opportunities, or sensitive personal outcomes | Preserve legitimacy, fairness, contestability, and meaningful review. | Human decision authority; transparent process; appeal routes; bias assessment; stakeholder consultation. |

### 5.2 Use a capability-and-risk assessment before deployment

For each candidate workflow, assess the following dimensions on a defined scale and record the evidence behind the rating:

| Dimension | Assessment question |
|---|---|
| **AI task capability** | Has the system demonstrated reliable performance on representative cases, including edge cases? |
| **Human expertise requirement** | What domain knowledge is needed to detect errors and interpret the output? |
| **Learning significance** | Does performing this task build knowledge needed for future work? |
| **Consequence of failure** | What happens if the system is wrong, late, biased, or unavailable? |
| **Reversibility** | Can the action be corrected before harm occurs? |
| **Observability** | Can the organization see what the agent did and why action is needed? |
| **Intervention feasibility** | Does a human have enough time, information, skill, and authority to intervene? |
| **Workforce impact** | How will the change affect roles, workload, autonomy, progression, and skill formation? |
| **Complementarity evidence** | Does the proposed human-AI arrangement outperform credible alternatives? |
| **Continuity** | Can the organization continue safely if the AI system is unavailable or withdrawn? |

The assessment should end with a specific operating design: what the AI does, what the person does, what is monitored, what triggers escalation, who has authority, how expertise is maintained, and how performance will be evaluated.

### 5.3 Avoid treating “human oversight” as a binary variable

An oversight plan should specify the actual form of human involvement, not simply state that a human remains in the loop.

For example:

- **Before deployment:** A process owner defines scope, prohibited actions, acceptable performance, and decision rights.
- **During routine operation:** The system performs low-risk tasks within boundaries and records actions.
- **At exception points:** A trained operator receives the relevant context and decides whether to continue, correct, or escalate.
- **At consequential decisions:** A qualified person exercises the required authority, with access to independent evidence.
- **After execution:** Independent reviewers sample outcomes, investigate errors, and identify systemic patterns.
- **During failure:** A designated person can pause the system, activate a fallback process, and coordinate recovery.

This layered approach is more resilient than a single approval gate because it distributes oversight across the lifecycle and aligns intervention with actual risk.

---

## 6. Measuring whether human capability is improving

Organizations often measure AI adoption through license utilization, number of prompts, task volume, cost reduction, or time saved. These can be useful operational indicators, but they say little about whether the workforce is becoming more capable or whether human control is genuine.

A balanced measurement model should include at least five categories.

### 6.1 Productivity and service performance

- End-to-end cycle time, including review and rework.
- Throughput and completed work.
- Cost per completed outcome.
- Error rates and severity.
- First-time-right performance.
- Customer or stakeholder satisfaction.
- Time spent on exceptions and recovery.

### 6.2 Human capability and learning

- Ability to explain core concepts and process dependencies.
- Independent problem-solving performance on representative tasks.
- Accuracy in detecting deliberately introduced errors.
- Quality of reasoning before and after AI assistance.
- Ability to identify missing information and invalid assumptions.
- Performance in simulations and unfamiliar scenarios.
- Retention of critical skills over time.
- Rate at which employees progress to more complex work.

### 6.3 Oversight and control

- Number and severity of AI-related incidents.
- Rate of detected and undetected errors.
- Time to identify an anomaly.
- Time to intervene and recover.
- Quality of escalation decisions.
- Frequency and outcomes of overrides.
- Percentage of consequential actions with adequate traceability.
- Reviewer workload and approval time.
- False-positive and false-negative alert rates.

### 6.4 Workforce and organizational health

- Employee autonomy and decision authority.
- Role clarity and workload.
- Access to learning opportunities.
- Internal mobility and promotion.
- Retention of critical expertise.
- Employee confidence in challenging AI recommendations.
- Reports of overwork, cognitive overload, or monitoring pressure.
- Perceived fairness of AI-enabled work allocation and performance evaluation.

### 6.5 Resilience and adaptability

- Ability to operate during AI outage or withdrawal.
- Recovery performance after a failed agent action.
- Number of employees able to perform critical fallback tasks.
- Time required to onboard staff into changed workflows.
- Speed at which the organization incorporates lessons from incidents.
- Ability to redeploy people when automation changes task demand.

Measurements should be segmented by role, experience, task type, and level of AI involvement. An organization-wide average may conceal the fact that novices are gaining confidence while experts are losing time, or that productivity is improving while exception performance is deteriorating.

### 6.6 Test capability, not just confidence

Employees may report confidence in AI without being able to recognize its mistakes. Confidence surveys are useful, but they should be paired with performance-based evaluations.

Examples include:

- Blind tests in which the AI recommendation is sometimes deliberately flawed.
- Simulations with incomplete or conflicting data.
- Exercises that require employees to explain why a decision is safe.
- Tests of whether people can recover a workflow after an unexpected failure.
- Before-and-after assessments of foundational domain knowledge.
- Comparisons of human-only, AI-only, and human-AI performance on representative tasks.

This is essential because the objective is calibrated reliance, not maximum trust. A capable employee should know when to rely on AI, when to verify it, and when to refuse or escalate.

---

## 7. An implementation roadmap

The following roadmap provides a practical sequence. Organizations can adapt the timing and level of formality to their size, risk, and operating context.

### Phase 1: Establish the baseline

**Objective:** Understand where AI is already changing work and where capability risks may be emerging.

Actions:

1. Select a small set of important workflows rather than beginning with a broad enterprise-wide program.
2. Map the tasks, decisions, handoffs, tools, data, and exceptions in each workflow.
3. Identify current AI use, including informal or employee-initiated use.
4. Interview experienced practitioners and newer employees to understand where expertise is developed.
5. Identify high-consequence actions and critical fallback requirements.
6. Measure current cycle time, quality, rework, exception rates, and capability levels.
7. Record where accountability, authority, or process visibility is unclear.

Deliverables:

- Workflow maps.
- Task-level automation and augmentation inventory.
- Baseline workforce capability profile.
- Initial risk and control register.
- List of critical knowledge and expertise dependencies.

### Phase 2: Design the target operating model

**Objective:** Decide how work and decisions should be divided between people and AI.

Actions:

1. Classify tasks as automate, augment, bounded delegation, human-led, or new work.
2. Define the type of human involvement at each material decision point.
3. Establish permission boundaries and escalation conditions.
4. Determine which expertise must remain available internally.
5. Identify learning pathways for roles affected by automation.
6. Define performance measures across productivity, quality, learning, workforce health, and resilience.
7. Consult affected employees and process owners before finalizing the design.

Deliverables:

- Target workflow and role design.
- Human-AI responsibility matrix.
- Risk-based delegation policy.
- Skills and learning plan.
- Measurement framework.
- Employee consultation record.

### Phase 3: Pilot and test alternatives

**Objective:** Validate that the new arrangement improves outcomes without weakening human capability.

Actions:

1. Run the system in shadow mode where possible, comparing AI outputs with current decisions without allowing autonomous action.
2. Compare human-only, AI-only, and human-AI approaches on representative cases.
3. Test boundary conditions and edge cases.
4. Test how employees interpret explanations, alerts, and uncertainty.
5. Simulate AI failure, data gaps, unexpected behavior, and escalation.
6. Measure review burden and total process cost.
7. Test learning interventions such as AI tutoring, apprenticeship, and scenario practice.

Deliverables:

- Pilot results and performance comparisons.
- Documented failure modes and boundary conditions.
- Updated human oversight design.
- Updated training and workflow requirements.
- Go/no-go recommendation with evidence.

### Phase 4: Deploy with bounded authority

**Objective:** Scale the system gradually while preserving intervention capability and accountability.

Actions:

1. Assign named owners for the system, business process, and risk controls.
2. Apply least-privilege access and approved action boundaries.
3. Ensure logs, provenance, and escalation paths are operational.
4. Train staff for the actual operating and exception-handling roles.
5. Verify pause, rollback, and fallback mechanisms.
6. Establish regular quality, capability, and risk reviews.
7. Expand permissions only when performance evidence supports the change.

Deliverables:

- Approved production operating model.
- System and process ownership assignments.
- Operational playbooks.
- Training and proficiency records.
- Monitoring and incident procedures.

### Phase 5: Continuously adapt the organization

**Objective:** Keep the workforce, processes, and control environment aligned as AI capabilities and organizational needs change.

Actions:

1. Reassess tasks when the system, model, data, or workflow changes.
2. Review performance differences across experience levels and roles.
3. Monitor whether employees are losing foundational practice or gaining higher-value capability.
4. Update case libraries, training scenarios, and operating policies.
5. Revisit career paths and hiring requirements.
6. Evaluate whether productivity gains are being used to improve service, quality, capacity, and capability.
7. Retire controls that no longer add value and introduce new ones where risks emerge.

Deliverables:

- Periodic operating model reviews.
- Updated capability and workforce plans.
- Evidence of learning and resilience.
- Revised AI permissions and controls.
- Continuous improvement backlog.

---

## 8. Common failure patterns and their alternatives

| Failure pattern | Why it fails | More effective alternative |
|---|---|---|
| **AI is introduced as a point solution.** | Local efficiency improves while handoffs, accountability, and downstream work remain unchanged. | Redesign the end-to-end process and measure total workflow performance. |
| **A human approves every action.** | Review volume creates delay, fatigue, and rubber-stamping. | Use risk-based controls, exception handling, and independent audit. |
| **Employees are trained only to use prompts.** | Tool proficiency does not establish domain understanding or decision capability. | Train problem framing, verification, context, systems thinking, and operational intervention. |
| **Junior work is automated without replacing the learning pathway.** | Short-term efficiency can weaken the future supply of experienced practitioners. | Build apprenticeship, simulation, practice, progressive autonomy, and alternative entry-level work. |
| **Manual rotations are imposed indiscriminately.** | They can create artificial work without developing the right capability. | Identify which skills require direct practice and design targeted exercises. |
| **The AI’s explanation is treated as proof.** | Fluent explanations can still be incomplete or misleading. | Use source evidence, independent checks, testing, and traceable actions. |
| **A dashboard is treated as meaningful oversight.** | Information may be visible without being interpretable or actionable. | Provide context, thresholds, decision rights, and intervention capability. |
| **Productivity is measured only as time saved.** | Review, rework, risk, learning, and quality costs may be hidden. | Measure end-to-end value and workforce outcomes. |
| **Employees are punished for challenging AI.** | The organization discourages the very behavior needed to detect problems. | Reward evidence-based challenge and provide safe escalation paths. |
| **AI authority expands without retesting.** | Changes in models, data, tools, and workflow can invalidate earlier assumptions. | Reassess capability and risk before expanding autonomy. |
| **The organization assumes human-AI collaboration is always better.** | Poor role design can make combined performance worse than either side alone. | Compare alternatives and engineer complementarity. |
| **Knowledge is captured but not transferred.** | Documentation alone does not create practical skill or judgment. | Combine knowledge assets with supervised practice and teach-back. |

---

## 9. The strategic choices organizations must make

The capability gap is not simply a training problem or a technical governance problem. It is the result of choices about how work is organized and what the organization chooses to develop.

Leadership teams should make several decisions explicitly:

### 9.1 What is the organization trying to optimize?

Is the priority lower cost, more capacity, better quality, faster service, greater innovation, resilience, or some combination? These objectives can conflict. A model that maximizes throughput may weaken learning or customer experience. A model that maximizes review may reduce speed without meaningfully reducing risk.

The organization should state its objectives and identify which outcomes cannot be traded away.

### 9.2 Which human capabilities are strategic assets?

Some skills can be purchased externally or accessed through AI services. Others are deeply embedded in organizational knowledge, customer relationships, regulatory experience, operational context, or proprietary systems.

Leaders should identify which capabilities are essential to differentiate the business, maintain safety, preserve resilience, and make effective decisions. These may include specialized technical skills, but also customer understanding, systems knowledge, negotiation, diagnosis, and the ability to manage unusual conditions.

### 9.3 Which learning experiences must be preserved?

If a task is being automated, leadership should ask whether it also serves as an apprenticeship step. If it does, the organization should decide how that learning will be recreated. This may involve AI coaching, simulation, rotations, case review, supervised responsibility, or new role design.

The choice should be deliberate rather than left to chance.

### 9.4 How much authority should AI receive?

Autonomy should be granted based on demonstrated capability, consequence, reversibility, and the quality of controls—not because a vendor describes a system as agentic or because the organization wants to move quickly.

The organization should determine which actions can be delegated, which require human authorization, which are prohibited, and what evidence is required before authority is expanded.

### 9.5 How will employees participate in the transition?

Employees are not merely recipients of automation. They are sources of operational knowledge, users of the new systems, and people whose capability and work conditions are affected. Their participation can reveal failure modes that are invisible in an executive process map.

Organizations should provide mechanisms for employees to identify issues, challenge designs, suggest improvements, and request review of AI-enabled decisions affecting their work.

### 9.6 How will productivity gains be reinvested?

Leaders should decide whether productivity gains will support growth, quality, employee development, reduced workload, new services, or cost reduction. A balanced strategy may use the gains for several purposes.

A business that treats human capability as a disposable cost may undermine the expertise and adaptability required to operate its AI systems over time.

---

## 10. Conclusion: build organizations that can think, act, and adapt with AI

The agentic era does not simply transfer work from people to machines. It changes the relationship between execution, experience, judgment, decision authority, and organizational learning.

AI can lower the cost of producing code, analysis, content, recommendations, and operational actions. It can help less experienced workers perform at a higher level, make specialist knowledge more accessible, and create opportunities for new services. But AI capabilities remain uneven, and human-AI collaboration is not automatically superior to either human or machine performance alone. The effects depend on task design, capability, organizational context, and how people interact with the system.

The most significant risk is not that humans will have less work to do. It is that organizations may remove the experiences through which people develop the knowledge they will still need—while assigning them responsibility for monitoring systems they cannot adequately understand, challenge, or control.

That is the human capability paradox. It should not be treated as a prediction of inevitable deskilling. It is a design challenge. Organizations can create the opposite outcome by using AI to expand access to expertise, accelerate learning, make practice more varied, strengthen organizational memory, and free people to focus on work where human judgment and relationships matter.

Doing so requires a broader strategy than adding training or inserting human approvals. It means redesigning workflows, defining decision rights, building observable and interruptible systems, creating alternative pathways into expertise, developing human-AI teams with clear role boundaries, aligning incentives, involving employees, and measuring human capability alongside productivity.

The objective is not to keep people busy performing work machines can perform. Nor is it to leave people at the end of an automated process to validate results after the meaningful decisions have already been made.

It is to create organizations in which people understand the work well enough to shape it, AI systems are given authority that is earned and bounded, and human capability continues to grow as technology advances.

The strategic question for leadership is therefore not simply **how much work can AI perform?** It is:

> **What must our people be able to understand, decide, create, challenge, and take responsibility for—and how will we deliberately build those capabilities as AI takes on more of the work?**

---

## References

1. Noy, S., & Zhang, W. (2023). “Experimental evidence on the productivity effects of generative artificial intelligence.” *Science*, 381(6654), 187–192. https://doi.org/10.1126/science.adh2586
2. Brynjolfsson, E., Li, D., & Raymond, L. R. (2025). “Generative AI at Work.” *The Quarterly Journal of Economics*, 140(2), 889–942. https://doi.org/10.1093/qje/qjae044
3. Cui, Z., Demirer, M., Jaffe, S., Musolff, L., Peng, S., & Salz, T. (2026). “The Effects of Generative AI on High-Skilled Work: Evidence from Three Field Experiments with Software Developers.” *Management Science*. https://doi.org/10.1287/mnsc.2025.00535
4. Dell’Acqua, F., McFowland, E., Mollick, E., Lifshitz-Assaf, H., Kellogg, K. C., Rajendran, S., Krayer, L., Candelon, F., & Lakhani, K. R. (2026). “Navigating the Jagged Technological Frontier: Field Experimental Evidence of the Effects of Artificial Intelligence on Knowledge Worker Productivity and Quality.” *Organization Science*, 37(2), 403–423. https://doi.org/10.1287/orsc.2025.21838
5. Gmyrek, P., Berg, J., & Bescond, D. (2025). “Generative AI and Jobs: A Refined Global Index of Occupational Exposure.” International Labour Organization, Working Paper 140. https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure
6. Acemoglu, D., & Restrepo, P. (2019). “Automation and New Tasks: How Technology Displaces and Reinstates Labor.” *Journal of Economic Perspectives*, 33(2), 3–30. https://doi.org/10.1257/jep.33.2.3
7. Autor, D. H. (2014). “Polanyi’s Paradox and the Shape of Employment Growth.” NBER Working Paper 20485. https://www.nber.org/papers/w20485
8. Vaccaro, M., Almaatouq, A., & Malone, T. (2024). “When combinations of humans and AI are useful: A systematic review and meta-analysis.” *Nature Human Behaviour*, 8, 2293–2303. https://doi.org/10.1038/s41562-024-02024-1
9. Agrawal, A., Gans, J., & Goldfarb, A. (2022). *Power and Prediction: The Disruptive Economics of Artificial Intelligence*. Harvard Business Review Press. https://store.hbr.org/product/power-and-prediction-the-disruptive-economics-of-artificial-intelligence/10580
10. Sweller, J., van Merriënboer, J. J. G., & Paas, F. (2019). “Cognitive Architecture and Instructional Design: 20 Years Later.” *Educational Psychology Review*, 31, 261–292. https://doi.org/10.1007/s10648-019-09465-5
11. Cowan, N. (2001). “The magical number 4 in short-term memory: A reconsideration of mental storage capacity.” *Behavioral and Brain Sciences*, 24(1), 87–114. https://doi.org/10.1017/S0140525X01003922
12. Lee, H.-P., Sarkar, A., Tankelevitch, L., Drosos, I., Rintel, S., Banks, R., & Wilson, N. (2025). “The Impact of Generative AI on Critical Thinking: Self-Reported Reductions in Cognitive Effort and Confidence Effects From a Survey of Knowledge Workers.” *Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems*. https://doi.org/10.1145/3706598.3713778
13. Goddard, K., Roudsari, A., & Wyatt, J. C. (2012). “Automation bias: a systematic review of frequency, effect mediators, and mitigators.” *Journal of the American Medical Informatics Association*, 19(1), 121–127. https://doi.org/10.1136/amiajnl-2011-000089
14. Parasuraman, R., & Manzey, D. H. (2010). “Complacency and bias in human use of automation: an attentional integration.” *Human Factors*, 52(3), 381–410. https://doi.org/10.1177/0018720810376055
15. Endsley, M. R. (1995). “Toward a Theory of Situation Awareness in Dynamic Systems.” *Human Factors*, 37(1), 32–64. https://doi.org/10.1518/001872095779049543
16. Endsley, M. R., & Kiris, E. O. (1995). “The Out-of-the-Loop Performance Problem and Level of Control in Automation.” *Human Factors*, 37(2), 381–394. https://doi.org/10.1518/001872095779064555
17. Bainbridge, L. (1983). “Ironies of Automation.” *Automatica*, 19(6), 775–779. https://doi.org/10.1016/0005-1098(83)90046-8
18. Parasuraman, R., Sheridan, T. B., & Wickens, C. D. (2000). “A model for types and levels of human interaction with automation.” *IEEE Transactions on Systems, Man, and Cybernetics—Part A: Systems and Humans*, 30(3), 286–297. https://doi.org/10.1109/3468.844354
19. Parker, S. K., & Knight, C. (2024). “The SMART model of work design: A higher order structure to help see the wood from the trees.” *Human Resource Management*, 63(2), 265–291. https://doi.org/10.1002/hrm.22200
20. OECD (2023). “Artificial intelligence, job quality and inclusiveness.” *OECD Employment Outlook 2023*. https://www.oecd.org/en/publications/2023/07/oecd-employment-outlook-2023_904bcef3/full-report/artificial-intelligence-job-quality-and-inclusiveness_a713d0ad.html
21. OECD (2025). “How widespread is algorithmic management in workplaces?” OECD Publishing. https://doi.org/10.1787/cda7a114-en
22. Autio, C., Schwartz, R., Dunietz, J., Jain, S., Stanley, M., Tabassi, E., Hall, P., & Roberts, K. (2024). *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile*. NIST AI 600-1. https://doi.org/10.6028/NIST.AI.600-1
23. International Organization for Standardization. (2023). *ISO/IEC 42001:2023 — Information technology—Artificial intelligence—Management system*. https://www.iso.org/standard/42001
24. European Parliament and Council. (2024). *Regulation (EU) 2024/1689 (Artificial Intelligence Act)*, Article 14: Human oversight. https://eur-lex.europa.eu/eli/reg/2024/1689
25. Ochmann, J., Michels, L., Tiefenbeck, V., Maier, C., & Laumer, S. (2024). “Perceived algorithmic fairness: An empirical study of transparency and anthropomorphism in algorithmic recruiting.” *Information Systems Journal*, 34(2), 384–414. https://doi.org/10.1111/isj.12482
26. United States District Court, Southern District of New York. (2023). *Mata v. Avianca, Inc.*, Opinion and Order on Sanctions, No. 22-cv-1461 (PKC), June 22, 2023. https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1%3A2022cv01461/575368/54/
27. Brynjolfsson, E., Rock, D., & Syverson, C. (2021). “The Productivity J-Curve: How Intangibles Complement General Purpose Technologies.” *American Economic Journal: Macroeconomics*, 13(1), 333–372. https://doi.org/10.1257/mac.20180386
