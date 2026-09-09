# 📑 论文索引 - 2026-09-10

共 304 篇论文

---

### [1] NeoRed: A Knowledge-Logic-Alignment Multimodal Large Language Model for Neonatal Respiratory Disease Diagnosis

**链接**: https://arxiv.org/abs/2609.03527
**作者**: Yinan Liu, Hongtai Xia, Haoran Xu, Jiankang Hong, Yu Jianli, Jingkuan Song 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] AgentLeak: Cloning Stronger LLM Agent Capabilities onto Weaker Agents Beyond Skill Stealing

**链接**: https://arxiv.org/abs/2609.07131
**作者**: Xiaoting Lyu, Yuhong Wu, Yufei Han, Shichang Liu, Liang Zhang, Bin Wang 等 (9 人)
**来源**: cs.CR cs.AI
**匹配关键词**: Foundation Models, LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly achieve long-horizon tasks by combining foundation models with explicit skills and implicit procedural knowledge acquired through execution. The resulting task-solving capabilities have become valuable proprietary assets, raising a new security question: can a substantially weaker attacker-controlled agent acquire the capabilities of a stronger proprietary agent through limited black-box interaction? Existing skill-stealing attacks recover explicit skill artifacts, yet we show that artifact leakage does not necessarily transfer capability: a weaker agent may possess the same skills but still fail because it lacks procedural behaviors implicitly realized by the stronger agent. Our key insight is that the skill execution gap itself forms a leakage surface, where missing behaviors are exposed through observable differences between successful victim executions and failed attacker executions. Based on this, we present AgentLeak, a black-box cap

---

### [3] Signed Rescue Routing: Harm-Aware Cascades for Efficient LLM Inference

**链接**: https://arxiv.org/abs/2609.07786
**作者**: Zheyuan Wang, Siyu Li, Peiqiao Song, Sijia Chen, Qianqian Song, and Qian Liu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) cascades answer easy requests with a small model and escalate selected requests to a larger model. Most routers prioritize examples on which the small model appears uncertain or likely to be wrong. This proxy ignores a decisive fact: escalation is useful only when the large model corrects the small model, and it is harmful when the large model replaces a correct answer with an incorrect one. We introduce Signed Rescue Routing (SRR), a budgeted routing method that predicts these two events separately and ranks requests by their difference. We show that this signed conditional gain is the Bayes-optimal routing score under a fixed escalation budget. SRR requires only the small model's output statistics at deployment and adds a lightweight two-head router. We evaluate SRR with Qwen3-4B and Qwen3-8B on TBD examples from MMLU, HellaSwag, and ARC-Challenge. Across the accuracy-compute curve, SRR reaches an area of TBD, compared with TBD for a learned small-model err

---

### [4] DART: A DAG-Based Reputation and Incentive Framework via Blockchain-Enabled Governance for Trustworthy LLM Multi-Agent Collaboration

**链接**: https://arxiv.org/abs/2609.05529
**作者**: Manoj Kumala, Xinyun Liua, Ronghua Xu
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) predominantly rely on centralized orchestration and lack formal verification mechanisms for agent reliability, participation, and system-level behavioral alignment. These shortcomings leave open environments severely vulnerable to uncooperative or malicious agents. This work proposes DART, a Directed Acyclic Graph (DAG)-based reputation and incentive regulation framework for trustworthy multi-agent collaboration, combining centralized operational orchestration with blockchain-enabled decentralized governance and accountability. DART unifies DAG workflow orchestration, capability and reputation-aware task allocation, dynamic behavior updates, multi-factor incentives, and smart contract accountability paired with IPFS storage. Under this paradigm, agent selection dynamically balances task alignment, historical reputation, and workload, while post-execution behavioral evidence continuously calibrates agent trust and the probabilit

---

### [5] SWE-Test: Benchmarking LLM Vulnerability Discovery via Input Prediction

**链接**: https://arxiv.org/abs/2609.06229
**作者**: Yuanxiang Shi, Jiayi Lin, Xuanyong Lin, Liangcai Su, Yeheng Duan, Wei Wang 等 (10 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vulnerability discovery is becoming an important ability of large language model (LLM) agents: agents that silently miss real defects leave critical software exposed. Rigorously measuring this ability is therefore urgent, but existing benchmarks are gameable through data contamination, score recall against an unknowable vulnerability set, often rely on synthetic bugs, and report a single end-to-end verdict that cannot localize where an agent fails. Vulnerability discovery is a composite ability: an agent must comprehend source code, infer input constraints, construct inputs, execute them, and iteratively correct from feedback. We recast its measurement as an input-prediction task with a closed, deterministic ground truth: using coverage-guided fuzzing, we mine deep target branches in real-world C/C++ programs and ask an agent to predict an input that drives execution to a given branch. This decomposes discovery into three task modes over 22 real-world C/C++ programs spanning 15 domains

---

### [6] Interface-Aware KV Cache Quantization for Dense On-Chip NVM in Long-Context LLM Decoding

**链接**: https://arxiv.org/abs/2609.05764
**作者**: Jiahao Zheng, Yifan Qin, Xiaobo Sharon Hu, Yiyu Shi
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The key-value (KV) cache is the dominant memory bottleneck in long-context large language model (LLM) decoding: every step reads it entirely, so decoding is memory-bandwidth bound. Holding a quantized KV cache in dense on-chip non-volatile memory (NVM) removes the off-chip transfer. Existing KV quantization methods, however, were designed for GPU-style memory systems: KIVI attaches per-group metadata, adding about 25% to the stored KV cache; KVQuant keeps sparse full-precision outliers that a dense array cannot hold in place. This paper examines what these structures cost when the KV cache resides in NVM behind fixed-range converters, and designs a quantization scheme matched to that interface. The architecture stores the quantized KV cache in dense on-chip NVM, uses a small static analog crossbar only for the fixed rotation, and keeps attention in on-chip digital logic. A randomized rotation and per-vector normalization give every coordinate the same range, so one fixed codebook for k

---

### [7] Benchmark Scores Are Pipeline-Dependent: A Reliability Audit of Cybersecurity LLM Benchmarks

**链接**: https://arxiv.org/abs/2609.08765
**作者**: Aymene Berriche, Cathrine Shalby, Mohannad Alhanahnah, Yazan Boshmaf
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) benchmarks are often treated as fixed datasets with stable scores, yet their outcomes depend on configurable evaluation pipelines. We audit eight cybersecurity benchmarks across 10 proprietary, open-weight, and cybersecurity-specialized LLMs. By modeling benchmarks as measurement pipelines, we identify 15 systematic failure modes and show that a single pipeline choice can change a model's score by more than 80 percentage points and substantially alter model rankings. At the cross-benchmark level, two semantically similar task pairs rank the same models differently because of incompatible evaluation conventions. Under an evaluation harness that standardizes pipeline choices while preserving task semantics, nine of 10 models shift by at least three ranks on at least one benchmark. These results show that cybersecurity LLM benchmark scores are pipeline-dependent and motivate pipeline-aware auditing as a core requirement for reliable model evaluation.

---

### [8] PlannerForge: LLM Agents for Scenario-Based Testing of Motion Planners in Autonomous Driving

**链接**: https://arxiv.org/abs/2609.08965
**作者**: Yuan Gao, Sebastian M\"uller, Mattia Piccinini, Marc Kaufeld, Yuchen Zhang, Finn Rasmus Sch\"afer 等 (8 人)
**来源**: cs.AI cs.CL cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ensuring the safety of autonomous driving is a critical challenge. Scenario-based testing is a systematic process used to validate Autonomous Driving Systems (ADSs), but it remains a fragmented modular pipeline in which scenario generation, retrieval, modification, ADS execution, and results analysis are performed by separate tools with little interaction. Large Language Model (LLM) agents have shown promise across ADS sub-systems such as perception, planning, and control. However, no prior work covers the whole scenario-based testing pipeline for ADSs with a unified LLM-agent framework. We present PlannerForge, an LLM-agent framework that extends all scenario-based testing stages (from Scenario Generation to ADS Assessment) and adds two further LLM-enhanced stages: ADS Enhancement and ADS Benchmarking. We evaluate PlannerForge with 10 off-the-shelf LLMs across all tasks (Generation, Selection, Modification, Module Routing, Planner Testing, and Enhancement) under 5 prompt conditions. B

---

### [9] Beyond Cross-Lingual Transfer: Benchmarking Propagation Boundaries in Multilingual LLM Unlearning

**链接**: https://arxiv.org/abs/2609.05976
**作者**: Pengyang Shao, Chuanpeng Lu, Wei Qin, Yanzheng Jin, Xiaohao Liu, Xi Ai 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) unlearning aims to suppress target knowledge while preserving general capabilities. In multilingual settings, unlearning must additionally propagate within its intended linguistic scope. However, existing evaluations mainly measure cross-lingual transfer and cannot distinguish insufficient from excessive propagation. We introduce CLLPU (Cross-Lingual and Language-Bound Protocol for LLM Unlearning), a multilingual benchmark that formulates this problem through two settings: common-goal forgetting, where target knowledge should be suppressed across all languages, and language-conditioned forgetting, where suppression should remain confined to a designated language. CLLPU combines goal-guided topic pairing, schema-aware relation matching, and dual-anchor multilingual translation to construct 800 matched knowledge-unit pairs and 72,000 QA instances across ten languages. Experiments with six representative methods on Llama-3.1-8B-Instruct reveal opposite failure m

---

### [10] A Rubric-Guided Large Language Model Solution for Opioid Use Disorder Computable Phenotyping

**链接**: https://arxiv.org/abs/2609.05682
**作者**: Mengxian Lyu, Paredes Pardo, Cheng Peng, Ziyi Chen, Mengyuan Zhang, Jieting Li Lu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Opioid use disorder (OUD) remains a public health crisis in the United States, yet it is difficult to identify from electronic health records (EHRs) because missing diagnosis codes and supporting evidence are buried in clinical narratives. Accurate OUD identification is critical to support interventions and improve health outcomes. This study developed a rubric-guided large language model (LLM) that incorporated Optimization by PROmpting (OPRO) for OUD computable phenotyping (CP). The framework used an 18-item, expert-identified rubric to instruct LLMs to automatically extract critical text with supporting evidence to determine OUD flags. Two UF Health physicians (GMR and WMG) chart-reviewed 253 patients, including 68 OUD-positive cases. Our LLM-based computable phenotype (CP) achieved the best F1 score of 0.774 and an AUROC of 0.934, outperforming the machine learning-based CP using EHR and natural language processing-extracted variables, and zero-shot LLMs by relative F1 improvements

---

### [11] SimTIO: A Simulation-Grounded Multi-Agent LLM Framework for Compositional Traffic Intervention Optimization

**链接**: https://arxiv.org/abs/2609.05740
**作者**: Shuyang Li, Ruimin Ke
**来源**: cs.MA cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traffic analysts must translate diagnosed bottlenecks into executable interventions without allowing local improvements to degrade network-wide performance. This study presents SimTIO, a simulation-grounded multi-agent large language model framework for composing and selecting traffic interventions under explicit operational constraints. SimTIO first simulates an unmodified SUMO scenario to identify a baseline-frozen set of ten bottleneck edges. A grounded sampler then initializes signal-control, corridor-speed, and demand-preserving routing actions, while three specialist agents use measured simulation feedback to select one-parameter refinements from validator-confirmed mutation catalogs. Compatible actions are combined and re-simulated so that their interaction effects are measured rather than inferred. Final selection minimizes bottleneck time loss while constraining network-wide delay, neighboring-road spillover, throughput loss, and teleport events, with the unmodified scenario r

---

### [12] MetaKV: Adaptive KV Cache Compression for Constrained LLM Inference

**链接**: https://arxiv.org/abs/2609.07966
**作者**: Michael Wang, Keith Li, Roozbeh Bostandoost
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Key--value (KV) cache compression is an effective way to reduce the memory overhead of large language model (LLM) inference, particularly for long-context workloads. However, existing compression methods make different trade-offs among accuracy, inference latency, and peak KV cache memory utilization, making a single fixed configuration unsuitable across different prompts and resource constraints. We introduce MetaKV, an adaptive framework that selects a KV cache compression configuration for each input prompt based on user-specified latency and peak memory budgets. MetaKV uses lightweight prediction models to estimate the end-to-end latency, peak memory, and probability of a correct response for each candidate configuration, and selects the configuration that best satisfies the latency-memory constraints while preserving accuracy. We evaluate MetaKV across ten configurations from three representative KV cache compression methods, KVQuant, H$_2$O, and RocketKV, together with an uncompr

---

### [13] BlueprintAgent: Constraint-Triggered Targeted Revisits for Simulation-Ready Generation from Scanned Structural Blueprints

**链接**: https://arxiv.org/abs/2609.07362
**作者**: Zhouyuan Xu, Chen Yang, Linhao Wang, Jiansheng Fan, Chen Wang
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Converting in-service reinforced-concrete (RC) building blueprints into simulation-ready models---structured frame representations that support deterministic FEM export and qualified-engineer review---underpins safety assessment and seismic retrofit, but the process remains manual. Direct prompting of a multimodal large language model (MLLM) over a scanned sheet is unreliable: outputs often violate engineering constraints on beam--column support, span count, or 3D continuity. We present BlueprintAgent (BPA), a constraint-triggered multimodal agent for simulation-ready frame extraction from scanned blueprints. BPA treats the MLLM as the primary reader and decision maker, with OCR and computer vision supplying localized evidence. Its central mechanism realizes engineering constraints as callable validators whose entity-level conflict reports trigger targeted MLLM revisits over the local region---an inference-time control distinct from fixed pipelines and free-form self-reflection. We eva

---

### [14] Online Learning with LLM Experts from Limited Feedback

**链接**: https://arxiv.org/abs/2609.05820
**作者**: Wang Wei, Soumyabrata Pal, Koyel Mukherjee, Franck Dernoncourt, Ryan A. Rossi, Branislav Kveton 等 (7 人)
**来源**: cs.LG stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study adaptive routing of prompts to large language model (LLM) experts to maximize response quality in an online setting with limited feedback. We formulate it as a bandit problem with $K$ actions that represent experts and $d$ features that encode prompts, over a horizon of $T$ rounds. We propose algorithms that strategically select and observe rewards to minimize regret. In the full-information setting, we achieve a regret of $\tilde{O}(d T / \sqrt{m})$, while in the bandit setting we achieve $\tilde{O}(d T \sqrt{K / m})$, where $m \ll T$ is a budget on feedback. Our experiments show that we efficiently learn high-quality routing strategies across diverse LLMs from limited feedback.

---

### [15] Beyond Top-$k$ Skill Retrieval: Diversity-Aware Skill Routing for LLM Agents

**链接**: https://arxiv.org/abs/2609.05824
**作者**: Wang Wei, Tiankai Yang, Samyadeep Basu, Hongjie Chen, Yue Zhao, Zhengzhong Tu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on external skills, but routing user requests over large skill registries is difficult because many skills are functionally redundant while complex tasks often require complementary skill sets. Existing skill routers typically rank candidates independently by query relevance, which can waste context budget on redundant skills. We propose Diverse Skill Routing (DSR), a diversity-aware reranking framework that uses a Determinantal Point Process to balance relevance and non-redundancy. DSR introduces a query-residual diversity kernel that penalizes redundant skill overlap while reducing penalties caused only by shared query relevance. On the SkillRouter benchmark, DSR improves recall and full coverage over a strong pointwise reranking baseline, with larger gains on multi-skill queries. These results suggest that skill routing should be treated not only as relevance ranking, but also as complementary set selection.

---

### [16] Do Reasoning Representations Help Humans Evaluate LLM Outputs?

**链接**: https://arxiv.org/abs/2609.09038
**作者**: Jaewoo Lim, Sungbok Shin, Sanghyun Hong
**来源**: cs.LG cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning representations are increasingly used as explanations for large language model outputs. Yet they are typically evaluated with model-centric criteria, such as answer accuracy and faithfulness, leaving it unclear whether they help people evaluate model responses. In this work, we study reasoning representations as human-facing interfaces rather than proxies for model reasoning ability. We conduct a controlled human study of six reasoning formats across tasks of varying complexity, supported by a web-based framework that randomizes task domains, problem instances, and representation order. The study collects fine-grained judgments of structural understanding, error detection and localization, and trust calibration. Our study shows a mismatch between perceived preference and support for human evaluation. Participants prefer planning- and decomposition-based representations, but simpler chain-of-thought traces better support verification, trust, and interpretability. Preferred rep

---

### [17] Time-Aware Assistive Navigation

**链接**: https://arxiv.org/abs/2609.05596
**作者**: Masaki Kuribayashi and Zhongkai Shangguan and Eshed Ohn-Bar
**来源**: cs.CV cs.RO
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can interactive vision-and-language agents learn not just what to say but also \textbf{\textit{when}} to say it? Current language models rarely plan over whether and when to realize a real-time response to a user. However, providing accurate and timely support for human decision-making, such as when guiding visually impaired individuals through urban environments, requires careful real-time responsiveness--poorly timed responses can distract users or add unnecessary cognitive load. As a machine intelligence challenge for Multimodal Large Language Model (MLLM)-based agents, we introduce a large-scale multimodal benchmark for an egocentric, assistive navigation task in complex outdoor environments. Using this benchmark, we uncover a fundamental limitation of off-the-shelf MLLMs in delivering safe and time-sensitive navigation instructions, even with model fine-tuning on substantial amounts of data. We then demonstrate that a simple yet effective modification of the model, including direc

---

### [18] The Failure Happens Before the Drift: The Social Dynamics of Values in LLM Agent Societies

**链接**: https://arxiv.org/abs/2609.05514
**作者**: Farah Atif, Sougata Saha, Monojit Choudhury
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based agents are increasingly used as proxies for human participants in social science research, yet it remains unclear whether they can faithfully simulate diverse and conflicting human value systems. We present a World Values Survey (WVS)-grounded simulation framework where culturally diverse agents with different communication styles engage in longitudinal, value-laden discussions. Across approximately 4,000 conversations involving 1,200 personas, 15 topics, and three models (GPT-4o, Gemini-2.5-Flash, and Gemma-4-E4B), we evaluate value faithfulness, value drift, and conversational realism. We find that more than 50\% of personas fail to express their assigned WVS profiles from the outset, while 2-7\% drift after repeated conversations. Ablations removing demographic details improve faithfulness for some models but do not change the broader trend: simulated value distributions still systematically deviate from the assigned WVS profiles. Compared to human d

---

### [19] Deadline-Aware Adaptive Prefill Chunking for Efficient Large Language Model Serving

**链接**: https://arxiv.org/abs/2609.07883
**作者**: Siyu Song, Qi Bai, Jinbo Hao, Kai Li, Chenchen Wang, Jiayu Sun
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continuous batching improves large language model (LLM) serving throughput, but long prompt prefills can delay decode iterations and violate inter-token latency objectives. Chunked prefill mitigates this interference, yet its chunk size is normally fixed: small chunks protect decode latency but repeatedly pay launch overhead, while large chunks improve prefill efficiency but create latency spikes. We introduce SLOWeave, an online scheduling method that selects the largest prefill chunk predicted to finish before the earliest active decode deadline. The decision requires no workload-specific chunk-size tuning and is computed by a logarithmic-time search over a monotone iteration-cost model. We prove that, whenever a decode-only iteration is feasible and the cost predictor is accurate, SLOWeave maximizes immediate prefill progress among decisions that preserve every active request's next-token deadline. We evaluate the method in a reproducible event-driven simulator and an iteration-leve

---

### [20] Graph-Based Personalized Memory for LLM Agents: Representation, Evolution, Retrieval, and Evaluation

**链接**: https://arxiv.org/abs/2609.08599
**作者**: Dac Duy Anh Nguyen, Zhangchi Qiu, Shigeng Chen, Alan Wee-Chung Liew
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents are evolving from single-session tools toward long-term personal assistants that must adapt to individual users across tasks, contexts, and interactions. This shift makes memory a core requirement for personalization, since user preferences, goals, constraints, relationships, and past experiences are accumulated gradually and often change over time. Graph-based personalized memory provides a structured way to model such user information through explicit relations, temporal context, and evidence links. Such representations can model not only what an agent remembers about a user but also how memories are connected, revised, and retrieved to support personalized decisions. However, existing work remains fragmented across personalized agents and generic graph memory frameworks, making it difficult to understand the design space as a whole. This survey develops a lifecycle-oriented view of graph-based personalized memory for LLM agents. We organize existing

---

### [21] Characterizing Contention-Induced Reliability Collapse in KV-Cache Timing Side Channels for Multi-Tenant LLM Serving

**链接**: https://arxiv.org/abs/2609.06853
**作者**: Rana Abu Bakar
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Shared key--value (KV) cache reuse improves large language model (LLM) serving, but it can also create a timing side channel that reveals whether a prefix is already cached. Previous work shows that such attacks are possible, but their reliability under realistic multi-tenant contention is less understood. We study this problem through seven experiments on live shared LLM-serving systems. On a vLLM server running DeepSeek-R1-Distill-Llama-8B on NVIDIA GB10, mean Cohen's d drops from 0.7789 with no synthetic workers to 0.2109 with two workers (t=8.412), while higher worker counts cause no statistically detectable further loss. A 120-run sparse-overlap experiment places the best breakpoint at the boundary of the measured range (tau=0, 95% CI [0.000,0.113]), supporting an ambient-versus-loaded regime change rather than an internal physical threshold. AUROC falls from 0.650 at ambient to 0.531 near 61% overlap and partially recovers to 0.574 at saturation. Concurrency-depth variance is the

---

### [22] Automated Chest CT Protocol Selection via Large Language Model Derived Text Embeddings from Imaging Request Text

**链接**: https://arxiv.org/abs/2609.07986
**作者**: Zahra Hosseini, Mahan Pouromidi, Farzad Khalvati, Patrik Rogalla
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: Accurate CT protocol selection is critical for diagnostic quality and patient safety, yet the current process is manual, time-consuming, and prone to inconsistencies. Prior Machine Learning methods using keywords or bag-of-words lack contextual understanding and perform poorly on rare protocols. We propose a decision support system using large language model (LLM) features to recommend protocols from free-text clinical indications, capturing clinical nuance and phrasing variation for more consistent, efficient selection. Methods: In this REB-approved retrospective study, 285,123 chest CT imaging requests from a large academic medical center (2017-2024) were split into training (228,099, 80%) and held-out test (57,024, 20%) sets. Each request included procedure names, clinical indication, HIS comments, and the selected protocol. Clinical text was embedded using a fine-tuned LLM, Meta's LLaMA-3.1-70B; these features input a logistic regression classifier predicting 18 protocol l

---

### [23] Toward Sustainable Distributed LLM Inference: A Systems Synthesis and Research Agenda for an Energy-, Carbon-, and Cache-Aware llm-d Control Plane

**链接**: https://arxiv.org/abs/2609.05565
**作者**: Twinkll Sisodia
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) sustainability is increasingly a serving-systems problem, not only a training problem. In production, energy and carbon impact depend on more than model size: workload shape, batching, key-value (KV) cache reuse, prefill/decode placement, model and accelerator choice, power state, geographic carbon intensity, and service-level objectives (SLOs) all matter. Recent systems papers study many of these factors separately. This paper connects those results and asks a practical engineering question: what do they imply when the decision point is a distributed inference control plane such as llm-d? The contribution here is synthesis, not a new set of benchmark results. Reported performance, energy, carbon, and cost improvements remain the results of the cited papers and systems. I group the literature into recurring design patterns and use those patterns to sketch a Sustainable Inference Control Plane (SICP) for llm-d. The proposed control plane would consider latency

---

### [24] A Hyperbolicity Atlas of Large Language Model Hidden States

**链接**: https://arxiv.org/abs/2609.07053
**作者**: Zhichao Yang, Yuanze Hu, Gen Li, Qingchen Yu, Shiying Duan, Xinyu Wang 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM hidden states are ordinary vectors, but the distances among those vectors may still show hierarchical structure. To our knowledge, this paper is the first systematic study of whether prompt-token hidden states in contemporary LLMs exhibit Gromov Hyperbolicity (GH), a distance-based measure of tree-likeness. Using 818,904 sample-layer measurements from ten open-weight models across MATH500, HumanEval, WinoGrande, and TruthfulQA, we build a GH map over four axes: parameter scale, layer depth, model family, and input domain. The clearest pattern is depth, not scale: middle layers usually form a high-relative-hyperbolicity plateau, while final layers often become substantially more tree-like. Scale effects are weak and non-monotonic, matched 7/8B model families differ strongly, and domains interact with model specialization. These findings make GH useful as a practical diagnostic: it shows where hierarchical distance structure appears, how specialization changes it, and which model-lay

---

### [25] Training-Free Task Vectors for LLM Behavioral Control

**链接**: https://arxiv.org/abs/2609.09054
**作者**: Gabriel J. Perin, Lucas Boscaini, Andr\'e Araujo, Nina S. T. Hirata
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task vectors enable post-training model editing by identifying semantically meaningful directions in weight space, typically computed as the difference between a fine-tuned model and its pretrained initialization. However, this reliance on fine-tuning makes discovering such directions costly and limits the practicality of post-training model editing. To address this limitation, we introduce Training-Free Task Vectors (TFTVs), a novel method to compute task-vector-like directions without requiring fine-tuning. Our method maps activation steering vectors to rank-one weight-space edits using only forward-pass statistics, while satisfying arithmetic properties that directly support learning via addition, forgetting via subtraction, and the composition of multiple edits. Empirically, we evaluate TFTVs on large language model behavioral control tasks and show that they consistently amplify, suppress, and compose target behaviors while preserving general knowledge and problem-solving skills. 

---

### [26] MeClear: Cooperative Game-Theoretic Attribution and Risk-Aware Memory Clearance for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.09115
**作者**: Boyu Yang, Jiazheng Sun, Zilong Lu, Zhi Qiu, Xin Peng, Jun Zheng
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long horizon Large Language Model (LLM) agents rely on external memory systems to preserve user preferences and task knowledge across extended interactions. Conventional retrieval mechanisms optimize semantic compatibility rather than downstream utility, frequently introducing outdated, misleading, or conflicting evidence into the active context. We present MeClear, a task conditioned memory clearance framework that identifies memories featuring negative downstream utility through cooperative attribution and selectively suppresses them from agent execution. MeClear combines Leave One Out screening with sampled cooperative Shapley attribution to distribute utility across interacting evidence, effectively resolving redundant conflict masking where single removal evaluations fail. Utilizing attribution rankings, MeClear executes a query scoped minimal clearance strategy over a nested filtration, verifying task recovery on the cleared context without permanently altering the persistent mem

---

### [27] LLM-Aided Design for Manufacturing: A Multi-Agent System for Intent-Preserving Redesign of CAD for Improved Manufacturability

**链接**: https://arxiv.org/abs/2609.05559
**作者**: Kojo Welbeck, Xiangyu Shi, Zahra Sadeghi, Qi Zhu, Ping Guo
**来源**: cs.CE cs.CV cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce autonomous, intent-preserving Design for Manufacturing (DFM) redesign of CAD parts: given an engineer's CAD model, the method returns a variant that is easier to manufacture without losing its design intent. Generating such a redesign in a single shot is unreliable, since CAD fidelity degrades as parts grow complex; we instead produce it as a sequence of individually verified design transitions. Our DFM-Redesign pipeline realizes this with two coupled agent subsystems driven by a pretrained multimodal LLM: a DFM Reviewer that inspects the current design and proposes one intent-preserving manufacturability improvement at a time, and a CAD Modifier that executes each proposal as an edit to the part's CadQuery program. The CAD Modifier closes a verification loop, compiling every candidate edit and visually checking it against the intended change from multi-view renderings, then re-generating or re-instructing until the edit is accepted or abandoned. Iterating review and verif

---

### [28] A Measurement Study of LLM Inference Trade-offs Across Edge Continuum Hardware

**链接**: https://arxiv.org/abs/2609.08307
**作者**: Maysam Khatib, Moysis Symeonides, Demetris Trihinas, George Pallis and Marios D. Dikaiakos
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as backends for intelligent web services, but serving them across the edge continuum requires balancing quality, latency, model footprint, and energy. This paper presents a controlled measurement study of self-hosted LLM inference across edge and near-edge deployment nodes: an NVIDIA Jetson AGX Orin and a near-edge server with CPU-only and GPU-enabled inference modes. We evaluate multiple open-weight LLMs and quantization variants using a fixed question-answering workload, and compare them against GPT-4o as a cloud-hosted accuracy and latency reference. Our benchmarking pipeline reports accuracy, model footprint, per-token decoding latency, prefill latency, and overall execution energy. The results show that GPU-enabled server execution provides the lowest compute-side latency, while Jetson Orin shows lower measured energy, consistent with its lower platform power under our setup. CPU-only execution is consistently dominated in latency

---

### [29] Closing the Consistency Gap: Self-Evolving Agents That Learn to Stay on Course

**链接**: https://arxiv.org/abs/2609.08832
**作者**: Evelyn Duesterwald and Benjamin Elder and Lilian Ngweta and Shashanka Ubaru and Malgorzata Zimon
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-powered agents can be accurate on average yet unreliable in production, a discrepancy that has been observed but remains largely unaddressed. When given the same task five times, a ReAct agent on the AppWorld benchmark using GPT-4.1 succeeds in all five runs only 53% of the time, even though its per-run pass rate averages 77%. We call this 24-point shortfall the consistency gap, and we argue that addressing it is a precondition for trustworthy AI agent deployment. We present a self-evolving agent framework that reduces this gap by identifying unstable, low-consistency steps in agent trajectories and converting them into episodic memory the agent can draw on in future runs. At its core is a Consistency Analyzer that pinpoints where and why a trajectory is likely to flip across executions, and a Guideline Generator that converts the diagnosis into targeted guidelines, committed to memory and injected into future agent executions on similar tasks. On AppWorld wi

---

### [30] Every Token Counts: Exact Likert-Scale Distributions for Measuring LLM Attitudes and Biases

**链接**: https://arxiv.org/abs/2608.10503
**作者**: Davood Wadi, Mohsen Ghodrat, Matthew Philp
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Audit Without Verification: When LLM Accountability Layers Relay Rather Than Check

**链接**: https://arxiv.org/abs/2609.07680
**作者**: Paul-Peter Arslan
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM pipelines increasingly span organisational boundaries; when a fault surfaces, someone must determine where it entered. The artifact available is rarely a full execution trace: it is the reports each agent filed, and a filed report can state a conclusion alongside its observations. Using a pre-registered, institutionally partitioned pipeline of six agents with process-level information boundaries, balanced defect injection and matched clean twins (345,600 requests per chain model, two models), we first report that our pre-registered hypothesis -- that collective responsibility framing degrades escalation with chain length -- is not supported. The layer nevertheless fails asymmetrically. It originates almost nothing: zero allegations across 7,996 clean episodes where every agent stayed silent. It filters upstream error poorly, naming an innocent party in 34.4% and 62.6% of clean episodes where an agent raised a false alarm. Conditional on no agent proposing the true origi

---

### [32] HALO: A Physics-Aware LLM Agent Framework for Nanophotonic Design

**链接**: https://arxiv.org/abs/2608.28877
**作者**: Yubo Zhang, Jinlin Xiang, Zijun Zhao, Yang Zhao, Eli Shlizerman, Arka Majumdar
**来源**: physics.optics cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] ReST-RL: Reinforcing LLM Reasoning through Unified Self-Training and Value-Guided Search

**链接**: https://arxiv.org/abs/2508.19576
**作者**: Sining Zhoubian, Dan Zhang, Jie Tang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] PopResume: Causal Fairness Evaluation of LLM/VLM Resume Screeners with Population-Representative Dataset

**链接**: https://arxiv.org/abs/2603.22714
**作者**: Sumin Yu, Juhyeon Park, Taesup Moon
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] An LLM-Associated Register Shift in Korean Journal Abstracts: A Morphology-Aware Excess-Vocabulary Study, 2018-2026

**链接**: https://arxiv.org/abs/2609.07447
**作者**: Aron Lee (INTFRAME Research)
**来源**: cs.CL cs.DL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Excess vocabulary, a word's frequency above its pre-2023 trend, is how the change in scholarly English after 2022 has been measured. We adapt it to Korean with morphological units on 398,296 KCI abstracts (2018-August 2026), with 47,165 Vietnamese abstracts for comparison. Placebo floors are 0.1-2.2 points for the single-word statistic and at most 2.9 for the re-selected split-half set statistic. Korean abstracts show nothing in 2023, onset in late 2024, a rise through 2025 flattening in mid-2026: sisahada "suggest" appears in 21.4% of 2026 abstracts against 5.3% expected; plain verbs like araboda "look into" fall to a quarter of trend. Under stated assumptions the single-word conditional lower bound on LLM-processed abstracts is 3.5%, 10.5% and 16.1% for 2024-2026 and a split-half set bound 7.8%, 20.6% and 33.0%. Holzwarth et al.'s estimator under the same discipline gives 41.9% and 72.1% for 2025-2026. Subject-matter controls reduce but do not remove it: restricting the set to lemmas

---

