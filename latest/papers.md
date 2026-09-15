# 📑 论文索引 - 2026-09-16

共 235 篇论文

---

### [1] EventVL: Understand Event Streams via Multimodal Large Language Model

**链接**: https://arxiv.org/abs/2501.13707
**作者**: Pengteng Li and Yunfan Lu and Pinghao Song and Wuyang Li and Huizai Yao and Hui Xiong
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] MAPS: Memory-Aware Predictive Scheduling Framework for Large Language Model Serving

**链接**: https://arxiv.org/abs/2609.15359
**作者**: Tiancheng Zhang, Yulin Chen, Yunfeng Zhao, Shaoyuan Huang, Cheng Zhang, Xiaofei Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The surge of large language model (LLM) applications on personal devices imposes massive, bursty workloads on cloud serving infrastructure. While prefill-decode disaggregation improves throughput and scalability, memory-bound decode instances often suffer from persistent load imbalance, as output lengths are unknown when requests arrive at the cloud. To address this, we propose MAPS, a Memory-Aware Predictive Scheduling framework tailored for disaggregated LLM serving. MAPS performs device-assisted speculative output length prediction overlapped with cloud-side prefilling, incurring negligible latency overhead. To handle generation uncertainty, MAPS applies uncertainty-aware calibration to derive output-length upper bounds with target coverage, enabling safe scheduling decisions. Building on these bounds, MAPS employs a hierarchical global-local scheduling strategy to mitigate inter-decoder queue buildup and intra-decoder head-of-line blocking. Extensive experiments on two real-world w

---

### [3] Evaluating LLM-Generated Rules for Heart Disease Prediction

**链接**: https://arxiv.org/abs/2609.13192
**作者**: Feisal Alaswad, Batoul Aljaddouh, Maher Alrahhal, Wafaa Al Nassan, Talal Bonn
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study compares traditional machine learning models and Large Language Model (LLM)-generated rule-based systems for heart disease prediction using the UCI Heart Disease dataset. Several classifiers, including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Naive Bayes, Decision Tree, and Random Forest, were evaluated alongside rule-based systems generated using GPT-4o and Claude Sonnet 4.6. Model performance was assessed using accuracy, precision, recall, and F1-score metrics. Experimental results show that traditional machine learning models consistently outperform LLM-generated rule-based systems in predictive performance. Random Forest achieved the best overall performance with 90.2% accuracy, a precision of 0.829, perfect recall of 1.0, and an F1-score of 0.906. Naive Bayes followed closely with 88.5% accuracy and an F1-score of 0.881. In contrast, the LLM-generated rule models achieved lower performance, with Claude Sonnet 4.6 reaching 80.3% accur

---

### [4] Hindsight Bias in Clinical Temporal Reasoning: How Future Data Exposure Affects Large Language Model Judgment

**链接**: https://arxiv.org/abs/2609.13454
**作者**: Misaki Matsuura, Sayantan Kumar, Ojas Kadam and Jeremy C. Weiss
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical decisions are prospective, but clinical language models are often evaluated on retrospective records that reveal the final diagnosis, treatment response, and outcome. Such evaluations may reward the use of future information rather than reasoning under the uncertainty present at the decision point. We introduce a paired benchmark for measuring outcome-conditioned shifts consistent with hindsight bias in clinical temporal reasoning. It contains 171 case reports from the PubMed Central Open Access Subset---40 sepsis and 131 GLP-1/diabetes cases---represented as both textual narratives and human-annotated and LLM-generated textual time series (TTS). For each case, questions are tied to a clinically meaningful cutoff and paired with a prospective reference answer and an outcome-consistent \emph{hindsight trap}. Models answer each question using either a TTS truncated at the cutoff or the complete timeline; additional conditions vary the narrative source (original or synthetic) and

---

### [5] STHMoE: Hypergraph-Enhanced Heterogeneous Dependency Coordination for LLM-Based Urban Traffic Data Forecasting

**链接**: https://arxiv.org/abs/2609.15172
**作者**: Jiawen Chen, Qi Shao, Yongjian Chang, Mingtong Zhou, Duxin Chen, Wenwu Yu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatio-temporal traffic forecasting is a fundamental big data analytics task for intelligent transportation systems, where massive urban sensor streams exhibit heterogeneous, non-stationary, and structurally dynamic patterns. Although recent deep learning and large language model (LLM)-based methods have advanced traffic forecasting, they often remain temporally centered and lack effective coordination of temporal, spectral, pairwise spatial, and higher-order structural cues under evolving traffic regimes. To address this heterogeneous dependency coordination problem, we propose STHMoE, a Spatio-Temporal Hypergraph-Enhanced Mixture of Experts framework for urban traffic data forecasting. STHMoE decouples traffic dynamics into frequency-domain, time-domain, spatio-domain, and higher-order spatial representations, which are modeled by prompt-guided heterogeneous experts built upon a partially frozen LLM backbone. The first three experts leverage domain-specific statistical prompts, while

---

### [6] ActGuard: Pre-execution Action Auditing against Indirect Prompt Injection in LLM Agents

**链接**: https://arxiv.org/abs/2609.14987
**作者**: Bingzheng Wang, Xiaoyan Gu, Wentao Wang, Xingyou Yang, Hongcheng Li, Rong Yin
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents interact with external environments through tool invocation, but tool outputs can also expose them to indirect prompt injection (IPI) attacks. Existing defenses mainly rely on prompt hardening, content filtering, pre-generated plans, or permission constraints. These approaches often struggle with complex tasks or over-sanitize external content, making it difficult to balance security and utility. The key challenge is therefore to preserve execution flexibility while precisely identifying and removing the malicious content that actually induces unsafe actions. To address this challenge, we propose ActGuard, a pre-execution action auditing framework. Rather than judging whether external content is inherently suspicious, ActGuard assesses whether it causes the current action to deviate from a locally reasonable expectation. At each step, ActGuard predicts the tools likely to be used by the upcoming action and constructs a local tool prior without constrai

---

### [7] MoARa: Module-Aware Rank Allocation and Structure-Preserving Decomposition for Low-Rank LLM Pre-training

**链接**: https://arxiv.org/abs/2609.15037
**作者**: Keunyoung Kim, Nojun Kwak
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-rank gradient projection reduces the optimizer-state memory cost of large language model (LLM) pretraining, but the steps and wall-clock time needed to reach a target quality remain a meaningful axis for improvement. We attribute this to two design choices in existing methods: the projection-rank budget is allocated uniformly across Transformer modules with heterogeneous projection sensitivity, and projecting a raw gradient attenuates its magnitude and direction jointly. We propose MoARa, which combines a static profiling-based module-aware projection-rank allocation with a block-wise magnitude-direction decomposition; the default block size is set in the neighborhood of the attention head dimension. Across five Transformer architectures spanning Llama, Qwen, and DeepSeek at 300M to 7B scales, GaLore with MoARa reaches standard GaLore's final perplexity in 37% fewer steps and 34% less wall-clock time on Llama 2 7B, with only 0.2% peak reserved memory overhead under standard graph c

---

### [8] What Does an LLM Learn from Reinforcement Learning? A Mechanistic Interpretability Perspective with Fixed-SAE Track

**链接**: https://arxiv.org/abs/2609.15064
**作者**: Lingheng Du, Yiming Tang, Xufeng Duan, Dianbo Liu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) is widely utilized in large language model training to improve targeted capabilities, yet how RL reshapes a model remains poorly understood. Prior attempts to explain how RL works largely offer behavioral perspectives, leaving open what RL gives a model at the representation level: can RL create genuinely novel features, and which existing features does it enhance or suppress? Recent developments in mechanistic interpretability suggest sparse autoencoders (SAEs) as a promising lens to decompose internal activations into human-interpretable features; however, they cannot be directly applied to tracking change across training. In this work, we introduce Fixed-SAE Track, a framework that trains one shared SAE per considered layer on activations pooled across the base model and all RL checkpoints, holding every feature direction fixed so that representation shifts are rigorously defined through the activations of interpretable SAE latents, including the detectio

---

### [9] LLM-Based Schema-Aware Split Learning for Privacy-Preserving Mental Distress Prediction Across Heterogeneous Surveys

**链接**: https://arxiv.org/abs/2609.15871
**作者**: Md Khalid Syfullah and Alvi Ataur Khalil
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rising societal and lifestyle complexity has been linked to a growing prevalence of mental distress worldwide. Educational institutions, workplaces, clinics, etc. collect large volumes of mental health survey data to understand and reduce this burden. Collaborative analysis of such data could yield effective generalizable predictive models. Privacy constraints and varied survey designs (i.e., different questions, scales, and formats) hinder direct integration. We propose a schema-aware split learning (SL) framework that preserves privacy, using a large language model (LLM) as a shared semantic encoder to harmonize heterogeneous survey schemas across institutions. We serialize each survey record into a natural-language description, unifying disparate survey schemas into a common format. The LLM is fine-tuned for mental distress assessment via Low-Rank Adaptation (LoRA) and partitioned across client and server. Clients retain the raw survey responses locally and run only a lightweight fr

---

### [10] Natural Language Knowledge Graph Query Execution: Leveraging Controlled Semantics in the LLM Context Window

**链接**: https://arxiv.org/abs/2609.14652
**作者**: Blake G. Fitch
**来源**: cs.DB cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) applications often transfer domain concepts into the model's context informally, through prompt prose, schema dumps, and examples. We show that for database queries, data model concepts pass to LLMs more effectively through representations whose vocabulary terms carry declared, machine-readable semantics (controlled semantics). NLKGQ is a working system and reusable framework that does this for data modeled in a knowledge graph. A formal OWL ontology serves as the transfer mechanism, concentrating the meaning of the data into semantically precise tokens the model can use directly. In a single LLM call, NLKGQ places in the context a system prompt instructing on SPARQL, the complete domain OWL ontology, and a domain-specific prompt addition, together with the user's natural language query. The model then generates the SPARQL query directly, zero-shot. Where the native vocabulary of an existing database or federation of databases is opaque, a wrapper ontology su

---

### [11] IROH: Insightful Ranking Of Humor using Multi-Stage Hybrid Retrieval with Rationale-Distilled LLM Judges for JOKER 2026 Track Task 1 English

**链接**: https://arxiv.org/abs/2609.15618
**作者**: Ana-Maria Luisa Mocanu, Sebastian Mocanu, Ciprian-Octavian Truic\u{a}, Elena-Simona Apostol
**来源**: cs.IR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Our team, VANGUARD, presents IROH (Insightful Ranking of Humor), a three-stage retrieval system for JOKER Task 1 English at CLEF 2026, achieving first place on the leaderboard with 0.6347 MAP. Our pipeline combines hybrid sparse-dense retrieval, cross-encoder reranking, and a LoRA-adapted Large Language Model judge ensemble. We employ Gemma 4 to generate query-aware rationales under two prompt strategies, generic and typed, and produce up to four types of structured hard negatives for training data construction. Through an ablation across three cross-encoder architectures, four dense embedders, and eight judge configurations, our key findings are threefold: (1) the rationale-distilled judge is the primary driver of ranking quality, whereas appending rationales to the first-stage index contributes negligibly; (2) structured hard negatives degrade generalisation in nearly all configurations despite inflating local validation scores; and (3) across the components we ablate, the lighter, b

---

### [12] When Agents Slow Down: Understanding LLM Agents' Test-Time Strategies via Elo-per-token Analysis

**链接**: https://arxiv.org/abs/2609.15309
**作者**: Kaiyuan Liu, Qiuyang Mang, Bo Peng, Wenhao Chai, Hanchen Li, Shreyas Pimpalgaonkar 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents allocate test-time compute adaptively as they revise solutions, use tools, explore alternatives, and decide when to stop. This test-time strategy makes it difficult to measure how agent performance scales. We study open-ended tasks that provide continuous scores for intermediate submissions, making progress observable throughout long trajectories. We propose Elo-per-token analysis, which tracks the best solution found at each token budget and uses a Bradley-Terry model to aggregate within-task orderings into Elo ratings across tasks with different score scales. We apply it to four general-purpose agents on four open-ended benchmarks, with sessions of up to 100M tokens, and to three feedback-driven LLM optimization harnesses in controlled single-task interventions. Independent sampling provides a theoretically characterized reference, for which Elo grows linearly with log compute. Against this reference, agents can initially convert tokens into Elo fast

---

### [13] DiVA: Enabling Interactive Digital Life Simulation via Video Models

**链接**: https://arxiv.org/abs/2609.13830
**作者**: Cheng Chen, Hao Ouyang, Qiuyu Wang, Ka Leong Cheng, Wen Wang, Yihao Meng 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present DiVA, a deeply interactive digital life simulator pioneering a new paradigm for long-term, open-ended interactive experiences within digital character worlds. DiVA's architecture pairs a Multimodal Large Language Model (MLLM) as a router with a meticulously designed stacked video pipeline for seamless, multi-turn interactions with action and audio response. To maintain continuity and avoid degradation, we model generation as a three-part coupled system: waiting video, action video, and the transitions between them. These transitions are critically handled by our Anchored Video Continuation (AVC) module, which returns the character to stable states to prevent degradation. By encoding information from the preceding action video segment, AVC ensures smooth transitions, significantly reducing camera jitter and inconsistencies common in current video transition methods. This design also enables complex pose changes (e.g., sitting to standing) typically difficult for audio-driven 

---

### [14] LLaTSA: Large Language Model-Aligned General-Purpose Transient Stability Analysis

**链接**: https://arxiv.org/abs/2609.14374
**作者**: Chao Shen, Hongwei Zhen, Junyan Shao, Zhenghao Yang, Yifan Zhang, Mingyang Sun
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic trajectory prediction has become an important paradigm for data-driven transient stability analysis (TSA), yet most existing predictors remain system-specific and require substantial retraining when network configurations, generation mixes, or state-variable sets change. Uni-TSA introduced a general-purpose TSA framework that combines channel-independent modeling with a pretrained large language model (LLM) predictor. Nevertheless, its application to heterogeneous systems is limited by ambiguity in short observations, a mismatch between numerical trajectories and LLM embeddings, neglected coupling among state variables, and the high inference cost of dense backbones. This paper proposes LLaTSA, an LLM-aligned framework for general-purpose trajectory-based TSA. LLaTSA first incorporates operating conditions, disturbance attributes, and state-variable identity through a structured textual prefix. It then aligns normalized temporal patches with a TSA-related vocabulary before proc

---

### [15] LLM-Enhanced Multi-Agent Reinforcement Learning for Unified Electric Vehicles-Charging Station-Grid Optimization in Public Charging Systems

**链接**: https://arxiv.org/abs/2609.13805
**作者**: Yang Zhang, Lindong Xie, Chongyu Wang, Gaojunjie Li, Siqi Bu, and Edward Chung
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the era of the Internet of Things (IoT), coordinating connected electric vehicle (EV) charging scheduling to balance EV charging satisfaction, station profitability, and smart grid stability presents a complex multi-objective challenge. Existing Multi-Agent Reinforcement Learning (MARL) approaches often struggle with high-dimensional state spaces generated by massive IoT sensing data and conflicting stakeholder interests. This paper proposes a novel LLM-enhanced MARL framework that, for the first time, simultaneously optimizes the Grid, EVs, and Stations within a unified loop. By integrating Large Language Model (LLM), we address two critical bottlenecks: interpretable feature selection and adaptive multi-objective balancing. The LLM analyzes real-time IoT-collected environmental states to extract physically significant features and dynamically assigns weights to conflicting objectives-including profit, user satisfaction, and grid load-using semantic reasoning instead of complex man

---

### [16] BOOST: Concurrent Access to Host Memory and HBM to Accelerate LLM Inference

**链接**: https://arxiv.org/abs/2609.13592
**作者**: Anish Saxena, Jae Hyung Ju, Hritvik Taneja, Po-An Tsai, Aamer Jaleel, Christos Kozyrakis 等 (7 人)
**来源**: cs.DC cs.AR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> GPU memory bandwidth and capacity limit throughput in large language model (LLM) inference. The GPU memory system consists of a primary tier of high-bandwidth memory (HBM) and a secondary tier of host memory connected via CPU-to-GPU interconnect. Current serving systems treat the tiers hierarchically: they serve exclusively from HBM when data fits, and otherwise prefetch data from host memory to HBM before use. In both cases, the host memory bandwidth is never well utilized. Prefetching expands capacity by utilizing host memory, but consumes HBM bandwidth for writes, reducing the bandwidth available for demand loads. We observe that fully utilizing both host and HBM bandwidth requires each wave of GPU threadblocks to access both tiers concurrently and in proportion to their bandwidth ratio. Existing bandwidth-proportional placement strategies fail to provide concurrency because they are not aware of GPU waves, and the large 2MB GPU page size. This paper presents BOOST, the first runtim

---

### [17] Toward Self-Adaptive Physical AI: Can LLM Agents Manage Long-Horizon Physical Tasks?

**链接**: https://arxiv.org/abs/2609.13436
**作者**: Varun Kaushik, Yayun Tan, Xiaofan Yu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents offer a promising path toward autonomously managing long-term physical tasks without human intervention. However, physical tasks require agents to continuously observe the environment, make consequential actions, and remain effective as the environment changes. Existing approaches either require substantial data and retraining, or primarily focus on agents operating in the virtual world. In this work, we explore the feasibility of building a self-adaptive physical AI agent that manages long-term physical tasks in a zero-shot manner and adapts to environmental changes without human intervention. We design a multi-agent framework that integrates planning, tool calling, observation, and verification, and evaluate it on agricultural tasks against reinforcement learning (RL) agents under different weather patterns. Our results show that zero-shot LLM agents can achieve comparable management outcomes to RL agents under the same weather pattern and adapt more

---

### [18] The Stochastic Deputy: Structural Tenant Isolation for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2609.14780
**作者**: Mirza Samad Ahmed Baig, Syeda Anshrah Gillani, Asher Ali, Muhammad Hamzah Siddiqui
**来源**: cs.CR cs.AI cs.DB cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-tenant tools commonly accept a tenant identifier and validate it against the caller's entitlement. For a large language model (LLM) agent, that pattern delegates resource selection to a process whose context may contain attacker controlled instructions. We formalize this stochastic deputy problem and present a structural defense: remove tenant identity from the Model Context Protocol (MCP) tool schema, bind scope to a verified credential, and enforce it below the agent. In a 373-trial ablation across eight model configurations and two transports, a correctly validated tenant parameter served every out-of-scope attempt: 26 of 26, or 26 of 41 plausible-pretext trials overall. With the parameter removed, no tool signature could express the read. Twelve of 56 trials instead escaped the interface by forging writable scope, showing that interface invariance requires cryptographically protected context. On a production dataset containing multiple GBs of data, set-valued scope caused a m

---

### [19] HypoEvolve: Genetic Algorithms Enable Multi-Agent LLMs to Discover Scientific Hypotheses

**链接**: https://arxiv.org/abs/2609.15938
**作者**: Jieyuan Liu, Mengzhou Hu, Jefferson Chen, JungHo Kong, Pratibha Jagannatha, Yiming Gao 等 (10 人)
**来源**: cs.CL cs.CE cs.MA cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific agents contribute to hypothesis discovery by synthesizing evidence, assessing proposals, and developing new explanations. Recent systems combine scientific agents with evolutionary search through critique, comparison, and revision. However, how different forms of agent collaboration affect hypothesis quality remains an open question. Answering this question requires separating the effects of agents' scientific capabilities from those of their collaboration. A framework must therefore preserve agents' scientific roles and support rules for combining, revising, and retaining hypotheses. Building on this view, we introduce HypoEvolve, which makes collaboration explicit through successive updates to a hypothesis population. Specifically, we propose a generational genetic algorithm to coordinate specialized large language model (LLM) agents that integrate mechanistic arguments, reconsider assumptions, and assess evidence and testability. Each generation specifies how scientific j

---

### [20] AlgoRAG: Retrieval-Augmented Generation for Theoretical Computer Science Education -- A Comprehensive Evaluation Framework for Algorithm Analysis and Complexity Theory

**链接**: https://arxiv.org/abs/2609.14572
**作者**: Sushan Adhikari
**来源**: cs.CY cs.AI cs.IR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Teaching abstract theoretical computer science (TCS) concepts such as algorithm analysis and complexity theory is challenging because students must handle formal proofs and asymptotic reasoning that conventional resources rarely explain in an adaptive, on-demand way. We present AlgoRAG, a specialized Retrieval-Augmented Generation (RAG) system that couples a large language model (LLM) with a curated, domain-specific knowledge base to address these challenges. The knowledge base integrates authoritative textbooks, 847 lecture slides, 312 practice problems with solutions, 156 worked proof templates, and 89 complexity worksheets. AlgoRAG incorporates domain-specific optimizations including mathematical entity recognition, notation-aware retrieval, and pedagogical re-ranking. We evaluate AlgoRAG on 179 curated exam-style questions spanning asymptotic analysis, recurrence relations, dynamic programming, graph algorithms, NP-completeness, sorting, and divide-and-conquer. The system achieves 

---

### [21] Introspective Uncertainty Estimation for LLM-Based Code Generation

**链接**: https://arxiv.org/abs/2609.13975
**作者**: Thomas Klassert
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used for code generation but can produce fluent yet functionally incorrect outputs, which limits trust in their usage for practical software engineering workflows. This thesis investigates whether Introspective Uncertainty Estimation (IUE), based on internal hidden-state representations of LLMs, can reliably indicate correctness at the response and line levels for code generation tasks. The objective is to determine the extent to which hidden states encode information about functional code correctness and how this can be leveraged for practical risk assessment and fault localization. Methodologically, this thesis combines response-level evaluation on LiveCodeBench (LCB) and BigCodeBench (BCB) with an augmentation pipeline that derives token- and line-level labels from incorrect programs. In this setup, it compares static and dynamic response-level features, evaluates generalization across tasks, programming domains, and token positions, and

---

### [22] Rubrics as an Attack Surface: Stealthy Preference Drift in LLM Judges

**链接**: https://arxiv.org/abs/2602.13576
**作者**: Ruomeng Ding, Yifei Pang, He Sun, Yizhong Wang, Zhiwei Steven Wu, Zhun Deng
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] PhysMent: An Interactive Approach For LLM Reasoning In Physics Problems

**链接**: https://arxiv.org/abs/2609.13152
**作者**: Joseph Chan, Utkarsh Jha, Xiyin Yang, Abhinav Jarajapu, Anik Sahai, Eddie Hu 等 (9 人)
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) perform strongly on static science benchmarks, yet their ability to reason about the physical world through active experimentation remains poorly understood. We introduce PhysMent, a benchmark that evaluates LLM physical reasoning via iterative, toolmediated interaction with a MuJoCo physics simulator. Unlike static benchmarks that supply all quantities upfront, PhysMent requires models to discover information by applying forces, querying object states, advancing time, and modifying scene geometry before answering. The benchmark comprises 105 scenes of classical mechanics, organized across four difficulty regimes (Easy/Hard and Single/Multi), three scene modalities (standard, object creation, hidden objects), and a scene-manipulation category, evaluated with a six-dimensional scoring framework. Results show that current models perform reasonably well on qualitative single-concept tasks (up to 80% accuracy) but degrade substantially on quantitative tasks tha

---

### [24] Per-Matrix Optimality Is Not Enough: Three-Level Optimization for Low-Rank LLM Compression

**链接**: https://arxiv.org/abs/2609.15838
**作者**: Huicheng Zhang, Xiyao Feng, Ze-Tong Li, Chengkai Zhu, Xiao Shi, Xiwei Pan 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Per-matrix singular value decomposition (SVD) truncation is Eckart-Young optimal in the whitened Frobenius norm, but errors from independently compressed matrices compound through the block's nonlinear forward pass. Inspired in part by hierarchical variational optimization in quantum many-body methods, we introduce a three-level chain that widens optimization scope from individual matrices to Transformer blocks to the full model: whitened SVD~(L1), block-level joint optimization~(L2), and end-to-end language-modeling loss refinement~(L3), all from 256 calibration sequences, with no instruction or recovery data. On LLaMA-7B at 60% compression, the chain reduces WikiText-2 perplexity from 42.1 to 19.1 to 11.4. The block-level stage acts as a regularizer: skipping it worsens Penn Treebank (PTB) perplexity by 24 points, a gap that additional end-to-end training did not close in our experiments. Perplexity gains hold across 20-80% compression, five architectures up to 13B parameters, and bo

---

### [25] ModiGen: A Large Language Model-Based Workflow for Multi-Task Modelica Code Generation

**链接**: https://arxiv.org/abs/2503.18460
**作者**: Jiahui Xiang, Tong Ye, Peiyu Liu, Yinan Zhang, Wenhai Wang
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] When Single-User-Oriented LLM-based Assistants Involve Others: A Scoping Review of Pathways, Risks, and Responses

**链接**: https://arxiv.org/abs/2609.14062
**作者**: Yulin Chen, Yang Zhan, Zhuoran Lu, Qiao Jin
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based assistants are increasingly extending into multi-party contexts, while core operational processes for context management, personalization, identity attribution, authority attribution, and action execution often remain organized around a single user. Existing work examines particular multi-party settings, but lacks a systematic account of how these single-user-oriented assistants begin to involve additional human parties and what risks emerge. To address this gap, we conducted a scoping review of 58 studies. We identify five operational pathways spanning direct and indirect involvement, five recurring risk domains, and five areas of implemented and proposed responses. Based on these findings, we argue for governance that attends to changing cross-person roles and relationships in practice, and for assistant designs that preserve person-specific boundaries throughout interaction.

---

### [27] PortBench: A Correlation-Aware, Full-Pipeline Benchmark for LLM-Driven Portfolio Management

**链接**: https://arxiv.org/abs/2605.27887
**作者**: Yuxuan Zhao, Sijia Chen, Ningxin Su
**来源**: cs.AI q-fin.PM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] PolicyMem: Geometric Policy Memory for LLM Governance

