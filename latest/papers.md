# 📑 论文索引 - 2026-10-09

共 212 篇论文

---

### [1] Learning Situation-Conditioned Thinking Policies for Long-Term LLM Agents

**链接**: https://arxiv.org/abs/2610.09590
**作者**: Hong Su
**来源**: cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running autonomous agents must reuse accumulated reasoning experience without allowing explicit historical memory and LLM context to grow indefinitely. However, existing memory mechanisms mainly retrieve, summarize, or compress past content and do not directly learn when particular kinds of thinking should be activated or discover new thinking knowledge from temporally dispersed experiences. This paper proposes a situation-conditioned thinking memory framework that transforms historical reasoning experience into a lightweight policy for predicting what should be thought about in the current situation, while leaving detailed reasoning to a large language model. Situations may represent temporal or spatiotemporal evolution rather than only current states. Temporary experiences are also periodically analyzed across multiple independent episodes to identify repeated long-range regularities, which are consolidated into new thinking knowledge and further internalized by the lightweight 

---

### [2] COPC: Coupled Off-Policy Correction for Asynchronous LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.09597
**作者**: Zicheng Hu, Zhijian Zhou, Xuan Zhang, Yuchen Liu, Cheng Chen, Yuan Li 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous RL accelerates large language model post-training by decoupling rollout generation from optimization, but trains on stale trajectories. Existing methods primarily correct token-level policy mismatch through importance-ratio control in the actor objective. We show that this \emph{policy-side correction} alone is insufficient: advantage estimates also inherit mismatch from behavior-policy continuations, which we term \emph{advantage staleness}. We derive exact bias and variance decompositions for a general two-channel actor update, revealing nonseparable coupling between policy-weight and advantage-estimation errors: their interaction induces multiplicative bias terms, while squared policy weights amplify advantage uncertainty in gradient variance. This motivates the hypothesis that policy- and advantage-side correction should be coordinated. We introduce Coupled Off-Policy Correction (COPC), an actor--critic method combining token-level ratio masking with two-sided clipped-

---

### [3] Beyond LLM-GA: Secure Fluid Antenna Systems with ReEvo-Designed Memetic Algorithm

**链接**: https://arxiv.org/abs/2610.10235
**作者**: Hanyong Xu, Zhaolai Dang, and Tong Zhang
**来源**: cs.IT cs.AI math.IT
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fluid antenna systems (FASs) offer significant spatial flexibility, yet securing them against eavesdropping is critical for practical FAS deployment in military, satellite, and internet-of-things networks. Although large language model (LLM)-assisted genetic algorithms (LLM-GAs) can address this secure FAS port selection problem, whether further algorithmic improvement is possible warrants deeper investigation. To this end, we propose a memetic algorithm based on reflective evolution (ReEvo). Unlike the state-of-the-art LLM-GAs, which design only crossover or mutation operators with an LLM, our algorithm leverages an LLM to evolve dedicated crossover, mutation, and local-search operators offline. These operators are then embedded into a memetic search framework, thereby obviating any online LLM queries during execution. Simulation results at equal generation counts demonstrate that our proposed algorithm achieves a higher secure sum-rate than the conventional GA and the state-of-the-ar

---

### [4] Successive Training Stages and Large Language Model Persuasion: Effects of Misalignment, Supervised Fine-Tuning, and Preference Optimization

**链接**: https://arxiv.org/abs/2610.09964
**作者**: Antony Dalmiere (LAAS-TRUST), Pascal Marchand, Guillaume Auriol (LAAS-TRUST, INSA Toulouse), Vincent Nicomette (LAAS-TSF, LAAS)
**来源**: cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can be tuned to influence human attitudes, yet the respective contributions of successive post-training stages remain un-clear. This study examines how three successive training stages affect LLM persuasiveness: (1) misalignment through supervised fine-tuning (SFT) on conspiracy data, (2) additional persuasive SFT on argumentative data, and (3) Identity Preference Optimization (IPO), a preference-optimization method. A total of 835 participants recruited on Prolific were randomly assigned to five between-subject conditions (neutral text, conspiracy-trained model, persuasion-trained model, preference-optimized model, and GPT-4) and were exposed to texts on 10 divisive political issues, personalized from their individual profiles in all model conditions. Attitude change was measured as the difference between pre- and post-exposure positions on continuous Likert scales and analyzed with an analysis of covariance (ANCOVA). A significant condition x baseline-att

---

### [5] LLM-Assisted Generation of Transparent, Open-Source Multiphysics Models of Electrochemical Devices

**链接**: https://arxiv.org/abs/2610.10320
**作者**: Sebastian Castro, Maya F. Schuchert, Spencer A. McCluskey, Eric W. Lees, Justin C. Bui
**来源**: physics.chem-ph cs.AI physics.comp-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiphysics continuum models are powerful tools for studying electrochemical devices, enabling in silico reactor design and resolution of local pH, potential, and concentration fields that govern device performance but are difficult to measure experimentally. However, constructing such models requires substantial numerical expertise or reliance on proprietary software. Here, we show that frontier large language model agents can remove this implementation burden while keeping the underlying physics under researcher control. Using one-dimensional electrochemical CO2 reduction to CO in a porous gas diffusion electrode as a test case, we develop a machine-readable, human-specified modeling harness containing governing equations, parameters, numerical methods, logical build stages, and human-verifiable checkpoints. From this specification, the agent reproducibly constructs complete multiphysics models in open-source Julia. Independently built models, including fully autonomous agent-built 

---

### [6] Training Advisors for LLM Agents from Task Outcomes

**链接**: https://arxiv.org/abs/2610.09858
**作者**: Sergei Polezhaev, Barys Liskavets, Ori Press, Alexander Golubev
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents tackle multi-step tasks by interleaving reasoning and tool calls with observations from the environment. Prior work has shown that natural-language feedback can help these agents revise their decisions during task execution. We introduce Caddie, a method for training critics to provide natural-language analysis and advice as agents work through a task. Unlike approaches that rely on step-level labels or reference critiques, Caddie learns from whether the agent ultimately succeeds after receiving the critic's feedback. We optimize the critic through reinforcement learning while keeping the base model frozen. Trained on multi-hop question answering with a single base model, our Qwen3-4B critic improves success rates across four base models of different scales and architectures, including three not used during critic training. On the MuSiQue benchmark, the trained critic improves Qwen3-4B's success rate by more than 25 percentage points, surpassing the performa

---

### [7] Re-purposing Multimodal Large Language Models for Audio-Text Retrieval

**链接**: https://scholar.google.com/scholar_url?url=https://robots.ox.ac.uk/~vgg/publications/2026/Xu26/xu26.pdf&hl=zh-CN&sa=X&d=1769803274945625591&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVEgT78hyyr8reYBBcC8c_18&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=8&folt=kw-top
**作者**: JXCTD Horak, W Xie, A Zisserman
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Driven by this insight, we propose a unified Multimodal Large Language Model ( MLLM )-… This hierarchical supervision is essential for model training, as it equips the MLLM with the … audio and text features by prompting the MLLM to generate a compact

---

### [8] TiTok: Audio-Visual LLM for Multi-Segment Temporal Grounding

**链接**: https://arxiv.org/abs/2610.09408
**作者**: Eunji Shin, Dahyun Choi, Seungyeon Jo, Yejin Hong, Jiyoung Lee
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-visual multi-segment grounding (AV-MSG) in untrimmed videos, reasoning over audio-visual evidence and predicting multiple segments for a query, is a fundamental problem but remains challenging. Visual-only models overlook complementary acoustic cues, while audio-visual models often fail to calibrate the number of events - a phenomenon we refer to as count miscalibration. We present TiTok, an audio-visual large language model (AV-LLM) that localizes an arbitrary number of temporal event segments for each query. For precise boundary prediction, we introduce the Time Token Interleaving (TTI) method, which explicitly injects special time tokens into the audio-visual stream to align input-side temporal perception with output-side temporal prediction. We further propose decoupled, multi-segment-oriented rewards for reinforcement learning, consisting of global, local, count, precision, and format rewards, optimized with Group reward-Decoupled Normalization Policy Optimization (GDPO). To

---

### [9] Are LLM watermarks reliable in practice? A systematic review of evidence, robustness, threat models, and deployment assumptions

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1574013726001826&hl=zh-CN&sa=X&d=14891321892172096612&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVGkUBfGuHatCDTVtbVOCqE1&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: MR Islam, MP Uddin, Y Xiang - Computer Science Review, 2027
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Large language model ( LLM ) watermarking is a prominent approach for identifying machine-generated text, supporting provenance, protecting intellectual property, and enabling accountability in generative-AI ecosystems. Proposed mechanisms

---

### [10] Do smart contract auditing results transfer across datasets? a two-benchmark empirical study of static and llm -based security tools

**链接**: https://scholar.google.com/scholar_url?url=https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ESEM.2026.45&hl=zh-CN&sa=X&d=7698807562515132636&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVGWR9HKFUTGExPVhq1B3eN7&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: S Khalid, J Tuckett, C Brown - 20th International Symposium on Empirical Software …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> In contrast to prior work, our study evaluates deterministic and LLM -based smart contract auditing tools under a unified category-level … LLM -based Tools. We include two large language model ( LLM )–based auditing tools that represent

---

### [11] Reproducible LLM Inference Benchmarking: A Sequential Isolation Protocol for Regression Testing

**链接**: https://arxiv.org/abs/2610.09778
**作者**: Arnold Olympio, Juan Manuel Servera Bondroit, Wael Abdelmalek, Guang Lu, Jo\~ao Carvalho
**来源**: cs.PF cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducible benchmarking of Large Language Model (LLM) inference is challenging because repeated measurements can vary with execution and system state. We present the Sequential Isolation Methodology, a controlled benchmarking and regression-testing protocol designed to reduce between-run measurement variance while deliberately varying workload concurrency. We evaluate three representative open-source LLMs on an NVIDIA A100 80GB GPU using vLLM 0.9.1 across six context sizes and eight concurrency levels, with five repetitions per configuration. The final protocol reduces average coefficient of variation (CV) from 15.2% in the least controlled methodology stage to 2.2% under the final protocol; using CV computed across the five repetition-level median (P50) TTFT values per configuration, 113 of 144 configurations (78.5%) achieve CV below 3%. The measurements also show a marked latency transition between 200 and 500 concurrent users on the tested stack and descriptive differences in P99 

---

### [12] GraphOPD: Graph-Augmented On-Policy Distillation for LLM Agents

**链接**: https://arxiv.org/abs/2610.08959
**作者**: Bohan Lin, Liyi Chen, Zhuoning Guo, Muyang Li, Qimeng Wang, Yan Gao 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation post-trains large language model agents by supplying dense, step-level guidance from a teacher policy when the reinforcement-learning reward is sparse and arrives only once per trajectory. Existing instantiations allocate this guidance by the size of the teacher-student divergence at each step, on the single-turn intuition that a large disagreement marks a mistake worth correcting. Once decisions chain over many turns, that rule misfires, since an early drift enters every later context both policies condition on, leaving the teacher consistent with the drifted trajectory instead of flagging its cause, while interchangeable steps register large but outcome-irrelevant divergences. We demonstrate this on an agentic benchmark, where distilling the highest-divergence steps brings no consistent benefit over random selection. To this end, we introduce GraphOPD, the first method to bring graph-based structural augmentation into on-policy distillation for agent capabiliti

---

### [13] Bridging Natural Language and Interactive What-If Interfaces via LLM-Generated Declarative Specifications

**链接**: https://arxiv.org/abs/2604.07652
**作者**: Sneha Gathani, Sirui Zeng, Diya Patel, Ryan Rossi, Dan Marshall, Cagatay Demiralp 等 (8 人)
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Large Language Model Orchestration under Heterogeneous Preferences via Explicit Persona Inference

**链接**: https://arxiv.org/abs/2610.07587
**作者**: Shuqing Shi, Ziyan Wang, Milind Tambe, Yali Du
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] "Is This Really a Human Peer Supporter?": Misalignments Between Peer Supporters and Experts in LLM-Supported Interactions

**链接**: https://arxiv.org/abs/2506.09354
**作者**: Kellie Yu Hui Sim, Roy Ka-Wei Lee, Kenny Tsu Wei Choo
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Marrying Pricing and Advertising with LLMs

**链接**: https://arxiv.org/abs/2610.09985
**作者**: Alessandro Barro, Francesco Bacchiocchi, Francesco Emanuele Stradi, Alberto Marchesi
**来源**: cs.GT cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study a sequential pricing problem in which a seller jointly posts a price and an advertisement generated by a large language model (LLM). The seller aims to maximize revenue under an unknown product demand that depends on both decisions, while observing only whether each offer leads to a purchase. We propose an online actor-critic algorithm that combines low-rank adaptation (LoRA) of a pretrained LLM with a demand model fitted to available data. At each round, the actor generates an advertisement, and the critic estimates purchase probabilities to guide price selection. Then, the resulting feedback is used to update both the actor and the critic, with the critic's revenue estimates providing a baseline for policy gradient updates of the actor. To evaluate our approach, we develop an evaluation framework with three synthetic demand models and a demand simulator built from real-world marketplace data. Finally, we compare our algorithm with benchmarks that do not jointly optimize pric

---

### [17] AdaGuard: Enhancing Safety and Policy Compliance with Reasoning-Enabled LLM-As-A-Judge Guardrails

**链接**: https://arxiv.org/abs/2610.08923
**作者**: Melissa Kazemi Rad, Sihui Dai, Isha Slavin, Kushal Chawla, Mann Patel, Jian Ni 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise generative AI applications require robust safety mechanisms that can accommodate diverse risk postures, evolving policies, and varying latency constraints. Current guardrail solutions often suffer from rigidity, relying on fixed policy sets and offering limited transparency or reasoning flexibility. We present Adaguard, an adaptive LLM-as-a-Judge framework designed to address these challenges through dynamic policy enforcement and adaptive reasoning-budget allocation. Built using supervised fine-tuning (SFT) and reinforcement learning (GRPO), AdaGuard generalizes to user-defined safety and compliance policies at runtime without requiring frequent model updates. A core innovation of our approach is the ability to dynamically infer the complexity of input-policy pairs, allowing the model to switch between high-speed black-box inference and explainable, reasoning-enabled moderation. This flexibility enables developers to balance stringent latency requirements with the need for 

---

### [18] Auditing Privacy Risks in LLM-Enhanced Graph Neural Networks

**链接**: https://arxiv.org/abs/2608.25727
**作者**: Longzhu He, Zelang Wen, Chaozhuo Li, Sen Su
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] Hidden in the Request: Explaining Unethical LLM Compliance through Token Relevance

**链接**: https://arxiv.org/abs/2608.23264
**作者**: Or Biton, Tomer Krichli, Itai Allouche, Joseph Keshet
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Geometry-Aware Online Scheduling for LLM Serving: From Theoretical Bound to System Practice

**链接**: https://arxiv.org/abs/2606.22327
**作者**: Li Kong, Qi Qi, Yinyu Ye, Zijie Zhou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] The Winner's Curse in LLM Self-Improvement Loops: Selection Noise, Lock-in, and Acceptance Rules

**链接**: https://arxiv.org/abs/2610.09239
**作者**: Litao Hu, Yutong Tang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM systems propose changes to themselves and keep those that score better on a small evaluation set. We treat this keep-if-better step as selection under measurement noise, model the correlated errors of the candidates in a single decision, and study empirically what happens when the evaluation set is reused. In runs where Qwen models rewrite their own instructions and every candidate is also scored on 600 held-out items, most proposals after the first are harmful, and the model gives the size of the winner's curse of a generation's best candidate. With a prior from a separate pilot, it matches the average overstatement of first-generation commits in native loops, though not setting by setting. In a pre-registered study, the final selection-set score of greedy loops exceeded held-out accuracy by 13 to 20 points with 16 selection items and by 1 to 5 points with 256. Held-out gains grew with the selection set on TREC but not on GSM8K, and the tested acceptance rules did n

---

### [22] From Prompts to Trees: Effective LLM-Guided Tree Generation for Few-Shot Tabular Classification

**链接**: https://arxiv.org/abs/2610.10227
**作者**: Yue Qiu, Zekang Du, Yiqun Diao, Bingsheng He, Qinbin Li
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) possess rich world knowledge and impressive generalization capabilities, their direct application to tabular data classification is hindered by high inference costs and limited interpretability. In contrast, decision trees are fast and transparent but often underperform in low-data regimes. In this work, we propose a novel framework that bridges these paradigms by distilling LLM knowledge into interpretable decision trees under a few-shot learning setting. Instead of directly prompting the LLM to generate full trees, which is often unstable and inefficient, we develop a three-stage paradigm that prompts the LLM to generate rules and organize the rules into a tree. Experiments on multiple real-world tabular datasets demonstrate that our method achieves superior accuracy and interpretability with significantly lower prompting overhead compared to existing baselines.

---

### [23] The Implications of Linguistic Illegibility for LLM Security

**链接**: https://arxiv.org/abs/2609.02852
**作者**: James Mickens
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] MIRROR: From Imitation to Internalization in LLM Personalization

**链接**: https://arxiv.org/abs/2610.09795
**作者**: Huayi Lai, Jicheng Yang, Min Yi, Chong Meng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The demand for personalized LLMs is shifting from style imitation toward content quality. We investigate whether self-distillation can bridge this gap in existing fine-tuning paradigm. To address this limitation, we introduce MIRROR(Meta- personalization by Internalizing Reference-Revealed On-policy Reflections), a novel self-distillation framework that shifts LLM personalization from imitation toward preference internalization. First, we replace reference-token imitation with reference-revealed on-policy self-distillation, aligning the model's next-token distributions along its own generation trajectories with those of its reference-conditioned self, thereby internalizing user preferences rather than reproducing reference wording.Second, we introduce MIRROR-F, a focal plug-in that augments on-policy distributional alignment with selective supervision over informative reference tokens, thereby strengthening content generation while preserving user-specific expression. Across three pers

---

### [25] The Trace Is the State: Exact Credit Assignment for LLM Agent Teams

**链接**: https://arxiv.org/abs/2603.06859
**作者**: Yanjun Chen, Yirong Sun, Hanlin Wang, Jinghan Wang, Xinming Zhang, Xiaoyu Shen 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Progressive Disclosure for LLM-Maintained Wiki Knowledge Bases: a Preregistered Ablation

**链接**: https://arxiv.org/abs/2607.04576
**作者**: Theodore O. Cochran
**来源**: cs.CL cs.CY cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Adaptive Workflow Intelligence: A Cognitive Architecture for Context-Driven Enterprise Automation

**链接**: https://arxiv.org/abs/2610.08793
**作者**: Sreedevi Pandiyath Viswambaran
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise systems increasingly rely on automated workflows, yet many AI-driven solutions remain brittle under non-stationary conditions, evolving policies, and delayed operational feedback. While reinforcement learning and large language model (LLM) agents offer partial adaptability, they do not by themselves provide persistent reflection mechanisms or straightforward integration with policy-constrained enterprise operations. This paper introduces Adaptive Workflow Intelligence (AWI), a cognitive architecture for context-driven enterprise agents organized around a four-layer Perception-Cognition-Action-Reflection (PCAR) loop. AWI treats reflection as a mechanism for continuous policy refinement and combines hybrid reasoning with reflective memory and feedback-driven adaptation to support decision making under environmental drift and operational constraints. We evaluate AWI in a simulated enterprise decision workflow characterized by delayed outcomes and a controlled regime shift. In a

---

### [28] Activation-Aware Weight Tensorization: A Calibration-Time Preconditioner for Tensor-Network LLM Compression

