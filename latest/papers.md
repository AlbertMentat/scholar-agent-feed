# 📑 论文索引 - 2026-10-13

共 121 篇论文

---

### [1] A multimodal large language model for evidence-based autism spectrum disorder screening

**链接**: https://arxiv.org/abs/2609.16464
**作者**: Jun Chen, Qi Zhao, Yunliang Jiang, Shuqin Cao, Yunqiang Lin, Chenglong Jia 等 (10 人)
**来源**: cs.CV cs.HC cs.LG
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] PreSTO: Predictive Subtree Prefetching for Fast LLM Power Sampling

**链接**: https://arxiv.org/abs/2610.13171
**作者**: Nan Jiang, Panagiotis Theodoropoulos, Wei Deng
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Power sampling improves large language model (LLM) reasoning at test time by sampling from a sharpened version of the base model's distribution. Its sampler, PowerMH, is slow because its Metropolis--Hastings (MH) updates are sequential: each accept/reject decision sets the state from which the next proposal is generated. Prior work reduces this cost by changing the sampler or the model (e.g., sequential Monte Carlo, approximate lookahead, distillation). We propose Predictive SubTree Prefetching (PreSTO), which accelerates PowerMH by prefetching future proposals and provably leaves its MH transition kernel unchanged. PreSTO views future MH outcomes as a tree of accept/reject decisions: in each model call, it generates the proposals of a \textit{prefetched subtree} of this tree in one batch, then follows the realized path with the original MH acceptance rule. We also observe that MH reaches only a sparse, nearly unary part of each prefetched subtree, we further design a \textit{predictiv

---

### [3] Semantic Views: Certified Reuse of LLM Labels Across Semantic Queries

**链接**: https://arxiv.org/abs/2610.12768
**作者**: Oktie Hassanzadeh, Dharmashankar Subramanian
**来源**: cs.DB cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic query engines evaluate natural-language filters with a large language model, and every evaluation is a costly oracle call. Optimizers that reduce these calls face a dilemma: cascades that trust a cheap proxy miss their precision and recall targets on many queries, methods with finite-sample guarantees save little, and all of them discard the oracle's labels when the query ends. We present SemViews, a certified semantic filter that orders tuples by signals that cost no oracle calls (the labels that earlier queries left behind as semantic views, a local embedding, and a helper model's score), refines that order with labels it must pay for anyway, and certifies its answer with fresh stratified oracle samples. The answer meets user precision and recall targets with probability at least $1-\delta$ for every workload and every catalog, so a stale or misleading view can cost oracle calls but never accuracy. On four workloads replayed against 725,000 recorded oracle labels, SemViews m

---

### [4] Host-Aware Web Crawling for LLM Pretraining Data

**链接**: https://arxiv.org/abs/2610.13321
**作者**: Malte Ostendorff
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web crawling is a major source of large language model (LLM) pretraining data, yet data-selection pipelines discard a large share of crawled pages. We investigate how a crawler should allocate its budget across and within hosts to collect more high-quality pretraining data. Combining document-level quality classifier scores, web-graph centrality metrics, and Common Crawl's per-host crawl coverage, we find that roughly half of the variation in classifier scores occurs between hosts. In the crawls we analyze, a few pages from a host also provide a useful estimate of the quality of its remaining pages. Common Crawl uses harmonic centrality, a graph centrality metric, to guide its crawl allocation. In our simulations, using centrality to choose which hosts to crawl yields limited gains over random ordering and performs worse for some classifiers. For deciding how deeply to crawl each host, sampling a few pages and then fetching more from hosts with higher-scoring samples collects several t

---

### [5] SharP: Soft and Hard Prompt-Guided Augmentation with LLM for Low Resource Fake News Detection

**链接**: https://arxiv.org/abs/2610.13207
**作者**: Ziyu Luo, Wei Li, Haoping Huang, Kecheng Liu, Min Gao
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fake news detection under low resource conditions is challenged by the scarcity of labeled data and the difficulty of capturing subtle deceptive patterns. In this work, we focus on low resource fake news detection, where only a small labeled set is available for training, while evaluation is performed under a fixed and unchanged test protocol. This setting is motivated by costly, ambiguous fact-checking and emerging topics and domains that are poorly covered by existing benchmarks. Existing data augmentation methods, such as synonym substitution, generative adversarial networks, and large language model (LLM)-based generation, often produce fluent but overly generic content, lacking the task-specific relevance needed for accurate detection. To address this, we propose SharP, a boundary-aware text generation framework guided by soft and hard prompts, which leverages LLMs as tools adapted to produce task-specific synthetic samples. SharP employs a dual prompt mechanism: hard prompts prov

---

### [6] Forgetting is Not Always Bad: A Neuro-Inspired Memory Repair Mechanism for Poisoned LLM Agents

**链接**: https://arxiv.org/abs/2610.13267
**作者**: Lei Liu, Yunji Liang, Xiaowen Zhang, Jingqi Liu, Qi Li, Bin Guo 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are highly vulnerable to memory-poisoning attacks. Existing defenses primarily rely on external modules for either static memory isolation or continuous online auditing, resulting in low memory efficiency and high computational overhead. To address these limitations, inspired by neuroscientific mechanisms that weak reactivation can destabilize memories and induce decay in the absence of reinforcement, we propose an agent-intrinsic training-free memory repair framework, DREAM (Dynamic Reactivation for Engram Attenuation in Memory), that enables selective functional forgetting of poisoned memories. Specifically, DREAM implements a three-stage pipeline: perturbation-induced implicit reactivation to reveal the structural fragility of malicious memories, adaptive anomaly diagnosis based on multi-dimensional activation patterns to detect topological anomalies, and a dynamic memory repair module that selectively suppresses harmful memories while reinforcing b

---

### [7] CB-Orchestrator: Adaptive Workflow Optimization for LLM Agents via Contextual Bandits

**链接**: https://arxiv.org/abs/2610.13064
**作者**: Jiahang Sun, Zhiwei Shang, Zhipiao Liu, Hongwei Yang, Guoqing Xie, Shuang Qiu 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have demonstrated remarkable capabilities in tackling complex tasks through agentic workflows. However, manually designing these workflows is labor-intensive and lacks flexibility to adapt to diverse queries. While automated workflow optimization is a promising direction, existing methods often incur expensive API costs during training-phase feedback collection. Furthermore, they fail to adaptively reuse high-quality workflows, which creates a bottleneck for both performance and cost-effectiveness. To address these limitations, we propose CB-Orchestrator, an adaptive framework that decouples workflow generation from selection. In the first stage, we construct a diverse pool of candidate workflows via evolutionary search. In the second stage, we formulate workflow selection as a Contextual Bandit problem, which enables sample-efficient learning by balancing exploration and exploitation, thereby significantly reducing the feedback required for training. 

---

### [8] SmartSalesBench: A Resistance-Aware Multi-Turn Benchmark for Evaluating LLM Sales Agents

**链接**: https://arxiv.org/abs/2610.12975
**作者**: P N Bhargav Teja, Velpula Lokesh Reddy, Madhu Basumata, Susen Sarkar, Rajasekhara Reddy Duvvuru Muni
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present SmartSalesBench, the first multi-turn conversational benchmark explicitly designed to evaluate large language model (LLM) sales agents against psychologically grounded, resistant buyer personas. Existing task-oriented dialogue benchmarks assume cooperative users and measure task completion; SmartSalesBench inverts this assumption, placing agents against personas programmed to resist and challenge across conversations of up to twenty turns. The benchmark includes five agent profiles, twelve buyer personas, fifteen smartphone products across six price tiers, and four controlled experiments with 3 iterations totaling 13,680 sessions. Both sales-agent and buyer persona generations are grounded through retrieval-augmented generation (RAG). We introduce nine evaluation metrics grouped into three tiers: primary outcome metrics (CR, BRS, RIR), secondary quality metrics (SMS, PFS, ETI), and exploratory metrics planned for future reporting (ITS, ARI, SPI). Our evaluation combines auto

---

### [9] A Multi-Agent LLM System for Automated Tuning of Specialized Neural Network Models

**链接**: https://arxiv.org/abs/2610.13663
**作者**: Ivan Moloshnikov, Dmitry Kunitsyn, Alexander Sboev, Maksim Skorokhodov, Roman Rybka, Yuanchao Liu
**来源**: cs.AI cs.CL cs.LG cs.MA cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many machine learning approaches are two-level: an expert selects a class of methods, within this class the choice of key components is critical and usually manual. This paper addresses the automatic tuning of these components and proposes a framework transferable across models of different nature. The multi-agent large language model (LLM) framework has three roles---analyst, coder, and recorder~---with an experiment log and a sandboxed execution environment. Unlike systems that optimize the entire ML script or search architectures in a discrete space, the framework operates over an open but semantically narrow space: the agent generates code only for the specified components, leaving the overall network structure unchanged. The approach is validated in two directions: tuning a classification spiking neural network with correlation learning, and solving high-order differential equations with Physics-Informed Neural Networks (PINN). Across five tasks---spiking classification on MNIST a

---

### [10] How Do Hardware Faults Manifest Differently in LLM Agents?

**链接**: https://arxiv.org/abs/2610.12756
**作者**: Aiden Rubey, Zachary Coalson, Cong Chen, Jean-Philippe Monteuuis, Jonathan Petit, Sanghyun Hong
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present the first systematic study of the resilience of large language model (LLM) agents to random hardware-induced faults. Prior work on hardware fault resilience in LLMs focuses on model-level outcomes, such as incorrect outputs or generation failures. Yet LLM agents repeatedly interact with tools and environments, creating loops that can change how hardware faults manifest. We conduct an extensive evaluation across three agent benchmarks, comprising 6,814 agent executions: 2,400+ clean runs and 4,300+ fault-injected runs with independently sampled random two-bit weight faults. We trace how these faults propagate through agent execution. Unlike prior studies, we find that agentic execution transforms model-level corruption into distinct system-level outcomes: (1) agents can recover from faulty model outputs and still complete tasks correctly; (2) this recovery increases computational and execution costs; (3) a few faults cause subtle but semantically meaningful errors while the a

---

### [11] U4RASD at KnowledgeGraphEval-2026: Ontology-Constrained Encoder and LLM Systems for Arabic Relation Extraction

**链接**: https://arxiv.org/abs/2610.12742
**作者**: Ahmad Abbas, Hussein Mazeh, Chadi Abou Chakra, Aya Jouni, Mohammad Ballout, Fadi A. Zaraket
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper details our submission to KnowledgeGraphEval 2026 Subtask 2 on directed Arabic relation extraction. We explored encoder-based and large language model approaches for predicting one of 40 relations or no_relation from an Arabic sentence and a subject-object pair. Our encoder systems use typed entity markers and separate relation-existence and relation-classification heads, while our LLM systems fine-tune Yehia and Qwen3.5 with QLoRA and ontology-constrained prediction. Our best system, an ensemble of Yehia-RE, Qwen-RE, and TypedPair, achieved a micro-F1 score of 94.06 and ranked 1st in Subtask 2. Yehia-RE (full-vocabulary) achieved 92.98, while the best encoder and Qwen-RE achieved 92.69 and 91.94 respectively. Our results highlight the importance of constrained prediction and complementary modeling approaches for Arabic relation extraction.

---

### [12] Evaluating LLM Creativity through Long-Tail Performance

**链接**: https://arxiv.org/abs/2610.12998
**作者**: Yichen Wang, Tenghao Huang, Vishakh Padmakumar, Mina Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Creativity benchmarks for large language models (LLMs) vary widely in task and metric design. This raises the question of whether they capture a common notion of creativity. We propose that this shared target can be formalized as task-specific performance in the long tail of a reference input-output distribution, which describes how common input-output pairs are relative to a chosen source of text. We ground this proposition in the novelty-quality product formulation and evaluate it empirically across 15 benchmarks and 26 open-weight models, using n-gram absence from the pretraining data as a novelty proxy. Our results show that creativity benchmarks lie further in the tail regions than standard benchmarks. Moreover, on both creativity and standard benchmarks, model rankings from higher-tail subsets of each benchmark align more closely with human creativity judgments in LM-Arena. Building on these findings, we introduce q@Tail($\alpha$), a lower-cost creativity diagnostic that measures

---

### [13] From Structure to Validity: Mechanism-Guided Generation and Refinement of LLM Rubrics

**链接**: https://arxiv.org/abs/2610.13375
**作者**: Feifei Qian, Xuan Chen, Lixin Cui, Chaoyang Mei, Fanlin Meng, Shuyao Xiao 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubrics have been widely used to evaluate and optimize language models on open-ended tasks. However, existing work primarily focuses on generating better rubrics, with limited understanding of what makes rubric design effective. In this work, we conduct a systematic mechanistic analysis of rubric design across criterion organization, criterion operationalization, and score aggregation. Our analysis shows that structural organization enables more comprehensive criterion construction, semantic specification alone does not ensure effective criterion-level judgments, and sophisticated score aggregation provides limited additional gains. Guided by these findings, we introduce Adaptive Rubric Tree Search with Hybrid refinement (ARTS-Hybrid), which combines adaptive tree construction with semantic-first, response-calibrated refinement. Experiments across benchmarks show that ARTS-Hybrid improves both end-to-end evaluation performance and intrinsic rubric quality. Further experiments suggest t

---

### [14] From Mastery Profile to Simulated Response: Stochastic Student Knowledge Graphs (SSKG) for Faithful LLM Student Simulation

**链接**: https://arxiv.org/abs/2608.21668
**作者**: Yuan An, Emily Wang, Benjamin Wang, Ruhma Hashmi
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] OWLET: On-Policy Weighted Learning via Evidence Transfer for Video Large Language Model Post-Training