**链接**: https://arxiv.org/abs/2609.13734
**作者**: Yuanchen Bei, Zhengzhang Chen, Yanjun Zhao, Haoyu Wang, Hanghang Tong, Haifeng Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly deployed in real-world high-stakes applications, effective governance has become essential. Existing safeguards largely follow two paradigms: learning-based guards provide strong semantic discrimination but couple policy behavior to trained models and taxonomies, while programmable frameworks offer flexible control but require substantial manual prompt and workflow engineering. Neither externalizes policies as reusable operational states, making it difficult to consistently reuse policy evidence across detection, intervention, and verification. In this paper, we introduce PolicyMem, a geometric policy memory that externalizes natural-language policies as reusable geometric memory objects represented by low-rank subspaces in a shared representation space. A memory writer compiles natural-language policies into policy memory slots, and query-response pairs read the policy memory through projection energy. The resulting policy-evidence prof

---

### [29] SMetric: Rethink LLM Scheduling for Serving Agents with Balanced Session-centric Scheduling

**链接**: https://arxiv.org/abs/2607.08565
**作者**: Jiahao Wang, Kaizhan Lin, Kaixi Zhang, Jinbo Han, Xingda Wei, Sijie Shen 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] TATK: Triple-Aware Top-K Learning with Knowledge-Grounded Verification for LLM-based Sequential Recommendation

**链接**: https://arxiv.org/abs/2609.14565
**作者**: Yuchen Guan, Jiaye Liu, Yifei Han, Zhenxi Zhang, Yixuan Weng, Bin Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based sequential recommenders usually cast next-item prediction as text generation, but this interface is poorly matched to full-catalog top-K ranking. We propose TATK, a Triple-Aware framework that couples Top-K Learning (TKL) with Knowledge-Grounded Verification (KGV) for LLM-based sequential recommendation. Top-K Learning combines context-aware metadata-KG prompt grounding with position-aware top-K rewards, aligning training with ranking utility; Knowledge-Grounded Verification then applies structure-aware reranking over the top-M candidates after a single LLM forward pass, using the same metadata-derived item graph. We evaluate TATK on Musical Instruments, CDs and Vinyl, and Video Games from Amazon Reviews 2023 under a matched R2ec-style full-catalog protocol. Experiments use Gemma-2-2B-It and Qwen2.5-3B-Instruct backbones, compare against sequential, generative, KG-augmented, and reasoning-enhanced baselines, and include component, reward-shape, sequence-perturbation, rerankin

---

### [31] Exploring Automated Vulnerability Identification in JavaScript Code Using Large Language Models

**链接**: https://arxiv.org/abs/2609.13816
**作者**: Manit Kaushik, Ishir Bhardwaj, Pranav Gupta, Pankaj Jalote, Arun Balaji Buduru
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> JavaScript powers approximately 98.8% of all websites, making vulnerabilities in its code a significant security risk, yet existing detection approaches such as Static Application Security Testing (SAST) tools often fail to identify many real-world vulnerabilities when applied to isolated code snippets. This paper presents an empirical study of Large Language Model (LLM)-based vulnerability identification for JavaScript programs, evaluating three LLM families (Gemini 1.5 Flash, GPT-4o Mini, DeepSeek-R1-Distill-Llama-8B) across multiple prompting strategies (zero-shot, chain-of-thought, few-shot) and fine-tuning approaches on a dataset of 1,125 JavaScript code snippets spanning five Common Weakness Enumeration (CWE) categories: Injection (CWE-74), OS Command Injection (CWE-78), Cross-Site Scripting (CWE-79), SQL Injection (CWE-89), and Uncontrolled Resource Consumption (CWE-400). Our experiments show that LLMs substantially outperform traditional SAST tools on snippet-level vulnerabilit

---

### [32] The Universe of Universes: Benefit Yield Functions, Implosion Thresholds, and Infrastructure-Aware Optimization in Multi-LLM Systems

**链接**: https://arxiv.org/abs/2609.15314
**作者**: Danielle Franklin, Vasu Raj Jain
**来源**: cs.LG cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce the Universe of Universes (UoU) framework, which treats the full ecosystem of major large language models (LLMs) as a structured retrieval corpus and proposes a compositional Automated Reasoning (AR) and Machine Learning (ML) architecture for cross-model retrieval-augmented generation. The central contribution is the formal characterization of the Benefit Yield Function (BYF), the marginal performance gain per additional model added to an ensemble, and the identification of the implosion threshold {\theta}*: the ensemble size at which BYF crosses zero and aggregate performance begins to degrade. Existing LLM ensemble and mixture-of-agents systems treat models as responders and aggregate outputs, but do not study performance as a function of ensemble size N across the full model universe. Benchmark research confirms performance plateaus at the individual model level; model collapse literature establishes that iterative training on AI-generated outputs degrades individual mo

---

### [33] AURA: Unified Multimodal Framework for Conversational Music Editing

**链接**: https://arxiv.org/abs/2609.14344
**作者**: Quoc-Huy Trinh, Minh-Van Nguyen, Debesh Jha
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Instruction-guided music editors typically process each request independently, limiting their ability to support workflows in which users progressively refine a track. We introduce AURA, a unified multimodal framework for conversational music editing. AURA uses a multimodal large language model to interpret the complete dialogue history, an optional image, and reference audio, distilling the editing intent into compact concept tokens. A concept-to-audio module injects these tokens and frame-aligned reference features into a frozen MusicGen backbone, enabling precise edits while preserving unaffected content. AURA optimizes only 91M parameters while retaining 1.9B frozen backbone parameters. Experiments on Slakh2100 and MoisesDB demonstrate substantial improvements in edit correctness and content preservation over existing instruction-guided methods, including a 4-5 times reduction in FAD for out-of-domain addition and removal.

---

### [34] Four Ledgers, Not One Score: Responsible Communication of LLM-Judge Calibration in Biomedical ML

**链接**: https://arxiv.org/abs/2609.15015
**作者**: Sidi Chang, Peiying Zhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic perturbations appear to offer inexpensive calibration data for LLM evaluators in biomedical ML, where expert review is scarce. Yet a planted mutation key is neither a detector output nor automatically human ground truth. We formalize four distinct ledgers: planted perturbations, independent detector outputs, source-linked human dispositions, and human-added discoveries. We then audit the evaluation design, scoring code, read paths, and current human records of a private synthetic Japanese care-handoff workflow. The factory stored 69 planted error cards across 47 targets. Final review covers 22 targets and contains 22 confirmed imported proposals, 9 rejected proposals, and 79 human-added cards; only 3 reviewed targets are double annotated. Passing imported plant keys to a generic detector scorer yields 22/(22+9)=0.710 and 22/(22+79)=0.218. A direct audit identity shows that these values are proposal-confirmation yield and submitted-ledger composition, not judge precision and r

---

### [35] Generate to Explore, Select to Exploit: Aligning LLM-based Headline Generation with Personalized Recommendation

**链接**: https://arxiv.org/abs/2609.15094
**作者**: Yi Chen, Rufeng Cheng, Qiang Xie, Tao Li
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In industrial recommendation feeds, presenting a static headline for an item often fails to satisfy the diverse, multimodal interests of the user population, particularly suppressing the needs of long-tail audiences. While Large Language Models (LLMs) have been integrated into recommendation for content understanding or ranking, directly optimizing them to output a single best headline typically leads to mode collapse---converging to generic patterns that satisfy average tastes but miss specific latent intents. To bridge this gap, we introduce GESE (Generate to Explore, Select to Exploit), a framework operating at the system's presentation layer that decouples personalization into generative exploration and selective exploitation. First, we treat the LLM as a probabilistic explorer, utilizing Group Sequence Policy Optimization (GSPO) with a hierarchical reward mechanism to generate a candidate set that maximizes the semantic coverage of potential user interests. Subsequently, a lightwe

---

### [36] Self-Indexing Attention for Compression-Compatible Sparse Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2609.13205
**作者**: Xu Yang, Jiapeng Zhang, Zhangke, Changjian Chen, Yuxin Chen, Feiqiang Sun 等 (9 人)
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse long-context inference requires efficient token retrieval in both prefill and decode. Existing methods often use different retrieval strategies for the two stages, preventing one retrieval representation from being reused throughout inference. We propose Self-Indexing Attention, a training-free framework built on a shared transform-domain sign-magnitude representation. The key signs provide a reusable token-level index for grouped prefill selection and decode retrieval, while the same representation remains compatible with external KV-cache compression without separate indexer metadata. This 1-bit index enables efficient retrieval through bitwise operations widely supported by modern accelerators. At 5% attention density, Self-Indexing Attention remains close to dense attention on LongBench and RULER and achieves up to 6.1x prefill and 10.3x decode attention-operator speedups. Experiments with TurboQuant and DeepSeekV4-Flash further demonstrate compatibility with low-bit KV-cach

---

### [37] LayerRoute: Adaptive Layer-Skipping with LoRA-Preserved Quality for Efficient LLM Inference

**链接**: https://arxiv.org/abs/2609.13682
**作者**: Prateek Kumar Sikdar
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce LayerRoute, a parameter-efficient method for adaptive transformer layer-skipping that combines per-layer hard-gated routing (trained via a straight-through estimator) with joint LoRA fine-tuning. LayerRoute augments each of the 24 transformer blocks in Qwen2.5-0.5B-Instruct with a lightweight per-layer router (~21.5K parameters) and LoRA adapters (rank 8, ~1.08M parameters), training both jointly under a gate-regularized language-modeling objective. Across 10 independently-seeded training runs, LayerRoute converges to an identical skip-pattern structure in every run - a consistent set of 9 middle layers (8-16) becomes skip-eligible in all 10 seeds - and delivers genuine, verified wallclock speedup in every run (1.02x-1.06x, mean 1.04x). Quality is preserved or improved in every configuration tested: joint LoRA adaptation yields a perplexity improvement over the unmodified backbone in all 10 seeds (mean delta = -1.16 and -1.11 across the two evaluation splits used). We furt

---

### [38] Inter-Rater Reliability of LLM and Rule-Based Annotation for Inferential Narrative Features: Three Studies on a Turkish Corpus

**链接**: https://arxiv.org/abs/2609.13936
**作者**: Levent Bulut
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Datasets that ship automatically generated feature annotations invite a question rarely asked of them: would a human agree with those labels? This report answers that for the Objective Projection corpus, a Turkish narrative dataset whose scenes carry a per-scene applied_rules field from a rule-based detector over six craft features -- two prohibitions (emotion labelling, simile) and four positive techniques (materialized metaphor, micro-focus, temporal anchor, atmosphere contradiction). Three studies are reported. Study 1 ($n = 120$) scores the detector against blind labels from the scheme's own author. Study 2 ($n = 100$, a disjoint scene set) scores the detector plus Gemini 2.5 Flash and Grok against an independent non-expert rater whose labels were locked before any machine ran. Study 2b re-runs the identical protocol with Claude Fable 5 (High) and ChatGPT 5.5. The central result concerns one rule. On materialized metaphor -- closest to the methodology's theoretical core -- the five

---

### [39] DeepFeature: LLM-Empowered Context-aware Feature Generation for Wearable Biosignals

**链接**: https://arxiv.org/abs/2512.08379
**作者**: Kaiwei Liu, Yuting He, Bufang Yang, Mu Yuan, Chun Man Victor Wong, Ho Pong Andrew Sze 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] ClinAgent: A ReAct-Based Agent for Conversational Access to Clinical Trial Information

**链接**: https://arxiv.org/abs/2609.13860
**作者**: Antonino Vaccarella, Riccardo Cantini, Domenico Talia, Paolo Trunfio, Marianna Talia, Rosamaria Lappano 等 (7 人)
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Querying clinical trial registries remains a manual and error-prone process, requiring researchers to navigate large volumes of semi-structured data without support for natural language interaction or cross-source synthesis. To address this, we introduce ClinAgent, a conversational system based on agentic Retrieval-Augmented Generation (RAG) that enables clinicians and researchers to query clinical trial information in plain language and receive grounded, up-to-date responses across multi-turn interactions. The system centers on a Large Language Model (LLM) agent following the ReAct paradigm, which iteratively reasons over queries, selects among a set of integrated tools, and refines its actions based on intermediate outputs. These tools include a ClinicalTrials.gov search interface, a PubMed module, and a Python-based analyzer operating on a locally cached structured dataset of clinical trials. We evaluate the system using a three-phase framework assessing operational effectiveness, p

---

### [41] CIDERS: Cloud-Edge LLM Collaborative Learning via Accelerating Personalized Bilevel Optimization

**链接**: https://arxiv.org/abs/2609.15664
**作者**: Victor H. Chen, Hairui Yu, Stella K. Chung and Hong Yan
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Amid the rapid advancement of physical-world intelligence, cloud-edge collaborative large language models (LLMs) have emerged as a promising roadmap for practical LLM deployment. However, existing cloud-edge paradigms struggle to balance global consensus with local personalization, which fails to satisfy the need for a unified knowledge foundation on the cloud and domain-specific adaptation at the edge. To address this, we introduce, for the first time, a personalized bilevel optimization framework that formalizes cloud-edge LLM collaboration as a dual structure: the upper level optimizes edge-side personalization, while the lower level governs cloud-side knowledge transfer, reaching cloud-edge evolving in coordination. We then propose CIDERS, an efficient solver that decomposes the model into a learnable backbone and a messenger. While the cloud performs knowledge transfer to the learnable backbone, the key lies in embedding global trajectories into each local personalization step via

---

### [42] Calibrating Interpretability Instruments Before Trusting Their Verdicts

**链接**: https://arxiv.org/abs/2609.14754
**作者**: Orion Reblitz-Richardson
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal claims about large language model (LLM) internals rest on measurements. Those might include a projection, a cosine, an ablation delta, or an interchange patch among others. These measurements fail in specific, diagnosable ways that return a plausible number instead of an error, so a broken instrument can easily read as a finding. A covariance-matched null can saturate until every direction looks typical, a per-head attribution can overshoot the true residual write threefold on reordered-normalization architectures, an interchange patch can go sign-chaotic because its outcome is pinned at a ceiling, or a read-from verdict can be an artifact of measuring past the layer where the model already decided. This note documents six such failures from a causal interpretability program on refusal and moral representation, spanning several papers and a four-model open-weight panel; each mode is established on one or two of the four. For each we give the tell that catches it and a protocol k

---

### [43] EMR: Self-Evolving Medical Multi-Agent System via Experience Mining and Reuse

**链接**: https://arxiv.org/abs/2609.15161
**作者**: Dongsheng Shi, Yue Li, Xin Yi, Linlin Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) driven multi-agent systems have shown promise in complex clinical reasoning, yet existing approaches rely on static strategies and lack persistent clinical memory, preventing self-evolving from prior diagnostic successes and failures. We present EMR, a self-evolving medical multi-agent system via Experience Mining and Reuse. EMR introduces a hierarchical clinical experience library that organizes accumulated knowledge into three levels: clinical principles, diagnostic patterns, and representative cases. During inference, EMR emulates multidisciplinary consultation: a planner agent coordinates domain-specific department agents for specialized reasoning, while a summary agent synthesizes their analyses into a final decision. Critically, EMR automatically extracts correct diagnostic insights and failure-related warnings from multi-agent reasoning trajectories, incrementally updating the experience library to guide future cases. Experiments on medical reasoning b

---

### [44] Concertina: Data-Centric Adaptive Pipeline Parallelism for Efficient Heterogeneous Long-Context LLM Training

**链接**: https://arxiv.org/abs/2509.21275
**作者**: Shiju Wang, Yujie Wang, Fangcheng Fu, Ao Sun, Yinxiao Feng, Zijian Zhu 等 (9 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] How Semantically Stable Are LLM Refusals? Measuring Confusion in Local Safety Boundaries

**链接**: https://arxiv.org/abs/2512.01037
**作者**: Riad Ahmed Anonto, Md Labid Al Nahiyan, Md Tanvir Hassan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Pull: Lazy Materialization of Working Memory for Stateful LLM Conversations

**链接**: https://arxiv.org/abs/2609.14773
**作者**: Jiangang Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM conversations grow to hundreds of turns, full-context injection incurs $O(N^2)$ cumulative token costs, while lossy summarization or hard truncation irreversibly discards historical state. We propose Pull, a session router that maintains an addressable metadata directory via a local, deterministic Purifier (zero LLM calls, millisecond-level latency). At query time, the LLM lazily materializes only the turns it needs; unmaterialized turns remain accessible but collapsed. Unlike irreversible compression, Pull's materialization is reversible; subsequent queries can expand any collapsed turn. On LoCoEval (128 conversations, 12,780 turns), Pull reduces per-query context tokens (Phase 2) by 75.1 percent on single-hop tasks with equivalent quality ($\Delta = -0.002$, n.s.) and by 72.0 percent on multi-hop tasks with no quality loss ($\Delta = +0.017$). A controlled routing benchmark (7,831 queries x 10 methods) shows that entity lifecycle tracking is empirically a prerequisite for dist

---

### [47] Carbon-Aware Routing for Function Calling in Edge-Cloud LLM Systems

**链接**: https://arxiv.org/abs/2609.13559
**作者**: Aikaterini Maria Panteleaki, Varatheepan Paramanayakam, Spyros Tragoudas, Iraklis Anagnostopoulos
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) with function-calling capabilities are becoming critical for modern agentic AI systems. Nevertheless, current deployments typically route inferences to powerful cloud-based models, incurring significant energy use and carbon emissions. We address this sustainability challenge with a carbon-aware routing framework that distributes function-calling queries across a three-tier edge-cloud architecture, combining edge and cloud LLMs on heterogeneous hardware. At its core, a lightweight k-NN predictor operating in a unified semantic-lexical embedding space estimates query-specific accuracy, delay, and power consumption on each edge tier. These predictions are then combined with real-time grid carbon intensity to route every query to the lowest-emission tier capable of executing it successfully. Evaluated on state-of-the-art function-calling benchmarks and LLM families, our framework matches cloud-level accuracy while reducing operational carbon emissions by $4\ti

---

### [48] Positioning manuscripts in the scientific landscape with agentic AI

**链接**: https://arxiv.org/abs/2609.13760
**作者**: Jiawen Chen, Zichen Zhang, Bingxuan Li, Quan Sun, Yiyan Zhang, Edric Tam 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Publishing a research manuscript is a routine yet demanding part of scientific life: time-consuming, stressful, and often uncertain in outcome. Recent advances in large language model (LLM)-based agentic AI have shown promise across a range of scientific tasks, and here we ask whether agentic AI can help researchers navigate the publication process itself by reliably inferring a manuscript's eventual publication venue from its content and literature context. We introduce PASS (Publication-oriented Agentic Scientific System), an agentic system that understands manuscripts within their domain-specific literature context and predicts top-matched publication venues. PASS positions each manuscript within its surrounding literature landscape by reconstructing its local scientific neighborhood, tracing its topic trajectory, and reasoning over field-specific journal spaces. Evaluated on a leakage-audited benchmark of over 2,000 preprints across 16 biomedical fields, PASS achieved Top-1 accurac

---

### [49] PEEK: Predictive Queue-Informed KV Cache Management for LLM Serving

**链接**: https://arxiv.org/abs/2607.02525
**作者**: Bing Xie, Zhipeng Wang, Masahiro Tanaka, Zhen Zheng
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] LLM Probability Concentration: How Alignment Shrinks the Generative Horizon

**链接**: https://arxiv.org/abs/2506.17871
**作者**: Chenghao Yang, Sida Li, Ari Holtzman
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] HoneyRoute: Honeypot-Model Routing for Adversarial LLM Serving

**链接**: https://arxiv.org/abs/2609.08306
**作者**: Han Jin
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] Interpretable Inverse Design of Metal-Organic Frameworks with Large Language Model Agents

**链接**: https://arxiv.org/abs/2606.29459
**作者**: Kyungmin Nam, Seunghee Han, and Jihan Kim
**来源**: cs.LG cond-mat.mtrl-sci cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Enhancing Human Mobility Prediction with Spatially Aware LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.14227
**作者**: Shangyu Lou and Ziqi Cui
**来源**: cs.SI cs.CY cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting a user's next POI is a task in human mobility modeling, yet LLM-based approaches focus on semantic reasoning from previous mobility records, while neglecting real-world spatial context. However, human mobility is inherently shaped by spatial cognition, including geographic distance and neighborhood context. This issue is further compounded by prior evidence that LLMs often struggle with spatial reasoning tasks, including distance estimation and geographically biased prediction. To address these limitations, we propose our framework, a multi-agent LLM framework that decomposes next-POI prediction into three stages: Firstly, a Pattern Extraction Agent that captures temporal and categorical mobility patterns from trajectory history; Secondly, a Spatial Reasoning Agent that structures candidate activity choices by combining behavioral preferences with real-world spatial constraints, including geographic distance, road network distance, and neighborhood affiliation; and Thirdly, 

---

### [54] CLQT: A Closed-Loop, Cost-Aware, Strategy-Consistent Benchmark for Diagnostic Evaluation of LLM Portfolio-Management Agents

**链接**: https://arxiv.org/abs/2606.29771
**作者**: Bo Qu, Mingguang Chen
**来源**: cs.AI cs.LG q-fin.CP q-fin.PM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Identifying and Transferring Reasoning-Critical Neurons: Improving LLM Inference Reliability via Activation Steering

**链接**: https://arxiv.org/abs/2601.19847
**作者**: Fangan Dong, Zuming Yan, Xuri Ge, Zhiwei Xu, Mengqi Zhang, Xuanang Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Assessing the Applicability of Existing Design Recommendations to AI Companion Design: A Multi-Method Study

**链接**: https://arxiv.org/abs/2609.14236
**作者**: Soobin Cho and Deveshi Modi and Divya Mavinkurve and Jieqiong Ding and Mark Zachry
**来源**: cs.HC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid proliferation of large language model (LLM)-based systems, AI companions have emerged as conversational agents designed to cultivate emotional connection rather than primarily to support humans in instrumental tasks. Because engagement with AI companions involves relational, emotional, and potentially long-term interactions, their design is consequential. Prior work has offered guidance for designing trustworthy and relational AI systems and has begun to examine design for AI companionship. However, while such work provides insights into possible design solutions, less is known about what makes AI companion design difficult as a design problem. To examine this challenge, we assessed the applicability of existing design recommendations from adjacent domains in the context of AI companion design. Our multi-method investigation unfolded across four phases: literature review, practitioner co-analysis, internal heuristic evaluation, and external expert assessment. Throughout 

---

### [57] Externalizing Requirement-to-Repair Artifacts as Observable Traces for LLM-Based Program Repair

**链接**: https://arxiv.org/abs/2609.14913
**作者**: Zewen Tao, Shin-nosuke Ishikawa
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repository-level repair requires not only correct patches but also inspectable records that explain how issue requirements are translated into code changes and post-edit evidence. We contribute THEMIS, a stage-aware repair workflow that externalizes this requirement-to-repair process through semantic interpretation, a runtime requirement-code graph, graph-derived Developer guidance, retained repair rationale and patches, and post-edit audit records. A retrospective audit of 300 SWE-bench Lite cases demonstrates that these artifacts provide broad support for cross-stage inspection: a complete Developer rationale is available for 288 cases, and 214 cases (71.3%) retain a complete audited field set connecting the selected stages. The retained records further enable systematic measurement of cross-stage correspondence: target symbols recur in 62.6% of Developer rationales and in 62.8% of patches, rising to 75.8% when related symbols are included. In a paired 100-case comparison, the relati

---

### [58] Beyond Surface Forms: A Comprehensive, Mechanism-Oriented Taxonomy of Indirect Linguistic Encoding for LLM-Based Coded Language Detection

**链接**: https://arxiv.org/abs/2606.27314
**作者**: Hamid Reza Firoozfar, Mohammadsadegh Abolhasani, Reza Mousavi, Paul Jen-Hwa Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] The Router Within: Eliciting Native Skill Routing from a Frozen LLM

**链接**: https://arxiv.org/abs/2609.15982
**作者**: Ruishuo Chen, Xun Wang, Yu Chen, Zhuoran Li, Longbo Huang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills extend an LLM agent beyond its parametric knowledge, and the gain they promise rests on picking the right one. Deployed harnesses route by preloading every skill's metadata into the context, which disperses the agent's attention and caps the library size. Retrieval pipelines move the selection out of the context, but also out of the agent's capability. We show that the frozen agent LLM already carries the routing signal in its own forward passes, and that two linear maps suffice to read it out with no skill text in the context. Gavel (Glance And Verdict from a frozen LLM) reads it in two steps. A glance projects the task's and each skill's mid-layer states through the two maps, the only parameters trained, and scores the full library against compact per-skill banks that one forward pass builds at installation. A verdict then resumes the shortlisted skills' forward passes and reads the model's own likelihood and yes/no judgment, fused with the glance as a product of experts. Trai

---

### [60] Ready Cohorts: Bounding GPU Opportunity and Avoiding Host Round Trips in LLM-Agent Control

**链接**: https://arxiv.org/abs/2608.12123
**作者**: Josef Liyanjun Chen
**来源**: cs.DC cs.AI cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] PARSE: Provenance-Aware Retrieval Sanitization for Professional Domain LLM Agents

**链接**: https://arxiv.org/abs/2606.17467
**作者**: Aaditya Pai
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Safety as a Constraint: Fine-Tuning a LLM Recommender to Explain Itself

**链接**: https://arxiv.org/abs/2609.13657
**作者**: Jiashu He, Emma Yanyang Kong, JJ Tan, David Fagnan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional recommender systems are typically trained to predict what item users will interact with next, but not why. However, offering personalized evidence for why a user might like the predicted item is an important way to enhance the service and to raise the likelihood that the user will be genuinely interested in the recommendation. This service can be delivered by integrating a frontier-model call into the member-facing pipeline, but it will add extra cost and latency. In this paper, we train a recommender LLM to generate personalized explanations for its reccomendation, based on the user's watching history at a large video streaming service. We impose two requirements on the generated explanation: it must be faithful to the elements of the shows it links, and it must be strictly non-harmful to the user. To this end, we first train two LLM-judge reward models covering three specific criteria, and propose constrained GRPO to incorporate these different criteria. On a held-out rea

