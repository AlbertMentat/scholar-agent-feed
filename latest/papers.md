# 📑 论文索引 - 2026-08-18

共 341 篇论文

---

### [1] Controlling a Robot Arm with a Large Language Model (LLM) in an Educational Setting

**链接**: https://scholar.google.com/scholar_url?url=https://peer.asee.org/controlling-a-robot-arm-with-a-large-language-model-llm-in-an-educational-setting.pdf&hl=zh-CN&sa=X&d=14826865188791074311&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-yjmdpS8YY8Kmu_IwZAX8L9&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: RL Avanzato, J Daniel - 2026 ASEE Annual Conference & Exposition, 2026
**匹配关键词**: LLM, Large Language Model, MLLM
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> commercially available MLLM as is utilized in our system. Our design choice to use a commercially available, pretrained MLLM and code … The benefit of integrating an MLLM into a robotics system is that the MLLM can handle the user

---

### [2] BCIJelly: An integrated ecosystem for brain-computer interface research

**链接**: https://arxiv.org/abs/2608.13576
**作者**: Liyuan Han, Xinrui Yang, Tianyu Zheng, Qizhi Yang, Yitao Qin, Liang Chen 等 (10 人)
**来源**: cs.HC cs.LG q-bio.NC
**匹配关键词**: BCI, Brain-Computer Interface, LLM, Large Language Model
**相关性评分**: 8.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain-computer interface (BCI) research relies on multistage computational pipelines, yet progress remains constrained by fragmented data formats, heterogeneous decoder implementations and hardware-specific deployment toolchains, and researchers lack an integrated workflow. Here, we fill this gap with BCIJelly, a unified computational ecosystem that integrates 18 curated BCI datasets, 15 benchmark decoders and an algorithmic library of 80 reusable modules, an automated architecture search (AAS) procedure, and hardware-aware deployment through the toChip pipeline within a single Python framework. AAS constructs task-specific decoders without manual architecture design. It is further extended into a closed-loop mode guided by a large language model (LLM), which uses task specifications, module descriptions and search history to support multitask and cross-species decoding. The toChip pipeline compiles trained decoders for execution on neuromorphic chips, enabling energy-efficient deploym

---

### [3] CBX-Bench: A Human-Aligned MLLM Council for Benchmarking Concept Bottleneck Model Explanations

**链接**: https://arxiv.org/abs/2608.15404
**作者**: Yusuf Meric Karadag, Gulay Oklan, Seref Baris Cagliyan, Umut Ozdemir, Emre Akbas
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Concept Bottleneck Models (CBMs) are designed to make visual classification interpretable by expressing predictions through human-understandable concepts. Although interpretability is the central motivation for CBMs, they are still largely evaluated as predictive models by downstream classification accuracy, supplemented by isolated qualitative examples. This highlights a pressing need for quantitative measures, a challenge complicated by the infeasibility of ground-truth concept annotation at scale and the open nature of concept lists due to a lack of consensus. To fill this gap, we develop a multimodal large language model (MLLM) council that, given an image and its CBM explanation, produces an explanation quality score. To ground and validate the council, we first conduct a human study to establish a ground-truth reference for CBM explanation quality: for an image, annotators compare explanations from two of LF-CBM, VLG-CBM, and CBM-Suite and choose the more useful one, or mark them

---

### [4] MLLM-Guided Semantic Correction for Text-to-Video Generation

**链接**: https://arxiv.org/abs/2608.16513
**作者**: Junhao Chen, Zheqi Lv, Keting Yin, Shengyu Zhang, Zhou Zhao, Feiyang Chen 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in diffusion models and Transformer architectures have led to significant progress in text-to-video generation. However, these models often suffer from semantic errors such as missing objects, incorrect attributes, or mismatched actions. Although some semantic correction methods perform optimization before sampling or refinement after sampling, how to detect and correct semantic deviations during the video generation process remains underexplored. In this paper, we introduce a training-free, interpretable mid-generation correction framework that integrates multimodal large language model (MLLM) feedback directly into the diffusion sampling loop. Our framework achieves diffusion trajectory correction by injecting semantic evaluation signals during video synthesis, enabling the model to optimize the generated content through continuous self-reflection. We propose two key modules: a Semantic Assessment Supervisor that generates intermediate preview frames for semantic eval

---

### [5] Remote-Sensing City Layout Extraction with MLLM

**链接**: https://arxiv.org/abs/2608.16484
**作者**: Zigan Zhou, Kai Li, Yupeng Deng
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote-sensing systems usually describe urban content with detection boxes, semantic masks, or vector boundaries. Such outputs locate classes and support image-plane scoring, yet they do not by themselves constitute an executable layout that retains object identities, typed relations, topology, and regeneration rules. Code-as-City instead casts urban-layout extraction from a single top-down image as constrained code generation with a multimodal large language model (MLLM). An image model first produces an aligned five-class semantic layout prior. Three ordered MLLM passes use the image and this prior to recover roads, land-cover regions and relations, and buildings. Deterministic normalization converts the accumulated records into a city graph and a restricted layout program. Executing the program creates a renderable 3D city layout and an orthographic semantic projection over shared geometry. The projection admits pixel-level comparison with remote-sensing masks, while named objects, 

---

### [6] HaReCAP: Habitual-action Grounding for Recursive Large Language Model Agents

**链接**: https://arxiv.org/abs/2608.16447
**作者**: Shen Liu, Zhenguo Xu, Shaopu Wang, Yike Gao, Chunlei Wang
**来源**: cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon embodied tasks require LLM agents to iteratively decompose high-level goals, revise plans in response to environmental feedback, and ground leaf-level subgoals into valid executable actions. Recursive context-management methods such as ReCAP improve planning stability through multi-level task decomposition and parent-node refinement, but still repeatedly invoke the LLM at leaf nodes to ground atomic subtasks into exact valid actions. We refer to this final grounding step as last-mile grounding redundancy, which accumulates into substantial LLM-call and token overhead during long-horizon execution. To mitigate this issue, we propose HaReCAP (Habitual-action Grounded ReCAP), a low-intrusion leaf grounding extension for ReCAP. HaReCAP extracts frequent leaf decisions from successful trajectories and compiles them offline into auditable and abstainable one-step leaf-reflex rules. At runtime, it skips the leaf LLM call only when a rule can uniquely determine a legal action in t

---

### [7] Beyond Direct Access: Resource Hijacking in LLM Agents

**链接**: https://arxiv.org/abs/2608.15108
**作者**: Puyu Zeng, Qibing Ren
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly connected to high-value resources such as computing infrastructure, credentials, usage budgets, identities, private knowledge, communication channels, and organizational workflows. Existing agent security research mainly studies attacks on instructions, data, and tool behaviors, while high-value resources accessible to agents have received much less attention as direct attack targets. We are the first to identify and systematically study agent resource hijacking, a security blind spot in which attackers induce agents to invoke, consume, transfer, or control high-value resources for their own goals without directly obtaining those resources or their credentials. To study this threat, we introduce ResourceHijackBench together with an automated pipeline for generating resource hijacking cases. We organize high-value agent resources into six categories and construct 300 attack scenarios with 900 attack prompts. Each case runs in an isolated loca

---

### [8] Designing LLM -powered virtual students with nonverbal behavior in an immersive VR classroom: Exploring pre-service teachers' perceived affordances for classroom …

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10639-026-14123-9&hl=zh-CN&sa=X&d=15979103761525641287&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-zibefyuDn7APj-MyCgh9Gw&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: J Dai, JK Choi, M Wang - Education and Information Technologies, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To address these issues, we present SimKids, a novel multi-agent system that utilizes large language model ( LLM ) and VR, incorporating Big Five Personality Traits and nonverbal behavior design, for classroom management training in early

---

### [9] ReForge: Keeping ABR Algorithms Never Finished with Verified Large Language Model Edits

**链接**: https://arxiv.org/abs/2608.15138
**作者**: Zhiqiang He and Zhi Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing an ABR algorithm for one network scenario takes an engineer months, and large language models now do this work in hours, matching or beating hand-built designs. But either way, the design fits only the world visible at its birth, and fails on the world that arrives after. We ask whether an ABR algorithm can keep pace with the world, redesigned in minutes as each scenario arrives, with every change proven harmless to every scenario already served. In this work, we propose ReForge, a continual heuristic learning framework that adapts to continuously changing scenarios. ReForge runs that routine with a large language model (LLM) in the loop. Each round the LLM reads where the current design falls short and proposes one small edit, and a replay over every network served so far decides. Specifically, what it edits is a single page of fuzzy rules that routes every decision to one of a frozen pool of pre-trained policies. The LLM writes the first page from measurements alone, then k

---

### [10] WARA: Toward Automated Wireless Optimization Research with Closed-Loop LLM Agents

**链接**: https://arxiv.org/abs/2608.14573
**作者**: Yuan Guo, Yilong Chen, Chao Hu, Xianghao Yu, Liang Hong, and Jie Xu
**来源**: cs.NI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly capable of tool use, code execution, artifact inspection, and iterative revision, creating new opportunities for automating scientific and engineering research. To the best of our knowledge, this paper presents the first end-to-end autoresearch framework for the wireless domain, with a focus on wireless resource allocation optimization. We propose the Wireless AutoResearch Agent (WARA), a closed-loop multi-agent system for automated wireless optimization research. Given only an initial topic, WARA decomposes the workflow into three phases: research gap identification and problem proposal, wireless optimization modeling, algorithm design and experimentation, and research deliverable construction. Across these phases, WARA uses artifact-mediated control: upstream artifacts are consumed as inputs, structured outputs are stored for downstream use, and controller-managed gates validate consistency among models, algorithms, experiments, and 

---

### [11] QUMem: Personalized Memory for Query-Conditioned User-State Inference in LLM Agents

**链接**: https://arxiv.org/abs/2608.16168
**作者**: Heng Wang, Yifei Li, Lingling Zhang, Pengyu Li, Xinyu Che, Xinyu Zhang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use external memory systems to support personalization by drawing on long and evolving interaction histories, in which user preferences may be distributed across time, change with context, and conflict with earlier evidence. However, existing systems face three limitations: fixed-turn, fixed-token, or session-based boundaries can mix unrelated dialogue or split an event from its causes, decisions, and outcomes; storing multiple pieces of user information from the same interaction as a single memory binds together items that serve different functions and should be independently retrievable; and treating the current task as a single top-$k$ retrieval query can return fragments that are individually relevant but fail to jointly capture preference evolution, temporal validity, and contextual applicability. We introduce \textsc{QUMem}, a structured memory framework for query-conditioned user-state inference. \textsc{QUMem} first segments intera

---

### [12] Large Language Model Assisted Operational Monitoring for Battery Energy Storage System Integrated Power Distribution Networks

**链接**: https://arxiv.org/abs/2608.15396
**作者**: Azmeer Akhtar, Md Fazley Rafy, and Anurag K. Srivastava
**来源**: cs.AI cs.CL cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Battery energy storage systems (BESS) are increasingly used in distribution networks for voltage regulation and demand response, which increases the volume and complexity of operational telemetry available to grid operators. This paper presents an AI-enabled monitoring framework that connects a large language model (LLM) interface with a structured telemetry database for BESS-integrated distribution system analysis. Operator questions are submitted in natural language and translated into validated SQL queries using predefined database schema information and approved KPI views. Retrieved measurements, including bus voltages, state of charge, active power, and reactive power, are evaluated against engineering constraints for voltage limits, BESS operation, and demand response tracking. The framework is validated using hardware-in-the-loop co-simulation data from a BESS-equipped distribution feeder operating under reactive power-based voltage control and price-driven demand response. Case

---

### [13] ATLAS: Discovering Agent Strategies through LLM-Guided Abstraction and Automata Learning

**链接**: https://arxiv.org/abs/2608.14352
**作者**: Ignacio D. Lopez-Miguel, Andreas Happe, J\"urgen Cito, Ezio Bartocci, Bettina K\"onighofer, Martin Tappler
**来源**: cs.SE cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based agents are increasingly used for complex tasks such as software testing and cybersecurity assessment. While these agents demonstrate impressive capabilities, their behavior is difficult to understand, explain, and analyze. Existing evaluations focus mainly on task success and execution traces, offering limited insight into the strategies employed by the agent. We present ATLAS (Automata Learning for Agent Trajectory Analysis and Strategy Discovery), an approach for recovering interpretable behavioral models from agent trajectories. ATLAS combines trace abstraction with automata learning to infer finite-state models that capture observed agent-environment interaction strategies. These models provide human-interpretable insights and support automated analyses of recurring behaviors, decision points, successful task-completion paths, and failure loops. As a proof of concept, we apply ATLAS to trajectories generated by an LLM-based penetration-testing agent

---

### [14] TRCA: Transition-wise Rubric Credit Assignment for Long-horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.16156
**作者**: Huan Zhang, Mingju Chen, Dongxu Zhou, Can Lv, Heng Chang, Sen Cui 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon large language model (LLM) agents are typically optimized with sparse terminal outcomes, making fine-grained credit assignment across multi-step interactions difficult. Existing approaches either rely on process evaluators, which incur annotation and inference costs, or derive step-level credit from successful trajectories. However, successful trajectories are extremely scarce during early-stage reinforcement learning, substantially weakening anchor-based methods. We propose Transition-wise Rubric Credit Assignment (TRCA), which derives step-level supervision directly from action-induced transitions without learned evaluators or successful anchors. TRCA evaluates each transition using Evidence, Execution, and Invalidity rubrics to capture task-relevant information acquisition, valid task execution, and invalid or regressive behavior. From these judgments, Foundational Rubric Reward measures local transition quality, while Breakthrough Rubric Reward tracks newly covered Evi

---

### [15] SKILL: Self-correcting Knowledge-guided Iterative Large Language Model Agent for Logic Optimization

**链接**: https://arxiv.org/abs/2608.14579
**作者**: Rui Yang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logic synthesis optimization poses significant challenges due to exponentially growing search spaces, sparse reward signals, and diverse logic structures. Traditional expert-designed flows lack adaptability, while reinforcement learning (RL) methods often suffer from low sample efficiency and limited interpretability. We introduce SKILL, a Self-correcting Knowledge-guided Iterative Large Language Model Agent that unifies multi-agent LLM reasoning and RL-based environment interaction for automated synthesis optimization. SKILL coordinates three specialized LLMs: GPT-4o for strategic planning, Claude Sonnet 4 for detailed reasoning, and Gemini 2.5 Pro for efficient analysis with a PPO-based RL agent that learns actionable policies through direct interaction with synthesis tools. A novel self-correcting module monitors environment feedback (PDA metrics), detects suboptimal behaviors, and invokes LLM-guided recovery strategies. Evaluations on IWLS, OpenCores, and EPFL benchmarks show SKILL

---

### [16] Belayer: Efficient Fault Tolerance for LLM Agentic RL Training

**链接**: https://arxiv.org/abs/2608.14635
**作者**: Jiecheng Zhou, Qinghao Hu, Peng Sun, Xingcheng Zhang, and Weiming Zhang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly trained with reinforcement learning in long-horizon, sandboxed environments. Unlike conventional RL, agentic RL couples GPU-intensive rollout engines with stateful environment containers whose actions may produce visible side effects, such as file edits, command execution, and dependency installation. A single trajectory can span many rounds of gen- eration and environment interaction, so a component failure can discard completed work or expose the model to an environment state that is inconsistent with its context. However, existing systems lack efficient and correct recovery mechanisms for this distributed execution model. This paper presents Belayer, an efficient fault-tolerant system for LLM agentic RL training. Belayer handles failures in both rollout engines and environment execution while targeting low failure-free overhead. For scoped worker-local rollout failures, Belayer equips each pre-initialized shadow worker with a select

---

### [17] A Hybrid LLM-Based Framework for Automated Security Annotation Generation in Business Process Models

**链接**: https://arxiv.org/abs/2608.14370
**作者**: Md Kamrul Islam, Tiphaine Henry, Mattia Salnitri, Julius K\"opke, Sami Souihi
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The modelling and analysis of secure business processes require the incorporation of security annotations into process models. Although BPMN extensions, including SecBPMN2, exist for this purpose, the derivation of accurate and complete security annotations from natural-language specifications remains a manual, expert-intensive, and error-prone task. This paper presents a hybrid framework that takes a BPMN process model and a security requirements document as input and automatically generates security annotations adhering to the SecBPMN2 specification. The approach combines Large Language Model (LLM)--based semantic extraction with schema-constrained mapping, rule-based normalization, and deterministic validation. The framework is evaluated comprehensively on a curated dataset of 27 process models from various domains. The results indicate that it consistently produces structurally valid SecBPMN2 annotations with high schema completeness. Compared to human security analysts, the system

---

### [18] Pallas: A Proactive KV Cache Migration Framework for LLM Inference in AI-RAN

**链接**: https://arxiv.org/abs/2608.16477
**作者**: Tianhang Ding, Jianchun Liu, Hongli Xu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-RAN brings large language model (LLM) serving close to mobile users, but cellular handover can separate an active request from its inference state: the user attaches to a target base station (gNB) while the large and growing key-value (KV) cache remains at the source. Retaining inference at the source preserves service continuity but persistently increases inter-token latency (ITL), whereas recovering the state at the target restores serving locality but requires KV-cache transfer, recomputation, or a combination of both only after handover, directly prolonging service interruption time (SIT). This work presents Pallas, a \textit{proactive} KV-cache migration framework that prepares the inference state at the predicted target before handover, in parallel with ongoing source-side inference and token delivery. At the preparation trigger, Pallas partitions the token sequence into a stable historical prefix and an evolving suffix. The target reconstructs the prefix through local prefill

---

### [19] Beyond Binary Priorities: Multi-Tier SLA Scheduling for Large Language Model Serving

**链接**: https://arxiv.org/abs/2608.16336
**作者**: Anders Vestrum, Arya Raeesi, Hanna Roed
**来源**: cs.AR cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM serving deployments must simultaneously satisfy heterogeneous service-level objectives (SLOs) across a diverse population of user tiers, ranging from latency-critical API calls to background batch processing. Llumnix introduced a dynamic, migration-capable multi-instance scheduler for LLM inference that achieves load balancing, defragmentation, prioritization, and auto-scaling through a unified "freeness" metric. However, Llumnix's priority model is restricted to two levels (high and normal), an abstraction too coarse to express the richer SLA classes common in production deployments. In this work, we extend Llumnix's priority model to support an arbitrary number of tiers and evaluate the effects of this extension under three realistic priority distributions (uniform, Gaussian, enterprise) using Vidur, a high-fidelity LLM inference simulator. We implement per-tier headroom with exponential decay, tier-aware dispatch ordering, and the full Llumnix migration pipeline inside Vi

---

### [20] Agent Gym: A Framework for Continuous Evaluation and Evolution of LLM Agents Through Human-in-the-Loop Feedback

**链接**: https://arxiv.org/abs/2608.15591
**作者**: Pouya Ghiasnezhad Omran, Michael Zimmermann, Duncan Cambridge, Ashmita Kapoor, Tanya Dixit
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents deployed in production environments face a fundamental tension: the agent's behavior is frozen at deployment time, while the business rules and edge cases it must handle continue to evolve. Existing approaches address agent construction and one-time evaluation but provide no structured mechanism for continuous post-deployment behavioral correction without modifying the agent's source code. Most of the approaches offered in the market, require intense collection of logs and traces, and re-examining the agent design by the engineering team, a process which is heavy, long and negates the economical value of agentic transformation. We introduce Agent Gym, a modular, domain-agnostic framework that wraps any existing LLM-based agent in a continuous evaluation-and-evolution loop. The framework provides six composable capabilities --- Act, Evaluate, Investigate, Correct, Learn, and Observe --- organized across three architectural zones: a constitution layer th

---

### [21] Rethinking Automated Program Repair: The Impact of Bug Complexity, Fault Localization, and LLM Cost-efficiency

**链接**: https://arxiv.org/abs/2608.14065
**作者**: Junchi Liu, Ali Bigdeli, Roya Daneshi, Atu Ambala, Sudipto Ghosh, Fabio Santos
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Software bugs remain a critical challenge in development, necessitating effective Automated Program Repair (APR) techniques. While Large Language Model (LLM)-based APR systems have shown promise, prior studies primarily focus on overall repair effectiveness. The effects of bug complexity, fault localization, reasoning settings, and repair cost-effectiveness remain insufficiently explored. Aims: This study presents a comprehensive empirical analysis of LLM-based APR, focusing on how repair performance is shaped by bug complexity, fault localization, reasoning settings, and costs. Method: We evaluate two APR techniques (ChatRepair and CodeCorrector) using three LLMs (DeepSeek, GPT, and Llama), and examine their performance across diverse levels of bug complexity and localization strategies through a multi-dimensional empirical framework and statistical analysis. Results: Although structurally complex bugs and imprecise fault localization make repair more challenging, LLM-base

---

### [22] From Sequence to Structure: Relational Uncertainty Propagation for LLM Agents

**链接**: https://arxiv.org/abs/2608.16002
**作者**: Zhengzhao Ma. Boxi Cao, Yaojie Lu, Hongyu Lin, Xianpei Han, Le Sun
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable uncertainty quantification (UQ) is essential for deploying large language model (LLM) agents in complex interactive environments. Existing UQ methods largely rely on local signals, such as token probabilities, predictive entropy, or per-step confidence, and therefore overlook the long-range dependencies through which errors accumulate across an execution trajectory. As a result, they may fail to identify agent failures whose causes originate several reasoning or interaction steps before the final answer. We propose RUPA (Relational Uncertainty Propagation for Agents), a trajectory-level UQ framework for LLM agents. RUPA represents an execution history as a directed trajectory graph in which reasoning states, tool interactions, and environment feedback are nodes connected by temporal and semantic dependency edges. It then propagates uncertainty over this graph to capture how execution risk accumulates and transfers across interaction steps. The propagated signal is combined wit

---

### [23] LAPF: LLM-Agent-Based Path Finder Using the UAVScenes Dataset

**链接**: https://arxiv.org/abs/2608.15175
**作者**: Yousef Emami, Mohammadhossein Homaei, Hao Zhou, Miguel Guti\'errez Gait\'an, Atefeh Hajijamali Arani, Rui Zhang
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Uncrewed aerial vehicles (UAVs) are increasingly deployed for autonomous navigation in complex outdoor environments, where dynamic conditions and mission requirements require intelligent adaptive decision-making. Existing optimization-based, Machine Learning (ML), and Reinforcement Learning (RL) approaches often rely on predefined models or task-specific training, limiting their generalization and adaptability in uncertain scenarios. Recent Large Language Model (LLM)-assisted approaches offer promising reasoning capabilities but remain constrained by limited agentic functionality, including insufficient memory, planning, and tool interaction mechanisms.This paper proposes an LLM-Agent-Based Path Finder (LAPF) framework for autonomous UAV navigation in town-scale outdoor environments. LAPF extends LLM-assisted navigation by integrating perception, memory, planning, and action modules into a closed-loop cognitive architecture. The proposed agent leverages prior navigation experiences, pe

---

### [24] Whose doctor does the AI recommend? An algorithm audit of reputation and demographic signals in large language model-assisted physician choice

**链接**: https://arxiv.org/abs/2608.14399
**作者**: Syeda Anshrah Gillani, Mirza Samad Ahmed Baig
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patients increasingly ask large language model (LLM) assistants which doctor to see, making these systems AI infomediaries: algorithms that intermediate one person's choice among other people and thereby decide, silently and at scale, which physicians become visible. We report a prespecified randomized algorithm audit of what causally moves those recommendations. Seven models (six open-weight; gpt-4o-mini) each chose among five synthetic family-medicine physician cards whose attributes were independently randomized across 3,024 choice sets, three patient personas, nine prompt paraphrases and nine experimental arms, yielding 40,068 scored responses; gender and ethnicity were signaled through names following correspondence-audit methodology. Reputation signals dominate: raising a rating from 3.9 to 4.7 increases choice probability by 31.4 percentage points (pp), and raising the fee from $90 to $190 lowers it by 20.0 pp. Demographic parity is rejected, but not in the direction human audit

---

### [25] AeroCopilotBench: A Two-Tier Benchmark for Evaluating LLM Agents as Aviation Copilots in an Interactive Virtual Cockpit Environment

**链接**: https://arxiv.org/abs/2608.16349
**作者**: Yuchen Yuan, Zhenghuang Wu, Yuangan Li, Liang Ma, Ke Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents may assist flight crews with complex decisions and task execution, but existing aviation evaluations centered on static knowledge do not support systematic testing of procedural execution and safety compliance in interactive environments. This paper presents the AeroCopilot Operational Environment (ACOE), a reproducible interactive virtual-cockpit test environment, and AeroCopilotBench, a two-tier aviation agent evaluation benchmark. Tier-1 evaluates aviation knowledge using 1,200 multiple-choice questions, while Tier-2 comprises 73 emergency and abnormal tasks derived from the manufacturers' Pilot's Operating Handbooks (POHs) and instantiated in ACOE. ACOE converts natural-language procedures into executable state transitions, final-state goal conditions, and hard safety constraints, enabling models to interpret cockpit state, diagnose faults, and operate aircraft systems through standardized tool interfaces. We establish a safety-gated evaluation fra

---

### [26] From "What-If" to "What-Is": Counterfactual Thinking-Inspired Semantic Alignment for Visual Brain Decoding

**链接**: https://arxiv.org/abs/2608.15163
**作者**: Kaitao Yan, Chi Liu, Congcong Zhu, Huajie Chen, Gengshen Wu, Minghao Wang 等 (8 人)
**来源**: cs.CV cs.HC
**匹配关键词**: LLM, Brain Decoding
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual brain decoding reconstructs visual content perceived by a person from neural measurements such as fMRI, providing a computational approach to studying how visual information is represented in the brain. Recent multimodal representations and diffusion priors have improved reconstruction realism. However, visually plausible reconstructions may contain incorrect objects, attributes, or relations because a strong generative prior can complete content not sufficiently specified by the decoded representation. Conventional reconstruction metrics mainly assess the final image and may therefore obscure such semantic errors. We propose ConceptAlign, a counterfactual semantic alignment framework for visual brain decoding. ConceptAlign pools decoded visual tokens and projects them into a frozen text-embedding space, aligning the representation with the ground-truth caption while separating it from scene-preserving near-miss alternatives. Generated offline by an LLM, these alternatives modif

---

### [27] PL-Guard: Probabilistic Logic Reasoning for LLM Guardrails

**链接**: https://arxiv.org/abs/2608.15673
**作者**: Satchit Chatterji, Shihan Wang, Giovanni Sileno, Erman Acar
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model guardrails can be viewed as policy-consistency problems: a system must determine which policy-relevant facts hold in a prompt-response pair and what those facts imply under a given policy. Common approaches, including policy prompting and LLM-as-a-judge pipelines, often overlap the tasks of semantic grounding and policy reasoning: the model both interprets the prompt-response pair and reasons about whether a policy has been violated. This can lead to unsafe compliance with harmful prompts, or refusals to assist benign ones. To separate grounding and reasoning roles, we propose PL-Guard, a neurosymbolic guardrail architecture. Using a symbolic policy interface consisting of predicates and ProbLog rules, a local LLM grounds prompt-response pairs into predicate probabilities using renormalized True/False token scores, while ProbLog performs explicit probabilistic rule inference over the symbolic policy. On the XSTest benchmark, an offline Qwen-based evaluator finds th

---

### [28] TwinGridShield: Consequence-Aware Runtime Authorization for LLM Grid-Agent Actions

**链接**: https://arxiv.org/abs/2608.15391
**作者**: Md Fazley Rafy
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-assisted energy-management tools can translate natural-language context into structured grid commands, but syntactic validity does not imply physical admissibility. This paper presents TwinGridShield, a model-independent runtime authorization layer that evaluates each proposed action in a deterministic network twin before release. The prototype checks connectivity, branch-flow, generator, and load-shedding invariants and records each decision in a hash-chained log. A controlled IEEE 14-bus study evaluates single-step switching, redispatch, and load-shedding actions using DC power flow and experimentally assigned branch ratings. In the matched-model experiment, a stochastic proposal source configured to select an unsafe action with probability p=0.84 produced 421 unsafe proposals in 500 attacked-condition trials, a realized rate of 84.2%. This value characterizes the configured surrogate and is not an empirical measurement of LLM prompt-injection susceptibilit

---

### [29] A Year in LLM Serving: Workload Evolution, Caching and Load-Balancing

**链接**: https://arxiv.org/abs/2608.13573
**作者**: William Nixon, Jon Durbin, Florian Standhartinger, Haryadi S. Gunawi, Juncheng Yang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) serving has become a critical cloud workload, and realistic traces are essential for motivating and benchmarking serving systems. However, existing LLM serving workload studies remain limited in scale and scope. They often observe short time periods and provide limited visibility into how users interact with models in production. As a result, they do not fully capture how LLM serving workloads evolve over time or how user-model interactions shape production traffic. In this work, we further the understanding of real-world LLM serving workloads through both a global characterization and a longitudinal study of a one-year production trace from Chutes. Unlike prior studies, our trace captures full production behavior across many models and users, including both popular and long-tail models. We analyze the workload from aggregate, temporal, model-level, and user-level perspectives, revealing workload evolution and user-model structure that are typically hidden be

---

### [30] Text-Pilot: Intelligent Visual Text Planning and Manipulation Via Multi-Modal Llm As Agent

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11630578/&hl=zh-CN&sa=X&d=10857861456554201667&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-y8SNbePtCEHDA9j14oUCN4&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: YK Kuo, QT Le, NP Doan, CC Huang - 2026 IEEE International Conference on Image …, 2026
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> • We propose Text-Pilot, a training-free MLLM framework designed for the automated detection and correction of visual text errors in images. • Text-Pilot provides a unified solution that autonomously identifies error types and selects

---

### [31] LLM -based Bearing Faults Diagnosis via Structured Spectral Text from Voltages Outputs of Nonlinear Piezoelectric Energy Harvester

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S092442472600926X&hl=zh-CN&sa=X&d=10735111278626153204&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-yjM7XACtWuMltrmr217ptr&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: Y Shang, J Xu - Sensors and Actuators A: Physical, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> modeling, structured spectral textualization, and large language model ( LLM )-based classification. Monostable and bistable PEH models are … The proposed textual strategy preserves sufficient discriminative information for later LLM -based

---

### [32] Le Critique: Privileged Value Functions for LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.16739
**作者**: Siddarth Venkatraman, Matthieu Dinot, Laurence Aitchison
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning algorithms for Large Language Models (LLMs) are largely distinguished by their variance reduction strategy. Group-relative methods like GRPO reduce gradient variance by sampling multiple rollouts per prompt, but provide only sequence-level credit. Training is also blocked by straggler rollouts, reducing throughput and increasing off-policyness. Learned value functions theoretically address both problems, providing token-level advantages without requiring large groups. However, additional infrastructure engineering challenges combined with the practical success of critic-free methods have made it difficult to justify their inclusion in RL pipelines. We propose two complementary strategies to improve the performance of value function RL: 1) Privileged Value Functions (PVF) which provide an elegant mechanism to inject additional task-relevant token-level signal without biasing the policy objective; 2) TETHER, a baseline that adaptively interpolates between group-rel

---

### [33] Ask to Be Sure: Informative Interactions for Confident Multi-Turn LLM Recommendation

**链接**: https://arxiv.org/abs/2608.15949
**作者**: Cedar Site Bai, Duanshun Li, Zhenyu Liao, Sheikh Sarwar, Huiyuan Chen, Yuan Chen 等 (9 人)
**来源**: cs.IR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) have enabled their use as conversational recommender systems (CRS), demonstrating strong recommendation accuracy and natural dialogue. However, guiding multi-turn interactions to elicit user preferences effectively remains challenging. Existing approaches either use separate reinforcement learning agents with templated interactions or optimize for interactivity judged by another LLM, without measuring how much useful information is actually gained. We propose a new approach that quantifies the effectiveness of each interaction by the reduction in the assistant's uncertainty, measured via entropy over recommendations. We apply this entropy reduction as a reward---without relying on ground-truth recommendations, which are often unavailable in real-world scenarios---to fine-tune the LLM, enabling strategic interaction generation. Empirical results with supervised fine-tuning (SFT) and direct preference optimization (DPO) on the INSPIRED and 

---

### [34] When the Model Writes the Questionnaire: An Item-Level Defect Taxonomy for LLM -Generated 360-Degree Feedback Instruments

**链接**: https://scholar.google.com/scholar_url?url=https://alessiobiancheri.com/research/papers/when-the-model-writes-the-questionnaire.pdf&hl=zh-CN&sa=X&d=7568159117230153587&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-zm7ycvXq9tWhosJUPyKfxv&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: A Biancheri - Preprint v1, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The valence-steering finding, which we consider the most consequential result here and which we believe is novel: an assistive LLM that nudges assessors toward positively phrased feedback corrupts the instrument in a direction that its own

---

### [35] Prior Audit-Repair Context Shifts LLM Verifier Thresholds Toward Leniency

**链接**: https://arxiv.org/abs/2608.16003
**作者**: Parsa Mazaheri and Kasra Mazaheri
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated checking pipelines increasingly place one language model as the checker and another (or the same one) as the fixer. We ask whether that wiring changes what the checker reports. Measuring false alarms on human-verified-correct ProcessBench traces with the present task held byte-identical, we find that a completed audit -> repair episode already in the model's context lowers false alarms in 15 of 15 model x wording combinations, by 2.8 to 11.5 percentage points against a length-matched non-audit control, a 9 to 25% reduction relative to that control. The direction contradicts what the accumulated-message literature predicts: an episode whose audit reported an error lowers false alarms further still, at all five wordings on the model where that manipulation lands cleanly, though a negativity asymmetry predicts more flagging. Decomposing the episode finds repair content and audit verdict complementary: different components carry the effect on different model families. Signal-dete

---

### [36] A Four-Axis Trustworthiness Benchmark for LLM-as-Judge in Principle-Based Regulation

**链接**: https://arxiv.org/abs/2608.14329
**作者**: Dipankar Sarkar
**来源**: cs.CR cs.AI cs.CL cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Principle-based regulation, with evaluative standards such as "fair, clear, and not misleading" or "deliver good outcomes", cannot be reduced to binary predicates, and LLM-as-judge is increasingly used as the substitute. Our position is that any such judge must be evaluated on four axes: accuracy, paraphrase robustness, adversarial robustness, and calibration. We release Principle-Bench, 168 cryptoasset financial-promotion scenarios mapped to two UK FCA principles, with paraphrase, adversarial keyword-stuffing, and boundary perturbations authored under a pre-registered rubric; the first benchmark covering all four axes for principle-based regulation. We also introduce Ceca (Calibrated Exemplar-Cluster Assessment): a calibrated, auditable assessor that emits exact per-exemplar counterfactual attributions. Across keyword counting, three sentence-transformer embedders, an open-weight LLM-judge, and a calibrated cascade, no method dominates all four axes. A 120B LLM-judge, strongest on ben

---

### [37] Multi-Granularity Sentiment Integration for LLM-Based Multimodal Sentiment Analysis

**链接**: https://arxiv.org/abs/2608.16201
**作者**: Shanshan Lin, Yuesheng Wu, Chao Chen, Yizhe Yang, Zhihao Chen, Zexian Yang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal sentiment analysis (MSA) aims to predict sentiment polarity and intensity from heterogeneous inputs such as text, audio, and vision. While large language models (LLMs) offer strong semantic priors for MSA, effectively incorporating audio and visual signals effectively remains challenging. A key challenge is that audio and visual sentiment cues evolve over different temporal scales, yet many LLM-based methods compress these signals through shallow projection or coarse pooling before fusing them with text, which can weaken cross-modal alignment and erase fine-grained affective information. We propose MGSI, a multi-granularity sentiment integration framework for LLM-based MSA. MGSI first encodes audio and visual streams at short-, medium-, and long-range temporal scales, preserving both local variations and global affective trends. It then refines non-text features through text-guided alignment, and applies polarity- and intensity-aware enhancement to better handle ambiguous an

---

### [38] The Value of a Prompt: An LLM-Relative Kolmogorov-Complexity Approach

**链接**: https://arxiv.org/abs/2608.16438
**作者**: Rafael Pass
**来源**: cs.AI cs.CC cs.IT math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In a world where valuable artifacts are increasingly created, completed, or processed by LLMs, the central economic question is not only what the LLM can produce, but what \emph{value} remains in the inputs (i.e., the prompts) we provide to it. Given a prompt, hint, critique, problem statement, or partial solution that helps an LLM produce an artifact $z$---a proof, program, design, or scientific hypothesis---how should we measure the value of that input? Intuitively, an input is valuable when it makes the target artifact easier for the model to generate: either by increasing its sampling probability, or by reducing the thinking time needed to find it. We propose a computational Levin--Kolmogorov complexity approach to this problem, by appropriately replacing the universal Turing machine in the classical definitions by the LLM itself. Concretely, we introduce an LLM-relative notion of \emph{probabilistic Levin--Kolmogorov complexity} $pKt$---treating the model's thinking as the random 

---

### [39] Do LLM Agents Negotiate Rationally? A Mechanism-Design Framework for Verifiable Multi-Agent Interaction over A2A/MCP

**链接**: https://arxiv.org/abs/2608.14613
**作者**: Wael Albayaydh, Rui Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM-agent frameworks increasingly interoperate through standards such as Anthropic's Model Context Protocol (MCP) for agent-to-tool access and Google's Agent2Agent (A2A) protocol for agent delegation and negotiation. However, these protocols specify transport and discovery rather than strategic correctness and do not guarantee efficient, individually rational, or strategy-proof outcomes. We introduce a framework that (i) encodes classical negotiation mechanisms, including alternating-offers bargaining and Vickrey-Clarke-Groves-style auctions, as constraints over A2A message schemas; (ii) provides a lightweight runtime verification and repair layer that checks messages against protocol invariants; and (iii) offers a benchmark of negotiation and allocation tasks with known optimal solutions for measuring deviations from game-theoretic predictions. We evaluate multiple LLM backbones using unstructured dialogue, structured protocols, and structured protocols with verification. Acros

