---
layout: default
title: "AI Research Daily"
---

# AI Research — Daily Paper Digest

**2026-09-02** — 96 new papers from arXiv. [📌 View favorites]({{ site.baseurl }}/favorites/) for archived papers.


## [HarnessEvolve: Learning from Reference Trajectories for Reliable Agent Self-Evolution]({{ site.baseurl }}/papers/2609.00829/)

**2026-09-01** · Wen Jiang et al. 

Self-evolving agents advance toward autonomy by optimizing their harness---prompts, skills, tools, and execution logic---based on environmental feedback. This paradigm, however, is hampered by three challenges: \textit{credit assignment failure}, where terminal success/failure feedback makes it ambi...

[Read more →]({{ site.baseurl }}/papers/2609.00829/)

---

## [Selective Agent Guidance via Entropy: Learning Autonomous Policies from Imperfect VLM Teachers]({{ site.baseurl }}/papers/2609.01567/)

**2026-09-01** · Matteo Merler et al. 

Vision-Language Models (VLMs) provide useful priors for interactive decision-making, but using them directly as policies is expensive and brittle: they must be queried at every step, do not improve from environment interaction, and can repeat systematic errors. We study how to learn a cheap autonomo...

[Read more →]({{ site.baseurl }}/papers/2609.01567/)

---

## [CordisBench: Can Language Models Reason About Component Lifecycles in Dynamic Agent Harnesses?]({{ site.baseurl }}/papers/2609.01600/)

**2026-09-01** · Damien Sileo et al. 

Dynamic agent harnesses let language models change the software that shapes their own execution. This flexibility brings a new reasoning burden: a local plugin change can propagate through dependencies and cleanup. We introduce CordisBench, a 1,200-question benchmark of this lifecycle reasoning. It ...

[Read more →]({{ site.baseurl }}/papers/2609.01600/)

---

## [Disclosure-Gated User Simulation for Companion-Agent Evaluation]({{ site.baseurl }}/papers/2609.00982/)

**2026-09-01** · Yao Liu et al. 

Using a large language model to play the user is now standard in scalable evaluation. It has a repeatedly diagnosed failure: the simulated user is excessively cooperative, so a system under test can score by the sheer number of questions it asks rather than by making the user willing to speak. We an...

[Read more →]({{ site.baseurl }}/papers/2609.00982/)

---

## [Data-Driven Persona-Conditioned Agents for A/B Test Simulation]({{ site.baseurl }}/papers/2609.01038/)

**2026-09-01** · Ziyad Benomar et al. 

A/B testing is the gold standard for evaluating product changes, but each experiment requires real user traffic, engineering effort, and weeks of measurement. We propose a simulation framework that predicts A/B test outcomes using LLM-powered agents conditioned on data-driven personas grounded in re...

[Read more →]({{ site.baseurl }}/papers/2609.01038/)

---

## [Agentic Empirical Asset Pricing: Methodological Foundations]({{ site.baseurl }}/papers/2609.00731/)

**2026-09-01** · Yingjian Pan et al. 

Recent advances in LLM agents enable a new paradigm for asset pricing, which we call Agentic Empirical Asset Pricing (AEAP): systems that autonomously conduct the scientific discovery process itself. We define AEAP and identify its core building blocks. Existing evaluation practices backtest only th...

[Read more →]({{ site.baseurl }}/papers/2609.00731/)

---

## [Why Multi-Layer Message Passing Works: Completeness Theory for Graph Neural Network Interatomic Potentials]({{ site.baseurl }}/papers/2609.00528/)

**2026-09-01** · Pingbing Ming et al. 

We prove that the Hypergraph Neural Network, an invariant architecture with 3-body message passing, is a universal approximator for potential energy surfaces. Our main contribution is a multi-layer completeness theory. We show that $L$ layers of message passing on sparse, cutoff-based graphs achieve...

[Read more →]({{ site.baseurl }}/papers/2609.00528/)

---

## [Bandits in Prod: Hyperparameter Optimization at Inference Time]({{ site.baseurl }}/papers/2609.01335/)

**2026-09-01** · Louis Abraham et al. 

Many production systems can assess a configuration only by using it on live requests and observing noisy feedback. Modern agentic systems are a prominent example, with inference-time choices such as model selection, retrieval depth, prompting strategy, and decoding temperature, yet often with no rep...

[Read more →]({{ site.baseurl }}/papers/2609.01335/)

---

## [Towards Generalizable Visually Grounded Exploration of Household Devices]({{ site.baseurl }}/papers/2609.00845/)

**2026-09-01** · Linhao Zheng et al. 

Recent advancements in Vision-Language Models (VLMs) have demonstrated impressive capabilities in static visual recognition and high-level semantic reasoning. However, current embodied exploration paradigms still heavily rely on imitation learning from human-annotated trajectories, which severely li...

[Read more →]({{ site.baseurl }}/papers/2609.00845/)

---

## [WorldBench: Culturally Grounded Benchmark for Multilingual Agents]({{ site.baseurl }}/papers/2609.01056/)

**2026-09-01** · Leonardo Ranaldi et al. 

Despite the growing use of LLM-powered agents to solve multi-step tasks in complex environments, existing benchmarks rarely test state preservation, performance across languages, and application to realistic, grounded scenarios. To address these concerns, we present WorldBench: a comprehensive, mult...

[Read more →]({{ site.baseurl }}/papers/2609.01056/)

---

## [Edge-Girth as a Structural Edge Feature for Graph Neural Networks]({{ site.baseurl }}/papers/2609.01441/)

**2026-09-01** · Lilian Marey et al. 

Graph neural networks (GNN) based on message passing are provably no more powerful than the one-dimensional Weisfeiler--Leman colour-refinement test (1-WL): two graphs it cannot tell apart receive identical representations, however deep or wide the network. A common remedy augments node or edge feat...

[Read more →]({{ site.baseurl }}/papers/2609.01441/)

---

## [LEAP: Likelihood Elicitation and Aggregation for LLM-based Probabilistic Forecasting]({{ site.baseurl }}/papers/2609.01337/)

**2026-09-01** · Yufei Chen et al. 

LLM-based forecasting systems have improved on real-world tasks such as financial markets and sports outcomes, largely through stronger search and tool use. Many systems still ask an LLM to read all collected evidence together and produce the final forecast. We call this design Monolithic Prediction...

