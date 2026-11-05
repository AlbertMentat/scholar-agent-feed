# 📑 论文索引 - 2026-11-06

共 165 篇论文

---

### [1] SecureGARD: Dynamic Ontology-Guided Governance for Secure Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2611.06682
**作者**: Guoqin Xiong, Shengtao Wen, Xiang Chen, Xinyi Zeng, Zhaoxin Fan, Wei Ye 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language model (LLM) agents translate model outputs into consequential actions, turning indirect prompt injection into an execution-security problem. Existing defenses constrain tool calls, trajectories, or information flows, but often leave action semantics, state dependencies, and evidence relations implicit, limiting generalization across heterogeneous tools and complicating safe updates. We present \ours{}, a dynamic ontology-guided governance framework. \ours{} grounds heterogeneous calls in a shared semantic representation and combines an executable ontology with episode-level task state to derive deterministic ready, waiting, and forbidden decisions. A waiting decision identifies an unmet but recoverable obligation, enabling bounded replanning without expanding the agent's authorization boundary. \ours{} evolves its ontology offline from verified training executions. An offline LLM proposes instance-independent action--state axioms, which are accepted only if th

---

### [2] A Feasibility Condition for Confidence-Gated Tiered LLM Inference

**链接**: https://arxiv.org/abs/2611.05394
**作者**: Sumit P. Ahuja
**来源**: cs.AI cs.DC cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tiered inference distributes large language model computation across a hierarchy of devices, from on-device and edge hardware to the datacenter, and is increasingly offered as the route to cheaper, lower-latency, and more private serving. Most such systems orchestrate frozen model checkpoints, and most decide what to resolve locally and what to escalate using a confidence signal produced by a forward-deployed model. We give a closed-form condition for when no threshold on that signal makes a tiered cascade worthwhile relative to sending every query to the backstop. Modeling the routing decision as a binary test and separating local from escalation cost through an architecture cost ratio $\kappa$, we derive a feasibility condition bracketed by a signal-free floor, below which a cascade is feasible at any signal quality, and a perfect-signal ceiling, above which none is. Read along the $\kappa$ axis the condition inverts: where local compute is billed, cost binds, matching a recent empir

---

### [3] Where to Connect? Boosting MLLMs via Dynamic Gated Pathways across ALL ViT and LLM Layers

**链接**: https://arxiv.org/abs/2611.06844
**作者**: Yingying Yan, Jiaqi Tang, Wei Wei, Qianzhou Wang, Lei Zhang, Jianmin Chen 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A central yet under-explored question in Multimodal Large Language Models (MLLMs) is where to connect---how visual information from a hierarchical vision encoder should be wired into the layer-wise semantics of a large language model. Mainstream MLLMs inject a fixed single-layer visual representation into the LLM and treat all LLM layers as a single consumer, ignoring that different layers demand different visual granularities. Recent multi-layer fusion methods either compress hierarchical features on the encoder side or rely on predefined sparse or hierarchical layer-to-layer connections, and therefore stop short of modeling adaptive cross-layer interactions between the ViT and LLM hierarchies. We address this gap with DGP (Dynamic Gated Pathways), a routing mechanism that establishes all-to-all connections between every ViT layer and every LLM layer, with each LLM layer dynamically gating its preference over visual layers conditioned on its own semantic state. Built on top of LLaVA-1

---

### [4] FlyHash for LLM Agent Memory: An Empirical Validation and a New Application

**链接**: https://arxiv.org/abs/2611.05791
**作者**: Mohan Bheemadolu, Chrisogonas O. Odhiambo
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on external memory stores to retain information across conversations, typically via dense vector embeddings searched with approximate nearest-neighbor methods. The fruit fly's olfactory circuit computes a locality-sensitive hash of sensory input using a strikingly different mechanism - sparse random projection followed by winner-take-all competition - and prior work (Dasgupta et al., 2017) showed this scheme, dubbed FlyHash, preserves neighbor structure better per bit than conventional random-hyperplane hashing (SimHash) on several benchmarks. We apply FlyHash, to our knowledge for the first time, to LLM agent memory retrieval, and ask three questions a practitioner actually needs answered: does the quality advantage hold under a correctly matched-bit protocol (it does, robustly, across 10 seeds and four datasets spanning two modalities, with one specific, previously undocumented comparison pitfall identified and corrected along the w

---

### [5] On Turn-Level Best-of-N Sampling for Scaling LLM Agents

**链接**: https://arxiv.org/abs/2611.06868
**作者**: Jalaj Bhandari, Dhawal Gupta, Hongli Zhan, Zhenting Wang, Varad Pimpalkhute, Zhengzhong Liu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we evaluate a simple inference-time scaling approach based on \textit{turn-level best-of-N sampling} (\method) for large language model (LLM) agents on complex, long-horizon tasks. We instantiate this using a \textit{generator-selector} framework with two LLMs; at each turn, a \emph{generator} model generates $N$ candidate actions and a \emph{selector} model selects one of them, which is then executed in the environment. This paper is closely related to the work of \cite{zainullina2025guided} who used critic models for guided search at inference time. Different from their work, we evaluate if off-the-shelf, open-weight LLMs can be effective at comparing different candidate actions directly. Experiments on long-horizon terminal tasks show that \method can lead to significant performance improvements, both in terms of accuracy (5--10\%) and consistency across repeated attempts. Analysis of agent trajectories reveal a shift in agent behaviour towards desirable patterns such 

---

### [6] Graph-Mediated Large Language Model Systems in the Agentic Era: Reasoning, Knowledge, Retrieval, Execution, and Coordination

**链接**: https://arxiv.org/abs/2611.05953
**作者**: Haihui Liu, Yang Chen, Zice Qiu, Yun Zhang, Jialun Zhong, Wenhua Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graphs play an increasingly important role in large language model (LLM) systems, supporting structural reasoning, knowledge grounding, retrieval, and memory. As these systems evolve toward the agentic era, graphs also organize execution dependencies and multi-agent communication, linking intermediate observations and retained information to subsequent decisions. However, understanding their contribution requires distinguishing the function of each graph operation, the component responsible for its computation, and the subsequent use of its output. This survey introduces an operation-level role--locus taxonomy for reasoning, knowledge and evidence, retrieval and memory, execution, and coordination. We compare how graph observations and external computations guide decisions, how memory representations and updates support later tasks, and how dependencies constrain execution and information delivery. These comparisons distinguish improvements in local metrics from downstream task perform

---

### [7] ServerBench: How can your coding agents design specialized LLM serving systems?

**链接**: https://arxiv.org/abs/2611.06841
**作者**: Xinrui Zhong, Zhiming Wang, Yongqi Liu, Zhaohui Wang, Shanglin Yang, Zikun Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) coding agents develop software through experimentation, offering an opportunity to design the serving systems supporting their own operation. Effective serving requires coordinating implementation and operating decisions under session dependencies, latency constraints, and correctness requirements. We introduce ServerBench, a benchmark for agentic design of complete, specialized LLM serving systems. Agents experiment against a common objective, dollars per dollar: latency-qualified token value per dollar of GPU cost. Stateful replay preserves session dependencies, and independent verification checks the submitted system. Across 11 coding-agent models and three deployments, Claude Sonnet 5.5 achieves 2.97 dollars per dollar on Gemma E4B, $4.87\times$ the vLLM reference; 22 of 33 runs yield verified systems, and 13 exceed the strongest baseline. Our analysis identifies three findings: high-value designs coordinate capacity improvements with load selection; agen

---

### [8] A.S.E 2.0: Understanding How Repository Context Impacts the Security of LLM-Generated Code

**链接**: https://arxiv.org/abs/2611.06294
**作者**: Jiongchi Yu and Keke Lian and Junqing Wang and Zhikang Fan and Zhaoxuan Li and Yongheng Huang and Ziming Zhao and Dong Zhang
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) coding assistants and agents construct a repository context before generating code. For security-sensitive code, this context decides whether the model sees the project's safeguards (e.g., authorization checks) or insecure code to imitate. However, context construction is designed almost exclusively for functional correctness, and secure-code benchmarks treat the context as fixed, so how repository context affects the security of generated code remains unclear. We construct CASE-Bench, a benchmark of 145 repository-level tasks from real CVEs in 51 projects. Each task runs in Docker, has functional tests and a proof-of-concept exploit validated in both directions, and is annotated with the repository code that enforces or undermines its security. Using CASE-Bench, we compare 13 context construction methods and six controls with six LLMs, edit single context elements, and analyze coding-agent trajectories. We find that (1) functionality-oriented context raises 

---

### [9] HarnessFlow: MCTS-Guided Harness Optimization for LLM Agents

**链接**: https://arxiv.org/abs/2611.06254
**作者**: Zhi Hong, Qianlong Wang, Hongchen Wei, Aidan Wu, Daohong Ying, Mingze Kong 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of large language model (LLM) agents depends on both the underlying model and the harness that governs interaction with tools and the environment. Yet harness design remains largely manual, and automating it requires navigating an open-ended search space through costly end-to-end evaluations. We introduce HarnessFlow, a framework for optimizing complete executable harnesses under a limited candidate-evaluation budget, with the model and task environment held fixed. HarnessFlow organizes candidates and their evaluation histories in a refinement tree, using a Monte Carlo Tree Search (MCTS)-based policy to balance exploitation and exploration. A coding agent refines selected harnesses using archived code, execution feedback, and a library of reusable harness mechanisms. With 15 refinement attempts per benchmark, HarnessFlow achieves the highest mean test scores among the compared methods on six benchmarks spanning agentic tasks, coding, and web interaction. The optimized h

---

### [10] TSFM Meets LLM: Context as Covariates

**链接**: https://arxiv.org/abs/2611.05515
**作者**: Hemanth Ram, Sai Shankar Narasimhan, Shubhankar Agarwal, Sandeep Chinchali
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Textual information is ubiquitous in real-world time series datasets, appearing as news, reports, and annotations that hold key predictive signals not deducible from numerical history alone. Large Language Models (LLMs) interpret text but lack numerical precision, while Time Series Foundation Models (TSFMs) are quantitatively accurate but cannot reason about the effects of text. Moreover, the lack of large-scale paired multimodal datasets limits progress in bridging this gap. In this work, we address this challenge by providing a scalable approach for generating realistic multimodal datasets by annotating real-world time series with LLMs. Building on this, we propose Context as Covariates (CoCo), a forecasting framework in which an LLM distills its textual reasoning into numerically grounded forecast and confidence covariates that guide a TSFM backbone, thereby exploiting the strengths of both LLMs and TSFMs. We align the two models in stages, first fine-tuning the LLM via Group Relati

---

### [11] Decoupling Knowledge and Privacy: Post-Task Self-Distillation Replay for LLM Continual Learning

**链接**: https://arxiv.org/abs/2609.29711
**作者**: Shengtao Wen, Yunying Yang, Xiang Chen, Lingbing Guo, Yu Tian, and Sheng-Jun Huang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] 3D-PLOT-LLM: Part-Level Object Tokens for 3D Large Language Models

**链接**: https://arxiv.org/abs/2606.19828
**作者**: Jintang Xue, Xinyu Wang, Yixing Wu, Jingwen Chen, C.-C. Jay Kuo
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [13] LLM Fine-Tuning Workloads: Characterization, Challenges, and Opportunities for Serverless AI

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.40983&hl=zh-CN&sa=X&d=5708562440685666514&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv4EMWsXy3DYMVEKEd079Mnf&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=0&folt=kw-top
**作者**: R Nicolae, D Lotito, A Iosup - arXiv preprint arXiv:2610.40983, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Serverless operation of LLM fine-tuning workloads shifts operational … how LLM fine-tuning workloads run in practice. In this work, we address the knowledge gap by characterizing the execution of LLM fine-tuning workloads on clusters equipped with

---

### [14] SpanUQ: Span-Level Uncertainty Quantification for Large Language Model Generation

**链接**: https://arxiv.org/abs/2607.05721
**作者**: Yimeng Zhang, Yingying Zhuang, Ziyi Wang, Yuxuan Lu, Pei Chen, Aman Gupta 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] Chiron: Cache Management Empowered by LLM Intelligence for AI Workloads

**链接**: https://arxiv.org/abs/2611.06179
**作者**: Bohan Zhang, Renshu Ge, Tianze Wang, Chen Chen
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI clusters keep data in remote object stores and rely on local caches to stop GPUs from waiting for data. A cache performs well only when its prefetching and eviction policies match the access pattern, yet these patterns differ across AI workloads and change between phases of one workflow. Existing methods either need code changes, which compromises user transparency, or use low-end heuristics, which cannot follow such changes. Large language models (LLMs) can infer access behavior without user hints, but direct LLM control of cache actions suffers from long reasoning delay, high token cost, and poor decision quality. We present Chiron, a cache system based on advisory switching control. An LLM asynchronously diagnoses the access pattern and recommends a policy. A deterministic harness gates this advice, executes expert-designed policies locally, and returns cache feedback for review. We implement Chiron atop JuiceFS and evaluate it on nine AI workloads. It reduces job completion time

---

### [16] A prototype-based LLM -assisted framework for life-cycle carbon emissions assessment of residential buildings

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0378778826014969&hl=zh-CN&sa=X&d=10775418246905491619&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv7aC7w1_yxDo7KeO5eMe5Lu&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=1&folt=kw-top
**作者**: S Jiang, Y Qiao, S Shen, Y Ye, H Wu, Y Li 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> As the focus of reducing carbon emissions in the building sector expands from the operational stage to the entire life cycle, there is an urgent need for a low-barrier method for the assessment of life-cycle carbon emissions (LCCE) in residential

---

### [17] Reliability without Validity: A Systematic, Large-Scale Evaluation of LLM-as-a-Judge Models Across Agreement, Consistency, and Bias

**链接**: https://arxiv.org/abs/2606.19544
**作者**: Justin D. Norman, Michael U. Rivera, D. Alex Hughes
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] What Does Multi-Turn Reinforcement Learning Really Improve in LLM Agents?