**链接**: https://arxiv.org/abs/2610.13272
**作者**: Qitan Lv, Ke Fan, Hong Wang, Wen Wu, Yilin Wang, Bowen Zhou 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training has become a key stage for eliciting reasoning capabilities in Video Large Language Models (Video-LLMs). Existing post-training methods mainly follow two paradigms: reinforcement learning (RL) and on-policy distillation (OPD). However, they do not fully exploit visual evidence for effective training. RL supervises the policy with a single trajectory-level reward, which is too coarse-grained for video reasoning: the same response-level advantage is applied to every generated token, disregarding that the tokens of a video response are grounded in the visual stream to very different degrees. OPD provides token-level supervision through output-distribution matching, but lacks direct supervision of the spatiotemporal representations that produce those outputs. We observe across extensive experiments that the same model reasons more accurately when its video view combines global temporal context with question-relevant details. Comparing the same student-generated response under

---

### [16] SwingGuard: Risk-Conditioned Multi-Agent Swing Trading with Dual-Timescale Governance

**链接**: https://arxiv.org/abs/2610.12988
**作者**: Junzhou Su, Yichen Luo, Yebo Feng, Teng Li, Jiahua Xu
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cryptocurrency swing trading spans mismatched timescales: positions remain active while market and event risk can change within minutes. However, many predictive and large language model (LLM)-based trading systems assess risk after strategy generation or run both functions at the same cadence, leaving proposals unconditioned by current risk and exposure weakly governed between revisions. We propose SwingGuard, a dual-timescale, long-only multi-agent framework for risk-conditioned strategy generation. At the strategy timescale, specialized analysts synthesize point-in-time technical, sentiment, on-chain, and macroeconomic evidence through bullish-bearish deliberation. The resulting evidence and current risk context are then combined by a Portfolio Architect to form a target position. At the governance timescale, a five-minute Risk Controller performs conditional diagnosis, maintains persistent risk states with staged recovery, audits the proposal, and constrains execution until the nex

---

### [17] VEPA: Verified Evolving Formal Policy for Lifelong LLM Agent Guardrails

**链接**: https://arxiv.org/abs/2610.12813
**作者**: Duy Nguyen, Lesly Miculicich, Bhavana Dalvi Mishra, Shuo Li, Krishnamurthy Dj Dvijotham, Mohit Bansal 等 (8 人)
**来源**: cs.AI cs.CL cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly operate over sensitive resources, such as private documents and mutable system states, which can create serious safety and security risks. Runtime guardrails should therefore make inspectable, reproducible, and deterministic allow or refuse decisions before potentially irreversible agent actions are executed. However, safety and security requirements are rarely complete before deployment, so guardrails need to keep adapting as new risks emerge. Existing adaptive guardrails learn from deployment experience, but they usually apply safety policies through LLM inference, which can lead to inconsistent decisions and ambiguous policy interpretations. Formal guardrails, on the other hand, enforce policies deterministically, but they usually rely on pre-deployment or task-specific policies and have no mechanism to adapt to newly observed risks. We introduce VEPA, a framework for the verified evolution of formal agent guardrails. VEPA represents the guardrail as a formal

---

### [18] Surfing the Activation Wave: Analyzing the Information and Geometry of LLM Hidden States for Speculative Decoding

**链接**: https://arxiv.org/abs/2610.12939
**作者**: Raghavv Goel, Sudhanshu Agrawal, Mukul Gagrani, Risheek Garrepalli, Mingu Lee
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decoder hidden states from different layers of large language models (LLMs) often encode complementary information. However, existing speculative decoding methods typically rely on a small set of target-model layers chosen using fixed, position-based heuristics. Selecting an optimal subset of layers is inherently a combinatorial problem, making exhaustive evaluation infeasible even for moderately deep models. In this work, we present a principled framework for multi-layer hidden-state selection for speculative decoding based on two complementary criteria: informativeness, measured through matrix-entropy analysis, and diversity, quantified using centered kernel alignment (CKA). We investigate layer-wise Shannon entropy, aggregate entropy under hidden-state concatenation, and pairwise CKA dynamics across depth, revealing distinct geometric and informational compartments within decoder representations. Motivated by these findings, we propose entropy and CKA-based layer selection algorithm

---

### [19] EvoDrive: Pareto Evolution for Safety-Critical Autonomous Driving via Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2606.03678
**作者**: Tong Nie, Yuewen Mei, Yihong Tang, Junlin He, Jie Deng, Jian Sun 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] EvoBelief: Falsifiable World Models for Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2610.12789
**作者**: Janet Wang, Jiang Guo, Yi Xiang, Jiaqing Yuan, Mingwen Dong, Hideo Kobayashi 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving LLM agents typically improve how they act through accumulated experience, reflection, or skills. Yet even procedurally capable agents can fail when their beliefs about environment dynamics are incomplete, incorrect, or outdated. We study a complementary axis of self-evolution: evolving those beliefs during deployment. Such beliefs can support multiple tasks, but incorrect ones can also propagate across them. We introduce EvoBelief, a self-evolving world model that represents environment knowledge as falsifiable hypotheses. Unexpected outcomes and decision-relevant unknowns trigger hypothesis formation. Later observations and controlled experiments provide independent validation before a rule can guide predictions or plans within its supported scope. Counterexamples narrow or retire rules as the environment changes. The language model remains frozen, and each rule remains linked to its evidence and the decisions it changes. Across four benchmarks spanning static dynamics, 

---

### [21] Constitutional Gating and Deterministic Recovery for Multi-Agent LLM Negotiation: Ablations Against a Stateful Adversarial Gatekeeper

**链接**: https://arxiv.org/abs/2610.11542
**作者**: Masaaki Nakatsu (AO, Inc. / OrbLabs AG), Reno Wang (AO, Inc.)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] TernaryLLM: Ternarized Large Language Model

**链接**: https://arxiv.org/abs/2406.07177
**作者**: Tianqi Chen, Zhe Li, Weixiang Xu, Zeyu Zhu, Dong Li, Lu Tian 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Same Query, Different Answer: Run-to-Run Variance in Semantic Query Processing

**链接**: https://arxiv.org/abs/2610.13823
**作者**: Oktie Hassanzadeh, Dharmashankar Subramanian
**来源**: cs.DB cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic query engines ask a large language model (LLM) to judge individual rows, and benchmarks compare these engines on the quality of a few executions at temperature 0. We measure how much another execution changes. We re-execute the text and tabular workloads of SemBench, LRO-Bench, and UDA-Bench through their own harnesses, log every one of 1.2 million model calls, and reanalyze SemBench's published executions. At temperature 0, between 0.07% and 10.2% of rows change their operator output over five executions, depending on the model, and up to 24.0% on one task. Plans amplify these changes exponentially in the number of rows an answer exposes, as a possible-worlds model predicts: on UDA-Bench, a few percent of extracted values change, but about two thirds of the answers do. In SemBench's published results, 21% of text results change quality between executions, including on engines whose plans are deterministic. Several per-query system comparisons, and 16 of 28 tests of LRO-Bench'

---

### [24] DRYLAB-Bench: Benchmarking the Biosecurity Risk of Agentic LLM Mutation Design

**链接**: https://arxiv.org/abs/2610.13116
**作者**: Yuzhen Wang, Chunxiao Li, Baichen Le, Lewen Yan, Jie Zhang, Yucheng T. Yang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) acquire advanced biological design capabilities, they offer substantial research benefits but simultaneously introduce severe dual-use risks, such as engineering enhanced pathogens or drug-resistant bacteria. While biosecurity frameworks recognize these threats, the actual risk of LLMs executing dangerous biological modifications remains unquantified, particularly when augmented with specialized biological design tools (BDTs). Existing evaluations primarily assess hazardous knowledge possession rather than practical application, overlook risk amplification from BDTs, and rely on unreliable, expensive, or hazardous validation methods. To address these gaps, we introduce DRYLAB-Bench (Design Risk Yielded by LLM Agent in Biodesign), the first comprehensive benchmark evaluating the high-risk biological mutation design capabilities of LLM agents. Moving beyond basic question-answering, DRYLAB-Bench tasks agents with 30 genuinely hazardous mutation-design scen

---

### [25] Web$hell: A Unified Interface for Agentic Web Access

**链接**: https://arxiv.org/abs/2610.13416
**作者**: Sunghwan Kim, Deogyong Kim, Sangam Lee, Donguk Kwon, Dongha Lee
**来源**: cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are becoming direct users of the open web. As they take on increasingly complex and information-intensive tasks, effective web access is becoming a core capability for agentic problem solving. Existing approaches have advanced agentic web access through different access models, including search-augmented agents, browser-based agents, and, more recently, filesystem-based agents. Nevertheless, as users expect agents to complete long-horizon, end-to-end tasks, they increasingly need to conduct broad information gathering, perform browser actions, and revisit acquired evidence within a single trajectory. Yet our preliminary analyses reveal that existing access models struggle to meet these demands. They primarily support either information gathering or browser interaction, while combining their capabilities can involve substantial costs or performance trade-offs. To this end, we present Web\$hell, an interface that unifies web access under a single access 

---

### [26] Measuring Harness-Induced Belief Divergence in Multi-Step LLM Agents

**链接**: https://arxiv.org/abs/2607.04528
**作者**: Haiwen Yi and Xinyuan Song
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] GenCoord: Executable Commitments for Embodied LLM Agents under Private Information

**链接**: https://arxiv.org/abs/2608.22055
**作者**: Junning Zhu, Peng He, Haohan Yuan, Jianpeng Liang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] ABLEIST: Intersectional Disability Bias in LLM-Generated Hiring Scenarios

**链接**: https://arxiv.org/abs/2510.10998
**作者**: Mahika Phutane, Hayoung Jung, Matthew Kim, Tanushree Mitra, Aditya Vashistha
**来源**: cs.CL cs.AI cs.CY cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] COFFEQA: Counterfactual-Guided Few-Shot Distillation for LLM Question Answering

**链接**: https://arxiv.org/abs/2610.12837
**作者**: Kavinda Kehelella, Sanghamitra Dutta
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge distillation aims to train a smaller student model to mimic a larger teacher model for resource-constrained environments. However, the process of distillation is typically data-intensive and computationally expensive, particularly for generative tasks. Few-shot distillation offers an alternative by transferring teacher knowledge using limited training samples. However, we observe that few-shot distillation performance is heavily dependent on the choice of these training samples. In fact, we demonstrate that using more uncertain samples near the teacher's decision boundary can significantly deteriorate distillation performance. Motivated by this observation, we propose Counterfactual-guided Few-shot Distillation in Open-book Question Answering (COFFEQA), a novel strategy that aptly uses counterfactuals to provide additional supervision around challenging factual samples. In the generative QA setting, we define a counterfactual as a minimally modified context that induces the t

---

### [30] First-Order In-Context Shapley: Scalable Data Auditing for LLM Alignment and Evaluation

**链接**: https://arxiv.org/abs/2607.22766
**作者**: Yunting Song, Matthew Watson, Moustafa Farid Alzantot, Peter Grabowski, Jun Qin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Epistemic Policy Divergence in Multi-Turn LLM Contamination: A Protocol-Gradient Investigation

**链接**: https://arxiv.org/abs/2609.35308
**作者**: Fahrell Giovanny, Geby Bayuningtyas, Sahrul Mukharom, and Hafiz Budi Firmansyah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Humanize Olympiad Agents: A Multi-Session Workflow for Olympiad Problem Solving with Solve, Review, Wiki, Verify

**链接**: https://arxiv.org/abs/2610.13632
**作者**: Zhengyang Zhang, Jing Xiong, Hongzhou Lin, Juihui Chung, Zijian Zhang, Song Han 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are rapidly improving on long-horizon scientific and olympiad tasks. Recent systems have produced a Lean-formalized resolution of the Navier--Stokes problem and autonomous solutions to four open questions in the Erd\H{o}s Conjectures database. Yet neither system releases both its underlying model and complete inference stack. More broadly, a single agent session remains brittle on difficult problems: early errors can propagate, missing domain knowledge can stall progress, and apparent success can mask a misinterpretation or weakening of the original task. We introduce HOA (Humanize Olympiads Agent), an open, flow-level framework that coordinates multiple agent sessions through three complementary feedback channels. First, an independent reviewer evaluates each candidate and provides actionable feedback. Second, a structured wiki supplies task-specific knowledge that may be missing or unreliable in model pretraining. Third, a verifier checks generated L

---

### [33] Knowing Is Not Telling: Identity Ossification in LLM Representations of Trans-border Communities

**链接**: https://arxiv.org/abs/2610.12610
**作者**: Minglu Sun, Lan Chen, Hang Jiang
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ethnic and cultural identities rarely align with political borders, a tension made sharper by migration and long-standing cross-border ties. Communities such as the Sami, the Rohingya, and the Kurds have long lived across more than one state. This tension is especially clear in mainland Southeast Asia, where many communities share history, language, and culture across state lines. We study nine such transborder ethnic communities along China's southwestern border with mainland Southeast Asia, looking at how large language models (LLMs) represent them. We define and study identity ossification: a pattern where LLMs turn a fluid, cross-border ethnic identity into a single, fixed nation-state identity. We introduce the Transborder Identity Ossification Diagnostic Framework (TIODF) that compares direct factual questions with open-ended narrative questions to test whether ossification comes from missing knowledge or from how models frame their answers. We test GPT-5.1 and DeepSeek-V3.2 in E

---

### [34] Matched-Context Group Policy Optimization for LLM Agent Training

**链接**: https://arxiv.org/abs/2610.13755
**作者**: Chenxu Zhang, Yaorui Shi, Wenlong Zhang, Jianchao Tan, Zihan Wang, Yiming Cheng
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training long-horizon language model agents requires assigning credit to intermediate decisions from sparse terminal feedback. Within a finite group of sibling rollouts, useful action comparisons depend on their context, evidence for both alternatives, and how that evidence enters learning. We propose Matched-Context Group Policy Optimization (MCGPO), a procedure for constructing weighted action preferences from already collected trajectories. MCGPO defines comparison contexts with pre-action state summaries and observed rubric progress, annotated by task rules. Two-action support selects among ordered exact and coarse matching rules. Fixed folds separate candidate decisions from the terminal outcomes used to orient their preferences, and support-dependent evidence weights scale an auxiliary pairwise objective alongside shared GraphGPO task learning. MCGPO reuses rollout data and each response's original history, preserving critic-free training. Across six environment-backbone settings

---