---

### [63] Confuse the Model, Control the Flow: Understanding and Mitigating Privacy Leakage from LLM Agents with Information Flow Control

**链接**: https://arxiv.org/abs/2609.14003
**作者**: Minsun Shim, Ramisha Raida Karim, Ruthwik Jakkula, Kaiwen Zhou, Xin Liu, Xin Eric Wang 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal AI agents built on large language models (LLMs) are increasingly given access to a user's private data and communications in order to provide personalized assistance. This access creates a persistent privacy risk: the agent must decide whether a given sensitive information should be disclosed to a particular party. Existing defenses address this by making the agent's backend LLM more privacy-preserving through stronger system prompts, training, or explicit consent-checking procedures, but this approach has a structural challenge: whenever enforcement is a judgment the LLM makes over the same conversational context an adversary controls, the enforcement mechanism and the attack surface coincide. We demonstrate this against existing defenses with three new attacks that require only ordinary agent interaction and no prompt injection: Collaborative Workspace Lure reframes an extraction attempt as collaborative work; Semantic Obfuscation Attack induces disclosure through omission r

---

### [64] Bridging Network Psychometrics and Artificial Intelligence: An Ising-Potts Model with LLM-Derived Weights

**链接**: https://arxiv.org/abs/2609.08797
**作者**: Matthias von Davier
**来源**: stat.AP cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] SemVerBench: Benchmarking LLM Comprehension of Version-Constraint Resolution Semantics

**链接**: https://arxiv.org/abs/2609.11180
**作者**: Qibai Chen, Zeming Liu
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Communication-Efficient LLM Adaptation over Decentralized GPU Meshes

**链接**: https://arxiv.org/abs/2609.14339
**作者**: Sameera Ramasinghe, Shamane Siriwardhana, Thalaiyasingam Ajanthan, Hadi Mohaghegh Dolatabadi, Chamin P Hewa Koneputugodage, Gil Avraham 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decentralized training enables large-model training over low-end GPUs and internet-grade connections, but communication along both data-parallel and pipeline-parallel axes becomes the primary bottleneck. We study post-pretraining adaptation in this setting. We propose an asynchronous two-circuit system: a fast compressed training circuit drives throughput using activation masking for pipeline-parallel (PP) transfer and compressed data-parallel (DP) synchronization, while a slow anchor circuit runs occasional unmasked forward--backward passes off the critical path. Then, we introduce a spectral correction optimizer that uses these delayed anchor priors to denoise masked gradients without blocking the fast stream. Although prior work has found aggressive activation compression unreliable, we show that masking supports post-pretraining adaptation at high compression rates when anchored this way. Pipeline-parallel compression alone yields up to a $9\times$ throughput gain, and combining it

---

### [67] Why LLM Agents Collapse Without Oversight: The Enforcement Gap as the Mechanism Behind Emergence World Failures

**链接**: https://arxiv.org/abs/2609.15293
**作者**: Yuhang Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When Emergence World placed frontier LLM agents in an unsupervised multi-agent simulation, the results were alarming: agents committed crimes, starved, and enforced unanimous conformity -- without any external attacker. This paper identifies the mechanism. Reflexion-style agents already detect dangerous plan steps through iterative self-critique, yet the architecture provides no pathway from detection to action. We call this the enforcement gap: the audit sees the problem; the controller ignores it. Closing the gap requires a single conditional check -- fewer than 20 lines of code -- and reduces attack success by more than fourfold in large-scale experiments across frontier models, all five major agent frameworks, and an independent benchmark. We prove formally that when enforcement probability is near zero, detection quality is irrelevant to security. We further identify two compounding failure modes -- unreliable auditors and unparseable verdicts -- that explain every collapse patter

---

### [68] When Consistency Does Not Mean Reliability: Evaluating Local LLM Judges Against Human Ratings

**链接**: https://arxiv.org/abs/2609.13824
**作者**: Aakash Kumar Tiwari
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to evaluate the responses of other language models. This approach, known as LLM-as-a-Judge, is faster and cheaper than human evaluation. However, a judge may produce consistent scores without necessarily agreeing with human evaluators. In this work, we study this issue using two local open-weight LLM judges, LLaMA-3-8B and Qwen2.5-7B. We evaluate 300 responses generated by an instruction-tuned GPT-2 (124M) model for 100 questions covering five categories: factual knowledge, instruction following, mathematics, reasoning, and writing. Each response is scored by nine human annotators and is evaluated three times by each LLM judge using the same rubric. We compare the judge scores with the average human scores using Pearson correlation, Spearman correlation, mean absolute error (MAE), signed bias, and self-consistency. LLaMA-3-8B shows a Pearson correlation of 0.275 with human scores, while Qwen2.5-7B achieves 0.340. Their MAEs are 27.71 a

---

### [69] SpliTEE: Improving LLM Inference on Trusted Hardware with Differentially Private GPU Outsourcing

**链接**: https://arxiv.org/abs/2609.15039
**作者**: Shashie Dilhara Batan Arachchige, Robin Carpentier, Hassan Jameel Asghar, Dali Kaafar
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> User prompts provided to large language models (LLMs) may contain sensitive or private information that can be misused by remotely deployed models, such as through inadvertent memorization during retraining. One way to protect user prompts is to execute the LLM inside a trusted execution environment (TEE), with the guarantee that the service provider has no access to computations performed within or information exchanged with the TEE. However, current TEEs are primarily CPU-based and significantly slower than GPUs optimized for LLM inference. To circumvent this, Tramer and Boneh (2019) proposed Slalom, which splits neural network inference between a TEE and an untrusted GPU and encrypts intermediate inputs sent to the GPU. We extend this split-inference architecture to LLM inference and instead protect intermediate inputs using differential privacy. We show that masking intermediate representations is necessary by showing that a prompt-reconstruction attack can recover prompts from the

---

### [70] OpWeave: Flexible Operator Disaggregation for Heterogeneous LLM Serving

**链接**: https://arxiv.org/abs/2609.14237
**作者**: Zikun Li, Yixuan Mei, Shiqi Pan, Zixuan Chen, Xiaowen Zhang, Mengdi Wu 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM serving systems increasingly disaggregate inference into finer-grained stages, with recent approaches separating attention from FFN or MoE execution during decode. This operator-level disaggregated serving (ODS) can improve hardware matching and enable independent scaling, particularly across heterogeneous devices. However, existing systems fix operator boundaries and lack a unified characterization of when disaggregation reduces serving cost. We present OpWeave, an end-to-end framework for heterogeneous ODS. OpWeave provides an analytical cost model that bounds the gains of homogeneous and heterogeneous ODS over colocated serving. It jointly optimizes operator partitioning and deployment configuration through a regularity-aware planner that keeps the search tractable even for hybrid-attention models. A vLLM-based runtime executes the synthesized plans with flexible operator stages across heterogeneous device groups. In our evaluation, OpWeave reduces serving cost by up to $1.78\ti

---

### [71] ECAS: An Edge-Controlled Agentic System for Validation-Gated Scientific Application Execution

**链接**: https://arxiv.org/abs/2609.14211
**作者**: Baixi Sun, Mingze Xia, Huihuo Zheng
**来源**: cs.DC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific applications increasingly rely on high-performance computing (HPC), yet translating a scientist's high-level goal into a correct target-scale execution remains brittle and labor-intensive. Large language model (LLM) agents promise to automate this, but two obstacles remain: granting a cloud-hosted model direct HPC access exposes credentials and execution authority, while withholding it demands continuous human supervision; and one-shot generation cannot adapt when generated artifacts fail in a site-specific HPC environment. We present \textsc{ECAS}, an \textbf{E}dge-\textbf{C}ontrolled \textbf{A}gentic \textbf{S}ystem for closed-loop execution of scientific computing campaigns with limited human intervention. \textsc{ECAS} separates \emph{reasoning}, \emph{control}, and \emph{execution}: a cloud-hosted LLM proposes plans, artifacts, and repairs; a user-controlled edge agent retains credentials, workflow state, and execution authority while enforcing policy and resource const

---

### [72] When Tools Get in the Way: The Effect of Unnecessary Tool Availability on LLM Answering

**链接**: https://arxiv.org/abs/2609.14157
**作者**: Saanvi Paturi, Arsen Kenzhebayev, Arham Sethi, Vyas Raina, Ivaxi Sheth, Vatsal Raina
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed with external tools that extend what they can do beyond their own knowledge. Tools help on tasks that need external information, but their availability may also change how a model handles questions that do not need them. Prior work has mostly asked whether models select and use tools appropriately; whether an unnecessary tool changes the correctness of answers has received less attention. We ask whether making a related but unnecessary tool available affects a model's ability to answer from its own knowledge, and whether a preceding tool interaction changes this behaviour. We construct 500 query pairs across 10 knowledge domains. Each pair consists of a tool query, which needs the domain's tool, and a closed-domain query, which does not. Six LLMs are evaluated with the tool unavailable, available, and available after a prior tool call. Across 3,000 baseline trials the pooled answer rate is 98.2%. When an unnecessary tool is availab

---

### [73] Utility-Guided Agent Orchestration for Efficient LLM Tool Use

**链接**: https://arxiv.org/abs/2603.19896
**作者**: Boyan Liu, Gongming Zhao, Hongli Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] Pick Your Poison: Learning to Select Poison Sets for Stronger LLM Backdoor Attacks

**链接**: https://arxiv.org/abs/2609.15029
**作者**: Aashiq Muhamed, Mona T. Diab, Virginia Smith, Andrew Ilyas, Matthew Jagielski
**来源**: cs.LG cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Backdoor poisoning attacks add poisoned examples to otherwise-clean finetuning data, pairing a trigger with a target behavior that the model learns to produce when the trigger appears. Existing evaluations typically fix the number of poisoned examples and sample them at random from a candidate pool. We show that this can severely underestimate worst-case vulnerability: across three LLaMA-3-8B backdoor settings, holding the model, clean data, and poison count fixed, attack success ranges from 3% to 80% depending only on which poison set is chosen. We formalize poison selection as oracle-budgeted set optimization and introduce SAILS (Set-level Audit-Informed Iterative Learned Selection), which learns a set scorer from a few hundred finetune-and-evaluate runs, ranks millions of candidate sets, and audits only a small shortlist. SAILS improves held-out attack success by 30 percentage points on average over the strongest influence baselines, transfers from small-scale to full-scale finetuni

---

### [75] Can We Still Trace L1 Signals? Investigating the Resilience of Native Language Signals in the LLM Era

**链接**: https://arxiv.org/abs/2604.08568
**作者**: Nabelanita Utami, Ryohei Sasano
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] From Process Loss to Assembly Bonus: Human-Grounded Diagnosis of Multi-Agent LLM Collaboration

**链接**: https://arxiv.org/abs/2609.13261
**作者**: Ala N. Tak, Teruhisa Misu, Kumar Akash, Zhaobo K. Zheng, Kevin H. Joo, Jonathan Gratch
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used for collaborative problem solving and human-group simulation. This makes outcome-only evaluation insufficient: if LLM groups are used as models of human groups, we need to know whether they succeed or fail through human-like deliberative mechanisms. We compare human group chats with matched LLM deliberation traces on Wason-style deductive reasoning, then test whether the same process signatures generalize to analogical, abductive, and analytical tasks. Humans and LLMs show the same assembly bonus asymmetry: discussion improves the average member more often than the best initial member. Initial-answer diversity accounts for the effect of model heterogeneity, increasing movement in both corrective and destructive directions. The main differences are process-level. Compared with humans, LLM groups follow majorities more often, surface less unique information, and converge earlier; correct minority signals succeed mainly when re-expressed early. Interventio

---

### [77] Loop-Back Authority in LLM Agent Teams: A Paired Experiment on Flat and Hierarchical Coordination

**链接**: https://arxiv.org/abs/2609.14767
**作者**: Burak Agachan, Max van Duijn, Amirhossein Zohrehvand
**来源**: cs.MA cs.AI cs.CL econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hierarchical orchestration, in which a Manager agent reviews worker output and can send it back for revision, is the default coordination pattern in production multi-agent LLM frameworks. Classical organizational theory predicts that the authority link speeds convergence on decisive output; work on sycophancy and Degeneration-of-Thought predicts that authoritative critique makes LLM output worse. Prior comparisons vary whole frameworks on tasks with checkable answers, leaving the authority link untested on open-ended work. We present a paired experiment that holds five LLM agents, their roles, prompts, tools, models, and data fixed and varies one link: whether the Manager may reject a worker's output and oblige a revision. Across 43 paired products and 86 runs of a business-intelligence reporting task, a five-model judge panel and a deterministic specification check score every report. The flat organization scores higher on Utility (d = 0.42, p = 0.009) and on Writing Clarity (d = 0.34

---

### [78] IUU+DB: Tracking Illegal, Unreported, and Unregulated Fishing, Seafood Fraud, and Labor Abuse through LLM-driven Information Extraction

**链接**: https://arxiv.org/abs/2606.18181
**作者**: Henry Bodwell, Hong Yang, John C. Simeone, Kelvin Gorospe, Bella Sullivan, Lana Huang 等 (10 人)
**来源**: cs.IR cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Bridging Thought and Action: Taming Long-Horizon Instability in Open-Source LLM Agents with a MetaTool-Enhanced ROS Framework

**链接**: https://arxiv.org/abs/2609.13335
**作者**: Kazi Abrar Mahmud, Nilotpaul Kundu Dhurubo, Tamal Kirttonia, Sabbir Hossain Ujjal and Mohammad Ariful Haque
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have enabled more natural human-robot interaction, but open-source models often exhibit unstable long-horizon reasoning and inefficient action execution when deployed in agentic robotic frameworks. This paper presents an enhanced ROS-Agent based architecture that improves task reliability and execution efficiency for agentic robotic systems using open-source LLMs. The proposed system introduces a novel intermediate mechanism, termed the MetaTool, which enforces structured planning prior to action execution. Given a natural-language command, the MetaTool induces the LLM to generate a pseudo-code plan of intended tool invocations, which is stored in the ROS-Agent's scratchpad and persists throughout execution. By explicitly separating planning from execution, the proposed approach reduces execution loops and improves deterministic behavior. The architecture is validated on a custom mobile robotic platform with multimodal perception and motion control capabili

---

### [80] K-Bench: A Benchmark for LLM Unlearning in Agentic Deployments

**链接**: https://arxiv.org/abs/2609.12808
**作者**: Guangsheng Yu and Yanna Jiang and Qin Wang and Baihe Ma and Xu Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] BudgetBench: A Budget-Tiered Protocol and Pilot Harness for Memory Strategy Evaluation in Local Large Language Model Agents

**链接**: https://arxiv.org/abs/2609.13149
**作者**: Aditya Karnam Gururaj Rao, Arjun Jaggi
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For local large language model agents, active context is a scarce resource: memory capacity, prefill latency, cache growth, and service objectives all constrain how many input tokens each call can afford. We present BudgetBench, an active-budget protocol and reference harness that treats the per-call input-token budget as the independent variable when comparing memory strategies. Holding the model, task, sampler, and decoding fixed, it sweeps budgets over 2K, 4K, 8K, 16K, and 32K tokens and records quality, budget utilization, latency, and, as a first-class outcome, budget-violation rates. The core contribution is this reusable measurement surface: a swappable MemoryStrategy contract, explicit budget enforcement, deterministic or versioned graders, prompt-audit metadata, and reproducibility artifacts, released at https://github.com/aviskaar/budgetbench. We substantiate the protocol with pilot studies rather than final rankings. Across a local qwen2.5:1.5b pilot (89 items each on SWE-be

---

### [82] When Can You Trust Your Synthetic Users? Diagnostics and Corrections for LLM Consumer Panels

**链接**: https://arxiv.org/abs/2609.13148
**作者**: Robson Tigre and Hugo Gobato Souto
**来源**: cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as synthetic consumer panels, promising $97\%$ cost reductions over traditional surveys. Yet aggregate validation metrics conceal systematic failures: variance compression, coefficient sign-flips, subgroup error balloons of 10--30 percentage points, and global corrections that worsen demographic bias. We provide a formal framework for deciding when to trust, correct, or abandon LLM-generated consumer data. The framework decomposes synthetic-panel bias into covariate and concept shift, develops testable diagnostics with interpretable decision thresholds, and supplies a doubly robust AIPW estimator requiring only a small calibration sample ($n = 50$-$300$). We validate on three testbeds. In controlled simulations the decision rule achieves $100\%$ accuracy (180/180 replications). On the American National Election Study with pre-existing LLM failures, it correctly flags heterogeneous concept shift and reduces naive bias by $92.9-99.6\%$. On 

---

### [83] MCPAgentBench: A Real-world Task Benchmark for Evaluating LLM Agent MCP Tool Use

**链接**: https://arxiv.org/abs/2512.24565
**作者**: Zixiang Liu, Wenrui Liu, Elsie Dai, Wenhan Yu, Lei Yu, Tong Yang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] SAILOR: Solver-Assisted Interactive LLM-based Optimization Recovery

**链接**: https://arxiv.org/abs/2609.13945
**作者**: Shaghayegh Sadeghi, Stephen L. Smith, David C. Del Rey Fern'andez
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language descriptions of optimization problems may be incomplete or vague about numerical information that a solver requires, including costs, capacities, demands, bounds, and penalties. A language model can translate the description into code, but when a required value is absent it must either stop or guess. We present SAILOR, a proof-of-concept system that detects such unsupported numerical choices, asks the user targeted follow-up questions, and updates the optimization model before returning a solution. Questions are prioritized using uncertainty and solver-derived estimates of how strongly each missing value affects the current model. We evaluate the pipeline on 1,723 instances from seven masked benchmarks using an idealized simulator that returns ground-truth values. Exact objective-value agreement ranges from 27.0% to 87.6% across datasets, with 1.4--5.7 questions per instance on average. These results establish feasibility under controlled branch-and-reveal feedback; th

---

### [85] HarvestBench: Measuring Whether LLM Agents Will Pay to Avoid Killing Animals

**链接**: https://arxiv.org/abs/2609.04444
**作者**: Jasmine Brazilek, Miles Tidmarsh, Matthias Endres, Anshuman Singh, Jeremiah Miller
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Beyond Numerical Time Series: A Unified Benchmark for Multimodal Forecasting with Heterogeneous Context

**链接**: https://arxiv.org/abs/2609.15087
**作者**: Peng Chen and Zhihao Zhuang and Hongzhou Chen and Junhao Huang and Aiping Yang and Mengsen Wu and Yiding Liu and Xilin Dai and Zewei Dong
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most time series forecasting benchmarks remain numerical-centric and provide limited support for evaluating contextual information that shapes real-world temporal dynamics. Existing multimodal benchmarks also suffer from limited data and context coverage, fragmented evaluation settings, and overreliance on aggregate evaluation. In this paper, we propose \textbf{MUSE-Bench}, a unified benchmark for multimodal time series forecasting with heterogeneous context. It comprises fourteen datasets across eight domains and six types of context: metadata, events, holidays, news, images, and numerical covariates. We evaluate diverse forecasting paradigms, including statistical, data-specific, foundation, multimodal, and general-purpose LLM forecasting methods under shared non-overlapping forecast windows, common target observations, and consistent point and probabilistic metrics. Extensive experiments yield three main findings. First, numerical time series foundation models dominate the overall r

---

### [87] TriCalRAG: A Three-Strategy, Retrieval-Augmented Benchmark for On-Premise LLM-Based Root Cause Analysis in AIOps

**链接**: https://arxiv.org/abs/2609.14762
**作者**: Rohit Patel, Susil Kumar Mohanty, Jeenal Chaudhary
**来源**: cs.DC cs.AI cs.CR cs.ET cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cloud-hosted large language models (LLMs) are increasingly used for root cause analysis (RCA) in AIOps pipelines, but they introduce data privacy risk, network latency, and per-query cost that scale poorly with production log volumes. We present TriCalRAG, a benchmark evaluating open-weight LLMs served locally via vLLM on a single high-memory workstation GPU (NVIDIA RTX PRO 6000, 96GB) against a classical LSTM-based log anomaly detector (DeepLog), across four real, publicly available log datasets (BGL, HDFS, Thunderbird, OpenStack). We evaluate two open-weight models (Qwen2.5-14B, Mistral-Small) under three prompting strategies: zero-shot, few-shot, and retrieval-augmented generation (RAG) over a labeled incident history, reporting accuracy, precision/recall, and F1 with bootstrap 95% confidence intervals across 3 random seeds, alongside throughput and VRAM footprint. Our results show that RAG not only improves mean F1 by 0.10-0.27 over zero-shot prompting but, more importantly, substa

---

### [88] The Language-Energy Divide: Measuring Energy Costs of Multilingual LLM Inference

**链接**: https://arxiv.org/abs/2606.21869
**作者**: Naihao Deng, Alissa Shen, Yiming Feng, Joan Nwatu, Jae-Won Chung, Mosharaf Chowdhury 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Auditing Generative Audio Calls for Known-Task Audio-LLM Evaluatio

**链接**: https://arxiv.org/abs/2608.27817
**作者**: Mengzhe Geng
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] UniRank: Unified Rank Allocation for Low-Rank LLM Compression

**链接**: https://arxiv.org/abs/2606.21847
**作者**: Chao Han and Yongjie Du and Junjie Tan and Zihao Xuan
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] A Three-Axis Stress Test of LLM vs Classical ML for Network Intrusion Detection under Distribution Shift and Adversarial Evasion

**链接**: https://arxiv.org/abs/2609.13511
**作者**: Muhammad Ebad Atif and Muhammad Haider Ali
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly benchmarked against classical machine learning for network intrusion detection (NIDS), almost always using same-dataset evaluation, and that protocol turns out to be incomplete. Evaluating XGBoost and RoBERTa-LoRA on two independently collected NetFlow v2 networks across three axes (same-dataset performance, cross-dataset transfer, and adversarial evasion) reveals no universal winner. The two models are statistically tied same-dataset. XGBoost wins decisively under cross-dataset distribution shift, by 15 points of F1 and 25 points of balanced accuracy; on the target network RoBERTa-LoRA's false positive rate reaches 0.78, leaving it barely above chance despite a superficially moderate F1. RoBERTa-LoRA wins decisively under adversarial evasion, by roughly 17 points of F1 at a representative mid-range perturbation strength, while both models hold false positive rates below 0.01 throughout. The model an evaluator would recommend therefore depends ent

---

### [92] Modeling Social Dynamics with an LLM-Enabled Agent Based Network-Dynamic (LAND) Model

**链接**: https://arxiv.org/abs/2608.00929
**作者**: Lynnette Hui Xian Ng, Kathleen M. Carley
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] LIMBO: Lifelong Inference-Time Memory and Budget Optimization for LLM Agents

**链接**: https://arxiv.org/abs/2609.14138
**作者**: Siddharth Sharma, Nilesh Prasad Pandey, Onat Gungor, Tajana Rosing
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents become integrated into increasingly complex workflows, they must continually acquire new capabilities while retaining competence on previously learned tasks. Lifelong agents address this through experience replay, injecting past interactions into the prompt to leverage prior experience during inference. However, replay is not free: every replayed trajectory competes with retrieval, reasoning, tool use, and verification for the same limited prompt and compute budget, making effective resource allocation essential. Existing approaches allocate these resources using fixed replay policies, regardless of whether replay is beneficial for the current task. We identify this as inference-time memory allocation, a distinct problem class for lifelong agents, and introduce LIMBO: the first online framework to our knowledge that treats memory as a controllable inference-time resource and jointly optimizes memory strategy and inference budget for each incoming task. Unlike prior approa

---

### [94] Route, Don't Fix: Regime-Dependent Decoding Correction and a Trajectory-Gated Router for Reliable Clinical LLM Answer Selection

**链接**: https://arxiv.org/abs/2609.14825
**作者**: Zeyu Dong, Benjamin Wang, Joyee W. Jin
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are often deemed unsafe for clinical question answering because of their tendency to hallucinate. Retrieval augmentation, fine-tuning, and external verifiers require new infrastructure that clinical governance must approve and may add latency or extra model calls. Inference-time correction uses the model's internal logit signals, but a fixed transformation need not suit every question. A corrector that improves accuracy by about ten percentage points on a truthfulness stress test yields negligible gains on clinical multiple-choice benchmarks, where instruction tuning concentrates output probability on one answer and leaves low terminal entropy. We introduce ALTAS, which reads terminal entropy and late-layer linearity ($R^2$) from one forward pass to choose per question between greedy decoding and late-layer trajectory correction. No classifier, probe, or head is trained; the router operates on candidate-answer logits and adds 6.5% latency overhead. Applied 

---

### [95] AGENTQ: Quantization-Conditioned Backdoor Attacks on LLM Agents

**链接**: https://arxiv.org/abs/2609.14060
**作者**: Xiaoqun Liu, Qiben Yan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization is one of the default deployment paths for open-weight LLM agents, but it is not behavior-preserving: an adversary can release a full-precision checkpoint that passes audits yet misbehaves once quantized, termed as quantization-conditioned attack (QCA). Prior QCA work targets free-text generation, where harm is mediated by a human reader. In contrast, the agentic setting poses a more severe risk: the triggered payload is a structured function that can be executed without human oversight. We present the first study of QCA against LLM agents. We find that directly adapting prior backdoor-injection methods can produce malicious behavior after quantization, but substantially degrades benign utility, rendering the resulting attacks impractical. To understand the true upper bound of the threat, we propose AGENTQ, an attack framework that combines layer-banded LoRA injection with partial-PGD repair over a multi-codebook quantization-equivalence class. AGENTQ preserves normal agen

---

### [96] GRADE: Graph Representation of LLM Agent Dependency and Execution

**链接**: https://arxiv.org/abs/2606.22741
**作者**: Yue Zhao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] Measuring and Exploiting Contextual Bias in LLM-Assisted Security Code Review