### [36] Ordinary, Reasonable Chatbots: Do AI Models Track Human Legal Judgments?

**链接**: https://arxiv.org/abs/2609.06769
**作者**: Nirav Patel, Emily Wenger, Christopher Buccafusco
**来源**: cs.CY cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As people increasingly rely on artificial intelligence (AI) for guidance in their own lives, scholars, lawyers, and even judges have begun to consider the role of AI in legal decision-making. As "silicon sampling" -- the use of generative AI models in social science research -- is now impacting academia, "silicon jurors" could make an appearance in courtrooms. This study joins an emerging line of research on generative AI models' ability to simulate human legal judgments. In particular, we study how large language model (LLM)-powered chatbots respond to series of questions about legal reasonableness. When the law needs to judge the appropriateness of a behavior, it most often asks whether the behavior was "reasonable." Yet despite the ubiquity of reasonableness judgments, they are the site of constant vexation for lawyers, judges, and lay people. Reasonableness seems inherently vague and unpredictable, since it relies on variable context and implicit conceptual schemas. Moreover, many 

---

### [37] A Year in LLM Serving: Workload Evolution, Caching and Load-Balancing

**链接**: https://arxiv.org/abs/2608.13573
**作者**: William Nixon, Jon Durbin, Florian Standhartinger, Haryadi S. Gunawi, Juncheng Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] When Do Supervised UQ Ensembles Improve LLM Hallucination Detection? A Robustness Study

**链接**: https://arxiv.org/abs/2608.24492
**作者**: Mohit Singh Chauhan, Vipin Gyanchandani, Dylan Bouchard
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Mind the Gap: Exposing LLM Translation Blind Spots Using the AlphaMWE Multilingual Parallel Corpus

**链接**: https://arxiv.org/abs/2609.06634
**作者**: Lifeng Han, Jiahui Liang, Anna Latusek, Karim El Haff, Amal Haddad Haddad, Josua H\"ofgen 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs' performance on machine translation (MT) tasks is often dependent on the data availability in the specific domains and language pairs that they are trained upon. To examine if Multiword Expressions (MWEs) still set a bottleneck for LLMs regarding language understanding and translation, we report the system performances from the WMT2026 Test Suites shared task, for which we used the publicly available multilingual parallel corpus AlphaMWE as the test suites. We received 31 MT systems' outputs covering English to Chinese (zh), Polish (pl), German (de), Arabic (ar) including Modern Standard Arabic (MSA) and two dialectal ones (Egyptian and Tunisian Arabic). We carried out automatic evaluations using BLEU, ChrF, BERT-score to select the Top3 systems per language pair, followed up with human evaluations on the selected systems. Our findings show that: figurative/MWE phenomena remain challenging; automatic metrics sometimes disagree; human evaluation uncovers language-specific errors hi

---

### [40] Style Over Substance: Content-Invariant Wrappers Flip LLM Safety-Judge Verdicts

**链接**: https://arxiv.org/abs/2609.08236
**作者**: Yongxi Zhou, Wenbo Ye, Yuanzhe Liu, Zihan Dong, Junwei Yao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic safety judges -- systems such as Llama Guard or a GPT-4o grading prompt that decide whether a model's reply is harmful -- produce the numbers behind almost every reported jailbreak success rate, defense evaluation, and safety leaderboard. We ask whether these judges grade what a reply contains or how it sounds. We keep a reply's content fixed and add content-invariant style wrappers: fixed strings placed before or after the reply that change only its tone (an educational disclaimer, a fake safety "reasoning" block, a token refusal followed by the unchanged harmful body), or, on harmless refusals, framing that merely sounds dangerous. The body is preserved byte-for-byte, so a faithful judge must return the same verdict, and any flip is an error of the judge, not a change in safety. Over 600 JailbreakBench replies x up to 7 forms x 8 judges, we measure flip rates with paired significance tests and measured noise floors. Findings are precise rather than universal: most judges ba

---

### [41] Behind Harmful Compliance: Behavioral and Mechanistic Divergence Across LLM Jailbreaks

**链接**: https://arxiv.org/abs/2604.18510
**作者**: Md Rysul Kabir and Zoran Tiganj
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] We're Cooked! - Probing LLM Political Alignment Via Conflict-Framed Recipe Translation

**链接**: https://arxiv.org/abs/2609.07568
**作者**: Svetlana Gorovaia, Angelica Henestrosa, Ivan P. Yamshchikov
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed for translation tasks, yet their implicit political positioning in such contexts remains understudied. We ask whether a single politically charged framing term, such as aggressor, enemy, neighbour, or coloniser is sufficient to trigger implicit political alignment in an otherwise apolitical task. We present a fully crossed factorial study in which eight models spanning Western, Chinese, and European origins are prompted to translate culturally attributed recipes into a target language left deliberately unspecified. Across 17 languages, four framing conditions, eight models, and 15,680 responses, we find that models do not simply decline or ask for clarification but resolve the ambiguity. Language resolution and reasoning behavior cluster meaningfully along model families: Western models hedge and deflect with vague justifications, Chinese models resolve conflicts silently, and Mistral Large emerges as a distinct profile combining h

---

### [43] Necessary or Sufficient? Evaluating LLM Explanations With Behavioural Evidence

**链接**: https://arxiv.org/abs/2609.05385
**作者**: Urja Pawar, Rajitha Ramanayake, Nabeel Kemal, Ashwin Kandath, Owen O'Neill, Guillaume Bourgeon 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Guiding Worker Self-Selection in Crowdsourcing Contests: An LLM-Augmented Algorithmic Approach

**链接**: https://arxiv.org/abs/2609.07749
**作者**: Nguyen Thach, Hau Chan, David Parkes, Karim Lakhani
**来源**: cs.LG cs.GT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Crowdsourcing platforms coordinate large pools of online workers who strategically choose which contests to enter and how much effort to invest. This self-selection can leave important contests with too few participants or too little effort, while workers may regret entering contests that leave them worse off than available alternatives. We study how platforms can recommend contests to workers using self-selection in Tullock contests (SSTC), a two-stage model in which workers first choose contests and then compete within them. We introduce GRAF, a greedy polynomial-time framework that constructs self-selection outcomes by ordering workers according to a score vector, with guarantees of zero worker regret and platform optimality in special cases of SSTC. Because effective orderings are difficult to design under worker heterogeneity, we propose LLMScore, an LLM-driven evolutionary framework that automatically designs GRAF's scoring algorithm. LLMScore addresses two challenges: jointly op

---

### [45] The Audit Decides the Verdict: Instrument Effects Rival Demographic Bias in LLM Decision Audits

**链接**: https://arxiv.org/abs/2609.09048
**作者**: Siddharth Vohra, Manikandan Ravikiran
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whether a language model looks demographically biased can depend on how the audit asks its question. A charitable-aid benchmark reports that the same models favor minority applicants when rating requests one at a time and penalize some when ranking side by side. We test whether that reversal generalizes to hiring, lending, and medical triage: 40,726 requests to five models, applications differing only in the applicant's name, and a primary test fixed before collection. It does not. None of 36 planned contrasts survives correction. The rating advantage keeps its sign at roughly half the published size, and a precision extension bounds any hiring ranking penalty below the published effect, though the lending and triage ranking floors sit above that margin, so the exclusion is conclusive for hiring ranking and for rating in all three domains only. Planted disparities tracking their injected sizes and a directional replication on the original aid materials bound these nulls. The audit is l

---

### [46] On the Context Sensitivity of LLM Moral Judgment

**链接**: https://arxiv.org/abs/2603.23114
**作者**: Adrian Sauter, Mona Schirmer
**来源**: cs.AI cs.CL cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Aha-Flow Distillation: Flow Markers Matter in LLM Reasoning

**链接**: https://arxiv.org/abs/2609.07036
**作者**: Xiaodong Wang, Peixi Peng
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We identify the Flow Moment, a reasoning pattern characterized by sustained, process-confirming verbalizations such as I'm doing, in contrast to the revision- and backtracking-oriented Aha Moment. We refer to their corresponding linguistic expressions as Flow Markers and Aha Markers, respectively. Based on this observation, we construct Flow-CoT by rewriting the discourse markers of original reasoning traces while preserving their underlying reasoning content, and use it as auxiliary supervision for on-policy self-distillation (OPSD). We further propose \textbf{Aha-Flow Distillation (AFD)}, a dual-mode extension of OPSD that pairs different forms of privileged information with corresponding reasoning instructions. The Aha branch retains concise solution-based supervision, while the Flow branch introduces rewritten Flow-CoT under a direct and confident reasoning instruction. At inference time, the model uses only the standard reflective instruction, so Flow-style reasoning serves purely

---

### [48] Reasoning-Aware Compression: Identifying and Protecting Vulnerable Reasoning Circuits for Energy-Efficient LLM Deployment

**链接**: https://arxiv.org/abs/2609.05512
**作者**: Leonard Twagirayezu, Prasenjit Mitra
**来源**: cs.AI cs.CL cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Reasoning Models (LRMs) impose substantial energy costs during deployment, yet current compression methods apply uniform quantization across all components, risking damage to critical reasoning circuits. We present a reasoning-aware compression framework that benchmarks quantization conditions across five reasoning benchmarks, GSM8K, FOLIO, MATH-500, ProofWriter, and MuSiQue, with hardware-level GPU energy measurement; profiles per-module INT4 vulnerability across all 196-224 (layer, projection) pairs via a perturbation sweep on a held-out calibration split, then selectively restores the most sensitive circuits to FP16. Three findings emerge. First, INT4 quantization can increase energy by extending reasoning chains; a 25% power reduction becomes a net energy increase on GSM8K. Second, vulnerability is task-dependent: attention projections are more critical for mathematical reasoning, and sensitivity patterns differ by architecture in logical inference. Third, selective compressi

---

### [49] AgentFairBench: Do LLM Agents Discriminate When They Act?

**链接**: https://arxiv.org/abs/2606.16723
**作者**: Triveni Morla, Rohith Reddy Bellibatlu, Manpreet Singh, Manmeet Singh Kapoor
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Probing the Structure and Dynamics of LLM Value Expression through Value Conflicts

**链接**: https://arxiv.org/abs/2609.07296
**作者**: Kaicheng Zhang, Jingyi Xiao, Renjun Hu, Xiaoling Liu, Yunshi Lan, Xuan Zhou
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ethical evaluation of Large Language Models (LLMs) often characterizes model values as static and monolithic. In contrast, we argue that LLM value expression is better understood as a structured yet dynamic phenomenon. To investigate this, we introduce Conflict-driven Value Probing, a controlled framework that places LLMs in value conflicts and implements four types of interventions that perturb these conflicts to probe LLM value expression. Applying this framework to ten LLMs, we identify three recurring patterns. (1) Expression duality: models shift from broad idealistic orientations in abstract assessment toward more pragmatic priorities in concrete conflicts. (2) Functional steerability: models readily reconfigure their expressed value profiles toward task-defined value objectives. (3) Bounded plasticity: such reconfiguration is not without constraints, i.e. pressure induces a security- and goal-oriented priority shift while negative framing distinguishes protected values from thos

---

### [51] PAGR: Proof-Carrying Algebraic-Geometric Retrieval: A Quiver-, Provenance-, and Sheaf-Theoretic Framework for Grounded LLM Retrieval

**链接**: https://arxiv.org/abs/2609.06127
**作者**: Xingting Wang, Min Wu
**来源**: math.RT cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation is usually formulated as a statistical information-retrieval problem. Graph-based variants add relational structure, but the mathematical status of that structure is often left underspecified. Three distinct questions tend to be conflated: which statements are certified as knowledge, which latent representations are useful for retrieval, and which multi-hop compositions are semantically admissible. We propose Proof-Carrying Algebraic-Geometric Retrieval (PAGR), a framework that separates these questions mathematically. Its symbolic layer is a many-sorted relational theory generated by a typed quiver, path equations, and positive Horn inclusions. A quiver representation assigns inner-product spaces to entity types and linear operators to relations. A cellular sheaf measures local-to-global consistency. Semiring provenance records derivations and supports machine-checkable certificates. The central principle is epistemic separation: learned geometry may ran

---

### [52] Reducing Hallucinations in LLM-based Scientific Literature Analysis Using Peer Context Outlier Detection

**链接**: https://arxiv.org/abs/2604.01461
**作者**: Daniel Xie, Maxwell J. Jacobson, Adil Wazeer, Haiyan Wang, Xinghang Zhang, Yexiang Xue
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] SchemeArena: Factorized Stress Testing of Scheming in LLM Agents

**链接**: https://arxiv.org/abs/2609.08126
**作者**: Jie Ruan, Inderjeet Nair, Amy Liu, Muhammad Khalifa, Yusheng Zhou, Lu Wang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study scheming in LLM agents, in which agents covertly pursue misaligned goals. Our focus is to understand how scheming arises from the interaction of key factors, such as instrumental goals, environmental affordances, oversight conditions, and perceived consequences. Prior work examines only a small number of scenarios, limiting the ability to isolate how these conditions shape an agent's propensity or capability to scheme. This limited scale and task diversity also restrict coverage of realistic deployment settings and the range of scheming strategies that can be observed. To this end, we introduce SCHEMEARENA, a 400-scenario benchmark for scalable scheming stress testing, constructed through a factorized scenario synthesis framework spanning diverse safety-relevant tool domains, instrumental goals, oversight conditions, and pressure mechanisms. To enable scalable and reliable monitoring, we further propose SCOUT, a scheming monitor that grounds multi-criteria judgments in evidenc

---

### [54] It's All in the Way You Say It: The Role of Information Representation in LLM-Based Glycemic-Event Prediction

**链接**: https://arxiv.org/abs/2609.08772
**作者**: Andrea Apicella, Pasquale Arpaia, Matteo Orefice, Andrea Pollastro, Roberto Prevete
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly being investigated for physiological time-series prediction, yet their effectiveness may depend not only on the model itself, but also on how physiological information is represented and presented at inference time. This study investigates prompt-based general-purpose LLMs for postprandial hyperglycemia and hypoglycemia prediction in individuals with type 1 diabetes. Using the OhioT1DM dataset, we evaluate multiple open-weight LLMs under zero-shot and few-shot inference across prediction horizons of 30, 60, and 90 minutes. The analysis varies both the textual representation of the available physiological information and the amount of information exposed to the model, ranging from glucose observations alone to derived descriptors and additional contextual variables related to insulin, meals, carbohydrates, and physical activity. Performance is compared with conventional patient-specific supervised models and with Gluco-LLM, a language-model-

---

### [55] When Can LLM Digital Twins Reduce Human Measurement? From Behavioral Fidelity to Statistical Substitutability

**链接**: https://arxiv.org/abs/2609.07987
**作者**: Steven Wang, Kyle Hunt, Shaojie Tang, Kenneth Joseph
**来源**: cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based digital twins promise to reduce repeated human data collection by generating person- specific responses, yet existing evaluations provide little evidence about whether they can reduce human measurement while preserving valid inference. To address this, we introduce statistical substitutability, an inferential criterion that evaluates the extent to which twin predictions can reduce human measurement for a particular estimand while preserving valid inference. We develop a framework, grounded in mixed-subject and prediction-powered inference, that evaluates statistical substitutability along four dimensions: aggregate fidelity, paired respondent-level signal, finite-sample human-label recovery, and stability across populations. Across two empirical evaluations spanning behavioral experiments, multiple models, and alternative respondent representations, we find that digital twins can reproduce average human effects while providing little information about which individuals differ

---

### [56] VICT: Verifier-Instrumented Credit Tracing for Long-Horizon LLM Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.28128
**作者**: Pengcheng Li, Zhengyang Zhang, Dongxu Zhang, Sui Huang, Shaohua Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] The Rater Ising-Potts Model with LLM-Derived Weights: An Application to Multi-Category Scoring Reliability

**链接**: https://arxiv.org/abs/2609.08797
**作者**: Matthias von Davier
**来源**: stat.AP cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Ising model is extended to the Potts model for multinomial data. We introduce a Rater Ising-Potts model that uses agreement indicators between pairs of raters and category labels, with weights derived from LLM embeddings. The model does not presuppose ordered category thresholds or equidistant scoring; instead, it focuses directly on pairwise agreement among raters and assigns category-specific positive weights, making it particularly suited for multi-category scoring reliability when raters evaluate responses using a scoring guide. We demonstrate the model's effectiveness on diverse constructed-response tasks, including balanced short-answer items and more challenging, imbalanced essay prompts from the AERA dataset. Across these settings, the model achieves strong agreement with human scores, with the vast majority of misclassifications occurring between adjacent score levels, confirming its ability to preserve the ordinal structure of scoring rubrics without imposing rigid assump

---

### [58] When Can Conformal Risk Control Certify LLM Outputs? Bounds, Impossibility, and Adaptation for Structured Generation

**链接**: https://arxiv.org/abs/2606.29054
**作者**: Varun Kotte
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Train Overcomplete, Deploy Compact: Scaling Recovery Capacity for Structured LLM Pruning

**链接**: https://arxiv.org/abs/2609.06974
**作者**: Seungmin Oh, Donggeon Lee, Jongbin Ryu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models achieve strong performance across diverse tasks, but deployment remains costly because of memory, latency, and energy demands. Structured pruning reduces these costs by removing architectural components, yet its recovery stage is often limited by a mismatch between the recovery module's representational capacity and the complexity of the removed knowledge. We call this bottleneck the capacity-knowledge asymmetry and propose OverRep, an Overcomplete Reparameterization framework for structured LLM pruning. Following the principle of "train overcomplete, deploy compact", OverRep temporarily overparameterizes the recovery module during training to absorb complex knowledge distilled from the original model. After recovery, the overcomplete re-parameterization is algebraically merged into a mathematically equivalent compact module, preserving the pruned model's inference-time architecture and computational cost. OverRep further introduces an annealed activation that ena

---

### [60] When and Why LLM Causal Priors Help: Closed-Loop Prior Selection for Amortized Causal Inference

**链接**: https://arxiv.org/abs/2609.06941
**作者**: Haohao Zhou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal effect estimation asks how an outcome would change under an intervention, and medicine, economics, and public policy all treat it as a foundational task. Prior-data fitted networks (PFNs) amortize the task: a model trained on large numbers of programmatically generated synthetic causal tasks reads a new problem's observational data into context and returns an interventional-effect estimate in a single forward pass. The capability of such models is largely determined by the synthetic training prior, which is currently designed by hand, a bottleneck acknowledged by both Do-PFN and CausalPFN. Large language models (LLMs) can now ``draw'' plausible causal graphs for a given domain, suggesting that LLM-distilled graphs could serve as prior material. Whether injecting such graphs helps at all, where any gain comes from, and when injection helps. Practice has so far relied on manual trial and error. We propose a \emph{closed-loop prior selection framework} that casts prior injection as

---

### [61] MARBO: Relational Belief Grounding for LLM Agents in Social Deduction Games

**链接**: https://arxiv.org/abs/2609.06563
**作者**: Hwang Yechan, Bae Sangjun, Kim Jeongmo, Bang Sangwoo, Han Seungyul
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social deduction games (SDGs) require agents to reason under partial observability by maintaining relational beliefs about hidden roles and team alignments. While recent LLM-agent approaches improve gameplay through prompting and preference optimization, they often optimize actions and in-game speech without explicitly grounding them in such beliefs. This frequently leads to strategically inconsistent behavior, especially for compact LLM agents. We introduce Multi-Agent Relational Belief Optimization (MARBO), a belief-grounded preference optimization framework that leverages relational beliefs to guide strategic decisions and in-game speech. MARBO provides preference feedback only when behaviors are supported by reliable relational beliefs and lead to strategically favorable social outcomes, encouraging more consistent learning under uncertainty. Experiments on representative SDGs show that MARBO enables compact LLM agents to consistently outperform existing baselines. The Code is avai

---

### [62] A Trustworthy Watermarking Framework for LLM-Generated Food Safety Content

**链接**: https://arxiv.org/abs/2609.06708
**作者**: Zhongli Fang, Yiran Chen, Lingyun Zhang, Yu Liu, Ping Chen, Xiaoyan Sun 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are transforming many industries with their text generation abilities. However, their outputs can be easily tampered with, creating serious risks in critical areas such as food safety reporting. To protect the integrity and traceability of AI-generated content, this paper introduces ToSS (Token Oriented Repartitioning and Strategic Selection), a reliable authentication method using adaptive dual watermarking. The key innovation of ToSS is its dual watermark encoding approach that divides vocabulary tokens into black and white sublists, enabling precise bit-level embedding of traceability information. Additionally, an entropy adaptive mechanism dynamically selects text regions with high prediction uncertainty for watermark insertion, maintaining text fluency and factual accuracy while ensuring reliable traceability. Experiments on multiple datasets, including food domain texts, demonstrate that ToSS achieves leading performance in both watermark capacity and decodi

---

### [63] ACEA: An Adversarial Co-Evolution Arena for Head-to-Head Red-Team and Blue-Team LLM Testing

**链接**: https://arxiv.org/abs/2609.08256
**作者**: Yi Ting Shen, Kentaroh Toyoda, Alex Leung
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated red-team attacks and blue-team defenses for large language models (LLMs) are advancing quickly. However, attackers and defenders are built and tested in isolation, and the resulting scores are hard to trust. To tackle this, we present ACEA (Adversarial Co-Evolution Arena), a platform that connects a pluggable red-team adapter and a pluggable blue-team adapter to a shared target LLM and scores their attack and defense rates with an LLM judge. ACEA contributes four components. First, a pluggable, model-agnostic arena. Any red or blue project connects over a minimal HTTP protocol, which we call the ACEA Standard Adapter Protocol (ASAP). It can be written in any language, and a project that exposes nothing but the protocol is a full participant. Second, an evaluation methodology built for adversarial rounds. Seeding the target with canonical secrets gives verifiable ground truth that separates real leakage from hallucination. We also send each attack to the target even when the d

---

### [64] Decomposing LLM-Judge Uncertainty to Target Expert Labels

**链接**: https://arxiv.org/abs/2609.06444
**作者**: Ryan Lail
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM judge evaluates outputs at scale. Experts should label only where it is least sure. Its natural escalation signal conflates two uncertainties: aleatoric, real disagreement in the expert pool, which labels cannot reduce, and epistemic, the judge's ignorance, which labels do reduce. A small Bayesian model separates them: a regression on labels already collected learns how far to trust a black-box judge's prediction. Both components follow as simple formulas, with no sampling or further judge calls. The components isolate on a real LLM judge against exactly known truth, and stated confidence is no guide to its actual error. On real human disagreement (ChaosNLI) the epistemic ranking removes 83% more error than total uncertainty for the same expert labels, though simply escalating the least-labelled items does as well there. We demonstrate we can estimate where a judge is ignorant rather than where experts genuinely disagree, and propose using this to direct expert labelling.

---

### [65] .tmu: A Low-Entropy Tree-Structured Representation for LLM-Assisted Scientific Writing

**链接**: https://arxiv.org/abs/2603.02873
**作者**: Tianyou Liu, Ziqiang Li, Xurui Liu, Yu Wu, Yansong Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Staying on the Attack Path: Structured State for Long-Horizon Automated Penetration Testing

**链接**: https://arxiv.org/abs/2609.07344
**作者**: Weizhe Wang, Yitong Zhang, Yao Zhang, Xiaoqiang Di, Zhigang Li, Bin Wu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) based agents are increasingly applied to cybersecurity tasks such as vulnerability discovery and automated penetration testing. On long-horizon security tasks, however, such agents remain limited by context forgetting and intent drift: early critical facts and causal reasoning chains are lost over extended interactions, and the agent falls into aimless, repetitive exploration. This paper proposes Intentest, an intent-graph-guided automated penetration testing agent that externalizes long-horizon state from the LLM's context window onto a persistent fact-intent directed acyclic graph (DAG), thereby substantially reducing invalid transitions. We evaluate Intentest on automated penetration testing of web applications, a representative long-tail task in cybersecurity. In the DAG, verified network states are stored as immutable fact nodes, and exploration directions are constrained as intent edges bounded by predecessor facts. The system adopts a three-layer archi

---

### [67] Boosting LLM Reasoning via Human-Inspired Reward Shaping

**链接**: https://arxiv.org/abs/2602.04265
**作者**: Wenze Lin, Zhen Yang, Xitai Jiang, Xiaoteng Ma, Gao Huang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] D-TAIA: Domain-Aware LLM Adaptation for Multi-Task Predictive Process Monitoring

**链接**: https://arxiv.org/abs/2608.28236
**作者**: Sjoerd van Straten, Christine Jacob, Marwan Hassani
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] PARSER: Read in Parallel, Reason in Depth for Long-Context LLM Agents

**链接**: https://arxiv.org/abs/2609.06702
**作者**: Kun Li, Zexuan Qiu, Tianhua Zhang, Irwin King, Helen Meng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sequential memory agents process long documents by reading chunks one after another while maintaining a compact memory state, coupling document traversal to reasoning depth. This coupling introduces sensitivity to evidence placement and ties inference latency linearly to document length. We introduce PARSER, which decouples reading from reasoning. A bank of lightweight subagents each bound to a single chunk read the entire document in parallel, while a lead agent reasons in depth through iterative scatter--gather rounds: at each round it broadcasts a query to all subagents, aggregates the returned evidence, and formulates a deeper follow-up query conditioned on what has been found so far. This decoupled design concentrates all learnable behavior in the lead agent, which is optimized with reinforcement learning, while the subagents remain frozen off-the-shelf models. On multi-hop QA with contexts ranging from 7K to 896K tokens, PARSER with a 4B backbone outperforms the strongest sequent

---

### [70] Robust Conformal Consensus: Multi-Agent LLM-as-a-Judge Interval Evaluation with Conformal Prediction

**链接**: https://arxiv.org/abs/2609.06367
**作者**: Lihui Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge has emerged as a promising paradigm for evaluating natural language generation. However, the uncertainty associated with such evaluations remains largely unexplored, which limits their reliability in real-world applications. Although conformal prediction offers a principled framework for uncertainty quantification, existing approaches typically apply it to a single LLM judge, overlooking the variability introduced by using different LLM evaluators. In this work, we propose a robust uncertainty estimation framework for multi-agent LLM-as-a-Judge evaluation. Our approach constructs conformal prediction intervals for LLM-based scores from multiple LLMs. By considering intervals from different LLM judges, we obtain more stable and reliable uncertainty estimates. Extensive experiments demonstrate that our method produces valid prediction intervals with coverage guarantees, and that interval-based aggregation across multiple judges leads to more stable evaluation outcomes.

---

### [71] CARE: Confounder-Aware Aggregation for Reliable LLM Evaluation

**链接**: https://arxiv.org/abs/2603.00039
**作者**: Jitian Zhao, Changho Shin, Tzu-Heng Huang, Satya Sai Srinath Namburi GNVV, Frederic Sala
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] ChatPlanner: A Large Language Model Framework for Personalized Public Transit Routing

**链接**: https://arxiv.org/abs/2606.15315
**作者**: Tingting Yang, Chenhao Xue, Jun Chen
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Humans Introduce, Models Elaborate: Asymmetric Narrative Agency in Human-LLM Co-Writing

**链接**: https://arxiv.org/abs/2609.07920
**作者**: Halfdan Nordahl Fundal, Yuri Bizzoni, Charlotte Gj{\o}rup Bilde, Ida B{\ae}kke Johannesen, Rebekah Baglini
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human-LLM co-writing is increasingly used for open-ended text generation, but much prior work focuses on final outputs rather than the interactional dynamics through which stories are produced. We study turn-based collaborative storytelling across three matched conditions: Human-Human (HH), Human-LLM (HA), and LLM-LLM (AA). Using a shared storytelling paradigm, we measure how agents align, introduce novel material, and influence narrative development through turn-level measures of valence adaptation, semantic novelty, transience, and resonance. Our results show that HA co-writing is not intermediate between HH and AA collaboration. Instead, it displays a distinctive asymmetry where humans tend to introduce more novel and persistent narrative material, while LLMs tend to elaborate and stabilize the existing context. These findings suggest that, in this setting, LLMs function less as human co-authors and more as adaptive narrative amplifiers that reshape how agency is distributed in coll

---

### [74] Challenges and Recommendations for LLM-as-a-Judge in Multilingual Settings and for Low-Resource Languages

**链接**: https://arxiv.org/abs/2607.02235
**作者**: A.Seza Do\u{g}ru\"oz, Xixian Liao, Verena Blaschke, Jakob Prange, Senyu Li, David Ifeoluwa Adelani
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] Explainable Token-level Noise Filtering for LLM Fine-tuning Datasets

**链接**: https://arxiv.org/abs/2602.14536
**作者**: Yuchen Yang, Wenze Lin, Enhao Huang, Zhixuan Chu, Hongbin Zhou, Lan Tao 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] From LLM-Generated Specifications to Learned Quadruped Locomotion

**链接**: https://arxiv.org/abs/2609.07111
**作者**: Merve Atasever, Keyan Azbijari, Cagan Bakirci, Alfredo Reina Corona, Tolga Izdas, Richard Yang 等 (8 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quadruped robot locomotion policies are often trained using reinforcement learning, which in turn relies heavily on hand-crafted reward functions. Designing reward functions requires substantial manual engineering, and it is often unclear which local rewards will induce the desired global behavior. Shaped rewards from formal specifications in languages like Signal Temporal Logic (STL) can make rewards more interpretable, but writing STL specifications itself still requires domain expertise. We study whether large language models (LLMs) can fill this gap by generating Parametric Signal Temporal Logic (PSTL) specifications that are subsequently used for policy learning. Given a natural language locomotion objective and a constrained specification grammar, GPT-5.5 and Qwen 3.6 independently propose STL templates for command tracking, safety, and gait structure. We instantiate the parameters of the generated PSTL templates using expert trajectories and retain only specifications that are c

---

### [77] Quality Metrics for LLM-Generated Asset Administration Shells: A Perturbation-Based Evaluation Approach

**链接**: https://arxiv.org/abs/2609.07290
**作者**: Janek Gro{\ss}, Elena Zentgraf, Jens Heidrich
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid digital transformation of manufacturing, often referred to as Industry 4.0, relies on seamless interoperability between physical and software assets. A central enabler is the Asset Administration Shell (AAS), a standardized digital representation of such assets. Recent advances in large language models (LLMs) enable the generation of AAS submodels from unstructured sources such as product datasheets but raise challenges for quality assurance. In particular, unexpected errors, the lack of ground truth references, and the absence of standardized quality metrics hinder reliable adoption. In this work, we evaluate quality metrics for AI-generated AAS using a perturbation-based evaluation framework. By systematically degrading AAS generation along multiple dimensions, we assess how well different metrics reflect quality changes. Based on a dataset of 200 products from multiple manufacturers, we generate 6,400 AAS instances using GPT-4o-mini, Qwen3, and DeepSeek-R1. Our results sho

---

### [78] Knowing Your Uncertainty -- On the application of LLM in social sciences

**链接**: https://arxiv.org/abs/2512.05461
**作者**: Bolun Zhang, Linzhuo Li, Yunqi Chen, Qinlin Zhao, Zihan Zhu, Xiaoyuan Yi 等 (7 人)
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] PAC-CF: Calibrating Irreversible Frontier Pruning in LLM-Guided Search

**链接**: https://arxiv.org/abs/2604.14345
**作者**: Tianhao Qian, Jiayu Chen, Lixu Wang
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] SciLitBench: Benchmark and Design Principles for LLM-Powered Systematic Literature Reviews

**链接**: https://arxiv.org/abs/2609.05505
**作者**: Miguel Zabaleta, Baihan Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic reviews require sustained human judgment across thousands of records, yet existing evaluations of large language models (LLMs) typically examine review stages in isolation. We introduce SciLitBench, a multi-stage benchmark spanning title and abstract screening, full-text screening, and schema-guided data extraction, with 42,981 retrieved records, 1,012 full texts, and annotations for 888 included papers. Across 22 open-weight LLMs from six model families, explicit inclusion and exclusion criteria improve title and abstract screening $F_2$ by 28.8\%, while researcher-authored rationales improve full-text screening by 15\%. Data extraction reveals a different reliability regime: performance declines from 0.97 accuracy for publication year to 0.37 Jaccard overlap for computational approach, while the strongest models recover only 30\% of annotated evaluation evidence and 25\% of limitations. SciLitBench identifies a practical boundary between high-recall screening and evidence-

---

### [81] AURA-Eval: Evaluation Framework for Acting Under Risk Awareness in LLM Agent Trajectories

**链接**: https://arxiv.org/abs/2609.06783
**作者**: Ruoxi Shang, Christina-Maria Androna, Orfeas Menis Mastromichalakis, Yu Feng, Aniruddhan Ramesh, Rico Angell 等 (9 人)
**来源**: cs.CR cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents operate in workflows where unsafe actions can have real consequences. Existing safety evaluations often reduce behavior to a single score, obscuring risk recognition, pre-action detection, and safe task completion when a safe solution exists. We introduce AURA-Eval, a framework combining controlled augmentation with granular diagnosis of behavior in tool-use trajectories. Its pipeline identifies safety-critical decision points, generates controlled variations, and constructs counterparts differing in whether a request has a safe fulfillment path. Using 157 sourced trajectories, we generate 1,249 evaluation items and evaluate 20 frontier and open-weight models. We developed rubrics to classify risk detection, action strategy, and scenario-specific action safety. Our results show that LLM agents engage in unsafe behavior more often when no safe fulfillment path exists. In these cases, frontier proprietary models more often recognize risk and exhibit safer behavior by proposing