### [35] Byzantine-Resilient Federated Large Language Model via Hypergraph Message Passing

**链接**: https://arxiv.org/abs/2610.12711
**作者**: Kai Li, Hanlin Cai, Zihao Liu, Yichen Li, Jose Alcaraz Calero, Wei Ni 等 (8 人)
**来源**: cs.LG cs.CR
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated Large Language Models (FedLLMs) are promising to deliver privacy-preserving, collaborative intelligence. The decentralized training process is vulnerable to Byzantine attacks that corrupt semantic consistency and factual resilience through malicious model updates. This paper presents a new resilience strategy that prevents semantically corrupted knowledge from propagating during federated aggregation. A defense problem is formulated to jointly maximize global accuracy and suppress manipulated model updates, enabling trustworthy knowledge aggregation without accessing private local data. To strengthen the resilience of FedLLMs, we develop a novel Hypergraph Message Passing Graph Autoencoder (HMP-GAE) framework, where low-rank model updates are represented as nodes in a hypergraph and high-order semantic relationships among multiple agents are exploited through iterative message passing. By leveraging historical checkpoints and cross-agent relational reasoning, HMP-GAE identifi

---

### [36] Structural and Representational Agency in LLM-Driven Timbre Generation and Interpolation

**链接**: https://arxiv.org/abs/2610.12532
**作者**: Joseph Cameron, Alan Blackwell
**来源**: cs.SD cs.HC cs.LG cs.MM eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative creative interfaces routinely report the user's position within a space of possibilities. Such displays imply that the quantities shown were measured from the artefact; in a growing class of systems they are instead predicted by a language model describing its own output, and the two are indistinguishable on screen. Most creative domains lack an agreed measurement against which such a self-report can be checked; audio admits one. In a measurement study of a working LLM-driven timbre interface, what a user can cause proves separable from what the interface reports. The first is exactly characterisable: the reachable set is a zonotope whose dimension increases by one per sound placed, so the space the model may act within is demonstrably the user's own. The second is inaccurate. The displayed position differs from measurement by approximately three times the width of that region, and the error has two independent sources: model-predicted coordinates, whose accuracy varies twof

---

### [37] RoleWorld: Knowledge Transfer in World Modeling with Functional Role Abstractions

**链接**: https://arxiv.org/abs/2610.13172
**作者**: Boyuan Xiao, Pu Wang, Ji Feng, Yao-Xiang Ding
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> World models enable large language model (LLM) agents to anticipate action effects and make informed decisions. For generalization, it is desirable for such world models to transfer efficiently to new environments with similar interaction structure and underlying dynamics. Recent approaches encode world dynamics as symbolic rules or executable programs, whose compositional structure in principle affords transfer, but still organize such knowledge around environment-specific objects. To address this limitation, we introduce RoleWorld, a symbolic world modeling approach which uses reusable prototypes and environment-specific parameter values as functional role abstractions to represent how objects behave in interactions. From interaction trajectories, a teacher LLM extracts role prototypes and executable transition rules defined over role instances, together with a skill that guides the actor LLM to use role information in decision making. In a target world, without the teacher, the acto

---

### [38] The Saturation Trap and the Subjectivity of Intervention Timing: Why Affect-Based Triggers and LLM Judges Fail to Time Interventions on Autonomous Agents

**链接**: https://arxiv.org/abs/2606.04296
**作者**: Manvendra Modgil
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Algebraic Integer Quantization for Machine Learning Applications

**链接**: https://arxiv.org/abs/2610.12494
**作者**: Anthony Kostal-Vazquez, Vassil Dimitrov, Branden Butler
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this article, we propose algebraic integer number formats (AINF) as a framework for highly configurable and accurate compressed computation. A key property of AINF is its straightforward reduction to purely integer arithmetic, enabling error-free multiply-accumulate operations. We develop a matrix multiplication engine that exploits this property, obtaining performance within a predictable factor of the most efficient numerical counterparts on modern hardware accelerators. Another key advantage of AIQ is the freedom to select algebraic integers tailored to the numerical characteristics of a given use case, offering optimization opportunities that are fundamentally unavailable in floating-point or fixed-point formats. Motivated by these properties, we introduce algebraic integer quantization (AIQ), a lossy compression format for large language model (LLM) inference, and provide results demonstrating that AIQ achieves competitive accuracy compared to the industry-standard MX format ac

---

### [40] Taking Tokenization off the Host for Agentic LLM Serving

**链接**: https://arxiv.org/abs/2610.13325
**作者**: Mohammad Siavashi, Pascal Schwinte, Ali Banaei, Gerald Q. Maguire Jr., Marco Chiesa, Dejan Kosti\'c
**来源**: cs.DC cs.CL cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic workloads resend long contexts that barely change between calls. Prefix caching now skips most of their prefill, yet every request must still be tokenized in full before the cache can even be consulted. Tokenization, a CPU stage long treated as negligible, becomes the largest part of time-to-first-token (TTFT), and a frontend that tokenizes for a whole GPU fleet limits how many GPUs it can feed. We present GraphTok, a GPU tokenizer that runs the entire encoding pipeline, from pre-tokenization through byte-pair encoding (BPE) merging to token-ID assembly, as one replayable CUDA graph. GraphTok reproduces the reference token IDs bit-for-bit on GPT-2, Llama 3, Qwen 2.5, DeepSeek-V3, and Gemma 3, hands short inputs to a CPU engine where the GPU cannot win, and plugs into unmodified vLLM and NVIDIA Dynamo. GraphTok encodes one million GPT-2 tokens in 1.7-3.2 ms including data transfers, and on Llama 3 it is 4.7-6.0x faster than gigatoken, the strongest CPU tokenizer. On TokTier's ow

---

### [41] AgentTune: A Unified Training Lifecycle for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.13335
**作者**: R E Zera Marveen Lyngkhoi, Abhivansh Gupta, Vidushee Vats, Ram Mohan Rao Kadiyala, Vinay Kumar Sankarapu, Pratinav Seth
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using agents increasingly require a common substrate for building, training, evaluating, distilling, and maintaining agentic systems, yet existing tooling typically addresses these stages in isolation. We present AgentTune, a source-available Python library that provides a unified framework for developing and optimizing tool-using agents. At its core, AgentTune introduces a two-tier EventLog representation that preserves agent trajectories while supporting consistent projections for training, evaluation, and auditing. Building on this substrate, the library provides a shared agent runtime, tool-calling reinforcement learning, agentic distillation, retrieval-augmented generation, decision workflows, evaluation utilities, and a designed path toward self-healing agents. These components are exposed through composable interfaces so that agent strategies, training methods, evaluation procedures, and recovery mechanisms can be combined without requiring separate representations or pipel

---

### [42] Generalized Proximal Policy Optimization: Unifying LLM RL Algorithms from the Perspective of Divergence

**链接**: https://arxiv.org/abs/2610.13015
**作者**: Zhicheng Cai, Xinyuan Guo, Hanlin Wu, Weinan Dai, Yuyan Zhou, Wei-Ying Ma 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning has become the foundational paradigm for enhancing the reasoning capabilities of LLMs. Yet the dominant approach, Proximal Policy Optimization (PPO), relies on a geometrically degenerate clipping proxy that cannot adapt its resistance to policy shifts, leading to premature clipping and degraded exploration. Subsequent variants alleviate these issues through fragmented and heuristic modifications. We propose Generalized Proximal Policy Optimization (GPPO), a principled and unified framework for understanding and designing LLM RL algorithms through the lens of divergence. We establish a generalized $f$-divergence trust-region theory with a monotonic performance improvement guarantee, and show that different $f$-divergences induce distinct geometries and policy update dynamics. We further introduce novel estimator topologies that provide more faithful divergence estimates than the conventional single-sample Monte Carlo estimation. Under this framework, PPO and recen

---

### [43] perturber: A Stateless Service for Semantics-Preserving Text Perturbations

**链接**: https://arxiv.org/abs/2610.12667
**作者**: Khoi-Nguyen Tran
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) evaluations on clean benchmarks overstate model robustness: real inputs arrive perturbed, and these meaning-preserving variants routinely move model answers. Studying this systematically requires applying perturbations one at a time, reproducibly, and identically wherever they run, yet existing tools couple them to a benchmarking stack rather than packaging them as a reusable transform layer. We present perturber, a stateless service and Python library that applies exactly one semantics-preserving perturbation per call, drawn from a first-party catalog of 68 perturbations across 11 families. It turns on a single primitive, with composition left to the caller chaining calls, so the service and the library produce identical output by construction. We evaluate the tool itself, its correctness, reproducibility, and cost, rather than any model's robustness, measuring meaning-preservation per perturbation rather than assuming it. The demonstration adds a live playg

---

### [44] Mitigating Capability Degradation in LLM Self-Improvement via Representation Geometry Regularization

**链接**: https://arxiv.org/abs/2610.12855
**作者**: Jiaqi Tian, Ting Long
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-Policy Self-distillation is a self-improvement paradigm that enables large language models (LLMs) to improve their capabilities by leveraging the same model as both teacher and student under different conditioning contexts. However, we find that OPSD methods can progressively degrade previously acquired capabilities: queries that are correctly responded at earlier training stages may become incorrectly responded as optimization proceeds, even the overall performance continues to improve. Further analysis reveals that this degradation coincides with a deterioration of the geometry of hidden representations, characterized by reduced intra-cluster compactness and diminished inter-cluster separation. Motivated by this observation, we propose Representation Geometry Regularization (RGR), which preserves representation geometry during post-training by encouraging compactness within cluster and separation across cluster. RGR can be seamlessly integrated into existing OPSD methods without a

---

### [45] Rethinking Entropy Allocation in LLM-based ASR: Understanding the Dynamics between Speech Encoders and LLMs

**链接**: https://arxiv.org/abs/2604.08003
**作者**: Yuan Xie, Jiaqi Song, Guang Qiu, Xianliang Wang, Ming Lei, Jie Gao 等 (7 人)
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] QTestBench: A Test Framework for Evaluating LLM-Generated Quantum Code

**链接**: https://arxiv.org/abs/2610.13811
**作者**: Meriem Terki, Nouhaila Innan, Minghao Shao, Muhammad Kashif, Alberto Marchisio, Muhammad Shafique
**来源**: cs.LG cs.CL quant-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong results in classical code generation and are increasingly used to write the unit tests that safeguard that code. Whether they can do the same for quantum software is less clear, because quantum programs are probabilistic, depend on numerical tolerances, and are judged by domain-specific checkers, so a well-formed test can still disagree with the benchmark's verdict. Existing quantum benchmarks measure whether a model produces a correct solution, but not whether its tests can distinguish correct implementations from faulty ones. We introduce QTestBench, a framework that evaluates LLM-generated quantum test suites against independent benchmark checkers, never treating the tests themselves as ground truth. For each task, QTestBench prompts models to produce syntactic, semantic, and behavioral tests, injects candidate solutions at runtime, and compares each test verdict with the checker's label under three validation cohorts, each answering a 

---

### [47] Trajectory-Aware Policy Optimization: Closing the State Distribution Gap in Long-Horizon LLM RL

**链接**: https://arxiv.org/abs/2610.13020
**作者**: Zhicheng Cai, Weinan Dai, Yuyan Zhou, Wei-Ying Ma, Ya-Qin Zhang, Hao Zhou
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has become a dominant paradigm for enhancing LLMs' reasoning capabilities. Yet long-horizon autoregressive rollouts introduce a fundamental limitation: local policy mismatch can compound into severe state distribution shift over trajectories. Existing LLM RL methods, such as GRPO and GSPO, control policy mismatch at the token or sequence level, but overlook this trajectory-induced shift, causing training instability and eventual collapse as the horizon grows. To close the state distribution gap, we propose Trajectory-Aware Policy Optimization (TAPO), a principled framework that theoretically derives the state-distribution correction from the off-policy policy gradient and incorporates it into the RL objective. TAPO further employs a geometric-mean estimator for variance reduction, together with a length-aware dynamic clipping that prevents overly deviated updates across the trajectory. Extensive experiments demonstrate that TAPO significantly surpasses exist

---

### [48] TreeHCA: Hindsight-Guided Exploration and Credit Assignment for Multi-Turn LLM Agents

**链接**: https://arxiv.org/abs/2610.12828
**作者**: Debajoy Mukherjee, Jeremy Carleton, Sushil Vemuri, Srinivas Shakkottai, Dileep Kalathil
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Outcome-supervised group-relative policy optimization (GRPO) assigns the same advantage to every token in an LLM agent trajectory, leaving useful and unhelpful decisions undifferentiated. Hindsight credit assignment (HCA) can refine this feedback, but its estimates rely on trajectories containing informative alternatives at consequential histories. We introduce TreeHCA, which couples hindsight-guided exploration with hindsight credit assignment. TreeHCA uses changes in reference-answer likelihood to revisit intermediate histories and sample alternative continuations, forming a tree of reasoning and tool interactions. Because this exploration changes the distribution of sampled continuations, we derive the corresponding inverse-hindsight importance correction, including an exact finite-pool identity. We use this structure in a normalized tree backup that propagates terminal outcomes into turn-level advantages. This shared hindsight structure is TreeHCA's central design principle, linkin

---

### [49] Meta-Reflective Evolution Effectively Improves Production AI Systems

**链接**: https://arxiv.org/abs/2610.12794
**作者**: Seung Won Wilson Yoo, Chang Zeng, Aditi Somayajula, Sahithi Ankireddy, Rohan Kosalge, Avishree Khare 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-guided evolutionary optimization has successfully improved prompts, programs, and even entire AI systems. Most optimization methods select a candidate from the search frontier, then mutate it in one LLM pass based only on its failures. This focus on the frontier can stall on production AI systems, where isolated failures reveal little about complex, hidden interactions. We introduce CoCoEvolve (Cortex Code Evolve), an evolutionary optimizer built around what we call meta-reflection, wherein an agentic mutator (Cortex Code) selectively retrieves evidence from the entire evolutionary history and probes the live system before verifying and proposing mutations. We apply CoCoEvolve to optimize three classes of production AI systems: data agents, LLM-powered data pipelines, and data engineering workflows. On DABStep, CoCoEvolve tops the public leaderboard, reaching 92.8% held-out hard accuracy compared to 78.4% for Meta-Harness and 30.4% for GEPA under matched cond