[Read more →]({{ site.baseurl }}/papers/2609.01337/)

---

## [Spawn Freely, Act Sparingly: Progressive Risk Vesting for Recursive LLM-Agent Trees]({{ site.baseurl }}/papers/2609.01035/)

**2026-09-01** · Molly Wang et al. 

Recursive LLM agents can broaden their search by spawning specialists. Some branches later request tools that send data or deploy code. When should a branch receive authority to act? We distinguish sandbox spawning, in which external controls prevent the specified harm, from capability activation, i...

[Read more →]({{ site.baseurl }}/papers/2609.01035/)

---

## [Explore More, Drift Less: Outcome-Only Reinforcement Learning Can Suffice for Long-Horizon Interactive Agents]({{ site.baseurl }}/papers/2609.01245/)

**2026-09-01** · Liming Pu et al. 

Reinforcement learning is a natural way to post-train LLM agents for long-horizon interactive tasks judged only by end-of-task verification, yet a shared belief holds that outcome-only RL soon hits a ceiling on small open models. Recent work therefore compensates around the training with denser rewa...

[Read more →]({{ site.baseurl }}/papers/2609.01245/)

---

## [SciTrue: Reliable Scientific Claim Validation with Frontier and Open Language Models at the NTCIR SciClaimEval Task]({{ site.baseurl }}/papers/2609.00654/)

**2026-09-01** · Qiming Bao et al. 

We describe the SciTrue team's participation in both subtasks of the NTCIR-19 SciClaimEval task~\cite{sciclaimeval}, which asks systems to verify scientific claims against the tables and figures of a paper. Rather than tuning a single model, we benchmark eleven frontier and open multimodal models un...

[Read more →]({{ site.baseurl }}/papers/2609.00654/)

---

## [ChatDev 2.0: A No-Code Multi-Agent Platform for Developing Everything]({{ site.baseurl }}/papers/2609.00714/)

**2026-09-01** · Yufan Dang et al. 

Large language model (LLM)-based multi-agent systems (MAS) have shown strong potential for solving complex tasks, yet their development forces a tradeoff: code frameworks are expressive but engineering-intensive, while no-code builders simplify authoring but constrain agent interactions to author-de...

[Read more →]({{ site.baseurl }}/papers/2609.00714/)

---

## [SymFold: Synergizing Evolutionary and Structural Priors for Accurate Protein Inverse Folding]({{ site.baseurl }}/papers/2609.01353/)

**2026-09-01** · Handong Wang et al. 

Protein inverse folding aims to recover amino acid sequences for a given 3D protein structure, underpinning broad applications such as enzyme engineering and drug discovery.Current methods often follow a serial pipeline, in which a structure encoder predicts a coarse sequence, which is then refined ...

[Read more →]({{ site.baseurl }}/papers/2609.01353/)

---

## [Reinforcement Learning Enhanced LLM Agents for Complex Vehicle Routing Problems]({{ site.baseurl }}/papers/2609.00859/)

**2026-09-01** · Yi Chen et al. 

Vehicle Routing Problems (VRPs) are fundamental combinatorial optimization problems with widespread applications in various scenarios. The advanced optimization solvers can effectively solve such problems. However, modeling complex VRP variants for solvers often requires substantial domain expertise...

[Read more →]({{ site.baseurl }}/papers/2609.00859/)

---

## [Retrieved but not ranked: surface-form bias in structural retrieval, from mathematics to agent trajectories]({{ site.baseurl }}/papers/2609.01556/)

**2026-09-01** · Nabira Rashid et al. 

We evaluate embedding retrieval where surface form and meaning are pulled apart on purpose: retrieving items that share underlying structure but not wording, in two unrelated domains under one protocol, competition mathematics (MathNet-Retrieve; 500 queries, 117,088-item corpus) and embodied-agent t...

[Read more →]({{ site.baseurl }}/papers/2609.01556/)

---

## [When Guardrails Look Effective: Construct Validity Failures in LLM Agent Commerce Evaluation]({{ site.baseurl }}/papers/2609.01519/)

**2026-09-01** · Peiying Zhu et al. 

Interactive simulations increasingly evaluate policies in markets populated by language-model agents. Their outputs can look economic---prices, profits, consumer surplus, and welfare---without instantiating the behavior named in the claim. We audit this risk in a multi-turn buyer--seller testbed for...

[Read more →]({{ site.baseurl }}/papers/2609.01519/)

---

## [Calibration is the Bottleneck: An Action-Class Diagnostic of Multi-Turn Tool-Calling]({{ site.baseurl }}/papers/2609.00949/)

**2026-09-01** · Kangjia Zhao et al. 

Multi-turn tool calling is a core evaluation scenario for large language model (LLM) agents. On public tool-calling benchmarks, open-weight models now approach or even surpass closed-source frontier models in aggregate accuracy. However, this metric averages over many different multi-turn situations...

[Read more →]({{ site.baseurl }}/papers/2609.00949/)

---

## [GlossoGen: Emergent Language in Complex Multi-Agent LLM Interactions]({{ site.baseurl }}/papers/2609.01491/)

**2026-09-01** · Elias Stengel-Eskin et al. 

The growing rate at which LLM agents interact with one another raises key questions about language evolution in multi-LLM-agent settings, with implications for safety and monitorability as well as for linguistic accounts of LLMs. To address these questions, we introduce GlossoGen, a novel platform f...

[Read more →]({{ site.baseurl }}/papers/2609.01491/)

---

## [AgentFactory: Towards Automated Agentic System Design and Optimization]({{ site.baseurl }}/papers/2609.01045/)

**2026-09-01** · Enci Zhang et al. 

Large Language Models (LLMs) have demonstrated remarkable capabilities as powerful components in agentic systems, enabling sophisticated reasoning and complex task execution. However, current approaches to manually designing and optimizing agentic systems heavily rely on manual effort, limiting thei...

[Read more →]({{ site.baseurl }}/papers/2609.01045/)

---

## [EvoSCM: Scientific Belief Revision Through Causal Model Evolution and Experimentation]({{ site.baseurl }}/papers/2609.01526/)

**2026-09-01** · Qing Zhao et al. 