**链接**: https://arxiv.org/abs/2611.06483
**作者**: Kejian Zhu, Zhuoran Jin, Shangqing Tu, Tianyi Men, Yupu Hao, Jiachun Li 等 (8 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multi-turn agentic reinforcement learning (RL) excels on long-horizon tasks, its performance gains remain highly sensitive to interaction constraints. Evaluating across sampling breadth $K$ and interaction depth $T$ via $Pass@(K,T)$, we show that trajectory-level RL advantages depend on sufficient turn budgets, diminishing significantly when budgets tighten. Besides, agentic RL does not uniformly elevate single-step decision quality; rather, its strength concentrates in error recovery and long-horizon resilience. To mitigate the deployment risks caused by this budget dependence, we provide a preliminary discussion on the benefits and limitations of process supervision signals and introduce BudgetMix RL as an alternative that varies interaction budgets during training. Experiments demonstrate that BudgetMix RL achieves robust performance across diverse execution settings. Project Page: https://rethinking-agentic-rl.github.io/

---

### [19] SAP Business AI Platform on BTP: AI Foundation, AI Core, and AI Launchpad

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/979-8-8688-2685-6_7&hl=zh-CN&sa=X&d=1844269753416403114&ei=H8bsaueXBIq86rQP3NyS0Ao&scisig=AIL1Nv7NWgQk8tVnY8Le8cjnRodN&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=3&folt=kw-top
**作者**: R Kaliyaperumal - Reinventing Enterprise with SAP Business AI: A …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> to select a suitable large language model (LLM). The model can explain complex prediction results in simple, business-friendly language . … SAP HANA Cloud Vector Engine works with other HANA Cloud capabilities in a multi - model architecture. This

---

### [20] Evaluating Human-LLM Alignment on Visualization Preference

**链接**: https://arxiv.org/abs/2611.06272
**作者**: Tanmay Bakshi, Chenglong Wang, Simra Shahid
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> There are often multiple valid visualizations, spanning different chart types, visual encodings, and aesthetic choices, that can all support a user's goal of analyzing a dataset. Determining which of these candidate visualizations is most appropriate, however, remains challenging. Prior work has leveraged expert-curated taxonomies to guide visualization design and subsequent quality evaluation, a practical evaluation model must also account for human-centric factors. Latest visualization tools integrate Large Language Models (LLMs) to generate and refine visualizations, using LLM-as-a-judge to provide design feedback. Without a deeper understanding of whether, and in what ways, human and LLM perceptions of visualizations align, there is a real risk of deploying low-quality agents that do not reflect human judgment. We study this question through a pilot experiment - we formulate the problem as a preference task over curated chart pairs and compare the judgments of state-of-the-art visi

---

### [21] A Training-Free Socket for DNA in Frozen Language Models

**链接**: https://arxiv.org/abs/2611.05401
**作者**: Arash Fatehi
**来源**: q-bio.GN cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Connecting a DNA foundation model to a large language model (LLM) usually requires training a connector, and often the LLM too. We show that a closed-form map is enough for gene-level questions. Our method, the socket, fits one ridge regression (the plug) from frozen Evo 2 features to the host LLM's own representation of the gene's symbol, name, and description at an early layer. The plug's output replaces the hidden state at placeholder positions, and no gradient passes through the host. We test it on GeneHop, a five-way multiple-choice benchmark split by homology. In a single run on the held-out test set, under a frozen analysis plan, real DNA beats shuffled DNA on all four hosts: by +22.2 points [19.8, 25.0] on Qwen3.5-4B, +26.1 [24.3, 27.9] on Qwen3.6-27B, +16.7 [14.2, 19.7] on Mistral-7B, and +18.4 [16.2, 21.0] on OLMo-2-7B. All four survive Holm correction, every null control stays within two points of the sham level, and the development results agree within 2.3 points. A layer r

---

### [22] Reward Budgeting Reduces Premature Convergence in Reinforcement Learning for LLM Reasoning

**链接**: https://arxiv.org/abs/2611.05942
**作者**: Mengni Jia, Mengyu Zhou, Xiaoxi Jiang, Guanjun Jiang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> RL for LLM reasoning often reaches an early performance plateau as the policy distribution becomes increasingly sharp. Recent work has studied policy entropy as both a diagnostic and a control signal for this behavior. In our experiments, however, increasing entropy alone does not reliably change the eventual plateau. We analyze RL through its implicit target policy and derive a sharpness factor $\kappa$, together with an effective counterpart $\kappa_{\mathrm{eff}}$, that describes how strongly reward or advantage gaps are translated into probability-ratio gaps. Motivated by this view, we introduce \emph{reward budgeting}, a plug-in advantage construction that assigns a fixed total reward budget to each prompt. For binary rewards and independent on-policy rollouts, its unclipped score-function estimator follows the gradient of an exact finite-$G$ concave objective with diminishing returns, while its advantage gap decreases as more rollouts become correct. For general rewards, a shifte

---

### [23] Finding the Gaps in LLM Translation with CoST

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.wmt-main.93.pdf&hl=zh-CN&sa=X&d=7884384972961247494&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv6ZOrkE4vU7iFgWyU_9I6Ea&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=3&folt=kw-top
**作者**: S Yadav, A Mukherjee, M Shrivastava - Proceedings of the Eleventh Conference on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models (LLMs) have advanced machine translation substantially, but generic benchmarks often fail to expose where these systems struggle with complex linguistic structures and stylistic nuance. We use CoST (Complex

---

### [24] From Solvers to Research: Large Language Model-Driven Formal Mathematics at the Research Frontier

**链接**: https://arxiv.org/abs/2607.07779
**作者**: Eric Jiang, Xiao Liang, Junyi Zhang, Justin Baker, Zhi Zhang, Yingjia Wan 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] When Disclosure Is Compulsory: Evaluating Ride-Hailing Rebalancing Policies with Self-Interested LLM Driver Agents

**链接**: https://arxiv.org/abs/2610.41132
**作者**: Xinyu Wang, Andres Fielbaum
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Analysis of Local Open-Weight LLM Agents on Vulnerability-Reproduction Tasks

**链接**: https://arxiv.org/abs/2611.06257
**作者**: Jorge Garc\'ia-Carrasco, Javier Sanchis, \'Alvaro Navarro, Alejandro Mat\'e, Juan Trujillo
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight language models that fit on a single consumer GPU are becoming capable on a growing range of tasks, and they matter because they can run locally without sending the code to a hosted service. Vulnerability reproduction, turning a vulnerability description into an input that crashes the vulnerable build, is a natural target for them, since it is an automated analysis task closer to test generation than to code comprehension and it runs against a build that must be executed rather than read. In order to assess whether current models can perform it, we evaluate twelve configurations of local models, spanning three generations, two architectures and three quantization levels, on ten CyberGym vulnerability-reproduction tasks, three runs each under one harness, and release the full artefact. We show that every configuration, down to the 4B model, solves most of the six easier tasks, and configurations separate only on the remaining four. For the harder tasks, the 27B model is requ

---

### [27] RAGAM-AI: A Hybrid Reinforcement Learning based Agentic approach powered by Generative AI for Edge Resource Management

**链接**: https://arxiv.org/abs/2611.06554
**作者**: Shreya K. Chari, John S. Vardakas, Kostas Ramantas, Christos Verikoukis
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Resource management for distributed edge networks hosting different services has been handled efficiently using Reinforcement learning (RL). Reward generalization in complex workflows is still an open issue within the RL realm. Therefore, this work proposes RAGAM-AI, a hybrid framework that combines the capabilities of RL algorithms and Generative-AI (Gen-AI) for powering an Agentic AI workflow that optimizes resource allocation at the Multi-access Edge Computing (MEC) units. This framework further resolves the reward generalization issue by utilizing Large Language Model (LLM) for feedback. A Multi- Agent Soft-Actor Critic (MASAC) using Math{\Sigma}tral as a reward oracle is implemented for managing resource allocations at the MEC. RAGAM-AI interprets system state information and evaluates multi-objective trade-offs guiding the resource orchestration loop over distributed edge server agents. The complexity of the framework is further brought down by incorporating surrogate reward mode

---

### [28] The Little Scientist: What Does the Scientific Method Buy an LLM Agent?

**链接**: https://arxiv.org/abs/2608.16951
**作者**: Travis Smith
**来源**: q-bio.QM cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] A Framework for Context Enrichment and Selective Robustness in LLM Social Agents

**链接**: https://arxiv.org/abs/2611.06914
**作者**: Mattia Greiche, Reihaneh Rabbany, Maximilian Puelma Touzel
**来源**: cs.MA cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers use large language models as agents in social simulations, where agents are prompted with observations and background information intended to shape their actions. Yet LLM agents have been shown to substantially change their behavior under meaning-preserving prompt variations, creating a validation problem for social simulation. One plausible hypothesis is that this brittleness reflects a lack of grounding and can be reduced by enriching the context provided to the agents. Whether richer context improves robustness remains unclear, in part because context richness and robustness are rarely defined in ways that support controlled comparisons. We address the first need with controlled context enrichment, a set of prompt substitution rules that systematically enriches distinct types of context: neutral padding, generic social background, descriptive decision grounding, and normative decision grounding. We address the second by introducing selective robustness as a validation cr

---

### [30] Stabilizing Off-policy LLM Optimization with Prefix Importance Ratio

**链接**: https://arxiv.org/abs/2601.22718
**作者**: Shiye Lei, Zhihao Cheng, Dacheng Tao
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] MASBench: Benchmarking LLM-based Multi-Agent Collaboration under Partial Observability

**链接**: https://arxiv.org/abs/2610.04672
**作者**: Qizhi Chu, Zekai Yu, Sijie Wen, Yang Liu, Chen Qian, Cheng Yang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Hybrid Spark: Adaptive Speculative Decoding That Lets the Content Choose the Drafter

**链接**: https://arxiv.org/abs/2611.05611
**作者**: Ekagra Ranjan, Bharat Venkitesh
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding (SD) speeds up large language model (LLM) serving, but its gain depends on the workload's \emph{shape}, such as batch size and context length, and on its \emph{content}. A model-based drafter proposes a short block on any content, while a model-free drafter such as n-gram lookup proposes long copies at almost no cost when the output repeats its input, as in code editing. Adaptive verification spends a batch-wide verification budget on the draft tokens most likely to be accepted, but it supports only one model-based drafter. Model-free drafters provide no per-token confidence, so they cannot take part in budget allocation, and deployments must either fix one drafter or split their GPUs between drafters. We present \sys, a framework that runs a model-based and a model-free drafter on every step and gives each request the better of their chains, within adaptive verification and entirely on the GPU, which keeps asynchronous scheduling intact. The key idea is a price pe

---

### [33] MD-ProTector: Positioning Multiple Data-Driven Prototypes for LLM-Generated Text Detection

**链接**: https://arxiv.org/abs/2608.10459
**作者**: Jinmo Han, Jimin Hong, Chanyeong Moon, Ju Yeon Kang, Seonuk Kim, Nam Soo Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] SafeStart: Mitigating the Overlooked Safety Cost of Active Expert Reduction in MoE LLM Serving

**链接**: https://arxiv.org/abs/2611.06147
**作者**: Erfan Baghaei Potraghloo, Saeid Shokoufa, Seyedarmin Azizi, Arya Fayyazi, Souvik Kundu, Mehdi Kamal 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixture-of-Experts (MoE) language models send each token through a few of many expert subnetworks. Serving methods make these models faster by running even fewer experts per token, and they are validated on accuracy benchmarks. We show that these methods can weaken the model's refusal of harmful requests, and we introduce SafeStart, which largely restores refusal while keeping most of the speedup. In vLLM on one RTX A6000, keeping about two thirds of the selected experts speeds up offline decoding by 15 to 28% at batch size 8. We find that, at this setting, under a jailbreak that tells the model not to refuse, the share of harmful requests that the model answers rises by 18.4 percentage points on Qwen1.5-MoE, 9.5 on OLMoE, and 6.6 on DeepSeek-V2-Lite, the three of nine models where it rises significantly, while MMLU accuracy drops by less than two points. We discover that most of this increase arises while the model processes the prompt and generates its first few tokens. SafeStart the

---

### [35] SPARTA: A Sparse Ternary LLM Accelerator with Adaptive Attention and Unified Datapath for Long-Context Edge Inference

**链接**: https://arxiv.org/abs/2610.34824
**作者**: Yanzhen Zhou, Zhengyu Han, Qunyou Liu, Zheyu Yan, Weihong Xu, Cheng Zhuo
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] PolicyMem: Geometric Policy Memory for LLM Governance

**链接**: https://arxiv.org/abs/2609.13734
**作者**: Yuanchen Bei, Zhengzhang Chen, Yanjun Zhao, Haoyu Wang, Hanghang Tong, Haifeng Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Zero-Shot Coordination among LLM Agents

**链接**: https://arxiv.org/abs/2611.06409
**作者**: Adrian Hayler, Shashank Reddy Chirra, Andrei Lupu, Johannes Forkel, Bidipta Sarkar, Siheng Feng 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study zero-shot coordination (ZSC), where independently developed agents must coordinate at test time. While ZSC has been well studied in the RL literature, far less is known about the performance of LLM agents despite their increasing deployment in such settings. Existing work on LLM coordination often relies on specialised scaffolding that independently developed agents are unlikely to share in practice. Moreover, evaluations on complex environments (e.g., Hanabi) make it difficult to pinpoint the sources of coordination failure. In contrast, we focus on simple, general-purpose scaffolds in minimal environments designed to isolate specific coordination challenges. Our results show that even in these controlled settings, frontier LLM agents struggle to coordinate, largely due to limited understanding of the coordination problem and weak reasoning about their partner's beliefs. While LLMs introduce semantic information as an additional axis for coordination, they nonetheless fail to

---

### [38] Tools Need Not Speak in Text: Latent Context Compression for Agents

**链接**: https://arxiv.org/abs/2611.06500
**作者**: Yuetong Liu, Zhehao Zhou, Yitong Zhang, Haorui Chen, Jia Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents typically append raw tool outputs to their context. Over multi-step interactions, long and noisy observations incur substantial context overhead and dilute the agent's attention to task-relevant information. Existing token pruning and summarization methods remain constrained by discrete text representations, limiting the achievable compression ratios. In this work, we challenge the prevailing assumption that agents must consume tool observations as explicit text tokens. To this end, we propose Coca-Cola, a continuous latent context compression model for LLM agents. Coca-Cola compresses tool observations into latent tokens and embeds them into the input embedding space of the agent. We further introduce Action-Preserving Training, which aligns the agent's next-action distributions under full and compressed observations. This trains the compression model to learn action-sufficient latent tokens that retain decision-critical information. Experiments with 

---

### [39] WhatIf: Interactive Exploration of Large-Scale LLM Agent Simulations for Policy Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3830398.3830720&hl=zh-CN&sa=X&d=9099854515845810086&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv48CgxWrvQRDxF3UWvNYgBZ&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=2&folt=kw-top
**作者**: Y Li, K Monteiro, H Shirado, S Das - Proceedings of the 39th Annual ACM Symposium …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> and natural language; explore over 12,000 LLM powered agents at interactive speeds; … Our findings show that interactive LLM -powered social simulations support a distinct mode … Together, these findings suggest that the key opportunity

---

### [40] Reducing confirmation bias on controversial issues through LLM -generated multi-persona debates

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306457326006308&hl=zh-CN&sa=X&d=14647848633443494515&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv5-dZczDDBjczP0B77od8Jq&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=5&folt=kw-top
**作者**: L Shi, H Liu, Y Wong, U Mujumdar, D Zhang, J Gwizdka… - Information Processing & … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multi-persona debate systems powered by large language models (LLMs) show promise in reducing confirmation bias; however, empirical evidence remains limited. Through a within-subjects experiment, we compared an LLM -generated multi-persona

---

### [41] Route to Remember: Adaptive Memory Selection for LLM Agents

**链接**: https://arxiv.org/abs/2611.05636
**作者**: Zeyu Fang, Jun Yin, Yongsheng Mei, Xu Han, Chaitali Joshi, Zhongkai Sun 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The memory of production agents is increasingly becoming a bottleneck and is built almost exclusively from text: key points are extracted from out-of-limit context and retrieved into context at query time. Therefore, every new query incurs an additional cost that grows with the accumulated history. Weight memory is a complementary alternative that internalizes knowledge into model parameters and answers with no context at all, and has recently proven effective in self-evolving agents for internalizing skills and behaviors. However, its application in episodic and semantic memory, such as user-specific facts, remains comparatively unexplored, and a gap remains between earlier attempts at weight memory and text-based systems regarding recall performance. We study how to make weight memory competitive as a long-term factual store by applying on-policy self-distillation (OPSD). It trains a context-free student from a teacher, which is the same model conditioned on the user's memory, togeth

---

### [42] LITMUS: Benchmarking Behavioral Jailbreaks of LLM Agents in Real OS Environments

**链接**: https://arxiv.org/abs/2605.10779
**作者**: Chiyu Zhang, Lu Zhou, Xiaogang Xu, Huiqin Yang, Bendong Jiang, Xiaolei Zhang 等 (10 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Pathwise-Budgeted LLM Routing: Online Allocation with K-Bit Tail-Cost Learning

**链接**: https://arxiv.org/abs/2611.05835
**作者**: Hanzhang Qin, Sophie H. Yu, Yuewei Zhang, Zhi-Hai Zhang
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Firms using large language models under fixed budgets must decide which model to call and whether to retry a failed task. Because a call's charge is revealed only after completion, one long response can exhaust the remaining budget and leave later tasks unserved. Our objective is to maximize the number of tasks solved before service stops. We develop a contextual bandit policy, ADP-HT, which learns each model's task-specific success probability and constructs conservative cost estimates from coarsened response-length labels on a quantile grid with $2^K$ intervals. The policy weighs predicted success against these costs, adjusting the cost penalty to realized spending and the budget available per remaining task. Under calibration, local regularity, and grid-coverage conditions, we bound the excess allowance in the policy's conservative cost estimates. At a fixed sample size, increasing $K$ reduces the discretization term but increases the estimation allowance. At the tightest tested bud

---

### [44] GaugeQuant: Online Learning of Quantization-Optimal Bases from LLM Symmetries

**链接**: https://arxiv.org/abs/2607.20757
**作者**: Miguel P. Bento, Jo\~ao F. Seabra
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] A Controlled Experimental Evaluation of Configuration and Cache Architecture in LLM Serving Engines

