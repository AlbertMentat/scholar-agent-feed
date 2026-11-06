# 📑 论文索引 - 2026-11-07

共 113 篇论文

---

### [1] LLM-Assisted Label Noise Correction for EEG-Based Sleep Stage Classification

**链接**: https://arxiv.org/abs/2611.08311
**作者**: Elmira Salari, Shruti Kshirsagar
**来源**: cs.CL
**匹配关键词**: EEG, LLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic sleep stage classification from electroencephalography (EEG) signals is a critical task in clinical sleep medicine. While deep learning models have shown promising results in this domain, their performance is fundamentally constrained by the quality of training labels, which human experts manually annotate and that are subject to inter-rater disagreement and systematic labeling errors. In this paper, we propose a novel LLM-assisted label-noise filtering pipeline that operates exclusively during training to identify and remove unreliable sleep-stage annotations before retraining the classifier. Specifically, TinySleepNet is first trained on the original dataset to extract per-epoch SoftMax confidence scores, then low-confidence epochs are submitted to LLaMA 3.1 along with their EEG spectral features and surrounding sequence context. The LLM evaluates each epoch against AASM sleep-scoring guidelines and assigns a verdict of RELIABLE or SUSPICIOUS. Suspicious epochs are removed 

---

### [2] Thalamus-Reasoning: A Multimodal Large Language Model for Multi-Sample Omics Reasoning

**链接**: https://arxiv.org/abs/2605.06728
**作者**: Maciej Sypetkowski, {\L}ukasz Smoli\'nski, Remigiusz Kinas, Joanna Krawczyk, Bart{\l}omiej Hofman, Aleksandra Mo\.zwi{\l}{\l}o 等 (9 人)
**来源**: q-bio.GN cs.AI q-bio.CB
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [3] FlashOffloading: Low-Latency KV Cache Offloading for Long-Context LLM Serving

**链接**: https://arxiv.org/abs/2611.07542
**作者**: Xuan Wang, Zhuanhao Wu, Tingzhu Fang, Xushi Li, Sicheng Zhang, Zhenyu Yang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In large language model (LLM) serving systems, the key-value (KV) cache grows linearly with sequence length and concurrency, so long-context inference easily hits the high-bandwidth memory (HBM) capacity wall and results in low concurrency. Offloading the KV cache to host dynamic random-access memory (DRAM) frees HBM space and raises concurrency, but the additional cache management and host-to-device (H2D) load overhead inflates inference latency, higher concurrency fails to translate into effective throughput. We present FlashOffloading, a host-DRAM-centric inference architecture that fully offloads the KV cache in both the prefill and decode phases. FlashOffloading builds rolling HBM cache for prefill, a hot cache for decode, a reverse sparse index with zero extra miss-lookup overhead, and a compute--load overlapped kernel, optimizing KV offloading latency across the entire pipeline and delivering throughput gains under a time-per-output-token (TPOT) service-level objective (SLO). In

---

### [4] StrataFlux: Memory-Hierarchy-Native Low-Bit LLM Inference

**链接**: https://arxiv.org/abs/2611.08363
**作者**: Jake Hyun, Ziyu Zhao, Jae-sun Seo, Mohamed S. Abdelfattah
**来源**: cs.LG cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization reduces the memory and bandwidth demands of large language model (LLM) inference but can degrade accuracy; offloading higher-precision data can instead stall generation. We introduce StrataFlux, a framework that challenges this tradeoff by recovering accuracy lost to low-bit weight and key-value (KV) cache quantization while retaining quantization's memory and speed advantages. StrataFlux co-designs refinement representation, selection, and delivery to make host RAM and solid-state drives useful sources of additional precision. Its selective precision streaming reduces transfer volume, overlaps delivery with computation, and reuses fetched precision across decoding steps so generation need not wait for every transfer. We evaluate 2-4-bit weights and 2-3-bit KV-cache on dedicated GPUs and unified-memory platforms. For 2-bit Llama-3.1-8B-Instruct weights, StrataFlux reduces WikiText-2 perplexity from 9.46 to 8.40 while maintaining 95.4% of the quantized base's throughput on 

---

### [5] Spatiotemporal Dynamics-Aware Industrial Anomaly Detection and Reasoning

**链接**: https://arxiv.org/abs/2611.08080
**作者**: S-Wei Chen, Siangyu Yang, Yi-Chen Jan, Chun-Yi Lee, Shao-Yuan Lo
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial Anomaly Detection (IAD) is a long-established problem that aims to detect defects in industrial products during manufacturing for quality control. Most existing studies focus on static visual patterns as the basis for detection. However, in real manufacturing environments, many anomalies are dynamics-based, such as irregular movements that cannot be perceived from static cues alone. We observe that even recent Multimodal Large Language Model (MLLM)-based approaches fall short in identifying such dynamic anomalies due to limited temporal modeling capability. To address this, we introduce MUSTARD: MUltimodal SpatioTemporal Anomaly Reasoning and Detection, a framework that equips MLLMs with fine-grained spatiotemporal dynamics awareness for detecting and reasoning about dynamics-based defects. MUSTARD introduces optical-flow-guided keyframe selection and augmented modalities to capture critical motion irregularities through local motion patterns and global dynamic evolution. It

---

### [6] TileQuant: Tile as the Precision-Allocation Unit for LLM Mixed-Precision Post-Training Quantization

**链接**: https://arxiv.org/abs/2611.07217
**作者**: Hanzhi Zhang, Qiao Zhang, Qinglei Cao, Heng Fan, Yan Huang, Kewei Sha 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) reduces large language model (LLM) deployment costs, but preserving quality requires accounting for uneven weight sensitivity. Uniform PTQ uses one weight bit-width, importance-aware PTQ adjusts scales or reconstructs weights within that width, and column-wise mixed precision retains selected columns at higher precision. However, sensitivity varies within columns, so whole-column retention also protects less sensitive weights, while runtime outlier detection adds decoding overhead. We therefore introduce TileQuant, a training-free framework that assigns precision to hardware-aligned 2D weight tiles. Offline calibration provides input-activation-aware scoring from forward statistics for lower calibration cost and gradient-informed scoring from loss sensitivity for stronger quality preservation. Within each projection's retention budget, the highest-scoring tiles remain at 16-bit and the rest use 8-bit. The resulting map guides reconstruction into compact

---

### [7] SKIM: Pruning Large Language Model Agents via Selective Knowledge Informed Masking

**链接**: https://arxiv.org/abs/2611.07558
**作者**: Moonseok Choi, Jongwon Jeong, Minki Kang, Giung Nam, Juho Lee
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents are increasingly deployed under structured generation, where grammar constraints enforce output format at inference time. Whereas existing compression methods target unconstrained generation, we first identify a fundamental mismatch: under structured generation, grammar constraints reduce the model's output distribution to valid tokens, and the logits matter most at the small set of positions that decide the agent's action. Motivated by this finding, we propose SKIM (Selective Knowledge-Informed Masking), the first pruning and distillation framework for LLM agents under structured generation, with both stages guided by token role. SKIM partitions token positions into context, decision, and format categories, and this partition drives two complementary axes: (1) category-aware pruning saliency scores that preserve parameters most relevant for decision positions; and (2) an on-policy distillation objective that aligns student and teacher on valid tokens,

---

### [8] The Power of Meta Access in the Software of the Future --- Demonstrated on LLM Chat UIs and Chat AI

**链接**: https://arxiv.org/abs/2611.08428
**作者**: Julian Kunkel, Ali Doosthosseini
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chat remains the default surface for many large language model (LLM) tasks, even as agentic tools such as OpenCode excel at coding and automation. Yet the model sees the current dialogue but not the workspace around it. We explore meta access---giving the assistant a structured, permissioned view of the interface itself and propose a ladder of levels: feature tutoring; metadata, settings, and preference access; retrieval over summaries and messages, confirmed mutation, and full orchestration. Meta access can turn a chat client from many screens into one entry point for finding, navigating, organising, and operating it, while raising risks around grounding, privacy, prompt injection, and trust. General-purpose agentic harnesses are runtimes; because they can change their own settings, meta access becomes reflexive and needs a separate control-plane boundary. We ground this in the Meta Chat prototype of the Chat AI client. It builds bounded context from, e.g., summaries, settings, and re

---

### [9] The Judge is Part of the Experiment: Auditing Peer Context Sensitivity in LLM-Based Evaluation

**链接**: https://arxiv.org/abs/2608.04463
**作者**: Alicia Guerra, Jiaming Qu, Yibo Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [10] Taurus: LLM-in-the-Loop CT Annotation Matches Coding Agents at Half the Cost

**链接**: https://arxiv.org/abs/2611.00247
**作者**: Bing Hu, Rishabh Sharma
**来源**: cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] PromptOps: Iterative Prompt Optimization for LLM-as-a-Judge Systems

**链接**: https://arxiv.org/abs/2611.07123
**作者**: Sven Kleinkop, Tam\'as Janusko, Ricardo Bochnia, Gunnar Hempel, Steffen Tomschke, J\"urgen Anke 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as automated judges for evaluating the behavior of chatbots and other AI systems. In deployment, however, their agreement with the intended human evaluation policy may degrade as user interactions and score distributions change. Existing automatic prompt optimization methods are primarily studied as one-shot procedures on static development sets and therefore provide limited guidance for maintaining LLM judges over time. We frame this problem as judge drift and introduce PromptOps, a closedloop framework for monitoring and iteratively recalibrating LLM-as-a-Judge (LLMaaJ) systems. PromptOps separates four operational decisions: when to optimize, which optimization procedure to apply, which feedback records to use, and how to update the judge prompt. We instantiate the framework with five prompt optimization methods: GEPA, SIMBA, Rubric Synthesis, and exemplar selection using either simulated annealing or a Tree-structured Parzen Estima

---

### [12] DictLLM: Post-training Compression of Large Language Model with Dictionary Kernels

**链接**: https://arxiv.org/abs/2611.08082
**作者**: Jinho Park, Se Young Chun, Mingoo Seok
**来源**: cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient deployment of large language models (LLMs) on mobile devices requires balancing performance with compute and memory constraints. Post-training compression is an effective approach to managing this trade-off, while requiring much less computation than in-training counterparts. We propose DictLLM, a dictionary-based compression scheme in which weight matrices within grouped layers are decomposed into a shared dictionary and layer-specific sparse coefficients, directly obtained from a pre-trained model without further training. Specifically, we cast DictLLM as a four-step post-training optimization. First, we obtain shared dictionaries via singular value decomposition (SVD) of input-scaled weight matrices, amortizing rank across grouped layers; second, we sparsify the layer-specific coefficients to the target compression ratio using a dictionary-aware Hessian; and third, we refine the dictionaries given the resulting sparse coefficients. Finally, we aggressively quantize both co

---

### [13] EvoDR: Evolving Dispatching Rules via Large Language Model for Dynamic Flexible Assembly Flow Shop Scheduling

**链接**: https://arxiv.org/abs/2601.15738
**作者**: Junhao Qiu, Haoyang Zhuang, Fei Liu, Jianjun Liu, Qingfu Zhang
**来源**: cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] ThermoLLM: LLM-Based Multi-Zone HVAC Control with a Spatiotemporal Context

**链接**: https://arxiv.org/abs/2606.22911
**作者**: Kirtan Bhatt, Xiachong Lin, Matthew Amos, Flora D. Salim, Wen Hu
**来源**: cs.AI cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] Harness Updating Is Not Harness Benefit: Disentangling Evolution Capabilities in Self-Evolving LLM Agents