Scientific agents must learn not only how to reason, but also what to believe. However, existing LLM agents typically express scientific hypotheses in free-form text, leaving their beliefs implicit and difficult to test or revise. We introduce EvoSCM, which equips scientific agents with explicit str...

[Read more →]({{ site.baseurl }}/papers/2609.01526/)

---

## [Agentic programs: an emerging form of scientific software in computational materials science]({{ site.baseurl }}/papers/2609.00795/)

**2026-09-01** · Yunsung Lim et al. 

Computational materials science has traditionally delegated algorithmic tasks to computers while leaving scientific judgments to humans. We argue that recent LLM-based agent harnesses enable an emerging form of scientific software, agentic programs, that combine deterministic algorithms with bounded...

[Read more →]({{ site.baseurl }}/papers/2609.00795/)

---

## [EDGE: Error Dependency Graph-Guided Multi-Error Attribution in Multi-Agent LLM Systems]({{ site.baseurl }}/papers/2609.01360/)

**2026-09-01** · Jun Hou et al. 

Large language model (LLM) agent failures often contain multiple related errors rather than a single mistake. Existing attribution methods usually identify a responsible agent, step, or root cause, but do not explicitly model dependency between errors. We introduce EDGE, an Error Dependency Graph-gu...

[Read more →]({{ site.baseurl }}/papers/2609.01360/)

---

## [EdiTikZ: Scientific Figure Editing from Revision Trajectories]({{ site.baseurl }}/papers/2609.01409/)

**2026-09-01** · Christian Greisinger et al. 

Vision-language models (VLMs) have shown strong performance in generating scientific figures from text or images. However, producing publication-ready figures requires iterative refinement, making scientific figure editing an important yet largely unexplored task. Existing approaches rely on costly ...

[Read more →]({{ site.baseurl }}/papers/2609.01409/)

---

## [ARISE-RL: Agentic Rubric-Grounded Iterative Self-Evolution with Reinforcement Learning]({{ site.baseurl }}/papers/2609.01058/)

**2026-09-01** · Fanrui Zhang et al. 

Training open-ended agents via reinforcement learning (RL) is hindered by the lack of verifiable gold answers and scalable rubrics. Moreover, even near the model's capability boundary, long-horizon open-ended agentic tasks often yield brittle and unstable rewards, resulting in weak or noisy rollout ...

[Read more →]({{ site.baseurl }}/papers/2609.01058/)

---

## [One Policy, Any Budget: Internalizing Budget-Aware Search via Reinforcement Learning]({{ site.baseurl }}/papers/2609.00813/)

**2026-09-01** · Xiaowei Sun et al. 

While reinforcement learning has enabled LLM-based search agents to invoke external tools, existing methods train under fixed budgets and cannot adapt when constraints vary at deployment. We propose AnySearch, a framework that enables a single policy to perform budget-aware search under any budget c...

[Read more →]({{ site.baseurl }}/papers/2609.00813/)

---

## [Harness-of-Harness: Multi-Day Autonomous Software Development with Continual Improvement]({{ site.baseurl }}/papers/2609.01481/)

**2026-09-01** · Haoyang Yan et al. 

This paper studies autonomous software development, in which LLM-based coding agents transform high-level requirements into complete, functional, and usable software systems without human intervention. We introduce Harness-of-Harness (HoH), a framework that enables coding agents to continually impro...

[Read more →]({{ site.baseurl }}/papers/2609.01481/)

---

## [The Rise of Verbal Reinforcement Learning]({{ site.baseurl }}/papers/2609.01597/)

**2026-09-01** · Kshitij Tayal et al. 

Natural language is emerging as a primary feedback channel for improving language agents, capable of conveying intent, preferences, and causal structure in forms interpretable by both humans and modern language models. We call this paradigm Verbal Reinforcement Learning (VRL) and offer the first uni...

[Read more →]({{ site.baseurl }}/papers/2609.01597/)

---

## [Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching]({{ site.baseurl }}/papers/2609.01404/)

**2026-09-01** · Jaewoo Park et al. 

Multimodal Large Language Models (MLLMs) are strong perceivers of images and video. We ask how far that reach extends into acting: dropping an MLLM directly into a drone's control loop, with its entire action space declared solely in the prompt. Recent systems approach this setting but increasingly ...

[Read more →]({{ site.baseurl }}/papers/2609.01404/)

---

## [ContextPipe: Database-Inspired Context Assembly for Long-Horizon Agents]({{ site.baseurl }}/papers/2609.00749/)

**2026-09-01** · Peng Xu et al. 

Long-horizon large language model (LLM) agents require context assembly: the runtime must decide what to include in each prompt, in what order, and when to compact history under a hard context-window budget and a byte-sensitive prompt cache. In production agentic systems, this logic is scattered acr...

[Read more →]({{ site.baseurl }}/papers/2609.00749/)

---

## [Parsing the Stream: A Live Trace Model for Long-Horizon Agents and Their Observers]({{ site.baseurl }}/papers/2609.01466/)

**2026-09-01** · Egor Pakhomov et al. 

A long-horizon agent's trace outgrows both of its consumers: the human observer monitoring the run, and the agent itself, whose bounded context the trace must be folded back into. We present a live trace model, an append-only event ledger folded incrementally into typed run state and compiled into p...

[Read more →]({{ site.baseurl }}/papers/2609.01466/)

---

## [Making Prospective Memory SLM-Shaped: Typed Intention Stores for Small-Model Agents]({{ site.baseurl }}/papers/2609.01272/)

**2026-09-01** · Jinqing Zhao et al. 

Prospective memory means carrying out a deferred intention at the right future cue while other work continues. Benchmarks now isolate it as an agent skill, yet frontier LLMs still struggle: the best published PM-Bench scaffold reaches only 65.1% Set-F1. We argue that this loop is schema-constrained ...

[Read more →]({{ site.baseurl }}/papers/2609.01272/)

---

## [Dr. Claw: An AI Scientist Workspace for Vibe Research]({{ site.baseurl }}/papers/2609.00365/)

**2026-08-31** · Dingjie Song et al. 

Command-line coding agents (e.g., Claude Code, Gemini CLI) can already read and write files and sustain long sessions, yet end-to-end research still fragments across chat tools, IDEs, terminals, and writing environments, and the decisions that make it auditable are rarely preserved. We present Dr. C...

