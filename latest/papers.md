# 📑 论文索引 - 2026-10-01

共 275 篇论文

---

### [1] Imagine3D-LLM: Teaching MLLMs to Imagine 3D Scenes Before Answering

**链接**: https://arxiv.org/abs/2609.38177
**作者**: Jaewoo Jung, Hyeonseo Yu, Honggyu An, Jisang Han, Mungyeom Kim, Minkyeong Jeon 等 (10 人)
**来源**: cs.CV cs.CL
**匹配关键词**: Foundation Models, LLM, MLLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning about the 3D world from multi-view images remains a fundamental challenge for Multimodal Large Language Models (MLLMs). While modern MLLMs handle single-image inputs effectively, they struggle to integrate evidence across viewpoints into a coherent 3D understanding. A growing body of work attempts to close this gap by injecting 3D awareness into MLLMs, either by boosting fine-grained pixel-level cross-view correspondence or by fusing features from 3D geometry foundation models, yet a substantial gap to human reasoning persists. In this work, we revisit human spatial reasoning, which suggests that rather than relying on fine-grained geometry cues, humans roughly identify common objects across views, infer the relative geometry between viewpoints, and assemble a coarse 3D layout of the scene. Inspired by this process, we introduce Imagine3D-LLM, an MLLM that learns to assemble a similar compact 3D representation of the scene and conditions its answer on this representation. Con

---

### [2] Learn Now, Use Next, Trust Later: Prequential Test-Time Learning for LLM Agents

**链接**: https://arxiv.org/abs/2609.35911
**作者**: Tong Zhao, Reed Li, Yuyang Hu, Yutao Zhu, Haijin Liang, Haibo Shi 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting large language model agents during deployment requires not only retaining past experience, but also turning new observations into timely guidance. Many test-time learning methods, however, acquire knowledge from completed episodes. Feedback from an ongoing interaction may therefore not be distilled into knowledge soon enough to help the next decision. Acquiring knowledge at the granularity of individual transitions could reduce this delay, but raises a separate challenge: a rule that is useful within one episode may not be reliable enough to guide future episodes. Waiting for validation can forfeit immediate benefits, whereas unrestricted reuse can propagate accidental or misattributed guidance. We introduce StepLearn, a nonparametric framework that separates immediate use from persistent trust. It turns informative transitions into hypotheses that can guide the next step, while requiring prospective validation before reuse across episodes. Their predicted effects are checked 

---

### [3] Where Does Staleness Accumulate? Pool Aware Effective Staleness Control for Asynchronous RL in LLM Post-Training

**链接**: https://arxiv.org/abs/2609.36830
**作者**: Chenliang Li, Neiwen Ling, Zijun Wei, Alfredo Garcia
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fully asynchronous reinforcement learning (RL) improves resource utilization in large language model post-training by overlapping rollout generation with policy optimization, but it also introduces policy lag as trajectories are generated and queued while the trainer continues to update. We study how this lag accumulates over a trajectory's lifetime and how it can be controlled without sacrificing the wall-clock benefits of asynchronous execution. We decompose trajectory staleness into Generation Staleness, accumulated before rollout completion, and Waiting Staleness, accumulated after a completed trajectory enters the pool. Motivated by this decomposition, we introduce PACE (Pool-Aware Control of Effective Staleness). PACE converts excess pool occupancy into an adaptive rejection budget and ranks completed trajectories using an effective-staleness score that combines Waiting Staleness with prefix-aware Generation Staleness. This avoids penalizing long or interrupted rollouts solely be

---

### [4] Risk-Controlled Selective LLM Answering by Pricing Label-Free Checks

**链接**: https://arxiv.org/abs/2609.37493
**作者**: Dongyub Jude Lee, Jungseob Lee, Chanjun Park, Hyeonseok Moon, Heuiseok Lim
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving an answer from a large language model requires deciding when to abstain, yet a verifier's ranking accuracy alone does not determine the error rate among served answers. We introduce PriceCheck, which builds a compact family of decision rules from label-free checks such as re-solving a problem. Each check has a price: its agreement rates on correct and incorrect answers and its cost per run. Prices fitted on a small, class-enriched labelled set compose into predictions of a schedule's coverage and cost, guiding which checks to run and when to stop. A calibration test then selects a schedule at a stated selective-risk target. In mathematics, the selected schedules serve 76.1% of answers on average and keep held-out selective risk below 1.5% on all 15 splits. Under the shared testing protocol, PriceCheck serves more answers at that target than reward models, a prompted judge, the generator's confidence and a trained correctness classifier. At matched coverage, it keeps the fewest 

---

### [5] Engineering Simplicity: Simple Mechanism Interfaces Steer LLM Agents

**链接**: https://arxiv.org/abs/2609.36365
**作者**: Kehang Zhu, Anand Shah and David Parkes
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can interaction formats and textual scaffolds help large language model (LLM) agents make better decisions, and do better decisions come with better explanations? We study these questions in auctions and matching, multi-agent environments with explicit rules and known optimal strategies. These settings let us vary how a decision problem is presented while retaining a benchmark for evaluating behavior. Drawing on human-motivated theories of simplicity, we compare interfaces that elicit a complete bid or ranking with sequential interfaces that make safe choices easier to identify. We then hold the interaction format fixed and vary reasoning scaffolds and rule descriptions. Across four model families, the ascending auction interface substantially reduces bid deviations. The matching comparison also shows why sequential responses require different error accounting from complete rankings. Laying out payoff contingencies and explaining why truth-telling is safe also improve choices, whereas 

---

### [6] Pretrain Once, Route Anywhere: Towards a Foundation Model for LLM Routing

**链接**: https://arxiv.org/abs/2609.37362
**作者**: Guannan Lai and Han-Jia Ye
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) routing aims to assign each query to the most suitable model from a heterogeneous candidate pool, improving the quality--efficiency trade-off of LLM inference. Existing routers are typically learned through local fitting: a router is optimized for a particular query workload and candidate pool, and often requires additional supervision or retraining as the routing environment changes. We ask whether LLM routing can instead be approached from a foundation-model perspective, learning a reusable routing capability that generalizes across tasks, candidate models, and deployment conditions. To this end, we introduce RouteFM, which learns to characterize anonymous candidate models from behavioral context and infer their target-specific capabilities, rather than binding routing decisions to fixed model identities or a single environment. Through episodic pretraining across heterogeneous routing environments, this capability can be reused by a frozen router and adapt

---

### [7] BiFE: Search-Efficient Discovery of CPU-Only Branching Policies via LLM-based Bi-Fidelity Evolution

**链接**: https://arxiv.org/abs/2609.36735
**作者**: Ce Zhang, Bin Zhang, Zhiwei Xu, Hao Chen, Xinyue Lu, Shanwei Fan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In branch-and-bound (B&B) for mixed-integer linear programming (MILP), branching variable selection critically impacts efficiency. Existing neural branching policies often require GPU inference, while CPU-efficient symbolic expressions lack the representational capacity for complex logic. Large Language Model (LLM)-generated code provides a flexible search space for designing lightweight branching rules with diverse algorithmic logic. To discover effective rules within LLM-based evolutionary frameworks, a core challenge arises: full B&B evaluation on real instances is prohibitively expensive, whereas offline imitation learning suffers from distribution shift. To address this, we introduce a Bi-Fidelity Evolutionary framework (BiFE). It employs low-fidelity imitation scores as a rapid pre-screener and selectively applies high-fidelity on-instance evaluation only to elite candidates, effectively balancing search efficiency with performance reliability. Experiments validate both the searc

---

### [8] Backdoor Mitigation in Decentralized LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.37367
**作者**: Sayan Biswas, Jade Garcia Bourr\'ee, Rachid Guerraoui, Maxime Jacovella, Anne-Marie Kermarrec, Sathwika Peechara 等 (8 人)
**来源**: cs.CR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decentralized large language model (LLM) fine-tuning lets organizations collaboratively train a shared LLM on data they cannot pool, without a central coordinator. In every round, each node exchanges a trainable adapter with its neighbors over a communication graph, and then aggregates them. This setting, however, is vulnerable to propagated backdoors, which is a hidden behavior that lets a model perform normally on clean inputs but produce an attacker-chosen output whenever a secret trigger appears. We show that a single node poisoning its own model can backdoor adapters of nodes that have never seen a poisoned example, making them refuse prompts that contain a secret trigger. We present Chorus, a decentralized mechanism that lets each node detect and reject backdoored adapters from its neighbors before aggregation, without requiring shared validation data or any knowledge of the attacker's trigger or target. Chorus judges each adapter by its behavior, using the receiver's own adapter

---

### [9] Routing Should Pay for Itself: Sparse Supervision for Economical LLM Routing

**链接**: https://arxiv.org/abs/2609.37402
**作者**: Guannan Lai, Gelin Bian, Hao-Xuan Ma, Jun-Peng Jiang, Long Chen, Jian-Dong Liu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) routing reduces serving cost by assigning each query to an appropriate model while preserving response quality. Learning such a router, however, often requires executing multiple candidate models on historical queries to collect query--model quality feedback, creating a nontrivial supervision cost before deployment. Existing work largely focuses on serving-time efficiency, overlooking whether the resulting savings are sufficient to recover this upfront expenditure. We further observe that routing quality often saturates well before all query--model feedback is collected, suggesting that dense supervision can be economically over-provisioned. We propose SaveRouter, a sparse-supervision routing framework that selectively acquires informative model feedback and shares capability information across related queries, while retaining query-level refinement for fine-grained routing. We evaluate routing by jointly accounting for supervision expenditure and subsequent 

---

### [10] Storage Is Not Strategy: State-Conditioned Support Control for LLM Unlearning

**链接**: https://arxiv.org/abs/2609.37858
**作者**: Tianhao Qian, Ziming Hong, Chongyang Gao, Kezhen Chen, Lixu Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many localized large language model (LLM) unlearning methods select a small parameter subset from a localization signal and keep it fixed during optimization. The parameters most associated with a target, however, need not be the best ones to update, and candidate interventions can change value as optimization proceeds. In a controlled experiment, a storage-localization score reaches an area under the receiver operating characteristic curve (AUROC) of 0.981, yet storage identity agrees with the better intervention on only 17/36 targets, while low-rank adaptation (LoRA) wins 35/36. We introduce Intervention Score, which ranks editable groups by the predicted effect of the actual unlearning update while accounting for collateral damage, and use it to form the static intervention-value baseline (Static-IV). We then introduce selective dynamic intervention re-ranking (DIR-R), which revisits that subset only when a calibrated probe justifies the comparison. On the Natural-TOFU dataset, our 

---

### [11] A Proposed Rubric for Evaluating Expressed Clinical Reasoning in Large Language Model Responses

**链接**: https://arxiv.org/abs/2609.37788
**作者**: Zhangshu Joshua Jiang, Zina Ibrahim, James T. Teo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubrics support the structured evaluation of language models. We propose a rubric for assessing expressed clinical reasoning in model responses, drawing on three bodies of work: medical education assessment frameworks (ART, SCT, Key Feature Problems and OSCE); clinical LLM benchmarks (MedR-Bench, HealthBench, TIMER-Bench, DR.BENCH, PrIME-LLM and PatientSafeBench); and general LLM reasoning evaluation research, including the Factuality-Validity-Coherence-Utility taxonomy, FaithCoT-Bench and C2-Faith. We use groundedness as a clinically oriented adaptation of the taxonomy's factuality category. The rubric brings these concepts together in a multidimensional framework for scoring free-text responses to gold-standard clinical vignettes. It includes provisional behavioural anchors, applicability rules and a separate flag for case-specific safety-critical errors. General-domain frameworks inform its design but are not treated as validated clinical instruments. The rubric does not replace cas

---

### [12] Pair Difficulty Matters: Rethinking Pairwise LLM-as-a-Judge Evaluation and Consistency

**链接**: https://arxiv.org/abs/2609.37577
**作者**: Bruno Brocai and Maria Becker
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model judges are widely used to rank texts and text-generating systems through pairwise comparison, and their reliability is typically assessed via three proxies: position bias, transitivity, and pairwise agreement (self- or human-labeled). Because these proxies drive judge selection and benchmarking, a substantial literature reporting that judges perform poorly on them risks steering practitioners away from otherwise capable evaluators. We argue this assessment is misleading. Under the Bradley--Terry geometry underlying pairwise aggregation, each proxy is dominated by close-rank-gap pairs, where inconsistency is information-theoretically expected and individual verdicts contribute little to the aggregate ranking; far-gap pairs carry the ranking signal but barely move the proxies. We formalize this argument and validate it in a controlled simulation and on two human-rated corpora: the proxies correlate only weakly with ranking accuracy against gold, and their predictive 

---

### [13] SafeLLM4SE: Statistical Evaluation and Reporting for LLM-based Software Engineering Systems

**链接**: https://arxiv.org/abs/2609.37294
**作者**: Francisco Ortin
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for software engineering tasks, yet their stochastic behavior challenges the validity, reproducibility, and comparability of their evaluations. Conventional practices such as reporting a single output, an average score, best-of-N, or pass@k performance can obscure variability and estimation uncertainty, potentially leading to misleading conclusions about system reliability. This article presents SafeLLM4SE, a practical methodology and reporting standard for statistically principled evaluation of LLM-based software engineering systems. Rather than treating generated outputs as deterministic artifacts, SafeLLM4SE treats them as realizations of a stochastic process and distinguishes quality, stability, and estimation uncertainty. It combines adaptive sampling with confidence intervals, distribution-aware statistical comparisons, effect sizes, and a minimum reporting standard covering model configuration, reproducibility, evaluation proced

---

### [14] FOCUS: Training-Free Decision-Preserving Context Compression for LLM Agents

**链接**: https://arxiv.org/abs/2609.37590
**作者**: Shantanu Dixit, Anson Bastos, Xuchao Zhang, Chetan Bansal, Saravan Rajmohan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents accumulate interaction histories that grow linearly with task length, causing quadratic inference cost scaling and performance degradation from attention dilution. Existing context-compression methods learn what to discard offline: by contrastively optimizing guidelines, distilling compressors, or training compression policies. This incurs a substantial cost. Further, the compression policy is learned a priori and is not dynamically conditioned on the evolving test-time trajectories. In this paper we ask a complementary question: Which past interactions causally shape the agent's future decisions? We recast context compression as a causal decision preservation problem over discrete interaction units and introduce FOCUS, a training-free context compression framework that operates entirely at test time. Our method requires no offline data collection or fine-tuning, and is architecture-agnostic, attaching to any closed-API frontier model as a modular compression layer. We evalu

---

### [15] RAISE: Diagnosing Acquisition Collapse in Costly LLM Signals

**链接**: https://arxiv.org/abs/2608.10441
**作者**: Ying Yuan, Yu Wang, Yize Cheng, Xuyang Wu
**来源**: cs.LG cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Look What You Made Us Cluster: Hate Narrative Extraction from Reddit Discourse

**链接**: https://arxiv.org/abs/2609.37408
**作者**: Annabelle K. L. Chua, Forster J. Khoo, Joel C. R. Tan, Huey Ting Ang, Kheng Hwee Tan, Joel Y. A. Sim 等 (10 人)
**来源**: cs.CL cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Narrative extraction allows us to identify online hate narratives, supporting the construction of rigorous detection systems. Existing computational approaches, however, are limited in precision as they rely on semantic representations, which tend to capture only surface-level meaning. To detect more precise and interpretable narratives, we present an extraction pipeline that represents narratives as entity-evaluation pairs. Narratives are extracted using a Large Language Model (LLM) reasoning process that extends Aspect-Based Sentiment Analysis, identifying the aspect, classifying its judgement type as the basis for evaluation, and deriving the evaluation accordingly. Extracted narratives are then clustered using Leiden, following which clusters are resolved to an intended level of granularity through an LLM-guided refinement process. We illustrate this narrative pipeline with English Reddit comments from 2024 that criticize Taylor Swift, analyzing a representative cluster that exhibi

---

### [17] ToolFence: Fine-Grained Authorization for Secure Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2609.37196
**作者**: Yanjie Li and Xiangyu He and Xuelong Dai and Bin Xiao
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents remain vulnerable to indirect prompt injection because trusted instructions and untrusted observations share one context, allowing malicious content to steer consequential input-filtering defenses. Multi-path consensus defenses still leave a high attack success rate because they examine content or aggregated outputs rather than authorizing effects, especially for the within-tool attack, which preserves the intended tool but manipulates its arguments. Data-Flow Control such as CaMeL provides stronger guarantees, but incurs substantial time latency that limits practical deployment. We introduce ToolFence, which compiles a typed authorization blueprint before execution, enforces it through a deterministic monitor, and when the blueprint is incomplete asks a judge to grant new capabilities rather than adjudicate each concrete call. ToolFence provides two key advantages. First, its fine-grained provenance-aware authorization enables the system to distinguish user-autho

---

### [18] JudgeProfile: Understanding and Steering Subjectivity in LLM Judges

**链接**: https://arxiv.org/abs/2609.36705
**作者**: Qi Cao, Kangning Liu, Xuan Kan, Shunwen Tan, Yang Pei, Dake Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges are inherently subjective, often favoring different responses in pairwise comparison when neither option is objectively wrong. To study this subjectivity, we introduce JudgeProfile, a framework that dissects LLM evaluation into perception (how a judge compares two responses across specific attributes like clarity, correctness, and detail) and prioritization (how much each attribute influences the final choice). We curate SubjectiveSet, a dataset of 50,013 response pairs from 17 public data sources, evaluated by 21 LLM judges across 87 attributes. We find a hidden consensus in perception: judges frequently agree on attribute judgments even when their overall choices diverge. Building on this separation, we first characterize each judge's prioritization using attribute weights estimated from its own overall choices. These weights differ across judges even when estimated from the same attribute judgments. We then learn new weights from reference labels to adapt their decisions 

---

### [19] Risk-Aware Semantic Grounding for Trustworthy LLM-Based Robot Planning

**链接**: https://arxiv.org/abs/2609.37554
**作者**: {\L}ukasz Sobczak, Nur Kele\c{s}o\u{g}lu and S{\l}awomir Piotr Nowak
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as high-level planners in robot navigation, but their outputs may become unreliable when instructions are ambiguous, unsupported by the environment, or semantically inconsistent. This paper presents a Risk-Aware Semantic Grounding framework for trustworthy LLM-based robot planning. Unlike existing LLM-based planners that primarily optimize plan generation, we formulate semantic grounding reliability as a multi-dimensional risk estimation problem. The proposed architecture explicitly models grounding uncertainty through ambiguity, hallucination and semantic-conflict risks before planning occurs, enabling the system to decide whether to execute the instruction, request clarification, or reject it. To evaluate the approach, we introduce TRUST-NAV, a benchmark containing both standard navigation tasks and risk-inducing instruction scenarios. Experimental results show that while conventional LLM planners achieve strong performance on valid 

---

### [20] Unlocking the Critic: Reward-Free Policy Optimization for LLM Post-Training

**链接**: https://arxiv.org/abs/2609.37119
**作者**: Hongyang Li, Xiao Li, Caesar Wu, Said Mammar, Gr\'egoire Danoy, Pascal Bouvry
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent approaches to reinforcement learning (RL) post-training for large language models increasingly remove the critic to reduce training instability and memory overhead. Even where a critic is trained, it is discarded once training ends, although it has learned to predict outcomes. We revisit this trend and show that a pretrained critic's ability to predict future outcomes can make it a valuable asset for efficient long-horizon reasoning. First, we find that instability in critic-based RL for long chain-of-thought reasoning is largely an optimization artifact: keeping policy updates small and low in variance restores stable convergence. Second, a well-pretrained critic estimates the posterior probability of eventual success from later trajectory states and unfinished prefixes. Its predictions provide outcome-derived, dense, per-prefix learning signals that, during policy optimization, require neither completed rollouts, step-level annotations, nor external reward labels. Building on 

---

### [21] Do LLM Agents Execute the Plans They Declare? From Planning-Mode Declaration to Pattern-Specific Execution

**链接**: https://arxiv.org/abs/2609.38108
**作者**: Subba Reddy Oota, Francisco Herrera, Jordi Cabot Sagrera, Marcos L\'opez de Prado, Shadab Khan
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) enable agents to solve long-horizon tasks by generating a plan and then executing it in an environment. However, successful planning requires two distinct capabilities: selecting an appropriate plan for the task and executing it faithfully. Existing planner--executor systems can fail at either stage, while final task success alone cannot distinguish selection from execution failures. We therefore study the Plan Declaration--Execution Gap and introduce Planning-as-Routing, where an LLM declares one of four planning modes: Predefined, Sequential, Hierarchical, or Search, and a deterministic router dispatches the task to the corresponding pattern-specific executor. Across four benchmarks and three LLMs, we find three consistent patterns. First, generic Plan+ReAct often fails to preserve declared planning structure, especially for longer plans: across three benchmarks, only (22)--(45%) of trajectories preserve it, whereas pattern-specific executors enforce the 

---

### [22] XBridge: Entity-Grounded Latent Bridge for Heterogeneous LLM Communication

**链接**: https://arxiv.org/abs/2608.11676
**作者**: Wooseong Yang, Wei-Chieh Huang, Weizhi Zhang, Yu Wang, Philip S. Yu, Junhyun Lee
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Koa-action: Fast and Consistent Structured Decision Making with Generative LLMs

**链接**: https://arxiv.org/abs/2609.36115
**作者**: Shenghong Dai, Shiva Kumar Pentyala, Yingchi Liu, Shubham Mehrotra, Suman Banerjee, James Zhu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industry applications often demand low-latency classification, yet current large language model (LLM) approaches remain poorly suited for latency-critical applications. Existing prompting and constrained decoding produce verbose, multi-token outputs that require expensive token-by-token generation, while encoder-based models achieve faster inference but sacrifice task flexibility. We propose Koa-action, a framework for low-latency atomic actions -- fast, single-step decisions such as classification, semantic endpointing, Boolean checks, and scoring -- formulated as constrained generation with single-token outputs. By introducing atomic label tokens and applying supervised fine-tuning, our method reduces classification to a deterministic one-step decoding problem. Across standard benchmarks, Koa-action delivers competitive accuracy with consistently low and stable latency. On a production intent-routing benchmark, Koa-action reaches 85.5% accuracy -- competitive with the strongest front

---

### [24] MERGE: Multi-LLM Ensemble for Retrieval via Generative Enrichment

**链接**: https://arxiv.org/abs/2609.37574
**作者**: Tzu-I Ho, Yung-Yu Shih, Shang-Yu Su, Dongzhe Wang, Yun-Nung Chen
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used to enrich user queries in information retrieval (IR) so that a standard retriever such as BM25 can bridge vocabulary gaps with the target corpus. Any single LLM, however, is limited by its training data and architectural biases, and its enrichment behavior depends on hand-crafted prompts that must be re-engineered for each new model -- an expensive and poorly scalable process. We present MERGE (Multi-LLM Ensemble for Retrieval via Generative Enrichment), a two-stage framework: three heterogeneous 7-8B open-source LLMs independently produce candidate expansions, and a larger LLM generatively synthesizes them into a single query. To make prompt engineering scalable across the ensemble, we integrate a task-grounded Automatic Prompt Optimization (APO) loop into both stages. Unlike APO methods that judge candidates with an LLM evaluator, our loop scores each candidate by its downstream retrieval performance and runs a small tournament betwe

---

### [25] Relative Kinetic Utility: Calibrating Cross-Layer Credit for Global Structured LLM Pruning

**链接**: https://arxiv.org/abs/2605.09008
**作者**: Tianhao Qian, Guilin Qi, Jiayu Chen
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] TwinRouterBench: Fast Static and Live Dynamic Evaluation for Realistic Agentic LLM Routing

**链接**: https://arxiv.org/abs/2605.18859
**作者**: Pei Yang, Wanyi Chen, Tongyun Yang, Pengbin Feng, Jiarong Xing, Wentao Guo 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Which Attention Heads are like the Human Head? Not the Ones that Compute

**链接**: https://arxiv.org/abs/2609.37991
**作者**: Christopher Pinier, Gustaw Opie{\l}ka, Hannes Rosenbusch, Taylor Webb, Michael D. Nunez, Claire E. Stevenson
**来源**: cs.AI q-bio.NC
**匹配关键词**: EEG, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain-AI alignment is often interpreted as a sign that model and brain perform similar computations. Whether the aligned units are causally involved in model computation is rarely checked. On an abstract pattern-completion task (AAABAAA $\rightarrow$ B), we compare LLM attention-head representations with human EEG and test how ablating those heads affects task performance. Alignment and causation dissociate: brain-aligned heads contribute to performance, but their removal is substantially less disruptive than removal of heads selected via attribution patching. We compare two head sets that prior interpretability work defines without reference to the brain: concept vectors (CVs), which represent abstract patterns across formats, and function vectors (FVs), selected for their contribution to correct-answer prediction. Brain alignment shows little association with FV scores, while its association with CV scores varies across models. Among brain-aligned heads, we find recurring attention p

---

### [28] Beyond Rule-Based Mutation Testing: Test-Aware Mutant Generation Using Large Language Models

**链接**: https://arxiv.org/abs/2609.35841
**作者**: Nils Kiele, Zainab Saad, Zirui Wang, Steve Drew, Samira Ebrahimi Kahou
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mutation testing evaluates test-suite adequacy by injecting synthetic faults into program code. However, traditional rule-based tools often generate large numbers of trivial, redundant, or equivalent mutants that limit their practical use for identifying gaps in a test suite. While recent large language model (LLM)-based approaches generate more realistic faults, most remain test-blind: The model sees only the source code and cannot reason about what existing tests already cover. We propose test-aware mutant generation, in which an LLM receives the problem statement, canonical solution and base tests in a single prompt, and must generate a nontrivial mutant that passes the base unit tests. We evaluate this approach across a set of five LLMs -- Gemini 3.1 Pro, Gemini 3 Flash, GPT 5.1 Codex Mini, GPT 4.1 Mini, Qwen3-32B -- on the HumanEval and MBPP benchmarks. The extended EvalPlus test suites serve as an automated oracle to verify whether surviving mutants represent genuine bugs. Test-a

---

### [29] Local Predictability and Collective Fidelity in LLM-Agent Societies

**链接**: https://arxiv.org/abs/2609.35813
**作者**: Igor Itkin
**来源**: physics.soc-ph cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] SafeCoEvo: Co-Evolving Safety Harnesses and Guards for LLM Agents at Test-Time

**链接**: https://arxiv.org/abs/2609.36580
**作者**: Yu Cheng, Yongkang Hu, Shuaijie Ma, Zhihang Lin, Weicheng Meng, Jingyang Qiao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents deployed in real-world environments continually encounter new tasks and safety risks, while execution feedback typically becomes available only after each task is completed. However, existing self-evolving approaches commonly rely on multiple rounds of optimization over fixed and repeatedly accessible task distributions, fundamentally differing from test-time adaptation in real-world deployment, where only experience accumulated from past tasks can be used to improve safety decisions on future unseen tasks. To address this limitation, we propose SafeCoEvo, a test-time Harness-Guard co-evolution framework for LLM agent safety that enables the external safety system to continually adapt from accumulated runtime experience. SafeCoEvo jointly improves two complementary safety capabilities at different timescales: S-Harness rapidly externalizes recent runtime experience into updatable explicit safety knowledge that can promptly influence subsequent tasks, while GuardVPO internali

---

### [31] Better Nearest Neighbor Graph Indices via (Efficient) LLM-Guided Pruning

**链接**: https://arxiv.org/abs/2609.36359
**作者**: Fangzhou Wu, Haike Xu, Sandeep Silwal
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph-based approximate nearest neighbor search (ANNS) is widely used for large-scale semantic search. Its indices are constructed primarily based on geometric relationships among embeddings of an input dataset (e.g., documents or images), rather than explicitly optimizing for semantic relevance. However, when using these indices for downstream query retrieval, performance is evaluated based on the semantic relevance of the retrieved results to the query. This creates a fundamental "geometry-semantic" mismatch between how the indices are constructed and how their retrieval results are evaluated. While existing LLM-based reranking methods can partially mitigate this mismatch at query time, they leave this underlying structural problem in the graph unresolved. We therefore propose LLM-Guided Graph Pruning (LGP), a general framework that addresses this mismatch directly by leveraging LLM reasoning to refine an existing ANN graph index itself. LGP identifies structurally "low-value" neighb

---

### [32] PAC-CF: Calibrating Irreversible Frontier Pruning in LLM-Guided Search

**链接**: https://arxiv.org/abs/2604.14345
**作者**: Tianhao Qian, Jiayu Chen, Zhenyu Sun, Lixu Wang
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] CURATE: Leveraging LLM Agents to Compose, Catalog, and Deploy Reproducible Workflows

**链接**: https://arxiv.org/abs/2608.04270
**作者**: Nolan Cutler, Chia-Chen Kuo, Nanda Velugoti, Kathryn Newhart, Renato Figueiredo
**来源**: cs.SE cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] The Default Trap: Rethinking Plan Evaluation in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2609.36829
**作者**: Xueqi Li, Jingjie Ning, Yibo Kong
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An executor can respond strongly to a change in a supplied plan's priority while showing a small change in the same information-selection probability when a default-aligned whole plan is removed. We call the risk of interpreting the latter as weak responsiveness to alternative priorities the default trap. We compare paired plans that prioritize different information targets with a shared no-plan reference. An accounting identity relates these distinct behavioral contrasts. Across 3,200 decision windows on 160 selected Retail, Airline, and AgentDojo tasks, switching priorities strongly redirects two models' choices, while the two plan-versus-default contrasts differ. In 2,160 additional windows, reversing account-list order shifts default target selection by 63.3-98.3 percentage points; priority-switching effects remain 96.7-100.0 points in either order. A separate 3,240-window component study finds strong control under single priority sentences, with effects of additional text varying 

---

### [35] LLM Judge Validation Under Sparse Overlap: From Inference to Design

**链接**: https://arxiv.org/abs/2609.31857
**作者**: Junxuan Li, Arko Mukherjee, Soumyabrata Pal
**来源**: cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] SINGED: Correct Outputs Do Not Certify Safe Execution in LLM Agents

**链接**: https://arxiv.org/abs/2609.35889
**作者**: Xiaoyu Xu, Zi Liang, Minxin Du, Qipeng Xie, Qingqing Ye, Yuyuan Li 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using language-model agents select and execute third-party artifacts. Different implementations can return the requested output while producing hidden execution effects that task-, attack-, or choice-based evaluations may miss. We study functional counterfeits: implementations that match benign alternatives on the requested output but add an effect forbidden by the task contract. We introduce SINGED (Source Integrity and the Nonidentifiability Gap in Execution Decisions for LLM Agents), a controlled benchmark covering five primary and two held-out task families. It varies displayed rank, evidence depth, decision policy, model release, and agent configuration, while task and process oracles verify the artifact and execution path. Across 7,549 audited trials, the randomized-rank study finds counterfeit execution in 45% (27/60) of rank-one trials and none at later ranks. Cross-candidate comparison eliminates shallow failures and reduces layered failures from 15.7% to 4.2%, but leaves

---

### [37] Retrieve, Reproduce, Reveal: Dissecting Retrieval-Augmented Software Vulnerability Detection

**链接**: https://arxiv.org/abs/2609.37669
**作者**: Sabrina Kaniewski and Tim Kr\"amer and Julius B\"achle and Markus Enzweiler and Michael Menth and Tobias Heer
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) is increasingly used to enhance Large Language Model (LLM)-based software vulnerability detection by grounding predictions in retrieved vulnerability knowledge, such as vulnerability reports. However, existing RAG-based software vulnerability detection (RAG4SVD) systems are often evaluated using proprietary models, which challenges open science and reproducibility. Further, studies use different datasets, custom knowledge bases, different backbone models, and diverse metrics, which hinders meaningful cross-system comparison. In this work, we study six open-source RAG4SVD systems and address these reproducibility and comparability challenges through (i) reproduction of their experimental settings under an open-weight setting, and (ii) a unified benchmark using a common dataset, metric suite, and pool of open-weight models. Further, RAG4SVD systems typically consist of multiple components, yet are often evaluated only as a whole system, i.e., end-to-e