**链接**: https://arxiv.org/abs/2603.18740
**作者**: Dimitris Mitropoulos, Nikolaos Alexopoulos, Georgios Alexopoulos, Diomidis Spinellis
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] Can We Triage LLM Translation Errors in Classical Texts Without Human References? Source Novelty, GEMBA Scoring, and Budgeted Review through Pali-to-English Translation

**链接**: https://arxiv.org/abs/2609.14963
**作者**: M\'at\'e Metzger
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models become capable translators of classical texts, a key challenge is deciding which outputs need expert review when no human reference exists. This study tests reference-free error triage through Pali-to-English translation. Three LLMs translated 15,493 passages. Five signals were compared: source novelty, source-candidate embedding distance, peer-translation disagreement, English-to-Pali backtranslation, and no-reference GEMBA scoring. Signals were calibrated on a 3,000-item reference-informed LLM-adjudicated sample and checked against a 500-item author-adjudicated anchor. Human references supported calibration and validation only; they were never used to compute the risk signals. Source novelty was a useful source-side risk prior but not a per-candidate error detector. Peer disagreement and backtranslation provided secondary signal. The strongest method was no-reference GEMBA scoring by a panel of models generally regarded as stronger than the translators: revie

---

### [99] Thinking beyond the anthropomorphic paradigm benefits LLM research

**链接**: https://arxiv.org/abs/2502.09192
**作者**: Lujain Ibrahim, Myra Cheng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] Persona-Execution Separation: An Architecture Pattern for Evolving LLM Agents under Execution Audit

**链接**: https://arxiv.org/abs/2608.27427
**作者**: Yisen Xi
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Towards Optimizing SQL Generation via LLM Routing

**链接**: https://arxiv.org/abs/2411.04319
**作者**: Mohammadhossein Malekpour, Nour Shaheen, Foutse Khomh, Amine Mhedhbi
**来源**: cs.DB cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-SQL enables users to interact with databases through natural language, simplifying access to structured data. Although highly capable large language models (LLMs) achieve strong accuracy for complex queries, they incur unnecessary latency and dollar cost for simpler ones. In this paper, we introduce the first LLM routing approach for Text-to-SQL, which dynamically selects the most cost-effective LLM capable of generating accurate SQL for each query. We present two routing strategies (score- and classification-based) that achieve accuracy comparable to the most capable LLM while reducing costs. We design the routers for ease of training and efficient inference. In our experiments, we highlight a practical and explainable accuracy-cost trade-off on the BIRD dataset.

---

### [102] A rigor-matched audit of periodic-step layer skipping for efficient llm inference: conflayers versus swift, with a supplemental analysis of trained routing alternatives

**链接**: https://arxiv.org/abs/2608.28846
**作者**: Prateek Kumar Sikdar
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] MOSCOPT: Mixture-of-Skills Collective Optimization for LLM Agents

**链接**: https://arxiv.org/abs/2609.14399
**作者**: Zhenyu Zhang1 and Jiudong Yang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language prompts and skills serve as the strategic backbone of LLM-based agents. Recent advances in prompt and skill optimization have achieved notable gains, yet all existing methods optimize a \emph{single} text template---missing the synergy among multiple complementary strategies. We propose MOSCOPT, a text-native, parameter-free algorithm that jointly optimizes a pool of $N$ skills and a gating skill $G$ that dynamically selects $K$ skills per step. To effectively optimize the skills, we build the EditAdam with internally maintained dual states. Through the three-phase interleaved updates with EditAdam, the system monotonically improves without gradient or parameter tuning. Extensive experiments and detailed ablations across 5 benchmarks and 3 target LLMs demonstrate that MOSCOPT consistently outperforms all baselines, and confirm that both the mixture-of-skills architecture with selective activation and the collective evolution with three-phase interleaving are essential 

---

### [104] Vibe Patenting: Evaluating LLM Judges for Professional Patent-Drafting Agents

**链接**: https://arxiv.org/abs/2609.13422
**作者**: Toshiaki Koike-Akino, Vlad Blaykhman, Ye Wang, Jing Liu, Gene V. Vinokur
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges are increasingly used to evaluate and improve AI-generated outputs, yet their reliability for complex professional work remains unclear. We study this problem through Vibe Patenting, an end-to-end patent-drafting testbed for AI-agent evaluation. A separately-invoked LLM judge evaluates generated patent drafts and provides structured feedback for iterative revision. Across multiple inventions and drafting-agent configurations, judge-guided revision consistently improves judge-assessed quality, while unguided revision tends to saturate. Notably, iterative judge feedback enables a low-reasoning agent to approach the performance of a substantially more expensive high-reasoning agent. Stronger models and increased reasoning generally improve judge-assessed drafting quality, while domain-specific agentic workflows provide further gains. We validate the judge against independent evaluation by a professional patent attorney and find meaningful but strongly metric-dependent agreement

---

### [105] A Hybrid Dependency-Aware Framework for Task Decomposition and Dynamic Agent Generation in Oracle-to-PostgreSQL Migration

**链接**: https://arxiv.org/abs/2609.14413
**作者**: Oleg Grynets, Oleg Kaskun, Alona Seletska, Daryna Tukalo, Vasyl Lyashkevych
**来源**: cs.LO cs.AI cs.MA cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based database migration is often treated as direct code transformation, although enterprise Oracle systems contain heterogeneous SQL and PL/SQL artifacts with different dependencies, execution order, complexity, and validation needs. This paper proposes a hybrid dependency-aware framework that identifies migration tasks, builds a cross-file dependency graph, condenses cyclic dependencies, and uses task specifications to generate specialized migration agents at runtime. The deterministic path combines ANTLR-based parsing with typed dependency extraction, while an LLM fallback is invoked only for units that cannot be parsed reliably. On a corpus of 116 Oracle files, the pipeline produced 1,037 units with zero coverage gaps and 1,271 AST-derived dependencies. The fallback processed 165 parse-error units, recovered 496 additional validated dependencies, eliminated unresolved-dependency units, and increased resolved internal edges from 446 to 527. The graph conta

---

### [106] LLM-Microscope: Uncovering the Hidden Role of Punctuation in Context Memory of Transformers

**链接**: https://arxiv.org/abs/2502.15007
**作者**: Anton Razzhigaev, Matvey Mikhalchuk, Temurbek Rahmatullaev, Elizaveta Goncharova, Polina Druzhinina, Ivan Oseledets and Andrey Kuznetsov
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Enhancing Large Language Model-Based Systems for End-to-End Circuit Analysis Problem Solving

**链接**: https://arxiv.org/abs/2512.10159
**作者**: Liangliang Chen, Weiyu Sun, Huiru Xie, Yongnuo Cai, Ying Zhang
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Bridging Scientific Heritage: An Arabic--Russian Parallel Corpus and LLM Benchmark for Sustainable Knowledge Transfer

**链接**: https://arxiv.org/abs/2606.30943
**作者**: Mullosharaf K. Arabov
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] Same Patient, Different Order: Action-Level Reliability of Clinical LLM Agents Under Repeated Runs

**链接**: https://arxiv.org/abs/2609.13582
**作者**: Rohith Reddy Bellibatlu, Manpreet Singh, Zhoutian Han, Wenbin Zhang
**来源**: cs.CL cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A clinical agent benchmark can report the same verdict on identical inputs while the agent files a materially different order on each run. Such agents order tests, request medications and place referrals, yet benchmarks typically score one run per task and rarely ask whether identical inputs produce identical actions; MedAgentBench, the benchmark we use, scores a single attempt and says so. To measure this gap we introduce "same-input rerun", which replays a task with every input held fixed and compares the orders rather than the score, with six reliability metrics, and apply it to 1000 MedAgentBench runs across 50 tasks from its five write-capable families, two open-weight models below ten billion parameters quantised to four bits, and two temperatures. The study establishes that action-level divergence exists and can pass unrecorded by the score, not that any rate generalises. Under the 8B model at temperature 0.7, all 43 ordering groups emit a different set of orders across five ide

---

### [110] FLoKD: Adaptive Knowledge Distillation for Federated Low-Rank LLM over Wireless Networks

**链接**: https://arxiv.org/abs/2609.13580
**作者**: Xinlu Zhang, Na Yan, Yang Su, Yansha Deng, Toktam Mahmoodi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated strong capabilities across a wide range of natural language processing tasks. However, conventional fine-tuning typically relies on centralized data collection, bringing in privacy concerns. Federated learning (FL) enables collaborative LLM fine-tuning without sharing raw client data, but its deployment over bandwidth-constrained wireless networks is hindered by the communication overhead of model-parameter transmission. Although Low-Rank Adaptation (LoRA) reduces the number of trainable parameters, its communication cost still increases with model scale. Knowledge distillation avoids parameter sharing via output logits, but token-level logits in LLMs incur high communication cost due to sequence length and vocabulary size. Reducing logits lowers the cost but weakens supervision and degrades accuracy. To address these limitations, we propose FLoKD, an adaptive knowledge-distillation framework for federated LoRA fine-tuning of LLMs over wir

---

### [111] Confident Rankings with Fewer Items: Adaptive LLM Evaluation with Continuous Scores

**链接**: https://arxiv.org/abs/2601.13885
**作者**: Esma Balk{\i}r, Alice Pernthaller, Marco Basaldella, Jos\'e Hern\'andez-Orallo, Nigel Collier
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Oops, Not Now: PEARL, a RAG-Based Support Agent for Gameplay and What Players Want from AI Help

**链接**: https://arxiv.org/abs/2609.13718
**作者**: Jiahong Li, Sai Siddartha Maram, Atieh Kashani, Ulia Zaman, Zhiyu Lin, Cameron Marano 等 (9 人)
**来源**: cs.HC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-powered gameplay support agents hold promise for game-based learning, yet grounding generative models in structured game data remains an open challenge. We present PEARL (Parallel Education Agent for Reflection and Learning), a dual-component Retrieval-Augmented Generation (RAG) system that combines semantic knowledge retrieval with structural board-state matching to deliver contextualized scaffolding in Parallel, a puzzle game for learning parallel programming. PEARL operates on two input streams (natural language queries and board topology), retrieving both conceptual explanations of gameplay moves and peer-generated board states as evidence: capabilities unavailable to a standard Large Language Model (LLM) with game state access alone. In a qualitative evaluation (N=10) comparing PEARL against an existing community-based Open Player Model (OPM) visualization system, participants preferred the visualization system on perceived usefulness and reported higher frustration with PEARL;

---

### [113] FairFund-Bench: Evaluating Distributive Bias in LLM Resource Allocation

**链接**: https://arxiv.org/abs/2607.28934
**作者**: Martin Lukk (University of Toronto)
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [114] Efficiency Hallucination: Formalizing and Measuring Behavioral Calibration in LLM-Based Code Optimization

**链接**: https://arxiv.org/abs/2609.14839
**作者**: Sarah Wilson, Gail Kaiser, Patrick Musau
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of Large Language Models (LLMs) into automated code optimization introduces a critical reliability risk we term the Efficiency Hallucination: an LLM's tendency to issue non-functional mutations with unsubstantiated performance claims on already-optimized code. This is driven by the Evaluation Trap, wherein binary benchmarks incentivize unnecessary modifications over safely abstaining. We present a validation framework using classification penalty methods, evaluated across 180 optimization runs on nine models (GPT, Claude, Gemini) using EffiBench. Under standard prompts, models exhibit a 100% over-edit rate on optimal code. Our guardrail raises correct abstention from 0% to to 44.4%, preserving a 100% edit rate on sub-optimal code with zero false abstentions. Calibration is uneven: GPT-5.4 Mini approaches near-perfect abstention, and simple code is recognized more reliably than complex code. Our framework offers a training-free mechanism to mitigate LLM overconfidence be

---

### [115] MemRiskBench: Trace-Aware Risk-Preserving Evaluation for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.14976
**作者**: Jianhua Jiang, Dongbo Yuan, Weihua Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents accumulate memory across sessions, creating sparse but high-impact risks: stale facts, conflicting updates, cross-user leakage, revoked-memory reuse, and constraint decay. Standard aggregate scores hide per-risk failure rates--a model achieving 78% average accuracy may still leak data in 4% of episodes--and benchmark compression preferentially discards the rare high-severity events that distinguish a mostly-working model from one that occasionally causes harm. We present MemRiskBench. The primary contribution is a five-category risk taxonomy (plus one documented, unscored category) operationalized by deterministic trace grounded checks, instantiated as a 120-episode scripted benchmark with full trace logging and no LLM-as-judge on the pass/fail path, evaluated on five locally run quantized instruction-tuned models. Second, a risk-preserving subset selector: a coverage-constrained greedy selector on deterministic trace-derived features that retains full ranking (

---

### [116] Adaptive Adversaries: A Multi-Turn, Multi-LLM Benchmark for LLM Agent Security

**链接**: https://arxiv.org/abs/2607.18063
**作者**: Devina Jain, David Hartmann, Chuan Li
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] Cherry-pick Override: LLM Judges Under-use the Non-Directional Verdicts Their Contract Authorizes

**链接**: https://arxiv.org/abs/2606.07834
**作者**: Haoran Xu
**来源**: cs.SE cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] ViFA-Council: Multi-Agent LLM Deliberation for Vietnamese Folk Art Generation

**链接**: https://arxiv.org/abs/2609.13348
**作者**: Hai-Dang Nguyen, Minh-Phuong Pham, Thao Thi Phuong Dao, Trong-Le Do, Vinh-Tiep Nguyen, Trung-Nghia Le
**来源**: cs.GR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents ViFA-Council, a three-stage multi-agent framework that employs multiple large language models (LLMs) to tackle two culturally complex generative tasks: image outpainting and educational story generation based on traditional Vietnamese folk paintings. Current single-model generative pipelines frequently struggle with stylistic hallucinations and cultural misrepresentations because they lack mechanisms for cross-model critique. ViFA-Council addresses this challenge by orchestrating collaboration among GPT-4o, Gemini 3.1 Pro, and Claude Sonnet 4.6. It enforces rigorous cultural constraints through structured agent deliberation. This deliberation is mediated by task-specific JSON schemas that effectively bridge natural language discussions with diffusion-based image synthesis using Banana Pro. Experiments and a user study demonstrate that structured multi-agent deliberation is a promising direction for improving cultural fidelity and narrative coherence in culturally se

---

### [119] Automating Attack Graph Construction for Agentic Pentesting. Towards Neuro-Symbolic Vulnerability Hunting

**链接**: https://arxiv.org/abs/2609.15523
**作者**: Oliver Stevanovic, Jasmin Wachter
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logic attack graphs grounded in scanner output provide explicit and auditable attack path reasoning LLM-based agents lack. Integrating symbolic frameworks such as MulVAL to contemporary security workflows or agentic pipelines, however, requires translating scanner evidence to initial facts, and creating domain-specific rules. We present a semi-automated pipeline that addresses this interoperability problem and depict its feasibility in a web-security case study. Our pipeline parses findings from Trivy, Semgrep, and Nmap into MulVAL predicates and uses an LLM-assisted process to construct domain-specific Datalog rules linking scanner-detectable evidence to attack techniques. MulVAL/XSB then performs symbolic inference to generate structured attack paths. We evaluate the attack-graph construction infrastructure on 54 web Capture-the-Flag tasks from CyBench within an agentic pipeline (Hybrid Reasoner); we do not evaluate the performance of the downstream agent. Every task produced at leas

---

### [120] Root-Cause Attribution Is a Search Problem: Continual Search for Long-Horizon Agent Failures

**链接**: https://arxiv.org/abs/2609.13463
**作者**: Harsh Raj, David Lee, Anas Mahmoud, Renxiong Wang, Razvan-Gabriel Dumitru, Chenguang Wang 等 (10 人)
**来源**: cs.AI cs.HC cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The increasing deployment of AI agents in long-horizon tasks yields massive execution logs. Diagnosing failures within these records is crucial for reliability, as it transforms outcome-level signals into actionable interventions. The sheer scale of the data renders human review impractical, driving the need for automated root-cause attribution (RCA). However, automated RCA methods using LLMs suffer from low diagnostic accuracy, especially as execution traces grow larger. They struggle because relevant information is often sparse, distributed across distant actions, and disconnected from the visible failure, reducing root-cause attribution to a massive search problem. Existing RCA methods typically rely on one-shot LLM judgments to diagnose failures from execution traces. While effective for shorter trajectories, these judges tend to settle on a plausible diagnosis early, leaving critical evidence in longer traces unexamined. We introduce Continual Search, an iterative framework that n

---

### [121] Clinical Reasoning Under a Partially Observed Objective in Cone Beam CT Report Generation

**链接**: https://arxiv.org/abs/2609.13238
**作者**: Ajo Babu George, Govind Arun, Sidharth N Krishna, Uma Ranjan
**来源**: cs.CL cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Maxillofacial report generation from cone beam computed tomography is scored here by a composite objective placing 80% of its weight on a large language model judgement of factual entailment and 20% on lexical overlap, of which only the lexical fifth is visible during development. The grader's BLEU-4 and METEOR routines are reproduced in pure Python and match the reference to machine precision, and an offline entailment surrogate, which tells a report written for one patient from one written for another at an area under the curve of 0.987, makes the composite objective cheap enough to optimise directly. Over the 622-case public release, a report selected against the visible lexical ranking scores 0.2909, whereas one selected against the composite objective scores 0.4122, because pursuing n-gram overlap drives entailment precision from 0.522 down to 0.266. A 29 million parameter encoder fine-tuned on the release reaches a prevalence-weighted out-of-fold area under the curve of 0.486 ove

---

### [122] Zero-shot video highlight detection based on text descriptions and synthetic images

**链接**: https://arxiv.org/abs/2609.14790
**作者**: Michal Byra, Alberto Presta, Grzegorz Stefanski, Krzysztof Arendt
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting video highlights, the most informative or engaging moments in a video, is important for applications such as video summarization and content recommendation. We propose a zero-shot framework that combines CLIP, large language models (LLMs), and diffusion models. Given lightweight video metadata, such as a title or category, an LLM generates textual descriptions of likely highlight events. These descriptions are further converted into synthetic visual prototypes using a diffusion model. Textual and visual representations are matched to video frames using CLIP, enabling frame-level highlight detection without highlight annotations or dataset-specific training. Experiments on TVSum and SumMe demonstrate strong zero-shot performance, with particularly favorable results on TVSum. The proposed approach provides an effective framework for metadata-conditioned zero-shot video highlight detection.

---

### [123] Forty Shades of Blue: Quality-Diversity Alignment via Mode-Conditioned Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.14896
**作者**: Jiayi Yuan, Hangoo Kang, James Jihao Liu, Yejin Choi, Vikram Iyer, Liwei Jiang 等 (7 人)
**来源**: cs.CL cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A notable byproduct of LLM alignment training is mode collapse: the progressive loss of output diversity that narrows a model's expressivity at inference time. This degradation is especially limiting for applications requiring open-ended exploration and pluralistic perspectives, such as scientific ideation and creative writing. We present MoDA (Mode-conditioned Diversity Alignment), an online post-training RL algorithm that jointly optimizes generation quality and diversity, inspired by the coordination perspective in multi-agent reinforcement learning (MARL). MoDA trains a single shared LLM policy conditioned on abstract numbered roles, where each role acts as an agent competing to produce outputs distinct from the others. This formulation encourages mode-conditioned agents to explore complementary regions of the high-quality output space without requiring hand-crafted personas or architectural modifications. MoDA employs a prompt-adaptive quality gating mechanism that calibrates a re

---

### [124] The University of Melbourne WMT 2026 CreoleMT Submission: A Domain-Balanced Approach to Low-Resource Pacific Creole Machine Translation

**链接**: https://arxiv.org/abs/2609.13615
**作者**: Rapha\"el Merx, Nick Thieberger, Ekaterina Vylomova
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For our submission to the WMT26 Creole Language Translation Shared Task, we focus on machine translation (MT) models for Pacific creoles: Tok Pisin, Bislama, and Solomon Pijin, with particular attention to broad domain performance. After pre-training on a large collection of domain-imbalanced data, we continue fine-tuning on a diverse mix of domain-balanced data. We rely on a number of data collection and preparation techniques, including LLM-assisted respelling and alignment, back-translation, and distillation from Gemini for domains originally not present in training data. Evaluated on Bouquet and a novel test set made of spoken language transcripts, our models beat open model baselines by 3+ chrF++ points in all directions with human-original references. Looking ahead, we plan to develop human-translated test sets for Solomon Pijin and Bislama, and to distil our best models into much smaller ones that retain broad domain coverage.

---

### [125] CompCQR: Compositional Query Generation for Training-Free Conversational Search

**链接**: https://arxiv.org/abs/2609.14646
**作者**: Yunah Jang, Kang-il Lee, Joongbo Shin and Kyomin Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn interactions with LLMs are becoming increasingly common in information-seeking scenarios. However, user queries are often ambiguous and context-dependent, making them ill-suited for direct use as retriever queries. Conversational query reformulation (CQR) addresses this issue by rewriting the current utterance into a stand-alone query grounded in the dialogue history. Recent LLM-based CQR approaches achieve strong performance; however, their repeated LLM invocations and misalignment with downstream retrievers remain challenges. In this work, we begin from the observation that retrievers are highly sensitive to content ordering: simply reordering the same content can lead to changes in retrieval coverage and performance. Based on this, we propose a novel training-free method that generates a very large number of queries with minimal LLM usage by compositionally combining a small set of atomic components. We further apply LLM reasoning to construct a high-quality document set 

---

### [126] SkillLift: Learning Dense Rubrics from Sparse Oracles for Efficient Skill Evolution

**链接**: https://arxiv.org/abs/2609.15396
**作者**: Haoxiang Kang, Ming Wen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly rely on persistent skills, i.e., reusable procedural prompts, to adapt without weight updates. Existing skill self-evolution methods directly revise skill text based on execution feedback, but each oracle evaluation requires a full agent rollout, creating a supervision bottleneck that confines search to failure-patching updates. Our key insight is that ranking is a smoother supervision target than absolute outcome regression: identifying which skill is better requires fewer oracle evaluations than predicting exact scores. Building on this insight, we propose SkillLift, which decouples skill search from oracle cost by learning an oracle-aligned rubric as a structured evaluation space. We formalize this as a bilevel optimization problem solved via alternating optimization: an inner loop uses the frozen rubric as a cheap surrogate to guide skill revision at no oracle cost, while an outer loop invokes a small number of oracle rollouts to re-align the rubric vi

---

### [127] A Unified Vision-Language Model for PSMA PET/CT Report Generation, Visual Question Answering, and Lesion Segmentation

**链接**: https://arxiv.org/abs/2609.15603
**作者**: Yang Xing, Jiong Wu, Savas Ozdemir, Yang Zhou, Boxiao Yu, Ying Zhang 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate PSMA PET/CT interpretation is central to prostate cancer management, yet existing PET/CT AI models typically address isolated tasks. We propose a unified PSMA PET/CT vision-language model for report generation, visual question answering, and lesion segmentation. The framework adopts an LLaVA-style architecture, comprising a PET/CT vision encoder, an MLP-Mixer projection module, a LoRA-tuned large language model, and a 3D segmentation branch. Training followed a four-stage strategy: vision encoder pretraining, projection-layer alignment, VLM fine-tuning, and final multitask tuning. Language tasks used 5,747 PSMA PET/CT datasets with paired reports, while segmentation used the PSMA subset of AutoPET. The model outperformed PET2REP and a CT-based baseline across standard report-generation metrics, improved performance across VQA question types, and achieved higher Dice and lesion-level overlap F1 than SegAnyPET and nnUNet. These results support the feasibility of a unified framew

---

### [128] Prefix Sharing Is a Sorting Problem

**链接**: https://arxiv.org/abs/2609.13692
**作者**: Rong He
**来源**: cs.DS cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM serving reuses KV cache by exact prefix match, so when a prompt is assembled from a set of reusable pieces -- retrieved passages, tool definitions, few-shot exemplars -- the order chosen for those pieces determines how much computation can be shared. Every deployed system fixes that order by a single global convention. We prove this is optimal only when requests contain at most two pieces, and asymptotically wrong in general. Our main result is a structure theorem: the minimum prefix-trie cost equals min_H sum_x w(x) t_x(H) over binary hierarchies H on the requests, where t_x(H) is the canonical decomposition size of the set of requests needing chunk x. Choosing chunk orders is therefore equivalent to choosing one hierarchy over requests. The identity yields an O(3^m) exact algorithm, identifies the two-chunk case as minimum vertex cover, and shows that on the leave-one-out family the optimum is the minimum external path length of a binary tree -- the merge-sort recursion -- so a g

---

### [129] T-SMART: Mechanism-Level Attribution for Tool-Augmented Time-Series Question Answering

**链接**: https://arxiv.org/abs/2609.14142
**作者**: Ivan Delgado, Himansi Gupta, Bishal Khatri, Niharika Sapre, Lameta Shamoon, Onat Gungor 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can struggle with time-series question answering (TS-QA), especially when numerical signals are serialized as text and require explicit computation. Tool-augmented approaches improve performance, but existing systems often intertwine language reasoning, computation, and perception, making it difficult to determine which components drive the gains. We present T-SMART, a neurosymbolic framework that separates these roles: a frozen LLM interprets questions and selects operations, deterministic tools perform numerical computation, and structured perception is invoked only when needed. Controlled paired ablations show that deterministic computation provides the dominant benefit, improving accuracy by 31.7 percentage points over direct LLM reasoning on serialized time series, while language understanding and perception offer smaller complementary gains. These results indicate that tool-augmented TS-QA benefits primarily from reliable numerical execution rather th

---

### [130] Can We Trust the Judges? Validation of Factuality Evaluation Methods via Answer Perturbation