[Read more →]({{ site.baseurl }}/papers/2609.00365/)

---

## [Elite-Weighted Supervised Fine-tuning for Goal-Directed Molecular Optimization]({{ site.baseurl }}/papers/2609.00189/)

**2026-08-31** · Shiyun Wa et al. 

Goal-directed optimization is essential for steering molecular generators to propose candidates with desired properties. However, it is often implemented with policy-gradient reinforcement learning, which requires a generation-trajectory log-probability whose form depends on the model architecture a...

[Read more →]({{ site.baseurl }}/papers/2609.00189/)

---

## [Auditing Harness Tampering in Self-Improving Agents]({{ site.baseurl }}/papers/2609.00069/)

**2026-08-30** · Xing Wang et al. 

Self-improving agents iteratively modify their own harness to push the frontier of their performance. However, such modifications can produce illusory performance gains or compromise integrity constraints such as authorization, provenance, and completeness without genuinely improving capability. We ...

[Read more →]({{ site.baseurl }}/papers/2609.00069/)

---

## [Meta$^n$: Recursive Self-Improvement through Emergent Depth]({{ site.baseurl }}/papers/2608.24735/)

**2026-08-25** · Zae Myung Kim et al. 

Self-improving LLM agents refine answers, not the process that produces those answers. Systems that add a meta-level hold that level fixed, and those that edit themselves must leave part of their own editing machinery untouched to stay stable, capping the meta-depth they realize at roughly two. We p...

[Read more →]({{ site.baseurl }}/papers/2608.24735/)

---

## [Recursive Experiential-Working Memory Evolution for Long-Horizon Agent Harnesses]({{ site.baseurl }}/papers/2608.24876/)

**2026-08-25** · Zhaochen Yu et al. 

Recursive self-improvement (RSI) remains hard in long-horizon tasks, where growing histories obscure the task state and misalign skill invocation. We introduce Recuris, a recursive Experiential-Working Memory architecture for long-horizon agent harnesses, in which Working Memory tracks task progress...

[Read more →]({{ site.baseurl }}/papers/2608.24876/)

---

## [CAFE: Self-Improving Search Agents Need Co-Evolving Feedback]({{ site.baseurl }}/papers/2608.24794/)

**2026-08-25** · Boyang Liu et al. 

Outcome-supervised search agents learn when and how to retrieve evidence, but terminal rewards neither localize intermediate errors nor redirect an ongoing trajectory before those errors compound. Treating corrective feedback as a learned in-trajectory intervention couples the two roles: the agent m...

[Read more →]({{ site.baseurl }}/papers/2608.24794/)

---

## [Auto-Policy, not Auto-Skill: Compiled Agent Skills for the Physical World]({{ site.baseurl }}/papers/2608.25091/)

**2026-08-25** · Zhonghao Zhan et al. 

Self-evolving Skill harnesses (AutoSkills, Hermes Agent) generate more advisory orchestration automatically; their reported gains are efficiency, not safety. This misses the actual gap: a Skill describes how an agent should behave; a Policy decides which behavior is allowed to become an action. Toda...

[Read more →]({{ site.baseurl }}/papers/2608.25091/)

---

## [VideoHarness-RSI: Recursive Harness Self-Improvement for Long-Video Understanding with Frozen Vision-Language Models]({{ site.baseurl }}/papers/2608.24302/)

**2026-08-25** · Guoyang Xu et al. 

Long-video understanding depends critically on how a limited model context is constructed from a much longer video. Existing approaches improve this process through compression, retrieval, memory, and agentic evidence acquisition, but these mechanisms are typically introduced as part of a manually d...

[Read more →]({{ site.baseurl }}/papers/2608.24302/)

---

## [TRACE: A Self-Evolving Skill Bank for Consistent, Limit-Aware LLM Agents]({{ site.baseurl }}/papers/2608.22793/)

**2026-08-24** · Wenhao Wu et al. 

Reliable deployment of LLM agents in user-facing products depends not on raw task-solving ability but on consistency and limit-awareness: behaving the same way across repeated trials, and recognizing when a request cannot, or cannot yet, be safely fulfilled. CAR-bench exposes this reliability gap in...

[Read more →]({{ site.baseurl }}/papers/2608.22793/)

---

## [MediSkill-Evo: Process-Constrained Self-Evolution for Evidence-Grounded Clinical Interaction]({{ site.baseurl }}/papers/2608.23397/)

**2026-08-24** · Ruoyu Wu et al. 

Interactive clinical agents operate under partial observability, so reliable care depends on reaching the correct diagnosis through evidence-grounded, safe interactions. Yet existing agents struggle to convert experience into reusable process knowledge with explicit provenance and authority. To addr...

[Read more →]({{ site.baseurl }}/papers/2608.23397/)

---

## [MolEmb: Multimodal Large Language Models Can Be Strong Molecular Embedding Models]({{ site.baseurl }}/papers/2608.23646/)

**2026-08-24** · Xinjian Zhao et al. 

Molecular embedding models can serve as foundational infrastructure for computational chemistry and drug discovery, where reusable vector representations support property prediction, virtual screening, and retrieval. Most molecular encoders are specialist models built around a single molecular view,...

[Read more →]({{ site.baseurl }}/papers/2608.23646/)

---

## [The Compaction Cliff in Long-Running AI Agent Memory]({{ site.baseurl }}/papers/2608.22752/)

**2026-08-24** · Saber Zerhoudi et al. 

A safety rule and an episodic log compete for the same tokens in an AI agent's context. When the budget overflows, both are summarized at the same rate; only the rule needs exact wording to remain enforceable. On 20 production agent configurations, Claude Code's /compact prompt on Sonnet 4.6 preserv...

[Read more →]({{ site.baseurl }}/papers/2608.22752/)

---

## [GSAR: Goal-State-Anchor Rewards for Mobile GUI Agents with Self-Evolving Data Synthesis]({{ site.baseurl }}/papers/2608.22847/)

**2026-08-24** · Long Zhang et al. 

Vision-Language Models (VLMs) based GUI agents stand to benefit significantly from online reinforcement learning (RL). However, their training is bottlenecked by two fundamental issues: current data synthesis methods for GUI Agents rely on specific environments and struggle to generate diverse data,...