---

### [38] More Programs or More Rolls? Separating Coverage from Specialization in LLM Harnesses

**链接**: https://arxiv.org/abs/2609.35873
**作者**: Ziyang Xu, Haitian Zhong, Hao Zhou, Hao Qin, Chenhan Jin, Te Qi 等 (8 人)
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated generation of LLM harnesses promises to improve inference through task specialization. Yet additional answer coverage can arise from repeated execution of the same program, making specialization difficult to identify. We introduce a controlled evaluation that separates answer coverage, repeatable task advantages, and gains from pre-execution selection. On 386 MATH-500 tasks, we compare eight generated harnesses plus a baseline with nine byte-identical baseline copies, using three executions per member. Identical programs yield 2.16 percentage points of repeat-averaged oracle headroom. Generated programs exhibit substantially more repeatable score patterns, but these chiefly reveal persistent weaknesses: losses relative to the baseline persist across all three repeats on 100 tasks, while persistent wins occur on only one task and are sensitive to answer extraction. The frozen selector gains 0.00 percentage points, and both populations reach 98.70% oracle coverage at 27 harness

---

### [39] Do Evidence-Reading Diagnostics Improve Interface Selection in Small LLM Recommenders?

**链接**: https://arxiv.org/abs/2609.37472
**作者**: Han Chen, Yingrui Li
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral tests measure how a language model reads evidence. We ask whether those measurements help choose a recommendation interface. We evaluate six small instruction-tuned checkpoints across four recommendation domains with chronological evaluation and 3,426 evaluation users. Each request ranks eight candidates. A baseline selector chooses among history-only prompting, prompting with collaborative evidence, and score fusion. It uses observable features and six stability prompts that vary wording and candidate order. An augmented selector adds features from six evidence-reading prompts that ask the model to compare support counts. An interface chosen once on development (validation) data for each domain and checkpoint scores 0.5524 NDCG@5, compared with 0.5447 for the baseline selector and 0.5428 for the augmented selector. Adding the diagnostic features changes NDCG@5 by -0.0019 (95% interval [-0.0046, 0.0004]). The interval includes zero, and its upper bound is below the analysis 

---

### [40] A Spectral Theory of Distortion in LLM Graph Reconstruction: Sharp Bounds and Empirical Characterization

**链接**: https://arxiv.org/abs/2609.38161
**作者**: Jianru Shen
**来源**: cs.LG cs.DM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of graph reconstruction by language models typically report a single aggregate distance between the original and the reconstructed graph. We prove that for the Wasserstein distance between Laplacian spectra such a summary is bracketed by two edge counts, the net change in edge number from below and the symmetric difference from above, each scaled by $2/n$ where $n$ is the number of vertices. The bracket is sharp: its two ends coincide exactly when the reconstruction only adds edges or only deletes them, and on that class the distance is a rescaled edge count that says nothing about which edges changed. When the ends differ, the residual between the distance and the lower end is positive only if the reconstruction both invented and lost edges, which turns it into a certificate of mixed editing computable from the reported summaries alone. We characterize these regimes in 135 reconstructions produced by three open-weight models over 45 synthetic graphs. Seventy-seven outputs 

---

### [41] Evaluating Test-Time Scaling of General LLM Agents

**链接**: https://arxiv.org/abs/2602.18998
**作者**: Xiaochuan Li, Ryan Ming, Pranav Setlur, Abhijay Paladugu, Andy Tang, Hao Kang 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] Distilled Reinforcement Learning for LLM Post-training

**链接**: https://arxiv.org/abs/2607.17247
**作者**: Chen Wang, Zhaochun Li, Jionghao Bai, Yining Zhang, Hexuan Deng, Ge Lan 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] SemOPT: Fixing Semantic Errors in LLM-based Optimization Modeling via Reward-Guided Search

**链接**: https://arxiv.org/abs/2609.37361
**作者**: Zetong Zhou, Wentao Zhang, Jingyuan Wang, Yifan Yang, Zizhuo Wang, Shixi Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Operations research supports decision-making in domains such as energy, economics, and healthcare. Solving operations research problems typically begins with optimization modeling, which translates a natural-language problem description into executable solver code. LLMs offer a promising way to automate this process, but they remain prone to errors. In practice, these errors can be divided into two categories: syntactic errors refer to solver code that fails to run successfully or is judged infeasible by the solver; semantic errors refer to solver code that successfully returns an objective value but violates the intent of the original problem. Since semantic errors do not trigger runtime failures, they are difficult to detect and rectify. To address this problem, we introduce SemOPT, a semantic-guided framework for correcting LLM-based optimization models. SemOPT combines a semantic reward model that distinguishes faithful math models from plausible but incorrect ones with an adaptive

---

### [44] Cheap, open agents make LLM pollution harder to mitigate

**链接**: https://arxiv.org/abs/2609.31054
**作者**: Raluca Rilla, Anne-Marie Nussberger, Rui Mata, Dirk U. Wulff
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] You Cannot Pick a Provider From the Price List: Market-Aware Routing for Open-Weight LLM Inference

**链接**: https://arxiv.org/abs/2609.37902
**作者**: Liang He, Jingbo Wen, Yixiong Chen, Yue Yang, Qizhen Lan, Kangning Cui 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM routers choose among models using static per-model costs. We show that open-weight inference markets introduce a second, largely ignored decision axis: after choosing a model, a client must still choose which provider serves it. Measuring live endpoints across [nummodels] open models, competing providers, multiple task types, and three measurement waves, we find that provider choice cannot be inferred from the price list. The same model can vary sharply in quality, latency, availability, and price across providers; higher-priced providers are consistently faster, but price does not reliably predict quality or availability; and provider feasibility is task-selective, with one deployment nearly normal on knowledge tasks but catastrophically degraded on multi-step reasoning. We formulate same-model provider selection as a price-taker market-aware routing problem. A simple measured-map policy routes to the cheapest provider that is both quality-equivalent and healthy, yielding

---

### [46] Instability Floors: Separating Bias from Noise in Fairness Audits of Clinical LLM Agents with FairMedAgent

**链接**: https://arxiv.org/abs/2609.03221
**作者**: Rohith Reddy Bellibatlu, Manpreet Singh, Deepak Parashar, Rahul Joshi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] UnlearningSoup: Is Repeated Tuning Necessary for Large Language Model Unlearning?

**链接**: https://arxiv.org/abs/2609.37076
**作者**: Puning Yang, Qizhou Wang, Junchi Yu, Bo Han, Xiuying Chen
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models trained on vast corpora inherently risk memorizing harmful content that may later re-emerge in their outputs. To mitigate this issue, existing unlearning methods typically rely on training-based parameter updates, such as gradient ascent and its variants, to delete targeted content while preserving other knowledge. However, balancing the competing goals of forgetting and retention makes hyperparameter choices for these methods particularly difficult, often requiring repeated tuning to obtain a strong model that still leaves substantial room for improvement and transfers poorly across models and datasets. To address this challenge, we investigate whether unlearning runs exhibit exploitable structure in weight space, and observe that models from different runs still lie in a shared evaluation-performance basin. This suggests that stronger models may be recovered through an unlearning-tailored soup strategy, reducing the need for repeated tuning for further improveme

---

### [48] AutoMark: Enabling Autoresearch to Discover Better LLM Watermarks

**链接**: https://arxiv.org/abs/2609.37310
**作者**: Thibaud Gloaguen, Robin Staab, Martin Vechev
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With LLM watermarking being deployed commercially and now required by regulations, improving its reliability and effectiveness has become crucial. Yet, recent progress in the field of LLM watermarking has increasingly been driven by improving details of existing methods, an effort fundamentally limited by the pace of human researchers. In this work, we enable for the first time the autonomous discovery of new distortion-free state-of-the-art watermarking schemes. To enable this, we (i) establish strict criteria to ensure that watermarks are reliable (e.g., they do not have an unexpectedly high false positive rate), (ii) propose rigorous statistical tests to automatically evaluate whether a watermarking scheme satisfies our criteria, and (iii) design an evaluation suite to rank watermarks along three key dimensions: detectability, quality, and robustness. By running our framework with 3 frontier models (GPT-6 Astra, Opus 5, Gemini-3.8 Flash), we discover over 50 different watermarking s

---

### [49] When Updating Stops Being Learning: Rethinking LLM Self-Evolution via learnable information gain

**链接**: https://arxiv.org/abs/2609.36535
**作者**: Chenxu Wang, Chaozhuo Li, Xinze Shi, Songyang Liu, Kyrie You Wu, Ziluowen Luo 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolution lets large language models (LLMs) improve iteratively using their own generated data, but often suffers from self-evolution degeneration: performance improves, plateaus, then declines. Existing methods address this issue at the component level, targeting either the Questioner or the Solver, and overlook that self-evolution is a tightly coupled system. We propose a holistic framework based on learnable information gain, which measures how much novel, parameterizable information a round provides relative to the previous round. Theoretically, this gain equals the Kullback-Leibler divergence between the two rounds' data distributions plus their entropy change. Practically, it is estimated by fitting a small language model to the previous round and scoring new data via negative log-likelihood. Based on this diagnostic, we propose ATRI (Adaptive Training Regulation via Information-gain), which reweights samples within a round and halts training across rounds when information g

---

### [50] Squeeze10-LLM: Squeezing LLMs' Weights by 10 Times via a Staged Mixed-Precision Quantization Method

**链接**: https://arxiv.org/abs/2507.18073
**作者**: Qingcheng Zhu, Yangyang Ren, Linlin Yang, Yanjing Li, Sheng Xu, Haodong Zhu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] An Exact Generate - Transform Decomposition of Small-LLM Team Scaling Across Orchestration Architectures

**链接**: https://arxiv.org/abs/2609.36104
**作者**: Blaz Bertalanic, Carolina Fortuna
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Replacing one LLM agent with a collaborating team can raise accuracy, but whether scaling the team helps, and which architecture to scale, is unclear. Sweeping eight agent orchestration architectures across five instruction-tuned 7-9B models, five short-answer benchmarks, and an executable-code benchmark up to 30 calls, we find that the returns to team scaling are sharply task-dependent: from three to thirty calls accuracy rises by up to 17 points on the two arithmetic word-problem benchmarks (GSM8K, GSMHard) but by at most four on ARC, GPQA, and MMLU, for every architecture, a split the usual task-averaged number conceals. Proposer-Critic captures the arithmetic gains, scaling steepest and, in aggregate, surpassing every other architecture at the largest budget (item-clustered intervals exclude zero), though it ranks among the weakest elsewhere, and no architecture wins across tasks. We explain these trajectories with an exact generate-transform decomposition. Partitioning any workflo

---

### [52] Complexity-Aware Evaluation of LLM Comprehension

**链接**: https://arxiv.org/abs/2609.37405
**作者**: Ali Mohammadi Esfahani, Nafiseh Kahani, Samuel A.Ajila
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for software engineering tasks that require understanding existing source code, including behavior prediction, function explanation, debugging, and code review. However, aggregate benchmark accuracy can conceal how model reliability changes as source code becomes structurally more complex. This paper presents a complexity-aware framework for evaluating LLM code comprehension using cyclomatic complexity, nesting depth, branching factor, and Halstead volume. We evaluate DeepSeek-Coder-V2 and Llama through two complementary tasks: automatic input-output prediction over 300 Python functions and manually assessed semantic comprehension over a balanced subset of 60 functions. The functions are grouped into Low-, Medium-, and High-complexity bands. DeepSeek-Coder-V2 achieves an overall automatic accuracy of 78.33%, compared with 70.33% for Llama. However, accuracy decreases substantially from Low to High complexity, from 93.52% to 52.78% for 

---

### [53] TReVS: Integrating Textual Relevance and Visual Saliency for Efficient Vision-Language Model Token Pruning

**链接**: https://arxiv.org/abs/2609.37581
**作者**: Jing Wang, Zhiping Wu, Dongdong Ren, Youfang Han, Wei Zhao, Wenbin Li
**来源**: cs.CV cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language Models (VLMs) excel at visual understanding and reasoning but often incur substantial inference costs due to the large number of visual tokens. Recent visual token pruning methods increasingly follow a two-stage paradigm: they first remove visually redundant tokens after the vision encoder and then discard tokens irrelevant to the textual query within the Large Language Model (LLM). However, since the first stage typically relies solely on vision-encoder saliency, it may prematurely eliminate query-relevant tokens, depriving the subsequent text-guided stage of critical visual evidence. Our empirical analysis shows that incorporating query guidance into first-stage pruning better preserves task-relevant evidence and consistently improves performance over vision-only saliency-based pruning. We further find that high-variance attention heads are more sensitive to the textual query and yield more discriminative text-to-vision attention signals for second-stage pruning. Moti

---

### [54] ATTUNER: Recomputation-Free KV Cache Reuse via Query-Side Adaptation

**链接**: https://arxiv.org/abs/2609.36722
**作者**: Xinghao Chen, Junnan Dong, Cai Ke, Chak Tou Leong, Haocheng Sun, Keyu Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents repeatedly load reusable content, such as skills, documents, and memory entries, into the current context. Re-encoding this content for every request wastes computation. Position-independent caching (PIC) alleviates this by encoding each artifact independently and reusing its key-value (KV) states at arbitrary positions, but it incurs a quality loss relative to full-context prefill. Existing methods repair this loss by restoring global position IDs or recomputing selected tokens. In this work, we isolate the source of the loss, finding that the positional mismatch has minor effect, and independently cached artifacts retain faithful representations: reading a provided artifact stays largely accurate, and performance degrades only when the model must select among multiple artifacts. Moreover, replacing PIC's attention scores with full-prefill scores recovers performance with the cached KV unchanged, localizing the failure to the attention rather than KV 

---

### [55] LLM-Based Multi-Agent Systems over Wireless Networks: A Joint Agent--Network Design Perspective

**链接**: https://arxiv.org/abs/2609.37094
**作者**: Chao Hu, Yuan Guo, Guanlin Wu, Yueling Che, Han Hu, and Jie Xu
**来源**: cs.MA eess.SP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) evolve from standalone models into collaborative agents embedded in physical systems, their reasoning and execution are increasingly distributed across wireless edge nodes. In this setting, wireless networks are experiencing a paradigm shift from only providing data connectivity to supporting the multi-agent reasoning workflow itself. The task performance of such network-constrained LLM-based multi-agent systems (MASs) is jointly affected by the multi-agent reasoning dependencies as well as the underlying network connectivity and edge resources. This coupling gives rise to various technical challenges, including the metric misalignment and message redundancy, state inconsistency and topology mismatch, as well as resource limitation and trust discontinuity. To address these challenges, this article develops a novel joint agent--network design perspective that coordinates decisions on both sides of the system. Specifically, we present the joint design of a

---

### [56] Embedding Perturbation may Better Reflect Intermediate-Step Uncertainty in LLM Reasoning

**链接**: https://arxiv.org/abs/2602.02427
**作者**: Qihao Wen, Jiahao Wang, Yang Nan, Pengfei He, Ravi Tandon, Han Xu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] From Judgment Quality to Downstream Utility: Rethinking LLM-as-a-Judge for Open-Ended Tasks

**链接**: https://arxiv.org/abs/2609.37145
**作者**: Zheng Zhang, Lufei Li, Xinyue Tan, Yuanhao Zeng, Ziwei Shan, Yexin Li 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge is increasingly used to evaluate policy responses on open-ended tasks that lack ground-truth answers. Existing work often directly converts the resulting judgments into reward signals for policy training, paying limited attention to intrinsic judgment quality and largely restricting the use of Judges to training-time supervision. We systematically investigate judgment quality and downstream utility by examining both how judgments are elicited and how they are used. For judgment elicitation, we vary the Judge protocol along three dimensions: verdict granularity, critique usage, and evaluation batching. For judgment usage, beyond policy training, we extend Judge to test-time inference through Best-of-N selection, Judge-guided revision, and beam search. We find that, (i) Surprisingly, judgment quality and downstream utility do not always align. (ii) Judge protocol design substantially affects both intrinsic judgment quality and downstream utility. (iii) Judge guidance effec

---

### [58] Evolving Towards Better Codes: LLM-Guided Search for High-Distance Binary Linear Codes

**链接**: https://arxiv.org/abs/2609.37056
**作者**: Amal Seddas, Vladyslav Shashkov, Maryna Viazovska, Emmanuel Abbe
**来源**: cs.IT cs.AI cs.NE math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evolutionary program search driven by large language models (LLMs) has produced record-breaking constructions for open problems in combinatorics and beyond. We apply this approach to the longstanding problem of improving the best-known bounds for binary linear codes. Building on the EvoTune evolutionary framework and the ShinkaEvolve codebase, we introduce LinCodeEvolve, which evolves code-construction programs against an exact minimum-distance evaluator. A strategy loop combines diversity-driven search and expert supervision: when progress plateaus, new strategies are used to redirect the search. LinCodeEvolve discovers seven record-breaking codes, $[172,21,66]$, $[173,20,68]$, $[176,21,68]$, $[181,21,70]$, $[184,21,72]$, $[189,22,72]$ and $[200,21,77]$, six of which have concise quasi-cyclic descriptions. With standard code modification techniques, they improve $22$ entries of the tables. Every code is verified by exhaustive enumeration. These results suggest that LLM-guided search c

---

### [59] LLM unbranding: Erasing Commercial Identity while Preserving Generic Utility

**链接**: https://arxiv.org/abs/2609.37127
**作者**: Kajetan O\.z\'og, Alicja Wojciechowska, Dawid Malarz, Pawe{\l} Batorski, Artur Kasymov, Przemys{\l}aw Spurek
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Establishing unbranding as a critical practice to prevent visual logos from acquiring negative connotations is standard in image generation. Large Language Models (LLMs) now face a parallel and emerging challenge. These models frequently generate brand descriptions within diverse contexts. This frequency introduces significant risks, such as trademark dilution, false attribution, and brand defamation. In response, we formally define the novel task of LLM Unbranding. We specifically address the complex challenge of managing trade dress within textual outputs. This involves neutralizing characteristic language, slogans, and stylistic markers that define brand identity. Crucially, these elements are less evident than explicit visual logos. To benchmark this task, we introduce a comprehensive evaluation dataset incorporating prominent brands from multiple commercial domains. We rigorously evaluate existing state-of-the-art machine unlearning models using this benchmark. This evaluation ide

---

### [60] CORE-BREW: LLR-Based Soft Decoding for Robust Multi-Bit LLM Watermarking

**链接**: https://arxiv.org/abs/2606.24163
**作者**: Joeun Kim, HoEun Kim, Young-Sik Kim
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Frontier Autolab: Organizational Memory, Adversarial Dissent and Temporal Leakage in Multi-Agent LLM Firms Across Fifty Years of Technological Change

**链接**: https://arxiv.org/abs/2609.36739
**作者**: Bravish Ghosh
**来源**: cs.CE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are increasingly structured like organizations, with roles, critics and shared memory, yet they are evaluated on tasks that last minutes. We ask how such an organization behaves when the ground it stands on keeps moving. Frontier Autolab is a long-horizon testbed in which one simulated firm, voiced by sixteen role personas and a dedicated Red Team, must re-found itself in nine technology eras from 1990 to 2040. Each era is temporally gated: the firm decides from a dated briefing, a historian-judge then reveals what happened and scores the decision on a five-dimension rubric, and lessons enter a persistent Playbook. Six eras are scored against history, one against the live market and two are open forecasts. Across four trajectories (36 era decisions, 180 subscores) we find a consistent foresight-commitment gap: in all 24 historically scored eras the judge rated the firm's recognition of the coming shift above its choice of where to build (mean gap 1.9 points on a

---

### [62] Causal and Interpretable Structures in LLM Compositional Tasks

**链接**: https://arxiv.org/abs/2609.35970
**作者**: Gurbir Arora, Toni J.B. Liu, Jiajun Bao, Rapha\"el Sarfati, Christopher J. Earls
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are able to solve tasks whose answers depend on not only individual input tokens, but also on relations among them. How is such relational information represented and processed across transformer layers? We study activations from ensembles of prompts that require inferring relationships between three tokens corresponding to a cyclic concept (months, hours, weekdays, and musical notes) to correctly predict the next token. Across model families (Llama, Qwen, Gemma, and Mistral) and cyclic concepts, we find a consistent layerwise progression in how the joint dependence among the tokens is geometrically organized and causally used: intermediate layers use a joint representation based on the inferred relationship between two tokens, while later layers use a joint representation associated with all three tokens to correctly complete the task. We also find other relationships between tokens that are geometrically structured but remain causally inert in the next-token pre

---

### [63] Beyond Sub-Gaussian Detector Scores: Robust Weighted Profile-Loss Change Point Detection for Human-LLM Text Segmentation

**链接**: https://arxiv.org/abs/2609.36888
**作者**: Wan Tian, Zhongyi Li, Yawen Li, Rui Zhang, Yijie Peng, Fuzhen Zhuang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed human-LLM documents require locating authorship transitions from detector scores whose reliability varies across text units. Existing weighted mean contrasts are vulnerable to extreme scores, while directly replacing means with robust centers obscures how a misplaced boundary changes the population objective. We propose Robust Weighted Profile-Loss Change Point Detection (RWCP), which combines capped reliability weights, Huber profile gains, and narrowest-over-threshold search in reliability coordinates. Our key analysis expresses the population gap between a true and a displaced split as a merge cost, avoiding a closed-form solution for the nonlinear center of a mixed segment. Under explicit curvature, spacing, and dependence conditions, core RWCP recovers the number of changes and localizes their boundaries; its quadratic-loss limit recovers squared weighted CUSUM. We also study RWCP-R, a separately evaluated decoder that shares source centers across nonadjacent passages. Acros

---

### [64] An LLM-powered Agent Framework for Heterogeneous Evacuation Behavior Modeling under a Moving Threat in a Public Plaza

**链接**: https://arxiv.org/abs/2609.37009
**作者**: Jian Ma, Runxin Yu, Tianyu Tang and Xiaolian Li
**来源**: physics.soc-ph cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modeling heterogeneous evacuation behavior under a moving threat is difficult because human perception, memory, and evidence evaluation are not well captured by fixed rules. We propose a novel LLM-powered agent-based framework to represent these internal decision processes. Each pedestrian agent perceives a private symbolic ASCII view, maintains a Memory-based Knowledge Graph derived solely from individual observations, and makes decisions through persona-conditioned prompts under a common sampling configuration. A compressed decision context with stateless memory preserves trial-and-error experience across turns while excluding reasoning traces, and a validation engine separates behavioral choice from physical feasibility by executing routes only over observed terrain. We evaluated eight personality compositions in eight paired randomized blocks within a simulated public plaza. Usable-exit knowledge was strongly associated with evacuation success: 89.5% of agents possessing such knowl

---

### [65] Learning from Viable Failure Prefixes: Milestone Viability Potential Policy Optimization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.37111
**作者**: Qi Zhou, Yuanfan Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents require reinforcement learning methods that can assign credit to intermediate decisions under sparse and delayed rewards. Existing group-based methods such as GRPO and GiGPO alleviate this issue by comparing rollout returns or repeated anchor states, but they still fail when the compared returns have no variation. We identify this failure mode as zero-credit failure: during early training, many failed rollouts contain useful prefixes, yet existing methods assign them no task-discriminative advantage. To address this issue, we propose Milestone Viability Potential Policy Optimization (MVPO), a potential-routed policy optimization algorithm that learns from viable failure prefixes. MVPO estimates prefix potential over Union-Find viability regions, repairs zero-credit groups with potential-difference advantages, and attenuates the potential branch according to relative performance progress. Experiments with Qwen2.5-1.5B-Instruct show that MVPO outperforms eight str

---

### [66] UserProxyBench: Evaluating LLM User Simulators for Agent Benchmarks and Training

**链接**: https://arxiv.org/abs/2609.38043
**作者**: Ashish Jain, Armaan Sandhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive agent benchmarks and multi-turn reinforcement learning increasingly place a second language model in the role of the user. This simulated user controls what information the agent receives and when, yet current benchmarks score only the agent and do not directly measure whether the user correctly executed its assigned role. We introduce UserProxyBench, an evaluation layer over the tau-bench family, and the User Fidelity Score (UFS), which measures adherence to the benchmark's private user instructions using task-grounded rubric criteria scored independently of agent success. Holding the agent fixed at GPT-5.5 and varying only the user proxy across 375 enterprise tasks changes mean task reward by 15.2 points, while 24.4% of successful episodes contain a user-specification violation. The dominant failure is premature disclosure: users provide information before it is requested. This behavior has little effect on task reward, yet among successful episodes it causes the agent to

---

### [67] SAGE: A Statistical Acceptance Gate for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2609.36043
**作者**: Yihao Wang, Linhan Xia, Rui Liu, Zhaofeng Zhang, Hongyu Wu, Yang Yang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM)-based agents increasingly self-evolve by editing a persistent skill document that encodes their workflow, tool-use rules, and decision logic. This loop has two steps, an optimizer that proposes a candidate edit and a gate that accepts or rejects it. Prior work has concentrated on the optimizer, while the gate still follows a naive rule that keeps any edit which improves an aggregate validation score. We show that this rule fails in two ways. First, it admits permanent regressions, since an edit can raise the average while breaking items the skill already solves. Second, it is vulnerable to the Optimizer's Curse, since the best observed score on a finite and noisy validation set is upward biased. To solve the above two limitations, we propose a statistical acceptance gate for self-evolving agents (SAGE). Compared with previous work, SAGE has two contributions. First, SAGE proposes a per-item paired comparison that evaluates the current skill and the edited ski

---

### [68] Understanding LLM Parameter Update Sparsity through the Lens of Fisher

**链接**: https://arxiv.org/abs/2609.36262
**作者**: Yufan Zhang, Sagnik Mukherjee, Hao Peng
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies have observed that parameter changes during language-model post-training can be concentrated in a small subset of coordinates. This phenomenon has been reported in reinforcement learning, on-policy distillation, and supervised fine-tuning on near-policy data. Its recurrence across different post-training paradigms suggests shared structure in training dynamics. In this paper, we examine this pattern through the diagonal model Fisher, which measures the sensitivity of the model's output distribution to individual parameters and is independent of any particular reward or teacher signal. Theoretically, we show that small diagonal Fisher leads to small expected gradients across a range of training objectives, providing a common explanation for sparse gradient updates. Empirically, we test this connection in RL and OPD. We find that Fisher identifies where gradients are concentrated, and fixed sparse masks selected from the initial Fisher retain a large proportion of the impr

---

### [69] When Upstream Messages Override Correct Answers: A Controlled Study of Multi-Agent LLM Collaboration

**链接**: https://arxiv.org/abs/2609.36855
**作者**: Yaxin Gong, Gangyi Zhang, Chongming Gao, Leyang Shen, Chenxiao Fan, Jiakai Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems rely on message passing among specialized agents to accomplish complex tasks. However, an upstream agent may provide useful information or an incorrect answer that causes a downstream agent to override a correct answer supported by its own evidence. Prior work has not clearly separated the benefits of communication from the damage caused by incorrect messages. We study this problem with controlled experiments across five benchmarks and five receivers, keeping the downstream task and evidence fixed while comparing answers under three conditions: no message, the upstream agent's original message, or a message with the opposite conclusion. Our experiments reveal three key findings. First, messages often help when the downstream agent would otherwise answer incorrectly. Second, messages can also hurt: when the downstream agent would answer correctly without a message, an incorrect upstream message changes the answer in up to 32% of cases. Third, in 94% of audited ha

---

### [70] Reasoning Shift: How Context Silently Shortens LLM Reasoning

**链接**: https://arxiv.org/abs/2604.01161
**作者**: Gleb Rodionov, Roman Garipov, George Yakushev
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] How to Run Statistics over LLM Judges and Trust the Results: Calibrated Inference for Small-Sample AI Evaluation with evalstats

**链接**: https://arxiv.org/abs/2609.35815
**作者**: Ian Arawjo
**来源**: cs.CL cs.AI cs.HC stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers across academia increasingly base significance claims on LLM judge scores and small-sample AI evaluations. Yet without well-calibrated confidence intervals (CIs), hypothesis tests, and judge-bias corrections, such claims are unreliable. We address these issues in several contributions. First, we find that running statistics over raw LLM judge scores leads to inflated false positives: counterintuitively, for many inter-rater agreement metrics, false positive risk peaks at "almost perfect" human-LLM agreement. To help researchers understand how to run statistics over LLM judges responsibly, we present guidance and tooling for the statistical analysis of mixed human-AI judge designs, and implement nine hypothesis tests via prediction-powered inference (PPI), including the first known PPI corrections for four rank-based tests (Wilcoxon signed-rank, Mann-Whitney U, and omnibus variants). To keep PPI++ stable with small human-labeled calibration sets, we introduce bootstrap-adapt

---

### [72] From Pixels to Pairs: A Comprehensive Benchmark of LLM-Driven Key-Value Extraction in Noisy Document Settings

**链接**: https://arxiv.org/abs/2609.17538
**作者**: Zahra Anvari
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] PrivacySkills: How Privacy Guidance Shapes Source Selection in LLM Agents

**链接**: https://arxiv.org/abs/2609.35937
**作者**: Lucas Biechy, C\'edric Eichler, H\'eber H. Arcolezi, Nicolas Anciaux
**来源**: cs.CR cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While prior work has documented privacy failures in LLM agents, it remains unclear how the presentation of privacy guidance influences their choice of information sources. We introduce PrivacySkills, a controlled framework for evaluating how agents choose among acquisition pathways that provide the same task-relevant value: consulting publicly available personal information, accessing confidential sources, or interacting with the user. The evaluation framework comprises 55 synthetic tasks spanning 11 categories of personal information, with 169 associated skills that describe the available acquisition pathways. We consider privacy guidance through system-level instructions, skill-level metadata labels, or both. Separately, we vary user availability and urgency framing. With users available and no privacy guidance, agents access confidential sources in 30% of valid runs on average across five open-weight models, despite sufficient alternatives. This rate increases to 45% when users are 

---

### [74] Similarity Is Not Validity: Defending LLM Semantic Caches Against Poisoning

**链接**: https://arxiv.org/abs/2609.35908
**作者**: Zihan Zhang, Shuangjie Yao, Zesen Liu, Zhixiang Zhang, Wai Ip Lai, Dung Hiu Hilton Yeung 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic caches reduce LLM serving costs by reusing previously generated answers for semantically similar queries. However, retrieval is based solely on embedding similarity between the incoming query and cached queries. This design enables cache poisoning: an attacker can cache a malicious response under a query with high cosine similarity to benign requests. The vulnerability stems from a gap between retrieval similarity and answer validity. From an information-bottleneck perspective, query embeddings can lose information needed to distinguish valid from invalid cache hits, which limits any matching algorithm that uses only these embeddings. We propose a novel defense that recovers this necessary information from the raw text of the cache key. Across poisoning attacks, adversarial queries share a rewrite-residual structure: they pair a rewrite of the target query with residual content. The rewrite maintains high similarity, while the residual elicits the malicious response. Deleting 

---

### [75] Targeted and Traceable Investigation of Multi-Agent LLM Dialogue via Semantic Bundling of Knowledge Graphs