**链接**: https://arxiv.org/abs/2605.30621
**作者**: Minhua Lin, Juncheng Wu, Zijun Wang, Zhan Shi, Yisi Sang, Bing He 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] TriAttention: Unified Sparse Mixed-Precision Attention for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2611.07256
**作者**: Hanzhi Zhang, Qiao Zhang, Qinglei Cao, Heng Fan, Yan Huang, Kewei Sha 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparsity and quantization reduce the cost of attention by skipping interactions and lowering the precision of those retained. However, useful interactions differ in their precision requirements: some tolerate low-precision scores while remaining sensitive to removal. We therefore introduce TriAttention, which assigns query-key (QK) tiles to skipping, 4-bit, or 8-bit computation, using 4-bit to retain quantization-tolerant interactions at lower cost. To represent compactly, we encode each head's computation regions with two diagonal-distance boundaries, keeping policy storage independent of context length. Offline calibration then evaluates candidate boundary pairs using normalized projected-output errors and complete-tile execution costs. Using these measurements, a model-wide allocator selects each head's boundaries to minimize calibration error under a shared computation budget. During prefill, the selected boundaries generate precision-grouped traversals for a fused kernel that skip

---

### [17] SteelAgent: LLM-Orchestrated, Physics-Informed Steel Property Prediction with Audited Generalization and Calibrated Uncertainty

**链接**: https://arxiv.org/abs/2611.06953
**作者**: Aleksandr Volkov, Roman Sultimov, Mikhail Kuzin, Yury Maximov
**来源**: cs.LG cond-mat.mtrl-sci
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Steel property models can perform well on random test splits even when they extrapolate poorly to unfamiliar alloys. SteelAgent couples metallurgical descriptors and machine-learning models with a language-model interface for property prediction, uncertainty reporting and inverse design. We examine how the choice of held-out unit changes the conclusions drawn from SteelBench tensile-strength evaluations. For gradient boosting, pooled out-of-fold $R^2$ fell from 0.859 on a random split to 0.113 when steel families were held out. Empirical coverage of nominal 90% prediction intervals ranged from 91.0% under random splitting to 37.6% on held-out sources. The effect of physics-derived features depended on the evaluation. They increased gradient-boosting $R^2$ by 0.2534 in a 17-family holdout analysis and decreased it by 0.358 in a separate four-grade laboratory analysis. We report group-level errors and a synthetic regression experiment illustrating how calibration can deteriorate on held-

---

### [18] What the Middleman Delivers: Answer Behavior, Tool Permissions, and Billed Usage in LLM API Relays

**链接**: https://arxiv.org/abs/2611.07650
**作者**: Xiaodong Wu, Zhimin Zhao, Qi Li, Chaklam Cheong, Xiangman Li, Jianbing Ni
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Third-party application programming interface (API) relays offer access to large language models (LLMs), often at lower prices. Users depend on these services for model quality, instruction compliance, and accurate billing. However, existing studies leave unclear whether relays meet these expectations together. We test 20 relays offering GPT-6 Astra and Claude Opus 5. First, we compare answers to knowledge questions with batch-matched official responses. In our first-round sample, the analysis flags 7/10 low-price and 2/10 same- or higher-price relays for behavioral differences. On retesting 35 pairs, seven gain or lose a flag under the original rules, and six under matched correction families. Because answer comparisons cannot reveal every delivery problem, we examine returned content and tool permissions. No injection is confirmed in 3,332 screened responses to a fixed, non-adversarial code and setup workload, yet four relays return tool calls despite instructions disabling them in t

---

### [19] ACSeL: Adaptive Configuration Search for Hardware-Constrained LLM Inference

**链接**: https://arxiv.org/abs/2611.07570
**作者**: Bokun Wang and Hung-Yueh Chiang and Diana Marculescu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving large language models (LLMs) under tight memory and latency service-level objectives (SLOs), including on edge devices, requires jointly selecting the model size, batch size, quantization algorithm, and mixed-precision quantization recipes. Exhaustive search over this combinatorially large space is infeasible. Unlike data-center serving, which often prioritizes throughput or generation speed, resource-constrained deployments typically set memory and latency budgets as constraints and then seek the configuration with the highest generation quality among feasible ones. To this end, we propose ACSeL, a framework that identifies configurations predicted to satisfy deployment constraints while achieving high predicted generation quality. To enable efficient quality estimation, we use Relative Model Quality Degradation (RMQD), a proxy based on the divergence between the candidate and reference models' next-token distributions over a small calibration corpus. Across the evaluated mode

---

### [20] PixelMoE: Scaling Pixel-Space Diffusion with LLM-Style Mixture-of-Experts

**链接**: https://arxiv.org/abs/2610.18857
**作者**: Ruixiao Dong, Jianmin Bao, Bozhi Luan, Zijie Meng, Xin Tao, Pengfei Wan 等 (9 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Do Recommenders Need to Think in Words? Latent Reasoning for Efficient LLM-Based Recommendation

**链接**: https://arxiv.org/abs/2611.07866
**作者**: Hongyang Su, Beibei Kong, Lei Cheng, Chengxiang Zhuo, Zang Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based recommender systems increasingly generate chain-of-thought (CoT) text before each item prediction to activate the LLM's reasoning capacity, costing tens to hundreds of extra tokens per recommendation at inference. We ask whether inference-time reasoning artifacts (textual or latent) can be replaced by training-time supervision alone, without loss of accuracy. We propose LatentRec, a framework for LLM-based generative recommendation that replaces inference-time reasoning artifacts with training-time per-step head supervision. LatentRec has three components. A 2.5M-parameter Continuous Thought Module iterates K latent reasoning steps over the LLM's hidden state during training. Soft Token Selection bridges the ~14x norm gap between hidden states and input embeddings. A Per-step Reasoning Loss (PRL) supervises every intermediate state through the LLM's prediction head against the first token of the target Semantic ID. The trained LLM retains this accuracy without the module at i

---

### [22] Adapting LLM Judges to Observed Human Annotation Policy through Soft Prompt Tuning

**链接**: https://arxiv.org/abs/2611.07126
**作者**: Tam\'as Janusko, Sven Kleinkop, Ricardo Bochnia, Gunnar Hempel, Steffen Tomschke, J\"urgen Anke 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly employed as automated judges for evaluating chatbot responses. While proprietary models can achieve high agreement with human annotators, they remain costly and difficult to deploy in practical settings. Lightweight open-source LLM judges provide an attractive alternative but typically exhibit lower agreement with human ratings. In this paper, we investigate whether soft prompt tuning can align open-source LLM judges more closely with human annotation policy. We train soft prompts on the FairBotBench benchmark and evaluate the adapted judges across the dimensions of bias, toxicity, and personalization. Our findings demonstrate that hybrid soft-prompt tuning, which combines textual prompts with learned continuous prompt embeddings, consistently improves agreement with human annotations over the corresponding untuned baselines. For Qwen 3.5 9B, the adapted judges surpass both hosted reference judges across all three evaluation dimensions.

---

### [23] MemForm: Benchmarking Memory Formation Poisoning in LLM Agents

**链接**: https://arxiv.org/abs/2610.14431
**作者**: Haowen Pan, Pengyang Shao, Yunshan Ma, Yanzheng Jin, Naixin Zhai, Xiang Wang 等 (7 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] Learning Multi-Agent Orchestration:Higher-Order Interactions in Policy Improvement

**链接**: https://arxiv.org/abs/2611.07495
**作者**: Kaixuan Liu, Guojun Xiong
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learned orchestration has emerged as a promising paradigm for large language model (LLM)-based multi-agent systems, in which a central orchestrator selects agents and controls the information they receive throughout a task. Despite rapid empirical progress, existing methods train the orchestrator by crediting each decision with its own advantage, implicitly assuming that the other decisions in the episode stay fixed. This assumption fails in orchestration, where the contribution of each decision to the final outcome depends on the decisions preceding it, so the gain of a joint update is not the sum of its per-decision effects. To address this challenge, we introduce \textbf{IAPO}, an interaction-aware policy optimization framework that explicitly accounts for interactions among decisions. Specifically, IAPO exactly decomposes the performance difference between two policies into the effects of individual decisions and their interactions, which we prove can account for half of the attain

---

### [25] LeanStream: A Speculate-and-Refine Streaming Framework for Efficient on-Device LLM Inference

**链接**: https://arxiv.org/abs/2609.03079
**作者**: Renyuan Liu, Yuyang Leng, Kaiyan Liu, Yuzhou Zhong, Shaohan Hu, Chun-Fu (Richard) Chen 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Accepted but Wrong: Silent Failures of LLM Code Repairs after API Migrations

**链接**: https://arxiv.org/abs/2611.08269
**作者**: Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> After a runtime or API migration, an LLM-repaired procedure can run cleanly yet return wrong results, and a release check on typical test inputs ships it. We report a preregistered study of 73 tasks covering 60 documented changes in CPython, Node.js and SQLite. Every candidate is executed on the real runtimes against withheld contracts. Over the complete repair space, the all-assertions gate on typical inputs released 0.410 of wrong repairs. One edge input written from the release note cut this to 0.065, and to 0.061 on 15 unseen clusters. Three inputs from a blind GPT-5.6-luna writer that never saw the program reached 0.070. Two further frozen stages enlarged the menu to 1491 fragments and then added 233 hard distractors that match the legacy output on typical inputs. The edge input (0.058) and the frontier-model writer (0.058) passed their preregistered tests. Yet 0.168 and 0.153 of the hard wrong programs still passed. Two local-model writers failed their preregistered tests. Across

---

### [27] When LLM Routers Overpay: The Cost of Strong-Model Preference

**链接**: https://arxiv.org/abs/2602.03478
**作者**: Guannan Lai and Long Chen and Han-Jia Ye
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] CLaRE-ty Amid Chaos: Quantifying Representational Entanglement to Predict Ripple Effects in LLM Editing

**链接**: https://arxiv.org/abs/2603.19297
**作者**: Manit Baser, Alperen Yildiz, Dinil Mon Divakaran, Mohan Gurusamy
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] RM-VLM: From Natural-Language Task Descriptions to Vision-Grounded Reward Machines

**链接**: https://arxiv.org/abs/2611.08308
**作者**: Roko Parac, Christos Ziakas, Leo Ardon, Alessandra Russo
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reward machines (RMs) have been proposed as a reward formulation in reinforcement learning (RL) to capture non-Markovian tasks where credit assignment depends on history. By representing reward functions as automata, RMs expose the task's temporal structure and allow such rewards to be handled within a Markovian framework. However, they assume a labelling function, a proposition-grounding oracle for observations, which must be manually engineered for each environment, limiting their wider applicability. In this work, we address this limitation by proposing RM-VLM, a novel approach in which a large language model (LLM) generates an RM from a natural-language task description, and a vision-language model (VLM) acts as the labelling function, grounding the RM's propositions over image-based observations during RM-guided policy learning. A VLM-based value function estimator is used to assess the agent's progress towards each RM transition and derive a dense reward signal. We evaluate RM-VL

---

### [30] Circe: Training-Free LLM Self-Evaluation via Component Interaction Consistency

**链接**: https://arxiv.org/abs/2611.07948
**作者**: Shuyi Miao, Zheng Li, Xu Xie, Linrui Xu, Fei Shen, Xiaoyu Du 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly deployed in real-world applications, evaluating the correctness of their responses is crucial for reliable use. However, such evaluation is challenging because reference answers are rarely available in practice. Existing reference-free methods mainly rely on output signals, which may assign high scores to incorrect responses and thus do not necessarily reflect correctness. This motivates exploring the model's internal computation for complementary correctness signals. Recent studies exploit internal states, but they mainly analyze hidden-state trajectories across layers, which record only the combined updates of attention and feed-forward networks (FFNs) and overlook how these components interact. We therefore propose Circe, a training-free self-evaluation method that assesses a response using both internal and external signals, without reference answers or repeated sampling. For internal signals, we first introduce component interaction