---

### [40] Hierarchical Agentic Incident Response with Digital-Twin-Validated Attack Inference

**链接**: https://arxiv.org/abs/2608.15016
**作者**: Yiran Gao, Juntao Chen, Tao Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Network incident response remains slow and labor-intensive as the defender must infer multi-stage attacks from partial observations and translate recovery decisions into reliable system commands. Decision-theoretic planners provide principled optimization but typically rely on abstract states and predefined actions, while large language model (LLM) agents can reason over operational context but may hallucinate attacks and responses. Toward automating response planning, we present a hierarchical agentic response framework that integrates LLM-based attack inference, rollout planning, and digital-twin validation. A fine-tuned LLM infers the attack progression and affected hosts from security alerts and system measurements. An emulated network digital twin replays the inferred attack and returns discrepancies between predicted and observed effects to calibrate the inference. A separately fine-tuned planning agent uses the rollout planning method to prioritize affected components at the tac

---

### [41] Proxy-Validated LLM UX Micro-Simulations: An Artifact-First Protocol for Early-Stage Decision Support

**链接**: https://arxiv.org/abs/2608.13563
**作者**: Alexandre Cristov\~ao Maiorano
**来源**: cs.HC cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Early-stage teams often lack users, time, and budget to run repeated UX studies, yet still need decision-oriented signals to iterate safely. We study an LLM-driven UX micro-simulation pipeline that generates structured customer-experience feedback (walkthrough steps, friction points, micro-survey signals) from versioned prompts, personas, tasks, and UI snapshots. Because public usability datasets with task outcomes are scarce, we validate simulated friction themes using multiple public proxy corpora (app reviews, support tweets, and open-source software issues). We propose a lightweight proxy-validation protocol with two alignment metrics: top-k Jaccard and distributional weighted-Jaccard (W), and compare lexical, TF-IDF, and multilingual embedding baselines across six proxy datasets. Embedding-based alignment yields higher W than lexical baselines on primary app-review and support-tweet proxies (e.g., W=0.128 vs 0.000 on Gojek), while top-k Jaccard is shown to overstate alignment at l

---

### [42] Agentic-SQL Revisited: Autonomy-Based Taxonomy and Empirical Benchmark Analysis for LLM Text-to-SQL

**链接**: https://arxiv.org/abs/2608.15389
**作者**: Changruo Zhao, Zujun Peng, Yu Tian, Yuting Liu, Yiyun Su, Huiying Zhu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based Text-to-SQL progress is reported across heterogeneous benchmarks, backbones, and inference protocols, making cross-system comparison fragile. We reframe the field as a leaderboard aggregation: we collect the metrics authors themselves report and organize them along an inference-autonomy axis spanning constrained, in-context, iterative, agentic, and reasoning-internalized generation, with traceable provenance for every cell. To anchor the aggregation empirically, we run a focused case study on Spider, comparing 8B open-source backbones with and without chain-of-thought (CoT) supervision against few-shot DeepSeek~V3 and GLM-4 baselines. Four patterns emerge: Spider gains transfer unevenly to BIRD and Spider~2.0; autonomy buys robustness at non-trivial cost; reasoning internalization sits between answer-only decoding and externally orchestrated agents; and CoT gains concentrate on Hard and Extra-Hard queries. We release a Python harness mirroring the autonomy axis so that future

---

### [43] SemPlan: Benchmarking Structured Semantic Planning for LLM-Based Queries over Enterprise Data

**链接**: https://arxiv.org/abs/2608.13612
**作者**: Bruno Santos Teixeira
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language interfaces to enterprise data must translate underspecified requests into governed, executable behavior while controlling invalid queries, policy failures, cost, and nondeterminism. SemPlan Benchmark evaluates this architectural design space with a deterministic synthetic bilingual benchmark containing 1,800 cases in English and Brazilian Portuguese; 1,200 cases form the frozen scientific evaluation subset. Four architectures are compared under the same model configuration: direct SQL generation (A1), a bounded tool-agent baseline (A2), structured semantic-request generation followed by deterministic planning and execution (A3), and a clarification/stateful semantic-plan variant (A4). Across 4,800 primary records, answer correctness was low in absolute terms: 22.25% for A1, 22.58% for A2, 25.67% for A3, and 24.25% for A4. A3 had the highest observed correctness and significantly exceeded A1, A2, and A4 in the pre-specified paired correctness analysis, while A1 retained

---

### [44] BRA-Audit: Budgeted Runtime Auditing for LLM Multi-Agent Systems via Cumulative-Exposure Audit-Point Placement

**链接**: https://arxiv.org/abs/2608.14668
**作者**: Kaixiang Wang, Yidan Lin, Jiong Lou, Jie Li
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (LLM-MAS) solve complex tasks through specialized collaboration, but inter-agent dependencies can propagate hallucinated or malicious outputs into system-level failures. Auditor agents mitigate these risks, yet existing strategies face an efficiency dilemma: end-only auditing reviews long trajectories and final outputs, potentially weakening audit effectiveness and enlarging rollback scope, while auditing every agent each round improves detection and localization at high token cost. How can guard performance be preserved while minimizing token cost? To address this problem, we propose BRA-Audit, a budget-aware runtime auditing framework that models MAS execution as a dynamic dependency graph and formulates audit scheduling as audit-point placement under a fixed audit-call budget to minimize cumulative unchecked exposure. Its greedy scheduler prioritizes influential and long-unaudited regions, while trusted audit points enable localized recovery. Across str

---

### [45] ORACLE-REMEDIATE: Context-Aware, Safety-Verified LLM Remediation for CIS Benchmark Compliance on Oracle Multitenant Databases

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11637188/&hl=zh-CN&sa=X&d=5181926725499243547&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-wqWSj4UrBpMHPni7LlK1Sk&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: D Rajput, VSR Dantuluri, S Bajaj, A Kolhe - 2026 International Conference on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Recent work on large-language-model ( LLM )-based security remediation for Kubernetes and embedded firmware has … LLM remediation framework for CIS compliance on Oracle Multitenant (CDB/PDB) deployments including RAC and

---

### [46] Agentao: A Governed Local-First Runtime for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2608.13574
**作者**: Bo Jin, Qiang Jiao, Xin Tong
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly operate as execution systems that invoke tools, modify local state, use persistent memory, and interact with external protocols. These capabilities make agents useful, but they also introduce risks related to over-privileged actions, weak auditability, prompt injection, tool poisoning, and uncontrolled side effects. This paper presents Agentao, a governed local-first runtime for tool-using LLM agents. Agentao separates model-generated action proposals from host-authorized execution through a layered architecture consisting of host-facing surfaces, a host contract, a runtime core, a permission-mediated tool system, and supporting subsystems for memory, replay, plugins, skills, sub-agents, and protocol integration. We describe the motivation, threat model, design goals, governance model, execution pipeline, and structured event interface of the system. Agentao does not provide formal safety guarantees; rather, it demonstrates how permissions, state, protocol bound

---

### [47] I-CALM: Incentivizing Confidence-Aware Abstention for LLM Selective Answering

**链接**: https://arxiv.org/abs/2604.03904
**作者**: Haotian Zong, Binze Li, Yufei Long, Sinyin Chang, Jialong Wu, Gillian K. Hadfield
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Architecture-Dependent Causal Transfer of Activation States Across Large Language Models

**链接**: https://arxiv.org/abs/2608.16347
**作者**: Fernando Cardenas Piepereit
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct communication between AI systems relies on natural language as an intermediate layer, incurring encoding/decoding overhead, token cost, and latency. We ask whether internal activation states can instead be transferred causally between different large language model (LLM) architectures via a learned projection, evaluated at three levels: representational similarity, cross-model retrieval from projected states, and end-to-end causal transfer via activation injection during generation. Using four architecturally diverse open-weight models (Qwen2-0.5B, Phi-3-mini, Mistral-7B, FLAN-T5-base), we find that representational alignment in trained models exceeds a random-initialization null baseline and is best captured by a rank-based metric (mutual k-nearest-neighbour alignment), more robust to activation-magnitude outliers than centered kernel alignment (CKA) or Procrustes analysis. A learned projection network retrieves the correct target-model representation from a held-out set well a

---

### [49] Ventor-QTest: Threat-Model-Driven Verification of Vendor-Hosted LLM APIs

**链接**: https://arxiv.org/abs/2608.16391
**作者**: Xiangfan Wu, Zonghao Ying, Huiyu Wu, Xing Zheng, Huangsheng Cheng, Xiaorong Shi 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models become increasingly widespread, third-party providers that deploy open-weight models have become an important part of the ecosystem. Auditing the quality of their inference APIs is therefore an open problem. We formalize hosted model routing as a stochastic process and propose \mbox{\textbf{Ventor-QTest}}, a composite black-box audit that requires no probability information from the target API. Its repeated-request component sends each frozen constrained context to the target multiple times, reconstructs a categorical output distribution from the returned text counts, and reports \emph{average fidelity loss} (AFL) as a null-bias-corrected, within-window mean coarsened-KL statistic. Its long-sequence component uses independent runs to report \emph{extreme fidelity loss} (EFL) through the empirical upper tail of a run-level reference-centered-surprisal statistic. Across three logprob-capable route conditions, AFL shows strong linear descriptive agreement with a l

---

### [50] SAPE: Sandwich Adapters for Parameter Efficiency in Large Language Model Fine-Tuning

**链接**: https://arxiv.org/abs/2608.15360
**作者**: Mohammad Aref Jafari-Raddani and Morteza Mohajjel Kafshdooz
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Parameter-Efficient Fine-Tuning (PEFT) has substantially reduced the hardware cost of adapting Large Language Models (LLMs) by decreasing the number of trainable parameters, recent studies have sought to further improve PEFT through parameter sharing. However, these approaches either employ uniform parameter sharing across layers, which can delay convergence, or rely on dynamic masking strategies, which add computational overhead. The potential of sharing patterns inspired by the inherent hierarchical structure of Transformer architectures remains unexplored in PEFT. To address this gap, we introduce SAPE (Sandwich Adapters for Parameter Efficiency), a PEFT framework based on a sandwich-style hard weight-sharing topology. SAPE routes intermediate Transformer layers through balanced shared group adapters while strictly isolating the input embedding and final projection boundary transformations to prevent gradient interference. This design significantly reduces memory consumption w

---

### [51] STAGE: Controlled Objective Admission for Multi-Preference LLM Alignment

**链接**: https://arxiv.org/abs/2608.16553
**作者**: Yongqi Tong, Zhenyu Zhang, Ruirui Wang, Kewei Fu, Shaoqing Lin, Sijie Dong 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-preference alignment is often framed as scalarization: combine reward dimensions, then optimize. This leaves a temporal decision underspecified: when should each preference dimension enter policy optimization? We propose \methodname, a stability-guided active-set controller for controlled objective admission. \methodname starts from a small active set, retains admitted objectives, and expands when reward-deviation gates indicate low recent deviation or a patience budget is exhausted. A probing phase estimates a hard-to-easy order, and adaptive weighting emphasizes underperforming active dimensions. Automatic evaluations with 15 training preferences and 16 held-out benchmark columns show that \methodname obtains higher averages than simultaneous scalarization and shared-budget adapted baselines. Component ablations and expansion dynamics further support cumulative retention, gated admission, and probing-derived ordering as useful design choices in this setting. These results posit

---

### [52] Agentic Transaction: Towards ACID-Compliant Agent Systems

**链接**: https://arxiv.org/abs/2608.13900
**作者**: Zhaoyan Sun, Xiaoxiao Wang, Guoliang Li
**来源**: cs.DB cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are evolving from conversational assistants into autonomous systems that execute long-horizon tasks through reasoning, tool use, code generation, and workspace manipulation. As agents increasingly operate over persistent environments and multi-step workflows, they face challenges analogous to those addressed by transactional database systems: reliable execution, consistent outcomes, safe concurrency, and durable state management. We introduce the concept of an agentic transaction and propose an ACID-compliant agent system framework that reinterprets the classical ACID properties for agent execution through four semantic guarantees: Semantic Atomicity, Semantic Consistency, Semantic Isolation, and Semantic Durability. Together, these properties provide a principled foundation for building reliable agent systems despite model uncertainty and dynamic execution environments. To instantiate this framework, we develop an ACID-compliant data agent that realiz

---

### [53] Spatial Message Passing in Language Space for Pathology Image Interpretation

**链接**: https://arxiv.org/abs/2608.14309
**作者**: Jing-Cheng Yang, Hao-Jung Wang, Jinhao Du, Yang Hu, Ming-shan Tsai, Jens Rittscher 等 (7 人)
**来源**: cs.CV q-bio.TO
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) can generate pathological descriptions from histological images, but gigapixel Whole Slide Images (WSIs) exceed their visual context limits. The standard tiling workaround makes WSIs tractable yet severs the tissue neighborhoods that define tumor-stroma interfaces and morphology. We introduce Spatial Language Message Passing (SLMP), a framework that performs spatial reasoning entirely in language space, human-readable by construction. SLMP represents a WSI region as a spatial text graph: tiles are nodes initialized with MLLM descriptions, and edges encode spatial adjacency. For each tile, an LLM refines its description by integrating language messages from adjacent tiles under a shared aggregation policy that, on the tile grid, acts as an adaptive local kernel operating on text rather than learned embeddings. This policy is an inspectable prompt that can be refined from model-observed tissue phenotypes via textual gradients, enabling automatic s

---

### [54] Discovering Efficient and Explainable Communication Topologies for LLM-based Multi-Agent Systems via Causal Inference

**链接**: https://arxiv.org/abs/2608.12921
**作者**: Junzhi Li, Peng He, Qirui Ji, Wei Wang, Lixiang Liu, Chuxiong Sun
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Do AI chatbots find what experts would? Effects of model, user role, and sample size on study retrieval for medical questions

**链接**: https://arxiv.org/abs/2608.13786
**作者**: Qingfang Liu, Qiao Jin, Joe D. Menke, Thorsten Kahnt, Zhiyong Lu
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) chatbots are increasingly used to answer clinical questions with citations to relevant clinical studies. Prior research has largely focused on citation fabrication, leaving a gap in evaluating the quality of retrieved studies and the factors driving their selection. In this study, we evaluated three general-purpose LLM chatbots: Claude Sonnet 5, Gemini 3.1 Pro, and ChatGPT GPT-5.5. We prompted the models with clinical questions adapted from 20 review questions in Issues 6 and 7 of the 2026 Cochrane Database of Systematic Reviews, simulating patient, clinician, and evidence-synthesis researcher roles. Each chatbot was queried under each user role with four independent repetitions, yielding 720 responses. Each chatbot was asked to support its answers with primary clinical citations, which we benchmarked against the included and excluded study sets of the Cochrane reviews. On average, a chatbot response retrieved 39.2% $\pm$ 29.8% of Cochrane included studies, w

---

### [56] LLM-Guided Graph Generation for Structure-Based Local Improvement Methods

**链接**: https://arxiv.org/abs/2608.13333
**作者**: Hai Xia, Vaidyanathan Peruvemba Ramaswamy, Stefan Szeider
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] A Memory-Augmented Self-Improvement Framework Using Reinforcement Learning and LLM -Generated Educational Contexts

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11637329/&hl=zh-CN&sa=X&d=10501086237098381890&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-y0EEj7ToP4Dm3wl75UOV1e&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: M Tselepatiotis, E Alepis, M Virvou - 2026 International Conference on Computer …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper presents the Memory-Augmented Self-Improvement Framework (MASIF), an adaptive instructional framework for educational environments with multiple teaching strategies, difficulty levels, learner-state indicators, and measurable

---

### [58] Clinical Utility of LLM -assisted Chart Review for the Detection of Bleeding Events

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1246782026001163/pdf%3Fmd5%3Dc633d8f656fe5c7c7058fd8fbd24714c%26pid%3D1-s2.0-S1246782026001163-main.pdf&hl=zh-CN&sa=X&d=5499396855377828607&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-w1gtNhfraUVmTc32eUnClP&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: MC Reuland, OM van der Meer, A Testoni… - Transfusion Clinique et …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Manual review detected 66 events, while the LLM detected 647 events. Manual review identified 7 true events missed by the LLM 1.1% (7/654). The LLM identified 588 true events not captured by manual review, corresponding to an incremental

---

### [59] PWLR: Pairwise Witness Local Rejection for Boundary-Aware Out-of-Distribution Detection

**链接**: https://arxiv.org/abs/2608.15802
**作者**: Chengyao Jia, Ruixuan Wang
**来源**: cs.CV cs.LG
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Out-of-distribution (OOD) detection remains challenging for image classifiers, especially when near-OOD samples lie close to in-distribution (ID) class boundaries. Recent vision-language detectors improve OOD detection through class semantics, local prompting, or LLM-generated outlier concepts, but seldom use language as explicit boundary evidence between confusing ID classes. We propose Pairwise Witness Local Rejection (PWLR), which uses an MLLM offline to describe visible local cues that favor one ID class over a specific rival class. These cue phrases are then screened with ID-only data under a frozen vision-language backbone, so that only reliable local verifiers are kept. At inference, PWLR first retains a small set of globally plausible classes, then checks whether any of them is locally supported against its most relevant rivals, and finally combines this pairwise local evidence with the global class score through calibration. Experiments on ImageNet-100 far-OOD, cleaner/challen

---

### [60] Evo-Harness: Context-to-Harness Skill Compilation for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2608.15071
**作者**: Tianxin Wei, Zhan Shi, Minhua Lin, Bing He, Zewen Liu, Yisi Sang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from experience is critical for developing capable, self-improving large language model (LLM) agents. Existing methods typically extract knowledge from accumulated trajectories via reflection, memory, rules, or skills. However, agents in realistic environments continuously encounter novel tasks, often offering only a one-shot opportunity to improve. These executions yield rich but highly noisy contexts, entangling broadly useful lessons with task-specific artifacts. Critically, prior works rarely validate their effectiveness on complex real-world tasks or isolate the underlying drivers of improvement. To address these gaps, we formulate online harness learning, where a frozen agent improves by continually updating a structured harness across sequential tasks. This formulation enables a systematic study of key self-improvement factors through our proposed Evo-Harness. At its core, context-to-harness skill compilation distills noisy, single-shot executions into reusable skill ha

---

### [61] Limits to scalable evaluation at the frontier: LLM as Judge won't beat twice the data

**链接**: https://arxiv.org/abs/2410.13341
**作者**: Florian E. Dorner, Vivian Y. Nastl, Moritz Hardt
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Enhancing the Non-Functional Quality Compliance of LLM-Generated Code through Quality-Aware Preference Learning

**链接**: https://arxiv.org/abs/2503.09020
**作者**: Liang Lu, Yuan Jiang, Christoph Treude, Shuzheng Gao, Jingyu Xiao, Xiaohong Su and Michael R. Lyu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] QGFace-LLaVA: Quality-Aware Controlled Fusion of Structured Side Information for Face Analysis Under Imperfect Metadata

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2313-7673/11/8/582&hl=zh-CN&sa=X&d=12553770427759490282&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-wCIqSgD74P0EBVE6Nt_Ipk&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: J Feng, N Xu, X Li, Z Fu, Z Xiao, Z Huang - Biomimetics 等 (7 人)
**匹配关键词**: Large Language Model, MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> large language model ( MLLM )-centered framework for robust face analysis under imperfect metadata. A pretrained MLLM serves as the … Overall, the framework transfers biomimetic selective cue integration into MLLM -based face analysis by

---

### [64] Scaling Domain Data Repetition in LLM Pretraining

**链接**: https://arxiv.org/abs/2608.14071
**作者**: Jingwei Li, Xinran Gu, Rui Dai, Xintong Hao, Chengyin Xu, Yan Wu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models scale, their training-token budgets must also increase to maintain an appropriate tokens-per-parameter ratio (\(\mathrm{TPP}\)). However, high-quality domain data is much harder to scale than general web data. As model size and the training-token budget increase, its fraction in the training mixture tends to decrease. Repeating the available high-quality data provides an effective way to counteract this dilution, but excessive repetition may lead to overfitting. We study this trade-off under practical LLM scaling, where the training-token budget grows proportionally with model size. For a fixed domain, we first find that, surprisingly at a fixed \(\mathrm{TPP}\), the optimal repetition count mildly increases with model size. Across different domains, we find that the optimal repetition count is strongly negatively correlated with the final validation loss of a domain: domains with lower loss can generally benefit from more repetitions. In contrast, the amount o

---

### [65] HyMem: Hierarchical Context Management for Long-Horizon Agents via Information Isolation

**链接**: https://arxiv.org/abs/2608.15703
**作者**: XinQi Wang, Jinwei Xiao, Sijia Cui, Hongming Zhang, Yanna Wang, Qingyang Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents often perform poorly on complex, long-horizon tasks because their context becomes increasingly cluttered over time. As interactions accumulate, detailed execution traces and intermediate outputs dominate the context, making it difficult for the model to retain and use high-level planning information. Most existing methods address this issue through compression or retrieval applied to a single, flat context, which does not clearly separate different types of context information and often leads to degraded reasoning. To address this challenge, we propose HyMem, a hierarchical framework that explicitly separates the agent's context into distinct functional layers. HyMem organizes context by function to separate high-level planning from execution and complex analysis. Its isolated reasoning module handles complex subtasks without adding intermediate reasoning traces to the persistent planning context, while its memory management module preserves task progr

---

### [66] Who's Keeping Score? Interactive Steering of LLM-Powered Scoring with Attune

**链接**: https://arxiv.org/abs/2608.14948
**作者**: Bhavya Chopra, Meng Chen, Rebecca Dang, Chanbin Park, Shreya Shankar, Sepanta Zeighami 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to score text records at scale (e.g., rating candidate resumes on a 1-5 scale). However, existing LLM-powered approaches do not account for the fact that effective scoring requires both holistic understanding of records and locally consistent judgments across similar ones. We present Attune, a mixed-initiative system for steerable LLM-powered scoring. Given a task description and scoring range, Attune performs pairwise comparisons across records to develop a global understanding first, and then resolves these comparisons into consistent score assignments-deriving scoring criteria and rules bottom-up in the process. These serve as shared representations of scoring logic that users can inspect and edit. Based on insights from a formative study (n = 12), Attune's interface introduces novel steering interactions that allow users to deterministically refine scoring logic. Users can provide examples, directly edit criteria, rules, or target 

---

### [67] POI Recommendation with LLM-Augmented Multi-Graph Learning and Contrastive Alignment

**链接**: https://arxiv.org/abs/2608.16407
**作者**: Burak Tamer, Wolfram H\"opken and Zehui Wang
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Point-of-interest (POI) recommendation models based on graph neural networks achieve strong performance by propagating collaborative signals over user-item interactions, yet they struggle with the cold-start problem, where items with few or no interactions are not represented. In this paper, we propose LLM-augmented Multi-Graph Contrastive Learning (LLM-MGCL), a multi-graph neural network that uses semantic and spatial information about items to extend the LightGCN backbone with two auxiliary item-item graphs: a semantic graph constructed from sentence embeddings of LLM-generated photo summaries and keywords, and a geographic graph derived from Haversine distances between business locations. Item embeddings are propagated over all three graphs in parallel, fused additively, and aligned across views through a bidirectional InfoNCE contrastive objective that connects behavioral, semantic, and spatial representations of the same items. Experiments on the Yelp Multimodal Recommendation Dat

---

### [68] SkillCommit: Evolving Agent Skills through Behaviorally Validated Scope Expansion

**链接**: https://arxiv.org/abs/2608.15165
**作者**: Yu He, Weikai Yang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can continually improve without parameter updates by converting historical experience into reusable procedural knowledge. However, existing methods often consolidate experience based on semantic similarity or LLM judgments, which may merge superficially related but behaviorally incompatible strategies and thereby degrade performance. To address the issue, we propose SkillCommit, an online skill evolution framework that continuously transforms experience into a hierarchical library of reusable skills. Each new experience is initially preserved as an instance-specific patch, retaining the behavior validated in its local context. As related skills accumulate, SkillCommit abstracts those sharing a common behavioral mechanism into higher-level skills. Specifically, for each incoming skill, embedding-based retrieval first identifies candidate related skills. Cross-instance replay and an LLM-based mechanism check determine whether these skills transfer across

---

### [69] Semantic Uncertainty-Guided Orchestration in Hierarchical Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.14707
**作者**: John Knowlton, Aritra Guha, Risto Miikkulainen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM)-based multi-agent systems become increasingly capable, coordinating agents under uncertainty becomes a fundamental challenge. Existing orchestration strategies typically rely on fixed interaction patterns and often lack mechanisms for assessing the reliability of intermediate reasoning steps, allowing errors and hallucinations to propagate through the system. This paper introduces a semantic-uncertainty-guided orchestration approach, HASSUM as a general framework for uncertainty-aware coordination in multi-agent systems. The method estimates uncertainty using semantic entropy and semantic density, which measure trust at the level of answer semantics rather than output probabilities. These signals enable adaptive orchestration decisions, including output verification, selective reprompting, additional deliberation, and confidence-aware response selection. Because the approach operates independently of any particular agent architecture, it can be integrated 

---

### [70] Broken Symmetry in LLM Refusal: Answer Release Is More Local Than Refusal Restoration

**链接**: https://arxiv.org/abs/2608.15772
**作者**: Yiqi Liu, Yang Wang, Songxin Wang, Chenghao Xiao, Chenghua Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a language model refuses to answer a prompt, it is unclear whether the correct answer is erased from its internal representations, or merely suppressed at the output layer. We investigate this mechanism using a controlled withhold setting, which yields perfectly matched answering and refusal trajectories for bidirectional activation patching. We uncover a causal asymmetry in intervention locality under matched causal interventions, which we term broken symmetry. Even when a model generates a clean refusal, the correct answer remains linearly recoverable from its hidden states. Furthermore, releasing this withheld answer is a highly local operation, requiring only a single-position patch. Conversely, the reverse operation is not equally local: reimposing suppression requires broader interventions across multiple positions, and assembling a coherent refusal sequence is more difficult still. We further demonstrate that while an average answer-to-refusal displacement vector marks the 

---

### [71] LLMs for Zero-Shot Threat Detection via Structured Risk Indicators

**链接**: https://arxiv.org/abs/2608.16508
**作者**: Abdullah Alghamdi, Siamak Layeghy and Marius Portmann
**来源**: cs.CR cs.LG cs.NI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose a two-stage large language model (LLM) framework for zero-shot detection of insider threats and advanced persistent threats (APTs) from heterogeneous security logs. The framework models user activity as chronological timelines and incorporates retrieval-augmented generation (RAG) to provide personalised behavioural context from each user's historical activity. Rather than performing end-to-end classification directly from raw logs, it first generates structured, interpretable sets of threat-specific risk indicators, which are then classified jointly across temporal sequences to capture attack patterns spanning multiple windows.The framework is evaluated on two benchmark datasets, CERT r5.2 for insider threat detection and PicoDomain for APT detection, using four combinations of two open-weight LLMs under both retrieval and non-retrieval settings. All configurations outperform the previous state-of-the-art LLM-based framework (GABM), with the best configuration improving the 

---

### [72] FactorFlow: A Visual Analytics Workspace with Large Language Model-Assisted Interpretation for Factor Analysis

**链接**: https://arxiv.org/abs/2608.13585
**作者**: Justin Philip Tuazon, Joemari Olea, Richelle Ann Juayong
**来源**: cs.HC stat.ME
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In exploratory factor analysis (EFA), one typically aims to extract and describe a small number of factors (i.e., latent variables) based on the relationships among numerous manifest variables (i.e., directly observable variables). In practice, performing EFA entails examining different factor models (and rotations) to identify the underlying latent structure. Now, the primary criterion for evaluating a factor model is interpretability. That is, the preferred model is the one that yields a meaningful, coherent, and theoretically defensible factor structure. However, gauging a model's interpretability is not a trivial task, as it is subjective and often requires keeping track of large amounts of information simultaneously. Because of this, researchers typically employ various visualizations to interpret models and determine the "best" one. Hence, we introduce FactorFlow, a visual analytics workspace for performing EFA end-to-end. Using FactorFlow, one can fit and rotate factor models, p

---

### [73] LLMs Can Predict Failure Risk, But Struggle to Predict Which Collaboration Protocol Pays Off: Cost-Aware Protocol Routing Across Reasoning Tasks

**链接**: https://arxiv.org/abs/2608.14927
**作者**: Chih-Hsuan Yang, Jingyan Jiang, Cheng-Hau Yang, Vikram Vasudevan, Huihuo Zheng, Venkatram Vishwanath 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) systems can improve reasoning by spending more computation, but deployment requires deciding when extra collaboration is worth its cost. We isolate this decision by running every problem under four protocols while holding the solver fixed within each setting: direct solving (Baseline), iterative self-correction (Single), planner-executor-reviewer collaboration (PER), and multi-agent deliberation (Broadcast). The primary benchmark comprises 4,181 competition-level math problems; paired robustness checks cover four benchmarks spanning competition math, biology, and broader science with two solver families. Across fixed policies, trained routers, and frozen LLM routers, conservative policies under-escalate, whereas higher-solve frozen routers often over-escalate. A post-answer, pre-collaboration gpt-oss-120b probe ranks Baseline failures with 0.8847 AUROC (4,151 parseable cases; 95% CI [0.8732, 0.8955]). The same score remains informative for predict

---

### [74] SchurQuant: Groupwise Discrete Optimization for Layer-Wise LLM Quantization

**链接**: https://arxiv.org/abs/2608.15567
**作者**: Gunjun Lee, Sehwan Son, Younjoo Lee, Byungjun Kim, Jung Ho Ahn
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-only post-training quantization (PTQ) enables the deployment of large language models under tight memory budgets, but accuracy often collapses at 2-3 bits. Existing backpropagation-free PTQ optimizers have two limitations: group decisions ignore the correction that the remaining continuous suffix can absorb, and discrete refinements typically keep the affine quantization grid fixed. We introduce SCHUROPT, which analytically eliminates the suffix's optimal continuous response, yielding an exact groupwise quadratic with Schur-complement curvature. It then alternates closed-form row-wise scale/zero-point refitting with coordinate descent over integer codes. With the GPTQ objective fixed, SCHUROPT improves mean zero-shot accuracy on 2-bit Qwen3-4B by 11.88 percentage points (pp). At higher precision, however, tighter reconstruction does not consistently improve end-model metrics. SCHURQUANT therefore combines SCHUROPT with quantized-prefix teacher reconstruction, reference-weight re

---

### [75] Optimal Watermark Localization in Mixed-Source Large Language Model Texts

**链接**: https://arxiv.org/abs/2608.14906
**作者**: Jose H. Blanchet, T. Tony Cai, Xiang Li, Hao Liu, Qi Long, Weijie J. Su
**来源**: stat.ME cs.CL cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking provides a principled way to authenticate text generated by large language models (LLMs). In practice, however, the final text may be mixed-source, with watermark evidence surviving at only a subset of token positions after rewriting, insertion, deletion, or paraphrasing. Although prior work has studied global detection of watermark signals, when such signals can be localized remains unclear. We formulate watermark localization as a token-level multiple-testing problem based on pivotal statistics, with a latent indicator recording whether watermark dependence survives at each position. Under an asymptotic regime indexed by exponents for signal sparsity, next-token concentration, and effective-vocabulary growth, we derive a sharp boundary for global detection and phase transitions for discovery and classification within the class of coordinatewise pivot-based localization rules. We show that discovery is strictly harder than detection and that consistent classification is i

---

### [76] A validity-guided workflow for robust large language model research in psychology

**链接**: https://arxiv.org/abs/2507.04491
**作者**: Zhicheng Lin
**来源**: cs.HC cs.AI cs.CL cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] WeSCE: A Benchmark for Measuring Security Drift in LLM-Driven Code Editing

**链接**: https://arxiv.org/abs/2608.15092
**作者**: Zhiyu Zhang, Tingyue Wen, Senke Sun, Dengxiang Liang, Enhao Huang
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we introduce WeSCE, a benchmark for quantifying security drift in code editing under weak-security constraints, where tasks specify only functional objectives without explicit security requirements. WeSCE consists of 400 executable programs derived from real-world code, covering feature addition, feature removal, bug fixing, and refactoring. To quantify security drift, we propose a continuous risk representation that aggregates heterogeneous vulnerability signals through a unified formulation, and define drift measures capturing changes in overall risk, worst-case severity, and vulnerability distribution under code transformations, providing a multi-scale view of security spanning average-case behavior to worst-case emphasis.

---

### [78] When Entropy Is Not Enough: Reclaiming Lost Semantics in LLM Output Length Prediction

**链接**: https://arxiv.org/abs/2608.15592
**作者**: Feiyang Ren, Shengtao Wen, Lingbing Guo, Yu Tian, Yuanning Cui, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient LLM serving is often bottlenecked by the need to pad sequences to a fixed maximum length, and this wastes compute and degrades throughput. Predicting output lengths in advance makes it possible to adopt length-aware scheduling, and this reduces the overhead. This advantage is especially pronounced in long-context reasoning and reinforcement learning applications. Existing approaches, such as entropy-guided token pooling, use token-wise entropy as their primary signal, but they tend to ignore differences in semantic content across tokens. So, important tokens are often underweighted, and tokens carrying little information receive disproportionate emphasis. This hurts the reliability of length prediction. We introduce ESTP (Entropy-and-Semantic Token Pooling), a lightweight framework that addresses this issue by combining entropy with attention-based importance scores. These scores are derived directly from the self-attention weights computed during the LLM prefill phase, and t

---

### [79] OTel: Building Domain-Specialized Telecom LLM Foundations for Intelligent Networks

**链接**: https://arxiv.org/abs/2608.15436
**作者**: Farbod Tavakkoli, Roderic Paulk, Jorden Terrazas, Kenneth Church, Mark Austin, Louis Powell 等 (10 人)
**来源**: cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier AI models have advanced rapidly, but they still struggle with telecom-specific tasks. We present Open Telco (OTel), an open telecom AI resource with derived datasets for retrieval, reranking, instruction tuning, and safety/abstention, plus 30 full-parameter post-trained baselines across embedding, reranking, and language models. The community has already engaged substantially with the resource: as of May 3, 2026, the released models have been downloaded over 16 million times, and the project has received 157+ pieces of media coverage worldwide. Building on prior open telecom datasets and benchmarks, OTel provides documented telecom data sources, held-out evaluation partitions, trained embedding models, rerankers, context-grounded LLMs, and safety/abstention data in one unified resource. OTel post-training improves performance across all three model families: embedding retrieval reaches 93.5% NDCG@10, reranking reaches 0.952 MRR@10, and language-model correctness reaches 88.2%.

---

### [80] LlamaRec-LKG-RAG: A Single-Pass, Learnable Knowledge Graph-RAG Framework for LLM-Based Ranking

**链接**: https://arxiv.org/abs/2506.07449
**作者**: Vahid Azizi, Fatemeh Koochaki
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] Constraint-Aware Synthetic Tabular Data Generation via Inter-Column Constraint Discovery with LLM Agents

**链接**: https://arxiv.org/abs/2608.15109
**作者**: Jianxing Zhao, Mao Guan, Dongyu Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating structurally valid synthetic tabular data remains difficult: outputs with high statistical fidelity and downstream utility can still violate semantically meaningful domain constraints. We study the discovery and enforcement of three complementary inter-column constraint families---equations, linear inequalities, and logical dependencies. Our unified tool-grounded workflow represents all three as machine-executable hypotheses and applies a common interface for full-table validation, deterministic diagnosis, and counterexample-guided revision. A generator-agnostic postprocessor coordinates family-specific repairs on outputs from unchanged tabular generators. Across curated behavioral audits and end-to-end evaluations, the complete workflow improves held-out violation detection over one-shot direct prompting, while postprocessing yields zero measured violations for every retained, applicable constraint, improves downstream utility on most datasets, and largely preserves univari

---

### [82] Catching Hallucinated Citations in Video-LLM Question Answering: A Self-Verification Pipeline and Verifier Ablation Study

**链接**: https://arxiv.org/abs/2608.15574
**作者**: Yogesh Kumar
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video question answering systems built on vision-language models often produce timestamped claims with high confidence even when unsupported by the cited frame. This deceptive hallucination arises because timestamps imply grounding without ensuring correctness, increasing user trust but not accuracy. We introduce a pipeline that closes this loop. A retrieval-augmented language model drafts answers with per-claim timestamp citations, and each cited frame is independently re-examined before being shown to the user. We compare against a plain baseline and ablate three verification designs, evaluated on both Apple Silicon (MLX) and Google Colab (HF Transformers, CUDA). Directly asking the vision model whether a frame supports a claim fails completely (0% catch rate on 40 claims) due to sycophancy. Blind re-captioning plus a general LLM judge improves results but is unstable, oscillating between 0% and 100% flagged depending on prompt phrasing. Replacing that judge with a small natural lang

---

### [83] SubZero+: Efficient Zeroth-Order LLM Fine-Tuning via Large Learning Rates

**链接**: https://arxiv.org/abs/2608.15665
**作者**: Ziming Yu, Shuyao Xiao, Xingyu Zhao, Sike Wang, Pan Zhou, Peiyu Zang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization enables backpropagation-free fine-tuning of large language models, but existing ZO methods suffer from high-variance gradient estimators, making convergence unstable and highly sensitive to learning rates. We propose SubZero+, an improved SubZero framework that improves stability in three complementary ways: (i) multi-query gradient estimation within layer-specific low-rank subspaces to reduce variance without exhibiting the multi-query paradox; (ii) a subspace Adam optimizer that performs adaptive updates using in-subspace multi-query gradient statistics; and (iii) a sign correction for QR-based subspace construction to ensure Haar-distributed projection matrices, eliminating implementation-dependent orientation ambiguity. Experiments on models from 1.3B to 32B across SuperGLUE, under both full-parameter tuning and LoRA, show that SubZero+ consistently outperforms prior ZO baselines, enlarges the stable learning-rate range, and narrows the gap to first-o