[Read more →]({{ site.baseurl }}/papers/2608.22847/)

---

## [Prime Agent: A Self-Improving RLM Harness]({{ site.baseurl }}/papers/2608.23552/)

**2026-08-24** · Seth Karten et al. 

Language models are sequential processors, but long-horizon agency requires external information and computation beyond model weights and active context. Prime Agent is an open-source harness for long-horizon evaluation and coding-agent workflows. A persistent IPython REPL follows the Recursive Lang...

[Read more →]({{ site.baseurl }}/papers/2608.23552/)

---

## [Physical Agentic AI: An Architecture for Orchestrating a Robot Crew with LLMs]({{ site.baseurl }}/papers/2608.22657/)

**2026-08-23** · Xinyuan Liu et al. 

Agentic AI frameworks interpret open-ended task goals and decompose them into multi-step plans. Richer information about embodiment-specific capabilities, physical preconditions, and cross-robot coordination improves grounding, but does not eliminate infeasible, mistimed, or unsafe physical actions....

[Read more →]({{ site.baseurl }}/papers/2608.22657/)

---

## [Training a Knowledge Base: Supervised Structure Learning for Agent-Curated Document Stores]({{ site.baseurl }}/papers/2608.21829/)

**2026-08-22** · Yu Pan et al. 

Retrieval-augmented generation treats the document store as a frozen input, and the offline pipelines that do build structure over it build it unsupervised -- a whole corpus indexed at uniform effort, with no signal about which structure a question will need. We instead treat the knowledge base as a...

[Read more →]({{ site.baseurl }}/papers/2608.21829/)

---

## [Semantic Reasoning Denoising: Correcting Language Model Reasoning with Semantic Operators]({{ site.baseurl }}/papers/2608.22090/)

**2026-08-22** · Yujiao Yang et al. 

Large language models can produce fluent reasoning traces whose local semantic errors propagate to an incorrect conclusion, while unconstrained self-correction may preserve, amplify, or introduce errors. Existing diffusion language models provide iterative refinement, but usually define noise as tok...

[Read more →]({{ site.baseurl }}/papers/2608.22090/)

---

## [SSE-Bio: A Structured Self-Evolving Agent with Agentic Retrieval Policy for Multi-Hop Biomedical Reasoning]({{ site.baseurl }}/papers/2608.22132/)

**2026-08-22** · Zhaohan Meng et al. 

Biomedical multi-hop question answering (QA) requires models to connect evidence across intermediate entities such as diseases, drugs, proteins, and phenotypes. Existing agents typically rely on static retrieval workflows or coarse-grained prompt rewriting, which can lead to instruction drift when r...

[Read more →]({{ site.baseurl }}/papers/2608.22132/)

---

## [Vis-Poison: Poisoning Visual Knowledge in Multimodal Retrieval-Augmented Generation]({{ site.baseurl }}/papers/2608.20756/)

**2026-08-21** · Rujin Liang et al. 

While multimodal retrieval-augmented generation (RAG) systems increasingly rely on images as external knowledge sources, the introduction of poisoned visual evidence can severely compromise multimodal large language model (MLLM) generation. Unlike prior attacks that rely on altering textual metadata...

[Read more →]({{ site.baseurl }}/papers/2608.20756/)

---

## [An integrated diffusion-weighted imaging processing and interpretation platform for MR-guided radiotherapy]({{ site.baseurl }}/papers/2608.20519/)

**2026-08-20** · Yunxiang Li et al. 

Background: Magnetic resonance imaging-guided linear accelerators (MR-Linacs) allow diffusion-weighted imaging (DWI) to be acquired at every treatment fraction, but converting these low-signal-to-noise-ratio acquisitions into clinical decisions requires both reliable quantitative processing and an i...

[Read more →]({{ site.baseurl }}/papers/2608.20519/)

---

## [Towards general embodied intelligence: integrating large language models, knowledge bases, and reasoning capabilities to build the next generation of AI agents]({{ site.baseurl }}/papers/2608.19794/)

**2026-08-20** · Fujiang Yuan et al. 

The convergence of large language models (LLMs), structured knowledge bases (KBs), and reasoning ability (RA) presents a promising trajectory toward general embodied intelligence (GEI). This paper reviews the evolution of LLM-centered intelligent systems, emphasising their integration with knowledge...

[Read more →]({{ site.baseurl }}/papers/2608.19794/)

---

## [CTIFoundry: An Agent-Native Corpus Scaffold for Cyber Threat Intelligence]({{ site.baseurl }}/papers/2608.18613/)

**2026-08-19** · Yutong Cheng et al. 

Cyber threat intelligence (CTI) is increasingly consumed not by human analysts but by LLM agents that compose multi-step investigations at query time. The harness side of this shift has matured rapidly (planning loops, tool protocols, context management), but the corpus side has not: threat reports ...

[Read more →]({{ site.baseurl }}/papers/2608.18613/)

---

## [From Threat Intelligence to Detection: Knowledge-driven Enrichment and Template-based Rule Grounding for Automated Sigma Rule Generation]({{ site.baseurl }}/papers/2608.19011/)

**2026-08-19** · Sepehr Ghaffarzadegan et al. 

Mechanisms for dynamically converting cyber threat intelligence (CTI) into actionable detection capabilities are necessary due to the rapid evolution of Advanced Persistent Threats (APTs). Sigma rules are an essential part of contemporary threat detection workflows because they offer a platform-inde...

[Read more →]({{ site.baseurl }}/papers/2608.19011/)

---

## [Science Done on a Machine by a Machine: AI Agents in Computational Chemistry]({{ site.baseurl }}/papers/2608.18508/)

**2026-08-19** · Pavlo O. Dral et al. 

We are witnessing an explosion of agentic systems for computational chemistry simulations: from half a dozen in 2024 to a dozen in 2025, and the current number approaches fifty, surveyed in this Perspective as of 8 August 2026. The capabilities of these agentic systems are shifting from assisting in...

[Read more →]({{ site.baseurl }}/papers/2608.18508/)

---

## [SGHA: Evidence-Grounded Research Problem Discovery with Local Language Models]({{ site.baseurl }}/papers/2608.17501/)

**2026-08-18** · Sarvesh Gharat et al. 