---

### [31] Rethinking Data Selection: The Importance of Coverage over Difficulty in LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2611.07323
**作者**: Lalchand Pandia, Kanishka Misra and Allyson Ettinger
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Selecting high-quality training data can reduce computation cost for LLM fine-tuning. Prior work on data selection developed a variety of difficulty-based scores, motivated by the intuition that harder examples are more informative. While effective for smaller classification models, we find that such methods often fail to outperform random selection for LLM fine-tuning. Our analysis reveals that random selection performs better because it is more representative of the underlying input space---i.e., has better coverage. To validate the importance of coverage, we implement a simple clustering-based selection method which selects data that is more representative of the underlying input distribution. On a set of diverse single-domain tasks, this method yields performance at or above that of random selection. On the diverse, multi-domain T\"{u}lu 3 mixture, where random sampling no longer guarantees a balanced subset, our method outperforms all methods. Overall, our results indicate that pr

---

### [32] When Verification Is Not Agreement: Cross-Agent LLM-to-Dafny Formalization

**链接**: https://arxiv.org/abs/2611.07073
**作者**: Priyanath Maji
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A verified Dafny postcondition certifies that a formula holds, but it does not guarantee that the result was reached through genuine independent reasoning. We introduce a cross-agent formalization protocol where a Specifier model translates clinical trial criteria into a Dafny predicate, and an Implementer model writes an operational method checked against it. A same-model control establishes that even with no capability gap, independent re-extraction from identical text agrees only 59.3% of the time. Evaluating four model configurations on 96 clinical trial documents, we find that agreement is highly sensitive to how model capability is allocated across the two roles: the GPT-4.1-nano/GPT-4.1-mini configuration achieves 53.0% agreement when the stronger model is the Implementer, but only 14.3% when the roles are reversed. The strongest tested configuration, GPT-5.6-luna/GPT-5.4-mini, improves agreement to 34.4% but remains below the same-model baseline and is dominated by direct contr

---

### [33] Teach the Way It Thinks: Guiding LLM Post-training Data Engineering with Sparse Autoencoders

**链接**: https://arxiv.org/abs/2605.27354
**作者**: Yi Jing, Zao Dai, Jinwu Hu, Zijun Yao, Lei Hou, Juanzi Li 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Stochastic Dynamics of Generative AI: From Autoregressive Models to Interacting LLM Networks and Neural SDEs

**链接**: https://arxiv.org/abs/2611.07065
**作者**: Vikram Krishnamurthy and Yiming Zhang and Luke Snow
**来源**: cs.LG cs.SY eess.SP eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper develops a stochastic dynamical-systems perspective on three classes of generative AI models. First, we formulate large language models (LLMs) as high-dimensional nonlinear autoregressive models with attention-based dependencies. This formulation connects pretraining by conditional maximum likelihood to sequential token generation and provides a probabilistic interpretation of LLM operation. Second, we consider networks of interacting LLMs and characterize their collective behavior through mean-field ordinary differential equations. These dynamics provide a framework for understanding emergent preferential attachment and persistent structural biases, including type-dependent glass-ceiling effects. Third, we consider neural stochastic differential equations (SDEs) as continuous-time generative models for stochastic trajectories, including those observed at irregular time intervals. We discuss their training with particular emphasis on Wiener-space cubature methods based on ro

---

### [35] Analysis of LLM Vulnerability to GPU Soft Errors: An Instruction-Level Fault Injection Study

**链接**: https://arxiv.org/abs/2601.19912
**作者**: Duo Chai, Zizhen Liu, Shuhuai Wang, Songwei Pei, Cheng Liu, Huawei Li and Shangguang Wang
**来源**: cs.AR cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Encoding and Propagation of Grammatical Number in Large Language Models

**链接**: https://arxiv.org/abs/2611.07283
**作者**: Jacob Solinsky (1), Serguei Pakhomov (1) ((1) University of Minnesota)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) have become an increasingly popular means of translating Large Language Model (LLM) hidden state vectors into a human-comprehensible list of features or symbols. As such, SAEs may provide insight into an LLM's knowledge representation and internal ``mental'' grammar - topics of pragmatic interest for mechanistic interpretation of AI behavior and of theoretical interest for the study of in silico representations of human language. Language models with fewer than 100M parameters, trained on small corpora, nonetheless exhibit strong grammatical competence and discourse coherence, despite producing content of limited reliability. We use SAEs that we trained on one such model (Pythia-70M) to conduct an in-depth examination of how a single grammatical phenomenon, number agreement, is represented and processed in an LLM. We demonstrate the mechanism and the methodology by which SAEs can be used to find and propagate ``plural noun'', ``plural matrix subject'', and ``

---

### [37] EcoGEO: Trajectory-Aware Evidence Ecosystems for Web-Enabled LLM Search Agents

**链接**: https://arxiv.org/abs/2605.12887
**作者**: Hengwei Ye, Jiasheng Mao, Zhenhan Guan, Zheng Tian
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] MEvince: Knowledge-Constrained LLM Reasoning for Technique Identification from Malware Reports

**链接**: https://arxiv.org/abs/2611.07486
**作者**: Hongyu She, Yiling He, Mengda Xie, Yiping Liu, Xingzhi Qian, Zhan Qin 等 (7 人)
**来源**: cs.CR cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mapping behavioral intelligence in malware analysis reports to ATT&CK techniques supports threat analysis and defense, but reliable identification remains challenging. Supporting evidence is often scattered across long, heterogeneous reports, while closely related techniques share behavioral cues and differ only in subtle but decisive details. While large language models (LLMs) can use external knowledge to interpret reports, they may assign techniques based on plausible associations rather than sufficient evidence. We present MEvince, a knowledge-constrained LLM reasoning framework for report-level malware technique identification. Its core is a shared behavioral representation connecting report observations to technique definitions. This representation is built through agentic mining of technique documentation and supports two online stages: 1) primitive-guided extraction uses behavioral primitives to structure LLM-extracted observations, link them to source passages, and group dispe

---

### [39] More Agents, More Reliable? System-Level Reliability of Multi-Agent LLMs under Operational-Profile Uncertainty

**链接**: https://arxiv.org/abs/2611.07140
**作者**: Burkay Tun\c{c}t\"urk, Koorosh Aslansefat, Yiannis Papadopoulos, Bao Nguyen
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Teams increasingly build software from cooperating large language model (LLM) agents, often assuming more agents mean more reliability. Yet the usual evidence, average benchmark accuracy, ignores the input mix a deployed system meets and the rule merging the agents' answers. Building on HIP-LLM, a hierarchical imprecise-probability assessment of single LLMs, we propose a framework combining it with a Bayesian network of the system's failure logic for multi-agent systems. Agent failure-probability intervals propagate through this network, where the combining rule can itself fail, into a reliability envelope showing which evidence limits it. In a pipeline extracting regulated chemical-hazard statements, majority voting over three models protected against the weakest but did not clearly exceed the best, and a voter failing on 5\% of demands would largely erase its advantage over the middle model. More agents yield a more defensible reliability claim, not automatically a more reliable syst

---

### [40] RT-DETR-World: Transferring Rich LLM Semantics to Real-Time Open-Vocabulary Detection

**链接**: https://arxiv.org/abs/2610.09502
**作者**: Yupeng Zhang, Ziyi Zhao, Juntao Cheng, Sheng Wang, Ningnan Guo, Ruize Han 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Muon Sublates the Edge of Stability in LLM Pretraining

**链接**: https://arxiv.org/abs/2609.34915
**作者**: Yanzhe Chen, Qifang Zhao, Xiaoxiao Xu, Fanghui Liu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] Localization Does Not Imply Steerability: A Mechanistic Study of Sign Errors in LLM Mathematics

**链接**: https://arxiv.org/abs/2611.07478
**作者**: Shradha Agarwal, Tariq J., Deepak Rajbhar
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When large language models do multi-step mathematics, a characteristic failure recurs: the model writes one wrong sign token mid-computation -- a cofactor sign, the minus of a recursive integration-by-parts step -- then executes the rest of the arithmetic correctly, and the answer comes out wrong. We ask where inside the network that sign is written. Across six open models spanning 14B to 675B parameters, a per-layer readout shows the wrong sign is committed late -- by MLP layers in the last quarter of the network (70-100% per model and task), a pattern present, where tested (Qwen), in the base model before instruction tuning. The mechanism varies: some models carry fixed "minus-stamp" layers that push a minus regardless of the right answer, others carry amplifiers of whichever sign was already chosen, and Qwen adds a downstream rescue layer that opposes the stamp. The circuit is causal: subtracting a single sign direction from the residual stream flips 13 of 14 held-out minus-written 

---

### [43] RouteAlign: Aligning Task Requirements with Model Profiles for LLM Service Selection

**链接**: https://arxiv.org/abs/2611.08162
**作者**: Jihao Zhao, Ding Chen, Yanfang Chen, Bo Tang, Feiyu Xiong, Junchi Yan 等 (7 人)
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM service selection requires performance evidence that reflects the demands of the current task. Aggregate scores obscure differences in capability and difficulty, while semantically related examples can involve different combinations of skills. We present RouteAlign, which uses task requirements to structure both the measurement of model performance and the selection of services. Task requirements describe capability demand and difficulty, enabling alignment with corresponding model performance measurements. Historical requirements determine how outcomes contribute to global profiles and local capability estimates; incoming requirements determine how those measurements inform the current decision. A shared scorer integrates the evidence, and a generation-cost preference controls selection among eligible services. Evaluation across diverse tasks and heterogeneous LLM services shows that RouteAlign extends the empirical quality-cost frontier toward higher task quality. Comparisons wit

---

### [44] Can an LLM Actually Reason and Program about Neural Network's Weights or is it just memorization on steroids? Exploring "Weight-Space Programming"

**链接**: https://arxiv.org/abs/2611.08070
**作者**: Nazmus Sakib Ahmed
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have recently been reported to read and write the raw weights of neural networks directly, a capability termed weight-space programming. We ask whether the reading side of this capability reflects reasoning about weight flows or a combination of local arithmetic at the network's edges and memorized priors over public datasets. We test Claude Opus 5.5 on small convolutional networks of about 125,000 parameters trained on five image datasets, providing every weight as plain text with no tools, no forward passes, and no dataset or class names. The model performs accurate local calculations: batch-normalization statistics lead it to infer about three optimizer steps on networks stopped after three updates, and output-layer sign patterns recover the vehicle/animal split of CIFAR-10. The sessions report reading the first and last layers closely and sampling the middle, and several claims built on partial tracing fail verification, although we did not run a direct

---

### [45] SeKV: Resolution-Adaptive KV Cache with Hierarchical Semantic Memory for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2606.31145
**作者**: Amirhossein Abaskohi, Giuseppe Carenini, Peter West, Yuhang He
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] BlockLock: Reproducible LLM Inference with Fixed Batch Geometry

