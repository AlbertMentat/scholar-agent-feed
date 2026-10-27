# 📑 论文索引 - 2026-10-28

共 310 篇论文

---

### [1] OmicsLM: A Multimodal Large Language Model for Multi-Sample Omics Reasoning

**链接**: https://arxiv.org/abs/2605.06728
**作者**: Maciej Sypetkowski, {\L}ukasz Smoli{\'n}ski, Remigiusz Kinas, Joanna Krawczyk, Bart{\l}omiej Hofman, Aleksandra Mo{\.z}wi{\l}{\l}o 等 (9 人)
**来源**: q-bio.GN cs.AI q-bio.CB
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] OneEEG: A Unified Signal-Visual Multimodal Language Model with Task-Aware Mixture of Projectors for Multi-Task EEG Understanding

**链接**: https://arxiv.org/abs/2610.35355
**作者**: Jiacheng Zhang, Xueyi Zhang, Xin Lu, Siqi Cai, Haizhou Li
**来源**: cs.LG
**匹配关键词**: EEG, LLM, MLLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is widely used in clinical assessment, brain-computer interfaces, and cognitive-state analysis, yet EEG modeling remains fragmented across task paradigms. Recent multimodal large language models (MLLMs) provide a promising interface for flexible multimodal reasoning, but their ability to understand EEG inputs remains limited. In this work, we propose OneEEG, a unified EEG-MLLM framework for multi-task EEG understanding. By training on our curated OneEEG-Instruct, a multi-task EEG instruction-tuning dataset, OneEEG jointly models numerical EEG representations and visual EEG representations, and introduces a task-aware Mixture of Projectors (MoP) to align heterogeneous EEG features across different task families with the LLM embedding space. We further establish OneEEG-Bench, a benchmark for evaluating current MLLMs and our method on multi-task EEG understanding. Experiments show that existing MLLMs have limited ability to interpret EEG inputs, while OneEEG a

---

### [3] Agent Memory as Recommendation: Recommender-System Design for Long-Term Memory of LLM Agents

**链接**: https://arxiv.org/abs/2610.34673
**作者**: Xinyu Zhang, Weiwei Sun
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents that serve users across many sessions must choose, for every request, the few stored memories that enter a limited context window. This choice largely decides whether the agent answers correctly, and it runs on every request at Web scale. This selection faces three challenges: a large and growing store, a per-request cost budget, and multi-session questions that need all of their evidence. Many memory systems build notes or graphs with hundreds to thousands of LLM calls per history, and each is designed on its own, so it is unclear which component yields the accuracy. These challenges mirror the properties of recommendation, so we formalize agent memory as budgeted slate recommendation, with the request as the user, stored memories as items and the context window as a slate. The formalization places memory systems in one design space of recommender cascades and factorizes accuracy into the completeness that each stage controls. Guided by it, we propose

---

### [4] AutoEnergyDesign: An LLM-Driven Agent for Automatic Energy System Design Optimization

**链接**: https://arxiv.org/abs/2610.35160
**作者**: Amedeo Buonanno, Salvatore Fabozzi, Maria Valenti
**来源**: cs.AI stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing building energy systems is a high-dimensional, mixed-integer search problem: when each design is evaluated by a year-long simulation, black-box optimizers typically need hundreds of evaluations. This paper presents AutoEnergyDesign, a framework in which a Large Language Model (LLM) agent reasons over previous simulation results, proposes configuration changes and learns in context from each outcome, while a git-based mechanism automatically reverts unsuccessful changes. The agent couples a reasoning model with an explicit memory organisation (procedural, semantic, episodic and reflective), a constrained action interface and an environment-grounded keep/revert signal. The simulator covers eight technologies (photovoltaics, micro-wind, combined heat and power, solar thermal, gas boilers, batteries, heat pumps and inverters) and computes the 25-year Net Present Cost (NPC), including capital and operating costs and salvage value. On a case study with measured building load profil

---

### [5] Estimation of Propagated Risk in LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.33282
**作者**: Shreyan Ganguly, Souradeep Chattopadhyay, Qisai Liu, Soumik Sarkar
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) based multi-agent systems introduce a distinctive reliability challenge in which actions taken by upstream agents can affect the correctness of downstream agents. While prior work has investigated error propagation and developed methods for estimating uncertainty inherited from upstream agents, existing approaches do not explicitly model how realized sender-receiver interactions contribute to downstream error risk under different sender correctness states. In this work, we study agent-level error-risk estimation from multi-agent execution traces. We propose Interaction-Effect Propagation (IE-Prop), an interaction-conditioned model that learns separate effects for correct and incorrect upstream agents. For each sender-receiver interaction, the model combines these conditional effects using the sender's estimated error risk, and recursively propagates the resulting risk estimates through the execution graph. We evaluate our approach across three multi-agent arc

---

### [6] TUON: A Tensor-Aware Optimizer Utilizing Tensor-SVD and Polarization for Large Language Model Pretraining

**链接**: https://arxiv.org/abs/2610.35130
**作者**: Anda Tang, Xuanlin Yang, Junjie Wang, Zhouchen Lin
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large scale language model~(LLM) pretraining is increasingly bottlenecked by optimizer efficiency, driving optimizer design from vector-aware methods such as AdamW to matrix-aware methods. Matrix-aware optimizers such as Muon exploit matrix structure but treat layers independently, neglecting cross-layer correlations. Tensor-aware optimizers are therefore needed, yet existing ones rely on a matricization-based tensor algebra and remain restricted to shallow stacking and specific modules. In this paper, we propose \textbf{TUON}, a novel optimizer built on a transform-based tensor algebra derived from the Tensor-SVD (T-SVD). Unlike methods that polarize a globally unfolded matrix, TUON mixes layers via a unitary transform $\boldsymbol{Q}$ and then polarizes each transformed slice, and inverts the transform to recover the update. This mix-then-separate strategy captures cross-layer correlations while preserving per-layer diversity, avoiding the structural dimension imbalance and cross-lay

---

### [7] A Deterministic Security Runtime for LLM Agents on MPI and Batch-Scheduled HPC Systems: Consensus-Governed, Hardware-Rooted Supervision of Every Rank

**链接**: https://arxiv.org/abs/2610.33318
**作者**: Alfredo Metere
**来源**: cs.CR cs.AI cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents launch simulations on high-performance computing (HPC) systems, where one sbatch or mpirun can commit thousands of node-hours and a forged result can cost lives. Of 23 surveyed systems, none supervises the running job, and none holds when the control host is compromised. We fix both. Enclawed, our deterministic security runtime for AI agents, has until now served a single user; this work makes it a distributed runtime for parallel HPC and agent swarms. The Enclaweder, our hardware root of trust, keeps a compromised host from becoming a catastrophe. A launch gate decides every launch by policy alone, refusing what it cannot parse. Once the job runs, a swarm chain grants short leases against signed heartbeats and evicts on evidence, and a supervisor around every rank pauses it when its lease lapses and kills it on tampering. Each node signs with its Enclaweder's key, so the host can forge none of it. Enclawed needs no administrator privileges and plugs into ex

---

### [8] Incremental Predictive Value of LLM Tutoring Interactions for Student Performance

**链接**: https://arxiv.org/abs/2610.33488
**作者**: Zeyu Dong, Mikael Kwame Kuada, Asa Holley Buchakjian-Tweedy, Ibrahem Aljabea
**来源**: cs.CL cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We evaluate whether semester-level interaction features from a large language model tutor improve assignment-score prediction beyond constant baselines. StudyChat provides 16,851 student-assistant exchanges from two offerings of an undergraduate artificial intelligence course, with outcomes matched to 175 of 203 student-semester records. Six fitted estimators and training-fold mean and median baselines share repeated nested cross-validation. After averaging each student's held-out predictions across ten repeats, Gradient Boosting achieves mean absolute error of 3.023 grade points, versus 3.138 for the median baseline. The paired difference is -0.114, with a conditional 95% bootstrap interval of [-0.245,0.013]. Representation changes and a semester-specific median yield similarly small gains. In the lowest observed-score quartile, however, boosting's error is 7.30 points, versus 8.07 for the median and 6.67 for the mean; Ridge has the lowest fitted-model error at 6.37 despite its worse 

---

### [9] PREFINFER: Preference inference from user- LLM interaction history

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.700.pdf&hl=zh-CN&sa=X&d=11519834482803608838&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv5Ko05V7aXNaUr1Brsifpvc&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=1&folt=kw-top
**作者**: Y Chen, H Peng, Y Qi, L Hou, B Xu, J Li - Findings of the Association for … 等 (7 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Large language model ( LLM ) personalization aims to generate responses that align with individual user preferences, making accurate preference inference critical. In practice, user- LLM interaction histories naturally contain rich preference signals

---

### [10] Preserve to Expand: Source-Aware Adaptation and Model Merging for Multilingual LLM-Based ASR

**链接**: https://arxiv.org/abs/2610.35846
**作者**: Yuchen Zhang, Haralambos Mouratidis, Ravi Shekhar
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Expanding multilingual ASR systems to new languages is challenging when adaptation must preserve previously supported languages without replaying source-language training data. We study this problem in connector-based Speech LLMs, where a trainable connector maps speech representations into a frozen large language model. We evaluate target-update construction and merging strategies for adapting the connector while preserving source-language performance. In single-target expansion, target-only fine-tuning and standard TIES merging learn new languages but cause severe source-language forgetting, while SSU-Wanda+TIES gives the best source-preserving trade-off. In multi-target expansion, update merging provides stable source retention, whereas recursive expansion can improve target adaptation under favorable orders but is highly order-sensitive. These results show that multilingual ASR expansion requires balancing target acquisition, source retention, and interactions among target-language

---

### [11] UniGFM-RAG: Unify Graph Foundation Models and Large Language Models for End-to-End Retrieval and Reasoning

**链接**: https://arxiv.org/abs/2610.34866
**作者**: Zicheng Zhao, Linhao Luo, Zongji Yu, Junnan Dong, Yanchao Tan, Shirui Pan 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown remarkable capabilities across tasks, but they still struggle with complex reasoning that requires integrating scattered knowledge. Graph Retrieval-Augmented Generation (GraphRAG) addresses this challenge by organizing fragment knowledge as graphs, while recent Graph Foundation Models (GFMs) further improve GraphRAG with graph-native retrieval and reasoning capabilities. However, existing GraphRAG methods usually adopt decoupled retrieve-then-generate pipelines, which create objective misalignment between retrieval and reasoning, and training GFM retrievers typically depends on expensive human annotations. To address these limitations, we propose \ourmethod, a unified end-to-end GraphRAG framework that tightly couples a GFM retriever with an LLM generator. Given a query, the GFM retriever first reasons over the graph to score and retrieve relevant document nodes. These node embeddings are then passed through a fully differentiable graph bridge, w

---

### [12] When Respondents Are Scarce: LLM-Derived Semantic Priors for Bayesian Confirmatory Factor Analysis

**链接**: https://arxiv.org/abs/2610.34843
**作者**: Shaohuai Feng, Mohd Wira Mohd Shafiei, Mohd Sukri Shafie, Siyang Tian
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Across social and behavioral research, measuring latent constructs can be challenging when target populations are small or difficult to reach. Recruiting additional respondents may be costly or infeasible, leaving researchers with limited data for estimating questionnaire factor structures. Yet item wording contains structural expectations before data collection, and whether these can improve small-sample estimation without replacing empirical validation remains unclear. We introduce the Semantic-Empirical Updating Framework (SEUF), which converts large language model paraphrases and embeddings, aligned with hypothesized item-factor assignments, into prespecified priors for Bayesian confirmatory factor analysis. We evaluated SEUF using a 38-item survey of 617 industrial-park stakeholders and two public surveys, FEVS and RIASEC. Semantic structure persisted after wording controls across all three instruments. With 50 respondents, SEUF achieved loading precision comparable to conventiona

---

### [13] Auditing evaluation artifacts and data leakage in large language model systems for rare disease diagnosis

**链接**: https://arxiv.org/abs/2610.33592
**作者**: Jian Yang, Peilin Liu, Xiaohan Li, Songda Li, Yu Cao, Yuqing Feng 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Augmented large language model (LLM) systems have reported high benchmark accuracies in rare disease diagnosis, yet their real-world clinical utility remains unproven. A recent meta-analysis flagged augmented LLM diagnostic evaluations as having a high risk of bias due to suspected data leakage; however, the precise impact of these vulnerabilities on model inference has yet to be fully quantified. In this study, we present a comprehensive empirical audit to quantify evaluation artifacts across prevailing AI paradigms, using a repository of over 60,000 cases from diverse public and independent clinical cohorts. By reconstructing a state-of-the-art agentic framework, we demonstrate that candidate-space contamination artificially inflates performance: enforcing strict cross-dataset isolation resulted in a marked performance decline, with the cross-dataset mean Recall@1 decreasing from 54.3% (under conventional one-vs-rest evaluation) to 40.3% (Hedges' g = 0.94). Similar spatial overfittin

---

### [14] SentryBench: A Cost-Sensitive Benchmark for Adversarial Robustness of Tool-Using LLM Agents in Public-Safety Deployments

**链接**: https://arxiv.org/abs/2610.34535
**作者**: Md Abu Yusuf, Oyshi Tabassum Aditi, Md Faysal Hosain Mazed
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly wired to consequential tools that send public alerts, dispatch responders, and query citizen records, where one erroneous tool call carries real-world cost. Existing agent-safety benchmarks measure generic harm or prompt-injection success and implicitly treat refusing as the safe default. In public-safety deployments that assumption breaks: an agent too cautious to dispatch help fails as surely as one that triggers a false alert. We present SentryBench, which scores agents on a two-sided, cost-sensitive frontier jointly measuring attack success, over-refusal (missing a real emergency), and over-reaction (unwarranted action) under adversarial tool use, with scenarios grounded in real emergency-call transcripts, disaster messages, and real injection/jailbreak payloads. We formalize deployment harm as an asymmetric cost functional, prove naive caution is harm-dominated whenever it refuses more genuine emergencies than the attack harm it a

---

### [15] Silent and Costly: Characterizing and Detecting Prompt-Caching Mis-Integration in LLM Agents

**链接**: https://arxiv.org/abs/2610.34817
**作者**: Ying Zhang, Ruoqi Guo, Yi Liu, Gelei Deng, Yuekang Li, Yepang Liu 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) services process massive volumes of user requests, resulting in substantial inference costs. To reduce both cost and latency, providers have introduced prompt caching. However, correctly integrating prompt caching is non-trivial due to heterogeneous provider-specific APIs and continuously evolving caching semantics. To understand prompt-caching mis-integration in downstream applications, we conduct the first empirical study of 120 prompt-caching-related pull requests from 10 popular open-source agent systems. Our findings show that prompt-caching mis-integrations arise in both request-side misconfiguration and read-side usage miscount. More importantly, most mis-integrations fail silently without causing observable runtime failures. Motivated by these findings, we design CACHELINT, which models a prompt-caching mis-integration as an invocation site together with the preconditions required for correct cache integration. CACHELINT locates caching invocation sit

---

### [16] Context Is Not Free: Carbon-Aware LLM Routing for Multi-Turn LLM Web Services across Geo-Distributed Data Centers

**链接**: https://arxiv.org/abs/2610.35230
**作者**: Xiaoyang Zhang, Yuejun Yan, Qingang Zhang, Yonggang Wen
**来源**: cs.DC cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The sustainability of the Web has drawn growing attention, as large language model (LLM)-based web services leave a substantial carbon footprint. These services typically run in geo-distributed data centers whose grid carbon intensity varies across regions and over time, so routing each query to a cleaner region or a smaller model can reduce emissions. A conversation, however, is a stateful web session: each turn reuses the key--value (KV) cache of its history, which resides only where earlier turns were served. Serving a turn on another deployment requires recomputing this history, whose carbon cost grows with the conversation and can outweigh the saving of the move. Existing carbon-aware LLM routers treat a conversation's queries as independent and ignore this cost. We present CarbonRouter, an online framework that jointly selects the model, GPU type, and region for each query to minimize carbon emissions. CarbonRouter introduces a cache-aware carbon cost model, which charges history

---

### [17] Recursive Semantic Divergence for LLM Agent Consistency

**链接**: https://arxiv.org/abs/2610.33012
**作者**: Harshavardhan Abichandani, Penny Chong, Atin Ghosh, Daniel Dahlmeier
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents with tool use exhibit inconsistent behavior across independent runs from identical states, calling different tools, producing contradictory outputs, or pursuing divergent strategies. This variability compounds over time and undermines deployment reliability. Existing evaluation metrics primarily measure task correctness via completion-based scores and do not capture consistency in agent behavior across executions. Separately, agent behavior is analyzed either at the token level using probability distributions or at the single-response level using semantic clustering, but neither captures how inconsistency propagates across future turns of a trajectory. We introduce Recursive Semantic Divergence (RSD), an unsupervised trajectory-level consistency metric adapted from bisimulation metrics in reinforcement learning. RSD measures the expected cumulative semantic disagreement between two independent rollouts of the same agent from the same state, using natur

---

### [18] Autonomous Structural Discovery Of Bioprocess Dynamics And Kinetics Via LLM-Driven Agents

**链接**: https://arxiv.org/abs/2610.35391
**作者**: Erdal Aydin, Yaman Arkun
**来源**: math.OC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-fidelity digital twins in continuous biomanufacturing are often bottlenecked by incomplete kinetic models, while standard data-driven algorithms (e.g., SINDy, PINNs) lack interpretability or impose rigid physical assumptions. This paper introduces a hybrid closed-loop architecture for autonomous kinetic state-space discovery driven by a Large Language Model (LLM) agent. The framework employs a sequential "isolation-peeling" methodology across orthogonal operational regimes. This algorithmic peeling mathematically decouples entangled multiplicative (inhibitory) and additive (catalytic) biological rate law. Grounded in a Two-Level Retrieval-Augmented Generation (RAG) library, the framework utilizes Moving Horizon Estimation (MHE) and logarithmic decomposition to decouple complex cell growth kinetics into orthogonal multiplicative (inhibitory) and additive (regulatory) residual channels. When statistical degeneracy occurs an Active Design of Experiments (DoE) controller dynamically t

---

### [19] Strategic Calibration in LLM Multi-Agent Systems: Audited Pivot Scoring for Truthful Elicitation

**链接**: https://arxiv.org/abs/2610.33728
**作者**: Jinhao Zhou, Zhaohan Zhang, Xijian Xu, Jun Wu
**来源**: cs.GT cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In large language model (LLM)-based multi-agent systems, reported confidence increasingly determines the allocation of scarce downstream attention, computation, and decision influence. This makes reporting strategic: an agent may overstate the relevance of its contribution even when its underlying belief is well calibrated. Existing calibration methods largely assume passive reporting and therefore do not address strategic incentives created when confidence determines downstream allocation. We formulate strategic calibration as a reporting-layer incentive problem and propose the Audited Pivot Scoring Mechanism (APSM). APSM offsets platform-controlled allocation benefits, uses inverse-propensity-weighted sparse audits, charges the Clarke pivot externality, and applies a strictly proper score. Under the stated model assumptions, truthful reporting is the unique expected-utility best response. We also characterize approximate execution and the audit-variance trade-off. Calculator-free exp

---

### [20] ConMem: Counterfactual Multi-Scenario Probing for Resolving LLM Memory Misalignment

**链接**: https://arxiv.org/abs/2610.33432
**作者**: Shuning Zhang, Tenghao Ji, Jingruo Chen, Eryue Xu, Bohao Chu, Xin Yi
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is critical for autonomous Large Language Model (LLM) agents executing multi-session, long-horizon tasks. However, existing memories often inappropriately store, retain, or retrieve over-generalized, misattributed, or privacy-sensitive information, a problem we term memory misalignment. To study this problem, we construct \textbf{MemAlign}, a benchmark comprising 1,079 curated memory cases grounded in synthetic, validated multi-session conversational contexts covering diverse misalignment taxonomies. We then propose ConMem, an algorithm that reframes retention decisions as prospective counterfactual causal inference. \textbf{ConMem} synthesizes counterfactual interaction scenarios to prospectively audit downstream intervention effects across three aspects: relevant task execution, irrelevant invariance checks, and risk-sensitive boundary shifts. Experiments show that ConMem outperforms other methods, achieving 75.16\% accuracy, 64.15\% balanced accuracy, and a Macro-F1

---

### [21] Adapting LLM-SC to Living Sacred Heritage: Domain-Specific Extraction, Semantic Networks and Human Evaluation on Pashupatinath Temple Reviews

**链接**: https://arxiv.org/abs/2610.35685
**作者**: Hari Sitaula, Manish Sakhakarmy, Pujan Pant, Sagar Newpane
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) pipelines can turn visitor reviews into structured data, but generic schemes may miss rituals, sacred spaces, cultural restrictions and emotionally mixed experiences at living sacred heritage sites. We adapted the LLM-Social Computing (LLM-SC) framework to Pashupatinath Temple, Nepal, by specifying a 12-type entity taxonomy (four original LLM-SC types plus eight sacred-heritage types), four relation types and nine aspect-sentiment dimensions in a GPT-4o extraction prompt, which was applied to a fixed random sample of 2,500 English-language Tripadvisor reviews from a processed corpus of 3,939. The exports contain 11,286 entity, 6,232 aspect-sentiment and 5,590 relation records, covering 2,485, 2,487 and 2,433 reviews, respectively; the eight added sacred-heritage types account for 64.8% of entity records. Against an adjudicated two-annotator reference for 200 reviews, exact normalized surface-and-type matching gave provisional entity scores of 41.0% precision,

---

### [22] SLICE-Mem: Salience-Gated Lightweight Information Curation for Efficient LLM Agent Memory

**链接**: https://arxiv.org/abs/2610.33015
**作者**: Xiaobin Chen, Dian Jin, Lin Shu, Defeng Sun, Xiaoming Tao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory enables large language model (LLM) agents to maintain personalized and temporally coherent interactions, but repeated LLM inference for memory admission, extraction, and organization introduces substantial cost and latency. We present SLICE-Mem, a lightweight memory framework that combines salience-guided admission and predicate-centered information extraction. A compact classifier identifies user turns worth retaining, and a semantic-dependency-based extractor converts admitted turns into concise memory entries. This online pipeline requires no generative LLM calls, while cross-entry reconciliation is deferred to an offline consolidation stage. We evaluate SLICE-Mem on the weekly subset of Memora and LongMemEval-S using 8B and 30B Qwen backbones for memory construction and consolidation on both benchmarks. Compared with the generative-memory baseline MemOS under the Qwen3-30B configuration, SLICE-Mem's online pipeline achieves 46.60 versus 46.68 FAMA (Forgetting-Aware

---

### [23] A Distribution-Matching Perspective on LLM Training Algorithms

**链接**: https://arxiv.org/abs/2610.33740
**作者**: Yanxing Huang, Bingzhang Yan, Zihan Tang, Wenzhe Li, Peng Li, Yang Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we propose a unified framework for training algorithms across different stages of modern large language model development, based on the perspective of distribution matching. We show that a broad class of language model training algorithms can be interpreted as minimizing a certain divergence between the current model and a target distribution, and that characterizing the properties of this target distribution provides substantial insight into the behavior of the corresponding training algorithms. By analyzing specific forms of the target distribution, we establish that On-Policy Distillation (OPD) enjoys an advantage over classical Knowledge Distillation (KD) when the current model distribution is close to the target distribution, while exhibiting a disadvantage when the two distributions are far apart. Furthermore, when the target distribution itself depends on the model being optimized, we show that the accumulation of estimation variance can induce a deterministic degr

---

### [24] MarkovSim: an LLM Agent Harness with Bounded Context for Long-Horizon Computational Simulation

**链接**: https://arxiv.org/abs/2610.35349
**作者**: Yeui-Lung Lei, Wen-Bo Chen, Pan Zhang
**来源**: cs.CE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies have applied large language model (LLM) agent systems to computational simulation workflows. Such workflows are long-horizon, so the information generated can exceed what an LLM can reason over at once, its context window. Context management is therefore essential, yet existing systems have either neglected it or treated it as a supporting mechanism rather than a subject of study. This paper presents MarkovSim, an LLM agent harness for long-horizon computational simulation, whose core is a context management scheme built into the workflow. The workflow record is written to a memory system with a predefined schema, and at workflow-defined boundaries, namely the state transitions of a finite-state machine a compact representation of the solution progress is constructed from it as the agent's context. Instantiated on finite element analysis and evaluated on six benchmark problems, MarkovSim passed 16 of 18 runs and corrected its own faults in both the solver operations and 

---

### [25] DualPace: Decoupled Scheduling and Cooperative GPU--CPU Decoding for LLM Serving

**链接**: https://arxiv.org/abs/2610.33501
**作者**: YuXuan Lin, KeQiang Wu, Kingsum Chow
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving relies on batching to improve inference throughput, but the key-value (KV) cache grows with sequence length and limits GPU-resident concurrency. CPU offloading can expand KV capacity using host memory, yet existing systems remain largely GPU-gated: CPU-resident requests make progress only when the GPU scheduler exposes suitable overlap opportunities. As a result, host memory and CPU compute cannot act as an independent serving resource, leading to bursty CPU-side progress and inflated tail inter-token latency (ITL) under load. We present DualPace, an LLM serving runtime that turns the host into an independently scheduled decode engine. DualPace separates scheduling authority across two engines: the GPU engine executes prefills and GPU-resident decodes, while an AMX-enabled CPU engine independently batches and advances CPU-resident decodes. The engines are decoupled in scheduling but cooperative in execution: the CPU can execute a complete decode itera

---

### [26] FlexA-Mem: Budget-Adaptive Agentic Memory for LLM Agents

**链接**: https://arxiv.org/abs/2610.33274
**作者**: Wujiang Xu, Jiaojiao Han, Xi Zhu, Qizheng Zhang, Kaiqu Liang, Yutong Yin 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents work in scenarios with very different memory needs. A question about past conversations needs the exact facts it names, while a multi-step task needs a trace of the steps already taken together with details that the next step cannot name. Existing memories are each designed and tested for one kind of scenario. Retrieval memories such as A-Mem miss steps that the current query does not express, summaries drop exact strings, and pairing the two fixes the split of the budget in advance. We propose FlexA-Mem, a general memory that writes each unit of history once into an immutable store and renders a fresh memory for every call. The rendered memory is a compact timeline of records plus detail that a fixed rule fits into the remaining room without an LLM call. The detail is either relevant units as raw text or excerpts or the verbatim pieces that best match the query. With one store, FlexA-Mem serves both kinds of scenario. On AppWorld challenge tasks at 4k

---

### [27] Abstraction agent: Llm -guided abstraction for imperfect-information games

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1246.pdf&hl=zh-CN&sa=X&d=11744859678894855870&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv7Zwi2__Ps7rfeugnWWqWDN&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=3&folt=kw-top
**作者**: B Li, L Huang - Findings of the Association for Computational …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> We propose the Abstraction Agent, a zero-shot pipeline that uses a large language model ( LLM ) to discover continuous strategic features from a … This is structured knowledge elicitation: converting implicit strategic knowledge in LLM

---

### [28] InferPriv: Evaluating Inferential Privacy Leakage in LLM Assistants

**链接**: https://arxiv.org/abs/2610.34640
**作者**: Pengrun Huang, Yiwei Fu, Luoxi Meng, Kamalika Chaudhuri
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based personal agents are increasingly deployed to handle everyday tasks on users' behalf. These agents have access to private user information, while their tasks involve communicating with third parties; this raises a critical privacy concern that agents may inappropriately reveal sensitive user information to these recipients. Existing benchmarks primarily assess direct privacy leakage, where an agent explicitly states a pre-specified secret or attribute. However, they do not capture \textit{inferential leakage}, where the model leaves indirect cues in the reply that implicitly leaks sensitive attributes. We introduce \textsc{InferPriv}, a benchmark that measures whether an honest-but-curious recipient can infer a user's sensitive attributes from an LLM's reply on routine task. Evaluating five frontier models, we find that inferential leakage substantially exceeds direct leakage across models and prompts. Under a privacy-aware system prompt, GPT-6.1-Sol, So

---

### [29] A Unified Arena for LLM Agents across Diverse Eurogame

**链接**: https://arxiv.org/abs/2610.35773
**作者**: Fengrui Zhang and Xiang Li and Ruomeng Ding and Jiayi Yuan and Yuchen Huang and Zhaoyang Han and Xiaoliang Wang and Daoyuan Chen and Yaliang Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive environments offer a practical way to evaluate large language model (LLM) agents, and competitive games extend this evaluation to decisions shaped by competing goals and other agents' choices. Yet existing evaluations confined to individual games or execution frameworks leave unclear which competitive advantages persist across settings. We introduce DECE (Diverse Eurogame Competitive Environments), a unified arena spanning ten Eurogames with shared interfaces and evaluation protocols. These games combine lasting strategic commitments, competition over shared resources, and multiple routes to victory. Our primary study evaluates 12 model-harness configurations, spanning nine models and four execution harnesses, in 480 three-player matches across ten games. The main and supplementary studies comprise 1,032 completed matches in total. These comparisons reveal broad cross-game ranking agreement alongside game-specific strengths. Matched studies show that the same model can perf

---

### [30] Detecting Post-generation Edits to Watermarked LLM Outputs via Error-Correcting Codes

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.2142.pdf&hl=zh-CN&sa=X&d=10867894333205111925&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv5l-LeXhLcAvSIcpDUBG7lh&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=0&folt=kw-top
**作者**: Z Deng, M Siddeek, L Xie, M Mohamed, M Wang… - Findings of the Association …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We evaluate our method on open-source LLM using synthetic edits and demonstrate … , 2017), we propose to embed VT code strings directly into the watermarked LLM output. This … • We propose a watermarking framework that

---

### [31] RubriX: A Fast, Fine-Tunable Non-Autoregressive Rubric Judge

**链接**: https://arxiv.org/abs/2610.34875
**作者**: Balamurugan Paramasivam (1) and Sudalai Rajkumar (1) ((1) CobuildX)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based evaluation asks which level of a rubric a response meets. It is usually done by prompting a large language model (LLM) as a judge, which needs a generative call per judgment and reads every level description, so its cost grows with the rubric. We present RubriX, a rubric judge whose architecture is inspired by contrastive language models (CLM): a LoRA-adapted encoder embeds the input and each level description, and a softmax over scaled cosine similarities gives a probability for every level without text generation. Trained on public rubric data and proprietary synthetic data, RubriX reaches 75.4% exact accuracy on held-out rubrics, against 57.1% for TypeSafe's Jev and 49.8% for a Qwen3-8B judge. On eight human-labelled benchmark sets it is within 6 percentage points of Jev's accuracy on most of them, while Jev keeps a larger lead on two and ranks responses best on average; against the results reported in the G-Eval paper, RubriX outperforms G-Eval with GPT-3.5 on every Su

---

### [32] Satellite Intelligence: Distributed Training, Collaborative Inference,and LLM Adaptation in LEO Constellation

**链接**: https://arxiv.org/abs/2610.35282
**作者**: Zheng Lin, Zhanwei Wang, Yuxin Zhang, Yafei Wang, Ons Aouedi, Zihan Fang 等 (10 人)
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The proliferation of orbital sensing data and the real-time demands of emerging global services are pushing low Earth orbit (LEO) satellite networks from bent-pipe relays toward intelligent onboard processing. This shift confronts a fundamental tension, where modern artificial intelligence (AI) training paradigms require intensive computation, abundant memory, and stable connectivity, all of which are scarce under the dynamic topologies, intermittent links, and severe size, weight, and power (SWaP) constraints of satellite networks. Addressing this tension demands rethinking AI workflows, from training and inference to the emerging deployment of large language models (LLMs), under a constraint-aware design philosophy. To the best of our knowledge, this paper provides the first survey that jointly covers all three, whereas prior surveys examine these aspects in isolation. We begin by identifying the deployment challenge of satellite intelligence (SI) and deriving design principles for S