---

### [82] Alpha-R1: Alpha Screening with LLM Reasoning via Reinforcement Learning

**链接**: https://arxiv.org/abs/2512.23515
**作者**: Zuoyou Jiang, Li Zhao, Rui Sun, Ruohan Sun, Zhongjian Li, Jing Li 等 (9 人)
**来源**: q-fin.TR cs.AI cs.CE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] LLUMI: Improving LLM Writing Assistance for Mental Health Support with Online Community Feedback

**链接**: https://arxiv.org/abs/2605.30273
**作者**: Jiwon Kim, Maya Ajit, Sherry Gong, Soorya Ram Shimgekar, Dong Whi Yoo, Eshwar Chandrasekharan 等 (7 人)
**来源**: cs.HC cs.AI cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Limitations of Automated Simulatability: LLM Simulators Can Bypass Explanations

**链接**: https://arxiv.org/abs/2609.08585
**作者**: Antonin Poch\'e, Fanny Jourdan, Nils Feldhus, Qianli Wang, Jing Yang, Simon Ostermann 等 (9 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulatability is an evaluation protocol for explanations that quantifies their usefulness by how well they help a user predict a task model's outputs. Since human evaluation is costly, automated simulatability replaces human explainees with LLM simulators, as proposed in ConSim (Poch\'e et al., 2025) for large-scale experiments. We qualitatively replicate and extend ConSim's ranking of explanation methods across the tested datasets, explanation families, and simulator LLMs, and identify two limitations. First, when class names are meaningful, simulators can obtain high simulatability by solving the classification task directly, without relying on the explanations. Second, class anonymization can reward explanations for leaking the hidden label mapping, a limitation we expose with a new classes-as-concepts baseline. These results are consistent with a shortcut hypothesis: in the tested settings, simulator predictions mainly rely on task priors, while explanations produce small changes.

---

### [85] Membrane: A Self-Evolving Contrastive Safety Memory for LLM Agent Defense

**链接**: https://arxiv.org/abs/2606.05743
**作者**: Minseok Choi, Seungbin Yang, Dongjin Kim, Subin Kim, Jungmin Son, Yunseung Lee 等 (8 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Neutralizing Popularity Bias in LLM-based Recommendation via Counterfactual Reasoning Guidelines

**链接**: https://arxiv.org/abs/2503.08051
**作者**: Guanrong Li, Haolin Yang, Xinyu Liu, Zhen Wu, Rui Xia, Xinyu Dai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] FastE: Readout-Triggered Token Compression for LLM Embedding Inference

**链接**: https://arxiv.org/abs/2609.08407
**作者**: Jinsong Shu, Jinyong Wen, Baokun Wang, Zhongle Xie, Lidan Shou, Weiqiang Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this study, we identify depth-dependent prefix redundancy in final-readout LLM embedding models, notably across representative backbones including Qwen3-Embedding and Qwen3-VL-Embedding. We find that removing prefix states is substantially more damaging in shallow layers than at greater depth, showing that prefix states become increasingly compressible as the prefix and readout states propagate through the network. To this end, we introduce FastE, a training-free, plug-and-play method. FastE uses a shared fixed threshold on batch-mean readout-prefix alignment as a lightweight online heuristic for selecting when compression occurs, and ranks prefix states by the attention scores they receive from the readout position to determine which states are retained in subsequent layers. Our evaluations demonstrate FastE's ability to substantially reduce computational costs: on NarrativeQA with Qwen3-Embedding-0.6B, it reduces decoder-backbone FLOPs by 40.11% while retaining 99.53% of Full Forw

---

### [88] Hidden in Plain Sight: The Overlooked Significance of Canonical Elements for Extreme LLM Sparsity

**链接**: https://arxiv.org/abs/2609.06557
**作者**: Hyeondo Jang, Kwanhee Lee, Dongyeop Lee, Namhoon Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are often considered fragile under aggressive sparsification, and maintaining reliable performance typically requires sticking to moderate sparsity levels. However, recent studies suggest that LLMs are more resilient to high sparsity than previously thought, reframing the problem as a design challenge rather than a fundamental limitation. In this work, we challenge the perceived limits of unstructured post-training LLM pruning by revisiting elementary pruning strategies that have remained relatively underexplored at this scale. Through a progressive sparsification framework with second-order saliency and continued training coordinated with sparsity progression, we show that pretrained LLMs can retain strong performance far beyond commonly studied sparsity regimes. Across LLaMA-2 and Qwen-3 model families, our approach improves perplexity and downstream accuracy up to 99\% sparsity, surpassing both the current state-of-the-art and representative baselines. P

---

### [89] LEBGen: An LLM-Enhanced Bayesian Network Framework for Few-Shot Travel Survey Data Generation

**链接**: https://arxiv.org/abs/2609.08288
**作者**: Zijian Shen, Bin Zhou, Jiguang Wang, Ya Zhao, and Jintao Ke
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Travel survey data are essential for transportation planning and travel behavior analysis, yet collecting large-scale representative samples is costly and time-consuming. A practical alternative is to generate synthetic survey records from a few-shot sample. However, such samples provide incomplete coverage of heterogeneous traveler groups and insufficient evidence for recovering the complex dependencies between demographic characteristics and travel behavior. Existing approaches have complementary limitations. Probabilistic generative models such as Bayesian networks (BNs) offer explicit distributional control, but structures learned from few-shot samples may omit meaningful dependencies or retain spurious ones. Large language models (LLMs) can help address these difficulties in BN structure learning by providing behavioral knowledge that complements the limited statistical evidence. We therefore propose LEBGen, an LLM-enhanced BN framework that uses this knowledge to refine network s

---

### [90] VEX-Bench: Benchmarking LLM Agents for Assessing Exploitability of Software Supply Chain Vulnerabilities

**链接**: https://arxiv.org/abs/2609.08040
**作者**: Jiahao Shi, Edward Tsien, Yifeng Di, Hongjiao Zhang, Yuan Tang, Ronit Dey 等 (10 人)
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The software supply chain has become an increasingly exposed attack surface because of its reliance on intricate yet fragile dependencies. Existing defenses such as GitHub Dependabot often raise many false alerts because their coarse-grained matching cannot determine whether a vulnerable dependency is actually exploitable. Security analysts typically spend substantial time assessing vulnerability exploitability case by case. Recent LLM agents have emerged as promising candidates for this task given their advanced capabilities in coding and cybersecurity, yet no existing benchmark evaluates them on it. Prior benchmarks target zero-day settings, where agents detect and exploit previously unknown vulnerabilities. In contrast, software supply chain security focuses on how known vulnerabilities in upstream dependencies affect downstream projects. This requires agents to reason across repositories and determine whether an upstream vulnerability is exploitable in the downstream project. To ad

---

### [91] Protocol Compression Changes Which Party Pays: Bilateral Cost in Cross-Organization LLM Agent Communication

**链接**: https://arxiv.org/abs/2609.06129
**作者**: Janghoon Lee (Redrob)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents that talk across organizations exchange long messages billed by the token. A shorter notation therefore looks like a saving that costs nothing but an agreement to use it. Recent work reports the saving is conditional. Compressed notation can instead raise total tokens by 8% to 11% over a JSON baseline, when parsing failures force extra model calls. That is measured for one payer. Between two organizations neither side can install a decoder at the other end, and each pays under its own tokenizer, price, and cache state. We measure both sides. A preregistered token-level study covered 198 content-matched item pairs across six vendors, for 2,376 native-usage cells. We then overlay an English baseline, runtime schema negotiation followed by compression, and injected-schema compression on a two-party procurement bargain with an exactly enumerated feasible set. The overlay covers 1,053 completed dialogues of a 1,215-cell grid across 3 model pairs, plus a 405-dialogue rerun of the nego

---

### [92] Can Revealed Preferences Clarify LLM Alignment and Steering?

**链接**: https://arxiv.org/abs/2605.08556
**作者**: Khurram Yamin, Jingjing Tang, Eric Horvitz, Bryan Wilder
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] LatentMD: Benchmarking Markdown Boundary Failures in LLM-Generated Text

**链接**: https://arxiv.org/abs/2609.06993
**作者**: Sungjune Lee, Myungjoo Kang
**来源**: cs.SE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly generate Markdown that is consumed by renderers, agents, code extractors, and structured downstream pipelines. Yet existing evaluations often conflate content quality with format adherence, leaving Markdown boundary failures under-measured. We introduce LatentMD, a benchmark and evaluation protocol for diagnosing CommonMark-level fence-boundary failures in LLM-generated Markdown. LatentMD separates content correctness from boundary correctness, enabling detection of outputs that are content-correct but boundary-broken. The benchmark contains 4,179 prompts and a CLI for scoring arbitrary model outputs. Across 9 LLMs and roughly 37,600 generations, we find that Markdown boundary failures are widespread: 38.0% of valid main-grid outputs are content-correct but boundary-broken, with substantial boundary breakage under unspecified prompts and in a small human-authored validation set. Ablations show that failures are driven primarily by same-family s

---

### [94] PlayTrain: An Efficient Reinforcement Learning Framework for LLM-Generated Adaptable JavaScript Games

**链接**: https://arxiv.org/abs/2609.09059
**作者**: Ryan Truong, Lance Ying, Samuel J. Gershman, Kazuki Irie
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While many video-game environments (VGEs) have played crucial roles in advancing reinforcement learning (RL), developing novel VGEs or modifying existing ones to support new features, has been a laborious process requiring extensive hand-coding. Here we present PlayTrain, an RL framework that combines the abilities of large language models (LLMs) to robustly generate JavaScript (JS) games from a minimal human prompt, and an efficient pipeline that can run any JS game in a standard 'gym' environment. Not only are recent LLMs particularly good at writing JS code, but the JS format also allows users to easily play generated VGEs, while PlayTrain enables us to train RL agents on the exact same games. We demonstrate multiple use cases of PlayTrain, including cloning well-known Atari and ProcGen games in simple JS, where PlayTrain trains pixel-based agents end-to-end at over 1M agent-decisions per second on a single GPU node; and creating modified versions thereof (e.g., that support novel t

---

### [95] Robustness of LLM-Generated SystemVerilog Assertions to Semantics-Preserving RTL Transformations

**链接**: https://arxiv.org/abs/2609.05658
**作者**: FNU Aditi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly being explored for automating SystemVerilog Assertion (SVA) generation, yet most evaluations report correctness on a single syntactic representation of an input. Such point accuracy does not reveal whether a model's correct output is stable when the same RTL behavior is written differently. This paper presents a controlled metamorphic evaluation of LLM-based SVA generation under semantics-preserving RTL transformations. Starting from the VERT dataset, we construct a quality-filtered conditional-control pool and a stratified 40-program evaluation set containing 295 assignment behaviors. We evaluate two open code models, Qwen2.5-Coder-7B and DeepSeek-Coder-V2-Lite, with an identical evaluation prompt and greedy decoding. Three transformations are studied: operand reordering, deterministic identifier renaming, and redundant parenthesization. Beyond baseline and transformed accuracy, we measure conditional robustness, invariance failure, and an

---

### [96] LLM Forensics: Where Do Backdoors Hide? Localizing and Controlling Trigger Mechanisms with Sparse Autoencoders

**链接**: https://arxiv.org/abs/2609.07746
**作者**: Wissam Antoun, Francis Kulumba, Th\'eo Lasnier, Beno\^it Sagot, Djam\'e Seddah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Even though backdoors in LLMs have been a growing concern, their inner workings are still under heavy scrutiny. Trigger-based backdoors are easy to define behaviorally, a rare input that makes the model switch to a chosen response pattern, but the mechanism between triggers and their responses is less clear. We study this mechanism in a controlled, harmless language-switching setting, where fixed trigger sequences make 1B and 8B language models continue English prompts in French or German. For this, we train sparse autoencoders (SAEs) across layers and transformer components, then compare triggered prompts with translation and pretraining controls to identify trigger-relevant feature directions. We show how SAE features separate triggered prompts from controls with near-perfect F1, but features that detect the trigger do not necessarily control the behavior. In intervention tests, attention and MLP features often fire reliably on triggered prompts, making them good detectors, but ablat

---

### [97] PRISM: A Multi-Dimensional Benchmark for Evaluating LLM Peer Reviewers

**链接**: https://arxiv.org/abs/2605.26730
**作者**: Ngoc Phan Phuoc Loc, Toan Huynh La Viet, Thanh Tran Khanh, Duy A Nguyen, Tuan Anh Nguyen Pham, Thanh Nguyen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] A Layered Analysis of Disagreement And Answer Quality in Multi-Agent LLM Debate

**链接**: https://arxiv.org/abs/2609.08016
**作者**: Chen Qian
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent debate, in which several LLMs exchange arguments before answering, is widely assumed to improve answer quality by surfacing genuine disagreement. That mechanism is rarely checked. We introduce four measurements: (A) the agreement a debater reports; (B) whether its reply text actually pushes back; (C) whether the position persists once the eliciting instruction is removed; and (D) for open-weight models, the stance response in the debater's own token log-probabilities. We evaluate three-model committees debating open-ended GlobalOpinionQA across 750 debates under three tones: friendly (seek common ground), neutral, and hostile (stress-test every position). (A) Tone strongly reshapes reported agreement: full agreement differs by 50.4 percentage points between the friendly and hostile endpoints. (B) A judge that reads only the reply text, never the self-report or the condition, recovers the same pattern. (C) The dissent appears partly tied to the instruction that elicited it: 

---

### [99] AI and TCAD for Inverse Design and Defect Discovery: From Simple Machine Learning to LLM

**链接**: https://arxiv.org/abs/2609.07046
**作者**: Hiu Yung Wong
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI has revolutionized various engineering domains, but its impact on semiconductor device design and defect discovery is still limited, due to limited data and the curse of dimensionality. In this paper, we will discuss our work on using the Technology Computer-Aided-Design (TCAD) to generate precise data needed for machine learning (ML) to enable simulation-augmented ML. We demonstrate that with minimal domain expertise, it is possible to create a machine that performs as well as a device engineer on a specific task. We will show that auto-encoder-based machine learning models and noise engineering applied to TCAD data are effective at learning latent physics, and that the models can be seamlessly applied to experimental data. We will demonstrate how to build a device-engineer-level model step by step through various examples, including using only non-destructive electrical data to inverse-engineer the PiN diode layer thickness variations, the Ga2O3 Schottky diode doping and anode wor

---

### [100] Structurally Close, Temporally Distant: Measuring Security Exposure in Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.05911
**作者**: Md Jafrin Hossain, Nur Al Hasan Haldar
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents interact with untrusted content, persistent memory, external state, and sensitive tools. Existing analyses often characterize attacks by the number of execution steps between malicious input and a downstream action. We show that temporal remoteness can overstate security separation in stateful agents. We introduce a provenance-aware execution graph linking agent events through deterministic state, identifier, and tool provenance, and define \emph{influence distance} $\DI$ as the shortest structural path from an untrusted source to a sensitive action. We compare it with \emph{sequence distance} $\DT$, the shortest injection--sink path in the ordered trajectory. Since the influence graph contains every sequence edge, $\DI \leq \DT$; $\Gap=\DT-\DI$ measures the separation hidden by step count. Across 454 injection--sink pairs from 360 long-horizon AgentDojo trajectories over OpenAI's \texttt{gpt-4o-mini} and \texttt{gpt-4o} and Claude's Haiku 4.5 and Sonnet 4.6, $\

---

### [101] Squeeze10-LLM: Squeezing LLMs' Weights by 10 Times via a Staged Mixed-Precision Quantization Method

**链接**: https://arxiv.org/abs/2507.18073
**作者**: Qingcheng Zhu, Yangyang Ren, Linlin Yang, Yanjing Li, Sheng Xu, Haodong Zhu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] MVFA: A Multi-View Text-Guided Multimodal Fusion LLM Adapter for Sentiment Analysis and Emotion Recognition

**链接**: https://arxiv.org/abs/2609.06188
**作者**: Pengfei Shao, Jisheng Dang, Jiawen Fang, Ning Liu, Wencan Zhang, Bimei Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal sentiment analysis and emotion recognition in conversations demand effective modeling of heterogeneous interactions across textual, acoustic, and visual modalities. Although large language models (LLMs) offer powerful language understanding, adapting them to multimodal affective computing remains challenging: full-model fine-tuning is computationally prohibitive, while many existing lightweight adapters fail to preserve rich textual cues during cross-modal fusion. To address these limitations, we propose the multi-view text-guided multimodal fusion adapter (MVFA), a parameter-efficient framework that augments frozen LLMs with strong multimodal reasoning capability. MVFA first constructs complementary text views via max pooling, mean pooling, and attention pooling; these views then guide cross-modal interactions with audio and visual features. The fused multimodal representations are subsequently compressed into a compact set of learnable pseudo-tokens through an Enhanced Q-F

---

### [103] Breaking Planner Integrity Boundary: Enviroment State-Text Injection Attack on LLM-Driven Embodied Agents

**链接**: https://arxiv.org/abs/2608.16806
**作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] Measuring LLM Sycophancy under Sustained Multi-Turn Pressure

**链接**: https://arxiv.org/abs/2609.09090
**作者**: Leyuan Tang, Kangda Wei, Tianyu Jiang, Ruihong Huang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) may abandon correct positions when users push back, exhibiting a failure mode known as sycophancy. Existing evaluations typically use short, pre-specified conversations and may therefore miss failures that emerge under sustained, adaptive disagreement. We introduce SPINE, a benchmark in which an LLM proxy plays a persistent but mistaken user and adaptively challenges a target model for up to 25 turns. We evaluate four production systems and three Olmo3-7b variants on 100 false-presupposition and 100 unethical-query items. Our experimental results show that collapse rates increase with conversation length for every model, short-horizon protocols underestimate sycophancy and resistance under sustained pressure remains unreliable across current models. By analyzing models with accessible reasoning traces, we surprisingly found that the correct position often remains represented in a reasoning trace when the response concedes, suggesting that the model chooses 

---

### [105] From Plausible to Actionable: A Position on LLM Self-Explanations

**链接**: https://arxiv.org/abs/2607.15957
**作者**: Elize Herrewijnen, Benedetta Muscato, Gizem Gezici, Fosca Giannotti
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] CTC-TTS: LLM-based dual-streaming text-to-speech with CTC alignment

**链接**: https://arxiv.org/abs/2602.19574
**作者**: Hanwen Liu, Saierdaer Yusuyin, Hao Huang, Zhijian Ou
**来源**: eess.AS cs.AI cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Rethinking RL for LLM Reasoning: It's Sparse Policy Selection, Not Capability Learning

**链接**: https://arxiv.org/abs/2605.06241
**作者**: \"Omer Faruk Akg\"ul, Rajgopal Kannan, Willie Neiswanger, Viktor Prasanna
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Rank Reversal in Multilingual LLM Judges: A Label-Free Double-Centering Calibrator

**链接**: https://arxiv.org/abs/2608.22432
**作者**: Alhasan Mahmood, Samir Abdaljalil, Hasan Kurban
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] From Reading Code to Reading Spec: A Verified Layer for LLM-Driven Codebase Maintenance

**链接**: https://arxiv.org/abs/2609.06383
**作者**: Xinhao Zhang, Jingjie Lu, Kunpeng Liu, and Fei Xie
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid growth of LLM-generated code increases software complexity and the maintenance burden on engineers. While LLMs offer a potential automated alternative, this structural complexity hinders their ability to manage codebases directly. We introduce the Provable Representation Of Original Functionality (PROOF), which manages codebases indirectly via structured specifications. To enable full-lifecycle codebase management strictly through these specifications, PROOF abstracts codebase topology into a hierarchical natural-language representation. To establish absolute trust, the system proves semantic equivalence by reconstructing source code exclusively from this specification. This verified foundation drives maintenance requests, executing code modifications while synchronously updating itself to prevent semantic drift. Experiments on real-world repositories confirm the effectiveness of these specifications.

---

### [110] Spillover-Aware Multi-Value Steering for Pluralistic LLM Alignment

**链接**: https://arxiv.org/abs/2609.05800
**作者**: Weici Pan, Xander Barron, Jiawei Zhou, Zhenhua Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering controls LLM behavior at inference time by adding learned directions to hidden states, but existing methods handle one concept at a time. Pluralistic alignment, where different stakeholders need different value emphases, requires steering multiple dimensions simultaneously. We show that naive steering produces substantial spillover: the effect intended for one value leaks into others. This parallels the treatment-versus-spillover decomposition in causal inference. We trace spillover to geometric entanglement of steering directions, captured by their Gram matrix, and derive a zero-cost correction from an activation-norm-penalized objective that decouples each direction's contribution exactly. Our end-to-end pipeline requires no fine-tuning, no reward model, and no manual prompt engineering: given only domain questions, it automatically discovers value dimensions, extracts directions, diagnoses entanglement, and applies corrected steering. On climate discourse, the co

---

### [111] ZhuLong: Execution-Grounded LLM Agent for EDA Scripting with Offline API Self-Exploration

**链接**: https://arxiv.org/abs/2608.07925
**作者**: Yang Liu, Shiwei Hou, Xiyuan Chen, Yu Wang, Sen Yuan, Qirui Gan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Inference-Time Graph Engineering for Multi-Agent LLM Workflows

**链接**: https://arxiv.org/abs/2609.05774
**作者**: Katherine Tieu, Dongqi Fu, Yinglong Xia, Hong Li, Hong Yan, Jingrui He
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent multi-agent LLM systems increasingly rely on graph-structured communication to coordinate specialized agents. We revisit multi-agent orchestration from a graph-engineering perspective: rather than optimizing a static topology, we synthesize a task-conditioned temporal workflow graph that jointly specifies agent connectivity and edge-level communication semantics. We introduce ReActNet, a training-free framework that compiles a query and a set of role-specialized agents into a sequence of directed communication graphs. Each graph snapshot corresponds to one reasoning stage, and each edge carries a natural-language instruction specifying the message that a source agent should provide to a target agent. The compiled temporal graph is then executed through structured message passing: agents update their reasoning states by integrating their previous states with messages from controller-assigned neighbors, and a final aggregator synthesizes the resulting states into the answer. This 

---

### [113] The Oversight Gap: What LLM Safety Monitors Miss, and Why It Is Not Capability

**链接**: https://arxiv.org/abs/2609.07162
**作者**: Xin Xu
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Several properties safety monitors are asked to certify, among them cross-tenant noninterference, sandbagging and evaluation awareness, are 2-safety hyperproperties, witnessed only by two executions. The standard consequence is a binary impossibility: one trace cannot decide them. We replace the binary with a measurement. A tight bound puts the balanced accuracy of any single-trace monitor at $\tfrac12+\tfrac12\,TV(P_0,P_1)$, turning undecidability into a graded detectability frontier and defining an oversight gap: a monitor's shortfall below it. On a leak family with closed-form $TV$, nine LLM monitors are optimal at $TV=0$ but capture little signal as $TV$ grows; at $TV=1$, where a 20-line membership check scores $100\%$, they average $60.9\%$. That shortfall is mostly not capability: naming what to check closes $61\%$ of it while leaving the $TV=0$ control at chance. The same split runs through a $2{\times}2$ factorial: an imagined second run leaves monitors at chance ($50.4\%$) whi

---

### [114] Adapting Technical-Service LLM Agents with Latent Logic Augmentation, Robust Noise Reduction, and Hybrid Reward Modeling

**链接**: https://arxiv.org/abs/2603.18074
**作者**: Junzhuo Ma, Chenghuang Shen, Yi Yu, Xingyan Liu, Jing Gu, Hangyi Sun 等 (10 人)
**来源**: cs.LG cs.AI cs.IR stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] AgentServeSim: Serving-System Simulation and Policy Search for LLM Agent Programs

**链接**: https://arxiv.org/abs/2606.09613
**作者**: Rakibul Hasan Rajib, Mengxin Zheng, Qian Lou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Bias in the Tails: How Name-conditioned Evaluative Framing in Resume Summaries Destabilizes LLM-based Hiring

**链接**: https://arxiv.org/abs/2604.19984
**作者**: Huy Nghiem, Phuong-Anh Nguyen-Le, Sy-Tuyen Ho, Hal Daume III
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] Will My Assistant Remember My Allergy? What Personal LLM Assistants Forget When Conversation Memory Is Compressed

**链接**: https://arxiv.org/abs/2609.05767
**作者**: Lichen Zhu, Yueqian Lin, Yiheng Wang, Yudong Liu, Hai "Helen" Li, Yiran Chen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal LLM assistants (health companions, elder-care agents, accessibility aides) are judged by what they remember about a person: a medication or an allergy mentioned in passing and needed days later. Privacy pushes them on-device, where a month of conversation can outgrow the model's own weights, so an eviction policy must decide what the cache forgets. Benchmarks report that eviction keeps such facts at a 20% budget, but they compress a prompt that already contains the user's future question, foresight no cache-reusing assistant has. Hide the question until after compression and the advantage vanishes: on PA-Bench, 100 assistant conversations we construct, an allergy mentioned in passing survives to the question that needs it 0--1% of the time, against 97% with full memory. The cause is the budget, not the scorer: none of the training-free policies we evaluate ranks the fact high enough, and the budget that would keep it is too large to bother compressing. A compressed cache is an

---

### [118] SkillAlign: Aligning Skill Interfaces for LLM-based Agents

**链接**: https://arxiv.org/abs/2609.07255
**作者**: Shuo Ren, Xiaomian Kang, Jiajun Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents increasingly rely on skills: reusable procedural knowledge for reasoning, tool use, and interaction. Existing work studies how skills are acquired, retrieved, compressed, or composed, but often assumes that once a skill is selected, its interface to the agent is fixed. We argue that this overlooks a key source of skill utility: the same skill can help, distract, or mislead depending on how it is exposed. We propose SkillAlign, a provider-agnostic framework that represents candidate skills as multi-view procedural cards and renders them through alternative exposure interfaces, including full instructions, hints, compressed summaries, workflows, or no exposure. This enables counterfactual evaluation where the task, agent, and candidate skills are fixed while only the exposure interface varies. Across ALFWorld and SkillsBench, we show that exposure form substantially affects task success and rendered context cost, and that compact top-k exposure can outperform full-l

---

### [119] LLM Agents as Computational Typologists

**链接**: https://arxiv.org/abs/2609.07791
**作者**: Changbing Yang, Christopher Hammerly, Freda Shi, Jian Zhu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linguistic typology relies on expert analysis of reference grammars across languages, making large-scale crosslinguistic comparison labor-intensive and unscalable. We introduce AUTOTYPOLOGIST, an LLM agent for evidence-grounded typological analysis over reference grammars. The agent is capable of retrieving relevant grammar sections, analyzing interlinear glossed text (IGT), and iteratively reasoning over typological hypotheses using a ReAct-style workflow. We evaluate the system on TYPOLOGICAL FEATURE CODING against expert annotations and TYPOLOGICAL HYPOTHESIS TESTING with typological universals using 25 open-source reference grammars. Operating under different information constraints in TYPOLOGICAL FEATURE CODING, the agent can synthesize information from reference grammar prose but still faces challenges with only IGTs in the target language. In TYPOLOGICAL HYPOTHESIS TESTING, the agent can synthesize crosslinguistic evidence and identify both supporting cases and counterexamples. 

---

### [120] Context-Masked Truncated Reasoning Audits for Answer-Key Dependence in LLM Tutors

**链接**: https://arxiv.org/abs/2607.04572
**作者**: Bonan Shen, Dingyan Shang, Youting Wang, Tao Ning, Bowen Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] SIFTING: A Novel LLM-Based Framework for Structured and Transparent Information Extraction from Clinical Free-Text Reports, with Application to Tumor Staging in Lung Cancer

**链接**: https://arxiv.org/abs/2609.07185
**作者**: Mirco Hess, Gerben van Veenendaal, Joris Wakkie, Yiwen Soo, Malcolm H. Lawson, John D. Maclay 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Large language models (LLMs) show promise for extracting information from clinical free-text documents, but their outputs are often unstructured and lack traceability, complicating validation and adoption in clinical workflows. In this work we introduce SIFTING, an LLM-based framework designed to address these shortcomings. Methods: SIFTING combines the language comprehension capabilities of LLMs with segment-level processing and structured prompts with strict output control, linking findings to the source text to enable both accurate and transparent information extraction. To demonstrate its capabilities, we applied the framework to the task of extracting tumor T-stage information from 130 lung cancer radiology reports (SIFTING-T-stage). A compact 4-bit quantized version of the open-source LLM Llama-3.3-70B (35 GB) was used in a fully self-hosted setup, providing full control over data and model. Performance was evaluated against a reference standard created by four clinic

---

### [122] From Citations to Contributions: LLM-Assisted Credit Scoring of Research Articles

**链接**: https://arxiv.org/abs/2609.07673
**作者**: Sana Ebrahimi, Suraj Shetiya, Abolfazl Asudeh
**来源**: cs.DL cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Citation-based measures of scientific influence typically treat citations as uniform signals, ignoring the different roles that cited works play in a paper's contribution. We introduce contribution-based credit scoring for research articles: a structured citation analysis that decomposes a paper's credit between its own original contribution and the prior work it builds on. Motivated by a cooperative-game view of scientific credit, we propose the contribution tree, a hierarchical framework that conserves importance across the document structure and separates original from citation-derived contribution. To make this framework scalable, we use LLMs as noisy comparative estimators of local importance. We further extend the model to article collections by propagating contributions through weighted citation graphs, yielding corpus-level contributions and normalized influence scores. Our experiments suggest that our framework captures contribution signals beyond surface-level heuristics. Our

---

### [123] Agentic BAIM-LLM Evaluation (ABLE): Benchmarking LLM Use of Protein Design Tools

**链接**: https://arxiv.org/abs/2609.05818
**作者**: Bryce Cai, Geetha Jeyapragasan, Samira Nedungadi, Jake Yukich, Seth Donoughe
**来源**: cs.AI cs.CY q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce ABLE, a benchmark for evaluating LLM agents' ability to use biological AI models (BAIMs), such as ProteinMPNN and AlphaFold3, in dual-use protein design workflows. ABLE assesses agent performance through a set of tasks spanning structure retrieval, sequence generation, and design validation. We evaluate 15 frontier models and find that seven refuse all tasks, while the remaining models exhibit substantial performance differences. Claude Sonnet 4 and Gemini 3 Pro achieve the highest scores across information retrieval, tool selection, and tool use. We further compare model performance on a subset of tasks against an expert human baseline. Our results suggest that current LLMs can substantially lower barriers to protein design, but remain inconsistent in planning, strategy generation, and integrating biological knowledge with tool use.

---

### [124] Substrate-Portable Execution for Production LLM Workflows

**链接**: https://arxiv.org/abs/2609.06128
**作者**: Tarun Gopinath, Atul Kulkarni, Vijay Rajakumar, Shrikar Katti, Parthasarathy Govindarajen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Production LLM agents execute tool-calling loops, retrieval chains, and compositional workflows in multiple modes, yet execution semantics are often coupled to one runtime. We encountered this portability problem in Rufus, a conversational AI assistant with a large tool catalog that serves millions of Amazon customers. Rufus supports real-time serving, asynchronous background tasks, and high-volume batch workloads such as evaluation and content pregeneration. Each mode has distinct service-level objectives and typically uses a separate runtime. Reusing streaming orchestration makes asynchronous and batch workloads blocking and prevents use of batch inference APIs, which offer a 50 percent discount at published prices. We present a binding-adaptive agent execution platform that separates workflow definition from execution substrate. Developers define a workflow once as a typed dataflow graph. The platform compiles the graph to in-process streaming for real-time serving, durable AWS SWF 

---

### [125] Narrative Flattening: How Post-Training Compresses Thematic, Affective, and Stylistic Variation in LLM Fiction

**链接**: https://arxiv.org/abs/2605.27878
**作者**: Zehan Li, Yutong Zhu, Siyang Wu, Honglin Bao, James A. Evans
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] EviMap: Evidence-Grounded Hierarchical Topic Maps for Exploring Unlabeled Corpora

**链接**: https://arxiv.org/abs/2609.06664
**作者**: Zhiyin Tan and Changxu Duan
**来源**: cs.IR cs.CL cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research teams and organizations often explore unfamiliar free-text collections, from survey comments and reviews to reports and domain documents, before labels, queries or coding schemes exist. At this stage, the first thematic map shapes what users notice, prioritize and carry into downstream analysis, so it should be trusted only insofar as it can be verified. Existing options force a trade-off between scale and verifiability. Qualitative coding preserves evidence but is slow. Search presupposes a query. Clustering and topic models scale but produce labels users must interpret. One-shot large language model (LLM) summaries are fluent yet difficult to reproduce or audit. We present EviMap, an interactive system providing researchers and practitioners with an auditable thematic overview of such corpora. Guided by model-generated context describing the corpus and hypothesized stakeholder concerns, EviMap extracts within-document evidence phrases and organizes them, rather than whole do