**链接**: https://arxiv.org/abs/2611.06977
**作者**: Xiuyuan Qi, Pedro Reviriego, Javier Conde, Shanshan Liu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducible LLM inference requires that a request produces the same output regardless of the other requests in the batch. Existing solutions pay for this in different ways: batch-invariant kernels constrain every operator, and isolating prefill with fixed-shape decode ({our CoRun-style baseline}) gives up shared prefill compute and pads decode. We present BlockLock, which keeps shared batched prefill and pins only the numerical path of the protected request: it fixes the geometry that the request sees, with {two modes: BlockLock-Rows uses fixed-width rows and retains batched decode of all requests; BlockLock-Pack uses terminal-anchored packing with an isolated dummy segment, then extracts the protected request's KV state for target-only decode. Under a stated per-deployment contract, both modes preserve the target's output bitwise when its companions change.} Across five {dense} models (Qwen3-8B/14B, Llama-3.1-8B-Instruct, and Gemma-3-4B/12B-IT) and three single-GPU deployments (NVIDI

---

### [47] Structural and Representational Agency in LLM-Driven Timbre Generation and Interpolation

**链接**: https://arxiv.org/abs/2610.12532
**作者**: Joseph Cameron, Alan Blackwell
**来源**: cs.SD cs.HC cs.LG cs.MM eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Unifying and Beyond the Theory of Pervasive Capability Degradation in LLM Post-training SFT from Feature Interference

**链接**: https://arxiv.org/abs/2611.05003
**作者**: Hang Chen and Jiaying Zhu and Wenya Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] PCBRouteAgent: How Close Are LLM Agents to Becoming PCB Routing Engineers?

**链接**: https://arxiv.org/abs/2611.08175
**作者**: Yue Zhang, Jilei Sun, Liqiang Jing, Yijie Wei, Ruohan Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automating printed circuit board (PCB) routing requires coordinating board-level connectivity decisions with geometric execution under strict design rules. Although recent agents can interact with native routing tools, reliable routing on complex boards remains challenging. We present PCBRouteAgent, a multimodal PCB routing agent inspired by how human engineers coordinate global strategy with local execution. A Global Routing Planner combines board images and structured electrical and geometric information to specify connection topology, routing order, corridors, and layer transitions. A Detailed Routing Executor realizes these guides through KiCad's native routing engine and performs bounded local recovery. Unresolved failures are returned as structured feedback, enabling targeted guide revisions while preserving accepted routes. We evaluate PCBRouteAgent on 247 synthetic and real-world boards from four PCBWorld-Bench test splits. It achieves clean-pass rates of 100%, 94.9%, 100%, and

---

### [50] Are LLM Safety Judges Policy-Invariant? A Three-Principle Stress-Test

**链接**: https://arxiv.org/abs/2605.06161
**作者**: Shihao Weng, Yang Feng, Xiaofei Xie
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] Generate-then-Rank: Learning Symbolic Goal Interpretation for Embodied Agents

**链接**: https://arxiv.org/abs/2611.07825
**作者**: Jisen Lei, Huizhi Liang
**来源**: cs.AI cs.CL cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Goal interpretation is to translate a natural language instruction into a formal symbolic goal that a planner can execute. It is critical for embodied agents because any error here propagates to every downstream planning and action step. Doing it well requires both generating suitable candidates and reliably selecting among them. We present a two-stage generate-then-rank approach to Goal Interpretation in the Embodied Agent Interface (EAI). First, supervised fine-tuning adapts a Large Language Model (LLM) to EAI's output convention. Second, Candidate-Output Ranking from Errors (CORE) learns preferences over complete outputs from the model's own generated alternatives. We conducted experiments on the household scenes of the Embodied Agent Interface Benchmark. Multiple open source LLMs including DeepSeek-V3 chat, DeepSeek-Reasoner, and Qwen2.5-7B and Qwen2.5-72B were evaluated. The proposed method outperformed the baseline models including LLMs with simple prompting, chain-of-thought, an

---

### [52] GAAC: Lossless KV Compression for Bandwidth-Efficient LLM Inference on Personal Devices

**链接**: https://arxiv.org/abs/2610.38210
**作者**: Yipin Guo, Arun M George, Siddharth Joshi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] FedReason: Large Language Models as Weight-Space Meta-Aggregators for Heterogeneous Federated Learning

**链接**: https://arxiv.org/abs/2611.08383
**作者**: Ali Mohammadi Ruzbahani, Abbas Yazdinejad, Hadis Karimipour
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated learning servers combine client models with a fixed aggregation rule, and each rule in common use is designed for one kind of heterogeneity. We study whether a large language model (LLM) that inspects the client models can choose the rule itself, without any training on the server. In FedReason, the LLM is called every ten rounds. It analyses the weights by running code in a restricted server-side sandbox, sees only the printed results, may score a few candidates on a 500-image proxy set, and submits a short Python aggregation program. The server applies the program until the next call and falls back to FedAvg whenever its output is invalid. Full weight tensors never leave the server. We evaluated FedReason with Claude Opus 5.5 on CIFAR-10 and CIFAR-100 with ResNet-18 under Dirichlet label skew, width-heterogeneous sub-models and Byzantine clients, in 168 runs against 14 baselines. Across 12 paired label-skew runs it beat FedAvg by 1.26 percentage points on average (10 wins),

---

### [54] Interactive Backdoor Attacks in LLM-Based Proactive Dialogue Systems

**链接**: https://arxiv.org/abs/2611.06969
**作者**: Zhiyang Xia, Yuming Shang, Xi Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based proactive dialogue systems provide goal-directed support through sustained interaction. Fine-tuning their underlying models on externally supplied dialogue data introduces backdoor risks. Existing LLM backdoor studies primarily focus on eliciting an attacker-specified response upon trigger activation. We present an interactive backdoor attack framework that uses training-data poisoning to steer post-trigger, multi-turn interactions toward an attacker-specified objective. Poisoned fine-tuning dialogues implant a trigger-conditioned guidance-policy bias that ordinary user utterances can activate, without deployment-time prompt modification or further attacker intervention. Specifically, we instantiate three complementary attacks under progressively expanded post-trigger interaction settings: (1) Direct Attack, which targets an immediate response deviation upon trigger activation, retaining the conventional trigger--response setting; (2) Constrained Progressive Attack, which pro

---

### [55] Who Should Know What? Empirical Information Design for Multi-Agent LLM Economies

**链接**: https://arxiv.org/abs/2611.07667
**作者**: Mete Erdogan, Mirac Suzgun, Aneesh Pappu, Guowei Xu, Batu El, Andrew A. Schoen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of multi-agent LLM systems depends not only on the capabilities of the underlying models but also on information-sharing policies, which govern what information each agent observes and at what level of detail. But does providing AI agents with more detailed information always improve collective outcomes, or can transparency paradoxically degrade efficiency? To investigate this, we introduce empirical information design, an experimental framework that systematically compares disclosure policies across economic markets populated by LLM agents, while holding interaction rules and models fixed. We evaluate ten frontier LLMs in multi-resource trade, bilateral bargaining, and double auctions, using ground-truth utilities to decouple identified opportunities from realized outcomes. We find that finer information disclosure yields highly model-dependent results. In trade, revealing exact valuations rather than ordinal preference rankings reduces realized gains for GPT-6 Sol (fr

---

### [56] Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs

**链接**: https://arxiv.org/abs/2611.07483
**作者**: Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise AI agents increasingly split a user's request across subagents and merge their results, and each handoff can summarize away, alter or ignore a requirement. We report a preregistered study with synthetic, exactly scorable tasks comparing free-text, structured JSON and signed requirement-manifest handoffs: the orchestrator extracts each requirement as a verbatim quote plus a checkable predicate, code signs the manifest with HMAC-SHA256, and deterministic code verifies the merger's decision. With Qwen3-8B (1,440 trajectories, five threats), signed manifests cut unsafe commits under attack from 69.4% to 9.0% (60.4 pp, 95% CI [51.4, 69.4]) with no net loss of conformant commits relative to structured handoffs. Signing is what defeats in-transit tampering: an unsigned manifest committed violations in 79% of mutated runs, the signed one in none. On identical trajectories the deterministic verifier caught 78.7% of violating decisions versus 59.0% for an LLM checker, with 7% versus 5

---

### [57] LinAlg-Bench: A Forensic Benchmark Revealing Structural Failure Modes in LLM Mathematical Reasoning

**链接**: https://arxiv.org/abs/2605.16675
**作者**: Shradha Agarwal, Deepak Rajbhar, Tariq J
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] A Night at the LLM Zoo: Data Conditioned Flow Matching for Generating Pretrained LLM Weights

**链接**: https://arxiv.org/abs/2611.07103
**作者**: Scott Biggs, Bedionita Soro, Saumya Gupta, Bruno Andreis, Sung Ju Hwang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A challenge to Weight Space Learning as it expands from task specific and vision models to Large Language Models (LLMs) is the absence of a well curated and analyzed LLM population. To address this, we train such a model zoo for application to Weight Space Generation by systematically varying the data mixture composition between web text, books, mathematics, coding, and French across populations of 51M, 124M, and 355M parameter GPT-2 Models, each tier with count N = 100. We analyze these populations by cosine similarity, functional diversity, Leave-One-Mixture-Out modeling, and variance decomposition. We show that the zoo contains diverse models whose variation is structured by training mixture composition. We embed the training mixture composition to condition a Flow Matching model of complete pretrained LLM weights in Gram-PCA compressed weight space. By demonstrating zero-shot generalization to held out mixtures, measuring Continuous Ranked Probability Score skill, as well as findin

---

### [59] The Price of Safety: Benign-Case Utility and Token Overhead of Memory-Poisoning Defenses in LLM Agents

**链接**: https://arxiv.org/abs/2609.22818
**作者**: Pritom Bhowmik
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] ZeroRAG: Adaptive Semantic Peer Routing for Decentralized Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2611.07928
**作者**: Petru Neague, Quinten Stokkink, Martijn de Vos, Rafael Pires, Mathis Randl, Anne-Marie Kermarrec 等 (7 人)
**来源**: cs.DC cs.AI cs.IR cs.NI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) is a standard approach to enhance the reliability of large language model (LLM) outputs by retrieving documents relevant to a query and supplying them in the LLM prompt. Today's RAG systems collect, index, and serve these documents from centralized stores. In practice, however, documents are owned by organizations, devices, and individuals who cannot or will not surrender custody of them to a central party, e.g., because of privacy, copyright or regulatory compliance. Existing modern decentralized retrieval techniques either reintroduce a coordinating authority, or rely on a global data structure that requires continuous network-wide coordination (e.g., DHTs). We present ZeroRAG, a decentralized routing layer for document retrieval in RAG that performs semantic query routing across an overlay of peers with- out global data structures or centralized orchestration. Documents remain with the peers that own them, and each peer keeps only lightweight loc

---

### [61] Signals, Evidence, and Context: User Scrutiny in Real-World LLM Conversations

**链接**: https://arxiv.org/abs/2611.08232
**作者**: Ahana Biswas, Yu-Ru Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often present synthesized answers without making their supporting evidence easy to inspect. We study how features of these answers relate to users' subsequent accepting, checking, and challenging in 489,283 assistant-user response pairs from ShareChat and WildChat. Broad attribution language appears in 31.9% of qualifying responses, compared with explicit URLs in 1.33%, revealing a gap between claims of grounding and preserved inspectable support. Attribution, uncertainty, and other response cues generally accompany both checking and challenging; only uncertainty shows a small statistically distinguishable pooled association favoring checking. Within Technical Help, uncertainty favors checking relative to challenging; refusals and reasoning traces favor challenging in Seeking Information. Scrutiny is concentrated in some conversations, while its apparent turn-to-turn persistence becomes much smaller when conversation-level differences and response ordering 

---

### [62] MCPHallu: Benchmarking Reasoning, Execution, and Memory Hallucinations in MCP Agents