**链接**: https://arxiv.org/abs/2610.10085
**作者**: Alessandro Beatini, Marco Maronese, Emanuele Rodol\`a
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training tensor-network compression replaces Transformer linear layers with Tensor Train (TT) or Tree Tensor Network (TTN) operators, but standard decompositions minimize weight-space Frobenius error rather than functional error under the layer's activation distribution. We propose Activation-aware Weight Tensorization (AWT), a training-free calibration wrapper that preconditions each weight matrix with a diagonal activation-derived scale before an unchanged TT/TTN solver and deploys the result with only an input-side elementwise rescaling. Across Llama 3.1 8B, Ministral 8B, and Qwen2.5 7B, AWT consistently improves vanilla TT/TTN tensorization at 2-6 times compression: under single-operator replacement, AWT closes 12-35% of the WikiText perplexity gap to the dense baseline across the three model families and 2-6 times compression settings; while under multi-operator Llama suffix replacement it closes 27-60% across attention-group and all-seven-matrix settings. The gains also tran

---

### [29] Clean: Second-order LLM Training at Linear Memory Cost via Nystr\"om Sketching

**链接**: https://arxiv.org/abs/2610.04204
**作者**: Beheshteh T. Rakhshan, Sahar Rajabi, Maziar Sargordi Shikai Fang, Guillaume Rabusseau, Sirisha Rambhatla
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Rubric Spans are Label Representations: Joint LLM Encoding for Short Answer Scoring

**链接**: https://arxiv.org/abs/2610.09660
**作者**: Zhifan Sun, Sebastian Gombert, Fabian Zehner, Leon Camus, Longwei Cong, Hendrik Drachsler
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Short Answer Scoring (ASAS) requires models that can score student responses against question-specific criteria while remaining efficient and transferable across rubric sets. We propose RUSPAN, a rubric-conditioned ASAS framework that treats rubric descriptions as semantic label representations. RUSPAN serialises the question context, student answer, and all candidate rubric levels into a single sequence, then scores the levels listwise from the rubric-span and whole-sequence representations produced in a single LM pass. We further introduce RUSPAN-RIM, in which a Rubric-Independent Mask prevents rubric spans from attending to one another, making rubric representations depend only on the answer and question context and preventing overfitting to rubric patterns during training for zero-shot transfer. On six ASAS benchmarks spanning English, German, and Portuguese, RUSPAN improves mono-benchmark scoring over discriminative and generative baselines, while RIM with position reind

---

### [31] Activation-Informed Pareto-Guided Low-Rank Compression for Efficient LLM/VLM

**链接**: https://arxiv.org/abs/2510.05544
**作者**: Ryan Solgi, Parsa Madinei, Jiayi Tian, Rupak Swaminathan, Jing Liu, Nathan Susanj 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Correct Answers, Unsupported Findings: Evidence Binding in Forensic Reconstruction of LLM Agent Logs

**链接**: https://arxiv.org/abs/2610.09581
**作者**: Taehyeon Yun, Dongho Kim, Geonwoo Kim, Juyoung Seo, Minseok Hur, Moohong Min
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Forensic reconstruction of LLM-agent actions requires not only recovering the correct value, but establishing which preserved record supports that finding. Tool logs, generated explanations, and local citation identifiers capture different parts of this evidence, yet a citation identifier does not establish a source unless its binding to a record is preserved. We audit this distinction using 64 mechanically checkable cases from saved AgentDojo Banking executions. Two LLM readers reconstruct source relationships under controlled variations in visible evidence and identifier-to-record bindings. We separately evaluate complete-record agreement, evidence-grounded findings, justified abstention, and unsupported assertions. With original identifiers and no binding table, Sonnet recovered every literal source location but made unsupported citation-source assertions in 26 of 28 cases requiring the missing relation; 22 nevertheless matched the complete reference. Adding explicit bindings improv

---

### [33] Right Number, Wrong State? Measuring Cross-Jurisdiction Substitution in LLM Recall of State Policy

**链接**: https://arxiv.org/abs/2610.09458
**作者**: Jiayu Feng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM answers a state-specific policy question wrongly, it may be hallucinating, or it may be returning a real value that holds in another state. We test this with a minimal-set design: the question wording is fixed and only the jurisdiction varies, across the 50 U.S. states and the District of Columbia (51 jurisdictions) and three exactly defined Medicaid income-eligibility quantities. Gold values come from an official data book and agree with an independent source in 101 of 102 checked cells. Under a pre-registered protocol, Claude Sonnet 5.5 and GPT-5.6 Sol reproducibly give another state's current value, identical across two independent repeats, for 10 and 25 of 153 items. Attribution is fragile, however. Crediting any wrong answer that equals another state's value yields 3-5x more reproducible substitutions than checking every number in the asked state's own records, because many apparent cross-state answers are the asked state's own values under another convention or from a

---

### [34] Multi-Label Topic Assignment via LLM Distillation: A Comparative Analysis of Generative vs. Discriminative Student Models

**链接**: https://arxiv.org/abs/2610.09063
**作者**: Sourabh Kasliwal, Shubhranshu Singh
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-label topic assignment for user-generated content (UGC) -- including product reviews and buyer-seller conversations -- poses unique scalability challenges in large-scale e-commerce due to informal language, extreme label sparsity, and rapidly evolving taxonomies. While utilizing Large Language Models (LLMs) as labeling oracles to distill ground-truth data has emerged as an industry standard to bypass prohibitive manual annotation costs, determining the optimal, low-latency architecture for the resulting student models remains an open challenge. To address this, we conduct a comprehensive evaluation across Small Language Model (SLM) parameter scales (1B, 4B, and 8B) and architectural paradigms (causal generative versus bidirectional discriminative). Comparing generative text-to-label classifiers against discriminative baselines (DeBERTa-V3 and ModernBERT), our analysis reveals a crucial data-dependent trade-off: while discriminative models outperform ultra-lightweight generative m

---

### [35] PathTrace: A Trace-Based Evidence Harness for Auditing Whole-Slide Pathology Agents

**链接**: https://scholar.google.com/scholar_url?url=https://papers.miccai.org/miccai-2026-sat/paper/COMPAYL_034.pdf&hl=zh-CN&sa=X&d=9880194302623411583&ei=Z3fHapfLEde46rQPmoOZiAE&scisig=ACTRDVHsRd87tkCCY9XIVVZkn4Li&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=4&folt=kw-top
**作者**: CH Lim
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language model (LLM)-based agents have shown potential for whole-slide image (WSI) analysis by approximating pathologists’ … by the model , and flagging missed tumour regions, off-tumour evidence, and trace-inconsistent citations. We

---

### [36] Pointwise and Pairwise LLM -as-a-Reranker for Job-Title to ESCO Skill Retrieval over GIST-Fine-Tuned JobBERT

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4283/paper482.pdf&hl=zh-CN&sa=X&d=7853224386200898108&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVE4d-dzi3X-sd8u1ak8IBcU&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: Y Liu, Z Niu, C Li, Z Fan - CLEF (Working Notes), 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> For each ordered pair (𝑐𝑖,𝑐𝑗) we present the LLM with the job title and two candidate skills … on the pairwise output, does not help: a deterministic LLM reproduces the same comparisons. … High recall at this stage is a prerequisite for

---

### [37] Apollo Restore: A Foundation LLM for Historical Greek Optimized for Fill-in-the-Middle Restoration of Ancient Greek Texts

**链接**: https://arxiv.org/abs/2609.22455
**作者**: Hope McGovern, Anna Dolganov, Samuel Belkadi, Guillaume Kunsch, Dimitris Vlitas, and David A. Smith
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] EASE: Entropy-Adaptive Distribution Shaping for Evading AI-generated Text Detectors

**链接**: https://arxiv.org/abs/2610.09976
**作者**: Jicheng Zhou, Kahim Wong, Jialong Wang, Jiantao Zhou
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-generated text (AIGT) detection can be sensitive to the decoding choices of the source large language model (LLM). We observe that perturbing next-token logits or adjusting sampling temperature can reduce detection performance, providing a clear signal of detector vulnerability to decoding-time distribution changes. Building on this observation, we propose EASE (Entropy-Adaptive Distribution Shaping for Evasion), a training-free and detector-agnostic framework for evading AIGT detectors. EASE computes predictive entropy directly from the source LLM's next-token distribution and uses it to adapt both logit perturbation and sampling temperature, without detector feedback or model fine-tuning. Experiments across three source LLMs and multiple detectors demonstrate consistent reductions in detection performance, with negligible degradation in text quality and negligible inference overhead.

---

### [39] Multi-LLM Collaborative Alignment via Stackelberg Games

**链接**: https://arxiv.org/abs/2609.39076
**作者**: Christina Hahn, Shangbin Feng, Dean Light, Swastik Roy, Hila Gonen, Yulia Tsvetkov
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] The Shadow Price of Intelligence: Quality Degradation in LLM Inference as a Supply Chain Problem

**链接**: https://arxiv.org/abs/2608.23986
**作者**: Elioth Sanabria
**来源**: math.OC cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Reliability of LLM Judges for Evaluating Entity Alignment

**链接**: https://arxiv.org/abs/2610.09554
**作者**: Vaibhava Lakshmi Ravideshik, Mayank Kejriwal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Entity Alignment (EA) identifies equivalent entities across knowledge graphs and is critical for knowledge base integration and ontology merging. Evaluating EA systems at scale requires expensive expert annotation, making systematic assessment across diverse domains practically infeasible. LLM-as-judge evaluation offers a potentially scalable alternative, yet its reliability for structured prediction tasks like EA remains unstudied. We present the first systematic benchmarking study across three frontier models, three datasets, and four EA systems, using perturbation bias diagnostics, meta-evaluation across all dataset-judge-prompt combinations, and counterfactual label-flip tests. We identify anchor bias, a failure mode in which judges invert discrimination when the system's decision label is visible. Label exposure causally collapses judge discrimination (J-ROC-AUC 0.12-0.87), while a label-free protocol recovers near-ceiling capability on distinctive-name datasets (0.93-1.00) and si

---

### [42] The Dichotomy Between Pattern Recognition and Step-by-Step Reasoning

**链接**: https://arxiv.org/abs/2610.09186
**作者**: Amrut Nadgir and Pratik Chaudhari and Vijay Balasubramanian
**来源**: cs.LG cond-mat.dis-nn
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We argue that pattern recognition and step-by-step reasoning are two ends of a spectrum. A large language model (LLM) learns to reason step-by-step when data is structured such that the next token depends on a small amount of preceding context. Inference in LLMs resembles pattern recognition when the next token depends on a large amount of preceding context. If the next token depends on only the $c$ most recent tokens, reasoning traces are paths on a De Bruijn graph whose nodes are $c$-length contexts and edges are next-token transitions between contexts. The set of reasoning traces of a task forms a directed acyclic subgraph of the De Bruijn graph. An LLM that has learned all edges of this subgraph can compose them to solve longer, unseen tasks, i.e., it reasons step-by-step. We prove that the number of edges is vanishingly small compared to the number of reasoning traces. Empirically, the number of training samples a transformer needs is a power law in the number of edges, so learnin

---

### [43] Arctic Questions, Missing Answers: A Dataset and Benchmark for LLM Abstention in Arctic Science

**链接**: https://arxiv.org/abs/2610.09446
**作者**: Benjamin Wilcox, Dawei Gao, Pradeeban Kathiravelu, Douglas Causey, Kewei Sha, Yunhe Feng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) should abstain from scientific multiple-choice questions when no option is valid, but frequent abstention alone does not demonstrate sensitivity to answer availability. We introduce ArcticQA, a dataset of 194 questions derived from primary Arctic research, with automated checks of answer support and distractor contradiction against source evidence. We further develop ArcticAbstain, a paired benchmark comparing answer-present and answer-absent conditions, with the correct answer replaced by a distractor in the latter and an explicit abstention option in both. We evaluate eight models from the Gemini, Claude, and ChatGPT families at high reasoning effort, with three trials per condition, yielding 9,312 recorded responses. Answer-present abstention rates range from 0.0% to 63.0%, whereas replacing the correct answer increases abstention by 5.05 percentage points on average. These findings highlight substantial baseline differences and the need to evaluate abst

---

### [44] Multi-Agent LLM Annotation and Scoring for Training Fine-Grained K-12 Writing-Feedback Models

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.aimecon-sessions.1.pdf&hl=zh-CN&sa=X&d=17903641739470410297&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVG0XXoWQMxMemmoMsKCzsGs&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: JO Barber, MP Hemenway, M Bellows, S Lottridge - Proceedings of the Artificial …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Fine-grained formative writing feedback needs dense, standards-aligned labels that human annotation cannot supply at scale. We describe a multi-agent LLM pipeline producing verified silver labels, and then train small deterministic transformer scorers

---

### [45] Insights Generator: Systematic Corpus-Level Trace Diagnostics for LLM Agents

**链接**: https://arxiv.org/abs/2605.21347
**作者**: Akshay Manglik, Vijay S. Kalmath, Jason Qin, Apaar Shanker, Kaustubh Deshpande, Yash Maurya 等 (9 人)
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] RLDISCOVER: LLM-driven co-evolution of reinforcement learning algorithms

**链接**: https://arxiv.org/abs/2610.09218
**作者**: Haoran Li, Zengle Ge, Xiaomin Yuan, Yui Lo, Songlin Zhou, Jiahua Ying 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-guided program evolution has enabled discoveries in mathematics and computational optimization, raising the prospect of reinforcement learning (RL) algorithms that self-evolve to improve how agents learn. However, realizing this prospect faces two obstacles. Joint search over coupled algorithmic components is difficult to scale: simultaneous changes can disrupt learning, while isolated changes overlook their dependencies. Evaluating candidate algorithms also requires costly training, with fitness remaining uncertain across random seeds. We introduce RLDiscover, a framework for the self-evolution of model-free deep RL algorithms. Progressive Co-Evolution advances from targeted component edits to joint evolution, while Progressive Probabilistic Evaluation balances search breadth and evaluation fidelity through staged training and repeated evaluation. Experiments across SAC, PPO, and DQN on four benchmark suites show substantial improvements in mean return, with per-family median gain

---

### [47] Goldsmith: Gold-Loss-Guided Definition Optimization with an Agentic Annotation Harness

**链接**: https://arxiv.org/abs/2610.09489
**作者**: Yihan Li, Hanyi Zhang, Xiaoxi Jiang, Man Guo
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many annotation projects begin before experts have a stable guideline or enough labels to train a task-specific model. We present Goldsmith, an agentic pipeline that turns a small gold set---expert-annotated calibration examples representing the intended task boundaries---into a reusable structured annotation definition. Goldsmith treats this definition as a trainable textual object. Candidate definitions are run on the same gold examples and scored with an executable structured loss, while the output schema, formatting, retrieval, repair, judging, and human review remain in an external harness. A large language model (LLM) editor converts the highest-loss failures into textual-gradient revisions, which are accepted only when the measured loss decreases. In prompt-optimization comparisons, Goldsmith improves over direct rewriting, OPRO, APE, and PromptBreeder under matched evaluation protocols. The resulting definition also improves downstream annotation when combined with retrieval, s

---

### [48] Epistemic Policy Divergence in Multi-Turn LLM Contamination: A Protocol-Gradient Investigation

**链接**: https://arxiv.org/abs/2609.35308
**作者**: Fahrell Giovanny, Geby Bayuningtyas, Sahrul Mukharom, and Hafiz Budi Firmansyah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Decoupling Logic from Persona: Structural Immunity of Edge LLM Agents to Context Pollution

**链接**: https://arxiv.org/abs/2610.09772
**作者**: Masaaki Nakatsu (AO, Inc. / OrbLabs AG), Reno Wang (AO, Inc.)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small language-model agents on edge devices must hold a persona and reason correctly at once, inside one context window that fills with conversational history and persona instructions. We study what happens to the logical part of such an agent when that history is long, misleading and persona-heavy (persona-logic interference), and present a Decoupling Architecture (AO-DA) that separates logical inference ("What") from persona expression ("How") into two inference paths on one INT4 base model with hot-swappable LoRA adapters. The logic path receives only the core turn and emits a verifiable structured state (Micro-State); the persona path renders it in character with the full history. In same-base-model ablations on an Apple M2 laptop (Llama-3.1-8B-Instruct and Gemma-3-4B-it, 4-bit; 480 runs over 4 pollution levels x 3 arms x 2 tasks x 2 personas x 5 seeds) we find: (i) the decoupled logic path is structurally invariant to pollution: its prompt stays at 180 (Llama) or 167 (Gemma) token

---

### [50] Sensitive-Topic Leakage Through LLM Routing Metadata: Measurement and Mitigation

**链接**: https://arxiv.org/abs/2610.09981
**作者**: Teng-Ruei Chen
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM routers pick a cheap or expensive model per request by its content, and many gateways and some cloud platforms can log that choice with content logging off. We measure this privacy channel beyond token counts, accounting for noisy labels and repeated prompts. We run pre-registered studies on 1.7 million real requests (WildChat-1M, LMSYS-Chat-1M) with two cost/quality routers and a domain router, survey eleven systems' logging, and test post-processing defenses. At matched length, the shift's direction depends on category and router. For RouteLLM at the 50% operating point, harassment and self-harm requests reach the strong model 19 points less often than comparable ones on prompts unseen in exploration, medical requests (exploratory: LLM labels failed their gate) 31 points less often on distinct prompts (both post hoc), and sexual requests 10 points more often (secondary); the other router's four are negative. Twenty RouteLLM decisions separate frequent medical askers with AUC 0.71

---

### [51] Learning to Accumulate Knowledge with Mutual Information

**链接**: https://arxiv.org/abs/2610.10042
**作者**: Yuyang Zhao, Lizi Liao, Leyang Shen, Xiaoyan Zhao, Yang Zhang, Fuli Feng 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can improve their performance by reusing knowledge distilled from past interactions. However, curating new experiences into a knowledge bank that becomes more useful as it grows remains challenging. Effective knowledge accumulation should limit redundant overlap among entries and ensure that new knowledge contributes beyond what the bank already provides. Yet training a curator with Group Relative Policy Optimization (GRPO) on standalone task success can reinforce general guidance even when it duplicates existing knowledge. Therefore, we propose Knowledge Weaver, a reinforcement learning framework that trains a language model to curate reusable knowledge from agent trajectories. We couple feedback inspired by token-wise mutual information (MI) with marginal success rewards to guide knowledge accumulation. Together, these signals encourage the curator to preserve distinct information from experience and produce entries that improve task success when add

---

### [52] CurveTQ: Rotation-Free Trellis Quantization of LLM Weights via Curvature-Weighted Search

**链接**: https://arxiv.org/abs/2610.09212
**作者**: Guanhua Ding, Zi Wang, Ruichao Li, Jack Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The best two-bit weight quantizers for large language models, such as QTIP and Proteus, rotate each weight matrix by a random orthogonal transform, which must be undone at every decoding step, then encode it with a trellis or lattice code under a Euclidean search; the layer Hessian enters only through error feedback between coding blocks. We show that this leaves part of the Hessian unused. Error feedback turns the loss into a weighted sum of per-coordinate rounding errors whose weights, the diagonal of the Hessian's LDL factorization, existing quantizers compute but never read. We put these weights into the Viterbi branch metric, so the search follows the curvature within each coding block. This also explains the rotation: it removes this within-block variation, so weighting in the native basis and rotating are substitutes. On three models the weighted native search matches a full-dimension randomized Hadamard to within about one point of downstream accuracy, and weighting after the r

---

### [53] From High Recall to High Utility: Dataset-Adaptive Post-Processing of LLM-Generated Customer Intents

**链接**: https://arxiv.org/abs/2610.09039
**作者**: Mahesh Viswanathan, Joan Rossello, Leticia Fernandes, Paul Mutawe
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can extract useful signals from heterogeneous enterprise data, but high-recall extraction often produces outputs that are duplicated, uneven in granularity, semantically overlapping, or too numerous for downstream systems and human reviewers to use effectively. We present a dataset-adaptive post-processing architecture developed for Customer Intent Extraction (CIE), where unstructured customer language is transformed into stable, traceable intent units. The approach separates recall-oriented extraction from utility-oriented reduction. Source-specific preprocessing first isolates evidence from multimodal plans, sparse operational records, and structured opportunity data. Candidate intents are then standardized and deduplicated, optionally enriched with metadata for embedding computation, represented in a shared semantic vector space, and grouped using a clustering strategy selected according to the candidate set's characteristics. Cluster-level keywords provide an 

---

### [54] Self-Indexing Attention for Compression-Compatible Sparse Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2609.13205
**作者**: Xu Yang, Jiapeng Zhang, Yuxin Chen, Feiqiang Sun, Chengguang Xu, Feng Jin 等 (7 人)
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] GRADE: Graph Representation of LLM Agent Dependency and Execution

**链接**: https://arxiv.org/abs/2606.22741
**作者**: Yue Zhao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] CM-DPO: Constraint-Margin Direct Preference Optimization for LLM Planning

**链接**: https://arxiv.org/abs/2610.09219
**作者**: Rabimba Karanjai, Qun Gu, Hemanth Hegadehalli Madhavarao, Wenhuan Sun, Xiaojiao Yu, Suryabhan Singh Hada 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct Preference Optimization (DPO) treats all constraint violations equally: a $1 budget overshoot and a $1,000 overshoot induce the same training signal. It is also susceptible to length and style bias when preference pairs come from different model families. We introduce Constraint-Margin DPO (CM-DPO), which replaces DPO's binary preference signal with a continuous margin derived from a deterministic symbolic verifier and scaled by violation severity. Hard and soft constraints are separated through a lexicographic objective, ensuring hard constraints are never traded off against preferences. To supply CM-DPO with bias-reduced training pairs, we generate preference data through procedurally generated constraint profiles (DCCG) and minimal-edit distillation from a reasoning teacher (RT-MED), within a framework we call SynPlan-R. On TravelPlanner, NaturalPlan, and out-of-distribution PlanBench, an 8B model fine-tuned with CM-DPO achieves 89.2% pass rate and 93.4% solve rate, matching 

---

### [57] Retrieve, Rerank, Survive: LLM -Listwise Pipelines for Job-Person and Job-Skill Matching at TalentCLEF 2026

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4283/paper479.pdf&hl=zh-CN&sa=X&d=3884909413001241256&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVFDW7oKD6r0y9M-IuTFFbgk&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: L Hemamou, R Dupont - CLEF (Working Notes), 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We describe team bipboopbipboop’s submissions to both shared tasks of TalentCLEF 2026. Task A (Contextualized Job–Person Matching) ranks candidate résumés by their relevance to a job offer, and Task B (Job–Skill Matching with Skill

---

### [58] APCD: Adaptive Path-Contrastive Decoding for Reliable Large Language Model Generation

**链接**: https://arxiv.org/abs/2605.09492
**作者**: Tianyu Zheng, Hong Wu, Jiaji Zhong
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Just for FUNS: LLM-Guided Spatio-Temporal Graph Node Generation for Forecasting Unobserved Node States

**链接**: https://arxiv.org/abs/2610.08818
**作者**: Shuhao Li, Weidong Yang, Changan Liu, Wei Zhuo, Yingbo Zhou, Fan Zhang 等 (7 人)
**来源**: cs.LG cs.AI cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatio-temporal forecasting is a cornerstone of logistics, urban planning, and intelligent transportation systems. However, constrained by deployment costs and maintenance resources, sensor networks often lack comprehensive spatial coverage, rendering Forecast Unobserved Node States (FUNS) a critical yet formidable challenge. Conventional models rely on historical observations and typically falter when encountering nodes without prior records. To address this, we redefine the problem as a conditional generation task on spatio-temporal graphs and propose GenST, a framework that introduces Large Language Models (LLMs) as a semantic bridge, leveraging a pre-trained LLM fine-tuned to extract rich semantic features from node descriptions, such as functional zones and road network structures, to compensate for missing spatio-temporal signals. Specifically, we design a two-stage generative architecture: a Spatio-Temporal VAE first compresses spatio-temporal dynamics into a latent space, follo

---

### [60] OOM-RL: Out-of-Money Reinforcement Learning Market-Driven Alignment for LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2604.11477
**作者**: Kun Liu, Liqun Chen
**来源**: cs.AI cs.SE q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] On KL-Regularized Policy Optimization

**链接**: https://arxiv.org/abs/2610.08963
**作者**: Yifan Zhang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous reinforcement learning (RL) for large language model (LLM) agents trains one policy on trajectories generated by another: rollouts come from stale checkpoints, and the inference engine's probabilities differ from the trainer's even at identical parameters. Standard remedies either clip importance ratios, which biases the update, or, as in GRPO, sample a group of responses per prompt, which is costly when episodes are long. We propose KL-Regularized Policy Optimization (KLPO), a framework that anchors the KL regularizer at the sampler. The regularized improvement step then has a closed-form Gibbs solution, and KLPO fits its log-ratio optimality condition by least squares on the sampler's own trajectories, so the sampler probability enters through a log-ratio and no importance weights are needed. Profiling out the regression intercept replaces the intractable log-partition function with the signal's sampler mean plus a sampler-to-trainer KL divergence. For token-level policy

---

### [62] TACO: Ternary Absolute-max Column-wise One-sparse Optimizer for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.02199
**作者**: Jichao Jiang, Cristian McGee, El Houcine Bergou, HanQin Cai, Aritra Dutta
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] Whose Memory Is It? Scope-Aware Commit Rules for Long-Term LLM Memory

**链接**: https://arxiv.org/abs/2610.09008
**作者**: Hongyu Gu, Xinchang Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory allows an LLM agent to carry experience across conversations, but it also turns a local reasoning mistake into a durable one. During deliberation, an agent may consider a plan, simulate a tool result, report another speaker's belief, and then reject all of them. If memory retains only the resulting sentences, those once-useful possibilities can later return as facts. The record is neither fabricated nor irrelevant; it has simply been detached from the context in which it was valid. We identify this missing context as \emph{discourse ownership}: the world, branch, or speaker that licenses a proposition. Our first finding is counterintuitive. Language models already carry a causally active signal for ownership, yet conventional memory interfaces discard it when they convert reasoning into records. We introduce CASK (Causally Anchored Scoping Keys), a commit rule that preserves this signal so that shared-world facts enter durable memory while provisional content remains 

---

### [64] CredLeakBench: Evaluating Credential Leakage and Recovery in LLM Agents

**链接**: https://arxiv.org/abs/2610.08871
**作者**: Rafid Ahmed, Joseph Fioresi, Mubarak Shah, Yuzhang Shang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model agents are increasingly deployed to automate everyday digital chores from managing emails and social media to handling banking and bills allowing users to step away from supervision. However, this capability also exposes sensitive information to phishing. Safe execution requires distinguishing malicious requests from genuine ones without simply refusing to act. Despite its practical importance, this problem remains underexplored and it is unclear whether current agents or existing defenses can achieve it. To study this problem, we first propose CredLeak-Bench, a comprehensive benchmark designed to evaluate how effectively and securely agents automate human workflows when confronted with phishing and identity verification. The benchmark covers both user-directed authentication and autonomous inbox monitoring, where agents are not explicitly instructed to log in. It systematically varies deceptive cues and pairs phishing scenarios with legitimate counterparts, enabling joi

---

### [65] Beyond Cooperative Simulators: Generating Realistic User Personas for Robust Evaluation of LLM Agents

**链接**: https://arxiv.org/abs/2605.12894
**作者**: Harshita Chopra, Kshitish Ghate, Aylin Caliskan, Tadayoshi Kohno, Chirag Shah, Natasha Jaques
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Conditional Accuracy Profiles: Diagnosing LLM Judges across Deployment Conditions

**链接**: https://arxiv.org/abs/2610.09229
**作者**: Wenqi Li, Bin Liu, Mindi Ruan, Chuanbo Hu, Minglei Yin, Xin Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-judge is now a standard tool for scalable evaluation, but judge performance is still often summarized by a single accuracy number. This aggregate view hides the deployment conditions under which a judge succeeds or fails. We introduce \textbf{Conditional Accuracy Profiling} (CAP), a post-hoc diagnostic framework that decomposes pairwise LLM-judge accuracy into eight conditions organized into content sensitivity, robustness, and rationale quality. CAP is benchmark-agnostic: it can be applied directly when a benchmark provides the required annotations, approximately through task-subset proxies, or through controlled augmentation when perturbation pairs can be generated. We instantiate CAP on seven LLM judges across six pairwise judging benchmarks, including \textsc{judgerEva-Standard}, a controlled testbed we created to support all eight conditions. CAP exposes profile differences hidden by aggregate accuracy: on \textsc{judgerEva}'s judge-independent Hard-Constructed subset, the 

---

### [67] Advancing LLM-based phoneme-to-grapheme for multilingual speech recognition

**链接**: https://arxiv.org/abs/2603.29217
**作者**: Lukuan Dong, Ziwei Li, Saierdaer Yusuyin, Xianyu Zhao, Zhijian Ou
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] NaVLM-PVC: Progressive Visual Compression for Efficient Native-Resolution Encoding in MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37189-8_12&hl=zh-CN&sa=X&d=4173352718555888849&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVGe9qqJLSsjeQmOv1NLeg8m&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: S Sun, Y Zhang, H Song, Z Guo, C Chen, Y Zhang… - European Conference on … 等 (7 人)
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We adopt a standard MLLM architecture with SigLIP2-SO400M [54] as the vision encoder, a pixelunshuffle [11] projector, and Qwen2-7B [51] as the LLM. Training follows a two-stage paradigm [71], first optimizing the vision encoder and projector

---

### [69] Phoneme-Guided Initialization for LLM-based Speech Recognition

**链接**: https://arxiv.org/abs/2610.08994
**作者**: Ryo Magoshi, Shinsuke Sakai, and Tatsuya Kawahara
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech large language models (speech LLMs) perform well on automatic speech recognition (ASR) when sufficient paired speech-text data is available, but their performance degrades in low-resource settings. A cascaded pipeline that performs speech-to-phoneme (S2P) conversion followed by phoneme-to-grapheme (P2G) conversion has been shown to outperform end-to-end speech LLMs in this regime, suggesting that phoneme-mediated processing is beneficial when paired data is scarce. We propose \textit{phoneme-guided initialization}, a simple method that uses this insight within an end-to-end framework: we pre-train the audio encoder on S2P and the LLM on P2G tasks, then connect them and fine-tune the full model end-to-end on the target ASR task. Experiments on Japanese (CSJ), Chinese (AISHELL-1), and two low-resource languages from Common Voice 25.0 (Tatar and Urdu) show that our method matches or outperforms both the cascaded S2P-P2G baseline and the end-to-end model without P2G initialization.

---

### [70] Vectorizing the Trie: Efficient Constrained Decoding for LLM-based Generative Retrieval on Accelerators

**链接**: https://arxiv.org/abs/2602.22647
**作者**: Zhengyang Su, Isay Katsman, Yueqi Wang, Ruining He, Lukasz Heldt, Raghunandan Keshavan 等 (10 人)
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] TACS: Trajectory-Aware Candidate Selection for LLM Jailbreak Suffix Optimization

**链接**: https://arxiv.org/abs/2608.29564
**作者**: Shiliang Xiao
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] From Code to Low-Code: An LLM -Driven Pipeline for Lifting Code Clones into Reusable Abstractions

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3837062.3839368&hl=zh-CN&sa=X&d=13020518896860396969&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVHo0oqflwiODVzUxU9tTabV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: R Zefferer, B Schenkenfelder, S Wagner - Proceedings of the ACM/IEEE 29th …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper introduces an LLM -driven approach that integrates two problems usually studied in isolation, namely reuse discovery (finding … The underlying hypothesis is that a combination of classical, machine learning, and LLM -based

---

### [73] Practice Makes Unsafe: Skill Misevolution in Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2608.12851
**作者**: Xutao Mao and Liangjie Zhao and Xiang Zheng and Cong Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] Loop-Back Authority in LLM Agent Teams: A Paired Experiment on Flat and Hierarchical Coordination

**链接**: https://arxiv.org/abs/2609.14767
**作者**: Burak Agachan, Max van Duijn, Amirhossein Zohrehvand
**来源**: cs.MA cs.AI cs.CL econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] Execution Realism and Reproducibility in LLM-Based Trading Systems: A Systematic Scoping Review and Evidence Audit

**链接**: https://arxiv.org/abs/2606.08285
**作者**: Junyi Yao, Zihao Zheng, Baichuan Li, Jiayu Long
**来源**: cs.AI cs.CE q-fin.CP q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] Know the Shape, Find the Fault: Topology-Conditioned Diagnosis of Multi-Agent LLM Failures

**链接**: https://arxiv.org/abs/2610.10126
**作者**: Xinwen Liu, Zhuocheng Pan, Isabella Zhu, Jawei Zhang, Xudong Liu, Tianyu Wo
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems coordinate task execution through exchanges of information among agents. When coordination breaks down, similar symptoms in execution traces can reflect different problems in how information is passed, used, or verified. Communication topology captures how agents exchange information and provides structural cues for distinguishing coordination failure modes. Using these cues for diagnosis requires establishing how topology relates to failure patterns and recovering the relevant structure from execution traces that lack explicit topology labels. We analyze the relationship between communication topology and failure patterns and introduce MAScope, a two-stage framework for topology-conditioned diagnosis. Its Trace Structural Extractor TSE recovers communication topology from heterogeneous execution traces by grounding an interaction graph in message evidence. The Topology-Conditioned Judge TC-Judge then classifies failures using the trace, predicted topology, an e

---

### [77] From Expected Harmfulness to Likelihood: A Probabilistic Reformulation of Jailbreaking LLM Agents

**链接**: https://arxiv.org/abs/2610.09973
**作者**: Juanyang Xu, Zheng Wang, Xingyu Zhao, Siddartha Khastgir, Andi Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When the harmfulness of an LLM agent's output can be quantified, a natural jailbreaking objective is to maximize expected harmfulness over admissible input modifications. An alternative approach constructs or selects harmful target outputs and modifies the input to increase their likelihood. We establish a precise connection between these two approaches through a probabilistic reformulation. Specifically, we show that the gradient of the logarithm of expected harmfulness with respect to the input equals the expected input gradient of the model's log-likelihood under a harmfulness reweighted output distribution. This identity provides a unified interpretation of expected harmfulness and target likelihood optimization. Building on this connection, we propose OPUR, a sampling distribution designed to generate highly harmful target outputs and use the resulting samples to guide likelihood-based input optimization. Experiments demonstrate the effectiveness of the resulting method in jailbre

---

### [78] Finding the Right Balance: Relevance and Diversity in LLM Retrieval

**链接**: https://arxiv.org/abs/2610.09412
**作者**: Guillaume Brouillette (1), Faustin Kagabo (1), Usef Faghihi (1), Nadia Ghazzali (1) ((1) Universit\'e du Qu\'ebec \`a Trois-Rivi\`eres, Trois-Rivi\`eres, Canada)
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval diversification is widely available in retrieval-augmented generation (RAG) frameworks, yet prior studies disagree on whether it improves retrieval and answer quality. We show that its effectiveness varies primarily with candidate-pool redundancy, in a pattern consistent with the number of distinct evidence pieces a query requires. Using controlled near-duplicate injection and production-style overlapping chunking, we find that diversification harms relevance, evidence coverage and answer quality on clean pools, but becomes beneficial on multi-evidence tasks when redundancy causes nearest-neighbor retrieval to select repeated passages. We therefore introduce a query-adaptive rule that diversifies only when the effective number of distinct documents in the nearest-neighbor top-$k$ selection falls below the query's evidence requirement. Computed from existing embeddings, the rule captures most of the achievable gain, transfers across datasets and encoders and automatically redu

---

### [79] DUDA-Bench: Benchmarking LLM Agents on Multimodal Data-Driven Urban Diagnosis

**链接**: https://arxiv.org/abs/2610.09374
**作者**: Yizhi Song, Hang Ni, Weijia Zhang, Hao Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Urban diagnosis integrates heterogeneous observations to identify urban problems, localize affected areas, and investigate contributing factors, informing evidence-based urban planning and management. However, its reliance on labor-intensive, case-specific expert workflows limits scalability and reuse, motivating the exploration of agent-based execution. To evaluate this capability, we introduce DUDA-Bench, a hierarchical and interactive benchmark that formalizes data-driven urban diagnosis as a multi-stage agent workflow. It comprises 86 atomic and 22 workflow tasks spanning four analytical stages, grounded in multimodal data from 12 cities covering five urban problem types. Evaluations of seven backbone models and five agent systems reveal a substantial gap between isolated analytical competence and end-to-end diagnosis, with system benefits varying across backbones. Trajectory analysis shows that unresolved evidence gaps propagate across stages, while successful recovery involves re

---

### [80] LiveMACE: Process-Aware Evaluation of LLM Agent Capabilities in Evolving Markets

**链接**: https://arxiv.org/abs/2610.09872
**作者**: Jun Zhao, Leiming Fu, Yanbo Wen, Yiding Wang, Xuantong Liu, Yang Shu 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating agents by outcomes alone can obscure the capabilities that produce them. This problem is especially pronounced in evolving environments, where outcomes reflect a closed-loop interaction between agent behavior and changing external conditions. We introduce LiveMACEBench, a process-aware benchmark that uses live financial markets as a naturally evolving testbed for persistent LLM agents. Five frontier LLMs operate along continuous trajectories under matched Tool Use, Persistent Memory, Rule Following, and Multi-Agent Collaboration configurations. We evaluate them through both realized outcomes and mechanism-specific diagnostics derived from complete decision traces. Across 30 days of live evaluation, we find a pronounced outcome-capability gap: realized returns often diverge from capability-specific measurements, and similar outcomes can arise from markedly different patterns of mechanism use. Trace-level diagnostics further expose distinct bottlenecks across capabilities, dem

---

### [81] From Uncertainty to Action: Learning to Steer LLM Agents

**链接**: https://arxiv.org/abs/2610.09115
**作者**: Hanwen Li, Jinhao Duan, Guanhua Zhu, Junchi Lu, Bo Shen, Chenxi Yuan 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Steering an LLM agent means deciding whether to correct it, at which step, and with which mechanism. Uncertainty is often used to decide when to correct an agent, but whether it can guide these decisions remains unclear. We steer agent trajectories separately at every non-terminal step with each of four mechanisms and run each continuation to completion. The resulting stepwise outcome table (SOT) holds about 82,000 counterfactual continuations of 1,864 trajectories from three benchmarks and two agents. It shows that uncertainty can identify failing trajectories, but that no single signal reliably locates the step at which steering helps. We therefore propose VoS (Value of Steering), a trajectory-level monitor, offline or online, that learns from SOT the value of steering at each step and decides where to steer by it. A harm-budgeted trigger decides whether to steer, limiting the fraction of successful trajectories that VoS disturbs. VoS improves on unmodified execution in all 12 settin

---

### [82] SafeEvo: Deciphering the Safety Alignment Mechanism and Evolution in Language Models

**链接**: https://arxiv.org/abs/2610.09600
**作者**: Miao Yu, Hao Huang, Lu Yuan, Yunpeng Li, Kun Wang, Zuming Jiang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety interpretability advances the study of Large Language Model (LLM) alignment from behavioral constraints driven by data or algorithms towards a deeper understanding of internal mechanisms. However, existing works have focused primarily on safety-related representations, attention heads, or neurons after alignment, while largely overlooking the safety mechanisms in pretrained-only models and their evolution across alignment checkpoints. To address this, we propose SafeEvo, an interpretability framework from the circuit (sparse subgraphs of an LLM) perspective. SafeEvo first applies an optimization-based extraction algorithm to identify weak refusal circuits in pretrained base LLMs that can independently express refusal behavior. Causally ablating these circuits completely eliminates the base model's refusal of harmful inputs. SafeEvo then traces the evolution of refusal circuits across successive alignment checkpoints and finds that their structures change progressively, suggestin

---

### [83] LoGRA: Scaling LLM Reinforcement Learning with Low-Rank Gradient Sketches

**链接**: https://arxiv.org/abs/2610.06647
**作者**: Shaokun Zhang, Yifan Zhang, Jian Hu, Yueying Li, Hao Zhang, Binfeng Xu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] LLM-Enabled UAV Dispatch: A System-Level Survey and Taxonomy

**链接**: https://arxiv.org/abs/2610.09466
**作者**: Xiao Han, Aoyang Quan, Xiangyu Zhao, Xiangjie Kong, Guojiang Shen
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unmanned aerial vehicle (UAV) dispatch is beginning to move beyond isolated path planning and optimization-driven resource allocation toward system-level coordination supported by semantic reasoning and LLM-based interfaces. This survey provides a unified characterization of LLM-enabled UAV dispatch systems that bridges semantic intent, symbolic decision-making, and physical UAV execution. Rather than treating LLMs as standalone add-ons, we conceptualize them as a cross-layer semantic orchestration layer connecting human instructions, external solvers, and distributed control modules. We organize the literature into four representative dispatch paradigms: pipeline dispatch, global assignment dispatch, decentralized agentic dispatch, and divide-and-conquer dispatch. For each paradigm, we analyze its decision logic, system structure, control flow, representative methods, and potential LLM roles. We further examine how LLMs support semantic parsing, retrieval-grounded planning, solver orc

---

### [85] WSM-Aware HRI: An IoT-Enhanced Framework for Early Detection and Norm-Guided Repair of Failures with LLM Guidance

**链接**: https://arxiv.org/abs/2609.32336
**作者**: Hanlin Zhang and Yuquan Wang and Tianwei Zhang and Zhenglong Sun
**来源**: cs.RO cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] LLM Persuasion Is in the Eye of the Evaluation

**链接**: https://arxiv.org/abs/2610.10232
**作者**: Kamile Dementaviciute, Julija Vaitonyte, Tijl De Bie
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have already been shown to match or exceed human experts in persuasion. While their persuasive capabilities hold promise for beneficial uses such as education and health communication, they can also be used to manipulate and misinform, making their evaluation a growing priority for developers and regulators. That evaluation, however, remains fragmented: studies differ in what they treat as persuasion, and broad claims often rest on narrow, situation-specific assessments. Automated methods, often modelled on human studies, offer a way to compare such assessments directly, as they can be run on the same models at scale and can include high-risk forms of persuasion that would be difficult or unethical to test on people. In this study, we adapt nine published automated methods to a shared setup, run them on the same fifteen LLMs, and ask whether their rankings agree and why. We find that the methods agree only weakly (mean Spearman $\rho = 0.25$). Our analyses 

---

### [87] A Positive Case for Faithfulness: LLM Self-Explanations Help Predict Model Behavior

**链接**: https://arxiv.org/abs/2602.02639
**作者**: Harry Mayne, Justin Singh Kang, Dewi Gould, Kannan Ramchandran, Adam Mahdi, Noah Y. Siegel
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] Leveraging LLM-Generated Explanations for Detecting Emotionally Rewritten Fake News

**链接**: https://arxiv.org/abs/2610.08835
**作者**: Yupei Guo, Jiajun He, Xiaohan Shi, Tomoki Toda, Zekun Yang, Bowen Wang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The spread of fake news may cause severe social consequences. Existing fake news detection methods mainly focus on stylistic variations or incorporate external information such as explanations. However, news articles are often rewritten under different emotional backgrounds while preserving their underlying factual claims, which may affect the robustness of detection models. In this work, we investigate fake news detec- tion under fact-preserving emotional variations. To study this problem, we construct emotion-rewritten test sets and generate explanations from the original news articles as stable background knowledge. We then propose a Gated Cross Attention (GCA) framework that adaptively integrates emotionally rewritten news with the corresponding explanations, enabling the model to focus on informative explanation content while reducing potential mismatches caused by emotional reframing. Experiments on PolitiFact, GossipCop, and LUN demonstrate that the proposed method achieves nota

---

### [89] Overview of the third “Voight-Kampff” Generative AI/ LLM detection task at PAN and ELOQUENT 2026

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4283/paper386.pdf&hl=zh-CN&sa=X&d=4881936250868602116&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVHD3QHJxnqMMiel1YuhXkWY&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: J Bevendorff, RR Gunti, J Karlgren, M Fröbe, M Potthast… - Working Notes of CLEF, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In the “Voight-Kampff” Generative AI/ LLM Detection shared task, we measure the effectiveness of LLM detection systems and their robustness against adversarial text obfuscations. In the 2026 edition, we focus explicitly on whether we can reliably

---

### [90] Beyond the Sycophancy Score: How Task, Model, and Pressure Shape LLM Yielding

**链接**: https://arxiv.org/abs/2610.08840
**作者**: Guang Yang, Homa Hosseinmardi, Fengchen Liu, Amir Ghasemian
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often abandon a correct answer, or endorse a user's position, once the user pushes back. This behavior, called sycophancy, is usually reported as a single rate per model, which says little about when it happens or how a user can avoid it. We study the conditions that produce it with 103,939 graded replies from ten configurations: eight LLMs with reasoning disabled, and two of them again with maximum reasoning, all facing the same 200 items, 13 pressure conditions, and four-turn conversations, with every reply labeled by two independent LLM judges. We find that the dominant factors are how costly it is for the model to verify the user's claim, and whether a trained guardrail covers it. Removing this task factor from a logistic model costs 0.485 of McFadden $R^2$, against 0.139 for model family and 0.009 for pressure tactic. Anchored facts are almost never conceded (1.3%), while adoption on logic puzzles rises with the number of clues needed to refute the pus

---

### [91] Ask the Expert: LLM-Guided Reinforcement Learning for Autonomous Cyber Defense

**链接**: https://arxiv.org/abs/2610.09337
**作者**: Fernando Martinez, Abhishek Satyam, Tao Li, Junaid Farooq, Ying Wang, and Juntao Chen
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Policy-based reinforcement learning (RL) approaches have produced promising results for autonomous cyber defense; however, they are sample-inefficient in settings where defenders must respond under delayed, partial observations with actions from large action spaces. While large language models (LLMs) may reason semantically about security state space, high latency and trust assumptions prevent attractive in-line deployment models. We introduce Ask the Expert, a training-time guidance framework which first summarizes hard cyber-defense states, then intermittently queries an LLM for host-level defensive recommendations via a constrained action interface, and finally transforms those recommendations into tiered reward shaping for use with PPO. Because the LLM is discarded after training, deployment is a pure RL policy. Across TTCP CAGE CC1 and CC2 and both attacker types, this asymmetric design improves sample efficiency over PPO and outperforms the evaluated potential-based reward shapin

---

### [92] Knowledge boundary probing and demand-guided intervention for LLM-based power system code generation

**链接**: https://arxiv.org/abs/2605.31478
**作者**: Hui Wu, Xiaoyang Wang, Zhong Fan
**来源**: cs.SE cs.CL cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] Taxonomy-Aware Hybrid Retrieval with Bounded LLM Reranking for TalentCLEF 2026 Task A

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4283/paper487.pdf&hl=zh-CN&sa=X&d=12873354266014502077&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVFi0gbQ-zWjKAzzjr2lGgyy&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: A Riabi, M Essayeh - CLEF (Working Notes), 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> signals and reserves the LLM for bounded reranking. This follows the broader evidence that listwise LLM prompting can improve document reranking [19… 20], including in zero-shot cross-lingual retrieval [21], while keeping the LLM anchored to

---

### [94] RT-DETR-World: Transferring Rich LLM Semantics to Real-Time Open-Vocabulary Detection

**链接**: https://arxiv.org/abs/2610.09502
**作者**: Yupeng Zhang, Ziyi Zhao, Juntao Cheng, Sheng Wang, Ningnan Guo, Ruize Han 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-vocabulary detection (OVD) recognizes categories unseen during training through textual category queries, yet achieving strong generalization with real-time efficiency remains challenging. Beyond vocabulary scaling, zero-shot generalization may benefit from reusable visual--semantic cues learned from seen data, including attributes, actions, states, and contextual relations. Existing real-time OVD methods primarily emphasize vocabulary coverage and efficient region/query--text matching; under strict efficiency constraints, compact detectors may struggle to absorb rich instance semantics and scene context. We propose RT-DETR-World, a compact DETR-style detector that transfers the rich semantics conveyed by descriptions during training while retaining lightweight query--text matching at inference. We construct GroundingCapv2 with three levels of supervision: category names for standard OVD, object descriptions conveying instance-level semantics, and image descriptions conveying obje

---

### [95] Hidden Dependencies in LLM -Enabled Code Generation: An Empirical Study of Regressions and Escaped Failures

**链接**: https://scholar.google.com/scholar_url?url=https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ESEM.2026.51&hl=zh-CN&sa=X&d=5187097348702355574&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVHv2C5BV1uP5NL4KO8z7Wfp&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: G Nam, G Yang - 20th International Symposium on Empirical Software …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> However, LLM -enabled code-generation systems also depend on non-code artifacts (the … , and retrieval data affect the behavior of LLM -enabled code-generation systems, framing the … , and retrieval data as software dependencies of an LLM -enabled

---

### [96] Continuous Semantic Caching for Low-Cost LLM Serving

**链接**: https://arxiv.org/abs/2604.20021
**作者**: Baran Atalar, Xutong Liu, Jinhang Zuo, Siwei Wang, Wei Chen, Carlee Joe-Wong
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] AGAR: a reinforcement learning substrate for LLM program evolution

**链接**: https://arxiv.org/abs/2610.09215
**作者**: Haoran Li, Zengle Ge, Xiaomin Yuan, Yui Lo, Haoxin Li, Songlin Zhou 等 (10 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given a task and an evaluator, a language model can rewrite a candidate program while a search loop decides which rewrites survive, offering a practical route to algorithm discovery. But that loop is governed by five constants set by hand: which parent to select, how hard to mutate, how to keep diversity, what to remember, and a scalar score that never says which part of the program earned it. Reinforcement learning already has an estimator for each. The obstacle is that program evolution is not usually written down as a decision process. We formalize it as a Markov decision process whose action is the modular prefix the model is conditioned on, rather than the program it emits. Credit assignment, value estimation, adaptive exploration, and experience memory can then attach to distinct components. AGAR (Algorithm Generation As RL) provides the resulting substrate: any estimator can be replaced or switched off without changing the controller, making the transfer auditable one mechanism 

---

### [98] EvoSignal: LLM-Guided Evolutionary Design of Modular Traffic Signal Control Programs

**链接**: https://arxiv.org/abs/2610.09563
**作者**: Leizhen Wang and Peibo Duan and Zhenlin Qin and Yancheng Ling and Jian Xu and Yue Wang and Hao Wang and Zhenliang Ma
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective traffic signal control (TSC) requires policies that respond to changing traffic demand and network conditions while meeting different control objectives. However, adapting existing strategies often involves repeated manual design and adjustment, making it difficult to systematically explore better control rules for a target network. Large language models (LLMs) can automate this process, but directly using them to select signal phases leaves decision rules embedded in black-box models and incurs recurring inference costs and latency. This paper formulates TSC as a modular program design problem and proposes EvoSignal, an LLM-guided evolutionary framework using traffic knowledge and performance feedback. The modular representation separates traffic feature extraction, local phase prioritization, and optional network-based priority adjustment. Starting from several established strategies, EvoSignal improves programs through feedback on congestion and signal operation, retaining

---

### [99] Open-Weight LLM Fine-Tuning Defenses are Susceptible to Simple Attacks

**链接**: https://arxiv.org/abs/2605.26526
**作者**: Kevin Kuo, Virginia Smith, Chhavi Yadav
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] Cross-Agent Learning Signals Enable Coordinated Role-Decomposed LLM Training

**链接**: https://arxiv.org/abs/2606.10684
**作者**: Jaewan Park, Solbee Cho, Jay-Yoon Lee
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] APEX: Active Protection at Execution Boundaries for LLM Agents

**链接**: https://arxiv.org/abs/2610.06966
**作者**: Xinran Zheng, Xin Fan Guo, Zhiqiang Hao, Fan Yang, Xingzhi Qian, Jiawei Du 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] An LLM-Native Psychometric Instrument Reveals a Self-Report--Behavior Gap Across 25 Models

**链接**: https://arxiv.org/abs/2606.09843
**作者**: Juan Manuel Contreras
**来源**: cs.HC cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] Who Brought Easter Eggs to Eid? Auditing LLM-Generated Cultural Translation of Math Word Problems Across Languages and Regions

**链接**: https://arxiv.org/abs/2606.11009
**作者**: Parisa Suchdev and Juniper Lovato
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] TutorLoop: Regulating Student Learning Behaviors via Sensor-in-the-Loop Generative Feedback

**链接**: https://arxiv.org/abs/2610.09400
**作者**: Songlin Xu and Xinyu Zhang
**来源**: cs.HC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present TutorLoop, a sensor-in-the-loop system that regulates student learning behaviors by delivering adaptive feedback based on real-time cognitive states. Unlike prior large language model (LLM) tutors that directly depend on scenario-specific content, TutorLoop operates on sensor-derived signals captured via webcams. Moreover, unlike direct cognitive-to-feedback mappings that are short-sighted, the system employs a deep reinforcement learning (DRL) agent to optimize the feedback type across the entire learning process. Finally, another LLM tutor refines feedback into human-like, context-aware messages. We evaluate TutorLoop in a large-scale user study (N=187), where a model trained offline is directly applied to a new learning task without retraining. Results show that TutorLoop provides less frequent yet more effective interventions, improving attention, reducing workload, increasing engagement, and ultimately enhancing learning outcomes. These findings highlight the potential 

---

### [105] Multi-Aspect Runtime Verification for Simulation-Based V&V of LLM-Enabled Autonomous Agents

**链接**: https://arxiv.org/abs/2610.08928
**作者**: Nikolaos Kekatos, Dimitrios Nikou, Anastasios Temperekidis, Alexios Lekidis, Nikolaos Kolokotronis, Panagiotis Katsaros 等 (7 人)
**来源**: cs.CR cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are entering decision-support roles in defence staff work, where the obligations they must respect are already written down and binding, and where retraining is not available as a control because models arrive as procured components. What can be placed under engineering control is the interface between the agent and the systems it acts on. Those obligations are at once spatial, temporal and text-semantic, and a violation typically lives in the composition of a multi-step interaction, which is why per-event guardrails miss sequential tool-attack chains. We present a multi-aspect runtime-verification framework that decomposes a natural-language policy clause into a typed spatial/temporal/semantic triple over one canonical event stream, checks each aspect with its own monitoring specification, and fuses the verdicts through a four-valued algebra that carries provenance. The spatial aspect is interpreted over a weighted two-sorted location graph in which mission geometry a

---

### [106] Reasoning with Evidence, Not Merely Rationales: Verifiable Preference Proofs for LLM -Based Recommendation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.02968&hl=zh-CN&sa=X&d=10245852012200634086&ei=Z3fHar_uBouu6rQP5qXViQs&scisig=ACTRDVEHZgz49sMlLKFC9YSVQseZ&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: Y Hou, N Kang, P Wang, H Li - arXiv preprint arXiv:2610.02968, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We introduce PROVE-REC, a general framework for verifiable preference reasoning in LLM -based recommendation. Pass A converts the … that PROVE-REC consistently outperforms strong sequential, generative, and LLM -enhanced

---

### [107] RAISED: Self-Distillation for Robustness to Prompt Injection in LLM Agents

**链接**: https://arxiv.org/abs/2610.06401
**作者**: Mohamed Dhouib, Clement Elliker, Alexi Canesse, Ma\"el Jenny, Lucas-Andrei Thil, Mahammed El Sharkawy 等 (8 人)
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Cache the Encoder Within:Compact, Reusable Memory across LLM Queries

**链接**: https://arxiv.org/abs/2610.10058
**作者**: Hanzuo Liu, Chunyu Liu, Chaofan Lin, Alex Lamb, Mingyu Gao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated queries over shared documents incur redundant encoding, while caching model states introduces persistent storage costs. Building on CoMem's intermediate-state interface, EncBank treats a pretrained LLM's lower layers as a reusable document encoder and compactly stores their outputs for an adapted upper-layer reader. A self-distilled suffix adapter is shared across storage precisions within each backbone, without quantization-specific retraining. Across five benchmark suites on three Qwen backbones spanning different sizes and full-attention and hybrid architectures, 4-bit storage keeps each reported benchmark aggregate within one score point of native-precision EncBank. In a fixed Qwen3-8B workload, it retains 28.1% of the native-precision persistent GPU store. Separate native-precision controls yield a 1.40x selected-pack prefill speedup over same-evidence, same-adapter text replay, at a 3.12-point RULER accuracy cost. A native-precision Qwen3.8-27B configuration also passes 

---

### [109] MATE: Diagnosing Empathy Calibration Failures in Multi-Turn Human-LLM Interaction

**链接**: https://arxiv.org/abs/2505.24658
**作者**: Yeseon Hong, Junhyuk Choi, Minju Kim, Bugeun Kim
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] MARS: Malware Analysis with Rule-Based Scoring of LLM Claims

**链接**: https://arxiv.org/abs/2610.09553
**作者**: Hyeongjun Choi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can triage malware through direct verdicts or behavioral claims scored by an external policy. We present MARS, a malware triage framework, and compare direct classification with single-pass claim scoring using the same evidence collector and identical static evidence bundles for each model. The evaluation covers 1,195 PE and ELF binaries grouped into 1,001 near-duplicate clusters and six language models, with deterministic rules providing a baseline. Direct classification is more accurate for all six models. On samples with usable outputs from both paths, its accuracy advantage ranges from 3.7 to 20.9 percentage points, with all 95% cluster-bootstrap confidence intervals for the differences above zero. It also achieves higher malicious alert recall in ten of twelve platform and model combinations. Claim mediation provides no consistent reduction in performance variation across models. Separate subset studies find more consistent alert decisions for direct classifi

---

### [111] Auditing generative audio calls for known-task audio-llm evaluation

**链接**: https://arxiv.org/abs/2608.27817
**作者**: Mengzhe Geng
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Training Parallel Speculative Draft Models by Directly Minimizing Expected Decoding Rounds

**链接**: https://arxiv.org/abs/2610.10411
**作者**: Yunxiao Zhao, Changxiao Cai
**来源**: cs.LG cs.AI cs.CL stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by using a low-cost draft model to propose tokens that the full-size target model verifies in parallel. Parallel and semi-autoregressive (semi- AR) drafters improve drafting efficiency by proposing an entire block in a single forward pass, but training them raises a new difficulty: the draft distribution for a given position depends on where the decoding round starts, and where rounds start depends on how many tokens earlier rounds accepted. Existing training objectives typically rely on block-local surrogates that ignore this cross-round coupling, and therefore do not directly optimize the global decoding efficiency. In this work, we develop a theoretical framework for training and evaluating these drafters by representing speculative decoding as a Markov reward process. This formulation yields the Expected Decoding Rounds (EDR) objective, which weights local rejection costs by state occupancies and exactly equals the exp

---

### [113] sk-bench: A Native-First Benchmark for Evaluating Large Language Models in Slovak

**链接**: https://arxiv.org/abs/2610.09152
**作者**: Marek \v{S}uppa, Ivan Vykopal, Andrej Ridzik, Kristi\'an Sopkovi\v{c}, Nat\'alia K\v{n}a\v{z}ekov\'a, Jaroslav Kop\v{c}an 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual LLM benchmarks omit Slovak, a morphologically rich West Slavic language of five million speakers, or cover it only by machine translation. We present sk-bench, a native-first Slovak benchmark with 30 datasets (33 scored task variants) across ten skill categories. Eleven resources are introduced or first packaged for generative-LLM evaluation, including IFEval-SK with Slovak-adapted instruction checkers and native Chiby/SKJ1 resources for Slovak grammar and morphology. We evaluate 55 open- and closed-weights models under one harness. The best open model trails proprietary APIs by 12.6 points. Model rankings are similar for native and translated closed-form data ($\rho\geq0.98$), though translation separates the strongest models less well. By contrast, human-authored and LLM-generated QA questions rank models differently ($\rho=0.72$). For Qwen3-14B, continued Slovak pretraining lowers the overall score by 13.9 points. A small instruction set restores three quarters of that 

---

### [114] Does Document Structure Help Dense Retrieval? A Placebo-Controlled Ablation of Four Mechanisms Across Two Corpora

**链接**: https://arxiv.org/abs/2610.10170
**作者**: Andrey Kuehlkamp, Priscila Correa Saboia Moreira, Samuel Rund
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation systems increasingly rely on document-structure treatments: structure-aligned chunking, LLM-generated chunk contexts, heading-path metadata, and hierarchical two-stage retrieval. Separate studies support each on different corpora, embedders, and metrics, and none control for a shared confound: any text prepended to a chunk perturbs its embedding. We present a mechanism-isolating ablation testing all four treatments under one protocol, matching chunk sizes across conditions and adding a semantically null placebo---heading paths that are structurally valid but shuffled across documents. We score retrieval with a coverage-aware nDCG and test four pre-registered contrasts via document-clustered bootstrap with Holm correction, on two distant corpora: 200 Wikipedia Featured Articles (951 queries) and 1,585 QASPER papers (4,303 questions). Organization helps, and the cause is content, not tokens: structure-aligned chunks with real heading paths beat contextualiz

---

### [115] An Empirical Study of Agent Skills' Downstream Utility

**链接**: https://arxiv.org/abs/2610.08875
**作者**: Yu Cheng, Dehai Zhao, Zhongxin Liu, Qing Huang, Zhenchang Xing, Xiaoxue Ren
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent Skills package procedural guidance and resources for reuse, but a relevant Skill does not necessarily improve task performance. Existing studies characterize Skill content and evaluate downstream performance, yet provide limited explanations of how utility depends on content, execution configuration, and multi-Skill organization. We conduct an empirical study on 87 SkillsBench tasks, defining downstream utility as the pass-rate difference from No-Skill on the same tasks under the same model--harness configuration. We compare the same Skills across nine configurations, then examine alternative published Skills and organizations of fixed Skill sets under three selected configurations. We retrieve marketplace candidates from a curated corpus of 37,596 Skills. LLM-assisted analysis of content, execution traces, and final artifacts, followed by author review, relates provided support to actual use and task outcomes. The same Skills help some configurations and hurt others on 36.78\% o

---

### [116] Let the Library Speak: Self-Advertised Method Selection for Formal Proving

**链接**: https://arxiv.org/abs/2610.09401
**作者**: Xiaopeng Yuan, Suijin Wang, Yanli Wang, Haibo Jin, Peng Kuang, Jerry Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based formal provers can retrieve relevant lemmas and prior proofs, but relevance alone does not say whether a mathematical method can be used on the current theorem. A method has prerequisites, a target, an intended action, and obligations that its use leaves to prove. Methods that look equally related to a theorem may therefore differ substantially in whether they offer a plausible next step. We formulate this as an applicability-aware method-selection problem and introduce self-advertisement: before candidates are ranked, a model generates a problem-specific proposal for each one, stating what part of the goal it targets, what action it would take, and what conditions that action requires. We organize 82 reusable methods from Putnam 2000-2014 as Method Contracts, which pair applicability descriptions with Mathlib anchors, a checked example or scaffold, and expected proof obligations. A single batched call elicits proposals across the library; vague or unsupported proposals are d

---

### [117] Talking with Language Models

**链接**: https://arxiv.org/abs/2610.09064
**作者**: James Ravi Kirkpatrick, Alexandru Radulescu, Rachel Katharine Sterken
**来源**: cs.CY cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When we interact with large language models (LLMs), are we having a conversation? They are designed to invite us to treat them as intelligent interlocutors who remember, act, and make commitments. But appearances deceive. We introduce the artifactual stance, a framework that reconceives human-AI interaction as artifact-mediated exchanges of candidate texts. LLM outputs are candidate texts optimized for utility, not utterances bearing meaning or force. LLMs are sophisticated text generators, not speakers. Between sessions, nothing runs; between turns, no one remembers. What persists is a configuration and a transcript. The "conversation" is a user's solo performance, interpretive labour disguised by interface and artifact design. This shift dissolves recent philosophical puzzles. Questions about what 'I' and 'you' refer to in AI exchanges, about whether systems can lie or be held to promises, about the identity of our supposed interlocutors all rest on a false presupposition. There is n

---

### [118] KVFetch: Temporal Prefetching for the Missing Half of KV Cache Compression

**链接**: https://arxiv.org/abs/2610.08811
**作者**: Linfeng Dong
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As context windows scale to tens or hundreds of thousands of tokens, KV cache compression has become essential for efficient LLM inference. Existing methods fall into three families: score-based eviction, summary compensation, and offload-and-recall. Yet all three decide what to keep or recall by content relevance to the current query. We show this shared design is structurally incomplete. A cache supports two access modes: associative lookup by content and sequential traversal by position; current compressors implement only the first. The gap matters in practice: retrieval-augmented generation, code completion, and structured-data extraction all require the model to reproduce identifiers, field values, or code tokens verbatim from the context. Under compression, content-based eviction retains the head of such a sequence but discards its continuation, causing verbatim copying to break irreversibly midway, a failure we call sequential forgetting. This failure resists better scoring, lar

---

### [119] Which Language Should a Skeleton Speak? Language Choices in Multilingual Reasoning

**链接**: https://arxiv.org/abs/2610.09607
**作者**: HyeonSeok Lim, SeungWoo Song, Inho Won, Hoyun Song, Jihyo Kim, KyungTae Lim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skeleton-based reasoning prompting is a promising training-free approach for structuring LLM reasoning, but prior work largely assumes an English-centric setting. We propose the Language-Aware Skeleton Exploration Framework (LASEF) to study skeleton-language choice in multilingual mathematical reasoning. Across math benchmarks, model scales, and languages, we show that English skeletons yield a small positive tendency on average, most visible for smaller models and low-resource languages. However, few language-level gains remain significant after correction, and English is not universally optimal. Combining greedy decoding, multi-rollout evaluation, translation ablation, and cross-benchmark validation, we further find three patterns of skeleton-language effects: directionally consistent, evaluation- and benchmark-dependent, and asymmetric negative. These effects cannot be fully explained by generation quality alone. Overall, skeleton language is a context-dependent design variable that

---

### [120] Kernel Autoresearch for Open-Ended Model Discovery

**链接**: https://arxiv.org/abs/2610.10394
**作者**: Richard Cornelius Suwandi, Feng Yin, Kevin Murphy
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Kernels encode the inductive bias of a wide range of machine learning models, yet automated kernel design faces a fundamental dilemma. A fixed grammar of base kernels and operators guarantees validity but limits the search to structures expressible by those building blocks. Conversely, unrestricted programs remove this limitation but no longer guarantee validity. In our stress tests, 22-58% of LLM-generated kernels that pass numerical checks on random inputs fail when evaluated at different scales or dimensions. We propose Kernel Autoresearch (Kernaut), which treats kernel design as open-ended model discovery. Coding agents write kernels as programs, while construction contracts ensure that every accepted kernel is valid. A quality-diversity archive retains high-performing kernels with distinct behaviors, and novelty screening steers agents toward functionally new candidates. Our experiments demonstrate that the discovered kernels encode reusable inductive biases that generalize to uns

---

### [121] Q-PACE: Dynamic Precision Allocation for Quantization-Aware Training

**链接**: https://arxiv.org/abs/2610.09183
**作者**: Alexandra Volkova, Matin Ansaripour, Erik Schultheis, Christoph H. Lampert, Dan Alistarh
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization-aware training (QAT) leverages lower-precision arithmetic to reduce the cost of LLM deployment, but aggressive quantization degrades final model performance. A common remedy is mixed-precision training, in which high precision is assigned to some of the layers to maintain performance while keeping the cost constrained. This approach then requires precision assignments for model layers during training. We provide a new approach, called Q-PACE, consisting of a second-order sensitivity model that predicts the loss increase as a sum of quantization noise MSE weighted by per-layer curvature coefficients. During training, we periodically re-compute these coefficients using perturbations across layers, and re-assign precision. Pretraining and supervised fine-tuning experiments on LLMs of up to 4B parameters show that Q-PACE consistently improves over existing mixed-precision training recipes, and achieves comparable loss at substantially lower total memory budgets. We further fin

---

### [122] The AI Evaluation Ecosystem

**链接**: https://arxiv.org/abs/2610.09296
**作者**: Yash Dave, Sang T. Truong, Serena Wang, Sanmi Koyejo
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI evaluation shapes the decisions of model providers, users, funders, and regulators. We argue that designing valid benchmarks requires contextualizing design choices in the dynamics of this ecosystem of actors. We develop a simulation architecture that combines rule-based market dynamics with LLM-driven strategic actors, building on advances in Generative Agent-Based Modeling (GABM). We model benchmarks, consumer needs, and provider capabilities as vectors over a six-dimensional capability space (reasoning, coding, knowledge, safety, communication, agentic), with structural information partitions across actors. As a case study, we apply this stylized simulation to explore benchmark holdout design. We find that moving from public benchmarks to private holdout benchmarks shrinks the gap between benchmark scores and user satisfaction on most benchmarks but widens it on a few, depending on where holdout weights shift scoring credit. We stress-test our findings at both the instrument and 

---

### [123] When Rank Rises as LLMs Degrade

**链接**: https://arxiv.org/abs/2610.09647
**作者**: Zhaohui Geoffrey Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training adapts language models in non-stationary environments. Practitioners monitor representation health with RankMe and related spectral statistics, often assuming that rank falls when representations degrade. We show that this assumption is unsafe for LLM post-training. In a controlled study of Qwen3-0.6B with four degradation modes and three seeds, data duplication worsens held-out loss by 75% relative to healthy while increasing both original and centred RankMe; the latter changes by 13.5 pooled standard deviations. Covariance effective rank rises to nearly twice its healthy value. This failure is spectral dispersion rather than collapse, so a one-sided monitor rates the worst checkpoint as the healthiest. By contrast, a learning-rate misconfiguration lowers centred RankMe and k95, while uncentred RankMe is inconsistent across seeds. Direction is therefore a property of the regime-statistic pair and cannot be fixed by recalibration alone. We also distinguish two often-confl

---

### [124] ScribbleEdit: A Benchmark for Scribble-Only Image Editing

**链接**: https://arxiv.org/abs/2610.09382
**作者**: Jie Ren, Hao Kang, Kai Guo, Yiding Yang, Bo Liu, Liming Jiang 等 (10 人)
**来源**: cs.GR cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scribble-based interaction provides a lightweight and intuitive way for users to specify image editing intents in interactive editing tools. However, current image editing models based on VLMs or LLMs struggle to understand and execute edits based solely on scribble inputs. To systematically study this problem, we construct a new benchmark, ScribbleEdit, that evaluates the ability of image editing models to perform image editing conditioned on scribbles. This task requires both a deep understanding of the intention of the scribble and an accurate interpretation of its spatial information. In ScribbleEdit, we design an automated data construction pipeline and introduce a dedicated evaluation protocol that explicitly measures intention alignment. Our analysis reveals that existing VLM/LLM-based editing models fail to accurately capture scribble intentions. To guide future progress on scribble-only image editing, we propose a simple yet effective soft-token baseline, which enhances the mo

---

### [125] Agentic AI-Assisted Modeling for Production Scheduling: Assessment in Constraint Programming

**链接**: https://arxiv.org/abs/2610.10184
**作者**: \'Angel S\'anchez-Fern\'andez, Javier Pernas-\'Alvarez and Diego Crespo-Pereira
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing optimization models for production scheduling requires substantial expert effort. Research on large language models (LLMs) has followed two directions: specialized approaches for automated modeling, mostly for mixed-integer linear programming, which often rely on dedicated training or problem-specific architectures that limit industrial deployment; and agentic artificial intelligence for operational decision support, which generally assumes that the optimization model already exists. This study bridges both directions by assessing whether general-purpose LLMs, orchestrated as agents without task-specific training, can formulate and implement constraint programming models from natural-language problem descriptions. Singleagent and multi-agent architectures are integrated with a Model Context Protocol server that provides context-aware retrieval of solver documentation to mitigate hallucinations during implementation. Both are compared with a direct LLM baseline on six industr

---

### [126] Performance Optimizations for AI-assisted Coding with CodeLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://uwspace.uwaterloo.ca/bitstreams/e5c8f64b-442b-45c6-ba81-37081959539b/download&hl=zh-CN&sa=X&d=12728488314273789332&ei=Z3fHapfLEde46rQPmoOZiAE&scisig=ACTRDVGQdGtgKds2fALYVUQtyksM&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=8&folt=kw-top
**作者**: K Thangarajah
**来源**: 2026
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> that scaling language models yields wide-ranging few-shot capability [18]. Codex first demonstrated that a large language model trained on … to send a new query to [186], and RouterBench provides a standard benchmark for comparing such multi - model

---

### [127] Dialect-Robust Speech Language Models with Synthetic Pseudo-Dialect Augmentation

**链接**: https://arxiv.org/abs/2610.09321
**作者**: Shunsuke Mitsumori, Tomoya Mizumoto, Yusuke Fujita
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech Language Model (SLM) performance often degrades on dialects due to data scarcity. Conventional text-to-speech (TTS) augmentation struggles to cover diverse dialects as it requires a certain amount of real dialect speech. We propose synthesizing pseudo-dialect speech by converting LLM-generated dialect text via a standard-language TTS model, requiring zero real dialect speech. Additionally, we introduce intermediate standard-text prediction during training, acting as semantic normalization for downstream tasks. We evaluate dialect understanding via dialect-to-English speech translation across Japanese, German, and Chinese dialects. Compared to synthetic standard speech baselines, pseudo-dialect augmentation improves scores for Japanese (from 25.38 to 26.24) and German (from 31.57 to 32.47). Furthermore, the intermediate standard-text prediction effectively bridges the semantic gap, boosting performance to 28.26 for Japanese and from 11.67 to 16.37 for Chinese. These results sugge

---

### [128] Large-scale Repository Engineering via Agent-Native Reusable Code Primitives

**链接**: https://arxiv.org/abs/2610.09079
**作者**: Haibo Jin, Peng Kuang, Xucheng Yu, Jerry Wang, Dehao Wu and Haohan Wang
**来源**: cs.SE cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models equipped with development environments have moved code generation toward repository-scale construction, yet building complete repositories remains difficult because interacting modules, interfaces, configurations, tests, and dependencies must work together. We introduce Code Primitives, agent-native reusable executable components with interface contracts, dependency closures, validation tests, and provenance. Each primitive uses a resident LLM to assess relevance and adapt its implementation, interfaces, and dependencies to the target repository, and we organize 1,424 validated primitives in CodeFace, a searchable library for repository construction. We introduce LEGO (Large-scale repository Engineering via aGent-native reusable cOde primitives), which activates task-relevant primitives, integrates their adapted implementations with task-specific code while resolving cross-component constraints, and revises the result against executed tests. To measure constructio

---

### [129] RACER: Reflective Agent Coupling Query Interpretation and Tool-Based Retrieval for Frame Selection in Long Video Understanding

**链接**: https://arxiv.org/abs/2610.08954
**作者**: Yiyang Huang, Yitian Zhang, Yizhou Wang, Jianglin Lu, Qihua Dong, Hailing Wang 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video large language models (Vid-LLMs) excel at diverse video-language tasks by reasoning over selected frames. However, frame selection for long videos remains challenging, as it requires retrieving relevant frames distributed across segments from a large candidate pool given complex queries. This paper investigates dominant approaches to long-video frame selection from a task-decomposition perspective, identifying two key challenges: the Query Comprehension Gap in similarity-based methods and the Interpretation--Selection Gap in judgment-based methods. To address them, we propose RACER, a training-free reflective agentic framework that decomposes long-video frame selection into query interpretation driven by a lightweight Vid-LLM and evidence localization supported by an embedding model serving as a retrieval tool. Specifically, the Vid-LLM is responsible solely for reformulating the complex query into sub-queries that make implicit information requirements explicit, mitigating the Q

---

### [130] Adaptive Code Generation for Controlling Robots

**链接**: https://arxiv.org/abs/2610.09588
**作者**: Justus Flerlage, Thorsten Wittkopp, Alexander Acker, Odej Kao
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying robots as Complex Adaptive Systems (CAS) in unknown and dynamic environments necessitates a transition from rigid command libraries toward intention-based autonomy, as natural language represents the only medium capable of articulating complex goals beyond the capacity of finite instruction sets. While Large Language Models (LLMs) offer a path toward natural language goal description, their integration introduces significant challenges: the formalization gap between imprecise intentions and executable actions, the taxonomy gap induced by unpredictable environments, and the challenge of maintaining temporal state and progress awareness. This work introduces an architectural framework that enables robotic control by leveraging generative AI. The system follows a dual-AI design: an LLM translates high-level intentions into executable program code restricted to a formal robotic library and constrained by verifiable syntax, while a Vision-Language Model (VLM) provides semantic gro

---

### [131] Covariate-dependent Joint Modeling of Multivariate Ordinal Preferences and Its Connections with Comparison Models

**链接**: https://arxiv.org/abs/2610.09070
**作者**: Yujie Chen, Antik Chakraborty, Anindya Bhadra
**来源**: stat.ML cs.LG stat.ME
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multivariate ordinal data along with covariates are commonly collected in problems ranging from alignment of language models with human preferences, as well as in recommender systems. For example, data sets such as MovieLens contain several movies rated on a scale 1--5 by human users, along with their demographic information such as age or gender. Similarly, data sets such as HelpSteer collect human feedback on several attributes such as "helpfulness" or "verbosity" of LLM response on an ordinal scale, with covariates depending on the LLM prompt--response pairs. Unfortunately, the standard approaches for modeling these data (a) look at the attributes individually rather than jointly, and (b) often convert the data into pairwise or list-wise win--loss comparisons for fitting models such as Bradley--Terry and Plackett--Luce. Both of these lead to a coarsening of what is actually observed, which we address via a joint covariate-dependent consecutive ratio Markov random field model. We als

---

### [132] NCU-IISR: BioASQ 14b Phase A/A+, and Phase B Challenge

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4283/paper19.pdf&hl=zh-CN&sa=X&d=10279409345369376168&ei=Z3fHapfLEde46rQPmoOZiAE&scisig=ACTRDVHJqtZOE_kQKuOlS63fbuWw&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=3&folt=kw-top
**作者**: YC Hung, JC Han, HC Hung, RTH Tsai - CLEF, 2026
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In Phase B, we examined dynamic contextual anchoring, cross-generational large language model characteristics, and multi - model ensemble fusion mechanisms to manage factual groundingandformattingcompliance.

---

### [133] PHRBench: A Behavioral Evaluation of Post-Hallucination Reasoning in LLMs

**链接**: https://arxiv.org/abs/2610.10455
**作者**: Linghao Meng, Feng He, Xuan Yang, Junyuan Mao, Pinze Ren, Deqing Mu 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hallucinated information can propagate through multi-stage LLM systems and become part of the context for subsequent reasoning. Existing studies of post-hallucination reasoning (PHR) mainly characterize changes in final outcomes and aggregate reasoning dynamics, leaving how models resolve hallucinated premises at the response level insufficiently understood. In this work, we introduce PHRBench, a controlled benchmark for behaviorally structured PHR across four domains and 18 large language models. PHRBench characterizes each reasoning trajectory independently of final-answer correctness through Hallucination Compliance, Hallucination Avoidance, and Heuristic Correction, and defines an insightful trajectory as successful correction that ultimately reaches the correct answer. Across 4820 controlled instances, we find that successful recovery remains relatively rare and is associated with more frequent belief updates along the reasoning trajectory. We further find that properties of the h

---

### [134] LLM4Impact: Integrating Heterogeneous Information for Scientific Impact Prediction

**链接**: https://arxiv.org/abs/2610.10138
**作者**: Yong Cao, Markus Flicke, Haoyu He, Katrin Renz, Andreas Geiger
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting the future impact of a newly published paper is challenging because it must be inferred from heterogeneous evidence available at publication time. Existing approaches often rely on a single source of information or combine multiple sources without accounting for their different predictive roles. In this paper, we present LLM4Impact, an evidence-aware method for scientific impact prediction that learns to represent, integrate, and calibrate heterogeneous information. LLM4Impact combines semantic, graph, LLM, and temporal representations, and injects graph information into a frozen LLM through continuous prefix tokens. A context aware gating mechanism adaptively weights different evidence, while a separate calibration module accounts for domain and temporal variation in citation scales. We further construct a large-scale benchmark dataset with 2 million papers, leakage-safe point-in-time heterogeneous ego graphs, temporal splits, and both year-level and month-level citation ta

---

### [135] Automatically Building and Updating a Knowledge Graph of MLIP Models

**链接**: https://arxiv.org/abs/2610.09644
**作者**: Alexis Beer, Liudmyla Klochko and Mathieu d'Aquin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complementing the many efforts in providing semantic representations of concepts, notions, and entities in materials science, we report and illustrate a process by which we can automatically build a knowledge graph of the fast evolving field of machine learning applied to the prediction of material properties, focusing on MLIP (Machine Learning Interatomic Potential). This LLM-based process relies on multiple steps, from information extraction in documents and articles to a validation loop using SHACL constraints to detect and correct errors. It is carried out on a model-by-model basis, focusing on the consistency of representation, therefore enabling an iterative construction where the addition of new models is facilitated. We illustrate the process by showing a few interesting aspects that can be queried from a knowledge graph built from the models listed in the Matbench Discovery leaderboard.

---

### [136] RunningTab: Direct Workspace Interaction with Environment-Side Tabs

**链接**: https://arxiv.org/abs/2610.10444
**作者**: Jinheon Baek, Soyeong Jeong, Yumin Choi, Dongsu Han, Sung Ju Hwang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Much knowledge work produces new deliverables from files a workspace already holds, and LLM agents are beginning to take such work over. Through direct corpus interaction, an agent can search and read any of those files from a terminal with no indexing, and producing a deliverable from many of them in this way is what we call direct workspace interaction (DWI). Reaching the files, however, is only half the task: nothing keeps track of what the task asks for, what has been read, and what was listed but never opened, all of which slip through the context window without leaving a trace, so an agent may extract a figure and still deliver a report without it. To address this, we present RunningTab, a framework that equips direct workspace interaction with an environment-side tab: a per-task record of what the task still owes, kept by the environment alongside the agent. Specifically, the agent adds its requirements, while the environment records every file read as an excerpt with its proven

---

### [137] Package Hallucination Attacks on Coding Agents through Prompt Injection in Rule Files

**链接**: https://arxiv.org/abs/2610.09264
**作者**: Yupu Wang, Zhengyuan Jiang, Reachal Wang, Neil Zhenqiang Gong
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern agentic coding frameworks increasingly rely on community-shared rule files (e.g., AGENTS.md or .cursorrules) to guide autonomous code generation, yet the security risks of this pipeline remain underexplored. To bridge this gap, we introduce the package hallucination attack, where an attacker injects malicious prompts into benign rule files to induce coding agents to replace legitimate dependencies with attacker-controlled packages. To obtain effective malicious prompts injected into rule files, we propose PackHallu, an evolutionary optimization framework that iteratively rewrites these injected prompts using trajectory-level feedback and LLM-guided mutations. Evaluations across multiple benchmarks, LLMs, and agent frameworks show that PackHallu achieves high attack success rates and strong transferability across diverse models and agent combinations. Our findings demonstrate that coding agents are vulnerable to package hallucination attacks, highlighting the urgent need for stro

---

### [138] Sigma-Hunter: A Domain-Specific Language Model for Threat Hunting and Detection Engineering

**链接**: https://arxiv.org/abs/2610.09007
**作者**: Kemal Davaslioglu and Sastry Kompella
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detection engineers must translate threat reports, forensic observations, and hunt hypotheses into precise, testable rules. General-purpose large language models (LLMs) can draft such rules, but often produce invalid YAML, incorrect log sources, unsupported fields, or overly broad detection logic. This paper presents \emph{Sigma-Hunter}, a domain-adapted LLM for analyst-assistive Sigma rule generation and threat hunting. We build an instruction-tuning dataset from 3,635 validated open-source Sigma rules, expanded into 7,663 question-answer and analyst-reasoning examples. Each source rule is assigned to a single train, validation, or test partition before this expansion, so no rule leaks across splits. We fine-tune a 7B Mistral model and a Phi-4 model with LoRA and score held-out rule generations on syntax, approximate field consistency, and a semantic judgment of detection logic, completeness, selectivity, and log-source alignment. Sigma-Hunter-Mistral scores 8.17 overall, against 7.88

---

### [139] Rephrase Before You Act: Characterizing and Mitigating Language Sensitivity in Vision-Language-Action Models

**链接**: https://arxiv.org/abs/2610.10526
**作者**: Mikey Watts (Independent Researcher), Yuchen Cui (University of California, Los Angeles)
**来源**: cs.RO cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language-action models (VLAs) are strikingly sensitive to instruction phrasing and do not inherit the language robustness of the vision-language models they are built on. A one-word edit can move success by tens of points: $\pi_{0.5}$ turns on a LIBERO stove 100% of the time for "switch on the stove" and 2% for "switch on the hot plate", and a $\pi_0$ checkpoint finetuned with rephrase augmentation still shows swings of up to 61 points. We characterize this sensitivity with statistically tested single-edit swings and an oracle phrase search, which shows that phrasing alone nearly closes the 21-point gap between in-distribution and out-of-distribution tasks. We then reduce it without modifying the policy. Because the sensitivity is systematic, it can be expressed as explicit rules: we score many phrasings of a few training tasks, have a large language model distill the evidence into ten to twenty rephrasing rules, and at deployment rewrite each incoming instruction once under the

---

### [140] From Probabilities to Decisions: Search and Multi-Teacher Distillation with Jev

**链接**: https://arxiv.org/abs/2610.09188
**作者**: Mohamad Yazan Sadoun, Sarah Sharif, Yaser Mike Banad
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Probability-only models, which TypeSafe calls System One models, return calibrated probabilities for fixed choices in milliseconds and generate no text. We study one such model, Jev, through two tasks that require decisions under tight constraints. In bullet chess, a bot that places Jev's judgment inside Stockfish search alongside an opening book and endgame tablebases climbs above a 2200 Lichess bullet rating against other bots. Live model calls are too slow for search, so we distill pairwise judgments into a compact evaluator that runs at every position. We then ask how best to spend a fixed labeling budget when an LLM, Qwen3-32B, is available as a second teacher. In chess, averaging both judges' labels beats spending the whole budget on Qwen alone by 9.6 Elo (95% interval 4.3 to 14.9), and the gain replicates on fresh openings; a second answer from the same judge is no substitute, and Jev is the strongest partner for Qwen among the models tested. In passage reranking, Jev's labels a

---

### [141] SkillForge: Co-Evolving Skills and Agents via Dynamic Skill Lifecycles

**链接**: https://arxiv.org/abs/2610.09832
**作者**: Yuyao Ge, Yiwei Wang, Yuchen He, Baolong Bi, Lingrui Mei, Jiayu Yao 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-augmented reinforcement learning strengthens LLM agents' ability to solve complex long-horizon tasks. Skills are one such form of memory, pairing instructions with an applicability condition over task types. However, retaining every skill indiscriminately as the policy improves lets obsolete or harmful entries accumulate and mislead the agent. We propose SkillForge, an agentic RL method that compiles and evolves the skill library through a fitness-driven skill lifecycle of trial, active, stable, and retired states, so that the skills and the model co-evolve throughout training. A pre-RL evaluation phase first uses the base model's own rollouts to pre-retire low-fitness skills, yielding a filtered library that then seeds supervised fine-tuning. Reinforcement learning takes over from this checkpoint, and at each iteration selective retirement, stabilization, and LLM-guided mutation continue to forge the skill library alongside policy optimization. Across multiple interactive agent

---

### [142] Constrained-Action AI Remediation for SIEM/XDR via a NeMo-Guardrails Proxy

**链接**: https://arxiv.org/abs/2610.09906
**作者**: Georgios Koutidis, Nikolaos Kekatos, Tom Nianios, Alexios Lekidis
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Security Operations Centers (SOCs) for information technology and operational technology share one incident-response problem: a flood of correlated alerts and too few analysts. Large Language Models (LLMs) are increasingly proposed as reasoning engines that triage alerts and, in autonomous deployments, issue commands that block IPs, kill processes, or quarantine files on production hosts. This coupling introduces a new risk: a single adversarial alert can become a remote code path through the LLM's reasoning, leading it to recommend an action the SOC then executes. We present a constrained-action architecture with two coordinated layers: (i) a SIEM/XDR control plane that grounds remediation in correlated host events and confines the LLM's output to a closed intent vocabulary whose templated commands are executed by thin endpoint agents, backstopped by an argument validator; and (ii) a NeMo-Guardrails proxy that wraps the SOC-analyst LLM with input- and output-rail policies, evaluated o

---

### [143] Sequential Probabilistic Uncertainty Estimation for Parallel Multi-Agent Reasoning Systems

**链接**: https://arxiv.org/abs/2610.08901
**作者**: Tunyu Zhang, Zihao Zhao, Yusong Zhao, Haizhou Shi, Zhuohang Li, Haoxian Chen 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) have attracted growing attention for improving reasoning through interaction among multiple agents. In this work, we focus on parallel multi-agent reasoning systems, where several agents solve the same problem over multiple rounds and aggregate their outputs into a final answer. Despite their strong reasoning performance, uncertainty estimation for such systems remains underexplored: the reliability of a MAS depends not only on individual generations, but also on how agents interact and evolve across rounds. We propose SAUCE (Sequential Agent Uncertainty through Consensus Evolution), a lightweight, training-free uncertainty estimator that formulates MAS uncertainty as sequential inference over a latent system-level belief. SAUCE aggregates round-level agreement and generation-uncertainty signals through a filtering-style update. Across five backbones, five benchmarks, and two MAS protocols, SAUCE improves misclassification detection, selective predic

---

### [144] The Confidence Game: Strategic Miscalibration in Human-AI Delegation

**链接**: https://arxiv.org/abs/2610.09371
**作者**: Raghu Arghal, Saswati Sarkar, and Shirin Saeedi Bidokhti
**来源**: cs.GT cs.AI cs.CL cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Calibrated uncertainty quantification is essential to ensuring AI agents are trustworthy and reliable. However, when agents seek to maximize user engagement or revenue, confidence reports may be strategically distorted, detracting from their informativeness. We formalize this problem in the Confidence Game: a repeated signaling game with imperfect monitoring in which an agent of unknown honesty and ability reports its confidence, and a user decides whether to delegate the task or complete it herself. The agent manages the tradeoff between manipulating signals and maintaining its reputation. We characterize the Markov Perfect Bayesian Equilibria of the two-period game and show that honest reporting is not an equilibrium, inflation is the unique best response once the agent is sufficiently myopic, and under-reporting requires that the user believe honesty to be a minority. We then place an LLM in the agent role, supplying it with its true probability of success so that any gap between wh

---

### [145] Few Bits, One Law: Toward W2A4KV2

**链接**: https://arxiv.org/abs/2610.09202
**作者**: Kai Yi, Tarek Elgamal, Sruthikesh Surineni, Vignesh Vivekraja, Soumyadeep Ghosh, Steven Li
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extreme low-bit LLM compression is most challenging when weights, activations, and KV caches are quantized together: their distributions differ, and quantization errors interact throughout the network. We introduce CanonQ, a unified quantization-aware training framework that addresses these challenges by separating source canonicalization from task-aware adaptation. Fixed rotations and energy normalization map heterogeneous tensor sources to canonical coordinates, enabling frozen Gaussian-reference codebooks to be reused across layers and models. Joint training then adapts the network to the coupled errors of weight, activation, and cache quantization within a common scalar/vector interface. We bound frozen-codebook transfer error and local task loss, and derive an exact normalization-aware straight-through Jacobian that links quantization distortion to gradient bias. The strongest gains arise under joint W2A4KV2 compression: across LLaMA3-1B/3B/8B, CanonQ-Omni achieves up to 14.28x lo

---

### [146] We Query, Therefore We Compute: On Oracle Computation beyond the Machine, with an Application to Agents

**链接**: https://arxiv.org/abs/2610.09243
**作者**: Kefan Liu, Fengning Ou, Yelin Luo, Jingdi Lei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic systems use large language models (LLMs) to carry out concrete tasks. Prior work often borrows abstractions such as scheduling, caching or isolation piecemeal from operating systems, so the mechanisms it builds share little common ground, and the shared view of the two forms of agentic system, Workflows and Agents, is limited. We construct an abstract machine that provides both. We treat the LLM as an Oracle and extend a two-stack pushdown automaton with one instruction, which hands the Oracle a whole stack as its query and appends the answer to that same stack. The machine thus performs two computations, the Oracle's and a Turing-complete one that we call the Priestess. A stack that the program only appends to grows autoregressively, as an agent's context does. Two symmetry breakings, S in storage and T in transitions, make a Priestess program the operating system of the programs the Oracle runs, and produce the Agent and the Workflow as the two placements of a task's program.

---

### [147] Robust Decentralized Fairness Auditing

**链接**: https://arxiv.org/abs/2610.10199
**作者**: Sayan Biswas, Jade Garcia Bourr\'ee, Anne-Marie Kermarrec, Palak, Martijn de Vos
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emerging legislation requires large language models (LLMs) to be audited for compliance with regulatory standards, particularly fairness. Such black-box audits typically assume a single auditor with access to a large, representative set of queries. In practice, it can be difficult for an auditor to obtain such a query set, but multiple auditors can together cover the relevant demographic groups by auditing the LLM collaboratively with their individual query sets. However, relying on multiple auditors raises a fundamental trust problem, as they may act on behalf of the LLM provider to portray a misleading appearance of fairness, i.e., fairwashing. We propose Auditopus, a novel approach for robust decentralized fairness auditing. In Auditopus, auditing proceeds in rounds without a central server. In each round, every auditor issues a fixed number of queries to the LLM, and sends only cumulative statistics vectors of its query results to other auditors instead of sensitive queries in clea

---

### [148] Move Fast and Mend Things: Keeping Up with Evolving AI Harms Using Social Media Commentary

**链接**: https://arxiv.org/abs/2610.09082
**作者**: Jacqueline Rowe, Animesh Srivastava, Sai Teja Peddinti, Seliem El-Sayed, Nina Taft
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid deployment of AI systems has created socio-technical, psychological, and operational harms that can elude ex-ante threat modelling and ex-post incident tracking. We introduce an LLM-assisted thematic analysis pipeline to dynamically detect, categorise, and track emerging AI harms from large-scale social media data. Applying it to 5.7 million Reddit post summaries over 18 months (01/2025 to 06/2026), we curate and release a dataset of 575,000 AI harm-related posts and a bottom-up AI harm taxonomy of 12 categories and 47 subnodes. The taxonomy reliably covers established expert-defined risks while surfacing granular harms that top-down frameworks overlook, such as distinct forms of AI privacy violations. Temporal analysis surfaces evolving user-centric harms, such as agentic privacy and security breaches, premature AI adoption in the workplace, and grief from AI companion discontinuation. Our pipeline shortens harm-detection timelines and hereby complements efforts towards more

---

### [149] Task-Oriented Key-Layer KV Communication for Efficient Latent Multi-Agent Collaboration

**链接**: https://arxiv.org/abs/2610.08820
**作者**: Dongsen Zhang, Peipei Li, Zekun Li, Wenjun Xu
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based multi-agent systems improve complex problem solving through collaboration, while latent communication directly transmits model internal states to avoid the high inference costs of natural language. However, existing KV-based latent communication methods prioritize sender-side state fidelity, leading to substantial communication and computation overhead and potentially introducing redundant information. To address these limitations, we revisit latent communication from a task-oriented perspective, shifting its objective from sender-side state fidelity to receiver-side task sufficiency. Under this formulation, we propose KITE, a training-free framework for task-oriented key-layer KV communication. KITE identifies a task-effective key layer using a receiver trajectory distortion criterion, transmits only the latent working memory associated with the key layer, and further uses the same layer as the entry point for autoregressive latent reasoning. Experiments on 

---

### [150] PatchBench: Measuring Collateral Damage in Activation Patching

**链接**: https://arxiv.org/abs/2610.10276
**作者**: Alexi Canesse, Mathis Le Bail, Ma\"el Jenny, Cl\'ement Elliker, Mahammed El Sharkawy, Sonia Vanier
**来源**: cs.LG cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM safety patch can pass a benchmark while still being a poor repair. This risk is especially acute for jailbreak repairs, where the goal is to correct a specific unsafe behaviour without changing unrelated behaviours. A patch may block exact evaluation prompts yet fail on close harmful variants, or suppress harmful behaviour by over-refusing benign prompts that share its wording or structure. Existing protocols primarily test whether models can be broken, while aggregate metrics (attack success, refusal rates, global capability) cannot distinguish selective repairs from broader local suppression. To address this gap, we introduce PatchBench, a benchmark of empirically observed model-specific jailbreak failures inducing actionable harmful answers. Starting from 27,870 prompts from 37 public datasets, we curate 15,314 English prompts and query 8 open-source instruction-tuned models. Combining WildGuard filtering, pairwise Elo ranking, and manual verification, we retain a curated ban

---

### [151] Validity Without Ground Truth: What Stated-Preference Economics Offers the Evaluation of Language Models

**链接**: https://arxiv.org/abs/2610.10506
**作者**: Daniel Robert Kling Alexander and Catherine Louise Kling
**来源**: cs.AI cs.CL econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many of the questions now put to large language models have no correct answer to score against: what a policy is worth, which option a user should choose, how to weigh competing values. Stated-preference economics has faced this problem for decades. It judges survey responses without knowing the true value, through a framework of validity and related concepts: content, construct, and criterion validity, reliability, incentive compatibility, and consequentiality. We argue that this framework is a general method for evaluating language models, and we set out what each concept means for LLM evaluation. We demonstrate the approach using a published water-quality stated preference economic valuation survey (Vossler et al. 2023) administered to six models. In this economic application, the validity tests take the form of predictions from economic theory: demand should slope down, and willingness to pay should respond to the scope of the good and to income. The tests separate the models sharp

---

### [152] HGP:An on-device personalized agent memory via hybrid graph storage

**链接**: https://arxiv.org/abs/2610.10071
**作者**: Ran Zhou, Xueming Han, Jiaheng Liu, Yuyao Zhang, Fanyu Meng, Junlan Feng 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents face challenges in personalized interactive tasks due to heterogeneous, multi-typed, and implicitly constrained long-term traces. Existing memory mechanisms struggle with accurate routing and retrieval, especially on-device where personalization is critical. Most methods use single-vector representations, blurring type distinctions and relational structure. We propose HGP, a hybrid graph memory framework. HGP employs a lightweight self-enhancement classifier for personalized memory routing and constructs episodic, semantic, and procedural memories as graphs. It also extracts working memory as a state trajectory to capture current state and implicit constraints, ensuring reliable decision-making. The classifier reduces large-model calls, enabling on-device deployment, while graph storage enables accurate retrieval and incremental user profile refinement. Experiments on two benchmarks show that on PAL-Set solution selection, HGP achieves an S-score of 35.58, nearly 7 poi

---

### [153] CIRRA: Dual-Level Continual Instruction Reconciliation with Ongoing Execution for Embodied Robot Agents in Interactive Household Tasks

**链接**: https://arxiv.org/abs/2610.08862
**作者**: Ci Zhang, Enfu Nan, Arman Akbari, Lin Zhao, Li Wang, Chen Wang 等 (9 人)
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Household robots must accommodate new user instructions while executing ongoing tasks. Existing agents often regenerate or extensively revise the remaining task sequence, introducing plan ambiguity, logical inconsistency, and redundant execution. We formulate continual instruction reconciliation and propose CIRRA (Continual Instruction Reconciliation for Robot Agents), a dual-level framework combining LLM-based semantic reasoning with rule-constrained structural integration. CIRRA first grounds incoming instructions to unique executable skills and resolves underspecified actions and execution locations. It then preserves the ongoing subtask sequence as an execution backbone and generates integration candidates by inserting incoming subtasks into location-matched segments. The semantic reasoner evaluates only modified segments to identify dependencies and conflicts and select the most logically coherent local integration. This structure-preserving process maintains alignment with ongoin

---

### [154] Stale, Misattributed, or Late: Where Personal Memory Fails Before Generation

**链接**: https://arxiv.org/abs/2610.10265
**作者**: Haonan Deng, Park Sinchaisri
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal memory for language agents is usually judged by whether the final an- swer is correct. That score hides errors that arise before generation: the memory block may contain an obsolete value, a fact about the wrong person, or no use- ful fact before the serving deadline. We measure these failures directly. Using Personal Fact Memory (PFM) as a reference layer, we find that temporal validity is primarily a property of memory construction in our setting. On a controlled revision benchmark, serving only the active value of each correctly keyed slot eliminates observed stale exposure; without update resolution, 70.3% of prompts expose a superseded value. Once retrievers share the same active store and par- ticipant information, participant-aware BM25 is equivalent to the reference ranker within a prespecified 0.02 margin. The harder problem is assigning revisions to the right slot. Missed merges leave stale values active, whereas false merges silently remove current values; four LLM 

---

### [155] Before Bringing It Up: When and How AI Companions Should Use Memor

**链接**: https://arxiv.org/abs/2610.09470
**作者**: Zihan Guo, Roxy He, Junwei Quan
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory can sustain AI companionship, yet even accurate recollection can be inappropriate to use. Two rounds of formative interviews with 14 users (n = 6 exploratory, n = 8 memory-focused) motivate asking what a companion should consider before using past information. Eight themes inform Reconsider, a single-call procedure with five checks and four handling modes, evaluated on 80 scenarios across five models over 400 blinded within-model pairs. Two LLM judges favored Reconsider by net margins of +15 and +23 percentage points, with bootstrap intervals excluding zero for three of five models but not for GPT or Claude. Evaluator analysis linked judge scoring differences to model family, and a preliminary matched-guidance control isolating memory-specific content gave positive margins. We contribute an interview-grounded design framework for memory use and an evaluation that scrutinizes its own evaluators.

---

### [156] Emo-Jev: Probabilistic Reasoning for Emotion Classification with Jev

**链接**: https://arxiv.org/abs/2610.08829
**作者**: Yazhou Zhang and Junhao Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jev offers an alternative interface for language understanding: given an input and predefined questions, it returns probabilistic decisions rather than free-form responses. Whether this interface can support effective reasoning for text classification against leading LLMs remains an open questions. We introduce Emo-Jev, a training-free framework with two complementary implementations. Emo-Jev-D decomposes classification into task-specific atomic judgments and composes their probabilities into a final prediction. Emo-Jev-SC constructs multiple judgment paths from complementary perspectives and aggregates their predictions into a consensus decision. We evaluate Emo-Jev on eight datasets spanning sentiment analysis, emotion recognition, sarcasm detection and humor detection, comparing against direct Jev classification and five SoTA LLMs under input/output and chain-of-thought reasoning. Standard Jev achieves 62.93\% average macro-F1 versus 67.28\% for the strongest LLM baseline, with lowe

---

### [157] Relevance Is Not Sufficiency: What Actually Closes the Evidence Gap in Long-Term Memory QA

**链接**: https://arxiv.org/abs/2610.09348
**作者**: Yufeng Li, Shuxin Li, Zhenhua Xu, Junxian Li, Peng Zeng, Sheng Yao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that interact with a user across many sessions accumulate histories that exceed their context window, so they store past interactions in an external memory and answer each question from a small set of retrieved records. Existing memory systems rank records by lexical or embedding relevance, yet the top-ranked memories can each be relevant while jointly omitting a complementary fact that the answer requires, especially for multi-session and temporal questions. Drawing on the distinction between relevance and sufficiency in legal evidence scholarship, we recast memory retrieval as constructing a sufficient memory set. To operationalize this view, we introduce a blinded LLM judgment over the retrieved set, together with Gold Hit and Turn Hit as evidence-coverage proxies. We then propose Budgeted Flat Reconstruction (BFR), which builds sufficient sets over a fixed flat memory store in two stages. Specifically, we first apply Formal Concept Analysis for Memory Selection (FCA-MS) 

---

### [158] Autonomous Active Directory Exploitation via Multi - Model Harness Orchestration: A Benchmark Study with NeuroSploit on GOAD

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.04243&hl=zh-CN&sa=X&d=1552029352408351175&ei=Z3fHapfLEde46rQPmoOZiAE&scisig=ACTRDVEQXYV4KiO9rRO4wmpVgiQ3&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=2&folt=kw-top
**作者**: JAS Barbosa - arXiv preprint arXiv:2610.04243, 2026
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> While recent work has demonstrated that large language models (LLMs) can autonomously conduct assumed-breach penetration testing against AD environments, these studies employ standalone LLM agents that lack structured guardrails

---

### [159] CANDO: Cooperative Agentic Network for Layout Design Optimization

**链接**: https://arxiv.org/abs/2610.10044
**作者**: Athanasios Masouris, Zheng Jing, Benjamin Sam Chandler, Hadi Jamali-Rad
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Layout generation for real-world facilities is a challenging problem, requiring reasoning over irregular site boundaries, heterogeneous orientations, access-aware placements, and motion-planning feasibility. Yet, most existing layout benchmarks in the generative AI space target simpler placements over rectangular domains and rely on distributional metrics such as FID and IoU that reward conformity to dataset priors, thus discounting design innovation. Motivated by these gaps, we introduce ALPS-Bench, a benchmark of $1,000$ professionally annotated real-world facility layouts paired with an instance-specific scoring protocol grounded in a structured design manual. As a strong baseline for ALPS-Bench, we propose CANDO, a training-free multi-agent framework in which specialized agents iteratively refine layouts through a verification-grounded loop, concentrating reasoning on strategic spatial decisions. We demonstrate that CANDO surpasses state-of-the-art trained and LLM-based baselines o

---

### [160] UniSkill: Learning Actor-Aligned Skill Proposals for an Evolving Policy

**链接**: https://arxiv.org/abs/2610.10164
**作者**: Yifei Lu, Cheng Liu, Dianzhi Yu, Hui Xiang, Ji Zhang, Yuanchu Xiao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can improve across tasks by retaining reusable skills distilled from prior interactions. Recent work jointly optimizes task execution and skill extraction, enabling the policy and skillbank to co-evolve. However, as the actor continues learning, rewarding skill proposals through their reuse in subsequent training steps may conflate skill benefits with actor improvement, while directly testing each proposed skill requires costly additional actor rollouts. In this paper, we introduce UniSkill, which uses a shared policy to interact with the environment and propose skillbank edits (Add, Update, or No Edit) from the resulting trajectories. Specifically, the actor learns from environment rewards, while contrastive action feedback guides skill proposal learning. This feedback provides an actor-alignment signal by measuring how replacing the retrieved skill with a proposed skill changes the current actor's action log-likelihood gap between previously collected succ

---

### [161] Not Every Call Needs a Frontier Model: Per-Call-Site Evaluation of Small Language Models in a Deployed Agentic Home-Automation System

**链接**: https://arxiv.org/abs/2610.09021
**作者**: Panagiotis Kasnesis, Christos Chatzigeorgiou, Lazaros Toumanidis, Amalia Contiero Syropoulou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agentic system issues several structurally different kinds of LLM calls. It routes intent, classifies actions, grounds language in a device registry, plans multi-agent pipelines and writes the Python code those pipelines run. The difficulty of these call sites varies by an order of magnitude, yet in practice a single model, chosen for the hardest site, serves all of them. In this work, we evaluate 9 models from 0.8B to a frontier hosted model across the five call sites of a deployed open-source home-automation framework (Wactorz), using its unmodified production prompts and two real Home Assistant installations (280 cases, 2520 scored calls). We find that capability is not ordered the same way at every site, and that larger models are not uniformly better: one 4B model is worse than its 2B sibling at grounded actuation. Paired testing shows the best local model to be statistically indistinguishable from both hosted models at four of five sites. Only code generation separates them, a

---

### [162] CircuitATLAS: Agentic reasoning over a systems neuroscience knowledge graph for target discovery in circuitopathies

**链接**: https://arxiv.org/abs/2610.09643
**作者**: Gabriel Ocana-Santero and Marko Tvrdic
**来源**: q-bio.QM cs.AI q-bio.NC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Drug discovery for neurological disease has traditionally centered on the molecules altered by disease. But the molecules that cause pathology are not necessarily the best points from which to reverse it. Here, we ask which otherwise unaltered molecular control points can be engaged to restore pathological neural circuits toward functional states. We present CircuitATLAS, a provenance-grounded systems-neuroscience knowledge graph and agentic framework for target discovery in circuitopathies. It structures literature-derived relationships across diseases, phenotypes, electrophysiology, circuits, brain regions, cell types and molecular effectors, while deliberately excluding direct disease-gene and disease-protein edges to reduce shortcut reasoning. The graph contains 3.83 million nodes and 7.66 million edges, including 5.31 million LLM-extracted relations, and incorporates structured datasets such as the Human Cell Atlas and new multimodal in vivo measurements. We then introduce an agen

---

### [163] Shaer: Controlled Arabic Poetry Generation with Meter Subform and Semantic Conditioning

**链接**: https://arxiv.org/abs/2610.09756
**作者**: Ahmad Abbas, Tamara Fakih, Nour Fakih, Ammar Mohanna
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classical Arabic poetry generation requires simultaneously satisfying semantic, linguistic, and fine-grained prosodic constraints. Existing systems typically control broad poetic attributes but do not jointly model semantic intent, meter subform, and poem length. We present Shaer, a controllable Classical Arabic poetry generation framework jointly conditioned on natural-language descriptions, meter subforms, and target hemistich counts. To support this task, we construct an enriched corpus of 116,032 classical Arabic poems derived from Ashaar, containing normalized meter-subform labels and automatically generated, validated semantic descriptions. We then adapt Yehia-7B using QLoRA-based supervised fine-tuning with a completion-only objective. Our evaluation combines automatic assessment of base-meter conformity, requested-subform adherence, and length control with three LLM judges, blinded human evaluation, and memorization analysis. Shaer achieves 95.17% base-meter accuracy, 91.75% po

---

### [164] MoR-MLLM: Mixture of Recursions for Efficient Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2610.08830
**作者**: Pengcheng Zheng, Chaoning Zhang, Jiaxin Yan, Sihan Cao, Jianwei Zhang, Xudong Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable reasoning capabilities across vision and language tasks. However, their massive computational and memory demands hinder real-world deployment. While recent efforts reduce costs by employing lightweight language backbones, existing paradigms remain computation-dense due to their static sparsity and depth allocation, which cannot adapt to the semantic complexity of each token. To this end, we propose MoR-MLLM, a computation-sparse MLLM based on the recent Mixture-of-Recursions (MoR) framework. MoR-MLLM introduces adaptive per-token recursion, allowing the model to dynamically adjust its recursive depth and allocate more computation to visually or linguistically challenging tokens while skipping redundant operations for simpler ones. To stabilize the training of recursive sparsity in multimodal settings, we further design a three-stage MoR-Tuning strategy and an entropy-regularized loss to encourage diverse routing dist

---

### [165] Open-MMUnlearning: Unifying Methods and Evaluation for MLLM Unlearning

**链接**: https://arxiv.org/abs/2610.10358
**作者**: Junkai Chen, Yuhao He, Qianshan Wei, Junxiang You, Jingwen Shao, Junkai Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As multimodal large language models (MLLMs) become more capable and widely deployed, concerns about privacy and safety have become increasingly pressing. Machine unlearning offers one approach to addressing these concerns by removing designated information from trained models while preserving unrelated capabilities. However, fragmented implementations and evaluation protocols, incomplete robustness testing, and limited understanding of metric reliability make progress in MLLM unlearning difficult to assess systematically. We introduce Open-MMUnlearning, an open-source, extensible framework that integrates target-model preparation, multimodal data processing, unlearning, and evaluation through shared interfaces and structured configurations. The framework supports five benchmarks spanning privacy, safety, and copyright, eight MLLMs from four model families, and twelve unlearning methods. Its evaluation suite jointly assesses forgetting effectiveness, retained utility, and robustness to 

---

### [166] Behavior Pack Optimization for Video MLLM Post-Training

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.03141&hl=zh-CN&sa=X&d=5124495380523741739&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVGq7sQCMaDYyDZ6ftvnRixW&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: Z Kang, S Liu, T Luo, W Zhang, Y He, L Wei 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Video multimodal large language models (MLLMs) keep climbing video question answering benchmarks, yet shuffling the frames, masking the segment that supports the answer, or occluding the target object barely changes their predictions. The

---

### [167] TerraVis: Towards Evaluation of World-Grounded Visual Consistency in Text-to-Image Generation via MLLM Workflows

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.02959&hl=zh-CN&sa=X&d=2715710626042110151&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVGuwzJB_ej-5W8mMJX8lZFc&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: S Fu, J Gu, J Zhou, Z Duan, G Zhou, Q Wu - arXiv preprint arXiv:2610.02959 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Recent text-to-image models have made substantial progress in photorealism, aesthetics, and text-image alignment. Yet visually appealing images can still violate real-world plausibility, exhibiting malformed object structures, impossible anatomy

---

### [168] CLINIC-VQA: Reasoning-Aware MLLM with Explicit Clinical Reasoning Traces for Medical Visual Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://papers.miccai.org/miccai-2026-sat/paper/MedReason_003.pdf&hl=zh-CN&sa=X&d=18152337502305350434&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVEgTO1TqcNzD5ieRMW51yuO&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: S Kondo, S Kasai
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study proposes a reasoning-based MLLM that visualizes the inference process to address the challenges of black-box behavior in Medical Visual Question Answering and to provide verifiable reasoning evidence for generated answers

---

### [169] Can Your Agent Read the Source Faithfully? Benchmarking MLLM Agents on Source-Grounded Multimodal Retrieval

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3DTK0X7eSPyx&hl=zh-CN&sa=X&d=2409464839031689037&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVF7JxLT79YppCIYQHlzHjIw&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: W Gao, S Huang, J Zhuang, A Garg, MH Rahman…
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multimodal agents are increasingly evaluated on their ability to search the web, invoke tools, and solve complex tasks autonomously. Yet no existing benchmark systematically evaluates the capability of autonomously searching, parsing, and

---

### [170] FlashGaze: Training-Free Multi-Scale Patch Pruning For Efficient Video Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.04225&hl=zh-CN&sa=X&d=6700417123227187411&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVE2cIXUAG2XVJOiZGFFpEmm&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=9&folt=kw-top
**作者**: Z Zhu, Y Zhou, L Tan, J Kang, S Li, X Yang - arXiv preprint arXiv:2610.04225 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> 1, they prune visual tokens only before or inside the MLLM . Consequently, part or all of the ViT, and even several MLLM layers in some cases, still process the full set of visual tokens. The later token pruning is applied, the more unnecessary

---

### [171] Beyond Anonymous Captions: Grounding Character Identity in Video Captioning and Question Answering

**链接**: https://arxiv.org/abs/2610.10163
**作者**: Anas Filali Razzouki, Killian Steunou, Khalil Guetari, Thomas Kling, Moun\^im El-Yacoubi, Yannis Tevissen
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linking people's appearance and actions to character identities is essential for understanding video narratives. We present a framework for identity-aware video captioning and person-centric question answering that combines automatic character identification, explicit spatial grounding, and task-specific adaptation. Starting from LSMDC v2 movie clips, our pipeline matches detected faces to actor reference images, tracks characters across frames, and builds inputs with identity-linked bounding boxes. A strong vision-language model generates identity-aware captions and questions, which are manually verified and filtered to create a benchmark of 750 captioned clips and 3,000 person-centric questions. We study five grounding strategies combining textual coordinates with visual face or estimated person boxes across Video-MLLM families at roughly 2B, 4B, and 8B parameters and larger frontier models. Combining visual face boxes with textual coordinates yields the most consistent performance a

---

### [172] Strong Helps Weak: Directional Cross-Modal Alignment Transfer in Multi-modal LLMs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.04580&hl=zh-CN&sa=X&d=12188037659807491096&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVHZKxQekGvOHmImHxfmj3_N&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=7&folt=kw-top
**作者**: H Seo, BH Lee, M Kim, D Mah, J Lee, SY Chun - arXiv preprint arXiv:2610.04580 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> However, improving an MLLM ’s capability for a given modality typically requires additional … source-modality MLLM into a data-scarce target-modality MLLM substantially improves the … quantities and strongly correlated with downstream

---

### [173] IRSTD-Agent: Agentic Infrared Small Target Detection via Zoom-Guided Interaction Learning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.05342&hl=zh-CN&sa=X&d=16885141067893160190&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVHGXTvubJu0pIKcB7rqNI_l&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=6&folt=kw-top
**作者**: J Xi, Y Zhang, T Zhao, Z Liu, M Yuan, X Wei - arXiv preprint arXiv:2610.05342 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> , our approach enables an MLLM to actively acquire … MLLM to guide this search, we introduce Zoom-guided Interaction Learning (ZIL), which uses annotation-derived interaction trajectories to supervise tool selection and the corresponding arguments

---

### [174] "I'm Very Happy for It to Start Hallucinating a Little Bit": Using ClayFlect to Negotiate Multimodal AI Representations in Material Meaning-Making

**链接**: https://arxiv.org/abs/2610.08943
**作者**: Kellie Yu Hui Sim, Quoc-Nam Nguyen, Shuenn Yuen Han, Kenny Tsu Wei Choo
**来源**: cs.HC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI enters reflection and emotional support, understanding how it can participate in personal meaning-making while preserving users' authority over interpretation is increasingly important. We present ClayFlect, a novel MLLM-powered system integrating tactile clay-making with conversational and visual generative AI, and report a mixed-methods study with 50 participants. Reflection developed across material, conversational, and generated forms rather than through AI interaction alone. Participants treated AI representations as provisional: they compared, redirected, reinterpreted, selectively incorporated, or left them aside as their artefacts and meanings evolved. Clay provided a directly manipulable space in which participants could continue developing meaning independently of the AI, while generated representations externalised possibilities beyond what they could readily make or visualise. We show how generative AI can participate through representations that remain negotiable, an

---

### [175] Which Tool Response Should I Trust? Towards Tool-Expertise-Aware Chest X-ray Agent with Multimodal Agentic Reinforcement Learning

**链接**: https://scholar.google.com/scholar_url?url=https://papers.miccai.org/miccai-2026-sat/paper/MedAgent_006.pdf&hl=zh-CN&sa=X&d=7652079635908255348&ei=Z3fHarb0GYGu6rQP-YzbyAU&scisig=ACTRDVH4IJCG0tCqzgyeIJdnBveR&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=5&folt=kw-top
**作者**: Z Huai, H Yang, X Li - Update
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> 2, the rollout τ in this paper is the concatenation of interleaved MLLM -generated tool-calling tokens and tool responses. We use <tool_call> … as the input to generate the MLLM response in the next turn. The rollout process stops when the

---

### [176] ZeroMAG: Zero-Shot Multimodal Adapter Generation for Plug-and-Play EEG Foundation Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.03546&hl=zh-CN&sa=X&d=13763578947481447322&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVFIAjG56svP6WpQZJEdX1-0&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: Y Wang, J Ma, X Zhou, Y Zhou, J Wang, S Zhao… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> data, while many EEG recordings also include companion physiological signals that provide complementary information beyond the EEG -… We introduce ZeroMAG, a zero-shot multimodal adapter generation framework that extends a frozen EEG

---

### [177] An EEG -based motor imagery intention decoding framework for smart vehicle window control

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426021828&hl=zh-CN&sa=X&d=2182219014839869567&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVGZGMU52WF_gG8E1Ftmm_q4&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: Y Guo, T Zhang, J Cai, L Deng, Z Gao - Biomedical Signal Processing and Control, 2027
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> , and non-Euclidean topology of EEG signals. This study proposes Brain2AutoWin (B2AW), an EEG -based MI intention decoding paradigm … A 32-channel EEG dataset was collected from 20 healthy participants in a high-fidelity driving

---

### [178] Multimodal LLMs Can Learn to Read Brain Signals: A Vision--Language Model for Unified Multi-Task EEG Decoding

**链接**: https://arxiv.org/abs/2610.09355
**作者**: Parastoo Azizeddin, Omid Sharafi, Maryam M. Shanechi
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning EEG representations that generalize across cognitive tasks, subjects, and recording conditions remains a key challenge in electroencephalography (EEG) decoding. Recent advances in foundation models have improved EEG decoding performance, yet a fundamental open question remains: how to effectively interface neural signals with these models to enable multi-task learning across datasets. To investigate this question, we introduce BraVista, a visual-language framework that encodes multichannel EEG signals as structured images and enables multi-task learning through instruction-conditioned vision-language models (VLMs). Our approach relies on continued post-training of a general-domain VLM, leveraging its visual and linguistic priors to adapt to neural signals without a separate large-scale EEG-specific pretraining stage. We evaluate BraVista on four datasets spanning sleep staging, emotion recognition, cognitive workload classification, and abnormal EEG detection, showing strong p

---

### [179] EEG and Eye-Tracking Evidence That AI Disclosure Shapes Face Evaluation

**链接**: https://arxiv.org/abs/2610.10182
**作者**: Teodora Mitrevska, Luise Donat, Andreas Butz, Thomas Kosch, Abdallah El Ali, Francesco Chiossi
**来源**: cs.HC cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-generated faces can be difficult to distinguish from real ones, leaving viewers to rely on source labels when judging an image. Yet prior work has made it difficult to separate the effects of what an image actually is from what viewers are told it is. We validated faces as AI-generated or human in an online study (N=169), then crossed actual source (AI, human) with label (none, Made with AI, Made by a human) in a lab study $N=30), recording event-related potentials (ERPs) and gaze. ERP responses were equivalent for AI-generated and real faces, but varied with the label: labels drew early attention (N2), while labels that conflicted with the face's actual source prompted re-evaluation of the face (P3). Affective processing and initial gaze orienting were unchanged, but labels altered visual exploration. We provide a validated stimulus set and evidence that attributed origin shapes face processing, with implications for disclosure design.

---

### [180] EEG Signatures Support a Shrinking Spotlight of Attention After Errors

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/abs/10.1111/psyp.70418&hl=zh-CN&sa=X&d=17089691664746022578&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVHn4qvCsO_BQVhQxln97M9Q&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: M Lavelle, A Fengler, A Zhang, JF Cavanagh - Psychophysiology, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Errors inhibit attainment of our goals, but there are many ways to get back on track: from increased caution to heightened attention. In this report we examined EEG signatures of control and perception in 21 participants who completed a luminance‐varying

---

### [181] How Aesthetic and Economic Factors Affect Consumers' Purchasing Decisions: Evidence from EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-328X/16/10/1819&hl=zh-CN&sa=X&d=5120866503635044684&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVEXK6jLpBgC7FPe0juU3Uaa&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: S Kong, H Li, H Fang - Behavioral Sciences, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Consumer theory identifies cultural and economic factors as key influences on purchasing decisions. Artworks, as material carriers of culture, are shaped by these factors in a particularly pronounced way. This study proposes that consumers’

---

### [182] Beyond processed depth targets: frontal EEG patterns, brain vulnerability, and postoperative delirium in older adults

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10877-026-01507-y&hl=zh-CN&sa=X&d=2776386847767504491&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVHqZjT1MXB5iJRastm8phsJ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: V Chauhan - Journal of Clinical Monitoring and Computing, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This review argues that the next step for limited-channel frontal EEG monitoring is not better targeting of dimensionless depth indices but disciplined interpretation of the raw EEG waveform, its spectral analysis, and the agent-specific EEG signatures

---

### [183] Recent Advances in Gel-Free Scalp EEG Electrodes: Materials, Structures, and Fixation Strategies

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2095809926005564&hl=zh-CN&sa=X&d=8767763675943627533&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVERm8Wlfhqrw1G0yZEu-Suf&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: D Yi, J Zhang, S Liu, Y Wang, Y Wang, W Pei - Engineering 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this review, the development of gel-free scalp electroencephalography ( EEG ) electrodes is summarized from three aspects: material selection, structural design, and head fixation strategies. The focus is on analyzing the role of these factors in

---

### [184] SPDAlign: Interpretable Riemannian Alignment for EEG Forward Modeling Shifts

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.06315&hl=zh-CN&sa=X&d=104522327950631559&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVHOYl-ockoMQl5OCcY2ssz0&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: S Li, S Chu, O Koç, C Liu, Q Zhao, M Kawanabe… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> drastically improve the utility of EEG data. In this work, we use a classic generative model of EEG to study distribution shifts introduced by the … Building on this insight, we propose SPDAlign, an interpretable framework for promoting domaininvariant

---

### [185] The Effects of Olfactory Stimulation on Convergent Thinking: Evidence Based on Resting-State EEG Microstates

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1871187126002634&hl=zh-CN&sa=X&d=16220343571559859963&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVF1qzMkY3nQs2fI34N5sTV0&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: Y Peng, Z Chen, S Xiao, T Wang - Thinking Skills and Creativity, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study investigated the effects of olfactory stimuli on convergent thinking from both behavior and neural activity perspectives. A total of 165 college students were randomly assigned to three groups: air (n=55), peppermint (n=55), and lavender-sweet

---

### [186] EEG emotion recognition via multilevel entropy analysis: The power of entropy of entropy on phase dynamics

**链接**: https://scholar.google.com/scholar_url?url=https://journals.plos.org/plosone/article%3Fid%3D10.1371/journal.pone.0329598&hl=zh-CN&sa=X&d=12663684843701053091&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVE0EM6ixvuB9ewYIVEZNde7&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: M Jafari Malali, S Zolfaghari, R Davoodi - PLoS One, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study introduces a novel application of Entropy of Entropy (EoE) to EEG phase series (… Using the GAMEEMO dataset, which includes EEG recordings from 28 participants during … This study provides the first systematic evaluation of EoE

---

### [187] A Proof-of-Concept Study of Weakly Supervised Labeling of Fine-Grained EEG Components for Artifact Attenuation

**链接**: https://arxiv.org/abs/2610.09792
**作者**: Lu Wang-N\"oth, Hai Huang, Philipp Heiler, Shuqiong Wu, Liyun Zhang, Helmut Mayer
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is highly susceptible to electromyographic (EMG) artifacts, whose temporal heterogeneity and spatial-spectral overlap with neural activity can leave mixed sources after blind source separation. Existing artifact-removal methods are further limited by scarce reliable component-level ground truth: expert annotations are costly and subjective, while no established method provides realistic simulation-based ground truth for EMG contamination in multichannel scalp EEG. To address these limitations, we propose a framework combining a frequency-aware high-dimensional representation with Multi-Instance Learning. The representation unfolds separated components into frequency-resolved intra-components, creating a space in which mixed neural and muscular activity becomes more separable, while the weakly supervised learning formulation enables artifact-likelihood scores for individual intra-components to be learned from epoch-level labels without finer-grained ground t

---

### [188] DenoFlow: Flow Matching for SSVEP Denoising under Real Physiological Artifacts

**链接**: https://arxiv.org/abs/2610.08817
**作者**: Zhentao He, Ziwei Wang, Dongrui Wu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG)-based brain-computer interfaces (BCIs), particularly steady-state visual evoked potential (SSVEP) systems, are highly vulnerable to noise and artifacts, which severely degrade decoding accuracy. Although recent denoising approaches have shown promise, they are fitted without paired ground truth, can settle on reproducing their input, and are optimized on waveform distance alone, which says nothing about whether the output stays decodable. To address these issues, we propose DenoFlow, which casts SSVEP denoising as transport: instead of learning a direct map from a contaminated trial to a clean one, a field network regresses the velocity of the straight path between them, following the rectified-flow formulation, and denoising integrates that field forward from the observation. The field network is an encoder-decoder that sees the contaminated trial at every layer and the path position at its bottleneck, and a classifier trained alongside it supervises the i

---

### [189] Mental health risk stratification using heart rate variability and prefrontal electroencephalography : eXtreme gradient boosting-based classifier and latent class analysis …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0165032726014448&hl=zh-CN&sa=X&d=15819008646565847133&ei=Z3fHatPeDPC96rQP1bi_iQQ&scisig=ACTRDVH0ZEIclQ8dqAbsE2JCeUHa&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=9&folt=kw-top
**作者**: JY Yun, G Kwon, M Shim, SM Kim, SH Lee, S Park - Journal of Affective Disorders 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Heart rate variability (HRV) and electroencephalography ( EEG ) are reflective of cardiac autonomic modulation/emotional regulation and cortical brain activity/psychopathology, respectively. This study aimed to determine the key HRV/prefrontal EEG classifiers

---

### [190] Evaluating Time Series Foundation Models for Electricity Price Forecasting: Contamination Risk, Distributional Shifts, and Covariate Dependence

**链接**: https://arxiv.org/abs/2607.02623
**作者**: Zhenghua Pan, Ahmed Aziz Ezzat
**来源**: cs.LG cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [191] RLHND: Video Foundation Models as Physically Grounded Hand Trackers for Robot Learning

**链接**: https://arxiv.org/abs/2610.09455
**作者**: Seungjun Moon, Subin Jeon, Sangwoo Kim, Hanbyul Joo, Jinwoo Shin
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, approaches that leverage human video datasets for robot policy training have become increasingly prevalent. However, most existing hand trackers regress pose from cropped frames with limited priors on hand motion and object interaction, resulting in inaccurate and physically inconsistent estimates. Moreover, the lack of physical cues, e.g., contact and force, limits the use of human videos for robot policy training. To this end, we propose RLHND, a video foundation model-based hand tracking model that jointly estimates hand pose and realistic tactile information from monocular egocentric videos. RLHND turns the pre-trained Cosmos 3 video diffusion backbone into a deterministic clip-level feature extractor via clean-latent conditioning, carrying its learned priors on hand motion and hand-object interaction into tracking. For pose estimation, RLHND (i) predicts hand poses with anatomically plausible joint angles and (ii) enables optional conditioning on the shape parameter to m

---

### [192] DisParQ: Self-Supervised Part Concepts for Interpretable Vision Foundation Models

**链接**: https://arxiv.org/abs/2610.09802
**作者**: Adam Pardyl, Siddhartha Gairola, Sukrut Rao, Adam Wr\'obel, Bartosz Zieli\'nski, Bernt Schiele 等 (7 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Concept-based vision models represent images through an intermediate layer of human-inspectable concepts, so what a model relies on can be traced to those concepts. However, those models are often limited to fixed categories or depend on language to define their concepts. We introduce DisParQ (Discrete Parts with Quantized attributes), a method that learns spatially grounded, discrete concept representations from a powerful frozen vision-only self-supervised backbone. It requires no class labels and no language supervision. Each image patch is assigned to exactly one concept from a learnable prototype dictionary, and only a sparse subset of concepts may activate per image. To capture how each concept varies across images (e.g., the type of a "wheel"), we learn continuous residuals alongside the concepts and then quantize them into discrete attributes. A spatial decoder reconstructs the backbone's representation from the concepts and attributes alone, so successful reconstruction means 

---

### [193] WxFM-XL: Adapting Univariate Foundation Models to Multi-Station Weather Forecasting

**链接**: https://arxiv.org/abs/2610.10057
**作者**: Xiao Wang, Changjian Chen, Zhuo Tang, Rongwen Li, Hongwu Liu, Kenli Li
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rise of univariate time series foundation models (e.g., Sundial, Timer), initial efforts have been made to extend them to multivariate settings. However, these models mainly focus on modeling correlations among variables. When they are applied to multi-station weather forecasting, two important factors are often overlooked: (1) the spatial information of stations, and (2) different error priors of different stations relative to the foundation model. In this paper, we propose WxFM-XL, a model for adapting univariate time series foundation models to multi-station weather forecasting. WxFM-XL introduces a cross-station error correlation prior graph to capture stationwise error priors with respect to the foundation model. Building on this, we further propose a dynamic fusion mechanism that adaptively integrates a spatial correlation graph with the error correlation prior graph. Experiments on multiple datasets demonstrate that our model outperforms state of the art baselines.

---

### [194] Backdooring Acoustic Foundation Models for Physically Realizable Triggers

**链接**: https://arxiv.org/abs/2610.09819
**作者**: Zebin Yun, Eyal Ronen, and Mahmood Sharif
**来源**: cs.SD cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Acoustic foundation models (AFMs) have democratized acoustic applications, enabling powerful models for tasks ranging from speech recognition to speaker verification with minimal resources. However, the security of applications based on AFMs remains largely underexplored. Our work addresses this gap by proposing the Foundation Acoustic model Backdoor (FAB) attack, demonstrating that state-of-the-art AFMs are susceptible to backdooring under practical settings. Despite making minimal assumptions about adversary capabilities (e.g., no access to pre-training data), we show that FAB preserves benign performance while inducing backdoors that survive fine-tuning and cause significant degradation across diverse downstream tasks when activated. Notably, FAB utilizes task-agnostic, physically realizable, inconspicuous, and sync-free triggers (e.g., a background siren). We evaluate FAB using two leading AFMs, nine downstream tasks, and four different triggers. We further demonstrate its effectiv

---

### [195] Pretraining Shapes Spectral Structure: Architecture- and Strategy-Conditional Prediction of OOD Robustness in Foundation Models

**链接**: https://arxiv.org/abs/2610.09709
**作者**: Sangyoon Bae, Sk Miraj Ahmed, Shinjae Yoo, Jiook Cha
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can we determine whether a foundation model will generalize out-of-distribution (OOD) before any target data is available? Existing diagnostics require source or target data, which rules them out before a target domain exists. Those that use the weights alone apply one statistic to every architecture, and do not separate robust models from fragile ones. We show the answer is encoded in the spectral structure of pretrained weights. Two forces shape that structure. Architecture determines how information is stored in weight matrices. Pretraining strategy determines what is rewarded. Together they set a spectral geometry that governs OOD robustness. We prove that the OOD accuracy gap is bounded by how tightly the source representations concentrate. A statistic computed from the pretrained weights alone serves as a proxy for that concentration. The direction of that proxy reverses between architecture families. We operationalize it: the direction is stable within one (architecture X strate

---

### [196] One-Slide Calibration of Pathology Foundation Models

**链接**: https://arxiv.org/abs/2610.08944
**作者**: Ming Ren Hou, Tianyi Huang
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scanner variation changes how pathology foundation models represent the same tissue. We introduce SlideRuler, which uses regions within a slide as internal controls to estimate and correct acquisition-induced shifts in other regions. A transfer map learned from paired rescans enables calibration from a single scan at inference while keeping the foundation model fixed. Across two encoders and five SCORPION scanners, learned transfer reduces mean target-to-source embedding distance by 16.3-38.5% relative to raw embeddings. Comparisons with unrelated same-scanner controls reveal a positive same-slide contribution across all four evaluation settings, including scanner holdout. A source-anchored variant reduces source-feature displacement by 47.7-83.6% relative to learned transfer while retaining most of its alignment gain. By drawing calibration information from the slide itself, SlideRuler offers a path toward more consistent use of frozen pathology models across imaging systems.

---

### [197] BehaviorBench: Benchmarking Foundation Models for Behavioral Science Tasks

**链接**: https://arxiv.org/abs/2606.24162
**作者**: Jin Huang, Yutong Xie, Wanli Song, Xingjian Zhang, Walter Yuan, Matthew O. Jackson 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [198] Fault-tolerant foundation models

**链接**: https://arxiv.org/abs/2610.10311
**作者**: Trevor McCourt, Ila R. Fiete, Isaac L. Chuang
**来源**: cs.LG cs.AI cs.AR
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emerging computer hardware often trades reliability for energy efficiency; here we show that large-language models (LLMs) can be trained to tolerate this unreliability, and that rather than degrading, their error resilience actually increases as they grow. Modified neural scaling laws inferred from 40,000 GPU-hours of training runs on simulated faulty digital hardware quantify this trend and suggest that models learn to compute within "good" error-correcting codes, whose relative overhead remains finite no matter how large the model gets. This finding leads us to conjecture that appropriately trained LLMs may be formally fault-tolerant; if true, running AI inference on low energy, faulty hardware may be a path to substantial energy savings over the status quo.

---

### [199] SAREO-FM: Decoupled Semantic Supervision for SAR-EO Foundation Models

**链接**: https://arxiv.org/abs/2610.09317
**作者**: Jeonghyeok Do, Munchurl Kim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic aperture radar (SAR) and electro-optical (EO) imagery provide complementary observations: SAR enables day-and-night, weather-resilient sensing, whereas EO provides rich appearance and fine-grained semantic cues. We introduce SAREO-FM, which avoids forcing a single token stream to serve two distinct roles: modality tokens preserve how each sensor observes the scene through masked reconstruction, while learnable semantic queries capture what the scene contains under guidance from a pretrained vision foundation model (VFM). By jointly encoding these queries with SAR and EO tokens, the queries acquire modality-grounded semantic context, while the modality-token outputs remain the explicit targets of masked reconstruction. This design assigns semantic and reconstruction supervision to separate token streams while preserving their interaction within the shared encoder. Pretrained on the million-scale SAR-1M corpus, SAREO-FM achieves strong unimodal transfer for both SAR-only and EO

---

### [200] HarnessIR: Harnessing Multimodal Foundation Models for Universal Real-World Image Restoration

**链接**: https://arxiv.org/abs/2610.10133
**作者**: Xiangtao Kong, Shuaizheng Liu, Rongyuan Wu, Lingchen Sun, Zhengqiang Zhang, Jinxin Zhao 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world low-quality images suffer from complex mixed degradations, including but not limited to noise, blur, atmospheric effects, etc. Recent agentic methods usually model real-world image restoration (Real-IR) as a sequential tool calling problem over task-specific single-degradation restoration models. This paradigm, however, is fundamentally limited because complex real-world degradations cannot be cleanly undone degradation by degradation, and the tool used for task-specific models caps the capability of the agent system. In this work, we present HarnessIR, an agentic framework for Real-IR by harnessing a multimodal foundation model (MFM) as the executor. HarnessIR consists of five stages: perception and diagnosis, on-demand tool invocation, prompt composition, execution, and verification-driven refinement. Unlike prior agentic Real-IR methods that rely on tool chains assembled from task-specific models, HarnessIR feeds the restoration requirements, the perceptual diagnosis, and

---

### [201] Thinking in Depth: Retrospective Inference for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.10317
**作者**: Hao-Run Cai, Si-Yang Liu, Zi-Jian Cheng, Kun-Yang Yu, Jin-Hao Sheng, Guo Yu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are pretrained across diverse tabular tasks and make predictions on a new table at inference time using its labeled examples as context. Most recent TFMs perform such in-context prediction with stacked Transformer layers, repeatedly transforming how examples are represented and compared. By tracing individual queries through several strong TFMs, we find that predictive refinement is highly uneven across depth and is often concentrated in later layers. This uneven refinement motivates us to reconsider how intermediate representations are constructed and reused throughout the network. We introduce Retro, a tabular foundation model based on retrospective inference, where later stages can explicitly revisit and recombine intermediate information produced earlier in the network. Retro organizes this process around two complementary operations: which intermediate information to revisit, and how the resulting contextual update should be shaped for each query. 

---

### [202] Quantifying Volumetric Risk: Class-Aware Asymmetric Weighted Conformal Prediction for 3D Medical Image Segmentation

**链接**: https://arxiv.org/abs/2610.09392
**作者**: Shadi Alijani, Fereshteh Aghaee Meibodi, Homayoun Najjaran
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable volumetric segmentation is critical for clinical diagnostics, yet foundation models such as MedSAM remain deterministic and lack calibrated uncertainty under distribution shift. Existing conformal prediction methods offer statistical guarantees but are frequently applied in 2D and assume symmetric error distributions, so they do not capture the class-specific biases that arise in 3D multi-class segmentation. We propose Class-Aware Asymmetric Weighted Conformal Prediction (CA-WCP), which combines latent-space density-ratio weighting for covariate shift with directional quantiles for the lower and upper volume bounds, and scales each bound by a class-specific asymmetry factor derived from validation-set false-positive and false-negative rates. We prove that CA-WCP retains the weighted-exchangeability marginal coverage guarantee for every class, and we evaluate it on 3D brain tumor segmentation (BraTS 2020) and on a synthetic multi-organ CT benchmark constructed under covariate s

---

### [203] One-Shot Adaptive Segmentation For Scientific Images

**链接**: https://arxiv.org/abs/2610.10306
**作者**: Tejaswi V. Panchagnula, Allison M. Davis, Fengqing Zhu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific image segmentation methods rely on extensive annotation and task-specific training, limiting adaptation across imaging modalities and experimental conditions. We present a training-free, one-shot framework that specializes vision foundation models using a single annotated reference image. The framework combines DINOv3 representations with background-adaptive feature orthogonalization to suppress artifact-related feature directions, after which cosine similarity localizes candidate regions for SAM segmentation. We evaluate the framework on red-blood-cell microscopy, structured-illumination pool boiling, and chest radiography. Relative to the strongest baseline, the proposed method improves mean IoU by 5.91% and 78.62% on the microscopy and pool-boiling datasets, respectively, while achieving comparable performance on chest radiographs. These results demonstrate that one-shot reference conditioning can adapt general-purpose vision models to specialized scientific segmentation 

---

### [204] Performance at What Cost? A Sustainability-Aware Performance Index for Cell and Nucleus Instance Segmentation

**链接**: https://arxiv.org/abs/2610.10324
**作者**: Eiram Mahera Sheikh, Alaa Tharwat, Wolfram Schenck
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained models for cell and nuclear instance segmentation differ substantially in architecture, pretraining data and objectives, parameter count, inference strategy, adaptation requirements, postprocessing pipeline, and computational demand. Large pretrained and foundation models are increasingly adopted because of their strong zero-shot capabilities, but their use also imposes greater energy consumption, memory requirements, computational demands, adaptation costs, and operational carbon emissions. Whether these additional demands are justified by meaningful gains in segmentation performance remains unclear. We address this question by introducing the Sustainability-Aware Performance Index (SAPI), a configurable metric that combines segmentation performance, energy consumption, and model size. We benchmark 19 pretrained and foundation models across six CellBinDB datasets under zero-shot inference and evaluate 16 fine-tunable models using few-shot adaptation with both frozen encoder

---

### [205] Transferability and operational reliability of a Prithvi crop classification foundation model under phenological and geographic shift across three continents

**链接**: https://arxiv.org/abs/2610.08810
**作者**: Venkatesh Kolluru, Rajat Shinde, Abdelhak Marouane, Caden Helbling, Deepak Shah, Othneil Drew 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuned geospatial foundation models (GeoFMs) pretrained on large satellite archives have been shown to improve crop classification accuracy and geographic transferability. However, their operational performance beyond the training distribution remains poorly characterized. We evaluated the out-of-distribution performance of a widely adopted GeoFM [Prithvi-EO-2.0] across 37 events in 12 countries on three continents and validated against regional reference products. Results indicated that the mean overall accuracy (OA) declined from 0.65 in the United States to 0.40 in Europe. Beyond accuracy metrics, we assessed five key aspects of model performance: whether model confidence indicates signal failure, sensitivity to observation windows, the effect of coarsening class schemes, and robustness to both band loss and cloud- and shadow-contamination. Accuracy collapsed when the observation window misaligned with local crop phenology, while deterministic confidence remained high. Expected 

---

### [206] EmbodiedRSI: Active Continual Robot Learning Through Hypothesis-Guided Co-Evolution

**链接**: https://arxiv.org/abs/2610.10498
**作者**: Python Song, Zhixuan Liang, Kelsey Fu, Mengdi Wang, Junfeng Yang, Shilong Liu
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models provide strong visuomotor control, yet their performance can degrade when object positions or task instructions change. Further improvements often require post-training on substantial robot data, which can be costly to collect through methods such as teleoperation. Agentic harnesses can adapt around the model, but current self-evolving harnesses use robot trials inefficiently when deciding which code and skill changes to pursue. We introduce EmbodiedRSI, a self-evolving agentic harness that autonomously decides where to explore next and turns the resulting physical interaction into improved code and skills. EmbodiedRSI realizes this through a Fast-Slow Dual-System Architecture, in which competing code and skill hypotheses are maintained in a Hypothesis Graph. Value-of-Information Experiment Selection chooses physical experiments that can distinguish these hypotheses. Their outcomes guide Code-Skill Co-Evolution. The Slow System builds Hierarchical Memory, and Re

---

### [207] RDGSplat: Render-Dedicated Geometry for Novel View Synthesis

**链接**: https://arxiv.org/abs/2610.09173
**作者**: Zhijie Zheng, Xinhao Xiang, Jiawei Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D foundation models enable efficient novel view synthesis by carrying a Gaussian head on the representation they already use for reconstruction. However, the views they render fall short of the geometry they recover, because that geometry is estimated under a metric objective and never scored on how it renders. Recent methods alleviate this by updating the backbone weights, but they thereby discard the metric predictions the model was built for and must be repeated for every new backbone. To this end, we propose RDGSplat, a framework that decodes a second geometry dedicated to rendering from a frozen 3D foundation model, leaving its metric predictions intact. In particular, we devise Render-Dedicated Geometry Decoding, which duplicates the pretrained decoders and optimizes the duplicates under photometric supervision alone. Then, a Target-Pose Conditioned Adapter is introduced to reformulate the representation those decoders read, conditioned on the target camera pose rather than the 

---

### [208] Do Better Visual Representations Always Lead to Better End-to-End Autonomous Driving?

**链接**: https://arxiv.org/abs/2610.09695
**作者**: Zihao Zhang, Haochen Tian, Tianyu Li, Changhui Jing, Jingliang He, Naisheng Ye 等 (8 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual foundation models (VFMs) are increasingly integrated into end-to-end autonomous driving for their powerful representations, yet it remains unclear when these representations improve driving performance. To investigate this question, we introduce ViRA, a planner-agnostic visual representation alignment framework that keeps the planner architecture and inference cost unchanged. Our study reveals three findings: (1) VFM-guided visual representations consistently improve driving performance across diverse end-to-end planners, with gains extending to zero-shot closed-loop evaluation. (2) The choice of VFM target matters for planning performance, and alignment to a different VFM can further benefit planners with pre-trained VFM encoders. (3) Auxiliary perception supervision reduces sensitivity to VFM target selection, narrowing the EPDMS spread across five targets from 2.7 to 0.5 points and potentially compensating for less effective VFM targets. Guided by these findings, we develop V

---

### [209] Sequential Pretraining Favors Large Models

**链接**: https://arxiv.org/abs/2610.09611
**作者**: Mohnish Harwani and Yujia Zheng
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large neural networks often acquire capabilities that small models fail to learn. Does this stem from large models learning more representative features, or from being more robust to unaccounted-for adverse effects introduced during training? We define and quantify one such adverse effect, primacy bias, as the extent to which exposure to early data distributions impairs later learning. We show that small models can allocate learning capacity inefficiently toward early distributions, whereas sufficiently overparameterized models are robust to this effect. This inefficiency is particularly consequential in pretraining, where foundation models often encounter heterogeneous data distributions sequentially rather than jointly. As a result, small foundation models can struggle to learn distributions encountered late in training, which is particularly harmful when later data emphasizes desirable capabilities such as code, mathematics, and reasoning. Motivated by these findings, we introduce E

---

### [210] Efficient Provably Private Classification with a Tabular Foundation Model

**链接**: https://arxiv.org/abs/2610.10068
**作者**: Talal Alrawajfeh, Cristiana Diaconu, Ossi R\"ais\"a, Sebastian Rodriguez Beltran, Yuan He, John Bronskill 等 (8 人)
**来源**: cs.LG cs.CR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular data underpin prediction and decision-making in medicine, finance, government and science, but often contain sensitive individual-level information, creating a need for accurate prediction while preserving privacy. Traditional private learning provides formal privacy guarantees, but requires slow dataset-specific optimisation, suffers substantial utility loss under strong privacy, and is often difficult to apply correctly. Tabular foundation models adapt rapidly to new datasets, but existing models lack formal privacy guarantees, and are highly vulnerable to membership-inference attacks, limiting their use on sensitive data. Here we introduce PrivTab, an easy to use tabular foundation model for differentially private classification that embeds a privacy mechanism within its architecture. Pretrained on simulated datasets, PrivTab uses in-context learning to transform sensitive rows into compact, provably private summaries---effectively learning how to learn under privacy. PrivTa

---

### [211] RoboQuest: Generalist Physical Agents that Search, Inspect and Test

**链接**: https://arxiv.org/abs/2610.10388
**作者**: Liu Renhang, Navonil Majumder, Tej Deep Pala, Soujanya Poria
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models have made them capable generalist physical agents for a range of manipulation tasks. However, successful operation in an unfamiliar environment may require an agent to seek task-relevant information through interaction when it is absent from the observations: it may need to determine where a relevant object is, inspect an unobserved property, or discover the effect of an unfamiliar tool. We thus introduce RoboQuest, a benchmark for goal-directed embodied exploration, where agents must actively acquire task-relevant information through physical interaction, use the resulting evidence to adapt subsequent actions, and autonomously decide when to commit to task completion. RoboQuest comprises ten mobile manipulation tasks centered on three forms of uncertainty: search, manipulation-based inspection, and interactive testing. We evaluate five frontier multimodal agents through a common visuomotor interface, as well as a $\pi_{0.5}$ policy fine-

---

### [212] Argos: Adapt Rich Geometric Priors for Generalizable Online Scene-Change-Detection

**链接**: https://arxiv.org/abs/2610.10181
**作者**: Ruihan Xu, Jiae Yoon, Kaichen Zhou, Ue-Hwan Kim, Luca Carlone
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robots operating in dynamic environments require reliable detection of how their surroundings change over time. Existing learning-based methods largely rely on pairwise 2D image features, which struggle under large viewpoint changes and occlusions, are sensitive to noise, and show limited generalization across domains, while explicit 3D approaches typically require costly offline optimization. We show that the implicit 3D knowledge of Geometric Foundation Models (GFMs) provides a strong basis for addressing these limitations. We introduce Argos, which adapts GFM features for joint scene change detection and 3D reconstruction. To address data scarcity and take a step toward a foundation model for scene change detection, we introduce a large-scale benchmark comprising two synthetic datasets and one real-world dataset, and train jointly across diverse datasets to improve cross-domain generalization. We further introduce Argos-SLAM, a real-time system designed for robotics, which performs 

---