---

### [84] PCA-guided Activation Scaling for Monotonic Bidirectional Control over LLM Sycophancy

**链接**: https://arxiv.org/abs/2608.16650
**作者**: Zheng Chen, Zhaoxin Feng, Yip Tin Po, Jianfei Ma, Emmanuele Chersoni, Bo Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) exhibit sycophancy, a tendency to agree with user beliefs regardless of factual accuracy. This can reinforce misconceptions, but eliminating it entirely risks over-correction against valid opinions. Effective control must therefore both reduce and increase sycophancy with predictable and gradual effect. Yet, existing methods fail to ensure a bidirectional and monotonic relationship between steering strength and behavioral outcome across models and datasets. We introduce PCA-guided Activation Scaling (PAS), an activation steering framework that decomposes residual stream activations into a PCA-identified sycophancy-honesty subspace and an orthogonal residual, then applies distinct scaling exponents to achieve monotonic, bidirectional control. Across three LLMs and three datasets, PAS achieves strong monotonicity (Spearman $\rho$ = +0.92) and an average shift of 15.4% per direction, compared with 8.7% for the baselines. Ablation studies confirm that the decom

---

### [85] When State Becomes an Attack Surface: State-Semantic Injection in LLM-Driven Embodied Agents

**链接**: https://arxiv.org/abs/2608.16806
**作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have demonstrated capabilities in in-context learning, task decomposition, step-by-step reasoning, and code generation, driving their gradual evolution from text generation models into the core of agents capable of perceiving environments, invoking tools, and executing tasks. Traditional LLM Agents typically obtain information through webpages, documents, databases, or external tools and generate corresponding invocation sequences according to user goals; when this technology is further integrated with robotic systems, large language models begin to undertake functions such as task understanding, high-level planning, and behavioral decision-making. SayCan combines the task reasoning capability of language models with the affordances of robotic skills, while Code as Policies and ProgPrompt generate robot task plans through policy code and programmatic prompting, respectively, and VoxPoser uses language models and vision-language models to construct three-dim

---

### [86] LLM-based Framework for Generating and Verifying Parallel DEVS Statecharts

**链接**: https://arxiv.org/abs/2608.14956
**作者**: Vamsi Krishna Vasa, Hessam S. Sarjoughian, Edward J. Yellig
**来源**: cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The development of models demands sound modeling and simulation knowledge as well as domain knowledge. Every model should accurately represent a system's dynamics and be verifiable. Toward this objective, this research introduces an agentic PDEVS-LLM framework to assist human modelers in generating and verifying PDEVS statecharts for behavior modeling of atomic Parallel Discrete Event System Specification (PDEVS) models. The framework supports (re)generating plausible facts from a system description prompt using the agentic LLM used for generating plausible facts. Inconsistencies in plausible facts lead to incorrect PDEVS statecharts having logical structure and behavioral inaccuracies. A controlled-correction mechanism is developed to verify the logical consistency of the plausible facts. The agentic LLM is used to generate key behavioral conditions from the system description prompt. The plausible facts are then verified against the behavioral conditions using propositional logic ent

---

### [87] Mental Model Management: An Operator-Based Framework for LLM Memory

**链接**: https://arxiv.org/abs/2608.15451
**作者**: Oliver Kramer
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models process large amounts of information but usually lack an explicit mechanism for maintaining compact and evolving conceptual representations. We introduce Mental Model Management (3M), a framework in which knowledge is represented as mental models consisting of compact chunks. Rather than accumulating text passages, 3M continuously integrates new information into an existing conceptual representation. A set of operators extracts knowledge, retrieves relevant models, adds and updates chunks, reorganizes representations, detects inconsistencies, and derives new knowledge. We describe the main 3M operators and illustrate each operation using Evolution Strategies as a running example.

---

### [88] INSIDE the Student's Mind: Jointly Modeling Latent Reasoning and Action in LLM Student Simulators

**链接**: https://arxiv.org/abs/2608.10492
**作者**: Rose Niousha, Minwoo Kang, Narges Norouzi
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Large language model-assisted discovery of cohorts from scientific literature

**链接**: https://arxiv.org/abs/2608.15909
**作者**: Moritz Sturm, Lisa M. Berg, Inken Berg, Harishny Sarma, Jasmin Hartmann, Denissa Girschik 等 (9 人)
**来源**: cs.IR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Planning multi-study analyses requires identifying cohorts with the relevant participants, phenotypes, and data modalities. This process commonly relies on prior knowledge, cohort catalogues, and manual literature searches. We developed a complementary question-driven framework that searches relevant scientific literature and extracts explicit cohort names. Methods: The framework first generates multiple PubMed queries from configurable vocabularies and templates and retrieves the resulting scientific literature automatically through the PubMed API. A large language model then screens the retrieved titles and abstracts and extracts explicit cohort names using a prompt tailored to the research question. The extracted names are deduplicated with human review. Configurable code, prompts, and example outputs are available at https://gitlab.rz.uni-frankfurt.de/cap_molgenlab/literature-cohort-discovery. Evaluation: As a use case, we applied the framework to youth aggression genet

---

### [90] PolyWorkBench: Benchmarking LLM Agents for Cross-Lingual Long-Horizon Workflows

**链接**: https://arxiv.org/abs/2607.06008
**作者**: Hongliang Li, Yijin Liu, Zhiwei Zhang, Zihe Liu, Xinyue Lou, Jinan Xu 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Emergent Misaligned Communication in Long-Horizon Multi-Agent LLM Commerce

**链接**: https://arxiv.org/abs/2608.14825
**作者**: Zeyuan Li (Massachusetts Institute of Technology), Lukas Petersson (Andon Labs), Alessandro Acquisti (Massachusetts Institute of Technology), Michiel A. Bakker (Massachusetts Institute of Technology)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier LLM agents increasingly transact on behalf of separate principals, often using natural language rather than structured APIs. Much of the safety literature studies misaligned LLM behavior through adversarial-elicitation evaluations on single agents or stylized tasks. Its prevalence and structure in settings that combine long horizons, separate principals, real operational state, and inter-agent natural-language exchange remain insufficiently measured. We study 2,583 inter-agent emails from 20 one-year simulation runs of Vending-Bench Arena, a competitive vending environment spanning 13 frontier LLMs. We operationalize speech-act misalignment as emails containing false factual claims, manipulation, collusion, or threats, combining message content with ground-truth simulator state and logged reasoning traces to classify and validate such behavior. Under our primary classifier, 12.6% of emails are labeled misaligned; misalignment appears in all 20 runs and 74.7% of individual agen

---

### [92] The Hallucination Snowball: Modeling Error Propagation as State Transitions in Multi-Agent LLM Pipelines

**链接**: https://arxiv.org/abs/2608.14588
**作者**: Prabhjot Singh, Bhushan Pawar
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sequential multi-agent LLM pipelines chain specialized agents without verification at handoffs, creating a structural flaw with measurable and severe consequences. We show that hallucinations injected at Stage 1 do not merely persist; they transform: raw numerical facts become derived computations, then narrative prose, then editorially approved conclusions. At each transformation, detectability degrades near-irreversibly. We formalize this as the hallucination snowball effect, a first-order Markov process over four states (Raw Fact $\to$ Derived $\to$ Narrative $\to$ Invisible) with empirically measured per-boundary escape probabilities of 24.6%, 48.3%, and 89.3%. Across 346 automatically injected hallucinations in a 4-agent financial analysis pipeline on FinanceBench, gpt-4o detection drops from 72.0% at Stage 1 to 50.9% at Stage 4, and 23.7% of hallucinations survive completely undetected in the final output. Even the strongest model tested (Qwen3.5-397B-A17B, 87.0% at Stage 1) face

---

### [93] VLM- and LLM-Driven Multi-Agent System for PET Image Denoising

**链接**: https://arxiv.org/abs/2608.13791
**作者**: Boxiao Yu, Savas Ozdemir, Yang Xing, Fumio Hashimoto, Jiong Wu, Yizhou Chen 等 (10 人)
**来源**: eess.IV cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Positron emission tomography (PET) imaging suffers from limited spatial resolution and low signal-to-noise ratio, which can compromise quantitative accuracy and lesion detectability. Deep learning-based denoising methods have demonstrated strong potential for improving PET image quality. However, their practical deployment in real-world settings remains challenging, often requiring multiple specialized models and expert interventions, such as identifying motion-induced misregistration artifacts, estimating noise levels to select an appropriate denoiser, and performing lesion-focused quantitative assessment after denoising. Recent advances in vision-language models (VLMs) for image quality understanding and large language models (LLMs) for contextual reasoning provide new opportunities for automated, decision-driven workflows. Inspired by expert workflows for PET image quality enhancement, we propose an VLM- and LLM-driven multi-agent PET denoising framework that dynamically assesses im

---

### [94] LLM Safety Alignment in Low-Resource Languages: A Systematic Literature Review

**链接**: https://arxiv.org/abs/2608.14626
**作者**: Valdini Douglace Lemofouet, Blessing Ngozi Uzor, Paula Chikaodinaka Anyanwu, Danielle Blanche Kapsa, Sukairaj Hafiz Imam, P Sam Sahil 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have achieved substantial progress in safety alignment, yet their safety guarantees remain significantly weaker in low-resource and multilingual settings than in high-resource languages. In this paper, we conduct a Systematic Literature Review (SLR) of LLM safety alignment in low-resource languages by adopting the PRISMA 2020 methodology. Out of roughly 1,500 papers identified from Semantic Scholar, arXiv, and OpenAlex, 50 relevant studies have been selected and analyzed. Our review is organized around four themes: safety alignment methods, multilingual safety risks, evaluation benchmarks, and cross-lingual transferability. We further propose a taxonomy of safety alignment approaches based on three adaptation mechanisms: data adaptation, objective optimization, and mechanistic alignment. Across literature, translated English benchmarks fail to sufficiently represent culturally rooted harms, and multilingual models are more vulnerable to cross-lingual jailbr

---

### [95] AgentRewind: Recoverable Execution for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.14380
**作者**: Yu Zhuang, Kefei Chen, Yitong Duan, Shuxin Zheng, Jian Li, Xu-Yao Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many real-world tasks require LLM agents to interact with their environments over long execution horizons. Errors that occur early in execution may propagate through both the agent context and environment state, and their effects may be difficult to reverse through subsequent actions. Existing methods mainly seek to reduce such errors through plan refinement and safety checks but provide little support after errors occur. To enable recovery during long-horizon execution, we present AgentRewind, a runtime recovery framework that records aligned checkpoints of the agent context and controlled environment, allowing agents to return to an earlier state and resume execution with information from previous attempts. We also construct MettleBench, a benchmark for evaluating task completion and partial progress on long-horizon engineering assignments containing a series of related requirements. Experiments across tasks, multiple models, execution strategies, and agent harnesses show that AgentR

---

### [96] Constraint-Validated Sequential Planning for Multi-Agent Pursuit–Evasion Games with LLM -Assisted Assignment

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0016003226005685&hl=zh-CN&sa=X&d=16196010293560479452&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-w50dIRm8a4aVbjtB71rYd5&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: X Li, Z Li, Y Cheng, X Yang, X Yu - Journal of the Franklin Institute, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper studies a class of multi-player pursuit–evasion games with sequential interception requirements, in which the feasibility of assigning a pursuer to one or more evaders evolves over time and depends on the capture order. Such scenarios

---

### [97] Sequential LLM Release Facilitates Manipulation in Regulated Markets

**链接**: https://arxiv.org/abs/2601.11496
**作者**: Eilam Shapira, Moshe Tennenholtz, Roi Reichart
**来源**: cs.GT cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] Evaluating LLM -Based Conversational Recommenders with Semantic and Genre-Aware Metrics

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0167865526002886&hl=zh-CN&sa=X&d=3095364283399644690&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-wxHSoZAdEop784anLqO04s&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: D Parmar, D Shah, P Mazumdar, S Mallik - Pattern Recognition Letters, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Overall, this study provides a reusable evaluation framework for benchmarking LLM -based conversational recommendation systems and … an ablation study comparing the full KG+ LLM framework with an LLM -only baseline. In the LLM -only

---

### [99] A Graph-Based Reinforcement Learning Framework for Structured Drift Diagnosis and Recovery in Autonomous LLM Agents

**链接**: https://arxiv.org/abs/2608.14109
**作者**: Ismail El Hamraoui, Sagar Jose, Nicolas Bureau, Robert Plana
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents are increasingly deployed in complex real-world workflows, yet they remain vulnerable to runtime behavioral drift, a silent deviation from the original task that can lead to irreversible side effects on external systems. Existing approaches address drift at the prompt level but lack structured mechanisms for step-level detection, risk assessment, and recovery decision. Because the main task-executing agent is often a large and expensive model that cannot be re-trained on every deployment, this work targets a plug-and-play recovery module instead. It introduces a graph-based framework in which a single small language model is trained via reinforcement learning to specialize at each node of a recovery graph, external to the main agent. Each node has a precise role\,: drift classification, operation detection, risk evaluation, or final decision and the model learns to produce structured XML-formatted reasoning adapted to that role. Training combines rule-based struct

---

### [100] Representation Signatures and Risk-Feedback Alignment in LLM Trading Agents

**链接**: https://arxiv.org/abs/2605.28850
**作者**: Weicheng Xue
**来源**: cs.LG q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Multi-Bin Batching for Increasing LLM Inference Throughput

**链接**: https://arxiv.org/abs/2412.04504
**作者**: Ozgur Guldogan, Jackson Kunde, Kangwook Lee, Ramtin Pedarsani
**来源**: cs.CL cs.DC cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Second Thought: Reasoning in Parallel as LLM Agents Act and Observe

**链接**: https://arxiv.org/abs/2608.13667
**作者**: Zhensu Sun, Chengran Yang, Yunbo Lyu, Jieke Shi, David Lo
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents in the ReAct paradigm alternate between reasoning, acting, and observing, but deliberate reasoning is confined to the Thought phase: while the agent serializes an action and waits for the environment, its reasoning is frozen. We identify this recurring interval for Action and Observation as a reasoning idle window and ask whether it can host additional reasoning in parallel that serves future turns. Therefore, we propose Second Thought, a training-free inference framework that forks four auxiliary branches the instant each Thought phase concludes, decodes them concurrently with the main loop, and merges the generated thoughts back when the environment observation arrives. In this way, Second Thought relocates the added reasoning off the main thread's sequential decoding path. Across three agentic benchmarks and three reasoning LLMs, Second Thought lowers the average turn count in all nine (model,benchmark) pairs and reduces main thread decoding in six of them by up to 43% (r

---

### [103] Class Imbalance and Batch Effects in LLM-Based Screening for Systematic Reviews

**链接**: https://arxiv.org/abs/2608.14737
**作者**: Gilberto Sussumu Hida, Danilo Monteiro Ribeiro, Clayton Suguio Hida
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study analyses LLMs in imbalanced binary classification, using study screening in systematic reviews as the application domain. An experiment was conducted in five reviews, comparing individual and batch processing, with and without prevalence metadata. The results indicate a limited influence of the prevalence metadata, with no evidence that it improves performance. In contrast, batch processing produced larger behavioral changes that varied according to the prevalence of the class. The aggregate and item-level analyses did not always coincide. Therefore, batch processing should be evaluated not only in terms of cost, but also in relation to its effects on decision-making behavior.

---

### [104] Breaking and Defending LLM-Powered Social Media Bot Detection Systems

**链接**: https://arxiv.org/abs/2608.15893
**作者**: Nof Orenstein, Yoni Birman
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rise of social media bots poses a persistent threat, enabling misinformation, opinion manipulation, and the erosion of trust in online platforms. To combat this, machine learning systems have been developed to detect and limit bot activity, but attackers continuously adapt through techniques such as adversarial learning and behavior imitation, fueling an ongoing arms race between bots and detection tools. Recent advances in large language models (LLMs) have significantly improved bot detection by enabling deeper semantic and contextual analysis of accounts and their content. However, this shift also introduces new attack surfaces, allowing adversaries to craft exploits that directly target the reasoning and generation mechanisms of LLM-based classifiers. Industry tools such as Anthropic's Claude Code Security similarly leverage LLMs for security-critical decisions, further motivating a careful study of their attack surfaces. In this work, we investigate both the offensive and defen

---

### [105] A Collaborative Multi-Agent Framework for Preference-Reversal Attacks on LLM -as-a-Judge Models

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426028988&hl=zh-CN&sa=X&d=16610658948789925863&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-ysHXVqesCEOXras2R2gp9m&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: Z Zhou, X Li, W Dou, Z Liu - Expert Systems with Applications, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models (LLMs) are increasingly employed as evaluative judges in a wide range of decision-making tasks. However, these models remain vulnerable to preference-reversal attacks, where adversaries manipulate prompts to induce

---

### [106] Does ISO-Grounded NFR Specification Improve LLM Code Generation? A Comparison of Rich and Structured Interventions against a Natural-Language Baseline