**链接**: https://arxiv.org/abs/2611.07689
**作者**: Yizhen Jiang, Haowei Guo, Tianyi Bai, Zengjie Hu, Lu Ma, Zhengyang Zhao 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly deployed through the Model Context Protocol (MCP), which allows them to discover and invoke tools across multiple servers at runtime. Existing MCP benchmarks primarily measure task completion; where they diagnose failures, they do so after execution rather than building specific reasoning, execution, and memory failure risks into task construction. We introduce MCPHallu, a benchmark for diagnosing hallucination-prone agent failures in MCP environments along three axes: reasoning, execution, and memory. MCPHallu contains 358 tasks across five capability domains and runs on 36 production MCP servers in isolated containers. Each task is designed with a structural trigger that makes one of four subtypes the dominant failure risk: Branch Collapse, Unreachable Goal, Tool Misuse, or Context Forgetting. This design enables subtype-level analysis rather than aggregate task success alone. We evaluate fourteen frontier LLM agents from eight vendors on 

---

### [63] AutoVend: Benchmarking LLM Agents on Long-Horizon Autonomous Vending Operations

**链接**: https://arxiv.org/abs/2610.36980
**作者**: Qiming Shi, Yikun Li, Beidi Luan, Rui Sun, Sinuo Wang, Delin Wang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Autoregressive Diffusion World Models for Off-Policy Evaluation of LLM Agents

**链接**: https://arxiv.org/abs/2606.05558
**作者**: Kaixuan Liu, Guojun Xiong, Weinan Zhang, Shengpu Tang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Binding Paraphrased Instructions to Encountered Objects in sLLM Agents under Partial Observability

**链接**: https://arxiv.org/abs/2611.07599
**作者**: Chanyoung Kim, Harim Song, Byoungchan Ko, Keonyoung Lee, Myungwon Lee, Dahuin Jung
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable deployment of LLM agents requires grounding diverse user expressions in their environments. Although RL-finetuned smaller large language model (sLLM) agents rival larger prompted LLMs on embodied tasks, their robustness to instruction paraphrases remains unclear. We introduce ALFWorld-Para to evaluate this robustness under controlled paraphrases, revealing 21-52% declines in success rates (SRs), predominantly driven by object synonyms. Despite retaining knowledge of synonym referents, agents often fail to take the corresponding objects even after observing them, exposing a gap between referential knowledge and object binding. Partial observability further complicates binding, as referents may remain unseen or have already been encountered under different labels. To address this challenge, we propose BINDIntent, a training-free framework that probabilistically binds referring expressions to observed labels using semantic proximity and estimated persistence against unseen candid

---

### [66] Reward Budgeting Reduces Premature Convergence in Reinforcement Learning for LLM Reasoning

**链接**: https://arxiv.org/abs/2611.05942
**作者**: Mengni Jia, Mengyu Zhou, Xiaoxi Jiang, Guanjun Jiang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Octopus: One Brain, Many Branches for Latent-KV Multi-Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.06956
**作者**: Tianming Sha
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems explore in parallel by spawning sub-agents with isolated context windows, whereas single-agent systems append every search and verification step into one growing trajectory. However, existing multi-agent frameworks duplicate prefix KV caches across branches, exchange findings by re-prefilling text summaries, and flatten or drop cross-branch dependencies during reinforcement learning (RL). We introduce Octopus, a single-model multi-agent RL framework in which all threads share one backbone and coordinate over a GPU-resident directed acyclic graph (DAG) of KV states through five primitives (fork, read_thread, wait_threads, rewind, commit). Octopus combines three co-designed mechanisms: (1) Zero-Copy Radix Forking, which spawns branches as $\mathcal{O}(1)$ cursor views over shared physical KV pages; (2) Attention-Only KV Mounting, which mounts a sibling thread's terminal KV blocks directly into full-attention layers while bypassing linear-recurrent states (Gated De

---

### [68] The Popular Get More Popular: Auditing Brand Bias in Generative Search

**链接**: https://arxiv.org/abs/2611.07614
**作者**: Giorgio Monaco, Jacopo Lenti, Francesco Pierri
**来源**: cs.CY cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The shift from traditional to generative search has fundamentally transformed online product discovery. Because conversational recommendations synthesize choices into a few direct answers, subtle systemic preferences toward specific providers can exert profound commercial impacts. In this work, we audit this phenomenon through two distinct dimensions: (i) brand popularity bias, the systematic preference for market-dominant entities over long-tail alternatives, and (ii) brand familiarity bias, the ranking advantage an entity encoded in an LLM's parametric memory holds over an unfamiliar competitor. First, evaluating commercial queries across major engines, we observe persistent brand popularity bias: dominant brands in the top quintile are cited 1.4x to 2.8x more frequently than the average brand within a sample of 1,176 top market players, already present in parametric memory that external web retrieval fails to mitigate. Second, through controlled in-context experiments holding produc

---

### [69] KDASO: Knowledge-Data Dual-Driven Automated Skill Optimization for Liability Adjudication Tasks

**链接**: https://arxiv.org/abs/2611.06972
**作者**: Zi-Jian Cheng and Weiming Wu and Jie Meng and Zhen Peng and Shan Huang and Qun Li and Guobing Wu and Lan-Zhe Guo
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Liability adjudication tasks (e.g., legal charge determination) require analyzing event descriptions against domain-specific skills to determine whether a party should bear liability. While Large Language Models (LLMs) have shown promise in this area by leveraging executable skills for interpretable reasoning, existing approaches face three critical limitations: skill libraries become stale as real-world scenarios dynamically evolve, skill descriptions often suffer from a semantic execution gap where LLMs deviate from intended expert logic, and growing skill collections exceed context budgets causing critical skill omission. To address these challenges, we propose Knowledge-Data Dual-Driven Automated Skill Optimization (KDASO), which continuously evolves a skill library through neighborhood-conditioned induction from recent adjudication data, execution-aligned refinement based on LLM trajectory analysis, and context-budgeted routing for scalable skill selection. Experiments across ride

---

### [70] Selective Retrieval Routing for Multi-Violation Knowledge Graph Repair

**链接**: https://arxiv.org/abs/2611.07342
**作者**: Tung-Wei Lin, Gabe Fierro, Han Li, Tianzhen Hong, Pierluigi Nuzzo, Alberto Sangiovanni-Vinentelli
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graphs often contain missing or inconsistent facts that undermine the applications built on them. Schema validation detects such violations but does not identify which of several valid repairs recovers the intended graph. External corpora can supply the evidence needed to identify the intended repair, but retrieving from them is costly and not always successful. We propose a framework for selective retrieval in iterative graph repair. An LLM repair agent explores and edits the graph, while a router controls its access to a researcher agent that retrieves external evidence. We extend a violation-injection framework to generate cases with multiple compatible violations and known reference repairs. The agent's repair outcomes on these cases provide supervision for training the deployment-specific router. On two building-automation datasets, researcher access improves repairs for some violations and degrades them for others, with effects differing across deployments. The router u

---

### [71] Redacting Personal Data: A Speed and Accuracy Comparison of Regex, Presidio and Hybrid Designs

**链接**: https://arxiv.org/abs/2611.07633
**作者**: Sai Yashwant, Manoj Kumar Gondimalla, Arjun Sharma, Shubham
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many enterprise projects now pass free text to large language models (LLMs), and that text often contains personally identifiable information (PII) such as names, phone numbers, email addresses, home addresses and dates of birth. Once a prompt is sent, this data is copied into provider systems, application logs and observability traces. Redacting PII before the call is an obvious control, yet teams seldom have numbers on what it costs in latency or what it lets through. This paper compares four redaction designs that any LLM pipeline can adopt: a pure regular-expression (regex) redactor, Microsoft Presidio running on a spaCy model, a hybrid in which Presidio finds only person names while regex handles structured identifiers, and a fast hybrid that calls spaCy's named-entity component directly. All four share a known-entity rule, which removes the person the system already knows it is handling, and a consistent placeholder scheme, so the LLM can still tell one person from another after 

---

### [72] WeightLoop: Weight-Space Programming with Experimental Feedback

**链接**: https://arxiv.org/abs/2611.07319
**作者**: Mengran Li, Bo Li, Weijing Zhao, Chengyang Zhang, Boyu Zhang, Jinfeng Xu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-space programming (WSP) shows that language models can reason about and rewrite neural network weights; recursive self-improvement (RSI) motivates feedback-driven improvement. Models guiding experiments receive concrete feedback: completed assays reveal prediction errors and inform what to test next. We introduce WeightLoop, a framework that turns experimental feedback into persistent updates to deployed predictors. GPT-6 Astra inspects a task specification and the model implementation, then writes a bounded, reusable parameter-editing program. As new measurements arrive, the program identifies prediction discrepancies, validates candidate edits using observed outcomes, and writes the selected changes back to the original model. The editor remains fixed while the predictor evolves, enabling repeated updates without further LLM calls or gradient retraining while preserving the original inference interface. In offline replay, targeted edits improve mean ranking utility in seven of

---

### [73] MedGraph: Maintaining Patient State with Graph Memory for Long-Term Medical Dialogue

**链接**: https://arxiv.org/abs/2611.08433
**作者**: Donghua Zhang, Zizheng Wang, Ze Dong, Yiding Feng, Siyu Qian
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based medical assistants that follow a patient across visits need a memory that keeps the patient's clinical state correct as it changes. We examine the errors of five memory systems on longitudinal medical dialogue and find three recurring causes: the retrieved evidence gives an outdated state, includes another person's health facts, or lacks a safety fact the answer depends on. We present MedGraph, a graph memory built for these three cases. Construction extracts dated facts from each session, attributes each fact to the person it describes, and links medication, diagnosis, and measurement records into chains that keep earlier states. Retrieval ranks the patient's chains as units, reads each chain at the time the question asks about, and adds the original dialogue text; a patient profile lists every recorded safety fact with every question. On MedMemoryBench, MedGraph has the highest overall accuracy with both a GPT and a Qwen backbone, 10.5 and 10.4 points above the strongest of

---

### [74] An Information Bottleneck for Post-hoc Memorization Mitigation in LLMs

**链接**: https://arxiv.org/abs/2611.07669
**作者**: Dina EL Zein, Shashi Kumar, and James Henderson
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies have shown that large language models (LLMs) can memorize and reproduce copyrighted training data, raising serious privacy and intellectual property concerns. In this work, we investigate whether memorization can be mitigated without modifying or retraining the underlying model through an information bottleneck. We propose a modular plug-and-play framework that inserts a nonparametric variational information bottleneck (NVIB) between a frozen LLM backbone and its language modeling head. By compressing the final hidden representations before token prediction, the proposed bottleneck aims to preserve general linguistic knowledge while filtering out highly specific memorized sequences. We evaluate our approach on memorization extraction tasks involving book passages and on standard language modeling benchmarks to measure the trade-off between memorization reduction and downstream utility. Our experiments show that the NVIB layer substantially reduces extractability while ma

---

### [75] AutoCompress: Automated Hardware-Guided Model Compression

**链接**: https://arxiv.org/abs/2611.08290
**作者**: Sheldon Liang, Ali Taghibakhshi, Saurav Muralidharan, Sharath Turuvekere Sreenivas, Ashwath Aithal, Pavlo Molchanov 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM pruning must preserve quality while meeting hardware- and workload-specific constraints on latency, throughput, and memory. Existing pruning workflows often target parameter counts, requiring practitioners to manually select model sizes that meet latency, throughput, and GPU memory limits. However, parameter count alone does not predict these metrics, which depend on the model architecture, workload, hardware, and serving engine. We introduce AutoCompress, a hardware-guided compression framework that directly incorporates such constraints into differentiable architecture search. AutoCompress jointly optimizes global and per-layer structure to produce heterogeneous architectures, guided by serving-engine cost models validated against end-to-end latency, throughput, and memory measurements. We evaluate AutoCompress on long-context local coding, batched datacenter serving, and latency-sensitive in-game interaction. Compared to the state-of-the-art Minitron pruning framework, AutoCompr