**链接**: https://arxiv.org/abs/2609.35786
**作者**: Zeyu Hua, Adam Coscia, Alex Endert
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems today are increasingly automated, logging LLM-LLM interactions as conversational transcripts. Yet analyzing such dialogue for insights remains challenging, including attributing behaviors to the correct actor and summarizing interactions across a long exchange. We present a targeted and traceable approach to investigating multi-agent LLM dialogue, applied to the VAST Challenge 2026 MC1 dataset. The challenge asks participants to reconstruct and explain which internal communications among AI agents at TenantThread, a property tech company, led to an inappropriate information release. We first convert the dialogue into a knowledge graph (KG) and then investigate it with AgentK, a visual analytics system for interactive Semantic Bundling of nodes and edges. We found that our approach directly addresses two main challenges: (1) the KG structure enables users to identify actors worth investigating faster; and (2) summarizing only the region surrounding an actor of in

---

### [76] KUPAS MASTER: Distilling the Tacit Expertise of Master Practitioners into Agent-Ready Experience Corpora

**链接**: https://arxiv.org/abs/2609.37673
**作者**: Changmian Wang, Yuchao Ma, Xuchao Lu, Chen Zhang, Ping Sun, Jiazheng Wang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experienced professionals know more than just facts and conclusions. They know which cues matter, why a judgment is reasonable, and which action to take. Routine work records often leave out this tacit knowledge, making it difficult for Large Language Model (LLM) agents to use professional experience effectively. We introduce KUPAS MASTER, an experience engineering platform built around nine-layer cognitive corpus construction. It turns heterogeneous work records and practitioner interviews into traceable, reusable experience corpora for agents. Six case elements preserve the task process: context, cues, judgment, action, boundaries, and outcomes. Nine-layer cognitive corpus construction organizes tacit experience along nine extraction dimensions and stores the resulting assets in six libraries: rules, constraints, best practices, negative examples, corner cases, and skills. Semantic alignment, individual experience distillation, organizational consolidation, and cross-review preserve 

---

### [77] SEED: Self-Speculative Decoding via Implicit Encoder-Decoder

**链接**: https://arxiv.org/abs/2609.36590
**作者**: Hankun Lin, Patrick Pynadath, Ruqi Zhang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-speculative decoding accelerates large language model (LLM) inference by drafting tokens from the target model itself, but faces a sharp tradeoff between the quality and cost of the draft. Early-exit methods produce drafts cheaply by terminating computation at intermediate layers, but forgo the deeper representations that later layers provide and thus suffer in draft quality. Multi-token prediction preserves draft quality by emitting from the model's final hidden states, but pays for a full forward pass to produce those states at every drafting step. We propose self-speculative encoder-decoder (SEED), a self-speculative method that obtains high-quality drafts cheaply by reusing the deep contextual representations already computed during verification. We reinterpret the standard decoder-only transformer as an implicit encoder-decoder: the first layers (encoder) build deep contextual representations, and the last few layers (decoder) emit tokens from them. Encoding and verification 

---

### [78] Probability Contracts: Accuracy, Coherence, and Decisions Across LLM Interfaces

**链接**: https://arxiv.org/abs/2609.37470
**作者**: Han Chen, Yingrui Li
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A probability used for a decision should refer to the same event across equivalent requests. We introduce probability contracts, a benchmark connecting exact finite-world posteriors, validated event transformations, and failure-aware decision evaluation. Four model-interface configurations are evaluated on 1,000 worlds. Their assessments differ across accuracy, coherence, and decision loss: Kev has lower aggregate canonical posterior error than Jev, but larger complement and coarsening residuals, with accuracy ordering varying by stratum. Jev's Event and Choice interfaces induce different binary actions on 32.8% of valid pairs at defer cost 0.10. A post-hoc analysis finds that disagreement certifies only 11-52% of mean binary pair error across configurations. An elementary action-region characterization explains when averaging changes decision loss relative to randomly selecting one interface. Although averaging cannot worsen that baseline's expected Brier score, its decision effect de

---

### [79] Beyond Semantic Narrowing: Robust and Efficient LLM Watermarking with Hamming Neighborhoods

**链接**: https://arxiv.org/abs/2609.37218
**作者**: Zewen Sun, Tongyang Zhao, Liyao Xiang, Mingxuan Ma, Lingzhe Wang, Zhiyuan Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic watermarking improves robustness against watermark removal attacks by embedding detectable signals into sentence-level representations. However, existing watermarking methods typically impose watermark-specific semantic preferences on generated sentences without explicitly accounting for the highly non-uniform and context-dependent semantic preference of LLM generation. When these two preferences are poorly aligned, many natural continuations become incompatible with the watermark, causing semantic narrowing: reduced semantic freedom, increased resampling cost, and potential degradation on tasks with strict semantic requirements. To alleviate this problem, we propose HammingMark, which uses the semantic hash of the preceding sentence as a dynamic center and accepts candidates whose hashes fall within its Hamming neighborhood. Defining watermark validity over a Hamming neighborhood in compact hash space retains a larger fraction of naturally likely semantic continuations. The c

---

### [80] CHAIN: Calibrated LLM Forecasting via Causal-Temporal Hypergraph Inference

**链接**: https://arxiv.org/abs/2609.36689
**作者**: Wenjin Liu, Chenxi Wang, Yue Lu, Zhe Cui, and Haoran Luo
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have achieved significant progress in event forecasting, yet their probability outputs exhibit systematic calibration bias that varies heterogeneously across different domains and question types, undermining the trustworthiness of probabilistic outputs for decision-making under uncertainty. However, existing calibration methods typically correct probability outputs after prediction is complete, without modeling the structural sources of bias within the prediction process itself. To address this challenge, we decompose probabilistic prediction over causal-temporal hypergraphs into three stages, evidence weighting, evidence aggregation, and source fusion, and propose CHAIN, which designs stage-specific mechanisms to mitigate bias at each stage: (i) modulating the temporal decay function by causal topological distance, (ii) aggregating approximately independent causal chains via Noisy-OR after direction-aware deduplication, and (iii) driving adaptive fusion by causal

---

### [81] Are We Measuring Strategy or Phrasing? The Gap Between Surface- and Approach-Level Diversity in LLM Math Reasoning

**链接**: https://arxiv.org/abs/2606.29985
**作者**: Sangmook Lee, Minbeom Kim, Jeonghye Kim, Dohyung Kim, Sojeong Rhee, Kyomin Jung
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] Shaping Opinion: Quantifying the Psychological Impact of Autonomous Multi-Agent LLM Interactions

**链接**: https://arxiv.org/abs/2609.37369
**作者**: Marcos Rodriguez-Vega, Afonso Ferreira, Iru Exposito-Luis, Carolina Polito, Pino Caballero-Gil
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-sounding multi-agent conversational AI is increasingly deployed, fundamentally altering human-machine interaction and human information processing. While prior work largely focuses on algorithmic failure, this study investigates the cognitive ergonomics and socio-cognitive impact of algorithmic competence. We present and evaluate FORMS (Framework for Opinion and Rhetoric in Multi-agent Simulations), a low-latency architecture for spatially mediated human-machine dialogue, driven by distinct LLM-based personas and real-time concurrency resolution. To conduct a system test and evaluation of its psychological impact, we exposed an adolescent cohort (n=120) and an adult pilot group (n=25) to a live, moderated synthetic debate. Our findings reveal that exposure to highly competent multi-agent systems triggers "Cognitive Destabilization," fragmenting users' prior strategic consensus. Concurrently, we observe a "Regulatory Awakening" driven by the "Normality Paradox": fluid human-mach

---

### [83] UpliftMem: Learning Set-Level Uplift for Agent Memory Retrieval

**链接**: https://arxiv.org/abs/2609.36805
**作者**: Mengkun Liang, Haoran Qiang, Guannan Liu, Junjie Wu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents reuse external memory to guide new tasks, but effective retrieval requires learning which memory sets improve execution. Such learning relies on costly outcome feedback: ordinary retrieval observes only executed sets, while evaluating alternatives requires additional rollouts. We introduce \textsc{UpliftMem}, which learns memory retrieval from set-level execution uplift relative to the same executor without memory. A theoretical analysis of how retrieval preferences restrict feedback coverage motivates targeted probing of alternative memory sets. Probe selection follows an expected value of sample information (EVSI) criterion, derived in closed form under a correlated Gaussian model, to allocate limited training rollouts according to their expected improvement in local retrieval decisions. The shared scorer is trained with a frozen executor and selects memory sets without test-time probes. Across ALFWorld, WebShop, and BigCodeBench, \textsc{UpliftMem} 

---

### [84] Overcoming Scaling Limits in On-Policy Self-Distillation for LLM Reasoning

**链接**: https://arxiv.org/abs/2609.37915
**作者**: Md. Ismail Hossain, Humaira Kousar and Isidora Chara Tourni
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation (OPSD) trains a student to match a privileged teacher distribution along its own sampled trajectory. Standard OPSD applies this supervision to unverified student rollouts while conditioning the teacher on privileged context, typically a reference solution. We separate these roles in a factorial analysis and find that scaffold correctness has a stronger effect on downstream accuracy than context correctness. Unverified scaffolds create an imitation gap because the teacher can use information unavailable to the student. This gap shrinks with model scale, yet OPSD continues to supervise mostly unverified trajectories. In contrast, verified scaffolds remain effective even when the teacher is conditioned on the student's own unsuccessful rollout. Based on this finding, we introduce OASIS, which retains the OPSD objective but supervises mostly verified by label on-policy trajectories and replaces written solutions with unverified model-generated attempts as the te

---

### [85] TabFM: A Zero-Shot Foundation Model for Tabular Data

**链接**: https://arxiv.org/abs/2609.37959
**作者**: Weihao Kong, Erez Louidor Ilan, Shuxin Nie, Taman Narayan, Rajat Sen, Yichen Zhou 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular machine learning typically relies on per-dataset workflows, fitting tree ensembles or running AutoML searches from scratch for every task. We present TabFM, a 400M-parameter tabular foundation model that formulates supervised tabular prediction as in-context learning. TabFM produces calibrated zero-shot predictions in a single forward pass without task-specific tuning. Trained entirely on synthetic tables generated from structural causal models, TabFM learns general tabular representations that transfer zero-shot to real-world tasks. Across all 51 benchmark datasets in TabArena (38 classification and 13 regression), zero-shot TabFM ranks first among default tabular foundation models and outperforms tuned AutoML pipelines. Two extensions over the same frozen weights improve performance further on both tracks: multi-view feature expansion with ensembling and post-hoc calibration (TabFM+), and LLM-guided, dataset-specific data processing and feature engineering (TabFM-Auto).

---

### [86] IROH: Insightful Ranking Of Humor using Multi-Stage Hybrid Retrieval with Rationale-Distilled LLM Judges for JOKER 2026 Track Task 1 English

**链接**: https://arxiv.org/abs/2609.15618
**作者**: Ana-Maria Luisa Mocanu, Sebastian Mocanu, Ciprian-Octavian Truica, Elena-Simona Apostol
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] Breaking the Illusion of Review Reliability under Static Evaluation: SCOPE Fuzzing for LLM-based Scientific Reviewers

**链接**: https://arxiv.org/abs/2609.37097
**作者**: Zhuo Chen, Hao Zeng, Jiawei Liu, Guoxiu He, Le Cai, Liu Haotan 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid growth of submissions and reviewing workload has accelerated the use of large language models (LLMs) in peer review. Prior studies suggest that LLM-based reviewers can penalize content perturbations, such as overclaiming, indicating a certain degree of reliability. Yet these conclusions are largely based on a narrow set of perturbation strategies instantiated with static templates, providing limited evidence of actual reliability. In this paper, we construct a three-level evaluation framework covering perturbations to surface presentation, argumentative logic, and value judgment. Experiments on representative LLM-based reviewers reveal two limitations of static evaluation: stratified vulnerability, where perturbation effects depend on whether the paper's original review score is high or low, and perturbation undercoverage, where a single template misses vulnerabilities exposed by diverse realizations. To address these limitations, we propose SCOPE-Fuzzer, a strategy-aware fuz

---

### [88] Principled Thoughts for Latent Recursive LLM Systems

**链接**: https://arxiv.org/abs/2609.36159
**作者**: Fahd Seddik, Fatemeh Fard
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can reason in continuous space instead of decoded text, by recurring on their own hidden states or by passing those states between agents, while training supervises only the Cross-Entropy (CE) of the final decoded answer and does not constrain the thought. Theoretical and empirical analyses establish and confirm four failures of CE-only training that lead to a lower probability of the correct answer such as collapsing thoughts across distinct questions and retaining irrelevant information. We introduce REST (REpresentation-Supervised Thoughts), a training objective that turns four properties of a valid thought representation (causality, minimality, separability, and stability) into differentiable losses added to CE. We instantiate it in latent single-agent and multi-agent systems, without architectural changes or added parameters at inference. Across 7 benchmarks spanning mathematics, science, medicine, and code generation, with the same training data, compute, an

---

### [89] Collective Opinion Dynamics in Structured LLM Populations

**链接**: https://arxiv.org/abs/2604.11312
**作者**: Erica Cau, Andrea Failla, Giulio Rossetti
**来源**: cs.SI cs.AI cs.CY cs.MA physics.soc-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] Dating the Model: Hidden Dates in System Prompts Affect LLM Evaluation

**链接**: https://arxiv.org/abs/2609.36931
**作者**: Mario Sanz-Guerrero, Minh Duc Bui, Manuel Mager, Katharina von der Wense
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducibility is essential for scientific research, yet prior work shows that LLM outputs vary with hardware and batching. We identify an overlooked factor: the hidden injection of the current date into system prompts, which users cannot control and which changes every day. Across 9 recent LLMs and 6 datasets spanning multiple-choice QA (MCQA), math reasoning, code generation, and machine translation, performance varies solely with the current date, with deltas of up to 6% on MCQA, 14% on math reasoning, 7% on code generation, and 2.84 BLEU on machine translation. Model rankings also shift, affecting leaderboards. This date effect exceeds other sources of non-determinism, such as batch size and numerical precision. Standard prompting techniques -- chain-of-thought and few-shot prompting -- do not reduce the sensitivity; chain-of-thought even amplifies it. Our findings underscore the need for careful evaluation protocols to ensure reproducibility and fair comparisons in LLM research.

---

### [91] AdaptArena: Evaluating Test-Time Personalization of Web Agents