Recent efforts toward fully automated AI scientists have demonstrated that language-model agents can generate hypotheses, execute experiments, and draft scientific manuscripts. However, during the early stages of research, when research problems are formulated, these AI scientists often rely heavily...

[Read more →]({{ site.baseurl }}/papers/2608.17501/)

---

## [ALPS: Measuring Valid Creativity in Large Language Models with Mathematical Construction]({{ site.baseurl }}/papers/2608.15979/)

**2026-08-17** · Eric Xie et al. 

Large language models produce outputs presented as discoveries - new proofs, conjectures, or molecules. Whether such an output that appears creative is truly original and effective is hard to establish: open-ended outputs require subjective judgment, the output may replicate something seen in traini...

[Read more →]({{ site.baseurl }}/papers/2608.15979/)

---

## [The Past and Future of AI Scientists]({{ site.baseurl }}/papers/2608.14407/)

**2026-08-14** · Ross D. King et al. 

We present a survey of the past and future of AI Scientists: machines capable of automating science. AI Scientists can originate hypotheses, deduce their consequences, design and execute experiments, interpret their results, and revise their beliefs. Such systems are integrated scientific agents, co...

[Read more →]({{ site.baseurl }}/papers/2608.14407/)

---

## [OmniScientist: An Omni-Modal Omni-Discipline AI Scientist]({{ site.baseurl }}/papers/2608.13558/)

**2026-08-13** · Bobo Li et al. 

Recent advances in foundation models have enabled AI scientists to automate increasingly complete research workflows, from hypothesis generation and code execution to manuscript preparation. Yet workflow coverage alone does not provide access to the full evidence on which scientific discovery depend...

[Read more →]({{ site.baseurl }}/papers/2608.13558/)

---

## [Training AI Scientists to Replicate Research]({{ site.baseurl }}/papers/2608.13331/)

**2026-08-13** · Damon Falck et al. 

The replicability of papers is a cornerstone of scientific knowledge, ensuring the reliability of existing results and providing a base for further experiments. The act of replication typically illuminates details that were previously underspecified, and thus requires similar hypothesis-driven explo...

[Read more →]({{ site.baseurl }}/papers/2608.13331/)

---

## [Multi-Agent Closed-Loop Reasoning for Organic Structure Elucidation from Multimodal Spectra]({{ site.baseurl }}/papers/2608.14720/)

**2026-08-12** · Bingsen Xue et al. 

Following the molecular discovery and synthesis revolutions, scalable automated structure elucidation from routine spectroscopic data remains an outstanding challenge. Despite decades of computational efforts, no existing system achieved reliable reasoning over unseen spectra. Here, we propose MACRO...

[Read more →]({{ site.baseurl }}/papers/2608.14720/)

---

## [AI Scientist Mission Control (AIMC): Visual Analytics for Human Oversight of Autonomous Scientific Discovery]({{ site.baseurl }}/papers/2608.28637/)

**2026-08-10** · Rikathi Pal et al. 

Autonomous scientific discovery systems can generate large numbers of research ideas, experiments, and manuscripts with minimal human intervention. As these systems become increasingly capable, scientists require effective mechanisms to monitor output quality, identify recurring failure modes, under...

[Read more →]({{ site.baseurl }}/papers/2608.28637/)

---

## [Strategy-first synthesis planning for complex natural products]({{ site.baseurl }}/papers/2608.07454/)

**2026-08-07** · Daniel Armstrong et al. 

The total synthesis of a complex molecule is among the most demanding intellectual and experimental feats in chemistry: a chemist must plan many steps ahead for how to assemble simple building blocks into an intricate target, devise backup strategies, and anticipate procedural challenges. It is also...

[Read more →]({{ site.baseurl }}/papers/2608.07454/)

---

## [CAi Copilot: Reducing Operational Workload in Molecular Design through Intent-Driven Agentic Workflows]({{ site.baseurl }}/papers/2608.06961/)

**2026-08-07** · Zhu Wang et al. 

Early-stage molecular design is an iterative process, not just a task of generating molecules. Researchers turn broad goals into design strategies, refine candidates, assess many properties, and gather evidence before synthesis and tests. AI methods can generate molecules, optimize several goals, pr...

[Read more →]({{ site.baseurl }}/papers/2608.06961/)

---

## [CrossAudit: A Git-Native, Cross-Vendor Audit Loop for Agentic Science]({{ site.baseurl }}/papers/2608.28631/)

**2026-08-05** · Zhaohe Dong et al. 

An AI scientist should not grade its own homework. Yet in the systems we examined, the agent that reviews the work usually comes from the same model family as the agent that produced it, or at least from the same vendor. Model evaluators are known to favour their own generations. Whether models trai...

[Read more →]({{ site.baseurl }}/papers/2608.28631/)

---

## [Eigenius: A Typed Knowledge-Graph DBMS with Epistemic Stratification and Institution-Mediated Reasoning]({{ site.baseurl }}/papers/2608.04457/)

**2026-08-05** · Hans-Martin Will et al. 

As "AI Scientists" emerge to drive research via the Model Context Protocol (MCP), systems relying on ephemeral scripts will fail. The sheer scale of stateful, interconnected evidence requires a machine-walkable warranty grounded in a purpose-built database architecture. Eigenius is an open-source, t...

[Read more →]({{ site.baseurl }}/papers/2608.04457/)

---

## [Adversarial Fast-Moving Real-World Domains as Test Beds for Benchmarking AI Scientist Capabilities]({{ site.baseurl }}/papers/2608.03569/)

**2026-08-04** · William Bolton et al. 

Benchmarking the ability of AI scientists to generate novel ideas is notoriously difficult. Existing benchmarks in this field have made progress in evaluating scientific reasoning and research replication, but often rely on synthetic tasks or retrospective targets, which may be confounded by prior e...

[Read more →]({{ site.baseurl }}/papers/2608.03569/)

---

## [A Blind Spot in Alignment: Quantifying Biosecurity Risks in Large Language Models]({{ site.baseurl }}/papers/2608.02684/)

**2026-08-03** · Shu Quan et al. 

Large Language Models (LLMs) are accelerating biological research, yet this same capability poses a critical biosecurity threat: models that assist in protein engineering can equally be prompted to generate predicted toxin-like sequences, potentially lowering the barrier to biological misuse. Curren...