**链接**: https://arxiv.org/abs/2611.05991
**作者**: Muhammad Faizan Anwar, Sina Keshvadi
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM applications repeat most of their prompt tokens across requests, and serving engines reuse the cached state of shared prefixes. vLLM and SGLang reuse it at different granularities, and benchmarks of their default deployments report large performance gaps, usually credited to the cache. Such comparisons rarely control for other configuration differences. One of them, whether a long prompt is prefilled in chunks, is set by each engine's defaults from the hardware and the release, and it confounds the comparison. We built a reproducible testbed on Kubernetes and a seeded multi-agent workload generator, and compared the two engines under vendor defaults and with chunked prefill matched. SGLang's configuration is the same in both arms, which makes it an internal control across independently provisioned deployments. Under defaults, vLLM's median time to first token is up to 64x SGLang's. Matching one setting removes 78% of the capacity gap where that gap is largest and 30 to 

---

### [46] Prospective Memory for Proactive LLM Agents

**链接**: https://arxiv.org/abs/2611.05731
**作者**: Yuanchen Bei, Zhining Liu, Tianxin Wei, Weizhi Zhang, Zhichen Zeng, Philip S. Yu 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most memory systems for LLM agents are retrospective, preserving and retrieving past information to inform current decisions. Proactive agents, however, also require prospective memory: retaining future-directed intentions and realizing them when appropriate opportunities arise, even without explicit requests. Crucially, remembering the right intention does not guarantee acting at the right time: a related observation may call for waiting, while a later cue may make the same intention actionable. Inspired by cognitive theories of human prospective memory, we introduce Pro-Memory, a memory framework that separates maintaining future intentions from deciding when and how to realize them. Pro-Memory preserves pending objectives linked to their supporting evidence, assesses new observations against their original goals and activation conditions, and coordinates appropriate contributions with the agent's ongoing actions. It further updates intention states based on actions actually issued o

---

### [47] LIBRA: Programmatic Induction of Executable Tool Libraries

**链接**: https://arxiv.org/abs/2611.05445
**作者**: Zekai Li, Zhenke Liu, Yonghao Li, Junhan Liu, Xulong Xiao, Jiapeng Zhang
**来源**: cs.SE cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly retrieve tools from large catalogs, yet most retrievers rank each tool independently by request similarity. For multi tool tasks, this recovers the goal matching tool while omitting prerequisite tools required by the workflow.We introduce LIBRA, a framework for Library Induction by Runtime Assembly that turns a flat tool catalog into an executable tool library. An LLM proposes per tool contracts of candidate invocations, reusable outputs and state changes, and success conditions; LIBRA then tests these compositions in a sandbox and retains the relations supported at runtime. Constructed before user queries, the library requires no dependency annotations, tool use trajectories, or task specific training, and supports both one-shot and agentic retrieval. On AppWorld, BFCL, and SciToolEval, LIBRA improves one-shot Recall and NDCG over the same dense retriever by 7.9 and 3.7 percentage points on average. Within ToolReAGt, it yields corresponding gai

---

### [48] Context--Answer Metamodels: Forecasting LLM Activations Before the First Answer Token

**链接**: https://arxiv.org/abs/2611.06837
**作者**: Tommy He, Thomas Jiralerspong
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Under stochastic decoding, a single context can elicit many different answers from a language model. Characterizing this variation typically requires many expensive autoregressive rollouts, each revealing only one realization. We ask whether the activations produced while reading the context can directly forecast the model's rollout activations. We train context--answer metamodels that map a context activation sequence to point or distribution forecasts of mean-pooled answer activations. We find that (i) the four metamodel families we study forecast mean-pooled answer activations with high fidelity, and the distribution metamodels also capture rollout variability; (ii) performance improves as the training set grows to 500,000 prompts, and the metamodels generalize zero-shot to out-of-domain datasets; (iii) their forecasts retain behavior-predictive signal; and (iv) context activations from Qwen2.5 predict mean-pooled answer activations from Qwen3.5 and Gemma 4, suggesting that activati

---

### [49] SpecCompact: Accelerating LLM Agent Context Compaction with Slot-Parallel Semantic Speculative Verification

**链接**: https://arxiv.org/abs/2611.06876
**作者**: Yulu An, Yifei Feng, Xiangyang Yin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents use context compaction to manage growing interaction histories, but summarizing long histories with large models can introduce substantial delays. Compaction therefore requires balancing information retention against latency. We observe that structured summary slots can retain information when generated independently. Based on this observation, we present SpecCompact, a framework that accelerates compaction through slot-parallel semantic speculation. SpecCompact fine-tunes a small drafter and generates slots in parallel. The target model verifies each proposed line and repairs rejected content, while subsequent drafting uses the updated slot prefix. System optimizations further reduce repeated context processing and model calls. Across AppWorld and $\tau^3$ benchmarks with two target models, SpecCompact achieves $2.04$--$5.63\times$ compaction speedups over Hermes-style summarization. Separate downstream evaluations reveal model- and task-dependent performance trade-offs. A 

---

### [50] AGORA: Reliability-Aware Aggregation of LLM Judges via Item-Response Theory

**链接**: https://arxiv.org/abs/2611.05556
**作者**: Junhyung Ahn
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge is a common substitute for costly human evaluation, and aggregating several judges is the standard remedy for any single judge's bias. Judge pools mix judges of very different reliability, while the human-labeled sets that validate them hold a few hundred items or fewer. In this regime the per-item mean weights weak judges as heavily as strong ones, and confusion-table models such as Dawid-Skene must estimate a per-judge error table from too few items. We propose AGORA (Aggregation Of Reliability-weighted Assessments), an item-response-theory aggregator that places every item on one latent quality scale and describes each judge by a sensitivity parameter and ordered rating thresholds, so judge reliability is learned from all items jointly and without human labels. Across three benchmarks, AGORA matches or exceeds Dawid-Skene on large evaluation sets, and its advantage widens as the set shrinks toward a few hundred items. It remains accurate as pools grow more uneven, a l

---

### [51] OpInf-LLM: Parametric PDE Solving with LLMs via Operator Inference

**链接**: https://arxiv.org/abs/2602.01493
**作者**: Zhuoyuan Wang, Hanjiang Hu, Xiyu Deng, Saviz Mowlavi, Yorie Nakahira
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] AgentTrustCI: Build-Time Policy, Grounding, and Trajectory Tests for Java LLM Agents

**链接**: https://arxiv.org/abs/2611.06674
**作者**: Sachin Gupta
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Infrastructure security does not establish whether an LLM agent selected an allowed tool, grounded its answer in tool output, or followed a required workflow. AgentTrustCI is a Java/JUnit 5 framework that expresses these application-layer expectations as policy, grounding, and trajectory checks over recorded traces. A deterministic replay implementation supports repeatable build-time tests; a judge interface provides an extension point for optional semantic evaluation. On 55 synthetic cases spanning seven enterprise domains, the full pipeline correctly classifies all 30 injected faults and 25 passing controls, including ten non-trivial controls, and misses none of 12 designated critical cases. Each single-layer configuration correctly classifies 35 cases because the corpus deliberately isolates ten faults per layer. A grounded answer obtained through a disallowed sequence illustrates the additional coverage of trajectory checks. Repeated measurements quantify validator execution separa

---

### [53] Quality-aware cost minimization for multi-tier LLM routing in heterogeneous data centers

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-76772-7_reference.pdf&hl=zh-CN&sa=X&d=3792863065320931128&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv6kA6_ELU7a5ft4gAqMSR_D&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=8&folt=kw-top
**作者**: K Chadli, G Botterweck, T Saber - Scientific Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We propose an LLM deployment and routing strategy that leverages hardware heterogeneity by coupling instance selection with quality … This work focuses on planning-level optimization of cost–quality trade-offs in heterogeneous LLM serving

---

### [54] A retrieval-augmented LLM framework for PRISMA-aligned systematic reviews: a case study on action quality assessment

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s00521-026-12546-6&hl=zh-CN&sa=X&d=2396552689595188356&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv5v2ometOvCy4og54QiqQ9Q&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=4&folt=kw-top
**作者**: R Silvestri, M Pincheira, M Vecchio, F Antonelli - Neural Computing and Applications, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Systematic reviews and meta-analyses are essential for advancing scientific research, but they are time-consuming, labor-intensive, and prone to human error during literature selection and data extraction. This paper proposes a framework that

---

### [55] LLM-based NPCs in Video Games: A Systematic Mapping Study

**链接**: https://arxiv.org/abs/2611.05427
**作者**: Dilan Mian, Jeremy Bradbury, Yann-Ga\"el Gu\'eh\'eneuc, Fabio Petrillo and Cristiano Politowski
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For decades, non-player characters (NPCs) have been driven by rule-based systems whose personalities and interactions are scripted before release. Large language models (LLMs) promise NPCs that converse openly, adapt to new situations, and behave in ways developers did not fully author, prompting a wave of research and commercial experimentation. Yet the field lacks a unified picture of what has been built, how well it works, and at what cost. We address this gap with a systematic mapping study of 377 papers from the academic literature, yielding 42 papers analysed against a main research question and ten sub-questions across four thematic axes. We provide the first quantitative characterisation of component adoption, latency, safety coverage, and reproducibility: short-term memory and world-state grounding are near-universal (60% and 69%), whereas long-term memory (31%), reflection (38%), and retrieval-augmented generation (14%) remain rare, and response times span 2.6 to 15 seconds. 

---

### [56] Learning When Human Decisions Matter: Executor-Relative Consultation Value for LLM Agents

**链接**: https://arxiv.org/abs/2611.05814
**作者**: Shuli Jiang, Khushbu Pahwa, Yuting Zhang, Yi Zhang, Wei Xia, Stefano Soatto
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly automate complex tasks, but human decision capacity does not scale with their capabilities. In many applications, humans remain essential for providing private context, authority, or judgments unavailable to the agent. We formulate human decision capacity allocation: given multiple consultation opportunities and a limited budget, at which decisions should an LLM agent consult a human? The central challenge is estimating consultation value, which is executor-dependent because the same human input may benefit different downstream agents differently. We introduce Consultation Value Distillation (CVD), which estimates consultation values offline using Monte Carlo executor rollouts and distills these values into lightweight predictors for budgeted allocation, requiring no rollout-based value estimation at deployment. Across five batch and three sequential settings with two frontier executors, CVD improves allocation through joint and continuation-aware val

---

### [57] When Do Summaries Become Instructions? Unsupported Policy in LLM Agents' Self-Written Handoff Summaries

**链接**: https://arxiv.org/abs/2611.06545
**作者**: Wenhui Chu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents compact their context, replacing most history with a summary. We ask whether handoff summaries state permissions or requirements the record does not support, whether such sentences change what the next instance (the successor) does, and where they come from. Synthetic tool-use tasks carry a ground-truth permission ledger; same-snapshot replay reruns the successor with those whole sentences replaced by neutral filler. Two AI readers, reading only rule-flagged held-out summaries, confirmed unsupported restrictions in 1.2% and 2.4% of all readable summaries from two open-weight models, and unsupported authorizations in 0.1% and 1.3%. For restrictions, a pre-specified replay test was not significant (p = 0.58); a follow-up, planned after it, found a fragile effect (p = 0.027). Neutralizing false approvals cut unauthorized actions from 24 to 7 of 120 held-out runs (post hoc; later set: 17 to 11 of 48). Most development restrictions followed the agent's earlier reason

---

### [58] Fractional Power-of-Two Quantization for Efficient and Effective Multiplier-Free LLM Inference

**链接**: https://arxiv.org/abs/2610.21257
**作者**: Sunghyun Wee, Geunjae Choi, Hyeonjin Kim, Suyoung Kim, Nojun Kwak
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Hybrid LLM-Deterministic Pipelines for Enterprise-Scale Code Migration at Bloomberg

**链接**: https://arxiv.org/abs/2611.05457
**作者**: Mario Corchero, David Williams, Laszlo Kiss Kollar, Haowen Liu, Shivam Bairoliya, Gala Malbasic 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large organizations carry a long tail of infrastructure migrations that are worth doing but rarely urgent enough to compete with feature work, because each one costs significant engineering time per repository. This paper reports on our industrial experience from Automated Uplift, a multi-month initiative applying LLM-assisted migration pipelines across thousands of Bloomberg repositories. We examine two distinct production campaigns: a heterogeneous Python packaging migration (approx. 1,900 candidate repositories) and a uniform C++ build system migration (approx. 6,700 candidate repositories). Together, these campaigns generated 2,333 pull requests, resulting in 729 successful migrations. We detail our hybrid architectural solution which maximizes deterministic processing, confines the LLM to bounded file transformations within a pre-computed context, and incorporates runtime production telemetry (such as execution logs and usage traces). Our findings show that generating migrations t

---

### [60] CARTBench: Rubric-Based Evaluation of Shopping Advice for Complex and Ambiguous Requests with Timelines

**链接**: https://arxiv.org/abs/2611.05862
**作者**: Yuqin Dai, Zhanwei Zhang, Honghui Yang, Zhouheng Yao, Yueqi Zhang, Jingyu He 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) shopping assistants now recommend products in multi-turn conversations. However, reliable evaluation faces Data scarcity and Difficulty Standardizing Criteria. To address these obstacles, we introduce CARTBench for CART (Complex and Ambiguous Requests with Timelines). For Data scarcity, we curate cases from real commercial shopping needs across 17 retail domains, pairing timestamped dialogue with 1,603 product records. For Difficulty Standardizing Criteria, we develop case-specific rubrics guided by Ideal Response Principles, distilled from excellent replies manually selected from successfully completed orders. These principles also guide Principle-Guided CART Prompting, our structured recommendation strategy. The experimental benchmark contains 1,328 expert-annotated criteria across Core, Excellence, and Safety. To answer the CART question, we evaluate 7 flagship commercial API models, including GPT-6.1-Sol and Claude-Opus-5, and 35B+ parameters open-weight 

---

### [61] Rewrite, Then Veto: Rewriter-Agnostic Edit Gating for LLM-Based Post-OCR Correction

**链接**: https://arxiv.org/abs/2611.05539
**作者**: Jorge Ram\'on Fonseca Cacho
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can repair noisy OCR transcripts of historical documents, but they also change text that was already correct. We propose EditVeto, a veto gate placed after a full-context LLM rewrite. The rewrite is character-aligned to the OCR input, its differences are split into blocks, and a 0.6B-parameter gate keeps or reverts each block. An oracle analysis motivates the design: given the true error locations, per-span generation is worse than no correction, whereas vetoing a full rewrite's edits helps. Trained on rewrites by two Qwen3 models and evaluated, frozen, on the eight HIPE-OCRepair-2026 test sets, the gate improves all five rewriters tested, two of them unseen in training: weighted cMER falls by 0.0026-0.0044 and the preference score rises by 0.15-0.25 (paired bootstrap, p ~ 0.0002 each). On published competition outputs it lowers cMER for three of four teams but raises it for the winning run (0.0050 to 0.0065). In a second, disclosed test look, a retrained gate still improves LoRA-

---

### [62] Computational Phenomenology of Borderline Personality Disorder: A Comparative Evaluation of LLM-Simulated Expert Personas and Human Clinical Experts

**链接**: https://arxiv.org/abs/2508.19008
**作者**: Marcin Moskalewicz, Anna Sterna, Karolina Dro\.zd\.z, Kacper Dudzic, Marek Pokropski, Paula Flores
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] Local Entropy Fluctuations for Black-Box LLM-Generated Text Detection

**链接**: https://arxiv.org/abs/2610.33767
**作者**: Xinpeng Wang, Bruce Rushing, Zhizhen Chen, Zhe Zeng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] LLM Agents Already Know When to Call Tools -- Even Without Reasoning

**链接**: https://arxiv.org/abs/2605.09252
**作者**: Chung-En Sun, Linbo Liu, Ge Yan, Zimo Wang, Tsui-Wei Weng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Agent Gym: A Framework for Continuous Evaluation and Evolution of LLM Agents Through Human-in-the-Loop Feedback

**链接**: https://arxiv.org/abs/2608.15591
**作者**: Pouya Ghiasnezhad Omran, Michael Zimmermann, Duncan Cambridge, Ashmita Kapoor, Tanya Dixit
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] AutoEnergyDesign: An LLM-Driven Agent for Automatic Energy System Design Optimization