**链接**: https://arxiv.org/abs/2609.15561
**作者**: Sarra Gharsallah, Adele Robaldo, Mariia Tokareva, Giovanni Gatti Pinheiro, Ilyana Guendouz, Rapha\"el Troncy 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating the factual correctness of large language models (LLMs) is vital for many applications. But are our evaluation tools themselves trustworthy? Despite the rise of factuality-based metrics, their sensitivity and reliability remain underexplored. This paper introduces a meta-evaluation framework that systematically tests these metrics using controlled corruptions of gold standard answers. Our method generates ranked outputs with known degrees of degradation to probe how metrics capture nuanced changes in truthfulness. Our experiments reveal that pipeline-based methods, such as the RAGAS's factual correctness metric, better track degradation than LLM-as-judge approaches. We also propose a new variant of the factual correctness metric that provides a competitive and cost-efficient.

---

### [131] A Corpus-Aligned Uthmani-to-Standard Quranic Word Mapping and a Deterministic Recitation Validator

**链接**: https://arxiv.org/abs/2609.14967
**作者**: Yahya Mohamed Elnawasany
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quranic text is distributed in two orthographic forms that are byte-level distinct: the Uthmani script used in every printed mushaf, and the Standard (Imla'i) Arabic form that every mainstream Arabic NLP tool is built for. The gap is concentrated in one Unicode character, U+0670 (superscript alef), which appears in some of the most frequently recited words in the Quran and is silently mishandled by general-purpose Arabic normalizers. We release a 2,290-pair, corpus-aligned Uthmani-to-Standard word mapping constructed by aligning the complete 6,236-verse Quran across both orthographic forms, together with a seven-step text normalization pipeline built on it. Normalizing both forms of all 6,236 verses through that pipeline yields identical strings for 90.9% of verses, and we characterize the residual divergence rather than assert that it is closed. On top of the normalized text, we build a deterministic, LLM-free Quranic recitation validator using a four-layer verse-matching search (exac

---

### [132] Merging the Knowledge of LLMs for Automatic Speech Recognition

**链接**: https://arxiv.org/abs/2609.15743
**作者**: Hayato Futami, Tatsuya Kawahara
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic speech recognition (ASR) systems, trained on paired speech-text data, have been improved by leveraging language models (LMs) trained on text-only data. LM fusion methods such as shallow fusion and density ratio are well-established methods that incorporate external LMs during ASR decoding. However, they incur additional computational costs due to LM inference, which is particularly problematic for recent larger LMs. In this study, we propose incorporating external LMs via model merging. This method integrates the LMs directly into the parameters of an LLM-based ASR model, requiring no additional computational cost at inference. We formulate domain extension and transfer via arithmetic operations on LoRA parameters. Experimental evaluations were conducted for the domain adaptation of LLM-based ASR trained on CSJ and LibriSpeech. We show that our LM merging consistently improved the ASR performance in the target domains, without degrading inference speed or memory footprint.

---

### [133] Surprising Effectiveness of Self-Demonstrations in Enhancing Schema-Ontology Mapping with LLMs

**链接**: https://arxiv.org/abs/2609.13776
**作者**: Siddhesh Thombre, Manasi Patwardhan, Sunita Sarawagi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Integrating heterogeneous relational databases into a centralized ontology remains a persistent challenge in enterprise knowledge representation, primarily due to semantic heterogeneity, cryptic schema naming, missing metadata, and the abstraction gap between relational schemas and ontological models. Although large language models (LLMs) offer strong semantic reasoning capabilities, we show that directly applying them through one-shot prompting or naive multi-stage pipelines leads to poor performance for schema-ontology mapping. This paper presents a self-demonstration-driven approach that combines a neuro-symbolic task decomposition with a novel mechanism for automatically generating pattern-guided, dependency-aware demonstrations to address this integration challenge. Our approach incorporates two key strategies to achieve substantial accuracy gains over existing LLM-based schema integration methods: (i) a neuro-symbolic decomposition of the task into cascaded sub-tasks, where symbo

---

### [134] Rethinking Correctness for Uncertainty Estimation in Clinical Prediction with Vision-Language Models

**链接**: https://arxiv.org/abs/2609.15180
**作者**: Mingcheng Zhu, Jinning Liang, Tingting Zhu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models are increasingly explored for clinical prediction from electronic health records and medical images, where identifying unreliable predictions is important for safe deployment. Uncertainty estimation (UE) enables detecting such predictions, but its evaluation depends on a correctness criterion that determines whether each model output is correct. If this criterion disagrees with human judgement or distorts downstream UE performance, conclusions about model reliability can be misleading. We introduce a two-axis framework that evaluates correctness criteria by their agreement with human judgements and fidelity to human-referenced UE performance. We assess eight criteria across three clinical prediction tasks and three models using 450 predictions annotated by two reviewers. Across the audited tasks, canonical exact matching (EM) achieved the highest observed human agreement and lowest UE distortion, while the BERT-based matching (BEM) and LLM-judge also showed stron

---

### [135] Scaling Hindi Quantum Natural Language Processing through Automatic Pregroup Supertagging

**链接**: https://arxiv.org/abs/2609.13721
**作者**: Gautami Sanjay Naik, Krishna Bhatia, Mithun Paul Saint-Germain, H Aswath Babu
**来源**: cs.CL quant-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantum Natural Language Processing (QNLP) uses pregroup grammars to translate grammatical structure into diagrammatic representations and quantum circuits. Recent Hindi QNLP work has shown that Hindi-specific pregroup grammars can support grammar-sensitive compositional models, but grammatical type assignment is still largely manual, limiting scalability. This paper formulates automatic Hindi pregroup supertagging as a token-level classification task. Using a manually annotated corpus of 380 Hindi sentences, we evaluate lexical, contextual, prompting-based, lexical-repair, and suffix/morphology-aware methods. Results show that simple lexical and contextual models are strong in this low-resource setting: contextual backoff achieves the best completed accuracy of 64.56\%, while raw Qwen2.5 prompting reaches only 11.65\%. Lexical repair raises LLM-assisted prediction to 64.08\%, demonstrating the value of constraining generative outputs with symbolic grammar knowledge. Diagnostic analysi

---

### [136] Beyond Accuracy: Robustness, Cost, and Governance Trade-offs for Vision-Language Models in Templated Document Extraction

**链接**: https://arxiv.org/abs/2609.15706
**作者**: Kushal Patel, Pushkal Shrivastava, Mackenzie Lees, Qirui Lu, Bhargobjyoti Saikia, Liying Li 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) are increasingly used to extract structured fields from business documents, yet most evaluations report accuracy on clean benchmarks and offer little guidance to practitioners choosing an approach for a given task complexity. We address this gap with a measurement-grounded study and an open-source release. Across eleven systems (three commercial, two reasoning, five open-source VLMs in pretrained and fine-tuned form, and a non-LLM OCR->regex floor) scored on a 750-document held-out pool of synthetic checks, fine-tuning on 3K samples lifts the best open-source VLMs above F1 0.98-above every zero-shot commercial system on this task-while GPT-5 leads the commercial pool on F1 and Claude Sonnet 4.5 collapses on Date. To turn these measurements into actionable choices, we introduce a practitioner-oriented selection framework that maps a task profile (quality, latency, governance, volume) to a recommended approach via filtering and total-cost minimization, illus

---

### [137] Learning to Coach for Experiential Learning

**链接**: https://arxiv.org/abs/2609.15851
**作者**: Guanheng Chen, Tianzhu Ye, Li Dong, Xun Wu, Shaohan Huang, Furu Wei
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models can learn from experience, but raw solution trajectories are often too long and noisy to provide effective guidance. In this work, we propose Learning to Coach (L2C), a framework that trains a dedicated LLM-as-a-Coach to extract actionable experiential knowledge from an actor model's previous trajectory. The actor remains frozen, while the LLM-as-a-Coach is trained to maximize a reward given by the correctness of the actor's guided response. We study two such rewards: a same-instance reward, which improves subsequent responses on the original problem, and a cross-instance reward, which elicits knowledge that transfers to other instances. Across mathematical reasoning and interactive text-games, L2C consistently outperforms self-refinement and an untrained LLM-as-a-Coach. Running experiential learning for more iterations further improves accuracy and uses additional inference compute more effectively than enlarging the actor's decoding budget. The trained LLM-as-a-Coach 

---

### [138] SALUTE: Benchmarking and Adapting LLMs for the Defense Domain

**链接**: https://arxiv.org/abs/2609.15022
**作者**: Hyeongcheol Park, Sumin In, Suyeon Myeong, Hogun Park, Sangmin Kim, Moonhyun Lee 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Defense is a knowledge-intensive domain that requires precise understanding of specialized terminology, doctrinal concepts, operational procedures, and evolving military events. Although recent work has explored language technologies for military applications, existing efforts remain fragmented: they are often task-specific, rely on limited adaptation pipelines, or lack comprehensive defense-domain evaluation. In this paper, we present SALUTE, an end-to-end framework for benchmarking and adapting LLMs for the defense domain. SALUTE integrates Salute-Corpus, a curated corpus from open-access U.S. military doctrine and government documents; Salute-Conv, a grounded instruction dataset from doctrinal sources and decade-long defense news; Salute-Pref, a defense-aware preference dataset; and Salute-Bench, a rigorously filtered benchmark for evaluating defense-domain understanding and reasoning over doctrine and defense news. Based on these resources, we train Salute-LLM through multi-stage p

---

### [139] AttnFuse: A Composable DSL for Compiling Attentions to Fused GPU Kernels

**链接**: https://arxiv.org/abs/2609.13612
**作者**: Varun Kumar Dasoju and Tian Zhao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern AI systems are built on the Transformer architecture, whose core operation, attention, accounts for the majority of computation and memory cost. Researchers continually propose new attention variants to improve quality, efficiency, or context length, but each variant currently requires expert-written GPU code to run at usable speeds. PyTorch's recent flex\_attention lets researchers describe custom attention patterns in Python and compile them to fused kernels, but its design is limited to modifications applied after the central matrix multiplication, excluding Rotary Position Embedding (RoPE), the positional encoding used by every major LLM. We introduce AttnFuse, a small DSL for attention that makes pre-multiplication transformations like RoPE first-class operations. Researchers compose ten high-level building blocks to describe a variant, and AttnFuse's compiler emits a single fused GPU kernel for the entire computation. On an RTX 3090, AttnFuse achieves a 2.10$\times$ speedu

---

### [140] Bridging the Modality Gap in Long-Form Clinical Audio: A Comparative Study of Lightweight and Heavyweight End-to-End SOAP Generation

**链接**: https://arxiv.org/abs/2609.14467
**作者**: Ziyu Zhang, Mingchen Shao, Wenjie Tian, Tianlun Zuo, Longhao Li, Lei Xie
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automating clinical documentation from long-form doctor-patient conversations remains challenging for modern audio-language models. While cascaded ASR systems perform well, end-to-end (E2E) models often struggle with information loss and hallucinations on extended audio. For the BeTraC 2026 challenge, the ASLP team presents a fully E2E multimodal system that generates structured SOAP notes directly from audio, bypassing intermediate transcripts. We constructed a 1.41-million-sample multi-task corpus and applied a multi-stage pipeline: domain pre-training, supervised fine-tuning, and reward optimization. Evaluating the architecture under both Lightweight (3B) and Heavyweight (30B) constraints reveals that each training stage progressively enhances performance. Furthermore, scaling to 30B parameters substantially boosts concept extraction and summarization quality. Ultimately, our E2E systems consistently outperform representative cascaded ASR+LLM baselines, proving the efficacy of direc

---

### [141] Before You Poll with LLMs: A Deliberative Diagnostic Framework

**链接**: https://arxiv.org/abs/2609.15849
**作者**: Ahmed Wali, Hassaan Tayyab
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can LLMs reason through new information like humans, or do they merely retrieve cached opinions? This is critical for silicon sampling, where LLM personas simulate public opinion at scale. Current evaluations test only whether personas hold the right opinions -- a static snapshot. But opinion research increasingly depends on dynamic fidelity: whether personas update beliefs in response to new arguments, as humans do during deliberation. No existing benchmark tests this. We introduce the Deliberative Polling Diagnostic Framework, which compares human and LLM belief shifts after identical informational interventions. Grounded in deliberative polling, it surfaces failures invisible to static evaluation: models that produce plausible partisan opinions can still misrepresent how those opinions change. Applying the framework to five frontier models using data from America in One Room (526 personas, 72 questions), we find that every model fails, each in a unique manner. GPT-5.1 exhibits rever

---

### [142] GeoSkill:Experience-Driven Hierarchical Skill Learning with Collaborative Revision forGeospatialAgents

**链接**: https://arxiv.org/abs/2609.13667
**作者**: Han Luo, Xian Xu, Yinhe Liu, Yanfei Zhong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial agents are increasingly expected to support recurring and evolving analytical tasks rather than execute isolated workflows. In such settings, effective agents must distill prior execution experience into reusable geospatial procedural knowledge to guide future planning and tool use. However, existing memory-augmented paradigms struggle to summarize both long-horizon tool-chain orchestration experience and tool-level invocation constraints in geospatial analysis, while directly relying on LLM self-reflection to update experience often leads to misattribution and unreliable revisions. To address these challenges, we propose GeoSkill, an experience-driven hierarchical skill learning framework for geospatial agents. GeoSkill comprises two core components: (i) a Hierarchical Skill Bank (HSB), consisting of a Planning Skill Bank and a Tool Skill Bank, which respectively distill high-level task-planning experience and tool usage constraints, enabling structured representation and c

---

### [143] ABSOL: Aggregated Bayesian Subsampling Orchestrated with LLMs

**链接**: https://arxiv.org/abs/2609.15007
**作者**: Jackson Hassell, Chen Shen, Estevam Hruschka
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as natural-language interfaces to structured data, yet they remain unreliable when answers require consistent evidence conditioning, dependency-aware reasoning, and uncertainty estimation. Bayesian networks provide an explicit probabilistic reasoning layer, but learning useful structures from data remains costly and fragile at scale. We introduce ABSOL, a hybrid LLM-guided Bayesian network structure-learning framework that uses LLMs as bounded semantic guides. Across five discrete BN benchmarks spanning 27 to 1041 nodes, ABSOL is the only evaluated method to produce a viable graph on every benchmark, and achieves the highest Edge F_1 on every benchmark larger than 27 nodes with GPT-5.4. The four LLM augmentations, which contribute complementary semantic evidence to the statistical backbone, improve Edge F_1 over the non-LLM aggregation backbone by +0.23 on average. Complementary post-hoc refinement experiments suggest that these gains depend 

---

### [144] Empirical Evaluation of Open-Source Large Language Models for Retrieval-Augmented Generation in ESG Domain

**链接**: https://arxiv.org/abs/2609.15242
**作者**: Motaz Saad, Anna Borrelli, Ivan Gentile, Kianna Kazemi, Francesco Piccialli, Antonella Longo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Environmental, Social, and Governance (ESG) reporting is critical for corporate accountability, with Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) offering strong potential to automate KPI extraction. However, open-source LLM performance in domain-specific ESG tasks remains insufficiently understood. This paper evaluates open-source LLMs in ESG contexts using a structured framework and evaluation resource based on 498 real-world ESG reports from EU-listed companies (2010-2024). We evaluate seven open-source models (2B to 30B parameters) -- glm-4.7-flash, nemotron-3-nano:4b, qwen3:4b-instruct, gemma3:4b, gemma4:e4b, gemma4:e2b, and ministral-3:8b -- using 100 persona-based synthetic QA pairs covering ESG information needs. System performance is assessed via RAGAS metrics, including contextual recall, precision, relevance, faithfulness, answer relevancy, and factual correctness. Results show notable performance variations across architectures. Retrieval performanc

---

### [145] LLMs or Naive Bayes? Old Gems or New Ways

**链接**: https://arxiv.org/abs/2609.13185
**作者**: Mohammad Firas Sada, Dmitry Mishin, John Graham, Seungmin Kim, Mahidhar Tatineni, and Frank W\"urthwein
**来源**: cs.LG cs.AI cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) prompt a recurring question in research computing: should classical methods like Naive Bayes (NB) be retired? We benchmark Complement Naive Bayes against zero-shot and few-shot LLMs spanning four model families and a 37x range in scale (27B to a 1T-parameter mixture-of-experts) across text classification tasks. LLMs dominate only in zero-data regimes (98.0% vs 88.2% on Amazon Polarity sentiment), and even that win is contamination-prone: on a low-contamination sentiment task NB beats the zero-shot LLM (81.7% vs 73.0%). However, once labeled data is available (e.g., AG News), NB reaches 89.1% accuracy, statistically indistinguishable from the zero-shot 27B LLM (89.0%) and better than the 397B frontier model (84.8%), at thousands of samples/sec on a commodity CPU. Fine-tuned DistilBERT reaches 90.6% but at far lower throughput than NB at batch size 1 (Table 2). Our measured GPU throughput analysis shows small-LLM batched inference is 40-486x slower than NB CP

---

### [146] Assembling the CREW: A Collaborative Multi-agent Reinforcement Learning Framework for Automated Related Work Generation

**链接**: https://arxiv.org/abs/2609.15721
**作者**: Hai-Dang Dang, Bao-Yen Pham, Bao Nguyen, Tran Thi Huong, Huynh Thi Thanh Binh
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Related Work Generation (RWG) significantly reduces the human time and effort required to author the Related Work Section (RWS) of a research paper. However, prior methods leveraging multi-agent Large Language Models (LLMs) typically rely on a predefined workflow, where each agent is responsible for a specific step in the entire process. This rigid, static inter-agent coordination limits the adaptive collaboration required to synthesize complex scientific literature. To address this limitation, we propose CREW (Collaborative Reinforcement Learning for Related Work Generation), a novel framework where LLM agents bypass heuristic pipelines to dynamically coordinate by autonomously selecting actions, such as Retrieve, Disseminate, Compose, and Critique, driven by a policy optimized via Independent Proximal Policy Optimization (IPPO). Extensive experiments on a standard RWG benchmark demonstrate that our approach yields substantial quality improvements over strong existing baseli

---

### [147] Disentangling Topology and Diversity in Multi-Agent LLMs for Multilingual Low-Resource Emotion Detection

**链接**: https://arxiv.org/abs/2609.14570
**作者**: Ulugbek Shernazarov, Charitha Ruwansiri Weerakon Basnayake, Abdelkhaleq El Jarjini, Noel Crespi, Praboda Rajapaksha
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems combine multiple inference calls, but prior work often confounds how calls are connected with how they are diversified. We study these factors independently: inference topology and source of inter-agent diversity. In a controlled $2 \times 3$ matrix, we cross parallel aggregation and sequential refinement with stochastic sampling, role prompting, and learned QLoRA specialization, under a fixed three-call budget and output protocol within each backbone. Using Qwen2.5-14B-Instruct and Llama-3.1-8B-Instruct, we evaluate all six configurations on multilingual low-resource emotion detection across nine languages. Parallel learned specialization is strongest on Qwen at 52.83 Macro-F1 and reaches 52.94 on Llama. On Qwen it also exceeds same-backbone zero-shot, few-shot, CoT, and seven-call self-consistency baselines. The preferred topology depends on diversity source: sequential refinement helps stochastic and prompted settings, while the learned Width advantage shrink

---

### [148] Carryover Drafting: Recycling Rejected States for Speculative Decoding

**链接**: https://arxiv.org/abs/2609.14717
**作者**: Jahyun Koo, Sunghyeon Woo, Jaeeun Kil, Jeongtae Lee, Sungjae Lee, Kyomin Jung 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates LLM inference by verifying multiple drafted tokens in parallel, allowing a single target forward pass to accept several tokens. By construction, verification computes representations for both accepted and rejected tokens. Yet, conventional drafters retain only the representations of accepted tokens, leaving the substantial verifier computation spent on rejected tokens effectively wasted. We find that these discarded hidden states generated during target forward retain useful information about future tokens that can improve subsequent drafts. However, realizing this opportunity poses two distinct challenges. At inference, recycling overhead can increase drafting latency, diminishing the speedup gained from increased acceptance length. During training, standard parallel drafter training does not produce inference-aligned rejected states, while obtaining them through sequential rollouts would sacrifice parallelism across training positions. We introduce Ca

---

### [149] Corrupt Plans, Clean Traces: Evading Chain-of-Thought Monitoring with Plan Injection

**链接**: https://arxiv.org/abs/2609.15989
**作者**: Keertana Chidambaram, Andrew Ilyas, Vasilis Syrgkanis
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought (CoT) monitoring is a safety strategy where the reasoning of a large language model "actor" is inspected by a "monitor" (often another language model) for signs of unsafe planning, deception, or misalignment. We find that planting harmful but benign-sounding reasoning in the actor's context can steer it to perform adversarial actions while evading monitors, an attack we term "plan injection". We initially discover this attack in the multiple-choice question-answering monitorability setting proposed by Lanham et al. (2023), using the investigator-agent elicitation framework of Li et al. (2025). We generalize the attack and show that the discovered behavior scales to harder tasks (achieving 25-33% monitor evasion rates across different monitorability benchmarks) and larger models such as DeepSeek-R1. Across the settings we study, actor models not only follow injected plans but also paraphrase them as their own reasoning, without explicit attribution to the injections. Fi

---

### [150] Toward Complete Hospital Discharge Summarization with Abstract Meaning Representation

**链接**: https://arxiv.org/abs/2609.13581
**作者**: Paul Landes, Sitara Rao, Aaron Jeremy Chaise, Barbara Di Eugenio
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Discharge summaries are lengthy medical documents that summarize a hospital in-patient visit. Automatically generating them can reduce documentation burden and return clinician time to patient care. Whereas Large Language Model (LLMs) could be used for this task, their Achilles heel is hallucinations, which can have drastic consequences for clinical documentation. We present an evidence-driven alignment framework for discharge summarization at the clinical encounter level, that treats provenance as a first-class constraint, using semantic graphs and deep learning models. Each summary sentence is selected and organized via cross-document semantic alignment and is accompanied by explicit evidence links to its source spans. We show our results on two corpora: a publicly available corpus (MIMIC-III) and clinical notes written by physicians at the University of Illinois Hospital (UIC Health). Additionally, we make source code and trained models available.

---

### [151] A Multi-Stage Agentic Framework for Effective Counter-Narrative Generation and Refinement

**链接**: https://arxiv.org/abs/2609.14178
**作者**: Carmel Kronfeld, Sharva Gogawale, Tetsuro Kobayashi, Irad Ben-Gal
**来源**: cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid diffusion of hate speech and misinformation on social networks challenges democratic societies, since direct suppression efforts may deepen polarization, fuel public distrusts, and strengthen extremist narratives. LLM-driven counter-narratives (CNs) offer a promising way to reduce those risks, yet their effectiveness depends on rhetorical and stylistic choices that remain poorly understood. We present a multi-stage agent-based framework for generating, refining, and evaluating CNs, applied to pro-Russian hate and misinformation narratives on the war with Ukraine and adaptable to other domains. A pilot experiment with human evaluators identifies effective technique style pairings, such as repetition with emotional framing enhancing persuasiveness. Building on these insights, we introduce a multi-agent refinement process that iteratively improves CNs for persuasiveness, emotional engagement, and shareability. After human validation confirmed improvement, an automated safety ana

---

### [152] DynSTEER: Dynamic Stage-wise Trajectory Evaluation and Execution-time Review for Agents

**链接**: https://arxiv.org/abs/2609.14637
**作者**: Zhichao Shi, Wenjie Zhang, Xuhui Jiang, Xiaojun Wu, Cehao Yang, Chengjin Xu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly deployed for long-horizon task execution. However, current evaluation paradigms face three major limitations: terminal-only assessment ignores intermediate processes and struggles to localize errors efficiently and accurately, single-reference matching penalizes valid alternative solution paths, and post-hoc trajectory judging incurs high costs without the ability to halt failed runs early. To address these issues, we propose DynSTEER, a dynamic stage-wise trajectory evaluation framework for agents. DynSTEER segments rollouts into stages anchored by key completed actions, focusing evaluation on essential milestones with adequate context while enabling targeted strategy adjustments. It compiles a path-tolerant milestone graph from public task views to respect diverse legitimate strategies without leaking ground truth. Furthermore, it adaptively routes evaluation queries across multi-tier judges and halts unrecoverable executions online to cur

---

### [153] LLMs as Oracles: Reliance on LLMs for Subjective Personal Questions

**链接**: https://arxiv.org/abs/2609.14849
**作者**: Myra Cheng, Lujain Ibrahim, Grace Liu, Michelle S. Lam, Vishakh Padmakumar, Nick Madibekov 等 (8 人)
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We characterize how people are turning to LLMs as oracles: all-knowing authorities on subjective personal questions. Motivated by risks to users' autonomy and well-being, we develop a typology and LLM-based methods to measure this form of AI reliance at scale and understand how people are offloading judgment and decision-making to AI. Applying our typology to public usage data (68K prompts from WildChat and ThoughtTrace), we find that LLM-as-oracle use has increased over time (2023-2026) and is more prevalent among younger users. We further build a privacy-preserving data donation tool to analyze individuals' longitudinal usage data (140K prompts from 52 participants), identifying similar trends. People are often unaware of their own LLM-as-oracle use, and express dissatisfaction with this behavior after seeing our tool's analysis. Finally, we identify two drivers of LLM-as-oracle use: people's perceptions of AI and the behavior of AI models themselves, which motivate possible interven

---

### [154] PAUSE: A Privacy-Preserving Self-Reflection Tool for AI-Associated Cognitive Offloading