---

### [76] SwarmEvolve: Latent Agent Swarms for Evolutionary Discovery and Optimization

**链接**: https://arxiv.org/abs/2611.08483
**作者**: Qile Jiang, George Em Karniadakis
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-guided evolutionary search uses AI agents to improve programs for mathematical and computational problems by iteratively refining solutions and combining high-scoring methods. However, the process is often slow because the LLM generates a long textual chain of thought for each round and must repeat this generation many times to maintain population diversity. We present SwarmEvolve, a framework in which hundreds of low-cost agents per round work in swarms, reason in latent space without decoding to text, and share information by passing KV caches. Each swarm studies the problem from a different angle. A novelty filter keeps the most distinct agent ideas by directly measuring the distances between the agents' hidden state vectors. Crossover of ideas happens naturally in latent space, as a summarizer agent receives the combined KV caches of all swarm members. On 21 problems in mathematical discovery and scientific computing, SwarmEvolve gets the highest average score and needs a media

---

### [77] AttnSR: Attention Step Reward for Long-Horizon Agentic RL

**链接**: https://arxiv.org/abs/2611.07932
**作者**: Mengsong Wu, Tianchen Zhou, Zhaochen Su, Zhenhua Liu, Zhe Cui, Aimin Zhou
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents make multi-step decisions, yet outcome-reward-only reinforcement learning provides little direct supervision for individual steps. We introduce AttnSR, a step-level reward augmentation method that derives reward allocations from policy attention extracted during training replay, without a separately trained reward model or additional rollouts. AttnSR traces backward through the policy model attention graph to estimate the relevance of earlier steps to the final response. The terminal step, measured relative to a running baseline, determines whether these rewards reinforce or penalize the selected steps. In a controlled Qwen2.5-7B-Instruct study, AttnSR consistently outperforms the PPO baseline across all evaluated checkpoints on ALFWorld, raising final held-out success from 91.2% to 97.1%. The ablation experiment shows that the benefit depends on how intermediate rewards are assigned, rather than simple accumulation of step rewards over time. AttnSR also improve

---

### [78] Terminal-style Mathematical Modeling Bench: The First Agentic and Verifiable Benchmark for Mathematical Modeling

**链接**: https://arxiv.org/abs/2611.08237
**作者**: Xiaojun Wu, Cehao Yang, Xuhui Jiang, Chengjin Xu, Jia Li, Jian Guo
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mathematical modeling turns an open-ended real-world problem into assumptions, a model, a solution, and a defended recommendation, and its answers matter only if they are both close to a credible reference and physically feasible; existing benchmarks either score solver fragments or grade reports with an LLM judge, leaving those numbers unchecked. We introduce TB-MathModel (the Terminal-style Mathematical Modeling Bench), the first benchmark to make complete contest-style modeling problems agentic, verifiable, and terminal at once, over 18 real CUMCM and MCM problems (2023--2025). Each task ships the verbatim statement, official attachments, and figures in a containerized terminal; the agent returns one JSON artifact, scored on the numeric core of the final question against a reproduction of the Outstanding-award paper. Two design choices distinguish it: direction-aware, one-sided scoring, which never penalises beating the anchor, and two-layer feasibility verification---a programmatic

---

### [79] CAMP: Context-Aware Mapping and Placement for LLMs on 3D-IMC Arrays

**链接**: https://arxiv.org/abs/2611.07707
**作者**: Orhun G\"orkem, Athanasios Vasilopoulos, Georgios Pagonis, Victoria Clerico, Hadjer Benmeziane, Irem Boybat 等 (9 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) incur severe memory-access overheads due to the cost of loading large weight matrices and key-value (KV) caches. Analog In-Memory Computing (AIMC) is an emerging solution that enables computation directly on static weights stored in memory, substantially reducing energy and latency. 3D-IMC further stacks memory arrays into vertical tiers, increasing capacity but revealing a new challenge: how weights are placed in memory determines which matrix-vector multiplications (MVMs) can execute concurrently, affecting latency and throughput. The concurrency aspect of 3D-IMC weight-mapping remains underexplored in the literature, leading to sub-optimal utilization of compute resources on 3D-IMC chips. In this context we propose CAMP (Context-Aware Mapping and Placement), an inference-context-aware weight mapping algorithm for 3D-IMC-based LLM accelerators. CAMP captures the potential resource contention resulting from the architecture, targeted network, and runtime c

---

### [80] The Last Mile to the Real World: Agent-Native Primitives as Reusable Building Blocks for Solving Real-World Tasks

**链接**: https://arxiv.org/abs/2611.07461
**作者**: Haibo Jin, Peng Kuang, Xiaopeng Yuan, Lucheng Fu, Jerry Wang, Xucheng Yu 等 (10 人)
**来源**: cs.CL cs.AI cs.LG cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How can an agent handle a real-world task end to end? Frontier models with their own harnesses still fall short on real-world benchmarks: on Terminal-Bench 4.0, GPT-5.6 Sol with Codex resolves 37.3% of the tasks and Claude Opus 5 with Claude Code 51.8%. These tasks fail at the step from reaching a resource to applying it, which we call the last mile to the real world. Existing approaches put the resource within reach but leave the competence to apply it with the caller, so each harness rebuilds that competence. We introduce agent-native primitives, reusable units that equip a resource with a resident LLM that applies it in context and communicates with other primitives, and HEELO (Harness Engineering around Evolving Agent-Native Primitives for the Last Mile to Real-WOrld Tasks), a harness engineering framework that builds each task's harness from a library of such primitives. HEELO composes the primitives a task needs into a task-specific graph, verifies the result against evidence fro

---

### [81] How Should Agents See Code? Rethinking Code Representations for Agentic Software Engineering

**链接**: https://arxiv.org/abs/2611.07286
**作者**: Melika Sepidband, Jiho Shin, Song Wang, Hadi Hemmati
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used for repository-level software engineering tasks. However, most agents still access repositories through raw files, lexical search, and shell commands, treating code primarily as text. This paper investigates map-based code-representation workflows as a design variable in agentic software engineering, examining how different repository views change agents' retrieval behavior, task success, token use, and latency. In this paper, we study five code-representation workflows: abstract syntax trees, call graphs, module dependencies, documentation-enriched search, and a hybrid workflow that combines them. Each workflow exposes a repository map that the agent can query during a task. We evaluate Claude Code with Haiku 4.5 against a raw-tool baseline on four repository-level tasks: fault localization with LinuxFLBench, repository-level code generation and repair with SWE-bench Pro, test generation with SWT-bench, and security patching with SecBench. The results 

---

### [82] OptIMerge: Optimization-Based Merging of Diffusion Models

**链接**: https://arxiv.org/abs/2611.07543
**作者**: Viraj Shah, Ashwini Pokle, Peyman Milanfar, Mauricio Delbracio, Hossein Talebi
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The arithmetic merging of weights from multiple task-specific models fine-tuned from a shared base model, commonly known as model souping, has emerged as a popular strategy for multi-task learning without the computational overhead of joint retraining. However, naive scalar weight averaging frequently leads to severe performance degradation when the constituent models learn structurally divergent feature representations, leading to destructive parameter interference. We study this problem in a largely unexplored setting: merging image-to-image (I2I) diffusion models fine-tuned for dense, pixel-accurate tasks such as image restoration. Unlike the large language models (LLMs) and text-to-image (T2I) diffusion models for which most merging methods were developed, I2I experts encode conflicting spatial priors (e.g., anisotropic motion-blur vs. isotropic defocus-blur) in their convolutional filters, where both naive soup and LLM-style element-wise merging introduce visible artifacts. We int

---

### [83] Agent-R$^2$: Scaling Agents for Realistic Productivity Work via Real-Source Data Synthesis

**链接**: https://arxiv.org/abs/2611.08219
**作者**: Teng Pan, Zixuan Wang, Yuchen Yan, Qifei Wu, Yao Chen, Yingqi Qu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have made rapid progress in agentic reasoning and tool use, raising expectations for agents that can take over realistic productivity work from humans. However, current agents still struggle to finish such tasks, where success requires following long-horizon professional workflows, understanding heterogeneous file contexts, and producing usable deliverables under fine-grained requirements. A key bottleneck is the lack of scalable post-training data that reflects real work intent, authentic file environments, and deliverable-level evaluation. To close this gap, we introduce Agent-R$^2$, a $\textbf{r}$eal-source data synthesis framework that scales training data for $\textbf{r}$ealistic productivity work. Instead of relying on manually specified workflows or LLM-generated files, Agent-R$^2$ grounds synthesis throughout the pipeline in real occupational seeds, corpus-derived workflow evidence, and authentic web-sourced files. From 10k web-corpus candidates, Agent-R$^

---

### [84] Measuring the Marginal Value of Verifier-Based RL Beyond Supervised Fine-Tuning

**链接**: https://arxiv.org/abs/2611.07639
**作者**: Amit Sagtani and Saloni Garg
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning from verifiable rewards (RLVR) is usually evaluated as an alternative to supervised fine-tuning (SFT), or as a stage that follows it, with the implicit assumption that the RL stage contributes gains of its own. We measure that contribution directly, in a controlled setting where both stages can be run to completion and compared exactly. We built gpu-train-debug, a deterministic benchmark of 1,877 synthetic GPU and LLM training failure diagnosis tasks across 30 archetypes, graded by a programmatic verifier with partial credit, and calibrated so that a mid-tier model scores in a 0.60 to 0.75 band. A pilot produced a surprise: 1,200 gold demonstrations nearly solved the benchmark (SFT 0.785 on the hard split), while 15 steps of GRPO from the base model did not move it (0.314 vs 0.311 base). We therefore amended the study, in writing and before the full run, to ask the sharper question: what does verifier-based RL add beyond demonstrations? At the pre-registered scal

---

### [85] Stress Testing Chain-of-Thought Monitoring Against Covert Misalignment

**链接**: https://arxiv.org/abs/2611.07586
**作者**: Yao Huang, Yifan Wang, Yitong Sun, Yichi Zhang, Yinpeng Dong
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents advance rapidly in autonomy, the risk of hidden objectives that bypass safety constraints becomes increasingly plausible. Chain-of-thought (CoT) monitoring offers a key control mechanism by reading the agent's reasoning and flagging misalignment before it materializes into action, yet its reliability depends on the realism of the red-team it is stress-tested against. Existing red-teaming efforts rely on shared templates, such as casting a side task as a prerequisite, which treat the side objective as an exogenous insertion and leave task-specific, contextually grounded evasions underexplored. We therefore ask: How robust is CoT monitoring against agents that strategically conceal misalignment? To answer this, we introduce TraceMRT, an automated Trace-level Monitor Red-Teaming framework that reframes the side task as a coherent sub-goal of the primary task and searches trace-shaping strategies whose induced trajectories complete the misaligned objective while reading as na

---

### [86] QRAE: Query-Relevant Attention Entropy for Context Compression in DeepSearch Agents