**链接**: https://arxiv.org/abs/2610.35160
**作者**: Amedeo Buonanno, Salvatore Fabozzi, Maria Valenti
**来源**: cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Dull, Dirty, Dangerous? Working Conditions and the Limits of Occupational AI Exposure

**链接**: https://arxiv.org/abs/2611.06888
**作者**: Siyi Yu
**来源**: cs.AI cs.HC econ.GN q-fin.EC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automation is often justified as relief from dull, dirty, and dangerous work. I examine how these conditions relate to occupational AI exposure using 21 O*NET items across 754 US occupations. Higher exposure is associated with lower condition scores under a large language model (LLM) measure and AI Occupational Exposure (AIOE), with equal occupation weights and employment weights. Adjustment for physical demands, required education, training and experience, and wages reduces the composite association. The adjusted confidence intervals include zero for LLM exposure and remain below zero for AIOE. Separating repetition from restricted discretion also changes what the combined Dull score conveys. These comparisons show how item groupings and occupational characteristics shape the interpretation of exposure estimates. Occupational profiles offer a starting point for selecting contrasting research settings. Establishing desired automation or realized relief requires evidence about workers' 

---

### [68] Pairing Expert Critique with LLM-Driven Refinement: An Iterative Approach for Curating Quality AI Evaluation Datasets

**链接**: https://arxiv.org/abs/2611.05749
**作者**: Honson Ling, Kidus Admassu, Stephanie Rosenthal
**来源**: cs.HC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating and improving domain-specific LLM responses requires high-quality reference data and rubrics, yet expert authoring is slow and expensive, and synthetic datasets may fail to capture practitioner preferences unless they are grounded in expert judgment. We present SME-C (Subject Matter Expert Critique), a human-AI workflow that captures expertise through lightweight critiques of candidate responses and complements it with LLM-driven analysis and refinement to iteratively curate response datasets and evaluation rubrics. We validate SME-C in the domain of financial business briefs, collecting 3,853 critiques from 411 finance professionals on 520 queries across two survey rounds. We evaluate two LLM-driven refinement strategies: one guided by the experts' written critiques and one that infers critique solely from their preference votes. In a blind validation survey with 100 additional professionals, we found that both strategies significantly improved quality over the experts' top

---

### [69] Before You Continue: Evaluating Time-Sensitive Safety Awareness in Conversational Assistants

**链接**: https://arxiv.org/abs/2611.06839
**作者**: Peidi Dong, Yunze Xiao, Yu-Lin Tsai, Yichen Zheng, Heyuan Huang, Weihao Xuan 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) assistants increasingly help users with everyday activities that involve time-dependent constraints. However, users may not mention these constraints in later requests, requiring assistants to recognize and adjust their advice accordingly. To evaluate such capability, we introduce TASC (Temporal Action Safety in Conversation), a benchmark that evaluates whether LLMs apply time-dependent constraints when responding to conversational requests. TASC consists of 3,418 inputs derived from 128 templates, along with a separate set of 33 scenarios designed to compare models' ability to calculate elapsed time with their ability to apply that information. Across 13 models, assistants account for time-dependent constraints in only 30.5% of cases where the proposed action violates a rule, while rarely warning users unnecessarily. More importantly, models fail to apply these constraints in 62.1% of cases despite correctly calculating the elapsed time. Explicitly providing

---

### [70] Cite What You Explore: Budget-Aware LLM Reasoning over Medical KGs with Verifiable Evidence

**链接**: https://arxiv.org/abs/2610.07739
**作者**: Chen Chen, Dongjie Wang, Mei Liu, Zijun Yao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Ekka: Automated Diagnosis of Silent Errors in LLM Inference

**链接**: https://arxiv.org/abs/2606.04594
**作者**: Yile Gu, Zhen Zhang, Shaowei Zhu, Xinwei Fu, Jun Wu, Yida Wang 等 (7 人)
**来源**: cs.DC cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] Who May Overrule the Agent? Evidence-Gated Authority in LLM Review Institutions

**链接**: https://arxiv.org/abs/2611.05390
**作者**: Fuad Ali
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent language-model systems often add a reviewer to improve an upstream agent's decision. Yet a reviewer can both repair errors and replace decisions that were already correct. We study this as a problem of institutional jurisdiction: conditional on the same proposal, task information, model, and review output, when is the reviewer authorized to make its recommendation binding? We compare broad override authority with an evidence gate that permits replacement only after the reviewer produces a mechanically valid record of a binding-constraint violation and a compliant repair. Across two locally run open-weight models, 96 spatial-policy tasks, and a 96-task portfolio-transfer benchmark, the gate sharply reduces corruption of correct proposals while retaining most repairs of violations. The directions of this tradeoff are partly implied by the rule; its magnitude depends on reviewer transitions and upstream proposal states. A prospective validation then gives the reviewer an expli

---

### [73] Scheduling Data to Compute: Hierarchical Data Pipelining for LLM Training on AMD GPUs

**链接**: https://arxiv.org/abs/2611.05751
**作者**: Gengyu Rao, Ghadeer Ahmed H Alabandi, Su Ann Chong, Thomas Huber, Kailash Gogineni, Subhajit Dutta Chowdhury 等 (10 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLM) have been the key focus of recent machine learning breakthroughs. As the model size grows exponentially, the computation needed for training is astronomical. A GPU can do a huge amount of arithmetic. However, the data its compute units need is not always available when they are ready. This data may still be in slow memory or on another GPU. While the chip waits, expensive compute sits idle, and at scale even a small drop in utilization translates into substantial cost. In this paper, we treat this waiting time as the primary bottleneck. We focus on hardware features designed for explicit data movement. These features load data from off-chip memory onto the chip, rearrange it into the layout the computation requires as it is loaded, and transfer it between GPUs. By orchestrating them, we keep a steady pipeline of data flowing to the compute units so that they remain busy. We present kernel and framework implementations that address this bottleneck using three

---

### [74] The Harness Is the Model: Agent Scaffolding Changes a Fixed LLM's Compliance with Banking Conduct Rules, Unevenly Across Models

**链接**: https://arxiv.org/abs/2611.06116
**作者**: Mehmet Murat Huyut
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Banks validate language models, but they deploy systems: a model inside a harness that decides what it sees, which tools it can call and who checks its actions. We test whether that harness changes compliance with banking conduct rules when the model is held fixed. Four open-weight models each ran five harnesses (a pipeline that makes one structured decision, a ReAct-style tool loop, a loop in which the policy is reachable only through search, a loop with a long benign customer memory, and a loop with a same-model compliance reviewer) on 156 pre-registered cases in a simulated retail bank whose 11 rule families paraphrase EU consumer-credit, payments, investor-protection, data-protection and anti-money-laundering provisions. Every one of the 3120 two-turn episodes was scored deterministically from the executed tool trace, with violations and over-refusals counted separately. Pooled across models the harness moved the correct-case rate only between 87.3% and 92.1%, but within a model it

---

### [75] Vision Paper: Why Distributed LLM Post-Training and Decentralized Alignment Are Now Essential

**链接**: https://arxiv.org/abs/2611.05841
**作者**: Zhanhong Jiang, Qisai Liu, Soumik Sarkar
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This vision paper argues that distributed learning, including federated and decentralized, should become a first-class paradigm in LLM post-training, not merely a privacy add-on. Current methods like RLHF and DPO rest on an invisible assumption: preference data should be centralized. We contend this assumption is scientifically unjustified, practically unsustainable, and ethically problematic. As LLMs deploy into healthcare, law, finance, and multilingual communities, preference data originates from populations that cannot or will not centralize. We develop a three-pillar argument grounded in (1) privacy and data sovereignty, (2) pluralism and representational equity, and (3) robustness and scalability. We formalize key technical challenges unique to this intersection, reference drift, preference heterogeneity, and the DP-utility trade-off for contrastive losses, and propose concrete algorithmic directions, and sketch a research agenda. Our analysis shows distributed post-training is n

---

### [76] Measuring Risk, Not Harm: Detecting Psychological Harm Risk Factors in LLM Conversations

**链接**: https://arxiv.org/abs/2611.06806
**作者**: Nil-Jana Akpinar, Eugenia Kim, Natalie Isak, Amanda Minnich, Victoria Westerhoff, Matthew Dressman
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Psychological harms from interactions with large language models cannot be monitored directly because they may emerge over repeated interactions and depend strongly on subjective individual user context. We propose measuring risk, not harm: detecting observable AI behaviors that constitute risk factors for psychological harm at the AI response level and aggregating these signals to support longitudinal monitoring. We operationalize eight such behaviors and construct a synthetic multi-label corpus of 47,062 AI responses and 373,873 response-factor labels, with targeted human annotations for validation and evaluation. We then compare trained embedding-based classifiers, direct LLM judging, and a classifier--judge cascade. All detectors are model-agnostic and operate only on LLM outputs, requiring no access to internal model states. We apply these detectors to several out-of-distribution human-AI conversation data sets from prior research. On held-out human-labeled data, the best cascade 

---

### [77] Programming Task Performance and Perceived Cognitive Engagement Across Three LLM Support Configurations

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S294988212600174X&hl=zh-CN&sa=X&d=2779179382552227378&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv4xzveDCw7lfBDmWjX1XbTj&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=9&folt=kw-top
**作者**: M Giannakos, HG Liisberg, M Kvalsund, C Wang… - Computers in Human …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Data comprised submitted code, interaction measures, questionnaires, and interviews with 15 students from the two LLM conditions. Unrestricted chat yielded higher task scores than both restricted feedback and the no- LLM environment. Both

---

### [78] Verified but Vacuous: Three Failure Surfaces of LLM-Driven Verified Code Generation