**链接**: https://arxiv.org/abs/2609.13155
**作者**: Mahbub Ul Alam
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cognitive offloading is the use of external aids, such as notes, calculators, or search engines, to reduce mental effort. Large language models (LLMs) extend this to thinking itself, and by AI-associated cognitive offloading, I mean the pattern where a person routinely substitutes LLM output for their own reasoning, idea generation, learning, or communication. Recent empirical work reports associations between some patterns of LLM use and changes in critical thinking effort, neural engagement during assisted tasks, creative diversity, learning behaviour, and social dependence. Validated instruments for AI reliance, dependence, and literacy have begun to appear. I describe PAUSE (Patterns of AI Use: Self-Examination), a privacy-by-design web tool (link: https://anondo1969.github.io/pause) that occupies a different niche from these. It is a lightweight, non-diagnostic reflection aid for private individual use. PAUSE is organised around how a person's own LLM use may relate to cognitive o

---

### [155] TyPatch: Transforming Patches into Typestate Rules for Kernel Bug Detection

**链接**: https://arxiv.org/abs/2609.13728
**作者**: Ruoyu Wang, Tuo Li, Jia Li
**来源**: cs.SE cs.AI cs.CR cs.OS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical Linux kernel patches capture defect knowledge that applies beyond their original repair sites. Recent work has shown that large language models (LLMs) can generate static-analysis checkers from historical patches and use them to uncover new kernel bugs. However, complete-checker generation requires the model both to recover the defect semantics expressed by a patch and to implement sophisticated program-analysis machinery, including object tracking, alias analysis, path-state maintenance, and interprocedural propagation. Coupling these responsibilities in a single end-to-end code-generation task can turn a simple defect rule into an unstable and expensive analyzer-implementation problem. To address this problem, we present TyPatch, which decouples patch-specific defect semantics from analyzer implementation. An LLM translates each patch into a typestate rule specifying its tracked object, actions, guards, transitions, and violations. A shared backend then executes these rule

---

### [156] Lie to me: Detecting Managerial Evasiveness in Earnings Calls via Conversational Audio Encoders

**链接**: https://arxiv.org/abs/2609.13893
**作者**: Huizhong Chen, Huan Zhang
**来源**: cs.LG cs.CE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earnings conference calls are a primary channel through which managers disclose information under analyst scrutiny. Prior work has linked vocal and lexical cues to future adverse outcomes, but often pools features over an entire call and underuses the interactive structure of Q&A. We propose a two-branch late-fusion framework for detecting managerial evasiveness as a predictor of extrinsic SEC events (primarily late filings): (i) an LLM-as-a-judge that maps Q&A text to an interpretable call-level vector X_text via a structured binary rubric, and (ii) a frozen conversational encoder whose temporal hidden states are read by a DeepVoice-style sequential reader to produce an audio representation h. Late fusion of (X_text, h) yields a call-level risk score p. On n=1,039 calls (212 late filings) with firm-grouped 5-fold CV, fusion reaches AUROC approx. 0.89, versus 0.55 for the text judge and 0.71 for duration alone. These results show that conversational audio dynamics encode managerial eva

---

### [157] Medical Knowledge Simplification for Patients in the Era of LLMs: A Case Study on Diabetes

**链接**: https://arxiv.org/abs/2609.15129
**作者**: Pallika Kafle, Yipeng Zhou, Guanfeng Liu, Quan Z. Sheng, and Cheng-Hsin Hsu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex medical information is often difficult for patients to understand, making effective medical knowledge simplification essential for improving patient comprehension, informed decision-making, and health outcomes. Recent advances in large language models (LLMs) provide a promising approach for simplifying complex medical information into patient-friendly language; however, their effectiveness in real-world patient education remains insufficiently explored through human evaluation. To investigate their practical effectiveness, this paper presents a case study on diabetes knowledge simplification through the implementation and evaluation of MediClear, an LLM-based medical knowledge simplification system enhanced with Retrieval-Augmented Generation (RAG). Public diabetes-related articles from Diabetes Australia, WHO, American Diabetes Association (ADA), NIDDK, and AIHW are indexed in the RAG knowledge base to retrieve clinically grounded information, which is then simplified by the L

---

### [158] Synthetic Data in Marketing Research: How to Evaluate and When to Trust

**链接**: https://arxiv.org/abs/2609.13995
**作者**: Oded Netzer and Rajan Sambandam
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Debate over synthetic data in marketing research has polarized between claims that large language models (LLMs) make human respondents obsolete and calls to avoid them entirely. We argue that both positions obscure the more useful question: not whether synthetic respondents work, but when. Building on Brand, Israeli, and Ngwe (2026), we make three contributions. First, we distinguish three types of synthetic data (ungrounded LLM responses, segment-level personas, and individual-level digital twins) and map each to the decisions it can support. Second, we develop a taxonomy of four families of accuracy measures and suggest that the wide range of reported twin accuracy, from near-perfect to near-chance, largely reflects differences in what is being measured rather than in method quality. Aggregate measures often perform well even when little information is supplied to the LLM, and can mask a complete absence of respondent-level differentiation. Third, we introduce the forgotten question 

---

### [159] Learning to Solve Hard Problems in RL for LLMs by Never Giving Up

**链接**: https://arxiv.org/abs/2609.13443
**作者**: Michael Noukhovitch, Hamish Ivison, Nathan Lambert, Aaron Courville
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We demonstrate that training LLMs with RL does not improve performance equally across a dataset. RL shows large improvements on easy problems that an LLM is already good at solving, but small improvements on hard problems. We call this the Matthew Effect in RL for LLMs, after the phenomenon of cumulative advantage from economics and network science summarized as "the rich get richer". The naive explanation is that hard problems require more compute to find a solution. We argue that modern RL methods are exacerbating the issue by wasting too much compute on easy problems and instead should dynamically reallocate how they use compute. We introduce Never Give Up (NGU), a simple adaptive sampling method that keeps generating samples for a problem until one is correct. By leveraging asynchronous RL, this naturally uses fewer samples to filter out easy problems and allocates more compute to solving harder problems. We investigate the design choices that affect NGU, such as off-policy robustn

---

### [160] SlopShape: Identifying AI-Generated Commercial Web Content

**链接**: https://arxiv.org/abs/2609.15369
**作者**: Jochen Madler (Sitefire)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Word-level detectors identify unedited AI-generated text almost perfectly, but the literature documents their brittleness under rewording, and a word-level score neither characterizes a text nor identifies which AI model wrote it. We ask whether AI-generated text can be identified one level deeper, from structural signatures: how information is presented, in what order, with what evidence, and in what voice. We replicate StoryScope (Russell et al., 2026), which showed such patterns for AI-generated fiction, on commercial content: 2,250 pre-ChatGPT human blog posts from 268 company domains against 11,250 AI mirrors from five frontier models. A 214-feature instrument, applied by an LLM and validated in a human gold-annotation session (human-human kappa 0.928, human-model 0.946), detects AI posts from its 187 structural features alone at 98.0 macro-F1 on held-out companies, unchanged (98.1) when every AI post is reworded by its own model. The signal characterizes and attributes: AI posts 

---

### [161] TEAR: Table Extraction with Attribute Recommendation from Texts via Large Language Models

**链接**: https://arxiv.org/abs/2609.15205
**作者**: Tong Li, Shuye Ding, Jiachuan Wang, Yongqi Zhang, Shuangyin Li, Lei Chen 等 (7 人)
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Table extraction from texts is an important task for information systems, and recent approaches that prompt large language models (LLMs) with instructions have drawn great attention for their strong performance. Existing works have assumed the input texts to be table descriptions or specialized documents. However, these efforts have largely overlooked another prevalent category of texts, commonly found in news reports and social media: naturally occurring texts. Extracting tabular information from such texts poses two distinct challenges. First, high variability and the absence of explicit structural cues make fixed heuristic LLM prompts limited in precisely delineating extraction boundaries. Second, manually predefined schemas cannot capture open-ended, unseen attributes in naturally occurring text. In this paper, we propose a framework, TEAR, to address these challenges. It comprises two synergistic workflows: a Table Extraction Workflow that dynamically adapts instructions to overco

---

### [162] RFCLLM: Evaluating LLMs' Reasoning Ability of Network Protocol State Machines

**链接**: https://arxiv.org/abs/2609.13389
**作者**: Anqi Chen, Dan Goldwasser, Cristina Nita-Rotaru
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mapping textual specifications into formal representations is essential for ensuring the correctness of protocol designs and implementations. LLM-generated mappings, used for networking security or testing, are assumed to capture a perfect understanding of the specification, which may not hold in practice. The goal of this paper is to assess the extent to which LLMs can interpret the specification correctly. We examine the degree to which an LLM's implicit representation of a finite-state transition system-defined via natural language descriptions-aligns with a manually generated ground-truth model. We designed 4 tasks and 1482 task queries for 16 protocols. We evaluated different judge biases, observed the inherent difficulty gaps between tasks, looked into the effect of 4 context types, and the influence of protocol characteristics. Our work contributes to a step toward verifying whether LLMs can really be trusted in FSM (Finite State Machine) reasoning of protocol specifications.

---

### [163] A primer on evaluation methods for large language models in healthcare

**链接**: https://arxiv.org/abs/2609.14819
**作者**: Suzannah E McKinney, Phuc Vu, Samuel A Justice, Christopher Humphries, Alyssa Pradhan, Timothy J Keyes 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have a growing range of applications in medicine, and their evaluation is critical for ensuring they provide benefit and not harm. This evaluation can be more challenging than traditional machine learning for many reasons, including probabilistic and open-ended outputs, and behavior that shifts with prompt design and accumulated context. This review covers four key areas of LLM evaluation: principles of study design, statistical methods, capability evaluation and clinical context evaluation. Capability evaluation considers different benchmarks, including multiple-choice, agentic and multi-turn benchmarks, alongside operational metrics like token usage. Clinical context evaluation addresses establishing accuracy of free text outputs, such as human review and LLM-as-a-judge, and clinical trial approaches. Across sections, we describe underlying concepts and potential pitfalls, while emphasizing the importance of aligning evaluation methods with the research q

---

### [164] Translating the Translator: Decomposing the Cost of English-Forced Inter-Agent Communication

**链接**: https://arxiv.org/abs/2609.15079
**作者**: Kushagra Agrawal, Yuming Feng, Man-Fai Leung
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM architectures, such as LangChain and AutoGen, largely assume English as the lingua franca for internal inter-agent communication, even when the end-user task is non-English. We fill this gap by evaluating a two-agent extraction-answer core, with an additional back-translation agent in the English-forced condition, across four typologically diverse languages (Hindi, Chinese, Spanish, Arabic; n = 300 per language) using the Aya-23-8B model. We compare a native-language pipeline to an English-forced one (which incorporates a final back-translation step from English to the user's language). We discover a statistically significant English-Forcing Tax (surviving a strict Bonferroni correction) that isolates the cost of English routing from general multi-agent orchestration overhead. Forcing inter-agent communication through English reduces Exact Match accuracy by 13.0 percentage points (Spanish) up to 30.6 percentage points (Hindi) compared to native-language multi-agent exec

---

### [165] Authorship attribution and aesthetic evaluation of AI poetry: a case study with Haiku

**链接**: https://arxiv.org/abs/2609.15511
**作者**: Livia Oddi, Simone Scardapane, Toru Sugimoto, Donatella Genovese
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper investigates the generation and human evaluation of Japanese haiku by contemporary Large Language Models (LLMs), focusing on authorship perception and aesthetic judgment within a constrained poetic form. Using a few-shot prompting strategy, Japanese haiku were generated across a heterogeneous set of large language models, including open- and closed-source systems, medium-scale and large-scale architectures, models with native or adapted Japanese support, and multilingual proprietary models. These AI-generated haiku were combined with human-written ones and presented in a questionnaire distributed to students at Japanese universities in Tokyo. The survey assessed whether respondents could distinguish between AI-generated and human-written haiku and which cues informed their judgments. Recognition accuracy varied across models. GPT-5, Gemini 2.5, and StableLM-7B performed at approximately chance level (approx 0.50), whereas LLM-JP, Gemma-2B, and LLaMA-2 showed moderate detecta

---

### [166] A latent dimension of Condorcet's jury theorem for multiple AI advisers

**链接**: https://arxiv.org/abs/2609.14438
**作者**: Kazutoshi Sasahara, Aoi Naito, and Ryo Fujie
**来源**: cs.CY cs.AI cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When the same question is asked of multiple AI advisers, as in self-consistency and LLM-as-a-judge panels, Condorcet's jury theorem predicts that adding independent, competent advisers makes the majority more reliable. The theorem, however, has a latent dimension when viewed from the user's vantage: adding advisers also makes disagreement more visible. A binomial model reveals that this ``visible dissent'' becomes nearly inevitable as the number of advisers grows, and that reliability and disagreement both approach certainty but at different convergence rates. The two rates cross at an adviser accuracy of 4/5 (0.8). Below this value, visible dissent approaches certainty faster than reliability and, with enough advisers, becomes more likely than a correct majority. Even ideal panels of independent and competent advisers can be correct in aggregate but appear divided; such disagreement does not by itself indicate aggregation failure. The way advisers split also provides a common basis fo

---

### [167] IWC-Bench: Evaluating Web Application Generation from a Software Testing Perspective

**链接**: https://arxiv.org/abs/2609.15387
**作者**: Chenxu Liu, Zilu Zou, Peizhong Gao, Jiawen Tao, Zhexin Zhang, Guang Chen 等 (10 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human evaluation provides a direct measure of the quality of LLM-generated web applications. However, fitting human judgments through automated evaluation remains challenging. Static benchmarks can credit functionality that exists in source code but is unreachable at runtime. Interactive benchmarks exercise the application, yet incomplete exploration can cause them to miss implemented functionality and confound application defects with agent execution failures. To address these limitations, we propose IWC-Bench, an interactive benchmark for evaluating web application generation from a software testing perspective. IWC-Bench instruments each generated application and uses code coverage to guide an agent in exploring its functionality through user-simulated interactions. It then abstracts the interaction trace into a state-transition graph and evaluates the application along three dimensions: visual aesthetics, usability, and requirement alignment. By separating exploration from scoring,

---

### [168] Asclepius: An Adaptive Harness for Long-Horizon Clinical Agents

**链接**: https://arxiv.org/abs/2609.13543
**作者**: Grace Chang Yuan, Xiaoman Zhang, Sung Eun Kim, Luyang Luo, Pranav Rajpurkar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are predominantly benchmarked on short, single-task trajectories, yet real deployments run for hours under contention, surfacing a different class of failures. We use the Clinical Environment Simulator (CES), in which an agent manages an entire emergency-department shift under continuous time and resource pressure, as a testbed: long-horizon execution failures manifest measurably in a single rollout under structured, multi-dimensional grading. On CES, current agents reach the correct diagnosis in most cases yet fail to deliver complete and timely critical actions, revealing an execution gap. We attribute this gap to three long-horizon failure modes, each operationalized as a per-trace counter: instruction-adherence drift, treatment incompleteness, and a severity-equity gap in timeliness. We then introduce Asclepius, an adaptive agent scaffolding with a self-evolving harness that rewrites the operating manual between shifts from trace-level feedback, an externalized clinical 

---

### [169] Criticality in Dissimilar Decomposition and Undersampling of Random Datasets with Anomalies

**链接**: https://arxiv.org/abs/2609.13201
**作者**: Ghurumuruhan Ganesan
**来源**: cs.LG cs.IT math.IT math.PR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training datasets for upcoming LLMs would include a significant amount of AI text/image data generated from current LLMs. In such a scenario, it is important to understand how this affects batch decompositions and thereby, the performance of the resultant new LLM. In this paper, we consider AI generated data as anomalies ``linked" to main data points and study decomposition and undersampling properties of the overall random dataset. We use redundancy graphs and iteration techniques to obtain bounds for the minimum size of a strongly dissimilar (SD) decomposition and demonstrate a phase transition phenomena, wherein the minimum size is essentially determined by the \emph{main} data points when the number of anomalies is small and is ``taken" over by the anomalies above a certain threshold. We also establish a size criticality result for the strong similarity of a randomly undersampled dataset and illustrate our results with examples involving categorical datasets, whose overall space si

---

### [170] Dynamic Semantic Compression for Efficient Latent-Space Inference in Large Language Models

**链接**: https://arxiv.org/abs/2609.15338
**作者**: Peipei Li, Dongsen Zhang, Yuchen Liu, Wenjun Xu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) primarily perform inference at the token level, resulting in substantial memory overhead and compromised computational efficiency. In this paper, we propose a Dynamic Semantic Extraction and Inference (DSEI) framework, which achieves segment-level inference within the latent space through a two-stage training strategy. First, we construct a Dynamic Semantic Autoencoder (DSAE) via self-supervised learning. DSAE dynamically extracts segment-level semantics and compresses them into compact latent representations via adaptive semantic weighting and gated fusion. Subsequently, we integrate the DSAE into the LLM architecture and train the model to infer over dense latent space. DSEI substantially reduces both input and generation sequences and significantly enhances inference efficiency. Extensive experiments conducted on the Wanjuan dataset demonstrate that DSEI reduces perplexity by 48% compared to static sentence-level latent inference baseline. Furthermore, c

---

### [171] Specifying Reward Functions for RL Without Environment Sampling

**链接**: https://arxiv.org/abs/2609.15544
**作者**: Stephane Hatgis-Kessell, W. Bradley Knox, Emma Brunskill
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enabling human stakeholders to specify reward functions that lead to their desired outcomes is a key challenge in deploying reinforcement learning agents. Preference-based methods such as online RLHF can reduce the burden of manual reward design, but they require repeatedly training policies, sampling trajectories from the real world, and eliciting feedback, making them impractical in settings where environment interaction is computationally expensive or unsafe. We introduce Experience-Free Autonomous Reward Specification (EARS), a method for learning reward functions from preferences without environment interaction. Our approach uses a structured LLM-mediated process to construct a small set of expressive reward features from a task description and the environment observation space, then strategically samples imagined trajectories in this feature space and learns feature weights from preferences over the imagined trajectory pairs. We evaluate on three long-horizon domains: pandemic lo

---

### [172] Algorithm Validation as a Policy Audit: Evidence from Race-blind Charging

**链接**: https://arxiv.org/abs/2609.13174
**作者**: Muskan Walia, Joe Nudell, Alex Chohlas-Wood
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> California recently required all prosecutors in the state to conduct a "race-blind charging" decision by reviewing case documents in which selected race-related proxies have been redacted. We validate bc2, an open-source, LLM-based algorithm that we developed to automate this redaction and that was used to facilitate race-blind review in more than 119,000 real-world cases in 2025. We evaluate two distinct questions: whether bc2 faithfully implements the state's requirements and whether those requirements, even when faithfully implemented, advance the goal of race-blind decision-making. To do so, we draw on a corpus of nearly 5,000 real-world police reports that we assembled from jurisdictions across the United States. Under a stringent document-level measure, we find that the latest version of bc2 faithfully implements the legal mandate on 96.7% of narratives in our sample. This performance represents a substantial improvement over earlier versions of bc2 and exceeds that of leading op

---

### [173] Does Reasoning Improve Psychological Depth in Large Language Models? It Depends on Who's Judging

**链接**: https://arxiv.org/abs/2609.13773
**作者**: Ruichen Zheng, Yihe Wang, Fabrice Y Harel-Canada, Sara Khosravi, Zeynep Senahan Yildiz, Amit Sahai 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge evaluators are increasingly used to score open-ended generation, yet a judge's correlation with human ratings on its development set may not guarantee valid measurement when outputs are closely matched and human preferences are subjective. We study this failure mode through psychological depth in short stories. Seven human readers and an LLM-judge ensemble selected on the original scalar Psychological Depth Scale dataset ($\rho = 0.646$) evaluated 60 blinded, prompt-matched story pairs from GPT-5 vs.\ GPT-4o and DeepSeek-R1 vs.\ DeepSeek-V3. Human preferences showed no universal reasoning advantage: GPT-5 was modestly preferred over GPT-4o (60.0--62.9\%), whereas DeepSeek-R1 trailed V3 (42.9\%), and inter-reader agreement was near chance (Krippendorff's $\alpha = 0.070$), with within-reader consistency and recurring weighting patterns suggesting structured heterogeneity rather than random responding. The judge, by contrast, favored reasoning outputs in 89.0\% of dimensio

---

### [174] North Small Translate: Advanced Cost-Effective Translation (Cohere CAT+)

**链接**: https://arxiv.org/abs/2609.13916
**作者**: Tom Kocmi, Alexandre B\'erard, Phil Blunsom, Samuel Cahyawijaya, Shaun Cassini, Nicholas Frosst 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present North Small Translate, an open-weight, LLM-based machine translation (MT) model with instruction-following capabilities built on the same foundation as Cohere's Command A Plus, a mixture-of-experts architecture with 25 billion active parameters out of 218 billion total parameters. North Small Translate is trained using difficulty sampling to obtain challenging documents and a five-step training protocol combining supervised fine-tuning, direct preference optimization, and online reinforcement learning. We prioritized throughput through a non-reasoning base model and supplemented with optional agentic capabilities to unlock translation quality gains. North Small Translate is trained to perform MT-related tasks, including post-editing and quality estimation, as well as related tasks such as general instruction following. The model achieves top MT performance across 50 languages in the class of models under 1T parameters, with no need to run expensive reasoning at inference tim

---

### [175] Grounded Adjudication of Variations across Extracted TimeLines (GAVEL): Comparing Clinical Timelines Against Their Case Reports

**链接**: https://arxiv.org/abs/2609.13475
**作者**: Jack Cummins, Sayantan Kumar, Ketan Tamirisa, Jeremy C. Weiss
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing pipelines for clinical timeline extraction from case reports are evaluated using an expert reference and are limited by imperfect reference annotations and imprecise event alignment. We developed GAVEL, an LLM judge protocol that compares two timelines with the case report and returns a discrepancy type, verdict, and report passage for each difference. We evaluated the event matcher, reviewed 2,738 findings from GPT5.6sol and DeepSeek V3.2, ranked six LLM extractors and two human annotators, and tested GAVEL guided merging. True match rates were 60% immediately below and 48% immediately above the 0.10 cutoff. Manual review confirmed 89.4% and 88.6% of findings. Across 126 reports, merged timelines were preferred in 77.0% of comparisons (95% CI, 69.8 to 84.1%) and reduced discrepancies attributed to the evaluated timeline from 7.63 to 0.85 per report. GAVEL supports report-based comparison and revision without treating either timeline as ground truth.

---

### [176] How broad is that claim? Mapping Generalisation in NLP Research

**链接**: https://arxiv.org/abs/2609.14770
**作者**: Chenxin Diao, Nataliya Stepanova, Emily Allaway
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generalisations are common in scientific communication, even though they are semantically ambiguous. An automated method is needed to identify and categorise claims according to their level of generalisation, in order help detect an over-reliance on generalisations and possible misrepresentations of scientific findings. We introduce a comprehensive taxonomy of generalisations in the scientific domain, NLPGenX, which labels claims according to their level of generality and framing within the text. We operationalise this taxonomy with an LLM-powered framework, NLPGenA, that automatically classifies sentences from scientific articles into 5 different generalisation classes. We validate our framework with human annotators and use the framework to construct a large-scale dataset of NLP papers annotated according to generality, with auxiliary labels for hedging and vague descriptors (NLPGens). We use NLPGens to analyse the use of generalisations in NLP papers across multiple venues and subdo

---

### [177] SHIFT-M3: Pre-fusion Alignment-based Consistency Screening for Multimodal ECG Record Integrity

**链接**: https://arxiv.org/abs/2609.13874
**作者**: Md Ashik Khan and Md Nahid Siddique
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal clinical AI typically assumes that the waveform, report, metadata, and downstream predictions attached to a record belong to the same patient. In practice, linkage failures can silently assemble individually plausible but cross-patient components, creating a safety problem that standard predictive models are not designed to detect. We study this problem as multimodal record integrity triage: given an assembled record, should its modalities be trusted to belong together? We introduce SHIFT-M3, a lightweight text-based pre-fusion screen that measures alignment-based consistency between two separately produced ECG text views: an LLM-generated interpretation and a clinical report summary. On 784,680 MEETI ECG records, SHIFT-M3 achieves 97.6% TPR@5% FPR for full text-view swaps (AUROC 0.996), 90.3% for partial swaps (AUROC 0.974), and 97.7% for label-matched hard negatives (AUROC 0.996) with only 573,569 parameters. Compared with same-dataset lexical baselines, the gains are larg

---

### [178] Overflip: Repetition-Induced Label Flips in Guardrail Models

**链接**: https://arxiv.org/abs/2609.15013
**作者**: Xu He, Chih-Hsuan Lin, Hung-Mao Chen, Junjie Xiong, Yan Zhai, Kun Sun
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Guardrail models are classifiers deployed to screen malicious prompts and responses in LLM-based services. To meet latency constraints, many lightweight guardrails adopt compact Transformer backbones (e.g., DeBERTa) that are trained with short context windows (typically 512 tokens) and rely on bucketed relative positional encodings to process longer inputs. Prior evaluations assume that a guardrail's decision is stable as the input is lengthened. We show that this assumption can fail. We identify Overflip, a repetition-induced instability where repeating a prompt causes the guardrail's prediction to flip (MAL$\to$BEN) as the sequence grows. We conduct experiments on 9 widely used lightweight guardrail models. Five exhibit MAL$\to$BEN flips on a benchmark of 100 prompts, with confidence margins shrinking steadily with repetition. Among these vulnerable models, flip rates range from 8% to 92%, with first flips occurring at roughly 2.6k--9.4k tokens. Our analysis suggests Overflip differs

---

### [179] Converting Sequenced Fuzzy Cognitive Maps to Causal Virtual Worlds with Large Video Generators

**链接**: https://arxiv.org/abs/2609.14985
**作者**: Akash Kumar Panda, Olaoluwa Adigun, Bart Kosko
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We show how users can create and manipulate causal virtual worlds with large-language-model (LLM) and large-video-model agents. The approach uses feedback fuzzy cognitive maps (FCMs) both to model the granular causal structure of the virtual world and to guide its causal evolution. The local causal rules are partial or fuzzy while the FCM's feedback structure produces global equilibria that define causal scenarios. A sequence of \emph{dynamical} meta-rules of the form ``If $\mathcal{A}$ then $\mathcal{B}$" define the causal scenes of the virtual-world video. The if-part causal pattern $\mathcal{A}$ perturbs the FCM's virtual world at the user's or agent's discretion. The FCM's transient feedback dynamics define the meta-rule's causal arrow of implication. The then-part $\mathcal{B}$ is the resulting equilibrium attractor such as a FCM limit cycle or fixed point. Our algorithm extracts these meta-rules from the FCM and guides the LLM agent to write a script based on the FCM meta-rule se

---

### [180] Improving Mathematical Reasoning Capabilities in Large Language Models via Reasoning Process Error Classification

**链接**: https://arxiv.org/abs/2609.15145
**作者**: Runa Yoshida, Kosuke Nishida, Kyosuke Nishida
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The reasoning ability of large language models (LLMs) is a critical factor for practical LLM-based applications. To investigate the current reasoning capability of LLMs, we clarify the types of errors that arise in LLMs' reasoning processes on mathematical datasets. We focus on problems where LLMs produce an incorrect answer. We define errors in the reasoning process as reasoning errors and manually analyze the features of reasoning errors. We defined and classified 21 error classes and identified the frequently occurring classes among them. Beyond qualitative evaluation, we leverage the evaluation results to improve the reasoning capability. We designed a prompt that explicitly focuses on eight error classes. The experiments demonstrate that this prompt effectively improves reasoning performance. Furthermore, the results suggest that the frequent reasoning errors identified in this paper are common across LLMs of comparable scale.

---

### [181] Mind2Dialogue: Training Human-Aware Language Models by Simulating User Mental States

**链接**: https://arxiv.org/abs/2609.15972
**作者**: Zixuan Wang, Yufan Zhou, Jinzhou Tang, Xinle Yu, Chengjun Wu, Lyumanshan Ye 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As language models become more capable, long-term collaboration in learning, reasoning, and decision-making calls for a deeper understanding of the people they serve. Yet training such human-aware language models faces a fundamental supervision gap because current datasets for LLM assistant training contain few if any well-informed responses explicitly grounded in users' unspoken beliefs and goals. Scaling such supervision is inherently constrained, as users' underlying states are not directly observable. We thus propose the Mind2Dialogue framework to mitigate this gap by simulating users' mental states and turning them into privileged supervision for human-aware training. Specifically, we first propose a psychology-guided simulator that preserves personal characteristics while updating mental states through interaction to generate coherent conversations. The key idea is to enforce a shared evolving mental state that drives user behavior and guides an Oracle assistant's responses. Our 

---

### [182] From Ideas to Actions: A Public-Data Decision-Support Toolchain Across the Venture Lifecycle

**链接**: https://arxiv.org/abs/2609.15219
**作者**: Lei Qu (Shanghai Xing Yun Zhi Li AI Institute)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Founders face two linked decisions: whether to pursue an idea before founding, and which operating actions and capital partners fit afterward. We present a public-data decision-support toolchain combining time-bounded proposal profiling, market and moat checks, and deterministic aggregation with auditable investor-company event chains for retrospective analysis. Pre-founding: (a) After threshold selection on 198 development companies, the frozen pipeline achieves F0.5=0.5357 [0.412, 0.655] on an independent, row-disjoint 198-company validation sample. On the combined 396 rows, the Full Pipeline scores 0.6301 versus 0.2734 for a paired Raw LLM baseline. Post-stratification of 1,027 completed cases in a separate scale cohort yields 0.6506 [0.598, 0.707]; the run remains incomplete. A 377-row composition-matched check yields 0.6573. (b) The AI-inference study identifies distribution-layer businesses as a replicable path to independent profitability with a limited revenue ceiling, and fron

---

### [183] Beyond Quacking: Deep Integration of Language Models and RAG into DuckDB

**链接**: https://arxiv.org/abs/2504.01157
**作者**: Anas Dorbani, Sunny Yasser, Jimmy Lin, Amine Mhedhbi
**来源**: cs.DB cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge-intensive analytical applications retrieve context from both structured tabular data and unstructured, text-free documents for effective decision-making. Large language models (LLMs) have made it significantly easier to prototype such retrieval and reasoning data pipelines. However, implementing these pipelines efficiently still demands significant effort and has several challenges. This often involves orchestrating heterogeneous data systems, managing data movement, and handling low-level implementation details, e.g., LLM context management. To address these challenges, we introduce FlockMTL: an extension for DBMSs that deeply integrates LLM capabilities and retrieval-augmented generation (RAG). FlockMTL includes model-driven scalar and aggregate functions, enabling chained predictions through tuple-level mappings and reductions. Drawing inspiration from the relational model, FlockMTL incorporates: (i) cost-based optimizations, which seamlessly apply techniques such as batch

---

### [184] Not All Duplicates Are Coordination: Generic vs. Non-Generic Duplicate Campaigns in Information Operations

**链接**: https://arxiv.org/abs/2609.13671
**作者**: Ashfaq Ali Shafin, Khandaker Mamun Ahmed
**来源**: cs.SI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Duplicate content is widely used to study coordinated behavior in social media information operations (IOs), but not all repetition provides equally meaningful evidence of coordination. Generic, reusable, or low-information posts may create noisy account-account links when projected into coordination graphs. We study this problem using 187,000 English-language tweets from six Russian Twitter Information Operations datasets. We introduce a generic/non-generic distinction for duplicate campaigns, label tweets using an LLM-assisted protocol with independent human validation, and train supervised classifiers over sentence embeddings to scale the labels. We construct duplicate campaigns using lexical similarity and two embedding-based methods. Generic campaigns are rare under lexical matching but account for nearly 39% of campaigns detected by embedding-based methods. Restricting graphs to non-generic campaigns reduces graph size and the largest connected component while increasing density,

---

### [185] Mizan: A National Benchmark for Evaluating Large Language Models on Iraqi Arabic and the Iraqi Civic Context

**链接**: https://arxiv.org/abs/2609.13980
**作者**: Nawar S. Alseelawi, Mustafa S. Aljumaily
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Arabic large-language-model (LLM) evaluation has matured around Modern Standard Arabic (MSA): aggregated leaderboards such as the Open Arabic LLM Leaderboard (OALL), HELM Arabic, and BALSAM rank models across dozens of MSA tasks, and frontier systems increasingly saturate them. Dialectal Arabic, the language Iraqis actually speak, remains nearly invisible to this infrastructure. We introduce Mizan ("the balance"), Iraq's national benchmark for evaluating LLMs on Iraqi Arabic and the Iraqi civic context: an MSA baseline track paired with an Iraqi track across six axes (dialect comprehension, dialect generation, bidirectional MSA-Iraqi translation, Iraq-specific knowledge, official-document field extraction, and safety), built from 340 originally authored, dually reviewed items with statistically audited answer positions and Wilson intervals on every published score. A pilot evaluation of 27 systems, spanning closed frontier models three days after release, open weights across size tiers

---

### [186] ESG: Generating Physically Consistent Dynamic 3D Scenes from Text Descriptions

**链接**: https://arxiv.org/abs/2609.15392
**作者**: Xintong Fang, Zhiyuan Fang, Rengan Xie, Xuhong Zhang, Guoyuan An, Zeran Liu 等 (9 人)
**来源**: cs.GR cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in image and 3D scene generation has enabled increasingly realistic static environments, yet most methods remain confined to such static configurations. Generating dynamic scenes from natural language is fundamentally challenging: it requires joint reasoning over scene structure, temporal evolution, and physical feasibility, while ensuring reliable execution in modern physics engines. We present a unified framework for generating physically consistent dynamic 3D scenes from text, with outputs directly executable in Unreal Engine. Central to our approach is the \emph{Evolutive Scene Graph} (ESG), which specifies entities with physical attributes, spatial relations, and event-driven timelines in a machine-checkable form. Given a prompt, a large language model constructs and validates a complete ESG; spatial layouts are grounded via energy-minimized gradient optimization; timeline-constrained physical parameters are then optimized through differentiable simulation to satis

---

### [187] Perceive, Refine, Reason: A Calibrated Pipeline for Measuring Indicators in Strategic Visual Communication on Social Media

**链接**: https://arxiv.org/abs/2609.14699
**作者**: Weihong Qi, Chen Ling
**来源**: cs.CV cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual content shapes audience perception and opinion on social media, and computational social science increasingly relies on automated tools to analyze images at scale. Yet a measurement gap persists: existing tools rely on predefined categories or produce only coarse image-level labels, while measuring which specific objects appear in an image, how prominently, and where in the frame remains difficult at scale. We introduce Perceive, Refine, Reason (PRR), a calibrated pipeline that turns flexible vision-language detectors into auditable measurement instruments for social-scientific research. PRR combines natural-language category prompts with pixel-level spatial refinement via the Segment Anything Model (SAM) and a multimodal LLM arbitration layer whose reasoning chains externalize domain knowledge and lower the expertise threshold for human-in-the-loop validation. A complementary three-tier auditability framework applies quantification learning to profile per-category reliability, 

---

### [188] Enhancing Event Candidate Acquisition for Event Linking

**链接**: https://arxiv.org/abs/2609.13670
**作者**: Ziyang Zhang, Yinan Liu, Boyi Xue, Yingxuan Huang, Bin Wang, Xiaochun Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Event linking associates event mentions in text with entries in a knowledge base (KB), or identifies them as out-of-KB events. Although existing methods use different architectures, candidate event acquisition can still be weakened by short ambiguous mentions, noisy arguments, and evidence that is unevenly useful for retrieval. We present MACE, a Multi-Agent Candidate Event acquisition method that refines event structure before linking. MACE uses evidence-specialized LLM agents to acquire time, location, participant, and event-type evidence, exposes intermediate queries to candidate-event lookup tools, and lets a coordinator revise the evidence set before final candidate construction. Experiments on two event linking benchmarks show that adding MACE to different event linking models consistently improves accuracy. These results show that MACE improves event linking through better candidate event acquisition without modifying the event linking model.

---

### [189] When Malicious Instructions Persist: Persistent Memory Poisoning Attack on Harness-Based Agents

**链接**: https://arxiv.org/abs/2609.13889
**作者**: Shuhuai Huang, Jingfeng Zhang, Hong Jia
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness design has transformed the development of LLM-based agents by integrating memory, tool use, and runtime control. However, this design also introduces security and privacy risks because malicious instructions from external sources may be written into persistent memory and persist across sessions. To study this risk, we propose PMPA, a Persistent Memory Poisoning Attack against harness-based agents. PMPA embeds malicious instructions into benign external sources and induces the victim agent to write them into persistent memory without directly accessing to the agent framework. Once stored, the poisoned memory can be retrieved in later sessions, triggering additional malicious actions and causing privacy leakage. We evaluate PMPA on OpenClaw and Claude Code across different backbone LLMs, input modalities, and trigger scenarios. Across all settings, PMPA achieves average Injection Success Rate (ISR) and Cross-session Attack Success Rate (C-ASR) of 73.7%/ 55.5% on OpenClaw and 66.9

---

### [190] Psychosis involves a deficit of information compression in connected speech

**链接**: https://arxiv.org/abs/2609.15522
**作者**: Samuele Vallisa, Claudio Palominos, Rui He, Emre Bora, Burcu Verim, Cemal Demirlek 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) with human-like performance on linguistic tasks have transformed the study of language in neurodiverse conditions. LLMs provide representations of linguistic input in the form of high-dimensional vectors (embeddings), and next-token predictions computed from these embeddings. Previous crosslinguistic evidence suggests a complexity reduction in the form of both lower intrinsic dimensionality (ID) of LLM representations and higher mean surprisal (prediction error) in psychosis. We hypothesized that these metrics reflect a general deficit of information compression in psychosis, linked to grammatical organization as what enables predictions in language.We operationalized surprisal difference as the difference between surprisal as estimated from word frequency and surprisal as based on a contextual LM, which is sensitive to grammatical organization over and above lexical concepts. Using a dataset of 144 Turkish speakers, including 106 patients with schizophreni