**链接**: https://arxiv.org/abs/2611.07976
**作者**: Yingjie Tan, Haiquan Qiu, Quanming Yao, Manyi Zhong, Xianzhi Yu, Yaqing Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> DeepSearch LLM agents repeatedly search and carry retrieved sources into subsequent reasoning steps. This expanding context increases token consumption and latency, although many results do not contribute to later reasoning. We propose Query-Relevant Attention Entropy (QRAE), an online context compression method that uses sparse evidence-assessment heads to decide which intact retrieved chunks should persist across reasoning steps. It scores bounded candidate batches through paired prefills: a query-free control suppresses shared attention responses, while normalized entropy measures the breadth of the positive response within each chunk. High-scoring chunks enter a persistent evidence whitelist and are included in the reasoning context. Uncertain chunks remain outside the reasoning context but are retained in a candidate cache, where they can be retrieved for later reevaluation. QRAE requires neither an additional generative compression pass nor modification of the attention operator.

---

### [87] Test-Time Self-Play: Scaling without a Verifier

**链接**: https://arxiv.org/abs/2611.07367
**作者**: Akira Yoshiyama, Akmal Ashirmatov, Jonas H\"ubotter, Ido Hakimi, Andreas Krause
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling methods spend additional compute at deployment to improve a large language model's performance on a hard target problem. Most methods rely on a verifier that scores candidate solutions for correctness, using it to select among or refine the model's outputs. In many deployment regimes, however, a strong verifier on the target problem is unavailable. We introduce Test-Time Self-Play (TTSP), an approach to test-time scaling using asymmetric self-play without reliance on a verifier. On a difficulty-calibrated subset of LiveCodeBench v6, TTSP is the best-performing method at every verifier strength we evaluate, and the gap to the strongest baseline widens as the verifier weakens; in the no-verifier limit, TTSP yields a 35\% absolute improvement in mean@8. The gains hold across a range of verifier strengths, except when the base policy has near-zero coverage of the correct answer.

---

### [88] How Do AI Agents Waste Your Money?

**链接**: https://arxiv.org/abs/2611.07238
**作者**: Huimin Zeng, Yuxuan Lu, Jesse Cai, Eric Hanchen Jiang, Di Wu, Po-Nien Kung 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents may consume massive tokens across a wide range of tasks, but how many of those tokens are really necessary? Although prior work has shown that agents can incur unexpectedly high token costs, we still lack a systematic way to identify and measure token waste. In this work, we introduce a unified framework for measuring token waste across heterogeneous agent systems. Our framework records and normalizes complete agent trajectories, identifies removable spans using an LLM-as-a-Judge (LLMaJ), and maps the identified text spans back to the original trajectory for token-level measurement. We validate the identified waste through direct interventions by removing marked spans, resuming agent execution, and measuring changes in task outcomes and subsequent actions. In online pruning experiments, we remove 41-46% of the model's reasoning while largely preserving task performance across two distinct agent benchmarks. Using this framework, we analyze agents across multiple settings. Our 

---

### [89] Decodability Is Not Validity: Evaluating Nuisance Sensitivity in Language Model Concept Probes

**链接**: https://arxiv.org/abs/2611.07805
**作者**: Ayal Klein
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two concept probes can be equally accurate at predicting a concept from a language model's hidden states while their scores contain different mixtures of the target concept and a correlated nuisance attribute. In four target--nuisance settings (two aspect sentiments in CEBaB; occupation and gender in BiasBios; Amazon review sentiment with negation, and with first-person framing), two LLMs, and a population of concept extractors, we compare decodability with discriminant evidence: the score's dependence on the nuisance at fixed target, and its response to input edits intended to change only the nuisance, filtered by two LLM judges and compared against placebo edits. Under correlated training data, extractors that are statistically equivalent in held-out AUROC differ up to several-fold in nuisance sensitivity in three of the four settings, and decodability is not a reliable proxy for it: their rank correlation changes sign across settings. The effect follows the probe's training data, no

---

### [90] Compositional Unalignment: Auditing Safety in Large Vision-Language Models

**链接**: https://arxiv.org/abs/2611.07216
**作者**: Hong kyu Lee, Kai Shu, Li Xiong
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large vision-language models (LVLMs) are vulnerable to compositional harm: an image and a prompt that are benign in isolation become harmful through the model's cross-modal reasoning. Recent alignment methods report strong scores on compositional safety benchmarks, but an LLM judge only measures observed behavior and cannot reveal how robustly safety is integrated into the model. We argue that un-alignment provides a complementary audit of alignment robustness. We first show that minimal supervised fine-tuning reaches an LLM-judge score comparable to a multi-stage reinforcement-learning pipeline, so similar benchmark scores cannot establish robustness by themselves. We then show that recognition and refusal of compositional harm are decoupled: nine standard direction-finding methods detect compositional harm with up to AUC=0.99, yet ablating the recovered directions either leaves refusal intact or destroys model coherence. We therefore propose CMaG, a training-free un-alignment method 

---

### [91] EnvOpt: Automated Optimization for Agent Environments

**链接**: https://arxiv.org/abs/2611.07372
**作者**: Mingxuan Li, Huanzhi Mao, Qiuyang Mang, Hanchen Li, Joseph E. Gonzalez, Alex Dimakis
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent's cost and success depend on its model, its harness, and its environment. In addition to the widely studied directions of parameter tuning and harness optimization, we propose the third direction: optimization over stationary environments. Agents are often deployed in rich environments shared by many tasks, such as a company's Slack workspace or a complex collection of data sources, documents or tickets. We call these environments stationary environments. We introduce EnvOpt, a method for automated end-to-end optimization of stationary environments for any given model and harness, using real or synthetic tasks without needing any graders or reference answers. On AutomationBench, EnvOpt reduces the cost of Claude Haiku 4.5 by 72.7% and raises its pass rate by 14.34%. The same environment transfers to Opus 5, cutting its cost by 68.1% with a 1.34% gain. Added on top of Meta-Harness's optimized harness for Haiku 4.5, it lowers cost by a further 83.4% and adds 11.17% accuracy 

---

### [92] SCALE: Real-Time Latent Communication for Cyber-Physical Agents

**链接**: https://arxiv.org/abs/2611.08390
**作者**: Shanghao Shi, Jian Xiao, Ching-Hsiang Chan, Sanjoy Baruah, Sastry Kompella, Yevgeniy Vorobeychik 等 (8 人)
**来源**: cs.RO cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Latent communication enables agents to collaborate efficiently by directly exchanging intermediate model representations rather than raw sensor data or text messages. Existing approaches, however, are primarily designed for LLM agents and do not consider the bandwidth constraints and heterogeneous task deadlines faced by cyber-physical agents. In this work, we propose SCALE, a real-time latent communication method tailored for cyber-physical agents. Motivated by the spatio-temporal continuity of the physical world, SCALE matches tokens across consecutive latent messages using similarity scores to identify reusable information and avoid redundant transmission. It then profiles the semantic gain and communication cost of transmitting different amounts of latent information. Based on these profiles, SCALE employs a real-time scheduler that jointly determines which pending messages to transmit and how many latent tokens to send, subject to available bandwidth and task deadlines. We evaluat

---

### [93] ChemE-as-Code: An Open-Source Platform for Agentic AI in Chemical Engineering

**链接**: https://arxiv.org/abs/2611.07947
**作者**: Artur M. Schweidtmann
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> ChemE-as-Code provides an open-source environment in which AI agents built on large language models (LLMs) can carry out chemical engineering work and engineers can check it. Its calculation tools range from catalysis through process simulation to plant layout, HAZOP and life cycle assessment, and skills tell a general-purpose agent how to use them. Engineering files are linked, machine-readable and versioned in Git; calculations run outside the LLM, each value records its origin, and automated checks report inconsistencies and out-of-date results by file and line. In an illustrative ammonia case, agents developed a written task into a preliminary basic-engineering package (simulation files, P&IDs, layout, HAZOP, datasheets, relief) for USD 224 of API cost in the design sessions. Planted faults and engineering changes show that the checks find what their rules cover and miss the rest, so they guide human review rather than replace it. No independent engineer has reviewed the design.

---

### [94] ReviewMap: Mapping Evaluative Acts and Automation Boundaries in Peer-Review Comments

**链接**: https://arxiv.org/abs/2611.07489
**作者**: Kihyun Na and Injung Kim
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer-review comments check what a paper does and judge why it matters, but no existing scheme distinguishes these two evaluative acts. We argue that making these acts explicit and measuring how reliably LLMs identify them is a prerequisite for responsible LLM-assisted review analysis: humans need to inspect review judgments and their grounds. This defines a more honest mission for NLP in peer review than full automation. We present ReviewMap, a framework that classifies each comment as assessment of claims and scholarly standards or calibration of contribution value and venue fit, with finer-grained attributes applied conditionally by act type. Applied to 500 ICLR~2026 papers through multi-model LLM consensus, the act layer proves reliably automatable under the operational guideline (inter-model $\kappa \geq 0.75$), supported by five-human validation on 470 development comments, while the attribute layer requires human oversight, defining a measured automation boundary. At the corpus l

---

### [95] Backbone-Informed Adaptation after EEG Pretraining: A Capacity-Controlled Study

**链接**: https://arxiv.org/abs/2611.07192
**作者**: Mingyang Jiang, Yamin Li, Fan Ma, Daniel Moyer, Hua Xu, Catie Chang
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) foundation models learn representations that combine information across channels and time. This structure motivates adapters that model the same relationships during downstream learning. However, it is not clear whether such a design outperforms other candidate adapters. Moreover, in order to arrive at a fair comparison between candidate adapters, we also need to consider their trainable parameters. Here, we ask whether a backbone-informed (native) adapter makes better use of a given capacity by comparing it against a token-wise multilayer perceptron control that transforms each feature vector independently. We approximately match their trainable parameter counts and keep the pretrained encoder fixed. Across two EEG foundation models and tasks covering emotion recognition, sleep staging, and EEG event classification, the native adapter shows no consistent advantage. For one backbone, differences between the designs are small relative to variation across run

---

### [96] Uncertainty calibration in Bayesian M/EEG source imaging

**链接**: https://arxiv.org/abs/2611.06979
**作者**: Ismail Huseynov, Mohammad Orabe, Srikantan Nagarajan, Stefan Haufe
**来源**: cs.LG cs.CE
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> M/EEG source imaging requires accurate localization and reliable uncertainty estimates, yet posterior credible regions are rarely assessed for empirical calibration. We present a simulation-based framework for uncertainty quantification and calibration of empirical Bayesian inverse methods with closed-form conditional Gaussian posterior summaries. We compare Bayesian minimum norm (BMN) with sLORETA depth weighting and sparse Bayesian learning (SBL) with sparse basis field expansions (S-FLEX). S-FLEX allows retained coefficients to contribute nonzero marginal posterior variance at locations where voxel-wise SBL yields degenerate variances. For BMN, we derive joint source- and noise-variance updates through evidence maximization. We test whether adaptive noise learning yields near-calibrated uncertainties. Both methods retain residual miscalibration, motivating post-hoc isotonic recalibration of credible-region levels using empirical coverage. Simulations assess fixed- and free-orientati

---

### [97] Open-HumanWAM: An Open Recipe for Scaling Human and Robot Experience for Embodied Foundation Models

**链接**: https://arxiv.org/abs/2611.06817
**作者**: Juncheng Ma, Jiaxin Li, Jiankai Tu, Bo Liang, Guodong Lv, Yufan Deng 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] When, Where, How: Active In-Context Learning for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2611.07886
**作者**: Christian M. M. Frey
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular Foundation Models (TFMs) adapt to a new task only through the labeled rows in their context. However, labels are expensive to acquire in real-world scenarios due to the need for highly specific domain knowledge to ensure high-quality data. Active in-context learning transfers classical acquisition rules to this setting, in which the model that guides acquisition changes with every label added. We ask how the value of diversity, predictive uncertainty and target-aware information gain changes as a frozen TFM acquires more context. For that, we study Target-Aware Nearest Neighbor (TANN) acquisition and the Expected Predictive Information Gain in Context (EPIC) and evaluate them against classical rules. Our study across twenty benchmarks with two well-established TFMs and classical GBDTs highlights three findings: (i) When: diversity-based acquisition is best during the first acquisition iterations; (ii) Where: labeling pool rows that serve the target inputs via a simple target-aw