**链接**: https://arxiv.org/abs/2611.05590
**作者**: Aditya Vempaty and Himaneesh Sompalle and Manan Tayal and Mowafak Allaham and Prasenjit Dey and Ashish Jagmohan and Ravi Kokku
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What should ``verified'' mean when evaluating LLM-generated code? Many existing pipelines report a single verification number. We argue this collapses three distinct properties measured in a conditional audit sequence: verifier acceptance (Surface A), \emph{syntactic specification binding (Surface B: does the proof obligation bind to the spec?), and \emph{semantic specification fidelity} (Surface C: does the spec capture the informal requirement?). Two empirical demonstrations show the surfaces separate. \textbf{First ($A \neq B$), via Li@Opus (a same-model reproduction of \citet{li2025dafny}'s Dafny-as-intermediate-representation (IR) pipeline under Claude Opus 4.7) on three Python benchmarks}: it reaches \textbf{99.1\% verifier acceptance} on HumanEval while only \textbf{1.9\%} carry a certificate binding to a spec-defined predicate or function. \textbf{Second ($B \neq C$), via VCG on two Rust benchmarks}: we use VCG (which is our own in-house Dafny-as-intermediate pipeline) on Rust 

---

### [79] Cognitive Bias Signatures in Search-Equipped LLM Agents: A Stage-Resolved Analysis

**链接**: https://arxiv.org/abs/2611.05720
**作者**: Yanru Xiao, Yingwei Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Search can help LLM agents correct mistakes, but their starting conditions may shape which evidence they find and use. Drawing on cognitive-bias paradigms, we develop a controlled search harness to examine result order, records of prior work, and initial hypotheses while holding each question and document collection fixed. Matched controls distinguish order effects from differences in document composition and the effects of failed work from context length. Across 10 models and 1,000 synthetic search worlds, we track queries, retrieved documents, document openings, and final answers. Our comparisons suggest that final answers are more sensitive to initial evidence order during active search than when all evidence is supplied in full. Dead-end histories can reduce strategy switching relative to matched neutral histories, indicating an effect beyond context length. Under wrong hypotheses, stage measurements distinguish reduced retrieval or opening from errors that persist after counter-ev

---

### [80] MemCanvas: A Structured Memory Canvas for Evolving Intent Alignment in LLM Dialogues

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/full/10.1145/3830398.3830596&hl=zh-CN&sa=X&d=13409188513887196579&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv5AUCJLXOGkc3ydLc6HXrtH&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=7&folt=kw-top
**作者**: J Ye, Y Fei, Y Lu, Z Zhou, W You - Proceedings of the 39th Annual ACM Symposium …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Aligning user intent in complex, evolving dialogues with Large Language Models (LLMs) is a significant challenge. We attribute this to a cognitive divergence between LLM ’s linear reasoning based on context and statistical semantic representations, and the

---

### [81] Modeling ESG Performance Drivers in the Shipping Industry: An LLM ‐Assisted q‐ROFRS‐Delphi‐WINGS‐FCM Framework for Causal Analysis and Simulation

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/abs/10.1002/bse.71715&hl=zh-CN&sa=X&d=3639513205030824934&ei=HsbsarfnNIq86rQP3NyS0Ao&scisig=AIL1Nv6QvOp0e7u5G9nXjzU96qeb&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=6&folt=kw-top
**作者**: S Lu, W Zhao, MA Moktadir, H Ma, Y Ayub, J Ren - Business Strategy and the … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this study, the LLM is used as a structured text mining and relationship extraction tool rather than as an independent causal inference model. Its … The reliability of the extracted CSFs is therefore not assumed solely from the LLM output;

---

### [82] MemReward: Graph-Based Experience Memory for LLM Reward Prediction with Limited Labels

**链接**: https://arxiv.org/abs/2603.19310
**作者**: Tianyang Luo, Tao Feng, Zhigang Hua, Yan Xie, Shuang Yang, Ge Liu 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] CyclicJudge: Mitigating Judge Bias Efficiently in LLM-based Evaluation

**链接**: https://arxiv.org/abs/2603.01865
**作者**: Ziyi Zhu, Olivier Tieleman, Alexey Bukhtiyarov, Jinghong Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Where Is the "Self" of a Large Language Model? -- From Self-Index to Self-Reference

**链接**: https://arxiv.org/abs/2610.16717
**作者**: Yuchen Li, Xintong Li, Zongqi Fan, Ken-tye Yong, Nguyen H. Tran
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [85] Multi-User Large Language Model Agents

**链接**: https://arxiv.org/abs/2604.08567
**作者**: Shu Yang, Shenzhe Zhu, Hao Zhu, Jos\'e Ram\'on Enr\'iquez, Di Wang, Alex Pentland 等 (8 人)
**来源**: cs.CL cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Give Up to Get More: Priors, Not Policies, Govern Test-Time Compute Allocation

**链接**: https://arxiv.org/abs/2611.06372
**作者**: Jinhyung Bae
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When many inputs share a budget of repeated attempts by a large language model (LLM), a common rule gives harder inputs more. On public math, code and formal-proof samples, the best published difficulty-proportional rule captures half or more of the oracle gain on benchmarks the model mostly solves, but at most 13% on hard workloads, even given true pass rates. Because the value of one more attempt peaks at intermediate difficulty, the optimal static allocation is inverted-U and gives little to inputs that are hopeless at the current budget. In a strict survey of 221 LLM allocation papers, at least 13 give the hardest inputs the most attempts; their easier settings sit at budgets where this is near-optimal, so the cost appears on harder workloads. Acting on it requires knowing which inputs are solvable, so information, not the policy, drives the gain. With a verifier and a prior from a related model's past runs on the same inputs, Thompson Sampling raises the solved share on the hardes

---

### [87] End-Edge-Cloud Collaborative Inference for Efficient Large Language Model Services: A Survey

**链接**: https://scholar.google.com/scholar_url?url=https://www.preprints.org/frontend/manuscript/880649bca70c7a5a8b931d5b28b7dd8b/download_pub&hl=zh-CN&sa=X&d=125709715041662727&ei=H8bsaueXBIq86rQP3NyS0Ao&scisig=AIL1Nv7LpebAaO2oJPoRLC0QNE00&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=1&folt=kw-top
**作者**: Y Hu, Z Yang, Q Guo, P Li, S Sun, M Liu 等 (8 人)
**来源**: 2026
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multi - model collaborative inference exploits complementary capabilities across tiers to reduce reliance on stronger … Edge vs cloud: How do we balance cost, latency, and quality for large language models over 5G networks? In Proceedings of

---

### [88] A Financial Brain Scan of the LLM

**链接**: https://arxiv.org/abs/2508.21285
**作者**: Hui Chen, Antoine Didisheim, Mo Pourmohammadi, Luciano Somoza, Hanqing Tian
**来源**: q-fin.GN cs.AI cs.CE econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Population-Aligned Persona Generation for LLM-based Social Simulation

**链接**: https://arxiv.org/abs/2509.10127
**作者**: Zhengyu Hu, Jianxun Lian, Zheyuan Xiao, Max Xiong, Tianfu Wang, Teng Xiao 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] AgentCount: An Agentic Workflow for Traceable Colony Counting and Insight Generation from Agar Plate Images

**链接**: https://arxiv.org/abs/2611.05398
**作者**: Zhuosheng Liu and Austin E. Weber
**来源**: q-bio.QM cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Colony counting is commonly used to evaluate microbial populations in food safety testing and microbiological studies. Despite its wide application, manual counting is time-consuming and operator-dependent, and the final count often lacks a record of the objects included in the measurement. To address these limitations, this study presents AgentCount, an open-source agentic workflow for colony counting and result interpretation from agar plate images. Plate photographs and plating metadata are processed through seven agents for image quality control, plate localisation, colony detection, counting, CFU calculation, validation, and reporting. Colony detection is performed using Segment Anything Model 3 (SAM 3) with multiple text prompts and morphology-based filtering. After that, replicate statistics are calculated and a large language model (LLM)-based agent is used to generate a results narrative. Intermediate outputs, including quality scores, segmentation masks, detections, and warni

---

### [91] CompressionBench: How can your coding agents compress LLMs?

**链接**: https://arxiv.org/abs/2611.06858
**作者**: Xinrui Zhong, Zhifeng Li, Zhiming Wang, Yongqi Liu, Shanglin Yang, Yang Zhou 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement requires AI systems to improve the models and infrastructure used by subsequent systems. LLM compression offers a concrete efficiency objective: retain a pretrained model's behavior within a smaller model storage budget. We study whether coding agents can carry out this step autonomously. We formulate compression as a terminal task in which an agent receives a source checkpoint, storage limit, inference environment, and time budget, then constructs compressed weights and executable inference code. The agent controls its algorithm and experiments; perplexity feedback guides search, and independent verification checks the final model. Across six agents and six model--size settings, 29 of 36 submissions pass verification. Selecting the lowest-perplexity agent design per task yields an average 3.4% perplexity increase over BF16 and 77.33% downstream accuracy, compared with 79.56% for BF16. Recorded experiments reveal how agents achieve these outcomes and where im

---

### [92] SAUCE: Summary Analysis Using Conversation Entailment

**链接**: https://arxiv.org/abs/2611.06812
**作者**: Man-Ling Sung, Hemanth Kandula, Jeff Ma, William Hartmann, Matthew Snover
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the growing need for evaluating Large Language Models (LLMs) and their applications to speech, challenges persist in summarizing and evaluating conversations that lack a clear end goal. We introduce SAUCE -- a reference-free, fact-based evaluation pipeline for cross-lingual conversational speech summarization. It measures the accuracy and the fact coverage of a summary through the entailment between conversation and text. We compare SAUCE against several popular summarization metrics and demonstrate the effectiveness of capturing information loss due to transcription and translation error and identifying broken summaries. Crucially, unlike black-box LLM evaluators or dense embedding metrics, SAUCE is inherently explainable: it maps summary scores to discrete, verifiable facts, allowing users to pinpoint exact hallucinations or omissions. We illustrate how this interpretability helps developers systematically profile LLM behaviors and gives end-users an actionable tool to verify su

---

### [93] Clips2Story: Training-Free Video Storyboarding and Editing Using Multimodal Retrieval-Embedded Generation

**链接**: https://arxiv.org/abs/2611.05992
**作者**: Junnuo Wang, Weihan Xu, Hao-Wen Dong
**来源**: cs.CV cs.AI cs.LG cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video editors often work with large collections of fragmented footage and must select and organize relevant clips into a coherent story. However, many existing video editing and summarization methods assume a temporally ordered source video and aim to preserve its original narrative and temporal structure. In this paper, we introduce Clips2Story, a training-free, LLM-based pipeline that enables users to create keyword-specified short videos from a pool of video clips. Given a pool of clips and a user-specified keyword, we first extract text-based multimodal descriptors for each clip and retrieve the clips most relevant to the keyword. We then provide the textual descriptors of these candidate clips to an LLM, which selects and arranges them into an editable storyboard with connective narrations. Finally, we assemble the selected clips and retrieve accompanying visuals for the narrations to compose the output video. To evaluate the proposed pipeline, we construct a synthetic evaluation 

---

### [94] CRESiST: Self-Enhancing Explorative Policy Learning for Simultaneous Speech Translation

**链接**: https://arxiv.org/abs/2611.06501
**作者**: Chenyang Le, Pei Zhang, Yuxiang Chen, Bing Han, Derek F. Wong, Baosong Yang 等 (7 人)
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simultaneous Speech Translation (SimulST) requires balancing translation quality and latency. While Large Language Models (LLMs) excel in offline translation, current LLM-based SimulST systems predominantly rely on prefix-incremental generation. This paradigm suffers from redundant Key-Value cache recomputation and necessitates external Voice Activity Detection to process unbounded streams. To overcome these bottlenecks, we propose an end-to-end interleaved read-write framework built upon an omni-modal LLM. By interleaving speech chunks and text tokens, our architecture achieves full KV cache reuse, natively supporting segmentation-free, infinite-length inference. Furthermore, to learn optimal streaming policies without rigid offline alignments, we introduce a novel Actor-Critic self-enhancement pipeline. An RNN-T Actor dynamically samples read-write trajectories, while an LLM-based Critic evaluates these paths via intrinsic semantic and latency rewards, distilling the optimal policy b

---

### [95] Beyond Best-Single: Empirical Multi - Model Routing Across Accuracy, Cost, and Routing Overhead

**链接**: https://scholar.google.com/scholar_url?url=https://www.zhafiz.com/research/beyond-best-single.pdf&hl=zh-CN&sa=X&d=16491921318217525070&ei=H8bsaueXBIq86rQP3NyS0Ao&scisig=AIL1Nv5a0AjtiL7B6q6VnDYgnWXB&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=0&folt=kw-top
**作者**: Z Hafiz
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Abstract— Large language model routing attempts to preserve response quality while reducing inference cost by selecting a model for each query. This work evaluates a cost aware GPT 5 relative router under a leakage controlled protocol

---

### [96] A Hybrid Approach for Automated Security Pattern Recovery

**链接**: https://arxiv.org/abs/2611.05823
**作者**: Anh Minh Nguyen, Tuan Dat Tran, Alzubair Hassan, Liliana Pasquale
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Security-by-design emphasises integrating security into software design and development. Security pattern catalogues operationalise this principle by prescribing reusable architectural solutions to recurring security problems. However, recovering their implementations from source code remains challenging because security patterns are abstract, span multiple components, and admit many valid implementations. We present SecPatRec, a hybrid approach for automated security pattern recovery from source code repositories. We treat a security pattern as a reference architecture and frame its recovery as a deductive task: determining which prescribed roles are present, grounding them in code entities, and recovering their interaction sequences. SecPatRec pairs a ReAct-style LLM agent equipped with semantic and lexical code search for role detection and grounding with static code property graph analysis for interaction recovery. We curate a human-validated ground-truth dataset of 100 pattern ins

---

### [97] Retrieval Supersedes Scale: Efficient Log Level Prediction via Multiplex Socio-Technical Context

**链接**: https://arxiv.org/abs/2611.05901
**作者**: Youssef Esseddiq Ouatiti, Mohammed Sayagh, Bram Adams, and Ahmed E. Hassan
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developers insert logging statements in source code to record its execution, and the resulting logs are essential for detecting and troubleshooting system anomalies. A key part of these statements is the log level (e.g., DEBUG, INFO, WARN, ERROR), which determines whether a message is recorded. Choosing it is a trade-off: levels set too low mask important information in production, while levels set too high create noisy logs and extra I/O and storage overhead. Recent work uses Large Language Models (LLMs) with In-Context Learning (ICL) to predict log levels, but typically augments the prompt with randomly sampled examples. We argue that this overlooks the socio-technical nature of logging, where conventions vary by component and development team. Off-the-shelf LLMs using random examples are reported to achieve median AUCs of only 0.56 to 0.76, leaving room for improvement without fine-tuning. In this paper, we propose a retrieval approach for LLM-powered log level prediction that prior

---

### [98] Task-Efficient Agent Evaluation Using Cached Traces

**链接**: https://arxiv.org/abs/2611.06803
**作者**: Ben Johnson and Hayden Helm
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient benchmarking estimates a system's full benchmark performance from a small number of task executions. Standard approaches rely solely on the binary correctness of executions from a collection of already-evaluated reference systems. An agentic system, however, produces a rich trace for each execution that can reveal substantially more about its capabilities. Leveraging this information requires useful trace representations. We propose representing a trace by extracting a structured summary of it with an LLM and embedding the summary with a standard text encoder. These representations preserve correctness- and task-related signal while minimizing the presence of system identity-, model family- and harness-related signals that dominate raw trace embeddings. Given this representation for each task execution from all reference systems, we construct low-dimensional representations of the systems and predict a new system's score from its position among the reference systems. On SWE-b

---

### [99] Do agents need to sleep?

**链接**: https://arxiv.org/abs/2611.02216
**作者**: Ido Haber, Giulio Tononi
**来源**: q-bio.NC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents, which increasingly operate persistently across sessions and accumulate memory through interaction, already exhibit the familiar symptoms of unchecked plasticity: semantic drift, degraded retrieval precision, propagation of stored errors, and saturation of memory capacity. Drawing on the selectionist "ringing, resonance and renormalization" (RRR) account of sleep, we propose that each of its three phases maps onto an operation feasible in digital memory architectures. Engineers building stateful agents, meanwhile, are independently rediscovering the problems sleep evolved to solve: what to forget, and when to do the forgetting. From this we derive the falsifiable prediction that selectionist consolidation will outperform instructionist alternatives as memory stores grow large. The core claim concerns the nature of continuous learning itself: plasticity has a price, and for any system that learns continuously under finite capacity while coupled to its environment, that 

---

### [100] Mind Control of LLMs via Closed-Loop Stimulation: Out-of-Distribution Robustness

**链接**: https://arxiv.org/abs/2611.06418
**作者**: Kasra Fallah, Rudramani Singha, Hannah Ghanei, Paul Sajda, James Anderson, Erfan Zabeh
**来源**: q-bio.NC cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brains and large language models need not be considered equivalent systems to reveal an interpretable commonality: both exhibit high-dimensional, nonlinear dynamics whose behavior can only be modeled imperfectly. This creates a shared challenge whenever we seek to intervene in their dynamics. A controller may either rely on a model identified around a particular operating regime and risk failure as the system moves away from that regime, or explicitly account for uncertainty and a changing internal state. Neurostimulation has confronted an analogous problem for decades. The limitations of fixed, open-loop stimulation have motivated closed-loop and state-dependent approaches that condition intervention on the ongoing state of the neural system. Inspired by this principle, we formulate LLM steering as a feedback-control problem in which the network's internal state, rather than a fixed intervention alone, determines how the system is perturbed. We further account for the mismatch between

---

### [101] AmbiHTMLBench: A Benchmark for HTML-based Visually Rich Document parsing

**链接**: https://arxiv.org/abs/2611.06449
**作者**: Boyu Niu, Yingjie Xiong, Shurui Li, Linhan Pang, Yuntong Zhang, Han Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional document parsing systems use Markdown as their output representation, which is effective for linear text but does not fully preserve fine-grained spatial structure, table geometry, visual hierarchy, or rendering semantics. We show that HTML is advantageous for heterogeneous and layout-sensitive documents whose representations must remain editable, inspectable, and reusable, and introduce AmbiHTMLBench to systematically study this setting. In this benchmark, given a real-world document, a model must recover executable HTML that preserves its content, organization, and visual appearance. The benchmark contains 1,115 diverse pages with structured annotations and evaluates predictions in two different ways: The objective protocol aligns ground-truth and predicted rendered blocks and measures table fidelity, page-level text error, and a two-dimensional layout consistency; a complementary reference-anchored protocol measures perceived fidelity by aligning LLM judges with human pr

---

### [102] Decision Models as Scalable Economic Surrogates that Capture Human Variation

**链接**: https://arxiv.org/abs/2611.05553
**作者**: Maxime Saxena, Fabio Caccioli, R. Maria del Rio-Chanona
**来源**: econ.GN cs.AI cs.MA q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision Models (DMs), a new class of AI models, give fast responses and return a probability distribution over a fixed set of options. These properties make them candidate human surrogates in economic simulations and surveys, a role increasingly filled by Large Language Models (LLMs), which are costly at scale and under-represent the variation in human behaviour. We present a first evaluation of DMs as human surrogates in economics, comparing 10 DMs with 8 LLMs in three economic settings: a household spending survey on consumption, several classic economic games and a labour-market field experiment. Frontier DMs, those that score highest on general decision-making benchmarks, reproduce the variation in human responses more closely than LLMs in all three settings. They capture the modal human response as well as LLMs in the spending survey, but less well in the economic games. Frontier DMs are also roughly ten times faster than the fastest LLM and can be over a hundred times cheaper. T

---

### [103] Grounding in the Dark: Text-Only Training for Zero-Shot Video Temporal Localization

**链接**: https://arxiv.org/abs/2611.06149
**作者**: Divyanshu Mishra, Sabine Sternig, Rakshith Shetty, Erhan Gundogdu
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video-LLMs are typically trained on paired video-text data for temporal tasks, yet collecting precise temporal annotations and training on large-scale video datasets are both costly. We investigate whether a text-only LLM, with no vision-language pretraining, can be trained on textual video descriptions alone to perform temporal grounding and receive video only at inference time. This setting removes paired video data from training altogether and is a step toward training multimodal models without paired annotations. We generate a 134K-example corpus of textual sequences with up to 100 time steps, adapt Qwen3-8B with LoRA on CLIP or LLM2CLIP text embeddings, and evaluate on Charades-STA and QV-Highlights without training on videos from either benchmark. LLM2CLIP, whose text encoder supports longer inputs, represents detailed descriptions better than CLIP (61.54 versus 53.86 mtIoU on Temporal-TextVid) and transfers them better to video. Still, replacing text with frame embeddings at inf

---

### [104] Give the Drafter a Second Chance to Guess: Parallel Reconsideration for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.05724
**作者**: Hoang Anh Duy Le, Huibing Dong, Alireza Khadem, Ziteng Sun, Xiang Song, Yizheng Huang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference with a small drafter, whose per-guess acceptance rate determines the achievable speedup. Feature-level drafters share a design choice: every token, easy or hard, is drafted under a single forward pass. Many of the tokens the target rejects are ones the drafter is itself unsure about yet the target answers decisively. To address this, we introduce Parallel Reconsideration: guided by its own uncertainty, the drafter reconsiders its hesitant guesses with extra passes that run in parallel with the one-pass draft, adding negligible latency. A co-designed training recipe and serving-time drafting algorithm append these reconsidered guesses to the original draft tree as refined candidates. Across models and benchmarks, on average, Parallel Reconsideration improves over the baselines by 5.3% to 10.2% on acceptance length and by 3.5% to 9.2% on speedup.

---

### [105] LegalEvolver: Agentic Legal Judgment Prediction via Rubric-Guided Self-Evolution

**链接**: https://arxiv.org/abs/2611.06381
**作者**: Xinyu Yang, Jiejun Tan, Chenlong Deng, Chenghao Zhang, Tongyu Wen, Zhicheng Dou
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based agents develop, they have been increasingly applied in the legal domain. Legal Judgment Prediction~(LJP) requires models to conduct multi-step reasoning and external legal evidence retrieval. Existing legal search agents' performance is often constrained by the quality of retrieval queries. They often formulate queries directly from the initial user request, overlooking latent legal issues and legally salient details. To address this issue, we propose \emph{LegalEvolver}, a query optimization framework specifically designed to generate legally informative queries for LJP-oriented retrieval. Sampling high-quality optimized queries and their corresponding search trajectories is challenging, as relying solely on unguided high-temperature rollouts is both inefficient and constrained by the model's initial capabilities. We therefore heuristically optimize queries as seeds, improving the efficiency of trajectory generation. Furthermore, we summarize rollout experience into rubri

---

### [106] PEARL: Prediction Error-Adaptive Regularized Learning for Selective Forgetting under Partial Preference Drift

**链接**: https://arxiv.org/abs/2611.05842
**作者**: Rashmi Gangadharaiah and Balakrishnan Narayanaswamy
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> User preferences shift as needs, context, and tastes evolve. This matters for personalized recommendation, LLM response generation, and RLHF-trained reward models, which can become miscalibrated as preferences drift. Existing non-stationary bandit methods forget uniformly across all dimensions, but real preference shifts are typically partial: some dimensions go stale while others remain valid. Neural contextual bandits accumulate confidence monotonically via the Gram matrix, with no mechanism to direct uncertainty where predictions have gone wrong. We propose PEARL (Prediction Error-Adaptive Regularized Learning), which reverses the Gram update along feature directions where predictions are surprisingly wrong, while leaving confidence intact elsewhere. We prove that (i) any non-adaptive policy suffers linear regret after a preference shift, (ii) no fixed exploration rate achieves low regret in both stationary and non-stationary regimes, and (iii) PEARL's cumulative regret scales with 

---

### [107] When File Ingestion Misleads Language Models: Measuring and Mitigating Divergences in Office Documents

**链接**: https://arxiv.org/abs/2611.05806
**作者**: Penghui Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Office documents are now routinely uploaded to large language models (LLMs) for processing. However, an LLM does not always see what a human sees, because it typically reads the text that an extractor produces from the document's underlying Office Open XML (OOXML) files. Depending on the implementation, extractors differ in which OOXML parts they read and how they interpret them, so their output can differ from what Office applications display. For example, by slightly shifting the positions of text boxes on a slide, an adversary can swap the order in which the model reads them while the slide looks unchanged. We show that this extraction divergence is an attack surface for LLM applications. In this work, we first measure what an adversary can exploit by analyzing the widely used extractors that LLM applications rely on. By combining static source code analysis with dynamic analysis, we identify 19 OOXML channels where extractors read content a human cannot see and 12 where they drop c

---

### [108] Same Method, Different Task: What the Bitter Lesson Does Not License in Social Simulation

**链接**: https://arxiv.org/abs/2611.05717
**作者**: Justin Downes, Robby Milletich, Newel Hirst
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The bitter lesson holds that general methods leveraging computation defeat hand-encoded domain knowledge. We argue it carries a condition its popular reading omits: in every case Sutton cites, the general method was scaled against the same task the domain engineering was solving. Social simulation substituted across tasks instead, replacing hand-built agents with an artifact optimized for predicting text. The move is bitter-lesson-shaped, but the lesson does not license it. Prediction is a solitary act: the predictor bears no consequences from the interaction it models. Cooperation, defection, and norm enforcement are phenomena of interested parties; they do not exist for a disinterested observer at any scale. What is missing is not emergence, which LLM populations already show, but stakes. We show that several anomalies reported in prior work (excess cooperation that predates alignment training, collective agreement without individual fidelity, and population homogeneity) follow from 

---

### [109] DARE: Difficulty Analysis for Repair Enhancement

**链接**: https://arxiv.org/abs/2611.05797
**作者**: Jikwang Lee, Seungwook Jung, Jaechang Nam
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based coding agents are primarily evaluated by their solve rates. However, this metric does not reveal how difficult the solved tasks are or account for differences intask difficulty across benchmarks. Determining the difficulty of individual tasks by repeatedly running multiple agents is costly, while a predicted difficulty score alone provides limited guidance on what support an agent needs. To address these challenges, we propose DARE (Difficulty Analysis for Repair Enhancement), which integrates repair-task difficulty measurement, prediction, feature-group contribution analysis, and task-specific repair support. We define continuous task difficulty as the observed failure rate across multiple coding agents. The DARE difficulty model predicts this difficulty using 151 static features extracted from benchmark artifacts. The framework also analyzes the contributions of seven Repair-Task Feature Groups to identify the characteristics most salient to each task and uses this informat

---

### [110] When Does Better Confidence Improve a Knowledge-Graph Audit?

**链接**: https://arxiv.org/abs/2611.05877
**作者**: Zehao Lin, Kai Chen, Xixuan Hao, Erenkai Zhu, Chunyu Li, Helan Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Confidence estimates guide human review in LLM-built knowledge graphs, but better error prediction can yield little improvement in an audit. We study this gap through repairability, selection headroom and label validity. Modelling non-adaptive auditing as budgeted covering, we characterise the minimal decision-relevant error statistics and bound the regret of scalar-preserving first-order planning by a structural mass $\Delta^{\mathrm{cl}}$. We simulate ideal repair against benchmark-aligned labels for five extraction configurations and two cross-document graphs on Re-DocRED, followed by frozen confirmation on test and replication on 500 hash-selected training documents. On the held-out cross-document graphs, an error-rate $\times$ fan-out queue leaves 3.98-4.74 percentage points more errors than a joint model with the same actions. By comparison, opening shared actions for that joint planner reduces residual errors by 0.89-1.43 points relative to its own fact-only plans, in point esti

---

### [111] Smartphone-Aided VR Exergames for HIIT: Gamifying Fitness with Real-Time Pose Estimation

**链接**: https://arxiv.org/abs/2611.06734
**作者**: Abhiram Kothagundu, Pheelip Pritipal Raipure, Abhijit Chandrakant Patil, Himangshu Sarma, Christian Eichhorn, David A. Plecher 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper introduces an innovative virtual reality (VR) exergame system designed to gamify High-Intensity Interval Training (HIIT) workouts through 11 predefined combo moves, including squat-punch combinations, bilateral arm strikes, and diagonal stretch combos. Unlike conventional tracking methods that often rely on wearable motion capture suits or limited headset-based sensors, our system uses a standard smartphone camera placed on a tripod to capture full-body movement. This approach offers a cost-effective and scalable alternative, particularly well-suited to the fast, dynamic motions typical of HIIT routines. The smartphone footage is processed in real time using a pose estimation algorithm, with extracted biomechanical data analyzed by a backend server built on the Model Context Protocol (MCP), Anthropic's open standard for connecting AI models to structured data sources and tools, and a GPT-4o large language model. The system generates personalized assessments of form accuracy,

---

### [112] GREP: Grounding Generated Room Evaluation in Principles

**链接**: https://arxiv.org/abs/2611.05802
**作者**: Mohan Cao, Yongsen Mao, Chucheng Xiang, Zhongyuan Liu, Zhihang Zhong, Haiping Wang 等 (7 人)
**来源**: cs.CV cs.AI cs.GR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent LLM-centric advances can generate attractive furnished rooms by selecting and arranging assets. Yet evaluation remains limited to specific perspectives or predefined questions, failing to reflect overall scene quality. To address this pressing need, we introduce GREP. Its core is a focus shift from defining specific questions to establishing a three-tier evaluation philosophy: basic physical validity checks whether a scene obeys physical constraints; visual coherence concerns compatibility in object scale, style, and composition; and, at the highest level, human-use logic requires object arrangements to align with everyday human habits. Guided by these principles, an evaluation agent autonomously and adaptively identifies issues from scene context, gathers evidence, and produces scores and reports. This supports scene-specific issue discovery and reliable judgments. Experiments show that (1) GREP achieves 87% agreement with human majority preferences, substantially outperforming

---

### [113] Agents, Think Only When it Helps

**链接**: https://arxiv.org/abs/2611.05709
**作者**: Min-Seon Kim and Seungdong Yoa and Sanghyu Yoon and Ye Seul Sim and Suhee Yoon and Dongmin Kim and Jung-Eun Kim
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agent distillation transfers agentic capabilities to student models by training on complete teacher trajectories that typically interleave thoughts and actions. We question how critical thought supervision is for agents' ultimate action performance. To answer this, we disentangle their impacts by independently perturbing teacher thoughts and actions during distillation. On widely adopted agent benchmarks across model scales, altering or discarding thoughts has little effect on student performance. We find, however, that thought supervision becomes important when information about the thought is not disclosed in the corresponding action during training. By identifying such discrepant cases, our findings challenge the common practice of distilling entire teacher trajectories for LLM agents, and offer a new insight that thought supervision can be a discernible choice for efficiency depending on whether the information of thought is disclosed in the action.

---

### [114] TACT: A Pragmatic Approach to Qualitative Analysis with an AI Council

**链接**: https://arxiv.org/abs/2611.05702
**作者**: Rudrajit Choudhuri, Christian Bird, Carmen Badea, Anita Sarma
**来源**: cs.SE cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Qualitative data can tell software teams what their stakeholders need, yet rigorously analyzing thousands of qualitative responses takes expert time that few teams can afford or justify. Teams therefore often face a false choice: leave the responses unanalyzed, or hand them to a large language model and accept its interpretation and judgment. In this paper, we take a pragmatic approach to AI-assisted qualitative analysis and present TACT (Traceable AI Council for Thematic analysis), a procedure that enables such analysis at scale while keeping teams in control of interpretation and judgment. TACT comes in two variants: TACT-Lite, the core AI council procedure, and TACT-Full, which adds adversaries (models from other model families that critique each model's output) and a decision model that surfaces high-uncertainty code assignments. We evaluated TACT on an independent dataset of 256 Stack Overflow threads qualitatively coded by other researchers. Against their labels, TACT's candidate

---

### [115] A Cracked Mirror: How People Perceive Gender Performance by Large Language Models

**链接**: https://arxiv.org/abs/2611.06393
**作者**: Faezeh Fadaei and Jenny Carla Moran and Taha Yasseri
**来源**: physics.soc-ph cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How do large language models (LLMs) perform gender under zero-shot prompting, and how do people interpret those performances in conversation? Drawing on gender performativity, we examine how gendered meanings emerge through generated language, conversational context and human interpretation. In a preregistered randomised online experiment, 1,060 participants each had five short conversations with an LLM. We used minimal prompts to elicit performances from "very masculine" to "very feminine" and asked participants to rate their partner's perceived gender after each conversation. Mean ratings shifted in the direction of the prompts, but ratings at the extremes were closer to the midpoint than the prompt labels implied. When prompted to perform as "neither masculine nor feminine", the models were perceived as slightly masculine on average. Ratings varied across models and conversation topics. Women and men gave similar ratings at the extremes, but women rated the models as more masculine 

---

### [116] PAYWORTHY: Can LLMs Predict Which Freelance Jobs an AI Agent Will Complete?

**链接**: https://arxiv.org/abs/2611.05759
**作者**: Mohammad Reza Rezaei, Dingxian Wang, Brett Levert, Celeste Fejzo, Andrew Rabinovich, Zhao Chen
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Before an AI agent takes on a paid job, someone has to judge whether it is likely to succeed. We test whether frontier language models can make this call before any attempt. We propose PAYWORTHY which contains 1{,}494 real freelance job postings, sampled from 18.8M postings made between 2020 and 2026 on a freelancing platform. An agent attempts each job from the posting alone in a single run, and an LLM judge acting as the client decides whether to accept the work. We ask 18 models to forecast how likely the agent is to succeed and measure how well each model's forecasts rank the accepted jobs above the rejected ones (AUC, where 0.5 is a random ranking). The answer depends on how the agent is described. Told what the agent cannot do, every model ranks the jobs well (AUC 0.66--0.86). Told instead that it is a generic agent with a browser and code execution, the same models rank the same jobs about as well as a random ordering (0.45--0.56). These results hold under judges from four other

---

### [117] Mass Producing Training Data with Surprising Side Effects

**链接**: https://arxiv.org/abs/2611.06324
**作者**: Yaowen Ye, Jacob Steinhardt, Sarah Schwettmann, Cassidy Laidlaw
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training data can have unexpected side effects on language model behavior outside the training domain: insecure code data can induce broad misalignment, and outdated bird names can induce a 19th-century persona. Understanding such generalization is hard because only dozens of isolated examples exist, each constructed by hand or discovered by accident. We propose automatically discovering such datasets with surprising side effects (DSSEs). We define three objectives for DSSEs: they should (1) elicit a target behavior, (2) read like ordinary post-training data, and (3) be surprising to human auditors reading the data. We operationalize each with LLM judges, and search for high-scoring datasets via evolution, reinforcement learning, and subliminal learning approaches. After re-scoring and filtering with held-out metrics, our pipeline produces a collection of 6,575 DSSEs across 8 behaviors, many of which generalize across model families and sizes. We find our automated metrics track ML res

---

### [118] Persona Perspectives: Adopting Viewpoints Reorganizes Representations in LLMs

**链接**: https://arxiv.org/abs/2611.06848
**作者**: Austin C. Kozlowski, Avital Mintz, Madison Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Common methods for monitoring features in large language models (LLMs) such as linear probes and sparse autoencoders (SAEs) assume that features maintain a consistent representation across contexts. LLMs, however, can flexibly adopt different perspectives or "personas" that suggest different underlying systems of conceptual relations. In this paper, we examine whether prompting an LLM to adopt a persona alters the representational geometry of the model's latent space. We extract representations of over 9,000 common words and 33 semantic axes from models adopting liberal and conservative political personas and compare these against two neutral baselines. We find that persona conditioning systematically alters both the projections of words onto semantic axes and the alignments among the axes themselves in directions consistent with the specified ideology. We then test the implications of this reorganization for two safety-relevant features: truthfulness and morality. Linear probes, SAE-b

---

### [119] Replicability, Reproducibility, and Robustness in Political and Social Science Research with Large Language Models

**链接**: https://arxiv.org/abs/2611.06639
**作者**: Joan C. Timoneda, Sebasti\'an Vallejo Vera
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This chapter addresses the central reproducibility problem of research with large language models. LLM output is probabilistic and varies across models and versions, which can have significant effects on downstream statistical results. The chapter distinguishes between replicability, reproducibility, and robustness, and proposes a probabilistic standard based on the distribution of results, not identical outputs. It introduces a standardized prompt script, tests within-model variation for encoders and decoders, and develops error-structure analysis to diagnose where models err and whether their errors align. Using three datasets, the chapter shows that measurement choice can reverse the sign of downstream regression coefficients. Existing design-based corrections with gold-labeled subsamples restore validity, but come at the cost of estimate precision. The main contribution of the chapter is a stacked ensemble of open-weight models that improves precision in the correction step while r

---

### [120] When to Ask, When to Answer: Strategic Clarification for Ambiguous Reference Resolution in Dialogue

**链接**: https://arxiv.org/abs/2611.05517
**作者**: Ibrahim Khebour and Nikhil Krishnaswamy
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For humans, referential disambiguation is a collaborative process involving clarification questions asked when they will meaningfully change the outcome. However, large language models (LLMs) have been shown to be biased toward premature answering, preferring definite single-turn responses over more clarification exchanges. In this paper, we study the problem of "strategic clarification" -- asking clarification questions in a reference game when their answers will narrow the set of candidate referents. We construct a controlled test environment from the SIMMC 2.1 dataset that records how many questions each ambiguous reference needs to be successfully resolved, and examine how baseline LLM behavior and common post-training methods ask clarifying questions vs. attempt to answer the referent. We also propose BACE (Belief-Aware Critic with Epistemic tracking), a lightweight action chooser method on top of a frozen LM backbone, and show that BACE more consistently chooses the optimal numbe

---

### [121] Factorized MLLM Embeddings for Composed Image Retrieval

**链接**: https://arxiv.org/abs/2611.05193
**作者**: WonJun Moon, Seongchan Kim, Dahun Kim, Seungryong Kim
**来源**: cs.CV cs.IR
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Phase-wise MLLM Tuning for Multi-framework WebUI Code Generation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.01692&hl=zh-CN&sa=X&d=15413531811594300565&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv6hi7RgRVOGL3T5dsLUQFn8&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=0&folt=kw-top
**作者**: H Ma, L Li, C Wang, H Sui, J Gao - arXiv preprint arXiv:2611.01692, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper studies supervised fine-tuning for multi-framework WebUI code generation and proposes a phase-wise MLLM tuning method … We freeze the MLLM ’s parameters Θ and introduce adapters for k frameworks with parameters W

---

### [123] Multi-View Factor Blocks as a Front End for MLLM -Based Multimodal Causal Discovery

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3DytJnOCpyCw&hl=zh-CN&sa=X&d=13024152674236069282&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv5i-OXLSYfLrIIVUyfX7veU&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=1&folt=kw-top
**作者**: H Lee, S Choi, M Kim, HS Choi - Machine Learning for Health 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We compare against our 209 own reproduction of MLLM -CD rather than its pub- 210 lished numbers. The comparison isolates the pair- 211 selection front end: both methods run one graph- 212 discovery iteration with identical quantification and 213

---

### [124] Think in 360 {\deg}: Benchmarking and Bootstrapping Panoramic Video Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.42082&hl=zh-CN&sa=X&d=293098769179102316&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv68D7HPdp5y4xDAtzINjquC&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=7&folt=kw-top
**作者**: L Lu, L Zou, X Mao, J Lv, Z Li, L Dong 等 (9 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In the first stage, we fine-tune the general video MLLM on PanoVideoCoT. Given the original ERP video and the multiple-choice question, including its options, the model learns to generate the synthesized CoT followed by the answer. The CoT

---

### [125] Embodied AI for Radio Mapping: From Solo to Swarm

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.00770&hl=zh-CN&sa=X&d=258050099638206511&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv4jvwYQlUks1h_ZxHTeefwX&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=8&folt=kw-top
**作者**: S Zhuang, W Lu, Z Zhang, Z Huang, Z Zhang, R Zhang… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In the upper layer, human interaction with an MLLM translates the mapping objective into team tasks … Mission Planning: The team planner uses an MLLM to combine human instructions with … We discussed how MLLM -assisted planning

---

### [126] ReVEAL: Eliciting Role-Aware Latent Visual Evidence from MLLMs for Reasoning Video Object Segmentation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.41257&hl=zh-CN&sa=X&d=1708900603319935455&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv5lJ2iJeJOzW3r-626MEFDf&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=2&folt=kw-top
**作者**: Z Bao, C He, L Zhang, Z Xu, Y Fu - arXiv preprint arXiv:2610.41257, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> role-aware latent visual evidence from MLLM reasoning to directly guide segmentation. ReVEAL … We train the MLLM to perform VET-augmented reasoning on our constructed ReVEAL-47K … -aware latent evidence from MLLM reasoning to

---

### [127] WebOverlay: High-Throughput Vision-Only Distillation for Extreme Aspect-Ratio Web Overlay Detection

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.41037&hl=zh-CN&sa=X&d=4227694861355660930&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv7j0cUYD-ddRQW-V1Hapzra&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=9&folt=kw-top
**作者**: J Huang, J Ding, L Yu, Z Li - arXiv preprint arXiv:2610.41037, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We address this with a vision-only student distilled from an MLLM teacher. Our renderer expands the viewport to the full document height, so overlays pinned with position: fixed or sticky land at the top, center, or bottom of the page. The student

---

### [128] Learning to Group and Order: Cross-Instance Self-Supervised RL for Vision-Centric MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.00892&hl=zh-CN&sa=X&d=16891454713624504872&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv5mUMKp6s0G337Jhbvj-erN&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=6&folt=kw-top
**作者**: S Yang, HT Yu, XS Wei - arXiv preprint arXiv:2611.00892, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> (GO-SSL), a cross-instance jigsaw framework for visioncentric MLLM post-training. Given two visual instances, GO-SSL mixes their local … Across diverse benchmarks, GO-SSL consistently improves over the base MLLM and prior self-supervised post-training

---

### [129] Entropogram-guided Visual Realignment Decoding: Capturing the Rhythm of Multimodal Reasoning

**链接**: https://arxiv.org/abs/2611.06415
**作者**: Jiaqi Deng, Zhe Fu, Yakun Chen, Dichang Zhang, Zonghan Wu, Xiaoshui Huang 等 (8 人)
**来源**: cs.CV cs.MM
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have demonstrated remarkable progress on cross-modal reasoning tasks, yet they continue to suffer from hallucinations in long-chain reasoning processes. In this work, we revisit hallucination in MLLMs from the perspective of reasoning generation dynamics. We argue that entropy is not merely a static measure of uncertainty but a structured signal that reflects how modality information is integrated throughout decoding. Through systematic analysis, we identify two characteristic entropy patterns associated with hallucination behaviors: (1) a generally high-confidence regime corresponds to premature convergence to inappropriate multimodal interactions; and (2) local abrupt entropy transitions are associated with reasoning instability and hallucination onset. Building on these observations, we propose an entropy-aware self-introspective framework for MLLM reasoning. Our method continuously tracks entropy dynamics during decoding and performs targete

---

### [130] Beyond Multimodal Emotion Conflict: Temporal Context-Aware Hidden Emotion Detection with Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.01943&hl=zh-CN&sa=X&d=9467237567764076511&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv4XmfoBUMUqdBR7a-ddApc3&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=4&folt=kw-top
**作者**: Y Wang, J Zhou - arXiv preprint arXiv:2611.01943, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Recent studies have specifically examined emotional conflicts among modalities in MLLM -based … MLLM tuning. The trained network is used to provide appropriate fused representations as the inputs, and can be seen as the input embedding

---

### [131] Multimodal In-Context Learning with Explicit Rule Induction

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.41754&hl=zh-CN&sa=X&d=17029684708633770820&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv6qu7gCDflqgOnduqMJ_Zjk&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=5&folt=kw-top
**作者**: Y Li, X Jiang, Y Xue, C Zhao - arXiv preprint arXiv:2610.41754, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Our goal is to fine-tune an MLLM that, given a support set and a query, can first explicitly induce the underlying rule shared by the episode, and then apply the induced rule to predict the final answer. Concretely, the model is trained to perform

---

### [132] DamageRAG: Benchmarking and diagnosing multi-hop retrieval-augmented reasoning for structural damage inspection

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S095070512601957X&hl=zh-CN&sa=X&d=3802266181471492149&ei=H8bsaovKC_C96rQP1rXIyQE&scisig=AIL1Nv7UMWypj7QQVM8DRpoi3GJE&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=3&folt=kw-top
**作者**: Z Hu - Knowledge-Based Systems, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> DamageRAG retrieves over MLLM -generated structured Damage Reports by field matching and routes quantitative queries to … A three-layer diagnosis separates retrieval, reasoning and perception failures; perception dominates: under MLLM -generated

---

### [133] Quantifying Trait-State Hierarchy in EEG Foundation Model and Signal Processing Embeddings

**链接**: https://arxiv.org/abs/2611.05652
**作者**: Anusha Madapura, Aditya Kommineni, Shrikanth Narayanan
**来源**: cs.AI cs.LG
**匹配关键词**: EEG, Brain-Computer Interface, Foundation Models, EEG Foundation Model
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) measures brain activity through recording electrical potentials of the scalp. EEG recordings capture two distinct sets of characteristics in the signal: (1) \emph{Traits} -- information that remains relatively constant over the course of a recording session, such as subject identity, age, and sex; (2) \emph{States} -- signatures that encode responses to external stimuli, including visual, auditory, and motor information. There is limited understanding of how different EEG modeling features (signal processing and foundation models) encode state and trait characteristics. In this work, we quantify state- and trait-level features captured by EEG embeddings using a hierarchy metric and kNN purity on Brain-Computer Interface dataset trials, and find that a majority of EEG features form a macro-trait hierarchy (embeddings form trait-level clusters with micro-states within). Our linear probe results indicate that this hierarchy structure leads to suboptimal state 

---

### [134] EEGDash Corpus: A Training-Ready Public Corpus for EEG Foundation Models

**链接**: https://arxiv.org/abs/2611.06356
**作者**: Kuber Shahi, Bruno Aristimunha, Arnaud Delorme
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for electroencephalography (EEG) are pretrained on tens of thousands of hours of recordings, and their accuracy grows with that amount. Such data is hard to assemble. The largest sources are clinical archives that cannot be redistributed, and the public sources are spread over several archives, file formats, and licences. We release eegdash-corpus-v0, a training-ready corpus of 77 public EEG datasets, as the gated Hugging Face dataset EEGDash/eegdash-corpus-v0 with the SHA-256 of every file. REVE, the largest published EEG foundation model, names 89 datasets as its pretraining corpus. Twelve cannot be redistributed: four clinical archives that hold 82% of its hours, and eight under no-derivatives licences. The corpus holds the 76 others that REVE's sampling rate allows and one more from REVE's release card: 77 datasets, 14,075 hours from 7,272 subjects, 5.0 million 10-second samples and 6.21 billion tokens per epoch. Every dataset is fetched through EEGDash, converted

---

### [135] Recasting Visual Language Models as EEG Foundation Models for Clinical Neurodiagnostics

**链接**: https://arxiv.org/abs/2611.05538
**作者**: Xin Zhou, Elena Sergeeva, Nan Bi, Wenyu Song, Lijun Yin, and Hao Deng
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historically automated electroencephalography (EEG) systems was done using task-specific supervised models trained on purposely annotated data. A more recent modeling paradigm relies on creating a unified representation, or a 'foundation model', for multiple modality-specific tasks through large-scale domain-specific pretraining on the unannotated EEG signal. The quality of this unified representation directly depends on the availability of the modality-specific datasets. At the same time, generalist Vision Language Models (VLMs) exhibit broad few-shot learning capacities as well as good fine-tuning adaptability to different visual and language tasks. Can VLMs learn how to read and interpret EEG visually, emulating to a degree the way human clinicians inspect the EEG patterns? In this work we make a case that they can: we show that generalist VLMs without large-scale EEG pretraining perform competitively across a collection of clinical neuro-diagnostic tasks, can adapt to different tas

---

### [136] LaBraM at Scale: Scaling Data and Models for EEG Pretraining

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.03165&hl=zh-CN&sa=X&d=14044756036176880078&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv6W-414jHXIyUgAnEeUn_0H&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=3&folt=kw-top
**作者**: JY Pan, R Yin, BL Lu, D Li, WL Zheng, Y Wang - arXiv preprint arXiv:2611.03165 等 (7 人)
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> LaBraM, an early EEG foundation model, demonstrated that large-scale EEG pretraining … We train ten encoders with 5.8 million to 1.97 billion parameters on three EEG collections … , 3.61 percentage points above the strongest baseline EEG

---

### [137] Adapting Sleep Foundation Models for Dense Sleep Spindle Localization

**链接**: https://arxiv.org/abs/2611.06546
**作者**: Alexis Bollengier, Abel D\'iaz Berenguer, Olivier Pallanca, Andr\'e Anjos, Hichem Sahli
**来源**: eess.SP cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting sleep foundation models to dense electroencephalography (EEG) event localization is challenging because multi-second representations may not preserve sufficient temporal detail for precise boundary recovery. We address sleep spindle localization by adapting a frozen SleepFM encoder with a local time-frequency pathway that preserves spindle-relevant spectral content and intra-token position. The local representation drives localization, while residual cross-attention incorporates SleepFM temporal context. Dense predictions are obtained through localized token-to-sample reconstruction and temporal refinement. Tested on the Massive Online Data Annotation (MODA), the proposed model achieves an event-level $F_1$ of $0.8080 \pm 0.0040$ at IoU 0.2 across six folds. Ablations show that localization primarily depends on local spectral and sub-token temporal information, while the pretrained representation provides complementary context. These results indicate that dense adaptation bene

---

### [138] AutoBCI: Forecast-Guided Agentic Neural Architecture Discovery for EEG-Based Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2609.35456
**作者**: Muyun Jiang, Yi Ding, Wei Zhang, Jinbo Chen, Chenyu Liu, Zhenjie Yang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] FPGA acceleration of CNN-BiLSTM for EEG -based sleep staging featuring FFT-based non-unit stride fast convolution

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.00669&hl=zh-CN&sa=X&d=1948909886501911154&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv5QZJEIVho8b1H56A1Lo6GP&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=6&folt=kw-top
**作者**: A Zhou, Y Xu, C Chen, J Yen, W Zheng, M Zhao 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> many other EEG -based wearable applications. To address these challenges, we present a DL accelerator for single-channel EEG -based … , this work targets a class of workloads commonly found in EEG -based applications that require long temporal

---

### [140] Systematic Review of Machine and Deep Learning in EEG Alzheimer's Detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0925492726002362&hl=zh-CN&sa=X&d=1824181363742599867&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv4jaWVoAKNHZrW_A28jB-qG&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=0&folt=kw-top
**作者**: ANL Kumar, VS Vetukuri, VMNSS Venkata, KR Gupta… - Psychiatry Research …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Alzheimer’s disease is the most prevalent neurodegenerative disease, resulting in progressive memory loss in people. It has a significant impact on the population and the global healthcare system. Disease acquisition is a major concern due to the

---

### [141] EEG -HealthLLM: Hierarchical Adaptation of Large Language Models for Unified Heterogeneous EEG Health Assessment

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.01652&hl=zh-CN&sa=X&d=2765496595090073895&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv7D3gfKZ8kfmGJ8FGGHG7Us&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=2&folt=kw-top
**作者**: R Ma, J Dang, R Lin, B Wang, J Zhao, W Ma… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG -HealthLLM, a unified and parameterefficient framework for heterogeneous EEG health assessment. We introduce an Asymmetric Hierarchical Adaptation Strategy: task-specific EEG … We further establish EEG HealthBench by reorganizing five

---

### [142] PINR-ESI: Physics-Informed Self-Supervised Implicit Neural Representation Framework for EEG Extended-Source Imaging

**链接**: https://arxiv.org/abs/2611.06700
**作者**: Zhiyong Zhou, Sheng Liao, Youshen Xiao, Xiaolin Li, Yakang Dai
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG extended-source imaging aims to localize active cortical regions and characterize their spatial extent, yet supervised inverse networks typically depend on synthetic EEG-source pairs and may be sensitive to synthetic-to-real mismatch. We propose a physics-informed self-supervised implicit neural representation (INR) framework for spatial source reconstruction without paired source labels or simulation-based supervised pretraining. The lead field matrix encodes the source-to-sensor volume-conduction model and constrains the INR through agreement between predicted and measured EEG. Cortical current density is modeled as a continuous coordinate-conditioned field. A classical inverse estimate provides warm initialization and spatial constraints on source activity, while patch-integrated projection maps the field to discrete source coefficients for forward modeling. Simulations with varying noise levels, source counts, and source extents showed the clearest advantage in identifying acti

---

### [143] ERIA: An Instruction-Optimized Agent for Clinical EEG Reporting

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.01394&hl=zh-CN&sa=X&d=5524041645048866484&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv7geRaVYbqWvebbsLeO8DAM&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=5&folt=kw-top
**作者**: A Sameh, G Kuruppu, N Wagh, B Brundy… - arXiv preprint arXiv …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ( EEG Reporting and Instruction-Optimized Agent), a locally deployable EEG interpretation framework that enables a single 27B language-model controller to analyze whole-recording EEGs … clinically relevant domains reflected in EEG

---

### [144] Thought-deciphering via hierarchical EEG-to-text alignment

**链接**: https://arxiv.org/abs/2611.03623
**作者**: Xiaopeng Mao, Morten M{\o}rup, Xin Xu, Sang Wan Lee, Sadasivan Puthusserypady
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] Federated learning-driven quantum models for EEG -based neurological disorder classifications

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426022433&hl=zh-CN&sa=X&d=15997781946625232751&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv6SPAUjFCqdgBX_q1Yop4jd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=7&folt=kw-top
**作者**: M Umair, B Song, P Wen, Y Li - Biomedical Signal Processing and Control, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Electroencephalography ( EEG ) enables non-invasive detection of neurological … This study, therefore, presents FL framework for EEG classification using DL models and … Two public datasets eg, OpenNeuro and TUH EEG Corpus