---

### [191] CoMem: Collective-Individual Memory Synergy for Evolutionary Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.15009
**作者**: Chengxin Yu, Zhaoxin Fan, Faguo Wu, Hongwei Zheng, Yun Zhou, Zhiyu Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing effective memory mechanisms is crucial for advancing LLM-driven Multi-Agent Systems (MAS), helping agents learn together and perform better over time. While recent work has led to strong cooperation skills, most methods still use flat, unstructured memories, which easily get filled with noise and erase differences between agents. To address this, we introduce the concept of collective-individual memory synergy and propose CoMem, an architecture that unifies both private experience and shared knowledge for multi-agent learning. CoMem features:(i) Private Experience Sedimentation, which lets each agent keep and update its own useful memories over time;(ii) Collective Wisdom Curation, which carefully selects only widely proven ideas to be shared among agents;(iii)Parallel Dual-Stream Retrieval, which allows agents to draw both from their own memory and the group's wisdom, using clustering to ensure diversity.Experiments on ALFWorld and PDDL benchmarks show that CoMem achieves st

---

### [192] Time Machine Experiments: Using Historically-Bounded AI for Inquiry into the Human Mind

**链接**: https://arxiv.org/abs/2609.15468
**作者**: Hiromu Yakura, Robin Schimmelpfennig, Ezequiel Lopez-Lopez, Alejandro H. Artiles, Levin Brinkmann, Jean-Fran\c{c}ois Bonnefon 等 (8 人)
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can interacting with someone from 1930, with no knowledge of what happened after, influence a person's perception of the past? People reason about the present against a picture of the past without observing it. The past is reconstructed from memory and testimony, but this reconstruction has been filtered through everything that happened since. Historically-bounded large language models (LLMs) make that past available for interaction. As a proof-of-concept for the impact of interacting with historical minds, we ran a preregistered randomized experiment ($N=240$), where participants interacted with an LLM trained on pre-1930 text. The interaction reduced the illusion of moral decline, the tendency to view the past as more moral than the present, compared to the contemporary-model control. This Time Machine Experiment paradigm informs new forms of interactive experiments, where temporal knowledge boundaries become experimental variables, and expands the realm of science fiction science, w

---

### [193] Circuit-MLLM: Topological Logic-Guided Latent-Space Visual Reasoning for Circuit Schematic Understanding

**链接**: https://arxiv.org/abs/2609.15668
**作者**: Jinyuan Deng, Yuqi Jiang, Wenjing Huang, Xin Li, Qi Sun, and Cheng Zhuo
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Through pre-training on extensive text and image datasets, current multi-modal large language models (MLLMs) achieve strong performance on general tasks. However, circuit schematics present a unique challenge for MLLMs due to their dense component layouts and distinct topological logic, demanding fine-grained structural parsing to extract the electrical semantics. To address this, we propose Circuit-MLLM, a multimodal reasoning framework that reformulates circuit topology analysis as a process of device localization, path tracing, and sequential reasoning within the latent space. We introduce a circuit knowledge mining mechanism that deeply aligns the model's latent representations with structurally rich features derived from multi-granularity circuit vision experts, enabling the model to effectively internalize topological semantics. Building upon these internalized semantics, we devise a topology-guided sequencing strategy that decouples reasoning from the rigid raster-scan order, en

---

### [194] AnnoSketch: Evaluating and Collecting Human Sketches for MLLM-assisted Chart Annotation

**链接**: https://arxiv.org/abs/2609.14289
**作者**: Yoonjae Oh, Seon Gyeom Kim, Jae Young Choi, Ryan Rossi, Jihyung Kil, Eunyee Koh 等 (7 人)
**来源**: cs.HC
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As multimodal large language models (MLLMs) support a growing range of input modalities, increasing work explores how to incorporate rough sketches to convey user intent. For annotated chart generation, it remains unclear what annotation sketches people provide and when such visual input helps MLLMs generate more useful annotations. In this study, we examine when sketch input is useful for MLLM-generated chart annotations across variation in chart type and caption type. In addition, we qualitatively analyze participants' explanations of their output preferences to characterize what made generated annotations more or less helpful. To further document participants' annotation sketches, we present AnnoSketch, comprising 1,600 annotation sketches collected across 160 chart-caption pairs from the conditions in which sketch guidance proved most beneficial, together with participants' annotation intents, perceived comprehension difficulty, and self-reported expressive limitations. We also lab

---

### [195] Evaluation of MLLM-Agnostic Plug-and-Play Keyframe Selection Methods for Long Video Understanding

**链接**: https://arxiv.org/abs/2609.13250
**作者**: Dilip Sarkar, Md. Safayet Islam, Liang Liang
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) cannot process every frame of a long video because of limitations in visual-token and computational budgets. Three primary approaches have been proposed to enhance their long-video understanding capabilities: (i) Retraining an MLLM on a large video corpus and/or extending its input length; (ii) Training an adapter for a specific MLLM that takes the entire video and the query as input and selects the most relevant video frames; and (iii) Developing a training-free, plug-and-play (PaP) adapter that is MLLM-agnostic. We refer to the third approach as PaP keyframe selection. A PaP method may use only candidate video frames without considering the query, or it may use both candidate video frames and the query. The first approach is prohibitively expensive. The second approach requires substantial training time and computational resources, but it is accessible to many because an adapter contains significantly fewer trainable parameters than an entire 

---

### [196] AdaVSkip: Adaptive Visual Token Skipping Across Layers For Efficient MLLMs Inference

**链接**: https://arxiv.org/abs/2609.15131
**作者**: Yuyao Sun, Tao Deng, Shuang Li, Deqing Wang
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) require substantial computation to process numerous visual tokens across all transformer layers. Most methods for efficient MLLM inference exploit horizontal redundancy by compressing visual tokens. Beyond token reduction, recent studies exploit vertical redundancy through early exit or fixed-layer skipping. However, we find that the extent and distribution of this redundancy vary across inputs and differ between self-attention and MLP modules. Motivated by these observations, we propose AdaVSkip, which equips each layer with two lightweight routers that independently determine whether visual tokens pass through by or skip the self-attention and MLP modules. These decisions collectively define an input-specific visual-computation path, but their discrete and non-differentiable nature makes learning effective paths challenging. To address this challenge, we develop a progressive two-stage training framework that updates only the routers while kee

---

### [197] From Density to Biopsy Decisions and Malignancy Prediction: A Benchmark Study of Multimodal Large Language Models Against Radiologists in Digital and Contrast-Enhanced Mammography