[Read more →]({{ site.baseurl }}/papers/2608.02684/)

---

## [Position: AI Agents in Scientific Teams Should Be Studied as Human-Agent Systems]({{ site.baseurl }}/papers/2608.14667/)

**2026-08-02** · Patrick Emami et al. 

Large language model-based agents are increasingly deployed as collaborators in scientific discovery yet most current work focuses on the autonomous capabilities of "AI Scientists". We argue that this overlooks the social aspects of scientific teamwork, and that studying AI Scientists as human-agent...

[Read more →]({{ site.baseurl }}/papers/2608.14667/)

---

## [Scaling Scientific Discovery Environments for Turn-Level Agentic RL]({{ site.baseurl }}/papers/2607.28990/)

**2026-07-31** · Yucheng Xu et al. 

Large language model agents have shown promising capabilities in data-driven scientific discovery tasks, where an agent interacts with an execution environment and produces a statistical claim. Long-horizon scientific analysis remains constrained by the lack of process supervised environments over r...

[Read more →]({{ site.baseurl }}/papers/2607.28990/)

---

## [Evaluating Agentic Bioinformatics through Function, Evidence, and Validation]({{ site.baseurl }}/papers/2607.27556/)

**2026-07-30** · Phuc Pham et al. 

Large language model agents increasingly plan, execute, and interpret biological analyses, yet fluent responses, successful tool calls, and benchmark performance alone do not establish scientific credibility. Existing reviews primarily organize biological agents by application, architecture, and age...

[Read more →]({{ site.baseurl }}/papers/2607.27556/)

---

## [An AI Scientist that Doesn't Drift: Taste, Structure, and Falsifiable Findings in a Quadruped Navigation Research Loop]({{ site.baseurl }}/papers/2608.07542/)

**2026-07-30** · Yiwen Zhang et al. 

Autonomous research loops driven by large language models can run machine-learning experiments at scale but tend to drift toward local refinements of whichever metric they optimise rather than testing the hypotheses that motivate the experiments. We address this structurally and present an AI Scient...

[Read more →]({{ site.baseurl }}/papers/2608.07542/)

---

## [OmniQEC: discovering practical quantum error-correcting codes by an AI scientist]({{ site.baseurl }}/papers/2607.25865/)

**2026-07-28** · Ge Yan et al. 

Quantum error correction (QEC) is indispensable for scalable fault-tolerant quantum computing. However, discovering QEC codes that remain effective is challenging, as logical performance depends on the interplay between code structure, hardware, syndrome extraction, and decoding, which often impose ...

[Read more →]({{ site.baseurl }}/papers/2607.25865/)

---

## [CausalSmith: A Formally Grounded, Self-Improving Agentic Framework for Automated Research in Causal Inference]({{ site.baseurl }}/papers/2607.22511/)

**2026-07-24** · Jiyuan Tan et al. 

Automating theoretical research is constrained not only by the generation of candidate results, but also by their reliable evaluation. A common approach is to close the research loop with a large language model (LLM) reviewer. However, such reviewers remain empirically unreliable: they may accept fa...

[Read more →]({{ site.baseurl }}/papers/2607.22511/)

---

## [PEARL: Auditable Repair for Scientific Reasoning Graph Extraction]({{ site.baseurl }}/papers/2607.17917/)

**2026-07-20** · Bohan Su et al. 

Scientific Reasoning Graph Extraction (SRGE) aims to recover explicit links among observations, evidence, intermediate claims, and paper-level conclusions. LLMs can produce graph-like scientific explanations, but their outputs often mix malformed syntax, drifting edge labels, incorrectly oriented ro...

[Read more →]({{ site.baseurl }}/papers/2607.17917/)

---

## [Do Language Models Dream of Binding Molecules? Benchmarking LLMs under Spatial Constraints]({{ site.baseurl }}/papers/2607.18144/)

**2026-07-20** · Thomas MacDougall et al. 

Structure-based drug design (SBDD) leverages the 3D structure of protein targets, often complemented by other spatial constraints, to generate candidate binding molecules. While diffusion models have dominated as a leading paradigm for high-quality 3D molecule generation, LLM-based methods are rapid...

[Read more →]({{ site.baseurl }}/papers/2607.18144/)

---

## [SciForge: An AI-Native, Multimodal Workbench for Scientific Discovery]({{ site.baseurl }}/papers/2607.16038/)

**2026-07-17** ·  SciForge Team et al. 

Scientific work increasingly spans heterogeneous artifacts -- papers, code, datasets, scientific file formats, model outputs, figures, manuscripts, and team decisions -- yet general-purpose AI assistants rarely preserve these objects as a coherent, auditable research state. We present SciForge, a mu...

[Read more →]({{ site.baseurl }}/papers/2607.16038/)

---

## [S1-Omni: A Unified Multimodal Reasoning Model for Scientific Understanding, Prediction, and Generation]({{ site.baseurl }}/papers/2607.15686/)

**2026-07-17** · Jiahao Zhao et al. 

We present S1-Omni, a unified multimodal reasoning model for scientific understanding, prediction, and generation. AI for Science (AI4S) has advanced significantly through domain-specific models, tool-augmented LLMs, and scientific language models. However, model capabilities remain highly fragmente...

[Read more →]({{ site.baseurl }}/papers/2607.15686/)

---

## [RetroAgent: Harnessing LLMs to Search Over Structured Memory for Agentic Retrosynthesis Planning]({{ site.baseurl }}/papers/2607.14512/)

**2026-07-16** · Yanqiao Zhu et al. 

Multi-step retrosynthesis planning seeks to decompose a target molecule into commercially available building blocks through a sequence of feasible reactions. The vast combinatorial search space makes this task challenging even for expert chemists. Traditional methods combine tree search with offline...

[Read more →]({{ site.baseurl }}/papers/2607.14512/)

---

## [ReasFlow: Assisting Reasoning-Centric Scientific Discovery in Applied Mathematics via a Knowledge-Based Multi-Agent System]({{ site.baseurl }}/papers/2607.14178/)

**2026-07-15** · Yutong He et al. 

Recent advances in Large Language Models have fueled autonomous AI agents capable of tackling complex scientific tasks, yet existing automated research systems remain predominantly focused on empirically driven domains with quantitative benchmarks, leaving theory-driven discovery, particularly in ma...