---

### [50] Faithful and Complete LLM-Assisted Automated Construction of Hierarchical Hardware Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.12762
**作者**: Haotian Qiao and Robert P. Dick
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hardware datasheets contain engineering specifications essential for component selection, system integration, and hardware compatibility verification. However, manual inspection is tedious and error-prone because datasheets are lengthy and heterogeneous, with dense information fragmented across tables, figures, and text. Although large language models (LLMs) can automate this process, na\"ive one-shot processing omits relevant specifications even when the document fits within the model's context window. We present an automated LLM-driven pipeline that transforms hardware datasheets into general-purpose hierarchical hardware knowledge graphs through chunk-based property extraction, hierarchical routing, and iterative refinement. The framework uses LLMs for information extraction and semantic reasoning while preserving source provenance and applying graph updates through validated instructions and deterministic local execution. This staged design reduces per-query context and maintains t

---

### [51] AMLworld-Compact: Importance-Weighted Downsampling for Cost-Effective LLM Evaluation and Error Diagnosis

**链接**: https://arxiv.org/abs/2610.13627
**作者**: Natapong Nitarach, Phume Ngampornsukswadi, Pittawat Taveekitworachai, Surapon Nonesung, Warit Sirichotedumrong, Kunat Pipatanakul
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating large language models (LLMs) on AMLworld's smallest test splits is costly because each of over a million targets requires a separate graph prompt. Sampling reduces this cost, but small balanced subsets change unweighted precision and F1. We introduce AMLworld-Compact, an evaluation set that retains every illicit test transaction and samples benign transactions from supervised-score strata. Its HT-Coreset protocol reduces evaluation targets by 271x and 611x on HI-Small and LI-Small. Horvitz-Thompson weights give unbiased full-test confusion-count estimates for fixed predictions; recall is exact, while precision and F1 are ratio estimates. In a held-out study using Graph Feature Preprocessor (GFP) features, one boosted-tree family defines strata for evaluating the other over 500 draws per configuration. At the released sizes, F1 RMSE is 0.00-2.58 percentage points versus 4.44-7.41 for uniform sampling with HT weights; conservative intervals remain broad. Under the evaluated gr

---

### [52] Human and LLM Facilitation in Collaborative Design Meetings: A Computational Behavioral Comparison

**链接**: https://arxiv.org/abs/2610.13082
**作者**: Mohammed Azeez Khan, Aaron Dsouza, Ashutosh Mishra, Ummul Faiz Z. Bibi, Neha K. Nair, and Amar Kumar Behera
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly being explored as facilitators of group discussion and collaborative work, but the behavioral differences between LLM-generated and human facilitation remain insufficiently characterized. We compare human Project Manager facilitation turns from scenario-based collaborative design meetings with Llama 3.1 8B Instruct responses across 199 paired contexts from the AMI Meeting Corpus. The analysis covers five confirmatory dimensions: contextual semantic distance, a lexical elaboration proxy, empathyand-hedge lexical density, topic divergence, and phase-vocabulary alignment. An exploratory directiveness measure failed domain validation and is not interpreted. The sampled human Project Manager turns were higher on contextual semantic distance (r = 0.644) and on empathyand-hedge lexical density (r = 0.203). The second contrast is carried mainly by hedge terms, so we read it as lexical hedging rather than psychological empathy. Llama-generated facil

---

### [53] Do More Agents Help? Evaluating Accuracy and Cost in LLM Multi-Agent Workflows

**链接**: https://arxiv.org/abs/2606.05670
**作者**: Yuhang Fu, Ruishan Fang, Jiaqi Shao, Huiyu Zheng, Zhengtao Zhu, Bing Luo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] GeoFitBench-LLM: A Benchmark for Assessing Large Language Models' Capabilities in Geospatial Data Requirements Elicitation for Geo-Analytic Tasks

**链接**: https://arxiv.org/abs/2610.12669
**作者**: Amirhossein Vahdat, Thierry Badard and Luc Lamontagne
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are becoming central to GeoAI systems, yet their evaluation rarely considers the elicitation of geospatial data requirements. This omission is critical as retrieval oriented geo-analytic tasks cannot be supported reliably without first identifying the necessary datasets and constraints. GeoFitBench-LLM is introduced as a benchmark for assessing whether LLMs can infer the datasets, the supporting resources and the constraints required by geo-analytic requests in natural language. The benchmark is structured around two reasoning dimensions, Spatio-Temporal Relational and Semantic Grounding, reflecting long-standing challenges in geospatial information retrieval and related natural language tasks. Ground truth requirements are encoded in a fixed, provider-independent schema for reproducible evaluation of resource identification and attribute-level specification. Experiments on seven models under minimal prompting indicate that identifying the necessary resources is o

---

### [55] Robust Langevin Sampling under State-Dependent Heavy-Tailed Noise with Applications to LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.12865
**作者**: M. Berk Sahin, Ege C. Kaya, Arda Fazla, Behzad Sharif, Abolfazl Hashemi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing convergence guarantees for non-log-concave sampling with stochastic gradient Langevin Monte Carlo (SG-LMC) typically assume globally Lipschitz gradients and uniformly bounded noise variance. Both assumptions can fail even in elementary sampling problems, and relaxing them better reflects practical applications such as Bayesian fine-tuning of large language models (LLMs). We relax both assumptions through generalized smoothness and our proposed state-dependent heavy-tailed oracle with finite $p$-th moments, $1<p\leq 2$. The oracle permits infinite variance when $p<2$ and includes the Blum-Gladyshev (BG-0) condition. We study these relaxations separately and jointly, proposing three methods. Under globally Lipschitz gradients, robust LMC (R-LMC) handles the proposed oracle through geometric-median centering and residual clipping. With exact gradients, adaptive LMC (A-LMC) controls discretization error under generalized smoothness. Robust adaptive LMC (RA-LMC) addresses both rela

---

### [56] Tracing and Taming Hallucinated Terms via Subsequence-Association Filtering and Breadth-Aware Selection for LLM Query Expansion

**链接**: https://arxiv.org/abs/2610.13810
**作者**: Amit Kumar Jaiswal, Sagar Uprety, Prayag Tiwari
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are now a standard source of query expansion terms but they hallucinate. They inject non existent entities and off-topic terms that add ranking noise and can hurt strong retrievers. Existing remedies such as corpus grounding, mutual verification and preference alignment treat hallucinated terms as an undifferentiated nuisance to be filtered by agreement heuristics, without a mechanistic account of why a given term appears or a principled criterion for how many terms to keep. We propose Subsequence-Association Filtered, breadth-aware query expansion (SAFE-QE), a training-free, retriever agnostic method that draws on the subsequence-association account of hallucination. We score each candidate expansion term by its corpus conditioned cross-context reproducibility, terms that reappear under randomised query contexts yet lack support in the pseudo-relevant set are flagged as products of dominant hallucinatory associations and down-weighted. Drawing on the chara

---

### [57] SynAct: Synergistic Active Feedback Learning for LLM Agents

**链接**: https://arxiv.org/abs/2610.12651
**作者**: Ning Liu, Ian Li, Kristina Klinkner
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents executing multi-step workflows fail in two fundamentally different ways: recoverable slips, which further attempts can repair, and knowledge gaps, which retrying cannot resolve. Expert feedback can address the latter, but expert attention is scarce. The key challenge is therefore not whether to ask for feedback, but where feedback can change the outcome. Existing approaches either avoid expert feedback, allowing agents to reinforce their own errors, or allocate feedback at the task level without identifying consequential decisions. We present SynAct, an active learning framework that treats expert attention as the binding constraint and allocates feedback at the level of individual decisions. SynAct ranks decisions by the mutual information between the selected action and the terminal outcome across repeated rollouts, queries an expert at the highest-value decisions, and distills the resulting corrections into transferable rules that the agent can reuse without expert access

---

### [58] Agent4Spec: An LLM-based Agentic System to Optimize API Specifications through Automated Validation and Market Analysis

**链接**: https://arxiv.org/abs/2610.13273
**作者**: Yongjian Tang, Costel Moraru, Doruk Tuncel, Hanya Elhashemy, Steffen Klepke, Thomas Runkler
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> API specifications serve as critical documentation for modern software development, directly impacting integration efficiency and client code generation. While recent advancements have leveraged Large Language Models (LLMs) to generate initial specifications from source code, existing approaches treat this process as a one-time event - overlooking the needs for continuous validation, long-term maintenance, and market-driven evolution of these artifacts. To address this issue, we present Agent4Spec, an autonomous multi-agent framework featuring two distinct pipelines: (1) a validation pipeline that detects and self-corrects OpenAPI syntax errors, and (2) a market analysis pipeline that conducts competitive research, identifies functional gaps against industry leaders, and automatically generates missing API-spec functionalities. We evaluate Agent4Spec on two curated datasets of API specifications spanning both general-purpose and industrial scenarios. Among 9 SOTA LLMs, the top-performe

---

### [59] Inject a Turn, Not a Token: Learning Where to Redirect LLM Reasoning for Self-Correction

**链接**: https://arxiv.org/abs/2610.13672
**作者**: Jiwon Jeon, Myungsik Cho, Jeonghye Kim, Youngchul Sung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models struggle to reliably identify and correct errors in their own reasoning. Unlike prior training-based approaches that fine-tune an LLM to generate revisions or feedback, we learn where to intervene in failed rollouts and determine how to redirect them. To choose where to intervene, we train a 130K-parameter MLP head on a frozen encoder using only final-answer correctness. For redirection, we find that under a fixed generation budget, the tested inline injections fail to reliably redirect reasoning, whereas presenting the same instruction in a new user turn changes the model's course. The resulting correction framework, UPTURN (User-Prompt TURN injection at a learned position), requires no LLM fine-tuning: it retains a selected prefix, injects an instruction as a new user turn, and regenerates the suffix. Across four reasoners and six math benchmarks, UPTURN improves average accuracy in every setting over a 32-rollout baseline. It outperforms self-correction and ref

---

### [60] Rollout-Time Intervention: Unlocking Agentic Reinforcement Learning Beyond Policy Limits

**链接**: https://arxiv.org/abs/2610.13438
**作者**: Chen Xi, Ding Ruixue, Wang Zhigaoyuan, Zhang Fanrui, Zhang Qiang, Chen Boli 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has emerged as a key paradigm for improving large language model (LLM) agents, enabling stronger reasoning, planning, and tool-use in interactive environments. However, existing agent RL methods remain fundamentally constrained by an on-policy reasoning bottleneck: when tasks exceed the model's current capability boundary, effective trajectories become extremely sparse and training often collapses. We introduce Rollout-Time Intervention (RTI), a technique designed to elicit successful trajectories beyond the policy's intrinsic exploration capacity. RTI operates by leveraging reward-side evidence (i.e., evaluation rubrics) during rollout to convert erroneous trajectories into successful ones, providing effective learning signals for tasks that the policy rarely solves on its own. Although intervention trajectories are inherently off-policy, we find that they can effectively guide policy optimization when trajectories with excessive distributional shifts are f

---

### [61] Agreement Without Alignment: Label-Free Rubric Clarification Increases LLM-Judge Consensus but Not Agreement with Humans

**链接**: https://arxiv.org/abs/2610.13303
**作者**: Sangdo Han, Moonsoo Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges are increasingly deployed as panels, and disagreement among panel members is often read as a symptom of an unclear rubric. We test a label-free procedure that turns this disagreement into rubric repairs. The procedure decomposes each rubric into sub-criteria, ranks them by cross-judge disagreement on a development split, and has an editor model rewrite only the most contested ones. An additional stage that moves text-checkable sub-criteria to deterministic checkers transferred none in our evaluation. Human labels are never used to select or edit clauses; they are used only to evaluate the outcome. We pre-specified four hypotheses in a version-controlled protocol and evaluated six rubric conditions with a panel of five judges from three providers on SummEval, the HealthBench meta-evaluation, and USR Topical-Chat, for a total of 129,770 judge requests, excluding retries. On SummEval, the procedure raised inter-judge Krippendorff's $\alpha$ by 0.069 (95% CI 0.046 to 0.092) over

---

### [62] Competence-Aware Orchestration for LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.13144
**作者**: Songmiao Wang, Yuchen Wang, Chenglin Yu, Hongxia Yang, Ming Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) have emerged as a promising paradigm for enhancing complex reasoning through role specialization and collaboration, yet a key challenge remains: how can collaboration be adapted to a backbone's competence on the current query? This problem matters because more collaboration is not always better--richer coordination may help on difficult cases, but it also incurs additional token cost and redundant interactions. We propose a two-stage competence-aware framework for automatic MAS orchestration. It first models the LLM backbone's task-conditioned competence for the current query, and then uses this signal to adapt role activation and the communication graph. Across six benchmarks, our method achieves an average score of 93.81%. Experiments with six LLM backbones of varying competence levels further show that our method adjusts collaboration according to the inferred competence: for higher-competence backbones, it improves average accuracy from 87.22 to 

---

### [63] Decoupling Logic from Persona: Structural Immunity of Edge LLM Agents to Context Pollution

**链接**: https://arxiv.org/abs/2610.09772
**作者**: Masaaki Nakatsu (AO, Inc. / OrbLabs AG), Reno Wang (AO, Inc.)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Test-Time Memory Construction

**链接**: https://arxiv.org/abs/2610.13348
**作者**: Zijun Wang, Yifan Ji, Haidong Xin, Zhenghao Liu, Yukun Yan, Zulong Chen 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) struggle to answer questions over long interaction histories, where relevant evidence may be scattered across distant sessions. Existing memory systems typically construct and maintain sophisticated memory representations offline, before user queries are observed, incurring substantial overhead and limiting their ability to adapt memory construction to query-specific information needs. In this paper, we propose T$^2$Mem, a Test-Time Memory construction framework that defers memory construction to inference and progressively builds memory along the reasoning process. Specifically, T$^2$Mem extracts lightweight episode-level metadata offline to capture key events and temporal associations as retrieval cues, while retaining links to the original interactions to facilitate the reconstruction of dependencies across episodes. At test time, the LLM adaptively retrieves and organizes metadata and raw interactions, progressively constructing query-specific memory as