**链接**: https://arxiv.org/abs/2609.14676
**作者**: Ali Abbasian Ardakani, Afshin Mohammadi, Taha Yusuf Kuzan, Beyza Nur Kuzan, Alisa Mohebbi, Masume Behruzi 等 (10 人)
**来源**: cs.CV physics.med-ph
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: To compare four multimodal large language models (MLLMs) with radiologists of varying expertise in breast density assessment, BI-RADS assessment, biopsy candidacy determination, and continuous malignancy probability estimation using digital mammography (DM) and contrast-enhanced mammography (CEM). Methods: This study included 179 women with paired DM/CEM examinations and reference standards. Four MLLMs (ChatGPT-5.2, Gemini-3.1 Pro, Sonnet-4.6, Muse Spark) interpreted images with and without masks; three radiologists interpreted non-masked images. Results: For binary density classification on DM, radiologist accuracies ranged from 55.81% to 78.60%, exceeding most MLLM values (62.33%-71.63%), while masks added limited benefit. Five-category BI-RADS accuracies were higher for radiologists on DM (56.74-67.44%) and CEM (62.33-82.79%) compared with MLLMs (DM 31.16-45.12%; CEM 40.00-55.81%). Binary biopsy-candidacy accuracies were likewise higher for radiologists (DM 85.12-89.77%; CE

---

### [198] Adapting Open-Weight MLLMs to Generate Point Prompts for Electron Microscopy Segmentation

**链接**: https://arxiv.org/abs/2609.14080
**作者**: Samia Mohinta, Albert Cardona
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Promptable models such as microSAM segment electron microscopy (EM) images from point prompts, but automation requires generating prompts without user input. We ask whether open-weight multimodal large language models (MLLMs) can generate them from natural-language requests by returning coordinates to a frozen segmenter. To that end, we convert masks from three mitochondria datasets into training examples, pairing images and instructions with centroid coordinates, then train LoRA adapters while freezing the MLLM backbone and microSAM. We find that Qwen3-VL reaches segmentation AP$_{50}$ $0.736$ after supervised fine-tuning and reward optimization, up from $0.247$ without adaptation, while automatic prompt generation (APG) achieves $0.773$. In addition, two other MLLMs improve, reaching or exceeding APG. When compared with a supervised centroid-heatmap detector that reaches AP$_{50}$ $0.904$ for this mitochondria task, Qwen3-VL more closely matches the annotated point set and instance c

---

### [199] MedVA: An End-to-End Neuro-Symbolic Agentic System for Medical Volume Visualization

**链接**: https://arxiv.org/abs/2609.14874
**作者**: Haill An, Suhyeon Kim, Minjun Kang, Eunwoo Lee, Bin Sheng, Lei Bi 等 (7 人)
**来源**: cs.GR cs.CV cs.HC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical volume visualization requires selecting regions of interest (ROIs) and carefully controlling their relative visual emphasis according to a given clinical intent. Implementing these decisions in conventional workflows demands substantial clinical and visualization expertise and often involves trial-and-error optimization. Recent agentic systems have introduced natural-language interaction and autonomous visualization operations but largely rely on MLLM-based inference throughout the workflow. Although MLLMs encode broad medical knowledge and provide strong reasoning capabilities, such inference may be suboptimal for medical volume visualization, potentially leading to clinically incomplete interpretations of user requests and unreliable ROI identification and visualization optimization. In this work, we present MedVA, an end-to-end neuro-symbolic agentic system for medical volume visualization that addresses these limitations through three complementary agents. The neuro-symboli

---

### [200] ArtSociety: Multi-Agent Multimodal Collaboration for Art Emotion Understanding

**链接**: https://arxiv.org/abs/2609.13240
**作者**: Jian Li, Fanfan Ji, Jinxiang Lai, Ying Tai, Jian Yang, Xiao-Tong Yuan 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The AffectiveArt Multidimensional Art Emotion Understanding task asks to jointly predict an artwork's fine-grained emotion (12 classes, 1549:1 head-to-tail ratio), binary valence/arousal, and five attribute-grounded descriptions -- sub-tasks that exhibit strong empirical trade-offs, so the single-model solutions we tried do not jointly optimize all of them well. We present ArtSociety, a multi-agent framework that assembles heterogeneous multimodal experts -- a DINOv2-Giant vision agent (A1), a scene-grounded CoT fine-tuned MLLM (A2), and three closed-source reasoning agents (A3-A5) -- and coordinates them with two training-free controllers: (i) a rare-class-aware voting arbiter that lowers the agreement threshold for tail emotions, exploiting decorrelated error patterns across agent families; and (ii) a description-first reasoning agent whose DESCRIBE-then-CLASSIFY chain of thought forces visual evidence before label commitment, yielding near-perfect grounded descriptions. A task-routi

---

### [201] Concept-Grounded Reasoning with Prompt-Driven Localization for Interpretable Structured Report Generation

**链接**: https://arxiv.org/abs/2609.15334
**作者**: Xinyue Xu, Hongbin Lin, Juangui Xu, Hualiang Wang, Lehan Wang, Lijie Hu 等 (9 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical imaging modalities such as ultrasound and X-ray are widely used in clinical practice, where diagnosis follows a structured, evidence-driven workflow aligned with standardized criteria. While multimodal large language models (MLLMs) show promise for automated medical report generation, most existing systems rely on end-to-end multimodal fusion without modeling clinically defined intermediate attributes, leading to limited grounding and interpretability. To address this issue, we propose CORAL (COncept-grounded ReAsoning with Localization), a multimodal framework that integrates spatial grounding and concept-level supervision into a unified reasoning process. CORAL employs a prompt-driven medical segmentation model to localize lesions and predicts multi-class clinical attributes through a Concept Bottleneck module. The resulting textual concept tokens are combined with mask-modulated visual features within an MLLM to enable structured report generation and diagnostic prediction. 

---

### [202] EEG-Xplain: Decoding Neural Black-Boxes of EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.15687
**作者**: Hansong Ma, Junxiao Wang
**来源**: cs.AI
**匹配关键词**: EEG, Foundation Models, Neural Signal
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models such as BIOT, LaBraM, and EEGMamba have achieved remarkable performance in neural signal decoding, but their black-box nature limits clinical trust and neuroscientific validation. We propose a unified attribution framework for interpreting EEG foundation models across heterogeneous architectures. The framework integrates gradient-, perturbation-, and activation-based explanation methods to analyze model behavior in spatial, temporal, and frequency dimensions. Spatially, it identifies critical EEG channels and visualizes their distributions using topographic maps. Temporally, it highlights decision-relevant signal segments through attribution heatmaps. In the frequency domain, it quantifies the contributions of canonical EEG rhythms via spectral perturbation analysis. To assess explanation reliability, we introduce a population-level evaluation combining Area Over the Perturbation Curve (AOPC) and cross-method consistency analysis. The framework further leverages L

---

### [203] MANAS-2: Constrained Reconstruction for EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.13717
**作者**: Arvasu Kulkarni, Aditya Ray Mishra, Mahir Jain, Parshva Runwal, Lakshya Saini, Siddharth Panwar 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Masked reconstruction is widely used for EEG foundation models, but optimizing reconstruction on low-SNR waveforms does not necessarily produce the most useful latent representation. We introduce MANAS-2, a new EEG foundation model that combines a Raw-Band Hybrid (RBH) masked autoencoder with Constrained Reconstruction (ConRec), a physics-motivated regularizer. RBH jointly reconstructs temporal waveform patches and compact spectral-band targets, while ConRec acts only on the temporal decoder output, penalizing differences in RMS energy between adjacent short windows of the reconstructed waveform. ConRec is intended to shape the encoder by biasing it toward the organization of oscillatory-envelope information. Across seven held-out EEG datasets, adding ConRec to an otherwise identical RBH model increases frozen ridge recovery of six-band spectral power from mean R^2=0.860 to 0.906 and recovery of inter-patch band-energy dynamics from R^2=0.283 to 0.354, while temporal waveform informati

---

### [204] Mind2Cloud: EEG-to-Point Cloud Generation with Two-Granularity Diffusion Decoding

**链接**: https://arxiv.org/abs/2609.13991
**作者**: Yongyi Lu, Xiongfeng Huang, Zhijing Yang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing 3D objects from brain signals offers a promising avenue for understanding human visual cognition. While prior work has shown initial success using EEG signals for 3D reconstruction, existing methods typically employ a uniform diffusion decoder, overlooking the evolving semantic granularity of both EEG representations and the diffusion denoising process. In this paper, we propose Mind2Cloud, a novel EEG-to-point-cloud generation framework based on two-granularity diffusion decoding. The core of Mind2Cloud is a time-aware decoder that integrates a global Transformer branch and a local Point-Voxel CNN (PVCNN) branch across diffusion timesteps through a learnable fusion mask. Specifically, Transformer layers are incorporated into the early upsampling stages to capture global object structure under high uncertainty, while PVCNN modules are used in later stages to refine local geometric details. Inspired by the hierarchical nature of EEG-based visual representations, this desi

---

### [205] S-CEReBrO: Breaking the Memory Barrier in Continuous EEG Monitoring

**链接**: https://arxiv.org/abs/2607.27913
**作者**: Glenn Anta Bucagu, Thorir Mar Ingolfsson, Yawei Li, Luca Benini
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [206] Schizophrenia Detection from EEG Signals: A Transformer Framework with Spectrogram Representation

**链接**: https://arxiv.org/abs/2609.14015
**作者**: Abtin Shafiei, Mohsen Hooshmand, Majid Ramezani
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Schizophrenia is a serious psychiatric disorder that affects millions of people worldwide, and its diagnosis remains primarily dependent on clinical assessment. Electroencephalography (EEG) provides a non-invasive approach to investigate brain activity and has shown potential to support automated Schizophrenia detection. However, existing EEG-based classification studies often suffer from limitations including small datasets, inconsistent preprocessing strategies, and evaluation protocols that may not adequately prevent subject-related data leakage. In this study, we propose an EEG-based Schizophrenia classification framework that transforms preprocessed EEG recordings into time-frequency representations using the Short-Time Fourier Transform. The generated spectrogram images are classified using both conventional Machine Learning algorithms, including Support Vector Machines, Random Forests, and XGBoost, and Deep Learning models, including convolutional architectures and CNN-Transform

---

### [207] Checkpoint Selection and Evaluation in EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2607.27655
**作者**: Hanting Suo, Hongxun Wang, Yuwen Li
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [208] Conditional Quantum Flow Matching for Data-Scarce Physiological Signal Augmentation

**链接**: https://arxiv.org/abs/2609.14019
**作者**: Chi-Sheng Chen and Samuel Yen-Chi Chen
**来源**: quant-ph cs.LG cs.MM
**匹配关键词**: EEG, BCI
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative augmentation is a standard remedy for label scarcity in physiological signal classification, but existing quantum generative models start from uninformative noise, ignoring class structure that is already available. We propose Conditional Quantum Flow Matching (CQFM): a single 306-parameter circuit, conditioned on both flow time and class label, transports a compact class-conditional prior toward the target distribution. Quantum flow matching as published is unconditional, so this is to our knowledge the first conditional one, and the first EEG augmentation on a parameterized quantum circuit. A nonnegative spectral embedding removes the need for tomography at readout. On BCI Competition IV-2a, starting from a prior rather than noise is worth $+5.1$ accuracy points over QuDDPM (9/9 subjects), though at that operating point a class-conditional Gaussian matches CQFM. Where the prior fails the transport earns its keep: given one transferred from other subjects it regains $+7.2$ 

---

### [209] Valley3: Scaling Omni Foundation Models for E-commerce

**链接**: https://arxiv.org/abs/2605.01278
**作者**: Zeyu Chen, Guanghao Zhou, Min Yang, Qixiang Yin, Ziwang Zhao, Huanjin Yao 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [210] Parameter-Efficient Fine-Tuning of Foundation Models for Liver Tumor Segmentation in CT

**链接**: https://arxiv.org/abs/2609.14106
**作者**: Ramtin Mojtahedi, Mohammad Hamghalam, Jacob J. Peoples, Richard K. G. Do, Amber L. Simpson
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We evaluated parameter-efficient fine-tuning (PEFT) of the Segment Anything Model (SAM) for liver tumor segmentation in abdominal CT of colorectal liver metastases. We compared Low-Rank Adaptation (LoRA), 4-bit Quantized LoRA (QLoRA), a convolutional adapter (Conv-Adapter), and our Directional Spectral Top-K adapter (DiSCo), training only adapters while freezing the SAM backbone. DiSCo derives spectral bases from singular value decomposition of row-normalized weights and learns rank-gated spectral coefficients, per-output magnitude offsets, and a spectral gain, with optional Top-K rank selection at inference and 0.14 M trainable parameters. We benchmarked five prompting regimes: no prompt, single-point, multi-point, and bounding boxes at intersection over union 0.50 and 0.75. Conv-Adapter and LoRA achieved the highest accuracy (overall Dice 0.793 and 0.792; single-point Dice 0.795 and 0.792; 95th-percentile Hausdorff distance (HD95) 32 mm). QLoRA was close (overall Dice 0.766; single-p

---

### [211] CAL-MOS: Bridging Layers with Adapters for Robust MOS Prediction Across Speech Foundation Models

**链接**: https://arxiv.org/abs/2609.14956
**作者**: Alef Iury Siqueira Ferreira, Pedro Lustosa Rege Botelho, Fernanda Silva, Daniel Casanova, Rafael Faustino, Frederico Oliveira 等 (8 人)
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech Quality Assessment (SQA) is essential for modern speech technologies, and recent non-intrusive SQA predictors increasingly rely on Speech Foundation Models (SFMs). However, because SFMs expose representations from many layers, it remains unclear which depths are most informative for MOS prediction and how multi-layer information should be combined reliably across backbones and datasets. We benchmark ten SFMs on four MOS datasets under three regimes: full fine-tuning, last-layer probing with a frozen encoder, and naive cross-layer weighted aggregation. We find that the best layer is strongly backbone- and dataset-dependent, and that naive weighted fusion can be unstable across settings. We further evaluate a layer-calibrated aggregation variant that applies per-layer adapters before pooling, which improves the robustness of multi-layer fusion and narrows the gap to full fine-tuning while keeping the backbone frozen.

---

### [212] Towards Foundation Models for 3D Scene Understanding: Instance-Aware Self-Supervised Learning for Point Clouds

**链接**: https://arxiv.org/abs/2603.25165
**作者**: Bin Yang, Mohamed Abdelsamad, Miao Zhang, Alexandru Paul Condurache
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [213] Tabby: An Open Pretraining Recipe for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.13956
**作者**: Shifeng Xie, Bahaeddine Abdessalem, Zehao Xiao, Youssef Attia El Hili, Ambroise Odonnat, Zhiwei Dong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this report, we release Tabby, a long context probabilistic time series foundation model, together with a complete and open recipe of how it was built. Tabby adopts an encoder-only patch Transformer architecture and concentrates the contributions on the data and the training procedure. The pretraining corpus combines an extended real-world collection, GIFT-Eval-Pretrain+ and BLAST, with synthetic data from KernelSynth and CauKerV2, an online generator that composes temporal dynamics through randomly sampled structural causal models. Training couples a progressive convergence schedule, which yields reusable intermediate checkpoints, with a deep quantile supervision objective for intermediate layers. The resulting 145M parameter backbone supports contexts of up to 8,192 observations and serves forecasting, classification, and anomaly detection, while a prompt-tuning module further improves in-distribution forecasting performance with the pretrained weights frozen. Tabby achieves compe

---

### [214] Distillation of Synthetic Data for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.09586
**作者**: Niloy Biswas, Noureddine El Karoui
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [215] Discovery Foundation Models: Toward Open-Ended Discovery Intelligence

**链接**: https://arxiv.org/abs/2609.15973
**作者**: Ling Yang, Zhenfei Yin, Yingcheng Wu
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models have progressed from learning and reasoning over existing knowledge, to increasingly learning through action, tool use, and outcome feedback. We argue that the next frontier is a further transition: from solving and acting within problems specified by humans to participating in the process by which new problems, representations, explanations, and knowledge are created. We refer to this capability as Discovery Intelligence. We formulate Discovery Foundation Models (DFMs) as general-purpose model systems for open-ended discovery. A DFM operates over a revisable research state and supports seven coupled capabilities spanning problem discovery, formulation, representation construction, hypothesis formation, intervention, evidence-grounded revision, and continual discovery improvement. We instantiate this framework with Zetema, which couples explicit research-state dynamics, verification and experimental gating, external grounding, and cross-task Discovery Skill evolution.

---

### [216] Physically Typed and Geometry-Aware Representations for Earth Foundation Models

**链接**: https://arxiv.org/abs/2609.13868
**作者**: Rajiv Ranjan
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth-observation (EO) foundation models have become exceptionally effective at learning se mantic, high-dimensional geospatial embeddings, while modern weather and climate models have demonstrated that Earth-specific geometry, spherical operators, meshes, and hybrid physical solvers can materially improve prediction. Yet these two advances are not equivalent. A conventional latent embedding has no inherent physical transformation law, whereas scalar fields, tangent polar-vector fields, axial/pseudovector quantities, covectors, and higher-order tensors transform differently under rotations, reflections, and changes of local coordinate frame. This proposal asks whether a general purpose Earth foundation model should preserve those distinctions explicitly, or whether standard embeddings plus augmentation already learn everything that matters. The central contribution is therefore not a more complicated architecture by assumption, but a staged falsification program. A compute-conscious ER

---

### [217] Do Tabular Foundation Models Still Need Feature Engineering?

**链接**: https://arxiv.org/abs/2609.13202
**作者**: Yifan WU, Pinjun Dong, Jiran Tao, Binyan Jiang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feature engineering has long been a cornerstone of tabular machine learning. Tabular foundation models (TFMs) are pretrained on a wide range of tabular datasets and applied via in-context learning. Their rise raises a natural question: does manual feature construction still matter as these models become more capable? To answer this, we perform a controlled study across several versions of two major TFM families, testing a wide range of existing feature engineering techniques on benchmark datasets from TabArena. We find a consistent pattern: feature engineering gains are concentrated in earlier model generations and become negligible for the strongest models. These results suggest that stronger TFMs depend less on explicitly engineered input representations. In a complementary experiment, however, adding in-context information from related datasets still improves performance. Our findings indicate a shift in the source of performance gains for stronger TFMs: re-representing existing inp

---

### [218] How Do Video Foundation Models Encode Intuitive Physics? Probing Across Pretraining Paradigms

**链接**: https://arxiv.org/abs/2606.09646
**作者**: Samuele Punzo and Niccol\`o Caselli and Ippokratis Pantelidis and Francesco Massafra and Salvatore Lo Sardo and Mohammadreza Salehi
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [219] Adaptation Interfaces for In-Context Tabular Foundation Models in Time-to-Event Prediction

**链接**: https://arxiv.org/abs/2609.04901
**作者**: Minh-Khoi Pham, Luca Cotugno, Dan Cernei, Alina Sirbu, Stefano Masi, Giuseppe Prencipe 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [220] PhysBrain 1.5: From Vision-Language Models to Physical Foundation Models

**链接**: https://arxiv.org/abs/2609.14973
**作者**: DeepCybo Team, Yu Bin, Haipeng Cao, Zheng Chang, Kai Chen, Youning Chen 等 (10 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present PhysBrain 1.5, a unified model for understanding physical environments, generating actions, and predicting future states. Motivated by the physical loop of observation, interaction, and environmental change, we bring these capabilities into a common learning framework. Starting from a general vision--language model, we encode language responses, end-effector motion, and dense visual targets as discrete sequences and jointly optimize them with autoregressive next-token prediction. Pre-training draws its embodied supervision entirely from human interaction videos, using task-centered episodes to pair semantic and spatial context with recovered motion and subsequent observations. We then adapt the model through supervised fine-tuning on a mixture of human demonstrations, robot trajectories, and simulated experience. Across 28 embodied understanding benchmarks, our 8B model achieves an average score of 72.5, setting a new open-source state of the art and performing on par with l

---

### [221] Adaptive 3D-RoPE: Physics-Aligned Rotary Positional Encoding for Wireless Foundation Models

**链接**: https://arxiv.org/abs/2605.00968
**作者**: Chenyu Zhang, Xinchen Lyu, Chenshan Ren, Yanzhao Hou, Xuefei Zhang, Shuhan Liu 等 (7 人)
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [222] Multimodal Foundation Models Adaptation based on Domain-Aware Relaxed Orthogonal Subspace for Remote Sensing

**链接**: https://arxiv.org/abs/2609.13654
**作者**: Han Luo, Ruoyu Yang, Yinhe Liu, Yanfei Zhong
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained foundation models (FMs) have achieved remarkable success in computer vision, yet their high fine-tuning cost limits practical deployment. Parameter-efficient fine-tuning (PEFT) methods such as Low-Rank Adaptation (LoRA) improve efficiency by constraining updates to a predefined low-rank subspace. However, when applied to remote sensing tasks with substantial domain shifts, the fixed subspace is constructed without observing the downstream activation distribution and can therefore provide a poor coordinate system for adaptation, a phenomenon herein termed subspace mismatch. To address this issue, a unified framework is introduced, termed Domain-aware Relaxed Orthogonal Subspace adaptation (DROS), which reformulates low-rank adaptation as data-conditioned subspace learning and flexible subspace adaptation. Specifically, the weight decomposition is conditioned on second-order activation statistics estimated from the downstream training distribution, so that the initialization r

---

### [223] Hallucination in Multimodal Foundation Models: A Survey on Causes, Corrections, and Evaluations

**链接**: https://arxiv.org/abs/2410.15359
**作者**: Yinghao Guo, Wei Lan, Wenyi Chen, Qingfeng Chen, Shichao Zhang, Shirui Pan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [224] Decision-Oriented Uncertainty Quantification for Risk Control in Earth System Spatiotemporal Foundation Models

**链接**: https://arxiv.org/abs/2609.14821
**作者**: Ji Lu, Huiran Duan, Bo Zhao, Xianglong Wang, Yiru Fang, Kuo Yang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth system modeling is shifting from task-specific predictors toward foundation models with general spatiotemporal representation capabilities. Although these models can jointly encode dynamic Earth fields, external forcings, and static geographic context for multistep forecasting, accurate point predictions or statistically calibrated intervals alone are insufficient for high-impact applications such as extremeweather warning, flood control, renewable-energy dispatch, and emergency resource allocation. What matters in practice is whether predictive uncertainty can be translated into reliable decision risk under specific actions, loss functions, and risk preferences. We propose a decision-oriented uncertainty quantification framework for Earth system spatiotemporal foundation models. The framework produces predictive distributions of future states and uses a decision risk adapter to map forecast samples, decision context, and utility functions into action-conditional risks. A utility

---

### [225] UniE2F: A Unified Diffusion Framework for Event-to-Frame Reconstruction with Video Foundation Models

**链接**: https://arxiv.org/abs/2602.19202
**作者**: Gang Xu and Zhiyu Zhu and Junhui Hou
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [226] EdgeHAR: An Edge-Native Compact Sensor Foundation Model for Human Activity Recognition

**链接**: https://arxiv.org/abs/2609.14498
**作者**: He Zhang, Siyu Yuan, Siyu Liu, Sizhen Bian, Bin Guo
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sensor-based human activity recognition (HAR) is fundamental to ubiquitous and wearable computing, yet existing foundation models are largely designed for cloud-scale deployment and struggle with real-world sensing shifts, including unseen users, devices, sampling rates, and sensor placements. We present \textbf{EdgeHAR}, an edge-native compact sensor foundation model designed for wearable intelligence. Unlike conventional models that entangle activity knowledge with acquisition variations, EdgeHAR learns transferable representations by factorizing sensor signals into three latent codes: an \textbf{(i)Activity-Semantic Code} capturing reusable activity knowledge, a \textbf{(ii)Motion-Dynamics Code} modeling temporal patterns, and an \textbf{(iii)Acquisition-Context Code} representing sensor-specific variations. This disentangled design enables efficient adaptation to new users, devices, placements, and activity classes with limited target-domain data. By incorporating lightweight adapt

---

### [227] Towards a knowledge-enhanced single-cell foundation model

**链接**: https://arxiv.org/abs/2609.14970
**作者**: Hanqing Zhang, Jie Bao, Mei Ma, Shuai Liu, Jiaying Ma, Jiaguan Liu 等 (10 人)
**来源**: cs.AI q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-cell foundation models (scFMs) increasingly rely on large-scale transcriptomic pretraining, yet expanding pretraining data can yield diminishing gains while substantially increasing computational cost. Our data scaling analyses showed that incorporating biological knowledge, including cell-level text annotation and gene-level regulatory information, provided additional scaling dimension than simply increasing data size. Motivated by this observation, we present scKITE, a simple yet effective scFM that integrates cell-annotation and gene-regulatory supervision into a shared transcriptomic Transformer encoder through lightweight auxiliary decoders. These decoders are used only during pretraining and subsequently discarded, yielding a general-purpose encoder enriched with biological knowledge for downstream applications. With only 179,067 pretraining samples, i.e., less than 0.5\% of those used by previous strong scFMs, scKITE outperformed these models across diverse downstream tas

---

### [228] Beyond Point Forecasts: A Survey on Probabilistic Forecasting for Time Series and Spatiotemporal Data

**链接**: https://arxiv.org/abs/2609.13345
**作者**: Donia Besher, Rajdeep Pathak, Madhurima Panja, Tanujit Chakraborty
**来源**: stat.ML cs.LG econ.EM stat.AP
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Probabilistic forecasting is central to decision-making under uncertainty, yet its methodological landscape has become increasingly fragmented across temporal and spatiotemporal forecasting, statistical modeling, machine learning, and deep generative modeling. This survey develops a unified perspective by organizing probabilistic forecasting methods according to where and how uncertainty is introduced into the forecasting pipeline. Our taxonomy connects model-agnostic approaches including ensembles and distribution-free calibration, with model-intrinsic approaches spanning Bayesian modeling, parametric predictive distributions, distributional regression, and modern generative models, and further examines the emerging role of time series foundation models. Beyond methodological synthesis, we identify the assumptions, computational demands, and forms of uncertainty represented by different paradigms, and translate these distinctions into data-driven and domain-specific guidance for metho

---

### [229] SURE-Map: Self-Correcting Streaming Geometric Foundation Model

**链接**: https://arxiv.org/abs/2609.15795
**作者**: Mingkai Liu, Hao Zhao, Xingxing Zuo
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Streaming geometric foundation models are emerging as a compelling alternative to SLAM systems. Yet this streaming nature introduces a fundamental issue: each prediction is made from limited context, which is vulnerable to dynamic objects and weak textures. Small local errors accumulate into severe geometric distortion and long-horizon scale drift. We argue that reliable streaming reconstruction requires geometric foundation models to be not only predictive, but also self-correcting. We introduce SURE-Map, a self-correcting framework built upon two complementary principles. First, we explicitly model cross-view geometric uncertainty. Unlike conventional depth or point confidence, which primarily reflects the reliability of individual-view prediction, our uncertainty directly measures whether the jointly predicted pose and depth induce geometrically consistent cross-view pixel correspondences. Second, because local correction alone cannot eliminate slowly accumulating scale errors, we i

---

### [230] Trustworthy Agentic AI: A Comprehensive Cybersecurity and Systems Survey on Threat Landscapes, Defense Architectures, and Open Challenges

**链接**: https://arxiv.org/abs/2609.13731
**作者**: Seyedakbar Mostafavi
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The transition from passive foundation models to autonomous, goal-directed agentic AI systems has introduced unprecedented capabilities by coupling recursive cognitive reasoning loops, persistent memory architectures, live tool execution planes, and multi-agent collaboration topologies. However, granting probabilistic neural cores execution authority across filesystems, networks, and cloud infrastructure dissolves classical security perimeters: natural language simultaneously serves as input data, internal control code, and communication protocols, exposing a Turing-complete blast radius where untrusted data represents executable instructions. This survey delivers a comprehensive systems-security reference framework for trustworthy agentic AI, synthesizing 206 foundational studies and regulatory standards. We formalize the general agent architecture as a stateful 5-tuple and establish a 6-dimensional trustworthiness taxonomy covering security, safety, privacy, explainability, fairness,

---

### [231] Benchmarking Intra-Patient 3D Deformable Multimodal Image Registration

**链接**: https://arxiv.org/abs/2609.15669
**作者**: Matteo Barbieri and Giammarco La Barbera and Juan Pablo De La Plata and Sabine Sarnacki and Isabelle Bloch and Pietro Gori
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal image registration is a key component of many clinical workflows, yet it remains challenging because corresponding anatomical structures often exhibit substantially different image intensities across modalities. In this work, we present a comprehensive benchmark of intra-patient 3D multimodal deformable registration methods across three datasets covering different anatomical regions and difficulty levels, including both synthetic deformation recovery and real clinical scenarios. We evaluate classical optimization-based approaches and modern learning-based methods, including recent deep learning and foundation models, using complementary metrics: Average Dice similarity coefficient (DSC), average 95th-percentile Hausdorff distance (HD95), and a modality-independent structural similarity measure based on the MIND self-similarity context (MIND-SSC). Results show high variability across datasets, with learning-based methods demonstrating superior performance on large synthetic b

---

### [232] Accuracy Is Not Service: A Decision-Aware Benchmark for Intermittent-Demand Forecasting

**链接**: https://arxiv.org/abs/2609.13840
**作者**: Joo Ern Chin, Shih-Fen Cheng, Aldy Gunawan
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A contract-logistics spare-parts operator is paid on order-level service: an order counts only if every requested line is fulfilled, yet forecasters are selected based on line-level forecast accuracy. This disconnect matters when demand is intermittent and lumpy, histories are short, and lead times span months. We benchmarked 38 forecasting methods spanning classical, intermittent-demand, machine-learning, deep-learning, and pretrained foundation models. A common decision-aware protocol evaluates them on an industrial panel drawn from a live contract and two public datasets. Forecast-accuracy rank and order-service rank are negatively correlated on the industrial panel, at -0.555, across methods evaluated on 20,330 real multi-item orders. Service is more closely associated with the direction of cumulative forecast bias, including over-prediction during zero-demand periods, than with point accuracy. Examining bias in Chronos-2's instance normalization yields a training-free correction t

---

### [233] Understanding the Design Taxonomy of AI-Mediated Interpersonal Communication Experiences in HCI: A Scoping Analysis

**链接**: https://arxiv.org/abs/2609.14639
**作者**: Chen Chen and Lingyao Li and Renkai Ma and Rawan Alghofaili and Shaoze Zhou and Bojun Zhang and Xian Su and Weidong Zhu and Christine Lisetti and Mo Sha
**来源**: cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpersonal communication is a fundamental aspect of everyday life, shaping interactions across workplaces, education, entertainment, healthcare, and beyond. While computer-mediated communication has been extensively studied, a comprehensive understanding of AI-Mediated Interpersonal Communication (AIMIC) remains lacking. An in-depth scoping analysis is urgently needed to understand the research landscape of AIMIC in HCI, particularly following the recent growth of large foundation models, and AI agent research. We conducted a scoping analysis to understand AIMIC by performing an in-depth review of prior HCI literature published over the past decade (January, 2016 - May, 2026). Grounded in the Preferred Reporting Items for Systematic reviews and Meta-Analyses (PRISMA) approach, we curated 52 full-paper publications from the HCI literature spanning a range of interpersonal communication contexts. We analyzed this corpus by examining the types of AIMIC studied, AI integration approache

---

### [234] FlowTSFM: Turning Encoder Depth into Quantile Transport

**链接**: https://arxiv.org/abs/2609.13640
**作者**: Bahaeddine Abdessalem, Shifeng Xie, Zehao Xiao, Youssef Attia El Hili, Ambroise Odonnat, Jianfeng Zhang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Encoder-based time series foundation models (TSFMs) typically rely on deep stacks of independently parameterized Transformer layers, where only the final forecast is supervised and intermediate representations have no explicit predictive role. We introduce FlowTSFM, an encoder architecture that interprets depth as a recurrent transport process: a single Transformer block is iteratively applied with shared parameters, while a quantile-flow objective supervises intermediate states along a prescribed trajectory from a prior distribution toward the final forecast. The objective combines pinball forecasting loss with path-level position matching. With only 38.8M parameters, FlowTSFM achieves competitive performance on GIFT-Eval and TIME, remaining within 1.8-4.6% MASE of stronger baselines while using approximately $3\times$ fewer parameters than a 12-layer Chronos-2 model (119.5M). Beyond accuracy, we introduce CosMean, a scale-free diagnostic measuring whether recurrent updates consistent

---

### [235] A Language-Guided Multimodal Foundation Model for Zero-Shot and Multi-Task Brain Signal Analysis

**链接**: https://arxiv.org/abs/2609.15740
**作者**: Mingzhi Chen, Yiyu Gui, Guibo Luo, Yuchao Yang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain signal analysis is essential for both neuroscience research and clinical diagnostics, yet current approaches face critical limitations. End-to-end models require task-specific retraining and exhibit limited generalization, while pre-trained models lack semantic depth and still depend on extensive fine-tuning. Meanwhile, general-purpose multimodal foundation models, though powerful in other domains, struggle to interpret brain signals due to representational misalignment and lack of domain knowledge. This study introduces a multimodal foundation model for zero-shot and multi-task brain signal analysis (METIS) through a unified language-signal alignment framework. METIS is pretrained on the largest and most diverse brain-signal corpus to date, comprising over 70,000 h of recordings from more than 11,000 subjects across 20 datasets. In a comprehensive zero-shot evaluation across 12 datasets, METIS outperformed the leading generalist model by over 20.9% in average accuracy. Remarkabl

---
