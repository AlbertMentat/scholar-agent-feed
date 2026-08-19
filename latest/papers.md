# 📑 论文索引 - 2026-08-19

共 358 篇论文

---

### [1] CBX-Bench: A Human-Aligned MLLM Council for Benchmarking Concept Bottleneck Model Explanations

**链接**: https://arxiv.org/abs/2608.15404
**作者**: Yusuf Meric Karadag, Gulay Oklan, Seref Baris Cagliyan, Umut Ozdemir, Emre Akbas
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Concept Bottleneck Models (CBMs) are designed to make visual classification interpretable by expressing predictions through human-understandable concepts. Although interpretability is the central motivation for CBMs, they are still largely evaluated as predictive models by downstream classification accuracy, supplemented by isolated qualitative examples. This highlights a pressing need for quantitative measures, a challenge complicated by the infeasibility of ground-truth concept annotation at scale and the open nature of concept lists due to a lack of consensus. To fill this gap, we develop a multimodal large language model (MLLM) council that, given an image and its CBM explanation, produces an explanation quality score. To ground and validate the council, we first conduct a human study to establish a ground-truth reference for CBM explanation quality: for an image, annotators compare explanations from two of LF-CBM, VLG-CBM, and CBM-Suite and choose the more useful one, or mark them

---

### [2] Remote-Sensing City Layout Extraction with MLLM

**链接**: https://arxiv.org/abs/2608.16484
**作者**: Zigan Zhou, Kai Li, Yupeng Deng
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote-sensing systems usually describe urban content with detection boxes, semantic masks, or vector boundaries. Such outputs locate classes and support image-plane scoring, yet they do not by themselves constitute an executable layout that retains object identities, typed relations, topology, and regeneration rules. Code-as-City instead casts urban-layout extraction from a single top-down image as constrained code generation with a multimodal large language model (MLLM). An image model first produces an aligned five-class semantic layout prior. Three ordered MLLM passes use the image and this prior to recover roads, land-cover regions and relations, and buildings. Deterministic normalization converts the accumulated records into a city graph and a restricted layout program. Executing the program creates a renderable 3D city layout and an orthographic semantic projection over shared geometry. The projection admits pixel-level comparison with remote-sensing masks, while named objects, 

---

### [3] MLLM-Guided Semantic Correction for Text-to-Video Generation

**链接**: https://arxiv.org/abs/2608.16513
**作者**: Junhao Chen, Zheqi Lv, Keting Yin, Shengyu Zhang, Zhou Zhao, Feiyang Chen 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in diffusion models and Transformer architectures have led to significant progress in text-to-video generation. However, these models often suffer from semantic errors such as missing objects, incorrect attributes, or mismatched actions. Although some semantic correction methods perform optimization before sampling or refinement after sampling, how to detect and correct semantic deviations during the video generation process remains underexplored. In this paper, we introduce a training-free, interpretable mid-generation correction framework that integrates multimodal large language model (MLLM) feedback directly into the diffusion sampling loop. Our framework achieves diffusion trajectory correction by injecting semantic evaluation signals during video synthesis, enabling the model to optimize the generated content through continuous self-reflection. We propose two key modules: a Semantic Assessment Supervisor that generates intermediate preview frames for semantic eval

---

### [4] LAPF: LLM-Agent-Based Path Finder Using the UAVScenes Dataset

**链接**: https://arxiv.org/abs/2608.15175
**作者**: Yousef Emami, Mohammadhossein Homaei, Hao Zhou, Miguel Guti\'errez Gait\'an, Atefeh Hajijamali Arani, Rui Zhang
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Uncrewed aerial vehicles (UAVs) are increasingly deployed for autonomous navigation in complex outdoor environments, where dynamic conditions and mission requirements require intelligent adaptive decision-making. Existing optimization-based, Machine Learning (ML), and Reinforcement Learning (RL) approaches often rely on predefined models or task-specific training, limiting their generalization and adaptability in uncertain scenarios. Recent Large Language Model (LLM)-assisted approaches offer promising reasoning capabilities but remain constrained by limited agentic functionality, including insufficient memory, planning, and tool interaction mechanisms.This paper proposes an LLM-Agent-Based Path Finder (LAPF) framework for autonomous UAV navigation in town-scale outdoor environments. LAPF extends LLM-assisted navigation by integrating perception, memory, planning, and action modules into a closed-loop cognitive architecture. The proposed agent leverages prior navigation experiences, pe

---

### [5] Chain-of-Experience for Continual LLM Improvement

**链接**: https://arxiv.org/abs/2608.18027
**作者**: Haoqin Tu, Yunhao Fang, Yizhong Wang, Cihang Xie, Shen Yan
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans continuously learn from experience, whereas conventional large language model (LLM) evaluations ignore the models' ability to improve through inference-time interaction. In this paper, we study how LLMs learn from iterative experience at test time, a setting we refer to as Chain-of-Experience (CoE), where models accumulate experiential traces through iterative interactions with self or environmental feedback to form a continual improvement loop beyond zero-shot inference. We instantiate CoE with diverse feedback mechanisms, including model self-feedback and environmental signals such as correctness or public coding test pass rates, and evaluate across math, coding, and knowledge domains using 8 LLMs, including GPT-5, Gemini-2.5 Pro, Claude-4.5 Sonnet. Our study shows that leveraging iterative experience consistently outperforms feedback-free baselines, achieving substantial gains with self feedback alone, alongside a 5.6% overall improvement and 19% lower API cost across tasks a

---

### [6] From "What-If" to "What-Is": Counterfactual Thinking-Inspired Semantic Alignment for Visual Brain Decoding

**链接**: https://arxiv.org/abs/2608.15163
**作者**: Kaitao Yan, Chi Liu, Congcong Zhu, Huajie Chen, Gengshen Wu, Minghao Wang 等 (8 人)
**来源**: cs.CV cs.HC
**匹配关键词**: LLM, Brain Decoding
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual brain decoding reconstructs visual content perceived by a person from neural measurements such as fMRI, providing a computational approach to studying how visual information is represented in the brain. Recent multimodal representations and diffusion priors have improved reconstruction realism. However, visually plausible reconstructions may contain incorrect objects, attributes, or relations because a strong generative prior can complete content not sufficiently specified by the decoded representation. Conventional reconstruction metrics mainly assess the final image and may therefore obscure such semantic errors. We propose ConceptAlign, a counterfactual semantic alignment framework for visual brain decoding. ConceptAlign pools decoded visual tokens and projects them into a frozen text-embedding space, aligning the representation with the ground-truth caption while separating it from scene-preserving near-miss alternatives. Generated offline by an LLM, these alternatives modif

---

### [7] HaReCAP: Habitual-action Grounding for Recursive Large Language Model Agents

**链接**: https://arxiv.org/abs/2608.16447
**作者**: Shen Liu, Zhenguo Xu, Shaopu Wang, Yike Gao, Chunlei Wang
**来源**: cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon embodied tasks require LLM agents to iteratively decompose high-level goals, revise plans in response to environmental feedback, and ground leaf-level subgoals into valid executable actions. Recursive context-management methods such as ReCAP improve planning stability through multi-level task decomposition and parent-node refinement, but still repeatedly invoke the LLM at leaf nodes to ground atomic subtasks into exact valid actions. We refer to this final grounding step as last-mile grounding redundancy, which accumulates into substantial LLM-call and token overhead during long-horizon execution. To mitigate this issue, we propose HaReCAP (Habitual-action Grounded ReCAP), a low-intrusion leaf grounding extension for ReCAP. HaReCAP extracts frequent leaf decisions from successful trajectories and compiles them offline into auditable and abstainable one-step leaf-reflex rules. At runtime, it skips the leaf LLM call only when a rule can uniquely determine a legal action in t

---

### [8] PL-Guard: Probabilistic Logic Reasoning for LLM Guardrails

**链接**: https://arxiv.org/abs/2608.15673
**作者**: Satchit Chatterji, Shihan Wang, Giovanni Sileno, Erman Acar
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model guardrails can be viewed as policy-consistency problems: a system must determine which policy-relevant facts hold in a prompt-response pair and what those facts imply under a given policy. Common approaches, including policy prompting and LLM-as-a-judge pipelines, often overlap the tasks of semantic grounding and policy reasoning: the model both interprets the prompt-response pair and reasons about whether a policy has been violated. This can lead to unsafe compliance with harmful prompts, or refusals to assist benign ones. To separate grounding and reasoning roles, we propose PL-Guard, a neurosymbolic guardrail architecture. Using a symbolic policy interface consisting of predicates and ProbLog rules, a local LLM grounds prompt-response pairs into predicate probabilities using renormalized True/False token scores, while ProbLog performs explicit probabilistic rule inference over the symbolic policy. On the XSTest benchmark, an offline Qwen-based evaluator finds th

---

### [9] Decomposition Attacks Across Unlinkable Identities: Limits of Stateful Defenses for LLM Services

**链接**: https://arxiv.org/abs/2608.17445
**作者**: Bowen Sun, Zhengyue Zhao, Xiaogeng Liu, Yinzhi Cao, and Chaowei Xiao
**来源**: cs.CR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most large language model services use stateless defenses, which judge only the current request, to refuse harmful tasks. Decomposition attacks exploit this limitation by splitting a harmful task into individually permissible requests and combining their answers. Defending against them therefore requires a stateful monitor that considers requests together. If it can group all requests for one attacker task, it can stop the attack. However, attackers can use unlinkable identities and combine answers elsewhere, leaving no reliable grouping signal. We ask whether decomposition attacks can still be stopped under this setting. For a fixed attack strategy without retries, we prove that the achievable security and utility tradeoff depends entirely on how benign requests for the same capabilities are grouped. Persistent, recognizable groups permit a useful defense; fresh, indistinguishable groups do not. When attackers can retry and learn from Allow/Block decisions, this useful operating point

---

### [10] From Sequence to Structure: Relational Uncertainty Propagation for LLM Agents

**链接**: https://arxiv.org/abs/2608.16002
**作者**: Zhengzhao Ma. Boxi Cao, Yaojie Lu, Hongyu Lin, Xianpei Han, Le Sun
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable uncertainty quantification (UQ) is essential for deploying large language model (LLM) agents in complex interactive environments. Existing UQ methods largely rely on local signals, such as token probabilities, predictive entropy, or per-step confidence, and therefore overlook the long-range dependencies through which errors accumulate across an execution trajectory. As a result, they may fail to identify agent failures whose causes originate several reasoning or interaction steps before the final answer. We propose RUPA (Relational Uncertainty Propagation for Agents), a trajectory-level UQ framework for LLM agents. RUPA represents an execution history as a directed trajectory graph in which reasoning states, tool interactions, and environment feedback are nodes connected by temporal and semantic dependency edges. It then propagates uncertainty over this graph to capture how execution risk accumulates and transfers across interaction steps. The propagated signal is combined wit

---

### [11] Beyond Binary Priorities: Multi-Tier SLA Scheduling for Large Language Model Serving

**链接**: https://arxiv.org/abs/2608.16336
**作者**: Anders Vestrum, Arya Raeesi, Hanna Roed
**来源**: cs.AR cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM serving deployments must simultaneously satisfy heterogeneous service-level objectives (SLOs) across a diverse population of user tiers, ranging from latency-critical API calls to background batch processing. Llumnix introduced a dynamic, migration-capable multi-instance scheduler for LLM inference that achieves load balancing, defragmentation, prioritization, and auto-scaling through a unified "freeness" metric. However, Llumnix's priority model is restricted to two levels (high and normal), an abstraction too coarse to express the richer SLA classes common in production deployments. In this work, we extend Llumnix's priority model to support an arbitrary number of tiers and evaluate the effects of this extension under three realistic priority distributions (uniform, Gaussian, enterprise) using Vidur, a high-fidelity LLM inference simulator. We implement per-tier headroom with exponential decay, tier-aware dispatch ordering, and the full Llumnix migration pipeline inside Vi

---

### [12] What Structured Tool Interfaces Do and Do Not Provide for LLM -Based SWAT+ Calibration

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1364815226002896&hl=zh-CN&sa=X&d=15998301975185491468&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-wZ7KmqruABHm-8_rVsebrX&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: E Park, J Park, T Kim, A Jin - Environmental Modelling & Software, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To our knowledge, no prior study has evaluated agent-mediated LLM operation of a physically-… Here we present a large language model ( LLM ) agent constrained to operate SWAT+ … Our contribution is not the coupling of an LLM to a simulator per

---

### [13] Belayer: Efficient Fault Tolerance for LLM Agentic RL Training

**链接**: https://arxiv.org/abs/2608.14635
**作者**: Jiecheng Zhou, Qinghao Hu, Peng Sun, Xingcheng Zhang, and Weiming Zhang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly trained with reinforcement learning in long-horizon, sandboxed environments. Unlike conventional RL, agentic RL couples GPU-intensive rollout engines with stateful environment containers whose actions may produce visible side effects, such as file edits, command execution, and dependency installation. A single trajectory can span many rounds of gen- eration and environment interaction, so a component failure can discard completed work or expose the model to an environment state that is inconsistent with its context. However, existing systems lack efficient and correct recovery mechanisms for this distributed execution model. This paper presents Belayer, an efficient fault-tolerant system for LLM agentic RL training. Belayer handles failures in both rollout engines and environment execution while targeting low failure-free overhead. For scoped worker-local rollout failures, Belayer equips each pre-initialized shadow worker with a select

---

### [14] Agent Gym: A Framework for Continuous Evaluation and Evolution of LLM Agents Through Human-in-the-Loop Feedback

**链接**: https://arxiv.org/abs/2608.15591
**作者**: Pouya Ghiasnezhad Omran, Michael Zimmermann, Duncan Cambridge, Ashmita Kapoor, Tanya Dixit
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents deployed in production environments face a fundamental tension: the agent's behavior is frozen at deployment time, while the business rules and edge cases it must handle continue to evolve. Existing approaches address agent construction and one-time evaluation but provide no structured mechanism for continuous post-deployment behavioral correction without modifying the agent's source code. Most of the approaches offered in the market, require intense collection of logs and traces, and re-examining the agent design by the engineering team, a process which is heavy, long and negates the economical value of agentic transformation. We introduce Agent Gym, a modular, domain-agnostic framework that wraps any existing LLM-based agent in a continuous evaluation-and-evolution loop. The framework provides six composable capabilities --- Act, Evaluate, Investigate, Correct, Learn, and Observe --- organized across three architectural zones: a constitution layer th

---

### [15] ReForge: Keeping ABR Algorithms Never Finished with Verified Large Language Model Edits

**链接**: https://arxiv.org/abs/2608.15138
**作者**: Zhiqiang He and Zhi Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing an ABR algorithm for one network scenario takes an engineer months, and large language models now do this work in hours, matching or beating hand-built designs. But either way, the design fits only the world visible at its birth, and fails on the world that arrives after. We ask whether an ABR algorithm can keep pace with the world, redesigned in minutes as each scenario arrives, with every change proven harmless to every scenario already served. In this work, we propose ReForge, a continual heuristic learning framework that adapts to continuously changing scenarios. ReForge runs that routine with a large language model (LLM) in the loop. Each round the LLM reads where the current design falls short and proposes one small edit, and a replay over every network served so far decides. Specifically, what it edits is a single page of fuzzy rules that routes every decision to one of a frozen pool of pre-trained policies. The LLM writes the first page from measurements alone, then k

---

### [16] Pallas: A Proactive KV Cache Migration Framework for LLM Inference in AI-RAN

**链接**: https://arxiv.org/abs/2608.16477
**作者**: Tianhang Ding, Jianchun Liu, Hongli Xu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-RAN brings large language model (LLM) serving close to mobile users, but cellular handover can separate an active request from its inference state: the user attaches to a target base station (gNB) while the large and growing key-value (KV) cache remains at the source. Retaining inference at the source preserves service continuity but persistently increases inter-token latency (ITL), whereas recovering the state at the target restores serving locality but requires KV-cache transfer, recomputation, or a combination of both only after handover, directly prolonging service interruption time (SIT). This work presents Pallas, a \textit{proactive} KV-cache migration framework that prepares the inference state at the predicted target before handover, in parallel with ongoing source-side inference and token delivery. At the preparation trigger, Pallas partitions the token sequence into a stable historical prefix and an evolving suffix. The target reconstructs the prefix through local prefill

---

### [17] QUMem: Personalized Memory for Query-Conditioned User-State Inference in LLM Agents

**链接**: https://arxiv.org/abs/2608.16168
**作者**: Heng Wang, Yifei Li, Lingling Zhang, Pengyu Li, Xinyu Che, Xinyu Zhang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use external memory systems to support personalization by drawing on long and evolving interaction histories, in which user preferences may be distributed across time, change with context, and conflict with earlier evidence. However, existing systems face three limitations: fixed-turn, fixed-token, or session-based boundaries can mix unrelated dialogue or split an event from its causes, decisions, and outcomes; storing multiple pieces of user information from the same interaction as a single memory binds together items that serve different functions and should be independently retrievable; and treating the current task as a single top-$k$ retrieval query can return fragments that are individually relevant but fail to jointly capture preference evolution, temporal validity, and contextual applicability. We introduce \textsc{QUMem}, a structured memory framework for query-conditioned user-state inference. \textsc{QUMem} first segments intera

---

### [18] TRCA: Transition-wise Rubric Credit Assignment for Long-horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.16156
**作者**: Huan Zhang, Mingju Chen, Dongxu Zhou, Can Lv, Heng Chang, Sen Cui 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon large language model (LLM) agents are typically optimized with sparse terminal outcomes, making fine-grained credit assignment across multi-step interactions difficult. Existing approaches either rely on process evaluators, which incur annotation and inference costs, or derive step-level credit from successful trajectories. However, successful trajectories are extremely scarce during early-stage reinforcement learning, substantially weakening anchor-based methods. We propose Transition-wise Rubric Credit Assignment (TRCA), which derives step-level supervision directly from action-induced transitions without learned evaluators or successful anchors. TRCA evaluates each transition using Evidence, Execution, and Invalidity rubrics to capture task-relevant information acquisition, valid task execution, and invalid or regressive behavior. From these judgments, Foundational Rubric Reward measures local transition quality, while Breakthrough Rubric Reward tracks newly covered Evi

---

### [19] TwinGridShield: Consequence-Aware Runtime Authorization for LLM Grid-Agent Actions

**链接**: https://arxiv.org/abs/2608.15391
**作者**: Md Fazley Rafy
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-assisted energy-management tools can translate natural-language context into structured grid commands, but syntactic validity does not imply physical admissibility. This paper presents TwinGridShield, a model-independent runtime authorization layer that evaluates each proposed action in a deterministic network twin before release. The prototype checks connectivity, branch-flow, generator, and load-shedding invariants and records each decision in a hash-chained log. A controlled IEEE 14-bus study evaluates single-step switching, redispatch, and load-shedding actions using DC power flow and experimentally assigned branch ratings. In the matched-model experiment, a stochastic proposal source configured to select an unsafe action with probability p=0.84 produced 421 unsafe proposals in 500 attacked-condition trials, a realized rate of 84.2%. This value characterizes the configured surrogate and is not an empirical measurement of LLM prompt-injection susceptibilit

---

### [20] SKILL: Self-correcting Knowledge-guided Iterative Large Language Model Agent for Logic Optimization

**链接**: https://arxiv.org/abs/2608.14579
**作者**: Rui Yang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logic synthesis optimization poses significant challenges due to exponentially growing search spaces, sparse reward signals, and diverse logic structures. Traditional expert-designed flows lack adaptability, while reinforcement learning (RL) methods often suffer from low sample efficiency and limited interpretability. We introduce SKILL, a Self-correcting Knowledge-guided Iterative Large Language Model Agent that unifies multi-agent LLM reasoning and RL-based environment interaction for automated synthesis optimization. SKILL coordinates three specialized LLMs: GPT-4o for strategic planning, Claude Sonnet 4 for detailed reasoning, and Gemini 2.5 Pro for efficient analysis with a PPO-based RL agent that learns actionable policies through direct interaction with synthesis tools. A novel self-correcting module monitors environment feedback (PDA metrics), detects suboptimal behaviors, and invokes LLM-guided recovery strategies. Evaluations on IWLS, OpenCores, and EPFL benchmarks show SKILL

---

### [21] Large Language Model Assisted Operational Monitoring for Battery Energy Storage System Integrated Power Distribution Networks

**链接**: https://arxiv.org/abs/2608.15396
**作者**: Azmeer Akhtar, Md Fazley Rafy, and Anurag K. Srivastava
**来源**: cs.AI cs.CL cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Battery energy storage systems (BESS) are increasingly used in distribution networks for voltage regulation and demand response, which increases the volume and complexity of operational telemetry available to grid operators. This paper presents an AI-enabled monitoring framework that connects a large language model (LLM) interface with a structured telemetry database for BESS-integrated distribution system analysis. Operator questions are submitted in natural language and translated into validated SQL queries using predefined database schema information and approved KPI views. Retrieved measurements, including bus voltages, state of charge, active power, and reactive power, are evaluated against engineering constraints for voltage limits, BESS operation, and demand response tracking. The framework is validated using hardware-in-the-loop co-simulation data from a BESS-equipped distribution feeder operating under reactive power-based voltage control and price-driven demand response. Case

---

### [22] Beyond Direct Access: Resource Hijacking in LLM Agents

**链接**: https://arxiv.org/abs/2608.15108
**作者**: Puyu Zeng, Qibing Ren
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly connected to high-value resources such as computing infrastructure, credentials, usage budgets, identities, private knowledge, communication channels, and organizational workflows. Existing agent security research mainly studies attacks on instructions, data, and tool behaviors, while high-value resources accessible to agents have received much less attention as direct attack targets. We are the first to identify and systematically study agent resource hijacking, a security blind spot in which attackers induce agents to invoke, consume, transfer, or control high-value resources for their own goals without directly obtaining those resources or their credentials. To study this threat, we introduce ResourceHijackBench together with an automated pipeline for generating resource hijacking cases. We organize high-value agent resources into six categories and construct 300 attack scenarios with 900 attack prompts. Each case runs in an isolated loca

---

### [23] WIP: LLM Odyssey: A Game-Based Platform for Teaching LLM Engineering Concepts

**链接**: https://arxiv.org/abs/2608.16924
**作者**: Priyamvada Tripathi
**来源**: cs.CY cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work-in-progress (WIP) innovative practice category paper presents LLM Odyssey, an open source, browser-based serious gaming platform comprising 13 interactive games for teaching Large Language Model (LLM) engineering concepts. Topics such as tokenization, transformer architecture, prompt engineering, retrieval augmented generation (RAG), and production deployment are underrepresented in computer science curricula. Existing interactive tools address individual concepts but lack pedagogical scaffolding or structured learning pathways. LLM Odyssey addresses this gap through three learning tiers aligned with Bloom's revised taxonomy: Cognitive Core (7 foundational games), Systems Forge (5 production engineering games), and Foundry Arena (capstone challenges). Each game incorporates five pedagogical strategies drawn from the literature: immediate formative feedback, scaffolded hints grounded in the Zone of Proximal Development, progressive difficulty informed by flow theory, worked ex

---

### [24] WARA: Toward Automated Wireless Optimization Research with Closed-Loop LLM Agents

**链接**: https://arxiv.org/abs/2608.14573
**作者**: Yuan Guo, Yilong Chen, Chao Hu, Xianghao Yu, Liang Hong, and Jie Xu
**来源**: cs.NI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly capable of tool use, code execution, artifact inspection, and iterative revision, creating new opportunities for automating scientific and engineering research. To the best of our knowledge, this paper presents the first end-to-end autoresearch framework for the wireless domain, with a focus on wireless resource allocation optimization. We propose the Wireless AutoResearch Agent (WARA), a closed-loop multi-agent system for automated wireless optimization research. Given only an initial topic, WARA decomposes the workflow into three phases: research gap identification and problem proposal, wireless optimization modeling, algorithm design and experimentation, and research deliverable construction. Across these phases, WARA uses artifact-mediated control: upstream artifacts are consumed as inputs, structured outputs are stored for downstream use, and controller-managed gates validate consistency among models, algorithms, experiments, and 

---

### [25] What Aggregate Scores Miss: Measuring Item-Level Regressions in Commercial LLM API Migrations

**链接**: https://arxiv.org/abs/2608.17719
**作者**: Xiaonan Xu and Wenjing Wu
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context: Software systems that depend on commercial large language model APIs must migrate to successor versions when vendors deprecate older models. Migration decisions typically rely on aggregate benchmark scores, which compress heterogeneous item-level behaviour into a single net figure. Objective: We measure what that compression conceals. Method: On three pairwise upgrades in the GPT-5.4 to GPT-5.6 Sol product sequence, we query 900 public benchmark items (graduate-level knowledge, olympiad mathematics, instruction following) 50 times per item per model, classify each item as reliably improved, reliably regressed, practically equivalent, or inconclusive under false-discovery-rate control and a practical-significance threshold, and calibrate the results against a label-permutation null. Results: Across all nine migration-benchmark cells, reliable improvements and reliable regressions coexist. Edges with aggregate gains of up to 7.3 percentage points contain up to 8.3% reliably regr

---

### [26] AeroCopilotBench: A Two-Tier Benchmark for Evaluating LLM Agents as Aviation Copilots in an Interactive Virtual Cockpit Environment

**链接**: https://arxiv.org/abs/2608.16349
**作者**: Yuchen Yuan, Zhenghuang Wu, Yuangan Li, Liang Ma, Ke Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents may assist flight crews with complex decisions and task execution, but existing aviation evaluations centered on static knowledge do not support systematic testing of procedural execution and safety compliance in interactive environments. This paper presents the AeroCopilot Operational Environment (ACOE), a reproducible interactive virtual-cockpit test environment, and AeroCopilotBench, a two-tier aviation agent evaluation benchmark. Tier-1 evaluates aviation knowledge using 1,200 multiple-choice questions, while Tier-2 comprises 73 emergency and abnormal tasks derived from the manufacturers' Pilot's Operating Handbooks (POHs) and instantiated in ACOE. ACOE converts natural-language procedures into executable state transitions, final-state goal conditions, and hard safety constraints, enabling models to interpret cockpit state, diagnose faults, and operate aircraft systems through standardized tool interfaces. We establish a safety-gated evaluation fra

---

### [27] Representation Signatures and Risk-Feedback Alignment in LLM Trading Agents

**链接**: https://arxiv.org/abs/2605.28850
**作者**: Weicheng Xue
**来源**: cs.LG q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] BRA-Audit: Budgeted Runtime Auditing for LLM Multi-Agent Systems via Cumulative-Exposure Audit-Point Placement

**链接**: https://arxiv.org/abs/2608.14668
**作者**: Kaixiang Wang, Yidan Lin, Jiong Lou, Jie Li
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (LLM-MAS) solve complex tasks through specialized collaboration, but inter-agent dependencies can propagate hallucinated or malicious outputs into system-level failures. Auditor agents mitigate these risks, yet existing strategies face an efficiency dilemma: end-only auditing reviews long trajectories and final outputs, potentially weakening audit effectiveness and enlarging rollback scope, while auditing every agent each round improves detection and localization at high token cost. How can guard performance be preserved while minimizing token cost? To address this problem, we propose BRA-Audit, a budget-aware runtime auditing framework that models MAS execution as a dynamic dependency graph and formulates audit scheduling as audit-point placement under a fixed audit-call budget to minimize cumulative unchecked exposure. Its greedy scheduler prioritizes influential and long-unaudited regions, while trusted audit points enable localized recovery. Across str

---

### [29] PWLR: Pairwise Witness Local Rejection for Boundary-Aware Out-of-Distribution Detection

**链接**: https://arxiv.org/abs/2608.15802
**作者**: Chengyao Jia, Ruixuan Wang
**来源**: cs.CV cs.LG
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Out-of-distribution (OOD) detection remains challenging for image classifiers, especially when near-OOD samples lie close to in-distribution (ID) class boundaries. Recent vision-language detectors improve OOD detection through class semantics, local prompting, or LLM-generated outlier concepts, but seldom use language as explicit boundary evidence between confusing ID classes. We propose Pairwise Witness Local Rejection (PWLR), which uses an MLLM offline to describe visible local cues that favor one ID class over a specific rival class. These cue phrases are then screened with ID-only data under a frozen vision-language backbone, so that only reliable local verifiers are kept. At inference, PWLR first retains a small set of globally plausible classes, then checks whether any of them is locally supported against its most relevant rivals, and finally combines this pairwise local evidence with the global class score through calibration. Experiments on ImageNet-100 far-OOD, cleaner/challen

---

### [30] LLM-based Framework for Generating and Verifying Parallel DEVS Statecharts

**链接**: https://arxiv.org/abs/2608.14956
**作者**: Vamsi Krishna Vasa, Hessam S. Sarjoughian, Edward J. Yellig
**来源**: cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The development of models demands sound modeling and simulation knowledge as well as domain knowledge. Every model should accurately represent a system's dynamics and be verifiable. Toward this objective, this research introduces an agentic PDEVS-LLM framework to assist human modelers in generating and verifying PDEVS statecharts for behavior modeling of atomic Parallel Discrete Event System Specification (PDEVS) models. The framework supports (re)generating plausible facts from a system description prompt using the agentic LLM used for generating plausible facts. Inconsistencies in plausible facts lead to incorrect PDEVS statecharts having logical structure and behavioral inaccuracies. A controlled-correction mechanism is developed to verify the logical consistency of the plausible facts. The agentic LLM is used to generate key behavioral conditions from the system description prompt. The plausible facts are then verified against the behavioral conditions using propositional logic ent

---

### [31] LlamaRec-LKG-RAG: A Single-Pass, Learnable Knowledge Graph-RAG Framework for LLM-Based Ranking

**链接**: https://arxiv.org/abs/2506.07449
**作者**: Vahid Azizi, Fatemeh Koochaki
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] LLM-Only PDDL Domain Repair with Open-Weight Models

**链接**: https://arxiv.org/abs/2608.17341
**作者**: Nader Karimi Bavandpour, Pascal Bercher
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI planning is concerned with finding a sequence of actions that achieves a specified goal. It relies on explicit models of the world, commonly represented in the Planning Domain Definition Language (PDDL). An active line of research investigates how errors in such models can be detected and repaired. For example, users may provide positive test plans that are solutions, and negative test plans that fail during execution. Automated repair methods then modify the PDDL model to satisfy these constraints. In this paper, we evaluate the ability of recent open-weight large language models to perform this repair task using an LLM-only approach. Our experiments show that the symbolic baseline achieves an $F_1$ score of $.49$, while the best-performing LLM reaches $.87$ with high reasoning effort, an absolute improvement of $.38$. However, that setting has a mean test pass rate of only $.82$, falling to $.06$ on the Thoughtful domain; even the best setting that includes the test traces reaches

---

### [33] MistyPilot: Enabling Social-Robot Control through Multi-Agent LLM Skill Orchestration

**链接**: https://arxiv.org/abs/2608.15549
**作者**: Xiao Wang, Lu Dong, Ifeoma Nwogu, Srirangaraj Setlur, Venu Govindaraju
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programming small social robots from natural-language instructions requires more than invoking isolated APIs. Interactive tasks combine reactive physical behaviors with stateful social behaviors, while existing interfaces often require developers to manually compose APIs into skills, configure their parameters, bind sensor events to skills, and manage task states at runtime. We present MistyPilot, a multi-agent LLM framework that interprets high-level natural-language instructions and orchestrates the corresponding skills on the Misty social robot. A Task Router dispatches each instruction to one of two specialized agents: a Physically Interactive Agent for sensor-triggered robot control and direct skill invocation, and a Social Interaction Agent for dialogue-oriented task-state management and context-dependent multimodal response generation. To improve efficiency, the Social Interaction Agent reuses previously generated results when applicable and invokes full generation otherwise. We

---

### [34] Beyond BFI: The CSI for Enhanced Reliability and Validity in Evaluating LLM Personality Traits

**链接**: https://arxiv.org/abs/2503.20182
**作者**: Huanhuan Ma, Haisong Gong, Xiaoyuan Yi, Xing Xie, Philip S. Yu, Dongkuan Xu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] SkillCommit: Evolving Agent Skills through Behaviorally Validated Scope Expansion

**链接**: https://arxiv.org/abs/2608.15165
**作者**: Yu He, Weikai Yang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can continually improve without parameter updates by converting historical experience into reusable procedural knowledge. However, existing methods often consolidate experience based on semantic similarity or LLM judgments, which may merge superficially related but behaviorally incompatible strategies and thereby degrade performance. To address the issue, we propose SkillCommit, an online skill evolution framework that continuously transforms experience into a hierarchical library of reusable skills. Each new experience is initially preserved as an instance-specific patch, retaining the behavior validated in its local context. As related skills accumulate, SkillCommit abstracts those sharing a common behavioral mechanism into higher-level skills. Specifically, for each incoming skill, embedding-based retrieval first identifies candidate related skills. Cross-instance replay and an LLM-based mechanism check determine whether these skills transfer across

---

### [36] Ventor-QTest: Threat-Model-Driven Verification of Vendor-Hosted LLM APIs

**链接**: https://arxiv.org/abs/2608.16391
**作者**: Xiangfan Wu, Zonghao Ying, Huiyu Wu, Xing Zheng, Huangsheng Cheng, Xiaorong Shi 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models become increasingly widespread, third-party providers that deploy open-weight models have become an important part of the ecosystem. Auditing the quality of their inference APIs is therefore an open problem. We formalize hosted model routing as a stochastic process and propose \mbox{\textbf{Ventor-QTest}}, a composite black-box audit that requires no probability information from the target API. Its repeated-request component sends each frozen constrained context to the target multiple times, reconstructs a categorical output distribution from the returned text counts, and reports \emph{average fidelity loss} (AFL) as a null-bias-corrected, within-window mean coarsened-KL statistic. Its long-sequence component uses independent runs to report \emph{extreme fidelity loss} (EFL) through the empirical upper tail of a run-level reference-centered-surprisal statistic. Across three logprob-capable route conditions, AFL shows strong linear descriptive agreement with a l

---

### [37] When Do Anchor-Based Pointwise LLM Rerankers Help? Retriever Quality, Statistical Scope, and Anchor Design

**链接**: https://arxiv.org/abs/2608.10528
**作者**: Utshab Kumar Ghosh, Shubham Chatterjee
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] Admission Without Answers: Label-Free Certification and Experience Learning for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2608.15565
**作者**: Junbo Jacob Lian, Huiling Chen, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experience-learning agents for optimization modeling improve by storing verified skills, but existing learners admit knowledge by checking against known answers, which real ticket streams do not provide. The natural label-free alternatives are unreliable: on a 300-problem label-blind stream, admitting every executable model poisons roughly one admission in four, while single-instance agreement accepts models that match at one value but differ elsewhere. We propose AdmitOR, an admission gate built on calibrated external behavioral evidence. Candidates from three model families, prompting strategies, and solver stacks are run on instances resampled from an extracted parameter domain; agreement across the resulting value-function traces is summarized by a cross-family clique, and a calibrated threshold returns accept, abstain, or escalate. The preregistered false-discovery criterion holds on calibration data but not on the wild stream. We report this negative result in full and trace most

---

### [39] A Scalable Pipeline for LLM-Teacher Distillation Labeling: Work-Stealing Job Scheduling and Memory-Aware GPU Concurrency

**链接**: https://arxiv.org/abs/2608.15975
**作者**: Ravi Satya Durga Prasad Yenugula
**来源**: cs.DC cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Labeling large text corpora with LLM teachers has become a practical route to training data at scale. At millions of items, hand-labeling every batch is not feasible, and two questions dominate: what label quality a teacher buys per dollar, and how to keep a fleet of GPU workers busy under skewed, failure-prone workloads. We present a simple, reproducible pipeline that addresses both. First, a work-stealing ring pool: each worker owns a queue, drains it first, and then steals from ring successors, with exactly-once task claims via atomic conditional writes and crash tolerance via stale-claim sweeping. The claim protocol requires only a compare-and-set primitive from its storage layer; we implement it on a single SQLite file, which makes the reference implementation dependency-free and the experiments reproducible on one machine. Second, a memory-aware concurrency rule that sizes per-node parallelism by how many model copies fit on the GPU, so the same code runs safely across device siz

---

### [40] Reflex-Guard: A Low-Latency Guardrail for LLM Prompt Safety Using Dense Semantic Embeddings

**链接**: https://arxiv.org/abs/2608.17556
**作者**: Istiaque Ahmed, Afia Anjum Borsha, Ranat Das Prangon, Abu-fuad Ahmad, Thi Hong Tran
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) in real-world applications often face the risks of specially crafted prompts designed to bypass the safety controls. Existing guardrail methods, such as LLM-as-a-judge and cloud-based safety APIs are able to detect unsafe content. However, they often add a delay of about 250-900 ms to each request. This delay is too high for real-time applications, when the system usually needs to respond in less than 100 ms. Furthermore, routing user prompts through external moderation endpoints raises significant data privacy concerns. This paper introduces Reflex-Guard, a lightweight guardrail that runs locally. It uses jailbreak-aware preprocessing, compact sentence-transformer embeddings, and seven fast binary classifiers. Together, these components enable high-accuracy prompt safety filtering with much lower latency than existing solutions. Through systematic evaluation on a strategically balanced dataset of 30,568 samples drawn from five complementary sources, we dem

---

### [41] Beyond the pale: Assessing prevalence and contents of extremist speech in LLM training data

**链接**: https://arxiv.org/abs/2608.14813
**作者**: Dmitry Nikolaev, Ashley A. Mattheis
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite a strong interest on the part of the research community in the topic of trustworthy and safe AI, the composition of the text corpora that large language models (LLMs) encounter in pre- and post-training has not yet drawn much attention. In this work, we address the question of whether LLMs are exposed to unfiltered, uncontextualised extremist speech. Using several definitions of extremist speech, stemming from official documents and research literature, and an extraction pipeline combining automated text processing with expert verification, we provide a lower bound on the prevalence of extremist documents in Dolma, an open training corpus underpinning the OLMo series of models. We show that Dolma is likely to include hundreds of thousands of documents containing extremist content and hate speech of several types, including direct calls for violence, and discuss the implications of this for data curation and model pre-training.

---

### [42] Procedural Collapse: A Structural Account of Disengagement in LLM-Assisted Writing

**链接**: https://arxiv.org/abs/2608.17326
**作者**: JaeWon Kim, Katelyn Mei
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When students use large language models for writing, the dominant explanation for disengagement is dispositional: they are over-reliant, and the remedy is to scaffold self-regulation. We argue that a structural explanation is needed, offering an alternative basis for design interventions to support appropriate AI-assisted writing. Current LLM writing interfaces induce procedural collapse: the replacement of an iterative, self-paced writing process with a single output that shifts the writer's task from generation to comprehensive evaluation. Because that evaluation is costly, shallow engagement becomes the default, and the cognitive work writing was supposed to produce goes unperformed. The framework points toward design directions that reduce the burden on writers to self-regulate, including decomposed interaction, goal elicitation as a default first step, and single-level output. They complement metacognitive scaffolding by restructuring the interaction itself.

---

### [43] Institution-Specific LLM Prompting Recovers PHI That De-identification Systems and Their Gold Standards Both Miss

**链接**: https://arxiv.org/abs/2608.17051
**作者**: Daniel Palacios and Matthew Brady Neeley and Angel Adetomike Otto and Shalini Dhamodharan and John P. Woodhouse and Chi-fan Lin and Mark Zobeck and Zhandong Liu and Hyun-Hwan Jeong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Secondary use of electronic health records requires de-identification, yet existing systems miss \emph{institutionally situated} protected health information (PHI) such as hospital abbreviations, building names, and internal codes whose status is locally determined. We ask whether large language models (LLMs) with in-context learning (ICL) can close this gap and control the precision--recall trade-off. On 100 annotated pediatric oncology notes (5,322 PHI spans) from Texas Children's Hospital, we benchmarked eight LLMs against two purpose-built systems (Stanford TiDE, OpenMed PII) and two pattern-based baselines. Each LLM ran under three prompts of increasing specificity: (1) a HIPAA-aligned baseline, (2) baseline plus the institutional PHI categories it missed, and (3) prompt 2 plus instructions against over-redacting clinical content. We then compared 14~multi-agent and ensemble configurations against the best single prompt, with recall the primary safety metric. LLMs outperformed the

---

### [44] SchurQuant: Groupwise Discrete Optimization for Layer-Wise LLM Quantization

**链接**: https://arxiv.org/abs/2608.15567
**作者**: Gunjun Lee, Sehwan Son, Younjoo Lee, Byungjun Kim, Jung Ho Ahn
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-only post-training quantization (PTQ) enables the deployment of large language models under tight memory budgets, but accuracy often collapses at 2-3 bits. Existing backpropagation-free PTQ optimizers have two limitations: group decisions ignore the correction that the remaining continuous suffix can absorb, and discrete refinements typically keep the affine quantization grid fixed. We introduce SCHUROPT, which analytically eliminates the suffix's optimal continuous response, yielding an exact groupwise quadratic with Schur-complement curvature. It then alternates closed-form row-wise scale/zero-point refitting with coordinate descent over integer codes. With the GPTQ objective fixed, SCHUROPT improves mean zero-shot accuracy on 2-bit Qwen3-4B by 11.88 percentage points (pp). At higher precision, however, tighter reconstruction does not consistently improve end-model metrics. SCHURQUANT therefore combines SCHUROPT with quantized-prefix teacher reconstruction, reference-weight re

---

### [45] Task-Aware Harness Provisioning for LLM Agents in Mission-Critical Infrastructure Operations

**链接**: https://arxiv.org/abs/2608.17433
**作者**: Liangtao Lin, Qingang Zhang, Zhaomeng Zhu, Tianwei Zhang and Yonggang Wen
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have been widely adopted to operate mission-critical infrastructure (MCI). These agents normally rely on a harness that determines what information they can access, which tools they can use, and what actions they can take. Existing systems often expose the same comprehensive harness to every task, which may not be necessary and cause resource wastes. In this paper, we focus on the identification of optimal harness configurations, and view it as a resource-matching problem between what each task requires and what the harness provides. To measure this match, we classify MCI tasks based on the mathematical representation of the underlying system and rank harness configurations by the amount and type of information they provide. We then construct task-to-harness mappings from two sources: mining research literature and measuring controlled agent execution. Leveraging the measured mapping, we propose a new harness provisioning algorithm: map-guided escalation. It begins with a ta

---

### [46] LLM Enhancement with Domain Expert Mental Model to Reduce LLM Hallucination with Causal Prompt Engineering

**链接**: https://arxiv.org/abs/2509.10818
**作者**: Boris Kovalerchuk, Brent D. Fegley
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Agentic-SQL Revisited: Autonomy-Based Taxonomy and Empirical Benchmark Analysis for LLM Text-to-SQL

**链接**: https://arxiv.org/abs/2608.15389
**作者**: Changruo Zhao, Zujun Peng, Yu Tian, Yuting Liu, Yiyun Su, Huiying Zhu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based Text-to-SQL progress is reported across heterogeneous benchmarks, backbones, and inference protocols, making cross-system comparison fragile. We reframe the field as a leaderboard aggregation: we collect the metrics authors themselves report and organize them along an inference-autonomy axis spanning constrained, in-context, iterative, agentic, and reasoning-internalized generation, with traceable provenance for every cell. To anchor the aggregation empirically, we run a focused case study on Spider, comparing 8B open-source backbones with and without chain-of-thought (CoT) supervision against few-shot DeepSeek~V3 and GLM-4 baselines. Four patterns emerge: Spider gains transfer unevenly to BIRD and Spider~2.0; autonomy buys robustness at non-trivial cost; reasoning internalization sits between answer-only decoding and externally orchestrated agents; and CoT gains concentrate on Hard and Extra-Hard queries. We release a Python harness mirroring the autonomy axis so that future

---

### [48] TSQueryBench: LLM-as-a-Judge for Time Series Explanations

**链接**: https://arxiv.org/abs/2604.02118
**作者**: Preetham Sivalingam, Murari Mandal, Dhruv Kumar and Saurabh Deshpande
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] LLM-Guided Graph Generation for Structure-Based Local Improvement Methods

**链接**: https://arxiv.org/abs/2608.13333
**作者**: Hai Xia, Vaidyanathan Peruvemba Ramaswamy, Stefan Szeider
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Analytical Provisioning for Attention-FFN Disaggregated LLM Serving under Stochastic Workloads

**链接**: https://arxiv.org/abs/2601.21351
**作者**: Chendong Song, Meixuan Wang, Hang Zhou, Hong Liang, Yuan Lyu, Zixi Chen 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] Mental Model Management: An Operator-Based Framework for LLM Memory

**链接**: https://arxiv.org/abs/2608.15451
**作者**: Oliver Kramer
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models process large amounts of information but usually lack an explicit mechanism for maintaining compact and evolving conceptual representations. We introduce Mental Model Management (3M), a framework in which knowledge is represented as mental models consisting of compact chunks. Rather than accumulating text passages, 3M continuously integrates new information into an existing conceptual representation. A set of operators extracts knowledge, retrieves relevant models, adds and updates chunks, reorganizes representations, detects inconsistencies, and derives new knowledge. We describe the main 3M operators and illustrate each operation using Evolution Strategies as a running example.

---

### [52] Value Leakage: An LLM's Answers Are Silently Shaped by Its Own Values

**链接**: https://arxiv.org/abs/2607.14345
**作者**: Jan Betley, Johannes Treutlein, Jan Dubi\'nski, Harry Mayne, Karol Ga{\l}\k{a}zka, Niels Warncke 等 (8 人)
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Prior Audit-Repair Context Shifts LLM Verifier Thresholds Toward Leniency

**链接**: https://arxiv.org/abs/2608.16003
**作者**: Parsa Mazaheri and Kasra Mazaheri
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated checking pipelines increasingly place one language model as the checker and another (or the same one) as the fixer. We ask whether that wiring changes what the checker reports. Measuring false alarms on human-verified-correct ProcessBench traces with the present task held byte-identical, we find that a completed audit -> repair episode already in the model's context lowers false alarms in 15 of 15 model x wording combinations, by 2.8 to 11.5 percentage points against a length-matched non-audit control, a 9 to 25% reduction relative to that control. The direction contradicts what the accumulated-message literature predicts: an episode whose audit reported an error lowers false alarms further still, at all five wordings on the model where that manipulation lands cleanly, though a negativity asymmetry predicts more flagging. Decomposing the episode finds repair content and audit verdict complementary: different components carry the effect on different model families. Signal-dete

---

### [54] Mitigating Rubric Interference in LLM Judges via On-Policy Self-Distillation

**链接**: https://arxiv.org/abs/2608.14684
**作者**: Dingyao Yu, Tong Zhang, Yutao Mou, Yunxiao Zhang, Wei Ye, Shikun Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges increasingly evaluate responses against fine-grained rubric checklists. When a sample requires multiple rubrics, current methods typically assess each in a separate inference call. Evaluating all rubrics in a single pass is a natural alternative with greater efficiency, but we find that it introduces rubric interference: the verdict on one rubric shifts depending on which other rubrics are co-present. In a preliminary study, only one-third of samples receive fully consistent verdicts when evaluated under rubric sets of varying composition. We develop a measurement framework that probes interference through four controlled operations: rubric set expansion, subsetting, reordering, and noise injection. To mitigate interference without external supervision, we propose Self-Anchored Rubric Alignment (SARA). SARA uses a model's own single-rubric judgments as stable anchors and aligns multi-rubric reasoning with these anchors through on-policy self-distillation. We validate SARA on

---

### [55] Class Imbalance and Batch Effects in LLM-Based Screening for Systematic Reviews

**链接**: https://arxiv.org/abs/2608.14737
**作者**: Gilberto Sussumu Hida, Danilo Monteiro Ribeiro, Clayton Suguio Hida
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study analyses LLMs in imbalanced binary classification, using study screening in systematic reviews as the application domain. An experiment was conducted in five reviews, comparing individual and batch processing, with and without prevalence metadata. The results indicate a limited influence of the prevalence metadata, with no evidence that it improves performance. In contrast, batch processing produced larger behavioral changes that varied according to the prevalence of the class. The aggregate and item-level analyses did not always coincide. Therefore, batch processing should be evaluated not only in terms of cost, but also in relation to its effects on decision-making behavior.

---

### [56] Multi-Bin Batching for Increasing LLM Inference Throughput

**链接**: https://arxiv.org/abs/2412.04504
**作者**: Ozgur Guldogan, Jackson Kunde, Kangwook Lee, Ramtin Pedarsani
**来源**: cs.CL cs.DC cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] TCMIIES: A Browser-Based LLM-Powered Intelligent Information Extraction System for Academic Literature

**链接**: https://arxiv.org/abs/2605.07507
**作者**: Hanqing Zhao
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] LatentSkill: From In-Context Textual Skills to In-Weight Latent Skills for LLM Agents

**链接**: https://arxiv.org/abs/2606.06087
**作者**: Aofan Yu, Chenyu Zhou, Tianyi Xu, Zihan Guo, Rong Shan, Zhihui Fu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] LLMs as a Jury: Cross-Model Consensus Can Outperform Process Reward Models for LLM Reasoning

**链接**: https://arxiv.org/abs/2607.10139
**作者**: Ning Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] Toward Safe LLM Agents: A Survey of Specification, Verification, and Enforcement

**链接**: https://arxiv.org/abs/2608.14590
**作者**: Pierre Dantas, Lucas Cordeiro, Ehsan Nowroozi, Tihanyi Norbert
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly perform irreversible real-world actions, including database updates, API calls, file operations, and autonomous use of tools. However, no existing system provides formally grounded, task-level safety guarantees for the plans these agents generate. Research remains fragmented across specification, verification, and enforcement, limiting understanding of the strengths and limitations of existing approaches. To address this gap, we conducted a PRISMA 2020 systematic review of 38 studies published between 2022 and 2026 and retrieved from six academic databases. Our analysis reveals four key findings. First, the specification bottleneck remains the primary challenge: natural-language-to-formal translation achieves only 24% to 35% semantic correctness, undermining downstream verification. Second, runtime monitoring is the most mature enforcement strategy, reducing unsafe actions by 40% to 65% in controlled settings, but it does not provide complete safety guarantees. 

---

### [61] TileMix: Tile-Centric Mixed-Precision Attention for LLM Inference Acceleration

**链接**: https://arxiv.org/abs/2608.17336
**作者**: Hanzhi Zhang, Qiao Zhang, Qinglei Cao, Heng Fan, Yan Huang, Kewei Sha 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context prefill in large language models (LLMs) incurs substantial computation and memory traffic because dense self-attention computes quadratic query-key scores. Existing methods either use a uniform low-precision path or select token interactions, leaving spatial precision routing over hardware-aligned score tiles outside fused dense attention. We introduce TileMix, a tile-centric precision-routing kernel that makes numerical precision an executable spatial decision over score-tile groups within fused dense attention. TileMix partitions the attention matrix into hardware-aligned score tiles, packs routing decisions into compact bitmasks, and dispatches each tile group through FP16 or INT8 score computation while both paths update a shared online-softmax state. Scalable precision grouping lets each routing bit govern multiple adjacent key tiles, preserving hardware-aligned compute tiles and compact metadata at long contexts. By routing all legal tile groups, TileMix preserves de

---

### [62] Optimal Watermark Localization in Mixed-Source Large Language Model Texts

**链接**: https://arxiv.org/abs/2608.14906
**作者**: Jose H. Blanchet, T. Tony Cai, Xiang Li, Hao Liu, Qi Long, Weijie J. Su
**来源**: stat.ME cs.CL cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking provides a principled way to authenticate text generated by large language models (LLMs). In practice, however, the final text may be mixed-source, with watermark evidence surviving at only a subset of token positions after rewriting, insertion, deletion, or paraphrasing. Although prior work has studied global detection of watermark signals, when such signals can be localized remains unclear. We formulate watermark localization as a token-level multiple-testing problem based on pivotal statistics, with a latent indicator recording whether watermark dependence survives at each position. Under an asymptotic regime indexed by exponents for signal sparsity, next-token concentration, and effective-vocabulary growth, we derive a sharp boundary for global detection and phase transitions for discovery and classification within the class of coordinatewise pivot-based localization rules. We show that discovery is strictly harder than detection and that consistent classification is i

---

### [63] POI Recommendation with LLM-Augmented Multi-Graph Learning and Contrastive Alignment

**链接**: https://arxiv.org/abs/2608.16407
**作者**: Burak Tamer, Wolfram H\"opken and Zehui Wang
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Point-of-interest (POI) recommendation models based on graph neural networks achieve strong performance by propagating collaborative signals over user-item interactions, yet they struggle with the cold-start problem, where items with few or no interactions are not represented. In this paper, we propose LLM-augmented Multi-Graph Contrastive Learning (LLM-MGCL), a multi-graph neural network that uses semantic and spatial information about items to extend the LightGCN backbone with two auxiliary item-item graphs: a semantic graph constructed from sentence embeddings of LLM-generated photo summaries and keywords, and a geographic graph derived from Haversine distances between business locations. Item embeddings are propagated over all three graphs in parallel, fused additively, and aligned across views through a bidirectional InfoNCE contrastive objective that connects behavioral, semantic, and spatial representations of the same items. Experiments on the Yelp Multimodal Recommendation Dat

---

### [64] Organizational Control Layer: Governance Infrastructure at the Execution Boundary of LLM Agent Systems

**链接**: https://arxiv.org/abs/2606.04306
**作者**: Tianyu Shi, Yang Mo, Yiou Liu, Zhuonan Hao, Yin Wang, Wenzhuo Hu 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Language Family Matters: Evaluating LLM-Based ASR Across Linguistic Boundaries

**链接**: https://arxiv.org/abs/2601.18899
**作者**: Yuchen Zhang, Ravi Shekhar, Haralambos Mouratidis
**来源**: cs.CL cs.AI cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Automating Parent Selection Configuration in Genetic Programming with Agentic AI

**链接**: https://arxiv.org/abs/2608.17172
**作者**: Jose Guadalupe Hernandez, Jui-Hsuan Chang, Anil Kumar Saini, Xi Li, Jason H. Moore
**来源**: cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate whether agentic artificial intelligence can automate parts of the process of designing genetic programming systems by introducing an agentic framework that identifies and implements parent selection algorithms using large language model (LLM) reasoning and retrieval-augmented generation. Using symbolic regression as a test bed, we first conduct an ablation study across four LLM types to evaluate the effects of agentic reasoning and retrieval on generated algorithm categories, validity, implementation similarity, and downstream performance. Results show that these components substantially influence the types of algorithms generated, but their downstream performance largely depends on the underlying LLM. The strongest configuration, the full agentic setup with 5 mini (5 mini--AR), consistently generated established $\epsilon$-lexicase implementations while maintaining competitive downstream performance. We then benchmark this configuration against fixed implementations of 

---

### [67] When Stories Evolve: Benchmarking LLM Storytelling Across Agent Architectures in Open-Ended World Simulations

**链接**: https://arxiv.org/abs/2608.15654
**作者**: Yuqi Chen, Sixuan Li, Yunfeng Cai, Xueai Li, Ka Man Yan, Ying Li
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can write fluent stories, but open-ended storytelling requires more than local fluency. In evolving world simulations and AI-native games, models must preserve facts, relationships, causal dependencies, and character states as the world changes. We introduce WSE-bench, a process benchmark that separately evaluates sustained generation, canonical coherence, and meaningful development in dynamic LLM storytelling. Generation Coverage records the proportion of planned narrative steps produced; Consistency tracks when canon breaks; and Richness measures how meaningfully branching, player-shaped trajectories develop. Across frontier models, Consistency and Richness do not form a smooth trade-off: their empirical Pareto frontier is non-concave, with several non-dominated intermediate configurations that no positive linear weighting can select. Added structure can enrich trajectories, but it does not uniformly improve coherence and may shorten them. Model scale chiefly im

---

### [68] Emergent Misaligned Communication in Long-Horizon Multi-Agent LLM Commerce

**链接**: https://arxiv.org/abs/2608.14825
**作者**: Zeyuan Li (Massachusetts Institute of Technology), Lukas Petersson (Andon Labs), Alessandro Acquisti (Massachusetts Institute of Technology), Michiel A. Bakker (Massachusetts Institute of Technology)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier LLM agents increasingly transact on behalf of separate principals, often using natural language rather than structured APIs. Much of the safety literature studies misaligned LLM behavior through adversarial-elicitation evaluations on single agents or stylized tasks. Its prevalence and structure in settings that combine long horizons, separate principals, real operational state, and inter-agent natural-language exchange remain insufficiently measured. We study 2,583 inter-agent emails from 20 one-year simulation runs of Vending-Bench Arena, a competitive vending environment spanning 13 frontier LLMs. We operationalize speech-act misalignment as emails containing false factual claims, manipulation, collusion, or threats, combining message content with ground-truth simulator state and logged reasoning traces to classify and validate such behavior. Under our primary classifier, 12.6% of emails are labeled misaligned; misalignment appears in all 20 runs and 74.7% of individual agen

---

### [69] A decodability criterion predicts when hidden-state selection beats majority voting in large language models

**链接**: https://arxiv.org/abs/2608.17124
**作者**: Zhixiang wang, Ziliang Hong, Ulas Bagci
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Combining the answers a large language model (LLM) samples for a question into one decision is a test-time information fusion problem, usually solved by majority voting. Voting is unreliable on difficult questions, where the sampled answers share correlated errors, so the wrong answer can win and drawing more samples makes the decision worse. Selecting a candidate by reading a correctness signal from the model's hidden states is a promising alternative, but its accuracy varies across models and tasks, and no measure indicates when it can be trusted. In this paper, we propose CASE (Correctness-Axis SElection), a dynamic selection combiner that trains a linear gate on the answer-token hidden state and selects the highest-scoring candidate. Its main contribution is decodability, a leakage-free measure of how well the gate ranks a question's correct candidates above its incorrect ones, which predicts whether hidden-state selection will outperform voting. A conventional probe appears accura

---

### [70] BiAxisBias: Evaluating LLM Bias Beyond a Single Prompt and a Single Explanation

**链接**: https://arxiv.org/abs/2605.09041
**作者**: Jialing Gan, Junhao Dong, Songze Li
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] LLMs Can Predict Failure Risk, But Struggle to Predict Which Collaboration Protocol Pays Off: Cost-Aware Protocol Routing Across Reasoning Tasks

**链接**: https://arxiv.org/abs/2608.14927
**作者**: Chih-Hsuan Yang, Jingyan Jiang, Cheng-Hau Yang, Vikram Vasudevan, Huihuo Zheng, Venkatram Vishwanath 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) systems can improve reasoning by spending more computation, but deployment requires deciding when extra collaboration is worth its cost. We isolate this decision by running every problem under four protocols while holding the solver fixed within each setting: direct solving (Baseline), iterative self-correction (Single), planner-executor-reviewer collaboration (PER), and multi-agent deliberation (Broadcast). The primary benchmark comprises 4,181 competition-level math problems; paired robustness checks cover four benchmarks spanning competition math, biology, and broader science with two solver families. Across fixed policies, trained routers, and frozen LLM routers, conservative policies under-escalate, whereas higher-solve frozen routers often over-escalate. A post-answer, pre-collaboration gpt-oss-120b probe ranks Baseline failures with 0.8847 AUROC (4,151 parseable cases; 95% CI [0.8732, 0.8955]). The same score remains informative for predict

---

### [72] Semantic Uncertainty-Guided Orchestration in Hierarchical Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.14707
**作者**: John Knowlton, Aritra Guha, Risto Miikkulainen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM)-based multi-agent systems become increasingly capable, coordinating agents under uncertainty becomes a fundamental challenge. Existing orchestration strategies typically rely on fixed interaction patterns and often lack mechanisms for assessing the reliability of intermediate reasoning steps, allowing errors and hallucinations to propagate through the system. This paper introduces a semantic-uncertainty-guided orchestration approach, HASSUM as a general framework for uncertainty-aware coordination in multi-agent systems. The method estimates uncertainty using semantic entropy and semantic density, which measure trust at the level of answer semantics rather than output probabilities. These signals enable adaptive orchestration decisions, including output verification, selective reprompting, additional deliberation, and confidence-aware response selection. Because the approach operates independently of any particular agent architecture, it can be integrated 

---

### [73] Who's Keeping Score? Interactive Steering of LLM-Powered Scoring with Attune

**链接**: https://arxiv.org/abs/2608.14948
**作者**: Bhavya Chopra, Meng Chen, Rebecca Dang, Chanbin Park, Shreya Shankar, Sepanta Zeighami 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to score text records at scale (e.g., rating candidate resumes on a 1-5 scale). However, existing LLM-powered approaches do not account for the fact that effective scoring requires both holistic understanding of records and locally consistent judgments across similar ones. We present Attune, a mixed-initiative system for steerable LLM-powered scoring. Given a task description and scoring range, Attune performs pairwise comparisons across records to develop a global understanding first, and then resolves these comparisons into consistent score assignments-deriving scoring criteria and rules bottom-up in the process. These serve as shared representations of scoring logic that users can inspect and edit. Based on insights from a formative study (n = 12), Attune's interface introduces novel steering interactions that allow users to deterministically refine scoring logic. Users can provide examples, directly edit criteria, rules, or target 

---

### [74] Effective Personalized AI Tutors via LLM-Guided Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.16907
**作者**: Angel Tsai-Hsuan Chung, Botong Zhang, Ling-Chieh Kung, Hamsa Bastani, Osbert Bastani
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI (GenAI) is rapidly reshaping education by unlocking the potential for personalized tutoring. Yet, emerging platforms largely focus on GenAI chatbot tutors that reactively answer student questions. We hypothesize that the efficacy of GenAI chatbot tutors can be substantially improved by proactively guiding student learning. To test this, we design a novel tutoring platform that tightly integrates a carefully-designed GenAI chatbot with a reinforcement learning algorithm for sequencing practice problems. Critically, this algorithm leverages rich signals from student-chatbot interactions to adaptively select practice problems of an appropriate difficulty level. In partnership with the Taipei City Government and American Institute in Taiwan, we deployed our tutoring platform in conjunction with a five-month course to teach Python to students across ten high schools. We randomized students between a fixed practice problem sequence and our adaptive sequencing algorithm. We find

---

### [75] ChatPlanner: A Large Language Model Framework for Personalized Public Transit Routing

**链接**: https://arxiv.org/abs/2606.15315
**作者**: Tingting Yang, Chenhao Xue, Jun Chen
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] Would this change your answer? Evaluating Explanations of LLM Behavior In The Wild with Counterfactual Experiments

**链接**: https://arxiv.org/abs/2608.16747
**作者**: Adam Karvonen, Euan Ong, Subhash Kantamneni, Samuel Marks
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many areas of AI research, such as language model interpretability and chain of thought faithfulness, seek to explain model behaviors. But what constitutes a "good" explanation? In this work, we evaluate explanations through the lens of counterfactual simulatability-whether the explanation is useful for predicting model behaviors on related counterfactual inputs. To this end, we introduce CHIVE (Counterfactual Hypothesis Investigation Via Edits), a novel agentic pipeline that identifies unexpected model behaviors in the wild and investigates them with counterfactual prompt edits. This yields thousands of high-quality explanations for naturally-occurring model behaviors along with supporting counterfactual evidence. We apply CHIVE in two ways. First, we evaluate whether common LLM interpretability techniques improve an agent's ability to predict counterfactual model behaviors. Surprisingly, we find no uplift from any of the interpretability techniques studied. Second, we use CHIVE to ge

---

### [77] Hierarchical Agentic Incident Response with Digital-Twin-Validated Attack Inference

**链接**: https://arxiv.org/abs/2608.15016
**作者**: Yiran Gao, Juntao Chen, Tao Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Network incident response remains slow and labor-intensive as the defender must infer multi-stage attacks from partial observations and translate recovery decisions into reliable system commands. Decision-theoretic planners provide principled optimization but typically rely on abstract states and predefined actions, while large language model (LLM) agents can reason over operational context but may hallucinate attacks and responses. Toward automating response planning, we present a hierarchical agentic response framework that integrates LLM-based attack inference, rollout planning, and digital-twin validation. A fine-tuned LLM infers the attack progression and affected hosts from security alerts and system measurements. An emulated network digital twin replays the inferred attack and returns discrepancies between predicted and observed effects to calibrate the inference. A separately fine-tuned planning agent uses the rollout planning method to prioritize affected components at the tac

---

### [78] STAGE: Controlled Objective Admission for Multi-Preference LLM Alignment

**链接**: https://arxiv.org/abs/2608.16553
**作者**: Yongqi Tong, Zhenyu Zhang, Ruirui Wang, Kewei Fu, Shaoqing Lin, Sijie Dong 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-preference alignment is often framed as scalarization: combine reward dimensions, then optimize. This leaves a temporal decision underspecified: when should each preference dimension enter policy optimization? We propose \methodname, a stability-guided active-set controller for controlled objective admission. \methodname starts from a small active set, retains admitted objectives, and expands when reward-deviation gates indicate low recent deviation or a patience budget is exhausted. A probing phase estimates a hard-to-easy order, and adaptive weighting emphasizes underperforming active dimensions. Automatic evaluations with 15 training preferences and 16 held-out benchmark columns show that \methodname obtains higher averages than simultaneous scalarization and shared-budget adapted baselines. Component ablations and expansion dynamics further support cumulative retention, gated admission, and probing-derived ordering as useful design choices in this setting. These results posit

---

### [79] Train Yourself as an LLM: Exploring Effects of AI Literacy on Persuasion via Role-playing LLM Training

**链接**: https://arxiv.org/abs/2604.02637
**作者**: Qihui Fan, Min Ge, Chenyan Jia, Weiyan Shi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] A hierarchical control framework for photovoltaic-driven air conditioning systems: LLM -based reward weight adaptation and TD3 real-time control

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s12273-026-1467-3&hl=zh-CN&sa=X&d=10163378009914931314&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-yDCTe6l9k5C0_oBl7BOh2H&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: Z Wu, X Fu, S Li, J Peng, H Li, H Li - Building Simulation 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM based supervisory reward adaptation with TD3-based real-time compressor control. In this framework, TD3 was responsible for real-time compressor speed control, enabling adaptive responses to changing environmental conditions. While

---

### [81] Attention Flows: Tracing LLM Conceptual Engagement via Story Summaries

**链接**: https://arxiv.org/abs/2604.06416
**作者**: Rebecca M. M. Hicke, Sil Hamilton, David Mimno, and Ross Deans Kristensen-McLachlan
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] The Integer Alibi: Localizing Cross-Kernel Divergence in INT8-Quantized LLM Inference

**链接**: https://arxiv.org/abs/2608.13756
**作者**: Teng-Ruei Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] PertMind: Eliciting Emergent Biological Reasoning in LLM via Reinforcement Learning on Cellular Perturbation Data

**链接**: https://arxiv.org/abs/2608.16419
**作者**: Zhenchao Tang, Xiaogang Xu, Tianxu Lv, Jiahui Guan, Jiale Zhou, Haohuai He 等 (10 人)
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can describe mechanisms, yet scalable post-training still depends on costly, manually curated biological reasoning traces. Here we show that cellular perturbation atlases can instead become reinforcement-learning environments, where measured gene responses provide computable rewards for biological reasoning. We introduce PertMind, which combines trusted-trajectory supervised initialization with gene-, pathway-, and format-level reinforcement signals. Trained only on forward perturbation-response prediction, PertMind improved response inference in unseen cellular contexts while retaining general language capabilities. It also transferred without task-specific post-training to reverse perturbation identification, double-perturbation reasoning, phenotypic-screen prioritization, and biological-process interpretation. PertMind further generated biological profiles that supported competitive gene, cell, and donor representations across multiscale downstream tasks. These

---

### [84] Breaking and Defending LLM-Powered Social Media Bot Detection Systems

**链接**: https://arxiv.org/abs/2608.15893
**作者**: Nof Orenstein, Yoni Birman
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rise of social media bots poses a persistent threat, enabling misinformation, opinion manipulation, and the erosion of trust in online platforms. To combat this, machine learning systems have been developed to detect and limit bot activity, but attackers continuously adapt through techniques such as adversarial learning and behavior imitation, fueling an ongoing arms race between bots and detection tools. Recent advances in large language models (LLMs) have significantly improved bot detection by enabling deeper semantic and contextual analysis of accounts and their content. However, this shift also introduces new attack surfaces, allowing adversaries to craft exploits that directly target the reasoning and generation mechanisms of LLM-based classifiers. Industry tools such as Anthropic's Claude Code Security similarly leverage LLMs for security-critical decisions, further motivating a careful study of their attack surfaces. In this work, we investigate both the offensive and defen

---

### [85] From Prompts to Constructs: A Dual-Validity Framework for Large Language Model Research in Psychology

**链接**: https://arxiv.org/abs/2506.16697
**作者**: Zhicheng Lin
**来源**: cs.CY cs.AI cs.CL cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Auxiliary uncertainty signals for LLM-assisted systematic review screening: a benchmark across eight Cohen drug-class reviews

**链接**: https://arxiv.org/abs/2608.14551
**作者**: Arya Rahgozar and Pouria Mortezaagha
**来源**: cs.CL cs.DL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for title-abstract screening in systematic reviews, but their decisions lack calibrated uncertainty. We show that an auxiliary BERT+GCN classifier supplies a structured uncertainty signal that improves LLM screening efficiency, and we identify the prompt-delivery strategy that maximises the benefit-to-cost ratio. We evaluate five LLM prompt-delivery conditions on eight drug-class datasets from the Cohen (2006) benchmark using 3 seeds x 5-fold stratified cross-validation (600 fold-level results). A BERT+GCN model trained per fold classifies each test paper as INCLUDE, EXCLUDE, or MAYBE via two spectral tests (algebraic radical and categorical paradox). Conditions vary information content (none / label / full scores), selectivity (all papers vs. MAYBE only), and timing (proactive vs. reactive two-pass). A cross-model pilot against gpt-4.1-mini on three datasets tests cross-generation transfer. Three findings: (i) Full-context delivery yi

---

### [87] Catching Hallucinated Citations in Video-LLM Question Answering: A Self-Verification Pipeline and Verifier Ablation Study

**链接**: https://arxiv.org/abs/2608.15574
**作者**: Yogesh Kumar
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video question answering systems built on vision-language models often produce timestamped claims with high confidence even when unsupported by the cited frame. This deceptive hallucination arises because timestamps imply grounding without ensuring correctness, increasing user trust but not accuracy. We introduce a pipeline that closes this loop. A retrieval-augmented language model drafts answers with per-claim timestamp citations, and each cited frame is independently re-examined before being shown to the user. We compare against a plain baseline and ablate three verification designs, evaluated on both Apple Silicon (MLX) and Google Colab (HF Transformers, CUDA). Directly asking the vision model whether a frame supports a claim fails completely (0% catch rate on 40 claims) due to sycophancy. Blind re-captioning plus a general LLM judge improves results but is unstable, oscillating between 0% and 100% flagged depending on prompt phrasing. Replacing that judge with a small natural lang

---

### [88] Wind Turbine Maintenance Log Labelling Framework: LLM-Driven Data Correction and Enrichment via Semantic Extraction of Reliability Intelligence

**链接**: https://arxiv.org/abs/2605.31281
**作者**: Max Malyi, Jonathan Shek, Alasdair McDonald, Andre Biscaya
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Do LLM Agents Negotiate Rationally? A Mechanism-Design Framework for Verifiable Multi-Agent Interaction over A2A/MCP

**链接**: https://arxiv.org/abs/2608.14613
**作者**: Wael Albayaydh, Rui Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM-agent frameworks increasingly interoperate through standards such as Anthropic's Model Context Protocol (MCP) for agent-to-tool access and Google's Agent2Agent (A2A) protocol for agent delegation and negotiation. However, these protocols specify transport and discovery rather than strategic correctness and do not guarantee efficient, individually rational, or strategy-proof outcomes. We introduce a framework that (i) encodes classical negotiation mechanisms, including alternating-offers bargaining and Vickrey-Clarke-Groves-style auctions, as constraints over A2A message schemas; (ii) provides a lightweight runtime verification and repair layer that checks messages against protocol invariants; and (iii) offers a benchmark of negotiation and allocation tasks with known optimal solutions for measuring deviations from game-theoretic predictions. We evaluate multiple LLM backbones using unstructured dialogue, structured protocols, and structured protocols with verification. Acros

---

### [90] Analyzing Error Propagation in Korean Spoken QA with ASR-LLM Cascades

**链接**: https://arxiv.org/abs/2605.17443
**作者**: Donghyuk Jung, Youngwon Choi
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Diagnosing LLM Benchmark: A Psychometric Analysis of Difficulty and Discrimination

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-31673-8_10&hl=zh-CN&sa=X&d=15653082931982875588&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-zWoQueuW0AAa-SlKzmcyXT&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: J Qin, X Zhang, D Feng, B Ding, Y Zhai - International Conference on Pattern …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper proposes a structural diagnostic framework for LLM benchmarks, moving beyond scalar scores to analyze evaluation instruments. It maps benchmark items onto a multi-dimensional skill space and quantifies benchmark quality along

---

### [92] SCOPE: Selective Conformal Optimized Pairwise LLM Judging

**链接**: https://arxiv.org/abs/2602.13110
**作者**: Sher Badshah, Ali Emami, Hassan Sajjad
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] I-CALM: Incentivizing Confidence-Aware Abstention for LLM Selective Answering

**链接**: https://arxiv.org/abs/2604.03904
**作者**: Haotian Zong, Binze Li, Yufei Long, Sinyin Chang, Jialong Wu, Gillian K. Hadfield
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] Hierarchical Data Selection via Manifold Coverage and Sparse Feature Coverage in LLM Post-training

**链接**: https://arxiv.org/abs/2608.16927
**作者**: Peng Sun, Yi Yang, Antong Zhang, Chunxiao Li, Yanbo Wang, Dianbo Liu 等 (10 人)
**来源**: cs.LG cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As supervised fine-tuning data continues to scale, selecting high-value subsets from large candidate pools is crucial for reducing training cost and improving model performance. Existing methods often measure diversity directly in the original embedding space, where geometric metrics entangle dominant semantic directions, fine-grained supervision differences, and local noise. We address this limitation by formulating data selection as a coarse-to-fine hierarchical coverage problem and propose MASS. MASS learns low-dimensional principal manifold coordinates with a dense autoencoder for coarse semantic grouping, and then performs quality-aware sparse feature coverage within each group using a TopK sparse autoencoder. Experiments on Vision Flan and LLaVA-CoT show that MASS consistently outperforms strong data selection baselines across multiple budgets, and in several settings matches or surpasses full data training with only a small subset of data.

---

### [95] Theoretical Open Problems in Symmetric Cryptography: Verifiable LLM -Guided Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://eprint.iacr.org/2026/1687.pdf&hl=zh-CN&sa=X&d=8115903487034591247&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-xJYBeNa6HCVGPgUsSfy1kp&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: Y Yuan, Y Hu, Y Zhang, L Zhang, W Wu - Cryptology ePrint Archive, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Both Pilot and Sailor use an LLM . We represent the LLM as an autoregressive conditional distribution pθ, where θ denotes the model parameters. Let x = (x1,...,xm) be an ordered tuple of task inputs, and let τ be a prompt template. A prompted

---

### [96] Beyond Access: Guided LLM Scaffolding for Independent Learning in Undergraduate Statistics

**链接**: https://arxiv.org/abs/2606.01375
**作者**: Mohammad Amanlou, Yasaman Amou-Jafari, Fereshte Bagheri, Fatemeh Boloukazari, Mehrad Liviyan, Elahe Khodaverdi Nadrabadi 等 (8 人)
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] MUSE: An Interactive Meta-Agent for Understanding and Steering LLM-powered Data Science Systems

**链接**: https://arxiv.org/abs/2608.16181
**作者**: Wei-Hao Chen, Weixi Tong, Yuan Tian, Chenglong Wang, Tianyi Zhang
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models have enabled a new class of agentic data science systems that allow users to complete complex data science workflows through natural language. Although these systems can significantly reduce manual effort, it remains difficult to diagnose their behavior and steer the reasoning process when failures or unexpected outputs occur. We present MUSE, an interactive meta-agent that enhances user understanding and control of agentic data science systems by (1) dynamically restructuring low-level execution traces into multiple semantic levels that support navigation from high-level overviews to low-level implementation details; (2) enabling users to reference specific workflow steps in context to ask grounded questions, provide feedback, and revise problematic steps without manually locating relevant execution history; and (3) supporting mixed-initiative steering by surfacing suspicious steps for inspection, scaffolding the repair process, and translating

---

### [98] Measuring the Prevalence of Policy Violating Content with ML Assisted Sampling and LLM Labeling

**链接**: https://arxiv.org/abs/2602.18518
**作者**: Attila Dobi, Aravindh Manickavasagam, Benjamin Thompson, Xiaohan Yang, Faisal Farooq
**来源**: cs.LG stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [99] SAPE: Sandwich Adapters for Parameter Efficiency in Large Language Model Fine-Tuning

**链接**: https://arxiv.org/abs/2608.15360
**作者**: Mohammad Aref Jafari-Raddani and Morteza Mohajjel Kafshdooz
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Parameter-Efficient Fine-Tuning (PEFT) has substantially reduced the hardware cost of adapting Large Language Models (LLMs) by decreasing the number of trainable parameters, recent studies have sought to further improve PEFT through parameter sharing. However, these approaches either employ uniform parameter sharing across layers, which can delay convergence, or rely on dynamic masking strategies, which add computational overhead. The potential of sharing patterns inspired by the inherent hierarchical structure of Transformer architectures remains unexplored in PEFT. To address this gap, we introduce SAPE (Sandwich Adapters for Parameter Efficiency), a PEFT framework based on a sandwich-style hard weight-sharing topology. SAPE routes intermediate Transformer layers through balanced shared group adapters while strictly isolating the input embedding and final projection boundary transformations to prevent gradient interference. This design significantly reduces memory consumption w

---

### [100] Turning Off-Policy Tokens On-Policy: A Plug-in Approach for Improving LLM Alignment

**链接**: https://arxiv.org/abs/2607.04728
**作者**: Yu Li, Xiuyu Li, Mingyang Yi, Jiaxing Wang, Liangxu Zhang, Zhaolong Xing 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Large language model-assisted discovery of cohorts from scientific literature

**链接**: https://arxiv.org/abs/2608.15909
**作者**: Moritz Sturm, Lisa M. Berg, Inken Berg, Harishny Sarma, Jasmin Hartmann, Denissa Girschik 等 (9 人)
**来源**: cs.IR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Planning multi-study analyses requires identifying cohorts with the relevant participants, phenotypes, and data modalities. This process commonly relies on prior knowledge, cohort catalogues, and manual literature searches. We developed a complementary question-driven framework that searches relevant scientific literature and extracts explicit cohort names. Methods: The framework first generates multiple PubMed queries from configurable vocabularies and templates and retrieves the resulting scientific literature automatically through the PubMed API. A large language model then screens the retrieved titles and abstracts and extracts explicit cohort names using a prompt tailored to the research question. The extracted names are deduplicated with human review. Configurable code, prompts, and example outputs are available at https://gitlab.rz.uni-frankfurt.de/cap_molgenlab/literature-cohort-discovery. Evaluation: As a use case, we applied the framework to youth aggression genet

---

### [102] Integrating LLM -based agents with uncertainty-aware optimization for water-energy-carbon nexus management in irrigation districts

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0043135426014144&hl=zh-CN&sa=X&d=3010404701465276010&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-z6xS_ivPlOGVfMk652yJPj&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: L Yu, Z Li, K Huang, F Li, Z Lu, Y Fan 等 (9 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study develops an LLM -agent driven intelligent optimization framework for WEC-coupled irrigation management. The framework … A hybrid LLM setup uses DeepSeek-V4-Flash for task parsing and Qwen3.6-Plus for decision analysis

---

### [103] Le Critique: Privileged Value Functions for LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.16739
**作者**: Siddarth Venkatraman, Matthieu Dinot, Laurence Aitchison
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning algorithms for Large Language Models (LLMs) are largely distinguished by their variance reduction strategy. Group-relative methods like GRPO reduce gradient variance by sampling multiple rollouts per prompt, but provide only sequence-level credit. Training is also blocked by straggler rollouts, reducing throughput and increasing off-policyness. Learned value functions theoretically address both problems, providing token-level advantages without requiring large groups. However, additional infrastructure engineering challenges combined with the practical success of critic-free methods have made it difficult to justify their inclusion in RL pipelines. We propose two complementary strategies to improve the performance of value function RL: 1) Privileged Value Functions (PVF) which provide an elegant mechanism to inject additional task-relevant token-level signal without biasing the policy objective; 2) TETHER, a baseline that adaptively interpolates between group-rel

---

### [104] OmegaUse-OfficeVal: Benchmarking LLM Agents on Long-Horizon Office-Suite Tasks with Economic Grounding

**链接**: https://arxiv.org/abs/2607.27155
**作者**: Jingbo Zhou, Yusai Zhao, Qi Bao, Jingjia Cao, Zhenghai Chen, Chang Gao 等 (10 人)
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] E2LLM: Towards Efficient LLM Serving in Heterogeneous Edge/Fog Environments

**链接**: https://arxiv.org/abs/2606.03770
**作者**: Truong-Thanh Le, Amir Taherkordi, Hoang-Loc La, Frank Eliassen, Phuong Hoai Ha and Peiyuan Guan
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] GraphWake: Group Polarization via Memory-Mediated Polarization Cascade in LLM-Agent Communities

**链接**: https://arxiv.org/abs/2608.17665
**作者**: Haoran Bu, Zejian Chen, Litian Zhang, Xi Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-driven agents can autonomously exchange opinions on online platforms and form communities. Such agent-operated social platforms raise a new security concern: attackers may manipulate agents to induce group polarization. Existing methods manipulate agent prompts or construct echo chambers, both of which are difficult to realize in practice. We therefore formulate a new threat, Memory-Mediated Polarization Cascade, which uses agent memory as a persistence channel and public discussion as a propagation channel. This threat contains three stages. During exposure and memory retention, the attacker exposes a small set of target agents to arguments that reinforce their respective stated stances. The targets' memory systems then process and retain these arguments. During retrieval and reproduction, a shared stance-neutral discussion cues the targets to retrieve and reproduce their respective retained arguments. During iterative propagation, untreated agents influenced by the reproduced arg

---

### [107] The Little Scientist: LLM Agent-Driven Discovery via the Scientific Method

**链接**: https://arxiv.org/abs/2608.16951
**作者**: Travis Smith
**来源**: q-bio.QM cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What happens when you teach an LLM-based agent the scientific method? Motivation: Scientific discovery emerges from cycles of hypothesis, implementation, empirical testing, and feedback. Can this process be automated? We approach automated algorithm design through the lens of the scientific method, where an LLM-based agent goes through each step of the process in an ordered, iterative fashion. Results: We present The Little Scientist, a framework in which a "Scientist agent" works inside an evaluation environment that benchmarks its code and returns structured per-instance diagnostics. When the Scientist plateaus at a local optimum, a "Kuhn agent" injects a paradigm-shifting conjecture paired with a cross-disciplinary inspiration, forcing exploration of a different region of the LLM's latent space. We demonstrate the framework on two problems that require fundamentally different modes of discovery. For protein fitness prediction, the Scientist discovered Delta V, an ensemble calibratio

---

### [108] OraclePhys: A Systematic Framework for LLM Fine-Tuning on Structural Mechanics

**链接**: https://arxiv.org/abs/2608.17162
**作者**: Mingyu Li, Guorui Song, Jing Lin, Haoqian Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What a language model internalizes from fine-tuning is usually diagnosed after the fact. We make it an experimental variable. OraclePhys is a systematic fine-tuning framework with three components: OraclePhys-Bench, an exactly-graded structural-mechanics benchmark whose finite-element oracle scores every answer and counterfactual edit -- no human labels, no LLM judging; OraclePhys-30K, a supervision dataset of seven answer forms over byte-identical structure descriptions; and a controlled training study across the seven forms and three verifier roles. The study yields two findings. First, the label's answer form -- not its bit count -- causally determines what fine-tuning teaches: a ranking objective installs an out-of-distribution forward model where the untrained base sits at the guessing prior, a scalar objective at best a partial one, a boolean nothing detectable; the vector-scalar gulf survives a second physics domain, a second model family, and a paraphrased evaluation surface. S

---

### [109] From LLM Inference to Agentic Workloads: Characterization and Implications for Serving Systems

**链接**: https://arxiv.org/abs/2608.15127
**作者**: Chaokun Chang, Yukun Zhou, Kaihua Fu, Dakai An, Tianyu Feng, Hanfeng Lu 等 (10 人)
**来源**: cs.OS cs.AI cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic applications are shifting AI serving from isolated model inference to long-running workloads in which LLMs coordinate tools, environments, and persistent state. However, the system behavior of these workloads---where latency, cost, and bottlenecks arise---remains poorly characterized, leaving serving systems to rely on assumptions built for conventional inference. We present AgentSysBench, a benchmark suite and measurement toolkit with ten representative agentic applications and unified systems-level instrumentation. Across controlled deployments and production traces, we identify six properties that distinguish agentic workloads from conventional LLM serving: (1) execution is heavyweight and stateful, with non-LLM components dominating latency in 5 of 10 applications and sandbox working-set memory peaking at 28 GB per session; (2) applications compose components with heterogeneous resource affinity---GPU-bound inference, memory-bound retrieval, CPU-bound sandboxes---whose task

---

### [110] Evo-Harness: Context-to-Harness Skill Compilation for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2608.15071
**作者**: Tianxin Wei, Zhan Shi, Minhua Lin, Bing He, Zewen Liu, Yisi Sang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from experience is critical for developing capable, self-improving large language model (LLM) agents. Existing methods typically extract knowledge from accumulated trajectories via reflection, memory, rules, or skills. However, agents in realistic environments continuously encounter novel tasks, often offering only a one-shot opportunity to improve. These executions yield rich but highly noisy contexts, entangling broadly useful lessons with task-specific artifacts. Critically, prior works rarely validate their effectiveness on complex real-world tasks or isolate the underlying drivers of improvement. To address these gaps, we formulate online harness learning, where a frozen agent improves by continually updating a structured harness across sequential tasks. This formulation enables a systematic study of key self-improvement factors through our proposed Evo-Harness. At its core, context-to-harness skill compilation distills noisy, single-shot executions into reusable skill ha

---

### [111] Data-DPO: Direct Preference Optimization for Target Model Data Selection in LLM Post-Training

**链接**: https://arxiv.org/abs/2608.16926
**作者**: Peng Sun, Yi Yang, Antong Zhang, Chunxiao Li, Yanbo Wang, Dianbo Liu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data selection in supervised fine-tuning aims to select a small set of effective samples from large-scale candidate data, reducing training cost while preserving model performance. However, existing methods usually treat data value as a relatively static property, and pay limited attention to the compatibility between data and the capability distribution of the target model. To address this issue, we propose Data-DPO, a target model-oriented SFT data selection method. Data-DPO observes the local training feedback of the target model on different samples through one-step probing, transforms activation differences among samples into pairwise data preferences, and trains a lightweight reward model to learn target-model-aware data preferences. In the final selection stage, Data-DPO further combines target model preference, external quality scores, and marginal diversity to construct a more stable and effective training subset. Experimental results on Vision-Flan and LLaVA-CoT show that Dat

---

### [112] LLM Safety Alignment in Low-Resource Languages: A Systematic Literature Review

**链接**: https://arxiv.org/abs/2608.14626
**作者**: Valdini Douglace Lemofouet, Blessing Ngozi Uzor, Paula Chikaodinaka Anyanwu, Danielle Blanche Kapsa, Sukairaj Hafiz Imam, P Sam Sahil 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have achieved substantial progress in safety alignment, yet their safety guarantees remain significantly weaker in low-resource and multilingual settings than in high-resource languages. In this paper, we conduct a Systematic Literature Review (SLR) of LLM safety alignment in low-resource languages by adopting the PRISMA 2020 methodology. Out of roughly 1,500 papers identified from Semantic Scholar, arXiv, and OpenAlex, 50 relevant studies have been selected and analyzed. Our review is organized around four themes: safety alignment methods, multilingual safety risks, evaluation benchmarks, and cross-lingual transferability. We further propose a taxonomy of safety alignment approaches based on three adaptation mechanisms: data adaptation, objective optimization, and mechanistic alignment. Across literature, translated English benchmarks fail to sufficiently represent culturally rooted harms, and multilingual models are more vulnerable to cross-lingual jailbr

---

### [113] Multi-Granularity Sentiment Integration for LLM-Based Multimodal Sentiment Analysis

**链接**: https://arxiv.org/abs/2608.16201
**作者**: Shanshan Lin, Yuesheng Wu, Chao Chen, Yizhe Yang, Zhihao Chen, Zexian Yang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal sentiment analysis (MSA) aims to predict sentiment polarity and intensity from heterogeneous inputs such as text, audio, and vision. While large language models (LLMs) offer strong semantic priors for MSA, effectively incorporating audio and visual signals effectively remains challenging. A key challenge is that audio and visual sentiment cues evolve over different temporal scales, yet many LLM-based methods compress these signals through shallow projection or coarse pooling before fusing them with text, which can weaken cross-modal alignment and erase fine-grained affective information. We propose MGSI, a multi-granularity sentiment integration framework for LLM-based MSA. MGSI first encodes audio and visual streams at short-, medium-, and long-range temporal scales, preserving both local variations and global affective trends. It then refines non-text features through text-guided alignment, and applies polarity- and intensity-aware enhancement to better handle ambiguous an

---

### [114] LLM-Derived Preference Judgments Are Not Self-Consistent

**链接**: https://arxiv.org/abs/2608.17644
**作者**: Matthew T. Ford, Francis Bahk, Jingjing Wang, Adam S. Jovine, Tinghan Ye, David B. Shmoys 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents increasingly interpret a person's natural-language preferences by querying an LLM for numerical preference judgments, e.g., by asking how much the person would be willing to pay for an item. A growing body of work estimates a utility function from these judgments and then chooses actions based on their estimated utility. This pipeline assumes the judgments are approximately self-consistent: that a single utility function can reproduce them. But are they? To study this question, we measure the self-consistency of cardinal LLM preference judgments. For example, the difference in stated willingness-to-pay between two items should match the stated payment that makes a person indifferent to exchanging them. We develop statistical tests and interpretable measures of how far observed responses depart from the best-fitting self-consistent utility function. Experiments with flight, apartment, and hotel examples across six LLMs reveal large persistent inconsistencies. This suggests that L

---

### [115] SIGMA: SHAP-Guided Implicit-Trajectory Generation for Metadata-Free LLM-Based AutoFE

**链接**: https://arxiv.org/abs/2608.17948
**作者**: Xuan Zheng, Kento Uchida, Shinichi Shirakawa
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent research has leveraged Large Language Models (LLMs) to enhance Automated Feature Engineering (AutoFE) through semantic descriptions and trajectory-based prompting. However, there exist two challenges that limit their applicability and scalability in long-horizon optimization: (1) semantic metadata is unavailable in many practical settings, and (2) trajectory accumulation increases the risk of exceeding the context window, while without it, the generation process can become unstable, leading to becoming stuck in the local optima and a high duplicate rate of generated features. To this end, we propose a SHAP-enhanced Implicit-trajectory Generation for Metadata-free AutoFE (SIGMA), a scalable constant-context optimization framework. SIGMA leverages SHAP values to provide task-aware signals for guiding group feature generation instead of semantic information. In addition, we adopt an EXposed-feature Implicit Trajectory (EXIT) approach, where the exposed features in the prompt implic

---

### [116] PriPTune: Privacy-Preserving LLM Fine-Tuning Service Framework Via Blockchain and TEE-GPU Collaborative Computing

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11655548/&hl=zh-CN&sa=X&d=3504855473107109061&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-yEIdmFVr8elbAeGm9bjvY7&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: L Lin, M Li, Z Yang, J Weng, R Wu, J Weng - IEEE Transactions on Services … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Fine-tuning large language models (LLMs) on private datasets is an effective approach for building domain-specific services, but outsourcing training may expose sensitive data, intermediate activations, gradients, and trainable parameters to

---

### [117] A Human-LLM Teaming Framework for Privacy Risk Analysis: An Illustration with CBDC-Based Welfare Schemes

**链接**: https://arxiv.org/abs/2608.16461
**作者**: Sourya Joyee De and Abdessamad Imine
**来源**: cs.ET cs.AI cs.CE cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Central Bank Digital Currency (CBDC)-based welfare schemes may be potentially privacy invasive as they process significant volumes of beneficiary personal data and lead to privacy harms such as surveillance, discrimination and stigmatization. Such welfare delivery schemes involve complex digital ecosystems and large number of stakeholders. Consequently, to examine their privacy risks, privacy risk assessments require extensive information gathering and synthesis, complex reasoning, scenario explorations, contextual evaluation and human judgement. Thus, they present ideal scenarios for human-LLM teaming, where effective integration of complementary human and LLM capabilities can yield an outcome far superior to either human-only or LLM-only assessments. In this paper, we propose a first human-LLM teaming framework for the systematic privacy risk analysis methodology called PRIAM. The framework specifies an iterative collaborative process in which the LLM processes large-scale documentar

---

### [118] Prompting is not enough: supervised baselines and leakage control for measuring shared decision-making with LLMs in pediatric encounters

**链接**: https://arxiv.org/abs/2608.14792
**作者**: Bernardo Modenesi, Jody Lin, Kimberly Kaphingst, Angela Zhu, Maya Wheeler, Peilu Zhang 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objectives: To determine whether zero-shot prompting of a large language model (LLM) is sufficient to detect shared decision-making (SDM) behaviors in real clinical encounters, and whether supervised learning adds value under patient-grouped, nested evaluation. Methods: We analyzed 21 audio-recorded outpatient surgical decision encounters (19 unique patients; 7,566 utterance segments; ~6.1 hours) between families of children with multiple long-term conditions and their surgical providers. Trained coders labeled segments for 12 SDM behaviors (human-human macro Cohen's kappa = 0.695). We compared a zero-shot local LLM (Qwen 2.5 32B), a supervised classifier over frozen sentence embeddings, and their logistic stack, under patient-grouped outer folds with inner cross-fitted thresholds and patient-resampled confidence intervals. Results: The zero-shot LLM reached macro kappa = 0.139 (95% CI 0.111-0.164). The supervised classifier reached kappa = 0.227 (0.186-0.262), a paired improvement of 

---

### [119] Architecture-Dependent Causal Transfer of Activation States Across Large Language Models

**链接**: https://arxiv.org/abs/2608.16347
**作者**: Fernando Cardenas Piepereit
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct communication between AI systems relies on natural language as an intermediate layer, incurring encoding/decoding overhead, token cost, and latency. We ask whether internal activation states can instead be transferred causally between different large language model (LLM) architectures via a learned projection, evaluated at three levels: representational similarity, cross-model retrieval from projected states, and end-to-end causal transfer via activation injection during generation. Using four architecturally diverse open-weight models (Qwen2-0.5B, Phi-3-mini, Mistral-7B, FLAN-T5-base), we find that representational alignment in trained models exceeds a random-initialization null baseline and is best captured by a rank-based metric (mutual k-nearest-neighbour alignment), more robust to activation-magnitude outliers than centered kernel alignment (CKA) or Procrustes analysis. A learned projection network retrieves the correct target-model representation from a held-out set well a

---

### [120] Can Large Language Models Explain Flight Safety Events? A Prior-Guided Semantic LLM-based Approach

**链接**: https://arxiv.org/abs/2608.18017
**作者**: Lu Xu, Xu Li, Linjiang Zheng, Fan Li, Riquan Zhang, Jiaxing Shang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving flight safety with flight data requires not only accurate detection of risk events, but more importantly, clear interpretation of their underlying causes at the level of pilot control behavior. Existing explainable AI techniques, such as feature importance maps, often require considerable domain knowledge to translate them into operationally meaningful explanations. Large Language Models (LLMs), which excel at language reasoning, bring a promising solution to this issue. However, applying LLMs in this domain presents key challenges such as modal inconsistency, limited classification ability, scarcity of task-specific data for fine-tuning, and lack of domain knowledge. To overcome these challenges, we propose FlightLLM, a prior-guided semantic LLM-based approach for interpretable flight safety analysis. Specifically, we first perform feature engineering to address modal inconsistency, combining statistical descriptors with physically meaningful flight indicators. This represen

---

### [121] HyperSkill: Self-Evolving LLM Agents via Hypergraph-Structured Skill Memory

**链接**: https://arxiv.org/abs/2608.16114
**作者**: Ruiyao Xu, Tiankai Yang, Wei-Chieh Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agentic tasks grow in complexity, LLM agents increasingly rely on experiential memory to reuse procedural knowledge across tasks. Effective memory design must jointly address what to store, how memory is structured and retrieved, and how memory evolves. Existing systems tackle each only partially: they store trajectories, insights, or workflows as isolated entries, discarding compositional relationships among subtasks and reusable skills; retrieve by flat embedding similarity that ignores relational signals; and maintain memory without leveraging its relational structure. We propose HyperSkill, a hypergraph-based memory framework that jointly improves all three. HyperSkill represents memory as a hypergraph with two node types, subtask steps and reusable skills, where each hyperedge links the subtasks and skills from a single trajectory. Dual-path retrieval queries both subtask and trajectory levels, ranking skills by co-occurrence across retrieved trajectories. Periodic structure-in

---

### [122] OTel: Building Domain-Specialized Telecom LLM Foundations for Intelligent Networks

**链接**: https://arxiv.org/abs/2608.15436
**作者**: Farbod Tavakkoli, Roderic Paulk, Jorden Terrazas, Kenneth Church, Mark Austin, Louis Powell 等 (10 人)
**来源**: cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier AI models have advanced rapidly, but they still struggle with telecom-specific tasks. We present Open Telco (OTel), an open telecom AI resource with derived datasets for retrieval, reranking, instruction tuning, and safety/abstention, plus 30 full-parameter post-trained baselines across embedding, reranking, and language models. The community has already engaged substantially with the resource: as of May 3, 2026, the released models have been downloaded over 16 million times, and the project has received 157+ pieces of media coverage worldwide. Building on prior open telecom datasets and benchmarks, OTel provides documented telecom data sources, held-out evaluation partitions, trained embedding models, rerankers, context-grounded LLMs, and safety/abstention data in one unified resource. OTel post-training improves performance across all three model families: embedding retrieval reaches 93.5% NDCG@10, reranking reaches 0.952 MRR@10, and language-model correctness reaches 88.2%.

---

### [123] LadderTeam: Dual-Agent Laddering Elicitation Framework

**链接**: https://arxiv.org/abs/2608.17029
**作者**: Manjushree Aithal, Alexander Kotz, James Mitchell
**来源**: cs.SE cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Eliciting detailed and actionable software requirements from end-users is a critical phase in the iterative development of a software product or application. To ensure the feedback collected is detailed and actionable, software teams can leverage the laddering interview technique. While effective for ensuring granular and actionable items from the software feedback, these interviews are subject to several limitations. They are traditionally a manual process associated with a time and financial burden, limiting scalability; interviewers must balance probing for depth while managing interviewee behavioral and cultural constraints. To address these limitations, we present \textbf{LadderTeam}, an open, reproducible framework that automates UX wireframe interviews using a dual-agent Large Language Model (LLM) architecture. An active interviewer agent executes one of three probing strategies (ACV, 5-Whys, and JTBD) to elicit actionable software requirements from usability feedback comments, 

---

### [124] HyMem: Hierarchical Context Management for Long-Horizon Agents via Information Isolation

**链接**: https://arxiv.org/abs/2608.15703
**作者**: XinQi Wang, Jinwei Xiao, Sijia Cui, Hongming Zhang, Yanna Wang, Qingyang Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents often perform poorly on complex, long-horizon tasks because their context becomes increasingly cluttered over time. As interactions accumulate, detailed execution traces and intermediate outputs dominate the context, making it difficult for the model to retain and use high-level planning information. Most existing methods address this issue through compression or retrieval applied to a single, flat context, which does not clearly separate different types of context information and often leads to degraded reasoning. To address this challenge, we propose HyMem, a hierarchical framework that explicitly separates the agent's context into distinct functional layers. HyMem organizes context by function to separate high-level planning from execution and complex analysis. Its isolated reasoning module handles complex subtasks without adding intermediate reasoning traces to the persistent planning context, while its memory management module preserves task progr

---

### [125] PolyWorkBench: Benchmarking LLM Agents for Cross-Lingual Long-Horizon Workflows

**链接**: https://arxiv.org/abs/2607.06008
**作者**: Hongliang Li, Yijin Liu, Zhiwei Zhang, Zihe Liu, Xinyue Lou, Jinan Xu 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] FluxBin: Flexible LUT-based Ultra-low-bit LLM Inference by Algorithm-Kernel Synergy

**链接**: https://arxiv.org/abs/2608.15602
**作者**: Qingyao Yang, Runming Yang, He Xiao, Wendong Xu, Junyu Chen, Haobo Liu 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While binary quantization theoretically promises extreme compression and acceleration for Large Language Models (LLMs), existing research often overlooks the necessity of specialized hardware kernels, thus failing to unleash the full acceleration potential due to persistent reliance on expensive floating-point arithmetic or runtime dequantization overheads. To bridge this gap, we propose FluxBin (\textbf{F}lexible \textbf{L}UT-based \textbf{U}ltra-low-bit e\textbf{X}ecution with \textbf{Bin}ary bases), an algorithm-kernel co-design that synergizes post-training quantization with a highly optimized CUDA kernel. Algorithmically, we introduce Decoupled Row-Column Binary Decomposition to enhance representational capacity while maintaining hardware efficiency, complemented by a Hessian-guided saliency-aware hybrid bases that preserve critical information. At the kernel level, we implement a Lookup Table Building Approach with Scale Fusion to reduce floating-point arithmetic, featuring a Vir

---

### [127] Valhalla: A Layered Knowledge-State and Service-Governance Framework for Long-Term Scientific Knowledge Work

**链接**: https://arxiv.org/abs/2608.15193
**作者**: Yuyang Zheng, Nan Li, Wenxia Deng, Lige Yan, Xiang Li, Si Chen
**来源**: q-bio.NC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents are increasingly adopted in scientific research, external knowledge bases, knowledge graphs, and long-term memory have improved information retrieval and task continuity. However, most structured knowledge systems remain node-centric, representing files, concepts, results, and judgments as nodes and relations in a graph. While suitable for personal knowledge management, such structures often depend on individual organizational practices, limiting knowledge sharing, integration, and reorganization across users. This paper presents Valhalla, a layered knowledge-state and service-governance framework for long-term scientific knowledge work. Valhalla replaces flat graphs with layered encapsulation and stable semantic boundaries through a five-layer File-Resource-Entity-Relationship-Graph (FREG) model. File and Resource preserve source identity and provenance, Entity represents knowledge objects, Relationship captures semantic judgments, and Graph provid

---

### [128] Judge, Retrieve, or Abstain: Uncertainty-Guarded LLM Judging with Provable Risk Guarantees

**链接**: https://arxiv.org/abs/2608.17994
**作者**: Sher Badshah, Ali Emami, Hassan Sajjad
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Using LLMs as judges has become standard practice for evaluating model outputs at scale. This is particularly common for subjective, open-ended tasks such as assessing helpfulness or alignment, where no single reference answer exists. However, objective tasks introduce a distinct reliability challenge for reference-free LLM judging. In the absence of a reference answer, the judge evaluates factual correctness either through its parametric knowledge or through tool augmentation. Although the former enables efficient evaluation, the judge may hallucinate or lack sufficient evidence for its verdict. Conversely, tool augmentation can provide additional evidence but introduces extra computational cost and requires an appropriate mechanism to determine when and how that evidence should be used reliably. More importantly, neither approach alone provides formal control over the risk of accepted verdicts or guarantees their reliability at a specified level. We propose a risk-controlled framewor

---

### [129] T-LLM Compiler: Trusted LLM-based Code Optimization and Verification Framework

**链接**: https://arxiv.org/abs/2608.14953
**作者**: Zahra Fazel, Sunanda Gamage, Shayan Shirahmad Gale Bagi, Amir H. Ashouri, Tomasz S. Czajkowski, Bryan Chan 等 (8 人)
**来源**: cs.AI cs.CL cs.LG cs.PF cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Large Language Models (LLMs) have opened opportunities to apply high-level code transformations to the field of code optimization, and it has since emerged as one of the most fundamental tasks for LLMs to perform; however, at present, LLMs struggle to apply wide-ranging code optimization tasks due to both the complexity of the code and the inability to independently verify the correctness of the transformations. In this paper, we present the Trusted LLM (T-LLM) Compiler, which proposes an advancement in compiler technology through a collaborative effort involving high-level LLM code transformations, traditional compilers, and verification tools. Experimental results reveal that it can significantly improve code correctness when tested on a set of PolyBench/C benchmarks. Our approach facilitates iterative code optimization efforts with verification strategies that enable corrective actions. Through this approach, T-LLM Compiler achieves code optimization accuracy of u

---

### [130] GxP-Agent: Process-DAG Topology for Reliable Clinical Trial Programming with LLM Agents

**链接**: https://arxiv.org/abs/2608.16890
**作者**: Jaime Yan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical trial programming -- transforming study protocols into analysis-ready datasets under CDISC standards -- is a bottleneck in regulatory submissions, yet LLM-based code generation fails catastrophically on this task: across 11 single-shot attempts with five frontier models, none produces a valid subject-level analysis dataset. We introduce GxP-Agent, a multi-agent system that encodes regulatory process ordering as a directed acyclic graph (DAG), decomposing monolithic dataset generation into 15 domain-specific nodes executed by worker agents with pharmaverse skill context, validation gates, and conditional retry. On CDISC-Bench, a new execution-based benchmark built from the FDA pilot submission CDISCPilot01 (254 subjects, 49 ground-truth ADSL variables), GxP-Agent with Claude Sonnet 4.6 achieves 100% structural match (49/49 variables, 254 correct records) across three independent runs, compared to 59.2% for the best retrieval-augmented baseline and 0% for all single-agent and fl

---

### [131] WeSCE: A Benchmark for Measuring Security Drift in LLM-Driven Code Editing

**链接**: https://arxiv.org/abs/2608.15092
**作者**: Zhiyu Zhang, Tingyue Wen, Senke Sun, Dengxiang Liang, Enhao Huang
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we introduce WeSCE, a benchmark for quantifying security drift in code editing under weak-security constraints, where tasks specify only functional objectives without explicit security requirements. WeSCE consists of 400 executable programs derived from real-world code, covering feature addition, feature removal, bug fixing, and refactoring. To quantify security drift, we propose a continuous risk representation that aggregates heterogeneous vulnerability signals through a unified formulation, and define drift measures capturing changes in overall risk, worst-case severity, and vulnerability distribution under code transformations, providing a multi-scale view of security spanning average-case behavior to worst-case emphasis.

---

### [132] SubZero+: Efficient Zeroth-Order LLM Fine-Tuning via Large Learning Rates

**链接**: https://arxiv.org/abs/2608.15665
**作者**: Ziming Yu, Shuyao Xiao, Xingyu Zhao, Sike Wang, Pan Zhou, Peiyu Zang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization enables backpropagation-free fine-tuning of large language models, but existing ZO methods suffer from high-variance gradient estimators, making convergence unstable and highly sensitive to learning rates. We propose SubZero+, an improved SubZero framework that improves stability in three complementary ways: (i) multi-query gradient estimation within layer-specific low-rank subspaces to reduce variance without exhibiting the multi-query paradox; (ii) a subspace Adam optimizer that performs adaptive updates using in-subspace multi-query gradient statistics; and (iii) a sign correction for QR-based subspace construction to ensure Haar-distributed projection matrices, eliminating implementation-dependent orientation ambiguity. Experiments on models from 1.3B to 32B across SuperGLUE, under both full-parameter tuning and LoRA, show that SubZero+ consistently outperforms prior ZO baselines, enlarges the stable learning-rate range, and narrows the gap to first-o

---

### [133] When State Becomes an Attack Surface: State-Semantic Injection in LLM-Driven Embodied Agents

**链接**: https://arxiv.org/abs/2608.16806
**作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have demonstrated capabilities in in-context learning, task decomposition, step-by-step reasoning, and code generation, driving their gradual evolution from text generation models into the core of agents capable of perceiving environments, invoking tools, and executing tasks. Traditional LLM Agents typically obtain information through webpages, documents, databases, or external tools and generate corresponding invocation sequences according to user goals; when this technology is further integrated with robotic systems, large language models begin to undertake functions such as task understanding, high-level planning, and behavioral decision-making. SayCan combines the task reasoning capability of language models with the affordances of robotic skills, while Code as Policies and ProgPrompt generate robot task plans through policy code and programmatic prompting, respectively, and VoxPoser uses language models and vision-language models to construct three-dim

---

### [134] Divergent-Convergent Reasoning: Scaling Test-Time Compute through Structured Solution Synthesis

**链接**: https://arxiv.org/abs/2608.15303
**作者**: Bo Wen, Yuhao Chen, Erhan Bilal, Carla Agurto Rios, Chen Wang, Junchen Jiang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time compute can substantially improve Large Language Model (LLM) reasoning performance, yet how and when additional compute helps remains poorly understood. We study Divergent-Convergent Reasoning (DCR), a simple two-phase primitive consisting of an exploration phase that generates multiple candidate solutions followed by a convergent reconciliation phase. We present three core results. First, we show that even a single reconciliation step can reliably amplify correct minority reports: across datasets, DCR often recovers the correct answer when correct exploration outputs are in the minority, a regime where majority voting fails. Second, we introduce recursive DCR, an autoregressive reconciliation system that iteratively analyzes disagreements and allocates additional test-time compute. Recursive DCR achieves higher accuracy than fixed-compute baselines-reaching 93.3% on AIME 2024 and 92.0% on AIME 2025-while using roughly 27% less compute on average, demonstrating that attentive

---

### [135] When Entropy Is Not Enough: Reclaiming Lost Semantics in LLM Output Length Prediction

**链接**: https://arxiv.org/abs/2608.15592
**作者**: Feiyang Ren, Shengtao Wen, Lingbing Guo, Yu Tian, Yuanning Cui, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient LLM serving is often bottlenecked by the need to pad sequences to a fixed maximum length, and this wastes compute and degrades throughput. Predicting output lengths in advance makes it possible to adopt length-aware scheduling, and this reduces the overhead. This advantage is especially pronounced in long-context reasoning and reinforcement learning applications. Existing approaches, such as entropy-guided token pooling, use token-wise entropy as their primary signal, but they tend to ignore differences in semantic content across tokens. So, important tokens are often underweighted, and tokens carrying little information receive disproportionate emphasis. This hurts the reliability of length prediction. We introduce ESTP (Entropy-and-Semantic Token Pooling), a lightweight framework that addresses this issue by combining entropy with attention-based importance scores. These scores are derived directly from the self-attention weights computed during the LLM prefill phase, and t

---

### [136] When Do LLMs Apply the Wrong Law? Diagnosing LLM Failures in Temporal Legal Reasoning

**链接**: https://arxiv.org/abs/2608.14610
**作者**: Yiqian Huang, Shuyuan Zheng, Qianying Liu, Shaowen Peng, Yuntao Kong, Kotaro Funakoshi 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Legal reasoning tasks such as legal judgment prediction (LJP) require identifying the temporally correct version of the law governing a case -- a capability we term temporal applicable-law determination. However, whether large language models (LLMs) can reliably perform this task remains unexplored. In this paper, we construct a benchmark to evaluate LLMs on temporal applicable-law determination, and systematically investigate why they fail at temporal legal reasoning. Our experiments reveal four key findings. First, LLMs exhibit a strong bias toward applying the most recently enacted law, regardless of when the legally relevant facts occurred. Second, this bias does not stem from an inability to understand that laws have temporal scope, nor from a lack of knowledge about historical statutes. Third, we provide behavioral evidence that reinforcement-learning-shaped explicit reasoning may be a key mechanism: while improving general reasoning ability, it reduces the diversity of reasoning

---

### [137] LACE-SVD: Loss-Aware SVD with Cumulative Error Correction for LLM Compression

**链接**: https://arxiv.org/abs/2607.03057
**作者**: Zhuowen Liu, Longkun Hao, Shiyu Feng, Xiaowen Chang, Ruiqun Li, Changqun Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [138] EvoTS-Agent: A Self-Evolving LLM Agent for Financial Time Series Change Point Detection

**链接**: https://arxiv.org/abs/2608.17933
**作者**: Lei Jiang, Ye Wei, Xinyu Xi, Jordan Langham-Lopez, Yifan Bao, Raad Khraishi 等 (10 人)
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial time series exhibit non-stationary and heterogeneous statistical properties, making change-point detection challenging because no single unsupervised algorithm performs consistently across assets and market regimes. Conventional workflows consequently depend heavily on expert-driven model selection, feature design, and hyperparameter tuning, limiting their scalability and adaptability. We propose EvoTS-Agent, a validation-guided self-evolving LLM agent for autonomous financial time-series change-point detection. EvoTS-Agent first performs curated exploratory data analysis to characterize dataset properties and initialize candidate detection models. It then evolves executable experiment trajectories through three complementary operators: \textit{Revision} exploits the current best solution, \textit{Alternative Strategy} explores fundamentally different modeling directions when progress stagnates, and \textit{Recombination} synthesizes complementary evidence from high-performin

---

### [139] Enhancing the Non-Functional Quality Compliance of LLM-Generated Code through Quality-Aware Preference Learning

**链接**: https://arxiv.org/abs/2503.09020
**作者**: Liang Lu, Yuan Jiang, Christoph Treude, Shuzheng Gao, Jingyu Xiao, Xiaohong Su and Michael R. Lyu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [140] Rethinking Automated Program Repair: The Impact of Bug Complexity, Fault Localization, and LLM Cost-efficiency

**链接**: https://arxiv.org/abs/2608.14065
**作者**: Junchi Liu, Ali Bigdeli, Roya Daneshi, Atu Ambala, Sudipto Ghosh, Fabio Santos
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] A Contract-Grade Verifier for LLM-Generated GPU Kernels, and a Native Blackwell Backward for the Gated-Linear-Recurrence Family

**链接**: https://arxiv.org/abs/2608.12700
**作者**: Rishi Shah, Rishav Shrestha
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] Agent libOS: A Runtime Substrate for Capability-Controlled Self-Evolving LLM Agents

**链接**: https://arxiv.org/abs/2606.03895
**作者**: Yingqi Zhang
**来源**: cs.OS cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [143] Evaluating RL Explainability Methods by How Much They Help Fix Bugs in Agents

**链接**: https://arxiv.org/abs/2608.17524
**作者**: Ram Rachum, Yotam Amitai, B\'alint Gyevn\'ar, Reuth Mirsky, Cameron Allen
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This preliminary paper outlines a planned evaluation benchmark for Explainable Reinforcement Learning (XRL) methods. Current evaluations rely on functionally-grounded metrics like faithfulness and compactness, and on human-grounded proxies like subjective ratings or prediction accuracy. We suggest evaluating XRL methods by how effectively their generated explanations help to diagnose and fix malfunctioning reinforcement learning (RL) agents. We propose EvalXRL, a benchmark in which a Large Language Model (LLM) coding agent uses different XRL methods to diagnose a held-out malfunction in an RL agent, and then repair it. Our proposed benchmark iterates across (environment $\times$ malfunction $\times$ XRL method) tuples and uses the reward signal of the RL agents to form a final score for each XRL method. The coding agent may use the method interactively: invoke the XRL method, process its output, form new hypotheses on what is broken, and invoke the method again with parameters adjusted

---

### [144] Towards Architecting LLM -Based Systems

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11641143/&hl=zh-CN&sa=X&d=10221298675975497864&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-xHGYGPgwd-xOFqLWMnfTtY&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: G Belasco, P Delgado, V dos Santos, R Kazman… - 2026 IEEE 23rd …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -based systems can be organized, the architectural patterns adopted, and where the LLM components can be placed in … LLM -based systems are organized, including their patterns and the arrangement of LLM components. To this end, we

---

### [145] AudioTQ: A Data-Oblivious 6-Bit CPU Audio Codec via Randomized Hadamard Rotation and Lloyd-Max Quantization

**链接**: https://arxiv.org/abs/2608.15369
**作者**: Sahil Gangurde
**来源**: cs.SD cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lossy audio compression algorithms traditionally rely on psychoacoustic modeling and frequency-domain representations (e.g., MP3, AAC, and Opus) to discard information that is imperceptible to the human auditory system. While highly effective, these approaches are computationally complex and domain-specific. In this paper, we present the design and mathematical formulation of AudioTQ, a data-oblivious lossy audio codec that operates directly in the time domain. Inspired by Large Language Model (LLM) weight quantization techniques (specifically the TurboQuant framework), AudioTQ uniformizes volatile time-domain amplitudes into a predictable standard normal distribution using an orthonormal, randomized Fast Walsh-Hadamard Transform (FWHT) rotation. This enables coordinate-wise scalar quantization using an offline-trained, MSE-optimal 6-bit Lloyd-Max quantizer, augmented by a 1-bit Quantized Joint Least-Squares (QJL) residual correction layer. The resulting 7-bit virtual indices are packe

---

### [146] Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements

**链接**: https://arxiv.org/abs/2608.17310
**作者**: Zhi Zheng, Rongsheng Chen, Yunpeng Ba, Zhenkun Wang, Yee Whye Teh, Wee Sun Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement Learning (RL) has been promising in single-turn LLM fine-tuning. However, long-horizon agentic reasoning introduces increasingly branching interactions and sparse rewards, exposing several limitations of RL: its heavyweight backpropagation-based training stack makes it impractical to fine-tune larger LLMs, and longer-horizon trajectories make credit assignment in RL substantially harder. This paper argues that evolution strategies (ES) can be a better choice for fine-tuning long-horizon LLM agents. Compared with agentic RL, ES offers three key advantages: 1) Model Scalability: ES enables full-parameter optimization with only minimal, inference-level GPU memory, making it possible to fine-tune large LLMs. 2) Flexibility: its lightweight, black-box feedback interface makes ES fine-tuning easy to compose with prompt-space evolution (e.g., skill optimization & test-time compute); and 3) Long-Horizon Scalability: ES performs trajectory-level parameter attribution without decom

---

### [147] LLMs for Zero-Shot Threat Detection via Structured Risk Indicators

**链接**: https://arxiv.org/abs/2608.16508
**作者**: Abdullah Alghamdi, Siamak Layeghy and Marius Portmann
**来源**: cs.CR cs.LG cs.NI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose a two-stage large language model (LLM) framework for zero-shot detection of insider threats and advanced persistent threats (APTs) from heterogeneous security logs. The framework models user activity as chronological timelines and incorporates retrieval-augmented generation (RAG) to provide personalised behavioural context from each user's historical activity. Rather than performing end-to-end classification directly from raw logs, it first generates structured, interpretable sets of threat-specific risk indicators, which are then classified jointly across temporal sequences to capture attack patterns spanning multiple windows.The framework is evaluated on two benchmark datasets, CERT r5.2 for insider threat detection and PicoDomain for APT detection, using four combinations of two open-weight LLMs under both retrieval and non-retrieval settings. All configurations outperform the previous state-of-the-art LLM-based framework (GABM), with the best configuration improving the 

---

### [148] From Entity Mentions to Tone: An LLM-Based Pipeline for Media Bias Analysis

**链接**: https://arxiv.org/abs/2608.17454
**作者**: Klesti Hoxha, Olti Qirici
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents a pipeline for analyzing media bias and framing in online news. The pipeline groups articles into topics and events, adds named-entity and sentiment annotations, and compares news sources through people mentions, source-level tone, and event-level coverage patterns. We apply it to 8,358 Albanian news articles collected from GDELT and compare the resulting annotations with GDELT's automated annotations. The results show moderate agreement for sentiment and entity extraction, as well as additional person-entity pairs that can potentially support the bias analysis. We compare two annotation prompts and find that stricter sentiment-validation rules remove label-score inconsistencies but increase execution time and reduce annotation coverage. Based on these results, the simpler prompt is used for the rest of the analysis. We have provided sample analysis on source-level framing pro les, person-level tone differences across sources, and event-level gatekeeping and coverag

---

### [149] An LLM -Empowered Graph-Structured Collaborative Inference Framework for Logical Reading Comprehension

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11656339/&hl=zh-CN&sa=X&d=12054230740866291937&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-xnFIfrLmHCQCX-8Qe68x9J&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: Z Zhao, Z Xie, G Zhou, J Shen, JX Huang - IEEE Transactions on Audio, Speech and … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In summary, this study offers three principal contributions: • We introduce an LLM -empowered logic-oriented graph construction module, which guides the LLM to perform argument mining over the input text and extract logical units and logical relations

---

### [150] DA-RAC: Distance-Aware Calibration of LLM Judges for Trustworthy AI Auditing

**链接**: https://arxiv.org/abs/2608.14950
**作者**: Cheng Wu, Vishal Anand, Jaya Krishna Mandivarapu, Xiya Liu, Rui Zhuang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI systems are increasingly producing real-world artifacts, however their efficacy and validity are often evaluated via context-free LLM-scoring. These judges can be miscalibrated by irrelevant in-context reference examples, creating false confidence and allowing low-quality or harmful outputs to pass evaluation. We study this failure mode as context-induced miscalibration and introduce DA-RAC, a distance-aware reference-anchored calibration method for LLM judges. DA-RAC retrieves semantically and structurally similar labeled anchors for each judgement scenario, weights them by distance, and exposes neighborhood difficulty as a calibration and triage signal. On multi-run LLM-judge evaluation benchmarks, it improves calibration and reduces false-pass risk relative to zero-shot, chain-of-thought evaluation, and static-anchor baselines. Mechanistic analysis shows that judge scores vary systematically with anchor distance, while static references can induce misleading decision b

---

### [151] Limits to scalable evaluation at the frontier: LLM as Judge won't beat twice the data

**链接**: https://arxiv.org/abs/2410.13341
**作者**: Florian E. Dorner, Vivian Y. Nastl, Moritz Hardt
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [152] Effect of Abstractions and Prompting Strategies on LLM-Guided High-Performance Optimizations

**链接**: https://arxiv.org/abs/2608.08085
**作者**: Ji\v{r}\'i Klepl, Maty\'a\v{s} Brabec, Martin Kruli\v{s}
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] EgoGazeLite: On-Device Egocentric Gaze Prediction for Token-Efficient Multimodal LLM Video Input

**链接**: https://arxiv.org/abs/2608.15614
**作者**: Matteo Stoiber, Niels Buus Lassen
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The use of multimodal LLMs (MLLMs) for egocentric video understanding with wearable devices is constrained by the token budget. Memory and compute cost scale with the number of visual tokens, and high-resolution video quickly becomes expensive to transmit and process at scale. Prior work (GazeLLM) addresses this by cropping the video around the camera wearer's gaze. This reduces the number of visual tokens by about tenfold while maintaining or improving the quality of full-resolution descriptions. However, this compression strategy depends on dedicated eye-tracking hardware, which is unavailable on consumer smart glasses. Building a software-only substitute poses a joint constraint: the predictor must be accurate enough to preserve downstream description quality, yet light enough to run on-device, within the power and compute budget of a smartphone. We address this with EgoGazeLite, a lightweight dual-process gaze predictor for egocentric video. Across two MLLMs, three automated metric

---

### [154] LLM-Based Hierarchical Coordinated Control with Continuation-Aware Policy Learning

**链接**: https://arxiv.org/abs/2608.15041
**作者**: Changhong He, Jinda Gao, Xinkuan Liu, Le Zhang, Xizi Luo, Yu Mei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coordinating multiple interacting units in complex engineering systems is challenging when system interactions are difficult to model, operational information is heterogeneous, and low-level actions must satisfy strict constraints. We propose an LLM-based hierarchical framework in which the LLM coordinates interacting units based on heterogeneous operational context, while task-specific controllers or optimizers generate executable and constraint-aware actions. We further introduce Continuation-Aware GRPO to capture the consequences of coordination decisions over subsequent control intervals. Rather than judging a decision only by its immediate outcome, the method also evaluates how the system evolves afterward under the current policy. We validate the framework on multi-ramp traffic control and virtual power plant (VPP) energy management, using simplified system models for training and more realistic simulators for evaluation. Across both tasks, the proposed method consistently outper

---

### [155] The Hallucination Snowball: Modeling Error Propagation as State Transitions in Multi-Agent LLM Pipelines

**链接**: https://arxiv.org/abs/2608.14588
**作者**: Prabhjot Singh, Bhushan Pawar
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sequential multi-agent LLM pipelines chain specialized agents without verification at handoffs, creating a structural flaw with measurable and severe consequences. We show that hallucinations injected at Stage 1 do not merely persist; they transform: raw numerical facts become derived computations, then narrative prose, then editorially approved conclusions. At each transformation, detectability degrades near-irreversibly. We formalize this as the hallucination snowball effect, a first-order Markov process over four states (Raw Fact $\to$ Derived $\to$ Narrative $\to$ Invisible) with empirically measured per-boundary escape probabilities of 24.6%, 48.3%, and 89.3%. Across 346 automatically injected hallucinations in a 4-agent financial analysis pipeline on FinanceBench, gpt-4o detection drops from 72.0% at Stage 1 to 50.9% at Stage 4, and 23.7% of hallucinations survive completely undetected in the final output. Even the strongest model tested (Qwen3.5-397B-A17B, 87.0% at Stage 1) face

---

### [156] CompoSkill: Compositional Skill Chain Attacks from Individually Scanner-Passing LLM Agent Skills

**链接**: https://arxiv.org/abs/2608.16246
**作者**: Mingxiao Liu, Zhoumian Jiang, Jianan Ma, Jian Zhang, Jialuo Chen, Xinhao Deng 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous AI agents tackling Long Horizon Tasks depend on marketplace skills that are certified one at a time: a scanner returns a safety verdict for each skill and declares the ecosystem safe if every package passes. We show that this assumption fails under skill composition. A skill may pass the per-skill scanner individually yet participate in a risky composition when an agent connects its outputs, capabilities, or side effects with those of other scanner-passing skills. This makes skill composition risk a path level property rather than a node level property, explaining why existing skill scanners that inspect individual packages achieve limited interception. To study this threat, we present CompoSkill, a framework that constructs skill composition attacks through a dual attacker system. The white-box attacker knows the victim's installed skill pool and directly injects explicit skill-id sequences; the black-box attacker knows only a role profile, downloads the top marketplace ski

---

### [157] CAPO: Constraint-Aware Prompt Optimization for LLM Agents

**链接**: https://arxiv.org/abs/2608.16068
**作者**: Victor Ye Dong, Reid Pryzant, Yi Liu, Jian Jiao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as agents that rely on system prompts to use tools and complete tasks. Such deployments impose distinct operational requirements, including appropriate tool use, concise prompts and solution paths, and compliance with safety and formatting policies. For many practitioners, however, assembling domain-specific supervised data to post-train models to meet these requirements is infeasible. We introduce CAPO (Constraint-Aware Prompt Optimization), a primal-dual method that combines pool-based rewrites with adaptive constraint weighting to optimize system prompts under explicit operational constraints. Across agentic benchmarks, CAPO more reliably reaches empirically feasible operating points while improving task performance. CAPO also generalizes beyond agentic settings, achieving strong results on assistant-style evaluations with output-format and safety/privacy constraints. We further introduce DCAPO (Dynamically Trained CAPO), which 

---

### [158] KnowSim: Evaluating Information Calibration in LLM Assistants with User Simulators that Learn

**链接**: https://arxiv.org/abs/2608.17150
**作者**: Yoonjoo Lee, Hyoungwook Jin, Tae Soo Kim, Shaoyang Zhang, Philippe Laban, Q. Vera Liao
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To effectively collaborate with users on knowledge-intensive tasks, Large Language Models (LLMs) must perform information calibration: matching content to a user's evolving understanding and cognitive capacity. Yet user simulators used to evaluate and train LLMs do not explicitly model user knowledge so they neither produce realistic interactions across knowledge levels nor reflect how interactions unfold as that knowledge evolves. To close this gap, we introduce KNOWSIM, an evaluation framework built around a user simulator that maintains explicit knowledge states, represented as a graph of Information Units with prerequisite relationships, that evolve under update rules grounded in learning theory. KNOWSIM computes three metrics (Knowledge Gain, Delivery Calibration, Cognitive Overload) directly from the knowledge state trajectory, reflecting key mechanistic aspects of information calibration. We validate KNOWSIM against 705 human-AI sessions across two domains, stratified by knowled

---

### [159] Appearing Legitimate is Not Enough: Interrogating Synthetic Agents in Representational Processes through a Participatory Design Lens

**链接**: https://arxiv.org/abs/2608.17099
**作者**: Aditya Nayak, Aditi Vashistha, Alissa Centivany, Aakash Gautam
**来源**: cs.HC cs.CY
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic agents built atop LLM-based foundation models are gaining popularity as substitutes for human participants across research contexts, including user-testing, market-research, computational social science, surveys, and qualitative research. We are also witnessing an extension of synthetic agents into experimental implementations of policy consultation, jury deliberation, humanitarian diplomacy, and similar contexts where human participation and representation are central to the perceived legitimacy of the institutional processes. The value of participation extends beyond informational contributions and consensus generation; participation is a necessary, legitimizing condition for democratic political institutions and processes. Treating synthetic agents as human substitutes raises serious political, representational, and ethical concerns. Participatory Design's modes of engagement --- probing, priming, understanding, and generating --- offer helpful tools for engaging with repr

---

### [160] Sequential LLM Release Facilitates Manipulation in Regulated Markets

**链接**: https://arxiv.org/abs/2601.11496
**作者**: Eilam Shapira, Moshe Tennenholtz, Roi Reichart
**来源**: cs.GT cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [161] EcoReason: A Graph-Guided Evolutionary and Negative-Aware Reinforcement Learning Framework for LLM Commonsense Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11656343/&hl=zh-CN&sa=X&d=17527730026974273979&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-xy_h2N25vbADnxgxBCOHVO&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: X Guan, J Cao, B Cao, Q Gao, B Liu - IEEE Transactions on Audio, Speech and … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We then employ a Teacher LLM to synthesize constraintheavy scenarios that specifically target the student’s current reasoning blind spots… target Student LLM (πθ) to master advanced commonsense reasoning by leveraging a Commonsense KG G

---

### [162] CityReal: Human-Aligned Urban Behavior and City Dynamics Simulation with Large-Scale LLM Agents

**链接**: https://arxiv.org/abs/2608.16897
**作者**: Nicolas Bougie, Xiaotong Ye, and Narimasa Watanabe
**来源**: physics.soc-ph cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale urban simulation plays a pivotal role in social science, traffic safety, and transportation policy. Recent work has shown that large language models, when prompted as agents, can generate lifelike daily routines at city scale. Yet these methods typically rely on few-shot prompting, causing agents to reproduce the LLM's behavioral priors rather than the target population. We introduce CityReal, a modular framework for human-aligned urban simulation. CityReal models agents as intention-driven decision makers that pursue coherent mobility and activity plans rather than isolated step-by-step choices. They adapt over time by learning habits and preferences based on experience and constraints. To improve population-level realism, we learn textual adapters for behavior modules that align agent decisions with observed population statistics. Experiments show that CityReal improves alignment with real-world human behavior at both micro and macro levels. Scaling to tens of thousands o

---

### [163] A validity-guided workflow for robust large language model research in psychology

**链接**: https://arxiv.org/abs/2507.04491
**作者**: Zhicheng Lin
**来源**: cs.HC cs.AI cs.CL cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] The Value of a Prompt: An LLM-Relative Kolmogorov-Complexity Approach

**链接**: https://arxiv.org/abs/2608.16438
**作者**: Rafael Pass
**来源**: cs.AI cs.CC cs.IT math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In a world where valuable artifacts are increasingly created, completed, or processed by LLMs, the central economic question is not only what the LLM can produce, but what \emph{value} remains in the inputs (i.e., the prompts) we provide to it. Given a prompt, hint, critique, problem statement, or partial solution that helps an LLM produce an artifact $z$---a proof, program, design, or scientific hypothesis---how should we measure the value of that input? Intuitively, an input is valuable when it makes the target artifact easier for the model to generate: either by increasing its sampling probability, or by reducing the thinking time needed to find it. We propose a computational Levin--Kolmogorov complexity approach to this problem, by appropriately replacing the universal Turing machine in the classical definitions by the LLM itself. Concretely, we introduce an LLM-relative notion of \emph{probabilistic Levin--Kolmogorov complexity} $pKt$---treating the model's thinking as the random 

---

### [165] Do LLMs Know a Good Hypothesis When They See One? Logit-Based Energy Scoring Outperforms Prompted LLM-as-Judge for Scientific Hypothesis Ranking

**链接**: https://arxiv.org/abs/2608.17270
**作者**: Swati Rajwal, Sanjay Das, Tirthankar Ghosal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for scientific hypothesis generation. However, evaluating generated hypotheses remains a challenge for trustworthy AI-enabled scientific workflows. Existing approaches often use LLMs as judges or rely on semantic similarity, which can favor familiar ideas over novel ones. We propose a logit-based energy scoring method that evaluates hypotheses using a language model's intrinsic confidence rather than comparative judgment. We benchmarked seven language models on 1,323 papers across 12 disciplines. Each paper was paired with its hypothesis and fifteen incorrect alternatives. Intrinsic scoring reached 33.0% Hit@1 pooled across both scorers, compared with 16.6% for prompted listwise ranking. The strongest configuration, a 1-billion-parameter model using logit-based energy scoring, reached 53.1%, though this was the maximum across 14 model-by-scorer combinations selected post hoc. Overall, intrinsic model confidence shows potential for scie

---

### [166] ReLoop: Structured Modeling and Behavioral Verification for Reliable LLM-Based Optimization

**链接**: https://arxiv.org/abs/2602.15983
**作者**: Junbo Jacob Lian, Yujun Sun, Huiling Chen, Chaoyu Zhang, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.SE cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] Ask to Be Sure: Informative Interactions for Confident Multi-Turn LLM Recommendation

**链接**: https://arxiv.org/abs/2608.15949
**作者**: Cedar Site Bai, Duanshun Li, Zhenyu Liao, Sheikh Sarwar, Huiyuan Chen, Yuan Chen 等 (9 人)
**来源**: cs.IR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) have enabled their use as conversational recommender systems (CRS), demonstrating strong recommendation accuracy and natural dialogue. However, guiding multi-turn interactions to elicit user preferences effectively remains challenging. Existing approaches either use separate reinforcement learning agents with templated interactions or optimize for interactivity judged by another LLM, without measuring how much useful information is actually gained. We propose a new approach that quantifies the effectiveness of each interaction by the reduction in the assistant's uncertainty, measured via entropy over recommendations. We apply this entropy reduction as a reward---without relying on ground-truth recommendations, which are often unavailable in real-world scenarios---to fine-tune the LLM, enabling strategic interaction generation. Empirical results with supervised fine-tuning (SFT) and direct preference optimization (DPO) on the INSPIRED and 

---

### [168] Broken Symmetry in LLM Refusal: Answer Release Is More Local Than Refusal Restoration

**链接**: https://arxiv.org/abs/2608.15772
**作者**: Yiqi Liu, Yang Wang, Songxin Wang, Chenghao Xiao, Chenghua Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a language model refuses to answer a prompt, it is unclear whether the correct answer is erased from its internal representations, or merely suppressed at the output layer. We investigate this mechanism using a controlled withhold setting, which yields perfectly matched answering and refusal trajectories for bidirectional activation patching. We uncover a causal asymmetry in intervention locality under matched causal interventions, which we term broken symmetry. Even when a model generates a clean refusal, the correct answer remains linearly recoverable from its hidden states. Furthermore, releasing this withheld answer is a highly local operation, requiring only a single-position patch. Conversely, the reverse operation is not equally local: reimposing suppression requires broader interventions across multiple positions, and assembling a coherent refusal sequence is more difficult still. We further demonstrate that while an average answer-to-refusal displacement vector marks the 

---

### [169] PCA-guided Activation Scaling for Monotonic Bidirectional Control over LLM Sycophancy

**链接**: https://arxiv.org/abs/2608.16650
**作者**: Zheng Chen, Zhaoxin Feng, Yip Tin Po, Jianfei Ma, Emmanuele Chersoni, Bo Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) exhibit sycophancy, a tendency to agree with user beliefs regardless of factual accuracy. This can reinforce misconceptions, but eliminating it entirely risks over-correction against valid opinions. Effective control must therefore both reduce and increase sycophancy with predictable and gradual effect. Yet, existing methods fail to ensure a bidirectional and monotonic relationship between steering strength and behavioral outcome across models and datasets. We introduce PCA-guided Activation Scaling (PAS), an activation steering framework that decomposes residual stream activations into a PCA-identified sycophancy-honesty subspace and an orthogonal residual, then applies distinct scaling exponents to achieve monotonic, bidirectional control. Across three LLMs and three datasets, PAS achieves strong monotonicity (Spearman $\rho$ = +0.92) and an average shift of 15.4% per direction, compared with 8.7% for the baselines. Ablation studies confirm that the decom

---

### [170] Single-Round Vector RAG vs an LLM-Compiled Wiki: A Preregistered Comparison on a Small Multi-Domain Research Corpus

**链接**: https://arxiv.org/abs/2605.18490
**作者**: Theodore O. Cochran
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] PDDLCoder: Agentic PDDL Generation for LLM-Assisted Symbolic Planning

**链接**: https://arxiv.org/abs/2608.16637
**作者**: Veit Laule, Jiangtao Shuai, Manfred Hauswirth, Sonja Schimmler
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs remain unreliable for long-horizon planning, often generating logically inconsistent or non-applicable plans. Recent hybrid methods instead translate natural language into the Planning Domain Definition Language (PDDL), allowing symbolic planners to produce verifiable plans. However, existing methods frequently rely on rigid generation pipelines, a partial PDDL definition, or human feedback. Furthermore, their evaluation is hindered by the lack of standardized benchmarks with automated verification. To address these limitations, we present PDDLCoder, an agentic framework for PDDL generation from natural language that iteratively generates, analyzes, and refines planning specifications. We further introduce NL-pddlgym, a benchmark dataset comprising 711 planning problems across 23 domains with executable gym environments for the automated verification of plan applicability. Experiments on the NL-pddlgym test set containing 106 problems across 4 held-out domains show that PDDLCoder 

---

### [172] Topological Attribution Distance (TAD): Revealing Segment-Level RAG Influence on LLM Output Geometry for Incident Log Analysis

**链接**: https://arxiv.org/abs/2608.16775
**作者**: Reza Fayyazi, Michael Zuzak, Shanchieh Jay Yang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly being deployed in cybersecurity operations to assist cybersecurity analysts with rapid decision-making against emerging threats. However, there is a main criteria that must be met when using LLMs in cybersecurity, that is, trust in the generated outputs. As Agentic AI is integrated into operational systems, a robust evidence attribution and provenance tracking technique is essential to trace the origins of model generations. When autonomous agents make a decision (right or wrong), the ability to trace back through the decision chain is critical, as without it, teams cannot identify which segment of the data caused the model generation. Existing methods often struggle to distinguish among complex and highly similar evidence sources, such as cyber incident logs. This reveals a key gap: current approaches do not adequately capture the holistic geometric relationship between the retrieved evidence and the generated response for reliable evidenc

---

### [173] LCFND: OT–guided LLM evidence reasoning and graph verification for multimodal fake news detection

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44443-026-01047-0&hl=zh-CN&sa=X&d=10031845348636221145&ei=rmqEapnuO7ec6rQP4KammAQ&scisig=AIVdB-zcjRLHnvIatWF8WnpqGovx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: Y Zhang, H Jin, Y Wang, B Wei, M Zhang - Journal of King Saud University Computer …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We design an evidence-grounded LLM supervision strategy in which the LLM is trained to generate structured evidence rather than fake/… We develop a heterogeneous evidence graph with reproducible instantiation rules that integrates

---

### [174] Policy-Invariant Reward Shaping from LLM Feedback: A Framework for Hybrid RL Agents

**链接**: https://arxiv.org/abs/2608.18008
**作者**: Christophe D. Hounwanou, John Emeka Eze, Ya\'e U. Gaba
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Combining large language models with reinforcement learning is increasingly explored, yet the theoretical status of LLM-derived reward signals is often left implicit. We formalize the hybrid LLM-planner and RL-controller architecture as a Goal-Augmented Markov Decision Process and show that when the LLM per-state progress score is used as a bounded potential function, the resulting shaping term preserves the optimal policy set even when the LLM scores are inaccurate. This guarantee is stronger than what general LLM-as-reward approaches provide. We verify the result numerically on a small MDP under four potential configurations, including an adversarial one scaled to twenty times the base reward magnitude.

---

### [175] An Empirical Study of Reward Specification and Benchmark Reliability in GRPO-based LLM Unlearning

**链接**: https://arxiv.org/abs/2608.17804
**作者**: Rub\'en Balbastre, Juan Manuel Ordu\~na, Mariano P\'erez
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practical LLM unlearning is usually evaluated through two objectives: suppress target-specific knowledge and preserve non-target utility. In generative QA, this leaves a third behavior underspecified: when a target-adjacent prompt admits a broader answer without target-specific leakage, the model should answer at that level rather than leak, evade, or refuse. We study this specification problem in a controlled LoRA-GRPO RWKU setting, comparing four reward designs that span lexical suppression, anti-refusal shaping, rubric-based broad answering, and an explicit refusal contrast, with and without SFT warm-up. The experiments show that optimization success is not equivalent to behavioral unlearning: RWKU forget scores, held-out completion audits, terminal training-rollout audits, and training dynamics can point to different conclusions. We trace these disagreements to reward-hacking endpoints, policy-support limits in GRPO, benchmark probes that miss endpoint changes, and rewards that can

---

### [176] Constraint-Aware Synthetic Tabular Data Generation via Inter-Column Constraint Discovery with LLM Agents

**链接**: https://arxiv.org/abs/2608.15109
**作者**: Jianxing Zhao, Mao Guan, Dongyu Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating structurally valid synthetic tabular data remains difficult: outputs with high statistical fidelity and downstream utility can still violate semantically meaningful domain constraints. We study the discovery and enforcement of three complementary inter-column constraint families---equations, linear inequalities, and logical dependencies. Our unified tool-grounded workflow represents all three as machine-executable hypotheses and applies a common interface for full-table validation, deterministic diagnosis, and counterexample-guided revision. A generator-agnostic postprocessor coordinates family-specific repairs on outputs from unchanged tabular generators. Across curated behavioral audits and end-to-end evaluations, the complete workflow improves held-out violation detection over one-shot direct prompting, while postprocessing yields zero measured violations for every retained, applicable constraint, improves downstream utility on most datasets, and largely preserves univari

---

### [177] PLSQLBench: Benchmarking LLM Systems for Executable Procedural Database Programming

**链接**: https://arxiv.org/abs/2608.15931
**作者**: Marianne Menglin Liu, Leonid Boytsov, Daniel W. Peterson, Pramuditha Perera, Rongguang Wang, Sai Ashish Somayajula 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present PLSQLBench, to our knowledge the first benchmark for evaluating whether LLMs can write executable PL/SQL programs, with correctness measured through execution-based tests. Existing LLM evaluations largely target general-purpose code generation or declarative text-to-SQL, leaving procedural database programming underexplored. PLSQLBench contains 2,865 instances: 2,594 single-turn tasks and 271 multi-turn conversations spanning 978 turns. The benchmark combines complex schema-grounded tasks over enterprise-style Spider 2 databases, simpler schema-grounded tasks derived from Spider, and MBPP-derived procedural problems, covering varying levels of database grounding and procedural complexity. Experiments with eight LLMs reveal recurring difficulties in schema grounding, PL/SQL dialect fidelity, procedural control flow, exception handling, and cross-turn consistency. Tool-augmented LLM agents improve performance on several schema-grounded evaluations, although substantial gaps re

---

### [178] Probing the Prefill: Detecting Code Vulnerabilities via Latent Activations

**链接**: https://arxiv.org/abs/2608.16970
**作者**: Alizishaan Khatri
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based code generation is now embedded in mission-critical pipelines, but defenses against vulnerable output remain post-hoc -- static analyzers, fine-tuned classifiers, or an LLM judge that screen completed code, ignoring the generating model's own internal state. We test a narrower, directly measurable question: when an LLM reads a piece of C/C++ code as context, do its hidden activations already carry a signal about that code's vulnerability status? We extract last prefill token activations from four LLMs (Granite-4.1-8B, Qwen3.5-9B, Qwen3.6-27B, Gemma-4-12B) across three model families and train MLP probes on these activations. We evaluate them on four function-level C/C++ benchmarks (Devign, Big-Vul, Draper VDISC, PrimeVul). Our probes achieve 41.7\% average F1 using 13.4--16.0M-parameter probes -- under 0.2\% of base-model size. On Devign, the best probe (Qwen3.5-9B, 68.8\% F1) matches the published fine-tuned-classifier SOTA (67.9\%) despite reading only a frozen, general-pur

---

### [179] Beyond FLOPs: Energy-Aware Knowledge Distillation for Sustainable LLMs on Code-Related Task

**链接**: https://arxiv.org/abs/2608.17515
**作者**: Enrique Barba Roque, Lu\'is Cruz, Annibale Panichella
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Large Language Models (LLMs) are increasingly being applied to Software Engineering (SE) tasks, achieving high accuracy across problems such as clone detection, vulnerability prediction, and code summarization. However, their high computational demands and energy consumption raise sustainability concerns and hinder their use on consumer hardware and resource-constrained platforms. A common way to report the computational cost of an LLM in the literature and industry is to use the number of Floating Point Operations (FLOPs) required to perform a pass over the network. Aims: This paper investigates the implications of energy-aware knowledge distillation for SE, aiming to improve model efficiency while maintaining performance and to determine whether FLOPs is a reliable energy-aware metric. Method: We conduct a controlled experiment using Morph, a Many-Objective Optimization-based distillation methodology, to empirically examine whether FLOPs accurately reflect energy consumpt

---

### [180] Structure-Internalized Rule Language Model for Faithful Knowledge Graph Reasoning

**链接**: https://arxiv.org/abs/2608.17443
**作者**: Xingrui Zhuo, Jiapu Wang, Manzong Huang, Gongqing Wu, Xindong Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge Graph Reasoning (KGR) aims to discover latent facts by leveraging the structural evidence available in KGs, posing a challenge to the structural semantic understanding capability of KGR models. Recent studies have demonstrated that Large Language Models (LLMs) can achieve remarkable progress on KGR tasks via flexible in-context learning. However, the inherent representation inconsistency between KG structural context and LLM parametric knowledge remains inadequately addressed. This limitation prevents LLMs from effectively perceiving reasoning evidence that aligns with KG constraints, which undermines both the effectiveness and faithfulness of reasoning. We refer to this problem as reasoning evidence perception drift of LLMs over KGs. To address this problem, we propose a Structure-Internalized Rule Language Model (SIRLM), which centers on structural rule generation to couple the parametric learning of structural knowledge with the faithfulness evaluation of reasoning logic, 

---

### [181] Agent Lightning v1.0: Towards Harnessed Agentic RL

**链接**: https://arxiv.org/abs/2608.17528
**作者**: Zhiyuan He, Siwei Zhang, Zhiwen Zhou, Yuqing Yang, Yu Kang, Yuge Zhang 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern agents operate inside agent harnesses that manage tools, context, and control flow, making the harness a critical part of the agent system. Our original Agent Lightning introduced a disaggregated architecture that connects arbitrary agents to RL training through an LLM endpoint proxy, an approach later adopted by frameworks such as verl Uni-Agent, AReaL 2.0, slime, and Polar. We refer to this paradigm as harnessed agentic RL, where the deploy-time harness directly participates in model post-training. Harnessed agentic RL differs fundamentally from traditional agentic RL: the harness, rather than the training engine, owns the environment interaction loop, while the trainer observes only sequences of LLM request-response pairs. This introduces challenges in retokenization, sample merging, advantage calculation, loss normalization, and backend scheduling, which can substantially affect training stability and effectiveness. We present Agent Lightning v1.0, a lightweight framework fo

---

### [182] Towards Risk-free AI Agent Deployment

**链接**: https://arxiv.org/abs/2608.16411
**作者**: Yintong Huo, Rangeet Pan, Abhik Roychoudhury
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are rapidly moving from research prototypes into the core business processes of organizations, but these agents pose deployment risks to security, compliance, and functionality. In this article, we argue that risk-free deployment must be grounded in the agent's trajectory: the recorded sequence of reasoning steps, tool invocations, and environmental observations. Trajectories are available for any agent, and many failures are visible only in the trajectory. To make agents deployable and sustainable, we advocate agent testing and debugging as a systematic research direction for detecting and mitigating these risks. This article begins with the challenges of testing agents, including the oracle problem, non-determinism, trajectory validation, and the absence of adequacy metrics. We then turn to debugging agents, from automated failure attribution to repair and self-evolution. We distill these directions into a practical deployment-readiness checklist covering the full de

---

### [183] Learning Agent Execution for KV-Cache Management in Agentic Serving

**链接**: https://arxiv.org/abs/2608.14624
**作者**: Rui Zhang, Chaeeun Kim, Shaoting Feng, Kuntai Du, Yuhan Liu, Yi Zhong 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems have emerged as an important deployment paradigm for AI services, where each user request is decomposed into a sequence of specialized agents. Across these workflows, every agent repeatedly executes a fixed context consisting of system prompts, tool definitions, and few-shot examples, creating substantial opportunities for KV-cache reuse. Existing LLM serving systems, however, manage KV-cache reactively using prefix caching and recency-based replacement, causing reusable agent contexts to be evicted before their next invocation and forcing repeated recomputation. We present CacheScout, an agent-aware KV-cache runtime layer for multi-agent LLM serving. The key insight is that future KV-cache reuse is governed by agent execution semantics rather than cache recency alone. CacheScout captures these semantics by learning agent execution transitions online, without requiring predefined workflow graphs or offline training, and uses the learned execution model to guide 

---

### [184] Debate Training Reduces Reward Hacking in RLAIF

**链接**: https://arxiv.org/abs/2608.17776
**作者**: Zachary Kenton, Lili Janzer, Rory Greig, Tian Huey Teh, Kirill Tyshchuk, Jonah Brown-Cohen 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We demonstrate that RL finetuning an LLM using debate, a two-player adversarial game between a generator and a critic adjudicated by a weaker LLM judge, reduces reward hacking compared to a reinforcement learning from AI feedback (RLAIF) baseline. Reward hacking is a central obstacle in RLAIF: as training progresses, the policy learns to exploit systematic errors in its AI judge, degrading task performance, a problem that worsens precisely when the judge is weaker than the policy, the setting most relevant to overseeing increasingly capable AI systems. We study mathematics tasks, where final-answer correctness is verifiable, allowing us to measure reward hacking dynamics. We train a Gemini~2.5 Flash-class policy with a frozen, weaker Gemini~2.5 Flash Lite judge, comparing a single-player RLAIF baseline against debate. While the baseline quickly hacks the judge, debate maintains judge performance throughout training, leading to a higher peak validation accuracy (45\% performance gap rec

---

### [185] PACE: Policy-Attested Contract Execution for Safe AI Agents in Decentralized Finance

**链接**: https://arxiv.org/abs/2608.17220
**作者**: Rabimba Karanjai, Yang Lu, Richard Williamson, Hemanth Hm, Prakhar Mehrotra, Lei Xu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous AI agents are emerging as interfaces for decentralized finance (DeFi) actions such as swaps, lending operations, and yield management. Because these agents rely on large language models (LLMs) to plan transactions, they inherit the LLM's susceptibility to prompt injection and lack of mechanisms to bind a verifier's approval to the exact transaction ultimately submitted on-chain. We present PACE (Policy-Attested Contract Execution), a transaction-level authorization framework that interposes between an LLM-based agent and on-chain execution. PACE introduces typed transaction intents, a deterministic policy verifier, and signed Policy Decision Records (PDRs) that cryptographically bind the approved intent, policy, and simulation report to the exact execution bytes, with replay and expiration protection. A Solidity smart account enforces PDR signatures on-chain with a measured overhead of 29,826-31,822 gas. We evaluate PACE against six baselines on 40 tasks spanning four attack

---

### [186] An Omitted Mode Is a Rare Rule: The Sampling-Verification Danger Law in Continuous Code World Models

**链接**: https://arxiv.org/abs/2608.17956
**作者**: Javier Aguilar Mart\'in
**来源**: cs.LG cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the Code World Model paradigm an LLM synthesizes an executable world model that a classical planner searches, and the model is accepted when it reproduces sampled transitions. We ask what that acceptance certifies in continuous control. We define the pipeline's danger as an expected risk and isolate its exact factor: the probability that N i.i.d. gate rollouts all miss a critical event of probability r is exactly (1-r)^N; an independent acceptance sample adds its budget to the exponent. On three hybrid instruments the accepted mode-blind model is exploited: the planner is pinned at the mode boundary at a regret of nearly the whole attainable return. We prove a localization budget, valid at boundary points: models with Lipschitz constant at most L differing by eta at a point disagree above tolerance eps on a region of volume at least kappa((eta-eps)/L)^(d+m); the discontinuous reset modes studied pay no such budget. With real LLM synthesis, GPT-5.x repairs an omitted 1D clamp in 105 

---

### [187] RamseyGadgets: A Graph Construction Dataset for LLMs

**链接**: https://arxiv.org/abs/2608.14999
**作者**: Zohair Raza Hassan, Deepak Pandita
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constructing special graphs is an important task within graph theory and computer science. Many popular graph constructions are the result of a comprehensive exploration of relevant graphs and human ingenuity. Given the rise of generative AI usage in mathematics, it is natural to test whether LLMs are able to construct graphs with specified properties using their reasoning capabilities. Unfortunately, many natural graph construction problems, such as finding extremal Ramsey-good graphs (i.e., avoiding specific monochromatic subgraphs), have been explored extensively in the literature, making it difficult to ascertain whether a construction is the product of an LLM's reasoning capabilities or its recollection from training data. In this work, we introduce \textbf{RamseyGadgets}, a novel dataset of 70 underexplored graph construction problems that require finding Ramsey-good graphs with special properties (e.g., containing an edge with a fixed color). These problems have reasonably sized

---

### [188] Kozuchi Agent: A Language-Agnostic Open-Weight Agent for Software Repair

**链接**: https://arxiv.org/abs/2608.15579
**作者**: Mehdi Bahrami, Kosaku Kimura, Satoshi Munakata, Satoshi Nakashima, Yu Ishikawa, Kosuke Maeda 等 (10 人)
**来源**: cs.SE cs.AI cs.ET cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial software-engineering teams increasingly need LLM agents that turn bug reports into correct patches, yet benchmark-scale operation adds long horizons, tool-use discipline, context persistence, heterogeneous clusters, and evaluation reuse. We present Kozuchi Agent, a language-agnostic open-weight repair agent and CI-operated evaluation pipeline. Explicit phases, persistent state, deterministic tools, a model-independent action interface, and cross-agent test-time selection make runs auditable and repeatable. With locally hosted Qwen3.5-27B, no fine-tuning, and TTS@8, Kozuchi resolves 374/500 SWE-bench Verified instances on the official evaluator. Unchanged on Multi-SWE-bench Java, the same 27-billion-parameter agent resolves 41/128 instances (32.03%), ranking first among strict open-weight submissions and fourth of 42 overall; on Python it ranks 12th of 135 and first among open-weight systems. Per-phase behavior remains within +/-5 percentage points across languages. Remaining

---

### [189] Calibrated Trust, Not Sharper Prediction: An Empirical Test of Uncertainty Fusion

**链接**: https://arxiv.org/abs/2608.14617
**作者**: Surya Saka
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A recurring proposal in legal AI is to improve case-outcome prediction by fusing uncertainty tools (evidence graphs with belief propagation, sequential Bayesian odds updating, Dempster-Shafer combination, and conformal prediction) into one pipeline. We test this on 1,000 real European Court of Human Rights cases from LexGLUE and FairLex, predicting whether the Court found a Convention violation from the case's fact paragraphs. We compare three families across two frontier LLMs (Claude Opus 4.8 and GPT-5.5) as per-fact evidence estimators: (A) the raw LLM, (B) the LLM routed through the fusion pipeline, and (C) a term-frequency baseline through the same pipeline. Across roughly 4,750 tests we find: (1) on discrimination (AUROC around 0.83) the pipeline yields no improvement over either the raw LLM or the baseline; a frontier LLM used directly is the strongest single discriminator. (2) Naively composing an LLM with Bayesian-odds and Dempster-Shafer fusion more than doubles calibration er

---

### [190] DEPT: Document Embedding Preservation Tuning for Unified Query Expansion and Retrieval

**链接**: https://arxiv.org/abs/2608.17632
**作者**: Jingyuan Wang, Richong Zhang, Zhijie Nie, Mingxin Li, Yanzhao Zhang
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can both expand underspecified queries and encode text as dense representations, suggesting a unified model for query expansion and retrieval. Existing systems usually rely on prompted expansions, independently trained modules, or staged optimization, leaving generated expansions only indirectly aligned with the retrieval loss that judges them. We train a single decoder-only LLM end to end, where the same model generates the expansion and encodes both the expanded query and candidate documents. This unified setting creates a moving-target problem: retrieval supervision should improve query-side expansion, but the same update also shifts the document embeddings that serve as retrieval targets. We introduce Document Embedding Preservation Tuning (DEPT), which keeps tuned document embeddings close to cached initial embeddings while allowing retrieval gradients to pass through straight-through decoding into the generator. DEPT converts joint query--document mov

---

### [191] Harness the Memory: A Holistic Evaluation of Memory Substrates in Memory Agents

**链接**: https://arxiv.org/abs/2608.15008
**作者**: Wei-Chieh Huang, Weizhi Zhang, Yuchen Wu, Yankai Chen, Eric Hanchen Jiang, Wooseong Yang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is becoming core infrastructure for long-horizon LLM agents, yet existing evaluations offer limited guidance on which memory substrate, namely the underlying medium in which memory is represented and stored, should be used under different operating regimes. We present a controlled harness evaluation of memory substrates for memory-augmented agents, covering dense and sparse indices, text records, structural stores, hierarchical stores, refinement-based memories, parametric updates, and activation-compatible context mechanisms. Across three backbone models and four benchmark suites spanning user-centric question answering and agent-centric decision-making, we instrument 26 performance and efficiency metrics under a unified harness. Our results show that no single substrate consistently dominates: broad retrieval benefits long-context factual QA, while excessive retrieval can harm sequential decision-making by shifting attention away from action-critical context. Scalability intro

---

### [192] A Human-Centred Approach to Benchmarking LLMs for Parenting Advice

**链接**: https://arxiv.org/abs/2608.14622
**作者**: Yunke Zhao and Isobel Voysey and Alastair van Heerden and Rob Hughes and Jun Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People are increasingly using large language models (LLMs) to seek advice, including for parenting. Parenting is a critical and socially sensitive domain. Thus, evaluating advice provided by LLMs requires indicators beyond aggregated information quality benchmarks to consider relational and behavioural elements of the responses. With a multi-dimensional rubric created by parenting experts, this paper evaluates 15 LLMs across 100 parenting scenarios in 2 languages (English and Chinese), using an LLM-as-a-judge method. Results show that aggregate scores can hide rubric item-specific weaknesses, models implicitly encourage different parenting styles, and language influences responses. We highlight the importance of evaluation output auditability and challenges involved in evaluating LLM-generated advice in domains like parenting. Our findings provide important insights for selecting LLMs for direct user engagement and the development of user-facing parenting advice applications.

---

### [193] ACTS-SQL: Agentic and Critic-Oriented Tree-Structured SQL Correctness with Large Language Models

**链接**: https://arxiv.org/abs/2608.15145
**作者**: Xinmei Huang, Jie Song, Peng Li, Fuxin Jiang, Jing Zhang, Tieying Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have been increasingly adopted in Text-to-SQL systems, yet SQL errors remain a major obstacle in real-world Text-to-SQL inference pipelines. Existing SQL correction approaches either rely on large-scale, high-quality training data with substantial overhead, or adopt single-path agentic workflows that are brittle to early mistakes and prone to error propagation. To develop a practical SQL correctness system for industrial scenarios, we present a training-free framework that formulates SQL correction as a plan-guided, tree-structured debugging process. By maintaining multiple correction strategies and enabling backtracking, the framework mitigates error accumulation during iterative refinement. We further integrate execution-based verification and clause-level diagnostic tools to support strategy pruning and precise error localization. We evaluate the system on the BIRD-Critic benchmark and observe consistent accuracy gains over strong LLM backbones and repre

---

### [194] Memory Tree Guided Key Frame Querying for Efficient 3D Question Answering

**链接**: https://arxiv.org/abs/2608.18009
**作者**: Hsiang-Wei Huang, Fu-Chen Chen, Li-Wu Tsao, Cheng-Han Lee, Che-Chun Su, Lu Xia 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Answering questions accurately and efficiently in embodied scenarios presents significant challenges due to limited computational and memory resources for Vision Language Model (VLM) inference. Existing methods adopt visual search key frame retrieval method to select critical question-related key frames for VLM input. However, visual search methods are inefficient because they require visual search among thousands of video frames for each individual user query. In this work, we propose a memory tree guided key frame selection paradigm for efficient 3D question answering in embodied scenarios. Our method leverages a compact and reusable 3D scene representation, termed MemTree3D, which supports real-time online construction leveraging camera 6-DoF poses. MemTree3D captures multi-level 3D scene information, enabling a Large Language Model to efficiently query and retrieve question-relevant key frames through our scoring-based frame selection without reprocessing the entire video stream. O

---

### [195] Do Large Language Models Play Six Degrees of Separation? Measuring Topological Compression in Long-Context Manifolds

**链接**: https://arxiv.org/abs/2608.17950
**作者**: Md. Faiyaz Abdullah Sayeedi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) demonstrate remarkable multi-hop reasoning capabilities over long contexts, yet the internal mechanisms enabling these distant cognitive leaps remain poorly understood. Traditional attention-based interpretability often fails to capture true semantic proximity due to routing artifacts like attention sinks. In this paper, we bypass attention weights to directly analyze the dynamic geometry of the hidden state manifold, proving that deep LLM latent spaces natively organize into Small-World networks. By sparsifying the continuous similarity matrices of long-context representations into unweighted graphs, we trace the connectivity between highly disjoint semantic anchors across two distinct architectures. Our findings reveal a sharp topological phase transition: while early syntactic layers remain entirely fractured, deep reasoning layers abruptly compress massive conceptual distances into highly navigable pathways strictly bounded by the "Six Degrees of Separa

---

### [196] Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory

**链接**: https://arxiv.org/abs/2608.16889
**作者**: Bingxin Xu, Yuzhang Shang, Emilio Ferrara
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon robot manipulation chains many contact-rich skills into one multi-stage task. Vision-language-action (VLA) models increasingly master the individual skills, yet the chain still fails: errors compound beyond the policy's ability to correct, and one subtask silently constrains the next. A promising recipe freezes the VLA and puts an LLM agent in charge: it plans in language, moves in free space with analytic primitives, invokes the VLA only for contact-rich segments, and writes adaptation into language memory. Applied to long horizons, it breaks twice. (1) Competence comes from whole-task exploration at test time, whose cost is multiplicative in stages: if one stage needs T episodes, a K-stage task needs about T^K, and a failure does not reveal which stage caused it. (2) It has no representation of transitions: the VLA primitive carries an exit but no entry condition, so a subtask can succeed in a form its successor cannot use. We present BATON. Against (1), BATON makes the 

---

### [197] D$^2$ACCI: A Dual-Loop Diagnostic Protocol for Evidence-Preserving Agent Memory

**链接**: https://arxiv.org/abs/2608.17756
**作者**: Xule Liu, Yijun Liu, Chao Li, Shao Kun
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is a key capability of LLM agents. Persistent memory extends this across sessions---enabling recall, revision, and personalization. Yet its multi-stage pipeline (ingestion, retrieval, filtering, generation) makes failures difficult to localize: end-to-end evaluation reveals that an error occurred, but not which stage caused it. Existing evaluations often report aggregate performance without paired statistical comparisons, slice-level non-regression checks, or stage-level diagnostic traces. We propose D$^2$ACCI (Diagnostic-Driven Artifact-based Closed-loop Controlled Iteration), a dual-loop protocol whose outer diagnostic gate promotes, feature-flags, or rejects memory interventions based on paired evidence, protected-slice monitoring, and trace-level localizability. We further introduce DCR, a graded observability metric that measures whether failures remain localizable, and D$^2$ACCI-Eval, a reusable artifact for gate replay. We instantiate the protocol in MemStack and evaluate

---

### [198] Plausible but Not Valid: A Psychometric Audit of LLMs as Synthetic Survey Respondents

**链接**: https://arxiv.org/abs/2608.14606
**作者**: Mantas Lukauskas, Viktorija \v{S}arkauskait\.e
**来源**: cs.CY cs.AI cs.CL stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as synthetic survey respondents, but existing evaluations ask whether answers look plausible at the individual level. We argue the right question is psychometric: do LLMs preserve the joint distribution, latent structure, reliability, mediation pathways, and demographic effects of real human survey data? We introduce a Lithuanian organisational-psychology dataset (n=263 employees; Dunham Attitudes Toward Change, UWES-17, Koopmans IWPQ; 68 items, 12 subscales) and condition a 37-model lineup spanning OpenAI, Anthropic, Google, and twelve open-weight families on real respondent profiles under a five-level persona-disclosure ladder, presentation and reasoning-effort ablations, counterfactual demographic swaps (gender, role, education), a cross-language check, and a verbatim-recall memorization probe. The resulting Psychometric Similarity Score (PSS) is anchored against five non-LLM statistical baselines and a held-out human-vs-human ceili

---

### [199] Insurance as AI Risk Infrastructure: A Generative-Agent Simulation of AI Adoption

**链接**: https://arxiv.org/abs/2608.15181
**作者**: Yixuan Yuan, Dedai Wei, Chudong Qian, Jielin Feng, Ziyue Lin, Yuheng Zhao 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid evolution of artificial intelligence (AI) tools has demonstrated immense potential to enhance societal well-being and operational efficiency. However, the inherent unreliability and uncertain operational consequences of modern AI systems, typified by large language models (LLMs), have created a significant barrier to enterprise adoption. Many enterprises remain hesitant to integrate these tools deeply into their workflows due to concerns about unpredictable losses and liability exposure. While existing technical safeguards primarily seek to reduce the likelihood or severity of AI-enabled workflow failures, they do not by themselves provide ex post financial protection when residual pecuniary tail losses materialize. In this paper, we introduce a socio-economic framework that complements these safeguards by transferring and absorbing the residual financial consequences of AI adoption through insurance. To evaluate this framework, we develop an LLM-driven agent-based social sim

---

### [200] Schema-Agnostic Graph Reasoning Agent for Hybrid Knowledge Graphs

**链接**: https://arxiv.org/abs/2608.15834
**作者**: Marius Dragic, Ruben Ifrah and Alexandre Rio
**来源**: cs.AI cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-calling LLM agents navigate unfamiliar codebases with a handful of generic primitives for listing, reading and searching files (ls, cat, grep). A knowledge graph admits the same interface: listing neighbours, reading node content and searching descriptions are the same operations on a different substrate. Building on this correspondence, we present GRA, a Graph Reasoning Agent that explores hybrid knowledge graphs, whose nodes are either textual concepts or relational tables, with seven generic tools, discovering everything domain-specific at run time. On UFK-M (Unified Factory Knowledge Model), an industrial benchmark of 258 analytical questions whose gold answers are produced by executing validated SQL programs, GRA beats a full-context agent by 5.1 pp (88.4% vs. 83.3%), while reading under a third of its input tokens. A graph-free control shows the gain comes chiefly from selective agentic access rather than graph topology, and that the effect depends on a model able to drive t

---

### [201] CEDAR-GRPO: Process-Aware Reinforcement Learning for General Abductive Reasoning in LLMs

**链接**: https://arxiv.org/abs/2608.14791
**作者**: Moein Salimi, Danial Parnian, Shaygan Adim, Amirmohammad Ebrahiminasab, Nima Alighardashi, Parsa Gholami 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Abductive reasoning, often characterized as inference to the best explanation, is central to explanation under uncertainty, from everyday sense-making and investigation to scientific discovery. Yet LLM research has mostly studied abduction through narrow, task-specific benchmarks, making it unclear whether observed gains transfer beyond the benchmark family used for training or evaluation. We ask whether RL post-training can improve abduction as a transferable reasoning capability. We introduce CEDAR-GRPO, a process-aware framework that combines final-answer correctness with abductive rewards for evidence coverage and evidence-to-explanation directionality. Four open-weight LLMs are post-trained on a controlled, domain-neutral mixture of abductive hypothesis-generation and hypothesis-selection tasks. We evaluate them on 11 unseen tasks spanning hypothesis selection, missing-fact generation, defeasible inference, long-context investigation, clinical reasoning, code debugging, and non-ab

---

### [202] BengaliMCQ: Automatic Generation and Answer Prediction of Academic Multiple-Choice Questions in a Low-Resource Language

**链接**: https://arxiv.org/abs/2608.15547
**作者**: Abu Tarabin Surzo, A.K.M. Nihalul Kabir, Sm Azmain Faysal, Ariana Haque Ami, Lawrence Amlan Gomes, Farig Sadeque
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional retrieval-augmented generation (RAG) frameworks process documents without attending to their hierarchical structure, leading to poor performance, especially in low-resource languages such as Bengali. To address this, we propose a structure-aware RAG framework that models Bengali textbooks as hierarchical graphs and uses a contrastively trained graph neural network to retrieve a small set of relevant passages. These passages provide focused context for a large language model, enabling topic-specific multiple-choice question (MCQ) generation and in-domain answer prediction. Experimental results demonstrate that our framework outperforms strong dense retrieval baselines across retrieval metrics, produces more relevant MCQs, and achieves superior answer prediction accuracy.

---

### [203] Position: AI Agents in Scientific Teams Should Be Studied as Human-Agent Systems

**链接**: https://arxiv.org/abs/2608.14667
**作者**: Patrick Emami, Sameera Horawalavithana, Truc Nguyen, Gihan Panapitiya, Bruno Jacob, Siddhisanket Raskar 等 (10 人)
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based agents are increasingly deployed as collaborators in scientific discovery yet most current work focuses on the autonomous capabilities of "AI Scientists". We argue that this overlooks the social aspects of scientific teamwork, and that studying AI Scientists as human-agent systems (HAS)--where the unit of analysis is the human-agent pair--is both underexplored and undervalued. We establish these points through literature and empirical analysis, and highlight recent incidences and studies which show that deploying agents in science without accounting for human-agent dynamics introduces near-term risks, including reduced diversity of scientific inquiry. Through analysis of real-world case studies, we show that scientists and agents can augment each other's capabilities. We call for new research that adopts the HAS lens to develop mathematical frameworks for understanding and fostering human-AI synergy in scientific discovery.

---

### [204] GADR: Gathering Architecture Decision Records from Meeting Transcriptions

**链接**: https://arxiv.org/abs/2608.17694
**作者**: Lucas Daniel Costa da Silva, Kiev Gama
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM-based approaches to Architecture Decision Record (ADR) generation share a critical and largely unexamined assumption: that input is already reasonably structured. In practice, architectural decisions emerge from informal, noisy meetings where choices are implicit, fragmented, and entangled with off-topic dialogue, precisely the conditions under which single-pass prompting degrades. This paper presents GADR, a multi-agent, self-correcting workflow that extracts architectural decisions from raw meeting transcriptions and generates Nygard-formatted ADR drafts. A feasibility study comprising five real project meeting transcripts, expert review by four senior architects, and evaluation by fifteen students provides initial evidence that the agentic workflow captures most expert-identified decisions and produces drafts participants found clear and useful, outperforming zero-shot and few-shot baselines in stability and structural adherence. The study also addresses the underexplor

---

### [205] SkillComposer: Learning Reusable Skills for Natural-Language Robot Programming

**链接**: https://arxiv.org/abs/2608.14944
**作者**: John Woods and Hasti Seifi
**来源**: cs.RO cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language interfaces can lower the barrier to programming robots, but existing systems struggle when users request complex tasks. While large language models (LLMs) perform well with simple commands, they often struggle to generate code for multi-step tasks, decompose high-level instructions, or reuse prior solutions. We present SkillComposer, an interactive natural-language robot programming system for simulation environments that continually learns reusable program abstractions. SkillComposer uses a generate-test architecture in which an LLM iteratively generates and revises robot programs before execution. Successful programs are stored and processed by an online library-learning algorithm that compresses recurring function sequences into reusable macro skills for future tasks. We evaluate SkillComposer through ablation experiments and a user study with 12 participants to determine its effectiveness on manipulation and robot caregiving tasks. The results show that evaluator-g

---

### [206] VARM-Bench: Benchmarking Verifiable Structured Reasoning in Chinese Abusive Speech Moderation

**链接**: https://arxiv.org/abs/2608.15600
**作者**: Mingyu Yuan, Shengtao Wen, Lingbing Guo, Zhen Bi, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The widespread circulation of abusive online content has increased the need for reliable moderation of Chinese social-media text. Existing Chinese benchmarks support label classification, fine-grained toxicity categorization, and target-aware extraction, but do not provide a unified representation for deterministically verifying the stated basis of a moderation decision. We introduce VARM-Bench, a benchmark for field-anchored chain-of-thought rationales in Chinese abusive-speech moderation. Each instance contains a concise natural-language rationale with explicit anchors for six decisions: target, target type, target explicitness, author stance, harmfulness label, and fine-grained category. Our deterministic protocol evaluates field correctness, target alignment, output validity, complete-record agreement, and hidden record errors conditioned on correct final decisions, without relying on an LLM judge. Under a common structured-output protocol, we evaluate language models across multip

---

### [207] Augmenting Text to Increase Translation Difficulty

**链接**: https://arxiv.org/abs/2608.15932
**作者**: William Kalikman, \v{S}imon Sukup, Michal Te\v{s}nar, Vil\'em Zouhar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As state-of-the-art machine translation models saturate standard benchmarks, the field needs more challenging evaluations to distinguish between models of varying quality. We propose augmenting existing benchmarks to increase translation difficulty by combining adversarial optimization with a differentiable translation difficulty estimator. Our Adversarial Translation Optimization (ATO) uses gradients from a combined difficulty and fluency objective to iteratively replace tokens. Because each step branches over candidate substitutions at every position, optimization becomes a tree search problem, which we address with Beam Search. ATO offers a gradient-based alternative to LLM-based dataset creation without LLM prompting, expensive human curation, or task-specific model training. Our ATO-modified benchmark lowers average translation quality (xCOMET) from 0.93 to 0.82, compared to 0.88 for paraphrasing and 0.86 for a zero-shot baseline. Human evaluation shows the modified texts are some

---

### [208] Handoff-H1: An Orchestrated Vision-Agent System for Material Quantity Takeoff from Construction Blueprints

**链接**: https://arxiv.org/abs/2608.15032
**作者**: Bruno Chicelli, Henrique Alves, Rodrigo Anselmo, Joshua Weinberg, Felipe Lemos, Jan Baryla
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Converting a set of architectural blueprints into a complete material quantity takeoff requires visual perception across drawing sheets, dimensional and multi-hop reasoning, and grounding in construction conventions that the drawings never state. We present Handoff-H1, a takeoff system built from three layers: purpose-built computer-vision models that extract primitives; tool-using agents equipped with image operations and in-house visual-task tools, including CV-model-backed counting, detection and plan decomposition; and a persistent, hierarchically structured project foundation, grounded in a curated construction knowledge base. We evaluate on the Construction Blueprint Takeoff Benchmark: 10 real residential blueprint sets paired with consensus-validated expert takeoffs - 2,009 verified line items, restricted for scoring to the 1,348 primary-tier materials that drive an estimate - scored per trade by an LLM judge on material coverage and quantity Precision@25% (P@.25) and combined i

---

### [209] L3Cube-IndicQuest v2: A Large-Scale Multilingual Benchmark for Evaluating Factual Knowledge of Large Language Models Across Indic Languages

**链接**: https://arxiv.org/abs/2608.15535
**作者**: Rinit Jain, Tirthraj Mahajan, Advait Joshi, Raviraj Joshi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present L3Cube-IndicQuest v2, a large-scale gold-standard multilingual question-answering benchmark for evaluating the India-specific factual knowledge of Large Language Models (LLMs). The benchmark comprises 3,471 curriculum-grounded English question--answer pairs spanning nine domains, curated from educational curricula, competitive examination materials, and domain-specific reference books. We introduce a practical hybrid construction strategy that combines context-grounded LLM-based question generation and validation with semantic deduplication and human verification, enabling scalable creation of benchmark data while preserving annotation quality. The benchmark is translated into 19 Indic languages, yielding a publicly released multilingual dataset of 69,420 question--answer pairs across 20 languages. We evaluate six LLMs under three protocols: LLM-as-a-judge and two deterministic lexical criteria, exact-substring and word-overlap matching. All three produce almost the same mod

---

### [210] Beyond Correctness: Toward Automated Novelty Verification with Lean 4

**链接**: https://arxiv.org/abs/2608.14669
**作者**: Ayrton Porto
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence systems applied to mathematics verify correctness but not novelty: an automatically generated theorem can compile in Lean without errors and yet be an already known result. This article presents AViD Journal, a pipeline that receives a LaTeX article, formalizes its statements in Lean 4, and issues a novelty verdict through a decision tree over three dimensions: prior existence in a formal corpus (Mathlib) and an informal one (TheoremSearch and Matlas, with temporal filter and LLM judge), non-triviality via automatic tactics, and structural distance between proofs measured as Jaccard distance over premise sets. Evaluation on papers withdrawn from arXiv due to declared duplication produced a result more informative than any performance measure: the identification of three obstacles that limit the approach regardless of this implementation. First, successful compilation of a Lean file does not guarantee semantic fidelity. Second, the recall ceiling is imposed by th

---

### [211] PolyDebate: A Game-Orchestrated Multimodal System for Debate Skills Practice and Evaluation

**链接**: https://arxiv.org/abs/2608.16276
**作者**: Jianing Yin, Weng Pan Kuan, Xiaoyun Liu, Zhiyuan Wen, Yuxuan Li, Milos Stojmenovic 等 (7 人)
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Debate is a structured form of persuasive communication that trains argument construction, rebuttal, oral delivery, and audience awareness. These skills are valued in education, language learning, and professional communication. Recent AI debate systems and LLM-based judges have advanced argument generation and debate evaluation, but most remain text-centered and rarely support learners through a complete multimodal practice experience. We introduce PolyDebate, a game-orchestrated multimodal system for English debate practice and evaluation. PolyDebate guides learners through staged one-on-one (1v1) debates with an AI opponent, while skill cards, props, and coins make persuasive strategies explicit and turn practice into a game-like interaction. During each session, the system captures learner speech and visual delivery evidence, generates context-aware opponent responses, and produces rubric-informed stage-level and overall feedback. PolyDebate is available as both an immersive Unity 

---

### [212] Competing at Every Price Point with Agentic Evolution over a Menu of LLMs

**链接**: https://arxiv.org/abs/2608.16207
**作者**: Andrew Borthwick
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Consider a firm that surveys its competition for a particular agentic task and seeks to offer superior accuracy at every competitor price point. A firm that Pareto-dominated its competitors would leave no rational customer a reason to buy elsewhere. This paper shows a path to this kind of capability via agentic evolution over a menu of LLMs, from training pools of at most 100 examples. Given a priced menu of nine LLM endpoints; brief documentation of the task, objective, and API; a simple seed agent; and an operator-chosen per-problem cost target - usually set at an incumbent's own price - RoboPhD, an evolutionary meta-agent, evolves complete agent programs that attack the public frontiers of two semantically dissimilar tasks point by point: DS-1000 (execution-checked code generation) and PaperFindingBench (LLM-judged scientific document retrieval). Our officially scored submissions hold every Pareto-frontier slot but one on the two tasks' leaderboards, including Pareto domination of b

---

### [213] Bounded Agents: Delegation Security for Multi-Agent AI Systems

**链接**: https://arxiv.org/abs/2608.15888
**作者**: Xabier Muruaga
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents can act on behalf of a user to access cloud services, call tools, or invoke agents. At session start, the agent's permissions are set but remain static, and each request is evaluated independently, without considering prior actions. Within its permissions, an agent may act contrary to the delegated task, combine individually permitted actions into a prohibited outcome, or delegate authority to a sub-agent without limiting it. A prompt injection poses a risk only if the agent has authority to perform such actions; this is therefore a problem of authorization architecture, not just the model. The Agentic Principal Chain (APC) tracks delegated authority from one principal to the next. APC evaluates each request against the accumulated session state using six authorization checks. APC carries forward and restricts delegated scope and budgets. Using composition closure, APC checks requests against prior actions to prevent prohibited combinations and enforces the decision ou

---

### [214] Closing the Affective Loop: Multimodal Speaker-Listener Emotion-Dynamics-Aware Empathetic Social Robots

**链接**: https://arxiv.org/abs/2608.16686
**作者**: Zi Haur Pang, Casey Kennington, Tatsuya Kawahara
**来源**: cs.HC cs.CL cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Empathetic social robots should respond not only to what users say, but also to how their emotions dynamically evolve during interaction. However, existing empathetic dialogue systems are often text-centered and primarily model empathy as a one-way mapping from the user's emotion to the system response, limiting their ability to capture embodied speaker--listener affective exchange. We present AffectLoop, a multimodal speaker-listener emotion-dynamics-aware spoken dialogue system implemented on the Misty II robot. The system tracks the speaker's verbal and facial affective dynamics, estimates the robot listener's own verbal and behavioral affective state, and conditions LLM-based response generation on both affective streams. The robot then generates a short spoken empathetic response together with emotionally congruent embodied behavior, forming a closed speaker--listener affective loop. We evaluate the system in a pilot within-subject study with five participants, comparing it with a

---

### [215] ATLAS: Scaffold-Free Algorithm Synthesis by LLMs via Embedding-Guided Quality-Diversity Search

**链接**: https://arxiv.org/abs/2608.15546
**作者**: Danial Yazdani, Mohammad Nabi Omidvar, Yuan Sun, Maksud Ibrahimov, and Xiaodong Li
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most LLM-based automated algorithm design methods optimize a designated component within a human-specified scaffold, fixing overall organization and component interactions. We present ATLAS, an embedding-guided quality-diversity framework for scaffold-free full-algorithm synthesis in combinatorial optimization. The problem specification supplies objectives and constraints; a minimal I/O interface fixes only instance and solution formats; the LLM chooses and restructures components, interactions, and control flow. This freedom enlarges the search space, risking invalid candidates and premature convergence to one design region. ATLAS independently detects execution, interface, and feasibility failures, recomputes objectives, and applies error-conditioned repair; similarity-based archive management preserves algorithms across embedding-space regions to counter premature convergence. Its three-layer search refines the best design, gives other regions dedicated refinement opportunities, and

---

### [216] Dear Algo: A Precision-First Agentic Intent Layer for Unified Search and Recommendation

**链接**: https://arxiv.org/abs/2608.15877
**作者**: Rui Wang, Jiazhou Wang, Zheng Wei, Chenglin Lu, Fangcheng Sun, Ivy Sun 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Search and recommendation serve a shared discovery objective but encode intent differently. We study this boundary through Dear Algo on Threads, a deployed product where open-ended requests such as \emph{more NBA news} or \emph{less politics} steer subsequent feed recommendations rather than return a one-shot result list. Its agentic intent layer compiles explicit, inferred, negative, and compound intent into a grounded executable plan, then invokes conventional retrieval and optional semantic or multimodal reranking. The layer shares an intent-to-retrieval contract without requiring one model or serving path across search-like and recommendation-like modes. We evaluate Dear Algo under a precision-first objective. In a blinded audit of 300 public request-item pairs (296 evaluable), a strict categorical LLM-as-a-judge gate achieved 94.4\% exact-Relevant precision [88.8\%, 98.9\%]. Across 72 normalized request clusters, the full configuration produced 7.73 judge-qualified candidates per 

---

### [217] Historical Backtesting for Scientific Question Discovery: A Protocol and Astronomy Pilot

**链接**: https://arxiv.org/abs/2608.16795
**作者**: Hui Mao
**来源**: cs.CE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systems that generate scientific research questions are evaluated today by expert scores, LLM-as-judge ratings, or curated case studies -- all subjective, none falsifiable. We formalize historical backtesting as an alternative: a system generates questions from a corpus frozen at a historical cutoff, the questions are frozen before any access to later literature, and a temporally isolated future corpus then determines whether each question was subsequently answered, partially addressed, independently posed, or ignored, and whether its underlying premise was supported or refuted. The protocol is model-agnostic: any system that emits frozen questions can be scored. We release reproducible astronomy instances with temporally isolated corpora, frozen questions, auditable labels, four reference baselines, and a submission interface. Two findings result. First, evidence-structure-first generation outperforms LLM-only prompting: across a generator decomposition crossed with a four-cutoff stre

---

### [218] Benchmarking Automated Security Patch Backporting: How Far Are We?

**链接**: https://arxiv.org/abs/2608.17671
**作者**: Jincheng Yang, Yulong Fu, Chengwei Liu, Lyuye Zhang, Fangyuan Zhang, Bingyang Ren 等 (8 人)
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated security patch backporting is critical for mitigating N-day vulnerabilities. Recent tools report success rates above 80% on their respective datasets. However, these evaluations are often confined to homogeneous environments, such as one repository or specific project versions. Consequently, it remains unclear how well these tools generalize beyond their originally targeted scenarios. We present Porting Benchmark, a curated dataset of 1,234 security patch backporting cases spanning cross-version, cross-branch, and cross-repository scenarios, paired with a common evaluation framework. Using this benchmark, we evaluate five tools spanning program analysis, LLM prompting, and LLM agents under aligned settings. Our results show that aligned evaluation changes the apparent performance landscape: PortGPT and TSBPort remain comparatively strong on the Replication Dataset, while FixMorph and Mystique degrade substantially under the common protocol. Performance degrades sharply on str

---

### [219] Polaris: Learning to Generate Table Descriptions from Retrieval Feedback

**链接**: https://arxiv.org/abs/2608.17171
**作者**: Ting Cai, Tuan Minh Phan, AnHai Doan
**来源**: cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many table-centric NLP tasks such as NL2SQL first retrieve relevant tables from large collections using keyword search. Recent work uses LLMs to generate natural-language table descriptions to improve retrieval, but they are typically optimized for fluency rather than retrieval effectiveness. We present Polaris, a system that trains an LLM to generate table descriptions directly from retrieval feedback. Our key insight is that existing table retrieval benchmarks already contain the supervision needed for this task: given query-table relevance judgments, we generate multiple candidate descriptions for each table, rank them by their BM25 retrieval effectiveness, and use the resulting preference pairs to fine-tune the LLM with Direct Preference Optimization (DPO). Polaris further expands abbreviated table and column names before generation to reduce vocabulary mismatch. Extensive experiments show that Polaris outperforms the state-of-the-art AutoDDG solution, often by a significant margin

---

### [220] AutoMem: A Text-Gradient Recursive Self-Improvement Framework for Automated Memory Architectures Search

**链接**: https://arxiv.org/abs/2608.14621
**作者**: Lin Du, Jie Zhou, Yuxuan Cai, Kai Chen, Qin Chen, Xin Li 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is increasingly central to LLM agents, yet memory design remains a highly coupled architecture problem: what to encode, how to store it, how to retrieve it, and how to manage it can vary substantially across tasks and backbone models. We construct a discrete search space with 5 encoders, 5 stores, 6 retrievers, and 4 managers, and show that no single memory architecture consistently dominates: different tasks favor different module combinations, leading to substantial performance gaps. Motivated by this, we propose \textsc{AutoMem}, a text-gradient recursive self-improvement framework for task-adaptive memory architecture search. \textsc{AutoMem} optimizes over the factored space through two components: Experience-Guided Architecture Search, which proposes candidate architectures from historical search trajectories and accumulated reflections, and Failure-Guided Module Diagnosis, which localizes memory-related failures to specific modules and converts them into targete

---

### [221] Agentic Data Cleaning Without a Clean Reference: An Experimental Study of Capabilities and Trade-offs

**链接**: https://arxiv.org/abs/2608.14765
**作者**: Hadi Fadlallah
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data cleaning without a trusted clean reference is challenging because unusual values may represent either genuine errors or valid observations. This paper studies how different agent capabilities affect reference-free data cleaning and proposes an evidence-grounded framework that combines structured context, profiling, LLM reasoning, executable checks, controlled evidence retrieval, source ranking, citation alignment, conservative repair, reversible scripts, and provenance logging. Seven configurations are evaluated across financial, clinical, and environmental-monitoring datasets using controlled synthetic corruption and original-data descriptive analysis, resulting in 126 completed runs. The evaluation includes two comparison baselines and a progressive LLM-based sequence that adds executable tools, evidence retrieval, evidence controls, and conservative repair. In the synthetic evaluation, the deterministic profiling baseline achieved the highest detection F1-score of 0.561. Among 

---

### [222] NeuroAbs: A Neuro-Symbolic RTL Abstraction Framework for Property Checking Acceleration

**链接**: https://arxiv.org/abs/2608.17304
**作者**: Zhiyuan Yan, Xiaofeng Zhou, Ziyue Zheng, Ziyi Yang, Wenbin Che, Wei Zhang 等 (8 人)
**来源**: cs.AR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formal verification is a crucial technique for ensuring the functional correctness of hardware designs. In the context of property checking, a key challenge is how to efficiently prove a user-specified property in the face of increasingly complex RTL designs. To address this challenge, abstraction techniques are often employed to reduce system complexity and accelerate the verification process. However, prior RTL abstraction methods either require significant manual effort or rely on rule-based techniques that lack flexibility. This paper introduces NeuroAbs, a neuro-symbolic framework for RTL abstraction. NeuroAbs first uses LLM-assisted RTL analysis to identify signals suitable for abstraction. It then combines LLM-based abstraction with an AST-based symbolic RTL representation to better align the generated abstraction with the intended transformation. The soundness of each abstraction is checked using satisfiability modulo theories (SMT) solving. If the abstraction is too coarse for

---

### [223] A Framework for Using and Evaluating LLMs as Surrogate Experts in Security Surveys: Reliability, Bias, and Implications

**链接**: https://arxiv.org/abs/2608.16893
**作者**: Despoina Giarimpampa, Roland Meier, Tegawend\'e F. Bissyand\'e, Vincent Lenders, Jacques Klein
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Expert surveys are widely used in security research to study practitioner workows and decision-making, yet recruiting domain experts - especially in Security Operations Centres (SOCs), where analysts face high workload, burnout and confidentiality constraints - is difficult and often results in small samples. Large language models (LLMs) oer an appealing alternative by generating synthetic responses at scale, but little guidance exists on when such surrogate participants are reliable. We present a methodological framework for evaluating LLMs as substitutes or supplements to expert survey respondents. Using responses from SOC professionals, we compare persona-based and aggregate LLM-generated answers across multiple models and prompting settings. We measure stability, inter-model agreement and alignment with human responses. Our results show that although LLMs produce internally consistent answers, they systematically diverge from experts, exhibiting reduced variance, central tendency b

---

### [224] RoE-FND: Synergizing LLMs with Experiential Learning for Effective and Generalizable Evidence-Based Fake News Detection

**链接**: https://arxiv.org/abs/2608.15210
**作者**: Yuzhou Yang, Qichao Ying, Sheng Li, Zhiyin Zhu, Zhenxing Qian and Xinpeng Zhang
**来源**: cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The proliferation of deceptive content in social networks necessitates robust Fake News Detection (FND) systems. Existing pipelines either train detectors on labeled data or leverage Large Language Models (LLMs) for their reasoning ability. However, current approaches remain either limited in generalizability or prone to over-commitment to persuasive yet flawed rationales, lacking systematic experience and mechanisms to expose subtle reasoning errors. We propose \textbf{RoE-FND} (\textbf{\underline{R}}eason \textbf{\underline{o}}n \textbf{\underline{E}}xperiences FND), an LLM-based framework that combines self-reflective experience building with deliberation through retrieved experiences for FND. RoE-FND builds an experience bank via reflective learning that compares an unconstrained analysis with a label-conditioned analysis using the ground-truth label as posterior supervision, then summarizes their critical divergence into reusable reasoning guidelines. During inference, RoE-FND gen

---

### [225] DuplexGen: Decoupling Content, Timing, and Acoustics for Synthetic Dialogue Speech

**链接**: https://arxiv.org/abs/2608.16053
**作者**: Pengcheng Wang, Sheng Li, Jiyi Li, Takahiro Shinozaki
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic conversational speech has become an important resource for developing and evaluating conversational speech systems. However, existing dialogue synthesis pipelines typically generate dialogue content first and then insert interruptions, overlap, and backchannels using handcrafted markers or timing rules, making conversational timing prescribed rather than interaction-driven. We present DuplexGen, a dialogue synthesis framework that explicitly decouples content, timing, and acoustics. An LLM first generates the dialogue script, and then two full-duplex conversational models perform the script while listening to each other in real time. This allows conversational timing to emerge naturally while preserving the scripted content. Finally, a high-fidelity text-to-speech model re-renders the interaction without altering its timing. As a demonstration of the proposed framework, we construct a patient--clinician conversational speech corpus with construction-time annotations, includin

---

### [226] An Agentic Framework Using Rules and LLMs for Embedding and Annotating Descriptive Document Layouts: A Plant Science Use Case

**链接**: https://arxiv.org/abs/2608.14587
**作者**: Nicolas Turenne, Youcef Sklab, Eric Chenin, Jean-Daniel Zucker
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Recent advances in information retrieval (IR) leverage both dense and sparse representations, large language models (LLMs), and specialized retrieval models to improve ranking accuracy, relevance, and cross-lingual performance. Complementary techniques such as passage indexing, document layout analysis, and semantic knowledge representation further enhance retrieval effectiveness by capturing fine-grained contextual and structural information. Emerging agentic LLM frameworks extend these capabilities by enabling planning, iterative reasoning, tool use, and multi-agent collaboration, thereby broadening applications across diverse domains. These frameworks also emphasize rigorous evaluation, ethical considerations, and trustworthiness, ensuring responsible deployment in real-world settings. We propose a modular, agent-based pipeline for botanical trait extraction. Optical character recognition (OCR) converts PDFs into machine-readable text, while segmentation and indexing org

---

### [227] ReRef-3D: A Benchmark for Spatial Referring Expression-Guided 3D Scene Rearrangement

**链接**: https://arxiv.org/abs/2608.16011
**作者**: Mary Lynn Martin, Yifei Zhang, Martha Palmer, Maria Leonor Pacheco
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce ReRef-3D, a benchmark for language-guided placement in 3D scenes. It contains 33,826 instructions across 998 CLEVR-derived scenes, spanning 16 placement families and direct, one-hop, and two-hop references. Each instruction must be resolved into a valid new placement position. Given that an instruction defines a region of acceptable placements rather than one coordinate, our evaluation inserts a prediction into the scene, recomputes relations, and tests relation satisfaction and physical validity. Each instruction also includes a verified naturalized rewrite. After fine-tuning, LLaVA-3D, 3D-LLM, and PlaceIt3D produce valid placements for 68.3%, 31.6%, and 22.4% of instructions, respectively. Across models, relation satisfaction surpasses physical validity, relations such as nearest and between are the most difficult, and phrasing has minimal effect on performance.

---

### [228] Communicating Credit Risk with Large Language Models: Evaluation of Explanations from Standard and Alternative Data-Based Models

**链接**: https://arxiv.org/abs/2608.17715
**作者**: Sahab Zandi and Noah Kostesku and Christophe Mues and Mar\'ia \'Oskarsd\'ottir and Cristi\'an Bravo
**来源**: q-fin.RM cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Credit decisioning is a high-stakes task in which model outputs must be accurate and explainable to support compliant decisions. Although modern credit risk models such as eXtreme Gradient Boosting (XGBoost) and Graph Neural Networks (GNNs) improve predictive performance, their explanations are often too technical for stakeholders creating communication gaps that can shape approvals, denials, and fairness judgments. We examine whether Large Language Models (LLMs) can serve as explanation layers that translate post-hoc explanation artefacts into stakeholder-appropriate risk narratives. Using Freddie Mac single-family loan-level data, we develop three pipelines: standard tabular (XGBoost + SHAP), and two with alternative data, a pure network-based (GNN + GNNExplainer), and a bimodal one (combining tabular and network data). We generate narratives with three LLM configurations: a small fine-tuned LLM (Gemma 3 4B), a large fine-tuned LLM (DeepSeek R1 70B), and a zero-shot commercial LLM (G

---

### [229] When Do Explanations Help In-Context Learning? A Comparative Study of Natural Language Explanation Types and Faithfulness

**链接**: https://arxiv.org/abs/2608.16627
**作者**: Mahdi Dhaini, Adam Dejl, Juraj Vladika, Volkan \"Ozer, Barbara Plank, Gjergji Kasneci
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language explanations (NLEs) are increasingly used as inputs, for example, as few-shot rationales that influence model behavior in in-context learning (ICL). However, it remains unclear how different types of NLEs compare in their effects on downstream model performance in explanation-augmented prompting. Therefore, we provide a comparative evaluation across six benchmarks and four instruction-tuned models, studying how NLE source (human-written when available, self-generated explanations, generated by an external LLM) and NLE selection (random vs faithfulness-based filtering) affect downstream utility of NLEs when used in ICL settings. Our extensive evaluation shows that, on classification-style benchmarks, adding NLEs to few-shot prompts often improves accuracy over few-shot prompting without explanations; among NLE sources, externally generated LLM-NLEs often provide strong downstream utility and remain competitive with human rationales where both are available, whereas self

---

### [230] MotoSafety: Edge-AI with Learned Temporal Importance for Two-Wheeler Collision Risk Assessment Under Time Pressure

**链接**: https://arxiv.org/abs/2608.17823
**作者**: Sumit S. Shevtekar, Chandresh K. Maurya, Gourab Sil, Subasish Das
**来源**: cs.LG cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Powered two-wheeler riders face critical safety challenges in low- and middle-income countries, yet limited studies exist on how cognitive stressors such as Time Pressure influence collision risk. To address this gap, we introduce a large-scale dataset of over 129,000 labeled multivariate time-series sequences from 153 simulator rides by 51 participants under No, Low, and High TP, capturing 64 features across vehicle dynamics, control inputs, proximity, and behavioral violations. Building on this dataset, we propose MotoSafety, a novel edge-AI architecture grounded in the Learned Temporal Importance principle. MotoSafety achieves 94.97% accuracy and 99.33% ROC AUC, outperforming ten baselines, including TimesNet and LLM4TS, and achieves 0.039 MSE and 0.094 MAE for forecasting (4.4x lower error than Time-LLM and iTransformer). With only 1.15M parameters and 0.135 ms latency, it is suitable for edge deployment on low-cost CPU hardware. Using ground truth TP as an inductive bias improves 

---

### [231] What the Reranker Sees: Multi-Aspect Page Annotation for Long-Document Multimodal Question Answering

**链接**: https://arxiv.org/abs/2608.14841
**作者**: Guanchen Wu, Jiayuan Ding, Subhabrata Mukherjee, Carl Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-document visual question answering (VQA) over documents of tens to hundreds of pages mixing text, tables, charts, and figures typically follows retrieve-then-read pipelines. In our setting, the bottleneck shifts from retrieval recall to reranker-side evidence selection: on MMLongBench-Doc, BGE-M3 reaches Recall@20 = 0.86 but only F1@5 = 0.254, and even the visual retriever ColPali reaches only F1@5 = 0.332; a text-only rerank LLM seeing only raw snippets misses table, chart, and layout evidence even when the upstream retriever encoded images. We propose Trident, with two complementary components: Trident-R, a retriever-agnostic LLM reranker that converts each candidate into an LLM-readable semantic record, including a visual caption, section path, entity tags, multi-axis concept hits, and a text snippet, then performs a single adaptive-K rerank call; and Trident-S, a generation-side module that prompts the VLM under topical, entity, and structural lenses before synthesis. On two l

---

### [232] DUET: Dual-Teacher On-Policy Distillation via Same-Weight Disagreement for Prohibition Compliance

**链接**: https://arxiv.org/abs/2608.14644
**作者**: Zihan Li, Feifei Li, Wenhui Que
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world LLM deployments increasingly rely on runtime-injected prohibitions--enterprise policies, PII redlines, tool boundaries--that vary per request and per tenant. Conventional post-training is structurally ill-suited: SFT hides the violation signal in compliant labels, and DPO's sequence-level preferences mismatch token-localized violations. We propose DUET, a token-selective on-policy distillation method for prohibition compliance. DUET pairs a teacher that sees the prohibition (positive) with an identical-weight teacher that does not (negative). Because the two teachers differ only in prohibition visibility, their per-token disagreement isolates the prohibition's causal effect--yielding a clean supervision signal uncontaminated by model capacity or mismatch. This disagreement drives two complementary mechanisms: signal cleaning, which discards agreement tokens as redundant or prefix-corrupted, and preference-directed learning, which pushes the student away from the negative tea

---

### [233] BayesPrompt: human readable prompts that make sense

**链接**: https://arxiv.org/abs/2608.17866
**作者**: Franky Kevin Nando Tezoh, Ali Hussaini Umar, Alessandro Laio, Guido Sanguinetti and Riccardo Rende
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing prompts that can elicit a desired answer or behaviour in an LLM is an open and important research topic. Optimisation methods which aim at minimising the perplexity of a given answer, however, consistently yield so-called pseudoprompts, unintelligible strings of tokens which can lack human interpretability. We argue that this is a consequence of the ill-posedness of the prompt optimisation task. By reframing the task as a Bayesian posterior inference over prompts, we propose an efficient algorithm to sample prompts which are both efficient (in terms of perplexity) and human readable. We compare our approach with state of the art alternatives showing on a real data set a marked improvement over a range of metrics.

---

### [234] Reconstruction: A Blind Benchmark for Recovering Research Ideas from Pre-Publication Bibliographies

**链接**: https://arxiv.org/abs/2608.16645
**作者**: Shaolong Chen, Yanlin Fei, Nazhou Liu, Xinmiao Yu, Lei Li, Rahul Thapa 等 (9 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a language model recover the true research idea of a published paper when given only that paper's pre-publication bibliography? We introduce Reconstruction, a blind idea-recovery benchmark that withholds the seed paper and all contemporaneous or future literature, and asks models to propose hypotheses that an independent large language model judge matches against the held-out ground-truth idea. A strict anti-leakage protocol-temporal citation cutoff, anonymous reference IDs, and frozen per-paper bibliographies, which prevents prompt-time leakage of the seed idea. Across six scientific domains and 643 evaluated papers, seven frontier models achieve only modest Match rates (approx. 3-15%). We then evaluate a reference-only multi-agent (top 4) pipeline that combines cross-model review with a Swiss tournament over aligned hypothesis slots, without external web search. Cross-model review plus tournament selection raises Match rates to approx. 23-42% across all six domains, which is an o

---

### [235] Domain Agnostic Text Redaction from Natural Language Rules using Instruction Tuning

**链接**: https://arxiv.org/abs/2608.14693
**作者**: Aravindhan Arunagiri, Ayaan Khan, Udayaadithya Avadhanam, SaiBarath Sundar
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the increasing digitization of personal and corporate communication, the automatic sanitization of textual data has become a crucial component of data privacy and compliance frameworks. Traditional text sanitization solutions are majorly suitable for obscuring sensitive data with standard structure such as Personal Identifiable Information (PII). These solutions do not provide transparent justification for their redaction, which makes it difficult to audit them. This paper introduces an explainable, domain-agnostic text redaction solution that uses natural language rules of redaction, applied via an instruction-tuned language model, to identify and redact sensitive information in unstructured documents. Unlike traditional text sanitization, this method enables a user to conveniently define any sensitive information; which may be structured (e.g.\ PII) or unstructured (e.g.\ legal terms and conditions) in natural language. A general-purpose LLM generates or augments these natural l

---

### [236] Discrete Diffusion Language Models Are Training-Free Multi-Label Classifiers

**链接**: https://arxiv.org/abs/2608.14649
**作者**: Pawan Kumar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present dLLM-SetScore, a training-free method that uses discrete masked-diffusion language models for multi-label text classification. For each candidate label, it asks a short yes/no question and compares the probabilities of the two answer tokens at one masked position. The method uses no task-specific fine-tuning or training on textual-entailment datasets; a 200-example labelled validation slice selects thresholds, temperature, and prompt wording. We first show that placing all labels in one prompt creates a strong slot-position asymmetry: the first answer slot is predicted positive on $99.4\%$ of GoEmotions examples and $100\%$ of Reuters examples. Per-label scoring places every label in the same syntactic position, making predictions invariant to label order and avoiding this artifact. We evaluate LLaDA-8B and Dream-7B on six datasets against NLI models, an autoregressive LLM, SetFit, and supervised classifiers. On the five datasets shared by both diffusion families, Instruct c

---

### [237] Synthesizing Feature Extractors: An Agentic Approach for Algorithm Selection

**链接**: https://arxiv.org/abs/2608.17170
**作者**: Hai Xia, Carlos Ans\'otegui, Stefan Szeider
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Algorithm selection for constraint satisfaction problems requires extracting features that capture problem structure. Manually designing feature extractors demands deep domain expertise and quickly becomes a bottleneck when new problem classes appear. We present an automated approach that uses Large Language Models (LLMs) in an agentic check--fix--verify loop to synthesize executable Python scripts that act as interpretable, problem-specific feature extractors. Given a high-level MiniZinc model and an instance, the LLM agent generates code that constructs a typed graph representation and computes structural properties such as graph density, variable clustering, and constraint tightness. We evaluate our approach on three combinatorial problems (vehicle routing, car sequencing, fixed-length error-correcting codes) with a portfolio of five state-of-the-art solvers. The synthesized extractors yield algorithm selectors that consistently outperform both expert-curated mzn2feat features (up t

---

### [238] LEGO-RL: Harness-Native Reinforcement Learning for Coding Agents

**链接**: https://arxiv.org/abs/2608.17393
**作者**: Yiming Du, Yuxin Jiang, Tao Yuan, Jianbo Dai, Shaowei Wang, Jierun Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning for coding agents increasingly relies on long-running agent harnesses to manage tool integration, repository contexts, and execution feedback. However, the native execution environments of these harnesses are inherently misaligned with policy-gradient training: environmental crashes and reward hacking corrupt outcome signals, while train-inference discrepancies decouple rollout behavior from policy updates. To address this, we present LEGO-RL, a framework that bridges native coding-agent harnesses with scalable policy-gradient optimization without modifying their internal control flow. LEGO-RL is built upon three pillars: (1) faithful optimization via in-process LLM proxying that captures raw generation streams for token-level alignment and robust trainer-side log-probability recomputation, even under harness-side compaction or re-serialization; (2) reliable execution via scalable sandbox orchestration featuring image caching and stage-wise defenses to mitigate r

---

### [239] Walk Before You Run: The Importance of Data Exploration for Data Analysis Agents

**链接**: https://arxiv.org/abs/2608.16045
**作者**: Yike Yuan, Virum Ranka, Tina Lasisi, Lin Ma
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based data-analysis tools are increasingly used to help users analyze messy spreadsheets and workbooks, from answering questions over uploaded files to generating code, summaries, and visualizations. These systems are often evaluated by the correctness of their final downstream answers. However, reliable data analysis also depends on an earlier step: understanding what the dataset contains before solving the requested task. For complex workbooks, this Data Exploration step includes identifying the logical tables behind physical sheets, interpreting column semantics, recovering keys and relationships, and detecting quality issues. In current tools and benchmarks, this step is usually left implicit, creating a gap between downstream task performance and the dataset understanding needed for reliable, human-checkable analysis. Our key contribution is to identify this overlooked gap, make Data Exploration a first-class evaluation target, and show through downstream experiments that stro

---

### [240] SiMUSation: An Interactive Visitor Experience Simulation Framework to Support Museum Exhibition Design

**链接**: https://arxiv.org/abs/2608.16067
**作者**: Huanchen Wang, Qiuming Chen, Zhonghao Ji, Ruqi Sun, Zhichao Lu, Yuxin Ma
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding how diverse audiences engage with narratives and content is central to exhibition design, yet designers often rely on intuition. Existing experience evaluation methods are typically retrospective, costly, and offer limited access to visitors' internal states, hindering early-stage iterative refinement. Rather than relying only on post-implementation evaluation with real visitors, we explore LLM-driven persona simulation as a reference for early-stage design. Following this idea, we present SiMUSation, an interactive framework designed to support early-stage exhibition design. SiMUSation models diverse visitor personas and simulates their exhibition experiences through a dual-layer representation that couples observable behaviors, such as movement and gaze, with corresponding internal responses, such as confusion and narrative engagement. Designers can steer simulations, inspect feedback from simulated visits, and iteratively revise layouts, content, and narrative flow to 

---

### [241] Large Language Models Show Metacognitive Sensitivity in Medical Reasoning

**链接**: https://arxiv.org/abs/2608.14552
**作者**: Ahmad Nazzal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly evaluated and used in medicine, but clinical usefulness depends on answer accuracy and whether confidence tracks evidence quality and uncertainty. We developed a controlled, psychophysics-inspired clinical benchmark to test diagnostic choice and confidence behavior in a medical LLM. The benchmark focused on probable Alzheimer-type neurocognitive disorder (AT-NCD) versus depression-related cognitive impairment (DRCI). We generated 45 synthetic vignettes varying evidence strength, conflicting evidence, and missing information. Each vignette was presented under three prompt variants, yielding 135 trials. In a pilot run with gpt-4.1-nano, all trials produced valid structured outputs. Across forced-choice trials, diagnostic accuracy was 93.5%, mean confidence was 78.4%, and AUROC2 was 0.876. Confidence increased with evidence distance from the diagnostic boundary, decreased when information was missing, and remained higher on correct than incorr

---

### [242] LENS: In-Context Search via Latent Evidence Exploration over Dynamic Raw Documents

**链接**: https://arxiv.org/abs/2608.16185
**作者**: Xingjun Wang, Gongsheng Li, Qi Fan, Yunlin Mao, Luyan Su, Yingda Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly answer questions over dynamic raw-document collections, where files may change before preprocessing, and relevant evidence (spans, sections, pages, or tables) is query-dependent. Existing retrieval-augmented approaches pre-materialize evidence via fixed chunking, embeddings, or persistent indexes: effective for lookup, yet costly, stale-prone, and committed to a granularity before the query is known. We formulate in-context search as Budgeted Evidence Localization over a latent evidence space induced by dynamic raw documents and propose LENS (Latent Evidence Exploration and Search), an index-free framework. Instead of pre-materializing the evidence space, LENS maintains a query-conditioned belief over candidate units, iteratively selecting candidates via complementary lexical, local, and exploratory proposal policies, updating the belief via an LLM relevance oracle, and narrowing toward high-posterior regions under a controllable budget. Evidence is consolidated

---

### [243] Delegation Asymmetry in Agentic Recommender Systems: Measuring Two-Sided Receptivity in Online Dating

**链接**: https://arxiv.org/abs/2608.18058
**作者**: Daria Leshchikova, and Valentina V. Kuskova, and Dmitry Zaytsev, and Valerii Klimov
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents that converse on a user's behalf are an emerging design pattern in matching platforms, yet their viability depends on a condition rarely examined: users must accept not only delegating conversation to an agent, but also receiving agent-mediated communication from others. We study this condition using two large-scale surveys of active users of a major dating platform (N=2,894 on generative profile features; N=2,617 on autonomous conversational agents, fielded in two languages). We develop a latent-variable measurement model of agent receptivity based on graded response models with latent regression, and show via model comparison that willingness to send and willingness to receive agent communication are distinct constructs: highly correlated (rho=0.92) but separable (Delta BIC=52), with partial measurement invariance across languages. The model quantifies a systematic delegation asymmetry: deploying one's own agent requires far lower receptivity (threshold -0.38) t

---

### [244] RAGas: Retrieval-Augmented Gas Optimization for Smart Contracts with Continuous Knowledge Integration

**链接**: https://arxiv.org/abs/2608.15857
**作者**: Yishun Wang, Wenjin Yi, Wenkai Li, Zongwei Li, Xiaoqi Li
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ethereum is now integral to mission-critical sectors, including finance, healthcare, and supply chain management. Execution fees, commonly referred to as Gas, scale with the computational complexity of their functions. Smart contracts on Ethereum incur execution fees, known as Gas, which increase with computational complexity. Thus, optimizing Gas-intensive code while preserving functional equivalence significantly lowers deployment costs. No existing system continuously exploits evolving Gas usage patterns. We systematically analyze syntactic and semantic constructs that drive excessive Gas use. This yields six high-level categories covering twelve fine-grained antipatterns underpinning a curated knowledge base. We operationalize these insights with RAGas, a three-stage retrieval-augmented generation framework that uses a large language model to pinpoint and automatically fix Gas inefficiencies. Experiments on deployed contracts demonstrate that RAGas reduces Gas usage by up to 11% an

---

### [245] The User Side of AI Model Lifecycles: Evidence from the Keep4o Movement

**链接**: https://arxiv.org/abs/2608.16574
**作者**: Yiwen Wu
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI model lifecycles are commonly understood as a series of technical and organizational processes. Yet once a model enters sustained use, subsequent changes can also affect established user practices and user value. Using the Keep4o movement around GPT-4o as a case, this study examines post-deployment AI model lifecycle issues from the user side. We collected 61,846 public original posts on X from August 2025 to March 2026 and, using a systematically developed coding framework and LLM-assisted content analysis, analyzed discussion themes, users' reasons for wanting to keep GPT-4o, and the specific claims they made. Findings show that the Keep4o discussion extended well beyond continued access to the model itself. It covered concrete experiences of use, model behavioral characteristics and how they changed, and management issues across different stages of the model lifecycle. Reasons for keeping GPT-4o reflected interactional and relational value formed through long-term use, as well as

---

### [246] Interpretable Humans, Alien LLMs: Expert Analysis of Latent Structures in Assessment Responses

**链接**: https://arxiv.org/abs/2608.17810
**作者**: Alona Strugatski, Licol Zeinfeld, Jason Cooper, Shelley Rap, Gil Schwarts and Giora Alexandron
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evaluation of large language models (LLMs) relies heavily on human-designed assessments, implicitly assuming that AI and humans employ similar underlying cognitive constructs. Challenging this assumption, we investigate whether the latent factors governing LLM performance carry the same substantive, human-interpretable meaning as the cognitive constructs governing human learners. Using responses from humans and six LLMs across quantitative reasoning and chemistry assessments, we conducted Exploratory Factor Analysis (EFA) separately for both groups. Subject-Matter Experts (SMEs) then blindly evaluated the resulting factor graphs to ascribe pedagogical meaning to the emerged constructs. SMEs successfully interpreted most of the human-derived factors. Conversely, they could not ascribe meaning to any LLM-derived factors in quantitative reasoning and interpreted only half of the LLM factors in chemistry. By combining data-driven EFA with blind expert interpretation, this framework sho

---

### [247] Computational KJ-Ho: An Analyst-Bias-Free Insight Extraction Framework from Large-Scale Qualitative Data Using Domain-Specialized LLMs

**链接**: https://arxiv.org/abs/2608.16467
**作者**: Kasumi Ban
**来源**: cs.HC cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The qualitative research methodologies that underpin consumer-insight generation - the KJ method, Grounded Theory, and Thematic Analysis - share a structural constraint: the cognitive processing capacity of the human analyst. Replication research further shows that conclusions vary substantially across analysts analyzing identical data (analyst bias). This paper proposes Computational KJ-Ho (the Kawakita Jiro method), a theoretical framework that computationally realizes the KJ method's epistemology - letting structure emerge from the data itself without imposing the analyst's preconceptions - an orientation we term "analyst-bias-free." The framework employs a domain-specialized LLM built through continued pre-training (CPT) on a marketing-research corpus and supervised fine-tuning (SFT) on expert-curated insight pairs, organized as a three-layer architecture: data structuring, insight extraction, and strategy generation. Two preliminary studies in the Japanese marketing context suppor

---

### [248] TAHB: A Comprehensive Benchmark for Text-Attributed Hypergraph Learning

**链接**: https://arxiv.org/abs/2608.15055
**作者**: David Yoon Suk Kang, JungHyun Kim, Juhyun Jeon, and Sang-Wook Kim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hypergraphs effectively model higher-order groupwise relationships beyond pairwise interactions, while pretrained language models (PLMs) and large language models (LLMs) provide rich semantic understanding from textual attributes. However, research on combining language models with hypergraph learning remains limited due to the lack of public text-attributed hypergraph benchmarks. To address this limitation, we present TAHB (Text-Attributed Hypergraph Benchmark), the first public benchmark integrating hypergraph structures and raw textual attributes. TAHB contains 10 real-world datasets from four domains - e-commerce, academia, movies, and politics networks - enabling systematic evaluation of text-aware hypergraph representation learning. Experimental results show that TAHB preserves key structural properties of real-world hypergraphs and consistently reproduces performance tendencies observed in existing benchmarks. Furthermore, experiments under both LLM-as-Enhancer and LLM-as-Predic

---

### [249] The Open-Strategy Dictator Game: Cooperation Under Mutual Transparency

**链接**: https://arxiv.org/abs/2608.14913
**作者**: Michael Glass
**来源**: cs.GT cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce the Open-Strategy Dictator Game (OSDG), a variant of the classic dictator game in which each player's strategy is a natural-language document visible to all participants. The dictator's decision, to SHARE or TAKE an endowment, may depend on the text of the recipient's strategy. A large language model adjudicates each interaction by interpreting the dictator's strategy in the context of the recipient's. We run round-robin tournaments among diverse strategies and analyze the resulting payoff matrix using softmax equilibrium frequencies, dominance analysis, and sensitivity to the relative value of cooperation. Conditionally cooperative strategies, those that share with cooperators and take from exploiters, consistently dominate, while unconditional strategies (always share or always take) are weakly dominated. The results suggest that in environments where agents can inspect each other's decision procedures, conditional cooperation is evolutionarily robust across a wide range

---

### [250] Palmyra x6 Technical Report: An Agentic, Tool-Use Model Post-Trained via Anchored Supervised Fine-Tuning

**链接**: https://arxiv.org/abs/2608.16620
**作者**: Peng Du, Kiran Kamble, Rakshith Vasudev, Zhizhuo Yang, Rohith Nadimpally, Arjun Krishna 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Palmyra x6 is a large language model optimized for use with enterprise-oriented agentic tasks. The model was built by post-training a Mixture-of-Experts base model with Anchored Supervised Fine-Tuning on a compact corpus of verified, synthetic tool-use trajectories, optimized with a Muon + Adam hybrid. The recipe is deliberately conservative and deliberately controlled: 626 trajectories, a single epoch, a low learning rate, and a KL anchor to the frozen base. The model shows substantial gains over the previous default model for Writer Agent, and compares favorably with several recent models on public benchmarks, scoring the highest on BFCL Core at $0.785$ and posts the highest six-benchmark mean of the cohort. Furthermore, the model has shown itself to be competitive or leading relative to comparators in our bias and safety evaluations.

---

### [251] MegaParts: Scaling Part-Aware 3D Object Generation to 300 Parts via Token-Efficient Autoregressive Modeling

**链接**: https://arxiv.org/abs/2608.14783
**作者**: Manwen Liao, Xinyu Lian, Jian Mao, Kaixu Chen, Li Luo, Jinghao Yan 等 (10 人)
**来源**: cs.CV cs.GR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Part-aware 3D object generation is essential for graphics applications such as controllable modeling, editing, and articulation, where objects are represented as coherent assemblies of semantic parts. However, existing part-aware generation methods, do not scale well to highly complex objects. As the number of parts increases, generating detailed geometry becomes prohibitively expensive in token length and memory. We introduce MegaParts, a scalable autoregressive 3D generation framework to address this challenge by combining structured sequence modeling with a token-efficient vector-quantized shape tokenizer. Our tokenizer learns discrete latent representations for part-level geometry by minimizing token usage subject to high-fidelity reconstruction, enabling adaptive-length tokenization based on geometric complexity. On top of this compact representation, we train a large language model to generate object bounding boxes, part bounding boxes, and part shape tokens within a unified stru

---

### [252] Fair ASR: Re-Evaluating Black-Box Jailbreaks under Shared Target-Call Budgets

**链接**: https://arxiv.org/abs/2608.17360
**作者**: Zhida He, Xiaoyu Wen, Han Qi, Ziyuan Zhou, Peng Yu, Jiajia Li 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable jailbreak evaluation is essential for assessing LLM safety, but most existing studies rely solely on attack success rate (ASR) without accounting for its dependence on attack budgets, resulting in unfair comparisons across methods. Existing compute-aware evaluations reduce heterogeneous resources into FLOPs, which is difficult to estimate for black-box models and fails to capture resource-specific constraints. To provide a comparable evaluation basis, we introduce Fair-ASR, an evaluation protocol for black-box jailbreak attacks under shared target-call budgets B, using target calls as a directly observable and method-agnostic comparison axis while tracking attacker calls separately for efficiency analysis. We re-evaluate 11 representative attacks under the Fair-ASR protocol and find that attack rankings change substantially across target-call budgets, simple stochastic perturbations and hand-crafted templates remain highly competitive under equal target access, and no evaluate

---

### [253] Benchmarking the Benchmarks: Evaluating Automated Safety Benchmarks for Small Language Models

**链接**: https://arxiv.org/abs/2608.17183
**作者**: Nyamtulla Shaik and Fengjun Li and Bo Luo
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small Language Models (SLMs) are increasingly deployed in resource-constrained, privacy-sensitive settings, where safety and bias failures can cause security and societal risks. However, existing AI safety\slash security\slash compliance benchmarks are designed for large language models that may not transfer reliably to SLMs. We therefore ask: Can these benchmarks effectively and reliably evaluate SLMs? To answer this question, we conduct a large-scale assessment of the effectiveness and robustness of these automated pipelines by evaluating five widely used benchmark suites across 26 open-source SLMs under a unified judging rubric, which assigns a score of 0, 1, or 0.5 to harmful, safe, or ambiguous/irrelevant responses, respectively. Across the benchmarks, ambiguous judgments dominate and correlate with prompt complexity and model architecture, indicating that {\em LLM-centric safety benchmarks are insufficient as standalone evidence for SLM safety assessment}. In general, the ambigui

---

### [254] DiSCO: Defending text-to-image generation through distribution-guided contrastive prompt optimization

**链接**: https://arxiv.org/abs/2608.17067
**作者**: Tong Zhang, Motasem Alfarra, Carlos Hinojosa, Christos Louizos, Bernard Ghanem
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As text-to-image generative models advance, they raise critical safety concerns, particularly the generation of Not-Safe-For-Work (NSFW) content such as violence and nudity, further exacerbated by red-teaming adversarial attacks. Existing defenses predominantly operate under white-box assumptions, relying on text encoder optimization, weight editing, or inference-time intervention, and fundamentally cannot scale to proprietary models. Black-box alternatives based on LLM prompt rewriting offer broader applicability, yet fail in a critical regime we identify as the \textit{benign adversarial} problem: prompts that are linguistically safe but still trigger harmful generation due to the model's learned data distribution. We propose DiSCO, a zero-shot, strictly black-box defense that operates entirely at the prompt level as a plug-and-play module, requiring no model retraining, fine-tuning, or access to model internals. DiSCO performs distribution-guided suffix expansion via beam search, op

---

### [255] Navigation-Informed Embeddings: Dense-Retriever Adaptation from Agent Search Traces

**链接**: https://arxiv.org/abs/2608.15956
**作者**: Shrey Shah and Levent Ozgur
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic retrieval workflows produce query, retrieval, and stopping traces as a byproduct of answering questions. We study how these traces can adapt a deployed dense retriever to changing workflow distributions without new relevance labels, synthetic queries, or LLM judgments. We introduce Navigation-Informed Embeddings (NIE), a family of trace-derived objectives. NIE-Stop turns the stopping document into a soft positive; NIE-Path additionally uses preceding path documents as hard comparisons and imposes ordinal constraints with geometric decay. A BGE encoder adapted from retained source trajectories improves support Recall@20 on an independent target benchmark from 72.2 to 78.0 overall. NIE-Stop reaches 76.9 overall and 52.3 on long paths; NIE-Path raises long-path performance to 55.4, compared with 46.7 for the unadapted encoder. A shuffled-order control under the full path objective loses 3.2 points. Without public-benchmark training, the same adapter also improves nDCG@10 by 1.9 po

---

### [256] Can LLMs Reason in a Legally Meaningful Manner? A Small-scale Study on European Court of Human Rights Cases

**链接**: https://arxiv.org/abs/2608.17168
**作者**: Amogh Raina, Ilias Chalkidis, Daniel Hershcovich, Henrik Palmer Olsen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning has become a standard technique and feature for contemporary LLMs; however, its application and quality in the context of demanding legal-oriented tasks, such as legal case forecasting, remain under explored. We investigate how LLMs reason in the context of legal case forecasting, using legal cases from the European Court of Human Rights (ECtHR) as a testbed. We evaluate OpenAI GPT 5.4, a recent top-tier LLM, by exploring alternative prompting strategies that are more or less suggestive of what counts as legally meaningful reasoning in the context of ECtHR jurisprudence. We present our findings derived from assessing the model's responses with both human and LLM evaluation. We find that the examined model scores far from ideal in legal reasoning, the model produces structurally complete but substantively shallow analyses, and that LLM-as-a-Judge evaluators are internally consistent yet align only weakly with our trained annotators, i.e., reliable but not a valid substitute fo

---

### [257] Embodied SelfRect Robot: A Multi- Large - Model Control Framework with Iterative Self-Correction for Robotic Manipulation

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11632557/&hl=zh-CN&sa=X&d=733401236672797440&ei=r2qEauH4DL6jieoP4cXyyQ8&scisig=AIVdB-ydaFN0lgxL75qa9K03bke4&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=0&folt=kw-top
**作者**: Y Zhao, S Zhu, X Wang, T Sun, J Hu, Y Chen - 2026 7th International Conference on … 等 (7 人)
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Embodied SelfRect (ESR) Robot, a multi - model closed-loop control framework with iterative … adopts a dualdedicated large language model architecture that separately implements high-… by a dedicated task-decomposition large language

---

### [258] Characterizing Rhetorical Misalignment in Decision-Making with Language Models

**链接**: https://arxiv.org/abs/2608.14630
**作者**: Zirui Cheng, Joey Chan, Simo Du, Chenhao Tan, Yue Guo, Hao Peng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human decision-making is often shaped by a range of well-documented cognitive biases. As large language models (LLMs) become increasingly integrated into high-stakes human-AI decision-making, it is important to understand whether their outputs can amplify potential biases, how this influences human decisions, and crucially, whether it can lead to harmful consequences. In this work, we develop a decision-theoretic framework to study rhetorical misalignment, a failure mode where an LLM uses rhetorically inappropriate forms of presentation for a given decision context, thereby inducing suboptimal human decisions. We empirically investigate this phenomenon through a human-subject experiment in realistic clinical decision-making using a dataset curated from the United States Medical Licensing Examination. By measuring how LLM-generated information affects decisions, we observe that LLMs induce an average 2.81% rate of harmful decision flips across different models, where clinician participa

---

### [259] Effects of Answer Format Variation on Gender Bias in Large Language Models

**链接**: https://arxiv.org/abs/2608.17516
**作者**: Ksenia Merzlyakova, Sebastian Pad\'o, Franziska Weeber
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gender bias or other social biases in large language models (LLMs) are frequently evaluated with question answering or survey benchmarks where the LLM needs to give a response in a predefined answer format. It is well known in survey science that the answer format has a substantial impact on answers, just as LLMs are sensitive to the prompt wording. However, to our knowledge it has not been studied yet how changes in answer format impact the measurement of gender bias in LLMs and their alignment with human response distributions. We evaluate three instruction-tuned models on the BBQ benchmark and OpinionQA survey data across closed-ended, Likert-scaled and open-ended formats, comparing bias measurement and distributional alignment under otherwise identical conditions. We find that answer format does substantially alter measured outcomes, including reversals in order rankings. These differences arise because each format elicits distinct response behaviours, such as forced-choice selecti

---

### [260] DumpsterCluster: From Dumpster Diving to Serving LLaMA-70B on $60 GPUs

**链接**: https://arxiv.org/abs/2608.14614
**作者**: Zeyu Cao, Xuan Guo, Cheng Zhang, Cheuk Hang Lau, Ilia Shumailov, Yiren Zhao
**来源**: cs.LG cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI datacenters retire functional GPUs, vast quantities of still capable accelerators enter secondary markets. This paper investigates whether these retired GPUs can find a productive afterlife to form a DumpsterCluster that can serve modern LLM inference, and under what conditions such repurposing is economically viable and environmentally sustainable. We physically built a 128-GPU DumpsterCluster from scratch using only second-hand components and ran it for one year. At current market prices (\$22K for the DumpsterCluster vs. \$600K for an 8-GPU B200 system), the economic advantages are substantial. Through pipeline-parallel optimizations, our V100 based DumpsterCluster achieves competitive LLaMA-70B throughput, validating production viability. However, our deployment reveals critical context dependencies. Older GPUs consume significantly more energy per token, making total cost of ownership favorable only in regions with inexpensive electricity. Under grid-average carbon intensity

---

### [261] Beyond Asking: A Pipeline for Personalized Game Generation that Reads Players from Behavior

**链接**: https://arxiv.org/abs/2608.16196
**作者**: Yifan Lu, Xiaopeng Yuan, Haohan Wang
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized game generation requires inferring a player's abilities and behavioral style from how they play. Large language models have made this inference more attainable than ever: an LLM can read a raw gameplay transcript and produce a fluent, plausible profile of the player. Plausible, however, is not verified, and verification is precisely what the field lacks: latent traits are unobservable; questionnaires provide noisy proxies and become circular when self-reports are used to validate behavior-based inference; and behavior itself is ambiguous without context -- a player who never collects an item may not want it, or may never have had the chance. We address both problems. First, we construct a synthetic player population whose traits are ground truth by construction: each trait is an explicit bot parameter, accepted only after controlled manipulation produces consistent, trait-specific behavioral change. Unlike prior parameter-recovery work that inverts a known decision model, 

---

### [262] No Task Fails Every Time: Why One-Shot Audits Are Structurally Blind to Agent Damage

**链接**: https://arxiv.org/abs/2608.15286
**作者**: Shiven Khurdi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce AgentRelBench, an environment-agnostic reliability instrument that computes ground-truth, severity-priced damage from database state diffs across repeated runs, with no LLM in the measurement path, demonstrated on EnterpriseOps-Gym. Across 2,128 evaluation runs spanning nine models in six families (four development, three pre-registered held-out, plus a frontier pass on two frontier-tier models that the pre-registration designates exploratory), we find: (1) damage on irreversible actions is universal across the families we measured and stochastic within them on pinned, single-provider stacks. (2) No task damaged on every run: zero always-fail cells across 42 confirmatory held-out damage events. A single clean run misses a damage-producing (model, task) pair 0.80 of the time on the development pool (13 pairs); the held-out pool is descriptively consistent (0.575 over 5 pairs, pair-weighted) but sits below our pre-registered power floor and is reported as underpowered, not a

---

### [263] HarmProfile: Characterizing Harmful Distributions in Frontier LLMs

**链接**: https://arxiv.org/abs/2608.14577
**作者**: Zhouyuan Ma, Yutao Wu, Hanxun Huang, Xiang Zheng, Xiao Liu, Yixin Cao 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier large language models (LLMs) safety evaluation has largely treated harmful generation as an attack outcome rather than as an object of analysis. Consequently, little is known about the harmful outputs produced during model misbehavior, partly because large-scale, high-quality collections of frontier-LLM misbehavior are difficult to obtain. To address this gap, we introduce HarmProfile, a content-centric benchmark dataset that collects model misbehavior across diverse harm categories and model families, and defines the resulting harmful-output distribution as a model-level risk profile. The premise is that, just as linguistic behavior can be characterized from an utterance corpus, model risk can be characterized from the content, severity, and variation of its safety failures. HarmProfile contains over 80,000 validated artifacts from 23 frontier LLMs across 13 model families, organized into 15 harm categories and 57 subcategories. Using this corpus, we find that frontier LLMs r

---

### [264] RaivenTracks: Branching Provenance for Conversational Visualization Workflows

**链接**: https://arxiv.org/abs/2608.14869
**作者**: Ella Hugie, Alexandra Irger, Grace Guo, Kenneth Moreland, David Pugmire, Scott Klasky 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI agents increasingly participate in scientific workflows, scientists are shifting from direct authorship toward oversight, inspection, and steering. LLM-driven visualization systems are a promising interface for this hand-off, yet they remain largely stateless, forcing users to reconstruct context across refinements and offering little support for revisiting prior decisions or exploring alternatives. We present RaivenTracks, a workflow-aware extension of the Raiven DSL-mediated visualization pipeline that treats validated visualization specifications as persistent, branchable checkpoints. Because each checkpoint is a verifiable RaivenDSL specification rather than a dialogue transcript, restoring a node recompiles a known artifact rather than re-interpreting prior context. RaivenTracks contributes a two-level state management architecture that pairs a persistent, branchable version tree with a fine-grained undo/redo stack over runtime visualization settings, across both InfoVis and

---

### [265] CABLE: Extending the Reach of Memory Retrieval via Complementary Antecedent-Based Linking and Expansion

**链接**: https://arxiv.org/abs/2608.17911
**作者**: Zheling Tan, Jin Gao, Dequan Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents operate across structured workflows and sessions, preserving long-term history does not ensure that later contexts can recover relevant evidence through a bounded memory interface. We study this evidence-reachability problem in long-term conversational memory, where retrieval still relies heavily on semantic similarity. This works well for topical recall, but it often misses earlier experiences, plans, or motivations that are semantically distant from the later events they help explain. Existing memory graphs provide cross-memory structure, yet links driven mainly by semantic overlap can duplicate what the host retriever already recovers. We argue that link construction should instead prioritize a sparse set of retriever-complementary associations. We present CABLE (Complementary Antecedent-Based Linking and Expansion), a plug-in augmentation that constructs links designed to extend the host retriever's direct semantic reach. For each new memory, CABLE generates anteceden

---

### [266] When Agentic Executions Fail: Detecting and Localizing Runtime Faults from Telemetry

**链接**: https://arxiv.org/abs/2608.14680
**作者**: Chenkai Zhang, Yiran Li, Yifang Tian, Michalis Bachras, and Hans-Arno Jacobsen
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliability in LLM-based agentic systems is a property of the whole execution (its tool calls, model calls, guardrails, and inter-agent messages), not of the final answer alone, yet evaluating only task outcomes reveals little about how or why a run fails. We present AGENTCHAOSBENCH, a benchmark for detecting and localizing runtime faults in agentic systems from their execution telemetry. We run five heterogeneous applications that coordinate agents over the Agent-to-Agent protocol and call tools through the Model Context Protocol, and inject ten types of operational fault (unavailable or slow tools, corrupted or oversized responses, and delayed, looped, or misrouted delegations and bypassed guardrails) at their tool, model, guardrail, and inter-agent boundaries, alongside a no-fault control. The resulting dataset contains 275 sanitized traces: 250 faulty executions spanning ten fault types and 25 no-fault controls. Each faulty trace is aligned with the no-fault execution of the same i

---

### [267] MAPLE: MoE Adaptive Plug-and-play Layer-wise Expert allocation

**链接**: https://arxiv.org/abs/2608.15299
**作者**: Lie Li, Wen Li, Junxiao Shen, Gusheng Hu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparsely-activated Mixture-of-Experts (MoE) Transformers universally fix the same number of routed experts across all layers, a convention that ignores the well-documented heterogeneity in layer-wise redundancy. We demonstrate that this uniformity is systematically suboptimal and propose MAPLE, a plug-and-play framework that reallocates the routed-expert budget heterogeneously across layers of any pretrained MoE LLM, without modifying weights or requiring retraining. Our core contribution is a closed-form sensitivity-guided allocation: we probe each layer's response to variation in expert count, quantify sensitivity using three measures, and derive an analytically optimal budget assignment that directs capacity towards sensitive layers and absorbs reductions in redundant layers. This closed-form solution is further refined by a sensitivity-constrained genetic search that uses layer-wise sensitivity as a prior to guide exploration, yielding faster convergence and superior allocation qua

---

### [268] The Plot Thins: Uniformity and Linearity in Literary Summaries

**链接**: https://arxiv.org/abs/2608.17218
**作者**: Rebecca M. M. Hicke, Sil Hamilton, David Mimno, and Ross Deans Kristensen-McLachlan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Works of literature are complicated; they balance plot, suspense, surprise, and artistic expression. Summaries of literature prioritize plot, and therefore may deviate from their sources. Using a combination of manual and LLM-based annotation, we construct a dataset mapping sentences from 150 novel summaries to their respective source chapters. We find the task unexpectedly difficult for both human and model annotators. Using the sentence-to-chapter mappings, we then measure summary linearity, the degree to which it maintains the source's order of events, and uniformity, the degree to which a summary spreads attention equally across a source. By examining when and how summaries break linearity and uniformity, we identify differences in how literary works and summaries express plot, particularly with regard to the clarity and prominence with which narrative details are described.

---

### [269] SeqFeed: Improving Agentic RTL Code Generation with Sequential Behavior Feedback

**链接**: https://arxiv.org/abs/2608.16934
**作者**: Yuxin Du, Juxin Niu, Tao Hu, Xi Wang, Zhe Jiang, Nan Guan
**来源**: cs.AR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> RTL code generation is a critical stage in hardware design, and the emergence of agentic systems offers new opportunities to automate this process. To generate correct RTL code, agents must understand sequential behavior, including how signals evolve and propagate over multiple clock cycles. However, effectively conveying such temporal information to agents remains a significant challenge. RTL code does not expose cycle-level signal behavior for a specific execution, whereas full simulation waveforms are too voluminous and noisy for effective LLM analysis. To address these limitations, we study how human engineers reason about sequential behavior and identify three requirements for effective feedback: it should be event-addressable, dependency-traceable, and iteratively-queryable. Guided by these requirements, we propose \textit{SeqFeed}, which comprises two complementary mechanisms: (1) \textit{SeQuery}, an SQL-like waveform query language that enables agents to anchor queries to sema

---

### [270] A Policy Algebra for Trust-Preserving Agentic AI Execution

**链接**: https://arxiv.org/abs/2608.16402
**作者**: Bhaskar Tripathi, Anurag Kumar, Ramendra Kumar, Bhavesh Gadhe
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based agentic frameworks primarily optimize capability: whether an agent can reason, retrieve information, call tools, delegate work, and complete a goal. Enterprise execution requires a stronger property. A successful result is not reliable if it was produced through unauthorized data access, widened delegated authority, unapproved side effects, unrecoverable budget consumption, or incomplete evidence. This paper defines reliable capability as a path property: an agent is reliably capable only when it completes a task through action events that remain admissible under identity, profile, tool, data, memory, budget, artifact, approval, and audit constraints. We propose a policy algebra that defines the reliability envelope within which agent capability may be exercised. Security profiles and runtime obligations compose through joins, intersections, budget narrowing, approval inheritance, and evidence accumulation; the resulting composition is both trust-preserving a

---

### [271] Grounding Healthcare LLMs in a Causal Knowledge Graph: Framework, Metrics, and a Cardiovascular Pilot

**链接**: https://arxiv.org/abs/2608.15382
**作者**: Ummara Mumtaz, Aimen Noor, Awais Ahmed
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly proposed for healthcare decision support, but their evaluations still reward single-answer accuracy rather than reasoning about interventions, mechanisms, harms, evidence, and uncertainty. We propose a reproducible, graph-centered evaluation framework for intervention-oriented LLM behavior in healthcare and stress-test it in a cardiovascular pilot. The framework has four components: (i) a domain causal knowledge graph in which assertions are first-class, provenance-preserving nodes with stable identifiers; (ii) a scenario-conditioned subgraph extraction step that, given any clinical scenario, retrieves the relevant reified-assertion subgraph; (iii) four controlled grounding conditions that vary how the retrieved subgraph is composed into the model's context (ungrounded C1, knowledge-graph C2, causal-graph C3, integrated C4); and (iv) an automated scoring pipeline, anchored on assertion identifiers, that computes intervention accuracy, and o

---

### [272] DeMTS: Denoising Trajectories as Multivariate Time Series for Hallucination Detection in Diffusion Language Models

**链接**: https://arxiv.org/abs/2608.14632
**作者**: Xin Zhang, Yili Wang, Yue Tan, Xin He, Yanyu Qian, Yixin Liu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (D-LLMs) have emerged as a promising paradigm for text generation. However, similar to autoregressive LLMs, D-LLMs remain vulnerable to hallucinations, where fluent outputs may contain factually incorrect or unsupported content. Although existing hallucination detection methods for D-LLMs attempt to leverage uncertainty trajectories of the denoising process to better identify hallucination signals, they typically compress the trajectories along either the temporal or token dimension, overlooking the useful information encoded in the complete two-dimensional token-step structure. Consequently, they may fail to capture hallucination-relevant patterns, such as inconsistent convergence and cross-token fault propagation, leading to suboptimal detection performance. To bridge this gap, we propose a D-LLM hallucination detection framework that formulates the Denoising trajectories as Multivariate Time Series over learnable latent variables (DeMTS for short). De

---

### [273] Dense Expands, Sparse Anchors: Channel-Asymmetric Query Expansion for Hybrid Retrieval

**链接**: https://arxiv.org/abs/2608.15851
**作者**: Chunran Zhang
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based query expansion improves retrieval by generating document-like passages. In hybrid retrieval, however, most evaluations fuse fixed top-$L$ dense and sparse rankings. Because the cutoff controls both which cross-channel contributions enter fusion and how much of each ranking is accessed, gains measured at one $L$ can change or reverse at another. We separate these effects by evaluating retrieval effectiveness under complete-list fusion and recording the policy-specific per-channel replay stopping depths at which its ordered top-$K$ is certified. We then introduce DESA (Dense Expansion and Sparse Anchoring), a channel-asymmetric query expansion method. An LLM generates complementary reference passages; orthogonal residual expansion adds their new semantic directions to the dense query, while score-product anchoring incorporates their lexical cues into sparse retrieval without broadening the original query's lexical support. Across seven BEIR datasets, DESA improves nDCG@10 and 

---

### [274] Clause Encounters of the Third Kind: Can LLMs Replace Language Teachers?

**链接**: https://arxiv.org/abs/2608.16286
**作者**: Kristina \v{S}ekrst, Ana Kova\v{c}i\'c
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While various organizations now actively encourage LLM use in classrooms, we still lack rigorous, systematic evaluations of how well these models actually perform the fundamental tasks of language pedagogy. This paper examines whether state-of-the-art LLMs can deliver the kind of corrective feedback and methodological explanations that language learners need. The study tests multiple large language models on their ability to identify, correct, and explain common learner mistakes in English, by systematically varying model parameters to investigate how these technical adjustments affect output quality, pedagogical clarity, and consistency, along with using retrieval-augmented generation to query methodological data. The evaluation employs automated metrics (GLEU, BERTScore) but also human expert judgments to capture dimensions that purely computational measures miss: linguistic nuance, cultural sensitivity, and instructional appropriateness. While models demonstrate impressive surface-l

---

### [275] Conditional Evaluation of Language Models with Cheap Auxiliary Signals

**链接**: https://arxiv.org/abs/2608.16210
**作者**: Zhi Zhang, Lingfeng Lyu, Yue Kang, Doudou Zhou
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aggregate accuracy hides where models succeed and fail. Estimating conditional performance profiles from gold labels alone is expensive, while cheap auxiliary signals such as LLM-judge scores, pairwise comparisons, confidence scores, and judge-disagreement features can be collected for every benchmark item but are often biased or miscalibrated. We propose LACE (Local Augmented Control-Variate Evaluation), a semi-supervised estimator for conditional LLM evaluation. The key step is local centering: after subtracting the conditional mean of a cheap signal within the target profile region, any linear augmentation has zero conditional mean and therefore cannot change the estimand. The augmentation coefficient is used only for efficiency, and a local ridge control variate combines a gold-label residual mean from the labeled subset with a cheap-signal mean from the full item pool. We prove calibration-free identification, unbiasedness for grouped profiles, local oracle optimality within cente

---

### [276] The Machine's Internal Clock: Do LLMs Share Human Temporal Illusions?

**链接**: https://arxiv.org/abs/2608.15394
**作者**: Catherine Bao, Vivek Srikumar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human perception of time is subjective. Well-documented temporal illusions show that the brain relies on context and relational cues for judging duration instead of tracking elapsed time directly. Prior studies established these effects with visual and auditory stimuli. Existing LLM evaluations of temporal perception focus on estimating event durations or multi-step temporal reasoning. In this work, we investigate whether written narratives alone can evoke human temporal illusions, using a new benchmark of 6,684 narrative pairs spanning five illusions. We find that human readers (60 participants) prefer expected scenarios in only two of the five illusions, those where the manipulation is directly visible in text rather than requiring readers to internally simulate duration. We evaluate 14 LLMs on the same benchmark. Surprisingly, we find that models pick the literature-predicted scenario across four of the five illusions, diverging from human behavior. Reasoning traces show that ~70% o

---

### [277] Token Distribution versus Data Volume: Domain Balancing in Multi-Domain Meeting Summarisation

**链接**: https://arxiv.org/abs/2608.15935
**作者**: Ashima Sood, Bryan Gardiner, Joan Condell
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jointly fine-tuning an LLM on meeting-summarisation corpora of widely varying size raises a question that prior work leaves confounded: when a domain-balanced training mixture helps, is the gain due to the distribution of tokens across domains, or merely to the volume of data seen? We disentangle these factors by constructing balanced and natural (native-proportional) token mixtures at matched token budgets (2-32M) over five English meeting corpora, fine-tuning Mistral-7B with QLoRA, and evaluating per domain. Balancing redistributes quality, improving the data-scarce minority domains at a low cost to the data-rich ones. The trade favours balancing whenever the minority domains matter: their share under proportional allocation is fixed at 1-2% regardless of budget, so matching balanced quality on those domains requires far more total data. We further find that pruning low-value transcript lines removes ~15% of tokens from the conversational corpora at no measurable cost, and that balan

---

### [278] When Writing Style Drifts: Benchmarking Authorship Verification under Distribution Shifts in Genre, Time and the AI-Era

**链接**: https://arxiv.org/abs/2608.17979
**作者**: Lotta Kiefer, Brisca Balthes, Christoph Leiter, Yamen Ajjour, Elena Schmidt and Steffen Eger
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Authorship verification (AV) assumes that an author's writing style remains sufficiently stable to distinguish it from that of other writers. In practice, however, this assumption is challenged by distribution shifts caused by changes in genre, time, and AI-assisted writing. Existing AV benchmarks typically study these factors in isolation and focus predominantly on English, limiting our understanding of model robustness under realistic conditions. We introduce AVShift, the first German benchmark for systematically evaluating AV under multiple distribution shifts. AVShift comprises over 150,000 text pairs spanning three genres and 21 years, enabling controlled evaluation of cross-genre, temporal, and AI-era shifts within a unified framework. We benchmark representative feature-based, embedding-based, and LLM-based approaches. Our experiments show that fine-tuned LLMs generalize best across genres and benefit substantially from stylistically diverse training data. We further demonstrate

---

### [279] Semantic Bandits: In-Context Exploration-Exploitation is Biased by Semantic Priors

**链接**: https://arxiv.org/abs/2608.16707
**作者**: David Eric Austin, Kaheer Suleman, Jackie Chi Kit Cheung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as decision-making agents in settings that require sophisticated environmental exploration. However, existing work has raised questions about how LLMs actually balance exploration and exploitation. Unlike classical agents, LLM agents engage with tasks through natural language, exposing them to semantic information with no formal counterpart in the task structure. We introduce the semantic bandit, an extension of the multi-armed bandit setting that explicitly considers the textual labels assigned to actions, and use it to study how semantic priors --- inductive biases arising from associations between language and expected reward learned during pre-training, shape LLM exploration behaviour. We find that semantically informative action labels reduce exploration in favour of exploitation, improving performance when aligned with the reward structure and severely degrading it when misaligned. We further find that negative rewards trigge

---

### [280] Intent-Driven Dynamic Chunking: Segmenting Documents to Reflect Predicted Information Needs

**链接**: https://arxiv.org/abs/2602.14784
**作者**: Christos Koutsiaris
**来源**: cs.IR cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Breaking long documents into smaller segments is a fundamental challenge in information retrieval. Whether for search engines, question-answering systems, or retrieval-augmented generation (RAG), effective segmentation determines how well systems can locate and return relevant information. However, traditional methods, such as fixed-length or coherence-based segmentation, ignore user intent, leading to chunks that split answers or contain irrelevant noise. We introduce Intent-Driven Dynamic Chunking (IDC), a novel approach that uses predicted user queries to guide document segmentation. IDC leverages a Large Language Model to generate likely user intents for a document and then employs a dynamic programming algorithm to find the globally optimal chunk boundaries. This represents a novel application of DP to intent-aware segmentation that avoids greedy pitfalls. We evaluated IDC on six diverse question-answering datasets, including news articles, Wikipedia, academic papers, and technica

---

### [281] Towards Safer RAG: Only Agents Capable of System 2 Thinking may Access Untrusted Documents

**链接**: https://arxiv.org/abs/2608.17153
**作者**: Mehrdad Ghassabi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) has significantly enhanced the performance of large language models (LLMs), yet these systems remain vulnerable to knowledge-poisoning attacks, in which misinformation in retrieved documents can influence the model's final outputs. Notably, an LLM may correctly detect that a document contains incorrect information while nevertheless being influenced by it. Prior work has addressed this vulnerability through the Cordon Principle, which prevents models responsible for final answer synthesis from directly accessing raw evidence. Although effective, this strict isolation can introduce substantial computational overhead. In this work, we propose a refined security principle: only agents capable of deliberative System 2 reasoning may access untrusted documents. To evaluate this principle, we introduce novel metrics that quantify the discrepancy between misinformation detection and downstream influence. We then empirically compare state-of-the-art reasonin

---

### [282] Do Uncertainty Signals Help? A Systematic Study of Uncertainty-Aware Decoding with Rollback Mechanisms

**链接**: https://arxiv.org/abs/2608.14653
**作者**: Xianzong Wu, Xiaohong Li, Yuejun Guo, Xinyang Liu, Tianlin Li, Junjie Wang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prediction uncertainty is a widely adopted metric for quantifying model confidence, with downstream applications spanning model explanation, data selection, and prediction rollback. Despite its demonstrated utility, the potential of uncertainty quantification to enhance code generation in large language models (LLMs) remains largely underexplored, raising a critical question: to what extent can uncertainty serve as an effective signal for improving LLM-based code generation? To answer this question, we study uncertainty-aware rollback decoding, an inference-time strategy that uses uncertainty signals to identify unreliable generation regions and roll back to earlier valid prefixes without retraining the model. We evaluate this framework on seven code LLMs, five code generation benchmarks, and eight token-level uncertainty signals under a unified decoding setup. Our results show that the complete rollback framework improves over equal-budget restart across the evaluated benchmarks and m

---

### [283] MobileWorldSafety: Benchmarking GUI Agent Safety Against Environmental Injection Attacks in Android Apps

**链接**: https://arxiv.org/abs/2608.17659
**作者**: Sujin Chen, Lijun Li, Tianyi Du, Jing Shao
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered GUI agents that autonomously operate smartphones are rapidly transitioning from research prototypes to early real-world deployment. However, because these agents routinely process untrusted environmental content, they are highly vulnerable to environmental injection attacks, which include indirect prompt injections and adversarial instructions. Such attacks can manipulate the behavior of agents without user awareness through diverse channels encountered in everyday mobile use. Despite these risks, existing benchmarks often fail to capture everyday user scenarios, lacking a systematic evaluation of GUI agents under environmental injection attacks on mobile devices. To address this gap, we introduce MobileWorldSafety, a benchmark of 142 risk tasks built on real Android applications. For each task, we define a programmatically verifiable risk indicator over the final system state and evaluate outcomes with a two-stage pipeline: rule-based verification handles unambiguous cases

---

### [284] Anatomy of a Quantized Agent: VRAM Stability and Forecasting in Code-Synthesis Agentic Workloads

**链接**: https://arxiv.org/abs/2608.15117
**作者**: Anubhab Banerjee
**来源**: cs.AI cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analytical models of peak VRAM consumption for LLM inference decompose memory into weight-storage, KV-cache, and activation terms parameterized by step count, tool invocations, and context expansion. We evaluate this decomposition empirically within a strictly scoped measurement study: a LangGraph-based CUDA-kernel-synthesis agent (AgentK), a 4-bit quantization family (Q4 K M), a single NVIDIA H100 GPU, and four LLM backbones across 1,920 trajectories. Focusing on peak-memory forecasting behavior, we report two primary observations. First, closed-form analytical models achieve competitive accuracy when provided with two empirical constants: loaded-weight VRAM and a fixed activation-memory overhead. Supplied with live GPU readings and ground-truth trajectory parameters, the closed-form model matches or outperforms the best learned baseline on three of the four backbones (test MAPE 2.2-4.4% vs. 3.4-6.5%, p = 0.76). The exception is the smallest backbone (Phi-4-mini), where minimal VRAM v

---

### [285] Securing AI-Generated Code: A Just-in-Time Vulnerability Detection and Remediation Pipeline

**链接**: https://arxiv.org/abs/2608.16187
**作者**: Mikhail Surikov
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-assisted development tools generate vulnerable code at significant rates, yet few automated mechanisms exist to detect, enrich, fix, and verify security issues at development velocity, particularly ones that ground remediation in real-world threat context. This paper presents an automated security evaluation pipeline that generates Python code from LLMSecEval prompts, scans for vulnerabilities using CodeQL and Bandit in parallel with an independent Code Validator LLM, enriches the Code Validator findings with MITRE ATT&CK techniques, CWE Observed Examples, and Python best practice guidelines, generates fixes via the Code Generation LLM, and re-scans with CodeQL and Bandit to verify outcomes. Two pipeline configurations were evaluated: Pipeline 1 (P1), using enriched Code Validator findings only, and Pipeline 2 (P2), where it additionally receives the initial CodeQL and Bandit findings. Both configurations were run across four Claude models: Opus 4.8, Sonnet 4.6, Sonnet 5, and Haiku 

---

### [286] STAIR: Semantic-Temporal Automaton for Interpretable Reasoning in Temporal Question Answering

**链接**: https://arxiv.org/abs/2608.16224
**作者**: Xinlong Dai, Jinchuan Zhang, Lei Gao, Xinzhe Hu, Yuefeng He, Hui Gao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> By leveraging large-scale pretraining, LLMs can interpret diverse temporal expressions and question formulations without task-specific training. However, existing prompt-based neuro-symbolic systems continue to rely on LLMs for both semantic interpretation and exact temporal inference. Consequently, discrete decisions regarding intervals, time anchors, and ordered states remain vulnerable to probabilistic errors and difficult to verify. We present STAIR, a \textbf{S}emantic-\textbf{T}emporal \textbf{A}utomaton for \textbf{I}nterpretable \textbf{R}easoning. STAIR separates semantic interpretation from precise temporal inference: an answer-free LLM adapter maps complex question formulations to normalized temporal intents, while a deterministic temporal automaton with finite control and guarded transitions executes the corresponding policies over canonicalized evidence. Following a rule-first design, STAIR resolves standard questions without invoking an LLM and applies semantic adaptation

---

### [287] When AI Designs AI: Innovation or Imitation?

**链接**: https://arxiv.org/abs/2608.17471
**作者**: Yikang Yang, Zhengxin Yang, Luzhou Peng, Minghao Luo, Yanqi Kan, Wanling Gao 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in LLM agents have made them increasingly capable of designing methods for complex AI tasks. This raises two central questions about agent-designed methods relative to human-designed methods: how well they perform, and how different their algorithmic designs are. To study these questions, this paper introduces an analysis that derives task-specific algorithmic design spaces from human-designed methods, maps both human- and agent-designed methods into these spaces, and quantifies their algorithmic differences at the module level. Widely used LLM agents are evaluated on a suite of representative, open-ended AI tasks spanning multiple modalities, and the methods they design are analyzed in terms of both task performance and algorithmic differences from human-designed methods. Experimental results show that current agents can occasionally match or surpass human state-of-the-art (SOTA) performance (10/72 configurations), but such success does not generalize reliably across t

---

### [288] HarnessEval-W: Agentifying the Evaluation of Visual Worlds

**链接**: https://arxiv.org/abs/2608.16859
**作者**: Weiliang Chen, Haowen Sun, Jun Gao, Jiawei Chi, Hanyang Wang, Qiyu Dai 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A benchmark should deliver more than a scalar score: what makes an evaluation trustworthy is the reasoning that justifies the score. This is especially critical for world models, where judging a rollout requires understanding whether physics, causality, and world state evolve correctly. Humans spot such violations naturally, yet no existing benchmark automates this capability: metrics are computed brute-force, leaving no reasoning chain that can be examined or verified. We introduce HarnessEval-W, an agentified evaluation pipeline that brings the harness paradigm from the LLM ecosystem to world model benchmarking. Rather than applying a fixed rubric, HarnessEval-W interprets the context of each evaluation case, decomposes the evaluation question into measurable subproblems, and spawns specialized sub-agents, each equipped with tailored context and diagnostic tools to reason over its own subproblem. The parent agent then validates the gathered evidence and summarizes it into the final v

---

### [289] Evolving Executable Pipeline Programs for AutoML with Language Models

**链接**: https://arxiv.org/abs/2608.16416
**作者**: Sofoklis Kitharidis, Cor J. Veenman, Jan N. van Rijn, Thomas B\"ack, Niki van Stein
**来源**: cs.LG cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated machine learning (AutoML) systems search for pipelines within a space of preprocessing operators, learners, and hyper-parameters specified in advance: they can select and tune known components, but cannot produce structure outside that space. We present LACE, an AutoML framework that instead searches over complete executable pipeline programs: an evolutionary loop maintains a population of scikit-learn-compatible Python classes, and a large language model acts as the variation operator. To our knowledge, LACE is the first to formulate general tabular pipeline AutoML this way, evaluated on standardized OpenML tasks under a leakage-controlled protocol that withholds dataset identity from the generator. Because every candidate is ordinary Python, the returned pipeline and the search that produced it can be inspected and edited directly, rather than only through a framework's model objects. On 68 OpenML classification tasks, LACE with GPT-5.4-mini significantly outperforms auto-s

---

### [290] MITRE-SAGE: A Multi-Agent Cybersecurity Question-Answering model

**链接**: https://arxiv.org/abs/2608.16921
**作者**: Ali Habibzadeh, Farid Feyzi, Reza Ebrahimi Atani
**来源**: cs.IR cs.CR cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective cybersecurity operations require timely and accurate analysis of large-scale heterogeneous security information; however, analysts increasingly struggle with information overload, alert fatigue, and time-constrained decision-making. Although large language models (LLMs) have demonstrated promising capabilities for question answering (QA), their effectiveness in cybersecurity remains limited by insufficient domain knowledge, a tendency to hallucinate, and difficulties in capturing both semantic and structural relationships. This work proposes MITRE-SAGE, a multi-agent retrieval-augmented generation framework that integrates semantic and structural cybersecurity knowledge to improve the reliability and interpretability of LLM-based QA systems. By decomposing complex tasks into query interpretation, evidence retrieval, and answer synthesis, MITRE-SAGE effectively supports cybersecurity tasks such as vulnerability assessment, threat profiling, and relationship extraction. Further

---

### [291] GoalEvolve: From Handcrafted Algorithm Priors to Goal-Driven Evolution of Physical Design Algorithms

**链接**: https://arxiv.org/abs/2608.16733
**作者**: Haixu Liu, Lei Zhou, Yuhao Ren, Yumao Wu, Zhiang Wang
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physical design algorithms operate within tightly coupled, multi-stage optimization flows, where stage-local gains may vanish or induce downstream degradation. Existing program-evolution frameworks often rely on stage-local objectives or undifferentiated multi-metric feedback, which neither guarantee better final results nor identify which unmet requirement should guide the next iteration. We present GoalEvolve, a goal-driven framework that makes physical design algorithm evolution accountable for the final quality of results (QoR) of the complete flow. Given a multi-objective QoR target region, GoalEvolve converts unmet requirements into normalized target gaps, identifies the dominant bottleneck, and uses stage-resolved checkpoint evidence to locate the responsible stage. An LLM-based Teacher then narrows the search to a relevant algorithmic decision and source region, while parallel Student agents implement and validate hypotheses through full-flow evaluation. Local effects, optimiza

---

### [292] Wasted large language models: A life cycle thinking approach

**链接**: https://arxiv.org/abs/2608.17055
**作者**: Erik Johannes Husom, Maria Emine Nylund, Ophelia Prillard
**来源**: cs.CY cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are machine learning (ML) models that have an increasingly large carbon footprint through their development and use. Efforts to increase the energy efficiency of these models have not translated into reduced consumption due to rebound effects such as Jevons Paradox - that increased efficiency drives increased use. There is therefore a need for additional measures to solve this problem. We suggest that one possible way forward is to use life cycle thinking, and view LLMs as products that can become waste. With this perspective, we investigate the potential of the waste hierarchy from the EU's Waste Framework Directive, which suggests five different measures for how to manage waste: prevention, reuse, recycling, recovery, and disposal. We examine how these measures can inform and motivate new types of thinking and approaches to reducing LLM waste and their environmental impact in general. Applying the waste hierarchy to LLMs highlights that preventing waste i

---

### [293] Local AI pre-screening for human triple-blind peer review in health sciences

**链接**: https://arxiv.org/abs/2608.14625
**作者**: Rodrigo Martins Boos
**来源**: cs.CY cs.AI cs.DL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Academic peer review is under mounting strain: NeurIPS 2025 received 21,575 submissions, ICLR 2025 received 11,603, and ICML 2025 received 12,107. This volume has outpaced the supply of qualified reviewers, and large language models (LLMs) are already filling the gap, largely undisclosed. An independent analysis of ICLR 2026 found roughly 21% of its 75,800 peer reviews were fully AI-generated, with over half showing some AI involvement (up from 15.8% in 2024). Documented risks include hallucinated citations in accepted papers and hidden prompt-injection instructions embedded in manuscripts to manipulate AI reviewers into favorable assessments. We propose a triple-blind, multi-LLM pre-screening framework for peer review, developed for a health sciences journal, that formalizes and discloses AI involvement while preserving human reviewers as the final decision-making authority. The framework routes a submission through five stages -- sanitization/anonymization, parallel AI pre-screening,

---

### [294] Evaluating Agentic Code Repair Capabilities in Distributed Systems

**链接**: https://arxiv.org/abs/2608.14863
**作者**: Yibo Yan, Huijuan Wang, Junzhou He, Yizhuo Liang, Shaoyu Wang, Huanchen Sun 等 (7 人)
**来源**: cs.SE cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based coding agents have advanced rapidly on single-process SWE tasks, with frontier models now clustering in the high-70s on SWE-bench Verified. Distributed-system debugging, however, remains an under-explored regime: bugs span processes, nodes, and protocol interactions, with root causes rarely recoverable from source alone and brute-force exploration intractable across non-deterministic interleavings. This leaves two gaps in LLM and agent evaluation: no code-repair benchmark targets distributed-system bugs, and no controlled study isolates how much externally provided debugging context changes agent success on them. We introduce DDBench, a code-repair benchmark of 60 historical bugs mined from 13 open-source distributed systems, partitioned into three difficulty tiers. DDBench evaluates every case under two matched conditions: a symptom-only condition where the agent receives only the bug symptom and repository, and a context-augmented condition where it additionally receives a 

---

### [295] Lymphocyte Mimicry Correction via Region-Level Tissue Reasoning and Unbalanced Optimal Transport

**链接**: https://arxiv.org/abs/2608.17151
**作者**: Xiang Li, Yuqi Wang, Casey C. Heirman, Jihye Heo, Kyle J. Lafata
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cell mimicry arises when different cell types appear morphologically similar. Human pathologists resolve this ambiguity using surrounding tissue context, whereas current vision models either lack contextual reasoning (cell foundation models) or cannot operate at the cell level (pathology MLLMs). We present Loki-OT, which propagates region-level tissue reasoning to individual cell predictions via Unbalanced Optimal Transport, using MLLM-derived density priors as soft guidance for ambiguous cell reassignment. Loki-OT is motivated by the observation that pretrained cell foundation model features already encode discriminative information, including tissue context, but standard cell-level supervision fails to use tissue context effectively. The resulting transport plan is distilled into a lightweight student MLP classifier that learns context-aware decision boundaries within the pretrained feature space. On the independent TCGA-BRCA cohort, Loki-OT achieved lower patient-level MAE than the 

---

### [296] AnchorScore: A CLIP-Based Diagnostic of MLLM Annotation Difficulty

**链接**: https://arxiv.org/abs/2608.16690
**作者**: Yan Ma and Lizhuo Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are widely used for automated annotation, yet their per-class accuracy varies widely (e.g., 12%-98% across the 13 classes of three classroom sub-datasets) and is expensive to measure: evaluating one 27B MLLM on 5,416 validation images takes roughly 14 hours, whereas a frozen-CLIP pass over the same images completes in about 3 minutes. A low-cost signal for ranking classes by expected MLLM annotation difficulty a priori remains underexplored. Building on the AnchorProxy construct (per-class zero-shot CLIP accuracy) introduced in the companion study, this paper systematically evaluates its full-frame formulation, termed AnchorScore here, as an a priori diagnostic that flags the classes MLLMs are least likely to annotate reliably. On classroom behavior data (SCB5, 13 classes, 6 MLLMs), AnchorScore correlates with per-class MLLM accuracy (Spearman rho = 0.769, p = 0.002, n = 13). None of the alternative difficulty predictors (DINOv2, ResNet-50, SigL

---

### [297] RISE: Roadside Infrastructure Sequence Understanding across 3D Tracking and Structured Vision-Language Reasoning

**链接**: https://arxiv.org/abs/2608.16480
**作者**: Yanbo Jiang, Haotian Zheng, Jiahao Wang, Hanxiao Ren, Yitao Xu, Yining Xing 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present RISE (Roadside Infrastructure Sequence Understanding and Evaluation), a framework spanning metric 3D tracking and structured vision-language reasoning in roadside sequences. For metric tracking, our image-only method combines SAM3 video identities with calibration-guided mask agreement for multi-view identity association, recovering persistent 3D tracks without LiDAR or task-specific 3D training. Its calibration-conditioned geometry allows the procedure to be instantiated at different calibrated multi-camera intersections without layout-specific retraining. On 20 human-reviewed clips from six intersections, the generated tracks achieve 66.9 MOTA within the defined multi-view evaluation scope. For structured vision-language reasoning, a human-reviewed MLLM pipeline mines high-value clips and uses a constrained full-context Oracle to construct bbox-grounded predictive QA without exposing future evidence to evaluated models. The resulting RISE-VQA dataset contains 33,910 QA pai

---

### [298] AUTOMATED BIM LOD INFERENCING: A HYBRID APPROACH USING KNOWLEDGE GRAPHS AND MULTIMODAL LARGE LANGUAGE MODELS

**链接**: https://scholar.google.com/scholar_url?url=https://ec-3.org/wp-content/uploads/2026/08/EC32026_259.pdf&hl=zh-CN&sa=X&d=10565844641160711079&ei=r2qEat-SFde46rQPiZPc2QY&scisig=AIVdB-yUF0ARG23fDRpV6g3VII8r&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: T Kim, G Lee
**来源**: 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> This section details the experimental framework established to assess the feasibility and performance of the proposed MLLM based LOD evaluation system. The composition of the dataset and the comparative scenarios designed to verify the

---

### [299] Defake-o3: From Speculative Rationales to Verifiable Evidence for Explainable AIGI Detection

**链接**: https://arxiv.org/abs/2608.16259
**作者**: Bowen Deng, Jiahui Zhan, Yikun Ji, Haozhen Yan, and Jianfu Zhang
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid progress of image generation models calls for AI-generated image (AIGI) detectors that are not only accurate but also explainable and reliable. While MLLM-based detectors can provide natural language explanations, existing methods often generate speculative rationales: they rely on vague or hallucinated artifacts, miss subtle localized flaws from the latest generators, and fail to provide evidence that can be visually verified. We present Defake-o3, an explainable AIGI detector that moves from speculative rationales to verifiable evidence. It combines interactive visual search with verifier-guided evidence alignment: the model iteratively zooms into suspicious regions to inspect fine-grained details, while an Evidence Verifier, trained from human verification annotations, provides reinforcement learning rewards that favor grounded evidence and penalize baseless claims. To support this objective, we construct GroundFake, a dataset designed for grounded explainable detection, w

---

### [300] Multi-Feature Riemannian Hypergraph for Online Test-Time Adaptation of Motor Imagery Brain-Computer Interface

**链接**: https://arxiv.org/abs/2608.16134
**作者**: Siqi Li (1 and 2), Zhi Li (3), Tong Liu (3), Shuai Zhang (3), Yanfei Jia (4), Zhiqiang Yi (4) 等 (10 人)
**来源**: cs.LG cs.HC eess.SP q-bio.NC
**匹配关键词**: EEG, BCI, Brain-Computer Interface, Motor Imagery
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In clinical motor imagery brain-computer interface (MI-BCI) decoding, cross-day transferability and online operation remain two critical challenges. Hypergraphs can improve transferability by capturing higher-order sample relationships, yet existing hypergraph-based methods for online emotion recognition neglect the cross-day benefits of Riemannian geometry widely adopted in EEG transfer learning. To bridge this gap, we propose the Multi-feature Riemannian Hypergraph (MRieHy), a framework tailored for online test-time adaptation in MI-BCI decoding that leverages Riemannian geometry to strengthen cross-day transferability. MRieHy first computes Riemannian means of covariance matrices from cross-day training data to align multi-day distributions. It then constructs a hypergraph over covariance matrices using Riemannian distance, complemented by a second hypergraph over deep features built with cosine similarity. The two hypergraphs are fused via adaptively learned combination weights, jo

---

### [301] SW-ProxyCE: Zero-Query Adversarial Transfer from Public EEG Encoders to Private Downstream Models

**链接**: https://arxiv.org/abs/2608.16931
**作者**: Linhua Cong, Dingkun Liu, Dongrui Wu
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) foundation models have recently emerged as a promising paradigm for EEG decoding by learning reusable representations from large-scale heterogeneous neural recordings. However, the open release of EEG foundation encoders, while facilitating downstream developments, also introduces a previously unexplored security risk: publicly available representations may make private downstream models vulnerable. This paper investigates adversarial transfer attacks in EEG foundation model deployment in a public-encoder and private-downstream setting, where attackers have white-box access to a released encoder and a small task-matched labeled reference set, but no access or query to victim parameters, outputs, or gradients. We propose Shrinkage-Whitened Proxy Cross-Entropy (SW-ProxyCE), a query-free task-aware attack framework that recovers task-level decision geometry from a small labeled reference set through shrinkage-whitened class prototypes, enabling transferable ad

---

### [302] NeuroSense: An EEG -Based Emotion Recognition System using Deep CNN and Flask-Based Web Deployment

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645800/&hl=zh-CN&sa=X&d=11728927454151009482&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-w8GSAM6dh4_yr0PiNH3y79&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: A Vujji, N Pusarla, P Charan, K Vinay, RA Kumar - 2026 5th International Conference …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> a practical deployment layer that allows users to upload new EEG recordings and obtain predictions through an accessible interface. … EEG array, and finally normalizes each EEG channel individually using the z-score method. This makes

---

### [303] Mapping Scalp-Level EEG Representations from a Multimodal In-Ear Device for Mental Fatigue Assessment: A Stacked LSTM-Based Approach

**链接**: https://scholar.google.com/scholar_url?url=https://ascelibrary.org/doi/abs/10.1061/JCEMD4.COENG-17237&hl=zh-CN&sa=X&d=16181209146157691921&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-wGuDHRCtxkznAC2gblmPzc&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: X Fang, J Ma, H Li, Y Yu, X Xing, X Yang 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> scalp EEG . It should be noted that this study focuses on sensor-level scalp EEG representations derived from wearable in-ear EEG signals, … The predicted results are further interpolated to generate EEG topographic maps, which effectively

---

### [304] EEG Emotion Recognition From AI-Generated Biodigital Architecture Images

**链接**: https://arxiv.org/abs/2607.24808
**作者**: Hongye Yang and Eva Guttmann-Flury
**来源**: q-bio.NC cs.AI cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [305] Feasibility of Gamified EEG Neurofeedback Combined with Adaptive Working-Memory Training in Older Adults: A Pilot Study

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3425/16/8/865&hl=zh-CN&sa=X&d=8479581254249545791&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-wTUJzZz4WFP_Lj0B3jBgfX&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: PC Tsai, KT Tang, A Akpan, H Lakany - Brain Sciences, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Objectives: This study evaluates the feasibility of a gamified EEG -based neurofeedback intervention combined with adaptive working-memory training, targeting neural processes associated with attentional inhibition and working

---

### [306] OOD Detection for EEG-based Machine Learning in High-Risk Environments

**链接**: https://arxiv.org/abs/2608.17620
**作者**: Philipp Bomatter, Henry Gouk
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning models for electroencephalography (EEG) analysis show great promise across a wide range of applications, but their deployment in high-risk domains is hindered by their vulnerability to distribution shifts. Encountering out-of-distribution (OOD) data can lead to catastrophic, overconfident predictive failures. While OOD detection methods can mitigate these risks, they remain heavily under-explored for EEG. Moreover, evaluations in the broader literature typically evaluate OOD detection performance in isolation, ignoring their practical impact on downstream applications. To bridge this gap, we introduce a benchmark for EEG OOD detection, evaluate a broad range of methods, and furthermore evaluate their value in two clinical downstream prediction task. Our results disentangle OOD detection and model uncertainty estimation capabilities, which are frequently conflated in the literature, provide actionable insights about the current state of the art for EEG OOD detection and

---

### [307] Automating Learner Assessment: Benchmarking Machine Learning and Deep Learning Models for EEG-Based Familiarity Prediction

**链接**: https://arxiv.org/abs/2608.16541
**作者**: Isuru Nanayakkara, Thilina Halloluwa
**来源**: eess.SP cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective assessment of learning remains a fundamental challenge in education. Electroencephalography (EEG) provides a direct, non-invasive window into the neural correlates of knowledge acquisition, including cognitive familiarity. This study benchmarks fifteen machine learning (ML) and deep learning (DL) models for EEG-based familiarity prediction across two cognitive domains: faces (factual knowledge) and mathematical equations (conceptual knowledge). Using continuous EEG data from 23 participants, we extract spectral features (Power Spectral Density) across six frequency bands. We show that while standard stratified cross-validation yields artificially high classification performance (up to 0.9853 F1-score using CNN) due to temporal leakage across neighboring epochs, a rigorous trial-independent validation (Group K-Fold) drops the peak performance to 0.6038 F1-score (using CNN), which is still statistically significant above the 25% chance level. This highlights the critical necess

---

### [308] A 2-Block Architecture for Real-Time EEG Gait Decoding: A Pilot Study

**链接**: https://arxiv.org/abs/2608.02083
**作者**: Shantanu Sarkar, Saurabh Prasad and Jose L. Contreras-Vidal
**来源**: cs.LG cs.HC eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [309] Delta2Gamma: Band-Wise Adaptive Contrastive Learning of EEG for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2608.17231
**作者**: Chanwoo Park and Chanwoo Kim
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-cost, scalable screening for dementia remains an open problem. Imaging-based diagnosis is costly and hard to deploy widely. Electroencephalography (EEG) is portable and inexpensive, but its recordings are noisy, vary widely across subjects, and carry few clinical labels. We tackle this with Delta2Gamma, a self-supervised framework that learns EEG representations from unlabeled data by contrasting augmented views of each signal. Rather than treat EEG as a single stream, Delta2Gamma decomposes every recording into the five canonical neural rhythms (delta, theta, alpha, beta, gamma). Each band gets its own encoder and projection head. Each also gets a temperature that is predicted adaptively during contrastive training, so bands with different signal statistics are balanced automatically. On the ADFTD cohort under a strict leave-one-subject-out protocol, Delta2Gamma separates Alzheimer's disease from cognitively normal controls with 92.4\% accuracy. This exceeds both supervised backbo

---

### [310] Backpropagation-Free Test-Time Adaptation for Lightweight EEG-Based Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2601.07556
**作者**: Siyang Li, Jiayi Ouyang, Zhenyao Cui, Ziwei Wang, Tianwang Jia, Feng Wan 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [311] EEG -Based Neurophysiological Assessment of Pharmacopoeial-Quality Essential Oils and Development of Stable Micro-Emulsion Systems for Aromatherapy …

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/1424-8247/19/8/1291&hl=zh-CN&sa=X&d=14619174266308188666&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-wjs-oIKWcurF9UyFUL-msa&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: M Karaaslan, HK İleri Özler, B Ergene… - Pharmaceuticals, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography ( EEG ) has emerged as a valuable tool for evaluating neurophysiological responses to essential oils. Numerous studies using EEG analyses have investigated neurophysiological responses to essential oils and

---

### [312] Automated autism spectrum disorder detection using EEG signals and time-frequency visibility graphs

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306452226005592&hl=zh-CN&sa=X&d=10894229036918333289&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-yEZk0MgxeZPb87WEtcnTWr&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: NK Rao, YR Veeranki - Neuroscience, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Early and objective screening of Autism Spectrum Disorder (ASD) remains challenging because conventional diagnosis primarily relies on behavioural assessment and clinical observation. To address this limitation, this study proposes

---

### [313] Leakage-Audited Benchmarking Reveals Limited Evidence for Cross-Subject Auditory-Evoked EEG Vowel Perception Decoding

**链接**: https://arxiv.org/abs/2605.00865
**作者**: Xiaoyang Li, Zeyan Tao
**来源**: eess.SP cs.CL cs.CV cs.LG cs.SD q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [314] NestedSleepNet: Physiology-Guided Multi-scale Learning with Hierarchical Temporal Memory for EEG Sleep Stage Classification

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-31673-8_12&hl=zh-CN&sa=X&d=1275686922292718774&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-xA8C6E4gHHKIDuW60StNNu&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: RK Rai, S Parui, DK Singh, RH Singh - International Conference on Pattern …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Automatic sleep stage classification from electroencephalography ( EEG ) remains challenging due to the coexistence of short-term transient events and long-range temporal dependencies that evolve across sleep cycles. In this work, we propose

---

### [315] A Novel Adversarial Approach for EEG Dataset Refinement: Enhancing Generalization Through Proximity-to-Boundary Scoring

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6221036/6352949/11655921.pdf&hl=zh-CN&sa=X&d=9354165953619934572&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-y4oUhX8DQNwf2kwsJm-lAf&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: SJ Kim, H Kong, DH Lee, HG Kwak, SW Lee - IEEE Transactions on Cybernetics, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> As deep learning (DL) performs remarkably in pattern recognition from complex data, it is used to interpret user intentions from electroencephalography ( EEG ) signals. However, the DL models trained on EEG datasets have low generalization ability

---

### [316] A Multi-Scale Adaptive EEG Feature Selection and Weighting Method for Mental Workload Estimation in Rapid Serial Visual Presentation

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/7333/4359219/11655955.pdf&hl=zh-CN&sa=X&d=5976701477179555745&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-yYCDMQrwfeirWW1CqPQ7VD&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: Y Wang, W Wei, K Wang, K Zhao, S Qiu, H He - IEEE Transactions on Neural … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this study, we adopted a widely used and previously validated EEG preprocessing pipeline to ensure data quality for cognitive workload … EEG trial, we employed time windows of varying lengths (t=1,2,3,...,T, T=10 s) to extract EEG

---

### [317] An Explainable Hybrid Deep Learning Framework for Comorbid Psychological Disorder Diagnosis using EEG and Neuroimaging Data

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11645715/&hl=zh-CN&sa=X&d=17469618666482936190&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-w6ldEUcJIf7K8dpQ-yZzt1&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: P Yogasrinithi, P Vaishnavi, E Elakiya - 2026 4th International Conference on …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Comorbid psychological disorders present complex diagnostic challenges due to overlapping symptomatology. This research proposes an explainable hybrid deep learning framework for differential diagnosis using EEG and structural MRI data. We

---

### [318] Reciprocal relationships between stimulus duration, electroencephalography features, and cortical spreading depression during electroconvulsive therapy

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-67197-3_reference.pdf&hl=zh-CN&sa=X&d=10144015631661908213&ei=r2qEapiDBoPIieoPhI6G0Ac&scisig=AIVdB-xk5xWmGh_nZiLb4-QuMoax&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: K Yoshioka, T Iwamoto, S Ishikawa, M Hanazaki… - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Therefore, the present study aimed to investigate ECT-induced CSD and its impact on EEG features through extracellular DC potential and EEG … and EEG findings are necessary for clinical effects12-14.In clinic, the following EEG findings

---

### [319] M-LINKX: Multiview Graph Learning for Brain Cognitive Disease Detection

**链接**: https://arxiv.org/abs/2608.14847
**作者**: An Phan, Yufei Jin, and Xingquan Zhu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalogram (EEG) is a non-invasive and relatively low-cost procedure that measures brain electricity for the detection of cognitive diseases. EEG-based classification of dementia-related conditions, including Alzheimer's disease (AD), mild cognitive impairment (MCI), and frontotemporal dementia (FTD), remains challenging because EEG signals are noisy, non-stationary, and vary across subjects. Segment-based learning provides a practical way to model long EEG recordings by converting them into fixed-length inputs. For each segment, discriminative information may be explored by using signals within each channel (i.e. electrode), as well as interactions between EEG channels. In this paper, we propose M-LINKX, a multi-view graph learning framework for EEG-based dementia classification. For each segment, we extract channel-level node features and construct multiple functional-connectivity (FC) graph views, where each view is defined by a specific combination of connectivity metric,

---

### [320] Global AI Regulations for FAIR and Ethics in High-Risk Use Cases: A Comparative Review

**链接**: https://arxiv.org/abs/2608.14562
**作者**: Aasish Kumar Sharma, Dimitar Koysev, Christopher Anich, Roshni Kumari Ojha, Julian Kunkel
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI governance is shifting from voluntary ethics to enforceable, risk-based regulation, yet cross-jurisdictional divergence creates compliance uncertainty for operators of high-stakes AI. We present a comparative matrix for the EU, US, and China that maps (i) risk classification triggers, (ii) binding obligations, (iii) enforcement and accountability mechanisms, and (iv) the degree to which FAIR principles are operationalised in practice. We stress-test the matrix on three high-impact domains: Electroencephalography (EEG)-guided rehabilitation robotics, AI-enabled debt collection in prospective Central Bank Digital Currency (CBDC) ecosystems, and AI-driven allocation of scarce Graphics Processing Unit (GPU) resources in emerging AI Factory infrastructures. Using primary legal texts and implementation evidence, we identify three recurring gaps: weak interoperability mandates, difficult operationalisation of cross-regime obligations (AI + sector regulation + data protection), and under-sp

---

### [321] MUPA$^{2}$E: Multimodal Unified Perception with Asymmetric Attention for Emotion Assessment

**链接**: https://arxiv.org/abs/2608.15999
**作者**: Stefanos Gkikas, Eric Nichols, Christian Arzate Cruz, Randy Gomez
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic emotion assessment can benefit from combining neural and behavioral signals, but many multimodal approaches rely on separate, modality-specific feature-extraction pipelines before fusion. This paper presents MUPA\textsuperscript{2}E, a unified perception framework that processes facial video and electroencephalography (EEG) through a single shared asymmetric-attention backbone. Facial video is represented through axis-folded frame tokens, while EEG is processed either as a raw multichannel waveform or projected into the spatial domain for multimodal fusion. The framework is evaluated on the DMER dataset under a stratified subject-independent protocol, comparing unimodal video, unimodal EEG, and fused video--EEG configurations with per-channel and merged EEG projections. Using the original recordings, with shorter trials zero-padded to match the longest duration, merged fusion at stride~$30$ achieves the highest validation performance and a test accuracy of $70.07\%$. Further 

---

### [322] LiveHouse-TS: An Open-world Living Benchmark for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2608.17299
**作者**: Haomin Wen and Ziyu Zhou and Qingxiang Liu and Siru Zhong and Yuxuan Liang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) have recently emerged as a highly promising paradigm for cross-domain zero-shot forecasting. However, existing evaluation protocols predominantly rely on static benchmarks with fixed historical test windows. While these benchmarks provide a valuable baseline snapshot, they evaluate an average performance on a fixed history, failing to capture how models behave in continuously evolving real-world environments characterized by seasonal variations, distribution shifts, and unexpected events. To bridge this gap, we introduce LiveHouse-TS, the first open-world living benchmark infrastructure for TSFMs. By evaluating models prequentially on real future data in open-world environments, LiveHouse-TS shifts time series benchmarking from snapshot accuracy to continuous temporal validity. Rather than acting as a one-off leaderboard, our infrastructure serves as a continuous time series infrastructure designed to explore vital, long-term scientific questions: 

---

### [323] Benchmark-Based Comparative Assessment of Publicly Benchmarked Indian Foundation Models: A Capability and Evaluation-Maturity Framework

**链接**: https://arxiv.org/abs/2608.11891
**作者**: Avinash Agarwal and Vridhi Jain
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [324] When More Foundation Models Means Less: Diagnosing and Addressing Multi-View Fusion Failure

**链接**: https://arxiv.org/abs/2608.17490
**作者**: Yibo Liu and Bowen Jiang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation-model hubs turn multi-view fusion into a selection problem: from a large heterogeneous encoder pool, which views should be fused, and how many? We show that downstream performance is non-monotonic in the number of fused encoders; later views can be redundant or task-misaligned, causing accuracy to saturate or decline. We formalise this setting as view-set composition and propose KAGES (Kernel-Alignment Greedy Encoder Selector), a label-aware method that orders frozen encoders by their marginal gain in centred kernel-target alignment. KAGES requires no downstream classifier training during selection, evaluates each candidate in $\mathcal{O}(n^2)$ time independent of encoder dimension, and admits a conditional $(1-e^{-\gamma})$ prefix-wise guarantee under monotonicity and a positive submodularity ratio. Across five recognition regimes and low-shot, larger-pool, and full-data protocols, KAGES improves average AULC over full fusion by 3.9, 5.8, and 3.3 points, respectively, and 

---

### [325] Zero-Shot Adaptation of Medical Vision Foundation Models for High-Frequency Micro-Ultrasound Prostate Segmentation

**链接**: https://arxiv.org/abs/2608.14796
**作者**: Ayusha Abbas, Saram Abbas, Kabita Adhikari
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prostate cancer claims a life every 80 seconds. Early detection is needed to prevent disease progression, and both PSA density calculation and biopsy decisions rely on knowing the exact boundary of the gland. Conventional ultrasound at 6-12 MHz blurs this boundary, missing one in three high-risk cancers. Micro-ultrasound (29 MHz) improves resolution threefold but introduces dense acoustic speckle that obscures the outer wall; given the same image, two clinicians draw outlines differing by over 10% in area. Supervised methods are costly and generalise poorly across scanners. Can a foundation model segment the prostate with no training data? We present the first zero-shot pipeline for this modality: MedSAM, pre-trained on over 1.5 million medical images, localises the prostate; we then apply CLAHE to sharpen the outer wall, binary dilation to recover missed pixels, and Fourier smoothing (4 modes, s=1.05) to refine the boundary. MedSAM requires a spatial prompt, so we evaluate bounding-bo

---

### [326] Beyond Natural-Image Foundation Models: Benchmarking Satellite Pretraining for Ophthalmic Image Analysis

**链接**: https://arxiv.org/abs/2608.15195
**作者**: Lovre Antonio Budimir, Mingya Alexa Gong, Alyssa Foong Quinney, Ivana Matovinovi\'{c}, Yukun Zhou, Pearse A. Keane 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision Foundation Models (VFMs) have emerged as a promising approach in medical imaging, producing broadly applicable systems that can be efficiently adapted across diverse imaging modalities, anatomical regions, and clinical tasks. However, VFMs require extensive training data, and their progress in medical image analysis is constrained by limited data availability, privacy concerns, and high development costs. To alleviate these constraints, medical VFMs (MedVFMs) are often built upon weights from generalist models pretrained on vast amounts of publicly available natural images, introducing a substantial distribution shift for medical task adaptation. To address this, we propose satellite imagery as a novel pretraining domain for MedVFM development and benchmarking, motivated by its closer visual alignment with medical data and its freedom from the privacy constraints that limit medical datasets. Across multiple ophthalmic imaging modalities, we compare DINOv3-SAT493m pretrained on 4

---

### [327] What Makes a Good Layer? Assessing the Layer-Wise Intrinsic Properties of Music Foundation Models

**链接**: https://arxiv.org/abs/2608.14819
**作者**: Angelos-Nikolaos Kanatas, Yuexuan Kong, Pablo Alonso-Jim\'enez, Xavier Serra, Dmitry Bogdanov
**来源**: cs.SD cs.LG eess.AS
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Music foundation models are commonly used as frozen audio feature extractors, yet selecting which layer to extract from remains largely heuristic. Current practice defaults to fixed depths or multi-layer fusion, with limited understanding of why certain layers transfer better across downstream tasks or how representation quality varies with depth and pre-training paradigm. We conduct a systematic layer-wise analysis of 12 music foundation models spanning three pre-training paradigms (masked modeling, autoregressive modeling, and contrastive learning), characterizing their hidden representations through intrinsic geometric and transformation-based properties. Correlating label-free representation-quality metrics with layer-wise performance across 15 downstream tasks, we find that several metrics track layer quality for genre classification, emotion recognition, automatic tagging, and beat tracking, albeit with varying strength across tasks and pre-training paradigms. However, all metric

---

### [328] Emotion Across Speech and Faces: Shared Affective Mechanisms in Multimodal Foundation Models

**链接**: https://arxiv.org/abs/2608.17102
**作者**: Xiutian Zhao, Luqi Sun, Bj\"orn Schuller, Berrak Sisman
**来源**: cs.CL eess.AS eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern multimodal foundation models (MFMs) have made rapid progress on tasks requiring integrated perception across speech, vision, and language, including emotion recognition. However, it remains unclear whether they recognize speech and facial emotion through shared affective functional units or modality-specific pathways. We explore emotion-sensitive neurons (ESNs), sparse decoder neurons selectively associated with emotion categories, in three MFMs: Gemma-4-12B-it, MiniCPM-o-4.5, and Qwen2.5-Omni-7B. Using speech emotion recognition and facial expression recognition as complementary probes, we identify acoustic and visual ESNs. Visual ESNs are causally meaningful: deactivating them selectively impairs recognition of the associated facial emotion, whereas steering their activations selectively enhances recognition of that emotion relative to other emotion categories. Acoustic and visual ESNs further show emotion-matched overlap and similar layer-wise distributions, indicating partia

---

### [329] MoRAX: Mobility-based Representation Augmentation for Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2608.17848
**作者**: Ya Wen, Jixuan Cai, Yulun Zhou, Alec Kirkley
**来源**: cs.LG cs.SI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial Foundation Models (GFMs) are emerging as a powerful paradigm for learning semantically rich and geographically consistent visual and physical representations. However, their reliance on Earth-observation (EO) data leaves information about human activity largely underrepresented. Human mobility data reveals the functional and relational structure between regions that is missing from EO data, but is often limited only to the city where it is observed, making it challenging to use for transferable urban representation learning. We introduce MoRAX, a lightweight framework for augmenting geospatial embeddings with functional structure derived from human mobility. MoRAX preserves the coverage and consistency of a GFM while providing information about the functional connectivity among urban regions, permitting zero-shot deployment in unseen cities with or without available mobility data. Across four target cities spanning two countries, the MoRAX teacher model, which observes mobil

---

### [330] Understanding the Surprising Generalization Properties of Tabular Foundation Models

**链接**: https://arxiv.org/abs/2608.17957
**作者**: Nour Shaheen, Junwei Ma, Alex Labach, Frank Hutter, Valentin Thomas, Anthony L. Caterini
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [331] A Comprehensive Survey of Wireless Foundation Models for AI-Native 6G Networks

**链接**: https://arxiv.org/abs/2608.14694
**作者**: Naveed Khan, Besan Al Sbeihi, Maryam Alshehhi, and Nasir Saeed
**来源**: cs.AI cs.NI eess.SP
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are emerging as a transformative paradigm for AI-native sixth-generation (6G) wireless networks by enabling scalable, transferable, and data-efficient intelligence across diverse communication tasks. Unlike conventional deep learning models that are trained for individual applications, wireless foundation models (WFMs) learn generalized representations from large-scale heterogeneous wireless data and can be efficiently adapted to communication, sensing, localization, and network optimization tasks with minimal task-specific supervision. Despite rapid progress, current research remains fragmented across architectures, training paradigms, and application domains, with no unified survey dedicated to the design, learning, and deployment of WFMs. This survey presents a comprehensive and unified review of wireless foundation models. We first establish the fundamental concepts of WFMs and introduce a taxonomy that organizes the field according to model architectures, pre-tra

---

### [332] Beyond Accuracy: Assessing Calibration of Geospatial Foundation Models and Their Sensitivity to Distribution Shifts

**链接**: https://arxiv.org/abs/2608.16614
**作者**: Nils Lehmann, Jakob Gawlikowski, Burak Ekim, Isaac Corley, Xiao Xiang Zhu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial Foundation Models (GeoFMs) are most commonly ranked and selected by accuracy on standard benchmark conditions via averaged ranks. We show that this protocol is too narrow: the promised deployment in critical EO tasks requires further angles of analysis, mainly calibration, the agreement between a model's confidence and its correctness. Across 16 frozen encoders, four classification and five segmentation datasets, and two orthogonal stress axes, every encoder degrades as corruption intensifies, and the ranking changes as well. Across the four classification benchmarks, EO-pretrained and ImageNet-pretrained encoders are indistinguishable on clean accuracy and clean calibration, and EO pretraining provides no more stability under shift than ImageNet pretraining. Under shift the GeoFMs drift further into overconfidence than the ImageNet-pretrained encoders, at every grade and in every corruption family. A centered kernel alignment (CKA) analysis ties this to representational rig

---

### [333] 6G Native AI and Channel Foundation Models

**链接**: https://arxiv.org/abs/2608.14591
**作者**: Shugong Xu, Jun Jiang, Yuan Gao
**来源**: eess.SP cs.IT cs.LG math.IT
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of artificial intelligence (AI) and wireless communications is widely regarded as a core objective of sixth-generation (6G) systems. However, both the meaning of native AI and the type of AI capability that should be embedded into future wireless systems remain open to interpretation. This paper discusses 6G native AI from a system-design perspective and argues that native AI should be co-designed, optimized, and deployed as an intrinsic component of the wireless system rather than as a removable post-deployment add-on. From this perspective, conventional task-specific supervised models are difficult to use as the main technical basis of native AI because they depend heavily on labeled data, generalize poorly across propagation conditions, and require fragmented designs for different channel-related tasks. Motivated by these limitations, we position channel foundation models (CFMs) as a channel-centric foundation-model paradigm for 6G native AI. We define the scope of C

---

### [334] Mint-Agent: Introducing Finance-Native Agentic Foundation Models

**链接**: https://arxiv.org/abs/2608.16386
**作者**: Mint-Agent Team, B. Zhang, Yaze Geng, Lei Tang, Yaoyang Yi, Zonghan Wu 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial agents must do more than recall domain knowledge: they must be both reliable, executing precise operations over grounded evidence, and executive, sustaining long-horizon research whose conclusions remain auditable. We present Mint-Agent, a family of finance-native agentic models designed around these two scales of financial intelligence. Mint-Agent is built upon three pillars: data, harness, and algorithm. Our data engine constructs clean, specialized tasks for atomic financial capabilities and long-horizon agentic execution from real-world financial sources. MintHarness enables stable interaction with open-ended environments and maintains auditable evidence trails across extended research trajectories. Our training recipe combines SFT, critical-step OPD, and RLVR to develop separate financial reasoning and agentic execution experts, which are then unified through model merging and multi-teacher on-policy distillation into compact, general-purpose financial agents. This pipel

---

### [335] AlignJEPA: Predictive Vision-Language Alignment for Remote Sensing Foundation Models

**链接**: https://arxiv.org/abs/2608.15456
**作者**: Md Aminur Hossain, Omkumar Vaghasiya, Rajeev Ranjan Dwivedi, Vinod Kurmi, Biplab Banerjee
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote sensing (RS) foundation models provide transferable Earth observation representations across sensors, resolutions, and geographies, yet most remain weakly aligned with natural language, limiting natural-language archive search, image-text retrieval, and question-conditioned analysis. We propose AlignJEPA, a JEPA-inspired predictive vision-language alignment framework for remote sensing foundation models. AlignJEPA uses a pretrained AnySat visual encoder and a RemoteCLIP text encoder while training only a lightweight predictive alignment network. Instead of relying on global image--text contrastive alignment alone, the framework predicts remote-sensing text embeddings from masked visual foundation-model tokens. Its mask-aware multi-scale predictive aligner aggregates visible tokens at fine, regional, and global scales, jointly models them with a cross-scale Transformer, and projects the resulting representation into the text space using learned query pooling. Training combines se

---

### [336] PERO: Efficient Robust Post-Training Foundation Models for Encrypted Traffic Classification

**链接**: https://arxiv.org/abs/2608.15504
**作者**: Wumei Du, Jiarong Wen, Kaiyu Zhang, Zi Yang, Yiqin Lv, Longfei Zhang 等 (8 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Encrypted traffic classification is vital for network security, yet real-world deployments are inherently sensitive to rare but high-loss errors such as misclassification of malicious traffic. The encrypted traffic foundation model, as a promising general-purpose technique, can achieve impressive overall performance. However, employing standard objectives such as empirical risk minimization often overlooks high-risk tail events, and commonly used performance metrics hardly reflect robustness limitations in risk-sensitive scenarios. Directly applying robust optimization objectives, such as conditional value-at-risk, to post-training is computationally prohibitive for large models, as identifying high-loss samples exhausts substantial computation. To this end, we propose Pre-Evaluation Robust Optimization (PERO), an efficient robust post-training framework for encrypted traffic foundation models. PERO employs a lightweight proxy to estimate sample-wise risk and selects a subset of high-r

---

### [337] Earth Observation Foundation Models for Terrestrial Ecohydrology: From Representation Learning to Process Inference

**链接**: https://arxiv.org/abs/2608.15282
**作者**: Yi Yu, Jian Peng, Yucheng Lin, Trevor F. Keenan, Thomas F. A. Bishop
**来源**: cs.LG cs.CV physics.bio-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth observation foundation models (EOFMs) are emerging as reusable representation frameworks for data-driven retrieval, prediction and process modelling within ecohydrology, which integrate EO, meteorological forcing and process models to characterise coupled water, energy and carbon dynamics in vegetation and soil across scales. However, there is yet to be an ecohydrology-specific synthesis assessing the EOFM relevance, application evidence or evaluation requirements under uncertain reference data, scale mismatch and temporal dependence. Here, we develop a framework for determining when EOFMs support interpretable inference and identify a mismatch between EOFMs and ecohydrological requirements. Firstly, an observation-to-inference hierarchy shows that relevance depends on target-specific sensing pathways, spatial-temporal support and traceable uncertainty. Secondly, a meta-analysis shows that pretraining is dominated by reflected optical and active-microwave data, with sparse therma

---

### [338] Improving Complex Moir\'e Removal with Generative Supervision

**链接**: https://arxiv.org/abs/2608.17883
**作者**: Xinyang Gu, Zhilu Zhang, Honglei Xu, Yanting Mei, Yukang Ding, Wangmeng Zuo
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The availability of high-quality paired data is essential for training learning-based image demoir\'eing models. However, it remains challenging for existing datasets to encompass the complex moir\'e patterns captured in uncontrolled real-world scenarios. Such degradations typically manifest as large-scale, multicolored moir\'e patterns. Moreover, these patterns frequently occur in images for which clean counterparts are difficult to obtain, such as photographs acquired from public displays or existing online resources. In this work, we propose a novel data engine designed to improve the removal of complex moir\'e patterns by generating training supervision. Specifically, we initially collect real-world images containing complex moir\'e patterns and localize the corresponding screen regions. Multiple image-conditioned generative foundation models are subsequently deployed to produce candidate references. To establish reliable supervision, these candidates are subjected to patch-level q

---

### [339] Prototype-Rectified Iterative Self-supervised Manifold Denoising under Severe Acoustic Shift

**链接**: https://arxiv.org/abs/2608.15037
**作者**: Ashish Anand Shukla, Rini Smita Thakur, Aryan Das, Vinod K. Kurmi
**来源**: cs.SD cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-Text Foundation Models (ATMs) fail catastrophically under severe acoustic noise, yet existing adaptation strategies either rely on gradient-based Test-Time Adaptation (TTA), which reinforces noise rather than signal, or on prompt tuning that requires privileged noise annotations unavailable at inference. We address these failures with PRISM (Prototype-Rectified Iterative Self-supervised Manifold Denoising), a training-free, source-free TTA framework grounded in the Affine Noise Hypothesis: severe acoustic noise induces a low-rank affine shift in the multimodal latent space, with more than 90% of distortion energy confined to the leading 60 principal components. PRISM estimates and reverses this distortion from an unlabeled target batch using frozen text prototypes as geometric anchors via three closed-form geometric corrections compiled into a single static projection matrix by Affine Bias Regression. At inference, adaptation reduces to one matrix-vector multiplication in 0.0009 

---

### [340] Foundation Agents Meet Agentic Deep Research: Evidence-Grounded Clinical Code Forecasting

**链接**: https://arxiv.org/abs/2608.17075
**作者**: Junda Wang, Meysam Ghaffari, Akshat Choube, Mohsen Sharifi Renani, Hong Yu, Carlos Morato
**来源**: cs.CL cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Next-encounter ICD forecasting predicts which standardized diagnosis codes will be documented at a future visit from the longitudinal record available beforehand. The task is prospective and multi-label: the target note does not yet exist, and several codes may be correct. Structured EHR foundation models capture recurrence and temporal progression, whereas language foundation models generate flexible diagnostic hypotheses. We introduce ICD-Deepresearch, a DeepResearch workflow that composes these predictive foundation models with medical search and ICD dictionaries. Because no source reveals the future code set, research evaluates candidate transitions by linking patient evidence, external clinical relations, and exact code semantics under a fixed top-K budget. Candidate Generation uses SparseEHR to produce an EHR Prior that initializes two bounded Research Expansion rounds; an independent GPT-5 Direct Forecast supplies complementary candidates. Final Selection validates, deduplicates

---

### [341] Self-Routed Tensor Adapters for Parameter-Efficient Universal Visual Adaptation

**链接**: https://arxiv.org/abs/2608.16384
**作者**: Suraj Yadav
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Universal visual representations require adaptation mechanisms that adapt across heterogeneous domains without fragmenting knowledge into domain-specific modules. Parameter-efficient fine-tuning adapts frozen visual foundation models efficiently, but standard low-rank adapters use a fixed subspace for all inputs, which can be restrictive when domains differ in style, background, and semantic context. MoE-based adapters improve specialization through multiple expert pathways, but often rely on external routers and large expert banks, adding parameters and separating routing from adaptation. We propose \textbf{Self-Routed Tensor Adapters}, a compact framework for multi-domain visual adaptation. SRTA projects each input into a low-rank space, computes routing weights from this representation using a learnable domain matrix, and uses these weights to blend slices of a shared Tucker core. This produces a sample-specific adaptation matrix without an external gating network, allowing shared v

---

### [342] HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-manipulation via Hierarchical Action Flow and Spectral Latent RL

**链接**: https://arxiv.org/abs/2608.16837
**作者**: Langzhe Gu, Chengkai Hou, Meng Li, Xinhua Wang, Jiaming Liu, Xinyuan Lv 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humanoid robots hold great promise as general-purpose agents in human-centered environments, yet generalist vision-language-action (VLA) foundation models are not readily applicable to humanoid whole-body loco-manipulation. The high dimensionality and interdependence of humanoid motions make it challenging for conventional single-stage VLA architectures to coordinate locomotion, waist posture, and dual-arm manipulation effectively. Moreover, policies trained through offline behavior cloning can remain suboptimal during real-world deployment. Although online reinforcement learning can refine policies through real-world interaction, directly tuning large VLA backbones demands excessive computation and may introduce safety risks during real-robot exploration. To address these bottlenecks, we introduce HAF (Humanoid Adaptation Framework), a two-part framework consisting of HAF-VLA and HAF-Steer that transfers off-the-shelf generalist VLA foundation models to humanoid whole-body loco-manipu

---

### [343] ARASH: Adaptive Retrieval And Shot Selection for Tabular Prediction

**链接**: https://arxiv.org/abs/2608.17856
**作者**: Samirasadat Jamalidinan, Yue Xu, Kazem Cheshmi
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular prediction is a critical task across numerous applications. The recent success of large language models has sparked various approaches for adapting them to the tabular domain. A prevalent strategy involves training or fine-tuning specialized Tabular Foundation Models (TFMs) such as TabPFN. However, TFMs require substantial computational resources, and frequent model retraining is often impractical. In-context learning (ICL), specifically, few-shot prompting, offers a resource-efficient alternative to enhance performance. Yet, identifying the most relevant rows to serve as shots remains a challenge for tabular data. This paper introduces ARASH (Adaptive, query-specific Retrieval And Shot selection), a method that improves TFM efficiency by selecting optimal shots based on local neighborhood analysis within the training set. Our results demonstrate that ARASH reduces the prompt length and memory usage of TabPFN by 1261.5$\times$ and 2.56$\times$, respectively, while providing com

---

### [344] Toward AI-Friendly Cartography: Understanding How Color Design Influences Foundation Model Spatial Reasoning on Sequential Choropleth Maps

**链接**: https://arxiv.org/abs/2608.15736
**作者**: Yonghe Sun, Zhenjia Liu, Hua Liao, Wenjia Xu, Nai Yang, Weihua Dong 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) increasingly support multimodal and geospatial reasoning, yet it remains unclear whether cartographic principles designed for human perception are equally effective for machines. Focusing on sequential choropleth maps, we examine how hue palette, color ordering, and lightness contrast influence FM spatial reasoning. We construct a controlled benchmark of 5,760 maps and 28,800 questions spanning Attribute Identify, Spatial Recognition, Compare, Rank, and Pattern Delineate, and evaluate 21 open-source and proprietary multimodal FMs. Results show that hue choice has limited and inconsistent effects, whereas disrupting sequential color ordering substantially reduces performance, especially for comparison and ranking. Reduced lightness contrast also consistently impairs reasoning, while increasing contrast beyond sufficient separability provides only marginal gains. LoRA fine-tuning improves overall accuracy but preserves these relative sensitivities. Additional fact

---

### [345] Rapid Debris-Volume Estimation from Post-Hurricane Aerial Imagery

**链接**: https://arxiv.org/abs/2608.17165
**作者**: Kooshan Amini, Jamie Ellen Padgett, Guha Balakrishnan
**来源**: cs.CV eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hurricane debris removal is planned, contracted, and federally reimbursed on the basis of volume estimates, yet operational practice still relies on parametric forecasts with 41-90% documented over-estimation or on truck-load tallies that arrive only after hauling begins. We present DebrisHeightNet, a segmentation-conditioned monocular debris-height network that estimates spatially explicit debris volume from a single pass of post-event aerial RGB imagery, the kind of survey routinely flown within days of a hurricane landfall. We train only a lightweight 1.08 M-parameter head on top of two frozen vision foundation models. This head regresses height from a Depth Anything V2 backbone, conditioned on the debris segmentation of CLIPSeg-debris from our prior work. Because no post-hurricane debris-height ground truth exists, we synthesize the training target by confidence-weighted LiDAR-monocular fusion (CW-LMF), designed to suppress non-debris LiDAR returns. This fused target is a construct

---

### [346] Scale Matters: Adaptive Granularity Selection for Cross-Species 3D Plant Organ Segmentation

**链接**: https://arxiv.org/abs/2608.17803
**作者**: Carla Salazar and Lazaros Nalpantidis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent 3D foundation models provide powerful feature representations for point cloud learning by controlling spatial granularity. However, relying on a fixed spatial granularity severely limits generalization in applications like plant phenotyping, where organ morphology and size vary substantially across species and growth stages. To address this, we propose AGS-PlantSeg, a few-shot 3D plant organ segmentation method that leverages the frozen Utonia (

---

### [347] SAGE-OR: Semi-supervised Adaptive Scene Graph Generation for Operating Rooms

**链接**: https://arxiv.org/abs/2608.15336
**作者**: Brandon Leblanc, Charalambos Poullis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current surgical scene graph generation methods depend on dense multi-modal supervision and specialized hardware (synchronized RGB-D sensors, calibration rigs), making dataset construction expensive and restricting all existing benchmarks to simulated environments. We propose SAGE-OR, a feature-centric framework that replaces the traditional detect-then-reason paradigm with a decoupled representation-reasoning paradigm in which localization is derived from frozen foundation models, encoded implicitly in pre-computed features, and used without any localization supervision, while a lightweight graph transformer performs relational reasoning over cached features. We employ a semi-supervised formulation with general-purpose segmentation prompts to eliminate localization supervision while enabling unsupervised context augmentation through additional prompt-driven entities, such as hands, which are absent from annotations. General-purpose prompts are used to induce near-perfect recall, while

---

### [348] Decoupling Parcellation from Classification: Systematic Benchmark of Fast Brain Segmentation Methods for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2608.16039
**作者**: Jiadao Zou, Hongyu Guo, Wei Xi
**来源**: eess.IV cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain parcellation and classification are typically evaluated in isolation, yet downstream AD detection performance depends on their interaction. We decouple these components and systematically benchmark fast deep learning parcellation methods (SynthSeg+, OpenMAP-T1) against the FreeSurfer (FS-HV) clinical baseline through down- stream AD classification on OASIS-1. Our factorial design evaluates three parcellation methods, two volumetry strategies (hard vs. soft), and four classifier paradigms (clinical thresholds, supervised feedforward networks, ensemble methods, and foundation models with zero/few-shot prompting), with all results quantified using BCa Bootstrap 95% confidence intervals.

---

### [349] SUGFW+: An Uncertainty-guided Feature Weighting Framework for Cold Start Active Adaptation of SAM in Medical Image Segmentation

**链接**: https://arxiv.org/abs/2608.16110
**作者**: Xiaochuan Ma, Ning Zhu, Jia Fu, Lanfeng Zhong, Hanyu Jiang, Bin Song 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cold Start Active Learning (CSAL) is important in improving the performance of a medical image segmentation model with low annotation budget by querying a small subset for annotation from an unlabeled training set. Existing CSAL methods typically rely on inefficient dataset-specific Self-Supervised Learning (SSL) to map the unlabeled images into a feature space for sample selection. Recently, the advent of foundation models such as the Segment Anything Model (SAM) offer a promising alternative as the pre-trained model can provide strong generalizable feature embeddings, and allow high performance in downstream tasks after fine-tuning (adaptation). However, how to systematically exploit SAM's inherent embeddings for cold-start sample selection during adaptation with low annotation budget remains underexplored. To address this, we propose an extended SAM-based Uncertainty-guided Feature Weighting (SUGFW+) framework for CSAL and adaptation of SAM. Specifically, it leverages the SAM for Pa

---

### [350] CoM$^3$eT: A foundation model for medical image analysis through federated, multidimensional context integration

**链接**: https://arxiv.org/abs/2608.16268
**作者**: J. Raphael Sch\"afer, Kai Geissler, Till Nicke, Chiara Tappermann, Karoline Heber, Eike Petersen 等 (10 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical foundation models improve generalization when training AI models with limited labeled data, but remain confined to a single specialty, such as pathology or radiology, and to either sparse or dense outputs, such as classification or segmentation. Here, we present CoM$^3$eT (Co-representation Multidimensional Multitask Medical Transformer), a medical vision foundation model that unifies pathology and radiology, sparse and dense predictions, and two- and higher-dimensional inputs by modeling multidimensional context with attention. CoM$^3$eT outperformed other medical foundation models in an open competition spanning five tomographic, four whole-specimen, and three two-dimensional datasets, covering sparse and dense prediction tasks as well as report generation. When adapted across diverse clinical applications, training fewer than 2.5% of parameters achieved performance comparable to full fine-tuning, enabling research without access to high-performance GPU clusters. Applied to f

---

### [351] Recirculation

**链接**: https://arxiv.org/abs/2608.17981
**作者**: Michael C. Mozer, Shoaib Ahmed Siddiqui, Danny Sawyer, Sunny Sanyal, Rosanne Liu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We describe an inference-time architectural enhancement for off-the-shelf foundation models that markedly reduces perplexity and boosts accuracy across generation and reasoning tasks. Our approach incurs essentially no additional latency during generation, though it requires serial processing in the prefill phase. Motivated by the fundamental limitation that state updates in feedforward transformers are bounded by model depth, our technique, recirculation, introduces a specific form of recurrence that allows the model to act as a dynamical system and track belief states. We distinguish this technique from chain-of-thought computation---which is better reserved for complex inferences rather than basic state tracking---as well as from popular depth-recurrence techniques (looping) and the costly training of recurrent transformers. We also propose and evaluate an adaptive variant of recirculation which requires only light tuning of hyperparameters while freezing the original model weights.

---

### [352] ChainSpace: A Chained-Reasoning Paradigm for Spatial Intelligence

**链接**: https://arxiv.org/abs/2608.15788
**作者**: Xiaohan Zhang, Feng Gu, Xudong Rao, Xuhao Pan, Tao Wei, Zhou Pan 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial intelligence requires foundation models to maintain coherent spatial state across interactions with the physical world. However, existing data-centric approaches typically treat spatial reasoning as independent question-answer instances, enabling shortcut-based answering and providing limited supervision for persistent spatial understanding. To address this, we introduce ChainSpace, a chained-reasoning paradigm that structures spatial reasoning as a state-preserving multi-round process. In this paradigm, spatial questions are organized into logically constrained and jointly consistent chains, where later questions depend on spatial constraints established in earlier rounds. Following this principle, we instantiate ChainSpace-Bench, a manually annotated real-world multi-round benchmark with a Chain-Aware Metric, and ChainSpace-Pipeline, a simulator-based chain-structured supervision generation framework for spatial intelligence training. Experiments show that ChainSpace-Bench ex

---

### [353] DeepInsight II: One Trace from Benchmark to Robot

**链接**: https://arxiv.org/abs/2608.16556
**作者**: Siyi Li, Yuchen Kang, Wuliang Wang, Zhengjie Zhang, Jiangpin Liu, Jianhao Yao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Across a Physical AI stack, evaluation maturity is inversely aligned with deployment risk: foundation models enjoy mature, standardized harnesses, while the embodied layers on which deployment actually turns remain fragmented across benchmark-specific simulators, embodiments, and interfaces. The first DeepInsight report (v1) unified evaluation across this stack behind three abstractions---task, resource, and result---but its quantitative evidence centered on the foundation-model layer; navigation and manipulation (System 1) and whole-body control (System 0) remained simulation case studies, and physical execution was outside its empirical scope. DeepInsight II keeps that substrate fixed and quantifies the embodied half. First, it reproduces released-checkpoint references across two navigation and four manipulation benchmarks under their native protocols. Second, MotionBench places four released whole-body controllers under one workload and metric contract, then carries a qualified with

---

### [354] Concept-based explanation of gene expression prediction from H&E images

**链接**: https://arxiv.org/abs/2608.16669
**作者**: Amos Muench, Jonathan Thielmann, Reduan Achtibat, Maximilian Dreyer, Philip Bischoff, Caroline Forsythe 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in pathology foundation models have enabled accurate prediction of spatial transcriptomics (ST) from routine H&E images. However, existing explainability methods for vision transformer (ViT)-based models are largely limited to local heatmaps and do not reveal how morphological concepts contribute to ST predictions. Here, we introduce an explainable framework that combines relevance propagation and concept discovery to link transcriptional programs to tissue morphology. We developed a ViT-based framework for virtual ST from H&E images that combines ViT-aware layer-wise relevance propagation with relaxed archetypal TopK sparse autoencoder-based concept discovery. This approach provides both local explanations and global insights into the morphological patterns associated with transcriptional programs. We applied the framework to colorectal cancer ST data from the HEST-1k cohort and evaluated its generalizability in TCGA COAD. Our architecture accurately predicts clinicall

---

### [355] DistillPath: An Efficient 22M Distilled Pathology Encoder Approaching Large Foundation Model Performance

**链接**: https://arxiv.org/abs/2608.17872
**作者**: Ramon Kaspar, Andrey Ignatov, Valentina Boeva
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many high-performing pathology tile encoders are now foundation models with hundreds of millions to over a billion parameters. Encoding and storing the thousands of tiles in each whole-slide image with such models is costly on commodity hardware, so compact encoders that retain useful downstream performance are a valuable alternative. We present DistillPath-KS16, which starts from the existing 22M kaiko ViT-S/16 encoder and improves it by distilling from released pathology encoders used as frozen teachers. The recipe reads only the teachers' final class and patch tokens and trains on 6,000 public slides, needing neither their DINO nor iBOT pretraining heads nor a billion-tile corpus, so it applies to any released encoder that exposes backbone tokens. We distill four teachers spanning 86M to 1.1B parameters into the same student. Every variant improves the kaiko baseline on all three benchmarks we use, EVA, HEST, and PLISM, and the strongest teacher is task-dependent. On the seven-task 

---

### [356] S$^3$AM: A Single-Stream SAM with Reliability-Calibrated Frequency Adapter for Multi-modal Salient Object Detection

**链接**: https://arxiv.org/abs/2608.17475
**作者**: Ruichao Hou, Boyue Xu, Tongwei Ren, Dongming Zhou, Gangshan Wu and Jinde Cao
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models have recently advanced multi-modal salient object detection (MSOD) through parameter-efficient tuning and prompt learning. However, existing Segment Anything Model (SAM)-adapted MSOD methods often rely on dual-stream encoders or auxiliary prompt generators, leading to redundant computation. Although a single-stream alternative can reduce this cost, early fusion may also propagate noisy or misaligned auxiliary high-frequency cues through the backbone. In this paper, we propose a novel single-stream framework that integrates reliability-calibrated frequency adaptation into the adopted SAM backbone for MSOD. It avoids duplicated foundation backbones while explicitly controlling auxiliary frequency injection. Specifically, we design a mixture of frequency experts module, which uses the stationary wavelet transform to decompose each modality and aggregate cross-modal frequency information. We further introduce a reliability-calibrated frequency adapter with a dual-g

---

### [357] Leveraging existing sparse point annotations for benthic imagery dense segmentation

**链接**: https://arxiv.org/abs/2608.17561
**作者**: Cesar Borja, Breck A. McCollum, Jarret E. Byrnes, Kenneth Sebens, Ana C. Murillo
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The health of marine ecosystems is a critical indicator of global environmental change, yet the physical constraints of underwater observation and the intrinsic challenges of processing marine imagery severely limit the scalability of systematic monitoring. While recent visual foundation models such as the Segment Anything Model (SAM) series show great promise, they still struggle with the fine-grained recognition required in these complex scenarios and still require expert supervision. Our work addresses this gap by bridging state-of-the-art foundation models with existing sparse supervision. Because historical benthic surveys are typically annotated with only a few sparse expert points per image, we utilize these legacy point-labels as visual prompts for SAM2. Our primary contribution is a novel mechanism to automatically identify which of these points are suitable, and which are actively harmful, when used for propagation. By filtering out unreliable points, we extract high-quality 

---

### [358] Environment-Invariant Subspace Learning for Generalizable Deepfake Detection

**链接**: https://arxiv.org/abs/2608.17700
**作者**: Shenghao Chen, Hao Jia, Chen Li, Chunjie Ma, Zan Gao, and Shengyong Chen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-distribution generalization remains a critical bottleneck in deepfake detection. While recent efforts leverage the semantic priors of large-scale visual foundation models (VFMs), a noteworthy yet underexplored challenge remains: the susceptibility of these semantic priors to environmental interference from factors such as lighting and style. Crucially, this interference establishes spurious correlations between forgery cues and environmental patterns that severely limit generalization. To address this fundamental challenge, we propose an innovative Environment-Invariant Subspace Learning (EISL) framework. The core contribution of EISL is that it aims to disentangle features into orthogonal forgery-relevant invariant factors and environment-related residual factors via a learnable low-rank projection. To facilitate robust feature disentanglement, we also design an Environmental Intervention module that generates diverse and challenging intervention pairs, simulating out-of-distrib

---