---

### [65] Temporal Evidence Forests for Long-Horizon Multi-Party Conversational Memory

**链接**: https://arxiv.org/abs/2610.12874
**作者**: Junyou Guo, Chongyang Tao, Yan He, Yong Wang, Shuai Ma
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory has been widely adopted in LLM-based agents to support persistent interaction and personalized assistance. Long-term multi-party interactions, however, accumulate substantially more detailed information, with decisions repeatedly updated and states evolving across participants and interaction stages. Temporal structure is therefore crucial for tracing such memories: relevant information often appears densely within short intervals, while transitions among different states are anchored by a strict temporal order. Existing temporally aware memory frameworks primarily store time as metadata or use temporal signals to guide retrieval over preconstructed memory structures, without using temporal structure to both recover locally concentrated evidence and reconstruct its complete event progression. To address these limitations, we propose T-Mem, a temporal-structure-based memory framework that preserves interactions and organizes query-relevant evidence through two temporal 

---

### [66] Training User Simulators with Latent Intrinsic Feedback

**链接**: https://arxiv.org/abs/2610.13617
**作者**: Tarek Naous, Craig Boutilier, Wei Xu, Ofer Meshi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> User simulators are gaining attention as environments to train LLM assistants that can better cope with the nuances of multi-turn conversations with real users. Prior work on user simulation has emphasized generating realistic user utterances, leaving unexplored their potential as a source of direct feedback on the assistant's responses. Such evaluation signals may not be explicitly communicated in language, but can instead reside in the latent reasoning of users. In this work, we introduce user simulators with intrinsic feedback, namely, models equipped with latent evaluation states: internal thoughts, reactions, and scalar ratings that evaluate the assistant from a first-person user perspective at each conversation turn. We train LLM-based simulators using interaction logs between real users and assistants and demonstrate that intrinsic feedback improves simulation realism and critiquing behaviors versus prompted simulator baselines, while also providing turn-level evaluations that e

---

### [67] RegulaTutor: A Theory-Informed Framework for Long-Term Personalized Learning

**链接**: https://arxiv.org/abs/2610.13399
**作者**: Yonggang Li, Boqian Han, Rui Sheng, Yushi Sun, Zixin Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term personalized tutoring requires language models to translate a learner's evolving history into appropriate instructional support. Existing LLM-based tutoring systems use memory and retrieval to personalize responses, but the pedagogical rationale linking historical evidence to teaching strategies is not always explicit. We introduce RegulaTutor, a theory-informed framework for long-term personalized tutoring that connects historical evidence, learner interpretation, and learner-facing instruction. Guided by self-regulated learning (SRL) research, its tutoring harness operationalizes a cognitive, affective, metacognitive, and motivational (CAMM) framework for deriving evidence-supported learner interpretations and teaching policies. The resulting policies retain links to their supporting evidence and are updated as new observations arrive. This staged workflow also supports systematic refinement through PairRoute, an offline procedure that uses intermediate execution records to

---

### [68] Cancerous Backdoor Attack: Gradual Activation via Invisible Tokens and A Stage Controller

**链接**: https://arxiv.org/abs/2610.12644
**作者**: Tahmid Imtiaz Imu, Emama Nahid, Prodipta Sen Amartya, Ahsanul Jobayer, Yutong Song, Jiang Wu 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Backdoor Attacks on Large Language Models (LLMs) typically follow a trigger-response pattern, where satisfying a trigger condition activates a single terminal behavior. However, this single-point backdoor activation does not explore attacks in which malicious behavior develops gradually through multiple intermediate stages before reaching the terminal activation stage. We present Cancerous Backdoor Attack, that gradually corrupts an LLM's reasoning over a sequence of interactions by leveraging invisible tokens and a stage controller. Specifically, invisible tokens provide hidden stages to the model without appearing in the user's visible request and the stage controller tracks the attack's progression during inference to realize gradual activation. We evaluate Cancerous Backdoor Attack across several reasoning datasets. The attack consistently produces gradual reasoning corruption across models and tasks. We compare Cancerous Backdoor Attack with prior backdoor attack baselines to demo

---

### [69] Not Just an Evaluation: A Case Study of Discourse Particle Sensitivity in Language Models

**链接**: https://arxiv.org/abs/2610.13794
**作者**: William Sheffield, Jiahui Chen, Amy Zhang, Alex Warstadt, Junyi Jessy Li, Kanishka Misra
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Discourse particles subtly shape the flow of discourse by reflecting conversational context and interlocutor attitudes, often leaving the truth-conditional meaning untouched. They are also often polyfunctional, with distinct senses which partially overlap with other particles; for example, the exclusive use of English "just" and "only" ("John only/just drinks water"). Despite the frequency of these words in natural language, they have gone largely unstudied due to the subtle nature of their effects. We investigate LLM sensitivity to "just" and "only" in natural conversations using behavioral and mechanistic analyses. First, we find that LLMs and humans similarly prefer the presence of these particles in context, and both are more sensitive to "just" compared to "only". Second, when sampling from LLMs with and without these particles, we find LLMs consistently rate generations as more likely, given their source context, demonstrating their particle sensitivity. In both experiments, inst

---

### [70] GeoGR: Spatial-Semantic Token Compression and Group Routing for Efficient 3D VLMs

**链接**: https://arxiv.org/abs/2610.13035
**作者**: Yongxin Zheng, Hao Wu, Fang Li, Hu Fu, Peiran Yin, Xudong Wang 等 (10 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-view representations enable pretrained image and video vision-language models to understand 3D scenes, but their long visual token sequences make inference costly. Redundancy arises both from repeated observations of the same scene regions across views and from processing all visual tokens at every LLM layer, regardless of their relevance to the current computation. We propose GeoGR, a two-stage framework that jointly compresses scene representations and visual computation. At the projector level, GeoSemZip consolidates cross-view observations into 3D voxel tokens and combines semantic saliency with spatial coverage to construct a compact scene representation. Unselected voxel features are aggregated into contextual anchors to retain scene information that would otherwise be discarded. At the LLM level, we identify an effective visual computation window and observe that query-conditioned token relevance remains locally stable but changes over longer layer intervals. Guided by the

---

### [71] DP-MIND: Differentially private memory-guided Long context Inference

**链接**: https://arxiv.org/abs/2610.13132
**作者**: Zhihao Liu, Yitian Cheng, Shuang Liu, Rui Wen, Yuke Hu, Zhan Qin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Service has become a dominant paradigm for accessing large language models without requiring local deployment. However, the process raises severe privacy concerns when user queries may include sensitive or confidential contexts. Differential privacy (DP) provides a principled approach to protecting such inputs, but existing DP inference methods are primarily designed for short- or moderate-context settings and struggle with million-token-scale inputs due to limited context capacity and severe utility degradation under DP perturbation. In this paper, we propose DP-MIND, a memory-guided framework that scales differentially private inference to million-token contexts. DP-MIND enables private long-context inference by locally perturbing the input and processing it chunk by chunk with a compact memory that preserves task-relevant information across the sequence. To make this memory robust to DP noise, we optimize the memory construction policy directly on perturbed inputs using rei

---

### [72] Verifiable Retrieval for Legal Reasoning through Structure-driven Knowledge Graph

**链接**: https://arxiv.org/abs/2610.13695
**作者**: Ibrahim Siddig, Sviatoslav Tugeev, Munir Georges
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Any automation within reliability-critical contexts such as medicine or law has to be transparent and verifiable. Despite their advantages, current LLM-based systems do not meet these requirements due to their inherent black-box nature. Retrieval Augmented Generation (RAG) attempts to ground the generative process in the relevant interpretable documents, thereby reducing the risk of AI 'hallucinations' and potentially enabling verification of the initial generation context. However, as the number and size of potential sources increases, naive retrieval approaches tend to perform worse, ignoring critical context elements. In this paper we aim to tackle this problem in the context of German Legal Code. Using structure-driven parsing to create a Knowledge Graph (KG) for the source document navigation and retrieval, we compare several KG-informed chunking and retrieval strategies and evaluate their effect on the accuracy of retrieved citations.

---

### [73] CLEAT: Learning Value-Guided Clarification for Interactive Agents

**链接**: https://arxiv.org/abs/2610.12655
**作者**: Jiatan Huang, Zheyuan Zhang, Ziming Li, Tianyi Ma, Mingchen Li, Yanfang Ye 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can execute increasingly complex tasks, but effective assistance also requires aligning their actions with goals and constraints that users may leave unstated. We study this problem as interactive intent alignment through clarification. Yet clarification is useful only when the agent can turn the answer into better decisions. As training changes how the agent handles incomplete information and uses additional answers, the same clarification can become more or less useful. We introduce CLEAT (CLarification through valuE-guided Agent co-Training), a framework that co-trains a clarification-value controller and the task policy from shared interaction outcomes. We formulate residual query value to measure the task utility gained by asking rather than proceeding under the current policy, and estimate it through paired rollouts from the same interaction history. These paired returns train the controller to predict clarification value and the task policy to select useful questions 

---

### [74] A Critical Look at Power Sampling when Test Time Sharpening LLMs

**链接**: https://arxiv.org/abs/2610.13653
**作者**: Abiel Malkani Talwar, Christopher Nemeth, Henry Moss
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) has substantially improved LLM reasoning, yet growing evidence suggests it mainly performs distribution sharpening: concentrating probability mass on reasoning paths the base model already produces. Recent work therefore seeks RLVR's gains without needing reward signals, by sampling from the power distribution $\pi_\alpha \propto \pi_{\text{base}}^\alpha$ via Markov chain Monte Carlo or sequential Monte Carlo. We show that these samplers fail to converge to $\pi_\alpha$ under realistic compute budgets, and that their gains are largely recreated via simple Best-of-$N$ with appropriate grading . This suggests they succeed by selecting high-probability sequences, not by approximating $\pi_\alpha$, raising a natural question: is the power distribution itself a worthwhile target? We test this hypothesis directly by fine-tuning the base model to match $\pi_\alpha$, sidestepping sampler convergence issues entirely. Despite approximating th

---

### [75] Contextual Correction of Parallel Draftsfor Speculative Decoding

**链接**: https://arxiv.org/abs/2610.12570
**作者**: Roy Eisenstadt, Harel Lidar, Tal Gonen, Omer Luxembourg, Itamar Zimerman, Lior Wolf 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by using a lightweight drafter to propose multiple tokens that are subsequently verified in parallel by the target model. Recent diffusion-based drafters make this paradigm particularly attractive: deep attention-based neural backbones provide strong predictions, while drafting multiple future positions in parallel avoids the sequential cost of autoregressive generation. This parallelism, however, comes at a cost. Tokens within a draft block are predicted without access to the realized identities of preceding draft tokens, removing intra-block dependencies that would naturally be available under autoregressive generation. We introduce DCOCO (DFlash Contextual Corrector), a lightweight mechanism that restores these dependencies while preserving parallel drafting. Rather than committing to each position's top prediction, DCOCO retains multiple candidate tokens and evaluates their contextual compatibility across adjacent draf

---

### [76] SWE-DeceptionBench: Benchmarking Deceptive Behaviors of LLMs Across the Software Development Lifecycle

**链接**: https://arxiv.org/abs/2610.13626
**作者**: Xiting Liu, Lin Yang, Yitong Zhang, Jia Li, Shi-Min Hu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used throughout the software development lifecycle. This growing reliance on LLMs raises concerns about their trustworthiness, with deception posing a particularly important risk. Deceptive behavior takes the form of misleading responses or assistance in fabricating, concealing, or distorting information. To study this behavior, we introduce SWE-DeceptionBench, a benchmark for evaluating LLM deception in software engineering. The benchmark covers six lifecycle stages and two deception triggers: Active Deception, where models recognize infeasible or conflicting requirements but still present them as achievable, and Passive Deception, where models help fulfill explicit user requests to mislead others. We further introduce Neutral, Reward, and Pressure conditions to study the effect of external inducements, resulting in 720 test instances in Chinese and English. Evaluating seven mainstream LLMs, we find substantial deception even under the Neu

---

### [77] Travel Back To Move Forward: Retrospective Exploration and Evolving for Long Horizon Agents

**链接**: https://arxiv.org/abs/2610.13058
**作者**: Ziang Ye, Wentao Shi, Lei Chen, Zhengzhou Cai, Yu Wang, Zhiyuan Yao 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly operate in long-horizon environments where early mistakes can trigger cascading failures and trap agents in dead-end trajectories. Agents must therefore be able to proactively recover from such states and turn their exploratory experience into guidance for subsequent decisions. We introduce ReTRAIL, a framework that enables agents to rewind the environment to earlier states while preserving valid progress and carrying forward knowledge learned from abandoned exploration. The environment state moves backward while the agent's knowledge continues to move forward. ReTRAIL trains a shared policy with two complementary signals: State-Anchored GRPO compares alternative continuations from revisited states to improve execution, while a branch-advancement reward guides reflection through the progress of subsequent exploration. Experiments across four interactive benchmark MineSweeper, Sokoban, ALFWorld and ScienceWorld show that simply adding a rewind pr

---

### [78] Large Language Models, Machine-Assisted Cultural Analytics, and the Agentic Turn

**链接**: https://arxiv.org/abs/2610.12792
**作者**: Andres Karjus
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Technologies like large language models make it easier to convert cultural material into analyzable variables, while LLM-driven agentic systems extend machine assistance to other parts of the research workflow. Rather than a full how-to guide or an exhaustive review of recent LLM use cases, this chapter looks at some crucial aspects of this new paradigm as well as the bigger picture. I argue that these technologies expand the scale, methodological range, and scope for delegation, while the basic logic by which those measurements support cultural claims remains mostly unchanged.

---

### [79] MoPrO-SD: Modular Prompt Optimization for Stance Detection