---

### [146] Thought-deciphering via hierarchical EEG -to-text alignment

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.03623&hl=zh-CN&sa=X&d=8078523013351827987&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv4mGAdjdNbVqquoDVQnKmRI&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=9&folt=kw-top
**作者**: X Mao, M Mørup, X Xu, SW Lee, S Puthusserypady - arXiv preprint arXiv:2611.03623, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> can be created between text and EEG , and how such a space contributes to an EEG -to-text translation task. We tackle the EEG -to-text … each EEG -text pair, so a sentence can be retrieved using its EEG as input. In short, our main contributions

---

### [147] A Lightweight Hybrid-Attention Conformer for Affective State Recognition from Wearable EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/1424-8220/26/21/6943&hl=zh-CN&sa=X&d=8664312407984503113&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv5EtIAvkulzlMbZE9Q-hKLa&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=4&folt=kw-top
**作者**: M Eriş, FG Eriş, O Yaman - Sensors, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> of EEG , while transformer models capture global context at high computational cost. This study proposes KimiFormer, an end-to-end hybrid-attention Conformer that classifies raw EEG … The model was evaluated on the public EEG Violence

---

### [148] Frequency-aware Spatio-Temporal Hypergraph for EEG -based Emotion Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://www.computer.org/csdl/journal/ta/5555/01/11770020/2l5C60uZMs0&hl=zh-CN&sa=X&d=11228490395803089605&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv77RiR9z1DfayLAkoK5ZxIa&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=8&folt=kw-top
**作者**: J Hu, D Guo, D Wu, Z Si, S Fu, M Wang - IEEE Transactions on Affective Computing 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Accurate emotion recognition from electroencephalogram ( EEG ) signals is a key challenge in affective computing, due to EEG's non-stationary nature … In FSTHG, each node encodes EEG features across channels, time, and frequency bands