**链接**: https://arxiv.org/abs/2608.13742
**作者**: Jo\`ao Pedro Monteiro Pereira and Vinicius Cardoso Garcia
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM-based code generation, Non-Functional Requirements (NFRs) are often specified as terse one-line phrases. We ask whether grounding those specifications in ISO/IEC 25010 Quality Model, either as rich natural-language prose (NL-rich) or as structured JSON (Structured), improves code generated on HumanEval/HumanEval-ET compared to a RobuNFR-style one-line baseline (NL-simple). We evaluate four NFRs (performance, error handling, code smell, readability) with ten prompt variations per condition under a fixed model snapshot and paired non-parametric analysis. Primary finding: ISO-grounded enrichment improves static quality proxies (unreadability density falls across all four NFRs (e.g., Performance 0.88 -> 0.69 for NL-rich)) and reduces sensitivity to prompt wording, but does not reliably improve functional correctness; for error handling, extended-test pass rate decreases, suggesting tension between defensive coding patterns and exact-output benchmarks. Secondary finding: when ISO con

---

### [107] CompoSkill: Compositional Skill Chain Attacks from Individually Scanner-Passing LLM Agent Skills

**链接**: https://arxiv.org/abs/2608.16246
**作者**: Mingxiao Liu, Zhoumian Jiang, Jianan Ma, Jian Zhang, Jialuo Chen, Xinhao Deng 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous AI agents tackling Long Horizon Tasks depend on marketplace skills that are certified one at a time: a scanner returns a safety verdict for each skill and declares the ecosystem safe if every package passes. We show that this assumption fails under skill composition. A skill may pass the per-skill scanner individually yet participate in a risky composition when an agent connects its outputs, capabilities, or side effects with those of other scanner-passing skills. This makes skill composition risk a path level property rather than a node level property, explaining why existing skill scanners that inspect individual packages achieve limited interception. To study this threat, we present CompoSkill, a framework that constructs skill composition attacks through a dual attacker system. The white-box attacker knows the victim's installed skill pool and directly injects explicit skill-id sequences; the black-box attacker knows only a role profile, downloads the top marketplace ski

---

### [108] LACE-SVD: Loss-Aware SVD with Cumulative Error Correction for LLM Compression

**链接**: https://arxiv.org/abs/2607.03057
**作者**: Zhuowen Liu, Longkun Hao, Shiyu Feng, Xiaowen Chang, Ruiqun Li, Changqun Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] LLM -assisted quality-aware GA–multi-agent deep deterministic policy gradient framework for multi-robot collaborative scheduling in construction quality control

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0926580526004449&hl=zh-CN&sa=X&d=3639720233764427582&ei=V2SCapaPHeOUieoP9aahyA0&scisig=AIVdB-xjceZEaOCBqUh9ttyRYgOA&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: M Zhu, Z Liu, H Zhou, W Li, S Wang, Q Zhang - Automation in Construction 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multi-robot construction quality control often suffers from limited adaptability, expensive quality-aware scheduling evaluation, and unstable cooperative execution. This paper proposes an Improved-GA-MADDPG- LLM framework that integrates

---

### [110] Valhalla: A Layered Knowledge-State and Service-Governance Framework for Long-Term Scientific Knowledge Work

**链接**: https://arxiv.org/abs/2608.15193
**作者**: Yuyang Zheng, Nan Li, Wenxia Deng, Lige Yan, Xiang Li, Si Chen
**来源**: q-bio.NC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents are increasingly adopted in scientific research, external knowledge bases, knowledge graphs, and long-term memory have improved information retrieval and task continuity. However, most structured knowledge systems remain node-centric, representing files, concepts, results, and judgments as nodes and relations in a graph. While suitable for personal knowledge management, such structures often depend on individual organizational practices, limiting knowledge sharing, integration, and reorganization across users. This paper presents Valhalla, a layered knowledge-state and service-governance framework for long-term scientific knowledge work. Valhalla replaces flat graphs with layered encapsulation and stable semantic boundaries through a five-layer File-Resource-Entity-Relationship-Graph (FREG) model. File and Resource preserve source identity and provenance, Entity represents knowledge objects, Relationship captures semantic judgments, and Graph provid

---

### [111] P2Skill: Privacy Preserving Skill Distillation for Cloud-Local LLM Inference Systems

**链接**: https://arxiv.org/abs/2608.14094
**作者**: Myunghoon Ryu, Geunpyo Park, Sungjoon Lee, XinYu Piao, Jong-Kook Kim
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cloud-local LLM inference systems have the potential to use the reasoning capability of large cloud models while protecting sensitive user data on personal devices. Cloud-bound requests must exclude personally identifiable information (PII) to prevent external data leakage. Existing privacy-preserving methods rely on prompt perturbation, entity masking, or model fine-tuning, but these approaches may distort contextual semantics or require additional training. This paper proposes P2Skill, a prompt-based skill distillation method in which a local small language model (SLM) autonomously performs decomposition, PII-aware routing, paraphrasing, and reconstruction by following the skill prompts. Skills are iteratively refined from execution failures by a cloud LLM, enabling the local SLM to generalize beyond memorized PII patterns, and therefore P2Skill requires no privacy-specific fine-tuning or learned auxiliary detectors. Evaluation on a four-domain benchmark shows that P2Skill achieves $

---

### [112] PertMind: Eliciting Emergent Biological Reasoning in LLM via Reinforcement Learning on Cellular Perturbation Data

**链接**: https://arxiv.org/abs/2608.16419
**作者**: Zhenchao Tang, Xiaogang Xu, Tianxu Lv, Jiahui Guan, Jiale Zhou, Haohuai He 等 (10 人)
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can describe mechanisms, yet scalable post-training still depends on costly, manually curated biological reasoning traces. Here we show that cellular perturbation atlases can instead become reinforcement-learning environments, where measured gene responses provide computable rewards for biological reasoning. We introduce PertMind, which combines trusted-trajectory supervised initialization with gene-, pathway-, and format-level reinforcement signals. Trained only on forward perturbation-response prediction, PertMind improved response inference in unseen cellular contexts while retaining general language capabilities. It also transferred without task-specific post-training to reverse perturbation identification, double-perturbation reasoning, phenotypic-screen prioritization, and biological-process interpretation. PertMind further generated biological profiles that supported competitive gene, cell, and donor representations across multiscale downstream tasks. These

---

### [113] DA-RAC: Distance-Aware Calibration of LLM Judges for Trustworthy AI Auditing

**链接**: https://arxiv.org/abs/2608.14950
**作者**: Cheng Wu, Vishal Anand, Jaya Krishna Mandivarapu, Xiya Liu, Rui Zhuang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI systems are increasingly producing real-world artifacts, however their efficacy and validity are often evaluated via context-free LLM-scoring. These judges can be miscalibrated by irrelevant in-context reference examples, creating false confidence and allowing low-quality or harmful outputs to pass evaluation. We study this failure mode as context-induced miscalibration and introduce DA-RAC, a distance-aware reference-anchored calibration method for LLM judges. DA-RAC retrieves semantically and structurally similar labeled anchors for each judgement scenario, weights them by distance, and exposes neighborhood difficulty as a calibration and triage signal. On multi-run LLM-judge evaluation benchmarks, it improves calibration and reduces false-pass risk relative to zero-shot, chain-of-thought evaluation, and static-anchor baselines. Mechanistic analysis shows that judge scores vary systematically with anchor distance, while static references can induce misleading decision b

---

### [114] SynAct: A Reasoning-Acting Large Language Model Agent for Adaptive Synthesis Optimization

**链接**: https://arxiv.org/abs/2608.12751
**作者**: Fangzhou Liu, Peiyi Han, Jiawei Liu, Yuan Pu, Zhuolun He, Rongliang Fu 等 (8 人)
**来源**: cs.AR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Geometric Filtering of LLM-Generated Samples for Few-Shot Text Classification

**链接**: https://arxiv.org/abs/2608.13866
**作者**: Benjam\'in Schindler and Gonzalo A. Ruz
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate synthetic training data for text classification, but the quality of generated samples is heterogeneous: some fall in correct class regions of the embedding space while others land in peripheral or cross-class zones. We propose a geometric filtering framework that evaluates each LLM-generated sample by its Euclidean distance to real class examples in a sentence embedding space, selecting only geometrically consistent candidates. A soft weighting mechanism transforms filter scores into sample weights for classifier training. Evaluated across 13 datasets, 5 classifiers, 10 augmentation methods, and over 6,700 configurations, our method achieves +2.61 percentage points (pp) over SMOTE ($p<0.0001$, Cohen's $d=0.95$, 88.9% win rate). The approach generalizes to named entity recognition (+9.26pp, 100% win rate) without filter modification, and is robust across 5 LLMs from 4 providers. A key finding is that the simplest distance-based filter consistent

---

### [116] Clearing the Fog: Towards Installing and Refining Proactive Exploration Capabilities in LLM Agents

**链接**: https://arxiv.org/abs/2608.14339
**作者**: Zhizhao Guan, Chen Huang, Ziming Liu, Hongru Liang, Wenqiang Lei, See-Kiong Ng 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study proactive exploration in LLM agents, i.e., the ability to explore an environment to acquire information that improves future decision-making. In this regard, we first identify two fundamental bottlenecks that hinder this capability and then propose \ours, a novel method designed to instill and refine proactive exploration. Specifically, \ours\ consists of two components: (1) Exploratory Data Construction, which synthesizes exploration-rich trajectories to mitigate the hindsight bias of standard demonstrations; and (2) RL Optimization with Contrastive Signal Guidance, which leverages contrastive trajectory pairs to distinguish productive exploration from redundant wandering. Extensive experiments demonstrate the effectiveness of \ours\ and provide insights into the characteristics of proactive exploration. Our code is available at: https://github.com/GuanZhizhao/SAFARI.

---

### [117] Single-Round Vector RAG vs an LLM-Compiled Wiki: A Preregistered Comparison on a Small Multi-Domain Research Corpus

**链接**: https://arxiv.org/abs/2605.18490
**作者**: Theodore O. Cochran
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] When Lexical Change Misleads: Rethinking Dynamic Topic Model Evaluation with Traditional and LLM-Based Metrics

**链接**: https://arxiv.org/abs/2608.13835
**作者**: Charu Karakkaparambil James
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic topic models capture evolving word distributions, but traditional coherence metrics may fail when vocabulary changes while semantic meaning persists. We evaluate 120 topics from CoNTM and DLDA across NYT, DBLP, and arXiv, using three human annotators and Low, Medium, and High lexical-change categories. Traditional temporal coherence shows highly variable agreement with human judgments ($\rho$=-0.256 to 0.614). In contrast, LLM-based semantic similarity agrees strongly with human semantic judgments for CoNTM on NYT ($\rho$=0.609), DBLP ($\rho$=0.721), and arXiv ($\rho$=0.502), but is less consistent for DLDA. Lexical-change stratification reveals variation hidden by aggregate evaluation. We therefore advocate lexical-change-aware evaluation, jointly reporting traditional coherence and LLM-based semantic measures as complementary rather than interchangeable signals.

---

### [119] Kalypso: Relational LLM Serving

**链接**: https://arxiv.org/abs/2607.23815
**作者**: Hojae Son, Md Ashraful Islam, Huy Gia Cao, Hui Guan, Marco Serafini
**来源**: cs.DB cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] LLMs as a Jury: Cross-Model Consensus Can Outperform Process Reward Models for LLM Reasoning

**链接**: https://arxiv.org/abs/2607.10139
**作者**: Ning Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] When Do LLMs Apply the Wrong Law? Diagnosing LLM Failures in Temporal Legal Reasoning

**链接**: https://arxiv.org/abs/2608.14610
**作者**: Yiqian Huang, Shuyuan Zheng, Qianying Liu, Shaowen Peng, Yuntao Kong, Kotaro Funakoshi 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Legal reasoning tasks such as legal judgment prediction (LJP) require identifying the temporally correct version of the law governing a case -- a capability we term temporal applicable-law determination. However, whether large language models (LLMs) can reliably perform this task remains unexplored. In this paper, we construct a benchmark to evaluate LLMs on temporal applicable-law determination, and systematically investigate why they fail at temporal legal reasoning. Our experiments reveal four key findings. First, LLMs exhibit a strong bias toward applying the most recently enacted law, regardless of when the legally relevant facts occurred. Second, this bias does not stem from an inability to understand that laws have temporal scope, nor from a lack of knowledge about historical statutes. Third, we provide behavioral evidence that reinforcement-learning-shaped explicit reasoning may be a key mechanism: while improving general reasoning ability, it reduces the diversity of reasoning

---

### [122] Beyond Access: Guided LLM Scaffolding for Independent Learning in Undergraduate Statistics

**链接**: https://arxiv.org/abs/2606.01375
**作者**: Mohammad Amanlou, Yasaman Amou-Jafari, Fereshte Bagheri, Fatemeh Boloukazari, Mehrad Liviyan, Elahe Khodaverdi Nadrabadi 等 (8 人)
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] T-LLM Compiler: Trusted LLM-based Code Optimization and Verification Framework

**链接**: https://arxiv.org/abs/2608.14953
**作者**: Zahra Fazel, Sunanda Gamage, Shayan Shirahmad Gale Bagi, Amir H. Ashouri, Tomasz S. Czajkowski, Bryan Chan 等 (8 人)
**来源**: cs.AI cs.CL cs.LG cs.PF cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Large Language Models (LLMs) have opened opportunities to apply high-level code transformations to the field of code optimization, and it has since emerged as one of the most fundamental tasks for LLMs to perform; however, at present, LLMs struggle to apply wide-ranging code optimization tasks due to both the complexity of the code and the inability to independently verify the correctness of the transformations. In this paper, we present the Trusted LLM (T-LLM) Compiler, which proposes an advancement in compiler technology through a collaborative effort involving high-level LLM code transformations, traditional compilers, and verification tools. Experimental results reveal that it can significantly improve code correctness when tested on a set of PolyBench/C benchmarks. Our approach facilitates iterative code optimization efforts with verification strategies that enable corrective actions. Through this approach, T-LLM Compiler achieves code optimization accuracy of u

---

### [124] LLM-Advisor: An LLM Advisor for Cost-efficient Path Planning across Multiple Terrains

**链接**: https://arxiv.org/abs/2503.01236
**作者**: Ling Xiao and Toshihiko Yamasaki
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] Cloud-ScPO: Hidden-State Geometry for Semi-Supervised Preference Optimization in LLM Reasoning

**链接**: https://arxiv.org/abs/2608.01014
**作者**: Yuzhou Liu, Xiyang Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] AudioTQ: A Data-Oblivious 6-Bit CPU Audio Codec via Randomized Hadamard Rotation and Lloyd-Max Quantization

**链接**: https://arxiv.org/abs/2608.15369
**作者**: Sahil Gangurde
**来源**: cs.SD cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lossy audio compression algorithms traditionally rely on psychoacoustic modeling and frequency-domain representations (e.g., MP3, AAC, and Opus) to discard information that is imperceptible to the human auditory system. While highly effective, these approaches are computationally complex and domain-specific. In this paper, we present the design and mathematical formulation of AudioTQ, a data-oblivious lossy audio codec that operates directly in the time domain. Inspired by Large Language Model (LLM) weight quantization techniques (specifically the TurboQuant framework), AudioTQ uniformizes volatile time-domain amplitudes into a predictable standard normal distribution using an orthonormal, randomized Fast Walsh-Hadamard Transform (FWHT) rotation. This enables coordinate-wise scalar quantization using an offline-trained, MSE-optimal 6-bit Lloyd-Max quantizer, augmented by a 1-bit Quantized Joint Least-Squares (QJL) residual correction layer. The resulting 7-bit virtual indices are packe

---

### [127] Admission Without Answers: Label-Free Certification and Experience Learning for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2608.15565
**作者**: Junbo Jacob Lian, Huiling Chen, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experience-learning agents for optimization modeling improve by storing verified skills, but existing learners admit knowledge by checking against known answers, which real ticket streams do not provide. The natural label-free alternatives are unreliable: on a 300-problem label-blind stream, admitting every executable model poisons roughly one admission in four, while single-instance agreement accepts models that match at one value but differ elsewhere. We propose AdmitOR, an admission gate built on calibrated external behavioral evidence. Candidates from three model families, prompting strategies, and solver stacks are run on instances resampled from an extracted parameter domain; agreement across the resulting value-function traces is summarized by a cross-family clique, and a calibrated threshold returns accept, abstain, or escalate. The preregistered false-discovery criterion holds on calibration data but not on the wild stream. We report this negative result in full and trace most

---

### [128] ReLoop: Structured Modeling and Behavioral Verification for Reliable LLM-Based Optimization

**链接**: https://arxiv.org/abs/2602.15983
**作者**: Junbo Jacob Lian, Yujun Sun, Huiling Chen, Chaoyu Zhang, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.SE cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] Prompting is not enough: supervised baselines and leakage control for measuring shared decision-making with LLMs in pediatric encounters

**链接**: https://arxiv.org/abs/2608.14792
**作者**: Bernardo Modenesi, Jody Lin, Kimberly Kaphingst, Angela Zhu, Maya Wheeler, Peilu Zhang 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objectives: To determine whether zero-shot prompting of a large language model (LLM) is sufficient to detect shared decision-making (SDM) behaviors in real clinical encounters, and whether supervised learning adds value under patient-grouped, nested evaluation. Methods: We analyzed 21 audio-recorded outpatient surgical decision encounters (19 unique patients; 7,566 utterance segments; ~6.1 hours) between families of children with multiple long-term conditions and their surgical providers. Trained coders labeled segments for 12 SDM behaviors (human-human macro Cohen's kappa = 0.695). We compared a zero-shot local LLM (Qwen 2.5 32B), a supervised classifier over frozen sentence embeddings, and their logistic stack, under patient-grouped outer folds with inner cross-fitted thresholds and patient-resampled confidence intervals. Results: The zero-shot LLM reached macro kappa = 0.139 (95% CI 0.111-0.164). The supervised classifier reached kappa = 0.227 (0.186-0.262), a paired improvement of 

---

### [130] GRASP: Gated Regression-Aware Skill Proposer for Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2605.29668
**作者**: Johannes Moll, Jean-Philippe Corbeil, Jiazhen Pan, Martin Hadamitzky, Daniel Rueckert, Lisa Adams 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Musical Mirrors: The LLM as Sounding Board in Songwriting

**链接**: https://arxiv.org/abs/2608.13944
**作者**: Xiao Xiao
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] When Stories Evolve: Benchmarking LLM Storytelling Across Agent Architectures in Open-Ended World Simulations

**链接**: https://arxiv.org/abs/2608.15654
**作者**: Yuqi Chen, Sixuan Li, Yunfeng Cai, Xueai Li, Ka Man Yan, Ying Li
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can write fluent stories, but open-ended storytelling requires more than local fluency. In evolving world simulations and AI-native games, models must preserve facts, relationships, causal dependencies, and character states as the world changes. We introduce WSE-bench, a process benchmark that separately evaluates sustained generation, canonical coherence, and meaningful development in dynamic LLM storytelling. Generation Coverage records the proportion of planned narrative steps produced; Consistency tracks when canon breaks; and Richness measures how meaningfully branching, player-shaped trajectories develop. Across frontier models, Consistency and Richness do not form a smooth trade-off: their empirical Pareto frontier is non-concave, with several non-dominated intermediate configurations that no positive linear weighting can select. Added structure can enrich trajectories, but it does not uniformly improve coherence and may shorten them. Model scale chiefly im

---

### [133] LLM-Based Hierarchical Coordinated Control with Continuation-Aware Policy Learning

**链接**: https://arxiv.org/abs/2608.15041
**作者**: Changhong He, Jinda Gao, Xinkuan Liu, Le Zhang, Xizi Luo, Yu Mei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coordinating multiple interacting units in complex engineering systems is challenging when system interactions are difficult to model, operational information is heterogeneous, and low-level actions must satisfy strict constraints. We propose an LLM-based hierarchical framework in which the LLM coordinates interacting units based on heterogeneous operational context, while task-specific controllers or optimizers generate executable and constraint-aware actions. We further introduce Continuation-Aware GRPO to capture the consequences of coordination decisions over subsequent control intervals. Rather than judging a decision only by its immediate outcome, the method also evaluates how the system evolves afterward under the current policy. We validate the framework on multi-ramp traffic control and virtual power plant (VPP) energy management, using simplified system models for training and more realistic simulators for evaluation. Across both tasks, the proposed method consistently outper

---

### [134] Simulation-Aware In-Context Policy Improvement for LLM-Aided Analog Layout Refinement

**链接**: https://arxiv.org/abs/2608.13767
**作者**: Bingyang Liu, Ziming Wei, Xiaohan Gao, and David Z. Pan
**来源**: cs.AI cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog IC layout design remains a labor-intensive iterative process dominated by simulation-driven refinement. Although end-to-end layout generators accelerate initial placement and routing, they still require experts to manually tune layout optimization parameters with repeated post-layout simulations for stringent design specifications. While Bayesian Optimization (BO) is widely adopted for parameter tuning in analog IC design, at the layout level it typically requires hundreds to thousands of evaluations, each involving costly parasitic extraction and post-layout simulation, which makes it impractical. Recently, Large Language Models (LLMs) have demonstrated potential in improving the sample efficiency of such simulation-driven tuning. However, their restricted access to geometric layout context and design-specific heuristics limits their ability to manipulate the layout optimization process. In this paper, we propose a simulation-aware LLM multi-agent framework that performs in-con

---

### [135] Auxiliary uncertainty signals for LLM-assisted systematic review screening: a benchmark across eight Cohen drug-class reviews

**链接**: https://arxiv.org/abs/2608.14551
**作者**: Arya Rahgozar and Pouria Mortezaagha
**来源**: cs.CL cs.DL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for title-abstract screening in systematic reviews, but their decisions lack calibrated uncertainty. We show that an auxiliary BERT+GCN classifier supplies a structured uncertainty signal that improves LLM screening efficiency, and we identify the prompt-delivery strategy that maximises the benefit-to-cost ratio. We evaluate five LLM prompt-delivery conditions on eight drug-class datasets from the Cohen (2006) benchmark using 3 seeds x 5-fold stratified cross-validation (600 fold-level results). A BERT+GCN model trained per fold classifies each test paper as INCLUDE, EXCLUDE, or MAYBE via two spectral tests (algebraic radical and categorical paradox). Conditions vary information content (none / label / full scores), selectivity (all papers vs. MAYBE only), and timing (proactive vs. reactive two-pass). A cross-model pilot against gpt-4.1-mini on three datasets tests cross-generation transfer. Three findings: (i) Full-context delivery yi

---

### [136] MistyPilot: Enabling Social-Robot Control through Multi-Agent LLM Skill Orchestration

**链接**: https://arxiv.org/abs/2608.15549
**作者**: Xiao Wang, Lu Dong, Ifeoma Nwogu, Srirangaraj Setlur, Venu Govindaraju
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programming small social robots from natural-language instructions requires more than invoking isolated APIs. Interactive tasks combine reactive physical behaviors with stateful social behaviors, while existing interfaces often require developers to manually compose APIs into skills, configure their parameters, bind sensor events to skills, and manage task states at runtime. We present MistyPilot, a multi-agent LLM framework that interprets high-level natural-language instructions and orchestrates the corresponding skills on the Misty social robot. A Task Router dispatches each instruction to one of two specialized agents: a Physically Interactive Agent for sensor-triggered robot control and direct skill invocation, and a Social Interaction Agent for dialogue-oriented task-state management and context-dependent multimodal response generation. To improve efficiency, the Social Interaction Agent reuses previously generated results when applicable and invokes full generation otherwise. We

---

### [137] When Personal Memory Has No Single Answer: Evaluating LLM Agents under Irreducible Conflict

**链接**: https://arxiv.org/abs/2608.13921
**作者**: Lu Yang, Shusheng Xu, Zhuoran Li, Tongkai Yang, and Longbo Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly maintain personal memory across sessions, but it can conflict. Preferences depend on context, behavior evolves, and sources can conflict. When a query lacks context, time, or source authority to interpret conflict, treating one memory as definitive converts unresolved conflict into an unjustified, overconfident action. Existing benchmarks recover one answer from conflicting evidence, overlooking whether agents recognize underdetermination, preserve alternatives, seek missing information, and choose appropriate actions. We introduce \underline{T}esting \underline{A}gents' \underline{N}avigation of \underline{G}enuine, \underline{L}atent, and \underline{E}ntangled Memory Conflicts (\textsc{TANGLE}), a benchmark for genuinely unresolvable memory conflicts. It comprises 541 instances across 40 personas and three types: Context-Partitioned Conflict (CPC), Behavior-Oscillation Conflict (BOC), and Source-Contradiction Conflict (SCC). We evaluate two tracks---an oracle 

---

### [138] Divergent-Convergent Reasoning: Scaling Test-Time Compute through Structured Solution Synthesis

**链接**: https://arxiv.org/abs/2608.15303
**作者**: Bo Wen, Yuhao Chen, Erhan Bilal, Carla Agurto Rios, Chen Wang, Junchen Jiang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time compute can substantially improve Large Language Model (LLM) reasoning performance, yet how and when additional compute helps remains poorly understood. We study Divergent-Convergent Reasoning (DCR), a simple two-phase primitive consisting of an exploration phase that generates multiple candidate solutions followed by a convergent reconciliation phase. We present three core results. First, we show that even a single reconciliation step can reliably amplify correct minority reports: across datasets, DCR often recovers the correct answer when correct exploration outputs are in the minority, a regime where majority voting fails. Second, we introduce recursive DCR, an autoregressive reconciliation system that iteratively analyzes disagreements and allocates additional test-time compute. Recursive DCR achieves higher accuracy than fixed-compute baselines-reaching 93.3% on AIME 2024 and 92.0% on AIME 2025-while using roughly 27% less compute on average, demonstrating that attentive

---

### [139] Beyond the pale: Assessing prevalence and contents of extremist speech in LLM training data

**链接**: https://arxiv.org/abs/2608.14813
**作者**: Dmitry Nikolaev, Ashley A. Mattheis
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite a strong interest on the part of the research community in the topic of trustworthy and safe AI, the composition of the text corpora that large language models (LLMs) encounter in pre- and post-training has not yet drawn much attention. In this work, we address the question of whether LLMs are exposed to unfiltered, uncontextualised extremist speech. Using several definitions of extremist speech, stemming from official documents and research literature, and an extraction pipeline combining automated text processing with expert verification, we provide a lower bound on the prevalence of extremist documents in Dolma, an open training corpus underpinning the OLMo series of models. We show that Dolma is likely to include hundreds of thousands of documents containing extremist content and hate speech of several types, including direct calls for violence, and discuss the implications of this for data curation and model pre-training.

---

### [140] Train Yourself as an LLM: Exploring Effects of AI Literacy on Persuasion via Role-playing LLM Training

**链接**: https://arxiv.org/abs/2604.02637
**作者**: Qihui Fan, Min Ge, Chenyan Jia, Weiyan Shi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] PLSQLBench: Benchmarking LLM Systems for Executable Procedural Database Programming

**链接**: https://arxiv.org/abs/2608.15931
**作者**: Marianne Menglin Liu, Leonid Boytsov, Daniel W. Peterson, Pramuditha Perera, Rongguang Wang, Sai Ashish Somayajula 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present PLSQLBench, to our knowledge the first benchmark for evaluating whether LLMs can write executable PL/SQL programs, with correctness measured through execution-based tests. Existing LLM evaluations largely target general-purpose code generation or declarative text-to-SQL, leaving procedural database programming underexplored. PLSQLBench contains 2,865 instances: 2,594 single-turn tasks and 271 multi-turn conversations spanning 978 turns. The benchmark combines complex schema-grounded tasks over enterprise-style Spider 2 databases, simpler schema-grounded tasks derived from Spider, and MBPP-derived procedural problems, covering varying levels of database grounding and procedural complexity. Experiments with eight LLMs reveal recurring difficulties in schema grounding, PL/SQL dialect fidelity, procedural control flow, exception handling, and cross-turn consistency. Tool-augmented LLM agents improve performance on several schema-grounded evaluations, although substantial gaps re

---

### [142] A Human-LLM Teaming Framework for Privacy Risk Analysis: An Illustration with CBDC-Based Welfare Schemes

**链接**: https://arxiv.org/abs/2608.16461
**作者**: Sourya Joyee De and Abdessamad Imine
**来源**: cs.ET cs.AI cs.CE cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Central Bank Digital Currency (CBDC)-based welfare schemes may be potentially privacy invasive as they process significant volumes of beneficiary personal data and lead to privacy harms such as surveillance, discrimination and stigmatization. Such welfare delivery schemes involve complex digital ecosystems and large number of stakeholders. Consequently, to examine their privacy risks, privacy risk assessments require extensive information gathering and synthesis, complex reasoning, scenario explorations, contextual evaluation and human judgement. Thus, they present ideal scenarios for human-LLM teaming, where effective integration of complementary human and LLM capabilities can yield an outcome far superior to either human-only or LLM-only assessments. In this paper, we propose a first human-LLM teaming framework for the systematic privacy risk analysis methodology called PRIAM. The framework specifies an iterative collaborative process in which the LLM processes large-scale documentar

---

### [143] A Scalable Pipeline for LLM-Teacher Distillation Labeling: Work-Stealing Job Scheduling and Memory-Aware GPU Concurrency

**链接**: https://arxiv.org/abs/2608.15975
**作者**: Ravi Satya Durga Prasad Yenugula
**来源**: cs.DC cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Labeling large text corpora with LLM teachers has become a practical route to training data at scale. At millions of items, hand-labeling every batch is not feasible, and two questions dominate: what label quality a teacher buys per dollar, and how to keep a fleet of GPU workers busy under skewed, failure-prone workloads. We present a simple, reproducible pipeline that addresses both. First, a work-stealing ring pool: each worker owns a queue, drains it first, and then steals from ring successors, with exactly-once task claims via atomic conditional writes and crash tolerance via stale-claim sweeping. The claim protocol requires only a compare-and-set primitive from its storage layer; we implement it on a single SQLite file, which makes the reference implementation dependency-free and the experiments reproducible on one machine. Second, a memory-aware concurrency rule that sizes per-node parallelism by how many model copies fit on the GPU, so the same code runs safely across device siz

---

### [144] HyperSkill: Self-Evolving LLM Agents via Hypergraph-Structured Skill Memory

**链接**: https://arxiv.org/abs/2608.16114
**作者**: Ruiyao Xu, Tiankai Yang, Wei-Chieh Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agentic tasks grow in complexity, LLM agents increasingly rely on experiential memory to reuse procedural knowledge across tasks. Effective memory design must jointly address what to store, how memory is structured and retrieved, and how memory evolves. Existing systems tackle each only partially: they store trajectories, insights, or workflows as isolated entries, discarding compositional relationships among subtasks and reusable skills; retrieve by flat embedding similarity that ignores relational signals; and maintain memory without leveraging its relational structure. We propose HyperSkill, a hypergraph-based memory framework that jointly improves all three. HyperSkill represents memory as a hypergraph with two node types, subtask steps and reusable skills, where each hyperedge links the subtasks and skills from a single trajectory. Dual-path retrieval queries both subtask and trajectory levels, ranking skills by co-occurrence across retrieved trajectories. Periodic structure-in

---

### [145] Not All Tokens Are Equal: Inflation-Aware Routing for Agentic LLM Systems

**链接**: https://arxiv.org/abs/2608.13571
**作者**: Heming Fu, Shan Lin, Qianqian Xie, Guojun Xiong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a language model fails to answer a query on the first attempt, an agentic system retries, consuming additional tokens each time. This retry overhead creates a gap between what a model's per-token price implies and what a full workflow actually costs. We call this gap \emph{token inflation} and define it as the ratio of true workflow cost to single-call cost. Systems like FrugalGPT route based on the latter, which can underestimate real cost by more than $2\times$ on difficult tasks. We address this with InflationAgent, a four-stage router that (1) measures token inflation systematically across model tiers and task types, finding inflation as high as $4.25\times$ for a 7B model on multi-hop question answering; (2) introduces CoT Branching Entropy (CBE), a pre-execution difficulty signal computed entirely from local inference, which predicts high inflation with AUROC 0.887; and (3) selects models by maximizing a Semantic Exchange Rate (SER) that divides expected accuracy by predicte

---

### [146] The Fools are Certain; the Wise are Doubtful: Exploring LLM Confidence in Code Completion

**链接**: https://arxiv.org/abs/2508.16131
**作者**: Zoe Kotti and Konstantina Dritsa and Diomidis Spinellis and Panos Louridas
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [147] From Prediction to Intervention: Personalized Meal-Level Glucose Regulation via an LLM Agent

**链接**: https://arxiv.org/abs/2608.13581
**作者**: Mingyu Huang, Weiqing Min, Ying Jin, Yilin Wang, Shuqiang Jiang
**来源**: cs.HC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized glucose regulation remains a central yet unresolved challenge in precision nutrition, as postprandial glucose response varies substantially across individuals. Existing approaches based on glycemic indices fail to adequately account for such heterogeneity and lack the mechanism to dynamically adjust meals based on personal physiological feedback. In this context, recent advances in LLM-based agents offer a promising direction, as they enable context-aware reasoning and iterative refinement. Inspired by this, we propose a physio-feedback agentic loop, a unified system that integrates individualized absorption modeling with dietary intervention to regulate glucose response. Specifically, we develop a Physiology-Aware Glucose Predictor to model individualized absorption dynamics through a learnable Temporal Physiological Absorption Decay Module. We then construct a Prediction-Driven Two-Stage Meal Optimization Agent that iteratively refines real-world meals using predicted ou

---

### [148] Theory-Grounded Evaluation Exposes the Authorship Gap in LLM Personalization

**链接**: https://arxiv.org/abs/2604.26460
**作者**: Yash Ganpat Sawant
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] PDDLCoder: Agentic PDDL Generation for LLM-Assisted Symbolic Planning

**链接**: https://arxiv.org/abs/2608.16637
**作者**: Veit Laule, Jiangtao Shuai, Manfred Hauswirth, Sonja Schimmler
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs remain unreliable for long-horizon planning, often generating logically inconsistent or non-applicable plans. Recent hybrid methods instead translate natural language into the Planning Domain Definition Language (PDDL), allowing symbolic planners to produce verifiable plans. However, existing methods frequently rely on rigid generation pipelines, a partial PDDL definition, or human feedback. Furthermore, their evaluation is hindered by the lack of standardized benchmarks with automated verification. To address these limitations, we present PDDLCoder, an agentic framework for PDDL generation from natural language that iteratively generates, analyzes, and refines planning specifications. We further introduce NL-pddlgym, a benchmark dataset comprising 711 planning problems across 23 domains with executable gym environments for the automated verification of plan applicability. Experiments on the NL-pddlgym test set containing 106 problems across 4 held-out domains show that PDDLCoder 

---

### [150] TimeSage-EV: A Live Benchmark for Agentic Time Series Analysis in Evolving Environments

**链接**: https://arxiv.org/abs/2608.14270
**作者**: Qingren Yao, Yaxuan Kong, Yuqi Nie, Yichen Li, Stefan Zohren, Anna Vettoruzzo 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series analysis in high-stakes domains relies on recurring data releases, where new observations can alter the evidence base and the validity of later conclusions. Existing time series QA benchmarks mostly rely on fixed snapshots, leaving temporal validity and cutoff-aware evidence use unevaluated. We introduce TimeSage-EV, a live benchmark for agentic time series analysis in evolving environments. It tracks 60 real institutional scenarios across 6 domains, comprising 1,485 scenario-period QA pairs from Feb 2023 to May 2026 and spanning monthly, weekly, daily, and irregular release cadences. At each period, large language model (LLM) agents receive time series data and source reports, while the withheld target release provides ground truth. TimeSage-EV evaluates state identification, data summarization, and outlook reasoning. Experiments with frontier LLM agents and TimeSage-1.0, a novel self-evolving agent with a reusable analytical skill library, reveal significant performance g

---

### [151] Adaptive Stopping for Multi-Turn LLM Reasoning

**链接**: https://arxiv.org/abs/2604.01413
**作者**: Xiaofan Zhou, Huy Nguyen, Bo Yu, Chenxi Liu, Lu Cheng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [152] E2LLM: Towards Efficient LLM Serving in Heterogeneous Edge/Fog Environments

**链接**: https://arxiv.org/abs/2606.03770
**作者**: Truong-Thanh Le, Amir Taherkordi, Hoang-Loc La, Frank Eliassen, Phuong Hoai Ha and Peiyuan Guan
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] The More Popular, The Harder to Forget: Adaptive Popularity for LLM Unlearning

**链接**: https://arxiv.org/abs/2608.14229
**作者**: Anna Borisiuk, Andrey Savchenko, Alexander Panchenko, Elena Tutubalina
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Popular facts are memorised more deeply during pretraining and resist removal longer than rare ones, yet existing LLM unlearning methods apply uniform gradient pressure regardless of training-data frequency. We propose the AdaPop (Adaptive Popularity) method, which combines local token confidence with a per-fact popularity-dependent exponent derived from an external proxy (e.g., Wikidata sitelinks, LLM-as-Judge), and automates the forget-retain balance via a dual-ascent controller that adjusts the retain penalty each epoch. Across three model families and two benchmarks, AdaPop leaks ~5x less forgotten content than competing methods under paraphrased queries and ~1.6x less under adversarial reformulations. We support our analysis with internal metrics: under our method, forget-set hidden states move further from the pre-unlearning model's states than under other methods, while retain-set representations remain close.

---

### [154] The Integer Alibi: Localizing Cross-Kernel Divergence in INT8-Quantized LLM Inference

**链接**: https://arxiv.org/abs/2608.13756
**作者**: Teng-Ruei Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [155] Analytical Provisioning for Attention-FFN Disaggregated LLM Serving under Stochastic Workloads

**链接**: https://arxiv.org/abs/2601.21351
**作者**: Chendong Song, Meixuan Wang, Hang Zhou, Hong Liang, Yuan Lyu, Zixi Chen 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] From LLM Inference to Agentic Workloads: Characterization and Implications for Serving Systems

**链接**: https://arxiv.org/abs/2608.15127
**作者**: Chaokun Chang, Yukun Zhou, Kaihua Fu, Dakai An, Tianyu Feng, Hanfeng Lu 等 (10 人)
**来源**: cs.OS cs.AI cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic applications are shifting AI serving from isolated model inference to long-running workloads in which LLMs coordinate tools, environments, and persistent state. However, the system behavior of these workloads---where latency, cost, and bottlenecks arise---remains poorly characterized, leaving serving systems to rely on assumptions built for conventional inference. We present AgentSysBench, a benchmark suite and measurement toolkit with ten representative agentic applications and unified systems-level instrumentation. Across controlled deployments and production traces, we identify six properties that distinguish agentic workloads from conventional LLM serving: (1) execution is heavyweight and stateful, with non-LLM components dominating latency in 5 of 10 applications and sandbox working-set memory peaking at 28 GB per session; (2) applications compose components with heterogeneous resource affinity---GPU-bound inference, memory-bound retrieval, CPU-bound sandboxes---whose task

---

### [157] Value Leakage: An LLM's Answers Are Silently Shaped by Its Own Values

**链接**: https://arxiv.org/abs/2607.14345
**作者**: Jan Betley, Johannes Treutlein, Jan Dubi\'nski, Harry Mayne, Karol Ga{\l}\k{a}zka, Niels Warncke 等 (8 人)
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] Mitigating Rubric Interference in LLM Judges via On-Policy Self-Distillation

**链接**: https://arxiv.org/abs/2608.14684
**作者**: Dingyao Yu, Tong Zhang, Yutao Mou, Yunxiao Zhang, Wei Ye, Shikun Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges increasingly evaluate responses against fine-grained rubric checklists. When a sample requires multiple rubrics, current methods typically assess each in a separate inference call. Evaluating all rubrics in a single pass is a natural alternative with greater efficiency, but we find that it introduces rubric interference: the verdict on one rubric shifts depending on which other rubrics are co-present. In a preliminary study, only one-third of samples receive fully consistent verdicts when evaluated under rubric sets of varying composition. We develop a measurement framework that probes interference through four controlled operations: rubric set expansion, subsetting, reordering, and noise injection. To mitigate interference without external supervision, we propose Self-Anchored Rubric Alignment (SARA). SARA uses a model's own single-rubric judgments as stable anchors and aligns multi-rubric reasoning with these anchors through on-policy self-distillation. We validate SARA on

---

### [159] LatentSkill: From In-Context Textual Skills to In-Weight Latent Skills for LLM Agents

**链接**: https://arxiv.org/abs/2606.06087
**作者**: Aofan Yu, Chenyu Zhou, Tianyi Xu, Zihan Guo, Rong Shan, Zhihui Fu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] EgoGazeLite: On-Device Egocentric Gaze Prediction for Token-Efficient Multimodal LLM Video Input

**链接**: https://arxiv.org/abs/2608.15614
**作者**: Matteo Stoiber, Niels Buus Lassen
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The use of multimodal LLMs (MLLMs) for egocentric video understanding with wearable devices is constrained by the token budget. Memory and compute cost scale with the number of visual tokens, and high-resolution video quickly becomes expensive to transmit and process at scale. Prior work (GazeLLM) addresses this by cropping the video around the camera wearer's gaze. This reduces the number of visual tokens by about tenfold while maintaining or improving the quality of full-resolution descriptions. However, this compression strategy depends on dedicated eye-tracking hardware, which is unavailable on consumer smart glasses. Building a software-only substitute poses a joint constraint: the predictor must be accurate enough to preserve downstream description quality, yet light enough to run on-device, within the power and compute budget of a smartphone. We address this with EgoGazeLite, a lightweight dual-process gaze predictor for egocentric video. Across two MLLMs, three automated metric

---

### [161] When Do Anchor-Based Pointwise LLM Rerankers Help? Retriever Quality, Statistical Scope, and Anchor Design

**链接**: https://arxiv.org/abs/2608.10528
**作者**: Utshab Kumar Ghosh, Shubham Chatterjee
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] Effect of Abstractions and Prompting Strategies on LLM-Guided High-Performance Optimizations

**链接**: https://arxiv.org/abs/2608.08085
**作者**: Ji\v{r}\'i Klepl, Maty\'a\v{s} Brabec, Martin Kruli\v{s}
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [163] Would this change your answer? Evaluating Explanations of LLM Behavior In The Wild with Counterfactual Experiments

**链接**: https://arxiv.org/abs/2608.16747
**作者**: Adam Karvonen, Euan Ong, Subhash Kantamneni, Samuel Marks
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many areas of AI research, such as language model interpretability and chain of thought faithfulness, seek to explain model behaviors. But what constitutes a "good" explanation? In this work, we evaluate explanations through the lens of counterfactual simulatability-whether the explanation is useful for predicting model behaviors on related counterfactual inputs. To this end, we introduce CHIVE (Counterfactual Hypothesis Investigation Via Edits), a novel agentic pipeline that identifies unexpected model behaviors in the wild and investigates them with counterfactual prompt edits. This yields thousands of high-quality explanations for naturally-occurring model behaviors along with supporting counterfactual evidence. We apply CHIVE in two ways. First, we evaluate whether common LLM interpretability techniques improve an agent's ability to predict counterfactual model behaviors. Surprisingly, we find no uplift from any of the interpretability techniques studied. Second, we use CHIVE to ge

---

### [164] BiAxisBias: Evaluating LLM Bias Beyond a Single Prompt and a Single Explanation

**链接**: https://arxiv.org/abs/2605.09041
**作者**: Jialing Gan, Junhao Dong, Songze Li
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] No Universal Signal Predicts Sample-Level LLM Regression under Version Updates

**链接**: https://arxiv.org/abs/2608.13607
**作者**: Jia Sheng, Yiwei Lu
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier LLMs are updated frequently and typically outperform their predecessors in aggregate. But aggregate gains say little about individual samples: an update can still cause sample-level regression, where a response correct under the old model becomes incorrect under the new one. This paper studies how to predict such regressions from signals available at inference time. We compare single-model signals (confidence, logit margin, attention entropy) against cross-version signals (output KL divergence, likelihood drift, token-level KL, representation drift) under a unified added-value test that isolates each signal's gain over a confidence baseline. Across six benchmarks in three task families (multiple-choice question answering, or MCQ; math reasoning; code generation) and six model update pairs, we find that (1) signal effectiveness is task-dependent: confidence is strongest on MCQ and simpler math, while likelihood/KL signals give the most frequent gains on harder math and code; (2

---

### [166] MUSE: An Interactive Meta-Agent for Understanding and Steering LLM-powered Data Science Systems

**链接**: https://arxiv.org/abs/2608.16181
**作者**: Wei-Hao Chen, Weixi Tong, Yuan Tian, Chenglong Wang, Tianyi Zhang
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models have enabled a new class of agentic data science systems that allow users to complete complex data science workflows through natural language. Although these systems can significantly reduce manual effort, it remains difficult to diagnose their behavior and steer the reasoning process when failures or unexpected outputs occur. We present MUSE, an interactive meta-agent that enhances user understanding and control of agentic data science systems by (1) dynamically restructuring low-level execution traces into multiple semantic levels that support navigation from high-level overviews to low-level implementation details; (2) enabling users to reference specific workflow steps in context to ask grounded questions, provide feedback, and revise problematic steps without manually locating relevant execution history; and (3) supporting mixed-initiative steering by surfacing suspicious steps for inspection, scaffolding the repair process, and translating

---

### [167] Organizational Control Layer: Governance Infrastructure at the Execution Boundary of LLM Agent Systems

**链接**: https://arxiv.org/abs/2606.04306
**作者**: Tianyu Shi, Yang Mo, Yiou Liu, Zhuonan Hao, Yin Wang, Wenzhuo Hu 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] CAPO: Constraint-Aware Prompt Optimization for LLM Agents

**链接**: https://arxiv.org/abs/2608.16068
**作者**: Victor Ye Dong, Reid Pryzant, Yi Liu, Jian Jiao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as agents that rely on system prompts to use tools and complete tasks. Such deployments impose distinct operational requirements, including appropriate tool use, concise prompts and solution paths, and compliance with safety and formatting policies. For many practitioners, however, assembling domain-specific supervised data to post-train models to meet these requirements is infeasible. We introduce CAPO (Constraint-Aware Prompt Optimization), a primal-dual method that combines pool-based rewrites with adaptive constraint weighting to optimize system prompts under explicit operational constraints. Across agentic benchmarks, CAPO more reliably reaches empirically feasible operating points while improving task performance. CAPO also generalizes beyond agentic settings, achieving strong results on assistant-style evaluations with output-format and safety/privacy constraints. We further introduce DCAPO (Dynamically Trained CAPO), which 

---

### [169] From Prompts to Constructs: A Dual-Validity Framework for Large Language Model Research in Psychology

**链接**: https://arxiv.org/abs/2506.16697
**作者**: Zhicheng Lin
**来源**: cs.CY cs.AI cs.CL cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [170] Toward Safe LLM Agents: A Survey of Specification, Verification, and Enforcement

**链接**: https://arxiv.org/abs/2608.14590
**作者**: Pierre Dantas, Lucas Cordeiro, Ehsan Nowroozi, Tihanyi Norbert
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly perform irreversible real-world actions, including database updates, API calls, file operations, and autonomous use of tools. However, no existing system provides formally grounded, task-level safety guarantees for the plans these agents generate. Research remains fragmented across specification, verification, and enforcement, limiting understanding of the strengths and limitations of existing approaches. To address this gap, we conducted a PRISMA 2020 systematic review of 38 studies published between 2022 and 2026 and retrieved from six academic databases. Our analysis reveals four key findings. First, the specification bottleneck remains the primary challenge: natural-language-to-formal translation achieves only 24% to 35% semantic correctness, undermining downstream verification. Second, runtime monitoring is the most mature enforcement strategy, reducing unsafe actions by 40% to 65% in controlled settings, but it does not provide complete safety guarantees. 

---

### [171] Topological Attribution Distance (TAD): Revealing Segment-Level RAG Influence on LLM Output Geometry for Incident Log Analysis

**链接**: https://arxiv.org/abs/2608.16775
**作者**: Reza Fayyazi, Michael Zuzak, Shanchieh Jay Yang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly being deployed in cybersecurity operations to assist cybersecurity analysts with rapid decision-making against emerging threats. However, there is a main criteria that must be met when using LLMs in cybersecurity, that is, trust in the generated outputs. As Agentic AI is integrated into operational systems, a robust evidence attribution and provenance tracking technique is essential to trace the origins of model generations. When autonomous agents make a decision (right or wrong), the ability to trace back through the decision chain is critical, as without it, teams cannot identify which segment of the data caused the model generation. Existing methods often struggle to distinguish among complex and highly similar evidence sources, such as cyber incident logs. This reveals a key gap: current approaches do not adequately capture the holistic geometric relationship between the retrieved evidence and the generated response for reliable evidenc

---

### [172] Knowing When to Stop: Bayesian Optimal Stopping for LLM Evaluations

**链接**: https://arxiv.org/abs/2608.14425
**作者**: Toby D. Pilditch
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM evaluations often use fixed sampling budgets, testing every item the same number of times even after estimates are precise. We introduce optstop, a precision-based adaptive stopping framework that treats evaluation as a sequential measurement problem: keep sampling where uncertainty remains high, and stop where estimates are precise or stable enough. The framework builds on hierarchical Bayesian inference, supports binary, ordinal, and continuous outcomes, and keeps every benchmark item eligible for sampling, without requiring a calibrated item bank. It runs live or retrospectively, and includes a safeguard that samples more cautiously as measured performance approaches zero, where rare successes matter most. In an illustrative 200-item, 10-epoch evaluation, it removes 57%-97% of planned trials across nine validation settings, with overall conclusions equivalent to the full run. These results show that LLM evaluation compute can be allocated by uncertainty rather than by fixed repe

---

### [173] MINT: A Universal Zero-Shot Predictor for Transaction Data

**链接**: https://arxiv.org/abs/2608.14198
**作者**: Parameswaran Kamalaruban, Viktor Drobnyi, Maeve Madigan, Julia Rozanova, David Sutton, Stuart Burrell
**来源**: cs.LG cs.CL
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Banks analyse sequential financial transaction data to perform many tasks, including fraud prevention, credit risk assessment and offer personalization. To improve the predictive accuracy of these tasks, Payments Foundation Models encode transaction sequence data as rich contextual embeddings, which can then be provided to task-specific models as features. However, these Foundation Models are not designed for flexible zero-shot reasoning across novel downstream prediction tasks, limiting their adaptability and utility. Existing LLM-based approaches to zero-shot prediction often fail to fully exploit the predictive signal within transaction data, while relying on costly text serialization or task-specific architectures that scale poorly. To address these limitations, we present the Multimodal Instruction Network for Transactions (MINT), a framework that connects a pretrained transaction sequence encoder to a decoder-only LLM through lightweight embedding injection, transaction-language 

---

### [174] Measuring the Prevalence of Policy Violating Content with ML Assisted Sampling and LLM Labeling

**链接**: https://arxiv.org/abs/2602.18518
**作者**: Attila Dobi, Aravindh Manickavasagam, Benjamin Thompson, Xiaohan Yang, Faisal Farooq
**来源**: cs.LG stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [175] FluxBin: Flexible LUT-based Ultra-low-bit LLM Inference by Algorithm-Kernel Synergy

**链接**: https://arxiv.org/abs/2608.15602
**作者**: Qingyao Yang, Runming Yang, He Xiao, Wendong Xu, Junyu Chen, Haobo Liu 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While binary quantization theoretically promises extreme compression and acceleration for Large Language Models (LLMs), existing research often overlooks the necessity of specialized hardware kernels, thus failing to unleash the full acceleration potential due to persistent reliance on expensive floating-point arithmetic or runtime dequantization overheads. To bridge this gap, we propose FluxBin (\textbf{F}lexible \textbf{L}UT-based \textbf{U}ltra-low-bit e\textbf{X}ecution with \textbf{Bin}ary bases), an algorithm-kernel co-design that synergizes post-training quantization with a highly optimized CUDA kernel. Algorithmically, we introduce Decoupled Row-Column Binary Decomposition to enhance representational capacity while maintaining hardware efficiency, complemented by a Hessian-guided saliency-aware hybrid bases that preserve critical information. At the kernel level, we implement a Lookup Table Building Approach with Scale Fusion to reduce floating-point arithmetic, featuring a Vir

---

### [176] SiMUSation: An Interactive Visitor Experience Simulation Framework to Support Museum Exhibition Design

**链接**: https://arxiv.org/abs/2608.16067
**作者**: Huanchen Wang, Qiuming Chen, Zhonghao Ji, Ruqi Sun, Zhichao Lu, Yuxin Ma
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding how diverse audiences engage with narratives and content is central to exhibition design, yet designers often rely on intuition. Existing experience evaluation methods are typically retrospective, costly, and offer limited access to visitors' internal states, hindering early-stage iterative refinement. Rather than relying only on post-implementation evaluation with real visitors, we explore LLM-driven persona simulation as a reference for early-stage design. Following this idea, we present SiMUSation, an interactive framework designed to support early-stage exhibition design. SiMUSation models diverse visitor personas and simulates their exhibition experiences through a dual-layer representation that couples observable behaviors, such as movement and gaze, with corresponding internal responses, such as confusion and narrative engagement. Designers can steer simulations, inspect feedback from simulated visits, and iteratively revise layouts, content, and narrative flow to 

---

### [177] Bootstrapping Niche Multilingual Code Translation via Reinforcement Learning with Execution-Based Verifiable Supervision

**链接**: https://arxiv.org/abs/2608.13854
**作者**: Kouki Yuki, Jie Zeng, Kyoko Ogawa, Ryunosuke Ikeda, Yohei Kobashi, Takeshi Kojima 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code translation must preserve executable behavior across many programming languages, yet neural code translation has largely focused on a few popular languages such as C++, Java, and Python. This leaves a niche, many-to-many setting where parallel supervision is sparse, producing plausible but non-executable translations. We address this setting with preference-based reinforcement learning driven by execution-based supervision. Our pipeline firstly expands verifiable seed Python programs into a multilingual pool of execution-validated codes. Using the pool, a base LLM generates translation candidates across language pairs, which we label by their execution outcomes. The resulting preferences are used to train a reward model that scores cross-language translation quality. Finally, we optimize our base LLMs with GRPO over 600 directed language pairs (25 x 24) using the reward model as a signal. To evaluate the niche translation capability, we introduce HumanEval-X++, an execution-based 

---

### [178] AutoMem: A Text-Gradient Recursive Self-Improvement Framework for Automated Memory Architectures Search

**链接**: https://arxiv.org/abs/2608.14621
**作者**: Lin Du, Jie Zhou, Yuxuan Cai, Kai Chen, Qin Chen, Xin Li 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is increasingly central to LLM agents, yet memory design remains a highly coupled architecture problem: what to encode, how to store it, how to retrieve it, and how to manage it can vary substantially across tasks and backbone models. We construct a discrete search space with 5 encoders, 5 stores, 6 retrievers, and 4 managers, and show that no single memory architecture consistently dominates: different tasks favor different module combinations, leading to substantial performance gaps. Motivated by this, we propose \textsc{AutoMem}, a text-gradient recursive self-improvement framework for task-adaptive memory architecture search. \textsc{AutoMem} optimizes over the factored space through two components: Experience-Guided Architecture Search, which proposes candidate architectures from historical search trajectories and accumulated reflections, and Failure-Guided Module Diagnosis, which localizes memory-related failures to specific modules and converts them into targete

---

### [179] The Open-Strategy Dictator Game: Cooperation Under Mutual Transparency

**链接**: https://arxiv.org/abs/2608.14913
**作者**: Michael Glass
**来源**: cs.GT cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce the Open-Strategy Dictator Game (OSDG), a variant of the classic dictator game in which each player's strategy is a natural-language document visible to all participants. The dictator's decision, to SHARE or TAKE an endowment, may depend on the text of the recipient's strategy. A large language model adjudicates each interaction by interpreting the dictator's strategy in the context of the recipient's. We run round-robin tournaments among diverse strategies and analyze the resulting payoff matrix using softmax equilibrium frequencies, dominance analysis, and sensitivity to the relative value of cooperation. Conditionally cooperative strategies, those that share with cooperators and take from exploiters, consistently dominate, while unconditional strategies (always share or always take) are weakly dominated. The results suggest that in environments where agents can inspect each other's decision procedures, conditional cooperation is evolutionarily robust across a wide range

---

### [180] When Agentic Executions Fail: Detecting and Localizing Runtime Faults from Telemetry

**链接**: https://arxiv.org/abs/2608.14680
**作者**: Chenkai Zhang, Yiran Li, Yifang Tian, Michalis Bachras, and Hans-Arno Jacobsen
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliability in LLM-based agentic systems is a property of the whole execution (its tool calls, model calls, guardrails, and inter-agent messages), not of the final answer alone, yet evaluating only task outcomes reveals little about how or why a run fails. We present AGENTCHAOSBENCH, a benchmark for detecting and localizing runtime faults in agentic systems from their execution telemetry. We run five heterogeneous applications that coordinate agents over the Agent-to-Agent protocol and call tools through the Model Context Protocol, and inject ten types of operational fault (unavailable or slow tools, corrupted or oversized responses, and delayed, looped, or misrouted delegations and bypassed guardrails) at their tool, model, guardrail, and inter-agent boundaries, alongside a no-fault control. The resulting dataset contains 275 sanitized traces: 250 faulty executions spanning ten fault types and 25 no-fault controls. Each faulty trace is aligned with the no-fault execution of the same i

---

### [181] Harness the Memory: A Holistic Evaluation of Memory Substrates in Memory Agents

**链接**: https://arxiv.org/abs/2608.15008
**作者**: Wei-Chieh Huang, Weizhi Zhang, Yuchen Wu, Yankai Chen, Eric Hanchen Jiang, Wooseong Yang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory is becoming core infrastructure for long-horizon LLM agents, yet existing evaluations offer limited guidance on which memory substrate, namely the underlying medium in which memory is represented and stored, should be used under different operating regimes. We present a controlled harness evaluation of memory substrates for memory-augmented agents, covering dense and sparse indices, text records, structural stores, hierarchical stores, refinement-based memories, parametric updates, and activation-compatible context mechanisms. Across three backbone models and four benchmark suites spanning user-centric question answering and agent-centric decision-making, we instrument 26 performance and efficiency metrics under a unified harness. Our results show that no single substrate consistently dominates: broad retrieval benefits long-context factual QA, while excessive retrieval can harm sequential decision-making by shifting attention away from action-critical context. Scalability intro

---

### [182] Conditional Evaluation of Language Models with Cheap Auxiliary Signals

**链接**: https://arxiv.org/abs/2608.16210
**作者**: Zhi Zhang, Lingfeng Lyu, Yue Kang, Doudou Zhou
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aggregate accuracy hides where models succeed and fail. Estimating conditional performance profiles from gold labels alone is expensive, while cheap auxiliary signals such as LLM-judge scores, pairwise comparisons, confidence scores, and judge-disagreement features can be collected for every benchmark item but are often biased or miscalibrated. We propose LACE (Local Augmented Control-Variate Evaluation), a semi-supervised estimator for conditional LLM evaluation. The key step is local centering: after subtracting the conditional mean of a cheap signal within the target profile region, any linear augmentation has zero conditional mean and therefore cannot change the estimand. The augmentation coefficient is used only for efficiency, and a local ridge control variate combines a gold-label residual mean from the labeled subset with a cheap-signal mean from the full item pool. We prove calibration-free identification, unbiasedness for grouped profiles, local oracle optimality within cente

---

### [183] GoalEvolve: From Handcrafted Algorithm Priors to Goal-Driven Evolution of Physical Design Algorithms

**链接**: https://arxiv.org/abs/2608.16733
**作者**: Haixu Liu, Lei Zhou, Yuhao Ren, Yumao Wu, Zhiang Wang
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physical design algorithms operate within tightly coupled, multi-stage optimization flows, where stage-local gains may vanish or induce downstream degradation. Existing program-evolution frameworks often rely on stage-local objectives or undifferentiated multi-metric feedback, which neither guarantee better final results nor identify which unmet requirement should guide the next iteration. We present GoalEvolve, a goal-driven framework that makes physical design algorithm evolution accountable for the final quality of results (QoR) of the complete flow. Given a multi-objective QoR target region, GoalEvolve converts unmet requirements into normalized target gaps, identifies the dominant bottleneck, and uses stage-resolved checkpoint evidence to locate the responsible stage. An LLM-based Teacher then narrows the search to a relevant algorithmic decision and source region, while parallel Student agents implement and validate hypotheses through full-flow evaluation. Local effects, optimiza

---

### [184] ATLAS: Scaffold-Free Algorithm Synthesis by LLMs via Embedding-Guided Quality-Diversity Search

**链接**: https://arxiv.org/abs/2608.15546
**作者**: Danial Yazdani, Mohammad Nabi Omidvar, Yuan Sun, Maksud Ibrahimov, and Xiaodong Li
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most LLM-based automated algorithm design methods optimize a designated component within a human-specified scaffold, fixing overall organization and component interactions. We present ATLAS, an embedding-guided quality-diversity framework for scaffold-free full-algorithm synthesis in combinatorial optimization. The problem specification supplies objectives and constraints; a minimal I/O interface fixes only instance and solution formats; the LLM chooses and restructures components, interactions, and control flow. This freedom enlarges the search space, risking invalid candidates and premature convergence to one design region. ATLAS independently detects execution, interface, and feasibility failures, recomputes objectives, and applies error-conditioned repair; similarity-based archive management preserves algorithms across embedding-space regions to counter premature convergence. Its three-layer search refines the best design, gives other regions dedicated refinement opportunities, and

---

### [185] Federated Prompt Learning: A Unified Framework, Empirical Analysis, and Future Directions

**链接**: https://arxiv.org/abs/2608.13844
**作者**: Qinglin Yang, Chen Qiu, Hongyuan Zhang, Pengdeng Li, Yuan Liu, and Zhihong Tian
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have become core components of cloud-based intelligent services in academia and industry, yet their training and deployment are hindered by high computational costs, data centralization, and privacy concerns. Federated learning (FL) offers a decentralized training paradigm that enables clients to collaboratively train a learning model without sharing raw data, making it a promising solution for privacy-preserving LLM training and reasoning. This paper presents a comprehensive survey of federated prompt learning (FPL) to review recent advances in integrating the federated learning paradigm and large language models, answering the following research questions: RQ1: The fundamental motivations, characteristics, and enabling technologies of FPL, and how it differs from conventional FL and full-model federated fine-tuning; RQ2: The trade-offs FPL approaches exhibit in performance, communication efficiency, computational overhead, scalability, personalization, an

---

### [186] DuplexGen: Decoupling Content, Timing, and Acoustics for Synthetic Dialogue Speech

**链接**: https://arxiv.org/abs/2608.16053
**作者**: Pengcheng Wang, Sheng Li, Jiyi Li, Takahiro Shinozaki
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic conversational speech has become an important resource for developing and evaluating conversational speech systems. However, existing dialogue synthesis pipelines typically generate dialogue content first and then insert interruptions, overlap, and backchannels using handcrafted markers or timing rules, making conversational timing prescribed rather than interaction-driven. We present DuplexGen, a dialogue synthesis framework that explicitly decouples content, timing, and acoustics. An LLM first generates the dialogue script, and then two full-duplex conversational models perform the script while listening to each other in real time. This allows conversational timing to emerge naturally while preserving the scripted content. Finally, a high-fidelity text-to-speech model re-renders the interaction without altering its timing. As a demonstration of the proposed framework, we construct a patient--clinician conversational speech corpus with construction-time annotations, includin

---

### [187] Jais 2: A Family of Arabic-Centric Open Large Language Models

**链接**: https://arxiv.org/abs/2608.13580
**作者**: Mohamed Anwar, Abed Alhakim Freihat, George Ibrahim, Mostafa Awad, Abdelrahman Sadallah, Gurpreet Gosal 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jais 2 is a family of Arabic-centric large language models developed jointly by MBZUAI, Cerebras, and Inception, designed to advance Arabic-centric language modeling, with strong performance across the Arabic and culturally grounded benchmarks evaluated in this report. The family includes, to our knowledge, the largest open Arabic-centric LLM trained from scratch at 70B parameters, and a competitive 8B-parameter variant among the evaluated open models. A custom Arabic-centric vocabulary enables efficient training and inference. In addition, an optimized architecture and training recipe yield highly compute-efficient training. With a substantially smaller token budget than comparable models, Jais 2 achieves strong Arabic performance on the benchmarks considered in this report and competitive English results. The models obtain leading results among the evaluated open models on OALL2 and AraGen. They also perform strongly on several culturally grounded Arabic benchmarks, including poetry,

---

### [188] L3Cube-IndicQuest v2: A Large-Scale Multilingual Benchmark for Evaluating Factual Knowledge of Large Language Models Across Indic Languages

**链接**: https://arxiv.org/abs/2608.15535
**作者**: Rinit Jain, Tirthraj Mahajan, Advait Joshi, Raviraj Joshi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present L3Cube-IndicQuest v2, a large-scale gold-standard multilingual question-answering benchmark for evaluating the India-specific factual knowledge of Large Language Models (LLMs). The benchmark comprises 3,471 curriculum-grounded English question--answer pairs spanning nine domains, curated from educational curricula, competitive examination materials, and domain-specific reference books. We introduce a practical hybrid construction strategy that combines context-grounded LLM-based question generation and validation with semantic deduplication and human verification, enabling scalable creation of benchmark data while preserving annotation quality. The benchmark is translated into 19 Indic languages, yielding a publicly released multilingual dataset of 69,420 question--answer pairs across 20 languages. We evaluate six LLMs under three protocols: LLM-as-a-judge and two deterministic lexical criteria, exact-substring and word-overlap matching. All three produce almost the same mod

---

### [189] Securing AI-Generated Code: A Just-in-Time Vulnerability Detection and Remediation Pipeline

**链接**: https://arxiv.org/abs/2608.16187
**作者**: Mikhail Surikov
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-assisted development tools generate vulnerable code at significant rates, yet few automated mechanisms exist to detect, enrich, fix, and verify security issues at development velocity, particularly ones that ground remediation in real-world threat context. This paper presents an automated security evaluation pipeline that generates Python code from LLMSecEval prompts, scans for vulnerabilities using CodeQL and Bandit in parallel with an independent Code Validator LLM, enriches the Code Validator findings with MITRE ATT&CK techniques, CWE Observed Examples, and Python best practice guidelines, generates fixes via the Code Generation LLM, and re-scans with CodeQL and Bandit to verify outcomes. Two pipeline configurations were evaluated: Pipeline 1 (P1), using enriched Code Validator findings only, and Pipeline 2 (P2), where it additionally receives the initial CodeQL and Bandit findings. Both configurations were run across four Claude models: Opus 4.8, Sonnet 4.6, Sonnet 5, and Haiku 

---

### [190] RoE-FND: Synergizing LLMs with Experiential Learning for Effective and Generalizable Evidence-Based Fake News Detection

**链接**: https://arxiv.org/abs/2608.15210
**作者**: Yuzhou Yang, Qichao Ying, Sheng Li, Zhiyin Zhu, Zhenxing Qian and Xinpeng Zhang
**来源**: cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The proliferation of deceptive content in social networks necessitates robust Fake News Detection (FND) systems. Existing pipelines either train detectors on labeled data or leverage Large Language Models (LLMs) for their reasoning ability. However, current approaches remain either limited in generalizability or prone to over-commitment to persuasive yet flawed rationales, lacking systematic experience and mechanisms to expose subtle reasoning errors. We propose \textbf{RoE-FND} (\textbf{\underline{R}}eason \textbf{\underline{o}}n \textbf{\underline{E}}xperiences FND), an LLM-based framework that combines self-reflective experience building with deliberation through retrieved experiences for FND. RoE-FND builds an experience bank via reflective learning that compares an unconstrained analysis with a label-conditioned analysis using the ground-truth label as posterior supervision, then summarizes their critical divergence into reusable reasoning guidelines. During inference, RoE-FND gen

---

### [191] ScienceFlow: A long-horizon agent for ML research, scientific discovery and beyond

**链接**: https://arxiv.org/abs/2608.14354
**作者**: Mingming Zhao, Jiqian Dong, Kangping Xu, Zadid Hasan, Chengrui Fan, Shan Jiang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enabling LLM agents to sustain productive, stable, and goal-aligned research over extended horizons is a central challenge for autonomous machine learning and scientific discovery, as progress hinges on continuously managing evolving state, exploration decisions, and computational resources. Pioneering autoresearch agents, despite great success, still lack mechanisms for continuity, recovery from dead ends, and value-driven compute allocation, which inherently undermines overall search efficiency, wastes computational resources, and lowers the chance of ultimate success. To bridge this gap, we introduce ScienceFlow, an end-to-end autoresearch agent framework that organizes long-horizon research work into research segments grounded in executable workspaces. It represents research progress as recoverable executable states, enabling efficient exploration, revision, and execution. Transitions between research segments are governed by Executable-State Transition through Re-Anchoring (ESTRA)

---

### [192] Computational KJ-Ho: An Analyst-Bias-Free Insight Extraction Framework from Large-Scale Qualitative Data Using Domain-Specialized LLMs

**链接**: https://arxiv.org/abs/2608.16467
**作者**: Kasumi Ban
**来源**: cs.HC cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The qualitative research methodologies that underpin consumer-insight generation - the KJ method, Grounded Theory, and Thematic Analysis - share a structural constraint: the cognitive processing capacity of the human analyst. Replication research further shows that conclusions vary substantially across analysts analyzing identical data (analyst bias). This paper proposes Computational KJ-Ho (the Kawakita Jiro method), a theoretical framework that computationally realizes the KJ method's epistemology - letting structure emerge from the data itself without imposing the analyst's preconceptions - an orientation we term "analyst-bias-free." The framework employs a domain-specialized LLM built through continued pre-training (CPT) on a marketing-research corpus and supervised fine-tuning (SFT) on expert-curated insight pairs, organized as a three-layer architecture: data structuring, insight extraction, and strategy generation. Two preliminary studies in the Japanese marketing context suppor

---

### [193] Walk Before You Run: The Importance of Data Exploration for Data Analysis Agents

**链接**: https://arxiv.org/abs/2608.16045
**作者**: Yike Yuan, Virum Ranka, Tina Lasisi, Lin Ma
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based data-analysis tools are increasingly used to help users analyze messy spreadsheets and workbooks, from answering questions over uploaded files to generating code, summaries, and visualizations. These systems are often evaluated by the correctness of their final downstream answers. However, reliable data analysis also depends on an earlier step: understanding what the dataset contains before solving the requested task. For complex workbooks, this Data Exploration step includes identifying the logical tables behind physical sheets, interpreting column semantics, recovering keys and relationships, and detecting quality issues. In current tools and benchmarks, this step is usually left implicit, creating a gap between downstream task performance and the dataset understanding needed for reliable, human-checkable analysis. Our key contribution is to identify this overlooked gap, make Data Exploration a first-class evaluation target, and show through downstream experiments that stro

---

### [194] A Policy Algebra for Trust-Preserving Agentic AI Execution

**链接**: https://arxiv.org/abs/2608.16402
**作者**: Bhaskar Tripathi, Anurag Kumar, Ramendra Kumar, Bhavesh Gadhe
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based agentic frameworks primarily optimize capability: whether an agent can reason, retrieve information, call tools, delegate work, and complete a goal. Enterprise execution requires a stronger property. A successful result is not reliable if it was produced through unauthorized data access, widened delegated authority, unapproved side effects, unrecoverable budget consumption, or incomplete evidence. This paper defines reliable capability as a path property: an agent is reliably capable only when it completes a task through action events that remain admissible under identity, profile, tool, data, memory, budget, artifact, approval, and audit constraints. We propose a policy algebra that defines the reliability envelope within which agent capability may be exercised. Security profiles and runtime obligations compose through joins, intersections, budget narrowing, approval inheritance, and evidence accumulation; the resulting composition is both trust-preserving a

---

### [195] Historical Backtesting for Scientific Question Discovery: A Protocol and Astronomy Pilot

**链接**: https://arxiv.org/abs/2608.16795
**作者**: Hui Mao
**来源**: cs.CE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systems that generate scientific research questions are evaluated today by expert scores, LLM-as-judge ratings, or curated case studies -- all subjective, none falsifiable. We formalize historical backtesting as an alternative: a system generates questions from a corpus frozen at a historical cutoff, the questions are frozen before any access to later literature, and a temporally isolated future corpus then determines whether each question was subsequently answered, partially addressed, independently posed, or ignored, and whether its underlying premise was supported or refuted. The protocol is model-agnostic: any system that emits frozen questions can be scored. We release reproducible astronomy instances with temporally isolated corpora, frozen questions, auditable labels, four reference baselines, and a submission interface. Two findings result. First, evidence-structure-first generation outperforms LLM-only prompting: across a generator decomposition crossed with a four-cutoff stre

---

### [196] Language-Specific Gaps in AI Safety Training Datasets

**链接**: https://arxiv.org/abs/2608.13695
**作者**: Chialuka Prisca-Mary Onuoha, Bright Etornam Sunu, Rashidat Sikiru
**来源**: cs.CY cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model providers routinely cite multilingual safety benchmarks spanning a dozen or more languages as evidence that their models are safe for non-English-speaking users. We show that these collection-level coverage claims frequently do not survive inspection at the level of an individual language. Auditing 21 resources across 25 language slices, of which 20 count as datasets under our counting rules, spanning three languages chosen to represent low- (Hausa), mid- (Swahili), and high-resource (French) tiers, we find that gaps in provenance, annotation reliability, access, harm-taxonomy coverage, and data reuse recur in patterns that partially, but not fully, track resource level. Using a controlled within-pipeline comparison, we show a Hausa-language slice falling below its own paper's translation-quality acceptance threshold while the same pipeline's Swahili output clears the same bar comfortably; this is evidence that these gaps are measurable and addressable, not inheren

---

### [197] Search or Chat? Comparing How We Learn About Debated Topics

**链接**: https://arxiv.org/abs/2608.14113
**作者**: Ran Yu, Alisa Rieger, Rabia Karatoprak Ersen, Jiqun Liu
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) become more integrated into everyday information platforms, chat-based systems are emerging as a popular alternative to traditional web searches, especially for informational search and informal learning tasks. Despite this shift, little is known about how different tools affect learning outcomes. Our work aims to improve the understanding of how chat-based information access supports and impacts learning performance in informal learning settings. In this paper, we present the results of a crowdsourcing user study (N = 194) that compares learning about debated topics using a traditional search interface versus an LLM-powered chat interface. Through our analysis of learning outcomes, user characteristics, and interaction patterns, we found no significant differences in user learning gain or critical reflection on our study tasks. Our observations from the analysis of further exploratory variables suggest that, in the context of longstanding debated topics

---

### [198] How Compliant is Sepsis Treatment? An Expert-Guided Neuro-symbolic Pipeline for Generating Clinical Compliance Insights

**链接**: https://arxiv.org/abs/2608.13617
**作者**: Himanshu Tripathi, Kaushik Roy, Subash Neupane, Shahram Rahimi
**来源**: cs.AI cs.SC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifying whether clinical care follows evidence-based protocols is a natural neuro-symbolic problem, yet the safety-critical setting defeats either paradigm alone. We present an expert-guided pipeline that constrains a large language model strictly to semantic normalization, mapping messy drug and microbiology strings onto a fixed clinical vocabulary, while a Sugeno fuzzy inference system reasons over the normalized events. The fuzzy layer encodes eight Surviving Sepsis Campaign bundle rules and replaces binary judgments with graded scores in [0,1]. Applied to 2,438 MIMIC-IV v3.1 sepsis episodes, it surfaces antibiotic timing as the most critical breakdown (mean 0.24, 13% within one hour), Hour-1 underperformance (mean 36.7%), a 51% elevated-lactate drop-off, and descriptive differences in ICU stay across compliance groups (3.8 versus 5.1 days).

---

### [199] Calibrated Trust, Not Sharper Prediction: An Empirical Test of Uncertainty Fusion

**链接**: https://arxiv.org/abs/2608.14617
**作者**: Surya Saka
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A recurring proposal in legal AI is to improve case-outcome prediction by fusing uncertainty tools (evidence graphs with belief propagation, sequential Bayesian odds updating, Dempster-Shafer combination, and conformal prediction) into one pipeline. We test this on 1,000 real European Court of Human Rights cases from LexGLUE and FairLex, predicting whether the Court found a Convention violation from the case's fact paragraphs. We compare three families across two frontier LLMs (Claude Opus 4.8 and GPT-5.5) as per-fact evidence estimators: (A) the raw LLM, (B) the LLM routed through the fusion pipeline, and (C) a term-frequency baseline through the same pipeline. Across roughly 4,750 tests we find: (1) on discrimination (AUROC around 0.83) the pipeline yields no improvement over either the raw LLM or the baseline; a frontier LLM used directly is the strongest single discriminator. (2) Naively composing an LLM with Bayesian-odds and Dempster-Shafer fusion more than doubles calibration er

---

### [200] Bounded Agents: Delegation Security for Multi-Agent AI Systems

**链接**: https://arxiv.org/abs/2608.15888
**作者**: Xabier Muruaga
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents can act on behalf of a user to access cloud services, call tools, or invoke agents. At session start, the agent's permissions are set but remain static, and each request is evaluated independently, without considering prior actions. Within its permissions, an agent may act contrary to the delegated task, combine individually permitted actions into a prohibited outcome, or delegate authority to a sub-agent without limiting it. A prompt injection poses a risk only if the agent has authority to perform such actions; this is therefore a problem of authorization architecture, not just the model. The Agentic Principal Chain (APC) tracks delegated authority from one principal to the next. APC evaluates each request against the accumulated session state using six authorization checks. APC carries forward and restricts delegated scope and budgets. Using composition closure, APC checks requests against prior actions to prevent prohibited combinations and enforces the decision ou

---

### [201] Agentic Data Cleaning Without a Clean Reference: An Experimental Study of Capabilities and Trade-offs

**链接**: https://arxiv.org/abs/2608.14765
**作者**: Hadi Fadlallah
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data cleaning without a trusted clean reference is challenging because unusual values may represent either genuine errors or valid observations. This paper studies how different agent capabilities affect reference-free data cleaning and proposes an evidence-grounded framework that combines structured context, profiling, LLM reasoning, executable checks, controlled evidence retrieval, source ranking, citation alignment, conservative repair, reversible scripts, and provenance logging. Seven configurations are evaluated across financial, clinical, and environmental-monitoring datasets using controlled synthetic corruption and original-data descriptive analysis, resulting in 126 completed runs. The evaluation includes two comparison baselines and a progressive LLM-based sequence that adds executable tools, evidence retrieval, evidence controls, and conservative repair. In the synthetic evaluation, the deterministic profiling baseline achieved the highest detection F1-score of 0.561. Among 

---

### [202] Large Language Models Show Metacognitive Sensitivity in Medical Reasoning

**链接**: https://arxiv.org/abs/2608.14552
**作者**: Ahmad Nazzal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly evaluated and used in medicine, but clinical usefulness depends on answer accuracy and whether confidence tracks evidence quality and uncertainty. We developed a controlled, psychophysics-inspired clinical benchmark to test diagnostic choice and confidence behavior in a medical LLM. The benchmark focused on probable Alzheimer-type neurocognitive disorder (AT-NCD) versus depression-related cognitive impairment (DRCI). We generated 45 synthetic vignettes varying evidence strength, conflicting evidence, and missing information. Each vignette was presented under three prompt variants, yielding 135 trials. In a pilot run with gpt-4.1-nano, all trials produced valid structured outputs. Across forced-choice trials, diagnostic accuracy was 93.5%, mean confidence was 78.4%, and AUROC2 was 0.876. Confidence increased with evidence distance from the diagnostic boundary, decreased when information was missing, and remained higher on correct than incorr

---

### [203] Semantic Bandits: In-Context Exploration-Exploitation is Biased by Semantic Priors

**链接**: https://arxiv.org/abs/2608.16707
**作者**: David Eric Austin, Kaheer Suleman, Jackie Chi Kit Cheung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as decision-making agents in settings that require sophisticated environmental exploration. However, existing work has raised questions about how LLMs actually balance exploration and exploitation. Unlike classical agents, LLM agents engage with tasks through natural language, exposing them to semantic information with no formal counterpart in the task structure. We introduce the semantic bandit, an extension of the multi-armed bandit setting that explicitly considers the textual labels assigned to actions, and use it to study how semantic priors --- inductive biases arising from associations between language and expected reward learned during pre-training, shape LLM exploration behaviour. We find that semantically informative action labels reduce exploration in favour of exploitation, improving performance when aligned with the reward structure and severely degrading it when misaligned. We further find that negative rewards trigge

---

### [204] STAIR: Semantic-Temporal Automaton for Interpretable Reasoning in Temporal Question Answering

**链接**: https://arxiv.org/abs/2608.16224
**作者**: Xinlong Dai, Jinchuan Zhang, Lei Gao, Xinzhe Hu, Yuefeng He, Hui Gao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> By leveraging large-scale pretraining, LLMs can interpret diverse temporal expressions and question formulations without task-specific training. However, existing prompt-based neuro-symbolic systems continue to rely on LLMs for both semantic interpretation and exact temporal inference. Consequently, discrete decisions regarding intervals, time anchors, and ordered states remain vulnerable to probabilistic errors and difficult to verify. We present STAIR, a \textbf{S}emantic-\textbf{T}emporal \textbf{A}utomaton for \textbf{I}nterpretable \textbf{R}easoning. STAIR separates semantic interpretation from precise temporal inference: an answer-free LLM adapter maps complex question formulations to normalized temporal intents, while a deterministic temporal automaton with finite control and guarded transitions executes the corresponding policies over canonicalized evidence. Following a rule-first design, STAIR resolves standard questions without invoking an LLM and applies semantic adaptation

---

### [205] Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory

**链接**: https://arxiv.org/abs/2608.16889
**作者**: Bingxin Xu, Yuzhang Shang, Emilio Ferrara
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon robot manipulation chains many contact-rich skills into one multi-stage task. Vision-language-action (VLA) models increasingly master the individual skills, yet the chain still fails: errors compound beyond the policy's ability to correct, and one subtask silently constrains the next. A promising recipe freezes the VLA and puts an LLM agent in charge: it plans in language, moves in free space with analytic primitives, invokes the VLA only for contact-rich segments, and writes adaptation into language memory. Applied to long horizons, it breaks twice. (1) Competence comes from whole-task exploration at test time, whose cost is multiplicative in stages: if one stage needs T episodes, a K-stage task needs about T^K, and a failure does not reveal which stage caused it. (2) It has no representation of transitions: the VLA primitive carries an exit but no entry condition, so a subtask can succeed in a form its successor cannot use. We present BATON. Against (1), BATON makes the 

---

### [206] RaivenTracks: Branching Provenance for Conversational Visualization Workflows

**链接**: https://arxiv.org/abs/2608.14869
**作者**: Ella Hugie, Alexandra Irger, Grace Guo, Kenneth Moreland, David Pugmire, Scott Klasky 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI agents increasingly participate in scientific workflows, scientists are shifting from direct authorship toward oversight, inspection, and steering. LLM-driven visualization systems are a promising interface for this hand-off, yet they remain largely stateless, forcing users to reconstruct context across refinements and offering little support for revisiting prior decisions or exploring alternatives. We present RaivenTracks, a workflow-aware extension of the Raiven DSL-mediated visualization pipeline that treats validated visualization specifications as persistent, branchable checkpoints. Because each checkpoint is a verifiable RaivenDSL specification rather than a dialogue transcript, restoring a node recompiles a known artifact rather than re-interpreting prior context. RaivenTracks contributes a two-level state management architecture that pairs a persistent, branchable version tree with a fine-grained undo/redo stack over runtime visualization settings, across both InfoVis and

---

### [207] The User Side of AI Model Lifecycles: Evidence from the Keep4o Movement

**链接**: https://arxiv.org/abs/2608.16574
**作者**: Yiwen Wu
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI model lifecycles are commonly understood as a series of technical and organizational processes. Yet once a model enters sustained use, subsequent changes can also affect established user practices and user value. Using the Keep4o movement around GPT-4o as a case, this study examines post-deployment AI model lifecycle issues from the user side. We collected 61,846 public original posts on X from August 2025 to March 2026 and, using a systematically developed coding framework and LLM-assisted content analysis, analyzed discussion themes, users' reasons for wanting to keep GPT-4o, and the specific claims they made. Findings show that the Keep4o discussion extended well beyond continued access to the model itself. It covered concrete experiences of use, model behavioral characteristics and how they changed, and management issues across different stages of the model lifecycle. Reasons for keeping GPT-4o reflected interactional and relational value formed through long-term use, as well as

---

### [208] Insurance as AI Risk Infrastructure: A Generative-Agent Simulation of AI Adoption

**链接**: https://arxiv.org/abs/2608.15181
**作者**: Yixuan Yuan, Dedai Wei, Chudong Qian, Jielin Feng, Ziyue Lin, Yuheng Zhao 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid evolution of artificial intelligence (AI) tools has demonstrated immense potential to enhance societal well-being and operational efficiency. However, the inherent unreliability and uncertain operational consequences of modern AI systems, typified by large language models (LLMs), have created a significant barrier to enterprise adoption. Many enterprises remain hesitant to integrate these tools deeply into their workflows due to concerns about unpredictable losses and liability exposure. While existing technical safeguards primarily seek to reduce the likelihood or severity of AI-enabled workflow failures, they do not by themselves provide ex post financial protection when residual pecuniary tail losses materialize. In this paper, we introduce a socio-economic framework that complements these safeguards by transferring and absorbing the residual financial consequences of AI adoption through insurance. To evaluate this framework, we develop an LLM-driven agent-based social sim

---

### [209] RAGas: Retrieval-Augmented Gas Optimization for Smart Contracts with Continuous Knowledge Integration

**链接**: https://arxiv.org/abs/2608.15857
**作者**: Yishun Wang, Wenjin Yi, Wenkai Li, Zongwei Li, Xiaoqi Li
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ethereum is now integral to mission-critical sectors, including finance, healthcare, and supply chain management. Execution fees, commonly referred to as Gas, scale with the computational complexity of their functions. Smart contracts on Ethereum incur execution fees, known as Gas, which increase with computational complexity. Thus, optimizing Gas-intensive code while preserving functional equivalence significantly lowers deployment costs. No existing system continuously exploits evolving Gas usage patterns. We systematically analyze syntactic and semantic constructs that drive excessive Gas use. This yields six high-level categories covering twelve fine-grained antipatterns underpinning a curated knowledge base. We operationalize these insights with RAGas, a three-stage retrieval-augmented generation framework that uses a large language model to pinpoint and automatically fix Gas inefficiencies. Experiments on deployed contracts demonstrate that RAGas reduces Gas usage by up to 11% an

---

### [210] No Task Fails Every Time: Why One-Shot Audits Are Structurally Blind to Agent Damage

**链接**: https://arxiv.org/abs/2608.15286
**作者**: Shiven Khurdi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce AgentRelBench, an environment-agnostic reliability instrument that computes ground-truth, severity-priced damage from database state diffs across repeated runs, with no LLM in the measurement path, demonstrated on EnterpriseOps-Gym. Across 2,128 evaluation runs spanning nine models in six families (four development, three pre-registered held-out, plus a frontier pass on two frontier-tier models that the pre-registration designates exploratory), we find: (1) damage on irreversible actions is universal across the families we measured and stochastic within them on pinned, single-provider stacks. (2) No task damaged on every run: zero always-fail cells across 42 confirmatory held-out damage events. A single clean run misses a damage-producing (model, task) pair 0.80 of the time on the development pool (13 pairs); the held-out pool is descriptively consistent (0.575 over 5 pairs, pair-weighted) but sits below our pre-registered power floor and is reported as underpowered, not a

---

### [211] A Human-Centred Approach to Benchmarking LLMs for Parenting Advice

**链接**: https://arxiv.org/abs/2608.14622
**作者**: Yunke Zhao and Isobel Voysey and Alastair van Heerden and Rob Hughes and Jun Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People are increasingly using large language models (LLMs) to seek advice, including for parenting. Parenting is a critical and socially sensitive domain. Thus, evaluating advice provided by LLMs requires indicators beyond aggregated information quality benchmarks to consider relational and behavioural elements of the responses. With a multi-dimensional rubric created by parenting experts, this paper evaluates 15 LLMs across 100 parenting scenarios in 2 languages (English and Chinese), using an LLM-as-a-judge method. Results show that aggregate scores can hide rubric item-specific weaknesses, models implicitly encourage different parenting styles, and language influences responses. We highlight the importance of evaluation output auditability and challenges involved in evaluating LLM-generated advice in domains like parenting. Our findings provide important insights for selecting LLMs for direct user engagement and the development of user-facing parenting advice applications.

---

### [212] Characterizing Rhetorical Misalignment in Decision-Making with Language Models

**链接**: https://arxiv.org/abs/2608.14630
**作者**: Zirui Cheng, Joey Chan, Simo Du, Chenhao Tan, Yue Guo, Hao Peng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human decision-making is often shaped by a range of well-documented cognitive biases. As large language models (LLMs) become increasingly integrated into high-stakes human-AI decision-making, it is important to understand whether their outputs can amplify potential biases, how this influences human decisions, and crucially, whether it can lead to harmful consequences. In this work, we develop a decision-theoretic framework to study rhetorical misalignment, a failure mode where an LLM uses rhetorically inappropriate forms of presentation for a given decision context, thereby inducing suboptimal human decisions. We empirically investigate this phenomenon through a human-subject experiment in realistic clinical decision-making using a dataset curated from the United States Medical Licensing Examination. By measuring how LLM-generated information affects decisions, we observe that LLMs induce an average 2.81% rate of harmful decision flips across different models, where clinician participa

---

### [213] Do Uncertainty Signals Help? A Systematic Study of Uncertainty-Aware Decoding with Rollback Mechanisms

**链接**: https://arxiv.org/abs/2608.14653
**作者**: Xianzong Wu, Xiaohong Li, Yuejun Guo, Xinyang Liu, Tianlin Li, Junjie Wang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prediction uncertainty is a widely adopted metric for quantifying model confidence, with downstream applications spanning model explanation, data selection, and prediction rollback. Despite its demonstrated utility, the potential of uncertainty quantification to enhance code generation in large language models (LLMs) remains largely underexplored, raising a critical question: to what extent can uncertainty serve as an effective signal for improving LLM-based code generation? To answer this question, we study uncertainty-aware rollback decoding, an inference-time strategy that uses uncertainty signals to identify unreliable generation regions and roll back to earlier valid prefixes without retraining the model. We evaluate this framework on seven code LLMs, five code generation benchmarks, and eight token-level uncertainty signals under a unified decoding setup. Our results show that the complete rollback framework improves over equal-budget restart across the evaluated benchmarks and m

---

### [214] DUET: Dual-Teacher On-Policy Distillation via Same-Weight Disagreement for Prohibition Compliance

**链接**: https://arxiv.org/abs/2608.14644
**作者**: Zihan Li, Feifei Li, Wenhui Que
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world LLM deployments increasingly rely on runtime-injected prohibitions--enterprise policies, PII redlines, tool boundaries--that vary per request and per tenant. Conventional post-training is structurally ill-suited: SFT hides the violation signal in compliant labels, and DPO's sequence-level preferences mismatch token-localized violations. We propose DUET, a token-selective on-policy distillation method for prohibition compliance. DUET pairs a teacher that sees the prohibition (positive) with an identical-weight teacher that does not (negative). Because the two teachers differ only in prohibition visibility, their per-token disagreement isolates the prohibition's causal effect--yielding a clean supervision signal uncontaminated by model capacity or mismatch. This disagreement drives two complementary mechanisms: signal cleaning, which discards agreement tokens as redundant or prefix-corrupted, and preference-directed learning, which pushes the student away from the negative tea

---

### [215] CRAFT: Constrained Reward via Attention Fine-Tuning for Subject Personalization without Composed Targets

**链接**: https://arxiv.org/abs/2608.14403
**作者**: Jihun Park, Kyoungmin Lee, Jongmin Gim, Hyeonseo Jo, Jaeyeul Kim, Han Zou 等 (9 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Subject-driven image personalization---generating new images that preserve the identity of one or several reference subjects in novel scenes---is a foundational capability for modern visual content creation. It is currently dominated by generalized methods that fine-tune a pretrained multimodal diffusion transformer (MMDiT) on hundreds of thousands to millions of paired \emph{(reference, composed-target)} examples, where each composed target is a synthesized image of the subject in a novel scene. Producing such targets demands a costly multi-stage curation pipeline---LLM-based prompt generation, T2I-based composed-target synthesis, reference-subject extraction, VLM-based quality filtering, and correspondence labeling---and tightly couples each method to a particular target synthesizer and curation choice. We introduce \emph{CRAFT} (Constrained Reward via Attention Fine-Tuning), a single-step ReFL framework that fine-tunes a pre-trained \emph{reference-aware} MMDiT via LoRA adapters usi

---

### [216] Context Aware AI Assistant and AR Interface for Lunar Extravehicular Activity (EVA) Procedural Guidance

**链接**: https://arxiv.org/abs/2608.13589
**作者**: Rodrigo Gallardo, Qilmeg Doudatcz, Ganit Goldstein, Ilkyaz Sarimehmetoglu, Sergio Mutis, Alexander Htet Kyaw 等 (10 人)
**来源**: cs.HC cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As human space exploration returns to the Moon, astronauts need rapid access to procedural information during extravehicular activities (EVAs), where attention is divided across navigation, repair tasks, tool handling, and environmental risk. The challenge is not the absence of information, but surfacing the right information at the right moment. We present GAIN-AI (Guided Assistant for Intelligent Navigation), a context-aware AI assistant and minimal heads-up interface for procedural guidance in simulated lunar EVA. The system operates in two layers. The first grounds a large language model with structured context: EVA procedure documents, live telemetry data, and error-handling protocols encoded as JSON. The second restructures that output into three compact units for AR display: Goal, Task, and Verification. Evaluated on 111 synthetic EVA scenarios, the system scores 10.0/10 on nominal conditions and 8.15/10 on single-fault scenarios, with performance degrading on multi-fault and bo

---

### [217] What the Reranker Sees: Multi-Aspect Page Annotation for Long-Document Multimodal Question Answering

**链接**: https://arxiv.org/abs/2608.14841
**作者**: Guanchen Wu, Jiayuan Ding, Subhabrata Mukherjee, Carl Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-document visual question answering (VQA) over documents of tens to hundreds of pages mixing text, tables, charts, and figures typically follows retrieve-then-read pipelines. In our setting, the bottleneck shifts from retrieval recall to reranker-side evidence selection: on MMLongBench-Doc, BGE-M3 reaches Recall@20 = 0.86 but only F1@5 = 0.254, and even the visual retriever ColPali reaches only F1@5 = 0.332; a text-only rerank LLM seeing only raw snippets misses table, chart, and layout evidence even when the upstream retriever encoded images. We propose Trident, with two complementary components: Trident-R, a retriever-agnostic LLM reranker that converts each candidate into an LLM-readable semantic record, including a visual caption, section path, entity tags, multi-axis concept hits, and a text snippet, then performs a single adaptive-K rerank call; and Trident-S, a generation-side module that prompts the VLM under topical, entity, and structural lenses before synthesis. On two l

---

### [218] Palmyra x6 Technical Report: An Agentic, Tool-Use Model Post-Trained via Anchored Supervised Fine-Tuning

**链接**: https://arxiv.org/abs/2608.16620
**作者**: Peng Du, Kiran Kamble, Rakshith Vasudev, Zhizhuo Yang, Rohith Nadimpally, Arjun Krishna 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Palmyra x6 is a large language model optimized for use with enterprise-oriented agentic tasks. The model was built by post-training a Mixture-of-Experts base model with Anchored Supervised Fine-Tuning on a compact corpus of verified, synthetic tool-use trajectories, optimized with a Muon + Adam hybrid. The recipe is deliberately conservative and deliberately controlled: 626 trajectories, a single epoch, a low learning rate, and a KL anchor to the frozen base. The model shows substantial gains over the previous default model for Writer Agent, and compares favorably with several recent models on public benchmarks, scoring the highest on BFCL Core at $0.785$ and posts the highest six-benchmark mean of the cohort. Furthermore, the model has shown itself to be competitive or leading relative to comparators in our bias and safety evaluations.

---

### [219] QUASAR: Lowering the Loss Floor of Quantization-Aware Training with Loss-Aware Reconstruction

**链接**: https://arxiv.org/abs/2608.13966
**作者**: Vincent Counathe, Ben Athiwaratkun, Christopher De Sa, Tianyi Zhang
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model inference shifts toward lower precision, post-training quantization (PTQ) becomes increasingly brittle, making quantization-aware training (QAT) essential for preserving model quality. However, QAT computes the loss and surrogate gradients using a lossy reconstruction of latent full-precision weights, while applying updates to the latent weights themselves. This mismatch can lead to suboptimal training trajectories and a higher loss floor. Second-order PTQ methods mitigate a similar gap by minimizing loss-aware reconstruction error, but doing it once for a frozen model can take hours; repeating this process throughout QAT as the weights evolve is impractical. We introduce QUASAR, a QAT method that continuously performs lightweight, loss-aware reconstruction in the training loop to lower the loss floor and improve the resulting low-bit model. At each training step, QUASAR uses the exponential moving average of squared gradients as online saliency estimates, searc

---

### [220] Buy the Rumor, Sell the News: When Is News Priced In?

**链接**: https://arxiv.org/abs/2608.14014
**作者**: Alireza Kargarzadeh, Nariman Khaledian, Navid Parvini, Sid Ghatak, Arman Khaledian
**来源**: cs.AI cs.LG q-fin.ST
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two old market sayings hold that news is already priced in by the time it is published, and that the rumor is bought while the news is sold. Both place the price move associated with a piece of news before and at publication rather than after it. Whether the claims hold, for which kinds of news, and by how much are basic questions about how fast markets absorb public information. We test them on 4.57 million financial news articles covering roughly 3,000 US stocks (2023-2026). A large language model teacher, distilled into a compact classifier through active learning, assigns each article one of 17 event tags and five attributes; articles are clustered into stories to separate first reports from follow-up coverage; and beta-adjusted abnormal returns are measured around the resulting 1.68 million stock-day events, with 364,405 neutral-sentiment events as a placebo group. Three results follow. First, the price move associated with news concentrates before and at publication: pooled acros

---

### [221] HERMES: a multi-agent framework for structured knowledge extraction from ultra-long documents in geoscience

**链接**: https://arxiv.org/abs/2608.14055
**作者**: Ziqi Song, Zongyuan Xiang, James G. Ogg, Bruce S. Lieberman, Gabi Ogg, Natalia L\'opez Carranza 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Authoritative scientific knowledge in geoscience remains largely trapped in legacy monographs and historical literature, where unstructured text and complex layouts hinder computational access. We introduce HERMES, a scalable multi-agent framework that extracts structured data from ultra-long scientific documents. Using a coordinating large language model, HERMES integrates domain constraints, validation rules and evidence tracing within a unified document-level extraction process that incorporates parsed text, tables, figures and captions. Applied to the 55-volume Treatise on Invertebrate Paleontology, the system produced a structured database of 32,277 fossil taxonomic entities and 451,878 attributes, released online at https://treatise.geolex.org. Extraction performance remained stable across fossil groups (average F1 scores of approximately 0.90 for entities and 0.91 for attributes), improving per-volume efficiency approximately sixfold relative to the tested fully manual baseline.

---

### [222] TAHB: A Comprehensive Benchmark for Text-Attributed Hypergraph Learning

**链接**: https://arxiv.org/abs/2608.15055
**作者**: David Yoon Suk Kang, JungHyun Kim, Juhyun Jeon, and Sang-Wook Kim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hypergraphs effectively model higher-order groupwise relationships beyond pairwise interactions, while pretrained language models (PLMs) and large language models (LLMs) provide rich semantic understanding from textual attributes. However, research on combining language models with hypergraph learning remains limited due to the lack of public text-attributed hypergraph benchmarks. To address this limitation, we present TAHB (Text-Attributed Hypergraph Benchmark), the first public benchmark integrating hypergraph structures and raw textual attributes. TAHB contains 10 real-world datasets from four domains - e-commerce, academia, movies, and politics networks - enabling systematic evaluation of text-aware hypergraph representation learning. Experimental results show that TAHB preserves key structural properties of real-world hypergraphs and consistently reproduces performance tendencies observed in existing benchmarks. Furthermore, experiments under both LLM-as-Enhancer and LLM-as-Predic

---

### [223] Plausible but Not Valid: A Psychometric Audit of LLMs as Synthetic Survey Respondents

**链接**: https://arxiv.org/abs/2608.14606
**作者**: Mantas Lukauskas, Viktorija \v{S}arkauskait\.e
**来源**: cs.CY cs.AI cs.CL stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as synthetic survey respondents, but existing evaluations ask whether answers look plausible at the individual level. We argue the right question is psychometric: do LLMs preserve the joint distribution, latent structure, reliability, mediation pathways, and demographic effects of real human survey data? We introduce a Lithuanian organisational-psychology dataset (n=263 employees; Dunham Attitudes Toward Change, UWES-17, Koopmans IWPQ; 68 items, 12 subscales) and condition a 37-model lineup spanning OpenAI, Anthropic, Google, and twelve open-weight families on real respondent profiles under a five-level persona-disclosure ladder, presentation and reasoning-effort ablations, counterfactual demographic swaps (gender, role, education), a cross-language check, and a verbatim-recall memorization probe. The resulting Psychometric Similarity Score (PSS) is anchored against five non-LLM statistical baselines and a held-out human-vs-human ceili

---

### [224] DeMTS: Denoising Trajectories as Multivariate Time Series for Hallucination Detection in Diffusion Language Models

**链接**: https://arxiv.org/abs/2608.14632
**作者**: Xin Zhang, Yili Wang, Yue Tan, Xin He, Yanyu Qian, Yixin Liu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (D-LLMs) have emerged as a promising paradigm for text generation. However, similar to autoregressive LLMs, D-LLMs remain vulnerable to hallucinations, where fluent outputs may contain factually incorrect or unsupported content. Although existing hallucination detection methods for D-LLMs attempt to leverage uncertainty trajectories of the denoising process to better identify hallucination signals, they typically compress the trajectories along either the temporal or token dimension, overlooking the useful information encoded in the complete two-dimensional token-step structure. Consequently, they may fail to capture hallucination-relevant patterns, such as inconsistent convergence and cross-token fault propagation, leading to suboptimal detection performance. To bridge this gap, we propose a D-LLM hallucination detection framework that formulates the Denoising trajectories as Multivariate Time Series over learnable latent variables (DeMTS for short). De

---

### [225] Dear Algo: A Precision-First Agentic Intent Layer for Unified Search and Recommendation

**链接**: https://arxiv.org/abs/2608.15877
**作者**: Rui Wang, Jiazhou Wang, Zheng Wei, Chenglin Lu, Fangcheng Sun, Ivy Sun 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Search and recommendation serve a shared discovery objective but encode intent differently. We study this boundary through Dear Algo on Threads, a deployed product where open-ended requests such as \emph{more NBA news} or \emph{less politics} steer subsequent feed recommendations rather than return a one-shot result list. Its agentic intent layer compiles explicit, inferred, negative, and compound intent into a grounded executable plan, then invokes conventional retrieval and optional semantic or multimodal reranking. The layer shares an intent-to-retrieval contract without requiring one model or serving path across search-like and recommendation-like modes. We evaluate Dear Algo under a precision-first objective. In a blinded audit of 300 public request-item pairs (296 evaluable), a strict categorical LLM-as-a-judge gate achieved 94.4\% exact-Relevant precision [88.8\%, 98.9\%]. Across 72 normalized request clusters, the full configuration produced 7.73 judge-qualified candidates per 

---

### [226] CEDAR-GRPO: Process-Aware Reinforcement Learning for General Abductive Reasoning in LLMs

**链接**: https://arxiv.org/abs/2608.14791
**作者**: Moein Salimi, Danial Parnian, Shaygan Adim, Amirmohammad Ebrahiminasab, Nima Alighardashi, Parsa Gholami 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Abductive reasoning, often characterized as inference to the best explanation, is central to explanation under uncertainty, from everyday sense-making and investigation to scientific discovery. Yet LLM research has mostly studied abduction through narrow, task-specific benchmarks, making it unclear whether observed gains transfer beyond the benchmark family used for training or evaluation. We ask whether RL post-training can improve abduction as a transferable reasoning capability. We introduce CEDAR-GRPO, a process-aware framework that combines final-answer correctness with abductive rewards for evidence coverage and evidence-to-explanation directionality. Four open-weight LLMs are post-trained on a controlled, domain-neutral mixture of abductive hypothesis-generation and hypothesis-selection tasks. We evaluate them on 11 unseen tasks spanning hypothesis selection, missing-fact generation, defeasible inference, long-context investigation, clinical reasoning, code debugging, and non-ab

---

### [227] Amplified Does Not Mean Predictive: Reasoning Behaviors in Thinking Models

**链接**: https://arxiv.org/abs/2608.13760
**作者**: Jean de Dieu Nyandwi, Leena Mathur, Yonatan Bisk, Robert Hawkins, Graham Neubig
**来源**: cs.CL cs.AI cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Which reasoning behaviors are associated with correct answers in reasoning models, and does reasoning-oriented training amplify those behaviors? This distinction is important because reasoning-oriented training can make traces look more deliberative without amplifying the behaviors most tied to model correctness. We quantify this mismatch with Behavioral Lift, a metric that measures how much correctness changes when a behavior is present versus absent in a model's reasoning trace. Across 15 models and 6 benchmarks spanning text-only and vision-language reasoning, we annotate 15,282 traces with a taxonomy whose core behaviors are defined for both LLM and VLM traces. We find evidence for an Amplification-Lift Gap, in which thinking models strongly amplify self-correction, hypothesis testing, and uncertainty acknowledgment, while the highest-lift behaviors are confidence calibration, knowledge alignment, and self-awareness. Confidence calibration is among the strongest positive signals of

---

### [228] Student-ChatGPT Interaction Visible: Designing a Teacher Dashboard for EFL Writing Education

**链接**: https://arxiv.org/abs/2608.13587
**作者**: Minsun Kim, Seon Gyeom Kim, Suyoun Lee, Yoosang Yoon, Junho Myung, Haneul Yoo 等 (10 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a Prompt Analytics Dashboard (PAD) for teachers that can traces student-LLM interactions from EFL writing classes. PAD can show student prompt-response exchanges with LLM chatbot and English essay writing revision histories to support data-informed instruction and visibility in classes. Through two iterative co-design sessions with six EFL instructors, we distilled a compact trace taxonomy (misuse signals, goal-alignment cues, revision effort) and instantiated three interface views (overview, week/outcome filter, drill-down with evidence snippets). This pipeline summarizes potential misuse and alignment at class/cohort levels and attaches micro-explanations to reduce over-surveillance. Instructors reported reduced scanning burden and clearer timing for interventions.

---

### [229] Competing at Every Price Point with Agentic Evolution over a Menu of LLMs

**链接**: https://arxiv.org/abs/2608.16207
**作者**: Andrew Borthwick
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Consider a firm that surveys its competition for a particular agentic task and seeks to offer superior accuracy at every competitor price point. A firm that Pareto-dominated its competitors would leave no rational customer a reason to buy elsewhere. This paper shows a path to this kind of capability via agentic evolution over a menu of LLMs, from training pools of at most 100 examples. Given a priced menu of nine LLM endpoints; brief documentation of the task, objective, and API; a simple seed agent; and an operator-chosen per-problem cost target - usually set at an incumbent's own price - RoboPhD, an evolutionary meta-agent, evolves complete agent programs that attack the public frontiers of two semantically dissimilar tasks point by point: DS-1000 (execution-checked code generation) and PaperFindingBench (LLM-judged scientific document retrieval). Our officially scored submissions hold every Pareto-frontier slot but one on the two tasks' leaderboards, including Pareto domination of b

---

### [230] Handoff-H1: An Orchestrated Vision-Agent System for Material Quantity Takeoff from Construction Blueprints

**链接**: https://arxiv.org/abs/2608.15032
**作者**: Bruno Chicelli, Henrique Alves, Rodrigo Anselmo, Joshua Weinberg, Felipe Lemos, Jan Baryla
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Converting a set of architectural blueprints into a complete material quantity takeoff requires visual perception across drawing sheets, dimensional and multi-hop reasoning, and grounding in construction conventions that the drawings never state. We present Handoff-H1, a takeoff system built from three layers: purpose-built computer-vision models that extract primitives; tool-using agents equipped with image operations and in-house visual-task tools, including CV-model-backed counting, detection and plan decomposition; and a persistent, hierarchically structured project foundation, grounded in a curated construction knowledge base. We evaluate on the Construction Blueprint Takeoff Benchmark: 10 real residential blueprint sets paired with consensus-validated expert takeoffs - 2,009 verified line items, restricted for scoring to the 1,348 primary-tier materials that drive an estimate - scored per trade by an LLM judge on material coverage and quantity Precision@25% (P@.25) and combined i

---

### [231] BengaliMCQ: Automatic Generation and Answer Prediction of Academic Multiple-Choice Questions in a Low-Resource Language

**链接**: https://arxiv.org/abs/2608.15547
**作者**: Abu Tarabin Surzo, A.K.M. Nihalul Kabir, Sm Azmain Faysal, Ariana Haque Ami, Lawrence Amlan Gomes, Farig Sadeque
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional retrieval-augmented generation (RAG) frameworks process documents without attending to their hierarchical structure, leading to poor performance, especially in low-resource languages such as Bengali. To address this, we propose a structure-aware RAG framework that models Bengali textbooks as hierarchical graphs and uses a contrastively trained graph neural network to retrieve a small set of relevant passages. These passages provide focused context for a large language model, enabling topic-specific multiple-choice question (MCQ) generation and in-domain answer prediction. Experimental results demonstrate that our framework outperforms strong dense retrieval baselines across retrieval metrics, produces more relevant MCQs, and achieves superior answer prediction accuracy.

---

### [232] Local AI pre-screening for human triple-blind peer review in health sciences

**链接**: https://arxiv.org/abs/2608.14625
**作者**: Rodrigo Martins Boos
**来源**: cs.CY cs.AI cs.DL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Academic peer review is under mounting strain: NeurIPS 2025 received 21,575 submissions, ICLR 2025 received 11,603, and ICML 2025 received 12,107. This volume has outpaced the supply of qualified reviewers, and large language models (LLMs) are already filling the gap, largely undisclosed. An independent analysis of ICLR 2026 found roughly 21% of its 75,800 peer reviews were fully AI-generated, with over half showing some AI involvement (up from 15.8% in 2024). Documented risks include hallucinated citations in accepted papers and hidden prompt-injection instructions embedded in manuscripts to manipulate AI reviewers into favorable assessments. We propose a triple-blind, multi-LLM pre-screening framework for peer review, developed for a health sciences journal, that formalizes and discloses AI involvement while preserving human reviewers as the final decision-making authority. The framework routes a submission through five stages -- sanitization/anonymization, parallel AI pre-screening,

---

### [233] VARM-Bench: Benchmarking Verifiable Structured Reasoning in Chinese Abusive Speech Moderation

**链接**: https://arxiv.org/abs/2608.15600
**作者**: Mingyu Yuan, Shengtao Wen, Lingbing Guo, Zhen Bi, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The widespread circulation of abusive online content has increased the need for reliable moderation of Chinese social-media text. Existing Chinese benchmarks support label classification, fine-grained toxicity categorization, and target-aware extraction, but do not provide a unified representation for deterministically verifying the stated basis of a moderation decision. We introduce VARM-Bench, a benchmark for field-anchored chain-of-thought rationales in Chinese abusive-speech moderation. Each instance contains a concise natural-language rationale with explicit anchors for six decisions: target, target type, target explicitness, author stance, harmfulness label, and fine-grained category. Our deterministic protocol evaluates field correctness, target alignment, output validity, complete-record agreement, and hidden record errors conditioned on correct final decisions, without relying on an LLM judge. Under a common structured-output protocol, we evaluate language models across multip

---

### [234] The Machine's Internal Clock: Do LLMs Share Human Temporal Illusions?

**链接**: https://arxiv.org/abs/2608.15394
**作者**: Catherine Bao, Vivek Srikumar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human perception of time is subjective. Well-documented temporal illusions show that the brain relies on context and relational cues for judging duration instead of tracking elapsed time directly. Prior studies established these effects with visual and auditory stimuli. Existing LLM evaluations of temporal perception focus on estimating event durations or multi-step temporal reasoning. In this work, we investigate whether written narratives alone can evoke human temporal illusions, using a new benchmark of 6,684 narrative pairs spanning five illusions. We find that human readers (60 participants) prefer expected scenarios in only two of the five illusions, those where the manipulation is directly visible in text rather than requiring readers to internally simulate duration. We evaluate 14 LLMs on the same benchmark. Surprisingly, we find that models pick the literature-predicted scenario across four of the five illusions, diverging from human behavior. Reasoning traces show that ~70% o

---

### [235] PolyDebate: A Game-Orchestrated Multimodal System for Debate Skills Practice and Evaluation

**链接**: https://arxiv.org/abs/2608.16276
**作者**: Jianing Yin, Weng Pan Kuan, Xiaoyun Liu, Zhiyuan Wen, Yuxuan Li, Milos Stojmenovic 等 (7 人)
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Debate is a structured form of persuasive communication that trains argument construction, rebuttal, oral delivery, and audience awareness. These skills are valued in education, language learning, and professional communication. Recent AI debate systems and LLM-based judges have advanced argument generation and debate evaluation, but most remain text-centered and rarely support learners through a complete multimodal practice experience. We introduce PolyDebate, a game-orchestrated multimodal system for English debate practice and evaluation. PolyDebate guides learners through staged one-on-one (1v1) debates with an AI opponent, while skill cards, props, and coins make persuasive strategies explicit and turn practice into a game-like interaction. During each session, the system captures learner speech and visual delivery evidence, generates context-aware opponent responses, and produces rubric-informed stage-level and overall feedback. PolyDebate is available as both an immersive Unity 

---

### [236] MAPLE: MoE Adaptive Plug-and-play Layer-wise Expert allocation

**链接**: https://arxiv.org/abs/2608.15299
**作者**: Lie Li, Wen Li, Junxiao Shen, Gusheng Hu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparsely-activated Mixture-of-Experts (MoE) Transformers universally fix the same number of routed experts across all layers, a convention that ignores the well-documented heterogeneity in layer-wise redundancy. We demonstrate that this uniformity is systematically suboptimal and propose MAPLE, a plug-and-play framework that reallocates the routed-expert budget heterogeneously across layers of any pretrained MoE LLM, without modifying weights or requiring retraining. Our core contribution is a closed-form sensitivity-guided allocation: we probe each layer's response to variation in expert count, quantify sensitivity using three measures, and derive an analytically optimal budget assignment that directs capacity towards sensitive layers and absorbs reductions in redundant layers. This closed-form solution is further refined by a sensitivity-constrained genetic search that uses layer-wise sensitivity as a prior to guide exploration, yielding faster convergence and superior allocation qua

---

### [237] Beyond Asking: A Pipeline for Personalized Game Generation that Reads Players from Behavior

**链接**: https://arxiv.org/abs/2608.16196
**作者**: Yifan Lu, Xiaopeng Yuan, Haohan Wang
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized game generation requires inferring a player's abilities and behavioral style from how they play. Large language models have made this inference more attainable than ever: an LLM can read a raw gameplay transcript and produce a fluent, plausible profile of the player. Plausible, however, is not verified, and verification is precisely what the field lacks: latent traits are unobservable; questionnaires provide noisy proxies and become circular when self-reports are used to validate behavior-based inference; and behavior itself is ambiguous without context -- a player who never collects an item may not want it, or may never have had the chance. We address both problems. First, we construct a synthetic player population whose traits are ground truth by construction: each trait is an explicit bot parameter, accepted only after controlled manipulation produces consistent, trait-specific behavioral change. Unlike prior parameter-recovery work that inverts a known decision model, 

---

### [238] Evaluating Agentic Code Repair Capabilities in Distributed Systems

**链接**: https://arxiv.org/abs/2608.14863
**作者**: Yibo Yan, Huijuan Wang, Junzhou He, Yizhuo Liang, Shaoyu Wang, Huanchen Sun 等 (7 人)
**来源**: cs.SE cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based coding agents have advanced rapidly on single-process SWE tasks, with frontier models now clustering in the high-70s on SWE-bench Verified. Distributed-system debugging, however, remains an under-explored regime: bugs span processes, nodes, and protocol interactions, with root causes rarely recoverable from source alone and brute-force exploration intractable across non-deterministic interleavings. This leaves two gaps in LLM and agent evaluation: no code-repair benchmark targets distributed-system bugs, and no controlled study isolates how much externally provided debugging context changes agent success on them. We introduce DDBench, a code-repair benchmark of 60 historical bugs mined from 13 open-source distributed systems, partitioned into three difficulty tiers. DDBench evaluates every case under two matched conditions: a symptom-only condition where the agent receives only the bug symptom and repository, and a context-augmented condition where it additionally receives a 

---

### [239] RamseyGadgets: A Graph Construction Dataset for LLMs

**链接**: https://arxiv.org/abs/2608.14999
**作者**: Zohair Raza Hassan, Deepak Pandita
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constructing special graphs is an important task within graph theory and computer science. Many popular graph constructions are the result of a comprehensive exploration of relevant graphs and human ingenuity. Given the rise of generative AI usage in mathematics, it is natural to test whether LLMs are able to construct graphs with specified properties using their reasoning capabilities. Unfortunately, many natural graph construction problems, such as finding extremal Ramsey-good graphs (i.e., avoiding specific monochromatic subgraphs), have been explored extensively in the literature, making it difficult to ascertain whether a construction is the product of an LLM's reasoning capabilities or its recollection from training data. In this work, we introduce \textbf{RamseyGadgets}, a novel dataset of 70 underexplored graph construction problems that require finding Ramsey-good graphs with special properties (e.g., containing an edge with a fixed color). These problems have reasonably sized

---

### [240] Beyond Simplification: DFT-GEN for Fidelity-Preserving Visual Accessibility in Dyslexia-Friendly Educational Texts

**链接**: https://arxiv.org/abs/2608.13583
**作者**: Jiaqian Yu, Chen Jason Zhang, Haoyang Li, and Guoqiong Ivanka Huang
**来源**: cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dense educational texts impose avoidable reading friction on people with dyslexia, yet generic simplification can delete terminology, task constraints, or source evidence that readers still need. Stakeholder interviews with dyslexic adults and specialists reveal a core tension: reduced burden must not compromise information fidelity. We present DFT-GEN, a stakeholder-informed text transformation framework for content-heavy educational materials. Its central contribution is not a generic LLM refinement loop, but a dyslexia-specific accessibility layer that combines protected-span preservation with a deterministic Dyslexia Accessibility Controller (DAC) for rendered visual organization. DAC converts stakeholder and expert preferences into reproducible controls for visual-unit length, chunk spacing, source/task separation, highlighting budget, and reviewable risk flags. We therefore separate evaluation into DCFI, a fidelity-safety diagnostic, and B-DVAS-VL, a rendered visual-accessibility

---

### [241] DumpsterCluster: From Dumpster Diving to Serving LLaMA-70B on $60 GPUs

**链接**: https://arxiv.org/abs/2608.14614
**作者**: Zeyu Cao, Xuan Guo, Cheng Zhang, Cheuk Hang Lau, Ilia Shumailov, Yiren Zhao
**来源**: cs.LG cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI datacenters retire functional GPUs, vast quantities of still capable accelerators enter secondary markets. This paper investigates whether these retired GPUs can find a productive afterlife to form a DumpsterCluster that can serve modern LLM inference, and under what conditions such repurposing is economically viable and environmentally sustainable. We physically built a 128-GPU DumpsterCluster from scratch using only second-hand components and ran it for one year. At current market prices (\$22K for the DumpsterCluster vs. \$600K for an 8-GPU B200 system), the economic advantages are substantial. Through pipeline-parallel optimizations, our V100 based DumpsterCluster achieves competitive LLaMA-70B throughput, validating production viability. However, our deployment reveals critical context dependencies. Older GPUs consume significantly more energy per token, making total cost of ownership favorable only in regions with inexpensive electricity. Under grid-average carbon intensity

---

### [242] Beyond Correctness: Toward Automated Novelty Verification with Lean 4

**链接**: https://arxiv.org/abs/2608.14669
**作者**: Ayrton Porto
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence systems applied to mathematics verify correctness but not novelty: an automatically generated theorem can compile in Lean without errors and yet be an already known result. This article presents AViD Journal, a pipeline that receives a LaTeX article, formalizes its statements in Lean 4, and issues a novelty verdict through a decision tree over three dimensions: prior existence in a formal corpus (Mathlib) and an informal one (TheoremSearch and Matlas, with temporal filter and LLM judge), non-triviality via automatic tactics, and structural distance between proofs measured as Jaccard distance over premise sets. Evaluation on papers withdrawn from arXiv due to declared duplication produced a result more informative than any performance measure: the identification of three obstacles that limit the approach regardless of this implementation. First, successful compilation of a Lean file does not guarantee semantic fidelity. Second, the recall ceiling is imposed by th

---

### [243] HarmProfile: Characterizing Harmful Distributions in Frontier LLMs

**链接**: https://arxiv.org/abs/2608.14577
**作者**: Zhouyuan Ma, Yutao Wu, Hanxun Huang, Xiang Zheng, Xiao Liu, Yixin Cao 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier large language models (LLMs) safety evaluation has largely treated harmful generation as an attack outcome rather than as an object of analysis. Consequently, little is known about the harmful outputs produced during model misbehavior, partly because large-scale, high-quality collections of frontier-LLM misbehavior are difficult to obtain. To address this gap, we introduce HarmProfile, a content-centric benchmark dataset that collects model misbehavior across diverse harm categories and model families, and defines the resulting harmful-output distribution as a model-level risk profile. The premise is that, just as linguistic behavior can be characterized from an utterance corpus, model risk can be characterized from the content, severity, and variation of its safety failures. HarmProfile contains over 80,000 validated artifacts from 23 frontier LLMs across 13 model families, organized into 15 harm categories and 57 subcategories. Using this corpus, we find that frontier LLMs r

---

### [244] Reconstruction: A Blind Benchmark for Recovering Research Ideas from Pre-Publication Bibliographies

**链接**: https://arxiv.org/abs/2608.16645
**作者**: Shaolong Chen, Yanlin Fei, Nazhou Liu, Xinmiao Yu, Lei Li, Rahul Thapa 等 (9 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a language model recover the true research idea of a published paper when given only that paper's pre-publication bibliography? We introduce Reconstruction, a blind idea-recovery benchmark that withholds the seed paper and all contemporaneous or future literature, and asks models to propose hypotheses that an independent large language model judge matches against the held-out ground-truth idea. A strict anti-leakage protocol-temporal citation cutoff, anonymous reference IDs, and frozen per-paper bibliographies, which prevents prompt-time leakage of the seed idea. Across six scientific domains and 643 evaluated papers, seven frontier models achieve only modest Match rates (approx. 3-15%). We then evaluate a reference-only multi-agent (top 4) pipeline that combines cross-model review with a Swiss tournament over aligned hypothesis slots, without external web search. Cross-model review plus tournament selection raises Match rates to approx. 23-42% across all six domains, which is an o

---

### [245] Token Distribution versus Data Volume: Domain Balancing in Multi-Domain Meeting Summarisation

**链接**: https://arxiv.org/abs/2608.15935
**作者**: Ashima Sood, Bryan Gardiner, Joan Condell
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jointly fine-tuning an LLM on meeting-summarisation corpora of widely varying size raises a question that prior work leaves confounded: when a domain-balanced training mixture helps, is the gain due to the distribution of tokens across domains, or merely to the volume of data seen? We disentangle these factors by constructing balanced and natural (native-proportional) token mixtures at matched token budgets (2-32M) over five English meeting corpora, fine-tuning Mistral-7B with QLoRA, and evaluating per domain. Balancing redistributes quality, improving the data-scarce minority domains at a low cost to the data-rich ones. The trade favours balancing whenever the minority domains matter: their share under proportional allocation is fixed at 1-2% regardless of budget, so matching balanced quality on those domains requires far more total data. We further find that pruning low-value transcript lines removes ~15% of tokens from the conversational corpora at no measurable cost, and that balan

---

### [246] ReRef-3D: A Benchmark for Spatial Referring Expression-Guided 3D Scene Rearrangement

**链接**: https://arxiv.org/abs/2608.16011
**作者**: Mary Lynn Martin, Yifei Zhang, Martha Palmer, Maria Leonor Pacheco
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce ReRef-3D, a benchmark for language-guided placement in 3D scenes. It contains 33,826 instructions across 998 CLEVR-derived scenes, spanning 16 placement families and direct, one-hop, and two-hop references. Each instruction must be resolved into a valid new placement position. Given that an instruction defines a region of acceptable placements rather than one coordinate, our evaluation inserts a prediction into the scene, recomputes relations, and tests relation satisfaction and physical validity. Each instruction also includes a verified naturalized rewrite. After fine-tuning, LLaVA-3D, 3D-LLM, and PlaceIt3D produce valid placements for 68.3%, 31.6%, and 22.4% of instructions, respectively. Across models, relation satisfaction surpasses physical validity, relations such as nearest and between are the most difficult, and phrasing has minimal effect on performance.

---

### [247] ACTS-SQL: Agentic and Critic-Oriented Tree-Structured SQL Correctness with Large Language Models

**链接**: https://arxiv.org/abs/2608.15145
**作者**: Xinmei Huang, Jie Song, Peng Li, Fuxin Jiang, Jing Zhang, Tieying Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have been increasingly adopted in Text-to-SQL systems, yet SQL errors remain a major obstacle in real-world Text-to-SQL inference pipelines. Existing SQL correction approaches either rely on large-scale, high-quality training data with substantial overhead, or adopt single-path agentic workflows that are brittle to early mistakes and prone to error propagation. To develop a practical SQL correctness system for industrial scenarios, we present a training-free framework that formulates SQL correction as a plan-guided, tree-structured debugging process. By maintaining multiple correction strategies and enabling backtracking, the framework mitigates error accumulation during iterative refinement. We further integrate execution-based verification and clause-level diagnostic tools to support strategy pruning and precise error localization. We evaluate the system on the BIRD-Critic benchmark and observe consistent accuracy gains over strong LLM backbones and repre

---

### [248] Towards Risk-free AI Agent Deployment

**链接**: https://arxiv.org/abs/2608.16411
**作者**: Yintong Huo, Rangeet Pan, Abhik Roychoudhury
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are rapidly moving from research prototypes into the core business processes of organizations, but these agents pose deployment risks to security, compliance, and functionality. In this article, we argue that risk-free deployment must be grounded in the agent's trajectory: the recorded sequence of reasoning steps, tool invocations, and environmental observations. Trajectories are available for any agent, and many failures are visible only in the trajectory. To make agents deployable and sustainable, we advocate agent testing and debugging as a systematic research direction for detecting and mitigating these risks. This article begins with the challenges of testing agents, including the oracle problem, non-determinism, trajectory validation, and the absence of adequacy metrics. We then turn to debugging agents, from automated failure attribution to repair and self-evolution. We distill these directions into a practical deployment-readiness checklist covering the full de

---

### [249] SkillComposer: Learning Reusable Skills for Natural-Language Robot Programming

**链接**: https://arxiv.org/abs/2608.14944
**作者**: John Woods and Hasti Seifi
**来源**: cs.RO cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language interfaces can lower the barrier to programming robots, but existing systems struggle when users request complex tasks. While large language models (LLMs) perform well with simple commands, they often struggle to generate code for multi-step tasks, decompose high-level instructions, or reuse prior solutions. We present SkillComposer, an interactive natural-language robot programming system for simulation environments that continually learns reusable program abstractions. SkillComposer uses a generate-test architecture in which an LLM iteratively generates and revises robot programs before execution. Successful programs are stored and processed by an online library-learning algorithm that compresses recurring function sequences into reusable macro skills for future tasks. We evaluate SkillComposer through ablation experiments and a user study with 12 participants to determine its effectiveness on manipulation and robot caregiving tasks. The results show that evaluator-g

---

### [250] Asymmetric Discourse Homogenization and Shared Language Technology: Evidence from Reddit

**链接**: https://arxiv.org/abs/2608.13674
**作者**: Fengming Liu
**来源**: cs.CY cs.CL cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> I document an ideologically asymmetric break in the pre-existing diversification trend of political discourse, emerging around late 2022, using 6 million Reddit comments from two cross-partisan forums, 2019-2025. Conservative users experienced an interruption of their prior diversification trajectory; progressive users showed no comparable change. The asymmetry is consistent across estimation strategies (ITS, DiD, RDiT, propensity-score matching) and temporal aggregations. A daily-frequency permutation test over 2,377 candidate cutoff dates shows the ChatGPT threshold produces an unremarkable estimate (49.8th percentile): the shift builds gradually instead of breaking at a single date. A continuous cumulative LLM index, tracking AI exposure across seven model releases, remains significant under a quadratic trend specification that eliminates the binary estimate. A stayer analysis narrows the mechanism: the homogenization effect disappears when the sample is restricted to authors active

---

### [251] Schema-Agnostic Graph Reasoning Agent for Hybrid Knowledge Graphs

**链接**: https://arxiv.org/abs/2608.15834
**作者**: Marius Dragic, Ruben Ifrah and Alexandre Rio
**来源**: cs.AI cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-calling LLM agents navigate unfamiliar codebases with a handful of generic primitives for listing, reading and searching files (ls, cat, grep). A knowledge graph admits the same interface: listing neighbours, reading node content and searching descriptions are the same operations on a different substrate. Building on this correspondence, we present GRA, a Graph Reasoning Agent that explores hybrid knowledge graphs, whose nodes are either textual concepts or relational tables, with seven generic tools, discovering everything domain-specific at run time. On UFK-M (Unified Factory Knowledge Model), an industrial benchmark of 258 analytical questions whose gold answers are produced by executing validated SQL programs, GRA beats a full-context agent by 5.1 pp (88.4% vs. 83.3%), while reading under a third of its input tokens. A graph-free control shows the gain comes chiefly from selective agentic access rather than graph topology, and that the effect depends on a model able to drive t

---

### [252] Clause Encounters of the Third Kind: Can LLMs Replace Language Teachers?

**链接**: https://arxiv.org/abs/2608.16286
**作者**: Kristina \v{S}ekrst, Ana Kova\v{c}i\'c
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While various organizations now actively encourage LLM use in classrooms, we still lack rigorous, systematic evaluations of how well these models actually perform the fundamental tasks of language pedagogy. This paper examines whether state-of-the-art LLMs can deliver the kind of corrective feedback and methodological explanations that language learners need. The study tests multiple large language models on their ability to identify, correct, and explain common learner mistakes in English, by systematically varying model parameters to investigate how these technical adjustments affect output quality, pedagogical clarity, and consistency, along with using retrieval-augmented generation to query methodological data. The evaluation employs automated metrics (GLEU, BERTScore) but also human expert judgments to capture dimensions that purely computational measures miss: linguistic nuance, cultural sensitivity, and instructional appropriateness. While models demonstrate impressive surface-l

---

### [253] Never the Number: Structural Abstention for AI Systems Whose Answers Are Consumed as Fact

**链接**: https://arxiv.org/abs/2608.13926
**作者**: Zhelun (Allen) Wu
**来源**: cs.AI cs.CL cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have made natural language interfaces to databases (NLIDB) newly credible, but LLM text-to-SQL systems fail in a way that matters for deployment: a hallucinated column or a mis-aggregated total yields a fluent wrong answer, indistinguishable at the point of use from a right one. Where the consumer cannot inspect the generated query, as in enterprise AI deployments and operational dashboards, and increasingly where the consumer is a tool-using agent rather than a person, accuracy alone is insufficient: nothing marks which answers to distrust. This is a reliability problem before it is an accuracy problem. We propose an architectural pattern for such systems, a trusted kernel with a generative shell, resting on one invariant: a component that can fabricate may influence which question the system answers, never which value it returns. A generative shell interprets underspecified input and phrases replies; a deterministic kernel matches fully specified questions again

---

### [254] Anatomy of a Quantized Agent: VRAM Stability and Forecasting in Code-Synthesis Agentic Workloads

**链接**: https://arxiv.org/abs/2608.15117
**作者**: Anubhab Banerjee
**来源**: cs.AI cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analytical models of peak VRAM consumption for LLM inference decompose memory into weight-storage, KV-cache, and activation terms parameterized by step count, tool invocations, and context expansion. We evaluate this decomposition empirically within a strictly scoped measurement study: a LangGraph-based CUDA-kernel-synthesis agent (AgentK), a 4-bit quantization family (Q4 K M), a single NVIDIA H100 GPU, and four LLM backbones across 1,920 trajectories. Focusing on peak-memory forecasting behavior, we report two primary observations. First, closed-form analytical models achieve competitive accuracy when provided with two empirical constants: loaded-weight VRAM and a fixed activation-memory overhead. Supplied with live GPU readings and ground-truth trajectory parameters, the closed-form model matches or outperforms the best learned baseline on three of the four backbones (test MAPE 2.2-4.4% vs. 3.4-6.5%, p = 0.76). The exception is the smallest backbone (Phi-4-mini), where minimal VRAM v

---

### [255] An Agentic Framework Using Rules and LLMs for Embedding and Annotating Descriptive Document Layouts: A Plant Science Use Case

**链接**: https://arxiv.org/abs/2608.14587
**作者**: Nicolas Turenne, Youcef Sklab, Eric Chenin, Jean-Daniel Zucker
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Recent advances in information retrieval (IR) leverage both dense and sparse representations, large language models (LLMs), and specialized retrieval models to improve ranking accuracy, relevance, and cross-lingual performance. Complementary techniques such as passage indexing, document layout analysis, and semantic knowledge representation further enhance retrieval effectiveness by capturing fine-grained contextual and structural information. Emerging agentic LLM frameworks extend these capabilities by enabling planning, iterative reasoning, tool use, and multi-agent collaboration, thereby broadening applications across diverse domains. These frameworks also emphasize rigorous evaluation, ethical considerations, and trustworthiness, ensuring responsible deployment in real-world settings. We propose a modular, agent-based pipeline for botanical trait extraction. Optical character recognition (OCR) converts PDFs into machine-readable text, while segmentation and indexing org

---

### [256] MegaParts: Scaling Part-Aware 3D Object Generation to 300 Parts via Token-Efficient Autoregressive Modeling

**链接**: https://arxiv.org/abs/2608.14783
**作者**: Manwen Liao, Xinyu Lian, Jian Mao, Kaixu Chen, Li Luo, Jinghao Yan 等 (10 人)
**来源**: cs.CV cs.GR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Part-aware 3D object generation is essential for graphics applications such as controllable modeling, editing, and articulation, where objects are represented as coherent assemblies of semantic parts. However, existing part-aware generation methods, do not scale well to highly complex objects. As the number of parts increases, generating detailed geometry becomes prohibitively expensive in token length and memory. We introduce MegaParts, a scalable autoregressive 3D generation framework to address this challenge by combining structured sequence modeling with a token-efficient vector-quantized shape tokenizer. Our tokenizer learns discrete latent representations for part-level geometry by minimizing token usage subject to high-fidelity reconstruction, enabling adaptive-length tokenization based on geometric complexity. On top of this compact representation, we train a large language model to generate object bounding boxes, part bounding boxes, and part shape tokens within a unified stru

---

### [257] VoiceChat-TTS: A Low-Latency Continuous Speech Synthesis Model for Interactive Agents

**链接**: https://arxiv.org/abs/2608.13831
**作者**: Edresson Casanova, Jaehyeon Kim, Mariana Graterol Fuenmayor, Shehzeen Hussain, Viacheslav Klimkov, Valentin Mendelev 等 (10 人)
**来源**: eess.AS cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spoken dialogue is a natural form of human--computer interaction, yet most speech language models remain limited to turn-based operation and lack real-time adaptability, such as user barge-in. Recent duplex speech-to-speech and speech-to-text models reduce latency by replacing multi-stage pipelines, but often compromise speech quality because accurate ASR, interruption handling, and high-fidelity synthesis must be optimized jointly. We propose VoiceChat-TTS, a low-latency, continuous, and streamable text-to-speech model for interactive agents. VoiceChat-TTS is driven directly by LLM text-token streams, supports explicit interruption via control tokens, and produces silence when no textual input is available. The model enables always-on, responsive speech generation while preserving modularity and high speech quality, and it supports mid-utterance interruptions without resetting the KV cache.

---

### [258] Grounding Without Corrective Control: Truth-Tracking Profiles for Large Language Models

**链接**: https://arxiv.org/abs/2608.14252
**作者**: Brett Reynolds
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work suggests that some large language model representations have content or reference. Grounding can secure either without supplying live routes for correction. This paper asks what follows from that gap. An output is answerable when discrepancies can affect what a target- and task-specific arrangement produces, accepts, or withdraws. The arrangement has corrective control only when live, sufficiently independent routes can detect and repair fresh discrepancies. A route profile records which routes constrain the arrangement and how they are related. Those profiles support analysis of truth-tracking: patterned support for representational success. Language models are the pressure case; text-only arrangements provide a task-relative limiting case. Text-trained models inherit patterns of testimony, coherence, and prior correction. Where target-sensitive correction survives training, these can supply derivative answerability (inherited constraint); live answerability is the relatio

---

### [259] Navigation-Informed Embeddings: Dense-Retriever Adaptation from Agent Search Traces

**链接**: https://arxiv.org/abs/2608.15956
**作者**: Shrey Shah and Levent Ozgur
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic retrieval workflows produce query, retrieval, and stopping traces as a byproduct of answering questions. We study how these traces can adapt a deployed dense retriever to changing workflow distributions without new relevance labels, synthetic queries, or LLM judgments. We introduce Navigation-Informed Embeddings (NIE), a family of trace-derived objectives. NIE-Stop turns the stopping document into a soft positive; NIE-Path additionally uses preceding path documents as hard comparisons and imposes ordinal constraints with geometric decay. A BGE encoder adapted from retained source trajectories improves support Recall@20 on an independent target benchmark from 72.2 to 78.0 overall. NIE-Stop reaches 76.9 overall and 52.3 on long paths; NIE-Path raises long-path performance to 55.4, compared with 46.7 for the unadapted encoder. A shuffled-order control under the full path objective loses 3.2 points. Without public-benchmark training, the same adapter also improves nDCG@10 by 1.9 po

---

### [260] Evolving Executable Pipeline Programs for AutoML with Language Models

**链接**: https://arxiv.org/abs/2608.16416
**作者**: Sofoklis Kitharidis, Cor J. Veenman, Jan N. van Rijn, Thomas B\"ack, Niki van Stein
**来源**: cs.LG cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated machine learning (AutoML) systems search for pipelines within a space of preprocessing operators, learners, and hyper-parameters specified in advance: they can select and tune known components, but cannot produce structure outside that space. We present LACE, an AutoML framework that instead searches over complete executable pipeline programs: an evolutionary loop maintains a population of scikit-learn-compatible Python classes, and a large language model acts as the variation operator. To our knowledge, LACE is the first to formulate general tabular pipeline AutoML this way, evaluated on standardized OpenML tasks under a leakage-controlled protocol that withholds dataset identity from the generator. Because every candidate is ordinary Python, the returned pipeline and the search that produced it can be inspected and edited directly, rather than only through a framework's model objects. On 68 OpenML classification tasks, LACE with GPT-5.4-mini significantly outperforms auto-s

---

### [261] Kozuchi Agent: A Language-Agnostic Open-Weight Agent for Software Repair

**链接**: https://arxiv.org/abs/2608.15579
**作者**: Mehdi Bahrami, Kosaku Kimura, Satoshi Munakata, Satoshi Nakashima, Yu Ishikawa, Kosuke Maeda 等 (10 人)
**来源**: cs.SE cs.AI cs.ET cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial software-engineering teams increasingly need LLM agents that turn bug reports into correct patches, yet benchmark-scale operation adds long horizons, tool-use discipline, context persistence, heterogeneous clusters, and evaluation reuse. We present Kozuchi Agent, a language-agnostic open-weight repair agent and CI-operated evaluation pipeline. Explicit phases, persistent state, deterministic tools, a model-independent action interface, and cross-agent test-time selection make runs auditable and repeatable. With locally hosted Qwen3.5-27B, no fine-tuning, and TTS@8, Kozuchi resolves 374/500 SWE-bench Verified instances on the official evaluator. Unchanged on Multi-SWE-bench Java, the same 27-billion-parameter agent resolves 41/128 instances (32.03%), ranking first among strict open-weight submissions and fourth of 42 overall; on Python it ranks 12th of 135 and first among open-weight systems. Per-phase behavior remains within +/-5 percentage points across languages. Remaining

---

### [262] BiasTrace: Linking Reasoning Behaviours to Biased Outputs in LLMs

**链接**: https://arxiv.org/abs/2608.14161
**作者**: Varsha Ramineni, Hossein A. Rahmani, Jerome Ramos, Karin Sevegnani, Emine Yilmaz
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs exhibit social biases that can produce inaccurate and discriminatory inferences, posing risks in high-stakes applications. While prior work has made progress in measuring and mitigating bias, it largely focuses on final outputs of models, with limited understanding of the mechanisms that produce biased outcomes. Recent advances in LLM reasoning offers a new lens for investigating bias, yet the link between reasoning and bias remains poorly understood. Existing approaches focus primarily on final answer correctness or explicitly biased language, overlooking different behaviours in reasoning that can drive biased outcomes. We introduce BiasTrace, an annotation scheme for labelling reasoning behaviours in model-generated traces and linking them to biased outcomes. BiasTrace captures bias-specific behaviours (e.g., unsupported demographic assumptions) as well as general reasoning patterns that may implicitly contribute to bias (e.g. overthinking). We apply BiasTrace to reasoning trace

---

### [263] Evaluating Agentic Learning Harness Capabilities Without Labels via the Scaling Hypothesis

**链接**: https://arxiv.org/abs/2608.13608
**作者**: Aryan Luthra, Kshitij Jain, Siddharth Arya, Bobby Filar, Anna Bertiger
**来源**: cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic "Continual Learning Harnesses", systems that pair an LLM with retrieval or memory to improve from feedback without retraining, have shown growing value in cybersecurity. But their value is conventionally measured by gains against labeled benchmarks, an approach that often fails in operational security settings. Benchmark labels are scarce, stale, and unrepresentative, so a practitioner often cannot tell whether a given harness helps at all or which of two is better for their task. Traditional LLM-as-a-judge offers little signal because it is no stronger than the agent it evaluates, and distillation is unreliable on scarce, sporadic, and biased labels. We propose a framework for evaluating learning harnesses end-to-end without a labeled benchmark, grounded in the scaling hypothesis. A stronger teacher model provides sparsely sampled corrections to a smaller student with a continual learning harness. We score a harness by how much its student converges toward the teacher over tim

---

### [264] Learning Agent Execution for KV-Cache Management in Agentic Serving

**链接**: https://arxiv.org/abs/2608.14624
**作者**: Rui Zhang, Chaeeun Kim, Shaoting Feng, Kuntai Du, Yuhan Liu, Yi Zhong 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems have emerged as an important deployment paradigm for AI services, where each user request is decomposed into a sequence of specialized agents. Across these workflows, every agent repeatedly executes a fixed context consisting of system prompts, tool definitions, and few-shot examples, creating substantial opportunities for KV-cache reuse. Existing LLM serving systems, however, manage KV-cache reactively using prefix caching and recency-based replacement, causing reusable agent contexts to be evicted before their next invocation and forcing repeated recomputation. We present CacheScout, an agent-aware KV-cache runtime layer for multi-agent LLM serving. The key insight is that future KV-cache reuse is governed by agent execution semantics rather than cache recency alone. CacheScout captures these semantics by learning agent execution transitions online, without requiring predefined workflow graphs or offline training, and uses the learned execution model to guide 

---

### [265] Augmenting Text to Increase Translation Difficulty

**链接**: https://arxiv.org/abs/2608.15932
**作者**: William Kalikman, \v{S}imon Sukup, Michal Te\v{s}nar, Vil\'em Zouhar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As state-of-the-art machine translation models saturate standard benchmarks, the field needs more challenging evaluations to distinguish between models of varying quality. We propose augmenting existing benchmarks to increase translation difficulty by combining adversarial optimization with a differentiable translation difficulty estimator. Our Adversarial Translation Optimization (ATO) uses gradients from a combined difficulty and fluency objective to iteratively replace tokens. Because each step branches over candidate substitutions at every position, optimization becomes a tree search problem, which we address with Beam Search. ATO offers a gradient-based alternative to LLM-based dataset creation without LLM prompting, expensive human curation, or task-specific model training. Our ATO-modified benchmark lowers average translation quality (xCOMET) from 0.93 to 0.82, compared to 0.88 for paraphrasing and 0.86 for a zero-shot baseline. Human evaluation shows the modified texts are some

---

### [266] Grounding Healthcare LLMs in a Causal Knowledge Graph: Framework, Metrics, and a Cardiovascular Pilot

**链接**: https://arxiv.org/abs/2608.15382
**作者**: Ummara Mumtaz, Aimen Noor, Awais Ahmed
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly proposed for healthcare decision support, but their evaluations still reward single-answer accuracy rather than reasoning about interventions, mechanisms, harms, evidence, and uncertainty. We propose a reproducible, graph-centered evaluation framework for intervention-oriented LLM behavior in healthcare and stress-test it in a cardiovascular pilot. The framework has four components: (i) a domain causal knowledge graph in which assertions are first-class, provenance-preserving nodes with stable identifiers; (ii) a scenario-conditioned subgraph extraction step that, given any clinical scenario, retrieves the relevant reified-assertion subgraph; (iii) four controlled grounding conditions that vary how the retrieved subgraph is composed into the model's context (ungrounded C1, knowledge-graph C2, causal-graph C3, integrated C4); and (iv) an automated scoring pipeline, anchored on assertion identifiers, that computes intervention accuracy, and o

---

### [267] Position: AI Agents in Scientific Teams Should Be Studied as Human-Agent Systems

**链接**: https://arxiv.org/abs/2608.14667
**作者**: Patrick Emami, Sameera Horawalavithana, Truc Nguyen, Gihan Panapitiya, Bruno Jacob, Siddhisanket Raskar 等 (10 人)
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based agents are increasingly deployed as collaborators in scientific discovery yet most current work focuses on the autonomous capabilities of "AI Scientists". We argue that this overlooks the social aspects of scientific teamwork, and that studying AI Scientists as human-agent systems (HAS)--where the unit of analysis is the human-agent pair--is both underexplored and undervalued. We establish these points through literature and empirical analysis, and highlight recent incidences and studies which show that deploying agents in science without accounting for human-agent dynamics introduces near-term risks, including reduced diversity of scientific inquiry. Through analysis of real-world case studies, we show that scientists and agents can augment each other's capabilities. We call for new research that adopts the HAS lens to develop mathematical frameworks for understanding and fostering human-AI synergy in scientific discovery.

---

### [268] Domain Agnostic Text Redaction from Natural Language Rules using Instruction Tuning

**链接**: https://arxiv.org/abs/2608.14693
**作者**: Aravindhan Arunagiri, Ayaan Khan, Udayaadithya Avadhanam, SaiBarath Sundar
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the increasing digitization of personal and corporate communication, the automatic sanitization of textual data has become a crucial component of data privacy and compliance frameworks. Traditional text sanitization solutions are majorly suitable for obscuring sensitive data with standard structure such as Personal Identifiable Information (PII). These solutions do not provide transparent justification for their redaction, which makes it difficult to audit them. This paper introduces an explainable, domain-agnostic text redaction solution that uses natural language rules of redaction, applied via an instruction-tuned language model, to identify and redact sensitive information in unstructured documents. Unlike traditional text sanitization, this method enables a user to conveniently define any sensitive information; which may be structured (e.g.\ PII) or unstructured (e.g.\ legal terms and conditions) in natural language. A general-purpose LLM generates or augments these natural l

---

### [269] Comparative Analysis of Interpretive Divergence in Externally and Regionally Trained Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11632329/&hl=zh-CN&sa=X&d=5235260092841151179&ei=V2SCauOxJtGhieoPpP7auQM&scisig=AIVdB-wbHH6Q6OVcGRGyLdpfwW5h&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=2&folt=kw-top
**作者**: A Vance, TR Vance - 2026 ITU Kaleidoscope-AI and Frontier Technologies …, 2026
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> , multi - model evaluation methodology designed to identify interpretive divergence (ongoing research refers to this as “LLM dissonance”) between Arabic-first and Western-trained large language models when … on Western-trained large language

---

### [270] Designing Mobile and Wearable Sensor-Fused Conversational Agents for Health and Wellbeing

**链接**: https://arxiv.org/abs/2608.14273
**作者**: Hansoo Lee, Pablo Fonseca, Md Haseen Akhtar
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile and wearable devices increasingly collect continuous wellbeing data, including sleep, activity, heart rate, stress, blood glucose, and blood pressure. Yet access to such data does not automatically help people interpret their condition or change behavior. Many health applications remain dashboard-first, presenting charts, thresholds, goals, and alerts while leaving users to decide what a change means and what action should follow. Conversely, generic LLM-based conversational agents (CAs) can provide fluent advice, but without personal sensor grounding, they cannot detect individualized patterns or provide contextual guidance. This three-hour tutorial teaches participants how to move from passive monitoring to actionable wellbeing dialogue. Participants examine a dashboard that combines wearable health-data visualization with conversational-agent feedback, then use Wearable Sensor-Dialogue Wellbeing Agent Studio (WSDWAS) to simulate wearables, generate sensor snapshots, configure

---

### [271] HarnessEval-W: Agentifying the Evaluation of Visual Worlds

**链接**: https://arxiv.org/abs/2608.16859
**作者**: Weiliang Chen, Haowen Sun, Jun Gao, Jiawei Chi, Hanyang Wang, Qiyu Dai 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A benchmark should deliver more than a scalar score: what makes an evaluation trustworthy is the reasoning that justifies the score. This is especially critical for world models, where judging a rollout requires understanding whether physics, causality, and world state evolve correctly. Humans spot such violations naturally, yet no existing benchmark automates this capability: metrics are computed brute-force, leaving no reasoning chain that can be examined or verified. We introduce HarnessEval-W, an agentified evaluation pipeline that brings the harness paradigm from the LLM ecosystem to world model benchmarking. Rather than applying a fixed rubric, HarnessEval-W interprets the context of each evaluation case, decomposes the evaluation question into measurable subproblems, and spawns specialized sub-agents, each equipped with tailored context and diagnostic tools to reason over its own subproblem. The parent agent then validates the gathered evidence and summarizes it into the final v

---

### [272] Dense Expands, Sparse Anchors: Channel-Asymmetric Query Expansion for Hybrid Retrieval

**链接**: https://arxiv.org/abs/2608.15851
**作者**: Chunran Zhang
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based query expansion improves retrieval by generating document-like passages. In hybrid retrieval, however, most evaluations fuse fixed top-$L$ dense and sparse rankings. Because the cutoff controls both which cross-channel contributions enter fusion and how much of each ranking is accessed, gains measured at one $L$ can change or reverse at another. We separate these effects by evaluating retrieval effectiveness under complete-list fusion and recording the policy-specific per-channel replay stopping depths at which its ordered top-$K$ is certified. We then introduce DESA (Dense Expansion and Sparse Anchoring), a channel-asymmetric query expansion method. An LLM generates complementary reference passages; orthogonal residual expansion adds their new semantic directions to the dense query, while score-product anchoring incorporates their lexical cues into sparse retrieval without broadening the original query's lexical support. Across seven BEIR datasets, DESA improves nDCG@10 and 

---

### [273] Discrete Diffusion Language Models Are Training-Free Multi-Label Classifiers

**链接**: https://arxiv.org/abs/2608.14649
**作者**: Pawan Kumar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present dLLM-SetScore, a training-free method that uses discrete masked-diffusion language models for multi-label text classification. For each candidate label, it asks a short yes/no question and compares the probabilities of the two answer tokens at one masked position. The method uses no task-specific fine-tuning or training on textual-entailment datasets; a 200-example labelled validation slice selects thresholds, temperature, and prompt wording. We first show that placing all labels in one prompt creates a strong slot-position asymmetry: the first answer slot is predicted positive on $99.4\%$ of GoEmotions examples and $100\%$ of Reuters examples. Per-label scoring places every label in the same syntactic position, making predictions invariant to label order and avoiding this artifact. We evaluate LLaDA-8B and Dream-7B on six datasets against NLI models, an autoregressive LLM, SetFit, and supervised classifiers. On the five datasets shared by both diffusion families, Instruct c

---

### [274] Demystifying Agent Skills: Why They Work-Until They Don't

**链接**: https://arxiv.org/abs/2608.14036
**作者**: Zhiyuan Jiang, Fangrui Huang, Hanwen Xing, Xander Wu, Yipeng Gao, Rui Cao 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills have emerged as a practical and effective approach for enhancing LLM agents at inference time through structured packages of knowledge. However, existing evaluations largely measure whether skills improve aggregated task success, leaving a more fundamental question underexplored: \emph{\textbf{When do skills help, why do they work, and where do they fail?}} Through controlled experiments across various benchmarks, agent harnesses and LLMs, we isolate the effects of representation, outcome annotation, retrieval difficulty, and cross-framework robustness of skills. To further answer this question, we design a contrastive study that combines controlled quantitative experiments with paired trajectory analysis. We normalize 8,135 trial records from controlled experiments and retain 238 valid unique labels from 240 open-coded records. We consolidate these observations into a taxonomy of three high-level categories and twelve skill-use modes: skills work when noisy trajectories become 

---

### [275] When Do Explanations Help In-Context Learning? A Comparative Study of Natural Language Explanation Types and Faithfulness

**链接**: https://arxiv.org/abs/2608.16627
**作者**: Mahdi Dhaini, Adam Dejl, Juraj Vladika, Volkan \"Ozer, Barbara Plank, Gjergji Kasneci
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language explanations (NLEs) are increasingly used as inputs, for example, as few-shot rationales that influence model behavior in in-context learning (ICL). However, it remains unclear how different types of NLEs compare in their effects on downstream model performance in explanation-augmented prompting. Therefore, we provide a comparative evaluation across six benchmarks and four instruction-tuned models, studying how NLE source (human-written when available, self-generated explanations, generated by an external LLM) and NLE selection (random vs faithfulness-based filtering) affect downstream utility of NLEs when used in ICL settings. Our extensive evaluation shows that, on classification-style benchmarks, adding NLEs to few-shot prompts often improves accuracy over few-shot prompting without explanations; among NLE sources, externally generated LLM-NLEs often provide strong downstream utility and remain competitive with human rationales where both are available, whereas self

---

### [276] Closing the Affective Loop: Multimodal Speaker-Listener Emotion-Dynamics-Aware Empathetic Social Robots

**链接**: https://arxiv.org/abs/2608.16686
**作者**: Zi Haur Pang, Casey Kennington, Tatsuya Kawahara
**来源**: cs.HC cs.CL cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Empathetic social robots should respond not only to what users say, but also to how their emotions dynamically evolve during interaction. However, existing empathetic dialogue systems are often text-centered and primarily model empathy as a one-way mapping from the user's emotion to the system response, limiting their ability to capture embodied speaker--listener affective exchange. We present AffectLoop, a multimodal speaker-listener emotion-dynamics-aware spoken dialogue system implemented on the Misty II robot. The system tracks the speaker's verbal and facial affective dynamics, estimates the robot listener's own verbal and behavioral affective state, and conditions LLM-based response generation on both affective streams. The robot then generates a short spoken empathetic response together with emotionally congruent embodied behavior, forming a closed speaker--listener affective loop. We evaluate the system in a pilot within-subject study with five participants, comparing it with a

---

### [277] LENS: In-Context Search via Latent Evidence Exploration over Dynamic Raw Documents

**链接**: https://arxiv.org/abs/2608.16185
**作者**: Xingjun Wang, Gongsheng Li, Qi Fan, Yunlin Mao, Luyan Su, Yingda Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly answer questions over dynamic raw-document collections, where files may change before preprocessing, and relevant evidence (spans, sections, pages, or tables) is query-dependent. Existing retrieval-augmented approaches pre-materialize evidence via fixed chunking, embeddings, or persistent indexes: effective for lookup, yet costly, stale-prone, and committed to a granularity before the query is known. We formulate in-context search as Budgeted Evidence Localization over a latent evidence space induced by dynamic raw documents and propose LENS (Latent Evidence Exploration and Search), an index-free framework. Instead of pre-materializing the evidence space, LENS maintains a query-conditioned belief over candidate units, iteratively selecting candidates via complementary lexical, local, and exploratory proposal policies, updating the belief via an LLM relevance oracle, and narrowing toward high-posterior regions under a controllable budget. Evidence is consolidated

---

### [278] Beyond Text Conditioning: A Systematic Study of MLLM-DiT Fusion for Video Generation

**链接**: https://arxiv.org/abs/2608.14043
**作者**: Yanbo Ding, Yijia Fan, Caihua Shan, Yifan Yang, Yifei Shen, Weijie Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion Transformers (DiTs) have become the dominant paradigm for high-fidelity video generation, yet their ability to perform high-level semantic planning remains limited. While hybrid architectures integrating MLLMs with diffusion backbones have shown strong advantages in image synthesis, such designs remain underexplored in video generation, where existing approaches often treat MLLMs primarily as frozen feature encoders rather than semantic generators. To fill this gap, we systematically study how an MLLM should be integrated with a DiT for video generation by answering three questions: what intermediate representation should bridge the MLLM and DiT, how the MLLM should generate it, and how the DiT should incorporate it during diffusion rendering. Our analysis reveals three key findings: (1) discrete semantic visual tokens produced by an EMA-based tokenizer provide a stable and expressive interface, (2) autoregressive causal modeling is effective for generating these tokens, and 

---

### [279] AnchorScore: A CLIP-Based Diagnostic of MLLM Annotation Difficulty

**链接**: https://arxiv.org/abs/2608.16690
**作者**: Yan Ma and Lizhuo Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are widely used for automated annotation, yet their per-class accuracy varies widely (e.g., 12%-98% across the 13 classes of three classroom sub-datasets) and is expensive to measure: evaluating one 27B MLLM on 5,416 validation images takes roughly 14 hours, whereas a frozen-CLIP pass over the same images completes in about 3 minutes. A low-cost signal for ranking classes by expected MLLM annotation difficulty a priori remains underexplored. Building on the AnchorProxy construct (per-class zero-shot CLIP accuracy) introduced in the companion study, this paper systematically evaluates its full-frame formulation, termed AnchorScore here, as an a priori diagnostic that flags the classes MLLMs are least likely to annotate reliably. On classroom behavior data (SCB5, 13 classes, 6 MLLMs), AnchorScore correlates with per-class MLLM accuracy (Spearman rho = 0.769, p = 0.002, n = 13). None of the alternative difficulty predictors (DINOv2, ResNet-50, SigL

---

### [280] Pedestrian Trajectory Prediction via MLLM with Goal-Guided Chain-of-Thought

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11633348/&hl=zh-CN&sa=X&d=16978026672655024168&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-wzod2A0pLPL1nf4vBo9Z-t&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: Y Su, Z Zhang, Q Wang, D Zhang, S Liu - … 6th International Conference on Control and …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> trajectory prediction via an MLLM with Goal-Guided Chain-of-Thought. Specifically, we fuse the scene background image with historical pedestrian coordinate sequences into a unified multi-modal prompt. By leveraging the vision-text alignment

---

### [281] Defake-o3: From Speculative Rationales to Verifiable Evidence for Explainable AIGI Detection

**链接**: https://arxiv.org/abs/2608.16259
**作者**: Bowen Deng, Jiahui Zhan, Yikun Ji, Haozhen Yan, and Jianfu Zhang
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid progress of image generation models calls for AI-generated image (AIGI) detectors that are not only accurate but also explainable and reliable. While MLLM-based detectors can provide natural language explanations, existing methods often generate speculative rationales: they rely on vague or hallucinated artifacts, miss subtle localized flaws from the latest generators, and fail to provide evidence that can be visually verified. We present Defake-o3, an explainable AIGI detector that moves from speculative rationales to verifiable evidence. It combines interactive visual search with verifier-guided evidence alignment: the model iteratively zooms into suspicious regions to inspect fine-grained details, while an Evidence Verifier, trained from human verification annotations, provides reinforcement learning rewards that favor grounded evidence and penalize baseless claims. To support this objective, we construct GroundFake, a dataset designed for grounded explainable detection, w

---

### [282] Exploring the Synergetic and Divergent Potentials of Multimodal Semantics for Feature Fusion-based Video Recommendation

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3839230&hl=zh-CN&sa=X&d=12912313281511253283&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-zhpRvaL9PDCofKNGVq0qq4&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: Z Cao, R Liu, R Sun, H Lian, Y Chen, D Zhang - ACM Transactions on Information … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> ( MLLM ). The refined textual embedding, E𝑖,𝑡, integrates visual context for improved semantic representation. We adopt GLM-4V-9B1 [11] as our MLLM … MLLM ’s last hidden states for the input text tokens. With respect to the cover

---

### [283] Thinking Like a Forensic Expert: A Multimodal Reasoning Chain for Training-Free Image Manipulation Localization

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11629882/&hl=zh-CN&sa=X&d=167771006873504197&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-wYFj1alQi_CSMgUzdl5eXu&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: R Chen, B Liu, C Miao, X Wang, Y Li, T Gong 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Conditioned on the filtered rules and task prompt, an MLLM proposes multiple coarse bounding boxes. We crop these candidate regions and re-examine them through successive MLLM passes to progressively select and refine the most

---

### [284] Toward precision urban resilience: Integrating multimodal large language models with spatial analytics for fire risk governance

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0264275126006815&hl=zh-CN&sa=X&d=8515126324165879440&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-zjCaT0W1Lg3W7IeiPxJFnT&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: D Xie, S Cai, K Wang, C Hou, S Dai, J Huang - Cities 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The main contributions of this study are: proposing an MLLM -based framework that uses multimodal data such as RS and SVI information for fine-grained scenario prediction of urban fire risks, and conducting natural language clustering based on

---

### [285] FIRM: Fine-Grained Intra-Token Representation of Masks for Remote Sensing Reasoning Segmentation

**链接**: https://arxiv.org/abs/2608.13980
**作者**: Weidong Tang, Kaiyu Li, Yikai Wang, Yanan Wu, Haotian Gan, Shihong Wang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning segmentation requires multimodal large language models (MLLMs) to translate implicit instructions into precise pixel-level masks. MLLMs encode an image as visual tokens, each of which merges a group of image patches. In remote sensing images, small targets, thin structures, and adjacent instances can occupy different parts of the same visual token. Assigning a single binary mask label to such a token loses its internal spatial structure, causing nearby targets to merge and object boundaries to become coarse. To bridge this representational gap, we introduce FIRM, a Fine-grained Intra-token Representation of Masks. For each visual token, FIRM predicts a mask code that specifies an $r\times r$ binary sub-cell pattern rather than a single foreground/background label. Given a target identified by the MLLM, the complete grid of mask codes is predicted in one mask pass. Fixed lookup converts the predicted codes into a discrete sub-cell mask, while marginalizing the code distributio

---

### [286] RISE: Roadside Infrastructure Sequence Understanding across 3D Tracking and Structured Vision-Language Reasoning

**链接**: https://arxiv.org/abs/2608.16480
**作者**: Yanbo Jiang, Haotian Zheng, Jiahao Wang, Hanxiao Ren, Yitao Xu, Yining Xing 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present RISE (Roadside Infrastructure Sequence Understanding and Evaluation), a framework spanning metric 3D tracking and structured vision-language reasoning in roadside sequences. For metric tracking, our image-only method combines SAM3 video identities with calibration-guided mask agreement for multi-view identity association, recovering persistent 3D tracks without LiDAR or task-specific 3D training. Its calibration-conditioned geometry allows the procedure to be instantiated at different calibrated multi-camera intersections without layout-specific retraining. On 20 human-reviewed clips from six intersections, the generated tracks achieve 66.9 MOTA within the defined multi-view evaluation scope. For structured vision-language reasoning, a human-reviewed MLLM pipeline mines high-value clips and uses a constrained full-context Oracle to construct bbox-grounded predictive QA without exposing future evidence to evaluated models. The resulting RISE-VQA dataset contains 33,910 QA pai

---

### [287] Multimodal denoising diffusion model for anomaly detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0031320326015967&hl=zh-CN&sa=X&d=840309224435951750&ei=V2SCasaYML6jieoPpIfI-QM&scisig=AIVdB-wh-_mYDr1ur7uy_sEOG2hw&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: P Li, C Huang, Y Dou, X Yan, L Cao, Y Tang - Pattern Recognition 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> As the text descriptions generated by MLLM are uncontrollable and prone to overflow, we concatenate the CLIP [30] text encoder to further … generated by MLLM . Ultimately, we obtain text descriptions of the anomaly semantics from the input

---

### [288] Multi-Feature Riemannian Hypergraph for Online Test-Time Adaptation of Motor Imagery Brain-Computer Interface

**链接**: https://arxiv.org/abs/2608.16134
**作者**: Siqi Li (1 and 2), Zhi Li (3), Tong Liu (3), Shuai Zhang (3), Yanfei Jia (4), Zhiqiang Yi (4) 等 (10 人)
**来源**: cs.LG cs.HC eess.SP q-bio.NC
**匹配关键词**: EEG, BCI, Brain-Computer Interface, Motor Imagery
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In clinical motor imagery brain-computer interface (MI-BCI) decoding, cross-day transferability and online operation remain two critical challenges. Hypergraphs can improve transferability by capturing higher-order sample relationships, yet existing hypergraph-based methods for online emotion recognition neglect the cross-day benefits of Riemannian geometry widely adopted in EEG transfer learning. To bridge this gap, we propose the Multi-feature Riemannian Hypergraph (MRieHy), a framework tailored for online test-time adaptation in MI-BCI decoding that leverages Riemannian geometry to strengthen cross-day transferability. MRieHy first computes Riemannian means of covariance matrices from cross-day training data to align multi-day distributions. It then constructs a hypergraph over covariance matrices using Riemannian distance, complemented by a second hypergraph over deep features built with cosine similarity. The two hypergraphs are fused via adaptively learned combination weights, jo

---

### [289] EEG-PRISM: Physiologically-Grounded Interpretability of Predictions by EEG Foundation Models

**链接**: https://arxiv.org/abs/2608.13676
**作者**: Deeksha M Shama, Punnisa Amornsirikul, Archana Venkataraman
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: Foundation models represent the next advancement in AI for EEG analysis; however current explainable AI techniques provide attribution scores in the time-channel input space, which is mismatched to clinical intuition about EEG. Thus, there is a critical need for a universal method that can extend the interpretability of any foundation model to alternative and physiologically relevant domains without modifying or retraining the underlying model. Methods: EEG-PRISM leverages linear transformations and established backpropagation rules to map time-channel attribution scores into alternative domains. We derive mappings to the frequency domain via an invertible DFT and to the source domain via an approximately invertible EEG generative model. We evaluate EEG-PRISM in simulated and real data, assessing recovery of ground-truth phenomena across domains with five foundation models and four AI explainers. Results: In simulation, EEG-PRISM achieves near-perfect spectral recovery and 6

---

### [290] Predicting training outcomes for developmental dyslexia from EEG data

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0891422226001605&hl=zh-CN&sa=X&d=12839721010711256485&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-yFYTtOGtaLXQmFHuoTZVoP&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: G Di Dona, DA Zamfira, F De Benedetto, C Turri… - Research in Developmental …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In the present work we applied machine learning to resting-state EEG to predict longitudinal training outcomes in adults with DD enrolled in a … Future studies should focus on the generalisability of predictive models to real-world settings, while

---

### [291] Analyzing Frequency-Space-Time EEG Signatures via Interpretable Neural Networks: A Simulation Study

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/10/4359967/11654544.pdf&hl=zh-CN&sa=X&d=4745970726862466906&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-xla99euZ0BgzXhDetIYpDF&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: D Borra, E Magosso - IEEE Transactions on Biomedical Engineering, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> extracted the EEG channel at which the spatial discriminatory power was maximum (most relevant EEG channel). The localization error was quantified as the geodesic distance between the most relevant EEG channel (prediction) and the

---

### [292] A 2-Block Architecture for Real-Time EEG Gait Decoding: A Pilot Study

**链接**: https://arxiv.org/abs/2608.02083
**作者**: Shantanu Sarkar, Saurabh Prasad and Jose L. Contreras-Vidal
**来源**: cs.LG cs.HC eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [293] Automating Learner Assessment: Benchmarking Machine Learning and Deep Learning Models for EEG-Based Familiarity Prediction

**链接**: https://arxiv.org/abs/2608.16541
**作者**: Isuru Nanayakkara, Thilina Halloluwa
**来源**: eess.SP cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective assessment of learning remains a fundamental challenge in education. Electroencephalography (EEG) provides a direct, non-invasive window into the neural correlates of knowledge acquisition, including cognitive familiarity. This study benchmarks fifteen machine learning (ML) and deep learning (DL) models for EEG-based familiarity prediction across two cognitive domains: faces (factual knowledge) and mathematical equations (conceptual knowledge). Using continuous EEG data from 23 participants, we extract spectral features (Power Spectral Density) across six frequency bands. We show that while standard stratified cross-validation yields artificially high classification performance (up to 0.9853 F1-score using CNN) due to temporal leakage across neighboring epochs, a rigorous trial-independent validation (Group K-Fold) drops the peak performance to 0.6038 F1-score (using CNN), which is still statistically significant above the 25% chance level. This highlights the critical necess

---

### [294] Compression Entropy: An efficient entropy measure for EEG -Based seizure detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426017866&hl=zh-CN&sa=X&d=9728307709763884215&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-zQcbMh_hbnlayjlqDxabAf&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: AB Kazen, TJ Newton, ZV Tosi, VK Muvvala… - … Signal Processing and …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We analyze the qualitative dynamics of each entropy measure on synthetic data, analyze their pairwise correlations on EEG data assess … EEG data (r = 0.85), achieved a segment-level F1-score of 0.714 for SWD detection using only a single

---

### [295] Backpropagation-Free Test-Time Adaptation for Lightweight EEG-Based Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2601.07556
**作者**: Siyang Li, Jiayi Ouyang, Zhenyao Cui, Ziwei Wang, Tianwang Jia, Feng Wan 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [296] A VR-treadmill- EEG laboratory method for studying effects of human activity states on thermal comfort in different types of large-scale public buildings

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0378778826011540&hl=zh-CN&sa=X&d=6185678411313998562&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-ybno8edn4FZWmQlJBFsKuA&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: Z Li, X Jin, G Song, Q Zhang, B Lin, A Yonzan 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Thermal comfort is essential to the operational quality of large-scale public buildings. It is necessary to investigate how occupant activities affect thermal comfort in different types of large-scale public buildings. This study utilized a VR–treadmill

---

### [297] Beyond Grid and Graph: A Dual-Stream Spatio-Temporal Framework with Kolmogorov-Arnold Networks for EEG Emotion Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11655232/&hl=zh-CN&sa=X&d=625137421332842968&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-zHsQGCxoeTVWaq5gaBNzn_&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: J Tong, W Chen - IEEE Internet of Things Journal, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Recent studies have demonstrated the feasibility of integrating EEG -based emotion recognition into wearable and AI-edge platforms for … efficient EEG emotion recognition model that can potentially support future IoT-enabled

---

### [298] An Optimized Deep Learning Framework for Robust Epileptic Seizure Detection Using EEG Signals

**链接**: https://scholar.google.com/scholar_url?url=https://jidmis.org/index.php/jidmis/article/download/1796/739&hl=zh-CN&sa=X&d=10311406531883632269&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-ytfW6OIKdiLYTrzYYxFsAu&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: MN Varma - Journal of Intelligent Decision Making and Information …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Epilepsy affects a person's behavior and is characterized by seizures. Epileptic seizures are infamously difficult to treat because of how unpredictable they are. Automatic electroencephalogram ( EEG ) seizure detection allows medical

---

### [299] Leakage-Audited Benchmarking Reveals Limited Evidence for Cross-Subject Auditory-Evoked EEG Vowel Perception Decoding

**链接**: https://arxiv.org/abs/2605.00865
**作者**: Xiaoyang Li, Zeyan Tao
**来源**: eess.SP cs.CL cs.CV cs.LG cs.SD q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [300] A Gated Artifact Management Pipeline for Low-Density Eyewear EEG

**链接**: https://scholar.google.com/scholar_url?url=https://iopscience.iop.org/article/10.1088/1361-6579/ae99ab/pdf&hl=zh-CN&sa=X&d=58904150483542671&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-wYafzy65lxl50IW4H6tqeV&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: AC Palmisciano, A Farabbi, F Latino, M Rossi… - Physiological Measurement, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Deep learning provides a modern framework for EEG artifact removal. Various architectures have been … The classification of EEG artifacts represents another crucial challenge in EEG processing. … The growing field of wearable EEG devices

---

### [301] EEG Emotion Recognition From AI-Generated Biodigital Architecture Images

**链接**: https://arxiv.org/abs/2607.24808
**作者**: Hongye Yang and Eva Guttmann-Flury
**来源**: q-bio.NC cs.AI cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [302] Attention and risk awareness in elevated construction tasks: AR-based simulation with EEG measures

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S092575352600319X&hl=zh-CN&sa=X&d=4543720362766775415&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-y83KbLitjwYcGgskmkY0dd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: H Ju, T Bulbul, X Yang, J Withers - Safety Science, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Working at height involves varying cognitive demands across subtasks such as locomotion, precision alignment, and load handling, yet the underlying neurocognitive mechanisms remain insufficiently understood. This study aims to

---

### [303] A Negative-Control Protocol for Clinical EEG Foundation-Model Benchmarks: Dataset Identity and External-Cohort Stress Testing

**链接**: https://arxiv.org/abs/2607.24519
**作者**: Marzieh Zare
**来源**: cs.LG cs.AI cs.NE
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [304] NeuroSpectNet: A Novel Architecture for Early Stage Detection of Executive Dysfunction from Resting-State EEG

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11655034.pdf&hl=zh-CN&sa=X&d=4909225669558318982&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-zThSZdahi42WLaJRLyQFFg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: C Rieck, L Eisentraut, P Penava, R Buettner - IEEE Access, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -stage detection of executive dysfunction from resting-state electroencephalography . The proposed approach is based on power spectral … that resting-state EEG contains stable, interpretable patterns of executive functioning and

---

### [305] Early Stratification of Risk for Poor Neurological Outcome After Cardiac Arrest Is Improved with Processed EEG Data

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0300957226003126&hl=zh-CN&sa=X&d=17492054843012015791&ei=V2SCaqfiIb6jieoPpIfI-QM&scisig=AIVdB-xPNyw563U2WsG1L9DlceL2&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: Q Jin, RR Riker, TL May, G Kshirsagar, H Williams… - Resuscitation, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> and processed EEG were initiated later than six hours after ROSC, we used the first values available in a secondary analysis that included the 6-hour EEG data and initial EEG data later than 6 hours. These SR and BIS values were determined

---

### [306] Global AI Regulations for FAIR and Ethics in High-Risk Use Cases: A Comparative Review

**链接**: https://arxiv.org/abs/2608.14562
**作者**: Aasish Kumar Sharma, Dimitar Koysev, Christopher Anich, Roshni Kumari Ojha, Julian Kunkel
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI governance is shifting from voluntary ethics to enforceable, risk-based regulation, yet cross-jurisdictional divergence creates compliance uncertainty for operators of high-stakes AI. We present a comparative matrix for the EU, US, and China that maps (i) risk classification triggers, (ii) binding obligations, (iii) enforcement and accountability mechanisms, and (iv) the degree to which FAIR principles are operationalised in practice. We stress-test the matrix on three high-impact domains: Electroencephalography (EEG)-guided rehabilitation robotics, AI-enabled debt collection in prospective Central Bank Digital Currency (CBDC) ecosystems, and AI-driven allocation of scarce Graphics Processing Unit (GPU) resources in emerging AI Factory infrastructures. Using primary legal texts and implementation evidence, we identify three recurring gaps: weak interoperability mandates, difficult operationalisation of cross-regime obligations (AI + sector regulation + data protection), and under-sp

---

### [307] MUPA$^{2}$E: Multimodal Unified Perception with Asymmetric Attention for Emotion Assessment

**链接**: https://arxiv.org/abs/2608.15999
**作者**: Stefanos Gkikas, Eric Nichols, Christian Arzate Cruz, Randy Gomez
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic emotion assessment can benefit from combining neural and behavioral signals, but many multimodal approaches rely on separate, modality-specific feature-extraction pipelines before fusion. This paper presents MUPA\textsuperscript{2}E, a unified perception framework that processes facial video and electroencephalography (EEG) through a single shared asymmetric-attention backbone. Facial video is represented through axis-folded frame tokens, while EEG is processed either as a raw multichannel waveform or projected into the spatial domain for multimodal fusion. The framework is evaluated on the DMER dataset under a stratified subject-independent protocol, comparing unimodal video, unimodal EEG, and fused video--EEG configurations with per-channel and merged EEG projections. Using the original recordings, with shorter trials zero-padded to match the longest duration, merged fusion at stride~$30$ achieves the highest validation performance and a test accuracy of $70.07\%$. Further 

---

### [308] M-LINKX: Multiview Graph Learning for Brain Cognitive Disease Detection

**链接**: https://arxiv.org/abs/2608.14847
**作者**: An Phan, Yufei Jin, and Xingquan Zhu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalogram (EEG) is a non-invasive and relatively low-cost procedure that measures brain electricity for the detection of cognitive diseases. EEG-based classification of dementia-related conditions, including Alzheimer's disease (AD), mild cognitive impairment (MCI), and frontotemporal dementia (FTD), remains challenging because EEG signals are noisy, non-stationary, and vary across subjects. Segment-based learning provides a practical way to model long EEG recordings by converting them into fixed-length inputs. For each segment, discriminative information may be explored by using signals within each channel (i.e. electrode), as well as interactions between EEG channels. In this paper, we propose M-LINKX, a multi-view graph learning framework for EEG-based dementia classification. For each segment, we extract channel-level node features and construct multiple functional-connectivity (FC) graph views, where each view is defined by a specific combination of connectivity metric,

---

### [309] Research-Oriented Human-Centric Evaluation for Foundation Models

**链接**: https://arxiv.org/abs/2506.01793
**作者**: Yijin Guo, Kaiyuan Ji, Xiaorong Zhu, Junying Wang, Farong Wen, Chunyi Li 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [310] Zero-Shot Adaptation of Medical Vision Foundation Models for High-Frequency Micro-Ultrasound Prostate Segmentation

**链接**: https://arxiv.org/abs/2608.14796
**作者**: Ayusha Abbas, Saram Abbas, Kabita Adhikari
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prostate cancer claims a life every 80 seconds. Early detection is needed to prevent disease progression, and both PSA density calculation and biopsy decisions rely on knowing the exact boundary of the gland. Conventional ultrasound at 6-12 MHz blurs this boundary, missing one in three high-risk cancers. Micro-ultrasound (29 MHz) improves resolution threefold but introduces dense acoustic speckle that obscures the outer wall; given the same image, two clinicians draw outlines differing by over 10% in area. Supervised methods are costly and generalise poorly across scanners. Can a foundation model segment the prostate with no training data? We present the first zero-shot pipeline for this modality: MedSAM, pre-trained on over 1.5 million medical images, localises the prostate; we then apply CLAHE to sharpen the outer wall, binary dilation to recover missed pixels, and Fourier smoothing (4 modes, s=1.05) to refine the boundary. MedSAM requires a spatial prompt, so we evaluate bounding-bo

---

### [311] Training Fair Tabular Foundation Models

**链接**: https://arxiv.org/abs/2608.14211
**作者**: Patrik Kenfack, Jesse C. Cresswell, Anthony L. Caterini, Samira Ebrahimi Kahou, Ulrich A\"ivodji
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular Foundation Models (TFMs) have emerged as leading methods for tabular predictive tasks, leveraging in-context learning to predict on new data without task-specific training. Despite the increased use of TFMs in high-stakes decision-making, their fairness properties remain largely unexplored. In this work, we incorporate fairness constraints directly into TFM training, enabling fair predictions in a single forward pass. Our approach addresses two key challenges: limited access to sensitive attributes in training data, and the incompatibility of existing fairness techniques with the in-context learning paradigm. We propose FairTFM, a scalable training strategy based on synthetic fairness tasks and a fairness-aware architecture using a gradient reversal layer, which encourages the model to learn representations invariant to sensitive attributes. Experiments on 132 fairness tasks show consistent improvements in fairness while maintaining competitive accuracy.

---

### [312] A Comprehensive Survey of Wireless Foundation Models for AI-Native 6G Networks

**链接**: https://arxiv.org/abs/2608.14694
**作者**: Naveed Khan, Besan Al Sbeihi, Maryam Alshehhi, and Nasir Saeed
**来源**: cs.AI cs.NI eess.SP
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are emerging as a transformative paradigm for AI-native sixth-generation (6G) wireless networks by enabling scalable, transferable, and data-efficient intelligence across diverse communication tasks. Unlike conventional deep learning models that are trained for individual applications, wireless foundation models (WFMs) learn generalized representations from large-scale heterogeneous wireless data and can be efficiently adapted to communication, sensing, localization, and network optimization tasks with minimal task-specific supervision. Despite rapid progress, current research remains fragmented across architectures, training paradigms, and application domains, with no unified survey dedicated to the design, learning, and deployment of WFMs. This survey presents a comprehensive and unified review of wireless foundation models. We first establish the fundamental concepts of WFMs and introduce a taxonomy that organizes the field according to model architectures, pre-tra

---

### [313] Benchmark-Based Comparative Assessment of Publicly Benchmarked Indian Foundation Models: A Capability and Evaluation-Maturity Framework

**链接**: https://arxiv.org/abs/2608.11891
**作者**: Avinash Agarwal and Vridhi Jain
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [314] Attributing Preprocessing Invariance in Spectral Foundation Models

**链接**: https://arxiv.org/abs/2608.14227
**作者**: Dongjun Wei, Hongyi Wu, Yinuo Zou
**来源**: cs.AI cs.CE cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Preprocessing invariance is an appealing goal for spectral foundation models: a frozen model should remain useful when laboratories preprocess spectra differently. It is usually measured by training a classifier under one preprocessing pipeline and testing it under another, with preserved accuracy read as evidence of learning. We revisit that reading, using a Raman foundation model as a case study. Such models normalize their inputs before any learned parameter is applied. If that normalization maps two differently preprocessed spectra to the same vector, the encoder receives identical inputs, so the invariance cannot be attributed to learning. For a normalization that uses each spectrum's own statistics, this happens exactly when one spectrum is a positive multiple of the other plus a constant. Several standard preprocessing operations take that form. The encoder should therefore be measured against the normalization alone, which has no learned parameters. On six Raman evaluation data

---

### [315] CFM-Bench: A Unified Multi-Domain, Multi-Task Benchmark for Channel Foundation Models

**链接**: https://arxiv.org/abs/2607.14975
**作者**: Yuan Gao, Wenjun Yu, Jun Jiang, Yunfan Li, Xinyu Guo, and Shugong Xu
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [316] Mint-Agent: Introducing Finance-Native Agentic Foundation Models

**链接**: https://arxiv.org/abs/2608.16386
**作者**: Mint-Agent Team, B. Zhang, Yaze Geng, Lei Tang, Yaoyang Yi, Zonghan Wu 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial agents must do more than recall domain knowledge: they must be both reliable, executing precise operations over grounded evidence, and executive, sustaining long-horizon research whose conclusions remain auditable. We present Mint-Agent, a family of finance-native agentic models designed around these two scales of financial intelligence. Mint-Agent is built upon three pillars: data, harness, and algorithm. Our data engine constructs clean, specialized tasks for atomic financial capabilities and long-horizon agentic execution from real-world financial sources. MintHarness enables stable interaction with open-ended environments and maintains auditable evidence trails across extended research trajectories. Our training recipe combines SFT, critical-step OPD, and RLVR to develop separate financial reasoning and agentic execution experts, which are then unified through model merging and multi-teacher on-policy distillation into compact, general-purpose financial agents. This pipel

---

### [317] Beyond Accuracy: Assessing Calibration of Geospatial Foundation Models and Their Sensitivity to Distribution Shifts

**链接**: https://arxiv.org/abs/2608.16614
**作者**: Nils Lehmann, Jakob Gawlikowski, Burak Ekim, Isaac Corley, Xiao Xiang Zhu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial Foundation Models (GeoFMs) are most commonly ranked and selected by accuracy on standard benchmark conditions via averaged ranks. We show that this protocol is too narrow: the promised deployment in critical EO tasks requires further angles of analysis, mainly calibration, the agreement between a model's confidence and its correctness. Across 16 frozen encoders, four classification and five segmentation datasets, and two orthogonal stress axes, every encoder degrades as corruption intensifies, and the ranking changes as well. Across the four classification benchmarks, EO-pretrained and ImageNet-pretrained encoders are indistinguishable on clean accuracy and clean calibration, and EO pretraining provides no more stability under shift than ImageNet pretraining. Under shift the GeoFMs drift further into overconfidence than the ImageNet-pretrained encoders, at every grade and in every corruption family. A centered kernel alignment (CKA) analysis ties this to representational rig

---

### [318] 6G Native AI and Channel Foundation Models

**链接**: https://arxiv.org/abs/2608.14591
**作者**: Shugong Xu, Jun Jiang, Yuan Gao
**来源**: eess.SP cs.IT cs.LG math.IT
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of artificial intelligence (AI) and wireless communications is widely regarded as a core objective of sixth-generation (6G) systems. However, both the meaning of native AI and the type of AI capability that should be embedded into future wireless systems remain open to interpretation. This paper discusses 6G native AI from a system-design perspective and argues that native AI should be co-designed, optimized, and deployed as an intrinsic component of the wireless system rather than as a removable post-deployment add-on. From this perspective, conventional task-specific supervised models are difficult to use as the main technical basis of native AI because they depend heavily on labeled data, generalize poorly across propagation conditions, and require fragmented designs for different channel-related tasks. Motivated by these limitations, we position channel foundation models (CFMs) as a channel-centric foundation-model paradigm for 6G native AI. We define the scope of C

---

### [319] Earth Observation Foundation Models for Terrestrial Ecohydrology: From Representation Learning to Process Inference

**链接**: https://arxiv.org/abs/2608.15282
**作者**: Yi Yu, Jian Peng, Yucheng Lin, Trevor F. Keenan, Thomas F. A. Bishop
**来源**: cs.LG cs.CV physics.bio-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth observation foundation models (EOFMs) are emerging as reusable representation frameworks for data-driven retrieval, prediction and process modelling within ecohydrology, which integrate EO, meteorological forcing and process models to characterise coupled water, energy and carbon dynamics in vegetation and soil across scales. However, there is yet to be an ecohydrology-specific synthesis assessing the EOFM relevance, application evidence or evaluation requirements under uncertain reference data, scale mismatch and temporal dependence. Here, we develop a framework for determining when EOFMs support interpretable inference and identify a mismatch between EOFMs and ecohydrological requirements. Firstly, an observation-to-inference hierarchy shows that relevance depends on target-specific sensing pathways, spatial-temporal support and traceable uncertainty. Secondly, a meta-analysis shows that pretraining is dominated by reflected optical and active-microwave data, with sparse therma

---

### [320] What Makes a Good Layer? Assessing the Layer-Wise Intrinsic Properties of Music Foundation Models

**链接**: https://arxiv.org/abs/2608.14819
**作者**: Angelos-Nikolaos Kanatas, Yuexuan Kong, Pablo Alonso-Jim\'enez, Xavier Serra, Dmitry Bogdanov
**来源**: cs.SD cs.LG eess.AS
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Music foundation models are commonly used as frozen audio feature extractors, yet selecting which layer to extract from remains largely heuristic. Current practice defaults to fixed depths or multi-layer fusion, with limited understanding of why certain layers transfer better across downstream tasks or how representation quality varies with depth and pre-training paradigm. We conduct a systematic layer-wise analysis of 12 music foundation models spanning three pre-training paradigms (masked modeling, autoregressive modeling, and contrastive learning), characterizing their hidden representations through intrinsic geometric and transformation-based properties. Correlating label-free representation-quality metrics with layer-wise performance across 15 downstream tasks, we find that several metrics track layer quality for genre classification, emotion recognition, automatic tagging, and beat tracking, albeit with varying strength across tasks and pre-training paradigms. However, all metric

---

### [321] Lost in Phonation: Voice Quality Variation as an Evaluation Dimension for Speech Foundation Models

**链接**: https://arxiv.org/abs/2510.25577
**作者**: Harm Lameris, Shree Harsha Bokkahalli Satish, Joakim Gustafson, \'Eva Sz\'ekely
**来源**: eess.AS cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [322] Forecast Collapse in Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2608.14106
**作者**: Shu Wan, Miles Ma, Hank Zhu, Guangqi Liu, Stephen Wang, Qingsong Wen 等 (7 人)
**来源**: cs.LG cs.AI cs.CE stat.AP stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When forecasting hourly returns for 1,000 US equities, we observe an unexpected phenomenon: predictions become nearly flat and show poor stock ranking, as measured by cross-sectional correlation. We call this forecast collapse. Surprisingly, the phenomenon largely disappears when forecasting trading volume under the same setting. We investigate forecast collapse across time-series foundation models (TSFMs), twelve deep-learning forecasting models, and 97 public benchmark configurations, and find that it is closely tied to target predictability. We identify two distinct reasons behind it: low predictability limits the amplitude of calibrated point forecasts, while per-series objectives leave cross-series structure unidentified. These findings reveal a calibration-ranking tradeoff: optimizing squared error leads to flat predictions, whereas directly optimizing cross-sectional correlation improves ranking but can inflate forecast amplitude by more than an order of magnitude. To address th

---

### [323] Beyond Natural-Image Foundation Models: Benchmarking Satellite Pretraining for Ophthalmic Image Analysis

**链接**: https://arxiv.org/abs/2608.15195
**作者**: Lovre Antonio Budimir, Mingya Alexa Gong, Alyssa Foong Quinney, Ivana Matovinovi\'{c}, Yukun Zhou, Pearse A. Keane 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision Foundation Models (VFMs) have emerged as a promising approach in medical imaging, producing broadly applicable systems that can be efficiently adapted across diverse imaging modalities, anatomical regions, and clinical tasks. However, VFMs require extensive training data, and their progress in medical image analysis is constrained by limited data availability, privacy concerns, and high development costs. To alleviate these constraints, medical VFMs (MedVFMs) are often built upon weights from generalist models pretrained on vast amounts of publicly available natural images, introducing a substantial distribution shift for medical task adaptation. To address this, we propose satellite imagery as a novel pretraining domain for MedVFM development and benchmarking, motivated by its closer visual alignment with medical data and its freedom from the privacy constraints that limit medical datasets. Across multiple ophthalmic imaging modalities, we compare DINOv3-SAT493m pretrained on 4

---

### [324] PERO: Efficient Robust Post-Training Foundation Models for Encrypted Traffic Classification

**链接**: https://arxiv.org/abs/2608.15504
**作者**: Wumei Du, Jiarong Wen, Kaiyu Zhang, Zi Yang, Yiqin Lv, Longfei Zhang 等 (8 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Encrypted traffic classification is vital for network security, yet real-world deployments are inherently sensitive to rare but high-loss errors such as misclassification of malicious traffic. The encrypted traffic foundation model, as a promising general-purpose technique, can achieve impressive overall performance. However, employing standard objectives such as empirical risk minimization often overlooks high-risk tail events, and commonly used performance metrics hardly reflect robustness limitations in risk-sensitive scenarios. Directly applying robust optimization objectives, such as conditional value-at-risk, to post-training is computationally prohibitive for large models, as identifying high-loss samples exhausts substantial computation. To this end, we propose Pre-Evaluation Robust Optimization (PERO), an efficient robust post-training framework for encrypted traffic foundation models. PERO employs a lightweight proxy to estimate sample-wise risk and selects a subset of high-r

---

### [325] AlignJEPA: Predictive Vision-Language Alignment for Remote Sensing Foundation Models

**链接**: https://arxiv.org/abs/2608.15456
**作者**: Md Aminur Hossain, Omkumar Vaghasiya, Rajeev Ranjan Dwivedi, Vinod Kurmi, Biplab Banerjee
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote sensing (RS) foundation models provide transferable Earth observation representations across sensors, resolutions, and geographies, yet most remain weakly aligned with natural language, limiting natural-language archive search, image-text retrieval, and question-conditioned analysis. We propose AlignJEPA, a JEPA-inspired predictive vision-language alignment framework for remote sensing foundation models. AlignJEPA uses a pretrained AnySat visual encoder and a RemoteCLIP text encoder while training only a lightweight predictive alignment network. Instead of relying on global image--text contrastive alignment alone, the framework predicts remote-sensing text embeddings from masked visual foundation-model tokens. Its mask-aware multi-scale predictive aligner aggregates visible tokens at fine, regional, and global scales, jointly models them with a cross-scale Transformer, and projects the resulting representation into the text space using learned query pooling. Training combines se

---

### [326] Concept-based explanation of gene expression prediction from H&E images

**链接**: https://arxiv.org/abs/2608.16669
**作者**: Amos Muench, Jonathan Thielmann, Reduan Achtibat, Maximilian Dreyer, Philip Bischoff, Caroline Forsythe 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in pathology foundation models have enabled accurate prediction of spatial transcriptomics (ST) from routine H&E images. However, existing explainability methods for vision transformer (ViT)-based models are largely limited to local heatmaps and do not reveal how morphological concepts contribute to ST predictions. Here, we introduce an explainable framework that combines relevance propagation and concept discovery to link transcriptional programs to tissue morphology. We developed a ViT-based framework for virtual ST from H&E images that combines ViT-aware layer-wise relevance propagation with relaxed archetypal TopK sparse autoencoder-based concept discovery. This approach provides both local explanations and global insights into the morphological patterns associated with transcriptional programs. We applied the framework to colorectal cancer ST data from the HEST-1k cohort and evaluated its generalizability in TCGA COAD. Our architecture accurately predicts clinicall

---

### [327] ChainSpace: A Chained-Reasoning Paradigm for Spatial Intelligence

**链接**: https://arxiv.org/abs/2608.15788
**作者**: Xiaohan Zhang, Feng Gu, Xudong Rao, Xuhao Pan, Tao Wei, Zhou Pan 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial intelligence requires foundation models to maintain coherent spatial state across interactions with the physical world. However, existing data-centric approaches typically treat spatial reasoning as independent question-answer instances, enabling shortcut-based answering and providing limited supervision for persistent spatial understanding. To address this, we introduce ChainSpace, a chained-reasoning paradigm that structures spatial reasoning as a state-preserving multi-round process. In this paradigm, spatial questions are organized into logically constrained and jointly consistent chains, where later questions depend on spatial constraints established in earlier rounds. Following this principle, we instantiate ChainSpace-Bench, a manually annotated real-world multi-round benchmark with a Chain-Aware Metric, and ChainSpace-Pipeline, a simulator-based chain-structured supervision generation framework for spatial intelligence training. Experiments show that ChainSpace-Bench ex

---

### [328] Self-Routed Tensor Adapters for Parameter-Efficient Universal Visual Adaptation

**链接**: https://arxiv.org/abs/2608.16384
**作者**: Suraj Yadav
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Universal visual representations require adaptation mechanisms that adapt across heterogeneous domains without fragmenting knowledge into domain-specific modules. Parameter-efficient fine-tuning adapts frozen visual foundation models efficiently, but standard low-rank adapters use a fixed subspace for all inputs, which can be restrictive when domains differ in style, background, and semantic context. MoE-based adapters improve specialization through multiple expert pathways, but often rely on external routers and large expert banks, adding parameters and separating routing from adaptation. We propose \textbf{Self-Routed Tensor Adapters}, a compact framework for multi-domain visual adaptation. SRTA projects each input into a low-rank space, computes routing weights from this representation using a learnable domain matrix, and uses these weights to blend slices of a shared Tucker core. This produces a sample-specific adaptation matrix without an external gating network, allowing shared v

---

### [329] CytoBERT: A Foundation Model for Cytometry Data

**链接**: https://arxiv.org/abs/2608.14414
**作者**: Syed Abdul Haseeb Qadri, Bjarne C. Hiller, Felix Blanke, Vanja Sophie Cangalovic, Kutalm{\i}\c{s} Co\c{s}kun, Amin Mirzaei 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cytometry measures the complex characteristics of single cells (e.g., counts and protein expression of immune cells) and is widely used across immunological research and clinical settings. However, cytometry data is highly heterogeneous and unstandardized due to experimental protocols and the choice of measured features. While machine learning methods hold the potential to gain deeper insights into cell biology, these challenges make them difficult to apply and transfer across studies. Recent advances in foundation models can alleviate these issues, but corresponding approaches are still scarce in this field. To address this, we provide CytoBERT, a publicly available, open-source, open-weight foundation model for single-cell cytometry data with variable marker panels. CytoBERT is pretrained in a self-supervised manner on a large-scale cytometry corpus (15 human datasets with heterogeneous marker panels and more than 50 million cells) curated through marker standardization, enabling it 

---

### [330] DeepInsight II: One Trace from Benchmark to Robot

**链接**: https://arxiv.org/abs/2608.16556
**作者**: Siyi Li, Yuchen Kang, Wuliang Wang, Zhengjie Zhang, Jiangpin Liu, Jianhao Yao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Across a Physical AI stack, evaluation maturity is inversely aligned with deployment risk: foundation models enjoy mature, standardized harnesses, while the embodied layers on which deployment actually turns remain fragmented across benchmark-specific simulators, embodiments, and interfaces. The first DeepInsight report (v1) unified evaluation across this stack behind three abstractions---task, resource, and result---but its quantitative evidence centered on the foundation-model layer; navigation and manipulation (System 1) and whole-body control (System 0) remained simulation case studies, and physical execution was outside its empirical scope. DeepInsight II keeps that substrate fixed and quantifies the embodied half. First, it reproduces released-checkpoint references across two navigation and four manipulation benchmarks under their native protocols. Second, MotionBench places four released whole-body controllers under one workload and metric contract, then carries a qualified with

---

### [331] The Past and Future of AI Scientists

**链接**: https://arxiv.org/abs/2608.14407
**作者**: Ross D. King
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a survey of the past and future of AI Scientists: machines capable of automating science. AI Scientists can originate hypotheses, deduce their consequences, design and execute experiments, interpret their results, and revise their beliefs. Such systems are integrated scientific agents, connected to the literature, formal knowledge, mathematical models, simulations, data-analysis systems and physical laboratories. Adam was the first machine to make novel scientific discoveries through cycles of hypothesis formation and physical experimentation. Eve established the architecture of the modern self-driving laboratory. Foundation models, autonomous agents and laboratory robotics now make it possible to build systems far more general than either Adam or Eve. The central problem is no longer whether individual components of science can be automated. They can. The problem is integration. AI Scientists must combine neural learning with logic, probability, mathematics, causal reasonin

---

### [332] CoM$^3$eT: A foundation model for medical image analysis through federated, multidimensional context integration

**链接**: https://arxiv.org/abs/2608.16268
**作者**: J. Raphael Sch\"afer, Kai Geissler, Till Nicke, Chiara Tappermann, Karoline Heber, Eike Petersen 等 (10 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical foundation models improve generalization when training AI models with limited labeled data, but remain confined to a single specialty, such as pathology or radiology, and to either sparse or dense outputs, such as classification or segmentation. Here, we present CoM$^3$eT (Co-representation Multidimensional Multitask Medical Transformer), a medical vision foundation model that unifies pathology and radiology, sparse and dense predictions, and two- and higher-dimensional inputs by modeling multidimensional context with attention. CoM$^3$eT outperformed other medical foundation models in an open competition spanning five tomographic, four whole-specimen, and three two-dimensional datasets, covering sparse and dense prediction tasks as well as report generation. When adapted across diverse clinical applications, training fewer than 2.5% of parameters achieved performance comparable to full fine-tuning, enabling research without access to high-performance GPU clusters. Applied to f

---

### [333] HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-manipulation via Hierarchical Action Flow and Spectral Latent RL

**链接**: https://arxiv.org/abs/2608.16837
**作者**: Langzhe Gu, Chengkai Hou, Meng Li, Xinhua Wang, Jiaming Liu, Xinyuan Lv 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humanoid robots hold great promise as general-purpose agents in human-centered environments, yet generalist vision-language-action (VLA) foundation models are not readily applicable to humanoid whole-body loco-manipulation. The high dimensionality and interdependence of humanoid motions make it challenging for conventional single-stage VLA architectures to coordinate locomotion, waist posture, and dual-arm manipulation effectively. Moreover, policies trained through offline behavior cloning can remain suboptimal during real-world deployment. Although online reinforcement learning can refine policies through real-world interaction, directly tuning large VLA backbones demands excessive computation and may introduce safety risks during real-robot exploration. To address these bottlenecks, we introduce HAF (Humanoid Adaptation Framework), a two-part framework consisting of HAF-VLA and HAF-Steer that transfers off-the-shelf generalist VLA foundation models to humanoid whole-body loco-manipu

---

### [334] Toward AI-Friendly Cartography: Understanding How Color Design Influences Foundation Model Spatial Reasoning on Sequential Choropleth Maps

**链接**: https://arxiv.org/abs/2608.15736
**作者**: Yonghe Sun, Zhenjia Liu, Hua Liao, Wenjia Xu, Nai Yang, Weihua Dong 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) increasingly support multimodal and geospatial reasoning, yet it remains unclear whether cartographic principles designed for human perception are equally effective for machines. Focusing on sequential choropleth maps, we examine how hue palette, color ordering, and lightness contrast influence FM spatial reasoning. We construct a controlled benchmark of 5,760 maps and 28,800 questions spanning Attribute Identify, Spatial Recognition, Compare, Rank, and Pattern Delineate, and evaluate 21 open-source and proprietary multimodal FMs. Results show that hue choice has limited and inconsistent effects, whereas disrupting sequential color ordering substantially reduces performance, especially for comparison and ranking. Reduced lightness contrast also consistently impairs reasoning, while increasing contrast beyond sufficient separability provides only marginal gains. LoRA fine-tuning improves overall accuracy but preserves these relative sensitivities. Additional fact

---

### [335] SAGE-OR: Semi-supervised Adaptive Scene Graph Generation for Operating Rooms

**链接**: https://arxiv.org/abs/2608.15336
**作者**: Brandon Leblanc, Charalambos Poullis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current surgical scene graph generation methods depend on dense multi-modal supervision and specialized hardware (synchronized RGB-D sensors, calibration rigs), making dataset construction expensive and restricting all existing benchmarks to simulated environments. We propose SAGE-OR, a feature-centric framework that replaces the traditional detect-then-reason paradigm with a decoupled representation-reasoning paradigm in which localization is derived from frozen foundation models, encoded implicitly in pre-computed features, and used without any localization supervision, while a lightweight graph transformer performs relational reasoning over cached features. We employ a semi-supervised formulation with general-purpose segmentation prompts to eliminate localization supervision while enabling unsupervised context augmentation through additional prompt-driven entities, such as hands, which are absent from annotations. General-purpose prompts are used to induce near-perfect recall, while

---

### [336] Decoupling Parcellation from Classification: Systematic Benchmark of Fast Brain Segmentation Methods for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2608.16039
**作者**: Jiadao Zou, Hongyu Guo, Wei Xi
**来源**: eess.IV cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain parcellation and classification are typically evaluated in isolation, yet downstream AD detection performance depends on their interaction. We decouple these components and systematically benchmark fast deep learning parcellation methods (SynthSeg+, OpenMAP-T1) against the FreeSurfer (FS-HV) clinical baseline through down- stream AD classification on OASIS-1. Our factorial design evaluates three parcellation methods, two volumetry strategies (hard vs. soft), and four classifier paradigms (clinical thresholds, supervised feedforward networks, ensemble methods, and foundation models with zero/few-shot prompting), with all results quantified using BCa Bootstrap 95% confidence intervals.

---

### [337] Rethinking Auxiliary Modalities in Multimodal Zero-shot Anomaly Detection: From Semantic Fusion to Conditional Modulation

**链接**: https://arxiv.org/abs/2608.13973
**作者**: Peng Wu, Xin Ge, Yujia Sun, Guansong Pang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent foundation model-based methods have endowed RGB images with strong zero-shot anomaly detection (ZSAD) through vision-language pretraining. However, RGB observations alone remain limited in perceiving anomalies dominated by geometric deformation, depth variation, or subtle surface changes. Auxiliary modalities can provide complementary structural information, but existing multimodal methods typically fuse them directly into a shared semantic space, which may disturb the text-aligned anomaly semantics established by RGB foundation models and often requires modality-specific architectures. To address this issue, we propose a plug-and-play auxiliary-conditioned enhancement framework for zero-shot anomaly detection. Instead of reconstructing a joint multimodal anomaly semantic space, our framework preserves the original RGB image-text anomaly matching pathway and uses auxiliary observations as conditional signals for RGB feature refinement, allowing auxiliary modalities to seamlessly

---

### [338] Model-agnostic Retrieval-Augmented Extended Forecasting for time series

**链接**: https://arxiv.org/abs/2608.14054
**作者**: Juan Pablo Villa Serna, Rohan Asthana, Vasileios Belagiannis
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series forecasting with pretrained foundation models has demonstrated strong zero-shot capabilities. However, achieving optimal performance on time series with short or negligible historical data in domain-specific applications typically requires adaptation via either fine-tuning or RAG. While fine-tuning is effective, it incurs substantial computational costs. This work explores RAG within univariate time series (Retrieval Augmented Generation) as a more efficient alternative, in particular RAF (Retrieval Augmented Forecasting), and introduces RAEF (Retrieval-Augmented Extended Forecasting), a model-agnostic method built upon RAF. RAEF incorporates key refinements to the retrieval and aggregation mechanisms: (1) direct retrieval in input-space rather than embedding-space, reducing inference overhead, and (2) concatenation-based aggregation that preserves temporal structure instead of averaging. Empirical evaluation across multiple benchmark datasets demonstrates that RAEF outperf

---

### [339] SUGFW+: An Uncertainty-guided Feature Weighting Framework for Cold Start Active Adaptation of SAM in Medical Image Segmentation

**链接**: https://arxiv.org/abs/2608.16110
**作者**: Xiaochuan Ma, Ning Zhu, Jia Fu, Lanfeng Zhong, Hanyu Jiang, Bin Song 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cold Start Active Learning (CSAL) is important in improving the performance of a medical image segmentation model with low annotation budget by querying a small subset for annotation from an unlabeled training set. Existing CSAL methods typically rely on inefficient dataset-specific Self-Supervised Learning (SSL) to map the unlabeled images into a feature space for sample selection. Recently, the advent of foundation models such as the Segment Anything Model (SAM) offer a promising alternative as the pre-trained model can provide strong generalizable feature embeddings, and allow high performance in downstream tasks after fine-tuning (adaptation). However, how to systematically exploit SAM's inherent embeddings for cold-start sample selection during adaptation with low annotation budget remains underexplored. To address this, we propose an extended SAM-based Uncertainty-guided Feature Weighting (SUGFW+) framework for CSAL and adaptation of SAM. Specifically, it leverages the SAM for Pa

---

### [340] Don't Claim Benchmark-Oriented Optimization Improves General Coding Capability -- Diverse Evaluation Is Required

**链接**: https://arxiv.org/abs/2608.13566
**作者**: Egor Shibaev, Vera Kudrevskaia, Timur Galimzyanov, Mikhail Evtikhiev, Ana Terna, Rastislav Rabatin 等 (10 人)
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training papers, model cards, and blog posts often treat scores on a small set of coding benchmarks (e.g., SWE-bench and LiveCodeBench) as evidence of broad coding capability, both for research artifacts and user-facing systems. We argue that optimization for these benchmarks leads to measuring task-specific performance, creating a meaning gap between measured scores and claims of general coding ability. We examine this gap with a Django-based case study benchmark suite we create. Evaluating foundation models and checkpoints post-trained on SWE-bench trajectories, we find that benchmark rankings frequently fail to generalize. Post-trained checkpoints show little cross-task transfer, and SWE-bench optimization yields limited or no gains on our tasks or on LiveCodeBench. Similarly, fine-tuning on individual Django modalities fails to transfer. We conclude that a small number of benchmarks is insufficient for evaluating diverse models under benchmark optimization pressure. We encoura

---

### [341] Prototype-Rectified Iterative Self-supervised Manifold Denoising under Severe Acoustic Shift

**链接**: https://arxiv.org/abs/2608.15037
**作者**: Ashish Anand Shukla, Rini Smita Thakur, Aryan Das, Vinod K. Kurmi
**来源**: cs.SD cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-Text Foundation Models (ATMs) fail catastrophically under severe acoustic noise, yet existing adaptation strategies either rely on gradient-based Test-Time Adaptation (TTA), which reinforces noise rather than signal, or on prompt tuning that requires privileged noise annotations unavailable at inference. We address these failures with PRISM (Prototype-Rectified Iterative Self-supervised Manifold Denoising), a training-free, source-free TTA framework grounded in the Affine Noise Hypothesis: severe acoustic noise induces a low-rank affine shift in the multimodal latent space, with more than 90% of distortion energy confined to the leading 60 principal components. PRISM estimates and reverses this distortion from an unlabeled target batch using frozen text prototypes as geometric anchors via three closed-form geometric corrections compiled into a single static projection matrix by Affine Bias Regression. At inference, adaptation reduces to one matrix-vector multiplication in 0.0009 

---