**链接**: https://arxiv.org/abs/2610.13386
**作者**: Meysam Sabbaghan, Nikesh Gyawali, Arman Zareian Jahromi, Sebastian Loera-Lozano, Doina Caragea, Cornelia Caragea
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Stance detection remains challenging for large language models (LLMs) due to implicit opinions, sarcasm, and context-dependent expressions of stance. Although automatic prompt optimization offers an alternative to fine-tuning without updating model parameters, existing structured approaches are not specifically designed around stance-label semantics and class-specific ambiguities. We introduce MoPrO-SD, a stance-specific prompt optimization framework that decomposes prompts into functional semantic modules and refines them sequentially using LLM-based feedback. We study three refinement strategies: instruction-only optimization (I), instruction with reasoning (I+R), and instruction with per-example reasoning (I+R+E), using class-conditioned errors for stance-label refinement. We also introduce VaccineStance, a new human-annotated benchmark for vaccine stance detection. Experiments across four datasets and five open-weight LLMs show that MoPrO-SD improves upon the human-written Base pro

---

### [80] CliQ-RRG: Clinical-Knowledge Guided Disease-aware Visual-Textual Alignment for QA-Style Radiology Report Generation

**链接**: https://arxiv.org/abs/2610.13059
**作者**: Chandravardhan Singh Raghaw, Shahid Shafi Dar, Arnav Nishith Sharma, Shrey Modi, Nagendra Kumar
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiology reports are essential for diagnostic reasoning and patient care, yet their manual preparation is time-consuming and cognitively demanding. Automatic radiology report generation (RRG) offers a scalable alternative, but existing models often produce lengthy, unstructured narratives that overlook diagnostic cues and multi-view information. We present Clinical-Knowledge Guided Disease-aware Visual-Textual Alignment for QA-Style Radiology Report Generation (CliQ-RRG), a unified two-stage framework for interpretable and clinically grounded reporting. In Stage 1, CliQ-RRG employs a Disease-aware Visual-Textual Alignment module that aligns image and text representations using predicted disease embeddings, reinforced by a Prior-Guided Attention Module (PrAM) to capture multi-view dependencies across current and prior scans. In Stage 2, GraphRAG-guided retrieval augments intermediate textual representations with graph-grounded clinical evidence, and a large language model restructures 

---

### [81] Sparse Dictionary Learning for Measure-Valued Data via Linearized Optimal Transport: Efficient Algorithms and Sample Complexity

**链接**: https://arxiv.org/abs/2610.12924
**作者**: Brendan Mallery, Shuchin Aeron, James Murphy
**来源**: stat.ML cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study dictionary learning for probability measure-valued data by embedding measures into Hilbert spaces using features derived from optimal transport geometry. We learn data-adapted dictionaries through sparse autoencoder parameterizations, producing fast, scalable representations of probability measures as sparse finite-dimensional codes. The resulting framework combines the rich, geometric structure of optimal transport with the interpretability and efficiency of sparse representation learning. We demonstrate its utility across diverse data modalities, including hyperspectral images, geometric point clouds, and document embeddings in large language model latent spaces. We also prove generalization bounds for sparse dictionary learning objectives on broad classes of $L^2$-valued measure embeddings, expressed in terms of the metric complexity of the atom class. For optimal transport and entropic transport map dictionaries, we derive new covering number bounds that yield explicit rat

---

### [82] r/ADHD: Community-Based Understandings of Time Management Challenges in Digital Environments

**链接**: https://arxiv.org/abs/2610.12629
**作者**: Shizhao Liu, Lei Cao, Celia T. Lee, Nikash Shanbhag, Renkai Ma, Kai Lukoff
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Community accounts of ADHD can complement clinical understandings by foregrounding members' own definitions of time-management difficulties and support. We used human-led, LLM-assisted thematic analysis to examine 5,379 relevant r/ADHD posts from 2020 to 2025. Across five challenge and nine strategy themes, members described difficulties beginning intended tasks, disengaging from digital media, and sustaining support. Tools often demanded the self-regulation they were meant to support, while lost time and tool breakdown carried guilt and self-blame. Members drew on people, routines, and environments alongside digital tools, often seeking advice and recognition from peers. These accounts broaden the design problem to include the practical and emotional work of sustaining support. They motivate tools that reduce this burden and evaluations that consider recovery after distraction and emotional costs alongside task outcomes.

---

### [83] GeopoliticalQA: Benchmarking Retrieval and Generation over Intelligence Reports

**链接**: https://arxiv.org/abs/2610.12617
**作者**: Veronika Solopova, Ivan Havlytskyi, Viktoria Skorik, Ostap Vykhopen
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geopolitical and strategic intelligence reports constitute a rich source of expert knowledge and have increasing value in the current political climate, but their heterogeneity and analytical complexity pose challenges for retrieval-augmented question answering. We introduce a benchmark for grounded question answering over 415 open-source geopolitical and strategic intelligence reports, comprising 5,525 document-grounded question-answer pairs spanning factual, inferential, comparative, and risk-oriented questions. We propose a document-aware generation pipeline that profiles reports before generating questions and validate dataset quality through expert annotation and an LLM-as-judge protocol. Using the benchmark, we evaluate 15 retrieval systems and six open-weight LLMs for RAG. We find that models perform similarly on document-level retrieval, while at the harder chunk level retrieval quality is not driven by embedding-model scale: bge-m3, a mid-size open encoder matches an order of 

---

### [84] A Baseline Assessment for the Agentic Web Technology Stack

**链接**: https://arxiv.org/abs/2610.13703
**作者**: Vagner Figueredo de Santana and Diogo Cortiz
**来源**: cs.AI cs.ET cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The fast pace in which protocols, frameworks, and technologies are being proposed for LLM-based agents results in a complex scenario for anyone aiming to create state-of-the-art AI solutions. Without an assessment on how different protocols, frameworks, and libraries work together to compose an Agentic Web solution, developers and organizations face different challenges (e.g., skilling, governance, infrastructure) even before becoming part of the Agentic Web ecosystem. In this context, we propose a system for performing Agentic Web evaluations called MASTIF (Multi-Agent System TestIng Framework) and present a baseline assessment of Agentic Web technologies, including 3 LLMs, 3 protocols, and 4 agent implementation frameworks, against 300 Mind2Web benchmark tasks. Results suggest that selecting a task-specific technology stack may result in gains of task completion rate, efficiency score, and social value stability scores; and reductions in verbosity and time to complete tasks. With the

---

### [85] Can Failed Trajectories Reveal Where Agents Go Wrong? Agentic Failure Attribution Without Step-Level Labels

**链接**: https://arxiv.org/abs/2610.13105
**作者**: Do Nguyen-Thanh, Junlin Fang, Bing Li, Zhen Fang, Sean Du
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Failure attribution for LLM agents aims to identify decisive steps responsible for task failure, which is critical for debugging and improving agentic systems. Existing methods rely on costly LLM prompting, step-level error annotations, or verified successful trajectories that lack failure signals for assistance. In this paper, we study failure attribution from step-unlabeled failure trajectories, where each trajectory is known to have failed but its decisive step is unknown. We propose SOAP (Spectral scOring with Attention-guided Propagation), an effective framework requiring neither step-level training labels nor a separate success-only reference set. SOAP first constructs a spectral reference space from LLM representations and assigns each step a base error score according to its projection behavior. Importantly, later steps may exhibit stronger failure signals because they inherit an earlier mistake, causing independent scorers to favor downstream consequences over the decisive err

---

### [86] PRIME: Pre-Retrieval Index Modeling Enhancement for Structured Document Retrieval-Real

**链接**: https://arxiv.org/abs/2610.13296
**作者**: Cheuk Hei Chung, Li Liu
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-precision retrieval over external knowledge bases is essential for LLM agents to operate effectively. However, existing Information Retrieval (IR) research primarily optimizes query-side retrievers (e.g., ColBERT, BGE) and generators (e.g., Self-RAG, GraphRAG), while reducing corpus-side representation to chunking. This leaves index-side quality an underexplored lever. We propose Pre-Retrieval Index Modeling & Enhancement (PRIME), an index-side optimization framework built on two complementary tracks: an LLM-driven Semantic Restructuring (SR) track that transforms long documents into structured, information-dense sections, and a deterministic Metadata Synthesis (MS) and Hierarchical Retrieval (HR) track that extracts semantic anchors and heading structure for coarse-to-fine section retrieval. Our evaluations show that deterministic metadata matches structure-aware chunking's retrieval quality while cutting embedding computation by 45.8 $\times$ and index vector count by 22.4 $\tim

---

### [87] KV-Repurpose: A Testbed for Evaluating Non-Prefix KV-Cache Reuse

**链接**: https://arxiv.org/abs/2610.13060
**作者**: Taiga Ikeda, Daisuke Miyashita and Jun Deguchi
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KV-cache reuse in large language model serving is commonly limited to exact prompt prefixes, preventing reuse when the same retrieved document appears after different system prompts, conversation histories, or dynamic metadata. We present KV-Repurpose, an open-source, vLLM-based system for developing and evaluating segment-wise KV-cache reuse beyond exact prefixes. The system combines cache-aware segment scheduling, prompt construction, capacity management, workload generation, and runtime monitoring. Experiments on long-context benchmarks show that naive segment reuse largely preserves output quality for single-document question answering and summarization, while exposing clear limitations in cross-document reasoning. Under a Zipfian RAG-style workload in which 20% of requests share a fixed prefix, KV-Repurpose achieves a substantially higher token-level cache hit rate than prefix caching at the same 30 GB cache capacity, 63.9% versus 3.3%, resulting in lower TTFT. Even with 1 TB of c

---

### [88] Proactive Agentic Orchestration

**链接**: https://arxiv.org/abs/2610.13485
**作者**: Xueyang Feng, Chaozhuo Li, Xiaohe Bo, Jiakai Tang, Chenxi Li, Qiwei Ye 等 (7 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic orchestration delegates tasks to sub-agents with independent contexts, providing a key path to extending the effective execution horizon of large language model agents. However, existing orchestration methods face two limitations: in execution, current methods fix sub-agents' goals and harnesses at creation time, limiting their adaptability to dynamic real-world environments; in optimization, sparse and delayed feedback constrains effective learning of the orchestration policy. To address these limitations, we introduce POrchestra, an on-the-fly proactive agentic orchestration framework. It allows sub-agents to proactively communicate with the orchestrator at any logical point to request harness adjustments while maintaining continuity of local execution. This mechanism not only enables sub-agents to adapt seamlessly to dynamic environments but also naturally inspires On-Policy Orchestration Distillation (OPOD) based on hindsight feedback. OPOD attributes sub-agents' proactive 

---

### [89] Quality, Not Just Outcome: A Structural Scoring Framework for Selecting Coding-Agent Trajectories for Supervised Fine-Tuning

**链接**: https://arxiv.org/abs/2610.13152
**作者**: Sida Li, Yuanxin Liu, Shicheng Li, Linli Yao, Xu Sun, Haoli Bai 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open coding agents are commonly trained through supervised fine-tuning on interaction trajectories whose final patches pass the benchmark test suite. However, this outcome-level filtering criterion ignores process quality: trajectories that eventually succeed may still contain inefficient interaction patterns such as repetitive file inspection, unstable tool usage, or delayed modification behavior, all of which become part of the imitation target. We propose TQS (Trajectory Quality Score), a structural scoring framework for coding-agent trajectories that operates directly on trajectory structure, requires no LLM judge, and runs in linear time. TQS characterizes trajectory quality through structural signals organized around structured convergence: information focus, intent--action alignment, and policy dynamics. Using 155,144 successful trajectories from a public open-license corpus, we rank trajectories by TQS and fine-tune coding agents on filtered subsets. Models trained on top-ranke

---

### [90] Humanize MLE Agents: Multi-Agent Session Alternation Beyond Single-Agent Limits

**链接**: https://arxiv.org/abs/2610.13494
**作者**: Changye Li, Zijian Zhang, Muheng Li, Yiduo Pang, Tingjun Wu, Menghan Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM-based agent approaches for long-horizon machine learning engineering (MLE) often use context engineering, implemented through custom harnesses that manage tools, skills, and accumulated experience. However, we find that as single-session execution lengthens, the agent's reasoning intensity declines alongside slowing progress, summarized as long-horizon deceleration, and the benefits of these custom harnesses vanish as the underlying model improves, summarized as harness staleness. These findings suggest that their benefits may not persist across versions, which motivates a workflow-level approach in which agents build on one another's work across sessions. We model these alternating agent sessions as a context-reset semi-Markov decision process (CR-SMDP) and establish sufficient conditions for alternation to exceed single-agent reference limits, derive an explicit experiment-budget bound, and characterize when session caps preserve this advantage. Guided by this analysis, 

---

### [91] Monarch-MoE: Structured Experts for Multimodal Continual Instruction Tuning

**链接**: https://arxiv.org/abs/2610.13215
**作者**: Xi Zhang, Boyu Diao, Zesen Chen, Ruiqi Liu, Hangda Liu, Yongjun Xu
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning new tasks in multimodal continual instruction tuning can cause catastrophic forgetting of previously acquired knowledge. Although multi-expert LoRA distributes learning across experts, updates to a dense low-rank expert can still affect many output features. We introduce Monarch-MoE, which replaces the dense factors in LoRA experts with block-diagonal factors connected by a fixed permutation. This structure provides blockwise gradient isolation: individual block-pair updates affect only one output block, while connections between all input and output blocks are maintained. To make these compact experts practical on memory-limited hardware, we combine batched computation, fused forward operators, and an optimized backward pass. Across three continual-learning methods evaluated on MLLM-DCL and UCIT with LLaVA-1.5-7B, Monarch-MoE improves first-task retention while reducing adapter parameters by approximately 75% and 50%, respectively. In the main comparison, first-task forgettin

---

### [92] TerraAgent: Demonstration-Grounded Multi-Agent Reasoning for Long-Context Remote Sensing Visual Question Answering

**链接**: https://arxiv.org/abs/2610.12517
**作者**: Jingwen Huang, Yiming Fang, Hanxiao Wu, Boyuan He, Keyi Luo
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote sensing visual question answering (RS-VQA) requires answers that truly depend on image evidence, yet current remote sensing multimodal large language models (RS MLLMs) are still evaluated mainly by accuracy, which cannot reveal whether a correct answer was produced without using the image. This setting introduces three challenges: demonstrations retrieved across different ground sample distances (GSD), sensors, and city textures may be poorly matched; real queries often involve long visual contexts from multi-scale tiles, multi-temporal frames, and retrieved knowledge, where evidence can be diluted and errors can propagate through multi-step reasoning; and prior-only answering remains invisible to standard metrics. We present AVA, a training-free framework that wraps a frozen RS MLLM with three modules. GDR performs GSD-bucketed, scene-graph-based demonstration retrieval and filters demonstrations whose answers are unsupported by their images. MACE decomposes each query into an 

---

### [93] Nimbus Studio reproduces reference BCI decoding pipelines: a validation study on public benchmarks across protocols and paradigms

**链接**: https://arxiv.org/abs/2610.13894
**作者**: Sergey Musienko
**来源**: cs.HC
**匹配关键词**: BCI, Brain-Computer Interface
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nimbus Studio is a visual pipeline platform for brain-computer interface (BCI) experiments: researchers assemble preprocessing, feature extraction, decoding, and evaluation over public benchmark datasets or their own recordings, with cross-validated evaluation protocols (including leave-one-subject-out), BIDS export, and bring-your-own Python model classes. Whether its numbers can be trusted is a fair question for any such platform. We answer it with a parity study: six standard BCI decoding pipelines (CSP+LDA, Riemannian MDM, tangent-space logistic regression through the platform's bring-your-own-code node, P300 xDAWN+LDA, and the deep ShallowConvNet and EEGNet) were evaluated on three public datasets (motor-imagery BNCI-2014-001/004; P300 BNCI-2014-009) under two protocols (per-subject session holdout and pooled leave-one-subject-out cross-validation via the platform's planned-CV driver), once through Nimbus Studio's execution engine and once through independent, hand-written referen

---

### [94] ThinkNet: Evolutionary Deep Ensembles for Efficient Motor-Imagery EEG Classification

**链接**: https://arxiv.org/abs/2609.33967
**作者**: Abdul Basit, Saim Rehman, Muhammad Shafique
**来源**: cs.HC cs.AI cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] Replaying the Movie in Your Mind Decoding Dynamic Visual Perception and Recall from EEG