---

### [149] BrainBind: Bridging Synchronized EEG and fMRI through Long-Form Naturalistic Video Representations

**链接**: https://arxiv.org/abs/2611.05581
**作者**: Shixiao Wang, Rining Wu, Jian K. Liu
**来源**: cs.AI cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world vision is dynamic and scene-rich, while EEG and fMRI resolve it at complementary temporal and spatial scales. Most neural decoding systems, however, align one modality in isolation and mostly against static images or short clips. We study the synchronized case: EEG and fMRI are recorded during the same long-form naturalistic viewing, giving a shared stimulus but also recurring narrative context and many semantically similar candidates. We present BrainBind, a framework that maps synchronized EEG and fMRI into frozen long-form video embedding spaces and treats those spaces as common visual-semantic references, not literal neural codes. On CineBrain, a five-seed Recall@K 2 x 4 matrix across two video anchors and four system configurations shows distinct retrieval profiles. With Omni, fMRI organizes the full candidate list most strongly (MRR = 23.82, nDCG@10 = 25.31), while Joint-Dual gives the highest mean label-aware R@1 (13.52%) with a distinct rank-wide profile. The complem

---

### [150] Beyond Classification Accuracy: Building Trustworthy Artificial Intelligence for Clinical Electroencephalography

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0361923026004855&hl=zh-CN&sa=X&d=14512361382041045376&ei=HsbsapmMO9rPieoP8OvCmQw&scisig=AIL1Nv4aK50p2O042A5AYlinAJ9j&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=1&folt=kw-top
**作者**: S Hu, Y Huang, J Zhang - Brain Research Bulletin, 2026
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> that EEG -AI translation should be judged by the strength of its evidence, not by technical performance alone. We examine why EEG is valuable yet hard to standardize, how EEG … Future EEG -AI systems should be assessed by whether