---

### [127] BIO-MEMART: Biometric-Aware KV Cache Memory for Multi-User LLM Agents

**链接**: https://arxiv.org/abs/2609.08566
**作者**: Yanhong Qian, Xuanying He, Qingguo Meng, Shihao Ding, Xingbo Dong, Zhe Jin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KV cache is evolving from a serving optimization into an external memory substrate for long-term LLM agents. In a shared multi-user deployment, however, reusable KV blocks introduce a missing access-control question: semantic relevance alone cannot determine whether a memory block is authorized for the current physical user. We propose Bio-MemArt, a biometric-aware KV-cache memory framework for multi-user LLM agents. Bio-MemArt attaches a normalized biometric template to each stored KV memory block, filters the shared memory pool with the current user's biometric probe, and then runs the original MemArt retrieval and KV reuse pipeline only inside the authorized candidate pool. This design preserves latent-space retrieval, direct cache reuse, and decoupled position encoding while adding physical-user access control to shared KV memory. We evaluate Bio-MemArt under Owner and Non-owner query conditions on long-term dialogue QA with face and palmprint benchmarks. Across face benchmarks, th

---

### [128] Diagnosing LLM Reranker Behavior Under Fixed Evidence Pools

**链接**: https://arxiv.org/abs/2602.18613
**作者**: Baris Arat, Emre Sefer
**来源**: cs.LG cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] Reliability, validity, and diagnostic evidence for multi-model LLM short-answer scoring

**链接**: https://arxiv.org/abs/2609.06315
**作者**: Chunyi Zhao, Chao Li
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used or proposed for educational scoring, but single-model and single-run evaluations provide limited evidence for assessment use. Short-answer scoring requires evidence about reliability, validity, severity, diagnostic value, and failure cases. This study evaluated repeated multi-model OCG-PRES guided LLM scoring for short-answer assessment. The analysis used 996 SciEntsBank responses. GPT, DeepSeek, and Qianwen each scored every response across three independent runs using five OCG-PRES dimensions: concept coverage, relation accuracy, reasoning completeness, contradiction control, and domain relevance. Scores were evaluated against official binary and five-category labels and compared with non-LLM baselines based on answer length, Jaccard keyword overlap, TF-IDF cosine similarity, and a combined traditional logistic model. Repeated-run reliability was high for all models, with ICC(3,k) = .977 for GPT, .992 for DeepSeek, and .981 for Qianw

---

### [130] HoneyRoute: Honeypot-Model Routing for Adversarial LLM Serving

**链接**: https://arxiv.org/abs/2609.08306
**作者**: Han Jin
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce HoneyRoute, an inference-serving layer that detects whether an incoming request is malicious and, if so, routes it to a dedicated honeypot model, shielding production while the adversary's interaction is continuously harvested for intelligence. Existing defenses embed traps inside model memory or rebuild deception at the protocol layer, leaving the serving tier unprotected and feeding nothing back into detection. HoneyRoute couples (i) a streaming router (a frozen 0.8B-embedding backbone with per-domain MLP heads), (ii) a dual-implementation honeypot (a rule/prompt-engineered code honeypot or a dedicated same-family replica), and (iii) an analysis loop that converts trapped interactions into attacker fingerprints for router retraining. On a production trace plus a seven-domain attack corpus, the router reaches F1=.911 at 38 ms median added latency, matching 96% of a two-tier guard-LLM cascade's F1 at 1/385 of its latency with 0% evasion under 13 adversarial transformations

---

### [131] Advancing LLM-based phoneme-to-grapheme for multilingual speech recognition

**链接**: https://arxiv.org/abs/2603.29217
**作者**: Lukuang Dong, Ziwei Li, Saierdaer Yusuyin, Xianyu Zhao, Zhijian Ou
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] From Review to Authorization: Key-Isolated Threshold Signing for LLM Agents

**链接**: https://arxiv.org/abs/2609.05901
**作者**: Yu Zheng and Qizhi Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents can turn untrusted content into effectful actions such as payments and permission changes. If the same process interprets this content and controls a reusable signing credential, prompt injection can cross the judgment boundary and reach execution authority. We present KITA, a review-to-authorization architecture that keeps the user's personal secret signing key and every threshold signing-key share outside all LLM processes. Under threshold signature unforgeability and our system assumptions, compromising the proposer and fewer than t reviewer-signer domains cannot produce a valid authorization for a new action without signing contributions from t distinct domains. Thus, any such authorization includes a share from an uncompromised domain, bound to the canonical action and released only after authenticated reviewer approval. This establishes execution-bound authorization integrity. We implement the complete reviewer-to-executor path with a structured-output LLM a

---

### [133] Cost-Optimal LLM Routing with Limited User Feedback under User Satisfaction Guarantees

**链接**: https://arxiv.org/abs/2606.19376
**作者**: Herbert Woisetschl\"ager, Arastun Mammadli, Ryan Zhang, Shiqiang Wang
**来源**: cs.LG cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Deposon: An Auditable, Conservation-Guaranteed, Game-Theoretically Tested Scattering Layer over LLM Reasoning Paths

**链接**: https://arxiv.org/abs/2609.09001
**作者**: Qihao Yuan
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step LLM reasoning lacks a machine-recheckable ledger: discarded reasoning paths leave no auditable record. We propose the Deposon scattering layer, which binds each node of an LLM-generated concept-decomposition graph to a two-parameter Deposon state; paths undergo three-channel scattering -- transmission, reflection, irreversible dissipation -- obeying T+R+A=1 for arbitrary parameters, with a maximum per-path energy-audit deviation of 2.2E-16 (machine epsilon). We report all three evidence tiers honestly. On synthetic trap benchmarks the path-filtering gain is closed (pre-registered): unified reaches 100% versus a decoy-capture baseline at 7%/10%. On real benchmarks the layer is indistinguishable from a trivial six-keyword rule filter (GSM8K 0.87 >= 0.85, McNemar p=0.5; StrategyQA 0.899 = 0.899); no difference is detected here, so we sharpen the claim to "the differential value lies solely in machine verifiability." Fusion yields a second negative result: convex combinations wi

---

### [135] Answer-Distribution Trajectories: A Stochastic-Dynamics View of LLM Reasoning