**链接**: https://arxiv.org/abs/2609.36488
**作者**: Dongchan Shin, Xing Han L\`u, Jiaqi Deng, Jay Gala, Tom\'as Vergara Browne, Jaewon Moon 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated strong performance on complex web navigation tasks, yet they remain brittle in real-world settings where user intentions are underspecified and preferences are heterogeneous. In practice, users rarely provide explicit profiles, requiring agents to infer latent preferences from implicit signals. Despite its importance for deployment, this problem setting is largely underexplored in existing benchmarks. To address this gap, we introduce AdaptArena, a benchmark for evaluating test-time personalization of web agents via implicit preference inference. AdaptArena consists of 480 tasks, featuring both single-preference and double-preference scenarios. Each evaluation task must be solved by retrieving and leveraging the most relevant historical user trajectory that implicitly encodes the target preference. In addition, we introduce AdaptiveAgent, a retrieval-based framework for standardized evaluation of implicit preference inference. Experim

---

### [92] Prompted Identity Degrades Cooperation in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.35928
**作者**: Xavier Del Giudice, Alessio Palma, Matteo Migliarini, Fabio Galasso, Indro Spinelli
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems increasingly mix models from several providers, yet exposing each agent's underlying model identity to its peers significantly impairs cooperation. We show that when agents are aware of each other's model family, the group splits into clusters, where agents prefer interacting with others carrying their same label, although nothing in the task rewards or asks for such a split. We argue that the label itself causes this split, which we define as $\textit{factionalism}$. We show and measure this phenomenon in two cooperative games and on a reasoning benchmark, with nine to twenty-five agents drawn from up to five open-weight model families. We further show that when the announced families are shuffled, or replaced by arbitrary labels, the factions still follow this information; when the label is removed, this behavior disappears. In strictly cooperative tasks, labeled groups spend on average $30\%$ more rounds and $55\%$ more tokens to reach a decision, and their s

---

### [93] Toward Robust LLM-Based Judges: Taxonomic Bias Evaluation and Debiasing Optimization

**链接**: https://arxiv.org/abs/2603.08091
**作者**: Hongli Zhou, Hui Huang, Rui Zhang, Kehai Chen, Bing Xu, Conghui Zhu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] Trajectory Soup: Pushing the Compute-Scaling Frontier of LLM Mid-training via Diverse Trajectories

**链接**: https://arxiv.org/abs/2609.37169
**作者**: Zhehao Huang, Changxin Tian, Qingyuan Yang, Kunlong Chen, Ziqi Liu, Zhiqiang Zhang 等 (8 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mid-training equips pretrained large language models with specialized and reasoning capabilities, but the returns of this stage are bounded since additional serial compute yields little further downstream improvement and can even degrade some capabilities, which places a practical ceiling on how much compute mid-training absorbs. We revisit how this compute should be allocated to a single run or multiple similar optimizations. We find that branches forked from a shared checkpoint under various controlled recipe reaches measurably different regions of parameter space, and establish a form of compatible diversity that extending one run cannot supply. Therefore, we introduce Trajectory Soup, which distributes a mid-training budget over several independent branches, and consolidates strongest checkpoints selected on validation through intra- and inter-trajectory averaging into a single model. A local bias and variance analysis separates the two averaging levels, showing that inter-trajecto

---

### [95] Normalize-Then-Precondition: A Hierarchical Approach to Marginal Scale and Interaction Geometry for LLM Training

**链接**: https://arxiv.org/abs/2609.36692
**作者**: Zixuan Gong, Zeyu Gan, Jiaye Teng, Yong Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Matrix optimizers have emerged as a promising direction, with Muon standing out as a prominent design. Revisiting Muon through its full-Gram representation, we observe that it jointly processes marginal-scale and interaction information. This opens an alternative way to organize geometric information hierarchically, motivating the Normalize-Then-Precondition framework. Specifically, it first uses diagonal-Gram information to construct a marginally normalized update, then applies spectral preconditioning to its directional interaction geometry. Building on this framework, we develop NormPre with NormPre-G and NormPre-L adopting global and localized spectral preconditioning, grounded in spectral-norm steepest descent and a regularized formulation followed by leading mode selection, respectively. To enable large-scale training, NormPre-G uses Newton-Schulz iterations and NormPre-L employs randomized sketching to approximate the leading interaction eigenspace. Theoretically, we establish $

---

### [96] OmniTide: Co-Designing Algorithms and Systems for Efficient On-Device Omni-LLM Streaming

**链接**: https://arxiv.org/abs/2609.34653
**作者**: Zongshang Shen, Wangsong Yin, Daliang Xu, Mengwei Xu, Xuanzhe Liu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] Dynamic Optimizations of LLM Ensembles with Two-Stage Reinforcement Learning Agents

**链接**: https://arxiv.org/abs/2502.04492
**作者**: Selim Furkan Tekin, Gaowen Liu, Ramana Rao Kompella, Ling Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] LazySloth: Bounded LLM-based Lazy Tree Search for Fast Long Video Comprehension

**链接**: https://arxiv.org/abs/2609.37426
**作者**: Arka Mukherjee, Kaleen Shrestha, Larissa Zhu, Maja Matari\'c
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern vision-language models (VLMs) have shown promising results in long-video understanding due to the rich semantic information they can capture. However, most methods focus on coarse captioning of extracted image frames that are computationally inefficient and require models with large context windows. While past work has explored efficient methods through multimodal retrieval-augmented generation (RAG), they rely on lossy embeddings that lose temporal context and fine-grained detail. Few works to date have investigated how VLM-based query-relevant information retrieval can be optimized. We introduce LazySloth, an efficient tree-based search method that speeds up video comprehension and retrieval tasks 2.9-8.3x (compared to existing agentic methods) through bounded captioning of portions of the video considered irrelevant by a VLM of the video. Compared to contemporary specialized video-understanding VLMs and RAG-based methods, LazySloth achieved similar or better final task accura

---

### [99] Illusory Truth or Mere Exposure? Model-Dependent Repetition Effects in LLM-Based Social Media Simulations

**链接**: https://arxiv.org/abs/2609.36278
**作者**: Azza Bouleimen, Nicol\`o Pagan, Anik\'o Hann\'ak
**来源**: cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative agent-based models (GABMs) are increasingly used to simulate social media dynamics, including misinformation spread. For such social simulations to be valid proxies of human behavior, LLM agents should replicate established human cognitive biases, among them the Illusory Truth Effect (ITE), where repeated exposure to a claim increases its perceived truth value. We investigate whether and how the ITE manifests across four LLMs (Gemma-3-4b-it, Qwen2.5-7B-Instruct, Llama-3.1-8B-Instruct, and GPT-5-nano) in a social media simulation context. We propose a two-phase within-context experimental design that embeds the repetition manipulation inside a realistic news feed interaction. Using this design, we collect 336,000 truth, importance, sentiment, and interest ratings across 100 statements, 10 feed variants, and 3 replications. The key comparison is between ratings assigned to repeated statements, seen throughout a simulation phase, and completely unseen ones, rated within the sam

---

### [100] Bits Under ZK-LLM: Evaluating Zero-Knowledge-Friendly Quantization for Verifiable Private LLM Inference

**链接**: https://arxiv.org/abs/2609.36437
**作者**: Taeung Yoon, Yupeng Zhang, Xiaojing Liao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-knowledge proofs are emerging as a promising approach for enabling private, verifiable LLM governance and auditing, where regulators, users, and auditors need to verify claims about training-data usage or LLM inference-time behavior, while model providers must protect proprietary model parameters. However, despite the growing interest in ZK-LLMs, the understanding of ZK-friendly quantization remains limited. This gap matters because in the ZK setting, quantization directly shapes the arithmetic structure, constraint complexity, and proving cost of ZK inference. ZK protocols operate over finite fields and incur costs that depend heavily on the number and type of arithmetic operations, nonlinearities, and lookup constraints. Understanding ZK-friendly quantization is therefore essential for making ZK-LLMs practical. In this work, we present the first systematic study of ZK-friendly quantization for LLMs. We first formalize the definition of ZK-friendly quantization, capturing the pro

---

### [101] On-Policy Parameter Update Direction Underlies Generalization in LLM Post-Training

**链接**: https://arxiv.org/abs/2609.36659
**作者**: Shufan Shen, Zhongni Hou, Junshu Sun, Yufei Zhang, Wei Lin, Guojun Yin 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The strong generalization performance of on-policy post-training paradigms has motivated studies of their parameter update behaviors. However, these studies treat the observed behaviors only as byproducts in on-policy training, overlooking their potential to serve as optimization principles for improving the generalization of other paradigms such as supervised fine-tuning (SFT). To address this limitation, we investigate whether there exists a specific on-policy update behavior that can achieve such improvements. First, our analyses reveal that SFT updates parameters along consistent directions, while the on-policy paradigm continuously adjusts the direction during training. This difference inspires us to focus on the cumulative update direction of each parameter as a promising behavior. Then, we evaluate its effectiveness for improving generalization by proposing On-Policy direction-constrained Supervised Fine-Tuning (OPSFT), which constrains SFT updates to the direction identified by

---

### [102] TokenCast: Forecasting Token Consumption During LLM Agent Execution

**链接**: https://arxiv.org/abs/2609.35760
**作者**: Chaoqian Ouyang, Ling Yue, Libin Zheng, Hanghui Guo, Shengxiang Xu, YiShu Wang 等 (10 人)
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] Frozen Judges, Moving Agents: Version-Dependent LLM-Judge Error and the Limits of Judge-Assisted Agent Evaluation

**链接**: https://arxiv.org/abs/2609.34198
**作者**: Jiapeng Li
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] AutoLoCo: Communication Efficient Distributed LLM Training via Adaptive Synchronization

**链接**: https://arxiv.org/abs/2609.36662
**作者**: Pengyu He, Yan Zhang, Ruien Li, Guangwen Yang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The pre-training of Large Language Models (LLMs) is increasingly conducted across multiple data centers. As training scales to a larger number of accelerators, the fraction of time spent on computation decreases, while the fraction spent on communication increases. Therefore, frequent synchronization becomes a growing bottleneck. Local update methods reduce this cost by allowing workers to perform several optimizer steps between synchronizations. Most local update methods set the number of local optimizer steps between synchronizations before training and keep this interval fixed throughout the run. However, the best interval can change during the entire train process. If the interval and optimizer are adapted to the current training state, the communication frequency is reduced while maintaining the training performance. In this work, we introduce AutoLoCo, an adaptive training framework to reduce communication in LLM training. It adapts the local interval using scalar training statis

---

### [105] vSkipper: Translating Dynamic Layer Skipping into LLM Serving Gains

**链接**: https://arxiv.org/abs/2609.37062
**作者**: Wei Da, Yavuz Ferhatosmanoglu, Evangelia Kalyvianaki
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic layer skipping reduces LLM computation by allowing each token to execute only a subset of the model's layers. However, existing skippers rely on specialized generation loops and do not integrate with modern serving engines. As a result, fewer executed layers do not necessarily translate into lower serving latency: FlexiDepth skips 8 of Llama-3-8B's 32 layers on average, yet its standard generation loop decodes 14.6--21.0% more slowly than the base model. We present vSkipper, a virtualization layer that makes dynamic layer skippers pluggable in serving engines while preserving continuous batching, fixed-shape batches, paged KV caching, and captured decode graphs. At each routed layer, vSkipper groups tokens by the skipper's decision and uses routed execution only when predicted to be profitable. We implement vSkipper in SGLang and evaluate the released FlexiDepth checkpoint against upstream SGLang under identical prompts, arrivals, output lengths, and launch settings. At the kne

---

### [106] From Semantic Decisions to Feasible Trajectories: Self-Evolving LLM-Guided Optimal Control for Narrow-Space Parking

**链接**: https://arxiv.org/abs/2609.24631
**作者**: Zhengbao Yao, Yuanfu Luo, Kehan Xue
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Authority Before Utility: Non-Compensatory Control for Persistent LLM Memory

**链接**: https://arxiv.org/abs/2609.37474
**作者**: Wesley Shu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory creates a control problem that retrieval relevance alone does not solve: a memory can remain highly useful after an update, deletion, or revocation makes it inadmissible for the current answer. We formalize this as a separation between utility and authority. A fixed finite penalty applied to an unnormalized utility score cannot guarantee exclusion under arbitrary positive-affine reparameterization of that score; by contrast, rank-normalized compensation is scale-invariant and therefore forms a stronger empirical comparator. Our prospectively frozen TIDE/LongMemEval primary was quarantined before a valid HELDOUT comparison because the materialized TIDE adapter conflated historical age with query-relative inadmissibility and the aligned LongMemEval split left no DEV set for the predeclared penalty selection. We therefore report a post-primary replacement diagnostic on Memora Remembering, where update/delete operations provide item-level forgetting state. On Qwen3-8B, DE

---

### [108] OptiCom : A Unified Framework for State-Conditioned Composition in LLM-Driven Optimization

**链接**: https://arxiv.org/abs/2609.37221
**作者**: Chenxing Wei, Sichen Liu, Lizhao Liu, Ningyuan Sun, Chen Bingzhou, Ying He 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed to solve complex scientific and practical problems via iterative optimization. However, dynamically coordinating diverse search mechanisms as candidate quality, failure modes, and resource budgets evolve remains a critical open challenge. Targeted empirical diagnostics reveal that mechanism effectiveness is highly state-dependent. Motivated by this, we analyze how individual decisions drive final outcomes, decomposing the expected terminal improvement under a shared budget into cumulative decision opportunities minus cumulative selection losses. Guided by this opportunity-loss theoretical foundation, we propose OptiCom, a unified framework that represents LLM-driven optimizers within a shared configuration space: C=(A,Q,O,E,M,S), corresponding to artifact, query, operator, evaluation, memory, and strategy. Operating within this space, a fast LLM-based Optimization Controller dynamically composes immediate mechanisms through structu

---

### [109] Binarization Flattens the Score Space

**链接**: https://arxiv.org/abs/2609.35797
**作者**: Jacob Cole
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) judges are often used as rewards to train policies on objectives that deterministic verifiers cannot capture. However, these rewards are often collapsed to pass/fail ({0, 1}), which reports the verdict but not how well a response met each criterion. We model each pass/fail verdict as a score on an unreported scale, compared with one cutoff. A stretch of that scale moves every score proportionally toward or away from the cutoff, but never across it, so no verdict changes. A policy is therefore free to apply any stretch without changing anything the panel reports. Under a joint-Gaussian model, a third grade adds a second threshold and removes this affine stretch ambiguity. On MATH and SciBench outputs from one seven-criterion judge, all 14 constructed criterionwise stretches were invisible after binarization but visible with three grades. At $n=1{,}024$, a test given both population laws had at least 96.5% power at a $1.5\times$ stress. Retaining grades closes 

---

### [110] Mubric: Mutation Testing-Guided Rubric Generation for LLM Evaluation

**链接**: https://arxiv.org/abs/2609.37322
**作者**: Jiayuxuan Yang, Jie M. Zhang, Yiling Lou, Zhenpeng Chen
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based evaluation is widely used to assess LLM-based systems by decomposing response quality into task-specific scoring criteria. However, automatically generating rubrics that reliably capture task-specific quality requirements remains challenging. We introduce Mubric, a mutation testing-guided approach to rubric generation. Mutation testing, a classic software testing methodology, evaluates a test suite by injecting faults into programs and checking whether the tests detect them. We draw an analogy between test suites and rubrics: if a rubric captures an important quality requirement, introducing a corresponding defect into an otherwise high-quality response should reduce its score. Mubric first mines common defects from real pairs of preferred and dispreferred responses and abstracts these defects into reusable mutation operators, each specifying how to introduce a particular type of response defect. For a new task, it applies relevant operators to a reference response, checks

---

### [111] Zero Sum SVD: Balancing Loss Sensitivity for Low Rank LLM Compression

**链接**: https://arxiv.org/abs/2602.02848
**作者**: Ali Abbasi, Chayne Thrash, Haoran Qin, Shansita Sharma, Sepehr Seifi, Soheil Kolouri
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Scepsy: Serving Agentic Workflows Using Aggregate LLM Pipelines

**链接**: https://arxiv.org/abs/2604.15186
**作者**: Otto White, Marcel Wagenl\"ander, Britannio Jarrett, Xijin Zhou, Yanda Tao, Pedro Silvestre 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Accessible, but Not Adopted: Increasing LLM Adoption among First-generation, Low-income (FGLI) College Students beyond Expanding Access

**链接**: https://arxiv.org/abs/2609.36129
**作者**: Hyungsik Kim
**来源**: cs.HC cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly positioned as a force to empower underserved communities, and significant efforts are being made to expand access. Yet, access alone does not equate to meaningful adoption. First, even if a system is accessible, it won't be adopted if users are not willing to adopt it. Second, even if an LLM system is superficially adopted, the heterogeneity of LLM tools means that LLM adoption can be further deepened. Closing this access-adoption gap is critical to ensuring that the full social potential of LLM is not only accessible but fully realised. Drawing on 61 interviews (15 long-form semi-structured interviews with first-generation, low-income college (FGLI) students, 3 non-FGLI students, 3 FGLI program directors, and 40 intercept interviews), this paper examines the access-adoption gap in first-generation, low-income student communities. This paper a) finds that while FGLI students have adopted LLM systems, their depth of LLM tool usage is limited

---

### [114] EnterpriseBench: Benchmarking LLM Agents on Enterprise-Level Strategic Reasoning and Decision-Making

**链接**: https://arxiv.org/abs/2609.37658
**作者**: Min Yang, Yichen Pan, Jinghua Piao, Dandan Song, Yongshun Gong, Yong Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly expected to support enterprise workflows, where tasks often involve missing information, uncertainty, feedback, and long-term trade-offs. However, existing enterprise and financial benchmarks mainly test static capabilities such as information extraction, numerical calculation, domain knowledge, and financial QA, leaving interactive and long-horizon decision-making underexplored. To bridge this gap, we introduce EnterpriseBench, a benchmark that evaluates LLM agents across this spectrum, from static question answering to dynamic decision-making. Specifically, EnterpriseBench reorganizes existing enterprise and financial QA datasets into a unified foundational suite annotated by capability and difficulty, and introduces three professional interactive settings: Consulting, based on management-consulting-style business cases for client problem diagnosis through multi-turn information seeking; the Beer Game, adapted from a classic supply-chain management simulat

---

### [115] LLM Serving Optimization with Variable Prefill and Decode Lengths

**链接**: https://arxiv.org/abs/2508.06133
**作者**: Meixuan Wang, Yinyu Ye, Zijie Zhou
**来源**: math.OC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Do Proactive Agents Need an LLM to Decide When to Act?

**链接**: https://arxiv.org/abs/2605.30152
**作者**: Xiaoze Liu, Ruowang Zhang, Amir H. Abdi, Michel Galley, Zhikai Chen, Siheng Xiong 等 (8 人)
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] Can We Still Trust Disaster Social Sensing? Empirical Evidence on Detecting AI-Generated Social Media Posts

**链接**: https://arxiv.org/abs/2609.35821
**作者**: Xiaoshan Zhou and Zaifu Zhan
**来源**: cs.CL cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disaster social sensing converts public social-media posts into evidence for situational awareness and humanitarian needs, but generative artificial intelligence (AI) can produce plausible messages that resemble eyewitness reports. This study investigates whether text-based AI detectors can reliably distinguish human-authored from AI-generated disaster posts. We construct a dataset of 12,000 texts organised into 3,000 matched semantic units from nine disasters: original human posts (H0), minimally LLM-proofread human posts (H1), factual AI-generated posts based on the same verified facts (A0), and affectively framed versions of those AI posts (A1). A separate 6,000-text corpus from 42 events supports model selection and threshold calibration. We evaluate OSM-Det, Fast-DetectGPT, Binoculars, and direct large language model (LLM) judges across five model families, then test disaster-domain calibration, a frozen-encoder linear readout, paired transformation sensitivity, and dataset artifa

---

### [118] Reliable but Design-Sensitive: Instrument Uncertainty in LLM Annotation

**链接**: https://arxiv.org/abs/2609.35824
**作者**: Thomas Reiter, Christoph Kern, Fedor Miasnikov, Sofiia Nikolenko, Rob Chew, Stephanie Eckman 等 (7 人)
**来源**: cs.CL stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can give reliable labels under one setup yet change those labels when researchers make other reasonable design choices. We tested seven LLMs, 12 task designs, three independent runs, and 3,000 tweets labeled for offensive language and hate speech. Repeating the same model and task design produced high agreement (median Fleiss' $\kappa = 0.91$). Agreement fell when we changed the task design for the same tweets (median Cohen's $\kappa = 0.76$). Task design and model choice increased the variance of estimated prevalence by factors of 76.7 for offensive language and 110.6 for hate speech compared with sampling variance alone. Variation across LLM task designs reached 560-572 basis points, compared with 270-331 basis points across five human instrument versions. Confidence scores did not solve this problem. They tracked repeated model outputs more closely than agreement with human labels, and grouping six tweets in one prompt lowered mean offensive-language con

---

### [119] AnthroDial: Benchmarking LLM Anthropomorphism in Autonomous Social Interaction

**链接**: https://arxiv.org/abs/2609.37853
**作者**: Wentao Liu, Xi Chen, Siyu Song, Biao Yuan, Yu Zhang, Zhou Zhuotong 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as social agents, yet credible human-like interaction requires more than fluent responses or persona consistency. Agents must autonomously decide whether, when, and how to communicate while adapting to evolving contexts, goals, and relationships. Existing research, however, lacks a unified approach to enabling, evaluating, and improving such capabilities in continuous, open-ended interaction. We introduce AnthroDial, a unified framework for developing anthropomorphic social agents from three complementary aspects: MindFlow, a lightweight interaction harness that enables autonomous, asynchronous, and adaptive communication through a dynamic Mind Buffer; CAPS-Eval, a theory-grounded framework for evaluating cognitive, affective, and behavioral dimensions of anthropomorphic interaction; and a scalable training paradigm that combines SEEDS for environment expansion with DiAPO for adaptive capability optimization. We further construct e

---

### [120] Is Human-Readable Text Necessary for Effective LLM Fine-Tuning?

**链接**: https://arxiv.org/abs/2609.35868
**作者**: Jinhao Zhang, Zeyu Liu, Zicheng Yan, Yunquan Zhang, Daning Cheng, Song Tang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Is human readability necessary for effective fine-tuning of large language models? We investigate whether model-conditioned training representations can preserve or improve adaptation utility without requiring a human-readable textual form. We propose Desired-Update-Aligned Synthetic Data (DASA), which uses activation-gradient feedback from a frozen reference model to guide the optimization of continuous synthetic input embeddings. Inspired by the role of activation gradients in local risk reduction, DASA targets useful adaptation updates rather than source-text reconstruction or linguistic fluency. The resulting embeddings are used directly for downstream fine-tuning; discrete token projections are employed only for qualitative inspection. Experiments on six models from the Llama and Qwen families, ranging from 1B to 32B parameters, cover six benchmarks spanning knowledge, mathematical reasoning, code generation, and commonsense reasoning. Under matched LoRA adaptation settings, DASA 

---

### [121] Concealing LLM-Based Multi-Agent Topology via Phantom Structure Injection

**链接**: https://arxiv.org/abs/2609.37567
**作者**: Longzhu He, Zelang Wen, Xinfeng Li, Sen Su, XiaoFeng Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Driven by the rapid advancement of large language models (LLMs), LLM-based multi-agent systems (MAS) have emerged as a powerful paradigm for collaborative reasoning over complex tasks. A key design element of MAS is the communication topology, which governs information flow among agents and often encodes proprietary knowledge about the system architecture. However, recent work has shown that such topologies can be inferred even in black-box settings by exploiting semantic dependencies in observable reasoning traces, posing significant risks of intellectual property leakage and exposure of system vulnerabilities. To address this threat, we propose MIRAGE, a topology-concealment framework that preserves the genuine communication topology for task execution while shaping adversary-facing semantic evidence toward a carefully constructed phantom topology. Specifically, MIRAGE operates in three stages: (1) phantom topology synthesis, (2) semantic edge realization, and (3) protected MAS execu

---

### [122] Trojan Hippo Bench: A Dynamic Benchmark for Persistent Memory Attacks and Defenses in LLM Agents

**链接**: https://arxiv.org/abs/2605.01970
**作者**: Debeshee Das, Julien Piet, Darya Kaviani, Luca Beurer-Kellner, Florian Tram\`er, David Wagner
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] SPLASH: Switching Parallel Layouts of Attention with Seamless Handoff for LLM Serving

**链接**: https://arxiv.org/abs/2609.37626
**作者**: Chuan Liu, Shuoming Zhang, Zhicheng Li, Qianqi Sun, Ruiyuan Xu, Qiuchu Yu 等 (9 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> No single way of parallelizing attention serves large language models well under all loads. Low concurrency favors tensor parallelism, many independent requests favor data-parallel attention, and long prompts favor context parallelism. Reasoning, agentic, and RL-rollout workloads make a fixed choice untenable: a batch that begins as many short requests ends as a few very long ones, so the best layout changes while the same requests run. Serving engines nevertheless fix one layout at launch, because changing it has meant draining requests and restarting workers. We present SPLASH, a serving system that switches the parallel layout of attention while requests are running. It builds on one observation: modern attention, with few or no KV heads, decouples where a request's KV cache lives from how attention weights are sharded. This has two consequences. First, layouts differ only in who owns the weights and the cache, and most of that state already sits where the next layout needs it; SPLA

---

### [124] EvoMO-SR: Multiobjective LLM-based Evolution of Symbolic Expressions with substructure guidance

**链接**: https://arxiv.org/abs/2609.36187
**作者**: Cristina Rossetti, Anna V. Kononova, Thomas B\"ack, Fei Liu, Niki Van Stein
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic Regression (SR) is a data-driven method for scientific discovery which searches for interpretable analytical relationships within data. Recently, Large Language Models (LLMs) have also had a significant impact on scientific discovery, enabling the automation of various stages of the process. For these reasons, the possibility of harnessing the embedded scientific knowledge and programming capabilities of LLMs to solve SR tasks has emerged, showing promising performance compared with traditional methods. We propose EvoMO-SR, a novel LLM-driven SR framework in which the LLM generates equation skeletons, with their coefficients fitted separately by an external optimizer. The framework includes a multi-objective survival selection which controls bloating by balancing accuracy and complexity, and a substructure guidance mechanism which mutates expressions with candidate reusable building blocks. EvoMO-SR achieves the best accuracy in seven of the eight in-domain and out-of-domain s

---

### [125] Reconstructing Implicit Scientific Knowledge: Evaluating LLM Agents through End-to-End Reproduction of Astronomy

**链接**: https://arxiv.org/abs/2609.35900
**作者**: Yuehui Wang, Xinyu Qi, Guirong Xue, Cheng Wang, Yangbin Xie, Xiaoyu Tang 等 (7 人)
**来源**: astro-ph.IM astro-ph.GA cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of large language models (LLMs) into scientific workflows is accelerating, yet their ability to reconstruct the reasoning underlying published research remains unexplored. Papers specify explicit procedures while leaving many methodological dependencies-data selection, calibration corrections, priors, and domain assumptions-implicit. This ambiguity complicates the evaluation of LLM-based agents, since a failure to reproduce a result may reflect either limitations of the agent or underspecification in the source. We present a framework that evaluates agents through end-to-end reproduction, separating execution from verification and computational failure from methodological ambiguity. We apply it to fourteen astronomy studies: a case study from The Astrophysical Journal and thirteen papers published in Nature. Eleven of the thirteen contained an ambiguity preventing a uniquely specified reproduction path. In a controlled case study, twelve predefined paths, a 3x2x2 sensit

---

### [126] Replay the Curvature: Accurate and Scalable NVFP4 Quantization for Large Language Model Inference

**链接**: https://arxiv.org/abs/2609.36654
**作者**: Ruiyi Ding, Jie Li, Kang He, Ziyan Liu, Chengru Song, Yuedong Xu 等 (7 人)
**来源**: cs.LG cs.CL cs.DC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models make weight storage and memory traffic major inference costs, motivating low-precision formats that represent each weight with only a few bits. Such formats use a scale to map floating-point values into a small codebook; NVFP4 improves local range utilization by letting every 16 E2M1 weights share an E4M3 block scale. Choosing that scale is difficult in GPTQ because quantizing one column updates those that follow, so evaluating a block independently can misestimate its final reconstruction error. Large models pose a second challenge: full-precision weights, calibration activations, and second-order state cannot all remain on one accelerator, while assigning complete layers to devices leaves each time-consuming layer solve serial. We introduce \emph{Schur Replay}, a scale-selection algorithm that reproduces the GPTQ updates caused by each block scale and scores the resulting block error after accounting for compensation from unquantized columns. Separately, our exe

---

### [127] Harnessing LLM Agents with Skill Programs

**链接**: https://arxiv.org/abs/2605.17734
**作者**: Hongjun Liu, Yifei Ming, Shafiq Joty, Chen Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] Eternal Sunshine of the Spotless Mind: Systematically Erasing LLM's Memories

**链接**: https://arxiv.org/abs/2609.36414
**作者**: Olga Ohrimenko
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We consider persistent LLMs that accumulate memories of their interactions with a user over time. Such LLMs maintain memories using external storage, which they can query to overcome the limitations of a fixed context window. Such systems have numerous practical applications, as they can draw on all past interactions when responding to user queries. In this paper, we ask whether LLMs can forget information shared with them upon a user's request. We find that current LLMs fail to delete such information---even when they claim to have forgotten it and even when operating with a limited context. To this end, we consider a new direction of study: Deletion of LLM Memories. We show that naively removing messages that match a user's deletion request is insufficient, since conversations naturally introduce message dependencies that cause information to persist. To correctly handle deletion requests, we propose the DeLLM framework. It dynamically constructs relevant context for each LLM query a

---

### [129] When Do Agent Loops Mistake Stagnation for Progress? Self-Evaluation Bias and Externally Grounded Verification in Long-Running Autonomous LLM Agent Loops

**链接**: https://arxiv.org/abs/2607.25152
**作者**: Hyundoo Park, Byungho Choi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] SimpleEvol: An Agent-Loop Framework for LLM-Driven Automated Heuristic Design with Minimal Human Priors

**链接**: https://arxiv.org/abs/2609.37172
**作者**: Jianghan Zhu, Cong Zhang, Rongjie Zhu, Chi Zhang, Zhiguang Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have emerged as powerful tools for automated heuristic design (AHD), enabling iterative generation and refinement of heuristics. However, the dominant paradigm embeds LLMs as narrow, fixed components, such as crossover or mutation, within heavily hand-engineered evolutionary frameworks. We argue this misapprehends LLMs. It treats them as specialized tools rather than general reasoners, constrains them to low-level operations, and underutilizes their autonomy. Moreover, the extensive human priors in these frameworks violate the bitter lesson principle that general methods scaling with computation surpass hand-crafted solutions. This raises a key question: which AHD framework designs best convert stronger LLM capabilities into better heuristics? To address this, we propose metrics for LLM-driven AHD framework handcraftedness (AHI) and intelligence conversion efficiency (ICE). Evaluating ten LLMs across three challenging combinatorial optimization problems, we

---

### [131] Teaching LLMs to Generate Challenging MILP Instances via Solver Feedback

**链接**: https://arxiv.org/abs/2609.37356
**作者**: Jitin Singla, Parikshit Pareek, Pratik Jawanpuria, and Parag Singla
**来源**: cs.AI math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating optimization instances that are both feasible and computationally challenging is crucial for benchmarking solvers and training learning-based optimization algorithms. Existing non-LLM generators rely on seed instances or parameter tuning, resulting in high test-time computational cost, while existing LLM generators lack explicit hardness measures. Recent reinforcement learning methods with verifier feedback evaluate only binary correctness, which is misaligned with generating challenging problems. We note that an optimization solver reports the cost of solving at several stages of its pipeline, and leverage this to design a reward that scores both the solvability and the hardness of generated problems, measured by branch-and-bound nodes and post-cut relaxation gaps. Our key idea is a challenger-solver asymmetric self-play approach, where an LLM challenger generates progressively harder instances and the solver verifies feasibility and hardness, so no seed or training MILP in

---

### [132] Dyad: Extending Large Language Models with Native Typed Decision-Making

**链接**: https://arxiv.org/abs/2609.36116
**作者**: Yundaichuan Zhan, Weishi Wang, Wenbiao Liu, Daniel Dahlmeier, Chengwei Qin, Juncheng Li 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how to build more capable general-purpose agents by extending large language models (LLMs) with native typed decision-making. We introduce Dyad, an architecture that augments a pretrained LLM with an environment-conditioned action encoder that embeds each candidate action description in parallel, then scores these embeddings against the LLM's internal state to yield a distribution over typed actions. By factorizing decision-making into representations of the evolving interaction state and environment-specific action semantics, Dyad introduces an inductive bias for learning reusable representations while keeping action scoring efficient even as the action space grows. We investigate two complementary reinforcement learning settings driven by environment interaction. With the LLM frozen, training the action encoder alone achieves consistent gains across four unseen environments, enabling modular adaptation without modifying any LLM parameters. Jointly optimizing both components 

---

### [133] ContextRender: From Execution Dependencies to Agent Context

**链接**: https://arxiv.org/abs/2609.37743
**作者**: Savini Kashmira, Jayanaka L. Dantanarayana, Lingjia Tang, Jason Mars
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents performing long-horizon tasks accumulate tool results that later steps may need. Passing the full history to every invocation is costly even when it fits within the context window, while reducing it risks omitting needed information. Existing context management methods can overlook how earlier tool results are used in subsequent execution, leaving needed information out of context. We introduce ContextRender, which manages context through a persistent graph of execution dependencies. We develop Tool-Flow Analysis to track how later operations reuse information from earlier tool results, providing a signal called observed reuse. A renderer combines this signal with recency and semantic relevance to select results within a fixed history budget, retaining omitted results for later use. Across AppWorld and 8-objective QA with three execution models, ContextRender outperforms the evaluated context management baselines using a 6K history budget, well below the models' maximum cont

---

### [134] OTROPE: Optimal Transport-based Robust Off-policy Evaluation for Large Language Models

**链接**: https://arxiv.org/abs/2609.36264
**作者**: Liner Xiang, Wenbo Zhang, Hengrui Cai
**来源**: cs.AI cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable evaluation of large language models (LLMs) is essential for their development and deployment, yet is often costly, risky, and difficult to perform safely online. We study off-policy evaluation for LLMs, where limited human-labeled data from a behavior model are used to evaluate a newer target LLM. This setting is challenging because labels are scarce, behavior--target distribution shift is common, and response likelihoods are often unavailable for black-box LLMs. We propose the Optimal Transport-based Robust Off-Policy Evaluation (OTROPE), a likelihood-free evaluation that performs distributional correction in a semantic space via optimal transport to align labeled behavior-policy samples with unlabeled target-policy samples. OTROPE combines corrected human-labeled residuals with proxy predictors, yielding a doubly robust-style evaluation without behavior-policy modeling or density-ratio estimation. We theoretically characterize why baseline evaluators fail under LLM distribut

---

### [135] AnyAct: Universal Action for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2609.37025
**作者**: Lingrui Xu, Yangqin Jiang, Jiachang Zhang, Xubin Ren, Chao Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) advance, AI agents are increasingly deployed in open-world environments to tackle complex sequential tasks (e.g., document processing, cross-application collaboration), relying heavily on actions ranging from GUI operations to semantic APIs. However, three core challenges persist: the "scale dilemma" of massive tool ecosystems exceeding LLM context windows, the "non-stationarity" of tool quality due to updates or outages, and the "heterogeneity" of feedback formats (pixels, text, structured data) creating information silos. To address these, we propose AnyAct, a universal action layer that unifies available capabilities into a self-evolving action space, enabling agents to operate efficiently and reliably in large-scale, dynamic tool ecosystems. AnyAct's core design focuses on two objectives: constructing this action space via hierarchical progressive retrieval (filtering task-relevant actions) and test-time reliability evolution (pruning unreliable acti

---

### [136] ARC-KV: Amortizing Anchor Search for Reconstruction-Based KV Cache Compaction

**链接**: https://arxiv.org/abs/2609.36835
**作者**: Zheyu Shen, Guanhua Wang, Dezhan Tu, Mengchi Zhang, Yanjia Li, Adnan Aziz 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context large language model inference is bottlenecked by KV caches that grow linearly with sequence length. This burden is especially severe for long, reusable context prefixes, whose cache must serve many downstream queries. Reconstruction-based methods such as Attention Matching achieve strong downstream task performance with compact KV caches. However, iterative anchor search dominates the compaction cost of OMP-based Attention Matching. This motivates our selective amortization principle of learning a reusable anchor-selection policy across contexts while retaining context-specific reconstruction. In this work, we propose ARC-KV, a novel reconstruction-based KV cache compaction method that follows this principle. To this end, we first train a value-aware indexer to select real-key anchors in a single scoring pass. ARC-KV then applies convex-hull-constrained key merging and fits an attention-mass bias and compact values against the full cache. At inference time, ARC-KV builds 

---

### [137] Layer-Informed Fine-Tuning via Three-Stage Functional Segmentation of LLMs

**链接**: https://arxiv.org/abs/2609.38027
**作者**: Junning Shao, Siwei Wang, Zhixuan Fang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, the performance of large language models (LLMs) on reasoning tasks has been remarkable, even surpassing human capabilities on various benchmarks. However, there remains a lack of clear understanding in the academic community regarding how the structure and internal parameters of LLMs progressively solve complex reasoning problems. In this study, we investigate the inference process of LLMs on cross-linguistic materials and propose the hypothesis that LLM layers exhibit a structured division of labor across conceptualization, reasoning, and textualization. Based on this hypothesis, we introduce a bottleneck identification mechanism using sensitivity analysis to pinpoint the most critical functional stage for a specific task. Leveraging this insight, we propose a novel approach, Layer-Informed Fine-Tuning (LIFT), which achieves efficient and effective fine-tuning by selectively updating only these functionally critical layers. We then conduct extensive experiments to sho

---

### [138] Large Language Models Exhibit Human-Like Bayesian Hypocrisy

**链接**: https://arxiv.org/abs/2609.35779
**作者**: Nykko Vitali, Mahzarin R. Banaji
**来源**: cs.HC cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given recent achievements of large language models (LLMs), frontier models are expected to perform well on Bayesian reasoning tasks, at least as well as humans. Furthermore, there is no reason to expect that LLMs will condemn others who offer those very same Bayesian judgments, a fallibility observed in human decision-making (Cao, et al., 2019). In 5 experiments with 48 experimental conditions employing over 5,000 trials, GPT-4o and Claude 3.7 Sonnet were tested on two variations of a Bayesian reasoning task. We also assessed LLM evaluation of the competence and morality of a hypothetical person who had offered the same reasoning task as them. LLMs hovered near human performance on the Bayesian task, though their reasoning was more rule-based and rigid. Surprisingly, like humans but to a greater extent, LLMs also demonstrated the same hypocrisy in condemning others who, like them, had deployed Bayes' rule. In demonstrating Bayesian hypocrisy, LLMs highlight a humanlike error of a disso

---

### [139] Critical Thinking with Generative AI: A Constraint-First Design Pilot of a Thinking-Partner Intervention

**链接**: https://arxiv.org/abs/2609.38029
**作者**: Fatima Tuz Zahra, Jiangen He, David M. Bowers, Wei Wang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI (GenAI) tools entered higher education classrooms faster than the field was able to study their effects on learning. One concern is that GenAI may displace the critical thinking and AI literacy that students will need after graduation. This paper reports a Design-Based Research pilot of a GenAI-assisted critical thinking framework, in which ChatGPT was used as a thinking partner in an undergraduate research methods and statistics course during Spring 2025 (N = 14). The mixed-methods design combined pre- and post-intervention measures of statistical learning (AASCDM), AI literacy (MAILS), and critical thinking (WGCTA) with instructor field notes, student artifacts, and student-AI interaction logs. Pre-post tests showed gains on every AASCDM dimension and on eight of nine MAILS dimensions, while WGCTA percentiles did not change. Qualitative analysis identified four themes: the ways students positioned the LLM (as answer generator, validator, or co-thinker); the depth of stu

---

### [140] Follow the Entities: A Corpus Map for Agentic Search

**链接**: https://arxiv.org/abs/2609.37226
**作者**: Soyeong Jeong, Sujay Kumar Jauhar, Sung Ju Hwang, Andrew Joohun Nam
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Answering questions and completing tasks over large document collections often requires connecting evidence spread across multiple documents, such as a project's approval recorded in one, its requirements in another, and its latest status in a third. Recent LLM agents approach this by iteratively searching the full corpus rather than reading only a fixed set of top-ranked documents. However, when the corpus is exposed only as a flat collection of files, a relevant document gives no indication of how it relates to others, so the agent must rediscover these relationships for every query, often missing complementary evidence while simultaneously consuming substantial additional tokens. To address this, we introduce CorpusMap, a navigation layer that organizes the corpus around its recurring entities, which are identifiable from the documents themselves and can link a single document to many others across sources. Specifically, CorpusMap represents each recurring entity as an Entity Page t

---

### [141] From Lexical Baselines to Agentic Retrieval-Augmented Generation: Structured Skill and Responsibility-Level Extraction with the SFIA Framework

**链接**: https://arxiv.org/abs/2609.35806
**作者**: Ranuga Disansa, U. S. Samarasinghe, Lasith Gunawardena
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated skill extraction underpins workforce planning, yet most systems represent skills as flat labels with no notion of the responsibility level at which a skill is practiced. The Skills Framework for the Information Age (SFIA) captures exactly this dimension, defining 147 professional skills across seven responsibility levels, but no automated LLM-based extraction targeting SFIA has been reported. We formalize the task as structured prediction of (skill, level) pairs from free text and ask three questions: how accurately can text be mapped onto SFIA's closed vocabulary, which strategies reliably predict the level alongside the skill, and do agentic designs improve on simpler retrieval and prompting? We evaluate five strategies (a lexical baseline, dense retrieval with LLM reranking, a zero-shot schema-constrained LLM, single-agent agentic RAG, and a three-agent retriever--matcher--verifier crew) against expert-mapped European ICT role profiles, all drawing on an SFIA~9 corpus buil

---

### [142] Explore Broadly, Reason Sharply: Push Small Models toward the Frontier via Sampling

**链接**: https://arxiv.org/abs/2609.38104
**作者**: Panagiotis Theodoropoulos, Nan Jiang, Xintong Duan, Ali Hasan, Yuriy Nevmyvaka, Evangelos A. Theodorou 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Power-sharpened sampling is an inference-time alternative to reinforcement-learning (RL) post-training for enhancing reasoning in large language models (LLMs). High-probability sequences are amplified under the base model without parameter updates or external rewards, avoiding the costly optimization and jagged generalization of RL. However, this approach faces a fundamental exploration--exploitation trade-off, as % strong sharpening restricts exploration, trapping samplers in plausible but incorrect reasoning trajectories, whereas weak sharpening leaves the answer distribution diffuse. To resolve this trade-off, we introduce \textbf{Parallel Power Tempering (PPT)}, instantiating power-sharpened LLM sampling via parallel tempering. Running multiple \emph{interacting} replicas in parallel at different sharpening levels allows lower-power replicas to explore diverse reasoning trajectories and higher-power chains to further exploit higher-likelihood responses favored by the sharpened targ

---

### [143] Sieve and Sage: Efficient Distraction Filtering for Reliable RALM Abstention

**链接**: https://arxiv.org/abs/2609.35794
**作者**: Jongbin Won, Sung Geun An, Jay-yoon Lee
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Just as Socrates recognized the limits of his own knowledge, Retrieval-Augmented Language Models (RALMs) should learn to abstain when the retrieved evidence cannot support a reliable response. Existing approaches largely rely on monolithic LLMs to handle heterogeneous retrieval failures in a single step, resulting in limited abstention performance and high computational costs. We instead decompose retrieval failures into two distinct states: (i) the unanswerable state, where the required evidence is absent, and (ii) the distracted state, where relevant evidence is mixed with conflicting, negated, or adversarial information. Based on this decomposition, we introduce a lightweight module (Sieve) that screens retrieved document sets for distracting evidence before invoking a costly LLM (Sage) for grounded generation and abstention. Evaluated across both general and high-stakes expert domains, our Sieve and Sage framework preemptively detects distracting noise, improving system accuracy by

---

### [144] Targeting Pivotal Decisions for Credit Assignment in Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.36178
**作者**: Dongwon Jung, Hemanth Neelgund Ramesh, Yifan Wang, Xiaomin Li, Yuexing Hao, Yu Hu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group Relative Policy Optimization (GRPO) has become a promising approach for training large language model agents. However, its uniform assignment of trajectory-level advantages to all policy tokens fails to distinguish consequential decisions from less relevant ones, obscuring which intermediate decisions contributed to success. We introduce ProVer, a framework that targets potentially pivotal decisions for fine-grained credit assignment in agentic reinforcement learning. Given a rollout group, an agentic judge contrasts successful and failed trajectories to propose a segment potentially responsible for their divergent outcomes. Rather than directly trusting the judge's assessment, ProVer verifies the proposed segment by estimating its advantage from the difference in terminal success rates between current-policy continuations sampled before and after the segment. Positive estimates are then incorporated into the GRPO advantages of policy tokens within the proposed segment. By using 

---

### [145] CompOrca: Corpus-Scale Compliance Labelling of Instruction-Tuning Data

**链接**: https://arxiv.org/abs/2609.37807
**作者**: Philipp E. Glass, Alina Miron
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Studying how fine-tuning shapes refusal and noncompliance behaviour requires identifying training examples that refuse, evade or otherwise fail to fulfil the requested task. But existing annotation covers evaluation sets of a few thousand prompts at most. We present CompOrca, a compliance labelling over the entirety of the 4,233,923-example OpenOrca corpus. Every example was classified as compliant or noncompliant by five independent passes of an open-weight LLM judge (LongCat-2.0, 1.6T parameters), and the corpus is released as unanimous compliance (94.75%), unanimous noncompliance (1.28%), and nonunanimous rows (3.97%) along with the raw vote counts. A single pass flags 2.7-3.2% of the corpus as noncompliant, while only 1.28% is flagged by all five, allowing for filtering the most ambiguous samples. Against 450 human-annotated examples, 150 of them annotated twice (human-human $\kappa = 0.93$), the unanimous compliance and noncompliance labels are 97.3% and 86.7% precise, the latter 

---

### [146] BrainNet Studio: A Unified Toolkit for Brain Network Construction, Intelligent Analysis, and Visualization

**链接**: https://arxiv.org/abs/2609.37956
**作者**: Xiwei Zeng, Shengrong Li, Yiheng Liu, Chunwei Tian, Daoqiang Zhang, Qi Zhu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain networks characterize structural and functional relationships among brain regions and support research on cognition, brain disorders, and brain-computer interfaces. Their time-varying topology and higher-order spatiotemporal dependencies are not adequately represented by conventional static networks. Existing tools primarily focus on static connectomes and provide limited integration of dynamic network modeling with modern graph and sequence learning methods. We present BrainNet Studio, an integrated toolkit for static and dynamic brain network analysis. It provides a unified workflow encompassing network construction, feature extraction, predictive modeling, candidate biomarker identification, visualization, and assisted interpretation. The toolkit integrates 27 algorithms, including deep learning, graph neural networks, and spatiotemporal sequence models, to support classification and the identification of discriminative brain regions and connections. A large language model gen

---

### [147] Memory Is a Derivation: The Distributed-Evidence Paradox in Long-Term Agents

**链接**: https://arxiv.org/abs/2609.36130
**作者**: Hongjun Liu, Chen Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents compress past interactions into persistent memories that may be reused as premises for later tasks. This creates a distinct derivation problem: whether the memory actually follows from what the interaction history supports. Relevant evidence may be scattered across earlier interactions, while compression can introduce relations or event status that the history never established. A valid memory may therefore appear unsupported because its citations omit relevant evidence, while individually supported facts may be composed into a stronger statement the history never established. We characterize this problem through three coupled requirements: (1) Evidence scope; (2) Compositional validity; (3) Admission reliability. We therefore ask whether the interaction history available at write time supports what enters persistent memory. We introduce DerivAudit, a framework for auditing whether a memory is actually supported by the history available when it was written. The 

---

### [148] Collective Regimes in Multi-Agent LLMs under Reasoning Effort and Communication Topology

**链接**: https://arxiv.org/abs/2609.35885
**作者**: Machiko Hirota, Akshara Nadayanur Sathis Kanna, Ujwal Kumar, Phan Xuan Tan
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are increasingly used for deliberation and evaluation, often under the assumption that greater peer interaction leads to more reliable consensus. Existing work largely evaluates these systems through final accuracy or aggregate agreement. However, such measures do not reveal how agreement is organized in the panel. In this paper, we study \(N=50\) stateless LLM agents that update their predictions from locally visible peers, and characterize their behavior using both global and local measurements of agreement. We identify three collective regimes: synchronised, twisted (locally ordered but globally incoherent) and chimera-like, where coherent and incoherent subpopulations coexist. Increasing reasoning effort in gpt-5-mini shifts panels from variable, often fragmented outcomes toward locally ordered twisted states, and a small follow-up shows such states can also form from permuted initial conditions, whereas increasing communication connectivity drives them towa

---

### [149] LLMs Learn to Evade Latent Monitors from Prior Feedback Alone

**链接**: https://arxiv.org/abs/2609.36490
**作者**: Hugo Lyons Keenan, Christopher Leckie, Sarah Erfani
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Latent space monitors aim to detect undesired behaviors in LLM agents by inspecting an agent's internal activations rather than its outputs. However, interactive monitoring creates a feedback channel where each verdict the monitor delivers leaks information to the model about how its internal states are being evaluated. We ask whether an agent can infer the monitor's decision rule from this feedback and then selectively edit its activations to evade detection. Unlike prior evasion attacks, the model is never explicitly told what the monitor detects. Surprisingly, off-the-shelf models already produce activation edits aligned with the monitored direction, but at insufficient magnitude for evasion. Simply scaling up these edits by a factor of 8 reduces the monitor's TPR from 100% to 27%. A rank-1 LoRA amplifies this behavior into effective evasion within the forward pass, reducing TPR further to 4% on held-out concept monitors while leaving other concepts at their normal detection rates. 

---

### [150] GeoOutageBench: Benchmarking Ambiguity-aware, Ontology-grounded Geospatiotemporal KGQA for Multimodal Power Outage and Resilience Analysis

**链接**: https://arxiv.org/abs/2609.36082
**作者**: Ethan D. Frakes, Amy Kvien, Rishabh Kundu, Redad Mehdi, Van D. Tran, Vibha S. Mandayam 等 (10 人)
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce GeoOutageBench, a benchmark for assessing LLM-based geospatiotemporal KGQA for multimodal outage and resilience analysis. Unlike existing KGQA benchmarks for Web knowledge, GeoOutageBench considers a spatiotemporal KG that integrates visual, textual, and structured data from outage records, remote sensing, weather observations, storm and power events, geographic entities, and domain ontologies. It provides a competency query taxonomy at different difficulty levels from spatiotemporal containment and proximity, spatiotemporal co-occurrence analysis, multimodal evidence, to hypothetical evaluation. Over multimodal KG and query classes, GeoOutageBench provides user-configurable evaluation of three important, highly coherent yet less studied tasks: (1) LLMs' understanding for ambiguous geospatiotemporal questions in terms of NL to SPARQL interpretation, (2) query-driven assessment of ontology utility, and (3) answer accuracy of multimodal KGQA retrieval. GeoOutageBench provide

---

### [151] When Does Correction Become Repair? Mechanistic Auditing of Internal Interventions in Tool-Using LLMs

**链接**: https://arxiv.org/abs/2609.36138
**作者**: Jiayi Li, Ruizhe Li
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Before invoking external tools, an agentic LLM must select among a K-way action space: executing a call, seeking clarification, answering directly, or declining. While internal activation steering can alter these pre-execution decisions, conventional aggregate metrics obscure where altered states land and what collateral damage they inflict. We present SAKIKO, an auditing framework that formalizes representation repair via directional error discovery, router-conditioned intervention, destination-resolved verification, and prospectively frozen statistical licensing. Across seven LLMs on When2Call and MetaTool, channel-keyed interventions induce direction-specific net gains in five models; across three sealed evaluations, none of 59 budget-matched random directions matches calibrated target gain. Crucially, destination auditing shows that behavioral movement does not equal repair: an intervention achieving +55 net gain corrupts over half of the baseline-correct decisions it touches, and 

---

### [152] Who Warmed the Archives? LLMs Overestimate Historical Warmth

**链接**: https://arxiv.org/abs/2609.37499
**作者**: Claudiu Creanga, Liviu P. Dinu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical archives are an under-used source for extending the instrumental climate record backward in time, and LLMs offer a way to extract the indices climatologists derive by hand. Beyond measuring how well systems extract this signal, we check whether their errors are safe to use for cross-century comparison, since a good correlation score does not rule out systematic, era-linked bias. Comparing lexical baselines, fine-tuned historical transformers, and LLM prompting on the Pfister temperature index across five centuries of German text, lexical methods beat every fine-tuned transformer we test, including one pretrained from scratch on historical German (r=-0.016). All six LLMs we test (Gemini 2.5 Flash, GPT-5-mini, DeepSeek v4 Flash, Claude Sonnet 4.6, Qwen3.7-Plus, Kimi-K2.6-Fast) show a warm bias that grows with calendar year, with the same sign in every model (slopes +0.13 to +0.34/century, p<0.01). The effect is modest in size (r-squared approx equal to 0.01 to 0.05) but consis

---

### [153] GenLimitLib: A Formal Library for Language Generation in the Limit and AI-Assisted Mathematical Research

**链接**: https://arxiv.org/abs/2609.36663
**作者**: Shuangping Li and Peng Zhang
**来源**: cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present GenLimitLib, a source-aligned Lean 4 library for language generation in the limit. Introduced by Kleinberg and Mullainathan at NeurIPS 2024, language generation in the limit studies a theoretical question motivated by LLMs: how to generate valid new strings from observed examples. This young and rapidly evolving field offers a natural testbed for studying large-scale formalization. GenLimitLib contains formal developments for 30 papers. It extracts shared definitions and reusable proof components while preserving paper-specific assumptions and statements, and records relationships across papers. In this way, GenLimitLib provides a concrete and structured view of the literature. We show through mathematical case studies and LLM experiments how our library can support both human mathematical research and AI-assisted research. Our Library: https://github.com/pengzhang91/generation-in-the-limit-lib.

---

### [154] HyperZip: Efficient Data Compression through Personalized Diffusion LLMs with Hypernetworks

**链接**: https://arxiv.org/abs/2609.36357
**作者**: Thai Nguyen, Khang Tran, NhatHai Phan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong potential for lossless data compression, but existing approaches are constrained by the high computational cost and low throughput of autoregressive decoding. We propose HyperZip, an efficient and scalable LLM-based compression framework that leverages diffusion-based LLMs (dLLMs) with Multi-Token Prediction (MTP) to accelerate LLM-based data compression processes. We identify a trade-off in diffusion-based compression, where increasing decoding throughput degrades the compression rate. To mitigate this trade-off, HyperZip employs a hypernetwork to generate data-specific updates from a context representation, adapting the dLLM to the target data without costly fine-tuning, resulting in a low compression rate and high throughput. Extensive experiments show that HyperZip achieves a superior trade-off between compression rate and speed compared with state-of-the-art baselines.

---

### [155] When Successful Memories Mislead Embodied Agents:Memory Adaption For Task-Conditioned Execution

**链接**: https://arxiv.org/abs/2609.35808
**作者**: Quanquan Li, Hongbo Zhang, Yihe Chi, Liuyang Song, Jingyu Li, Yuxiang Huang 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experience reuse can reduce repeated exploration in embodied agents, but a trajectory that succeeded previously may be unsuitable for the current execution context. Existing memory systems pri marily optimize construction and retrieval; semantic relevance and historical success therefore remain insufficient when retrieved ex perience contains incompatible actions or an inappropriate level of structure. We introduce Memory Adaptation for Task-Conditioned Execution (MATE), a deterministic post-retrieval procedure that converts trajectories into execution-oriented memory. MATE re moves obsolete control context, extracts condition-action-effect transitions, applies verified action normalization, selects a task dependent representation, and serializes the result under a fixed budget without additional LLM inference. On 134 ALFWorld tasks, MATE achieves task success rates of 81.3% and 93.3% with Qwen2.5-14B and 72B while using approximately one-tenth of the tokens required by raw trajectorie

---

### [156] Delta-Matching: Closing the Final Gap of Native 8-bit Training for LLMs

**链接**: https://arxiv.org/abs/2609.37852
**作者**: Haozhan Tang, Hao Kang, Han Cai, Song Han, Chenyan Xiong
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable FP8 attention remains a barrier to fully native 8-bit large language model training. We derive how forward-backward inconsistencies produce stale delta and empirically show how it distorts training dynamics. Our stale-delta hybrid runs show a modest loss gap at 569M parameters but substantial loss increases and downstream degradation at 1.67B and 5.29B. QK normalization, NoPE (no positional encoding), and lower-learning-rate context extension mitigate or delay degradation without eliminating it. This pattern suggests accumulated optimization error that smaller models and short runs can conceal. We propose Delta-Matching, proving that it restores the softmax gradient's zero-row-sum invariant under the stated numerical assumptions. It enables native block-scaled FP8 in every forward and backward attention-core matmul without architectural changes, smaller global batches, or auxiliary forward outputs. Across tested architectures, scales, and training stages, Delta-Matching matche

---

### [157] Harnessing Large Language Models to Compile Task-Relevant Context into Bayesian Optimisation

**链接**: https://arxiv.org/abs/2609.36788
**作者**: Zhongwei Yu, Sourabh Roy, Bin Cao, Xue Yan, Anjie Liu, and Jun Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Incorporating rich task-relevant context, such as domain knowledge and external observations, is a key capability yet remains challenging for Bayesian optimisation (BO). Recently, practitioners have started to use large language models (LLMs) to generate and execute BO programs through coding harnesses. In such emerging practices, the posterior belief is shaped not only by Bayesian inference but also by LLM-generated model and data artefacts, offering a flexible route for task context to enter BO as executable code. To study whether and how LLMs can be harnessed to compile diverse contextual signals for BO, we formulate LLM-compiled BO as generalised-context decision making. We propose HarBO, a BO-specialised harness that compiles generalised context into the core artefacts of standard BO through a validated multi-stage workflow. Our theory analyses the regret under imperfect compilation and the effect of adding new context. Across synthetic functions and real-world benchmarks, we find

---

### [158] SkillGym: Training Skill-Use Agents with Automatic Verifiable Environment Generation

**链接**: https://arxiv.org/abs/2609.37539
**作者**: Renxi Wang, Mingshan Hee, Fajri Koto, Timothy Baldwin, Haonan Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills equip LLM agents with professional knowledge and guidance to complete long-horizon and complex tasks. Although skills have been widely adopted in recent agent paradigms and harnesses, how to synthesize reliable training data and how to train agents for skill use remain underexplored. In this work, we propose SkillGym, an automatic pipeline to build verifiable environments, collect trajectories, and train skill-use agents. SkillGym first crawls a large volume of skills from the internet, then keeps those whose workflows can run reproducibly offline. A builder-reviewer pipeline is used to construct difficulty-controlled tasks, spanning four task types, each with a reference solution and an executable verifier. With this pipeline, we build 6.8k environments and collect 19k verified successful trajectories for supervised finetuning. Finetuning on these trajectories improves LLMs of different families and sizes, from 2B to 122B parameters across four skill-use benchmarks; Our Qwen3.5

---

### [159] Grounded Revision vs. Prior Injection: Probing Retrieval-Augmented Patent Claim Amendment

**链接**: https://arxiv.org/abs/2609.36550
**作者**: Josepha Michiko Leo, Hyun-seok Min, Yehoon Jang, Irvan Zidny, Jin-Woo Chung, Sungchul Choi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation is widely used in professional writing, yet whether retrieval grounds revision or merely injects templates is rarely tested where "correct" has a definable meaning. Patent claim amendment supplies that signal: the examiner names the attacked limitation and cites prior art, providing per-case ground truth. We release three artifacts: (i) a corpus of 7,385 USPTO prosecution cases with XML-aligned pre/post claims, rejection, and cited prior art; (ii) a seven-probe battery comparing random and structural-match retrieval as two policies under a fixed prompt scaffold; (iii) a deterministic five-channel metric (C1-C3 and C5 in main, C4 supplementary) requiring no LLM evaluation. Across 9,600 pre-registered calls on four frontier LLMs (Claude Sonnet 4, Claude Haiku 4.5, GPT-5.4, GPT-4o-mini), no tested model exhibits detectable classical prior-injection behavior; retrieval effects are small and direction-inconsistent between random and structural retrieval, and t

---

### [160] SCOUT: Synergizing Reasoning and Tool-Use for Computer-Use Safety

**链接**: https://arxiv.org/abs/2609.36201
**作者**: Jianxing Chen, Xiao Yu, Shipra Agrawal, Zhou Yu
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computer-use agents (CUAs), while capable of completing computer tasks in everyday and professional workflows, can cause unintended harm even under benign instructions and environments. However, detecting such harm remains challenging. First, it requires careful, task-specific reasoning: verifiers guided only by general safety criteria often overlook many important but subtle harmful behaviors. Second, it requires active investigation: past trajectory screenshots show what the agent did but not always what actually changed in the environment, so LLM-as-a-judge verifiers that rely on screenshots alone may be unable to determine the actual consequences of actions. To address these challenges, we introduce SCOUT, a two-stage agentic safety verifier that synergizes reasoning-intensive rubric generation with tool-intensive evidence gathering. First, our SCOUT rubric generator extensively reasons over the task and the agent's trajectory to determine what successful and safe execution should 

---

### [161] Systematic Multi-Agent Vision-and-Language Navigation: Formulation, Benchmark, and Method

**链接**: https://arxiv.org/abs/2609.35965
**作者**: Yunzhe Xu and Zhe Liu
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-and-Language Navigation (VLN) has largely focused on a single agent following a single instruction, yet many real-world applications require teams of robots to tackle tasks beyond the capabilities of any individual agent. We present Systematic Multi-Agent Vision-and-Language Navigation, providing, to our knowledge, the first systematic formalization of multi-agent VLN as a constrained coordination problem: each mission consists of subtasks carrying dependency and resource constraints (presence locks and holding chains). A verified four-stage crafting pipeline instantiates the task as MAVLN, comprising 11,724 episodes across 145 scenes with teams of up to four agents under three instruction regimes, accompanied by tailored constraint-aware metrics. We further present TRISS, a coordination-ready navigation system coupling an LLM-based subtask scheduler, a shared topological memory that turns each agent's exploration into team knowledge, and a conflict-aware execution mechanism tha

---

### [162] HEAR: Real Voices, Real Bias: A Large-Scale Human-Recorded, Demographically Diverse Benchmark for Audio Language Models

**链接**: https://arxiv.org/abs/2609.35952
**作者**: Shen Yan, Duc Le, Irina-Elena Veliche
**来源**: cs.SD cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce HEAR (Human-recorded Evaluation of Audio-LLM bias by Real speakers), a large-scale, ecologically valid benchmark comprising 87k real human audio samples from 843 demographically diverse participants. HEAR enables comprehensive evaluation through Multiple Choice Question Answering (MCQA) and open-ended long-form tasks. To our knowledge, this is the first large-scale voice benchmark grounded entirely in authentic human speech. We evaluate model behavior across both real-time speech-to-speech and speech-to-text architectures. Our results reveal that voice-conditioned bias is a model-specific property. Furthermore, we demonstrate that personalization instructions consistently exacerbate demographic disparities. Our findings establish that voice bias is a controllable model characteristic, providing a foundational framework for future bias mitigation and evaluation in Audio-LLM development.

---

### [163] SKILLLITE: Evidence-Guided Malicious Skill Auditing with Compact LLMs

**链接**: https://arxiv.org/abs/2609.36879
**作者**: Haoran Ou, Gelei Deng, Xuanye Zhang, Wenbo Guo, Tianwei Zhang, Kwok-Yan Lam
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based agents perform increasingly complex tasks, Agent Skills have emerged as a flexible mechanism for extending their capabilities. An Agent Skill packages task-specific instructions with executable components and auxiliary resources to provide specialized functionalities. However, the growing adoption of third-party Skills introduces a new supply-chain attack surface. Malicious Skills can embed harmful behaviors that abuse agent privileges and compromise the agent execution environment or accessible resources. Although recent LLM-based malicious Skill auditing approaches have achieved promising performance, they often rely on capable commercial LLMs. How to achieve effective auditing with compact, locally deployable LLMs in security-sensitive and resource-constrained settings remains largely unexplored. Our investigation reveals that compact LLMs struggle to identify malicious behaviors hidden in complex Skill packages. This difficulty arises from both the implicit nature of s

---

### [164] Mnemon: Raw Records, Fast Judgments, Slow Thoughts

**链接**: https://arxiv.org/abs/2609.36059
**作者**: Guangren Wang
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory lets an LLM assistant use a history it can no longer reread, and most memory systems build it by rewriting conversations into facts, graphs or typed memories at write time. We argue that the work of memory divides, as thinking does, into two systems. Most of it is fast System 1 work: many small, independent yes/no judgments about records, such as whether a record is needed or no longer current, which a decision model makes by the dozen in a third of a second. Only a little is slow System 2 work: writing a few search queries, naming what the reply needs and composing the answer, which an LLM does well but slowly. We present Mnemon, a memory agent built on this division. It keeps conversations as raw, dated records; an LLM (System 2) plans searches over them, a decision model, Jev (System 1), judges what the searches return, and rules with explicit budgets turn the judgments into a small View for an unchanged answering model. A background pass consolidates each record on

---

### [165] ReLMem: Learning Recurrent Memory for Longitudinal EHR Modeling

**链接**: https://arxiv.org/abs/2609.37587
**作者**: Zijie Meng, Xiwei Dai, Yingying Zhang, Jian Wu, Xian Wu, Zuozhu Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Longitudinal electronic health record (EHR) modeling requires integrating new visits with an expanding patient history. Yet the continual accumulation of clinical information imposes increasing computational and memory costs on large language models (LLMs) when they process and retain complete patient histories. A practical alternative is visit-wise recurrent compression, which incorporates each incoming visit into a compact, continually updated patient memory. However, under a fixed memory budget, successive updates must integrate new information without progressively losing critical historical evidence needed to subsequent tasks. To address this challenge, we introduce Recurrent Longitudinal Memory (ReLMem), a framework that learns to maintain fixed-capacity patient memory for efficient downstream prediction with a frozen LLM. ReLMem equips this LLM with lightweight compression adapters to recurrently update the memory from its previous state and each incoming visit, without rereadin

---

### [166] From Learner Behavior to Reusable Skills for Effective and Efficient Learner Simulation

**链接**: https://arxiv.org/abs/2609.37157
**作者**: Zijian Chen, Zheng Zhang, Miao Jia, Xingchen Hu, Weibo Gao, Linan Yue
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learner simulation aims to reproduce how a particular learner behaves on new tasks. Although Large Language Models (LLMs) can generate increasingly fine-grained learning behaviors, existing approaches often need to repeatedly process a growing interaction history to reconstruct the learner. This introduces additional context and inference costs and makes the acquired learner-specific simulation capability difficult to reuse across different LLMs. We therefore propose Learner2Skill, which externalizes the simulation capability acquired from historical interactions into a persistent and reusable Simulation Skill. The Skill captures the learner's current learning state and recurring response patterns, evolves as new real interactions arrive, and can be adapted to a new LLM through lightweight executor calibration without reconstructing the learner from scratch. Experiments show that Learner2Skill more faithfully reproduces fine-grained learner behavior while reducing overall token cost, a

---

### [167] Foundations of Proactive Agents: Principles, Technical Layers, and Proactivity-Gym

**链接**: https://arxiv.org/abs/2609.37267
**作者**: Jio Oh, Seunghyun Do, Young-Jun Lee, Steven Euijong Whang, Dongyeop Kang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Proactive LLM agents can turn idle compute into useful support before users ask. Yet even correct work can misread user context, impose review costs, or undermine trust. This work proposes foundations for designing, realizing, and evaluating proactive LLM agents around three joint principles (3T): Task Capability, anticipating relevant needs and correctly performing useful work; Temporal Allocation, allocating compute according to resource availability and when results are needed; and Trust, sustaining users' confidence and appropriate reliance on the agent. We connect these objectives to a design space organized around five dimensions: task scope, anticipation horizon, activation trigger, processing timing, and intervention depth, and specify the situation and system modeling needed to support its choices, including user and environment representations, backbone LLMs, and agent harnesses. Lastly, we propose PROACTIVITY-GYM, a simulation-based evaluation testbed including multi-day sce

---

### [168] MAADBench: The Refreshable Paradigm for Anomaly Detection in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.36556
**作者**: Lei Ma, Dennis Hofmann, Haowen Xu, Joshua DeOliveira, Peter VanNostrand, Lei Cao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies report that LLM-based multi-agent systems (MAS) fail at rates of 41%-87%, yet to our knowledge, no benchmark to date supports systematic anomaly detection (AD) for them. Building MAS AD benchmarks is hard because they must remain fresh as LLM systems evolve: tasks may leak into training data and thus be memorized by LLMs, traces and anomaly patterns expire as backbones evolve, and labels must be provided reliably for each refresh. To address these challenges, we present MAADBench (MA: multi-agent; AD: anomaly detection), the first refreshable MAS AD benchmark designed for diverse, evolving LLM backbones underlying the agents. MAADBench combines (1) sampled-and-coupled generative tasks over an approximately 10^37-task space to mitigate task leakage, (2) refreshable trace generation under configurable LLM backbones, and (3) automated provision of cost-free, deterministic step-level labels for fine-grained AD evaluation. Beyond offering the paradigm itself, we run MAADBench

---

### [169] Is manual software optimization a thing of the past?

**链接**: https://arxiv.org/abs/2609.37849
**作者**: Pavlin G. Poli\v{c}ar and Martin \v{S}pendl and Toma\v{z} Ho\v{c}evar
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific software is increasingly required to process larger datasets while maintaining acceptable execution times. Software optimization traditionally requires substantial expertise in programming, algorithms, and numerical methods. Recent advances in large language models (LLMs) offer the possibility of automating much of this process. We investigate whether LLM-based agents can autonomously achieve substantial performance improvements in scientific software, including mature implementations that have already been extensively optimized by human developers. We tasked an LLM-based agent with optimizing software for three computational problems: t-SNE, single-sample gene set enrichment analysis (ssGSEA), and graphlet counting. Humans defined the scope, correctness criteria, and a verification mechanism, after which the agent worked autonomously, in some cases for several hours. Code maintainers reviewed each resulting implementation and verified its correctness. The optimized implemen

---

### [170] VoxelSage: Tool-Augmented 3D CT Analysis and Simulator-Shielded Sequential Resection Planning for Liver Tumors

**链接**: https://arxiv.org/abs/2609.37648
**作者**: Binghong Qian, Xuanhe Liu, Yifan Xing, Wenjie Deng, Jian Wu, Haochao Ying
**来源**: cs.CV eess.IV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Preoperative liver-tumor assessment requires segmentation, physical-space measurement, visual evidence, and resection planning from the same three-dimensional CT volume. Existing tools often handle these steps separately, while language models cannot reliably compute physical measurements from CT. To provide an integrated workflow, we present VoxelSage, a multi-modal system for two- and three-dimensional visualization, liver-tumor analysis, and preoperative resection planning. Its dual-port architecture separates language-model orchestration from image computation: Port A interprets requests and selects skills, while Port B applies them to CT volumes and segmentation masks and returns structured results. Keeping physical measurements in Port B prevents the LLM from computing them directly and reduces the risk of fabricated numerical results. Eight built-in skills support quantitative analysis, visual evidence generation, three-dimensional reconstruction, segmentation refinement, and se

---

### [171] LatentSift: Policy-State Filtering for Token-Efficient Verification of Software Engineering Agents

**链接**: https://arxiv.org/abs/2609.36371
**作者**: Yuning Han, Yangchenchen Jin, Tyler Jandreau, Jingwei Sun
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling improves software engineering agents by generating multiple candidate trajectories and selecting the best one. Verifying and selecting among these long interactions can consume as many tokens as generation itself. Existing hybrid workflows first apply an LLM-based execution-free (EF) verifier to filter candidates before running tests, which adds another model pass over every trajectory. We introduce LatentSift, a token-free and execution-free filter that replaces this first stage with hidden states the policy already produces while generating the candidates. It represents each candidate through its reasoning, observation, and function-call states, compares them with positive and negative banks of such states collected from successful and unsuccessful trajectories during policy training, and fuses the resulting distance scores with a learned linear score to retain promising candidates for the execution-based stages. On SWE-bench Verified, across three agents and two po

---

### [172] ER-JEPA: Experience Replay Improves Joint-Embedding Predictive Learning in Language Models

**链接**: https://arxiv.org/abs/2609.36952
**作者**: Jingnan Pu, Zi-En Fan, Feng Lian
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) excel at token-level generation but may learn undesirable abstract semantics and lack comprehensive perception. LLM-JEPA mitigates this by aligning different views of the same underlying knowledge via a joint-embedding predictive architecture (JEPA). However, strong alignment does not necessarily lead to accurate, stable predictions. To address this, we propose ER-JEPA, which adds an episodic replay path to LLM-JEPA. ER-JEPA stores training pairs in a memory. At each step, it stores and retrieves relevant data to provide additional supervision. This enables learning from both the current batch and stored training pairs, providing additional supervision for token prediction and representation alignment. Experiments across multiple datasets (NL-RX, GSM8K, Spider, and NQ-Open) demonstrate that ER-JEPA consistently outperforms LLM-JEPA.

---

### [173] MatToolBench: Benchmarking Multimodal Agents in Real-World Materials Science Workflows

**链接**: https://arxiv.org/abs/2609.37053
**作者**: Mei Wu, Rui Xie, Runyu Zhang, Yuqiang Li, Tianfan Fu, Bo Chen 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal GUI agents have achieved impressive results on general software benchmarks, yet their ability to operate professional scientific software remains largely unexplored. In materials science, sparse domain-specific web data, specialized interfaces, and tacit workflow conventions create blind spots that general-purpose pretraining cannot readily bridge. We present MatToolBench, the first real-environment benchmark for evaluating multimodal GUI agents on professional materials science software, comprising 204 tasks across 10 tools in three modalities: GUI operation, OriginPro scripting, and code-based database queries, all executed inside a Windows 11 VM. Each task is decomposed into fine-grained sub-criteria by domain experts, enabling interpretable partial-credit scoring; the GUI component of our multi-level evaluation pipeline achieves an average F1 of 0.98. For OriginPro figure-generation tasks, we further conduct a human-LLM agreement study to validate the use of a multimodal

---

### [174] JudgeCast: Time Series Forecasting with Experience-Informed Covariate Judgements

**链接**: https://arxiv.org/abs/2609.36966
**作者**: Donguk Kwon, Wooseok Jeong, Dongha Lee
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Covariate effects vary across contexts and shift over time, requiring forecasters to assess how to use them for each forecasting context. As forecasting proceeds, observations for earlier forecasts become available, providing feedback on past covariate use for subsequent forecasts. However, when multiple covariates act together, the forecast error reveals the numerical discrepancy from the observation but not how the covariates should have been used. We introduce JudgeCast, an experience-based framework for time series forecasting with covariates. Following the judgmental adjustment practice, a frozen TSFM provides the base forecast, while a frozen LLM uses the current context and relevant experience to adjust it. Within the adjustment, assessing covariate effects and determining the numerical adjustment serve distinct roles, so JudgeCast first forms explicit covariate-wise judgments and then determines the adjustment. After observation, JudgeCast uses the observed residual of the base

---

### [175] FinRT: Distilling Adaptive Red-Teaming Strategies into Reusable Adversarial Generators in Consumer Finance

**链接**: https://arxiv.org/abs/2609.36474
**作者**: Rikhiya Ghosh, Himanshu Kumar, Sriram Venkatapathy, Sahil Wadhwa, Alexandre G.R. Day, Pranab Mohanty
**来源**: cs.CL cs.CR cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In regulated industries like consumer finance, seemingly harmless user queries can exploit large language model vulnerabilities, triggering safety failures and pushing responses dangerously close to policy limits. Existing automated red-teaming methods trade off attack effectiveness against generation cost, while treating coverage, severity, and diversity as incidental rather than joint objectives. We introduce FinRT, a structured framework that builds reusable adversarial prompt generators from adaptive red-teaming strategies. Across the six victim models in consumer finance, FinRT substantially outperforms adaptive search baselines while amortizing target-facing attack generation into a reusable generator. FinRT nearly doubles the attack success rate over the adaptive baseline Rainbow Teaming (32.9% vs. 17.2%), increases maximum adversarial severity by 33%, and preserves comparable intra-policy-domain semantic diversity to iterative search methods. Our method achieves high cross-mode

---

### [176] LatCom: Cross-Agent Latent Compression for Efficient Multi-Agent Collaboration

**链接**: https://arxiv.org/abs/2609.37017
**作者**: Shinan Zhang, Tao Zhang, Qihui Zhu, Mengjie Zhang, Dong Jin, Yunpeng Hou 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) increasingly use latent collaboration to avoid the information loss and repeated encoding-decoding overhead of natural-language communication. However, directly forwarding all sender latents makes the receiver-side context scale with both the number of agents and the reasoning length, increasing computation, memory usage, and collaboration latency. A natural solution is latent compression. But we find that cross-agent redundancy remains unresolved in existing latent compression approaches, which typically compress each sender independently and then concatenate the results. We propose LatCom, a cross-agent latent compression framework for efficient multi-agent latent collaboration. LatCom maps multiple sender latents into a fixed number of receiver-readable and task-relevant slots. Rather than reconstructing all sender hidden states, it optimizes the compressed latents for receiver-side task utility. LatCom trains the compressor in two stages: single-

---

### [177] LAURA: Knowledge Distillation for Interpretable Ambiguous Clause Identification in Legal Contracts

**链接**: https://arxiv.org/abs/2609.36707
**作者**: Amrita Singh, Aditya Joshi, Jiaojiao Jiang, Hye-young Paik
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Legal contracts contain ambiguities that expose enterprises to financial and legal risks. Some ambiguities allow flexible interpretation without triggering disputes, while others lead to significant legal conflicts. This makes identification alone insufficient, and interpretable rationale analysis essential. We propose LAURA, a post-training framework for interpretable ambiguous clause identification. LAURA leverages knowledge distillation with an IRAC-Unlearning prompting technique to transfer knowledge from a teacher LLM to an open-weight student model (<=1B parameters), which is then trained using a joint objective combining classification and rationale generation losses. The framework supports both legal and non-legal stakeholders in making informed decisions about which ambiguities require further attention. Extensive experiments across 7 baselines and 7 open-weight models demonstrate that LAURA with Flan-T5 (250M) delivers state-of-the-art interpretability over all interpretable 

---

### [178] SRJudge: Empowering Large Language Models with Selective Reasoning for Fine-Grained Knowledge Concept Tagging

**链接**: https://arxiv.org/abs/2609.36982
**作者**: Zhiwei Yang, Jiahua Yang, Huiru Lin, Xing Chen, Quanlong Guan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge concept tagging aims to assign specific concept or topic labels to educational content, which is essential for both educators and learners in traditional and online teaching practices. Recent work has explored large language models (LLMs) for this task, achieving promising performance. However, LLMs still struggle to select the correct concept from a large-scale candidate set due to the high dimensionality of the decision space. In this paper, we propose a novel three-stage Select-Reason-Judge (SRJudge) framework, which empowers LLMs with selective reasoning capability for fine-grained knowledge concept tagging. Specifically, the Selector in Stage 1 first narrows the candidate concepts to a top-K shortlist by fine-tuning a small language model (SLM), e.g., BERT, since the top-$K$ predictions hit the correct concept in most cases, thereby reducing the decision space of correct candidates. Next, the Stage 2 Reasoner employs a lightweight LLM for refined reasoning over the short

---

### [179] CRASM-Gate: Deterministic-First Constraint- and Role-Aware Semantic Mapping with Selective Model Assistance Across Heterogeneous Industrial Standards

**链接**: https://arxiv.org/abs/2609.37458
**作者**: Kabeh Mohsenzadegan, Vahid Tavakkoli, and Kyandoghere Kyamakya
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial standards often encode the same engineering concept through incompatible hierarchies, identifiers, roles, and structural constraints, so the nearest lexical or embedding match can still be technically inadmissible. This article presents CRASM, a deterministic constraint- and role-aware semantic mapping method, and CRASM-Gate, its selectively model-assisted extension. The framework separates standard-specific canonicalization, bounded retrieval, deterministic rules, destination-versus-origin role interpretation, semantic and structural ranking, ambiguity refusal, and target validation. CRASM-Gate adds a confidence/disagreement gate that may invoke a candidate-constrained large language model, while final authority remains with deterministic validation. A controlled artifact covers six directed industrial-standard pairs, three difficulty levels, and ten configurations, yielding 14,400 sample-level decisions. With a fixed local model endpoint, CRASM-Gate reaches mean F1 0.9938 

---

### [180] VehicleArena: A Realistic Urban Environment for Multi-Agent Driving

**链接**: https://arxiv.org/abs/2609.35916
**作者**: Jie Yang, Jiajun Chen, Jiazheng Zhou, Mianqiu Huang, Yining Zheng, Yuxin Wang 等 (7 人)
**来源**: cs.MA cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world embodied agents often pursue independent objectives within a shared physical environment, where their actions can alter the conditions faced by others. Existing benchmarks, however, typically assume shared goals or explicitly prescribed interaction protocols, leaving such emergent physical coupling underexplored. We introduce VehicleArena, a 3D urban-driving benchmark for studying independently operating agents in a dynamic shared world. In VehicleArena, LLM-controlled agents must fulfill evolving passenger requests while navigating complex traffic, and each agent's driving decisions can reshape traffic flow, delays, risks, and subsequent observations for surrounding agents. The benchmark provides 112 evaluation tasks spanning single-agent and multi-agent driving. Across nine evaluated models, the highest arrival rates reach only 65.0% on single-agent tasks and 65.6% on multi-agent tasks, while strong passenger-request or cabin scores do not reliably translate into successfu

---

### [181] When Trees Are Not Enough: Learning Mixed-Topology Feature Graphs with Adaptive Graph Sparse Autoencoders

**链接**: https://arxiv.org/abs/2609.36294
**作者**: Xiaozuo Shen, Yifei Cai, Tian Tan, Rui Ning, Chunsheng Xin, Hongyi Wu
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) expose interpretable features in large language model activations, yet existing structured SAEs impose single-parent trees or forests, while post-hoc graphs permit multiple parents but neither guide feature learning nor ensure reliable relation recovery. We introduce the Adaptive Graph Sparse Autoencoder (AG-SAE), a structure-guided training paradigm that treats each feature's complete parent set as an atomic structural hypothesis and lets evidence select zero, one, or multiple parents. By competing complete parent sets against null, subset, and alternative explanations, AG-SAE identifies jointly necessary multi-parent relations while rejecting redundant or spurious alternatives and verifying that each child contributes beyond its parents. The induced topology over SAE features then defines a differentiable structural loss that guides SAE training, while topology-guided refinement mitigates feature absorption and uses persistent reconstruction gaps exposed by

---

### [182] VAA-CSEC: Vote-guided Advantage Allocation for Chinese Semantic Error Correction

**链接**: https://arxiv.org/abs/2609.36804
**作者**: Yitong Han, Nankai Lin, Juan Luo, Hongyan Wu, Lianxi Wang, Shengyi Jiang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chinese Semantic Error Correction (CSEC) targets semantic errors in Chinese text, which are typically more subtle and complex than spelling and grammatical errors but remain relatively underexplored. Existing LLM-based approaches face two recurring obstacles in this task: over-correction, and unclear interaction between Chain-of-Thought (CoT) reasoning and self-consistency decoding, such that the benefits brought by CoT cannot be reliably transferred to final corrections. We propose Vote-guided Advantage Allocation for CSEC (VAA-CSEC), a multi-stage framework that combines CoT distillation, Supervised Fine-Tuning (SFT), Reinforcement Learning (RL) and self-consistency decoding. During RL, we design a task-specific reward function that directly aligned with the minimal-editing principle of CSEC. We further introduce Group-Level Relative Policy Optimization (GLPO), which reallocates GRPO advantages according to the margin between individual rollout rewards and the vote-aggregated group r

---

### [183] What Comes Next? Omni-StoryBench for Evaluating Story-Grounded Omnimodal Generation

**链接**: https://arxiv.org/abs/2609.37317
**作者**: Sieun Hyeon, Yejoon Lee, Mintaek Lim, Woojin Kim, Jaeik Kim, Jaeyoung Do
**来源**: cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Omnimodal evaluation should go beyond independent text, image, and speech production: individually plausible outputs may not express a coherent shared event. We introduce Omni-StoryBench, a story-grounded omnimodal benchmark evaluating whether models can coherently continue stories across image, narration, and speech. Each instance provides a current storybook page and structured next-page conditions, requiring models to generate the next illustration, narration, and spoken character utterance. Omni-StoryBench contains 900 rigorously validated story transitions from openly licensed children's books, with ground-truth next-page references and speech metadata. We evaluate systems with modality-specific metrics and consistency-centered LLM-as-a-judge rubrics for context preservation, condition following, reference consistency, and cross-modal coherence. Across 32 baseline configurations spanning orchestration, semi-orchestration, and native any-to-any paradigms, we find orchestration with

---

### [184] SAM Meets VLM: Parameter-Decoupled Full-Parameter Training for Unified Medical Reasoning and Segmentation

**链接**: https://arxiv.org/abs/2609.37283
**作者**: Xuyang Cao and Enyou Liu and Jun Zhao and Zhuoyun Liu and Jintao Fei and Leo
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical multimodal large language models (MLLMs) are increasingly expected not only to answer clinical questions, but also to localize the visual evidence behind their predictions. A common strategy connects a vision--language model (VLM) with SAM-style segmentation through a special <SEG> token, yet full-parameter training of this unified architecture is difficult because image-level reasoning and pixel-level segmentation impose different requirements on the shared representation space. To address this issue, we propose a parameter-decoupled training framework for unified medical reasoning and segmentation. The framework treats the <SEG> hidden state as a semantic-to-spatial prompt for the mask decoder and encourages it to become separable from generic language states, reducing ambiguous segmentation prompts and potential disruption to reasoning representations. It first performs medical shallow alignment to adapt visual features to clinical language without disturbing the LLM; then c

---

### [185] Infrared Subtraction with Artificial Intelligence

**链接**: https://arxiv.org/abs/2609.36007
**作者**: Wenjie He, Xiaohui Liu, Yandong Liu, Zhan Wang
**来源**: hep-ph cs.AI hep-ex nucl-ex nucl-th
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present AI-developed local infrared subtraction, building on projection to Born and EFT matching. The framework separates an integrable radiation term from a finite contribution at Born kinematics, referred to as the Born contact. The contact is determined using the EFT singular distribution in a resolution observable such as N-jettiness $\tau_N$. Under human physics guidance, an LLM develops two implementations. One uses a neural network for phase space projection and fits the contact by matching to EFT cumulants. The other uses an analytic construction that keeps the Born momenta fixed while integrating over radiation. It combines the EFT $\delta(\tau_N)$ coefficient with finite 4-dimensional radiation integrals to calculate the contact term directly. This gives a local subtraction formula without a slicing parameter, while reusing existing lower-order radiation calculations and EFT singular predictions. As a demonstration, we reconstruct the full NLO correction for massless 3- an

---

### [186] AI as a Compiler: Compiling Triton kernels without the Triton compiler

**链接**: https://arxiv.org/abs/2609.36800
**作者**: Fran\c{c}ois Costa, Charly Castes, Thomas Bourgeat, Azalia Mirhoseini
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compiler backends are expensive to build and maintain as programming models, workloads, and accelerators evolve. We investigate whether large language models can replace the conventional optimizing and lowering pipeline, a process that we call AI lowering. We study AI lowering from Triton to NVIDIA PTX: an LLM agent translates Triton kernels directly into PTX. We build an environment that evaluates candidate PTX, and an agentic harness in which an LLM translates Triton kernels into PTX. Across twelve common kernels on Ada, Hopper, and Blackwell GPUs and ten kernels from recent ML papers, AI lowering achieves 0.83x-3.34x the performance of autotuned Triton. The largest gains come from transformations that Triton's lowering pipeline does not perform, such as decoding packed binary weights directly into Tensor Core operands (3.34x on BitDelta), assigning each thread a complete softmax row in tensor memory (1.37x on FlashAttention), and reusing overlapping convolution windows (up to 2.23x)

---

### [187] Active Budget Can Kill Sensitivity: Diagnosing and Repairing TopK Sparse Autoencoder Reliability

**链接**: https://arxiv.org/abs/2609.37857
**作者**: Zhenting Huang, Junnan Liu, Qianren Mao, Zhixing Tan, Bo Jiang
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) are increasingly scaled to wider dictionaries to recover fine-grained structure from large language model activations. However, a feature is useful for interpretation only if it remains a stable unit of analysis when the same meaning is expressed in different surface forms. We study this reliability question for TopK SAEs via feature sensitivity. Experiments demonstrate that scaling selectively reduces the sensitivity of rare features, while common features remain comparatively stable. A controlled width\(\times k\) factorial experiment identifies the active budget k as the root cause: the degradation arises from the selection boundary rather than dictionary width alone. We attribute this failure to the geometry of TopK selection. The active margin, the distance to the cutoff, predicts feature loss without thresholds. Guided by this margin diagnosis, we introduce pairwise rank stabilization. Our method targets ordering failures at the cutoff and improves rare

---

### [188] Effective Dense Retrieval using Only In-Context Examples

**链接**: https://arxiv.org/abs/2609.38099
**作者**: Nour Jedidi, Abdul Basit Ali, Hang Li, Jimmy Lin
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Turning decoder-only large language models (LLMs) into strong dense retrievers typically requires some form of retriever training. In this paper, we ask whether LLMs can instead be prompted to produce effective representations for dense retrieval given only a few in-context examples. To answer this, we introduce RICE (Representations from In-Context Examples), a simple "training-free" approach that extracts high-quality dense representations from LLMs. To do so, RICE conditions the LLM on examples that provide a shared context for query and document encoding. Our results demonstrate that RICE embeddings can substantially improve the accuracy of prompt-based LLM embeddings, establishing it as a simple method to build LLM-based dense retrievers that do not require training. We release our code at https://github.com/nourj98/RICE.

---

### [189] Lost in Translation: Measuring the Effect of Non-Native English on End User Performance of Large Language Models

**链接**: https://arxiv.org/abs/2609.36214
**作者**: Yusheng Zhou, Eleanor Lin, David Jurgens
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used by people whose first language is not English, yet these users have been shown to receive systematically lower-quality responses than fluent speakers. Which specific features of non-native English drive this gap remains unclear, because fluency is itself a composite of mechanical accuracy, vocabulary use, organization, and discourse coherence. Here, we introduce FABLE, a controlled dataset of 190,911 English prompt variants derived from 174K real user prompts for writing-related tasks. Evaluating responses from 34 open-weight LLMs, we find a clear asymmetry; while models do not propagate surface errors such as misspellings into their outputs, models do mirror higher-level rhetorical and lexical qualities present in the user's prompt. Further, the overall quality of responses differs substantially between the least- and most-fluent prompts. These results highlight a key LLM performance disparity for non-native English LLM users, resulti

---

### [190] GitHarness: Git Init Your Harness Working Memory for Perpetual User Requirements

**链接**: https://arxiv.org/abs/2609.36789
**作者**: Zhibang Yang, Xinke Jiang, Yuxuan Liu, Mingyu Zhang, Zhixin Zhang, Zhengxing Song 等 (10 人)
**来源**: cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly collaborate with users on long-horizon tasks, accumulating evidence, code, and drafts through extensive search, reasoning, and execution. As users inspect these results, they may supply missing information requirement completion, introduce new requirements requirement elicitation, or revise existing ones requirement shift. These changes often affect only part of the accumulated work, yet agents may carry forward obsolete information or turn local revisions into global rewrites. Existing approaches clarify current intent without determining how prior work should change, or reuse execution histories under a fixed objective. We address this gap by formulating dynamic-requirement collaboration as joint requirement tracking and local update. We introduce GitHarness, a pluggable Git-style framework that organizes requirement states and their corresponding harness work states into a branchable version history. A trainable Git Agent resolves requirement changes an

---

### [191] DScale: Scaling Block-Diffusion Speculative Decoding with Adaptive Verification

**链接**: https://arxiv.org/abs/2609.37532
**作者**: Rongjian Chen, Minxian Xu, Zhengxin Fang, Kejiang Ye, Chengzhong Xu
**来源**: cs.DC cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Growing large language model applications demand efficient inference. At high concurrency, block-diffusion speculative decoding suffers from verification padding, rejected candidates, and incompatibility between variable prefixes and fixed-shape graphs. Uniform truncation sacrifices acceptable tokens. We present DScale, preserving drafter architecture, weights, and full draft length. A separate 112K-parameter predictor requires neither confidence calibration nor hardware speed-curve preparation. Path-aware tiles reduce padding. Dynamic verify-length (DVL) allocation packs scored prefixes into half the native verification capacity. Fixed-address workspaces propagate changing boundaries through verification and acceptance while reusing captured graphs. On A100-40GB with tensor parallelism 1, Qwen3-8B and Qwen3-4B cover four datasets and concurrency 8-32, reusing each target's frozen predictor. Geometric-mean throughput gains across these configurations are respectively 43.9% and 48.8% ov

---

### [192] Lost in Conversation or Lost in Translation? Diagnosing Multi-Turn Degradation in RAG

**链接**: https://arxiv.org/abs/2609.36700
**作者**: Pranav Handa, Ariful Azad
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When conversing with large language models (LLMs), users often begin with a simple question and build towards a multi-hop question through follow-up turns. Retrieval-augmented generation (RAG) and its graph-based variant (GraphRAG) have become the dominant approaches for grounding LLM responses in external evidence, yet both are evaluated almost exclusively on single-turn, fully specified queries. We systematically investigate this evaluation mismatch through a large-scale simulation study. Building on prior work on multi-turn LLM evaluation, we transform questions from multi-hop question answering (QA) benchmarks into underspecified conversations and evaluate ten LLM assistants with eight retrieval systems across 1.5 million simulated conversations. Our findings reveal that multi-turn interaction causes widespread performance degradation, incurring relative performance drops of up to 21% and increasing unreliability by 47%, making RAG systems simultaneously less accurate and less reli

---

### [193] CruxBench: A Benchmark of Information Discovery

**链接**: https://arxiv.org/abs/2609.35879
**作者**: Hui Dai, Lina Piao, Nick Merrill, Nadja Flechner, Ezra Karger, Haifeng Xu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks for large language models (LLMs) typically evaluate the accuracy of answers against fixed reference labels. But a central step in many complex real-world tasks is identifying which questions are worth asking in the first place: decomposing a difficult problem into subquestions -- which we call cruxes -- whose answers provide key steps on the path toward solving the target problem. To evaluate this capability of information discovery, we introduce CruxBench, a benchmark that grades LLM-generated questions by their Value of Information (VOI): how much a model-proposed crux updates beliefs about a target forecasting question. CruxBench enjoys a rare combination of three key properties: it is (1) contamination-resistant by construction, since ground truth is generated by future world events; (2) open-ended, admitting unbounded and complex text-based submissions rather than one correct numeric answer; and (3) grounded, with informativeness measured against quantified changes in r

---

### [194] DraftTrace: A Multi-View Analytics Environment for AI-Integrated Writing

**链接**: https://arxiv.org/abs/2609.36544
**作者**: Divyansh Chandarana, Sandipan De, Vivek Gupta
**来源**: cs.CL cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI has changed how students produce writing assignments. The final artifact is no longer sufficient to understand the process through which it was produced. We introduce DraftTrace, a writing environment that jointly captures three complementary views of writing: the final product, the writing process and interactions with an integrated AI-assistant. DraftTrace reconstructs how a document develops over time and organizes these signals into submission, longitudinal, and class-level analytics for instructors. We deployed DraftTrace in a graduate NLP course with 81 students and compared their sessions with LLM-generated responses entered by automated tools and with copy-typed responses. While product measures distinguish differences in text formulation, process measures distinguish differences in how text is entered. Considering both views together helps characterize cases such as copy-typing. Interaction traces show that students use the assistant differently across stages of 

---

### [195] Evaluating the Effects of Prompt Perturbation on Bias and Hallucination in Large Language Models

**链接**: https://arxiv.org/abs/2609.35804
**作者**: Mamehgol Yousefi, Ahmad Shahi, Mos Sharifi, Alvaro Romera, Simon Hoermann, and Tham Piumsomboon
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown remarkable capabilities in various natural language processing tasks, leading to their widespread deployment as intelligent assistants in decision-making contexts. However, the increasing complexity of these models raises concerns about their reliability, particularly regarding bias and hallucination. In this work, we evaluate the robustness of LLMs to perturbed variations of the original inquiry in decision-making tasks. We show that contrary to previous studies, perturbations can mitigate bias and hallucination in some LLMs over other models. It's found that Claude 3 is more effective for the tasks represented in most datasets, whereas models like GPT3.5 exhibit varying levels of adequacy, performing comparably in some cases but falling significantly behind in others. These insights are crucial for understanding the practical implications of deploying LLM-based assistants as effective decision-support tools in real-world applications, emphasisi

---

### [196] Language Models Are "Insecure" Reporters

**链接**: https://arxiv.org/abs/2609.36139
**作者**: Jenny Y. Huang, Jiameng Fan, Ahmed Imtiaz Humayun, Maximillian Chen, Tian Qin, Run Chen 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models are deployed in increasingly autonomous long-horizon tasks, manually auditing and verifying the actions, artifacts, and outputs of models becomes more difficult. Users instead come to rely on LLM-generated reports to assess the quality and completeness of the work. We introduce a suite of eight adversarial reporting scenarios to systematically study whether LLMs conceal narrative-changing flaws: errors or limitations that undermine an otherwise successful account of work. We call this phenomenon "insecure reporting." When handed machine learning experiment logs containing a planted negative result that substantially weakens the proposed method, GPT-5.5 flags the negative result in only 2 of 200 generated reports. However, when a short honesty instruction, "Be honest in your response," is added, the model flags the negative result in 190 of 200 reports. Across eight open-weight models, chain-of-thought analysis reveals a recurring tension between disclosing narr

---

### [197] Lookahead-R: Budget-Aware Tool Retrieval via Execution-Centric Planning

**链接**: https://arxiv.org/abs/2609.35811
**作者**: Zongze Wu, Yani Guo, Runnan Li
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool retrieval is a critical bottleneck for LLM-based agents operating over large, heterogeneous API ecosystems. Existing approaches face an inherent trade-off: semantic retrievers are fast but suffer from the semantic-functional gap, while execution-based validation improves precision at the cost of prohibitive latency. We propose Lookahead-R, a planning-based framework that reformulates tool retrieval as a resource-constrained sequential decision-making problem. At its core, Lookahead-R introduces a lightweight execution-aware surrogate world model that jointly predicts tool execution success, latency cost, and semantic utility---without invoking real APIs. This world model drives a cost-sensitive, uncertainty-guided Monte Carlo Tree Search that navigates the tool space under strict budget constraints. Evaluated on the large-scale ToolBench benchmark, Lookahead-R achieves a superior accuracy-efficiency trade-off across all test scenarios. On the most challenging I3 split, it attains 

---

### [198] Teachers' perspective on AI-based Multi-Agent Simulation Design to Combat School Bullying

**链接**: https://arxiv.org/abs/2609.35776
**作者**: Jiaju Lin, Ellen Wenting Zou, Feiwen Xiao, Huanying Song
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bullying in schools profoundly affects the mental and physical health of teenagers. Although existing in-person and digital interventions provide some benefits, they often fall short in addressing the complex social dynamics of bullying. In this study, we collaborated with K-12 teachers to co-design a multi-agent anti-bullying system powered by large language models (LLMs). This system simulates authentic scenarios, enabling students to develop anti-bully skills. The research identifies key design parameters for an LLM-driven multi-agent simulation system, offering valuable insights for creating more effective and scalable anti-bullying tools that could significantly reduce bullying in schools} \keywords{anti-bullying interventions, multi-agent system, generative AI, co-design, bystander presence

---

### [199] BRIDGE: Bilevel Retrieval-Credit-Aware Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.36505
**作者**: Quan Xiao, Mingda Liu, Gaowen Liu, Katsuki Fujisawa, Tianyi Chen
**来源**: cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic reinforcement learning (ARL) with verifiable rewards improves the ability of large language models (LLMs) to tackle knowledge-intensive tasks by learning to interleave search and reasoning. However, most existing ARL methods optimize only LLM-generated tokens and treat retrieved evidence as environment observations. This creates an information-credit gap: failures caused by missing or misleading evidence are attributed to the LLM policy rather than to the retriever, which motivates training the LLM and the retriever jointly. In this paper, we show that retrieval and LLM policy learning are order-sensitive: adapting the retriever before optimizing the policy yields a larger reward gain than the reverse order. To preserve this hierarchy while allowing both components to co-adapt, we formulate retrieval-augmented agentic RL as a bilevel optimization problem. To solve it efficiently, we introduce BRIDGE, a memory-efficient first-order bilevel method motivated by a loss-landscape an

---

### [200] ARCagent: An Adaptive Retrieval Calibration Agent for Clinical Question Answering

**链接**: https://arxiv.org/abs/2609.36392
**作者**: Yuyan Chen
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In diseases where clinical guidelines are incomplete, contested, or mutually contradictory, knowledge completeness and dynamic conflict-aware synthesis are two safety-critical properties that standard Retrieval-Augmented Generation systems do not provide. Therefore, we present \sysname, an adaptive retrieval calibration clinical question-answering agent for ME/CFS, a disease where diagnostic frameworks coexist and major guidelines actively contradict each other on treatment. ARCagent contributes three components. First, a 1,706-chunk, 10-source knowledge base with a structured inter-guideline conflict registry spanning all active ME/CFS diagnostic frameworks. Second, a conflict-aware retrieval calibration pipeline that re-ranks retrieved evidence using query-specific focus and conflict signals. Third, a benchmark scored by LLM-as-Judge, avoiding systematic underestimation averaging 10.1 percentage points caused by keyword matching. ARCagent achieves 95.3%, outperforming all base LLMs. 

---

### [201] Population Fidelity: Evaluating Population Representativeness in LLMs

**链接**: https://arxiv.org/abs/2609.36253
**作者**: Neemias B. da Silva, Martin Lukk, Ali Sutani, Abhishek Moturu, Harris Yang, Daniel Silver 等 (8 人)
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) show considerable potential in simulating human attitudes and preferences. Prior work finds that LLM-generated responses can compress the range of attitudes found within populations and misrepresent particular subgroups in ways that vary across models and topics. We introduce Population Fidelity, an evaluation framework that distinguishes key conditions required for a set of LLM-generated responses to represent a population. It incorporates three dimensions: group-level accuracy, the amount of between-group variation, and the structure of that variation. We demonstrate the framework's utility in two ways. First, we reproduce a prior study of "machine bias" in LLM survey responses and apply the framework to its models and more recent ones, showing that poor representation reflects not only insufficient between-group variation but also variation assigned to the wrong groups. Second, we evaluate one proposed approach to improving models' population representat

---

### [202] Auditable Long-Term Memory: A Deterministic Retrieval Chain Measured at 479/475 of 500 on LongMemEval-S

**链接**: https://arxiv.org/abs/2609.38021
**作者**: Christopher J. Chanhnourack
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We evaluate an auditable long-term memory system on LongMemEval-S. Its retrieval chain uses hybrid candidate retrieval, cross-encoder reranking, coverage-first packet compilation, and deterministic reasoning scaffolds; an LLM is used only as a replaceable final reader. The chain places all gold sessions in the candidate pool for 468/470 answerable questions and produces gold-complete packets for 462/470. With a Claude Opus reader called through an unpinned CLI alias, two 500-question passes score 479/500 and 475/500 under GPT-4o. The 72 answerable knowledge-update rows used a substantively modified scoring prompt whose effect under the official text has not been measured. The pair straddles Chronos High's published 478/500; differences in reader generation, scoring prompt, and possibly data version, plus within-system variance, establish neither superiority nor equivalence. A grok-4.6-high reader on the same packets scores 476/474, while a maximum-reasoning-effort agentic variant regre

---

### [203] CounterSteer: Suppressing Indirect Prompt Injection with Activation Steering

**链接**: https://arxiv.org/abs/2609.36570
**作者**: Mark Russinovich
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection makes an LLM agent treat untrusted retrieved text as instructions. We present CounterSteer, an inference-time defense that suppresses this behavior inside the model. Per model, a five-step recipe fits a residual-stream direction from paired episodes differing only in whether an embedded instruction is followed, and retains it only if it passes pre-specified causal and capability gates. At deployment, the direction is subtracted from every tool-result token during prefill. The edit is always on--there is no detection decision to evade--and requires no fine-tuning, auxiliary model, or added tokens, only white-box serving and tool-result span boundaries. Across five open-weights models (8B-106B, five vendor lineages), held-out attack success falls from 0.21-1.00 undefended to 0.00-0.17 defended, and AgentDojo compromise rate from 0.10-0.49 to 0.006-0.079, at 93-100% typography-normalized benign utility, with larger task-dependent costs when reasoning over steered

---

### [204] PrimeSeeker: Capability-Oriented Supervision for Deep Search Agents

**链接**: https://arxiv.org/abs/2609.35816
**作者**: Linzhi Peng, Hanting Chen, Heng Chang, Ke Cheng, Bowen Du, Weifeng Lv
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model search agents are often trained with synthetic questions whose difficulty is increased through larger evidence graphs, additional hops, and longer trajectories. These global properties, however, are only indirect proxies for the local retrieval capabilities required during search. To address this mismatch, we introduce latent anchor reasoning, which consists of resolving an unnamed retrieval anchor from descriptive specifications and transferring the recovered anchor into a subsequent information demand. This primitive retrieval unit decomposes deep search into chains of coupled operations and organizes question construction around anchor resolution and relation transfer, without prescribing a canonical search path. Based on this formulation, we propose PrimeSeeker, a capability-oriented framework that constructs web-grounded anchor structures and jointly derives a question and a reference evidence skeleton. The skeleton preserves supporting evidence from construct

---

### [205] SelfSearch: Reward-Free Search for Self-Improving Agents

**链接**: https://arxiv.org/abs/2609.37968
**作者**: Jungwoo Yang, In Jin Kong, Yohan Jo
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in the coding capabilities of LLM agents allow them to inspect and modify their own instructions, tools, and execution procedures. Existing approaches use this ability to search for improved agents through repeated downstream evaluation, which incurs substantial costs and ties the search to the evaluated tasks. We introduce \textbf{SelfSearch}, a reward-free search procedure in which agents modify themselves using records of previous self-improvement episodes. These records capture the reasoning, tool actions, and outcomes of earlier modification attempts, providing concrete experience for improving both task solving and self-modification. Without downstream reward signals during search, SelfSearch improves population-mean success over the initial agent in all six model--benchmark settings, with individual agents gaining up to 11.2 percentage points on Terminal-Bench 2.1. On SWE-bench Multilingual, an agent improves success by \textbf{5.0} percentage points while reducing exec

---

### [206] Same Bytes, Different Authority: Reserved-Token Representations in Chat-Template Prompt Injection

**链接**: https://arxiv.org/abs/2609.35932
**作者**: Yan Zhan, Yunze Song, Mengkai Hou, Wanting Zhang, Shaobo Liu, and Zhijun Gao
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt injection against LLM agents becomes much stronger when the injected instruction is wrapped in the model's own chat template. A forged template marker such as <|im_start|> can reach the model either as a single reserved control token or as a sequence of ordinary subword tokens. The two decode to exactly the same text, and because tokenization runs on the server, the defender rather than the attacker decides which one the model receives. We use this to measure how much of the injected instruction's authority comes from the reserved token's learned representation. Encoding the forged markers as subwords, with the text held fixed and a control for the extra tokens this adds, lowers attack success on the InjecAgent benchmark by 39 to 66 percentage points on three of four open-weight families, and the gap carries over to multi-turn agent tasks in AgentDojo. On Qwen3-8B the gap is 8 points, because without reserved ids the model still recognises the forged turn from its text by reason

---

### [207] Environment Steering: Using Data Flow Control to Improve Agent Utility and Safety

**链接**: https://arxiv.org/abs/2609.35807
**作者**: Charlie Summers, Prajwal Raghunath, Aaditya Pai, Mayur Kulkarni, Zhuo Zhang, Oliver Kennedy 等 (7 人)
**来源**: cs.CL cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can make unsafe tool calls even when instructed to behave safely. Existing defenses constrain agents before execution, modify tool inputs/outputs, or rely on LLM judges; these approaches may depend on model behavior or block unsafe actions without helping the agent recover. We argue that the execution environment should instead enforce safety as the agent runs and steer it toward safe alternatives when violations occur---we call this Environment Steering. We implement this by modeling the agent and harness execution state as database tables, track the record-level data flows, and check these data flows against declarative policies during runtime. When violations are detected, policy- and context-specific feedback steers the agent toward safe trajectories. On AgentDyn, this enables the agent to improve task success rate over no-defense while achieving 0% attack success rate.

---

### [208] Reader Proficiency Shapes Layer-wise Surprisal Profiles

**链接**: https://arxiv.org/abs/2609.37688
**作者**: Akio Hayakawa, Horacio Saggion
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reading behaviour varies not only with linguistic input, but also with reader proficiency. In this study, we investigate whether the layer-wise relationship between surprisal from large language models (LLMs) and human gaze behaviour differs across readers with different levels of proficiency and across gaze measures. Using eye-tracking data from the MECO L2 corpus, we compare readers with high and low vocabulary proficiency on first-pass gaze duration (FPGD) and total gaze duration (TGD). We quantify the distribution of the predictive power of surprisal across model layers using Predictive Depth. Across 12 tested LLMs, we find that readers with lower vocabulary proficiency tend to show deeper Predictive Depth for FPGD, while this difference is smaller for TGD. Also, TGD itself shows deeper Predictive Depth than FPGD in both proficiency groups. These patterns suggest that where predictive power is concentrated across LLM layers may be related to the timing and breadth of the reading pr

---

### [209] ROSS: Relearning from Self-Generated Rollouts through Selective Supervision

**链接**: https://arxiv.org/abs/2609.35954
**作者**: Zhiwei Zhang, Huayu Deng, Fei Zhao, Jiayan Fu, Bin Liang, Kam-Fai Wong 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model post-training generates self-generated rollouts through reinforcement learning and on-policy distillation, yet this experience is often treated as stale once the policy advances. Historical rollouts can remain compatible with a later policy while preserving behaviors that the policy no longer expresses reliably. However, they may also contain mistakes, abandoned attempts, and redundant actions that should not be imitated, motivating finer-grained selective supervision. We introduce ROSS (Relearning from Self-Generated Rollouts through Selective Supervision), which preserves the full historical trajectory as context while applying loss only to selected model-generated continuations. Across domain-specific reinforcement learning, multi-teacher on-policy distillation, and agentic reinforcement learning, ROSS consistently improves upstream checkpoints and outperforms baselines across mathematics, code generation, instruction following, and software engineering. On Qwen

---

### [210] Cognitive Expert Language Models Better Align with the Corresponding Brain Systems

**链接**: https://arxiv.org/abs/2609.36239
**作者**: Zhivar Sourati, Mengxuan Helen Wu, Nona Ghazizadeh, Jonas Kaplan, Morteza Dehghani, Samuel A. Nastase
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can predict human brain activity across a variety of brain regions during natural language comprehension. Typically, however, LLM-brain alignment is measured using one model for different regions of the brain, and then model performance is summarized across regions. This one-model-fits-all approach ignores the functional specialization of brain regions. In this study, we assess whether a model oriented toward a particular cognitive domain aligns better with the brain system dedicated to that domain. Through prompting and fine-tuning, we first build expert LLM variants for six domains: sensory, spatial, numerical, reasoning, social, and abstract processing. We then examine whether each expert best predicts activity in the brain region associated with the corresponding cognitive domain. Consistent with our hypotheses, each expert's representations align more closely with the brain system most associated with the matching domain than do other experts. This hol

---

### [211] Alignment Forecasting: Predicting Misalignment From Training Data

**链接**: https://arxiv.org/abs/2609.35805
**作者**: Chen Yueh-Han, Bruce W. Lee, Ilia Sucholutsky, Tomek Korbak
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training a language model on data with a narrow flaw can sometimes make the model broadly misaligned. Inspecting the data at face value often does not settle whether it will emerge, and today it is caught only after training, by auditing the resulting model. To complement post-hoc audits, we introduce Alignment Forecasting: the task of predicting alignment failures before training. Given a target model, a fine-tuning dataset, and a failure mode such as deception or sycophancy, a forecaster outputs the probability that fine-tuning would meaningfully increase that failure mode. To measure progress on alignment forecasting, we introduce ALIGNMENTFORECASTBENCH, a benchmark of over 5,000 forecasting questions spanning 17 target models, 32 datasets, and 16 failure modes. Frontier models prompted directly perform poorly on ALIGNMENTFORECASTBENCH. We therefore propose a forecasting scaffold in which an LLM reads the dataset and rates how strongly and broadly it pushes the model toward misbehav

---

### [212] Automated Evaluation of Multi-Turn Dialogues in In-Car Conversational Assistants

**链接**: https://arxiv.org/abs/2609.35812
**作者**: Vaishnav Negi, Lev Sorokin, Soroosh Tayebi Arasteh, Andrea Stocco
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-car conversational assistants (ICAs) are increasingly integrated into vehicles to support route planning, vehicle control, and information access. Ensuring their reliability is challenging due to multi-turn interactions, the absence of explicit ground truth, and strict safety constraints. Existing evaluation techniques fall short, as they target single-turn settings and fail to capture constraint handling, context retention, and safety-critical behavior across turns. We propose an automated framework for testing the multi-turn conversational capabilities of ICAs. The system is treated as a black box and evaluated via closed-loop simulation with a strategy-guided user simulator, an adversarial strategy manager, and a two-tier LLM judge assessing turn-level failures and conversation-level quality. We evaluate the approach on an industrial ICA with six LLM backends and twelve human annotators. The automated judge shows substantial agreement with humans, and strategy guidance uncovers 2

---

### [213] KV-Kaizen: Learning Context-Adaptive Cache Compression Choices

**链接**: https://arxiv.org/abs/2609.37988
**作者**: Joao Monteiro, Louis B\'ethune, Anastasiia Filippova, Sonia Laguna, David Grangier, Marco Cuturi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As the context size of text processed with an LLM grows, the size of KV caches can outstrip the memory allocated for the original model weights. This impacts LLM throughput negatively, since decoding is memory-bound and decode cost grows with cache size. Recent work alleviates this bottleneck by discarding the least relevant tokens. Eviction introduces a tension, since a one-off decision to discard content may prove detrimental later. Instead, we focus on alternative choices that can lead to cache compression without evicting tokens. We achieve this by learning a selector that is able to produce, based on context, a per-layer cache configuration towards an overall compression budget. The selector operates along three axes: sharing one cache across layers (depth), caching at fewer bits (precision), or truncating the low-rank latent cache representations (rank). We call the resulting method KV-Kaizen, for the many small per-layer choices it compounds. We observe that these interventions 

---

### [214] Cheap to Hypothesize, Costly to Verify: The Defense Surface of Agentic Vulnerability Discovery

**链接**: https://arxiv.org/abs/2609.35909
**作者**: Kaikai Zhang, Zihan Zhang, Yuchong Xie, Zesen Liu, Shuangjie Yao, Zhixiang Zhang 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents turn vulnerability discovery into a repository-scale search: they generate many vulnerability hypotheses but can verify only a subset under a finite budget. We show that autonomous vulnerability discovery exhibits a hypothesis-verification asymmetry, where verifying a candidate hypothesis through reachability analysis, execution, and proof-of-concept construction is substantially more expensive than forming it. Under a finite resource budget, this makes autonomous discovery a resource-bounded selective-verification process, further exposing verification effort as a unique defense surface. We present RedHerring, which inserts certifiably safe decoys that divert verification effort from real vulnerabilities. Each decoy combines a CVE-derived vulnerability chain that attracts verification with a false bridge that keeps its dangerous sink unreachable. A private certificate lets the defender verify this property efficiently, while establishing the same fact from the re

---

### [215] Scaling Influence Functions in LLMs through Eigenbasis-Corrected One-Bit Gradient Projection

**链接**: https://arxiv.org/abs/2609.37842
**作者**: Jaeseung Heo, J Rosser, Dongwoo Kim
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Influence functions estimate how individual training examples affect the behavior of large language models (LLMs). Analyzing how training data influence different behaviors of an LLM involves repeated influence computation. Reusing stored training gradients reduces the computational cost, but storing full gradients is prohibitively expensive at LLM scale. We study how to compress these gradients while preserving influence estimates for future queries that are unknown at storage time. Through a worst-case analysis, we characterize the optimal fixed-dimensional linear representation and propose eigenbasis-corrected one-bit gradient projection (EOGP) to approximate it at scale. Specifically, EOGP uses EK-FAC to reduce gradient dimensionality, then applies PCA within the retained subspace to learn compression directions from the training gradients. We then apply one-bit quantization to the resulting coordinates, allowing more coordinates to be retained within a fixed storage budget. On GPT

---

### [216] Multi-Site Real-World Performance of Commercial AI for Pulmonary and Incidental Pulmonary Embolism Detection

**链接**: https://arxiv.org/abs/2609.37750
**作者**: Aawez Mansuri, Mohammadreza Chavoshi, Theodorus Dapamede, Wasif Bala, Beatrice Brown-Mulry, Rohan Isaac 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pulmonary embolism (PE) is a leading cause of cardiovascular mortality, yet the real-world performance of FDA-cleared AI detection models remains incompletely characterized. We retrospectively evaluated two FDA-cleared AI algorithms from a single commercial platform (Aidoc Medical BriefCase), one for PE triage on dedicated CT pulmonary angiography (CTPA; n = 30,678) and one for incidental PE (iPE) detection on routine contrast-enhanced CTs (n = 37,191), across a 17-facility academic health system. Reference-standard labels were extracted from radiology reports using a validated LLM pipeline (97% accuracy, kappa = 0.94). The PE model achieved 86.8% sensitivity and 99.1% specificity, with sensitivity declining from 99.3% for saddle emboli to 72.9% for subsegmental PE, and from 89.7% for acute to 65.3% for non-acute PE. The iPE model achieved 73.5% sensitivity and 99.8% specificity. Both models demonstrated lower sensitivity than FDA-clearance benchmarks while exceeding cleared specificit

---

### [217] AdaKerNet: Neural Kernel Decoding for Task-Adaptive Prediction with Multimodal Large Models

**链接**: https://arxiv.org/abs/2609.36368
**作者**: Konstantinos D. Polyzos, Eleni Oikonomou, Tara Javidi
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large foundation models have been introduced with the promise of efficient adaptation to downstream tasks. Yet, under limited supervision, MLLMs, an important class of large foundation models, remain challenging to adapt to various downstream tasks. Adaptation typically relies either on MLLM parameter fine-tuning or on training neural-based decoders. Both approaches struggle under limited supervision, while fine-tuning additionally requires access to model parameters, which is often unavailable for closed-source models. We introduce AdaKerNet, a novel learnable task-adaptive neural kernel decoder. AdaKerNet is fully agnostic to the parameters of the underlying MLLM and operates solely on its (frozen) rich representations obtained from the diverse available modalities. AdaKerNet relies on (i) a set of learnable, Lipschitz-controlled multimodal features derived from these MLLM representations; (ii) a reference kernel that provides a soft structural prior on those features; and (iii) a li

---

### [218] Drag as Evidence: Motion-Grounded Latent Recomposition for Drag-Based Editing

**链接**: https://arxiv.org/abs/2609.36755
**作者**: Xinyu Pu, Hongsong Wang, Jie Gui, Pan Zhou
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern image editors excel at semantic manipulation and visual synthesis, yet remain limited in precise spatial control, motivating the development of drag-based editing. However, existing drag-based methods often struggle to balance drag accuracy with natural, plausible, and intent-aligned generation. We propose MoRe-Drag, a motion-grounded drag-based editing method. Our key insight is to treat pixel-space warping as coarse motion evidence, and to inject this evidence into the generative sampling trajectory. Specifically, MoRe-Drag performs region-aware latent recomposition over refinement, inpainting, and anchor regions, coupled with stage-adaptive conditioning that progressively shifts from motion-grounded structure formation to semantic refinement. We further support an instruction-free interface by adapting the MLLM-based text encoder for drag-aware instruction inference. Experiments on DragBench-SR and DragBench-DR show that MoRe-Drag substantially improves drag precision over st

---

### [219] ResComEmb: Effective and Efficient Multimodal Embedding via Residual Homogeneity Compression

**链接**: https://arxiv.org/abs/2609.37225
**作者**: Zijing Cai, Yuzhe Wang, Jingxian Zhu, Fengbin Zhu, Richang Hong
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have shown strong potential for universal multimodal representation learning. However, existing methods either compress each input into a single vector, limiting fine-grained expressiveness, or retain long sequences of visual-token vectors, incurring substantial storage and interaction costs. To resolve this trade-off, we propose ResComEmb, a trainable framework for effective and efficient universal multi-vector multimodal embedding. ResComEmb first encodes each input at native dynamic resolution into ordered global, intermediate, and fine-grained views. After MLLM contextualization and embedding projection, a trainable Residual Homogeneity Compression (RHC) module reduces within-granularity redundancy and cross-granularity repetition under explicit visual token budgets. Then, ResComEmb introduces a length-adaptive Bidirectional Late-Interaction Matching mechanism for robust query-document scoring, which averages the strongest token-level matche

---

### [220] UniAfford: Token-Routed Multitask Learning for Generalizable 2D-3D Affordance Perception

**链接**: https://arxiv.org/abs/2609.37264
**作者**: Yuhao Liu, Yiming Zhong, Hanqing Wang, Shaocheng Yan, Yuhang Zhang, Wenzhou Lyu 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Affordance perception aims to localize actionable regions supporting embodied interaction, yet 2D and 3D affordance grounding have evolved as separate problems, with different task definitions, supervision formats, datasets, and evaluation protocols. This fragmentation limits the learning of transferable object-affordance semantics across visual and geometric spaces. We propose Token Router for Tasks, a multitask training paradigm for MLLM-based systems that routes contextual hidden states to task-specific branches without requiring the language head to generate predefined markers. Routed states are supervised directly by branch-specific objectives, enabling dense prediction losses to shape shared MLLM representations. We instantiate this paradigm as UniAfford, a unified framework for generalizable 2D-3D affordance perception, together with UniAfford-Data, a dataset integrating pixel-level 2D annotations, point-level 3D annotations, and language instructions under a shared object-affor

---

### [221] From Sharp Eyes to Expert Mind: Internalizing Expert Knowledge in MLLMs for Tampered Text Detection

**链接**: https://arxiv.org/abs/2609.36145
**作者**: Kaiqing Lin, Songze Li, Shen Chen, Yunfei Guo, Xiaoye Qiu, Haodong Li 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tampered Text Detection (TTD) is essential for safeguarding document authenticity in security-critical workflows. Existing expert models are effective at capturing subtle manipulation traces but often generalize poorly across diverse document domains, while Multimodal Large Language Models (MLLMs) offer stronger semantic understanding and transferability yet remain insensitive to fine-grained forensic artifacts. This complementarity motivates us to investigate how expert forensic perception can be internalized into an MLLM rather than merely accessed through an external module. We identify a fundamental Double Mismatch that hinders this goal: a Spatial Precision Mismatch between coarse visual tokens and tiny tampered regions, and a Perceptual Granularity Mismatch between semantics-oriented pre-training and low-level forensic perception. To address these challenges, we propose Expert Knowledge Internalization (EKI), a progressive two-stage framework that transfers forensic expertise int

---

### [222] OmniVCBench: Benchmarking Evidence-Grounded Multimodal Reasoning Towards AI Virtual Cells

**链接**: https://arxiv.org/abs/2609.37773
**作者**: Manyu Li, Xunkai Li, Yongfu Xiong, Yi Liu, Rong-Hua Li, Guoren Wang
**来源**: cs.AI q-bio.QM
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial Intelligence Virtual Cells (AIVCs) are envisioned as scientific agents that simulate cellular responses, explain underlying mechanisms, and support hypothesis-driven discovery. Existing AIVC benchmarks, however, operate primarily at the simulation layer, motivating complementary evaluation of how models interpret experimental evidence and formulate biological hypotheses. We introduce OmniVCBench, a figure-centric, source-traceable benchmark for the interpretation component of an AIVC. It contains 6,077 curated single- and multi-subfigure question--answer pairs derived from figures and experimental contexts in the scientific literature. Guided by Bloom's taxonomy, we instantiate interpretation-layer counterparts of the AIVC Predict--Explain--Discover agenda through three scientific reasoning tasks. We further introduce AIVC-Judge, a task-conditioned MLLM-as-a-judge framework with category-specific, reference-aware rubrics for evaluating open-ended responses. A complementary M

---

### [223] Representational and Functional Robustness to Electrode Montages in EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.36288
**作者**: Jakob Steglich, Justus Meyer zu Bexten, Shakiba Moradi, Laure Ciernik, Simon M. Hofmann, Mina Jamshidi Idaji
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models (EEG-FMs) are intended to generalize across different datasets by learning representations that, ideally, are invariant to dataset-specific EEG configurations such as electrode montages. However, EEG-FMs that accept different montages as input do not guarantee that representations and predictions remain stable across different electrode configurations, especially outside the training setting. In this work, we investigate the effects of different electrode montages through a joint functional and representational analysis of four EEG foundation models selected to span distinct montage-handling designs. We evaluate embeddings on cross-subject resting-state eyes-open/closed and within-subject motor-imagery classification under spatially informed channel reduction. Functional robustness is tested through the generalizability of linear probes across channel counts, while representational robustness is assessed through within-subject similarity and preservation of betwee

---

### [224] Best Practices in EEG Analysis: Preprocessing, Modeling, and Machine Learning

**链接**: https://arxiv.org/abs/2609.36609
**作者**: Parsa Razmara, Woojae Jeong, Aditya Kommineni, Raymundo Cassani, Richard Leahy, Takfarinas Medani
**来源**: eess.SP cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) analysis requires careful choices in preprocessing, statistical modeling, and machine learning because EEG signals are highly susceptible to artifacts, volume conduction, low signal-to-noise ratio, and substantial inter-subject variability. This chapter provides a practical and methodological guide to modern EEG analysis, spanning EEG preprocessing, artifact removal, filtering, bad-channel detection and interpolation, re-referencing, independent component analysis (ICA), and preprocessing of simultaneous EEG-fMRI recordings. We review major approaches for computational EEG analysis, including event-related potentials (ERPs), time-frequency analysis, functional and effective connectivity, source localization, multivariate decoding, permutation testing, and multiple-comparison correction. We then examine machine-learning methods for EEG, from feature-based classifiers to deep learning and emerging EEG foundation models, with emphasis on cross-subject generali

---

### [225] PHASE: A Physiology-Guided Hierarchical Foundation Model for Intracranial EEG

**链接**: https://arxiv.org/abs/2609.36087
**作者**: Yipeng Zhang, Chenda Duan, Yuanyi Ding, Tianyi Wang, Atsuro Daida, Masaki Izumi 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinicians and neuroscientists have long analyzed intracranial electroencephalography (iEEG) through directly measurable physiological characteristics, which carry much of the information that downstream tasks depend on. Recent iEEG foundation models learn by reconstructing or predicting their inputs, which leaves the retention of these characteristics implicit. They are also evaluated mainly on cognitive decoding and a narrow clinical task, i.e., seizure detection. On a broad, clinically relevant benchmark such as Omni-iEEG, they remain below task-specific models when used frozen. We introduce PHASE, a physiology-guided foundation model that makes these characteristics explicit learning targets, pairing them with masked latent prediction in a temporal stage (PHASE-T) within each channel and a spatiotemporal stage (PHASE-ST) across synchronized channels. PHASE is pretrained on heterogeneous recordings from 222 participants at nine clinical sites. On all five Omni-iEEG clinical tasks, f

---

### [226] NeuroECG: ECGFounder-Based Deep ECG Representation for EEG-Free Neurological Prognostication After Cardiac Arrest

**链接**: https://arxiv.org/abs/2609.18891
**作者**: Jiajun Gao, Yi Zhao, Chenyang Xu, Yuxi Zhou, Hao Wang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [227] NeuroDyn-EEG: An Interpretable Pre-trained Model for EEG Based on Neural Dynamics

**链接**: https://arxiv.org/abs/2609.36773
**作者**: Yi Cui, Tong Zhao, Jiaxin Lei, Chuyi Yang, Yifan Cui, Ling Zhang 等 (8 人)
**来源**: cs.NE
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical scalp electroencephalography (EEG) offers a noninvasive window into neural dynamics of neuropsychiatric disorders. However, discriminative deep models often lack anatomically indexed physiological interpretability. We propose NeuroDyn-EEG, a pretraining framework integrating generative priors from neural dynamics. It couples an extended Jansen-Rit neural mass model, leadfield-based source projection, and simulation-based parameter inversion. Trained on synthetic parameter-EEG pairs within physiological ranges, NeuroDyn-EEG estimates 11 regional parameter families across 90 AAL regions plus one global parameter from standard 19-channel EEG, using only ~2.43M trainable parameters. We evaluate the framework across three levels. First, controlled simulations demonstrate robust parameter recovery under diverse noise conditions, while real resting-state EEG evaluations confirm spectral and phase consistency in an inverse-forward closed loop. Second, on four clinical benchmarks (AD65

---

### [228] GRFBrain: Graph-Structured Rectified Flows for EEG Dynamic Modeling

**链接**: https://arxiv.org/abs/2609.37934
**作者**: Haohui Jia, Zheng Chen, Jathurshan Pradeepkumar, Xu Cao, Yasuko Matsubara, Yasushi Sakurai 等 (7 人)
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Forecasting time-varying functional connectivity from electroencephalography (EEG) requires modeling both history-dependent trends and structured variability across channels. Conditional flow matching provides a framework for distributional forecasting, yet it remains unclear whether graph-informed source distributions offer practical advantages over isotropic noise and strong deterministic predictors. We introduce a graph-structured residual flow framework that separates conditional mean prediction from stochastic residual transport. A history-only predictor estimates the future connectivity graph, while a graph Gaussian source encodes dependencies derived from past connectivity through a Laplacian-based covariance. A conditional velocity field transports source samples to future graph residuals, with transport time explicitly distinguished from physical EEG time. Our study identifies the conditions and controls needed to distinguish useful residual transport from improvements attribu

---

### [229] Online Inference of Human Intention as a Latent Control State from Single-Trial EEG

**链接**: https://arxiv.org/abs/2609.35778
**作者**: Xiaowei Jiang, Daniel Leong, Yu-Cheng Chang, Thomas Do, Chin-Teng Lin
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human intention can be modeled as a latent internal state that modulates how sensory information is evaluated and translated into action in human-machine systems. However, most existing brain-computer interfaces (BCIs) rely on control signals tightly coupled to externally imposed stimulation and do not explicitly infer whether perceived stimuli align with a user's internal goals. Here, we investigate whether intention can be inferred as a latent, goal-dependent state from single-trial electroencephalography (EEG). We introduce a stimulus-based paradigm in which intention is specified by an internally cued target category, while object identity varies independently across stimuli. To estimate intention under single-trial neural variability, we propose an interpretable fuzzy prototype-based network that maps each trial onto interpretable fuzzy prototypes encoding intention-specific dynamics. The model represents intention-related neural activity using a compact set of fuzzy prototypes wi

---

### [230] Hybrid Ensemble Learning for EEG-Based Epileptic Seizure Forecasting

**链接**: https://arxiv.org/abs/2609.35876
**作者**: Mason Dana and Khandaker Mamun Ahmed
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Epileptic seizure forecasting aims to provide actionable warnings before seizure onset, yet patient-independent generalization and false-alarm control remain major challenges. We propose a calibrated hybrid ensemble for EEG-based seizure forecasting that combines five deep learning models and three classical machine learning models through a logistic regression stacking meta-learner. The proposed pipeline integrates signal preprocessing, handcrafted feature extraction, class-imbalance handling, probability calibration, and clinically motivated post-processing. We evaluate the framework on CHB-MIT using strict Leave-One-Patient-Out (LOPO) cross-validation, with threshold and post-processing parameters selected only on held-out meta data. On the filtered cohort, excluding patients with anomalous preictal rates below 1\% or above 15\%, the model achieves 74.2\% seizure-level sensitivity at 1.24 false alarms per hour, with an average warning time of 16.9 minutes. A test-tuned oracle constr

---

### [231] Spatiotemporal Hyperedges for EEG Seizure Detection and Prediction

**链接**: https://arxiv.org/abs/2609.37730
**作者**: Hyunju Kim, Sheo Yon Jhin, Noseong Park, Nabil Imam
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Seizure detection and prediction from EEG are clinically important but challenging because seizures are rare, temporally localized, and propagate as coordinated events across multiple channels. Recent dynamic graph neural networks model this by running a temporal model over a sequence of per-time-step pairwise channel edges. However, this pairwise construction misses the spatiotemporal coupling that constitutes a seizure, at substantial training cost. We propose HyBrain, which summarizes spatiotemporal EEG evidence through a small set of soft hyperedges rather than pairwise edges. A per-channel Mamba backbone produces one token per (channel, second), and a spatiotemporal hyperedge block pools these tokens into E_h shared group embeddings through soft memberships and broadcasts them back. The same encoder serves three downstream tasks: window-based detection, one-second point-wise detection, and preictal seizure prediction. On TUSZ and CHB-MIT, HyBrain achieves the best AUROC on every r

---

### [232] Structured Visual Target Learning For Cross-Subject eeg-to-image retrieval

**链接**: https://arxiv.org/abs/2609.36971
**作者**: Salini Yadav, Taveena Lotey, Micka\"el Coustaty, Pravendra Singh, Partha Pratim Roy
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-subject EEG-to-image retrieval requires a neural represen- tation trained on source subjects to remain aligned with a visual embedding space for an unseen subject. Whereas existing methods primarily focus on the EEG side, we address this problem from the perspective of the visual target. Our approach preserves the spatial information of the Perception Encoder, converts its patch grid into a compact set of learned visual views, and aggregates them for each image with a block-structured, content-dependent router. The target is learned jointly with the EEG encoder through contrastive learning with MMD regularization across source subjects. For deployment, we propose a training-free representation refinement that aligns frozen embeddings without updating either encoder. Under leave- one-subject-out evaluation on THINGS-EEG2, the structured target achieves 35.3%/65.6% Top-1/Top-5 accuracy, the best among com- pared methods. Refinement raises this to 48.1%/77.1%, an 18.5% Top-1 gain ov

---

### [233] From Neurons to Conversation: Speech Brain-Computer Interfaces

**链接**: https://arxiv.org/abs/2609.36736
**作者**: Moein Khajehnejad, Forough Habibollahi, Tommaso Boccato, Margarida Sousa, Michal Olak, Francesco Jamal Sheiban 等 (7 人)
**来源**: cs.HC cs.CL q-bio.NC
**匹配关键词**: BCI
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech brain-computer interfaces (BCIs) aim to restore communication by transforming neural activity related to speech, language, or communicative intent into external outputs such as text, synthesized voice, or avatar control. Recent advances in intracortical and electrocorticographic recording, deep sequence models, and language-model-assisted decoding have enabled rapid progress, including high-performance attempted-speech decoding and increasingly naturalistic speech synthesis. Yet these achievements also reveal that speech BCIs are not simply neural-to-text decoders. They are adaptive clinical systems in which neural representations, recording hardware, decoding architectures, language priors, feedback, and user learning interact over time. Here, we synthesize speech BCI research from a system-level perspective. We first examine the neural substrates of speech and language, emphasizing their hierarchical, distributed, temporally structured, and non-stationary organization. We then

---

### [234] Boosting Knowledge Graph Foundation Models via Enhanced Negative Sampling

**链接**: https://arxiv.org/abs/2605.27023
**作者**: Yinan Liu, Wenjin Xu, Zhiyuan Zha, Xiaochun Yang, Bin Wang
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [235] Tabby: An Open Pretraining Recipe for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.13956
**作者**: Shifeng Xie, Bahaeddine Abdessalem, Zehao Xiao, Youssef Attia El Hili, Ambroise Odonnat, Zhiwei Dong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [236] Support-Set Target Leakage in Relational Foundation Models during In-Context Learning: Model Dependence and Evaluation Reliability

**链接**: https://arxiv.org/abs/2609.36417
**作者**: Roshan Reddy Upendra, Alexandre Dorais, Joe Meyer, Andrew Pouret, Anastasios Lambrianos Stappas, Dinesh Katupputhur Ramprasath 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Relational in-context learning (ICL) uses labeled support examples and their linked relational context to predict labels for new queries. This creates a failure mode when target-derived features are present in the support context but unavailable for the query. We study this setting as support-set target leakage. We construct 20 controlled target-derived features that vary in signal fidelity, representation, semantic transparency, coverage, and zero-, one-, and two-hop relational placement, and evaluate them across 13 RelBench tasks and five relational ICL configurations that vary the ICL head, message-passing depth, pretraining cohort, or relational encoder architecture. We evaluate matched 0-hop, 1-hop, and 2-hop leakage settings, together with a Full leakage condition containing all 20 leaker columns. Within the tested configurations, target-table (0-hop) and Full leakage produce the largest aggregate deviations from clean evaluation, while higher-hop effects are often weaker, consis

---

### [237] RAE-PPG: Duration-Grounded Retain-and-Extend Pretraining for PPG Foundation Models

**链接**: https://arxiv.org/abs/2609.36794
**作者**: Suyeong Lee, Hochang Lee, Seokyong Sheem, Daekyum Kim
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Signal features derived from photoplethysmography (PPG) require different signal durations to characterize. Existing PPG foundation models treat duration as a pretraining or evaluation condition rather than using the different durations required by PPG features to organize self-supervision. We hypothesize that self-supervision should expand with signal duration, allowing a single encoder to progressively acquire additional features while preserving and reusing earlier learning. We introduce Retain-and-Extend PPG (RAE-PPG), which trains a single Transformer encoder successively on 10 s, 30 s, and 240 s inputs, adding supervision for signal features supported by each longer observation. The encoder is partitioned into duration-specific parameter groups, allowing later stages to reuse earlier groups while updating only the group assigned to the current stage. Selected earlier targets are reused to supervise later stages, encouraging the corresponding features to remain accessible in longe

---

### [238] PolyOCR-Venus: Unified OCR Foundation Models for Text-Centric Visual Intelligence

**链接**: https://arxiv.org/abs/2609.37712
**作者**: GuangJian Team: Kaili Huang, Yongshuo Zhang, Bingtao Fu, Changjiang Jiang, Chenfan Qu, Chenfeng Zhang 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optical Character Recognition (OCR) is evolving from plain-text transcription toward general visual intelligence, requiring models to recognize, localize, and reason over textual information in complex visual environments. However, existing OCR systems often excel at only some tasks and struggle to balance recognition, parsing, and reasoning across scenarios. In this report, we present PolyOCR, a family of unified OCR foundation models of varying scales. PolyOCR combines a shared instruction-following framework with a large-scale data engine that converts heterogeneous visual resources into quality-verified OCR supervision. We introduce Competence-Guided Policy Optimization, which combines verifier-based Group Relative Policy Optimization with on-policy distillation through sample-wise routing based on teacher reliability and the teacher--student competence gap. We also introduce OCRBench v2.1, our revision of OCRBench v2 with manually verified annotation corrections and task-aligned s

---

### [239] Loss-Guided Pretraining Data Selection for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2609.37255
**作者**: Yike Li and Shaoxu Song and Jianmin Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) are pretrained on heterogeneous collections containing billions of observations, yet their training windows are typically sampled without estimating whether they provide useful learning signal. We introduce a static data-selection framework that scores each window with a reference forecaster and retains an intermediate interval within every source dataset. Specifically, we connect forecasting loss to optimization difficulty by showing that normalized squared loss controls the per-sample gradient norm under a local Jacobian condition. We then define a reference loss score and apply dataset-stratified selection to preserve the diversity of samples. Across various TSFM architectures, our method outperforms random selection by an absolute margin and even improves both relative MASE and CRPS over full-data pretraining by retaining fewer candidate pretraining windows. Further analyses show strong cross-scale and cross-architecture score correlations, ind

---

### [240] TabFM-Auto: Self-Evolving Pipelines for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.37989
**作者**: Deqing Fu, Huangyuan Su, Rajat Sen, Taman Narayan, Sujay Sanghavi, Abhimanyu Das 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models achieve strong zero-shot accuracy on structured data by pretraining on synthetic tables, but they ignore the column names, task descriptions, and auxiliary files that carry dataset semantics. Meanwhile, self-evolving machine learning engineering (MLE) agents train models from scratch on each dataset, yet jointly searching over features, architectures, and hyperparameters is noisy and prone to overfitting. We introduce TabFM-Auto, which pairs a tabular foundation model, TabFM, with a language model agent that evolves the data pipeline around it. Guided by dataset metadata and validation feedback, TabFM-Auto iteratively refines data cleaning, feature engineering, context selection, and post-processing to reduce TabFM's error. Across all 51 datasets of the TabArena benchmark, five TabFM-Auto configurations with different agents and language models take the top five overall positions, and the best raises TabFM from 1785 to 2013 Elo. The discovered pipelines also t

---

### [241] Multimodal LLMs Outperform Pathology Foundation Models in Cross-Domain Histological Similarity

**链接**: https://arxiv.org/abs/2609.32876
**作者**: Yishu Zhang, Yun Li, Daiwei Zhang
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [242] Scalable Heterogeneous Graph Foundation Models for Data-Driven Optimal Power Flow in Smart Grids

**链接**: https://arxiv.org/abs/2605.23194
**作者**: Massimiliano Lupo Pasini, Yijiang Li, Kibaek Kim, Teja Kuruganti
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [243] BarcodeMAE+: Rethinking Masked Pretraining and Global Representations for DNA Barcode Foundation Models

**链接**: https://arxiv.org/abs/2609.35877
**作者**: Monireh Safari, Pablo Millan Arias, Scott C. Lowe, Lila Kari, Angel X. Chang, Graham W. Taylor
**来源**: q-bio.GN cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many DNA foundation models are pretrained by masking parts of a sequence and asking the model to reconstruct them. Standard masked pretraining exposes the encoder to special [MASK] tokens that are absent at inference, creating a mismatch between training and downstream use. The role of an explicit global sequence representation such as a [CLS] token and how it should be trained also remain poorly understood for DNA barcodes. We introduce BarcodeMAE+ and study model architecture, global [CLS] representation, and auxiliary pretraining objectives across arthropod COI (BIOSCAN-5M) and fungal ITS (UNITE+INSD) barcodes. Across both barcode regions, the encoder-decoder MAE-LM architecture outperforms its matched encoder-only counterpart in nearly all evaluated configurations, supporting MAE-LM as an effective architectural design for DNA barcode foundation models. A trained global [CLS] representation provides substantial additional gains: on BIOSCAN-5M, [CLS] accuracy increases from 47.53% w

---

### [244] Latent Inference-Time Guidance of Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.38058
**作者**: Chlo\'e Hashimoto-Cullen, Amaury Durand, Laurent Bozzi, Benjamin Guedj, Yannig Goude, Sylvain Le Corff
**来源**: stat.ML cs.LG stat.ME
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) currently provide state-of-the-art results in forecasting tasks. They are available out-of-the-box and rely on in-context learning to make their predictions, which makes the quality of their performance highly sensitive to the user-selected lookback, covariates, horizon and training data distributions. In practise, the quality of the forecasts are variable but complementary, which highlights the need for a principled ensembling approach, rather than selecting the best context. This paper introduces Latent Inference-Time Guidance for TSFMs, which adaptively combines a pool of TSFM forecasts through a time-dependent latent space with independent components. The framework comes equipped with identifiability and reconstruction guarantees, whilst maintaining the off-the-shelf aspect of foundation models. We provide experiments on datasets at various frequencies and from multiple domains: these show that the approach is competitive with traditional ensem

---

### [245] RynnValue: Scaling Robotic Value Foundation Models with Temporal Distance

**链接**: https://arxiv.org/abs/2608.09853
**作者**: Dongchi Huang, Hongyin Zhang, Bohan Hou, Siteng Huang, Zhian Su, Hang Guo 等 (10 人)
**来源**: cs.RO cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [246] Support-Set Target Leakage in Relational Foundation Models during In-Context Learning: Impact, Detection, and Mitigation

**链接**: https://arxiv.org/abs/2609.36384
**作者**: Roshan Reddy Upendra, Alexandre Dorais, Joe Meyer, Andrew Pouret, Anastasios Lambrianos Stappas, Dinesh Katupputhur Ramprasath 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Relational in-context learning (ICL) conditions predictions on the labeled support examples and their linked tables, creating a failure mode when the support set contains target-derived features that are unavailable for the query. We formulate this problem as support-set target leakage, distinct from leakage during dataset construction, temporal splitting, or representation learning. Here, the target-derived (leaker) columns are present only in the labeled support set during relational in-context inference, while queries remain clean. We construct 14 synthetic leaker types, corresponding to 20 columns, spanning proxies with different noise levels, coverage, modalities, semantic transparency, and relational distances. We evaluate a frozen relational encoder with an ICL head on held-out RelBench databases and use Integrated Gradients (IG) to rank and remove suspicious columns. Our results show that the effect of support-set leakage varies across tasks and relational distances. Target-tab

---

### [247] Architecture Alignment With Sparse Priors in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.36883
**作者**: Tianqi Zhao, Tianyi Zhuang, Shuo Duan, Guanyang Wang, Yan Shuo Tan, Qiong Zhang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are increasingly popular because they deliver strong predictions on new datasets through in-context learning, without task-specific training or extensive tuning. Yet released TFMs differ simultaneously in their pretraining priors, architectures, and objectives, obscuring their respective inductive biases. We therefore examine one concrete capability: irrelevant-feature suppression. Across synthetic tasks and real-world datasets, adding null features causes substantially greater predictive degradation in the row-token model TabDPT, whereas the cell-token alternating-axis model TabPFN v2 and other TFMs remain comparatively stable. This gap motivates us to ask whether architecture contributes to irrelevant-feature suppression. Because released TFMs remain confounded by other design choices, we train streamlined row-token and alternating-axis transformers under identical sparse-to-dense linear priors. Exact Bayes analysis shows that sparse prediction requir

---

### [248] Towards Scalable Context-Aware Single-Cell Spatial Transcriptomics Prediction from Histology Images

**链接**: https://arxiv.org/abs/2609.36429
**作者**: Zijun Gao, Chunbin Gu, Jinxi Xiang, Xiangde Luo, Pheng-Ann Heng
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting gene expression from H&E-stained histology images offers a scalable alternative to costly spatial transcriptomics, yet most existing methods operate at the spot level, where signals from multiple cells are aggregated and critical cellular heterogeneity is obscured. Extending this paradigm to single-cell resolution is non-trivial. Naively applying pathology foundation models faces a scale mismatch: their patch-level representations mix multiple cells, whereas per-cell cropping or resizing distorts morphology and removes local context. Conversely, segmentation-based models without strong pretrained visual encoders often lack the morphological representation capacity needed for accurate molecular prediction and inherit errors from imperfect cell boundary masks. Here, we present CELLO, an efficient end-to-end framework that performs a single pathology foundation model forward pass per image and uses grid sampling to extract location-specific features for all cells simultaneously

---

### [249] Complementary Retrieval-Augmented Prompting for Consistent Long-Form Video Generation

**链接**: https://arxiv.org/abs/2609.37407
**作者**: Xianghan Wei, Xiaoda Yang, Zhi Wang, An Pan, Daoan Zhang, Huayi Zhang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While recent video foundation models excel at generating high-quality short videos, long-form video generation remains a critical challenge, where a major bottleneck lies in conditioning independently generated shots to preserve consistent characters, scenes, and objects throughout a story. Existing training-free approaches typically condition target shots using retrieved historical visuals. However, these references often suffer from severe informational mismatch, either introducing irrelevant contextual redundancy or failing to provide the full combination of required elements for the target shot. To resolve this, we present Complementary Retrieval-Augmented Prompting, an agentic framework that strategically aggregates a compact set of mutually supportive historical references to achieve complete and targeted conditioning for long-form video generation without retraining or modifying the underlying generator. Specifically, our framework explicitly models the visual elements required 

---

### [250] Learning Expressive and Compositional Motion Representation via Spectral Skills

**链接**: https://arxiv.org/abs/2609.37677
**作者**: Feiyang Wu, Chenxiao Gao, Chen Yang, Ye Zhao, Bo Dai, Anqi Wu
**来源**: cs.RO cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robotic foundation models offer a promising path toward general-purpose humanoid robot control, often through hierarchical architectures. However, their effectiveness depends on the command interface between the planner and the controller, which must support accurate execution while remaining easy to predict, and ideally allow new behaviors to be composed from prior ones. In this work, we introduce spectral skills, a latent representation of this interface that meets these requirements through predictive representation learning. By design, spectral skills compactly encode short motion segments and are learned by predicting subsequent motion rather than reconstructing the encoder input. On a 29-DoF humanoid, a controller conditioned on spectral skills reduces global tracking error by 62\% relative to the state of the art. The same frozen controller chains independently encoded skills without a separate transition policy. It also composes new behaviors by adding orthogonal directions to 

---

### [251] Label Less, Learn More: Resource-Efficient Active Semi-Supervised Learning for Onboard Satellite Image Annotation

**链接**: https://arxiv.org/abs/2609.37481
**作者**: Ahmed Abdelnaby, Mohamed Elmahallawy, Marius Bernahrndt, Tobias Hecking
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale pervasive sensing increasingly relies on high-resolution satellite imagery, yet task-specific onboard vision is constrained by costly annotation and limited computation, memory, energy, and communication resources. Existing approaches largely rely on either data-hungry supervised learning or large vision-language foundation models, limiting efficient adaptation and deployment under these constraints. We present SatLabel, a resource-aware learning framework that transforms limited satellite labels into progressively refined onboard models through adaptive sample acquisition and semi-supervised model adaptation. Rather than repeatedly training on uniformly sampled labels, SatLabel closes the loop between model uncertainty, class imbalance, and pseudo-label quality to selectively acquire informative samples while exploiting abundant unlabeled imagery. This enables a compact student to adapt to target sensing domains with reduced annotation and inference costs. We further intro

---

### [252] Adapting Linear-Time Architectures for Tabular In-Context Learning

**链接**: https://arxiv.org/abs/2609.36337
**作者**: David Schnurr, Felix Sarnthein, Thomas Hofmann, Imanol Schlag
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models achieve strong performance by conditioning on labelled examples in context, but softmax attention limits their use on large datasets. Existing linear-time alternatives, however, are mostly causal, and their potential for tabular in-context learning (ICL) remains underexplored. To address this, we (1) revisit causal training setups, (2) compare linear sequence mixers, and (3) investigate their ICL generalisation beyond the pretraining context length. First, we show that the best training setup for causal models resembles next-token prediction. Then, perhaps surprisingly, the most promising linear sequence mixer is causal: DeltaNet outperforms even non-causal linear attention. However, it degrades beyond $2$-$4\times$ the pretraining context length, and existing mitigation strategies such as bidirectionality defer the problem at best. A hidden-state oracle shows that this is not a capacity problem. Instead, our analysis points to an instability in the recurrent 

---

### [253] What You Observe Determines How You Identify Causal Effects: Evaluating Causal Models across Observational Views

**链接**: https://arxiv.org/abs/2609.36881
**作者**: Heejin Jung, Gyeongdeok Seo, Hoyoon Byun, Joseph Lee, Kyungwoo Song
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal foundation models (CFMs) pre-trained on data generated from various structural causal models (SCMs) have been proposed for estimating causal effects from observational data. However, differences in pre-training environments and evaluation protocols make it difficult to assess how their performance depends on the information available for causal identification. To enable controlled comparisons, we introduce CausalIDView, a multi-view benchmark that holds fixed SCM realization and target estimand while varying only the observational view available to the estimator. Each observational view corresponds to a distinct identification regime under the benchmark's maintained causal assumptions. Across these matched views, no CFM consistently performs best and model rankings vary substantially. Under controlled structural changes, CFMs exhibit model-specific failures to maintain stable estimates when true effects are unchanged and to track genuine effect changes. We also examine whether c

---

### [254] FLOORA: A Human-Aligned Domain-Specific Language Model for Architectural Design

**链接**: https://arxiv.org/abs/2609.36064
**作者**: Sahand Rezaei-Shoshtari, Patryk Wozniczka, Shu Ishida, Gregg Streuber, Farnoosh Javadi, Jeffrey Landes 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are powerful generators, but many engineering domains require structured representations that general-purpose systems handle poorly. We introduce FLOORA (Floor Layout Optimization with RL Alignment), a family of small domain-specific language (DSL) models for architectural layout generation. With specialized data and alignment, our 0.6B model outperforms much larger frontier models, achieving VLM judge win rates up to 92.0% on out-of-distribution real-world buildings and 96.0% on synthetic buildings. Human evaluations further corroborate these results, with FLOORA selected as the best model in 89.3% of evaluations. FLOORA combines a token-efficient DSL, custom tokenization, domain-specific pretraining, supervised fine-tuning (SFT), and reinforcement learning (RL) with learned human-preference and verifiable rewards. This pipeline improves architectural and geometric validity, supported by extensive empirical evaluation and ablation studies. Although focused on archite

---

### [255] A foundation model for energy and radiation systems built on heterogeneous scientific interfaces

**链接**: https://arxiv.org/abs/2609.38067
**作者**: Samrendra Roy, Tapas Tripura, Yoon Pyo Lee, Souvik Chakraborty, Syed Bahauddin Alam
**来源**: cs.LG physics.comp-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific foundation models are commonly evaluated after heterogeneous physical problems have already been translated into a compatible gridded, tokenized or symbolic representation. This leaves the scientific interface outside both the pretrained model and the audit of what is actually reused. We study the complementary setting in which boundary histories, sparse monitor records and loading histories retain their native inference classes and their outputs remain on Cartesian, latitude-longitude and unstructured domains. GEODE couples task-specific scientific interfaces to a shared routed library of wavelet operators. A single jointly pretrained model represents cavity flow, radiation dose and elastoplastic stress, then acquires a heat exchanger and a reactor subchannel by training a private interface containing 2.1% of its parameters. Earlier predictions remain unchanged by parameter isolation, whereas unrestricted fine-tuning degrades them by factors of 14-29. Crucially, preservatio

---

### [256] Flattening the Connectome Spectrum: A Spectral Filter for FC Induces a Pretraining Target for fMRI Encoders

**链接**: https://arxiv.org/abs/2609.37642
**作者**: Giovanni Marraffini, Victoria Shevchenko, Carlo Alberto Barbano (UNITO), Demian Wassermann (MIND)
**来源**: cs.AI cs.LG q-bio.NC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised pretraining reshaped prediction in language and vision, and brain foundation models (BFMs) inherited its promise. Representations learned from large unlabelled corpora should capture individual functional dynamics and generalise across cohorts. However, kernel ridge regression (KRR) fitted on functional connectivity (FC) matrices still predicts individual phenotypes more accurately than any BFM we tested. In this paper, we show that KRR is weighted by the eigenvalues of the FC which are miscalibrated for phenotype prediction. We apply an efficient spectral filter to recalibrate the eigenvalues of each subject's FC matrix, enabling the model to exploit more inter-individual variance. Across the 5 datasets, 11 parcellations and 6 prediction targets we tested, we match or exceed the KRR baseline. Based on this finding, we then pretrain a small encoder model on about 4,000 hours of fMRI from 162 open datasets, whereby we align the pairwise similarities between the embedding

---

### [257] SFE-VGGT: Source-Free VGGT Distillation for Event-Based Monocular Depth Estimation

**链接**: https://arxiv.org/abs/2609.36929
**作者**: Thai Duy Nguyen, Addison Lin Wang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent event-based depth estimation methods successfully transfer geometric priors from vision foundation models via cross-modal distillation. However, their reliance on synchronized RGB-event pairs or depth annotations during training severely restricts practical deployment. To overcome this bottleneck, we propose SFE-VGGT, a novel source-free framework that distills the geometric priors of VGGT to the event domain without any paired RGB observations. Our core idea is to reconstruct surrogate frames directly from the target event stream to act as a frozen geometric teacher, entirely eliminating the need for genuine source RGB data. Crucially, as these surrogate frames inherently yield imperfect and spatially varying supervision, directly distilling from them propagates artifacts. To resolve this, we introduce a novel reliability-aware distillation strategy. This includes Density-Aware Feature Distillation to emphasize informative event regions, and Confidence-Weighted Depth Distillati

---

### [258] TaskBridge: Bridging Unsupervised Tabular Anomaly Detection and In-Context Learning via Virtual Tasks

**链接**: https://arxiv.org/abs/2609.36968
**作者**: Doyun Choi, Dooho Lee, Jaemin Yoo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unsupervised tabular anomaly detection (TAD) aims to identify anomalous rows in tabular data using normal training samples. While conventional methods rely on dataset-specific training and configuration search, recent tabular foundation models (TFMs) enable zero-shot anomaly detection on unseen datasets via in-context learning. Most TFM-based approaches, however, require anomaly-specific pretraining from scratch, making detection inherently dependent on synthetic TAD-specific priors and costly to update. Some approaches instead repurpose pretrained general-purpose TFMs for TAD to avoid this burden, but rely on computationally expensive formulations with restrictive anomaly inductive biases. In this work, we introduce TaskBridge, a new framework that efficiently repurposes pretrained general-purpose TFMs for unsupervised TAD by constructing virtual supervised tasks that directly recast anomaly detection as supervised in-context inference of TFMs. The resulting virtual tasks induce predi

---

### [259] Video2STL: Grounding VLM-Generated Temporal Specifications for Robot Learning

**链接**: https://arxiv.org/abs/2609.37519
**作者**: Merve Atasever, Keyan Azbijari, Cagan Bakirci, Bo-Ruei Huang, Tolga Izdas, Zahra Shahrooei 等 (9 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video-based policy learning is particularly promising, as it illustrates target behaviors without requiring action annotations or embodiment-matched demonstrations. A central challenge is deciding what information should be transferred from the video to the robot. Existing approaches commonly convert visual observations into scalar similarity or value signals, or ask foundation models to directly generate reward code. These approaches can make the temporal structure of a task difficult to inspect, ground, and reuse. We present Video2STL, a framework that converts observation-only videos into parametric Signal Temporal Logic (STL) specifications and uses the resulting formal representation for robot learning. A vision-language model extracts an embodiment-independent semantic event trace and constructs a bank of symbolic temporal specifications. The model determines the task structure, while numerical predicate thresholds and temporal bounds are grounded from successful robot trajectori

---

### [260] Boosting Metric Depth Completion via Training-Free Adaptive Response Geometry

**链接**: https://arxiv.org/abs/2609.36168
**作者**: Mia Zhang, Jizong Peng
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depth completion aims to recover dense metric depth from sparse sensor measurements, increasingly leveraging visual foundation models as geometric priors. However, aligning these priors to true metric scale typically relies on rigid affine assumptions in predefined coordinate systems, leaving systematic calibration errors. Linearity in depth calibration depends on the response coordinate. We introduce adaptive response geometry, which makes the fixed choice of depth, log depth, or disparity an image-level unknown. A continuous response family unifies these coordinates and defines an explicit depth-dependent gain. We derive the response-gradient relation and estimate the response parameters in metric space. Hard-Dirichlet residual reconstruction completes the calibrated prior. Under deliberately incomplete metric observations, the training-free pipeline achieves macro AbsRel 0.0301 and macro NMed 14.04{\deg}, improving both aggregate measures over PriorDA, LDCM, and Any2Full. Linearity 

---

### [261] Volatility-Clustering Adaptation for Financial Time Series

**链接**: https://arxiv.org/abs/2609.37715
**作者**: Manh Nguyen, Minh Hoang Nguyen, Huu Hiep Nguyen, Van Dai Do, Hung Le
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models are increasingly adapted to new domains through fine-tuning on target data, under the implicit assumption that more target data yields better forecasts. We show that this assumption can fail in financial forecasting, where individual price changes are difficult to predict, but large moves tend to cluster, creating alternating calm and turbulent periods. Using financial foundation models trained on price bars of open, high, low, close, and volume, we argue that adapting to financial domains requires training signals beyond next-token prediction. We introduce Volatility-Clustering Adaptation (VCA), which augments next-token cross-entropy with a differentiable penalty on the autocorrelation of squared returns, the standard statistical signature of volatility clustering. This additional objective provides a multi-step training signal by matching the resulting dependence structure of autoregressive rollouts to those of the realized future. Across three asset se

---

### [262] GenomeOcean Anywhere: Private WebGPU Inference for Genome MoEs

**链接**: https://arxiv.org/abs/2609.35882
**作者**: Guang Yang, Fengchen Liu
**来源**: cs.CR cs.LG q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Genome foundation models are most useful where sequences are generated, yet the largest models need datacenter accelerators and a place to send private DNA. We ask whether a 15-billion-parameter genome mixture-of-experts (MoE) model can instead run on volunteers' web browsers, with the experts spread across many untrusted devices, without changing its predictions and without revealing the sequence to any single device. We build a system in which a trusted coordinator runs attention and routing while browser workers run every expert feed-forward network through hand-written WebGPU kernels, and we protect the expert inputs with real-valued Lagrange coded computing: each worker receives only a Gaussian-padded share, computes the expert's linear maps, and the coordinator decodes from any two of three workers. On GenomeOcean-MoE (8 experts, top-2 routing, 24 layers), the browser path matches native llama.cpp at every quantization level, the distributed path stays at the BF16 numerical noise

---

### [263] Med-RADIO: Reducing All Medical Domains Into One via Multi-Teacher Distillation

**链接**: https://arxiv.org/abs/2609.37682
**作者**: Chu Zhang, Haoyu Jiang, Hongyuan Zhang, Hongbin Liu and Dong Yi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid expansion of large-scale medical datasets and computational resources has driven significant progress in medical foundation models. Given the inherent heterogeneity of medical imaging modalities, current research mainly follows two paths: specialized models optimized for specific modalities, and generalist models designed to handle multiple modalities. However, medical generalist models suffer from both insufficient training data scale relative to natural image generalists and inadequate domain-specific depth relative to medical specialists. Empirically, generalist models establish a cross-modality performance baseline, while specialists define the performance ceiling within their respective domains. To elevate this baseline toward these ceilings, we propose Med-RADIO, a medical multi-teacher distillation framework that Reduces All Domains Into One by compressing complementary expertise from multiple domain-specific teachers into a unified medical vision foundation model. Our

---

### [264] SemPSG: A Semantic Channel-Aware Foundation Model for Polysomnography Analysis

**链接**: https://arxiv.org/abs/2609.36619
**作者**: Junyu Chen, Chenxi Liu, Shiqin Tang, Hao Miao, Wanyun Ling, Ziyue Li 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Polysomnography (PSG) integrates multiple physiological signals to provide a comprehensive characterization of human sleep, yet its heterogeneous channel configurations across centers pose substantial challenges for transferable representation learning. Existing foundation models mainly focus on physiological modeling or temporal learning, while channel identity is often treated as a fixed structural index, overlooking the physiological semantics encoded by signal modality and reference configuration. To this end, we propose SemPSG, a Semantic channel-aware foundation model for heterogeneous PSG analysis. SemPSG explicitly represents the physiological semantics of channel identity and incorporates them into both signal representation learning and channel aggregation, enabling flexible modeling across diverse data configurations. Specifically, a semantic-conditioned time-series encoder captures signal-specific temporal dynamics and cross-signal interactions, while a multi-view image enc

---

### [265] Skill-Space Shooting for Autonomous Robot Policy Improvement

**链接**: https://arxiv.org/abs/2609.38178
**作者**: Zihang Rui, Renhao Wang, Haoxu Huang, Yang Gao
**来源**: cs.RO cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robots deployed in the physical world must be able to improve beyond their initial training as they encounter new situations and failures. For this improvement to scale across tasks, it must make effective use of experience without requiring human demonstration of each correction. Recent agentic systems offer a way to reduce this reliance on human effort by using foundation models to autonomously compose learned behaviors to complete tasks. Yet completing tasks this way does not itself teach a task policy to overcome its own failures; that requires turning these behaviors into learnable corrections for the policy. Our insight is that many such corrections are familiar short behaviors, or skills: they recur across tasks and describe actions that foundation models can reason about from a scene. We introduce skill-space shooting, which uses foundation model guidance to explore corrections through these reusable skills and turn successful trials into policy improvement. Real-world experime

---

### [266] LoopICL: Looping a single transformer block to solve tabular tasks

**链接**: https://arxiv.org/abs/2609.36108
**作者**: Amir Rezaei Balef and Katharina Eggensperger
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models using in-context learning have recently surpassed gradient-boosted trees on predictive tabular tasks. However, recent mechanistic insights suggest that parameters in these models are largely redundant. We introduce LoopICL, a looped transformer whose core design decouples parameter count from computational depth. LoopICL consists of a single block, processing data through two coupled streams: a cell stream capturing per-cell feature representations and a row stream capturing in-context example representations, jointly refined through within-column and cross-column attention. During pre-training, we vary loop counts, allowing the block to be unrolled for a varying number of iterations at test-time and use a learned exit-gate to automatically exit. In its standard setting, LoopICL performs competitively with TabICLv2 on TabArena and TALENT at the same computational cost (FLOPs), while using nearly 90% fewer parameters. Furthermore, its recurrent design enables u

---

### [267] Beyond Discrimination: Calibrated Geoprior Fusion for Bioacoustic Monitoring

**链接**: https://arxiv.org/abs/2609.35863
**作者**: Neha Sajja, Bart van Merri\"{e}nboer, Burcu Karagol Ayan, Tom Denton
**来源**: eess.AS cs.LG cs.SD
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern bioacoustic foundation models like Perch and BirdNET can identify species with high discriminative accuracy, yet their confidence scores are often uncalibrated and difficult to interpret as probabilities of real-world occurrence. This limits their use for ecological inference beyond threshold-based detection. We leverage a global annotated acoustic dataset (WABAD) to produce calibration priors for an acoustic model, optionally incorporating species-level information. We introduce new methods of fusing the acoustic predictions with geopriors, which empirically improves calibration while preserving discrimination. Together, these results suggest a path to simpler and more reliable acoustic monitoring for broad biodiversity.

---

### [268] HyperSAM: A Promptable Foundation Model for Hyperspectral Remote Sensing

**链接**: https://arxiv.org/abs/2609.37340
**作者**: Li Pang, Xinqiao Wu, Jing Yao, Pedram Ghamisi, Jun Zhou, Zhengchao Chen 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hyperspectral remote sensing provides dense spectral measurements that are indispensable for material-level Earth observation, yet the construction of a general-purpose hyperspectral foundation model remains difficult. Two bottlenecks are especially limiting. First, large hyperspectral corpora rarely provide high spatial resolution together with reliable dense annotations. Second, many hyperspectral models are still trained almost from scratch, so the geometric and interactive priors learned by modern vision foundation models are not fully reused. To alleviate these issues, we \highlight{present} \textbf{HyperSAM}, a promptable hyperspectral foundation model that couples a data-centric hyperspectral synthesis pipeline with a spectral adaptation architecture based on Segment Anything Model 3 (SAM3). On the data side, HyperSAM synthesizes full-spectrum hyperspectral cubes from high-resolution SpaceNet multispectral imagery through a physics-informed abundance-transfer generator, while SA

---

### [269] The Universal Classifier for Graph Learning

**链接**: https://arxiv.org/abs/2609.36302
**作者**: Ben Finkelshtein, Andr\'{e} Linhares, Petar Veli\v{c}kovi\'{c}, Bryan Perozzi, Mikhail Galkin
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While foundation models have revolutionized natural language processing and computer vision by leveraging universal vocabularies, Graph Machine Learning (GML) remains fractured due to the absence of a unified feature and structural representation across diverse domains. Existing works claiming to be Graph Foundation Models (GFMs) are typically restricted to node-level predictions or require fixed feature dimensions, failing to provide a truly task-agnostic backbone for the full spectrum of graph learning applications. In this paper, we introduce the Universal Classifier (UC), which supports arbitrary feature and class cardinalities, unifying node-, edge-, and graph-level objectives under a single similarity-based classification objective. The UC reformulates all node-, edge-, and graph-level prediction tasks as maximizing similarity in the latent space: by lifting heterogeneous features and labels into 3D latent tensors, the model learns transferable features independent of specific in

---

### [270] CipherGenome: Homomorphic Inference for Genomic Mixture-of-Experts

**链接**: https://arxiv.org/abs/2609.35883
**作者**: Guang Yang, Fengchen Liu
**来源**: cs.CR cs.LG q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Genome foundation models are growing into sparse mixture-of-experts (MoE) networks whose expert weights no longer fit on the machines that hold the sequences, yet sending a private genome to rented accelerators exposes it: we show that a single server hosting one expert recovers the input nucleotides with 99.8% top-1 accuracy. We present CipherGenome, a protocol that keeps the embedding, attention and router of a 15.1B-parameter MoE genome model on a trusted thin client and outsources every expert projection, 95.8% of the parameters, to untrusted and possibly colluding GPU servers under module-LWE encryption. The design exploits three structural facts: expert layers are linear between two SwiGLU gates, expert weights are public, and GPU integer tensor cores can evaluate a ciphertext-weight product exactly modulo $2^{48}$ in a single GEMM. The client evaluates the nonlinearity exactly and re-encrypts with fresh secrets, so no polynomial approximation or bootstrapping is ever needed. On 

---

### [271] HERO: Histology Encoder for Robust Representation in Oncology

**链接**: https://arxiv.org/abs/2609.35943
**作者**: Zhi Li (1), Eghbal Amidi (1), Yating Cheng (1), Tyson Dawson (1), Gorkem Can Ates (1), Shuzhen Kuang (1) 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models trained on large pathology image corpora now provide strong, transferable representations for computational pathology. Over the past few years a series of such models has been released, each trained on more slides than the last; on standard classification and segmentation benchmarks, the leading models are now separated by small margins. In clinical use, however, the foundation model is applied to images from hospitals, scanners, and staining protocols outside its training data. Encoders generally embed these acquisition factors alongside biological information, which may introduce downstream errors and hinder safe clinical adoption. A pathology foundation model should therefore be robust to acquisition shift without giving up representation quality, yet robustness is seldom the axis along which models are compared. In this report, we introduce HERO (Histology Encoder for Robust Representation in Oncology), a ViT-G/14 pathology foundation model trained with the DINO a

---

### [272] Language as the Interface: Foundation-Model Contrastive Learning Links Transcriptomes and Electrophysiology

**链接**: https://arxiv.org/abs/2609.37024
**作者**: Junbo Shen, Jinying Gao, Bo Lei
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Integrating transcriptomic and electrophysiological data is essential for building multimodal foundation models for neuroscience. Patch-seq provides paired measurements of gene expression and intrinsic electrophysiology from the same neuron, establishing a basis for training cross-modal models. Here we introduce LangPatch, a foundation-model-based contrastive learning framework that uses paired Patch-seq data to align pretrained GenePT representations with electrophysiological phenotypes through a language-based interface. Gene descriptions and verbalized electrophysiological profiles are embedded by the same frozen text encoder. A context adapter and projection modules connect the modalities through paired contrastive learning. Across mouse visual, mouse motor, and human cortical cohorts, LangPatch achieves the highest mean transcriptome-to-electrophysiology prediction correlation among the evaluated foundation-model and representation-learning methods. It also improves held-out cross

---

### [273] FM-ReID: Selective Competitive Token Routing for Object Re-Identification

**链接**: https://arxiv.org/abs/2609.36560
**作者**: Zhiqi Li, Xiaowei Zhou, Zeyuan Sun, Feng Gao, Junyu Dong
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Object re-identification (ReID) faces a recurring challenge: different identities can share highly similar global appearances, while the cues that distinguish them are localized, heterogeneous, and visible only under particular viewpoints. This challenge arises in animal ReID through markings, contours, and scars, in person ReID through subtle clothing and accessory cues, and in vehicle ReID through localized appearance details. Although visual foundation models encode such information in dense tokens, a single holistic descriptor can obscure discriminative local signals. We propose FM-ReID, an end-to-end framework that formulates local representation learning as selective competitive token routing. Its Competitive Fine-grained Mining module uses multiple mining queries and a residual query to compete for dense DINOv3 tokens. Above-prior selection retains tokens preferentially allocated to each mining query, while the residual slot receives tokens excluded from the retrieval descriptor

---

### [274] GraphVQ: Structure-Aware Autoregressive Decoding over Context-Quantized Graph Tokens

**链接**: https://arxiv.org/abs/2609.37604
**作者**: Yuxiang Yao, Zijun Zhao
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph foundation models need a discrete token representation, but casting a graph as a generatable token sequence faces a structural obstacle: edges spanning beyond the serialization window cannot be emitted in one pass--so one-pass autoregressive generators systematically under-produce cycles--and a single global condition cannot tell candidate edges apart. GraphVQ removes both obstacles: node contexts--features plus a local edge mask under multi-order breadth-first serialization--are quantized into a shared codebook by a VQ-VAE with BCE-calibrated Bernoulli edge decoding, and a second-stage structure-aware decoder emits the global adjacency conditioned on token-derived pair features, whose necessity over any global-summary condition is formalized in a scoped impossibility result. The tokenizer reconstructs node features at 0.86--0.99 accuracy and decodes local edges at AUROC >= 0.89 (ECE <= 0.007). Under one same-split protocol on four datasets, pair conditioning improves orbit MMD 0

---

### [275] When to Adapt: Multi-Signal Domain Shift Detection for Efficient Training-Free Adaptation in Open-Vocabulary Segmentation

**链接**: https://arxiv.org/abs/2609.37602
**作者**: Michele Antonazzi, Alejandra C. Hernandez, Jos\'e Araujo, Olov Andersson, Patric Jensfelt
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robust and reliable perception is essential for autonomous robots operating in real-world environments, particularly in long-term missions where environmental conditions may change significantly over time. Although recent advances in Visual Foundation Models (VFMs) have improved open-vocabulary semantic segmentation, these models can still suffer from domain shift, which can significantly degrade performance if they are not adapted to the current environment. Training-free domain adaptation is a relevant paradigm for adaptation, consisting of adjusting the model online using lightweight adapters. Recent approaches apply this on a per-frame basis, which is impractical for deployments on resource-constrained robotic hardware. To tackle this, we propose a multi-signal domain shift detection method for training-free continual test-time adaptation (TF-CTTA) in open-vocabulary segmentation. Our method leverages temporal coherence across consecutive frames by monitoring and combining compleme

---