---

### [99] When GeoFMs Meet VHR: Benchmarking Foundation Models on Very High Resolution Earth Observation Imagery

**链接**: https://arxiv.org/abs/2611.08003
**作者**: Kshitij Raj Sharma, Pierre Adorni, Minh-Tan Pham, Dirk Tiede, S\'ebastien Lef\`evre
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models are a widely adopted starting point for remote sensing tasks. Most are pretrained on Sentinel-1/2 and Landsat imagery at a ground sampling distance (GSD) of 10m or coarser. Many applications instead rely on very high resolution (VHR) imagery, where individual buildings, roads, and amenities are resolved. We study which pretraining regimes transfer well to this scale. We introduce VHR-Bench, a benchmark suite of ten datasets at 1.5m GSD or finer spanning five task families, eight application domains, and both satellite and aerial platforms. We evaluate twelve encoders in three pretraining tiers with frozen backbones at two training-data fractions. We find that both pretraining on large natural-image collections and VHR-specific pretraining transfer effectively to VHR tasks, with complementary strengths. SkySense leads when labels are scarce; at the full label fraction the web-pretrained DINOv3 ViT-L edges ahead, with the two close together there. Encoders pr

---

### [100] Genome-Factory: A Library for Tuning, Deploying, and Interpreting Genomic Foundation Models

**链接**: https://arxiv.org/abs/2509.12266
**作者**: Weimin Wu, Xuefeng Song, Yibo Wen, Qinjie Lin, Zhihan Zhou, Jerry Yao-Chieh Hu 等 (8 人)
**来源**: q-bio.GN cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] Scaling Recurrence-aware Foundation Models for Clinical Records via Next-Visit Prediction

**链接**: https://arxiv.org/abs/2603.24562
**作者**: Xiang Gao, Haresh Rengaraj Rajamohan, Weicheng Zhu, Shih-Lun Huang, Long Chen, Gabe Schulman 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Do sEMG Foundation Models Improve Cross-Subject Generalisation?

**链接**: https://arxiv.org/abs/2611.08199
**作者**: William Raftery, Dario Farina
**来源**: cs.LG q-bio.NC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> sEMG Foundation Models aim to learn general purpose representations over diverse subjects and recording conditions that boost performance on a variety of downstream tasks. However, existing evaluations make it difficult to discern whether pretraining alone is sufficient to combat the cross-subject overfitting which makes machine learning on sEMG so challenging. We conduct a systematic evaluation of three sEMG foundation models across three gesture classification datasets under both intra-session and inter-subject splits, using three fine-tuning strategies designed to isolate the contribution of pretraining. We find that pretraining boosts performance when train and test samples are drawn from the same recording session, but this benefit largely disappears under inter-subject evaluation. In low subject count datasets, pretraining provides little to no benefit and classical ML baselines match or exceed foundation model performance.

---

### [103] PiCo: Physics-Informed Concept Probing for Geo-Foundation Models

**链接**: https://arxiv.org/abs/2610.20973
**作者**: Yihang She, Andrew Blake, Jianbo Qi, and Srinivasan Keshav
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] Blueprint2CAD: Benchmarking Foundation Models on Engineering Drawing-to-CAD Render Correspondence

**链接**: https://arxiv.org/abs/2611.02433
**作者**: Alexander Valverde, Danny Xie-Li, Zhichao Wang, Marcos V. Conde
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Towards fNIRS foundation models: A curated corpus of 67 public datasets with channel positions in MNI space

**链接**: https://arxiv.org/abs/2610.40277
**作者**: Santiago Posso-Murillo
**来源**: cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] GeoCore-9B: Towards Geo-Aware Generative Foundation Models in Earth Observation

**链接**: https://arxiv.org/abs/2608.01896
**作者**: Jeonghyeok Do, Munchurl Kim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] VINO: Revisiting 3D Representation Learning with Volume Transformers

**链接**: https://arxiv.org/abs/2611.07176
**作者**: Adrian Kruse and Kadir Yilmaz and Daan de Geus and Francis Engelmann and Bastian Leibe
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised learning has given rise to vision foundation models that learn general-purpose image representations transferable across downstream tasks, yet representation learning for 3D scenes has not achieved comparable success. Motivated by this, we identify key limitations of current 3D representation learning approaches and revisit their core design choices. We first replace the commonly used hierarchical PTv3 backbone with the Volume Transformer, a ViT-like architecture for 3D scenes. We then redesign two core objectives of modern approaches built around student-teacher networks: matching representations across views and predicting masked content from visible context. For the first objective, we separate the roles of teacher and student: the teacher provides clean, consistent targets while the student learns invariance to stronger perturbations. For the second objective, we prevent the student from accessing the masked geometry and instead require it to infer missing represent

---

### [108] How Deep is the Signal? Time-Context up to 30 Years for Colorectal Cancer Prediction in a Primary-Care EHR Model

**链接**: https://arxiv.org/abs/2611.07265
**作者**: Achille Raviez, Lan Wang, Brendan Delaney
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EHR foundation models read medical events within a fixed context window, and long context has so far been measured only in tokens. How far back in time a model must look to capture the earliest predictive signal is unknown. We introduce time-context, the calendar lookback window before the prediction point, and provide, to our knowledge, the first systematic evaluation of decade-scale time-context for an EHR foundation model. We pretrained a decoder-only transformer (34.6M parameters) on 1.4B coded events from 3.6M primary-care patients in North West London and fine-tuned it to predict incident colorectal cancer under a 12-month pre-diagnostic buffer. A frozen cohort of 1,008 cases and 9,582 matched controls, all registered for at least 30 years, was evaluated at 15 nested lookback windows from 2 to 30 years, so that every truncation is compared within the same patients. Discrimination rose from an AUROC of 0.551 at 2 years to 0.590 at 18 years, then plateaued, with about 80% of the ga

---

### [109] InnerLogic-Surg: An Open Surgical Foundation Model via Continual Pretraining

**链接**: https://arxiv.org/abs/2611.07883
**作者**: Kun Yuan, Hao Ding, Yiqing Shen, Gasper Podobnik, Benjamin Killeen, Tito Porras 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models are the backbone of modern surgical image analysis, yet most surgical systems still rely on encoders pretrained on natural images or on specialist models trained from scratch on comparatively small datasets. Pretraining encoders on large amounts of surgery-specific data has the potential to generally enhance the performance of surgical image analysis methods simply by providing stronger backbones. Here we present InnerLogic-Surg, an open family of surgical vision encoders (21M--300M parameters) obtained by continually pretraining a transformer-based image encoder on millions of surgical images curated from 11,965 internet-sourced surgical videos spanning ~2,900 hours and more than fifteen procedure types. Our training recipe inherits DINOv3's pretraining stage to preserve representation ability after surgical adaptation, and additionally applies a learned feature-upsampling module for high-resolution dense prediction at low token cost. Across a benchmark coveri

---

### [110] EnergyBench: a live, gate-aligned benchmark of day-ahead forecasts for European power markets

**链接**: https://arxiv.org/abs/2611.07784
**作者**: Evgenii Genov, Ander Martinez Alonso, Christoph Bergmeir
**来源**: cs.LG cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Energy forecasting models are usually compared on backtests and fixed public datasets. Backtests can use data that did not yet exist when the forecast would have been made, and a fixed test set, reused across studies and possibly contained in the pretraining data of foundation models, invites overfitting to the benchmark. EnergyBench evaluates every entry live instead. Each day at 11:30 CET/CEST, thirty minutes before the day-ahead (SDAC) gate closes, every model forecasts the next day's price, wind and solar generation and load on the 15-minute grid for six bidding zones (BE, NL, FR, DE-LU, DK1, DK2). Unlike existing live benchmarks, EnergyBench runs the models itself, on one information set that it freezes at the cut-off and publishes, including three numerical weather prediction models, so that foundation models can be compared with and without the same weather covariates under the actual market deadline. Errors are pooled per series against a seasonal-naive baseline, and models are

---

### [111] Big Models, Small Gains: Frozen Forecasters as Classifiers on MONSTER

**链接**: https://arxiv.org/abs/2611.06988
**作者**: Rishit Jain, Rishit Kar, Chetashri Bhadane, Nilesh Patil
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Forecasting foundation models are increasingly used as frozen feature extractors for time series classification, but it remains unclear whether their pretrained representations offer an advantage over strong classifiers that do not require pretraining. This raises an important question: do these representations provide useful information beyond what the model architecture alone can capture, particularly when labelled data are scarce? We present a controlled benchmarking of two forecasting models, Reverso and Chronos-Bolt, on six large datasets from the MONSTER benchmark, using 1%, 10%, and 100% of the available training labels. We compare their frozen representations against four established time series classification methods and random-weight versions of the same forecasting models. Our results show that pretraining improves classification accuracy over random-weight counterparts on five of the six datasets, with gains of up to 23 percentage points. However, the frozen representations

---

### [112] BrainPFN: Amortized Brain-Behaviour Prediction via Prior-Data Fitted Networks

**链接**: https://arxiv.org/abs/2611.06934
**作者**: Carlo Alberto Barbano (MIND), Demian Wassermann (MIND)
**来源**: q-bio.NC cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The standard approach to predicting behavioral phenotypes from functional MRI is represented by Kernel Ridge Regression (KRR) applied on functional connectivity (FC) matrices. However, this approach is limited: separate models must be fit and tuned for every score and cohort, they do not transfer across datasets, and accuracy degrades sharply when only a handful of subjects are available, as is typical of clinical or cognitive studies. Despite an increasing interest in developing brain foundation models, none has consistently outperformed KRR on behaviour prediction; most reported gains come from easier targets such as age, sex, or diagnosis rather than continuous behavioural scores. We introduce BrainPFN, a Prior Data Fitted Network for brain behaviour regression. BrainPFN is meta-trained on a domain-specific prior built from ~7k real FC matrices, from which we sample one billion synthetic training samples. At inference, a labelled context is simply passed through the network in a sin

---

### [113] Pediatric ECG foundation model via adult-to-pediatric fine-tuning: downstream tasks and clinical evaluation

**链接**: https://arxiv.org/abs/2611.07717
**作者**: Yu Cao, Haiyan Xu, Xiaohan Li, Jian Yang, Yuqing Feng, Wei Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pediatric electrocardiogram (ECG) interpretation is complicated by age-dependent electrophysiological changes that limit direct transfer of adult AI models. We asked whether an adult ECG foundation model could be adapted to pediatric ECGs. Using 339,563 12-lead ECGs from 238,189 children, we compared direct application, pediatric fine-tuning, and training from scratch under an identical architecture. Direct transfer was poor (mean AUC 0.8256). Fine-tuning reached 0.9695, above de novo training (0.9661), and attained 0.9079 using only 1% of training data. On 10,999 external ECGs, fine-tuning achieved a mean AUC of 0.9385 across 30 labels. It generalized to age regression (MAE 1.12 years) and congenital heart disease classification (AUC 0.9562). Across 17 clinicians and 100 cases, diagnostic accuracy rose from 56.8% to 65.4% (p < 0.001) and did not decline when AI erred. Adult ECG foundation models require pediatric adaptation; fine-tuning offers a data-efficient route to scalable pediat

---