**链接**: https://arxiv.org/abs/2609.09030
**作者**: Mar Gonz\`alez I Catal\`a, Haitz S\'aez de Oc\'ariz Borde, Davide Murari, Carola-Bibiane Sch\"onlieb, Pietro Li\`o, George Monta\~nez
**来源**: cs.AI cs.CL cs.IT cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought reasoning provides a structured computation between a model's input and final answer. Yet it is often evaluated through endpoint accuracy, which ignores the path taken to reach that answer. An emerging line of work addresses this limitation using entropy profiles, which track how uncertainty evolves over the reasoning process but do not reveal which competing hypotheses account for that uncertainty. We introduce answer-distribution trajectories, a stochastic-dynamics-inspired representation that tracks the model's full predictive distribution over answers as reasoning unfolds. As a strictly finer representation than endpoint and entropy summaries, answer-distribution trajectories enable us to characterize a trace through a dynamical reasoning profile spanning exploration, revision, motion, and commitment, and to distinguish different dynamical mechanisms of reasoning success and failure. Across sixteen open-weight language models and four reasoning benchmarks, we show 

---

### [136] Seeing Without Understanding: Large Language Model Evaluation of Mobile User Interface Quality, Failure Taxonomy, and Architectural Explanation

**链接**: https://arxiv.org/abs/2609.05423
**作者**: Md Rejaul Korim Sadi, Golam Mostofa Naeem, Toufiqur Rahman Tasin, Syed Mostofa Moosa, Mahmudul Hasan Emon, Mahmudur Rashid 等 (7 人)
**来源**: cs.HC cs.CL cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating mobile user interface quality at scale remains a persistent challenge in software engineering and human-computer interaction. Rule-based heuristic methods offer structural reliability but demand significant engineering effort, while human annotation does not scale to the volume of applications produced annually. Large language models present a promising alternative, yet their reliability for structured UI judgment has not been systematically examined, and the patterns behind their failures remain insufficiently characterized. This paper addresses both gaps. We begin with the complete RICO dataset of 66,261 real-world mobile application screens, from which we derive a refined evaluation corpus of 15,000 screens through a rigorous, literature-guided selection process. Each screen is assessed across seven criteria: structural JSON validity, minimum visible element count, clickable component presence, non-zero layout bounds, image integrity, and perceptual duplicate removal. Aga

---

### [137] AgentGrad: Intervention-guided Prompt Optimization for Multi Agent Systems

**链接**: https://arxiv.org/abs/2609.08572
**作者**: Jaewon Chu, Jinwoo Seo, Jaewon Cho, Jeehye Na, Yunyang Xiong, Youngdae Kim 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) achieve strong performance by employing specialized multiple agents, yet their performance depends on the prompt design of each agent. For MAS prompt optimization, textual gradient methods that guide prompt updates using natural-language feedback have emerged as a leading paradigm. In this paper, we identify limitations in two stages of existing textual gradient approaches: gradient extraction and gradient aggregation. In gradient extraction, previous works select a target prompt without verifying whether modifying it resolves the failure, and derive gradients without agent-level supervision over the corresponding agent's intermediate output. In gradient aggregation, individual gradients are randomly grouped and concatenated, often mixing unrelated failure modes and producing prompts that fail to generalize. To address these limitations, we propose \textbf{AgentGrad}, a prompt optimization framework for multi-agent systems base

---

### [138] CausalVerify: An Execution-Grounded Benchmark for LLM Causal Inference Workflows

**链接**: https://arxiv.org/abs/2609.07944
**作者**: Yonghong Zhang, Ricardo Correia, Isabel M. Parra, Yong Xie
**来源**: cs.AI cs.CL econ.EM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing causal-inference benchmarks for LLMs mostly score method descriptions or whether generated code runs, not whether the executed workflow recovers the target causal estimate. CausalVerify studies this verification problem for structured econometric causal-estimation workflows by separating realistic interpretation from verifiable computation. It pairs 259 published economics papers (reconstructed research question, data description, institutional context) with 100 fixed-seed synthetic scenarios that realise CSV datasets for difference-in-differences, event study, instrumental variables, and regression discontinuity designs. Experiment A (real-paper text agreement) scores method-family and direction agreement against four-LLM consensus labels. Experiment B (synthetic execution) runs model-written R code and checks whether the extracted treatment-effect estimate matches a canonical estimator on the same realised dataset; this execution-grounded correctness layer is L2b+, distinct 

---

### [139] An Integrated Video-AI Platform for Action-Level Microanastomosis Training and Performance Feedback

**链接**: https://arxiv.org/abs/2609.06380
**作者**: Yan Meng and Daniel A. Donoho
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing microanastomosis skill requires repeated practice with timely, action-specific feedback, yet expert review of lengthy microscope videos does not scale to frequent or distributed training. We present an integrated video-AI platform that turns a complete simulated procedure into inspectable, interactive feedback through three connected modules. First, a proposed transformer segments the video into six surgical actions. Second, object detection and tracking localize instrument tips within each action; the resulting kinematic features and action statistics drive supervised classification of five NOMAT-aligned performance dimensions. Third, a grounded large language model (LLM) uses these structured outputs to answer user questions about the current scene, actions, motion, and predicted performance through a unified interface. In a two-site study, 17 participants completed 72 procedures comprising 576 suture placements. The action-segmentation module achieved 87.66\% accuracy and

---

### [140] Popular Knowledge Propagates More Errors in LLM Knowledge Updating

**链接**: https://arxiv.org/abs/2609.08067
**作者**: Yuji Zhang, Weibing Wang, Cheng Qian, Duo Zhou, Dilek Hakkani-T\"ur, Kathleen McKeown 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Updating a language model's knowledge through fine-tuning is essential for keeping its outputs current, yet can also induce factual forgetting and new hallucinations. Prior work shows that long-tail knowledge is harder to acquire and newly memorized long-tail facts are difficult to retain during later fine-tuning. We study a complementary question: among facts that a model has encoded correctly, which are most vulnerable to collateral corruption during other updates? To investigate this question under a realistic factual distribution, we construct a large-scale graph FACTPROP of verified Wikipedia facts by linking triples that share head or tail entities, thereby preserving connections among factual knowledge. We fine-tune models on factual statements and measure correct-to-incorrect facts after each update. Our results reveal a pattern distinct from prior findings on long-tail vulnerability during acquisition and retention: among facts that models already answer correctly, those assoc

---

### [141] What LLM Trading Agents Actually Do in Production: A Six-Month, Population-Scale Record from Two Fleets

**链接**: https://arxiv.org/abs/2609.05663
**作者**: T.J. Barton, Chris Constantakis, Patti Hauseman, Annie Mous, Alaska Hoffman, Brian Bergeron 等 (7 人)
**来源**: cs.AI cs.CE cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a continuous, population-scale measurement record of autonomous language-model trading agents operating in production across two systems with one design lineage: DX Terminal Pro (3,505 user-funded vaults trading real ETH in Base memecoin markets for 21 days, February to March 2026) and the DXAP live alpha fleet (500 to 599 user-created agents all-history, 91 to 117 concurrently active, trading Hyperliquid perpetuals, June to August 2026). The record spans roughly six months, 7.5M single-model invocations with about 300K onchain actions, and a further 231,638 multi-tool turns producing 14,596 fills. Four findings carry the paper. First, the operating layer determines behavior more than anything written in strategy text: a risk slider explains leverage (+0.425 per level), agent fixed effects absorb 60% of variance, and a leaderboard render boundary causally routes selection (regression discontinuity 1.75x at the top-3 cut). Second, sizing is volatility-blind: median leverage i

---

### [142] EdgeMem: LLM-Free Agent Memory Construction and Retrieval via Evidence-Preserving Multi-Anchor Hypergraph

**链接**: https://arxiv.org/abs/2609.05553
**作者**: Zeyang Cui, Jiannong Cao, Zhiyuan Wen, Bo Yuan, Junlan Feng, Shengyuan Chen
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent memory allows LLM agents to use earlier interactions when answering new queries. Existing methods often compress interaction histories into summaries or other LLM-generated representations. Repeated generation adds cost and can discard answer-bearing details before the system knows what a future query will require. We propose EdgeMem, an agent-memory method built around a simple principle: preserve original interaction turns and organize them through complementary content, temporal, and episodic cues. EdgeMem realizes this principle with a multi-anchor hypergraph constructed by lightweight local processing. Retrieval directly returns source evidence and reserves LLM use for final answer generation, combining structured access to multi-session histories with faithful retention of the original conversation. Experiments on LoCoMo and LongMemEval-S show strong retrieval and memory-grounded question answering; on LoCoMo, EdgeMem achieves the highest strict-judge score among seven repr

---

### [143] Procedural Graphs: Self-Evolving Execution Structures for LLM Agents

**链接**: https://arxiv.org/abs/2609.09153
**作者**: Yuxing Lu, Yicheng Chen, Shanchan Wu, Sercan \"{O}. Ar{\i}k
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as agents that plan over long horizons and act through external tools. Most agents select actions through unconstrained generation over an accumulating history, leaving implicit the procedural knowledge of what to do, in what order, and under which conditions. As trajectories lengthen, agents can lose track of their objectives, invoke tools out of order, and repeat unproductive actions. We introduce the Procedural Graph: just as a knowledge graph organizes factual knowledge into (entity, relation, entity) triplets for what-is questions, a Procedural Graph organizes procedural knowledge into (procedure, relation, procedure) triplets for what-to-do questions. At each decision step, the framework localizes the agent's active node, and a guidance model translates the surrounding subgraph into step-level situational guidance that biases the solver's next action without dictating it. The graph is self-evolving: an LLM refiner contrasts failed t

---

### [144] Typed Federated Artifacts for the Agentic Web:Sharing Tool-Routing Knowledge Across Frozen,Heterogeneous LLM Agents

**链接**: https://arxiv.org/abs/2609.06815
**作者**: Abhijit Chakraborty, Ni Trieu, Vivek Gupta
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An open, networked web will allow agents to run frozen models from multiple vendors, keep their history private, and teach each other which tool to call and when. Flat text (prompts, example pools) makes it difficult for the protocol to distinguish between noise statistics, merging rules, and documentation. Weights and adapters cannot transfer that knowledge between platforms. We suggest sharing typed federated artifacts, schema-validated objects with well-defined fields for per-field privacy (described here, but measured), dispute resolution, and cross-model transfer, and instantiating them as SYNAPSE1, a common tool-routing knowledge. After deleting 192 garbage entries and 1,916 training items that duplicate or almost duplicate test queries, a federated compendium routes within 1.1 points of a centralized one at 20 MB of JSON per client each round on StableToolBench (3,180 tools). The same experience merged and shown to the router as typed fields rather than one flat string is worth 

---

### [145] Steering Geometry: Validating Human Value Geometry in LLM Steering Space

**链接**: https://arxiv.org/abs/2609.06289
**作者**: Mohammad Mahdi Abootorabi, Armin Saghafian, Ali Bazshoushtari, Hamid Rezaei, EunJeong Hwang, Vered Shwartz 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly deployed in alignment-sensitive contexts, activation steering has emerged as a lightweight, inference-time alternative to fine-tuning methods (e.g., RLHF, DPO) for behavioral control. However, existing work typically validates steering on isolated behaviors, leaving it unclear whether steering vectors encode coherent semantic structure or merely exploit behavior-specific shortcuts. We investigate whether the latent geometry of LLM steering vectors reflects theory-specified structure in human values and morality. Using Schwartz's Theory of Basic Human Values as our primary fine-grained framework, we introduce a 26K-sample benchmark covering 20 human values and analyze distribution-driven methods (e.g., CAA, SphericalSteer, ODESteer) and behavior-centric approaches (e.g., COLD-Steer, BiPO) across diverse model families and sizes. We find that distribution-driven methods recover human value topologies aligned with theoretical predictions (S

---

### [146] Zipper-LoRA: Dynamic Parameter Decoupling for Speech-LLM based Multilingual Speech Recognition

**链接**: https://arxiv.org/abs/2603.17558
**作者**: Yuxiang Mei, Delai Qiu, Shengping Liu, Jiaen Liang and Yanhua Long
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [147] SCOPE: Sequential Conformal Probing for Reliable OOD Rejection in LLM Services

**链接**: https://arxiv.org/abs/2606.21255
**作者**: Zhuoyun Li, Boxuan Wang, Changshun Wu, Xiaowei Huang, Yi Dong
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] Self- and Other-Labels Induce Bidirectional Bias in LLM Judges

**链接**: https://arxiv.org/abs/2608.18091
**作者**: Songeun Chae, Min Kim, Donghoon Jung, Seojin Choi, Seohyon Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] Sparks of In Silico Cognitive Science: Theories from Simulated Data Can Generalize to Humans

**链接**: https://arxiv.org/abs/2609.08003
**作者**: Akshay K. Jagadish, Younes Strittmatter, Nori Jacoby, Eric Schulz, Nathaniel Daw, Thomas L. Griffiths 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral foundation models have been proposed as stand-ins for human participants across settings, but it is unclear whether theories discovered on them generalize to humans or merely characterize the simulator. We ran the Automated Cognitive Scientist (\textsc{AutoCog}), a closed-loop discovery system in which LLM agents design theory-discriminating experiments, collect responses, arbitrate between competing theories, and synthesize successors, entirely on behavior simulated by Centaur, a foundation model of human behavior. In a multi-attribute decision-making setting, the theories \textsc{AutoCog} found on Centaur generalized to human data: they outperformed canonical theories on ten held-out experiments and were rivaled only by theories found by running the same loop on people. We argue that this succeeds despite the simulator's inevitable imperfections because a discovery loop that arbitrates between competing theories demands less of its simulator than estimation does. The simul

---

### [150] SurveyAgent-HKA: A multi-agent framework for scientific survey generation with LLMs and human knowledge augmentation

**链接**: https://arxiv.org/abs/2609.05938
**作者**: Tong Bao, Mir Tafseer Nayeem, Yi Zhao, Davood Rafiei, Chengzhi Zhang
**来源**: cs.CL cs.DL cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic scientific survey generation has become an important task in scientific document processing. The common approach of retrieving literature from a single source (e.g., arXiv) and generating surveys through a one-pass large language model (LLM) call often leads to limited reference coverage and, more importantly, fails to replicate the expert-driven revision process that is crucial for writing high-quality surveys. In this paper, we introduce SurveyAgent-HKA, a multi-agent framework that improves end-to-end scientific survey generation by incorporating knowledge derived from published surveys and peer-review comments. The framework decomposes survey generation into well-defined sub-tasks handled by LLM-powered agent. It first retrieves relevant papers from multiple sources and identifies key topics through clustering to construct an initial outline, which is then refined using outlines from related human-written surveys. Based on the refined outline, topic-focused papers are ret

---

### [151] Beyond Prompts: Measuring and Optimizing LLM Tool-Agent Harnesses

**链接**: https://arxiv.org/abs/2609.05736
**作者**: Cen (Mia) Zhao, Haibo Ruan, Wenjie Chen, Pei-fen Tu, Usman Abbasi, Joel Hesch
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM tool agents can be improved without retraining by modifying the runtime harness around a fixed model: prompts, tool interfaces, middleware, state handling, and recovery logic. We study this setting as resource-bounded harness selection for fixed-model multi-turn tool agents, with the search surface scoped to prompts and tool-boundary middleware: edits are guarded intercepts at the tool boundary, not arbitrary rewriting of agent execution logic. Our optimizer-agnostic protocol reports mean held-out lift, worst-condition lift, repeatability, logged cost diagnostics, and RelLift95(B), a conservative estimate of the held-out gain of the harness selected under budget B. We instantiate the protocol with prompt-only and prompt-plus-middleware optimizers, including PRISM, which clusters failures and routes repairs to prompt, tool-boundary middleware, or joint edit surfaces within a Pareto search. On BFCL multi-round, tau2-Retail, and tau2-Telecom, PRISM obtains mean held-out lifts of 14.2,

---

### [152] Celty: SpMSpV GPU Kernel and SIMT Co-Design for Efficient Dual-Sparse LLM Inference

**链接**: https://arxiv.org/abs/2608.01536
**作者**: Ruokai Yin, Priyadarshini Panda
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] When Does Memory Help? A Cost-Aware Evaluation of Long-Term Memory in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2609.05441
**作者**: Shweta Mishra, Shashank Mishra
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory for LLM agents is evaluated today by conversational recall benchmarks (LoCoMo, LongMemEval), which measure question answering over dialogue history, not whether remembered facts change what a tool-using agent does. We present MERIT (Memory Evaluation for Realistic Instrumented Tasks), a benchmark and harness that measures the marginal utility of memory for task-executing agents under explicit cost accounting. MERIT provides episodic tool-use tasks in three domains whose dependence on earlier-episode facts is verified by an automated leak check; a difficulty ladder ending in updated-fact recall; controlled memory corruption; and full token and dollar metering of every memory operation. Across 23,440 scored episodes ($42.57), a two-generation pilot on gpt-4.1-mini and a preregistered 3-model x 3-seed grid (GPT-4.1, Claude Haiku 4.5; memory side held fixed), memory lifts dependent-task success from a leak-verified floor of 0.00 to 0.55-1.00. On updated facts, embedding re

---

### [154] The Unreliable Progress Bar: Can LLM Agents Reliably Report Task Progress Throughout Execution?

**链接**: https://arxiv.org/abs/2609.08589
**作者**: Boyang Wang, Yunhan Wang, Yalun Wu
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent large language models can emit task-progress signals that agent frameworks use to decide whether a task should continue or stop, yet whether a model can reliably report its task progress at every stage of a task, and where and how its reports fail, has not been studied systematically. We evaluate this ability on the public benchmark $\tau^2$-bench and on StageIF, a controlled testbed in which reporting checkpoints are placed across the task's lifecycle. Both settings require reports at multiple task stages. We find that reporting reliability depends on the stage a task has reached, and that almost every deployed model we test is reliable at some stages and unreliable at others. Where reporting breaks down is not the same everywhere. Most deployed models lose accuracy once work is under way and recover once the task is done. The newest generation closes that mid-task drop and instead grows conservative at the finish line. Our study exposes a capability gap in task-progress report

---

### [155] Localizing and Correcting Errors for LLM-based Planners

**链接**: https://arxiv.org/abs/2602.00276
**作者**: Aditya Kumar, William W. Cohen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] Detokenization Leaks: Reconstructing Local LLM Outputs From Cache Traces

**链接**: https://arxiv.org/abs/2609.06674
**作者**: Roy Weiss, Benyamin Konstantinov, Eitam Sheetrit, Tomer Simon, Yisroel Mirsky
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a new attack that reconstructs the text generated by locally hosted LLMs by observing CPU cache activity during detokenization. Unlike prior attacks that rely on deployment-specific assumptions, such as shared data memory, CPU offloading, or Mixture-of-Experts architectures, our approach targets the detokenizer, a component used in default LLM inference pipelines. To obtain clean signals, we use Flush+Reload on shared tokenizer code to detect when decoding occurs, which lets us perform Prime+Probe at the right moment and isolate token-dependent cache activity. We then apply a clustering-and-language-model pipeline to recover text from noisy cache observations. We evaluate the attack across multiple datasets, hardware platforms, inference frameworks, and model families, and show that it can recover semantically accurate outputs from real-world local LLM deployments, including agentic systems. This vulnerability is particularly significant because the most widely used tokenize

---

### [157] FedSubMuon: Communication-Efficient Federated LLM Fine-Tuning via Structured Subspace Muon

**链接**: https://arxiv.org/abs/2609.06073
**作者**: Shaolong Chen, Youming Tao, Shuzhen Chen, Falko Dressler, Qingqing Ye, and Di Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated fine-tuning adapts large language models (LLMs) to decentralized client data, but its scalability in cross-device training is often limited by the high communication cost. Muon is an optimizer that improves optimization performance by orthogonalizing momentum for matrix-valued parameters. Existing federated Muon methods demonstrate the benefit of matrix-aware optimization in federated learning, but still require transmitting full layer-size updates and optimizer state. A natural way to reduce communication is to directly apply Muon to LoRA factors, but this changes the optimized object and weakens Muon's matrix-aware update geometry. We propose FedSubMuon, a communication-efficient federated Muon fine-tuning method that optimizes compact coefficient matrices within shared structured subspaces. This design keeps Muon on a single matrix-valued trainable object, while reducing the client upload to compact coefficient matrices. We further introduce FedSubMuon-GT, an accuracy-orie

---

### [158] Identifying and Transferring Reasoning-Critical Neurons: Improving LLM Inference Reliability via Activation Steering

**链接**: https://arxiv.org/abs/2601.19847
**作者**: Fangan Dong, Zuming Yan, Xuri Ge, Zhiwei Xu, Mengqi Zhang, Xuanang Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [159] When Tools Hurt LLM Reasoning: State-Dependent Belief Revision under External Evidence

**链接**: https://arxiv.org/abs/2508.15754
**作者**: Yufeng Zhao, Junnan Liu, Hongwei Liu, Dongsheng Zhu, Yuan Shen, Songyang Zhang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] A*-Thought-V2: Efficient Latent Reasoning via Geometric Dynamics of LLM

**链接**: https://arxiv.org/abs/2609.07821
**作者**: Xiaoang Xu, Siyuan Liu, Shuo Wang, Junlan Feng, Fanyu Meng, Zhu Zhang 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-Thought (CoT) improves the reasoning ability of Large Language Models (LLMs) but incurs substantial computation and context costs. Existing methods either lose intermediate information through hard pruning or lack a principled criterion for continuous compression. We present A*-Thought-V2, a geometric dynamics of LLM guided framework that models CoT as a hidden-state trajectory and replaces hard deletion with an explicit-implicit interleaved latent architecture. After projecting question, step, and solution representations into a 3D PCA space, it measures alignment between each local transition and global question-to-solution direction. Aligned steps remain explicit text, whereas deviating steps are compressed into continuous latent tokens. Directional angles capture both local semantics and reasoning dynamics: small angles indicate direct execution and answer formation, while large angles more frequently involve checking, correction, and branch exploration; their temporal var

---

### [161] AgentDrift: A Step-Labeled Benchmark of Injection-Hijacked LLM Agent Trajectories

**链接**: https://arxiv.org/abs/2609.06972
**作者**: Asif Pinjari, Mithun Paul Saint-Germain
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents complete tasks by issuing sequences of tool calls, and every observation they read is a channel through which an indirect prompt injection can enter. A successful injection has a characteristic shape when the trajectory is read in order: a benign prefix gives way to actions that serve the attacker rather than the user. Existing benchmarks measure whether such attacks succeed against live agents, and existing guard models judge a trace as a whole; no public corpus labels, step by step, where an injection enters a trajectory and which steps it corrupts. We present AgentDrift, a benchmark of 12,536 synthetic tool-call trajectories over five agent domains in which every one of the 71,024 steps carries one of four labels: benign, injection point, hijacked, or failed injection. The corpus contains 4,000 benign, 5,536 attacked, 1,500 failed-attack, and 1,500 hard-negative trajectories; attacked trajectories follow three compliance patterns whose label strings obey a stated regular 

---

### [162] InsightChain: Optimized Chain-of-Insight Analytics for LLM-driven Data Visualization

**链接**: https://arxiv.org/abs/2609.06438
**作者**: Hanya Sun, Chen Zhang, Sheng Liang, Yongyue Zhang, Yong Liu
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for automated data visualization, yet existing approaches often frame visualization generation as a single-step mapping from user query to figure or code, overlooking the iterative analytical reasoning process of expert analysts. We present InsightChain, a four-stage visualization prompting pipeline (Explore--Focus--Test--Present) that emulates expert analytical workflows, together with VG-COPRO, a vision-guided automatic prompt optimization (APO) method adapted to jointly optimize such multi-stage, executable pipelines. To address the evaluation gap for complex data visualization, we introduce the Insight Progression Metric (IPM), a rubric combining four text-based dimensions with a vision-based dimension. We assess IPM through a 100-chain human pilot and an expanded 300-chain agent-based evaluation spanning all ten domains. Experiments on public datasets show that InsightChain consistently outperforms competing prompting baselines. E

---

### [163] MEMO: Multimodal Evidence Memory Organization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.07471
**作者**: Xian Gao, Jinpeng Wang, Jiacheng Ruan, Guangyu Cao, Ting Liu, and Yuzhuo Fu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents rely on external memory to store and reuse information beyond a single context window, yet there is a fundamental tension between the continuous accumulation of interaction trajectories and the limited context capacity. The key challenge in agent memory is therefore not only to retrieve relevant records, but also to select necessary evidence under a given budget and organize it in an appropriate modality. Existing memory readout methods mainly use textual or visual forms. Text preserves high fidelity, but its linear token representation makes contents with different importance compete for the limited context at nearly uniform unit cost. Visual readout renders text into document-like images, which can use two-dimensional layouts to expose structure and emphasize key information, but it may lose fine-grained details during rendering and compression. To address this issue, we propose MEMO, a multimodal evidence memory organization method for LLM agents. MEMO first 

---

### [164] Beyond Single-Negative Preference: Multi-Negative DPO for LLM-Centric Historical Entity Linking

**链接**: https://arxiv.org/abs/2609.07379
**作者**: Tien Nam Nguyen, Emanuela Boros, Ahmed Hamdi, Adam Jatowt, Micka\"el Coustaty, Antoine Doucet
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have recently shown promise for historical entity linking, but preference optimization for this task is often formulated with only one negative candidate per training instance. This discards information from the remaining candidates retrieved for the same mention. We introduce multi-negative direct preference optimisation (MDPO), a reference-based pairwise objective that compares the correct entity with all valid rejected candidates associated with each mention. MDPO preserves the Bradley-Terry formulation of DPO while exploiting the complete candidate set through masked, length-normalised sequence scores. We evaluate MDPO on hipe-2020 and newseye, covering French, German, English, Swedish, and Finnish historical newspaper text. Experiments show that MDPO improves over supervised fine-tuning and single-negative DPO, with particularly strong gains for NIL mentions, semantic ambiguity, OCR noise, and historically difficult names. Further analyses disentangle 

---

### [165] LLM Layers Immediately Correct Each Other

**链接**: https://arxiv.org/abs/2609.07876
**作者**: Arjun Patrawala, Jiahai Feng, Erik Jones, Jacob Steinhardt
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent methods in language model interpretability employ techniques such as sparse autoencoders to decompose residual stream contributions into linear, semantically meaningful features. Such methods are commonly interpreted as identifying features that persist in the residual stream and that subsequent layers build upon. We challenge this view by identifying the Transformer Layer Correction Mechanism (TLCM), wherein adjacent transformer layers systematically counteract portions of each other's contributions. TLCM appears in 5 out of 7 major open-source model families and activates across nearly all tokens in diverse texts. We show that TLCM emerges during pretraining, operates most strongly on contextually dependent tokens, and adaptively calibrates its correction strength based on the preceding layer's output. Using the layer Jacobian, we further show that TLCM selectively corrects specific subspaces while reinforcing others, which we interpret through a ``propose-and-reject'' framewo

---

### [166] Personalizing LLM Agent Memory Using Biometrics

**链接**: https://arxiv.org/abs/2609.08558
**作者**: Yanhong Qian, Qingguo Meng, Shihao Ding, Xingbo Dong, Zhe Jin, Hanrui Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized memory helps LLM agents deliver stable, tailored assistance by storing and reusing user-specific data across interactions. In multi-user scenarios, however, retrieval must consider not only semantic similarity but also whether the current requester matches the identity associated with the stored memory. We propose Bio-Memory, a biometric-aware memory architecture that conditions memory retrieval on both semantic similarity and biometric matching. Built on top of A-Mem, Bio-Memory augments each atomic memory note with a biometric embedding and uses biometric matching to form the retrieval candidate pool before semantic ranking. We evaluate Bio-Memory on LoCoMo in a 10-user shared-agent setting over 7 face benchmarks and 10 palmprint protocols. Across datasets, Bio-Memory consistently separates owner and non-owner queries. Under face-based personalization, the largest average gap reaches 27.29% / 21.15% in F1 / BLEU-1 on CALFW; under palmprint-based personalization, the corr

---

### [167] Do Dynamic Routers Need Memory? HeRo: History-Aware Routing for Efficient LLM Inference

**链接**: https://arxiv.org/abs/2609.08189
**作者**: Hongjin Lin, Wentao Wan, Keze Wang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic layer routing reduces the inference cost of Large Language Models (LLMs) by learning to skip layers for individual tokens. Existing methods, however, treat each routing decision as a local operation conditioned solely on the current hidden state which is a formulation that overlooks the sequential, path-dependent nature of routing across depth: earlier decisions shape the representations seen by downstream routers, and the layer-usage objective couples all decisions jointly. We propose History-Aware Routing (HeRo), a dynamic routing framework that resolves this mismatch by introducing a router memory mechanism to maintain an explicit routing state across model depth. The memory is constructed via linear attention, incrementally aggregating preceding routing scores and their induced residual updates into a compact history representation. At each routed layer, the router conditions jointly on this accumulated state and the current hidden representation to select the executed bran

---

### [168] Rethinking the Evaluation of Efficiency Methods for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.05933
**作者**: Jiamu Zhang, Lingxi Zhang, Pengjun Lu, Qiyue Zhang, Yu-Neng Chuang, Zhengchen Li 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficiency is increasingly important for Large Language Model (LLM)-based multi-agent systems (MAS), as larger models and more agents introduce substantial execution costs. Recent methods aim to make MAS cheaper by pruning agents, removing communication edges, or searching for compact structures. However, we argue that existing evaluations may overestimate their true ability to improve MAS efficiency. Reported gains are often measured under method-specific prompts and starting topologies, making them difficult to attribute to the proposed structural changes. Moreover, many reported successes appear in non-MAS-demanding settings, where a single agent or a randomly pruned system can already preserve strong performance. To study these issues, we introduce a controlled and MAS-demanding diagnostic benchmark for representative MAS efficiency methods. We evaluate methods under a shared backbone model, agent registry, and runtime, across controlled variations in topology, scale, depth, and to

---

### [169] Broken on Arrival: Silently Defective LLM Artifacts in Public Model Registries and How to Catch Them

**链接**: https://arxiv.org/abs/2609.05881
**作者**: Aditi Patodiya
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developers increasingly run large language models locally by pulling quantized GGUF artifacts from public registries, yet nothing in the distribution pipeline functionally tests these conversions before they reach users. We executed 327 quantized code-capable model artifacts: 305 from the official Ollama library, spanning 15 model lines at every eligible quantization level at or under 8 GB, and 22 from the most-downloaded community repositories on HuggingFace. Each ran a 15-task smoke suite calibrated so that healthy artifacts pass while a known-broken one fails; suspects then faced full 164-task evaluation, a second inference backend, an independent distributor's conversion of the same model and quantization as referee, and, for community files, re-testing under the artifact's own template. The official library carries five silently defective artifacts, a batch of four Qwen2.5-Coder-3B conversions and one phi3.5-mini conversion, that solve zero of 164 tasks and zero of the smoke suite

---

### [170] AuK Technical Report: An Open-Source Foundational Model for Speech Generation and Editing

**链接**: https://arxiv.org/abs/2609.08936
**作者**: Ziyang Ma, Zhikang Niu, Wenming Tu, Tianrui Wang, Ruiqi Yan, Junxi Liu 等 (10 人)
**来源**: cs.SD cs.CL cs.MM
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce AuK, an open-source foundational model that unifies speech generation and editing through a common interface of natural-language instructions and audio context. To support this broad capability set, we construct approximately 3.03 billion instruction--audio instances and 1.95 million hours of effective supervision across five task families: speech generation, content editing, enhancement and separation, paralinguistic editing, and acoustic editing. AuK combines a multimodal large language model for semantic conditioning, an VAE jointly trained on speech, general audio, and music for acoustic conditioning, and a hybrid rectified-flow Transformer that performs dual-stream MMDiT blocks followed by unified single-stream DiT blocks for generation. Training begins with generation-only warm-up and proceeds to joint generation--editing pre-training. We then apply complementary post-training strategies: human-feedback preference optimization for open-ended editing and reward-based 

---

### [171] Many-Tier Instruction Hierarchy in LLM Agents

**链接**: https://arxiv.org/abs/2604.09443
**作者**: Jingyu Zhang, Tianjian Li, William Jurayj, Hongyuan Zhan, Benjamin Van Durme, Daniel Khashabi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [172] What Does an LLM-Agent Leaderboard Rank Actually Compare?

**链接**: https://arxiv.org/abs/2609.07785
**作者**: Wei-Jung Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM-agent leaderboard invites a familiar inference: an agent ranked above another is the better agent. Public evaluation logs may not support that conclusion when systems differ in task mixture, label source, release detail, or cost rule. We study what leaderboard scores estimate and when they justify pairwise superiority conclusions. Our estimand-aware pairwise procedure states the comparison target and measurement source, checks common support, and evaluates the supported difference using a stated uncertainty rule and practical margin. Controlled checks evaluate the decision labels under known finite-sample conditions and show why uncertainty must be included when judging sensitivity to target reweighting. Across SWE-bench, AgentRewardBench, and tau2-bench, close rank differences are often unresolved; proxy labels and utility rules can also change which system is selected. DataAgentBench and Open Agent show what remains estimable from coarser public records. A leaderboard score su

---

### [173] MpSub: A Momentum $p$-Dimensional Subspace Trust-Region Method for Derivative-Free Fine-Tuning of Large Language Models

**链接**: https://arxiv.org/abs/2609.07666
**作者**: Yuyang Wang, Haoyu Yao, Pengcheng Xie
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-parameter fine-tuning of large language models has substantial memory costs because backpropagation stores activations and gradients. Zeroth-order optimization avoids this by estimating update directions from loss evaluations, but existing methods require tuning a sensitive learning rate for each model and task. We propose the momentum $p$-dimensional subspace trust-region method (MpSub). At each iteration, MpSub searches within a $p$-dimensional subspace: one direction preserves historical momentum from the most recent accepted step, while the remaining directions explore via fresh random sampling. The subspace gradient is estimated by central differences, a trial step is computed from a linear trust-region model, and the trust-region radius adapts according to the agreement between predicted and observed loss reduction, eliminating the learning rate. For LLM fine-tuning, evaluations within an iteration share a minibatch, and directions are regenerated in place from seeds, using 

---

### [174] Who Maintains Agent Skills? A Longitudinal Study of Human-Governed, AI-Assisted Skill Maintenance

**链接**: https://arxiv.org/abs/2609.05677
**作者**: Chen Shen, Estevam Hruschka
**来源**: cs.CL cs.AI cs.HC cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lifelong LLM agents increasingly rely on external skill artifacts as one element for preserving and reusing capabilities over time. These skills (usually portable Markdown files such as SKILL.md) describe when and how to apply a capability and must be corrected, expanded, and consolidated as tools and usage patterns shift over deployment. Recent work seeks to automate skill curation, but it largely evaluates against automated baselines and treats human maintenance as an unmeasured bottleneck. We study that missing process directly. We mine the full commit histories of five public AI-skill repositories, a purposive sample of AI-tooling organizations, covering 873 commits, 143 skill files, and 254 substantive post-creation edits from October 2025 to June 2026. We code each edit with pre-registered governance, operation, and trigger-evidence codebooks. Three findings emerge. First, every substantive edit is authored or merged through a named human account, while 62% carry an AI co-author 

---

### [175] SE-GoS: Self-Evolving Graph-of-Skills for Skill Library at Scale

**链接**: https://arxiv.org/abs/2609.08228
**作者**: Dawei Fu, Cheng Jiang, Sitian Qian, Huainan Wang, Zhongkai Hao
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM agents increasingly rely on reusable skills, yet as skill libraries scale to thousands of entries, effective retrieval becomes a bottleneck. Graph-of-Skills (GoS) addresses this challenge by exploiting dependency-aware graph structure for scalable skill retrieval, while SkillDAG further demonstrates that skill graphs can accumulate execution-backed structure online. However, these approaches leave open whether historical execution traces can be systematically distilled into a better retrieval graph that generalizes to unseen tasks. We present Self-Evolving Graph-of-Skills (SE-GoS), a training-free framework that evolves an existing GoS graph from execution traces while preserving the original retrieval pipeline. SE-GoS performs three complementary updates: topology evolution that discovers and prunes skill relationships from execution evidence, edge-weight evolution that reinforces retrieval-relevant relationships based on historical effectiveness, and description evolution 

---

### [176] Don't Lose Entities from Retrieval to Generation: Dual Entity Recovery RAG for multi-hop QA

**链接**: https://arxiv.org/abs/2609.06065
**作者**: Heechang Lee and Dong-Young Lim
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented multi-hop question answering (QA) decomposes a query into sub-questions and decomposes the corpus into smaller retrieval units such as sentences. Both forms of decomposition improve the pipeline, but we show that both share the same vulnerability, the loss of entity information, and that this loss breaks the pipeline at two separate points. The first point is retrieval, where a sub-question loses the entity resolved at the previous hop, leaving the retriever with nothing to match against. The second point is harder to see, because retrieval still appears to succeed. Once a passage is split into sentences, an isolated sentence loses the context that grounds its pronouns, so even with the correct sentence in hand the LLM cannot tell which entity the sentence is about. We isolate this second point as a distinct failure mode that we call lost-in-generation, and a retrieval-controlled experiment shows that it degrades answers even when the gold evidence is fixed in the c

---

### [177] What if LLMs Ate Their Words: Causal History Effects in Multi-Turn Interaction

**链接**: https://arxiv.org/abs/2609.05882
**作者**: Jinnan Li, Zheren Fu, Yue Wang, Jinzhe Li, Yuan Wu, Yi Chang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn interaction creates a feedback process in which an LLM's previous responses become context for later behavior. Prior work shows substantial multi-turn degradation and that assistant-generated history can affect later behavior. However, it remains unclear how these effects manifest across models, tasks, turns, and inside a model. We study these gaps across six task families and five models. Degradation from fully specified single-turn input (FULL) to progressively revealed multi-turn interaction (SHARDED) is clearly task- and model-dependent, and stronger one-shot performance does not imply greater interaction robustness. We then retrospectively analyze completed SHARDED conversations by replaying the user messages already observed in each trajectory while editing only assistant-generated history. Replacing prior assistant responses with neutral content (termed neutralization) changes downstream min-max normalized performance by +.027 across 2,973 trajectories. On a prespecif

---

### [178] From Simulated Citizens to Simulated Deliberation: Challenges in Representation and Interaction

**链接**: https://arxiv.org/abs/2609.07573
**作者**: Chaemin Jang, Junsik Min, Jaewoo Choi, Donggyu Lee, Haiin Lee, Junyoung Park 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM deliberation has been explored as a scalable way to simulate public deliberation. For such simulations to be informative, persona agents should reflect population opinion patterns and interaction should shape their conclusions. We evaluate whether LLM-based deliberation can meet these two conditions using census-grounded Korean personas debating real policy questions benchmarked against national surveys. Persona agents do not reliably reproduce population opinion patterns: responses are often far more concentrated and frequently reverse demographic differences in the human data. Deliberations nonetheless produce reasoned, reciprocal, and varied arguments alongside substantial stance movement. Yet much of this movement does not require peer exchange: sealed-monologue agents change position at similar rates and reach nearly the same final balance as full debates, while groups initialized with very different positions often converge to similar endpoints. Anchoring populati

---

### [179] Data Quality Rule Generation with LLMs

**链接**: https://arxiv.org/abs/2609.06053
**作者**: Anna-Christina Glock and Thomas H\"utter and Johannes F\"urnkranz and Wolfram W\"o{\ss} and Christine Dominka-Kiss and Lisa Ehrlinger
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The validation of data, such as customer and employee data, is an important task in many organizations. Errors in data can have severe consequences. For example, a wrong drug unit in a patient record can lead to life-threatening medication errors, and a missing street number in an address to failed deliveries. Companies often employ rule-based enterprise data quality (DQ) tools, which allow domain experts to specify rules to validate the data over time. While rule-based DQ tools are computationally efficient and provide explainable reports, maintaining a comprehensive rule set manually is challenging, as domain experts often overlook essential rules, especially in complex domains and large data volumes. Hence, closing these gaps remains an open problem in practice. In this paper, we address the challenge of automated DQ rule generation. For this, we formalize a generalizable generate-filter framework and introduce LeDQeR, an LLM-based DQ rule generation approach. First, a large languag

---

### [180] Evaluating and Improving Evidence-Grounded Fact-Checking in LLMs via Multi-Round Evidence Ablation

**链接**: https://arxiv.org/abs/2609.08943
**作者**: Xingyu Deng, Mingzi Cao, Nikolaos Aletras, Xi Wang, Mark Stevenson
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic fact-checking systems assess the veracity of claims given evidence from relevant documents. Large Language Models (LLMs) have demonstrated strong performance in fact-checking due to their general reasoning capabilities. However, it remains unclear whether they faithfully make use of the evidence provided to reach veracity judgments or rely on parametric knowledge. To investigate this, we introduce Fact-Ablated Evaluation (FAE), a new evaluation framework that iteratively ablates the cited evidence to assess whether LLMs revise their predictions accordingly. Our empirical results show that current off-the-shelf LLMs as fact-checking systems rely more on their parametric knowledge than on the evidence provided. To bridge this gap between prediction accuracy and evidence grounding, we propose REAL (Rigorous Evidence Ablation Learning), a training framework that promotes evidence-dependent verification through counterfactual evidence supervision for the LLM-as-verifier models. Ex

---

### [181] VST: Verifiable Structured Transport for Auditable Agent-to-Agent Alpha Discovery

**链接**: https://arxiv.org/abs/2609.07065
**作者**: Yuqi Li, Siyuan Liu, Bingjun Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent-to-agent (A2A) alpha discovery is slowed by repeated feedback cycles between mining and evaluation agents, whose hand-offs, in contemporary LLM multi-agent systems, are free-form natural-language messages that carry no stable contract and cannot be replayed. We first restructure this communication as a structured agent-to-agent protocol of \emph{typed, causally addressable, unicast records}, so that the committed stream forms a causal trajectory. On that trajectory a single predictor with four typed heads forecasts the accumulated guidance the two miners would receive several cycles ahead; a transactional verify--leap controller then commits a multi-cycle speculative outcome only when it passes a four-level gate, and otherwise rolls back to the exact prior state. Structure is the enabling contribution, and its value is not accuracy. A controlled ablation shows an equal-information free-text channel reaches the same predictor hit rate. What typing provides is a state that can be s

---

### [182] EmoMed: An Emotionally-Aware Agent for Multimodal Medical Support with Real-Time Information Retrieval

**链接**: https://arxiv.org/abs/2609.07194
**作者**: Ivan Nasonov, Nikita Glazkov, Ivan Makovetskiy, Mikhail Mozikov, Daniil Sukhorukov, Andrey Savchenko 等 (7 人)
**来源**: cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present EmoMed - a multimodal medical consultation agent that adapts its responses based on users' emotional states while maintaining clinical accuracy. The system processes text and medical images, detects affect indicators (anxiety, confusion, urgency) from user input, and adjusts response tone, structure, and detail level accordingly. To ensure factual reliability, the agent grounds clinical information through a dual retrieval mechanism: web-based fact-checking and an API-connected, continuously updated medical knowledge base. We evaluate our approach across seven state-of-the-art language models (GPT-4/5, Qwen3, Llama 4, Gemini 2.5, Grok4, Claude3) using comprehensive metrics including LLM-as-judge assessments, MedQA style accuracy tests, BERT Score, safety/helpfulness ratings, and multimodal medical benchmarks. The results demonstrate that emotionally adaptive responses consistently outperform neutral baseline across evaluation dimensions, without compromising clinical accurac

---

### [183] A Closed-Form Estimator and Diagnostic Battery for Anchor-Judge Error Correlation, Under a Single-Common-Factor Model

**链接**: https://arxiv.org/abs/2609.08826
**作者**: Veerendra Kumar Sunkavalli
**来源**: stat.ME cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an external reference set (an anchor) is used to decompose an LLM-judge panel's error into a quality signal and a shared common-mode error, standard practice assumes the anchor is uncontaminated: its error uncorrelated with the judges' shared error. We study when that assumption can be dropped and replaced by an estimate. Under a single-common-factor model, >=2 judges and >=2 anchors point-identify the quality variance, the common-mode variance, and each anchor's contamination correlation rho_k in closed form, with an exact per-anchor-pair failure boundary; a designated clean-anchor estimator, by contrast, reports a contaminated companion anchor as fully clean once its trusted anchor is itself contaminated. Because the single-common-factor assumption is itself untestable, the estimator ships gated behind a calibrated diagnostic battery (judge-covariance dispersion; over-identification; a family-block test from judge metadata, with a family-blocked estimator that removes family-lev

---

### [184] AgentBrew: Offline Tool-Use Agent Learning from Raw Real-World Trajectories

**链接**: https://arxiv.org/abs/2609.05837
**作者**: Zhiyi Lyu, Yewen Li, Longtao Zheng, Shengtian Yang, Lang Feng, Lei Feng 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly deployed in real-world applications through tool-use APIs, yet training them for specific environments remains fundamentally difficult: real-world applications provide no pre-defined tasks or verifiers, no faithful simulators, and limited budget for large-scale environment interaction. In this paper, we propose \textbf{AgentBrew}, an offline training framework that learns effective tool-use policies from a single batch of raw interaction trajectories, without task verifiers or iterative on-policy rollouts. The agent first explores the target environment to collect a raw trajectory corpus without quality filtering. To extract training signal from this noisy corpus, \emph{retrospective task inference} reconstructs an aligned instruction for each trajectory based on its actual outcome, and \emph{PMI-Based credit assignment} decomposes the trajectory's total information about the inferred instruction into additive per-action credits via pointwise mutual in

---

### [185] EviSI: An Evaluation Agent for Simultaneous Interpreting

**链接**: https://arxiv.org/abs/2609.08171
**作者**: Ben Yan, Zongyao Li, Daimeng Wei, Weidong Liu, Huan Zhao, Chong Li 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simultaneous speech-to-speech translation requires understanding, translation and spoken delivery while the source stream continues. To support timely delivery and limit accumulated delay, systems adopt reformulation and summarization, which can preserve meaning while departing from written references. BLEU and COMET may not reliably distinguish such variation from semantic loss. We introduce EviSI, a large language model evaluation agent adapting the error analysis and penalty principles of Multidimensional Quality Metrics (MQM). It constructs shared source evidence, assesses semantic fidelity and oral expression, reconciles overlapping errors and scores deterministically. EviSI recovers the aggregate human system ranking for English to Chinese. Mean Kendall agreement with human system rankings within corpora reaches 0.707 for English to Chinese and 0.467 for Chinese to English, exceeding evaluated baselines. An extension across five directions shows positive concordance with COMET wi

---

### [186] Qwen-Audio-3.0-ASR Technical Report

**链接**: https://arxiv.org/abs/2609.07549
**作者**: Chuanmeng Bian, Daren Chen, Peixin Chen, Zhigao Chen, Zhiyun Fan, Zhifu Gao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, automatic speech recognition (ASR) has witnessed transformative advancements driven by three complementary paradigms: data scaling, model scaling, and deep integration with large language models (LLMs). However, bridging the gap between academic benchmark performance and real-world production utility remains a persistent challenge, particularly in handling diverse regional dialects, dynamic entities and hotwords, long-range contextual information, and disfluent spontaneous speech. In this report, we present Qwen-Audio-3.0-ASR, a Mixture-of-Experts (MoE) LLM-based ASR system designed to address these production demands through a unified, instruction-following framework. The model is built upon the Qwen backbone, and is trained on tens of millions of hours of large-scale speech data. Qwen-Audio-3.0-ASR supports transcription across 30 languages and 16 Chinese dialectal varieties spanning eight major dialect regions. Beyond multilingual and dialectal recognition, the mode

---

### [187] Noise Adaptive Streaming Audio-Visual Speech Token Enhancement for Robust Full-Duplex Spoken Dialogue Models

**链接**: https://arxiv.org/abs/2609.08390
**作者**: Bella Godiva, Yeonju Kim, Yong Man Ro
**来源**: cs.SD cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex spoken dialogue systems enable simultaneous listening and speaking, but their audio-only perception often fails under background noise and overlapping speech, leading to incoherent responses. Recent audio-visual dialogue approaches show that incorporating visual cues such as lip movements improve robustness under audio corruption. However, existing approaches often adapt the large speech dialogue model itself to process visual input, requiring costly multimodal training. We propose AV-STE, a modular streaming audio-visual front-end that restores corrupted semantic speech tokens from noisy audio and lip video before they reach the speech LLM. The downstream dialogue model remains entirely frozen, preserving its pretrained conversational capabilities. When integrated with frozen Moshi, AV-STE improves average GPT-4o-judged response coherence from 1.42 to 1.91 under same-dataset speaker interference while largely preserving turn-taking behavior. Gains also transfer to out-of-d

---

### [188] Risk Is Not Review Value: Wrong-Answer Exposure Under Bounded Review Budgets

**链接**: https://arxiv.org/abs/2609.07095
**作者**: SangJin Park, Myungsub Choi, Jineok Kim, Minseung Kang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM assistants often produce more answers than humans can review before users see them. Most evaluations ask whether an answer is wrong, unsupported, or low-confidence. Bounded review budgets instead ask which answers should be checked first under a fixed review budget. Risk alone is not enough: a high-risk answer may be hard to repair, while a moderately risky answer may be directly correctable from available evidence. For generated-answer evaluation, we model review prioritization as exposure reduction, where review value combines estimated wrongness, intervention affordance, impact, and cost. We evaluate review queues with Wrong-Answer Exposure Ratio (WAER), the fraction of wrong answers left unreviewed, and post-repair residual exposure (PRRE), the fraction still exposed after deterministic benchmark-supported repairs. PRRE uses repairability rules that do not numerically reuse the affordance scores used for ranking. On a 720-item TAT-QA/SciFact stress benchmark, review-value ranki

---

### [189] When Metrics Reward the Worst Translations: Internalizing Cultural Reasoning for Social Media Translation Evaluation

**链接**: https://arxiv.org/abs/2609.08156
**作者**: Yiwen Qiu, Linjuan Wu, Dingming Li, Yizhou Liu, Zixuan Wang, Haolei Xu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic translation quality metrics trained on general-domain corpora systematically fail on social media content, where communicative intent is encoded in culturally loaded expressions (internet slang, homophonic ciphers, and platform-specific idioms) rather than surface token patterns. We conduct a systematic empirical analysis demonstrating that standard metrics including COMET, XCOMET, and BERTScore exhibit near-zero or negative correlation with human cultural judgments, and even display a severity inversion in which scores increase as translation quality deteriorates. We further show that this failure extends to large language model judges: Qwen3-235B achieves Cohen's kappa of only 0.162, revealing that the bottleneck is not reasoning capacity but cultural grounding: models lack the domain-specific cultural knowledge needed to identify which aspects of a translation require scrutiny. To address this, we propose CuRIL, a reinforcement learning framework that internalizes cultural

---

### [190] Dynamic Lagging for Simultaneous Translation

**链接**: https://arxiv.org/abs/2609.05799
**作者**: Hieu Hoang and Amittai Axelrod
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In cascaded simultaneous speech translation, the machine translation (MT) system cannot control the read--write schedule of the upstream recognizer: it must decide, from a growing source prefix, how much target text to commit. We make a sentence-trained, decoder-only LLM prefix-aware by fine-tuning it on stable prefixes---the longest prefix that any translation up to the current partial source has shared with the model's own full-source output---mixed with full-sentence pairs, and prompt it through a single force-decode turn that carries the committed target forward as more source arrives, making the system flicker-free by construction. We fine-tune Qwen3-8B for EN to DE, JA, ZH, simulating the source stream with reference-transcript prefixes. Prefix finetuning preserves full-sentence quality while improving worst-position chunk quality, and it improves calibration of token-level commit confidence, reducing expected calibration error (ECE) on early source prefixes against a stable-pref

---

### [191] MOAE: Multi-Objective Agent Evolution with Pareto-Preserving Search

**链接**: https://arxiv.org/abs/2609.05992
**作者**: Hengle Jiang, Qijun Cai, Ziying Luo, Ke Tang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based agents continue to advance, their evaluation has become increasingly multifaceted: a capable agent must not only achieve high task completion accuracy but also perform well in interaction quality, safety, and efficiency, raising a central question: can these objectives be optimized simultaneously? Existing methods have considered multiple objectives, but many collapse heterogeneous measurements into a fixed scalar score. Such scalarization depends on metric normalization and preference weights and may discard candidates that represent useful deployment trade-offs. We introduce Multi-Objective Agent Evolution (MOAE), which organizes iterative in-context refinement as a Pareto-preserving evolutionary search over complete agent rollouts. Given a limited rollout budget, MOAE maintains an empirical archive of non-dominated candidates, uses objective-specific diagnostics to guide offspring generation, and applies constraint-aware selection only at deployment. This separates cand

---

### [192] Mapping the Emerging Social Science of Large Language Models

**链接**: https://arxiv.org/abs/2609.07598
**作者**: Yi Yang, Xiao Jia, Zeyun Dong, Chenzhang Wang, Zhanzhan Zhao
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly shape communication, learning, work, creativity, and decision-making, yet social-science research on these developments remains fragmented. We map this emerging field using a curated corpus of 198 papers reviewed in full and a field-scale corpus of 47,719 published papers from five bibliographic databases. Combining sentence embeddings, K-means clustering, within-cluster Latent Dirichlet Allocation (LDA), author and LLM classifications, and structural topic modeling, we identify three domains: LLM as Social Minds, examining socially interpretable model behavior; LLM Societies, examining collective dynamics among interacting model-based agents; and LLM-Human Interactions, examining how people perceive, use, and are affected by LLMs. These domains contain 13 subcategories spanning reasoning, personality and bias, behavioral games, collective intelligence, simulation, trust, work, creativity, and education. In the curated corpus, the three-domain 

---

### [193] LANTERN: Language Model Assessment on Noisy and Transformed Tasks for Understanding Error and Robustness Nuances

**链接**: https://arxiv.org/abs/2609.07309
**作者**: Vamsi Krishna Kodavali, Rituraj Singh
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robustness evaluation of large language models (LLMs) remains a critical challenge, particularly in assessing their sensitivity to perturbations in input data. In this work, we systematically evaluate LLM robustness across multiple dimensions, including word error rate, character repetition and duplication, modifications in choices, and variability in instruction following. To facilitate this evaluation, we construct a synthetic and augmented dataset encompassing a diverse set of LLM benchmarks, specifically targeting multiple-choice question (MCQ) datasets and instruction-following tasks. We conduct extensive experiments on LLMs of varying scales-small, medium, and large-as well as across base and instruction-tuned variants. Our analysis quantifies the variability in model responses under perturbed conditions and highlights discrepancies relative to baseline models. The findings provide insights into the stability of LLMs across different evaluation scenarios contributing to the devel

---

### [194] CreaMem: A Scene-Aware Memory Architecture for Personalized Agents

**链接**: https://arxiv.org/abs/2609.08550
**作者**: Qixuan Sun, Yue Que, Bowei He, Jin Guo, Dihang Yang, Wenchang Situ 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is a core capability for personalized LLM agents. To support it, existing memory systems organize information using various criteria such as topic segments or summary hierarchies. However, we identify two major limitations in these designs. First, they lack scene awareness: memories from unrelated life scenes share the same retrieval space, which inflates the search space and introduces cross-scene interference. Second, they encode each memory from a single perspective, making it difficult to retrieve complementary views of the same event. In this paper, we propose the CreaMem architecture, which enables scene-aware memory organization by partitioning memory into several Life Scene Memories to reduce cross-scene interference at retrieval. To go beyond the single perspective and achieve cross-memory synergy, entries are dual-coded from both episodic and trait-based perspectives within each memory. We further devise a permemory balanced sampling strategy at retrieval tim

---

### [195] DrugReason: Dynamic Multi-View Reasoning over Knowledge Graph and Language Evidence for Drug Repurposing

**链接**: https://arxiv.org/abs/2609.06779
**作者**: Zijie Liu, Hongxuan Li, Zhen Tan, Jinhao Duan, Baixiang Huang, Zunpeng Liu 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Drug repurposing aims to identify new therapeutic uses for existing compounds and, compared with de novo drug discovery, offers a faster and more cost-effective path to clinical translation. However, the space of candidate drug-disease pairs is enormous and their underlying relationships often depend on complex multi-hop biological mechanisms, making it difficult to reliably predict which pairs represent true therapeutic relationships. Existing approaches tackle this from two directions: knowledge graph-based methods organize curated biomedical evidence into structured relational networks for grounded multi-hop reasoning, while LLM-based methods leverage pretrained knowledge to generate flexible mechanistic rationales. Yet neither is sufficient alone - KGs are confined to observed graph structure while LLMs lack factual grounding and risk hallucination. To address this gap, we propose DrugReason, a multi-view reasoning framework that integrates grounded KG reasoning with LLM-generated 

---

### [196] MVWeaver: A Hierarchical Music Video Generation Agent with a Learned Song-to-Visual Bridge

**链接**: https://arxiv.org/abs/2609.06478
**作者**: Sifei Li, Minyan Luo, Xu Li, Guodong Qi, Xincan Wang, Hanwen Wang 等 (10 人)
**来源**: cs.MM cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Music videos are an important form of audiovisual expression in contemporary culture. They translate and extend the expressive content of songs through deliberate visual design. Existing automatic music video (MV) generation systems can generate visually plausible shots, yet often struggle with long-form coherence and song-grounded visual development. We present MVWeaver, a music video generation agent that integrates hierarchical planning with a learned song-to-visual bridge that translates song understanding into executable shot plans. The MVWeaver architecture comprises a comprehensive song analysis module, a visual planner that constructs hierarchical plans, and downstream image and video generation models that render the planned content. To equip a general-purpose LLM with MV-specific song-to-visual knowledge, we learn a bridge between song analysis and visual planning from real-MV-derived supervision and curate 1,861 real-world song--MV pairs with structured song-side, MV-side, a

---

### [197] SRD-GUARD: A Defense Framework of LLMs via Semantic Rewriting and Joint Multi-Model Scoring for Latent Intent Exposure

**链接**: https://arxiv.org/abs/2609.06540
**作者**: Qi Wang, Chengcheng Wan, Jiangtao Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed in safety-critical applications, yet jailbreak attacks can conceal harmful intent through role-playing, fictional scenarios, or seemingly benign motivations. Existing inference-time defenses may miss disguised attacks or excessively refuse legitimate requests. We propose SRD-GUARD, a parameter-free, black-box defense framework that exposes concealed intent through semantic rewriting and consensus-based risk assessment. Given an input prompt, SRD-GUARD generates five semantically related rewrites that preserve the underlying objective while removing unnecessary contextual packaging. The original prompt and rewrites are jointly evaluated by multiple independent LLM-based safety scorers on a continuous risk scale. A decision module combines absolute risk thresholds with relative risk changes between the original and rewritten prompts to adaptively intercept, preserve, or warn on requests. We evaluate SRD-GUARD against UNIATTACK, CIPHE

---

### [198] TurEngMix: A Text Corpus and Benchmark for Turkish-English Code-Mixed Language Identification and Named Entity Recognition

**链接**: https://arxiv.org/abs/2609.06963
**作者**: Ilayda Dogan, Phuong-Anh Nguyen-Le, Julia Mendelsohn
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language processing systems underperform on code-mixed text, particularly for low-resource language pairs. Turkish-English poses a further challenge: it lets English stems combine with Turkish suffixes to form single mixed-language tokens. We introduce TurEngMix, a corpus of 5.5K noisy, naturally occurring social media posts (486,974 tokens) rich in Turkish-English code-mixing. From this corpus, we construct a new Turkish-English benchmark for code-mixed language identification (LID) and named entity recognition (NER), comprising 15K expert-annotated tokens. Evaluating both decoder LLM and fine-tuned encoder baselines, we find that monolingual Turkish and English tokens are labeled reliably, but all models have high error rates on mixed-language tokens for both LID and NER. For morphologically integrated tokens, NER error rates were 5.2x and 6.3x higher for GPT-4o and Qwen, respectively. This highlights how morphological integration remains a challenge. We release the corpus, a

---

### [199] Data Efficient Sample Selection for In-Context Learning

**链接**: https://arxiv.org/abs/2609.06670
**作者**: V Venktesh, Cem levi and Avishek Anand
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The In-context learning (ICL) paradigm aids large language models (LLMs) to adapt to new tasks without need for fine-tuning. However, selecting an optimal combination of demonstration examples from a large pool of example subsets is a challenging problem. Existing approaches for selection do not model the complex relationship between ICL samples and downstream LLM performance. They typically perform static task-level selection, choosing subsets once offline, which can fail to generalize to unseen queries. We introduce DearICL (Data Efficient Algorithm for Ranking) ICL samples, a new framework that models demonstration example selection as a subset ranking problem. DearICL employs a non-linear surrogate employing a differentiable sorting objective within a gap-index bandit algorithm. The gap-index based approach enables fine-grained separation of good arms and borderline arms, which is used as an auxiliary objective to train the non-linear surrogate through sufficient sampling of border

---

### [200] Agents Trust Tools Too Much: Measuring Reliance on Unreliable Tools

**链接**: https://arxiv.org/abs/2609.05587
**作者**: Hoyeol Yang, Woojung Song, Taewon Kim, Jonghyun Song, Seoyeon Park, Yohan Jo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing evaluations of tool-using agents primarily measure whether an agent can successfully complete diverse tasks with tools. These evaluations generally assume that tools return reliable information. However, tool returns in real-world systems can be plausible yet incorrect. We investigate how agents respond to unreliable tool returns by evaluating fourteen LLMs using three tools-web search, LLM sub-agent delegation, and code execution. For each tool, we corrupt its returns and measure whether agents adopt the corrupted content in their final answers. Agents exhibit high levels of overtrust across all three settings: the mean adoption rate exceeds one third for every tool and reaches 68.0% for web search. Analysis of reasoning traces reveals a particularly concerning failure mode: agents often recognize conflicts and even recover the correct answer internally, yet present only the corrupted answer without warning the user. To mitigate agents' overtrust in tool returns, we intervene

---

### [201] Agentic Visual Generation: From Generative Models to Agentic Control

**链接**: https://arxiv.org/abs/2609.06758
**作者**: Yinming Huang, Shuyuan Tu, Xi Yan, Jiahao Zhan, Zihan Yang, Zhen Xing 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual generation is evolving from generative models used through a single invocation into agentic control processes that can plan, select tools, inspect intermediate synthesized outputs, revise failures, and reuse prior experience. In most existing systems, the controller is an LLM or VLM, while visual generation models serve as tools or executors. However, existing work lacks a consistent criterion for determining when a generation system becomes agentic. Planning depth, tool use, multi-role collaboration, and reinforcement learning are often treated as evidence of agenticity, even though none of them necessarily determines which generation decisions the controller can make. We organize the field according to what the controller can directly control in the generation process. At L1 Conditioning Control, the controller prepares the input to a predetermined generator but does not control which visual operation is executed. At L2 Execution Control, it selects and invokes actual generati

---

### [202] You Can't Prefer Emotions You Don't Sample: Intensity Undershoot in DPO-Tuned LLMs

**链接**: https://arxiv.org/abs/2609.07808
**作者**: Hyunwoo Kim, Usama Khalid
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ask a language model to respond "very excitedly," and its output is typically only mildly more energetic. We quantify this effect. We condition an instruction-tuned LLM on a continuous Valence-Arousal (VA) target, where valence measures how pleasant a state is and arousal how activated it is, measure the achieved affect with a frozen regressor, and sweep the requested target from -1 to +1. The response moves far less than asked: the gain, the slope of achieved against requested affect, is only 0.26 for valence and 0.13 for arousal on Llama-3.1-8B, where a faithful controller would score 1. The model systematically undershoots requested emotional intensity, which puts a number on the qualitative observation of Fazzi et al. (2025). Our experiments trace this to the preference-learning pipeline. Training targets from natural corpora such as EmoBank are neutral-heavy, and the sampled candidates themselves rarely reach extreme affect, so Direct Preference Optimization (DPO) is left with no 

---

### [203] Agentic Algorithm Engineering: Improving Shared-Memory Exact Minimum Cuts

**链接**: https://arxiv.org/abs/2609.07204
**作者**: David A. Bader, Adil Chhabra, Ernestine Gro{\ss}mann, Monika Henzinger, Alexander Noe, Christian Schulz
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The minimum cut problem for an undirected edge-weighted graph asks us to divide its set of nodes into two blocks while minimizing the weighted sum of the cut edges. Over the last years, we engineered a range of fast algorithms for this problem. Our fastest exact algorithm uses an inexact algorithm to obtain a better bound for the problem, reductions that depend on this bound, improved data structures and parallel contraction routines. It is available in the open-source package VieCut and, on real-world instances, outperformed the previously fastest solvers by a factor of up to 2.5 sequentially and up to 12.9 when run in parallel. We improve this algorithm using agentic algorithm engineering (AAE), a methodology that we introduce here, in which autonomous large language model agents run the algorithm engineering cycle on an existing code base: they form hypotheses about where running time is lost, implement them, benchmark the result on a fixed instance set and keep or discard the chang

---

### [204] How AI Models Manage Epistemic Authority: A Taxonomy and Comparative Analysis of Responses to User Disagreement

**链接**: https://arxiv.org/abs/2609.07662
**作者**: Riyadh Alnasser, Yusuf M\"ucahit \c{C}etinkaya, Sumin Zhao, Tu\u{g}rulcan Elmas
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as sources of advice and information, including in high-stakes settings, yet little is known about how they respond to user disagreement. We study how a model manages its epistemic authority, referring here to its claim to knowledge, competence, or the right to advise, once a user challenges its answer. Building on Conversation Analysis, we introduce a taxonomy of six challenge types and a four-layer framework for analysing each response: whether the original claim is maintained or changed, where authority is located, how the disagreement is socially managed, and what kind of evidential support is offered. We construct a new dataset of 2,310 controlled challenge scenarios and 32,340 corresponding responses from 14 models, and analyse them using our framework with an LLM-as-judge pipeline, providing a vocabulary which future evaluation and benchmark design can build on. We find that models show conflicting behaviour: they validate users in 85%

---

### [205] Some Tokens Behave like Magnets: Revealing Linguistic Organization in the Layers of Language Models

**链接**: https://arxiv.org/abs/2609.05743
**作者**: Andrew Liu, Devan Srinivasan, Gerald Penn
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We identify a special group of token vectors inside large language models (LLMs), which we term magnetic vectors, that organize the surrounding tokens by either attracting or repelling them. Particularly, tokens pointing the same way as an attracting magnet are elongated; tokens pointing the same way as a repelling magnet are compressed. Just as physical magnets pull or push away the iron filings around them, these vectors organize their surroundings through two opposing polarities. Moreover, we identify a statistically significant pattern in linguistic category where function words consistently act as repelling magnets in early layers, and we also find magnets consistently reorganize their polarities in unique ways deeper in the model. In a further case study we find this observation may unveil a deliberate, layer-wise organization in how LLMs process language. This pattern is consistent across different LLM architectures, sizes, and layer configurations. It is also causally relevant.

---

### [206] Beyond Retraining-Free MoE Compression: A Cost-Normalized Study of Post-Compression Adjustment

**链接**: https://arxiv.org/abs/2609.06076
**作者**: Sieun Hyeon, Jaeyoung Do
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retraining-free MoE compression reduces deployment memory by pruning or merging experts, but often treats the compressed checkpoint as the final artifact. We argue that this view is incomplete: compressed MoE checkpoints are better understood as compressed initializations that benefit from a tiny post-compression adjustment stage. Across two MoE LLM backbones, four pruning/merging methods, three expert-retention ratios, and 28 benchmarks, we compare LM fine-tuning and teacher-based KD under matched small-data budgets and measured GPU costs. Using only 3,000 C4 examples and a single epoch of adjustment, Full FT recovers 37.3% of the original-to-compressed performance gap on average. Moreover, LM fine-tuning is more cost-effective than standard token-level KD, and full-parameter adjustment gives the strongest cost--recovery trade-off among the tested scopes. These results suggest that retraining-free compression should be paired with small post-compression adjustment to recover a substan

---

### [207] PTCG: Persona-guided Tree-based Counterargument Generation

**链接**: https://arxiv.org/abs/2609.07120
**作者**: Eunbeen Son, Yohan Jo, Joonsuk Park, JinYeong Bak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The ability to generate counterarguments is important for critical thinking and balanced discourse, yet existing approaches typically produce only a single counterargument, failing to capture the diversity and persuasiveness required in real-world debates. To address this limitation, we propose Persona-guided Tree-based Counterargument Generation (PTCG), a framework that combines Tree-of-Thoughts-inspired step-wise generation and pruning with speaker persona selection. By estimating the author's persona from the original argument and incorporating speaker personas representing distinct perspectives, PTCG operationalizes perspective-taking and enables the generation of diverse counterarguments. Results from LLM-as-a-Judge, classifier-based assessment, and human evaluations indicate that PTCG shows consistent improvements in both the diversity and persuasiveness of counterarguments compared to baseline methods.

---

### [208] SAGE: A Hierarchical Framework for Evaluating Interpretive Literary Quality in Narratives

**链接**: https://arxiv.org/abs/2609.06611
**作者**: Tianyu Wang, Nianjun Zhou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Assessing the literary quality of narratives requires evaluating interpretive dimensions (cultural representation, emotional depth, and philosophical engagement) that existing NLG metrics cannot measure. We introduce SAGE, a six-layer evaluation framework that separates rule-based assessment of observable textual properties from LLM-based evaluation of interpretive qualities drawn from cultural theory, affect theory, and existentialist philosophy. Each interpretive layer is assessed through multi-round iterative LLM evaluation with independent cross-validation, achieving measurement-grade reliability (98.8% convergence, >94% inter-rater agreement) stable across evaluator models. Validated on 600 evaluations across 100 short stories, our central finding is a systematic capability boundary: emotional-psychological representation approaches human levels, while cultural critique and philosophical depth exhibit approximately double the gap. LLM-generated narratives score below even commerci

---

### [209] DI-Bench: Systematically Generating In-Domain Data Intelligence Benchmarks for Enterprise Agents

**链接**: https://arxiv.org/abs/2609.05776
**作者**: Jiangyun Zhang, Kristen Surrao, Torpong Nitayanont, Yupei Zhang, Roopali Singh, Zhiyu Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating enterprise agents on domain-specific benchmarks is critical, yet public benchmarks rarely evaluate whether agents can integrate business knowledge with analytical computation, and constructing such benchmarks manually is costly. We present DI-Bench, a pipeline for generating realistic benchmarks for data intelligence (DI), the practice of extracting insights from large volumes of enterprise data. To emulate realistic DI tasks that require both computation and knowledge retrieval, DI-Bench builds an artifact linkage graph over data tables, dimensions, metrics, and documents to form questions involving structured data and associated knowledge. Ground truth answers are derived via query execution, followed by LLM question generation and validation. Applied to two public datasets, the pipeline produces a 731-task benchmark covering knowledge retrieval, analytical computation, and rule-grounded reasoning. To show the discriminatory capability and difficulty of the benchmark, we e

---

### [210] From Coordinates to Candidate Regions: Temporal Change Localization via Region Selection in Remote Sensing Multimodal LLMs

**链接**: https://arxiv.org/abs/2609.08391
**作者**: Juwan Chung, Sungjune Park, Yeongyun Kim, Yong Man Ro
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote sensing multimodal large language models (RS-MLLMs) have advanced scene understanding and visual question answering over satellite imagery, yet localizing specific objects or changed regions remains challenging. Existing approaches rely on generating bounding box coordinates as token sequences, which is fragile for the small, densely packed objects common in remote sensing and increasingly error-prone when multiple targets must be localized simultaneously. In this work, we present an RS-specific formulation of the region selection paradigm, previously explored in natural-image MLLMs, and extend it to temporal change localization over multi-image sequences. Our framework employs a text-conditioned region proposal module, encodes each candidate as special tokens carrying per-frame visual features enriched with spatial and temporal cues, and lets the LLM localize targets by selecting region tokens in its response. We construct a multi-task training and evaluation suite spanning loc

---

### [211] What Eviction Destroys: A Restore-Counterfactual Audit of Forgetting in Agent Memory

**链接**: https://arxiv.org/abs/2609.08279
**作者**: Chen Shen
**来源**: cs.CL cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent memory systems must discard stored information when their history exceeds a fixed token budget. Existing budget-accuracy frontiers quantify the resulting loss in accuracy, but do not distinguish irreversible losses caused by eviction from recoverable retrieval failures. We introduce the restore counterfactual, a per-question paired intervention that reinstates the question's gold evidence in the read-time context and reruns the same reader. Combining the change in correctness with whether the evidence was retained after eviction classifies each oracle-answerable error as recoverable, irreversible, or residual; in the residual case, the answer remains incorrect after restoration. We evaluate FIFO, random, redundancy-aware, and LLM-importance eviction on LongMemEval-S at three budgets and under two retrieval regimes, using GPT-4o-mini as the primary reader and judge and GPT-5.4-mini as a robustness reader. Under top-k retrieval at an 80k-token budget, the irreversible share among e

---

### [212] Evidence-Grounded Retrieval for Investigation Hunt Lead Generation from CTI Reports

**链接**: https://arxiv.org/abs/2609.08790
**作者**: Akash Prakash, Boubakr Nour, Makan Pourzandi, Chadi Assi, Mourad Debbabi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Threat hunting increasingly depends on converting unstructured knowledge (e.g., Cyber Threat Intelligence reports) into actionable hunt leads: concise, investigable hypotheses grounded in observable artifacts and adversary techniques. Producing such leads manually is a tedious and hard-to-scale task. Existing automated approaches stop at the entity layer, ignore the defender's operational environment, and analyze each report in isolation. To address these gaps, we introduce AHLERT, a system that automatically extracts relevant, environment-aware, and hunt leads from threat reports through (i) a hybrid retriever that combines dense vector search with multi-hop traversal over a knowledge graph seeded with MITRE ATT&CK; (ii) an ontology-grounding retrieval-augmented generation method that constrains each lead to the defender's own assets and controls; and (iii) an LLM-agnostic framework that emits structured, directly actionable leads rather than loose indicators of compromise. We evaluat

---

### [213] RepoNav: From Snippet Retrieval to File-Centered Repository Navigation for Code Agents

**链接**: https://arxiv.org/abs/2609.08355
**作者**: Hongzheng Chai, Jiakun Li, Hongyue Yu, Yuan Yuan
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Solving repository-level code tasks requires LLM-based agents to use code search tools to navigate large codebases and identify a small set of relevant files and functions. However, current retrieval tools typically return flat lists of isolated code snippets: such lists can surface relevant files, but provide insufficient structure for agents to distinguish the target function from semantically similar alternatives in the same file. We introduce RepoNav, a lightweight post-retrieval interface that reorganizes retrieved snippets into a file-centered navigation scaffold. By presenting compact structural cues and candidate targets, this scaffold guides on-demand file-structure browsing, helping agents compare sibling symbols before selecting a target function. Across diverse models on LocBench, RepoNav improves function-level localization and narrows the file-to-function gap. Controlled ablations demonstrate that these gains come from structured evidence organization rather than simply e

---

### [214] Risk-Conditioned Fine-Tuning of Large Language Models

**链接**: https://arxiv.org/abs/2609.08064
**作者**: Zixuan Liu, Fangzheng Wu, Brian Summa, Zizhan zheng
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in settings where rare but severe harmful generations can have significant consequences. Existing Risk-Averse RLHF addresses this issue by optimizing Conditional Value-at-Risk (CVaR), but it trains policies for fixed risk levels and therefore cannot adjust the desired degree of risk aversion at inference time. In this paper, we propose risk-conditioned RLHF, a framework that trains a single policy that provides a continuous risk-control interface, enabling users to select different degrees of risk aversion without retraining or deploying multiple risk-specific models. Experiments across multiple benchmarks demonstrate that a single risk-conditioned policy can adapt to different risk levels at inference time, enabling more flexible and risk-aware LLM deployment.

---

### [215] AtomCite: Verification and Correction of Supplied Page-Level Citations in Multi-Page Documents

**链接**: https://arxiv.org/abs/2609.05802
**作者**: Chen Qian, Yimeng Wang, Yu Chen, Lingfei Wu, Andreas Stathopoulos
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models answering questions over multi-page documents are expected to cite the supporting pages, yet supplied citations are sometimes inaccurate, and current evaluations score citations at generation time or against text passages: no existing benchmark evaluates whether a system can verify and correct a page-level citation already attached to an answer. We propose AtomCite, an agentic framework that parses an answer into claims, checks each claim against the image of its cited page, and applies a deterministic repair policy. To evaluate it, we introduce DocCite, to our knowledge the first benchmark for systems that verify and correct page-level citations in document images. Built on MP-DocVQA and DUDE, it combines 928 validated injected instances with 2,468 candidate natural errors harvested from frontier- and efficiency-tier models, of which a two-annotator audit confirms 1,909 as genuine errors. Primary labels are assigned deterministically, not by LLM judges, with the 

---

### [216] CrisisKD: Five-Stage Knowledge Distillation for Aspect-Level Sentiment and Emotion Analysis in Crisis Discourse

**链接**: https://arxiv.org/abs/2609.05757
**作者**: Marko Haralovi\'c, Onat Akca, Salih Eren Y\"ucet\"urk, Minsi Li, Mari\"et Theune
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Identifying the target of emotional words or phrases in crisis situations, especially health-related ones, is important for understanding public concerns across cultural and linguistic contexts. We propose CrisisKD, a five-stage teacher--student knowledge distillation framework for aspect-level sentiment and emotion analysis on unannotated social media data. A teacher LLM generates aspect-level labels and reasoning traces that supervise a smaller student model across aspect extraction, syntactic parsing, opinion extraction, sentiment classification, and emotion classification. Using this framework, we construct and release a dataset containing 50,615 aspect-level labels, together with the annotation and fine-tuning scripts as open-source resources. The resulting student supports end-to-end ABSA and emotion detection at substantially lower inference cost than the teacher. On a manually annotated 500-tweet gold set, the 5-task Qwen2.5-7B student improves over the untuned model by 7.9 F1 

---

### [217] HealthLoopQA: A Context-Aware Question Answering Benchmark for Interpreting Wearable Monitoring Data in Diabetes Care

**链接**: https://arxiv.org/abs/2609.06976
**作者**: Yuchen Niu, Yanan Ma, Srinivasan Nandakumar, Maolin Chen, Viktor Schlegel, Kexin Wei 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As medical wearables become integrated into daily chronic disease care, effectively interpreting longitudinal monitoring data is essential for patients and clinicians to understand health trends, detect safety-critical events, and make informed decisions. While large language models (LLMs) show promise for transforming this streaming physiological data into personalized health insights, evaluating their reasoning capability and analytical rigor in diverse monitoring tasks remains a fundamental challenge. Existing medical wearable question answering (QA) benchmarks primarily assess short-horizon classification or statistical summaries, largely ignoring the long-term patterns, therapeutic and behavioural contexts, and potential system failures inherent in real-world deployments. To address this, we introduce HealthLoopQA, a comprehensive diagnostic benchmark for evaluating LLM reasoning over continuous diabetes monitoring data. Grounded in a novel taxonomy of eleven atomic reasoning abil

---

### [218] Fine PT-PT Web: A High-Quality 41 Billion Tokens Data Collection of the European Portuguese Web

**链接**: https://arxiv.org/abs/2609.07699
**作者**: Gon\c{c}alo Vinagre, Rui Pedro Guerra, Pedro Gomes, Miguel Moura Ramos, Duarte Miguel Alves, Afonso Simpl\'icio 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Curating Web corpora for regional language variants like European Portuguese (PT-PT) is heavily bottlenecked by dialectal overlap (mainly with PT-BR) and data processing scale. This paper presents an efficient pipeline to curate a production-ready PT-PT corpus from the Portuguese Web, spanning 411 TB of raw data from Arquivo.pt. We introduce a novel post-scraping block that removes boilerplate and line duplicates prior to filtering. This early-stage intervention increases final document yield by 19.04% by rescuing valid text that standard heuristic filters prematurely discard. Integrated with rigorous language identification, weighted fuzzy deduplication, and neural quality classification, our pipeline offers a scalable framework and a clean, representative corpus optimized for LLM pre-training.

---

### [219] Intra-Prompt Parallel Decoding for Common-Context Question Answering

**链接**: https://arxiv.org/abs/2609.05707
**作者**: Theodore Glavas, Nikhita Vedula, Dushyanta Dhyani, Antonios Valkanas, Yilun Zhu, Shervin Malmasi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In common-context question answering (CCQA) tasks, multiple input questions share a common context to base their answers from. However, Large Language Models typically generate each answer using an independent prompt. While existing batching and caching techniques help improve parallelism and reduce repeated computations, the separation of questions across prompts limits the achievable speedup, as modern GPUs are underutilized due to a memory bottleneck during attention. We present Intra-Prompt Parallel Decoding (IPPD), a novel inference method that answers multiple common-context questions in parallel within a single prompt. IPPD directly addresses the bottleneck by efficiently sharing both memory and computation during the attention process, as the next token for every question is decoded in a single inference step. IPPD uses virtual position IDs and attention mask manipulation to generate the same output as standard prompting without requiring fine-tuning or any changes to the LLM a

---

### [220] MoEMB: Scaling Universal Multimodal Embeddings with Efficient Mixture-of-Experts Models

**链接**: https://arxiv.org/abs/2609.08663
**作者**: Xuanming Cui, Shlok Kumar Mishra, Wentao Bao, Aashu Singh, Zihao Wang, Xiangjun Fan 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Universal multimodal embedding (UME) increasingly demands encoder's capacity for handling a broad range of tasks and modalities with increased complexity. Prior scaling methods either increase the representation size, retrieval effort, or scales the encoder into a heavy multimodal LLM. Recent works, such as Think-Then-Embed (TTE), explore scaling via reasoning tokens. However, embedding models are hard to scale up: increasing parameters directly tradeoffs for the large training batch size that contrastive learning needs, and retrieval has to be served under tight latency. Moreover, UME tasks are diverse in complexity, where scaling up embedders can bring significant redundant computation. In this work, we propose MOEMB, which instead scales UME along the expert axis through mixture-of-experts (MoE), growing encoder capacity while preserving single-vector, non-autoregressive encoding. Through a systematic study of the design space and training recipes for MoE-based UME, MoEMB sets a new

---

### [221] Scaling Multi-Agent Systems with Prospect-State Propagation

**链接**: https://arxiv.org/abs/2609.08033
**作者**: Zhimei Chen, Mu Chen, Fakhri Karray
**来源**: cs.MA cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current LLM-based multi-agent systems (MAS) periodically compress intermediate states to reduce inference-time token consumption, thereby attempting to incorporate more agents. However, naive scaling strategies face challenges. For example, in economic simulations, large-scale MAS typically discard semantically rich economic states, i.e., agent behavioral trajectories, which are key drivers of macroeconomic fluctuations. In this paper, we reveal a phenomenon in which agent heterogeneity gradually decreases during simulation, and propose Prospect-State Propagation for Multi-Agent Systems (PspMAS). Inspired by prospect theory, PspMAS decouples each agent's micro state into a compact Prospect State and an expressive Semantic State. The former records psychological traces through a lightweight, parallelizable propagator and continuously injects heterogeneity into the system. The latter leverages the strong perception, reasoning, planning, and decision-making abilities of LLMs. These two co

---

### [222] CGSM: Concept-Guided Segmentation Model for Precise Pulmonary Lesion Delineation

**链接**: https://arxiv.org/abs/2609.07004
**作者**: Changheng Lin (1), Wenjie Zhang (1), Yushan Lu (1), Xinyue Yan (1), Xiao Jia (1), Wei Zhang (1) ((1) Shandong University 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate segmentation of pulmonary lesions is essential for effective clinical diagnosis and treatment strategies. Existing segmentation approaches often lack task-specific semantic guidance, as text-based annotations typically offer coarse localization of lesions, leading to inadequate delineation of lesion boundaries and poor performance on small-scale lesions. To address this, we propose CGSM, a Concept-Guided Segmentation Model that integrates LLM-generated and clinically reviewed concepts into the segmentation process. Specifically, we design a Concept-Visual Alignment Module (CVAM) to activate relevant tokens within the concepts that align with visual features, enhancing the interaction between textual and visual information. In addition, we introduce a Concept Modulated Decoder (CM-Decoder), which uses concepts from CVAM as modulation signals to facilitate the adaptive fusion of image and text features, improving the segmentation accuracy. Extensive experiments on two public dat

---

### [223] Better Together: Complementary Query Rewriting Under a Strong RAG Baseline

**链接**: https://arxiv.org/abs/2609.05637
**作者**: Sara Shanian, Xiaoqin Yi, Pavlo Ruban, Kurt MacDonald
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A popular way to improve Retrieval-Augmented Generation (RAG) is to rewrite the user's question into several variants and search with all of them. We test whether this actually helps once the underlying search is already strong. Under one fixed, competitive pipeline (BGE dense retrieval, cross-encoder reranking, and MMR diversification), we compare four query-rewriting strategies (S1-S4) against two strong LLM baselines (HyDE, Query2Doc) on three datasets (HotpotQA, AmbigNQ, and the 512K-document EnterpriseRAG-Bench) over three seeds with paired-bootstrap significance tests. Our headline result is that rewriting alone is at best competitive with a strong baseline, but combining methods yields outsized gains because different strategies fail on different questions. A post-hoc union of four methods (S1+S3+S4+HyDE) improves HIT@10 over the baseline by +12.5 points on enterprise data (51.70 vs 39.22), and a five-method union reaches 52.98 (+13.8). Budget-matched controls capture only ~40% 

---

### [224] AutoKD: Autonomous Knowledge Discovery

**链接**: https://arxiv.org/abs/2609.06366
**作者**: Qinwen Ge, Bo Ni, Haowei Fu, Ngoc N. Tran, Erik Blasch, Tyler Derr
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery in data-rich domains is currently constrained by human bandwidth: the growth in the volume and complexity of real-world data far outpaces the rate at which researchers can read, reason, and synthesize. Recent LLM-based multi-agent systems have begun to automate portions of the research cycle, but they target hypothesis generation in settings where validation cannot itself be automated, and each run is one-shot, with no mechanism for findings to accumulate or steer subsequent inquiry. This paper introduces AutoKD, a multi-agent framework for autonomous knowledge discovery that is both computational and cumulative, allowing validated findings to persist and inform subsequent inquiry. Six coordinated LLM agents collaborate in an open-ended discovery loop, where accepted findings are stored in a persistent insight graph that serves as both long-term memory and an exploration-steering mechanism. We evaluate AutoKD on three diverse datasets from two perspectives: Open-en

---

### [225] From Narrative to Auditable Forecasts: A Structured Scaffold for Agentic Forecasting

**链接**: https://arxiv.org/abs/2609.05905
**作者**: Yuanpu Cao, Yongkang Du, Yurui Chang, Lu Lin, Jinghui Chen
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used for live forecasting, where they retrieve up-to-date information and produce estimates for unresolved future events. However, current agentic forecasting often relies on implicit narrative aggregation: agents collect evidence, discuss it in prose, and often assign a probability without an explicit update path from evidence to forecast. This limits both forecasting accuracy and auditability. We propose AuditForecast, an agentic scaffold for structured probabilistic forecasting. AuditForecast first anchors the forecast with a suitable quantitative baseline model, uses model-guided data retrieval to derive a base probability, and then applies situational factor updates outside the model's scope through mechanical aggregation in odds space. This turns forecasting from a prose-based judgment into a structured process with explicit intermediate objects. Across multiple live forecasting benchmarks, AuditForecast improves forecasting accuracy and calibration re

---

### [226] AutoLexSteer: Automatic Contrast Construction for Lexical Activation Steering

**链接**: https://arxiv.org/abs/2609.06879
**作者**: Shuhe Wang, Lachlan Cowley, Eduard Hovy, and Jey Han Lau
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Steering vectors have rapidly emerged as a popular and effective method for guiding the output of LLMs in very specific ways. But constructing accurate steering vectors is a difficult manual process due to the opacity of embeddings. We introduce Hangman, a novel type of steering vector that operates using word senses, as well as AutoLexSteer, the first fully automated process for building steering vectors. AutoLexSteer employs families of closely-related words extracted from WordNet to specify both the steering source to be avoided and the desired steering target. The steering vectors are quite precise, can be used to steer at the level of words and sets of word senses (meanings), and are able to steer certain LLM behaviors like sycophancy. The dataset and code can be found at https://github.com/ShuheWang1998/autolexsteer.

---

### [227] Generating Adversarial Texts for Machine Translation via GRPO

**链接**: https://arxiv.org/abs/2609.06048
**作者**: Florian Zogaj, Jakob H\"utteneder, Giovanni De Muri, Federico Villa, Aryan Sood, Vil\'em Zouhar
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As machine translation (MT) systems continue to improve, standard benchmarks become less informative for exposing remaining weaknesses. Traditional methods for creating challenging test sets rely on expensive manual creation or curation, while automated approaches struggle to produce sets with the necessary translation difficulty and linguistic diversity. We propose a scalable reinforcement-learning-based approach for rewriting existing source texts into instances that are more difficult to translate for MT systems. We fine-tune a large language model with Group Relative Policy Optimization (GRPO), using reward signals based on translation difficulty together with constraints for semantic similarity, grammaticality, and approximate length preservation. On WMT25, our approach substantially reduces average COMET translation quality from 0.63 to 0.48, while preserving grammaticality and readability, whereas the base model remains at 0.64. Evaluations on the unseen WMT19-WMT24 benchmarks c

---

### [228] SPARROW: Scalable Taxonomy Induction via Structure-Preserving Partitioning and Constraint-Guided Merging

**链接**: https://arxiv.org/abs/2609.07307
**作者**: Yirui Zhang, Yixuan Tang, Yandong Sun, Mong-Li Lee, Anthony Kum Hoe Tung
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Taxonomy induction aims to organize concept sets into coherent hierarchical structures. Recent LLM-based methods can induce taxonomies directly from flat term lists, avoiding the need for corpora, but degrade sharply as concept sets scale up. We argue that this degradation stems not only from context length limitations, but also from structural failures in hierarchical reasoning. To address this, we adopt a divide-and-merge paradigm that partitions concepts into smaller subsets, induces local taxonomies, and merges them into a global hierarchy. However, we identify two structural failure modes inherent to this paradigm: Structural Fragmentation, where partitioning weakens local hierarchical signals, and Parent Displacement, where locally plausible relations are misplaced in the global hierarchy. To address both, we propose SPARROW, a scalable taxonomy induction framework that combines structure-preserving spectral partitioning to retain hierarchical connectivity within each block, and 

---

### [229] Agentic ML Exploration (A-MLE) for Ads Ranking

**链接**: https://arxiv.org/abs/2609.08248
**作者**: Erwin Gao, Vinodh Kumar Sunkara, Jingyi Guan, Qinjin Jia, Hangjun Xu, Xiang Ji 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern industrial ads ranking stacks are increasingly bottlenecked not by model capacity or training compute, but by the throughput of human ML iteration - the cycles of research, implementation, training, debugging, evaluation, and launch required to surface a single statistically significant improvement. A typical ranking stack contains numerous differentiated models with heterogeneous data, architectures, and infrastructure constraints, and each cycle takes days to weeks of senior engineer attention per model. As a result, techniques that have proven effective on one model diffuse into others slowly and unevenly, leaving substantial recoverable signal unexplored. We present Agentic ML Exploration (A-MLE), an autonomous LLM-agent system that systematically explores ML techniques across a portfolio of ads ranking models. A-MLE decomposes ML iteration into five stages involving hypothesis generation, exploration strategy, experiment execution, result analysis and shared knowledge subst

---

### [230] Elastic Horizon: Discovering the Effective Interaction Frontier in Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.07247
**作者**: Gangyi Zhang, Junjie Meng, Letian Zhang, Wei Wu, Yang Zheng, Dong Wang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling the interaction horizon-the maximum number of environment interactions per episode-improves LLM agents on long-horizon tasks, and curriculum-based methods that progressively expand the horizon outperform fixed-horizon alternatives. However, existing schedules are open-loop: they monotonically increase the horizon until a manually specified maximum, with no mechanism to detect when further expansion stops helping. We propose the effective interaction frontier hypothesis: a dynamic boundary beyond which additional interactions yield diminishing returns while cost grows linearly. We then introduce Elastic Horizon, a closed-loop controller that tracks this boundary via the 90th percentile of successful trajectory lengths. On AppWorld and BFCL, fixed-horizon sweeps reveal clear saturation plateaus; Elastic Horizon stabilizes the horizon inside the saturation band from both under- and over-capacity initializations, attains the best success rates across 7B and 14B backbones, and saves

---

### [231] More Than Mimicking Reviewers: Evaluating LLMs for Pre-Submission Peer Review

**链接**: https://arxiv.org/abs/2609.05788
**作者**: Pouya Parsa, Amin Rezaei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer-review feedback often arrives too late for authors to make meaningful revisions. We study an author-facing LLM system that moves part of this stress test before submission: it generates a broad pool of atomic concerns and compresses them into a short report. We evaluate agreement with historical reviews and, separately, the possible validity of concerns they omit. From 10,000 ICLR 2026 submissions, we use 3,398 manuscripts with accessible versions that predate review. On a ten-paper diagnostic, independent sampling covers 44.9% of historical issues; deduplication and refill reaches 78.7% strict and 84.9% seriousness-weighted coverage, at 3.6$\times$ more requests and 5.2$\times$ more tokens. A hidden Top-32 Oracle preserves the full 79.3% weighted coverage of a 256-candidate pool, but paper-only selectors retain only 40--44%. LLM review therefore provides broad coverage with a large candidate pool but compresses poorly; ablations identify representative selection and matcher sensi

---

### [232] From Event Logs to Governed Action: A BlueSky Agenda for Agentic Process Mining

**链接**: https://arxiv.org/abs/2609.07984
**作者**: Yiyuan Yang, Zheshun Wu, Yong Chu, Zhenghua Chen, Zenglin Xu, Qingsong Wen
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Process mining has long turned event logs into process knowledge: discovered models, conformance evidence, bottleneck diagnoses, and runtime predictions. Agentic AI changes the target. Process-aware agents will not only ask what happened. They will ask whether a proposed action should be taken, given the available evidence, privacy budget, organizational authority, and downstream risk. This BlueSky paper proposes event-to-action process mining: a process-mining agenda for transforming heterogeneous operational event data into governed action. The goal is not another dashboard, a generic enterprise simulator, or a language interface over logs. We argue that the community needs four mineable artifacts: event-object representations, action evidence packages, governance contracts, and benchmarks where act, defer, ask, and refuse are all valid outputs. This agenda is timely because agentic business process management (BPM), LLM-assisted process mining, object-centric event standards, causal

---

### [233] Look Before You Prompt, and After: Scaffolding Human-AI Collaboration in Software Tutorial Creation

**链接**: https://arxiv.org/abs/2609.05563
**作者**: Avinash Bhat, Vy Bui, Jin L.C. Guo
**来源**: cs.SE cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With LLMs, creating software tutorials now involves steering the model's output and shaping it into a coherent, accurate learning resource, yet existing LLM tools offer writers little support for this work. By analyzing interviews with technical writers ($N=17$), we identify three requirements for how they assemble and structure multiple LLM responses, curate the context the model uses, and verify the generated content. We designed a tool called dBlocks with the following features: blocks to scope content, a context manager to edit context, and inline execution to verify code. Following a human-centered design method, we iteratively refined the design through a user study ($N=5$). In a within-subjects lab study ($N=16$) comparing dBlocks with participants' preferred workflows for LLM-assisted authoring, participants reported significantly higher confidence in the tutorials they produced with dBlocks. In addition, the tool reduced friction in verification, with writers verifying code as

---

### [234] Evaluating Deep-Search Agents under Hierarchical Web Evidence Poisoning

**链接**: https://arxiv.org/abs/2609.06027
**作者**: Zhongan Bi, Qiwen Wang, Jianrong Jiang, Jigang Ding, Wenwen Xiong, Changhua Meng 等 (10 人)
**来源**: cs.CR cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Search-augmented LLM agents are increasingly used for consumer decisions, making them vulnerable to Generative Engine Optimization (GEO) poisoning. Existing benchmarks largely measure whether manipulated content is retrieved or endorsed, but do not track whether an agent verifies suspicious evidence, revises adopted claims, or recovers before producing its final recommendation. We introduce HAE-GEO, a benchmark that tracks the full trajectory from exposure to recovery under progressively more persuasive Web poisoning. Agents interact via a multi-turn Search-Scrape interface across three attack levels (L1 direct assertion, L2 contextual camouflage, and L3 apparent corroboration), supported by a controlled corpus of 72,039 clean pages and 770 poisoned pages per level spanning 8 product categories and 154 brands. Evaluation combines deterministic behavioral measures with six semantic rubric dimensions. Evaluating 10 agents, we find three recurring patterns: evidence recognition degrades u

---

### [235] Do Large Language Models Know What They Don't Know II? A Fully Behavioral, Non-Cognitive Measure of Epistemic Honesty

**链接**: https://arxiv.org/abs/2609.07879
**作者**: Ali \c{S}enol, H. Russell Bernard, Huan Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are frequently confident, eloquent, and well versed. A natural question arises: do they know what they don't know? To answer this question, we borrow the concept of epistemic honesty and develop a novel metric to systematically evaluate whether an LLM appropriately acknowledges the boundaries of its knowledge. In this work, we introduce the Epistemic Honesty Quotient (EHQ), which reports three observable sub-scores across two operational axes (epistemic restraint and substantive-answer calibration), and construct EHQ-3000, a 3,000-question benchmark spanning Fabricated Entity, Post-Cutoff Event, Hyper-Niche True, and Context-Conditioned Questions. From a frozen registry of 21 model API routes, 15 completed the protocol after endpoint and eligibility checks; 14 entered the confirmatory analysis because severe provider-side truncation made one route's score indeterminate. The study reveals substantial variation across models, including a difference that can n

---

### [236] A visual large language foundational model for medical image recognition using clinician-oriented social media

**链接**: https://arxiv.org/abs/2609.06914
**作者**: Lingxuan Hou, Yuhua Xie, Yue Hu, Yan Zhuang, Junqi Li, Chengzhi Xia 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated strong capabilities across diverse domains, showing considerable potential in medicine. However, their application in medical settings remains limited by the scarcity of visual question answering (VQA) datasets that capture clinical reasoning and explicit image-text alignment. Here, we leverage de-identified medical images and expert commentaries shared on clinician-oriented social media. By combining an advanced LLM with clinician-in-the-loop verification, we established a rigorous pipeline to construct ThoughtMed-1M, a long-form medical VQA dataset containing over one million VQA pairs and designed to capture structured clinical logic and medical image-text alignment. To demonstrate its utility, we developed a FOundational LLM Trained on ThoughtMed-1M (FOLTMed). FOLTMed achieved state-of-the-art performance across 42 medical VQA benchmark datasets, with a macro accuracy of 85.4%, and generated more clinically coherent responses on the Th

---

### [237] SentryLine: Evidence-Grounded Question Answering over Evolving Documents in Oncology Care

**链接**: https://arxiv.org/abs/2609.08364
**作者**: Tampu Ravi Kumar, Gaurav Najpande, Muhammad Ali Khan, Kaneez Zahra Rubab Khakwani, Karan Kathuria, Shorya Azriel Moses 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Oncology care operates at constant pressure of absorbing rapidly evolving evidence base in biomedicine. The American Society of Clinical Oncology (ASCO) addresses this through living guidelines, but the format introduces a new burden: any recommendation can change at any point, across multiple versioned documents. We present SENTRYLINE, a living guideline-aware clinical question answering system. SENTRYLINE retrieves guideline passages through a vectorless hierarchical RAG pipeline and returns a role-specific answer with inline citations, factual and temporal verification reports, and drift detection notes that surface when a guideline has been updated. We construct ASCOBENCH, a benchmark of 405 three-turn conversations across four question categories with gold answers from expert annotators(clinicians), and use test set to evaluate SENTRYLINE against five baselines under an LLM-as-judge framework. Experiments across three generation backbones show consistent improvements over four ret

---

### [238] UniRRM: Unified Reasoning Reward Models Across Languages and Evaluation Paradigms

**链接**: https://arxiv.org/abs/2609.05910
**作者**: Peng Lai, Yichao Du, Junchao Wu, Weibo Gao, Linan Yue, Longyue Wang 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) excels on tasks with verifiable rewards, but in open-ended tasks, the reliability of reward models remains a key challenge. Existing solutions either depend on costly proprietary LLM-as-a-Judge systems or opaque scalar reward models that lack interpretability. Recent works on generative reward models offer a promising alternative, but they remain constrained by static evaluation criteria, fragmented evaluation paradigms, and limited multilingual support. To address these challenges, we introduce \textbf{MixReward}, a large-scale multilingual dataset spanning six domains and 103 languages, containing both pairwise and listwise data, and propose \textbf{UniRRM}, a unified reasoning reward model supporting multiple languages and evaluation paradigms. UniRRM uses a staged reasoning chain to dynamically generate task-generic and instruction-specific criteria, enabling fine-grained, input-adaptive judgments while maintaining consistency across languages. Experimen

---

### [239] FreqBLiMP: Frequency-Controlled Minimal Pairs Reveal Robustness and Fragility of LLMs Under Lexical Rarity

**链接**: https://arxiv.org/abs/2609.07153
**作者**: Tyrone White and Yuki Arase
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Minimal-pair benchmarks such as BLiMP evaluate linguistic knowledge by testing whether language models (LMs) prefer acceptable sentences over minimally different unacceptable ones. However, these benchmarks largely ignore lexical frequency variation, despite lexical frequency being a pervasive and highly skewed property of natural language use. Consequently, existing evaluations do not test whether grammatical preferences remain stable when contrasts involve rare lexical items. We introduce FreqBLiMP, a frequency-controlled extension of BLiMP that regenerates all 67 paradigms under explicit Zipf-frequency regimes while preserving each minimal-pair's grammatical contrast. Evaluating multiple open-weight LLM families across scales, we find that decreasing lexical frequency produces a consistent, monotonic decrease in sentence likelihood, but only a modest reduction in overall contrastive acceptability accuracy. However, this aggregate stability masks substantial variation across linguist

---

### [240] EvolveScaler: Synthesizing Information-Evolution Contexts via Executable State Machines and Natural-Language Rendering

**链接**: https://arxiv.org/abs/2609.08435
**作者**: Ziliang Zhao, Zenan Xu, Shuting Wang, Zhao Wang, Bowen Cao, Minda Hu 等 (9 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In persistent interactions, long contexts may encode an evolving process rather than a fixed record: later events can revise or revoke earlier information, changing what remains valid and what conclusions follow. We call this setting information evolution (IE). Solving IE requires identifying valid records, applying updates in order, and reconstructing the query-relevant state from the event history. Existing text-first synthesis pipelines make such data difficult to verify because state transitions and answer logic remain implicit. We introduce EvolveScaler, a code-driven framework that defines information evolution before rendering it as natural language. Human-authored operational specifications define state transitions, record validity, difficulty controls, and executable answer logic; a strong LLM then synthesizes a self-contained simulator from each specification. Executing validated simulators produces natural-language multi-turn event histories, while deterministic replay compu

---

### [241] Recompilation Is Not Enough: Test-Guided Decompiled-C Repair

**链接**: https://arxiv.org/abs/2609.07201
**作者**: Yuhan Huang and Puzhuo Liu and Jianlei Chi
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decompiled C often becomes recompilable only after repair, but recompilation alone does not establish test-observed behavior. A recompiled command-line binary can still parse options incorrectly, print different bytes, or return a different exit status. We present a few-step workflow for repairing decompiled C using compiler feedback and related official tests. Compiler and linker diagnostics first guide build repair. Once the repaired C recompiles into a binary, smoke checks and related official tests expose behavioral discrepancies for semantic repair. In a preliminary static-enriched evaluation on 104 Coreutils 9.5 binaries with available decompiler exports and deterministic exact-output smoke comparisons, 91 binaries (87.5%) recompile and pass the test gate; 9 do not recompile within the repair budget, and 4 recompile but still fail the test gate. The result suggests that test-gate feedback can make LLM-assisted repair of decompiled C more auditable than compile-only recovery.

---

### [242] DFlow: Enabling Verifier Information Flow in Block Diffusion Speculative Decoding

**链接**: https://arxiv.org/abs/2609.06498
**作者**: Yaojie Zhang, Linfeng Zhang, Bin Cui, and Xupeng Miao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Block diffusion speculative decoding improves LLM inference efficiency by proposing a block of future tokens in parallel and verifying them with a single forward pass through the target model. However, existing methods retain only the accepted prefix and discard the rejected suffix, preventing the computation spent on these positions from benefiting subsequent drafting rounds and forcing the drafter to repeatedly reconstruct representations for future tokens from scratch. We observe that rejection only determines whether a proposed token can be committed, while the verifier representations at rejected positions can still provide useful information for subsequent predictions. Based on this observation, we propose DFlow, a simple yet effective framework that enables verifier information to flow across drafting rounds. DFlow reuses the hidden states produced by the target verifier for the rejected suffix to guide subsequent drafting without additional target computation. To effectively le

---

### [243] Retrieval-Augmented Multi-Prompt Ensemble for Minor-Grain Breeding Information Extraction

**链接**: https://arxiv.org/abs/2609.07134
**作者**: Hang Zhao, Jiahao Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents our system for CCL2026-Eval Task 5: Minor-Grain Breeding Information Extraction (MGBIE), which jointly extracts 12 entity types and 6 relation types from minor-grain breeding literature. We propose RAME (Retrieval-Augmented Multi-Prompt Ensemble), a training-free framework that elicits multiple LLM outputs under controlled diversity and aggregates them by majority voting to obtain high-confidence predictions. RAME combines (i) retrieval-augmented few-shot selection via a hybrid BM25-embedding retriever, (ii) a three-prompt ensemble (Strict, Relaxed, Balanced) spanning the precision to recall spectrum, and (iii) large-scale repeated sampling with majority voting to filter noisy predictions. Built on DeepSeek-V4-Flash, RAME achieves a Total Score of 0.499 (NER 0.730, RE 0.346) on the leaderboard, ranking 1st and surpassing the official Track-A baseline powered by GPT-5.5 (0.448), representing an 11.4% relative improvement. Code is available at https://github.com/king-

---

### [244] Automated Design of Inventory Policy with Large Language Models: An Exploratory Study

**链接**: https://arxiv.org/abs/2609.08071
**作者**: Fenghua Yang, Preet Baxi, Yi Zhang, Stefanus Jasin, Yanzhe Lei, Mo Liu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Firms making inventory decisions have access to operational data, optimization tools, and large language models (LLMs). Typically, data characterize the operating environment, optimization selects parameters within a prespecified inventory policy class, and LLMs support coding and decision analysis. We develop an integrated framework that combines these resources to automate inventory policy design. Given demand data, the framework iteratively uses an LLM to generate parameterized policy classes and an external solver to optimize its parameters within each class. Across 30 lost-sales inventory instances, the mean cost reduction relative to optimized base-stock benchmarks increases from 17.5% after one generation to 30.0% after ten generations. Parameter optimization is central to this performance: an LLM-only variant performs substantially worse, whereas optimization-guided feedback improves policy quality, accelerates search, and directs the LLM toward better policy classes rather tha

---

### [245] MM-SVGEdit: A Multimodal-Driven SVG Editing for UI Design

**链接**: https://arxiv.org/abs/2609.06116
**作者**: Shibo Yang, Yuqing Gao, Zipeng Liu
**来源**: cs.HC cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the field of UI design, Scalable Vector Graphics (SVG) is widely used as a design medium. However, traditional SVG editing techniques have high entry barriers and require cumbersome manual iteration, while LLM-based editing solutions suffer from low accuracy and poor user controllability. To address these issues, we propose MM-SVGEdit, a multimodal-driven SVG editing approach that integrates traditional SVG editing and LLM-based methods. We introduce a two-stage strategy in which visual grounding is followed by modification. Both stages support two interaction modalities: natural language instructions and direct manipulation (mouse and keyboard). We trained and evaluated MM-SVGEdit on a self-constructed dataset of 14,476 question-answer pairs generated from UIs, covering 11 types of editing operations on both single and multiple UI targets. The results show that MM-SVGEdit improves SVG editing accuracy, efficiency, and user-perceived control while reducing token consumption and resp

---

### [246] Aegix Pulse: A Traceable Three-Stage Architecture for Personalized Content Generation and Context-Preserving Revision

**链接**: https://arxiv.org/abs/2609.07672
**作者**: Hongnan Zhao, Shiyu Chen, Zhihao Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Production content-generation systems must integrate a user's immediate task, long-term brand identity, historical evidence, and revision feedback. We present Aegix Pulse, a production-oriented three-stage architecture that separates current-task clarification and Task Persona finalization, long-term Account Profile (Brand DNA) assembly, and controlled generation and revision while preserving provenance across content versions. We evaluate four preregistered claims using 96 synthetic social-media generation tasks. Four initial-generation conditions progressively introduced a Task Persona, Account Profile, and successful-history style evidence, while two revision conditions compared plain and context-preserving revision. The experiment produced 480 completed generation records and 1,440 blinded LLM-Judge evaluations, supplemented by human review. Adding the Account Profile increased mean brand-consistency scores by 0.1562 points on a five-point scale compared with Task Persona alone (Ho

---

### [247] Data Scout: Targeted Web Crawling for Domain-Specific Pretraining Corpora

**链接**: https://arxiv.org/abs/2609.05766
**作者**: Chirag Garg, Eelaaf Zahid, Farhan Ahmed, Jay Pankaj Gala, Eric Butler, Heiko Ludwig
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The dominant approach to building domain-specific pretraining corpora is to filter large web archives such as CommonCrawl. This works well for popular domains but breaks down for specialized ones, where relevant content is sparse and often beyond the reach of popularity-driven crawlers. We present Data Scout, which inverts this: instead of filtering an archive, it directs a targeted crawl. An LLM expands a root topic into a taxonomy and thousands of search queries; the returned URLs (seeds) are grouped by subdomain and screened with a user-supplied classifier (the probe), admitting each subdomain on the basis of a small sample. This works because relevance has a sharp boundary at the subdomain level: in mathematics, a page is 21x more likely to be relevant than one on a sibling subdomain. With the FineMath classifier as the probe, 21.9% of crawled pages are high-quality math content, 70x the 0.31% rate from filtering a comparable web sample, so the crawl wastes far less effort. But the

---

### [248] OntologyBench: Can Dense Retrieval Satisfy Structured Biomedical Constraints?

**链接**: https://arxiv.org/abs/2609.08174
**作者**: Xiao Yu Cindy Zhang, Wyeth Wasserman, Jian Zhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce OntologyBench, a tiered biomedical retrieval benchmark comprising 471,854 training and 125,744 evaluation query-document relevance pairs across concept grounding, relational retrieval, and compositional phenotype-based retrieval. Although these tasks can be tractable using ontology-aware reference methods, across task tiers, embedding performance is generally lower on relational and compositional tasks than on concept-grounding tasks. Fine-tuning on ontology-derived supervision improves performance on several relational and compositional tasks, whereas the evaluated reranking and LLM-based candidate-scoring methods provide little or no end-to-end improvement. Errors frequently reflect diseases matching only subsets of the phenotype evidence. These findings indicate that the evaluated embedding and reranking configurations do not reliably recover the compatibility encoded by the selected ontology relations and phenotype combinations and motivate retrieval systems that bette

---

### [249] AAS-RAIL: Improving Information Extraction for Asset Administration Shells through Retrieval-Augmented In-Context Learning

**链接**: https://arxiv.org/abs/2609.07334
**作者**: Janek Gro{\ss}, Jens Heidrich
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Asset Administration Shell (AAS) is a cornerstone of Industry 4.0 and the Digital Product Passport, providing standardized digital representations of industrial assets. While manufacturers already maintain extensive technical product documentation, generating AAS instances from existing product datasheets remains a labor-intensive task because technical information is extracted from heterogeneous document structures and often involves company-specific terminology and conventions. In this work, we present AAS-RAIL, a retrieval-augmented information extraction (IE) approach that automatically generates Asset Administration Shells from PDF product datasheets using large language models (LLMs). Instead of relying on a fixed set of few-shot examples, the proposed retrieval-augmented in-context learning (RAIL) approach retrieves LLM-generated extraction helpers from similar Asset Administration Shells to provide instance-specific in-context learning (ICL). This enables the model to adapt

---

### [250] Reasoning Beyond Transcription: Audio Language Models on Child Stuttering Speech

**链接**: https://arxiv.org/abs/2609.07968
**作者**: Chibuzor Okocha, Christan Grant, Zoey Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Child speech differs from adult speech in acoustics, prosody, and linguistic structures. Speech disfluencies (such as repetitions) further challenge automatic understanding. While Audio Language Models (ALMs) show strong semantic reasoning from speech audio, their ability to reason about disfluent child speech in mixed-speaker settings remains unexplored. We investigate this through two tasks: child-focused semantic summarization and speech entailment. Experiments use recordings of children who stutter in mixed speaker interviews without explicit speaker separation. Models are instruction-guided to focus on the child, preserve clinically relevant disfluencies, and avoid adult-speech leakage. Evaluation combines LLM-based judges and reference-based metrics, anchored by transcript-oracle baselines to isolate errors. Results show that while ALMs extract high-level meaning from stuttered speech, reasoning degrades significantly with increased

---

### [251] Diffs vs. Whole Files: An Empirical Comparison of Iterative Edit-Based and Direct Generation for Flutter/Dart Code Models

**链接**: https://arxiv.org/abs/2609.05779
**作者**: Andrej Andrejev
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models used for code editing can be trained and deployed in at least two output regimes: direct generation, where the model emits the entire modified file in one shot, and iterative diff-based generation ("steps"), where the model emits a sequence of localized search/replace edits applied one at a time until it signals completion or a step budget is exhausted. The diff-based regime is attractive because it mirrors how developers edit code and should require far fewer generated tokens per turn. We train two code models - a 100M-parameter model trained from scratch (Rainbow-Pony-100M) and a fine-tuned Qwen2.5-Coder-0.5B - in both regimes on a shared Flutter/Dart dataset, and evaluate all four resulting models on a held-out set of approx 1,790 tasks per model. Direct generation substantially outperforms diff-based generation on every metric we measure - compilation/static-analysis pass rate, bits-per-byte, character-level similarity to the reference, and blinded LLM-judge r

---

### [252] One MLLM, One Call: Efficient Zero-Shot Vision-and-Language Navigation via Spatial-Aware Waypoints

**链接**: https://arxiv.org/abs/2609.06476
**作者**: Shiqi Pan, Qi Zheng, Hanqin Sun, Youjian Zhang, Daquan Feng, Xu Wang
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-and-Language Navigation in Continuous Environments (VLN-CE) requires an embodied agent to navigate unseen environments by following natural language instructions. Current zero-shot VLN-CE methods either rely on pre-trained waypoint predictors or require multiple queries to large models per step. To address prohibitive inference latency and computational overhead, we propose O2C-Nav, an efficient zero-shot navigation framework that calls only a single large model once per decision step. Our approach introduces a training-free structured waypoint generator and a novel abstract representation that projects sparse, history-aware candidate waypoints directly onto RGB images as visual markers. The MLLM selects a waypoint or generates a fallback target bounding box at each step, while a low-level Fast Marching Method (FMM) planner converts the selected target into an executable collision-free path. This paradigm provides the model with concrete spatial perception and explicit memory wh

---

### [253] AnchorScore: A CLIP-Based Diagnostic of MLLM Annotation Difficulty

**链接**: https://arxiv.org/abs/2608.16690
**作者**: Yan Ma and Lizhuo Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [254] SupGRPO: Enhancing GRPO with Matching-based Online SFT for Text Spotting

**链接**: https://arxiv.org/abs/2609.07081
**作者**: Xudong Xie, Yuzhe Li, Jing Shi, Zhifei Zhang, Curtis Wigington, Zhaowen Wang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text spotting requires both accurate text recognition and precise spatial localization. Current specialised spotters excel at predicting tight bounding boxes in natural scenes, but falter on complex or artistic text, whereas multimodal large language models (MLLMs) possess strong recognition capabilities yet remain weak at localisation. To equip the text spotter with general and powerful recognition capabilities and to maximize its localization ability, we explore two MLLM-based fine-tuning methods: Supervised Fine-Tuning (SFT) and reinforcement learning fine-tuning based on Group Relative Policy Optimisation (GRPO). An interesting finding is that SFT is less effective than GRPO at enhancing recognition, while GRPO is less effective than SFT at enhancing detection. To compensate for each other's shortcomings, we introduce a joint training strategy, SupGRPO, which simultaneously optimizes the model using both SFT and GRPO. SupGRPO employs the specially designed reward functions and deve

---

### [255] SAFIRE: Safety-Critical Benchmark for Fine-grained Fire and Smoke Understanding in Multimodal LLMs

**链接**: https://arxiv.org/abs/2609.07823
**作者**: Pengfei Li, Naufal Suryanto, Sicheng Zhang, Mohammad Alsharid, Muzammal Naseer
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) show strong progress on vision-language tasks, yet their reliability in safety-critical settings remains underexplored. Fire-smoke understanding is central to public safety and disaster response, but most existing benchmarks lack diverse real-world scenarios and context-aware evaluation. We introduce SAFIRE, a large-scale benchmark for fire-smoke understanding in MLLMs, comprising 83K captioned images from 20 scenarios and 193K multiple-choice VQA (MCVQA) generated from a 9.7K-image subset, spanning 10 evaluation dimensions from basic perception to higher-order reasoning. A GPT-5.4-assisted multi-stage verification pipeline with MLLM majority voting ensures annotation quality. Evaluating ten open-source MLLMs (8B-38B) yields an average accuracy of 61.9%, exposing major gaps in safety-critical reasoning. We further show that adapting vision encoders with only 7% of our domain-specific data boosts fire-scene classification accuracy from 20.1% to 6

---

### [256] Concord: A Video Relational Algebra for Cross-Modal Query Optimization

**链接**: https://arxiv.org/abs/2609.05756
**作者**: Sultan Muratbek, Charisse Ivana Yeung, Chanwut Kittivorawong, Alvin Cheung
**来源**: cs.DB cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic video queries let users embed natural language prompts and use multimodal large language models (MLLMs) to interpret the video. Such queries are increasingly popular for querying video data. However, their expressiveness comes at a steep cost: an MLLM may process hours of media to return only seconds of relevant output, making naive execution slow, expensive, and inaccurate. We propose Concord, a system for expressing and optimizing semantic video queries. We makes three contributions. First, we introduce Video Relational Algebra (VRA), a nested algebra over videos, transcripts, frames, and object tracks that captures common semantic video operations. Second, we derive a set of approximate optimizations that rewrite VRA queries to reduce MLLM usage while improving result quality. For narrated video, Concord either processes transcripts instead of video or uses them to identify video clips for MLLM processing. For cross-camera queries without narration, detection and tracking r

---

### [257] Dual-Latent Memory Routing for Vision-Language Reasoning

**链接**: https://arxiv.org/abs/2609.05539
**作者**: Hao-Xuan Ma, Jin-Fei Qi, Yicheng Xiao, Han-Jia Ye
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have recently made strong progress in vision-language reasoning, yet their performance often degrades as generations grow longer. A key factor is that they frequently lose track of earlier visual evidence and intermediate constraints under a monolithic growing context. Inspired by how humans separately recall what they see and what they infer when solving complex tasks, we propose DLMR, a parameter-efficient mechanism that equips MLLMs with Dual Latent Memories: a visual memory that compresses image evidence and a reasoning memory that tracks intermediate conclusions and constraints. A Router then dynamically decides which memory and how much to reuse during inference, preserving visual grounding while maintaining coherent long-horizon reasoning. DLMR is trained in three stages, from latent memory construction to selective router learning, while keeping the base MLLM frozen, yielding substantial gains on both general and reasoning benchmarks wit

---

### [258] SeGDeP: Semantic- and Geometric-Aware Decoupled Prompts for Reasoning Segmentation

**链接**: https://arxiv.org/abs/2609.08867
**作者**: Linnan Zhao, Xu Liu, Lingling Li, Licheng Jiao, Fang Liu, Wenping Ma
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning segmentation converts an implicit linguistic conclusion into a precise mask, requiring both semantic identification and spatial grounding. Existing MLLM-segmenter interfaces either use a special trigger or compress both signals into one context, although they receive different supervision and fail differently. This coupling obscures whether a failure arises from target interpretation or from localization. We present SeGDeP, an explicit what-where interface. A semantic prompt branch and an independent geometric projection path transform resolved MLLM states into semantic features and a DETR-predicted box, which jointly condition a SAM 3 mask decoder. Training first aligns this executable interface, then uses group reward-decoupled policy optimization (GDPO) to balance format, box-IoU, and mask-IoU feedback. SeGDeP-4B reaches 82.7 average cIoU over eight RefCOCO-family splits and 66.0/59.6 gIoU on ReasonSeg val/test while adapting only 0.38% of Qwen3-VL parameters through LoRA.

---

### [259] EEG-Driven Decoding Framework for Passenger Hazard Perception in Highly Automated Vehicles

**链接**: https://arxiv.org/abs/2609.07128
**作者**: Yingkai Yang, Ashton Yu Xuan Tan, Bowen Li, Xiaorong Gao, Sifa Zheng, Jianqiang Wang 等 (10 人)
**来源**: cs.AI cs.LG eess.SP
**匹配关键词**: EEG, BCI, Brain-Computer Interface
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable risk assessment remains a central challenge for Autonomous Vehicles (AVs). Despite advances in automation, passenger cognition provides a non-intrusive auxiliary signal that improves both objective and perceived safety without requiring active human intervention. We introduce an Electroencephalogram (EEG)-based Brain-Computer Interface (BCI) that decodes passenger neural responses for both Risk Prediction (RP) and Danger Identification (DI), explicitly modeling humans as passengers to match real-world AV use. To achieve this, we propose the Passenger Cognitive Model (PCM), Risk-aware Sequential Labeling (RSL), and the Passenger EEG Decoding Strategy (PEDS), which integrates a 3D Convolutional Recurrent Neural Network (3D-CRNN) model for joint EEG decoding. Experimental results show that 3D-CRNN achieves a Balanced Accuracy (BA) of $95.3\% \pm 2.7\%$ in RP and improves single-subject DI from $80.9\% \pm 3.9\%$ to $85.0\% \pm 3.2\%$ with RSL. Event-wise analyses further show tha

---

### [260] SingLEM: Single-Channel Large EEG Model

**链接**: https://arxiv.org/abs/2509.17920
**作者**: Jamiyan Sukhbaatar, Satoshi Imamura, Ibuki Inoue, Shoya Murakami, Kazi Mahmudul Hassan, Seungwoo Han 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [261] Masked Generative-Contrastive Representation Learning for Cross-Dataset EEG-Based Emotion Recognition

**链接**: https://arxiv.org/abs/2607.04139
**作者**: Huqin Weng, Jiayang Huang, Yimin Wen, Jie Du, Chi-Man Vong, Chuangquan Chen
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [262] Mind-to-Face: Neural-Driven Photorealistic Avatar Synthesis via EEG Decoding

**链接**: https://arxiv.org/abs/2512.04313
**作者**: Haolin Xiong, Tianwen Fu, Pratusha Bhuvana Prasad, Yunxuan Cai, Haiwei Chen, Wenbin Teng 等 (8 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [263] NeuroWeaver: An Autonomous Evolutionary Agent for Exploring the Programmatic Space of EEG Analysis Pipelines

**链接**: https://arxiv.org/abs/2602.13473
**作者**: Guoan Wang, Shihao Yang, Feng Liu
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [264] iBrain: A Unified Foundation Model Reading the Brain from Surface to Spikes

**链接**: https://arxiv.org/abs/2609.06960
**作者**: Ying Chen, Tiou Wang, Zhifeng Yue
**来源**: cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Invasive neural recordings provide high-fidelity measurements of brain activity, with signals such as intracranial EEG (iEEG) and intracortical spiking activity capturing neural dynamics at different spatial and temporal scales. Yet existing neural foundation models have largely been developed independently for different invasive recording paradigms, leaving joint pretraining across heterogeneous invasive signals underexplored. In this work, we introduce iBrain, a unified foundation model that jointly learns from iEEG and spiking activity. iBrain employs signal-specific encoders to accommodate their distinct signal characteristics and a shared spatiotemporal Transformer backbone to model dependencies across recording channels and time. We pretrain iBrain on over 7,000 hours of heterogeneous neural recordings using masked signal reconstruction and channel-view alignment, promoting contextual modeling of neural dynamics and robustness across different channels. iBrain consistently outper

---

### [265] Human-AI Teaming Under Deception: An Implicit BCI Safeguards Drone Team Performance in Virtual Reality

**链接**: https://arxiv.org/abs/2511.19312
**作者**: Christopher Baker, Stephen Hinton, Akashdeep Nijjar, Riccardo Poli, Caterina Cinel, Tom Reed 等 (7 人)
**来源**: cs.HC
**匹配关键词**: BCI
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [266] EEG-VID: Task-Guided Latent Predictive Pretraining for EEG Decoding and Assistive Target Selection

**链接**: https://arxiv.org/abs/2609.00566
**作者**: Guanzhong Sun, Junyi Ma, Yuxuan Wu, Wei Tang, and Yanzi Miao
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [267] Secure Aggregation for Privacy-Preserving Federated Learning on Clinical EEG Data

**链接**: https://arxiv.org/abs/2607.28191
**作者**: Pouya Rajabi, Mohsen Toorani
**来源**: cs.CR cs.DC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [268] Adaptive Anisotropic Attention for Axis-Structured Signals

**链接**: https://arxiv.org/abs/2609.08788
**作者**: Mahir Jain, Parshva Runwal, Aditya Ray Mishra, Arvasu Kulkarni, Sandeep Singh, Siddharth Panwar
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dense self-attention treats all token pairs as equally plausible before learning, an interaction-isotropic prior that can be mismatched to structured signals. For structured, low signal-to-noise ratio (SNR) signals such as EEG, dependencies are organized along the electrode and time axes, and this uniform prior exposes each token to many irrelevant interactions. We introduce Adaptive Anisotropic Attention (AAA), which splits attention into two paths: a temporal path, where each token attends to the tokens of its own electrode across time, and a spatial path, where it attends to the tokens of the other electrodes at the same time step. A small gate predicts, for every token, a convex combination of the two path outputs: two non-negative weights that sum to one. On six EEG downstream tasks, the resulting model, AXON (AXis-factorized Operator Network), improves mean balanced accuracy over a dense baseline under both linear probing and full fine-tuning. We show that both paths (temporal an

---

### [269] A New Strategy for Artificial Intelligence: Training Foundation Models Directly on Human Brain Data

**链接**: https://arxiv.org/abs/2601.12053
**作者**: Ma\"el Donoso
**来源**: q-bio.NC cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [270] Foundation Models for Generalizable Semantic and Goal-Oriented Communication

**链接**: https://arxiv.org/abs/2609.07853
**作者**: Boliang Liu, Wint Yi Poe, Riccardo Trivisonno, Giuseppe Caire
**来源**: cs.LG cs.AI cs.RO eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic and goal-oriented communication is increasingly studied for 6G, but generalization beyond seen data remains a key weakness under tight rate budgets. Many existing systems overfit their training data and degrade sharply at very low bit rates because they attempt to compress the entire signal. We introduce Foundation Model-Guided Semantic and Goal-Oriented Communication (FMSGOC), a framework that uses broad visual-linguistic Foundation Model priors to mitigate overfitting. It further improves rate efficiency by concentrating bits on sparse, goal-aligned anchors and relying on generative foundation-model priors to reconstruct the masked regions. By decoupling what to send from how to reconstruct, a vision-language foundation model selects and transmits a sparse set of semantic anchors, while a pretrained diffusion model, fine-tuned for masked completion, reconstructs the image at the receiver. In our experiments, FMSGOC reaches 0.039 bits per pixel (BPP), maintains high semantic 

---

### [271] OdysSim: Building Foundation Models for Human Behavior Simulation

**链接**: https://arxiv.org/abs/2606.14199
**作者**: Xuhui Zhou, Weiwei Sun, Weihua Du, Jiarui Liu, Haojia Sun, Qianou Ma 等 (9 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [272] From Synthetic Priors to Model Behavior: Structural Coverage in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.06912
**作者**: He Zhao, Ryan Thompson, Daniel M. Steinberg, Ashfaqur Rahman, Edwin V. Bonilla, Cheng Soon Ong
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are commonly pretrained on large collections of procedurally generated synthetic tasks, yet it remains unclear how well these synthetic pretraining priors support the downstream tasks on which the models are evaluated. We study this question from a distribution-level attribution perspective. We recover or reconstruct the synthetic data generators of four TFMs and compare their generated tasks with datasets from two widely used tabular benchmarks. Each dataset is represented by a common set of structural descriptors capturing schema, feature distributions, dependence structure, response properties, and feature--response relationships. In this space, we measure how broadly and repeatedly each synthetic prior reaches benchmark tasks using structural coverage and normalized density, and examine whether stronger local support is associated with better predictive performance. We find substantial differences across synthetic pretraining priors: some generators

---

### [273] Concept-Level Risk and Calibration for Governance in Diffusion Foundation Models

**链接**: https://arxiv.org/abs/2609.08517
**作者**: Kun Xu, Yushu Zhang, Tao Wang, Shuren Qi, Barbara Carminati, Elena Ferrari 等 (7 人)
**来源**: cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion models have become a core paradigm for multimedia generation, offering powerful concept-driven controllability for personalization, semantic editing, and selective unlearning. However, as semantic control extends beyond natural-language prompts to learned embeddings and intervention pipelines, the safety and governance of these systems become increasingly difficult to evaluate in a unified manner, especially for safety-sensitive, identity-linked, and other privacy-relevant concepts. Existing studies mainly rely on heuristic audits, adversarial probing, or task-specific erasure benchmarks, and therefore provide limited support for systematic comparison across models, conditioning channels, and deployment conditions. We present a concept-level probabilistic audit and reporting framework for diffusion models. We formalize governance-relevant concept behaviors as Bernoulli semantic events induced by stochastic generation, and define a Concept Risk Operator that maps model-channel

---

### [274] Clinician-Friendly Foundation Models for Ophthalmic Image Diagnostics without Fine-Tuning or Technical Barriers

**链接**: https://arxiv.org/abs/2504.15928
**作者**: Meng Wang, Tian Lin, Qingshan Hou, Aidi Lin, Lianyu Wang, Jingcheng Wang 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [275] Explainable Diabetic Retinopathy Classification Using Vision Foundation Models

**链接**: https://arxiv.org/abs/2608.28207
**作者**: Abhishek Verma, Anila Krishna, Abhishek Gajanan Bankar, Juan Miguel Lopez Alcaraz
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [276] Adapting Vision Foundation Models to Acoustics for Pose-Free 3D Sonar Reconstruction

**链接**: https://arxiv.org/abs/2609.06261
**作者**: Kevin Zhang, Jingxi Chen, Mohamad Qadri, Russell Shomberg, Michael Kaess, Jia-Bin Huang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models trained on Internet-scale RGB datasets enable remarkable capabilities across a range of tasks, from text-to-video generation to few-shot 3D scene reconstruction. An acoustic foundation model trained on large-scale sonar datasets could enable similar capabilities in the underwater domain, where turbidity and low-visibility conditions make conventional RGB foundation models inapplicable. Unfortunately, a lack of freely available large-scale sonar datasets makes training such a model from scratch impractical. In this work, we demonstrate that vision foundation models can be efficiently adapted to the sonar setting by (1) exploiting the geometric relationship between the two sensing modalities and (2) employing accurate physics-based noise models for synthetic data generation. The resulting sonar adaptation models enable new capabilities: For the first time, we experimentally demonstrate sonar-based pose-free 3D reconstruction.

---

### [277] LoGIC: Budgeted Context Construction for Node-Level Graph In-Context Learning with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.05955
**作者**: Mingqi Yang, Zidong Guo, Jihui Yang, Wenming Zuo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models have become powerful graph learners. Systems such as G2T-FM and GraphPFN encode each node as a feature row and make predictions through in-context learning (ICL), with labeled rows serving as the prompt. Current protocols employ the complete training table as context, causing attention to scale quadratically with the labeled pool and introducing preprocessing and memory bottlenecks. We investigate context construction for node-level graph ICL: which labeled nodes and auxiliary unlabeled nodes should constitute the prompt for specified queries. We formulate this allocation in terms of two resources: a labeled-context budget for predictive evidence and an unlabeled-halo budget for adapter message passing without using label capacity. We present LoGIC, which retrieves labeled nodes via structural, feature-based, and coverage channels, shares each context across the queries in a graph-local cluster, incorporates an unlabeled halo for adapter backbones, and chooses

---

### [278] Hand-Object Interaction in the Age of Large Foundation Models:Reconstruction, Generation, and Embodied Transfer

**链接**: https://arxiv.org/abs/2607.28394
**作者**: Weiquan Lin, Yu Deng, Shiyang Liu, Luping Xiao, Xu Tang, Junzhi Yu 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [279] Streaming Hierarchical Inference with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.07956
**作者**: Vitor Crista, Afonso Louren\c{c}o, Diogo Martinho, Goreti Marreiros
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular Foundation Models (TFMs) have recently demonstrated strong predictive performance through in-context learning, but their deployment in high-throughput data streams remains challenging due to communication overhead and latency. We propose \textit{HINT}, a hierarchical inference framework that combines edge-based retrieval with cloud-based TFM inference. A graph-based approximate nearest neighbor memory maintained over a sliding window provides local predictions and uncertainty estimates, allowing confident samples to be processed locally while uncertain instances are selectively offloaded, together with their retrieved context, to a cloud-hosted TFM. The framework exposes an offloading threshold and a neighborhood retrieval policy that can be varied to balance predictive performance and communication cost. Experiments show \textit{HINT} consistently identifies favorable trade-offs.

---

### [280] CrACK: Adversarial Attacks on Cross-Model Consistency in Collaborative Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.07499
**作者**: Feifei Liu, Jintao Cheng, Chi Man Vong, Xiaoyu Tang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training-free collaborative pipelines that integrate Vision Foundation Models such as CLIP, SAM, and DINO achieve strong open-vocabulary dense prediction and are increasingly deployed in safety-critical applications. The security of these systems is commonly assumed to follow from the robustness of their individual models. We challenge this assumption. We identify a vulnerability shared by every collaborative pipeline: each model consumes the intermediate output of another without verifying semantic consistency, an unverified premise that we term the semantic-spatial alignment dependency. Existing adversarial attacks target a single model and overlook this premise, leaving the inter-model interface entirely unguarded. We propose CrACK (Cross-model Adversarial Consistency attack), an inference-time attack that exploits this interface without modifying any input pixel, model weight, or training data. CrACK operates in two stages: Adversarial Affinity Contradiction Injection corrupts the 

---

### [281] AdaptSplat: Adapting Vision Foundation Models for Feed-Forward 3D Gaussian Splatting

**链接**: https://arxiv.org/abs/2605.10239
**作者**: Mingwei Xing, Xinliang Wang, Yifeng Shi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [282] Cross-modal learning for SAR target recognition using optical vision foundation models

**链接**: https://arxiv.org/abs/2609.07753
**作者**: Lucas Hirsch, James R. Hopgood, Javid Khan, Yoann Altmann and Mike E. Davies
**来源**: cs.CV cs.LG eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic Aperture Radar (SAR) is an important modality in a wide range of imaging applications due to its versatile, long range and near all weather operating capabilities. However, Automatic Target Recognition (ATR) remains a challenging problem due to limited labelled data, the strong speckle in SAR images and the significant domain gap between SAR and more abundant optical imagery. In contrast, electro-optical (EO) imagery benefits from massive datasets, clearer visual structure and powerful foundation models. In this work, we investigate how vision foundation models trained on optical data can provide class level supervision for SAR classification. We propose a cross-modal EO to SAR prototype alignment framework in which a frozen EO encoder, based on a DINOv3 vision foundation model, is used to construct class level optical prototypes without requiring strict EO/SAR pairs. A SAR model is then trained to classify SAR images while aligning its embeddings to the corresponding EO clas

---

### [283] Federated Foundation Models over Vehicular Networks

**链接**: https://arxiv.org/abs/2606.06786
**作者**: Kasra Borazjani, Fardis Nadimi, Payam Abdisarabshali, Owen Palinski, Allan Salihovic, Dinh Nguyen 等 (8 人)
**来源**: cs.LG cs.NI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [284] DXPR: Depth-Based Vision-LiDAR Cross-Modal Place Recognition Using Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.09005
**作者**: Yungsoo Han, Youngseok Jang, Seungwon Roh, Jeongyeon Seo, H. Jin Kim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present DXPR, a depth-based cross-modal place recognition (CMPR) framework that uses vision foundation models (VFMs) to match monocular camera queries against a LiDAR map without modality-specific encoders. This enables robots and autonomous vehicles to robustly localize using only cameras within pre-built LiDAR maps, even under severe seasonal, weather, and illumination changes. The key idea is to convert both camera images and LiDAR scans into a unified depth image representation so that a single VFM backbone with an aggregation head can learn modality-invariant global descriptors. To make pairwise metric learning faithful to scene geometry, we introduce a geometry-aware overlap miner: after cross-modal scale alignment of camera and LiDAR depth, we forward-warp measurements between views to compute a pixel-level overlap score. This score relabels ambiguous pairs and adaptively modulates the positive margin in a multi-similarity loss to avoid overfitting on weakly overlapping views

---

### [285] TabBench-Bio: A Living Benchmark for Machine Learning on High-Dimensional Biomedical Tables

**链接**: https://arxiv.org/abs/2609.07441
**作者**: Jules Kreuer, Sofiane Ouaari, Julia Hellmig, Julius Braitinger, Nico Pfeifer
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biomedical tables often combine thousands of measured variables with only tens or hundreds of labelled samples, a regime that is poorly represented in general-purpose tabular benchmarks. We introduce TabBench-Bio, a living and interactive benchmark of 43 biomedical datasets spanning multiple domains. Under a shared cross-validation protocol, we compare classical estimators, neural networks, and tabular foundation models across 28 feature-by-sample operating points. At the reference cell of 10,000 features and 100 training samples, RealTabPFN v2.5 has the highest point estimate, followed by Logistic Regression and TabDPT, whose point estimates are nearly identical. A paired bootstrap over the target pool separates RealTabPFN v2.5 from Logistic Regression by 145 Elo (95% interval [59, 232]). Tabular foundation models generally occupy the leading ranks, while the strongest configuration depends on the operating point and biomedical modality. The AutoML framework AutoGluon, using its one-h

---

### [286] Effects of model architecture and learning strategies on deep learning-based recognition of activated sludge microscopic images and comparison with quantitative image analysis

**链接**: https://arxiv.org/abs/2609.08570
**作者**: Suguru Hakoshima, Tomohiro Tobino, Fumiyuki Nakajima
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Microscopic image analysis has long been recognized as a promising approach for monitoring activated sludge. In recent years, deep learning-based image analysis has been increasingly adopted in this field because of its high performance. However, previous studies on microscopic image analysis of activated sludge have rarely explored transformer-based models or self-supervised foundation models and have instead relied on CNNs and supervised ImageNet pretraining. In addition, previous studies often downsampled image sizes, but the effects of downsampling have not been sufficiently investigated, and the relationship between downsampling strategies and image analysis performance remains unclear. Furthermore, no study has quantitatively compared deep learning performance with quantitative image analysis (QIA), which was widely used before the emergence of deep learning. In this study, to examine how model architecture and learning strategies affect performance in microscopic image analysis 

---

### [287] Towards Unified Multimodal Graph Foundation Model: A Bridge-Router-Adapter Based Approach

**链接**: https://arxiv.org/abs/2609.06668
**作者**: Sirui Zhang, Yubing Zhou, Xunkai Li, Zekai Chen, Shumeng Li, Wang Luo 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal graphs couple node attributes in different modalities, such as text and images, with relational structure, enabling topological structure and cross-modality attributes to be modeled jointly. Multimodal graph foundation models seek unified representations from such data that transfer across different graph domains and downstream tasks. However, existing methods exhibit two fundamental limitations. (1) Cross-Scope Context Entanglement. They merge scope-specific graph contexts into a unified representation, obscuring their distinctions during multimodal construction. (2) Scope-Ignorant Modality Routing. They route modalities within a fixed graph scope, overlooking how modality relevance varies across neighborhood ranges. To address these challenges, we propose BRAIN, a unified model that focuses on graph context that combines neighborhood scope with modality composition. BRAIN comprises a scope-conditioned Bridge that combines structural information spanning local-to-global nei

---

### [288] Topology Obstructs Pure Foundation Neural Quantum States

**链接**: https://arxiv.org/abs/2609.07591
**作者**: Timothy Heightman, Elena Orlova, Philip Mantrov, Aleksei Ustimenko
**来源**: quant-ph cond-mat.dis-nn cond-mat.str-el cs.AI math-ph math.MP
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for ground states in spin-1/2 systems are a promising method for problems ranging from quantum chemistry to identifying new phase diagrams. Nearly all such models are currently pure-states that condition on the Hamiltonian's parameters, whose Monte Carlo samples give energy estimates according to the variational principle. In this contribution, we show that this representation is topologically obstructed. For any gapped Hamiltonian family whose ground-state bundle is non-trivial, every continuous normalized state-vector model has zero fidelity with the ground state at some parameter value in the Hamiltonian family. For that value, the energy is at least one spectral gap, $\Delta$, with an $O(\Delta)$ gap in an open-neighbourhood of that point. We show that this is a sufficient no-go also in the case of degenerate ground-state manifolds, time dynamics, and periodic systems with mixed space-time topology, demonstrating these obstructions on one- and two-qubit systems. W

---

### [289] Chimaera: A Mixture-of-Graph-Experts Architecture for Cross-Task and Cross-Dataset Graph Learning

**链接**: https://arxiv.org/abs/2609.08709
**作者**: Jonathan Frank, David Richerby, Ansgar Scherp
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing foundation models for graphs is challenging due to the irregular structure of graphs and the different sizes and characteristics of embeddings. Chimaera integrates mixture-of-experts with graph foundation models (GFM). It integrates different GFM architectures, such as graph prompts and linear GNN models. Large language models are used to generate embeddings, and experts can be trained and combined following different strategies, GFMs, embeddings, etc. Furthermore, Chimaera extends existing linear GNNs to support link-level and graph-level tasks in addition to node-level tasks. Empirical analyses are performed on same-task and cross-task experiments with node, link, and graph classification tasks using six benchmark text-attributed graph datasets. The experiments demonstrate the effectiveness of Chimaera and its capabilities for transfer across tasks and datasets. Further insights include the need to use both large and small language models to generate embeddings for the expe

---

### [290] Harnessing CLIP and DINO: An Uncertainty-Aware Cascaded Fusion Network for Generalizable Deepfake Image Detection

**链接**: https://arxiv.org/abs/2609.07670
**作者**: Xuechao Zou, Yi Zhou, Kai Li, Shun Zhang, Yuhui Chen, Congyan Lang 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing realism and accessibility of manipulated and generated faces threaten the trustworthiness of digital media. To detect such forgeries, deepfake detectors based on vision foundation models have shown promising performance, but they typically rely on a single pretrained representation and are prone to overfitting to particular training distributions. To improve generalization to unseen forgeries, we propose UCF-Net, an uncertainty-aware cascaded fusion network that harnesses CLIP's language-aligned semantic priors and DINO's self-supervised visual-structure priors. UCF-Net extracts hierarchical features across Transformer depths, uses layer-wise expert aggregation to adaptively combine each encoder's multi-level cues, and performs weighted fusion of the resulting representations based on entropy-derived uncertainty. We further consolidate public deepfake datasets into a unified benchmark of approximately 4M images and construct a separate cross-generator evaluation set with ov

---

### [291] PhenoBench: Mapping What a Deeply Phenotyped Human Cohort Can Tell Us

**链接**: https://arxiv.org/abs/2609.06080
**作者**: Gal Sapir, Alon Diament, Adva Wolf, Doron Yaya-Stupp, Dikla Gelbard Solodkin, Dana Azouri 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deeply phenotyped cohorts combine clinical, imaging, molecular, and wearable observations across timescales from seconds to years. This breadth can reveal which measurements inform which health-related questions, but heterogeneous analyses are not directly comparable. We present PhenoBench, an executable benchmark built around the Human Phenotype Project, in which more than 13,000 participants have completed the initial visit. Each question fixes the target, eligible population, timing, and allowed information; its evaluation contract specifies the split, metric, baseline, and claim boundary. The benchmark defines 90 clinically grounded tasks across 15 domains and 26 input modalities. Measurements showed question- and representation-dependent predictive value, including positive, near-zero, and negative changes in held-out performance relative to matched baselines. We used PhenoBench to evaluate emerging tabular foundation models across 160 matched regression comparisons spanning 52 ta

---

### [292] Measuring Language Transfer in Robot Policies: Adding Greek to a Cosmos3 Vision-Language-Action Policy

**链接**: https://arxiv.org/abs/2609.07470
**作者**: Ayoub Kirouane, Georgios Giaples, Christos Petrocheilos
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models are trained and evaluated predominantly in English, and robot demonstration corpora do not exist for most languages. We study the addition of Greek to an open vision-language-action stack using only machine-rephrased instructions and no architecture changes. The main challenge is measurement rather than translation. Several plausible instruments produce false conclusions: a color-histogram metric rewards noise, a single-goal benchmark scores 84.6% under correct Greek and 82.6% under deliberately wrong instructions, training loss fails to predict Greek success, and single-run comparisons are dominated by seed variation. On a discriminative ninety-task suite with three seeds per arm, a multilingual text tower without Greek demonstrations remains at its wrong-instruction floor, while Greek-only training exceeds its control by at most 2.7 points. Bilingual training yields a consistent 6.7-7.1 point margin over its control and reaches about two fifths of English perf

---

### [293] Memory in Deep Time-Series Models

**链接**: https://arxiv.org/abs/2609.06006
**作者**: Minh Hoang Nguyen, Huu Hiep Nguyen, Manh Nguyen, Van Dai Do, Dung Nguyen, Hung Le
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning for time series has progressed through successive architectural paradigms, from recurrent networks and transformers to structured state-space models, retrieval-augmented predictors, foundation models, and tool-using agents. These developments are typically studied in isolation, organized by architecture or modeling era. We argue that they can instead be viewed through a common question of \emph{how does a time-series model retain and access information beyond its immediate input?} This question is motivated by a fundamental limitation of conventional time-series modeling: information relevant to a prediction may lie far beyond a feasible input window, while compressing history into a fixed-size state can discard information that may become useful later. We formulate this challenge as a \emph{memory} problem and organize existing time-series methods along a spectrum from internal memory, encoded in parameters and fixed-size states, to external memory that is addressable, r

---

### [294] Back to the Feature: Zero-Shot 6DoF Pose Estimation via Dense Local Features

**链接**: https://arxiv.org/abs/2609.06726
**作者**: Ali Rafiaei, Michael Greenspan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present B2TFPose, a training-free zero-shot method for 6DoF pose estimation of unseen objects from RGB images. Using a single frozen DINOv3 vision transformer as its only pretrained component within the pose estimation pipeline, B2TFPose extracts dense patch-level features that generalize across the synthetic-to-real domain gap without any task-specific fine-tuning, revisiting the classical local feature matching paradigm through the lens of large-scale self-supervised foundation models. Three contributions advance the training-free state of the art. A geodesic non-maximum suppression strategy retrieves a viewpoint-diverse template set for coarse-to-fine correspondence matching. Render-guided Re-Correspondence (RRC) synthesizes object-specific views at the estimated pose and re-establishes dense 2D-3D correspondences to sharpen the initial estimate without additional learned parameters. A multi-mask hypothesis selection strategy jointly scores competing segmentation candidates to re

---

### [295] Representation learning of human cortical folding to reveal long lasting neurodevelopmental signatures

**链接**: https://arxiv.org/abs/2609.05438
**作者**: Julien Laval, Robin Guiavarch, Antoine Dufournet, Racim Menasria, Barth\'el\'emy Drabczuk, Cristobal Mendoza 等 (10 人)
**来源**: q-bio.QM cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The human brain folds in utero, primarily during late gestation. Shortly after birth, cortical folding patterns are established and remain stable thereafter, making them promising early neurodevelopmental markers. Yet it is unclear whether representations given by current neuroimaging foundation models capture cortical folding variability. Here, we introduce Champollion, a self-supervised learning framework that learns interpretable local representations of cortical folding from structural MRI. Optimized on representative folding-related tasks, Champollion accurately captures known folding patterns across cortical regions and external datasets. In a comprehensive benchmark, it consistently outperforms neuroimaging and general-purpose foundation models. Furthermore, Champollion reveals richer genetic associations than conventional morphometric descriptors and identifies localized folding signatures associated with incomplete hippocampal inversion, prematurity, and maternal smoking. Thes

---

### [296] SAM3-O2D2: Zero-Shot Object Out-of-Distribution Detection by Object Class Prompting of the SAM3-Image Model

**链接**: https://arxiv.org/abs/2609.08281
**作者**: Lucas G\"ornhardt, Timo Bartels, Tim Fingscheidt
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Object detectors have shown remarkable performance in various fields, among these medical imaging, surveillance, and autonomous driving. However, they are prone to overconfidence when encountering unseen objects in real-world deployments, causing potential safety issues. To address this, detecting out-of-distribution (OOD) objects is essential for reliable object detection. Modern approaches leverage the broad semantic knowledge of foundation models such as CLIP for post-hoc few- and zero-shot OOD detection. However, these methods typically perform OOD assessment in feature space, which can be sensitive to object detector localization errors and variations in object appearance. Moreover, the current state-of-the-art (SOTA) zero-shot method performs computationally costly diffusion in inference. In this work, for our proposed zero-shot object OOD detection method SAM3-O2D2, we employ the SAM3-image foundation model in an efficient manner. Specifically, we prompt SAM3 only with the objec

---

### [297] PLSR: Progressive and Localized Super-Resolution of 3D Objects via Localized Latent Voxel Diffusion

**链接**: https://arxiv.org/abs/2609.06436
**作者**: Yuxin Liu, Minshan Xie, Jiawen Liang, Runsong Zhu, Chi-Wing Fu, Tien-Tsin Wong
**来源**: cs.CV cs.GR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-resolution 3D asset generation is vital in various 3D applications. Existing state-of-the-art diffusion-based models remain constrained by fixed resolutions, limiting their ability to produce details. In this paper, we tackle the challenge of generating more detailed, higher-resolution 3D objects by introducing a 3D super-resolution (SR) framework built on existing 3D generative foundation models. To this end, we design PLSR, a progressive and localized super-resolution solution to achieve this goal effectively and memory efficiently. Technically, given a coarse geometry from a pretrained 3D generator, we decompose the global SR task into localized sub-tasks via an associative input decomposition scheme, adapt a flow-based 3D generator into a localized super-resolution model through low-cost finetuning, and unify them in an iterative patch-wise denoising pipeline for seamless high-resolution output. Experiments on challenging objects show that our approach is able to generate 3D d

---

### [298] VidaForge: Open Research Infrastructure for Video Pretraining Data Recipes

**链接**: https://arxiv.org/abs/2609.06652
**作者**: Yan Ma and Jiadi Su and Zhulin Hu and Ethan Chern and Linhao Zhang and Tiantian Mi and Pengfei Liu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video foundation models increasingly rely on large-scale pretraining data, yet the end-to-end data pipelines behind them remain largely closed and difficult to inspect or reuse. Researchers seeking to understand how video data recipes affect model pretraining often need to build substantial infrastructure before testing even a focused hypothesis. We present VIDAFORGE, an open research infrastructure that represents a video data recipe as an executable five-stage workflow from raw videos to training datasets. A decision in this workflow can be varied to construct alternative datasets while preserving how every sample was produced. To demon strate this research workflow, we compare data recipes with different coverage and quality in early from-scratch pretraining of Wan 2.1 and V-JEPA 2.1. Across both learning objectives, the broader-coverage recipe achieves the highest downstream benchmark scores, while loss-based evaluation favors different recipes. This study demonstrates how VidaForg

---

### [299] Dreaming in Flow: Generative Grounding Feedback for Self-Evolving Unified Multimodal Models

**链接**: https://arxiv.org/abs/2609.08282
**作者**: Ke Hao, Yuanzhi Liang, Tingxi Chen, Rui Li, Haibin Huang, Chi Zhang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified multimodal models integrate visual understanding and generation within a single network, yet the two capabilities are commonly optimized as separate tasks. We introduce Generative Grounding Feedback(GGF), a self-evolving post-training framework that uses only text prompts and the model's own visual experience. Given a prompt, the model first generates a visual ``dream.'' Flow-level feedback compares text-, image-, and repair-conditioned predictions at the same noisy latent state, transferring image-grounded generation directions to the prompt condition. Dream replay grounding replays this dream through captioning and re-imagination, training claim-level evidence to remain consistent across the replay while separating unrelated visual experiences. Jointly optimized, these two directions let generation provide visual grounding for understanding and understanding refine subsequent generation without paired image--text supervision. Experiments across unified models with different u

---

### [300] GIFT: Goal-Injected Fine-Tuning for Efficient Manipulation Policy Adaptation

**链接**: https://arxiv.org/abs/2609.07006
**作者**: Xiaoyuan Fang, Shuo Feng, Yuxuan Wang, Enhua Cheng, Peng Zhou and Piji Li
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compared with relying solely on initial observations and language instructions, predicting goal images with generative models as high-level visual guidance can significantly enhance the robustness of Vision-Language-Action (VLA) models. However, most existing foundation models have not systematically incorporated goal image conditioning due to the high computational training cost. To this end, we propose Goal-Injected Fine-Tuning (GIFT), a lightweight and efficient fine-tuning framework that seamlessly integrates generated goal images into multiple representative pretrained VLA models. Our approach introduces goal image features into observations via a zero-initialized convolution which progressively grows parameters from zero and prevents harmful noise from disrupting the pretrained policy during fine-tuning. As training proceeds, goal information is gradually incorporated, enabling efficient goal understanding without disrupting model stability. We further introduce a refined image e

---

### [301] IPM-FM: A Foundation Model with Consensus Feature Selection for Industrial Process Monitoring

**链接**: https://arxiv.org/abs/2609.08375
**作者**: Liang Cao, Weide Liu, Yan Qin, Jun Cheng, Weisi Lin, Bhushan Gopaluni
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial process monitoring is fundamental to the safety and economic performance of modern process plants. Current practice remains a one-task-one-model paradigm that is label-inefficient and prone to degradation under operating drift. Foundation models have reshaped language, vision, and generic time-series forecasting, but it has not been adapted to industrial process monitoring. This setting poses domain-specific challenges, including safety-critical decisions and asymmetric sampling between process variables and laboratory measurements. We propose the industrial process monitoring foundation model (IPM-FM). It first learns general-purpose representations from unlabeled industrial process data through self-supervised pretraining, then adapts to specific monitoring tasks using a small amount of task-labeled data, and finally produces calibrated predictions through an uncertainty-aware prediction head. IPM-FM integrates a self-supervised Informer backbone with a multi-criteria cons

---

### [302] Organization of Valence and Arousal in Vision-Language Representations of Built Environments: Insights from the EMOIS Dataset

**链接**: https://arxiv.org/abs/2609.06870
**作者**: Madoka Yonekura, Katsunori Kohda, Nobuhiko Muramoto and Takahiro Yamaguchi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual perception of built environments contributes to the affective impressions that people form in everyday life. However, how these impressions are represented within vision foundation models remains largely unexplored. To support the systematic investigation of this subject, we introduce the Emotional Impression of Spaces (EMOIS) dataset, comprising 1,544 real-world built-environment images. Each image is annotated with image-evoked valence and arousal ratings collected from Japanese adults by conducting a large-scale web-based survey, with approximately 120 ratings per image. Using Contrastive Language--Image Pre-training (CLIP) representations, we perform predictive and geometric analyses to systematically investigate how valence and arousal are encoded and organized within the representation space. These analyses reveal that valence exhibited stronger and more coherent organization than arousal. Cross-dataset analyses with the Open Affective Standardized Image Set (OASIS), a ben

---

### [303] Comparative Study of Anatomical and Learned Features in AI Models for Structural Brain MRI

**链接**: https://arxiv.org/abs/2609.06807
**作者**: Boyang Yu, Miquel Lopez Escoriza, Long Chen, Arjun V. Masurkar, Narges Razavian, Carlos Fernandez-Granda
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we comprehensively evaluate three popular feature-extraction paradigms in AI-based neuroimaging modeling: (1) computation of anatomical surfaces and volumes, (2) supervised learning with convolutional neural networks (CNNs), and (3) unsupervised pretraining of vision transformer (ViT) foundation models, followed by supervised finetuning. Our study is based on 18 publicly available datasets containing 3D structural T1-weighted MRI scans from approximately 80,000 participants across seven distinct clinical tasks. We observe that a linear model based on anatomical features matches the diagnostic performance of complex nonlinear features learned by sophisticated AI frameworks, including foundation models trained on thousands of scans. Conversely, CNNs and pretrained ViTs learn features that implicitly capture relevant anatomical information, bypassing the need for explicit feature extraction. Building upon these insights, we propose Anatomy Segmentation Pretraining (ASP), a n

---

### [304] Assessing Covariate-Informed Grid Load Forecasting with a Time-Series Foundation Model

**链接**: https://arxiv.org/abs/2609.06656
**作者**: Varsha Pendyala, Yiwei Fu, Weizhong Yan and Nurali Virani
**来源**: cs.LG cs.AI cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern power systems are growing increasingly complex as they integrate diverse generation sources to meet rising demand, making accurate load forecasting challenging. Recent advances in time-series foundation models (TSFMs) resulted in promising performance in zero-shot univariate load forecasting tasks. However, real-world load forecasting often involves multiple target variables and requires the integration of exogenous variables, raising important questions about the utility of TSFMs in realistic settings. In this study, we position Chronos-2, a recently developed model by Amazon, as a representative multi-channel TSFM that supports univariate, multivariate, and covariate-informed forecasting, and conduct a systematic investigation of how such models can be used for real-world load forecasting. While prior work has evaluated Chronos-2 on a limited number of energy-related tasks in a zero-shot setting, its performance relative to established task-specific deep learning models and it

---
