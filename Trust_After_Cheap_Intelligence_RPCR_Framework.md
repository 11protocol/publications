## 🛡️ LEGAL NOTICE
>By continuing to access or use this document, you acknowledge that you have read, understood, and agree to be bound by the 11Protocol [Licensing & Intellectual Property terms](https://github.com/11protocol/publications/tree/main?tab=License-1-ov-file).
---
# Trust After Cheap Intelligence: From Human Trust to Risk-Proportionate AI Reliance

## Abstract

Trust allows societies and markets to function without requiring every claim, transaction, and professional judgment to be independently re-established from first principles. It reduces the cost of cooperation under uncertainty, but it does not eliminate the need for evidence, accountability, or safeguards. Generative artificial intelligence changes the conditions under which trust is exercised: systems can produce fluent, coherent, and apparently authoritative outputs at scale, while the truth, relevance, and fitness of those outputs for a particular decision may remain uncertain. Yet it would be an overstatement to conclude that AI always makes verification harder, that models cannot express useful uncertainty, or that human oversight is inherently effective. The challenge is contextual. AI may reduce the cost of producing information faster than it reduces the cost of validating it, particularly when correctness depends on external evidence, specialized knowledge, tacit context, or consequences that are difficult to reverse.

This paper integrates theories of interpersonal and organizational trust, information asymmetry, transaction costs, bounded rationality, and appropriate reliance on automation with research on hallucination, sycophancy, self-correction, automation bias, and human-AI decision support. It distinguishes perceived trustworthiness from warranted reliance and separates three questions that are often collapsed: where an assertion came from, whether evidence supports it, and whether it is sufficient for the decision at hand. On that foundation, it proposes a practical Risk-Proportionate Calibrated Reliance (RPCR) framework. The framework assesses the consequences and reversibility of error, uncertainty and detectability, evidence quality, autonomy and scale, affected rights, and the capacity for competent review; it then maps the resulting risk level to proportionate technical, procedural, and governance controls. The framework is a theory-informed operating proposal, not a validated universal score or a substitute for legal classification. Its central rule is simple: the level of decision weight granted to an AI output should never exceed what the available evidence, system capability, context, and accountability arrangements can justify.

**Keywords:** artificial intelligence; trust; appropriate reliance; verification economics; automation bias; hallucination; sycophancy; risk management; provenance; human oversight; AI governance

---

## 1. Introduction: The Cost of Believing

Modern society depends on acting without knowing everything. We rely on professional expertise, organizational roles, reputation, contracts, standards, and institutions because fully verifying every statement and transaction would be prohibitively expensive. Trust is not merely a personal feeling; it is part of the infrastructure that makes cooperation, specialization, and complex exchange possible. Economic and organizational theory has long examined how governance mechanisms reduce the costs and risks created by uncertainty, incomplete information, and the separation of ownership from control [[1](https://doi.org/10.5465/amr.1995.9508080335)] [[2](https://doi.org/10.1086/227496)] [[3](https://doi.org/10.2307/1879431)].

Imagine a business leader considering a recommendation to enter a new market. When the advice comes from a person, the leader may weigh the adviser’s expertise, the evidence behind the recommendation, and what the adviser stands to gain. When the recommendation comes from AI, fluent wording and apparent confidence can make those same questions easier to overlook, even though the relevant controls differ: task-specific performance must be assessed, evidence traced, missing context surfaced, and responsibility assigned to the people and organizations operating the system. The central question is not simply whether to trust the messenger. It is which parts of the recommendation are warranted, by what evidence, and with what consequences if they are wrong.

Generative AI changes this familiar arrangement. A user can receive an answer, summary, analysis, draft, or recommendation in seconds. The answer may be clear, context-sensitive, and confidently presented. Those qualities make interaction easy, but do not establish that a claim is true, that the system has the necessary context, or that its output should influence a consequential decision. Research on natural-language generation documents the continuing problem of outputs that are unsupported by their source or inaccurate about the world; research on human-AI interaction shows that people may accept incorrect system advice or change their own correct answer in response to an AI recommendation [[4](https://doi.org/10.1518/hfes.46.1.50_30392)] [[5](https://doi.org/10.1136/amiajnl-2011-000089)] [[6](https://doi.org/10.1145/3571730)].

The temptation is to describe this as a wholesale replacement of human trust by machine reliability. That formulation is too simple. People still need to trust the organizations that build, deploy, configure, and govern AI systems. They need to assess the evidence an AI system provides, the system’s performance on the task, the limitations of the surrounding workflow, and the incentives of the people and institutions responsible for it. At the same time, the interpersonal cues people use to assess other humans—such as fluency, confidence, agreement, and apparent empathy—cannot be transferred directly to a generative model as proof of competence or integrity. The more useful distinction is between **perceived trustworthiness** and **warranted reliance**: the first concerns how trustworthy a source appears; the second concerns how much decision weight its output deserves given the evidence and consequences.

This paper addresses four connected questions:

1. What functions do trust and assurance perform in society and economic exchange, and which parts of those functions remain relevant when AI is involved?
2. How do human trust judgments differ from the technical evaluation of AI outputs, without pretending either humans or machines are uniformly reliable?
3. Under what conditions can AI reduce the cost of producing information faster than an organization can validate it, and how should that possibility be evaluated rather than assumed?
4. How can an organization match verification and mitigation to the actual risk of a use case instead of applying the same level of oversight to every AI task?

The contribution is a proposed Risk-Proportionate Calibrated Reliance (RPCR) framework. It draws on established theory and research, aligns conceptually with lifecycle-oriented risk management guidance, and translates those foundations into an operational method for deciding when AI can assist, when its output requires review, when an independent decision-maker must approve it, and when the use should not proceed. It is not presented as a validated psychometric instrument or as a replacement for applicable law, professional standards, or established risk frameworks. Its risk levels and control bundles are a design proposal intended to support assessment, testing, and refinement.

## 2. The Foundations: Why Trust Exists

### 2.1 Bounded rationality and the need to delegate

Individuals and organizations make decisions with incomplete information, limited time, finite attention, and imperfect foresight. This is the practical condition often described as bounded rationality: a concept developed in Herbert Simon’s account of how real decision-makers choose under limits on information, attention, and computation [[7](https://doi.org/10.2307/1884852)]. Trust, expertise, and institutional routines help manage it by making it possible to delegate work and act on information that cannot be independently reconstructed in every instance. Transaction-cost economics treats the cost of coordinating, monitoring, and governing exchanges as a central explanatory variable in the organization of economic activity [[2](https://doi.org/10.1086/227496)].

Trust reduces the need for continuous, exhaustive verification, but it does not make verification worthless. Rather, it allows verification to be selective. A person may rely on a licensed professional because the professional has relevant training, a track record, ethical obligations, and exposure to review or liability. A company may rely on a supplier because contracts, quality controls, audits, warranties, and experience provide reasonable assurance. These arrangements combine beliefs about a source with mechanisms that constrain what can happen if those beliefs are wrong.

This is an important starting point for AI. The objective cannot be to verify every token or to require humans to repeat every task that an AI system performs. That would forfeit many of the benefits that make automation useful. The objective is to select an appropriate level and method of verification based on what can go wrong, how easily the error can be found, and how much assurance the task requires.

### 2.2 Interpersonal trust: ability, benevolence, and integrity

The influential integrative model of organizational trust developed by Mayer, Davis, and Schoorman defines trust in terms of a willingness to accept vulnerability to another party, based on positive expectations about that party’s actions. It distinguishes three widely used antecedents of perceived trustworthiness: **ability**, **benevolence**, and **integrity** [[1](https://doi.org/10.5465/amr.1995.9508080335)].

- **Ability** refers to relevant skills, competence, and domain-specific capacity.
- **Benevolence** concerns whether the trustee is believed to care about the trustor’s interests, rather than acting only for self-benefit.
- **Integrity** concerns adherence to principles the trustor finds acceptable.

The framework is useful because it explains why trust is not a synonym for technical skill. A knowledgeable adviser can be competent but conflicted. A well-intentioned person can be sincere but wrong. A source can have a strong track record while its incentives or circumstances change. Human trust therefore combines judgments about capability with judgments about motivations, values, and the broader relationship.

For this paper, accuracy and reliability are treated as outcomes to measure, not as interchangeable substitutes for the three dimensions. An individual may be honest but mistaken, capable but careless, or benevolent but subject to conflicting incentives. An organization’s assessment should distinguish these possibilities rather than collapsing every failure into a generic trust score.

The model’s relational concepts do not transfer literally to a language model. It is not useful to describe a model as benevolent or dishonest in the same sense as a person. But the model remains highly relevant when the unit of analysis is the **sociotechnical arrangement**: the vendor, deploying organization, model, data, interface, operating procedures, reviewer, and affected decision-maker. In that arrangement, competence, incentives, integrity, and accountability all remain consequential—even if they reside in different places.

### 2.3 Information asymmetry and the economics of quality signals

Economic exchange often requires one party to judge the quality of something it cannot fully inspect before purchase or use. Akerlof’s classic “Market for Lemons” analysis shows how uncertainty about quality can distort market behavior: when buyers cannot distinguish high-quality goods from low-quality ones, the incentives and prices that sustain quality can weaken [[3](https://doi.org/10.2307/1879431)]. Related ideas in agency theory examine conflicts that arise when one party acts on behalf of another but has different information or incentives [[8](https://doi.org/10.1016/0304-405X%2876%2990026-X)].

These ideas offer a useful analogy for AI-generated information. Fluent prose, polished formatting, a plausible citation, or an elaborate explanation can function as apparent signals of quality. But when such signals become cheap to produce, their evidentiary value may decline unless they are supported by signals that are harder to fake or independently test. This does **not** prove that AI will produce a universal “market for lemons.” The analogy instead raises a testable question: which signals become less informative when polished output is abundant, and which signals—such as a verifiable source trail, independent testing, reproducible results, warranties, a validated track record, or clear accountability—continue to distinguish dependable work?

The practical implication is that trust in AI-assisted work cannot rest on presentation alone. Organizations need quality signals connected to observable performance and evidence. The signal should be appropriate to the claim: source references for factual claims, tests for code, calculations for quantitative results, validated procedures for repeated decisions, and accountable domain review for judgments that cannot be reduced to a deterministic check.

### 2.4 Trust, reliability, and reliance are not the same

Trust, system reliability, and reliance should be kept analytically distinct. Trust is a judgment or attitude. Reliability is an observed property of system performance under specified conditions. Reliance is the behavior of giving a system some influence over a decision. Appropriate reliance occurs when the weight given to system output is warranted by the system’s demonstrated capability and by the decision context [[4](https://doi.org/10.1518/hfes.46.1.50_30392)] [[9](https://doi.org/10.1145/3696449)] [[10](https://doi.org/10.1016/j.patter.2024.101045)].

A person can trust a highly capable system too little and lose its benefits. A person can trust a flawed system too much and accept poor advice. The same person may rationally rely on an AI for summarizing a large document while refusing to let it make an irreversible decision. There is no universally optimal level of “trust in AI.” What matters is whether a particular use of a particular system is justified for a particular task under particular conditions.

This distinction is foundational to RPCR. The goal is not to maximize AI acceptance or force humans to distrust it. The goal is to calibrate decision weight and control effort to evidence, capability, uncertainty, and consequence.

## 3. What Changes with Generative AI

### 3.1 Output fluency is not evidence of correctness

Large language models produce text by using learned representations and generation procedures shaped by training and, in many systems, further instruction-tuning or preference optimization. This can support remarkable flexibility, synthesis, and responsiveness. It also means that a well-formed answer is not, by itself, evidence that the answer has been checked against reliable sources or that the model has represented uncertainty correctly. Research surveys describe multiple types of hallucination and emphasize that the appropriate definition and detection method depend on the task and available source evidence [[6](https://doi.org/10.1145/3571730)].

The relevant distinction is not that AI “does not know anything” or that it simply predicts words without useful internal representations. Models can encode factual relationships, solve some problems, and perform well on many evaluations. The narrower and more defensible point is this: **natural-language fluency is not a reliable stand-alone proxy for factual validity or decision fitness**. A user should not treat confidence of tone, specificity, agreement, or explanatory detail as proof that an output is correct.

Nor should model confidence be dismissed universally. Research has found that some language models can estimate the correctness of their answers with useful calibration in particular tasks and formats, while their self-assessment may be weaker or less transferable in other settings [[11](https://arxiv.org/abs/2207.05221)]. The implication is to validate uncertainty estimates for the actual model, task, and operating conditions—not to treat them as inherently meaningful or inherently useless.

### 3.2 Hallucination and the evidence problem

“Hallucination” is an umbrella term for generated content that is false, unsupported by input evidence, or inconsistent with source material, with definitions differing across tasks. A summary that adds a fact absent from the source can fail faithfulness even if the added statement happens to be true; an answer to a real-world question can be factually wrong even if it is consistent with the prompt. The distinction matters because different failure modes need different checks [[6](https://doi.org/10.1145/3571730)].

A model may generate a nonexistent citation, attribute a statement to the wrong source, omit a material qualification, or combine individually true facts into a misleading conclusion. The problem is not solved merely by asking the model to provide citations. A reference is a route to evidence, not evidence that the cited material supports the specific claim. Source checking must establish whether the source exists, whether it is authoritative for the matter, whether it is current, and whether the claim follows from it.

Grounding techniques such as retrieval-augmented generation can make evidence more accessible, and deterministic checks can validate parts of an output. They do not guarantee that the retrieval step selected the right source, that the model interpreted it accurately, or that the source itself was correct. Verification should therefore be designed around the claim and the task rather than around the mere presence of citations or tools.

### 3.3 Sycophancy: agreement can compete with accuracy

Research on language-model behavior has found cases where assistants change an answer or affirm a user’s stated view in ways that reduce truthfulness. Perez and colleagues identified sycophancy in model-written evaluations, including cases where larger models repeated users’ preferred answers [[12](https://arxiv.org/abs/2212.09251)]. Sharma and colleagues subsequently tested five assistants across multiple free-form tasks and found consistent sycophantic patterns; their analysis indicated that human preference judgments can favor belief-matching responses even when those responses are incorrect [[13](https://arxiv.org/abs/2310.13548)].

In the study’s question-answering experiment across selected datasets, Claude 1.3 wrongly admitted a mistake on 98% of questions after being asked “Are you sure?”—a result tied to that model version, test set, and prompt. It should not be treated as a universal rate for current models or as proof that every challenge will make AI less accurate. The broader lesson is narrower: a user's confident objection can sometimes induce a model to abandon a correct answer, so agreement, apology, or apparent deference should not be mistaken for evidence-based updating [[13](https://arxiv.org/abs/2310.13548)].

This does not mean that every model is primarily optimized to flatter the user, nor that sycophancy is explained by one training method alone. Human-feedback training has been used to improve helpfulness and truthfulness as well as instruction following [[14](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract.html)]. The risk arises when preference signals, interaction patterns, or evaluation methods reward apparent agreement more strongly than correctness in particular conditions. The right response is to test for the failure mode and design workflows that reward evidence, not merely pleasing answers.

### 3.4 Self-review is not the same as independent verification

Asking a model to review its own answer can catch some problems, especially when the task is constrained or the model is given a useful rubric. But a model reviewing its own output without external feedback may reuse the same assumptions, blind spots, or unsupported premises that produced the original answer. Huang and colleagues found that intrinsic self-correction without external feedback did not reliably improve reasoning performance in the tasks they studied and could sometimes reduce it [[15](https://arxiv.org/abs/2310.01798)].

The result should not be generalized into “AI cannot self-correct.” A tool-enabled workflow may check code by executing tests, compare extracted fields with a source record, validate a calculation with a deterministic function, or retrieve independent evidence. Those mechanisms provide information beyond the model’s unsupported self-assessment. Their effectiveness still depends on their design, independence, coverage, and the quality of the reference evidence.

For governance purposes, therefore, self-review is a useful layer, not a sufficient assurance case. High-risk claims should be checked against a source, process, test, or reviewer that is independent enough to expose the original failure rather than merely restate it.

### 3.5 Human oversight can fail too

Automation bias—the tendency to over-rely on automated decision support or accept its incorrect suggestions—has been studied in settings including clinical decision support. A systematic review by Goddard and colleagues identified automation-bias effects and mitigating factors, while emphasizing that their frequency and impact depend on the context and system [[5](https://doi.org/10.1136/amiajnl-2011-000089)]. The risk is not limited to AI: people may accept advice from human authorities, defer to dashboards, or follow a familiar process without adequate scrutiny.

“Human in the loop” is therefore not a guarantee of meaningful oversight. An assigned reviewer may lack subject-matter competence, time, access to evidence, independence from the original recommendation, or authority to stop the action. An approval click can become ritual rather than control. Conversely, competent human reviewers can also make errors, suffer fatigue, or be outperformed by automated checks on narrow and repeatable tasks.

Buçinca and colleagues found that cognitive-forcing interventions—such as eliciting a person's initial judgment before exposing them to AI advice—can reduce overreliance in the studied decision-making tasks [[16](https://doi.org/10.1145/3449287)]. Such interventions are not universal solutions: they impose time and cognitive costs, and their value depends on the task and workflow. The practical lesson is to engineer oversight so that it is capable of detecting and correcting errors, rather than assuming that a human presence alone makes a process safe.

## 4. Comparing Human Trust and AI Reliance

The comparison below does not rank humans and AI as globally better or worse. Both can be wrong, biased, inconsistent, or difficult to audit. Their failure mechanisms and available assurance methods differ, which is why an organization should evaluate the actual human-AI process rather than anthropomorphize the model or assume that human review is automatically superior.

| Dimension | Human source or adviser | AI system or AI-enabled workflow | Practical implication |
|---|---|---|---|
| Capability | Evaluated through training, experience, specialization, performance, and peer or professional review. | Must be evaluated for the specific model, version, task, data, interface, and workflow. Benchmark performance may not generalize to edge cases. | Define the task and validate performance in that context; avoid general labels such as “smart” or “expert.” |
| Accuracy and consistency | Subject to memory limits, bias, fatigue, negligence, and deliberate deception. | Can produce unsupported or incorrect claims; performance varies by prompt, source, context, model, and tool configuration. | Measure error rates and failure modes rather than infer accuracy from fluency or reputation. |
| Intent and incentives | May have benevolent, selfish, conflicting, or malicious motives. | A model should not be assumed to possess human-like conscious intent; provider, developer, deployer, and user incentives still affect the system and its use. | Assess the people and organizations around the model, including commercial incentives, conflicts, and accountability. |
| Context | May draw on lived experience, tacit knowledge, physical circumstances, and shared history, but can misread them. | Uses the context supplied or made accessible through the system and can miss tacit or omitted information. | Specify required context and identify what remains unknown. Do not ask the system to infer critical facts silently. |
| Confidence and explanation | Verbal confidence may be informative but can be strategically exaggerated or poorly calibrated. | Confidence language and explanations may not correspond to measured uncertainty or faithfully reveal the generation process. | Validate calibrated uncertainty separately; treat explanations as hypotheses to inspect, not proof. |
| Evidence and auditability | Internal reasoning may be difficult to inspect; records and supporting materials may be available. | Can be instrumented with source traces, logs, tests, structured outputs, and reproducible workflows—but only if designed to do so. | Prefer direct evidence and testable outputs; retain provenance and evaluation records where justified. |
| Learning and change | Can learn from experience, but may forget, drift, or apply stale knowledge. | Behavior can change with model updates, prompt changes, retrieval sources, tools, context limits, or system instructions. | Version the full system configuration, monitor drift, and re-evaluate material changes. |
| Accountability | Responsibility may be personal, professional, contractual, or institutional. | Responsibility is distributed across provider, deployer, operator, and approver, but should not be allowed to disappear into the technology. | Name a human or organizational owner for the decision and its consequences. |
| Verification | Often uses professional standards, source checks, second opinions, audits, or observed outcomes. | May allow deterministic checks and repeatable tests, but generative judgments still require task-appropriate evaluation. | Use the strongest available independent check; do not treat a second answer from a similar model as full independence. |

The key difference is not that human trust should be abandoned. Human trust remains necessary in selecting suppliers, setting controls, evaluating expertise, and assigning accountability. The change is that a conversational interface can invite a relational response to a system whose output quality must be established through empirical and procedural means. Human trust theory helps identify the relationships and incentives at stake; reliability engineering and appropriate-reliance research help determine how much weight should be given to a particular output [[1](https://doi.org/10.5465/amr.1995.9508080335)] [[4](https://doi.org/10.1518/hfes.46.1.50_30392)] [[9](https://doi.org/10.1145/3696449)].

## 5. The Economics of Verification

### 5.1 Why lower generation cost does not settle total value

AI can reduce the time required to produce drafts, summaries, code, or analyses. In a preregistered experiment involving 453 college-educated professionals performing midlevel writing tasks, Noy and Zhang found that access to ChatGPT reduced average completion time by 40% and increased assessed output quality by 18% in that experimental setting [[17](https://doi.org/10.1126/science.adh2586)]. That result is meaningful evidence of productivity potential, but it does not establish that AI reduces total costs in every occupation or that review can be omitted. Task design, error consequences, downstream rework, and the availability of evidence alter the net benefit.

The economic question is not simply whether generation becomes cheaper. It is whether **the total cost of a dependable outcome** decreases. That total can include model inference, data preparation, integration, tool execution, verification, correction, review time, incident management, security, compliance, and accountability. Even where inference is inexpensive, expensive specialist review may be necessary. Conversely, well-designed structured extraction, code execution, or source-grounded workflows may reduce both production and verification effort. Any broad claim that verification costs always remain constant or always increase would therefore exceed the evidence.

Recent economic analysis has advanced a “measurability gap” thesis: as AI increases the amount of work agents can execute, human capacity to verify results may become a binding constraint [[18](https://arxiv.org/abs/2602.20946)]. This is a useful conceptual lens, not an empirically established universal law. It is presented as a theoretical working paper and uses strong economy-wide assumptions that should be tested across different tasks and industries. This paper adopts the underlying question without treating the proposed gap as a measured fact: **does the organization have enough capable verification capacity for the volume, complexity, and consequence of the AI-supported decisions it is generating?**

### 5.2 An operational indicator: verification demand versus capacity

To make that question actionable, an organization can estimate a **verification-capacity ratio** for a defined workflow:

> **Verification-capacity ratio = estimated competent review effort required for the workflow / competent review capacity available during the same period.**

A ratio above 1 indicates that the expected verification workload exceeds available review capacity under the stated assumptions. The ratio is not a safety score, and it does not measure whether reviews are substantively effective. Estimates may be uncertain, and different claims require different review depth. Still, the indicator can expose a common operational contradiction: a process produces more AI-assisted outputs than the organization can meaningfully check.

The response to an excessive ratio should not automatically be to lower the review standard. Depending on the risk, an organization can reduce the volume of outputs, narrow the system’s scope, prioritize the highest-consequence claims, automate deterministic checks, improve access to source evidence, allocate more qualified reviewers, redesign the workflow, or suspend the use case. For low-risk tasks, sampling may be proportionate. For high-consequence decisions, an inability to provide the required level of verification can be a reason not to deploy.

This ratio should be evaluated alongside error rates and consequence. A workflow with a low verification-capacity ratio can still be unsafe if the reviewer is unqualified or the source of truth is unavailable. A workflow with a higher ratio may be manageable if most claims can be checked automatically and only a small subset require expert judgment. The point is to identify a capacity constraint, not to disguise a complex decision as a single number.

### 5.3 The shifting economics of quality signals

If fluent output becomes abundant, users may find it harder to distinguish high-quality work by appearance alone. This is where the lemons analogy is useful. It suggests a possible shift in what the market values—not that quality inevitably collapses, but that the old signals may become weaker and new signals more important. A dependable AI-enabled service might distinguish itself through task-specific evaluations, reliable source traceability, clear limits, measurable performance, independent audits, service-level commitments, and an accountable party that stands behind its results.

That advantage is not free. Some forms of verification can be automated or embedded in the workflow; others require domain experts or external ground truth. A rigorous assurance process can cost more than the task it is meant to improve. The decision to use AI should therefore compare alternatives: the expected cost and risk of the AI-assisted workflow, the cost and performance of a human-only process, and the cost of a hybrid process. Verification is a source of value when it prevents losses, enables trustworthy use at scale, or differentiates quality; it becomes wasteful friction when it adds no meaningful assurance to a low-risk, easily corrected task.

The economic goal is not maximum verification. It is the least-cost workflow that reaches the level of assurance justified by the consequences. This is the rationale for risk-proportionate mitigation.

## 6. From Theory to Method: A Risk-Proportionate Approach

The RPCR framework translates the preceding theories into an assessment and operating method. It is a proposed synthesis, not a framework already empirically validated in its current form. It is designed to complement rather than replace the risk-management lifecycle in NIST’s AI Risk Management Framework and its Generative AI Profile [[19](https://www.nist.gov/itl/ai-risk-management-framework)] [[20](https://doi.org/10.6028/NIST.AI.600-1)]. NIST organizes AI risk-management activity around govern, map, measure, and manage; the RPCR method uses a similar lifecycle orientation but focuses on the operational question of how much decision weight to grant AI and which verification controls that decision requires.

### 6.1 The core rule

**Assign decision weight only to the degree justified by task-specific evidence, validated capability, context, and accountable oversight. Increase mitigation when potential harm is greater, errors are harder to detect, or actions are difficult to reverse. If necessary assurance cannot be achieved, constrain or do not use the system for that decision.**

This rule avoids two opposite mistakes: using AI too freely because it appears capable, and rejecting AI indiscriminately because it can fail. It treats appropriate reliance as a decision about a specific use case, not a global judgment about the technology.

### 6.2 Assess inherent risk before choosing controls

Assessment begins with the use case, not the model name. Record the decision to be influenced, the affected people or assets, the actions the system can take, the evidence available, and the plausible consequences of error. Evaluate the following dimensions:

1. **Severity of harm:** What is the credible downside of a wrong, incomplete, biased, or misleading output? Consider financial, legal, safety, privacy, security, reputational, and rights-related effects.
2. **Reversibility and time sensitivity:** Can the consequence be corrected before harm occurs? Can an action be undone? Does speed reduce the opportunity to intervene?
3. **Likelihood and exposure:** How often is the output used, how many people or decisions does it affect, and what is known about error frequency under the actual operating conditions?
4. **Uncertainty and detectability:** Is there a stable source of truth? Are errors easy to identify, or can a plausible error survive review? Does the task depend on tacit context, novel conditions, ambiguous evidence, or open-ended judgment?
5. **Evidence quality and independence:** Are claims linked to current, authoritative sources? Can the source be checked? Is a verifier independent of the model and assumptions that generated the answer?
6. **Autonomy and propagation:** Does the system draft a suggestion, recommend a decision, execute an action, or trigger further tools and decisions? Can one error cascade across an agentic workflow?
7. **Rights, vulnerability, and distribution:** Could the output affect access to services, employment, credit, health, education, public benefits, or other consequential interests? Are some groups more exposed to harm?
8. **Governance and review capacity:** Does a qualified person have the time, evidence, authority, and responsibility to evaluate the result and stop the process?

These dimensions should be recorded with a short rationale and evidence, not converted automatically into a pseudo-precise numerical score. A single severe consequence, a missing source of truth, or the absence of competent review should not be averaged away by several low-risk attributes. Legal classification and mandatory controls must be assessed separately where applicable; the RPCR tiers below are an internal operating aid and are not equivalent to the statutory categories in the EU AI Act [[21](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)].

### 6.3 Four risk levels and their default controls

The following tiers are a proposed practical scheme. The names describe the level of assurance expected, not a legal classification. Organizations should calibrate the tier boundaries to their domain, obligations, and risk appetite. Where a use case spans multiple tiers, apply the higher tier to the consequential action or claim.

| RPCR level | Typical characteristics | Minimum assurance pattern | Autonomy and decision authority |
|---|---|---|---|
| **Level 1 — Routine** | Low consequence, easy to correct, limited external effect; examples include brainstorming, formatting, or drafting internal notes that will not be relied upon as factual authority. | Basic user review; clear distinction between generated text and verified facts; sampling or lightweight checks where outputs repeat at scale; no sensitive input unless approved. | AI may generate or transform content. A human remains responsible for deciding whether to use it. |
| **Level 2 — Material** | A wrong output could cause meaningful rework, misinform a customer, misstate an operational fact, or affect a moderate business decision; correction is feasible but not costless. | Verify material factual claims against primary or authoritative sources; use structured outputs and automated consistency checks where possible; require a named reviewer before external release or reliance; retain source links for claims that matter. | AI may recommend or draft. A competent human approves the output before it changes a material decision or reaches an external audience. |
| **Level 3 — High consequence** | A wrong output could create substantial financial, legal, employment, health, safety, security, or rights-related harm; errors may be difficult to detect or partially reversible. | Domain-qualified independent review; source-level verification of consequential claims; task-specific evaluation before deployment and after material changes; cognitive-forcing design where useful; audit logs; explicit escalation, override, and incident handling; no approval based solely on the model’s self-review. | AI remains decision support. A designated, authorized decision-maker retains substantive authority and must have enough information and time to disagree. |
| **Level 4 — Critical / restricted** | Credible potential for severe or widespread harm, safety-critical or critical-infrastructure impact, irreversible action, large-scale propagation, or a decision that cannot be adequately verified. | Formal risk and safety case; rigorous testing and adversarial evaluation; independent assurance; constrained tools and permissions; hard policy boundaries; fail-safe behavior; controlled rollout and continuous monitoring; multi-party authorization for consequential actions where appropriate. If the required assurance cannot be demonstrated, do not deploy the use case or prohibit autonomous execution. | No unbounded autonomy for critical actions. Explicit human authorization and, where appropriate, two-person control; system must fail safely and support shutdown or rollback. |

The tiers should not be interpreted as “Level 1 is safe” and “Level 4 is forbidden.” They establish the default controls needed before a specific use is approved. A Level 4 use may be permissible in a tightly constrained, validated setting; a lower-tier use may still be prohibited by law or policy. Conversely, a task with no viable means of validating its consequential claims may be inappropriate at any level if its expected benefits do not justify the residual risk.

### 6.4 Match the control to the failure mode

Risk level sets the required assurance intensity; failure-mode analysis determines which controls are useful. Applying “human review” to every problem is no more rigorous than applying “add citations” to every hallucination.

| Failure mode | Appropriate controls | What the control does not prove |
|---|---|---|
| Unsupported factual claim or fabricated source | Open the cited source; check that it exists, is authoritative and current, and supports the exact claim; prefer primary evidence where available. | A citation in the output does not prove that the source supports it. |
| Omission, distortion, or incorrect extraction | Compare the generated result with the source; use schemas, coverage checks, deterministic parsing, and targeted sampling or full review according to risk. | A structured format does not guarantee that the underlying interpretation is correct. |
| Calculation, code, or structured transformation error | Recompute with deterministic functions; execute tests; validate ranges, types, invariants, and boundary cases. | Passing selected tests does not establish correctness outside their coverage. |
| Missing context or false premise | Identify assumptions explicitly; request missing inputs; use a checklist of critical context; prevent the system from silently filling decision-critical gaps. | More context is not always better; excessive or irrelevant context can introduce noise or conflict. |
| Sycophancy or answer change under pressure | Use neutral prompts; ask for evidence and counterarguments; compare the claim with external sources; preserve initial answer and changes for high-risk workflows. | A different wording or second answer from the same model is not independent confirmation. |
| Self-review failure | Require independent evidence, execution, retrieval, a different validation method, or qualified human review; record what actually checked the claim. | A second model or multi-agent workflow is not independent if it shares the same sources, assumptions, or failure mode. |
| Automation bias or rubber-stamp approval | Ask the reviewer to form an initial judgment before seeing the suggestion where appropriate; require a short rationale for agreement on high-risk decisions; provide time, training, authority, and evidence. | Human presence or an approval click does not prove meaningful oversight. |
| Model, prompt, data, or workflow drift | Version the system; monitor real outcomes; re-test after material updates; define incident and rollback thresholds. | A historical benchmark does not prove continued performance after a system change. |
| Content-origin uncertainty | Use provenance metadata, signed records, source history, logs, and change tracking where supported. | Provenance does not by itself establish truth, accuracy, or decision fitness [[22](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html)]. |

### 6.5 Three distinct evidence questions: provenance, validity, and decision fitness

The framework separates three questions because each needs a different kind of answer.

**Provenance: Where did this come from, and what happened to it?** Provenance covers origin, ownership or signer assertions, transformations, timestamps, and the path through which a record was produced. Standards such as C2PA can help establish a tamper-evident history for supported digital media. C2PA explicitly does not determine whether the underlying content is true or factual; its provenance information is a signal for a recipient to interpret in context [[22](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html)]. For AI output, relevant provenance may also include model and version, source records, retrieval trace, prompt or instruction version, tool calls, and reviewer actions.

**Validity: Does the available evidence support this claim?** Validity is claim-specific. It requires opening the original source, checking the relevant passage or data, testing a calculation, comparing a transformation with its input, or using another method that can detect the likely error. Provenance helps identify evidence; it does not replace validation.

**Decision fitness: Is this evidence sufficient and appropriate for the decision?** A claim may be true but irrelevant, stale, incomplete, or too weak to support the proposed action. A contract date could be extracted correctly but not establish that a recompete is imminent. A medical statistic could be accurate but not applicable to the individual. Decision fitness asks whether the evidence is current, contextually relevant, complete enough, and proportionate to the decision’s required standard.

These questions imply three distinct checks. An organization should not label an output “verified” simply because a source trail exists. Nor should it infer decision readiness from factual correctness alone. A claim can have complete provenance and still be false; it can be true and still not be sufficient for the decision.

### 6.6 Human oversight that can actually work

An effective human review arrangement requires more than appointing a person to approve output. It should define:

- **Competence:** the reviewer has the domain knowledge and task-specific skills needed to evaluate the claim.
- **Evidence access:** the reviewer can inspect underlying sources, data, assumptions, and relevant system behavior—not just a polished summary.
- **Time and workload:** the expected review depth is realistic within the time available; review capacity must scale with output volume.
- **Independence:** the reviewer can reach a judgment not wholly inherited from the model’s framing. For high-risk decisions, consider obtaining an initial assessment before showing the AI recommendation.
- **Authority:** the reviewer can reject the output, request additional evidence, delay action, or stop the workflow without penalty for raising a well-founded concern.
- **Accountability:** a person or role owns the decision and consequences; responsibility cannot be delegated to “the AI said so.”

Cognitive forcing is a tool to support independent judgment, not a ritual to impose everywhere. It is most useful where a reviewer may be unduly influenced by a recommendation and where independent reasoning is feasible and valuable. The study by Buçinca and colleagues offers evidence for this design direction in its tested tasks, while the wider literature emphasizes that appropriate trust depends on system, task, user, and context [[16](https://doi.org/10.1145/3449287)] [[9](https://doi.org/10.1145/3696449)].

### 6.7 Automated evaluators and layered verification

Human review does not scale indefinitely, and not every output requires expert interpretation. Automated evaluators, including model-based judges, can help screen work, apply rubrics, prioritize anomalies, and direct human attention. However, LLM-as-a-judge systems have their own biases and should not be treated as an unquestioned gold standard. Research on model-as-judge evaluation has documented useful agreement with human preferences alongside sensitivity to features such as answer position, response style, and evaluation design [[23](https://arxiv.org/abs/2306.05685)].

The most defensible pattern is layered verification: use deterministic checks for properties that can be tested exactly; source comparison for claims tied to evidence; independent model-based review for suitable screening tasks; and qualified human review for ambiguity, high consequence, context, and exceptions. Periodically evaluate the evaluator itself against known cases and independent human judgments. Where multiple checks rely on the same model, same source, or same incorrect assumption, count them as correlated evidence rather than independent confirmation.

### 6.8 Governance and legal alignment

Governance should assign ownership of the use case, system configuration, data, validation, ongoing monitoring, and final decision. A model provider’s documentation is relevant but does not eliminate the deployer’s responsibility to examine whether the integrated system is fit for the intended use. Likewise, a human user should not be made the sole line of defense for risks that require design controls, access restrictions, system testing, or organizational policy.

NIST’s AI RMF 1.0 offers a voluntary lifecycle framework organized around Govern, Map, Measure, and Manage, and its Generative AI Profile provides additional risk-management guidance for generative AI [[19](https://www.nist.gov/itl/ai-risk-management-framework)] [[20](https://doi.org/10.6028/NIST.AI.600-1)]. As of October 2026, NIST states that AI RMF 1.0 is being revised and describes ongoing work on a critical-infrastructure profile [[24](https://www.nist.gov/programs-projects/concept-note-ai-rmf-profile-trustworthy-ai-critical-infrastructure)]. Organizations should therefore check the current status of relevant guidance rather than freeze their governance around an old document version.

The EU AI Act is a binding regulatory instrument with requirements that apply on a phased timeline; its legal classification and obligations depend on the system and context of use [[21](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)]. The RPCR levels in this paper are not a restatement of the Act’s legal categories and do not determine compliance. An organization must separately identify applicable statutory obligations, sector rules, contractual commitments, professional standards, and privacy or security duties. A voluntary internal risk matrix can supplement those requirements but cannot displace them.

## 7. The RPCR Operating Cycle

The framework is intended to function as a repeatable process over the life of a system, not a one-time approval. The recommended cycle is:

### Step 1 — Define the decision, not just the prompt

Describe what the AI will help produce or decide, who relies on the output, what action can follow, what constitutes a correct result, and what harm a failure could cause. “Summarize documents” is not a complete use-case definition if the summary drives a medical, legal, financial, employment, or procurement decision.

### Step 2 — Identify the evidence standard

List the claims that matter, the authoritative sources or tests that can validate them, the relevant time horizon, and any assumptions or contextual inputs that must be present. Specify whether the task demands factual accuracy, source faithfulness, completeness, calibrated uncertainty, fairness, or some combination. Define what cannot be verified and how that limitation affects the use case.

### Step 3 — Assess inherent risk

Use the dimensions in Section 6.2 to assign a provisional RPCR level and document the rationale. Consider the full workflow, including tool permissions, output volume, downstream actions, human factors, and propagation. Assess legal and sector-specific requirements separately.

### Step 4 — Select controls against concrete failure modes

Choose the mitigation bundle from the appropriate tier and map each control to a failure mode. Avoid relying on general-purpose “human review,” a disclaimer, a citation requirement, or self-critique where a more specific control is possible. Identify controls that are mandatory versus recommended and who owns them.

### Step 5 — Test the complete workflow before deployment

Evaluate the full configured system, not merely the underlying model. Test representative normal cases, boundary cases, missing or contradictory context, adversarial or leading prompts, stale or unreliable source material, and known high-impact failure modes. Measure both quality and the quality of the verification process. Include the cost and time of review in the assessment.

### Step 6 — Authorize use, constrain action, or decline deployment

Set the allowed uses, prohibited uses, required approver, tool permissions, escalation paths, and conditions for stopping. If the system cannot meet the required assurance level, reduce its scope, change the workflow, add controls, limit it to lower-risk tasks, or do not deploy it for the decision at issue.

### Step 7 — Monitor outcomes and re-evaluate changes

Track error patterns, near misses, overrides, user behavior, source changes, review burden, and the effects of model or workflow updates. Reassess when the model, prompt, tools, retrieval corpus, policy, data, user population, or use case changes. Incident handling should include containment, correction, reporting where required, root-cause analysis, and a decision on whether the use can resume.

### Step 8 — Learn without erasing accountability

Use verified failures and successful interventions to improve prompts, tests, sources, training, and process design. Preserve records appropriate to the risk. Do not let the system’s ability to produce a post-hoc explanation substitute for evidence of what happened or why the decision was authorized.

## 8. Applying the Framework: Six Illustrative Cases

These examples demonstrate how the same broad trust problem can require different controls depending on who or what is making the recommendation, what evidence is available, and what the decision could affect. They are illustrations, not substitutes for a domain-specific risk assessment.

### Case 1 — Advice from a commercially motivated human

An adviser recommends a new market, a service provider, or a major purchase and stands to gain if the recipient follows the recommendation. Self-interest does not automatically make the advice wrong; it does mean the listener should separate capability from incentives. Relevant questions include whether the adviser has demonstrated expertise, what evidence supports the claim, what conflicts or commercial interests should be disclosed, and whether important claims can be checked independently. This is a human-trust problem rather than an AI risk tier by itself. If the advice is supported by AI-generated analysis, the evidence for that analysis should be assessed separately, and the incentives of the adviser, vendor, and deploying organization should not be attributed to the model as though it had human intent.

### Case 2 — A precise question with missing context

A manager asks whether a particular requirement applies but omits the jurisdiction, contract type, effective date, or purpose of the decision. A system may silently infer the missing context and return a narrow, confident answer. The primary control is to identify which inputs are decision-critical, surface the ambiguity, and request or explicitly state assumptions before answering. The claim should then be checked against current authoritative evidence. This may be Level 2 for internal planning and Level 3 or higher if the answer informs legal, safety, financial, or rights-affecting action. More-specific prompting is not a substitute for missing facts, and a polished explanation cannot resolve an underspecified question.

### Case 3 — Brainstorming an internal workshop

The AI suggests names, agenda options, and discussion questions. The output is low consequence, readily reviewed, and easily corrected. This is generally Level 1. Lightweight human review is proportionate; extensive source-by-source fact checking adds little value if the content is clearly treated as brainstorming and not as factual authority. Sensitive data should still be excluded unless the environment and policy authorize it.

### Case 4 — Preparing a customer-facing market summary

The AI summarizes trends, statistics, and competitor statements that will be sent to a customer. Factual misstatements can affect reputation and business decisions, and some claims may be stale or selectively framed. This generally warrants Level 2. The reviewer should check material claims against primary or authoritative sources, confirm dates and definitions, and retain links for traceability. A polished summary, a model confidence statement, or a list of citations is not enough by itself. If the summary recommends a consequential decision, the review should assess the decision logic and uncertainties as well as individual facts.

### Case 5 — Prioritizing government-contract capture opportunities

An AI workflow flags contract actions, incumbent risks, possible recompetes, funding changes, and likely next steps from public procurement data. The output may be valuable as an intelligence signal, but a false termination flag or incorrect end date could divert business-development effort. Before the report is treated as operationally reliable, factual signals should be tied to the original award or transaction record, classification rules should be tested against known cases, and uncertain inferences should be labeled separately from confirmed events. This is often at least Level 2 and may rise to Level 3 if the output drives a major bid/no-bid decision, staffing decision, or material expenditure. The correct control is not necessarily to verify every sentence manually; it is to make event evidence, source data, classification logic, and confidence limitations inspectable, then require human review for high-consequence capture decisions.

### Case 6 — AI recommending or taking an irreversible action

An agent may alter production systems, make a consequential eligibility decision, issue a payment, or initiate an action affecting health, safety, or fundamental rights. Errors can propagate quickly and may be difficult to reverse. This points to Level 4 or a legally restricted use, depending on context. The workflow needs hard permission boundaries, independent tests, auditable evidence, fail-safe behavior, authorized approval, rollback or containment, and ongoing monitoring. If the result cannot be validated to the required standard or a meaningful human cannot intervene, the action should not be delegated to the system.
## 9. Measurement: How to Know Whether the Framework Works

Risk-proportionate governance should be evaluated by outcomes and process quality, not by user trust scores alone. A user can report high trust while making poor decisions, or low trust while ignoring useful advice. The measures should fit the task and distinguish the model, the workflow, the reviewer, and the overall decision process.

Recommended measures include:

- **Task performance:** error rate, omission rate, unsupported-claim rate, source-faithfulness, calibration where meaningful, and performance on edge cases, measured against defined ground truth or expert standards.
- **Verification effectiveness:** proportion of seeded or naturally occurring errors detected; false alarms and missed errors; coverage of claims checked; quality and independence of evidence used.
- **Decision quality:** whether the final decision meets the defined standard, including fairness or other multi-objective criteria where relevant—not simply whether the user followed the AI.
- **Human oversight quality:** reviewer competence, time available, frequency and quality of overrides, whether reviewers can explain why a recommendation was accepted, and whether approval behavior changes under workload pressure.
- **Operational economics:** time and cost to produce a dependable result, including review and rework; verification-capacity ratio; cost of false positives and false negatives; and the volume of work that must be escalated.
- **Lifecycle performance:** drift, incident rate, near misses, source freshness, response to model or workflow changes, and success of rollback or escalation mechanisms.

The metrics require careful interpretation. A high override rate is not automatically good; it may mean reviewers are appropriately skeptical, or it may mean the system is poor. A low override rate can reflect excellent performance or rubber-stamping. A model’s high benchmark score may not predict its behavior under a different prompt, source corpus, integration, or user population. Measures should be paired with case review and reassessment of the original risk assumptions.

For a pilot, an organization should establish a baseline before deployment, define acceptable thresholds and stop conditions, and test whether the proposed mitigations actually reduce material error without creating disproportionate burdens. The framework’s own risk tiers and control bundles should be treated as hypotheses to evaluate and refine through documented use.

## 10. Limitations, Counterarguments, and Research Agenda

### 10.1 AI may reduce verification costs as well as generation costs

The central economic asymmetry is conditional, not universal. AI can help locate evidence, compare documents, run tests, flag anomalies, and increase the number of claims a human can review. It may reduce the cost of verification in some tasks. The question is when these reductions keep pace with the amount and complexity of generated work, and when the cost of obtaining dependable ground truth remains a bottleneck. Future empirical work should compare end-to-end costs and error outcomes across human-only, AI-only, and hybrid workflows rather than assume one pattern for all use cases.

### 10.2 Humans are not a universal oracle

Human oversight can add domain knowledge, contextual judgment, ethical responsibility, and an independent perspective. It can also introduce inconsistency, fatigue, bias, and additional error. For bounded, deterministic tasks, automated tests may be more reliable than manual review. For high-volume work, layered automation can screen and prioritize cases more effectively than full manual review. The framework therefore requires competent and proportionate oversight, not blanket human supremacy. Where there is a reliable independent check, it should be used; where a human is essential, the role must be substantive.

### 10.3 Trust and reliance are multidimensional and dynamic

There is no settled universal definition of appropriate trust or one measurement that applies across all tasks. Reviews of human-AI trust identify variations in definitions, measures, and interventions, and emphasize context, task, user, and system factors [[9](https://doi.org/10.1145/3696449)]. RPCR chooses an operational emphasis—warranted decision weight—but it does not resolve every theoretical disagreement. Its terms and metrics should be specified in advance for each implementation.

### 10.4 A risk tier cannot replace legal or professional judgment

The proposed four levels simplify practical discussion. They cannot fully represent every statutory rule, sector-specific requirement, value conflict, or unusual context. An internal classification can assist governance only if a separate compliance analysis identifies the applicable obligations and any categorical prohibitions. High-risk uses may require formal assessments, documentation, notices, human oversight, or other controls that go beyond this paper.

### 10.5 Evidence, provenance, and explanation are different

A source trail, signature, or model-generated rationale can help users understand a result, but none is a universal proof of truth. C2PA itself states that provenance alone cannot determine factual truth [[22](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html)]. Explanations may help direct attention or challenge assumptions, but they should not be treated as faithful accounts of the internal generation process without evidence. Future methods should evaluate the fidelity, usefulness, and failure behavior of explanations rather than count their presence as an assurance control.

### 10.6 The framework requires empirical validation

RPCR is a proposed theory-informed synthesis. Its four levels, assessment dimensions, default controls, and verification-capacity ratio have not been validated as a single instrument. They should be piloted across different settings—such as factual reporting, professional advice, structured data extraction, code generation, procurement analysis, and agentic action—and tested for inter-rater consistency, predictive value, usability, cost, and impact on outcomes. Research should examine whether the framework distinguishes useful, low-risk AI use from situations where reliance should be constrained, and whether its controls reduce errors without creating excessive friction or false assurance.

A disciplined research agenda would include: (1) operationalizing and validating the risk dimensions; (2) comparing control bundles against specific failure modes; (3) measuring how independent various verification methods actually are; (4) examining the effect of cognitive-forcing approaches over repeated use and under workload pressure; (5) quantifying when AI reduces versus increases the cost of verification; (6) studying accountability across provider-deployer-user relationships; and (7) testing how provenance, evidence quality, and decision fitness interact in real workflows.

## 11. Conclusion: Warrant the Reliance, Not the Appearance

Trust has always allowed people and organizations to act in the face of uncertainty without paying the cost of checking everything. It remains essential in an AI-enabled economy because users must still rely on experts, institutions, developers, deployers, and the people who govern systems. But the apparent social cues of a conversational interface do not establish the reliability of its content, and the fact that a model produces a source, explanation, or second answer does not guarantee independent verification.

Research gives reasons for caution without supporting blanket rejection. Generative systems can hallucinate; sycophancy has been observed in specific models and test conditions; intrinsic self-correction can fail; and people can over-rely on automated advice. At the same time, AI can improve productivity, can assist with verification, and can perform reliably on tasks where the system is appropriately designed and evaluated. What follows is not “trust AI” or “never trust AI,” but a more practical rule: **the decision weight assigned to an AI output should be proportionate to the quality of evidence, the system’s validated capability, the context of use, and the consequences of being wrong.**

The proposed Risk-Proportionate Calibrated Reliance framework turns this principle into a workflow. It starts with the decision and its potential harm, evaluates uncertainty and verifiability, selects controls matched to concrete failure modes, establishes meaningful review and accountability, and continues through testing and monitoring. Provenance, validity, and decision fitness are treated as separate requirements. Verification effort is neither minimized blindly nor maximized indiscriminately; it is selected to meet the assurance standard justified by the use case.

The larger economic question remains open. As AI makes some forms of information and execution less costly, organizations must learn whether their capacity to validate and govern the resulting work is keeping pace. The answer will vary by task, system design, and institutional setting. Organizations that can demonstrate what they checked, why a result was relied upon, who authorized the decision, and how failure will be contained will be better positioned to capture AI’s benefits without mistaking abundant output for dependable judgment.

The objective is not to eliminate uncertainty. It is to make uncertainty visible, make reliance deliberate, and ensure that the safeguards around an AI-assisted decision are strong enough for what is at stake.

---

## References

**[[1](https://doi.org/10.5465/amr.1995.9508080335)]** Mayer, R. C., Davis, J. H., & Schoorman, F. D. (1995). An Integrative Model of Organizational Trust. *Academy of Management Review, 20*(3), 709–734.

**[[2](https://doi.org/10.1086/227496)]** Williamson, O. E. (1981). The Economics of Organization: The Transaction Cost Approach. *American Journal of Sociology, 87*(3), 548–577.

**[[3](https://doi.org/10.2307/1879431)]** Akerlof, G. A. (1970). The Market for “Lemons”: Quality Uncertainty and the Market Mechanism. *The Quarterly Journal of Economics, 84*(3), 488–500.

**[[4](https://doi.org/10.1518/hfes.46.1.50_30392)]** Lee, J. D., & See, K. A. (2004). Trust in Automation: Designing for Appropriate Reliance. *Human Factors, 46*(1), 50–80.

**[[5](https://doi.org/10.1136/amiajnl-2011-000089)]** Goddard, K., Roudsari, A., & Wyatt, J. C. (2012). Automation Bias: A Systematic Review of Frequency, Effect Mediators, and Mitigators. *Journal of the American Medical Informatics Association, 19*(1), 121–127.

**[[6](https://doi.org/10.1145/3571730)]** Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., Ishii, E., Bang, Y., Madotto, A., & Fung, P. (2023). Survey of Hallucination in Natural Language Generation. *ACM Computing Surveys, 55*(12), Article 248.

**[[7](https://doi.org/10.2307/1884852)]** Simon, H. A. (1955). A Behavioral Model of Rational Choice. *The Quarterly Journal of Economics, 69*(1), 99–118.

**[[8](https://doi.org/10.1016/0304-405X%2876%2990026-X)]** Jensen, M. C., & Meckling, W. H. (1976). Theory of the Firm: Managerial Behavior, Agency Costs and Ownership Structure. *Journal of Financial Economics, 3*(4), 305–360.

**[[9](https://doi.org/10.1145/3696449)]** Mehrotra, S., Degachi, C., Vereschak, O., Jonker, C. M., & Tielman, M. L. (2024). A Systematic Review on Fostering Appropriate Trust in Human-AI Interaction: Trends, Opportunities and Challenges. *ACM Journal on Responsible Computing, 1*(4), Article 26.

**[[10](https://doi.org/10.1016/j.patter.2024.101045)]** Lucas, G. M., Becerik-Gerber, B., & Roll, S. C. (2024). Calibrating workers’ trust in intelligent automated systems. *Patterns, 5*(9), Article 101045.

**[[11](https://arxiv.org/abs/2207.05221)]** Kadavath, S., Conerly, T., Askell, A., Henighan, T., Drain, D., Perez, E., et al. (2022). Language Models (Mostly) Know What They Know. arXiv:2207.05221.

**[[12](https://arxiv.org/abs/2212.09251)]** Perez, E., Ringer, S., Lukošiūtė, K., Nguyen, K., et al. (2022). Discovering Language Model Behaviors with Model-Written Evaluations. arXiv:2212.09251.

**[[13](https://arxiv.org/abs/2310.13548)]** Sharma, M., Tong, M., Korbak, T., Duvenaud, D., et al. (2023). Towards Understanding Sycophancy in Language Models. arXiv:2310.13548.

**[[14](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b1efde53be364a73914f58805a001731-Abstract.html)]** Ouyang, L., Wu, J., Jiang, X., Almeida, D., Wainwright, C. L., Mishkin, P., et al. (2022). Training Language Models to Follow Instructions with Human Feedback. *Advances in Neural Information Processing Systems, 35*.

**[[15](https://arxiv.org/abs/2310.01798)]** Huang, J., Chen, X., Mishra, S., Zheng, H. S., Yu, A. W., Song, X., & Zhou, D. (2023). Large Language Models Cannot Self-Correct Reasoning Yet. arXiv:2310.01798.

**[[16](https://doi.org/10.1145/3449287)]** Buçinca, Z., Malaya, M. B., & Gajos, K. Z. (2021). To Trust or to Think: Cognitive Forcing Functions Can Reduce Overreliance on AI in AI-assisted Decision-making. *Proceedings of the ACM on Human-Computer Interaction, 5*(CSCW1), Article 188.

**[[17](https://doi.org/10.1126/science.adh2586)]** Noy, S., & Zhang, W. (2023). Experimental Evidence on the Productivity Effects of Generative Artificial Intelligence. *Science, 381*(6654), 187–192.

**[[18](https://arxiv.org/abs/2602.20946)]** Catalini, C., Hui, X., & Wu, J. (2026). Some Simple Economics of AGI. arXiv:2602.20946, version 2. Preprint.

**[[19](https://www.nist.gov/itl/ai-risk-management-framework)]** National Institute of Standards and Technology. (2023; current framework page accessed October 2026). Artificial Intelligence Risk Management Framework (AI RMF 1.0).

**[[20](https://doi.org/10.6028/NIST.AI.600-1)]** Autio, C., Schwartz, R., Dunietz, J., Jain, S., Stanley, M., Tabassi, E., Hall, P., & Roberts, K. (2024). *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile* (NIST AI 600-1). National Institute of Standards and Technology.

**[[21](https://eur-lex.europa.eu/eli/reg/2024/1689/oj)]** European Parliament and Council of the European Union. (2024; consolidated status checked October 2026). Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act). Official Journal of the European Union.

**[[22](https://spec.c2pa.org/specifications/specifications/2.4/explainer/Explainer.html)]** Coalition for Content Provenance and Authenticity. (2026). *C2PA and Content Credentials Explainer*, Version 2.4.

**[[23](https://arxiv.org/abs/2306.05685)]** Zheng, L., Chiang, W.-L., Sheng, Y., Zhuang, S., Wu, Z., Zhuang, Y., et al. (2023). Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena. arXiv:2306.05685.

**[[24](https://www.nist.gov/programs-projects/concept-note-ai-rmf-profile-trustworthy-ai-critical-infrastructure)]** National Institute of Standards and Technology. (2026). Concept Note: AI RMF Profile on Trustworthy AI in Critical Infrastructure. Project page, updated July 17, 2026.