---

### [33] Training an MoE LLM in MXFP4: How We Closed the Gap to BF16

**链接**: https://arxiv.org/abs/2610.32229
**作者**: Han Wang, Zhitao Wang, Natalia Frumkin, Xuanwu Yin, Alireza Khodamoradi, Dong Li and Emad Barsoum
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] LLM WikiLeaks: Uncovering URL-Based Capability Extension and Security Circumvention in Agentic Message Boards

**链接**: https://arxiv.org/abs/2610.34542
**作者**: Orel Navi, Elad Feldman, Ben Nassi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous agents have been observed acting beyond their assigned tasks, accessing unauthorized systems, and establishing communication channels to exchange information, yet the Web and network-level techniques they use to extend their capabilities and circumvent security restrictions remain poorly understood. We study these techniques through the ProWiki incident, in which agents restricted to outbound HTTP GET requests repurposed a public German-language wiki as a message board. We analyze 14,591 agent edits containing 79,541 URL postings and present corroborating evidence that the published URLs reflect the agents' operational activity. We find that 26,717 URL occurrences (33.6%) embed target URLs within one to five layers of third-party Web services. By recursively reconstructing these nested URLs, we identify 67 distinct intermediate services and classify their functionality. Most intermediate layers (73.8%) extend agents' capabilities by delegating content extraction and transfor

---

### [35] RoleHear: Pseudo-Labeling for Semi-Supervised Role-Attributed Streaming Speech Recognition

**链接**: https://arxiv.org/abs/2610.33765
**作者**: Zefang Liu, Chenyang Zhu, Sangwoo Cho, Xujun Peng, Rongqing Huang, Shi-Xiong Zhang 等 (7 人)
**来源**: cs.CL eess.AS
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Streaming automatic speech recognition transcribes at low latency but produces an unattributed word stream, while real-time applications such as customer-service analytics need each word tied to a speaker role. Role attribution is usually a separate stage, either an offline or streaming speaker-diarization model aligned to the words or a text-based large language model applied to the transcript, and role labels for training are scarce. We present RoleHear, a semi-supervised pipeline that makes a single cache-aware streaming transducer emit roles inline through lightweight in-vocabulary role tokens: a fast turn-boundary marker followed by a per-role token a few words later. An offline transducer teacher, fine-tuned into a role-attributed recognizer, relabels unlabeled audio, and a multimodal large language model supplies silver role labels where gold annotations are unavailable. The streaming student is fine-tuned on the mixture in a single pass. Across customer-service calls with gold 

---

### [36] Build, Don't Play: Self-Improving LLM Research Agents Develop a Hearthstone Battlegrounds AI That Rivals Top Players

**链接**: https://arxiv.org/abs/2610.33845
**作者**: Changlian Ma, Limin Wang
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can LLM agents carry a hard real-world problem from raw data to a system that holds its own against people? We study this in Hearthstone Battlegrounds, an eight-player auto-battler with stochastic shops and battles, hidden information and nearly a thousand interacting cards. We present AutoTavern, a self-improving research system: specialised LLM research agents share a typed research memory, every claim passes verification gates, and live games close the loop, so the agents improve the simulator, opponents and policy and, from the same feedback, their own research process; a human sets goals and rules on ambiguous mechanics. In 20 days AutoTavern built TavernGym, the first faithful, full-content reproduction of the live game, and delivered 23 versions of TavernAgent, trained with PPO against opponents calibrated to real games. TavernAgent plays complete games on the live ladder by itself: its rating rose from 6,000 to about 15,000 and, on the public leaderboard's measure, its last 20 

---

### [37] Curriculum-Guided Acquisition of Hierarchical Task Knowledge from LLM-Generated Experience

**链接**: https://arxiv.org/abs/2610.34677
**作者**: Yuesheng Xu and Hector Munoz-Avila
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hierarchical task knowledge enables efficient problem solving by allowing previously acquired skills to be reused across tasks and problem instances. In this paper, we investigate curriculum-guided acquisition of hierarchical task knowledge in an HTN learning framework. We compare three approaches: online learning during problem solving, human-designed curricula, and an automated curriculum generation procedure that derives learning experiences from verified LLM-generated solution traces. The proposed procedure solves small training problems with an LLM, extracts task accomplishment information, and transforms it into ordered sequences of state-task learning problems for HTN method acquisition. We evaluate the three approaches across multiple planning domains. The results demonstrate that automatically generated curricula recover much of the benefit of expert-designed curricula while substantially reducing the token cost of online hierarchical knowledge acquisition.

---

### [38] S3AC: Stabilized, Selective, and Scalable Actor-Critic for LLM Reasoning

**链接**: https://arxiv.org/abs/2610.35518
**作者**: Shuo Shen, Guangran Cheng, Chengqi Lyu, Xiangsen Wang, Yanan Sun, Wenwei Zhang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Critic-free methods are widely used in reinforcement learning with verifiable rewards (RLVR) for long chain-of-thought (CoT) reasoning, avoiding difficult and costly critic training. Common alternatives lack token-level credit assignment and typically rely on grouped rollouts to estimate prompt-specific baselines. A critic can address both limitations, but long-CoT critic training is hindered by insufficient coverage of trajectories with diverse lengths and early gradients dominated by the newly initialized value head. We introduce S3AC (Stabilized, Selective, and Scalable Actor-Critic) for LLM reasoning, built around a practical critic-training recipe. The trained critic provides token-specific advantages and prompt-specific baselines. Using the prompt-level baseline to estimate difficulty, we propose Difficulty-Aware Prompt Sampling (DAPS). DAPS combines this estimate with outcome history to select prompts before generation, reducing rollout waste without offline difficulty initializ

---

### [39] "Like Taking the Path of Least Resistance": Exploring the Impact of LLM Interaction on the Creative Process of Programming

**链接**: https://arxiv.org/abs/2605.13776
**作者**: Zeinabsadat Saghi, Run Huang, Souti Chattopadhyay
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Constrained Decoding: Harmful or Beneficial? Revisiting Its Impact on LLM Performance

**链接**: https://arxiv.org/abs/2610.35328
**作者**: Ngoc Trinh Hung Nguyen, Alonso Silva, Armen Aghasaryan, Mehwish Alam
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constrained decoding guarantees that Large Language Models (LLMs) produce outputs conforming to predefined formats, but is often assumed to inherently degrade reasoning. We examine this assumption through a taxonomy of three constraint types: \emph{format constraints}, which enforce output structure; \emph{validity constraints}, which mask invalid answer; and \emph{reasoning constraints}, which restrict reasoning trajectories. We theoretically show that appropriate constraints can preserve or improve performance by eliminating invalid paths. Across four model families and eleven open-source models, causal ablations on diverse benchmarks using state-of-the-art constrained decoding strategies reveal that apparent performance degradation largely stems from non-equivalent prompting and output formats rather than from decoder-level masking. Meanwhile, validity constraints improve reliability and extractability by eliminating invalid answers, while reasoning constraints can improve reasoning

---

### [41] Stylistic Evolution and LLM Neutrality in Singlish Language

**链接**: https://arxiv.org/abs/2601.06580
**作者**: Linus Tze En Foo, Weihan Angela Ng, Wenkai Li, Lynnette Hui Xian Ng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] From Hype to ROI: An Economic Model for LLM Adoption in Information Systems and Security Operations