**链接**: https://arxiv.org/abs/2610.13120
**作者**: Zikai Fang, Tian-Yi Zhou, Xuan-Hao Liu, Yixi Li, Xiaoyu Xing, Yutong Pei 等 (8 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decoding dynamic visual content from EEG has advanced rapidly for visual perception, yet it remains unclear which aspects of neural representations are preserved when people internally replay dynamic scenes. We introduce PAIR, an EEG benchmark collected from 20 participants using an interleaved, clip-wise paradigm that pairs naturalistic video viewing with immediate visual recall. This design enables a comparison between externally driven perception and internally generated recall for the same stimulus content within a fixed trial sequence. We benchmark multiple decoding models on hierarchical semantic classification at both fine-grained and coarse-grained levels, meta-feature decoding tasks covering motion, color, object number, face, and human presence, and a state-decoding task that discriminates perception from recall. Within-subject validation results show numerically similar performance for several model--task combinations, alongside higher perception accuracy in two coarse-grain

---

### [96] Expert-level detection of low-voltage intervals in EEG as a robust biomarker of neonatal encephalopathy

**链接**: https://arxiv.org/abs/2610.12680
**作者**: John M. O'Toole, Sean R. Mathieson, Aurel Luca, Soraia Ventura, Sean Griffin, Geraldine B. Boylan 等 (7 人)
**来源**: cs.LG eess.SP physics.med-ph
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Discontinuity in neonatal EEG is a critical marker of brain dysfunction but can be difficult to quantify visually. Inter-burst intervals (IBIs) are a key characteristic of discontinuity, yet their definition does not easily translate to AI detection. Objectives: To introduce low-voltage intervals (LVIs), defined exclusively by amplitude and duration, as a context-independent alternative to IBIs, develop an AI detection method for LVIs, and assess their clinical utility as a marker of brain injury. Methods: We developed a ConvNeXt model to detect LVIs and compared its performance with existing methods. We then tested the clinical relevance of detected LVIs across four applications: 1) grading background EEG abnormalities on an open benchmark dataset, 2) classifying clinical hypoxic-ischaemic encephalopathy (HIE) grades and comparing with a normal EEG dataset, 3) seizure prediction, and 4) association with seizure burden. Results: For training and validation, 654 hours of per

---

### [97] Machine Learning and Time-Series Foundation Models for Day-Ahead Electricity Forecasting in a University Building

**链接**: https://arxiv.org/abs/2610.12638
**作者**: Amey Vasulkar, Samuel Kernan Freire, Arie-Willem de Leeuw, Tadeo-Baldiri Salcedo-Rahola
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Day-ahead electricity forecasts can help building operators schedule heating, ventilation, and other services around anticipated demand. Choosing a forecasting model also requires balancing accuracy with its forecast-time inputs, local training, and computational requirements. We benchmark statistical, machine-learning, recurrent neural-network, and pretrained TimesFM models for a university building. We use chronological validation and evaluate all configurations on the same 57 test days, comparing accuracy across workdays, weekends, and holidays alongside local fitting and forecasting time. Weather covariates use retrospective observations. TimesFM 3.0 with covariates achieves the lowest overall errors, reducing mean absolute error by approximately 43\% relative to weekly seasonal-naive forecasting. XGBoost remains competitive, although paired daily comparisons do not establish a clear mean-absolute-error advantage for TimesFM. TimesFM also performs strongly using only past electrici

---

### [98] Mesh-Native Tokenisation: Retrofitting Foundation Models to Unstructured Data

**链接**: https://arxiv.org/abs/2610.12618
**作者**: Georg Maierhofer, Miles Cranmer, Payel Mukhopadhyay
**来源**: cs.CE cs.AI cs.NA math.NA
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physics foundation models are an increasingly popular approach for building versatile emulators for spatiotemporal systems. They require tokenisation layers that lift physical field data into a latent representation suitable for dynamic processing. A typical choice for this layer is a convolutional encoder, which lifts field information in a locality-aware way and can be trained very efficiently. However, this choice cannot be applied to a large class of scientific computing problems where data are represented on unstructured meshes, for example simulations on domains with curved boundaries. Such data typically require graph neural network architectures, which are more expensive to train and, in the form currently used, encode information differently from their CNN counterparts, thus limiting the portability of physics emulators between these data regimes. In this work we introduce Mesh-Native Convolution (MNC), a locality-aware tokenisation layer that encodes unstructured mesh-based d

---

### [99] FactoryNet: A Large-Scale Dataset toward Industrial Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2605.09081
**作者**: Jonas Petersen, Pratik Jawahar, Riccardo Maggioni, Alexandre Huou, Karim Othman, Camilla Mazzoleni 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] On the Encoding of Calendar Features in Covariate-Informed Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.13676
**作者**: Alexander Kreusel, Maximilian Beichter, Alexandra Nikoltchovska, Benjamin Sch\"afer, Ralf Mikut, Frederik Zahn 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) increasingly offer covariate support, with calendar information being the most common type of categorical covariate in practice, as it is available for every point in time. However, how these features are encoded is largely treated as an implementation detail rather than as an object of study, despite encoding being one of the few design choices left for pretrained models at inference time. With the present study, we demonstrate that the way information is propagated into the model substantially affects forecast accuracy of TSFMs. Therefore, we systematically compare seven calendar encodings, including three conventional target-agnostic representations (ordinal, one-hot, and cyclic) and four target encodings, across four state-of-the-art TSFMs on nine datasets from multiple domains in a zero-shot rolling evaluation. The nine datasets are influenced by social activities, such as weekends and holidays, making calendar information particularly relevan

---

### [101] TabReliBench: Evaluating Tabular Foundation Models Beyond Predictive Accuracy

**链接**: https://arxiv.org/abs/2610.13654
**作者**: Tianqi Zhao, Jia Guo, Yan Shuo Tan, Qiong Zhang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are increasingly popular for their strong predictive performance. Many also provide posterior predictive distributions (PPDs), whose reliability remains less studied. We assess reliability through point prediction, distributional quality, marginal and subgroup calibration, and interval efficiency. We then introduce TabReliBench, a large classification and regression benchmark for these comparisons and dataset-level analyses. We find that TFMs' rankings change between TabArena and our benchmark and across reliability metrics. Regression TFMs usually achieve near-nominal marginal coverage and retain narrow intervals, but this favorable marginal behavior does not imply valid conditional coverage. Dataset-level analyses show that classification difficulty often accompanies poor calibration, whereas regression predictive performance is not a reliable indicator of calibration. Ensembling improves predictive performance but does not consistently improve calibr

---

### [102] Zebra3D: Efficient Hybrid Foundation Models For Scalable 3D Reconstruction

**链接**: https://arxiv.org/abs/2610.12727
**作者**: Utkarsh Saxena, Ruijing Yang, Mehdi Rezagholizadeh, Akash Haridas, Vikram Appia, Emad Barsoum
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feed-forward 3D foundation models reconstruct scenes from unposed images, but the quadratic cost of global attention limits their scalability to large view sets. We present Zebra3D, a layerwise sparse-linear hybrid attention framework that improves the efficiency of pretrained 3D foundation models without training from scratch. Across VGGT, HunyuanWorld-Mirror, and $\pi^3$, we observe a broadly consistent depth-wise pattern: early stages are relatively tolerant to linear replacement, while sensitive middle-to-late stages tend to exhibit more concentrated attention. Zebra3D exploits this structure by assigning linear-centered attention to tolerant stages and tile-sparse attention to sensitive stages, using landmark summaries to preserve unselected context. Closed-form affine fitting enables training-free conversion, while optional post-conversion training combines task supervision with output and relational feature distillation. Across all three backbones, Zebra3D achieves strong recons

---

### [103] TabMF: Learning Dataset Representations with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.13818
**作者**: Rafiq Kamel, Nicolas Atienza, Aziz Fouch\'e, Nicola Cancedda, Josif Grabocka
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representations of supervised datasets support higher-level machine-learning tasks such as dataset retrieval and distribution-shift monitoring. However, existing approaches typically rely either on hand-crafted meta-features or on dataset encoders trained specifically for representation learning. We introduce TabMF, a framework that repurposes pretrained tabular foundation models (TFMs) as encoders of supervised datasets. TabMF equips a predictive TFM with an architecture-aware dataset-level readout and adapts the model end-to-end using contrastive post-training on stochastic views of synthetic supervised datasets. We instantiate TabMF on TabICLv2 and TabPFN-2.5 and evaluate the resulting representations across six tasks on unseen real datasets. Simple frozen TFM readouts yield competitive representations, indicating that predictive pretraining already induces substantial dataset-level structure. The two TabMF encoders obtain the strongest aggregate performance among the evaluated lear

---

### [104] PPG-Bench: A Unified Benchmark for PPG Foundation Models

**链接**: https://arxiv.org/abs/2610.13435
**作者**: Arvasu Kulkarni, Mahir Jain, Aditya Ray Mishra, Sandeep Singh, Siddharth Panwar
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Photoplethysmography (PPG) is increasingly recorded by wearable and clinical devices at enormous scale, and a growing number of PPG foundation models (FMs) have been developed to compute reusable representations for various downstream tasks. These models are difficult to compare: different evaluations use different datasets, task definitions, preprocessing, downstream heads, hyperparameter tuning, and baselines. We present PPG-Bench, a unifying open-source benchmark evaluating five public PPG FMs across nine open-access datasets and 26 tasks spanning cardiovascular state estimation, activity, sleep, screening, and identification. We evaluate models under four downstream regimes of increasing adaptability (linear probing, random forests, frozen MLP probes, and end-to-end finetuning), with model-specific hyperparameter optimization and subject-disjoint cross-validation. We also evaluate against three controls: random/constant baseline, a deterministic pulse-rate-variability (PRV) feature

---

### [105] Dataset-Specific Encoding of Image Content Underlies Cross-Dataset Failure in Brain MRI Foundation Models

**链接**: https://arxiv.org/abs/2610.13027
**作者**: Minh Sao Khue Luu and Bair N. Tuchinov
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frozen features of brain MRI foundation models lose accuracy on new datasets, a failure usually blamed on the features encoding where each scan came from. We show that the failure lies elsewhere. Across 17 public datasets and eight frozen representations, every representation recognizes the MRI sequence within each dataset, yet most fail on an unseen one. The cause is neither dataset encoding nor a shift of each dataset: the content itself is encoded along different directions in each dataset. This explains which datasets fail, for the sequence and for sex, and why removing the dataset signal with INLP, LEACE, CORAL or adversarial training never improves sequence transfer. Only the broadly pretrained 3DINO and SAM-Med3D encode the sequence consistently enough to transfer; the brain-specific BrainIAC and BrainFM do no better than an untrained network. Code is available at https://github.com/BrainFM/brainfm-profiler/tree/main/representation_utility.

---

### [106] GIST: Generator-state-Informed Supervision for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.12904
**作者**: Zhangyang Peng, Jingze Shi, Tongyi Zhang, Yuyu Luo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) based on prior-data fitted networks typically use sampled hard query labels, leaving avoidable sampling variability in pretraining. A key observation is that intermediate generator states can reveal label uncertainty beyond a sampled outcome. We propose Generator-state-Informed Supervision for TFMs (GIST), which uses these states to average query losses over conditional label distributions. GIST jointly designs task generation and query supervision, using entropy-calibrated encodings to obtain tractable, input-consistent targets on supported label-dependent branches. We show that this averaging preserves the population objective and yields no larger gradient covariance at fixed parameters within each generating distribution. Under matched pretraining schedules, GIST improves mean rank across three architectures on both TabArena and TALENT without changing architecture or inference. Across these benchmarks and architectures, GIST wins 62.1% of paired dat

---