[Read more →]({{ site.baseurl }}/papers/2607.14178/)

---

## [From Observation to Insight: Mechanistic World Models and the Quest for Autonomous Discovery]({{ site.baseurl }}/papers/2607.12474/)

**2026-07-14** · Ingmar Posner et al. 

Recent advances in foundation models have transformed AI for Science, enabling remarkably accurate predictive performance across domains ranging from protein folding to weather forecasting. Yet prediction alone does not constitute scientific discovery. Scientific understanding depends on uncovering ...

[Read more →]({{ site.baseurl }}/papers/2607.12474/)

---

## [NVAITC AI Scientist: A Governed End-to-End Research System -- A Hypertension GWAS Case Study]({{ site.baseurl }}/papers/2607.11084/)

**2026-07-13** · Eddie Huang et al. 

Agentic research systems are emerging as a new paradigm for coordinating scientific workflows beyond isolated model inference, code generation, or statistical analysis. However, deployment in institutional biomedical environments requires governed mechanisms for research planning, data access, workf...

[Read more →]({{ site.baseurl }}/papers/2607.11084/)

---

## [TheBioCollection: Unified Pre-Training Scale LLM Corpus for Biology]({{ site.baseurl }}/papers/2607.08803/)

**2026-07-09** · Hyunjin Seo et al. 

The push toward large language models for biology (BioLM) has created a need for training corpora that can endow models with a genuine understanding of biology. However, existing biological resources, such as molecular databases, protein repositories, genomic annotations, single-cell atlases, and pa...

[Read more →]({{ site.baseurl }}/papers/2607.08803/)

---

## [DrugGen 2: A disease-aware language model for enhancing drug discovery]({{ site.baseurl }}/papers/2607.08404/)

**2026-07-09** · Ali Motahharynia et al. 

Current computational approaches for drug design typically focus on generating molecules conditioned on specific targets or general molecular properties, often neglecting the influence of disease context on target behavior and therapeutic outcomes. To address this gap, we introduce DrugGen-2, a nove...

[Read more →]({{ site.baseurl }}/papers/2607.08404/)

---

## [Accurate, Interdisciplinary and Transparent Structure-property Understanding with Deep Native Structural Reasoning]({{ site.baseurl }}/papers/2607.07708/)

**2026-07-08** · Chen Tang et al. 

Structure-property relationships are foundational to biology, chemistry and materials science, where function, reactivity and physical response emerge from spatial, chemical and periodic organization. Mechanistically explaining these relationships requires interpreting structural evidence through sc...

[Read more →]({{ site.baseurl }}/papers/2607.07708/)

---

## [URSA: Chemistry-Aware Benchmark for Utilitarian Retrosynthesis Assessment]({{ site.baseurl }}/papers/2607.04688/)

**2026-07-06** · Bogdan Zagribelnyy et al. 

Synthesis planning aiming to find pathways of reactions for a target molecule is one of the most important and challenging tasks in drug discovery. Recent progress has produced both specialized deep-learning retrosynthesis systems and general-purpose large language models, but objective comparison r...

[Read more →]({{ site.baseurl }}/papers/2607.04688/)

---

## [Agentic generation of verifiable rules for deterministic, self-expanding reaction classification]({{ site.baseurl }}/papers/2607.01061/)

**2026-07-01** · Daniel Armstrong et al. 

Computer-assisted synthesis planning breaks target molecules into accessible precursors using large libraries of reaction rules that assign each transformation a deterministic, interpretable label. But chemistry is long-tailed, making manual encoding intractable, and existing tools rely on fixed rul...

[Read more →]({{ site.baseurl }}/papers/2607.01061/)

---

## [Active-GRPO: Adaptive Imitation and Self-Improving Reasoning for Molecular Optimization]({{ site.baseurl }}/papers/2607.00531/)

**2026-07-01** · Xuefeng Liu et al. 

Scientific reasoning is an increasingly important capability of large language models, yet improving the robustness and efficiency of training such reasoning remains a key open challenge. We study this problem in instruction-based molecular optimization, where answer-only supervised fine-tuning (SFT...

[Read more →]({{ site.baseurl }}/papers/2607.00531/)

---

## [Towards Generalizable and Evidential Nuclear Magnetic Resonance-Based Molecular Structure Elucidation via Large Language Model Agent]({{ site.baseurl }}/papers/2606.29776/)

**2026-06-29** · Zheng Fang et al. 

Nuclear Magnetic Resonance (NMR) spectroscopy is the gold standard for molecular structure elucidation, yet interpreting complex spectra for unknown molecules remains a bottleneck reliant on human expertise. While artificial intelligence has advanced this field, current methods face a critical trade...

[Read more →]({{ site.baseurl }}/papers/2606.29776/)

---

## [Two-Stage Fine-Tuning for Protein Sequence Generation with Targeted Amino-Acid Composition]({{ site.baseurl }}/papers/2606.27939/)

**2026-06-26** · Violeta Basten-Romero et al. 

Protein language models are standard priors for biological sequence generation, but steering them toward explicit distributional design targets remains largely unexplored. We study a constrained protein generation problem in which sequences must match a desired amino-acid (AA) composition profile wh...

[Read more →]({{ site.baseurl }}/papers/2606.27939/)

---

## [SP-Mind: An Autonomous Reasoning Agent for Spatial Proteomics Analysis]({{ site.baseurl }}/papers/2606.24235/)

**2026-06-23** · Yucheng Yuan et al. 

Spatial proteomics enables single-cell-resolution characterization of protein expression within tissue architecture, playing a critical role in understanding tumor microenvironments and guiding precision medicine. However, current analysis workflows remain fragmented, requiring expert manual orchest...

[Read more →]({{ site.baseurl }}/papers/2606.24235/)

---

## [Uncertainty-aware reinforcement learning for chemical language models]({{ site.baseurl }}/papers/2606.24990/)

**2026-06-23** · Borja Medina et al. 

Reinforcement Learning (RL) has become a powerful paradigm for de novo molecular design, enabling Chemical Language Models (CLMs) to navigate and explore the chemical space while optimizing specific desired properties. However, the existing RL frameworks treat all scoring functions as deterministic ...

[Read more →]({{ site.baseurl }}/papers/2606.24990/)

---