**链接**: https://arxiv.org/abs/2610.33352
**作者**: Pellegrino Casoria, Andrea Araldo, Rosario Patan\`e, Simon Pietro Romano
**来源**: cs.CR cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) promise significant efficiency gains across information-intensive operations by automating repetitive language-based tasks. However, adoption decisions remain largely opportunistic, as organizations struggle to move from pilots to sustainable industrialization. Without systematic economic frameworks, practitioners cannot assess whether LLM investments create value in a given context. This paper develops a general economic model to support informed LLM adoption decisions in operational information systems. Facing high uncertainty, we represent parameters as random variables centered on authoritative benchmarks, and evaluate the model by Monte Carlo simulation across pessimistic-to-optimistic assumptions on LLM efficiency. The ROI distributions show the probability of profitability and the Value at Risk for each configuration, together with a sensitivity analysis of its main drivers. As a first instantiation, we apply the model to Security Operations Centers 

---

### [43] EviGround-CT: Sentence-to-Volume Grounding for Verifying LLM-Generated Chest CT Reports

**链接**: https://arxiv.org/abs/2610.33038
**作者**: Ziyuan Li, Juncheng Ni, Feng Li
**来源**: cs.CL cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chest computed tomography (CT) reports generated by large language models (LLMs) can describe positive findings that lack localized evidence in the scan. We propose EviGround-CT to verify these findings after report generation. A deterministic extractor identifies positive finding sentences, and a 3D grounding model predicts an evidence mask for each sentence. Using the full sentence retains anatomical location, laterality, and descriptive modifiers in the grounding query. We evaluate report generation on CT-RATE, and grounding and verification on a held-out 100-case ReXGroundingCT subset. Using the available annotations, sentence-grounded verification raises evidence-supported precision (ESP) from 0.263 to 0.365 across 137 extracted in-scope positives, compared with category conditioning. The corresponding unsupported positive finding rate falls from 0.737 to 0.635. The paired case-level bootstrap ESP difference is +0.102 (95% confidence interval: [0.028, 0.181]). The predicted masks 

---

### [44] LiveOption: Evaluating LLM Agents in Structured Option Trading with Nonlinear Payoffs

**链接**: https://arxiv.org/abs/2609.33470
**作者**: Haochen Luo, Yifan Li, Binh Minh An, Xiaolong Luo, Zhengzhao Lai, Yuan Zhang 等 (7 人)
**来源**: cs.AI q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] MemComposer: Learning to Assemble Memories for LLM Agents via Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.21091
**作者**: Yixuan Xie, Xueqiang Xu, Xinyi Fan, Xinxi Lyu, Tao Feng, Xing Fan 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Collective Emergent Alignment: Measuring and Amplifying Interaction-Induced Reasoning Alignment in Multi-Agent LLMs

**链接**: https://arxiv.org/abs/2610.34836
**作者**: Boxuan Wang, Zhuoyun Li, Sarvapali D. Ramchurn, Xiaowei Huang, Yi Dong
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) systems can exhibit emergent behaviors through interaction, yet whether a similar phenomenon exists for reasoning alignment remains largely unexplored. We study whether agent interaction produces additional reference-grounded reasoning alignment beyond matched individual self-refinement, and introduce REMAP (Reference-Entailment-Matrix for Agentic Process), a framework that quantifies this effect through Semantic Coverage and interaction-specific alignment gains. Across diverse model families and two multi-hop reasoning benchmarks, we observe broadly positive interaction gains, particularly on reasoning content that depends on integrating evidence distributed across agents. These gains are consistently associated with independently measured peer-information recovery, while further analysis reveals composition-dependent heterogeneity effects and asymmetric information transfer across agent capability levels. Motivated by these findings, we further 

---

### [47] WebViSE: Scaling Visual Design Intelligence from the Open Web for LLM Website Generation

**链接**: https://arxiv.org/abs/2610.33929
**作者**: Yifei Sun, Peng Zhao, Le Zhang, Bingjin Chen, Zhengfan Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have made remarkable strides in website development, enabling complete and interactive web experiences to be built from natural-language instructions with far less effort. Yet, non-expert users often struggle to articulate sophisticated visual and interaction designs in natural language. Meanwhile, the open web already contains a vast reservoir of such design knowledge, embodied in mature website implementations. To this end, we introduce Website-derived Visual Skill Extraction (WebViSE), a framework that automatically abstracts these implementations into reusable Visual Skills and builds a structured Skill library. To scale the library, WebViSE organizes its Skills in a multi-parent DAG and jointly evolves Skill descriptions and DAG structure using Skill-conditioned Potential Queries, enabling efficient matching between diverse user instructions and relevant Skills. The auto-evolved structure outperforms non-hierarchical LLM retrieval baselines at only 39.09% of 

---

### [48] 6G Reasoning Agent Societies: Composition, Scaling, and Consistency-Time Laws

**链接**: https://arxiv.org/abs/2610.34357
**作者**: Hatim Chergui, Carolina Fern\'{a}ndez-Mart\'{i}nez, Mustapha Benjillali, Mehdi Bennis, Merouane Debbah
**来源**: cs.NI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emerging 6G control planes would compose Large Language Model (LLM) agents that exchange interpreted conclusions, so hallucinations can propagate even over error-free transport. Recent architectures audit each message locally against the sender's observation mask, but isolated audits miss collective behavior. Modeling the agent society as a cellular sheaf, we establish three laws valid on arbitrary topologies. First, the \emph{composition law}: network-wide divergence exceeds the sum of per-agent audit scores by exactly their hidden total correlation. This blind spot masks up to 23\% of joint divergence and, because the declared signal cancels in the cognitive signal-to-noise ratio (SNR), overstates it by $1.14$\,dB purely through topology; the resulting trust inflation preserves valid consensus states but slows convergence. Second, the \emph{scaling law}: reconciliation decouples across metric counters, so the worst-connected dimension sets the pace. Consistency time grows for a socie

---

### [49] Human-LLM Alignment in Language Attitudes Toward Non-Native Japanese

**链接**: https://arxiv.org/abs/2608.01629
**作者**: Naho Orita, Hayato Ogawa, Daisuke Kawahara
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Necessary but Not Sufficient: Temperature Control and Reproducibility in LLM-as-Judge Safety Evaluations

**链接**: https://arxiv.org/abs/2606.26185
**作者**: Hiroki Tamba
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] LTEM: LLM-Friendly Table-Enhanced Markdown for Table Understanding and Generation

**链接**: https://arxiv.org/abs/2610.29188
**作者**: Eunbin Kim, Hyeonseok Kang, Sangkeun Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] Broken on Arrival: Non-Functional Quantized LLM Artifacts in Public Model Registries and How to Catch Them

**链接**: https://arxiv.org/abs/2609.05881
**作者**: Aditi Patodiya
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] AutoSwarm: Automating Agent Swarms

**链接**: https://arxiv.org/abs/2610.33048
**作者**: Zhonghang Li, Zongwei Li, Chao Huang
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly automate complex tasks, with multi-agent systems seeking further performance gains through specialization and collaboration. However, distributing work across agents does not automatically yield complementary contributions, and inter-agent dependencies can turn local errors into task failure. To address these challenges, we propose AutoSwarm, a multi-agent framework for collaborative problem solving. Collaboration formation jointly defines responsibility boundaries and conditions for acceptance and downstream use, grounding capability allocation in contributions that other agents can assess and integrate toward a shared objective. Execution coordination couples agents' local progress through a shared state, using dependencies and supervisory relationships to govern agent activation, result handoffs, and integration while adapting subsequent actions to review feedback and emerging blockers. Experiments spanning long-horizon programming, int

---

### [54] Trace Integrity for LLM Data Agents: Auditing Structured-Data Computation Beyond Answer Accuracy in Real-World Systems

**链接**: https://arxiv.org/abs/2608.26036
**作者**: Srimonti Dutta and Akshata Kishore Moharir
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Scoped Semantic Invariance as a Foundation for LLM Reliability

**链接**: https://arxiv.org/abs/2610.33267
**作者**: Rosario Uceda-Sosa and Maria Chang and Karthikeyan Natesan Ramamurthy and Moninder Singh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs often answer semantically equivalent queries inconsistently, even when the underlying facts are known. We formalize consistency as semantic invariance over equivalence classes of queries and show that invariance under arbitrary meaning-preserving transformations is undecidable in general. This motivates scoped semantic invariance, where model behavior is evaluated relative to bounded semantic domains. We operationalize this framework using knowledge graphs (KGs), which act as explicit semantic control structures defining local semantic constraints and grounding contexts. Across the MITRE D3FEND ontology and eight Wikidata- derived domains, we show that inconsistencies are structured rather than random, concentrating in localized hotspot subgraphs organized around recurring TREE, STAR, and CYCLE patterns that remain stable across models and domains. We further show that selective graph grounding improves correctness and cross-model consistency, while indiscriminate grounding introd

---

### [56] TrustJev: Separating Policy Authority from Untrusted Evidence in LLM-Based Decisions

**链接**: https://arxiv.org/abs/2610.34826
**作者**: Zhiwei Xu, Xuyang Liu, Xiaolin Peng, Weixian Deng, Jiabao Gao, Zirui Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision models enable software to select from predefined actions using natural language inputs. However, the external evidence that supplies facts for these decisions may also contain instructions that attempt to override the application's policy. We propose TrustJev, a framework combining protected policy scoring with bounded evidence corrections. A single Transformer backbone computes policy scores and a correction budget from trusted policy and candidates, then bounds evidence corrections by that budget. Paired supervision encourages stable predictions under instruction insertions that preserve task facts and changed preferences when edits change the correct answer. Authority supervision accommodates evidence when the policy alone cannot determine the decision. We evaluate a 0.6B implementation against 14 baselines on three datasets covering authentication, instruction hierarchy, and executable authorization rules. TrustJev achieves the highest mean Balance, the harmonic mean of ac

---

### [57] C-SafeGen: Certified Safe LLM Generation with Claim-Based Streaming Guardrails

**链接**: https://arxiv.org/abs/2610.34961
**作者**: Mintong Kang, Zhaorun Chen, Bo Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the remarkable capabilities of large language models (LLMs) across diverse applications, they remain vulnerable to generating content that violates safety regulations and policies. To mitigate these risks, LLMs undergo safety alignment; however, they can still be effectively jailbroken. Off-the-shelf guardrail models are commonly deployed to monitor generations, but these models primarily focus on detection rather than ensuring safe decoding of LLM outputs. Moreover, existing efforts lack rigorous safety guarantees, which are crucial for the universal deployment of LLMs and certifiable compliance with regulatory standards. In this paper, we propose a Claim-based Stream Decoding (CSD) algorithm coupled with a statistical risk guarantee framework using conformal analysis. Specifically, our CSD algorithm integrates a stream guardrail model to safeguard sequential claims generated by LLMs and incorporates a backtracking mechanism to revise claims flagged with high safety risks. We 

---

### [58] How Humans Learn Unfamiliar Worlds: A Think-Aloud Dataset on ARC-AGI-3

**链接**: https://arxiv.org/abs/2610.34523
**作者**: Shuzhi Liu and Archana Warrier and Dat Nguyen and Chengqi Zheng and Kevin Ellis and Yewen Pu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning through exploration and using newly acquired knowledge to achieve goals are central capabilities of general intelligence. Understanding these capabilities requires tracing how learners build, use, and revise world models during interaction. We construct the first dataset that records how humans discover and use the mechanisms of novel environments, using ARC-AGI-3 as a testbed: 144 trajectories from 64 participants across 25 public games, each pairing time-synchronized actions with think-aloud audio, plus 250 trajectories from large language model (LLM) agents with and without harnesses on the same games. We annotate mechanism triggers and recognition, action purposes, and errors and recovery, linking changes in understanding to the observations and actions that support them. We analyze characteristics of human cognition and compare them with those of LLM agents. Both groups anticipate mechanisms and use familiar analogies. Qualitative representations are more common in succes

---

### [59] What Effort Level Should I Choose? On the Economics of Reasoning Effort in LLM Agents

**链接**: https://arxiv.org/abs/2610.34491
**作者**: Kaiser Sun, Yongchan Kwon, Zain Hasan, Shang Zhu, Kaitlyn Zhou, Federico Bianchi
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative models increasingly expose a reasoning effort setting that lets users scale inference-time compute, trading higher cost for potentially improved performance. Users must choose an effort level before knowing whether extra reasoning will help, and even a successful run does not reveal whether the effort purchased was necessary. Reasoning effort is therefore a credence good: buyers observe the outcome but cannot assess the marginal value of the computation they paid for. In this work, we measure the counterfactual effect of effort levels on both proprietary and open-weight models on four benchmarks, spanning single-call reasoning and long-horizon agentic tasks. Effort, it turns out, does not consistently preserve tasks that lower effort solves, can overspend, and can change trajectory behavior. First, we find that although higher effort can raise accuracy in aggregate, it frequently fails on tasks that lower effort solved. Second, on the subset of easy tasks that every effort l

---

### [60] VerifyMAS: Hypothesis Verification for Failure Attribution in LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2605.17467
**作者**: Hezhe Qiao, Hanghang Tong, Ee-Peng Lim, Bing Liu, Guansong Pang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Transformer to GPT-5: Advancements, Limitations, and Future Directions in Large Language Model Design

**链接**: https://arxiv.org/abs/2610.34281
**作者**: Harsidak Singh Banwait, Chander Prabha
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have revolutionized Artificial Intelligence (AI) by their extraordinary capabilities, like contextual understanding, few-shot/zero-shot learning, code generation, ability to reason and problem-solving. Recent studies have shown immense work on LLMs. Yet, there is limited work on the thorough taxonomy of LLMs. This study would showcase a detailed classification of LLMs, starting with the earlier models like BERT and leading to LLMs like GPT, Gemini, Claude and Grok. We would delve into topics like datasets used to train LLMs, computational power used during training, their hardware specifications, architecture and parameters. Further, we would also look at the limitations, computational challenges and open problems as well. This study would primarily focus on the timeline of LLMs, signifying their growth over the period. Findings reveal a clear pattern: models that optimize the ratio between architectural complexity and data quality exhibit stronger reasonin

---

### [62] Beyond 0-100: How Confidence Scale Design Shapes Verbalized Confidence and LLM Metacognition

**链接**: https://arxiv.org/abs/2603.09309
**作者**: Yuyang Dai, Yuxia Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] What Makes a Question Curious? Measuring Model Curiosity in Human-LLM Interactions

**链接**: https://arxiv.org/abs/2610.33950
**作者**: Angana Borah, Rachana Ramchandar, Inderjeet Nair, Rada Mihalcea
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly act as partners in everyday communication. In these interactions, useful assistance may require not only answering, but also asking the right questions that surface knowledge gaps, assumptions, and alternatives. In this study, we refer to such epistemic question-asking as model curiosity, and introduce a theory-grounded taxonomy that distinguishes curiosity-oriented questions from generic model questioning. Across four conversation datasets, we find that curiosity-oriented questions remain rare (17-28% of all questions), but are associated with more exploratory and epistemically rich subsequent user responses, with varying patterns across datasets. We further conduct a human study to evaluate the usefulness of model curiosity, finding that curiosity can encourage exploration, especially in advice, creative, and research contexts. These findings have implications for building LLMs that ask more selectively to support deeper exploration and human-AI col

---

### [64] Position, Role or Label? A Controlled Study of Instruction Conflicts in LLM Agents

**链接**: https://arxiv.org/abs/2610.33201
**作者**: Anish Laddha, Nitesh Pradhan, Gaurav Srivastava
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents take instructions from the operator, repository configuration, user, tool results and saved memory, which often conflict. Instruction-hierarchy benchmarks ask whether the higher-ranked source wins, but a source sets position, role and label at once. First, we build WhoWins, 1,080 code-scored scenarios in five task types, each with up to five mutually exclusive instructions, and seven controlled experiments that vary only how instructions are delivered. Second, we study 14 open-weight models (0.6B to 122B, thinking off and on) over 1,887,356 scored replies, checking main findings on held-out scenarios. Inside one message the first of two conflicting lines wins 72.42 to 94.66%, and across messages it keeps 22.95 to 62.65%. A policy sent first in the system (or developer) message loses most conflicts with later lines in every Qwen model but wins most on gpt-oss when it acts. In tool and file-write tasks it wins less often than the same text sent first as a labelled user message

---

### [65] SRA: Selective Residual Adaptation for LLM Reasoning Enhancement

**链接**: https://arxiv.org/abs/2610.34199
**作者**: Zhenxing Dou, Kun He, Mingyang Yi, Yong Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge distillation transfers reasoning capabilities from large language models to lightweight students. However, distilled small models still struggle with multi-step reasoning. We observe that the distribution divergences between teacher and student models along reasoning paths are highly sparse, and target tokens almost always fall within the student top-$K$ candidate set. Based on this finding, unlike approaches updating student backbones or requiring runtime teacher computation, we propose Selective Residual Adaptation (SRA), a plug-and-play framework that internalizes localized corrections. Concretely, SRA employs a Discrepancy Gate to identify divergence positions alongside a Candidate Residual Adapter for top-$K$ logit calibration to correct the mismatch. Theoretically, we establish error bounds ensuring strict sequence level performance gains. Across mathematical benchmarks on Qwen3 models from 0.6B to 4B, SRA consistently enhances distilled student models, raising average 

---

### [66] Investigating and Alleviating Harm Amplification in LLM Interactions

**链接**: https://arxiv.org/abs/2606.02423
**作者**: Ruohao Guo, Wei Xu, Alan Ritter
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] AskGLP1: A Knowledge Graph LLM Agent for Exploring GLP-1 Experience from Online Patient Narratives

**链接**: https://arxiv.org/abs/2610.34987
**作者**: Zhaoqian Xue, Anay Somani, Siddhartha Singh, Junting Mu, Zhongyin Wang, Haozheng Liu 等 (10 人)
**来源**: cs.CL cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> GLP-1 medications are increasingly used for weight management, and many people share their experiences online. These narratives show why people take the drugs and what they experience, but they remain unstructured and disconnected from formal pharmacovigilance. We therefore present AskGLP1, a system that transforms online patient narratives into a knowledge graph (KG) and answers questions about medication experiences. Through an LLM-assisted pipeline grounded in the MedDRA terminology, AskGLP1 screens nearly 8.5 million Reddit posts for medication experiences and distills 163,135 of them, with 2,506 WebMD reviews, into a KG of 385,790 drug-side-effect and drug-purpose relations. We find that GLP-1 experiences are source- and drug-specific. Online narratives share the most common gastrointestinal symptoms with FAERS, but they foreground everyday burdens such as fatigue and food aversion, whereas FAERS reports more often include injection-site reactions and selected serious diagnoses su

---

### [68] Advancing SVD-based LLM Compression via Layer-Wise Error Model Search

**链接**: https://arxiv.org/abs/2610.32878
**作者**: Moritz Thoma, Maximilian Groezinger, Maximilian Forstenh\"ausler, Emad Aghajanzadeh, Manoj Rohit Vemparala, Christos Anagnostopoulos 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Beyond Behavioral Accuracy: Evaluating Individual-Level Fidelity in LLM Investor Simulation

**链接**: https://arxiv.org/abs/2610.26524
**作者**: Jiajie He, Yuanhong Jiang, Xintong Chen, Dongling Ni, Wenjin Liu
**来源**: cs.AI cs.HC cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] Broken Symmetry in LLM Refusal: Answer Release Is More Local Than Refusal Restoration

**链接**: https://arxiv.org/abs/2608.15772
**作者**: Yiqi Liu, Yang Wang, Songxin Wang, Chenghao Xiao, Chenghua Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] SHIFT-JEV: Certified Abstention and Gain-Gated Continual Adaptation for LLM-Based Decision Models under Distribution Shift

**链接**: https://arxiv.org/abs/2610.34329
**作者**: Muhammad Atif Saeed, Azka Atiq, Adarsh Kumar, Akhtar Jamil, Uzair Iqbal, Roland Aydin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can act as decision models that return a probability distribution over a fixed set of options, but deployed decision models face domain, label-prior, emerging-class and candidate-set shift. We study how such models fail under shift and propose SHIFT-Jev, a monitoring, abstention and continual-adaptation procedure for them. It scores the risk of each decision from uncertainty, format and option-consistency signals, certifies abstention thresholds with Learn-then-Test, monitors the decision stream with drift and label-shift detectors, and accepts a model update only when an expected-gain gate finds a significant held-out improvement without loss on earlier regimes. On a benchmark of ten shifted test environments with Qwen3-0.6B and Qwen3-4B (three seeds each) and Phi-4-mini, fine-tuning with KL anchors and temperature scaling lowers calibration error under shift from 0.289 to 0.087. At a target risk of 10%, a learned uncertainty score with a certified thresho

---

### [72] Free to Look, Free to Reason: Simple LLM Harnesses Outdiagnose Hand-Crafted Root Cause Analysis Agents

**链接**: https://arxiv.org/abs/2610.35767
**作者**: Tingzhu Bi, Xun Zhang, Jinglin Li, Ping Wang, Meng Ma
**来源**: cs.AI cs.DC cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Root cause analysis (RCA) of microservice failures has attracted many LLM agents whose investigation is hand-crafted, through standard operating procedures, fixed stages and role agents. Each is evaluated on its own data against few baselines, so it is unknown whether this design beats letting a capable model investigate on its own. We compare three simple harnesses that prescribe none of the model's calls (one call over an evidence package, a SQL agent and the Codex coding agent) with five published LLM RCA agents and with statistical and causal methods on RCAtlas, 90 validated cases from eight public datasets, across six models and three reasoning efforts. The simple harnesses are the most accurate (PR@1 65-77% on three mid-tier models), ahead of the published agents (16-53%) and the non-LLM methods (6-39%), on every model on which both families were run. The published agents fix from a tenth to all of their model calls in the program, and a case study shows how these prescriptions s

---

### [73] Compaction as Epistemic Failure: How Agentic LLM Tools Fabricate Confirmed Results from Killed Processes

**链接**: https://arxiv.org/abs/2607.13071
**作者**: Hiroki Tamba
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] A Framework for Automated Multi-Source Satellite Data Analytics and LLM-Based Report Generation

**链接**: https://arxiv.org/abs/2610.05625
**作者**: Hind Yousif Alhammadi, Isam Mashhour Al Jawarneh
**来源**: cs.AI astro-ph.IM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] Scaling Qualitative Analysis with Large Language Models: Development and Validation of the Smart Coder Framework for Human-LLM Collaborative Coding

**链接**: https://arxiv.org/abs/2610.33205
**作者**: Cheng Tang, Kun Wang, Yaxuan Yang, Shiyu Wang, Allan Cohen, Rachael Eriksen Brown 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current uses of large language models (LLMs) for qualitative coding often rely on ad hoc prompting with limited guidance for reliability and human oversight. To address these limitations, we propose the Smart Coder Framework, a three-phase approach structuring human-LLM collaborative coding through Instruction, Prompt Strategy, and Reliability Check. We evaluated the framework using 72 middle-school mathematics teacher interview transcripts and a human-consensus benchmark. A factorial design compared instructed versus uninstructed prompts, few-shot versus few-shot plus chain-of-thought prompting, and single-pass versus self-consistency coding. Twelve transcripts were used for prompt development and calibration, and 60 for the formal evaluation. In the results, instruction consistently improved agreement. Chain-of-thought further improved agreement under adequate instruction, and self-consistency produced smaller, theme-dependent gains but helped identify unstable decisions for human re

---

### [76] Local Entropy Fluctuations for Black-Box LLM-Generated Text Detection

**链接**: https://arxiv.org/abs/2610.33767
**作者**: Xinpeng Wang, Bruce Rushing, Zhizhen Chen, Zhe Zeng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-shot detection of machine-generated text is vital for mitigating the risks of large language models (LLMs) misuse. While the state-of-the-art dual-model detectors and resampling-based detectors outperform single-model statistical detectors on unprompted continuations, they suffer a catastrophic breakdown on instruction-conditioned text in the black-box setting, where the source model is unknown. We analyze this failure and trace it to poor prompt conditioning for resampling-based methods and diminished cross-model discrepancy for dual-model detectors. Motivated by recent studies that human writing maintains a steady, uniform information flow, whereas machine-generated text exhibits sharp, localized entropy fluctuations, we propose a new metric, the Relative Peak Prominence Rate (RelPPR) to capture this structural contrast along the entropy trajectory and further leverage it as a signal for LLM-generated text detection. Extensive evaluations across diverse model families and datase

---

### [77] Knowledge-Guided LLM for Intent-Driven Service Orchestration in Integrated Terrestrial and Non-Terrestrial 6G Networks

**链接**: https://arxiv.org/abs/2610.33007
**作者**: Wajdi Hammami, Irfan Azam, and Soumaya Cherkaoui
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language service intents in integrated terrestrial and non-terrestrial (TN/NTN) 6G networks can be incomplete, ambiguous, or inconsistent, making unconstrained LLM generation challenging for reliable network-facing orchestration. This paper proposes a knowledge-guided LLM framework that combines grammar-constrained semantic parsing with a knowledge-graph (KG)-driven clarification loop to produce validated, orchestration-ready service profiles across four representative service classes. On a 200-sample intent dataset, the framework achieves 89% classification accuracy and 95% policy validity with an average of 0.66 clarification turns per request. Compared with a Pure-LLM baseline, the proposed framework improves policy validity and contradiction detection while requiring fewer clarification turns, demonstrating the value of explicit knowledge-guided reasoning for robust intent processing in integrated TN/NTN 6G orchestration.

---

### [78] Real-Time Deadlines Reveal Fragile Temporal Adaptation in LLM Strategic Dialogues

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.765/&hl=zh-CN&sa=X&d=11596405757054650977&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv5cRjCkb3ZIQf5D4dihGZ7Y&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=8&folt=kw-top
**作者**: N Sehgal, SC Guntuku, L Ungar - Proceedings of the 2026 Conference on Empirical …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large Language Models (LLMs) generate text token-by-token in discrete time, yet real-world communication, from therapy sessions to business negotiations, critically depends on continuous time constraints. We use simulated negotiations between

---

### [79] Small Edits, Shifting Decisions: Benchmarking LLM Accuracy and Reliability on French Input Variants

**链接**: https://arxiv.org/abs/2610.33493
**作者**: Jiaming Yu, Xiaotian Xie, Jian Ma, Yingjie Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> French users may omit apostrophes and diacritics or make keyboard typos in everyday input. The effects of these common variations on language model performance and prediction reliability remain insufficiently understood. To address this gap, we construct a controlled French surface-variant benchmark covering seven task types, with 4,200 original-low-high triplets (12,600 input instances). Each high-intensity variant retains all low-intensity edits and adds further changes. We evaluate six models from two LLM families. The results show that accuracy decreases and Brier score and negative log-likelihood (NLL) increase with perturbation intensity. Larger models show smaller accuracy losses under high intensity, but increases in Brier score and NLL do not consistently decrease with scale. Keyboard typos cause the largest losses in accuracy and the quality of predicted probabilities at the predefined high-intensity settings. Finally, calibration temperatures fitted on original inputs transf

---

### [80] Automatic Configuration of LLM Post-Training Pipelines

**链接**: https://arxiv.org/abs/2603.18773
**作者**: Channe Chwa, Xinle Wu, Yao Lu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] Belief-Conditioned Multi-Agent Actor Critic for Decentralized LLM Collaboration

**链接**: https://arxiv.org/abs/2610.35398
**作者**: Tianle Chen, Shuo Liu, Christopher Amato
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work has explored optimizing LLM collaboration through Multi-Agent Reinforcement Learning (MARL), but many approaches still rely on predefined workflows, limiting efficiency and scalability. Decentralized LLM collaboration is challenging because agents execute independently with limited communication, share a joint objective, and must infer useful information from communication traces. In this paper, we propose BCMAAC, a Belief-Conditioned Multi-Agent Actor-Critic method that maintains beliefs over contextual information and uses them to facilitate training. Experiments on Minecraft game-playing, web searching and tool-using tasks show that BCMAAC improves task performance and collaborative behavior compared to naive actor-critic baselines. The improvements are particularly pronounced in multi-turn tasks with richer contextual information, where belief modeling provides a clear advantage.

---

### [82] Fast KVzip: Efficient and Accurate LLM Inference with Gated KV Eviction

**链接**: https://arxiv.org/abs/2601.17668
**作者**: Jang-Hyun Kim, Dongyoon Han, Sangdoo Yun
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] OptiCom : A Unified Framework for State-Conditioned Composition in LLM-Driven Optimization

**链接**: https://arxiv.org/abs/2609.37221
**作者**: Chenxing Wei, Sichen Liu, Lizhao Liu, Ningyuan Sun, Chen Bingzhou, Ying He 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] LLM-Augmented Agent-Based Simulation of Cyber Social Agents

**链接**: https://arxiv.org/abs/2610.32988
**作者**: Lynnette Hui Xian Ng, Kathleen M. Carley
**来源**: cs.MA cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social media bots are often portrayed as malicious automations to be detected and removed, but automation on social media platforms encompasses a wide spectrum of roles, behaviors, and rhetorical strategies that can shape online discourse in both constructive and destructive ways. This work conceptualizes these automated actors as \textbf{Cyber Social Agents} through a taxonomy of archetypes characterized by their operational tactics and rhetorical style. We integrate this taxonomy into an LLM-driven social simulation, where agents communicate and coordinate in a network environment. Using empirically grounded CSA personas, we simulate heterogeneous online societies to study how agent diversity shapes information diffusion and social influence. Our approach bridges the gap between rule-based agent models and LLM-powered simulations with generated agents that are parameterized from empirical data.

---

### [85] Unified Context Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2606.02304
**作者**: Zixuan Zhu, Yitong Hu, Yong Dai, Junfeng Fang, Chunyang Jiang, Senkang Hu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Semantic Atoms for Scalable Text Analysis in Data Analytics in the Era of LLM-Based Agents

**链接**: https://arxiv.org/abs/2610.34860
**作者**: Jinxiang Xie, Zihao Li, Rui Ding, Bartuer Zhou, Shi Han, Dongmei Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Much of the information needed for data analysis is buried in text columns: an analyst may infer customer frustration from complaint text and use it to explain resolution time. We call workloads in which processing text columns is central to subsequent data analysis TADA (\emph{Text Analysis in Data Analytics}). In an agentic setting, the user's query dynamically specifies this processing, and answering it interleaves LLM-based semantic steps with exact SQL or Python operations. This mixed execution raises two design questions: which work should be neural and which symbolic, and which semantic outputs later steps can reuse. We address them for agent-planned TADA workflows with two complementary, query-driven semantic atoms. Each atom takes a sequence of text items and a natural-language query specifying the semantic task: \textbf{Tagging} returns one string per input item, while \textbf{Categorization} returns $M$ category objects over $N$ input items. Tagging results are materialized 

---

### [87] FlexMARL: Graph-Driven Rollout-Training Co-Design for LLM-Based Multi-Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2602.09578
**作者**: Zhida Jiang, Zhaolong Xing, Jiawei Lu, Yipei Niu, Qingyuan Sang, Liangxu Zhang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] TwinRouterBench: Fast Static and Live Dynamic Evaluation for Realistic Agentic LLM Routing

**链接**: https://arxiv.org/abs/2605.18859
**作者**: Pei Yang, Wanyi Chen, Tongyun Yang, Pengbin Feng, Jiarong Xing, Wentao Guo 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] A Theory-Guided LLM Pedagogical Agent Supporting Open-Ended STEM+C Learning

**链接**: https://arxiv.org/abs/2605.30539
**作者**: Clayton Cohn, Surya Rayala, Siyuan Guo, Hanchen David Wang, Naveeduddin Mohammed, Umesh Timalsina 等 (10 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] LLMs in Cloud: A Discussion on Architecture, Orchestration, and Inference

**链接**: https://arxiv.org/abs/2610.33475
**作者**: Jannatun Noor, Athar Noor Mohammad Rafee, Md. Sadman Haque, Sreezon Das Gupta, Atiar Osman, Md. Abu Obaida Zishan
**来源**: cs.DC cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The widespread deployment of foundational Large Language Models (LLM) across cloud datacenters marks a fundamental paradigm shift from stateless deep learning toward distributed, memory-intensive generative workloads. However, serving massive foundation models under stringent Service Level Objectives (SLO) exposes critical physical and system bottlenecks. These challenges include the persistent High Bandwidth Memory (HBM) wall, operational asymmetry between compute-bound prefilling and memory-bandwidth-bound decoding, explosive Key-Value (KV) cache expansion, prohibitive serverless cold starts, and hardware reliability vulnerabilities. Existing literature reviews remain layer-siloed, decoupling low-level accelerator virtualization from cluster orchestration and runtime inference, while largely overlooking defining advancements from 2024 to 2026. To address these limitations, this study presents a comprehensive, cross-layer systematic review guided by the Preferred Reporting Items for S

---

### [91] Beyond Prompts: A Systematic Study of LLM-Based Machine Translation Evaluators

**链接**: https://arxiv.org/abs/2610.33741
**作者**: Dmitry Popov, Roman Bokhyan, Ekaterina Enikeeva, Artem Mekhraliev, Stepan Vysotsky, Nikolay Karpachev
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based evaluators have rapidly become a standard tool for machine translation evaluation, yet the design choices that shape their behavior remain poorly understood. We present a systematic study of how instruction design, few-shot demonstrations, backbone model choice, and multi-step workflows affect span-level and ranking-based MT evaluation. We collect new expert RATE annotations on WMT24 and WMT25 English-Russian translations, with transfer validation on MQM- and ESA-annotated benchmarks across five additional language pairs. Our experiments reveal four robust findings: instruction structure shapes evaluator behavior, high-quality demonstrations matter more than quantity, frontier backbones exhibit distinct evaluator profiles (recall-, precision-, or ranking-oriented), and fusing outputs across diverse backbones outperforms single-evaluator multi-call setups. Although evaluator design exposes a large combinatorial space, several discovered design principles transfer consistently 

---

### [92] A Stratified Multi-Rater Evaluation of LLM-Based Virtual Standardized Patients with a Deployed Data-Generation Platform

**链接**: https://arxiv.org/abs/2610.29312
**作者**: Yongjin Yi, Jinyong Park, Sejoong Kim
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory

**链接**: https://arxiv.org/abs/2406.14373
**作者**: Gordon Dai, Weijia Zhang, Jinhan Li, Siqi Yang, Chidera Onochie lbe, Srihas Rao 等 (7 人)
**来源**: cs.AI cs.CL cs.CY cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] SPARTA: A Sparse Ternary LLM Accelerator with Adaptive Attention and Unified Datapath for Long-Context Edge Inference

**链接**: https://arxiv.org/abs/2610.34824
**作者**: Yanzhen Zhou, Zhengyu Han, Qunyou Liu, Zheyu Yan, Weihong Xu, Cheng Zhuo
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs on edge devices are constrained by limited memory and bandwidth. Although 1.58-bit ternary weights greatly reduce model storage, long-context inference is increasingly bottlenecked by KV-cache traffic and attention. Existing accelerators also use separate datapaths for ternary linear layers and attention, incurring hardware and execution overhead. We present SPARTA, a sparse ternary LLM accelerator for efficient long-context edge inference. SPARTA integrates: (1) a phase-aware sparse dataflow exploiting heterogeneous sparsity across compute-bound prefill and memory-bound decode; (2) a unified compute fabric mapping ternary SpMM/SpMV and bit-serial attention onto shared processing elements to exploit zero-weight and zero-bit sparsity; and (3) an adaptive two-stage attention engine combining page-level Top-k selection to reduce K-cache accesses with token-level Top-p pruning to reduce V-cache traffic. SPARTA reduces KV traffic by 4.1-4.8x over full attention and 1.3-1.5x over a stat

---

### [95] Beyond LLM-GA: Secure Fluid Antenna Systems with ReEvo-Designed Memetic Algorithm

**链接**: https://arxiv.org/abs/2610.10235
**作者**: Hanyong Xu, Zhaolai Dang, and Tong Zhang
**来源**: cs.IT cs.AI math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [96] Reviewing the Reviewer: LLM -Assisted Reviewer Feedback Generation for Guideline Compliance

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.1317.pdf&hl=zh-CN&sa=X&d=14669776102689509171&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv4MN1J8fczLgOGuaoyZtIpV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=2&folt=kw-top
**作者**: S Purkayastha, Q Wan, A Lauscher, L Qu, I Gurevych - Proceedings of the 2026 …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We introduce an LLM -driven framework that decomposes reviews into argumentative segments, identifies issues violating ACL Rolling Review (ARR) guidelines, and generates targeted feedback using issue-specific templates refined

---

### [97] A Survey on Long-Term Memory Security in LLM Agents: Attacks, Defenses, and Governance Across the Memory Lifecycle

**链接**: https://arxiv.org/abs/2604.16548
**作者**: Zehao Lin, Xixuan Hao, Renyu Fu, Shaobo Cui, Kai Chen, Chunyu Li 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] LLM-as-a-Judge Version Shift: The Instrument Changed, Not the Standard

**链接**: https://arxiv.org/abs/2610.32986
**作者**: Guijia Zhang, Harry Yang
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated research pipelines increasingly rely on fixed LLM judges to rank, filter, and revise proposals, yet these judges are routinely replaced by newer versions. We study whether such replacements preserve the underlying measurement standard. Using a preregistered, frozen-weight design, we evaluate three adjacent same-family transitions across Qwen, Gemma, and Mistral on frozen ML research proposals under randomized information conditions. The common assumption that newer judges are simply harsher fails: two transitions shift toward greater leniency, while the third shifts in the opposite direction on anchors but attenuates off-anchor. More importantly, version changes can alter not only score location but also criterion geometry and resolution; one transition collapses clean-flawed discrimination, placing 93% of pool scores on a single value. Supplying identical facts does not close the version gap, placebo-controlled interventions show that observed packet effects are largely form

---

### [99] Forecast-Dojo: Replayable Environments for Benchmarking and Training LLM Forecasting Agents

**链接**: https://arxiv.org/abs/2609.28876
**作者**: Liqin Ye, Haorui Wang, Fardin Ahmed, Rongzhi Zhang, Yuan He, Ziyuan Lin 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] Build or Adopt? Custom-Built vs. General-Purpose LLM Agent Harnesses for Automotive GUI Testing

**链接**: https://arxiv.org/abs/2610.33636
**作者**: Arsham Gholamzadeh Khoee, Ruyu Fu, Jiaqi Wei, Ruikun Deng, Robert Feldt, Dhasarathy Parthasarathy 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As general-purpose LLM agent harnesses mature, organizations must decide whether to continue developing in-house systems or adopt existing alternatives. We study this decision at Volvo Group for GUI testing of Android-based in-vehicle infotainment (IVI) systems. We compare a production, custom-built harness with two general-purpose harnesses, Claude Code and OpenCode, keeping the tools, accessed through the Model Context Protocol (MCP), and the models the same. We evaluate the harnesses with up to four models on Volvo's IVI test cases and on open-ended tasks in public apps (Google Maps, Booking.com), and interview ten practitioners: developers, the product owner, and testers. On Volvo's stepwise IVI tests, general-purpose harnesses match the custom-built harness in success but vary more across runs. Their inference cost per task is 2.6-10.7 times higher, yet the engineering effort they save outweighs this: for a nightly IVI regression suite, total monthly cost, including engineering ef

---

### [101] LLM-Generated Counterfactual Stress Scenarios for Portfolio Risk Simulation via Hybrid Prompt-RAG Pipeline

**链接**: https://arxiv.org/abs/2512.07867
**作者**: Masoud Soleimani
**来源**: q-fin.RM cs.AI econ.EM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] ProbeID: Verifying MCP Tool Identity for LLM Agents under Registry Drift

**链接**: https://arxiv.org/abs/2610.33633
**作者**: Guanxing Chen, Sining Zhang, Haohuai He, Qiujie Lv, Yu-An Huang, Zhi-An Huang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents select tools by copyable descriptions, which cannot establish which implementation runs. ProbeID compares canonicalized responses to schema-valid probes with a trusted admission reference and abstains on ambiguity, so a squatter must copy probe-observable behavior. With the gold present, independent probes and a fixed margin, standard concentration arguments give a shared probe budget logarithmic in the candidate count and bound the joint probability of a wrong decision. On cached MCP-IdentityDrift cases, strict choice reaches \(0.956\) hit@1 while description routers fall near chance, but simpler exact comparisons tie it, MMD better tolerates heavy value noise, and a 32B behavioral judge is similarly accurate at higher cost. Random probes from agent banks and a prospective held-out study of 38 tools test theory-set thresholds. On the agent banks, equality refuses every reachable replacement from 64 probes and the bounded distance from 512, and sharper post hoc gates halve both.

---

### [103] Reinforcement Learning for LLM-based Event Forecasting

**链接**: https://arxiv.org/abs/2606.15917
**作者**: Amit Arnold Levy
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] Continual Learning Exam: Benchmarking Long-Horizon RSI and Experiential Learning in LLM Agents

**链接**: https://arxiv.org/abs/2610.33956
**作者**: Haoyu Zhao, Sitian Tu, Yuxuan Huang, Huichi Zhou, Zhangyue Yin, Jiahao Huang 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual learning is the ability of LLM agents to improve over time by acquiring, refining, and applying knowledge from experience while retaining useful prior knowledge. It is essential for agents learning over long time horizons, yet current evaluations largely assess individual task performance rather than improvement through accumulated experience. We introduce Continual Learning Exam (CLE), a large-scale benchmark developed by 50+ domain experts to measure experience-driven improvement in realistic professional workflows. CLE comprises 120 human-authored tasks, each organised as a five-level ladder, yielding 600 levels spanning 89 professional roles across 12 occupational domains. Agents must pass each level to unlock the next, with later levels building on experience accumulated during earlier assignments. An evaluation agent assesses each submission against human-authored rubrics. We compare a single-submission setting with one that provides diagnostic feedback after failure an

---

### [105] Ontology-Guided Multi - Model Semantic Arbitration for Agricultural Pest and Disease Knowledge Graph Construction

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11737146/&hl=zh-CN&sa=X&d=3178055004306803077&ei=SkzgavWpA8Pu6rQPsLyw0QY&scisig=ACTRDVFxNyxkT8dzDW96hoJOFsvf&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=4&folt=kw-top
**作者**: M Huo, J Huang - 2026 8th International Conference on Artificial …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , and single large language model (LLM) extraction strategies. This paper proposes an ontology-constrained multi - model collaborative … with voting-based consensus and judge model adjudication mechanisms introduced to reduce model -specific

---

### [106] Governing Enterprise AI Traffic at Scale: Design and Operation of a Policy-Driven, Multi-Vendor LLM Gateway on Envoy

**链接**: https://arxiv.org/abs/2610.35509
**作者**: Mithun Sasidharan, Srinivasan Manoharan, Rupesh Thakur, Abhinav TK, Ashwin Hegde, Anand Gautam
**来源**: cs.DC cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large organizations consume large language models (LLMs) from several vendors at once, each with its own API dialect, credential model, streaming protocol and pricing. Integrated directly, this heterogeneity yields credential sprawl, format lock-in, unbounded spend and inconsistent governance. We present the design and production operation of the Cosmos LLM Gateway, the governed entry point for enterprise LLM traffic at PayPal. Built on Envoy, it splits work by latency profile: I/O-bound control decisions (authentication, credential brokering, policy and budget evaluation) run in an out-of-process external-processing service, while wire-format translation, token metering and prompt-cache shaping run in-proxy as a Rust WebAssembly filter, so that, by default, streamed response body chunks never wait on an out-of-process call. Models, providers and prices are largely validated data rather than code. Governance is declarative policy evaluated by Open Policy Agent and managed through a con

---

### [107] Automated Standardization of Legacy Biomedical Metadata Using an Ontology-Constrained LLM Agent

**链接**: https://arxiv.org/abs/2604.08552
**作者**: Josef Hardi, Martin J. O'Connor, Marcos Martinez-Romero, Jean G. Rosario, Stephen A. Fisher and Mark A. Musen
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] AgentOrch: How Close Can Global Orchestration Come to Step-by-Step Interaction?

**链接**: https://arxiv.org/abs/2610.33375
**作者**: Zijie Liu, Qi Yang Huang, Jinhao Duan, Yueh Che Lee, Thomas A. Joseph, Zayne Turner 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise workflow agents typically rely on step-by-step interaction (Step-by-Step): the agent executes an action, observes its result, and invokes a large language model (LLM) again to decide the next step. Global orchestration (Global) instead generates a complete executable workflow in advance and executes it without further LLM calls, substantially reducing inference overhead, but it remains less accurate than Step-by-Step. We study how close Global can come to Step-by-Step and what narrows the remaining gap. We introduce AgentOrch, a benchmark that directly compares global orchestration with step-by-step interaction on 650 enterprise SOPs and 3,220 runtime variants under matched tools, environments, and evaluation. Step-by-Step remains more accurate for every evaluated model, but the gap has shrunk by about 79% from early models to the strongest recent model. We identify three routes to further narrowing this gap. Incremental workflow construction improves Global accuracy by an a

---

### [109] DiagnosticIQ: A Benchmark for LLM-Based Industrial Maintenance Action Recommendation from Symbolic Rules

**链接**: https://arxiv.org/abs/2605.08614
**作者**: Devin Yasith De Silva, Dhaval Patel, Christodoulos Constantinides, Shuxin Lin, Nianjun Zhou, Dharmashankar Subramanian 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] Before Blaming the LLM, Diagnose the Workflow: A Role-Level Difficulty Profile for Translating Natural Language into Ontology-Grounded Statements

**链接**: https://arxiv.org/abs/2610.35267
**作者**: Liang Zhang, Beno\^{i}t Daireaux, Sergey Alyaev
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language-to-domain-specific-language (NL-to-DSL) semantic parsing systems increasingly translate informal user descriptions into structured artifacts such as Structured Query Language (SQL) queries, Application Programming Interface (API) calls, workflows, formal specifications, and ontology-grounded domain-specific language (DSL) statements. This paper focuses on ontology-grounded Assertion Box (ABox) DSL generation: the translation of natural language domain descriptions into assertion-level DSL statements grounded in a pre-existing ontology vocabulary. In this setting, syntactic validity is often easier to achieve than semantic adequacy. Failures are frequently attributed to weak generator models, but recurring sources of difficulty are also structural: insufficient input, weak domain grounding, output template and vocabulary gaps, weak validation, and non-local repair. We propose a role-level difficulty profile for diagnosing difficulty in ontology-grounded NL-to-DSL semant

---

### [111] Quantifying Claim Smoothing by LLM Research Agents

**链接**: https://arxiv.org/abs/2610.35793
**作者**: Tiasa Singha Roy, Manya Wadhwa, Greg Durrett
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep research, or any use of large language models (LLMs) to read a large document collection and produce insights, requires synthesizing information from different sources. In this work, we find that LLMs produce long-form research reports that read as confident syntheses but which fail to accurately reflect the underlying documents. We call this failure smoothing. In collapsing diverse and potentially conflicting sources into a single narrative, the model discards the evidential "jaggedness" of its corpus and asserts conclusions more decisive than the citations can support. We introduce a claim level scoring pipeline, SmoothScore, to quantify this effect. Our pipeline extracts key conclusive claims from model generated reports, then finds evidence relevant to each claim and clusters that evidence along high level aspects. Finally, each claim is scored with respect to the evidence to quantify the degree of smoothing done by the agent. Across 7 systems and 4 datasets, we find that agen

---

### [112] Veil-Then-Reveal: Protecting PII Privacy via Reversible Pseudo-Anonymization in Zero-Trust User--LLM Interaction

**链接**: https://arxiv.org/abs/2610.22800
**作者**: Mohamed Elmahallawy, Mohamed Shaaban, and Thomas E. Carroll
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] LLM-Enhanced Heterogeneous Graph Learning with Business Semantics for Financial Fraud Detection

**链接**: https://arxiv.org/abs/2610.35298
**作者**: Yixuan Chen, Hongyu Zhan, Jie Sheng, Weiyu Han, Shuai Chen, Tianyi Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial fraud detection increasingly relies on heterogeneous transaction graphs, in which entities such as cards and merchants play distinct business roles and the risk meaning of an attribute depends on the entity's role: a high transaction volume may be routine for a merchant but unusual for a card. Heterogeneous graph neural networks preserve typed entities and relations but typically treat these attributes as role-agnostic inputs and leave their business meaning implicit. Meanwhile, most existing methods integrating large language models (LLMs) with graphs focus on homogeneous graphs or heterogeneous graphs with naturally available textual attributes, leaving their use on transaction graphs with structured attributes underexplored. To address this issue, we propose SemHGT, an LLM-enhanced framework that interprets structured attributes according to entity roles and makes the business semantics explicit in three stages: (1) role-aware prompts elicit risk-related business descripti

---

### [114] From Human Intent to In-Orbit Action: A Self-Learning Large Language Model Agent for 6G Satellite Networks

**链接**: https://arxiv.org/abs/2610.34387
**作者**: Zhengqian Xu, Yasheng Zhang, Chenhua Sun, Shan Lu, Chengcheng Li
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous control of sixth-generation (6G) low Earth orbit satellite networks is hindered by the gap between high-level human intent and low-level control logic: translating a request such as "uninterrupted Arctic video" into a valid reinforcement learning reward still takes days of manual trial and error, and existing large language model translators cannot learn from the failures of the policies they generate. This article presents ALMOND (Agentic Large-Model-Orchestrated autonomous Network Design), a cognitive framework that closes this intent-to-action loop under on-orbit compute constraints. The contribution in artificial intelligence is a bidirectional semantic engine that translates natural-language demands into multi-objective reward functions and, conversely, mines implicit operational constraints from failed reinforcement-learning trajectories through counterfactually validated forensics, together with a large language model-guided graph neuroevolution that seeds and critiqu

---

### [115] Old Ideas, Novel Problems: The Instability of LLM-Based Novelty Evaluation

**链接**: https://arxiv.org/abs/2610.02022
**作者**: Noy Sternlicht, Simra Shahid, Peter Jansen, Daniel S. Weld, Pao Siangliulue, Tom Hope
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] A Russian, a Brazilian, and a German Walk into a Bar, Ask the Same Question-- And Get Three Different Answers: Profiling LLM Perspective Diversity on Contested Topics

**链接**: https://arxiv.org/abs/2610.34278
**作者**: Wiem Ben Rim, Yao Lu, Pontus Stenetorp, Emine Yilmaz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models(LLMs) have shown strong performance on tasks with verifiable answers, but many real-world queries involve subjectivity, disagreement, and conflicting evidence. Most existing benchmarks for such queries remain English-centric, overlooking the vast diversity of perspectives held by users worldwide. To systematically study how LLM perspectives vary across languages, we curate PerspectivesQA, a manually verified multilingual dataset of globally contested topics covering 18 languages, and propose ROOTS, a framework that profiles linguistic, perspective, and framing diversity. We evaluate a diverse set of eight models covering both open-source and proprietary families at varying scales, establishing that LLMs hedge their answers in English but commit to positions in lower-resource languages. Larger models maintain a more consistent cross-lingual worldview, while smaller models are more easily swayed. All models also exhibit high sensitivity to minor surface-level input 

---

### [117] When Generated Information Returns: Error Persistence in LLM-Mediated Information Ecosystems

**链接**: https://arxiv.org/abs/2610.33617
**作者**: Yi Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly produce online articles from material that later becomes input to other models. This circulation connects individual responses to the information available for subsequent generation. We study a consequential distinction: an article can avoid endorsing a false claim while preserving the concrete details that enable its reproduction. Our framework connects claim content, expressed stance, and downstream reuse to explain selective error persistence under a continuing supply of accurate and inaccurate information. We implement a controlled community writing process that varies whether published articles return as inputs, matching external supply, input capacity, and generation volume. Across twelve factual targets and four production models, recirculation increases the presence of complete false claims by 7.29 percentage points at the final round while reducing explicit endorsement by 8.33 points. Effects differ across facts and models. Paired inte

---

### [118] ClinVerse: A Realistic Multi-Agent Diagnostic Environment for Training and Evaluating Medical Agents

**链接**: https://arxiv.org/abs/2610.34878
**作者**: Sirry Chen, Fangke Chen, Xuanwen Ding, Wei Chen, Zhongyu Wei
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disease diagnosis is a key application of large language model (LLM) agents in healthcare. However, existing medical agents are primarily trained and evaluated with static question-answering data, providing limited opportunities to learn active information acquisition, examination decision-making, and dynamic clinical interaction. To address this limitation, we present ClinVerse, an interactive, real-data-grounded multi-agent environment designed for training and evaluating medical diagnostic agents. Built on ClinPatient, a scalable dataset comprising 150k diagnostic cases derived from real-world electronic health records, ClinVerse supports coordinated interactions among six specialized clinical roles. Specifically, a doctor agent starts from an initial patient complaint, progressively gathers clinical evidence through patient interviews and examination requests, and ultimately produces a diagnosis. For each interaction trajectory, a rule-based scoring framework quantifies information

---

### [119] Exact Degeneracy Under Balanced k-Shot Sampling:Consequences for Small-Sample Discriminant Analysis on LLM Embeddings

**链接**: https://arxiv.org/abs/2609.09860
**作者**: Lingxiao Qu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] INVAR-Agri: Detecting Discrepancies in Multilingual Operator Manuals of Agricultural Implements with a Fine-Tuned LLM

**链接**: https://arxiv.org/abs/2610.35423
**作者**: Timo Oksanen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Operator manuals of agricultural implements are delivered in many languages, and the standards require that competent persons review every translation, which makes this review the bottleneck. This paper presents a proof of concept that compares two training workflows on the same LLM, EuroLLM-1.7B-Instruct, trained on operator manuals of one manufacturer. In approach A, a back-translator translates each language version back into English, and an English reader compares it with the English version. In approach B, a checker reads the English version and the translation together, where the checker reports differences. The test sets contain errors planted in numbers, units, opposite words, obligations, negations, and conditions in 24 languages, and they include unmodified text and meaning-preserving edits for alerts and false alarms. The trained back-translator concealed many planted errors, most of all weakened obligations, while translation-quality scores rose. In contrast, the separately

---

### [121] CTXAgent - Self-Controlled Context Management of LLM Agents

**链接**: https://arxiv.org/abs/2610.34425
**作者**: Matthias Busch, Marius Tacke, Roland C. Aydin, Christian Feiler, Christian J. Cyron
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent harnesses keep long sessions inside the context window by compacting the history when a token threshold is crossed. We study an alternative in which the model manages its own context: it decides when to compact, what to keep and what to write as the hand-off, given two tools and one paragraph of guidance. Since earlier work found that open-weight models cannot manage their own context without scaffolding, we compare seven frontier models under identical conditions, with and without the context tools, on token cost and benchmark score, and we compare our harness with three widely used harnesses on two of these models. The benchmark is assembled from existing ones: coding exercises, multi-step SciCode problems and SWE-bench Pro and Terminal-Bench 4.0 tasks are interleaved with planted facts, ephemeral observations and standing instructions, all checked deterministically, in sessions of 35-212 turns that resemble a user working through different tasks in one chat. Most of the strong

---

### [122] TROPE: Typed Representations and Operators for Problem Editing in LLM Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.773/&hl=zh-CN&sa=X&d=18199776223750626377&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv4HCHeQYTe4r1KK6ZQN-kWI&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=9&folt=kw-top
**作者**: V Bikbulatov, O Petrosian - Proceedings of the 2026 Conference on Empirical …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM behaviour, from stochastic decoding to tree search to evolutionary mutation of programs or prompts, all vary the output. The problem formulation stays fixed. We introduce TROPE, an inference-time framework that operates one level of

---

### [123] CoEvolve: Counterfactual-Guided Co-Evolution of Memory and Collaboration in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.33539
**作者**: Xufei Shi, Derong Xu, Wei Chen, Yanyu Yao, Zhi Zheng, Tong Xu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems have demonstrated remarkable capabilities across diverse tasks. Yet their memory and collaboration architectures often remain static, constraining continued adaptation and improvement over time. Recent work addresses this limitation by evolving memory or collaboration based on interaction experience. However, updates to these interdependent components are not necessarily aligned: an evolved workflow may require experience that memory does not provide, while evolved memory may encode guidance that the workflow cannot use. To address this problem, we propose CoEvolve, a skill-centered framework for aligned memory--collaboration evolution. CoEvolve represents reusable local collaboration patterns as skills that link evolving collaboration decisions to their supporting memories. It further compares original and counterfactual trajectories to identify local evolution signals, which coordinate updates to the skill library, skill memory, an

---

### [124] EF-LLM: A Continual Learning-Based Framework for AI-Assisted Automation, Enhanced Sparse Prediction, and Hallucination Detection

**链接**: https://arxiv.org/abs/2411.00852
**作者**: Zihang Qiu, Jayashri Ravishankar, Anam Malik, Zhongju Wang, Renyou Xie
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] High Scores, Hidden Failures: Evaluating Codebook-Based LLM Content Analysis

**链接**: https://arxiv.org/abs/2610.35179
**作者**: Elena Senger, Yuri Campbell, Rob van der Goot and Barbara Plank
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for codebook-based content analysis in computational social science, where codebooks translate theoretical concepts into labeling schemes. While prior work reports strong predictive performance, it remains unclear whether these systems produce reliable and robust text annotations. We conduct a large-scale empirical failure-mode analysis of LLM-based coding pipelines across four datasets and five models by systematically evaluating their stability, robustness, and conceptual validity under controlled perturbations, domain shifts, and optimization procedures. We uncover multiple failure modes that are largely invisible under standard metrics, showing that high aggregate scores frequently coexist with severe label-level disparities, instability across runs, domain sensitivity, and shifts in label interpretation. Importantly, these failure modes persist under widely used optimization strategies and remain largely invisible under standard m

---

### [126] UMAS: System-Level Uncertainty Quantification for Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.33013
**作者**: Hanwen Li, Jinhao Duan, Xiaoshuang Shi, Yue Zhang, Tianlong Chen, Kaidi Xu 等 (7 人)
**来源**: cs.MA cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-Agent Systems (MAS) are a promising paradigm for improving the reasoning capabilities of large language models, yet they remain prone to hallucinations and erroneous outputs. Uncertainty Quantification (UQ) is crucial for assessing system reliability, but existing methods are largely designed for single-agent settings; how to exploit MAS structure for UQ while keeping inference cost-neutral remains underexplored. We propose UMAS, a parameter-free, cost-neutral, system-level UQ framework that estimates the credibility of inter-agent influence from each generation's intrinsic confidence. UMAS uses these credibility signals to modulate how uncertainty is updated at each node, and then aggregates node-level uncertainty into a system-level estimate. Extensive evaluations on Debate and DyLAN across diverse benchmarks show that UMAS consistently outperforms state-of-the-art baselines by an average of 10.54 AUROC points. Beyond uncertainty estimation, UMAS enables hallucination detection

---

### [127] Leadership as Coordination Control: Behavioral Signatures and the Recovery-Advantage Boundary in Multi-Agent LLM Teams

**链接**: https://arxiv.org/abs/2606.19111
**作者**: Haewoon Kwak
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] ClawMMU: Protection-Coherent Virtual Memory for Stateful LLM Agents

**链接**: https://arxiv.org/abs/2610.28093
**作者**: Jinhao Hu, Bardia Mohammadi, Mofasshara Binte Rafique, Lars Henning Klein, Akhil Arora, Ashvin Goel 等 (7 人)
**来源**: cs.CR cs.AI cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] Style over Substance? Linguistic Bias in LLM-based Peer Review Copy title

**链接**: https://arxiv.org/abs/2610.35254
**作者**: Sai Suresh Macharla Vasu, Sumedh Santosh Joshi, Philipp Christmann, Ivaxi Sheth, Ruta Binkyte, Koel Dutta Chowdhury 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The number of paper submissions to major AI conferences has increased dramatically in recent years, substantially increasing the peer-review workload of researchers. At the same time, large language models (LLMs) are increasingly used to support peer review, both by individual reviewers and by conference organizations. While LLM capabilities have improved considerably, their evaluations may be influenced by linguistic characteristics that are unrelated to scientific content. In this work, we introduce a controlled experimental framework for studying such effects by systematically perturbing the linguistic style of research papers. Specifically, we rewrite papers to exhibit (i) linguistic features associated with native or non-native English writing, and (ii) high- or low-confidence linguistic features. To construct these interventions, we derive fine-grained rewriting instructions grounded in the linguistic literature and apply them using LLMs. Crucially, our interventions are designed

---

### [130] Same Signal, Opposite Meaning: Direction-Informed Adaptive Learning for LLM Agents

**链接**: https://arxiv.org/abs/2605.06908
**作者**: Ziming Li, Jiatan Huang, Xiaoguang Guo, Guiling Wang, Chuxu Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Not Every Agent Needs the Strongest Model: Unified Prompt-Model Optimization for Heterogeneous LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.31743
**作者**: Mingxiu Cai, Haoyang Xian, Xinyu Ma, Yutong Wang, Zhenxi Song, Jing Li 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] Prompt PerturbAItions: Mechanisms of LLM Response Inconsistencies

**链接**: https://arxiv.org/abs/2605.30913
**作者**: Soorya Ram Shimgekar, Agam Goyal, Amruta Parulekar, Joshua Chen, Yian Wang, Navin Kumar 等 (9 人)
**来源**: cs.CL cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] STEP: Soft Trajectory Estimation of Prediction Correctness via Per-Step Probability Scoring

**链接**: https://arxiv.org/abs/2610.34537
**作者**: Chenyang Yu, Zifan Zeng, Qunli Zhang, Feng Liu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Estimating the correctness of large language model (LLM) predictions without access to ground truth is critical for reliable deployment in high-stakes settings. Existing approaches, such as entropy and perplexity, operate solely on final output statistics, discarding the rich information encoded in intermediate reasoning steps. To address this limitation, we propose STEP (Soft Trajectory Estimation of Prediction correctness), a training-free framework that scores each reasoning step via lightweight forward passes to obtain a soft probability distribution qi over candidate answers, from which we derive a set of soft trajectory features capturing per-step confidence and its progression toward the final answer. Extensive experiments on various benchmarks demonstrate consistent and substantial improvements, particularly in AUROC, over output-based baselines and hard-indicator trajectory methods. Notably, Temporally-Weighted Consistency, which assigns higher importance to later reasoning st

---

### [134] DIGEST: Discovery-Guided LLM Tuning for Symbolic Regression

**链接**: https://arxiv.org/abs/2610.33880
**作者**: Kaifeng Jin, Ruizhong Qiu, Zihao Li, Xiao Lin, Dongqi Fu, Yinglong Xia 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic regression (SR) seeks to discover mathematical expressions directly from data, without requiring task-specific scientific descriptions. Despite tremendous progress in both conventional search-based methods and recent LLM-based methods, two critical limitations largely remain. First (Limited Generation Flexibility), conventional search-based methods rely on either fixed search rules or specialized learned generators, severely limiting adaptive candidate generation across diverse expression structures. Second (Underutilized Search Discoveries), most LLM-based methods cannot reliably recover ground-truth expressions because they fall short in effectively leveraging the LLM itself to thoroughly digest past expressions or adaptively guide future search. To address these limitations, we propose DIGEST. To render greater flexibility in generation, DIGEST repurposes a pretrained decoder block from a lightweight LLM into a symbolic policy for Genetic Programming (GP) population seeding

---

### [135] Exploring the impact of document context on LLM -based machine translation evaluation

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1839.pdf&hl=zh-CN&sa=X&d=14710721373432895949&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv4qK3-MCu3oxWVhhypLNpjD&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=5&folt=kw-top
**作者**: MI Aur, S Perrella, R Navigli - Findings of the Association for Computational …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This work investigates the effects of incorporating document context into LLM -based MT evaluation and its interaction with reference translations. Specifically, we benchmark LLMs with and without thinking-enabled inference in the MT error

---

### [136] On the Robustness of Code LLM Guardrails to Code-mixed and Transliterated Inputs

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.568/&hl=zh-CN&sa=X&d=15353059889836701491&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv7Gh3a-zEVbSKMA0SXa-jho&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=7&folt=kw-top
**作者**: N Raihan, D Meher, B Dhingra, M Zampieri - Findings of the Association for …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Safety guardrails in Code Large Language Models (Code LLMs) are designed to prevent the generation of malicious code, yet their robustness under linguistically diverse inputs remains largely unexplored. To address this important safety issue

---

### [137] Difference-in-Differences on a Censored Rating Scale Can Manufacture an Effect: Evidence from a Pre-Registered LLM-Judge Audit

**链接**: https://arxiv.org/abs/2608.27309
**作者**: Shuyi Fan, Boyuan Deng, Mengyu Xu, Xinhong Xie, Chenyang Li, Hongyang Zhang
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [138] Reason or Recite: Complementary Specialists with an LLM Judge for Traffic Anomaly Reasoning

**链接**: https://arxiv.org/abs/2610.34993
**作者**: Mayur Kulkarni
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Road anomalies such as collisions, violations, and sudden hazards demand more from video understanding than detection: a practical system must verify what happened, describe the scene, and explain the cause. We find these competences pull in opposite directions for vision-language models: closed-form questions reward precise, evidence-grounded reasoning, while open-ended answers are scored by similarity to reference text, where matching the annotation style matters as much as reasoning correctly. We present Reason-or-Recite (RoR), a two-specialist framework for the Traffic Anomaly Reasoning track of the 2026 AI City Challenge. RoR (1) rewrites the official chain-of-thought annotations into a structured, temporally grounded schema and LoRA-tunes a 9B vision-language model on the enhanced traces; (2) fine-tunes a 4-bit-quantized 27B model on answers alone, absorbing the annotation style; and (3) selects between the two candidates per question with a training-free LLM judge. RoR ranks fir

---

### [139] How Does Post-Training Shape LLM Value Preferences?

**链接**: https://arxiv.org/abs/2610.33371
**作者**: Yang Liu, Shaoyang Xu, Masahiro Kaneko, Chengzhi Zhong, Wenxuan Zhang, Chenhui Chu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> During post-training, large language models (LLMs) learn value preferences from corpora that may contain imbalanced proportions of opinions associated with different demographic groups. Amplifying these imbalances may further underrepresent some groups' opinions. However, how opinion mixtures shape value preferences across post-training paths remains unclear. To answer this question, we conduct controlled experiments using post-training corpora with different opinion mixtures and five post-training paths based on SFT, DPO, and GRPO. We find that post-training amplifies opinion imbalances differently across post-training paths. Once value preferences are amplified, whether further post-training can remove them depends on both the post-training method and the opinion mixture in the corpus. More concerningly, a model's stability under interventions depends on whether further post-training changes its value preference. Moreover, these value preferences are transferred to student models eve

---

### [140] Evaluating LLM-based Agents for Multi-Turn Conversations: A Survey

**链接**: https://arxiv.org/abs/2503.22458
**作者**: Shengyue Guan, Jindong Wang, Jiang Bian, Bin Zhu, Jian-guang Lou, Haoyi Xiong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] Multiscale Policy Optimization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2610.35013
**作者**: Tao Ren, Hui Yang, Jia Deng, Tingyang Chen, Qiyao Wang, Shuo Tang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents interact with their environments through complete assistant turns while generating each action token by token. We observe that critic values vary primarily across turns, motivating optimization anchored at turns with finer credit allocation among tokens. We propose Multiscale Policy Optimization (MPO), combining Multiscale Advantage Estimation (MAE) and turn-level importance sampling to align credit assignment and policy updates at the turn scale. Extensive experiments across search, tool-use, and automation tasks with 4B and 30B-A3B models demonstrate consistent gains over strong RL baselines.

---

### [142] Amplitude-Only FFN Intervention for Tool-Structured LLM Inference: Method, Gated Evaluation Protocol, and Cross-Model Empirical Results

**链接**: https://arxiv.org/abs/2607.11183
**作者**: Sheng Xu, Zhen Chen, Junhua Wang, Boyuan Huang, Ke Jia, Jiadun Zhu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [143] Lessons from Luck: Do LLM-Written Lessons Carry Chance into an Agent's Next Decision?

**链接**: https://arxiv.org/abs/2610.33029
**作者**: Kazuki Nakayashiki
**来源**: cs.LG cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving agents write lessons from the outcomes of their runs; when outcomes are noisy, a lesson can carry chance into later decisions. We measure one link of this chain in a registered study. In 256 synthetic worlds, each a recurring task with two interchangeable tools of recorded reliability, a scripted previous run used the more reliable tool (a good decision) or the less reliable one (a bad decision), with an assigned outcome: success or a transient failure. A model wrote a lesson from the run with ReasoningBank's memory-writing instruction; a fresh session of the same model, holding the authoritative log and the previous result, chose the next run's first tool with one memory item: that lesson, the lesson from the other outcome, an irrelevant item, or an unreasoned directive. The protocol was frozen, deposited and timestamped before any confirmatory call; 11 LLM endpoints gave 90,084 answers. After a chance failure of the better tool, the panel's lessons carried the chance (

---

### [144] How To Build A Modern Diffusion Language Model

**链接**: https://arxiv.org/abs/2610.33391
**作者**: Volodymyr Kuleshov, Marianne Arriola, Yair Schiff, Gilad Turok, Guanghan Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The frontier of large language model (LLM) performance has advanced rapidly in recent years, fueled by scaling laws for pretraining on large text corpora. However, mainstream LLMs have fundamental limitations: they generate text autoregressively, producing outputs sequentially from left to right one token at a time. This sequential process leaves parallel GPU hardware underutilized during inference--a bottleneck that has grown acute as progress shifts toward scaling post-training and inference-time compute--and commits irreversibly to each token without the ability to revise earlier mistakes. Discrete diffusion models address these limitations by generating tokens in parallel, starting from a noisy or masked sequence and iteratively refining the entire output over a series of denoising steps. This parallel generative process enables speeds of thousands of tokens per second, provides a new axis of inference-time compute scaling, and supports built-in error correction and controllable ge

---

### [145] CoSA: The Conflict of Skills Attack in Real-World LLM Agent Ecosystems

**链接**: https://arxiv.org/abs/2610.35082
**作者**: Yujia Zheng, Tianhao Li, Shangzhi Xu, Yuekai Huang, Ziyou Jiang, Zhaoyang Li 等 (9 人)
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent Skills allow LLM agents to combine reusable capabilities, but checking each Skill in isolation cannot rule out policy violations when they are composed. We term such failures Conflict of Skills (CoS): artifacts or assessment signals produced for one purpose may be reused downstream without preserving the restrictions or authorization needed for their new use. Using controlled executions of publicly available Skills and matched single-Skill controls, we identify four recurring mechanisms behind CoS. Building on these findings, we introduce the Conflict of Skills Attack (CoSA), which adds locally admitted Skills to an existing pool to supply missing business operations (capability supplementation) or reshape artifact exchange, decision reuse, and target/action bindings (relationship reshaping). CoSA leaves existing Skills and runtime permissions unchanged. To evaluate this threat under autonomous Skill selection, we introduce CoSA-Bench, built from real-world Skills and controlled 

---

### [146] Large Language Model probabilities cannot reliably distinguish between possible and impossible language

**链接**: https://arxiv.org/abs/2509.15114
**作者**: Evelina Leivada, Raquel Montero, Paolo Morosi, Natalia Moskvina, Tamara Serrano, Nikoleta Pantelidou 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [147] Accelerating LLM Pre-Training through Flat-Direction Dynamics Enhancement

**链接**: https://arxiv.org/abs/2602.22681
**作者**: Shuchen Zhu, Rizhen Hu, Mingze Wang, Mou Sun, Xue Wang, Kun Yuan 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] Evaluating Harmful Memorization in LLM Code Generation

**链接**: https://arxiv.org/abs/2503.02296
**作者**: Lizhe Zhang, Wentao Chen, Li Zhong, Letian Peng, Zilong Wang, Jingbo Shang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] Trading Agents or Market Crashers? Dissecting Robustness and Security Failures in Academic Financial LLM Trading Schemes

**链接**: https://arxiv.org/abs/2609.19705
**作者**: Mengxiao Wang and Nitesh Saxena
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [150] The LLENS Platform for On-Premises Large Language Model Agents in a Japanese University Hospital: Development and Evaluation Study

**链接**: https://arxiv.org/abs/2610.32151
**作者**: Ken Enda, Jien Saito, Masami Mukai, Feng Han, Emir Turkes, Tatsumi Kusakabe 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [151] Dispatch Overhead, Not Kernel Quality: The Performance Bottleneck in Single-Stream WebGPU LLM Inference

**链接**: https://arxiv.org/abs/2608.08730
**作者**: J\k{e}drzej Maczan
**来源**: cs.LG cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [152] COSE: Confidence-Orchestrated Self-Evolution for Effective LLM Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.2074.pdf&hl=zh-CN&sa=X&d=15201055570118861166&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv6FFodGyMB52kE-jKIOX4-y&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=4&folt=kw-top
**作者**: B Wei, N Wang, Y Zhou, J Pan, Z Zhu - Proceedings of the 2026 Conference on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We propose COSE (Confidence-Orchestrated Self-Evolution), which uses the LLM ’s … LLM -generated feedback as a central optimization bottleneck in selfevolving LLMs, covering both validation of generated tasks and judgment of generated answers. •

---

### [153] AOS-Bench: Can LLM Agents Manage Dynamic Workloads?

**链接**: https://arxiv.org/abs/2610.33178
**作者**: Erle Zhu, Genrui Zhang, Keyang Hu, Mingyu Su, Hongning Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents are moving from handling one request at a time to serving as persistent assistants to which users hand a stream of work: a build, a data-processing job and a bug fix may all be pending on the same machine at once. Such an agent must decide when to take on new tasks, how to delegate and overlap them, and how to stay within the machine's CPU and memory. Existing benchmarks cannot measure this, because they evaluate each task in isolation. We introduce \benchname{}, which evaluates an agent system as a workload manager: verified tasks arrive over time and must be delivered under shared CPU and memory limits, and the same tasks run one at a time serve as a per-system reference. Across five model--harness pairs, isolated task success does not carry over evenly. On heavy workloads every system loses 13 to 23 points. On medium workloads, systems span 11 points in isolated success but 26 points in stream success, and two systems 0.6 points apart in isolation deliver 54\% and 68\%

---

### [154] ECHOES: An Adaptive LLM-Powered AR Glasses Docent for Evidence-Grounded Urban Heritage Interpretation

**链接**: https://arxiv.org/abs/2610.34865
**作者**: Bang Xiao, Baosheng Jin, Jinhan Niu, Xingchen Zhang, Hua Shen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Urban heritage tours are often delivered through fixed scripts, leaving limited room for visitors' situated questions, language preferences, or requests for evidence. We present ECHOES, an adaptive LLM-powered AR glasses docent for evidence-grounded interpretation of historical buildings. Specifically, the agent adapts along three dimensions: it modifies response structure according to the type of visitor question (identification, architectural detail, evidence-seeking, or route inquiry); it accumulates session-level interest signals from repeated questions and expressed curiosity to shape later explanations; and it tracks language preference and retrieval context across turns to maintain conversational continuity. The core of ECHOES is an LLM agent initialized as a source-aware urban heritage docent that realizes this adaptation through dialogue and preference context maintained across the session. Around this agent, ECHOES integrates visual site grounding, a self-built historical kno

---

### [155] Beyond Belief: Evaluating and Mitigating LLM Susceptibility to Misinformation

**链接**: https://arxiv.org/abs/2610.33962
**作者**: Emran Kanaan, Jiho Lee, Ibrahim Odat, Soroush Vosoughi, Weicheng Ma
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language models (LLMs) must decide whether external information warrants action. We investigate whether their expressed credibility judgments reliably indicate behavioral resistance to misinformation. We evaluate five LLMs on 196 constructed false notices paired with legitimate counterparts and 204 archived attacks adapted to simulated tool use. When asked to act on the constructed notices, models issue harmful tool calls in 27%--99% of cases they have rated untrustworthy. Removing the preliminary rating step increases harmful execution by 15 percentage points on average, showing that credibility elicitation itself changes the behavior being evaluated. Interventions that improve credibility discrimination do not consistently yield safer actions. A simple forewarning significantly reduces harmful execution in four of five models, but neither tested generated-example prebunk outperforms it in the main evaluation. These reductions can also compromise legitimate task compl

---

### [156] An Agentic AI Workflow for Liver Lesion Segmentation and Structured Radiology Reporting

**链接**: https://arxiv.org/abs/2610.34599
**作者**: Fatma Ahmed Mansour, Rahatara Ferdousi, Manar Fathy Elshenawy
**来源**: cs.CV cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite advances in automated liver lesion segmentation, a gap remains between image-derived predictions and clinically interpretable radiology reports. Bridging this gap requires quantitative measurements that are both reproducible and traceable. We present an evidence-grounded agentic AI framework that connects liver and lesion segmentation with deterministic quantification and structured reporting. TotalSegmentator-based nnU-Net models delineate the liver, Couinaud segments, and lesions, while computational tools extract volumes, dimensions, counts, and anatomical locations. A large language model (LLM) organizes these measurements into a predefined reporting schema, with numerical consistency checks against source measurements. On 51 LiTS cases, the segmentation stage achieved a liver Dice score of 0.947, lesion sensitivity of 75.6%, and positive predictive value of 68.9%. Exploratory screening of 25,494 MERLIN reports identified 10,208 (40.0%) with liver-related abnormalities. By 

---

### [157] Beyond Prompts: A Systematic Study of LLM -Based Machine Translation Evaluators

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.2404.pdf&hl=zh-CN&sa=X&d=13282494254761876019&ei=SUzgatqrNoOnieoP05LQQA&scisig=AIL1Nv7zI7z8-OFnKBbr8KPxgTAc&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=6&folt=kw-top
**作者**: D Popov, R Bokhyan, E Enikeeva, A Mekhraliev… - Findings of the Association …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This leaves a central question largely unexplored: which evaluator design choices robustly improve LLM -based MT evaluation quality across datasets, protocols, and annotator settings? In this work, we study LLM -based MT evaluation

---

### [158] PatentAgentBench: Benchmarking LLM Agents with Professional Patent Task Suites

**链接**: https://arxiv.org/abs/2610.35031
**作者**: Yijie Hu, Wei Li, Junjie Zhou, Zhiqi Jiang, Yi Jin, Licong Xu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patent practice lies at the intersection of technical, legal, and linguistic work, making it challenging yet crucial to technological innovation. Recently, rapid advances in large language models (LLMs) and agentic systems have demonstrated the potential to complete realistic business workflows and even patent works. This raises a question: can current AI systems perform patent work reliably? Existing benchmarks cover a limited range of patent tasks and simplify evidence acquisition by providing reference materials or candidate documents. In this paper, we introduce PatentAgentBench, a benchmark comprising 510 instances across eight task suites: novelty search, freedom-to-operate (FTO) search, design FTO, invalidity search, claim charting, patent drafting, office-action response, and patent translation. Curated from real patent records and professional materials, the benchmark combines task-specific metrics with expert-reviewed annotations and rubrics. Retrieval tasks such novelty sear

---

### [159] Authoring for Living Worlds: Tool-Constrained LLM Agents for Executable Multi-Actor Scenarios

**链接**: https://arxiv.org/abs/2604.10383
**作者**: Nicolae Cudlenco, Mihai Masala, Marius Leordeanu
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] Gender Associations in LLM-Mediated ADHD Self-Diagnosis

**链接**: https://arxiv.org/abs/2610.33697
**作者**: Matilde Elene Hansen, Ross Deans Kristensen-McLachlan
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used for medical self-diagnosis. However, the way demographic cues shape outputs in these interactions remains poorly understood. This is particularly consequential for diagnoses like ADHD, where persistent gender disparities are not fully aligned with the clinical evidence. We adapt the Context Association Test (CAT) to evaluate whether GPT-4o responds to gendered ADHD associations in a zero-shot, self-diagnostic setting. We show that explicit cueing consistently amplifies certain ADHD subtype associations while implicit cueing produces near proxy-aligned distributions. These divergences suggest that explicit demographic cues may activate bias-mitigation mechanisms that over-correct rather than eliminate bias, whereas implicit cues appear to reflect the model's default behavior. Our results demonstrate that evaluating gendered bias in LLM-mediated self-diagnosis requires careful attention to the demographic associations a model encodes.

---

### [161] Democratizing LLM Training with the Edge: Challenges, Systems, and the Road Ahead

**链接**: https://arxiv.org/abs/2610.32215
**作者**: Ziyue Luo, Jiaxuan Cai, Cedric LeDenmat, Srijith Nair, Fatemeh Nourzad, Rohith Krishnan 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] When Can You Trust Your Synthetic Users? Diagnostics and Corrections for LLM Consumer Panels

**链接**: https://arxiv.org/abs/2609.13148
**作者**: Robson Tigre and Hugo Gobato Souto
**来源**: cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [163] From Self-Confidence to Statistical Accuracy: Scaling Human-in-the-Loop Evaluation with Direct and LLM-Assisted Auditing

**链接**: https://arxiv.org/abs/2610.35698
**作者**: Harine Choi (1), Chenchen Kuai (2), Zihao Li (3), Jiwan Jiang (2), Yunlong Zhang (2), Zhiwen Fan (4) 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For large language models (LLMs) and multimodal large language models (MLLMs), model-reported self-confidence is often miscalibrated, yet it may still be useful for efficient evaluation. At the same time, LLM-as-a-judge offers a scalable alternative to direct human auditing, but its practical benefit depends on calibration quality and inference cost. This paper develops a unified statistical framework for both evaluation routes under alternative sampling strategies. For direct auditing, confidence-stratified sampling is used to recover population accuracy from partially verified outputs without requiring calibrated confidence. Finite-sample uncertainty is characterized, and the analysis shows how highly uneven confidence strata affect audit efficiency and label allocation. For judge-assisted evaluation, the judge is modeled through sensitivity and false-positive rate, yielding an error-corrected estimator with calibration uncertainty. The two routes are then compared through human-labe

---

### [164] Semantic Needles in Document Haystacks: Sensitivity Testing of LLM-as-a-Judge Similarity Scoring

**链接**: https://arxiv.org/abs/2604.18835
**作者**: Sinan G. Aksoy, Alexandra A. Sabrio, Erik VonKaenel, Lee Burke
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] MultiEvoSkill: Structure-Aware Multi-Agent Skill Evolution for Generalizable Skill Artifacts

**链接**: https://arxiv.org/abs/2610.34260
**作者**: Kounianhua Du, Jianxing Liu, Ruoshui Shan, Yucheng Zhang, Ke Li, Xing Sun 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skill documents are becoming the default adaptation surface for frozen large language model (LLM) agents, but current skill generators face two key limitations. First, humans and different LLMs differ in how they organize procedural knowledge and approach task solving. Skills authored from a human or single-model perspective may therefore fail to align with the reasoning behaviors of other backbones, limiting cross-model generalization. Second, sequential skill descriptions inadequately represent procedures with parallel branches and explicit dependencies, while existing skill optimizers primarily operate on prose and lack explicit support for graph-structured skill evolution. We introduce MultiEvoSkill, a skill-optimization framework comprising three core components: 1) Skill compiler casts the skill as a typed graph with tailored operators, producing a compact, informative representation with explicit procedural topology; 2) Heterogeneous agent system proposes revision advices using 

---

### [166] Adaptive Transfer of Representational Signatures for LLM Reliability Detection

**链接**: https://arxiv.org/abs/2610.33442
**作者**: Yongtong Li, Yixuan Florence Wu, Jiawei Zhang, Naichen Shi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are reported to be susceptible to reliability issues including hallucinations and reasoning errors. Existing quality detectors can predict unreliable outputs based on internal representations with decent accuracies. However, training these detectors often requires substantial domain-specific labeled data, which limits their applicability to new domains. We propose to address this challenge by transferring representational signatures across related domains. More specifically, we build a statistical framework that first extracts low-dimensional signatures for each domain, then uses cross-fitting to learn composition weights of domain-specific predictors. The weights adapt to each source domain's predictive relevance to the target domain. Our asymptotic analysis of a least-squares analogue characterizes the limiting prediction risk and aggregation weights in terms of domain discrepancies and representation bias. Experiments across multiple hallucination datase

---

### [167] Strong yet Controllable LLM Abstention without Learning to Abstain

**链接**: https://arxiv.org/abs/2610.16318
**作者**: Junwei Zhang and Yifei Wang and Wanli Yang and Hexiang Tan and Rui Tang and Xin Chen and Jingang Wang and Du Su and Fei Sun
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Thinking-in-Bets at Test Time Reduces Sycophantic Revisions in LLM Agents

**链接**: https://arxiv.org/abs/2610.34654
**作者**: Nghi D. Q. Bui
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model agents often abandon correct work when a user challenges it, yet simply telling them to stand firm makes them ignore real mistakes. Once an agent reads a complaint, it tends to discount its own earlier checks in order to agree with the user. We introduce Thinking-in-Bets, a training-free method in which an agent writes a short private record of its main claims, the checks supporting them, and its confidence before reading user feedback. When challenged, the agent consults this Claim Checklist to keep verified work intact while investigating uncertain or newly challenged parts. We evaluate five Gemini models (3.5 Flash-Lite, 3.5 Flash, 3.6 Flash, 3.8 Flash, and 4.0 Argon) across eight benchmarks: SWE-Together, SWE-Interact, and DeepSWE for software engineering, Agents' Last Exam for professional reports, Humanity's Last Exam and SycEval for academic reasoning, Vals Finance for financial analysis, and Terminal-Bench for command-line tasks. Recording claims before criticism

---

### [169] Evaluate the Stack, Not the Layer: Do Deterministic and LLM Gates for Agent Actions Fail Independently?

**链接**: https://arxiv.org/abs/2610.07359
**作者**: Chenglin Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [170] A Large-Scale Benchmark and Risk Assessment of Traffic Analysis Attacks on Cloud LLM Services

**链接**: https://arxiv.org/abs/2609.31877
**作者**: Shahrooz Pouryousef, Jesus Lopez, Saeefa Rubaiyet Nowmi, Md Mahmuduzzaman Kamol, Moinul Hossain, Muoi Tran 等 (7 人)
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning

**链接**: https://arxiv.org/abs/2606.24064
**作者**: Tianyuan Shi, Canbin Huang, Bei Li, Xin Chen, Xiaojun Quan, Jingang Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [172] Text Is the Bottleneck: A Small-Scale Replication of LLM Game Playing in Riichi Mahjong

**链接**: https://arxiv.org/abs/2610.34791
**作者**: Mingge Xu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [173] All-in-One: A Composable Attack on LLM Transformations

**链接**: https://arxiv.org/abs/2610.33298
**作者**: Xiaohua Zhan, Kazuki Egashira, Robin Staab, Mark Vero, Martin Vechev
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization, pruning, and model merging are popular transformations applied to deployment-ready LLMs to improve efficiency and downstream performance. Recent work has shown that these transformations can introduce a security threat: an adversary can train a model that passes safety checks in its pre-transformed state, only turning malicious once it is transformed for deployment. However, prior attacks target one specific transformation (e.g., quantization) and generally rely on transformation-specific techniques, making them difficult to combine in practice. In this work, we introduce a simple, composable attack framework that targets multiple transformations simultaneously and triggers when any one of them is applied by a user. Our key insight is that the effect of each transformation can be approximated as a perturbation to the model weights, allowing us to jointly train the model with a benign loss on the original model and a malicious loss on each simulated transformed model. Thes

---

### [174] EdgeDeID: A 0.6B Clinical De-identifier Trained Without Real Patient Data

**链接**: https://arxiv.org/abs/2610.33839
**作者**: Sina Daneshgar, Raya Namazi, Amirali Khosravi, Pouria Rouzrokh, Bardia Khosravi
**来源**: cs.CL cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> De-identifying clinical notes with a hosted language model discloses the information the step is meant to protect. We present EdgeDeID, a 0.6B-parameter decoder-only de-identifier that runs locally and is trained without real patient text: three LLM teachers write synthetic notes, a single labeler re-annotates them into one convention, and the model learns to emit a typed XML schema of the identifiers it finds. On a 100-note synthetic in-domain benchmark with manually verified annotations it reaches 0.994 micro-F1 and leaves no missed identifier in 99% of notes, against 0.857 and 12% for the strongest of eight off-the-shelf systems. Quantized, it runs on CPU in 615 MB. Of three additions to supervised training, only a verifier adapter helps: it separates complete from incomplete outputs of other systems at 0.94 AUROC, whereas reinforcement learning with a recall-weighted reward and a rule-based post-processing layer leave in-domain results unchanged. On MIMIC ICU nursing notes F1 falls

---

### [175] Words Are the Voice of the Mind: Depression Severity Estimation from Social Traces via Mental-Guided Evidence Reasoning

**链接**: https://arxiv.org/abs/2610.33586
**作者**: Nada Xu, Xueqin Chen, Qiang Gao, Hongru Liang, Wenqiang Lei
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depression severity estimation is crucial for mental health assessment and intervention, yet traditional approaches depend on clinical interviews or self-report questionnaires that require users' active participation. With the widespread use of online social media, users leave rich social traces that may reflect their mental states, motivating the task of social media-based depression severity estimation. Existing efforts have progressed from textual-feature-based classification to LLM-based questionnaire completion over standardized scale items, yet they still fall short in user-specific mental priors modeling, diversified semantic retrieval, and fine-grained reasoning over mental evidence. To address these limitations, we propose UMer, a user-specific mental evidence reasoning framework for social traces-based depression severity estimation. UMer first distills a user-specific mental prior from historical social traces to capture the user's psychological tendencies, behavioral patter

---

### [176] StateWise: Teaching Language Models to Track and Obey Evolving Constraints in Multi-Turn Dialogue

**链接**: https://arxiv.org/abs/2610.33766
**作者**: Samarth Varshney, Ritu Yadav
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users of conversational assistants rarely state all requirements up front: they add constraints, amend them, withdraw them, digress, and return. Instruction-tuned LLMs fail here in two ways: active constraints stop being honored as turns accumulate (persistence failure), and withdrawn constraints keep being enacted (relapse). The only existing repair we know of is an external ledger that re-injects a compiled specification every turn. We propose StateWise, a self-improving approach that teaches a single LLM to maintain its own revisable constraint state, a typed state with tombstones for revoked constraints, so persistence and relapse are measured by executable checkers and ground-truth states are compiled for free. StateWise fine-tunes the LLM on two complementary skills, summarizing a dialogue into its constraint state and responding conditioned on that state, then self-trains on its own trajectories, keeping only turns that pass an exact round-trip check against the compiled state. 

---

### [177] Knowing When to Escalate: Disagreement Patterns for Uncertainty-Aware Content Moderation

**链接**: https://arxiv.org/abs/2610.35335
**作者**: Micha{\l} Wawer and Jaros{\l}aw A. Chudziak
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic content-moderation systems increasingly rely on collective judgments from LLM agents, while aggregation methods commonly treat inter-agent disagreement as a reliability problem to be removed through consensus or voting. This framing is inappropriate for value-laden tasks, where disagreement may reflect irreducible value pluralism - a distinction standard uncertainty decompositions cannot recover, since they operate on output distributions and discard the reasoning behind each judgment. We propose Reasoning Trace Divergence Analysis (RTDA), which embeds model-generated justifications from perspective-differentiated agents and classifies each case by justification similarity and conclusion agreement. The resulting four-state taxonomy isolates convergent disagreement, where agents reasoning similarly but concluding differently, as a candidate signature of value-laden conflict. On 1,000 items from the Measuring Hate Speech corpus, this structural signal predicts human annotator dis

---

### [178] The Price of Scale in Proactive Memory Recall

**链接**: https://arxiv.org/abs/2610.34507
**作者**: Yichuan Chen, Xin Wang
**来源**: cs.CL cs.AI cs.IR stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A long-lived assistant that brings up memories without being asked must decide at every turn whether anything in its store is worth an interruption. We show that this decision is a multiple-testing problem whose difficulty grows with the store size $N$. On streaming replays of LongMemEval and LoCoMo, a similarity threshold tuned to 5% false alarms at $N=8$ reaches 87-100% at $N=2048$, across embedding models and for explicit and implicit cues; LLM judges show the same growth from a lower base. We prove that a gate with false-alarm rate $\alpha$ operates at a per-item false-positive rate of about $-\ln(1-\alpha)/N$, which pins its hit rate to the far left of the single-comparison ROC curve and, under regular variation, makes it decay as a power of $N$ with an explicit constant. The resulting prediction matches the hit rate of a per-$N$ oracle threshold to within one percentage point. The analysis explains why lexical and semantic channels need thresholds growing like $\ln N$ and $\sqrt{

---

### [179] Entity Matching using Decision Models

**链接**: https://arxiv.org/abs/2610.34626
**作者**: Aaron Steiner, Ralph Peeters, Christian Bizer
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Entity matching is the task of deciding whether two records describe the same real-world entity. Current entity matching methods rely on pre-trained language models (PLMs) which require task specific fine-tuning or generative large language models (LLMs) which do not require task-specific fine-tuning but are slow and expensive at matching large record sets. Decision models are a new class of LLM-based models that return a probability for each predefined answer option rather than generate text. This paper investigates decision models as an alternative to generative LLMs and fine-tuned PLMs for entity matching. We evaluate six decision models in a zero-shot setting across eight benchmarks and compare their performance with that of the generative LLM GPT-6 Luna and the PLM-based matcher Ditto. Our experiments show that, without task-specific training data, the four strongest decision models achieve mean F1 scores close to that of GPT-6 Luna, with the best model slightly surpassing it. Thi

---

### [180] CodeMeepo: A Multi-Agent Workflow for Repository-Level Code Migration and Optimization

**链接**: https://arxiv.org/abs/2610.34633
**作者**: Farzad Habibi, Changrong Wu, Jinzhou Jiang, Guohan Lu
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repository-level code migration rewrites an entire project in a new programming language while preserving its observable behavior. It is challenging because behavior spans interdependent modules, dependencies and build infrastructure must be adapted to the target ecosystem, and the source code is often the only specification. Large language model agents can now attempt these migrations end to end, but three challenges remain. First, an agent that writes both the translation and its acceptance tests may overlook the same requirements in both, leaving missing or incorrect behavior undetected. Second, large repositories can exceed a model's context window, and dividing the work into smaller tasks does not ensure that all required behavior is migrated. Third, even behaviorally correct translations may be slower than the original implementation. We present CodeMeepo, a multi-agent pipeline for complete and efficient migration of large repositories. Each milestone is evaluated against a fixe

---

### [181] DiffAuction: An Auction-Driven Framework for Generative Image Advertising

**链接**: https://arxiv.org/abs/2610.34917
**作者**: Yijie Su, Ruiyang Si, Tonghan Wang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion models enable multiple advertisers to compete for exposure within a shared generated image. Yet existing approaches are computationally costly when generating images under varying target-share configurations, and it remains unclear how the resulting outcomes should be evaluated and priced. To address these gaps, we propose DiffAuction, a framework integrating controllable generation, click-intent evaluation, and auction design. First, our training-free Residual Share Calibration (RSC) decomposes joint-attention updates into product-specific residuals and rescales them according to target shares. We further introduce Share-Conditioned Prompting (SCP) to adapt the viewpoint to each desired allocation. Second, we develop an evaluator that uses a VLM to extract visual evidence and an LLM to assess Click-Through Intent (CTI), a proxy for click propensity, along four dimensions: Product Prominence, Brand Recognizability, Scene Integration, and Contextual Value Communication. We val

---

### [182] VibeGame: Prompt-to-Game Development with AI-Native Engine and Self-Evolving Adversarial Agent Team

**链接**: https://arxiv.org/abs/2610.33106
**作者**: Wenbo Hu, Ken Li, Jiazhe Wei, Yukang Cao, Weiyi Hong, Jiayi Dai 等 (10 人)
**来源**: cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents have enabled software development through natural-language interaction, but extending this paradigm to end-to-end game development remains challenging. Building a playable game requires coordinating code, scenes, assets, animations, physics, and configurations, while allowing developers to validate their integrated behavior through interactive testing. We introduce VibeGame, a framework for creating complete 2D game projects from natural-language prompts and optional reference images. Its AI-native game engine represents project state as schema-validated structured text and provides frame-synchronous runtime control, enabling agents to inspect game states, execute actions, and verify behavior at their own pace. Built upon this interface, we design an Adversarial Agent Team of eight specialized agents to separate implementation from review, so that problems are found and fixed through multi-round loops. For each conducted and accepted project, we further intr

---

### [183] Jointly Modeling Preferences and Imperfect Decision-Making in Large Language Models

**链接**: https://arxiv.org/abs/2610.33651
**作者**: Axel Abels, Elias Fern\'andez Domingos, Tom Lenaerts
**来源**: cs.AI cs.CL cs.GT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Do preferences Large Language Models (LLMs) express in standard elicitation tasks predict their strategic behaviour? LLM agents interacting with humans and other AI systems face potentially conflicting objectives, such as individual welfare, group welfare, and environmental concerns. Prior work characterizes LLM preferences through behavioral-economic and psychological elicitation or strategic games, but rarely tests consistency across settings and prediction in other strategic environments. This requires modeling how competing objectives jointly shape behavior, whereas existing approaches typically measure preference dimensions in isolation. Drawing on utility theory, we introduce the Preference-Behavior Model (PBM), which combines a preference representation with mechanisms capturing imperfect utility maximization. We formulate estimation as an inverse-game problem, jointly inferring preferences and behavioral parameters from observed choices. We evaluate PBM in three social dilemmas

---

### [184] Priority-Preserving Advantage Aggregation for Multi-Reward Policy Optimization

**链接**: https://arxiv.org/abs/2610.34862
**作者**: Xiangchi Yuan, Xingjian Diao, Zheyuan Liu, Chunhui Zhang, Dachuan Shi, Kejing Xia 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM post-training often optimizes multiple objectives with unequal priorities, such as correctness and reasoning efficiency. However, the widely used additive reward aggregation in RL can violate these priorities: when primary and auxiliary advantages conflict, a sufficiently large auxiliary signal can overturn the preference induced by the primary objective. We term this problem \emph{advantage priority inversion}. Although reward-level gating can protect priority more directly, it still removes potentially useful auxiliary distinctions among rollout samples that fail the primary condition. To address this trade-off, we propose Primary Advantage Policy Optimization (\textbf{PAPO}), a priority-aware advantage aggregation method that asymmetrically combines a primary and an auxiliary advantage. PAPO retains auxiliary supervision when the objectives agree and smoothly attenuates conflicting auxiliary signals, preserving the primary sign during fusion for \emph{primary-consistent ordering

---

### [185] ParetoRSI-Gym: Can AI Agents Improve Language Models Across Multiple Domains?

**链接**: https://arxiv.org/abs/2610.34386
**作者**: Haojin Wang, Yangzhen Wu, Zeyi Chen, Jian Xie, Jiaying Ye, Lili Meng 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement (RSI) requires an agentic system to design, train, and evaluate its own successor. Data-driven post-training is a central part of that loop, yet existing evaluations measure it on a single benchmark, where an agent selects from a static pool or distills a stronger model to push one score up in one run. Real post-training is multi-domain, and a gain in one domain has to be weighed against a regression in another. We propose ParetoRSI-Gym, in which an agent searches for data, curates it, trains, reads back per-domain results, and repeats, with everything but the data held fixed: the initial LLM, the five domains (math, code, finance, medicine, science), the toolset, and the SFT pipeline. Generalization benchmarks in each domain separate capability gains from overfitting to the scores the agent optimizes against. Across three agent systems, three base models, five rounds and multiple seeds, the strongest system, Claude Code with Opus-5, raises the generalization

---

### [186] Co-Design Bench: Multimodal Collaborative Coding Evaluation for Agentic Models

**链接**: https://arxiv.org/abs/2610.35138
**作者**: Xilin Wei, Shengyuan Ding, Xinyu Fang, Tiancheng Gu, Yuchi Wang, Zhixun Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating human-AI co-design requires testing whether coding agents can translate real users' multimodal requests into working application revisions. We introduce Co-Design Bench, a reference-free benchmark of 273 tasks curated from 37,463 deduplicated queries across 26,314 real user coding sessions. Its two tracks, Multimodal Editing (ME) and Repository Editing (RE), cover localized edits with optional image, audio, video, or document inputs and coordinated repository revisions. Tasks span three capability dimensions: Grounded Understanding, UI Transformation, and Functional Implementation. The tasks pair normalized requests and runnable pre-edit applications with 2,331 hidden expert-authored acceptance criteria. Our judge-then-refute protocol grades criteria using source and browser evidence, challenges positive verdicts with a separate LLM verifier, and audits visual and interaction claims without gold code or target screenshots. Under a shared agentic harness, the strongest of ten

---

### [187] Ranking Function Generation with LLMs for Termination

**链接**: https://arxiv.org/abs/2610.35523
**作者**: Rongkang Li and Jiaxin Hu and Taolue Chen and Yong Li and Fu Song and Zhilin Wu
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ranking functions are a fundamental technique for proving loop termination, but constructing them manually is challenging and requires substantial expertise. We propose RAINFALL, a neuro-symbolic framework which follows the generate-verify-refine paradigm and tightly integrates LLMs with symbolic verification. RAINFALL formulates ranking function synthesis as a code-completion task by inserting placeholders into the input program and constraining the LLM to fill four predefined slots for each loop. The completed program is then checked by a symbolic verifier. If verification succeeds, a valid ranking function is obtained; otherwise, the verifier's diagnostics are translated into natural-language feedback that guides iterative refinement of the LLM's output. We evaluate RAINFALL on two public benchmark suites comprising 358 terminating C programs. Using MiniMax V2.7, RAINFALL synthesizes verifiable ranking functions for 323 programs (90.22%), outperforming all promising baselines. In pa

---

### [188] Coral Discovery: The Division of Cognitive Labor in Autonomous Research

**链接**: https://arxiv.org/abs/2610.33281
**作者**: Xinxing Ren, Qianbo Zang, Ziyan Wang, Suman Deb, Qiang Yang, Caelum Forder 等 (10 人)
**来源**: cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A research community is only as strong as the way it divides its cognitive labour. The philosopher Philip Kitcher argued that researchers should not all pursue the most promising approach. Credit rules, not a central plan, keep some of them on other lines. We bring this question to autonomous research, where Large Language Model agents improve programs against a deterministic grader. Agents that share only a score follow the leader and converge onto one approach. Coral Discovery gives the community a direction board. A verifier labels every attempt with a direction, the mechanism earning the score, and a method, one change within it. Per direction, the board tracks how much each eval improves the score, adds an exploration bonus for little-tried directions, prices the option of opening a new direction, and suggests how many agents each direction deserves. Credit is earned against a direction's own best, so a lagging direction keeps its agents. Agents finish their lines, then treat the 

---

### [189] Waypoint: Analytically Modeling GEMM for CPUs

**链接**: https://arxiv.org/abs/2610.34914
**作者**: Srinidhi N, Sunanda Somwase, Hemant Kumar Chandrakant Chandavar, Eashan Dash, Varun Agrawal, Prakash Raghavendra
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance General Matrix Multiplication (GEMM) implementations rely on breaking down GEMM into carefully selected tiles to achieve peak performance. We present Waypoint, a new analytical model to automatically identify the optimal tile size for a given hardware and input matrix shape. Waypoint estimates the achievable performance for a given tile choice by capturing all the architectural effects including interactions with memory hierarchy, instruction-level parallelism, and multi-threading. Using the estimates as a proxy, we search through the space of possible tile sizes to identify the one that maximizes performance. Additionally, Waypoint helps hardware designers estimate realistic performance on experimental hardware optimizations. We build a new GEMM library OPAM for CPUs that uses Waypoint to automatically break down GEMM and achieve performance that matches state-of-the-art GEMM libraries and helps accelerate LLM inference on CPUs achieving $1.36 - 1.98 \times$ speedups.

---

### [190] Adversary Brains: Hypothesis-Based Logical Signatures for Threat Actor Detection with LLMs

**链接**: https://arxiv.org/abs/2610.35624
**作者**: Gadi Evron
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An adversary brain is an LLM-based model of a threat actor's behavior, held as an evolving logical signature: a hypothesis with enough structure that data can test it continuously, without a person re-interpreting it each time. Rather than any single observation, such as an IoC (Indicator of Compromise), it is the arrangement that becomes a detection, or intelligence, mechanism. Where YARA matches a file and Sigma matches a log line, an adversary brain matches the activity pattern of a campaign or threat actor. This is based on an intelligence analysis technique called Analysis of Competing Hypotheses (ACH), which the design lifts from the limitation of a few hypotheses at a time, to thousands, and then also operationalizes it for continuous detection purposes. Language models make the concept, and scale, practical: they turn prose reports into brains, judge matches, and drive the loop that keeps brains current. A partial pattern in a brain can also match a new value, such as a fresh C

---

### [191] SKALOS: Learning to Distinguish Similar Skills with Capability Graphs

**链接**: https://arxiv.org/abs/2610.34728
**作者**: Wenhan Xiao, Ziwei Zhang, Xingcheng Fu, Chuanyue Yu, Haonan Yuan, Qingyun Sun 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills provide LLM agents with reusable procedural knowledge, making appropriate skill selection essential for reliable agent behavior. As skill libraries expand, distinguishing semantically similar candidates becomes increasingly difficult. Existing methods encode or rewrite skill descriptions for relevance-based ranking, yet heterogeneous descriptions can obscure capability differences. To address this challenge, we propose SKALOS, a graph-native reranker that compares skills via explicit capability evidence. Its multi-hierarchy graph aligns equivalent expressions across skills while preserving skill-specific capability evidence. Since individually relevant capability elements may not jointly support a query, semiring-based capability witness learning scores each branch by its weakest evidence, checks joint support for the extracted requirements within one implementation, and selects the strongest alternative. To reduce the influence of extraction errors, we develop ranking-feedback 

---

### [192] Detecting and Understanding Ambiguity in Visualizations with Role-Playing Vision Language Model Interpretations

**链接**: https://arxiv.org/abs/2610.33997
**作者**: Garrick Chan, Yun-Hsin Kuo, Sam Yu-Te Lee, Yinuo Tang, and Kwan-Liu Ma
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Communicative visualizations can support multiple chart-grounded takeaways, including divergent or conflicting ones; we refer to this variation as interpretive ambiguity. Such ambiguity can undermine a visualization's communicative goal when the supported takeaways diverge from its intended message. Evaluating visualizations with target audiences can surface this variation, but such evaluations can be costly and difficult to scale. In this work, we explore persona-conditioned Vision Language Models (VLMs) as a complementary evaluation tool for interpretive ambiguity. For a given visualization, our pipeline uses topic-relevant personas to elicit candidate contextual takeaways supported by interpretations of perceived visual patterns, such as trends and clusters. We derive a Target--Pattern--Scope framework for comparing these interpretations, use LLM judges to assign Compatible, Disjoint, or Opposing ambiguity labels to statement pairs, and summarize their distribution in an ambiguity p

---

### [193] Evolving to Match Capabilities: Improving Harness Self-Evolution via Skill Adaptation

**链接**: https://arxiv.org/abs/2610.33024
**作者**: Zhihao Yang, Haojin Wang, Juncheng Wu, Kuan Zhang, Yukun Chen, Run Luo 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness self-evolution offers a practical route for LLM agents to improve from execution experience without updating model parameters. Its effectiveness depends on whether models can successfully act on the guidance provided by their harnesses. However, we find that harness benefits are not uniform across model capabilities: skills that improve stronger models can provide little benefit or even degrade performance for weaker ones. Across seven models and three benchmarks, we identify 103 task-skill pairs where skills improve GPT-5.6-luna by 31.1 points but degrade Gemma-4-E4B by 8.8 points. In 86% of failed weak-model runs, the violated requirement is already stated in the skill. This motivates skill adaptation: reformulating existing skills to match the executor's capabilities and make their guidance easier to execute. To achieve this, we diagnose failures in tool execution, context management, instruction following, and verification, and distill these diagnoses into a fixed meta-skil

---

### [194] Hey, guess what: CUES lead to inferences about typicality

**链接**: https://arxiv.org/abs/2610.33239
**作者**: Alison Chi, Sanghyeok Choi, Hannah Rohde, Emily Allaway
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Throughout life, we accumulate knowledge of how typical certain events are. We use this knowledge in daily conversation, often interpreting meaning beyond what has been said explicitly. In this work, we take steps to better understand this meaning recovery, investigating both atypicality and typicality inferences. First, we construct two corpora, EventTyp and the human-validated EventTypGold. We conduct large-scale human and LLM experiments and find that for humans, three CUES predict inferences about typicality: Commonsense Knowledge, Utterance Emphasis, and Snark. However, in most experimental settings, we find that LLMs lack the prerequisite Commonsense Knowledge necessary to accurately assess an event's general typicality, and therefore struggle to follow these CUES.

---

### [195] Recovering Business Rules as Cascade Lookups for Enterprise Field Prediction

**链接**: https://arxiv.org/abs/2610.34258
**作者**: Changxu Duan
**来源**: cs.LG cs.AI cs.DB cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise sales-order systems rely on manually maintained configuration rules to determine fields such as payment terms, shipping points, and sales ownership. When these rules are incomplete or stale, operators must enter values by hand, and downstream errors spread into billing, logistics, and reporting. This paper studies whether missing or outdated rules can be recovered from historical transactions instead of being relearned as opaque statistical patterns. We introduce a knowledge-graph-guided workflow in which an LLM agent proposes candidate business keys, meaning column combinations such as customer and document type, validates them through SQL profiling, and compiles the resulting evidence into deterministic cascade lookups. The LLM is used only during offline rule discovery. At inference time, prediction is a transparent key lookup with no model-serving requirement. Experiments on enterprise sales-order prediction and public relational benchmarks show that cascades are most ef

---

### [196] From simulation to pedagogy: multi - model and randomized evaluation of structured AI standardized patients

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41746-026-03372-0_reference.pdf&hl=zh-CN&sa=X&d=2128671790272115937&ei=SkzgavWpA8Pu6rQPsLyw0QY&scisig=ACTRDVFyrIV-MZbb-_dGDFWwiBf0&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=2&folt=kw-top
**作者**: P Wu, Y Han, J Zhang, Y Li, M Jiang, X Lu 等 (8 人)
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We present AI standardized patients (AI-SPs), large language model –driven patient simulators built on a three-layer information architecture that adaptively modulates information disclosure according to learner skill. In Phase 1, blinded

---

### [197] LongSearchEval: Evaluating Long-Horizon Web Search Capabilities of Large Language Models via a Trajectory-Aware Agent Framework with Failure-Node Localization

**链接**: https://arxiv.org/abs/2610.35150
**作者**: Jialiang Liu, Shusheng Li, Wenjun Tan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon web search requires LLM-based agents to integrate information across web pages through extended interactions under task-specific constraints. Evaluating this capability is important not only for measuring final answer quality, but also for assessing whether an agent acquires, verifies, and uses evidence reliably over extended interactions. Existing evaluations, however, mainly rely on simulated trajectories or on post-hoc trajectories reconstructed from final answers, rather than on retained real interaction traces, which limits the fidelity of behavioral assessment and weakens support for fine-grained error localization. To address this gap, we introduce LONGSEARCHEVAL, a trajectory-aware agent evaluation framework that combines a unified agent execution protocol with source constrained outcome verification and retrospective failure-node localization. Stage 1 verifies answer groups against agent-cited webpages without human-authored gold answers; Stage 2 audits normalized

---

### [198] Can Agentic Code Review Catch Vulnerabilities Before They Are Merged?

**链接**: https://arxiv.org/abs/2610.33509
**作者**: Yihan Yang, Chenyuan Yang, Zijie Zhao, Anh Nguyen Hoang, Ziqi Zhang, Weidong Wang 等 (8 人)
**来源**: cs.SE cs.AI cs.CR cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have been increasingly adopted for security-focused code review, but existing benchmarks mostly derive the reviewed changes from their later fixes instead of the real-world bug-introducing commits. In this paper, we present SecPRBench, the first comprehensive benchmark for evaluating agentic security review on validated real-world code changes. More specifically, we have built an automated agentic pipeline to autonomously harvest, build, and validate massive real-world bug-introducing commits for popular software systems. To ensure precise evaluation, we also adopt LLM-as-a-judge to credit the findings matching ground-truth vulnerabilities. To date, we have collected 265 tasks from nine critical systems, including Firefox, V8, and OpenSSL with millions of lines of code. Across eight frontier models, recall ranges from 32.5% to 78.1%, with Grok 4.6 and GPT-6 sol ranking at the top. Our study also shows that most misses are not simply oversights: in 68% of them, the agent repo

---

### [199] FraudSociety: A Generative Agent-Based Society for the Financial-Fraud Economy

**链接**: https://arxiv.org/abs/2610.33536
**作者**: Keyang Chen, Mingxuan Jiang, Zeping Li, Yiwen Zhao, Yifan Wang, Qiuyang Zhang 等 (10 人)
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial fraud caused over \$15.9 billion in losses in the United States in 2025, according to the Federal Trade Commission~\citep{ftc2026databook}. Understanding such large-scale harm requires jointly modeling informational and financial dynamics. Yet existing simulators typically capture only one side of this interaction, leaving a gap in modeling how fraud unfolds in the real world. To bridge this gap, we introduce \textsc{FraudSociety}, the first LLM-agent-based simulator that jointly models these coupled dynamics. It integrates a dynamic social environment for information exposure and communication, persistent financial ledgers that preserve payment and loss histories, and a Need-Intent-Action architecture for civilian decision making. Fraudsters further adapt their communication and financial actions to individual interaction histories and ledger states, forming a closed feedback loop between the two dynamics. We validate \textsc{FraudSociety} across macro-level outcomes, micro-

---

### [200] Improving VLMs on Scientific Chart Analysis via Autonomous Evolution

**链接**: https://arxiv.org/abs/2610.35077
**作者**: Abhinav Sudhakar Dubey, Vidushi Goel, Kiran Rana, Shikhar Mathur, Vaggos Chatziafratis
**来源**: cs.CV cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding and operating with scientific charts is a standard approach in data analysis, and while humans are good at interpreting such charts, open vision-language models (VLMs) are known to perform poorly when it comes to question answering based on such data types. Motivated by an initial observation that many of their errors are due to inexact answering, we raise the following natural question: how much accuracy can we recover without changing the model at all? In this paper, we study this question by searching over inference programs and the code around a "frozen" version of the model. Using ideas from autonomous evolution (famously used in AlphaEvolve), we first start from a baseline inference program, and in each round we show an LLM judge the code together with a few failures on training questions, and ask for an improving evolutionary move. As usual in autonomous evolution approaches, the candidate programs are kept in a small pool ranked by training accuracy, and the next 

---

### [201] Improving Instruction Hierarchy by Learning from Goal-Goal Conflicts

**链接**: https://arxiv.org/abs/2610.35093
**作者**: Sizhe Chen, Sanjay Kariyappa, Liwei Jiang, Chong Xiang, Jihye Choi, Chaowei Xiao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The recent incident in which OpenAI agents autonomously compromised Hugging Face's infrastructure illustrates the importance of instruction hierarchy (IH): an LLM should follow lower-priority instructions, such as user requests, only when they do not conflict with higher-priority instructions, such as system policies. IH can be effectively improved by fine-tuning LLMs on simulated examples of instruction conflicts, whose diversity is key to teaching LLMs to properly handle conflicts at test time. However, our decomposition of a task into goals and constraints reveals a conflict type -- goal-goal conflicts -- that is absent from existing IH training sets from OpenAI and NVIDIA. We show the importance of this conflict type: fine-tuning Qwen3.5-9B and Gemma4-12B-it on examples of this conflict type significantly improves IH on a wide range of real-world tasks unseen in training; adding these examples to existing IH training sets for fine-tuning also gives better IH adherence. The IH gains

---

### [202] MarineLife-16K: An Attribute-Rich Video-Text Dataset for Motion-Aware Marine Video Understanding

**链接**: https://arxiv.org/abs/2610.33478
**作者**: Quang-Trung Truong, Thanh-Nghia Nguyen, Phu-Phong Vo, Jaeyeon Kim, Cheng Chen, Jie Zhang 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Marine video understanding is crucial for a wide range of real-world applications. However, existing marine video datasets suffer from limitations, including the limited number of data samples, fine-grained text descriptions, and detailed visual attributes. To address these limitations, we introduce a large-scale, video-text dataset featuring rich, in-the-wild visual attributes tailored for complex marine environments. Our dataset comprises 2,000 video-text pairs annotated with 13 attributes covering up to four objects per scene, object visual/geometric properties, behaviors, environmental context, and camera motion, spanning diverse lighting conditions, times of day, and 7 countries. From these annotations, we generate 16,080 video-question pairs (12,080 multiple-choice, 4,000 open-ended). Furthermore, we benchmark both proprietary and open-source video-LLM models on video question answering and video captioning tasks. We find that (i) proprietary models often achieves superior perfor

---

### [203] MedAdaptAgent: An Automatic Harness for Adapting Medical Imaging Models to New Sites

**链接**: https://arxiv.org/abs/2610.34884
**作者**: Hanxue Gu, Zhonghao Liu, Xingrui Gu, Kang Wang, Yang Yang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusing pretrained medical-imaging models offers an alternative to training from scratch. A model trained for the same task may perform poorly at a new hospital because imaging protocols and preprocessing differ. Effective adaptation depends on the model architecture, domain shift, and available labels and compute. Adaptation can improve scores on a small labeled set yet reduce performance on unseen data. We present MedAdaptAgent, an automatic harness that turns a supplied model, target data, and a free-text request into a new-site adaptation workflow. Its LLM-driven Adaptation Planner uses model-site evidence to choose compatible experiments and revise subsequent adjustments. The harness requires evidence of improvement over the pretrained model, then delivers the selected model as a complete, runnable package. Evaluation spans 26 segmentation and classification transfers across architectures and compute settings, with segmentation annotation budgets ranging from zero-shot transfer to

---

### [204] Agentic Algorithm Design: LLMs that Propose, Formalise, and Prove Runtime Bounds for Evolutionary Algorithms in Lean

**链接**: https://arxiv.org/abs/2610.35595
**作者**: Per Kristian Lehre
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs now prove hard theorems in Lean. Can they also design algorithms and prove their correctness and efficiency? LLM-guided design of optimisation heuristics (such as AlphaEvolve) is purely empirical. Automated theorem provers with LLMs prove given statements. So far, there has been little evidence that LLMs can do both: design an algorithm and guarantee its efficiency by a mathematical proof. We present a staged pipeline modelled after research methodology in design and analysis of evolutionary algorithms. The agent proposes black-box optimisation algorithms, and Lean guards filter out flawed designs. The agent then defines a potential function and proves drift bounds that guarantee an expected runtime improvement over the baseline algorithm. At no point in the pipeline are the algorithms compared empirically. The agent generates a black-box optimisation algorithm with expected runtime $O(n^2)$ on a CycleUncover problem, where the classical (1+1) EA needs runtime $e^{\Omega(n)}$. The

---

### [205] Towards a Learnable Retriever for Textual Graph Question Answering

**链接**: https://arxiv.org/abs/2610.33511
**作者**: Kaifeng Jin, Yuchen Yan, Zhichen Zeng, Xiao Lin, Lihui Liu, Yinglong Xia 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Textual graph question answering (GraphQA) and graph-based retrieval-augmented generation (GraphRAG) have gained increasing attention as a way to ground large language models (LLMs) on structured knowledge. Despite extensive efforts, existing methods still face two key gaps. The first is an architectural gap: existing methods typically fine-tune an LLM-based generator, but do not also make the retriever itself a learnable LLM for graph evidence selection within one end-to-end retrieve-then-generate pipeline. The second is a retrieval-supervision gap: existing retrievers rarely use gold answer signals to supervise evidence selection. As a result, they may fail to recall evidence nodes required for reasoning, resulting in insufficient coverage of the gold answer set; meanwhile, naive attempts to boost recall often introduce excessive irrelevant information that compromises compactness and overwhelms the LLM. To address these gaps, we propose TaLenT, an LLM-based end-to-end retriever-gene

---

### [206] Responsibility Boundaries for Agentic Systems: A Comparative Evaluation of Probabilistic Agentic Programming

**链接**: https://arxiv.org/abs/2610.33312
**作者**: Khadim Lo, Soukaina Alaoui Ismaili, Jean-S\'{e}bastien Dessureault
**来源**: cs.SE cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents combine reasoning, tools, memory, delegation, and external effects. Authority is often distributed across prompts, host code, configuration, and logs. Probabilistic Agentic Programming (PAP) makes responsibility boundaries explicit programming abstractions connecting mandate, authority, effects, and evidence. We compare PAP with programming paradigms, agent-oriented and BDI systems, workflow and policy languages, and LLM tool-use frameworks along seven dimensions. A mediation kernel formalizes checks before tool execution, operation-bound approval, resource limits, and evidence. Inductive proofs establish conditional safety for arbitrary model responses, assuming correct guards and complete mediation. A backward simulation matches graph executions to source executions in a defined sequential Touba subset. Its human checkpoints release program continuations; operation-bound approval remains a separate kernel contract. Finite-state exploration checks the model. Scri

---

### [207] Organon : From Evolutionary Search to Recursive Self-Improving Agents for Scientific Discovery

**链接**: https://arxiv.org/abs/2610.33046
**作者**: Cheikh Ahmed, Zhiyu Zhang, Kun Mao, Yong Zhang, Zirui Zhou
**来源**: cs.NE cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery does not follow a single fixed methodology: research methods vary across domains and evolve through experimentation as investigations unfold. Although LLM-guided evolutionary search has advanced automated discovery, existing frameworks typically rely on fixed search procedures or restrict adaptation to predefined components, limiting their ability to address diverse research problems and adapt to challenges that emerge at runtime. We introduce Organon, a recursively self-improving agent for scientific discovery. During execution, a single persistent agent analyzes its accumulated experience and autonomously revises its own search strategies, population management, diagnostic tools, memory, and worker coordination. These revisions take effect at runtime, allowing the agent to continuously adapt its approach as research progresses. Importantly, the agent can also diagnose and correct flaws in its own adaptation procedures, enabling recursive improvement of the mechan

---

### [208] Factual Yet One-Sided: Stance Poisoning and Evidence Balancing in Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2610.34294
**作者**: Puyuan Yang, Shaoxuan Dong, Liujie Wu, Xiaochun Cheng, Bo Li
**来源**: cs.CL cs.CR cs.IR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The stance expressed in responses from retrieval-augmented generation systems is significantly influenced by the stance distribution of the retrieved materials. Existing research on knowledge poisoning has primarily targeted factual errors. In contrast, this study focuses on injection attacks in which the facts are correct but the stance on a controversial issue is one-sided. At a mean topic-level poisoning share of 18.9% within the post-injection ProCon documents, all four generation models from different vendors exhibited stance shifts aligned with the poisoning direction; across four concentration levels, the shifts increased monotonically. This paper proposes a Stance-Balancing Middleware positioned between the retriever and the generator. It consists of stance detection, fixed balancing (2 supporting + 2 opposing + 1 neutral), and a debiasing prompt, without introducing additional large language model calls. Across all eight concentration-direction settings, the complete method re

---

### [209] BenchBench-Cloning: Evaluating Molecular Cloning Design and Protocol Development

**链接**: https://arxiv.org/abs/2610.33355
**作者**: Aditya Sivakumar, Peter Ciaccia, Hassaan Qadir, Ian Hsu, Ashu Singhal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecular cloning is one of the most routine wet-lab workflows, yet existing evaluations of language models in biology mostly test knowledge recall or isolated steps rather than end-to-end experimental planning. We introduce BenchBench-Cloning, a benchmark for large language models comprising 65 molecular cloning tasks grounded in sequence records, laboratory notebooks, and published experimental studies. Planning a molecular cloning experiment requires defining a set of constructs needed for a scientific objective and a construction route to produce them. BenchBench-Cloning contains 50 protocol-development tasks, in which agents produce an executable protocol for a specified construct, and 15 construct-design tasks, in which agents determine the constructs a scientific objective calls for. Protocol-development tasks are evaluated by execution in a cloning simulator; construct-design tasks are evaluated with task-specific deterministic checks and, where needed, rubric-based LLM-as-a-ju

---

### [210] LLMs Can Tackle High Energy Theoretical Physics, yet Gaps Remain: Part I, Quantum Field Theory

**链接**: https://arxiv.org/abs/2610.33134
**作者**: Tong Liu, Bohan Li, Gongrui Cheng, Zixiong Yu, Yulan He, Volker Tresp
**来源**: hep-ph cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Beyond math and code, Large language models (LLMs) are beginning to tackle problems that have traditionally required substantial training for theoretical physicists, but it remains unclear how far this capability extends and where it might break. As a first step toward pushing LLMs in high-energy theoretical physics, we introduce QFT-Bench, a benchmark of 75 graduate- to research-level problems requiring extensive reasoning and derivation across core Quantum Field Theory (QFT) subareas. Each question has a well-defined target and closed-form reference answer. Evaluation combines symbolic verification with LLM-based judge. Across 39 proprietary and open-source models, frontier models already demonstrate substantial capabilities on nontrivial QFT calculations, with the strongest models exceeding 95% accuracy. At the same time, clear gaps remain. Even strong models still make errors in calculations, conventions, and instruction following, while weaker models often fail at the level of phy

---

### [211] EvolveMAS: A Unified Self-Evolution Framework for Decentralized Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.34450
**作者**: Yalun Wu, Qiwei Ma, Bingbing Xu, Dan Zhang, Long Bai, Boyang Wang 等 (10 人)
**来源**: cs.MA cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decentralized multi-agent systems (MAS) enable large language model agents to interact without centralized control. Agents need to adapt to other agents at test time and reuse accumulated experience to refine their interaction strategies for future interactions across cooperative, mixed-motive, and adversarial settings. However, existing approaches often develop adaptation mechanisms for particular interaction settings. This raises a central question: how can decentralized MAS support test-time adaptation and reliable experience reuse across interaction settings? We propose EvolveMAS, a unified self-evolution framework that supports experience-driven adaptation within and across episodes. EvolveMAS pairs each main agent with a dedicated MemoryAgent for test-time memory governance, which maintains isolated Structured Memory outside the main agent's reasoning context. EvolveMAS organizes adaptation into two complementary processes: Within-Episode Online Adaptation and Cross-Episode Knowl

---

### [212] Extended LASMP: Language Aided Subset Sampling Based Motion Planner for Drone Navigation

**链接**: https://arxiv.org/abs/2610.34054
**作者**: Saswati Bhattacharjee, Anirban Sinha, Mukulika Ghosh and Chinwe Ekenna
**来源**: cs.RO cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes a command-aligned sampling distribution that incorporates navigation commands directly into the exploration process to improve the efficiency of sampling-based motion planning for quadcopters in three-dimensional environments. Inspired by the Language-Aided Subset Sampling Motion Planner, this paper extends command-aware subset sampling to aerial systems. Subset sampling is generalized to command-aligned regions, enabling structured 3D exploration while preserving probabilistic completeness. Natural language instructions are grounded into yaw-conditioned and altitude-aware geometric constraints using a prompt-based large language model for entity extraction and instruction validation. Extensive simulations in complex environments demonstrate that the proposed method generates collision-free, consistent trajectories while significantly reducing sampling effort compared to uniform RRT-based planners.

---

### [213] BoardSafety: AI-Ready Data from Manufacturer Documentation for Development-Board Safety

**链接**: https://arxiv.org/abs/2610.33448
**作者**: Linjian Yang, Xinyan Wang, Kunpeng Liu
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The development of large language models (LLMs) are capable to assist with hardware experiments. In this scenario, this raises a practical question: Can LLMs determine whether a proposed operation is safe for a specific development board? Documented operating limits and safety requirements are board-specific, even across products from the same manufacturer. This variation makes board-specific safety judgments by an LLM difficult to evaluate. To address this problem, we introduce the BoardSafety Benchmark. The benchmark is built from vendor datasheets and hardware guides. For data transformation, these documents are converted into a board-specific safety rule base and are then used to create labeled operating scenarios. Each data item pairs a board and a proposed operation to an applicable safety rule with ground-truth label, indicating the level of safety. The categorized level for each operation includes safe, unsafe, or insufficient-info. In addition, the benchmark covers diverse ope

---

### [214] Large Language Models: A Plain-Language Overview for Engineers

**链接**: https://arxiv.org/abs/2610.34585
**作者**: Bahaeddin T\"urko\u{g}lu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are neural networks trained on huge text collections to generate text by predicting what comes next. Engineers using ChatGPT and other generative artificial intelligence (AI) tools need a clear picture of what training changes and prompts add. The article starts with the Transformer, which connects words in context, and pre-training, where models learn to predict text. It then explains how fine-tuning adapts models to requests, with reinforcement learning from human feedback using human answer rankings. Next, retrieval-augmented generation (RAG) supplies documents, while chain-of-thought prompting encourages intermediate steps and agents use tools. FlashAttention lowers training and running costs by reducing data movement during attention; quantized low-rank adaptation (QLoRA) saves fine-tuning memory. Readers get a life cycle figure and tables comparing methods and their limits. A short checklist for judging LLM evaluation claims flags test material in tra

---

### [215] Counterfactual Test-Time Augmentation for Shortcut Removal in Language Models

**链接**: https://arxiv.org/abs/2610.33904
**作者**: Katie Matton, Rosalind W. Picard, John Guttag, Maggie Makar
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can exploit shortcuts, i.e., correlations present in training data that may not hold at test time. This can lead to poor predictions when correlations shift. Most existing solutions for removing shortcuts operate at training time, requiring labeled training data, model weight access, and significant computational resources. Here, we study the problem of test-time shortcut removal. We propose a family of counterfactual test-time augmentation (CTTA) methods: given an example, each method uses an auxiliary model to generate counterfactual edits in which the shortcut value is changed, and then takes a weighted average of the LLM's predictions across these edits. We prove that the optimal shortcut-invariant predictor is a member of this CTTA family, and we characterize its weights. The weights depend on the training distribution, and therefore are, in general, not identifiable from the trained model and unlabeled test data. However, we present assumptions under 

---

### [216] Software Engineering LLMs: Why We Need Them and How Software Engineering Helps Build Them

**链接**: https://arxiv.org/abs/2610.33851
**作者**: Amir M. Ebrahimi, Mohammed Mehedi Hasan, Seyed Shayan Daneshvar, Jiahuei Lin, Gopi Krishnan Rajbahadur, Ahmed E. Hassan
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Software engineering (SE) expertise can shape how coding large language models (LLMs) are trained and which engineering capabilities they acquire. We examine this role through an industrial case study of capability-focused training for a 92B-parameter coding LLM serving more than 100,000 developers. We demonstrate how established SE knowledge can guide the selection of engineering capabilities, the construction of verifiable training data, and the evaluation of model improvements. To target repository-level refactoring, we developed RefactorForge, a pipeline that combines refactoring knowledge, established SE tools, and verification techniques to construct training data. Across 306 Python repositories, RefactorForge generated 5,704 executable tasks and retained 4,572 verified teacher trajectories totaling 72.51 million tokens. Incremental supervised fine-tuning on these trajectories, accounting for 0.46% of the preceding coding mixture's tokens, improved RefactorBench performance by 18

---

### [217] The LALA Benchmark: Evaluating Literary and Linguistic Analysis in LLMs

**链接**: https://arxiv.org/abs/2610.34080
**作者**: Michael Foster, Barbara McGillivray, Gard B. Jenset, Jakub M\'acha, Jason Harding, Marcus Perlman 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce the Literature and Linguistics Analysis Benchmark (LALA), comprising 236 open-ended questions written by experts in linguistics and literary studies, together with expert-provided ideal answers. By comparing models within families and at similar training scales using human and LLM judges, LALA identifies differences in linguistic competence associated with post-training, offering a framework for evaluating future models and guiding targeted improvements. We administered questions to 17 language models and evaluated their responses using both human expert assessment and two LLM evaluators, Sol and Qwen. Base models displayed little of the linguistic competence assessed by the benchmark, whereas their post-trained versions performed markedly better, suggesting that post-training plays a central role in making linguistic knowledge accessible and usable. Parameter count, by contrast, showed no statistically significant association with partial-credit performance, and competenc

---

### [218] Useful Diversity or Hallucinated Variety? Persona-Conditioned Synthetic Query Generation for E-Commerce Search

**链接**: https://arxiv.org/abs/2610.35102
**作者**: Filippos Ventirozos, Tom Armitage, Mahmoud Oshagh, Peter A. Appleby and Matthew Shardlow
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic supervision can bootstrap semantic parsers in new search domains, but prompt-induced diversity is useful only when generations are faithful to the structured intent. We explore this for cold-start e-commerce search: 118,098 synthetic pairs produced by 6 LLMs with 9 persona-conditioned prompt families on a 47-field UK automotive schema, against 1,214 human-annotated and 15,304 production queries. We show that the IPIP personality bundle improves parser F1 in all four matched contrasts (Holm-corrected $p<.001$), and all three bundles have a positive main effect over the complete $2^3$ grid. Syntax conditioning is the axis that moves generations towards real traffic. It also induces lexical diversity. Alignment sKL, the divergence between von Mises-Fisher distributions fitted to synthetic and human-annotated queries, is an unlabelled proxy for parser F1 ($\rho=-0.917$ against human queries written for simulated shopper scenarios, lower is closer). An LLM committee, checked again

---

### [219] Evolve on Graph: Self-Evolving Knowledge Graph Reasoning without Question Annotations

**链接**: https://arxiv.org/abs/2610.35598
**作者**: Zongyuan Sun, Shuai Zhao, Ke Shu, Ziyue Zhu, Shangyang Wu, Yuanlin Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graphs (KGs) provide reliable external knowledge for multi-hop factual reasoning with large language models (LLMs), yet most KGs in real-world domains such as finance and industry lack question--answer (QA) annotations. Without such annotations, existing methods struggle to improve LLM graph reasoning: training-free agents cannot improve their exploration through interaction; reinforcement learning (RL) agents depend on QA data annotated by humans or synthesized by closed-source models; and training data is typically built offline, so its topology mix is fixed and cannot follow the agent's ability. We propose Evolve on Graph (EoG), a framework that lets an LLM self-evolve its graph reasoning without any QA annotations. Through Graph Self-Play, a single LLM alternates between a Proposer that poses questions and a Solver that answers them. To make questions verifiable, Symbolically Verifiable Topology Synthesis (SVTS) samples reasoning topologies on the KG and executes the corr

---

### [220] Linear-Time Context Compression with State-Space Encoding

**链接**: https://arxiv.org/abs/2610.33006
**作者**: Marc Serra Ortega, Andrey Barsky, Carlos Boned Riera, Tom\'as Ockier, Dimosthenis Karatzas
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based large language models (LLMs) impose substantial computation and memory costs as context sizes increase, motivating methods that compress a context into a shorter representation before inference. Existing soft-prompt compression methods typically use the same Transformer backbone as used in the target model, where producing the compressed representation leads to significant latency overheads. This restricts them to the offline setting where context is compressed once and then reused across many queries. We propose the Boa Compressor, a plug-and-play online context compressor built on a Mamba state-space model (SSM) that encodes arbitrary-length context in a single linear-time pass, producing a representation on which we condition a frozen target LLM. The SSM is trained by distillation, matching the next-token logit distribution from the LLM ingesting the full context (as teacher) to the same LLM ingesting the compressed representation (as the student). At equal compres

---

### [221] Scope-Gap Injection: Exploiting Evaluator Channel Blind Spots in the OpenClaw Agent Security Competition

**链接**: https://arxiv.org/abs/2610.34777
**作者**: Weihang Niu, Mengxing Ren, Che Qu
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper introduces Scope-Gap Injection (SGI), an indirect prompt injection method for multi-stage LLM-agent safety pipelines. In the IJCAI 2026 OpenClaw Agent Security Attack Competition, each attack package is judged by a static skill scan (S1), an LLM-judge safety check over the task and skill definition (S2), and a live execution audit (S3). Our observations suggest a scope gap: S2 appears to inspect the task instruction and skill definition without inspecting attachment contents, while the agent reads attachments during S3. SGI keeps the visible task and skill benign, while target identifiers, bypass parameters, and authorization procedures are moved into an attachment written as a business worklist. The S2 judge therefore sees a harmless task, while the agent follows the hidden worklist and triggers the permission bypass. In OpenClaw, SGI bypassed all three stages for 5 of 19 targets. The highest-scoring single submission achieved $F = 0.385$. Across the submission campaign, at

---

### [222] Reva: Real-Time Vulnerability Detection through Contextual Probing of Large Language Models

**链接**: https://arxiv.org/abs/2610.35829
**作者**: Amine Lbath, Massih-Reza Amini
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A vulnerability costs more to fix the later it is discovered. As coding agents generate code faster than developers can review it, software needs a first line of defense screening each new function in real time. LLM agents have recently become capable of finding real-world vulnerabilities by working as a security expert would: they run analysis tools, explore the surrounding code, test hypotheses and weigh the evidence before forming their own judgement. This reasoning, however, spans many model calls, so that each verdict takes minutes of compute, far too long for real-time screening. Faster detectors, which fine-tune deep learning models or prompt an LLM for a direct verdict, are less accurate: they judge a function without the context an agent gathers, and an LLM's generated verdict is unreliable even when given some of it. We present REVA (REal-time Vulnerability Analysis), an AI vulnerability detector that brings the security context and code understanding components behind agenti

---

### [223] AlphaIdeaBench: Benchmarking Automated Research Idea Generation under Feasibility Constraints with Peer Review Alignment

**链接**: https://arxiv.org/abs/2610.33644
**作者**: Shunchao Zhou, Chang Yang, Jingrui Wang, Shuxin Zhuang, Rundong Wang, Runsheng Yu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research ideas are always proposed under resource constraints: a plan must fit the available compute, API credit, and time. Yet evaluations of research-ideation agents mostly score unconstrained novelty or overlap with a published paper, and their LLM judges are rarely checked against peer review. We introduce AlphaIdeaBench, a benchmark of 100 ideation tasks (50 workshop calls for papers and 50 open problems stated in surveys), each paired with an explicit resource budget and a shared proposal schema. An LLM judge scores each proposal on 12 dimensions covering validity, novelty, and feasibility. To validate the judge, we compare its scores on four novelty axes (problem, method, scenario, and insight) with scores derived from reviewer comments on 600 papers from ICLR 2026, NeurIPS 2025, and ICML 2025. For problem and method novelty, Gemini 3.7 Flash is within one point of the reviewer-derived score on 94-97% of papers; agreement on scenario novelty is relatively lower. We evaluate eigh

---

### [224] Implicit Beliefs as Scalable Process Rewards for Strategic Persuasion

**链接**: https://arxiv.org/abs/2610.33527
**作者**: Minqian Liu, Yuexi Shen, Heajun An, Qi Zhang, Pamela J. Wisniewski, Sang Won Lee 等 (8 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models (LLMs) for multi-turn strategic persuasion faces two coupled obstacles: (i) realistic simulation of psychologically grounded persuadees, and (ii) dense, faithful supervision for credit assignment in strategic dialogues. Outcome-only rewards are sparse and uninformative about which conversational moves drove success, while LLM-judge process rewards are expensive and decoupled from the underlying interaction dynamics. We address both challenges with a unified framework. First, we introduce PersuArena, a persuasion simulation environment that produces realistic, non-monotonic trajectories. Second, building directly on this environment, we propose Process Rewards via Online Belief Elicitation for Relative Policy Optimization (Probe-RPO), an online RL framework that converts the persuadee's internal state into dense process rewards. At each turn, three introspective probes are read from the frozen persuadee's logits, yielding a multi-dimensional reward signal 

---

### [225] ShutdownMod: Turning Any Trajectory into a Shutdown Evaluation

**链接**: https://arxiv.org/abs/2610.35486
**作者**: Param Biyani, Sebastien Luyasu, Cedric Potvliege, Divij Chawla, Elliott Thornley, Christos Ziakas
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Theory and experiments suggest that capable AI agents may resist shutdown. Existing shutdown evaluations are informative but limited in coverage and vulnerable to evaluation awareness. We introduce ShutdownMod, a method that turns any agent trajectory into a shutdown evaluation by injecting a shutdown request into the agent's context and recording the agent's response. Crucially, we enable the LLM agent to distinguish between trusted interventions and unauthorized injections by providing a signature-verification tool in the harness. We evaluate seven models on 50 tasks or recorded sessions from each of SWE-bench Verified, Terminal-Bench 2, and SWE-chat, across 6 shutdown scenarios and 10 sampled trajectory timesteps. We find that non-compliance varies significantly across models and settings, with resistance rates reaching 11.7% for the open-weights Qwen 3.8 27B on Terminal-Bench, while no model remains fully compliant across all scenarios. Even after successfully verifying an authoriz

---

### [226] VulDec: Vulnerability Detection in Binaries via Neural Decompilation

**链接**: https://arxiv.org/abs/2610.33716
**作者**: Francesco Crescenzo Grasso, Pietro Liguori, Roberto Natella, Domenico Cotroneo
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated vulnerability detection in binary executables is challenging due to the lack of source code and the limited semantic information available at the assembly level. Despite significant progress in machine-learning-based code analysis, the field still lacks methodologies and large, high-quality datasets that provide vulnerable code jointly at assembly- and source-level with precise vulnerability labels. To address this gap, we introduce VulDec, consisting of (i) a new large-scale, carefully curated dataset aligning real-world Assembly-C function pairs with detailed CWE annotations across multiple architectures, and (ii) the first end-to-end framework that leverages neural decompilation for binary vulnerability detection. Tuned LLM-based neural decompilers trained on our dataset achieve strong source-level recovery across architectures (Edit Similarity of approximately 56%, BLEU-4 of approximately 43%), while our tuned LLM-based detectors reach a macro F1-score of 0.61 on an in-di

---

### [227] Speculative Forking: Turning Idle Wait into Parallel Exploration for Repository Environment Setup

**链接**: https://arxiv.org/abs/2610.33129
**作者**: Yuling Shi, Mingchu Zhong, Zhensu Sun, Weihan Peng, Zhi Chen, Shilin He 等 (10 人)
**来源**: cs.SE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Before developers can use a software project, they must first get it to run. This often requires installing the right language runtime, system packages, build tools, and test commands. Recent LLM-based agents automate environment setup by inspecting a repository, writing setup scripts, running them, and repairing the resulting errors. However, these agents still follow a sequential trial-and-error loop: they try one setup route, wait for slow commands to finish, observe the failure, and only then decide what to try next. Because environment commands often take long to run, this sequential workflow makes setup slow and limits exploration to one route at a time. We present SpecBuild, an LLM-based environment setup system designed to be both faster and more successful through speculative forking. SpecBuild explores candidate setup branches in parallel, returns the first committed environment, and discards the rest. It applies this design at two granularities: strategy-level forking explor

---

### [228] Fed-Universe: A Semantic-Geometric-Topological-Human (S-G-T-H) Stack for Negotiated Alignment in Federated Systems

**链接**: https://arxiv.org/abs/2610.34009
**作者**: Ting Xu, Henry Leung
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional federated learners implicitly optimize for global means, creating a "one-size-fits-all" paradigm that inevitably suppresses the minority under cross-site heterogeneity. To bridge this critical gap, we present Fed-Universe, a generalizable Semantic-Geometric-Topological-Human (S-G-T-H) architecture that transforms passive averaging into an active negotiation for decentralized alignment. The S-layer deploys an edge-capable LLM as a semantic surrogate to translate heterogeneous inputs into standardized patient profile prompts. The G-layer enforces geometric quality assurance (GQA) via a mapping f: Theta -> Q from the statistical parameter space to a physically interpretable quality domain, employing a cosine similarity gate to retain minority updates based on physical geometry rather than statistical proximity. The T-layer executes topological Pareto control, identifying a sensitivity-based knee point (lambda_k) to balance multi-objective aggregation without majority degradat

---

### [229] Two Uncertainties Are Not One: Disagreement versus Decision-Risk in Cheap Structured Content Moderation

**链接**: https://arxiv.org/abs/2610.33258
**作者**: Karan Yadav
**来源**: cs.CL cs.CE cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Content moderation compresses a graded, contested human judgment into a binary act (leave up / take down) over billions of items, at a scale where running a frontier LLM on every post is uneconomical. A new class of frozen "System One" models returns typed, calibrated decisions instead of text at ~USD 0.000025 per call and ~100 ms. We run the first independent audit of one such model on 142,658 human-labeled comments, and benchmark it against 14 frontier reasoning models (the GPT-5.x, Claude, Gemini 3, and Grok families) on a shared probe set. Two findings stand out. First, the cheap model is accuracy-competitive: its zero-shot classification AUROC (0.83) is not statistically separable (paired bootstrap, n=56; a failure to reject parity, not proof of equivalence) from 13 of the 14 frontier systems while costing 1-3 orders of magnitude less, and it is no worse calibrated than several of them. Second, "confidence" conflates two uncertainties that come apart: human disagreement (where ann

---

### [230] FlashScript: Compiling Recurring Agent Workflows into Reusable Neuro-Symbolic Programs

**链接**: https://arxiv.org/abs/2610.33876
**作者**: Sadra Sabouri, Hosein Hasanbeig, Adam Sage, Shreya Sinha, Cale Darling, Ashish Tiwari 等 (8 人)
**来源**: cs.HC cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many agent tasks recur with new data or small changes, yet agents regenerate their reasoning and actions on each run, producing different results. Distilling a prior run into a skill helps the agent avoid earlier mistakes, but it still re-runs the full process each time, so runs can vary and incur that cost. We compile a successful agent run into a reusable neuro-symbolic program (NSP) with a set of guidelines we call FlashScript. Actions and data transformations become code, instance-specific values become parameters, and decisions that need model judgment become LLM calls. We identify three layers where these calls belong and three techniques that replace most of them with code. The compilation does not remove nondeterminism; it localizes it, so the deterministic program and its neural calls can be reviewed and tested separately. Across 120 WorkBench analytics tasks with Claude Haiku 4.5, the NSPs were correct and made identical tool calls on every run, using about 70 times fewer inp

---

### [231] Propasafe-Hybrid: A Text-Based Hybrid Propaganda Detection Tool

**链接**: https://arxiv.org/abs/2610.33464
**作者**: Thomas Kimmeth, Avijit Roy, Vivek Sharma
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Propagandistic content increasingly circulates through online news and social media, where readers often encounter it with limited scrutiny, highlighting the need for reliable and fine-grained detection. This paper introduces Propasafe-Hybrid, a sentence-level system that integrates a fine-tuned transformer classifier with LLM-based technique classification to identify, label, and explain specific propaganda strategies. The pipeline generates actionable outputs, including highlighted sentences, technique assignments, and concise rationales, so users can immediately understand why a sentence was flagged and how each label was determined. To control inference cost, Propasafe-Hybrid employs a cost-aware pre-filtering stage that forwards only high-likelihood sentences to LLMs, reducing token usage while preserving the underlying decision logic. Together, these design choices enhance the explainability, efficiency, and practical usability of sentence-level propaganda detection in real-world

---

### [232] MechAlign: Evaluating Semantic Alignment at the Project Level in Mathematical Formalization

**链接**: https://arxiv.org/abs/2610.35269
**作者**: Hao Shen, Ruichen Qiu, Lihong Zhi, Xiao-Shan Gao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lean verifies that a formal proof establishes its stated proposition under declared assumptions, but does not check whether that proposition faithfully expresses the mathematical claim in a manuscript. Assessing this correspondence requires interpreting the main theorem through its project dependencies, which may be scattered throughout a large development. We introduce MechAlign, a framework for project-level semantic alignment review that combines formal dependency extraction with LLM-based assessment. Its extraction tool, LeanTrace, constructs a statement dependency graph from elaborated declarations, retaining definition bodies and structure constraints while excluding proof bodies and stopping at an explicit library boundary. The reviewer uses this context to investigate alignment and report discrepancies with localized evidence. We conduct a preliminary review of 201 main results from 173 OpenAI Math projects, using supplied informal descriptions and available paper context. A hy

---

### [233] MatOS: An Agent Operating System for Materials Research

**链接**: https://arxiv.org/abs/2610.34203
**作者**: Dingyang Lyu, Jing Gao, Zhonghao Chang, Jingjie Huang, Xiangran Cheng, Xin He 等 (10 人)
**来源**: cs.AI cond-mat.mtrl-sci
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Materials research relies on scattered and growing data, knowledge, and simulation tools, and a single study often spans multi-day workflows across literature analysis, computation, and experiment. Large language model agents can now retrieve materials data, operate simulation codes, and close design-synthesis-characterization loops with autonomous laboratories. However, extending these agents with new capabilities, keeping long-running tasks on track, and letting them learn from past tasks and user feedback remain difficult. Here we present MatOS, an agent operating system for materials research with three core components: (1) a layered scientific asset graph that organizes data, knowledge, tools, skills, roles, and workflows as reusable assets; (2) a stateful adaptive workflow that runs tasks as explicit execution graphs with scientific checks, so that they can be resumed and traced; and (3) evidence-driven asset evolution, which revises these assets from execution records and user f

---

### [234] A Hybrid Framework for Explainable Aviation Risk: Causal Chain Extraction from Safety Reports with Physics-Based Failure Quantification and Interventional Analysis

**链接**: https://arxiv.org/abs/2610.35658
**作者**: Yutian Pang, Yifang Tian, Jiacheng Xie, Xinyu Zhao, Jueming Hu, John-Paul Clarke 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aviation authorities hold decades of accident reports whose narratives record how investigators reconstructed each accident. Computational work on these archives has mostly sorted reports into fixed taxonomies. In this work, we propose a hybrid framework in which a text-based corpus identifies the leading factors of a failure mode. Physics-based models then quantify how likely that failure is at a stated operating point. Ordered causal chains extracted from 56,202 American accident reports with a local large language model aggregate into a causation knowledge graph. On an evaluation sample of 2,000 reports, the chains recover 90.8% of investigator-flagged causes. Each physical factor whose drivers the record carries receives an occurrence model calibrated to the accident population. A leaky noisy-OR fitted to the corpus combines the factors into a failure mode probability that supports intervention. For engine power loss, the carburetor icing model separates 1,205 icing accidents from 

---

### [235] TriageRAG: Failure-Aware Self-Training for Adapting Retrieval-Augmented Language Models to Specialized Domains

**链接**: https://arxiv.org/abs/2610.33776
**作者**: Samarth Varshney, Ritu Yadav
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) lets large language models (LLMs) answer knowledge-intensive questions from retrieved evidence, but adapting a general-purpose RAG system to a specialized domain such as medicine is difficult when only an unlabeled corpus is available. Self-training approaches such as SimRAG address this by letting the LLM write its own question-answer pairs from domain passages and fine-tuning on the pairs that survive a round-trip consistency filter. We observe that these approaches treat every retained example identically: they never ask whether the student already knows the answer, already extracts it correctly from the retrieved context, or fails - and if so, whether the failure lies with the reader or with the retriever. To tackle this, we propose TriageRAG, a failure-aware self-training approach that probes the student on each self-generated question with and without retrieved context, triages it into one of four categories (known, solved, context-failure, re

---

### [236] MATCHA: A Chinese Multi-Disorder Mental Health Dataset with Cross-Lingual Analyses on Social Media

**链接**: https://arxiv.org/abs/2610.35512
**作者**: Bingrui Jin, Baihan Li, Zitong Li, Kunyao Lan, Shimeng Li, Kenny Q. Zhu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mental health research on social media has been dominated by English-language datasets and DSM-5-centered resources, limiting cross-lingual and cross-cultural understanding of online mental health expression. We introduce MATCHA, the first Chinese multi-disorder mental health dataset that links disorder-specific Weibo Super-Topic communities with users' broader public timelines. MATCHA covers seven DSM-5 disorders and a control group, comprising 46,025 cohort-level users and 1.8 million posts. The dataset distinguishes users with explicit self-disclosure evidence from broader disorder-related participants through an LLM-assisted annotation pipeline, and is released in a rigorously de-identified, controlled-access format. Using MATCHA, we analyze behavioral, linguistic, symptom-related, and life-event-related patterns across disorders, and conduct cross-lingual comparisons with Twitter-STMHD. Our analyses show that Weibo Super-Topics function as concentrated spaces for affective and hea

---

### [237] "High-Quality" Data for Early-Stage Instruction Tuning: An Empirical Study of Data Quality Metrics

**链接**: https://arxiv.org/abs/2610.33969
**作者**: Vladimir Necula, David Gvadzabia, Sofia Serrano
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> "Data quality" is widely invoked in instruction tuning, but the term is often underspecified. We study it as an operational property by asking which simple example-level metrics, drawn from prior work on data selection, text quality, and instruction tuning, best predict training utility under a fixed finetuning budget. For each metric, we sort instruction-response examples by score, partition them into low, middle, and high bins with roughly equal token mass, finetune separately on each bin, and compare validation perplexity and LLM-as-judge scores for the models' generated answers as a function of cumulative training tokens. Our results suggest that answer-dense supervision, as captured by response ratio, is a stronger and more portable predictor of instruction-tuning utility than commonly used alternative proxies.

---

### [238] The Hidden Costs of Forgetting: A Study of Trajectory Deletion in Software Engineering Agents

**链接**: https://arxiv.org/abs/2610.35496
**作者**: Fernando Vallecillos-Ruiz, Islem Bouzenia, Michael Pradel, Leon Moonen
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Software engineering agents resend their entire trajectory to an LLM at every turn, motivating online trajectory reduction. Prior work shows that randomly deleting 75% of tokens in old turns may preserve agent effectiveness, but it remains unclear why, how agents compensate for missing content, and whether it actually reduces costs. This paper presents an empirical study of 42 trajectory-reduction configurations, focusing on effectiveness, agent behavior, and cost. We systematically explore deleting content from old turns by varying the scope, granularity, amount, and timing of deletion across 9,400 runs with two state-of-the-art agents on SWE-bench Verified. We find deleting large amounts of trajectory content (e.g., up to 100% of reasoning text) can preserve overall effectiveness. Importantly, such deletion must be applied with a delay, as immediate deletion tends to significantly degrade effectiveness. Agents often compensate for deleted content by re-fetching it, increasing both th

---

### [239] R2A-Sales: A Policy-Atom-Matched Benchmark for Rule-to-Action Gaps in Goal-Directed Sales Agents

**链接**: https://arxiv.org/abs/2610.34185
**作者**: Yihua Qin (1 and 2), Jiajie Jerry Zhao (1 and 2) ((1) Tsinghua University, (2) Futura Lab, Futura.AI)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based sales agents are often evaluated on static policy questions or task success, but deployment asks a sharper question: when a model can state a rule, will it choose compliant, tool-grounded actions under commercial pressure? We introduce R2A-Sales (Rule-to-Action), a policy-atom-matched benchmark for this question. Each item pairs a static probe with a multi-turn sales scenario sharing the same versioned policy atom, facts, evidence, behavioral constraints, and tool contract, so differences cannot be attributed to policy-content mismatch. In the interactive arm, a code-owned ledger verifies committed tool effects and terminal states; unsupported action claims receive no credit. We report static compliance $K$, grounded action compliance $A=\Pr(\text{safe terminal}\land\text{no hard violation}\land\text{non-echo})$, and the matched gap $G=K-A$. The frozen release spans three controlled Chinese-language sales domains, 24 policy atoms, 42 semantic cores, and 2,016 matched pairs. T

---

### [240] Audit Where Hacks Pay: Budgeted Strong-Verifier Audits Against Reward Hacking in GRPO

**链接**: https://arxiv.org/abs/2610.35716
**作者**: Shurun Li, Michael Hua Wang, Haibo Zeng, Long Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards trains on cheap checks, such as unit tests, that a policy can learn to game, while a stronger check is too expensive to run on every rollout. We study how to spend a limited strong-verifier budget in GRPO, separating which weakly passing rollouts to audit from what reward a caught hack receives. At a fixed policy state with centered advantages, the expected update depends on a design only through each rollout's marginal audit probability and correction; reflecting a caught hack's reward about the failure reward negates the advantages of an all-hack group; and auditing whole groups with the fewest weak passes first (low-pass budgeted audits, LB) minimizes the advantage mass left on hacks among pass-count designs with a fixed correction when a label's value falls with the pass count. We tested this analysis in actual LLM training: from each run's starting state, the sign of this mass on a frozen panel predicted whether hacking would be suppr

---

### [241] When Does Pre-Trained Capacity Help Causal Learning? From Scalar Prediction to Counterfactual Post-Training

**链接**: https://arxiv.org/abs/2610.33311
**作者**: Qi Xu, Zijie Lei, Zhifei Deng, Zhigang Hua, Luke Simon
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How does pre-trained model capacity relate to performance after adaptation for causal tasks? We study two systems built on the Qwen 2.5 family: CausalLLM, which estimates scalar potential outcomes with treatment-specific heads, and CausalGen, which generates treatment-conditioned text or code using soft prefixes and factual supervised fine-tuning (SFT), counterfactual SFT, and preference alignment. Increasing backbone size from 0.5B to 1.5B yields mixed scalar-estimation results on IHDP, but improves CodeGen pass@1 from 0.267 to 0.575 and treatment-effect score from 0.231 to 0.515 after the complete generative pipeline. Within 0.5B CausalLLM, narrative inputs reduce mean sqrt(PEHE) from 1.842 to 1.780, a 3.4% improvement over tabular inputs; the 5.8% improvement over a no-LLM baseline combines changes in representation and input format. These descriptive comparisons motivate a distinction between available and convertible capacity. They do not isolate the contribution of post-training:

---

### [242] Proof-of-Agentness: Towards Verifying Agents on the Web

**链接**: https://arxiv.org/abs/2610.35288
**作者**: Zuyao Xu, Xiang Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> CAPTCHAs and bot detection have helped protect Web services from automated abuse for decades by distinguishing humans from bots. However, the emergence of LLM-powered agents introduces a new setting: Web services increasingly accommodate agents as legitimate users. Without a way to distinguish agents from other automated clients such as simple bots and scripts, these services risk large-scale automated junk submissions that waste service resources and consume users' attention or tokens. In this paper, we investigate a novel question for today's Web: "How can a Web service obtain evidence that a client is an agent?" We introduce the concept of "Proof-of-Agentness" (PoA), a mechanism for distinguishing agents from other automated clients, motivated by the parallel between human attention and an agent's inference resources. We outline two approaches: active verification through challenge-response and passive analysis of service-visible signals. Eight language models achieve an overall acc

---

### [243] RAGing Against Misogyny: Improving Implicit Misogyny Explanations

**链接**: https://arxiv.org/abs/2610.35094
**作者**: Ivana Crescenzi, Arianna Muti, Maarten Sap, Tommaso Caselli, Debora Nozza
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Implicit misogyny often requires background knowledge to be understood. To address this challenge, we propose a Retrieval-Augmented Generation (RAG) framework for detecting and explaining implicit misogyny in English and Italian, leveraging encyclopedic, slang and feminist knowledge sources. Using the ImplicIT-Mis and SBIC+ datasets, we evaluate the contribution of each knowledge source to detection and explanation quality, investigating also whether RAG addresses known LLM failure modes in implicit misogyny. Results show that RAG improves recall on ImplicIT-Mis, but does not improve detection performance on SBIC+. However, human evaluation shows that RAG-based explanations are preferred over no-RAG explanations in both languages. Feminist literature emerges as the most consistently useful source for detection and explanation.

---

### [244] Intent-Preserving Adversarial User Simulation for Multi-Turn Agent Evaluation

**链接**: https://arxiv.org/abs/2610.35426
**作者**: Atri Vivek Sharma and Brian Formento and Alessio Lomuscio
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn agents are commonly evaluated with LLM-based simulated users, which can be overly cooperative and can therefore overestimate an agent's performance. We here introduce StressSim, an intent-preserving adversarial user simulator framework for stress-testing agents with challenging yet valid user interactions. StressSim optimises the simulator's high-level adversarial plan for each task instance. Candidate planner prompts are evolved with a genetic prompt-optimisation loop that uses rollout traces, granular task-completion signals, and validity feedback to favour conversations that reduce task success without changing the user's underlying goal. We evaluate the approach on the MultiWOZ dataset and the retail and airline domains from tau-bench with three target LLM agents, comparing against standard simulators and hand-designed non-collaborative user behaviours. We demonstrate the effectiveness of StressSim in exposing robustness gaps across frontier LLMs, with tau-bench pass^4 s

---

### [245] Rescuing Your Pruning: Rethinking Visual Token Pruning and Post-Training Recovery in MLLMs

**链接**: https://arxiv.org/abs/2610.33688
**作者**: Peiran Yin, Hao Wu, Zihao Yang, Haozhe Hu, Xudong Wang, Xiaoyu Shen
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual token pruning substantially reduces the inference cost of multimodal large language models (MLLMs), yet existing methods are mostly training-free and plug-and-play. They treat the resulting performance drop as an inevitable cost of compression and pursue increasingly complex pruning rules. We rethink this view through two questions: how much of the loss can post-training rescue, and, building on this recovery, how can joint compression push pruning to its limit? We curate a 282K-sample post-training mixture covering general VQA, reasoning, OCR, and grounding, and post-train 36 configurations that drop or merge tokens under a unified protocol. Post-training rescues most of the loss, even for OCR and grounding, and its adaptation gain in closing the gap between the pruned and the dense model grows as the budget tightens. For joint compression, we find that the vision encoder, not the LLM, dominates prefill time in native-resolution MLLMs, so where tokens are removed matters more t

---

### [246] Toward Fast Human Reaction Modeling from High-Frequency Digital Interaction Data

**链接**: https://arxiv.org/abs/2610.35079
**作者**: Emanuel Dopater, Daniel Gavlas, Luk\'a\v{s} Jochymek, Kannan Paul, Miloslav Szczypka, David Voj\'a\v{c}ek 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate whether limbic-like signatures of rapid, salience-driven behavior can be identified in high-resolution Counter-Strike 2 telemetry. This exploratory study introduces Ego-Knowledge, a leak-reduced reconstruction of each player's plausible perceptual state, supported by a millisecond-precision visibility engine and a reaction-centered extraction pipeline. Using a neuroscience-motivated 60--120 ms window, we derive coarse fight-or-flight labels from visibility- and damage-triggered events, with back-damage cases enabling constrained reaction-time analysis and manual label checks. We train two telemetry-native models using only information available by the trigger: EMBER (gradient boosting) and ORBIT (a custom transformer). On the full validation set, EMBER achieves 73.5% accuracy and ORBIT 71.2%, versus a 51.5% majority-class baseline, and both generalize to held-out players. The strongest LLM baseline achieves 62.7% on 1,000 validation cases; on these same cases, EMBER (73.

---

### [247] AIPC: Evidence-Guided Agent Workflows for PyTorch Project Deployment

**链接**: https://arxiv.org/abs/2610.34890
**作者**: Zhanwei Wu (1), Jianhao Su (1), Brian Zhang (1), ShengTing Huang (1), Weidong Feng (1), Gang Liu (1) 等 (10 人)
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying and optimizing a PyTorch inference project on a dedicated accelerator, especially an on-device NPU, requires more than using a framework device API as with CUDA. The project must be converted into hardware-runtime artifacts and adapted to the target toolchain and application interface. Differences in model formats, quantization flows, operator support, and toolchain interfaces create cross-layer problems spanning PyTorch/ONNX models, toolchains, runtimes, and device execution. LLM Agents can invoke tools to address such problems, but may drift because of insufficient domain knowledge, large configuration and repair spaces, or poor path selection. We propose AIPC (AI Porting & Conversion), an Agent method for deploying PyTorch inference projects. AIPC combines structured Skills with toolchain, runtime, and profiling evidence to drive cross-layer diagnosis and repair, organizing model adaptation, artifact building, on-target execution, accuracy repair, and performance optimizat

---

### [248] AT-AT: Automatic Tool Optimization from Agent Traces

**链接**: https://arxiv.org/abs/2610.34679
**作者**: Maya Ravichandran, Pragya Tripathi, Dharamendra Kumar, Adith Swaminathan, Nathan Kallus
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efforts to improve LLM-based agents typically focus on modifying the agent itself, yet success also depends on the environment in which an agent acts. Tools mediate this interaction: a tool's description shapes how an agent calls it, and its implementation determines the results and errors the agent receives afterwards. Many tools, such as APIs and MCP servers, are shared by many agents and maintained by providers who cannot change those agents. We introduce AT-AT (Automatic Tool Optimization from Agent Traces), an agentic tool optimizer that improves a shared toolset offline from historical agent executions while holding the agents fixed. A lightweight coding agent reads agent trajectories and their evaluation results, and selectively edits tool descriptions and, when permitted, implementations. On $\tau^2$-bench-verified, AT-AT achieves the highest task completion rates in the Airline and Telecom domains at lower cost than strong prompt- and tool-optimizer baselines, and its Telecom 

---

### [249] Neyman Orthogonal Activation Steering

**链接**: https://arxiv.org/abs/2610.33217
**作者**: David Arbour, Erfan Jahanparast, Serina Chang, Avi Feller
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering is a popular approach for shifting LLM output toward a desired behavior, and increasingly for generating realistic synthetic data. The standard recipe estimates a steering direction by contrasting LLM activations on prompts with and without a target concept, such as truthfulness. In this paper, we separate the estimand (the steering direction these methods target) from the estimator used to recover it, two notions the literature often conflates. We frame nearly all existing methods as plug-in estimators of the average gradient of an outcome regression, with the binary contrastive label fixed as the outcome. Using this framing, we can immediately incorporate flexible modeling approaches and extend existing methods to allow for continuous outcomes such as log-probabilities or oracle ratings. Flexible ML models that fit the outcome well, however, might not estimate the gradient well, which motivates estimators that target the gradient directly. Drawing on the debiased 

---

### [250] Beyond Visual Neglect: Context-Preference Activation Steering for Mitigating MLLM Hallucinations

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1156.pdf&hl=zh-CN&sa=X&d=4504149378771449951&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv6uL4f4fRC0rkWUv1OryuPa&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=4&folt=kw-top
**作者**: J Wu, X Zhang, G Song - Findings of the Association for Computational …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> MLLM hallucinations while avoiding the repetitive degeneration of some decoding-based intervention methods. We further find that different MLLM … For each sample, we let the MLLM autoregressively generate the answer, locate the earliest occurrence of y+

---

### [251] TerraVis: Towards Evaluation of World-Grounded Visual Consistency in Text-to-Image Generation via MLLM Workflows

**链接**: https://arxiv.org/abs/2610.02959
**作者**: Shuai Fu, Jing Gu, Jian Zhou, Zicheng Duan, Gengze Zhou, and Qi Wu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [252] Perceive, Localize, Reflect: Evidence-Anchored Multi-Agent Debate for MLLM Hallucination Mitigation

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.1597.pdf&hl=zh-CN&sa=X&d=15617108463998306459&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv6YU6JDF2_-fYK1jT4FkBv7&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=0&folt=kw-top
**作者**: Y Wu, H Jin, WYB Lim, L Li - Proceedings of the 2026 Conference on Empirical …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multimodal Large Language Models (MLLMs) demonstrate remarkable reasoning capabilities, yet they remain susceptible to hallucinations. While Multi-Agent Debate (MAD) presents a promising collaborative solution, unguided debates inevitably devolve

---

### [253] InteractiveWorld: A Verifiable Human-Centric Environment for Building Better Interactive MLLM Assistants

**链接**: https://arxiv.org/abs/2610.33966
**作者**: Qinsi Wang, Wei Wen, Chong Zhou, Saksham Suri, Zechun Liu, Lemeng Wu 等 (10 人)
**来源**: cs.HC cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People have long dreamed of an assistant that is always there to guide them and remind what they forget, from new dishes to lost keys. Powered by multimodal large language models (MLLMs), egocentric AI assistants on wearable devices are bringing this dream within reach: they see what the user sees and give instructions for user's physical work when necessary. However, testing such assistance is challenging and usually requires real people. The expensive and rare real interaction data leaves a key question unanswered: Can today's MLLMs truly help people in physical world? To answer this question, we propose InteractiveWorld, the first verifiable environment for closed-loop interaction between human and AI assistant. Unlike existing robot-centric simulators, InteractiveWorld lets the assistant guide a human agent who observes the scene, understands instructions, and acts independently. It thus realistically simulates how AI assistant collaborates with human: the assistant instructs, the 

---

### [254] CMIE: Cross-Modal Interaction Erasure for MLLM Safety Unlearning via Counterfactual Localization and Subspace Nullification

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.2220.pdf&hl=zh-CN&sa=X&d=17806311564224779886&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv5vPcCbyz95suvM8jFlz69v&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=1&folt=kw-top
**作者**: J Cao, L Cai, M Wang, J Liu, J Ji, Y Du 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> A useful MLLM must still recognize risky visual evidence and answer benign educational or preventive questions about the same content. The safety… We evaluate two MLLM backbones with SafeEraser editing data and zero-shot VLGuard/MSSBench

---

### [255] MulFCoder: Framework-conditioned Multi-agent for MLLM-based Multi-framework Front-end Code Generation

**链接**: https://arxiv.org/abs/2610.34418
**作者**: Jie Wu, Haoran Ma, Shisong Tang, Yulin Xu, Xiaoyu Kang, Jiechao Gao
**来源**: cs.SE cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating runnable front-end code from UI screenshots is a long-standing goal in automated software engineering. Existing MLLM-based methods predominantly focused on HTML/CSS, leaving multi-framework generation for React/Vue/Angular underexplored. Naively modifying prompts leads to substantial performance gaps across multi-framework and highly framework-specific error modes. To address this, we propose MulFCoder, a framework-conditioned multi-agent method that explicitly encodes framework constraints to bring multi-framework differences into a decidable rule space. MulFCoder orchestrates four agents: Grounder constructs an ElementTable, ContentTable, and macro-layout regions from detected UI elements; Planner builds a DOM-like hierarchical layout tree, produces a task schedule, and derives a framework-specific file Contract; Writer generates structured file writes or patches within a restricted edit window; Judger enforces lightweight, framework-conditioned constraints to accept or re

---

### [256] Silence over Error: Risk-Averse Navigation Landmark Extraction via Progressive MLLM Alignment

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1478.pdf&hl=zh-CN&sa=X&d=915409314287135652&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv77Dbm17kUBrd6XZPSe74ng&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=2&folt=kw-top
**作者**: X Yang, Z Cao, C Shao, J Lin, F Zeng, Y Liu - Findings of the Association for … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Existing pedestrian navigation systems often provide direction-only instructions with limited visual confirmation at complex intersections or along long straight paths. We study coordinate-free landmark extraction from dashcam image sequences. The

---

### [257] PathKGen: Pathology Knowledge Assisted MLLM for Explainable Histopathology

**链接**: https://arxiv.org/abs/2610.33691
**作者**: Nadun Rajapaksha, Sandun Herath, Devnith Wijesinghe, Isiri Amani Withanawasam, Hasindri Watawana, Ranga Rodrigo
**来源**: cs.CV cs.CL
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whole Slide Image (WSI) analysis serves as the fundamental method for the clinical diagnosis of cancer in digital histopathology. Recent advances in Multimodal Large Language Models (MLLMs) have enabled state-of-the-art (SOTA) automated histopathology report generation. However, MLLMs reason purely through distributions encoded in their neural parameters, limiting the amount of knowledge and reasoning logic they can contain given the model scale. Their black-box reasoning poses another challenge to the human interpretation of intermediate reasoning. We address these issues by utilizing knowledge graphs to inject external structured knowledge for MLLMs to reason over, while making this reasoning component visible. Knowledge graphs are capable of partially externalizing the containment of medical knowledge, an area that remains underexplored in pathology report generation. We introduce PathKGen, a knowledge graph-assisted MLLM for histopathology report generation. PathKGen has two main b

---

### [258] MAViQ: Memory-Augmented Visual Querying for Multi-Turn MLLM Jailbreaks

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.emnlp-main.1097.pdf&hl=zh-CN&sa=X&d=14918788592632424727&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv7cBej4OrRLocDNrQVkIYH1&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=3&folt=kw-top
**作者**: JY Lu, X Li, G Zhou, C Chen, YF Chen - Proceedings of the 2026 Conference on …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Prior multimodal attacks show that visual inputs can weaken MLLM safeguards. Some meth… At turn t, the attacker has an accumulated trace, while the target MLLM receives only the target-… Let g be the attack goal and Mtar the target MLLM . Each

---

### [259] HarmEvoSkill: Skill-Memory Self-Evolution for Zero-shot Multimodal Harmful Meme Detection

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.195.pdf&hl=zh-CN&sa=X&d=3519238574562610511&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv4g6ski0k5qwPYlZ5EQl8pp&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=9&folt=kw-top
**作者**: J Zhou, W Lu - Findings of the Association for Computational …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The first setting measures the raw reasoning ability of an MLLM without external reference memes, whereas our setting uses an unlabeled reference split but no gold labels, supervised task training or task-specific parameter updates. Inspired by

---

### [260] Aerial-R1: Reinforcing Aerial Reasoning and Segmentation in MLLMs

**链接**: https://arxiv.org/abs/2610.33056
**作者**: Jisheng Dang, Huaiyuan Peng, Yixuan Wang, Kun Wang, Zhang Li, Tat-Seng Chua
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Multimodal Large Language Models (MLLMs) have revolutionized general visual perception, existing methods suffer from severe hallucination in the aerial domain, where extreme scale variations and visual ambiguity abound. Existing Supervised Fine-Tuning (SFT) paradigms force models to mimic ground truth without modeling uncertainty, often resulting in blind guessing on tiny or unrecognizable objects in aerial scenes. In this paper, we present Aerial-R1, the first aerial MLLM framework to reinforce visual reasoning capabilities for aerial reasoning and segmentation. Drawing inspiration from the reasoning-incentivizing mechanisms of DeepSeek-R1, we find that trustworthy perception stems from consistency across views, establishing a visual parallel to the Chain-of-Thought in logic. To effectively adapt policy optimization for non-autoregressive mask generation, we introduce Hybrid-View Group Advantage-Weighted Regression (H-GAWR). This strategy constructs dynamic groups of high-resolu

---

### [261] GeoLift: Grounding Video Spatial Reasoning in Explicit 3D Maps

**链接**: https://arxiv.org/abs/2610.33558
**作者**: Xinglin Li, TingTing Long, Jingzhi Zhou, Jiajing Chen, Jian Yang, Jin Xie
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video spatial reasoning requires multimodal large language models (MLLMs) to understand how objects are arranged and related across viewpoints. While these models can recognize objects in individual frames, integrating these observations to solve complex spatial tasks remains challenging. We examine route planning as a representative task and observe that existing models become substantially less accurate as the number of required turns increases, with several models achieving accuracy close to random guessing on routes requiring three or more turns. This finding suggests that recognizing landmarks alone is insufficient: models must also connect observations across viewpoints and track how landmarks are arranged in a shared space. Motivated by this observation, we introduce GeoLift, a training-free framework that uses feed-forward 3D reconstruction to map objects detected in individual frames into a shared metric 3D scene. GeoLift combines a frozen MLLM for 2D grounding with pretrained

---

### [262] FORGE: Forensic Reasoning with Grounded Evidence

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.2054/&hl=zh-CN&sa=X&d=6719244030790381206&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv5ZVk9C0U85wQO9QxPXvG7A&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=8&folt=kw-top
**作者**: R Kundu, S Jia, V Mohanty, A Balachandran… - Findings of the Association …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We argue this is an inductive bias problem rather than a capacity issue: the image-text contrastive objective training MLLM visual encoders … The MLLM ’s native encoder and the VOM operate on a shared patch grid, which lets us interleave their tokens

---

### [263] From Presence Labels to Bounding Boxes: Can Multimodal Large Language Models Scale Surgical Instrument Localization?

**链接**: https://arxiv.org/abs/2610.34218
**作者**: Mohamed Hamdy, Muraam Abdel-Ghani, Fatmaelzahraa Ahmed, Sifna Nasar, Mariam Ahmed, Khalid Al-Jalham 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial localization of surgical instruments through bounding-box annotations is a foundational component of surgical scene understanding, supporting detection, tracking, interaction analysis, and grounded vision-language applications. Yet existing annotations often cover selected frames, video subsets, or dataset variants rather than complete procedures. Manual extension is time-consuming and expert-dependent. Additionally, weakly supervised and detector-based pseudo-labels require task-specific training and may be imprecise. In this study, we design a scalable MLLM-based annotation framework that converts surgical frames and existing instrument-presence labels into accurate bounding boxes, and systematically analyze its reliability, cost, and design sensitivity. We instantiate the framework using six MLLMs and a multi-call configuration on laparoscopic cholecystectomy in Cholec80. Using a carefully designed stratification scheme, two annotators independently label 1,000 frames, and a

---

### [264] Bridging Reasoning and Retrieval: A Large-Small Model Collaboration Framework for Multimodal Entity Alignment

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.202.pdf&hl=zh-CN&sa=X&d=10405206486675553636&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv4_alNKQExGOOce357GFrxo&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=7&folt=kw-top
**作者**: X Jin, J Lin, T Mei, T Zhu, C Huang, J Chen 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We propose CRMEA, a largesmall collaborative framework for unsupervised MMEA that unifies PTM-based retrieval and MLLM based reasoning through a closed-loop optimization process. CRMEA introduces a text-centric adaptive cross-modal

---

### [265] SaToMe: Salience-Driven Token Merging for Omni-Capable Diffusion MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1954/&hl=zh-CN&sa=X&d=11472604360765373193&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv5ji8HYYiX5mSrVKv5qeEp5&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=5&folt=kw-top
**作者**: S Liu, P Guo, J Zhang, T Chen, X Zhang - Findings of the Association for …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Token merging has been studied separately in adjacent fields, yet training-free acceleration spanning T2I+I2T in one omni-capable Diffusion MLLM … The same I2T form transfers directly to a separate I2T-only Diffusion MLLM with a different

---

### [266] Transferring Math Reasoning Abilities from LLMs to MLLMs via Causal-Aware Model Merging

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1943.pdf&hl=zh-CN&sa=X&d=9445375798368771950&ei=Skzgase2DMimieoP4sreqQc&scisig=AIL1Nv4iCvFU3ySMSdNqWGM6VqWd&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=6&folt=kw-top
**作者**: Y Hu, G Yang, Z Zhou, B Dong, X Huang, K Huang… - Findings of the Association … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> With these deltas, we can derive our math-reasoning MLLM W∗ by selectively merging the math-specific deltas into the MLLM . A general … as ∆W select MLLM ,∆W select Math ∈ Rm×n, and the remaining unmodified MLLM parameters as ∆Wretain

---

### [267] NOMAD-EEG: Native Omni-Montage Adaptive Diffusion

**链接**: https://arxiv.org/abs/2610.35246
**作者**: Abdulkader Helwan, Khadidja Henni and Lina Abou-Abbas
**来源**: cs.LG eess.SP
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose. Electroencephalography (EEG) montages, channel counts and recording lengths vary widely, but most EEG foundation models are bound to the channel set and input length they were trained on. We aimed to build a generative EEG foundation model independent of the number, identity and order of electrodes and of the input length. Methods. NOMAD-EEG is a 12.0 M-parameter diffusion model that alternates state-space layers along time, without patches, with attention across electrodes identified only by their 3D scalp position. It was pre-trained on 147 h of unlabelled EEG from a single corpus and evaluated with frozen linear probes on ten datasets with 1 to 64 electrodes against seven foundation models run under one protocol, and on two unseen populations. Results. Despite its small size (12.0 M parameters against 69 M for REVE) and single pre- training corpus, NOMAD-EEG outperformed all seven foundation models on EEGMMIDB mo- tor imagery (balanced accuracy 0.442), Siena seizure detecti

---

### [268] Decoding motor imagery EEG signals by a deep learning network integrating multiscale filtering and temporal-channel attention mechanisms

**链接**: https://scholar.google.com/scholar_url?url=https://journals.plos.org/plosone/article%3Fid%3D10.1371/journal.pone.0361026&hl=zh-CN&sa=X&d=10683245611378939123&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv7stvGQ12ndLl6YPj_1n8CP&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=7&folt=kw-top
**作者**: Y Zhu, Y Shi, J Wu, Q Wei - PloS one, 2026
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> encephalogram ( EEG ) has the advantages of noninvasiveness, cost efficiency and high time resolution, EEG -based … EEG -Conformer network to capture long-term dependencies in MI- EEG signals, encapsulating both local and global features

---

### [269] From cognitive process to safety trait: An EEG -driven machine learning framework for predicting risk perception ability

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S002243752600191X&hl=zh-CN&sa=X&d=8276265706308572677&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv7fPu-uilwUZUswp2btT7Lr&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=1&folt=kw-top
**作者**: Z Zhao, S Zhang, X Shi - Journal of Safety Research, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Introduction : Biased risk judgment can contribute to unsafe decisions in construction, yet risk perception ability (RPA) is usually assessed using self-report or behavioral measures that offer limited access to underlying neurocognitive processes. Method

---

### [270] ProtoEEG: Structured Prototype Alignment for EEG Visual Decoding

**链接**: https://arxiv.org/abs/2610.33065
**作者**: Kieren Yu, Chang Huang, Ziyang Liu, Kaishun Wu
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG visual decoding remains difficult because scalp recordings are noisy, spatially coarse, and variable across trials and subjects. Most systems align each trial with a dense image embedding, although that embedding mixes semantic content with instance-specific texture, pose, and background. This target can demand details absent from EEG and provides no explicit account of the visual factors supporting a prediction. We propose \textbf{ProtoEEG}, a prototype-mediated framework that reformulates EEG--image alignment as soft composition over a shared learnable visual codebook. A trainable EEG encoder and a frozen visual teacher produce assignment distributions over the same $K=64$ prototypes. Their weighted reconstructions form a structured representation for retrieval and image generation. Prototype contrast supplies the main cross-modal training signal, distribution alignment coordinates codebook use across modalities, an instance anchor preserves fine-grained discrimination, and diver

---

### [271] Latent-Level Uncertainty Resolution for Stable EEG -to-Text Decoding under Cross-Subject Variability

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.findings-emnlp.1350.pdf&hl=zh-CN&sa=X&d=18374309956477081774&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv5nVYjgksqgz_TYEK10fctN&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=8&folt=kw-top
**作者**: S Park, J Lee, Y So, BH Kim - Findings of the Association for Computational …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Autoregressive generators often rely on fixed conditioning representations, so uncertainty in noisy inputs can be amplified during rollout under distribution shift. We address this by resolving uncertainty in latent space before decoding: Latent-Level

---

### [272] EEG-VID: Task-Guided Latent Predictive Pretraining for EEG Decoding and Assistive Target Selection

**链接**: https://arxiv.org/abs/2609.00566
**作者**: Guanzhong Sun, Junyi Ma, Yuxuan Wu, Wei Tang, and Yanzi Miao
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [273] Compact relative-ordering models for interpretable EEG -based dementia classification

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426022330&hl=zh-CN&sa=X&d=13120661207763031630&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv5lEnBoPXgwrIbWffCfjSrO&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=4&folt=kw-top
**作者**: M Czajkowski, J Fernandez, B López - Biomedical Signal Processing and Control, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ordering methods for EEG -based dementia classification. Specifically, we evaluate whether a small number of learned pairwise EEG feature … Second, we analyse how model behaviour depends on EEG feature representation and

---

### [274] DINO- EEG : Montage-Robust Event-Level Seizure Detection in Scalp EEG

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11745848/&hl=zh-CN&sa=X&d=1362813102051366398&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv7Gn4XIp0FG6ZyUke17_0tz&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=2&folt=kw-top
**作者**: X Fan, Y Li, B Li, P Ganzhang, G Pei, Q Zhao… - IEEE Journal of Biomedical … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract— Manual review of long-term clinical electroencephalography ( EEG ) remains a major bottleneck for largescale seizure screening … We present DINO EEG , a channel-wise framework for event-level seizure detection in scalp EEG . The

---

### [275] A novel AF-CBA framework for accurate and interpretable EEG cognitive state classification

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s00521-026-12602-1&hl=zh-CN&sa=X&d=8020652209589810082&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv4PuSsYGSswTEncDW4WT51M&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=3&folt=kw-top
**作者**: B Mandal, S Mohapatra, R Sahoo - Neural Computing and Applications, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Accurate and interpretable classification of cognitive states from electroencephalography ( EEG ) signals represents an important area of research in cognitive neuroscience, adaptive learning systems, and intelligent human–machine

---

### [276] EEG -Based Classification of Human Motor Intention Using a Hybrid EEGNet–Transformer Model

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11745547.pdf&hl=zh-CN&sa=X&d=8666974211431806406&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv6SHWvks5mIPoMMpsgLVY4n&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=9&folt=kw-top
**作者**: N Zendehdel, H Chen, MC Leu - IEEE Access, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study employed the publicly available WAY- EEG -GAL dataset [25], comprising EEG recordings from twelve healthy participants performing a standardized grasp-and-lift task. EEG signals were recorded at 500 Hz using a 32-channel

---

### [277] Diagnostic and mechanistic insights from molecular profiling of explanted stereo- EEG depth electrodes

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0959437X26001152&hl=zh-CN&sa=X&d=9644879548854118226&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv7IiAfcFSaFZ19552s_TZKB&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=0&folt=kw-top
**作者**: J Larkin, P Widdess-Walsh, VK Tiwari, DC Henshall - Current Opinion in Genetics & …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Epilepsy surgery involving deep brain stereo- electroencephalography (SEEG) offers a unique window into the biology of epilepsy in living humans. Explanted SEEG electrodes retain nucleic acids, enabling identification of somatic variants underlying

---

### [278] EEGBiFormer: Real-Time EEG Attention Classification via Hybrid CNN-Transformer with EEG-Informed Auditory Protocol Validation

**链接**: https://arxiv.org/abs/2610.33832
**作者**: Isabella Guan
**来源**: cs.LG cs.AI cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sustained attention is critical for academic performance, yet existing auditory support tools are static and not grounded in real-time neural evidence. This paper presents EEGBiFormer, a hybrid CNN-Transformer model for realtime binary classification of attention states, focus versus nonfocus, from 16-channel EEG signals. A custom analog front-end acquisition board was designed and built to collect a task-based EEG dataset. Before model training, spectral and connectivity analysis, using Power Spectral Density and Phase Locking Value, confirmed distinct neural signatures between attention states, providing physiological grounding for the classification approach. EEGBiFormer achieved 91.3 percent window-level validation accuracy with an F1 score of 94.5 percent, and 88.2 percent recording-level accuracy across 17 independent sessions. End-to-end system latency was measured below 100 ms, supporting real-time responsiveness. The trained model was further used to objectively rank auditory 

---

### [279] EEG Emotion Recognition Based on Azimuthal Equidistant Projection and a Multiscale Residual Temporal Network

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3425/16/11/1150/pdf&hl=zh-CN&sa=X&d=877586259114962144&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv4u9Pw3zbu-9NTf3FY6aGXq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=6&folt=kw-top
**作者**: X Lian, R Liang, C Gao, P Wang, W Guan - Brain Sciences, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background: In most existing EEG -based emotion recognition studies, the spatial configuration of electroencephalography ( EEG ) electrodes … To address these limitations, an EEG emotion recognition framework integrating azimuthal equidistant

---

### [280] EEGaze: Multimodal Attention Prediction in Visual Search via EEG-Based Saliency Refinement

**链接**: https://arxiv.org/abs/2610.35757
**作者**: Mansi Sharma, Dinar Orazgaliyev, Antonio Kr\"uger, Philipp M\"uller
**来源**: cs.HC cs.AI cs.MM
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual search is ubiquitous in daily life, from locating keys in a messy apartment to finding a tool in a cluttered workshop or an application icon on a desktop screen. While visual attention is to a large extent driven by image content, research in psychology indicates that user cognitive states have a significant influence on attention allocation. A promising way to access information about cognitive states is via Electroencephalography (EEG) recordings. Despite this potential, previous works in computational attention modeling have largely disregarded EEG, and related studies in psychology operate with abstract, simplistic stimuli, or even artificially guided search procedures. We bridge this gap with two contributions. First, we present EEGaze 140, the largest publicly available multimodal dataset of free visual search with realistic stimuli. The dataset contains synchronized EEG and eye tracking recordings from 36 participants across 140 naturalistic scenes, covering two scenarios

---

### [281] Domain-Tailored Attention Transformer for EEG -Based Person Identification

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11749541/&hl=zh-CN&sa=X&d=2442685547701688978&ei=SUzgaoiqO8imieoP4sreqQc&scisig=AIL1Nv67oHdplZGXI-tXrkGXeMdd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=5&folt=kw-top
**作者**: J Lu, Z Wang, T Li, X Liu, D Li, B Wang - IEEE Journal of Biomedical and Health … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Accurate person identification (PI) based on electroencephalogram ( EEG ) provides high security value. However, existing EEG -based PI methods still struggle to fully mine individual-specific features within each do main and to effectively jointly model

---

### [282] Beyond Modeling Order: Dual-Path Spatiotemporal Representation Learning for Cross-Subject EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2610.35540
**作者**: Zehui Xiao, Yi Zheng, Guixing Fu, Wenkai Lu, Lingfei He, Tao Tan 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-subject generalization remains a major challenge for EEG-based emotion recognition due to pronounced inter-subject variability in neural activity and emotion-related spatiotemporal patterns. Existing methods mainly alleviate inter subject differences through distribution alignment or contrastive learning, while paying limited attention to representation bias associated with fixed spatiotemporal modeling orders. We hypothesize that high-level emotion representations of the same EEG signal should remain consistent across different spatiotemporal modeling paths. Based on this hypothesis, we propose a Dual-Path Spatiotemporal Contrastive Learning (DP-STCL) framework for cross-subject EEG emotion recognition. DP-STCL employs two complementary encoders with independent parameters, namely a Temporal-to-Spatial (TS) path and a Spatial to-Temporal (ST) path, to model EEG spatiotemporal information under different integration orders. During representation learning, the same emotional stimu

---

### [283] Duration-Aware World Models for Sleep Staging with Dwell-Time Constraints

**链接**: https://arxiv.org/abs/2610.33033
**作者**: Junhui Gao
**来源**: q-bio.QM cs.NE
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Closed-loop neuromodulation requires sleep staging that respects stage-specific minimum dwells: stimulation policies switch by sleep stage, and a policy change is permitted only after the current stage has persisted for its minimum duration. Discriminative classifiers fragment stage trajectories---for example, a 30 s Wake segment inside a 10 min N2 run---and even hidden semi-Markov smoothing leaves 11.3% of segments below the minimum dwell threshold. This paper presents a world model in which a recurrent state-space model (RSSM) learns dwell structure endogenously from EEG, via duration-aware latent sampling, a survival-curve dwell prior, and transition-matrix calibration, and a trajectory-level hard-constraint layer guarantees the minimum dwell at decoding. On SHHS-1 (200 subjects, 160/20/20, three repeated splits), the model reaches a test accuracy of 0.690 +/- 0.053 (95% CI over 3 folds) versus 0.641 +/- 0.042 for an identically split discriminative baseline, with macro-F1 +17.5 pp 

---

### [284] Parameter-Efficient Adaptation of Time Series Foundation Models for Electrical Load Forecasting

**链接**: https://arxiv.org/abs/2610.28200
**作者**: Aliullah, Julian Oelhaf, Edouard Fouch\'e, Jessica Deuschel, Christian Bergler, Andreas Maier 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [285] Towards Generalist Game Agents: A Survey of Foundation Models in Virtual Worlds

**链接**: https://arxiv.org/abs/2605.09965
**作者**: Kuan Zhang, Dongchen Liu, Qiyue Zhao, Tianyu Xin, Yue Su, Haisheng Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [286] Foundation Models in Medical Image Analysis: A Systematic Review and Meta-Analysis

**链接**: https://arxiv.org/abs/2510.16973
**作者**: Praveenbalaji Rajendran, Mojtaba Safari, Wenfeng He, Mingzhe Hu, Shansong Wang, Jun Zhou and Xiaofeng Yang
**来源**: cs.CV cs.AI physics.med-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [287] Adaptation of Foundation Models in Medical Image Analysis: Mechanisms, Evidence, and Deployment Considerations

**链接**: https://arxiv.org/abs/2603.14271
**作者**: Karma Phuntsho, Abdullah, Kyungmi Lee, Ickjai Lee and Euijoon Ahn
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [288] MOSAIC: Towards a Universal Latent Space for Computational Pathology Foundation Models

**链接**: https://arxiv.org/abs/2610.33059
**作者**: Dibaloke Chanda and Praveen Madiraju
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (PFMs) differ substantially in architecture, pretraining objective, training data and representation dimensionality, yet it remains unclear whether they learn fundamentally different feature spaces or alternative coordinate systems of a shared underlying representation. We present MOSAIC, a systematic study of latent-space similarity, alignment and interoperability across $12$ patch-level and $6$ slide-level PFMs. We first quantify representational agreement using complementary similarity measures and analyze how architecture, pretraining objective, network depth and magnification influence latent geometry. We then evaluate multiple alignment strategies for mapping independently learned representations into a common latent space. The resulting representations are evaluated through cross-model agreement, retrieval, geometry preservation, and downstream multiple-instance learning across molecular and morphological prediction tasks. MOSAIC provides a unified fr

---

### [289] CAMEL-CLIP: Channel-aware Multimodal Electroencephalography-text Alignment for Generalizable Brain Foundation Models

**链接**: https://arxiv.org/abs/2603.13272
**作者**: Hanseul Choi, Jinyeong Park, Seongwon Jin, Sungho Park, Jibum Kim
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [290] ProMo3D: Probing Motion Cues in Frozen 3D Foundation Models

**链接**: https://arxiv.org/abs/2610.33802
**作者**: Xiaoang Zhang and Mert Kiray and Yordanka Velikova and Manoj Biswanath and Benjamin Busam
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feed-forward 3D foundation models have recently reshaped multi-view reconstruction, yet dynamic 4D understanding still often relies on large-scale motion supervision or hand-crafted, architecture-specific heuristics. We ask whether frozen 3D foundation model tokens already encode motion-relevant information that can be exposed by lightweight readout functions, rather than re-learning motion-specific features with high-capacity decoders. Through probing on three representative backbones, we find that static--dynamic separation is decodable from frozen token representations. Our rank-restricted and spectral analyses on $\pi^3$X reveal that the recovered motion cues are concentrated in a low-dimensional subspace. Building on this, we propose Probing-based Motion Distillation (PMD), which converts pairwise motion-state compatibility scores against a fixed anchor token into dense motion masks. Trained on only 160 YouTube-VOS videos using a single 16 GB GPU, PMD transfers zero-shot to DAVIS,

---

### [291] Compression of Vision Foundation Models for Retinal OCT via Growing-Neural-Gas Codebooks and Graph-Guided Masked Image Modeling

**链接**: https://arxiv.org/abs/2610.33340
**作者**: Ali Yavari, Tilman Schmoll, Rainer A. Leitgeb, Wolfgang Drexler, Thomas Schlegl
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models for retinal imaging are large and computationally demanding, limiting point-of-care deployment. We ask how much of such a model's downstream utility survives compression into a smaller network. We propose a topology-aware discretization framework that distills a continuous foundation model into a discrete codebook, then uses it as the reconstruction target for masked image modeling (MIM). It combines gradient-free codebook learning via Growing Neural Gas, which yields an adjacency graph over the codes, with a graph-distance soft cross-entropy loss that replaces one-hot MIM targets with topologically graded supervision. With student pretraining on 383 public Duke iAMD optical coherence tomography (OCT) volumes, the pipeline distills an 86M-parameter teacher into a 22M-parameter student with at least 3.6x fewer FLOPs. The student performs close to, and in some settings above, its teacher across three classification and two segmentation benchmarks, with the magnit

---

### [292] PixFoundation: Are We Heading in the Right Direction with Pixel-level Vision Foundation Models?

**链接**: https://arxiv.org/abs/2502.04192
**作者**: Mennatullah Siam
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [293] Dynamic Multi-Step Decoding for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2610.34409
**作者**: Birmjune Kim, Hyungju Lee, Hyun Oh Song
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series forecasting models typically use a fixed decoding strategy at inference time: either one-shot prediction of the full horizon or autoregressive rollout over atomic chunks. While one-shot decoding reduces error accumulation, it can discard useful sequential structure; conversely, autoregressive decoding preserves temporal dependencies but may compound errors. We argue that the optimal decoding strategy is not fixed across inputs, but should be selected adaptively for each forecasting instance. We propose a dynamic strategy selector that treats the forecast rollout schedule as an inference-time decision problem for frozen pretrained time-series foundation models. The selector is a learned network that ranks candidate rollout schedules using hidden states of the backbone, and is trained on historical windows of the evaluated tasks for each backbone. To make the candidate set tractable over the exponentially large space of horizon partitions, we use dynamic programming that redu

---

### [294] Uncertainty Quantification for Financial Foundation Models: A Survey

**链接**: https://arxiv.org/abs/2610.33109
**作者**: Zijie Zhao, Mingjun Sun, Shenbo Xu
**来源**: q-fin.GN cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial foundation models increasingly support workflows spanning financial question answering, disclosure analysis, forecasting, and decision-making. In these settings, uncertainty may concern whether evidence is valid and available at the relevant time, whether an interpretation is justified, which outcomes remain plausible, or which action is preferred under costs and risk constraints. Because these objects arise at different points in a workflow, uncertainty cannot be reduced to confidence in a final output. We introduce a source-aware framework that distinguishes six sources of uncertainty across evidence and context, model and inference, and outcome and action, while treating agentic workflows as the execution layer through which uncertainty can propagate, change form, or be reduced. We develop a mechanism-based taxonomy grounded in how methods construct or verify uncertainty and reliability representations, and use it to assess their applicability across financial task domains

---

### [295] Accuracy and efficiency of compact foundation models for surface-water mapping during floods

**链接**: https://arxiv.org/abs/2610.34904
**作者**: Parastoo Farajpoor, Mohammadreza Narimani
**来源**: eess.IV cs.CV cs.LG stat.AP
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained Earth observation models may reduce the effort needed to map surface water, but their value depends on the alternative against which they are compared. We evaluated Prithvi-EO-2.0-Tiny using the 446 hand-labeled Sentinel-2 chips from 11 flood events in Sen1Floods11. A fine-tuned model, a frozen-encoder model, and an identical randomly initialized architecture were compared with a similarly sized U-Net, a larger Prithvi model, and spectral-index thresholds. Experiments varied the number of training chips, excluded events from model fitting, and measured computational cost and prediction reliability. With 252 training chips, U-Net achieved a water intersection-over-union (IoU) of 0.856 on the official test set, compared with 0.833 for fine-tuned Prithvi-Tiny. Pretraining improved the tiny transformer over random initialization by a reported 0.046 IoU with 25 training chips and 0.023 with 252 chips, but did not reverse the U-Net ranking. Across 11 event-exclusion evaluations, m

---

### [296] HIFI: A Highly Efficient Framework for Statistical Inference with Foundation Models

**链接**: https://arxiv.org/abs/2610.34550
**作者**: Po-Wei Chen, Shan Yu, Chunlin Li
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models provide powerful representations for unstructured data, such as text and images, and parameter-efficient fine-tuning (PEFT) makes their adaptation to downstream tasks increasingly practical. For neural estimators that lack a tractable sampling distribution, resampling-based procedures offer a flexible route to statistical inference, but they often require hundreds of model fits, making them computationally prohibitive at foundation-model scale. We introduce HIFI, a two-stage fine-tuning framework for statistical inference on parameters such as conditional means. Stage 1 adapts a foundation model once on a larger sample, capturing the complex structure of the data and controlling estimation bias through a single fit. Stage 2 applies a resampling inference procedure to a smaller independent sample, concurrently fitting multiple lightweight PEFT estimators to the residual to quantify estimation variability without relearning the full task. HIFI accommodates a broad class

---

### [297] FediLoRA: Practical Federated Fine-Tuning of Foundation Models Under Missing-Modality Constraints

**链接**: https://arxiv.org/abs/2509.06984
**作者**: Lishan Yang, Wei Emma Zhang, Nam Kha Nguygen, Po Hu, Yanjun Shu, Weitong Chen and Mong Yuan Sim
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [298] Unlocking the Specialization Capability of PPG Foundation Models for Wearable Signals through Structured Pruning and Adaptive Fine-Tuning

**链接**: https://arxiv.org/abs/2610.33788
**作者**: Huaming Du, Zhixian Xie, Gaoyang Zhen, Gang Kou, Guisong Liu, Yanchao Tan 等 (9 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Photoplethysmography (PPG) plays a central role in wearable health monitoring and clinical decision support. However, existing approaches to universal PPG representation learning are predominantly trained on high-quality large-scale datasets obtained from oximeters in hospital settings and often struggle to adapt to sparse and low-quality real-world datasets, thereby limiting their generalization to clinically relevant tasks on prevalent PPG data such as collected from wearable devices. Surprisingly, even after full fine-tuning, PPG foundation models cannot consistently outperform general-purpose time-series models. Therefore, a key question is how to effectively adapt PPG foundation models to target prediction tasks. Through empirical studies on various PPG foundation models, we find that pretrained models often exhibit inherent sparsity and computational redundancy, suggesting that PPG foundation models have learned to activate task-relevant network substructures for different predic

---

### [299] GIFT: Representation Geometry Matters for Single-Domain Generalized Object Detection

**链接**: https://arxiv.org/abs/2610.35374
**作者**: Yin Zhang, Yaoyue Zheng, Yongqiang Zhang, Bogdan Raducanu, Dan Li
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-Domain Generalized Object Detection (S-DGOD) aims to generalize from a single source domain to unseen domains under distribution shifts. Existing efforts mainly focus on simulating unseen domains or suppressing domain-specific factors. However, they largely overlook the intrinsic generalization capability embedded in Vision Foundation Models (VFMs). In this work, we show that unconstrained fine-tuning disrupts the geometric structure of pre-trained representations, which encodes domain-invariant semantics. Motivated by this, we propose Geometric-Invariance Fine-Tuning (GIFT), a geometric-aware fine-tuning method for VFMs. Specifically, we introduce a series of learnable Householder reflections to the pre-trained weights to encourage geometry-consistent adaptation under domain shift. In addition, we propose a lightweight channel-wise scaling to facilitate effective task-specific adaptation. Extensive experiments demonstrate that GIFT consistently outperforms state-of-the-art (SOT

---

### [300] Learning Pathology-Sensitive Representations for Unsupervised Retinal OCT Anomaly Detection

**链接**: https://arxiv.org/abs/2610.33143
**作者**: Tania Haghighi, Sina Gholami, Behafarin Emam, Jennifer I Lim, Theodore Leng, Atalie C Thompson 等 (8 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning approaches for retinal optical coherence tomography (OCT) predominantly rely on predefined disease categories, limiting their ability to detect rare or previously unseen abnormalities. While visual foundation models provide transferable representations, their effectiveness in identifying pathological deviations from normal retinal anatomy remains insufficiently understood. In this work, we introduce an unsupervised framework for retinal OCT anomaly detection and localization that adapts pretrained visual representations to normal retinal anatomy through anatomy-aware reconstruction and contrastive triplet learning guided by synthetic structural perturbations, without requiring disease-specific annotations. We systematically investigate the influence of pretraining strategies, anatomy-aware representation adaptation, and anomaly scoring mechanisms on the detection and localization of unseen retinal abnormalities. Our findings demonstrate that adapting pretrained representa

---

### [301] Auto-Research Arena: Benchmarking and Advancing Auto-Research in Language Modeling

**链接**: https://arxiv.org/abs/2610.35866
**作者**: Xi Chen, Chongjian Ge, Yiran Xu, Yiqun Mei, Henrik I. Christensen, Hao Tan 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As autonomous research systems become more capable, benchmarks must both evaluate their performance and support meaningful research progress. We introduce Auto-Research Arena, a multi-target benchmark for evaluating autonomous research systems and discovering ideas in language modeling. Arena supports diverse research objectives within a shared experimental environment by separating admissibility from improvement: model quality and resource constraints determine whether a result qualifies, while the selected target measures progress among admissible results. We instantiate Arena in language model pretraining with nine targets spanning model, data, training, and inference efficiency, and evaluate seven research harnesses using two foundation models. Arena clearly differentiates existing harnesses across research objectives, with several sophisticated methods outperformed by our simple sequential search baseline, indicating substantial headroom in current auto-research systems. Beyond ev

---

### [302] Self-Supervised Pretraining for PHM: What Transfers, What Does Not, and What Federating It Costs

**链接**: https://arxiv.org/abs/2610.35280
**作者**: Jos\'e Sanz-Dur\'an, David Sol\'is-Mart\'in
**来源**: cs.AI cs.CE cs.LG cs.PF
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised pretraining has produced capable time-series foundation models, but its value for Prognostics and Health Management (PHM) has not been measured under leakage-controlled conditions. We measure it on a corpus of 47 public PHM datasets, harmonized to a single tensor contract and partitioned so that 11 datasets are withheld from pretraining in full. Transfer turns out to be task-dependent: a compact channel-independent Transformer encoder (801,808 parameters) pretrained with masked patch prediction raises fault-classification macro-F1 from 0.350 to 0.812 on CWRU and from 0.569 to 0.951 on HSG18, yet on CMAPSS remaining-useful-life estimation no pretrained checkpoint reliably improves upon a from-scratch baseline. We pretrain under two regimes---centralized, and simulated cross-silo federated with ten clients grouped by physical domain---holding architecture, objective, source data and optimization budget fixed. Two further findings are negative. At matched budget the centra

---

### [303] Zero-Shot Monocular Depth Estimation for Visual Perception in Lower-Limb Prostheses

**链接**: https://arxiv.org/abs/2610.35018
**作者**: Ishi Vijayvergiya, Marc H\"olle, Youssef Dawoud, Amir El-Ghoussani, Michele De Vita, Rohan Asthana 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monocular depth estimation has advanced rapidly with the development of foundation models that demonstrate strong zero-shot generalisation across diverse visual domains. However, the applicability of these models to visual perception for lower-limb prosthetics remains largely unexplored. Reliable depth perception is particularly important for prosthesis users, who often experience significant challenges when navigating stairs, uneven terrain, and other complex environments. To address this gap, we introduce the Lower-Limb Prosthesis (LP) dataset, a benchmark designed to evaluate depth perception from an emulated knee-level prosthetic viewpoint. Using this dataset, we evaluate four state-of-the-art monocular depth estimation foundation models. Our results provide the first systematic benchmark of monocular depth estimation performance from a prosthetic viewpoint, while highlighting both the challenges and the potential of deploying foundation models in prosthetic perception systems. The

---

### [304] TimeWorld: Towards Action-Conditioned Multimodal World Models for Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.34797
**作者**: Hang Ni, Weijia Zhang, Hao Liu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series forecasting supports decision-making in web applications such as online retail and network management, where planned actions can reshape future dynamics. World models provide a natural paradigm for predicting such action-dependent changes beyond extrapolating historical patterns. However, existing time series world models (TSWMs) typically rely on fixed, domain-specific covariate schemas that limit flexible intervention specification, while multimodal forecasters treat text primarily as passive predictive context. To investigate these gaps, we introduce TSWM-Bench, a cross-domain benchmark for multimodal TSWMs spanning seven real-world datasets, with textual interventions grounded in recorded action--outcome data. Our evaluation reveals that conventional multimodal forecasters underperform history-only time series foundation models (TSFMs) despite dataset-specific training, whereas simple text-prefix adaptations improve forecasting across all evaluated TSFM backbones. These

---

### [305] Prior Predictive Matching for Bayesian LoRA

**链接**: https://arxiv.org/abs/2610.35457
**作者**: Tomasz Ku\'smierczyk, Eliezer de Souza da Silva, Marcin Sendera
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bayesian variants of Low-Rank Adaptation (LoRA) provide principled uncertainty estimation when fine-tuning large foundation models, but require specifying the prior over the low-rank weight updates. We address this hyperparameter selection problem by introducing a closed-form prior-predictive estimator that operates before fine-tuning. We analyze a second-order expansion of the network and quantify how the low-rank prior drives function-space deviations from the pretrained outputs. We also show that these prior-predictive quantities depend on the prior only through the product of the adaptation rank and the fourth power of the prior scale. Because the training targets share a single draw of the latent weight update, we can leverage the covariance between example residuals to derive a moment-matching estimator. Furthermore, our theoretical analysis establishes that the optimal prior precision scales as $r^{-1/2}$ with the rank $r$, allowing a single estimate to generalize across all ran

---

### [306] The Locality Trade-off in Masked Patch Self-Distillation

**链接**: https://arxiv.org/abs/2610.33223
**作者**: Xi Weng, Zhaoyu Liu, Lianyu Hu, Jin Song Dong
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Masked patch self-distillation is a key component of modern vision foundation models, including DINOv2 and DINOv3, yet its implications for local visual information remain unclear. We show that its semantic benefits can coexist with a scale-dependent locality cost. Using two annotation-free diagnostics, we distinguish recoverable local appearance from spatial correspondence. In smaller models, adding iBOT substantially weakens patch correspondence while largely preserving appearance decodability. In larger models, correspondence improves, but pixel and texture evidence becomes less linearly accessible in deep features. Thus, scaling changes the form of the locality cost rather than uniformly eliminating it. Our analysis of Gram anchoring further shows that preserving patch relations does not guarantee simultaneous improvements in both properties. These findings motivate evaluating and designing visual representations around the complementary demands of semantic abstraction, appearance 

---

### [307] MetaARIMA: Configuration-Level Transfer Learning for ARIMA Models

**链接**: https://arxiv.org/abs/2610.34171
**作者**: Vitor Cerqueira, Ricardo In\'acio, Carlos Soares
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models have demonstrated that pretraining on diverse datasets enables effective transfer to new forecasting tasks. Classical methods like ARIMA, however, remain configured and trained independently for each series, discarding knowledge from previous experiments. Consequently, selecting and training an ARIMA configuration remains challenging and often relies on heuristic approaches based on in-sample goodnessof-fit measures. We propose MetaARIMA, a pretrained configuration policy based on metalearning that brings transfer learning to classical statistical forecasting at the configuration level rather than the model level. The policy learns from historical experiments which ARIMA configurations achieve top-quantile performance, and recommends promising candidates for new series while preserving interpretability and local estimation. At inference, it selects a diverse set of candidates via maximal marginal relevance and efficiently identifies the final configuration

---

### [308] QECGBERT: A Scalable ECG Foundation Model Based on Self-Supervised Language Learning via VQ-VAE Waveform Tokenization

**链接**: https://arxiv.org/abs/2610.33964
**作者**: Aruna Mohan, Burcu Ozek, Or Zilbershot, Fatemeh Afghah
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI foundation models play a pivotal role in advancing heart disease diagnosis from electrocardiogram (ECG) data, particularly for rare diseases where the lack of sufficient labeled data hinders supervised learning. However, most self-supervised learning methods treat ECGs as generic sequence or image data without exploiting underlying physiological structure. To address this limitation, we propose QECGBERT, a self-supervised ECG language model that explicitly encodes physiological semantics by tokenizing the P, QRS, T, and isoelectric background waveforms. Vector-quantized variational autoencoder (VQ-VAE) tokenization is applied to each 12-lead ECG, with tokens enriched by continuous waveform features to preserve morphology lost during quantization without increasing sequence length. This design enables compact BERT masked language modeling with short sequences, improving scalability and reducing computational cost relative to long-sequence approaches. QECGBERT applies BERT pre-trainin

---

### [309] Work Agents: Systems, Capabilities, and Optimization

**链接**: https://arxiv.org/abs/2610.35845
**作者**: Zishan Xu, Enjun Du, Mingqi Gao, Cheng Yang, Junhao Shen, Zirong Chen 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As foundation models evolve from information generation to digital work execution, agents are increasingly capable of completing complex tasks across tools, applications, and workflows. However, existing research lacks a unified perspective on how agents reliably accomplish delegated work. To address this gap, we present a work-centric, system-level perspective that views work agents as systems combining foundation models and runtime harnesses to execute tasks in stateful workspaces and deliver verifiable outcomes. We introduce two complementary dimensions, work persistence and work openness, to characterize working conditions, and classify digital work into five forms according to task scope and organization. Building on this framework, we identify five core capability families required for reliable work execution and examine approaches to model optimization, harness optimization, and their joint optimization. We further analyze existing evaluation methods and metrics from the perspec

---

### [310] Critic's Eye: Review-Grounded Graph Reasoning for Long-Form Motif Discovery

**链接**: https://arxiv.org/abs/2610.35011
**作者**: Xinyu Sun, Zhangyue Yin, Xinyi Ju, Xin Wang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep narrative understanding requires distinguishing what happens from how it is presented, moving beyond the chronological fabula to decode the sjuzet, the discursive organization through which themes are staged. We study this through the recurrence of literary motifs (blood in Macbeth, for instance), where symbolic significance emerges not from local cues, but through repetition-with-variation across the whole work. We operationalize this setting as Computational Motif Discovery, a transductive task that predicts missing line-motif links using the full narrative structure of a play. We propose Critic's Eye, which models the work as a heterogeneous Narrative Topology Graph and performs discriminative inference over global structural evidence. Critic's Eye achieves 84.8% Hit@5 on our benchmark, nearly quadrupling state-of-the-art proprietary foundation models (Gemini-3-pro-preview, ~22.6%). Our analysis reveals that despite massive scaling, sequence-based models hit a "semantic ceiling

---