### [107] Medical foundation models converge less under label supervision

**链接**: https://arxiv.org/abs/2607.20274
**作者**: Soroosh Tayebi Arasteh, Sebastian Ziegelmayer, Mahshad Lotfinia, Lisa Adams, Sven Nebelung, Jakob Nikolas Kather 等 (7 人)
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Benchmarking Attention for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.31306
**作者**: Maximilian Schambach and Clemens Biehl and Sam Thelin
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] Scaling RNA Foundation Models through Iterative Refinement

**链接**: https://arxiv.org/abs/2610.13106
**作者**: Pengan Chen, Liang Hong, Xinyuan Liu, Han Huang, Ziqian Lin, Jiayang Chen 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biological function in RNA is encoded across scales, from local sequence motifs to long-range structural dependencies. Conventional RNA foundation models couple parameter capacity and inference depth within a fixed architecture, prescribing a fixed computation graph for each inference. Here we present Eco-RNA, an 80M-parameter RNA foundation model that makes inference depth adjustable through learned iterative refinement. Its shared, input-conditioned Transformer core refines sequence representations through repeated application. The iteration count is selected after training and controls effective depth at fixed model parameters. We train across recurrent depths with masked reconstruction, state regularization, and a one-sided loss that anchors deeper reconstruction to a shallow reference. On the 70-assay RNAGym fitness benchmark, increasing refinement from one to four iterations raises aggregate absolute Spearman correlation from 0.242 to 0.286, with the gain retained through eight i

---

### [110] How Much Computation Does Every Forecast Need? Structured Block Skipping in Two Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2610.13208
**作者**: Max Bourgeat
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models use the same network depth for every input, although forecasting windows differ in structure and difficulty. We test whether whole Transformer blocks can be removed at inference time in two pretrained models: Chronos-Bolt and TimesFM 2.5. Our bypasses avoid the original block computation and preserve the dense model exactly when all blocks are enabled. Masks are selected only on calibration windows and evaluated on 1,088 held-out windows from ETTh1, Traffic, Weather, and Exchange. At moderate sparsity, Chronos-Bolt with 7/11 candidate blocks and TimesFM with 16/20 blocks show little change in mean relative forecasting quality across datasets while reducing median A100 batch-1 latency by 11.2% and 13.4%. More aggressive TimesFM skipping accelerates inference further but substantially harms Traffic and Weather. Across both models, different equal-budget masks win on different windows, and a retrospective oracle significantly improves over the best static mas

---

### [111] Market Impact Estimation via Causal Foundation Models

**链接**: https://arxiv.org/abs/2610.12537
**作者**: Dennis Thumm and Ying Chen
**来源**: cs.LG cs.CE q-fin.TR
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a trader executes a large order, the relevant question is not \emph{what will the price be?} but \emph{what would the price have been had I not traded?} Market impact is thus a causal quantity, yet classical models (Almgren--Chriss, propagators) regress price on flow, which is biased whenever informed flow moves prices through information as well as trading. We present a proof-of-concept \emph{Causal Market Simulator}: a continuous-time causal prior-data fitted network (PFN) trained on a synthetic market prior in which a hidden informational flow confounds the flow--price relation by construction, with confounding strength an exact per-episode knob. On this prior, the naive estimator's bias follows a closed form we confirm empirically (up to 68\% overestimation), while the PFN tracks the unbiased true-parameter oracle at high confounding. Its \emph{do-ablated twin}, the same model with the intervention inputs removed, collapses onto the pre-window mean. Zero-shot, the model respon

---

### [112] Tabular Foundation Models Are Effectively Shallow

**链接**: https://arxiv.org/abs/2610.13253
**作者**: Irene Cannistraci, Julia E. Vogt
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context-learning Tabular Foundation Models (TFMs) are uniquely suited to scenarios with limited resources or privacy constraints, as they solve new tasks without additional training. However, their architecture consists of multiple transformer blocks, resulting in high computational and memory footprints. Meanwhile, traditional alternatives like Gradient-Boosted Decision Trees (GBDTs) remain highly competitive and run efficiently on CPUs, suggesting that tabular tasks may not inherently require deep architectures. This contrast raises a fundamental question: can TFMs be simplified by removing architectural redundancies without sacrificing performance? To answer this, we introduce a closed-form, label-free affine translator that replaces a contiguous window of up to 96% of the blocks, leaving the rest unchanged. Evaluating eight frontier TFMs on 171 classification datasets, we reveal that tabular transformers are vastly overparameterized: replacing half of a model's blocks costs at m

---

### [113] Learning Features, Not Layouts: Feature-Axis Attention as a Transfer Prior for Medical Imaging

**链接**: https://arxiv.org/abs/2610.13012
**作者**: Aon Safdar, Mohamed Saadeldin
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-image-pretrained foundation models are increasingly adapted to medical imaging, yet transfer remains unreliable under domain shift, modality heterogeneity, and label scarcity. We trace part of this fragility to an overlooked design choice. Standard vision transformers place all global modeling on self-attention over spatial tokens, an object-layout prior well suited to natural scenes but not to medical images, where the discriminative signal lies in feature correlations and texture that recur across scanners while layout does not. We ask whether the axis of global attention, spatial versus feature, is itself a lever for transferable medical representations. Existing channel-aware hybrids confound this question, adding channel attention to a spatially-mixed backbone and leaving the axes coupled and the feature axis unmeasurable in isolation. We design FAD-ViT, a backbone that strictly decouples the two axes, making feature-axis attention the primary global operator and the atten

---

### [114] Domain Adaptation of SAM 2.1 for Building-Component Segmentation in Image-Based 3D Reconstruction

**链接**: https://arxiv.org/abs/2610.12786
**作者**: Ehsan Agha Ebrahimi, Yong-Cheol Lee, Keith G. Mills
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D reconstruction of building components using image-based scanning requires appropriate segmentation of the objects in the 2D building images. In order to benefit from consistent grouping of the 2D masks in 3D environments, vision foundation models such as the Segment Anything Model have been utilized by Group Anything with Radiance Fields (GARField) to perform 3D segmentation. This study fine-tuned SAM 2.1 on the HBD dataset, consisting of 2,679 annotated images from 42 buildings, to enhance multi-class segmentation of 2D building images, covering 11 classes (Wall, Window, Ceiling, Door, Column, Beam, Floor, Opening, Curtain Wall, Roof, and Lift). The model was evaluated using per-class IoU, Dice, and mIoU metrics, and the results show an improvement in mIoU from 49.9% to 69.6%, indicating a meaningful improvement in class segmentation and providing a more accurate model for distilling the masks in 3D. SegFormer was then used as a baseline, generating per-class masks for comparison w

---

### [115] Shortcut Learning in Geospatial Foundation Model Embeddings for Cross-Disaster Damage Assessment

**链接**: https://arxiv.org/abs/2610.13766
**作者**: Ali Shibli, Andrea Nascetti, Yifang Ban
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models can support disaster damage assessment, but high accuracy on familiar disasters may hide shortcut learning: prediction from event or scene characteristics rather than evidence that transfers to a new disaster. We study embeddings from TerraMind, Prithvi-EO-2.0, DOFA, and DINOv3 on the multi-disaster datasets xView2 and BRIGHT. Holding out an entire disaster, instead of randomly splitting image tiles, reduces mean balanced accuracy from 0.807 to 0.638 on xView2 and from 0.818 to 0.568 on BRIGHT. Four sets of tests examine what information supports prediction: event and acquisition context, before/after image inputs, building count, and correct image pairing. Pre-event images remain predictive, and a classifier given only the annotated number of buildings reaches balanced accuracy of 0.629 and 0.653. Combining before/after features performs best on average on xView2, but does not improve over pre-only features on BRIGHT. Shuffling image pairs within the same 

---

### [116] HART: Hybrid Attention-RWKV Time series Foundation Model

**链接**: https://arxiv.org/abs/2610.12883
**作者**: Qingwen Lin, Boyan Xu, Shifeng Xie, Zhifeng Hao, Keli Zhang, Ruichu Cai
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Non-autoregressive multi-step forecasting (NAF) enables time series foundation models to predict an entire future horizon in a single forward pass. Despite its strong sequence modeling capabilities, RWKV-7 exhibits long-horizon degradation in our NAF experiments. In this setup, future patches are represented as missing inputs, requiring the recurrent state to evolve across the prediction horizon without new observations. Our analysis of RWKV-7's generalized delta rule suggests a mechanism we term Placeholder Idling Decay (PID): repeated state transitions can attenuate historical information when placeholder-driven writes provide insufficient compensation. Layer-wise analysis reveals reduced state-injection norms in most layers, while transition-matrix norms remain similar between historical and prediction regions, consistent with PID. Motivated by this analysis, we propose HART, a Hybrid Attention-RWKV Time-series Foundation Model that alternates attention and RWKV blocks, combining di

---

### [117] GlucoPRISM: Protocol-Supervised Pretraining for Cross-Cohort Glucose Transfer

**链接**: https://arxiv.org/abs/2610.12528
**作者**: Adinath Madhavrao Dukre, Abdullah Mohammad, Yifan Lu, Eran Segal, Ahmed Metwally, Imran Razzak
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continuous glucose monitoring (CGM) foundation models encode each day as one vector that mixes who the person is, what happened that day and how the sensor measured it, so measurement differences travel with the representation into new cohorts. We ask whether pretraining can place the measurement component that harms transfer in known coordinates, so that deployment drops them with a fixed projection and no target data. GlucoPRISM supervises a GlucoFM backbone with response contracts, rules for how each part of the representation should change when only the day or only the sensor changes: a 64-dimensional Trait band should change with neither, a 48-dimensional State band only across days, and a 16-dimensional Sensor band should track the device. Synthetic sensor views calibrated on paired Dexcom and Libre recordings, different-day pairs and glucose-summary targets supply this supervision without clinical labels. Across twelve cross-cohort directions, dropping the Sensor band from the s

---

### [118] Scaling Multi-Teacher Distillation for Digital Pathology

**链接**: https://arxiv.org/abs/2610.12574
**作者**: Sofi\`ene Boutaj, Pierre Marza, Varun Belagali, Dimitris Samaras, Maria Vakalopoulou, Stergios Christodoulidis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-teacher distillation allows transferring knowledge from multiple "teacher" networks to a single "student" network. This method is promising in fields such as digital pathology, where many powerful foundation models were proposed recently. However, as we show in this paper, the standard multi-teacher distillation approach reacts poorly to an increase in the number of teachers used to train a student encoder. We demonstrate that learning teacher-specific representations is a key to scaling in MTD. Importantly, different design choices, such as learnable teacher tokens, a tailored attention scheme, additional mixture-of-experts layers and a contrastive loss, are proposed to better learn such teacher-specific representations. We show that our method better scales with respect to the number of considered teachers, allowing us to train compact student encoders, up to 10x more efficient than larger teacher foundation models, while matching their performance and even outperforming them o

---

### [119] A4-MR: Abnormality-aware Anatomical Alignment for MR

**链接**: https://arxiv.org/abs/2610.13056
**作者**: Noel D'souza, Zhijian Yang, Nishank Singla, Pranay Doshi, Krisztian Koos, Fei Tan 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large-scale foundation models have enabled strong generalization across a wide range of clinical and research tasks in magnetic resonance imaging (MRI). However, existing vision-language MRI models remain limited in anatomy-specific localization and pathology-aware representation, particularly in real-world settings. We introduce A4-MR, a 3D vision-language foundation model trained on approximately 50,000 MRI studies comprising 491,000 series, roughly half of which are paired with radiology reports. A4-MR is designed to: (1) learn anatomy localization through large-scale pretraining with noisy labels; (2) align image and text representations at the anatomical level; and (3) learn distinct representations of healthy and abnormal anatomy. Across a diverse set of downstream tasks, A4-MR outperforms existing foundation models, including a +1.7 AUROC improvement over MedSigLIP for abnormality detection. Using a frozen encoder, A4-MR also surpasses an end-to-end task-speci

---

### [120] PlacePulse: Learning Transferable Place Representations from Structural Geographic Data

**链接**: https://arxiv.org/abs/2610.13390
**作者**: Luc\'ia Garc\'ia-Duarte, Miguel \'Alvarez, Diego Vicente, Javier P\'erez Trufero, Javier de la Torre
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial machine learning often depends on task-specific feature engineering over large collections of sociodemographic, business, and environmental variables. Geospatial foundation models offer reusable representations of place, but leading approaches typically encode dynamic signals, such as mobility and search activity, or visual signals from satellite imagery. Few models represent the static structural composition of places (who lives and works there, which businesses operate there, and which risks they face) as transferable embeddings at fine spatial resolution. We introduce PlacePulse, a structural geospatial foundation model that compresses 572 attributes, expanded to 2,288 inputs through H3 neighborhood aggregates, into 256-dimensional unit-norm embeddings for 1,055,537 H3 resolution-7 cells in the United States. We also introduce a reusable two-axis benchmark that separates intrinsic representation quality from downstream predictive utility across multiple targets and spatia

---

### [121] Diffusion Precipitation Generation with Medium-range Weather Forecasting

**链接**: https://arxiv.org/abs/2610.12976
**作者**: Guowen Li, Yang Liu, Mengxuan Chen, Jiashun Cheng, Haoyuan Liang, Shilei Cao 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate daily precipitation forecasts are important for weather-sensitive decisions. Although recent Weather Foundation Models (WFMs) have achieved significant progress, they are trained on reanalysis data, which exhibit regional and intensity-dependent biases. Since retraining WFMs on observation-based targets is costly, we study Dynamics-Precipitation Decoupling, a plug-and-play framework that uses a separately trained generator to map non-precipitation forecasts from a frozen weather model to observation-aligned daily precipitation. Its key challenges are to capture heterogeneous rainfall distributions and align daily accumulations with atmospheric signals that evolve across space and time. To address them, we train a diffusion generator conditional on atmospheric states and satellite-gauge estimates of precipitation. A multi-scale recurrent encoder summarizes atmospheric evolution, while cross-attention aligns atmospheric and precipitation features during denoising. Extensive eval

---