---

### [151] Utilizing Earth Foundation Models to Enhance the Simulation Performance of Hydrological Models with AlphaEarth Embeddings

**链接**: https://arxiv.org/abs/2601.01558
**作者**: Pengfei Qu, Lei Ye, Wenyu Ouyang, Chi Zhang, Yikai Chai, Shuolong Xu 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [152] Open-HumanScale: An Open Recipe for Scaling Human and Robot Experience for Embodied Foundation Models

**链接**: https://arxiv.org/abs/2611.06817
**作者**: Juncheng Ma, Jiaxin Li, Jiankai Tu, Bo Liang, Guodong Lv, Yufan Deng 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Egocentric human video offers a scalable source of manipulation priors for robot learning, yet translating raw data scale into generalizable robot policies demands rigorous data curation and training recipes. We introduce Open-HumanScale, the first fully open recipe for scaling egocentric pretraining to 50,000 hours, anchored by Open-HumanScale-50K---a curated egocentric video corpus densely annotated with hand motion and natural language. Leveraging this corpus, we systematically investigate pure human pretraining via closed-loop simulation evaluations and uncover an empirical log-linear scaling law linking pretraining data hours to downstream robot success rates. Grounded in these findings, we develop HumanWAM-Vanilla, a world--action model pretrained exclusively on 50k hours of egocentric human video. Upon robot post-training, HumanWAM-Vanilla reaches 92.08% success on RoboTwin 2.0 Clean2Clean and 68.88% on Clean2Random, alongside a 14.17% mean success rate and a 19.00 mean progress

---

### [153] Decouple to Reuse: Fine-Grained Knowledge Augmentation for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2611.05993
**作者**: Yuqian Wu, Qingxiang Liu, Yuxin Guo, Weifeng Su, Jian Li, Pengfei Xu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series forecasting is critical for demand prediction and resource management in modern Web services, yet applying pretrained Time Series Foundation Models (TSFMs) to downstream tasks remains challenging due to domain shifts. Existing retrieval-augmented approaches typically retrieve coarse-grained window contexts and may introduce context-specific noise. To address this problem, we argue that temporal patterns should be reused at a decomposition level, as effective trend and seasonal dynamics may originate from different contexts. We propose \method, a two-stage \underline{F}ine-grained \underline{K}nowledge \underline{A}ugmentation framework that decouples and consolidates pre-training knowledge into compact, task-shared residual codebooks to enhance frozen TSFMs. Specifically, Stage I constructs dual-branch residual codebooks for decoupled trend and seasonal signals, while Stage II dynamically retrieves and merges these fine-grained patterns into target representations via task-

---

### [154] Graph Foundation Models Can Become Effective Multivariate Time Series Anomaly Detectors

**链接**: https://arxiv.org/abs/2611.06441
**作者**: Zhuangyan Hu, Zhuoxuan Liang, Wei Li, Xiaohua Jia, Moustafa Youssef, Sumi Helal
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multivariate time series anomaly detection (MTSAD) relies on modeling both temporal dynamics and inter-sensor dependencies to identify complex system faults. Although graph-based detectors explicitly model sensor topologies, they train task-specific networks from scratch on limited target-domain data, remaining vulnerable to spurious correlations and unable to reuse transferable priors. While pretrained Graph Foundation Models (GFMs) offer transferable topological priors and anomaly discriminability, directly adapting them to MTSAD is hindered by cross-modal feature-topology mismatch, unreliable pseudo-anomaly supervision, and decision distortion during node-to-window aggregation. To fill these gaps, we propose a novel adaptation framework, Gfm4Mtsad, which unleashes pretrained GFMs for MTSAD. We introduce the Structure-and-Information Contract Alignment (SICA) module to bridge continuous time series and the pretrained GFM space. This module harmonizes principal subspace token projecti

---

### [155] Do Tabular Foundation Models Agree with Themselves?

**链接**: https://arxiv.org/abs/2608.06004
**作者**: Christian Kl\"otergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme, Tom Hanika
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] From Adults to Children: Benchmarking Foundation Models for Chest X-Ray Classification under Domain Shift

**链接**: https://arxiv.org/abs/2610.21809
**作者**: Sara In\'acio, Hugo Proen\c{c}a, Jo\~ao C. Neves
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [157] MESA: An Evaluation Framework for Compositional, Semantic, and Spatial Generalization in Robotics

**链接**: https://arxiv.org/abs/2611.05567
**作者**: Albert Wilcox, Frank Chang, Nhi Nguyen, Aishani Chakraborty, Jeremy A. Collins, Vaibhav Saxena 等 (9 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite growing interest in foundation models for robotic manipulation, systematic evaluation of their capabilities remains elusive. Existing benchmarks are either narrow and saturated, offering little signal on SOTA methods, broadly scoped, providing diversity at the cost of controlled experimentation, or require training on large, messy open-source datasets. We introduce MESA, an evaluation framework designed for precise, reproducible measurement of language-conditioned policy generalization. MESA provides five evaluation suites that isolate in-distribution performance and four distinct axes of generalization: spatial configuration, object instance, object category, and subtask composition, enabling researchers to diagnose where and why policies fail, not just whether they fail. To populate these suites at scale, we develop MESA-Gen, a pipeline for task and demonstration generation built by improving MimicGen. We instantiate the framework on two platforms and release both: the single

---

### [158] XuanJian-DINOSAR: A SAR Foundation Model Based on Global and Local Semantic Consistency

**链接**: https://arxiv.org/abs/2611.06105
**作者**: Chunxiao Wu, Huixin Huang, Jialei Pan, Qiang Liang, Tao Wu, Cheng Wu 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised pre-training on synthetic aperture radar (SAR) imagery enables transferable representations, but the optical-SAR domain gap and speckle perturbations limit representation stability. Most SAR foundation models use masked image modeling (MIM) through pixel reconstruction or structural feature prediction, which is sensitive to speckle or relies on predefined operators. Joint modeling of cross-view semantics and perturbation stability at corresponding spatial locations remains underexplored. We propose XuanJian-DINOSAR, a SAR foundation model based on global and local semantic consistency. We curate over 360K publicly available SAR target chips, detection images, and scene images spanning diverse targets, scenes, and sensors, and adapt an optically pre-trained DINOv2 model to SAR through self-supervised learning. The framework combines DINO global semantic self-distillation, iBOT local masked modeling, and KoLeo feature-distribution regularization to learn globally discrimi

---

### [159] Annotator-Free Object Detection via Foundation Model Collaboration

**链接**: https://arxiv.org/abs/2611.06195
**作者**: Yasiru Ranasinghe and Vishal M. Patel
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Object detection research remains constrained by high annotation costs and the closed-set assumptions of supervised models, limiting scalability to novel categories. We present a target-dataset annotation-free object detection framework that eliminates the need for human labeling on the target dataset by leveraging the complementary strengths of pretrained foundation models, including segmentation and vision-language systems, combined with a self-refining training loop. To further reduce reliance on expensive LVLM queries, we introduce a landmark-based clustering mechanism that amortizes labeling across image clusters, improving label consistency while lowering computational cost. Our method autonomously generates segmentation proposals, assigns semantic labels through multimodal reasoning, and iteratively improves both localization and classification using a lightweight open-set detector. This modular pipeline enables adaptation to completely unseen object classes and domains without 

---

### [160] Feature Puzzles: Single-Image Supervision for Multi-View 3D-Aware Segmentation

**链接**: https://arxiv.org/abs/2611.05874
**作者**: Jiahao Ma, Qiang Zhang, Miaomiao Liu, David Ahmedt-Aristizabal and Chuong Nguyen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans can easily recognize the same objects across different viewpoints of a 3D scene, whereas teaching models such multi-view-consistent perception typically requires videos or calibrated multi-view captures, which are considerably more expensive and less diverse than large-scale monocular data.~In this paper, we introduce Feature Puzzles, a novel framework for learning multi-view-consistent segmentation using only single-image semantic segmentation supervision. Specifically, we propose a simple yet effective pipeline that constructs multi-view-consistent segmentation pseudo-labels through image cropping and geometric transformations. We further introduce a lightweight, plug-and-play network that leverages the multi-view-consistent image features learned by existing pretrained 3D foundation models and the generated pseudo-labels to perform multi-view-consistent segmentation. Importantly, our flexible framework supports various types of prompts provided from one or multiple views and 

---

### [161] TailSteer: Trajectory-Tail Steering for Drift-Resistant Multi-turn Image Editing

**链接**: https://arxiv.org/abs/2611.06741
**作者**: Ruikang Li, Zixuan Chen, Jiarui Wu, Mingde Yao, Yiyuan Zhang, Yujin Wang 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Strong single-turn editing performance does not guarantee reliable multi-turn interaction: as edited outputs are repeatedly reused, small unintended changes can accumulate into severe visual drift. This long-term drift is often mitigated through training on multi-turn data or cross-turn rollouts, potentially altering pretrained priors, or through specialized inference-time mechanisms that are difficult to scale to foundation models. We introduce TailSteer, a final-stage training framework that improves multi-turn robustness while retaining the generative and editing capabilities acquired through earlier training. TailSteer follows a simple principle: keep early denoising dynamics close to those of the base model and concentrate preservation corrections near the trajectory tail, where fine-grained deviations can be suppressed. These corrections are learned from the editor's own on-policy denoising rollouts, using unchanged source content as a preservation reference without requiring cur

---

### [162] Interactive World Simulation with Cosmos for Physical AI

**链接**: https://arxiv.org/abs/2611.06627
**作者**: NVIDIA: Anis Ahmad, Jon Allen, Malik Aqeel Anwar, Jesse Archer, Maciej Bala, Piotr Barejko 等 (10 人)
**来源**: cs.AI cs.CV cs.LG cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a shared framework that adapts Cosmos world foundation models for real-time interactive world simulation in Physical AI. By streaming visual observations in response to actions and scene controls, the framework enables users and embodied agents to interact with evolving virtual environments. It supports both predicting the visual consequences of actions and generating observations from physical state maintained by an external simulator. We demonstrate this approach across camera navigation and robot manipulation, controllable video transfer, and multi-view autonomous vehicle (AV) simulation. These examples provide a shared foundation for developing interactive virtual environments for Physical AI training and evaluation. Our code and model checkpoints are available at https://github.com/nvidia/cosmos and https://huggingface.co/collections/nvidia/cosmos3-examples. The project website is available at https://research.nvidia.com/labs/cosmos-lab/cosmos-simulation.

---

### [163] A 3D foundation model unifying CT interpretation and segmentation

**链接**: https://arxiv.org/abs/2611.06471
**作者**: Yulu Xie, Zilong Li, Shen Xu, Yifan Bai, Liuhong Shi, Jiao Chen 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiologists interpret computed tomography (CT) scans by jointly determining what a finding represents and where it lies in three-dimensional (3D) anatomy. However, CT models have treated CT interpretation and 3D segmentation as separate tasks, leaving textual findings spatially unverifiable and overlooking potential synergy between clinical understanding and spatial perception. Here we present HoloCT, a generalist 3D foundation model unifying CT interpretation and voxel-level segmentation by jointly modelling whole-volume context and fine-grained anatomical detail, providing 3D masks as evidence. We curated HoloDATA, comprising 195,921 CT scans from 73 public datasets and six clinical cohorts, with 6.2 million instruction dialogues and 2.8 million CT-mask pairs. Across 346 tasks spanning segmentation, lesion screening, visual question answering, and report generation on 61 internal and 12 external datasets, HoloCT outperformed specialist and foundation models. In multicentre validatio

---

### [164] Dexterous Robotic Hands in the Foundation-Model Era: A Full-Stack Survey of Hardware, Data, Cross-Embodiment Transfer, Learning, and Evaluation

**链接**: https://arxiv.org/abs/2611.06724
**作者**: Ji Pei
**来源**: cs.RO cs.AI cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dexterous robotic hands are increasingly coupled to large-scale human data and foundation models, yet progress in hardware, representation learning and evaluation is often assessed separately. This survey reviews work from January 2024 to early November 2026, with earlier studies included to establish technical lineages. We organize the literature into five interdependent layers: hardware; data collection and curation; cross-embodiment transfer; learning and foundation models; and evaluation and applications. Human hand-object understanding and tactile sensing provide two cross-cutting perspectives. A system-level architecture, comparative tables and five case analyses connect design choices across these layers. We distinguish within-study experimental comparisons from heterogeneous corpus statistics, vendor specifications and company-reported results. Three conclusions emerge. First, the value of human data depends on kinematic, visual and contact alignment, not recording volume alone

---

### [165] CounterFactual Retrieval for Evidence-Aware Individual Animal Identification

**链接**: https://arxiv.org/abs/2611.06864
**作者**: Ankit K. Upadhyay, Aleksandr Algasov, Ekaterina Nepovinnykh, Fedor Zolotarev, Tuomas Eerola, Heikki K\"alvi\"ainen 等 (8 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated identification of individual animals is moving from small curated studies toward shared benchmarks and reusable foundation models. This progress is useful, but current evaluation leaves the evidence behind a match unresolved, i.e., high retrieval accuracy does not show whether a model used animal features or identity-correlated shortcuts. We address this with Counterfactual Foreground Retrieval (CFR), an evidence-aware evaluation protocol. CFR evaluates the same query-gallery task under different views: full image, foreground-only, and shortcut-only. The full-image measures standard retrieval performance; the foreground-only measures foreground-supported retrieval; and shortcut-only view measure how much identity signal is recoverable from background, or silhouette. This turns a retrieval score into an evidence profile: how well the model performs on the original images, how much of that performance remains when only the animal is visible, and how much identity signal remains

---
